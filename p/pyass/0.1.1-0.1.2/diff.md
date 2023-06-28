# Comparing `tmp/pyass-0.1.1.tar.gz` & `tmp/pyass-0.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyass-0.1.1.tar", max compression
+gzip compressed data, was "pyass-0.1.2.tar", max compression
```

## Comparing `pyass-0.1.1.tar` & `pyass-0.1.2.tar`

### file list

```diff
@@ -1,16 +1,16 @@
--rw-r--r--   0        0        0     1067 2023-04-25 07:33:42.674438 pyass-0.1.1/LICENSE
--rw-r--r--   0        0        0       89 2023-04-25 07:33:42.674438 pyass-0.1.1/README.md
--rw-r--r--   0        0        0     1349 2023-04-25 07:33:42.674438 pyass-0.1.1/pyass/__init__.py
--rw-r--r--   0        0        0      847 2023-04-25 07:33:42.674438 pyass-0.1.1/pyass/color.py
--rw-r--r--   0        0        0      112 2023-04-25 07:33:42.674438 pyass-0.1.1/pyass/drawing.py
--rw-r--r--   0        0        0      896 2023-04-25 07:33:42.674438 pyass-0.1.1/pyass/enum.py
--rw-r--r--   0        0        0     4780 2023-04-25 07:33:42.674438 pyass-0.1.1/pyass/event.py
--rw-r--r--   0        0        0      124 2023-04-25 07:33:42.674438 pyass-0.1.1/pyass/float.py
--rw-r--r--   0        0        0      419 2023-04-25 07:33:42.674438 pyass-0.1.1/pyass/position.py
--rw-r--r--   0        0        0     3749 2023-04-25 07:33:42.674438 pyass-0.1.1/pyass/script.py
--rw-r--r--   0        0        0     5579 2023-04-25 07:33:42.674438 pyass-0.1.1/pyass/section.py
--rw-r--r--   0        0        0     4239 2023-04-25 07:33:42.674438 pyass-0.1.1/pyass/style.py
--rw-r--r--   0        0        0    27281 2023-04-25 07:33:42.674438 pyass-0.1.1/pyass/tag.py
--rw-r--r--   0        0        0     3592 2023-04-25 07:33:42.674438 pyass-0.1.1/pyass/timedelta.py
--rw-r--r--   0        0        0      673 2023-04-25 07:33:42.674438 pyass-0.1.1/pyproject.toml
--rw-r--r--   0        0        0      674 1970-01-01 00:00:00.000000 pyass-0.1.1/PKG-INFO
+-rw-r--r--   0        0        0     1067 2023-06-28 05:53:17.963169 pyass-0.1.2/LICENSE
+-rw-r--r--   0        0        0     3687 2023-06-28 05:53:17.963169 pyass-0.1.2/README.md
+-rw-r--r--   0        0        0     1349 2023-06-28 05:53:17.963169 pyass-0.1.2/pyass/__init__.py
+-rw-r--r--   0        0        0      847 2023-06-28 05:53:17.963169 pyass-0.1.2/pyass/color.py
+-rw-r--r--   0        0        0      112 2023-06-28 05:53:17.963169 pyass-0.1.2/pyass/drawing.py
+-rw-r--r--   0        0        0      896 2023-06-28 05:53:17.963169 pyass-0.1.2/pyass/enum.py
+-rw-r--r--   0        0        0     4780 2023-06-28 05:53:17.963169 pyass-0.1.2/pyass/event.py
+-rw-r--r--   0        0        0      124 2023-06-28 05:53:17.963169 pyass-0.1.2/pyass/float.py
+-rw-r--r--   0        0        0      419 2023-06-28 05:53:17.963169 pyass-0.1.2/pyass/position.py
+-rw-r--r--   0        0        0     3749 2023-06-28 05:53:17.963169 pyass-0.1.2/pyass/script.py
+-rw-r--r--   0        0        0     5579 2023-06-28 05:53:17.963169 pyass-0.1.2/pyass/section.py
+-rw-r--r--   0        0        0     4239 2023-06-28 05:53:17.963169 pyass-0.1.2/pyass/style.py
+-rw-r--r--   0        0        0    27281 2023-06-28 05:53:17.963169 pyass-0.1.2/pyass/tag.py
+-rw-r--r--   0        0        0     3809 2023-06-28 05:53:17.963169 pyass-0.1.2/pyass/timedelta.py
+-rw-r--r--   0        0        0      673 2023-06-28 05:53:17.963169 pyass-0.1.2/pyproject.toml
+-rw-r--r--   0        0        0     4272 1970-01-01 00:00:00.000000 pyass-0.1.2/PKG-INFO
```

### Comparing `pyass-0.1.1/LICENSE` & `pyass-0.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `pyass-0.1.1/pyass/__init__.py` & `pyass-0.1.2/pyass/__init__.py`

 * *Files identical despite different names*

### Comparing `pyass-0.1.1/pyass/color.py` & `pyass-0.1.2/pyass/color.py`

 * *Files identical despite different names*

### Comparing `pyass-0.1.1/pyass/enum.py` & `pyass-0.1.2/pyass/enum.py`

 * *Files identical despite different names*

### Comparing `pyass-0.1.1/pyass/event.py` & `pyass-0.1.2/pyass/event.py`

 * *Files identical despite different names*

### Comparing `pyass-0.1.1/pyass/script.py` & `pyass-0.1.2/pyass/script.py`

 * *Files identical despite different names*

### Comparing `pyass-0.1.1/pyass/section.py` & `pyass-0.1.2/pyass/section.py`

 * *Files identical despite different names*

### Comparing `pyass-0.1.1/pyass/style.py` & `pyass-0.1.2/pyass/style.py`

 * *Files identical despite different names*

### Comparing `pyass-0.1.1/pyass/tag.py` & `pyass-0.1.2/pyass/tag.py`

 * *Files identical despite different names*

### Comparing `pyass-0.1.1/pyass/timedelta.py` & `pyass-0.1.2/pyass/timedelta.py`

 * *Files 4% similar despite different names*

```diff
@@ -30,28 +30,37 @@
             minutes,
             hours,
             weeks,
         )
 
     @staticmethod
     def parse(s: str):
+        is_neg = s.startswith("-")
+        s = s.removeprefix("-")
+
         s_str, _, cs_str = s.partition(".")
         hrs, mins, secs = map(int, s_str.split(":"))
         cs = int(cs_str)
 
-        return timedelta(hours=hrs, minutes=mins, seconds=secs, centiseconds=cs)
+        td = timedelta(hours=hrs, minutes=mins, seconds=secs, centiseconds=cs)
+        return -td if is_neg else td
 
     def __str__(self) -> str:
-        hours, remainder = self.total_seconds() // 3600, self.total_seconds() % 3600
+        is_neg = self.total_seconds() < 0
+        td = -self if is_neg else self
+
+        hours, remainder = td.total_seconds() // 3600, td.total_seconds() % 3600
         minutes, seconds = remainder // 60, remainder % 60
 
-        return "{:01}:{:02}:{:02}.{:02}".format(
-            int(hours), int(minutes), int(seconds), int(self.microseconds // 10000)
+        s = "{:01}:{:02}:{:02}.{:02}".format(
+            int(hours), int(minutes), int(seconds), int(td.microseconds // 10000)
         )
 
+        return "-" + s if is_neg else s
+
     def __add__(self, other):
         result = super(timedelta, self).__add__(other)
         return timedelta(
             days=result.days, seconds=result.seconds, microseconds=result.microseconds
         )
 
     def __sub__(self, other):
```

### Comparing `pyass-0.1.1/pyproject.toml` & `pyass-0.1.2/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 ]
 
 [tool.isort]
 profile = "black"
 
 [tool.poetry]
 name = "pyass"
-version = "0.1.1"
+version = "0.1.2"
 description = "A library to read, manipulate, and write Advanced SubStation Alpha (.ass) files"
 authors = ["xIceArcher <xicearcher@gmail.com>"]
 license = "MIT"
 readme = "README.md"
 repository = "https://github.com/xIceArcher/pyass"
 
 [tool.poetry.dependencies]
```

