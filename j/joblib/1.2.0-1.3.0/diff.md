# Comparing `tmp/joblib-1.2.0.tar.gz` & `tmp/joblib-1.3.0-py3-none-any.whl.zip`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "joblib-1.2.0.tar", last modified: Fri Sep 16 09:59:29 2022, max compression
+Zip archive data, at least v2.0 to extract, compression method=deflate
```

## filetype from diffoscope

```diff
@@ -1 +1 @@
-GzipFile
+ZipFile
```

