# Comparing `tmp/etu-fastapi-frame-1.3.0.tar.gz` & `tmp/etu_fastapi_frame-1.3.1-py3-none-any.whl.zip`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "etu-fastapi-frame-1.3.0.tar", last modified: Wed Jun 28 03:38:47 2023, max compression
+Zip archive data, at least v2.0 to extract, compression method=deflate
```

## filetype from diffoscope

```diff
@@ -1 +1 @@
-GzipFile
+ZipFile
```

