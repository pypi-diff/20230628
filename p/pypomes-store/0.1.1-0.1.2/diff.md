# Comparing `tmp/pypomes_store-0.1.1.tar.gz` & `tmp/pypomes_store-0.1.2.tar.gz`

## Comparing `pypomes_store-0.1.1.tar` & `pypomes_store-0.1.2.tar`

### file list

```diff
@@ -1,8 +1,8 @@
--rw-r--r--   0        0        0     1104 2020-02-02 00:00:00.000000 pypomes_store-0.1.1/src/pypomes_store/__init__.py
--rw-r--r--   0        0        0     7745 2020-02-02 00:00:00.000000 pypomes_store-0.1.1/src/pypomes_store/azure_pomes.py
--rw-r--r--   0        0        0    10533 2020-02-02 00:00:00.000000 pypomes_store-0.1.1/src/pypomes_store/minio_pomes.py
--rw-r--r--   0        0        0       83 2020-02-02 00:00:00.000000 pypomes_store-0.1.1/.gitignore
--rw-r--r--   0        0        0     1086 2020-02-02 00:00:00.000000 pypomes_store-0.1.1/LICENSE
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pypomes_store-0.1.1/README.md
--rw-r--r--   0        0        0      912 2020-02-02 00:00:00.000000 pypomes_store-0.1.1/pyproject.toml
--rw-r--r--   0        0        0      823 2020-02-02 00:00:00.000000 pypomes_store-0.1.1/PKG-INFO
+-rw-r--r--   0        0        0     1104 2020-02-02 00:00:00.000000 pypomes_store-0.1.2/src/pypomes_store/__init__.py
+-rw-r--r--   0        0        0     7765 2020-02-02 00:00:00.000000 pypomes_store-0.1.2/src/pypomes_store/azure_pomes.py
+-rw-r--r--   0        0        0    10545 2020-02-02 00:00:00.000000 pypomes_store-0.1.2/src/pypomes_store/minio_pomes.py
+-rw-r--r--   0        0        0       83 2020-02-02 00:00:00.000000 pypomes_store-0.1.2/.gitignore
+-rw-r--r--   0        0        0     1086 2020-02-02 00:00:00.000000 pypomes_store-0.1.2/LICENSE
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pypomes_store-0.1.2/README.md
+-rw-r--r--   0        0        0      974 2020-02-02 00:00:00.000000 pypomes_store-0.1.2/pyproject.toml
+-rw-r--r--   0        0        0      899 2020-02-02 00:00:00.000000 pypomes_store-0.1.2/PKG-INFO
```

### Comparing `pypomes_store-0.1.1/src/pypomes_store/__init__.py` & `pypomes_store-0.1.2/src/pypomes_store/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -16,9 +16,9 @@
     # minio_pomes
     MINIO_BUCKET, MINIO_HOST, MINIO_ACCESS_KEY, MINIO_SECRET_KEY, MINIO_SECURE_ACCESS, MINIO_TEMP_PATH,
     minio_access, minio_file_store, minio_object_store, minio_object_stat,
     minio_object_delete, minio_objects_list, minio_object_retrieve, minio_object_exists,
     minio_object_tags_retrieve, minio_file_retrieve, minio_setup
 ]
 
-__version__ = "0.1.1"
-__version_info__ = (0, 1, 1)
+__version__ = "0.1.2"
+__version_info__ = (0, 1, 2)
```

### Comparing `pypomes_store-0.1.1/src/pypomes_store/azure_pomes.py` & `pypomes_store-0.1.2/src/pypomes_store/azure_pomes.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,13 +1,14 @@
+import io
+import sys
 # noinspection PyPackageRequirements
 from azure.storage.blob import BlobClient, BlobProperties
 from typing import Final
-import io
-import sys
-from .env_pomes import APP_PREFIX, env_get_str
+from pypomes_core.env_pomes import APP_PREFIX, env_get_str
+from pypomes_core.exception_pomes import exc_format
 
 # string de conexão com o Azure
 AZURE_CONNECTION_STRING: Final[str] = env_get_str(f"{APP_PREFIX}_AZURE_CONNECTION_STRING")
 
 #  nome do bucket no armazenamento Azure
 AZURE_STORAGE_BUCKET: Final[str] = env_get_str(f"{APP_PREFIX}_AZURE_STORAGE_BUCKET")
 
@@ -162,15 +163,14 @@
     """
     Formata e retorna a mensagem de erro correspondente à exceção levantada no acesso ao Azure.
 
     :param exception: A exceção levantada
     :return: A mensagem de erro formatada
     """
     # TODO
-    from .exception_pomes import exc_format
     return exc_format(exception, sys.exc_info())
 
 
 # testes do acesso ao Azure
 # if __name__ == "__main__":
 #
 #     # print errors
```

### Comparing `pypomes_store-0.1.1/src/pypomes_store/minio_pomes.py` & `pypomes_store-0.1.2/src/pypomes_store/minio_pomes.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,17 +1,17 @@
 from typing import Final, Iterator
-from minio import Minio
-from minio.datatypes import Object as MinioObject
-from minio.commonconfig import Tags
-from unidecode import unidecode
 import os
 import pickle
 import tempfile
 import uuid
-from .env_pomes import APP_PREFIX, env_get_bool, env_get_str
+from minio import Minio
+from minio.datatypes import Object as MinioObject
+from minio.commonconfig import Tags
+from pypomes_core.env_pomes import APP_PREFIX, env_get_bool, env_get_str
+from unidecode import unidecode
 
 MINIO_BUCKET: Final[str] = env_get_str(f"{APP_PREFIX}_MINIO_BUCKET")
 MINIO_HOST: Final[str] = env_get_str(f"{APP_PREFIX}_MINIO_HOST")
 MINIO_ACCESS_KEY: Final[str] = env_get_str(f"{APP_PREFIX}_MINIO_ACCESS_KEY")
 MINIO_SECRET_KEY: Final[str] = env_get_str(f"{APP_PREFIX}_MINIO_SECRET_KEY")
 MINIO_SECURE_ACCESS: Final[bool] = env_get_bool(F"{APP_PREFIX}_MINIO_SECURE_ACCESS")
 MINIO_TEMP_PATH: Final[str] = env_get_str(F"{APP_PREFIX}_MINIO_TEMP_PATH", tempfile.gettempdir())
```

### Comparing `pypomes_store-0.1.1/LICENSE` & `pypomes_store-0.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `pypomes_store-0.1.1/pyproject.toml` & `pypomes_store-0.1.2/pyproject.toml`

 * *Files 27% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 requires = [
     "hatchling"
 ]
 build-backend = "hatchling.build"
 
 [project]
 name = "pypomes_store"
-version = "0.1.1"
+version = "0.1.2"
 authors = [
   { name="GT Nunes", email="wisecoder01@gmail.com" },
 ]
 description = "A collection of Python pomes, pennyeach (object storage modules)"
 readme = "README.md"
 requires-python = ">=3.10"
 classifiers = [
@@ -19,17 +19,19 @@
     "Operating System :: OS Independent",
 ]
 dependencies = [
     "azure-common>=1.1.28",
     "azure-core>=1.26.4",
     "azure-identity>=1.13.0",
     "azure-storage-blob>=12.16.0",
+    "azure-storage-common>=2.1.10",
     "minio>=7.1.15",
     "pip>=23.1.2",
     "pypomes_core>=0.1.1",
     "setuptools>=68.0.0",
+    "unidecode>=1.3.6",
     "wheel>=0.40.0"
 ]
 
 [project.urls]
 "Homepage" = "https://github.com/TheWiseCoder/PyPomes-Store"
 "Bug Tracker" = "https://github.com/TheWiseCoder/PyPomes-Store/issues"
```

### Comparing `pypomes_store-0.1.1/PKG-INFO` & `pypomes_store-0.1.2/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,21 +1,23 @@
 Metadata-Version: 2.1
 Name: pypomes_store
-Version: 0.1.1
+Version: 0.1.2
 Summary: A collection of Python pomes, pennyeach (object storage modules)
 Project-URL: Homepage, https://github.com/TheWiseCoder/PyPomes-Store
 Project-URL: Bug Tracker, https://github.com/TheWiseCoder/PyPomes-Store/issues
 Author-email: GT Nunes <wisecoder01@gmail.com>
 License-File: LICENSE
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3.10
 Requires-Dist: azure-common>=1.1.28
 Requires-Dist: azure-core>=1.26.4
 Requires-Dist: azure-identity>=1.13.0
 Requires-Dist: azure-storage-blob>=12.16.0
+Requires-Dist: azure-storage-common>=2.1.10
 Requires-Dist: minio>=7.1.15
 Requires-Dist: pip>=23.1.2
 Requires-Dist: pypomes-core>=0.1.1
 Requires-Dist: setuptools>=68.0.0
+Requires-Dist: unidecode>=1.3.6
 Requires-Dist: wheel>=0.40.0
```

