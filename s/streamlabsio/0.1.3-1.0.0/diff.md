# Comparing `tmp/streamlabsio-0.1.3.tar.gz` & `tmp/streamlabsio-1.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "streamlabsio-0.1.3.tar", max compression
+gzip compressed data, was "streamlabsio-1.0.0.tar", max compression
```

## Comparing `streamlabsio-0.1.3.tar` & `streamlabsio-1.0.0.tar`

### file list

```diff
@@ -1,8 +1,9 @@
--rw-r--r--   0        0        0     1091 2022-11-13 08:19:22.113345 streamlabsio-0.1.3/LICENSE
--rw-r--r--   0        0        0      686 2022-11-14 19:22:46.490741 streamlabsio-0.1.3/pyproject.toml
--rw-r--r--   0        0        0     2046 2022-11-14 19:26:53.239199 streamlabsio-0.1.3/README.md
--rw-r--r--   0        0        0       29 2022-11-13 08:41:46.471896 streamlabsio-0.1.3/streamlabsio/__init__.py
--rw-r--r--   0        0        0     1892 2022-11-14 19:25:51.651288 streamlabsio-0.1.3/streamlabsio/client.py
--rw-r--r--   0        0        0      505 2022-11-14 19:15:57.911385 streamlabsio-0.1.3/streamlabsio/models.py
--rw-r--r--   0        0        0     2942 2022-11-14 19:30:45.992397 streamlabsio-0.1.3/setup.py
--rw-r--r--   0        0        0     2744 2022-11-14 19:30:45.992397 streamlabsio-0.1.3/PKG-INFO
+-rw-r--r--   0        0        0     1091 2022-11-13 08:19:22.113345 streamlabsio-1.0.0/LICENSE
+-rw-r--r--   0        0        0      962 2023-06-27 22:58:54.075697 streamlabsio-1.0.0/pyproject.toml
+-rw-r--r--   0        0        0     2582 2023-06-28 02:39:37.040396 streamlabsio-1.0.0/README.md
+-rw-r--r--   0        0        0       29 2023-06-27 16:58:43.358807 streamlabsio-1.0.0/streamlabsio/__init__.py
+-rw-r--r--   0        0        0     3108 2023-06-28 02:09:50.328366 streamlabsio-1.0.0/streamlabsio/client.py
+-rw-r--r--   0        0        0      104 2023-06-27 23:54:01.479898 streamlabsio-1.0.0/streamlabsio/error.py
+-rw-r--r--   0        0        0      505 2023-06-27 20:27:01.395526 streamlabsio-1.0.0/streamlabsio/models.py
+-rw-r--r--   0        0        0     3579 2023-06-28 02:42:00.557889 streamlabsio-1.0.0/setup.py
+-rw-r--r--   0        0        0     3359 2023-06-28 02:42:00.557889 streamlabsio-1.0.0/PKG-INFO
```

### Comparing `streamlabsio-0.1.3/LICENSE` & `streamlabsio-1.0.0/LICENSE`

 * *Files identical despite different names*

### Comparing `streamlabsio-0.1.3/README.md` & `streamlabsio-1.0.0/README.md`

 * *Files 21% similar despite different names*

```diff
@@ -1,19 +1,23 @@
 [![PyPI version](https://badge.fury.io/py/streamlabsio.svg)](https://badge.fury.io/py/streamlabsio)
 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/onyx-and-iris/streamlabs-socketio-py/blob/dev/LICENSE)
 [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
 [![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)
 
 # A Python client for Streamlabs Socket API
 
+For an outline of past/future changes refer to: [CHANGELOG](CHANGELOG.md)
+
 ### Requirements
 
 -   A Streamlabs Socket API key.
     -   You can acquire this by logging into your Streamlabs.com dashboard then `Settings->Api Settings->API Tokens`
 
+-   Python 3.8 or greater
+
 ### How to install using pip
 
 ```
 pip install streamlabsio
 ```
 
 ### How to Use
@@ -33,16 +37,16 @@
 
 Example `__main__.py`:
 
 ```python
 import streamlabsio
 
 
-def on_twitch_event(event, msg):
-    print(f"{event}: {msg.attrs()}")
+def on_twitch_event(event, data):
+    print(f"{event}: {data.attrs()}")
 
 
 def main():
     with streamlabsio.connect(token="<apikey>") as client:
         client.obs.on("streamlabs", on_twitch_event)
         client.obs.on("twitch_account", on_twitch_event)
 
@@ -54,21 +58,37 @@
     main()
 ```
 
 #### note
 
 From the [SocketIO docs](https://python-socketio.readthedocs.io/en/latest/client.html#managing-background-tasks), `client.sio.wait()` may be used if your application has nothing to do in the main thread.
 
+### Client class
+`streamlabsio.connect(token="<apikey>", raw=False)`
+
+The following keyword arguments may be passed:
+
+-   `token`: str   Streamlabs SocketIO api token.
+-   `raw`: boolean=False    Receive raw json objects.
+
 ### Attributes
 
-For event messages you may inspect the available attributes using `attrs()`.
+For event data you may inspect the available attributes using `attrs()`.
 
 example:
 
 ```python
-def on_twitch_event(event, msg):
-    print(f"{event}: {msg.attrs()}")
+def on_twitch_event(event, data):
+    print(f"{event}: {data.attrs()}")
 ```
 
+### Errors
+
+-   `SteamlabsSIOConnectionError`: Exception raised when connection errors occur
+
+### Logging
+
+To view raw incoming event data set logging level to DEBUG. Check `debug` example.
+
 ### Official Documentation
 
 -   [Streamlabs Socket API](https://dev.streamlabs.com/docs/socket-api)
```

### Comparing `streamlabsio-0.1.3/streamlabsio/client.py` & `streamlabsio-1.0.0/streamlabsio/client.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,58 +1,86 @@
 import logging
 from pathlib import Path
+from typing import Optional
 
 import socketio
 from observable import Observable
 
-try:
-    import tomllib
-except ModuleNotFoundError:
-    import tomli as tomllib
-
+from .error import SteamlabsSIOConnectionError
 from .models import as_dataclass
 
+logger = logging.getLogger(__name__)
 
-class Client:
-    logger = logging.getLogger("socketio.client")
 
-    def __init__(self, token=None):
+class Client:
+    def __init__(self, token=None, raw=False):
+        self.logger = logger.getChild(self.__class__.__name__)
         self.token = token or self._token_from_toml()
+        self._raw = raw
         self.sio = socketio.Client()
         self.sio.on("connect", self.connect_handler)
         self.sio.on("event", self.event_handler)
         self.sio.on("disconnect", self.disconnect_handler)
         self.obs = Observable()
         self.streamlabs = ("donation",)
         self.twitch = ("follow", "subscription", "host", "bits", "raids")
         self.youtube = ("follow", "subscription", "superchat")
 
     def __enter__(self):
-        self.sio.connect(f"https://sockets.streamlabs.com?token={self.token}")
+        try:
+            self.sio.connect(f"https://sockets.streamlabs.com?token={self.token}")
+        except socketio.exceptions.ConnectionError as e:
+            self.logger.exception(f"{type(e).__name__}: {e}")
+            raise SteamlabsSIOConnectionError(
+                "no connection could be established to the Streamlabs SIO server"
+            ) from e
         return self
 
     def _token_from_toml(self) -> str:
-        filepath = Path.cwd() / "config.toml"
-        with open(filepath, "rb") as f:
-            conn = tomllib.load(f)
-            assert "token" in conn.get("streamlabs")
-        return conn["streamlabs"].get("token")
+        try:
+            import tomllib
+        except ModuleNotFoundError:
+            import tomli as tomllib
+
+        def get_filepath() -> Optional[Path]:
+            filepaths = (
+                Path.cwd() / "config.toml",
+                Path.home() / ".config" / "streamlabsio" / "config.toml",
+            )
+            for filepath in filepaths:
+                if filepath.exists():
+                    return filepath
+
+        try:
+            filepath = get_filepath()
+            if not filepath:
+                raise FileNotFoundError("config.toml was not found")
+            with open(filepath, "rb") as f:
+                conn = tomllib.load(f)
+                assert "token" in conn.get(
+                    "streamlabs"
+                ), "token not found in config.toml"
+            return conn["streamlabs"].get("token")
+        except (FileNotFoundError, tomllib.TOMLDecodeError) as e:
+            self.logger.error(f"{type(e).__name__}: {e}")
+            raise
 
     def connect_handler(self):
         self.logger.info("Connected to Streamlabs Socket API")
 
     def event_handler(self, data):
         if "for" in data and data["type"] in set(
             self.streamlabs + self.twitch + self.youtube
         ):
             self.obs.trigger(
                 data["for"],
                 data["type"],
-                as_dataclass(data["type"], *data["message"]),
+                data if self._raw else as_dataclass(data["type"], *data["message"]),
             )
+            self.logger.debug(data)
 
     def disconnect_handler(self):
         self.logger.info("Disconnected from Streamlabs Socket API")
 
     def __exit__(self, exc_type, exc_val, exc_tb):
         self.sio.disconnect()
```

### Comparing `streamlabsio-0.1.3/setup.py` & `streamlabsio-1.0.0/setup.py`

 * *Files 18% similar despite different names*

```diff
@@ -11,26 +11,30 @@
 ['observable>=1.0.3,<2.0.0',
  'python-engineio==3.14.2',
  'python-socketio[client]==4.6.0']
 
 extras_require = \
 {':python_version < "3.11"': ['tomli>=2.0.1,<3.0.0']}
 
+entry_points = \
+{'console_scripts': ['debug = scripts:ex_debug']}
+
 setup_kwargs = {
     'name': 'streamlabsio',
-    'version': '0.1.3',
+    'version': '1.0.0',
     'description': 'Get real time Twitch/Youtube events through Streamlabs SocketIO API',
-    'long_description': '[![PyPI version](https://badge.fury.io/py/streamlabsio.svg)](https://badge.fury.io/py/streamlabsio)\n[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/onyx-and-iris/streamlabs-socketio-py/blob/dev/LICENSE)\n[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)\n[![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)\n\n# A Python client for Streamlabs Socket API\n\n### Requirements\n\n-   A Streamlabs Socket API key.\n    -   You can acquire this by logging into your Streamlabs.com dashboard then `Settings->Api Settings->API Tokens`\n\n### How to install using pip\n\n```\npip install streamlabsio\n```\n\n### How to Use\n\nYou may store your api key in a `config.toml` file, its contents should resemble:\n\n```toml\n[streamlabs]\ntoken = "<apikey>"\n```\n\nPlace it next to your `__main__.py` file.\n\n#### Otherwise:\n\nYou may pass it as a keyword argument.\n\nExample `__main__.py`:\n\n```python\nimport streamlabsio\n\n\ndef on_twitch_event(event, msg):\n    print(f"{event}: {msg.attrs()}")\n\n\ndef main():\n    with streamlabsio.connect(token="<apikey>") as client:\n        client.obs.on("streamlabs", on_twitch_event)\n        client.obs.on("twitch_account", on_twitch_event)\n\n        # run for 30 seconds then disconnect client from server\n        client.sio.sleep(30)\n\n\nif __name__ == "__main__":\n    main()\n```\n\n#### note\n\nFrom the [SocketIO docs](https://python-socketio.readthedocs.io/en/latest/client.html#managing-background-tasks), `client.sio.wait()` may be used if your application has nothing to do in the main thread.\n\n### Attributes\n\nFor event messages you may inspect the available attributes using `attrs()`.\n\nexample:\n\n```python\ndef on_twitch_event(event, msg):\n    print(f"{event}: {msg.attrs()}")\n```\n\n### Official Documentation\n\n-   [Streamlabs Socket API](https://dev.streamlabs.com/docs/socket-api)\n',
+    'long_description': '[![PyPI version](https://badge.fury.io/py/streamlabsio.svg)](https://badge.fury.io/py/streamlabsio)\n[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/onyx-and-iris/streamlabs-socketio-py/blob/dev/LICENSE)\n[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)\n[![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)\n\n# A Python client for Streamlabs Socket API\n\nFor an outline of past/future changes refer to: [CHANGELOG](CHANGELOG.md)\n\n### Requirements\n\n-   A Streamlabs Socket API key.\n    -   You can acquire this by logging into your Streamlabs.com dashboard then `Settings->Api Settings->API Tokens`\n\n-   Python 3.8 or greater\n\n### How to install using pip\n\n```\npip install streamlabsio\n```\n\n### How to Use\n\nYou may store your api key in a `config.toml` file, its contents should resemble:\n\n```toml\n[streamlabs]\ntoken = "<apikey>"\n```\n\nPlace it next to your `__main__.py` file.\n\n#### Otherwise:\n\nYou may pass it as a keyword argument.\n\nExample `__main__.py`:\n\n```python\nimport streamlabsio\n\n\ndef on_twitch_event(event, data):\n    print(f"{event}: {data.attrs()}")\n\n\ndef main():\n    with streamlabsio.connect(token="<apikey>") as client:\n        client.obs.on("streamlabs", on_twitch_event)\n        client.obs.on("twitch_account", on_twitch_event)\n\n        # run for 30 seconds then disconnect client from server\n        client.sio.sleep(30)\n\n\nif __name__ == "__main__":\n    main()\n```\n\n#### note\n\nFrom the [SocketIO docs](https://python-socketio.readthedocs.io/en/latest/client.html#managing-background-tasks), `client.sio.wait()` may be used if your application has nothing to do in the main thread.\n\n### Client class\n`streamlabsio.connect(token="<apikey>", raw=False)`\n\nThe following keyword arguments may be passed:\n\n-   `token`: str   Streamlabs SocketIO api token.\n-   `raw`: boolean=False    Receive raw json objects.\n\n### Attributes\n\nFor event data you may inspect the available attributes using `attrs()`.\n\nexample:\n\n```python\ndef on_twitch_event(event, data):\n    print(f"{event}: {data.attrs()}")\n```\n\n### Errors\n\n-   `SteamlabsSIOConnectionError`: Exception raised when connection errors occur\n\n### Logging\n\nTo view raw incoming event data set logging level to DEBUG. Check `debug` example.\n\n### Official Documentation\n\n-   [Streamlabs Socket API](https://dev.streamlabs.com/docs/socket-api)\n',
     'author': 'onyx-and-iris',
     'author_email': 'code@onyxandiris.online',
     'maintainer': None,
     'maintainer_email': None,
     'url': 'https://github.com/onyx-and-iris/streamlabs-socketio-py',
     'packages': packages,
     'package_data': package_data,
     'install_requires': install_requires,
     'extras_require': extras_require,
-    'python_requires': '>=3.10,<4.0',
+    'entry_points': entry_points,
+    'python_requires': '>=3.8,<4.0',
 }
 
 
 setup(**setup_kwargs)
```

### Comparing `streamlabsio-0.1.3/PKG-INFO` & `streamlabsio-1.0.0/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,38 +1,44 @@
 Metadata-Version: 2.1
 Name: streamlabsio
-Version: 0.1.3
+Version: 1.0.0
 Summary: Get real time Twitch/Youtube events through Streamlabs SocketIO API
 Home-page: https://github.com/onyx-and-iris/streamlabs-socketio-py
 License: MIT
 Author: onyx-and-iris
 Author-email: code@onyxandiris.online
-Requires-Python: >=3.10,<4.0
+Requires-Python: >=3.8,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
 Requires-Dist: observable (>=1.0.3,<2.0.0)
 Requires-Dist: python-engineio (==3.14.2)
 Requires-Dist: python-socketio[client] (==4.6.0)
 Requires-Dist: tomli (>=2.0.1,<3.0.0); python_version < "3.11"
 Project-URL: Repository, https://github.com/onyx-and-iris/streamlabs-socketio-py
 Description-Content-Type: text/markdown
 
 [![PyPI version](https://badge.fury.io/py/streamlabsio.svg)](https://badge.fury.io/py/streamlabsio)
 [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/onyx-and-iris/streamlabs-socketio-py/blob/dev/LICENSE)
 [![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
 [![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)
 
 # A Python client for Streamlabs Socket API
 
+For an outline of past/future changes refer to: [CHANGELOG](CHANGELOG.md)
+
 ### Requirements
 
 -   A Streamlabs Socket API key.
     -   You can acquire this by logging into your Streamlabs.com dashboard then `Settings->Api Settings->API Tokens`
 
+-   Python 3.8 or greater
+
 ### How to install using pip
 
 ```
 pip install streamlabsio
 ```
 
 ### How to Use
@@ -52,16 +58,16 @@
 
 Example `__main__.py`:
 
 ```python
 import streamlabsio
 
 
-def on_twitch_event(event, msg):
-    print(f"{event}: {msg.attrs()}")
+def on_twitch_event(event, data):
+    print(f"{event}: {data.attrs()}")
 
 
 def main():
     with streamlabsio.connect(token="<apikey>") as client:
         client.obs.on("streamlabs", on_twitch_event)
         client.obs.on("twitch_account", on_twitch_event)
 
@@ -73,22 +79,38 @@
     main()
 ```
 
 #### note
 
 From the [SocketIO docs](https://python-socketio.readthedocs.io/en/latest/client.html#managing-background-tasks), `client.sio.wait()` may be used if your application has nothing to do in the main thread.
 
+### Client class
+`streamlabsio.connect(token="<apikey>", raw=False)`
+
+The following keyword arguments may be passed:
+
+-   `token`: str   Streamlabs SocketIO api token.
+-   `raw`: boolean=False    Receive raw json objects.
+
 ### Attributes
 
-For event messages you may inspect the available attributes using `attrs()`.
+For event data you may inspect the available attributes using `attrs()`.
 
 example:
 
 ```python
-def on_twitch_event(event, msg):
-    print(f"{event}: {msg.attrs()}")
+def on_twitch_event(event, data):
+    print(f"{event}: {data.attrs()}")
 ```
 
+### Errors
+
+-   `SteamlabsSIOConnectionError`: Exception raised when connection errors occur
+
+### Logging
+
+To view raw incoming event data set logging level to DEBUG. Check `debug` example.
+
 ### Official Documentation
 
 -   [Streamlabs Socket API](https://dev.streamlabs.com/docs/socket-api)
```

