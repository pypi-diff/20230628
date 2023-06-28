# Comparing `tmp/django_cloud_storages-0.1.2.tar.gz` & `tmp/django_cloud_storages-0.1.3.tar.gz`

## Comparing `django_cloud_storages-0.1.2.tar` & `django_cloud_storages-0.1.3.tar`

### file list

```diff
@@ -1,12 +1,12 @@
--rw-r--r--   0        0        0      686 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.2/requirements.txt
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.2/cloud_storages/__init__.py
--rw-r--r--   0        0        0      381 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.2/cloud_storages/utils.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.2/cloud_storages/backends/__init__.py
--rw-r--r--   0        0        0     7399 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.2/cloud_storages/backends/appwrite.py
--rw-r--r--   0        0        0     7771 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.2/cloud_storages/backends/dropbox.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.2/tests/__init__.py
--rw-r--r--   0        0        0     3236 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.2/.gitignore
--rw-r--r--   0        0        0     1106 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.2/LICENSE
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.2/README.md
--rw-r--r--   0        0        0      687 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.2/pyproject.toml
--rw-r--r--   0        0        0      520 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.2/PKG-INFO
+-rw-r--r--   0        0        0      686 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.3/requirements.txt
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.3/cloud_storages/__init__.py
+-rw-r--r--   0        0        0      381 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.3/cloud_storages/utils.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.3/cloud_storages/backends/__init__.py
+-rw-r--r--   0        0        0    10114 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.3/cloud_storages/backends/appwrite.py
+-rw-r--r--   0        0        0     8254 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.3/cloud_storages/backends/dropbox.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.3/tests/__init__.py
+-rw-r--r--   0        0        0     3236 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.3/.gitignore
+-rw-r--r--   0        0        0     1106 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.3/LICENSE
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.3/README.md
+-rw-r--r--   0        0        0      687 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.3/pyproject.toml
+-rw-r--r--   0        0        0      520 2020-02-02 00:00:00.000000 django_cloud_storages-0.1.3/PKG-INFO
```

### Comparing `django_cloud_storages-0.1.2/requirements.txt` & `django_cloud_storages-0.1.3/requirements.txt`

 * *Files identical despite different names*

### Comparing `django_cloud_storages-0.1.2/cloud_storages/backends/appwrite.py` & `django_cloud_storages-0.1.3/cloud_storages/backends/dropbox.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,195 +1,209 @@
 import requests
-import secrets
-import string
-import traceback
-import re
 
 from django.core.files.storage import Storage
 from django.core.files import File
 from django.utils.deconstruct import deconstructible
 from django.utils.deconstruct import deconstructible
 
-from appwrite.client import Client
-from appwrite.input_file import InputFile
-from appwrite.services.storage import Storage as appwrite_storage
-from appwrite.exception import AppwriteException
+import dropbox
+from dropbox import sharing as dbx_sharing
+from dropbox.exceptions import ApiError
+from dropbox.files import *
 
 from cloud_storages.utils import *
 
+_DEFAULT_TIMEOUT = 100
+_DEFAULT_MODE = 'add'
 
 @deconstructible
-class AppWriteStorage(Storage):
+class DropBoxStorage(Storage):
     CHUNK_SIZE = 4 * 1024 * 1024
-    MAX_FILE_NAME_LENGTH = 30
     def __init__(self):
-        self.APPWRITE_API_KEY = setting('APPWRITE_API_KEY')
-        self.APPWRITE_PROJECT_ID = setting('APPWRITE_PROJECT_ID')
-        self.APPWRITE_BUCKET_ID = setting('APPWRITE_BUCKET_ID')
-        self.APPWRITE_API_ENDPOINT = setting('APPWRITE_API_ENDPOINT', "https://cloud.appwrite.io/v1")
+        self.DROPBOX_OAUTH2_ACCESS_TOKEN = setting('DROPBOX_OAUTH2_ACCESS_TOKEN')
+        self.DROPBOX_OAUTH2_REFRESH_TOKEN = setting('DROPBOX_OAUTH2_REFRESH_TOKEN')
+        self.DROPBOX_APP_KEY = setting('DROPBOX_APP_KEY')
+        self.DROPBOX_APP_SECRET = setting('DROPBOX_APP_SECRET')
+        self.DROPBOX_ROOT_PATH = setting('DROPBOX_ROOT_PATH')
         self.MEDIA_URL = setting('MEDIA_URL')
-        
-        self.client = Client()
-        (self.client
-        .set_endpoint(self.APPWRITE_API_ENDPOINT) # Your API Endpoint
-        .set_project(self.APPWRITE_PROJECT_ID) # Your project ID
-        .set_key(self.APPWRITE_API_KEY) # Your secret API key
-        )
-        self.storage = appwrite_storage(self.client)
+        self.timeout = setting('DROPBOX_TIMEOUT', _DEFAULT_TIMEOUT)
+        self.write_mode = setting('DROPBOX_WRITE_MODE', _DEFAULT_MODE)
+        self.dbx = dropbox.Dropbox(app_key=self.DROPBOX_APP_KEY, app_secret=self.DROPBOX_APP_SECRET, oauth2_refresh_token=self.DROPBOX_OAUTH2_REFRESH_TOKEN)
+        self.dbx.users_get_current_account()
 
     def open(self, name, mode="rb"):
         """Retrieve the specified file from storage."""
         return self._open(name, mode)
     def _open(self, name, mode='rb'):
-        result = self.url(name)
-        response = requests.get(result)
+        full_file_url = self.url(name)
+        response = requests.get(full_file_url)
         if (response.status_code == 200):
             data = response.text
             remote_file = File(data)
             return remote_file
-    
+        
     def save(self, name, content, max_length=None):
         """
         Save new content to the file specified by name. The content should be
         a proper File object or any Python file-like object, ready to be read
         from the beginning.
         """
+        # Get the proper name for the file, as it will actually be saved.
+        if name is None:
+            name = content.name
         if not hasattr(content, "chunks"):
             content = File(content, name)
-        name = self.get_available_name(name, max_length=max_length)
-        name = self._save(name, content)
-        return name['file_id']
+        path = self.get_available_name(name, content, max_length=max_length)
+        if path[1] is None:
+            self._save(path[0], content)
+        return path[0]
     def _save(self, name, content):
         content.open()
-        the_file = InputFile.from_bytes(bytes=content.read(), filename=name['file_name'])
-        result = self.storage.create_file(self.APPWRITE_BUCKET_ID, name['file_id'], the_file)
+        if content.size <= self.CHUNK_SIZE:
+            self.dbx.files_upload(content.read(), name, mode=WriteMode(self.write_mode))
+        else:
+            self._chunked_upload(content, name)
         content.close()
         return name
-    
-    def get_available_name(self, name, max_length=None):
+
+    def get_available_name(self, name, content, max_length=None):
         """
         Return a filename that's free on the target storage system and
         available for new content to be written to.
         """
         formatted_name = self.get_valid_name(name)
         new_name = formatted_name
         index = 0
         while(1):
             index += 1
-            if self.exists(new_name['file_id']):
-                new_name = self.get_alternative_name(formatted_name, index=index)
-                continue
+            if self.exists(new_name):
+                remote_file = self.open(new_name)
+                remote_file.open()
+                content.open()
+                remote_file_data = remote_file.read()
+                content_data = content.read()
+                remote_file.close()
+                content.close()
+                if remote_file_data == content_data:
+                    return (new_name, 'Exists')
+                else:
+                    new_name = self.get_alternative_name(formatted_name, index=index)
+                    continue
             break
-        return new_name
+        return (new_name, None)
     
     def generate_filename(self, filename):
         """
         Validate the filename by calling get_valid_name() and return a filename
         to be passed to the save() method.
         """
         name = self.get_valid_name(filename)
         return name
 
     def get_valid_name(self, name):
         """
         Return a filename, based on the provided filename, that's suitable for
         use in the target storage system.
         """
-        res = name.rsplit('.', 1)  # Split on last occurrence of delimiter
-        if len(res[0])>self.MAX_FILE_NAME_LENGTH:
-            raise Exception(f"The entire file path length must be less than or equal to {self.MAX_FILE_NAME_LENGTH}")
         name = str(name).replace("\\", "/")
-        name = re.sub(r"^\W+", "", name) # Remove special characters at beginning
-        # name = name.rsplit('.', 1)
-        # file_name = name[0] if len(name[0])<=self.MAX_FILE_NAME_LENGTH else name[0][0:30]
-        # name = f"{file_name}.{name[1]}"
-        # alphaNumeric = string.ascii_uppercase + string.digits
-        # file_id = ''.join([secrets.choice(alphaNumeric) for i in range(36)])
-        return {'file_id': name, 'file_name': name}
-
+        path = f"{self.DROPBOX_ROOT_PATH}/{name}"
+        return path
+    
     def get_alternative_name(self, file_root, file_ext=None, index=0):
         """
         Return an alternative filename if one exists to the filename.
         """
-        res = file_root['file_name'].rsplit('.', 1)  # Split on last occurrence of delimiter
+        res = file_root.rsplit('.', 1)  # Split on last occurrence of delimiter
         file_name = f"{res[0]}({index})"
         file_ext = res[1]
         updated_name =  f"{file_name}.{file_ext}"
-        return {'file_id': updated_name, 'file_name': updated_name}
+        return updated_name
 
     def delete(self, name):
         """
         Delete the specified file from the storage system.
         """
-        result = self.storage.delete_file(self.APPWRITE_BUCKET_ID, name)
+        self.dbx.files_delete_v2(name)
 
     def exists(self, name):
         """
         Return True if a file referenced by the given name already exists in the
         storage system, or False if the name is available for a new file.
         """
         try:
-            result = self.storage.get_file(self.APPWRITE_BUCKET_ID, name)
-            return True
-        except AppwriteException as e:
-            if str(e) == "The requested file could not be found.":
-                return False
-            else:
-                traceback.print_exc()
-                raise(e)
-        
+            return bool(self.dbx.files_get_metadata(name))
+        except ApiError:
+            return False
+    
     def listdir(self, path):
         """
         List the contents of the specified path. Return a 2-tuple of lists:
         the first item being directories, the second item being files.
         """
-        pass
+        directories, files = [], []
+        metadata = self.dbx.files_list_folder(path)
+        for entry in metadata.entries:
+            if isinstance(entry, FolderMetadata):
+                directories.append(entry.name)
+            else:
+                files.append(entry.name)
+        return directories, files
     
     def size(self, name):
         """
         Return the total size, in bytes, of the file specified by name.
         """
-        result = self.storage.get_file(self.APPWRITE_BUCKET_ID, name)
-        return result.sizeOriginal
-    
+        metadata = self.dbx.files_get_metadata(name)
+        return metadata.size
+
     def url(self, name, permanent_link=False):
         """
         Return an absolute URL where the file's contents can be accessed directly by a web browser.
         """
         try:
-            file_url = f"https://cloud.appwrite.io/v1/storage/buckets/{self.APPWRITE_BUCKET_ID}/files/{name}/view?project={self.APPWRITE_PROJECT_ID}"
-            return file_url
-        except Exception as e:
-            print(e)
+            if not permanent_link:
+                media = self.dbx.files_get_temporary_link(name)
+                return media.link
+            else:
+                dbx_share_settings = dbx_sharing.SharedLinkSettings(allow_download=True)
+                media = self.dbx.sharing_create_shared_link_with_settings(name, settings=dbx_share_settings)
+                file_url = str(media.url)[:-1]+"1"
+                return file_url
+        except ApiError:
             return None
-    
+
     def get_accessed_time(self, name):
         """
         Return the last accessed time (as a datetime) of the file specified by name.
         The datetime will be timezone-aware if USE_TZ=True.
         """
-        result = self.storage.get_file(self.APPWRITE_BUCKET_ID, name)
-        return result.updatedAt
+        last_accessed = self.dbx.files_get_metadata(name).client_modified
+        return last_accessed
 
     def get_created_time(self, name):
         """
         Return the creation time (as a datetime) of the file specified by name.
         The datetime will be timezone-aware if USE_TZ=True.
         """
-        result = self.storage.get_file(self.APPWRITE_BUCKET_ID, name)
-        return result.createdAt
-    
+        created_at = self.dbx.files_get_metadata(name).client_modified
+        return created_at
+
     def get_modified_time(self, name):
         """
         Return the last modified time (as a datetime) of the file specified by
         name. The datetime will be timezone-aware if USE_TZ=True.
         """
-        result = self.storage.get_file(self.APPWRITE_BUCKET_ID, name)
-        return result.updatedAt
-    
-
-    
-    
-    
-
+        last_modified = self.dbx.files_get_metadata(name).server_modified
+        return last_modified
+                
+    def _chunked_upload(self, content, dest_path):
+        upload_session = self.dbx.files_upload_session_start(content.read(self.CHUNK_SIZE))
+        cursor = UploadSessionCursor(session_id=upload_session.session_id, offset=content.tell())
+        commit = CommitInfo(path=dest_path, mode=WriteMode(self.write_mode))
+        while content.tell() < content.size:
+            if (content.size - content.tell()) <= self.CHUNK_SIZE:
+                self.dbx.files_upload_session_finish(content.read(self.CHUNK_SIZE), cursor, commit)
+            else:
+                self.dbx.files_upload_session_append_v2(content.read(self.CHUNK_SIZE), cursor)
+                cursor.offset = content.tell()
```

### Comparing `django_cloud_storages-0.1.2/.gitignore` & `django_cloud_storages-0.1.3/.gitignore`

 * *Files identical despite different names*

### Comparing `django_cloud_storages-0.1.2/LICENSE` & `django_cloud_storages-0.1.3/LICENSE`

 * *Files identical despite different names*

### Comparing `django_cloud_storages-0.1.2/pyproject.toml` & `django_cloud_storages-0.1.3/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling", "django", "requests", "dropbox", "appwrite"]
 build-backend = "hatchling.build"
 
 [project]
 name = "django-cloud-storages"
-version = "0.1.2"
+version = "0.1.3"
 authors = [
   { name="Samiddha Chakrabarti", email="samiddha99@protonmail.com" },
 ]
 description = "Cloud file storages for django."
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `django_cloud_storages-0.1.2/PKG-INFO` & `django_cloud_storages-0.1.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: django-cloud-storages
-Version: 0.1.2
+Version: 0.1.3
 Summary: Cloud file storages for django.
 Project-URL: Homepage, https://github.com/Samiddha99/django-cloud-storages
 Project-URL: Bug Tracker, https://github.com/Samiddha99/django-cloud-storages/issues
 Author-email: Samiddha Chakrabarti <samiddha99@protonmail.com>
 License-File: LICENSE
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

