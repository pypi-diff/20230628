# Comparing `tmp/tweeterpy-0.0.4.tar.gz` & `tmp/tweeterpy-0.0.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tweeterpy-0.0.4.tar", last modified: Sun Jun 25 07:48:12 2023, max compression
+gzip compressed data, was "tweeterpy-0.0.5.tar", last modified: Wed Jun 28 07:57:47 2023, max compression
```

## Comparing `tweeterpy-0.0.4.tar` & `tweeterpy-0.0.5.tar`

### file list

```diff
@@ -1,23 +1,23 @@
-drwxrwxrwx   0        0        0        0 2023-06-25 07:48:12.553864 tweeterpy-0.0.4/
--rw-rw-rw-   0        0        0     1093 2023-05-19 18:11:22.000000 tweeterpy-0.0.4/LICENSE
--rw-rw-rw-   0        0        0       22 2023-06-20 15:06:14.000000 tweeterpy-0.0.4/MANIFEST.in
--rw-rw-rw-   0        0        0     3389 2023-06-25 07:48:12.553864 tweeterpy-0.0.4/PKG-INFO
--rw-rw-rw-   0        0        0     2336 2023-06-22 07:42:40.000000 tweeterpy-0.0.4/README.md
--rw-rw-rw-   0        0        0       42 2023-06-25 07:48:12.553864 tweeterpy-0.0.4/setup.cfg
--rw-rw-rw-   0        0        0     1499 2023-06-25 07:47:41.000000 tweeterpy-0.0.4/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-25 07:48:12.553864 tweeterpy-0.0.4/tweeterpy/
--rw-rw-rw-   0        0        0       34 2023-06-20 15:09:15.000000 tweeterpy-0.0.4/tweeterpy/__init__.py
--rw-rw-rw-   0        0        0     2581 2023-06-20 09:49:11.000000 tweeterpy-0.0.4/tweeterpy/api_util.py
--rw-rw-rw-   0        0        0      671 2023-06-25 06:51:11.000000 tweeterpy-0.0.4/tweeterpy/config.py
--rw-rw-rw-   0        0        0     1980 2023-06-20 14:19:17.000000 tweeterpy-0.0.4/tweeterpy/constants.py
--rw-rw-rw-   0        0        0     6654 2023-06-24 14:06:58.000000 tweeterpy-0.0.4/tweeterpy/login_util.py
--rw-rw-rw-   0        0        0     1653 2023-06-20 07:35:05.000000 tweeterpy-0.0.4/tweeterpy/request_util.py
--rw-rw-rw-   0        0        0     2278 2023-06-25 06:51:11.000000 tweeterpy-0.0.4/tweeterpy/session_util.py
--rw-rw-rw-   0        0        0    22817 2023-06-25 07:23:32.000000 tweeterpy-0.0.4/tweeterpy/tweeterpy.py
--rw-rw-rw-   0        0        0     3526 2023-06-25 07:16:42.000000 tweeterpy-0.0.4/tweeterpy/util.py
-drwxrwxrwx   0        0        0        0 2023-06-25 07:48:12.553864 tweeterpy-0.0.4/tweeterpy.egg-info/
--rw-rw-rw-   0        0        0     3389 2023-06-25 07:48:12.000000 tweeterpy-0.0.4/tweeterpy.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      406 2023-06-25 07:48:12.000000 tweeterpy-0.0.4/tweeterpy.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-25 07:48:12.000000 tweeterpy-0.0.4/tweeterpy.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      221 2023-06-25 07:48:12.000000 tweeterpy-0.0.4/tweeterpy.egg-info/requires.txt
--rw-rw-rw-   0        0        0       10 2023-06-25 07:48:12.000000 tweeterpy-0.0.4/tweeterpy.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 07:57:47.935358 tweeterpy-0.0.5/
+-rw-rw-rw-   0        0        0     1093 2023-05-19 18:11:22.000000 tweeterpy-0.0.5/LICENSE
+-rw-rw-rw-   0        0        0       22 2023-06-20 15:06:14.000000 tweeterpy-0.0.5/MANIFEST.in
+-rw-rw-rw-   0        0        0     3389 2023-06-28 07:57:47.935358 tweeterpy-0.0.5/PKG-INFO
+-rw-rw-rw-   0        0        0     2336 2023-06-22 07:42:40.000000 tweeterpy-0.0.5/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 07:57:47.935358 tweeterpy-0.0.5/setup.cfg
+-rw-rw-rw-   0        0        0     1499 2023-06-28 07:55:23.000000 tweeterpy-0.0.5/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:57:47.908196 tweeterpy-0.0.5/tweeterpy/
+-rw-rw-rw-   0        0        0       34 2023-06-20 15:09:15.000000 tweeterpy-0.0.5/tweeterpy/__init__.py
+-rw-rw-rw-   0        0        0     2581 2023-06-20 09:49:11.000000 tweeterpy-0.0.5/tweeterpy/api_util.py
+-rw-rw-rw-   0        0        0      671 2023-06-25 06:51:11.000000 tweeterpy-0.0.5/tweeterpy/config.py
+-rw-rw-rw-   0        0        0     1980 2023-06-20 14:19:17.000000 tweeterpy-0.0.5/tweeterpy/constants.py
+-rw-rw-rw-   0        0        0     6654 2023-06-24 14:06:58.000000 tweeterpy-0.0.5/tweeterpy/login_util.py
+-rw-rw-rw-   0        0        0     1653 2023-06-20 07:35:05.000000 tweeterpy-0.0.5/tweeterpy/request_util.py
+-rw-rw-rw-   0        0        0     2278 2023-06-25 06:51:11.000000 tweeterpy-0.0.5/tweeterpy/session_util.py
+-rw-rw-rw-   0        0        0    22817 2023-06-25 07:23:32.000000 tweeterpy-0.0.5/tweeterpy/tweeterpy.py
+-rw-rw-rw-   0        0        0     3593 2023-06-28 07:54:04.000000 tweeterpy-0.0.5/tweeterpy/util.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:57:47.923821 tweeterpy-0.0.5/tweeterpy.egg-info/
+-rw-rw-rw-   0        0        0     3389 2023-06-28 07:57:47.000000 tweeterpy-0.0.5/tweeterpy.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      406 2023-06-28 07:57:47.000000 tweeterpy-0.0.5/tweeterpy.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 07:57:47.000000 tweeterpy-0.0.5/tweeterpy.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      221 2023-06-28 07:57:47.000000 tweeterpy-0.0.5/tweeterpy.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       10 2023-06-28 07:57:47.000000 tweeterpy-0.0.5/tweeterpy.egg-info/top_level.txt
```

### Comparing `tweeterpy-0.0.4/LICENSE` & `tweeterpy-0.0.5/LICENSE`

 * *Files identical despite different names*

### Comparing `tweeterpy-0.0.4/PKG-INFO` & `tweeterpy-0.0.5/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tweeterpy
-Version: 0.0.4
+Version: 0.0.5
 Summary: TweeterPy is a python library to extract data from Twitter. TweeterPy API lets you scrape data from a user's profile like username, userid, bio, followers/followings list, profile media, tweets, etc.
 Home-page: https://github.com/iSarabjitDhiman/TweeterPy
 Author: Sarabjit Dhiman
 Author-email: hello@sarabjitdhiman.com
 License: MIT
 Keywords: tweeterpy,twitter scraper,tweet scraper,twitter data extraction,twitter api,twitter python,tweet api,tweetpy
 Classifier: Development Status :: 3 - Alpha
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: tweeterpy Version: 0.0.4 Summary: TweeterPy is a
+Metadata-Version: 2.1 Name: tweeterpy Version: 0.0.5 Summary: TweeterPy is a
 python library to extract data from Twitter. TweeterPy API lets you scrape data
 from a user's profile like username, userid, bio, followers/followings list,
 profile media, tweets, etc. Home-page: https://github.com/iSarabjitDhiman/
 TweeterPy Author: Sarabjit Dhiman Author-email: hello@sarabjitdhiman.com
 License: MIT Keywords: tweeterpy,twitter scraper,tweet scraper,twitter data
 extraction,twitter api,twitter python,tweet api,tweetpy Classifier: Development
 Status :: 3 - Alpha Classifier: Intended Audience :: End Users/Desktop
```

### Comparing `tweeterpy-0.0.4/README.md` & `tweeterpy-0.0.5/README.md`

 * *Files identical despite different names*

### Comparing `tweeterpy-0.0.4/setup.py` & `tweeterpy-0.0.5/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from setuptools import setup
 
-VERSION = "0.0.4"
+VERSION = "0.0.5"
 SHORT_DESCRIPTION = "TweeterPy is a python library to extract data from Twitter. TweeterPy API lets you scrape data from a user's profile like username, userid, bio, followers/followings list, profile media, tweets, etc."
 
 with open("requirements.txt") as file:
     dependencies = file.read().splitlines()
 with open("README.md", "r") as file:
     DESCRIPTION = file.read()
```

### Comparing `tweeterpy-0.0.4/tweeterpy/api_util.py` & `tweeterpy-0.0.5/tweeterpy/api_util.py`

 * *Files identical despite different names*

### Comparing `tweeterpy-0.0.4/tweeterpy/config.py` & `tweeterpy-0.0.5/tweeterpy/config.py`

 * *Files identical despite different names*

### Comparing `tweeterpy-0.0.4/tweeterpy/constants.py` & `tweeterpy-0.0.5/tweeterpy/constants.py`

 * *Files identical despite different names*

### Comparing `tweeterpy-0.0.4/tweeterpy/login_util.py` & `tweeterpy-0.0.5/tweeterpy/login_util.py`

 * *Files identical despite different names*

### Comparing `tweeterpy-0.0.4/tweeterpy/request_util.py` & `tweeterpy-0.0.5/tweeterpy/request_util.py`

 * *Files identical despite different names*

### Comparing `tweeterpy-0.0.4/tweeterpy/session_util.py` & `tweeterpy-0.0.5/tweeterpy/session_util.py`

 * *Files identical despite different names*

### Comparing `tweeterpy-0.0.4/tweeterpy/tweeterpy.py` & `tweeterpy-0.0.5/tweeterpy/tweeterpy.py`

 * *Files identical despite different names*

### Comparing `tweeterpy-0.0.4/tweeterpy/util.py` & `tweeterpy-0.0.5/tweeterpy/util.py`

 * *Files 6% similar despite different names*

```diff
@@ -44,16 +44,16 @@
         if user_info_feautres:
             features.update(
                 {"subscriptions_verification_info_verified_since_enabled": True})
 
     if additional_features:
         features.update({"rweb_lists_timeline_redesign_enabled": True, "creator_subscriptions_tweet_preview_api_enabled": True, "tweetypie_unmention_optimization_enabled": True,
                          "responsive_web_edit_tweet_api_enabled": True, "graphql_is_translatable_rweb_tweet_is_translatable_enabled": True, "view_counts_everywhere_api_enabled": True,
-                         "longform_notetweets_consumption_enabled": True, "tweet_awards_web_tipping_enabled": False, "freedom_of_speech_not_reach_fetch_enabled": True,
-                         "standardized_nudges_misinfo": True, "tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled": False,
+                         "longform_notetweets_consumption_enabled": True, "responsive_web_twitter_article_tweet_consumption_enabled": False, "tweet_awards_web_tipping_enabled": False,
+                         "freedom_of_speech_not_reach_fetch_enabled": True, "standardized_nudges_misinfo": True, "tweet_with_visibility_results_prefer_gql_limited_actions_policy_enabled": False,
                          "longform_notetweets_rich_text_read_enabled": True, "longform_notetweets_inline_media_enabled": False, "responsive_web_enhance_cards_enabled": False})
 
     return features
 
 
 def generate_url(domain=None, url_path=None):
     if not domain and not url_path:
```

### Comparing `tweeterpy-0.0.4/tweeterpy.egg-info/PKG-INFO` & `tweeterpy-0.0.5/tweeterpy.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tweeterpy
-Version: 0.0.4
+Version: 0.0.5
 Summary: TweeterPy is a python library to extract data from Twitter. TweeterPy API lets you scrape data from a user's profile like username, userid, bio, followers/followings list, profile media, tweets, etc.
 Home-page: https://github.com/iSarabjitDhiman/TweeterPy
 Author: Sarabjit Dhiman
 Author-email: hello@sarabjitdhiman.com
 License: MIT
 Keywords: tweeterpy,twitter scraper,tweet scraper,twitter data extraction,twitter api,twitter python,tweet api,tweetpy
 Classifier: Development Status :: 3 - Alpha
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: tweeterpy Version: 0.0.4 Summary: TweeterPy is a
+Metadata-Version: 2.1 Name: tweeterpy Version: 0.0.5 Summary: TweeterPy is a
 python library to extract data from Twitter. TweeterPy API lets you scrape data
 from a user's profile like username, userid, bio, followers/followings list,
 profile media, tweets, etc. Home-page: https://github.com/iSarabjitDhiman/
 TweeterPy Author: Sarabjit Dhiman Author-email: hello@sarabjitdhiman.com
 License: MIT Keywords: tweeterpy,twitter scraper,tweet scraper,twitter data
 extraction,twitter api,twitter python,tweet api,tweetpy Classifier: Development
 Status :: 3 - Alpha Classifier: Intended Audience :: End Users/Desktop
```

