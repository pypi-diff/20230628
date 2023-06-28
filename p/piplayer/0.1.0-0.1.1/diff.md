# Comparing `tmp/piplayer-0.1.0.tar.gz` & `tmp/piplayer-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "piplayer-0.1.0.tar", max compression
+gzip compressed data, was "piplayer-0.1.1.tar", max compression
```

## Comparing `piplayer-0.1.0.tar` & `piplayer-0.1.1.tar`

### file list

```diff
@@ -1,4 +1,4 @@
--rw-r--r--   0        0        0     2230 2023-06-24 18:32:41.358634 piplayer-0.1.0/README.md
--rw-r--r--   0        0        0     5972 2023-06-26 15:55:00.886197 piplayer-0.1.0/piplayer/__init__.py
--rw-r--r--   0        0        0      512 2023-06-26 15:57:23.680870 piplayer-0.1.0/pyproject.toml
--rw-r--r--   0        0        0     2940 1970-01-01 00:00:00.000000 piplayer-0.1.0/PKG-INFO
+-rw-r--r--   0        0        0     2230 2023-06-24 18:32:41.358634 piplayer-0.1.1/README.md
+-rw-r--r--   0        0        0     6170 2023-06-26 16:36:13.900620 piplayer-0.1.1/piplayer/__init__.py
+-rw-r--r--   0        0        0      512 2023-06-28 15:46:00.758198 piplayer-0.1.1/pyproject.toml
+-rw-r--r--   0        0        0     2940 1970-01-01 00:00:00.000000 piplayer-0.1.1/PKG-INFO
```

### Comparing `piplayer-0.1.0/README.md` & `piplayer-0.1.1/README.md`

 * *Files identical despite different names*

### Comparing `piplayer-0.1.0/piplayer/__init__.py` & `piplayer-0.1.1/piplayer/__init__.py`

 * *Files 5% similar despite different names*

```diff
@@ -57,24 +57,14 @@
             then
                 sudo apt-get update
                 sudo apt-get -y install vlc
             fi
             """
         self.remote_run(command)
 
-    def prepare_video_paths(self):
-        videos = self.videos
-
-        if isinstance(videos, str):
-            videos = [videos]
-
-        videos = [glob(v) for v in videos]
-        videos = [v for sublist in videos for v in sublist]
-
-        self.videos = videos
 
     def copy_videos(self):
         self.create_folder()
         self.send_commands()
 
         for v in self.videos:
             command = f"""rsync -avzP --ignore-existing {v} {self.user}@{self.host}:~/videos/"""
@@ -136,43 +126,58 @@
             self.remote_run(command)
 
             self.remote_run("systemctl --user enable player.service")
             self.remote_run("systemctl --user daemon-reload")
             self.remote_run("systemctl --user restart player.service")
 
     def run(self):
-        self.prepare_video_paths()
         self.copy_videos()
         self.install_vlc()
         self.make_playlist()
         self.create_service()
         self.send_commands()
 
 
+def prepare_video_paths(videos, basepath):
+
+    if isinstance(videos, str):
+        videos = [videos]
+
+    if basepath:
+        videos = [glob(os.path.join(basepath, v)) for v in videos]
+    else:
+        videos = [glob(v) for v in videos]
+    videos = [v for sublist in videos for v in sublist]
+
+    return videos
 
 def main(project_file=None, hosts=None, videos=None):
     settings = {}
     players = []
+    basepath = None
 
     if project_file:
         with open(project_file, "r") as infile:
             data = yaml.safe_load(infile)
             settings = data.get("settings", {})
             players = data.get("players", [])
+            basepath = os.path.dirname(os.path.abspath(project_file))
+            print(basepath)
     elif hosts is not None and videos is not None:
         for h in hosts:
             players.append({"host": h, "videos": videos})
 
     # merge settings and defaults
     settings = {**DEFAULTS, **settings}
 
     # for each player, merge settings
     players = [{**settings, **p} for p in players]
 
     for p in players:
+        p['videos'] = prepare_video_paths(p['videos'], basepath)
         p = PiPlayer(**p)
         p.run()
 
 
 def extant_file(x):
     """
     'Type' for argparse - checks that file exists but does not open.
```

### Comparing `piplayer-0.1.0/pyproject.toml` & `piplayer-0.1.1/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "piplayer"
-version = "0.1.0"
+version = "0.1.1"
 description = "A command line interface to help set up a raspberry pi as a video player."
 authors = ["Sam Lavigne <splavigne@gmail.com>"]
 readme = "README.md"
 homepage = "https://github.com/antiboredom/piplayer"
 repository = "https://github.com/antiboredom/piplayer"
 
 [tool.poetry.dependencies]
```

### Comparing `piplayer-0.1.0/PKG-INFO` & `piplayer-0.1.1/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: piplayer
-Version: 0.1.0
+Version: 0.1.1
 Summary: A command line interface to help set up a raspberry pi as a video player.
 Home-page: https://github.com/antiboredom/piplayer
 Author: Sam Lavigne
 Author-email: splavigne@gmail.com
 Requires-Python: >=3.7,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.7
```

