# Comparing `tmp/qlytix_package-2.0.tar.gz` & `tmp/qlytix_package-3.0-py3-none-any.whl.zip`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "qlytix_package-2.0.tar", last modified: Wed Jun 28 11:41:29 2023, max compression
+Zip archive data, at least v2.0 to extract, compression method=deflate
```

## filetype from diffoscope

```diff
@@ -1 +1 @@
-GzipFile
+ZipFile
```

