# Comparing `tmp/connect_extension_runner-28.0.tar.gz` & `tmp/connect_extension_runner-28.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "connect_extension_runner-28.0.tar", max compression
+gzip compressed data, was "connect_extension_runner-28.1.tar", max compression
```

## Comparing `connect_extension_runner-28.0.tar` & `connect_extension_runner-28.1.tar`

### file list

```diff
@@ -1,36 +1,36 @@
--rw-r--r--   0        0        0    11357 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/LICENSE
--rw-r--r--   0        0        0     1422 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/README.md
--rw-r--r--   0        0        0       55 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/dataclasses.py
--rw-r--r--   0        0        0      405 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/extension.py
--rw-r--r--   0        0        0      143 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/__init__.py
--rw-r--r--   0        0        0        0 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/artworks/__init__.py
--rw-r--r--   0        0        0     9409 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/artworks/ansi_regular.flf
--rw-r--r--   0        0        0      950 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/artworks/banner.py
--rw-r--r--   0        0        0    11425 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/artworks/bloody.flf
--rw-r--r--   0        0        0     6483 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/config.py
--rw-r--r--   0        0        0     5708 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/constants.py
--rw-r--r--   0        0        0      320 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/exceptions.py
--rw-r--r--   0        0        0        0 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/handlers/__init__.py
--rw-r--r--   0        0        0     2692 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/handlers/anvil.py
--rw-r--r--   0        0        0     4391 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/handlers/base.py
--rw-r--r--   0        0        0     3751 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/handlers/events.py
--rw-r--r--   0        0        0     2444 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/handlers/transformations.py
--rw-r--r--   0        0        0     6881 2023-06-15 15:55:12.711196 connect_extension_runner-28.0/connect/eaas/runner/handlers/web.py
--rw-r--r--   0        0        0    18982 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/helpers.py
--rw-r--r--   0        0        0     1989 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/main.py
--rw-r--r--   0        0        0      340 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/managers/__init__.py
--rw-r--r--   0        0        0     3190 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/managers/background.py
--rw-r--r--   0        0        0     8100 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/managers/base.py
--rw-r--r--   0        0        0     2225 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/managers/interactive.py
--rw-r--r--   0        0        0     1931 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/managers/scheduled.py
--rw-r--r--   0        0        0    20464 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/managers/transformation.py
--rw-r--r--   0        0        0      533 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/managers/utils.py
--rw-r--r--   0        0        0     7917 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/master.py
--rw-r--r--   0        0        0        0 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/workers/__init__.py
--rw-r--r--   0        0        0     2549 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/workers/anvil.py
--rw-r--r--   0        0        0    11320 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/workers/base.py
--rw-r--r--   0        0        0     8834 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/workers/events.py
--rw-r--r--   0        0        0     6545 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/workers/transformations.py
--rw-r--r--   0        0        0     6916 2023-06-15 15:55:12.715196 connect_extension_runner-28.0/connect/eaas/runner/workers/web.py
--rw-r--r--   0        0        0     2870 2023-06-15 15:56:19.568483 connect_extension_runner-28.0/pyproject.toml
--rw-r--r--   0        0        0     2909 1970-01-01 00:00:00.000000 connect_extension_runner-28.0/PKG-INFO
+-rw-r--r--   0        0        0    11357 2023-06-28 08:28:29.032849 connect_extension_runner-28.1/LICENSE
+-rw-r--r--   0        0        0     1422 2023-06-28 08:28:29.032849 connect_extension_runner-28.1/README.md
+-rw-r--r--   0        0        0       55 2023-06-28 08:28:29.032849 connect_extension_runner-28.1/connect/eaas/dataclasses.py
+-rw-r--r--   0        0        0      405 2023-06-28 08:28:29.032849 connect_extension_runner-28.1/connect/eaas/extension.py
+-rw-r--r--   0        0        0      143 2023-06-28 08:28:29.032849 connect_extension_runner-28.1/connect/eaas/runner/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 08:28:29.032849 connect_extension_runner-28.1/connect/eaas/runner/artworks/__init__.py
+-rw-r--r--   0        0        0     9409 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/artworks/ansi_regular.flf
+-rw-r--r--   0        0        0      950 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/artworks/banner.py
+-rw-r--r--   0        0        0    11425 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/artworks/bloody.flf
+-rw-r--r--   0        0        0     6483 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/config.py
+-rw-r--r--   0        0        0     5708 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/constants.py
+-rw-r--r--   0        0        0      320 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/exceptions.py
+-rw-r--r--   0        0        0        0 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/handlers/__init__.py
+-rw-r--r--   0        0        0     2692 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/handlers/anvil.py
+-rw-r--r--   0        0        0     4391 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/handlers/base.py
+-rw-r--r--   0        0        0     3751 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/handlers/events.py
+-rw-r--r--   0        0        0     2444 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/handlers/transformations.py
+-rw-r--r--   0        0        0     6881 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/handlers/web.py
+-rw-r--r--   0        0        0    18982 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/helpers.py
+-rw-r--r--   0        0        0     1989 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/main.py
+-rw-r--r--   0        0        0      340 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/managers/__init__.py
+-rw-r--r--   0        0        0     3190 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/managers/background.py
+-rw-r--r--   0        0        0     8100 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/managers/base.py
+-rw-r--r--   0        0        0     2225 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/managers/interactive.py
+-rw-r--r--   0        0        0     1931 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/managers/scheduled.py
+-rw-r--r--   0        0        0    20665 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/managers/transformation.py
+-rw-r--r--   0        0        0      533 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/managers/utils.py
+-rw-r--r--   0        0        0     7917 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/master.py
+-rw-r--r--   0        0        0        0 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/workers/__init__.py
+-rw-r--r--   0        0        0     2549 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/workers/anvil.py
+-rw-r--r--   0        0        0    11320 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/workers/base.py
+-rw-r--r--   0        0        0     8834 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/workers/events.py
+-rw-r--r--   0        0        0     6545 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/workers/transformations.py
+-rw-r--r--   0        0        0     6916 2023-06-28 08:28:29.036849 connect_extension_runner-28.1/connect/eaas/runner/workers/web.py
+-rw-r--r--   0        0        0     2870 2023-06-28 08:29:39.181766 connect_extension_runner-28.1/pyproject.toml
+-rw-r--r--   0        0        0     2909 1970-01-01 00:00:00.000000 connect_extension_runner-28.1/PKG-INFO
```

### Comparing `connect_extension_runner-28.0/LICENSE` & `connect_extension_runner-28.1/LICENSE`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/README.md` & `connect_extension_runner-28.1/README.md`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/artworks/ansi_regular.flf` & `connect_extension_runner-28.1/connect/eaas/runner/artworks/ansi_regular.flf`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/artworks/banner.py` & `connect_extension_runner-28.1/connect/eaas/runner/artworks/banner.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/artworks/bloody.flf` & `connect_extension_runner-28.1/connect/eaas/runner/artworks/bloody.flf`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/config.py` & `connect_extension_runner-28.1/connect/eaas/runner/config.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/constants.py` & `connect_extension_runner-28.1/connect/eaas/runner/constants.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/handlers/anvil.py` & `connect_extension_runner-28.1/connect/eaas/runner/handlers/anvil.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/handlers/base.py` & `connect_extension_runner-28.1/connect/eaas/runner/handlers/base.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/handlers/events.py` & `connect_extension_runner-28.1/connect/eaas/runner/handlers/events.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/handlers/transformations.py` & `connect_extension_runner-28.1/connect/eaas/runner/handlers/transformations.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/handlers/web.py` & `connect_extension_runner-28.1/connect/eaas/runner/handlers/web.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/helpers.py` & `connect_extension_runner-28.1/connect/eaas/runner/helpers.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/main.py` & `connect_extension_runner-28.1/connect/eaas/runner/main.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/managers/background.py` & `connect_extension_runner-28.1/connect/eaas/runner/managers/background.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/managers/base.py` & `connect_extension_runner-28.1/connect/eaas/runner/managers/base.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/managers/interactive.py` & `connect_extension_runner-28.1/connect/eaas/runner/managers/interactive.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/managers/scheduled.py` & `connect_extension_runner-28.1/connect/eaas/runner/managers/scheduled.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/managers/transformation.py` & `connect_extension_runner-28.1/connect/eaas/runner/managers/transformation.py`

 * *Files 2% similar despite different names*

```diff
@@ -172,15 +172,16 @@
             result_message.output.message = traceback.format_exc()[:4000]
 
         return result_message
 
     async def _fail_task(self, task_data, message):
         try:
             client = self.get_client(task_data)
-            await client('billing').requests[task_data.input.object_id]('fail').post()
+            ns, _ = task_data.input.event_type.split('_', 1)
+            await client(ns).requests[task_data.input.object_id]('fail').post()
             await client.conversations[task_data.input.object_id].messages.create(
                 payload={
                     'type': 'message',
                     'text': f'Transformation request processing failed: {message}.',
                 },
             )
         except Exception:
@@ -244,15 +245,16 @@
             )
             for task in tasks:
                 if not task.done():
                     task.cancel()
             input_file.close()
             output_file.close()
             client = self.get_client(task_data)
-            await client('billing').requests[task_data.input.object_id]('fail').post()
+            ns, _ = task_data.input.event_type.split('_', 1)
+            await client(ns).requests[task_data.input.object_id]('fail').post()
             await client.conversations[task_data.input.object_id].messages.create(
                 payload={
                     'type': 'message',
                     'text': f'Transformation request processing failed: {str(e)}',
                 },
             )
             return TransformationResponse.fail(output=str(e))
@@ -500,15 +502,16 @@
                 raise RowTransformationError(
                     f'Invalid row transformation response status: {response.status}.',
                 )
         return row
 
     def send_stat_update(self, task_data, rows_processed, total_rows):
         client = self.get_sync_client(task_data)
-        client('billing').requests[task_data.input.object_id].update(
+        ns, _ = task_data.input.event_type.split('_', 1)
+        client(ns).requests[task_data.input.object_id].update(
             payload={'stats': {'rows': {'total': total_rows, 'processed': rows_processed}}},
         )
 
     async def send_output_file(self, task_data, batch_id, output_file, logger):
         client = self.get_client(task_data)
 
         fileobj = open(output_file.name, 'rb')
@@ -541,11 +544,12 @@
             content=chunks_iterator(),
             headers=headers,
         )
         logger.info(
             f'Output file upload completed for {task_data.input.object_id}',
         )
         media_file_id = json.loads(media_file)['id']
-        await client('billing').requests[task_data.input.object_id].update(
+        ns, _ = task_data.input.event_type.split('_', 1)
+        await client(ns).requests[task_data.input.object_id].update(
             payload={'files': {'output': {'id': media_file_id}}},
         )
-        await client('billing').requests[task_data.input.object_id]('process').post()
+        await client(ns).requests[task_data.input.object_id]('process').post()
```

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/managers/utils.py` & `connect_extension_runner-28.1/connect/eaas/runner/managers/utils.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/master.py` & `connect_extension_runner-28.1/connect/eaas/runner/master.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/workers/anvil.py` & `connect_extension_runner-28.1/connect/eaas/runner/workers/anvil.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/workers/base.py` & `connect_extension_runner-28.1/connect/eaas/runner/workers/base.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/workers/events.py` & `connect_extension_runner-28.1/connect/eaas/runner/workers/events.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/workers/transformations.py` & `connect_extension_runner-28.1/connect/eaas/runner/workers/transformations.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/connect/eaas/runner/workers/web.py` & `connect_extension_runner-28.1/connect/eaas/runner/workers/web.py`

 * *Files identical despite different names*

### Comparing `connect_extension_runner-28.0/pyproject.toml` & `connect_extension_runner-28.1/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "connect-extension-runner"
-version = "28.0"
+version = "28.1"
 description = "CloudBlue Connect EaaS Extension Runner"
 authors = ["CloudBlue LLC"]
 license = "Apache-2.0"
 packages = [
     { include = "connect" },
 ]
 readme = "./README.md"
```

### Comparing `connect_extension_runner-28.0/PKG-INFO` & `connect_extension_runner-28.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: connect-extension-runner
-Version: 28.0
+Version: 28.1
 Summary: CloudBlue Connect EaaS Extension Runner
 Home-page: https://connect.cloudblue.com
 License: Apache-2.0
 Author: CloudBlue LLC
 Requires-Python: >=3.8,<4
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
```

