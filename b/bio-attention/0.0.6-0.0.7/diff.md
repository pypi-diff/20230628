# Comparing `tmp/bio-attention-0.0.6.tar.gz` & `tmp/bio-attention-0.0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "bio-attention-0.0.6.tar", last modified: Thu Jun  8 11:58:40 2023, max compression
+gzip compressed data, was "bio-attention-0.0.7.tar", last modified: Wed Jun 28 15:12:03 2023, max compression
```

## Comparing `bio-attention-0.0.6.tar` & `bio-attention-0.0.7.tar`

### file list

```diff
@@ -1,24 +1,24 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 11:58:40.390834 bio-attention-0.0.6/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 11:58:40.386834 bio-attention-0.0.6/.github/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 11:58:40.386834 bio-attention-0.0.6/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)      607 2023-06-08 11:58:28.000000 bio-attention-0.0.6/.github/workflows/publish.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1799 2023-06-08 11:58:28.000000 bio-attention-0.0.6/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-06-08 11:58:28.000000 bio-attention-0.0.6/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     2791 2023-06-08 11:58:40.390834 bio-attention-0.0.6/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2480 2023-06-08 11:58:28.000000 bio-attention-0.0.6/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 11:58:40.386834 bio-attention-0.0.6/bio_attention/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-08 11:58:28.000000 bio-attention-0.0.6/bio_attention/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16276 2023-06-08 11:58:28.000000 bio-attention-0.0.6/bio_attention/attention.py
--rw-r--r--   0 runner    (1001) docker     (123)     7563 2023-06-08 11:58:28.000000 bio-attention-0.0.6/bio_attention/embed.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 11:58:40.390834 bio-attention-0.0.6/bio_attention/img/
--rw-r--r--   0 runner    (1001) docker     (123)  2372654 2023-06-08 11:58:28.000000 bio-attention-0.0.6/bio_attention/img/2Dslidingwindow-attention.png
--rw-r--r--   0 runner    (1001) docker     (123)   118589 2023-06-08 11:58:28.000000 bio-attention-0.0.6/bio_attention/img/windowed_implementation.svg
--rw-r--r--   0 runner    (1001) docker     (123)    22849 2023-06-08 11:58:28.000000 bio-attention-0.0.6/bio_attention/positional.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-08 11:58:40.390834 bio-attention-0.0.6/bio_attention.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2791 2023-06-08 11:58:40.000000 bio-attention-0.0.6/bio_attention.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      465 2023-06-08 11:58:40.000000 bio-attention-0.0.6/bio_attention.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-08 11:58:40.000000 bio-attention-0.0.6/bio_attention.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-08 11:58:40.000000 bio-attention-0.0.6/bio_attention.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       14 2023-06-08 11:58:40.000000 bio-attention-0.0.6/bio_attention.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      136 2023-06-08 11:58:28.000000 bio-attention-0.0.6/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)      438 2023-06-08 11:58:40.390834 bio-attention-0.0.6/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:12:03.890345 bio-attention-0.0.7/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:12:03.882345 bio-attention-0.0.7/.github/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:12:03.886345 bio-attention-0.0.7/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)      607 2023-06-28 15:11:54.000000 bio-attention-0.0.7/.github/workflows/publish.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1799 2023-06-28 15:11:54.000000 bio-attention-0.0.7/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-06-28 15:11:54.000000 bio-attention-0.0.7/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     2791 2023-06-28 15:12:03.890345 bio-attention-0.0.7/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2480 2023-06-28 15:11:54.000000 bio-attention-0.0.7/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:12:03.886345 bio-attention-0.0.7/bio_attention/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:11:54.000000 bio-attention-0.0.7/bio_attention/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16898 2023-06-28 15:11:54.000000 bio-attention-0.0.7/bio_attention/attention.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7864 2023-06-28 15:11:54.000000 bio-attention-0.0.7/bio_attention/embed.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:12:03.890345 bio-attention-0.0.7/bio_attention/img/
+-rw-r--r--   0 runner    (1001) docker     (123)  2372654 2023-06-28 15:11:54.000000 bio-attention-0.0.7/bio_attention/img/2Dslidingwindow-attention.png
+-rw-r--r--   0 runner    (1001) docker     (123)   118589 2023-06-28 15:11:54.000000 bio-attention-0.0.7/bio_attention/img/windowed_implementation.svg
+-rw-r--r--   0 runner    (1001) docker     (123)    22849 2023-06-28 15:11:54.000000 bio-attention-0.0.7/bio_attention/positional.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:12:03.886345 bio-attention-0.0.7/bio_attention.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2791 2023-06-28 15:12:03.000000 bio-attention-0.0.7/bio_attention.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      465 2023-06-28 15:12:03.000000 bio-attention-0.0.7/bio_attention.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:12:03.000000 bio-attention-0.0.7/bio_attention.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       19 2023-06-28 15:12:03.000000 bio-attention-0.0.7/bio_attention.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       14 2023-06-28 15:12:03.000000 bio-attention-0.0.7/bio_attention.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      136 2023-06-28 15:11:54.000000 bio-attention-0.0.7/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)      438 2023-06-28 15:12:03.890345 bio-attention-0.0.7/setup.cfg
```

### Comparing `bio-attention-0.0.6/.github/workflows/publish.yml` & `bio-attention-0.0.7/.github/workflows/publish.yml`

 * *Files identical despite different names*

### Comparing `bio-attention-0.0.6/.gitignore` & `bio-attention-0.0.7/.gitignore`

 * *Files identical despite different names*

### Comparing `bio-attention-0.0.6/LICENSE` & `bio-attention-0.0.7/LICENSE`

 * *Files identical despite different names*

### Comparing `bio-attention-0.0.6/PKG-INFO` & `bio-attention-0.0.7/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: bio-attention
-Version: 0.0.6
+Version: 0.0.7
 Summary: Simple implementations of attention modules adapted for the biological data domain
 Home-page: https://github.com/gdewael/bio-attention
 Author: Gaetan De Waele
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
```

### Comparing `bio-attention-0.0.6/README.md` & `bio-attention-0.0.7/README.md`

 * *Files identical despite different names*

### Comparing `bio-attention-0.0.6/bio_attention/attention.py` & `bio-attention-0.0.7/bio_attention/attention.py`

 * *Files 2% similar despite different names*

```diff
@@ -532,8 +532,29 @@
     
 class TransformerDecoder(Transformer):
     def __init__(self, *args, **kwargs):
         super().__init__(*args, **kwargs)
     def forward(self, x, pos=None, mask=None, **mod_kwargs):
         for layer in self.layers:
             x = layer(x, pos=pos, mask=mask, causal=True, **mod_kwargs)
-        return x
+        return x
+
+
+class Aggregator(nn.Module):
+    def __init__(self, method = "max"):
+        super().__init__()
+        assert method in ["mean", "max", "cls"]
+        self.method = method
+
+    def forward(self, x, mask = None):
+        """
+        X = B, *, L, H
+        mask = B, *, L
+        """
+        if mask is not None:
+            x = x * mask.unsqueeze(-1)
+        if self.method == "mean":
+            return x.sum(-2) / (mask.sum(-1, keepdim=True) if mask is not None else x.shape[-2])
+        elif self.method == "max":
+            return x.max(-2).values
+        elif self.method == "cls":
+            return x[..., 0, :]
```

### Comparing `bio-attention-0.0.6/bio_attention/embed.py` & `bio-attention-0.0.7/bio_attention/embed.py`

 * *Files 2% similar despite different names*

```diff
@@ -7,16 +7,18 @@
         self,
         num_embeddings,
         embedding_dim,
         cls=False,
         cls_axis=-2,
         init_cls_as_mask=False,
     ):
-        """Embedding module for discrete data. Uses `nn.Embedding` with added support for masking tokens cls tokens.
+        """Embedding module for discrete data. Uses `nn.Embedding` with added support for masking tokens and cls tokens.
         Masking tokens are recognized as torch.nans. Therefore, input should be float dtype.
+        WARNING: Because this module expects a float dtype for what should be integers, there is a limit to the vocab size you can effectively accurately represent.
+        In practice, vocab sizes up to 1 million in size should be faithfully represented with float32. For float16, expect issues.
 
         Args:
             num_embeddings (int): number of discrete classes.
             embedding_dim (int): number of hidden dimensions of the embeddings
             cls (bool, optional): whether to include cls token. Defaults to True.
             cls_axis (int, optional): which axis in the input to add cls token to. Defaults to -1.
             init_cls_as_mask (bool, optional): initialize the cls token to be equal to the masking token. Defaults to False.
```

### Comparing `bio-attention-0.0.6/bio_attention/img/2Dslidingwindow-attention.png` & `bio-attention-0.0.7/bio_attention/img/2Dslidingwindow-attention.png`

 * *Files identical despite different names*

### Comparing `bio-attention-0.0.6/bio_attention/img/windowed_implementation.svg` & `bio-attention-0.0.7/bio_attention/img/windowed_implementation.svg`

 * *Files identical despite different names*

### Comparing `bio-attention-0.0.6/bio_attention/positional.py` & `bio-attention-0.0.7/bio_attention/positional.py`

 * *Files 0% similar despite different names*

```diff
@@ -542,15 +542,15 @@
             self.embed_lin(pos_emb),
             "... (nh h) -> ... nh h",
             nh=self.n_heads,
             h=q.shape[-1],
         )
 
         l1, l2 = q.shape[-3], k.shape[-3]
-        r_l1, r_l2 = r.shape[-2], r.shape[-1]
+        r_l1, r_l2 = r.shape[-4], r.shape[-3]
         if (l1 != r_l1) or (l2 != r_l2):
             r = F.pad(r, (0, 0, 0, 0, l2-r_l2, 0, l1-r_l1, 0))
 
         q_r = q + self.bias_r_w
         BD = einsum(q_r, r, "... q n h, ... q k n h -> ... n q k")
         return (0 if mask is None else mask) + BD
```

### Comparing `bio-attention-0.0.6/bio_attention.egg-info/PKG-INFO` & `bio-attention-0.0.7/bio_attention.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: bio-attention
-Version: 0.0.6
+Version: 0.0.7
 Summary: Simple implementations of attention modules adapted for the biological data domain
 Home-page: https://github.com/gdewael/bio-attention
 Author: Gaetan De Waele
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
```

