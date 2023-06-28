# Comparing `tmp/hack_pc_to_LV_1-0.0.1.tar.gz` & `tmp/hack_pc_to_LV_1-0.0.3-py3-none-any.whl.zip`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "hack_pc_to_LV_1-0.0.1.tar", last modified: Wed Jun 28 05:36:35 2023, max compression
+Zip archive data, at least v2.0 to extract, compression method=deflate
```

## filetype from diffoscope

```diff
@@ -1 +1 @@
-GzipFile
+ZipFile
```

