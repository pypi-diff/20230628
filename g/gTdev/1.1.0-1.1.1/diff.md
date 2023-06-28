# Comparing `tmp/gTdev-1.1.0.tar.gz` & `tmp/gTdev-1.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "gTdev-1.1.0.tar", last modified: Wed Jun 28 09:10:31 2023, max compression
+gzip compressed data, was "gTdev-1.1.1.tar", last modified: Wed Jun 28 09:12:10 2023, max compression
```

## Comparing `gTdev-1.1.0.tar` & `gTdev-1.1.1.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 09:10:31.169007 gTdev-1.1.0/
--rw-rw-rw-   0        0        0     1091 2022-12-02 07:39:30.000000 gTdev-1.1.0/LICENSE
--rw-rw-rw-   0        0        0      123 2023-04-19 01:59:01.000000 gTdev-1.1.0/MANIFEST.in
--rw-rw-rw-   0        0        0     7464 2023-06-28 09:10:31.168007 gTdev-1.1.0/PKG-INFO
--rw-rw-rw-   0        0        0     7041 2023-06-28 09:09:36.000000 gTdev-1.1.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 09:10:31.141008 gTdev-1.1.0/gTdev/
--rw-rw-rw-   0        0        0      129 2023-05-22 03:09:44.000000 gTdev-1.1.0/gTdev/__init__.py
--rw-rw-rw-   0        0        0     2548 2023-05-22 02:15:58.000000 gTdev-1.1.0/gTdev/gtInv.py
--rw-rw-rw-   0        0        0     2957 2023-06-28 02:26:44.000000 gTdev-1.1.0/gTdev/gtcurve.py
--rw-rw-rw-   0        0        0      187 2023-05-16 06:36:50.000000 gTdev-1.1.0/gTdev/gtdevCommon.py
--rw-rw-rw-   0        0        0     1561 2023-05-24 00:29:00.000000 gTdev-1.1.0/gTdev/gtfile.py
--rw-rw-rw-   0        0        0     4205 2023-06-28 02:33:49.000000 gTdev-1.1.0/gTdev/gtmos.py
-drwxrwxrwx   0        0        0        0 2023-06-28 09:10:31.165010 gTdev-1.1.0/gTdev.egg-info/
--rw-rw-rw-   0        0        0     7464 2023-06-28 09:10:30.000000 gTdev-1.1.0/gTdev.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      256 2023-06-28 09:10:30.000000 gTdev-1.1.0/gTdev.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 09:10:30.000000 gTdev-1.1.0/gTdev.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        6 2023-06-28 09:10:30.000000 gTdev-1.1.0/gTdev.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 09:10:31.169007 gTdev-1.1.0/setup.cfg
--rw-rw-rw-   0        0        0      689 2023-06-28 09:10:14.000000 gTdev-1.1.0/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:12:10.006076 gTdev-1.1.1/
+-rw-rw-rw-   0        0        0     1091 2022-12-02 07:39:30.000000 gTdev-1.1.1/LICENSE
+-rw-rw-rw-   0        0        0      123 2023-04-19 01:59:01.000000 gTdev-1.1.1/MANIFEST.in
+-rw-rw-rw-   0        0        0     7464 2023-06-28 09:12:10.004089 gTdev-1.1.1/PKG-INFO
+-rw-rw-rw-   0        0        0     7041 2023-06-28 09:09:36.000000 gTdev-1.1.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 09:12:09.982073 gTdev-1.1.1/gTdev/
+-rw-rw-rw-   0        0        0      129 2023-05-22 03:09:44.000000 gTdev-1.1.1/gTdev/__init__.py
+-rw-rw-rw-   0        0        0     2548 2023-05-22 02:15:58.000000 gTdev-1.1.1/gTdev/gtInv.py
+-rw-rw-rw-   0        0        0     2957 2023-06-28 02:26:44.000000 gTdev-1.1.1/gTdev/gtcurve.py
+-rw-rw-rw-   0        0        0      187 2023-05-16 06:36:50.000000 gTdev-1.1.1/gTdev/gtdevCommon.py
+-rw-rw-rw-   0        0        0     1868 2023-06-28 08:56:21.000000 gTdev-1.1.1/gTdev/gtfile.py
+-rw-rw-rw-   0        0        0     4609 2023-06-28 08:23:36.000000 gTdev-1.1.1/gTdev/gtmos.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:12:10.001076 gTdev-1.1.1/gTdev.egg-info/
+-rw-rw-rw-   0        0        0     7464 2023-06-28 09:12:09.000000 gTdev-1.1.1/gTdev.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      256 2023-06-28 09:12:09.000000 gTdev-1.1.1/gTdev.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 09:12:09.000000 gTdev-1.1.1/gTdev.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 09:12:09.000000 gTdev-1.1.1/gTdev.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 09:12:10.007075 gTdev-1.1.1/setup.cfg
+-rw-rw-rw-   0        0        0      689 2023-06-28 09:11:39.000000 gTdev-1.1.1/setup.py
```

### Comparing `gTdev-1.1.0/LICENSE` & `gTdev-1.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `gTdev-1.1.0/PKG-INFO` & `gTdev-1.1.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gTdev
-Version: 1.1.0
+Version: 1.1.1
 Summary: 高效碳基测试运算模块
 Home-page: https://gitee.com/lxwk1spectre/gdevsample
 Author: Spectre Lee
 Author-email: lxwk1spectre@foxmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `gTdev-1.1.0/README.md` & `gTdev-1.1.1/README.md`

 * *Files identical despite different names*

### Comparing `gTdev-1.1.0/gTdev/gtInv.py` & `gTdev-1.1.1/gTdev/gtInv.py`

 * *Files identical despite different names*

### Comparing `gTdev-1.1.0/gTdev/gtcurve.py` & `gTdev-1.1.1/gTdev/gtcurve.py`

 * *Files identical despite different names*

### Comparing `gTdev-1.1.0/gTdev/gtfile.py` & `gTdev-1.1.1/gTdev/gtfile.py`

 * *Files 25% similar despite different names*

```diff
@@ -8,14 +8,18 @@
         self.name = name
         self.x = x
         self.y = y
         self.info = info
         self.curve = (self.x,self.y)
     def __str__(self):
         return str(self.curve)
+    def cut(self,start,end):
+        data = list(zip(self.x,self.y))
+        self.x = [d[0] for d in data if d[0]>=start and d[0]<=end]
+        self.y = [d[1] for d in data if d[0]>=start and d[0]<=end]
 
 class gtfile():
     def __init__(self,key='.xls',location='./',X_Axis='GateV',Y_Axis="DrainI",absY=True):
         self.key=key
         self.location = location
         
         self.X_Axis = X_Axis
@@ -28,27 +32,28 @@
         self.filterFile()
         self.getcurves(absY)
 
     def filterFile(self):
         for f  in os.listdir(self.location):
             if self.key in f:
                 self.files.add(f)
-
+    def cutcurve(self,start,end):
+        for curve in self.curves:
+            curve.cut(start,end)
     def axis2d(self, df, absY=True):
         try:
             x=list(df[self.X_Axis])
             if absY:
                 y=np.abs(list(df[self.Y_Axis]))
             else:
                 y=list(df[self.Y_Axis])
             return x,y
         except:
             return (None,None)
 
-
     def getcurves(self, absY=True):
         for file in self.files:
             dataforms = pandas.read_excel(
                 os.path.join(self.location,file),
                 sheet_name=None)
 
             sheets = list(dataforms.keys())
```

### Comparing `gTdev-1.1.0/gTdev/gtmos.py` & `gTdev-1.1.1/gTdev/gtmos.py`

 * *Files 13% similar despite different names*

```diff
@@ -72,59 +72,65 @@
             return self._VthLE()
         elif self.vthMod ==2:
             return self._maxTrans()
     def _maxTrans(self):
         # get threshold voltage by maximum transconductance
         Vgs,Id=self.noBack()
         import numpy as np
-
+        _,Vgs,Id = self.limitReg(Vgs,Id,lambda y:abs(np.array(y))**0.5)
         yy=np.ediff1d(Id,to_begin=0)/np.ediff1d(Vgs,to_begin=1)
         i=np.argmax(abs(yy))
         self.Gm=yy[i]
         if self.vthMod == 2:
             self.Vth=Vgs[i]
         return self.Vth
 
     def _VthHLE(self):
         Vgs,Id=self.noBack()
        
         haId=abs(np.array(Id))**.5
-        reg=gtcurve.linearOfCurve(Vgs,haId)
+        #reg=gtcurve.linearOfCurve(Vgs,haId)
+        reg,_,_ = self.limitReg(Vgs,Id,lambda y:abs(np.array(y))**0.5)
         xdata=np.array(Vgs)[reg]
         ydata=np.array(haId)[reg]
         p = gtcurve.linearFit(xdata,ydata)
         
         self.Vth=p[0]/p[1]
         return self.Vth
 
     def _VthLE(self):
         Vgs,Id=self.noBack()
        
         haId=abs(np.array(Id))
-        reg=gtcurve.linearOfCurve(Vgs,haId)
+        #reg=gtcurve.linearOfCurve(Vgs,haId)
+        reg,_,_ = self.limitReg(Vgs,Id,lambda y:abs(np.array(y)))
         xdata=np.array(Vgs)[reg]
         ydata=np.array(haId)[reg]
         p = gtcurve.linearFit(xdata,ydata)
         
         self.Vth=p[0]/p[1]
         return self.Vth
 
-    def getSS(self):
-        Vgs,Id=self.noBack()
+    def limitReg(self, Vgs, Id, yFunc, limits=[0, 0.5e-10, 1e-10, 5e-10, 1e-9, 5e-9, 1e-8]):
         def dataAbove(x,y,limit):
             return ([a[0] for a in zip(x,y) if abs(a[1])>abs(limit)], [a[1] for a in zip(x,y) if abs(a[1])>abs(limit)])    
-        
         lenreg = 0
-        for limit in [0, 0.5e-10, 1e-10, 5e-10, 1e-9, 5e-9, 1e-8]:
+        for limit in limits:
             x,y = dataAbove(Vgs,Id,limit)
-            alId=np.log10(abs(np.array(y)))
+            alId = yFunc(y)
+
             tempreg=gtcurve.linearOfCurve(x,alId,0.85)
             if len(tempreg)>lenreg:
                 reg = tempreg
                 lenreg = len(tempreg)
+                newX,newY = dataAbove(Vgs,Id,limit)
+        return reg,newX,newY
+    def getSS(self):
+        Vgs,Id=self.noBack()
+        reg,_,_ = self.limitReg(Vgs,Id,lambda y:np.log10(abs(np.array(y))))
         try:
             alId=np.log10(abs(np.array(Id)))
             xdata=np.array(Vgs)[reg]
             ydata=np.array(alId)[reg]
             p = gtcurve.linearFit(xdata,ydata)
             self.SS=1/abs(p[1])
         except:
```

### Comparing `gTdev-1.1.0/gTdev.egg-info/PKG-INFO` & `gTdev-1.1.1/gTdev.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gTdev
-Version: 1.1.0
+Version: 1.1.1
 Summary: 高效碳基测试运算模块
 Home-page: https://gitee.com/lxwk1spectre/gdevsample
 Author: Spectre Lee
 Author-email: lxwk1spectre@foxmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `gTdev-1.1.0/setup.py` & `gTdev-1.1.1/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="gTdev",
-    version="1.1.0",
+    version="1.1.1",
     author="Spectre Lee",
     author_email="lxwk1spectre@foxmail.com",
     description="高效碳基测试运算模块",
     long_description=long_description,
     long_description_content_type="text/markdown",
     include_package_data=True,
     url="https://gitee.com/lxwk1spectre/gdevsample",
```

