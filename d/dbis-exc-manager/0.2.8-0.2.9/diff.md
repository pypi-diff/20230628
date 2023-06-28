# Comparing `tmp/dbis-exc-manager-0.2.8.tar.gz` & `tmp/dbis-exc-manager-0.2.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dbis-exc-manager-0.2.8.tar", last modified: Fri Jul 15 13:11:06 2022, max compression
+gzip compressed data, was "dbis-exc-manager-0.2.9.tar", last modified: Mon Jul 18 06:08:25 2022, max compression
```

## Comparing `dbis-exc-manager-0.2.8.tar` & `dbis-exc-manager-0.2.9.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-07-15 13:11:06.521142 dbis-exc-manager-0.2.8/
--rw-r--r--   0 runner    (1001) docker     (121)    11357 2022-07-15 13:10:57.000000 dbis-exc-manager-0.2.8/LICENSE
--rw-r--r--   0 runner    (1001) docker     (121)     1663 2022-07-15 13:11:06.521142 dbis-exc-manager-0.2.8/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)     1070 2022-07-15 13:10:57.000000 dbis-exc-manager-0.2.8/README.md
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-07-15 13:11:06.521142 dbis-exc-manager-0.2.8/dbis_exc_manager.egg-info/
--rw-r--r--   0 runner    (1001) docker     (121)     1663 2022-07-15 13:11:06.000000 dbis-exc-manager-0.2.8/dbis_exc_manager.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)      329 2022-07-15 13:11:06.000000 dbis-exc-manager-0.2.8/dbis_exc_manager.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-07-15 13:11:06.000000 dbis-exc-manager-0.2.8/dbis_exc_manager.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (121)       75 2022-07-15 13:11:06.000000 dbis-exc-manager-0.2.8/dbis_exc_manager.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (121)       11 2022-07-15 13:11:06.000000 dbis-exc-manager-0.2.8/dbis_exc_manager.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-07-15 13:11:06.521142 dbis-exc-manager-0.2.8/excmanager/
--rw-r--r--   0 runner    (1001) docker     (121)     3574 2022-07-15 13:10:57.000000 dbis-exc-manager-0.2.8/excmanager/Task.py
--rw-r--r--   0 runner    (1001) docker     (121)     7169 2022-07-15 13:10:57.000000 dbis-exc-manager-0.2.8/excmanager/Util.py
--rw-r--r--   0 runner    (1001) docker     (121)      174 2022-07-15 13:10:57.000000 dbis-exc-manager-0.2.8/excmanager/Version.py
--rw-r--r--   0 runner    (1001) docker     (121)        0 2022-07-15 13:10:57.000000 dbis-exc-manager-0.2.8/excmanager/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     4009 2022-07-15 13:10:57.000000 dbis-exc-manager-0.2.8/excmanager/scorer.py
--rw-r--r--   0 runner    (1001) docker     (121)       38 2022-07-15 13:11:06.521142 dbis-exc-manager-0.2.8/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (121)     1029 2022-07-15 13:10:57.000000 dbis-exc-manager-0.2.8/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-07-18 06:08:25.989611 dbis-exc-manager-0.2.9/
+-rw-r--r--   0 runner    (1001) docker     (121)    11357 2022-07-18 06:08:13.000000 dbis-exc-manager-0.2.9/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (121)     1663 2022-07-18 06:08:25.989611 dbis-exc-manager-0.2.9/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (121)     1070 2022-07-18 06:08:13.000000 dbis-exc-manager-0.2.9/README.md
+drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-07-18 06:08:25.989611 dbis-exc-manager-0.2.9/dbis_exc_manager.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (121)     1663 2022-07-18 06:08:25.000000 dbis-exc-manager-0.2.9/dbis_exc_manager.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (121)      329 2022-07-18 06:08:25.000000 dbis-exc-manager-0.2.9/dbis_exc_manager.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (121)        1 2022-07-18 06:08:25.000000 dbis-exc-manager-0.2.9/dbis_exc_manager.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (121)       75 2022-07-18 06:08:25.000000 dbis-exc-manager-0.2.9/dbis_exc_manager.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (121)       11 2022-07-18 06:08:25.000000 dbis-exc-manager-0.2.9/dbis_exc_manager.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-07-18 06:08:25.989611 dbis-exc-manager-0.2.9/excmanager/
+-rw-r--r--   0 runner    (1001) docker     (121)     3574 2022-07-18 06:08:13.000000 dbis-exc-manager-0.2.9/excmanager/Task.py
+-rw-r--r--   0 runner    (1001) docker     (121)     7169 2022-07-18 06:08:13.000000 dbis-exc-manager-0.2.9/excmanager/Util.py
+-rw-r--r--   0 runner    (1001) docker     (121)      174 2022-07-18 06:08:13.000000 dbis-exc-manager-0.2.9/excmanager/Version.py
+-rw-r--r--   0 runner    (1001) docker     (121)        0 2022-07-18 06:08:13.000000 dbis-exc-manager-0.2.9/excmanager/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (121)     4364 2022-07-18 06:08:13.000000 dbis-exc-manager-0.2.9/excmanager/scorer.py
+-rw-r--r--   0 runner    (1001) docker     (121)       38 2022-07-18 06:08:25.989611 dbis-exc-manager-0.2.9/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (121)     1029 2022-07-18 06:08:13.000000 dbis-exc-manager-0.2.9/setup.py
```

### Comparing `dbis-exc-manager-0.2.8/LICENSE` & `dbis-exc-manager-0.2.9/LICENSE`

 * *Files identical despite different names*

### Comparing `dbis-exc-manager-0.2.8/PKG-INFO` & `dbis-exc-manager-0.2.9/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dbis-exc-manager
-Version: 0.2.8
+Version: 0.2.9
 Summary: RWTH Aachen Computer Science i5/dbis assets for Lecture Datenbanken und Informationssysteme
 Home-page: https://github.com/rwth-acis/dbis-exercise-manager.git
 Author: Michal Slupczynski
 Author-email: slupczynski@dbis.rwth-aachen.de
 License: Apache
 Platform: UNKNOWN
 Classifier: Programming Language :: Python
```

### Comparing `dbis-exc-manager-0.2.8/README.md` & `dbis-exc-manager-0.2.9/README.md`

 * *Files identical despite different names*

### Comparing `dbis-exc-manager-0.2.8/dbis_exc_manager.egg-info/PKG-INFO` & `dbis-exc-manager-0.2.9/dbis_exc_manager.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dbis-exc-manager
-Version: 0.2.8
+Version: 0.2.9
 Summary: RWTH Aachen Computer Science i5/dbis assets for Lecture Datenbanken und Informationssysteme
 Home-page: https://github.com/rwth-acis/dbis-exercise-manager.git
 Author: Michal Slupczynski
 Author-email: slupczynski@dbis.rwth-aachen.de
 License: Apache
 Platform: UNKNOWN
 Classifier: Programming Language :: Python
```

### Comparing `dbis-exc-manager-0.2.8/excmanager/Task.py` & `dbis-exc-manager-0.2.9/excmanager/Task.py`

 * *Files identical despite different names*

### Comparing `dbis-exc-manager-0.2.8/excmanager/Util.py` & `dbis-exc-manager-0.2.9/excmanager/Util.py`

 * *Files identical despite different names*

### Comparing `dbis-exc-manager-0.2.8/excmanager/scorer.py` & `dbis-exc-manager-0.2.9/excmanager/scorer.py`

 * *Files 7% similar despite different names*

```diff
@@ -16,15 +16,27 @@
             verbose(bool): if True show scoring checks and problems, default: True
             debug(bool): if True show debugging information, default: False
         '''
         self.maxscore=0.0 # maximum score
         self.score=0 # total score reached
         self.verbose=verbose
         self.debug=debug
-    
+        
+    def feedback(self,msg:str,positive:bool):
+        '''
+        give positive or negative feedback with the given message
+        
+        Args:
+            msg(str): the message to print
+            positive(bool): if True add a ✅ marker else ❌
+        '''
+        marker="✅" if positive else "❌"
+        if self.verbose:
+            print(f"{msg} {marker}")
+      
     def addScore(self,amount:float,check:str,problem:str=None,negativeOnProblem:bool=False):
         '''
         add the given amount to self.score if there is no problem 
         increment self.maxscore by 1
         
         Args:
             amount(float): the amount to add
@@ -37,21 +49,19 @@
         amountstr=f"{frac.numerator}/{frac.denominator}" if frac.denominator>1 else f"{frac.numerator}"
         if problem is not None:
             if negativeOnProblem:
                 msg=f"subtracting {amountstr}"
                 self.score-=amount
             else:
                 msg=f"no score"
-            if self.verbose:
-                print(f"{msg} for {check} due to {problem}❌")
+            self.feedback(f"{msg} for {check} due to {problem}", positive=False)
             return
         else:
             self.score+=amount
-            if self.verbose:
-                print(f"adding {amountstr} to score for {check}✅")
+            self.feedback(f"adding {amountstr} to score for {check}",positive=True)
                 
 class MultipleChoiceScorer(Scorer):
     '''
     scorer for multiple choice questions
     
     Für jede richtige Antwort gibt es 1/𝑛 Punkte.
     Für jede falsche Antwort gibt es −1/𝑛 Punkte.
```

### Comparing `dbis-exc-manager-0.2.8/setup.py` & `dbis-exc-manager-0.2.9/setup.py`

 * *Files identical despite different names*

