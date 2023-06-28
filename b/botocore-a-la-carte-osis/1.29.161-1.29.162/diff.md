# Comparing `tmp/botocore-a-la-carte-osis-1.29.161.tar.gz` & `tmp/botocore_a_la_carte_osis-1.29.162-py3-none-any.whl.zip`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "botocore-a-la-carte-osis-1.29.161.tar", last modified: Tue Jun 27 01:45:07 2023, max compression
+Zip archive data, at least v2.0 to extract, compression method=deflate
```

## filetype from diffoscope

```diff
@@ -1 +1 @@
-GzipFile
+ZipFile
```

