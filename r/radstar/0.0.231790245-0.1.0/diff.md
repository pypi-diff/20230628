# Comparing `tmp/radstar-0.0.231790245.tar.gz` & `tmp/radstar-0.1.0-py3-none-any.whl.zip`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "radstar-0.0.231790245.tar", last modified: Wed Jun 28 02:45:51 2023, max compression
+Zip archive data, at least v2.0 to extract, compression method=deflate
```

## filetype from diffoscope

```diff
@@ -1 +1 @@
-GzipFile
+ZipFile
```

