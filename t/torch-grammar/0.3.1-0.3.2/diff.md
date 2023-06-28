# Comparing `tmp/torch_grammar-0.3.1.tar.gz` & `tmp/torch_grammar-0.3.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "torch_grammar-0.3.1.tar", max compression
+gzip compressed data, was "torch_grammar-0.3.2.tar", max compression
```

## Comparing `torch_grammar-0.3.1.tar` & `torch_grammar-0.3.2.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0     1890 2023-06-27 14:34:41.788242 torch_grammar-0.3.1/README.md
--rw-r--r--   0        0        0      588 2023-06-27 14:35:12.424183 torch_grammar-0.3.1/pyproject.toml
--rw-r--r--   0        0        0       74 2023-06-19 15:27:17.327365 torch_grammar-0.3.1/torch_grammar/__init__.py
--rw-r--r--   0        0        0     9709 2023-06-19 17:39:52.938166 torch_grammar-0.3.1/torch_grammar/grammar_parser.py
--rw-r--r--   0        0        0     6419 2023-06-26 21:03:33.486520 torch_grammar-0.3.1/torch_grammar/grammar_sampler.py
--rw-r--r--   0        0        0     2626 2023-06-27 14:34:57.299812 torch_grammar-0.3.1/torch_grammar/token_trie.py
--rw-r--r--   0        0        0     2528 1970-01-01 00:00:00.000000 torch_grammar-0.3.1/PKG-INFO
+-rw-r--r--   0        0        0     1890 2023-06-27 14:34:41.788242 torch_grammar-0.3.2/README.md
+-rw-r--r--   0        0        0      588 2023-06-28 16:16:07.654313 torch_grammar-0.3.2/pyproject.toml
+-rw-r--r--   0        0        0       74 2023-06-19 15:27:17.327365 torch_grammar-0.3.2/torch_grammar/__init__.py
+-rw-r--r--   0        0        0     9709 2023-06-19 17:39:52.938166 torch_grammar-0.3.2/torch_grammar/grammar_parser.py
+-rw-r--r--   0        0        0     6473 2023-06-28 16:11:27.863024 torch_grammar-0.3.2/torch_grammar/grammar_sampler.py
+-rw-r--r--   0        0        0     2626 2023-06-27 14:34:57.299812 torch_grammar-0.3.2/torch_grammar/token_trie.py
+-rw-r--r--   0        0        0     2528 1970-01-01 00:00:00.000000 torch_grammar-0.3.2/PKG-INFO
```

### Comparing `torch_grammar-0.3.1/README.md` & `torch_grammar-0.3.2/README.md`

 * *Files identical despite different names*

### Comparing `torch_grammar-0.3.1/pyproject.toml` & `torch_grammar-0.3.2/pyproject.toml`

 * *Files 18% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "torch-grammar"
-version = "0.3.1"
+version = "0.3.2"
 description = "Restrict LLM generations to a context-free grammar"
 authors = ["Burke Libbey <burke.libbey@shopify.com>"]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "torch_grammar"}]
 
 [tool.poetry.dependencies]
```

### Comparing `torch_grammar-0.3.1/torch_grammar/grammar_parser.py` & `torch_grammar-0.3.2/torch_grammar/grammar_parser.py`

 * *Files identical despite different names*

### Comparing `torch_grammar-0.3.1/torch_grammar/grammar_sampler.py` & `torch_grammar-0.3.2/torch_grammar/grammar_sampler.py`

 * *Files 3% similar despite different names*

```diff
@@ -22,15 +22,15 @@
         elif len(input_ids[0]) == self.last_size + 1:
             self.stacks = self.grammar.accept_token(input_ids[0][-1], self.stacks)
         else:
             raise "Input size changed"
 
         # TODO: the <s> token should be accounted for directly rather than just
         # dropped here...
-        self.grammar.filter_logits(scores[0], self.stacks)
+        self.grammar.filter_logits(scores[0], self.stacks, scores.device)
 
         self.last_size = len(input_ids[0])
         return scores
 
 
 class GrammarSampler:
     def __init__(self, input_text, start_rule_name, tokenizer):
@@ -143,16 +143,16 @@
         for i in range(0, num_chars, 2):
             start = self.src[pos + i]
             end = self.src[pos + i + 1]
             for j in range(start, end + 1):
                 acceptance[j] = True
         return acceptance
 
-    @lru_cache(maxsize=1024)
-    def token_acceptance_for_stack(self, stack):
+    @lru_cache(maxsize=8192)
+    def token_acceptance_for_stack(self, stack, device):
         st = time.time()
         stack = list(stack)  # needs to come in as a tuple for lru_cache
 
         accepts = [False] * len(self.token_trie)
         accepts[self.eos_token_id] = len(stack) == 0
 
         def traverse_trie(trie, stacks):
@@ -182,22 +182,22 @@
 
                 if new_stacks:
                     traverse_trie(next_trie, new_stacks)
 
         traverse_trie(self.token_trie.trie, [stack])
 
         et = time.time() - st
-        x = torch.tensor(accepts, dtype=torch.bool)
+        x = torch.tensor(accepts, dtype=torch.bool, device=device)
         self.tt += et
         self.nt += 1
         return x
 
-    def filter_logits(self, logits, stacks):
+    def filter_logits(self, logits, stacks, device):
         # resolve each stack to a tensor of True/False for each token
         # indicating acceptance
         acceptance = torch.cat(
-            [self.token_acceptance_for_stack(tuple(stack)) for stack in stacks]
+            [self.token_acceptance_for_stack(tuple(stack), device) for stack in stacks]
         )
         # Merge stacks: any True => True
         acceptance = acceptance.reshape(len(stacks), -1).any(dim=0)
         # Logits to -inf where False
         logits[~acceptance] = -inf
```

### Comparing `torch_grammar-0.3.1/torch_grammar/token_trie.py` & `torch_grammar-0.3.2/torch_grammar/token_trie.py`

 * *Files identical despite different names*

### Comparing `torch_grammar-0.3.1/PKG-INFO` & `torch_grammar-0.3.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: torch-grammar
-Version: 0.3.1
+Version: 0.3.2
 Summary: Restrict LLM generations to a context-free grammar
 License: MIT
 Author: Burke Libbey
 Author-email: burke.libbey@shopify.com
 Requires-Python: >=3.9,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
```

