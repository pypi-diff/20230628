# Comparing `tmp/plone.formwidget.geolocation-3.0.4.tar.gz` & `tmp/plone.formwidget.geolocation-3.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "plone.formwidget.geolocation-3.0.4.tar", last modified: Fri Jun  2 10:01:34 2023, max compression
+gzip compressed data, was "plone.formwidget.geolocation-3.0.5.tar", last modified: Wed Jun 28 13:06:01 2023, max compression
```

## Comparing `plone.formwidget.geolocation-3.0.4.tar` & `plone.formwidget.geolocation-3.0.5.tar`

### file list

```diff
@@ -1,158 +1,160 @@
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.473252 plone.formwidget.geolocation-3.0.4/
--rw-r--r--   0 peterm     (501) staff       (20)       67 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/.coveragerc
--rw-r--r--   0 peterm     (501) staff       (20)     1229 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/.editorconfig
--rw-r--r--   0 peterm     (501) staff       (20)      410 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/.flake8
--rw-r--r--   0 peterm     (501) staff       (20)      655 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/.gitignore
--rw-r--r--   0 peterm     (501) staff       (20)     1596 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/.pre-commit-config.yaml
--rw-r--r--   0 peterm     (501) staff       (20)     4726 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/CHANGES.rst
--rw-r--r--   0 peterm     (501) staff       (20)      130 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/MANIFEST.in
--rw-r--r--   0 peterm     (501) staff       (20)    11677 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/Makefile
--rw-r--r--   0 peterm     (501) staff       (20)     7053 2023-06-02 10:01:34.473316 plone.formwidget.geolocation-3.0.4/PKG-INFO
--rw-r--r--   0 peterm     (501) staff       (20)     1524 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/README.rst
--rw-r--r--   0 peterm     (501) staff       (20)       58 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/constraints.txt
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.453365 plone.formwidget.geolocation-3.0.4/docs/
--rw-r--r--   0 peterm     (501) staff       (20)     1376 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/docs/INSTALL.txt
--rw-r--r--   0 peterm     (501) staff       (20)    17987 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/docs/LICENSE.GPL
--rw-r--r--   0 peterm     (501) staff       (20)      744 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/docs/LICENSE.txt
--rw-r--r--   0 peterm     (501) staff       (20)      424 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/instance.yaml
--rw-r--r--   0 peterm     (501) staff       (20)      601 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/mx.ini
--rw-r--r--   0 peterm     (501) staff       (20)      848 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/package.json
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.453510 plone.formwidget.geolocation-3.0.4/plone/
--rw-r--r--   0 peterm     (501) staff       (20)       56 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/__init__.py
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.454801 plone.formwidget.geolocation-3.0.4/plone/formwidget/
--rw-r--r--   0 peterm     (501) staff       (20)       56 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/__init__.py
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.458013 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/
--rw-r--r--   0 peterm     (501) staff       (20)      293 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/__init__.py
--rw-r--r--   0 peterm     (501) staff       (20)     3096 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/configure.zcml
--rw-r--r--   0 peterm     (501) staff       (20)      543 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/controlpanel.py
--rw-r--r--   0 peterm     (501) staff       (20)      935 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/converter.py
--rw-r--r--   0 peterm     (501) staff       (20)      937 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/deserializer.py
--rw-r--r--   0 peterm     (501) staff       (20)      468 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/field.py
--rw-r--r--   0 peterm     (501) staff       (20)      464 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/geolocation.py
--rw-r--r--   0 peterm     (501) staff       (20)      757 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/geolocation_display.pt
--rw-r--r--   0 peterm     (501) staff       (20)     1471 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/geolocation_input.pt
--rw-r--r--   0 peterm     (501) staff       (20)     3980 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/interfaces.py
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.458309 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.449446 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/de/
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.458461 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/de/LC_MESSAGES/
--rw-r--r--   0 peterm     (501) staff       (20)     6517 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/de/LC_MESSAGES/plone.formwidget.geolocation.po
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.449577 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/fr/
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.458627 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/fr/LC_MESSAGES/
--rw-r--r--   0 peterm     (501) staff       (20)     7894 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/fr/LC_MESSAGES/plone.formwidget.geolocation.po
--rw-r--r--   0 peterm     (501) staff       (20)     6533 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/plone.formwidget.geolocation.pot
--rwxr-xr-x   0 peterm     (501) staff       (20)      523 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/update.sh
--rw-r--r--   0 peterm     (501) staff       (20)      225 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/popup.pt
--rw-r--r--   0 peterm     (501) staff       (20)      595 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/popup.py
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.449853 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.459077 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/default/
--rw-r--r--   0 peterm     (501) staff       (20)      699 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/default/controlpanel.xml
--rw-r--r--   0 peterm     (501) staff       (20)      107 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/default/metadata.xml
--rw-r--r--   0 peterm     (501) staff       (20)      614 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/default/registry.xml
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.459241 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/uninstall/
--rw-r--r--   0 peterm     (501) staff       (20)      208 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/uninstall/registry.xml
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.449908 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/upgrades/
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.459384 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/upgrades/to_2000/
--rw-r--r--   0 peterm     (501) staff       (20)      209 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/upgrades/to_2000/registry.xml
--rw-r--r--   0 peterm     (501) staff       (20)      834 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/serializer.py
--rw-r--r--   0 peterm     (501) staff       (20)      399 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/setuphandlers.py
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.465488 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/
--rw-r--r--   0 peterm     (501) staff       (20)      535 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/151b708954e10ff9b542.png
--rw-r--r--   0 peterm     (501) staff       (20)    78268 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/1551f4f60c37af51121f.woff2
--rw-r--r--   0 peterm     (501) staff       (20)   165517 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/1f2cc17911c8d4a3fa01.png
--rw-r--r--   0 peterm     (501) staff       (20)    89988 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/2285773e6b4b172f07d9.woff
--rw-r--r--   0 peterm     (501) staff       (20)   134294 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/23f19bb08961f37aaf69.eot
--rw-r--r--   0 peterm     (501) staff       (20)     1466 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/2b3e1faf89f94a483539.png
--rw-r--r--   0 peterm     (501) staff       (20)   747927 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/2f517e09eb2ca6650ff5.svg
--rw-r--r--   0 peterm     (501) staff       (20)      696 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/416d91365b44e4b4f477.png
--rw-r--r--   0 peterm     (501) staff       (20)   144714 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/4689f52cc96215721344.svg
--rw-r--r--   0 peterm     (501) staff       (20)    33736 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/491974d108fe4002b2aa.ttf
--rw-r--r--   0 peterm     (501) staff       (20)     1765 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/4cb77f5b444ed35e8e2e.svg
--rw-r--r--   0 peterm     (501) staff       (20)   133988 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/527940b104eb2ea366c8.ttf
--rw-r--r--   0 peterm     (501) staff       (20)    34034 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/77206a6bb316fa0aded5.eot
--rw-r--r--   0 peterm     (501) staff       (20)    13224 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/7a3337626410ca2f4071.woff2
--rw-r--r--   0 peterm     (501) staff       (20)   918991 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/7a8b4f130182d19a2d7c.svg
--rw-r--r--   0 peterm     (501) staff       (20)      219 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/7c18af1f4c99e9740a67.png
--rw-r--r--   0 peterm     (501) staff       (20)      491 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/88d12380a9385aca0b5e.png
--rw-r--r--   0 peterm     (501) staff       (20)     1259 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/8f2c4d11474275fbc161.png
--rw-r--r--   0 peterm     (501) staff       (20)   203030 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/9bbb245e67a133f6e486.eot
--rw-r--r--   0 peterm     (501) staff       (20)      945 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/a8f4a7de091d4a05f2de.svg
--rw-r--r--   0 peterm     (501) staff       (20)    16276 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/bb58e57c48a3e911f15f.woff
--rw-r--r--   0 peterm     (501) staff       (20)   202744 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/be9ee23c0c6390141475.ttf
--rw-r--r--   0 peterm     (501) staff       (20)     7185 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/bundle-remote.min.js
--rw-r--r--   0 peterm     (501) staff       (20)    36986 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/bundle-remote.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)     6672 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/bundle.min.js
--rw-r--r--   0 peterm     (501) staff       (20)    35308 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/bundle.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)      678 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/ca179ed3d0daf2238700.png
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.471384 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/
--rw-r--r--   0 peterm     (501) staff       (20)    31477 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/209.003c259079020170dead.min.js
--rw-r--r--   0 peterm     (501) staff       (20)   148754 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/209.003c259079020170dead.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)    25921 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/225.b61fcef1ea1cd5d168fd.min.js
--rw-r--r--   0 peterm     (501) staff       (20)    58438 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/225.b61fcef1ea1cd5d168fd.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)   149357 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/243.520ed689ac00fad2760b.min.js
--rw-r--r--   0 peterm     (501) staff       (20)   700679 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/243.520ed689ac00fad2760b.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)     7903 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/244.99e821275a9a8cd8a002.min.js
--rw-r--r--   0 peterm     (501) staff       (20)    17416 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/244.99e821275a9a8cd8a002.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)   229578 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/345.9472bed909073f23fc24.min.js
--rw-r--r--   0 peterm     (501) staff       (20)   282685 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/345.9472bed909073f23fc24.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)     1770 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/408.3b6d07fc9bfe7d5ff5f6.min.js
--rw-r--r--   0 peterm     (501) staff       (20)     6499 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/408.3b6d07fc9bfe7d5ff5f6.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)      239 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/41.cc781ee643f4dd99a76f.min.js
--rw-r--r--   0 peterm     (501) staff       (20)      278 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/41.cc781ee643f4dd99a76f.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)      238 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/608.62567ffe5c5bb8ed8b53.min.js
--rw-r--r--   0 peterm     (501) staff       (20)      453 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/608.62567ffe5c5bb8ed8b53.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)     4606 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/632.479ae0ac97903a1a34f2.min.js
--rw-r--r--   0 peterm     (501) staff       (20)    12176 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/632.479ae0ac97903a1a34f2.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)    12998 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/687.92e0c5f9be34801669a1.min.js
--rw-r--r--   0 peterm     (501) staff       (20)    46660 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/687.92e0c5f9be34801669a1.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)     1297 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/710.2ad7d1d2c95de800580a.min.js
--rw-r--r--   0 peterm     (501) staff       (20)    34123 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/732.b3d36ecac26cd86168a1.min.js
--rw-r--r--   0 peterm     (501) staff       (20)   134768 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/732.b3d36ecac26cd86168a1.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)    87365 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/755.e7e5bacd7254c4286594.min.js
--rw-r--r--   0 peterm     (501) staff       (20)   460205 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/755.e7e5bacd7254c4286594.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)     2549 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/848.b3cd765166bf08cfebcd.min.js
--rw-r--r--   0 peterm     (501) staff       (20)     7221 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/848.b3cd765166bf08cfebcd.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)     5839 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/929.8e6f969165fb95e4f6a3.min.js
--rw-r--r--   0 peterm     (501) staff       (20)    17118 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/929.8e6f969165fb95e4f6a3.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)    23445 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/978.21a03d5107c83ad21c78.min.js
--rw-r--r--   0 peterm     (501) staff       (20)    51691 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/978.21a03d5107c83ad21c78.min.js.map
--rw-r--r--   0 peterm     (501) staff       (20)    76736 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/d878b0a6a1144760244f.woff2
--rw-r--r--   0 peterm     (501) staff       (20)     1469 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/dfc8c849388499bd892c.png
--rw-r--r--   0 peterm     (501) staff       (20)    56965 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/e52214306ad12a5c837e.png
--rw-r--r--   0 peterm     (501) staff       (20)   101648 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/eeccf4f66002c6f2ba24.woff
--rw-r--r--   0 peterm     (501) staff       (20)      216 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/supermodel.py
--rw-r--r--   0 peterm     (501) staff       (20)     1058 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/testing.py
--rw-r--r--   0 peterm     (501) staff       (20)      152 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/testing.zcml
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.472875 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/
--rw-r--r--   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/__init__.py
--rw-r--r--   0 peterm     (501) staff       (20)     1909 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_converter.py
--rw-r--r--   0 peterm     (501) staff       (20)     1430 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_deserializer.py
--rw-r--r--   0 peterm     (501) staff       (20)      601 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_geolocation.py
--rw-r--r--   0 peterm     (501) staff       (20)      264 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_popup.pt
--rw-r--r--   0 peterm     (501) staff       (20)     1386 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_serializer.py
--rw-r--r--   0 peterm     (501) staff       (20)     1246 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_setup.py
--rw-r--r--   0 peterm     (501) staff       (20)      962 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_supermodel.py
--rw-r--r--   0 peterm     (501) staff       (20)      602 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_vocabularies.py
--rw-r--r--   0 peterm     (501) staff       (20)     6844 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_widget.py
--rw-r--r--   0 peterm     (501) staff       (20)      366 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/utils.py
--rw-r--r--   0 peterm     (501) staff       (20)     2622 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/upgrades.py
--rw-r--r--   0 peterm     (501) staff       (20)     1996 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/upgrades.zcml
--rw-r--r--   0 peterm     (501) staff       (20)     4343 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/vocabularies.py
--rw-r--r--   0 peterm     (501) staff       (20)     5059 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/widget.py
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.454663 plone.formwidget.geolocation-3.0.4/plone.formwidget.geolocation.egg-info/
--rw-r--r--   0 peterm     (501) staff       (20)     7053 2023-06-02 10:01:34.000000 plone.formwidget.geolocation-3.0.4/plone.formwidget.geolocation.egg-info/PKG-INFO
--rw-r--r--   0 peterm     (501) staff       (20)     7122 2023-06-02 10:01:34.000000 plone.formwidget.geolocation-3.0.4/plone.formwidget.geolocation.egg-info/SOURCES.txt
--rw-r--r--   0 peterm     (501) staff       (20)        1 2023-06-02 10:01:34.000000 plone.formwidget.geolocation-3.0.4/plone.formwidget.geolocation.egg-info/dependency_links.txt
--rw-r--r--   0 peterm     (501) staff       (20)       40 2023-06-02 10:01:34.000000 plone.formwidget.geolocation-3.0.4/plone.formwidget.geolocation.egg-info/entry_points.txt
--rw-r--r--   0 peterm     (501) staff       (20)       23 2023-06-02 10:01:34.000000 plone.formwidget.geolocation-3.0.4/plone.formwidget.geolocation.egg-info/namespace_packages.txt
--rw-r--r--   0 peterm     (501) staff       (20)        1 2023-06-02 10:01:34.000000 plone.formwidget.geolocation-3.0.4/plone.formwidget.geolocation.egg-info/not-zip-safe
--rw-r--r--   0 peterm     (501) staff       (20)      104 2023-06-02 10:01:34.000000 plone.formwidget.geolocation-3.0.4/plone.formwidget.geolocation.egg-info/requires.txt
--rw-r--r--   0 peterm     (501) staff       (20)        6 2023-06-02 10:01:34.000000 plone.formwidget.geolocation-3.0.4/plone.formwidget.geolocation.egg-info/top_level.txt
--rw-r--r--   0 peterm     (501) staff       (20)      123 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/requirements.txt
-drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-02 10:01:34.473129 plone.formwidget.geolocation-3.0.4/resources/
--rw-r--r--   0 peterm     (501) staff       (20)      204 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/resources/config.js
--rw-r--r--   0 peterm     (501) staff       (20)       69 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/resources/index.js
--rw-r--r--   0 peterm     (501) staff       (20)      143 2023-06-02 10:01:34.473533 plone.formwidget.geolocation-3.0.4/setup.cfg
--rw-r--r--   0 peterm     (501) staff       (20)     1677 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/setup.py
--rw-r--r--   0 peterm     (501) staff       (20)     3804 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/tox.ini
--rw-r--r--   0 peterm     (501) staff       (20)     1367 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/webpack.config.js
--rw-r--r--   0 peterm     (501) staff       (20)   442322 2023-06-02 10:01:33.000000 plone.formwidget.geolocation-3.0.4/yarn.lock
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.905281 plone.formwidget.geolocation-3.0.5/
+-rw-r--r--   0 peterm     (501) staff       (20)       67 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/.coveragerc
+-rw-r--r--   0 peterm     (501) staff       (20)     1229 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/.editorconfig
+-rw-r--r--   0 peterm     (501) staff       (20)      410 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/.flake8
+-rw-r--r--   0 peterm     (501) staff       (20)      655 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/.gitignore
+-rw-r--r--   0 peterm     (501) staff       (20)     1598 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/.pre-commit-config.yaml
+-rw-r--r--   0 peterm     (501) staff       (20)     4953 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/CHANGES.rst
+-rw-r--r--   0 peterm     (501) staff       (20)      130 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/MANIFEST.in
+-rw-r--r--   0 peterm     (501) staff       (20)    11677 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/Makefile
+-rw-r--r--   0 peterm     (501) staff       (20)     7280 2023-06-28 13:06:01.905366 plone.formwidget.geolocation-3.0.5/PKG-INFO
+-rw-r--r--   0 peterm     (501) staff       (20)     1524 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/README.rst
+-rw-r--r--   0 peterm     (501) staff       (20)       58 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/constraints.txt
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.887967 plone.formwidget.geolocation-3.0.5/docs/
+-rw-r--r--   0 peterm     (501) staff       (20)     1376 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/docs/INSTALL.txt
+-rw-r--r--   0 peterm     (501) staff       (20)    17987 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/docs/LICENSE.GPL
+-rw-r--r--   0 peterm     (501) staff       (20)      744 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/docs/LICENSE.txt
+-rw-r--r--   0 peterm     (501) staff       (20)      424 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/instance.yaml
+-rw-r--r--   0 peterm     (501) staff       (20)      601 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/mx.ini
+-rw-r--r--   0 peterm     (501) staff       (20)      848 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/package.json
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.888082 plone.formwidget.geolocation-3.0.5/plone/
+-rw-r--r--   0 peterm     (501) staff       (20)       56 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/__init__.py
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.889133 plone.formwidget.geolocation-3.0.5/plone/formwidget/
+-rw-r--r--   0 peterm     (501) staff       (20)       56 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/__init__.py
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.891685 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/
+-rw-r--r--   0 peterm     (501) staff       (20)      293 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/__init__.py
+-rw-r--r--   0 peterm     (501) staff       (20)     3096 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/configure.zcml
+-rw-r--r--   0 peterm     (501) staff       (20)      543 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/controlpanel.py
+-rw-r--r--   0 peterm     (501) staff       (20)      935 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/converter.py
+-rw-r--r--   0 peterm     (501) staff       (20)      937 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/deserializer.py
+-rw-r--r--   0 peterm     (501) staff       (20)      468 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/field.py
+-rw-r--r--   0 peterm     (501) staff       (20)      464 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/geolocation.py
+-rw-r--r--   0 peterm     (501) staff       (20)      757 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/geolocation_display.pt
+-rw-r--r--   0 peterm     (501) staff       (20)     1471 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/geolocation_input.pt
+-rw-r--r--   0 peterm     (501) staff       (20)     3980 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/interfaces.py
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.891928 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.884402 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/de/
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.892178 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/de/LC_MESSAGES/
+-rw-r--r--   0 peterm     (501) staff       (20)      480 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/de/LC_MESSAGES/plone.formwidget.geolocation.mo
+-rw-r--r--   0 peterm     (501) staff       (20)     6517 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/de/LC_MESSAGES/plone.formwidget.geolocation.po
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.884524 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/fr/
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.892433 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/fr/LC_MESSAGES/
+-rw-r--r--   0 peterm     (501) staff       (20)     3161 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/fr/LC_MESSAGES/plone.formwidget.geolocation.mo
+-rw-r--r--   0 peterm     (501) staff       (20)     7894 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/fr/LC_MESSAGES/plone.formwidget.geolocation.po
+-rw-r--r--   0 peterm     (501) staff       (20)     6533 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/plone.formwidget.geolocation.pot
+-rwxr-xr-x   0 peterm     (501) staff       (20)      523 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/update.sh
+-rw-r--r--   0 peterm     (501) staff       (20)      225 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/popup.pt
+-rw-r--r--   0 peterm     (501) staff       (20)      595 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/popup.py
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.884785 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.892796 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/default/
+-rw-r--r--   0 peterm     (501) staff       (20)      680 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/default/controlpanel.xml
+-rw-r--r--   0 peterm     (501) staff       (20)      107 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/default/metadata.xml
+-rw-r--r--   0 peterm     (501) staff       (20)      614 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/default/registry.xml
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.892914 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/uninstall/
+-rw-r--r--   0 peterm     (501) staff       (20)      208 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/uninstall/registry.xml
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.884835 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/upgrades/
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.893040 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/upgrades/to_2000/
+-rw-r--r--   0 peterm     (501) staff       (20)      209 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/upgrades/to_2000/registry.xml
+-rw-r--r--   0 peterm     (501) staff       (20)      834 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/serializer.py
+-rw-r--r--   0 peterm     (501) staff       (20)      399 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/setuphandlers.py
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.898316 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/
+-rw-r--r--   0 peterm     (501) staff       (20)      535 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/151b708954e10ff9b542.png
+-rw-r--r--   0 peterm     (501) staff       (20)    78268 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/1551f4f60c37af51121f.woff2
+-rw-r--r--   0 peterm     (501) staff       (20)   165517 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/1f2cc17911c8d4a3fa01.png
+-rw-r--r--   0 peterm     (501) staff       (20)    89988 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/2285773e6b4b172f07d9.woff
+-rw-r--r--   0 peterm     (501) staff       (20)   134294 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/23f19bb08961f37aaf69.eot
+-rw-r--r--   0 peterm     (501) staff       (20)     1466 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/2b3e1faf89f94a483539.png
+-rw-r--r--   0 peterm     (501) staff       (20)   747927 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/2f517e09eb2ca6650ff5.svg
+-rw-r--r--   0 peterm     (501) staff       (20)      696 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/416d91365b44e4b4f477.png
+-rw-r--r--   0 peterm     (501) staff       (20)   144714 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/4689f52cc96215721344.svg
+-rw-r--r--   0 peterm     (501) staff       (20)    33736 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/491974d108fe4002b2aa.ttf
+-rw-r--r--   0 peterm     (501) staff       (20)     1765 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/4cb77f5b444ed35e8e2e.svg
+-rw-r--r--   0 peterm     (501) staff       (20)   133988 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/527940b104eb2ea366c8.ttf
+-rw-r--r--   0 peterm     (501) staff       (20)    34034 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/77206a6bb316fa0aded5.eot
+-rw-r--r--   0 peterm     (501) staff       (20)    13224 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/7a3337626410ca2f4071.woff2
+-rw-r--r--   0 peterm     (501) staff       (20)   918991 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/7a8b4f130182d19a2d7c.svg
+-rw-r--r--   0 peterm     (501) staff       (20)      219 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/7c18af1f4c99e9740a67.png
+-rw-r--r--   0 peterm     (501) staff       (20)      491 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/88d12380a9385aca0b5e.png
+-rw-r--r--   0 peterm     (501) staff       (20)     1259 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/8f2c4d11474275fbc161.png
+-rw-r--r--   0 peterm     (501) staff       (20)   203030 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/9bbb245e67a133f6e486.eot
+-rw-r--r--   0 peterm     (501) staff       (20)      945 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/a8f4a7de091d4a05f2de.svg
+-rw-r--r--   0 peterm     (501) staff       (20)    16276 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/bb58e57c48a3e911f15f.woff
+-rw-r--r--   0 peterm     (501) staff       (20)   202744 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/be9ee23c0c6390141475.ttf
+-rw-r--r--   0 peterm     (501) staff       (20)     7185 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/bundle-remote.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)    36986 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/bundle-remote.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)     6672 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/bundle.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)    35308 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/bundle.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)      678 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/ca179ed3d0daf2238700.png
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.903652 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/
+-rw-r--r--   0 peterm     (501) staff       (20)    31477 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/209.003c259079020170dead.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)   148754 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/209.003c259079020170dead.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)    25921 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/225.b61fcef1ea1cd5d168fd.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)    58438 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/225.b61fcef1ea1cd5d168fd.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)   149357 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/243.520ed689ac00fad2760b.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)   700679 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/243.520ed689ac00fad2760b.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)     7903 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/244.99e821275a9a8cd8a002.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)    17416 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/244.99e821275a9a8cd8a002.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)   229578 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/345.9472bed909073f23fc24.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)   282685 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/345.9472bed909073f23fc24.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)     1770 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/408.3b6d07fc9bfe7d5ff5f6.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)     6499 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/408.3b6d07fc9bfe7d5ff5f6.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)      239 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/41.cc781ee643f4dd99a76f.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)      278 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/41.cc781ee643f4dd99a76f.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)      238 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/608.62567ffe5c5bb8ed8b53.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)      453 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/608.62567ffe5c5bb8ed8b53.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)     4606 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/632.479ae0ac97903a1a34f2.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)    12176 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/632.479ae0ac97903a1a34f2.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)    12998 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/687.92e0c5f9be34801669a1.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)    46660 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/687.92e0c5f9be34801669a1.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)     1297 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/710.2ad7d1d2c95de800580a.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)    34123 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/732.b3d36ecac26cd86168a1.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)   134768 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/732.b3d36ecac26cd86168a1.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)    87365 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/755.e7e5bacd7254c4286594.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)   460205 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/755.e7e5bacd7254c4286594.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)     2549 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/848.b3cd765166bf08cfebcd.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)     7221 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/848.b3cd765166bf08cfebcd.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)     5839 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/929.8e6f969165fb95e4f6a3.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)    17118 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/929.8e6f969165fb95e4f6a3.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)    23445 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/978.21a03d5107c83ad21c78.min.js
+-rw-r--r--   0 peterm     (501) staff       (20)    51691 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/978.21a03d5107c83ad21c78.min.js.map
+-rw-r--r--   0 peterm     (501) staff       (20)    76736 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/d878b0a6a1144760244f.woff2
+-rw-r--r--   0 peterm     (501) staff       (20)     1469 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/dfc8c849388499bd892c.png
+-rw-r--r--   0 peterm     (501) staff       (20)    56965 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/e52214306ad12a5c837e.png
+-rw-r--r--   0 peterm     (501) staff       (20)   101648 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/eeccf4f66002c6f2ba24.woff
+-rw-r--r--   0 peterm     (501) staff       (20)      216 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/supermodel.py
+-rw-r--r--   0 peterm     (501) staff       (20)     1058 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/testing.py
+-rw-r--r--   0 peterm     (501) staff       (20)      152 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/testing.zcml
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.904932 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/
+-rw-r--r--   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/__init__.py
+-rw-r--r--   0 peterm     (501) staff       (20)     1909 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_converter.py
+-rw-r--r--   0 peterm     (501) staff       (20)     1430 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_deserializer.py
+-rw-r--r--   0 peterm     (501) staff       (20)      601 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_geolocation.py
+-rw-r--r--   0 peterm     (501) staff       (20)      264 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_popup.pt
+-rw-r--r--   0 peterm     (501) staff       (20)     1386 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_serializer.py
+-rw-r--r--   0 peterm     (501) staff       (20)     1246 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_setup.py
+-rw-r--r--   0 peterm     (501) staff       (20)      962 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_supermodel.py
+-rw-r--r--   0 peterm     (501) staff       (20)      602 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_vocabularies.py
+-rw-r--r--   0 peterm     (501) staff       (20)     6937 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_widget.py
+-rw-r--r--   0 peterm     (501) staff       (20)      366 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/utils.py
+-rw-r--r--   0 peterm     (501) staff       (20)     2622 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/upgrades.py
+-rw-r--r--   0 peterm     (501) staff       (20)     2226 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/upgrades.zcml
+-rw-r--r--   0 peterm     (501) staff       (20)     4343 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/vocabularies.py
+-rw-r--r--   0 peterm     (501) staff       (20)     4872 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/widget.py
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.889014 plone.formwidget.geolocation-3.0.5/plone.formwidget.geolocation.egg-info/
+-rw-r--r--   0 peterm     (501) staff       (20)     7280 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone.formwidget.geolocation.egg-info/PKG-INFO
+-rw-r--r--   0 peterm     (501) staff       (20)     7290 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone.formwidget.geolocation.egg-info/SOURCES.txt
+-rw-r--r--   0 peterm     (501) staff       (20)        1 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone.formwidget.geolocation.egg-info/dependency_links.txt
+-rw-r--r--   0 peterm     (501) staff       (20)       40 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone.formwidget.geolocation.egg-info/entry_points.txt
+-rw-r--r--   0 peterm     (501) staff       (20)       23 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone.formwidget.geolocation.egg-info/namespace_packages.txt
+-rw-r--r--   0 peterm     (501) staff       (20)        1 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone.formwidget.geolocation.egg-info/not-zip-safe
+-rw-r--r--   0 peterm     (501) staff       (20)      104 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone.formwidget.geolocation.egg-info/requires.txt
+-rw-r--r--   0 peterm     (501) staff       (20)        6 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/plone.formwidget.geolocation.egg-info/top_level.txt
+-rw-r--r--   0 peterm     (501) staff       (20)      123 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/requirements.txt
+drwxr-xr-x   0 peterm     (501) staff       (20)        0 2023-06-28 13:06:01.905162 plone.formwidget.geolocation-3.0.5/resources/
+-rw-r--r--   0 peterm     (501) staff       (20)      204 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/resources/config.js
+-rw-r--r--   0 peterm     (501) staff       (20)       69 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/resources/index.js
+-rw-r--r--   0 peterm     (501) staff       (20)      143 2023-06-28 13:06:01.905585 plone.formwidget.geolocation-3.0.5/setup.cfg
+-rw-r--r--   0 peterm     (501) staff       (20)     1677 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/setup.py
+-rw-r--r--   0 peterm     (501) staff       (20)     3804 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/tox.ini
+-rw-r--r--   0 peterm     (501) staff       (20)     1367 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/webpack.config.js
+-rw-r--r--   0 peterm     (501) staff       (20)   442322 2023-06-28 13:06:01.000000 plone.formwidget.geolocation-3.0.5/yarn.lock
```

### Comparing `plone.formwidget.geolocation-3.0.4/.editorconfig` & `plone.formwidget.geolocation-3.0.5/.editorconfig`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/.gitignore` & `plone.formwidget.geolocation-3.0.5/.gitignore`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/.pre-commit-config.yaml` & `plone.formwidget.geolocation-3.0.5/.pre-commit-config.yaml`

 * *Files 4% similar despite different names*

```diff
@@ -3,28 +3,28 @@
 # See the inline comments on how to expand/tweak this configuration file
 ci:
     autofix_prs: false
     autoupdate_schedule: monthly
 
 repos:
 -   repo: https://github.com/asottile/pyupgrade
-    rev: v3.3.2
+    rev: v3.4.0
     hooks:
     -   id: pyupgrade
         args: [--py38-plus]
 -   repo: https://github.com/pycqa/isort
     rev: 5.12.0
     hooks:
     -   id: isort
 -   repo: https://github.com/psf/black
     rev: 23.3.0
     hooks:
     -   id: black
 -   repo: https://github.com/collective/zpretty
-    rev: 3.0.4
+    rev: 3.1.0a2
     hooks:
     -   id: zpretty
 -   repo: https://github.com/PyCQA/flake8
     rev: 6.0.0
     hooks:
     -   id: flake8
 -   repo: https://github.com/codespell-project/codespell
```

### Comparing `plone.formwidget.geolocation-3.0.4/CHANGES.rst` & `plone.formwidget.geolocation-3.0.5/CHANGES.rst`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,21 @@
 Changelog
 =========
 
+3.0.5 (2023-06-28)
+------------------
+
+- Fix controlpanel icon.
+  [petschki]
+
+- Fix showing map when creating content and sanitize default lat/lng
+  values with or without default initial configuration settings.
+  [petschki]
+
+
 3.0.4 (2023-06-02)
 ------------------
 
 - Fix usage of default location from configuration
   [mpeeters]
 
 - Ensure that the marker is the main marker to fix geosearch
```

### Comparing `plone.formwidget.geolocation-3.0.4/Makefile` & `plone.formwidget.geolocation-3.0.5/Makefile`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/PKG-INFO` & `plone.formwidget.geolocation-3.0.5/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: plone.formwidget.geolocation
-Version: 3.0.4
+Version: 3.0.5
 Summary: Geolocation field and widget
 Home-page: https://github.com/collective/plone.formwidget.geolocation
 Author: David Glick
 Author-email: dglick@gmail.com
 License: GPL
 Keywords: z3c form leaflet map field widget
 Classifier: Framework :: Plone
@@ -75,14 +75,25 @@
 -------
 
 The project is licensed under the GPLv2.
 
 Changelog
 =========
 
+3.0.5 (2023-06-28)
+------------------
+
+- Fix controlpanel icon.
+  [petschki]
+
+- Fix showing map when creating content and sanitize default lat/lng
+  values with or without default initial configuration settings.
+  [petschki]
+
+
 3.0.4 (2023-06-02)
 ------------------
 
 - Fix usage of default location from configuration
   [mpeeters]
 
 - Ensure that the marker is the main marker to fix geosearch
```

### Comparing `plone.formwidget.geolocation-3.0.4/README.rst` & `plone.formwidget.geolocation-3.0.5/README.rst`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/docs/INSTALL.txt` & `plone.formwidget.geolocation-3.0.5/docs/INSTALL.txt`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/docs/LICENSE.GPL` & `plone.formwidget.geolocation-3.0.5/docs/LICENSE.GPL`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/docs/LICENSE.txt` & `plone.formwidget.geolocation-3.0.5/docs/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/mx.ini` & `plone.formwidget.geolocation-3.0.5/mx.ini`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/package.json` & `plone.formwidget.geolocation-3.0.5/package.json`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/configure.zcml` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/configure.zcml`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/controlpanel.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/controlpanel.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/converter.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/converter.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/deserializer.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/deserializer.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/geolocation_display.pt` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/geolocation_display.pt`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/geolocation_input.pt` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/geolocation_input.pt`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/interfaces.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/interfaces.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/de/LC_MESSAGES/plone.formwidget.geolocation.po` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/de/LC_MESSAGES/plone.formwidget.geolocation.po`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/fr/LC_MESSAGES/plone.formwidget.geolocation.po` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/fr/LC_MESSAGES/plone.formwidget.geolocation.po`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/plone.formwidget.geolocation.pot` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/plone.formwidget.geolocation.pot`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/locales/update.sh` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/locales/update.sh`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/popup.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/popup.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/default/controlpanel.xml` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/default/controlpanel.xml`

 * *Files 11% similar despite different names*

#### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/default/controlpanel.xml` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/default/controlpanel.xml`

```diff
@@ -1,6 +1,6 @@
 <?xml version="1.0" encoding="utf-8"?>
 <object xmlns:i18n="http://xml.zope.org/namespaces/i18n" meta_type="Plone Control Panel Tool" name="portal_controlpanel" i18n:domain="plone.formwidget.geolocation">
-  <configlet action_id="geolocation-settings" appId="plone.formwidget.geolocation" category="Products" condition_expr="" icon_expr="string:${portal_url}/logoIcon.png" title="Geolocation" url_expr="string:${portal_url}/@@geolocation-controlpanel" visible="True" i18n:attributes="title">
+  <configlet action_id="geolocation-settings" appId="plone.formwidget.geolocation" category="Products" condition_expr="" icon_expr="string:geo-alt" title="Geolocation" url_expr="string:${portal_url}/@@geolocation-controlpanel" visible="True" i18n:attributes="title">
     <permission>Plone Site Setup: Site</permission>
   </configlet>
 </object>
```

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/profiles/default/registry.xml` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/profiles/default/registry.xml`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/serializer.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/serializer.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/151b708954e10ff9b542.png` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/151b708954e10ff9b542.png`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/1551f4f60c37af51121f.woff2` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/1551f4f60c37af51121f.woff2`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/1f2cc17911c8d4a3fa01.png` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/1f2cc17911c8d4a3fa01.png`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/2285773e6b4b172f07d9.woff` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/2285773e6b4b172f07d9.woff`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/23f19bb08961f37aaf69.eot` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/23f19bb08961f37aaf69.eot`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/2b3e1faf89f94a483539.png` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/2b3e1faf89f94a483539.png`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/2f517e09eb2ca6650ff5.svg` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/2f517e09eb2ca6650ff5.svg`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/416d91365b44e4b4f477.png` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/416d91365b44e4b4f477.png`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/4689f52cc96215721344.svg` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/4689f52cc96215721344.svg`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/491974d108fe4002b2aa.ttf` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/491974d108fe4002b2aa.ttf`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/4cb77f5b444ed35e8e2e.svg` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/4cb77f5b444ed35e8e2e.svg`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/527940b104eb2ea366c8.ttf` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/527940b104eb2ea366c8.ttf`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/77206a6bb316fa0aded5.eot` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/77206a6bb316fa0aded5.eot`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/7a3337626410ca2f4071.woff2` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/7a3337626410ca2f4071.woff2`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/7a8b4f130182d19a2d7c.svg` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/7a8b4f130182d19a2d7c.svg`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/8f2c4d11474275fbc161.png` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/8f2c4d11474275fbc161.png`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/9bbb245e67a133f6e486.eot` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/9bbb245e67a133f6e486.eot`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/a8f4a7de091d4a05f2de.svg` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/a8f4a7de091d4a05f2de.svg`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/bb58e57c48a3e911f15f.woff` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/bb58e57c48a3e911f15f.woff`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/be9ee23c0c6390141475.ttf` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/be9ee23c0c6390141475.ttf`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/bundle-remote.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/bundle-remote.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/bundle-remote.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/bundle-remote.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/bundle.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/bundle.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/bundle.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/bundle.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/ca179ed3d0daf2238700.png` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/ca179ed3d0daf2238700.png`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/209.003c259079020170dead.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/209.003c259079020170dead.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/209.003c259079020170dead.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/209.003c259079020170dead.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/225.b61fcef1ea1cd5d168fd.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/225.b61fcef1ea1cd5d168fd.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/225.b61fcef1ea1cd5d168fd.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/225.b61fcef1ea1cd5d168fd.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/243.520ed689ac00fad2760b.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/243.520ed689ac00fad2760b.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/243.520ed689ac00fad2760b.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/243.520ed689ac00fad2760b.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/244.99e821275a9a8cd8a002.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/244.99e821275a9a8cd8a002.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/244.99e821275a9a8cd8a002.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/244.99e821275a9a8cd8a002.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/345.9472bed909073f23fc24.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/345.9472bed909073f23fc24.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/345.9472bed909073f23fc24.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/345.9472bed909073f23fc24.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/408.3b6d07fc9bfe7d5ff5f6.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/408.3b6d07fc9bfe7d5ff5f6.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/408.3b6d07fc9bfe7d5ff5f6.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/408.3b6d07fc9bfe7d5ff5f6.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/632.479ae0ac97903a1a34f2.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/632.479ae0ac97903a1a34f2.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/632.479ae0ac97903a1a34f2.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/632.479ae0ac97903a1a34f2.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/687.92e0c5f9be34801669a1.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/687.92e0c5f9be34801669a1.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/687.92e0c5f9be34801669a1.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/687.92e0c5f9be34801669a1.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/710.2ad7d1d2c95de800580a.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/710.2ad7d1d2c95de800580a.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/732.b3d36ecac26cd86168a1.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/732.b3d36ecac26cd86168a1.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/732.b3d36ecac26cd86168a1.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/732.b3d36ecac26cd86168a1.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/755.e7e5bacd7254c4286594.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/755.e7e5bacd7254c4286594.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/755.e7e5bacd7254c4286594.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/755.e7e5bacd7254c4286594.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/848.b3cd765166bf08cfebcd.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/848.b3cd765166bf08cfebcd.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/848.b3cd765166bf08cfebcd.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/848.b3cd765166bf08cfebcd.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/929.8e6f969165fb95e4f6a3.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/929.8e6f969165fb95e4f6a3.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/929.8e6f969165fb95e4f6a3.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/929.8e6f969165fb95e4f6a3.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/978.21a03d5107c83ad21c78.min.js` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/978.21a03d5107c83ad21c78.min.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/chunks/978.21a03d5107c83ad21c78.min.js.map` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/chunks/978.21a03d5107c83ad21c78.min.js.map`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/d878b0a6a1144760244f.woff2` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/d878b0a6a1144760244f.woff2`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/dfc8c849388499bd892c.png` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/dfc8c849388499bd892c.png`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/e52214306ad12a5c837e.png` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/e52214306ad12a5c837e.png`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/static/eeccf4f66002c6f2ba24.woff` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/static/eeccf4f66002c6f2ba24.woff`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/testing.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/testing.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_converter.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_converter.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_deserializer.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_deserializer.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_geolocation.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_geolocation.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_serializer.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_serializer.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_setup.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_setup.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_supermodel.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_supermodel.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_vocabularies.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_vocabularies.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/tests/test_widget.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/tests/test_widget.py`

 * *Files 6% similar despite different names*

```diff
@@ -93,30 +93,32 @@
         widget.request[widget.name] = (50.0, 5.0)
         widget.update()
         json_result = json.loads(widget.data_geojson)
         feature = json_result["features"][0]
         coordinates = feature["geometry"]["coordinates"]
         self.assertEqual(coordinates, [5.0, 50.0])
 
-    def test_default_loc(self):
+    def test_default_location(self):
         widget = GeolocationWidget(self.request)
         widget.id = widget.name = "geolocation"
         widget.request[widget.name] = None
 
         widget.update()
-        self.assertEqual(widget._default_loc(), (None, None))
+        self.assertEqual(widget.value, (None, None))
+        self.assertEqual(widget.coordinates, ("0", "0"))
 
         set_registry_record("geolocation.default_latitude", 70.0)
         set_registry_record("geolocation.default_longitude", 7.0)
         widget.update()
-        self.assertEqual(widget._default_loc(), (70.0, 7.0))
+        self.assertEqual(widget.value, (70.0, 7.0))
+        self.assertEqual(widget.coordinates, (70.0, 7.0))
 
         set_registry_record("geolocation.use_default_geolocation_as_value", False)
         widget.update()
-        self.assertEqual(widget._default_loc(), (None, None))
+        self.assertEqual(widget.value, (None, None))
 
     def test_render(self):
         widget = GeolocationWidget(self.request)
         widget.id = widget.name = "geolocation"
         self.request[widget.name] = (50.0, 5.0)
         widget.request = self.request
         widget.update()
```

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/upgrades.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/upgrades.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/upgrades.zcml` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/upgrades.zcml`

 * *Files 8% similar despite different names*

```diff
@@ -50,8 +50,17 @@
     <genericsetup:upgradeDepends
         title="Upgrade resource registry"
         import_profile="plone.formwidget.geolocation:to_2000"
         import_steps="plone.app.registry"
         />
   </genericsetup:upgradeSteps>
 
+  <genericsetup:upgradeDepends
+      title="Fix controlpanel icon"
+      description=""
+      profile="plone.formwidget.geolocation:default"
+      source="2000"
+      destination="2001"
+      import_steps="controlpanel"
+      />
+
 </configure>
```

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/vocabularies.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/vocabularies.py`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/plone/formwidget/geolocation/widget.py` & `plone.formwidget.geolocation-3.0.5/plone/formwidget/geolocation/widget.py`

 * *Files 10% similar despite different names*

```diff
@@ -18,38 +18,33 @@
 @implementer_only(IGeolocationWidget)
 class GeolocationWidget(TextWidget):
     klass = "geolocation-widget"
     value = None
 
     def update(self):
         super().update()
-        if self.value is None and self.mode == "input":
-            self.value = self._default_loc()
+        self.coordinates = self.value
+        if self.coordinates is None or not all(self.coordinates):
+            # determine default location from settings if the context
+            self.update_default_location()
 
     @property
     def id_input_lat(self):
         return f"{self.id}_latitude"
 
     @property
     def id_input_lng(self):
         return f"{self.id}_longitude"
 
     @property
     def data_geojson(self):
         """Return the geo location as GeoJSON string."""
-        coordinates = self.value
-        if self.mode != "input" and (not coordinates or not all(coordinates)):
+        if not self.coordinates or not all(self.coordinates):
             return
 
-        if not coordinates or not all(coordinates):
-            coordinates = (
-                getrec("geolocation.default_latitude", default="0"),
-                getrec("geolocation.default_longitude", default="0"),
-            )
-
         popup_view = queryMultiAdapter(
             (self.context, self.request), name="geolocation-geojson-popup"
         )
         geo_json = {
             "type": "FeatureCollection",
             "features": [
                 {
@@ -57,33 +52,28 @@
                     "properties": {
                         "popup": popup_view(),
                         "main": True,
                     },
                     "geometry": {
                         "type": "Point",
                         "coordinates": [
-                            coordinates[1],  # longitude
-                            coordinates[0],  # latitude
+                            self.coordinates[1],  # longitude
+                            self.coordinates[0],  # latitude
                         ],
                     },
                 },
             ],
         }
 
         if self.mode == "input":
             properties = geo_json["features"][0]["properties"]
             properties["editable"] = True
             properties["no_delete"] = True
             properties["latinput"] = f"#{self.id_input_lat}"
             properties["lnginput"] = f"#{self.id_input_lng}"
-            # set default lat/lng to 0 if None
-            if geo_json["features"][0]["geometry"]["coordinates"][0] is None:
-                geo_json["features"][0]["geometry"]["coordinates"][0] = "0"
-            if geo_json["features"][0]["geometry"]["coordinates"][1] is None:
-                geo_json["features"][0]["geometry"]["coordinates"][1] = "0"
 
         return json.dumps(geo_json)
 
     @property
     def map_configuration(self):
         map_layers = getrec("geolocation.map_layers") or []
         config = {
@@ -98,38 +88,44 @@
             "map_layers": [
                 {
                     "title": translate(_(layer), context=self.request),
                     "id": layer,
                 }
                 for layer in map_layers
             ],
-            "latitude": self.value[0],
-            "longitude": self.value[1],
+            "latitude": self.coordinates[0],
+            "longitude": self.coordinates[1],
         }
+
         if self.mode == "input":
             # geosearch for input is always active
             config["geosearch"] = True
             # zoomcontrol for input is always active
             config["zoomcontrol"] = True
-            # set default lat/lng to 0 if None
-            if config["latitude"] is None:
-                config["latitude"] = getrec("geolocation.default_latitude", default="0")
-            if config["longitude"] is None:
-                config["longitude"] = getrec(
-                    "geolocation.default_longitude", default="0"
-                )
+
         return json.dumps(config)
 
-    def _default_loc(self):
+    def update_default_location(self):
         if getrec("geolocation.use_default_geolocation_as_value"):
-            return (
+            # we want to inject default values when creating a content
+            # the values are injected to self.value (input fields)
+            # and self.coordinates (map marker)
+            self.value = self.coordinates = (
                 getrec("geolocation.default_latitude"),
                 getrec("geolocation.default_longitude"),
             )
-        # no default value for contents not yet geolocated
-        return (None, None)
+
+        if self.coordinates is None or not all(self.coordinates):
+            # no default value for contents not yet geolocated
+            # the display template will not show the map at all
+            # NOTE: when creating a content, self.value is None so we have to
+            # set the initial lat/lng tuple here
+            self.value = (None, None)
+            if self.mode == "input":
+                # fallback to ("0", "0") for input mode to show the map and the marker
+                self.coordinates = ("0", "0")
 
 
 @implementer(IFieldWidget)
 @adapter(IGeolocationField, IFormLayer)
 def GeolocationFieldWidget(field, request):
     return FieldWidget(field, GeolocationWidget(request))
```

### Comparing `plone.formwidget.geolocation-3.0.4/plone.formwidget.geolocation.egg-info/PKG-INFO` & `plone.formwidget.geolocation-3.0.5/plone.formwidget.geolocation.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: plone.formwidget.geolocation
-Version: 3.0.4
+Version: 3.0.5
 Summary: Geolocation field and widget
 Home-page: https://github.com/collective/plone.formwidget.geolocation
 Author: David Glick
 Author-email: dglick@gmail.com
 License: GPL
 Keywords: z3c form leaflet map field widget
 Classifier: Framework :: Plone
@@ -75,14 +75,25 @@
 -------
 
 The project is licensed under the GPLv2.
 
 Changelog
 =========
 
+3.0.5 (2023-06-28)
+------------------
+
+- Fix controlpanel icon.
+  [petschki]
+
+- Fix showing map when creating content and sanitize default lat/lng
+  values with or without default initial configuration settings.
+  [petschki]
+
+
 3.0.4 (2023-06-02)
 ------------------
 
 - Fix usage of default location from configuration
   [mpeeters]
 
 - Ensure that the marker is the main marker to fix geosearch
```

### Comparing `plone.formwidget.geolocation-3.0.4/plone.formwidget.geolocation.egg-info/SOURCES.txt` & `plone.formwidget.geolocation-3.0.5/plone.formwidget.geolocation.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -49,15 +49,17 @@
 plone/formwidget/geolocation/testing.zcml
 plone/formwidget/geolocation/upgrades.py
 plone/formwidget/geolocation/upgrades.zcml
 plone/formwidget/geolocation/vocabularies.py
 plone/formwidget/geolocation/widget.py
 plone/formwidget/geolocation/locales/plone.formwidget.geolocation.pot
 plone/formwidget/geolocation/locales/update.sh
+plone/formwidget/geolocation/locales/de/LC_MESSAGES/plone.formwidget.geolocation.mo
 plone/formwidget/geolocation/locales/de/LC_MESSAGES/plone.formwidget.geolocation.po
+plone/formwidget/geolocation/locales/fr/LC_MESSAGES/plone.formwidget.geolocation.mo
 plone/formwidget/geolocation/locales/fr/LC_MESSAGES/plone.formwidget.geolocation.po
 plone/formwidget/geolocation/profiles/default/controlpanel.xml
 plone/formwidget/geolocation/profiles/default/metadata.xml
 plone/formwidget/geolocation/profiles/default/registry.xml
 plone/formwidget/geolocation/profiles/uninstall/registry.xml
 plone/formwidget/geolocation/profiles/upgrades/to_2000/registry.xml
 plone/formwidget/geolocation/static/151b708954e10ff9b542.png
```

### Comparing `plone.formwidget.geolocation-3.0.4/setup.py` & `plone.formwidget.geolocation-3.0.5/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 from setuptools import find_packages
 from setuptools import setup
 
 import os
 
 
-version = "3.0.4"
+version = "3.0.5"
 
 
 def read(*rnames):
     with open(os.path.join(os.path.dirname(__file__), *rnames)) as f:
         return f.read()
```

### Comparing `plone.formwidget.geolocation-3.0.4/tox.ini` & `plone.formwidget.geolocation-3.0.5/tox.ini`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/webpack.config.js` & `plone.formwidget.geolocation-3.0.5/webpack.config.js`

 * *Files identical despite different names*

### Comparing `plone.formwidget.geolocation-3.0.4/yarn.lock` & `plone.formwidget.geolocation-3.0.5/yarn.lock`

 * *Files identical despite different names*

