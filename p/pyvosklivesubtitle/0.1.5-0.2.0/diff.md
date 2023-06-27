# Comparing `tmp/pyvosklivesubtitle-0.1.5.tar.gz` & `tmp/pyvosklivesubtitle-0.2.0-cp38-cp38-manylinux_2_17_x86_64.whl.zip`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyvosklivesubtitle-0.1.5.tar", last modified: Thu Apr 27 13:24:16 2023, max compression
+Zip archive data, at least v2.0 to extract, compression method=deflate
```

## filetype from diffoscope

```diff
@@ -1 +1 @@
-GzipFile
+ZipFile
```

