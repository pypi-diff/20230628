# Comparing `tmp/Google Ads Transparency Scraper-1.2.tar.gz` & `tmp/Google Ads Transparency Scraper-1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "Google Ads Transparency Scraper-1.2.tar", last modified: Wed Jun 28 07:52:46 2023, max compression
+gzip compressed data, was "Google Ads Transparency Scraper-1.3.tar", last modified: Wed Jun 28 10:55:24 2023, max compression
```

## Comparing `Google Ads Transparency Scraper-1.2.tar` & `Google Ads Transparency Scraper-1.3.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 07:52:46.454018 Google Ads Transparency Scraper-1.2/
-drwxrwxrwx   0        0        0        0 2023-06-28 07:52:46.445019 Google Ads Transparency Scraper-1.2/GoogleAdsTransparency/
--rw-rw-rw-   0        0        0      106 2023-06-28 05:20:16.000000 Google Ads Transparency Scraper-1.2/GoogleAdsTransparency/__init__.py
--rw-rw-rw-   0        0        0    10314 2023-06-28 07:22:06.000000 Google Ads Transparency Scraper-1.2/GoogleAdsTransparency/main.py
--rw-rw-rw-   0        0        0    11448 2023-06-28 06:06:26.000000 Google Ads Transparency Scraper-1.2/GoogleAdsTransparency/regions.py
-drwxrwxrwx   0        0        0        0 2023-06-28 07:52:46.453020 Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/
--rw-rw-rw-   0        0        0      855 2023-06-28 07:52:46.000000 Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      399 2023-06-28 07:52:46.000000 Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 07:52:46.000000 Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       69 2023-06-28 07:52:46.000000 Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/requires.txt
--rw-rw-rw-   0        0        0       22 2023-06-28 07:52:46.000000 Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      855 2023-06-28 07:52:46.455020 Google Ads Transparency Scraper-1.2/PKG-INFO
--rw-rw-rw-   0        0        0       29 2023-06-26 11:23:38.000000 Google Ads Transparency Scraper-1.2/README.md
--rw-rw-rw-   0        0        0       86 2023-06-28 07:52:46.456020 Google Ads Transparency Scraper-1.2/setup.cfg
--rw-rw-rw-   0        0        0     1273 2023-06-28 07:52:18.000000 Google Ads Transparency Scraper-1.2/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:55:24.301246 Google Ads Transparency Scraper-1.3/
+drwxrwxrwx   0        0        0        0 2023-06-28 10:55:24.277236 Google Ads Transparency Scraper-1.3/GoogleAdsTransparency/
+-rw-rw-rw-   0        0        0      106 2023-06-28 05:20:16.000000 Google Ads Transparency Scraper-1.3/GoogleAdsTransparency/__init__.py
+-rw-rw-rw-   0        0        0    10314 2023-06-28 07:22:06.000000 Google Ads Transparency Scraper-1.3/GoogleAdsTransparency/main.py
+-rw-rw-rw-   0        0        0    11448 2023-06-28 06:06:26.000000 Google Ads Transparency Scraper-1.3/GoogleAdsTransparency/regions.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:55:24.293243 Google Ads Transparency Scraper-1.3/Google_Ads_Transparency_Scraper.egg-info/
+-rw-rw-rw-   0        0        0      863 2023-06-28 10:55:23.000000 Google Ads Transparency Scraper-1.3/Google_Ads_Transparency_Scraper.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      399 2023-06-28 10:55:24.000000 Google Ads Transparency Scraper-1.3/Google_Ads_Transparency_Scraper.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 10:55:23.000000 Google Ads Transparency Scraper-1.3/Google_Ads_Transparency_Scraper.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       69 2023-06-28 10:55:23.000000 Google Ads Transparency Scraper-1.3/Google_Ads_Transparency_Scraper.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       22 2023-06-28 10:55:23.000000 Google Ads Transparency Scraper-1.3/Google_Ads_Transparency_Scraper.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      863 2023-06-28 10:55:24.301246 Google Ads Transparency Scraper-1.3/PKG-INFO
+-rw-rw-rw-   0        0        0       29 2023-06-26 11:23:38.000000 Google Ads Transparency Scraper-1.3/README.md
+-rw-rw-rw-   0        0        0       86 2023-06-28 10:55:24.301246 Google Ads Transparency Scraper-1.3/setup.cfg
+-rw-rw-rw-   0        0        0     1291 2023-06-28 10:54:51.000000 Google Ads Transparency Scraper-1.3/setup.py
```

### Comparing `Google Ads Transparency Scraper-1.2/GoogleAdsTransparency/main.py` & `Google Ads Transparency Scraper-1.3/GoogleAdsTransparency/main.py`

 * *Files identical despite different names*

### Comparing `Google Ads Transparency Scraper-1.2/GoogleAdsTransparency/regions.py` & `Google Ads Transparency Scraper-1.3/GoogleAdsTransparency/regions.py`

 * *Files identical despite different names*

### Comparing `Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/PKG-INFO` & `Google Ads Transparency Scraper-1.3/Google_Ads_Transparency_Scraper.egg-info/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,17 +1,18 @@
 Metadata-Version: 2.1
 Name: Google-Ads-Transparency-Scraper
-Version: 1.2
+Version: 1.3
 Summary: A scraper for getting Ads from Google Transparency
 Home-page: https://github.com/faniAhmed/GoogleAdsTransparencyScraper
 Download-URL: https://github.com/faniAhmed/GoogleAdsTransparencyScraper/archive/refs/tags/v1.2.tar.gz
 Author: Farhan Ahmed
 Author-email: jattfarhan10@gmail.com
 License: Securely Incorporation
 Keywords: Google,Transparency,Scraper,API,Google Ads,Ads,Google Transparency,Google Transparency Scraper,Google Ads Scrapre
+Platform: any
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Intended Audience :: Developers
 Classifier: License :: Free for non-commercial use
 Classifier: Natural Language :: Urdu
 Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python
```

### Comparing `Google Ads Transparency Scraper-1.2/PKG-INFO` & `Google Ads Transparency Scraper-1.3/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,17 +1,18 @@
 Metadata-Version: 2.1
 Name: Google Ads Transparency Scraper
-Version: 1.2
+Version: 1.3
 Summary: A scraper for getting Ads from Google Transparency
 Home-page: https://github.com/faniAhmed/GoogleAdsTransparencyScraper
 Download-URL: https://github.com/faniAhmed/GoogleAdsTransparencyScraper/archive/refs/tags/v1.2.tar.gz
 Author: Farhan Ahmed
 Author-email: jattfarhan10@gmail.com
 License: Securely Incorporation
 Keywords: Google,Transparency,Scraper,API,Google Ads,Ads,Google Transparency,Google Transparency Scraper,Google Ads Scrapre
+Platform: any
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Intended Audience :: Developers
 Classifier: License :: Free for non-commercial use
 Classifier: Natural Language :: Urdu
 Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python
```

### Comparing `Google Ads Transparency Scraper-1.2/setup.py` & `Google Ads Transparency Scraper-1.3/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -3,16 +3,16 @@
 
 setup(
     name="Google Ads Transparency Scraper",
     author="Farhan Ahmed",
     author_email="jattfarhan10@gmail.com",
     url="https://github.com/faniAhmed/GoogleAdsTransparencyScraper",
     description="A scraper for getting Ads from Google Transparency",
-    version="1.2",
-    packages=find_packages(where=".", exclude=["tests"]),
+    version="1.3",
+    #packages=find_packages(where=".", exclude=["tests"]),
     download_url= 'https://github.com/faniAhmed/GoogleAdsTransparencyScraper/archive/refs/tags/v1.2.tar.gz',
     keywords= ['Google', 'Transparency', 'Scraper', 'API', 'Google Ads', 'Ads', 'Google Transparency', 'Google Transparency Scraper', 'Google Ads Scrapre'],
     license='Securely Incorporation',
     install_requires=[
         "setuptools>=45.0",
         "beautifulsoup4>=4.12.2",
         "Requests>=2.31.0",
@@ -21,10 +21,11 @@
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Environment :: Console",
         "Intended Audience :: Developers",
         "License :: Free for non-commercial use",
         "Natural Language :: Urdu",
         "Operating System :: OS Independent",
-        "Programming Language :: Python :: 3.9",
+        "Programming Language :: Python",
     ],
+    platforms=["any"],
 )
```

