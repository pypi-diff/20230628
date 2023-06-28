# Comparing `tmp/remotivelabs_cli-0.0.1a7.tar.gz` & `tmp/remotivelabs_cli-0.0.1a8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "remotivelabs_cli-0.0.1a7.tar", max compression
+gzip compressed data, was "remotivelabs_cli-0.0.1a8.tar", max compression
```

## Comparing `remotivelabs_cli-0.0.1a7.tar` & `remotivelabs_cli-0.0.1a8.tar`

### file list

```diff
@@ -1,23 +1,23 @@
--rw-r--r--   0        0        0      608 2023-06-19 13:55:54.232642 remotivelabs_cli-0.0.1a7/LICENSE
--rw-r--r--   0        0        0     2095 2023-06-22 08:12:57.643193 remotivelabs_cli-0.0.1a7/README.md
--rw-r--r--   0        0        0      122 2022-10-26 14:05:47.581000 remotivelabs_cli-0.0.1a7/cli/__about__.py
--rw-r--r--   0        0        0       26 2022-10-26 11:41:55.030088 remotivelabs_cli-0.0.1a7/cli/__init__.py
--rw-r--r--   0        0        0     4011 2023-06-21 12:52:00.336557 remotivelabs_cli-0.0.1a7/cli/brokers.py
--rw-r--r--   0        0        0        1 2022-10-24 12:45:02.134227 remotivelabs_cli-0.0.1a7/cli/cloud/__init__.py
--rw-r--r--   0        0        0     3538 2023-06-22 08:03:29.813439 remotivelabs_cli-0.0.1a7/cli/cloud/auth.py
--rw-r--r--   0        0        0     2940 2023-06-22 08:03:46.314372 remotivelabs_cli-0.0.1a7/cli/cloud/auth_keys.py
--rw-r--r--   0        0        0     2323 2023-06-22 08:07:25.218764 remotivelabs_cli-0.0.1a7/cli/cloud/brokers.py
--rw-r--r--   0        0        0     1580 2023-06-21 13:16:22.379502 remotivelabs_cli-0.0.1a7/cli/cloud/cloud_cli.py
--rw-r--r--   0        0        0     3132 2023-06-19 13:52:07.776885 remotivelabs_cli-0.0.1a7/cli/cloud/configs.py
--rw-r--r--   0        0        0     1366 2023-06-20 19:11:51.341364 remotivelabs_cli-0.0.1a7/cli/cloud/projects.py
--rw-r--r--   0        0        0     7899 2023-06-22 15:52:20.798411 remotivelabs_cli-0.0.1a7/cli/cloud/recordings.py
--rw-r--r--   0        0        0     3486 2023-06-21 12:56:24.052615 remotivelabs_cli-0.0.1a7/cli/cloud/rest_helper.py
--rw-r--r--   0        0        0     1990 2023-06-20 13:21:18.023240 remotivelabs_cli-0.0.1a7/cli/cloud/service_account_keys.py
--rw-r--r--   0        0        0     1615 2023-06-21 14:06:01.150934 remotivelabs_cli-0.0.1a7/cli/cloud/service_accounts.py
--rw-r--r--   0        0        0      141 2022-10-25 14:33:01.608000 remotivelabs_cli-0.0.1a7/cli/lib/__about__.py
--rw-r--r--   0        0        0     4938 2023-06-21 12:13:16.823623 remotivelabs_cli-0.0.1a7/cli/lib/broker.py
--rw-r--r--   0        0        0      432 2023-06-22 08:58:34.023633 remotivelabs_cli-0.0.1a7/cli/remotive.py
--rw-r--r--   0        0        0       77 2023-06-08 06:07:23.995982 remotivelabs_cli-0.0.1a7/cli/requirements.txt
--rw-r--r--   0        0        0       63 2023-03-21 06:24:07.422989 remotivelabs_cli-0.0.1a7/cli/test/test_simple.py
--rw-r--r--   0        0        0      498 2023-06-22 16:21:19.512051 remotivelabs_cli-0.0.1a7/pyproject.toml
--rw-r--r--   0        0        0     2747 1970-01-01 00:00:00.000000 remotivelabs_cli-0.0.1a7/PKG-INFO
+-rw-r--r--   0        0        0      608 2023-06-19 13:55:54.232642 remotivelabs_cli-0.0.1a8/LICENSE
+-rw-r--r--   0        0        0     2095 2023-06-22 08:12:57.643193 remotivelabs_cli-0.0.1a8/README.md
+-rw-r--r--   0        0        0      122 2022-10-26 14:05:47.581000 remotivelabs_cli-0.0.1a8/cli/__about__.py
+-rw-r--r--   0        0        0       26 2022-10-26 11:41:55.030088 remotivelabs_cli-0.0.1a8/cli/__init__.py
+-rw-r--r--   0        0        0     4011 2023-06-21 12:52:00.336557 remotivelabs_cli-0.0.1a8/cli/brokers.py
+-rw-r--r--   0        0        0        1 2022-10-24 12:45:02.134227 remotivelabs_cli-0.0.1a8/cli/cloud/__init__.py
+-rw-r--r--   0        0        0     3538 2023-06-22 08:03:29.813439 remotivelabs_cli-0.0.1a8/cli/cloud/auth.py
+-rw-r--r--   0        0        0     2942 2023-06-28 08:27:04.993369 remotivelabs_cli-0.0.1a8/cli/cloud/auth_keys.py
+-rw-r--r--   0        0        0     2323 2023-06-22 08:07:25.218764 remotivelabs_cli-0.0.1a8/cli/cloud/brokers.py
+-rw-r--r--   0        0        0     1580 2023-06-21 13:16:22.379502 remotivelabs_cli-0.0.1a8/cli/cloud/cloud_cli.py
+-rw-r--r--   0        0        0     3132 2023-06-19 13:52:07.776885 remotivelabs_cli-0.0.1a8/cli/cloud/configs.py
+-rw-r--r--   0        0        0     1366 2023-06-20 19:11:51.341364 remotivelabs_cli-0.0.1a8/cli/cloud/projects.py
+-rw-r--r--   0        0        0     9353 2023-06-28 11:30:46.601114 remotivelabs_cli-0.0.1a8/cli/cloud/recordings.py
+-rw-r--r--   0        0        0     3498 2023-06-28 09:33:40.616990 remotivelabs_cli-0.0.1a8/cli/cloud/rest_helper.py
+-rw-r--r--   0        0        0     1990 2023-06-20 13:21:18.023240 remotivelabs_cli-0.0.1a8/cli/cloud/service_account_keys.py
+-rw-r--r--   0        0        0     1615 2023-06-21 14:06:01.150934 remotivelabs_cli-0.0.1a8/cli/cloud/service_accounts.py
+-rw-r--r--   0        0        0      141 2022-10-25 14:33:01.608000 remotivelabs_cli-0.0.1a8/cli/lib/__about__.py
+-rw-r--r--   0        0        0     4938 2023-06-21 12:13:16.823623 remotivelabs_cli-0.0.1a8/cli/lib/broker.py
+-rw-r--r--   0        0        0      432 2023-06-22 08:58:34.023633 remotivelabs_cli-0.0.1a8/cli/remotive.py
+-rw-r--r--   0        0        0       77 2023-06-08 06:07:23.995982 remotivelabs_cli-0.0.1a8/cli/requirements.txt
+-rw-r--r--   0        0        0       63 2023-03-21 06:24:07.422989 remotivelabs_cli-0.0.1a8/cli/test/test_simple.py
+-rw-r--r--   0        0        0      498 2023-06-28 11:40:42.815263 remotivelabs_cli-0.0.1a8/pyproject.toml
+-rw-r--r--   0        0        0     2747 1970-01-01 00:00:00.000000 remotivelabs_cli-0.0.1a8/PKG-INFO
```

### Comparing `remotivelabs_cli-0.0.1a7/LICENSE` & `remotivelabs_cli-0.0.1a8/LICENSE`

 * *Files identical despite different names*

### Comparing `remotivelabs_cli-0.0.1a7/README.md` & `remotivelabs_cli-0.0.1a8/README.md`

 * *Files identical despite different names*

### Comparing `remotivelabs_cli-0.0.1a7/cli/brokers.py` & `remotivelabs_cli-0.0.1a8/cli/brokers.py`

 * *Files identical despite different names*

### Comparing `remotivelabs_cli-0.0.1a7/cli/cloud/auth.py` & `remotivelabs_cli-0.0.1a8/cli/cloud/auth.py`

 * *Files identical despite different names*

### Comparing `remotivelabs_cli-0.0.1a7/cli/cloud/auth_keys.py` & `remotivelabs_cli-0.0.1a8/cli/cloud/auth_keys.py`

 * *Files 1% similar despite different names*

```diff
@@ -48,15 +48,15 @@
     Show contents of specified key file
     """
     print(read_file(file))
 
 
 @app.command()
 def activate(
-        file: str = typer.Option(..., help="File name")):
+        file: str = typer.Argument(..., help="File name")):
     """
     Activate a key file to be used for authentication.
 
     --file
 
     This will be used as the current access token in all subsequent requests. This would
     be the same as login with a browser.
```

### Comparing `remotivelabs_cli-0.0.1a7/cli/cloud/brokers.py` & `remotivelabs_cli-0.0.1a8/cli/cloud/brokers.py`

 * *Files identical despite different names*

### Comparing `remotivelabs_cli-0.0.1a7/cli/cloud/cloud_cli.py` & `remotivelabs_cli-0.0.1a8/cli/cloud/cloud_cli.py`

 * *Files identical despite different names*

### Comparing `remotivelabs_cli-0.0.1a7/cli/cloud/configs.py` & `remotivelabs_cli-0.0.1a8/cli/cloud/configs.py`

 * *Files identical despite different names*

### Comparing `remotivelabs_cli-0.0.1a7/cli/cloud/projects.py` & `remotivelabs_cli-0.0.1a8/cli/cloud/projects.py`

 * *Files identical despite different names*

### Comparing `remotivelabs_cli-0.0.1a7/cli/cloud/recordings.py` & `remotivelabs_cli-0.0.1a8/cli/cloud/recordings.py`

 * *Files 14% similar despite different names*

```diff
@@ -8,74 +8,74 @@
 import json
 import shutil
 from rich.progress import Progress, SpinnerColumn, TextColumn
 from . import rest_helper as rest
 
 app = typer.Typer()
 
+
 def uid(p):
     print(p)
     return p['uid']
 
+# to be used in options
+#autocompletion=project_names)
 def project_names():
     r = requests.get(f'{rest.base_url}/api/bu/{rest.org}/project', headers=rest.headers)
-    #sys.stderr.write(r.text)
+    # sys.stderr.write(r.text)
     if r.status_code == 200:
         projects = r.json()
         names = map(lambda p: p['uid'], projects)
         return (list(names))
     else:
         sys.stderr.write(f"Could not list projects due to {r.status_code}\n")
-        #os.kill(signal.SIGSTOP)
+        # os.kill(signal.SIGSTOP)
         raise typer.Exit(0)
-        #return []
+        # return []
 
-        #return map(list(r.json()), lambda e: e.uid)
-#    return ["beamyhack"]
+        # return map(list(r.json()), lambda e: e.uid)
 
 
-@app.command("list", help="Lists recordings in project")
-def listRecordings(type: str = typer.Argument(default="all", help="all, processing, recent"),
-         project: str = typer.Option(..., help="Project ID", envvar='REMOTIVE_CLOUD_PROJECT',
-                                     autocompletion=project_names)):
+#    return ["beamyhack"]
 
 
-    if project == "_":
-        print("Something went wrong")
-        raise typer.Exit()
+@app.command("list")
+def listRecordings(is_processing: bool = typer.Option(default=False, help="Use this option to see only those that are beeing processed or are invalid"),
+                   project: str = typer.Option(..., help="Project ID", envvar='REMOTIVE_CLOUD_PROJECT')):
+    """
+    List all recording sessions in a project. You can choose to see all valid recordings (default) or use
+    --is-processing and you will get those that are currently beeing processed or that failed to be validated.
 
-    if type == "all":
-        rest.handle_get(f"/api/project/{project}/files/recording")
-    elif type == "recent":
-        rest.handle_get(f"/api/project/{project}/files/recording/recent")
-    elif type == "processing":
+    """
+
+    if is_processing:
         rest.handle_get(f"/api/project/{project}/files/recording/processing")
     else:
-        print("Unknown type: " + type)
+        rest.handle_get(f"/api/project/{project}/files/recording")
+
 
 
 @app.command(help="Shows details about a specific recording in project")
-def describe(name: str, project: str = typer.Option(..., help="Project ID", envvar='REMOTIVE_CLOUD_PROJECT')):
-    rest.handle_get(f"/api/project/{project}/files/recording/{name}")
+def describe(recording_session: str = typer.Argument(..., help="Recording session id"),
+
+             project: str = typer.Option(..., help="Project ID", envvar='REMOTIVE_CLOUD_PROJECT')):
+    rest.handle_get(f"/api/project/{project}/files/recording/{recording_session}")
 
 
 def doStart(name: str, project: str, api_key: str, return_response: bool = False):
     if api_key == "":
         body = {"size": "S"}
     else:
         body = {"size": "S", 'apiKey': api_key}
     return rest.handle_post(f"/api/project/{project}/brokers/{name}", body=json.dumps(body),
                             return_response=return_response)
 
 
-
-
-
 @app.command(help="Plays all recording files or a single recording")
-def play(recording_session: str = typer.Option(..., help="Recording session id"),
+def play(recording_session: str = typer.Argument(..., help="Recording session id"),
          ensure_broker_started: bool = typer.Option(default=False, help="Ensure broker exists, start otherwise"),
          broker: str = typer.Option(..., help="Broker name to play on"),
          project: str = typer.Option(..., help="Project ID", envvar='REMOTIVE_CLOUD_PROJECT')):
     with Progress(
             SpinnerColumn(),
             TextColumn("[progress.description]{task.description}"),
             transient=True,
@@ -97,96 +97,122 @@
         elif r.status_code != 200:
             sys.stderr.write(f"Got http status code {r.status_code}")
             typer.Exit(0)
 
         progress.add_task(
             description=f"Uploading recording {recording_session} to {broker} and setting play mode to pause...",
             total=None)
-        #if recording_file == "":
+        # if recording_file == "":
         #    rest.handle_get(f"/api/project/{project}/files/recording/{recording_session}/upload",
         #                    params={'brokerName': broker})
-        #else:
+        # else:
         rest.handle_get(f"/api/project/{project}/files/recording/{recording_session}/upload",
-                            params={'brokerName': broker})
+                        params={'brokerName': broker})
 
 
-@app.command(help="Downloads the specified recording file")
-def download(recording_session: str = typer.Option(..., help="Recording session id"),
-             recording_file: str = typer.Option("", help="Recording file"),
-             project: str = typer.Option(..., help="Project ID", envvar='REMOTIVE_CLOUD_PROJECT')):
+@app.command(help="Downloads the specified recording file to disk")
+def download_recording_file(
+        recording_file_name: str = typer.Argument(..., help="Recording file to download"),
+        recording_session: str = typer.Option(..., help="Recording session id that this file belongs to", envvar='REMOTIVE_CLOUD_RECORDING_SESSION'),
+        project: str = typer.Option(..., help="Project ID", envvar='REMOTIVE_CLOUD_PROJECT')):
     with Progress(
             SpinnerColumn(),
             TextColumn("[progress.description]{task.description}"),
             transient=True,
     ) as progress:
-        progress.add_task(description=f"Downloading {recording_file}", total=None)
+        progress.add_task(description=f"Downloading {recording_file_name}", total=None)
 
         # First request the download url from cloud. This is a public signed url that is valid
         # for a short period of time
         rest.ensure_auth_token()
         get_signed_url_resp = requests.get(
-            f'{rest.base_url}/api/project/{project}/files/recording/{recording_session}/recording-file/{recording_file}',
+            f'{rest.base_url}/api/project/{project}/files/recording/{recording_session}/recording-file/{recording_file_name}',
             headers=rest.headers, allow_redirects=True)
         if get_signed_url_resp.status_code == 200:
 
             # Next download the actual file
             download_resp = requests.get(url=get_signed_url_resp.json()["downloadUrl"], stream=True)
             if download_resp.status_code == 200:
-                with open(recording_file, 'wb') as out_file:
+                with open(recording_file_name, 'wb') as out_file:
                     shutil.copyfileobj(download_resp.raw, out_file)
-                print(f"{recording_file} downloaded")
+                print(f"{recording_file_name} downloaded")
             else:
                 sys.stderr.write(download_resp.text)
                 sys.stderr.write(f"Got http status {download_resp.status_code}\n")
         else:
             sys.stderr.write(get_signed_url_resp.text)
             sys.stderr.write(f"Got http dd status {get_signed_url_resp.status_code}\n")
 
 
-@app.command()
-def upload(file: str, project: str = typer.Option(..., help="Project ID", envvar='REMOTIVE_CLOUD_PROJECT')):
+@app.command(name="delete")
+def delete(recording_session: str = typer.Argument(..., help="Recording session id"),
+           project: str = typer.Option(..., help="Project ID", envvar='REMOTIVE_CLOUD_PROJECT')):
+    """
+    Deletes the specified recording session including all media files and configurations.
+
+    """
+    rest.handle_delete(f"/api/project/{project}/files/recording/{recording_session}")
+
+
+@app.command(name="delete-recording-file")
+def delete_recording_file(recording_file_name: str = typer.Argument(..., help="Recording file to download"),
+           recording_session: str = typer.Option(..., help="Recording session id that this file belongs to", envvar='REMOTIVE_CLOUD_RECORDING_SESSION'),
+           project: str = typer.Option(..., help="Project ID", envvar='REMOTIVE_CLOUD_PROJECT')):
+    """
+    Deletes the specified recording file
+
+    """
+    rest.handle_delete(f'/api/project/{project}/files/recording/{recording_session}/recording-file/{recording_file_name}')
 
+@app.command()
+def upload(path: str  = typer.Argument(..., help="Path to valid recording to upload"),
+           project: str = typer.Option(..., help="Project ID", envvar='REMOTIVE_CLOUD_PROJECT')):
     with Progress(
             SpinnerColumn(),
             TextColumn("[progress.description]{task.description}"),
             transient=True,
     ) as progress:
         progress.add_task(description=f"Uploading {file}", total=None)
 
         filename = os.path.basename(file)
         rest.ensure_auth_token()
         rest.headers["content-type"] = "application/octet-stream"
         r = requests.post(f"{rest.base_url}/api/project/{project}/files/recording/{filename}", headers=rest.headers)
         if r.status_code == 200:
             headers = {}
             headers["content-type"] = "application/x-www-form-urlencoded"
-            r = requests.put(r.text, open(file, 'rb'), headers = headers)
-            print("File successfully uploaded, please run 'remotive cloud recordings list' to verify that the recording was successfully processed")
+            r = requests.put(r.text, open(file, 'rb'), headers=headers)
+            print(
+                "File successfully uploaded, please run 'remotive cloud recordings list' to verify that the recording was successfully processed")
         else:
             print(r.text)
 
-@app.command()
-def download_config(
-        recording_session: str = typer.Option(..., help="Recording session id"),
-        broker_config_name: str = typer.Option(..., help="Broker config name"),
+
+@app.command(help="Downloads the specified broker configuration directory as zip file")
+def download_configuration(
+        broker_config_name: str = typer.Argument(..., help="Broker config name"),
+        recording_session: str = typer.Option(..., help="Recording session id", envvar='REMOTIVE_CLOUD_RECORDING_SESSION'),
         project: str = typer.Option(..., help="Project ID", envvar='REMOTIVE_CLOUD_PROJECT')
 ):
     rest.ensure_auth_token()
-    #print(rest.base_url)
-    r = rest.handle_get(url=f"/api/project/{project}/files/recording/{recording_session}/configuration/{broker_config_name}", return_response=True)
-    #print(r.status_code)
-    #print(r.headers)
-    #print(get_filename_from_cd(r.headers.get('content-disposition')))
-    filename=get_filename_from_cd(r.headers.get('content-disposition'))
+    # print(rest.base_url)
+    r = rest.handle_get(
+        url=f"/api/project/{project}/files/recording/{recording_session}/configuration/{broker_config_name}",
+        return_response=True)
+    # print(r.status_code)
+    # print(r.headers)
+    # print(get_filename_from_cd(r.headers.get('content-disposition')))
+    filename = get_filename_from_cd(r.headers.get('content-disposition'))
     open(filename, 'wb').write(r.content)
     print(f'Downloaded file {filename}')
 
+
 def get_filename_from_cd(cd):
     """
     Get filename from content-disposition
     """
     if not cd:
         return None
     fname = re.findall('filename=(.+)', cd)
     if len(fname) == 0:
         return None
-    return fname[0]
+    return fname[0]
```

### Comparing `remotivelabs_cli-0.0.1a7/cli/cloud/rest_helper.py` & `remotivelabs_cli-0.0.1a8/cli/cloud/rest_helper.py`

 * *Files 2% similar despite different names*

```diff
@@ -30,19 +30,19 @@
 
 headers = {}
 org = ""
 
 
 def ensure_auth_token():
 
-    if 'REMOTIVE_CLOUD_ORGANISATION' not in os.environ:
-        print('You must first set the organisation id to use: export REMOTIVE_CLOUD_ORGANISATION=organisationUid')
-        raise typer.Exit()
+    #if 'REMOTIVE_CLOUD_ORGANISATION' not in os.environ:
+    #    print('You must first set the organisation id to use: export REMOTIVE_CLOUD_ORGANISATION=organisationUid')
+    #    raise typer.Exit()
     global org
-    org = os.environ["REMOTIVE_CLOUD_ORGANISATION"]
+    #org = os.environ["REMOTIVE_CLOUD_ORGANISATION"]
 
     if not exists(str(Path.home()) + "/.config/.remotive/cloud.secret.token"):
         print("Access token not found, please login first")
         raise typer.Exit()
 
     f = open(str(Path.home()) + "/.config/.remotive/cloud.secret.token", "r")
     token = f.read()
@@ -76,15 +76,15 @@
 
 def handle_delete(url, params={}):
     ensure_auth_token()
     r = requests.delete(f'{base_url}{url}', headers=headers, params=params)
     if r.status_code == 200:
         print(json.dumps(r.json()))
     if r.status_code == 204:
-        sys.stderr.write('empty result\n')
+        sys.stderr.write('Successfully deleted\n')
     else:
         print(f'Got status code: {r.status_code}')
         print(r.text)
 
 
 def handle_post(url, body=None, params={}, return_response: bool = False):
     ensure_auth_token()
```

### Comparing `remotivelabs_cli-0.0.1a7/cli/cloud/service_account_keys.py` & `remotivelabs_cli-0.0.1a8/cli/cloud/service_account_keys.py`

 * *Files identical despite different names*

### Comparing `remotivelabs_cli-0.0.1a7/cli/cloud/service_accounts.py` & `remotivelabs_cli-0.0.1a8/cli/cloud/service_accounts.py`

 * *Files identical despite different names*

### Comparing `remotivelabs_cli-0.0.1a7/cli/lib/broker.py` & `remotivelabs_cli-0.0.1a8/cli/lib/broker.py`

 * *Files identical despite different names*

### Comparing `remotivelabs_cli-0.0.1a7/PKG-INFO` & `remotivelabs_cli-0.0.1a8/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: remotivelabs-cli
-Version: 0.0.1a7
+Version: 0.0.1a8
 Summary: 
 Author: Johan Rask
 Author-email: johan.rask@remotivelabs.com
 Requires-Python: >=3.9,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
```

