# Comparing `tmp/xtor-0.1.0.tar.gz` & `tmp/xtor-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "xtor-0.1.0.tar", max compression
+gzip compressed data, was "xtor-0.1.1.tar", max compression
```

## Comparing `xtor-0.1.0.tar` & `xtor-0.1.1.tar`

### file list

```diff
@@ -1,4 +1,5 @@
--rw-r--r--   0        0        0       88 2023-06-27 08:43:25.527391 xtor-0.1.0/README.md
--rw-r--r--   0        0        0      288 2023-06-27 08:47:49.815087 xtor-0.1.0/pyproject.toml
--rw-r--r--   0        0        0       22 2023-06-27 08:42:27.339394 xtor-0.1.0/xtor/__init__.py
--rw-r--r--   0        0        0      596 1970-01-01 00:00:00.000000 xtor-0.1.0/PKG-INFO
+-rw-r--r--   0        0        0      676 2023-06-27 09:35:27.671062 xtor-0.1.1/README.md
+-rw-r--r--   0        0        0      548 2023-06-28 12:53:41.352182 xtor-0.1.1/pyproject.toml
+-rw-r--r--   0        0        0     1454 2023-06-28 12:52:37.944213 xtor-0.1.1/xtor/__init__.py
+-rw-r--r--   0        0        0     1841 2023-06-28 12:47:37.924474 xtor-0.1.1/xtor/utils.py
+-rw-r--r--   0        0        0     1517 1970-01-01 00:00:00.000000 xtor-0.1.1/PKG-INFO
```

