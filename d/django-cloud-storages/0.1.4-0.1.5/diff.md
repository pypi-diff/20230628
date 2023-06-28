# Comparing `tmp/django_cloud_storages-0.1.4.tar.gz` & `tmp/django_cloud_storages-0.1.5.tar.gz`

## Comparing `django_cloud_storages-0.1.4.tar` & `django_cloud_storages-0.1.5.tar`

### file list

```diff
@@ -1,12 +1,12 @@
--rw-r--r--   0        0        0      686 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.4/requirements.txt
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.4/cloud_storages/__init__.py
--rw-r--r--   0        0        0      960 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.4/cloud_storages/utils.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.4/cloud_storages/backends/__init__.py
--rw-r--r--   0        0        0    10072 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.4/cloud_storages/backends/appwrite.py
--rw-r--r--   0        0        0     8254 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.4/cloud_storages/backends/dropbox.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.4/tests/__init__.py
--rw-r--r--   0        0        0     3236 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.4/.gitignore
--rw-r--r--   0        0        0     1106 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.4/LICENSE
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.4/README.md
--rw-r--r--   0        0        0      687 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.4/pyproject.toml
--rw-r--r--   0        0        0      520 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.4/PKG-INFO
+-rw-r--r--   0        0        0      686 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.5/requirements.txt
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.5/cloud_storages/__init__.py
+-rw-r--r--   0        0        0      794 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.5/cloud_storages/utils.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.5/cloud_storages/backends/__init__.py
+-rw-r--r--   0        0        0    10432 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.5/cloud_storages/backends/appwrite.py
+-rw-r--r--   0        0        0     8254 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.5/cloud_storages/backends/dropbox.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.5/tests/__init__.py
+-rw-r--r--   0        0        0     3236 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.5/.gitignore
+-rw-r--r--   0        0        0     1106 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.5/LICENSE
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.5/README.md
+-rw-r--r--   0        0        0      687 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.5/pyproject.toml
+-rw-r--r--   0        0        0      520 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.5/PKG-INFO
```

### Comparing `django_cloud_storages-0.1.4/requirements.txt` & `django_cloud_storages-0.1.5/requirements.txt`

 * *Files identical despite different names*

### Comparing `django_cloud_storages-0.1.4/cloud_storages/utils.py` & `django_cloud_storages-0.1.5/cloud_storages/utils.py`

 * *Files 13% similar despite different names*

```diff
@@ -10,20 +10,16 @@
     :param default: Value if setting is not found
     :returns: Setting's value
     """
     return getattr(settings, name, default)
 
 
 class FileNameLengthError(Exception):
-    """Exception raised for errors when file name length exceed.
-    Attributes:
-        max_length -- maximum length of the file name
-        message -- explanation of the error
+    """Exception raised for errors when file name length is too large or too small.
     """
-    def __init__(self, max_length, message=None):
+    def __init__(self, min_length=None, max_length=None, message=None):
+        self.min_length = min_length
         self.max_length = max_length
         self.message = message
-        if self.message is None:
-            self.message = f"File name's length must be less than or equal to {max_length}."
         super().__init__(self.message)
     def __str__(self):
         return self.message
```

### Comparing `django_cloud_storages-0.1.4/cloud_storages/backends/appwrite.py` & `django_cloud_storages-0.1.5/cloud_storages/backends/appwrite.py`

 * *Files 2% similar despite different names*

```diff
@@ -144,18 +144,22 @@
 
     def get_valid_name(self, name):
         """
         Return a filename, based on the provided filename, that's suitable for
         use in the target storage system.
         """
         folder, filename = self.extract_folder_and_filename(name)
+        filename = self._id_validation(filename)
         res = filename.rsplit('.', 1)  # Split on last occurrence of delimiter
         if len(res[0])>self.MAX_FILE_NAME_LENGTH:
-            raise FileNameLengthError(max_length=self.MAX_FILE_NAME_LENGTH)
-        filename = self._id_validation(filename)
+            err_msg = f"File name's length must be less than or equal to {self.MAX_FILE_NAME_LENGTH}."
+            raise FileNameLengthError(max_length=self.MAX_FILE_NAME_LENGTH, message=err_msg)
+        elif len(res[0]) < 1:
+            err_msg = f"File name's length is too small. Avoid using special characters in file name, and file name should not start with underscore."
+            raise FileNameLengthError(message=err_msg)
         return f"{folder}/{filename}"
         # return {'file_id': filename, 'file_name': filename, 'folder_id': folder, 'folder_name': folder}
 
     def get_alternative_name(self, file_root, file_ext=None, index=0):
         """
         Return an alternative filename if one exists to the filename.
         """
```

### Comparing `django_cloud_storages-0.1.4/cloud_storages/backends/dropbox.py` & `django_cloud_storages-0.1.5/cloud_storages/backends/dropbox.py`

 * *Files identical despite different names*

### Comparing `django_cloud_storages-0.1.4/.gitignore` & `django_cloud_storages-0.1.5/.gitignore`

 * *Files identical despite different names*

### Comparing `django_cloud_storages-0.1.4/LICENSE` & `django_cloud_storages-0.1.5/LICENSE`

 * *Files identical despite different names*

### Comparing `django_cloud_storages-0.1.4/pyproject.toml` & `django_cloud_storages-0.1.5/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling", "django", "requests", "dropbox", "appwrite"]
 build-backend = "hatchling.build"
 
 [project]
 name = "django-cloud-storages"
-version = "0.1.4"
+version = "0.1.5"
 authors = [
   { name="Samiddha Chakrabarti", email="samiddha99@protonmail.com" },
 ]
 description = "Cloud file storages for django."
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `django_cloud_storages-0.1.4/PKG-INFO` & `django_cloud_storages-0.1.5/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: django-cloud-storages
-Version: 0.1.4
+Version: 0.1.5
 Summary: Cloud file storages for django.
 Project-URL: Homepage, https://github.com/Samiddha99/django-cloud-storages
 Project-URL: Bug Tracker, https://github.com/Samiddha99/django-cloud-storages/issues
 Author-email: Samiddha Chakrabarti <samiddha99@protonmail.com>
 License-File: LICENSE
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

