# Comparing `tmp/pybrick-0.2.4-py3-none-any.whl.zip` & `tmp/pybrick-0.2.5-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,8 +1,8 @@
-Zip file size: 4754 bytes, number of entries: 6
+Zip file size: 5457 bytes, number of entries: 6
 -rw-rw-rw-  2.0 fat        0 b- defN 22-Jun-30 13:40 pybrick/__init__.py
--rw-rw-rw-  2.0 fat    10069 b- defN 23-Jun-12 20:01 pybrick/pybrick.py
--rw-rw-rw-  2.0 fat      321 b- defN 23-Jun-12 20:07 pybrick-0.2.4.dist-info/METADATA
--rw-rw-rw-  2.0 fat       92 b- defN 23-Jun-12 20:07 pybrick-0.2.4.dist-info/WHEEL
--rw-rw-rw-  2.0 fat        8 b- defN 23-Jun-12 20:07 pybrick-0.2.4.dist-info/top_level.txt
-?rw-rw-r--  2.0 fat      445 b- defN 23-Jun-12 20:07 pybrick-0.2.4.dist-info/RECORD
-6 files, 10935 bytes uncompressed, 3946 bytes compressed:  63.9%
+-rw-rw-rw-  2.0 fat    12398 b- defN 23-Jun-28 15:38 pybrick/pybrick.py
+-rw-rw-rw-  2.0 fat      321 b- defN 23-Jun-28 15:43 pybrick-0.2.5.dist-info/METADATA
+-rw-rw-rw-  2.0 fat       92 b- defN 23-Jun-28 15:43 pybrick-0.2.5.dist-info/WHEEL
+-rw-rw-rw-  2.0 fat        8 b- defN 23-Jun-28 15:43 pybrick-0.2.5.dist-info/top_level.txt
+?rw-rw-r--  2.0 fat      445 b- defN 23-Jun-28 15:43 pybrick-0.2.5.dist-info/RECORD
+6 files, 13264 bytes uncompressed, 4649 bytes compressed:  65.0%
```

## zipnote {}

```diff
@@ -1,19 +1,19 @@
 Filename: pybrick/__init__.py
 Comment: 
 
 Filename: pybrick/pybrick.py
 Comment: 
 
-Filename: pybrick-0.2.4.dist-info/METADATA
+Filename: pybrick-0.2.5.dist-info/METADATA
 Comment: 
 
-Filename: pybrick-0.2.4.dist-info/WHEEL
+Filename: pybrick-0.2.5.dist-info/WHEEL
 Comment: 
 
-Filename: pybrick-0.2.4.dist-info/top_level.txt
+Filename: pybrick-0.2.5.dist-info/top_level.txt
 Comment: 
 
-Filename: pybrick-0.2.4.dist-info/RECORD
+Filename: pybrick-0.2.5.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## pybrick/pybrick.py

```diff
@@ -1,72 +1,123 @@
+__doc__="""
+pybrick uses sqlalchemy to provide a convenient connection to Yellowbrick.
+"""
+import pdb
 import os
 import sys
 import subprocess
 import tempfile
 import sqlalchemy as sa
+from sqlalchemy.dialects.postgresql.base import PGDialect
 import pandas as pd
+import socket
 
 
 class YbConnector:
     """ A pytezza-esque connector to Yellowbrick. """
-    def __init__(self,host,db,user,pw="",psql_compatible_version='13.7'):
+    def __init__(self,host,db,user,pw="",psql_compatible_version='13.7',ybhosts=None):
         """ """
-        self.host=host
+        self.host=self._resolveHost(host,ybhosts)
         self.db=db
         self.user=user
-        
-        self.pw=pw
-        if not pw:
-          self.pw=os.environ.get('YBPASSWORD')
+        self.pw=pw if pw else os.environ.get('YBPASSWORD')
         
         self.psql_compatible_version=psql_compatible_version
         self.dry_run_mode=False
         self.engine=None
         self.connection=self.getConnection()
     
+    
+    def _resolveHost(self,host,ybhosts,check_only=False):
+        """ ybhosts may be a dict (with hosts at keys and IPs as values), or a file where
+            each line contains a hostname, and then a space, and then the IP.
+        """
+        #If we resolve the host right away, great.
+        try:
+            _=socket.getaddrinfo(host,0,0,0,0)
+            return host
+        except socket.gaierror as d:
+            print("Yellowbrick host resolution failed:",d)
+            if check_only:
+                return None
+        
+        if not ybhosts:
+            print("No ybhosts provided.")
+            return None
+        
+        #If DNS resolution fails try ybhosts.
+        #If it's a dict, just do a blind get.
+        if type(ybhosts)==dict:
+            h=ybhosts.get(host)
+            return self._resolveHost(h,None,True)
+        
+        #If it's not a dict, try it as a file.
+        try:
+            if os.path.isfile(ybhosts):
+                ybhosts=self._getHosts(ybhosts)
+                h=ybhosts.get(host)
+                return self._resolveHost(h,None,True)
+        except Exception as e:
+            print("Unable to parse ybhosts:",e)
+        
+        print("Could not resolve Yellowbrick host:",host)
+        return None
+    
+    
+    def _getHosts(self,ybhosts):
+        """ """
+        lu={}
+        with open(ybhosts,'r') as h:
+            for line in h.readlines():
+                hname,ip=line.split(" ")[0:2]
+                lu[hname.strip()]=ip.strip()
+        return lu
+    
     def __del__(self):
         if hasattr(self,"connection"):
             try:
                 self.disconnect()
             except:
                 pass
         return
     
     def __repr__(self):
         """ """
         stat="CONNECTED"
         try:
-            self.connection.execute("select 1")
+            self.connection.execute(sa.text("select 1"))
         except:
             stat="DISCONNECTED"
             
         return(f"Yellowbrick connector for user {self.user} on host {self.host}.\n{stat}")
     
     def _checkConnection(self,reconnect=False):
         """ When using psycopg2 interactively, it's not unusual for the db
             connection to become invalid due to idle timeout.  Before issuing
             a query, check the connection and optionally reconnect if needed.
         """
         try:
-            self.connection.execute("select 1")
+            self.connection.execute(sa.text("select 1"))
         except Exception as e:
             if reconnect:
                 self.disconnect()
                 self.connection=self.getConnection()
             else:
                 raise Exception("Connection problem: %s"%e, sys.exc_info()[2])
-        
+    
     def getEngine(self):
         """ """
         self._checkConnection()
         return self.engine
     
     def getConnection(self):
         """ """
-        from sqlalchemy.dialects.postgresql.base import PGDialect
+        if not self.host:
+            sys.exit(1)
+        
         psql_vinfo=tuple([int(x) for x in self.psql_compatible_version.split(".")])
         PGDialect._get_server_version_info = lambda *args:psql_vinfo
         
         connection_url = sa.engine.URL.create(
             drivername="postgresql+psycopg2",
             username=self.user,
             password=self.pw,
@@ -77,15 +128,15 @@
         try:
             self.engine=sa.create_engine(connection_url,pool_pre_ping=True)
             conn=self.engine.connect().execution_options(isolation_level="AUTOCOMMIT")
             return conn
         except Exception as details:
             print("Error connecting using:",(self.host,self.db,self.user,self.pw))
             print(">>> ",details)
-            sys.exit()
+            sys.exit(1)
     
     def disconnect(self):
         """ """
         if self.connection:
             self.connection.close()
         return
     
@@ -118,20 +169,20 @@
         #In case of a conflict, err on the side of returning data.
         withData=max(withResults,withData)
         
         #Connect and execute, with or without returning results.  If there's a problem
         #print the details, and always close the connection.
         try:
             if withData:
-                df=pd.read_sql(query_to_run,self.getEngine())
+                df=pd.read_sql(sa.text(query_to_run),self.getEngine())
             else:
-                self.connection.execute(query_to_run)
+                self.connection.execute(sa.text(query_to_run))
         except Exception as d:
             print("There was an error while executing the SQL:\n",d)
-            sys.exit()
+            sys.exit(1)
         
         return df
     
     def tableExists(self,table):
         """ """
         (db,tbl)=table.split(".")
         q=f"""
@@ -173,15 +224,14 @@
         return ddl
 
     def dfToYb(self,src,target,distribute_on="random",clobber=False,ybTypes=None,verbose=False,ignoreLoadErrors=False):
         """ Given a pandas df, push that table to yellowbrick, optionally replace the existing table in yellowbrick.
             If ybTypes immutable is provided, use those types and to hell with the consequences.
             Otherwise, infer the types.
         """
-        
         def vprint(s):
             if verbose:
                 print(s)
         
         print(f"Loading {src.shape[0]} rows and {src.shape[1]} columns into {target}.")
         vprint(f"Here is a sample of the source data:\n{src.head(5)}")
         
@@ -197,34 +247,50 @@
         if ignoreLoadErrors:
             maxbad="-1"
         
         ddl = self.getDfDDL(src,ybTypes)
         
         dump=tempfile.mkstemp(".csv")[1]
         vprint(f"Dumping local data to {dump}")
-        src.to_csv(dump,index=False,header=True,lineterminator="\n")
+        src.to_csv(dump,index=False,header=True,line_terminator="\n")
         vprint(f"Dumped {os.path.getsize(dump)/1024/1024:0.2f}MB.")
         
         if not self.tableExists(target):
             self.execute(f"""
                 create table {target} (
                     {ddl}
                 )
                 ;
             """,printQuery=verbose)
         
         os.environ["YBPASSWORD"]=self.pw
-        cmd=rf'"C:\Program Files\Yellowbrick Data\Client Tools\bin\ybload.exe" --host {self.host} --username {self.user} --dbname {self.db} --max-bad-rows {maxbad} --csv-skip-header-line true --table {target} {dump}'
-        vprint(f"Running this now ===> {cmd}")
+        
+        if sys.platform=='win32':
+            ybin=r"C:\Program Files\Yellowbrick Data\Client Tools\bin\ybload.exe"
+        else:
+            ybin="ybload"
+        
+        #You could also have run this with .call(cmd,shell=True):
+        #cmd=rf'{ybin} --host {self.host} --username {self.user} --dbname {self.db} --max-bad-rows {maxbad} --csv-skip-header-line true --table {target} {dump}'
+        cmd=[ybin,
+             '--host',self.host,
+             '--username',self.user,
+             '--dbname',self.db,
+             '--max-bad-rows',maxbad,
+             '--csv-skip-header-line','true',
+             '--table',target,
+             dump
+        ]
+        vprint(f"Running this now ===> {' '.join(cmd)}")
         
         try:
-            _=subprocess.call(cmd)
+            res=subprocess.run(cmd,capture_output=True,check=True)
         except Exception as details:
             print(f"There was a problem running ybload.  Make sure it's installed, is on your PATH, and that Java is installed:\n{details}\n")
-            sys.exit(1)
+            sys.exit(res.returncode)
         
         lrows = self.tableRowCount(target)
         if len(src)==lrows or clobber==False:
             print("YBload successful")
             vprint(f"Dumped {len(src)} rows, and then loaded {lrows} rows.")
         else:
             print("THERE MIGHT HAVE BEEN A PROBLEM LOADING!  The number of rows loaded doesn't match the input length.  Check the output.")
@@ -246,37 +312,38 @@
         ybtypes = []
         for t in df.dtypes:
             ybtypes.append(df2yb.get(t.name,default_yb))
         return(tuple(ybtypes))
 
 
 
-def test(timeouttest=False):
+def test(timeout_minutes=0.1):
     """ """
-    YB = YbConnector("ybr-01.eyc.com","dbo","clevis")
+    import time
+    YB = YbConnector("ybr-01.eyc.com","dbo","cl2")
     tt = "geatstanl.cjl_test"
     if YB.tableExists(tt):
         print(f"{tt} already exists.  Dropping.")
-        YB.query(f"drop table {tt}")
+        YB.execute(f"drop table {tt}")
     
-    YB.query(f"create table {tt} as select 1 one,current_timestamp as ts")
-    d=YB.query("select * from %s"%tt,withData=True)
+    YB.execute(f"create table {tt} as select 1 one,current_timestamp as ts")
+    d=YB.query("select * from %s"%tt)
     print(type(d))
     print(d)
     
-    data=pd.read_csv(r"C:\temp\ptest.csv")
+    data=pd.read_csv(r"ptest.csv")
     YB.dfToYb(data,"geatstanl.cjltest",clobber=True)
-    d=YB.query("select * from geatstanl.cjltest",withData=True)
+    d=YB.query("select * from geatstanl.cjltest")
     d.head()
     print(len(d))
     
-    if timeouttest:
-        import time
-        mins=12
-        print(f"Make some tea.  This will run for {mins} minutes.")
-        time.sleep(mins*60)
-        print(YB.query("select current_timestamp",withData=True))
-    
+    print(f"Make some tea.  This will run for {timeout_minutes} minutes.")
+    time.sleep(float(timeout_minutes)*60)
+    print(YB.query("select current_timestamp"))
+    print("Test complete.")
+    return True
 
 if __name__=="__main__":
-    pass
-
+    """ """
+    if len(sys.argv)>1:
+       test(timeout_minutes=sys.argv[1])
+
```

