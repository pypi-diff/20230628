# Comparing `tmp/sb6-0.0.6.tar.gz` & `tmp/sb6-0.0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sb6-0.0.6.tar", last modified: Wed Jun 28 15:19:16 2023, max compression
+gzip compressed data, was "sb6-0.0.7.tar", last modified: Wed Jun 28 15:37:28 2023, max compression
```

## Comparing `sb6-0.0.6.tar` & `sb6-0.0.7.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 15:19:16.684479 sb6-0.0.6/
--rw-rw-rw-   0        0        0     1067 2023-04-11 12:54:43.000000 sb6-0.0.6/LICENSE
--rw-rw-rw-   0        0        0      462 2023-06-28 15:19:16.683479 sb6-0.0.6/PKG-INFO
--rw-rw-rw-   0        0        0       69 2023-05-12 01:06:50.000000 sb6-0.0.6/README.md
--rw-rw-rw-   0        0        0       42 2023-06-28 15:19:16.684479 sb6-0.0.6/setup.cfg
--rw-rw-rw-   0        0        0      738 2023-06-28 15:16:09.000000 sb6-0.0.6/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 15:19:16.674479 sb6-0.0.6/src/
-drwxrwxrwx   0        0        0        0 2023-06-28 15:19:16.683479 sb6-0.0.6/src/sb6.egg-info/
--rw-rw-rw-   0        0        0      462 2023-06-28 15:19:16.000000 sb6-0.0.6/src/sb6.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      191 2023-06-28 15:19:16.000000 sb6-0.0.6/src/sb6.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 15:19:16.000000 sb6-0.0.6/src/sb6.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       27 2023-06-28 15:19:16.000000 sb6-0.0.6/src/sb6.egg-info/requires.txt
--rw-rw-rw-   0        0        0        4 2023-06-28 15:19:16.000000 sb6-0.0.6/src/sb6.egg-info/top_level.txt
--rw-rw-rw-   0        0        0   150665 2023-06-28 15:17:16.000000 sb6-0.0.6/src/sb6.py
+drwxrwxrwx   0        0        0        0 2023-06-28 15:37:28.083860 sb6-0.0.7/
+-rw-rw-rw-   0        0        0     1067 2023-04-11 12:54:43.000000 sb6-0.0.7/LICENSE
+-rw-rw-rw-   0        0        0      462 2023-06-28 15:37:28.082860 sb6-0.0.7/PKG-INFO
+-rw-rw-rw-   0        0        0       69 2023-05-12 01:06:50.000000 sb6-0.0.7/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 15:37:28.083860 sb6-0.0.7/setup.cfg
+-rw-rw-rw-   0        0        0      738 2023-06-28 15:37:13.000000 sb6-0.0.7/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 15:37:28.070861 sb6-0.0.7/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 15:37:28.082860 sb6-0.0.7/src/sb6.egg-info/
+-rw-rw-rw-   0        0        0      462 2023-06-28 15:37:28.000000 sb6-0.0.7/src/sb6.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      191 2023-06-28 15:37:28.000000 sb6-0.0.7/src/sb6.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 15:37:28.000000 sb6-0.0.7/src/sb6.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       27 2023-06-28 15:37:28.000000 sb6-0.0.7/src/sb6.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        4 2023-06-28 15:37:28.000000 sb6-0.0.7/src/sb6.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0   150666 2023-06-28 15:36:51.000000 sb6-0.0.7/src/sb6.py
```

### Comparing `sb6-0.0.6/LICENSE` & `sb6-0.0.7/LICENSE`

 * *Files identical despite different names*

### Comparing `sb6-0.0.6/setup.py` & `sb6-0.0.7/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="sb6",
-    version="0.0.6",
+    version="0.0.7",
     description='chatbot',
     license='MIT',
     author="aiml department",
     author_email="aiml@gmail.com",
     long_description=long_description,
     long_description_content_type="text/markdown",
     packages=setuptools.find_packages(),
```

### Comparing `sb6-0.0.6/src/sb6.py` & `sb6-0.0.7/src/sb6.py`

 * *Files 0% similar despite different names*

```diff
@@ -900,16 +900,16 @@
 target = LabelEncoder().fit_transform(target)       # automatic text to numbers 
 
 from sklearn.naive_bayes import GaussianNB
 bclassifier = GaussianNB().fit(xtrain,ytrain)
 bpredict = bclassifier.predict(xtest)       # predict for testing
 
 from sklearn.metrics import accuracy_score,confusion_matrix
-print(confusion_matrix(kpredict,ytest))          # if only diagonal no error
-print(accuracy_score(kpredict,ytest))       # only get accurecy
+print(confusion_matrix(bpredict,ytest))          # if only diagonal no error
+print(accuracy_score(bpredict,ytest))       # only get accurecy
         """)
         
     def nbnosothers():
         print(r"""
 import pandas as pd
 fulldata = pd.read_csv('Iris.csv')
 data = fulldata.iloc[:,1:-1].values
@@ -1510,15 +1510,15 @@
 # Calculate probability of Heart Disease given Age=63
 q = heart_disease_infer.query(variables=['heartdisease'], evidence={'age': 63})
 print(q)
 
 q = heart_disease_infer.query(variables=['heartdisease'], evidence={'chol': 233})  # cholesterol
 print(q)
 
-q = HeartDisease_infer.query(variables=['heartdisease'], evidence={'age': 63, 'sex' :1,'trestbps':130})
+q = heart_disease_infer.query(variables=['heartdisease'], evidence={'age': 63, 'sex' :1,'trestbps':130})
 print(q)
         """)
 
 class mlfull():
     """
 pg1() : FIND-S : Finding a Maximally Specific (0) Hypothesis  
     Implement and demonstrate the FIND-S algorithm for finding the most specific hypothesis based on a given set of training data samples.
```

