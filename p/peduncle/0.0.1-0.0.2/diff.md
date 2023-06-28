# Comparing `tmp/peduncle-0.0.1.tar.gz` & `tmp/peduncle-0.0.2.tar.gz`

## Comparing `peduncle-0.0.1.tar` & `peduncle-0.0.2.tar`

### file list

```diff
@@ -1,10 +1,11 @@
--rw-r--r--   0        0        0     4079 2020-02-02 00:00:00.000000 peduncle-0.0.1/benchmark/benchmark.py
--rw-r--r--   0        0        0      318 2020-02-02 00:00:00.000000 peduncle-0.0.1/src/example.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 peduncle-0.0.1/src/peduncle/__init__.py
--rw-r--r--   0        0        0     2418 2020-02-02 00:00:00.000000 peduncle-0.0.1/src/peduncle/grader.py
--rw-r--r--   0        0        0      604 2020-02-02 00:00:00.000000 peduncle-0.0.1/src/peduncle/peduncle.py
--rw-r--r--   0        0        0       11 2020-02-02 00:00:00.000000 peduncle-0.0.1/.gitignore
--rw-r--r--   0        0        0     1076 2020-02-02 00:00:00.000000 peduncle-0.0.1/LICENSE
--rw-r--r--   0        0        0      379 2020-02-02 00:00:00.000000 peduncle-0.0.1/README.md
--rw-r--r--   0        0        0      582 2020-02-02 00:00:00.000000 peduncle-0.0.1/pyproject.toml
--rw-r--r--   0        0        0      899 2020-02-02 00:00:00.000000 peduncle-0.0.1/PKG-INFO
+-rw-r--r--   0        0        0     1968 2020-02-02 00:00:00.000000 peduncle-0.0.2/.github/workflows/publish.yml
+-rw-r--r--   0        0        0     4231 2020-02-02 00:00:00.000000 peduncle-0.0.2/benchmark/benchmark.py
+-rw-r--r--   0        0        0      318 2020-02-02 00:00:00.000000 peduncle-0.0.2/src/example.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 peduncle-0.0.2/src/peduncle/__init__.py
+-rw-r--r--   0        0        0     2418 2020-02-02 00:00:00.000000 peduncle-0.0.2/src/peduncle/grader.py
+-rw-r--r--   0        0        0      604 2020-02-02 00:00:00.000000 peduncle-0.0.2/src/peduncle/peduncle.py
+-rw-r--r--   0        0        0       16 2020-02-02 00:00:00.000000 peduncle-0.0.2/.gitignore
+-rw-r--r--   0        0        0     1076 2020-02-02 00:00:00.000000 peduncle-0.0.2/LICENSE
+-rw-r--r--   0        0        0     1509 2020-02-02 00:00:00.000000 peduncle-0.0.2/README.md
+-rw-r--r--   0        0        0      582 2020-02-02 00:00:00.000000 peduncle-0.0.2/pyproject.toml
+-rw-r--r--   0        0        0     2029 2020-02-02 00:00:00.000000 peduncle-0.0.2/PKG-INFO
```

### Comparing `peduncle-0.0.1/benchmark/benchmark.py` & `peduncle-0.0.2/benchmark/benchmark.py`

 * *Files 9% similar despite different names*

```diff
@@ -84,41 +84,48 @@
             )[0][0] for i in range(answer_mat.shape[0])
         ])
         
     def get_final_score(self):
         self.run()
         return self.scores.mean()
     
+    def get_acc_rate(self,threshold):
+        c = 0
+        for i in self.scores:
+            if i > threshold:
+                c+=1
+        return c/len(self.scores)
+    
     def clean(self, text):
         text: str = text.replace("\n", " ").replace("\r", " ").replace("\t", " ")
         return re.sub(r'\s+', ' ', text)
         
 if __name__=="__main__":
     
     data = DataLoader()
     evaluator = Evaluator()
     
-    extracted_content_len = 0
-    eval_str_len = 0
+    diffs = []
     
     with tqdm(total=len(data)) as bar:
         for raw_fname,eval_fname in data:
             raw_file = open(raw_fname,'r',encoding='utf8',errors='ignore')
             eval_file = open(eval_fname,'r',encoding='utf8',errors='ignore')
             raw_str = raw_file.read()
             eval_str = eval_file.read()
             raw_file.close()
             eval_file.close()
             
             # extracted_content = evaluator.clean(Grader(raw_str).main_node.text)
-            extracted_content = evaluator.clean(extract_text(raw_str))
+            extracted_content = evaluator.clean(extract_text(raw_str,0.21))
 
             eval_str = evaluator.clean(eval_str)
             evaluator.push(extracted_content,eval_str)
             
-            extracted_content_len += len(extracted_content)/len(data)
-            eval_str_len += len(eval_str)/len(data)
+            diffs.append(len(extracted_content)-len(eval_str))
             
             bar.update()
     
     print(f"similarty: {evaluator.get_final_score()}")
-    print(f"len_diff: {extracted_content_len-eval_str_len}")
+    print(f"acc: {evaluator.get_acc_rate(0.95)}")
+    print(f"len_diff: {np.mean(diffs)}")
+    print(f"diff std: {np.std(diffs)}")
```

### Comparing `peduncle-0.0.1/src/peduncle/grader.py` & `peduncle-0.0.2/src/peduncle/grader.py`

 * *Files identical despite different names*

### Comparing `peduncle-0.0.1/src/peduncle/peduncle.py` & `peduncle-0.0.2/src/peduncle/peduncle.py`

 * *Files identical despite different names*

### Comparing `peduncle-0.0.1/LICENSE` & `peduncle-0.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `peduncle-0.0.1/pyproject.toml` & `peduncle-0.0.2/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling"]
 build-backend = "hatchling.build"
 
 [project]
 name = "peduncle"
-version = "0.0.1"
+version = "0.0.2"
 authors = [
   { name="Midstream", email="midstream.lou@gmail.com" },
 ]
 description = "Simple Python content extractor for html"
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

