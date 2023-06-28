# Comparing `tmp/capsula-0.0.2.tar.gz` & `tmp/capsula-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "capsula-0.0.2.tar", max compression
+gzip compressed data, was "capsula-0.0.3.tar", max compression
```

## Comparing `capsula-0.0.2.tar` & `capsula-0.0.3.tar`

### file list

```diff
@@ -1,10 +1,10 @@
--rw-r--r--   0        0        0     1074 2023-06-23 14:46:03.560678 capsula-0.0.2/LICENSE
--rw-r--r--   0        0        0       81 2023-06-25 03:00:51.991804 capsula-0.0.2/README.md
--rw-r--r--   0        0        0       48 2023-06-25 03:19:05.921800 capsula-0.0.2/capsula/__init__.py
--rw-r--r--   0        0        0     1654 2023-06-25 03:00:51.991804 capsula-0.0.2/capsula/__main__.py
--rw-r--r--   0        0        0       22 2023-06-25 03:21:49.471792 capsula-0.0.2/capsula/_version.py
--rw-r--r--   0        0        0     2829 2023-06-25 03:00:51.991804 capsula-0.0.2/capsula/capture.py
--rw-r--r--   0        0        0     4487 2023-06-25 03:00:51.991804 capsula-0.0.2/capsula/context.py
--rw-r--r--   0        0        0      849 2023-06-25 03:00:51.991804 capsula-0.0.2/capsula/hash.py
--rw-r--r--   0        0        0     3436 2023-06-25 03:21:49.471792 capsula-0.0.2/pyproject.toml
--rw-r--r--   0        0        0      645 1970-01-01 00:00:00.000000 capsula-0.0.2/PKG-INFO
+-rw-r--r--   0        0        0     1074 2023-06-23 14:46:03.560678 capsula-0.0.3/LICENSE
+-rw-r--r--   0        0        0     4107 2023-06-28 12:33:50.283621 capsula-0.0.3/README.md
+-rw-r--r--   0        0        0       48 2023-06-28 11:47:35.793639 capsula-0.0.3/capsula/__init__.py
+-rw-r--r--   0        0        0     1654 2023-06-28 11:47:35.793639 capsula-0.0.3/capsula/__main__.py
+-rw-r--r--   0        0        0       22 2023-06-28 12:38:06.943652 capsula-0.0.3/capsula/_version.py
+-rw-r--r--   0        0        0     2909 2023-06-28 12:06:12.283638 capsula-0.0.3/capsula/capture.py
+-rw-r--r--   0        0        0     4487 2023-06-28 12:06:12.283638 capsula-0.0.3/capsula/context.py
+-rw-r--r--   0        0        0      849 2023-06-28 11:47:35.803639 capsula-0.0.3/capsula/hash.py
+-rw-r--r--   0        0        0     3436 2023-06-28 12:38:06.943652 capsula-0.0.3/pyproject.toml
+-rw-r--r--   0        0        0     4671 1970-01-01 00:00:00.000000 capsula-0.0.3/PKG-INFO
```

### Comparing `capsula-0.0.2/LICENSE` & `capsula-0.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `capsula-0.0.2/capsula/__main__.py` & `capsula-0.0.3/capsula/__main__.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.2/capsula/capture.py` & `capsula-0.0.3/capsula/capture.py`

 * *Files 4% similar despite different names*

```diff
@@ -19,14 +19,18 @@
 
 
 class CaptureFileConfig(BaseModel):
     hash_algorithm: Literal["md5", "sha1", "sha256", "sha3"] = "sha256"
     copy_: bool = Field(default=True, alias="copy")
 
 
+class GitConfig(BaseModel):
+    repositories: dict[str, Path] = Field(default_factory=dict)
+
+
 class CaptureConfig(BaseModel):
     """Configuration for the capture command."""
 
     vault_directory: Path
     subdirectory_template: str
 
     # Whether to include the Capsula version in the output file.
@@ -36,15 +40,15 @@
 
     pre_capture_commands: list[str] = Field(default_factory=list)
 
     environment_variables: list[str] = Field(default_factory=list)
 
     files: dict[Path, CaptureFileConfig] = Field(default_factory=list)
 
-    git_repositories: dict[str, Path] = Field(default_factory=dict)
+    git: GitConfig = Field(default_factory=GitConfig)
 
     class Config:  # noqa: D106
         alias_generator = to_hyphen_case
         populate_by_name = False
         extra = "forbid"
 
     _subdirectory: Path | None = None
```

### Comparing `capsula-0.0.2/capsula/context.py` & `capsula-0.0.3/capsula/context.py`

 * *Files 0% similar despite different names*

```diff
@@ -99,15 +99,15 @@
     sha: str
     branch: str
     remotes: list[GitRemote]
 
     @classmethod
     def capture(cls, config: CaptureConfig) -> dict[Path, Self]:
         git_infos = {}
-        for name, path in config.git_repositories.items():
+        for name, path in config.git.repositories.items():
             repo = Repo(path)
             git_infos[name] = cls(
                 path=path,
                 sha=repo.head.object.hexsha,
                 remotes=[GitRemote(name=remote.name, url=remote.url) for remote in repo.remotes],
                 branch=repo.active_branch.name,
             )
```

### Comparing `capsula-0.0.2/capsula/hash.py` & `capsula-0.0.3/capsula/hash.py`

 * *Files identical despite different names*

### Comparing `capsula-0.0.2/pyproject.toml` & `capsula-0.0.3/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "capsula"
-version = "0.0.2"
+version = "0.0.3"
 description = "A Python package to capture and reproduce command execution contexts"
 authors = ["Shunichiro Nomura <nomura@space.t.u-tokyo.ac.jp>"]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "capsula"}]
 
 [tool.poetry.dependencies]
@@ -85,15 +85,15 @@
 # ]
 
 [tool.tbump]
 # Uncomment this if your project is hosted on GitHub:
 github_url = "https://github.com/shunichironomura/capsula/"
 
 [tool.tbump.version]
-current = "0.0.2"
+current = "0.0.3"
 
 # Example of a semver regexp.
 # Make sure this matches current_version before
 # using tbump
 regex = '''
   (?P<major>\d+)
   \.
```

