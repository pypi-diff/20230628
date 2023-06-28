# Comparing `tmp/pyuftp-0.0.4.tar.gz` & `tmp/pyuftp-0.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyuftp-0.0.4.tar", last modified: Wed May  3 10:53:04 2023, max compression
+gzip compressed data, was "pyuftp-0.0.6.tar", last modified: Wed Jun 28 13:00:45 2023, max compression
```

## Comparing `pyuftp-0.0.4.tar` & `pyuftp-0.0.6.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-03 10:53:04.332293 pyuftp-0.0.4/
--rw-r--r--   0 runner    (1001) docker     (123)     1619 2023-05-03 10:52:53.000000 pyuftp-0.0.4/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1441 2023-05-03 10:53:04.332293 pyuftp-0.0.4/PKG-INFO
--rwxr-xr-x   0 runner    (1001) docker     (123)     1108 2023-05-03 10:52:53.000000 pyuftp-0.0.4/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      369 2023-05-03 10:52:53.000000 pyuftp-0.0.4/pyproject.toml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-03 10:53:04.332293 pyuftp-0.0.4/pyuftp/
--rwxr-xr-x   0 runner    (1001) docker     (123)       74 2023-05-03 10:52:53.000000 pyuftp-0.0.4/pyuftp/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      497 2023-05-03 10:53:04.332293 pyuftp-0.0.4/pyuftp/_version.py
--rw-r--r--   0 runner    (1001) docker     (123)     7202 2023-05-03 10:52:53.000000 pyuftp-0.0.4/pyuftp/authenticate.py
--rw-r--r--   0 runner    (1001) docker     (123)     6770 2023-05-03 10:52:53.000000 pyuftp-0.0.4/pyuftp/base.py
--rw-r--r--   0 runner    (1001) docker     (123)     1788 2023-05-03 10:52:53.000000 pyuftp-0.0.4/pyuftp/client.py
--rw-r--r--   0 runner    (1001) docker     (123)     6732 2023-05-03 10:52:53.000000 pyuftp-0.0.4/pyuftp/cp.py
--rw-r--r--   0 runner    (1001) docker     (123)     3382 2023-05-03 10:52:53.000000 pyuftp-0.0.4/pyuftp/share.py
--rw-r--r--   0 runner    (1001) docker     (123)     7721 2023-05-03 10:52:53.000000 pyuftp-0.0.4/pyuftp/uftp.py
--rw-r--r--   0 runner    (1001) docker     (123)     6736 2023-05-03 10:52:53.000000 pyuftp-0.0.4/pyuftp/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-03 10:53:04.332293 pyuftp-0.0.4/pyuftp.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1441 2023-05-03 10:53:04.000000 pyuftp-0.0.4/pyuftp.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      400 2023-05-03 10:53:04.000000 pyuftp-0.0.4/pyuftp.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-03 10:53:04.000000 pyuftp-0.0.4/pyuftp.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       46 2023-05-03 10:53:04.000000 pyuftp-0.0.4/pyuftp.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)       59 2023-05-03 10:53:04.000000 pyuftp-0.0.4/pyuftp.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-05-03 10:53:04.000000 pyuftp-0.0.4/pyuftp.egg-info/top_level.txt
--rwxr-xr-x   0 runner    (1001) docker     (123)      190 2023-05-03 10:53:04.332293 pyuftp-0.0.4/setup.cfg
--rwxr-xr-x   0 runner    (1001) docker     (123)     1062 2023-05-03 10:52:53.000000 pyuftp-0.0.4/setup.py
--rw-r--r--   0 runner    (1001) docker     (123)    83607 2023-05-03 10:52:53.000000 pyuftp-0.0.4/versioneer.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:45.066634 pyuftp-0.0.6/
+-rw-r--r--   0 runner    (1001) docker     (123)     1619 2023-06-28 13:00:31.000000 pyuftp-0.0.6/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1478 2023-06-28 13:00:45.066634 pyuftp-0.0.6/PKG-INFO
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1145 2023-06-28 13:00:31.000000 pyuftp-0.0.6/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      369 2023-06-28 13:00:31.000000 pyuftp-0.0.6/pyproject.toml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:45.066634 pyuftp-0.0.6/pyuftp/
+-rwxr-xr-x   0 runner    (1001) docker     (123)       74 2023-06-28 13:00:31.000000 pyuftp-0.0.6/pyuftp/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      497 2023-06-28 13:00:45.066634 pyuftp-0.0.6/pyuftp/_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7202 2023-06-28 13:00:31.000000 pyuftp-0.0.6/pyuftp/authenticate.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8561 2023-06-28 13:00:31.000000 pyuftp-0.0.6/pyuftp/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1831 2023-06-28 13:00:31.000000 pyuftp-0.0.6/pyuftp/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11899 2023-06-28 13:00:31.000000 pyuftp-0.0.6/pyuftp/cp.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3382 2023-06-28 13:00:31.000000 pyuftp-0.0.6/pyuftp/share.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7911 2023-06-28 13:00:31.000000 pyuftp-0.0.6/pyuftp/uftp.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6757 2023-06-28 13:00:31.000000 pyuftp-0.0.6/pyuftp/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:00:45.066634 pyuftp-0.0.6/pyuftp.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1478 2023-06-28 13:00:45.000000 pyuftp-0.0.6/pyuftp.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      400 2023-06-28 13:00:45.000000 pyuftp-0.0.6/pyuftp.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:00:45.000000 pyuftp-0.0.6/pyuftp.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       46 2023-06-28 13:00:45.000000 pyuftp-0.0.6/pyuftp.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 13:00:45.000000 pyuftp-0.0.6/pyuftp.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 13:00:45.000000 pyuftp-0.0.6/pyuftp.egg-info/top_level.txt
+-rwxr-xr-x   0 runner    (1001) docker     (123)      190 2023-06-28 13:00:45.066634 pyuftp-0.0.6/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1062 2023-06-28 13:00:31.000000 pyuftp-0.0.6/setup.py
+-rw-r--r--   0 runner    (1001) docker     (123)    83607 2023-06-28 13:00:31.000000 pyuftp-0.0.6/versioneer.py
```

### Comparing `pyuftp-0.0.4/LICENSE` & `pyuftp-0.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `pyuftp-0.0.4/PKG-INFO` & `pyuftp-0.0.6/README.md`

 * *Files 14% similar despite different names*

```diff
@@ -1,19 +1,7 @@
-Metadata-Version: 2.1
-Name: pyuftp
-Version: 0.0.4
-Summary: UFTP (UNICORE FTP) commandline client
-Home-page: https://github.com/UNICORE-EU/pyuftp
-Author: Bernd Schuller
-Author-email: b.schuller@fz-juelich.de
-License: License :: OSI Approved :: BSD
-Requires-Python: >=3.7
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 # PyUFTP, a commandline client for UFTP (UNICORE FTP) commandline client
 
 UFTP (UNICORE File Transfer Protocol) is a high-performance data
 streaming library and file transfer tool with sharing capabilities.
 It allows to transfer data from client to server (and vice versa),
 as well as providing data staging and third-party transfer between
 UFTP-enabled UNICORE sites.
@@ -27,14 +15,15 @@
 * authenticate  - Authenticate only, returning UFTPD address and one-time password
 * checksum      - Compute hashes for remote file(s) (MD5, SHA-1, SHA-256, SHA-512)
 * cp            - Download/upload file(s)
 * find          - List all files in a remote directory
 * info          - Gets info about the remote server
 * ls            - List a remote directory
 * mkdir         - Create a remote directory
+* rcp           - Server-server copy
 * rm            - Remove a remote file/directory
 * share         - List, create, update and delete shares
 
 ## Installation
 
 Install from PyPI with
```

### Comparing `pyuftp-0.0.4/README.md` & `pyuftp-0.0.6/PKG-INFO`

 * *Files 26% similar despite different names*

```diff
@@ -1,7 +1,19 @@
+Metadata-Version: 2.1
+Name: pyuftp
+Version: 0.0.6
+Summary: UFTP (UNICORE FTP) commandline client
+Home-page: https://github.com/UNICORE-EU/pyuftp
+Author: Bernd Schuller
+Author-email: b.schuller@fz-juelich.de
+License: License :: OSI Approved :: BSD
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 # PyUFTP, a commandline client for UFTP (UNICORE FTP) commandline client
 
 UFTP (UNICORE File Transfer Protocol) is a high-performance data
 streaming library and file transfer tool with sharing capabilities.
 It allows to transfer data from client to server (and vice versa),
 as well as providing data staging and third-party transfer between
 UFTP-enabled UNICORE sites.
@@ -15,14 +27,15 @@
 * authenticate  - Authenticate only, returning UFTPD address and one-time password
 * checksum      - Compute hashes for remote file(s) (MD5, SHA-1, SHA-256, SHA-512)
 * cp            - Download/upload file(s)
 * find          - List all files in a remote directory
 * info          - Gets info about the remote server
 * ls            - List a remote directory
 * mkdir         - Create a remote directory
+* rcp           - Server-server copy
 * rm            - Remove a remote file/directory
 * share         - List, create, update and delete shares
 
 ## Installation
 
 Install from PyPI with
```

### Comparing `pyuftp-0.0.4/pyuftp/authenticate.py` & `pyuftp-0.0.6/pyuftp/authenticate.py`

 * *Files identical despite different names*

### Comparing `pyuftp-0.0.4/pyuftp/client.py` & `pyuftp-0.0.6/pyuftp/client.py`

 * *Files 6% similar despite different names*

```diff
@@ -8,14 +8,15 @@
             "authenticate": pyuftp.base.Auth(),
             "checksum": pyuftp.utils.Checksum(),
             "cp": pyuftp.cp.Copy(),
             "find": pyuftp.utils.Find(),
             "info": pyuftp.base.Info(),
             "ls": pyuftp.utils.Ls(),
             "mkdir": pyuftp.utils.Mkdir(),
+            "rcp": pyuftp.cp.RemoteCopy(),
             "rm": pyuftp.utils.Rm(),
             "share": pyuftp.share.Share(),
         }
 
 def show_version():
     print("PyUFTP commandline client for UFTP (UNICORE FTP) "
           "%s, https://www.unicore.eu" % pyuftp._version.get_versions().get('version', "n/a"))
```

### Comparing `pyuftp-0.0.4/pyuftp/share.py` & `pyuftp-0.0.6/pyuftp/share.py`

 * *Files identical despite different names*

### Comparing `pyuftp-0.0.4/pyuftp/uftp.py` & `pyuftp-0.0.6/pyuftp/uftp.py`

 * *Files 2% similar despite different names*

```diff
@@ -199,15 +199,19 @@
                 if written is None:
                     written = 0
                 write_offset += written
                 to_write -= written
             total = total + len(data)
         target.flush()
         return total, int(time()) - start_time
-    
+
+    def receive_file(self, local_file, remote_file, server, password):
+        cmd = f"RECEIVE-FILE '{local_file}' '{remote_file}' '{server}' '{password}'"
+        return self.ftp.sendcmd(cmd)
+
     def finish_transfer(self):
         self.ftp.voidresp()
     
 class FileInfo:
     def __init__(self, ls_line = None):
         self.path = None
         self.size = -1
```

### Comparing `pyuftp-0.0.4/pyuftp/utils.py` & `pyuftp-0.0.6/pyuftp/utils.py`

 * *Files 4% similar despite different names*

```diff
@@ -93,20 +93,18 @@
         if endpoint is None:
             raise ValueError(f"Does not seem to be a valid URL: {self.args.authURL}")
         if file_name is None:
             file_name = "."
         host, port, onetime_pwd = self.authenticate(endpoint, base_dir)
         self.verbose(f"Connecting to UFTPD {host}:{port}")
         with pyuftp.uftp.open(host, port, onetime_pwd) as uftp:
-            st = uftp.stat(file_name)
-            if st['st_mode']&stat.S_IFREG:
-                _hash, _f = uftp.checksum(file_name, self.args.algorithm)
+            for (entry, _) in crawl_remote(uftp, base_dir, file_name):
+                entry = os.path.relpath(entry, base_dir)
+                _hash, _f = uftp.checksum(entry, self.args.algorithm)
                 print(_hash, _f)
-            else:
-                raise ValueError(f"Not a regular file: {file_name}")
 
 class Find(pyuftp.base.Base):
     
     def add_command_args(self):
         self.parser.prog = "pyuftp find"
         self.parser.description = self.get_synopsis()
         self.parser.add_argument("remoteURL", help="Remote UFTP URL")
@@ -129,15 +127,15 @@
                     base = file_name
                     uftp.cwd(base)
                 else:
                     pattern = file_name
             if base_dir=="/":
                 # to clean-up the output since normpath does not collapse two leading '/'
                 base_dir = ""
-            for entry in crawl_remote(uftp, base, pattern, all=True):
+            for (entry, _) in crawl_remote(uftp, base, pattern, all=True):
                 print(os.path.normpath(base_dir+"/"+entry))
 
 
 _factors = {"k":1024, "m":1024*1024, "g":1024*1024*1024}
 
 def parse_value_with_units(value):
     multiplier = value[-1].lower()
@@ -149,27 +147,28 @@
         value = value[:-1]
     return _factor * int(value)
 
 def is_wildcard(path):
     return "*" in path or "?" in path
 
 def crawl_remote(uftp, base_dir, file_pattern="*", recurse=False, all=False):
+    """ returns tuples (name, size) """
     for x in uftp.listdir("."):
         if not x.is_dir:
             if not fnmatch.fnmatch(x.path, file_pattern):
                 continue
             else:
-                yield base_dir+"/"+x.path
+                yield base_dir+"/"+x.path, x.size
         if all or (recurse and fnmatch.fnmatch(x.path, file_pattern)):
             try:
                 uftp.cwd(x.path)
             except OSError:
                 continue
-            for y in crawl_remote(uftp, base_dir+"/"+x.path, file_pattern, recurse, all):
-                yield y
+            for y, size in crawl_remote(uftp, base_dir+"/"+x.path, file_pattern, recurse, all):
+                yield y, size
             uftp.cdup()
 
 def crawl_local(base_dir, file_pattern="*", recurse=False, all=False):
     for x in os.listdir(base_dir):
         if not os.path.isdir(base_dir+"/"+x):
             if not fnmatch.fnmatch(x, file_pattern):
                 continue
```

### Comparing `pyuftp-0.0.4/pyuftp.egg-info/PKG-INFO` & `pyuftp-0.0.6/pyuftp.egg-info/PKG-INFO`

 * *Files 23% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyuftp
-Version: 0.0.4
+Version: 0.0.6
 Summary: UFTP (UNICORE FTP) commandline client
 Home-page: https://github.com/UNICORE-EU/pyuftp
 Author: Bernd Schuller
 Author-email: b.schuller@fz-juelich.de
 License: License :: OSI Approved :: BSD
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown
@@ -27,14 +27,15 @@
 * authenticate  - Authenticate only, returning UFTPD address and one-time password
 * checksum      - Compute hashes for remote file(s) (MD5, SHA-1, SHA-256, SHA-512)
 * cp            - Download/upload file(s)
 * find          - List all files in a remote directory
 * info          - Gets info about the remote server
 * ls            - List a remote directory
 * mkdir         - Create a remote directory
+* rcp           - Server-server copy
 * rm            - Remove a remote file/directory
 * share         - List, create, update and delete shares
 
 ## Installation
 
 Install from PyPI with
```

### Comparing `pyuftp-0.0.4/setup.py` & `pyuftp-0.0.6/setup.py`

 * *Files identical despite different names*

### Comparing `pyuftp-0.0.4/versioneer.py` & `pyuftp-0.0.6/versioneer.py`

 * *Files identical despite different names*

