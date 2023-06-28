# Comparing `tmp/idocker-1.0.0.tar.gz` & `tmp/idocker-1.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "idocker-1.0.0.tar", last modified: Wed Apr  5 13:10:20 2023, max compression
+gzip compressed data, was "idocker-1.1.0.tar", last modified: Wed Jun 28 07:05:23 2023, max compression
```

## Comparing `idocker-1.0.0.tar` & `idocker-1.1.0.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxrwxr-x   0 pon       (1001) pon       (1001)        0 2023-04-05 13:10:20.632079 idocker-1.0.0/
--rw-rw-r--   0 pon       (1001) pon       (1001)     2756 2023-04-05 13:10:20.632079 idocker-1.0.0/PKG-INFO
--rw-rw-r--   0 pon       (1001) pon       (1001)     1917 2023-01-31 04:58:15.000000 idocker-1.0.0/README.md
-drwxrwxr-x   0 pon       (1001) pon       (1001)        0 2023-04-05 13:10:20.624080 idocker-1.0.0/idocker/
--rw-rw-r--   0 pon       (1001) pon       (1001)      101 2023-04-05 13:08:58.000000 idocker-1.0.0/idocker/__init__.py
-drwxrwxr-x   0 pon       (1001) pon       (1001)        0 2023-04-05 13:10:20.632079 idocker-1.0.0/idocker/cli/
--rw-rw-r--   0 pon       (1001) pon       (1001)        0 2023-01-31 02:12:48.000000 idocker-1.0.0/idocker/cli/__init__.py
--rw-rw-r--   0 pon       (1001) pon       (1001)     1934 2023-04-05 13:08:13.000000 idocker-1.0.0/idocker/cli/main.py
-drwxrwxr-x   0 pon       (1001) pon       (1001)        0 2023-04-05 13:10:20.632079 idocker-1.0.0/idocker.egg-info/
--rw-rw-r--   0 pon       (1001) pon       (1001)     2756 2023-04-05 13:10:20.000000 idocker-1.0.0/idocker.egg-info/PKG-INFO
--rw-rw-r--   0 pon       (1001) pon       (1001)      280 2023-04-05 13:10:20.000000 idocker-1.0.0/idocker.egg-info/SOURCES.txt
--rw-rw-r--   0 pon       (1001) pon       (1001)        1 2023-04-05 13:10:20.000000 idocker-1.0.0/idocker.egg-info/dependency_links.txt
--rw-rw-r--   0 pon       (1001) pon       (1001)       49 2023-04-05 13:10:20.000000 idocker-1.0.0/idocker.egg-info/entry_points.txt
--rw-rw-r--   0 pon       (1001) pon       (1001)       18 2023-04-05 13:10:20.000000 idocker-1.0.0/idocker.egg-info/requires.txt
--rw-rw-r--   0 pon       (1001) pon       (1001)        8 2023-04-05 13:10:20.000000 idocker-1.0.0/idocker.egg-info/top_level.txt
--rw-rw-r--   0 pon       (1001) pon       (1001)       38 2023-04-05 13:10:20.632079 idocker-1.0.0/setup.cfg
--rw-rw-r--   0 pon       (1001) pon       (1001)     1305 2023-02-08 10:45:30.000000 idocker-1.0.0/setup.py
+drwxrwxr-x   0 pon       (1001) pon       (1001)        0 2023-06-28 07:05:23.417278 idocker-1.1.0/
+-rw-rw-r--   0 pon       (1001) pon       (1001)     2756 2023-06-28 07:05:23.417278 idocker-1.1.0/PKG-INFO
+-rw-rw-r--   0 pon       (1001) pon       (1001)     1917 2023-01-31 04:58:15.000000 idocker-1.1.0/README.md
+drwxrwxr-x   0 pon       (1001) pon       (1001)        0 2023-06-28 07:05:23.409278 idocker-1.1.0/idocker/
+-rw-rw-r--   0 pon       (1001) pon       (1001)      101 2023-06-28 07:00:37.000000 idocker-1.1.0/idocker/__init__.py
+drwxrwxr-x   0 pon       (1001) pon       (1001)        0 2023-06-28 07:05:23.417278 idocker-1.1.0/idocker/cli/
+-rw-rw-r--   0 pon       (1001) pon       (1001)        0 2023-01-31 02:12:48.000000 idocker-1.1.0/idocker/cli/__init__.py
+-rw-rw-r--   0 pon       (1001) pon       (1001)     2571 2023-06-28 07:04:12.000000 idocker-1.1.0/idocker/cli/main.py
+drwxrwxr-x   0 pon       (1001) pon       (1001)        0 2023-06-28 07:05:23.413278 idocker-1.1.0/idocker.egg-info/
+-rw-rw-r--   0 pon       (1001) pon       (1001)     2756 2023-06-28 07:05:23.000000 idocker-1.1.0/idocker.egg-info/PKG-INFO
+-rw-rw-r--   0 pon       (1001) pon       (1001)      280 2023-06-28 07:05:23.000000 idocker-1.1.0/idocker.egg-info/SOURCES.txt
+-rw-rw-r--   0 pon       (1001) pon       (1001)        1 2023-06-28 07:05:23.000000 idocker-1.1.0/idocker.egg-info/dependency_links.txt
+-rw-rw-r--   0 pon       (1001) pon       (1001)       49 2023-06-28 07:05:23.000000 idocker-1.1.0/idocker.egg-info/entry_points.txt
+-rw-rw-r--   0 pon       (1001) pon       (1001)       18 2023-06-28 07:05:23.000000 idocker-1.1.0/idocker.egg-info/requires.txt
+-rw-rw-r--   0 pon       (1001) pon       (1001)        8 2023-06-28 07:05:23.000000 idocker-1.1.0/idocker.egg-info/top_level.txt
+-rw-rw-r--   0 pon       (1001) pon       (1001)       38 2023-06-28 07:05:23.417278 idocker-1.1.0/setup.cfg
+-rw-rw-r--   0 pon       (1001) pon       (1001)     1305 2023-02-08 10:45:30.000000 idocker-1.1.0/setup.py
```

### Comparing `idocker-1.0.0/PKG-INFO` & `idocker-1.1.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: idocker
-Version: 1.0.0
+Version: 1.1.0
 Summary: docker cli with python
 Home-page: https://github.com/ponponon/idocker
 Author: ponponon
 Author-email: 1729303158@qq.com
 Maintainer: ponponon
 Maintainer-email: 1729303158@qq.com
 License: MIT License
```

### Comparing `idocker-1.0.0/README.md` & `idocker-1.1.0/README.md`

 * *Files identical despite different names*

### Comparing `idocker-1.0.0/idocker/cli/main.py` & `idocker-1.1.0/idocker/cli/main.py`

 * *Files 8% similar despite different names*

```diff
@@ -37,20 +37,27 @@
             mb = container_stats['memory_stats']['usage']/1024/1024
 
             if mb < 1024:
                 memory_stats__usage: str = f'{round(mb,2)} MB'
             else:
                 memory_stats__usage: str = f'{round(mb/1024,2)} GB'
 
+        cpu_usage = container_stats['cpu_stats']['cpu_usage']['total_usage']
+        system_cpu_usage = container_stats['cpu_stats']['system_cpu_usage']
+        cpu_percent = (cpu_usage / system_cpu_usage) * 100
+        cpu_count = container_stats['cpu_stats']['online_cpus']
+        cpu_stats__usage = f"{cpu_percent*cpu_count:.2f}%"
+
         containers_info.append(
             [
                 short_id,
                 status.ljust(8, " "),
-                removeprefix(name.ljust(25, " "), '/'),
+                removeprefix(name.ljust(27, " "), '/'),
                 memory_stats__usage.rjust(10, " "),
+                cpu_stats__usage.rjust(10, " "),
             ]
         )
 
     client = docker.from_env()
 
     containers = client.containers.list(all=True)
 
@@ -63,14 +70,23 @@
     for container in containers[:]:
         pool.submit(get_container_info, container)
 
     pool.shutdown(wait=True)
 
     containers_info.sort(key=lambda x: x[2])
 
+    containers_info.insert(
+        0, [
+            'container id',
+            'status'.ljust(8, " "),
+            removeprefix('container name'.ljust(26, " "), '/'),
+            'memory'.rjust(10, " "),
+            'cpu'.rjust(10, " "),
+        ])
+
     for container_info in containers_info:
         console.print('   '.join(container_info))
 
 
 cli = click.CommandCollection(sources=[idocker_cli])
 
 if __name__ == '__main__':
```

### Comparing `idocker-1.0.0/idocker.egg-info/PKG-INFO` & `idocker-1.1.0/idocker.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: idocker
-Version: 1.0.0
+Version: 1.1.0
 Summary: docker cli with python
 Home-page: https://github.com/ponponon/idocker
 Author: ponponon
 Author-email: 1729303158@qq.com
 Maintainer: ponponon
 Maintainer-email: 1729303158@qq.com
 License: MIT License
```

### Comparing `idocker-1.0.0/setup.py` & `idocker-1.1.0/setup.py`

 * *Files identical despite different names*

