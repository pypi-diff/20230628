# Comparing `tmp/cli3-1.1.1.tar.gz` & `tmp/cli3-1.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cli3-1.1.1.tar", last modified: Tue May  9 00:54:21 2023, max compression
+gzip compressed data, was "cli3-1.1.2.tar", last modified: Wed Jun 28 01:53:24 2023, max compression
```

## Comparing `cli3-1.1.1.tar` & `cli3-1.1.2.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-05-09 00:54:21.476932 cli3-1.1.1/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1064 2020-10-21 03:10:04.000000 cli3-1.1.1/LICENSE
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1537 2023-05-09 00:54:21.476932 cli3-1.1.1/PKG-INFO
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1038 2022-11-16 03:06:40.000000 cli3-1.1.1/README.md
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-05-09 00:54:21.472932 cli3-1.1.1/cli/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1343 2023-05-03 02:43:51.000000 cli3-1.1.1/cli/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)    13785 2023-05-03 02:43:51.000000 cli3-1.1.1/cli/abc.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     6825 2023-05-03 02:43:51.000000 cli3-1.1.1/cli/app.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     4660 2023-05-09 00:41:40.000000 cli3-1.1.1/cli/argument.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     7041 2023-05-09 00:53:27.000000 cli3-1.1.1/cli/command.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     4501 2023-05-03 02:43:51.000000 cli3-1.1.1/cli/flag.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     4997 2023-05-03 02:43:51.000000 cli3-1.1.1/cli/help.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     7434 2023-05-03 02:43:51.000000 cli3-1.1.1/cli/parser.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-05-09 00:54:21.472932 cli3-1.1.1/cli/tests/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      111 2023-05-03 02:43:51.000000 cli3-1.1.1/cli/tests/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     5816 2023-05-03 02:43:51.000000 cli3-1.1.1/cli/tests/app.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-05-09 00:54:21.476932 cli3-1.1.1/cli/tests/content/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      145 2023-05-03 02:43:51.000000 cli3-1.1.1/cli/tests/content/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2599 2023-05-03 02:43:51.000000 cli3-1.1.1/cli/tests/content/v1.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2002 2023-05-03 02:43:51.000000 cli3-1.1.1/cli/tests/content/v2.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)    14056 2023-05-09 00:39:09.000000 cli3-1.1.1/cli/wraps.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-05-09 00:54:21.476932 cli3-1.1.1/cli3.egg-info/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1537 2023-05-09 00:54:21.000000 cli3-1.1.1/cli3.egg-info/PKG-INFO
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      402 2023-05-09 00:54:21.000000 cli3-1.1.1/cli3.egg-info/SOURCES.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)        1 2023-05-09 00:54:21.000000 cli3-1.1.1/cli3.egg-info/dependency_links.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)        7 2023-05-09 00:54:21.000000 cli3-1.1.1/cli3.egg-info/requires.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)        4 2023-05-09 00:54:21.000000 cli3-1.1.1/cli3.egg-info/top_level.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)       38 2023-05-09 00:54:21.476932 cli3-1.1.1/setup.cfg
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      762 2023-05-09 00:53:59.000000 cli3-1.1.1/setup.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:53:24.901958 cli3-1.1.2/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1064 2020-10-21 03:10:04.000000 cli3-1.1.2/LICENSE
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1537 2023-06-28 01:53:24.901958 cli3-1.1.2/PKG-INFO
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1038 2022-11-16 03:06:40.000000 cli3-1.1.2/README.md
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:53:24.901958 cli3-1.1.2/cli/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1343 2023-05-03 02:43:51.000000 cli3-1.1.2/cli/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)    13821 2023-06-26 05:51:15.000000 cli3-1.1.2/cli/abc.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     6825 2023-06-26 05:50:21.000000 cli3-1.1.2/cli/app.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     4660 2023-05-09 00:41:40.000000 cli3-1.1.2/cli/argument.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     7041 2023-05-09 00:53:27.000000 cli3-1.1.2/cli/command.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     4504 2023-06-26 05:52:32.000000 cli3-1.1.2/cli/flag.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     4997 2023-05-03 02:43:51.000000 cli3-1.1.2/cli/help.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     7434 2023-05-03 02:43:51.000000 cli3-1.1.2/cli/parser.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:53:24.901958 cli3-1.1.2/cli/tests/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      111 2023-05-03 02:43:51.000000 cli3-1.1.2/cli/tests/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     5816 2023-05-03 02:43:51.000000 cli3-1.1.2/cli/tests/app.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:53:24.901958 cli3-1.1.2/cli/tests/content/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      145 2023-05-03 02:43:51.000000 cli3-1.1.2/cli/tests/content/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2599 2023-05-03 02:43:51.000000 cli3-1.1.2/cli/tests/content/v1.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2002 2023-05-03 02:43:51.000000 cli3-1.1.2/cli/tests/content/v2.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)    14056 2023-05-09 00:39:09.000000 cli3-1.1.2/cli/wraps.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:53:24.901958 cli3-1.1.2/cli3.egg-info/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1537 2023-06-28 01:53:24.000000 cli3-1.1.2/cli3.egg-info/PKG-INFO
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      402 2023-06-28 01:53:24.000000 cli3-1.1.2/cli3.egg-info/SOURCES.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)        1 2023-06-28 01:53:24.000000 cli3-1.1.2/cli3.egg-info/dependency_links.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)       17 2023-06-28 01:53:24.000000 cli3-1.1.2/cli3.egg-info/requires.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)        4 2023-06-28 01:53:24.000000 cli3-1.1.2/cli3.egg-info/top_level.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)       38 2023-06-28 01:53:24.901958 cli3-1.1.2/setup.cfg
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      775 2023-06-26 05:52:58.000000 cli3-1.1.2/setup.py
```

### Comparing `cli3-1.1.1/LICENSE` & `cli3-1.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `cli3-1.1.1/PKG-INFO` & `cli3-1.1.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cli3
-Version: 1.1.1
+Version: 1.1.2
 Summary: A highly configurable, dynamic, fast, and easy solution to managing a command-line application.
 Home-page: https://github.com/imgurbot12/cli
 Author: Andrew Scott
 Author-email: imgurbot12@gmail.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `cli3-1.1.1/README.md` & `cli3-1.1.2/README.md`

 * *Files identical despite different names*

### Comparing `cli3-1.1.1/cli/__init__.py` & `cli3-1.1.2/cli/__init__.py`

 * *Files identical despite different names*

### Comparing `cli3-1.1.1/cli/abc.py` & `cli3-1.1.2/cli/abc.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,17 +1,19 @@
 """
 Abstract/BaseClass Instances/Protocols
 """
 from abc import abstractmethod
 from collections import UserList
-from dataclasses import dataclass, field
 from functools import cached_property
 from typing import *
+from typing import TextIO
 from typing_extensions import Self
 
+from pyderive import dataclass, field
+
 #** Variables **#
 __all__ = [
     'T',
     'NO_ACTION',
     'Result',
     'SyncAction',
     'AsyncAction',
@@ -182,15 +184,15 @@
 
     def swap(self, fromidx: int, toidx: int):
         """swap from and to index in list"""
         if fromidx >= len(self) or toidx >= len(self):
             raise ValueError("index out of range")
         self[fromidx], self[toidx] = self[toidx], self[fromidx]
 
-@dataclass
+@dataclass(slots=True)
 class Context:
     """Context-Object to Pass Information into/from Various Command Actions"""
     app:          'AbsApplication'    = field(repr=False)
     command:      'AbsCommand'        = field(repr=False) 
     ctx_parent:   Optional['Context'] = field(default=None, repr=False)
     global_flags: FlagDict            = field(default_factory=dict)
     local_flags:  FlagDict            = field(default_factory=dict)
```

### Comparing `cli3-1.1.1/cli/app.py` & `cli3-1.1.2/cli/app.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,15 +38,15 @@
     except:
         loop = asyncio.new_event_loop()
         asyncio.set_event_loop(loop)
     return loop
 
 #** Classes **#
 
-class App(AbsApplication, Command):
+class App(Command, AbsApplication):
     """
     application determines handling of arguments and stores metadata
 
     :param name:              name of application
     :param usage:             specified usage description
     :param version:           symantic version number
     :param argsusage:         argument usage description
```

### Comparing `cli3-1.1.1/cli/argument.py` & `cli3-1.1.2/cli/argument.py`

 * *Files identical despite different names*

### Comparing `cli3-1.1.1/cli/command.py` & `cli3-1.1.2/cli/command.py`

 * *Files identical despite different names*

### Comparing `cli3-1.1.1/cli/flag.py` & `cli3-1.1.2/cli/flag.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,15 +1,16 @@
 """
 all possible flags allowed to be passed into application and parsed from args
 """
 from contextlib import contextmanager
 from datetime import timedelta
-from dataclasses import dataclass, field
 from typing import Optional, Any, Union, Type, List, ClassVar
 
+from pyderive import dataclass, field
+
 from .abc import *
 from .argument import *
 
 #** Variables **#
 __all__ = [
     'Flag',
     'BoolFlag',
@@ -33,15 +34,15 @@
     except Exception:
         pass
 
 #** Classes **#
 
 #TODO: move flag validation to app setup and execution
 
-@dataclass
+@dataclass(slots=True)
 class Flag(AbsFlag[T]):
     """
     baseclass Flag declaration
     
     :param name:      name of flag
     :param usage:     usage description
     :param default:   default value
@@ -63,72 +64,67 @@
         self.parser: TypeFunc = self.parser or self.type
 
     def parse(self, value: str) -> T:
         """convert cli-value into the correct-type"""
         with capture_errors():
             return self.parser(value)
 
-@dataclass
+@dataclass(slots=True)
 class BoolFlag(Flag[bool]):
     """implementation for supporting boolean flags"""
     type:      ClassVar[Type] = bool
     default:   bool           = False
     has_value: bool           = False
 
-@dataclass
 class IntFlag(Flag[int]):
     """implementation for supporting integer flags"""
     type: ClassVar[Type] = int
 
-@dataclass
 class StringFlag(Flag[str]):
     """implementation for supporting string flags"""
     type: ClassVar[Type] = str
 
-@dataclass
 class FloatFlag(Flag[float]):
     """implementation for supporting flag flags"""
     type: ClassVar[Type] = float
 
-@dataclass
+@dataclass(slots=True)
 class DecimalFlag(Flag[float]):
     """
     implementation for supporting controlable decimal flags
 
     :param decimal: number of allowed decimal places
     """
     type:    ClassVar[Type] = float
     decimal: int            = 2
 
     def parse(self, value: str):
         """handle float founding based on decimal setting"""
         with capture_errors():
             return parse_decimal(value, self.decimal)
 
-@dataclass
 class ListFlag(Flag[List[str]]):
     """implementatin for supporting list flags"""
     type: ClassVar[Type] = list
 
     def parse(self, value: str):
         """convert value into list object"""
         with capture_errors():
             return [c.strip() for c in value.split(',')]
 
-@dataclass
 class DurationFlag(Flag[timedelta]):
     """implementation for supporting time-duration flags"""
     type: ClassVar[Type] = timedelta
 
     def parse(self, value: str):
         """convert string-value into timedelta"""
         with capture_errors():
             return parse_duration(value)
 
-@dataclass
+@dataclass(slots=True)
 class EnumFlag(Flag[Any]):
     """
     implementation for supporting enum-value flags
 
     :param enum: enumeration allowed of allowed values in flag
     """
     type: ClassVar[Type] = Any
@@ -137,15 +133,15 @@
     def parse(self, value: str) -> Optional[Any]:
         """ensure the specified value is included in the enum"""
         with capture_errors():
             if value not in self.enum:
                 return
             return self.enum[value] if isinstance(self.enum, dict) else value
 
-@dataclass
+@dataclass(slots=True)
 class FilePathFlag(Flag[str]):
     """
     implementation for supporting existing/new file-paths
 
     :param exists: ensure file exists if true
     """
     type:   ClassVar[Type] = str
```

### Comparing `cli3-1.1.1/cli/help.py` & `cli3-1.1.2/cli/help.py`

 * *Files identical despite different names*

### Comparing `cli3-1.1.1/cli/parser.py` & `cli3-1.1.2/cli/parser.py`

 * *Files identical despite different names*

### Comparing `cli3-1.1.1/cli/tests/app.py` & `cli3-1.1.2/cli/tests/app.py`

 * *Files identical despite different names*

### Comparing `cli3-1.1.1/cli/tests/content/v1.py` & `cli3-1.1.2/cli/tests/content/v1.py`

 * *Files identical despite different names*

### Comparing `cli3-1.1.1/cli/tests/content/v2.py` & `cli3-1.1.2/cli/tests/content/v2.py`

 * *Files identical despite different names*

### Comparing `cli3-1.1.1/cli/wraps.py` & `cli3-1.1.2/cli/wraps.py`

 * *Files identical despite different names*

### Comparing `cli3-1.1.1/cli3.egg-info/PKG-INFO` & `cli3-1.1.2/cli3.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cli3
-Version: 1.1.1
+Version: 1.1.2
 Summary: A highly configurable, dynamic, fast, and easy solution to managing a command-line application.
 Home-page: https://github.com/imgurbot12/cli
 Author: Andrew Scott
 Author-email: imgurbot12@gmail.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

