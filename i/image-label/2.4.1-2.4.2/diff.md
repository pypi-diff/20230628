# Comparing `tmp/image_label-2.4.1.tar.gz` & `tmp/image_label-2.4.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "image_label-2.4.1.tar", last modified: Wed Jun 28 07:55:51 2023, max compression
+gzip compressed data, was "image_label-2.4.2.tar", last modified: Wed Jun 28 09:32:10 2023, max compression
```

## Comparing `image_label-2.4.1.tar` & `image_label-2.4.2.tar`

### file list

```diff
@@ -1,32 +1,32 @@
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:51.001154 image_label-2.4.1/
--rw-rw-r--   0 sks       (1000) sks       (1000)     1063 2023-06-27 05:51:46.000000 image_label-2.4.1/LICENSE
--rw-rw-r--   0 sks       (1000) sks       (1000)       47 2023-06-27 12:56:47.000000 image_label-2.4.1/MANIFEST.in
--rw-rw-r--   0 sks       (1000) sks       (1000)      599 2023-06-28 07:55:50.997154 image_label-2.4.1/PKG-INFO
--rw-rw-r--   0 sks       (1000) sks       (1000)     3594 2023-06-28 07:51:23.000000 image_label-2.4.1/README.md
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.989153 image_label-2.4.1/image_label/
--rw-rw-r--   0 sks       (1000) sks       (1000)     5768 2023-06-28 06:32:15.000000 image_label-2.4.1/image_label/__init__.py
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.989153 image_label-2.4.1/image_label/frontend/
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.993153 image_label-2.4.1/image_label/frontend/build/
--rw-rw-r--   0 sks       (1000) sks       (1000)      879 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/asset-manifest.json
--rw-rw-r--   0 sks       (1000) sks       (1000)   197459 2023-06-27 20:47:52.000000 image_label-2.4.1/image_label/frontend/build/bootstrap.min.css
--rw-rw-r--   0 sks       (1000) sks       (1000)     2168 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/index.html
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.989153 image_label-2.4.1/image_label/frontend/build/static/
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.993153 image_label-2.4.1/image_label/frontend/build/static/css/
--rw-rw-r--   0 sks       (1000) sks       (1000)     1505 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/css/main.459970d8.chunk.css
--rw-rw-r--   0 sks       (1000) sks       (1000)     3311 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/css/main.459970d8.chunk.css.map
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.997154 image_label-2.4.1/image_label/frontend/build/static/js/
--rw-rw-r--   0 sks       (1000) sks       (1000)   533439 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/2.d24733fb.chunk.js
--rw-rw-r--   0 sks       (1000) sks       (1000)     2284 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/2.d24733fb.chunk.js.LICENSE.txt
--rw-rw-r--   0 sks       (1000) sks       (1000)  1907895 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/2.d24733fb.chunk.js.map
--rw-rw-r--   0 sks       (1000) sks       (1000)     4747 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/main.5f5eb4ba.chunk.js
--rw-rw-r--   0 sks       (1000) sks       (1000)    20614 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/main.5f5eb4ba.chunk.js.map
--rw-rw-r--   0 sks       (1000) sks       (1000)     1598 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/runtime-main.657b0728.js
--rw-rw-r--   0 sks       (1000) sks       (1000)     8383 2023-06-27 20:48:03.000000 image_label-2.4.1/image_label/frontend/build/static/js/runtime-main.657b0728.js.map
-drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 07:55:50.993153 image_label-2.4.1/image_label.egg-info/
--rw-rw-r--   0 sks       (1000) sks       (1000)      599 2023-06-28 07:55:50.000000 image_label-2.4.1/image_label.egg-info/PKG-INFO
--rw-rw-r--   0 sks       (1000) sks       (1000)      933 2023-06-28 07:55:50.000000 image_label-2.4.1/image_label.egg-info/SOURCES.txt
--rw-rw-r--   0 sks       (1000) sks       (1000)        1 2023-06-28 07:55:50.000000 image_label-2.4.1/image_label.egg-info/dependency_links.txt
--rw-rw-r--   0 sks       (1000) sks       (1000)       16 2023-06-28 07:55:50.000000 image_label-2.4.1/image_label.egg-info/requires.txt
--rw-rw-r--   0 sks       (1000) sks       (1000)       12 2023-06-28 07:55:50.000000 image_label-2.4.1/image_label.egg-info/top_level.txt
--rw-rw-r--   0 sks       (1000) sks       (1000)       38 2023-06-28 07:55:51.001154 image_label-2.4.1/setup.cfg
--rw-rw-r--   0 sks       (1000) sks       (1000)      970 2023-06-28 07:55:39.000000 image_label-2.4.1/setup.py
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 09:32:10.527840 image_label-2.4.2/
+-rw-rw-r--   0 sks       (1000) sks       (1000)     1063 2023-06-27 05:51:46.000000 image_label-2.4.2/LICENSE
+-rw-rw-r--   0 sks       (1000) sks       (1000)       47 2023-06-27 12:56:47.000000 image_label-2.4.2/MANIFEST.in
+-rw-rw-r--   0 sks       (1000) sks       (1000)      599 2023-06-28 09:32:10.527840 image_label-2.4.2/PKG-INFO
+-rw-rw-r--   0 sks       (1000) sks       (1000)     3594 2023-06-28 07:51:23.000000 image_label-2.4.2/README.md
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 09:32:10.519841 image_label-2.4.2/image_label/
+-rw-rw-r--   0 sks       (1000) sks       (1000)     5768 2023-06-28 09:30:59.000000 image_label-2.4.2/image_label/__init__.py
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 09:32:10.519841 image_label-2.4.2/image_label/frontend/
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 09:32:10.523841 image_label-2.4.2/image_label/frontend/build/
+-rw-rw-r--   0 sks       (1000) sks       (1000)      879 2023-06-28 09:31:28.000000 image_label-2.4.2/image_label/frontend/build/asset-manifest.json
+-rw-rw-r--   0 sks       (1000) sks       (1000)   197459 2023-06-28 09:31:15.000000 image_label-2.4.2/image_label/frontend/build/bootstrap.min.css
+-rw-rw-r--   0 sks       (1000) sks       (1000)     2168 2023-06-28 09:31:28.000000 image_label-2.4.2/image_label/frontend/build/index.html
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 09:32:10.519841 image_label-2.4.2/image_label/frontend/build/static/
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 09:32:10.523841 image_label-2.4.2/image_label/frontend/build/static/css/
+-rw-rw-r--   0 sks       (1000) sks       (1000)     1866 2023-06-28 09:31:28.000000 image_label-2.4.2/image_label/frontend/build/static/css/main.ae733660.chunk.css
+-rw-rw-r--   0 sks       (1000) sks       (1000)     3999 2023-06-28 09:31:28.000000 image_label-2.4.2/image_label/frontend/build/static/css/main.ae733660.chunk.css.map
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 09:32:10.527840 image_label-2.4.2/image_label/frontend/build/static/js/
+-rw-rw-r--   0 sks       (1000) sks       (1000)   533810 2023-06-28 09:31:28.000000 image_label-2.4.2/image_label/frontend/build/static/js/2.97a7e3b4.chunk.js
+-rw-rw-r--   0 sks       (1000) sks       (1000)     2284 2023-06-28 09:31:28.000000 image_label-2.4.2/image_label/frontend/build/static/js/2.97a7e3b4.chunk.js.LICENSE.txt
+-rw-rw-r--   0 sks       (1000) sks       (1000)  1908254 2023-06-28 09:31:28.000000 image_label-2.4.2/image_label/frontend/build/static/js/2.97a7e3b4.chunk.js.map
+-rw-rw-r--   0 sks       (1000) sks       (1000)     6124 2023-06-28 09:31:28.000000 image_label-2.4.2/image_label/frontend/build/static/js/main.209bf5ec.chunk.js
+-rw-rw-r--   0 sks       (1000) sks       (1000)    24446 2023-06-28 09:31:28.000000 image_label-2.4.2/image_label/frontend/build/static/js/main.209bf5ec.chunk.js.map
+-rw-rw-r--   0 sks       (1000) sks       (1000)     1598 2023-06-28 09:31:28.000000 image_label-2.4.2/image_label/frontend/build/static/js/runtime-main.657b0728.js
+-rw-rw-r--   0 sks       (1000) sks       (1000)     8383 2023-06-28 09:31:28.000000 image_label-2.4.2/image_label/frontend/build/static/js/runtime-main.657b0728.js.map
+drwxrwxr-x   0 sks       (1000) sks       (1000)        0 2023-06-28 09:32:10.519841 image_label-2.4.2/image_label.egg-info/
+-rw-rw-r--   0 sks       (1000) sks       (1000)      599 2023-06-28 09:32:10.000000 image_label-2.4.2/image_label.egg-info/PKG-INFO
+-rw-rw-r--   0 sks       (1000) sks       (1000)      933 2023-06-28 09:32:10.000000 image_label-2.4.2/image_label.egg-info/SOURCES.txt
+-rw-rw-r--   0 sks       (1000) sks       (1000)        1 2023-06-28 09:32:10.000000 image_label-2.4.2/image_label.egg-info/dependency_links.txt
+-rw-rw-r--   0 sks       (1000) sks       (1000)       16 2023-06-28 09:32:10.000000 image_label-2.4.2/image_label.egg-info/requires.txt
+-rw-rw-r--   0 sks       (1000) sks       (1000)       12 2023-06-28 09:32:10.000000 image_label-2.4.2/image_label.egg-info/top_level.txt
+-rw-rw-r--   0 sks       (1000) sks       (1000)       38 2023-06-28 09:32:10.527840 image_label-2.4.2/setup.cfg
+-rw-rw-r--   0 sks       (1000) sks       (1000)      970 2023-06-28 09:32:07.000000 image_label-2.4.2/setup.py
```

### Comparing `image_label-2.4.1/LICENSE` & `image_label-2.4.2/LICENSE`

 * *Files identical despite different names*

### Comparing `image_label-2.4.1/PKG-INFO` & `image_label-2.4.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: image_label
-Version: 2.4.1
+Version: 2.4.2
 Summary: This is an Image Labeling Component for streamlit
 Home-page: https://github.com/SksOp/image_label
 Author: sks
 Author-email: shubhaman47@gmail.com
 Requires-Python: >=3.6
 Description-Content-Type: text/plain
 License-File: LICENSE
```

### Comparing `image_label-2.4.1/README.md` & `image_label-2.4.2/README.md`

 * *Files identical despite different names*

### Comparing `image_label-2.4.1/image_label/__init__.py` & `image_label-2.4.2/image_label/__init__.py`

 * *Files identical despite different names*

### Comparing `image_label-2.4.1/image_label/frontend/build/bootstrap.min.css` & `image_label-2.4.2/image_label/frontend/build/bootstrap.min.css`

 * *Files identical despite different names*

### Comparing `image_label-2.4.1/image_label/frontend/build/index.html` & `image_label-2.4.2/image_label/frontend/build/index.html`

 * *Files 4% similar despite different names*

```diff
@@ -1 +1 @@
-<!doctype html><html lang="en"><head><title>Streamlit Component</title><meta charset="UTF-8"/><meta name="viewport" content="width=device-width,initial-scale=1"/><meta name="theme-color" content="#000000"/><meta name="description" content="Streamlit Component"/><link rel="stylesheet" href="bootstrap.min.css"/><link href="./static/css/main.459970d8.chunk.css" rel="stylesheet"></head><body><noscript>You need to enable JavaScript to run this app.</noscript><div id="root"></div><script>!function(e){function t(t){for(var n,l,a=t[0],p=t[1],i=t[2],c=0,s=[];c<a.length;c++)l=a[c],Object.prototype.hasOwnProperty.call(o,l)&&o[l]&&s.push(o[l][0]),o[l]=0;for(n in p)Object.prototype.hasOwnProperty.call(p,n)&&(e[n]=p[n]);for(f&&f(t);s.length;)s.shift()();return u.push.apply(u,i||[]),r()}function r(){for(var e,t=0;t<u.length;t++){for(var r=u[t],n=!0,a=1;a<r.length;a++){var p=r[a];0!==o[p]&&(n=!1)}n&&(u.splice(t--,1),e=l(l.s=r[0]))}return e}var n={},o={1:0},u=[];function l(t){if(n[t])return n[t].exports;var r=n[t]={i:t,l:!1,exports:{}};return e[t].call(r.exports,r,r.exports,l),r.l=!0,r.exports}l.m=e,l.c=n,l.d=function(e,t,r){l.o(e,t)||Object.defineProperty(e,t,{enumerable:!0,get:r})},l.r=function(e){"undefined"!=typeof Symbol&&Symbol.toStringTag&&Object.defineProperty(e,Symbol.toStringTag,{value:"Module"}),Object.defineProperty(e,"__esModule",{value:!0})},l.t=function(e,t){if(1&t&&(e=l(e)),8&t)return e;if(4&t&&"object"==typeof e&&e&&e.__esModule)return e;var r=Object.create(null);if(l.r(r),Object.defineProperty(r,"default",{enumerable:!0,value:e}),2&t&&"string"!=typeof e)for(var n in e)l.d(r,n,function(t){return e[t]}.bind(null,n));return r},l.n=function(e){var t=e&&e.__esModule?function(){return e.default}:function(){return e};return l.d(t,"a",t),t},l.o=function(e,t){return Object.prototype.hasOwnProperty.call(e,t)},l.p="./";var a=this.webpackJsonpstreamlit_component_template=this.webpackJsonpstreamlit_component_template||[],p=a.push.bind(a);a.push=t,a=a.slice();for(var i=0;i<a.length;i++)t(a[i]);var f=p;r()}([])</script><script src="./static/js/2.d24733fb.chunk.js"></script><script src="./static/js/main.5f5eb4ba.chunk.js"></script></body></html>
+<!doctype html><html lang="en"><head><title>Streamlit Component</title><meta charset="UTF-8"/><meta name="viewport" content="width=device-width,initial-scale=1"/><meta name="theme-color" content="#000000"/><meta name="description" content="Streamlit Component"/><link rel="stylesheet" href="bootstrap.min.css"/><link href="./static/css/main.ae733660.chunk.css" rel="stylesheet"></head><body><noscript>You need to enable JavaScript to run this app.</noscript><div id="root"></div><script>!function(e){function t(t){for(var n,l,a=t[0],p=t[1],i=t[2],c=0,s=[];c<a.length;c++)l=a[c],Object.prototype.hasOwnProperty.call(o,l)&&o[l]&&s.push(o[l][0]),o[l]=0;for(n in p)Object.prototype.hasOwnProperty.call(p,n)&&(e[n]=p[n]);for(f&&f(t);s.length;)s.shift()();return u.push.apply(u,i||[]),r()}function r(){for(var e,t=0;t<u.length;t++){for(var r=u[t],n=!0,a=1;a<r.length;a++){var p=r[a];0!==o[p]&&(n=!1)}n&&(u.splice(t--,1),e=l(l.s=r[0]))}return e}var n={},o={1:0},u=[];function l(t){if(n[t])return n[t].exports;var r=n[t]={i:t,l:!1,exports:{}};return e[t].call(r.exports,r,r.exports,l),r.l=!0,r.exports}l.m=e,l.c=n,l.d=function(e,t,r){l.o(e,t)||Object.defineProperty(e,t,{enumerable:!0,get:r})},l.r=function(e){"undefined"!=typeof Symbol&&Symbol.toStringTag&&Object.defineProperty(e,Symbol.toStringTag,{value:"Module"}),Object.defineProperty(e,"__esModule",{value:!0})},l.t=function(e,t){if(1&t&&(e=l(e)),8&t)return e;if(4&t&&"object"==typeof e&&e&&e.__esModule)return e;var r=Object.create(null);if(l.r(r),Object.defineProperty(r,"default",{enumerable:!0,value:e}),2&t&&"string"!=typeof e)for(var n in e)l.d(r,n,function(t){return e[t]}.bind(null,n));return r},l.n=function(e){var t=e&&e.__esModule?function(){return e.default}:function(){return e};return l.d(t,"a",t),t},l.o=function(e,t){return Object.prototype.hasOwnProperty.call(e,t)},l.p="./";var a=this.webpackJsonpstreamlit_component_template=this.webpackJsonpstreamlit_component_template||[],p=a.push.bind(a);a.push=t,a=a.slice();for(var i=0;i<a.length;i++)t(a[i]);var f=p;r()}([])</script><script src="./static/js/2.97a7e3b4.chunk.js"></script><script src="./static/js/main.209bf5ec.chunk.js"></script></body></html>
```

### Comparing `image_label-2.4.1/image_label/frontend/build/static/css/main.459970d8.chunk.css` & `image_label-2.4.2/image_label/frontend/build/static/css/main.ae733660.chunk.css`

 * *Files 14% similar despite different names*

```diff
@@ -1,2 +1,2 @@
-.selectItem{width:100%;border:0;border-bottom:1px solid #ccc;padding:5px;font-size:16px;font-weight:500;color:#333;background:#fff;outline:none;transition:all .3s ease-in-out}.selectItem:focus{border-bottom:1px solid #333}.selectItem:focus-visible{outline:none}.selectItem option{font-size:16px;font-weight:500;color:#333;background:#fff;outline:none;transition:all .3s ease-in-out}.selectItem option:focus,.selectItem option:hover{background:#ccc}.selectItem option:focus-visible{outline:none}.selectItem select{border-radius:10px}.addLabelButton{background-color:#4caf50;border:none;color:#fff;padding:5px 10px;text-align:center;text-decoration:none;display:inline-block;font-size:16px}.addLabelButton:hover{background-color:#3e8e41;cursor:pointer}.addLabelButton:focus,.addLabelButton:focus-visible{outline:none}.holder{border-radius:5px;position:absolute;color:#000;padding:5px;display:flex;grid-gap:10px;gap:10px;flex-direction:column;align-items:flex-end;width:150px;z-index:100}.deleteAnnotationButton{background-color:#691c1c;border:2px solid #f10;border-radius:2px;color:#f7f4f4;text-align:center;text-decoration:none;display:inline-block;font-size:7px;position:absolute;z-index:1000;right:-10px;top:-10px;font-weight:700}.downloadButton{border:none;margin:10px 0;background-color:#151515;color:#4caf50}.downloadButton:hover{background-color:#151515;color:#3e8e41;cursor:pointer}.downloadButton:focus,.downloadButton:focus-visible{outline:none}
-/*# sourceMappingURL=main.459970d8.chunk.css.map */
+.selectItem{width:100%;border:0;border-bottom:1px solid #ccc;padding:5px;font-size:16px;font-weight:500;color:#333;background:#fff;outline:none;transition:all .3s ease-in-out}.selectItem:focus{border-bottom:1px solid #333}.selectItem:focus-visible{outline:none}.selectItem option{font-size:16px;font-weight:500;color:#333;background:#fff;outline:none;transition:all .3s ease-in-out}.selectItem option:focus,.selectItem option:hover{background:#ccc}.selectItem option:focus-visible{outline:none}.selectItem select{border-radius:10px}.addLabelButton{background-color:#4caf50;border:none;color:#fff;padding:5px 10px;text-align:center;text-decoration:none;display:inline-block;font-size:16px}.addLabelButton:hover{background-color:#3e8e41;cursor:pointer}.addLabelButton:focus,.addLabelButton:focus-visible{outline:none}.holder{border-radius:5px;position:absolute;color:#000;padding:5px;display:flex;grid-gap:10px;gap:10px;flex-direction:column;align-items:flex-end;width:150px;z-index:100}.deleteAnnotationButton{background-color:#691c1c;border:2px solid #f10;border-radius:2px;color:#f7f4f4;text-align:center;text-decoration:none;display:inline-block;font-size:7px;position:absolute;z-index:1000;right:-10px;top:-10px;font-weight:700}.downloadButton{border:none;margin:10px 0;background-color:#151515;color:#4caf50}.downloadButton:hover{background-color:#151515;color:#3e8e41;cursor:pointer}.downloadButton:focus,.downloadButton:focus-visible{outline:none}.hoverDiv .hover-info{position:absolute;padding:10px;background:rgba(9,3,40,.3);border-radius:2px;pointer-events:none;color:#fff;-webkit-backdrop-filter:blur(5px);backdrop-filter:blur(5px)}.dataHolder{display:flex;flex-direction:column}.dataItem{display:flex;flex-direction:row;justify-content:space-between;padding:5px;grid-gap:.8rem;gap:.8rem;font-size:.8rem}
+/*# sourceMappingURL=main.ae733660.chunk.css.map */
```

### Comparing `image_label-2.4.1/image_label/frontend/build/static/css/main.459970d8.chunk.css.map` & `image_label-2.4.2/image_label/frontend/build/static/css/main.ae733660.chunk.css.map`

 * *Files 12% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.75%*

 * *Differences: {"'file'": "'main.ae733660.chunk.css'",*

 * * "'mappings'": "'AAAA,YACE,UAAW,CACX,QAAW,CACX,4BAA6B,CAC7B,WAAY,CACZ,cAAe,CACf,eAAgB,CAChB,UAAW,CACX,eAAgB,CAChB,YAAa,CACb,8BACF,CACA,kBACE,4BACF,CACA,0BACE,YACF,CAEA,mBACE,cAAe,CACf,eAAgB,CAChB,UAAW,CACX,eAAgB,CAChB,YAAa,CACb,8BACF,CAMA,kDACE,eACF,CAEA,iCACE,YACF,CAGA,mBACE,kBACF,CAEA,gBACE,wBAAyB,CACzB,WAAY,CACZ,UAAY,CACZ,gBAAiB,CACjB,iBAAkB,CAClB,oBAAqB,CACrB,oBAAqB,CACrB,cACF,CAEA,sBACE,wBAAyB,CACzB,cACF,CAMA,oDACE,YACF,CAiBA,QACE,iBAAkB,CAClB,iBAAkB,CAClB,UAAY,C […]*

```diff
@@ -1,12 +1,12 @@
 {
-    "file": "main.459970d8.chunk.css",
-    "mappings": "AAAA,YACE,UAAW,CACX,QAAW,CACX,4BAA6B,CAC7B,WAAY,CACZ,cAAe,CACf,eAAgB,CAChB,UAAW,CACX,eAAgB,CAChB,YAAa,CACb,8BACF,CACA,kBACE,4BACF,CACA,0BACE,YACF,CAEA,mBACE,cAAe,CACf,eAAgB,CAChB,UAAW,CACX,eAAgB,CAChB,YAAa,CACb,8BACF,CAMA,kDACE,eACF,CAEA,iCACE,YACF,CAGA,mBACE,kBACF,CAEA,gBACE,wBAAyB,CACzB,WAAY,CACZ,UAAY,CACZ,gBAAiB,CACjB,iBAAkB,CAClB,oBAAqB,CACrB,oBAAqB,CACrB,cACF,CAEA,sBACE,wBAAyB,CACzB,cACF,CAMA,oDACE,YACF,CAiBA,QACE,iBAAkB,CAClB,iBAAkB,CAClB,UAAY,CACZ,WAAY,CACZ,YAAa,CACb,aAAS,CAAT,QAAS,CACT,qBAAsB,CACtB,oBAAqB,CACrB,WAAY,CACZ,WACF,CAEA,wBACE,wBAAkC,CAClC,qBAAyB,CACzB,iBAAkB,CAClB,aAAyB,CAEzB,iBAAkB,CAClB,oBAAqB,CACrB,oBAAqB,CACrB,aAAc,CACd,iBAAkB,CAClB,YAAa,CACb,WAAY,CACZ,SAAU,CACV,eACF,CAEA,gBACE,WAAY,CACZ,aAAc,CACd,wBAAiC,CACjC,aACF,CAEA,sBACE,wBAAiC,CACjC,aAAc,CACd,cACF,CAMA,oDACE,YACF",
+    "file": "main.ae733660.chunk.css",
+    "mappings": "AAAA,YACE,UAAW,CACX,QAAW,CACX,4BAA6B,CAC7B,WAAY,CACZ,cAAe,CACf,eAAgB,CAChB,UAAW,CACX,eAAgB,CAChB,YAAa,CACb,8BACF,CACA,kBACE,4BACF,CACA,0BACE,YACF,CAEA,mBACE,cAAe,CACf,eAAgB,CAChB,UAAW,CACX,eAAgB,CAChB,YAAa,CACb,8BACF,CAMA,kDACE,eACF,CAEA,iCACE,YACF,CAGA,mBACE,kBACF,CAEA,gBACE,wBAAyB,CACzB,WAAY,CACZ,UAAY,CACZ,gBAAiB,CACjB,iBAAkB,CAClB,oBAAqB,CACrB,oBAAqB,CACrB,cACF,CAEA,sBACE,wBAAyB,CACzB,cACF,CAMA,oDACE,YACF,CAiBA,QACE,iBAAkB,CAClB,iBAAkB,CAClB,UAAY,CACZ,WAAY,CACZ,YAAa,CACb,aAAS,CAAT,QAAS,CACT,qBAAsB,CACtB,oBAAqB,CACrB,WAAY,CACZ,WACF,CAEA,wBACE,wBAAkC,CAClC,qBAAyB,CACzB,iBAAkB,CAClB,aAAyB,CAEzB,iBAAkB,CAClB,oBAAqB,CACrB,oBAAqB,CACrB,aAAc,CACd,iBAAkB,CAClB,YAAa,CACb,WAAY,CACZ,SAAU,CACV,eACF,CAEA,gBACE,WAAY,CACZ,aAAc,CACd,wBAAiC,CACjC,aACF,CAEA,sBACE,wBAAiC,CACjC,aAAc,CACd,cACF,CAMA,oDACE,YACF,CAEA,sBACE,iBAAkB,CAClB,YAAa,CACb,0BAA+B,CAC/B,iBAAkB,CAClB,mBAAoB,CACpB,UAAyB,CACzB,iCAA0B,CAA1B,yBACF,CAEA,YACE,YAAa,CACb,qBACF,CAEA,UACE,YAAa,CACb,kBAAmB,CACnB,6BAA8B,CAC9B,WAAY,CACZ,cAAW,CAAX,SAAW,CACX,eACF",
     "names": [],
     "sources": [
         "webpack://src/label-image.css"
     ],
     "sourcesContent": [
-        ".selectItem {\n  width: 100%;\n  border: 0px;\n  border-bottom: 1px solid #ccc;\n  padding: 5px;\n  font-size: 16px;\n  font-weight: 500;\n  color: #333;\n  background: #fff;\n  outline: none;\n  transition: all 0.3s ease-in-out;\n}\n.selectItem:focus {\n  border-bottom: 1px solid #333;\n}\n.selectItem:focus-visible {\n  outline: none;\n}\n\n.selectItem option {\n  font-size: 16px;\n  font-weight: 500;\n  color: #333;\n  background: #fff;\n  outline: none;\n  transition: all 0.3s ease-in-out;\n}\n\n.selectItem option:hover {\n  background: #ccc;\n}\n\n.selectItem option:focus {\n  background: #ccc;\n}\n\n.selectItem option:focus-visible {\n  outline: none;\n}\n\n/* making the option holder border radius 10 px */\n.selectItem select {\n  border-radius: 10px;\n}\n\n.addLabelButton {\n  background-color: #4caf50;\n  border: none;\n  color: white;\n  padding: 5px 10px;\n  text-align: center;\n  text-decoration: none;\n  display: inline-block;\n  font-size: 16px;\n}\n\n.addLabelButton:hover {\n  background-color: #3e8e41;\n  cursor: pointer;\n}\n\n.addLabelButton:focus {\n  outline: none;\n}\n\n.addLabelButton:focus-visible {\n  outline: none;\n}\n\n/* style={{\n    background: \"rgba(0, 0, 0, 0.3)\",\n    borderRadius: 3,\n    position: \"absolute\",\n    left: `0`,\n    top: `0`,\n    color: \"black\",\n    padding: \"5px \",\n    display: \"flex\",\n    gap: \"10px\",\n    flexDirection: \"column\",\n    alignItems: \"flex-end\",\n    width: \"100px\"\n  }} */\n\n.holder {\n  border-radius: 5px;\n  position: absolute;\n  color: black;\n  padding: 5px;\n  display: flex;\n  gap: 10px;\n  flex-direction: column;\n  align-items: flex-end;\n  width: 150px;\n  z-index: 100;\n}\n\n.deleteAnnotationButton {\n  background-color: rgb(105, 28, 28);\n  border: 2px solid #ff1100;\n  border-radius: 2px;\n  color: rgb(247, 244, 244);\n\n  text-align: center;\n  text-decoration: none;\n  display: inline-block;\n  font-size: 7px;\n  position: absolute;\n  z-index: 1000;\n  right: -10px;\n  top: -10px;\n  font-weight: bold;\n}\n\n.downloadButton {\n  border: none;\n  margin: 10px 0;\n  background-color: rgb(21, 21, 21);\n  color: #4caf50;\n}\n\n.downloadButton:hover {\n  background-color: rgb(21, 21, 21);\n  color: #3e8e41;\n  cursor: pointer;\n}\n\n.downloadButton:focus {\n  outline: none;\n}\n\n.downloadButton:focus-visible {\n  outline: none;\n}\n"
+        ".selectItem {\n  width: 100%;\n  border: 0px;\n  border-bottom: 1px solid #ccc;\n  padding: 5px;\n  font-size: 16px;\n  font-weight: 500;\n  color: #333;\n  background: #fff;\n  outline: none;\n  transition: all 0.3s ease-in-out;\n}\n.selectItem:focus {\n  border-bottom: 1px solid #333;\n}\n.selectItem:focus-visible {\n  outline: none;\n}\n\n.selectItem option {\n  font-size: 16px;\n  font-weight: 500;\n  color: #333;\n  background: #fff;\n  outline: none;\n  transition: all 0.3s ease-in-out;\n}\n\n.selectItem option:hover {\n  background: #ccc;\n}\n\n.selectItem option:focus {\n  background: #ccc;\n}\n\n.selectItem option:focus-visible {\n  outline: none;\n}\n\n/* making the option holder border radius 10 px */\n.selectItem select {\n  border-radius: 10px;\n}\n\n.addLabelButton {\n  background-color: #4caf50;\n  border: none;\n  color: white;\n  padding: 5px 10px;\n  text-align: center;\n  text-decoration: none;\n  display: inline-block;\n  font-size: 16px;\n}\n\n.addLabelButton:hover {\n  background-color: #3e8e41;\n  cursor: pointer;\n}\n\n.addLabelButton:focus {\n  outline: none;\n}\n\n.addLabelButton:focus-visible {\n  outline: none;\n}\n\n/* style={{\n    background: \"rgba(0, 0, 0, 0.3)\",\n    borderRadius: 3,\n    position: \"absolute\",\n    left: `0`,\n    top: `0`,\n    color: \"black\",\n    padding: \"5px \",\n    display: \"flex\",\n    gap: \"10px\",\n    flexDirection: \"column\",\n    alignItems: \"flex-end\",\n    width: \"100px\"\n  }} */\n\n.holder {\n  border-radius: 5px;\n  position: absolute;\n  color: black;\n  padding: 5px;\n  display: flex;\n  gap: 10px;\n  flex-direction: column;\n  align-items: flex-end;\n  width: 150px;\n  z-index: 100;\n}\n\n.deleteAnnotationButton {\n  background-color: rgb(105, 28, 28);\n  border: 2px solid #ff1100;\n  border-radius: 2px;\n  color: rgb(247, 244, 244);\n\n  text-align: center;\n  text-decoration: none;\n  display: inline-block;\n  font-size: 7px;\n  position: absolute;\n  z-index: 1000;\n  right: -10px;\n  top: -10px;\n  font-weight: bold;\n}\n\n.downloadButton {\n  border: none;\n  margin: 10px 0;\n  background-color: rgb(21, 21, 21);\n  color: #4caf50;\n}\n\n.downloadButton:hover {\n  background-color: rgb(21, 21, 21);\n  color: #3e8e41;\n  cursor: pointer;\n}\n\n.downloadButton:focus {\n  outline: none;\n}\n\n.downloadButton:focus-visible {\n  outline: none;\n}\n\n.hoverDiv .hover-info {\n  position: absolute;\n  padding: 10px;\n  background: rgba(9, 3, 40, 0.3);\n  border-radius: 2px;\n  pointer-events: none;\n  color: rgb(255, 255, 255);\n  backdrop-filter: blur(5px);\n}\n\n.dataHolder {\n  display: flex;\n  flex-direction: column;\n}\n\n.dataItem {\n  display: flex;\n  flex-direction: row;\n  justify-content: space-between;\n  padding: 5px;\n  gap: 0.8rem;\n  font-size: 0.8rem;\n}\n\n.dataItemLabel {\n}\n\n.dataItemValue {\n}\n"
     ],
     "version": 3
 }
```

### Comparing `image_label-2.4.1/image_label/frontend/build/static/js/2.d24733fb.chunk.js` & `image_label-2.4.2/image_label/frontend/build/static/js/2.97a7e3b4.chunk.js`

 * *Files 1% similar despite different names*

#### js-beautify {}

```diff
@@ -1,8 +1,8 @@
-/*! For license information please see 2.d24733fb.chunk.js.LICENSE.txt */
+/*! For license information please see 2.97a7e3b4.chunk.js.LICENSE.txt */
 (this.webpackJsonpstreamlit_component_template = this.webpackJsonpstreamlit_component_template || []).push([
     [2],
     [function(e, t, n) {
         "use strict";
 
         function r(e, t) {
             if (!(e instanceof t)) throw new TypeError("Cannot call a class as a function")
@@ -11,15 +11,15 @@
             return r
         }))
     }, function(e, t, n) {
         "use strict";
         n.d(t, "a", (function() {
             return a
         }));
-        var r = n(21);
+        var r = n(22);
 
         function i(e, t) {
             for (var n = 0; n < t.length; n++) {
                 var i = t[n];
                 i.enumerable = i.enumerable || !1, i.configurable = !0, "value" in i && (i.writable = !0), Object.defineProperty(e, Object(r.a)(i.key), i)
             }
         }
@@ -30,15 +30,15 @@
             }), e
         }
     }, function(e, t, n) {
         "use strict";
         n.d(t, "a", (function() {
             return i
         }));
-        var r = n(19);
+        var r = n(20);
 
         function i(e, t) {
             if ("function" !== typeof t && null !== t) throw new TypeError("Super expression must either be null or a function");
             e.prototype = Object.create(t && t.prototype, {
                 constructor: {
                     value: e,
                     writable: !0,
@@ -50,16 +50,16 @@
         }
     }, function(e, t, n) {
         "use strict";
         n.d(t, "a", (function() {
             return o
         }));
         var r = n(8),
-            i = n(20),
-            a = n(15);
+            i = n(21),
+            a = n(16);
 
         function o(e) {
             var t = Object(i.a)();
             return function() {
                 var n, i = Object(r.a)(e);
                 if (t) {
                     var o = Object(r.a)(this).constructor;
@@ -69,15 +69,15 @@
             }
         }
     }, function(e, t, n) {
         "use strict";
         n.d(t, "a", (function() {
             return i
         }));
-        var r = n(14);
+        var r = n(15);
 
         function i() {
             i = function() {
                 return e
             };
             var e = {},
                 t = Object.prototype,
@@ -397,28 +397,31 @@
             }, e
         }
     }, function(e, t, n) {
         "use strict";
         n.d(t, "a", (function() {
             return a
         }));
-        var r = n(18);
-        var i = n(17);
+        var r = n(19);
+        var i = n(18);
 
         function a(e) {
             return function(e) {
                 if (Array.isArray(e)) return Object(r.a)(e)
             }(e) || function(e) {
                 if ("undefined" !== typeof Symbol && null != e[Symbol.iterator] || null != e["@@iterator"]) return Array.from(e)
             }(e) || Object(i.a)(e) || function() {
                 throw new TypeError("Invalid attempt to spread non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.")
             }()
         }
     }, function(e, t, n) {
         "use strict";
+        e.exports = n(33)
+    }, function(e, t, n) {
+        "use strict";
 
         function r(e, t, n, r, i, a, o) {
             try {
                 var u = e[a](o),
                     c = u.value
             } catch (s) {
                 return void n(s)
@@ -445,34 +448,31 @@
             }
         }
         n.d(t, "a", (function() {
             return i
         }))
     }, function(e, t, n) {
         "use strict";
-        e.exports = n(32)
-    }, function(e, t, n) {
-        "use strict";
 
         function r(e) {
             return r = Object.setPrototypeOf ? Object.getPrototypeOf.bind() : function(e) {
                 return e.__proto__ || Object.getPrototypeOf(e)
             }, r(e)
         }
         n.d(t, "a", (function() {
             return r
         }))
     }, function(e, t, n) {
-        e.exports = n(41)()
+        e.exports = n(42)()
     }, function(e, t, n) {
         "use strict";
         n.d(t, "a", (function() {
             return a
         }));
-        var r = n(12);
+        var r = n(14);
 
         function i(e, t) {
             var n = Object.keys(e);
             if (Object.getOwnPropertySymbols) {
                 var r = Object.getOwnPropertySymbols(e);
                 t && (r = r.filter((function(t) {
                     return Object.getOwnPropertyDescriptor(e, t).enumerable
@@ -490,31 +490,71 @@
                     Object.defineProperty(e, t, Object.getOwnPropertyDescriptor(n, t))
                 }))
             }
             return e
         }
     }, function(e, t, n) {
         "use strict";
+        n.d(t, "a", (function() {
+            return i
+        }));
+        var r = n(18);
+
+        function i(e, t) {
+            return function(e) {
+                if (Array.isArray(e)) return e
+            }(e) || function(e, t) {
+                var n = null == e ? null : "undefined" != typeof Symbol && e[Symbol.iterator] || e["@@iterator"];
+                if (null != n) {
+                    var r, i, a, o, u = [],
+                        c = !0,
+                        s = !1;
+                    try {
+                        if (a = (n = n.call(e)).next, 0 === t) {
+                            if (Object(n) !== n) return;
+                            c = !1
+                        } else
+                            for (; !(c = (r = a.call(n)).done) && (u.push(r.value), u.length !== t); c = !0);
+                    } catch (l) {
+                        s = !0, i = l
+                    } finally {
+                        try {
+                            if (!c && null != n.return && (o = n.return(), Object(o) !== o)) return
+                        } finally {
+                            if (s) throw i
+                        }
+                    }
+                    return u
+                }
+            }(e, t) || Object(r.a)(e, t) || function() {
+                throw new TypeError("Invalid attempt to destructure non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.")
+            }()
+        }
+    }, function(e, t, n) {
+        "use strict";
+        e.exports = n(44)
+    }, function(e, t, n) {
+        "use strict";
         (function(e, r) {
             n.d(t, "b", (function() {
                 return He
             }));
-            var i = n(29),
+            var i = n(30),
                 a = n.n(i),
-                o = n(7),
+                o = n(6),
                 u = n.n(o),
-                c = n(23),
+                c = n(24),
                 s = n.n(c),
-                l = n(30),
+                l = n(31),
                 f = n.n(l),
                 h = n(9),
                 d = n.n(h),
-                p = n(24),
+                p = n(25),
                 y = n.n(p),
-                v = n(22),
+                v = n(23),
                 b = "function" === typeof Symbol && "symbol" === typeof Symbol.iterator ? function(e) {
                     return typeof e
                 } : function(e) {
                     return e && "function" === typeof Symbol && e.constructor === Symbol && e !== Symbol.prototype ? "symbol" : typeof e
                 },
                 m = function(e, t) {
                     if (!(e instanceof t)) throw new TypeError("Cannot call a class as a function")
@@ -1362,35 +1402,32 @@
                         return t(e, n)
                     };
                     return ze.forEach((function(e) {
                         n[e] = n(e)
                     })), n
                 }(Ye, We));
             t.a = $e
-        }).call(this, n(38), n(39)(e))
+        }).call(this, n(39), n(40)(e))
     }, function(e, t, n) {
         "use strict";
         n.d(t, "a", (function() {
             return i
         }));
-        var r = n(21);
+        var r = n(22);
 
         function i(e, t, n) {
             return (t = Object(r.a)(t)) in e ? Object.defineProperty(e, t, {
                 value: n,
                 enumerable: !0,
                 configurable: !0,
                 writable: !0
             }) : e[t] = n, e
         }
     }, function(e, t, n) {
         "use strict";
-        e.exports = n(43)
-    }, function(e, t, n) {
-        "use strict";
 
         function r(e) {
             return r = "function" == typeof Symbol && "symbol" == typeof Symbol.iterator ? function(e) {
                 return typeof e
             } : function(e) {
                 return e && "function" == typeof Symbol && e.constructor === Symbol && e !== Symbol.prototype ? "symbol" : typeof e
             }, r(e)
@@ -1399,16 +1436,16 @@
             return r
         }))
     }, function(e, t, n) {
         "use strict";
         n.d(t, "a", (function() {
             return a
         }));
-        var r = n(14),
-            i = n(16);
+        var r = n(15),
+            i = n(17);
 
         function a(e, t) {
             if (t && ("object" === Object(r.a)(t) || "function" === typeof t)) return t;
             if (void 0 !== t) throw new TypeError("Derived constructors may only return object or undefined");
             return Object(i.a)(e)
         }
     }, function(e, t, n) {
@@ -1422,15 +1459,15 @@
             return r
         }))
     }, function(e, t, n) {
         "use strict";
         n.d(t, "a", (function() {
             return i
         }));
-        var r = n(18);
+        var r = n(19);
 
         function i(e, t) {
             if (e) {
                 if ("string" === typeof e) return Object(r.a)(e, t);
                 var n = Object.prototype.toString.call(e).slice(8, -1);
                 return "Object" === n && e.constructor && (n = e.constructor.name), "Map" === n || "Set" === n ? Array.from(e) : "Arguments" === n || /^(?:Ui|I)nt(?:8|16|32)(?:Clamped)?Array$/.test(n) ? Object(r.a)(e, t) : void 0
             }
@@ -1474,15 +1511,15 @@
             return r
         }))
     }, function(e, t, n) {
         "use strict";
         n.d(t, "a", (function() {
             return i
         }));
-        var r = n(14);
+        var r = n(15);
 
         function i(e) {
             var t = function(e, t) {
                 if ("object" !== Object(r.a)(e) || null === e) return e;
                 var n = e[Symbol.toPrimitive];
                 if (void 0 !== n) {
                     var i = n.call(e, t || "default");
@@ -1491,15 +1528,15 @@
                 }
                 return ("string" === t ? String : Number)(e)
             }(e, "string");
             return "symbol" === Object(r.a)(t) ? t : String(t)
         }
     }, function(e, t, n) {
         "use strict";
-        e.exports = n(36)
+        e.exports = n(37)
     }, function(e, t, n) {
         e.exports = function e(t) {
             "use strict";
             var n = /^\0+/g,
                 r = /[\0\r\f]/g,
                 i = /: */g,
                 a = /zoo|gra/,
@@ -2261,149 +2298,149 @@
                 return t
             }
             return t
         }
     }, function(e, t, n) {
         "use strict";
         n.d(t, "a", (function() {
-            return fl
+            return pl
         })), n.d(t, "b", (function() {
-            return hl
+            return yl
         }));
         var r = {};
         n.r(r), n.d(r, "memcpy", (function() {
-            return Me
+            return Ne
         })), n.d(r, "joinUint8Arrays", (function() {
-            return Le
+            return Pe
         })), n.d(r, "toArrayBufferView", (function() {
-            return Fe
+            return Ue
         })), n.d(r, "toInt8Array", (function() {
-            return Ne
+            return Re
         })), n.d(r, "toInt16Array", (function() {
-            return Pe
+            return ze
         })), n.d(r, "toInt32Array", (function() {
-            return Ue
+            return Ve
         })), n.d(r, "toBigInt64Array", (function() {
-            return Re
+            return We
         })), n.d(r, "toUint8Array", (function() {
-            return ze
+            return Ye
         })), n.d(r, "toUint16Array", (function() {
-            return Ve
+            return He
         })), n.d(r, "toUint32Array", (function() {
-            return We
+            return $e
         })), n.d(r, "toBigUint64Array", (function() {
-            return Ye
+            return Ke
         })), n.d(r, "toFloat32Array", (function() {
-            return He
+            return qe
         })), n.d(r, "toFloat64Array", (function() {
-            return $e
+            return Qe
         })), n.d(r, "toUint8ClampedArray", (function() {
-            return Ke
+            return Ge
         })), n.d(r, "toArrayBufferViewIterator", (function() {
-            return Qe
+            return Je
         })), n.d(r, "toInt8ArrayIterator", (function() {
-            return Ge
+            return Ze
         })), n.d(r, "toInt16ArrayIterator", (function() {
-            return Xe
+            return et
         })), n.d(r, "toInt32ArrayIterator", (function() {
-            return Je
+            return tt
         })), n.d(r, "toUint8ArrayIterator", (function() {
-            return Ze
+            return nt
         })), n.d(r, "toUint16ArrayIterator", (function() {
-            return et
+            return rt
         })), n.d(r, "toUint32ArrayIterator", (function() {
-            return tt
+            return it
         })), n.d(r, "toFloat32ArrayIterator", (function() {
-            return nt
+            return at
         })), n.d(r, "toFloat64ArrayIterator", (function() {
-            return rt
+            return ot
         })), n.d(r, "toUint8ClampedArrayIterator", (function() {
-            return it
+            return ut
         })), n.d(r, "toArrayBufferViewAsyncIterator", (function() {
-            return at
+            return ct
         })), n.d(r, "toInt8ArrayAsyncIterator", (function() {
-            return ut
+            return lt
         })), n.d(r, "toInt16ArrayAsyncIterator", (function() {
-            return ct
+            return ft
         })), n.d(r, "toInt32ArrayAsyncIterator", (function() {
-            return st
+            return ht
         })), n.d(r, "toUint8ArrayAsyncIterator", (function() {
-            return lt
+            return dt
         })), n.d(r, "toUint16ArrayAsyncIterator", (function() {
-            return ft
+            return pt
         })), n.d(r, "toUint32ArrayAsyncIterator", (function() {
-            return ht
+            return yt
         })), n.d(r, "toFloat32ArrayAsyncIterator", (function() {
-            return dt
+            return vt
         })), n.d(r, "toFloat64ArrayAsyncIterator", (function() {
-            return pt
+            return bt
         })), n.d(r, "toUint8ClampedArrayAsyncIterator", (function() {
-            return yt
+            return mt
         })), n.d(r, "rebaseValueOffsets", (function() {
-            return vt
+            return gt
         })), n.d(r, "compareArrayLike", (function() {
-            return bt
+            return kt
         }));
         var i = {};
         n.r(i), n.d(i, "getBool", (function() {
-            return Qt
+            return Jt
         })), n.d(i, "getBit", (function() {
-            return Gt
+            return Zt
         })), n.d(i, "setBool", (function() {
-            return Xt
+            return en
         })), n.d(i, "truncateBitmap", (function() {
-            return Jt
+            return tn
         })), n.d(i, "packBools", (function() {
-            return Zt
+            return nn
         })), n.d(i, "iterateBits", (function() {
-            return en
+            return rn
         })), n.d(i, "popcnt_bit_range", (function() {
-            return tn
+            return an
         })), n.d(i, "popcnt_array", (function() {
-            return nn
+            return on
         })), n.d(i, "popcnt_uint32", (function() {
-            return rn
+            return un
         }));
         var a = {};
         n.r(a), n.d(a, "uint16ToFloat64", (function() {
-            return jr
+            return Sr
         })), n.d(a, "float64ToUint16", (function() {
-            return xr
+            return Ir
         }));
         var o = {};
         n.r(o), n.d(o, "isArrowBigNumSymbol", (function() {
-            return Lr
+            return Pr
         })), n.d(o, "bignumToString", (function() {
-            return Dr
+            return Fr
         })), n.d(o, "bignumToBigInt", (function() {
-            return Mr
+            return Nr
         })), n.d(o, "BN", (function() {
-            return Wr
+            return $r
         }));
         var u = {};
         n.r(u), n.d(u, "clampIndex", (function() {
-            return Ai
+            return Di
         })), n.d(u, "clampRange", (function() {
-            return Ci
-        })), n.d(u, "createElementComparator", (function() {
             return Mi
+        })), n.d(u, "createElementComparator", (function() {
+            return Ni
         }));
         var c = {};
         n.r(c), n.d(c, "BaseInt64", (function() {
-            return Ga
+            return Za
         })), n.d(c, "Uint64", (function() {
-            return Xa
+            return eo
         })), n.d(c, "Int64", (function() {
-            return Ja
+            return to
         })), n.d(c, "Int128", (function() {
-            return Za
+            return no
         }));
-        var s = n(28),
+        var s = n(29),
             l = n.n(s),
-            f = n(7),
+            f = n(6),
             h = n.n(f),
             d = new WeakMap,
             p = new WeakMap;
 
         function y(e) {
             var t = d.get(e);
             return console.assert(null != t, "'this' is expected an Event object, but got", e), t
@@ -2698,15 +2735,15 @@
                     }(i, null), !i.defaultPrevented
             }
         }, Object.defineProperty(E.prototype, "constructor", {
             value: E,
             configurable: !0,
             writable: !0
         }), "undefined" !== typeof window && "undefined" !== typeof window.EventTarget && Object.setPrototypeOf(E.prototype, window.EventTarget.prototype);
-        var A = n(17);
+        var A = n(18);
 
         function C(e, t) {
             var n = "undefined" !== typeof Symbol && e[Symbol.iterator] || e["@@iterator"];
             if (!n) {
                 if (Array.isArray(e) || (n = Object(A.a)(e)) || t && e && "number" === typeof e.length) {
                     n && (e = n);
                     var r = 0,
@@ -2747,49 +2784,19 @@
                         o || null == n.return || n.return()
                     } finally {
                         if (u) throw a
                     }
                 }
             }
         }
-        var B = n(6),
+        var B = n(7),
             D = n(0),
             M = n(1),
-            L = n(4);
-
-        function F(e, t) {
-            return function(e) {
-                if (Array.isArray(e)) return e
-            }(e) || function(e, t) {
-                var n = null == e ? null : "undefined" != typeof Symbol && e[Symbol.iterator] || e["@@iterator"];
-                if (null != n) {
-                    var r, i, a, o, u = [],
-                        c = !0,
-                        s = !1;
-                    try {
-                        if (a = (n = n.call(e)).next, 0 === t) {
-                            if (Object(n) !== n) return;
-                            c = !1
-                        } else
-                            for (; !(c = (r = a.call(n)).done) && (u.push(r.value), u.length !== t); c = !0);
-                    } catch (l) {
-                        s = !0, i = l
-                    } finally {
-                        try {
-                            if (!c && null != n.return && (o = n.return(), Object(o) !== o)) return
-                        } finally {
-                            if (s) throw i
-                        }
-                    }
-                    return u
-                }
-            }(e, t) || Object(A.a)(e, t) || function() {
-                throw new TypeError("Invalid attempt to destructure non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.")
-            }()
-        }
+            L = n(4),
+            F = n(11);
 
         function N(e, t) {
             this.v = e, this.k = t
         }
 
         function P(e) {
             return new N(e, 0)
@@ -3335,15 +3342,15 @@
                 if (ne || !te) {
                     var t = new e("utf-8");
                     return function(e) {
                         return t.decode(e)
                     }
                 }
                 return function(e) {
-                    var t = ze(e),
+                    var t = Ye(e),
                         n = t.buffer,
                         r = t.byteOffset,
                         i = t.length;
                     return te.from(n, r, i).toString()
                 }
             }("undefined" !== typeof TextDecoder ? TextDecoder : X),
             ie = function(e) {
@@ -3351,15 +3358,15 @@
                     var t = new e;
                     return function(e) {
                         return t.encode(e)
                     }
                 }
                 return function() {
                     var e = arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : "";
-                    return ze(te.from(e, "utf8"))
+                    return Ye(te.from(e, "utf8"))
                 }
             }("undefined" !== typeof TextEncoder ? TextEncoder : J),
             ae = n(2),
             oe = n(3),
             ue = Object.freeze({
                 done: !0,
                 value: void 0
@@ -3484,20 +3491,20 @@
                     key: t,
                     value: function() {
                         return this
                     }
                 }, {
                     key: "toDOMStream",
                     value: function(e) {
-                        return gt.toDOMStream(this._closedPromiseResolve || this._error ? this : this._values, e)
+                        return Ot.toDOMStream(this._closedPromiseResolve || this._error ? this : this._values, e)
                     }
                 }, {
                     key: "toNodeStream",
                     value: function(e) {
-                        return gt.toNodeStream(this._closedPromiseResolve || this._error ? this : this._values, e)
+                        return Ot.toNodeStream(this._closedPromiseResolve || this._error ? this : this._values, e)
                     }
                 }, {
                     key: "throw",
                     value: function() {
                         var e = Object(B.a)(Object(L.a)().mark((function e(t) {
                             return Object(L.a)().wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
@@ -3596,31 +3603,32 @@
                     key: "_ensureOpen",
                     value: function() {
                         if (this._closedPromiseResolve) return !0;
                         throw new Error("".concat(this, " is closed"))
                     }
                 }]), r
             }(se, Symbol.asyncIterator),
-            fe = F(function() {
+            fe = function() {
                 var e = function() {
                     throw new Error("BigInt is not available in this environment")
                 };
 
                 function t() {
                     throw e()
                 }
                 return t.asIntN = function() {
                     throw e()
                 }, t.asUintN = function() {
                     throw e()
                 }, "undefined" !== typeof BigInt ? [BigInt, !0] : [t, !1]
-            }(), 2),
-            he = fe[0],
-            de = fe[1],
-            pe = F(function() {
+            }(),
+            he = Object(F.a)(fe, 2),
+            de = he[0],
+            pe = he[1],
+            ye = function() {
                 var e = function() {
                     throw new Error("BigInt64Array is not available in this environment")
                 };
                 return "undefined" !== typeof BigInt64Array ? [BigInt64Array, !0] : [function() {
                     function t() {
                         throw Object(D.a)(this, t), e()
                     }
@@ -3637,17 +3645,18 @@
                     }, {
                         key: "from",
                         value: function() {
                             throw e()
                         }
                     }]), t
                 }(), !1]
-            }(), 2),
-            ye = pe[0],
-            ve = (pe[1], F(function() {
+            }(),
+            ve = Object(F.a)(ye, 2),
+            be = ve[0],
+            me = (ve[1], function() {
                 var e = function() {
                     throw new Error("BigUint64Array is not available in this environment")
                 };
                 return "undefined" !== typeof BigUint64Array ? [BigUint64Array, !0] : [function() {
                     function t() {
                         throw Object(D.a)(this, t), e()
                     }
@@ -3664,154 +3673,155 @@
                     }, {
                         key: "from",
                         value: function() {
                             throw e()
                         }
                     }]), t
                 }(), !1]
-            }(), 2)),
-            be = ve[0],
-            me = (ve[1], function(e) {
+            }()),
+            ge = Object(F.a)(me, 2),
+            ke = ge[0],
+            we = (ge[1], function(e) {
                 return "number" === typeof e
             }),
-            ge = function(e) {
-                return "boolean" === typeof e
-            },
-            ke = function(e) {
-                return "function" === typeof e
-            },
-            we = function(e) {
-                return null != e && Object(e) === e
-            },
             Oe = function(e) {
-                return we(e) && ke(e.then)
+                return "boolean" === typeof e
             },
             _e = function(e) {
-                return we(e) && ke(e[Symbol.iterator])
+                return "function" === typeof e
             },
             je = function(e) {
-                return we(e) && ke(e[Symbol.asyncIterator])
+                return null != e && Object(e) === e
             },
             xe = function(e) {
-                return we(e) && we(e.schema)
+                return je(e) && _e(e.then)
             },
             Te = function(e) {
-                return we(e) && "done" in e && "value" in e
+                return je(e) && _e(e[Symbol.iterator])
             },
             Se = function(e) {
-                return we(e) && ke(e.stat) && me(e.fd)
+                return je(e) && _e(e[Symbol.asyncIterator])
             },
             Ie = function(e) {
-                return we(e) && Ee(e.body)
+                return je(e) && je(e.schema)
             },
             Ee = function(e) {
-                return we(e) && ke(e.cancel) && ke(e.getReader) && !(e instanceof se)
+                return je(e) && "done" in e && "value" in e
             },
             Ae = function(e) {
-                return we(e) && ke(e.read) && ke(e.pipe) && ge(e.readable) && !(e instanceof se)
+                return je(e) && _e(e.stat) && we(e.fd)
+            },
+            Ce = function(e) {
+                return je(e) && Be(e.body)
             },
-            Ce = Object(L.a)().mark(Qe),
-            Be = Y.ByteBuffer,
-            De = "undefined" !== typeof SharedArrayBuffer ? SharedArrayBuffer : ArrayBuffer;
+            Be = function(e) {
+                return je(e) && _e(e.cancel) && _e(e.getReader) && !(e instanceof se)
+            },
+            De = function(e) {
+                return je(e) && _e(e.read) && _e(e.pipe) && Oe(e.readable) && !(e instanceof se)
+            },
+            Me = Object(L.a)().mark(Je),
+            Le = Y.ByteBuffer,
+            Fe = "undefined" !== typeof SharedArrayBuffer ? SharedArrayBuffer : ArrayBuffer;
 
-        function Me(e, t) {
+        function Ne(e, t) {
             var n = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : 0,
                 r = arguments.length > 3 && void 0 !== arguments[3] ? arguments[3] : t.byteLength,
                 i = e.byteLength,
                 a = new Uint8Array(e.buffer, e.byteOffset, i),
                 o = new Uint8Array(t.buffer, t.byteOffset, Math.min(r, i));
             return a.set(o, n), e
         }
 
-        function Le(e, t) {
+        function Pe(e, t) {
             for (var n, r, i, a = function(e) {
                     for (var t, n, r, i, a, o, u = e[0] ? [e[0]] : [], c = 0, s = 0, l = e.length; ++c < l;)
                         if (a = u[s], o = e[c], !a || !o || a.buffer !== o.buffer || o.byteOffset < a.byteOffset) o && (u[++s] = o);
                         else {
                             var f = a;
                             t = f.byteOffset, r = f.byteLength;
                             var h = o;
                             n = h.byteOffset, i = h.byteLength, t + r < n || n + i < t ? o && (u[++s] = o) : u[s] = new Uint8Array(a.buffer, t, n - t + i)
                         } return u
                 }(e), o = a.reduce((function(e, t) {
                     return e + t.byteLength
                 }), 0), u = 0, c = -1, s = Math.min(t || 1 / 0, o), l = a.length; ++c < l;) {
                 if (s <= u + (r = (n = a[c]).subarray(0, Math.min(n.length, s - u))).length) {
-                    r.length < n.length ? a[c] = n.subarray(r.length) : r.length === n.length && c++, i ? Me(i, r, u) : i = r;
+                    r.length < n.length ? a[c] = n.subarray(r.length) : r.length === n.length && c++, i ? Ne(i, r, u) : i = r;
                     break
                 }
-                Me(i || (i = new Uint8Array(s)), r, u), u += r.length
+                Ne(i || (i = new Uint8Array(s)), r, u), u += r.length
             }
             return [i || new Uint8Array(0), a.slice(c), o - (i ? i.byteLength : 0)]
         }
 
-        function Fe(e, t) {
-            var n = Te(t) ? t.value : t;
-            return n instanceof e ? e === Uint8Array ? new e(n.buffer, n.byteOffset, n.byteLength) : n : n ? ("string" === typeof n && (n = ie(n)), n instanceof ArrayBuffer || n instanceof De ? new e(n) : n instanceof Be ? Fe(e, n.bytes()) : ArrayBuffer.isView(n) ? n.byteLength <= 0 ? new e(0) : new e(n.buffer, n.byteOffset, n.byteLength / e.BYTES_PER_ELEMENT) : e.from(n)) : new e(0)
+        function Ue(e, t) {
+            var n = Ee(t) ? t.value : t;
+            return n instanceof e ? e === Uint8Array ? new e(n.buffer, n.byteOffset, n.byteLength) : n : n ? ("string" === typeof n && (n = ie(n)), n instanceof ArrayBuffer || n instanceof Fe ? new e(n) : n instanceof Le ? Ue(e, n.bytes()) : ArrayBuffer.isView(n) ? n.byteLength <= 0 ? new e(0) : new e(n.buffer, n.byteOffset, n.byteLength / e.BYTES_PER_ELEMENT) : e.from(n)) : new e(0)
         }
-        var Ne = function(e) {
-                return Fe(Int8Array, e)
-            },
-            Pe = function(e) {
-                return Fe(Int16Array, e)
-            },
-            Ue = function(e) {
-                return Fe(Int32Array, e)
-            },
-            Re = function(e) {
-                return Fe(ye, e)
+        var Re = function(e) {
+                return Ue(Int8Array, e)
             },
             ze = function(e) {
-                return Fe(Uint8Array, e)
+                return Ue(Int16Array, e)
             },
             Ve = function(e) {
-                return Fe(Uint16Array, e)
+                return Ue(Int32Array, e)
             },
             We = function(e) {
-                return Fe(Uint32Array, e)
+                return Ue(be, e)
             },
             Ye = function(e) {
-                return Fe(be, e)
+                return Ue(Uint8Array, e)
             },
             He = function(e) {
-                return Fe(Float32Array, e)
+                return Ue(Uint16Array, e)
             },
             $e = function(e) {
-                return Fe(Float64Array, e)
+                return Ue(Uint32Array, e)
             },
             Ke = function(e) {
-                return Fe(Uint8ClampedArray, e)
+                return Ue(ke, e)
             },
             qe = function(e) {
+                return Ue(Float32Array, e)
+            },
+            Qe = function(e) {
+                return Ue(Float64Array, e)
+            },
+            Ge = function(e) {
+                return Ue(Uint8ClampedArray, e)
+            },
+            Xe = function(e) {
                 return e.next(), e
             };
 
-        function Qe(e, t) {
+        function Je(e, t) {
             var n, r;
             return Object(L.a)().wrap((function(i) {
                 for (;;) switch (i.prev = i.next) {
                     case 0:
                         return n = Object(L.a)().mark((function e(t) {
                             return Object(L.a)().wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
                                     case 0:
                                         return e.next = 2, t;
                                     case 2:
                                     case "end":
                                         return e.stop()
                                 }
                             }), e)
-                        })), r = "string" === typeof t || ArrayBuffer.isView(t) || t instanceof ArrayBuffer || t instanceof De ? n(t) : _e(t) ? t : n(t), i.delegateYield(qe(Object(L.a)().mark((function t(n) {
+                        })), r = "string" === typeof t || ArrayBuffer.isView(t) || t instanceof ArrayBuffer || t instanceof Fe ? n(t) : Te(t) ? t : n(t), i.delegateYield(Xe(Object(L.a)().mark((function t(n) {
                             var r;
                             return Object(L.a)().wrap((function(t) {
                                 for (;;) switch (t.prev = t.next) {
                                     case 0:
                                         r = null;
                                     case 1:
-                                        return t.t0 = n, t.next = 4, Fe(e, r);
+                                        return t.t0 = n, t.next = 4, Ue(e, r);
                                     case 4:
                                         t.t1 = t.sent, r = t.t0.next.call(t.t0, t.t1);
                                     case 6:
                                         if (!r.done) {
                                             t.next = 1;
                                             break
                                         }
@@ -3821,59 +3831,59 @@
                                 }
                             }), t)
                         }))(r[Symbol.iterator]())), "t0", 3);
                     case 3:
                     case "end":
                         return i.stop()
                 }
-            }), Ce)
+            }), Me)
         }
-        var Ge = function(e) {
-                return Qe(Int8Array, e)
-            },
-            Xe = function(e) {
-                return Qe(Int16Array, e)
-            },
-            Je = function(e) {
-                return Qe(Int32Array, e)
-            },
-            Ze = function(e) {
-                return Qe(Uint8Array, e)
+        var Ze = function(e) {
+                return Je(Int8Array, e)
             },
             et = function(e) {
-                return Qe(Uint16Array, e)
+                return Je(Int16Array, e)
             },
             tt = function(e) {
-                return Qe(Uint32Array, e)
+                return Je(Int32Array, e)
             },
             nt = function(e) {
-                return Qe(Float32Array, e)
+                return Je(Uint8Array, e)
             },
             rt = function(e) {
-                return Qe(Float64Array, e)
+                return Je(Uint16Array, e)
             },
             it = function(e) {
-                return Qe(Uint8ClampedArray, e)
+                return Je(Uint32Array, e)
+            },
+            at = function(e) {
+                return Je(Float32Array, e)
+            },
+            ot = function(e) {
+                return Je(Float64Array, e)
+            },
+            ut = function(e) {
+                return Je(Uint8ClampedArray, e)
             };
 
-        function at(e, t) {
-            return ot.apply(this, arguments)
+        function ct(e, t) {
+            return st.apply(this, arguments)
         }
 
-        function ot() {
-            return ot = R(Object(L.a)().mark((function e(t, n) {
+        function st() {
+            return st = R(Object(L.a)().mark((function e(t, n) {
                 var r, i, a;
                 return Object(L.a)().wrap((function(e) {
                     for (;;) switch (e.prev = e.next) {
                         case 0:
-                            if (!Oe(n)) {
+                            if (!xe(n)) {
                                 e.next = 13;
                                 break
                             }
-                            return e.t0 = z, e.t1 = V, e.t2 = at, e.t3 = t, e.next = 7, P(n);
+                            return e.t0 = z, e.t1 = V, e.t2 = ct, e.t3 = t, e.next = 7, P(n);
                         case 7:
                             return e.t4 = e.sent, e.t5 = (0, e.t2)(e.t3, e.t4), e.t6 = (0, e.t1)(e.t5), e.t7 = P, e.delegateYield((0, e.t0)(e.t6, e.t7), "t8", 12);
                         case 12:
                             return e.abrupt("return", e.t8);
                         case 13:
                             return r = function() {
                                 var e = R(Object(L.a)().mark((function e(t) {
@@ -3893,15 +3903,15 @@
                                     return e.apply(this, arguments)
                                 }
                             }(), i = function() {
                                 var e = R(Object(L.a)().mark((function e(t) {
                                     return Object(L.a)().wrap((function(e) {
                                         for (;;) switch (e.prev = e.next) {
                                             case 0:
-                                                return e.delegateYield(z(V(qe(Object(L.a)().mark((function e(t) {
+                                                return e.delegateYield(z(V(Xe(Object(L.a)().mark((function e(t) {
                                                     var n;
                                                     return Object(L.a)().wrap((function(e) {
                                                         for (;;) switch (e.prev = e.next) {
                                                             case 0:
                                                                 n = null;
                                                             case 1:
                                                                 return e.t0 = t, e.next = 4, n && n.value;
@@ -3923,23 +3933,23 @@
                                                 return e.stop()
                                         }
                                     }), e)
                                 })));
                                 return function(t) {
                                     return e.apply(this, arguments)
                                 }
-                            }(), a = "string" === typeof n || ArrayBuffer.isView(n) || n instanceof ArrayBuffer || n instanceof De ? r(n) : _e(n) ? i(n) : je(n) ? n : r(n), e.delegateYield(z(V(qe(function() {
+                            }(), a = "string" === typeof n || ArrayBuffer.isView(n) || n instanceof ArrayBuffer || n instanceof Fe ? r(n) : Te(n) ? i(n) : Se(n) ? n : r(n), e.delegateYield(z(V(Xe(function() {
                                 var e = R(Object(L.a)().mark((function e(n) {
                                     var r;
                                     return Object(L.a)().wrap((function(e) {
                                         for (;;) switch (e.prev = e.next) {
                                             case 0:
                                                 r = null;
                                             case 1:
-                                                return e.t0 = P, e.t1 = n, e.next = 5, Fe(t, r);
+                                                return e.t0 = P, e.t1 = n, e.next = 5, Ue(t, r);
                                             case 5:
                                                 return e.t2 = e.sent, e.t3 = e.t1.next.call(e.t1, e.t2), e.next = 9, (0, e.t0)(e.t3);
                                             case 9:
                                                 r = e.sent;
                                             case 10:
                                                 if (!r.done) {
                                                     e.next = 1;
@@ -3956,105 +3966,106 @@
                                 }
                             }()(a[Symbol.asyncIterator]())))), "t9", 17);
                         case 17:
                         case "end":
                             return e.stop()
                     }
                 }), e)
-            }))), ot.apply(this, arguments)
+            }))), st.apply(this, arguments)
         }
-        var ut = function(e) {
-                return at(Int8Array, e)
-            },
-            ct = function(e) {
-                return at(Int16Array, e)
-            },
-            st = function(e) {
-                return at(Int32Array, e)
-            },
-            lt = function(e) {
-                return at(Uint8Array, e)
+        var lt = function(e) {
+                return ct(Int8Array, e)
             },
             ft = function(e) {
-                return at(Uint16Array, e)
+                return ct(Int16Array, e)
             },
             ht = function(e) {
-                return at(Uint32Array, e)
+                return ct(Int32Array, e)
             },
             dt = function(e) {
-                return at(Float32Array, e)
+                return ct(Uint8Array, e)
             },
             pt = function(e) {
-                return at(Float64Array, e)
+                return ct(Uint16Array, e)
             },
             yt = function(e) {
-                return at(Uint8ClampedArray, e)
+                return ct(Uint32Array, e)
+            },
+            vt = function(e) {
+                return ct(Float32Array, e)
+            },
+            bt = function(e) {
+                return ct(Float64Array, e)
+            },
+            mt = function(e) {
+                return ct(Uint8ClampedArray, e)
             };
 
-        function vt(e, t, n) {
+        function gt(e, t, n) {
             if (0 !== e) {
                 n = n.slice(0, t + 1);
                 for (var r = -1; ++r <= t;) n[r] += e
             }
             return n
         }
 
-        function bt(e, t) {
+        function kt(e, t) {
             var n = 0,
                 r = e.length;
             if (r !== t.length) return !1;
             if (r > 0)
                 do {
                     if (e[n] !== t[n]) return !1
                 } while (++n < r);
             return !0
         }
-        var mt = Object(L.a)().mark(wt),
-            gt = {
+        var wt = Object(L.a)().mark(jt),
+            Ot = {
                 fromIterable: function(e) {
-                    return kt(wt(e))
+                    return _t(jt(e))
                 },
                 fromAsyncIterable: function(e) {
-                    return kt(function(e) {
-                        return Ot.apply(this, arguments)
+                    return _t(function(e) {
+                        return xt.apply(this, arguments)
                     }(e))
                 },
                 fromDOMStream: function(e) {
-                    return kt(function(e) {
-                        return _t.apply(this, arguments)
+                    return _t(function(e) {
+                        return Tt.apply(this, arguments)
                     }(e))
                 },
                 fromNodeStream: function(e) {
-                    return kt(function(e) {
-                        return It.apply(this, arguments)
+                    return _t(function(e) {
+                        return Ct.apply(this, arguments)
                     }(e))
                 },
                 toDOMStream: function(e, t) {
                     throw new Error('"toDOMStream" not available in this environment')
                 },
                 toNodeStream: function(e, t) {
                     throw new Error('"toNodeStream" not available in this environment')
                 }
             },
-            kt = function(e) {
+            _t = function(e) {
                 return e.next(), e
             };
 
-        function wt(e) {
+        function jt(e) {
             var t, n, r, i, a, o, u, c, s, l, f, h;
             return Object(L.a)().wrap((function(d) {
                 for (;;) switch (d.prev = d.next) {
                     case 0:
                         return c = function() {
-                            if ("peek" === a) return Le(r, o)[0];
-                            var e = F(Le(r, o), 3);
-                            return i = e[0], r = e[1], u = e[2], i
+                            if ("peek" === a) return Pe(r, o)[0];
+                            var e = Pe(r, o),
+                                t = Object(F.a)(e, 3);
+                            return i = t[0], r = t[1], u = t[2], i
                         }, n = !1, r = [], u = 0, d.next = 6, null;
                     case 6:
-                        s = d.sent, a = s.cmd, o = s.size, l = Ze(e)[Symbol.iterator](), d.prev = 10;
+                        s = d.sent, a = s.cmd, o = s.size, l = nt(e)[Symbol.iterator](), d.prev = 10;
                     case 11:
                         if (f = isNaN(o - u) ? l.next(void 0) : l.next(o - u), t = f.done, i = f.value, !t && i.byteLength > 0 && (r.push(i), u += i.byteLength), !(t || o <= u)) {
                             d.next = 22;
                             break
                         }
                     case 16:
                         return d.next = 18, c();
@@ -4077,32 +4088,33 @@
                         d.prev = 25, d.t0 = d.catch(10), (n = !0) && "function" === typeof l.throw && l.throw(d.t0);
                     case 28:
                         return d.prev = 28, !1 === n && "function" === typeof l.return && l.return(), d.finish(28);
                     case 31:
                     case "end":
                         return d.stop()
                 }
-            }), mt, null, [
+            }), wt, null, [
                 [10, 25, 28, 31]
             ])
         }
 
-        function Ot() {
-            return (Ot = R(Object(L.a)().mark((function e(t) {
+        function xt() {
+            return (xt = R(Object(L.a)().mark((function e(t) {
                 var n, r, i, a, o, u, c, s, l, f, h, d;
                 return Object(L.a)().wrap((function(e) {
                     for (;;) switch (e.prev = e.next) {
                         case 0:
                             return s = function() {
-                                if ("peek" === o) return Le(i, u)[0];
-                                var e = F(Le(i, u), 3);
-                                return a = e[0], i = e[1], c = e[2], a
+                                if ("peek" === o) return Pe(i, u)[0];
+                                var e = Pe(i, u),
+                                    t = Object(F.a)(e, 3);
+                                return a = t[0], i = t[1], c = t[2], a
                             }, r = !1, i = [], c = 0, e.next = 6, null;
                         case 6:
-                            l = e.sent, o = l.cmd, u = l.size, f = lt(t)[Symbol.asyncIterator](), e.prev = 10;
+                            l = e.sent, o = l.cmd, u = l.size, f = dt(t)[Symbol.asyncIterator](), e.prev = 10;
                         case 11:
                             if (!isNaN(u - c)) {
                                 e.next = 17;
                                 break
                             }
                             return e.next = 14, P(f.next(void 0));
                         case 14:
@@ -4154,42 +4166,43 @@
                     }
                 }), e, null, [
                     [10, 34, 40, 46]
                 ])
             })))).apply(this, arguments)
         }
 
-        function _t() {
-            return (_t = R(Object(L.a)().mark((function e(t) {
+        function Tt() {
+            return (Tt = R(Object(L.a)().mark((function e(t) {
                 var n, r, i, a, o, u, c, s, l, f, h, d;
                 return Object(L.a)().wrap((function(e) {
                     for (;;) switch (e.prev = e.next) {
                         case 0:
                             return s = function() {
-                                if ("peek" === o) return Le(i, u)[0];
-                                var e = F(Le(i, u), 3);
-                                return a = e[0], i = e[1], c = e[2], a
+                                if ("peek" === o) return Pe(i, u)[0];
+                                var e = Pe(i, u),
+                                    t = Object(F.a)(e, 3);
+                                return a = t[0], i = t[1], c = t[2], a
                             }, n = !1, r = !1, i = [], c = 0, e.next = 6, null;
                         case 6:
-                            l = e.sent, o = l.cmd, u = l.size, f = new jt(t), e.prev = 10;
+                            l = e.sent, o = l.cmd, u = l.size, f = new St(t), e.prev = 10;
                         case 11:
                             if (!isNaN(u - c)) {
                                 e.next = 17;
                                 break
                             }
                             return e.next = 14, P(f.read(void 0));
                         case 14:
                             e.t0 = e.sent, e.next = 20;
                             break;
                         case 17:
                             return e.next = 19, P(f.read(u - c));
                         case 19:
                             e.t0 = e.sent;
                         case 20:
-                            if (h = e.t0, n = h.done, a = h.value, !n && a.byteLength > 0 && (i.push(ze(a)), c += a.byteLength), !(n || u <= c)) {
+                            if (h = e.t0, n = h.done, a = h.value, !n && a.byteLength > 0 && (i.push(Ye(a)), c += a.byteLength), !(n || u <= c)) {
                                 e.next = 31;
                                 break
                             }
                         case 25:
                             return e.next = 27, s();
                         case 27:
                             d = e.sent, o = d.cmd, u = d.size;
@@ -4230,15 +4243,15 @@
                             return e.stop()
                     }
                 }), e, null, [
                     [10, 34, 40, 48]
                 ])
             })))).apply(this, arguments)
         }
-        var jt = function() {
+        var St = function() {
             function e(t) {
                 Object(D.a)(this, e), this.source = t, this.byobReader = null, this.defaultReader = null;
                 try {
                     this.supportsBYOB = !!(this.reader = this.getBYOBReader())
                 } catch (n) {
                     this.supportsBYOB = !(this.reader = this.getDefaultReader())
                 }
@@ -4304,15 +4317,15 @@
                                     e.t0 = e.sent, e.next = 11;
                                     break;
                                 case 8:
                                     return e.next = 10, this.readFromBYOBReader(t);
                                 case 10:
                                     e.t0 = e.sent;
                                 case 11:
-                                    return !(n = e.t0).done && (n.value = ze(n)), e.abrupt("return", n);
+                                    return !(n = e.t0).done && (n.value = Ye(n)), e.abrupt("return", n);
                                 case 14:
                                 case "end":
                                     return e.stop()
                             }
                         }), e, this)
                     })));
                     return function(t) {
@@ -4334,15 +4347,15 @@
             }, {
                 key: "readFromBYOBReader",
                 value: function() {
                     var e = Object(B.a)(Object(L.a)().mark((function e(t) {
                         return Object(L.a)().wrap((function(e) {
                             for (;;) switch (e.prev = e.next) {
                                 case 0:
-                                    return e.next = 2, xt(this.getBYOBReader(), new ArrayBuffer(t), 0, t);
+                                    return e.next = 2, It(this.getBYOBReader(), new ArrayBuffer(t), 0, t);
                                 case 2:
                                     return e.abrupt("return", e.sent);
                                 case 3:
                                 case "end":
                                     return e.stop()
                             }
                         }), e, this)
@@ -4350,20 +4363,20 @@
                     return function(t) {
                         return e.apply(this, arguments)
                     }
                 }()
             }]), e
         }();
 
-        function xt(e, t, n, r) {
-            return Tt.apply(this, arguments)
+        function It(e, t, n, r) {
+            return Et.apply(this, arguments)
         }
 
-        function Tt() {
-            return (Tt = Object(B.a)(Object(L.a)().mark((function e(t, n, r, i) {
+        function Et() {
+            return (Et = Object(B.a)(Object(L.a)().mark((function e(t, n, r, i) {
                 var a, o, u;
                 return Object(L.a)().wrap((function(e) {
                     for (;;) switch (e.prev = e.next) {
                         case 0:
                             if (!(r >= i)) {
                                 e.next = 2;
                                 break
@@ -4375,54 +4388,54 @@
                         case 2:
                             return e.next = 4, t.read(new Uint8Array(n, r, i - r));
                         case 4:
                             if (a = e.sent, o = a.done, u = a.value, !((r += u.byteLength) < i) || o) {
                                 e.next = 11;
                                 break
                             }
-                            return e.next = 10, xt(t, u.buffer, r, i);
+                            return e.next = 10, It(t, u.buffer, r, i);
                         case 10:
                             return e.abrupt("return", e.sent);
                         case 11:
                             return e.abrupt("return", {
                                 done: o,
                                 value: new Uint8Array(u.buffer, 0, r)
                             });
                         case 12:
                         case "end":
                             return e.stop()
                     }
                 }), e)
             })))).apply(this, arguments)
         }
-        var St = function(e, t) {
+        var At = function(e, t) {
             var n, r = function(e) {
                 return n([t, e])
             };
             return [t, r, new Promise((function(i) {
                 return (n = i) && e.once(t, r)
             }))]
         };
 
-        function It() {
-            return It = R(Object(L.a)().mark((function e(t) {
+        function Ct() {
+            return Ct = R(Object(L.a)().mark((function e(t) {
                 var n, r, i, a, o, u, c, s, l, f, h, d, p, y, v;
                 return Object(L.a)().wrap((function(e) {
                     for (;;) switch (e.prev = e.next) {
                         case 0:
                             return v = function(e, n) {
                                 return l = s = null, new Promise(function() {
                                     var r = Object(B.a)(Object(L.a)().mark((function r(i, a) {
                                         var o, u, c, s, l, f;
                                         return Object(L.a)().wrap((function(r) {
                                             for (;;) switch (r.prev = r.next) {
                                                 case 0:
                                                     o = C(e);
                                                     try {
-                                                        for (o.s(); !(u = o.n()).done;) c = F(u.value, 2), s = c[0], l = c[1], t.off(s, l)
+                                                        for (o.s(); !(u = o.n()).done;) c = Object(F.a)(u.value, 2), s = c[0], l = c[1], t.off(s, l)
                                                     } catch (n) {
                                                         o.e(n)
                                                     } finally {
                                                         o.f()
                                                     }
                                                     try {
                                                         (f = t.destroy) && f.call(t, n), n = void 0
@@ -4438,40 +4451,41 @@
                                         }), r)
                                     })));
                                     return function(e, t) {
                                         return r.apply(this, arguments)
                                     }
                                 }())
                             }, f = function() {
-                                if ("peek" === o) return Le(s, u)[0];
-                                var e = F(Le(s, u), 3);
-                                return l = e[0], s = e[1], c = e[2], l
+                                if ("peek" === o) return Pe(s, u)[0];
+                                var e = Pe(s, u),
+                                    t = Object(F.a)(e, 3);
+                                return l = t[0], s = t[1], c = t[2], l
                             }, n = [], r = "error", i = !1, a = null, c = 0, s = [], e.next = 9, null;
                         case 9:
                             if (h = e.sent, o = h.cmd, u = h.size, !t.isTTY) {
                                 e.next = 16;
                                 break
                             }
                             return e.next = 15, new Uint8Array(0);
                         case 15:
                             return e.abrupt("return", e.sent);
                         case 16:
-                            e.prev = 16, n[0] = St(t, "end"), n[1] = St(t, "error");
+                            e.prev = 16, n[0] = At(t, "end"), n[1] = At(t, "error");
                         case 19:
-                            return n[2] = St(t, "readable"), e.next = 22, P(Promise.race(n.map((function(e) {
+                            return n[2] = At(t, "readable"), e.next = 22, P(Promise.race(n.map((function(e) {
                                 return e[2]
                             }))));
                         case 22:
-                            if (d = e.sent, p = F(d, 2), r = p[0], a = p[1], "error" !== r) {
+                            if (d = e.sent, p = Object(F.a)(d, 2), r = p[0], a = p[1], "error" !== r) {
                                 e.next = 28;
                                 break
                             }
                             return e.abrupt("break", 37);
                         case 28:
-                            if ((i = "end" === r) || (isFinite(u - c) ? (l = ze(t.read(u - c))).byteLength < u - c && (l = ze(t.read(void 0))) : l = ze(t.read(void 0)), l.byteLength > 0 && (s.push(l), c += l.byteLength)), !(i || u <= c)) {
+                            if ((i = "end" === r) || (isFinite(u - c) ? (l = Ye(t.read(u - c))).byteLength < u - c && (l = Ye(t.read(void 0))) : l = Ye(t.read(void 0)), l.byteLength > 0 && (s.push(l), c += l.byteLength)), !(i || u <= c)) {
                                 e.next = 36;
                                 break
                             }
                         case 30:
                             return e.next = 32, f();
                         case 32:
                             y = e.sent, o = y.cmd, u = y.size;
@@ -4492,115 +4506,115 @@
                         case 41:
                         case "end":
                             return e.stop()
                     }
                 }), e, null, [
                     [16, , 37, 41]
                 ])
-            }))), It.apply(this, arguments)
+            }))), Ct.apply(this, arguments)
         }
-        var Et = n(10),
-            At = n(8);
+        var Bt = n(10),
+            Dt = n(8);
 
-        function Ct() {
-            return Ct = "undefined" !== typeof Reflect && Reflect.get ? Reflect.get.bind() : function(e, t, n) {
+        function Mt() {
+            return Mt = "undefined" !== typeof Reflect && Reflect.get ? Reflect.get.bind() : function(e, t, n) {
                 var r = function(e, t) {
-                    for (; !Object.prototype.hasOwnProperty.call(e, t) && null !== (e = Object(At.a)(e)););
+                    for (; !Object.prototype.hasOwnProperty.call(e, t) && null !== (e = Object(Dt.a)(e)););
                     return e
                 }(e, t);
                 if (r) {
                     var i = Object.getOwnPropertyDescriptor(r, t);
                     return i.get ? i.get.call(arguments.length < 3 ? e : n) : i.value
                 }
-            }, Ct.apply(this, arguments)
+            }, Mt.apply(this, arguments)
         }
-        var Bt, Dt, Mt, Lt, Ft, Nt, Pt = Object(M.a)((function e() {
+        var Lt, Ft, Nt, Pt, Ut, Rt, zt = Object(M.a)((function e() {
             Object(D.a)(this, e)
         }));
-        Ft = Bt || (Bt = {}), Lt = Ft.apache || (Ft.apache = {}), Mt = Lt.arrow || (Lt.arrow = {}),
+        Ut = Lt || (Lt = {}), Pt = Ut.apache || (Ut.apache = {}), Nt = Pt.arrow || (Pt.arrow = {}),
             function(e) {
                 e[e.V1 = 0] = "V1", e[e.V2 = 1] = "V2", e[e.V3 = 2] = "V3", e[e.V4 = 3] = "V4"
-            }((Dt = Mt.flatbuf || (Mt.flatbuf = {})).MetadataVersion || (Dt.MetadataVersion = {})),
+            }((Ft = Nt.flatbuf || (Nt.flatbuf = {})).MetadataVersion || (Ft.MetadataVersion = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             ! function(e) {
                                 e[e.Sparse = 0] = "Sparse", e[e.Dense = 1] = "Dense"
                             }(e.UnionMode || (e.UnionMode = {}))
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             ! function(e) {
                                 e[e.HALF = 0] = "HALF", e[e.SINGLE = 1] = "SINGLE", e[e.DOUBLE = 2] = "DOUBLE"
                             }(e.Precision || (e.Precision = {}))
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             ! function(e) {
                                 e[e.DAY = 0] = "DAY", e[e.MILLISECOND = 1] = "MILLISECOND"
                             }(e.DateUnit || (e.DateUnit = {}))
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             ! function(e) {
                                 e[e.SECOND = 0] = "SECOND", e[e.MILLISECOND = 1] = "MILLISECOND", e[e.MICROSECOND = 2] = "MICROSECOND", e[e.NANOSECOND = 3] = "NANOSECOND"
                             }(e.TimeUnit || (e.TimeUnit = {}))
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             ! function(e) {
                                 e[e.YEAR_MONTH = 0] = "YEAR_MONTH", e[e.DAY_TIME = 1] = "DAY_TIME"
                             }(e.IntervalUnit || (e.IntervalUnit = {}))
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             ! function(e) {
                                 e[e.NONE = 0] = "NONE", e[e.Null = 1] = "Null", e[e.Int = 2] = "Int", e[e.FloatingPoint = 3] = "FloatingPoint", e[e.Binary = 4] = "Binary", e[e.Utf8 = 5] = "Utf8", e[e.Bool = 6] = "Bool", e[e.Decimal = 7] = "Decimal", e[e.Date = 8] = "Date", e[e.Time = 9] = "Time", e[e.Timestamp = 10] = "Timestamp", e[e.Interval = 11] = "Interval", e[e.List = 12] = "List", e[e.Struct_ = 13] = "Struct_", e[e.Union = 14] = "Union", e[e.FixedSizeBinary = 15] = "FixedSizeBinary", e[e.FixedSizeList = 16] = "FixedSizeList", e[e.Map = 17] = "Map", e[e.Duration = 18] = "Duration", e[e.LargeBinary = 19] = "LargeBinary", e[e.LargeUtf8 = 20] = "LargeUtf8", e[e.LargeList = 21] = "LargeList"
                             }(e.Type || (e.Type = {}))
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             ! function(e) {
                                 e[e.Little = 0] = "Little", e[e.Big = 1] = "Big"
                             }(e.Endianness || (e.Endianness = {}))
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -4632,15 +4646,15 @@
                                     }
                                 }]), e
                             }();
                             e.Null = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -4672,15 +4686,15 @@
                                     }
                                 }]), e
                             }();
                             e.Struct_ = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -4712,15 +4726,15 @@
                                     }
                                 }]), e
                             }();
                             e.List = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -4752,15 +4766,15 @@
                                     }
                                 }]), e
                             }();
                             e.LargeList = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -4803,15 +4817,15 @@
                                     }
                                 }]), e
                             }();
                             e.FixedSizeList = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -4854,15 +4868,15 @@
                                     }
                                 }]), e
                             }();
                             e.Map = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -4940,15 +4954,15 @@
                                     }
                                 }]), t
                             }();
                             t.Union = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -5002,15 +5016,15 @@
                                     }
                                 }]), e
                             }();
                             e.Int = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -5053,15 +5067,15 @@
                                     }
                                 }]), t
                             }();
                             t.FloatingPoint = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -5093,15 +5107,15 @@
                                     }
                                 }]), e
                             }();
                             e.Utf8 = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -5133,15 +5147,15 @@
                                     }
                                 }]), e
                             }();
                             e.Binary = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -5173,15 +5187,15 @@
                                     }
                                 }]), e
                             }();
                             e.LargeUtf8 = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -5213,15 +5227,15 @@
                                     }
                                 }]), e
                             }();
                             e.LargeBinary = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -5264,15 +5278,15 @@
                                     }
                                 }]), e
                             }();
                             e.FixedSizeBinary = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -5304,15 +5318,15 @@
                                     }
                                 }]), e
                             }();
                             e.Bool = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -5366,15 +5380,15 @@
                                     }
                                 }]), e
                             }();
                             e.Decimal = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -5417,15 +5431,15 @@
                                     }
                                 }]), t
                             }();
                             t.Date = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -5479,15 +5493,15 @@
                                     }
                                 }]), t
                             }();
                             t.Time = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -5541,15 +5555,15 @@
                                     }
                                 }]), t
                             }();
                             t.Timestamp = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -5592,15 +5606,15 @@
                                     }
                                 }]), t
                             }();
                             t.Interval = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -5643,15 +5657,15 @@
                                     }
                                 }]), t
                             }();
                             t.Duration = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -5705,15 +5719,15 @@
                                     }
                                 }]), e
                             }();
                             e.KeyValue = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -5778,15 +5792,15 @@
                                     }
                                 }]), t
                             }();
                             t.DictionaryEncoding = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -5931,15 +5945,15 @@
                                     }
                                 }]), t
                             }();
                             t.Field = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -5966,15 +5980,15 @@
                                     }
                                 }]), e
                             }();
                             e.Buffer = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -6080,35 +6094,35 @@
                                     }
                                 }]), t
                             }();
                             t.Schema = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Bt || (Bt = {})),
+            }(Lt || (Lt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
-                            e.Schema = Bt.apache.arrow.flatbuf.Schema
+                            e.Schema = Lt.apache.arrow.flatbuf.Schema
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Nt || (Nt = {})),
+            }(Rt || (Rt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             ! function(e) {
                                 e[e.NONE = 0] = "NONE", e[e.Schema = 1] = "Schema", e[e.DictionaryBatch = 2] = "DictionaryBatch", e[e.RecordBatch = 3] = "RecordBatch", e[e.Tensor = 4] = "Tensor", e[e.SparseTensor = 5] = "SparseTensor"
                             }(e.MessageHeader || (e.MessageHeader = {}))
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Nt || (Nt = {})),
+            }(Rt || (Rt = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -6135,15 +6149,15 @@
                                     }
                                 }]), e
                             }();
                             e.FieldNode = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Nt || (Nt = {})),
+            }(Rt || (Rt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -6171,15 +6185,15 @@
                                         var e = this.bb.__offset(this.bb_pos, 6);
                                         return e ? this.bb.__vector_len(this.bb_pos + e) : 0
                                     }
                                 }, {
                                     key: "buffers",
                                     value: function(e, t) {
                                         var n = this.bb.__offset(this.bb_pos, 8);
-                                        return n ? (t || new Bt.apache.arrow.flatbuf.Buffer).__init(this.bb.__vector(this.bb_pos + n) + 16 * e, this.bb) : null
+                                        return n ? (t || new Lt.apache.arrow.flatbuf.Buffer).__init(this.bb.__vector(this.bb_pos + n) + 16 * e, this.bb) : null
                                     }
                                 }, {
                                     key: "buffersLength",
                                     value: function() {
                                         var e = this.bb.__offset(this.bb_pos, 8);
                                         return e ? this.bb.__vector_len(this.bb_pos + e) : 0
                                     }
@@ -6230,15 +6244,15 @@
                                     }
                                 }]), t
                             }();
                             t.RecordBatch = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Nt || (Nt = {})),
+            }(Rt || (Rt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -6303,15 +6317,15 @@
                                     }
                                 }]), t
                             }();
                             t.DictionaryBatch = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Nt || (Nt = {})),
+            }(Rt || (Rt = {})),
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -6321,15 +6335,15 @@
                                     value: function(e, t) {
                                         return this.bb_pos = e, this.bb = t, this
                                     }
                                 }, {
                                     key: "version",
                                     value: function() {
                                         var e = this.bb.__offset(this.bb_pos, 4);
-                                        return e ? this.bb.readInt16(this.bb_pos + e) : Bt.apache.arrow.flatbuf.MetadataVersion.V1
+                                        return e ? this.bb.readInt16(this.bb_pos + e) : Lt.apache.arrow.flatbuf.MetadataVersion.V1
                                     }
                                 }, {
                                     key: "headerType",
                                     value: function() {
                                         var t = this.bb.__offset(this.bb_pos, 6);
                                         return t ? this.bb.readUint8(this.bb_pos + t) : e.apache.arrow.flatbuf.MessageHeader.NONE
                                     }
@@ -6345,15 +6359,15 @@
                                         var e = this.bb.__offset(this.bb_pos, 10);
                                         return e ? this.bb.readInt64(this.bb_pos + e) : this.bb.createLong(0, 0)
                                     }
                                 }, {
                                     key: "customMetadata",
                                     value: function(e, t) {
                                         var n = this.bb.__offset(this.bb_pos, 12);
-                                        return n ? (t || new Bt.apache.arrow.flatbuf.KeyValue).__init(this.bb.__indirect(this.bb.__vector(this.bb_pos + n) + 4 * e), this.bb) : null
+                                        return n ? (t || new Lt.apache.arrow.flatbuf.KeyValue).__init(this.bb.__indirect(this.bb.__vector(this.bb_pos + n) + 4 * e), this.bb) : null
                                     }
                                 }, {
                                     key: "customMetadataLength",
                                     value: function() {
                                         var e = this.bb.__offset(this.bb_pos, 12);
                                         return e ? this.bb.__vector_len(this.bb_pos + e) : 0
                                     }
@@ -6366,15 +6380,15 @@
                                     key: "startMessage",
                                     value: function(e) {
                                         e.startObject(5)
                                     }
                                 }, {
                                     key: "addVersion",
                                     value: function(e, t) {
-                                        e.addFieldInt16(0, t, Bt.apache.arrow.flatbuf.MetadataVersion.V1)
+                                        e.addFieldInt16(0, t, Lt.apache.arrow.flatbuf.MetadataVersion.V1)
                                     }
                                 }, {
                                     key: "addHeaderType",
                                     value: function(t, n) {
                                         t.addFieldInt8(1, n, e.apache.arrow.flatbuf.MessageHeader.NONE)
                                     }
                                 }, {
@@ -6421,53 +6435,53 @@
                                     }
                                 }]), t
                             }();
                             t.Message = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Nt || (Nt = {}));
-        Bt.apache.arrow.flatbuf.Type;
-        var Ut, Rt, zt = Bt.apache.arrow.flatbuf.DateUnit,
-            Vt = Bt.apache.arrow.flatbuf.TimeUnit,
-            Wt = Bt.apache.arrow.flatbuf.Precision,
-            Yt = Bt.apache.arrow.flatbuf.UnionMode,
-            Ht = Bt.apache.arrow.flatbuf.IntervalUnit,
-            $t = Nt.apache.arrow.flatbuf.MessageHeader,
-            Kt = Bt.apache.arrow.flatbuf.MetadataVersion;
+            }(Rt || (Rt = {}));
+        Lt.apache.arrow.flatbuf.Type;
+        var Vt, Wt, Yt = Lt.apache.arrow.flatbuf.DateUnit,
+            Ht = Lt.apache.arrow.flatbuf.TimeUnit,
+            $t = Lt.apache.arrow.flatbuf.Precision,
+            Kt = Lt.apache.arrow.flatbuf.UnionMode,
+            qt = Lt.apache.arrow.flatbuf.IntervalUnit,
+            Qt = Rt.apache.arrow.flatbuf.MessageHeader,
+            Gt = Lt.apache.arrow.flatbuf.MetadataVersion;
         ! function(e) {
             e[e.NONE = 0] = "NONE", e[e.Null = 1] = "Null", e[e.Int = 2] = "Int", e[e.Float = 3] = "Float", e[e.Binary = 4] = "Binary", e[e.Utf8 = 5] = "Utf8", e[e.Bool = 6] = "Bool", e[e.Decimal = 7] = "Decimal", e[e.Date = 8] = "Date", e[e.Time = 9] = "Time", e[e.Timestamp = 10] = "Timestamp", e[e.Interval = 11] = "Interval", e[e.List = 12] = "List", e[e.Struct = 13] = "Struct", e[e.Union = 14] = "Union", e[e.FixedSizeBinary = 15] = "FixedSizeBinary", e[e.FixedSizeList = 16] = "FixedSizeList", e[e.Map = 17] = "Map", e[e.Dictionary = -1] = "Dictionary", e[e.Int8 = -2] = "Int8", e[e.Int16 = -3] = "Int16", e[e.Int32 = -4] = "Int32", e[e.Int64 = -5] = "Int64", e[e.Uint8 = -6] = "Uint8", e[e.Uint16 = -7] = "Uint16", e[e.Uint32 = -8] = "Uint32", e[e.Uint64 = -9] = "Uint64", e[e.Float16 = -10] = "Float16", e[e.Float32 = -11] = "Float32", e[e.Float64 = -12] = "Float64", e[e.DateDay = -13] = "DateDay", e[e.DateMillisecond = -14] = "DateMillisecond", e[e.TimestampSecond = -15] = "TimestampSecond", e[e.TimestampMillisecond = -16] = "TimestampMillisecond", e[e.TimestampMicrosecond = -17] = "TimestampMicrosecond", e[e.TimestampNanosecond = -18] = "TimestampNanosecond", e[e.TimeSecond = -19] = "TimeSecond", e[e.TimeMillisecond = -20] = "TimeMillisecond", e[e.TimeMicrosecond = -21] = "TimeMicrosecond", e[e.TimeNanosecond = -22] = "TimeNanosecond", e[e.DenseUnion = -23] = "DenseUnion", e[e.SparseUnion = -24] = "SparseUnion", e[e.IntervalDayTime = -25] = "IntervalDayTime", e[e.IntervalYearMonth = -26] = "IntervalYearMonth"
-        }(Ut || (Ut = {})),
+        }(Vt || (Vt = {})),
         function(e) {
             e[e.OFFSET = 0] = "OFFSET", e[e.DATA = 1] = "DATA", e[e.VALIDITY = 2] = "VALIDITY", e[e.TYPE = 3] = "TYPE"
-        }(Rt || (Rt = {}));
-        var qt = Object(L.a)().mark(en);
+        }(Wt || (Wt = {}));
+        var Xt = Object(L.a)().mark(rn);
 
-        function Qt(e, t, n, r) {
+        function Jt(e, t, n, r) {
             return 0 !== (n & 1 << r)
         }
 
-        function Gt(e, t, n, r) {
+        function Zt(e, t, n, r) {
             return (n & 1 << r) >> r
         }
 
-        function Xt(e, t, n) {
+        function en(e, t, n) {
             return n ? !!(e[t >> 3] |= 1 << t % 8) || !0 : !(e[t >> 3] &= ~(1 << t % 8)) && !1
         }
 
-        function Jt(e, t, n) {
+        function tn(e, t, n) {
             var r = n.byteLength + 7 & -8;
             if (e > 0 || n.byteLength < r) {
                 var i = new Uint8Array(r);
-                return i.set(e % 8 === 0 ? n.subarray(e >> 3) : Zt(en(n, e, t, null, Qt)).subarray(0, r)), i
+                return i.set(e % 8 === 0 ? n.subarray(e >> 3) : nn(rn(n, e, t, null, Jt)).subarray(0, r)), i
             }
             return n
         }
 
-        function Zt(e) {
+        function nn(e) {
             var t, n = [],
                 r = 0,
                 i = 0,
                 a = 0,
                 o = C(e);
             try {
                 for (o.s(); !(t = o.n()).done;) {
@@ -6478,15 +6492,15 @@
             } finally {
                 o.f()
             }(0 === r || i > 0) && (n[r++] = a);
             var u = new Uint8Array(n.length + 7 & -8);
             return u.set(n), u
         }
 
-        function en(e, t, n, r, i) {
+        function rn(e, t, n, r, i) {
             var a, o, u, c, s;
             return Object(L.a)().wrap((function(l) {
                 for (;;) switch (l.prev = l.next) {
                     case 0:
                         a = t % 8, o = t >> 3, u = 0, c = n;
                     case 3:
                         if (!(c > 0)) {
@@ -6504,60 +6518,60 @@
                     case 8:
                         a = 0, l.next = 3;
                         break;
                     case 11:
                     case "end":
                         return l.stop()
                 }
-            }), qt)
+            }), Xt)
         }
 
-        function tn(e, t, n) {
+        function an(e, t, n) {
             if (n - t <= 0) return 0;
             if (n - t < 8) {
                 var r, i = 0,
-                    a = C(en(e, t, n - t, e, Gt));
+                    a = C(rn(e, t, n - t, e, Zt));
                 try {
                     for (a.s(); !(r = a.n()).done;) {
                         i += r.value
                     }
                 } catch (c) {
                     a.e(c)
                 } finally {
                     a.f()
                 }
                 return i
             }
             var o = n >> 3 << 3,
                 u = t + (t % 8 === 0 ? 0 : 8 - t % 8);
-            return tn(e, t, u) + tn(e, o, n) + nn(e, u >> 3, o - u >> 3)
+            return an(e, t, u) + an(e, o, n) + on(e, u >> 3, o - u >> 3)
         }
 
-        function nn(e, t, n) {
-            for (var r = 0, i = 0 | t, a = new DataView(e.buffer, e.byteOffset, e.byteLength), o = void 0 === n ? e.byteLength : i + n; o - i >= 4;) r += rn(a.getUint32(i)), i += 4;
-            for (; o - i >= 2;) r += rn(a.getUint16(i)), i += 2;
-            for (; o - i >= 1;) r += rn(a.getUint8(i)), i += 1;
+        function on(e, t, n) {
+            for (var r = 0, i = 0 | t, a = new DataView(e.buffer, e.byteOffset, e.byteLength), o = void 0 === n ? e.byteLength : i + n; o - i >= 4;) r += un(a.getUint32(i)), i += 4;
+            for (; o - i >= 2;) r += un(a.getUint16(i)), i += 2;
+            for (; o - i >= 1;) r += un(a.getUint8(i)), i += 1;
             return r
         }
 
-        function rn(e) {
+        function un(e) {
             var t = 0 | e;
             return 16843009 * ((t = (858993459 & (t -= t >>> 1 & 1431655765)) + (t >>> 2 & 858993459)) + (t >>> 4) & 252645135) >>> 24
         }
-        var an = n(5),
-            on = function() {
+        var cn = n(5),
+            sn = function() {
                 function e() {
                     Object(D.a)(this, e)
                 }
                 return Object(M.a)(e, [{
                     key: "visitMany",
                     value: function(e) {
                         for (var t = this, n = arguments.length, r = new Array(n > 1 ? n - 1 : 0), i = 1; i < n; i++) r[i - 1] = arguments[i];
                         return e.map((function(e, n) {
-                            return t.visit.apply(t, [e].concat(Object(an.a)(r.map((function(e) {
+                            return t.visit.apply(t, [e].concat(Object(cn.a)(r.map((function(e) {
                                 return e[n]
                             })))))
                         }))
                     }
                 }, {
                     key: "visit",
                     value: function() {
@@ -6566,151 +6580,151 @@
                     }
                 }, {
                     key: "getVisitFn",
                     value: function(e) {
                         return function(e, t) {
                             var n = !(arguments.length > 2 && void 0 !== arguments[2]) || arguments[2],
                                 r = null,
-                                i = Ut.NONE;
-                            t instanceof tr || t instanceof Pt ? i = un(t.type) : t instanceof kn ? i = un(t) : "number" !== typeof(i = t) && (i = Ut[t]);
+                                i = Vt.NONE;
+                            t instanceof ir || t instanceof zt ? i = ln(t.type) : t instanceof _n ? i = ln(t) : "number" !== typeof(i = t) && (i = Vt[t]);
                             switch (i) {
-                                case Ut.Null:
+                                case Vt.Null:
                                     r = e.visitNull;
                                     break;
-                                case Ut.Bool:
+                                case Vt.Bool:
                                     r = e.visitBool;
                                     break;
-                                case Ut.Int:
+                                case Vt.Int:
                                     r = e.visitInt;
                                     break;
-                                case Ut.Int8:
+                                case Vt.Int8:
                                     r = e.visitInt8 || e.visitInt;
                                     break;
-                                case Ut.Int16:
+                                case Vt.Int16:
                                     r = e.visitInt16 || e.visitInt;
                                     break;
-                                case Ut.Int32:
+                                case Vt.Int32:
                                     r = e.visitInt32 || e.visitInt;
                                     break;
-                                case Ut.Int64:
+                                case Vt.Int64:
                                     r = e.visitInt64 || e.visitInt;
                                     break;
-                                case Ut.Uint8:
+                                case Vt.Uint8:
                                     r = e.visitUint8 || e.visitInt;
                                     break;
-                                case Ut.Uint16:
+                                case Vt.Uint16:
                                     r = e.visitUint16 || e.visitInt;
                                     break;
-                                case Ut.Uint32:
+                                case Vt.Uint32:
                                     r = e.visitUint32 || e.visitInt;
                                     break;
-                                case Ut.Uint64:
+                                case Vt.Uint64:
                                     r = e.visitUint64 || e.visitInt;
                                     break;
-                                case Ut.Float:
+                                case Vt.Float:
                                     r = e.visitFloat;
                                     break;
-                                case Ut.Float16:
+                                case Vt.Float16:
                                     r = e.visitFloat16 || e.visitFloat;
                                     break;
-                                case Ut.Float32:
+                                case Vt.Float32:
                                     r = e.visitFloat32 || e.visitFloat;
                                     break;
-                                case Ut.Float64:
+                                case Vt.Float64:
                                     r = e.visitFloat64 || e.visitFloat;
                                     break;
-                                case Ut.Utf8:
+                                case Vt.Utf8:
                                     r = e.visitUtf8;
                                     break;
-                                case Ut.Binary:
+                                case Vt.Binary:
                                     r = e.visitBinary;
                                     break;
-                                case Ut.FixedSizeBinary:
+                                case Vt.FixedSizeBinary:
                                     r = e.visitFixedSizeBinary;
                                     break;
-                                case Ut.Date:
+                                case Vt.Date:
                                     r = e.visitDate;
                                     break;
-                                case Ut.DateDay:
+                                case Vt.DateDay:
                                     r = e.visitDateDay || e.visitDate;
                                     break;
-                                case Ut.DateMillisecond:
+                                case Vt.DateMillisecond:
                                     r = e.visitDateMillisecond || e.visitDate;
                                     break;
-                                case Ut.Timestamp:
+                                case Vt.Timestamp:
                                     r = e.visitTimestamp;
                                     break;
-                                case Ut.TimestampSecond:
+                                case Vt.TimestampSecond:
                                     r = e.visitTimestampSecond || e.visitTimestamp;
                                     break;
-                                case Ut.TimestampMillisecond:
+                                case Vt.TimestampMillisecond:
                                     r = e.visitTimestampMillisecond || e.visitTimestamp;
                                     break;
-                                case Ut.TimestampMicrosecond:
+                                case Vt.TimestampMicrosecond:
                                     r = e.visitTimestampMicrosecond || e.visitTimestamp;
                                     break;
-                                case Ut.TimestampNanosecond:
+                                case Vt.TimestampNanosecond:
                                     r = e.visitTimestampNanosecond || e.visitTimestamp;
                                     break;
-                                case Ut.Time:
+                                case Vt.Time:
                                     r = e.visitTime;
                                     break;
-                                case Ut.TimeSecond:
+                                case Vt.TimeSecond:
                                     r = e.visitTimeSecond || e.visitTime;
                                     break;
-                                case Ut.TimeMillisecond:
+                                case Vt.TimeMillisecond:
                                     r = e.visitTimeMillisecond || e.visitTime;
                                     break;
-                                case Ut.TimeMicrosecond:
+                                case Vt.TimeMicrosecond:
                                     r = e.visitTimeMicrosecond || e.visitTime;
                                     break;
-                                case Ut.TimeNanosecond:
+                                case Vt.TimeNanosecond:
                                     r = e.visitTimeNanosecond || e.visitTime;
                                     break;
-                                case Ut.Decimal:
+                                case Vt.Decimal:
                                     r = e.visitDecimal;
                                     break;
-                                case Ut.List:
+                                case Vt.List:
                                     r = e.visitList;
                                     break;
-                                case Ut.Struct:
+                                case Vt.Struct:
                                     r = e.visitStruct;
                                     break;
-                                case Ut.Union:
+                                case Vt.Union:
                                     r = e.visitUnion;
                                     break;
-                                case Ut.DenseUnion:
+                                case Vt.DenseUnion:
                                     r = e.visitDenseUnion || e.visitUnion;
                                     break;
-                                case Ut.SparseUnion:
+                                case Vt.SparseUnion:
                                     r = e.visitSparseUnion || e.visitUnion;
                                     break;
-                                case Ut.Dictionary:
+                                case Vt.Dictionary:
                                     r = e.visitDictionary;
                                     break;
-                                case Ut.Interval:
+                                case Vt.Interval:
                                     r = e.visitInterval;
                                     break;
-                                case Ut.IntervalDayTime:
+                                case Vt.IntervalDayTime:
                                     r = e.visitIntervalDayTime || e.visitInterval;
                                     break;
-                                case Ut.IntervalYearMonth:
+                                case Vt.IntervalYearMonth:
                                     r = e.visitIntervalYearMonth || e.visitInterval;
                                     break;
-                                case Ut.FixedSizeList:
+                                case Vt.FixedSizeList:
                                     r = e.visitFixedSizeList;
                                     break;
-                                case Ut.Map:
+                                case Vt.Map:
                                     r = e.visitMap
                             }
                             if ("function" === typeof r) return r;
                             if (!n) return function() {
                                 return null
                             };
-                            throw new Error("Unrecognized type '".concat(Ut[i], "'"))
+                            throw new Error("Unrecognized type '".concat(Vt[i], "'"))
                         }(this, e, !(arguments.length > 1 && void 0 !== arguments[1]) || arguments[1])
                     }
                 }, {
                     key: "visitNull",
                     value: function(e) {
                         return null
                     }
@@ -6798,333 +6812,333 @@
                     key: "visitMap",
                     value: function(e) {
                         return null
                     }
                 }]), e
             }();
 
-        function un(e) {
+        function ln(e) {
             switch (e.typeId) {
-                case Ut.Null:
-                    return Ut.Null;
-                case Ut.Int:
+                case Vt.Null:
+                    return Vt.Null;
+                case Vt.Int:
                     var t = e.bitWidth,
                         n = e.isSigned;
                     switch (t) {
                         case 8:
-                            return n ? Ut.Int8 : Ut.Uint8;
+                            return n ? Vt.Int8 : Vt.Uint8;
                         case 16:
-                            return n ? Ut.Int16 : Ut.Uint16;
+                            return n ? Vt.Int16 : Vt.Uint16;
                         case 32:
-                            return n ? Ut.Int32 : Ut.Uint32;
+                            return n ? Vt.Int32 : Vt.Uint32;
                         case 64:
-                            return n ? Ut.Int64 : Ut.Uint64
+                            return n ? Vt.Int64 : Vt.Uint64
                     }
-                    return Ut.Int;
-                case Ut.Float:
+                    return Vt.Int;
+                case Vt.Float:
                     switch (e.precision) {
-                        case Wt.HALF:
-                            return Ut.Float16;
-                        case Wt.SINGLE:
-                            return Ut.Float32;
-                        case Wt.DOUBLE:
-                            return Ut.Float64
-                    }
-                    return Ut.Float;
-                case Ut.Binary:
-                    return Ut.Binary;
-                case Ut.Utf8:
-                    return Ut.Utf8;
-                case Ut.Bool:
-                    return Ut.Bool;
-                case Ut.Decimal:
-                    return Ut.Decimal;
-                case Ut.Time:
+                        case $t.HALF:
+                            return Vt.Float16;
+                        case $t.SINGLE:
+                            return Vt.Float32;
+                        case $t.DOUBLE:
+                            return Vt.Float64
+                    }
+                    return Vt.Float;
+                case Vt.Binary:
+                    return Vt.Binary;
+                case Vt.Utf8:
+                    return Vt.Utf8;
+                case Vt.Bool:
+                    return Vt.Bool;
+                case Vt.Decimal:
+                    return Vt.Decimal;
+                case Vt.Time:
                     switch (e.unit) {
-                        case Vt.SECOND:
-                            return Ut.TimeSecond;
-                        case Vt.MILLISECOND:
-                            return Ut.TimeMillisecond;
-                        case Vt.MICROSECOND:
-                            return Ut.TimeMicrosecond;
-                        case Vt.NANOSECOND:
-                            return Ut.TimeNanosecond
+                        case Ht.SECOND:
+                            return Vt.TimeSecond;
+                        case Ht.MILLISECOND:
+                            return Vt.TimeMillisecond;
+                        case Ht.MICROSECOND:
+                            return Vt.TimeMicrosecond;
+                        case Ht.NANOSECOND:
+                            return Vt.TimeNanosecond
                     }
-                    return Ut.Time;
-                case Ut.Timestamp:
+                    return Vt.Time;
+                case Vt.Timestamp:
                     switch (e.unit) {
-                        case Vt.SECOND:
-                            return Ut.TimestampSecond;
-                        case Vt.MILLISECOND:
-                            return Ut.TimestampMillisecond;
-                        case Vt.MICROSECOND:
-                            return Ut.TimestampMicrosecond;
-                        case Vt.NANOSECOND:
-                            return Ut.TimestampNanosecond
+                        case Ht.SECOND:
+                            return Vt.TimestampSecond;
+                        case Ht.MILLISECOND:
+                            return Vt.TimestampMillisecond;
+                        case Ht.MICROSECOND:
+                            return Vt.TimestampMicrosecond;
+                        case Ht.NANOSECOND:
+                            return Vt.TimestampNanosecond
                     }
-                    return Ut.Timestamp;
-                case Ut.Date:
+                    return Vt.Timestamp;
+                case Vt.Date:
                     switch (e.unit) {
-                        case zt.DAY:
-                            return Ut.DateDay;
-                        case zt.MILLISECOND:
-                            return Ut.DateMillisecond
+                        case Yt.DAY:
+                            return Vt.DateDay;
+                        case Yt.MILLISECOND:
+                            return Vt.DateMillisecond
                     }
-                    return Ut.Date;
-                case Ut.Interval:
+                    return Vt.Date;
+                case Vt.Interval:
                     switch (e.unit) {
-                        case Ht.DAY_TIME:
-                            return Ut.IntervalDayTime;
-                        case Ht.YEAR_MONTH:
-                            return Ut.IntervalYearMonth
-                    }
-                    return Ut.Interval;
-                case Ut.Map:
-                    return Ut.Map;
-                case Ut.List:
-                    return Ut.List;
-                case Ut.Struct:
-                    return Ut.Struct;
-                case Ut.Union:
+                        case qt.DAY_TIME:
+                            return Vt.IntervalDayTime;
+                        case qt.YEAR_MONTH:
+                            return Vt.IntervalYearMonth
+                    }
+                    return Vt.Interval;
+                case Vt.Map:
+                    return Vt.Map;
+                case Vt.List:
+                    return Vt.List;
+                case Vt.Struct:
+                    return Vt.Struct;
+                case Vt.Union:
                     switch (e.mode) {
-                        case Yt.Dense:
-                            return Ut.DenseUnion;
-                        case Yt.Sparse:
-                            return Ut.SparseUnion
-                    }
-                    return Ut.Union;
-                case Ut.FixedSizeBinary:
-                    return Ut.FixedSizeBinary;
-                case Ut.FixedSizeList:
-                    return Ut.FixedSizeList;
-                case Ut.Dictionary:
-                    return Ut.Dictionary
+                        case Kt.Dense:
+                            return Vt.DenseUnion;
+                        case Kt.Sparse:
+                            return Vt.SparseUnion
+                    }
+                    return Vt.Union;
+                case Vt.FixedSizeBinary:
+                    return Vt.FixedSizeBinary;
+                case Vt.FixedSizeList:
+                    return Vt.FixedSizeList;
+                case Vt.Dictionary:
+                    return Vt.Dictionary
             }
-            throw new Error("Unrecognized type '".concat(Ut[e.typeId], "'"))
+            throw new Error("Unrecognized type '".concat(Vt[e.typeId], "'"))
         }
-        on.prototype.visitInt8 = null, on.prototype.visitInt16 = null, on.prototype.visitInt32 = null, on.prototype.visitInt64 = null, on.prototype.visitUint8 = null, on.prototype.visitUint16 = null, on.prototype.visitUint32 = null, on.prototype.visitUint64 = null, on.prototype.visitFloat16 = null, on.prototype.visitFloat32 = null, on.prototype.visitFloat64 = null, on.prototype.visitDateDay = null, on.prototype.visitDateMillisecond = null, on.prototype.visitTimestampSecond = null, on.prototype.visitTimestampMillisecond = null, on.prototype.visitTimestampMicrosecond = null, on.prototype.visitTimestampNanosecond = null, on.prototype.visitTimeSecond = null, on.prototype.visitTimeMillisecond = null, on.prototype.visitTimeMicrosecond = null, on.prototype.visitTimeNanosecond = null, on.prototype.visitDenseUnion = null, on.prototype.visitSparseUnion = null, on.prototype.visitIntervalDayTime = null, on.prototype.visitIntervalYearMonth = null;
-        var cn = function(e) {
+        sn.prototype.visitInt8 = null, sn.prototype.visitInt16 = null, sn.prototype.visitInt32 = null, sn.prototype.visitInt64 = null, sn.prototype.visitUint8 = null, sn.prototype.visitUint16 = null, sn.prototype.visitUint32 = null, sn.prototype.visitUint64 = null, sn.prototype.visitFloat16 = null, sn.prototype.visitFloat32 = null, sn.prototype.visitFloat64 = null, sn.prototype.visitDateDay = null, sn.prototype.visitDateMillisecond = null, sn.prototype.visitTimestampSecond = null, sn.prototype.visitTimestampMillisecond = null, sn.prototype.visitTimestampMicrosecond = null, sn.prototype.visitTimestampNanosecond = null, sn.prototype.visitTimeSecond = null, sn.prototype.visitTimeMillisecond = null, sn.prototype.visitTimeMicrosecond = null, sn.prototype.visitTimeNanosecond = null, sn.prototype.visitDenseUnion = null, sn.prototype.visitSparseUnion = null, sn.prototype.visitIntervalDayTime = null, sn.prototype.visitIntervalYearMonth = null;
+        var fn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n() {
                 return Object(D.a)(this, n), t.apply(this, arguments)
             }
             return Object(M.a)(n, [{
                 key: "compareSchemas",
                 value: function(e, t) {
-                    return e === t || t instanceof e.constructor && gn.compareFields(e.fields, t.fields)
+                    return e === t || t instanceof e.constructor && On.compareFields(e.fields, t.fields)
                 }
             }, {
                 key: "compareFields",
                 value: function(e, t) {
                     return e === t || Array.isArray(e) && Array.isArray(t) && e.length === t.length && e.every((function(e, n) {
-                        return gn.compareField(e, t[n])
+                        return On.compareField(e, t[n])
                     }))
                 }
             }, {
                 key: "compareField",
                 value: function(e, t) {
-                    return e === t || t instanceof e.constructor && e.name === t.name && e.nullable === t.nullable && gn.visit(e.type, t.type)
+                    return e === t || t instanceof e.constructor && e.name === t.name && e.nullable === t.nullable && On.visit(e.type, t.type)
                 }
             }]), n
-        }(on);
+        }(sn);
 
-        function sn(e, t) {
+        function hn(e, t) {
             return t instanceof e.constructor
         }
 
-        function ln(e, t) {
-            return e === t || sn(e, t)
+        function dn(e, t) {
+            return e === t || hn(e, t)
         }
 
-        function fn(e, t) {
-            return e === t || sn(e, t) && e.bitWidth === t.bitWidth && e.isSigned === t.isSigned
+        function pn(e, t) {
+            return e === t || hn(e, t) && e.bitWidth === t.bitWidth && e.isSigned === t.isSigned
         }
 
-        function hn(e, t) {
-            return e === t || sn(e, t) && e.precision === t.precision
+        function yn(e, t) {
+            return e === t || hn(e, t) && e.precision === t.precision
         }
 
-        function dn(e, t) {
-            return e === t || sn(e, t) && e.unit === t.unit
+        function vn(e, t) {
+            return e === t || hn(e, t) && e.unit === t.unit
         }
 
-        function pn(e, t) {
-            return e === t || sn(e, t) && e.unit === t.unit && e.timezone === t.timezone
+        function bn(e, t) {
+            return e === t || hn(e, t) && e.unit === t.unit && e.timezone === t.timezone
         }
 
-        function yn(e, t) {
-            return e === t || sn(e, t) && e.unit === t.unit && e.bitWidth === t.bitWidth
+        function mn(e, t) {
+            return e === t || hn(e, t) && e.unit === t.unit && e.bitWidth === t.bitWidth
         }
 
-        function vn(e, t) {
-            return e === t || sn(e, t) && e.mode === t.mode && e.typeIds.every((function(e, n) {
+        function gn(e, t) {
+            return e === t || hn(e, t) && e.mode === t.mode && e.typeIds.every((function(e, n) {
                 return e === t.typeIds[n]
-            })) && gn.compareFields(e.children, t.children)
+            })) && On.compareFields(e.children, t.children)
         }
 
-        function bn(e, t) {
-            return e === t || sn(e, t) && e.unit === t.unit
+        function kn(e, t) {
+            return e === t || hn(e, t) && e.unit === t.unit
         }
-        cn.prototype.visitNull = ln, cn.prototype.visitBool = ln, cn.prototype.visitInt = fn, cn.prototype.visitInt8 = fn, cn.prototype.visitInt16 = fn, cn.prototype.visitInt32 = fn, cn.prototype.visitInt64 = fn, cn.prototype.visitUint8 = fn, cn.prototype.visitUint16 = fn, cn.prototype.visitUint32 = fn, cn.prototype.visitUint64 = fn, cn.prototype.visitFloat = hn, cn.prototype.visitFloat16 = hn, cn.prototype.visitFloat32 = hn, cn.prototype.visitFloat64 = hn, cn.prototype.visitUtf8 = ln, cn.prototype.visitBinary = ln, cn.prototype.visitFixedSizeBinary = function(e, t) {
-            return e === t || sn(e, t) && e.byteWidth === t.byteWidth
-        }, cn.prototype.visitDate = dn, cn.prototype.visitDateDay = dn, cn.prototype.visitDateMillisecond = dn, cn.prototype.visitTimestamp = pn, cn.prototype.visitTimestampSecond = pn, cn.prototype.visitTimestampMillisecond = pn, cn.prototype.visitTimestampMicrosecond = pn, cn.prototype.visitTimestampNanosecond = pn, cn.prototype.visitTime = yn, cn.prototype.visitTimeSecond = yn, cn.prototype.visitTimeMillisecond = yn, cn.prototype.visitTimeMicrosecond = yn, cn.prototype.visitTimeNanosecond = yn, cn.prototype.visitDecimal = ln, cn.prototype.visitList = function(e, t) {
-            return e === t || sn(e, t) && e.children.length === t.children.length && gn.compareFields(e.children, t.children)
-        }, cn.prototype.visitStruct = function(e, t) {
-            return e === t || sn(e, t) && e.children.length === t.children.length && gn.compareFields(e.children, t.children)
-        }, cn.prototype.visitUnion = vn, cn.prototype.visitDenseUnion = vn, cn.prototype.visitSparseUnion = vn, cn.prototype.visitDictionary = function(e, t) {
-            return e === t || sn(e, t) && e.id === t.id && e.isOrdered === t.isOrdered && gn.visit(e.indices, t.indices) && gn.visit(e.dictionary, t.dictionary)
-        }, cn.prototype.visitInterval = bn, cn.prototype.visitIntervalDayTime = bn, cn.prototype.visitIntervalYearMonth = bn, cn.prototype.visitFixedSizeList = function(e, t) {
-            return e === t || sn(e, t) && e.listSize === t.listSize && e.children.length === t.children.length && gn.compareFields(e.children, t.children)
-        }, cn.prototype.visitMap = function(e, t) {
-            return e === t || sn(e, t) && e.keysSorted === t.keysSorted && e.children.length === t.children.length && gn.compareFields(e.children, t.children)
+        fn.prototype.visitNull = dn, fn.prototype.visitBool = dn, fn.prototype.visitInt = pn, fn.prototype.visitInt8 = pn, fn.prototype.visitInt16 = pn, fn.prototype.visitInt32 = pn, fn.prototype.visitInt64 = pn, fn.prototype.visitUint8 = pn, fn.prototype.visitUint16 = pn, fn.prototype.visitUint32 = pn, fn.prototype.visitUint64 = pn, fn.prototype.visitFloat = yn, fn.prototype.visitFloat16 = yn, fn.prototype.visitFloat32 = yn, fn.prototype.visitFloat64 = yn, fn.prototype.visitUtf8 = dn, fn.prototype.visitBinary = dn, fn.prototype.visitFixedSizeBinary = function(e, t) {
+            return e === t || hn(e, t) && e.byteWidth === t.byteWidth
+        }, fn.prototype.visitDate = vn, fn.prototype.visitDateDay = vn, fn.prototype.visitDateMillisecond = vn, fn.prototype.visitTimestamp = bn, fn.prototype.visitTimestampSecond = bn, fn.prototype.visitTimestampMillisecond = bn, fn.prototype.visitTimestampMicrosecond = bn, fn.prototype.visitTimestampNanosecond = bn, fn.prototype.visitTime = mn, fn.prototype.visitTimeSecond = mn, fn.prototype.visitTimeMillisecond = mn, fn.prototype.visitTimeMicrosecond = mn, fn.prototype.visitTimeNanosecond = mn, fn.prototype.visitDecimal = dn, fn.prototype.visitList = function(e, t) {
+            return e === t || hn(e, t) && e.children.length === t.children.length && On.compareFields(e.children, t.children)
+        }, fn.prototype.visitStruct = function(e, t) {
+            return e === t || hn(e, t) && e.children.length === t.children.length && On.compareFields(e.children, t.children)
+        }, fn.prototype.visitUnion = gn, fn.prototype.visitDenseUnion = gn, fn.prototype.visitSparseUnion = gn, fn.prototype.visitDictionary = function(e, t) {
+            return e === t || hn(e, t) && e.id === t.id && e.isOrdered === t.isOrdered && On.visit(e.indices, t.indices) && On.visit(e.dictionary, t.dictionary)
+        }, fn.prototype.visitInterval = kn, fn.prototype.visitIntervalDayTime = kn, fn.prototype.visitIntervalYearMonth = kn, fn.prototype.visitFixedSizeList = function(e, t) {
+            return e === t || hn(e, t) && e.listSize === t.listSize && e.children.length === t.children.length && On.compareFields(e.children, t.children)
+        }, fn.prototype.visitMap = function(e, t) {
+            return e === t || hn(e, t) && e.keysSorted === t.keysSorted && e.children.length === t.children.length && On.compareFields(e.children, t.children)
         };
-        var mn, gn = new cn,
-            kn = function() {
+        var wn, On = new fn,
+            _n = function() {
                 function e() {
                     Object(D.a)(this, e)
                 }
                 return Object(M.a)(e, [{
                     key: "typeId",
                     get: function() {
-                        return Ut.NONE
+                        return Vt.NONE
                     }
                 }, {
                     key: "compareTo",
                     value: function(e) {
-                        return gn.visit(this, e)
+                        return On.visit(this, e)
                     }
                 }], [{
                     key: "isNull",
                     value: function(e) {
-                        return e && e.typeId === Ut.Null
+                        return e && e.typeId === Vt.Null
                     }
                 }, {
                     key: "isInt",
                     value: function(e) {
-                        return e && e.typeId === Ut.Int
+                        return e && e.typeId === Vt.Int
                     }
                 }, {
                     key: "isFloat",
                     value: function(e) {
-                        return e && e.typeId === Ut.Float
+                        return e && e.typeId === Vt.Float
                     }
                 }, {
                     key: "isBinary",
                     value: function(e) {
-                        return e && e.typeId === Ut.Binary
+                        return e && e.typeId === Vt.Binary
                     }
                 }, {
                     key: "isUtf8",
                     value: function(e) {
-                        return e && e.typeId === Ut.Utf8
+                        return e && e.typeId === Vt.Utf8
                     }
                 }, {
                     key: "isBool",
                     value: function(e) {
-                        return e && e.typeId === Ut.Bool
+                        return e && e.typeId === Vt.Bool
                     }
                 }, {
                     key: "isDecimal",
                     value: function(e) {
-                        return e && e.typeId === Ut.Decimal
+                        return e && e.typeId === Vt.Decimal
                     }
                 }, {
                     key: "isDate",
                     value: function(e) {
-                        return e && e.typeId === Ut.Date
+                        return e && e.typeId === Vt.Date
                     }
                 }, {
                     key: "isTime",
                     value: function(e) {
-                        return e && e.typeId === Ut.Time
+                        return e && e.typeId === Vt.Time
                     }
                 }, {
                     key: "isTimestamp",
                     value: function(e) {
-                        return e && e.typeId === Ut.Timestamp
+                        return e && e.typeId === Vt.Timestamp
                     }
                 }, {
                     key: "isInterval",
                     value: function(e) {
-                        return e && e.typeId === Ut.Interval
+                        return e && e.typeId === Vt.Interval
                     }
                 }, {
                     key: "isList",
                     value: function(e) {
-                        return e && e.typeId === Ut.List
+                        return e && e.typeId === Vt.List
                     }
                 }, {
                     key: "isStruct",
                     value: function(e) {
-                        return e && e.typeId === Ut.Struct
+                        return e && e.typeId === Vt.Struct
                     }
                 }, {
                     key: "isUnion",
                     value: function(e) {
-                        return e && e.typeId === Ut.Union
+                        return e && e.typeId === Vt.Union
                     }
                 }, {
                     key: "isFixedSizeBinary",
                     value: function(e) {
-                        return e && e.typeId === Ut.FixedSizeBinary
+                        return e && e.typeId === Vt.FixedSizeBinary
                     }
                 }, {
                     key: "isFixedSizeList",
                     value: function(e) {
-                        return e && e.typeId === Ut.FixedSizeList
+                        return e && e.typeId === Vt.FixedSizeList
                     }
                 }, {
                     key: "isMap",
                     value: function(e) {
-                        return e && e.typeId === Ut.Map
+                        return e && e.typeId === Vt.Map
                     }
                 }, {
                     key: "isDictionary",
                     value: function(e) {
-                        return e && e.typeId === Ut.Dictionary
+                        return e && e.typeId === Vt.Dictionary
                     }
                 }]), e
             }();
-        kn[Symbol.toStringTag] = ((mn = kn.prototype).children = null, mn.ArrayType = Array, mn[Symbol.toStringTag] = "DataType");
-        var wn = function(e) {
+        _n[Symbol.toStringTag] = ((wn = _n.prototype).children = null, wn.ArrayType = Array, wn[Symbol.toStringTag] = "DataType");
+        var jn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n() {
                 return Object(D.a)(this, n), t.apply(this, arguments)
             }
             return Object(M.a)(n, [{
                 key: "toString",
                 value: function() {
                     return "Null"
                 }
             }, {
                 key: "typeId",
                 get: function() {
-                    return Ut.Null
+                    return Vt.Null
                 }
             }]), n
-        }(kn);
-        wn[Symbol.toStringTag] = function(e) {
+        }(_n);
+        jn[Symbol.toStringTag] = function(e) {
             return e[Symbol.toStringTag] = "Null"
-        }(wn.prototype);
-        var On = function(e) {
+        }(jn.prototype);
+        var xn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n(e, r) {
                 var i;
                 return Object(D.a)(this, n), (i = t.call(this)).isSigned = e, i.bitWidth = r, i
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.Int
+                    return Vt.Int
                 }
             }, {
                 key: "ArrayType",
                 get: function() {
                     switch (this.bitWidth) {
                         case 8:
                             return this.isSigned ? Int8Array : Uint8Array;
@@ -7138,388 +7152,388 @@
                 }
             }, {
                 key: "toString",
                 value: function() {
                     return "".concat(this.isSigned ? "I" : "Ui", "nt").concat(this.bitWidth)
                 }
             }]), n
-        }(kn);
-        On[Symbol.toStringTag] = function(e) {
+        }(_n);
+        xn[Symbol.toStringTag] = function(e) {
             return e.isSigned = null, e.bitWidth = null, e[Symbol.toStringTag] = "Int"
-        }(On.prototype);
-        var _n = function(e) {
+        }(xn.prototype);
+        var Tn = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.call(this, !0, 8)
                 }
                 return Object(M.a)(n)
-            }(On),
-            jn = function(e) {
+            }(xn),
+            Sn = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.call(this, !0, 16)
                 }
                 return Object(M.a)(n)
-            }(On),
-            xn = function(e) {
+            }(xn),
+            In = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.call(this, !0, 32)
                 }
                 return Object(M.a)(n)
-            }(On),
-            Tn = function(e) {
+            }(xn),
+            En = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.call(this, !0, 64)
                 }
                 return Object(M.a)(n)
-            }(On),
-            Sn = function(e) {
+            }(xn),
+            An = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.call(this, !1, 8)
                 }
                 return Object(M.a)(n)
-            }(On),
-            In = function(e) {
+            }(xn),
+            Cn = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.call(this, !1, 16)
                 }
                 return Object(M.a)(n)
-            }(On),
-            En = function(e) {
+            }(xn),
+            Bn = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.call(this, !1, 32)
                 }
                 return Object(M.a)(n)
-            }(On),
-            An = function(e) {
+            }(xn),
+            Dn = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.call(this, !1, 64)
                 }
                 return Object(M.a)(n)
-            }(On);
-        Object.defineProperty(_n.prototype, "ArrayType", {
+            }(xn);
+        Object.defineProperty(Tn.prototype, "ArrayType", {
             value: Int8Array
-        }), Object.defineProperty(jn.prototype, "ArrayType", {
+        }), Object.defineProperty(Sn.prototype, "ArrayType", {
             value: Int16Array
-        }), Object.defineProperty(xn.prototype, "ArrayType", {
+        }), Object.defineProperty(In.prototype, "ArrayType", {
             value: Int32Array
-        }), Object.defineProperty(Tn.prototype, "ArrayType", {
+        }), Object.defineProperty(En.prototype, "ArrayType", {
             value: Int32Array
-        }), Object.defineProperty(Sn.prototype, "ArrayType", {
+        }), Object.defineProperty(An.prototype, "ArrayType", {
             value: Uint8Array
-        }), Object.defineProperty(In.prototype, "ArrayType", {
+        }), Object.defineProperty(Cn.prototype, "ArrayType", {
             value: Uint16Array
-        }), Object.defineProperty(En.prototype, "ArrayType", {
+        }), Object.defineProperty(Bn.prototype, "ArrayType", {
             value: Uint32Array
-        }), Object.defineProperty(An.prototype, "ArrayType", {
+        }), Object.defineProperty(Dn.prototype, "ArrayType", {
             value: Uint32Array
         });
-        var Cn = function(e) {
+        var Mn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n(e) {
                 var r;
                 return Object(D.a)(this, n), (r = t.call(this)).precision = e, r
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.Float
+                    return Vt.Float
                 }
             }, {
                 key: "ArrayType",
                 get: function() {
                     switch (this.precision) {
-                        case Wt.HALF:
+                        case $t.HALF:
                             return Uint16Array;
-                        case Wt.SINGLE:
+                        case $t.SINGLE:
                             return Float32Array;
-                        case Wt.DOUBLE:
+                        case $t.DOUBLE:
                             return Float64Array
                     }
                     throw new Error("Unrecognized ".concat(this[Symbol.toStringTag], " type"))
                 }
             }, {
                 key: "toString",
                 value: function() {
                     return "Float".concat(this.precision << 5 || 16)
                 }
             }]), n
-        }(kn);
-        Cn[Symbol.toStringTag] = function(e) {
+        }(_n);
+        Mn[Symbol.toStringTag] = function(e) {
             return e.precision = null, e[Symbol.toStringTag] = "Float"
-        }(Cn.prototype);
-        var Bn = function(e) {
+        }(Mn.prototype);
+        var Ln = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
-                    return Object(D.a)(this, n), t.call(this, Wt.HALF)
+                    return Object(D.a)(this, n), t.call(this, $t.HALF)
                 }
                 return Object(M.a)(n)
-            }(Cn),
-            Dn = function(e) {
+            }(Mn),
+            Fn = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
-                    return Object(D.a)(this, n), t.call(this, Wt.SINGLE)
+                    return Object(D.a)(this, n), t.call(this, $t.SINGLE)
                 }
                 return Object(M.a)(n)
-            }(Cn),
-            Mn = function(e) {
+            }(Mn),
+            Nn = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
-                    return Object(D.a)(this, n), t.call(this, Wt.DOUBLE)
+                    return Object(D.a)(this, n), t.call(this, $t.DOUBLE)
                 }
                 return Object(M.a)(n)
-            }(Cn);
-        Object.defineProperty(Bn.prototype, "ArrayType", {
+            }(Mn);
+        Object.defineProperty(Ln.prototype, "ArrayType", {
             value: Uint16Array
-        }), Object.defineProperty(Dn.prototype, "ArrayType", {
+        }), Object.defineProperty(Fn.prototype, "ArrayType", {
             value: Float32Array
-        }), Object.defineProperty(Mn.prototype, "ArrayType", {
+        }), Object.defineProperty(Nn.prototype, "ArrayType", {
             value: Float64Array
         });
-        var Ln = function(e) {
+        var Pn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n() {
                 return Object(D.a)(this, n), t.call(this)
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.Binary
+                    return Vt.Binary
                 }
             }, {
                 key: "toString",
                 value: function() {
                     return "Binary"
                 }
             }]), n
-        }(kn);
-        Ln[Symbol.toStringTag] = function(e) {
+        }(_n);
+        Pn[Symbol.toStringTag] = function(e) {
             return e.ArrayType = Uint8Array, e[Symbol.toStringTag] = "Binary"
-        }(Ln.prototype);
-        var Fn = function(e) {
+        }(Pn.prototype);
+        var Un = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n() {
                 return Object(D.a)(this, n), t.call(this)
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.Utf8
+                    return Vt.Utf8
                 }
             }, {
                 key: "toString",
                 value: function() {
                     return "Utf8"
                 }
             }]), n
-        }(kn);
-        Fn[Symbol.toStringTag] = function(e) {
+        }(_n);
+        Un[Symbol.toStringTag] = function(e) {
             return e.ArrayType = Uint8Array, e[Symbol.toStringTag] = "Utf8"
-        }(Fn.prototype);
-        var Nn = function(e) {
+        }(Un.prototype);
+        var Rn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n() {
                 return Object(D.a)(this, n), t.call(this)
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.Bool
+                    return Vt.Bool
                 }
             }, {
                 key: "toString",
                 value: function() {
                     return "Bool"
                 }
             }]), n
-        }(kn);
-        Nn[Symbol.toStringTag] = function(e) {
+        }(_n);
+        Rn[Symbol.toStringTag] = function(e) {
             return e.ArrayType = Uint8Array, e[Symbol.toStringTag] = "Bool"
-        }(Nn.prototype);
-        var Pn = function(e) {
+        }(Rn.prototype);
+        var zn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n(e, r) {
                 var i;
                 return Object(D.a)(this, n), (i = t.call(this)).scale = e, i.precision = r, i
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.Decimal
+                    return Vt.Decimal
                 }
             }, {
                 key: "toString",
                 value: function() {
                     return "Decimal[".concat(this.precision, "e").concat(this.scale > 0 ? "+" : "").concat(this.scale, "]")
                 }
             }]), n
-        }(kn);
-        Pn[Symbol.toStringTag] = function(e) {
+        }(_n);
+        zn[Symbol.toStringTag] = function(e) {
             return e.scale = null, e.precision = null, e.ArrayType = Uint32Array, e[Symbol.toStringTag] = "Decimal"
-        }(Pn.prototype);
-        var Un = function(e) {
+        }(zn.prototype);
+        var Vn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n(e) {
                 var r;
                 return Object(D.a)(this, n), (r = t.call(this)).unit = e, r
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.Date
+                    return Vt.Date
                 }
             }, {
                 key: "toString",
                 value: function() {
-                    return "Date".concat(32 * (this.unit + 1), "<").concat(zt[this.unit], ">")
+                    return "Date".concat(32 * (this.unit + 1), "<").concat(Yt[this.unit], ">")
                 }
             }]), n
-        }(kn);
-        Un[Symbol.toStringTag] = function(e) {
+        }(_n);
+        Vn[Symbol.toStringTag] = function(e) {
             return e.unit = null, e.ArrayType = Int32Array, e[Symbol.toStringTag] = "Date"
-        }(Un.prototype);
-        var Rn = function(e) {
+        }(Vn.prototype);
+        var Wn = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
-                    return Object(D.a)(this, n), t.call(this, zt.DAY)
+                    return Object(D.a)(this, n), t.call(this, Yt.DAY)
                 }
                 return Object(M.a)(n)
-            }(Un),
-            zn = function(e) {
+            }(Vn),
+            Yn = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
-                    return Object(D.a)(this, n), t.call(this, zt.MILLISECOND)
+                    return Object(D.a)(this, n), t.call(this, Yt.MILLISECOND)
                 }
                 return Object(M.a)(n)
-            }(Un),
-            Vn = function(e) {
+            }(Vn),
+            Hn = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e, r) {
                     var i;
                     return Object(D.a)(this, n), (i = t.call(this)).unit = e, i.bitWidth = r, i
                 }
                 return Object(M.a)(n, [{
                     key: "typeId",
                     get: function() {
-                        return Ut.Time
+                        return Vt.Time
                     }
                 }, {
                     key: "toString",
                     value: function() {
-                        return "Time".concat(this.bitWidth, "<").concat(Vt[this.unit], ">")
+                        return "Time".concat(this.bitWidth, "<").concat(Ht[this.unit], ">")
                     }
                 }]), n
-            }(kn);
-        Vn[Symbol.toStringTag] = function(e) {
+            }(_n);
+        Hn[Symbol.toStringTag] = function(e) {
             return e.unit = null, e.bitWidth = null, e.ArrayType = Int32Array, e[Symbol.toStringTag] = "Time"
-        }(Vn.prototype);
-        var Wn = function(e) {
+        }(Hn.prototype);
+        var $n = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n(e, r) {
                 var i;
                 return Object(D.a)(this, n), (i = t.call(this)).unit = e, i.timezone = r, i
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.Timestamp
+                    return Vt.Timestamp
                 }
             }, {
                 key: "toString",
                 value: function() {
-                    return "Timestamp<".concat(Vt[this.unit]).concat(this.timezone ? ", ".concat(this.timezone) : "", ">")
+                    return "Timestamp<".concat(Ht[this.unit]).concat(this.timezone ? ", ".concat(this.timezone) : "", ">")
                 }
             }]), n
-        }(kn);
-        Wn[Symbol.toStringTag] = function(e) {
+        }(_n);
+        $n[Symbol.toStringTag] = function(e) {
             return e.unit = null, e.timezone = null, e.ArrayType = Int32Array, e[Symbol.toStringTag] = "Timestamp"
-        }(Wn.prototype);
-        var Yn = function(e) {
+        }($n.prototype);
+        var Kn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n(e) {
                 var r;
                 return Object(D.a)(this, n), (r = t.call(this)).unit = e, r
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.Interval
+                    return Vt.Interval
                 }
             }, {
                 key: "toString",
                 value: function() {
-                    return "Interval<".concat(Ht[this.unit], ">")
+                    return "Interval<".concat(qt[this.unit], ">")
                 }
             }]), n
-        }(kn);
-        Yn[Symbol.toStringTag] = function(e) {
+        }(_n);
+        Kn[Symbol.toStringTag] = function(e) {
             return e.unit = null, e.ArrayType = Int32Array, e[Symbol.toStringTag] = "Interval"
-        }(Yn.prototype);
-        var Hn = function(e) {
+        }(Kn.prototype);
+        var qn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n(e) {
                 var r;
                 return Object(D.a)(this, n), (r = t.call(this)).children = [e], r
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.List
+                    return Vt.List
                 }
             }, {
                 key: "toString",
                 value: function() {
                     return "List<".concat(this.valueType, ">")
                 }
             }, {
@@ -7534,105 +7548,105 @@
                 }
             }, {
                 key: "ArrayType",
                 get: function() {
                     return this.valueType.ArrayType
                 }
             }]), n
-        }(kn);
-        Hn[Symbol.toStringTag] = function(e) {
+        }(_n);
+        qn[Symbol.toStringTag] = function(e) {
             return e.children = null, e[Symbol.toStringTag] = "List"
-        }(Hn.prototype);
-        var $n = function(e) {
+        }(qn.prototype);
+        var Qn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n(e) {
                 var r;
                 return Object(D.a)(this, n), (r = t.call(this)).children = e, r
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.Struct
+                    return Vt.Struct
                 }
             }, {
                 key: "toString",
                 value: function() {
                     return "Struct<{".concat(this.children.map((function(e) {
                         return "".concat(e.name, ":").concat(e.type)
                     })).join(", "), "}>")
                 }
             }]), n
-        }(kn);
-        $n[Symbol.toStringTag] = function(e) {
+        }(_n);
+        Qn[Symbol.toStringTag] = function(e) {
             return e.children = null, e[Symbol.toStringTag] = "Struct"
-        }($n.prototype);
-        var Kn = function(e) {
+        }(Qn.prototype);
+        var Gn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n(e, r, i) {
                 var a;
                 return Object(D.a)(this, n), (a = t.call(this)).mode = e, a.children = i, a.typeIds = r = Int32Array.from(r), a.typeIdToChildIndex = r.reduce((function(e, t, n) {
                     return (e[t] = n) && e || e
                 }), Object.create(null)), a
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.Union
+                    return Vt.Union
                 }
             }, {
                 key: "toString",
                 value: function() {
                     return "".concat(this[Symbol.toStringTag], "<").concat(this.children.map((function(e) {
                         return "".concat(e.type)
                     })).join(" | "), ">")
                 }
             }]), n
-        }(kn);
-        Kn[Symbol.toStringTag] = function(e) {
+        }(_n);
+        Gn[Symbol.toStringTag] = function(e) {
             return e.mode = null, e.typeIds = null, e.children = null, e.typeIdToChildIndex = null, e.ArrayType = Int8Array, e[Symbol.toStringTag] = "Union"
-        }(Kn.prototype);
-        var qn = function(e) {
+        }(Gn.prototype);
+        var Xn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n(e) {
                 var r;
                 return Object(D.a)(this, n), (r = t.call(this)).byteWidth = e, r
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.FixedSizeBinary
+                    return Vt.FixedSizeBinary
                 }
             }, {
                 key: "toString",
                 value: function() {
                     return "FixedSizeBinary[".concat(this.byteWidth, "]")
                 }
             }]), n
-        }(kn);
-        qn[Symbol.toStringTag] = function(e) {
+        }(_n);
+        Xn[Symbol.toStringTag] = function(e) {
             return e.byteWidth = null, e.ArrayType = Uint8Array, e[Symbol.toStringTag] = "FixedSizeBinary"
-        }(qn.prototype);
-        var Qn = function(e) {
+        }(Xn.prototype);
+        var Jn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n(e, r) {
                 var i;
                 return Object(D.a)(this, n), (i = t.call(this)).listSize = e, i.children = [r], i
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.FixedSizeList
+                    return Vt.FixedSizeList
                 }
             }, {
                 key: "valueType",
                 get: function() {
                     return this.children[0].type
                 }
             }, {
@@ -7647,30 +7661,30 @@
                 }
             }, {
                 key: "toString",
                 value: function() {
                     return "FixedSizeList[".concat(this.listSize, "]<").concat(this.valueType, ">")
                 }
             }]), n
-        }(kn);
-        Qn[Symbol.toStringTag] = function(e) {
+        }(_n);
+        Jn[Symbol.toStringTag] = function(e) {
             return e.children = null, e.listSize = null, e[Symbol.toStringTag] = "FixedSizeList"
-        }(Qn.prototype);
-        var Gn = function(e) {
+        }(Jn.prototype);
+        var Zn = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n(e) {
                 var r, i = arguments.length > 1 && void 0 !== arguments[1] && arguments[1];
                 return Object(D.a)(this, n), (r = t.call(this)).children = [e], r.keysSorted = i, r
             }
             return Object(M.a)(n, [{
                 key: "typeId",
                 get: function() {
-                    return Ut.Map
+                    return Vt.Map
                 }
             }, {
                 key: "keyType",
                 get: function() {
                     return this.children[0].type.children[0].type
                 }
             }, {
@@ -7682,33 +7696,33 @@
                 key: "toString",
                 value: function() {
                     return "Map<{".concat(this.children[0].type.children.map((function(e) {
                         return "".concat(e.name, ":").concat(e.type)
                     })).join(", "), "}>")
                 }
             }]), n
-        }(kn);
-        Gn[Symbol.toStringTag] = function(e) {
+        }(_n);
+        Zn[Symbol.toStringTag] = function(e) {
             return e.children = null, e.keysSorted = null, e[Symbol.toStringTag] = "Map_"
-        }(Gn.prototype);
-        var Xn, Jn = (Xn = -1, function() {
-                return ++Xn
+        }(Zn.prototype);
+        var er, tr = (er = -1, function() {
+                return ++er
             }),
-            Zn = function(e) {
+            nr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e, r, i, a) {
                     var o;
-                    return Object(D.a)(this, n), (o = t.call(this)).indices = r, o.dictionary = e, o.isOrdered = a || !1, o.id = null == i ? Jn() : "number" === typeof i ? i : i.low, o
+                    return Object(D.a)(this, n), (o = t.call(this)).indices = r, o.dictionary = e, o.isOrdered = a || !1, o.id = null == i ? tr() : "number" === typeof i ? i : i.low, o
                 }
                 return Object(M.a)(n, [{
                     key: "typeId",
                     get: function() {
-                        return Ut.Dictionary
+                        return Vt.Dictionary
                     }
                 }, {
                     key: "children",
                     get: function() {
                         return this.dictionary.children
                     }
                 }, {
@@ -7723,46 +7737,46 @@
                     }
                 }, {
                     key: "toString",
                     value: function() {
                         return "Dictionary<".concat(this.indices, ", ").concat(this.dictionary, ">")
                     }
                 }]), n
-            }(kn);
+            }(_n);
 
-        function er(e) {
+        function rr(e) {
             var t = e;
             switch (e.typeId) {
-                case Ut.Decimal:
+                case Vt.Decimal:
                     return 4;
-                case Ut.Timestamp:
+                case Vt.Timestamp:
                     return 2;
-                case Ut.Date:
-                case Ut.Interval:
+                case Vt.Date:
+                case Vt.Interval:
                     return 1 + t.unit;
-                case Ut.Int:
-                case Ut.Time:
+                case Vt.Int:
+                case Vt.Time:
                     return +(t.bitWidth > 32) + 1;
-                case Ut.FixedSizeList:
+                case Vt.FixedSizeList:
                     return t.listSize;
-                case Ut.FixedSizeBinary:
+                case Vt.FixedSizeBinary:
                     return t.byteWidth;
                 default:
                     return 1
             }
         }
-        Zn[Symbol.toStringTag] = function(e) {
+        nr[Symbol.toStringTag] = function(e) {
             return e.id = null, e.indices = null, e.isOrdered = null, e.dictionary = null, e[Symbol.toStringTag] = "Dictionary"
-        }(Zn.prototype);
-        var tr = function() {
+        }(nr.prototype);
+        var ir = function() {
             function e(t, n, r, i, a, o, u) {
                 var c;
                 Object(D.a)(this, e), this.type = t, this.dictionary = u, this.offset = Math.floor(Math.max(n || 0, 0)), this.length = Math.floor(Math.max(r || 0, 0)), this._nullCount = Math.floor(Math.max(i || 0, -1)), this.childData = (o || []).map((function(t) {
                     return t instanceof e ? t : t.data
-                })), a instanceof e ? (this.stride = a.stride, this.values = a.values, this.typeIds = a.typeIds, this.nullBitmap = a.nullBitmap, this.valueOffsets = a.valueOffsets) : (this.stride = er(t), a && ((c = a[0]) && (this.valueOffsets = c), (c = a[1]) && (this.values = c), (c = a[2]) && (this.nullBitmap = c), (c = a[3]) && (this.typeIds = c)))
+                })), a instanceof e ? (this.stride = a.stride, this.values = a.values, this.typeIds = a.typeIds, this.nullBitmap = a.nullBitmap, this.valueOffsets = a.valueOffsets) : (this.stride = rr(t), a && ((c = a[0]) && (this.valueOffsets = c), (c = a[1]) && (this.values = c), (c = a[2]) && (this.nullBitmap = c), (c = a[3]) && (this.typeIds = c)))
             }
             return Object(M.a)(e, [{
                 key: "typeId",
                 get: function() {
                     return this.type.typeId
                 }
             }, {
@@ -7787,15 +7801,15 @@
                         return e + t.byteLength
                     }), e)
                 }
             }, {
                 key: "nullCount",
                 get: function() {
                     var e, t = this._nullCount;
-                    return t <= -1 && (e = this.nullBitmap) && (this._nullCount = t = this.length - tn(e, this.offset, this.offset + this.length)), t
+                    return t <= -1 && (e = this.nullBitmap) && (this._nullCount = t = this.length - an(e, this.offset, this.offset + this.length)), t
                 }
             }, {
                 key: "clone",
                 value: function(t) {
                     return new e(t, arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.offset, arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : this.length, arguments.length > 3 && void 0 !== arguments[3] ? arguments[3] : this._nullCount, arguments.length > 4 && void 0 !== arguments[4] ? arguments[4] : this, arguments.length > 5 && void 0 !== arguments[5] ? arguments[5] : this.childData, this.dictionary)
                 }
             }, {
@@ -7808,207 +7822,207 @@
                         o = 16 === r ? n : 1,
                         u = this._sliceBuffers(e, t, n, r);
                     return this.clone(this.type, this.offset + e, t, a, u, !i.length || this.valueOffsets ? i : this._sliceChildren(i, o * e, o * t))
                 }
             }, {
                 key: "_changeLengthAndBackfillNullBitmap",
                 value: function(e) {
-                    if (this.typeId === Ut.Null) return this.clone(this.type, 0, e, 0);
+                    if (this.typeId === Vt.Null) return this.clone(this.type, 0, e, 0);
                     var t = this.length,
                         n = this.nullCount,
                         r = new Uint8Array((e + 63 & -64) >> 3).fill(255, 0, t >> 3);
-                    r[t >> 3] = (1 << t - (-8 & t)) - 1, n > 0 && r.set(Jt(this.offset, t, this.nullBitmap), 0);
+                    r[t >> 3] = (1 << t - (-8 & t)) - 1, n > 0 && r.set(tn(this.offset, t, this.nullBitmap), 0);
                     var i = this.buffers;
-                    return i[Rt.VALIDITY] = r, this.clone(this.type, 0, e, n + (e - t), i)
+                    return i[Wt.VALIDITY] = r, this.clone(this.type, 0, e, n + (e - t), i)
                 }
             }, {
                 key: "_sliceBuffers",
                 value: function(e, t, n, r) {
                     var i, a = this.buffers;
-                    return (i = a[Rt.TYPE]) && (a[Rt.TYPE] = i.subarray(e, e + t)), (i = a[Rt.OFFSET]) && (a[Rt.OFFSET] = i.subarray(e, e + t + 1)) || (i = a[Rt.DATA]) && (a[Rt.DATA] = 6 === r ? i : i.subarray(n * e, n * (e + t))), a
+                    return (i = a[Wt.TYPE]) && (a[Wt.TYPE] = i.subarray(e, e + t)), (i = a[Wt.OFFSET]) && (a[Wt.OFFSET] = i.subarray(e, e + t + 1)) || (i = a[Wt.DATA]) && (a[Wt.DATA] = 6 === r ? i : i.subarray(n * e, n * (e + t))), a
                 }
             }, {
                 key: "_sliceChildren",
                 value: function(e, t, n) {
                     return e.map((function(e) {
                         return e.slice(t, n)
                     }))
                 }
             }], [{
                 key: "new",
                 value: function(t, n, r, i, a, o, u) {
                     switch (a instanceof e ? a = a.buffers : a || (a = []), t.typeId) {
-                        case Ut.Null:
+                        case Vt.Null:
                             return e.Null(t, n, r);
-                        case Ut.Int:
-                            return e.Int(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.DATA] || []);
-                        case Ut.Dictionary:
-                            return e.Dictionary(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.DATA] || [], u);
-                        case Ut.Float:
-                            return e.Float(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.DATA] || []);
-                        case Ut.Bool:
-                            return e.Bool(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.DATA] || []);
-                        case Ut.Decimal:
-                            return e.Decimal(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.DATA] || []);
-                        case Ut.Date:
-                            return e.Date(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.DATA] || []);
-                        case Ut.Time:
-                            return e.Time(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.DATA] || []);
-                        case Ut.Timestamp:
-                            return e.Timestamp(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.DATA] || []);
-                        case Ut.Interval:
-                            return e.Interval(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.DATA] || []);
-                        case Ut.FixedSizeBinary:
-                            return e.FixedSizeBinary(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.DATA] || []);
-                        case Ut.Binary:
-                            return e.Binary(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.OFFSET] || [], a[Rt.DATA] || []);
-                        case Ut.Utf8:
-                            return e.Utf8(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.OFFSET] || [], a[Rt.DATA] || []);
-                        case Ut.List:
-                            return e.List(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.OFFSET] || [], (o || [])[0]);
-                        case Ut.FixedSizeList:
-                            return e.FixedSizeList(t, n, r, i || 0, a[Rt.VALIDITY], (o || [])[0]);
-                        case Ut.Struct:
-                            return e.Struct(t, n, r, i || 0, a[Rt.VALIDITY], o || []);
-                        case Ut.Map:
-                            return e.Map(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.OFFSET] || [], (o || [])[0]);
-                        case Ut.Union:
-                            return e.Union(t, n, r, i || 0, a[Rt.VALIDITY], a[Rt.TYPE] || [], a[Rt.OFFSET] || o, o)
+                        case Vt.Int:
+                            return e.Int(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.DATA] || []);
+                        case Vt.Dictionary:
+                            return e.Dictionary(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.DATA] || [], u);
+                        case Vt.Float:
+                            return e.Float(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.DATA] || []);
+                        case Vt.Bool:
+                            return e.Bool(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.DATA] || []);
+                        case Vt.Decimal:
+                            return e.Decimal(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.DATA] || []);
+                        case Vt.Date:
+                            return e.Date(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.DATA] || []);
+                        case Vt.Time:
+                            return e.Time(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.DATA] || []);
+                        case Vt.Timestamp:
+                            return e.Timestamp(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.DATA] || []);
+                        case Vt.Interval:
+                            return e.Interval(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.DATA] || []);
+                        case Vt.FixedSizeBinary:
+                            return e.FixedSizeBinary(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.DATA] || []);
+                        case Vt.Binary:
+                            return e.Binary(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.OFFSET] || [], a[Wt.DATA] || []);
+                        case Vt.Utf8:
+                            return e.Utf8(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.OFFSET] || [], a[Wt.DATA] || []);
+                        case Vt.List:
+                            return e.List(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.OFFSET] || [], (o || [])[0]);
+                        case Vt.FixedSizeList:
+                            return e.FixedSizeList(t, n, r, i || 0, a[Wt.VALIDITY], (o || [])[0]);
+                        case Vt.Struct:
+                            return e.Struct(t, n, r, i || 0, a[Wt.VALIDITY], o || []);
+                        case Vt.Map:
+                            return e.Map(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.OFFSET] || [], (o || [])[0]);
+                        case Vt.Union:
+                            return e.Union(t, n, r, i || 0, a[Wt.VALIDITY], a[Wt.TYPE] || [], a[Wt.OFFSET] || o, o)
                     }
                     throw new Error("Unrecognized typeId ".concat(t.typeId))
                 }
             }, {
                 key: "Null",
                 value: function(t, n, r) {
                     return new e(t, n, r, 0)
                 }
             }, {
                 key: "Int",
                 value: function(t, n, r, i, a, o) {
-                    return new e(t, n, r, i, [void 0, Fe(t.ArrayType, o), ze(a)])
+                    return new e(t, n, r, i, [void 0, Ue(t.ArrayType, o), Ye(a)])
                 }
             }, {
                 key: "Dictionary",
                 value: function(t, n, r, i, a, o, u) {
-                    return new e(t, n, r, i, [void 0, Fe(t.indices.ArrayType, o), ze(a)], [], u)
+                    return new e(t, n, r, i, [void 0, Ue(t.indices.ArrayType, o), Ye(a)], [], u)
                 }
             }, {
                 key: "Float",
                 value: function(t, n, r, i, a, o) {
-                    return new e(t, n, r, i, [void 0, Fe(t.ArrayType, o), ze(a)])
+                    return new e(t, n, r, i, [void 0, Ue(t.ArrayType, o), Ye(a)])
                 }
             }, {
                 key: "Bool",
                 value: function(t, n, r, i, a, o) {
-                    return new e(t, n, r, i, [void 0, Fe(t.ArrayType, o), ze(a)])
+                    return new e(t, n, r, i, [void 0, Ue(t.ArrayType, o), Ye(a)])
                 }
             }, {
                 key: "Decimal",
                 value: function(t, n, r, i, a, o) {
-                    return new e(t, n, r, i, [void 0, Fe(t.ArrayType, o), ze(a)])
+                    return new e(t, n, r, i, [void 0, Ue(t.ArrayType, o), Ye(a)])
                 }
             }, {
                 key: "Date",
                 value: function(t, n, r, i, a, o) {
-                    return new e(t, n, r, i, [void 0, Fe(t.ArrayType, o), ze(a)])
+                    return new e(t, n, r, i, [void 0, Ue(t.ArrayType, o), Ye(a)])
                 }
             }, {
                 key: "Time",
                 value: function(t, n, r, i, a, o) {
-                    return new e(t, n, r, i, [void 0, Fe(t.ArrayType, o), ze(a)])
+                    return new e(t, n, r, i, [void 0, Ue(t.ArrayType, o), Ye(a)])
                 }
             }, {
                 key: "Timestamp",
                 value: function(t, n, r, i, a, o) {
-                    return new e(t, n, r, i, [void 0, Fe(t.ArrayType, o), ze(a)])
+                    return new e(t, n, r, i, [void 0, Ue(t.ArrayType, o), Ye(a)])
                 }
             }, {
                 key: "Interval",
                 value: function(t, n, r, i, a, o) {
-                    return new e(t, n, r, i, [void 0, Fe(t.ArrayType, o), ze(a)])
+                    return new e(t, n, r, i, [void 0, Ue(t.ArrayType, o), Ye(a)])
                 }
             }, {
                 key: "FixedSizeBinary",
                 value: function(t, n, r, i, a, o) {
-                    return new e(t, n, r, i, [void 0, Fe(t.ArrayType, o), ze(a)])
+                    return new e(t, n, r, i, [void 0, Ue(t.ArrayType, o), Ye(a)])
                 }
             }, {
                 key: "Binary",
                 value: function(t, n, r, i, a, o, u) {
-                    return new e(t, n, r, i, [Ue(o), ze(u), ze(a)])
+                    return new e(t, n, r, i, [Ve(o), Ye(u), Ye(a)])
                 }
             }, {
                 key: "Utf8",
                 value: function(t, n, r, i, a, o, u) {
-                    return new e(t, n, r, i, [Ue(o), ze(u), ze(a)])
+                    return new e(t, n, r, i, [Ve(o), Ye(u), Ye(a)])
                 }
             }, {
                 key: "List",
                 value: function(t, n, r, i, a, o, u) {
-                    return new e(t, n, r, i, [Ue(o), void 0, ze(a)], [u])
+                    return new e(t, n, r, i, [Ve(o), void 0, Ye(a)], [u])
                 }
             }, {
                 key: "FixedSizeList",
                 value: function(t, n, r, i, a, o) {
-                    return new e(t, n, r, i, [void 0, void 0, ze(a)], [o])
+                    return new e(t, n, r, i, [void 0, void 0, Ye(a)], [o])
                 }
             }, {
                 key: "Struct",
                 value: function(t, n, r, i, a, o) {
-                    return new e(t, n, r, i, [void 0, void 0, ze(a)], o)
+                    return new e(t, n, r, i, [void 0, void 0, Ye(a)], o)
                 }
             }, {
                 key: "Map",
                 value: function(t, n, r, i, a, o, u) {
-                    return new e(t, n, r, i, [Ue(o), void 0, ze(a)], [u])
+                    return new e(t, n, r, i, [Ve(o), void 0, Ye(a)], [u])
                 }
             }, {
                 key: "Union",
                 value: function(t, n, r, i, a, o, u, c) {
-                    var s = [void 0, void 0, ze(a), Fe(t.ArrayType, o)];
-                    return t.mode === Yt.Sparse ? new e(t, n, r, i, s, u) : (s[Rt.OFFSET] = Ue(u), new e(t, n, r, i, s, c))
+                    var s = [void 0, void 0, Ye(a), Ue(t.ArrayType, o)];
+                    return t.mode === Kt.Sparse ? new e(t, n, r, i, s, u) : (s[Wt.OFFSET] = Ve(u), new e(t, n, r, i, s, c))
                 }
             }]), e
         }();
-        tr.prototype.childData = Object.freeze([]);
-        var nr = void 0;
+        ir.prototype.childData = Object.freeze([]);
+        var ar = void 0;
 
-        function rr(e) {
+        function or(e) {
             if (null === e) return "null";
-            if (e === nr) return "undefined";
+            if (e === ar) return "undefined";
             switch (typeof e) {
                 case "number":
                 case "bigint":
                     return "".concat(e);
                 case "string":
                     return '"'.concat(e, '"')
             }
             return "function" === typeof e[Symbol.toPrimitive] ? e[Symbol.toPrimitive]("string") : ArrayBuffer.isView(e) ? "[".concat(e, "]") : JSON.stringify(e)
         }
 
-        function ir(e) {
+        function ur(e) {
             if (!e || e.length <= 0) return function(e) {
                 return !0
             };
             var t = "",
                 n = e.filter((function(e) {
                     return e === e
                 }));
             return n.length > 0 && (t = "\n    switch (x) {".concat(n.map((function(e) {
                 return "\n        case ".concat(function(e) {
-                    if ("bigint" !== typeof e) return rr(e);
-                    if (de) return "".concat(rr(e), "n");
-                    return '"'.concat(rr(e), '"')
+                    if ("bigint" !== typeof e) return or(e);
+                    if (pe) return "".concat(or(e), "n");
+                    return '"'.concat(or(e), '"')
                 }(e), ":")
             })).join(""), "\n            return false;\n    }")), e.length !== n.length && (t = "if (x !== x) return false;\n".concat(t)), new Function("x", "".concat(t, "\nreturn true;"))
         }
-        var ar = function(e, t) {
+        var cr = function(e, t) {
                 return (e * t + 63 & -64 || 64) / t
             },
-            or = function() {
+            sr = function() {
                 function e(t) {
                     var n = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : 1;
                     Object(D.a)(this, e), this.buffer = t, this.stride = n, this.BYTES_PER_ELEMENT = t.BYTES_PER_ELEMENT, this.ArrayType = t.constructor, this._resize(this.length = t.length / n | 0)
                 }
                 return Object(M.a)(e, [{
                     key: "byteLength",
                     get: function() {
@@ -8038,43 +8052,43 @@
                     key: "reserve",
                     value: function(e) {
                         if (e > 0) {
                             this.length += e;
                             var t = this.stride,
                                 n = this.length * t,
                                 r = this.buffer.length;
-                            n >= r && this._resize(ar(0 === r ? 1 * n : 2 * n, this.BYTES_PER_ELEMENT))
+                            n >= r && this._resize(cr(0 === r ? 1 * n : 2 * n, this.BYTES_PER_ELEMENT))
                         }
                         return this
                     }
                 }, {
                     key: "flush",
                     value: function() {
                         var e = arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : this.length;
-                        e = ar(e * this.stride, this.BYTES_PER_ELEMENT);
+                        e = cr(e * this.stride, this.BYTES_PER_ELEMENT);
                         var t = function(e) {
                             var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : 0;
-                            return e.length >= t ? e.subarray(0, t) : Me(new e.constructor(t), e, 0)
+                            return e.length >= t ? e.subarray(0, t) : Ne(new e.constructor(t), e, 0)
                         }(this.buffer, e);
                         return this.clear(), t
                     }
                 }, {
                     key: "clear",
                     value: function() {
                         return this.length = 0, this._resize(0), this
                     }
                 }, {
                     key: "_resize",
                     value: function(e) {
-                        return this.buffer = Me(new this.ArrayType(e), this.buffer)
+                        return this.buffer = Ne(new this.ArrayType(e), this.buffer)
                     }
                 }]), e
             }();
-        or.prototype.offset = 0;
-        var ur = function(e) {
+        sr.prototype.offset = 0;
+        var lr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
@@ -8089,16 +8103,16 @@
                     }
                 }, {
                     key: "set",
                     value: function(e, t) {
                         return this.reserve(e - this.length + 1), this.buffer[e * this.stride] = t, this
                     }
                 }]), n
-            }(or),
-            cr = function(e) {
+            }(sr),
+            fr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     var e, r = arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : new Uint8Array(0);
                     return Object(D.a)(this, n), (e = t.call(this, r, 1 / 8)).numValid = 0, e
                 }
@@ -8120,19 +8134,19 @@
                             i = e % 8,
                             a = n[r] >> i & 1;
                         return t ? 0 === a && (n[r] |= 1 << i, ++this.numValid) : 1 === a && (n[r] &= ~(1 << i), --this.numValid), this
                     }
                 }, {
                     key: "clear",
                     value: function() {
-                        return this.numValid = 0, Ct(Object(At.a)(n.prototype), "clear", this).call(this)
+                        return this.numValid = 0, Mt(Object(Dt.a)(n.prototype), "clear", this).call(this)
                     }
                 }]), n
-            }(ur),
-            sr = function(e) {
+            }(lr),
+            hr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     var e = arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : new Int32Array(1);
                     return Object(D.a)(this, n), t.call(this, e, 1)
                 }
@@ -8148,29 +8162,29 @@
                             r = this.reserve(e - n + 1).buffer;
                         return n < e++ && r.fill(r[n], n, e), r[e] = r[e - 1] + t, this
                     }
                 }, {
                     key: "flush",
                     value: function() {
                         var e = arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : this.length - 1;
-                        return e > this.length && this.set(e - 1, 0), Ct(Object(At.a)(n.prototype), "flush", this).call(this, e + 1)
+                        return e > this.length && this.set(e - 1, 0), Mt(Object(Dt.a)(n.prototype), "flush", this).call(this, e + 1)
                     }
                 }]), n
-            }(ur),
-            lr = function(e) {
+            }(lr),
+            dr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "ArrayType64",
                     get: function() {
-                        return this._ArrayType64 || (this._ArrayType64 = this.buffer instanceof Int32Array ? ye : be)
+                        return this._ArrayType64 || (this._ArrayType64 = this.buffer instanceof Int32Array ? be : ke)
                     }
                 }, {
                     key: "set",
                     value: function(e, t) {
                         switch (this.reserve(e - this.length + 1), typeof t) {
                             case "bigint":
                                 this.buffer64[e] = t;
@@ -8182,30 +8196,30 @@
                                 this.buffer.set(t, e * this.stride)
                         }
                         return this
                     }
                 }, {
                     key: "_resize",
                     value: function(e) {
-                        var t = Ct(Object(At.a)(n.prototype), "_resize", this).call(this, e),
+                        var t = Mt(Object(Dt.a)(n.prototype), "_resize", this).call(this, e),
                             r = t.byteLength / (this.BYTES_PER_ELEMENT * this.stride);
-                        return de && (this.buffer64 = new this.ArrayType64(t.buffer, t.byteOffset, r)), t
+                        return pe && (this.buffer64 = new this.ArrayType64(t.buffer, t.byteOffset, r)), t
                     }
                 }]), n
-            }(or),
-            fr = function() {
+            }(sr),
+            pr = function() {
                 function e(t) {
                     var n = t.type,
                         r = t.nullValues;
-                    Object(D.a)(this, e), this.length = 0, this.finished = !1, this.type = n, this.children = [], this.nullValues = r, this.stride = er(n), this._nulls = new cr, r && r.length > 0 && (this._isValid = ir(r))
+                    Object(D.a)(this, e), this.length = 0, this.finished = !1, this.type = n, this.children = [], this.nullValues = r, this.stride = rr(n), this._nulls = new fr, r && r.length > 0 && (this._isValid = ur(r))
                 }
                 return Object(M.a)(e, [{
                     key: "toVector",
                     value: function() {
-                        return Pt.new(this.flush())
+                        return zt.new(this.flush())
                     }
                 }, {
                     key: "ArrayType",
                     get: function() {
                         return this.type.ArrayType
                     }
                 }, {
@@ -8300,16 +8314,16 @@
                     value: function() {
                         var e = [],
                             t = this._values,
                             n = this._offsets,
                             r = this._typeIds,
                             i = this.length,
                             a = this.nullCount;
-                        r ? (e[Rt.TYPE] = r.flush(i), n && (e[Rt.OFFSET] = n.flush(i))) : n ? (t && (e[Rt.DATA] = t.flush(n.last())), e[Rt.OFFSET] = n.flush(i)) : t && (e[Rt.DATA] = t.flush(i)), a > 0 && (e[Rt.VALIDITY] = this._nulls.flush(i));
-                        var o = tr.new(this.type, 0, i, a, e, this.children.map((function(e) {
+                        r ? (e[Wt.TYPE] = r.flush(i), n && (e[Wt.OFFSET] = n.flush(i))) : n ? (t && (e[Wt.DATA] = t.flush(n.last())), e[Wt.OFFSET] = n.flush(i)) : t && (e[Wt.DATA] = t.flush(i)), a > 0 && (e[Wt.VALIDITY] = this._nulls.flush(i));
+                        var o = ir.new(this.type, 0, i, a, e, this.children.map((function(e) {
                             return e.flush()
                         })));
                         return this.clear(), o
                     }
                 }, {
                     key: "finish",
                     value: function() {
@@ -8347,15 +8361,15 @@
                                 i = void 0 === r ? "bytes" !== n ? 1e3 : Math.pow(2, 14) : r,
                                 a = "bytes" !== n ? "length" : "byteLength";
                             return Object(L.a)().mark((function t(n) {
                                 var r, o, u, c, s;
                                 return Object(L.a)().wrap((function(t) {
                                     for (;;) switch (t.prev = t.next) {
                                         case 0:
-                                            r = 0, o = fr.new(e), u = C(n), t.prev = 3, u.s();
+                                            r = 0, o = pr.new(e), u = C(n), t.prev = 3, u.s();
                                         case 5:
                                             if ((c = u.n()).done) {
                                                 t.next = 14;
                                                 break
                                             }
                                             if (s = c.value, !(o.append(s)[a] >= i)) {
                                                 t.next = 12;
@@ -8403,15 +8417,15 @@
                                 a = "bytes" !== n ? "length" : "byteLength";
                             return function() {
                                 var t = R(Object(L.a)().mark((function t(n) {
                                     var r, o, u, c, s, l, f, h;
                                     return Object(L.a)().wrap((function(t) {
                                         for (;;) switch (t.prev = t.next) {
                                             case 0:
-                                                r = 0, o = fr.new(e), u = !1, c = !1, t.prev = 4, l = V(n);
+                                                r = 0, o = pr.new(e), u = !1, c = !1, t.prev = 4, l = V(n);
                                             case 6:
                                                 return t.next = 8, P(l.next());
                                             case 8:
                                                 if (!(u = !(f = t.sent).done)) {
                                                     t.next = 18;
                                                     break
                                                 }
@@ -8467,93 +8481,93 @@
                                     return t.apply(this, arguments)
                                 }
                             }()
                         }(e)
                     }
                 }]), e
             }();
-        fr.prototype.length = 1, fr.prototype.stride = 1, fr.prototype.children = null, fr.prototype.finished = !1, fr.prototype.nullValues = null, fr.prototype._isValid = function() {
+        pr.prototype.length = 1, pr.prototype.stride = 1, pr.prototype.children = null, pr.prototype.finished = !1, pr.prototype.nullValues = null, pr.prototype._isValid = function() {
             return !0
         };
-        var hr = function(e) {
+        var yr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), (r = t.call(this, e))._values = new ur(new r.ArrayType(0), r.stride), r
+                    return Object(D.a)(this, n), (r = t.call(this, e))._values = new lr(new r.ArrayType(0), r.stride), r
                 }
                 return Object(M.a)(n, [{
                     key: "setValue",
                     value: function(e, t) {
                         var r = this._values;
-                        return r.reserve(e - r.length + 1), Ct(Object(At.a)(n.prototype), "setValue", this).call(this, e, t)
+                        return r.reserve(e - r.length + 1), Mt(Object(Dt.a)(n.prototype), "setValue", this).call(this, e, t)
                     }
                 }]), n
-            }(fr),
-            dr = function(e) {
+            }(pr),
+            vr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), (r = t.call(this, e))._pendingLength = 0, r._offsets = new sr, r
+                    return Object(D.a)(this, n), (r = t.call(this, e))._pendingLength = 0, r._offsets = new hr, r
                 }
                 return Object(M.a)(n, [{
                     key: "setValue",
                     value: function(e, t) {
                         var n = this._pending || (this._pending = new Map),
                             r = n.get(e);
                         r && (this._pendingLength -= r.length), this._pendingLength += t.length, n.set(e, t)
                     }
                 }, {
                     key: "setValid",
                     value: function(e, t) {
-                        return !!Ct(Object(At.a)(n.prototype), "setValid", this).call(this, e, t) || ((this._pending || (this._pending = new Map)).set(e, void 0), !1)
+                        return !!Mt(Object(Dt.a)(n.prototype), "setValid", this).call(this, e, t) || ((this._pending || (this._pending = new Map)).set(e, void 0), !1)
                     }
                 }, {
                     key: "clear",
                     value: function() {
-                        return this._pendingLength = 0, this._pending = void 0, Ct(Object(At.a)(n.prototype), "clear", this).call(this)
+                        return this._pendingLength = 0, this._pending = void 0, Mt(Object(Dt.a)(n.prototype), "clear", this).call(this)
                     }
                 }, {
                     key: "flush",
                     value: function() {
-                        return this._flush(), Ct(Object(At.a)(n.prototype), "flush", this).call(this)
+                        return this._flush(), Mt(Object(Dt.a)(n.prototype), "flush", this).call(this)
                     }
                 }, {
                     key: "finish",
                     value: function() {
-                        return this._flush(), Ct(Object(At.a)(n.prototype), "finish", this).call(this)
+                        return this._flush(), Mt(Object(Dt.a)(n.prototype), "finish", this).call(this)
                     }
                 }, {
                     key: "_flush",
                     value: function() {
                         var e = this._pending,
                             t = this._pendingLength;
                         return this._pendingLength = 0, this._pending = void 0, e && e.size > 0 && this._flushPending(e, t), this
                     }
                 }]), n
-            }(fr);
-        var pr = function(e) {
+            }(pr);
+        var br = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), (r = t.call(this, e))._values = new cr, r
+                    return Object(D.a)(this, n), (r = t.call(this, e))._values = new fr, r
                 }
                 return Object(M.a)(n, [{
                     key: "setValue",
                     value: function(e, t) {
                         this._values.set(e, +t)
                     }
                 }]), n
-            }(fr),
-            yr = function(e) {
+            }(pr),
+            mr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
@@ -8561,65 +8575,65 @@
                     value: function(e, t) {}
                 }, {
                     key: "setValid",
                     value: function(e, t) {
                         return this.length = Math.max(e + 1, this.length), t
                     }
                 }]), n
-            }(fr),
-            vr = function(e) {
+            }(pr),
+            gr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(hr),
-            br = function(e) {
+            }(yr),
+            kr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(vr),
-            mr = function(e) {
+            }(gr),
+            wr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(vr),
-            gr = function(e) {
+            }(gr),
+            Or = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(hr),
-            kr = function(e) {
+            }(yr),
+            _r = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r, i = e.type,
                         a = e.nullValues,
                         o = e.dictionaryHashFunction;
                     return Object(D.a)(this, n), (r = t.call(this, {
-                        type: new Zn(i.dictionary, i.indices, i.id, i.isOrdered)
-                    }))._nulls = null, r._dictionaryOffset = 0, r._keysToIndices = Object.create(null), r.indices = fr.new({
+                        type: new nr(i.dictionary, i.indices, i.id, i.isOrdered)
+                    }))._nulls = null, r._dictionaryOffset = 0, r._keysToIndices = Object.create(null), r.indices = pr.new({
                         type: r.type.indices,
                         nullValues: a
-                    }), r.dictionary = fr.new({
+                    }), r.dictionary = pr.new({
                         type: r.type.dictionary,
                         nullValues: null
                     }), "function" === typeof o && (r.valueToKey = o), r
                 }
                 return Object(M.a)(n, [{
                     key: "values",
                     get: function() {
@@ -8677,535 +8691,535 @@
                             n = this.dictionary.toVector(),
                             r = this.indices.flush().clone(e);
                         return r.dictionary = t ? t.concat(n) : n, this.finished || (this._dictionaryOffset += n.length), this._dictionary = r.dictionary, this.clear(), r
                     }
                 }, {
                     key: "finish",
                     value: function() {
-                        return this.indices.finish(), this.dictionary.finish(), this._dictionaryOffset = 0, this._keysToIndices = Object.create(null), Ct(Object(At.a)(n.prototype), "finish", this).call(this)
+                        return this.indices.finish(), this.dictionary.finish(), this._dictionaryOffset = 0, this._keysToIndices = Object.create(null), Mt(Object(Dt.a)(n.prototype), "finish", this).call(this)
                     }
                 }, {
                     key: "clear",
                     value: function() {
-                        return this.indices.clear(), this.dictionary.clear(), Ct(Object(At.a)(n.prototype), "clear", this).call(this)
+                        return this.indices.clear(), this.dictionary.clear(), Mt(Object(Dt.a)(n.prototype), "clear", this).call(this)
                     }
                 }, {
                     key: "valueToKey",
                     value: function(e) {
                         return "string" === typeof e ? e : "".concat(e)
                     }
                 }]), n
-            }(fr),
-            wr = function(e) {
+            }(pr),
+            jr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(hr),
-            Or = new Float64Array(1),
-            _r = new Uint32Array(Or.buffer);
+            }(yr),
+            xr = new Float64Array(1),
+            Tr = new Uint32Array(xr.buffer);
 
-        function jr(e) {
+        function Sr(e) {
             var t = (31744 & e) >> 10,
                 n = (1023 & e) / 1024,
                 r = Math.pow(-1, (32768 & e) >> 15);
             switch (t) {
                 case 31:
                     return r * (n ? NaN : 1 / 0);
                 case 0:
                     return r * (n ? 6103515625e-14 * n : 0)
             }
             return r * Math.pow(2, t - 15) * (1 + n)
         }
 
-        function xr(e) {
+        function Ir(e) {
             if (e !== e) return 32256;
-            Or[0] = e;
-            var t = (2147483648 & _r[1]) >> 16 & 65535,
-                n = 2146435072 & _r[1],
+            xr[0] = e;
+            var t = (2147483648 & Tr[1]) >> 16 & 65535,
+                n = 2146435072 & Tr[1],
                 r = 0;
-            return n >= 1089470464 ? _r[0] > 0 ? n = 31744 : (n = (2080374784 & n) >> 16, r = (1048575 & _r[1]) >> 10) : n <= 1056964608 ? (r = 1048576 + ((r = 1048576 + (1048575 & _r[1])) << (n >> 20) - 998) >> 21, n = 0) : (n = n - 1056964608 >> 10, r = 512 + (1048575 & _r[1]) >> 10), t | n | 65535 & r
+            return n >= 1089470464 ? Tr[0] > 0 ? n = 31744 : (n = (2080374784 & n) >> 16, r = (1048575 & Tr[1]) >> 10) : n <= 1056964608 ? (r = 1048576 + ((r = 1048576 + (1048575 & Tr[1])) << (n >> 20) - 998) >> 21, n = 0) : (n = n - 1056964608 >> 10, r = 512 + (1048575 & Tr[1]) >> 10), t | n | 65535 & r
         }
-        var Tr = function(e) {
+        var Er = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(hr),
-            Sr = function(e) {
+            }(yr),
+            Ar = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "setValue",
                     value: function(e, t) {
-                        this._values.set(e, xr(t))
+                        this._values.set(e, Ir(t))
                     }
                 }]), n
-            }(Tr),
-            Ir = function(e) {
+            }(Er),
+            Cr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "setValue",
                     value: function(e, t) {
                         this._values.set(e, t)
                     }
                 }]), n
-            }(Tr),
-            Er = function(e) {
+            }(Er),
+            Br = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "setValue",
                     value: function(e, t) {
                         this._values.set(e, t)
                     }
                 }]), n
-            }(Tr),
-            Ar = n(19),
-            Cr = n(20);
+            }(Er),
+            Dr = n(20),
+            Mr = n(21);
 
-        function Br(e, t, n) {
-            return Br = Object(Cr.a)() ? Reflect.construct.bind() : function(e, t, n) {
+        function Lr(e, t, n) {
+            return Lr = Object(Mr.a)() ? Reflect.construct.bind() : function(e, t, n) {
                 var r = [null];
                 r.push.apply(r, t);
                 var i = new(Function.bind.apply(e, r));
-                return n && Object(Ar.a)(i, n.prototype), i
-            }, Br.apply(null, arguments)
+                return n && Object(Dr.a)(i, n.prototype), i
+            }, Lr.apply(null, arguments)
         }
-        var Dr, Mr, Lr = Symbol.for("isArrowBigNum");
+        var Fr, Nr, Pr = Symbol.for("isArrowBigNum");
 
-        function Fr(e) {
+        function Ur(e) {
             for (var t = arguments.length, n = new Array(t > 1 ? t - 1 : 0), r = 1; r < t; r++) n[r - 1] = arguments[r];
-            return 0 === n.length ? Object.setPrototypeOf(Fe(this.TypedArray, e), this.constructor.prototype) : Object.setPrototypeOf(Br(this.TypedArray, [e].concat(n)), this.constructor.prototype)
+            return 0 === n.length ? Object.setPrototypeOf(Ue(this.TypedArray, e), this.constructor.prototype) : Object.setPrototypeOf(Lr(this.TypedArray, [e].concat(n)), this.constructor.prototype)
         }
 
-        function Nr() {
+        function Rr() {
             for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++) t[n] = arguments[n];
-            return Fr.apply(this, t)
+            return Ur.apply(this, t)
         }
 
-        function Pr() {
+        function zr() {
             for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++) t[n] = arguments[n];
-            return Fr.apply(this, t)
+            return Ur.apply(this, t)
         }
 
-        function Ur() {
+        function Vr() {
             for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++) t[n] = arguments[n];
-            return Fr.apply(this, t)
+            return Ur.apply(this, t)
         }
 
-        function Rr(e) {
+        function Wr(e) {
             for (var t, n, r = e.buffer, i = e.byteOffset, a = e.length, o = e.signed, u = new Int32Array(r, i, a), c = 0, s = 0, l = u.length; s < l;) n = u[s++], t = u[s++], o || (t >>>= 0), c += (n >>> 0) + t * Math.pow(s, 32);
             return c
         }
 
-        function zr(e) {
+        function Yr(e) {
             var t = "",
                 n = new Uint32Array(2),
                 r = new Uint16Array(e.buffer, e.byteOffset, e.byteLength / 2),
                 i = new Uint32Array((r = new Uint16Array(r).reverse()).buffer),
                 a = -1,
                 o = r.length - 1;
             do {
                 for (n[0] = r[a = 0]; a < o;) r[a++] = n[1] = n[0] / 10, n[0] = (n[0] - 10 * n[1] << 16) + r[a];
                 r[a] = n[1] = n[0] / 10, n[0] = n[0] - 10 * n[1], t = "".concat(n[0]).concat(t)
             } while (i[0] || i[1] || i[2] || i[3]);
             return t || "0"
         }
-        Fr.prototype[Lr] = !0, Fr.prototype.toJSON = function() {
-            return '"'.concat(Dr(this), '"')
-        }, Fr.prototype.valueOf = function() {
-            return Rr(this)
-        }, Fr.prototype.toString = function() {
-            return Dr(this)
-        }, Fr.prototype[Symbol.toPrimitive] = function() {
+        Ur.prototype[Pr] = !0, Ur.prototype.toJSON = function() {
+            return '"'.concat(Fr(this), '"')
+        }, Ur.prototype.valueOf = function() {
+            return Wr(this)
+        }, Ur.prototype.toString = function() {
+            return Fr(this)
+        }, Ur.prototype[Symbol.toPrimitive] = function() {
             switch (arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : "default") {
                 case "number":
-                    return Rr(this);
+                    return Wr(this);
                 case "string":
-                    return Dr(this);
+                    return Fr(this);
                 case "default":
-                    return Mr(this)
+                    return Nr(this)
             }
-            return Dr(this)
-        }, Object.setPrototypeOf(Nr.prototype, Object.create(Int32Array.prototype)), Object.setPrototypeOf(Pr.prototype, Object.create(Uint32Array.prototype)), Object.setPrototypeOf(Ur.prototype, Object.create(Uint32Array.prototype)), Object.assign(Nr.prototype, Fr.prototype, {
-            constructor: Nr,
+            return Fr(this)
+        }, Object.setPrototypeOf(Rr.prototype, Object.create(Int32Array.prototype)), Object.setPrototypeOf(zr.prototype, Object.create(Uint32Array.prototype)), Object.setPrototypeOf(Vr.prototype, Object.create(Uint32Array.prototype)), Object.assign(Rr.prototype, Ur.prototype, {
+            constructor: Rr,
             signed: !0,
             TypedArray: Int32Array,
-            BigIntArray: ye
-        }), Object.assign(Pr.prototype, Fr.prototype, {
-            constructor: Pr,
+            BigIntArray: be
+        }), Object.assign(zr.prototype, Ur.prototype, {
+            constructor: zr,
             signed: !1,
             TypedArray: Uint32Array,
-            BigIntArray: be
-        }), Object.assign(Ur.prototype, Fr.prototype, {
-            constructor: Ur,
+            BigIntArray: ke
+        }), Object.assign(Vr.prototype, Ur.prototype, {
+            constructor: Vr,
             signed: !0,
             TypedArray: Uint32Array,
-            BigIntArray: be
-        }), de ? (Mr = function(e) {
-            return 8 === e.byteLength ? new e.BigIntArray(e.buffer, e.byteOffset, 1)[0] : zr(e)
-        }, Dr = function(e) {
-            return 8 === e.byteLength ? "".concat(new e.BigIntArray(e.buffer, e.byteOffset, 1)[0]) : zr(e)
-        }) : Mr = Dr = zr;
-        var Vr, Wr = function() {
+            BigIntArray: ke
+        }), pe ? (Nr = function(e) {
+            return 8 === e.byteLength ? new e.BigIntArray(e.buffer, e.byteOffset, 1)[0] : Yr(e)
+        }, Fr = function(e) {
+            return 8 === e.byteLength ? "".concat(new e.BigIntArray(e.buffer, e.byteOffset, 1)[0]) : Yr(e)
+        }) : Nr = Fr = Yr;
+        var Hr, $r = function() {
                 function e(t, n) {
                     return Object(D.a)(this, e), e.new(t, n)
                 }
                 return Object(M.a)(e, null, [{
                     key: "new",
                     value: function(e, t) {
                         switch (t) {
                             case !0:
-                                return new Nr(e);
+                                return new Rr(e);
                             case !1:
-                                return new Pr(e)
+                                return new zr(e)
                         }
                         switch (e.constructor) {
                             case Int8Array:
                             case Int16Array:
                             case Int32Array:
-                            case ye:
-                                return new Nr(e)
+                            case be:
+                                return new Rr(e)
                         }
-                        return 16 === e.byteLength ? new Ur(e) : new Pr(e)
+                        return 16 === e.byteLength ? new Vr(e) : new zr(e)
                     }
                 }, {
                     key: "signed",
                     value: function(e) {
-                        return new Nr(e)
+                        return new Rr(e)
                     }
                 }, {
                     key: "unsigned",
                     value: function(e) {
-                        return new Pr(e)
+                        return new zr(e)
                     }
                 }, {
                     key: "decimal",
                     value: function(e) {
-                        return new Ur(e)
+                        return new Vr(e)
                     }
                 }]), e
             }(),
-            Yr = function(e) {
+            Kr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "setValue",
                     value: function(e, t) {
                         this._values.set(e, t)
                     }
                 }]), n
-            }(hr),
-            Hr = function(e) {
+            }(yr),
+            qr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Yr),
-            $r = function(e) {
+            }(Kr),
+            Qr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Yr),
-            Kr = function(e) {
+            }(Kr),
+            Gr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Yr),
-            qr = function(e) {
+            }(Kr),
+            Xr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), e.nullValues && (e.nullValues = e.nullValues.map(Zr)), (r = t.call(this, e))._values = new lr(new Int32Array(0), 2), r
+                    return Object(D.a)(this, n), e.nullValues && (e.nullValues = e.nullValues.map(ni)), (r = t.call(this, e))._values = new dr(new Int32Array(0), 2), r
                 }
                 return Object(M.a)(n, [{
                     key: "values64",
                     get: function() {
                         return this._values.buffer64
                     }
                 }, {
                     key: "isValid",
                     value: function(e) {
-                        return Ct(Object(At.a)(n.prototype), "isValid", this).call(this, Zr(e))
+                        return Mt(Object(Dt.a)(n.prototype), "isValid", this).call(this, ni(e))
                     }
                 }]), n
-            }(Yr),
-            Qr = function(e) {
+            }(Kr),
+            Jr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Yr),
-            Gr = function(e) {
+            }(Kr),
+            Zr = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Yr),
-            Xr = function(e) {
+            }(Kr),
+            ei = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Yr),
-            Jr = function(e) {
+            }(Kr),
+            ti = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), e.nullValues && (e.nullValues = e.nullValues.map(Zr)), (r = t.call(this, e))._values = new lr(new Uint32Array(0), 2), r
+                    return Object(D.a)(this, n), e.nullValues && (e.nullValues = e.nullValues.map(ni)), (r = t.call(this, e))._values = new dr(new Uint32Array(0), 2), r
                 }
                 return Object(M.a)(n, [{
                     key: "values64",
                     get: function() {
                         return this._values.buffer64
                     }
                 }, {
                     key: "isValid",
                     value: function(e) {
-                        return Ct(Object(At.a)(n.prototype), "isValid", this).call(this, Zr(e))
+                        return Mt(Object(Dt.a)(n.prototype), "isValid", this).call(this, ni(e))
                     }
                 }]), n
-            }(Yr),
-            Zr = (Vr = {
-                BigIntArray: ye
+            }(Kr),
+            ni = (Hr = {
+                BigIntArray: be
             }, function(e) {
-                return ArrayBuffer.isView(e) && (Vr.buffer = e.buffer, Vr.byteOffset = e.byteOffset, Vr.byteLength = e.byteLength, e = Mr(Vr), Vr.buffer = null), e
+                return ArrayBuffer.isView(e) && (Hr.buffer = e.buffer, Hr.byteOffset = e.byteOffset, Hr.byteLength = e.byteLength, e = Nr(Hr), Hr.buffer = null), e
             }),
-            ei = function(e) {
+            ri = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(hr),
-            ti = function(e) {
+            }(yr),
+            ii = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(ei),
-            ni = function(e) {
+            }(ri),
+            ai = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(ei),
-            ri = function(e) {
+            }(ri),
+            oi = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(ei),
-            ii = function(e) {
+            }(ri),
+            ui = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(ei),
-            ai = function(e) {
+            }(ri),
+            ci = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(hr),
-            oi = function(e) {
+            }(yr),
+            si = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(ai),
-            ui = function(e) {
+            }(ci),
+            li = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(ai),
-            ci = function(e) {
+            }(ci),
+            fi = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(ai),
-            si = function(e) {
+            }(ci),
+            hi = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(ai),
-            li = function(e) {
+            }(ci),
+            di = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(hr),
-            fi = function(e) {
+            }(yr),
+            pi = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(li),
-            hi = function(e) {
+            }(di),
+            yi = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(li),
-            di = function(e) {
+            }(di),
+            vi = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), (r = t.call(this, e))._values = new or(new Uint8Array(0)), r
+                    return Object(D.a)(this, n), (r = t.call(this, e))._values = new sr(new Uint8Array(0)), r
                 }
                 return Object(M.a)(n, [{
                     key: "byteLength",
                     get: function() {
                         var e = this._pendingLength + 4 * this.length;
                         return this._offsets && (e += this._offsets.byteLength), this._values && (e += this._values.byteLength), this._nulls && (e += this._nulls.byteLength), e
                     }
                 }, {
                     key: "setValue",
                     value: function(e, t) {
-                        return Ct(Object(At.a)(n.prototype), "setValue", this).call(this, e, ze(t))
+                        return Mt(Object(Dt.a)(n.prototype), "setValue", this).call(this, e, Ye(t))
                     }
                 }, {
                     key: "_flushPending",
                     value: function(e, t) {
                         var n, r, i = this._offsets,
                             a = this._values.reserve(t).buffer,
                             o = 0,
                             u = 0,
                             c = 0,
                             s = C(e);
                         try {
                             for (s.s(); !(r = s.n()).done;) {
-                                var l = F(r.value, 2);
+                                var l = Object(F.a)(r.value, 2);
                                 o = l[0], void 0 === (n = l[1]) ? i.set(o, 0) : (u = n.length, a.set(n, c), i.set(o, u), c += u)
                             }
                         } catch (f) {
                             s.e(f)
                         } finally {
                             s.f()
                         }
                     }
                 }]), n
-            }(dr),
-            pi = function(e) {
+            }(vr),
+            bi = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), (r = t.call(this, e))._values = new or(new Uint8Array(0)), r
+                    return Object(D.a)(this, n), (r = t.call(this, e))._values = new sr(new Uint8Array(0)), r
                 }
                 return Object(M.a)(n, [{
                     key: "byteLength",
                     get: function() {
                         var e = this._pendingLength + 4 * this.length;
                         return this._offsets && (e += this._offsets.byteLength), this._values && (e += this._values.byteLength), this._nulls && (e += this._nulls.byteLength), e
                     }
                 }, {
                     key: "setValue",
                     value: function(e, t) {
-                        return Ct(Object(At.a)(n.prototype), "setValue", this).call(this, e, ie(t))
+                        return Mt(Object(Dt.a)(n.prototype), "setValue", this).call(this, e, ie(t))
                     }
                 }, {
                     key: "_flushPending",
                     value: function(e, t) {}
                 }]), n
-            }(dr);
-        pi.prototype._flushPending = di.prototype._flushPending;
-        var yi = function() {
+            }(vr);
+        bi.prototype._flushPending = vi.prototype._flushPending;
+        var mi = function() {
                 function e() {
                     Object(D.a)(this, e)
                 }
                 return Object(M.a)(e, [{
                     key: "length",
                     get: function() {
                         return this._values.length
@@ -9219,29 +9233,29 @@
                     key: "clear",
                     value: function() {
                         return this._values = null, this
                     }
                 }, {
                     key: "bind",
                     value: function(e) {
-                        return e instanceof Pt ? e : (this._values = e, this)
+                        return e instanceof zt ? e : (this._values = e, this)
                     }
                 }]), e
             }(),
-            vi = n(15),
-            bi = n(16),
-            mi = n(12),
-            gi = Symbol.for("parent"),
-            ki = Symbol.for("rowIndex"),
-            wi = Symbol.for("keyToIdx"),
-            Oi = Symbol.for("idxToVal"),
-            _i = Symbol.for("nodejs.util.inspect.custom"),
-            ji = function(e) {
+            gi = n(16),
+            ki = n(17),
+            wi = n(14),
+            Oi = Symbol.for("parent"),
+            _i = Symbol.for("rowIndex"),
+            ji = Symbol.for("keyToIdx"),
+            xi = Symbol.for("idxToVal"),
+            Ti = Symbol.for("nodejs.util.inspect.custom"),
+            Si = function(e) {
                 function t(e, n) {
-                    Object(D.a)(this, t), this[gi] = e, this.size = n
+                    Object(D.a)(this, t), this[Oi] = e, this.size = n
                 }
                 return Object(M.a)(t, [{
                     key: "entries",
                     value: function() {
                         return this[Symbol.iterator]()
                     }
                 }, {
@@ -9250,34 +9264,34 @@
                         return void 0 !== this.get(e)
                     }
                 }, {
                     key: "get",
                     value: function(e) {
                         var t = void 0;
                         if (null !== e && void 0 !== e) {
-                            var n = this[wi] || (this[wi] = new Map),
+                            var n = this[ji] || (this[ji] = new Map),
                                 r = n.get(e);
                             if (void 0 !== r) {
-                                var i = this[Oi] || (this[Oi] = new Array(this.size));
+                                var i = this[xi] || (this[xi] = new Array(this.size));
                                 void 0 !== (t = i[r]) || (i[r] = t = this.getValue(r))
                             } else if ((r = this.getIndex(e)) > -1) {
                                 n.set(e, r);
-                                var a = this[Oi] || (this[Oi] = new Array(this.size));
+                                var a = this[xi] || (this[xi] = new Array(this.size));
                                 void 0 !== (t = a[r]) || (a[r] = t = this.getValue(r))
                             }
                         }
                         return t
                     }
                 }, {
                     key: "set",
                     value: function(e, t) {
                         if (null !== e && void 0 !== e) {
-                            var n = this[wi] || (this[wi] = new Map),
+                            var n = this[ji] || (this[ji] = new Map),
                                 r = n.get(e);
-                            if (void 0 === r && n.set(e, r = this.getIndex(e)), r > -1)(this[Oi] || (this[Oi] = new Array(this.size)))[r] = this.setValue(r, t)
+                            if (void 0 === r && n.set(e, r = this.getIndex(e)), r > -1)(this[xi] || (this[xi] = new Array(this.size)))[r] = this.setValue(r, t)
                         }
                         return this
                     }
                 }, {
                     key: "clear",
                     value: function() {
                         throw new Error("Clearing ".concat(this[Symbol.toStringTag], " not supported."))
@@ -9290,15 +9304,15 @@
                 }, {
                     key: e,
                     value: Object(L.a)().mark((function e() {
                         var t, n, r, i, a, o, u, c, s;
                         return Object(L.a)().wrap((function(e) {
                             for (;;) switch (e.prev = e.next) {
                                 case 0:
-                                    t = this.keys(), n = this.values(), r = this[wi] || (this[wi] = new Map), i = this[Oi] || (this[Oi] = new Array(this.size)), u = 0;
+                                    t = this.keys(), n = this.values(), r = this[ji] || (this[ji] = new Map), i = this[xi] || (this[xi] = new Array(this.size)), u = 0;
                                 case 5:
                                     if ((c = t.next()).done || (s = n.next()).done) {
                                         e.next = 15;
                                         break
                                     }
                                     return a = c.value, o = s.value, i[u] = o, r.has(a) || r.set(a, u), e.next = 12, [a, o];
                                 case 12:
@@ -9311,20 +9325,20 @@
                         }), e, this)
                     }))
                 }, {
                     key: "forEach",
                     value: function(e, t) {
                         for (var n, r, i, a, o = this.keys(), u = this.values(), c = void 0 === t ? e : function(n, r, i) {
                                 return e.call(t, n, r, i)
-                            }, s = this[wi] || (this[wi] = new Map), l = this[Oi] || (this[Oi] = new Array(this.size)), f = 0; !(i = o.next()).done && !(a = u.next()).done; ++f) n = i.value, r = a.value, l[f] = r, s.has(n) || s.set(n, f), c(r, n, this)
+                            }, s = this[ji] || (this[ji] = new Map), l = this[xi] || (this[xi] = new Array(this.size)), f = 0; !(i = o.next()).done && !(a = u.next()).done; ++f) n = i.value, r = a.value, l[f] = r, s.has(n) || s.set(n, f), c(r, n, this)
                     }
                 }, {
                     key: "toArray",
                     value: function() {
-                        return Object(an.a)(this.values())
+                        return Object(cn.a)(this.values())
                     }
                 }, {
                     key: "toJSON",
                     value: function() {
                         var e = {};
                         return this.forEach((function(t, n) {
                             return e[n] = t
@@ -9332,105 +9346,105 @@
                     }
                 }, {
                     key: "inspect",
                     value: function() {
                         return this.toString()
                     }
                 }, {
-                    key: _i,
+                    key: Ti,
                     value: function() {
                         return this.toString()
                     }
                 }, {
                     key: "toString",
                     value: function() {
                         var e = [];
                         return this.forEach((function(t, n) {
-                            n = rr(n), t = rr(t), e.push("".concat(n, ": ").concat(t))
+                            n = or(n), t = or(t), e.push("".concat(n, ": ").concat(t))
                         })), "{ ".concat(e.join(", "), " }")
                     }
                 }]), t
             }(Symbol.iterator);
-        ji[Symbol.toStringTag] = function(e) {
+        Si[Symbol.toStringTag] = function(e) {
             var t;
             return Object.defineProperties(e, (t = {
                 size: {
                     writable: !0,
                     enumerable: !1,
                     configurable: !1,
                     value: 0
                 }
-            }, Object(mi.a)(t, gi, {
+            }, Object(wi.a)(t, Oi, {
                 writable: !0,
                 enumerable: !1,
                 configurable: !1,
                 value: null
-            }), Object(mi.a)(t, ki, {
+            }), Object(wi.a)(t, _i, {
                 writable: !0,
                 enumerable: !1,
                 configurable: !1,
                 value: -1
             }), t)), e[Symbol.toStringTag] = "Row"
-        }(ji.prototype);
-        var xi = function(e) {
+        }(Si.prototype);
+        var Ii = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), r = t.call(this, e, e.length), Object(vi.a)(r, Ei(Object(bi.a)(r)))
+                    return Object(D.a)(this, n), r = t.call(this, e, e.length), Object(gi.a)(r, Bi(Object(ki.a)(r)))
                 }
                 return Object(M.a)(n, [{
                     key: "keys",
                     value: function() {
-                        return this[gi].getChildAt(0)[Symbol.iterator]()
+                        return this[Oi].getChildAt(0)[Symbol.iterator]()
                     }
                 }, {
                     key: "values",
                     value: function() {
-                        return this[gi].getChildAt(1)[Symbol.iterator]()
+                        return this[Oi].getChildAt(1)[Symbol.iterator]()
                     }
                 }, {
                     key: "getKey",
                     value: function(e) {
-                        return this[gi].getChildAt(0).get(e)
+                        return this[Oi].getChildAt(0).get(e)
                     }
                 }, {
                     key: "getIndex",
                     value: function(e) {
-                        return this[gi].getChildAt(0).indexOf(e)
+                        return this[Oi].getChildAt(0).indexOf(e)
                     }
                 }, {
                     key: "getValue",
                     value: function(e) {
-                        return this[gi].getChildAt(1).get(e)
+                        return this[Oi].getChildAt(1).get(e)
                     }
                 }, {
                     key: "setValue",
                     value: function(e, t) {
-                        this[gi].getChildAt(1).set(e, t)
+                        this[Oi].getChildAt(1).set(e, t)
                     }
                 }]), n
-            }(ji),
-            Ti = function(e) {
+            }(Si),
+            Ei = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), r = t.call(this, e, e.type.children.length), Object(vi.a)(r, Ii(Object(bi.a)(r)))
+                    return Object(D.a)(this, n), r = t.call(this, e, e.type.children.length), Object(gi.a)(r, Ci(Object(ki.a)(r)))
                 }
                 return Object(M.a)(n, [{
                     key: "keys",
                     value: Object(L.a)().mark((function e() {
                         var t, n, r;
                         return Object(L.a)().wrap((function(e) {
                             for (;;) switch (e.prev = e.next) {
                                 case 0:
-                                    t = C(this[gi].type.children), e.prev = 1, t.s();
+                                    t = C(this[Oi].type.children), e.prev = 1, t.s();
                                 case 3:
                                     if ((n = t.n()).done) {
                                         e.next = 9;
                                         break
                                     }
                                     return r = n.value, e.next = 7, r.name;
                                 case 7:
@@ -9454,15 +9468,15 @@
                 }, {
                     key: "values",
                     value: Object(L.a)().mark((function e() {
                         var t, n, r;
                         return Object(L.a)().wrap((function(e) {
                             for (;;) switch (e.prev = e.next) {
                                 case 0:
-                                    t = C(this[gi].type.children), e.prev = 1, t.s();
+                                    t = C(this[Oi].type.children), e.prev = 1, t.s();
                                 case 3:
                                     if ((n = t.n()).done) {
                                         e.next = 9;
                                         break
                                     }
                                     return r = n.value, e.next = 7, this[r.name];
                                 case 7:
@@ -9482,46 +9496,46 @@
                         }), e, this, [
                             [1, 11, 14, 17]
                         ])
                     }))
                 }, {
                     key: "getKey",
                     value: function(e) {
-                        return this[gi].type.children[e].name
+                        return this[Oi].type.children[e].name
                     }
                 }, {
                     key: "getIndex",
                     value: function(e) {
-                        return this[gi].type.children.findIndex((function(t) {
+                        return this[Oi].type.children.findIndex((function(t) {
                             return t.name === e
                         }))
                     }
                 }, {
                     key: "getValue",
                     value: function(e) {
-                        return this[gi].getChildAt(e).get(this[ki])
+                        return this[Oi].getChildAt(e).get(this[_i])
                     }
                 }, {
                     key: "setValue",
                     value: function(e, t) {
-                        return this[gi].getChildAt(e).set(this[ki], t)
+                        return this[Oi].getChildAt(e).set(this[_i], t)
                     }
                 }]), n
-            }(ji);
-        Object.setPrototypeOf(ji.prototype, Map.prototype);
-        var Si, Ii = function() {
+            }(Si);
+        Object.setPrototypeOf(Si.prototype, Map.prototype);
+        var Ai, Ci = function() {
                 var e = {
                     enumerable: !0,
                     configurable: !1,
                     get: null,
                     set: null
                 };
                 return function(t) {
                     var n, r = -1,
-                        i = t[wi] || (t[wi] = new Map),
+                        i = t[ji] || (t[ji] = new Map),
                         a = function(e) {
                             return function() {
                                 return this.get(e)
                             }
                         },
                         o = function(e) {
                             return function(t) {
@@ -9538,32 +9552,32 @@
                         u.e(s)
                     } finally {
                         u.f()
                     }
                     return e.get = e.set = null, t
                 }
             }(),
-            Ei = function() {
-                if ("undefined" === typeof Proxy) return Ii;
-                var e = ji.prototype.has,
-                    t = ji.prototype.get,
-                    n = ji.prototype.set,
-                    r = ji.prototype.getKey,
+            Bi = function() {
+                if ("undefined" === typeof Proxy) return Ci;
+                var e = Si.prototype.has,
+                    t = Si.prototype.get,
+                    n = Si.prototype.set,
+                    r = Si.prototype.getKey,
                     i = {
                         isExtensible: function() {
                             return !1
                         },
                         deleteProperty: function() {
                             return !1
                         },
                         preventExtensions: function() {
                             return !0
                         },
                         ownKeys: function(e) {
-                            return Object(an.a)(e.keys()).map((function(e) {
+                            return Object(cn.a)(e.keys()).map((function(e) {
                                 return "".concat(e)
                             }))
                         },
                         has: function(e, t) {
                             switch (t) {
                                 case "getKey":
                                 case "getIndex":
@@ -9592,19 +9606,19 @@
                                 case "__defineGetter__":
                                 case "__defineSetter__":
                                 case "hasOwnProperty":
                                 case "__lookupGetter__":
                                 case "__lookupSetter__":
                                 case Symbol.iterator:
                                 case Symbol.toStringTag:
-                                case gi:
-                                case ki:
                                 case Oi:
-                                case wi:
                                 case _i:
+                                case xi:
+                                case ji:
+                                case Ti:
                                     return !0
                             }
                             return "number" !== typeof t || e.has(t) || (t = e.getKey(t)), e.has(t)
                         },
                         get: function(n, i, a) {
                             switch (i) {
                                 case "getKey":
@@ -9634,29 +9648,29 @@
                                 case "__defineGetter__":
                                 case "__defineSetter__":
                                 case "hasOwnProperty":
                                 case "__lookupGetter__":
                                 case "__lookupSetter__":
                                 case Symbol.iterator:
                                 case Symbol.toStringTag:
-                                case gi:
-                                case ki:
                                 case Oi:
-                                case wi:
                                 case _i:
+                                case xi:
+                                case ji:
+                                case Ti:
                                     return Reflect.get(n, i, a)
                             }
                             return "number" !== typeof i || e.call(a, i) || (i = r.call(a, i)), t.call(a, i)
                         },
                         set: function(t, i, a, o) {
                             switch (i) {
-                                case gi:
-                                case ki:
                                 case Oi:
-                                case wi:
+                                case _i:
+                                case xi:
+                                case ji:
                                     return Reflect.set(t, i, a, o);
                                 case "getKey":
                                 case "getIndex":
                                 case "getValue":
                                 case "setValue":
                                 case "toArray":
                                 case "toJSON":
@@ -9691,104 +9705,104 @@
                         }
                     };
                 return function(e) {
                     return new Proxy(e, i)
                 }
             }();
 
-        function Ai(e, t, n) {
+        function Di(e, t, n) {
             var r = e.length,
                 i = t > -1 ? t : r + t % r;
             return n ? n(e, i) : i
         }
 
-        function Ci(e, t, n, r) {
+        function Mi(e, t, n, r) {
             var i = e.length,
                 a = void 0 === i ? 0 : i,
                 o = "number" !== typeof t ? 0 : t,
                 u = "number" !== typeof n ? a : n;
-            return o < 0 && (o = (o % a + a) % a), u < 0 && (u = (u % a + a) % a), u < o && (Si = o, o = u, u = Si), u > a && (u = a), r ? r(e, o, u) : [o, u]
+            return o < 0 && (o = (o % a + a) % a), u < 0 && (u = (u % a + a) % a), u < o && (Ai = o, o = u, u = Ai), u > a && (u = a), r ? r(e, o, u) : [o, u]
         }
-        var Bi = de ? he(0) : 0,
-            Di = function(e) {
+        var Li = pe ? de(0) : 0,
+            Fi = function(e) {
                 return e !== e
             };
 
-        function Mi(e) {
+        function Ni(e) {
             var t = typeof e;
-            if ("object" !== t || null === e) return Di(e) ? Di : "bigint" !== t ? function(t) {
+            if ("object" !== t || null === e) return Fi(e) ? Fi : "bigint" !== t ? function(t) {
                 return t === e
             } : function(t) {
-                return Bi + t === e
+                return Li + t === e
             };
             if (e instanceof Date) {
                 var n = e.valueOf();
                 return function(e) {
                     return e instanceof Date && e.valueOf() === n
                 }
             }
             return ArrayBuffer.isView(e) ? function(t) {
-                return !!t && bt(e, t)
+                return !!t && kt(e, t)
             } : e instanceof Map ? function(e) {
                 var t = -1,
                     n = [];
                 return e.forEach((function(e) {
-                    return n[++t] = Mi(e)
-                })), Li(n)
+                    return n[++t] = Ni(e)
+                })), Pi(n)
             }(e) : Array.isArray(e) ? function(e) {
-                for (var t = [], n = -1, r = e.length; ++n < r;) t[n] = Mi(e[n]);
-                return Li(t)
-            }(e) : e instanceof Pt ? function(e) {
-                for (var t = [], n = -1, r = e.length; ++n < r;) t[n] = Mi(e.get(n));
-                return Li(t)
+                for (var t = [], n = -1, r = e.length; ++n < r;) t[n] = Ni(e[n]);
+                return Pi(t)
+            }(e) : e instanceof zt ? function(e) {
+                for (var t = [], n = -1, r = e.length; ++n < r;) t[n] = Ni(e.get(n));
+                return Pi(t)
             }(e) : function(e) {
                 var t = Object.keys(e);
                 if (0 === t.length) return function() {
                     return !1
                 };
-                for (var n = [], r = -1, i = t.length; ++r < i;) n[r] = Mi(e[t[r]]);
-                return Li(n, t)
+                for (var n = [], r = -1, i = t.length; ++r < i;) n[r] = Ni(e[t[r]]);
+                return Pi(n, t)
             }(e)
         }
 
-        function Li(e, t) {
+        function Pi(e, t) {
             return function(n) {
                 if (!n || "object" !== typeof n) return !1;
                 switch (n.constructor) {
                     case Array:
                         return function(e, t) {
                             var n = e.length;
                             if (t.length !== n) return !1;
                             for (var r = -1; ++r < n;)
                                 if (!e[r](t[r])) return !1;
                             return !0
                         }(e, n);
                     case Map:
-                    case xi:
-                    case Ti:
-                        return Fi(e, n, n.keys());
+                    case Ii:
+                    case Ei:
+                        return Ui(e, n, n.keys());
                     case Object:
                     case void 0:
-                        return Fi(e, n, t || Object.keys(n))
+                        return Ui(e, n, t || Object.keys(n))
                 }
-                return n instanceof Pt && function(e, t) {
+                return n instanceof zt && function(e, t) {
                     var n = e.length;
                     if (t.length !== n) return !1;
                     for (var r = -1; ++r < n;)
                         if (!e[r](t.get(r))) return !1;
                     return !0
                 }(e, n)
             }
         }
 
-        function Fi(e, t, n) {
+        function Ui(e, t, n) {
             for (var r = n[Symbol.iterator](), i = t instanceof Map ? t.keys() : Object.keys(t)[Symbol.iterator](), a = t instanceof Map ? t.values() : Object.values(t)[Symbol.iterator](), o = 0, u = e.length, c = a.next(), s = r.next(), l = i.next(); o < u && !s.done && !l.done && !c.done && (s.value === l.value && e[o](c.value)); ++o, s = r.next(), l = i.next(), c = a.next());
             return !!(o === u && s.done && l.done && c.done) || (r.return && r.return(), i.return && i.return(), a.return && a.return(), !1)
         }
-        var Ni = function(e, t) {
+        var Ri = function(e, t) {
             Object(ae.a)(r, e);
             var n = Object(oe.a)(r);
 
             function r(e) {
                 var t, i = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : [],
                     a = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : function(e) {
                         for (var t = new Uint32Array((e || []).length + 1), n = t[0] = 0, r = t.length, i = 0; ++i < r;) t[i] = n += e[i - 1].length;
@@ -9855,29 +9869,29 @@
                     return e < 0 && (this._nullCount = e = this._chunks.reduce((function(e, t) {
                         return e + t.nullCount
                     }), 0)), e
                 }
             }, {
                 key: "indices",
                 get: function() {
-                    if (kn.isDictionary(this._type)) {
+                    if (_n.isDictionary(this._type)) {
                         if (!this._indices) {
                             var e = this._chunks;
-                            this._indices = 1 === e.length ? e[0].indices : r.concat.apply(r, Object(an.a)(e.map((function(e) {
+                            this._indices = 1 === e.length ? e[0].indices : r.concat.apply(r, Object(cn.a)(e.map((function(e) {
                                 return e.indices
                             }))))
                         }
                         return this._indices
                     }
                     return null
                 }
             }, {
                 key: "dictionary",
                 get: function() {
-                    return kn.isDictionary(this._type) ? this._chunks[this._chunks.length - 1].data.dictionary : null
+                    return _n.isDictionary(this._type) ? this._chunks[this._chunks.length - 1].data.dictionary : null
                 }
             }, {
                 key: t,
                 value: Object(L.a)().mark((function e() {
                     var t, n, r;
                     return Object(L.a)().wrap((function(e) {
                         for (;;) switch (e.prev = e.next) {
@@ -9918,15 +9932,15 @@
                 value: function() {
                     for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++) t[n] = arguments[n];
                     return this.clone(r.flatten.apply(r, [this].concat(t)))
                 }
             }, {
                 key: "slice",
                 value: function(e, t) {
-                    return Ci(this, e, t, this._sliceInternal)
+                    return Mi(this, e, t, this._sliceInternal)
                 }
             }, {
                 key: "getChildAt",
                 value: function(e) {
                     if (e < 0 || e >= this._numChildren) return null;
                     var t, n, i, a = this._children || (this._children = []);
                     return (t = a[e]) ? t : (n = (this._type.children || [])[e]) && (i = this._chunks.map((function(t) {
@@ -9984,15 +9998,15 @@
                     var e = this.chunks,
                         t = e.length,
                         n = this._type.ArrayType;
                     if (t <= 0) return new n(0);
                     if (t <= 1) return e[0].toArray();
                     for (var r = 0, i = new Array(t), a = -1; ++a < t;) r += (i[a] = e[a].toArray()).length;
                     n !== i[0].constructor && (n = i[0].constructor);
-                    for (var o = new n(r), u = n === Array ? Ui : Pi, c = -1, s = 0; ++c < t;) s = u(i[c], o, s);
+                    for (var o = new n(r), u = n === Array ? Vi : zi, c = -1, s = 0; ++c < t;) s = u(i[c], o, s);
                     return o
                 }
             }, {
                 key: "getInternal",
                 value: function(e, t, n) {
                     return e._chunks[t].get(n)
                 }
@@ -10028,39 +10042,39 @@
                     }
                     return e.clone(r)
                 }
             }], [{
                 key: "flatten",
                 value: function() {
                     for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++) t[n] = arguments[n];
-                    return Hi(Pt, t)
+                    return qi(zt, t)
                 }
             }, {
                 key: "concat",
                 value: function() {
                     var e = r.flatten.apply(r, arguments);
                     return new r(e[0].type, e)
                 }
             }]), r
-        }(Pt, Symbol.iterator);
-        var Pi = function(e, t, n) {
+        }(zt, Symbol.iterator);
+        var zi = function(e, t, n) {
                 return t.set(e, n), n + e.length
             },
-            Ui = function(e, t, n) {
+            Vi = function(e, t, n) {
                 for (var r = n, i = -1, a = e.length; ++i < a;) t[r++] = e[i];
                 return r
             },
-            Ri = function(e) {
+            Wi = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r, i = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : [],
                         a = arguments.length > 2 ? arguments[2] : void 0;
-                    return Object(D.a)(this, n), i = Ni.flatten.apply(Ni, Object(an.a)(i)), (r = t.call(this, e.type, i, a))._field = e, 1 !== i.length || Object(bi.a)(r) instanceof zi ? r : Object(vi.a)(r, new zi(e, i[0], r._chunkOffsets))
+                    return Object(D.a)(this, n), i = Ri.flatten.apply(Ri, Object(cn.a)(i)), (r = t.call(this, e.type, i, a))._field = e, 1 !== i.length || Object(ki.a)(r) instanceof Yi ? r : Object(gi.a)(r, new Yi(e, i[0], r._chunkOffsets))
                 }
                 return Object(M.a)(n, [{
                     key: "field",
                     get: function() {
                         return this._field
                     }
                 }, {
@@ -10095,28 +10109,28 @@
                             return null != e
                         }))).length > 0 ? a[e] = new n(r, i) : null
                     }
                 }], [{
                     key: "new",
                     value: function(e, t) {
                         for (var r = arguments.length, i = new Array(r > 2 ? r - 2 : 0), a = 2; a < r; a++) i[a - 2] = arguments[a];
-                        var o = Ni.flatten(Array.isArray(t) ? [].concat(Object(an.a)(t), i) : t instanceof Pt ? [t].concat(i) : [Pt.new.apply(Pt, [t].concat(i))]);
+                        var o = Ri.flatten(Array.isArray(t) ? [].concat(Object(cn.a)(t), i) : t instanceof zt ? [t].concat(i) : [zt.new.apply(zt, [t].concat(i))]);
                         if ("string" === typeof e) {
                             var u = o[0].data.type;
-                            e = new Zi(e, u, !0)
+                            e = new na(e, u, !0)
                         } else !e.nullable && o.some((function(e) {
                             return e.nullCount > 0
                         })) && (e = e.clone({
                             nullable: !0
                         }));
                         return new n(e, o)
                     }
                 }]), n
-            }(Ni),
-            zi = function(e) {
+            }(Ri),
+            Yi = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e, r, i) {
                     var a;
                     return Object(D.a)(this, n), (a = t.call(this, e, [r], i))._chunk = r, a
                 }
@@ -10142,84 +10156,85 @@
                     }
                 }, {
                     key: "indexOf",
                     value: function(e, t) {
                         return this._chunk.indexOf(e, t)
                     }
                 }]), n
-            }(Ri),
-            Vi = Array.isArray,
-            Wi = function(e, t) {
-                return Ki(e, t, [], 0)
+            }(Wi),
+            Hi = Array.isArray,
+            $i = function(e, t) {
+                return Gi(e, t, [], 0)
             },
-            Yi = function(e) {
-                return Xi(e, [
+            Ki = function(e) {
+                return ea(e, [
                     [],
                     []
                 ])
             },
-            Hi = function(e, t) {
-                return qi(e, t, [], 0)
+            qi = function(e, t) {
+                return Xi(e, t, [], 0)
             },
-            $i = function(e, t) {
-                return Qi(e, t, [], 0)
+            Qi = function(e, t) {
+                return Ji(e, t, [], 0)
             };
 
-        function Ki(e, t, n, r) {
-            for (var i, a = r, o = -1, u = t.length; ++o < u;) Vi(i = t[o]) ? a = Ki(e, i, n, a).length : i instanceof e && (n[a++] = i);
+        function Gi(e, t, n, r) {
+            for (var i, a = r, o = -1, u = t.length; ++o < u;) Hi(i = t[o]) ? a = Gi(e, i, n, a).length : i instanceof e && (n[a++] = i);
             return n
         }
 
-        function qi(e, t, n, r) {
-            for (var i, a = r, o = -1, u = t.length; ++o < u;) Vi(i = t[o]) ? a = qi(e, i, n, a).length : i instanceof Ni ? a = qi(e, i.chunks, n, a).length : i instanceof e && (n[a++] = i);
+        function Xi(e, t, n, r) {
+            for (var i, a = r, o = -1, u = t.length; ++o < u;) Hi(i = t[o]) ? a = Xi(e, i, n, a).length : i instanceof Ri ? a = Xi(e, i.chunks, n, a).length : i instanceof e && (n[a++] = i);
             return n
         }
 
-        function Qi(e, t, n, r) {
-            for (var i, a = r, o = -1, u = t.length; ++o < u;) Vi(i = t[o]) ? a = Qi(e, i, n, a).length : i instanceof e ? a = Ki(Pt, i.schema.fields.map((function(e, t) {
+        function Ji(e, t, n, r) {
+            for (var i, a = r, o = -1, u = t.length; ++o < u;) Hi(i = t[o]) ? a = Ji(e, i, n, a).length : i instanceof e ? a = Gi(zt, i.schema.fields.map((function(e, t) {
                 return i.getChildAt(t)
-            })), n, a).length : i instanceof Pt && (n[a++] = i);
+            })), n, a).length : i instanceof zt && (n[a++] = i);
             return n
         }
-        var Gi = function(e, t, n) {
-            var r = F(t, 2),
+        var Zi = function(e, t, n) {
+            var r = Object(F.a)(t, 2),
                 i = r[0],
                 a = r[1];
             return e[0][n] = i, e[1][n] = a, e
         };
 
-        function Xi(e, t) {
+        function ea(e, t) {
             var n, r;
             switch (r = e.length) {
                 case 0:
                     return t;
                 case 1:
                     if (n = t[0], !e[0]) return t;
-                    if (Vi(e[0])) return Xi(e[0], t);
-                    if (!(e[0] instanceof tr || e[0] instanceof Pt || e[0] instanceof kn)) {
-                        var i = F(Object.entries(e[0]).reduce(Gi, t), 2);
-                        n = i[0], e = i[1]
+                    if (Hi(e[0])) return ea(e[0], t);
+                    if (!(e[0] instanceof ir || e[0] instanceof zt || e[0] instanceof _n)) {
+                        var i = Object.entries(e[0]).reduce(Zi, t),
+                            a = Object(F.a)(i, 2);
+                        n = a[0], e = a[1]
                     }
                     break;
                 default:
-                    Vi(n = e[r - 1]) ? e = Vi(e[0]) ? e[0] : e.slice(0, r - 1) : (e = Vi(e[0]) ? e[0] : e, n = [])
+                    Hi(n = e[r - 1]) ? e = Hi(e[0]) ? e[0] : e.slice(0, r - 1) : (e = Hi(e[0]) ? e[0] : e, n = [])
             }
-            for (var a, o, u = -1, c = -1, s = -1, l = e.length, f = F(t, 2), h = f[0], d = f[1]; ++s < l;)
-                if ((o = e[s]) instanceof Ri && (d[++c] = o)) h[++u] = o.field.clone(n[s], o.type, !0);
+            for (var o, u, c = -1, s = -1, l = -1, f = e.length, h = Object(F.a)(t, 2), d = h[0], p = h[1]; ++l < f;)
+                if ((u = e[l]) instanceof Wi && (p[++s] = u)) d[++c] = u.field.clone(n[l], u.type, !0);
                 else {
-                    var p = n[s];
-                    a = void 0 === p ? s : p, o instanceof kn && (d[++c] = o) ? h[++u] = Zi.new(a, o, !0) : o && o.type && (d[++c] = o) && (o instanceof tr && (d[c] = o = Pt.new(o)), h[++u] = Zi.new(a, o.type, !0))
+                    var y = n[l];
+                    o = void 0 === y ? l : y, u instanceof _n && (p[++s] = u) ? d[++c] = na.new(o, u, !0) : u && u.type && (p[++s] = u) && (u instanceof ir && (p[s] = u = zt.new(u)), d[++c] = na.new(o, u.type, !0))
                 } return t
         }
-        var Ji = function(e) {
+        var ta = function(e) {
                 function t() {
                     var e = arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : [],
                         n = arguments.length > 1 ? arguments[1] : void 0,
                         r = arguments.length > 2 ? arguments[2] : void 0;
-                    Object(D.a)(this, t), this.fields = e || [], this.metadata = n || new Map, r || (r = ta(e)), this.dictionaries = r
+                    Object(D.a)(this, t), this.fields = e || [], this.metadata = n || new Map, r || (r = ia(e)), this.dictionaries = r
                 }
                 return Object(M.a)(t, [{
                     key: e,
                     get: function() {
                         return "Schema"
                     }
                 }, {
@@ -10228,15 +10243,15 @@
                         return "Schema<{ ".concat(this.fields.map((function(e, t) {
                             return "".concat(t, ": ").concat(e)
                         })).join(", "), " }>")
                     }
                 }, {
                     key: "compareTo",
                     value: function(e) {
-                        return gn.compareSchemas(this, e)
+                        return On.compareSchemas(this, e)
                     }
                 }, {
                     key: "select",
                     value: function() {
                         for (var e = arguments.length, n = new Array(e), r = 0; r < e; r++) n[r] = arguments[r];
                         var i = n.reduce((function(e, t) {
                             return (e[t] = !0) && e
@@ -10253,42 +10268,42 @@
                             return e.fields[t]
                         })).filter(Boolean), this.metadata)
                     }
                 }, {
                     key: "assign",
                     value: function() {
                         for (var e = arguments.length, n = new Array(e), r = 0; r < e; r++) n[r] = arguments[r];
-                        var i = n[0] instanceof t ? n[0] : new t(Wi(Zi, n)),
-                            a = Object(an.a)(this.fields),
-                            o = ea(ea(new Map, this.metadata), i.metadata),
+                        var i = n[0] instanceof t ? n[0] : new t($i(na, n)),
+                            a = Object(cn.a)(this.fields),
+                            o = ra(ra(new Map, this.metadata), i.metadata),
                             u = i.fields.filter((function(e) {
                                 var t = a.findIndex((function(t) {
                                     return t.name === e.name
                                 }));
                                 return !~t || (a[t] = e.clone({
-                                    metadata: ea(ea(new Map, a[t].metadata), e.metadata)
+                                    metadata: ra(ra(new Map, a[t].metadata), e.metadata)
                                 })) && !1
                             })),
-                            c = ta(u, new Map);
-                        return new t([].concat(Object(an.a)(a), Object(an.a)(u)), o, new Map([].concat(Object(an.a)(this.dictionaries), Object(an.a)(c))))
+                            c = ia(u, new Map);
+                        return new t([].concat(Object(cn.a)(a), Object(cn.a)(u)), o, new Map([].concat(Object(cn.a)(this.dictionaries), Object(cn.a)(c))))
                     }
                 }], [{
                     key: "from",
                     value: function() {
                         return t.new(arguments.length <= 0 ? void 0 : arguments[0], arguments.length <= 1 ? void 0 : arguments[1])
                     }
                 }, {
                     key: "new",
                     value: function() {
                         for (var e = arguments.length, n = new Array(e), r = 0; r < e; r++) n[r] = arguments[r];
-                        return new t(Yi(n)[0])
+                        return new t(Ki(n)[0])
                     }
                 }]), t
             }(Symbol.toStringTag),
-            Zi = function(e) {
+            na = function(e) {
                 function t(e, n) {
                     var r = arguments.length > 2 && void 0 !== arguments[2] && arguments[2],
                         i = arguments.length > 3 ? arguments[3] : void 0;
                     Object(D.a)(this, t), this.name = e, this.type = n, this.nullable = r, this.metadata = i || new Map
                 }
                 return Object(M.a)(t, [{
                     key: "typeId",
@@ -10304,186 +10319,186 @@
                     key: "toString",
                     value: function() {
                         return "".concat(this.name, ": ").concat(this.type)
                     }
                 }, {
                     key: "compareTo",
                     value: function(e) {
-                        return gn.compareField(this, e)
+                        return On.compareField(this, e)
                     }
                 }, {
                     key: "clone",
                     value: function() {
-                        for (var e, n, r, i, a, o, u, c, s, l, f = arguments.length, h = new Array(f), d = 0; d < f; d++) h[d] = arguments[d];
-                        var p = h[0],
-                            y = h[1],
-                            v = h[2],
-                            b = h[3];
-                        return h[0] && "object" === typeof h[0] ? (p = void 0 === (u = (o = h[0]).name) ? this.name : u, y = void 0 === (c = o.type) ? this.type : c, v = void 0 === (s = o.nullable) ? this.nullable : s, b = void 0 === (l = o.metadata) ? this.metadata : l) : (p = void 0 === (n = (e = F(h, 4))[0]) ? this.name : n, y = void 0 === (r = e[1]) ? this.type : r, v = void 0 === (i = e[2]) ? this.nullable : i, b = void 0 === (a = e[3]) ? this.metadata : a), t.new(p, y, v, b)
+                        for (var e, n, r, i, a, o, u, c, s, l, f, h = arguments.length, d = new Array(h), p = 0; p < h; p++) d[p] = arguments[p];
+                        var y = d[0],
+                            v = d[1],
+                            b = d[2],
+                            m = d[3];
+                        return d[0] && "object" === typeof d[0] ? (y = void 0 === (c = (u = d[0]).name) ? this.name : c, v = void 0 === (s = u.type) ? this.type : s, b = void 0 === (l = u.nullable) ? this.nullable : l, m = void 0 === (f = u.metadata) ? this.metadata : f) : (e = d, y = void 0 === (r = (n = Object(F.a)(e, 4))[0]) ? this.name : r, v = void 0 === (i = n[1]) ? this.type : i, b = void 0 === (a = n[2]) ? this.nullable : a, m = void 0 === (o = n[3]) ? this.metadata : o), t.new(y, v, b, m)
                     }
                 }], [{
                     key: "new",
                     value: function() {
                         for (var e = arguments.length, n = new Array(e), r = 0; r < e; r++) n[r] = arguments[r];
                         var i = n[0],
                             a = n[1],
                             o = n[2],
                             u = n[3];
                         return n[0] && "object" === typeof n[0] && (i = n[0].name, void 0 === a && (a = n[0].type), void 0 === o && (o = n[0].nullable), void 0 === u && (u = n[0].metadata)), new t("".concat(i), a, o, u)
                     }
                 }]), t
             }(Symbol.toStringTag);
 
-        function ea(e, t) {
-            return new Map([].concat(Object(an.a)(e || new Map), Object(an.a)(t || new Map)))
+        function ra(e, t) {
+            return new Map([].concat(Object(cn.a)(e || new Map), Object(cn.a)(t || new Map)))
         }
 
-        function ta(e) {
+        function ia(e) {
             for (var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : new Map, n = -1, r = e.length; ++n < r;) {
                 var i = e[n].type;
-                if (kn.isDictionary(i))
+                if (_n.isDictionary(i))
                     if (t.has(i.id)) {
                         if (t.get(i.id) !== i.dictionary) throw new Error("Cannot create Schema containing two different dictionaries with the same Id")
                     } else t.set(i.id, i.dictionary);
-                i.children && i.children.length > 0 && ta(i.children, t)
+                i.children && i.children.length > 0 && ia(i.children, t)
             }
             return t
         }
-        Ji.prototype.fields = null, Ji.prototype.metadata = null, Ji.prototype.dictionaries = null, Zi.prototype.type = null, Zi.prototype.name = null, Zi.prototype.nullable = null, Zi.prototype.metadata = null;
-        var na = function(e) {
+        ta.prototype.fields = null, ta.prototype.metadata = null, ta.prototype.dictionaries = null, na.prototype.type = null, na.prototype.name = null, na.prototype.nullable = null, na.prototype.metadata = null;
+        var aa = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), (r = t.call(this, e))._run = new yi, r._offsets = new sr, r
+                    return Object(D.a)(this, n), (r = t.call(this, e))._run = new mi, r._offsets = new hr, r
                 }
                 return Object(M.a)(n, [{
                     key: "addChild",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : "0";
                         if (this.numChildren > 0) throw new Error("ListBuilder can only have one child.");
-                        return this.children[this.numChildren] = e, this.type = new Hn(new Zi(t, e.type, !0)), this.numChildren - 1
+                        return this.children[this.numChildren] = e, this.type = new qn(new na(t, e.type, !0)), this.numChildren - 1
                     }
                 }, {
                     key: "clear",
                     value: function() {
-                        return this._run.clear(), Ct(Object(At.a)(n.prototype), "clear", this).call(this)
+                        return this._run.clear(), Mt(Object(Dt.a)(n.prototype), "clear", this).call(this)
                     }
                 }, {
                     key: "_flushPending",
                     value: function(e) {
                         var t, n, r = this._run,
                             i = this._offsets,
                             a = this._setValue,
                             o = 0,
                             u = C(e);
                         try {
                             for (u.s(); !(n = u.n()).done;) {
-                                var c = F(n.value, 2);
+                                var c = Object(F.a)(n.value, 2);
                                 o = c[0], void 0 === (t = c[1]) ? i.set(o, 0) : (i.set(o, t.length), a(this, o, r.bind(t)))
                             }
                         } catch (s) {
                             u.e(s)
                         } finally {
                             u.f()
                         }
                     }
                 }]), n
-            }(dr),
-            ra = function(e) {
+            }(vr),
+            oa = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     var e;
-                    return Object(D.a)(this, n), (e = t.apply(this, arguments))._run = new yi, e
+                    return Object(D.a)(this, n), (e = t.apply(this, arguments))._run = new mi, e
                 }
                 return Object(M.a)(n, [{
                     key: "setValue",
                     value: function(e, t) {
-                        Ct(Object(At.a)(n.prototype), "setValue", this).call(this, e, this._run.bind(t))
+                        Mt(Object(Dt.a)(n.prototype), "setValue", this).call(this, e, this._run.bind(t))
                     }
                 }, {
                     key: "addChild",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : "0";
                         if (this.numChildren > 0) throw new Error("FixedSizeListBuilder can only have one child.");
                         var n = this.children.push(e);
-                        return this.type = new Qn(this.type.listSize, new Zi(t, e.type, !0)), n
+                        return this.type = new Jn(this.type.listSize, new na(t, e.type, !0)), n
                     }
                 }, {
                     key: "clear",
                     value: function() {
-                        return this._run.clear(), Ct(Object(At.a)(n.prototype), "clear", this).call(this)
+                        return this._run.clear(), Mt(Object(Dt.a)(n.prototype), "clear", this).call(this)
                     }
                 }]), n
-            }(fr),
-            ia = function(e) {
+            }(pr),
+            ua = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "set",
                     value: function(e, t) {
-                        return Ct(Object(At.a)(n.prototype), "set", this).call(this, e, t)
+                        return Mt(Object(Dt.a)(n.prototype), "set", this).call(this, e, t)
                     }
                 }, {
                     key: "setValue",
                     value: function(e, t) {
                         t = t instanceof Map ? t : new Map(Object.entries(t));
                         var n = this._pending || (this._pending = new Map),
                             r = n.get(e);
                         r && (this._pendingLength -= r.size), this._pendingLength += t.size, n.set(e, t)
                     }
                 }, {
                     key: "addChild",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : "".concat(this.numChildren);
                         if (this.numChildren > 0) throw new Error("ListBuilder can only have one child.");
-                        return this.children[this.numChildren] = e, this.type = new Gn(new Zi(t, e.type, !0), this.type.keysSorted), this.numChildren - 1
+                        return this.children[this.numChildren] = e, this.type = new Zn(new na(t, e.type, !0), this.type.keysSorted), this.numChildren - 1
                     }
                 }, {
                     key: "_flushPending",
                     value: function(e) {
                         var t = this,
                             n = this._offsets,
                             r = this._setValue;
                         e.forEach((function(e, i) {
                             void 0 === e ? n.set(i, 0) : (n.set(i, e.size), r(t, i, e))
                         }))
                     }
                 }]), n
-            }(dr),
-            aa = function(e) {
+            }(vr),
+            ca = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "addChild",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : "".concat(this.numChildren),
                             n = this.children.push(e);
-                        return this.type = new $n([].concat(Object(an.a)(this.type.children), [new Zi(t, e.type, !0)])), n
+                        return this.type = new Qn([].concat(Object(cn.a)(this.type.children), [new na(t, e.type, !0)])), n
                     }
                 }]), n
-            }(fr),
-            oa = function(e) {
+            }(pr),
+            sa = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), (r = t.call(this, e))._typeIds = new ur(new Int8Array(0), 1), "function" === typeof e.valueToChildTypeId && (r._valueToChildTypeId = e.valueToChildTypeId), r
+                    return Object(D.a)(this, n), (r = t.call(this, e))._typeIds = new lr(new Int8Array(0), 1), "function" === typeof e.valueToChildTypeId && (r._valueToChildTypeId = e.valueToChildTypeId), r
                 }
                 return Object(M.a)(n, [{
                     key: "typeIdToChildIndex",
                     get: function() {
                         return this.type.typeIdToChildIndex
                     }
                 }, {
@@ -10495,207 +10510,207 @@
                     key: "set",
                     value: function(e, t, n) {
                         return void 0 === n && (n = this._valueToChildTypeId(this, t, e)), this.setValid(e, this.isValid(t)) && this.setValue(e, t, n), this
                     }
                 }, {
                     key: "setValue",
                     value: function(e, t, r) {
-                        this._typeIds.set(e, r), Ct(Object(At.a)(n.prototype), "setValue", this).call(this, e, t)
+                        this._typeIds.set(e, r), Mt(Object(Dt.a)(n.prototype), "setValue", this).call(this, e, t)
                     }
                 }, {
                     key: "addChild",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : "".concat(this.children.length),
                             n = this.children.push(e),
                             r = this.type,
                             i = r.children,
                             a = r.mode,
                             o = r.typeIds,
-                            u = [].concat(Object(an.a)(i), [new Zi(t, e.type)]);
-                        return this.type = new Kn(a, [].concat(Object(an.a)(o), [n]), u), n
+                            u = [].concat(Object(cn.a)(i), [new na(t, e.type)]);
+                        return this.type = new Gn(a, [].concat(Object(cn.a)(o), [n]), u), n
                     }
                 }, {
                     key: "_valueToChildTypeId",
                     value: function(e, t, n) {
                         throw new Error("Cannot map UnionBuilder value to child typeId. Pass the `childTypeId` as the second argument to unionBuilder.append(), or supply a `valueToChildTypeId` function as part of the UnionBuilder constructor options.")
                     }
                 }]), n
-            }(fr),
-            ua = function(e) {
+            }(pr),
+            la = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(oa),
-            ca = function(e) {
+            }(sa),
+            fa = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), (r = t.call(this, e))._offsets = new ur(new Int32Array(0)), r
+                    return Object(D.a)(this, n), (r = t.call(this, e))._offsets = new lr(new Int32Array(0)), r
                 }
                 return Object(M.a)(n, [{
                     key: "setValue",
                     value: function(e, t, r) {
                         var i = this.type.typeIdToChildIndex[r];
-                        return this._offsets.set(e, this.getChildAt(i).length), Ct(Object(At.a)(n.prototype), "setValue", this).call(this, e, t, r)
+                        return this._offsets.set(e, this.getChildAt(i).length), Mt(Object(Dt.a)(n.prototype), "setValue", this).call(this, e, t, r)
                     }
                 }]), n
-            }(oa),
-            sa = function(e) {
+            }(sa),
+            ha = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(on),
-            la = function(e, t, n) {
+            }(sn),
+            da = function(e, t, n) {
                 e[t] = n % 4294967296 | 0, e[t + 1] = n / 4294967296 | 0
             },
-            fa = function(e, t, n, r) {
+            pa = function(e, t, n, r) {
                 var i = t[n],
                     a = t[n + 1];
                 null != i && null != a && e.set(r.subarray(0, a - i), i)
             },
-            ha = function(e, t, n) {
+            ya = function(e, t, n) {
                 ! function(e, t, n) {
                     e[t] = n / 864e5 | 0
                 }(e.values, t, n.valueOf())
             },
-            da = function(e, t, n) {
+            va = function(e, t, n) {
                 var r = e.values;
-                la(r, 2 * t, n.valueOf())
+                da(r, 2 * t, n.valueOf())
             },
-            pa = function(e, t, n) {
+            ba = function(e, t, n) {
                 var r = e.stride;
                 e.values[r * t] = n
             },
-            ya = function(e, t, n) {
+            ma = function(e, t, n) {
                 var r = e.stride;
-                e.values[r * t] = xr(n)
+                e.values[r * t] = Ir(n)
             },
-            va = function(e, t, n) {
+            ga = function(e, t, n) {
                 switch (typeof n) {
                     case "bigint":
                         e.values64[t] = n;
                         break;
                     case "number":
                         e.values[t * e.stride] = n;
                         break;
                     default:
                         var r = n,
                             i = e.stride,
-                            a = Fe(e.ArrayType, r);
+                            a = Ue(e.ArrayType, r);
                         e.values.set(a.subarray(0, i), i * t)
                 }
             },
-            ba = function(e, t, n) {
+            ka = function(e, t, n) {
                 var r = e.values;
-                return la(r, 2 * t, n / 1e3)
+                return da(r, 2 * t, n / 1e3)
             },
-            ma = function(e, t, n) {
+            wa = function(e, t, n) {
                 var r = e.values;
-                return la(r, 2 * t, n)
+                return da(r, 2 * t, n)
             },
-            ga = function(e, t, n) {
+            Oa = function(e, t, n) {
                 return function(e, t, n) {
                     e[t] = 1e3 * n % 4294967296 | 0, e[t + 1] = 1e3 * n / 4294967296 | 0
                 }(e.values, 2 * t, n)
             },
-            ka = function(e, t, n) {
+            _a = function(e, t, n) {
                 return function(e, t, n) {
                     e[t] = 1e6 * n % 4294967296 | 0, e[t + 1] = 1e6 * n / 4294967296 | 0
                 }(e.values, 2 * t, n)
             },
-            wa = function(e, t, n) {
+            ja = function(e, t, n) {
                 e.values[e.stride * t] = n
             },
-            Oa = function(e, t, n) {
+            xa = function(e, t, n) {
                 e.values[e.stride * t] = n
             },
-            _a = function(e, t, n) {
+            Ta = function(e, t, n) {
                 e.values.set(n.subarray(0, 2), 2 * t)
             },
-            ja = function(e, t, n) {
+            Sa = function(e, t, n) {
                 e.values.set(n.subarray(0, 2), 2 * t)
             },
-            xa = function(e, t, n) {
+            Ia = function(e, t, n) {
                 var r = e.typeIdToChildIndex[e.typeIds[t]],
                     i = e.getChildAt(r);
                 i && i.set(e.valueOffsets[t], n)
             },
-            Ta = function(e, t, n) {
+            Ea = function(e, t, n) {
                 var r = e.typeIdToChildIndex[e.typeIds[t]],
                     i = e.getChildAt(r);
                 i && i.set(t, n)
             },
-            Sa = function(e, t, n) {
+            Aa = function(e, t, n) {
                 e.values.set(n.subarray(0, 2), 2 * t)
             },
-            Ia = function(e, t, n) {
+            Ca = function(e, t, n) {
                 e.values[t] = 12 * n[0] + n[1] % 12
             };
-        sa.prototype.visitBool = function(e, t, n) {
+        ha.prototype.visitBool = function(e, t, n) {
             var r = e.offset,
                 i = e.values,
                 a = r + t;
             n ? i[a >> 3] |= 1 << a % 8 : i[a >> 3] &= ~(1 << a % 8)
-        }, sa.prototype.visitInt = function(e, t, n) {
-            e.type.bitWidth < 64 ? pa(e, t, n) : va(e, t, n)
-        }, sa.prototype.visitInt8 = pa, sa.prototype.visitInt16 = pa, sa.prototype.visitInt32 = pa, sa.prototype.visitInt64 = va, sa.prototype.visitUint8 = pa, sa.prototype.visitUint16 = pa, sa.prototype.visitUint32 = pa, sa.prototype.visitUint64 = va, sa.prototype.visitFloat = function(e, t, n) {
-            e.type.precision !== Wt.HALF ? pa(e, t, n) : ya(e, t, n)
-        }, sa.prototype.visitFloat16 = ya, sa.prototype.visitFloat32 = pa, sa.prototype.visitFloat64 = pa, sa.prototype.visitUtf8 = function(e, t, n) {
+        }, ha.prototype.visitInt = function(e, t, n) {
+            e.type.bitWidth < 64 ? ba(e, t, n) : ga(e, t, n)
+        }, ha.prototype.visitInt8 = ba, ha.prototype.visitInt16 = ba, ha.prototype.visitInt32 = ba, ha.prototype.visitInt64 = ga, ha.prototype.visitUint8 = ba, ha.prototype.visitUint16 = ba, ha.prototype.visitUint32 = ba, ha.prototype.visitUint64 = ga, ha.prototype.visitFloat = function(e, t, n) {
+            e.type.precision !== $t.HALF ? ba(e, t, n) : ma(e, t, n)
+        }, ha.prototype.visitFloat16 = ma, ha.prototype.visitFloat32 = ba, ha.prototype.visitFloat64 = ba, ha.prototype.visitUtf8 = function(e, t, n) {
             var r = e.values,
                 i = e.valueOffsets;
-            fa(r, i, t, ie(n))
-        }, sa.prototype.visitBinary = function(e, t, n) {
+            pa(r, i, t, ie(n))
+        }, ha.prototype.visitBinary = function(e, t, n) {
             var r = e.values,
                 i = e.valueOffsets;
-            return fa(r, i, t, n)
-        }, sa.prototype.visitFixedSizeBinary = function(e, t, n) {
+            return pa(r, i, t, n)
+        }, ha.prototype.visitFixedSizeBinary = function(e, t, n) {
             var r = e.stride;
             e.values.set(n.subarray(0, r), r * t)
-        }, sa.prototype.visitDate = function(e, t, n) {
-            e.type.unit === zt.DAY ? ha(e, t, n) : da(e, t, n)
-        }, sa.prototype.visitDateDay = ha, sa.prototype.visitDateMillisecond = da, sa.prototype.visitTimestamp = function(e, t, n) {
-            switch (e.type.unit) {
-                case Vt.SECOND:
-                    return ba(e, t, n);
-                case Vt.MILLISECOND:
-                    return ma(e, t, n);
-                case Vt.MICROSECOND:
-                    return ga(e, t, n);
-                case Vt.NANOSECOND:
-                    return ka(e, t, n)
-            }
-        }, sa.prototype.visitTimestampSecond = ba, sa.prototype.visitTimestampMillisecond = ma, sa.prototype.visitTimestampMicrosecond = ga, sa.prototype.visitTimestampNanosecond = ka, sa.prototype.visitTime = function(e, t, n) {
+        }, ha.prototype.visitDate = function(e, t, n) {
+            e.type.unit === Yt.DAY ? ya(e, t, n) : va(e, t, n)
+        }, ha.prototype.visitDateDay = ya, ha.prototype.visitDateMillisecond = va, ha.prototype.visitTimestamp = function(e, t, n) {
             switch (e.type.unit) {
-                case Vt.SECOND:
+                case Ht.SECOND:
+                    return ka(e, t, n);
+                case Ht.MILLISECOND:
                     return wa(e, t, n);
-                case Vt.MILLISECOND:
+                case Ht.MICROSECOND:
                     return Oa(e, t, n);
-                case Vt.MICROSECOND:
-                    return _a(e, t, n);
-                case Vt.NANOSECOND:
-                    return ja(e, t, n)
+                case Ht.NANOSECOND:
+                    return _a(e, t, n)
             }
-        }, sa.prototype.visitTimeSecond = wa, sa.prototype.visitTimeMillisecond = Oa, sa.prototype.visitTimeMicrosecond = _a, sa.prototype.visitTimeNanosecond = ja, sa.prototype.visitDecimal = function(e, t, n) {
+        }, ha.prototype.visitTimestampSecond = ka, ha.prototype.visitTimestampMillisecond = wa, ha.prototype.visitTimestampMicrosecond = Oa, ha.prototype.visitTimestampNanosecond = _a, ha.prototype.visitTime = function(e, t, n) {
+            switch (e.type.unit) {
+                case Ht.SECOND:
+                    return ja(e, t, n);
+                case Ht.MILLISECOND:
+                    return xa(e, t, n);
+                case Ht.MICROSECOND:
+                    return Ta(e, t, n);
+                case Ht.NANOSECOND:
+                    return Sa(e, t, n)
+            }
+        }, ha.prototype.visitTimeSecond = ja, ha.prototype.visitTimeMillisecond = xa, ha.prototype.visitTimeMicrosecond = Ta, ha.prototype.visitTimeNanosecond = Sa, ha.prototype.visitDecimal = function(e, t, n) {
             e.values.set(n.subarray(0, 4), 4 * t)
-        }, sa.prototype.visitList = function(e, t, n) {
+        }, ha.prototype.visitList = function(e, t, n) {
             for (var r = e.getChildAt(0), i = e.valueOffsets, a = -1, o = i[t], u = i[t + 1]; o < u;) r.set(o++, n.get(++a))
-        }, sa.prototype.visitStruct = function(e, t, n) {
+        }, ha.prototype.visitStruct = function(e, t, n) {
             var r, i, a = n instanceof Map ? (r = t, i = n, function(e, t, n) {
                 return e && e.set(r, i.get(t.name))
-            }) : n instanceof Pt ? function(e, t) {
+            }) : n instanceof zt ? function(e, t) {
                 return function(n, r, i) {
                     return n && n.set(e, t.get(i))
                 }
             }(t, n) : Array.isArray(n) ? function(e, t) {
                 return function(n, r, i) {
                     return n && n.set(e, t[i])
                 }
@@ -10703,282 +10718,282 @@
                 return function(n, r, i) {
                     return n && n.set(e, t[r.name])
                 }
             }(t, n);
             e.type.children.forEach((function(t, n) {
                 return a(e.getChildAt(n), t, n)
             }))
-        }, sa.prototype.visitUnion = function(e, t, n) {
-            e.type.mode === Yt.Dense ? xa(e, t, n) : Ta(e, t, n)
-        }, sa.prototype.visitDenseUnion = xa, sa.prototype.visitSparseUnion = Ta, sa.prototype.visitDictionary = function(e, t, n) {
+        }, ha.prototype.visitUnion = function(e, t, n) {
+            e.type.mode === Kt.Dense ? Ia(e, t, n) : Ea(e, t, n)
+        }, ha.prototype.visitDenseUnion = Ia, ha.prototype.visitSparseUnion = Ea, ha.prototype.visitDictionary = function(e, t, n) {
             var r = e.getKey(t);
             null !== r && e.setValue(r, n)
-        }, sa.prototype.visitInterval = function(e, t, n) {
-            e.type.unit === Ht.DAY_TIME ? Sa(e, t, n) : Ia(e, t, n)
-        }, sa.prototype.visitIntervalDayTime = Sa, sa.prototype.visitIntervalYearMonth = Ia, sa.prototype.visitFixedSizeList = function(e, t, n) {
+        }, ha.prototype.visitInterval = function(e, t, n) {
+            e.type.unit === qt.DAY_TIME ? Aa(e, t, n) : Ca(e, t, n)
+        }, ha.prototype.visitIntervalDayTime = Aa, ha.prototype.visitIntervalYearMonth = Ca, ha.prototype.visitFixedSizeList = function(e, t, n) {
             for (var r = e.getChildAt(0), i = e.stride, a = -1, o = t * i; ++a < i;) r.set(o + a, n.get(a))
-        }, sa.prototype.visitMap = function(e, t, n) {
-            for (var r = e.getChildAt(0), i = e.valueOffsets, a = n instanceof Map ? Object(an.a)(n) : Object.entries(n), o = -1, u = i[t], c = i[t + 1]; u < c;) r.set(u++, a[++o])
+        }, ha.prototype.visitMap = function(e, t, n) {
+            for (var r = e.getChildAt(0), i = e.valueOffsets, a = n instanceof Map ? Object(cn.a)(n) : Object.entries(n), o = -1, u = i[t], c = i[t + 1]; u < c;) r.set(u++, a[++o])
         };
-        var Ea, Aa = new sa,
-            Ca = function(e) {
+        var Ba, Da = new ha,
+            Ma = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "visitNull",
                     value: function() {
-                        return yr
+                        return mr
                     }
                 }, {
                     key: "visitBool",
                     value: function() {
-                        return pr
+                        return br
                     }
                 }, {
                     key: "visitInt",
                     value: function() {
-                        return Yr
+                        return Kr
                     }
                 }, {
                     key: "visitInt8",
                     value: function() {
-                        return Hr
+                        return qr
                     }
                 }, {
                     key: "visitInt16",
                     value: function() {
-                        return $r
+                        return Qr
                     }
                 }, {
                     key: "visitInt32",
                     value: function() {
-                        return Kr
+                        return Gr
                     }
                 }, {
                     key: "visitInt64",
                     value: function() {
-                        return qr
+                        return Xr
                     }
                 }, {
                     key: "visitUint8",
                     value: function() {
-                        return Qr
+                        return Jr
                     }
                 }, {
                     key: "visitUint16",
                     value: function() {
-                        return Gr
+                        return Zr
                     }
                 }, {
                     key: "visitUint32",
                     value: function() {
-                        return Xr
+                        return ei
                     }
                 }, {
                     key: "visitUint64",
                     value: function() {
-                        return Jr
+                        return ti
                     }
                 }, {
                     key: "visitFloat",
                     value: function() {
-                        return Tr
+                        return Er
                     }
                 }, {
                     key: "visitFloat16",
                     value: function() {
-                        return Sr
+                        return Ar
                     }
                 }, {
                     key: "visitFloat32",
                     value: function() {
-                        return Ir
+                        return Cr
                     }
                 }, {
                     key: "visitFloat64",
                     value: function() {
-                        return Er
+                        return Br
                     }
                 }, {
                     key: "visitUtf8",
                     value: function() {
-                        return pi
+                        return bi
                     }
                 }, {
                     key: "visitBinary",
                     value: function() {
-                        return di
+                        return vi
                     }
                 }, {
                     key: "visitFixedSizeBinary",
                     value: function() {
-                        return wr
+                        return jr
                     }
                 }, {
                     key: "visitDate",
                     value: function() {
-                        return vr
+                        return gr
                     }
                 }, {
                     key: "visitDateDay",
                     value: function() {
-                        return br
+                        return kr
                     }
                 }, {
                     key: "visitDateMillisecond",
                     value: function() {
-                        return mr
+                        return wr
                     }
                 }, {
                     key: "visitTimestamp",
                     value: function() {
-                        return ai
+                        return ci
                     }
                 }, {
                     key: "visitTimestampSecond",
                     value: function() {
-                        return oi
+                        return si
                     }
                 }, {
                     key: "visitTimestampMillisecond",
                     value: function() {
-                        return ui
+                        return li
                     }
                 }, {
                     key: "visitTimestampMicrosecond",
                     value: function() {
-                        return ci
+                        return fi
                     }
                 }, {
                     key: "visitTimestampNanosecond",
                     value: function() {
-                        return si
+                        return hi
                     }
                 }, {
                     key: "visitTime",
                     value: function() {
-                        return ei
+                        return ri
                     }
                 }, {
                     key: "visitTimeSecond",
                     value: function() {
-                        return ti
+                        return ii
                     }
                 }, {
                     key: "visitTimeMillisecond",
                     value: function() {
-                        return ni
+                        return ai
                     }
                 }, {
                     key: "visitTimeMicrosecond",
                     value: function() {
-                        return ri
+                        return oi
                     }
                 }, {
                     key: "visitTimeNanosecond",
                     value: function() {
-                        return ii
+                        return ui
                     }
                 }, {
                     key: "visitDecimal",
                     value: function() {
-                        return gr
+                        return Or
                     }
                 }, {
                     key: "visitList",
                     value: function() {
-                        return na
+                        return aa
                     }
                 }, {
                     key: "visitStruct",
                     value: function() {
-                        return aa
+                        return ca
                     }
                 }, {
                     key: "visitUnion",
                     value: function() {
-                        return oa
+                        return sa
                     }
                 }, {
                     key: "visitDenseUnion",
                     value: function() {
-                        return ca
+                        return fa
                     }
                 }, {
                     key: "visitSparseUnion",
                     value: function() {
-                        return ua
+                        return la
                     }
                 }, {
                     key: "visitDictionary",
                     value: function() {
-                        return kr
+                        return _r
                     }
                 }, {
                     key: "visitInterval",
                     value: function() {
-                        return li
+                        return di
                     }
                 }, {
                     key: "visitIntervalDayTime",
                     value: function() {
-                        return fi
+                        return pi
                     }
                 }, {
                     key: "visitIntervalYearMonth",
                     value: function() {
-                        return hi
+                        return yi
                     }
                 }, {
                     key: "visitFixedSizeList",
                     value: function() {
-                        return ra
+                        return oa
                     }
                 }, {
                     key: "visitMap",
                     value: function() {
-                        return ia
+                        return ua
                     }
                 }]), n
-            }(on),
-            Ba = new Ca;
-        fr.new = function e(t) {
+            }(sn),
+            La = new Ma;
+        pr.new = function e(t) {
                 var n = t.type,
-                    r = new(Ba.getVisitFn(n)())(t);
+                    r = new(La.getVisitFn(n)())(t);
                 if (n.children && n.children.length > 0) {
                     var i = t.children || [],
                         a = {
                             nullValues: t.nullValues
                         },
                         o = Array.isArray(i) ? function(e, t) {
                             return i[t] || a
                         } : function(e) {
                             var t = e.name;
                             return i[t] || a
                         };
                     n.children.forEach((function(t, n) {
                         var i = t.type,
                             a = o(t, n);
-                        r.children.push(e(Object(Et.a)(Object(Et.a)({}, a), {}, {
+                        r.children.push(e(Object(Bt.a)(Object(Bt.a)({}, a), {}, {
                             type: i
                         })))
                     }))
                 }
                 return r
-            }, Object.keys(Ut).map((function(e) {
-                return Ut[e]
+            }, Object.keys(Vt).map((function(e) {
+                return Vt[e]
             })).filter((function(e) {
-                return "number" === typeof e && e !== Ut.NONE
+                return "number" === typeof e && e !== Vt.NONE
             })).forEach((function(e) {
-                Ba.visit(e).prototype._setValue = Aa.getVisitFn(e)
-            })), pi.prototype._setValue = Aa.visitBinary,
+                La.visit(e).prototype._setValue = Da.getVisitFn(e)
+            })), bi.prototype._setValue = Da.visitBinary,
             function(e) {
                 ! function(t) {
                     ! function(t) {
                         ! function(t) {
                             var n = function() {
                                 function t() {
                                     Object(D.a)(this, t), this.bb = null, this.bb_pos = 0
@@ -10988,21 +11003,21 @@
                                     value: function(e, t) {
                                         return this.bb_pos = e, this.bb = t, this
                                     }
                                 }, {
                                     key: "version",
                                     value: function() {
                                         var e = this.bb.__offset(this.bb_pos, 4);
-                                        return e ? this.bb.readInt16(this.bb_pos + e) : Bt.apache.arrow.flatbuf.MetadataVersion.V1
+                                        return e ? this.bb.readInt16(this.bb_pos + e) : Lt.apache.arrow.flatbuf.MetadataVersion.V1
                                     }
                                 }, {
                                     key: "schema",
                                     value: function(e) {
                                         var t = this.bb.__offset(this.bb_pos, 6);
-                                        return t ? (e || new Bt.apache.arrow.flatbuf.Schema).__init(this.bb.__indirect(this.bb_pos + t), this.bb) : null
+                                        return t ? (e || new Lt.apache.arrow.flatbuf.Schema).__init(this.bb.__indirect(this.bb_pos + t), this.bb) : null
                                     }
                                 }, {
                                     key: "dictionaries",
                                     value: function(t, n) {
                                         var r = this.bb.__offset(this.bb_pos, 8);
                                         return r ? (n || new e.apache.arrow.flatbuf.Block).__init(this.bb.__vector(this.bb_pos + r) + 24 * t, this.bb) : null
                                     }
@@ -11033,15 +11048,15 @@
                                     key: "startFooter",
                                     value: function(e) {
                                         e.startObject(4)
                                     }
                                 }, {
                                     key: "addVersion",
                                     value: function(e, t) {
-                                        e.addFieldInt16(0, t, Bt.apache.arrow.flatbuf.MetadataVersion.V1)
+                                        e.addFieldInt16(0, t, Lt.apache.arrow.flatbuf.MetadataVersion.V1)
                                     }
                                 }, {
                                     key: "addSchema",
                                     value: function(e, t) {
                                         e.addFieldOffset(1, t, 0)
                                     }
                                 }, {
@@ -11081,15 +11096,15 @@
                                     }
                                 }]), t
                             }();
                             t.Footer = n
                         }(t.flatbuf || (t.flatbuf = {}))
                     }(t.arrow || (t.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Ea || (Ea = {})),
+            }(Ba || (Ba = {})),
             function(e) {
                 ! function(e) {
                     ! function(e) {
                         ! function(e) {
                             var t = function() {
                                 function e() {
                                     Object(D.a)(this, e), this.bb = null, this.bb_pos = 0
@@ -11121,23 +11136,23 @@
                                     }
                                 }]), e
                             }();
                             e.Block = t
                         }(e.flatbuf || (e.flatbuf = {}))
                     }(e.arrow || (e.arrow = {}))
                 }(e.apache || (e.apache = {}))
-            }(Ea || (Ea = {}));
-        var Da = Y.Long,
-            Ma = Y.Builder,
-            La = Y.ByteBuffer,
-            Fa = Ea.apache.arrow.flatbuf.Block,
-            Na = Ea.apache.arrow.flatbuf.Footer,
-            Pa = function() {
+            }(Ba || (Ba = {}));
+        var Fa = Y.Long,
+            Na = Y.Builder,
+            Pa = Y.ByteBuffer,
+            Ua = Ba.apache.arrow.flatbuf.Block,
+            Ra = Ba.apache.arrow.flatbuf.Footer,
+            za = function() {
                 function e(t) {
-                    var n = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : Kt.V4,
+                    var n = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : Gt.V4,
                         r = arguments.length > 2 ? arguments[2] : void 0,
                         i = arguments.length > 3 ? arguments[3] : void 0;
                     Object(D.a)(this, e), this.schema = t, this.version = n, r && (this._recordBatches = r), i && (this._dictionaryBatches = i)
                 }
                 return Object(M.a)(e, [{
                     key: "numRecordBatches",
                     get: function() {
@@ -11211,37 +11226,37 @@
                     key: "getDictionaryBatch",
                     value: function(e) {
                         return e >= 0 && e < this.numDictionaries && this._dictionaryBatches[e] || null
                     }
                 }], [{
                     key: "decode",
                     value: function(e) {
-                        e = new La(ze(e));
-                        var t = Na.getRootAsFooter(e),
-                            n = Ji.decode(t.schema());
-                        return new Ua(n, t)
+                        e = new Pa(Ye(e));
+                        var t = Ra.getRootAsFooter(e),
+                            n = ta.decode(t.schema());
+                        return new Va(n, t)
                     }
                 }, {
                     key: "encode",
                     value: function(e) {
-                        var t = new Ma,
-                            n = Ji.encode(t, e.schema);
-                        Na.startRecordBatchesVector(t, e.numRecordBatches), Object(an.a)(e.recordBatches()).slice().reverse().forEach((function(e) {
-                            return Ra.encode(t, e)
+                        var t = new Na,
+                            n = ta.encode(t, e.schema);
+                        Ra.startRecordBatchesVector(t, e.numRecordBatches), Object(cn.a)(e.recordBatches()).slice().reverse().forEach((function(e) {
+                            return Wa.encode(t, e)
                         }));
                         var r = t.endVector();
-                        Na.startDictionariesVector(t, e.numDictionaries), Object(an.a)(e.dictionaryBatches()).slice().reverse().forEach((function(e) {
-                            return Ra.encode(t, e)
+                        Ra.startDictionariesVector(t, e.numDictionaries), Object(cn.a)(e.dictionaryBatches()).slice().reverse().forEach((function(e) {
+                            return Wa.encode(t, e)
                         }));
                         var i = t.endVector();
-                        return Na.startFooter(t), Na.addSchema(t, n), Na.addVersion(t, Kt.V4), Na.addRecordBatches(t, r), Na.addDictionaries(t, i), Na.finishFooterBuffer(t, Na.endFooter(t)), t.asUint8Array()
+                        return Ra.startFooter(t), Ra.addSchema(t, n), Ra.addVersion(t, Gt.V4), Ra.addRecordBatches(t, r), Ra.addDictionaries(t, i), Ra.finishFooterBuffer(t, Ra.endFooter(t)), t.asUint8Array()
                     }
                 }]), e
             }(),
-            Ua = function(e) {
+            Va = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e, r) {
                     var i;
                     return Object(D.a)(this, n), (i = t.call(this, e, r.version()))._footer = r, i
                 }
@@ -11256,70 +11271,70 @@
                         return this._footer.dictionariesLength()
                     }
                 }, {
                     key: "getRecordBatch",
                     value: function(e) {
                         if (e >= 0 && e < this.numRecordBatches) {
                             var t = this._footer.recordBatches(e);
-                            if (t) return Ra.decode(t)
+                            if (t) return Wa.decode(t)
                         }
                         return null
                     }
                 }, {
                     key: "getDictionaryBatch",
                     value: function(e) {
                         if (e >= 0 && e < this.numDictionaries) {
                             var t = this._footer.dictionaries(e);
-                            if (t) return Ra.decode(t)
+                            if (t) return Wa.decode(t)
                         }
                         return null
                     }
                 }]), n
-            }(Pa),
-            Ra = function() {
+            }(za),
+            Wa = function() {
                 function e(t, n, r) {
                     Object(D.a)(this, e), this.metaDataLength = t, this.offset = "number" === typeof r ? r : r.low, this.bodyLength = "number" === typeof n ? n : n.low
                 }
                 return Object(M.a)(e, null, [{
                     key: "decode",
                     value: function(t) {
                         return new e(t.metaDataLength(), t.bodyLength(), t.offset())
                     }
                 }, {
                     key: "encode",
                     value: function(e, t) {
                         var n = t.metaDataLength,
-                            r = new Da(t.offset, 0),
-                            i = new Da(t.bodyLength, 0);
-                        return Fa.createBlock(e, r, n, i)
+                            r = new Fa(t.offset, 0),
+                            i = new Fa(t.bodyLength, 0);
+                        return Ua.createBlock(e, r, n, i)
                     }
                 }]), e
             }(),
-            za = function(e) {
+            Ya = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "write",
                     value: function(e) {
-                        if ((e = ze(e)).byteLength > 0) return Ct(Object(At.a)(n.prototype), "write", this).call(this, e)
+                        if ((e = Ye(e)).byteLength > 0) return Mt(Object(Dt.a)(n.prototype), "write", this).call(this, e)
                     }
                 }, {
                     key: "toString",
                     value: function() {
                         return arguments.length > 0 && void 0 !== arguments[0] && arguments[0] ? re(this.toUint8Array(!0)) : this.toUint8Array(!1).then(re)
                     }
                 }, {
                     key: "toUint8Array",
                     value: function() {
                         var e = this;
-                        return arguments.length > 0 && void 0 !== arguments[0] && arguments[0] ? Le(this._values)[0] : Object(B.a)(Object(L.a)().mark((function t() {
+                        return arguments.length > 0 && void 0 !== arguments[0] && arguments[0] ? Pe(this._values)[0] : Object(B.a)(Object(L.a)().mark((function t() {
                             var n, r, i, a, o, u, c, s;
                             return Object(L.a)().wrap((function(t) {
                                 for (;;) switch (t.prev = t.next) {
                                     case 0:
                                         n = [], r = 0, i = !1, a = !1, t.prev = 3, u = V(e);
                                     case 5:
                                         return t.next = 7, u.next();
@@ -11350,30 +11365,30 @@
                                         }
                                         throw o;
                                     case 28:
                                         return t.finish(25);
                                     case 29:
                                         return t.finish(20);
                                     case 30:
-                                        return t.abrupt("return", Le(n, r)[0]);
+                                        return t.abrupt("return", Pe(n, r)[0]);
                                     case 31:
                                     case "end":
                                         return t.stop()
                                 }
                             }), t, null, [
                                 [3, 16, 20, 30],
                                 [21, , 25, 29]
                             ])
                         })))()
                     }
                 }]), n
             }(le),
-            Va = function(e) {
+            Ha = function(e) {
                 function t(e) {
-                    Object(D.a)(this, t), e && (this.source = new Ya(gt.fromIterable(e)))
+                    Object(D.a)(this, t), e && (this.source = new Ka(Ot.fromIterable(e)))
                 }
                 return Object(M.a)(t, [{
                     key: e,
                     value: function() {
                         return this
                     }
                 }, {
@@ -11399,17 +11414,17 @@
                 }, {
                     key: "read",
                     value: function(e) {
                         return this.source.read(e)
                     }
                 }]), t
             }(Symbol.iterator),
-            Wa = function(e) {
+            $a = function(e) {
                 function t(e) {
-                    Object(D.a)(this, t), e instanceof t ? this.source = e.source : e instanceof za ? this.source = new Ha(gt.fromAsyncIterable(e)) : Ae(e) ? this.source = new Ha(gt.fromNodeStream(e)) : Ee(e) ? this.source = new Ha(gt.fromDOMStream(e)) : Ie(e) ? this.source = new Ha(gt.fromDOMStream(e.body)) : _e(e) ? this.source = new Ha(gt.fromIterable(e)) : (Oe(e) || je(e)) && (this.source = new Ha(gt.fromAsyncIterable(e)))
+                    Object(D.a)(this, t), e instanceof t ? this.source = e.source : e instanceof Ya ? this.source = new qa(Ot.fromAsyncIterable(e)) : De(e) ? this.source = new qa(Ot.fromNodeStream(e)) : Be(e) ? this.source = new qa(Ot.fromDOMStream(e)) : Ce(e) ? this.source = new qa(Ot.fromDOMStream(e.body)) : Te(e) ? this.source = new qa(Ot.fromIterable(e)) : (xe(e) || Se(e)) && (this.source = new qa(Ot.fromAsyncIterable(e)))
                 }
                 return Object(M.a)(t, [{
                     key: e,
                     value: function() {
                         return this
                     }
                 }, {
@@ -11445,15 +11460,15 @@
                 }, {
                     key: "read",
                     value: function(e) {
                         return this.source.read(e)
                     }
                 }]), t
             }(Symbol.asyncIterator),
-            Ya = function() {
+            Ka = function() {
                 function e(t) {
                     Object(D.a)(this, e), this.source = t
                 }
                 return Object(M.a)(e, [{
                     key: "cancel",
                     value: function(e) {
                         this.return(e)
@@ -11485,15 +11500,15 @@
                 }, {
                     key: "return",
                     value: function(e) {
                         return Object.create(this.source.return && this.source.return(e) || ue)
                     }
                 }]), e
             }(),
-            Ha = function() {
+            qa = function() {
                 function e(t) {
                     var n = this;
                     Object(D.a)(this, e), this.source = t, this._closedPromise = new Promise((function(e) {
                         return n._closedPromiseResolve = e
                     }))
                 }
                 return Object(M.a)(e, [{
@@ -11647,21 +11662,21 @@
                         })));
                         return function(t) {
                             return e.apply(this, arguments)
                         }
                     }()
                 }]), e
             }(),
-            $a = function(e) {
+            Qa = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e, r) {
                     var i;
-                    return Object(D.a)(this, n), (i = t.call(this)).position = 0, i.buffer = ze(e), i.size = "undefined" === typeof r ? i.buffer.byteLength : r, i
+                    return Object(D.a)(this, n), (i = t.call(this)).position = 0, i.buffer = Ye(e), i.size = "undefined" === typeof r ? i.buffer.byteLength : r, i
                 }
                 return Object(M.a)(n, [{
                     key: "readInt32",
                     value: function(e) {
                         var t = this.readAt(e, 4),
                             n = t.buffer,
                             r = t.byteOffset;
@@ -11705,16 +11720,16 @@
                     value: function(e) {
                         return this.close(), {
                             done: !0,
                             value: e
                         }
                     }
                 }]), n
-            }(Va),
-            Ka = function(e) {
+            }(Ha),
+            Ga = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e, r) {
                     var i;
                     return Object(D.a)(this, n), (i = t.call(this)).position = 0, i._handle = e, "number" === typeof r ? i.size = r : i._pending = Object(B.a)(Object(L.a)().mark((function t() {
                         return Object(L.a)().wrap((function(t) {
@@ -11916,21 +11931,21 @@
                             }), e, this)
                         })));
                         return function(t) {
                             return e.apply(this, arguments)
                         }
                     }()
                 }]), n
-            }(Wa);
+            }($a);
 
-        function qa(e) {
+        function Xa(e) {
             return e < 0 && (e = 4294967295 + e + 1), "0x".concat(e.toString(16))
         }
-        var Qa = [1, 10, 100, 1e3, 1e4, 1e5, 1e6, 1e7, 1e8],
-            Ga = function() {
+        var Ja = [1, 10, 100, 1e3, 1e4, 1e5, 1e6, 1e7, 1e8],
+            Za = function() {
                 function e(t) {
                     Object(D.a)(this, e), this.buffer = t
                 }
                 return Object(M.a)(e, [{
                     key: "high",
                     value: function() {
                         return this.buffer[1]
@@ -11970,19 +11985,19 @@
                     key: "greaterThan",
                     value: function(e) {
                         return e.lessThan(this)
                     }
                 }, {
                     key: "hex",
                     value: function() {
-                        return "".concat(qa(this.buffer[1]), " ").concat(qa(this.buffer[0]))
+                        return "".concat(Xa(this.buffer[1]), " ").concat(Xa(this.buffer[0]))
                     }
                 }]), e
             }(),
-            Xa = function(e) {
+            eo = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
@@ -12009,15 +12024,15 @@
                     }
                 }, {
                     key: "fromString",
                     value: function(e) {
                         for (var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : new Uint32Array(2), r = e.length, i = new n(t), a = 0; a < r;) {
                             var o = 8 < r - a ? 8 : r - a,
                                 u = new n(new Uint32Array([parseInt(e.substr(a, o), 10), 0])),
-                                c = new n(new Uint32Array([Qa[o], 0]));
+                                c = new n(new Uint32Array([Ja[o], 0]));
                             i.times(c), i.plus(u), a += o
                         }
                         return i
                     }
                 }, {
                     key: "convertArray",
                     value: function(e) {
@@ -12031,16 +12046,16 @@
                     }
                 }, {
                     key: "add",
                     value: function(e, t) {
                         return new n(new Uint32Array(e.buffer)).plus(t)
                     }
                 }]), n
-            }(Ga),
-            Ja = function(e) {
+            }(Za),
+            to = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
@@ -12079,15 +12094,15 @@
                     }
                 }, {
                     key: "fromString",
                     value: function(e) {
                         for (var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : new Uint32Array(2), r = e.startsWith("-"), i = e.length, a = new n(t), o = r ? 1 : 0; o < i;) {
                             var u = 8 < i - o ? 8 : i - o,
                                 c = new n(new Uint32Array([parseInt(e.substr(o, u), 10), 0])),
-                                s = new n(new Uint32Array([Qa[u], 0]));
+                                s = new n(new Uint32Array([Ja[u], 0]));
                             a.times(s), a.plus(c), o += u
                         }
                         return r ? a.negate() : a
                     }
                 }, {
                     key: "convertArray",
                     value: function(e) {
@@ -12101,60 +12116,60 @@
                     }
                 }, {
                     key: "add",
                     value: function(e, t) {
                         return new n(new Uint32Array(e.buffer)).plus(t)
                     }
                 }]), n
-            }(Ga),
-            Za = function() {
+            }(Za),
+            no = function() {
                 function e(t) {
                     Object(D.a)(this, e), this.buffer = t
                 }
                 return Object(M.a)(e, [{
                     key: "high",
                     value: function() {
-                        return new Ja(new Uint32Array(this.buffer.buffer, this.buffer.byteOffset + 8, 2))
+                        return new to(new Uint32Array(this.buffer.buffer, this.buffer.byteOffset + 8, 2))
                     }
                 }, {
                     key: "low",
                     value: function() {
-                        return new Ja(new Uint32Array(this.buffer.buffer, this.buffer.byteOffset, 2))
+                        return new to(new Uint32Array(this.buffer.buffer, this.buffer.byteOffset, 2))
                     }
                 }, {
                     key: "negate",
                     value: function() {
                         return this.buffer[0] = 1 + ~this.buffer[0], this.buffer[1] = ~this.buffer[1], this.buffer[2] = ~this.buffer[2], this.buffer[3] = ~this.buffer[3], 0 == this.buffer[0] && ++this.buffer[1], 0 == this.buffer[1] && ++this.buffer[2], 0 == this.buffer[2] && ++this.buffer[3], this
                     }
                 }, {
                     key: "times",
                     value: function(e) {
-                        var t = new Xa(new Uint32Array([this.buffer[3], 0])),
-                            n = new Xa(new Uint32Array([this.buffer[2], 0])),
-                            r = new Xa(new Uint32Array([this.buffer[1], 0])),
-                            i = new Xa(new Uint32Array([this.buffer[0], 0])),
-                            a = new Xa(new Uint32Array([e.buffer[3], 0])),
-                            o = new Xa(new Uint32Array([e.buffer[2], 0])),
-                            u = new Xa(new Uint32Array([e.buffer[1], 0])),
-                            c = new Xa(new Uint32Array([e.buffer[0], 0])),
-                            s = Xa.multiply(i, c);
+                        var t = new eo(new Uint32Array([this.buffer[3], 0])),
+                            n = new eo(new Uint32Array([this.buffer[2], 0])),
+                            r = new eo(new Uint32Array([this.buffer[1], 0])),
+                            i = new eo(new Uint32Array([this.buffer[0], 0])),
+                            a = new eo(new Uint32Array([e.buffer[3], 0])),
+                            o = new eo(new Uint32Array([e.buffer[2], 0])),
+                            u = new eo(new Uint32Array([e.buffer[1], 0])),
+                            c = new eo(new Uint32Array([e.buffer[0], 0])),
+                            s = eo.multiply(i, c);
                         this.buffer[0] = s.low();
-                        var l = new Xa(new Uint32Array([s.high(), 0]));
-                        return s = Xa.multiply(r, c), l.plus(s), s = Xa.multiply(i, u), l.plus(s), this.buffer[1] = l.low(), this.buffer[3] = l.lessThan(s) ? 1 : 0, this.buffer[2] = l.high(), new Xa(new Uint32Array(this.buffer.buffer, this.buffer.byteOffset + 8, 2)).plus(Xa.multiply(n, c)).plus(Xa.multiply(r, u)).plus(Xa.multiply(i, o)), this.buffer[3] += Xa.multiply(t, c).plus(Xa.multiply(n, u)).plus(Xa.multiply(r, o)).plus(Xa.multiply(i, a)).low(), this
+                        var l = new eo(new Uint32Array([s.high(), 0]));
+                        return s = eo.multiply(r, c), l.plus(s), s = eo.multiply(i, u), l.plus(s), this.buffer[1] = l.low(), this.buffer[3] = l.lessThan(s) ? 1 : 0, this.buffer[2] = l.high(), new eo(new Uint32Array(this.buffer.buffer, this.buffer.byteOffset + 8, 2)).plus(eo.multiply(n, c)).plus(eo.multiply(r, u)).plus(eo.multiply(i, o)), this.buffer[3] += eo.multiply(t, c).plus(eo.multiply(n, u)).plus(eo.multiply(r, o)).plus(eo.multiply(i, a)).low(), this
                     }
                 }, {
                     key: "plus",
                     value: function(e) {
                         var t = new Uint32Array(4);
                         return t[3] = this.buffer[3] + e.buffer[3] >>> 0, t[2] = this.buffer[2] + e.buffer[2] >>> 0, t[1] = this.buffer[1] + e.buffer[1] >>> 0, t[0] = this.buffer[0] + e.buffer[0] >>> 0, t[0] < this.buffer[0] >>> 0 && ++t[1], t[1] < this.buffer[1] >>> 0 && ++t[2], t[2] < this.buffer[2] >>> 0 && ++t[3], this.buffer[3] = t[3], this.buffer[2] = t[2], this.buffer[1] = t[1], this.buffer[0] = t[0], this
                     }
                 }, {
                     key: "hex",
                     value: function() {
-                        return "".concat(qa(this.buffer[3]), " ").concat(qa(this.buffer[2]), " ").concat(qa(this.buffer[1]), " ").concat(qa(this.buffer[0]))
+                        return "".concat(Xa(this.buffer[3]), " ").concat(Xa(this.buffer[2]), " ").concat(Xa(this.buffer[1]), " ").concat(Xa(this.buffer[0]))
                     }
                 }], [{
                     key: "multiply",
                     value: function(t, n) {
                         return new e(new Uint32Array(t.buffer)).times(n)
                     }
                 }, {
@@ -12176,194 +12191,194 @@
                     }
                 }, {
                     key: "fromString",
                     value: function(t) {
                         for (var n = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : new Uint32Array(4), r = t.startsWith("-"), i = t.length, a = new e(n), o = r ? 1 : 0; o < i;) {
                             var u = 8 < i - o ? 8 : i - o,
                                 c = new e(new Uint32Array([parseInt(t.substr(o, u), 10), 0, 0, 0])),
-                                s = new e(new Uint32Array([Qa[u], 0, 0, 0]));
+                                s = new e(new Uint32Array([Ja[u], 0, 0, 0]));
                             a.times(s), a.plus(c), o += u
                         }
                         return r ? a.negate() : a
                     }
                 }, {
                     key: "convertArray",
                     value: function(t) {
                         for (var n = new Uint32Array(4 * t.length), r = -1, i = t.length; ++r < i;) e.from(t[r], new Uint32Array(n.buffer, n.byteOffset + 16 * r, 4));
                         return n
                     }
                 }]), e
             }(),
-            eo = function(e) {
+            ro = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e, r, i, a) {
                     var o;
                     return Object(D.a)(this, n), (o = t.call(this)).nodesIndex = -1, o.buffersIndex = -1, o.bytes = e, o.nodes = r, o.buffers = i, o.dictionaries = a, o
                 }
                 return Object(M.a)(n, [{
                     key: "visit",
                     value: function(e) {
-                        return Ct(Object(At.a)(n.prototype), "visit", this).call(this, e instanceof Zi ? e.type : e)
+                        return Mt(Object(Dt.a)(n.prototype), "visit", this).call(this, e instanceof na ? e.type : e)
                     }
                 }, {
                     key: "visitNull",
                     value: function(e) {
                         var t = (arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode()).length;
-                        return tr.Null(e, 0, t)
+                        return ir.Null(e, 0, t)
                     }
                 }, {
                     key: "visitBool",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Bool(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
+                        return ir.Bool(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
                     }
                 }, {
                     key: "visitInt",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Int(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
+                        return ir.Int(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
                     }
                 }, {
                     key: "visitFloat",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Float(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
+                        return ir.Float(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
                     }
                 }, {
                     key: "visitUtf8",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Utf8(e, 0, n, r, this.readNullBitmap(e, r), this.readOffsets(e), this.readData(e))
+                        return ir.Utf8(e, 0, n, r, this.readNullBitmap(e, r), this.readOffsets(e), this.readData(e))
                     }
                 }, {
                     key: "visitBinary",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Binary(e, 0, n, r, this.readNullBitmap(e, r), this.readOffsets(e), this.readData(e))
+                        return ir.Binary(e, 0, n, r, this.readNullBitmap(e, r), this.readOffsets(e), this.readData(e))
                     }
                 }, {
                     key: "visitFixedSizeBinary",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.FixedSizeBinary(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
+                        return ir.FixedSizeBinary(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
                     }
                 }, {
                     key: "visitDate",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Date(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
+                        return ir.Date(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
                     }
                 }, {
                     key: "visitTimestamp",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Timestamp(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
+                        return ir.Timestamp(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
                     }
                 }, {
                     key: "visitTime",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Time(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
+                        return ir.Time(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
                     }
                 }, {
                     key: "visitDecimal",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Decimal(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
+                        return ir.Decimal(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
                     }
                 }, {
                     key: "visitList",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.List(e, 0, n, r, this.readNullBitmap(e, r), this.readOffsets(e), this.visit(e.children[0]))
+                        return ir.List(e, 0, n, r, this.readNullBitmap(e, r), this.readOffsets(e), this.visit(e.children[0]))
                     }
                 }, {
                     key: "visitStruct",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Struct(e, 0, n, r, this.readNullBitmap(e, r), this.visitMany(e.children))
+                        return ir.Struct(e, 0, n, r, this.readNullBitmap(e, r), this.visitMany(e.children))
                     }
                 }, {
                     key: "visitUnion",
                     value: function(e) {
-                        return e.mode === Yt.Sparse ? this.visitSparseUnion(e) : this.visitDenseUnion(e)
+                        return e.mode === Kt.Sparse ? this.visitSparseUnion(e) : this.visitDenseUnion(e)
                     }
                 }, {
                     key: "visitDenseUnion",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Union(e, 0, n, r, this.readNullBitmap(e, r), this.readTypeIds(e), this.readOffsets(e), this.visitMany(e.children))
+                        return ir.Union(e, 0, n, r, this.readNullBitmap(e, r), this.readTypeIds(e), this.readOffsets(e), this.visitMany(e.children))
                     }
                 }, {
                     key: "visitSparseUnion",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Union(e, 0, n, r, this.readNullBitmap(e, r), this.readTypeIds(e), this.visitMany(e.children))
+                        return ir.Union(e, 0, n, r, this.readNullBitmap(e, r), this.readTypeIds(e), this.visitMany(e.children))
                     }
                 }, {
                     key: "visitDictionary",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Dictionary(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e.indices), this.readDictionary(e))
+                        return ir.Dictionary(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e.indices), this.readDictionary(e))
                     }
                 }, {
                     key: "visitInterval",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Interval(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
+                        return ir.Interval(e, 0, n, r, this.readNullBitmap(e, r), this.readData(e))
                     }
                 }, {
                     key: "visitFixedSizeList",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.FixedSizeList(e, 0, n, r, this.readNullBitmap(e, r), this.visit(e.children[0]))
+                        return ir.FixedSizeList(e, 0, n, r, this.readNullBitmap(e, r), this.visit(e.children[0]))
                     }
                 }, {
                     key: "visitMap",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextFieldNode(),
                             n = t.length,
                             r = t.nullCount;
-                        return tr.Map(e, 0, n, r, this.readNullBitmap(e, r), this.readOffsets(e), this.visit(e.children[0]))
+                        return ir.Map(e, 0, n, r, this.readNullBitmap(e, r), this.readOffsets(e), this.visit(e.children[0]))
                     }
                 }, {
                     key: "nextFieldNode",
                     value: function() {
                         return this.nodes[++this.nodesIndex]
                     }
                 }, {
@@ -12397,288 +12412,288 @@
                     }
                 }, {
                     key: "readDictionary",
                     value: function(e) {
                         return this.dictionaries.get(e.id)
                     }
                 }]), n
-            }(on),
-            to = function(e) {
+            }(sn),
+            io = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e, r, i, a) {
                     var o;
                     return Object(D.a)(this, n), (o = t.call(this, new Uint8Array(0), r, i, a)).sources = e, o
                 }
                 return Object(M.a)(n, [{
                     key: "readNullBitmap",
                     value: function(e, t) {
                         var n = (arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : this.nextBufferRange()).offset;
-                        return t <= 0 ? new Uint8Array(0) : Zt(this.sources[n])
+                        return t <= 0 ? new Uint8Array(0) : nn(this.sources[n])
                     }
                 }, {
                     key: "readOffsets",
                     value: function(e) {
                         var t = (arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextBufferRange()).offset;
-                        return Fe(Uint8Array, Fe(Int32Array, this.sources[t]))
+                        return Ue(Uint8Array, Ue(Int32Array, this.sources[t]))
                     }
                 }, {
                     key: "readTypeIds",
                     value: function(e) {
                         var t = (arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextBufferRange()).offset;
-                        return Fe(Uint8Array, Fe(e.ArrayType, this.sources[t]))
+                        return Ue(Uint8Array, Ue(e.ArrayType, this.sources[t]))
                     }
                 }, {
                     key: "readData",
                     value: function(e) {
                         var t = (arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this.nextBufferRange()).offset,
                             n = this.sources;
-                        return kn.isTimestamp(e) || (kn.isInt(e) || kn.isTime(e)) && 64 === e.bitWidth || kn.isDate(e) && e.unit === zt.MILLISECOND ? Fe(Uint8Array, Ja.convertArray(n[t])) : kn.isDecimal(e) ? Fe(Uint8Array, Za.convertArray(n[t])) : kn.isBinary(e) || kn.isFixedSizeBinary(e) ? function(e) {
+                        return _n.isTimestamp(e) || (_n.isInt(e) || _n.isTime(e)) && 64 === e.bitWidth || _n.isDate(e) && e.unit === Yt.MILLISECOND ? Ue(Uint8Array, to.convertArray(n[t])) : _n.isDecimal(e) ? Ue(Uint8Array, no.convertArray(n[t])) : _n.isBinary(e) || _n.isFixedSizeBinary(e) ? function(e) {
                             for (var t = e.join(""), n = new Uint8Array(t.length / 2), r = 0; r < t.length; r += 2) n[r >> 1] = parseInt(t.substr(r, 2), 16);
                             return n
-                        }(n[t]) : kn.isBool(e) ? Zt(n[t]) : kn.isUtf8(e) ? ie(n[t].join("")) : Fe(Uint8Array, Fe(e.ArrayType, n[t].map((function(e) {
+                        }(n[t]) : _n.isBool(e) ? nn(n[t]) : _n.isUtf8(e) ? ie(n[t].join("")) : Ue(Uint8Array, Ue(e.ArrayType, n[t].map((function(e) {
                             return +e
                         }))))
                     }
                 }]), n
-            }(eo);
-        var no = Y.Long,
-            ro = Bt.apache.arrow.flatbuf.Null,
-            io = Bt.apache.arrow.flatbuf.Int,
-            ao = Bt.apache.arrow.flatbuf.FloatingPoint,
-            oo = Bt.apache.arrow.flatbuf.Binary,
-            uo = Bt.apache.arrow.flatbuf.Bool,
-            co = Bt.apache.arrow.flatbuf.Utf8,
-            so = Bt.apache.arrow.flatbuf.Decimal,
-            lo = Bt.apache.arrow.flatbuf.Date,
-            fo = Bt.apache.arrow.flatbuf.Time,
-            ho = Bt.apache.arrow.flatbuf.Timestamp,
-            po = Bt.apache.arrow.flatbuf.Interval,
-            yo = Bt.apache.arrow.flatbuf.List,
-            vo = Bt.apache.arrow.flatbuf.Struct_,
-            bo = Bt.apache.arrow.flatbuf.Union,
-            mo = Bt.apache.arrow.flatbuf.DictionaryEncoding,
-            go = Bt.apache.arrow.flatbuf.FixedSizeBinary,
-            ko = Bt.apache.arrow.flatbuf.FixedSizeList,
-            wo = Bt.apache.arrow.flatbuf.Map,
-            Oo = function(e) {
+            }(ro);
+        var ao = Y.Long,
+            oo = Lt.apache.arrow.flatbuf.Null,
+            uo = Lt.apache.arrow.flatbuf.Int,
+            co = Lt.apache.arrow.flatbuf.FloatingPoint,
+            so = Lt.apache.arrow.flatbuf.Binary,
+            lo = Lt.apache.arrow.flatbuf.Bool,
+            fo = Lt.apache.arrow.flatbuf.Utf8,
+            ho = Lt.apache.arrow.flatbuf.Decimal,
+            po = Lt.apache.arrow.flatbuf.Date,
+            yo = Lt.apache.arrow.flatbuf.Time,
+            vo = Lt.apache.arrow.flatbuf.Timestamp,
+            bo = Lt.apache.arrow.flatbuf.Interval,
+            mo = Lt.apache.arrow.flatbuf.List,
+            go = Lt.apache.arrow.flatbuf.Struct_,
+            ko = Lt.apache.arrow.flatbuf.Union,
+            wo = Lt.apache.arrow.flatbuf.DictionaryEncoding,
+            Oo = Lt.apache.arrow.flatbuf.FixedSizeBinary,
+            _o = Lt.apache.arrow.flatbuf.FixedSizeList,
+            jo = Lt.apache.arrow.flatbuf.Map,
+            xo = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "visit",
                     value: function(e, t) {
-                        return null == e || null == t ? void 0 : Ct(Object(At.a)(n.prototype), "visit", this).call(this, e, t)
+                        return null == e || null == t ? void 0 : Mt(Object(Dt.a)(n.prototype), "visit", this).call(this, e, t)
                     }
                 }, {
                     key: "visitNull",
                     value: function(e, t) {
-                        return ro.startNull(t), ro.endNull(t)
+                        return oo.startNull(t), oo.endNull(t)
                     }
                 }, {
                     key: "visitInt",
                     value: function(e, t) {
-                        return io.startInt(t), io.addBitWidth(t, e.bitWidth), io.addIsSigned(t, e.isSigned), io.endInt(t)
+                        return uo.startInt(t), uo.addBitWidth(t, e.bitWidth), uo.addIsSigned(t, e.isSigned), uo.endInt(t)
                     }
                 }, {
                     key: "visitFloat",
                     value: function(e, t) {
-                        return ao.startFloatingPoint(t), ao.addPrecision(t, e.precision), ao.endFloatingPoint(t)
+                        return co.startFloatingPoint(t), co.addPrecision(t, e.precision), co.endFloatingPoint(t)
                     }
                 }, {
                     key: "visitBinary",
                     value: function(e, t) {
-                        return oo.startBinary(t), oo.endBinary(t)
+                        return so.startBinary(t), so.endBinary(t)
                     }
                 }, {
                     key: "visitBool",
                     value: function(e, t) {
-                        return uo.startBool(t), uo.endBool(t)
+                        return lo.startBool(t), lo.endBool(t)
                     }
                 }, {
                     key: "visitUtf8",
                     value: function(e, t) {
-                        return co.startUtf8(t), co.endUtf8(t)
+                        return fo.startUtf8(t), fo.endUtf8(t)
                     }
                 }, {
                     key: "visitDecimal",
                     value: function(e, t) {
-                        return so.startDecimal(t), so.addScale(t, e.scale), so.addPrecision(t, e.precision), so.endDecimal(t)
+                        return ho.startDecimal(t), ho.addScale(t, e.scale), ho.addPrecision(t, e.precision), ho.endDecimal(t)
                     }
                 }, {
                     key: "visitDate",
                     value: function(e, t) {
-                        return lo.startDate(t), lo.addUnit(t, e.unit), lo.endDate(t)
+                        return po.startDate(t), po.addUnit(t, e.unit), po.endDate(t)
                     }
                 }, {
                     key: "visitTime",
                     value: function(e, t) {
-                        return fo.startTime(t), fo.addUnit(t, e.unit), fo.addBitWidth(t, e.bitWidth), fo.endTime(t)
+                        return yo.startTime(t), yo.addUnit(t, e.unit), yo.addBitWidth(t, e.bitWidth), yo.endTime(t)
                     }
                 }, {
                     key: "visitTimestamp",
                     value: function(e, t) {
                         var n = e.timezone && t.createString(e.timezone) || void 0;
-                        return ho.startTimestamp(t), ho.addUnit(t, e.unit), void 0 !== n && ho.addTimezone(t, n), ho.endTimestamp(t)
+                        return vo.startTimestamp(t), vo.addUnit(t, e.unit), void 0 !== n && vo.addTimezone(t, n), vo.endTimestamp(t)
                     }
                 }, {
                     key: "visitInterval",
                     value: function(e, t) {
-                        return po.startInterval(t), po.addUnit(t, e.unit), po.endInterval(t)
+                        return bo.startInterval(t), bo.addUnit(t, e.unit), bo.endInterval(t)
                     }
                 }, {
                     key: "visitList",
                     value: function(e, t) {
-                        return yo.startList(t), yo.endList(t)
+                        return mo.startList(t), mo.endList(t)
                     }
                 }, {
                     key: "visitStruct",
                     value: function(e, t) {
-                        return vo.startStruct_(t), vo.endStruct_(t)
+                        return go.startStruct_(t), go.endStruct_(t)
                     }
                 }, {
                     key: "visitUnion",
                     value: function(e, t) {
-                        bo.startTypeIdsVector(t, e.typeIds.length);
-                        var n = bo.createTypeIdsVector(t, e.typeIds);
-                        return bo.startUnion(t), bo.addMode(t, e.mode), bo.addTypeIds(t, n), bo.endUnion(t)
+                        ko.startTypeIdsVector(t, e.typeIds.length);
+                        var n = ko.createTypeIdsVector(t, e.typeIds);
+                        return ko.startUnion(t), ko.addMode(t, e.mode), ko.addTypeIds(t, n), ko.endUnion(t)
                     }
                 }, {
                     key: "visitDictionary",
                     value: function(e, t) {
                         var n = this.visit(e.indices, t);
-                        return mo.startDictionaryEncoding(t), mo.addId(t, new no(e.id, 0)), mo.addIsOrdered(t, e.isOrdered), void 0 !== n && mo.addIndexType(t, n), mo.endDictionaryEncoding(t)
+                        return wo.startDictionaryEncoding(t), wo.addId(t, new ao(e.id, 0)), wo.addIsOrdered(t, e.isOrdered), void 0 !== n && wo.addIndexType(t, n), wo.endDictionaryEncoding(t)
                     }
                 }, {
                     key: "visitFixedSizeBinary",
                     value: function(e, t) {
-                        return go.startFixedSizeBinary(t), go.addByteWidth(t, e.byteWidth), go.endFixedSizeBinary(t)
+                        return Oo.startFixedSizeBinary(t), Oo.addByteWidth(t, e.byteWidth), Oo.endFixedSizeBinary(t)
                     }
                 }, {
                     key: "visitFixedSizeList",
                     value: function(e, t) {
-                        return ko.startFixedSizeList(t), ko.addListSize(t, e.listSize), ko.endFixedSizeList(t)
+                        return _o.startFixedSizeList(t), _o.addListSize(t, e.listSize), _o.endFixedSizeList(t)
                     }
                 }, {
                     key: "visitMap",
                     value: function(e, t) {
-                        return wo.startMap(t), wo.addKeysSorted(t, e.keysSorted), wo.endMap(t)
+                        return jo.startMap(t), jo.addKeysSorted(t, e.keysSorted), jo.endMap(t)
                     }
                 }]), n
-            }(on),
-            _o = new Oo;
+            }(sn),
+            To = new xo;
 
-        function jo(e) {
-            return new Ho(e.count, To(e.columns), So(e.columns))
+        function So(e) {
+            return new qo(e.count, Eo(e.columns), Ao(e.columns))
         }
 
-        function xo(e, t) {
+        function Io(e, t) {
             return (e.children || []).filter(Boolean).map((function(e) {
-                return Zi.fromJSON(e, t)
+                return na.fromJSON(e, t)
             }))
         }
 
-        function To(e) {
+        function Eo(e) {
             return (e || []).reduce((function(e, t) {
-                return [].concat(Object(an.a)(e), [new qo(t.count, (n = t.VALIDITY, (n || []).reduce((function(e, t) {
+                return [].concat(Object(cn.a)(e), [new Xo(t.count, (n = t.VALIDITY, (n || []).reduce((function(e, t) {
                     return e + +(0 === t)
-                }), 0)))], Object(an.a)(To(t.children)));
+                }), 0)))], Object(cn.a)(Eo(t.children)));
                 var n
             }), [])
         }
 
-        function So(e) {
+        function Ao(e) {
             for (var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : [], n = -1, r = (e || []).length; ++n < r;) {
                 var i = e[n];
-                i.VALIDITY && t.push(new Ko(t.length, i.VALIDITY.length)), i.TYPE && t.push(new Ko(t.length, i.TYPE.length)), i.OFFSET && t.push(new Ko(t.length, i.OFFSET.length)), i.DATA && t.push(new Ko(t.length, i.DATA.length)), t = So(i.children, t)
+                i.VALIDITY && t.push(new Go(t.length, i.VALIDITY.length)), i.TYPE && t.push(new Go(t.length, i.TYPE.length)), i.OFFSET && t.push(new Go(t.length, i.OFFSET.length)), i.DATA && t.push(new Go(t.length, i.DATA.length)), t = Ao(i.children, t)
             }
             return t
         }
 
-        function Io(e) {
+        function Co(e) {
             return new Map(Object.entries(e || {}))
         }
 
-        function Eo(e) {
-            return new On(e.isSigned, e.bitWidth)
+        function Bo(e) {
+            return new xn(e.isSigned, e.bitWidth)
         }
 
-        function Ao(e, t) {
+        function Do(e, t) {
             var n = e.type.name;
             switch (n) {
                 case "NONE":
                 case "null":
-                    return new wn;
+                    return new jn;
                 case "binary":
-                    return new Ln;
+                    return new Pn;
                 case "utf8":
-                    return new Fn;
+                    return new Un;
                 case "bool":
-                    return new Nn;
+                    return new Rn;
                 case "list":
-                    return new Hn((t || [])[0]);
+                    return new qn((t || [])[0]);
                 case "struct":
                 case "struct_":
-                    return new $n(t || [])
+                    return new Qn(t || [])
             }
             switch (n) {
                 case "int":
                     var r = e.type;
-                    return new On(r.isSigned, r.bitWidth);
+                    return new xn(r.isSigned, r.bitWidth);
                 case "floatingpoint":
                     var i = e.type;
-                    return new Cn(Wt[i.precision]);
+                    return new Mn($t[i.precision]);
                 case "decimal":
                     var a = e.type;
-                    return new Pn(a.scale, a.precision);
+                    return new zn(a.scale, a.precision);
                 case "date":
                     var o = e.type;
-                    return new Un(zt[o.unit]);
+                    return new Vn(Yt[o.unit]);
                 case "time":
                     var u = e.type;
-                    return new Vn(Vt[u.unit], u.bitWidth);
+                    return new Hn(Ht[u.unit], u.bitWidth);
                 case "timestamp":
                     var c = e.type;
-                    return new Wn(Vt[c.unit], c.timezone);
+                    return new $n(Ht[c.unit], c.timezone);
                 case "interval":
                     var s = e.type;
-                    return new Yn(Ht[s.unit]);
+                    return new Kn(qt[s.unit]);
                 case "union":
                     var l = e.type;
-                    return new Kn(Yt[l.mode], l.typeIds || [], t || []);
+                    return new Gn(Kt[l.mode], l.typeIds || [], t || []);
                 case "fixedsizebinary":
                     var f = e.type;
-                    return new qn(f.byteWidth);
+                    return new Xn(f.byteWidth);
                 case "fixedsizelist":
                     var h = e.type;
-                    return new Qn(h.listSize, (t || [])[0]);
+                    return new Jn(h.listSize, (t || [])[0]);
                 case "map":
                     var d = e.type;
-                    return new Gn((t || [])[0], d.keysSorted)
+                    return new Zn((t || [])[0], d.keysSorted)
             }
             throw new Error('Unrecognized type: "'.concat(n, '"'))
         }
-        var Co = Y.Long,
-            Bo = Y.Builder,
-            Do = Y.ByteBuffer,
-            Mo = Bt.apache.arrow.flatbuf.Type,
-            Lo = Bt.apache.arrow.flatbuf.Field,
-            Fo = Bt.apache.arrow.flatbuf.Schema,
-            No = Bt.apache.arrow.flatbuf.Buffer,
-            Po = Nt.apache.arrow.flatbuf.Message,
-            Uo = Bt.apache.arrow.flatbuf.KeyValue,
-            Ro = Nt.apache.arrow.flatbuf.FieldNode,
-            zo = Bt.apache.arrow.flatbuf.Endianness,
-            Vo = Nt.apache.arrow.flatbuf.RecordBatch,
-            Wo = Nt.apache.arrow.flatbuf.DictionaryBatch,
-            Yo = function() {
+        var Mo = Y.Long,
+            Lo = Y.Builder,
+            Fo = Y.ByteBuffer,
+            No = Lt.apache.arrow.flatbuf.Type,
+            Po = Lt.apache.arrow.flatbuf.Field,
+            Uo = Lt.apache.arrow.flatbuf.Schema,
+            Ro = Lt.apache.arrow.flatbuf.Buffer,
+            zo = Rt.apache.arrow.flatbuf.Message,
+            Vo = Lt.apache.arrow.flatbuf.KeyValue,
+            Wo = Rt.apache.arrow.flatbuf.FieldNode,
+            Yo = Lt.apache.arrow.flatbuf.Endianness,
+            Ho = Rt.apache.arrow.flatbuf.RecordBatch,
+            $o = Rt.apache.arrow.flatbuf.DictionaryBatch,
+            Ko = function() {
                 function e(t, n, r, i) {
                     Object(D.a)(this, e), this._version = n, this._headerType = r, this.body = new Uint8Array(0), i && (this._createHeader = function() {
                         return i
                     }), this._bodyLength = "number" === typeof t ? t : t.low
                 }
                 return Object(M.a)(e, [{
                     key: "type",
@@ -12704,86 +12719,86 @@
                     key: "header",
                     value: function() {
                         return this._createHeader()
                     }
                 }, {
                     key: "isSchema",
                     value: function() {
-                        return this.headerType === $t.Schema
+                        return this.headerType === Qt.Schema
                     }
                 }, {
                     key: "isRecordBatch",
                     value: function() {
-                        return this.headerType === $t.RecordBatch
+                        return this.headerType === Qt.RecordBatch
                     }
                 }, {
                     key: "isDictionaryBatch",
                     value: function() {
-                        return this.headerType === $t.DictionaryBatch
+                        return this.headerType === Qt.DictionaryBatch
                     }
                 }], [{
                     key: "fromJSON",
                     value: function(t, n) {
-                        var r = new e(0, Kt.V4, n);
+                        var r = new e(0, Gt.V4, n);
                         return r._createHeader = function(e, t) {
                             return function() {
                                 switch (t) {
-                                    case $t.Schema:
-                                        return Ji.fromJSON(e);
-                                    case $t.RecordBatch:
-                                        return Ho.fromJSON(e);
-                                    case $t.DictionaryBatch:
-                                        return $o.fromJSON(e)
+                                    case Qt.Schema:
+                                        return ta.fromJSON(e);
+                                    case Qt.RecordBatch:
+                                        return qo.fromJSON(e);
+                                    case Qt.DictionaryBatch:
+                                        return Qo.fromJSON(e)
                                 }
-                                throw new Error("Unrecognized Message type: { name: ".concat($t[t], ", type: ").concat(t, " }"))
+                                throw new Error("Unrecognized Message type: { name: ".concat(Qt[t], ", type: ").concat(t, " }"))
                             }
                         }(t, n), r
                     }
                 }, {
                     key: "decode",
                     value: function(t) {
-                        t = new Do(ze(t));
-                        var n = Po.getRootAsMessage(t),
+                        t = new Fo(Ye(t));
+                        var n = zo.getRootAsMessage(t),
                             r = n.bodyLength(),
                             i = n.version(),
                             a = n.headerType(),
                             o = new e(r, i, a);
                         return o._createHeader = function(e, t) {
                             return function() {
                                 switch (t) {
-                                    case $t.Schema:
-                                        return Ji.decode(e.header(new Fo));
-                                    case $t.RecordBatch:
-                                        return Ho.decode(e.header(new Vo), e.version());
-                                    case $t.DictionaryBatch:
-                                        return $o.decode(e.header(new Wo), e.version())
+                                    case Qt.Schema:
+                                        return ta.decode(e.header(new Uo));
+                                    case Qt.RecordBatch:
+                                        return qo.decode(e.header(new Ho), e.version());
+                                    case Qt.DictionaryBatch:
+                                        return Qo.decode(e.header(new $o), e.version())
                                 }
-                                throw new Error("Unrecognized Message type: { name: ".concat($t[t], ", type: ").concat(t, " }"))
+                                throw new Error("Unrecognized Message type: { name: ".concat(Qt[t], ", type: ").concat(t, " }"))
                             }
                         }(n, a), o
                     }
                 }, {
                     key: "encode",
                     value: function(e) {
-                        var t = new Bo,
+                        var t = new Lo,
                             n = -1;
-                        return e.isSchema() ? n = Ji.encode(t, e.header()) : e.isRecordBatch() ? n = Ho.encode(t, e.header()) : e.isDictionaryBatch() && (n = $o.encode(t, e.header())), Po.startMessage(t), Po.addVersion(t, Kt.V4), Po.addHeader(t, n), Po.addHeaderType(t, e.headerType), Po.addBodyLength(t, new Co(e.bodyLength, 0)), Po.finishMessageBuffer(t, Po.endMessage(t)), t.asUint8Array()
+                        return e.isSchema() ? n = ta.encode(t, e.header()) : e.isRecordBatch() ? n = qo.encode(t, e.header()) : e.isDictionaryBatch() && (n = Qo.encode(t, e.header())), zo.startMessage(t), zo.addVersion(t, Gt.V4), zo.addHeader(t, n), zo.addHeaderType(t, e.headerType), zo.addBodyLength(t, new Mo(e.bodyLength, 0)), zo.finishMessageBuffer(t, zo.endMessage(t)), t.asUint8Array()
                     }
                 }, {
                     key: "from",
                     value: function(t) {
                         var n = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : 0;
-                        if (t instanceof Ji) return new e(0, Kt.V4, $t.Schema, t);
-                        if (t instanceof Ho) return new e(n, Kt.V4, $t.RecordBatch, t);
-                        if (t instanceof $o) return new e(n, Kt.V4, $t.DictionaryBatch, t);
+                        if (t instanceof ta) return new e(0, Gt.V4, Qt.Schema, t);
+                        if (t instanceof qo) return new e(n, Gt.V4, Qt.RecordBatch, t);
+                        if (t instanceof Qo) return new e(n, Gt.V4, Qt.DictionaryBatch, t);
                         throw new Error("Unrecognized Message header: ".concat(t))
                     }
                 }]), e
             }(),
-            Ho = function() {
+            qo = function() {
                 function e(t, n, r) {
                     Object(D.a)(this, e), this._nodes = n, this._buffers = r, this._length = "number" === typeof t ? t : t.low
                 }
                 return Object(M.a)(e, [{
                     key: "nodes",
                     get: function() {
                         return this._nodes
@@ -12796,15 +12811,15 @@
                 }, {
                     key: "buffers",
                     get: function() {
                         return this._buffers
                     }
                 }]), e
             }(),
-            $o = function() {
+            Qo = function() {
                 function e(t, n) {
                     var r = arguments.length > 2 && void 0 !== arguments[2] && arguments[2];
                     Object(D.a)(this, e), this._data = t, this._isDelta = r, this._id = "number" === typeof n ? n : n.low
                 }
                 return Object(M.a)(e, [{
                     key: "id",
                     get: function() {
@@ -12833,202 +12848,202 @@
                 }, {
                     key: "buffers",
                     get: function() {
                         return this.data.buffers
                     }
                 }]), e
             }(),
-            Ko = Object(M.a)((function e(t, n) {
+            Go = Object(M.a)((function e(t, n) {
                 Object(D.a)(this, e), this.offset = "number" === typeof t ? t : t.low, this.length = "number" === typeof n ? n : n.low
             })),
-            qo = Object(M.a)((function e(t, n) {
+            Xo = Object(M.a)((function e(t, n) {
                 Object(D.a)(this, e), this.length = "number" === typeof t ? t : t.low, this.nullCount = "number" === typeof n ? n : n.low
             }));
 
-        function Qo(e, t) {
-            for (var n, r = [], i = -1, a = -1, o = e.childrenLength(); ++i < o;)(n = e.children(i)) && (r[++a] = Zi.decode(n, t));
+        function Jo(e, t) {
+            for (var n, r = [], i = -1, a = -1, o = e.childrenLength(); ++i < o;)(n = e.children(i)) && (r[++a] = na.decode(n, t));
             return r
         }
 
-        function Go(e) {
+        function Zo(e) {
             var t = new Map;
             if (e)
                 for (var n, r, i = -1, a = 0 | e.customMetadataLength(); ++i < a;)(n = e.customMetadata(i)) && null != (r = n.key()) && t.set(r, n.value());
             return t
         }
 
-        function Xo(e) {
-            return new On(e.isSigned(), e.bitWidth())
+        function eu(e) {
+            return new xn(e.isSigned(), e.bitWidth())
         }
 
-        function Jo(e, t) {
+        function tu(e, t) {
             var n = e.typeType();
             switch (n) {
-                case Mo.NONE:
-                case Mo.Null:
-                    return new wn;
-                case Mo.Binary:
-                    return new Ln;
-                case Mo.Utf8:
-                    return new Fn;
-                case Mo.Bool:
-                    return new Nn;
-                case Mo.List:
-                    return new Hn((t || [])[0]);
-                case Mo.Struct_:
-                    return new $n(t || [])
+                case No.NONE:
+                case No.Null:
+                    return new jn;
+                case No.Binary:
+                    return new Pn;
+                case No.Utf8:
+                    return new Un;
+                case No.Bool:
+                    return new Rn;
+                case No.List:
+                    return new qn((t || [])[0]);
+                case No.Struct_:
+                    return new Qn(t || [])
             }
             switch (n) {
-                case Mo.Int:
-                    var r = e.type(new Bt.apache.arrow.flatbuf.Int);
-                    return new On(r.isSigned(), r.bitWidth());
-                case Mo.FloatingPoint:
-                    var i = e.type(new Bt.apache.arrow.flatbuf.FloatingPoint);
-                    return new Cn(i.precision());
-                case Mo.Decimal:
-                    var a = e.type(new Bt.apache.arrow.flatbuf.Decimal);
-                    return new Pn(a.scale(), a.precision());
-                case Mo.Date:
-                    var o = e.type(new Bt.apache.arrow.flatbuf.Date);
-                    return new Un(o.unit());
-                case Mo.Time:
-                    var u = e.type(new Bt.apache.arrow.flatbuf.Time);
-                    return new Vn(u.unit(), u.bitWidth());
-                case Mo.Timestamp:
-                    var c = e.type(new Bt.apache.arrow.flatbuf.Timestamp);
-                    return new Wn(c.unit(), c.timezone());
-                case Mo.Interval:
-                    var s = e.type(new Bt.apache.arrow.flatbuf.Interval);
-                    return new Yn(s.unit());
-                case Mo.Union:
-                    var l = e.type(new Bt.apache.arrow.flatbuf.Union);
-                    return new Kn(l.mode(), l.typeIdsArray() || [], t || []);
-                case Mo.FixedSizeBinary:
-                    var f = e.type(new Bt.apache.arrow.flatbuf.FixedSizeBinary);
-                    return new qn(f.byteWidth());
-                case Mo.FixedSizeList:
-                    var h = e.type(new Bt.apache.arrow.flatbuf.FixedSizeList);
-                    return new Qn(h.listSize(), (t || [])[0]);
-                case Mo.Map:
-                    var d = e.type(new Bt.apache.arrow.flatbuf.Map);
-                    return new Gn((t || [])[0], d.keysSorted())
+                case No.Int:
+                    var r = e.type(new Lt.apache.arrow.flatbuf.Int);
+                    return new xn(r.isSigned(), r.bitWidth());
+                case No.FloatingPoint:
+                    var i = e.type(new Lt.apache.arrow.flatbuf.FloatingPoint);
+                    return new Mn(i.precision());
+                case No.Decimal:
+                    var a = e.type(new Lt.apache.arrow.flatbuf.Decimal);
+                    return new zn(a.scale(), a.precision());
+                case No.Date:
+                    var o = e.type(new Lt.apache.arrow.flatbuf.Date);
+                    return new Vn(o.unit());
+                case No.Time:
+                    var u = e.type(new Lt.apache.arrow.flatbuf.Time);
+                    return new Hn(u.unit(), u.bitWidth());
+                case No.Timestamp:
+                    var c = e.type(new Lt.apache.arrow.flatbuf.Timestamp);
+                    return new $n(c.unit(), c.timezone());
+                case No.Interval:
+                    var s = e.type(new Lt.apache.arrow.flatbuf.Interval);
+                    return new Kn(s.unit());
+                case No.Union:
+                    var l = e.type(new Lt.apache.arrow.flatbuf.Union);
+                    return new Gn(l.mode(), l.typeIdsArray() || [], t || []);
+                case No.FixedSizeBinary:
+                    var f = e.type(new Lt.apache.arrow.flatbuf.FixedSizeBinary);
+                    return new Xn(f.byteWidth());
+                case No.FixedSizeList:
+                    var h = e.type(new Lt.apache.arrow.flatbuf.FixedSizeList);
+                    return new Jn(h.listSize(), (t || [])[0]);
+                case No.Map:
+                    var d = e.type(new Lt.apache.arrow.flatbuf.Map);
+                    return new Zn((t || [])[0], d.keysSorted())
             }
-            throw new Error('Unrecognized type: "'.concat(Mo[n], '" (').concat(n, ")"))
+            throw new Error('Unrecognized type: "'.concat(No[n], '" (').concat(n, ")"))
         }
-        Zi.encode = function(e, t) {
+        na.encode = function(e, t) {
             var n = -1,
                 r = -1,
                 i = -1,
                 a = t.type,
                 o = t.typeId;
-            kn.isDictionary(a) ? (o = a.dictionary.typeId, i = _o.visit(a, e), r = _o.visit(a.dictionary, e)) : r = _o.visit(a, e);
+            _n.isDictionary(a) ? (o = a.dictionary.typeId, i = To.visit(a, e), r = To.visit(a.dictionary, e)) : r = To.visit(a, e);
             var u = (a.children || []).map((function(t) {
-                    return Zi.encode(e, t)
+                    return na.encode(e, t)
                 })),
-                c = Lo.createChildrenVector(e, u),
-                s = t.metadata && t.metadata.size > 0 ? Lo.createCustomMetadataVector(e, Object(an.a)(t.metadata).map((function(t) {
-                    var n = F(t, 2),
+                c = Po.createChildrenVector(e, u),
+                s = t.metadata && t.metadata.size > 0 ? Po.createCustomMetadataVector(e, Object(cn.a)(t.metadata).map((function(t) {
+                    var n = Object(F.a)(t, 2),
                         r = n[0],
                         i = n[1],
                         a = e.createString("".concat(r)),
                         o = e.createString("".concat(i));
-                    return Uo.startKeyValue(e), Uo.addKey(e, a), Uo.addValue(e, o), Uo.endKeyValue(e)
+                    return Vo.startKeyValue(e), Vo.addKey(e, a), Vo.addValue(e, o), Vo.endKeyValue(e)
                 }))) : -1;
             t.name && (n = e.createString(t.name));
-            Lo.startField(e), Lo.addType(e, r), Lo.addTypeType(e, o), Lo.addChildren(e, c), Lo.addNullable(e, !!t.nullable), -1 !== n && Lo.addName(e, n); - 1 !== i && Lo.addDictionary(e, i); - 1 !== s && Lo.addCustomMetadata(e, s);
-            return Lo.endField(e)
-        }, Zi.decode = function(e, t) {
+            Po.startField(e), Po.addType(e, r), Po.addTypeType(e, o), Po.addChildren(e, c), Po.addNullable(e, !!t.nullable), -1 !== n && Po.addName(e, n); - 1 !== i && Po.addDictionary(e, i); - 1 !== s && Po.addCustomMetadata(e, s);
+            return Po.endField(e)
+        }, na.decode = function(e, t) {
             var n, r, i, a, o, u;
-            t && (u = e.dictionary()) ? t.has(n = u.id().low) ? (a = (a = u.indexType()) ? Xo(a) : new xn, o = new Zn(t.get(n), a, n, u.isOrdered()), r = new Zi(e.name(), o, e.nullable(), Go(e))) : (a = (a = u.indexType()) ? Xo(a) : new xn, t.set(n, i = Jo(e, Qo(e, t))), o = new Zn(i, a, n, u.isOrdered()), r = new Zi(e.name(), o, e.nullable(), Go(e))) : (i = Jo(e, Qo(e, t)), r = new Zi(e.name(), i, e.nullable(), Go(e)));
+            t && (u = e.dictionary()) ? t.has(n = u.id().low) ? (a = (a = u.indexType()) ? eu(a) : new In, o = new nr(t.get(n), a, n, u.isOrdered()), r = new na(e.name(), o, e.nullable(), Zo(e))) : (a = (a = u.indexType()) ? eu(a) : new In, t.set(n, i = tu(e, Jo(e, t))), o = new nr(i, a, n, u.isOrdered()), r = new na(e.name(), o, e.nullable(), Zo(e))) : (i = tu(e, Jo(e, t)), r = new na(e.name(), i, e.nullable(), Zo(e)));
             return r || null
-        }, Zi.fromJSON = function(e, t) {
+        }, na.fromJSON = function(e, t) {
             var n, r, i, a, o, u;
-            return t && (a = e.dictionary) ? t.has(n = a.id) ? (r = (r = a.indexType) ? Eo(r) : new xn, u = new Zn(t.get(n), r, n, a.isOrdered), i = new Zi(e.name, u, e.nullable, Io(e.customMetadata))) : (r = (r = a.indexType) ? Eo(r) : new xn, t.set(n, o = Ao(e, xo(e, t))), u = new Zn(o, r, n, a.isOrdered), i = new Zi(e.name, u, e.nullable, Io(e.customMetadata))) : (o = Ao(e, xo(e, t)), i = new Zi(e.name, o, e.nullable, Io(e.customMetadata))), i || null
-        }, Ji.encode = function(e, t) {
+            return t && (a = e.dictionary) ? t.has(n = a.id) ? (r = (r = a.indexType) ? Bo(r) : new In, u = new nr(t.get(n), r, n, a.isOrdered), i = new na(e.name, u, e.nullable, Co(e.customMetadata))) : (r = (r = a.indexType) ? Bo(r) : new In, t.set(n, o = Do(e, Io(e, t))), u = new nr(o, r, n, a.isOrdered), i = new na(e.name, u, e.nullable, Co(e.customMetadata))) : (o = Do(e, Io(e, t)), i = new na(e.name, o, e.nullable, Co(e.customMetadata))), i || null
+        }, ta.encode = function(e, t) {
             var n = t.fields.map((function(t) {
-                return Zi.encode(e, t)
+                return na.encode(e, t)
             }));
-            Fo.startFieldsVector(e, n.length);
-            var r = Fo.createFieldsVector(e, n),
-                i = t.metadata && t.metadata.size > 0 ? Fo.createCustomMetadataVector(e, Object(an.a)(t.metadata).map((function(t) {
-                    var n = F(t, 2),
+            Uo.startFieldsVector(e, n.length);
+            var r = Uo.createFieldsVector(e, n),
+                i = t.metadata && t.metadata.size > 0 ? Uo.createCustomMetadataVector(e, Object(cn.a)(t.metadata).map((function(t) {
+                    var n = Object(F.a)(t, 2),
                         r = n[0],
                         i = n[1],
                         a = e.createString("".concat(r)),
                         o = e.createString("".concat(i));
-                    return Uo.startKeyValue(e), Uo.addKey(e, a), Uo.addValue(e, o), Uo.endKeyValue(e)
+                    return Vo.startKeyValue(e), Vo.addKey(e, a), Vo.addValue(e, o), Vo.endKeyValue(e)
                 }))) : -1;
-            Fo.startSchema(e), Fo.addFields(e, r), Fo.addEndianness(e, Zo ? zo.Little : zo.Big), -1 !== i && Fo.addCustomMetadata(e, i);
-            return Fo.endSchema(e)
-        }, Ji.decode = function(e) {
+            Uo.startSchema(e), Uo.addFields(e, r), Uo.addEndianness(e, nu ? Yo.Little : Yo.Big), -1 !== i && Uo.addCustomMetadata(e, i);
+            return Uo.endSchema(e)
+        }, ta.decode = function(e) {
             var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : new Map,
                 n = function(e, t) {
-                    for (var n, r = [], i = -1, a = -1, o = e.fieldsLength(); ++i < o;)(n = e.fields(i)) && (r[++a] = Zi.decode(n, t));
+                    for (var n, r = [], i = -1, a = -1, o = e.fieldsLength(); ++i < o;)(n = e.fields(i)) && (r[++a] = na.decode(n, t));
                     return r
                 }(e, t);
-            return new Ji(n, Go(e), t)
-        }, Ji.fromJSON = function(e) {
+            return new ta(n, Zo(e), t)
+        }, ta.fromJSON = function(e) {
             var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : new Map;
-            return new Ji(function(e, t) {
+            return new ta(function(e, t) {
                 return (e.fields || []).filter(Boolean).map((function(e) {
-                    return Zi.fromJSON(e, t)
+                    return na.fromJSON(e, t)
                 }))
-            }(e, t), Io(e.customMetadata), t)
-        }, Ho.encode = function(e, t) {
+            }(e, t), Co(e.customMetadata), t)
+        }, qo.encode = function(e, t) {
             var n = t.nodes || [],
                 r = t.buffers || [];
-            Vo.startNodesVector(e, n.length), n.slice().reverse().forEach((function(t) {
-                return qo.encode(e, t)
+            Ho.startNodesVector(e, n.length), n.slice().reverse().forEach((function(t) {
+                return Xo.encode(e, t)
             }));
             var i = e.endVector();
-            Vo.startBuffersVector(e, r.length), r.slice().reverse().forEach((function(t) {
-                return Ko.encode(e, t)
+            Ho.startBuffersVector(e, r.length), r.slice().reverse().forEach((function(t) {
+                return Go.encode(e, t)
             }));
             var a = e.endVector();
-            return Vo.startRecordBatch(e), Vo.addLength(e, new Co(t.length, 0)), Vo.addNodes(e, i), Vo.addBuffers(e, a), Vo.endRecordBatch(e)
-        }, Ho.decode = function(e) {
-            var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : Kt.V4;
-            return new Ho(e.length(), function(e) {
-                for (var t, n = [], r = -1, i = -1, a = e.nodesLength(); ++r < a;)(t = e.nodes(r)) && (n[++i] = qo.decode(t));
+            return Ho.startRecordBatch(e), Ho.addLength(e, new Mo(t.length, 0)), Ho.addNodes(e, i), Ho.addBuffers(e, a), Ho.endRecordBatch(e)
+        }, qo.decode = function(e) {
+            var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : Gt.V4;
+            return new qo(e.length(), function(e) {
+                for (var t, n = [], r = -1, i = -1, a = e.nodesLength(); ++r < a;)(t = e.nodes(r)) && (n[++i] = Xo.decode(t));
                 return n
             }(e), function(e, t) {
-                for (var n, r = [], i = -1, a = -1, o = e.buffersLength(); ++i < o;)(n = e.buffers(i)) && (t < Kt.V4 && (n.bb_pos += 8 * (i + 1)), r[++a] = Ko.decode(n));
+                for (var n, r = [], i = -1, a = -1, o = e.buffersLength(); ++i < o;)(n = e.buffers(i)) && (t < Gt.V4 && (n.bb_pos += 8 * (i + 1)), r[++a] = Go.decode(n));
                 return r
             }(e, t))
-        }, Ho.fromJSON = jo, $o.encode = function(e, t) {
-            var n = Ho.encode(e, t.data);
-            return Wo.startDictionaryBatch(e), Wo.addId(e, new Co(t.id, 0)), Wo.addIsDelta(e, t.isDelta), Wo.addData(e, n), Wo.endDictionaryBatch(e)
-        }, $o.decode = function(e) {
-            var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : Kt.V4;
-            return new $o(Ho.decode(e.data(), t), e.id(), e.isDelta())
-        }, $o.fromJSON = function(e) {
-            return new $o(jo(e.data), e.id, e.isDelta)
-        }, qo.encode = function(e, t) {
-            return Ro.createFieldNode(e, new Co(t.length, 0), new Co(t.nullCount, 0))
-        }, qo.decode = function(e) {
-            return new qo(e.length(), e.nullCount())
-        }, Ko.encode = function(e, t) {
-            return No.createBuffer(e, new Co(t.offset, 0), new Co(t.length, 0))
-        }, Ko.decode = function(e) {
-            return new Ko(e.offset(), e.length())
+        }, qo.fromJSON = So, Qo.encode = function(e, t) {
+            var n = qo.encode(e, t.data);
+            return $o.startDictionaryBatch(e), $o.addId(e, new Mo(t.id, 0)), $o.addIsDelta(e, t.isDelta), $o.addData(e, n), $o.endDictionaryBatch(e)
+        }, Qo.decode = function(e) {
+            var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : Gt.V4;
+            return new Qo(qo.decode(e.data(), t), e.id(), e.isDelta())
+        }, Qo.fromJSON = function(e) {
+            return new Qo(So(e.data), e.id, e.isDelta)
+        }, Xo.encode = function(e, t) {
+            return Wo.createFieldNode(e, new Mo(t.length, 0), new Mo(t.nullCount, 0))
+        }, Xo.decode = function(e) {
+            return new Xo(e.length(), e.nullCount())
+        }, Go.encode = function(e, t) {
+            return Ro.createBuffer(e, new Mo(t.offset, 0), new Mo(t.length, 0))
+        }, Go.decode = function(e) {
+            return new Go(e.offset(), e.length())
         };
-        for (var Zo = function() {
+        for (var nu = function() {
                 var e = new ArrayBuffer(2);
                 return new DataView(e).setInt16(0, 256, !0), 256 === new Int16Array(e)[0]
-            }(), eu = Y.ByteBuffer, tu = function(e) {
-                return "Expected ".concat($t[e], " Message in stream, but was null or length 0.")
-            }, nu = function(e) {
-                return "Header pointer of flatbuffer-encoded ".concat($t[e], " Message is null or length 0.")
-            }, ru = function(e, t) {
+            }(), ru = Y.ByteBuffer, iu = function(e) {
+                return "Expected ".concat(Qt[e], " Message in stream, but was null or length 0.")
+            }, au = function(e) {
+                return "Header pointer of flatbuffer-encoded ".concat(Qt[e], " Message is null or length 0.")
+            }, ou = function(e, t) {
                 return "Expected to read ".concat(e, " metadata bytes, but only read ").concat(t, ".")
-            }, iu = function(e, t) {
+            }, uu = function(e, t) {
                 return "Expected to read ".concat(e, " bytes for message body, but only read ").concat(t, ".")
-            }, au = function(e) {
+            }, cu = function(e) {
                 function t(e) {
-                    Object(D.a)(this, t), this.source = e instanceof Va ? e : new Va(e)
+                    Object(D.a)(this, t), this.source = e instanceof Ha ? e : new Ha(e)
                 }
                 return Object(M.a)(t, [{
                     key: e,
                     value: function() {
                         return this
                     }
                 }, {
@@ -13048,61 +13063,61 @@
                         return this.source.return(e)
                     }
                 }, {
                     key: "readMessage",
                     value: function(e) {
                         var t;
                         if ((t = this.next()).done) return null;
-                        if (null != e && t.value.headerType !== e) throw new Error(tu(e));
+                        if (null != e && t.value.headerType !== e) throw new Error(iu(e));
                         return t.value
                     }
                 }, {
                     key: "readMessageBody",
                     value: function(e) {
                         if (e <= 0) return new Uint8Array(0);
-                        var t = ze(this.source.read(e));
-                        if (t.byteLength < e) throw new Error(iu(e, t.byteLength));
+                        var t = Ye(this.source.read(e));
+                        if (t.byteLength < e) throw new Error(uu(e, t.byteLength));
                         return t.byteOffset % 8 === 0 && t.byteOffset + t.byteLength <= t.buffer.byteLength ? t : t.slice()
                     }
                 }, {
                     key: "readSchema",
                     value: function() {
                         var e = arguments.length > 0 && void 0 !== arguments[0] && arguments[0],
-                            t = $t.Schema,
+                            t = Qt.Schema,
                             n = this.readMessage(t),
                             r = n && n.header();
-                        if (e && !r) throw new Error(nu(t));
+                        if (e && !r) throw new Error(au(t));
                         return r
                     }
                 }, {
                     key: "readMetadataLength",
                     value: function() {
-                        var e = this.source.read(cu),
-                            t = e && new eu(e),
+                        var e = this.source.read(fu),
+                            t = e && new ru(e),
                             n = t && t.readInt32(0) || 0;
                         return {
                             done: 0 === n,
                             value: n
                         }
                     }
                 }, {
                     key: "readMetadata",
                     value: function(e) {
                         var t = this.source.read(e);
                         if (!t) return ue;
-                        if (t.byteLength < e) throw new Error(ru(e, t.byteLength));
+                        if (t.byteLength < e) throw new Error(ou(e, t.byteLength));
                         return {
                             done: !1,
-                            value: Yo.decode(t)
+                            value: Ko.decode(t)
                         }
                     }
                 }]), t
-            }(Symbol.iterator), ou = function(e) {
+            }(Symbol.iterator), su = function(e) {
                 function t(e, n) {
-                    Object(D.a)(this, t), this.source = e instanceof Wa ? e : Se(e) ? new Ka(e, n) : new Wa(e)
+                    Object(D.a)(this, t), this.source = e instanceof $a ? e : Ae(e) ? new Ga(e, n) : new $a(e)
                 }
                 return Object(M.a)(t, [{
                     key: e,
                     value: function() {
                         return this
                     }
                 }, {
@@ -13210,15 +13225,15 @@
                                         }
                                         return e.abrupt("return", null);
                                     case 4:
                                         if (null == t || n.value.headerType === t) {
                                             e.next = 6;
                                             break
                                         }
-                                        throw new Error(tu(t));
+                                        throw new Error(iu(t));
                                     case 6:
                                         return e.abrupt("return", n.value);
                                     case 7:
                                     case "end":
                                         return e.stop()
                                 }
                             }), e, this)
@@ -13237,21 +13252,21 @@
                                     case 0:
                                         if (!(t <= 0)) {
                                             e.next = 2;
                                             break
                                         }
                                         return e.abrupt("return", new Uint8Array(0));
                                     case 2:
-                                        return e.t0 = ze, e.next = 5, this.source.read(t);
+                                        return e.t0 = Ye, e.next = 5, this.source.read(t);
                                     case 5:
                                         if (e.t1 = e.sent, !((n = (0, e.t0)(e.t1)).byteLength < t)) {
                                             e.next = 9;
                                             break
                                         }
-                                        throw new Error(iu(t, n.byteLength));
+                                        throw new Error(uu(t, n.byteLength));
                                     case 9:
                                         return e.abrupt("return", n.byteOffset % 8 === 0 && n.byteOffset + n.byteLength <= n.buffer.byteLength ? n : n.slice());
                                     case 10:
                                     case "end":
                                         return e.stop()
                                 }
                             }), e, this)
@@ -13264,21 +13279,21 @@
                     key: "readSchema",
                     value: function() {
                         var e = Object(B.a)(Object(L.a)().mark((function e() {
                             var t, n, r, i, a = arguments;
                             return Object(L.a)().wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
                                     case 0:
-                                        return t = a.length > 0 && void 0 !== a[0] && a[0], n = $t.Schema, e.next = 4, this.readMessage(n);
+                                        return t = a.length > 0 && void 0 !== a[0] && a[0], n = Qt.Schema, e.next = 4, this.readMessage(n);
                                     case 4:
                                         if (r = e.sent, i = r && r.header(), !t || i) {
                                             e.next = 8;
                                             break
                                         }
-                                        throw new Error(nu(n));
+                                        throw new Error(au(n));
                                     case 8:
                                         return e.abrupt("return", i);
                                     case 9:
                                     case "end":
                                         return e.stop()
                                 }
                             }), e, this)
@@ -13291,17 +13306,17 @@
                     key: "readMetadataLength",
                     value: function() {
                         var e = Object(B.a)(Object(L.a)().mark((function e() {
                             var t, n, r;
                             return Object(L.a)().wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
                                     case 0:
-                                        return e.next = 2, this.source.read(cu);
+                                        return e.next = 2, this.source.read(fu);
                                     case 2:
-                                        return t = e.sent, n = t && new eu(t), r = n && n.readInt32(0) || 0, e.abrupt("return", {
+                                        return t = e.sent, n = t && new ru(t), r = n && n.readInt32(0) || 0, e.abrupt("return", {
                                             done: 0 === r,
                                             value: r
                                         });
                                     case 6:
                                     case "end":
                                         return e.stop()
                                 }
@@ -13327,119 +13342,119 @@
                                         }
                                         return e.abrupt("return", ue);
                                     case 5:
                                         if (!(n.byteLength < t)) {
                                             e.next = 7;
                                             break
                                         }
-                                        throw new Error(ru(t, n.byteLength));
+                                        throw new Error(ou(t, n.byteLength));
                                     case 7:
                                         return e.abrupt("return", {
                                             done: !1,
-                                            value: Yo.decode(n)
+                                            value: Ko.decode(n)
                                         });
                                     case 8:
                                     case "end":
                                         return e.stop()
                                 }
                             }), e, this)
                         })));
                         return function(t) {
                             return e.apply(this, arguments)
                         }
                     }()
                 }]), t
-            }(Symbol.asyncIterator), uu = function(e) {
+            }(Symbol.asyncIterator), lu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
                     return Object(D.a)(this, n), (r = t.call(this, new Uint8Array(0)))._schema = !1, r._body = [], r._batchIndex = 0, r._dictionaryIndex = 0, r._json = e instanceof ce ? e : new ce(e), r
                 }
                 return Object(M.a)(n, [{
                     key: "next",
                     value: function() {
                         var e = this._json;
                         if (!this._schema) return this._schema = !0, {
                             done: !1,
-                            value: Yo.fromJSON(e.schema, $t.Schema)
+                            value: Ko.fromJSON(e.schema, Qt.Schema)
                         };
                         if (this._dictionaryIndex < e.dictionaries.length) {
                             var t = e.dictionaries[this._dictionaryIndex++];
                             return this._body = t.data.columns, {
                                 done: !1,
-                                value: Yo.fromJSON(t, $t.DictionaryBatch)
+                                value: Ko.fromJSON(t, Qt.DictionaryBatch)
                             }
                         }
                         if (this._batchIndex < e.batches.length) {
                             var n = e.batches[this._batchIndex++];
                             return this._body = n.columns, {
                                 done: !1,
-                                value: Yo.fromJSON(n, $t.RecordBatch)
+                                value: Ko.fromJSON(n, Qt.RecordBatch)
                             }
                         }
                         return this._body = [], ue
                     }
                 }, {
                     key: "readMessageBody",
                     value: function(e) {
                         return function e(t) {
                             return (t || []).reduce((function(t, n) {
-                                return [].concat(Object(an.a)(t), Object(an.a)(n.VALIDITY && [n.VALIDITY] || []), Object(an.a)(n.TYPE && [n.TYPE] || []), Object(an.a)(n.OFFSET && [n.OFFSET] || []), Object(an.a)(n.DATA && [n.DATA] || []), Object(an.a)(e(n.children)))
+                                return [].concat(Object(cn.a)(t), Object(cn.a)(n.VALIDITY && [n.VALIDITY] || []), Object(cn.a)(n.TYPE && [n.TYPE] || []), Object(cn.a)(n.OFFSET && [n.OFFSET] || []), Object(cn.a)(n.DATA && [n.DATA] || []), Object(cn.a)(e(n.children)))
                             }), [])
                         }(this._body)
                     }
                 }, {
                     key: "readMessage",
                     value: function(e) {
                         var t;
                         if ((t = this.next()).done) return null;
-                        if (null != e && t.value.headerType !== e) throw new Error(tu(e));
+                        if (null != e && t.value.headerType !== e) throw new Error(iu(e));
                         return t.value
                     }
                 }, {
                     key: "readSchema",
                     value: function() {
-                        var e = $t.Schema,
+                        var e = Qt.Schema,
                             t = this.readMessage(e),
                             n = t && t.header();
-                        if (!t || !n) throw new Error(nu(e));
+                        if (!t || !n) throw new Error(au(e));
                         return n
                     }
                 }]), n
-            }(au), cu = 4, su = "ARROW1", lu = new Uint8Array(6), fu = 0; fu < 6; fu += 1) lu[fu] = su.charCodeAt(fu);
+            }(cu), fu = 4, hu = "ARROW1", du = new Uint8Array(6), pu = 0; pu < 6; pu += 1) du[pu] = hu.charCodeAt(pu);
 
-        function hu(e) {
-            for (var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : 0, n = -1, r = lu.length; ++n < r;)
-                if (lu[n] !== e[t + n]) return !1;
+        function yu(e) {
+            for (var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : 0, n = -1, r = du.length; ++n < r;)
+                if (du[n] !== e[t + n]) return !1;
             return !0
         }
-        var du = lu.length,
-            pu = du + cu,
-            yu = 2 * du + cu,
-            vu = function(e) {
+        var vu = du.length,
+            bu = vu + fu,
+            mu = 2 * vu + fu,
+            gu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     var e;
                     return Object(D.a)(this, n), (e = t.call(this))._byteLength = 0, e._nodes = [], e._buffers = [], e._bufferRegions = [], e
                 }
                 return Object(M.a)(n, [{
                     key: "visit",
                     value: function(e) {
-                        if (!kn.isDictionary(e.type)) {
+                        if (!_n.isDictionary(e.type)) {
                             var t = e.data,
                                 r = e.length,
                                 i = e.nullCount;
                             if (r > 2147483647) throw new RangeError("Cannot write arrays larger than 2^31 - 1 in length");
-                            kn.isNull(e.type) || bu.call(this, i <= 0 ? new Uint8Array(0) : Jt(t.offset, r, t.nullBitmap)), this.nodes.push(new qo(r, i))
+                            _n.isNull(e.type) || ku.call(this, i <= 0 ? new Uint8Array(0) : tn(t.offset, r, t.nullBitmap)), this.nodes.push(new Xo(r, i))
                         }
-                        return Ct(Object(At.a)(n.prototype), "visit", this).call(this, e)
+                        return Mt(Object(Dt.a)(n.prototype), "visit", this).call(this, e)
                     }
                 }, {
                     key: "visitNull",
                     value: function(e) {
                         return this
                     }
                 }, {
@@ -13467,82 +13482,83 @@
                     get: function() {
                         return this._bufferRegions
                     }
                 }], [{
                     key: "assemble",
                     value: function() {
                         for (var e = new n, t = arguments.length, r = new Array(t), i = 0; i < t; i++) r[i] = arguments[i];
-                        var a = $i(gs, r),
-                            o = F(e.visitMany(a), 1)[0];
-                        return void 0 === o ? e : o
+                        var a = Qi(Os, r),
+                            o = e.visitMany(a),
+                            u = Object(F.a)(o, 1)[0];
+                        return void 0 === u ? e : u
                     }
                 }]), n
-            }(on);
+            }(sn);
 
-        function bu(e) {
+        function ku(e) {
             var t = e.byteLength + 7 & -8;
-            return this.buffers.push(e), this.bufferRegions.push(new Ko(this._byteLength, t)), this._byteLength += t, this
+            return this.buffers.push(e), this.bufferRegions.push(new Go(this._byteLength, t)), this._byteLength += t, this
         }
 
-        function mu(e) {
-            return bu.call(this, e.values.subarray(0, e.length * e.stride))
+        function wu(e) {
+            return ku.call(this, e.values.subarray(0, e.length * e.stride))
         }
 
-        function gu(e) {
+        function Ou(e) {
             var t = e.length,
                 n = e.values,
                 r = e.valueOffsets,
                 i = r[0],
                 a = r[t],
                 o = Math.min(a - i, n.byteLength - i);
-            return bu.call(this, vt(-r[0], t, r)), bu.call(this, n.subarray(i, i + o)), this
+            return ku.call(this, gt(-r[0], t, r)), ku.call(this, n.subarray(i, i + o)), this
         }
 
-        function ku(e) {
+        function _u(e) {
             var t = e.length,
                 n = e.valueOffsets;
-            return n && bu.call(this, vt(n[0], t, n)), this.visit(e.getChildAt(0))
+            return n && ku.call(this, gt(n[0], t, n)), this.visit(e.getChildAt(0))
         }
 
-        function wu(e) {
+        function ju(e) {
             return this.visitMany(e.type.children.map((function(t, n) {
                 return e.getChildAt(n)
             })).filter(Boolean))[0]
         }
-        vu.prototype.visitBool = function(e) {
+        gu.prototype.visitBool = function(e) {
             var t;
-            return e.nullCount >= e.length ? bu.call(this, new Uint8Array(0)) : (t = e.values) instanceof Uint8Array ? bu.call(this, Jt(e.offset, e.length, t)) : bu.call(this, Zt(e))
-        }, vu.prototype.visitInt = mu, vu.prototype.visitFloat = mu, vu.prototype.visitUtf8 = gu, vu.prototype.visitBinary = gu, vu.prototype.visitFixedSizeBinary = mu, vu.prototype.visitDate = mu, vu.prototype.visitTimestamp = mu, vu.prototype.visitTime = mu, vu.prototype.visitDecimal = mu, vu.prototype.visitList = ku, vu.prototype.visitStruct = wu, vu.prototype.visitUnion = function(e) {
+            return e.nullCount >= e.length ? ku.call(this, new Uint8Array(0)) : (t = e.values) instanceof Uint8Array ? ku.call(this, tn(e.offset, e.length, t)) : ku.call(this, nn(e))
+        }, gu.prototype.visitInt = wu, gu.prototype.visitFloat = wu, gu.prototype.visitUtf8 = Ou, gu.prototype.visitBinary = Ou, gu.prototype.visitFixedSizeBinary = wu, gu.prototype.visitDate = wu, gu.prototype.visitTimestamp = wu, gu.prototype.visitTime = wu, gu.prototype.visitDecimal = wu, gu.prototype.visitList = _u, gu.prototype.visitStruct = ju, gu.prototype.visitUnion = function(e) {
             var t = e.type,
                 n = e.length,
                 r = e.typeIds,
                 i = e.valueOffsets;
-            if (bu.call(this, r), t.mode === Yt.Sparse) return wu.call(this, e);
-            if (t.mode === Yt.Dense) {
-                if (e.offset <= 0) return bu.call(this, i), wu.call(this, e);
+            if (ku.call(this, r), t.mode === Kt.Sparse) return ju.call(this, e);
+            if (t.mode === Kt.Dense) {
+                if (e.offset <= 0) return ku.call(this, i), ju.call(this, e);
                 for (var a, o, u = r.reduce((function(e, t) {
                         return Math.max(e, t)
-                    }), r[0]), c = new Int32Array(u + 1), s = new Int32Array(u + 1).fill(-1), l = new Int32Array(n), f = vt(-i[0], n, i), h = -1; ++h < n;) - 1 === (o = s[a = r[h]]) && (o = s[a] = f[a]), l[h] = f[h] - o, ++c[a];
-                bu.call(this, l);
+                    }), r[0]), c = new Int32Array(u + 1), s = new Int32Array(u + 1).fill(-1), l = new Int32Array(n), f = gt(-i[0], n, i), h = -1; ++h < n;) - 1 === (o = s[a = r[h]]) && (o = s[a] = f[a]), l[h] = f[h] - o, ++c[a];
+                ku.call(this, l);
                 for (var d, p = -1, y = t.children.length; ++p < y;)
                     if (d = e.getChildAt(p)) {
                         var v = t.typeIds[p],
                             b = Math.min(n, c[v]);
                         this.visit(d.slice(s[v], b))
                     }
             }
             return this
-        }, vu.prototype.visitInterval = mu, vu.prototype.visitFixedSizeList = ku, vu.prototype.visitMap = ku;
-        var Ou = function(e, t) {
+        }, gu.prototype.visitInterval = wu, gu.prototype.visitFixedSizeList = _u, gu.prototype.visitMap = _u;
+        var xu = function(e, t) {
                 Object(ae.a)(r, e);
                 var n = Object(oe.a)(r);
 
                 function r(e) {
                     var t;
-                    return Object(D.a)(this, r), (t = n.call(this))._position = 0, t._started = !1, t._sink = new za, t._schema = null, t._dictionaryBlocks = [], t._recordBatchBlocks = [], t._dictionaryDeltaOffsets = new Map, we(e) || (e = {
+                    return Object(D.a)(this, r), (t = n.call(this))._position = 0, t._started = !1, t._sink = new Ya, t._schema = null, t._dictionaryBlocks = [], t._recordBatchBlocks = [], t._dictionaryDeltaOffsets = new Map, je(e) || (e = {
                         autoDestroy: !0,
                         writeLegacyIpcFormat: !1
                     }), t._autoDestroy = "boolean" !== typeof e.autoDestroy || e.autoDestroy, t._writeLegacyIpcFormat = "boolean" === typeof e.writeLegacyIpcFormat && e.writeLegacyIpcFormat, t
                 }
                 return Object(M.a)(r, [{
                     key: "toString",
                     value: function() {
@@ -13555,17 +13571,17 @@
                         var e = arguments.length > 0 && void 0 !== arguments[0] && arguments[0];
                         return this._sink.toUint8Array(e)
                     }
                 }, {
                     key: "writeAll",
                     value: function(e) {
                         var t = this;
-                        return Oe(e) ? e.then((function(e) {
+                        return xe(e) ? e.then((function(e) {
                             return t.writeAll(e)
-                        })) : je(e) ? Tu(this, e) : xu(this, e)
+                        })) : Se(e) ? Eu(this, e) : Iu(this, e)
                     }
                 }, {
                     key: "closed",
                     get: function() {
                         return this._sink.closed
                     }
                 }, {
@@ -13599,116 +13615,116 @@
                         return this._autoDestroy ? this.close() : this.reset(this._sink, this._schema), this
                     }
                 }, {
                     key: "reset",
                     value: function() {
                         var e, t = arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : this._sink,
                             n = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : null;
-                        return t === this._sink || t instanceof za ? this._sink = t : (this._sink = new za, t && (we(e = t) && ke(e.abort) && ke(e.getWriter) && !(e instanceof se)) ? this.toDOMStream({
+                        return t === this._sink || t instanceof Ya ? this._sink = t : (this._sink = new Ya, t && (je(e = t) && _e(e.abort) && _e(e.getWriter) && !(e instanceof se)) ? this.toDOMStream({
                             type: "bytes"
                         }).pipeTo(t) : t && function(e) {
-                            return we(e) && ke(e.end) && ke(e.write) && ge(e.writable) && !(e instanceof se)
+                            return je(e) && _e(e.end) && _e(e.write) && Oe(e.writable) && !(e instanceof se)
                         }(t) && this.toNodeStream({
                             objectMode: !1
                         }).pipe(t)), this._started && this._schema && this._writeFooter(this._schema), this._started = !1, this._dictionaryBlocks = [], this._recordBatchBlocks = [], this._dictionaryDeltaOffsets = new Map, n && n.compareTo(this._schema) || (null === n ? (this._position = 0, this._schema = null) : (this._started = !0, this._schema = n, this._writeSchema(n))), this
                     }
                 }, {
                     key: "write",
                     value: function(e) {
                         var t = null;
                         if (!this._sink) throw new Error("RecordBatchWriter is closed");
                         if (null === e || void 0 === e) return this.finish() && void 0;
-                        if (e instanceof ms && !(t = e.schema)) return this.finish() && void 0;
-                        if (e instanceof gs && !(t = e.schema)) return this.finish() && void 0;
+                        if (e instanceof ws && !(t = e.schema)) return this.finish() && void 0;
+                        if (e instanceof Os && !(t = e.schema)) return this.finish() && void 0;
                         if (t && !t.compareTo(this._schema)) {
                             if (this._started && this._autoDestroy) return this.close();
                             this.reset(this._sink, t)
                         }
-                        e instanceof gs ? e instanceof ks || this._writeRecordBatch(e) : e instanceof ms ? this.writeAll(e.chunks) : _e(e) && this.writeAll(e)
+                        e instanceof Os ? e instanceof _s || this._writeRecordBatch(e) : e instanceof ws ? this.writeAll(e.chunks) : Te(e) && this.writeAll(e)
                     }
                 }, {
                     key: "_writeMessage",
                     value: function(e) {
                         var t = (arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : 8) - 1,
-                            n = Yo.encode(e),
+                            n = Ko.encode(e),
                             r = n.byteLength,
                             i = this._writeLegacyIpcFormat ? 4 : 8,
                             a = r + i + t & ~t,
                             o = a - r - i;
-                        return e.headerType === $t.RecordBatch ? this._recordBatchBlocks.push(new Ra(a, e.bodyLength, this._position)) : e.headerType === $t.DictionaryBatch && this._dictionaryBlocks.push(new Ra(a, e.bodyLength, this._position)), this._writeLegacyIpcFormat || this._write(Int32Array.of(-1)), this._write(Int32Array.of(a - i)), r > 0 && this._write(n), this._writePadding(o)
+                        return e.headerType === Qt.RecordBatch ? this._recordBatchBlocks.push(new Wa(a, e.bodyLength, this._position)) : e.headerType === Qt.DictionaryBatch && this._dictionaryBlocks.push(new Wa(a, e.bodyLength, this._position)), this._writeLegacyIpcFormat || this._write(Int32Array.of(-1)), this._write(Int32Array.of(a - i)), r > 0 && this._write(n), this._writePadding(o)
                     }
                 }, {
                     key: "_write",
                     value: function(e) {
                         if (this._started) {
-                            var t = ze(e);
+                            var t = Ye(e);
                             t && t.byteLength > 0 && (this._sink.write(t), this._position += t.byteLength)
                         }
                         return this
                     }
                 }, {
                     key: "_writeSchema",
                     value: function(e) {
-                        return this._writeMessage(Yo.from(e))
+                        return this._writeMessage(Ko.from(e))
                     }
                 }, {
                     key: "_writeFooter",
                     value: function(e) {
                         return this._writeLegacyIpcFormat ? this._write(Int32Array.of(0)) : this._write(Int32Array.of(-1, 0))
                     }
                 }, {
                     key: "_writeMagic",
                     value: function() {
-                        return this._write(lu)
+                        return this._write(du)
                     }
                 }, {
                     key: "_writePadding",
                     value: function(e) {
                         return e > 0 ? this._write(new Uint8Array(e)) : this
                     }
                 }, {
                     key: "_writeRecordBatch",
                     value: function(e) {
-                        var t = vu.assemble(e),
+                        var t = gu.assemble(e),
                             n = t.byteLength,
                             r = t.nodes,
                             i = t.bufferRegions,
                             a = t.buffers,
-                            o = new Ho(e.length, r, i),
-                            u = Yo.from(o, n);
+                            o = new qo(e.length, r, i),
+                            u = Ko.from(o, n);
                         return this._writeDictionaries(e)._writeMessage(u)._writeBodyBuffers(a)
                     }
                 }, {
                     key: "_writeDictionaryBatch",
                     value: function(e, t) {
                         var n = arguments.length > 2 && void 0 !== arguments[2] && arguments[2];
                         this._dictionaryDeltaOffsets.set(t, e.length + (this._dictionaryDeltaOffsets.get(t) || 0));
-                        var r = vu.assemble(e),
+                        var r = gu.assemble(e),
                             i = r.byteLength,
                             a = r.nodes,
                             o = r.bufferRegions,
                             u = r.buffers,
-                            c = new Ho(e.length, a, o),
-                            s = new $o(c, t, n),
-                            l = Yo.from(s, i);
+                            c = new qo(e.length, a, o),
+                            s = new Qo(c, t, n),
+                            l = Ko.from(s, i);
                         return this._writeMessage(l)._writeBodyBuffers(u)
                     }
                 }, {
                     key: "_writeBodyBuffers",
                     value: function(e) {
                         for (var t, n, r, i = -1, a = e.length; ++i < a;)(t = e[i]) && (n = t.byteLength) > 0 && (this._write(t), (r = (n + 7 & -8) - n) > 0 && this._writePadding(r));
                         return this
                     }
                 }, {
                     key: "_writeDictionaries",
                     value: function(e) {
                         var t, n = C(e.dictionaries);
                         try {
                             for (n.s(); !(t = n.n()).done;) {
-                                var r = F(t.value, 2),
+                                var r = Object(F.a)(t.value, 2),
                                     i = r[0],
                                     a = r[1],
                                     o = this._dictionaryDeltaOffsets.get(i) || 0;
                                 if (0 === o || (a = a.slice(o)).length > 0) {
                                     var u, c = C("chunks" in a ? a.chunks : [a]);
                                     try {
                                         for (c.s(); !(u = c.n()).done;) {
@@ -13737,32 +13753,32 @@
                 }, {
                     key: "throughDOM",
                     value: function(e, t) {
                         throw new Error('"throughDOM" not available in this environment')
                     }
                 }]), r
             }(se, Symbol.asyncIterator),
-            _u = function(e) {
+            Tu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, null, [{
                     key: "writeAll",
                     value: function(e, t) {
                         var r = new n(t);
-                        return Oe(e) ? e.then((function(e) {
+                        return xe(e) ? e.then((function(e) {
                             return r.writeAll(e)
-                        })) : je(e) ? Tu(r, e) : xu(r, e)
+                        })) : Se(e) ? Eu(r, e) : Iu(r, e)
                     }
                 }]), n
-            }(Ou),
-            ju = function(e) {
+            }(xu),
+            Su = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     var e;
                     return Object(D.a)(this, n), (e = t.call(this))._autoDestroy = !0, e
                 }
@@ -13770,51 +13786,51 @@
                     key: "_writeSchema",
                     value: function(e) {
                         return this._writeMagic()._writePadding(2)
                     }
                 }, {
                     key: "_writeFooter",
                     value: function(e) {
-                        var t = Pa.encode(new Pa(e, Kt.V4, this._recordBatchBlocks, this._dictionaryBlocks));
-                        return Ct(Object(At.a)(n.prototype), "_writeFooter", this).call(this, e)._write(t)._write(Int32Array.of(t.byteLength))._writeMagic()
+                        var t = za.encode(new za(e, Gt.V4, this._recordBatchBlocks, this._dictionaryBlocks));
+                        return Mt(Object(Dt.a)(n.prototype), "_writeFooter", this).call(this, e)._write(t)._write(Int32Array.of(t.byteLength))._writeMagic()
                     }
                 }], [{
                     key: "writeAll",
                     value: function(e) {
                         var t = new n;
-                        return Oe(e) ? e.then((function(e) {
+                        return xe(e) ? e.then((function(e) {
                             return t.writeAll(e)
-                        })) : je(e) ? Tu(t, e) : xu(t, e)
+                        })) : Se(e) ? Eu(t, e) : Iu(t, e)
                     }
                 }]), n
-            }(Ou);
+            }(xu);
 
-        function xu(e, t) {
+        function Iu(e, t) {
             var n = t;
-            t instanceof ms && (n = t.chunks, e.reset(void 0, t.schema));
+            t instanceof ws && (n = t.chunks, e.reset(void 0, t.schema));
             var r, i = C(n);
             try {
                 for (i.s(); !(r = i.n()).done;) {
                     var a = r.value;
                     e.write(a)
                 }
             } catch (o) {
                 i.e(o)
             } finally {
                 i.f()
             }
             return e.finish()
         }
 
-        function Tu(e, t) {
-            return Su.apply(this, arguments)
+        function Eu(e, t) {
+            return Au.apply(this, arguments)
         }
 
-        function Su() {
-            return (Su = Object(B.a)(Object(L.a)().mark((function e(t, n) {
+        function Au() {
+            return (Au = Object(B.a)(Object(L.a)().mark((function e(t, n) {
                 var r, i, a, o, u, c;
                 return Object(L.a)().wrap((function(e) {
                     for (;;) switch (e.prev = e.next) {
                         case 0:
                             r = !1, i = !1, e.prev = 2, o = V(n);
                         case 4:
                             return e.next = 6, o.next();
@@ -13856,70 +13872,70 @@
                     }
                 }), e, null, [
                     [2, 14, 18, 28],
                     [19, , 23, 27]
                 ])
             })))).apply(this, arguments)
         }
-        var Iu = new Uint8Array(0),
-            Eu = function(e) {
-                return [Iu, Iu, new Uint8Array(e), Iu]
+        var Cu = new Uint8Array(0),
+            Bu = function(e) {
+                return [Cu, Cu, new Uint8Array(e), Cu]
             };
 
-        function Au(e, t) {
+        function Du(e, t) {
             return function(e, t) {
-                var n, r = Object(an.a)(e.fields),
+                var n, r = Object(cn.a)(e.fields),
                     i = [],
                     a = {
                         numBatches: t.reduce((function(e, t) {
                             return Math.max(e, t.length)
                         }), 0)
                     },
                     o = 0,
                     u = 0,
                     c = -1,
                     s = t.length,
                     l = [];
                 for (; a.numBatches-- > 0;) {
                     for (u = Number.POSITIVE_INFINITY, c = -1; ++c < s;) l[c] = n = t[c].shift(), u = Math.min(u, n ? n.length : u);
-                    isFinite(u) && (l = Cu(r, u, l, t, a), u > 0 && (i[o++] = [u, l.slice()]))
+                    isFinite(u) && (l = Mu(r, u, l, t, a), u > 0 && (i[o++] = [u, l.slice()]))
                 }
-                return [e = new Ji(r, e.metadata), i.map((function(t) {
-                    return Br(gs, [e].concat(Object(an.a)(t)))
+                return [e = new ta(r, e.metadata), i.map((function(t) {
+                    return Lr(Os, [e].concat(Object(cn.a)(t)))
                 }))]
             }(e, t.map((function(e) {
-                return e instanceof Ni ? e.chunks.map((function(e) {
+                return e instanceof Ri ? e.chunks.map((function(e) {
                     return e.data
                 })) : [e.data]
             })))
         }
 
-        function Cu(e, t, n, r, i) {
+        function Mu(e, t, n, r, i) {
             for (var a, o, u = 0, c = -1, s = r.length, l = (t + 63 & -64) >> 3; ++c < s;)(a = n[c]) && (u = a.length) >= t ? u === t ? n[c] = a : (n[c] = a.slice(0, t), a = a.slice(t, u - t), i.numBatches = Math.max(i.numBatches, r[c].unshift(a))) : ((o = e[c]).nullable || (e[c] = o.clone({
                 nullable: !0
-            })), n[c] = a ? a._changeLengthAndBackfillNullBitmap(t) : tr.new(o.type, 0, t, t, Eu(l)));
+            })), n[c] = a ? a._changeLengthAndBackfillNullBitmap(t) : ir.new(o.type, 0, t, t, Bu(l)));
             return n
         }
 
-        function Bu(e, t) {
+        function Lu(e, t) {
             if (null == e) return {};
             var n, r, i = function(e, t) {
                 if (null == e) return {};
                 var n, r, i = {},
                     a = Object.keys(e);
                 for (r = 0; r < a.length; r++) n = a[r], t.indexOf(n) >= 0 || (i[n] = e[n]);
                 return i
             }(e, t);
             if (Object.getOwnPropertySymbols) {
                 var a = Object.getOwnPropertySymbols(e);
                 for (r = 0; r < a.length; r++) n = a[r], t.indexOf(n) >= 0 || Object.prototype.propertyIsEnumerable.call(e, n) && (i[n] = e[n])
             }
             return i
         }
-        var Du = function(e, t) {
+        var Fu = function(e, t) {
             Object(ae.a)(r, e);
             var n = Object(oe.a)(r);
 
             function r(e, t) {
                 var i;
                 return Object(D.a)(this, r), (i = n.call(this))._children = t, i.numChildren = e.childData.length, i._bindDataAccessors(i.data = e), i
             }
@@ -13957,15 +13973,15 @@
                 key: "byteLength",
                 get: function() {
                     return this.data.byteLength
                 }
             }, {
                 key: "VectorName",
                 get: function() {
-                    return "".concat(Ut[this.typeId], "Vector")
+                    return "".concat(Vt[this.typeId], "Vector")
                 }
             }, {
                 key: "ArrayType",
                 get: function() {
                     return this.type.ArrayType
                 }
             }, {
@@ -13993,140 +14009,140 @@
                 get: function() {
                     return "".concat(this.VectorName, "<").concat(this.type[Symbol.toStringTag], ">")
                 }
             }, {
                 key: "clone",
                 value: function(e) {
                     var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this._children;
-                    return Pt.new(e, t)
+                    return zt.new(e, t)
                 }
             }, {
                 key: "concat",
                 value: function() {
                     for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++) t[n] = arguments[n];
-                    return Ni.concat.apply(Ni, [this].concat(t))
+                    return Ri.concat.apply(Ri, [this].concat(t))
                 }
             }, {
                 key: "slice",
                 value: function(e, t) {
-                    return Ci(this, e, t, this._sliceInternal)
+                    return Mi(this, e, t, this._sliceInternal)
                 }
             }, {
                 key: "isValid",
                 value: function(e) {
                     if (this.nullCount > 0) {
                         var t = this.offset + e;
                         return 0 !== (this.nullBitmap[t >> 3] & 1 << t % 8)
                     }
                     return !0
                 }
             }, {
                 key: "getChildAt",
                 value: function(e) {
-                    return e < 0 || e >= this.numChildren ? null : (this._children || (this._children = []))[e] || (this._children[e] = Pt.new(this.data.childData[e]))
+                    return e < 0 || e >= this.numChildren ? null : (this._children || (this._children = []))[e] || (this._children[e] = zt.new(this.data.childData[e]))
                 }
             }, {
                 key: "toJSON",
                 value: function() {
-                    return Object(an.a)(this)
+                    return Object(cn.a)(this)
                 }
             }, {
                 key: "_sliceInternal",
                 value: function(e, t, n) {
                     return e.clone(e.data.slice(t, n - t), null)
                 }
             }, {
                 key: "_bindDataAccessors",
                 value: function(e) {}
             }]), r
-        }(Pt, Symbol.toStringTag);
-        Du.prototype[Symbol.isConcatSpreadable] = !0;
-        var Mu = function(e) {
+        }(zt, Symbol.toStringTag);
+        Fu.prototype[Symbol.isConcatSpreadable] = !0;
+        var Nu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "asUtf8",
                     value: function() {
-                        return Pt.new(this.data.clone(new Fn))
+                        return zt.new(this.data.clone(new Un))
                     }
                 }]), n
-            }(Du),
-            Lu = function(e) {
+            }(Fu),
+            Pu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, null, [{
                     key: "from",
                     value: function(e) {
-                        return bs((function() {
-                            return new Nn
+                        return ks((function() {
+                            return new Rn
                         }), e)
                     }
                 }]), n
-            }(Du),
-            Fu = function(e) {
+            }(Fu),
+            Uu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, null, [{
                     key: "from",
                     value: function() {
                         for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++) t[n] = arguments[n];
-                        return 2 === t.length ? bs((function() {
-                            return t[1] === zt.DAY ? new Rn : new zn
-                        }), t[0]) : bs((function() {
-                            return new zn
+                        return 2 === t.length ? ks((function() {
+                            return t[1] === Yt.DAY ? new Wn : new Yn
+                        }), t[0]) : ks((function() {
+                            return new Yn
                         }), t[0])
                     }
                 }]), n
-            }(Du),
-            Nu = function(e) {
+            }(Fu),
+            Ru = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Fu),
-            Pu = function(e) {
+            }(Uu),
+            zu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Fu),
-            Uu = function(e) {
+            }(Uu),
+            Vu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Du),
-            Ru = function(e) {
+            }(Fu),
+            Wu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
-                    return Object(D.a)(this, n), (r = t.call(this, e)).indices = Pt.new(e.clone(r.type.indices)), r
+                    return Object(D.a)(this, n), (r = t.call(this, e)).indices = zt.new(e.clone(r.type.indices)), r
                 }
                 return Object(M.a)(n, [{
                     key: "dictionary",
                     get: function() {
                         return this.data.dictionary
                     }
                 }, {
@@ -14158,70 +14174,70 @@
                     key: "from",
                     value: function() {
                         for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++) t[n] = arguments[n];
                         if (3 === t.length) {
                             var r = t[0],
                                 i = t[1],
                                 a = t[2],
-                                o = new Zn(r.type, i, null, null);
-                            return Pt.new(tr.Dictionary(o, 0, a.length, 0, null, a, r))
+                                o = new nr(r.type, i, null, null);
+                            return zt.new(ir.Dictionary(o, 0, a.length, 0, null, a, r))
                         }
-                        return bs((function() {
+                        return ks((function() {
                             return t[0].type
                         }), t[0])
                     }
                 }]), n
-            }(Du);
-        Ru.prototype.indices = null;
-        var zu = function(e) {
+            }(Fu);
+        Wu.prototype.indices = null;
+        var Yu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Du),
-            Vu = function(e) {
+            }(Fu),
+            Hu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Du),
-            Wu = function(e) {
+            }(Fu),
+            $u = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, null, [{
                     key: "from",
                     value: function(e) {
-                        var t = Qu(this);
+                        var t = Ju(this);
                         if (e instanceof ArrayBuffer || ArrayBuffer.isView(e)) {
-                            var n = qu(e.constructor) || t;
+                            var n = Xu(e.constructor) || t;
                             if (null === t && (t = n), t && t === n) {
                                 var r = new t,
                                     i = e.byteLength / r.ArrayType.BYTES_PER_ELEMENT;
-                                if (!Ku(t, e.constructor)) return Pt.new(tr.Float(r, 0, i, 0, null, e))
+                                if (!Gu(t, e.constructor)) return zt.new(ir.Float(r, 0, i, 0, null, e))
                             }
                         }
-                        if (t) return bs((function() {
+                        if (t) return ks((function() {
                             return new t
                         }), e);
                         if (e instanceof DataView || e instanceof ArrayBuffer) throw new TypeError("Cannot infer float type from instance of ".concat(e.constructor.name));
                         throw new TypeError("Unrecognized FloatVector input")
                     }
                 }]), n
-            }(Du),
-            Yu = function(e) {
+            }(Fu),
+            Ku = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
@@ -14231,705 +14247,705 @@
                     }
                 }, {
                     key: "toFloat64Array",
                     value: function() {
                         return new Float64Array(this)
                     }
                 }]), n
-            }(Wu),
-            Hu = function(e) {
+            }($u),
+            qu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Wu),
-            $u = function(e) {
+            }($u),
+            Qu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Wu),
-            Ku = function(e, t) {
-                return e === Bn && t !== Uint16Array
+            }($u),
+            Gu = function(e, t) {
+                return e === Ln && t !== Uint16Array
             },
-            qu = function(e) {
+            Xu = function(e) {
                 switch (e) {
                     case Uint16Array:
-                        return Bn;
+                        return Ln;
                     case Float32Array:
-                        return Dn;
+                        return Fn;
                     case Float64Array:
-                        return Mn;
+                        return Nn;
                     default:
                         return null
                 }
             },
-            Qu = function(e) {
+            Ju = function(e) {
                 switch (e) {
-                    case Yu:
-                        return Bn;
-                    case Hu:
-                        return Dn;
-                    case $u:
-                        return Mn;
+                    case Ku:
+                        return Ln;
+                    case qu:
+                        return Fn;
+                    case Qu:
+                        return Nn;
                     default:
                         return null
                 }
             },
-            Gu = function(e) {
+            Zu = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Du),
-            Xu = function(e) {
+            }(Fu),
+            ec = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Gu),
-            Ju = function(e) {
+            }(Zu),
+            tc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Gu),
-            Zu = function(e) {
+            }(Zu),
+            nc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, null, [{
                     key: "from",
                     value: function() {
                         for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++) t[n] = arguments[n];
                         var r = t[0],
                             i = t[1],
                             a = void 0 !== i && i,
-                            o = lc(this, a);
+                            o = dc(this, a);
                         if (r instanceof ArrayBuffer || ArrayBuffer.isView(r)) {
-                            var u = sc(r.constructor, a) || o;
+                            var u = hc(r.constructor, a) || o;
                             if (null === o && (o = u), o && o === u) {
                                 var c = new o,
                                     s = r.byteLength / c.ArrayType.BYTES_PER_ELEMENT;
-                                return cc(o, r.constructor) && (s *= .5), Pt.new(tr.Int(c, 0, s, 0, null, r))
+                                return fc(o, r.constructor) && (s *= .5), zt.new(ir.Int(c, 0, s, 0, null, r))
                             }
                         }
-                        if (o) return bs((function() {
+                        if (o) return ks((function() {
                             return new o
                         }), r);
                         if (r instanceof DataView || r instanceof ArrayBuffer) throw new TypeError("Cannot infer integer type from instance of ".concat(r.constructor.name));
                         throw new TypeError("Unrecognized IntVector input")
                     }
                 }]), n
-            }(Du),
-            ec = function(e) {
+            }(Fu),
+            rc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Zu),
-            tc = function(e) {
+            }(nc),
+            ic = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Zu),
-            nc = function(e) {
+            }(nc),
+            ac = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Zu),
-            rc = function(e) {
+            }(nc),
+            oc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "toBigInt64Array",
                     value: function() {
-                        return Re(this.values)
+                        return We(this.values)
                     }
                 }, {
                     key: "values64",
                     get: function() {
                         return this._values64 || (this._values64 = this.toBigInt64Array())
                     }
                 }]), n
-            }(Zu),
-            ic = function(e) {
+            }(nc),
+            uc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Zu),
-            ac = function(e) {
+            }(nc),
+            cc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Zu),
-            oc = function(e) {
+            }(nc),
+            sc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Zu),
-            uc = function(e) {
+            }(nc),
+            lc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "toBigUint64Array",
                     value: function() {
-                        return Ye(this.values)
+                        return Ke(this.values)
                     }
                 }, {
                     key: "values64",
                     get: function() {
                         return this._values64 || (this._values64 = this.toBigUint64Array())
                     }
                 }]), n
-            }(Zu),
-            cc = function(e, t) {
-                return (e === Tn || e === An) && (t === Int32Array || t === Uint32Array)
+            }(nc),
+            fc = function(e, t) {
+                return (e === En || e === Dn) && (t === Int32Array || t === Uint32Array)
             },
-            sc = function(e, t) {
+            hc = function(e, t) {
                 switch (e) {
                     case Int8Array:
-                        return _n;
+                        return Tn;
                     case Int16Array:
-                        return jn;
+                        return Sn;
                     case Int32Array:
-                        return t ? Tn : xn;
-                    case ye:
-                        return Tn;
+                        return t ? En : In;
+                    case be:
+                        return En;
                     case Uint8Array:
-                        return Sn;
+                        return An;
                     case Uint16Array:
-                        return In;
+                        return Cn;
                     case Uint32Array:
-                        return t ? An : En;
-                    case be:
-                        return An;
+                        return t ? Dn : Bn;
+                    case ke:
+                        return Dn;
                     default:
                         return null
                 }
             },
-            lc = function(e, t) {
+            dc = function(e, t) {
                 switch (e) {
-                    case ec:
-                        return _n;
-                    case tc:
-                        return jn;
-                    case nc:
-                        return t ? Tn : xn;
                     case rc:
                         return Tn;
                     case ic:
                         return Sn;
                     case ac:
-                        return In;
+                        return t ? En : In;
                     case oc:
-                        return t ? An : En;
+                        return En;
                     case uc:
                         return An;
+                    case cc:
+                        return Cn;
+                    case sc:
+                        return t ? Dn : Bn;
+                    case lc:
+                        return Dn;
                     default:
                         return null
                 }
             },
-            fc = function(e) {
+            pc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Du),
-            hc = function(e) {
+            }(Fu),
+            yc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "asList",
                     value: function() {
                         var e = this.type.children[0];
-                        return Pt.new(this.data.clone(new Hn(e)))
+                        return zt.new(this.data.clone(new qn(e)))
                     }
                 }, {
                     key: "bind",
                     value: function(e) {
                         var t = this.getChildAt(0),
                             n = this.valueOffsets,
                             r = n[e],
                             i = n[e + 1];
-                        return new xi(t.slice(r, i))
+                        return new Ii(t.slice(r, i))
                     }
                 }]), n
-            }(Du),
-            dc = function(e) {
+            }(Fu),
+            vc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Du),
-            pc = Symbol.for("rowIndex"),
-            yc = function(e) {
+            }(Fu),
+            bc = Symbol.for("rowIndex"),
+            mc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "bind",
                     value: function(e) {
-                        var t = this._row || (this._row = new Ti(this)),
+                        var t = this._row || (this._row = new Ei(this)),
                             n = Object.create(t);
-                        return n[pc] = e, n
+                        return n[bc] = e, n
                     }
                 }]), n
-            }(Du),
-            vc = function(e) {
+            }(Fu),
+            gc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Du),
-            bc = function(e) {
+            }(Fu),
+            kc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(vc),
-            mc = function(e) {
+            }(gc),
+            wc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(vc),
-            gc = function(e) {
+            }(gc),
+            Oc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(vc),
-            kc = function(e) {
+            }(gc),
+            _c = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(vc),
-            wc = function(e) {
+            }(gc),
+            jc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Du),
-            Oc = function(e) {
+            }(Fu),
+            xc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(wc),
-            _c = function(e) {
+            }(jc),
+            Tc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(wc),
-            jc = function(e) {
+            }(jc),
+            Sc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(wc),
-            xc = function(e) {
+            }(jc),
+            Ic = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(wc),
-            Tc = function(e) {
+            }(jc),
+            Ec = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "typeIdToChildIndex",
                     get: function() {
                         return this.data.type.typeIdToChildIndex
                     }
                 }]), n
-            }(Du),
-            Sc = function(e) {
+            }(Fu),
+            Ac = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "valueOffsets",
                     get: function() {
                         return this.data.valueOffsets
                     }
                 }]), n
-            }(Tc),
-            Ic = function(e) {
+            }(Ec),
+            Cc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(Tc),
-            Ec = function(e) {
+            }(Ec),
+            Bc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "asBinary",
                     value: function() {
-                        return Pt.new(this.data.clone(new Ln))
+                        return zt.new(this.data.clone(new Pn))
                     }
                 }], [{
                     key: "from",
                     value: function(e) {
-                        return bs((function() {
-                            return new Fn
+                        return ks((function() {
+                            return new Un
                         }), e)
                     }
                 }]), n
-            }(Du);
+            }(Fu);
 
-        function Ac(e) {
+        function Dc(e) {
             return function() {
                 return e(this)
             }
         }
 
-        function Cc(e) {
+        function Mc(e) {
             return function(t, n) {
                 return e(this, t, n)
             }
         }
-        var Bc = function(e) {
+        var Lc = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(on),
-            Dc = function(e, t) {
+            }(sn),
+            Fc = function(e, t) {
                 return 4294967296 * e[t + 1] + (e[t] >>> 0)
             },
-            Mc = function(e) {
+            Nc = function(e) {
                 return new Date(e)
             },
-            Lc = function(e, t, n) {
+            Pc = function(e, t, n) {
                 var r = t[n],
                     i = t[n + 1];
                 return null != r && null != i ? e.subarray(r, i) : null
             },
-            Fc = function(e, t) {
+            Uc = function(e, t) {
                 return function(e, t) {
-                    return Mc(function(e, t) {
+                    return Nc(function(e, t) {
                         return 864e5 * e[t]
                     }(e, t))
                 }(e.values, t)
             },
-            Nc = function(e, t) {
+            Rc = function(e, t) {
                 return function(e, t) {
-                    return Mc(Dc(e, t))
+                    return Nc(Fc(e, t))
                 }(e.values, 2 * t)
             },
-            Pc = function(e, t) {
+            zc = function(e, t) {
                 var n = e.stride;
                 return e.values[n * t]
             },
-            Uc = function(e, t) {
+            Vc = function(e, t) {
                 var n = e.stride;
-                return jr(e.values[n * t])
+                return Sr(e.values[n * t])
             },
-            Rc = function(e, t) {
+            Wc = function(e, t) {
                 var n = e.stride,
                     r = e.values,
                     i = e.type;
-                return Wr.new(r.subarray(n * t, n * (t + 1)), i.isSigned)
+                return $r.new(r.subarray(n * t, n * (t + 1)), i.isSigned)
             },
-            zc = function(e, t) {
+            Yc = function(e, t) {
                 var n = e.values;
-                return 1e3 * Dc(n, 2 * t)
+                return 1e3 * Fc(n, 2 * t)
             },
-            Vc = function(e, t) {
+            Hc = function(e, t) {
                 var n = e.values;
-                return Dc(n, 2 * t)
+                return Fc(n, 2 * t)
             },
-            Wc = function(e, t) {
+            $c = function(e, t) {
                 return function(e, t) {
                     return e[t + 1] / 1e3 * 4294967296 + (e[t] >>> 0) / 1e3
                 }(e.values, 2 * t)
             },
-            Yc = function(e, t) {
+            Kc = function(e, t) {
                 return function(e, t) {
                     return e[t + 1] / 1e6 * 4294967296 + (e[t] >>> 0) / 1e6
                 }(e.values, 2 * t)
             },
-            Hc = function(e, t) {
+            qc = function(e, t) {
                 return e.values[e.stride * t]
             },
-            $c = function(e, t) {
+            Qc = function(e, t) {
                 return e.values[e.stride * t]
             },
-            Kc = function(e, t) {
+            Gc = function(e, t) {
                 var n = e.values;
-                return Wr.signed(n.subarray(2 * t, 2 * (t + 1)))
+                return $r.signed(n.subarray(2 * t, 2 * (t + 1)))
             },
-            qc = function(e, t) {
+            Xc = function(e, t) {
                 var n = e.values;
-                return Wr.signed(n.subarray(2 * t, 2 * (t + 1)))
+                return $r.signed(n.subarray(2 * t, 2 * (t + 1)))
             },
-            Qc = function(e, t) {
+            Jc = function(e, t) {
                 var n = e.typeIdToChildIndex[e.typeIds[t]],
                     r = e.getChildAt(n);
                 return r ? r.get(e.valueOffsets[t]) : null
             },
-            Gc = function(e, t) {
+            Zc = function(e, t) {
                 var n = e.typeIdToChildIndex[e.typeIds[t]],
                     r = e.getChildAt(n);
                 return r ? r.get(t) : null
             },
-            Xc = function(e, t) {
+            es = function(e, t) {
                 return e.values.subarray(2 * t, 2 * (t + 1))
             },
-            Jc = function(e, t) {
+            ts = function(e, t) {
                 var n = e.values[t],
                     r = new Int32Array(2);
                 return r[0] = n / 12 | 0, r[1] = n % 12 | 0, r
             };
-        Bc.prototype.visitNull = function(e, t) {
+        Lc.prototype.visitNull = function(e, t) {
             return null
-        }, Bc.prototype.visitBool = function(e, t) {
+        }, Lc.prototype.visitBool = function(e, t) {
             var n = e.offset + t;
             return 0 !== (e.values[n >> 3] & 1 << n % 8)
-        }, Bc.prototype.visitInt = function(e, t) {
-            return e.type.bitWidth < 64 ? Pc(e, t) : Rc(e, t)
-        }, Bc.prototype.visitInt8 = Pc, Bc.prototype.visitInt16 = Pc, Bc.prototype.visitInt32 = Pc, Bc.prototype.visitInt64 = Rc, Bc.prototype.visitUint8 = Pc, Bc.prototype.visitUint16 = Pc, Bc.prototype.visitUint32 = Pc, Bc.prototype.visitUint64 = Rc, Bc.prototype.visitFloat = function(e, t) {
-            return e.type.precision !== Wt.HALF ? Pc(e, t) : Uc(e, t)
-        }, Bc.prototype.visitFloat16 = Uc, Bc.prototype.visitFloat32 = Pc, Bc.prototype.visitFloat64 = Pc, Bc.prototype.visitUtf8 = function(e, t) {
+        }, Lc.prototype.visitInt = function(e, t) {
+            return e.type.bitWidth < 64 ? zc(e, t) : Wc(e, t)
+        }, Lc.prototype.visitInt8 = zc, Lc.prototype.visitInt16 = zc, Lc.prototype.visitInt32 = zc, Lc.prototype.visitInt64 = Wc, Lc.prototype.visitUint8 = zc, Lc.prototype.visitUint16 = zc, Lc.prototype.visitUint32 = zc, Lc.prototype.visitUint64 = Wc, Lc.prototype.visitFloat = function(e, t) {
+            return e.type.precision !== $t.HALF ? zc(e, t) : Vc(e, t)
+        }, Lc.prototype.visitFloat16 = Vc, Lc.prototype.visitFloat32 = zc, Lc.prototype.visitFloat64 = zc, Lc.prototype.visitUtf8 = function(e, t) {
             var n = e.values,
                 r = e.valueOffsets,
-                i = Lc(n, r, t);
+                i = Pc(n, r, t);
             return null !== i ? re(i) : null
-        }, Bc.prototype.visitBinary = function(e, t) {
+        }, Lc.prototype.visitBinary = function(e, t) {
             var n = e.values,
                 r = e.valueOffsets;
-            return Lc(n, r, t)
-        }, Bc.prototype.visitFixedSizeBinary = function(e, t) {
+            return Pc(n, r, t)
+        }, Lc.prototype.visitFixedSizeBinary = function(e, t) {
             var n = e.stride;
             return e.values.subarray(n * t, n * (t + 1))
-        }, Bc.prototype.visitDate = function(e, t) {
-            return e.type.unit === zt.DAY ? Fc(e, t) : Nc(e, t)
-        }, Bc.prototype.visitDateDay = Fc, Bc.prototype.visitDateMillisecond = Nc, Bc.prototype.visitTimestamp = function(e, t) {
-            switch (e.type.unit) {
-                case Vt.SECOND:
-                    return zc(e, t);
-                case Vt.MILLISECOND:
-                    return Vc(e, t);
-                case Vt.MICROSECOND:
-                    return Wc(e, t);
-                case Vt.NANOSECOND:
-                    return Yc(e, t)
-            }
-        }, Bc.prototype.visitTimestampSecond = zc, Bc.prototype.visitTimestampMillisecond = Vc, Bc.prototype.visitTimestampMicrosecond = Wc, Bc.prototype.visitTimestampNanosecond = Yc, Bc.prototype.visitTime = function(e, t) {
+        }, Lc.prototype.visitDate = function(e, t) {
+            return e.type.unit === Yt.DAY ? Uc(e, t) : Rc(e, t)
+        }, Lc.prototype.visitDateDay = Uc, Lc.prototype.visitDateMillisecond = Rc, Lc.prototype.visitTimestamp = function(e, t) {
             switch (e.type.unit) {
-                case Vt.SECOND:
+                case Ht.SECOND:
+                    return Yc(e, t);
+                case Ht.MILLISECOND:
                     return Hc(e, t);
-                case Vt.MILLISECOND:
+                case Ht.MICROSECOND:
                     return $c(e, t);
-                case Vt.MICROSECOND:
-                    return Kc(e, t);
-                case Vt.NANOSECOND:
-                    return qc(e, t)
+                case Ht.NANOSECOND:
+                    return Kc(e, t)
             }
-        }, Bc.prototype.visitTimeSecond = Hc, Bc.prototype.visitTimeMillisecond = $c, Bc.prototype.visitTimeMicrosecond = Kc, Bc.prototype.visitTimeNanosecond = qc, Bc.prototype.visitDecimal = function(e, t) {
+        }, Lc.prototype.visitTimestampSecond = Yc, Lc.prototype.visitTimestampMillisecond = Hc, Lc.prototype.visitTimestampMicrosecond = $c, Lc.prototype.visitTimestampNanosecond = Kc, Lc.prototype.visitTime = function(e, t) {
+            switch (e.type.unit) {
+                case Ht.SECOND:
+                    return qc(e, t);
+                case Ht.MILLISECOND:
+                    return Qc(e, t);
+                case Ht.MICROSECOND:
+                    return Gc(e, t);
+                case Ht.NANOSECOND:
+                    return Xc(e, t)
+            }
+        }, Lc.prototype.visitTimeSecond = qc, Lc.prototype.visitTimeMillisecond = Qc, Lc.prototype.visitTimeMicrosecond = Gc, Lc.prototype.visitTimeNanosecond = Xc, Lc.prototype.visitDecimal = function(e, t) {
             var n = e.values;
-            return Wr.decimal(n.subarray(4 * t, 4 * (t + 1)))
-        }, Bc.prototype.visitList = function(e, t) {
+            return $r.decimal(n.subarray(4 * t, 4 * (t + 1)))
+        }, Lc.prototype.visitList = function(e, t) {
             var n = e.getChildAt(0),
                 r = e.valueOffsets,
                 i = e.stride;
             return n.slice(r[t * i], r[t * i + 1])
-        }, Bc.prototype.visitStruct = function(e, t) {
+        }, Lc.prototype.visitStruct = function(e, t) {
             return e.bind(t)
-        }, Bc.prototype.visitUnion = function(e, t) {
-            return e.type.mode === Yt.Dense ? Qc(e, t) : Gc(e, t)
-        }, Bc.prototype.visitDenseUnion = Qc, Bc.prototype.visitSparseUnion = Gc, Bc.prototype.visitDictionary = function(e, t) {
+        }, Lc.prototype.visitUnion = function(e, t) {
+            return e.type.mode === Kt.Dense ? Jc(e, t) : Zc(e, t)
+        }, Lc.prototype.visitDenseUnion = Jc, Lc.prototype.visitSparseUnion = Zc, Lc.prototype.visitDictionary = function(e, t) {
             return e.getValue(e.getKey(t))
-        }, Bc.prototype.visitInterval = function(e, t) {
-            return e.type.unit === Ht.DAY_TIME ? Xc(e, t) : Jc(e, t)
-        }, Bc.prototype.visitIntervalDayTime = Xc, Bc.prototype.visitIntervalYearMonth = Jc, Bc.prototype.visitFixedSizeList = function(e, t) {
+        }, Lc.prototype.visitInterval = function(e, t) {
+            return e.type.unit === qt.DAY_TIME ? es(e, t) : ts(e, t)
+        }, Lc.prototype.visitIntervalDayTime = es, Lc.prototype.visitIntervalYearMonth = ts, Lc.prototype.visitFixedSizeList = function(e, t) {
             var n = e.getChildAt(0),
                 r = e.stride;
             return n.slice(t * r, (t + 1) * r)
-        }, Bc.prototype.visitMap = function(e, t) {
+        }, Lc.prototype.visitMap = function(e, t) {
             return e.bind(t)
         };
-        var Zc = new Bc,
-            es = function(e) {
+        var ns = new Lc,
+            rs = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(on);
+            }(sn);
 
-        function ts(e, t, n) {
+        function is(e, t, n) {
             if (void 0 === t) return -1;
             if (null === t) return function(e, t) {
                 var n = e.nullBitmap;
                 if (!n || e.nullCount <= 0) return -1;
                 var r, i = 0,
-                    a = C(en(n, e.data.offset + (t || 0), e.length, n, Qt));
+                    a = C(rn(n, e.data.offset + (t || 0), e.length, n, Jt));
                 try {
                     for (a.s(); !(r = a.n()).done;) {
                         if (!r.value) return i;
                         ++i
                     }
                 } catch (o) {
                     a.e(o)
                 } finally {
                     a.f()
                 }
                 return -1
             }(e, n);
-            for (var r = Mi(t), i = (n || 0) - 1, a = e.length; ++i < a;)
+            for (var r = Ni(t), i = (n || 0) - 1, a = e.length; ++i < a;)
                 if (r(e.get(i))) return i;
             return -1
         }
 
-        function ns(e, t, n) {
-            for (var r = Mi(t), i = (n || 0) - 1, a = e.length; ++i < a;)
+        function as(e, t, n) {
+            for (var r = Ni(t), i = (n || 0) - 1, a = e.length; ++i < a;)
                 if (r(e.get(i))) return i;
             return -1
         }
-        es.prototype.visitNull = function(e, t) {
+        rs.prototype.visitNull = function(e, t) {
             return null === t && e.length > 0 ? 0 : -1
-        }, es.prototype.visitBool = ts, es.prototype.visitInt = ts, es.prototype.visitInt8 = ts, es.prototype.visitInt16 = ts, es.prototype.visitInt32 = ts, es.prototype.visitInt64 = ts, es.prototype.visitUint8 = ts, es.prototype.visitUint16 = ts, es.prototype.visitUint32 = ts, es.prototype.visitUint64 = ts, es.prototype.visitFloat = ts, es.prototype.visitFloat16 = ts, es.prototype.visitFloat32 = ts, es.prototype.visitFloat64 = ts, es.prototype.visitUtf8 = ts, es.prototype.visitBinary = ts, es.prototype.visitFixedSizeBinary = ts, es.prototype.visitDate = ts, es.prototype.visitDateDay = ts, es.prototype.visitDateMillisecond = ts, es.prototype.visitTimestamp = ts, es.prototype.visitTimestampSecond = ts, es.prototype.visitTimestampMillisecond = ts, es.prototype.visitTimestampMicrosecond = ts, es.prototype.visitTimestampNanosecond = ts, es.prototype.visitTime = ts, es.prototype.visitTimeSecond = ts, es.prototype.visitTimeMillisecond = ts, es.prototype.visitTimeMicrosecond = ts, es.prototype.visitTimeNanosecond = ts, es.prototype.visitDecimal = ts, es.prototype.visitList = ts, es.prototype.visitStruct = ts, es.prototype.visitUnion = ts, es.prototype.visitDenseUnion = ns, es.prototype.visitSparseUnion = ns, es.prototype.visitDictionary = ts, es.prototype.visitInterval = ts, es.prototype.visitIntervalDayTime = ts, es.prototype.visitIntervalYearMonth = ts, es.prototype.visitFixedSizeList = ts, es.prototype.visitMap = ts;
-        var rs = new es,
-            is = function(e) {
+        }, rs.prototype.visitBool = is, rs.prototype.visitInt = is, rs.prototype.visitInt8 = is, rs.prototype.visitInt16 = is, rs.prototype.visitInt32 = is, rs.prototype.visitInt64 = is, rs.prototype.visitUint8 = is, rs.prototype.visitUint16 = is, rs.prototype.visitUint32 = is, rs.prototype.visitUint64 = is, rs.prototype.visitFloat = is, rs.prototype.visitFloat16 = is, rs.prototype.visitFloat32 = is, rs.prototype.visitFloat64 = is, rs.prototype.visitUtf8 = is, rs.prototype.visitBinary = is, rs.prototype.visitFixedSizeBinary = is, rs.prototype.visitDate = is, rs.prototype.visitDateDay = is, rs.prototype.visitDateMillisecond = is, rs.prototype.visitTimestamp = is, rs.prototype.visitTimestampSecond = is, rs.prototype.visitTimestampMillisecond = is, rs.prototype.visitTimestampMicrosecond = is, rs.prototype.visitTimestampNanosecond = is, rs.prototype.visitTime = is, rs.prototype.visitTimeSecond = is, rs.prototype.visitTimeMillisecond = is, rs.prototype.visitTimeMicrosecond = is, rs.prototype.visitTimeNanosecond = is, rs.prototype.visitDecimal = is, rs.prototype.visitList = is, rs.prototype.visitStruct = is, rs.prototype.visitUnion = is, rs.prototype.visitDenseUnion = as, rs.prototype.visitSparseUnion = as, rs.prototype.visitDictionary = is, rs.prototype.visitInterval = is, rs.prototype.visitIntervalDayTime = is, rs.prototype.visitIntervalYearMonth = is, rs.prototype.visitFixedSizeList = is, rs.prototype.visitMap = is;
+        var os = new rs,
+            us = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(on);
+            }(sn);
 
-        function as(e) {
+        function cs(e) {
             if (e.nullCount > 0) return function(e) {
-                var t = Zc.getVisitFn(e);
-                return en(e.nullBitmap, e.offset, e.length, e, (function(e, n, r, i) {
+                var t = ns.getVisitFn(e);
+                return rn(e.nullBitmap, e.offset, e.length, e, (function(e, n, r, i) {
                     return 0 !== (r & 1 << i) ? t(e, n) : null
                 }))
             }(e);
             var t = e.type,
                 n = e.typeId,
                 r = e.length;
-            return 1 === e.stride && (n === Ut.Timestamp || n === Ut.Int && 64 !== t.bitWidth || n === Ut.Time && 64 !== t.bitWidth || n === Ut.Float && t.precision > 0) ? e.values.subarray(0, r)[Symbol.iterator]() : Object(L.a)().mark((function t(n) {
+            return 1 === e.stride && (n === Vt.Timestamp || n === Vt.Int && 64 !== t.bitWidth || n === Vt.Time && 64 !== t.bitWidth || n === Vt.Float && t.precision > 0) ? e.values.subarray(0, r)[Symbol.iterator]() : Object(L.a)().mark((function t(n) {
                 var i;
                 return Object(L.a)().wrap((function(t) {
                     for (;;) switch (t.prev = t.next) {
                         case 0:
                             i = -1;
                         case 1:
                             if (!(++i < r)) {
@@ -14941,51 +14957,51 @@
                             t.next = 1;
                             break;
                         case 6:
                         case "end":
                             return t.stop()
                     }
                 }), t)
-            }))(Zc.getVisitFn(e))
+            }))(ns.getVisitFn(e))
         }
-        is.prototype.visitNull = as, is.prototype.visitBool = as, is.prototype.visitInt = as, is.prototype.visitInt8 = as, is.prototype.visitInt16 = as, is.prototype.visitInt32 = as, is.prototype.visitInt64 = as, is.prototype.visitUint8 = as, is.prototype.visitUint16 = as, is.prototype.visitUint32 = as, is.prototype.visitUint64 = as, is.prototype.visitFloat = as, is.prototype.visitFloat16 = as, is.prototype.visitFloat32 = as, is.prototype.visitFloat64 = as, is.prototype.visitUtf8 = as, is.prototype.visitBinary = as, is.prototype.visitFixedSizeBinary = as, is.prototype.visitDate = as, is.prototype.visitDateDay = as, is.prototype.visitDateMillisecond = as, is.prototype.visitTimestamp = as, is.prototype.visitTimestampSecond = as, is.prototype.visitTimestampMillisecond = as, is.prototype.visitTimestampMicrosecond = as, is.prototype.visitTimestampNanosecond = as, is.prototype.visitTime = as, is.prototype.visitTimeSecond = as, is.prototype.visitTimeMillisecond = as, is.prototype.visitTimeMicrosecond = as, is.prototype.visitTimeNanosecond = as, is.prototype.visitDecimal = as, is.prototype.visitList = as, is.prototype.visitStruct = as, is.prototype.visitUnion = as, is.prototype.visitDenseUnion = as, is.prototype.visitSparseUnion = as, is.prototype.visitDictionary = as, is.prototype.visitInterval = as, is.prototype.visitIntervalDayTime = as, is.prototype.visitIntervalYearMonth = as, is.prototype.visitFixedSizeList = as, is.prototype.visitMap = as;
-        var os = new is,
-            us = function(e) {
+        us.prototype.visitNull = cs, us.prototype.visitBool = cs, us.prototype.visitInt = cs, us.prototype.visitInt8 = cs, us.prototype.visitInt16 = cs, us.prototype.visitInt32 = cs, us.prototype.visitInt64 = cs, us.prototype.visitUint8 = cs, us.prototype.visitUint16 = cs, us.prototype.visitUint32 = cs, us.prototype.visitUint64 = cs, us.prototype.visitFloat = cs, us.prototype.visitFloat16 = cs, us.prototype.visitFloat32 = cs, us.prototype.visitFloat64 = cs, us.prototype.visitUtf8 = cs, us.prototype.visitBinary = cs, us.prototype.visitFixedSizeBinary = cs, us.prototype.visitDate = cs, us.prototype.visitDateDay = cs, us.prototype.visitDateMillisecond = cs, us.prototype.visitTimestamp = cs, us.prototype.visitTimestampSecond = cs, us.prototype.visitTimestampMillisecond = cs, us.prototype.visitTimestampMicrosecond = cs, us.prototype.visitTimestampNanosecond = cs, us.prototype.visitTime = cs, us.prototype.visitTimeSecond = cs, us.prototype.visitTimeMillisecond = cs, us.prototype.visitTimeMicrosecond = cs, us.prototype.visitTimeNanosecond = cs, us.prototype.visitDecimal = cs, us.prototype.visitList = cs, us.prototype.visitStruct = cs, us.prototype.visitUnion = cs, us.prototype.visitDenseUnion = cs, us.prototype.visitSparseUnion = cs, us.prototype.visitDictionary = cs, us.prototype.visitInterval = cs, us.prototype.visitIntervalDayTime = cs, us.prototype.visitIntervalYearMonth = cs, us.prototype.visitFixedSizeList = cs, us.prototype.visitMap = cs;
+        var ss = new us,
+            ls = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n)
-            }(on);
+            }(sn);
 
-        function cs(e) {
+        function fs(e) {
             var t = e.type,
                 n = e.length,
                 r = e.stride;
             switch (t.typeId) {
-                case Ut.Int:
-                case Ut.Float:
-                case Ut.Decimal:
-                case Ut.Time:
-                case Ut.Timestamp:
+                case Vt.Int:
+                case Vt.Float:
+                case Vt.Decimal:
+                case Vt.Time:
+                case Vt.Timestamp:
                     return e.values.subarray(0, n * r)
             }
-            return Object(an.a)(os.visit(e))
+            return Object(cn.a)(ss.visit(e))
         }
-        us.prototype.visitNull = cs, us.prototype.visitBool = cs, us.prototype.visitInt = cs, us.prototype.visitInt8 = cs, us.prototype.visitInt16 = cs, us.prototype.visitInt32 = cs, us.prototype.visitInt64 = cs, us.prototype.visitUint8 = cs, us.prototype.visitUint16 = cs, us.prototype.visitUint32 = cs, us.prototype.visitUint64 = cs, us.prototype.visitFloat = cs, us.prototype.visitFloat16 = cs, us.prototype.visitFloat32 = cs, us.prototype.visitFloat64 = cs, us.prototype.visitUtf8 = cs, us.prototype.visitBinary = cs, us.prototype.visitFixedSizeBinary = cs, us.prototype.visitDate = cs, us.prototype.visitDateDay = cs, us.prototype.visitDateMillisecond = cs, us.prototype.visitTimestamp = cs, us.prototype.visitTimestampSecond = cs, us.prototype.visitTimestampMillisecond = cs, us.prototype.visitTimestampMicrosecond = cs, us.prototype.visitTimestampNanosecond = cs, us.prototype.visitTime = cs, us.prototype.visitTimeSecond = cs, us.prototype.visitTimeMillisecond = cs, us.prototype.visitTimeMicrosecond = cs, us.prototype.visitTimeNanosecond = cs, us.prototype.visitDecimal = cs, us.prototype.visitList = cs, us.prototype.visitStruct = cs, us.prototype.visitUnion = cs, us.prototype.visitDenseUnion = cs, us.prototype.visitSparseUnion = cs, us.prototype.visitDictionary = cs, us.prototype.visitInterval = cs, us.prototype.visitIntervalDayTime = cs, us.prototype.visitIntervalYearMonth = cs, us.prototype.visitFixedSizeList = cs, us.prototype.visitMap = cs;
-        var ss = new us,
-            ls = function(e, t) {
+        ls.prototype.visitNull = fs, ls.prototype.visitBool = fs, ls.prototype.visitInt = fs, ls.prototype.visitInt8 = fs, ls.prototype.visitInt16 = fs, ls.prototype.visitInt32 = fs, ls.prototype.visitInt64 = fs, ls.prototype.visitUint8 = fs, ls.prototype.visitUint16 = fs, ls.prototype.visitUint32 = fs, ls.prototype.visitUint64 = fs, ls.prototype.visitFloat = fs, ls.prototype.visitFloat16 = fs, ls.prototype.visitFloat32 = fs, ls.prototype.visitFloat64 = fs, ls.prototype.visitUtf8 = fs, ls.prototype.visitBinary = fs, ls.prototype.visitFixedSizeBinary = fs, ls.prototype.visitDate = fs, ls.prototype.visitDateDay = fs, ls.prototype.visitDateMillisecond = fs, ls.prototype.visitTimestamp = fs, ls.prototype.visitTimestampSecond = fs, ls.prototype.visitTimestampMillisecond = fs, ls.prototype.visitTimestampMicrosecond = fs, ls.prototype.visitTimestampNanosecond = fs, ls.prototype.visitTime = fs, ls.prototype.visitTimeSecond = fs, ls.prototype.visitTimeMillisecond = fs, ls.prototype.visitTimeMicrosecond = fs, ls.prototype.visitTimeNanosecond = fs, ls.prototype.visitDecimal = fs, ls.prototype.visitList = fs, ls.prototype.visitStruct = fs, ls.prototype.visitUnion = fs, ls.prototype.visitDenseUnion = fs, ls.prototype.visitSparseUnion = fs, ls.prototype.visitDictionary = fs, ls.prototype.visitInterval = fs, ls.prototype.visitIntervalDayTime = fs, ls.prototype.visitIntervalYearMonth = fs, ls.prototype.visitFixedSizeList = fs, ls.prototype.visitMap = fs;
+        var hs = new ls,
+            ds = function(e, t) {
                 return e + t
             },
-            fs = function(e) {
+            ps = function(e) {
                 return "Cannot compute the byte width of variable-width column ".concat(e)
             },
-            hs = function(e) {
+            ys = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
@@ -15002,20 +15018,20 @@
                     key: "visitFloat",
                     value: function(e) {
                         return e.ArrayType.BYTES_PER_ELEMENT
                     }
                 }, {
                     key: "visitBinary",
                     value: function(e) {
-                        throw new Error(fs(e))
+                        throw new Error(ps(e))
                     }
                 }, {
                     key: "visitUtf8",
                     value: function(e) {
-                        throw new Error(fs(e))
+                        throw new Error(ps(e))
                     }
                 }, {
                     key: "visitBool",
                     value: function(e) {
                         return 1 / 8
                     }
                 }, {
@@ -15032,50 +15048,50 @@
                     key: "visitTime",
                     value: function(e) {
                         return e.bitWidth / 8
                     }
                 }, {
                     key: "visitTimestamp",
                     value: function(e) {
-                        return e.unit === Vt.SECOND ? 4 : 8
+                        return e.unit === Ht.SECOND ? 4 : 8
                     }
                 }, {
                     key: "visitInterval",
                     value: function(e) {
                         return 4 * (e.unit + 1)
                     }
                 }, {
                     key: "visitList",
                     value: function(e) {
-                        throw new Error(fs(e))
+                        throw new Error(ps(e))
                     }
                 }, {
                     key: "visitStruct",
                     value: function(e) {
-                        return this.visitFields(e.children).reduce(ls, 0)
+                        return this.visitFields(e.children).reduce(ds, 0)
                     }
                 }, {
                     key: "visitUnion",
                     value: function(e) {
-                        return this.visitFields(e.children).reduce(ls, 0)
+                        return this.visitFields(e.children).reduce(ds, 0)
                     }
                 }, {
                     key: "visitFixedSizeBinary",
                     value: function(e) {
                         return e.byteWidth
                     }
                 }, {
                     key: "visitFixedSizeList",
                     value: function(e) {
-                        return e.listSize * this.visitFields(e.children).reduce(ls, 0)
+                        return e.listSize * this.visitFields(e.children).reduce(ds, 0)
                     }
                 }, {
                     key: "visitMap",
                     value: function(e) {
-                        return this.visitFields(e.children).reduce(ls, 0)
+                        return this.visitFields(e.children).reduce(ds, 0)
                     }
                 }, {
                     key: "visitDictionary",
                     value: function(e) {
                         return this.visit(e.indices)
                     }
                 }, {
@@ -15085,291 +15101,291 @@
                         return (e || []).map((function(e) {
                             return t.visit(e.type)
                         }))
                     }
                 }, {
                     key: "visitSchema",
                     value: function(e) {
-                        return this.visitFields(e.fields).reduce(ls, 0)
+                        return this.visitFields(e.fields).reduce(ds, 0)
                     }
                 }]), n
-            }(on),
-            ds = new hs,
-            ps = function(e) {
+            }(sn),
+            vs = new ys,
+            bs = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "visitNull",
                     value: function() {
-                        return dc
+                        return vc
                     }
                 }, {
                     key: "visitBool",
                     value: function() {
-                        return Lu
+                        return Pu
                     }
                 }, {
                     key: "visitInt",
                     value: function() {
-                        return Zu
+                        return nc
                     }
                 }, {
                     key: "visitInt8",
                     value: function() {
-                        return ec
+                        return rc
                     }
                 }, {
                     key: "visitInt16",
                     value: function() {
-                        return tc
+                        return ic
                     }
                 }, {
                     key: "visitInt32",
                     value: function() {
-                        return nc
+                        return ac
                     }
                 }, {
                     key: "visitInt64",
                     value: function() {
-                        return rc
+                        return oc
                     }
                 }, {
                     key: "visitUint8",
                     value: function() {
-                        return ic
+                        return uc
                     }
                 }, {
                     key: "visitUint16",
                     value: function() {
-                        return ac
+                        return cc
                     }
                 }, {
                     key: "visitUint32",
                     value: function() {
-                        return oc
+                        return sc
                     }
                 }, {
                     key: "visitUint64",
                     value: function() {
-                        return uc
+                        return lc
                     }
                 }, {
                     key: "visitFloat",
                     value: function() {
-                        return Wu
+                        return $u
                     }
                 }, {
                     key: "visitFloat16",
                     value: function() {
-                        return Yu
+                        return Ku
                     }
                 }, {
                     key: "visitFloat32",
                     value: function() {
-                        return Hu
+                        return qu
                     }
                 }, {
                     key: "visitFloat64",
                     value: function() {
-                        return $u
+                        return Qu
                     }
                 }, {
                     key: "visitUtf8",
                     value: function() {
-                        return Ec
+                        return Bc
                     }
                 }, {
                     key: "visitBinary",
                     value: function() {
-                        return Mu
+                        return Nu
                     }
                 }, {
                     key: "visitFixedSizeBinary",
                     value: function() {
-                        return zu
+                        return Yu
                     }
                 }, {
                     key: "visitDate",
                     value: function() {
-                        return Fu
+                        return Uu
                     }
                 }, {
                     key: "visitDateDay",
                     value: function() {
-                        return Nu
+                        return Ru
                     }
                 }, {
                     key: "visitDateMillisecond",
                     value: function() {
-                        return Pu
+                        return zu
                     }
                 }, {
                     key: "visitTimestamp",
                     value: function() {
-                        return vc
+                        return gc
                     }
                 }, {
                     key: "visitTimestampSecond",
                     value: function() {
-                        return bc
+                        return kc
                     }
                 }, {
                     key: "visitTimestampMillisecond",
                     value: function() {
-                        return mc
+                        return wc
                     }
                 }, {
                     key: "visitTimestampMicrosecond",
                     value: function() {
-                        return gc
+                        return Oc
                     }
                 }, {
                     key: "visitTimestampNanosecond",
                     value: function() {
-                        return kc
+                        return _c
                     }
                 }, {
                     key: "visitTime",
                     value: function() {
-                        return wc
+                        return jc
                     }
                 }, {
                     key: "visitTimeSecond",
                     value: function() {
-                        return Oc
+                        return xc
                     }
                 }, {
                     key: "visitTimeMillisecond",
                     value: function() {
-                        return _c
+                        return Tc
                     }
                 }, {
                     key: "visitTimeMicrosecond",
                     value: function() {
-                        return jc
+                        return Sc
                     }
                 }, {
                     key: "visitTimeNanosecond",
                     value: function() {
-                        return xc
+                        return Ic
                     }
                 }, {
                     key: "visitDecimal",
                     value: function() {
-                        return Uu
+                        return Vu
                     }
                 }, {
                     key: "visitList",
                     value: function() {
-                        return fc
+                        return pc
                     }
                 }, {
                     key: "visitStruct",
                     value: function() {
-                        return yc
+                        return mc
                     }
                 }, {
                     key: "visitUnion",
                     value: function() {
-                        return Tc
+                        return Ec
                     }
                 }, {
                     key: "visitDenseUnion",
                     value: function() {
-                        return Sc
+                        return Ac
                     }
                 }, {
                     key: "visitSparseUnion",
                     value: function() {
-                        return Ic
+                        return Cc
                     }
                 }, {
                     key: "visitDictionary",
                     value: function() {
-                        return Ru
+                        return Wu
                     }
                 }, {
                     key: "visitInterval",
                     value: function() {
-                        return Gu
+                        return Zu
                     }
                 }, {
                     key: "visitIntervalDayTime",
                     value: function() {
-                        return Xu
+                        return ec
                     }
                 }, {
                     key: "visitIntervalYearMonth",
                     value: function() {
-                        return Ju
+                        return tc
                     }
                 }, {
                     key: "visitFixedSizeList",
                     value: function() {
-                        return Vu
+                        return Hu
                     }
                 }, {
                     key: "visitMap",
                     value: function() {
-                        return hc
+                        return yc
                     }
                 }]), n
-            }(on),
-            ys = new ps,
-            vs = ["values"];
+            }(sn),
+            ms = new bs,
+            gs = ["values"];
 
-        function bs(e, t) {
-            if (_e(t)) return Pt.from({
+        function ks(e, t) {
+            if (Te(t)) return zt.from({
                 nullValues: [null, void 0],
                 type: e(),
                 values: t
             });
-            if (je(t)) return Pt.from({
+            if (Se(t)) return zt.from({
                 nullValues: [null, void 0],
                 type: e(),
                 values: t
             });
-            var n = Object(Et.a)({}, t),
+            var n = Object(Bt.a)({}, t),
                 r = n.values,
                 i = void 0 === r ? [] : r,
                 a = n.type,
                 o = void 0 === a ? e() : a,
                 u = n.nullValues,
                 c = void 0 === u ? [null, void 0] : u;
-            return _e(i), Pt.from(Object(Et.a)(Object(Et.a)({
+            return Te(i), zt.from(Object(Bt.a)(Object(Bt.a)({
                 nullValues: c
             }, t), {}, {
                 type: o
             }))
         }
-        Pt.new = function(e) {
+        zt.new = function(e) {
             for (var t = arguments.length, n = new Array(t > 1 ? t - 1 : 0), r = 1; r < t; r++) n[r - 1] = arguments[r];
-            return Br(ys.getVisitFn(e)(), [e].concat(n))
-        }, Pt.from = function(e) {
-            var t = Object(Et.a)({
+            return Lr(ms.getVisitFn(e)(), [e].concat(n))
+        }, zt.from = function(e) {
+            var t = Object(Bt.a)({
                     nullValues: [null, void 0]
                 }, e),
                 n = t.values,
                 r = void 0 === n ? [] : n,
-                i = Bu(t, vs);
-            if (_e(r)) {
-                var a = Object(an.a)(fr.throughIterable(i)(r));
-                return 1 === a.length ? a[0] : Ni.concat(a)
+                i = Lu(t, gs);
+            if (Te(r)) {
+                var a = Object(cn.a)(pr.throughIterable(i)(r));
+                return 1 === a.length ? a[0] : Ri.concat(a)
             }
             return function() {
                 var e = Object(B.a)(Object(L.a)().mark((function e(t) {
                     var n, a, o, u, c, s, l;
                     return Object(L.a)().wrap((function(e) {
                         for (;;) switch (e.prev = e.next) {
                             case 0:
-                                n = fr.throughAsyncIterable(i), a = !1, o = !1, e.prev = 3, c = V(n(r));
+                                n = pr.throughAsyncIterable(i), a = !1, o = !1, e.prev = 3, c = V(n(r));
                             case 5:
                                 return e.next = 7, c.next();
                             case 7:
                                 if (!(a = !(s = e.sent).done)) {
                                     e.next = 13;
                                     break
                                 }
@@ -15395,78 +15411,78 @@
                                 }
                                 throw u;
                             case 27:
                                 return e.finish(24);
                             case 28:
                                 return e.finish(19);
                             case 29:
-                                return e.abrupt("return", 1 === t.length ? t[0] : Ni.concat(t));
+                                return e.abrupt("return", 1 === t.length ? t[0] : Ri.concat(t));
                             case 30:
                             case "end":
                                 return e.stop()
                         }
                     }), e, null, [
                         [3, 15, 19, 29],
                         [20, , 24, 28]
                     ])
                 })));
                 return function(t) {
                     return e.apply(this, arguments)
                 }
             }()([])
-        }, Du.prototype.get = function(e) {
-            return Zc.visit(this, e)
-        }, Du.prototype.set = function(e, t) {
-            return Aa.visit(this, e, t)
-        }, Du.prototype.indexOf = function(e, t) {
-            return rs.visit(this, e, t)
-        }, Du.prototype.toArray = function() {
+        }, Fu.prototype.get = function(e) {
+            return ns.visit(this, e)
+        }, Fu.prototype.set = function(e, t) {
+            return Da.visit(this, e, t)
+        }, Fu.prototype.indexOf = function(e, t) {
+            return os.visit(this, e, t)
+        }, Fu.prototype.toArray = function() {
+            return hs.visit(this)
+        }, Fu.prototype.getByteWidth = function() {
+            return vs.visit(this.type)
+        }, Fu.prototype[Symbol.iterator] = function() {
             return ss.visit(this)
-        }, Du.prototype.getByteWidth = function() {
-            return ds.visit(this.type)
-        }, Du.prototype[Symbol.iterator] = function() {
-            return os.visit(this)
-        }, Du.prototype._bindDataAccessors = function() {
+        }, Fu.prototype._bindDataAccessors = function() {
             var e = this.nullBitmap;
             e && e.byteLength > 0 && (this.get = (t = this.get, function(e) {
                 return this.isValid(e) ? t.call(this, e) : null
             }), this.set = function(e) {
                 return function(t, n) {
-                    Xt(this.nullBitmap, this.offset + t, !(null === n || void 0 === n)) && e.call(this, t, n)
+                    en(this.nullBitmap, this.offset + t, !(null === n || void 0 === n)) && e.call(this, t, n)
                 }
             }(this.set));
             var t
-        }, Object.keys(Ut).map((function(e) {
-            return Ut[e]
+        }, Object.keys(Vt).map((function(e) {
+            return Vt[e]
         })).filter((function(e) {
             return "number" === typeof e
         })).filter((function(e) {
-            return e !== Ut.NONE
+            return e !== Vt.NONE
         })).forEach((function(e) {
-            var t, n = ys.visit(e);
-            n.prototype.get = (t = Zc.getVisitFn(e), function(e) {
+            var t, n = ms.visit(e);
+            n.prototype.get = (t = ns.getVisitFn(e), function(e) {
                 return t(this, e)
-            }), n.prototype.set = Cc(Aa.getVisitFn(e)), n.prototype.indexOf = Cc(rs.getVisitFn(e)), n.prototype.toArray = Ac(ss.getVisitFn(e)), n.prototype.getByteWidth = function(e) {
+            }), n.prototype.set = Mc(Da.getVisitFn(e)), n.prototype.indexOf = Mc(os.getVisitFn(e)), n.prototype.toArray = Dc(hs.getVisitFn(e)), n.prototype.getByteWidth = function(e) {
                 return function() {
                     return e(this.type)
                 }
-            }(ds.getVisitFn(e)), n.prototype[Symbol.iterator] = Ac(os.getVisitFn(e))
+            }(vs.getVisitFn(e)), n.prototype[Symbol.iterator] = Dc(ss.getVisitFn(e))
         }));
-        var ms = function(e) {
+        var ws = function(e) {
             Object(ae.a)(n, e);
             var t = Object(oe.a)(n);
 
             function n() {
                 var e;
                 Object(D.a)(this, n);
                 for (var r = null, i = arguments.length, a = new Array(i), o = 0; o < i; o++) a[o] = arguments[o];
-                a[0] instanceof Ji && (r = a.shift());
-                var u = Wi(gs, a);
+                a[0] instanceof ta && (r = a.shift());
+                var u = $i(Os, a);
                 if (!r && !(r = u[0] && u[0].schema)) throw new TypeError("Table must be initialized with a Schema or at least one RecordBatch");
-                return u[0] || (u[0] = new ks(r)), (e = t.call(this, new $n(r.fields), u))._schema = r, e._chunks = u, e
+                return u[0] || (u[0] = new _s(r)), (e = t.call(this, new Qn(r.fields), u))._schema = r, e._chunks = u, e
             }
             return Object(M.a)(n, [{
                 key: "schema",
                 get: function() {
                     return this._schema
                 }
             }, {
@@ -15516,121 +15532,121 @@
                     if (n = i[e]) return n;
                     if (t = r[e]) {
                         var a = this._chunks.map((function(t) {
                             return t.getChildAt(e)
                         })).filter((function(e) {
                             return null != e
                         }));
-                        if (a.length > 0) return i[e] = new Ri(t, a)
+                        if (a.length > 0) return i[e] = new Wi(t, a)
                     }
                     return null
                 }
             }, {
                 key: "serialize",
                 value: function() {
-                    return (!(arguments.length > 1 && void 0 !== arguments[1]) || arguments[1] ? _u : ju).writeAll(this).toUint8Array(!0)
+                    return (!(arguments.length > 1 && void 0 !== arguments[1]) || arguments[1] ? Tu : Su).writeAll(this).toUint8Array(!0)
                 }
             }, {
                 key: "count",
                 value: function() {
                     return this._length
                 }
             }, {
                 key: "select",
                 value: function() {
                     for (var e = this._schema.fields.reduce((function(e, t, n) {
                             return e.set(t.name, n)
                         }), new Map), t = arguments.length, n = new Array(t), r = 0; r < t; r++) n[r] = arguments[r];
-                    return this.selectAt.apply(this, Object(an.a)(n.map((function(t) {
+                    return this.selectAt.apply(this, Object(cn.a)(n.map((function(t) {
                         return e.get(t)
                     })).filter((function(e) {
                         return e > -1
                     }))))
                 }
             }, {
                 key: "selectAt",
                 value: function() {
                     for (var e, t = arguments.length, r = new Array(t), i = 0; i < t; i++) r[i] = arguments[i];
                     var a = (e = this._schema).selectAt.apply(e, r);
                     return new n(a, this._chunks.map((function(e) {
                         var t = e.length,
                             n = e.data.childData;
-                        return new gs(a, t, r.map((function(e) {
+                        return new Os(a, t, r.map((function(e) {
                             return n[e]
                         })).filter(Boolean))
                     })))
                 }
             }, {
                 key: "assign",
                 value: function(e) {
                     var t = this,
                         r = this._schema.fields,
                         i = e.schema.fields.reduce((function(e, t, n) {
-                            var i = F(e, 2),
+                            var i = Object(F.a)(e, 2),
                                 a = i[0],
                                 o = i[1],
                                 u = r.findIndex((function(e) {
                                     return e.name === t.name
                                 }));
                             return ~u ? o[u] = n : a.push(n), e
                         }), [
                             [],
                             []
                         ]),
-                        a = F(i, 2),
+                        a = Object(F.a)(i, 2),
                         o = a[0],
                         u = a[1],
                         c = this._schema.assign(e.schema),
-                        s = [].concat(Object(an.a)(r.map((function(n, r, i) {
+                        s = [].concat(Object(cn.a)(r.map((function(n, r, i) {
                             var a = arguments.length > 3 && void 0 !== arguments[3] ? arguments[3] : u[r];
                             return void 0 === a ? t.getColumnAt(r) : e.getColumnAt(a)
-                        }))), Object(an.a)(o.map((function(t) {
+                        }))), Object(cn.a)(o.map((function(t) {
                             return e.getColumnAt(t)
                         })))).filter(Boolean);
-                    return Br(n, Object(an.a)(Au(c, s)))
+                    return Lr(n, Object(cn.a)(Du(c, s)))
                 }
             }], [{
                 key: "empty",
                 value: function() {
-                    return new n(arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : new Ji([]), [])
+                    return new n(arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : new ta([]), [])
                 }
             }, {
                 key: "from",
                 value: function(e) {
                     if (!e) return n.empty();
                     if ("object" === typeof e) {
-                        var t = _e(e.values) ? function(e) {
+                        var t = Te(e.values) ? function(e) {
                             var t = e.type;
-                            if (t instanceof $n) return ms.fromStruct(yc.from(e));
+                            if (t instanceof Qn) return ws.fromStruct(mc.from(e));
                             return null
-                        }(e) : je(e.values) ? function(e) {
+                        }(e) : Se(e.values) ? function(e) {
                             var t = e.type;
-                            if (t instanceof $n) return yc.from(e).then((function(e) {
-                                return ms.fromStruct(e)
+                            if (t instanceof Qn) return mc.from(e).then((function(e) {
+                                return ws.fromStruct(e)
                             }));
                             return null
                         }(e) : null;
                         if (null !== t) return t
                     }
-                    var r = _s.from(e);
-                    return Oe(r) ? Object(B.a)(Object(L.a)().mark((function e() {
+                    var r = Ts.from(e);
+                    return xe(r) ? Object(B.a)(Object(L.a)().mark((function e() {
                         return Object(L.a)().wrap((function(e) {
                             for (;;) switch (e.prev = e.next) {
                                 case 0:
                                     return e.t0 = n, e.next = 3, r;
                                 case 3:
                                     return e.t1 = e.sent, e.next = 6, e.t0.from.call(e.t0, e.t1);
                                 case 6:
                                     return e.abrupt("return", e.sent);
                                 case 7:
                                 case "end":
                                     return e.stop()
                             }
                         }), e)
-                    })))() : r.isSync() && (r = r.open()) ? r.schema ? new n(r.schema, Object(an.a)(r)) : n.empty() : function() {
+                    })))() : r.isSync() && (r = r.open()) ? r.schema ? new n(r.schema, Object(cn.a)(r)) : n.empty() : function() {
                         var e = Object(B.a)(Object(L.a)().mark((function e(t) {
                             var r, i, a, o, u, c, s, l, f;
                             return Object(L.a)().wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
                                     case 0:
                                         return e.next = 2, t;
                                     case 2:
@@ -15714,61 +15730,62 @@
                 value: function(e) {
                     return n.new(e.data.childData, e.type.children)
                 }
             }, {
                 key: "new",
                 value: function() {
                     for (var e = arguments.length, t = new Array(e), r = 0; r < e; r++) t[r] = arguments[r];
-                    return Br(n, Object(an.a)((i = function(e) {
-                        var t = F(Xi(e, [
+                    return Lr(n, Object(cn.a)((i = function(e) {
+                        var t = ea(e, [
                                 [],
                                 []
-                            ]), 2),
-                            n = t[0];
-                        return t[1].map((function(e, t) {
-                            return e instanceof Ri ? Ri.new(e.field.clone(n[t]), e) : e instanceof Pt ? Ri.new(n[t], e) : Ri.new(n[t], [])
+                            ]),
+                            n = Object(F.a)(t, 2),
+                            r = n[0];
+                        return n[1].map((function(e, t) {
+                            return e instanceof Wi ? Wi.new(e.field.clone(r[t]), e) : e instanceof zt ? Wi.new(r[t], e) : Wi.new(r[t], [])
                         }))
-                    }(t), Au(new Ji(i.map((function(e) {
+                    }(t), Du(new ta(i.map((function(e) {
                         return e.field
                     }))), i))));
                     var i
                 }
             }]), n
-        }(Ni);
-        var gs = function(e) {
+        }(Ri);
+        var Os = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     var e, r;
                     Object(D.a)(this, n);
                     for (var i = arguments.length, a = new Array(i), o = 0; o < i; o++) a[o] = arguments[o];
                     var u, c = a[0];
-                    if (a[1] instanceof tr) r = a[1], u = a[2];
+                    if (a[1] instanceof ir) r = a[1], u = a[2];
                     else {
                         var s = c.fields,
                             l = a[1],
                             f = a[2];
-                        r = tr.Struct(new $n(s), 0, l, 0, null, f)
+                        r = ir.Struct(new Qn(s), 0, l, 0, null, f)
                     }
                     return (e = t.call(this, r, u))._schema = c, e
                 }
                 return Object(M.a)(n, [{
                     key: "clone",
                     value: function(e) {
                         var t = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : this._children;
                         return new n(this._schema, e, t)
                     }
                 }, {
                     key: "concat",
                     value: function() {
                         for (var e = arguments.length, t = new Array(e), r = 0; r < e; r++) t[r] = arguments[r];
                         var i = this._schema,
-                            a = Ni.flatten.apply(Ni, [this].concat(t));
-                        return new ms(i, a.map((function(e) {
+                            a = Ri.flatten.apply(Ri, [this].concat(t));
+                        return new ws(i, a.map((function(e) {
                             var t = e.data;
                             return new n(i, t)
                         })))
                     }
                 }, {
                     key: "schema",
                     get: function() {
@@ -15778,23 +15795,23 @@
                     key: "numCols",
                     get: function() {
                         return this._schema.fields.length
                     }
                 }, {
                     key: "dictionaries",
                     get: function() {
-                        return this._dictionaries || (this._dictionaries = ws.collect(this))
+                        return this._dictionaries || (this._dictionaries = js.collect(this))
                     }
                 }, {
                     key: "select",
                     value: function() {
                         for (var e = this._schema.fields.reduce((function(e, t, n) {
                                 return e.set(t.name, n)
                             }), new Map), t = arguments.length, n = new Array(t), r = 0; r < t; r++) n[r] = arguments[r];
-                        return this.selectAt.apply(this, Object(an.a)(n.map((function(t) {
+                        return this.selectAt.apply(this, Object(cn.a)(n.map((function(t) {
                             return e.get(t)
                         })).filter((function(e) {
                             return e > -1
                         }))))
                     }
                 }, {
                     key: "selectAt",
@@ -15805,80 +15822,81 @@
                                 return t.data.childData[e]
                             })).filter(Boolean);
                         return new n(o, this.length, u)
                     }
                 }], [{
                     key: "from",
                     value: function(e) {
-                        return _e(e.values), ms.from(e)
+                        return Te(e.values), ws.from(e)
                     }
                 }, {
                     key: "new",
                     value: function() {
                         for (var e = arguments.length, t = new Array(e), r = 0; r < e; r++) t[r] = arguments[r];
-                        var i = F(Yi(t), 2),
-                            a = i[0],
-                            o = i[1].filter((function(e) {
-                                return e instanceof Pt
+                        var i = Ki(t),
+                            a = Object(F.a)(i, 2),
+                            o = a[0],
+                            u = a[1].filter((function(e) {
+                                return e instanceof zt
                             }));
-                        return Br(n, Object(an.a)(function(e, t) {
+                        return Lr(n, Object(cn.a)(function(e, t) {
                             for (var n, r, i = arguments.length > 2 && void 0 !== arguments[2] ? arguments[2] : t.reduce((function(e, t) {
                                     return Math.max(e, t.length)
-                                }), 0), a = -1, o = t.length, u = Object(an.a)(e.fields), c = [], s = (i + 63 & -64) >> 3; ++a < o;)(n = t[a]) && n.length === i ? c[a] = n : ((r = u[a]).nullable || (u[a] = u[a].clone({
+                                }), 0), a = -1, o = t.length, u = Object(cn.a)(e.fields), c = [], s = (i + 63 & -64) >> 3; ++a < o;)(n = t[a]) && n.length === i ? c[a] = n : ((r = u[a]).nullable || (u[a] = u[a].clone({
                                 nullable: !0
-                            })), c[a] = n ? n._changeLengthAndBackfillNullBitmap(i) : tr.new(r.type, 0, i, i, Eu(s)));
-                            return [new Ji(u), i, c]
-                        }(new Ji(a), o.map((function(e) {
+                            })), c[a] = n ? n._changeLengthAndBackfillNullBitmap(i) : ir.new(r.type, 0, i, i, Bu(s)));
+                            return [new ta(u), i, c]
+                        }(new ta(o), u.map((function(e) {
                             return e.data
                         })))))
                     }
                 }]), n
-            }(yc),
-            ks = function(e) {
+            }(mc),
+            _s = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     return Object(D.a)(this, n), t.call(this, e, 0, e.fields.map((function(e) {
-                        return tr.new(e.type, 0, 0, 0)
+                        return ir.new(e.type, 0, 0, 0)
                     })))
                 }
                 return Object(M.a)(n)
-            }(gs),
-            ws = function(e) {
+            }(Os),
+            js = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     var e;
                     return Object(D.a)(this, n), (e = t.apply(this, arguments)).dictionaries = new Map, e
                 }
                 return Object(M.a)(n, [{
                     key: "visit",
                     value: function(e, t) {
                         var n = this;
-                        return kn.isDictionary(t) ? this.visitDictionary(e, t) : (e.childData.forEach((function(e, r) {
+                        return _n.isDictionary(t) ? this.visitDictionary(e, t) : (e.childData.forEach((function(e, r) {
                             return n.visit(e, t.children[r].type)
                         })), this)
                     }
                 }, {
                     key: "visitDictionary",
                     value: function(e, t) {
                         var n = e.dictionary;
                         return n && n.length > 0 && this.dictionaries.set(t.id, n), this
                     }
                 }], [{
                     key: "collect",
                     value: function(e) {
-                        return (new n).visit(e.data, new $n(e.schema.fields)).dictionaries
+                        return (new n).visit(e.data, new Qn(e.schema.fields)).dictionaries
                     }
                 }]), n
-            }(on),
-            Os = Object(L.a)().mark(Ls),
-            _s = function(e, t, n) {
+            }(sn),
+            xs = Object(L.a)().mark(Ps),
+            Ts = function(e, t, n) {
                 Object(ae.a)(i, e);
                 var r = Object(oe.a)(i);
 
                 function i(e) {
                     var t;
                     return Object(D.a)(this, i), (t = r.call(this))._impl = e, t
                 }
@@ -15963,15 +15981,15 @@
                         return this._impl.reset(e), this._DOMStream = void 0, this._nodeStream = void 0, this
                     }
                 }, {
                     key: "open",
                     value: function(e) {
                         var t = this,
                             n = this._impl.open(e);
-                        return Oe(n) ? n.then((function() {
+                        return xe(n) ? n.then((function() {
                             return t
                         })) : this
                     }
                 }, {
                     key: "readRecordBatch",
                     value: function(e) {
                         return this._impl.isFile() ? this._impl.readRecordBatch(e) : null
@@ -15986,27 +16004,27 @@
                     value: function() {
                         return this._impl[Symbol.asyncIterator]()
                     }
                 }, {
                     key: "toDOMStream",
                     value: function() {
                         var e = this;
-                        return gt.toDOMStream(this.isSync() ? Object(mi.a)({}, Symbol.iterator, (function() {
+                        return Ot.toDOMStream(this.isSync() ? Object(wi.a)({}, Symbol.iterator, (function() {
                             return e
-                        })) : Object(mi.a)({}, Symbol.asyncIterator, (function() {
+                        })) : Object(wi.a)({}, Symbol.asyncIterator, (function() {
                             return e
                         })))
                     }
                 }, {
                     key: "toNodeStream",
                     value: function() {
                         var e = this;
-                        return gt.toNodeStream(this.isSync() ? Object(mi.a)({}, Symbol.iterator, (function() {
+                        return Ot.toNodeStream(this.isSync() ? Object(wi.a)({}, Symbol.iterator, (function() {
                             return e
-                        })) : Object(mi.a)({}, Symbol.asyncIterator, (function() {
+                        })) : Object(wi.a)({}, Symbol.asyncIterator, (function() {
                             return e
                         })), {
                             objectMode: !0
                         })
                     }
                 }], [{
                     key: "throughNode",
@@ -16017,55 +16035,55 @@
                     key: "throughDOM",
                     value: function(e, t) {
                         throw new Error('"throughDOM" not available in this environment')
                     }
                 }, {
                     key: "from",
                     value: function(e) {
-                        return e instanceof i ? e : xe(e) ? function(e) {
-                            return new js(new Ds(e))
-                        }(e) : Se(e) ? function(e) {
-                            return Us.apply(this, arguments)
-                        }(e) : Oe(e) ? Object(B.a)(Object(L.a)().mark((function t() {
+                        return e instanceof i ? e : Ie(e) ? function(e) {
+                            return new Ss(new Fs(e))
+                        }(e) : Ae(e) ? function(e) {
+                            return Vs.apply(this, arguments)
+                        }(e) : xe(e) ? Object(B.a)(Object(L.a)().mark((function t() {
                             return Object(L.a)().wrap((function(t) {
                                 for (;;) switch (t.prev = t.next) {
                                     case 0:
                                         return t.t0 = i, t.next = 3, e;
                                     case 3:
                                         return t.t1 = t.sent, t.next = 6, t.t0.from.call(t.t0, t.t1);
                                     case 6:
                                         return t.abrupt("return", t.sent);
                                     case 7:
                                     case "end":
                                         return t.stop()
                                 }
                             }), t)
-                        })))() : Ie(e) || Ee(e) || Ae(e) || je(e) ? function(e) {
-                            return Ps.apply(this, arguments)
-                        }(new Wa(e)) : function(e) {
-                            var t = e.peek(du + 7 & -8);
-                            return t && t.byteLength >= 4 ? hu(t) ? new Ts(new Cs(e.read())) : new js(new Es(e)) : new js(new Es(Object(L.a)().mark((function e() {
+                        })))() : Ce(e) || Be(e) || De(e) || Se(e) ? function(e) {
+                            return zs.apply(this, arguments)
+                        }(new $a(e)) : function(e) {
+                            var t = e.peek(vu + 7 & -8);
+                            return t && t.byteLength >= 4 ? yu(t) ? new Es(new Ms(e.read())) : new Ss(new Bs(e)) : new Ss(new Bs(Object(L.a)().mark((function e() {
                                 return Object(L.a)().wrap((function(e) {
                                     for (;;) switch (e.prev = e.next) {
                                         case 0:
                                         case "end":
                                             return e.stop()
                                     }
                                 }), e)
                             }))()))
-                        }(new Va(e))
+                        }(new Ha(e))
                     }
                 }, {
                     key: "readAll",
                     value: function(e) {
-                        return e instanceof i ? e.isSync() ? Ls(e) : Fs(e) : xe(e) || ArrayBuffer.isView(e) || _e(e) || Te(e) ? Ls(e) : Fs(e)
+                        return e instanceof i ? e.isSync() ? Ps(e) : Us(e) : Ie(e) || ArrayBuffer.isView(e) || Te(e) || Ee(e) ? Ps(e) : Us(e)
                     }
                 }]), i
             }(se, Symbol.iterator, Symbol.asyncIterator),
-            js = function(e, t, n) {
+            Ss = function(e, t, n) {
                 Object(ae.a)(i, e);
                 var r = Object(oe.a)(i);
 
                 function i(e) {
                     var t;
                     return Object(D.a)(this, i), (t = r.call(this, e))._impl = e, t
                 }
@@ -16087,16 +16105,16 @@
                                     case "end":
                                         return t.stop()
                                 }
                             }), t)
                         })))()
                     }
                 }]), i
-            }(_s, Symbol.iterator, Symbol.asyncIterator),
-            xs = function(e, t, n) {
+            }(Ts, Symbol.iterator, Symbol.asyncIterator),
+            Is = function(e, t, n) {
                 Object(ae.a)(i, e);
                 var r = Object(oe.a)(i);
 
                 function i(e) {
                     var t;
                     return Object(D.a)(this, i), (t = r.call(this, e))._impl = e, t
                 }
@@ -16107,36 +16125,36 @@
                     }
                 }, {
                     key: n,
                     value: function() {
                         return this._impl[Symbol.asyncIterator]()
                     }
                 }]), i
-            }(_s, Symbol.iterator, Symbol.asyncIterator),
-            Ts = function(e) {
+            }(Ts, Symbol.iterator, Symbol.asyncIterator),
+            Es = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
                     return Object(D.a)(this, n), (r = t.call(this, e))._impl = e, r
                 }
                 return Object(M.a)(n)
-            }(js),
-            Ss = function(e) {
+            }(Ss),
+            As = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
                     return Object(D.a)(this, n), (r = t.call(this, e))._impl = e, r
                 }
                 return Object(M.a)(n)
-            }(xs),
-            Is = function() {
+            }(Is),
+            Cs = function() {
                 function e() {
                     var t = arguments.length > 0 && void 0 !== arguments[0] ? arguments[0] : new Map;
                     Object(D.a)(this, e), this.closed = !1, this.autoDestroy = !0, this._dictionaryIndex = 0, this._recordBatchIndex = 0, this.dictionaries = t
                 }
                 return Object(M.a)(e, [{
                     key: "numDictionaries",
                     get: function() {
@@ -16171,45 +16189,45 @@
                     key: "reset",
                     value: function(e) {
                         return this._dictionaryIndex = 0, this._recordBatchIndex = 0, this.schema = e, this.dictionaries = new Map, this
                     }
                 }, {
                     key: "_loadRecordBatch",
                     value: function(e, t) {
-                        return new gs(this.schema, e.length, this._loadVectors(e, t, this.schema.fields))
+                        return new Os(this.schema, e.length, this._loadVectors(e, t, this.schema.fields))
                     }
                 }, {
                     key: "_loadDictionaryBatch",
                     value: function(e, t) {
                         var n = e.id,
                             r = e.isDelta,
                             i = e.data,
                             a = this.dictionaries,
                             o = this.schema,
                             u = a.get(n);
                         if (r || !u) {
                             var c = o.dictionaries.get(n);
-                            return u && r ? u.concat(Pt.new(this._loadVectors(i, t, [c])[0])) : Pt.new(this._loadVectors(i, t, [c])[0])
+                            return u && r ? u.concat(zt.new(this._loadVectors(i, t, [c])[0])) : zt.new(this._loadVectors(i, t, [c])[0])
                         }
                         return u
                     }
                 }, {
                     key: "_loadVectors",
                     value: function(e, t, n) {
-                        return new eo(t, e.nodes, e.buffers, this.dictionaries).visitMany(n)
+                        return new ro(t, e.nodes, e.buffers, this.dictionaries).visitMany(n)
                     }
                 }]), e
             }(),
-            Es = function(e, t) {
+            Bs = function(e, t) {
                 Object(ae.a)(r, e);
                 var n = Object(oe.a)(r);
 
                 function r(e, t) {
                     var i;
-                    return Object(D.a)(this, r), (i = n.call(this, t))._reader = xe(e) ? new uu(i._handle = e) : new au(i._handle = e), i
+                    return Object(D.a)(this, r), (i = n.call(this, t))._reader = Ie(e) ? new lu(i._handle = e) : new cu(i._handle = e), i
                 }
                 return Object(M.a)(r, [{
                     key: "isSync",
                     value: function() {
                         return !0
                     }
                 }, {
@@ -16226,15 +16244,15 @@
                     key: "cancel",
                     value: function() {
                         !this.closed && (this.closed = !0) && (this.reset()._reader.return(), this._reader = null, this.dictionaries = null)
                     }
                 }, {
                     key: "open",
                     value: function(e) {
-                        return this.closed || (this.autoDestroy = Ms(this, e), this.schema || (this.schema = this._reader.readSchema()) || this.cancel()), this
+                        return this.closed || (this.autoDestroy = Ns(this, e), this.schema || (this.schema = this._reader.readSchema()) || this.cancel()), this
                     }
                 }, {
                     key: "throw",
                     value: function(e) {
                         return !this.closed && this.autoDestroy && (this.closed = !0) ? this.reset()._reader.throw(e) : ue
                     }
                 }, {
@@ -16263,31 +16281,31 @@
                                     var i = e.header(),
                                         a = t.readMessageBody(e.bodyLength),
                                         o = this._loadDictionaryBatch(i, a);
                                     this.dictionaries.set(i.id, o)
                                 }
                             } return this.schema && 0 === this._recordBatchIndex ? (this._recordBatchIndex++, {
                             done: !1,
-                            value: new ks(this.schema)
+                            value: new _s(this.schema)
                         }) : this.return()
                     }
                 }, {
                     key: "_readNextMessageAndValidate",
                     value: function(e) {
                         return this._reader.readMessage(e)
                     }
                 }]), r
-            }(Is, Symbol.iterator),
-            As = function(e, t) {
+            }(Cs, Symbol.iterator),
+            Ds = function(e, t) {
                 Object(ae.a)(r, e);
                 var n = Object(oe.a)(r);
 
                 function r(e, t) {
                     var i;
-                    return Object(D.a)(this, r), (i = n.call(this, t))._reader = new ou(i._handle = e), i
+                    return Object(D.a)(this, r), (i = n.call(this, t))._reader = new su(i._handle = e), i
                 }
                 return Object(M.a)(r, [{
                     key: "isAsync",
                     value: function() {
                         return !0
                     }
                 }, {
@@ -16331,15 +16349,15 @@
                             return Object(L.a)().wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
                                     case 0:
                                         if (this.closed) {
                                             e.next = 10;
                                             break
                                         }
-                                        if (this.autoDestroy = Ms(this, t), e.t0 = this.schema, e.t0) {
+                                        if (this.autoDestroy = Ns(this, t), e.t0 = this.schema, e.t0) {
                                             e.next = 7;
                                             break
                                         }
                                         return e.next = 6, this._reader.readSchema();
                                     case 6:
                                         e.t0 = this.schema = e.sent;
                                     case 7:
@@ -16467,15 +16485,15 @@
                                     case 31:
                                         if (!this.schema || 0 !== this._recordBatchIndex) {
                                             e.next = 34;
                                             break
                                         }
                                         return this._recordBatchIndex++, e.abrupt("return", {
                                             done: !1,
-                                            value: new ks(this.schema)
+                                            value: new _s(this.schema)
                                         });
                                     case 34:
                                         return e.next = 36, this.return();
                                     case 36:
                                         return e.abrupt("return", e.sent);
                                     case 37:
                                     case "end":
@@ -16504,21 +16522,21 @@
                             }), e, this)
                         })));
                         return function(t) {
                             return e.apply(this, arguments)
                         }
                     }()
                 }]), r
-            }(Is, Symbol.asyncIterator),
-            Cs = function(e) {
+            }(Cs, Symbol.asyncIterator),
+            Ms = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e, r) {
-                    return Object(D.a)(this, n), t.call(this, e instanceof $a ? e : new $a(e), r)
+                    return Object(D.a)(this, n), t.call(this, e instanceof Qa ? e : new Qa(e), r)
                 }
                 return Object(M.a)(n, [{
                     key: "footer",
                     get: function() {
                         return this._footer
                     }
                 }, {
@@ -16553,76 +16571,76 @@
                                 }
                             } catch (i) {
                                 r.e(i)
                             } finally {
                                 r.f()
                             }
                         }
-                        return Ct(Object(At.a)(n.prototype), "open", this).call(this, e)
+                        return Mt(Object(Dt.a)(n.prototype), "open", this).call(this, e)
                     }
                 }, {
                     key: "readRecordBatch",
                     value: function(e) {
                         if (this.closed) return null;
                         this._footer || this.open();
                         var t = this._footer && this._footer.getRecordBatch(e);
                         if (t && this._handle.seek(t.offset)) {
-                            var n = this._reader.readMessage($t.RecordBatch);
+                            var n = this._reader.readMessage(Qt.RecordBatch);
                             if (n && n.isRecordBatch()) {
                                 var r = n.header(),
                                     i = this._reader.readMessageBody(n.bodyLength);
                                 return this._loadRecordBatch(r, i)
                             }
                         }
                         return null
                     }
                 }, {
                     key: "_readDictionaryBatch",
                     value: function(e) {
                         var t = this._footer && this._footer.getDictionaryBatch(e);
                         if (t && this._handle.seek(t.offset)) {
-                            var n = this._reader.readMessage($t.DictionaryBatch);
+                            var n = this._reader.readMessage(Qt.DictionaryBatch);
                             if (n && n.isDictionaryBatch()) {
                                 var r = n.header(),
                                     i = this._reader.readMessageBody(n.bodyLength),
                                     a = this._loadDictionaryBatch(r, i);
                                 this.dictionaries.set(r.id, a)
                             }
                         }
                     }
                 }, {
                     key: "_readFooter",
                     value: function() {
                         var e = this._handle,
-                            t = e.size - pu,
+                            t = e.size - bu,
                             n = e.readInt32(t),
                             r = e.readAt(t - n, n);
-                        return Pa.decode(r)
+                        return za.decode(r)
                     }
                 }, {
                     key: "_readNextMessageAndValidate",
                     value: function(e) {
                         if (this._footer || this.open(), this._footer && this._recordBatchIndex < this.numRecordBatches) {
                             var t = this._footer && this._footer.getRecordBatch(this._recordBatchIndex);
                             if (t && this._handle.seek(t.offset)) return this._reader.readMessage(e)
                         }
                         return null
                     }
                 }]), n
-            }(Es),
-            Bs = function(e) {
+            }(Bs),
+            Ls = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     Object(D.a)(this, n);
                     for (var r = arguments.length, i = new Array(r > 1 ? r - 1 : 0), a = 1; a < r; a++) i[a - 1] = arguments[a];
                     var o = "number" !== typeof i[0] ? i.shift() : void 0,
                         u = i[0] instanceof Map ? i.shift() : void 0;
-                    return t.call(this, e instanceof Ka ? e : new Ka(e, o), u)
+                    return t.call(this, e instanceof Ga ? e : new Ga(e, o), u)
                 }
                 return Object(M.a)(n, [{
                     key: "footer",
                     get: function() {
                         return this._footer
                     }
                 }, {
@@ -16677,15 +16695,15 @@
                                         e.next = 20;
                                         break;
                                     case 17:
                                         e.prev = 17, e.t1 = e.catch(5), r.e(e.t1);
                                     case 20:
                                         return e.prev = 20, r.f(), e.finish(20);
                                     case 23:
-                                        return e.next = 25, Ct(Object(At.a)(n.prototype), "open", this).call(this, t);
+                                        return e.next = 25, Mt(Object(Dt.a)(n.prototype), "open", this).call(this, t);
                                     case 25:
                                         return e.abrupt("return", e.sent);
                                     case 26:
                                     case "end":
                                         return e.stop()
                                 }
                             }), e, this, [
@@ -16724,15 +16742,15 @@
                                     case 10:
                                         e.t0 = e.sent;
                                     case 11:
                                         if (!e.t0) {
                                             e.next = 22;
                                             break
                                         }
-                                        return e.next = 14, this._reader.readMessage($t.RecordBatch);
+                                        return e.next = 14, this._reader.readMessage(Qt.RecordBatch);
                                     case 14:
                                         if (!(r = e.sent) || !r.isRecordBatch()) {
                                             e.next = 22;
                                             break
                                         }
                                         return i = r.header(), e.next = 19, this._reader.readMessageBody(r.bodyLength);
                                     case 19:
@@ -16765,15 +16783,15 @@
                                     case 5:
                                         e.t0 = e.sent;
                                     case 6:
                                         if (!e.t0) {
                                             e.next = 17;
                                             break
                                         }
-                                        return e.next = 9, this._reader.readMessage($t.DictionaryBatch);
+                                        return e.next = 9, this._reader.readMessage(Qt.DictionaryBatch);
                                     case 9:
                                         if (!(r = e.sent) || !r.isDictionaryBatch()) {
                                             e.next = 17;
                                             break
                                         }
                                         return i = r.header(), e.next = 14, this._reader.readMessageBody(r.bodyLength);
                                     case 14:
@@ -16798,19 +16816,19 @@
                                     case 0:
                                         if (t = this._handle, e.t0 = t._pending, !e.t0) {
                                             e.next = 5;
                                             break
                                         }
                                         return e.next = 5, t._pending;
                                     case 5:
-                                        return n = t.size - pu, e.next = 8, t.readInt32(n);
+                                        return n = t.size - bu, e.next = 8, t.readInt32(n);
                                     case 8:
                                         return r = e.sent, e.next = 11, t.readAt(n - r, r);
                                     case 11:
-                                        return i = e.sent, e.abrupt("return", Pa.decode(i));
+                                        return i = e.sent, e.abrupt("return", za.decode(i));
                                     case 13:
                                     case "end":
                                         return e.stop()
                                 }
                             }), e, this)
                         })));
                         return function() {
@@ -16859,40 +16877,40 @@
                             }), e, this)
                         })));
                         return function(t) {
                             return e.apply(this, arguments)
                         }
                     }()
                 }]), n
-            }(As),
-            Ds = function(e) {
+            }(Ds),
+            Fs = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e, r) {
                     return Object(D.a)(this, n), t.call(this, e, r)
                 }
                 return Object(M.a)(n, [{
                     key: "_loadVectors",
                     value: function(e, t, n) {
-                        return new to(t, e.nodes, e.buffers, this.dictionaries).visitMany(n)
+                        return new io(t, e.nodes, e.buffers, this.dictionaries).visitMany(n)
                     }
                 }]), n
-            }(Es);
+            }(Bs);
 
-        function Ms(e, t) {
+        function Ns(e, t) {
             return t && "boolean" === typeof t.autoDestroy ? t.autoDestroy : e.autoDestroy
         }
 
-        function Ls(e) {
+        function Ps(e) {
             var t;
             return Object(L.a)().wrap((function(n) {
                 for (;;) switch (n.prev = n.next) {
                     case 0:
-                        if (t = _s.from(e), n.prev = 1, t.open({
+                        if (t = Ts.from(e), n.prev = 1, t.open({
                                 autoDestroy: !1
                             }).closed) {
                             n.next = 6;
                             break
                         }
                     case 3:
                         return n.next = 5, t;
@@ -16903,30 +16921,30 @@
                         }
                     case 6:
                         return n.prev = 6, t.cancel(), n.finish(6);
                     case 9:
                     case "end":
                         return n.stop()
                 }
-            }), Os, null, [
+            }), xs, null, [
                 [1, , 6, 9]
             ])
         }
 
-        function Fs(e) {
-            return Ns.apply(this, arguments)
+        function Us(e) {
+            return Rs.apply(this, arguments)
         }
 
-        function Ns() {
-            return (Ns = R(Object(L.a)().mark((function e(t) {
+        function Rs() {
+            return (Rs = R(Object(L.a)().mark((function e(t) {
                 var n;
                 return Object(L.a)().wrap((function(e) {
                     for (;;) switch (e.prev = e.next) {
                         case 0:
-                            return e.next = 2, P(_s.from(t));
+                            return e.next = 2, P(Ts.from(t));
                         case 2:
                             return n = e.sent, e.prev = 3, e.next = 6, P(n.open({
                                 autoDestroy: !1
                             }));
                         case 6:
                             if (e.sent.closed) {
                                 e.next = 12;
@@ -16951,41 +16969,41 @@
                     }
                 }), e, null, [
                     [3, , 12, 16]
                 ])
             })))).apply(this, arguments)
         }
 
-        function Ps() {
-            return (Ps = Object(B.a)(Object(L.a)().mark((function e(t) {
+        function zs() {
+            return (zs = Object(B.a)(Object(L.a)().mark((function e(t) {
                 var n;
                 return Object(L.a)().wrap((function(e) {
                     for (;;) switch (e.prev = e.next) {
                         case 0:
-                            return e.next = 2, t.peek(du + 7 & -8);
+                            return e.next = 2, t.peek(vu + 7 & -8);
                         case 2:
                             if (!((n = e.sent) && n.byteLength >= 4)) {
                                 e.next = 18;
                                 break
                             }
-                            if (hu(n)) {
+                            if (yu(n)) {
                                 e.next = 8;
                                 break
                             }
-                            e.t1 = new xs(new As(t)), e.next = 15;
+                            e.t1 = new Is(new Ds(t)), e.next = 15;
                             break;
                         case 8:
-                            return e.t2 = Ts, e.t3 = Cs, e.next = 12, t.read();
+                            return e.t2 = Es, e.t3 = Ms, e.next = 12, t.read();
                         case 12:
                             e.t4 = e.sent, e.t5 = new e.t3(e.t4), e.t1 = new e.t2(e.t5);
                         case 15:
                             e.t0 = e.t1, e.next = 19;
                             break;
                         case 18:
-                            e.t0 = new xs(new As(R(Object(L.a)().mark((function e() {
+                            e.t0 = new Is(new Ds(R(Object(L.a)().mark((function e() {
                                 return Object(L.a)().wrap((function(e) {
                                     for (;;) switch (e.prev = e.next) {
                                         case 0:
                                         case "end":
                                             return e.stop()
                                     }
                                 }), e)
@@ -16996,71 +17014,71 @@
                         case "end":
                             return e.stop()
                     }
                 }), e)
             })))).apply(this, arguments)
         }
 
-        function Us() {
-            return (Us = Object(B.a)(Object(L.a)().mark((function e(t) {
+        function Vs() {
+            return (Vs = Object(B.a)(Object(L.a)().mark((function e(t) {
                 var n, r, i;
                 return Object(L.a)().wrap((function(e) {
                     for (;;) switch (e.prev = e.next) {
                         case 0:
                             return e.next = 2, t.stat();
                         case 2:
-                            if (n = e.sent, r = n.size, i = new Ka(t, r), !(r >= yu)) {
+                            if (n = e.sent, r = n.size, i = new Ga(t, r), !(r >= mu)) {
                                 e.next = 12;
                                 break
                             }
-                            return e.t0 = hu, e.next = 9, i.readAt(0, du + 7 & -8);
+                            return e.t0 = yu, e.next = 9, i.readAt(0, vu + 7 & -8);
                         case 9:
                             if (e.t1 = e.sent, !(0, e.t0)(e.t1)) {
                                 e.next = 12;
                                 break
                             }
-                            return e.abrupt("return", new Ss(new Bs(i)));
+                            return e.abrupt("return", new As(new Ls(i)));
                         case 12:
-                            return e.abrupt("return", new xs(new As(i)));
+                            return e.abrupt("return", new Is(new Ds(i)));
                         case 13:
                         case "end":
                             return e.stop()
                     }
                 }), e)
             })))).apply(this, arguments)
         }
-        var Rs = ["readableStrategy", "writableStrategy", "queueingStrategy"];
-        var zs = function() {
+        var Ws = ["readableStrategy", "writableStrategy", "queueingStrategy"];
+        var Ys = function() {
                 function e(t) {
                     var n, r, i = this;
                     Object(D.a)(this, e), this._numChunks = 0, this._finished = !1, this._bufferedSize = 0;
                     var a = t.readableStrategy,
                         o = t.writableStrategy,
                         u = t.queueingStrategy,
                         c = void 0 === u ? "count" : u,
-                        s = Bu(t, Rs);
-                    this._controller = null, this._builder = fr.new(s), this._getSize = "bytes" !== c ? Vs : Ws;
-                    var l = Object(Et.a)({}, a).highWaterMark,
+                        s = Lu(t, Ws);
+                    this._controller = null, this._builder = pr.new(s), this._getSize = "bytes" !== c ? Hs : $s;
+                    var l = Object(Bt.a)({}, a).highWaterMark,
                         f = void 0 === l ? "bytes" === c ? Math.pow(2, 14) : 1e3 : l,
-                        h = Object(Et.a)({}, o).highWaterMark,
+                        h = Object(Bt.a)({}, o).highWaterMark,
                         d = void 0 === h ? "bytes" === c ? Math.pow(2, 14) : 1e3 : h;
-                    this.readable = new ReadableStream((n = {}, Object(mi.a)(n, "cancel", (function() {
+                    this.readable = new ReadableStream((n = {}, Object(wi.a)(n, "cancel", (function() {
                         i._builder.clear()
-                    })), Object(mi.a)(n, "pull", (function(e) {
+                    })), Object(wi.a)(n, "pull", (function(e) {
                         i._maybeFlush(i._builder, i._controller = e)
-                    })), Object(mi.a)(n, "start", (function(e) {
+                    })), Object(wi.a)(n, "start", (function(e) {
                         i._maybeFlush(i._builder, i._controller = e)
                     })), n), {
                         highWaterMark: f,
-                        size: "bytes" !== c ? Vs : Ws
-                    }), this.writable = new WritableStream((r = {}, Object(mi.a)(r, "abort", (function() {
+                        size: "bytes" !== c ? Hs : $s
+                    }), this.writable = new WritableStream((r = {}, Object(wi.a)(r, "abort", (function() {
                         i._builder.clear()
-                    })), Object(mi.a)(r, "write", (function() {
+                    })), Object(wi.a)(r, "write", (function() {
                         i._maybeFlush(i._builder, i._controller)
-                    })), Object(mi.a)(r, "close", (function() {
+                    })), Object(wi.a)(r, "close", (function() {
                         i._maybeFlush(i._builder.finish(), i._controller)
                     })), r), {
                         highWaterMark: d,
                         size: function(e) {
                             return i._writeValueAndReturnChunkSize(e)
                         }
                     })
@@ -17079,67 +17097,67 @@
                 }, {
                     key: "_enqueue",
                     value: function(e, t) {
                         this._bufferedSize = 0, this._controller = null, null === t ? e.close() : e.enqueue(t)
                     }
                 }]), e
             }(),
-            Vs = function(e) {
+            Hs = function(e) {
                 return e.length
             },
-            Ws = function(e) {
+            $s = function(e) {
                 return e.byteLength
             };
-        var Ys = function() {
+        var Ks = function() {
                 function e() {
                     Object(D.a)(this, e)
                 }
                 return Object(M.a)(e, [{
                     key: "eq",
                     value: function(t) {
-                        return t instanceof e || (t = new Hs(t)), new Js(this, t)
+                        return t instanceof e || (t = new qs(t)), new tl(this, t)
                     }
                 }, {
                     key: "le",
                     value: function(t) {
-                        return t instanceof e || (t = new Hs(t)), new Zs(this, t)
+                        return t instanceof e || (t = new qs(t)), new nl(this, t)
                     }
                 }, {
                     key: "ge",
                     value: function(t) {
-                        return t instanceof e || (t = new Hs(t)), new el(this, t)
+                        return t instanceof e || (t = new qs(t)), new rl(this, t)
                     }
                 }, {
                     key: "lt",
                     value: function(e) {
-                        return new tl(this.ge(e))
+                        return new il(this.ge(e))
                     }
                 }, {
                     key: "gt",
                     value: function(e) {
-                        return new tl(this.le(e))
+                        return new il(this.le(e))
                     }
                 }, {
                     key: "ne",
                     value: function(e) {
-                        return new tl(this.eq(e))
+                        return new il(this.eq(e))
                     }
                 }]), e
             }(),
-            Hs = function(e) {
+            qs = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
                     return Object(D.a)(this, n), (r = t.call(this)).v = e, r
                 }
                 return Object(M.a)(n)
-            }(Ys),
-            $s = function(e) {
+            }(Ks),
+            Qs = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
                     return Object(D.a)(this, n), (r = t.call(this)).name = e, r
                 }
@@ -17156,115 +17174,115 @@
                         }
                         var r = this.vector = e.getChildAt(this.colidx);
                         return function(e) {
                             return r.get(e)
                         }
                     }
                 }]), n
-            }(Ys),
-            Ks = function() {
+            }(Ks),
+            Gs = function() {
                 function e() {
                     Object(D.a)(this, e)
                 }
                 return Object(M.a)(e, [{
                     key: "and",
                     value: function() {
                         for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++) t[n] = arguments[n];
-                        return Br(Gs, [this].concat(t))
+                        return Lr(Zs, [this].concat(t))
                     }
                 }, {
                     key: "or",
                     value: function() {
                         for (var e = arguments.length, t = new Array(e), n = 0; n < e; n++) t[n] = arguments[n];
-                        return Br(Xs, [this].concat(t))
+                        return Lr(el, [this].concat(t))
                     }
                 }, {
                     key: "not",
                     value: function() {
-                        return new tl(this)
+                        return new il(this)
                     }
                 }]), e
             }(),
-            qs = function(e) {
+            Xs = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e, r) {
                     var i;
                     return Object(D.a)(this, n), (i = t.call(this)).left = e, i.right = r, i
                 }
                 return Object(M.a)(n, [{
                     key: "bind",
                     value: function(e) {
-                        return this.left instanceof Hs ? this.right instanceof Hs ? this._bindLitLit(e, this.left, this.right) : this._bindLitCol(e, this.left, this.right) : this.right instanceof Hs ? this._bindColLit(e, this.left, this.right) : this._bindColCol(e, this.left, this.right)
+                        return this.left instanceof qs ? this.right instanceof qs ? this._bindLitLit(e, this.left, this.right) : this._bindLitCol(e, this.left, this.right) : this.right instanceof qs ? this._bindColLit(e, this.left, this.right) : this._bindColCol(e, this.left, this.right)
                     }
                 }]), n
-            }(Ks),
-            Qs = function(e) {
+            }(Gs),
+            Js = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     var e;
                     Object(D.a)(this, n), e = t.call(this);
                     for (var r = arguments.length, i = new Array(r), a = 0; a < r; a++) i[a] = arguments[a];
                     return e.children = i, e
                 }
                 return Object(M.a)(n)
-            }(Ks);
-        Qs.prototype.children = Object.freeze([]);
-        var Gs = function(e) {
+            }(Gs);
+        Js.prototype.children = Object.freeze([]);
+        var Zs = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     for (var e = arguments.length, r = new Array(e), i = 0; i < e; i++) r[i] = arguments[i];
                     return Object(D.a)(this, n), r = r.reduce((function(e, t) {
                         return e.concat(t instanceof n ? t.children : t)
-                    }), []), t.call.apply(t, [this].concat(Object(an.a)(r)))
+                    }), []), t.call.apply(t, [this].concat(Object(cn.a)(r)))
                 }
                 return Object(M.a)(n, [{
                     key: "bind",
                     value: function(e) {
                         var t = this.children.map((function(t) {
                             return t.bind(e)
                         }));
                         return function(e, n) {
                             return t.every((function(t) {
                                 return t(e, n)
                             }))
                         }
                     }
                 }]), n
-            }(Qs),
-            Xs = function(e) {
+            }(Js),
+            el = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     for (var e = arguments.length, r = new Array(e), i = 0; i < e; i++) r[i] = arguments[i];
                     return Object(D.a)(this, n), r = r.reduce((function(e, t) {
                         return e.concat(t instanceof n ? t.children : t)
-                    }), []), t.call.apply(t, [this].concat(Object(an.a)(r)))
+                    }), []), t.call.apply(t, [this].concat(Object(cn.a)(r)))
                 }
                 return Object(M.a)(n, [{
                     key: "bind",
                     value: function(e) {
                         var t = this.children.map((function(t) {
                             return t.bind(e)
                         }));
                         return function(e, n) {
                             return t.some((function(t) {
                                 return t(e, n)
                             }))
                         }
                     }
                 }]), n
-            }(Qs),
-            Js = function(e) {
+            }(Js),
+            tl = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
@@ -17284,15 +17302,15 @@
                             return r(e, t) == i(e, t)
                         }
                     }
                 }, {
                     key: "_bindColLit",
                     value: function(e, t, n) {
                         var r = t.bind(e);
-                        if (t.vector instanceof Ru) {
+                        if (t.vector instanceof Wu) {
                             var i, a = t.vector;
                             return a.dictionary !== this.lastDictionary ? (i = a.reverseLookup(n.v), this.lastDictionary = a.dictionary, this.lastKey = i) : i = this.lastKey, -1 === i ? function() {
                                 return !1
                             } : function(e) {
                                 return a.getKey(e) === i
                             }
                         }
@@ -17302,16 +17320,16 @@
                     }
                 }, {
                     key: "_bindLitCol",
                     value: function(e, t, n) {
                         return this._bindColLit(e, n, t)
                     }
                 }]), n
-            }(qs),
-            Zs = function(e) {
+            }(Xs),
+            nl = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
@@ -17344,16 +17362,16 @@
                     value: function(e, t, n) {
                         var r = n.bind(e);
                         return function(e, n) {
                             return t.v <= r(e, n)
                         }
                     }
                 }]), n
-            }(qs),
-            el = function(e) {
+            }(Xs),
+            rl = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
@@ -17386,16 +17404,16 @@
                     value: function(e, t, n) {
                         var r = n.bind(e);
                         return function(e, n) {
                             return t.v >= r(e, n)
                         }
                     }
                 }]), n
-            }(qs),
-            tl = function(e) {
+            }(Xs),
+            il = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e) {
                     var r;
                     return Object(D.a)(this, n), (r = t.call(this)).child = e, r
                 }
@@ -17404,35 +17422,35 @@
                     value: function(e) {
                         var t = this.child.bind(e);
                         return function(e, n) {
                             return !t(e, n)
                         }
                     }
                 }]), n
-            }(Ks);
-        ms.prototype.countBy = function(e) {
-            return new nl(this.chunks).countBy(e)
-        }, ms.prototype.scan = function(e, t) {
-            return new nl(this.chunks).scan(e, t)
-        }, ms.prototype.scanReverse = function(e, t) {
-            return new nl(this.chunks).scanReverse(e, t)
-        }, ms.prototype.filter = function(e) {
-            return new nl(this.chunks).filter(e)
+            }(Gs);
+        ws.prototype.countBy = function(e) {
+            return new al(this.chunks).countBy(e)
+        }, ws.prototype.scan = function(e, t) {
+            return new al(this.chunks).scan(e, t)
+        }, ws.prototype.scanReverse = function(e, t) {
+            return new al(this.chunks).scanReverse(e, t)
+        }, ws.prototype.filter = function(e) {
+            return new al(this.chunks).filter(e)
         };
-        var nl = function(e) {
+        var al = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n() {
                     return Object(D.a)(this, n), t.apply(this, arguments)
                 }
                 return Object(M.a)(n, [{
                     key: "filter",
                     value: function(e) {
-                        return new il(this.chunks, e)
+                        return new ul(this.chunks, e)
                     }
                 }, {
                     key: "scan",
                     value: function(e, t) {
                         for (var n = this.chunks, r = n.length, i = -1; ++i < r;) {
                             var a = n[i];
                             t && t(a);
@@ -17449,48 +17467,48 @@
                         }
                     }
                 }, {
                     key: "countBy",
                     value: function(e) {
                         var t = this.chunks,
                             n = t.length,
-                            r = "string" === typeof e ? new $s(e) : e;
+                            r = "string" === typeof e ? new Qs(e) : e;
                         r.bind(t[n - 1]);
                         var i = r.vector;
-                        if (!kn.isDictionary(i.type)) throw new Error("countBy currently only supports dictionary-encoded columns");
+                        if (!_n.isDictionary(i.type)) throw new Error("countBy currently only supports dictionary-encoded columns");
                         for (var a = Math.ceil(Math.log(i.length) / Math.log(256)), o = new(4 == a ? Uint32Array : a >= 2 ? Uint16Array : Uint8Array)(i.dictionary.length), u = -1; ++u < n;) {
                             var c = t[u];
                             r.bind(c);
                             for (var s = r.vector.indices, l = -1, f = c.length; ++l < f;) {
                                 var h = s.get(l);
                                 null !== h && o[h]++
                             }
                         }
-                        return new rl(i.dictionary, Zu.from(o))
+                        return new ol(i.dictionary, nc.from(o))
                     }
                 }]), n
-            }(ms),
-            rl = function(e) {
+            }(ws),
+            ol = function(e) {
                 Object(ae.a)(n, e);
                 var t = Object(oe.a)(n);
 
                 function n(e, r) {
                     Object(D.a)(this, n);
-                    var i = new Ji([new Zi("values", e.type), new Zi("counts", r.type)]);
-                    return t.call(this, new gs(i, r.length, [e, r]))
+                    var i = new ta([new na("values", e.type), new na("counts", r.type)]);
+                    return t.call(this, new Os(i, r.length, [e, r]))
                 }
                 return Object(M.a)(n, [{
                     key: "toJSON",
                     value: function() {
                         for (var e = this.getColumnAt(0), t = this.getColumnAt(1), n = {}, r = -1; ++r < this.length;) n[e.get(r)] = t.get(r);
                         return n
                     }
                 }]), n
-            }(ms),
-            il = function(e, t) {
+            }(ws),
+            ul = function(e, t) {
                 Object(ae.a)(r, e);
                 var n = Object(oe.a)(r);
 
                 function r(e, t) {
                     var i;
                     return Object(D.a)(this, r), (i = n.call(this, e))._predicate = t, i
                 }
@@ -17555,38 +17573,38 @@
                         return new r(this._chunks, this._predicate.and(e))
                     }
                 }, {
                     key: "countBy",
                     value: function(e) {
                         var t = this._chunks,
                             n = t.length,
-                            r = "string" === typeof e ? new $s(e) : e;
+                            r = "string" === typeof e ? new Qs(e) : e;
                         r.bind(t[n - 1]);
                         var i = r.vector;
-                        if (!kn.isDictionary(i.type)) throw new Error("countBy currently only supports dictionary-encoded columns");
+                        if (!_n.isDictionary(i.type)) throw new Error("countBy currently only supports dictionary-encoded columns");
                         for (var a = Math.ceil(Math.log(i.length) / Math.log(256)), o = new(4 == a ? Uint32Array : a >= 2 ? Uint16Array : Uint8Array)(i.dictionary.length), u = -1; ++u < n;) {
                             var c = t[u],
                                 s = this._predicate.bind(c);
                             r.bind(c);
                             for (var l = r.vector.indices, f = -1, h = c.length; ++f < h;) {
                                 var d = l.get(f);
                                 null !== d && s(f, c) && o[d]++
                             }
                         }
-                        return new rl(i.dictionary, Zu.from(o))
+                        return new ol(i.dictionary, nc.from(o))
                     }
                 }]), r
-            }(nl, Symbol.iterator);
-        Object(Et.a)(Object(Et.a)(Object(Et.a)(Object(Et.a)(Object(Et.a)(Object(Et.a)({}, o), c), i), a), r), u);
-        gt.toDOMStream = function(e, t) {
-            if (je(e)) return function(e, t) {
+            }(al, Symbol.iterator);
+        Object(Bt.a)(Object(Bt.a)(Object(Bt.a)(Object(Bt.a)(Object(Bt.a)(Object(Bt.a)({}, o), c), i), a), r), u);
+        Ot.toDOMStream = function(e, t) {
+            if (Se(e)) return function(e, t) {
                 var n = null,
                     r = t && "bytes" === t.type || !1,
                     i = t && t.highWaterMark || Math.pow(2, 24);
-                return new ReadableStream(Object(Et.a)(Object(Et.a)({}, t), {}, {
+                return new ReadableStream(Object(Bt.a)(Object(Bt.a)({}, t), {}, {
                     start: function(t) {
                         return Object(B.a)(Object(L.a)().mark((function r() {
                             return Object(L.a)().wrap((function(r) {
                                 for (;;) switch (r.prev = r.next) {
                                     case 0:
                                         return r.next = 2, a(t, n || (n = e[Symbol.asyncIterator]()));
                                     case 2:
@@ -17651,15 +17669,15 @@
                                     case 14:
                                     case "end":
                                         return e.stop()
                                 }
                             }), e)
                         })))()
                     }
-                }), Object(Et.a)({
+                }), Object(Bt.a)({
                     highWaterMark: r ? i : void 0
                 }, t));
 
                 function a(e, t) {
                     return o.apply(this, arguments)
                 }
 
@@ -17673,15 +17691,15 @@
                                 case 2:
                                     return e.next = 4, n.next(r ? o : null);
                                 case 4:
                                     if ((a = e.sent).done) {
                                         e.next = 11;
                                         break
                                     }
-                                    if (ArrayBuffer.isView(a.value) && (i = ze(a.value)) && (null != o && r && (o = o - i.byteLength + 1), a.value = i), t.enqueue(a.value), !(null != o && --o <= 0)) {
+                                    if (ArrayBuffer.isView(a.value) && (i = Ye(a.value)) && (null != o && r && (o = o - i.byteLength + 1), a.value = i), t.enqueue(a.value), !(null != o && --o <= 0)) {
                                         e.next = 9;
                                         break
                                     }
                                     return e.abrupt("return");
                                 case 9:
                                     e.next = 2;
                                     break;
@@ -17691,43 +17709,43 @@
                                 case "end":
                                     return e.stop()
                             }
                         }), e)
                     }))), o.apply(this, arguments)
                 }
             }(e, t);
-            if (_e(e)) return function(e, t) {
+            if (Te(e)) return function(e, t) {
                 var n = null,
                     r = t && "bytes" === t.type || !1,
                     i = t && t.highWaterMark || Math.pow(2, 24);
-                return new ReadableStream(Object(Et.a)(Object(Et.a)({}, t), {}, {
+                return new ReadableStream(Object(Bt.a)(Object(Bt.a)({}, t), {}, {
                     start: function(t) {
                         a(t, n || (n = e[Symbol.iterator]()))
                     },
                     pull: function(e) {
                         n ? a(e, n) : e.close()
                     },
                     cancel: function() {
                         n && n.return && n.return(), n = null
                     }
-                }), Object(Et.a)({
+                }), Object(Bt.a)({
                     highWaterMark: r ? i : void 0
                 }, t));
 
                 function a(e, t) {
                     for (var n, i = null, a = e.desiredSize || null; !(i = t.next(r ? a : null)).done;)
-                        if (ArrayBuffer.isView(i.value) && (n = ze(i.value)) && (null != a && r && (a = a - n.byteLength + 1), i.value = n), e.enqueue(i.value), null != a && --a <= 0) return;
+                        if (ArrayBuffer.isView(i.value) && (n = Ye(i.value)) && (null != a && r && (a = a - n.byteLength + 1), i.value = n), e.enqueue(i.value), null != a && --a <= 0) return;
                     e.close()
                 }
             }(e, t);
             throw new Error("toDOMStream() must be called with an Iterable or AsyncIterable")
-        }, fr.throughDOM = function(e) {
-            return new zs(e)
-        }, _s.throughDOM = function(e, t) {
-            var n = new za,
+        }, pr.throughDOM = function(e) {
+            return new Ys(e)
+        }, Ts.throughDOM = function(e, t) {
+            var n = new Ya,
                 r = null,
                 i = new ReadableStream({
                     cancel: function() {
                         return Object(B.a)(Object(L.a)().mark((function e() {
                             return Object(L.a)().wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
                                     case 0:
@@ -17780,30 +17798,30 @@
                                         return t.stop()
                                 }
                             }), t)
                         })))()
                     }
                 });
             return {
-                writable: new WritableStream(n, Object(Et.a)({
+                writable: new WritableStream(n, Object(Bt.a)({
                     highWaterMark: Math.pow(2, 14)
                 }, e)),
                 readable: i
             };
 
             function a() {
                 return o.apply(this, arguments)
             }
 
             function o() {
                 return (o = Object(B.a)(Object(L.a)().mark((function e() {
                     return Object(L.a)().wrap((function(e) {
                         for (;;) switch (e.prev = e.next) {
                             case 0:
-                                return e.next = 2, _s.from(n);
+                                return e.next = 2, Ts.from(n);
                             case 2:
                                 return e.next = 4, e.sent.open(t);
                             case 4:
                                 return e.abrupt("return", e.sent);
                             case 5:
                             case "end":
                                 return e.stop()
@@ -17843,17 +17861,17 @@
                             case 11:
                             case "end":
                                 return e.stop()
                         }
                     }), e)
                 }))), c.apply(this, arguments)
             }
-        }, Ou.throughDOM = function(e, t) {
+        }, xu.throughDOM = function(e, t) {
             var n = new this(e),
-                r = new Wa(n),
+                r = new $a(n),
                 i = new ReadableStream({
                     type: "bytes",
                     cancel: function() {
                         return Object(B.a)(Object(L.a)().mark((function e() {
                             return Object(L.a)().wrap((function(e) {
                                 for (;;) switch (e.prev = e.next) {
                                     case 0:
@@ -17887,15 +17905,15 @@
                                     case 2:
                                     case "end":
                                         return t.stop()
                                 }
                             }), t)
                         })))()
                     }
-                }, Object(Et.a)({
+                }, Object(Bt.a)({
                     highWaterMark: Math.pow(2, 14)
                 }, t));
             return {
                 writable: new WritableStream(n, e),
                 readable: i
             };
 
@@ -17931,15 +17949,15 @@
                             case "end":
                                 return e.stop()
                         }
                     }), e)
                 })))).apply(this, arguments)
             }
         };
-        var al, ol = function() {
+        var cl, sl = function() {
                 function e(e, t, n, r) {
                     var i = this;
                     this.getCell = function(e, t) {
                         var n = e < i.headerRows && t < i.headerColumns,
                             r = e >= i.headerRows && t < i.headerColumns,
                             a = e < i.headerRows && t >= i.headerColumns;
                         if (n) {
@@ -17970,18 +17988,18 @@
                             type: "data",
                             id: "T_" + i.uuid + "row" + u + "_col" + c,
                             classNames: o.join(" "),
                             content: s
                         }
                     }, this.getContent = function(e, t, n) {
                         var r = e.getColumnAt(n);
-                        return null === r ? "" : i.getColumnTypeId(e, n) === Ut.Timestamp ? i.nanosToDate(r.get(t)) : r.get(t)
-                    }, this.dataTable = ms.from(e), this.indexTable = ms.from(t), this.columnsTable = ms.from(n), this.styler = r ? {
+                        return null === r ? "" : i.getColumnTypeId(e, n) === Vt.Timestamp ? i.nanosToDate(r.get(t)) : r.get(t)
+                    }, this.dataTable = ws.from(e), this.indexTable = ws.from(t), this.columnsTable = ws.from(n), this.styler = r ? {
                         caption: r.caption,
-                        displayValuesTable: ms.from(r.displayValues),
+                        displayValuesTable: ws.from(r.displayValues),
                         styles: r.styles,
                         uuid: r.uuid
                     } : void 0
                 }
                 return Object.defineProperty(e.prototype, "rows", {
                     get: function() {
                         return this.indexTable.length + this.columnsTable.numCols
@@ -18062,56 +18080,56 @@
                     }
                 }, e.prototype.getColumnTypeId = function(e, t) {
                     return e.schema.fields[t].type.typeId
                 }, e.prototype.nanosToDate = function(e) {
                     return new Date(e / 1e6)
                 }, e
             }(),
-            ul = function() {
-                return ul = Object.assign || function(e) {
+            ll = function() {
+                return ll = Object.assign || function(e) {
                     for (var t, n = 1, r = arguments.length; n < r; n++)
                         for (var i in t = arguments[n]) Object.prototype.hasOwnProperty.call(t, i) && (e[i] = t[i]);
                     return e
-                }, ul.apply(this, arguments)
+                }, ll.apply(this, arguments)
             };
         ! function(e) {
             e.COMPONENT_READY = "streamlit:componentReady", e.SET_COMPONENT_VALUE = "streamlit:setComponentValue", e.SET_FRAME_HEIGHT = "streamlit:setFrameHeight"
-        }(al || (al = {}));
-        var cl = function() {
+        }(cl || (cl = {}));
+        var fl = function() {
                 function e() {}
                 return e.API_VERSION = 1, e.RENDER_EVENT = "streamlit:render", e.events = new E, e.registeredMessageListener = !1, e.setComponentReady = function() {
-                    e.registeredMessageListener || (window.addEventListener("message", e.onMessageEvent), e.registeredMessageListener = !0), e.sendBackMsg(al.COMPONENT_READY, {
+                    e.registeredMessageListener || (window.addEventListener("message", e.onMessageEvent), e.registeredMessageListener = !0), e.sendBackMsg(cl.COMPONENT_READY, {
                         apiVersion: e.API_VERSION
                     })
                 }, e.setFrameHeight = function(t) {
-                    void 0 === t && (t = document.body.scrollHeight), t !== e.lastFrameHeight && (e.lastFrameHeight = t, e.sendBackMsg(al.SET_FRAME_HEIGHT, {
+                    void 0 === t && (t = document.body.scrollHeight), t !== e.lastFrameHeight && (e.lastFrameHeight = t, e.sendBackMsg(cl.SET_FRAME_HEIGHT, {
                         height: t
                     }))
                 }, e.setComponentValue = function(t) {
                     var n;
-                    t instanceof ol ? (n = "dataframe", t = t.serialize()) : ! function(e) {
+                    t instanceof sl ? (n = "dataframe", t = t.serialize()) : ! function(e) {
                         var t = !1;
                         try {
                             t = e instanceof BigInt64Array || e instanceof BigUint64Array
                         } catch (n) {}
                         return e instanceof Int8Array || e instanceof Uint8Array || e instanceof Uint8ClampedArray || e instanceof Int16Array || e instanceof Uint16Array || e instanceof Int32Array || e instanceof Uint32Array || e instanceof Float32Array || e instanceof Float64Array || t
-                    }(t) ? t instanceof ArrayBuffer ? (n = "bytes", t = new Uint8Array(t)) : n = "json" : (n = "bytes", t = new Uint8Array(t.buffer)), e.sendBackMsg(al.SET_COMPONENT_VALUE, {
+                    }(t) ? t instanceof ArrayBuffer ? (n = "bytes", t = new Uint8Array(t)) : n = "json" : (n = "bytes", t = new Uint8Array(t.buffer)), e.sendBackMsg(cl.SET_COMPONENT_VALUE, {
                         value: t,
                         dataType: n
                     })
                 }, e.onMessageEvent = function(t) {
                     if (t.data.type === e.RENDER_EVENT) e.onRenderMessage(t.data)
                 }, e.onRenderMessage = function(t) {
                     var n = t.args;
                     null == n && (console.error("Got null args in onRenderMessage. This should never happen"), n = {});
                     var r = t.dfs && t.dfs.length > 0 ? e.argsDataframeToObject(t.dfs) : {};
-                    n = ul(ul({}, n), r);
+                    n = ll(ll({}, n), r);
                     var i = Boolean(t.disabled),
                         a = t.theme;
-                    a && sl(a);
+                    a && hl(a);
                     var o = {
                             disabled: i,
                             args: n,
                             theme: a
                         },
                         u = new CustomEvent(e.RENDER_EVENT, {
                             detail: o
@@ -18126,27 +18144,27 @@
                     return Object.fromEntries(n)
                 }, e.toArrowTable = function(e) {
                     var t = e.data,
                         n = t.data,
                         r = t.index,
                         i = t.columns,
                         a = t.styler;
-                    return new ol(n, r, i, a)
+                    return new sl(n, r, i, a)
                 }, e.sendBackMsg = function(e, t) {
-                    window.parent.postMessage(ul({
+                    window.parent.postMessage(ll({
                         isStreamlitMessage: !0,
                         type: e
                     }, t), "*")
                 }, e
             }(),
-            sl = function(e) {
+            hl = function(e) {
                 var t = document.createElement("style");
                 document.head.appendChild(t), t.innerHTML = "\n    :root {\n      --primary-color: " + e.primaryColor + ";\n      --background-color: " + e.backgroundColor + ";\n      --secondary-background-color: " + e.secondaryBackgroundColor + ";\n      --text-color: " + e.textColor + ";\n      --font: " + e.font + ";\n    }\n\n    body {\n      background-color: var(--background-color);\n      color: var(--text-color);\n    }\n  "
             };
-        var ll = function() {
+        var dl = function() {
                 var e = function(t, n) {
                     return e = Object.setPrototypeOf || {
                         __proto__: []
                     }
                     instanceof Array && function(e, t) {
                         e.__proto__ = t
                     } || function(e, t) {
@@ -18156,35 +18174,35 @@
                 return function(t, n) {
                     function r() {
                         this.constructor = t
                     }
                     e(t, n), t.prototype = null === n ? Object.create(n) : (r.prototype = n.prototype, new r)
                 }
             }(),
-            fl = function(e) {
+            pl = function(e) {
                 function t() {
                     return null !== e && e.apply(this, arguments) || this
                 }
-                return ll(t, e), t.prototype.componentDidMount = function() {
-                    cl.setFrameHeight()
+                return dl(t, e), t.prototype.componentDidMount = function() {
+                    fl.setFrameHeight()
                 }, t.prototype.componentDidUpdate = function() {
-                    cl.setFrameHeight()
+                    fl.setFrameHeight()
                 }, t
             }(h.a.PureComponent);
 
-        function hl(e) {
+        function yl(e) {
             var t = function(t) {
                 function n(n) {
                     var r = t.call(this, n) || this;
                     return r.componentDidMount = function() {
-                        cl.events.addEventListener(cl.RENDER_EVENT, r.onRenderEvent), cl.setComponentReady()
+                        fl.events.addEventListener(fl.RENDER_EVENT, r.onRenderEvent), fl.setComponentReady()
                     }, r.componentDidUpdate = function() {
-                        null != r.state.componentError && cl.setFrameHeight()
+                        null != r.state.componentError && fl.setFrameHeight()
                     }, r.componentWillUnmount = function() {
-                        cl.events.removeEventListener(cl.RENDER_EVENT, r.onRenderEvent)
+                        fl.events.removeEventListener(fl.RENDER_EVENT, r.onRenderEvent)
                     }, r.onRenderEvent = function(e) {
                         var t = e;
                         r.setState({
                             renderData: t.detail
                         })
                     }, r.render = function() {
                         return null != r.state.componentError ? h.a.createElement("div", null, h.a.createElement("h1", null, "Component Error"), h.a.createElement("span", null, r.state.componentError.message)) : null == r.state.renderData ? null : h.a.createElement(e, {
@@ -18194,15 +18212,15 @@
                             theme: r.state.renderData.theme
                         })
                     }, r.state = {
                         renderData: void 0,
                         componentError: void 0
                     }, r
                 }
-                return ll(n, t), n.getDerivedStateFromError = function(e) {
+                return dl(n, t), n.getDerivedStateFromError = function(e) {
                     return {
                         componentError: e
                     }
                 }, n
             }(h.a.PureComponent);
             return l()(t, e)
         }
@@ -18244,18 +18262,18 @@
         "use strict";
         ! function e() {
             if ("undefined" !== typeof __REACT_DEVTOOLS_GLOBAL_HOOK__ && "function" === typeof __REACT_DEVTOOLS_GLOBAL_HOOK__.checkDCE) try {
                 __REACT_DEVTOOLS_GLOBAL_HOOK__.checkDCE(e)
             } catch (t) {
                 console.error(t)
             }
-        }(), e.exports = n(33)
+        }(), e.exports = n(34)
     }, function(e, t, n) {
         "use strict";
-        var r = n(22),
+        var r = n(23),
             i = {
                 childContextTypes: !0,
                 contextType: !0,
                 contextTypes: !0,
                 defaultProps: !0,
                 displayName: !0,
                 getDefaultProps: !0,
@@ -18318,15 +18336,15 @@
                     }
                 }
             }
             return t
         }
     }, function(e, t, n) {
         "use strict";
-        var r = n(40),
+        var r = n(41),
             i = /^ms-/;
         e.exports = function(e) {
             return r(e).replace(i, "-ms-")
         }
     }, function(e, t, n) {
         e.exports = function() {
             "use strict";
@@ -18359,19 +18377,19 @@
                             a.split(n).forEach(r)
                     }
                 }
             }
         }()
     }, function(e, t, n) {
         "use strict";
-        var r = n(7),
+        var r = n(6),
             i = n.n(r),
             a = n(9),
             o = n.n(a),
-            u = n(11);
+            u = n(13);
         var c = Object.assign || function(e) {
             for (var t = 1; t < arguments.length; t++) {
                 var n = arguments[t];
                 for (var r in n) Object.prototype.hasOwnProperty.call(n, r) && (e[r] = n[r])
             }
             return e
         };
@@ -19286,15 +19304,15 @@
                 disableOverlay: o.a.bool,
                 renderOverlay: o.a.func.isRequired,
                 allowTouch: o.a.bool
             }, je.defaultProps = Se, xe));
         t.a = Ne
     }, function(e, t, n) {
         "use strict";
-        var r = n(26),
+        var r = n(27),
             i = "function" === typeof Symbol && Symbol.for,
             a = i ? Symbol.for("react.element") : 60103,
             o = i ? Symbol.for("react.portal") : 60106,
             u = i ? Symbol.for("react.fragment") : 60107,
             c = i ? Symbol.for("react.strict_mode") : 60108,
             s = i ? Symbol.for("react.profiler") : 60114,
             l = i ? Symbol.for("react.provider") : 60109,
@@ -19589,17 +19607,17 @@
         }, t.useRef = function(e) {
             return R().useRef(e)
         }, t.useState = function(e) {
             return R().useState(e)
         }, t.version = "16.14.0"
     }, function(e, t, n) {
         "use strict";
-        var r = n(7),
-            i = n(26),
-            a = n(34);
+        var r = n(6),
+            i = n(27),
+            a = n(35);
 
         function o(e) {
             for (var t = "https://reactjs.org/docs/error-decoder.html?invariant=" + e, n = 1; n < arguments.length; n++) t += "&args[]=" + encodeURIComponent(arguments[n]);
             return "Minified React error #" + e + "; visit " + t + " for the full message or use the non-minified dev environment for full errors and additional helpful warnings."
         }
         if (!r) throw Error(o(227));
 
@@ -24830,15 +24848,15 @@
         }, t.unstable_renderSubtreeIntoContainer = function(e, t, n, r) {
             if (!is(n)) throw Error(o(200));
             if (null == e || void 0 === e._reactInternalFiber) throw Error(o(38));
             return as(e, t, n, !1, r)
         }, t.version = "16.14.0"
     }, function(e, t, n) {
         "use strict";
-        e.exports = n(35)
+        e.exports = n(36)
     }, function(e, t, n) {
         "use strict";
         var r, i, a, o, u;
         if ("undefined" === typeof window || "function" !== typeof MessageChannel) {
             var c = null,
                 s = null,
                 l = function e() {
@@ -25294,15 +25312,15 @@
         "use strict";
         var r = /([A-Z])/g;
         e.exports = function(e) {
             return e.replace(r, "-$1").toLowerCase()
         }
     }, function(e, t, n) {
         "use strict";
-        var r = n(42);
+        var r = n(43);
 
         function i() {}
 
         function a() {}
         a.resetWarningCache = i, e.exports = function() {
             function e(e, t, n, i, a, o) {
                 if (o !== r) {
@@ -25341,15 +25359,15 @@
             return n.PropTypes = n, n
         }
     }, function(e, t, n) {
         "use strict";
         e.exports = "SECRET_DO_NOT_PASS_THIS_OR_YOU_WILL_BE_FIRED"
     }, function(e, t, n) {
         "use strict";
-        var r = n(7),
+        var r = n(6),
             i = 60103;
         if (t.Fragment = 60107, "function" === typeof Symbol && Symbol.for) {
             var a = Symbol.for;
             i = a("react.element"), t.Fragment = a("react.fragment")
         }
         var o = r.__SECRET_INTERNALS_DO_NOT_USE_OR_YOU_WILL_BE_FIRED.ReactCurrentOwner,
             u = Object.prototype.hasOwnProperty,
@@ -25375,8 +25393,8 @@
                 props: a,
                 _owner: o.current
             }
         }
         t.jsx = s, t.jsxs = s
     }]
 ]);
-//# sourceMappingURL=2.d24733fb.chunk.js.map
+//# sourceMappingURL=2.97a7e3b4.chunk.js.map
```

### Comparing `image_label-2.4.1/image_label/frontend/build/static/js/2.d24733fb.chunk.js.LICENSE.txt` & `image_label-2.4.2/image_label/frontend/build/static/js/2.97a7e3b4.chunk.js.LICENSE.txt`

 * *Files identical despite different names*

### Comparing `image_label-2.4.1/image_label/frontend/build/static/js/2.d24733fb.chunk.js.map` & `image_label-2.4.2/image_label/frontend/build/static/js/2.97a7e3b4.chunk.js.map`

 * *Files 3% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.8475841977644519%*

 * *Differences: {"'file'": "'static/js/2.97a7e3b4.chunk.js'",*

 * * "'mappings'": "';0IAAe,SAASA,EAAgBC,EAAUC,GAChD,KAAMD,aAAoBC,GACxB,MAAM,IAAIC,UAAU,oCAExB,CAJA,iC,+BCAA,8CACA,SAASC,EAAkBC,EAAQC,GACjC,IAAK,IAAIC,EAAI,EAAGA,EAAID,EAAME,OAAQD,IAAK,CACrC,IAAIE,EAAaH,EAAMC,GACvBE,EAAWC,WAAaD,EAAWC,aAAc,EACjDD,EAAWE,cAAe,EACtB,UAAWF,IAAYA,EAAWG,UAAW,GACjDC,OAAOC,eAAeT,EAAQ,YAAcI,EAAWM,KAAMN,EAC/D,CACF,CACe,SAASO,EAAad,EAAae,EAAYC,GAM5D,OALID,GAAYb,EAAkBF,EAAYiB,UAAWF,GACrDC,GAAad,EAAkBF,EAAagB,GAChDL,OAAOC,eAAeZ,EAAa,YAAa,CAC9CU,U […]*

```diff
@@ -1,10 +1,10 @@
 {
-    "file": "static/js/2.d24733fb.chunk.js",
+    "file": "static/js/2.97a7e3b4.chunk.js",
     "names": [
         "_classCallCheck",
         "instance",
         "Constructor",
         "TypeError",
         "_defineProperties",
         "target",
@@ -167,36 +167,45 @@
         "_toConsumableArray",
         "arr",
         "Array",
         "isArray",
         "arrayLikeToArray",
         "from",
         "unsupportedIterableToArray",
+        "module",
+        "require",
         "asyncGeneratorStep",
         "gen",
         "_next",
         "_throw",
         "_asyncToGenerator",
         "args",
-        "module",
-        "require",
         "_getPrototypeOf",
         "o",
         "bind",
         "ownKeys",
         "enumerableOnly",
         "getOwnPropertySymbols",
         "symbols",
         "filter",
         "sym",
         "getOwnPropertyDescriptor",
         "_objectSpread2",
         "source",
         "getOwnPropertyDescriptors",
         "defineProperties",
+        "_slicedToArray",
+        "_i",
+        "_s",
+        "_e",
+        "_x",
+        "_r",
+        "_arr",
+        "_n",
+        "_d",
         "getChildContext",
         "unsubscribeId",
         "possibleConstructorReturn",
         "_this",
         "_temp",
         "unsubscribeFromContext",
         "attrs",
@@ -505,28 +514,19 @@
         "setEventPhase",
         "setCurrentTarget",
         "_createForOfIteratorHelper",
         "allowArrayLike",
         "it",
         "F",
         "s",
-        "_e",
         "f",
         "normalCompletion",
         "didErr",
         "step",
         "_e2",
-        "_slicedToArray",
-        "_i",
-        "_s",
-        "_x",
-        "_r",
-        "_arr",
-        "_n",
-        "_d",
         "_OverloadYield",
         "kind",
         "v",
         "_awaitAsyncGenerator",
         "AsyncGenerator",
         "front",
         "back",
@@ -807,31 +807,34 @@
         "_context4",
         "_x4",
         "_peek",
         "_callee5",
         "_context5",
         "_x5",
         "_this2",
-        "_ref2",
+        "_ref",
         "BigIntUnavailableError",
         "BigIntUnavailable",
         "asIntN",
         "asUintN",
         "BigInt",
+        "_ref2",
         "BigIntCtor",
         "BigIntAvailable",
-        "_ref4",
+        "_ref3",
         "BigInt64ArrayUnavailableError",
         "BigInt64Array",
         "BigInt64ArrayUnavailable",
+        "_ref4",
         "BigInt64ArrayCtor",
-        "_ref6",
+        "_ref5",
         "BigUint64ArrayUnavailableError",
         "BigUint64Array",
         "BigUint64ArrayUnavailable",
+        "_ref6",
         "BigUint64ArrayCtor",
         "isNumber",
         "isBoolean",
         "isFunction",
         "isPromise",
         "isIterable",
         "isAsyncIterable",
@@ -904,17 +907,15 @@
         "t2",
         "t3",
         "t4",
         "t5",
         "t6",
         "t7",
         "t8",
-        "_ref",
         "_context6",
-        "_ref3",
         "_context7",
         "toInt8ArrayAsyncIterator",
         "toInt16ArrayAsyncIterator",
         "toInt32ArrayAsyncIterator",
         "toUint8ArrayAsyncIterator",
         "toUint16ArrayAsyncIterator",
         "toUint32ArrayAsyncIterator",
@@ -933,21 +934,24 @@
         "_fromNodeStream",
         "threw",
         "cmd",
         "bufferLength",
         "byteRange",
         "_yield",
         "_yield$byteRange",
+        "_joinUint8Arrays",
         "_joinUint8Arrays2",
         "throw",
         "_yield2",
         "_yield$byteRange2",
+        "_joinUint8Arrays3",
         "_joinUint8Arrays4",
         "_yield3",
         "_yield$byteRange3",
+        "_joinUint8Arrays5",
         "_joinUint8Arrays6",
         "AdaptiveByteReader",
         "releaseLock",
         "byobReader",
         "defaultReader",
         "supportsBYOB",
         "reader",
@@ -977,14 +981,15 @@
         "_iterator",
         "_step",
         "_step$value",
         "evt",
         "destroy",
         "_x11",
         "_x12",
+        "_joinUint8Arrays7",
         "_joinUint8Arrays8",
         "race",
         "map",
         "isFinite",
         "receiver",
         "base",
         "org",
@@ -1698,15 +1703,14 @@
         "mid",
         "isValidInternal",
         "getInternal",
         "indexOfInternal",
         "toArray",
         "arraySet",
         "typedSet",
-        "_ref5",
         "chunkIndex",
         "fromIndex",
         "start",
         "found",
         "slices",
         "chunkOffsets",
         "chunkLength",
@@ -1728,16 +1732,17 @@
         "_selectArgs",
         "selectFieldArgs",
         "_selectFieldArgs",
         "_selectChunkArgs",
         "selectVectorChildrenArgs",
         "_selectVectorChildrenArgs",
         "toKeysAndValues",
-        "_Object$entries$reduc2",
+        "_Object$entries$reduc",
         "entries",
+        "_Object$entries$reduc2",
         "fieldIndex",
         "valueIndex",
         "_ret",
         "_keys$idx",
         "_Symbol$toStringTag",
         "dictionaries",
         "generateDictionaryMap",
@@ -1747,14 +1752,15 @@
         "columnIndices",
         "curFields",
         "mergeMaps",
         "newFields",
         "f2",
         "newDictionaries",
         "_Symbol$toStringTag2",
+        "_args",
         "_args2",
         "_args2$",
         "_args2$2",
         "_args2$3",
         "_args2$4",
         "_args$",
         "_args$$name",
@@ -2089,14 +2095,15 @@
         "_bufferRegions",
         "RangeError",
         "isNull",
         "addBuffer",
         "_nullV",
         "assembler",
         "vectorChildren",
+        "_assembler$visitMany",
         "_assembler$visitMany3",
         "assembleFlatVector",
         "assembleFlatListVector",
         "firstOffset",
         "lastOffset",
         "assembleListVector",
         "assembleNestedVector",
@@ -2347,21 +2354,21 @@
         "tableFromAsyncIterable",
         "RecordBatchReader",
         "isSync",
         "open",
         "opening",
         "_fromAsync",
         "cols",
+        "_selectFieldArgs2",
         "_selectFieldArgs3",
         "selectColumnArgs",
         "_StructVector",
         "_dictionaries",
         "DictionaryCollector",
         "collect",
-        "_selectFieldArgs2",
         "fs",
         "vs",
         "batchData",
         "ensureSameLengthData",
         "readAllSync",
         "impl",
         "_impl",
@@ -3941,27 +3948,31 @@
         "../node_modules/@babel/runtime/helpers/esm/inherits.js",
         "../node_modules/@babel/runtime/helpers/esm/createSuper.js",
         "../node_modules/@babel/runtime/helpers/esm/regeneratorRuntime.js",
         "../node_modules/@babel/runtime/helpers/esm/toConsumableArray.js",
         "../node_modules/@babel/runtime/helpers/esm/arrayWithoutHoles.js",
         "../node_modules/@babel/runtime/helpers/esm/iterableToArray.js",
         "../node_modules/@babel/runtime/helpers/esm/nonIterableSpread.js",
-        "../node_modules/@babel/runtime/helpers/esm/asyncToGenerator.js",
         "../node_modules/react/index.js",
+        "../node_modules/@babel/runtime/helpers/esm/asyncToGenerator.js",
         "../node_modules/@babel/runtime/helpers/esm/getPrototypeOf.js",
         "../node_modules/prop-types/index.js",
         "../node_modules/@babel/runtime/helpers/esm/objectSpread2.js",
+        "../node_modules/@babel/runtime/helpers/esm/slicedToArray.js",
+        "../node_modules/@babel/runtime/helpers/esm/arrayWithHoles.js",
+        "../node_modules/@babel/runtime/helpers/esm/iterableToArrayLimit.js",
+        "../node_modules/@babel/runtime/helpers/esm/nonIterableRest.js",
+        "../node_modules/react/jsx-runtime.js",
         "../../src/models/StyleTags.js",
         "../../src/models/StyleSheetManager.js",
         "../../src/models/StyledComponent.js",
         "../../src/models/ComponentStyle.js",
         "../../src/constructors/keyframes.js",
         "../../src/constructors/injectGlobal.js",
         "../node_modules/@babel/runtime/helpers/esm/defineProperty.js",
-        "../node_modules/react/jsx-runtime.js",
         "../node_modules/@babel/runtime/helpers/esm/typeof.js",
         "../node_modules/@babel/runtime/helpers/esm/possibleConstructorReturn.js",
         "../node_modules/@babel/runtime/helpers/esm/assertThisInitialized.js",
         "../node_modules/@babel/runtime/helpers/esm/unsupportedIterableToArray.js",
         "../node_modules/@babel/runtime/helpers/esm/arrayLikeToArray.js",
         "../node_modules/@babel/runtime/helpers/esm/setPrototypeOf.js",
         "../node_modules/@babel/runtime/helpers/esm/isNativeReflectConstruct.js",
@@ -3969,18 +3980,14 @@
         "../node_modules/@babel/runtime/helpers/esm/toPrimitive.js",
         "../node_modules/react-is/index.js",
         "../node_modules/stylis/stylis.js",
         "../node_modules/styled-components/node_modules/hoist-non-react-statics/dist/hoist-non-react-statics.cjs.js",
         "../../src/event.mjs",
         "../../src/event-target.mjs",
         "../node_modules/@babel/runtime/helpers/esm/createForOfIteratorHelper.js",
-        "../node_modules/@babel/runtime/helpers/esm/slicedToArray.js",
-        "../node_modules/@babel/runtime/helpers/esm/arrayWithHoles.js",
-        "../node_modules/@babel/runtime/helpers/esm/iterableToArrayLimit.js",
-        "../node_modules/@babel/runtime/helpers/esm/nonIterableRest.js",
         "../node_modules/@babel/runtime/helpers/esm/OverloadYield.js",
         "../node_modules/@babel/runtime/helpers/esm/awaitAsyncGenerator.js",
         "../node_modules/@babel/runtime/helpers/esm/AsyncGenerator.js",
         "../node_modules/@babel/runtime/helpers/esm/wrapAsyncGenerator.js",
         "../node_modules/@babel/runtime/helpers/esm/asyncGeneratorDelegate.js",
         "../node_modules/@babel/runtime/helpers/esm/asyncIterator.js",
         "../node_modules/flatbuffers/js/flatbuffers.mjs",
@@ -4133,27 +4140,31 @@
         "import setPrototypeOf from \"./setPrototypeOf.js\";\nexport default function _inherits(subClass, superClass) {\n  if (typeof superClass !== \"function\" && superClass !== null) {\n    throw new TypeError(\"Super expression must either be null or a function\");\n  }\n  subClass.prototype = Object.create(superClass && superClass.prototype, {\n    constructor: {\n      value: subClass,\n      writable: true,\n      configurable: true\n    }\n  });\n  Object.defineProperty(subClass, \"prototype\", {\n    writable: false\n  });\n  if (superClass) setPrototypeOf(subClass, superClass);\n}",
         "import getPrototypeOf from \"./getPrototypeOf.js\";\nimport isNativeReflectConstruct from \"./isNativeReflectConstruct.js\";\nimport possibleConstructorReturn from \"./possibleConstructorReturn.js\";\nexport default function _createSuper(Derived) {\n  var hasNativeReflectConstruct = isNativeReflectConstruct();\n  return function _createSuperInternal() {\n    var Super = getPrototypeOf(Derived),\n      result;\n    if (hasNativeReflectConstruct) {\n      var NewTarget = getPrototypeOf(this).constructor;\n      result = Reflect.construct(Super, arguments, NewTarget);\n    } else {\n      result = Super.apply(this, arguments);\n    }\n    return possibleConstructorReturn(this, result);\n  };\n}",
         "import _typeof from \"./typeof.js\";\nexport default function _regeneratorRuntime() {\n  \"use strict\"; /*! regenerator-runtime -- Copyright (c) 2014-present, Facebook, Inc. -- license (MIT): https://github.com/facebook/regenerator/blob/main/LICENSE */\n  _regeneratorRuntime = function _regeneratorRuntime() {\n    return exports;\n  };\n  var exports = {},\n    Op = Object.prototype,\n    hasOwn = Op.hasOwnProperty,\n    defineProperty = Object.defineProperty || function (obj, key, desc) {\n      obj[key] = desc.value;\n    },\n    $Symbol = \"function\" == typeof Symbol ? Symbol : {},\n    iteratorSymbol = $Symbol.iterator || \"@@iterator\",\n    asyncIteratorSymbol = $Symbol.asyncIterator || \"@@asyncIterator\",\n    toStringTagSymbol = $Symbol.toStringTag || \"@@toStringTag\";\n  function define(obj, key, value) {\n    return Object.defineProperty(obj, key, {\n      value: value,\n      enumerable: !0,\n      configurable: !0,\n      writable: !0\n    }), obj[key];\n  }\n  try {\n    define({}, \"\");\n  } catch (err) {\n    define = function define(obj, key, value) {\n      return obj[key] = value;\n    };\n  }\n  function wrap(innerFn, outerFn, self, tryLocsList) {\n    var protoGenerator = outerFn && outerFn.prototype instanceof Generator ? outerFn : Generator,\n      generator = Object.create(protoGenerator.prototype),\n      context = new Context(tryLocsList || []);\n    return defineProperty(generator, \"_invoke\", {\n      value: makeInvokeMethod(innerFn, self, context)\n    }), generator;\n  }\n  function tryCatch(fn, obj, arg) {\n    try {\n      return {\n        type: \"normal\",\n        arg: fn.call(obj, arg)\n      };\n    } catch (err) {\n      return {\n        type: \"throw\",\n        arg: err\n      };\n    }\n  }\n  exports.wrap = wrap;\n  var ContinueSentinel = {};\n  function Generator() {}\n  function GeneratorFunction() {}\n  function GeneratorFunctionPrototype() {}\n  var IteratorPrototype = {};\n  define(IteratorPrototype, iteratorSymbol, function () {\n    return this;\n  });\n  var getProto = Object.getPrototypeOf,\n    NativeIteratorPrototype = getProto && getProto(getProto(values([])));\n  NativeIteratorPrototype && NativeIteratorPrototype !== Op && hasOwn.call(NativeIteratorPrototype, iteratorSymbol) && (IteratorPrototype = NativeIteratorPrototype);\n  var Gp = GeneratorFunctionPrototype.prototype = Generator.prototype = Object.create(IteratorPrototype);\n  function defineIteratorMethods(prototype) {\n    [\"next\", \"throw\", \"return\"].forEach(function (method) {\n      define(prototype, method, function (arg) {\n        return this._invoke(method, arg);\n      });\n    });\n  }\n  function AsyncIterator(generator, PromiseImpl) {\n    function invoke(method, arg, resolve, reject) {\n      var record = tryCatch(generator[method], generator, arg);\n      if (\"throw\" !== record.type) {\n        var result = record.arg,\n          value = result.value;\n        return value && \"object\" == _typeof(value) && hasOwn.call(value, \"__await\") ? PromiseImpl.resolve(value.__await).then(function (value) {\n          invoke(\"next\", value, resolve, reject);\n        }, function (err) {\n          invoke(\"throw\", err, resolve, reject);\n        }) : PromiseImpl.resolve(value).then(function (unwrapped) {\n          result.value = unwrapped, resolve(result);\n        }, function (error) {\n          return invoke(\"throw\", error, resolve, reject);\n        });\n      }\n      reject(record.arg);\n    }\n    var previousPromise;\n    defineProperty(this, \"_invoke\", {\n      value: function value(method, arg) {\n        function callInvokeWithMethodAndArg() {\n          return new PromiseImpl(function (resolve, reject) {\n            invoke(method, arg, resolve, reject);\n          });\n        }\n        return previousPromise = previousPromise ? previousPromise.then(callInvokeWithMethodAndArg, callInvokeWithMethodAndArg) : callInvokeWithMethodAndArg();\n      }\n    });\n  }\n  function makeInvokeMethod(innerFn, self, context) {\n    var state = \"suspendedStart\";\n    return function (method, arg) {\n      if (\"executing\" === state) throw new Error(\"Generator is already running\");\n      if (\"completed\" === state) {\n        if (\"throw\" === method) throw arg;\n        return doneResult();\n      }\n      for (context.method = method, context.arg = arg;;) {\n        var delegate = context.delegate;\n        if (delegate) {\n          var delegateResult = maybeInvokeDelegate(delegate, context);\n          if (delegateResult) {\n            if (delegateResult === ContinueSentinel) continue;\n            return delegateResult;\n          }\n        }\n        if (\"next\" === context.method) context.sent = context._sent = context.arg;else if (\"throw\" === context.method) {\n          if (\"suspendedStart\" === state) throw state = \"completed\", context.arg;\n          context.dispatchException(context.arg);\n        } else \"return\" === context.method && context.abrupt(\"return\", context.arg);\n        state = \"executing\";\n        var record = tryCatch(innerFn, self, context);\n        if (\"normal\" === record.type) {\n          if (state = context.done ? \"completed\" : \"suspendedYield\", record.arg === ContinueSentinel) continue;\n          return {\n            value: record.arg,\n            done: context.done\n          };\n        }\n        \"throw\" === record.type && (state = \"completed\", context.method = \"throw\", context.arg = record.arg);\n      }\n    };\n  }\n  function maybeInvokeDelegate(delegate, context) {\n    var methodName = context.method,\n      method = delegate.iterator[methodName];\n    if (undefined === method) return context.delegate = null, \"throw\" === methodName && delegate.iterator[\"return\"] && (context.method = \"return\", context.arg = undefined, maybeInvokeDelegate(delegate, context), \"throw\" === context.method) || \"return\" !== methodName && (context.method = \"throw\", context.arg = new TypeError(\"The iterator does not provide a '\" + methodName + \"' method\")), ContinueSentinel;\n    var record = tryCatch(method, delegate.iterator, context.arg);\n    if (\"throw\" === record.type) return context.method = \"throw\", context.arg = record.arg, context.delegate = null, ContinueSentinel;\n    var info = record.arg;\n    return info ? info.done ? (context[delegate.resultName] = info.value, context.next = delegate.nextLoc, \"return\" !== context.method && (context.method = \"next\", context.arg = undefined), context.delegate = null, ContinueSentinel) : info : (context.method = \"throw\", context.arg = new TypeError(\"iterator result is not an object\"), context.delegate = null, ContinueSentinel);\n  }\n  function pushTryEntry(locs) {\n    var entry = {\n      tryLoc: locs[0]\n    };\n    1 in locs && (entry.catchLoc = locs[1]), 2 in locs && (entry.finallyLoc = locs[2], entry.afterLoc = locs[3]), this.tryEntries.push(entry);\n  }\n  function resetTryEntry(entry) {\n    var record = entry.completion || {};\n    record.type = \"normal\", delete record.arg, entry.completion = record;\n  }\n  function Context(tryLocsList) {\n    this.tryEntries = [{\n      tryLoc: \"root\"\n    }], tryLocsList.forEach(pushTryEntry, this), this.reset(!0);\n  }\n  function values(iterable) {\n    if (iterable) {\n      var iteratorMethod = iterable[iteratorSymbol];\n      if (iteratorMethod) return iteratorMethod.call(iterable);\n      if (\"function\" == typeof iterable.next) return iterable;\n      if (!isNaN(iterable.length)) {\n        var i = -1,\n          next = function next() {\n            for (; ++i < iterable.length;) if (hasOwn.call(iterable, i)) return next.value = iterable[i], next.done = !1, next;\n            return next.value = undefined, next.done = !0, next;\n          };\n        return next.next = next;\n      }\n    }\n    return {\n      next: doneResult\n    };\n  }\n  function doneResult() {\n    return {\n      value: undefined,\n      done: !0\n    };\n  }\n  return GeneratorFunction.prototype = GeneratorFunctionPrototype, defineProperty(Gp, \"constructor\", {\n    value: GeneratorFunctionPrototype,\n    configurable: !0\n  }), defineProperty(GeneratorFunctionPrototype, \"constructor\", {\n    value: GeneratorFunction,\n    configurable: !0\n  }), GeneratorFunction.displayName = define(GeneratorFunctionPrototype, toStringTagSymbol, \"GeneratorFunction\"), exports.isGeneratorFunction = function (genFun) {\n    var ctor = \"function\" == typeof genFun && genFun.constructor;\n    return !!ctor && (ctor === GeneratorFunction || \"GeneratorFunction\" === (ctor.displayName || ctor.name));\n  }, exports.mark = function (genFun) {\n    return Object.setPrototypeOf ? Object.setPrototypeOf(genFun, GeneratorFunctionPrototype) : (genFun.__proto__ = GeneratorFunctionPrototype, define(genFun, toStringTagSymbol, \"GeneratorFunction\")), genFun.prototype = Object.create(Gp), genFun;\n  }, exports.awrap = function (arg) {\n    return {\n      __await: arg\n    };\n  }, defineIteratorMethods(AsyncIterator.prototype), define(AsyncIterator.prototype, asyncIteratorSymbol, function () {\n    return this;\n  }), exports.AsyncIterator = AsyncIterator, exports.async = function (innerFn, outerFn, self, tryLocsList, PromiseImpl) {\n    void 0 === PromiseImpl && (PromiseImpl = Promise);\n    var iter = new AsyncIterator(wrap(innerFn, outerFn, self, tryLocsList), PromiseImpl);\n    return exports.isGeneratorFunction(outerFn) ? iter : iter.next().then(function (result) {\n      return result.done ? result.value : iter.next();\n    });\n  }, defineIteratorMethods(Gp), define(Gp, toStringTagSymbol, \"Generator\"), define(Gp, iteratorSymbol, function () {\n    return this;\n  }), define(Gp, \"toString\", function () {\n    return \"[object Generator]\";\n  }), exports.keys = function (val) {\n    var object = Object(val),\n      keys = [];\n    for (var key in object) keys.push(key);\n    return keys.reverse(), function next() {\n      for (; keys.length;) {\n        var key = keys.pop();\n        if (key in object) return next.value = key, next.done = !1, next;\n      }\n      return next.done = !0, next;\n    };\n  }, exports.values = values, Context.prototype = {\n    constructor: Context,\n    reset: function reset(skipTempReset) {\n      if (this.prev = 0, this.next = 0, this.sent = this._sent = undefined, this.done = !1, this.delegate = null, this.method = \"next\", this.arg = undefined, this.tryEntries.forEach(resetTryEntry), !skipTempReset) for (var name in this) \"t\" === name.charAt(0) && hasOwn.call(this, name) && !isNaN(+name.slice(1)) && (this[name] = undefined);\n    },\n    stop: function stop() {\n      this.done = !0;\n      var rootRecord = this.tryEntries[0].completion;\n      if (\"throw\" === rootRecord.type) throw rootRecord.arg;\n      return this.rval;\n    },\n    dispatchException: function dispatchException(exception) {\n      if (this.done) throw exception;\n      var context = this;\n      function handle(loc, caught) {\n        return record.type = \"throw\", record.arg = exception, context.next = loc, caught && (context.method = \"next\", context.arg = undefined), !!caught;\n      }\n      for (var i = this.tryEntries.length - 1; i >= 0; --i) {\n        var entry = this.tryEntries[i],\n          record = entry.completion;\n        if (\"root\" === entry.tryLoc) return handle(\"end\");\n        if (entry.tryLoc <= this.prev) {\n          var hasCatch = hasOwn.call(entry, \"catchLoc\"),\n            hasFinally = hasOwn.call(entry, \"finallyLoc\");\n          if (hasCatch && hasFinally) {\n            if (this.prev < entry.catchLoc) return handle(entry.catchLoc, !0);\n            if (this.prev < entry.finallyLoc) return handle(entry.finallyLoc);\n          } else if (hasCatch) {\n            if (this.prev < entry.catchLoc) return handle(entry.catchLoc, !0);\n          } else {\n            if (!hasFinally) throw new Error(\"try statement without catch or finally\");\n            if (this.prev < entry.finallyLoc) return handle(entry.finallyLoc);\n          }\n        }\n      }\n    },\n    abrupt: function abrupt(type, arg) {\n      for (var i = this.tryEntries.length - 1; i >= 0; --i) {\n        var entry = this.tryEntries[i];\n        if (entry.tryLoc <= this.prev && hasOwn.call(entry, \"finallyLoc\") && this.prev < entry.finallyLoc) {\n          var finallyEntry = entry;\n          break;\n        }\n      }\n      finallyEntry && (\"break\" === type || \"continue\" === type) && finallyEntry.tryLoc <= arg && arg <= finallyEntry.finallyLoc && (finallyEntry = null);\n      var record = finallyEntry ? finallyEntry.completion : {};\n      return record.type = type, record.arg = arg, finallyEntry ? (this.method = \"next\", this.next = finallyEntry.finallyLoc, ContinueSentinel) : this.complete(record);\n    },\n    complete: function complete(record, afterLoc) {\n      if (\"throw\" === record.type) throw record.arg;\n      return \"break\" === record.type || \"continue\" === record.type ? this.next = record.arg : \"return\" === record.type ? (this.rval = this.arg = record.arg, this.method = \"return\", this.next = \"end\") : \"normal\" === record.type && afterLoc && (this.next = afterLoc), ContinueSentinel;\n    },\n    finish: function finish(finallyLoc) {\n      for (var i = this.tryEntries.length - 1; i >= 0; --i) {\n        var entry = this.tryEntries[i];\n        if (entry.finallyLoc === finallyLoc) return this.complete(entry.completion, entry.afterLoc), resetTryEntry(entry), ContinueSentinel;\n      }\n    },\n    \"catch\": function _catch(tryLoc) {\n      for (var i = this.tryEntries.length - 1; i >= 0; --i) {\n        var entry = this.tryEntries[i];\n        if (entry.tryLoc === tryLoc) {\n          var record = entry.completion;\n          if (\"throw\" === record.type) {\n            var thrown = record.arg;\n            resetTryEntry(entry);\n          }\n          return thrown;\n        }\n      }\n      throw new Error(\"illegal catch attempt\");\n    },\n    delegateYield: function delegateYield(iterable, resultName, nextLoc) {\n      return this.delegate = {\n        iterator: values(iterable),\n        resultName: resultName,\n        nextLoc: nextLoc\n      }, \"next\" === this.method && (this.arg = undefined), ContinueSentinel;\n    }\n  }, exports;\n}",
         "import arrayWithoutHoles from \"./arrayWithoutHoles.js\";\nimport iterableToArray from \"./iterableToArray.js\";\nimport unsupportedIterableToArray from \"./unsupportedIterableToArray.js\";\nimport nonIterableSpread from \"./nonIterableSpread.js\";\nexport default function _toConsumableArray(arr) {\n  return arrayWithoutHoles(arr) || iterableToArray(arr) || unsupportedIterableToArray(arr) || nonIterableSpread();\n}",
         "import arrayLikeToArray from \"./arrayLikeToArray.js\";\nexport default function _arrayWithoutHoles(arr) {\n  if (Array.isArray(arr)) return arrayLikeToArray(arr);\n}",
         "export default function _iterableToArray(iter) {\n  if (typeof Symbol !== \"undefined\" && iter[Symbol.iterator] != null || iter[\"@@iterator\"] != null) return Array.from(iter);\n}",
         "export default function _nonIterableSpread() {\n  throw new TypeError(\"Invalid attempt to spread non-iterable instance.\\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.\");\n}",
-        "function asyncGeneratorStep(gen, resolve, reject, _next, _throw, key, arg) {\n  try {\n    var info = gen[key](arg);\n    var value = info.value;\n  } catch (error) {\n    reject(error);\n    return;\n  }\n  if (info.done) {\n    resolve(value);\n  } else {\n    Promise.resolve(value).then(_next, _throw);\n  }\n}\nexport default function _asyncToGenerator(fn) {\n  return function () {\n    var self = this,\n      args = arguments;\n    return new Promise(function (resolve, reject) {\n      var gen = fn.apply(self, args);\n      function _next(value) {\n        asyncGeneratorStep(gen, resolve, reject, _next, _throw, \"next\", value);\n      }\n      function _throw(err) {\n        asyncGeneratorStep(gen, resolve, reject, _next, _throw, \"throw\", err);\n      }\n      _next(undefined);\n    });\n  };\n}",
         "'use strict';\n\nif (process.env.NODE_ENV === 'production') {\n  module.exports = require('./cjs/react.production.min.js');\n} else {\n  module.exports = require('./cjs/react.development.js');\n}\n",
+        "function asyncGeneratorStep(gen, resolve, reject, _next, _throw, key, arg) {\n  try {\n    var info = gen[key](arg);\n    var value = info.value;\n  } catch (error) {\n    reject(error);\n    return;\n  }\n  if (info.done) {\n    resolve(value);\n  } else {\n    Promise.resolve(value).then(_next, _throw);\n  }\n}\nexport default function _asyncToGenerator(fn) {\n  return function () {\n    var self = this,\n      args = arguments;\n    return new Promise(function (resolve, reject) {\n      var gen = fn.apply(self, args);\n      function _next(value) {\n        asyncGeneratorStep(gen, resolve, reject, _next, _throw, \"next\", value);\n      }\n      function _throw(err) {\n        asyncGeneratorStep(gen, resolve, reject, _next, _throw, \"throw\", err);\n      }\n      _next(undefined);\n    });\n  };\n}",
         "export default function _getPrototypeOf(o) {\n  _getPrototypeOf = Object.setPrototypeOf ? Object.getPrototypeOf.bind() : function _getPrototypeOf(o) {\n    return o.__proto__ || Object.getPrototypeOf(o);\n  };\n  return _getPrototypeOf(o);\n}",
         "/**\n * Copyright (c) 2013-present, Facebook, Inc.\n *\n * This source code is licensed under the MIT license found in the\n * LICENSE file in the root directory of this source tree.\n */\n\nif (process.env.NODE_ENV !== 'production') {\n  var ReactIs = require('react-is');\n\n  // By explicitly using `prop-types` you are opting into new development behavior.\n  // http://fb.me/prop-types-in-prod\n  var throwOnDirectAccess = true;\n  module.exports = require('./factoryWithTypeCheckers')(ReactIs.isElement, throwOnDirectAccess);\n} else {\n  // By explicitly using `prop-types` you are opting into new production behavior.\n  // http://fb.me/prop-types-in-prod\n  module.exports = require('./factoryWithThrowingShims')();\n}\n",
         "import defineProperty from \"./defineProperty.js\";\nfunction ownKeys(object, enumerableOnly) {\n  var keys = Object.keys(object);\n  if (Object.getOwnPropertySymbols) {\n    var symbols = Object.getOwnPropertySymbols(object);\n    enumerableOnly && (symbols = symbols.filter(function (sym) {\n      return Object.getOwnPropertyDescriptor(object, sym).enumerable;\n    })), keys.push.apply(keys, symbols);\n  }\n  return keys;\n}\nexport default function _objectSpread2(target) {\n  for (var i = 1; i < arguments.length; i++) {\n    var source = null != arguments[i] ? arguments[i] : {};\n    i % 2 ? ownKeys(Object(source), !0).forEach(function (key) {\n      defineProperty(target, key, source[key]);\n    }) : Object.getOwnPropertyDescriptors ? Object.defineProperties(target, Object.getOwnPropertyDescriptors(source)) : ownKeys(Object(source)).forEach(function (key) {\n      Object.defineProperty(target, key, Object.getOwnPropertyDescriptor(source, key));\n    });\n  }\n  return target;\n}",
+        "import arrayWithHoles from \"./arrayWithHoles.js\";\nimport iterableToArrayLimit from \"./iterableToArrayLimit.js\";\nimport unsupportedIterableToArray from \"./unsupportedIterableToArray.js\";\nimport nonIterableRest from \"./nonIterableRest.js\";\nexport default function _slicedToArray(arr, i) {\n  return arrayWithHoles(arr) || iterableToArrayLimit(arr, i) || unsupportedIterableToArray(arr, i) || nonIterableRest();\n}",
+        "export default function _arrayWithHoles(arr) {\n  if (Array.isArray(arr)) return arr;\n}",
+        "export default function _iterableToArrayLimit(arr, i) {\n  var _i = null == arr ? null : \"undefined\" != typeof Symbol && arr[Symbol.iterator] || arr[\"@@iterator\"];\n  if (null != _i) {\n    var _s,\n      _e,\n      _x,\n      _r,\n      _arr = [],\n      _n = !0,\n      _d = !1;\n    try {\n      if (_x = (_i = _i.call(arr)).next, 0 === i) {\n        if (Object(_i) !== _i) return;\n        _n = !1;\n      } else for (; !(_n = (_s = _x.call(_i)).done) && (_arr.push(_s.value), _arr.length !== i); _n = !0);\n    } catch (err) {\n      _d = !0, _e = err;\n    } finally {\n      try {\n        if (!_n && null != _i[\"return\"] && (_r = _i[\"return\"](), Object(_r) !== _r)) return;\n      } finally {\n        if (_d) throw _e;\n      }\n    }\n    return _arr;\n  }\n}",
+        "export default function _nonIterableRest() {\n  throw new TypeError(\"Invalid attempt to destructure non-iterable instance.\\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.\");\n}",
+        "'use strict';\n\nif (process.env.NODE_ENV === 'production') {\n  module.exports = require('./cjs/react-jsx-runtime.production.min.js');\n} else {\n  module.exports = require('./cjs/react-jsx-runtime.development.js');\n}\n",
         "// @flow\n/* eslint-disable flowtype/object-type-delimiter */\n/* eslint-disable react/prop-types */\n\nimport React, { type Element } from 'react'\nimport { IS_BROWSER, DISABLE_SPEEDY, SC_ATTR } from '../constants'\nimport StyledError from '../utils/error'\nimport { type ExtractedComp } from '../utils/extractCompsFromCSS'\nimport { splitByRules } from '../utils/stringifyRules'\nimport getNonce from '../utils/nonce'\nimport once from '../utils/once'\n\nimport {\n  type Names,\n  addNameForId,\n  resetIdNames,\n  hasNameForId,\n  stringifyNames,\n  cloneNames,\n} from '../utils/styleNames'\n\nimport {\n  sheetForTag,\n  safeInsertRule,\n  deleteRules,\n} from '../utils/insertRuleHelpers'\n\nexport interface Tag<T> {\n  // $FlowFixMe: Doesn't seem to accept any combination w/ HTMLStyleElement for some reason\n  styleTag: HTMLStyleElement | null;\n  /* lists all ids of the tag */\n  getIds(): string[];\n  /* checks whether `name` is already injected for `id` */\n  hasNameForId(id: string, name: string): boolean;\n  /* inserts a marker to ensure the id's correct position in the sheet */\n  insertMarker(id: string): T;\n  /* inserts rules according to the ids markers */\n  insertRules(id: string, cssRules: string[], name: ?string): void;\n  /* removes all rules belonging to the id, keeping the marker around */\n  removeRules(id: string): void;\n  css(): string;\n  toHTML(additionalAttrs: ?string): string;\n  toElement(): Element<*>;\n  clone(): Tag<T>;\n  /* used in server side rendering to indicate that the rules in the tag have been flushed to HTML */\n  sealed: boolean;\n}\n\n/* this marker separates component styles and is important for rehydration */\nconst makeTextMarker = id => `\\n/* sc-component-id: ${id} */\\n`\n\n/* add up all numbers in array up until and including the index */\nconst addUpUntilIndex = (sizes: number[], index: number): number => {\n  let totalUpToIndex = 0\n  for (let i = 0; i <= index; i += 1) {\n    totalUpToIndex += sizes[i]\n  }\n\n  return totalUpToIndex\n}\n\n/* create a new style tag after lastEl */\nconst makeStyleTag = (\n  target: ?HTMLElement,\n  tagEl: ?Node,\n  insertBefore: ?boolean\n) => {\n  const el = document.createElement('style')\n  el.setAttribute(SC_ATTR, '')\n\n  const nonce = getNonce()\n  if (nonce) {\n    el.setAttribute('nonce', nonce)\n  }\n\n  /* Work around insertRule quirk in EdgeHTML */\n  el.appendChild(document.createTextNode(''))\n\n  if (target && !tagEl) {\n    /* Append to target when no previous element was passed */\n    target.appendChild(el)\n  } else {\n    if (!tagEl || !target || !tagEl.parentNode) {\n      throw new StyledError(6)\n    }\n\n    /* Insert new style tag after the previous one */\n    tagEl.parentNode.insertBefore(el, insertBefore ? tagEl : tagEl.nextSibling)\n  }\n\n  return el\n}\n\n/* takes a css factory function and outputs an html styled tag factory */\nconst wrapAsHtmlTag = (css: () => string, names: Names) => (\n  additionalAttrs: ?string\n): string => {\n  const nonce = getNonce()\n  const attrs = [\n    nonce && `nonce=\"${nonce}\"`,\n    `${SC_ATTR}=\"${stringifyNames(names)}\"`,\n    additionalAttrs,\n  ]\n\n  const htmlAttr = attrs.filter(Boolean).join(' ')\n  return `<style ${htmlAttr}>${css()}</style>`\n}\n\n/* takes a css factory function and outputs an element factory */\nconst wrapAsElement = (css: () => string, names: Names) => () => {\n  const props = {\n    [SC_ATTR]: stringifyNames(names),\n  }\n\n  const nonce = getNonce()\n  if (nonce) {\n    // $FlowFixMe\n    props.nonce = nonce\n  }\n\n  // eslint-disable-next-line react/no-danger\n  return <style {...props} dangerouslySetInnerHTML={{ __html: css() }} />\n}\n\nconst getIdsFromMarkersFactory = (markers: Object) => (): string[] =>\n  Object.keys(markers)\n\n/* speedy tags utilise insertRule */\nconst makeSpeedyTag = (\n  el: HTMLStyleElement,\n  getImportRuleTag: ?() => Tag<any>\n): Tag<number> => {\n  const names: Names = (Object.create(null): Object)\n  const markers = Object.create(null)\n  const sizes: number[] = []\n\n  const extractImport = getImportRuleTag !== undefined\n  /* indicates whther getImportRuleTag was called */\n  let usedImportRuleTag = false\n\n  const insertMarker = id => {\n    const prev = markers[id]\n    if (prev !== undefined) {\n      return prev\n    }\n\n    markers[id] = sizes.length\n    sizes.push(0)\n    resetIdNames(names, id)\n\n    return markers[id]\n  }\n\n  const insertRules = (id, cssRules, name) => {\n    const marker = insertMarker(id)\n    const sheet = sheetForTag(el)\n    const insertIndex = addUpUntilIndex(sizes, marker)\n\n    let injectedRules = 0\n    const importRules = []\n    const cssRulesSize = cssRules.length\n\n    for (let i = 0; i < cssRulesSize; i += 1) {\n      const cssRule = cssRules[i]\n      let mayHaveImport = extractImport /* @import rules are reordered to appear first */\n      if (mayHaveImport && cssRule.indexOf('@import') !== -1) {\n        importRules.push(cssRule)\n      } else if (safeInsertRule(sheet, cssRule, insertIndex + injectedRules)) {\n        mayHaveImport = false\n        injectedRules += 1\n      }\n    }\n\n    if (extractImport && importRules.length > 0) {\n      usedImportRuleTag = true\n      // $FlowFixMe\n      getImportRuleTag().insertRules(`${id}-import`, importRules)\n    }\n\n    sizes[marker] += injectedRules /* add up no of injected rules */\n    addNameForId(names, id, name)\n  }\n\n  const removeRules = id => {\n    const marker = markers[id]\n    if (marker === undefined) return\n\n    const size = sizes[marker]\n    const sheet = sheetForTag(el)\n    const removalIndex = addUpUntilIndex(sizes, marker)\n    deleteRules(sheet, removalIndex, size)\n    sizes[marker] = 0\n    resetIdNames(names, id)\n\n    if (extractImport && usedImportRuleTag) {\n      // $FlowFixMe\n      getImportRuleTag().removeRules(`${id}-import`)\n    }\n  }\n\n  const css = () => {\n    const { cssRules } = sheetForTag(el)\n    let str = ''\n\n    // eslint-disable-next-line guard-for-in\n    for (const id in markers) {\n      str += makeTextMarker(id)\n      const marker = markers[id]\n      const end = addUpUntilIndex(sizes, marker)\n      const size = sizes[marker]\n      for (let i = end - size; i < end; i += 1) {\n        const rule = cssRules[i]\n        if (rule !== undefined) {\n          str += rule.cssText\n        }\n      }\n    }\n\n    return str\n  }\n\n  return {\n    clone() {\n      throw new StyledError(5)\n    },\n    css,\n    getIds: getIdsFromMarkersFactory(markers),\n    hasNameForId: hasNameForId(names),\n    insertMarker,\n    insertRules,\n    removeRules,\n    sealed: false,\n    styleTag: el,\n    toElement: wrapAsElement(css, names),\n    toHTML: wrapAsHtmlTag(css, names),\n  }\n}\n\nconst makeTextNode = id => document.createTextNode(makeTextMarker(id))\n\nconst makeBrowserTag = (\n  el: HTMLStyleElement,\n  getImportRuleTag: ?() => Tag<any>\n): Tag<Text> => {\n  const names = (Object.create(null): Object)\n  const markers = Object.create(null)\n\n  const extractImport = getImportRuleTag !== undefined\n\n  /* indicates whther getImportRuleTag was called */\n  let usedImportRuleTag = false\n\n  const insertMarker = id => {\n    const prev = markers[id]\n    if (prev !== undefined) {\n      return prev\n    }\n\n    markers[id] = makeTextNode(id)\n    el.appendChild(markers[id])\n    names[id] = Object.create(null)\n\n    return markers[id]\n  }\n\n  const insertRules = (id, cssRules, name) => {\n    const marker = insertMarker(id)\n    const importRules = []\n    const cssRulesSize = cssRules.length\n\n    for (let i = 0; i < cssRulesSize; i += 1) {\n      const rule = cssRules[i]\n      let mayHaveImport = extractImport\n      if (mayHaveImport && rule.indexOf('@import') !== -1) {\n        importRules.push(rule)\n      } else {\n        mayHaveImport = false\n        const separator = i === cssRulesSize - 1 ? '' : ' '\n        marker.appendData(`${rule}${separator}`)\n      }\n    }\n\n    addNameForId(names, id, name)\n\n    if (extractImport && importRules.length > 0) {\n      usedImportRuleTag = true\n      // $FlowFixMe\n      getImportRuleTag().insertRules(`${id}-import`, importRules)\n    }\n  }\n\n  const removeRules = id => {\n    const marker = markers[id]\n    if (marker === undefined) return\n\n    /* create new empty text node and replace the current one */\n    const newMarker = makeTextNode(id)\n    el.replaceChild(newMarker, marker)\n    markers[id] = newMarker\n    resetIdNames(names, id)\n\n    if (extractImport && usedImportRuleTag) {\n      // $FlowFixMe\n      getImportRuleTag().removeRules(`${id}-import`)\n    }\n  }\n\n  const css = () => {\n    let str = ''\n    // eslint-disable-next-line guard-for-in\n    for (const id in markers) {\n      str += markers[id].data\n    }\n    return str\n  }\n\n  return {\n    clone() {\n      throw new StyledError(5)\n    },\n    css,\n    getIds: getIdsFromMarkersFactory(markers),\n    hasNameForId: hasNameForId(names),\n    insertMarker,\n    insertRules,\n    removeRules,\n    sealed: false,\n    styleTag: el,\n    toElement: wrapAsElement(css, names),\n    toHTML: wrapAsHtmlTag(css, names),\n  }\n}\n\nconst makeServerTagInternal = (namesArg, markersArg): Tag<[string]> => {\n  const names =\n    namesArg === undefined ? (Object.create(null): Object) : namesArg\n  const markers = markersArg === undefined ? Object.create(null) : markersArg\n\n  const insertMarker = id => {\n    const prev = markers[id]\n    if (prev !== undefined) {\n      return prev\n    }\n\n    return (markers[id] = [''])\n  }\n\n  const insertRules = (id, cssRules, name) => {\n    const marker = insertMarker(id)\n    marker[0] += cssRules.join(' ')\n    addNameForId(names, id, name)\n  }\n\n  const removeRules = id => {\n    const marker = markers[id]\n    if (marker === undefined) return\n    marker[0] = ''\n    resetIdNames(names, id)\n  }\n\n  const css = () => {\n    let str = ''\n    // eslint-disable-next-line guard-for-in\n    for (const id in markers) {\n      const cssForId = markers[id][0]\n      if (cssForId) {\n        str += makeTextMarker(id) + cssForId\n      }\n    }\n    return str\n  }\n\n  const clone = () => {\n    const namesClone = cloneNames(names)\n    const markersClone = Object.create(null)\n\n    // eslint-disable-next-line guard-for-in\n    for (const id in markers) {\n      markersClone[id] = [markers[id][0]]\n    }\n\n    return makeServerTagInternal(namesClone, markersClone)\n  }\n\n  const tag = {\n    clone,\n    css,\n    getIds: getIdsFromMarkersFactory(markers),\n    hasNameForId: hasNameForId(names),\n    insertMarker,\n    insertRules,\n    removeRules,\n    sealed: false,\n    styleTag: null,\n    toElement: wrapAsElement(css, names),\n    toHTML: wrapAsHtmlTag(css, names),\n  }\n\n  return tag\n}\n\nconst makeServerTag = (): Tag<[string]> => makeServerTagInternal()\n\nexport const makeTag = (\n  target: ?HTMLElement,\n  tagEl: ?HTMLStyleElement,\n  forceServer?: boolean,\n  insertBefore?: boolean,\n  getImportRuleTag?: () => Tag<any>\n): Tag<any> => {\n  if (IS_BROWSER && !forceServer) {\n    const el = makeStyleTag(target, tagEl, insertBefore)\n\n    if (DISABLE_SPEEDY) {\n      return makeBrowserTag(el, getImportRuleTag)\n    } else {\n      return makeSpeedyTag(el, getImportRuleTag)\n    }\n  }\n\n  return makeServerTag()\n}\n\n/* wraps a given tag so that rehydration is performed once when necessary */\nexport const makeRehydrationTag = (\n  tag: Tag<any>,\n  els: HTMLStyleElement[],\n  extracted: ExtractedComp[],\n  immediateRehydration: boolean\n): Tag<any> => {\n  /* rehydration function that adds all rules to the new tag */\n  const rehydrate = once(() => {\n    /* add all extracted components to the new tag */\n    for (let i = 0, len = extracted.length; i < len; i += 1) {\n      const { componentId, cssFromDOM } = extracted[i]\n      const cssRules = splitByRules(cssFromDOM)\n      tag.insertRules(componentId, cssRules)\n    }\n\n    /* remove old HTMLStyleElements, since they have been rehydrated */\n    for (let i = 0, len = els.length; i < len; i += 1) {\n      const el = els[i]\n      if (el.parentNode) {\n        el.parentNode.removeChild(el)\n      }\n    }\n  })\n\n  if (immediateRehydration) rehydrate()\n\n  return {\n    ...tag,\n    /* add rehydration hook to insertion methods */\n    insertMarker: id => {\n      rehydrate()\n      return tag.insertMarker(id)\n    },\n    insertRules: (id, cssRules, name) => {\n      rehydrate()\n      return tag.insertRules(id, cssRules, name)\n    },\n  }\n}\n",
         "// @flow\nimport React, { Component } from 'react'\nimport PropTypes from 'prop-types'\nimport StyleSheet from './StyleSheet'\nimport ServerStyleSheet from './ServerStyleSheet'\nimport { CONTEXT_KEY } from '../constants'\nimport StyledError from '../utils/error'\n\ntype Props = {\n  sheet?: StyleSheet | null,\n  target?: HTMLElement | null,\n}\n\nexport default class StyleSheetManager extends Component<Props, void> {\n  static childContextTypes = {\n    [CONTEXT_KEY]: PropTypes.oneOfType([\n      PropTypes.instanceOf(StyleSheet),\n      PropTypes.instanceOf(ServerStyleSheet),\n    ]).isRequired,\n  }\n\n  static propTypes = {\n    sheet: PropTypes.oneOfType([\n      PropTypes.instanceOf(StyleSheet),\n      PropTypes.instanceOf(ServerStyleSheet),\n    ]),\n    target: PropTypes.shape({\n      appendChild: PropTypes.func.isRequired,\n    }),\n  }\n\n  sheetInstance: StyleSheet\n\n  getChildContext() {\n    return { [CONTEXT_KEY]: this.sheetInstance }\n  }\n\n  componentWillMount() {\n    if (this.props.sheet) {\n      this.sheetInstance = this.props.sheet\n    } else if (this.props.target) {\n      this.sheetInstance = new StyleSheet(this.props.target)\n    } else {\n      throw new StyledError(4)\n    }\n  }\n\n  render() {\n    /* eslint-disable react/prop-types */\n    // Flow v0.43.1 will report an error accessing the `children` property,\n    // but v0.47.0 will not. It is necessary to use a type cast instead of\n    // a \"fixme\" comment to satisfy both Flow versions.\n    return React.Children.only((this.props: any).children)\n  }\n}\n",
         "// @flow\n\nimport hoist from 'hoist-non-react-statics'\nimport PropTypes from 'prop-types'\nimport { Component, createElement } from 'react'\nimport { CONTEXT_KEY } from '../constants'\nimport createWarnTooManyClasses from '../utils/createWarnTooManyClasses'\nimport determineTheme from '../utils/determineTheme'\nimport { EMPTY_OBJECT } from '../utils/empties'\nimport escape from '../utils/escape'\nimport generateDisplayName from '../utils/generateDisplayName'\nimport getComponentName from '../utils/getComponentName'\nimport isStyledComponent from '../utils/isStyledComponent'\nimport isTag from '../utils/isTag'\nimport validAttr from '../utils/validAttr'\nimport hasInInheritanceChain from '../utils/hasInInheritanceChain'\nimport once from '../utils/once'\nimport ServerStyleSheet from './ServerStyleSheet'\nimport StyleSheet from './StyleSheet'\nimport { CHANNEL_NEXT, contextShape } from './ThemeProvider'\n\nimport type { Theme } from './ThemeProvider'\nimport type { RuleSet, Target } from '../types'\n\n// HACK for generating all static styles without needing to allocate\n// an empty execution context every single time...\nconst STATIC_EXECUTION_CONTEXT = {}\n\ntype BaseState = {\n  theme?: ?Theme,\n  generatedClassName?: string,\n}\n\nconst modifiedContextShape = {\n  ...contextShape,\n  [CONTEXT_KEY]: PropTypes.oneOfType([\n    PropTypes.instanceOf(StyleSheet),\n    PropTypes.instanceOf(ServerStyleSheet),\n  ]),\n}\n\nconst identifiers = {}\n\n/* We depend on components having unique IDs */\nconst generateId = (\n  ComponentStyle: Function,\n  _displayName: string,\n  parentComponentId: string\n) => {\n  const displayName =\n    typeof _displayName !== 'string' ? 'sc' : escape(_displayName)\n\n  /**\n   * This ensures uniqueness if two components happen to share\n   * the same displayName.\n   */\n  const nr = (identifiers[displayName] || 0) + 1\n  identifiers[displayName] = nr\n\n  const componentId = `${displayName}-${ComponentStyle.generateName(\n    displayName + nr\n  )}`\n\n  return parentComponentId !== undefined\n    ? `${parentComponentId}-${componentId}`\n    : componentId\n}\n\nlet warnExtendDeprecated = () => {}\nif (process.env.NODE_ENV !== 'production') {\n  warnExtendDeprecated = once(() => {\n    // eslint-disable-next-line no-console\n    console.warn(\n      'Warning: The \"extend\" API will be removed in the upcoming v4.0 release. Use styled(StyledComponent) instead. You can find more information here: https://github.com/styled-components/styled-components/issues/1546'\n    )\n  })\n}\n\n// $FlowFixMe\nclass BaseStyledComponent extends Component<*, BaseState> {\n  static target: Target\n  static styledComponentId: string\n  static attrs: Object\n  static componentStyle: Object\n  static defaultProps: Object\n  static warnTooManyClasses: Function\n\n  attrs = {}\n  state = {\n    theme: null,\n    generatedClassName: '',\n  }\n  unsubscribeId: number = -1\n\n  unsubscribeFromContext() {\n    if (this.unsubscribeId !== -1) {\n      this.context[CHANNEL_NEXT].unsubscribe(this.unsubscribeId)\n    }\n  }\n\n  buildExecutionContext(theme: any, props: any) {\n    const { attrs } = this.constructor\n    const context = { ...props, theme }\n    if (attrs === undefined) {\n      return context\n    }\n\n    this.attrs = Object.keys(attrs).reduce((acc, key) => {\n      const attr = attrs[key]\n\n      // eslint-disable-next-line no-param-reassign\n      acc[key] =\n        typeof attr === 'function' && !hasInInheritanceChain(attr, Component)\n          ? attr(context)\n          : attr\n      return acc\n    }, {})\n\n    return { ...context, ...this.attrs }\n  }\n\n  generateAndInjectStyles(theme: any, props: any) {\n    const { attrs, componentStyle, warnTooManyClasses } = this.constructor\n    const styleSheet = this.context[CONTEXT_KEY] || StyleSheet.master\n\n    // statically styled-components don't need to build an execution context object,\n    // and shouldn't be increasing the number of class names\n    if (componentStyle.isStatic && attrs === undefined) {\n      return componentStyle.generateAndInjectStyles(\n        STATIC_EXECUTION_CONTEXT,\n        styleSheet\n      )\n    } else {\n      const executionContext = this.buildExecutionContext(theme, props)\n      const className = componentStyle.generateAndInjectStyles(\n        executionContext,\n        styleSheet\n      )\n\n      if (\n        process.env.NODE_ENV !== 'production' &&\n        warnTooManyClasses !== undefined\n      ) {\n        warnTooManyClasses(className)\n      }\n\n      return className\n    }\n  }\n\n  componentWillMount() {\n    const { componentStyle } = this.constructor\n    const styledContext = this.context[CHANNEL_NEXT]\n\n    // If this is a statically-styled component, we don't need to the theme\n    // to generate or build styles.\n    if (componentStyle.isStatic) {\n      const generatedClassName = this.generateAndInjectStyles(\n        STATIC_EXECUTION_CONTEXT,\n        this.props\n      )\n      this.setState({ generatedClassName })\n      // If there is a theme in the context, subscribe to the event emitter. This\n      // is necessary due to pure components blocking context updates, this circumvents\n      // that by updating when an event is emitted\n    } else if (styledContext !== undefined) {\n      const { subscribe } = styledContext\n      this.unsubscribeId = subscribe(nextTheme => {\n        // This will be called once immediately\n        const theme = determineTheme(\n          this.props,\n          nextTheme,\n          this.constructor.defaultProps\n        )\n\n        const generatedClassName = this.generateAndInjectStyles(\n          theme,\n          this.props\n        )\n\n        this.setState({ theme, generatedClassName })\n      })\n    } else {\n      // eslint-disable-next-line react/prop-types\n      const theme = this.props.theme || EMPTY_OBJECT\n      const generatedClassName = this.generateAndInjectStyles(theme, this.props)\n      this.setState({ theme, generatedClassName })\n    }\n  }\n\n  componentWillReceiveProps(nextProps: { theme?: Theme, [key: string]: any }) {\n    // If this is a statically-styled component, we don't need to listen to\n    // props changes to update styles\n    const { componentStyle } = this.constructor\n    if (componentStyle.isStatic) {\n      return\n    }\n\n    this.setState(prevState => {\n      const theme = determineTheme(\n        nextProps,\n        prevState.theme,\n        this.constructor.defaultProps\n      )\n      const generatedClassName = this.generateAndInjectStyles(theme, nextProps)\n\n      return { theme, generatedClassName }\n    })\n  }\n\n  componentWillUnmount() {\n    this.unsubscribeFromContext()\n  }\n\n  render() {\n    // eslint-disable-next-line react/prop-types\n    const { innerRef } = this.props\n    const { generatedClassName } = this.state\n    const { styledComponentId, target } = this.constructor\n\n    const isTargetTag = isTag(target)\n\n    const className = [\n      // eslint-disable-next-line react/prop-types\n      this.props.className,\n      styledComponentId,\n      this.attrs.className,\n      generatedClassName,\n    ]\n      .filter(Boolean)\n      .join(' ')\n\n    const baseProps: Object = {\n      ...this.attrs,\n      className,\n    }\n\n    if (isStyledComponent(target)) {\n      baseProps.innerRef = innerRef\n    } else {\n      baseProps.ref = innerRef\n    }\n\n    const propsForElement = baseProps\n    let key\n\n    for (key in this.props) {\n      // Don't pass through non HTML tags through to HTML elements\n      // always omit innerRef\n      if (\n        key !== 'innerRef' &&\n        key !== 'className' &&\n        (!isTargetTag || validAttr(key))\n      ) {\n        propsForElement[key] =\n          key === 'style' && key in this.attrs\n            ? { ...this.attrs[key], ...this.props[key] }\n            : this.props[key]\n      }\n    }\n\n    return createElement(target, propsForElement)\n  }\n}\n\nexport default (ComponentStyle: Function, constructWithOptions: Function) => {\n  const createStyledComponent = (\n    target: Target,\n    options: Object,\n    rules: RuleSet\n  ) => {\n    const {\n      isClass = !isTag(target),\n      displayName = generateDisplayName(target),\n      componentId = generateId(\n        ComponentStyle,\n        options.displayName,\n        options.parentComponentId\n      ),\n      ParentComponent = BaseStyledComponent,\n      rules: extendingRules,\n      attrs,\n    } = options\n\n    const styledComponentId =\n      options.displayName && options.componentId\n        ? `${escape(options.displayName)}-${options.componentId}`\n        : options.componentId || componentId\n\n    const componentStyle = new ComponentStyle(\n      extendingRules === undefined ? rules : extendingRules.concat(rules),\n      attrs,\n      styledComponentId\n    )\n\n    class StyledComponent extends ParentComponent {\n      static attrs = attrs\n      static componentStyle = componentStyle\n      static contextTypes = modifiedContextShape\n      static displayName = displayName\n      static styledComponentId = styledComponentId\n      static target = target\n\n      static withComponent(tag: Target) {\n        const { componentId: previousComponentId, ...optionsToCopy } = options\n\n        const newComponentId =\n          previousComponentId &&\n          `${previousComponentId}-${\n            isTag(tag) ? tag : escape(getComponentName(tag))\n          }`\n\n        const newOptions = {\n          ...optionsToCopy,\n          componentId: newComponentId,\n          ParentComponent: StyledComponent,\n        }\n\n        return createStyledComponent(tag, newOptions, rules)\n      }\n\n      static get extend() {\n        const {\n          rules: rulesFromOptions,\n          componentId: parentComponentId,\n          ...optionsToCopy\n        } = options\n\n        const newRules =\n          rulesFromOptions === undefined\n            ? rules\n            : rulesFromOptions.concat(rules)\n\n        const newOptions = {\n          ...optionsToCopy,\n          rules: newRules,\n          parentComponentId,\n          ParentComponent: StyledComponent,\n        }\n\n        warnExtendDeprecated()\n\n        return constructWithOptions(createStyledComponent, target, newOptions)\n      }\n    }\n\n    if (process.env.NODE_ENV !== 'production') {\n      StyledComponent.warnTooManyClasses = createWarnTooManyClasses(displayName)\n    }\n\n    if (isClass) {\n      hoist(StyledComponent, target, {\n        // all SC-specific things should not be hoisted\n        attrs: true,\n        componentStyle: true,\n        displayName: true,\n        extend: true,\n        styledComponentId: true,\n        target: true,\n        warnTooManyClasses: true,\n        withComponent: true,\n      })\n    }\n\n    return StyledComponent\n  }\n\n  return createStyledComponent\n}\n",
         "// @flow\nimport hashStr from '../vendor/glamor/hash'\n\nimport type { RuleSet, NameGenerator, Flattener, Stringifier } from '../types'\nimport StyleSheet from './StyleSheet'\nimport { IS_BROWSER } from '../constants'\nimport isStyledComponent from '../utils/isStyledComponent'\n\nconst areStylesCacheable = IS_BROWSER\n\nconst isStaticRules = (rules: RuleSet, attrs?: Object): boolean => {\n  for (let i = 0, len = rules.length; i < len; i += 1) {\n    const rule = rules[i]\n\n    // recursive case\n    if (Array.isArray(rule) && !isStaticRules(rule)) {\n      return false\n    } else if (typeof rule === 'function' && !isStyledComponent(rule)) {\n      // functions are allowed to be static if they're just being\n      // used to get the classname of a nested styled component\n      return false\n    }\n  }\n\n  if (attrs !== undefined) {\n    // eslint-disable-next-line guard-for-in, no-restricted-syntax\n    for (const key in attrs) {\n      if (typeof attrs[key] === 'function') {\n        return false\n      }\n    }\n  }\n\n  return true\n}\n\nconst isHMREnabled =\n  typeof module !== 'undefined' &&\n  module.hot &&\n  process.env.NODE_ENV !== 'production'\n\n/*\n ComponentStyle is all the CSS-specific stuff, not\n the React-specific stuff.\n */\nexport default (\n  nameGenerator: NameGenerator,\n  flatten: Flattener,\n  stringifyRules: Stringifier\n) => {\n  /* combines hashStr (murmurhash) and nameGenerator for convenience */\n  const generateRuleHash = (str: string) => nameGenerator(hashStr(str))\n\n  class ComponentStyle {\n    rules: RuleSet\n    componentId: string\n    isStatic: boolean\n    lastClassName: ?string\n\n    constructor(rules: RuleSet, attrs?: Object, componentId: string) {\n      this.rules = rules\n      this.isStatic = !isHMREnabled && isStaticRules(rules, attrs)\n      this.componentId = componentId\n\n      if (!StyleSheet.master.hasId(componentId)) {\n        const placeholder =\n          process.env.NODE_ENV !== 'production' ? [`.${componentId} {}`] : []\n\n        StyleSheet.master.deferredInject(componentId, placeholder)\n      }\n    }\n\n    /*\n     * Flattens a rule set into valid CSS\n     * Hashes it, wraps the whole chunk in a .hash1234 {}\n     * Returns the hash to be injected on render()\n     * */\n    generateAndInjectStyles(executionContext: Object, styleSheet: StyleSheet) {\n      const { isStatic, componentId, lastClassName } = this\n      if (\n        areStylesCacheable &&\n        isStatic &&\n        lastClassName !== undefined &&\n        styleSheet.hasNameForId(componentId, ((lastClassName: any): string))\n      ) {\n        return lastClassName\n      }\n\n      const flatCSS = flatten(this.rules, executionContext)\n      const name = generateRuleHash(this.componentId + flatCSS.join(''))\n\n      if (!styleSheet.hasNameForId(componentId, name)) {\n        styleSheet.inject(\n          this.componentId,\n          stringifyRules(flatCSS, `.${name}`),\n          name\n        )\n      }\n\n      this.lastClassName = name\n      return name\n    }\n\n    static generateName(str: string): string {\n      return generateRuleHash(str)\n    }\n  }\n\n  return ComponentStyle\n}\n",
         "// @flow\nimport hashStr from '../vendor/glamor/hash'\nimport type { Interpolation, NameGenerator, Stringifier } from '../types'\nimport StyleSheet from '../models/StyleSheet'\n\nconst replaceWhitespace = (str: string): string => str.replace(/\\s|\\\\n/g, '')\n\ntype KeyframesFn = (\n  strings: Array<string>,\n  ...interpolations: Array<Interpolation>\n) => string\n\nexport default (\n  nameGenerator: NameGenerator,\n  stringifyRules: Stringifier,\n  css: Function\n): KeyframesFn => (...arr): string => {\n  const styleSheet = StyleSheet.master\n  const rules = css(...arr)\n  const name = nameGenerator(hashStr(replaceWhitespace(JSON.stringify(rules))))\n  const id = `sc-keyframes-${name}`\n\n  if (!styleSheet.hasNameForId(id, name)) {\n    styleSheet.inject(id, stringifyRules(rules, name, '@keyframes'), name)\n  }\n\n  return name\n}\n",
         "// @flow\nimport hashStr from '../vendor/glamor/hash'\nimport StyleSheet from '../models/StyleSheet'\nimport type { Interpolation, Stringifier } from '../types'\n\ntype InjectGlobalFn = (\n  strings: Array<string>,\n  ...interpolations: Array<Interpolation>\n) => void\n\nexport default (stringifyRules: Stringifier, css: Function) => {\n  const injectGlobal: InjectGlobalFn = (...args) => {\n    const styleSheet = StyleSheet.master\n    const rules = css(...args)\n    const hash = hashStr(JSON.stringify(rules))\n    const id = `sc-global-${hash}`\n\n    if (!styleSheet.hasId(id)) {\n      styleSheet.inject(id, stringifyRules(rules))\n    }\n  }\n\n  return injectGlobal\n}\n",
         "import toPropertyKey from \"./toPropertyKey.js\";\nexport default function _defineProperty(obj, key, value) {\n  key = toPropertyKey(key);\n  if (key in obj) {\n    Object.defineProperty(obj, key, {\n      value: value,\n      enumerable: true,\n      configurable: true,\n      writable: true\n    });\n  } else {\n    obj[key] = value;\n  }\n  return obj;\n}",
-        "'use strict';\n\nif (process.env.NODE_ENV === 'production') {\n  module.exports = require('./cjs/react-jsx-runtime.production.min.js');\n} else {\n  module.exports = require('./cjs/react-jsx-runtime.development.js');\n}\n",
         "export default function _typeof(obj) {\n  \"@babel/helpers - typeof\";\n\n  return _typeof = \"function\" == typeof Symbol && \"symbol\" == typeof Symbol.iterator ? function (obj) {\n    return typeof obj;\n  } : function (obj) {\n    return obj && \"function\" == typeof Symbol && obj.constructor === Symbol && obj !== Symbol.prototype ? \"symbol\" : typeof obj;\n  }, _typeof(obj);\n}",
         "import _typeof from \"./typeof.js\";\nimport assertThisInitialized from \"./assertThisInitialized.js\";\nexport default function _possibleConstructorReturn(self, call) {\n  if (call && (_typeof(call) === \"object\" || typeof call === \"function\")) {\n    return call;\n  } else if (call !== void 0) {\n    throw new TypeError(\"Derived constructors may only return object or undefined\");\n  }\n  return assertThisInitialized(self);\n}",
         "export default function _assertThisInitialized(self) {\n  if (self === void 0) {\n    throw new ReferenceError(\"this hasn't been initialised - super() hasn't been called\");\n  }\n  return self;\n}",
         "import arrayLikeToArray from \"./arrayLikeToArray.js\";\nexport default function _unsupportedIterableToArray(o, minLen) {\n  if (!o) return;\n  if (typeof o === \"string\") return arrayLikeToArray(o, minLen);\n  var n = Object.prototype.toString.call(o).slice(8, -1);\n  if (n === \"Object\" && o.constructor) n = o.constructor.name;\n  if (n === \"Map\" || n === \"Set\") return Array.from(o);\n  if (n === \"Arguments\" || /^(?:Ui|I)nt(?:8|16|32)(?:Clamped)?Array$/.test(n)) return arrayLikeToArray(o, minLen);\n}",
         "export default function _arrayLikeToArray(arr, len) {\n  if (len == null || len > arr.length) len = arr.length;\n  for (var i = 0, arr2 = new Array(len); i < len; i++) arr2[i] = arr[i];\n  return arr2;\n}",
         "export default function _setPrototypeOf(o, p) {\n  _setPrototypeOf = Object.setPrototypeOf ? Object.setPrototypeOf.bind() : function _setPrototypeOf(o, p) {\n    o.__proto__ = p;\n    return o;\n  };\n  return _setPrototypeOf(o, p);\n}",
         "export default function _isNativeReflectConstruct() {\n  if (typeof Reflect === \"undefined\" || !Reflect.construct) return false;\n  if (Reflect.construct.sham) return false;\n  if (typeof Proxy === \"function\") return true;\n  try {\n    Boolean.prototype.valueOf.call(Reflect.construct(Boolean, [], function () {}));\n    return true;\n  } catch (e) {\n    return false;\n  }\n}",
@@ -4161,18 +4172,14 @@
         "import _typeof from \"./typeof.js\";\nexport default function _toPrimitive(input, hint) {\n  if (_typeof(input) !== \"object\" || input === null) return input;\n  var prim = input[Symbol.toPrimitive];\n  if (prim !== undefined) {\n    var res = prim.call(input, hint || \"default\");\n    if (_typeof(res) !== \"object\") return res;\n    throw new TypeError(\"@@toPrimitive must return a primitive value.\");\n  }\n  return (hint === \"string\" ? String : Number)(input);\n}",
         "'use strict';\n\nif (process.env.NODE_ENV === 'production') {\n  module.exports = require('./cjs/react-is.production.min.js');\n} else {\n  module.exports = require('./cjs/react-is.development.js');\n}\n",
         "/*\n *          __        ___\n *    _____/ /___  __/ (_)____\n *   / ___/ __/ / / / / / ___/\n *  (__  ) /_/ /_/ / / (__  )\n * /____/\\__/\\__, /_/_/____/\n *          /____/\n *\n * light - weight css preprocessor @licence MIT\n */\n(function (factory) {/* eslint-disable */\n\ttypeof exports === 'object' && typeof module !== 'undefined' ? (module['exports'] = factory(null)) :\n\t\ttypeof define === 'function' && define['amd'] ? define(factory(null)) :\n\t\t\t(window['stylis'] = factory(null))\n}(/** @param {*=} options */function factory (options) {/* eslint-disable */\n\n\t'use strict'\n\n\t/**\n\t * Notes\n\t *\n\t * The ['<method name>'] pattern is used to support closure compiler\n\t * the jsdoc signatures are also used to the same effect\n\t *\n\t * ----\n\t *\n\t * int + int + int === n4 [faster]\n\t *\n\t * vs\n\t *\n\t * int === n1 && int === n2 && int === n3\n\t *\n\t * ----\n\t *\n\t * switch (int) { case ints...} [faster]\n\t *\n\t * vs\n\t *\n\t * if (int == 1 && int === 2 ...)\n\t *\n\t * ----\n\t *\n\t * The (first*n1 + second*n2 + third*n3) format used in the property parser\n\t * is a simple way to hash the sequence of characters\n\t * taking into account the index they occur in\n\t * since any number of 3 character sequences could produce duplicates.\n\t *\n\t * On the other hand sequences that are directly tied to the index of the character\n\t * resolve a far more accurate measure, it's also faster\n\t * to evaluate one condition in a switch statement\n\t * than three in an if statement regardless of the added math.\n\t *\n\t * This allows the vendor prefixer to be both small and fast.\n\t */\n\n\tvar nullptn = /^\\0+/g /* matches leading null characters */\n\tvar formatptn = /[\\0\\r\\f]/g /* matches new line, null and formfeed characters */\n\tvar colonptn = /: */g /* splits animation rules */\n\tvar cursorptn = /zoo|gra/ /* assert cursor varient */\n\tvar transformptn = /([,: ])(transform)/g /* vendor prefix transform, older webkit */\n\tvar animationptn = /,+\\s*(?![^(]*[)])/g /* splits multiple shorthand notation animations */\n\tvar propertiesptn = / +\\s*(?![^(]*[)])/g /* animation properties */\n\tvar elementptn = / *[\\0] */g /* selector elements */\n\tvar selectorptn = /,\\r+?/g /* splits selectors */\n\tvar andptn = /([\\t\\r\\n ])*\\f?&/g /* match & */\n\tvar escapeptn = /:global\\(((?:[^\\(\\)\\[\\]]*|\\[.*\\]|\\([^\\(\\)]*\\))*)\\)/g /* matches :global(.*) */\n\tvar invalidptn = /\\W+/g /* removes invalid characters from keyframes */\n\tvar keyframeptn = /@(k\\w+)\\s*(\\S*)\\s*/ /* matches @keyframes $1 */\n\tvar plcholdrptn = /::(place)/g /* match ::placeholder varient */\n\tvar readonlyptn = /:(read-only)/g /* match :read-only varient */\n\tvar beforeptn = /\\s+(?=[{\\];=:>])/g /* matches \\s before ] ; = : */\n\tvar afterptn = /([[}=:>])\\s+/g /* matches \\s after characters [ } = : */\n\tvar tailptn = /(\\{[^{]+?);(?=\\})/g /* matches tail semi-colons ;} */\n\tvar whiteptn = /\\s{2,}/g /* matches repeating whitespace */\n\tvar pseudoptn = /([^\\(])(:+) */g /* pseudo element */\n\tvar writingptn = /[svh]\\w+-[tblr]{2}/ /* match writing mode property values */\n\tvar gradientptn = /([\\w-]+t\\()/g /* match *gradient property */\n\tvar supportsptn = /\\(\\s*(.*)\\s*\\)/g /* match supports (groups) */\n\tvar propertyptn = /([\\s\\S]*?);/g /* match properties leading semicolon */\n\tvar selfptn = /-self|flex-/g /* match flex- and -self in align-self: flex-*; */\n\tvar pseudofmt = /[^]*?(:[rp][el]a[\\w-]+)[^]*/ /* extrats :readonly or :placholder from selector */\n\tvar trimptn = /[ \\t]+$/ /* match tail whitspace */\n\tvar dimensionptn = /stretch|:\\s*\\w+\\-(?:conte|avail)/ /* match max/min/fit-content, fill-available */\n\tvar imgsrcptn = /([^-])(image-set\\()/\n\n\t/* vendors */\n\tvar webkit = '-webkit-'\n\tvar moz = '-moz-'\n\tvar ms = '-ms-'\n\n\t/* character codes */\n\tvar SEMICOLON = 59 /* ; */\n\tvar CLOSEBRACES = 125 /* } */\n\tvar OPENBRACES = 123 /* { */\n\tvar OPENPARENTHESES = 40 /* ( */\n\tvar CLOSEPARENTHESES = 41 /* ) */\n\tvar OPENBRACKET = 91 /* [ */\n\tvar CLOSEBRACKET = 93 /* ] */\n\tvar NEWLINE = 10 /* \\n */\n\tvar CARRIAGE = 13 /* \\r */\n\tvar TAB = 9 /* \\t */\n\tvar AT = 64 /* @ */\n\tvar SPACE = 32 /*   */\n\tvar AND = 38 /* & */\n\tvar DASH = 45 /* - */\n\tvar UNDERSCORE = 95 /* _ */\n\tvar STAR = 42 /* * */\n\tvar COMMA = 44 /* , */\n\tvar COLON = 58 /* : */\n\tvar SINGLEQUOTE = 39 /* ' */\n\tvar DOUBLEQUOTE = 34 /* \" */\n\tvar FOWARDSLASH = 47 /* / */\n\tvar GREATERTHAN = 62 /* > */\n\tvar PLUS = 43 /* + */\n\tvar TILDE = 126 /* ~ */\n\tvar NULL = 0 /* \\0 */\n\tvar FORMFEED = 12 /* \\f */\n\tvar VERTICALTAB = 11 /* \\v */\n\n\t/* special identifiers */\n\tvar KEYFRAME = 107 /* k */\n\tvar MEDIA = 109 /* m */\n\tvar SUPPORTS = 115 /* s */\n\tvar PLACEHOLDER = 112 /* p */\n\tvar READONLY = 111 /* o */\n\tvar IMPORT = 105 /* <at>i */\n\tvar CHARSET = 99 /* <at>c */\n\tvar DOCUMENT = 100 /* <at>d */\n\tvar PAGE = 112 /* <at>p */\n\n\tvar column = 1 /* current column */\n\tvar line = 1 /* current line numebr */\n\tvar pattern = 0 /* :pattern */\n\n\tvar cascade = 1 /* #id h1 h2 vs h1#id h2#id  */\n\tvar prefix = 1 /* vendor prefix */\n\tvar escape = 1 /* escape :global() pattern */\n\tvar compress = 0 /* compress output */\n\tvar semicolon = 0 /* no/semicolon option */\n\tvar preserve = 0 /* preserve empty selectors */\n\n\t/* empty reference */\n\tvar array = []\n\n\t/* plugins */\n\tvar plugins = []\n\tvar plugged = 0\n\tvar should = null\n\n\t/* plugin context */\n\tvar POSTS = -2\n\tvar PREPS = -1\n\tvar UNKWN = 0\n\tvar PROPS = 1\n\tvar BLCKS = 2\n\tvar ATRUL = 3\n\n\t/* plugin newline context */\n\tvar unkwn = 0\n\n\t/* keyframe animation */\n\tvar keyed = 1\n\tvar key = ''\n\n\t/* selector namespace */\n\tvar nscopealt = ''\n\tvar nscope = ''\n\n\t/**\n\t * Compile\n\t *\n\t * @param {Array<string>} parent\n\t * @param {Array<string>} current\n\t * @param {string} body\n\t * @param {number} id\n\t * @param {number} depth\n\t * @return {string}\n\t */\n\tfunction compile (parent, current, body, id, depth) {\n\t\tvar bracket = 0 /* brackets [] */\n\t\tvar comment = 0 /* comments /* // or /* */\n\t\tvar parentheses = 0 /* functions () */\n\t\tvar quote = 0 /* quotes '', \"\" */\n\n\t\tvar first = 0 /* first character code */\n\t\tvar second = 0 /* second character code */\n\t\tvar code = 0 /* current character code */\n\t\tvar tail = 0 /* previous character code */\n\t\tvar trail = 0 /* character before previous code */\n\t\tvar peak = 0 /* previous non-whitespace code */\n\n\t\tvar counter = 0 /* count sequence termination */\n\t\tvar context = 0 /* track current context */\n\t\tvar atrule = 0 /* track @at-rule context */\n\t\tvar pseudo = 0 /* track pseudo token index */\n\t\tvar caret = 0 /* current character index */\n\t\tvar format = 0 /* control character formating context */\n\t\tvar insert = 0 /* auto semicolon insertion */\n\t\tvar invert = 0 /* inverted selector pattern */\n\t\tvar length = 0 /* generic length address */\n\t\tvar eof = body.length /* end of file(length) */\n\t\tvar eol = eof - 1 /* end of file(characters) */\n\n\t\tvar char = '' /* current character */\n\t\tvar chars = '' /* current buffer of characters */\n\t\tvar child = '' /* next buffer of characters */\n\t\tvar out = '' /* compiled body */\n\t\tvar children = '' /* compiled children */\n\t\tvar flat = '' /* compiled leafs */\n\t\tvar selector /* generic selector address */\n\t\tvar result /* generic address */\n\n\t\t// ...build body\n\t\twhile (caret < eof) {\n\t\t\tcode = body.charCodeAt(caret)\n\n\t\t\t// eof varient\n\t\t\tif (caret === eol) {\n\t\t\t\t// last character + noop context, add synthetic padding for noop context to terminate\n\t\t\t\tif (comment + quote + parentheses + bracket !== 0) {\n\t\t\t\t\tif (comment !== 0) {\n\t\t\t\t\t\tcode = comment === FOWARDSLASH ? NEWLINE : FOWARDSLASH\n\t\t\t\t\t}\n\n\t\t\t\t\tquote = parentheses = bracket = 0\n\t\t\t\t\teof++\n\t\t\t\t\teol++\n\t\t\t\t}\n\t\t\t}\n\n\t\t\tif (comment + quote + parentheses + bracket === 0) {\n\t\t\t\t// eof varient\n\t\t\t\tif (caret === eol) {\n\t\t\t\t\tif (format > 0) {\n\t\t\t\t\t\tchars = chars.replace(formatptn, '')\n\t\t\t\t\t}\n\n\t\t\t\t\tif (chars.trim().length > 0) {\n\t\t\t\t\t\tswitch (code) {\n\t\t\t\t\t\t\tcase SPACE:\n\t\t\t\t\t\t\tcase TAB:\n\t\t\t\t\t\t\tcase SEMICOLON:\n\t\t\t\t\t\t\tcase CARRIAGE:\n\t\t\t\t\t\t\tcase NEWLINE: {\n\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\t\tchars += body.charAt(caret)\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t}\n\n\t\t\t\t\t\tcode = SEMICOLON\n\t\t\t\t\t}\n\t\t\t\t}\n\n\t\t\t\t// auto semicolon insertion\n\t\t\t\tif (insert === 1) {\n\t\t\t\t\tswitch (code) {\n\t\t\t\t\t\t// false flags\n\t\t\t\t\t\tcase OPENBRACES:\n\t\t\t\t\t\tcase CLOSEBRACES:\n\t\t\t\t\t\tcase SEMICOLON:\n\t\t\t\t\t\tcase DOUBLEQUOTE:\n\t\t\t\t\t\tcase SINGLEQUOTE:\n\t\t\t\t\t\tcase OPENPARENTHESES:\n\t\t\t\t\t\tcase CLOSEPARENTHESES:\n\t\t\t\t\t\tcase COMMA: {\n\t\t\t\t\t\t\tinsert = 0\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// ignore\n\t\t\t\t\t\tcase TAB:\n\t\t\t\t\t\tcase CARRIAGE:\n\t\t\t\t\t\tcase NEWLINE:\n\t\t\t\t\t\tcase SPACE: {\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// valid\n\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\tinsert = 0\n\t\t\t\t\t\t\tlength = caret\n\t\t\t\t\t\t\tfirst = code\n\t\t\t\t\t\t\tcaret--\n\t\t\t\t\t\t\tcode = SEMICOLON\n\n\t\t\t\t\t\t\twhile (length < eof) {\n\t\t\t\t\t\t\t\tswitch (body.charCodeAt(length++)) {\n\t\t\t\t\t\t\t\t\tcase NEWLINE:\n\t\t\t\t\t\t\t\t\tcase CARRIAGE:\n\t\t\t\t\t\t\t\t\tcase SEMICOLON: {\n\t\t\t\t\t\t\t\t\t\t++caret\n\t\t\t\t\t\t\t\t\t\tcode = first\n\t\t\t\t\t\t\t\t\t\tlength = eof\n\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\tcase COLON: {\n\t\t\t\t\t\t\t\t\t\tif (format > 0) {\n\t\t\t\t\t\t\t\t\t\t\t++caret\n\t\t\t\t\t\t\t\t\t\t\tcode = first\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\tcase OPENBRACES: {\n\t\t\t\t\t\t\t\t\t\tlength = eof\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t}\n\t\t\t\t\t}\n\t\t\t\t}\n\n\t\t\t\t// token varient\n\t\t\t\tswitch (code) {\n\t\t\t\t\tcase OPENBRACES: {\n\t\t\t\t\t\tchars = chars.trim()\n\t\t\t\t\t\tfirst = chars.charCodeAt(0)\n\t\t\t\t\t\tcounter = 1\n\t\t\t\t\t\tlength = ++caret\n\n\t\t\t\t\t\twhile (caret < eof) {\n\t\t\t\t\t\t\tswitch (code = body.charCodeAt(caret)) {\n\t\t\t\t\t\t\t\tcase OPENBRACES: {\n\t\t\t\t\t\t\t\t\tcounter++\n\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\tcase CLOSEBRACES: {\n\t\t\t\t\t\t\t\t\tcounter--\n\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\tcase FOWARDSLASH: {\n\t\t\t\t\t\t\t\t\tswitch (second = body.charCodeAt(caret + 1)) {\n\t\t\t\t\t\t\t\t\t\t// /*, //\n\t\t\t\t\t\t\t\t\t\tcase STAR:\n\t\t\t\t\t\t\t\t\t\tcase FOWARDSLASH: {\n\t\t\t\t\t\t\t\t\t\t\tcaret = delimited(second, caret, eol, body)\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t// given \"[\" === 91 & \"]\" === 93 hence forth 91 + 1 + 1 === 93\n\t\t\t\t\t\t\t\tcase OPENBRACKET: {\n\t\t\t\t\t\t\t\t\tcode++\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t// given \"(\" === 40 & \")\" === 41 hence forth 40 + 1 === 41\n\t\t\t\t\t\t\t\tcase OPENPARENTHESES: {\n\t\t\t\t\t\t\t\t\tcode++\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t// quote tail delimiter is identical to the head delimiter hence noop,\n\t\t\t\t\t\t\t\t// fallthrough clauses have been shifted to the correct tail delimiter\n\t\t\t\t\t\t\t\tcase DOUBLEQUOTE:\n\t\t\t\t\t\t\t\tcase SINGLEQUOTE: {\n\t\t\t\t\t\t\t\t\twhile (caret++ < eol) {\n\t\t\t\t\t\t\t\t\t\tif (body.charCodeAt(caret) === code) {\n\t\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\n\t\t\t\t\t\t\tif (counter === 0) {\n\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t}\n\n\t\t\t\t\t\t\tcaret++\n\t\t\t\t\t\t}\n\n\t\t\t\t\t\tchild = body.substring(length, caret)\n\n\t\t\t\t\t\tif (first === NULL) {\n\t\t\t\t\t\t\tfirst = (chars = chars.replace(nullptn, '').trim()).charCodeAt(0)\n\t\t\t\t\t\t}\n\n\t\t\t\t\t\tswitch (first) {\n\t\t\t\t\t\t\t// @at-rule\n\t\t\t\t\t\t\tcase AT: {\n\t\t\t\t\t\t\t\tif (format > 0) {\n\t\t\t\t\t\t\t\t\tchars = chars.replace(formatptn, '')\n\t\t\t\t\t\t\t\t}\n\n\t\t\t\t\t\t\t\tsecond = chars.charCodeAt(1)\n\n\t\t\t\t\t\t\t\tswitch (second) {\n\t\t\t\t\t\t\t\t\tcase DOCUMENT:\n\t\t\t\t\t\t\t\t\tcase MEDIA:\n\t\t\t\t\t\t\t\t\tcase SUPPORTS:\n\t\t\t\t\t\t\t\t\tcase DASH: {\n\t\t\t\t\t\t\t\t\t\tselector = current\n\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\t\t\t\tselector = array\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t}\n\n\t\t\t\t\t\t\t\tchild = compile(current, selector, child, second, depth+1)\n\t\t\t\t\t\t\t\tlength = child.length\n\n\t\t\t\t\t\t\t\t// preserve empty @at-rule\n\t\t\t\t\t\t\t\tif (preserve > 0 && length === 0) {\n\t\t\t\t\t\t\t\t\tlength = chars.length\n\t\t\t\t\t\t\t\t}\n\n\t\t\t\t\t\t\t\t// execute plugins, @at-rule context\n\t\t\t\t\t\t\t\tif (plugged > 0) {\n\t\t\t\t\t\t\t\t\tselector = select(array, chars, invert)\n\t\t\t\t\t\t\t\t\tresult = proxy(ATRUL, child, selector, current, line, column, length, second, depth, id)\n\t\t\t\t\t\t\t\t\tchars = selector.join('')\n\n\t\t\t\t\t\t\t\t\tif (result !== void 0) {\n\t\t\t\t\t\t\t\t\t\tif ((length = (child = result.trim()).length) === 0) {\n\t\t\t\t\t\t\t\t\t\t\tsecond = 0\n\t\t\t\t\t\t\t\t\t\t\tchild = ''\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t}\n\n\t\t\t\t\t\t\t\tif (length > 0) {\n\t\t\t\t\t\t\t\t\tswitch (second) {\n\t\t\t\t\t\t\t\t\t\tcase SUPPORTS: {\n\t\t\t\t\t\t\t\t\t\t\tchars = chars.replace(supportsptn, supports)\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\tcase DOCUMENT:\n\t\t\t\t\t\t\t\t\t\tcase MEDIA:\n\t\t\t\t\t\t\t\t\t\tcase DASH: {\n\t\t\t\t\t\t\t\t\t\t\tchild = chars + '{' + child + '}'\n\t\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\tcase KEYFRAME: {\n\t\t\t\t\t\t\t\t\t\t\tchars = chars.replace(keyframeptn, '$1 $2' + (keyed > 0 ? key : ''))\n\t\t\t\t\t\t\t\t\t\t\tchild = chars + '{' + child + '}'\n\n\t\t\t\t\t\t\t\t\t\t\tif (prefix === 1 || (prefix === 2 && vendor('@'+child, 3))) {\n\t\t\t\t\t\t\t\t\t\t\t\tchild = '@' + webkit + child + '@' + child\n\t\t\t\t\t\t\t\t\t\t\t} else {\n\t\t\t\t\t\t\t\t\t\t\t\tchild = '@' + child\n\t\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\t\t\t\t\tchild = chars + child\n\n\t\t\t\t\t\t\t\t\t\t\tif (id === PAGE) {\n\t\t\t\t\t\t\t\t\t\t\t\tchild = (out += child, '')\n\t\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t} else {\n\t\t\t\t\t\t\t\t\tchild = ''\n\t\t\t\t\t\t\t\t}\n\n\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t// selector\n\t\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\t\tchild = compile(current, select(current, chars, invert), child, id, depth+1)\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t}\n\n\t\t\t\t\t\tchildren += child\n\n\t\t\t\t\t\t// reset\n\t\t\t\t\t\tcontext = 0\n\t\t\t\t\t\tinsert = 0\n\t\t\t\t\t\tpseudo = 0\n\t\t\t\t\t\tformat = 0\n\t\t\t\t\t\tinvert = 0\n\t\t\t\t\t\tatrule = 0\n\t\t\t\t\t\tchars = ''\n\t\t\t\t\t\tchild = ''\n\t\t\t\t\t\tcode = body.charCodeAt(++caret)\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t\tcase CLOSEBRACES:\n\t\t\t\t\tcase SEMICOLON: {\n\t\t\t\t\t\tchars = (format > 0 ? chars.replace(formatptn, '') : chars).trim()\n\n\t\t\t\t\t\tif ((length = chars.length) > 1) {\n\t\t\t\t\t\t\t// monkey-patch missing colon\n\t\t\t\t\t\t\tif (pseudo === 0) {\n\t\t\t\t\t\t\t\tfirst = chars.charCodeAt(0)\n\n\t\t\t\t\t\t\t\t// first character is a letter or dash, buffer has a space character\n\t\t\t\t\t\t\t\tif ((first === DASH || first > 96 && first < 123)) {\n\t\t\t\t\t\t\t\t\tlength = (chars = chars.replace(' ', ':')).length\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\n\t\t\t\t\t\t\t// execute plugins, property context\n\t\t\t\t\t\t\tif (plugged > 0) {\n\t\t\t\t\t\t\t\tif ((result = proxy(PROPS, chars, current, parent, line, column, out.length, id, depth, id)) !== void 0) {\n\t\t\t\t\t\t\t\t\tif ((length = (chars = result.trim()).length) === 0) {\n\t\t\t\t\t\t\t\t\t\tchars = '\\0\\0'\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\n\t\t\t\t\t\t\tfirst = chars.charCodeAt(0)\n\t\t\t\t\t\t\tsecond = chars.charCodeAt(1)\n\n\t\t\t\t\t\t\tswitch (first) {\n\t\t\t\t\t\t\t\tcase NULL: {\n\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\tcase AT: {\n\t\t\t\t\t\t\t\t\tif (second === IMPORT || second === CHARSET) {\n\t\t\t\t\t\t\t\t\t\tflat += chars + body.charAt(caret)\n\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\t\t\tif (chars.charCodeAt(length-1) === COLON) {\n\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t}\n\n\t\t\t\t\t\t\t\t\tout += property(chars, first, second, chars.charCodeAt(2))\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t}\n\n\t\t\t\t\t\t// reset\n\t\t\t\t\t\tcontext = 0\n\t\t\t\t\t\tinsert = 0\n\t\t\t\t\t\tpseudo = 0\n\t\t\t\t\t\tformat = 0\n\t\t\t\t\t\tinvert = 0\n\t\t\t\t\t\tchars = ''\n\t\t\t\t\t\tcode = body.charCodeAt(++caret)\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t}\n\t\t\t}\n\n\t\t\t// parse characters\n\t\t\tswitch (code) {\n\t\t\t\tcase CARRIAGE:\n\t\t\t\tcase NEWLINE: {\n\t\t\t\t\t// auto insert semicolon\n\t\t\t\t\tif (comment + quote + parentheses + bracket + semicolon === 0) {\n\t\t\t\t\t\t// valid non-whitespace characters that\n\t\t\t\t\t\t// may precede a newline\n\t\t\t\t\t\tswitch (peak) {\n\t\t\t\t\t\t\tcase CLOSEPARENTHESES:\n\t\t\t\t\t\t\tcase SINGLEQUOTE:\n\t\t\t\t\t\t\tcase DOUBLEQUOTE:\n\t\t\t\t\t\t\tcase AT:\n\t\t\t\t\t\t\tcase TILDE:\n\t\t\t\t\t\t\tcase GREATERTHAN:\n\t\t\t\t\t\t\tcase STAR:\n\t\t\t\t\t\t\tcase PLUS:\n\t\t\t\t\t\t\tcase FOWARDSLASH:\n\t\t\t\t\t\t\tcase DASH:\n\t\t\t\t\t\t\tcase COLON:\n\t\t\t\t\t\t\tcase COMMA:\n\t\t\t\t\t\t\tcase SEMICOLON:\n\t\t\t\t\t\t\tcase OPENBRACES:\n\t\t\t\t\t\t\tcase CLOSEBRACES: {\n\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\t\t// current buffer has a colon\n\t\t\t\t\t\t\t\tif (pseudo > 0) {\n\t\t\t\t\t\t\t\t\tinsert = 1\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t}\n\t\t\t\t\t}\n\n\t\t\t\t\t// terminate line comment\n\t\t\t\t\tif (comment === FOWARDSLASH) {\n\t\t\t\t\t\tcomment = 0\n\t\t\t\t\t} else if (cascade + context === 0 && id !== KEYFRAME && chars.length > 0) {\n\t\t\t\t\t\tformat = 1\n\t\t\t\t\t\tchars += '\\0'\n\t\t\t\t\t}\n\n\t\t\t\t\t// execute plugins, newline context\n\t\t\t\t\tif (plugged * unkwn > 0) {\n\t\t\t\t\t\tproxy(UNKWN, chars, current, parent, line, column, out.length, id, depth, id)\n\t\t\t\t\t}\n\n\t\t\t\t\t// next line, reset column position\n\t\t\t\t\tcolumn = 1\n\t\t\t\t\tline++\n\t\t\t\t\tbreak\n\t\t\t\t}\n\t\t\t\tcase SEMICOLON:\n\t\t\t\tcase CLOSEBRACES: {\n\t\t\t\t\tif (comment + quote + parentheses + bracket === 0) {\n\t\t\t\t\t\tcolumn++\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t}\n\t\t\t\tdefault: {\n\t\t\t\t\t// increment column position\n\t\t\t\t\tcolumn++\n\n\t\t\t\t\t// current character\n\t\t\t\t\tchar = body.charAt(caret)\n\n\t\t\t\t\t// remove comments, escape functions, strings, attributes and prepare selectors\n\t\t\t\t\tswitch (code) {\n\t\t\t\t\t\tcase TAB:\n\t\t\t\t\t\tcase SPACE: {\n\t\t\t\t\t\t\tif (quote + bracket + comment === 0) {\n\t\t\t\t\t\t\t\tswitch (tail) {\n\t\t\t\t\t\t\t\t\tcase COMMA:\n\t\t\t\t\t\t\t\t\tcase COLON:\n\t\t\t\t\t\t\t\t\tcase TAB:\n\t\t\t\t\t\t\t\t\tcase SPACE: {\n\t\t\t\t\t\t\t\t\t\tchar = ''\n\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\t\t\t\tif (code !== SPACE) {\n\t\t\t\t\t\t\t\t\t\t\tchar = ' '\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// escape breaking control characters\n\t\t\t\t\t\tcase NULL: {\n\t\t\t\t\t\t\tchar = '\\\\0'\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\tcase FORMFEED: {\n\t\t\t\t\t\t\tchar = '\\\\f'\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\tcase VERTICALTAB: {\n\t\t\t\t\t\t\tchar = '\\\\v'\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// &\n\t\t\t\t\t\tcase AND: {\n\t\t\t\t\t\t\t// inverted selector pattern i.e html &\n\t\t\t\t\t\t\tif (quote + comment + bracket === 0 && cascade > 0) {\n\t\t\t\t\t\t\t\tinvert = 1\n\t\t\t\t\t\t\t\tformat = 1\n\t\t\t\t\t\t\t\tchar = '\\f' + char\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// ::p<l>aceholder, l\n\t\t\t\t\t\t// :read-on<l>y, l\n\t\t\t\t\t\tcase 108: {\n\t\t\t\t\t\t\tif (quote + comment + bracket + pattern === 0 && pseudo > 0) {\n\t\t\t\t\t\t\t\tswitch (caret - pseudo) {\n\t\t\t\t\t\t\t\t\t// ::placeholder\n\t\t\t\t\t\t\t\t\tcase 2: {\n\t\t\t\t\t\t\t\t\t\tif (tail === PLACEHOLDER && body.charCodeAt(caret-3) === COLON) {\n\t\t\t\t\t\t\t\t\t\t\tpattern = tail\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t// :read-only\n\t\t\t\t\t\t\t\t\tcase 8: {\n\t\t\t\t\t\t\t\t\t\tif (trail === READONLY) {\n\t\t\t\t\t\t\t\t\t\t\tpattern = trail\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// :<pattern>\n\t\t\t\t\t\tcase COLON: {\n\t\t\t\t\t\t\tif (quote + comment + bracket === 0) {\n\t\t\t\t\t\t\t\tpseudo = caret\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// selectors\n\t\t\t\t\t\tcase COMMA: {\n\t\t\t\t\t\t\tif (comment + parentheses + quote + bracket === 0) {\n\t\t\t\t\t\t\t\tformat = 1\n\t\t\t\t\t\t\t\tchar += '\\r'\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// quotes\n\t\t\t\t\t\tcase DOUBLEQUOTE:\n\t\t\t\t\t\tcase SINGLEQUOTE: {\n\t\t\t\t\t\t\tif (comment === 0) {\n\t\t\t\t\t\t\t\tquote = quote === code ? 0 : (quote === 0 ? code : quote)\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// attributes\n\t\t\t\t\t\tcase OPENBRACKET: {\n\t\t\t\t\t\t\tif (quote + comment + parentheses === 0) {\n\t\t\t\t\t\t\t\tbracket++\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\tcase CLOSEBRACKET: {\n\t\t\t\t\t\t\tif (quote + comment + parentheses === 0) {\n\t\t\t\t\t\t\t\tbracket--\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// functions\n\t\t\t\t\t\tcase CLOSEPARENTHESES: {\n\t\t\t\t\t\t\tif (quote + comment + bracket === 0) {\n\t\t\t\t\t\t\t\tparentheses--\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\tcase OPENPARENTHESES: {\n\t\t\t\t\t\t\tif (quote + comment + bracket === 0) {\n\t\t\t\t\t\t\t\tif (context === 0) {\n\t\t\t\t\t\t\t\t\tswitch (tail*2 + trail*3) {\n\t\t\t\t\t\t\t\t\t\t// :matches\n\t\t\t\t\t\t\t\t\t\tcase 533: {\n\t\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\t// :global, :not, :nth-child etc...\n\t\t\t\t\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\t\t\t\t\tcounter = 0\n\t\t\t\t\t\t\t\t\t\t\tcontext = 1\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t}\n\n\t\t\t\t\t\t\t\tparentheses++\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\tcase AT: {\n\t\t\t\t\t\t\tif (comment + parentheses + quote + bracket + pseudo + atrule === 0) {\n\t\t\t\t\t\t\t\tatrule = 1\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// block/line comments\n\t\t\t\t\t\tcase STAR:\n\t\t\t\t\t\tcase FOWARDSLASH: {\n\t\t\t\t\t\t\tif (quote + bracket + parentheses > 0) {\n\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t}\n\n\t\t\t\t\t\t\tswitch (comment) {\n\t\t\t\t\t\t\t\t// initialize line/block comment context\n\t\t\t\t\t\t\t\tcase 0: {\n\t\t\t\t\t\t\t\t\tswitch (code*2 + body.charCodeAt(caret+1)*3) {\n\t\t\t\t\t\t\t\t\t\t// //\n\t\t\t\t\t\t\t\t\t\tcase 235: {\n\t\t\t\t\t\t\t\t\t\t\tcomment = FOWARDSLASH\n\t\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\t// /*\n\t\t\t\t\t\t\t\t\t\tcase 220: {\n\t\t\t\t\t\t\t\t\t\t\tlength = caret\n\t\t\t\t\t\t\t\t\t\t\tcomment = STAR\n\t\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t// end block comment context\n\t\t\t\t\t\t\t\tcase STAR: {\n\t\t\t\t\t\t\t\t\tif (code === FOWARDSLASH && tail === STAR && length + 2 !== caret) {\n\t\t\t\t\t\t\t\t\t\t// /*<!> ... */, !\n\t\t\t\t\t\t\t\t\t\tif (body.charCodeAt(length+2) === 33) {\n\t\t\t\t\t\t\t\t\t\t\tout += body.substring(length, caret+1)\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\tchar = ''\n\t\t\t\t\t\t\t\t\t\tcomment = 0\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t}\n\t\t\t\t\t}\n\n\t\t\t\t\t// ignore comment blocks\n\t\t\t\t\tif (comment === 0) {\n\t\t\t\t\t\t// aggressive isolation mode, divide each individual selector\n\t\t\t\t\t\t// including selectors in :not function but excluding selectors in :global function\n\t\t\t\t\t\tif (cascade + quote + bracket + atrule === 0 && id !== KEYFRAME && code !== SEMICOLON) {\n\t\t\t\t\t\t\tswitch (code) {\n\t\t\t\t\t\t\t\tcase COMMA:\n\t\t\t\t\t\t\t\tcase TILDE:\n\t\t\t\t\t\t\t\tcase GREATERTHAN:\n\t\t\t\t\t\t\t\tcase PLUS:\n\t\t\t\t\t\t\t\tcase CLOSEPARENTHESES:\n\t\t\t\t\t\t\t\tcase OPENPARENTHESES: {\n\t\t\t\t\t\t\t\t\tif (context === 0) {\n\t\t\t\t\t\t\t\t\t\t// outside of an isolated context i.e nth-child(<...>)\n\t\t\t\t\t\t\t\t\t\tswitch (tail) {\n\t\t\t\t\t\t\t\t\t\t\tcase TAB:\n\t\t\t\t\t\t\t\t\t\t\tcase SPACE:\n\t\t\t\t\t\t\t\t\t\t\tcase NEWLINE:\n\t\t\t\t\t\t\t\t\t\t\tcase CARRIAGE: {\n\t\t\t\t\t\t\t\t\t\t\t\tchar = char + '\\0'\n\t\t\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\t\t\t\t\t\tchar = '\\0' + char + (code === COMMA ? '' : '\\0')\n\t\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\tformat = 1\n\t\t\t\t\t\t\t\t\t} else {\n\t\t\t\t\t\t\t\t\t\t// within an isolated context, sleep untill it's terminated\n\t\t\t\t\t\t\t\t\t\tswitch (code) {\n\t\t\t\t\t\t\t\t\t\t\tcase OPENPARENTHESES: {\n\t\t\t\t\t\t\t\t\t\t\t\t// :globa<l>(\n\t\t\t\t\t\t\t\t\t\t\t\tif (pseudo + 7 === caret && tail === 108) {\n\t\t\t\t\t\t\t\t\t\t\t\t\tpseudo = 0\n\t\t\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\t\t\tcontext = ++counter\n\t\t\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\t\tcase CLOSEPARENTHESES: {\n\t\t\t\t\t\t\t\t\t\t\t\tif ((context = --counter) === 0) {\n\t\t\t\t\t\t\t\t\t\t\t\t\tformat = 1\n\t\t\t\t\t\t\t\t\t\t\t\t\tchar += '\\0'\n\t\t\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\tcase TAB:\n\t\t\t\t\t\t\t\tcase SPACE: {\n\t\t\t\t\t\t\t\t\tswitch (tail) {\n\t\t\t\t\t\t\t\t\t\tcase NULL:\n\t\t\t\t\t\t\t\t\t\tcase OPENBRACES:\n\t\t\t\t\t\t\t\t\t\tcase CLOSEBRACES:\n\t\t\t\t\t\t\t\t\t\tcase SEMICOLON:\n\t\t\t\t\t\t\t\t\t\tcase COMMA:\n\t\t\t\t\t\t\t\t\t\tcase FORMFEED:\n\t\t\t\t\t\t\t\t\t\tcase TAB:\n\t\t\t\t\t\t\t\t\t\tcase SPACE:\n\t\t\t\t\t\t\t\t\t\tcase NEWLINE:\n\t\t\t\t\t\t\t\t\t\tcase CARRIAGE: {\n\t\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\t\t\t\t\t// ignore in isolated contexts\n\t\t\t\t\t\t\t\t\t\t\tif (context === 0) {\n\t\t\t\t\t\t\t\t\t\t\t\tformat = 1\n\t\t\t\t\t\t\t\t\t\t\t\tchar += '\\0'\n\t\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t}\n\n\t\t\t\t\t\t// concat buffer of characters\n\t\t\t\t\t\tchars += char\n\n\t\t\t\t\t\t// previous non-whitespace character code\n\t\t\t\t\t\tif (code !== SPACE && code !== TAB) {\n\t\t\t\t\t\t\tpeak = code\n\t\t\t\t\t\t}\n\t\t\t\t\t}\n\t\t\t\t}\n\t\t\t}\n\n\t\t\t// tail character codes\n\t\t\ttrail = tail\n\t\t\ttail = code\n\n\t\t\t// visit every character\n\t\t\tcaret++\n\t\t}\n\n\t\tlength = out.length\n\n\t\t// preserve empty selector\n \t\tif (preserve > 0) {\n \t\t\tif (length === 0 && children.length === 0 && (current[0].length === 0) === false) {\n \t\t\t\tif (id !== MEDIA || (current.length === 1 && (cascade > 0 ? nscopealt : nscope) === current[0])) {\n\t\t\t\t\tlength = current.join(',').length + 2\n \t\t\t\t}\n \t\t\t}\n\t\t}\n\n\t\tif (length > 0) {\n\t\t\t// cascade isolation mode?\n\t\t\tselector = cascade === 0 && id !== KEYFRAME ? isolate(current) : current\n\n\t\t\t// execute plugins, block context\n\t\t\tif (plugged > 0) {\n\t\t\t\tresult = proxy(BLCKS, out, selector, parent, line, column, length, id, depth, id)\n\n\t\t\t\tif (result !== void 0 && (out = result).length === 0) {\n\t\t\t\t\treturn flat + out + children\n\t\t\t\t}\n\t\t\t}\n\n\t\t\tout = selector.join(',') + '{' + out + '}'\n\n\t\t\tif (prefix*pattern !== 0) {\n\t\t\t\tif (prefix === 2 && !vendor(out, 2))\n\t\t\t\t\tpattern = 0\n\n\t\t\t\tswitch (pattern) {\n\t\t\t\t\t// ::read-only\n\t\t\t\t\tcase READONLY: {\n\t\t\t\t\t\tout = out.replace(readonlyptn, ':'+moz+'$1')+out\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t\t// ::placeholder\n\t\t\t\t\tcase PLACEHOLDER: {\n\t\t\t\t\t\tout = (\n\t\t\t\t\t\t\tout.replace(plcholdrptn, '::' + webkit + 'input-$1') +\n\t\t\t\t\t\t\tout.replace(plcholdrptn, '::' + moz + '$1') +\n\t\t\t\t\t\t\tout.replace(plcholdrptn, ':' + ms + 'input-$1') + out\n\t\t\t\t\t\t)\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t}\n\n\t\t\t\tpattern = 0\n\t\t\t}\n\t\t}\n\n\t\treturn flat + out + children\n\t}\n\n\t/**\n\t * Select\n\t *\n\t * @param {Array<string>} parent\n\t * @param {string} current\n\t * @param {number} invert\n\t * @return {Array<string>}\n\t */\n\tfunction select (parent, current, invert) {\n\t\tvar selectors = current.trim().split(selectorptn)\n\t\tvar out = selectors\n\n\t\tvar length = selectors.length\n\t\tvar l = parent.length\n\n\t\tswitch (l) {\n\t\t\t// 0-1 parent selectors\n\t\t\tcase 0:\n\t\t\tcase 1: {\n\t\t\t\tfor (var i = 0, selector = l === 0 ? '' : parent[0] + ' '; i < length; ++i) {\n\t\t\t\t\tout[i] = scope(selector, out[i], invert, l).trim()\n\t\t\t\t}\n\t\t\t\tbreak\n\t\t\t}\n\t\t\t// >2 parent selectors, nested\n\t\t\tdefault: {\n\t\t\t\tfor (var i = 0, j = 0, out = []; i < length; ++i) {\n\t\t\t\t\tfor (var k = 0; k < l; ++k) {\n\t\t\t\t\t\tout[j++] = scope(parent[k] + ' ', selectors[i], invert, l).trim()\n\t\t\t\t\t}\n\t\t\t\t}\n\t\t\t}\n\t\t}\n\n\t\treturn out\n\t}\n\n\t/**\n\t * Scope\n\t *\n\t * @param {string} parent\n\t * @param {string} current\n\t * @param {number} invert\n\t * @param {number} level\n\t * @return {string}\n\t */\n\tfunction scope (parent, current, invert, level) {\n\t\tvar selector = current\n\t\tvar code = selector.charCodeAt(0)\n\n\t\t// trim leading whitespace\n\t\tif (code < 33) {\n\t\t\tcode = (selector = selector.trim()).charCodeAt(0)\n\t\t}\n\n\t\tswitch (code) {\n\t\t\t// &\n\t\t\tcase AND: {\n\t\t\t\tswitch (cascade + level) {\n\t\t\t\t\tcase 0:\n\t\t\t\t\tcase 1: {\n\t\t\t\t\t\tif (parent.trim().length === 0) {\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t}\n\t\t\t\t\tdefault: {\n\t\t\t\t\t\treturn selector.replace(andptn, '$1'+parent.trim())\n\t\t\t\t\t}\n\t\t\t\t}\n\t\t\t\tbreak\n\t\t\t}\n\t\t\t// :\n\t\t\tcase COLON: {\n\t\t\t\tswitch (selector.charCodeAt(1)) {\n\t\t\t\t\t// g in :global\n\t\t\t\t\tcase 103: {\n\t\t\t\t\t\tif (escape > 0 && cascade > 0) {\n\t\t\t\t\t\t\treturn selector.replace(escapeptn, '$1').replace(andptn, '$1'+nscope)\n\t\t\t\t\t\t}\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t\tdefault: {\n\t\t\t\t\t\t// :hover\n\t\t\t\t\t\treturn parent.trim() + selector.replace(andptn, '$1'+parent.trim())\n\t\t\t\t\t}\n\t\t\t\t}\n\t\t\t}\n\t\t\tdefault: {\n\t\t\t\t// html &\n\t\t\t\tif (invert*cascade > 0 && selector.indexOf('\\f') > 0) {\n\t\t\t\t\treturn selector.replace(andptn, (parent.charCodeAt(0) === COLON ? '' : '$1')+parent.trim())\n\t\t\t\t}\n\t\t\t}\n\t\t}\n\n\t\treturn parent + selector\n\t}\n\n\t/**\n\t * Property\n\t *\n\t * @param {string} input\n\t * @param {number} first\n\t * @param {number} second\n\t * @param {number} third\n\t * @return {string}\n\t */\n\tfunction property (input, first, second, third) {\n\t\tvar index = 0\n\t\tvar out = input + ';'\n\t\tvar hash = (first*2) + (second*3) + (third*4)\n\t\tvar cache\n\n\t\t// animation: a, n, i characters\n\t\tif (hash === 944) {\n\t\t\treturn animation(out)\n\t\t} else if (prefix === 0 || (prefix === 2 && !vendor(out, 1))) {\n\t\t\treturn out\n\t\t}\n\n\t\t// vendor prefix\n\t\tswitch (hash) {\n\t\t\t// text-decoration/text-size-adjust/text-shadow/text-align/text-transform: t, e, x\n\t\t\tcase 1015: {\n\t\t\t\t// text-shadow/text-align/text-transform, a\n\t\t\t\treturn out.charCodeAt(10) === 97 ? webkit + out + out : out\n\t\t\t}\n\t\t\t// filter/fill f, i, l\n\t\t\tcase 951: {\n\t\t\t\t// filter, t\n\t\t\t\treturn out.charCodeAt(3) === 116 ? webkit + out + out : out\n\t\t\t}\n\t\t\t// color/column, c, o, l\n\t\t\tcase 963: {\n\t\t\t\t// column, n\n\t\t\t\treturn out.charCodeAt(5) === 110 ? webkit + out + out : out\n\t\t\t}\n\t\t\t// box-decoration-break, b, o, x\n\t\t\tcase 1009: {\n\t\t\t\tif (out.charCodeAt(4) !== 100) {\n\t\t\t\t\tbreak\n\t\t\t\t}\n\t\t\t}\n\t\t\t// mask, m, a, s\n\t\t\t// clip-path, c, l, i\n\t\t\tcase 969:\n\t\t\tcase 942: {\n\t\t\t\treturn webkit + out + out\n\t\t\t}\n\t\t\t// appearance: a, p, p\n\t\t\tcase 978: {\n\t\t\t\treturn webkit + out + moz + out + out\n\t\t\t}\n\t\t\t// hyphens: h, y, p\n\t\t\t// user-select: u, s, e\n\t\t\tcase 1019:\n\t\t\tcase 983: {\n\t\t\t\treturn webkit + out + moz + out + ms + out + out\n\t\t\t}\n\t\t\t// background/backface-visibility, b, a, c\n\t\t\tcase 883: {\n\t\t\t\t// backface-visibility, -\n\t\t\t\tif (out.charCodeAt(8) === DASH) {\n\t\t\t\t\treturn webkit + out + out\n\t\t\t\t}\n\n\t\t\t\t// image-set(...)\n\t\t\t\tif (out.indexOf('image-set(', 11) > 0) {\n\t\t\t\t\treturn out.replace(imgsrcptn, '$1'+webkit+'$2') + out\n\t\t\t\t}\n\n\t\t\t\treturn out\n\t\t\t}\n\t\t\t// flex: f, l, e\n\t\t\tcase 932: {\n\t\t\t\tif (out.charCodeAt(4) === DASH) {\n\t\t\t\t\tswitch (out.charCodeAt(5)) {\n\t\t\t\t\t\t// flex-grow, g\n\t\t\t\t\t\tcase 103: {\n\t\t\t\t\t\t\treturn webkit + 'box-' + out.replace('-grow', '') + webkit + out + ms + out.replace('grow', 'positive') + out\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// flex-shrink, s\n\t\t\t\t\t\tcase 115: {\n\t\t\t\t\t\t\treturn webkit + out + ms + out.replace('shrink', 'negative') + out\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// flex-basis, b\n\t\t\t\t\t\tcase 98: {\n\t\t\t\t\t\t\treturn webkit + out + ms + out.replace('basis', 'preferred-size') + out\n\t\t\t\t\t\t}\n\t\t\t\t\t}\n\t\t\t\t}\n\n\t\t\t\treturn webkit + out + ms + out + out\n\t\t\t}\n\t\t\t// order: o, r, d\n\t\t\tcase 964: {\n\t\t\t\treturn webkit + out + ms + 'flex' + '-' + out + out\n\t\t\t}\n\t\t\t// justify-items/justify-content, j, u, s\n\t\t\tcase 1023: {\n\t\t\t\t// justify-content, c\n\t\t\t\tif (out.charCodeAt(8) !== 99) {\n\t\t\t\t\tbreak\n\t\t\t\t}\n\n\t\t\t\tcache = out.substring(out.indexOf(':', 15)).replace('flex-', '').replace('space-between', 'justify')\n\t\t\t\treturn webkit + 'box-pack' + cache + webkit + out + ms + 'flex-pack' + cache + out\n\t\t\t}\n\t\t\t// cursor, c, u, r\n\t\t\tcase 1005: {\n\t\t\t\treturn cursorptn.test(out) ? out.replace(colonptn, ':' + webkit) + out.replace(colonptn, ':' + moz) + out : out\n\t\t\t}\n\t\t\t// writing-mode, w, r, i\n\t\t\tcase 1000: {\n\t\t\t\tcache = out.substring(13).trim()\n\t\t\t\tindex = cache.indexOf('-') + 1\n\n\t\t\t\tswitch (cache.charCodeAt(0)+cache.charCodeAt(index)) {\n\t\t\t\t\t// vertical-lr\n\t\t\t\t\tcase 226: {\n\t\t\t\t\t\tcache = out.replace(writingptn, 'tb')\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t\t// vertical-rl\n\t\t\t\t\tcase 232: {\n\t\t\t\t\t\tcache = out.replace(writingptn, 'tb-rl')\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t\t// horizontal-tb\n\t\t\t\t\tcase 220: {\n\t\t\t\t\t\tcache = out.replace(writingptn, 'lr')\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t\tdefault: {\n\t\t\t\t\t\treturn out\n\t\t\t\t\t}\n\t\t\t\t}\n\n\t\t\t\treturn webkit + out + ms + cache + out\n\t\t\t}\n\t\t\t// position: sticky\n\t\t\tcase 1017: {\n\t\t\t\tif (out.indexOf('sticky', 9) === -1) {\n\t\t\t\t\treturn out\n\t\t\t\t}\n\t\t\t}\n\t\t\t// display(flex/inline-flex/inline-box): d, i, s\n\t\t\tcase 975: {\n\t\t\t\tindex = (out = input).length - 10\n\t\t\t\tcache = (out.charCodeAt(index) === 33 ? out.substring(0, index) : out).substring(input.indexOf(':', 7) + 1).trim()\n\n\t\t\t\tswitch (hash = cache.charCodeAt(0) + (cache.charCodeAt(7)|0)) {\n\t\t\t\t\t// inline-\n\t\t\t\t\tcase 203: {\n\t\t\t\t\t\t// inline-box\n\t\t\t\t\t\tif (cache.charCodeAt(8) < 111) {\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t}\n\t\t\t\t\t// inline-box/sticky\n\t\t\t\t\tcase 115: {\n\t\t\t\t\t\tout = out.replace(cache, webkit+cache)+';'+out\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t\t// inline-flex\n\t\t\t\t\t// flex\n\t\t\t\t\tcase 207:\n\t\t\t\t\tcase 102: {\n\t\t\t\t\t\tout = (\n\t\t\t\t\t\t\tout.replace(cache, webkit+(hash > 102 ? 'inline-' : '')+'box')+';'+\n\t\t\t\t\t\t\tout.replace(cache, webkit+cache)+';'+\n\t\t\t\t\t\t\tout.replace(cache, ms+cache+'box')+';'+\n\t\t\t\t\t\t\tout\n\t\t\t\t\t\t)\n\t\t\t\t\t}\n\t\t\t\t}\n\n\t\t\t\treturn out + ';'\n\t\t\t}\n\t\t\t// align-items, align-center, align-self: a, l, i, -\n\t\t\tcase 938: {\n\t\t\t\tif (out.charCodeAt(5) === DASH) {\n\t\t\t\t\tswitch (out.charCodeAt(6)) {\n\t\t\t\t\t\t// align-items, i\n\t\t\t\t\t\tcase 105: {\n\t\t\t\t\t\t\tcache = out.replace('-items', '')\n\t\t\t\t\t\t\treturn webkit + out + webkit + 'box-' + cache + ms + 'flex-' + cache + out\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// align-self, s\n\t\t\t\t\t\tcase 115: {\n\t\t\t\t\t\t\treturn webkit + out + ms + 'flex-item-' + out.replace(selfptn, '') + out\n\t\t\t\t\t\t}\n\t\t\t\t\t\t// align-content\n\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\treturn webkit + out + ms + 'flex-line-pack' + out.replace('align-content', '').replace(selfptn, '') + out\n\t\t\t\t\t\t}\n\t\t\t\t\t}\n\t\t\t\t}\n\t\t\t\tbreak\n\t\t\t}\n\t\t\t// min/max\n\t\t\tcase 973:\n\t\t\tcase 989: {\n\t\t\t\t// min-/max- height/width/block-size/inline-size\n\t\t\t\tif (out.charCodeAt(3) !== DASH || out.charCodeAt(4) === 122) {\n\t\t\t\t\tbreak\n\t\t\t\t}\n\t\t\t}\n\t\t\t// height/width: min-content / width: max-content\n\t\t\tcase 931:\n\t\t\tcase 953: {\n\t\t\t\tif (dimensionptn.test(input) === true) {\n\t\t\t\t\t// stretch\n\t\t\t\t\tif ((cache = input.substring(input.indexOf(':') + 1)).charCodeAt(0) === 115)\n\t\t\t\t\t\treturn property(input.replace('stretch', 'fill-available'), first, second, third).replace(':fill-available', ':stretch')\n\t\t\t\t\telse\n\t\t\t\t\t\treturn out.replace(cache, webkit + cache) + out.replace(cache, moz + cache.replace('fill-', '')) + out\n\t\t\t\t}\n\t\t\t\tbreak\n\t\t\t}\n\t\t\t// transform, transition: t, r, a\n\t\t\tcase 962: {\n\t\t\t\tout = webkit + out + (out.charCodeAt(5) === 102 ? ms + out : '') + out\n\n\t\t\t\t// transitions\n\t\t\t\tif (second + third === 211 && out.charCodeAt(13) === 105 && out.indexOf('transform', 10) > 0) {\n\t\t\t\t\treturn out.substring(0, out.indexOf(';', 27) + 1).replace(transformptn, '$1' + webkit + '$2') + out\n\t\t\t\t}\n\n\t\t\t\tbreak\n\t\t\t}\n\t\t}\n\n\t\treturn out\n\t}\n\n\t/**\n\t * Vendor\n\t *\n\t * @param {string} content\n\t * @param {number} context\n\t * @return {boolean}\n\t */\n\tfunction vendor (content, context) {\n\t\tvar index = content.indexOf(context === 1 ? ':' : '{')\n\t\tvar key = content.substring(0, context !== 3 ? index : 10)\n\t\tvar value = content.substring(index + 1, content.length - 1)\n\n\t\treturn should(context !== 2 ? key : key.replace(pseudofmt, '$1'), value, context)\n\t}\n\n\t/**\n\t * Supports\n\t *\n\t * @param {string} match\n\t * @param {string} group\n\t * @return {string}\n\t */\n\tfunction supports (match, group) {\n\t\tvar out = property(group, group.charCodeAt(0), group.charCodeAt(1), group.charCodeAt(2))\n\n\t\treturn out !== group+';' ? out.replace(propertyptn, ' or ($1)').substring(4) : '('+group+')'\n\t}\n\n\t/**\n\t * Animation\n\t *\n\t * @param {string} input\n\t * @return {string}\n\t */\n\tfunction animation (input) {\n\t\tvar length = input.length\n\t\tvar index = input.indexOf(':', 9) + 1\n\t\tvar declare = input.substring(0, index).trim()\n\t\tvar out = input.substring(index, length-1).trim()\n\n\t\tswitch (input.charCodeAt(9)*keyed) {\n\t\t\tcase 0: {\n\t\t\t\tbreak\n\t\t\t}\n\t\t\t// animation-*, -\n\t\t\tcase DASH: {\n\t\t\t\t// animation-name, n\n\t\t\t\tif (input.charCodeAt(10) !== 110) {\n\t\t\t\t\tbreak\n\t\t\t\t}\n\t\t\t}\n\t\t\t// animation/animation-name\n\t\t\tdefault: {\n\t\t\t\t// split in case of multiple animations\n\t\t\t\tvar list = out.split((out = '', animationptn))\n\n\t\t\t\tfor (var i = 0, index = 0, length = list.length; i < length; index = 0, ++i) {\n\t\t\t\t\tvar value = list[i]\n\t\t\t\t\tvar items = value.split(propertiesptn)\n\n\t\t\t\t\twhile (value = items[index]) {\n\t\t\t\t\t\tvar peak = value.charCodeAt(0)\n\n\t\t\t\t\t\tif (keyed === 1 && (\n\t\t\t\t\t\t\t// letters\n\t\t\t\t\t\t\t(peak > AT && peak < 90) || (peak > 96 && peak < 123) || peak === UNDERSCORE ||\n\t\t\t\t\t\t\t// dash but not in sequence i.e --\n\t\t\t\t\t\t\t(peak === DASH && value.charCodeAt(1) !== DASH)\n\t\t\t\t\t\t)) {\n\t\t\t\t\t\t\t// not a number/function\n\t\t\t\t\t\t\tswitch (isNaN(parseFloat(value)) + (value.indexOf('(') !== -1)) {\n\t\t\t\t\t\t\t\tcase 1: {\n\t\t\t\t\t\t\t\t\tswitch (value) {\n\t\t\t\t\t\t\t\t\t\t// not a valid reserved keyword\n\t\t\t\t\t\t\t\t\t\tcase 'infinite': case 'alternate': case 'backwards': case 'running':\n\t\t\t\t\t\t\t\t\t\tcase 'normal': case 'forwards': case 'both': case 'none': case 'linear':\n\t\t\t\t\t\t\t\t\t\tcase 'ease': case 'ease-in': case 'ease-out': case 'ease-in-out':\n\t\t\t\t\t\t\t\t\t\tcase 'paused': case 'reverse': case 'alternate-reverse': case 'inherit':\n\t\t\t\t\t\t\t\t\t\tcase 'initial': case 'unset': case 'step-start': case 'step-end': {\n\t\t\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\t\t\t\t\tvalue += key\n\t\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t}\n\n\t\t\t\t\t\titems[index++] = value\n\t\t\t\t\t}\n\n\t\t\t\t\tout += (i === 0 ? '' : ',') + items.join(' ')\n\t\t\t\t}\n\t\t\t}\n\t\t}\n\n\t\tout = declare + out + ';'\n\n\t\tif (prefix === 1 || (prefix === 2 && vendor(out, 1)))\n\t\t\treturn webkit + out + out\n\n\t\treturn out\n\t}\n\n\t/**\n\t * Isolate\n\t *\n\t * @param {Array<string>} current\n\t */\n\tfunction isolate (current) {\n\t\tfor (var i = 0, length = current.length, selector = Array(length), padding, element; i < length; ++i) {\n\t\t\t// split individual elements in a selector i.e h1 h2 === [h1, h2]\n\t\t\tvar elements = current[i].split(elementptn)\n\t\t\tvar out = ''\n\n\t\t\tfor (var j = 0, size = 0, tail = 0, code = 0, l = elements.length; j < l; ++j) {\n\t\t\t\t// empty element\n\t\t\t\tif ((size = (element = elements[j]).length) === 0 && l > 1) {\n\t\t\t\t\tcontinue\n\t\t\t\t}\n\n\t\t\t\ttail = out.charCodeAt(out.length-1)\n\t\t\t\tcode = element.charCodeAt(0)\n\t\t\t\tpadding = ''\n\n\t\t\t\tif (j !== 0) {\n\t\t\t\t\t// determine if we need padding\n\t\t\t\t\tswitch (tail) {\n\t\t\t\t\t\tcase STAR:\n\t\t\t\t\t\tcase TILDE:\n\t\t\t\t\t\tcase GREATERTHAN:\n\t\t\t\t\t\tcase PLUS:\n\t\t\t\t\t\tcase SPACE:\n\t\t\t\t\t\tcase OPENPARENTHESES:  {\n\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t}\n\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\tpadding = ' '\n\t\t\t\t\t\t}\n\t\t\t\t\t}\n\t\t\t\t}\n\n\t\t\t\tswitch (code) {\n\t\t\t\t\tcase AND: {\n\t\t\t\t\t\telement = padding + nscopealt\n\t\t\t\t\t}\n\t\t\t\t\tcase TILDE:\n\t\t\t\t\tcase GREATERTHAN:\n\t\t\t\t\tcase PLUS:\n\t\t\t\t\tcase SPACE:\n\t\t\t\t\tcase CLOSEPARENTHESES:\n\t\t\t\t\tcase OPENPARENTHESES: {\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t\tcase OPENBRACKET: {\n\t\t\t\t\t\telement = padding + element + nscopealt\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t\tcase COLON: {\n\t\t\t\t\t\tswitch (element.charCodeAt(1)*2 + element.charCodeAt(2)*3) {\n\t\t\t\t\t\t\t// :global\n\t\t\t\t\t\t\tcase 530: {\n\t\t\t\t\t\t\t\tif (escape > 0) {\n\t\t\t\t\t\t\t\t\telement = padding + element.substring(8, size - 1)\n\t\t\t\t\t\t\t\t\tbreak\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t// :hover, :nth-child(), ...\n\t\t\t\t\t\t\tdefault: {\n\t\t\t\t\t\t\t\tif (j < 1 || elements[j-1].length < 1) {\n\t\t\t\t\t\t\t\t\telement = padding + nscopealt + element\n\t\t\t\t\t\t\t\t}\n\t\t\t\t\t\t\t}\n\t\t\t\t\t\t}\n\t\t\t\t\t\tbreak\n\t\t\t\t\t}\n\t\t\t\t\tcase COMMA: {\n\t\t\t\t\t\tpadding = ''\n\t\t\t\t\t}\n\t\t\t\t\tdefault: {\n\t\t\t\t\t\tif (size > 1 && element.indexOf(':') > 0) {\n\t\t\t\t\t\t\telement = padding + element.replace(pseudoptn, '$1' + nscopealt + '$2')\n\t\t\t\t\t\t} else {\n\t\t\t\t\t\t\telement = padding + element + nscopealt\n\t\t\t\t\t\t}\n\t\t\t\t\t}\n\t\t\t\t}\n\n\t\t\t\tout += element\n\t\t\t}\n\n\t\t\tselector[i] = out.replace(formatptn, '').trim()\n\t\t}\n\n\t\treturn selector\n\t}\n\n\t/**\n\t * Proxy\n\t *\n\t * @param {number} context\n\t * @param {string} content\n\t * @param {Array<string>} selectors\n\t * @param {Array<string>} parents\n\t * @param {number} line\n\t * @param {number} column\n\t * @param {number} length\n\t * @param {number} id\n\t * @param {number} depth\n\t * @param {number} at\n\t * @return {(string|void|*)}\n\t */\n\tfunction proxy (context, content, selectors, parents, line, column, length, id, depth, at) {\n\t\tfor (var i = 0, out = content, next; i < plugged; ++i) {\n\t\t\tswitch (next = plugins[i].call(stylis, context, out, selectors, parents, line, column, length, id, depth, at)) {\n\t\t\t\tcase void 0:\n\t\t\t\tcase false:\n\t\t\t\tcase true:\n\t\t\t\tcase null: {\n\t\t\t\t\tbreak\n\t\t\t\t}\n\t\t\t\tdefault: {\n\t\t\t\t\tout = next\n\t\t\t\t}\n\t\t\t}\n\t\t}\n\t\tif (out !== content) {\n\t\t  return out\n\t\t}\n\t}\n\n\t/**\n\t * @param {number} code\n\t * @param {number} index\n\t * @param {number} length\n\t * @param {string} body\n\t * @return {number}\n\t */\n\tfunction delimited (code, index, length, body) {\n\t\tfor (var i = index + 1; i < length; ++i) {\n\t\t\tswitch (body.charCodeAt(i)) {\n\t\t\t\t// /*\n\t\t\t\tcase FOWARDSLASH: {\n\t\t\t\t\tif (code === STAR) {\n\t\t\t\t\t\tif (body.charCodeAt(i - 1) === STAR &&  index + 2 !== i) {\n\t\t\t\t\t\t\treturn i + 1\n\t\t\t\t\t\t}\n\t\t\t\t\t}\n\t\t\t\t\tbreak\n\t\t\t\t}\n\t\t\t\t// //\n\t\t\t\tcase NEWLINE: {\n\t\t\t\t\tif (code === FOWARDSLASH) {\n\t\t\t\t\t\treturn i + 1\n\t\t\t\t\t}\n\t\t\t\t}\n\t\t\t}\n\t\t}\n\n\t\treturn i\n\t}\n\n\t/**\n\t * @param {number} type\n\t * @param {number} index\n\t * @param {number} length\n\t * @param {number} find\n\t * @param {string} body\n\t * @return {number}\n\t */\n\tfunction match (type, index, length, body) {\n\t\tfor (var i = index + 1; i < length; ++i) {\n\t\t\tswitch (body.charCodeAt(i)) {\n\t\t\t\tcase type: {\n\t\t\t\t\treturn i\n\t\t\t\t}\n\t\t\t}\n\t\t}\n\n\t\treturn i\n\t}\n\n\t/**\n\t * Minify\n\t *\n\t * @param {(string|*)} output\n\t * @return {string}\n\t */\n\tfunction minify (output) {\n\t\treturn output\n\t\t\t.replace(formatptn, '')\n\t\t\t.replace(beforeptn, '')\n\t\t\t.replace(afterptn, '$1')\n\t\t\t.replace(tailptn, '$1')\n\t\t\t.replace(whiteptn, ' ')\n\t}\n\n\t/**\n\t * Use\n\t *\n\t * @param {(Array<function(...?)>|function(...?)|number|void)?} plugin\n\t */\n\tfunction use (plugin) {\n\t\tswitch (plugin) {\n\t\t\tcase void 0:\n\t\t\tcase null: {\n\t\t\t\tplugged = plugins.length = 0\n\t\t\t\tbreak\n\t\t\t}\n\t\t\tdefault: {\n\t\t\t\tif (typeof plugin === 'function') {\n\t\t\t\t\tplugins[plugged++] = plugin\n\t\t\t\t}\telse if (typeof plugin === 'object') {\n\t\t\t\t\tfor (var i = 0, length = plugin.length; i < length; ++i) {\n\t\t\t\t\t\tuse(plugin[i])\n\t\t\t\t\t}\n\t\t\t\t} else {\n\t\t\t\t\tunkwn = !!plugin|0\n\t\t\t\t}\n\t\t\t}\n \t\t}\n\n \t\treturn use\n\t}\n\n\t/**\n\t * Set\n\t *\n\t * @param {*} options\n\t */\n\tfunction set (options) {\n\t\tfor (var name in options) {\n\t\t\tvar value = options[name]\n\t\t\tswitch (name) {\n\t\t\t\tcase 'keyframe': keyed = value|0; break\n\t\t\t\tcase 'global': escape = value|0; break\n\t\t\t\tcase 'cascade': cascade = value|0; break\n\t\t\t\tcase 'compress': compress = value|0; break\n\t\t\t\tcase 'semicolon': semicolon = value|0; break\n\t\t\t\tcase 'preserve': preserve = value|0; break\n\t\t\t\tcase 'prefix':\n\t\t\t\t\tshould = null\n\n\t\t\t\t\tif (!value) {\n\t\t\t\t\t\tprefix = 0\n\t\t\t\t\t} else if (typeof value !== 'function') {\n\t\t\t\t\t\tprefix = 1\n\t\t\t\t\t} else {\n\t\t\t\t\t\tprefix = 2\n\t\t\t\t\t\tshould = value\n\t\t\t\t\t}\n\t\t\t}\n\t\t}\n\n\t\treturn set\n\t}\n\n\t/**\n\t * Stylis\n\t *\n\t * @param {string} selector\n\t * @param {string} input\n\t * @return {*}\n\t */\n\tfunction stylis (selector, input) {\n\t\tif (this !== void 0 && this.constructor === stylis) {\n\t\t\treturn factory(selector)\n\t\t}\n\n\t\t// setup\n\t\tvar ns = selector\n\t\tvar code = ns.charCodeAt(0)\n\n\t\t// trim leading whitespace\n\t\tif (code < 33) {\n\t\t\tcode = (ns = ns.trim()).charCodeAt(0)\n\t\t}\n\n\t\t// keyframe/animation namespace\n\t\tif (keyed > 0) {\n\t\t\tkey = ns.replace(invalidptn, code === OPENBRACKET ? '' : '-')\n\t\t}\n\n\t\t// reset, used to assert if a plugin is moneky-patching the return value\n\t\tcode = 1\n\n\t\t// cascade/isolate\n\t\tif (cascade === 1) {\n\t\t\tnscope = ns\n\t\t} else {\n\t\t\tnscopealt = ns\n\t\t}\n\n\t\tvar selectors = [nscope]\n\t\tvar result\n\n\t\t// execute plugins, pre-process context\n\t\tif (plugged > 0) {\n\t\t\tresult = proxy(PREPS, input, selectors, selectors, line, column, 0, 0, 0, 0)\n\n\t\t\tif (result !== void 0 && typeof result === 'string') {\n\t\t\t\tinput = result\n\t\t\t}\n\t\t}\n\n\t\t// build\n\t\tvar output = compile(array, selectors, input, 0, 0)\n\n\t\t// execute plugins, post-process context\n\t\tif (plugged > 0) {\n\t\t\tresult = proxy(POSTS, output, selectors, selectors, line, column, output.length, 0, 0, 0)\n\n\t\t\t// bypass minification\n\t\t\tif (result !== void 0 && typeof(output = result) !== 'string') {\n\t\t\t\tcode = 0\n\t\t\t}\n\t\t}\n\n\t\t// reset\n\t\tkey = ''\n\t\tnscope = ''\n\t\tnscopealt = ''\n\t\tpattern = 0\n\t\tline = 1\n\t\tcolumn = 1\n\n\t\treturn compress*code === 0 ? output : minify(output)\n\t}\n\n\tstylis['use'] = use\n\tstylis['set'] = set\n\n\tif (options !== void 0) {\n\t\tset(options)\n\t}\n\n\treturn stylis\n}));\n",
         "'use strict';\n\n/**\n * Copyright 2015, Yahoo! Inc.\n * Copyrights licensed under the New BSD License. See the accompanying LICENSE file for terms.\n */\nvar REACT_STATICS = {\n    childContextTypes: true,\n    contextTypes: true,\n    defaultProps: true,\n    displayName: true,\n    getDefaultProps: true,\n    getDerivedStateFromProps: true,\n    mixins: true,\n    propTypes: true,\n    type: true\n};\n\nvar KNOWN_STATICS = {\n    name: true,\n    length: true,\n    prototype: true,\n    caller: true,\n    callee: true,\n    arguments: true,\n    arity: true\n};\n\nvar defineProperty = Object.defineProperty;\nvar getOwnPropertyNames = Object.getOwnPropertyNames;\nvar getOwnPropertySymbols = Object.getOwnPropertySymbols;\nvar getOwnPropertyDescriptor = Object.getOwnPropertyDescriptor;\nvar getPrototypeOf = Object.getPrototypeOf;\nvar objectPrototype = getPrototypeOf && getPrototypeOf(Object);\n\nfunction hoistNonReactStatics(targetComponent, sourceComponent, blacklist) {\n    if (typeof sourceComponent !== 'string') { // don't hoist over string (html) components\n\n        if (objectPrototype) {\n            var inheritedComponent = getPrototypeOf(sourceComponent);\n            if (inheritedComponent && inheritedComponent !== objectPrototype) {\n                hoistNonReactStatics(targetComponent, inheritedComponent, blacklist);\n            }\n        }\n\n        var keys = getOwnPropertyNames(sourceComponent);\n\n        if (getOwnPropertySymbols) {\n            keys = keys.concat(getOwnPropertySymbols(sourceComponent));\n        }\n\n        for (var i = 0; i < keys.length; ++i) {\n            var key = keys[i];\n            if (!REACT_STATICS[key] && !KNOWN_STATICS[key] && (!blacklist || !blacklist[key])) {\n                var descriptor = getOwnPropertyDescriptor(sourceComponent, key);\n                try { // Avoid failures from read-only properties\n                    defineProperty(targetComponent, key, descriptor);\n                } catch (e) {}\n            }\n        }\n\n        return targetComponent;\n    }\n\n    return targetComponent;\n}\n\nmodule.exports = hoistNonReactStatics;\n",
         "/**\n * @typedef {object} PrivateData\n * @property {EventTarget} eventTarget The event target.\n * @property {{type:string}} event The original event object.\n * @property {number} eventPhase The current event phase.\n * @property {EventTarget|null} currentTarget The current event target.\n * @property {boolean} canceled The flag to prevent default.\n * @property {boolean} stopped The flag to stop propagation.\n * @property {boolean} immediateStopped The flag to stop propagation immediately.\n * @property {Function|null} passiveListener The listener if the current listener is passive. Otherwise this is null.\n * @property {number} timeStamp The unix time.\n * @private\n */\n\n/**\n * Private data for event wrappers.\n * @type {WeakMap<Event, PrivateData>}\n * @private\n */\nconst privateData = new WeakMap()\n\n/**\n * Cache for wrapper classes.\n * @type {WeakMap<Object, Function>}\n * @private\n */\nconst wrappers = new WeakMap()\n\n/**\n * Get private data.\n * @param {Event} event The event object to get private data.\n * @returns {PrivateData} The private data of the event.\n * @private\n */\nfunction pd(event) {\n    const retv = privateData.get(event)\n    console.assert(\n        retv != null,\n        \"'this' is expected an Event object, but got\",\n        event\n    )\n    return retv\n}\n\n/**\n * https://dom.spec.whatwg.org/#set-the-canceled-flag\n * @param data {PrivateData} private data.\n */\nfunction setCancelFlag(data) {\n    if (data.passiveListener != null) {\n        if (\n            typeof console !== \"undefined\" &&\n            typeof console.error === \"function\"\n        ) {\n            console.error(\n                \"Unable to preventDefault inside passive event listener invocation.\",\n                data.passiveListener\n            )\n        }\n        return\n    }\n    if (!data.event.cancelable) {\n        return\n    }\n\n    data.canceled = true\n    if (typeof data.event.preventDefault === \"function\") {\n        data.event.preventDefault()\n    }\n}\n\n/**\n * @see https://dom.spec.whatwg.org/#interface-event\n * @private\n */\n/**\n * The event wrapper.\n * @constructor\n * @param {EventTarget} eventTarget The event target of this dispatching.\n * @param {Event|{type:string}} event The original event to wrap.\n */\nfunction Event(eventTarget, event) {\n    privateData.set(this, {\n        eventTarget,\n        event,\n        eventPhase: 2,\n        currentTarget: eventTarget,\n        canceled: false,\n        stopped: false,\n        immediateStopped: false,\n        passiveListener: null,\n        timeStamp: event.timeStamp || Date.now(),\n    })\n\n    // https://heycam.github.io/webidl/#Unforgeable\n    Object.defineProperty(this, \"isTrusted\", { value: false, enumerable: true })\n\n    // Define accessors\n    const keys = Object.keys(event)\n    for (let i = 0; i < keys.length; ++i) {\n        const key = keys[i]\n        if (!(key in this)) {\n            Object.defineProperty(this, key, defineRedirectDescriptor(key))\n        }\n    }\n}\n\n// Should be enumerable, but class methods are not enumerable.\nEvent.prototype = {\n    /**\n     * The type of this event.\n     * @type {string}\n     */\n    get type() {\n        return pd(this).event.type\n    },\n\n    /**\n     * The target of this event.\n     * @type {EventTarget}\n     */\n    get target() {\n        return pd(this).eventTarget\n    },\n\n    /**\n     * The target of this event.\n     * @type {EventTarget}\n     */\n    get currentTarget() {\n        return pd(this).currentTarget\n    },\n\n    /**\n     * @returns {EventTarget[]} The composed path of this event.\n     */\n    composedPath() {\n        const currentTarget = pd(this).currentTarget\n        if (currentTarget == null) {\n            return []\n        }\n        return [currentTarget]\n    },\n\n    /**\n     * Constant of NONE.\n     * @type {number}\n     */\n    get NONE() {\n        return 0\n    },\n\n    /**\n     * Constant of CAPTURING_PHASE.\n     * @type {number}\n     */\n    get CAPTURING_PHASE() {\n        return 1\n    },\n\n    /**\n     * Constant of AT_TARGET.\n     * @type {number}\n     */\n    get AT_TARGET() {\n        return 2\n    },\n\n    /**\n     * Constant of BUBBLING_PHASE.\n     * @type {number}\n     */\n    get BUBBLING_PHASE() {\n        return 3\n    },\n\n    /**\n     * The target of this event.\n     * @type {number}\n     */\n    get eventPhase() {\n        return pd(this).eventPhase\n    },\n\n    /**\n     * Stop event bubbling.\n     * @returns {void}\n     */\n    stopPropagation() {\n        const data = pd(this)\n\n        data.stopped = true\n        if (typeof data.event.stopPropagation === \"function\") {\n            data.event.stopPropagation()\n        }\n    },\n\n    /**\n     * Stop event bubbling.\n     * @returns {void}\n     */\n    stopImmediatePropagation() {\n        const data = pd(this)\n\n        data.stopped = true\n        data.immediateStopped = true\n        if (typeof data.event.stopImmediatePropagation === \"function\") {\n            data.event.stopImmediatePropagation()\n        }\n    },\n\n    /**\n     * The flag to be bubbling.\n     * @type {boolean}\n     */\n    get bubbles() {\n        return Boolean(pd(this).event.bubbles)\n    },\n\n    /**\n     * The flag to be cancelable.\n     * @type {boolean}\n     */\n    get cancelable() {\n        return Boolean(pd(this).event.cancelable)\n    },\n\n    /**\n     * Cancel this event.\n     * @returns {void}\n     */\n    preventDefault() {\n        setCancelFlag(pd(this))\n    },\n\n    /**\n     * The flag to indicate cancellation state.\n     * @type {boolean}\n     */\n    get defaultPrevented() {\n        return pd(this).canceled\n    },\n\n    /**\n     * The flag to be composed.\n     * @type {boolean}\n     */\n    get composed() {\n        return Boolean(pd(this).event.composed)\n    },\n\n    /**\n     * The unix time of this event.\n     * @type {number}\n     */\n    get timeStamp() {\n        return pd(this).timeStamp\n    },\n\n    /**\n     * The target of this event.\n     * @type {EventTarget}\n     * @deprecated\n     */\n    get srcElement() {\n        return pd(this).eventTarget\n    },\n\n    /**\n     * The flag to stop event bubbling.\n     * @type {boolean}\n     * @deprecated\n     */\n    get cancelBubble() {\n        return pd(this).stopped\n    },\n    set cancelBubble(value) {\n        if (!value) {\n            return\n        }\n        const data = pd(this)\n\n        data.stopped = true\n        if (typeof data.event.cancelBubble === \"boolean\") {\n            data.event.cancelBubble = true\n        }\n    },\n\n    /**\n     * The flag to indicate cancellation state.\n     * @type {boolean}\n     * @deprecated\n     */\n    get returnValue() {\n        return !pd(this).canceled\n    },\n    set returnValue(value) {\n        if (!value) {\n            setCancelFlag(pd(this))\n        }\n    },\n\n    /**\n     * Initialize this event object. But do nothing under event dispatching.\n     * @param {string} type The event type.\n     * @param {boolean} [bubbles=false] The flag to be possible to bubble up.\n     * @param {boolean} [cancelable=false] The flag to be possible to cancel.\n     * @deprecated\n     */\n    initEvent() {\n        // Do nothing.\n    },\n}\n\n// `constructor` is not enumerable.\nObject.defineProperty(Event.prototype, \"constructor\", {\n    value: Event,\n    configurable: true,\n    writable: true,\n})\n\n// Ensure `event instanceof window.Event` is `true`.\nif (typeof window !== \"undefined\" && typeof window.Event !== \"undefined\") {\n    Object.setPrototypeOf(Event.prototype, window.Event.prototype)\n\n    // Make association for wrappers.\n    wrappers.set(window.Event.prototype, Event)\n}\n\n/**\n * Get the property descriptor to redirect a given property.\n * @param {string} key Property name to define property descriptor.\n * @returns {PropertyDescriptor} The property descriptor to redirect the property.\n * @private\n */\nfunction defineRedirectDescriptor(key) {\n    return {\n        get() {\n            return pd(this).event[key]\n        },\n        set(value) {\n            pd(this).event[key] = value\n        },\n        configurable: true,\n        enumerable: true,\n    }\n}\n\n/**\n * Get the property descriptor to call a given method property.\n * @param {string} key Property name to define property descriptor.\n * @returns {PropertyDescriptor} The property descriptor to call the method property.\n * @private\n */\nfunction defineCallDescriptor(key) {\n    return {\n        value() {\n            const event = pd(this).event\n            return event[key].apply(event, arguments)\n        },\n        configurable: true,\n        enumerable: true,\n    }\n}\n\n/**\n * Define new wrapper class.\n * @param {Function} BaseEvent The base wrapper class.\n * @param {Object} proto The prototype of the original event.\n * @returns {Function} The defined wrapper class.\n * @private\n */\nfunction defineWrapper(BaseEvent, proto) {\n    const keys = Object.keys(proto)\n    if (keys.length === 0) {\n        return BaseEvent\n    }\n\n    /** CustomEvent */\n    function CustomEvent(eventTarget, event) {\n        BaseEvent.call(this, eventTarget, event)\n    }\n\n    CustomEvent.prototype = Object.create(BaseEvent.prototype, {\n        constructor: { value: CustomEvent, configurable: true, writable: true },\n    })\n\n    // Define accessors.\n    for (let i = 0; i < keys.length; ++i) {\n        const key = keys[i]\n        if (!(key in BaseEvent.prototype)) {\n            const descriptor = Object.getOwnPropertyDescriptor(proto, key)\n            const isFunc = typeof descriptor.value === \"function\"\n            Object.defineProperty(\n                CustomEvent.prototype,\n                key,\n                isFunc\n                    ? defineCallDescriptor(key)\n                    : defineRedirectDescriptor(key)\n            )\n        }\n    }\n\n    return CustomEvent\n}\n\n/**\n * Get the wrapper class of a given prototype.\n * @param {Object} proto The prototype of the original event to get its wrapper.\n * @returns {Function} The wrapper class.\n * @private\n */\nfunction getWrapper(proto) {\n    if (proto == null || proto === Object.prototype) {\n        return Event\n    }\n\n    let wrapper = wrappers.get(proto)\n    if (wrapper == null) {\n        wrapper = defineWrapper(getWrapper(Object.getPrototypeOf(proto)), proto)\n        wrappers.set(proto, wrapper)\n    }\n    return wrapper\n}\n\n/**\n * Wrap a given event to management a dispatching.\n * @param {EventTarget} eventTarget The event target of this dispatching.\n * @param {Object} event The event to wrap.\n * @returns {Event} The wrapper instance.\n * @private\n */\nexport function wrapEvent(eventTarget, event) {\n    const Wrapper = getWrapper(Object.getPrototypeOf(event))\n    return new Wrapper(eventTarget, event)\n}\n\n/**\n * Get the immediateStopped flag of a given event.\n * @param {Event} event The event to get.\n * @returns {boolean} The flag to stop propagation immediately.\n * @private\n */\nexport function isStopped(event) {\n    return pd(event).immediateStopped\n}\n\n/**\n * Set the current event phase of a given event.\n * @param {Event} event The event to set current target.\n * @param {number} eventPhase New event phase.\n * @returns {void}\n * @private\n */\nexport function setEventPhase(event, eventPhase) {\n    pd(event).eventPhase = eventPhase\n}\n\n/**\n * Set the current target of a given event.\n * @param {Event} event The event to set current target.\n * @param {EventTarget|null} currentTarget New current target.\n * @returns {void}\n * @private\n */\nexport function setCurrentTarget(event, currentTarget) {\n    pd(event).currentTarget = currentTarget\n}\n\n/**\n * Set a passive listener of a given event.\n * @param {Event} event The event to set current target.\n * @param {Function|null} passiveListener New passive listener.\n * @returns {void}\n * @private\n */\nexport function setPassiveListener(event, passiveListener) {\n    pd(event).passiveListener = passiveListener\n}\n",
         "import {\n    isStopped,\n    setCurrentTarget,\n    setEventPhase,\n    setPassiveListener,\n    wrapEvent,\n} from \"./event.mjs\"\n\n/**\n * @typedef {object} ListenerNode\n * @property {Function} listener\n * @property {1|2|3} listenerType\n * @property {boolean} passive\n * @property {boolean} once\n * @property {ListenerNode|null} next\n * @private\n */\n\n/**\n * @type {WeakMap<object, Map<string, ListenerNode>>}\n * @private\n */\nconst listenersMap = new WeakMap()\n\n// Listener types\nconst CAPTURE = 1\nconst BUBBLE = 2\nconst ATTRIBUTE = 3\n\n/**\n * Check whether a given value is an object or not.\n * @param {any} x The value to check.\n * @returns {boolean} `true` if the value is an object.\n */\nfunction isObject(x) {\n    return x !== null && typeof x === \"object\" //eslint-disable-line no-restricted-syntax\n}\n\n/**\n * Get listeners.\n * @param {EventTarget} eventTarget The event target to get.\n * @returns {Map<string, ListenerNode>} The listeners.\n * @private\n */\nfunction getListeners(eventTarget) {\n    const listeners = listenersMap.get(eventTarget)\n    if (listeners == null) {\n        throw new TypeError(\n            \"'this' is expected an EventTarget object, but got another value.\"\n        )\n    }\n    return listeners\n}\n\n/**\n * Get the property descriptor for the event attribute of a given event.\n * @param {string} eventName The event name to get property descriptor.\n * @returns {PropertyDescriptor} The property descriptor.\n * @private\n */\nfunction defineEventAttributeDescriptor(eventName) {\n    return {\n        get() {\n            const listeners = getListeners(this)\n            let node = listeners.get(eventName)\n            while (node != null) {\n                if (node.listenerType === ATTRIBUTE) {\n                    return node.listener\n                }\n                node = node.next\n            }\n            return null\n        },\n\n        set(listener) {\n            if (typeof listener !== \"function\" && !isObject(listener)) {\n                listener = null // eslint-disable-line no-param-reassign\n            }\n            const listeners = getListeners(this)\n\n            // Traverse to the tail while removing old value.\n            let prev = null\n            let node = listeners.get(eventName)\n            while (node != null) {\n                if (node.listenerType === ATTRIBUTE) {\n                    // Remove old value.\n                    if (prev !== null) {\n                        prev.next = node.next\n                    } else if (node.next !== null) {\n                        listeners.set(eventName, node.next)\n                    } else {\n                        listeners.delete(eventName)\n                    }\n                } else {\n                    prev = node\n                }\n\n                node = node.next\n            }\n\n            // Add new value.\n            if (listener !== null) {\n                const newNode = {\n                    listener,\n                    listenerType: ATTRIBUTE,\n                    passive: false,\n                    once: false,\n                    next: null,\n                }\n                if (prev === null) {\n                    listeners.set(eventName, newNode)\n                } else {\n                    prev.next = newNode\n                }\n            }\n        },\n        configurable: true,\n        enumerable: true,\n    }\n}\n\n/**\n * Define an event attribute (e.g. `eventTarget.onclick`).\n * @param {Object} eventTargetPrototype The event target prototype to define an event attrbite.\n * @param {string} eventName The event name to define.\n * @returns {void}\n */\nfunction defineEventAttribute(eventTargetPrototype, eventName) {\n    Object.defineProperty(\n        eventTargetPrototype,\n        `on${eventName}`,\n        defineEventAttributeDescriptor(eventName)\n    )\n}\n\n/**\n * Define a custom EventTarget with event attributes.\n * @param {string[]} eventNames Event names for event attributes.\n * @returns {EventTarget} The custom EventTarget.\n * @private\n */\nfunction defineCustomEventTarget(eventNames) {\n    /** CustomEventTarget */\n    function CustomEventTarget() {\n        EventTarget.call(this)\n    }\n\n    CustomEventTarget.prototype = Object.create(EventTarget.prototype, {\n        constructor: {\n            value: CustomEventTarget,\n            configurable: true,\n            writable: true,\n        },\n    })\n\n    for (let i = 0; i < eventNames.length; ++i) {\n        defineEventAttribute(CustomEventTarget.prototype, eventNames[i])\n    }\n\n    return CustomEventTarget\n}\n\n/**\n * EventTarget.\n *\n * - This is constructor if no arguments.\n * - This is a function which returns a CustomEventTarget constructor if there are arguments.\n *\n * For example:\n *\n *     class A extends EventTarget {}\n *     class B extends EventTarget(\"message\") {}\n *     class C extends EventTarget(\"message\", \"error\") {}\n *     class D extends EventTarget([\"message\", \"error\"]) {}\n */\nfunction EventTarget() {\n    /*eslint-disable consistent-return */\n    if (this instanceof EventTarget) {\n        listenersMap.set(this, new Map())\n        return\n    }\n    if (arguments.length === 1 && Array.isArray(arguments[0])) {\n        return defineCustomEventTarget(arguments[0])\n    }\n    if (arguments.length > 0) {\n        const types = new Array(arguments.length)\n        for (let i = 0; i < arguments.length; ++i) {\n            types[i] = arguments[i]\n        }\n        return defineCustomEventTarget(types)\n    }\n    throw new TypeError(\"Cannot call a class as a function\")\n    /*eslint-enable consistent-return */\n}\n\n// Should be enumerable, but class methods are not enumerable.\nEventTarget.prototype = {\n    /**\n     * Add a given listener to this event target.\n     * @param {string} eventName The event name to add.\n     * @param {Function} listener The listener to add.\n     * @param {boolean|{capture?:boolean,passive?:boolean,once?:boolean}} [options] The options for this listener.\n     * @returns {void}\n     */\n    addEventListener(eventName, listener, options) {\n        if (listener == null) {\n            return\n        }\n        if (typeof listener !== \"function\" && !isObject(listener)) {\n            throw new TypeError(\"'listener' should be a function or an object.\")\n        }\n\n        const listeners = getListeners(this)\n        const optionsIsObj = isObject(options)\n        const capture = optionsIsObj\n            ? Boolean(options.capture)\n            : Boolean(options)\n        const listenerType = capture ? CAPTURE : BUBBLE\n        const newNode = {\n            listener,\n            listenerType,\n            passive: optionsIsObj && Boolean(options.passive),\n            once: optionsIsObj && Boolean(options.once),\n            next: null,\n        }\n\n        // Set it as the first node if the first node is null.\n        let node = listeners.get(eventName)\n        if (node === undefined) {\n            listeners.set(eventName, newNode)\n            return\n        }\n\n        // Traverse to the tail while checking duplication..\n        let prev = null\n        while (node != null) {\n            if (\n                node.listener === listener &&\n                node.listenerType === listenerType\n            ) {\n                // Should ignore duplication.\n                return\n            }\n            prev = node\n            node = node.next\n        }\n\n        // Add it.\n        prev.next = newNode\n    },\n\n    /**\n     * Remove a given listener from this event target.\n     * @param {string} eventName The event name to remove.\n     * @param {Function} listener The listener to remove.\n     * @param {boolean|{capture?:boolean,passive?:boolean,once?:boolean}} [options] The options for this listener.\n     * @returns {void}\n     */\n    removeEventListener(eventName, listener, options) {\n        if (listener == null) {\n            return\n        }\n\n        const listeners = getListeners(this)\n        const capture = isObject(options)\n            ? Boolean(options.capture)\n            : Boolean(options)\n        const listenerType = capture ? CAPTURE : BUBBLE\n\n        let prev = null\n        let node = listeners.get(eventName)\n        while (node != null) {\n            if (\n                node.listener === listener &&\n                node.listenerType === listenerType\n            ) {\n                if (prev !== null) {\n                    prev.next = node.next\n                } else if (node.next !== null) {\n                    listeners.set(eventName, node.next)\n                } else {\n                    listeners.delete(eventName)\n                }\n                return\n            }\n\n            prev = node\n            node = node.next\n        }\n    },\n\n    /**\n     * Dispatch a given event.\n     * @param {Event|{type:string}} event The event to dispatch.\n     * @returns {boolean} `false` if canceled.\n     */\n    dispatchEvent(event) {\n        if (event == null || typeof event.type !== \"string\") {\n            throw new TypeError('\"event.type\" should be a string.')\n        }\n\n        // If listeners aren't registered, terminate.\n        const listeners = getListeners(this)\n        const eventName = event.type\n        let node = listeners.get(eventName)\n        if (node == null) {\n            return true\n        }\n\n        // Since we cannot rewrite several properties, so wrap object.\n        const wrappedEvent = wrapEvent(this, event)\n\n        // This doesn't process capturing phase and bubbling phase.\n        // This isn't participating in a tree.\n        let prev = null\n        while (node != null) {\n            // Remove this listener if it's once\n            if (node.once) {\n                if (prev !== null) {\n                    prev.next = node.next\n                } else if (node.next !== null) {\n                    listeners.set(eventName, node.next)\n                } else {\n                    listeners.delete(eventName)\n                }\n            } else {\n                prev = node\n            }\n\n            // Call this listener\n            setPassiveListener(\n                wrappedEvent,\n                node.passive ? node.listener : null\n            )\n            if (typeof node.listener === \"function\") {\n                try {\n                    node.listener.call(this, wrappedEvent)\n                } catch (err) {\n                    if (\n                        typeof console !== \"undefined\" &&\n                        typeof console.error === \"function\"\n                    ) {\n                        console.error(err)\n                    }\n                }\n            } else if (\n                node.listenerType !== ATTRIBUTE &&\n                typeof node.listener.handleEvent === \"function\"\n            ) {\n                node.listener.handleEvent(wrappedEvent)\n            }\n\n            // Break if `event.stopImmediatePropagation` was called.\n            if (isStopped(wrappedEvent)) {\n                break\n            }\n\n            node = node.next\n        }\n        setPassiveListener(wrappedEvent, null)\n        setEventPhase(wrappedEvent, 0)\n        setCurrentTarget(wrappedEvent, null)\n\n        return !wrappedEvent.defaultPrevented\n    },\n}\n\n// `constructor` is not enumerable.\nObject.defineProperty(EventTarget.prototype, \"constructor\", {\n    value: EventTarget,\n    configurable: true,\n    writable: true,\n})\n\n// Ensure `eventTarget instanceof window.EventTarget` is `true`.\nif (\n    typeof window !== \"undefined\" &&\n    typeof window.EventTarget !== \"undefined\"\n) {\n    Object.setPrototypeOf(EventTarget.prototype, window.EventTarget.prototype)\n}\n\nexport { defineEventAttribute, EventTarget }\nexport default EventTarget\n",
         "import unsupportedIterableToArray from \"./unsupportedIterableToArray.js\";\nexport default function _createForOfIteratorHelper(o, allowArrayLike) {\n  var it = typeof Symbol !== \"undefined\" && o[Symbol.iterator] || o[\"@@iterator\"];\n  if (!it) {\n    if (Array.isArray(o) || (it = unsupportedIterableToArray(o)) || allowArrayLike && o && typeof o.length === \"number\") {\n      if (it) o = it;\n      var i = 0;\n      var F = function F() {};\n      return {\n        s: F,\n        n: function n() {\n          if (i >= o.length) return {\n            done: true\n          };\n          return {\n            done: false,\n            value: o[i++]\n          };\n        },\n        e: function e(_e) {\n          throw _e;\n        },\n        f: F\n      };\n    }\n    throw new TypeError(\"Invalid attempt to iterate non-iterable instance.\\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.\");\n  }\n  var normalCompletion = true,\n    didErr = false,\n    err;\n  return {\n    s: function s() {\n      it = it.call(o);\n    },\n    n: function n() {\n      var step = it.next();\n      normalCompletion = step.done;\n      return step;\n    },\n    e: function e(_e2) {\n      didErr = true;\n      err = _e2;\n    },\n    f: function f() {\n      try {\n        if (!normalCompletion && it[\"return\"] != null) it[\"return\"]();\n      } finally {\n        if (didErr) throw err;\n      }\n    }\n  };\n}",
-        "import arrayWithHoles from \"./arrayWithHoles.js\";\nimport iterableToArrayLimit from \"./iterableToArrayLimit.js\";\nimport unsupportedIterableToArray from \"./unsupportedIterableToArray.js\";\nimport nonIterableRest from \"./nonIterableRest.js\";\nexport default function _slicedToArray(arr, i) {\n  return arrayWithHoles(arr) || iterableToArrayLimit(arr, i) || unsupportedIterableToArray(arr, i) || nonIterableRest();\n}",
-        "export default function _arrayWithHoles(arr) {\n  if (Array.isArray(arr)) return arr;\n}",
-        "export default function _iterableToArrayLimit(arr, i) {\n  var _i = null == arr ? null : \"undefined\" != typeof Symbol && arr[Symbol.iterator] || arr[\"@@iterator\"];\n  if (null != _i) {\n    var _s,\n      _e,\n      _x,\n      _r,\n      _arr = [],\n      _n = !0,\n      _d = !1;\n    try {\n      if (_x = (_i = _i.call(arr)).next, 0 === i) {\n        if (Object(_i) !== _i) return;\n        _n = !1;\n      } else for (; !(_n = (_s = _x.call(_i)).done) && (_arr.push(_s.value), _arr.length !== i); _n = !0);\n    } catch (err) {\n      _d = !0, _e = err;\n    } finally {\n      try {\n        if (!_n && null != _i[\"return\"] && (_r = _i[\"return\"](), Object(_r) !== _r)) return;\n      } finally {\n        if (_d) throw _e;\n      }\n    }\n    return _arr;\n  }\n}",
-        "export default function _nonIterableRest() {\n  throw new TypeError(\"Invalid attempt to destructure non-iterable instance.\\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.\");\n}",
         "export default function _OverloadYield(value, kind) {\n  this.v = value, this.k = kind;\n}",
         "import OverloadYield from \"./OverloadYield.js\";\nexport default function _awaitAsyncGenerator(value) {\n  return new OverloadYield(value, 0);\n}",
         "import OverloadYield from \"./OverloadYield.js\";\nexport default function AsyncGenerator(gen) {\n  var front, back;\n  function resume(key, arg) {\n    try {\n      var result = gen[key](arg),\n        value = result.value,\n        overloaded = value instanceof OverloadYield;\n      Promise.resolve(overloaded ? value.v : value).then(function (arg) {\n        if (overloaded) {\n          var nextKey = \"return\" === key ? \"return\" : \"next\";\n          if (!value.k || arg.done) return resume(nextKey, arg);\n          arg = gen[nextKey](arg).value;\n        }\n        settle(result.done ? \"return\" : \"normal\", arg);\n      }, function (err) {\n        resume(\"throw\", err);\n      });\n    } catch (err) {\n      settle(\"throw\", err);\n    }\n  }\n  function settle(type, value) {\n    switch (type) {\n      case \"return\":\n        front.resolve({\n          value: value,\n          done: !0\n        });\n        break;\n      case \"throw\":\n        front.reject(value);\n        break;\n      default:\n        front.resolve({\n          value: value,\n          done: !1\n        });\n    }\n    (front = front.next) ? resume(front.key, front.arg) : back = null;\n  }\n  this._invoke = function (key, arg) {\n    return new Promise(function (resolve, reject) {\n      var request = {\n        key: key,\n        arg: arg,\n        resolve: resolve,\n        reject: reject,\n        next: null\n      };\n      back ? back = back.next = request : (front = back = request, resume(key, arg));\n    });\n  }, \"function\" != typeof gen[\"return\"] && (this[\"return\"] = void 0);\n}\nAsyncGenerator.prototype[\"function\" == typeof Symbol && Symbol.asyncIterator || \"@@asyncIterator\"] = function () {\n  return this;\n}, AsyncGenerator.prototype.next = function (arg) {\n  return this._invoke(\"next\", arg);\n}, AsyncGenerator.prototype[\"throw\"] = function (arg) {\n  return this._invoke(\"throw\", arg);\n}, AsyncGenerator.prototype[\"return\"] = function (arg) {\n  return this._invoke(\"return\", arg);\n};",
         "import AsyncGenerator from \"./AsyncGenerator.js\";\nexport default function _wrapAsyncGenerator(fn) {\n  return function () {\n    return new AsyncGenerator(fn.apply(this, arguments));\n  };\n}",
         "import OverloadYield from \"./OverloadYield.js\";\nexport default function _asyncGeneratorDelegate(inner) {\n  var iter = {},\n    waiting = !1;\n  function pump(key, value) {\n    return waiting = !0, value = new Promise(function (resolve) {\n      resolve(inner[key](value));\n    }), {\n      done: !1,\n      value: new OverloadYield(value, 1)\n    };\n  }\n  return iter[\"undefined\" != typeof Symbol && Symbol.iterator || \"@@iterator\"] = function () {\n    return this;\n  }, iter.next = function (value) {\n    return waiting ? (waiting = !1, value) : pump(\"next\", value);\n  }, \"function\" == typeof inner[\"throw\"] && (iter[\"throw\"] = function (value) {\n    if (waiting) throw waiting = !1, value;\n    return pump(\"throw\", value);\n  }), \"function\" == typeof inner[\"return\"] && (iter[\"return\"] = function (value) {\n    return waiting ? (waiting = !1, value) : pump(\"return\", value);\n  }), iter;\n}",
         "export default function _asyncIterator(iterable) {\n  var method,\n    async,\n    sync,\n    retry = 2;\n  for (\"undefined\" != typeof Symbol && (async = Symbol.asyncIterator, sync = Symbol.iterator); retry--;) {\n    if (async && null != (method = iterable[async])) return method.call(iterable);\n    if (sync && null != (method = iterable[sync])) return new AsyncFromSyncIterator(method.call(iterable));\n    async = \"@@asyncIterator\", sync = \"@@iterator\";\n  }\n  throw new TypeError(\"Object is not async iterable\");\n}\nfunction AsyncFromSyncIterator(s) {\n  function AsyncFromSyncIteratorContinuation(r) {\n    if (Object(r) !== r) return Promise.reject(new TypeError(r + \" is not an object.\"));\n    var done = r.done;\n    return Promise.resolve(r.value).then(function (value) {\n      return {\n        value: value,\n        done: done\n      };\n    });\n  }\n  return AsyncFromSyncIterator = function AsyncFromSyncIterator(s) {\n    this.s = s, this.n = s.next;\n  }, AsyncFromSyncIterator.prototype = {\n    s: null,\n    n: null,\n    next: function next() {\n      return AsyncFromSyncIteratorContinuation(this.n.apply(this.s, arguments));\n    },\n    \"return\": function _return(value) {\n      var ret = this.s[\"return\"];\n      return void 0 === ret ? Promise.resolve({\n        value: value,\n        done: !0\n      }) : AsyncFromSyncIteratorContinuation(ret.apply(this.s, arguments));\n    },\n    \"throw\": function _throw(value) {\n      var thr = this.s[\"return\"];\n      return void 0 === thr ? Promise.reject(value) : AsyncFromSyncIteratorContinuation(thr.apply(this.s, arguments));\n    }\n  }, new AsyncFromSyncIterator(s);\n}",
         "/// @file\n/// @addtogroup flatbuffers_javascript_api\n/// @{\n/// @cond FLATBUFFERS_INTERNAL\n\n/**\n * @fileoverview\n *\n * Need to suppress 'global this' error so the Node.js export line doesn't cause\n * closure compile to error out.\n * @suppress {globalThis}\n */\n\n/**\n * @const\n * @namespace\n */\nvar flatbuffers = {};\n\n/**\n * @typedef {number}\n */\nflatbuffers.Offset;\n\n/**\n * @typedef {{\n *   bb: flatbuffers.ByteBuffer,\n *   bb_pos: number\n * }}\n */\nflatbuffers.Table;\n\n/**\n * @type {number}\n * @const\n */\nflatbuffers.SIZEOF_SHORT = 2;\n\n/**\n * @type {number}\n * @const\n */\nflatbuffers.SIZEOF_INT = 4;\n\n/**\n * @type {number}\n * @const\n */\nflatbuffers.FILE_IDENTIFIER_LENGTH = 4;\n\n/**\n * @enum {number}\n */\nflatbuffers.Encoding = {\n  UTF8_BYTES: 1,\n  UTF16_STRING: 2\n};\n\n/**\n * @type {Int32Array}\n * @const\n */\nflatbuffers.int32 = new Int32Array(2);\n\n/**\n * @type {Float32Array}\n * @const\n */\nflatbuffers.float32 = new Float32Array(flatbuffers.int32.buffer);\n\n/**\n * @type {Float64Array}\n * @const\n */\nflatbuffers.float64 = new Float64Array(flatbuffers.int32.buffer);\n\n/**\n * @type {boolean}\n * @const\n */\nflatbuffers.isLittleEndian = new Uint16Array(new Uint8Array([1, 0]).buffer)[0] === 1;\n\n////////////////////////////////////////////////////////////////////////////////\n\n/**\n * @constructor\n * @param {number} low\n * @param {number} high\n */\nflatbuffers.Long = function(low, high) {\n  /**\n   * @type {number}\n   * @const\n   */\n  this.low = low | 0;\n\n  /**\n   * @type {number}\n   * @const\n   */\n  this.high = high | 0;\n};\n\n/**\n * @param {number} low\n * @param {number} high\n * @returns {flatbuffers.Long}\n */\nflatbuffers.Long.create = function(low, high) {\n  // Special-case zero to avoid GC overhead for default values\n  return low == 0 && high == 0 ? flatbuffers.Long.ZERO : new flatbuffers.Long(low, high);\n};\n\n/**\n * @returns {number}\n */\nflatbuffers.Long.prototype.toFloat64 = function() {\n  return (this.low >>> 0) + this.high * 0x100000000;\n};\n\n/**\n * @param {flatbuffers.Long} other\n * @returns {boolean}\n */\nflatbuffers.Long.prototype.equals = function(other) {\n  return this.low == other.low && this.high == other.high;\n};\n\n/**\n * @type {flatbuffers.Long}\n * @const\n */\nflatbuffers.Long.ZERO = new flatbuffers.Long(0, 0);\n\n/// @endcond\n////////////////////////////////////////////////////////////////////////////////\n/**\n * Create a FlatBufferBuilder.\n *\n * @constructor\n * @param {number=} opt_initial_size\n */\nflatbuffers.Builder = function(opt_initial_size) {\n  if (!opt_initial_size) {\n    var initial_size = 1024;\n  } else {\n    var initial_size = opt_initial_size;\n  }\n\n  /**\n   * @type {flatbuffers.ByteBuffer}\n   * @private\n   */\n  this.bb = flatbuffers.ByteBuffer.allocate(initial_size);\n\n  /**\n   * Remaining space in the ByteBuffer.\n   *\n   * @type {number}\n   * @private\n   */\n  this.space = initial_size;\n\n  /**\n   * Minimum alignment encountered so far.\n   *\n   * @type {number}\n   * @private\n   */\n  this.minalign = 1;\n\n  /**\n   * The vtable for the current table.\n   *\n   * @type {Array.<number>}\n   * @private\n   */\n  this.vtable = null;\n\n  /**\n   * The amount of fields we're actually using.\n   *\n   * @type {number}\n   * @private\n   */\n  this.vtable_in_use = 0;\n\n  /**\n   * Whether we are currently serializing a table.\n   *\n   * @type {boolean}\n   * @private\n   */\n  this.isNested = false;\n\n  /**\n   * Starting offset of the current struct/table.\n   *\n   * @type {number}\n   * @private\n   */\n  this.object_start = 0;\n\n  /**\n   * List of offsets of all vtables.\n   *\n   * @type {Array.<number>}\n   * @private\n   */\n  this.vtables = [];\n\n  /**\n   * For the current vector being built.\n   *\n   * @type {number}\n   * @private\n   */\n  this.vector_num_elems = 0;\n\n  /**\n   * False omits default values from the serialized data\n   *\n   * @type {boolean}\n   * @private\n   */\n  this.force_defaults = false;\n};\n\nflatbuffers.Builder.prototype.clear = function() {\n  this.bb.clear();\n  this.space = this.bb.capacity();\n  this.minalign = 1;\n  this.vtable = null;\n  this.vtable_in_use = 0;\n  this.isNested = false;\n  this.object_start = 0;\n  this.vtables = [];\n  this.vector_num_elems = 0;\n  this.force_defaults = false;\n};\n\n/**\n * In order to save space, fields that are set to their default value\n * don't get serialized into the buffer. Forcing defaults provides a\n * way to manually disable this optimization.\n *\n * @param {boolean} forceDefaults true always serializes default values\n */\nflatbuffers.Builder.prototype.forceDefaults = function(forceDefaults) {\n  this.force_defaults = forceDefaults;\n};\n\n/**\n * Get the ByteBuffer representing the FlatBuffer. Only call this after you've\n * called finish(). The actual data starts at the ByteBuffer's current position,\n * not necessarily at 0.\n *\n * @returns {flatbuffers.ByteBuffer}\n */\nflatbuffers.Builder.prototype.dataBuffer = function() {\n  return this.bb;\n};\n\n/**\n * Get the bytes representing the FlatBuffer. Only call this after you've\n * called finish().\n *\n * @returns {Uint8Array}\n */\nflatbuffers.Builder.prototype.asUint8Array = function() {\n  return this.bb.bytes().subarray(this.bb.position(), this.bb.position() + this.offset());\n};\n\n/// @cond FLATBUFFERS_INTERNAL\n/**\n * Prepare to write an element of `size` after `additional_bytes` have been\n * written, e.g. if you write a string, you need to align such the int length\n * field is aligned to 4 bytes, and the string data follows it directly. If all\n * you need to do is alignment, `additional_bytes` will be 0.\n *\n * @param {number} size This is the of the new element to write\n * @param {number} additional_bytes The padding size\n */\nflatbuffers.Builder.prototype.prep = function(size, additional_bytes) {\n  // Track the biggest thing we've ever aligned to.\n  if (size > this.minalign) {\n    this.minalign = size;\n  }\n\n  // Find the amount of alignment needed such that `size` is properly\n  // aligned after `additional_bytes`\n  var align_size = ((~(this.bb.capacity() - this.space + additional_bytes)) + 1) & (size - 1);\n\n  // Reallocate the buffer if needed.\n  while (this.space < align_size + size + additional_bytes) {\n    var old_buf_size = this.bb.capacity();\n    this.bb = flatbuffers.Builder.growByteBuffer(this.bb);\n    this.space += this.bb.capacity() - old_buf_size;\n  }\n\n  this.pad(align_size);\n};\n\n/**\n * @param {number} byte_size\n */\nflatbuffers.Builder.prototype.pad = function(byte_size) {\n  for (var i = 0; i < byte_size; i++) {\n    this.bb.writeInt8(--this.space, 0);\n  }\n};\n\n/**\n * @param {number} value\n */\nflatbuffers.Builder.prototype.writeInt8 = function(value) {\n  this.bb.writeInt8(this.space -= 1, value);\n};\n\n/**\n * @param {number} value\n */\nflatbuffers.Builder.prototype.writeInt16 = function(value) {\n  this.bb.writeInt16(this.space -= 2, value);\n};\n\n/**\n * @param {number} value\n */\nflatbuffers.Builder.prototype.writeInt32 = function(value) {\n  this.bb.writeInt32(this.space -= 4, value);\n};\n\n/**\n * @param {flatbuffers.Long} value\n */\nflatbuffers.Builder.prototype.writeInt64 = function(value) {\n  this.bb.writeInt64(this.space -= 8, value);\n};\n\n/**\n * @param {number} value\n */\nflatbuffers.Builder.prototype.writeFloat32 = function(value) {\n  this.bb.writeFloat32(this.space -= 4, value);\n};\n\n/**\n * @param {number} value\n */\nflatbuffers.Builder.prototype.writeFloat64 = function(value) {\n  this.bb.writeFloat64(this.space -= 8, value);\n};\n/// @endcond\n\n/**\n * Add an `int8` to the buffer, properly aligned, and grows the buffer (if necessary).\n * @param {number} value The `int8` to add the the buffer.\n */\nflatbuffers.Builder.prototype.addInt8 = function(value) {\n  this.prep(1, 0);\n  this.writeInt8(value);\n};\n\n/**\n * Add an `int16` to the buffer, properly aligned, and grows the buffer (if necessary).\n * @param {number} value The `int16` to add the the buffer.\n */\nflatbuffers.Builder.prototype.addInt16 = function(value) {\n  this.prep(2, 0);\n  this.writeInt16(value);\n};\n\n/**\n * Add an `int32` to the buffer, properly aligned, and grows the buffer (if necessary).\n * @param {number} value The `int32` to add the the buffer.\n */\nflatbuffers.Builder.prototype.addInt32 = function(value) {\n  this.prep(4, 0);\n  this.writeInt32(value);\n};\n\n/**\n * Add an `int64` to the buffer, properly aligned, and grows the buffer (if necessary).\n * @param {flatbuffers.Long} value The `int64` to add the the buffer.\n */\nflatbuffers.Builder.prototype.addInt64 = function(value) {\n  this.prep(8, 0);\n  this.writeInt64(value);\n};\n\n/**\n * Add a `float32` to the buffer, properly aligned, and grows the buffer (if necessary).\n * @param {number} value The `float32` to add the the buffer.\n */\nflatbuffers.Builder.prototype.addFloat32 = function(value) {\n  this.prep(4, 0);\n  this.writeFloat32(value);\n};\n\n/**\n * Add a `float64` to the buffer, properly aligned, and grows the buffer (if necessary).\n * @param {number} value The `float64` to add the the buffer.\n */\nflatbuffers.Builder.prototype.addFloat64 = function(value) {\n  this.prep(8, 0);\n  this.writeFloat64(value);\n};\n\n/// @cond FLATBUFFERS_INTERNAL\n/**\n * @param {number} voffset\n * @param {number} value\n * @param {number} defaultValue\n */\nflatbuffers.Builder.prototype.addFieldInt8 = function(voffset, value, defaultValue) {\n  if (this.force_defaults || value != defaultValue) {\n    this.addInt8(value);\n    this.slot(voffset);\n  }\n};\n\n/**\n * @param {number} voffset\n * @param {number} value\n * @param {number} defaultValue\n */\nflatbuffers.Builder.prototype.addFieldInt16 = function(voffset, value, defaultValue) {\n  if (this.force_defaults || value != defaultValue) {\n    this.addInt16(value);\n    this.slot(voffset);\n  }\n};\n\n/**\n * @param {number} voffset\n * @param {number} value\n * @param {number} defaultValue\n */\nflatbuffers.Builder.prototype.addFieldInt32 = function(voffset, value, defaultValue) {\n  if (this.force_defaults || value != defaultValue) {\n    this.addInt32(value);\n    this.slot(voffset);\n  }\n};\n\n/**\n * @param {number} voffset\n * @param {flatbuffers.Long} value\n * @param {flatbuffers.Long} defaultValue\n */\nflatbuffers.Builder.prototype.addFieldInt64 = function(voffset, value, defaultValue) {\n  if (this.force_defaults || !value.equals(defaultValue)) {\n    this.addInt64(value);\n    this.slot(voffset);\n  }\n};\n\n/**\n * @param {number} voffset\n * @param {number} value\n * @param {number} defaultValue\n */\nflatbuffers.Builder.prototype.addFieldFloat32 = function(voffset, value, defaultValue) {\n  if (this.force_defaults || value != defaultValue) {\n    this.addFloat32(value);\n    this.slot(voffset);\n  }\n};\n\n/**\n * @param {number} voffset\n * @param {number} value\n * @param {number} defaultValue\n */\nflatbuffers.Builder.prototype.addFieldFloat64 = function(voffset, value, defaultValue) {\n  if (this.force_defaults || value != defaultValue) {\n    this.addFloat64(value);\n    this.slot(voffset);\n  }\n};\n\n/**\n * @param {number} voffset\n * @param {flatbuffers.Offset} value\n * @param {flatbuffers.Offset} defaultValue\n */\nflatbuffers.Builder.prototype.addFieldOffset = function(voffset, value, defaultValue) {\n  if (this.force_defaults || value != defaultValue) {\n    this.addOffset(value);\n    this.slot(voffset);\n  }\n};\n\n/**\n * Structs are stored inline, so nothing additional is being added. `d` is always 0.\n *\n * @param {number} voffset\n * @param {flatbuffers.Offset} value\n * @param {flatbuffers.Offset} defaultValue\n */\nflatbuffers.Builder.prototype.addFieldStruct = function(voffset, value, defaultValue) {\n  if (value != defaultValue) {\n    this.nested(value);\n    this.slot(voffset);\n  }\n};\n\n/**\n * Structures are always stored inline, they need to be created right\n * where they're used.  You'll get this assertion failure if you\n * created it elsewhere.\n *\n * @param {flatbuffers.Offset} obj The offset of the created object\n */\nflatbuffers.Builder.prototype.nested = function(obj) {\n  if (obj != this.offset()) {\n    throw new Error('FlatBuffers: struct must be serialized inline.');\n  }\n};\n\n/**\n * Should not be creating any other object, string or vector\n * while an object is being constructed\n */\nflatbuffers.Builder.prototype.notNested = function() {\n  if (this.isNested) {\n    throw new Error('FlatBuffers: object serialization must not be nested.');\n  }\n};\n\n/**\n * Set the current vtable at `voffset` to the current location in the buffer.\n *\n * @param {number} voffset\n */\nflatbuffers.Builder.prototype.slot = function(voffset) {\n  this.vtable[voffset] = this.offset();\n};\n\n/**\n * @returns {flatbuffers.Offset} Offset relative to the end of the buffer.\n */\nflatbuffers.Builder.prototype.offset = function() {\n  return this.bb.capacity() - this.space;\n};\n\n/**\n * Doubles the size of the backing ByteBuffer and copies the old data towards\n * the end of the new buffer (since we build the buffer backwards).\n *\n * @param {flatbuffers.ByteBuffer} bb The current buffer with the existing data\n * @returns {flatbuffers.ByteBuffer} A new byte buffer with the old data copied\n * to it. The data is located at the end of the buffer.\n *\n * uint8Array.set() formally takes {Array<number>|ArrayBufferView}, so to pass\n * it a uint8Array we need to suppress the type check:\n * @suppress {checkTypes}\n */\nflatbuffers.Builder.growByteBuffer = function(bb) {\n  var old_buf_size = bb.capacity();\n\n  // Ensure we don't grow beyond what fits in an int.\n  if (old_buf_size & 0xC0000000) {\n    throw new Error('FlatBuffers: cannot grow buffer beyond 2 gigabytes.');\n  }\n\n  var new_buf_size = old_buf_size << 1;\n  var nbb = flatbuffers.ByteBuffer.allocate(new_buf_size);\n  nbb.setPosition(new_buf_size - old_buf_size);\n  nbb.bytes().set(bb.bytes(), new_buf_size - old_buf_size);\n  return nbb;\n};\n/// @endcond\n\n/**\n * Adds on offset, relative to where it will be written.\n *\n * @param {flatbuffers.Offset} offset The offset to add.\n */\nflatbuffers.Builder.prototype.addOffset = function(offset) {\n  this.prep(flatbuffers.SIZEOF_INT, 0); // Ensure alignment is already done.\n  this.writeInt32(this.offset() - offset + flatbuffers.SIZEOF_INT);\n};\n\n/// @cond FLATBUFFERS_INTERNAL\n/**\n * Start encoding a new object in the buffer.  Users will not usually need to\n * call this directly. The FlatBuffers compiler will generate helper methods\n * that call this method internally.\n *\n * @param {number} numfields\n */\nflatbuffers.Builder.prototype.startObject = function(numfields) {\n  this.notNested();\n  if (this.vtable == null) {\n    this.vtable = [];\n  }\n  this.vtable_in_use = numfields;\n  for (var i = 0; i < numfields; i++) {\n    this.vtable[i] = 0; // This will push additional elements as needed\n  }\n  this.isNested = true;\n  this.object_start = this.offset();\n};\n\n/**\n * Finish off writing the object that is under construction.\n *\n * @returns {flatbuffers.Offset} The offset to the object inside `dataBuffer`\n */\nflatbuffers.Builder.prototype.endObject = function() {\n  if (this.vtable == null || !this.isNested) {\n    throw new Error('FlatBuffers: endObject called without startObject');\n  }\n\n  this.addInt32(0);\n  var vtableloc = this.offset();\n\n  // Trim trailing zeroes.\n  var i = this.vtable_in_use - 1;\n  for (; i >= 0 && this.vtable[i] == 0; i--) {}\n  var trimmed_size = i + 1;\n\n  // Write out the current vtable.\n  for (; i >= 0; i--) {\n    // Offset relative to the start of the table.\n    this.addInt16(this.vtable[i] != 0 ? vtableloc - this.vtable[i] : 0);\n  }\n\n  var standard_fields = 2; // The fields below:\n  this.addInt16(vtableloc - this.object_start);\n  var len = (trimmed_size + standard_fields) * flatbuffers.SIZEOF_SHORT;\n  this.addInt16(len);\n\n  // Search for an existing vtable that matches the current one.\n  var existing_vtable = 0;\n  var vt1 = this.space;\nouter_loop:\n  for (i = 0; i < this.vtables.length; i++) {\n    var vt2 = this.bb.capacity() - this.vtables[i];\n    if (len == this.bb.readInt16(vt2)) {\n      for (var j = flatbuffers.SIZEOF_SHORT; j < len; j += flatbuffers.SIZEOF_SHORT) {\n        if (this.bb.readInt16(vt1 + j) != this.bb.readInt16(vt2 + j)) {\n          continue outer_loop;\n        }\n      }\n      existing_vtable = this.vtables[i];\n      break;\n    }\n  }\n\n  if (existing_vtable) {\n    // Found a match:\n    // Remove the current vtable.\n    this.space = this.bb.capacity() - vtableloc;\n\n    // Point table to existing vtable.\n    this.bb.writeInt32(this.space, existing_vtable - vtableloc);\n  } else {\n    // No match:\n    // Add the location of the current vtable to the list of vtables.\n    this.vtables.push(this.offset());\n\n    // Point table to current vtable.\n    this.bb.writeInt32(this.bb.capacity() - vtableloc, this.offset() - vtableloc);\n  }\n\n  this.isNested = false;\n  return vtableloc;\n};\n/// @endcond\n\n/**\n * Finalize a buffer, poiting to the given `root_table`.\n *\n * @param {flatbuffers.Offset} root_table\n * @param {string=} opt_file_identifier\n */\nflatbuffers.Builder.prototype.finish = function(root_table, opt_file_identifier) {\n  if (opt_file_identifier) {\n    var file_identifier = opt_file_identifier;\n    this.prep(this.minalign, flatbuffers.SIZEOF_INT +\n      flatbuffers.FILE_IDENTIFIER_LENGTH);\n    if (file_identifier.length != flatbuffers.FILE_IDENTIFIER_LENGTH) {\n      throw new Error('FlatBuffers: file identifier must be length ' +\n        flatbuffers.FILE_IDENTIFIER_LENGTH);\n    }\n    for (var i = flatbuffers.FILE_IDENTIFIER_LENGTH - 1; i >= 0; i--) {\n      this.writeInt8(file_identifier.charCodeAt(i));\n    }\n  }\n  this.prep(this.minalign, flatbuffers.SIZEOF_INT);\n  this.addOffset(root_table);\n  this.bb.setPosition(this.space);\n};\n\n/// @cond FLATBUFFERS_INTERNAL\n/**\n * This checks a required field has been set in a given table that has\n * just been constructed.\n *\n * @param {flatbuffers.Offset} table\n * @param {number} field\n */\nflatbuffers.Builder.prototype.requiredField = function(table, field) {\n  var table_start = this.bb.capacity() - table;\n  var vtable_start = table_start - this.bb.readInt32(table_start);\n  var ok = this.bb.readInt16(vtable_start + field) != 0;\n\n  // If this fails, the caller will show what field needs to be set.\n  if (!ok) {\n    throw new Error('FlatBuffers: field ' + field + ' must be set');\n  }\n};\n\n/**\n * Start a new array/vector of objects.  Users usually will not call\n * this directly. The FlatBuffers compiler will create a start/end\n * method for vector types in generated code.\n *\n * @param {number} elem_size The size of each element in the array\n * @param {number} num_elems The number of elements in the array\n * @param {number} alignment The alignment of the array\n */\nflatbuffers.Builder.prototype.startVector = function(elem_size, num_elems, alignment) {\n  this.notNested();\n  this.vector_num_elems = num_elems;\n  this.prep(flatbuffers.SIZEOF_INT, elem_size * num_elems);\n  this.prep(alignment, elem_size * num_elems); // Just in case alignment > int.\n};\n\n/**\n * Finish off the creation of an array and all its elements. The array must be\n * created with `startVector`.\n *\n * @returns {flatbuffers.Offset} The offset at which the newly created array\n * starts.\n */\nflatbuffers.Builder.prototype.endVector = function() {\n  this.writeInt32(this.vector_num_elems);\n  return this.offset();\n};\n/// @endcond\n\n/**\n * Encode the string `s` in the buffer using UTF-8. If a Uint8Array is passed\n * instead of a string, it is assumed to contain valid UTF-8 encoded data.\n *\n * @param {string|Uint8Array} s The string to encode\n * @return {flatbuffers.Offset} The offset in the buffer where the encoded string starts\n */\nflatbuffers.Builder.prototype.createString = function(s) {\n  if (s instanceof Uint8Array) {\n    var utf8 = s;\n  } else {\n    var utf8 = [];\n    var i = 0;\n\n    while (i < s.length) {\n      var codePoint;\n\n      // Decode UTF-16\n      var a = s.charCodeAt(i++);\n      if (a < 0xD800 || a >= 0xDC00) {\n        codePoint = a;\n      } else {\n        var b = s.charCodeAt(i++);\n        codePoint = (a << 10) + b + (0x10000 - (0xD800 << 10) - 0xDC00);\n      }\n\n      // Encode UTF-8\n      if (codePoint < 0x80) {\n        utf8.push(codePoint);\n      } else {\n        if (codePoint < 0x800) {\n          utf8.push(((codePoint >> 6) & 0x1F) | 0xC0);\n        } else {\n          if (codePoint < 0x10000) {\n            utf8.push(((codePoint >> 12) & 0x0F) | 0xE0);\n          } else {\n            utf8.push(\n              ((codePoint >> 18) & 0x07) | 0xF0,\n              ((codePoint >> 12) & 0x3F) | 0x80);\n          }\n          utf8.push(((codePoint >> 6) & 0x3F) | 0x80);\n        }\n        utf8.push((codePoint & 0x3F) | 0x80);\n      }\n    }\n  }\n\n  this.addInt8(0);\n  this.startVector(1, utf8.length, 1);\n  this.bb.setPosition(this.space -= utf8.length);\n  for (var i = 0, offset = this.space, bytes = this.bb.bytes(); i < utf8.length; i++) {\n    bytes[offset++] = utf8[i];\n  }\n  return this.endVector();\n};\n\n/**\n * A helper function to avoid generated code depending on this file directly.\n *\n * @param {number} low\n * @param {number} high\n * @returns {flatbuffers.Long}\n */\nflatbuffers.Builder.prototype.createLong = function(low, high) {\n  return flatbuffers.Long.create(low, high);\n};\n////////////////////////////////////////////////////////////////////////////////\n/// @cond FLATBUFFERS_INTERNAL\n/**\n * Create a new ByteBuffer with a given array of bytes (`Uint8Array`).\n *\n * @constructor\n * @param {Uint8Array} bytes\n */\nflatbuffers.ByteBuffer = function(bytes) {\n  /**\n   * @type {Uint8Array}\n   * @private\n   */\n  this.bytes_ = bytes;\n\n  /**\n   * @type {number}\n   * @private\n   */\n  this.position_ = 0;\n};\n\n/**\n * Create and allocate a new ByteBuffer with a given size.\n *\n * @param {number} byte_size\n * @returns {flatbuffers.ByteBuffer}\n */\nflatbuffers.ByteBuffer.allocate = function(byte_size) {\n  return new flatbuffers.ByteBuffer(new Uint8Array(byte_size));\n};\n\nflatbuffers.ByteBuffer.prototype.clear = function() {\n  this.position_ = 0;\n};\n\n/**\n * Get the underlying `Uint8Array`.\n *\n * @returns {Uint8Array}\n */\nflatbuffers.ByteBuffer.prototype.bytes = function() {\n  return this.bytes_;\n};\n\n/**\n * Get the buffer's position.\n *\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.position = function() {\n  return this.position_;\n};\n\n/**\n * Set the buffer's position.\n *\n * @param {number} position\n */\nflatbuffers.ByteBuffer.prototype.setPosition = function(position) {\n  this.position_ = position;\n};\n\n/**\n * Get the buffer's capacity.\n *\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.capacity = function() {\n  return this.bytes_.length;\n};\n\n/**\n * @param {number} offset\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.readInt8 = function(offset) {\n  return this.readUint8(offset) << 24 >> 24;\n};\n\n/**\n * @param {number} offset\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.readUint8 = function(offset) {\n  return this.bytes_[offset];\n};\n\n/**\n * @param {number} offset\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.readInt16 = function(offset) {\n  return this.readUint16(offset) << 16 >> 16;\n};\n\n/**\n * @param {number} offset\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.readUint16 = function(offset) {\n  return this.bytes_[offset] | this.bytes_[offset + 1] << 8;\n};\n\n/**\n * @param {number} offset\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.readInt32 = function(offset) {\n  return this.bytes_[offset] | this.bytes_[offset + 1] << 8 | this.bytes_[offset + 2] << 16 | this.bytes_[offset + 3] << 24;\n};\n\n/**\n * @param {number} offset\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.readUint32 = function(offset) {\n  return this.readInt32(offset) >>> 0;\n};\n\n/**\n * @param {number} offset\n * @returns {flatbuffers.Long}\n */\nflatbuffers.ByteBuffer.prototype.readInt64 = function(offset) {\n  return new flatbuffers.Long(this.readInt32(offset), this.readInt32(offset + 4));\n};\n\n/**\n * @param {number} offset\n * @returns {flatbuffers.Long}\n */\nflatbuffers.ByteBuffer.prototype.readUint64 = function(offset) {\n  return new flatbuffers.Long(this.readUint32(offset), this.readUint32(offset + 4));\n};\n\n/**\n * @param {number} offset\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.readFloat32 = function(offset) {\n  flatbuffers.int32[0] = this.readInt32(offset);\n  return flatbuffers.float32[0];\n};\n\n/**\n * @param {number} offset\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.readFloat64 = function(offset) {\n  flatbuffers.int32[flatbuffers.isLittleEndian ? 0 : 1] = this.readInt32(offset);\n  flatbuffers.int32[flatbuffers.isLittleEndian ? 1 : 0] = this.readInt32(offset + 4);\n  return flatbuffers.float64[0];\n};\n\n/**\n * @param {number} offset\n * @param {number|boolean} value\n */\nflatbuffers.ByteBuffer.prototype.writeInt8 = function(offset, value) {\n  this.bytes_[offset] = /** @type {number} */(value);\n};\n\n/**\n * @param {number} offset\n * @param {number} value\n */\nflatbuffers.ByteBuffer.prototype.writeUint8 = function(offset, value) {\n  this.bytes_[offset] = value;\n};\n\n/**\n * @param {number} offset\n * @param {number} value\n */\nflatbuffers.ByteBuffer.prototype.writeInt16 = function(offset, value) {\n  this.bytes_[offset] = value;\n  this.bytes_[offset + 1] = value >> 8;\n};\n\n/**\n * @param {number} offset\n * @param {number} value\n */\nflatbuffers.ByteBuffer.prototype.writeUint16 = function(offset, value) {\n    this.bytes_[offset] = value;\n    this.bytes_[offset + 1] = value >> 8;\n};\n\n/**\n * @param {number} offset\n * @param {number} value\n */\nflatbuffers.ByteBuffer.prototype.writeInt32 = function(offset, value) {\n  this.bytes_[offset] = value;\n  this.bytes_[offset + 1] = value >> 8;\n  this.bytes_[offset + 2] = value >> 16;\n  this.bytes_[offset + 3] = value >> 24;\n};\n\n/**\n * @param {number} offset\n * @param {number} value\n */\nflatbuffers.ByteBuffer.prototype.writeUint32 = function(offset, value) {\n    this.bytes_[offset] = value;\n    this.bytes_[offset + 1] = value >> 8;\n    this.bytes_[offset + 2] = value >> 16;\n    this.bytes_[offset + 3] = value >> 24;\n};\n\n/**\n * @param {number} offset\n * @param {flatbuffers.Long} value\n */\nflatbuffers.ByteBuffer.prototype.writeInt64 = function(offset, value) {\n  this.writeInt32(offset, value.low);\n  this.writeInt32(offset + 4, value.high);\n};\n\n/**\n * @param {number} offset\n * @param {flatbuffers.Long} value\n */\nflatbuffers.ByteBuffer.prototype.writeUint64 = function(offset, value) {\n    this.writeUint32(offset, value.low);\n    this.writeUint32(offset + 4, value.high);\n};\n\n/**\n * @param {number} offset\n * @param {number} value\n */\nflatbuffers.ByteBuffer.prototype.writeFloat32 = function(offset, value) {\n  flatbuffers.float32[0] = value;\n  this.writeInt32(offset, flatbuffers.int32[0]);\n};\n\n/**\n * @param {number} offset\n * @param {number} value\n */\nflatbuffers.ByteBuffer.prototype.writeFloat64 = function(offset, value) {\n  flatbuffers.float64[0] = value;\n  this.writeInt32(offset, flatbuffers.int32[flatbuffers.isLittleEndian ? 0 : 1]);\n  this.writeInt32(offset + 4, flatbuffers.int32[flatbuffers.isLittleEndian ? 1 : 0]);\n};\n\n/**\n * Return the file identifier.   Behavior is undefined for FlatBuffers whose\n * schema does not include a file_identifier (likely points at padding or the\n * start of a the root vtable).\n * @returns {string}\n */\nflatbuffers.ByteBuffer.prototype.getBufferIdentifier = function() {\n  if (this.bytes_.length < this.position_ + flatbuffers.SIZEOF_INT +\n      flatbuffers.FILE_IDENTIFIER_LENGTH) {\n    throw new Error(\n        'FlatBuffers: ByteBuffer is too short to contain an identifier.');\n  }\n  var result = \"\";\n  for (var i = 0; i < flatbuffers.FILE_IDENTIFIER_LENGTH; i++) {\n    result += String.fromCharCode(\n        this.readInt8(this.position_ + flatbuffers.SIZEOF_INT + i));\n  }\n  return result;\n};\n\n/**\n * Look up a field in the vtable, return an offset into the object, or 0 if the\n * field is not present.\n *\n * @param {number} bb_pos\n * @param {number} vtable_offset\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.__offset = function(bb_pos, vtable_offset) {\n  var vtable = bb_pos - this.readInt32(bb_pos);\n  return vtable_offset < this.readInt16(vtable) ? this.readInt16(vtable + vtable_offset) : 0;\n};\n\n/**\n * Initialize any Table-derived type to point to the union at the given offset.\n *\n * @param {flatbuffers.Table} t\n * @param {number} offset\n * @returns {flatbuffers.Table}\n */\nflatbuffers.ByteBuffer.prototype.__union = function(t, offset) {\n  t.bb_pos = offset + this.readInt32(offset);\n  t.bb = this;\n  return t;\n};\n\n/**\n * Create a JavaScript string from UTF-8 data stored inside the FlatBuffer.\n * This allocates a new string and converts to wide chars upon each access.\n *\n * To avoid the conversion to UTF-16, pass flatbuffers.Encoding.UTF8_BYTES as\n * the \"optionalEncoding\" argument. This is useful for avoiding conversion to\n * and from UTF-16 when the data will just be packaged back up in another\n * FlatBuffer later on.\n *\n * @param {number} offset\n * @param {flatbuffers.Encoding=} opt_encoding Defaults to UTF16_STRING\n * @returns {string|Uint8Array}\n */\nflatbuffers.ByteBuffer.prototype.__string = function(offset, opt_encoding) {\n  offset += this.readInt32(offset);\n\n  var length = this.readInt32(offset);\n  var result = '';\n  var i = 0;\n\n  offset += flatbuffers.SIZEOF_INT;\n\n  if (opt_encoding === flatbuffers.Encoding.UTF8_BYTES) {\n    return this.bytes_.subarray(offset, offset + length);\n  }\n\n  while (i < length) {\n    var codePoint;\n\n    // Decode UTF-8\n    var a = this.readUint8(offset + i++);\n    if (a < 0xC0) {\n      codePoint = a;\n    } else {\n      var b = this.readUint8(offset + i++);\n      if (a < 0xE0) {\n        codePoint =\n          ((a & 0x1F) << 6) |\n          (b & 0x3F);\n      } else {\n        var c = this.readUint8(offset + i++);\n        if (a < 0xF0) {\n          codePoint =\n            ((a & 0x0F) << 12) |\n            ((b & 0x3F) << 6) |\n            (c & 0x3F);\n        } else {\n          var d = this.readUint8(offset + i++);\n          codePoint =\n            ((a & 0x07) << 18) |\n            ((b & 0x3F) << 12) |\n            ((c & 0x3F) << 6) |\n            (d & 0x3F);\n        }\n      }\n    }\n\n    // Encode UTF-16\n    if (codePoint < 0x10000) {\n      result += String.fromCharCode(codePoint);\n    } else {\n      codePoint -= 0x10000;\n      result += String.fromCharCode(\n        (codePoint >> 10) + 0xD800,\n        (codePoint & ((1 << 10) - 1)) + 0xDC00);\n    }\n  }\n\n  return result;\n};\n\n/**\n * Retrieve the relative offset stored at \"offset\"\n * @param {number} offset\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.__indirect = function(offset) {\n  return offset + this.readInt32(offset);\n};\n\n/**\n * Get the start of data of a vector whose offset is stored at \"offset\" in this object.\n *\n * @param {number} offset\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.__vector = function(offset) {\n  return offset + this.readInt32(offset) + flatbuffers.SIZEOF_INT; // data starts after the length\n};\n\n/**\n * Get the length of a vector whose offset is stored at \"offset\" in this object.\n *\n * @param {number} offset\n * @returns {number}\n */\nflatbuffers.ByteBuffer.prototype.__vector_len = function(offset) {\n  return this.readInt32(offset + this.readInt32(offset));\n};\n\n/**\n * @param {string} ident\n * @returns {boolean}\n */\nflatbuffers.ByteBuffer.prototype.__has_identifier = function(ident) {\n  if (ident.length != flatbuffers.FILE_IDENTIFIER_LENGTH) {\n    throw new Error('FlatBuffers: file identifier must be length ' +\n                    flatbuffers.FILE_IDENTIFIER_LENGTH);\n  }\n  for (var i = 0; i < flatbuffers.FILE_IDENTIFIER_LENGTH; i++) {\n    if (ident.charCodeAt(i) != this.readInt8(this.position_ + flatbuffers.SIZEOF_INT + i)) {\n      return false;\n    }\n  }\n  return true;\n};\n\n/**\n * A helper function to avoid generated code depending on this file directly.\n *\n * @param {number} low\n * @param {number} high\n * @returns {flatbuffers.Long}\n */\nflatbuffers.ByteBuffer.prototype.createLong = function(low, high) {\n  return flatbuffers.Long.create(low, high);\n};\n\n// Exports for Node.js and RequireJS\nexport { flatbuffers };\n\n/// @endcond\n/// @}\n",
```

### Comparing `image_label-2.4.1/image_label/frontend/build/static/js/main.5f5eb4ba.chunk.js` & `image_label-2.4.2/image_label/frontend/build/static/js/main.209bf5ec.chunk.js`

 * *Files 14% similar despite different names*

#### js-beautify {}

```diff
@@ -1,84 +1,136 @@
 (this.webpackJsonpstreamlit_component_template = this.webpackJsonpstreamlit_component_template || []).push([
     [0], {
-        37: function(t, e, n) {},
-        44: function(t, e, n) {
+        38: function(t, e, n) {},
+        45: function(t, e, n) {
             "use strict";
             n.r(e);
-            var a = n(7),
+            var a = n(6),
                 o = n.n(a),
-                i = n(27),
+                i = n(28),
                 c = n.n(i),
-                r = n(5),
-                s = n(4),
-                d = n(6),
+                s = n(5),
+                r = n(4),
+                d = n(7),
                 l = n(0),
                 u = n(1),
                 h = n(2),
                 b = n(3),
+                v = n(11),
                 j = n(10),
-                g = n(25),
-                f = (n(37), n(31)),
-                m = n(13),
+                m = n(26),
+                f = (n(38), n(32)),
+                g = n(12),
                 p = function(t) {
                     var e = t.children,
                         n = t.geometry,
                         a = t.style;
-                    return Object(m.jsx)("div", {
+                    return Object(g.jsx)("div", {
                         style: Object(j.a)(Object(j.a)({}, a), {}, {
                             position: "absolute",
                             left: "".concat(n.x, "%"),
                             top: "".concat(n.y, "%"),
                             height: "".concat(n.height, "%"),
                             width: "".concat(n.width, "%")
                         }),
                         children: e
                     })
                 };
 
-            function v(t) {
+            function O(t) {
                 var e = t.annotation,
                     n = e.geometry;
-                return Object(m.jsx)("div", {
+                return Object(g.jsx)("div", {
                     style: {
                         background: "black",
                         color: "white",
                         padding: 10,
                         position: "absolute",
                         fontSize: 12,
                         left: "".concat(n.x, "%"),
                         top: "".concat(n.y + n.height, "%")
                     },
                     children: e.data && e.data.text
                 }, e.data.id)
             }
-            var O = function(t) {
+            var x = function(t) {
+                    var e = t.annotations,
+                        n = t.labels,
+                        o = Object(a.useState)({}),
+                        i = Object(v.a)(o, 2),
+                        c = i[0],
+                        s = i[1];
+                    return Object(a.useEffect)((function() {
+                        var t = {};
+                        n.forEach((function(e) {
+                            t[e] = 0
+                        })), e.forEach((function(e) {
+                            var n = e.data.text,
+                                a = t[n] ? t[n] + 1 : 1;
+                            t[n] = a
+                        })), s(t), console.log({
+                            tempData: t
+                        })
+                    }), [e]), Object(g.jsx)(g.Fragment, {
+                        children: Object(g.jsx)("div", {
+                            className: "dataHolder",
+                            children: Object.keys(c).map((function(t) {
+                                return Object(g.jsxs)("div", {
+                                    className: "dataItem",
+                                    children: [Object(g.jsx)("div", {
+                                        className: "dataItemLabel",
+                                        children: t
+                                    }), Object(g.jsx)("div", {
+                                        className: "dataItemValue",
+                                        children: c[t]
+                                    })]
+                                }, t)
+                            }))
+                        })
+                    })
+                },
+                y = function(t) {
                     Object(h.a)(n, t);
                     var e = Object(b.a)(n);
 
                     function n(t) {
                         var a, i;
-                        return Object(l.a)(this, n), (i = e.call(this, t)).canvasRef = o.a.createRef(), i.renderImageToCanvas = function() {
+                        return Object(l.a)(this, n), (i = e.call(this, t)).canvasRef = o.a.createRef(), i.moveDiv = function(t) {
+                            i.setState({
+                                coords: {
+                                    x: t.clientX,
+                                    y: t.clientY
+                                }
+                            })
+                        }, i.onMouseMove = function(t) {
+                            i.setState({
+                                showDiv: !0
+                            }), window.addEventListener("mousemove", i.moveDiv)
+                        }, i.onMouseOut = function(t) {
+                            i.setState({
+                                showDiv: !1
+                            }), window.removeEventListener("mousemove", i.moveDiv)
+                        }, i.renderImageToCanvas = function() {
                             return new Promise((function(t) {
                                 var e = i.canvasRef.current,
                                     n = e.getContext("2d"),
                                     a = new Image;
                                 a.onload = function() {
                                     e.width = a.width, e.height = a.height, n.drawImage(a, 0, 0, a.width, a.height), i.state.annotations.forEach((function(t) {
                                         var e = t.geometry,
                                             o = t.data,
                                             i = e.x,
                                             c = e.y,
-                                            r = e.width,
-                                            s = e.height,
+                                            s = e.width,
+                                            r = e.height,
                                             d = o.text,
                                             l = i / 100 * a.width,
                                             u = c / 100 * a.height,
-                                            h = r / 100 * a.width,
-                                            b = s / 100 * a.height;
+                                            h = s / 100 * a.width,
+                                            b = r / 100 * a.height;
                                         n.beginPath(), n.rect(l, u, h, b), n.lineWidth = 3, n.strokeStyle = "red", n.fillStyle = "red", n.stroke(), n.font = "40px Arial", n.fillText(d, l, u > 15 ? u - 5 : u + 15)
                                     })), t()
                                 }, a.src = "data:image/jpeg;base64," + i.props.image
                             }))
                         }, i.onChange = function(t) {
                             i.setState({
                                 annotation: t
@@ -102,155 +154,180 @@
                             })
                         }, i.deleteAnnotation = function(t) {
                             i.setState({
                                 annotations: i.state.annotations.filter((function(e) {
                                     return e.data.id !== t
                                 }))
                             })
-                        }, i.downloadImage = Object(d.a)(Object(s.a)().mark((function t() {
+                        }, i.downloadImage = Object(d.a)(Object(r.a)().mark((function t() {
                             var e, n, a;
-                            return Object(s.a)().wrap((function(t) {
+                            return Object(r.a)().wrap((function(t) {
                                 for (;;) switch (t.prev = t.next) {
                                     case 0:
                                         return t.next = 2, i.renderImageToCanvas();
                                     case 2:
                                         n = null === (e = i.canvasRef.current) || void 0 === e ? void 0 : e.toDataURL(), (a = document.createElement("a")).href = n, a.download = "image.png", a.click();
                                     case 7:
                                     case "end":
                                         return t.stop()
                                 }
                             }), t)
                         }))), i.state = {
-                            annotations: Object(r.a)(null === (a = i.props) || void 0 === a ? void 0 : a.detectedAnotations),
-                            annotation: {}
+                            annotations: Object(s.a)(null === (a = i.props) || void 0 === a ? void 0 : a.detectedAnotations),
+                            annotation: {},
+                            showDiv: !1,
+                            coords: {
+                                x: 0,
+                                y: 0
+                            }
                         }, i
                     }
                     return Object(u.a)(n, [{
+                        key: "componentWillUnmount",
+                        value: function() {
+                            window.removeEventListener("mousemove", this.moveDiv)
+                        }
+                    }, {
                         key: "render",
                         value: function() {
                             var t = this,
                                 e = "data:image/jpeg;base64," + this.props.image;
-                            return Object(m.jsxs)("div", {
-                                children: [Object(m.jsx)(f.a, {
-                                    src: e,
-                                    alt: "pcb",
-                                    annotations: this.state.annotations,
-                                    type: this.state.type,
-                                    value: this.state.annotation,
-                                    onChange: this.onChange,
-                                    onSubmit: this.onSubmit,
-                                    renderEditor: function(e) {
-                                        return function(t, e) {
-                                            var n = t.annotation.geometry;
-                                            return n ? Object(m.jsxs)("div", {
-                                                className: "holder",
-                                                style: {
-                                                    background: "rgba(0, 0, 0, 0.15)",
-                                                    left: "".concat(n.x > 80 ? 75 : n.x, "%"),
-                                                    top: "".concat(n.y > 85 ? 85 : n.y, "%")
-                                                },
-                                                children: [Object(m.jsxs)("select", {
-                                                    className: "selectItem",
-                                                    onChange: function(e) {
-                                                        t.onChange(Object(j.a)(Object(j.a)({}, t.annotation), {}, {
-                                                            data: Object(j.a)(Object(j.a)({}, t.annotation.data), {}, {
-                                                                text: e.target.value
-                                                            })
-                                                        }))
+                            return Object(g.jsxs)(g.Fragment, {
+                                children: [Object(g.jsxs)("div", {
+                                    className: "hoverDiv",
+                                    onMouseMove: this.onMouseMove,
+                                    onMouseOut: this.onMouseOut,
+                                    children: [Object(g.jsx)(f.a, {
+                                        src: e,
+                                        alt: "pcb",
+                                        annotations: this.state.annotations,
+                                        type: this.state.type,
+                                        value: this.state.annotation,
+                                        onChange: this.onChange,
+                                        onSubmit: this.onSubmit,
+                                        renderEditor: function(e) {
+                                            return function(t, e) {
+                                                var n = t.annotation.geometry;
+                                                return n ? Object(g.jsxs)("div", {
+                                                    className: "holder",
+                                                    style: {
+                                                        background: "rgba(0, 0, 0, 0.15)",
+                                                        left: "".concat(n.x > 80 ? 75 : n.x, "%"),
+                                                        top: "".concat(n.y > 85 ? 85 : n.y, "%")
                                                     },
-                                                    children: [Object(m.jsx)("option", {
-                                                        value: "",
-                                                        children: "Select..."
-                                                    }), e.map((function(t) {
-                                                        return Object(m.jsx)("option", {
-                                                            value: t,
-                                                            children: t
-                                                        }, t)
-                                                    }))]
-                                                }), Object(m.jsx)("button", {
-                                                    className: "addLabelButton",
-                                                    onClick: t.onSubmit,
-                                                    children: "Add"
-                                                })]
-                                            }) : null
-                                        }(e, t.props.labels)
-                                    },
-                                    renderContent: v,
-                                    renderHighlight: function(e) {
-                                        return function(t) {
-                                            var e = t.annotation,
-                                                n = t.active,
-                                                a = t.deleteAnnotation,
-                                                o = e.geometry;
-                                            return o ? Object(m.jsx)(p, {
-                                                geometry: o,
-                                                style: {
-                                                    border: "solid 1px ".concat(n ? "#3e8e41" : w())
-                                                },
-                                                children: n && Object(m.jsx)("button", {
-                                                    className: "deleteAnnotationButton",
-                                                    onClick: function() {
-                                                        console.log("delete"), a(e.data.id)
+                                                    children: [Object(g.jsxs)("select", {
+                                                        className: "selectItem",
+                                                        onChange: function(e) {
+                                                            t.onChange(Object(j.a)(Object(j.a)({}, t.annotation), {}, {
+                                                                data: Object(j.a)(Object(j.a)({}, t.annotation.data), {}, {
+                                                                    text: e.target.value
+                                                                })
+                                                            }))
+                                                        },
+                                                        children: [Object(g.jsx)("option", {
+                                                            value: "",
+                                                            children: "Select..."
+                                                        }), e.map((function(t) {
+                                                            return Object(g.jsx)("option", {
+                                                                value: t,
+                                                                children: t
+                                                            }, t)
+                                                        }))]
+                                                    }), Object(g.jsx)("button", {
+                                                        className: "addLabelButton",
+                                                        onClick: t.onSubmit,
+                                                        children: "Add"
+                                                    })]
+                                                }) : null
+                                            }(e, t.props.labels)
+                                        },
+                                        renderContent: O,
+                                        renderHighlight: function(e) {
+                                            return function(t) {
+                                                var e = t.annotation,
+                                                    n = t.active,
+                                                    a = t.deleteAnnotation,
+                                                    o = e.geometry;
+                                                return o ? Object(g.jsx)(p, {
+                                                    geometry: o,
+                                                    style: {
+                                                        border: "solid 1px ".concat(n ? "#3e8e41" : k())
                                                     },
-                                                    children: "X"
-                                                })
-                                            }, e.data.id) : null
-                                        }({
-                                            annotation: e.annotation,
-                                            active: e.active,
-                                            deleteAnnotation: t.deleteAnnotation
+                                                    children: n && Object(g.jsx)("button", {
+                                                        className: "deleteAnnotationButton",
+                                                        onClick: function() {
+                                                            console.log("delete"), a(e.data.id)
+                                                        },
+                                                        children: "X"
+                                                    })
+                                                }, e.data.id) : null
+                                            }({
+                                                annotation: e.annotation,
+                                                active: e.active,
+                                                deleteAnnotation: t.deleteAnnotation
+                                            })
+                                        }
+                                    }), this.state.showDiv && Object(g.jsx)("div", {
+                                        className: "hover-info",
+                                        style: {
+                                            top: "".concat(this.state.coords.y + 30, "px"),
+                                            left: "".concat(this.state.coords.x + 30, "px")
+                                        },
+                                        children: Object(g.jsx)(x, {
+                                            labels: this.props.labels,
+                                            annotations: this.state.annotations
                                         })
-                                    }
-                                }), Object(m.jsx)("button", {
+                                    })]
+                                }), Object(g.jsx)("button", {
                                     className: "downloadButton",
                                     onClick: this.downloadImage,
                                     children: "Download"
-                                }), Object(m.jsx)("canvas", {
+                                }), Object(g.jsx)("canvas", {
                                     ref: this.canvasRef,
                                     style: {
                                         display: "none"
                                     }
                                 })]
                             })
                         }
                     }]), n
                 }(a.Component),
-                x = function(t) {
+                w = function(t) {
                     Object(h.a)(n, t);
                     var e = Object(b.a)(n);
 
                     function n() {
                         return Object(l.a)(this, n), e.apply(this, arguments)
                     }
                     return Object(u.a)(n, [{
                         key: "render",
                         value: function() {
                             var t = this.props.args,
                                 e = t.image,
                                 n = t.labels,
                                 a = t.detectedAnotations;
-                            return Object(m.jsx)(O, {
+                            return Object(g.jsx)(y, {
                                 image: e,
                                 labels: n,
                                 detectedAnotations: a
                             })
                         }
                     }]), n
-                }(g.a),
-                y = Object(g.b)(x);
+                }(m.a),
+                S = Object(m.b)(w);
 
-            function w() {
+            function k() {
                 for (var t = "#", e = 0; e < 6; e++) {
                     t += Math.floor(16 * Math.random()).toString(16)
                 }
                 return t
             }
-            c.a.render(Object(m.jsx)(o.a.StrictMode, {
-                children: Object(m.jsx)(y, {})
+            c.a.render(Object(g.jsx)(o.a.StrictMode, {
+                children: Object(g.jsx)(S, {})
             }), document.getElementById("root"))
         }
     },
     [
-        [44, 1, 2]
+        [45, 1, 2]
     ]
 ]);
-//# sourceMappingURL=main.5f5eb4ba.chunk.js.map
+//# sourceMappingURL=main.209bf5ec.chunk.js.map
```

### Comparing `image_label-2.4.1/image_label/frontend/build/static/js/main.5f5eb4ba.chunk.js.map` & `image_label-2.4.2/image_label/frontend/build/static/js/main.209bf5ec.chunk.js.map`

 * *Files 20% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.7892857142857144%*

 * *Differences: {"'file'": "'static/js/main.209bf5ec.chunk.js'",*

 * * "'mappings'": "'+SAmHMA,EAAM,SAAHC,GAAA,IAAMC,EAAQD,EAARC,SAAUC,EAAQF,EAARE,SAAUC,EAAKH,EAALG,MAAK,OACtCC,cAAA,OACED,MAAKE,wBAAA,GACAF,GAAK,IACRG,SAAU,WACVC,KAAK,GAADC,OAAKN,EAASO,EAAC,KACnBC,IAAI,GAADF,OAAKN,EAASS,EAAC,KAClBC,OAAO,GAADJ,OAAKN,EAASU,OAAM,KAC1BC,MAAM,GAADL,OAAKN,EAASW,MAAK,OACxBZ,SAEDA,GACG,EA8BR,SAASa,EAAaC,GAAkB,IAAfC,EAAUD,EAAVC,WACfd,EAAac,EAAbd,SACR,OACEE,cAAA,OAEED,MAAO,CACLc,WAAY,QACZC,MAAO,QACPC,QAAS,GACTb,SAAU,WACVc,SAAU,GACVb,KAAK,G […]*

```diff
@@ -1,10 +1,10 @@
 {
-    "file": "static/js/main.5f5eb4ba.chunk.js",
-    "mappings": "uSAmHMA,EAAM,SAAHC,GAAA,IAAMC,EAAQD,EAARC,SAAUC,EAAQF,EAARE,SAAUC,EAAKH,EAALG,MAAK,OACtCC,cAAA,OACED,MAAKE,wBAAA,GACAF,GAAK,IACRG,SAAU,WACVC,KAAK,GAADC,OAAKN,EAASO,EAAC,KACnBC,IAAI,GAADF,OAAKN,EAASS,EAAC,KAClBC,OAAO,GAADJ,OAAKN,EAASU,OAAM,KAC1BC,MAAM,GAADL,OAAKN,EAASW,MAAK,OACxBZ,SAEDA,GACG,EA8BR,SAASa,EAAaC,GAAkB,IAAfC,EAAUD,EAAVC,WACfd,EAAac,EAAbd,SACR,OACEE,cAAA,OAEED,MAAO,CACLc,WAAY,QACZC,MAAO,QACPC,QAAS,GACTb,SAAU,WACVc,SAAU,GACVb,KAAK,GAADC,OAAKN,EAASO,EAAC,KACnBC,IAAI,GAADF,OAAKN,EAASS,EAAIT,EAASU,OAAM,MACpCX,SAEDe,EAAWK,MAAQL,EAAWK,KAAKC,MAX/BN,EAAWK,KAAKE,GAc3B,CAqCC,IAEKC,EAAW,SAAAC,GAAAC,YAAAF,EAAAC,GAAA,IAAAE,EAAAC,YAAAJ,GAMf,SAAAA,EAAYK,GAAQ,IAADC,EAAAC,EAKhB,OALgBC,YAAA,KAAAR,IACjBO,EAAAJ,EAAAM,KAAA,KAAMJ,IAMRK,UAAYC,IAAMC,YAAWL,EAE7BM,oBAAsB,WACpB,OAAO,IAAIC,SAAQ,SAACC,GAClB,IAAMC,EAAST,EAAKG,UAAUO,QACxBC,EAAUF,EAAOG,WAAW,MAC5BC,EAAM,IAAIC,MAEhBD,EAAIE,OAAS,WACXN,EAAO3B,MAAQ+B,EAAI/B,MACnB2B,EAAO5B,OAASgC,EAAIhC,OACpB8B,EAAQK,UAAUH,EAAK,EAAG,EAAGA,EAAI/B,MAAO+B,EAAIhC,QAE5CmB,EAAKiB,MAAMC,YAAYC,SAAQ,SAAClC,GAC9B,IAAQd,EAAmBc,EAAnBd,SAAUmB,EAASL,EAATK,KACVZ,EAAwBP,EAAxBO,EAAGE,EAAqBT,EAArBS,EAAGE,EAAkBX,EAAlBW,MAAOD,EAAWV,EAAXU,OACbU,EAASD,EAATC,KAED6B,EACJ1C,EAAI,IAAOmC,EAAI/B,MADPuC,EAERzC,EAAI,IAAOiC,EAAIhC,OAFHyC,EAGZxC,EAAQ,IAAO+B,EAAI/B,MAHCyC,EAIpB1C,EAAS,IAAOgC,EAAIhC,OAGvB8B,EAAQa,YACRb,EAAQc,KAAKL,EAAIC,EAAIC,EAAQC,GAC7BZ,EAAQe,UAAY,EACpBf,EAAQgB,YAAc,MACtBhB,EAAQiB,UAAY,MACpBjB,EAAQkB,SACRlB,EAAQmB,KAAO,aACfnB,EAAQoB,SAASxC,EAAM6B,EAAIC,EAAK,GAAKA,EAAK,EAAIA,EAAK,GACrD,IAGAb,GACF,EAEAK,EAAImB,IAAM,0BAA4BhC,EAAKF,MAAMmC,KACnD,GACF,EAACjC,EAEDkC,SAAW,SAACjD,GACVe,EAAKmC,SAAS,CAAElD,cAClB,EAACe,EAEDoC,SAAW,SAACnD,GACV,IAAQd,EAAmBc,EAAnBd,SAAUmB,EAASL,EAATK,KAElBU,EAAKmC,SAAS,CACZlD,WAAY,CAAC,EACbiC,YAAalB,EAAKiB,MAAMC,YAAYzC,OAAO,CACzCN,WACAmB,KAAIhB,wBAAA,GACCgB,GAAI,IACPE,GAAI6C,KAAKC,cAIjB,EAACtC,EACDuC,aAAe,SAACC,GACdxC,EAAKmC,SAAS,CACZlD,WAAY,CAAC,EACbwD,KAAMD,EAAEE,cAAcC,WAE1B,EAAC3C,EACD4C,iBAAmB,SAACpD,GAClBQ,EAAKmC,SAAS,CACZjB,YAAalB,EAAKiB,MAAMC,YAAY2B,QAAO,SAAC5D,GAC1C,OAAOA,EAAWK,KAAKE,KAAOA,CAChC,KAEJ,EAACQ,EACD8C,cAAaC,YAAAC,cAAAC,MAAG,SAAAC,IAAA,IAAAC,EAAAC,EAAAC,EAAA,OAAAL,cAAAM,MAAA,SAAAC,GAAA,cAAAA,EAAAC,KAAAD,EAAAE,MAAA,cAAAF,EAAAE,KAAA,EAERzD,EAAKM,sBAAqB,OAG1B8C,EAAgC,QAAzBD,EAAGnD,EAAKG,UAAUO,eAAO,IAAAyC,OAAA,EAAtBA,EAAwBO,aAGlCL,EAAOM,SAASC,cAAc,MAC/BC,KAAOT,EAGZC,EAAKS,SAAW,YAGhBT,EAAKU,QAAO,wBAAAR,EAAAS,OAAA,GAAAd,EAAA,KA9FZlD,EAAKiB,MAAQ,CACXC,YAAW+C,YAAgB,QAAhBlE,EAAMC,EAAKF,aAAK,IAAAC,OAAA,EAAVA,EAAYmE,oBAC7BjF,WAAY,CAAC,GACde,CACH,CA6HC,OA7HAmE,YAAA1E,EAAA,EAAA2E,IAAA,SAAAC,MA4FD,WAAU,IAADC,EAAA,KACDC,EAAW,0BAA4BC,KAAK1E,MAAMmC,MAExD,OACEwC,eAAA,OAAAvG,SAAA,CACEG,cAACqG,IAAU,CACT1C,IAAKuC,EACLI,IAAI,MACJzD,YAAasD,KAAKvD,MAAMC,YACxBuB,KAAM+B,KAAKvD,MAAMwB,KACjB4B,MAAOG,KAAKvD,MAAMhC,WAClBiD,SAAUsC,KAAKtC,SACfE,SAAUoC,KAAKpC,SACfwC,aAAc,SAAC9E,GAEb,OA7JZ,SAAsBA,EAAO+E,GAC3B,IAAQ1G,EAAa2B,EAAMb,WAAnBd,SACR,OAAKA,EAEHsG,eAAA,OACEK,UAAU,SACV1G,MAAO,CACLc,WAAY,sBACZV,KAAK,GAADC,OAAKN,EAASO,EAAI,GAAK,GAAKP,EAASO,EAAC,KAC1CC,IAAI,GAADF,OAAKN,EAASS,EAAI,GAAK,GAAKT,EAASS,EAAC,MACzCV,SAAA,CAEFuG,eAAA,UACEK,UAAU,aACV5C,SAAU,SAACM,GACT1C,EAAMoC,SAAQ5D,wBAAC,CAAC,EACXwB,EAAMb,YAAU,IACnBK,KAAIhB,wBAAA,GACCwB,EAAMb,WAAWK,MAAI,IACxBC,KAAMiD,EAAEuC,OAAOV,UAGrB,EAAEnG,SAAA,CAEFG,cAAA,UAAQgG,MAAM,GAAEnG,SAAC,cAChB2G,EAAOG,KAAI,SAACC,GAAK,OAChB5G,cAAA,UAAoBgG,MAAOY,EAAM/G,SAC9B+G,GADUA,EAEJ,OAGb5G,cAAA,UAAQyG,UAAU,iBAAiBI,QAASpF,EAAMsC,SAASlE,SAAC,WA7B1C,IAkCxB,CAyHmB0G,CAAa9E,EADLwE,EAAKxE,MAAM+E,OAE5B,EACA9F,cAAeA,EACfoG,gBAAiB,SAAAC,GACf,OA/MZ,SAAwBC,GAA4C,IAAzCpG,EAAUoG,EAAVpG,WAAYqG,EAAMD,EAANC,OAAQ1C,EAAgByC,EAAhBzC,iBACrCzE,EAAac,EAAbd,SACR,OAAKA,EAEHE,cAACL,EAAG,CAEFG,SAAUA,EACVC,MAAO,CACLmH,OAAO,aAAD9G,OAAe6G,EAAS,UAAYE,MAE1CtH,SAEDoH,GACCjH,cAAA,UACEyG,UAAU,yBACVI,QAAS,WACPO,QAAQC,IAAI,UACZ9C,EAAiB3D,EAAWK,KAAKE,GACnC,EAAEtB,SACH,OAdEe,EAAWK,KAAKE,IAHH,IAuBxB,CAsLmB2F,CAAgB,CACrBlG,WAF0BmG,EAAVnG,WAGhBqG,OAHkCF,EAANE,OAI5B1C,iBAAkB0B,EAAK1B,kBAE3B,IAEFvE,cAAA,UAAQyG,UAAU,iBAAiBI,QAASV,KAAK1B,cAAc5E,SAAC,aAIhEG,cAAA,UAAQsH,IAAKnB,KAAKrE,UAAW/B,MAAO,CAAEwH,QAAS,YAGrD,KAACnG,CAAA,CAzIc,CAASoG,aA4IpBC,EAAG,SAAAC,GAAApG,YAAAmG,EAAAC,GAAA,IAAAC,EAAAnG,YAAAiG,GAAA,SAAAA,IAAA,OAAA7F,YAAA,KAAA6F,GAAAE,EAAAC,MAAA,KAAAC,UAAA,CAWN,OAXM/B,YAAA2B,EAAA,EAAA1B,IAAA,SAAAC,MACP,WACE,IAAA8B,EAA8C3B,KAAK1E,MAAMsG,KAAjDnE,EAAKkE,EAALlE,MAAO4C,EAAMsB,EAANtB,OAAQX,EAAkBiC,EAAlBjC,mBAEvB,OACE7F,cAACoB,EAAW,CACVwC,MAAOA,EACP4C,OAAQA,EACRX,mBAAoBA,GAG1B,KAAC4B,CAAA,CAXM,CAASO,KAcHC,cAAwBR,GAEvC,SAASN,IAIP,IAHA,IAAIe,EAAU,IAGLC,EAAI,EAAGA,EAAI,EAAGA,IAAK,CAK1BD,GAHiBlE,KAAKoE,MAAsB,GAAhBpE,KAAKC,UAAeoE,SAAS,GAI3D,CAEA,OAAOH,CACT,CC3XAI,IAASC,OACPvI,cAAC+B,IAAMyG,WAAU,CAAA3I,SACfG,cAACoB,EAAW,MAEdkE,SAASmD,eAAe,Q",
+    "file": "static/js/main.209bf5ec.chunk.js",
+    "mappings": "+SAmHMA,EAAM,SAAHC,GAAA,IAAMC,EAAQD,EAARC,SAAUC,EAAQF,EAARE,SAAUC,EAAKH,EAALG,MAAK,OACtCC,cAAA,OACED,MAAKE,wBAAA,GACAF,GAAK,IACRG,SAAU,WACVC,KAAK,GAADC,OAAKN,EAASO,EAAC,KACnBC,IAAI,GAADF,OAAKN,EAASS,EAAC,KAClBC,OAAO,GAADJ,OAAKN,EAASU,OAAM,KAC1BC,MAAM,GAADL,OAAKN,EAASW,MAAK,OACxBZ,SAEDA,GACG,EA8BR,SAASa,EAAaC,GAAkB,IAAfC,EAAUD,EAAVC,WACfd,EAAac,EAAbd,SACR,OACEE,cAAA,OAEED,MAAO,CACLc,WAAY,QACZC,MAAO,QACPC,QAAS,GACTb,SAAU,WACVc,SAAU,GACVb,KAAK,GAADC,OAAKN,EAASO,EAAC,KACnBC,IAAI,GAADF,OAAKN,EAASS,EAAIT,EAASU,OAAM,MACpCX,SAEDe,EAAWK,MAAQL,EAAWK,KAAKC,MAX/BN,EAAWK,KAAKE,GAc3B,CAuCA,IAAMC,EAAU,SAAHC,GAAiC,IAA3BC,EAAWD,EAAXC,YAAaC,EAAMF,EAANE,OAE9BC,EAAwBC,mBAAS,CAAC,GAAEC,EAAAC,YAAAH,EAAA,GAA7BP,EAAIS,EAAA,GAAEE,EAAOF,EAAA,GAgBpB,OAdAG,qBAAU,WACR,IAAMC,EAAW,CAAC,EAClBP,EAAOQ,SAAQ,SAACC,GACdF,EAASE,GAAS,CACpB,IACAV,EAAYS,SAAQ,SAACnB,GACnB,IACQM,EADSN,EAATK,KACAC,KACFe,EAAWH,EAASZ,GAAQY,EAASZ,GAAQ,EAAI,EACvDY,EAASZ,GAAQe,CACnB,IACAL,EAAQE,GACRI,QAAQC,IAAI,CAAEL,YAChB,GAAG,CAACR,IAEFtB,cAAAoC,WAAA,CAAAvC,SACEG,cAAA,OAAKqC,UAAU,aAAYxC,SACxByC,OAAOC,KAAKtB,GAAMuB,KAAI,SAACC,GACtB,OACEC,eAAA,OAAKL,UAAU,WAAUxC,SAAA,CACvBG,cAAA,OAAKqC,UAAU,gBAAexC,SAAE4C,IAChCzC,cAAA,OAAKqC,UAAU,gBAAexC,SAAEoB,EAAKwB,OAFRA,EAKnC,OAIR,EAEME,EAAW,SAAAC,GAAAC,YAAAF,EAAAC,GAAA,IAAAE,EAAAC,YAAAJ,GAMf,SAAAA,EAAYK,GAAQ,IAADC,EAAAC,EAOhB,OAPgBC,YAAA,KAAAR,IACjBO,EAAAJ,EAAAM,KAAA,KAAMJ,IAQRK,UAAYC,IAAMC,YAAWL,EAC7BM,QAAU,SAACC,GACTP,EAAKQ,SAAS,CAAEC,OAAQ,CAAEtD,EAAGoD,EAAEG,QAASrD,EAAGkD,EAAEI,UAC/C,EAACX,EAEDY,YAAc,SAACL,GACbP,EAAKQ,SAAS,CAAEK,SAAS,IACzBC,OAAOC,iBAAiB,YAAaf,EAAKM,QAC5C,EAACN,EAEDgB,WAAa,SAACT,GACZP,EAAKQ,SAAS,CAAEK,SAAS,IACzBC,OAAOG,oBAAoB,YAAajB,EAAKM,QAC/C,EAACN,EAMDkB,oBAAsB,WACpB,OAAO,IAAIC,SAAQ,SAACC,GAClB,IAAMC,EAASrB,EAAKG,UAAUmB,QACxBC,EAAUF,EAAOG,WAAW,MAC5BC,EAAM,IAAIC,MAEhBD,EAAIE,OAAS,WACXN,EAAO9D,MAAQkE,EAAIlE,MACnB8D,EAAO/D,OAASmE,EAAInE,OACpBiE,EAAQK,UAAUH,EAAK,EAAG,EAAGA,EAAIlE,MAAOkE,EAAInE,QAE5C0C,EAAK6B,MAAMzD,YAAYS,SAAQ,SAACnB,GAC9B,IAAQd,EAAmBc,EAAnBd,SAAUmB,EAASL,EAATK,KACVZ,EAAwBP,EAAxBO,EAAGE,EAAqBT,EAArBS,EAAGE,EAAkBX,EAAlBW,MAAOD,EAAWV,EAAXU,OACbU,EAASD,EAATC,KAED8D,EACJ3E,EAAI,IAAOsE,EAAIlE,MADPwE,EAER1E,EAAI,IAAOoE,EAAInE,OAFH0E,EAGZzE,EAAQ,IAAOkE,EAAIlE,MAHC0E,EAIpB3E,EAAS,IAAOmE,EAAInE,OAGvBiE,EAAQW,YACRX,EAAQY,KAAKL,EAAIC,EAAIC,EAAQC,GAC7BV,EAAQa,UAAY,EACpBb,EAAQc,YAAc,MACtBd,EAAQe,UAAY,MACpBf,EAAQgB,SACRhB,EAAQiB,KAAO,aACfjB,EAAQkB,SAASzE,EAAM8D,EAAIC,EAAK,GAAKA,EAAK,EAAIA,EAAK,GACrD,IAGAX,GACF,EAEAK,EAAIiB,IAAM,0BAA4B1C,EAAKF,MAAM6C,KACnD,GACF,EAAC3C,EAED4C,SAAW,SAAClF,GACVsC,EAAKQ,SAAS,CAAE9C,cAClB,EAACsC,EAED6C,SAAW,SAACnF,GACV,IAAQd,EAAmBc,EAAnBd,SAAUmB,EAASL,EAATK,KAElBiC,EAAKQ,SAAS,CACZ9C,WAAY,CAAC,EACbU,YAAa4B,EAAK6B,MAAMzD,YAAYlB,OAAO,CACzCN,WACAmB,KAAIhB,wBAAA,GACCgB,GAAI,IACPE,GAAI6E,KAAKC,cAIjB,EAAC/C,EACDgD,aAAe,SAACzC,GACdP,EAAKQ,SAAS,CACZ9C,WAAY,CAAC,EACbuF,KAAM1C,EAAE2C,cAAcC,WAE1B,EAACnD,EACDoD,iBAAmB,SAACnF,GAClB+B,EAAKQ,SAAS,CACZpC,YAAa4B,EAAK6B,MAAMzD,YAAYiF,QAAO,SAAC3F,GAC1C,OAAOA,EAAWK,KAAKE,KAAOA,CAChC,KAEJ,EAAC+B,EAEDsD,cAAaC,YAAAC,cAAAC,MAAG,SAAAC,IAAA,IAAAC,EAAAC,EAAAC,EAAA,OAAAL,cAAAM,MAAA,SAAAC,GAAA,cAAAA,EAAAC,KAAAD,EAAAE,MAAA,cAAAF,EAAAE,KAAA,EAERjE,EAAKkB,sBAAqB,OAG1B0C,EAAgC,QAAzBD,EAAG3D,EAAKG,UAAUmB,eAAO,IAAAqC,OAAA,EAAtBA,EAAwBO,aAGlCL,EAAOM,SAASC,cAAc,MAC/BC,KAAOT,EAGZC,EAAKS,SAAW,YAGhBT,EAAKU,QAAO,wBAAAR,EAAAS,OAAA,GAAAd,EAAA,KAlHZ1D,EAAK6B,MAAQ,CACXzD,YAAWqG,YAAgB,QAAhB1E,EAAMC,EAAKF,aAAK,IAAAC,OAAA,EAAVA,EAAY2E,oBAC7BhH,WAAY,CAAC,EACbmD,SAAS,EACTJ,OAAQ,CAAEtD,EAAG,EAAGE,EAAG,IACpB2C,CACH,CAuKC,OAvKA2E,YAAAlF,EAAA,EAAAF,IAAA,uBAAAqF,MAgBD,WACE9D,OAAOG,oBAAoB,YAAa4D,KAAKvE,QAC/C,GAAC,CAAAf,IAAA,SAAAqF,MA4FD,WAAU,IAADE,EAAA,KACDC,EAAW,0BAA4BF,KAAK/E,MAAM6C,MAExD,OACEnD,eAAAN,WAAA,CAAAvC,SAAA,CACE6C,eAAA,OACEL,UAAU,WACVyB,YAAaiE,KAAKjE,YAClBI,WAAY6D,KAAK7D,WAAWrE,SAAA,CAE5BG,cAACkI,IAAU,CACTtC,IAAKqC,EACLE,IAAI,MACJ7G,YAAayG,KAAKhD,MAAMzD,YACxB6E,KAAM4B,KAAKhD,MAAMoB,KACjB2B,MAAOC,KAAKhD,MAAMnE,WAClBkF,SAAUiC,KAAKjC,SACfC,SAAUgC,KAAKhC,SACfqC,aAAc,SAACpF,GAEb,OAxNd,SAAsBA,EAAOzB,GAC3B,IAAQzB,EAAakD,EAAMpC,WAAnBd,SACR,OAAKA,EAEH4C,eAAA,OACEL,UAAU,SACVtC,MAAO,CACLc,WAAY,sBACZV,KAAK,GAADC,OAAKN,EAASO,EAAI,GAAK,GAAKP,EAASO,EAAC,KAC1CC,IAAI,GAADF,OAAKN,EAASS,EAAI,GAAK,GAAKT,EAASS,EAAC,MACzCV,SAAA,CAEF6C,eAAA,UACEL,UAAU,aACVyD,SAAU,SAACrC,GACTT,EAAM8C,SAAQ7F,wBAAC,CAAC,EACX+C,EAAMpC,YAAU,IACnBK,KAAIhB,wBAAA,GACC+C,EAAMpC,WAAWK,MAAI,IACxBC,KAAMuC,EAAE4E,OAAOP,UAGrB,EAAEjI,SAAA,CAEFG,cAAA,UAAQ8H,MAAM,GAAEjI,SAAC,cAChB0B,EAAOiB,KAAI,SAACR,GAAK,OAChBhC,cAAA,UAAoB8H,MAAO9F,EAAMnC,SAC9BmC,GADUA,EAEJ,OAGbhC,cAAA,UAAQqC,UAAU,iBAAiBiG,QAAStF,EAAM+C,SAASlG,SAAC,WA7B1C,IAkCxB,CAoLqBuI,CAAapF,EADLgF,EAAKhF,MAAMzB,OAE5B,EACAb,cAAeA,EACf6H,gBAAiB,SAAAC,GACf,OA1Qd,SAAwBC,GAA4C,IAAzC7H,EAAU6H,EAAV7H,WAAY8H,EAAMD,EAANC,OAAQpC,EAAgBmC,EAAhBnC,iBACrCxG,EAAac,EAAbd,SACR,OAAKA,EAEHE,cAACL,EAAG,CAEFG,SAAUA,EACVC,MAAO,CACL4I,OAAO,aAADvI,OAAesI,EAAS,UAAYE,MAE1C/I,SAED6I,GACC1I,cAAA,UACEqC,UAAU,yBACViG,QAAS,WACPpG,QAAQC,IAAI,UACZmE,EAAiB1F,EAAWK,KAAKE,GACnC,EAAEtB,SACH,OAdEe,EAAWK,KAAKE,IAHH,IAuBxB,CAiPqBoH,CAAgB,CACrB3H,WAF0B4H,EAAV5H,WAGhB8H,OAHkCF,EAANE,OAI5BpC,iBAAkB0B,EAAK1B,kBAE3B,IAEDyB,KAAKhD,MAAMhB,SACV/D,cAAA,OACEqC,UAAU,aACVtC,MAAO,CACLO,IAAI,GAADF,OAAK2H,KAAKhD,MAAMpB,OAAOpD,EAAI,GAAE,MAChCJ,KAAK,GAADC,OAAK2H,KAAKhD,MAAMpB,OAAOtD,EAAI,GAAE,OAKnCR,SAEAG,cAACoB,EAAO,CACNG,OAAQwG,KAAK/E,MAAMzB,OACnBD,YAAayG,KAAKhD,MAAMzD,mBAKhCtB,cAAA,UAAQqC,UAAU,iBAAiBiG,QAASP,KAAKvB,cAAc3G,SAAC,aAIhEG,cAAA,UAAQ6I,IAAKd,KAAK1E,UAAWtD,MAAO,CAAE+I,QAAS,YAGrD,KAACnG,CAAA,CArLc,CAASoG,aAwLpBC,EAAG,SAAAC,GAAApG,YAAAmG,EAAAC,GAAA,IAAAC,EAAAnG,YAAAiG,GAAA,SAAAA,IAAA,OAAA7F,YAAA,KAAA6F,GAAAE,EAAAC,MAAA,KAAAC,UAAA,CAWN,OAXMvB,YAAAmB,EAAA,EAAAvG,IAAA,SAAAqF,MACP,WACE,IAAAuB,EAA8CtB,KAAK/E,MAAMsG,KAAjDzD,EAAKwD,EAALxD,MAAOtE,EAAM8H,EAAN9H,OAAQqG,EAAkByB,EAAlBzB,mBAEvB,OACE5H,cAAC2C,EAAW,CACVkD,MAAOA,EACPtE,OAAQA,EACRqG,mBAAoBA,GAG1B,KAACoB,CAAA,CAXM,CAASO,KAcHC,cAAwBR,GAEvC,SAASJ,IAIP,IAHA,IAAIa,EAAU,IAGLC,EAAI,EAAGA,EAAI,EAAGA,IAAK,CAK1BD,GAHiBzD,KAAK2D,MAAsB,GAAhB3D,KAAKC,UAAe2D,SAAS,GAI3D,CAEA,OAAOH,CACT,CCzcAI,IAASC,OACP9J,cAACsD,IAAMyG,WAAU,CAAAlK,SACfG,cAAC2C,EAAW,MAEd0E,SAAS2C,eAAe,Q",
     "names": [
         "Box",
         "_ref",
         "children",
         "geometry",
         "style",
         "_jsx",
@@ -23,41 +23,74 @@
         "background",
         "color",
         "padding",
         "fontSize",
         "data",
         "text",
         "id",
+        "DataDiv",
+        "_ref4",
+        "annotations",
+        "labels",
+        "_useState",
+        "useState",
+        "_useState2",
+        "_slicedToArray",
+        "setData",
+        "useEffect",
+        "tempData",
+        "forEach",
+        "label",
+        "frquency",
+        "console",
+        "log",
+        "_Fragment",
+        "className",
+        "Object",
+        "keys",
+        "map",
+        "key",
+        "_jsxs",
         "MyComponent",
         "_Component",
         "_inherits",
         "_super",
         "_createSuper",
         "props",
         "_this$props",
         "_this",
         "_classCallCheck",
         "call",
         "canvasRef",
         "React",
         "createRef",
+        "moveDiv",
+        "e",
+        "setState",
+        "coords",
+        "clientX",
+        "clientY",
+        "onMouseMove",
+        "showDiv",
+        "window",
+        "addEventListener",
+        "onMouseOut",
+        "removeEventListener",
         "renderImageToCanvas",
         "Promise",
         "resolve",
         "canvas",
         "current",
         "context",
         "getContext",
         "img",
         "Image",
         "onload",
         "drawImage",
         "state",
-        "annotations",
-        "forEach",
         "px",
         "py",
         "pwidth",
         "pheight",
         "beginPath",
         "rect",
         "lineWidth",
@@ -65,20 +98,18 @@
         "fillStyle",
         "stroke",
         "font",
         "fillText",
         "src",
         "image",
         "onChange",
-        "setState",
         "onSubmit",
         "Math",
         "random",
         "onChangeType",
-        "e",
         "type",
         "currentTarget",
         "innerHTML",
         "deleteAnnotation",
         "filter",
         "downloadImage",
         "_asyncToGenerator",
@@ -98,37 +129,29 @@
         "href",
         "download",
         "click",
         "stop",
         "_toConsumableArray",
         "detectedAnotations",
         "_createClass",
-        "key",
         "value",
+        "this",
         "_this2",
         "imageSrc",
-        "this",
-        "_jsxs",
         "Annotation",
         "alt",
         "renderEditor",
-        "labels",
-        "className",
         "target",
-        "map",
-        "label",
         "onClick",
         "renderHighlight",
-        "_ref5",
+        "_ref6",
         "_ref2",
         "active",
         "border",
         "generateRandomHexCode",
-        "console",
-        "log",
         "ref",
         "display",
         "Component",
         "App",
         "_StreamlitComponentBa",
         "_super2",
         "apply",
@@ -148,12 +171,12 @@
     ],
     "sourceRoot": "",
     "sources": [
         "MyComponent.jsx",
         "index.jsx"
     ],
     "sourcesContent": [
-        "import {\n  Streamlit,\n  StreamlitComponentBase,\n  withStreamlitConnection,\n} from \"streamlit-component-lib\"\nimport React, { Component } from \"react\"\nimport \"./label-image.css\"\n\n// import Button from \"./Button\"\n\n// /**\n//  * This is a React-based component template. The `render()` function is called\n//  * automatically when your component should be re-rendered.\n//  */\n// class MyComponent extends StreamlitComponentBase {\n//   state = { numClicks: 0, isFocused: false }\n\n//   render = () => {\n//     // Arguments that are passed to the plugin in Python are accessible\n//     // via `this.props.args`. Here, we access the \"name\" arg.\n//     const name = this.props.args[\"name\"]\n\n//     // Streamlit sends us a theme object via props that we can use to ensure\n//     // that our component has visuals that match the active theme in a\n//     // streamlit app.\n//     const { theme } = this.props\n//     const style = {}\n\n//     // Maintain compatibility with older versions of Streamlit that don't send\n//     // a theme object.\n//     if (theme) {\n//       // Use the theme object to style our button border. Alternatively, the\n//       // theme style is defined in CSS vars.\n//       const borderStyling = `1px solid ${\n//         this.state.isFocused ? theme.primaryColor : \"gray\"\n//       }`\n//       style.border = borderStyling\n//       style.outline = borderStyling\n//     }\n\n//     // Show a button and some text.\n//     // When the button is clicked, we'll increment our \"numClicks\" state\n//     // variable, and send its new value back to Streamlit, where it'll\n//     // be available to the Python program.\n//     return (\n//       <span>\n//         Hello, {name}! &nbsp;\n//         <button\n//           style={style}\n//           onClick={this.onClicked}\n//           disabled={this.props.disabled}\n//           onFocus={this._onFocus}\n//           onBlur={this._onBlur}\n//         >\n//           Click Me!\n//         </button>\n//       </span>\n//     )\n//   }\n\n//   /** Click handler for our \"Click Me!\" button. */\n//   onClicked = () => {\n//     // Increment state.numClicks, and pass the new value back to\n//     // Streamlit via `Streamlit.setComponentValue`.\n//     this.setState(\n//       (prevState) => ({ numClicks: prevState.numClicks + 1 }),\n//       () => Streamlit.setComponentValue(this.state.numClicks)\n//     )\n//   }\n\n//   /** Focus handler for our \"Click Me!\" button. */\n//   _onFocus = () => {\n//     this.setState({ isFocused: true })\n//   }\n\n//   /** Blur handler for our \"Click Me!\" button. */\n//   _onBlur = () => {\n//     this.setState({ isFocused: false })\n//   }\n// }\n\n// // \"withStreamlitConnection\" is a wrapper function. It bootstraps the\n// // connection between your component and the Streamlit app, and handles\n// // passing arguments from Python -> Component.\n// //\n// // You don't need to edit withStreamlitConnection (but you're welcome to!).\n// export default withStreamlitConnection(MyComponent)\n// import {\n//   Streamlit,\n//   StreamlitComponentBase,\n//   withStreamlitConnection,\n// } from \"streamlit-component-lib\"\n// import React from \"react\"\n\n// class MyComponent extends StreamlitComponentBase {\n//   state = { numClicks: 0, isFocused: false }\n\n//   render = () => {\n//     const props = this.props\n//     const { image, labels } = props.args\n//     console.log({ labels })\n//     // prepend the proper prefix for base64 encoded jpeg images\n//     const imageSrc = \"data:image/jpeg;base64,\" + image\n//     console.log(props)\n//     return (\n//       <div>\n//         <img src={imageSrc} alt=\"My custom component image\" width=\"100%\" />\n//       </div>\n//     )\n//   }\n// }\n\n// export default withStreamlitConnection(MyComponent)\nimport Annotation from \"react-image-annotation\"\n\nconst Box = ({ children, geometry, style }) => (\n  <div\n    style={{\n      ...style,\n      position: \"absolute\",\n      left: `${geometry.x}%`,\n      top: `${geometry.y}%`,\n      height: `${geometry.height}%`,\n      width: `${geometry.width}%`,\n    }}\n  >\n    {children}\n  </div>\n)\n\nfunction renderHighlight({ annotation, active, deleteAnnotation }) {\n  const { geometry } = annotation\n  if (!geometry) return null\n  return (\n    <Box\n      key={annotation.data.id}\n      geometry={geometry}\n      style={{\n        border: `solid 1px ${active ? \"#3e8e41\" : generateRandomHexCode()}`,\n        // boxShadow: active && \"0 0 20px 20px rgba(255, 255, 255, 0.3) inset\",\n      }}\n    >\n      {active && (\n        <button\n          className=\"deleteAnnotationButton\"\n          onClick={() => {\n            console.log(\"delete\")\n            deleteAnnotation(annotation.data.id)\n          }}\n        >\n          X\n        </button>\n      )}\n    </Box>\n  )\n}\n\nfunction renderContent({ annotation }) {\n  const { geometry } = annotation\n  return (\n    <div\n      key={annotation.data.id}\n      style={{\n        background: \"black\",\n        color: \"white\",\n        padding: 10,\n        position: \"absolute\",\n        fontSize: 12,\n        left: `${geometry.x}%`,\n        top: `${geometry.y + geometry.height}%`,\n      }}\n    >\n      {annotation.data && annotation.data.text}\n    </div>\n  )\n}\nfunction renderEditor(props, labels) {\n  const { geometry } = props.annotation\n  if (!geometry) return null\n  return (\n    <div\n      className=\"holder\"\n      style={{\n        background: \"rgba(0, 0, 0, 0.15)\",\n        left: `${geometry.x > 80 ? 75 : geometry.x}%`,\n        top: `${geometry.y > 85 ? 85 : geometry.y}%`,\n      }}\n    >\n      <select\n        className=\"selectItem\"\n        onChange={(e) => {\n          props.onChange({\n            ...props.annotation,\n            data: {\n              ...props.annotation.data,\n              text: e.target.value,\n            },\n          })\n        }}\n      >\n        <option value=\"\">Select...</option>\n        {labels.map((label) => (\n          <option key={label} value={label}>\n            {label}\n          </option>\n        ))}\n      </select>\n      <button className=\"addLabelButton\" onClick={props.onSubmit}>\n        Add\n      </button>\n    </div>\n  )\n}\n\nclass MyComponent extends Component {\n  // state = {\n  //   annotations: [],\n  //   annotation: {},\n  // }\n\n  constructor(props) {\n    super(props)\n    this.state = {\n      annotations: [...this.props?.detectedAnotations],\n      annotation: {},\n    }\n  }\n  canvasRef = React.createRef()\n\n  renderImageToCanvas = () => {\n    return new Promise((resolve) => {\n      const canvas = this.canvasRef.current\n      const context = canvas.getContext(\"2d\")\n      const img = new Image()\n\n      img.onload = () => {\n        canvas.width = img.width\n        canvas.height = img.height\n        context.drawImage(img, 0, 0, img.width, img.height)\n\n        this.state.annotations.forEach((annotation) => {\n          const { geometry, data } = annotation\n          const { x, y, width, height } = geometry\n          const { text } = data\n\n          const [px, py, pwidth, pheight] = [\n            (x / 100) * img.width,\n            (y / 100) * img.height,\n            (width / 100) * img.width,\n            (height / 100) * img.height,\n          ]\n\n          context.beginPath()\n          context.rect(px, py, pwidth, pheight)\n          context.lineWidth = 3\n          context.strokeStyle = \"red\"\n          context.fillStyle = \"red\"\n          context.stroke()\n          context.font = \"40px Arial\" // Set the font size and font family\n          context.fillText(text, px, py > 15 ? py - 5 : py + 15)\n        })\n\n        // Resolve the Promise after the image has loaded and drawn\n        resolve()\n      }\n\n      img.src = \"data:image/jpeg;base64,\" + this.props.image\n    })\n  }\n\n  onChange = (annotation) => {\n    this.setState({ annotation })\n  }\n\n  onSubmit = (annotation) => {\n    const { geometry, data } = annotation\n\n    this.setState({\n      annotation: {},\n      annotations: this.state.annotations.concat({\n        geometry,\n        data: {\n          ...data,\n          id: Math.random(),\n        },\n      }),\n    })\n  }\n  onChangeType = (e) => {\n    this.setState({\n      annotation: {},\n      type: e.currentTarget.innerHTML,\n    })\n  }\n  deleteAnnotation = (id) => {\n    this.setState({\n      annotations: this.state.annotations.filter((annotation) => {\n        return annotation.data.id !== id\n      }),\n    })\n  }\n  downloadImage = async () => {\n    // First, render the image to the canvas\n    await this.renderImageToCanvas()\n\n    // Then, create a data URL of the canvas content\n    const dataUrl = this.canvasRef.current?.toDataURL()\n\n    // Create a new 'a' element\n    const link = document.createElement(\"a\")\n    link.href = dataUrl\n\n    // Set the download attribute with the desired file name\n    link.download = \"image.png\"\n\n    // Trigger a click on the link to start the download\n    link.click()\n  }\n  render() {\n    const imageSrc = \"data:image/jpeg;base64,\" + this.props.image\n\n    return (\n      <div>\n        <Annotation\n          src={imageSrc}\n          alt=\"pcb\"\n          annotations={this.state.annotations}\n          type={this.state.type}\n          value={this.state.annotation}\n          onChange={this.onChange}\n          onSubmit={this.onSubmit}\n          renderEditor={(props) => {\n            const labels = this.props.labels\n            return renderEditor(props, labels)\n          }}\n          renderContent={renderContent}\n          renderHighlight={({ annotation, active }) => {\n            return renderHighlight({\n              annotation,\n              active,\n              deleteAnnotation: this.deleteAnnotation,\n            })\n          }}\n        />\n        <button className=\"downloadButton\" onClick={this.downloadImage}>\n          Download\n        </button>\n\n        <canvas ref={this.canvasRef} style={{ display: \"none\" }} />\n      </div>\n    )\n  }\n}\n\nclass App extends StreamlitComponentBase {\n  render() {\n    const { image, labels, detectedAnotations } = this.props.args\n\n    return (\n      <MyComponent\n        image={image}\n        labels={labels}\n        detectedAnotations={detectedAnotations}\n      />\n    )\n  }\n}\n\nexport default withStreamlitConnection(App)\n\nfunction generateRandomHexCode() {\n  let hexCode = \"#\"\n\n  // Generate a random hex color code\n  for (let i = 0; i < 6; i++) {\n    // Generate a random number between 0 and 15, convert to hex\n    let hexSegment = Math.floor(Math.random() * 16).toString(16)\n\n    // Add the segment to the hex code\n    hexCode += hexSegment\n  }\n\n  return hexCode\n}\n\n// {\n//   \"annotations\": [\n//       {\n//           \"geometry\": {\n//               \"type\": \"RECTANGLE\",\n//               \"x\": 13.494318181818182,\n//               \"y\": 21.284080914687774,\n//               \"width\": 12.642045454545455,\n//               \"height\": 27.08883025505717\n//           },\n//           \"data\": {\n//               \"text\": \"new\",\n//               \"id\": 0.3982473149726953\n//           }\n//       }\n//   ],\n//   \"annotation\": {}\n// }\n\n// {\n//   \"annotations\": [],\n//   \"annotation\": {\n//       \"selection\": {\n//           \"mode\": \"EDITING\",\n//           \"anchorX\": 16.90340909090909,\n//           \"anchorY\": 29.37554969217238,\n//           \"showEditor\": true\n//       },\n//       \"geometry\": {\n//           \"type\": \"RECTANGLE\",\n//           \"x\": 16.90340909090909,\n//           \"y\": 29.37554969217238,\n//           \"width\": 9.65909090909091,\n//           \"height\": 5.980650835532106\n//       },\n//       \"data\": {\n//           \"text\": \"option1\"\n//       }\n//   }\n// }\n\n// {\n//   \"annotations\": [],\n//   \"annotation\": {\n//       \"selection\": {\n//           \"mode\": \"EDITING\",\n//           \"anchorX\": 17.1875,\n//           \"anchorY\": 29.551451187335093,\n//           \"showEditor\": true\n//       },\n//       \"geometry\": {\n//           \"type\": \"RECTANGLE\",\n//           \"x\": 17.1875,\n//           \"y\": 29.551451187335093,\n//           \"width\": 9.65909090909091,\n//           \"height\": 5.980650835532099\n//       },\n//       \"data\": {\n//           \"text\": \"option1\"\n//       }\n//   }\n// }\n\n// {\n//   \"annotations\": [\n//       {\n//           \"geometry\": {\n//               \"type\": \"RECTANGLE\",\n//               \"x\": 1.4204545454545454,\n//               \"y\": 1.58311345646438,\n//               \"width\": 49.85795454545455,\n//               \"height\": 50.131926121372025\n//           },\n//           \"data\": {\n//               \"text\": \"option1\",\n//               \"id\": 0.42675792821517256\n//           }\n//       },\n//       {\n//           \"geometry\": {\n//               \"type\": \"RECTANGLE\",\n//               \"x\": 51.42045454545454,\n//               \"y\": 49.780123131046615,\n//               \"width\": 48.295454545454554,\n//               \"height\": 49.42832014072119\n//           },\n//           \"data\": {\n//               \"text\": \"option2\",\n//               \"id\": 0.1293396936727722\n//           }\n//       }\n//   ],\n//   \"annotation\": {\n//       \"selection\": {\n//           \"mode\": \"EDITING\",\n//           \"anchorX\": 98.7215909090909,\n//           \"anchorY\": 1.2313104661389622,\n//           \"showEditor\": true\n//       },\n//       \"geometry\": {\n//           \"type\": \"RECTANGLE\",\n//           \"x\": 51.42045454545454,\n//           \"y\": 1.2313104661389622,\n//           \"width\": 47.30113636363637,\n//           \"height\": 48.37291116974494\n//       },\n//       \"data\": {\n//           \"text\": \"option3\"\n//       }\n//   }\n// }\n",
+        "import {\n  Streamlit,\n  StreamlitComponentBase,\n  withStreamlitConnection,\n} from \"streamlit-component-lib\"\nimport React, { Component, useState, useEffect } from \"react\"\nimport \"./label-image.css\"\n\n// import Button from \"./Button\"\n\n// /**\n//  * This is a React-based component template. The `render()` function is called\n//  * automatically when your component should be re-rendered.\n//  */\n// class MyComponent extends StreamlitComponentBase {\n//   state = { numClicks: 0, isFocused: false }\n\n//   render = () => {\n//     // Arguments that are passed to the plugin in Python are accessible\n//     // via `this.props.args`. Here, we access the \"name\" arg.\n//     const name = this.props.args[\"name\"]\n\n//     // Streamlit sends us a theme object via props that we can use to ensure\n//     // that our component has visuals that match the active theme in a\n//     // streamlit app.\n//     const { theme } = this.props\n//     const style = {}\n\n//     // Maintain compatibility with older versions of Streamlit that don't send\n//     // a theme object.\n//     if (theme) {\n//       // Use the theme object to style our button border. Alternatively, the\n//       // theme style is defined in CSS vars.\n//       const borderStyling = `1px solid ${\n//         this.state.isFocused ? theme.primaryColor : \"gray\"\n//       }`\n//       style.border = borderStyling\n//       style.outline = borderStyling\n//     }\n\n//     // Show a button and some text.\n//     // When the button is clicked, we'll increment our \"numClicks\" state\n//     // variable, and send its new value back to Streamlit, where it'll\n//     // be available to the Python program.\n//     return (\n//       <span>\n//         Hello, {name}! &nbsp;\n//         <button\n//           style={style}\n//           onClick={this.onClicked}\n//           disabled={this.props.disabled}\n//           onFocus={this._onFocus}\n//           onBlur={this._onBlur}\n//         >\n//           Click Me!\n//         </button>\n//       </span>\n//     )\n//   }\n\n//   /** Click handler for our \"Click Me!\" button. */\n//   onClicked = () => {\n//     // Increment state.numClicks, and pass the new value back to\n//     // Streamlit via `Streamlit.setComponentValue`.\n//     this.setState(\n//       (prevState) => ({ numClicks: prevState.numClicks + 1 }),\n//       () => Streamlit.setComponentValue(this.state.numClicks)\n//     )\n//   }\n\n//   /** Focus handler for our \"Click Me!\" button. */\n//   _onFocus = () => {\n//     this.setState({ isFocused: true })\n//   }\n\n//   /** Blur handler for our \"Click Me!\" button. */\n//   _onBlur = () => {\n//     this.setState({ isFocused: false })\n//   }\n// }\n\n// // \"withStreamlitConnection\" is a wrapper function. It bootstraps the\n// // connection between your component and the Streamlit app, and handles\n// // passing arguments from Python -> Component.\n// //\n// // You don't need to edit withStreamlitConnection (but you're welcome to!).\n// export default withStreamlitConnection(MyComponent)\n// import {\n//   Streamlit,\n//   StreamlitComponentBase,\n//   withStreamlitConnection,\n// } from \"streamlit-component-lib\"\n// import React from \"react\"\n\n// class MyComponent extends StreamlitComponentBase {\n//   state = { numClicks: 0, isFocused: false }\n\n//   render = () => {\n//     const props = this.props\n//     const { image, labels } = props.args\n//     console.log({ labels })\n//     // prepend the proper prefix for base64 encoded jpeg images\n//     const imageSrc = \"data:image/jpeg;base64,\" + image\n//     console.log(props)\n//     return (\n//       <div>\n//         <img src={imageSrc} alt=\"My custom component image\" width=\"100%\" />\n//       </div>\n//     )\n//   }\n// }\n\n// export default withStreamlitConnection(MyComponent)\nimport Annotation from \"react-image-annotation\"\n\nconst Box = ({ children, geometry, style }) => (\n  <div\n    style={{\n      ...style,\n      position: \"absolute\",\n      left: `${geometry.x}%`,\n      top: `${geometry.y}%`,\n      height: `${geometry.height}%`,\n      width: `${geometry.width}%`,\n    }}\n  >\n    {children}\n  </div>\n)\n\nfunction renderHighlight({ annotation, active, deleteAnnotation }) {\n  const { geometry } = annotation\n  if (!geometry) return null\n  return (\n    <Box\n      key={annotation.data.id}\n      geometry={geometry}\n      style={{\n        border: `solid 1px ${active ? \"#3e8e41\" : generateRandomHexCode()}`,\n        // boxShadow: active && \"0 0 20px 20px rgba(255, 255, 255, 0.3) inset\",\n      }}\n    >\n      {active && (\n        <button\n          className=\"deleteAnnotationButton\"\n          onClick={() => {\n            console.log(\"delete\")\n            deleteAnnotation(annotation.data.id)\n          }}\n        >\n          X\n        </button>\n      )}\n    </Box>\n  )\n}\n\nfunction renderContent({ annotation }) {\n  const { geometry } = annotation\n  return (\n    <div\n      key={annotation.data.id}\n      style={{\n        background: \"black\",\n        color: \"white\",\n        padding: 10,\n        position: \"absolute\",\n        fontSize: 12,\n        left: `${geometry.x}%`,\n        top: `${geometry.y + geometry.height}%`,\n      }}\n    >\n      {annotation.data && annotation.data.text}\n    </div>\n  )\n}\nfunction renderEditor(props, labels) {\n  const { geometry } = props.annotation\n  if (!geometry) return null\n  return (\n    <div\n      className=\"holder\"\n      style={{\n        background: \"rgba(0, 0, 0, 0.15)\",\n        left: `${geometry.x > 80 ? 75 : geometry.x}%`,\n        top: `${geometry.y > 85 ? 85 : geometry.y}%`,\n      }}\n    >\n      <select\n        className=\"selectItem\"\n        onChange={(e) => {\n          props.onChange({\n            ...props.annotation,\n            data: {\n              ...props.annotation.data,\n              text: e.target.value,\n            },\n          })\n        }}\n      >\n        <option value=\"\">Select...</option>\n        {labels.map((label) => (\n          <option key={label} value={label}>\n            {label}\n          </option>\n        ))}\n      </select>\n      <button className=\"addLabelButton\" onClick={props.onSubmit}>\n        Add\n      </button>\n    </div>\n  )\n}\n\nconst DataDiv = ({ annotations, labels }) => {\n  // we will create a table here\n  const [data, setData] = useState({})\n\n  useEffect(() => {\n    const tempData = {}\n    labels.forEach((label) => {\n      tempData[label] = 0\n    })\n    annotations.forEach((annotation) => {\n      const { data } = annotation\n      const { text } = data\n      const frquency = tempData[text] ? tempData[text] + 1 : 1\n      tempData[text] = frquency\n    })\n    setData(tempData)\n    console.log({ tempData })\n  }, [annotations])\n  return (\n    <>\n      <div className=\"dataHolder\">\n        {Object.keys(data).map((key) => {\n          return (\n            <div className=\"dataItem\" key={key}>\n              <div className=\"dataItemLabel\">{key}</div>\n              <div className=\"dataItemValue\">{data[key]}</div>\n            </div>\n          )\n        })}\n      </div>\n    </>\n  )\n}\n\nclass MyComponent extends Component {\n  // state = {\n  //   annotations: [],\n  //   annotation: {},\n  // }\n\n  constructor(props) {\n    super(props)\n    this.state = {\n      annotations: [...this.props?.detectedAnotations],\n      annotation: {},\n      showDiv: false,\n      coords: { x: 0, y: 0 },\n    }\n  }\n  canvasRef = React.createRef()\n  moveDiv = (e) => {\n    this.setState({ coords: { x: e.clientX, y: e.clientY } })\n  }\n\n  onMouseMove = (e) => {\n    this.setState({ showDiv: true })\n    window.addEventListener(\"mousemove\", this.moveDiv)\n  }\n\n  onMouseOut = (e) => {\n    this.setState({ showDiv: false })\n    window.removeEventListener(\"mousemove\", this.moveDiv)\n  }\n\n  componentWillUnmount() {\n    window.removeEventListener(\"mousemove\", this.moveDiv)\n  }\n\n  renderImageToCanvas = () => {\n    return new Promise((resolve) => {\n      const canvas = this.canvasRef.current\n      const context = canvas.getContext(\"2d\")\n      const img = new Image()\n\n      img.onload = () => {\n        canvas.width = img.width\n        canvas.height = img.height\n        context.drawImage(img, 0, 0, img.width, img.height)\n\n        this.state.annotations.forEach((annotation) => {\n          const { geometry, data } = annotation\n          const { x, y, width, height } = geometry\n          const { text } = data\n\n          const [px, py, pwidth, pheight] = [\n            (x / 100) * img.width,\n            (y / 100) * img.height,\n            (width / 100) * img.width,\n            (height / 100) * img.height,\n          ]\n\n          context.beginPath()\n          context.rect(px, py, pwidth, pheight)\n          context.lineWidth = 3\n          context.strokeStyle = \"red\"\n          context.fillStyle = \"red\"\n          context.stroke()\n          context.font = \"40px Arial\" // Set the font size and font family\n          context.fillText(text, px, py > 15 ? py - 5 : py + 15)\n        })\n\n        // Resolve the Promise after the image has loaded and drawn\n        resolve()\n      }\n\n      img.src = \"data:image/jpeg;base64,\" + this.props.image\n    })\n  }\n\n  onChange = (annotation) => {\n    this.setState({ annotation })\n  }\n\n  onSubmit = (annotation) => {\n    const { geometry, data } = annotation\n\n    this.setState({\n      annotation: {},\n      annotations: this.state.annotations.concat({\n        geometry,\n        data: {\n          ...data,\n          id: Math.random(),\n        },\n      }),\n    })\n  }\n  onChangeType = (e) => {\n    this.setState({\n      annotation: {},\n      type: e.currentTarget.innerHTML,\n    })\n  }\n  deleteAnnotation = (id) => {\n    this.setState({\n      annotations: this.state.annotations.filter((annotation) => {\n        return annotation.data.id !== id\n      }),\n    })\n  }\n\n  downloadImage = async () => {\n    // First, render the image to the canvas\n    await this.renderImageToCanvas()\n\n    // Then, create a data URL of the canvas content\n    const dataUrl = this.canvasRef.current?.toDataURL()\n\n    // Create a new 'a' element\n    const link = document.createElement(\"a\")\n    link.href = dataUrl\n\n    // Set the download attribute with the desired file name\n    link.download = \"image.png\"\n\n    // Trigger a click on the link to start the download\n    link.click()\n  }\n  render() {\n    const imageSrc = \"data:image/jpeg;base64,\" + this.props.image\n\n    return (\n      <>\n        <div\n          className=\"hoverDiv\"\n          onMouseMove={this.onMouseMove}\n          onMouseOut={this.onMouseOut}\n        >\n          <Annotation\n            src={imageSrc}\n            alt=\"pcb\"\n            annotations={this.state.annotations}\n            type={this.state.type}\n            value={this.state.annotation}\n            onChange={this.onChange}\n            onSubmit={this.onSubmit}\n            renderEditor={(props) => {\n              const labels = this.props.labels\n              return renderEditor(props, labels)\n            }}\n            renderContent={renderContent}\n            renderHighlight={({ annotation, active }) => {\n              return renderHighlight({\n                annotation,\n                active,\n                deleteAnnotation: this.deleteAnnotation,\n              })\n            }}\n          />\n          {this.state.showDiv && (\n            <div\n              className=\"hover-info\"\n              style={{\n                top: `${this.state.coords.y + 30}px`,\n                left: `${this.state.coords.x + 30}px`,\n              }}\n              // style={{\n              //   top: `${50}px`,\n              //   left: `${20}px`,\n              // }}\n            >\n              <DataDiv\n                labels={this.props.labels}\n                annotations={this.state.annotations}\n              />\n            </div>\n          )}\n        </div>\n        <button className=\"downloadButton\" onClick={this.downloadImage}>\n          Download\n        </button>\n\n        <canvas ref={this.canvasRef} style={{ display: \"none\" }} />\n      </>\n    )\n  }\n}\n\nclass App extends StreamlitComponentBase {\n  render() {\n    const { image, labels, detectedAnotations } = this.props.args\n\n    return (\n      <MyComponent\n        image={image}\n        labels={labels}\n        detectedAnotations={detectedAnotations}\n      />\n    )\n  }\n}\n\nexport default withStreamlitConnection(App)\n\nfunction generateRandomHexCode() {\n  let hexCode = \"#\"\n\n  // Generate a random hex color code\n  for (let i = 0; i < 6; i++) {\n    // Generate a random number between 0 and 15, convert to hex\n    let hexSegment = Math.floor(Math.random() * 16).toString(16)\n\n    // Add the segment to the hex code\n    hexCode += hexSegment\n  }\n\n  return hexCode\n}\n\n// {\n//   \"annotations\": [\n//       {\n//           \"geometry\": {\n//               \"type\": \"RECTANGLE\",\n//               \"x\": 13.494318181818182,\n//               \"y\": 21.284080914687774,\n//               \"width\": 12.642045454545455,\n//               \"height\": 27.08883025505717\n//           },\n//           \"data\": {\n//               \"text\": \"new\",\n//               \"id\": 0.3982473149726953\n//           }\n//       }\n//   ],\n//   \"annotation\": {}\n// }\n\n// {\n//   \"annotations\": [],\n//   \"annotation\": {\n//       \"selection\": {\n//           \"mode\": \"EDITING\",\n//           \"anchorX\": 16.90340909090909,\n//           \"anchorY\": 29.37554969217238,\n//           \"showEditor\": true\n//       },\n//       \"geometry\": {\n//           \"type\": \"RECTANGLE\",\n//           \"x\": 16.90340909090909,\n//           \"y\": 29.37554969217238,\n//           \"width\": 9.65909090909091,\n//           \"height\": 5.980650835532106\n//       },\n//       \"data\": {\n//           \"text\": \"option1\"\n//       }\n//   }\n// }\n\n// {\n//   \"annotations\": [],\n//   \"annotation\": {\n//       \"selection\": {\n//           \"mode\": \"EDITING\",\n//           \"anchorX\": 17.1875,\n//           \"anchorY\": 29.551451187335093,\n//           \"showEditor\": true\n//       },\n//       \"geometry\": {\n//           \"type\": \"RECTANGLE\",\n//           \"x\": 17.1875,\n//           \"y\": 29.551451187335093,\n//           \"width\": 9.65909090909091,\n//           \"height\": 5.980650835532099\n//       },\n//       \"data\": {\n//           \"text\": \"option1\"\n//       }\n//   }\n// }\n\n// {\n//   \"annotations\": [\n//       {\n//           \"geometry\": {\n//               \"type\": \"RECTANGLE\",\n//               \"x\": 1.4204545454545454,\n//               \"y\": 1.58311345646438,\n//               \"width\": 49.85795454545455,\n//               \"height\": 50.131926121372025\n//           },\n//           \"data\": {\n//               \"text\": \"option1\",\n//               \"id\": 0.42675792821517256\n//           }\n//       },\n//       {\n//           \"geometry\": {\n//               \"type\": \"RECTANGLE\",\n//               \"x\": 51.42045454545454,\n//               \"y\": 49.780123131046615,\n//               \"width\": 48.295454545454554,\n//               \"height\": 49.42832014072119\n//           },\n//           \"data\": {\n//               \"text\": \"option2\",\n//               \"id\": 0.1293396936727722\n//           }\n//       }\n//   ],\n//   \"annotation\": {\n//       \"selection\": {\n//           \"mode\": \"EDITING\",\n//           \"anchorX\": 98.7215909090909,\n//           \"anchorY\": 1.2313104661389622,\n//           \"showEditor\": true\n//       },\n//       \"geometry\": {\n//           \"type\": \"RECTANGLE\",\n//           \"x\": 51.42045454545454,\n//           \"y\": 1.2313104661389622,\n//           \"width\": 47.30113636363637,\n//           \"height\": 48.37291116974494\n//       },\n//       \"data\": {\n//           \"text\": \"option3\"\n//       }\n//   }\n// }\n",
         "import React from \"react\"\nimport ReactDOM from \"react-dom\"\nimport MyComponent from \"./MyComponent\"\n\nReactDOM.render(\n  <React.StrictMode>\n    <MyComponent />\n  </React.StrictMode>,\n  document.getElementById(\"root\")\n)\n"
     ],
     "version": 3
 }
```

### Comparing `image_label-2.4.1/image_label/frontend/build/static/js/runtime-main.657b0728.js` & `image_label-2.4.2/image_label/frontend/build/static/js/runtime-main.657b0728.js`

 * *Files identical despite different names*

### Comparing `image_label-2.4.1/image_label/frontend/build/static/js/runtime-main.657b0728.js.map` & `image_label-2.4.2/image_label/frontend/build/static/js/runtime-main.657b0728.js.map`

 * *Files identical despite different names*

### Comparing `image_label-2.4.1/image_label.egg-info/PKG-INFO` & `image_label-2.4.2/image_label.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: image-label
-Version: 2.4.1
+Version: 2.4.2
 Summary: This is an Image Labeling Component for streamlit
 Home-page: https://github.com/SksOp/image_label
 Author: sks
 Author-email: shubhaman47@gmail.com
 Requires-Python: >=3.6
 Description-Content-Type: text/plain
 License-File: LICENSE
```

### Comparing `image_label-2.4.1/setup.py` & `image_label-2.4.2/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 import setuptools
 
 setuptools.setup(
     name="image_label",
-    version="2.4.1",
+    version="2.4.2",
     author="sks",
     author_email="shubhaman47@gmail.com",
     description="This is an Image Labeling Component for streamlit",
     long_description="The image_label package provides a custom Streamlit component for image annotation. It allows users to manually annotate images with bounding boxes and labels, making it a great tool for data labeling tasks, especially in machine learning projects. for more info go to https://github.com/SksOp/image_label",
     long_description_content_type="text/plain",
     url="https://github.com/SksOp/image_label",
     packages=setuptools.find_packages(),
```
