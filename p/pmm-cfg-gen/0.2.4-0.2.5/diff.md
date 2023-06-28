# Comparing `tmp/pmm_cfg_gen-0.2.4.tar.gz` & `tmp/pmm_cfg_gen-0.2.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pmm_cfg_gen-0.2.4.tar", max compression
+gzip compressed data, was "pmm_cfg_gen-0.2.5.tar", max compression
```

## Comparing `pmm_cfg_gen-0.2.4.tar` & `pmm_cfg_gen-0.2.5.tar`

### file list

```diff
@@ -1,35 +1,35 @@
--rw-r--r--   0        0        0    35149 2023-04-01 09:59:32.119583 pmm_cfg_gen-0.2.4/LICENSE
--rw-r--r--   0        0        0     1810 2023-04-24 17:17:02.023284 pmm_cfg_gen-0.2.4/README.md
--rw-r--r--   0        0        0     1246 2023-06-13 01:20:51.816201 pmm_cfg_gen-0.2.4/pyproject.toml
--rw-r--r--   0        0        0       29 2023-04-04 21:44:17.290489 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/.gitignore
--rw-r--r--   0        0        0     1691 2023-04-24 15:14:53.409283 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/__init__.py
--rw-r--r--   0        0        0     5242 2023-06-08 14:36:04.841456 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/config_default.yaml
--rw-r--r--   0        0        0     2809 2023-06-12 17:14:55.748774 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/logging.yaml
--rw-r--r--   0        0        0       27 2023-04-25 13:15:00.359814 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/library.json.j2
--rw-r--r--   0        0        0       24 2023-04-25 13:14:55.063789 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/movie.collection.json.j2
--rw-r--r--   0        0        0     3855 2023-06-13 12:28:08.719838 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/movie.collection.yaml.j2
--rw-r--r--   0        0        0       25 2023-04-21 20:29:02.908227 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/movie.metadata.json.j2
--rw-r--r--   0        0        0     3396 2023-06-13 12:58:26.728929 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/movie.metadata.yaml.j2
--rw-r--r--   0        0        0       24 2023-04-25 13:14:34.303691 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/show.collection.json.j2
--rw-r--r--   0        0        0     3854 2023-06-13 12:50:38.818656 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/show.collection.yaml.j2
--rw-r--r--   0        0        0       24 2023-04-21 20:28:17.955980 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/show.metadata.json.j2
--rw-r--r--   0        0        0     3733 2023-06-13 12:58:33.560963 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/show.metadata.yaml.j2
--rw-r--r--   0        0        0     1107 2023-05-11 19:57:56.303215 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/template.collection.yaml.j2
--rw-r--r--   0        0        0        0 2023-04-03 13:48:27.869541 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/__init__.py
--rw-r--r--   0        0        0     2592 2023-06-08 14:35:32.685306 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/cli_args.py
--rw-r--r--   0        0        0     1956 2023-05-10 00:07:32.747680 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/file_utils.py
--rw-r--r--   0        0        0     1778 2023-04-13 17:07:10.794833 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/logging_utils.py
--rw-r--r--   0        0        0    36895 2023-06-13 12:26:52.555452 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/plex.py
--rw-r--r--   0        0        0     2951 2023-06-12 16:23:04.350525 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/plex_cache.py
--rw-r--r--   0        0        0     2150 2023-06-12 16:23:51.874774 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/plex_stats.py
--rw-r--r--   0        0        0    17322 2023-06-13 00:41:25.266381 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/plex_utils.py
--rwxr-xr-x   0        0        0    14285 2023-06-13 12:50:09.094516 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/pmm_utils.py
--rw-r--r--   0        0        0    18201 2023-06-08 15:54:52.364845 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/settings_utils_v1.py
--rw-r--r--   0        0        0    10122 2023-06-13 02:22:42.005047 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/template_filters.py
--rw-r--r--   0        0        0     5057 2023-06-13 01:24:01.797107 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/template_manager.py
--rwxr-xr-x   0        0        0     4443 2023-05-11 12:21:27.849258 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/time_span.py
--rw-r--r--   0        0        0     2691 2023-04-10 21:13:51.972712 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/timer.py
--rw-r--r--   0        0        0     2579 2023-04-26 13:50:19.226275 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/tmdb_utils.py
--rw-r--r--   0        0        0     1361 2023-04-24 15:15:17.785439 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/trakt_utils.py
--rw-r--r--   0        0        0     1514 2023-04-10 21:13:52.064713 pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/tvdb_utils.py
--rw-r--r--   0        0        0     3115 1970-01-01 00:00:00.000000 pmm_cfg_gen-0.2.4/PKG-INFO
+-rw-r--r--   0        0        0    35149 2023-04-01 09:59:32.119583 pmm_cfg_gen-0.2.5/LICENSE
+-rw-r--r--   0        0        0     2502 2023-06-13 21:13:26.509716 pmm_cfg_gen-0.2.5/README.md
+-rw-r--r--   0        0        0     1263 2023-06-28 13:11:14.647360 pmm_cfg_gen-0.2.5/pyproject.toml
+-rw-r--r--   0        0        0       29 2023-04-04 21:44:17.290489 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/.gitignore
+-rw-r--r--   0        0        0     1691 2023-04-24 15:14:53.409283 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/__init__.py
+-rw-r--r--   0        0        0     5242 2023-06-08 14:36:04.841456 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/config_default.yaml
+-rw-r--r--   0        0        0     2705 2023-06-13 15:55:55.365775 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/logging.yaml
+-rw-r--r--   0        0        0       27 2023-04-25 13:15:00.359814 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/library.json.j2
+-rw-r--r--   0        0        0       24 2023-04-25 13:14:55.063789 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/movie.collection.json.j2
+-rw-r--r--   0        0        0     3855 2023-06-13 12:28:08.719838 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/movie.collection.yaml.j2
+-rw-r--r--   0        0        0       25 2023-04-21 20:29:02.908227 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/movie.metadata.json.j2
+-rw-r--r--   0        0        0     3527 2023-06-28 12:16:51.792847 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/movie.metadata.yaml.j2
+-rw-r--r--   0        0        0       24 2023-04-25 13:14:34.303691 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/show.collection.json.j2
+-rw-r--r--   0        0        0     3854 2023-06-13 12:50:38.818656 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/show.collection.yaml.j2
+-rw-r--r--   0        0        0       24 2023-04-21 20:28:17.955980 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/show.metadata.json.j2
+-rw-r--r--   0        0        0     3859 2023-06-28 12:17:20.073017 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/show.metadata.yaml.j2
+-rw-r--r--   0        0        0     1107 2023-05-11 19:57:56.303215 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/template.collection.yaml.j2
+-rw-r--r--   0        0        0        0 2023-04-03 13:48:27.869541 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/__init__.py
+-rw-r--r--   0        0        0     2592 2023-06-08 14:35:32.685306 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/cli_args.py
+-rw-r--r--   0        0        0     1956 2023-05-10 00:07:32.747680 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/file_utils.py
+-rw-r--r--   0        0        0     1778 2023-04-13 17:07:10.794833 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/logging_utils.py
+-rw-r--r--   0        0        0    37611 2023-06-15 15:59:43.139022 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/plex.py
+-rw-r--r--   0        0        0     2951 2023-06-12 16:23:04.350525 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/plex_cache.py
+-rw-r--r--   0        0        0     2150 2023-06-12 16:23:51.874774 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/plex_stats.py
+-rw-r--r--   0        0        0    17324 2023-06-15 19:42:50.434591 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/plex_utils.py
+-rwxr-xr-x   0        0        0    14285 2023-06-13 12:50:09.094516 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/pmm_utils.py
+-rw-r--r--   0        0        0    18201 2023-06-08 15:54:52.364845 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/settings_utils_v1.py
+-rw-r--r--   0        0        0    10122 2023-06-13 02:22:42.005047 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/template_filters.py
+-rw-r--r--   0        0        0     5057 2023-06-13 01:24:01.797107 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/template_manager.py
+-rwxr-xr-x   0        0        0     4443 2023-05-11 12:21:27.849258 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/time_span.py
+-rw-r--r--   0        0        0     2691 2023-04-10 21:13:51.972712 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/timer.py
+-rw-r--r--   0        0        0     2579 2023-04-26 13:50:19.226275 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/tmdb_utils.py
+-rw-r--r--   0        0        0     1361 2023-04-24 15:15:17.785439 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/trakt_utils.py
+-rw-r--r--   0        0        0     1514 2023-04-10 21:13:52.064713 pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/tvdb_utils.py
+-rw-r--r--   0        0        0     3845 1970-01-01 00:00:00.000000 pmm_cfg_gen-0.2.5/PKG-INFO
```

### Comparing `pmm_cfg_gen-0.2.4/LICENSE` & `pmm_cfg_gen-0.2.5/LICENSE`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/README.md` & `pmm_cfg_gen-0.2.5/README.md`

 * *Files 22% similar despite different names*

```diff
@@ -1,58 +1,68 @@
 # Plex-Meta-Manager-Config-Generator
 
 [![PyPI version](https://badge.fury.io/py/pmm-cfg-gen.svg)](https://badge.fury.io/py/pmm-cfg-gen)
 
-A python script to automatically generate Plex Meta Manager configuration files based on your plex libraries.
+A python application to automatically generate Plex Meta Manager configuration files based on your plex libraries.
 
 ## Install
 
 ```shell
 pip install pmm-cfg-gen
 ```
 
 ## Running from command line
 
 Usage:
 
 ```shell
-usage: pmm-cfg-gen [-h] [--plex.serverUrl PLEX.SERVERURL] [--plex.token PLEX.TOKEN] [--plex.lbraries [PLEX.LBRARIES ...]] [--output.path OUTPUT.PATH] [--logLevel {INFO,WARN,DEBUG,CRITICAL}]
+usage: pmm-cfg-gen [-h] [--plex.serverUrl PLEX.SERVERURL] [--plex.token PLEX.TOKEN] [--plex.lbraries [PLEX.LBRARIES ...]] [--output.path OUTPUT.PATH] [--output.overwrite OUTPUT.OVERWRITE]
+                   [--theMovieDatabase.apiKey THEMOVIEDATABASE.APIKEY] [--thePosterDatabase.enablePro] [--pmm.deltaOnly] [--logLevel {INFO,WARN,DEBUG,CRITICAL}]
 
 options:
   -h, --help            show this help message and exit
   --plex.serverUrl PLEX.SERVERURL
                         Plex Server fully qualifed URL
   --plex.token PLEX.TOKEN
                         Authentication Token (not claim token) for the plex server
   --plex.lbraries [PLEX.LBRARIES ...]
                         Comma delimited list of libraries to process
   --output.path OUTPUT.PATH
                         Root path to store generated files (default: ./data)
+  --output.overwrite OUTPUT.OVERWRITE
+                        Overwrite existing files (default: False)
+  --theMovieDatabase.apiKey THEMOVIEDATABASE.APIKEY
+                        The Movie Database API Key
+  --thePosterDatabase.enablePro
+                        Enable Pro features for The Poster Database (requires you to be able to login to the site)
+  --pmm.deltaOnly       Only generate files for items that do not already exist in current PMM configs
   --logLevel {INFO,WARN,DEBUG,CRITICAL}
                         Logging Level (default: INFO)
 
 ```
 
 ## Configuration File
 
 All of the configuration can be stored in a ```config.yaml``` file that uses the following format (with the exception of logLevel).
 
 config.yaml:
 
 ```yaml
 plex:
-  serverUrl: <plex server>
+  serverUrl: <plex server url>
   token: <plex token>
   libraries:
-    - <plex library name>
-    - <plex library name>
-    - <plex library name>
-    
+    - { name: "TV Shows", path: "tv", pmm_path: "/pmm_config/tv" }
+    - { name: "Movies", path: "movies" }
+
+plexMetaManager:
+  cacheExistingFiles: true
+
 theMovieDatabase:
-  apiKey: <api key for tmdb>
+  apiKey: <tmdb api key>
 
 output:
     path: <path to store generated output>
 ```
 
 Notes:
```

### Comparing `pmm_cfg_gen-0.2.4/pyproject.toml` & `pmm_cfg_gen-0.2.5/pyproject.toml`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "pmm-cfg-gen"
-version = "0.2.4"
+version = "0.2.5"
 description = "A script to help automatically generate Plex Meta Manager configuration files for your libraries"
 license = "GPL-3.0-or-later"
 authors = ["Shawn Anderson <sanderson@eye-catcher.com>"]
 readme = "README.md"
 homepage = "https://github.com/ravensorb/Plex-Meta-Manager-Config-Generator"
 repository = "https://github.com/ravensorb/Plex-Meta-Manager-Config-Generator"
 keywords = [ "pmm", "plex-meta-manager", "plex" ]
@@ -26,14 +26,15 @@
 importlib-resources = "^5.12.0"
 coloredlogs = "^15.0.1"
 readchar = "^4.0.5"
 jsonpickle = "^3.0.1"
 json-fix = "^0.5.2"
 themoviedb = "^0.3.3"
 dotty-dict = "*"
+dotty = "^0.1.0"
 
 [tool.poetry.group.dev.dependencies]
 pre-commit = "^3.2.1"
 scriv = {extras = ["toml"], version = "^1.2.1"}
 
 [tool.poetry.group.docs]
 optional = true
```

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/__init__.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/__init__.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/config_default.yaml` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/config_default.yaml`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/logging.yaml` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/logging.yaml`

 * *Files 4% similar despite different names*

```diff
@@ -18,15 +18,14 @@
     datefmt: "%Y-%m-%d %H:%M:%S"
 
   debug:
     format: "%(asctime)s [%(levelname)8s] %(name)s.%(funcName)s(%(lineno)s) : %(message)s"
     datefmt: "%Y-%m-%d %H:%M:%S"
   debug_details:
     format: "%(asctime)s|%(name)s|%(levelname)s|<PID %(process)d:%(processName)s>|%(name)s.%(funcName)s(%(lineno)s)|%(message)s"
-    #format: "[%(asctime)s] (%(filename)25s:%(lineno)4s: %(funcName)30s) - %(levelname)8s - %(message)"
     datefmt: "%Y-%m-%d %H:%M:%S"
 
 handlers:
   info_file_handler:
     class: logging.handlers.RotatingFileHandler
     level: INFO
     formatter: standard_detailed
```

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/movie.collection.yaml.j2` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/movie.collection.yaml.j2`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/movie.metadata.yaml.j2` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/movie.metadata.yaml.j2`

 * *Files 9% similar despite different names*

```diff
@@ -1,16 +1,19 @@
 metadata:
 {%- for item in items %}
     {%- set itemTitleFull = item.metadata | formatItemTitle %}
     {%- set itemTitleShort = item.metadata | formatItemTitle(False, False) %}
+    {#- title: {{ item.metadata.title }}
+    # itemTitleFull: {{ itemTitleFull }}
+    # itemTitleShort: {{ itemTitleShort }} #}
     "{{ itemTitleFull }}":
         year: {{ item.metadata.year }}
         title: "{{ item.metadata.title }}"
-        {%- if itemTitleFull != item.metadata.title %}
-        alt_title: "{{ itemTitleFull }}"{% endif %}
+        {%- if itemTitleShort != item.metadata.title  %}
+        alt_title: "{{ itemTitleShort }}"{% endif %}
         {%- if item.metadata.originalTitle and itemTitleFull != item.metadata.originalTitle %}
         orig_title: "{{ item.metadata.originalTitle }}"{% endif %}
         {%- if item.metadata.titleSort and item.metadata.titleSort != item.metadata.title %}
         sort_title: "{{ item.metadata.titleSort }}"{% endif %}
         {%- if item.metadata.editionTitle and item.metadata.editionTitle | length > 0 %}
         edition_filter: {{ item.metadata.editionTitle }}{% endif %}
         {% if not item.pmm.poster %}# {% endif %}url_poster: {{ item.pmm.poster | default(settings.thePosterDatabase.dbAssetUrl, True) }}
```

#### html2text {}

```diff
@@ -1,19 +1,20 @@
 metadata: {%- for item in items %} {%- set itemTitleFull = item.metadata |
 formatItemTitle %} {%- set itemTitleShort = item.metadata | formatItemTitle
-(False, False) %} "{{ itemTitleFull }}": year: {{ item.metadata.year }} title:
-"{{ item.metadata.title }}" {%- if itemTitleFull != item.metadata.title %}
-alt_title: "{{ itemTitleFull }}"{% endif %} {%- if item.metadata.originalTitle
-and itemTitleFull != item.metadata.originalTitle %} orig_title: "{
-{ item.metadata.originalTitle }}"{% endif %} {%- if item.metadata.titleSort and
-item.metadata.titleSort != item.metadata.title %} sort_title: "{
-{ item.metadata.titleSort }}"{% endif %} {%- if item.metadata.editionTitle and
-item.metadata.editionTitle | length > 0 %} edition_filter: {
-{ item.metadata.editionTitle }}{% endif %} {% if not item.pmm.poster %}# {%
-endif %}url_poster: {{ item.pmm.poster | default
+(False, False) %} {#- title: {{ item.metadata.title }} # itemTitleFull: {
+{ itemTitleFull }} # itemTitleShort: {{ itemTitleShort }} #} "{{ itemTitleFull
+}}": year: {{ item.metadata.year }} title: "{{ item.metadata.title }}" {%- if
+itemTitleShort != item.metadata.title %} alt_title: "{{ itemTitleShort }}"{%
+endif %} {%- if item.metadata.originalTitle and itemTitleFull !=
+item.metadata.originalTitle %} orig_title: "{{ item.metadata.originalTitle }}"
+{% endif %} {%- if item.metadata.titleSort and item.metadata.titleSort !=
+item.metadata.title %} sort_title: "{{ item.metadata.titleSort }}"{% endif %}
+{%- if item.metadata.editionTitle and item.metadata.editionTitle | length > 0
+%} edition_filter: {{ item.metadata.editionTitle }}{% endif %} {% if not
+item.pmm.poster %}# {% endif %}url_poster: {{ item.pmm.poster | default
 (settings.thePosterDatabase.dbAssetUrl, True) }} # IDs: {{ item.metadata.guids
 | map(attribute="id") | list | join(', ')}} # tpdb: {{ item.metadata |
 generateTpDbSearchUrl }} # tmdb: {% if item.metadata | getItemGuidByName
 ("tmdb") | default("") | length > 0 %}https://www.themoviedb.org/{% if
 item.metadata.type == "movie" %}movie{% elif item.metadata.type == "show" %}tv
 {% else %}{% endif %}/{{ item.metadata | getItemGuidByName("tmdb") }}{% endif
 %} # tvdb: {% if item.metadata | getItemGuidByName("tvdb") | default("") |
```

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/show.collection.yaml.j2` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/show.collection.yaml.j2`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/show.metadata.yaml.j2` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/show.metadata.yaml.j2`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,19 @@
 metadata: 
 {%- for item in items %}
     {%- set itemTitleFull = item.metadata | formatItemTitle %}
     {%- set itemTitleShort = item.metadata | formatItemTitle(False, False) %}
+    {#- title: {{ item.metadata.title }}
+    # itemTitleFull: {{ itemTitleFull }}
+    # itemTitleShort: {{ itemTitleShort }} #}    
     "{{ itemTitleFull }}":
         year: {{ item.metadata.year }}
         title: "{{ item.metadata.title }}"
-        {%- if itemTitleFull != item.metadata.title %}
-        alt_title: "{{ itemTitleFull }}"{% endif %}
+        {%- if itemTitleShort != item.metadata.title %}
+        alt_title: "{{ itemTitleShort }}"{% endif %}
         {%- if item.metadata.originalTitle and itemTitleFull != item.metadata.originalTitle %}
         orig_title: "{{ item.metadata.originalTitle }}"{% endif %}
         {%- if item.metadata.titleSort and item.metadata.titleSort != item.metadata.title %}
         sort_title: "{{ item.metadata.titleSort }}"{% endif %}
         {% if not item.pmm.poster %}# {% endif %}url_poster: {{ item.pmm.poster | default(settings.thePosterDatabase.dbAssetUrl, True) }}
         # IDs: {{ item.metadata.guids | map(attribute="id") | list | join(', ')}}
         # tpdb: {{ item.metadata | generateTpDbSearchUrl }}
@@ -19,15 +22,15 @@
         # imdb: {% if item.metadata | getItemGuidByName("imdb") | default("") | length > 0 %}https://www.imdb.com/title/{{ item.metadata | getItemGuidByName("imdb") }}{% endif %}
         {%- for season in item.seasons %}
             {%- set pmmSeasonPoster = item.pmm | getPMMSeason(season.seasonNumber, "poster") %}
         {%- if loop.first %}
         {% if not pmmSeasonPoster %}# {% endif %}seasons:{%- endif %}
             {% if not pmmSeasonPoster %}# {% endif %}{{ season.seasonNumber }}:
                 {% if not pmmSeasonPoster %}# {% endif %}url_poster: {{ pmmSeasonPoster | default(settings.thePosterDatabase.dbAssetUrl, True) }}
-        {%- endfor %}        
+        {%- endfor %}
 {% endfor %}
 
 {#- 
 ########################################################################################################################
 ########################################################################################################################
 
 external_templates:
```

#### html2text {}

```diff
@@ -1,35 +1,36 @@
 metadata: {%- for item in items %} {%- set itemTitleFull = item.metadata |
 formatItemTitle %} {%- set itemTitleShort = item.metadata | formatItemTitle
-(False, False) %} "{{ itemTitleFull }}": year: {{ item.metadata.year }} title:
-"{{ item.metadata.title }}" {%- if itemTitleFull != item.metadata.title %}
-alt_title: "{{ itemTitleFull }}"{% endif %} {%- if item.metadata.originalTitle
-and itemTitleFull != item.metadata.originalTitle %} orig_title: "{
-{ item.metadata.originalTitle }}"{% endif %} {%- if item.metadata.titleSort and
-item.metadata.titleSort != item.metadata.title %} sort_title: "{
-{ item.metadata.titleSort }}"{% endif %} {% if not item.pmm.poster %}# {% endif
-%}url_poster: {{ item.pmm.poster | default
-(settings.thePosterDatabase.dbAssetUrl, True) }} # IDs: {{ item.metadata.guids
-| map(attribute="id") | list | join(', ')}} # tpdb: {{ item.metadata |
-generateTpDbSearchUrl }} # tmdb: {% if item.metadata | getItemGuidByName
-("tmdb") | default("") | length > 0 %}https://www.themoviedb.org/{% if
-item.metadata.type == "movie" %}movie{% elif item.metadata.type == "show" %}tv
-{% else %}{% endif %}/{{ item.metadata | getItemGuidByName("tmdb") }}{% endif
-%} # tvdb: {% if item.metadata | getItemGuidByName("tvdb") | default("") |
-length > 0 %}https://thetvdb.com/search?menu%5Btype%5D={% if item.metadata.type
-== "movie"%}movie{% elif item.metadata.type == "show" %}series{% else %}{%
-endif %}&menu%5Byear%5D={{ item.metadata.year }}&query={{ item.metadata |
-getItemGuidByName("tvdb") }}{% endif %} # imdb: {% if item.metadata |
-getItemGuidByName("imdb") | default("") | length > 0 %}https://www.imdb.com/
-title/{{ item.metadata | getItemGuidByName("imdb") }}{% endif %} {%- for season
-in item.seasons %} {%- set pmmSeasonPoster = item.pmm | getPMMSeason
-(season.seasonNumber, "poster") %} {%- if loop.first %} {% if not
-pmmSeasonPoster %}# {% endif %}seasons:{%- endif %} {% if not pmmSeasonPoster
-%}# {% endif %}{{ season.seasonNumber }}: {% if not pmmSeasonPoster %}# {%
-endif %}url_poster: {{ pmmSeasonPoster | default
+(False, False) %} {#- title: {{ item.metadata.title }} # itemTitleFull: {
+{ itemTitleFull }} # itemTitleShort: {{ itemTitleShort }} #} "{{ itemTitleFull
+}}": year: {{ item.metadata.year }} title: "{{ item.metadata.title }}" {%- if
+itemTitleShort != item.metadata.title %} alt_title: "{{ itemTitleShort }}"{%
+endif %} {%- if item.metadata.originalTitle and itemTitleFull !=
+item.metadata.originalTitle %} orig_title: "{{ item.metadata.originalTitle }}"
+{% endif %} {%- if item.metadata.titleSort and item.metadata.titleSort !=
+item.metadata.title %} sort_title: "{{ item.metadata.titleSort }}"{% endif %}
+{% if not item.pmm.poster %}# {% endif %}url_poster: {{ item.pmm.poster |
+default(settings.thePosterDatabase.dbAssetUrl, True) }} # IDs: {
+{ item.metadata.guids | map(attribute="id") | list | join(', ')}} # tpdb: {
+{ item.metadata | generateTpDbSearchUrl }} # tmdb: {% if item.metadata |
+getItemGuidByName("tmdb") | default("") | length > 0 %}https://
+www.themoviedb.org/{% if item.metadata.type == "movie" %}movie{% elif
+item.metadata.type == "show" %}tv{% else %}{% endif %}/{{ item.metadata |
+getItemGuidByName("tmdb") }}{% endif %} # tvdb: {% if item.metadata |
+getItemGuidByName("tvdb") | default("") | length > 0 %}https://thetvdb.com/
+search?menu%5Btype%5D={% if item.metadata.type == "movie"%}movie{% elif
+item.metadata.type == "show" %}series{% else %}{% endif %}&menu%5Byear%5D={
+{ item.metadata.year }}&query={{ item.metadata | getItemGuidByName("tvdb") }}{%
+endif %} # imdb: {% if item.metadata | getItemGuidByName("imdb") | default("")
+| length > 0 %}https://www.imdb.com/title/{{ item.metadata | getItemGuidByName
+("imdb") }}{% endif %} {%- for season in item.seasons %} {%- set
+pmmSeasonPoster = item.pmm | getPMMSeason(season.seasonNumber, "poster") %} {%-
+if loop.first %} {% if not pmmSeasonPoster %}# {% endif %}seasons:{%- endif %}
+{% if not pmmSeasonPoster %}# {% endif %}{{ season.seasonNumber }}: {% if not
+pmmSeasonPoster %}# {% endif %}url_poster: {{ pmmSeasonPoster | default
 (settings.thePosterDatabase.dbAssetUrl, True) }} {%- endfor %} {% endfor %} {#-
 ########################################################################################################################
 ########################################################################################################################
 external_templates: pmm: templates templates: tplCommonBase: optional: - poster
 move_prefix: The sync_mode: sync url_poster: <> tplCommonItem: default:
 sort_prefix: "" sort_order: "" sort_separator: "" sort_title: <><><><><
 ><><><><> tplTVDBCollection: optional: - list - show - movie tvdb_show: <>
```

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/templates/template.collection.yaml.j2` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/templates/template.collection.yaml.j2`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/cli_args.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/cli_args.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/file_utils.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/file_utils.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/logging_utils.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/logging_utils.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/plex.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/plex.py`

 * *Files 1% similar despite different names*

```diff
@@ -730,30 +730,45 @@
         )
 
         self._logger.info(
             "  Items Skipped: {}".format(self.__stats.countsProgram.items.skipped)
         )
 
         for libraryName in self.__stats.timerLibraries.keys():
-            libraryTimer = self.__stats.timerLibraries[libraryName]
-            libaryCounts = self.__stats.countsLibraries[libraryName]
+            try:
+                libraryTimer = self.__stats.timerLibraries[libraryName]
+                libaryCounts = self.__stats.countsLibraries[libraryName]
+
+                self._logger.info("Statistics for Library: '{}'".format(libraryName))
+
+                self._logger.info(
+                    "  Processing Time: '{}'. Total Time: {}".format(
+                        libraryName, libraryTimer.elapsed_time_ts.to_str()
+                    )
+                )
 
-            self._logger.info("Statistics for Library: '{}'".format(libraryName))
+                self._logger.info(
+                    "  Collections Processed: {}".format(libaryCounts.collections.total)
+                )
 
-            self._logger.info(
-                "  Processing Time: '{}'. Total Time: {}".format(
-                    libraryName, libraryTimer.elapsed_time_ts.to_str()
+                self._logger.info(
+                    "  Collections Skipped: {}".format(libaryCounts.collections.skipped)
                 )
-            )
 
-            self._logger.info(
-                "  Collections Processed: {}".format(libaryCounts.collections.total)
-            )
-
-            self._logger.info(
-                "  Collections Skipped: {}".format(libaryCounts.collections.skipped)
-            )
+                self._logger.info("  Items Processed: {}".format(libaryCounts.items.total - libaryCounts.items.skipped))
+                self._logger.info("  Items Skipped: {}".format(libaryCounts.items.skipped))
+            except:
+                self._logger.exception("Failed displaying stats for library: '{}'".format(libraryName))
+                
+        self._logger.info("-" * 50)
 
-            self._logger.info("  Items Processed: {}".format(libaryCounts.items.total - libaryCounts.items.skipped))
-            self._logger.info("  Items Skipped: {}".format(libaryCounts.items.skipped))
+    # def _unlockAllLibraryFields(self):
 
-        self._logger.info("-" * 50)
+    #     #self._logger.debug("Possible Fields: {}".format(self.plexLibrary.listFields(self.plexLibrary.type)))
+
+    #     for field in self.plexLibrary.listFields(self.plexLibrary.type):
+    #         self._logger.info("Unlocking Field: '{}'".format(field))
+    #         try:
+    #             self.plexLibrary.unlockAllField(field)
+    #         except:
+    #             self._logger.exception("Failed unlocking field: '{}'".format(field))
+
```

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/plex_cache.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/plex_cache.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/plex_stats.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/plex_stats.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/plex_utils.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/plex_utils.py`

 * *Files 0% similar despite different names*

```diff
@@ -20,15 +20,15 @@
     def flatten(self, obj, data):
         """
          Flatten a Plex object into a dictionary. This is useful for generating JSON - RPC responses from server - side
          
          @param obj - The object to be flattened
          @param data - The dictionary to be flattened into. Should be an empty dictionary
          
-         @return The dictionary with flattened objects as key / value pairs in the form of a dictionary ( field_name : value
+         @return The dictionary with flattened objects as key / value pairs in the form of a dictionary ( field_name : value )
         """
         # Fix url raise
         # Set the _baseurl attribute of obj to the PlexServer.
         if isinstance(obj, PlexServer):
             setattr(obj, "_baseurl", globalSettingsMgr.settings.plex.serverUrl)
         # remove methods, private fields etc
         members = [
```

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/pmm_utils.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/pmm_utils.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/settings_utils_v1.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/settings_utils_v1.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/template_filters.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/template_filters.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/template_manager.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/template_manager.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/time_span.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/time_span.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/timer.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/timer.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/tmdb_utils.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/tmdb_utils.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/trakt_utils.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/trakt_utils.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/src/pmm_cfg_gen/utils/tvdb_utils.py` & `pmm_cfg_gen-0.2.5/src/pmm_cfg_gen/utils/tvdb_utils.py`

 * *Files identical despite different names*

### Comparing `pmm_cfg_gen-0.2.4/PKG-INFO` & `pmm_cfg_gen-0.2.5/PKG-INFO`

 * *Files 22% similar despite different names*

```diff
@@ -1,24 +1,25 @@
 Metadata-Version: 2.1
 Name: pmm-cfg-gen
-Version: 0.2.4
+Version: 0.2.5
 Summary: A script to help automatically generate Plex Meta Manager configuration files for your libraries
 Home-page: https://github.com/ravensorb/Plex-Meta-Manager-Config-Generator
 License: GPL-3.0-or-later
 Keywords: pmm,plex-meta-manager,plex
 Author: Shawn Anderson
 Author-email: sanderson@eye-catcher.com
 Requires-Python: >=3.10,<4.0
 Classifier: License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Topic :: Utilities
 Requires-Dist: coloredlogs (>=15.0.1,<16.0.0)
 Requires-Dist: confuse (>=2.0.1,<3.0.0)
+Requires-Dist: dotty (>=0.1.0,<0.2.0)
 Requires-Dist: dotty-dict
 Requires-Dist: expandvars (>=0.9.0,<0.10.0)
 Requires-Dist: importlib-resources (>=5.12.0,<6.0.0)
 Requires-Dist: jinja2
 Requires-Dist: json-fix (>=0.5.2,<0.6.0)
 Requires-Dist: jsonpickle (>=3.0.1,<4.0.0)
 Requires-Dist: plexapi
@@ -29,61 +30,71 @@
 Project-URL: Repository, https://github.com/ravensorb/Plex-Meta-Manager-Config-Generator
 Description-Content-Type: text/markdown
 
 # Plex-Meta-Manager-Config-Generator
 
 [![PyPI version](https://badge.fury.io/py/pmm-cfg-gen.svg)](https://badge.fury.io/py/pmm-cfg-gen)
 
-A python script to automatically generate Plex Meta Manager configuration files based on your plex libraries.
+A python application to automatically generate Plex Meta Manager configuration files based on your plex libraries.
 
 ## Install
 
 ```shell
 pip install pmm-cfg-gen
 ```
 
 ## Running from command line
 
 Usage:
 
 ```shell
-usage: pmm-cfg-gen [-h] [--plex.serverUrl PLEX.SERVERURL] [--plex.token PLEX.TOKEN] [--plex.lbraries [PLEX.LBRARIES ...]] [--output.path OUTPUT.PATH] [--logLevel {INFO,WARN,DEBUG,CRITICAL}]
+usage: pmm-cfg-gen [-h] [--plex.serverUrl PLEX.SERVERURL] [--plex.token PLEX.TOKEN] [--plex.lbraries [PLEX.LBRARIES ...]] [--output.path OUTPUT.PATH] [--output.overwrite OUTPUT.OVERWRITE]
+                   [--theMovieDatabase.apiKey THEMOVIEDATABASE.APIKEY] [--thePosterDatabase.enablePro] [--pmm.deltaOnly] [--logLevel {INFO,WARN,DEBUG,CRITICAL}]
 
 options:
   -h, --help            show this help message and exit
   --plex.serverUrl PLEX.SERVERURL
                         Plex Server fully qualifed URL
   --plex.token PLEX.TOKEN
                         Authentication Token (not claim token) for the plex server
   --plex.lbraries [PLEX.LBRARIES ...]
                         Comma delimited list of libraries to process
   --output.path OUTPUT.PATH
                         Root path to store generated files (default: ./data)
+  --output.overwrite OUTPUT.OVERWRITE
+                        Overwrite existing files (default: False)
+  --theMovieDatabase.apiKey THEMOVIEDATABASE.APIKEY
+                        The Movie Database API Key
+  --thePosterDatabase.enablePro
+                        Enable Pro features for The Poster Database (requires you to be able to login to the site)
+  --pmm.deltaOnly       Only generate files for items that do not already exist in current PMM configs
   --logLevel {INFO,WARN,DEBUG,CRITICAL}
                         Logging Level (default: INFO)
 
 ```
 
 ## Configuration File
 
 All of the configuration can be stored in a ```config.yaml``` file that uses the following format (with the exception of logLevel).
 
 config.yaml:
 
 ```yaml
 plex:
-  serverUrl: <plex server>
+  serverUrl: <plex server url>
   token: <plex token>
   libraries:
-    - <plex library name>
-    - <plex library name>
-    - <plex library name>
-    
+    - { name: "TV Shows", path: "tv", pmm_path: "/pmm_config/tv" }
+    - { name: "Movies", path: "movies" }
+
+plexMetaManager:
+  cacheExistingFiles: true
+
 theMovieDatabase:
-  apiKey: <api key for tmdb>
+  apiKey: <tmdb api key>
 
 output:
     path: <path to store generated output>
 ```
 
 Notes:
```

