# Comparing `tmp/json-lineage-0.1.0.tar.gz` & `tmp/json_lineage-0.2.0-py3-none-any.whl.zip`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "json-lineage-0.1.0.tar", last modified: Sun Jun 25 16:23:48 2023, max compression
+Zip archive data, at least v2.0 to extract, compression method=deflate
```

## filetype from diffoscope

```diff
@@ -1 +1 @@
-GzipFile
+ZipFile
```

