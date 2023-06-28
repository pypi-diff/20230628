# Comparing `tmp/seqLister-1.0.0.tar.gz` & `tmp/seqLister-1.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "/eno/media/src/seqLister/dist/tmpcpy89nrt/seqLister-1.0.0.tar", last modified: Mon Jul 12 03:50:24 2021, max compression
+gzip compressed data, was "/eno/media/src/seqLister/dist/tmpsddmqz17/seqLister-1.1.0.tar", last modified: Wed Jun 28 01:35:54 2023, max compression
```

## Comparing `seqLister-1.0.0.tar` & `seqLister-1.1.0.tar`

### file list

```diff
@@ -1,14 +1,15 @@
-drwxrwxrwx   0 jrowell   (1026) users      (100)        0 2021-07-12 03:50:11.000000 seqLister-1.0.0/
-drwxrwxrwx   0 jrowell   (1026) users      (100)        0 2021-07-12 03:50:11.000000 seqLister-1.0.0/src/
-drwxrwxrwx   0 jrowell   (1026) users      (100)        0 2021-07-12 03:50:11.000000 seqLister-1.0.0/src/seqLister/
--rw-rw-rw-   0 jrowell   (1026) users      (100)    13966 2021-06-23 03:35:13.000000 seqLister-1.0.0/src/seqLister/__init__.py
-drwxrwxrwx   0 jrowell   (1026) users      (100)        0 2021-07-12 03:50:11.000000 seqLister-1.0.0/src/seqLister.egg-info/
--rwxrwxrwx   0 jrowell   (1026) users      (100)        1 2021-07-12 03:50:11.000000 seqLister-1.0.0/src/seqLister.egg-info/dependency_links.txt
--rwxrwxrwx   0 jrowell   (1026) users      (100)      216 2021-07-12 03:50:11.000000 seqLister-1.0.0/src/seqLister.egg-info/SOURCES.txt
--rwxrwxrwx   0 jrowell   (1026) users      (100)     4281 2021-07-12 03:50:11.000000 seqLister-1.0.0/src/seqLister.egg-info/PKG-INFO
--rwxrwxrwx   0 jrowell   (1026) users      (100)       10 2021-07-12 03:50:11.000000 seqLister-1.0.0/src/seqLister.egg-info/top_level.txt
--rwxrwxrwx   0 jrowell   (1026) users      (100)     4281 2021-07-12 03:50:11.000000 seqLister-1.0.0/PKG-INFO
--rwxrwxrwx   0 jrowell   (1026) users      (100)      104 2021-06-23 03:32:49.000000 seqLister-1.0.0/pyproject.toml
--rw-rw-rw-   0 jrowell   (1026) users      (100)     1620 2021-06-23 02:53:59.000000 seqLister-1.0.0/LICENSE
--rwxrwxrwx   0 jrowell   (1026) users      (100)      742 2021-07-12 03:50:11.000000 seqLister-1.0.0/setup.cfg
--rw-rw-rw-   0 jrowell   (1026) users      (100)     3627 2021-06-27 19:46:01.000000 seqLister-1.0.0/README.md
+drwxrwxrwx   0 jrowell   (1026) users      (100)        0 2023-06-28 01:35:54.000000 seqLister-1.1.0/
+drwxrwxrwx   0 jrowell   (1026) users      (100)        0 2023-06-28 01:35:54.000000 seqLister-1.1.0/src/
+drwxrwxrwx   0 jrowell   (1026) users      (100)        0 2023-06-28 01:35:54.000000 seqLister-1.1.0/src/seqLister/
+-rw-rw-rw-   0 jrowell   (1026) users      (100)    14566 2023-06-28 01:15:47.000000 seqLister-1.1.0/src/seqLister/__init__.py
+drwxrwxrwx   0 jrowell   (1026) users      (100)        0 2023-06-28 01:35:54.000000 seqLister-1.1.0/src/seqLister.egg-info/
+-rwxrwxrwx   0 jrowell   (1026) users      (100)        1 2023-06-28 01:35:54.000000 seqLister-1.1.0/src/seqLister.egg-info/dependency_links.txt
+-rwxrwxrwx   0 jrowell   (1026) users      (100)      225 2023-06-28 01:35:54.000000 seqLister-1.1.0/src/seqLister.egg-info/SOURCES.txt
+-rwxrwxrwx   0 jrowell   (1026) users      (100)     4674 2023-06-28 01:35:54.000000 seqLister-1.1.0/src/seqLister.egg-info/PKG-INFO
+-rwxrwxrwx   0 jrowell   (1026) users      (100)       10 2023-06-28 01:35:54.000000 seqLister-1.1.0/src/seqLister.egg-info/top_level.txt
+-rwxrwxrwx   0 jrowell   (1026) users      (100)     4674 2023-06-28 01:35:54.000000 seqLister-1.1.0/PKG-INFO
+-rwxrwxrwx   0 jrowell   (1026) users      (100)      104 2021-06-23 03:32:49.000000 seqLister-1.1.0/pyproject.toml
+-rw-rw-rw-   0 jrowell   (1026) users      (100)     1620 2022-09-13 00:23:24.000000 seqLister-1.1.0/LICENSE
+-rwxrwxrwx   0 jrowell   (1026) users      (100)      742 2023-06-28 01:35:54.000000 seqLister-1.1.0/setup.cfg
+-rw-rw-rw-   0 jrowell   (1026) users      (100)     4020 2023-06-27 19:25:28.000000 seqLister-1.1.0/README.md
+-rwxrwxrwx   0 jrowell   (1026) users      (100)       68 2023-06-27 19:57:46.000000 seqLister-1.1.0/setup.py
```

### Comparing `seqLister-1.0.0/src/seqLister/__init__.py` & `seqLister-1.1.0/src/seqLister/__init__.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 # BSD 3-Clause License
 #
-# Copyright (c) 2008-2021, James Philip Rowell,
+# Copyright (c) 2008-2023, James Philip Rowell,
 # Alpha Eleven Incorporated
 # www.alpha-eleven.com
 # All rights reserved.
 #
 # Redistribution and use in source and binary forms, with or without
 # modification, are permitted provided that the following conditions are
 # met:
@@ -33,14 +33,19 @@
 # (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
 # OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
 
 
 # seqLister module - used for expanding and condensing ranges of
 # frame numbers to/from a common format to describe such ranges.
 
+# MAJOR version for incompatible API changes
+# MINOR version for added functionality in a backwards compatible manner
+# PATCH version for backwards compatible bug fixes
+#
+__version__ = "1.1.0"
 
 # Expands the argument 'seqList' into a list of integers.
 # 'seqList' may be a single string with the following format
 # (see description below), or a list of integers and/or
 # strings of the following format:
 #
 # individual frame numbers: [1, "4", 10, 15]
@@ -99,27 +104,27 @@
             if len(lastItem) != 2 :
                 nonSeqList.append(origItem)
                 continue
             if not lastItem[1].isdigit() :
                 nonSeqList.append(origItem)
                 continue
             stepValue = int(lastItem[1])
-            seqItemList[-1] = lastItem[0] # Stick back in list minus "xN" part
+            seqItemList[-1] = lastItem[0] # Stick last element back in the list w/o "xN" part
 
         if seqItemList[0] == "" : # Means there was leading minus sign.
             seqItemList.pop(0)
             if len(seqItemList) == 0:
                 nonSeqList.append(origItem)
                 continue
             if not seqItemList[0].isdigit() :
                 nonSeqList.append(origItem)
                 continue
             seqItemList[0] = -1 * int(seqItemList[0]) # Repace first entry...
         elif seqItemList[0].isdigit() :
-            seqItemList[0] = int(seqItemList[0]) #...with an ingeter.
+            seqItemList[0] = int(seqItemList[0]) #...with an integer.
         else :
             nonSeqList.append(origItem)
             continue
 
         if len(seqItemList) == 1 : # Was just string with one number in it.
             if seqItemList[0] not in resultList :
                 resultList.append(seqItemList[0])
@@ -208,31 +213,37 @@
 # [1, 1, 1, 3, 3, 5, 5, 5] -> ['1-5x2']
 # [1, 2, 3, 4, 6, 8, 10] -> ['1-4', '6-10x2']
 # [1, 2, 3, 4, 6, 8] -> ['1-4', '6', '8']
 #
 # condenseSeq(expandSeq(["2-50x2", "3-50x3", "5-50x5", "7-50x7", "11-50x11", "13-50x13", "17-50x17", "19-50x19", "23-50x23"]))
 #     yeilds -> ['2-28', '30', '32-36', '38-40', '42', '44-46', '48-50']
 #
-def condenseSeq(seqList, pad=1) :
+def condenseSeq(seqList, pad=1, nonSeqList=[]) :
+
+    condensedList = []
 
-    # Turn seqList into all integers and throw away invalid entries
+    # Turn seqList into all integers and stash invalid entries
     #
     tmpSeqList = seqList
     seqList = []
     for n in tmpSeqList :
         if isinstance(n, int) :
             seqList.append(int(n))
-        if isinstance(n, str) :
+        elif isinstance(n, str) :
             if n.isdigit() :
                 seqList.append(int(n))
             elif n[0] == "-" and n[1:].isdigit() :
-                seqList.append(-1 * int(n))
+                seqList.append(-1 * int(n[1:]))
+            else :
+                nonSeqList.append(n)
+        else :
+            nonSeqList.append(n)
 
     if len(seqList) == 0 : # Take care of 1st trivial case
-        return []
+        return condensedList
 
     # Remove duplicates
     #
     seqList.sort()
     tmpSeqList = seqList
     seqList = []
     seqList.append(tmpSeqList[0])
@@ -240,15 +251,16 @@
     for n in tmpSeqList :
         if n != seqList[-1] :
             seqList.append(n)
 
     formatStr = "%0" + str(pad) + "d"
 
     if len(seqList) == 1 : # Take care of second trivial case.
-        return [formatStr % seqList[0]]
+        condensedList.append(formatStr % seqList[0])
+        return condensedList
 
     # At this point - guaranteed that len(seqList) > 1
 
     gapList = []
     i = 1
     while i < len(seqList) : # Record gaps between frame #'s
         gapList.append(seqList[i] - seqList[i-1])
@@ -339,31 +351,37 @@
 # to a range (A-B) if and only if the numbers are successive.
 #
 # This [2, 1, 3, 7, 8, 4, 5, 6, 9, 10]
 #     yeilds -> ['1-10']
 # and this [0, 8, 16, 2, 4, 6, 10, 12, 14]
 #     yeilds -> [0, 2, 4, 6, 8, 10, 12, 14, 16]
 #
-def condenseSeqOnes(seqList, pad=1) :
+def condenseSeqOnes(seqList, pad=1, nonSeqList=[]) :
+
+    condensedList = []
 
-    # Turn seqList into all integers and throw away invalid entries
+    # Turn seqList into all integers and stash invalid entries
     #
     tmpSeqList = seqList
     seqList = []
     for n in tmpSeqList :
         if isinstance(n, int) :
             seqList.append(int(n))
-        if isinstance(n, str) :
+        elif isinstance(n, str) :
             if n.isdigit() :
                 seqList.append(int(n))
             elif n[0] == "-" and n[1:].isdigit() :
-                seqList.append(-1 * int(n))
+                seqList.append(-1 * int(n[1:]))
+            else:
+                nonSeqList.append(n)
+        else:
+            nonSeqList.append(n)
 
     if len(seqList) == 0 : # Take care of 1st trivial case
-        return []
+        return condensedList
 
     # Remove duplicates
     #
     seqList.sort()
     tmpSeqList = seqList
     seqList = []
     seqList.append(tmpSeqList[0])
@@ -371,15 +389,16 @@
     for n in tmpSeqList :
         if n != seqList[-1] :
             seqList.append(n)
 
     formatStr = "%0" + str(pad) + "d"
 
     if len(seqList) == 1 : # Take care of second trivial case.
-        return [formatStr % seqList[0]]
+        condensedList.append(formatStr % seqList[0])
+        return condensedList
 
     # At this point - guaranteed that len(seqList) > 1
 
     condensedList = []
 
     firstFrame = seqList[0]
     lastFrame = seqList[0]
```

### Comparing `seqLister-1.0.0/src/seqLister.egg-info/PKG-INFO` & `seqLister-1.1.0/src/seqLister.egg-info/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: seqLister
-Version: 1.0.0
+Version: 1.1.0
 Summary: Python library to expand and condense integer-sequences using a simple syntax widely used within the VFX-industry for specifying frame-ranges.
 Home-page: https://github.com/jrowellfx/seqLister
 Author: James Rowell
 Author-email: james@alpha-eleven.com
 License: UNKNOWN
 Project-URL: Bug Tracker, https://github.com/jrowellfx/seqLister/issues
 Platform: UNKNOWN
@@ -61,19 +61,19 @@
 been listed once, it will not be listed again.
 
 Eg. seqLister.expandSeq(["0-16x8", "0-16x2"]) returns  
 [0, 8, 16, 2, 4, 6, 10, 12, 14]
 
 Anything that is not of the above format is ignored for
 the purposes of building the list of integers and the ignored
-item is appended to the optional argument "nonSeqList".
+items are appended to the optional argument "nonSeqList".
 
 The returned list of integers is NOT sorted.
 
-### condenseSeq(seqList, pad=1)
+### condenseSeq(seqList, pad=1, nonSeqList=[])
 
 Takes a list of numbers and condenses it into the most minimal
 form using the syntax described in 'expandSeq()' above. Since the returned 
 list is a list of strings, then you can specify the padding of the integers with
 the optional pad argument.
 
 Examples:  
@@ -104,23 +104,31 @@
 
 seqLister.condenseSeq([1, 2, 3, 4, 6, 8]) returns  
 ['1-4', '6', '8']
 
 condenseSeq(expandSeq(["2-50x2", "3-50x3", "5-50x5", "7-50x7", "11-50x11", "13-50x13", "17-50x17", "19-50x19", "23-50x23"])) returns  
 ['2-28', '30', '32-36', '38-40', '42', '44-46', '48-50']
 
+Anything in seqList that is not an integer is ignored for
+the purposes of condensing the list of integers and the ignored
+items are appended to the optional argument "nonSeqList".
+
 ### condenseSeqOnes(seqList, pad=1)
 
 Takes a list of numbers and condenses it into the most minimal
-form using with the restriction that sequences are compressed
+form with the restriction that sequences are compressed
 to a range (A-B) if and only if the numbers are successive.
 
 Examples:
 
 seqLister.condenseSeqOnes([2, 1, 3, 7, 8, 4, 5, 6, 9, 10]) returns   
 ['1-10']
 
 seqLister.condenseSeqOnes([0, 8, 16, 2, 4, 6, 10, 12, 14]) returns   
 ['0', '2', '4', '6', '8', '10', '12', '14', '16']
 
+As with condenseSeq,
+anything in seqList that is not an integer is ignored for
+the purposes of condensing the list of integers and the ignored
+items are appended to the optional argument "nonSeqList".
```

### Comparing `seqLister-1.0.0/PKG-INFO` & `seqLister-1.1.0/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: seqLister
-Version: 1.0.0
+Version: 1.1.0
 Summary: Python library to expand and condense integer-sequences using a simple syntax widely used within the VFX-industry for specifying frame-ranges.
 Home-page: https://github.com/jrowellfx/seqLister
 Author: James Rowell
 Author-email: james@alpha-eleven.com
 License: UNKNOWN
 Project-URL: Bug Tracker, https://github.com/jrowellfx/seqLister/issues
 Platform: UNKNOWN
@@ -61,19 +61,19 @@
 been listed once, it will not be listed again.
 
 Eg. seqLister.expandSeq(["0-16x8", "0-16x2"]) returns  
 [0, 8, 16, 2, 4, 6, 10, 12, 14]
 
 Anything that is not of the above format is ignored for
 the purposes of building the list of integers and the ignored
-item is appended to the optional argument "nonSeqList".
+items are appended to the optional argument "nonSeqList".
 
 The returned list of integers is NOT sorted.
 
-### condenseSeq(seqList, pad=1)
+### condenseSeq(seqList, pad=1, nonSeqList=[])
 
 Takes a list of numbers and condenses it into the most minimal
 form using the syntax described in 'expandSeq()' above. Since the returned 
 list is a list of strings, then you can specify the padding of the integers with
 the optional pad argument.
 
 Examples:  
@@ -104,23 +104,31 @@
 
 seqLister.condenseSeq([1, 2, 3, 4, 6, 8]) returns  
 ['1-4', '6', '8']
 
 condenseSeq(expandSeq(["2-50x2", "3-50x3", "5-50x5", "7-50x7", "11-50x11", "13-50x13", "17-50x17", "19-50x19", "23-50x23"])) returns  
 ['2-28', '30', '32-36', '38-40', '42', '44-46', '48-50']
 
+Anything in seqList that is not an integer is ignored for
+the purposes of condensing the list of integers and the ignored
+items are appended to the optional argument "nonSeqList".
+
 ### condenseSeqOnes(seqList, pad=1)
 
 Takes a list of numbers and condenses it into the most minimal
-form using with the restriction that sequences are compressed
+form with the restriction that sequences are compressed
 to a range (A-B) if and only if the numbers are successive.
 
 Examples:
 
 seqLister.condenseSeqOnes([2, 1, 3, 7, 8, 4, 5, 6, 9, 10]) returns   
 ['1-10']
 
 seqLister.condenseSeqOnes([0, 8, 16, 2, 4, 6, 10, 12, 14]) returns   
 ['0', '2', '4', '6', '8', '10', '12', '14', '16']
 
+As with condenseSeq,
+anything in seqList that is not an integer is ignored for
+the purposes of condensing the list of integers and the ignored
+items are appended to the optional argument "nonSeqList".
```

### Comparing `seqLister-1.0.0/LICENSE` & `seqLister-1.1.0/LICENSE`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 3-Clause BSD License
 
-Copyright (c) 2008-2021, James Philip Rowell,
+Copyright (c) 2008-2022, James Philip Rowell,
 Alpha Eleven Incorporated
 www.alpha-eleven.com
 All rights reserved.
 
 Redistribution and use in source and binary forms, with or without
 modification, are permitted provided that the following conditions are
 met:
```

### Comparing `seqLister-1.0.0/setup.cfg` & `seqLister-1.1.0/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = seqLister
-version = 1.0.0
+version = 1.1.0
 author = James Rowell
 author_email = james@alpha-eleven.com
 description = Python library to expand and condense integer-sequences using a simple syntax widely used within the VFX-industry for specifying frame-ranges.
 long_description = file: README.md
 long_description_content_type = text/markdown
 url = https://github.com/jrowellfx/seqLister
 project_urls =
```

### Comparing `seqLister-1.0.0/README.md` & `seqLister-1.1.0/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -44,19 +44,19 @@
 been listed once, it will not be listed again.
 
 Eg. seqLister.expandSeq(["0-16x8", "0-16x2"]) returns  
 [0, 8, 16, 2, 4, 6, 10, 12, 14]
 
 Anything that is not of the above format is ignored for
 the purposes of building the list of integers and the ignored
-item is appended to the optional argument "nonSeqList".
+items are appended to the optional argument "nonSeqList".
 
 The returned list of integers is NOT sorted.
 
-### condenseSeq(seqList, pad=1)
+### condenseSeq(seqList, pad=1, nonSeqList=[])
 
 Takes a list of numbers and condenses it into the most minimal
 form using the syntax described in 'expandSeq()' above. Since the returned 
 list is a list of strings, then you can specify the padding of the integers with
 the optional pad argument.
 
 Examples:  
@@ -87,21 +87,29 @@
 
 seqLister.condenseSeq([1, 2, 3, 4, 6, 8]) returns  
 ['1-4', '6', '8']
 
 condenseSeq(expandSeq(["2-50x2", "3-50x3", "5-50x5", "7-50x7", "11-50x11", "13-50x13", "17-50x17", "19-50x19", "23-50x23"])) returns  
 ['2-28', '30', '32-36', '38-40', '42', '44-46', '48-50']
 
+Anything in seqList that is not an integer is ignored for
+the purposes of condensing the list of integers and the ignored
+items are appended to the optional argument "nonSeqList".
+
 ### condenseSeqOnes(seqList, pad=1)
 
 Takes a list of numbers and condenses it into the most minimal
-form using with the restriction that sequences are compressed
+form with the restriction that sequences are compressed
 to a range (A-B) if and only if the numbers are successive.
 
 Examples:
 
 seqLister.condenseSeqOnes([2, 1, 3, 7, 8, 4, 5, 6, 9, 10]) returns   
 ['1-10']
 
 seqLister.condenseSeqOnes([0, 8, 16, 2, 4, 6, 10, 12, 14]) returns   
 ['0', '2', '4', '6', '8', '10', '12', '14', '16']
 
+As with condenseSeq,
+anything in seqList that is not an integer is ignored for
+the purposes of condensing the list of integers and the ignored
+items are appended to the optional argument "nonSeqList".
```

