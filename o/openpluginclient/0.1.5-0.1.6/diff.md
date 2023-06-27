# Comparing `tmp/openpluginclient-0.1.5.tar.gz` & `tmp/openpluginclient-0.1.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "openpluginclient-0.1.5.tar", last modified: Tue Jun 27 17:56:53 2023, max compression
+gzip compressed data, was "openpluginclient-0.1.6.tar", last modified: Tue Jun 27 22:33:56 2023, max compression
```

## Comparing `openpluginclient-0.1.5.tar` & `openpluginclient-0.1.6.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 17:56:53.480650 openpluginclient-0.1.5/
--rw-r--r--   0 runner    (1001) docker     (123)      646 2023-06-27 17:56:53.480650 openpluginclient-0.1.5/PKG-INFO
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 17:56:53.480650 openpluginclient-0.1.5/openpluginclient/
--rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/openpluginclient/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2190 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/openpluginclient/openpluginclient.py
--rw-r--r--   0 runner    (1001) docker     (123)    18582 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/openpluginclient/plugins.json
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/openpluginclient/types.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 17:56:53.480650 openpluginclient-0.1.5/openpluginclient.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)      646 2023-06-27 17:56:53.000000 openpluginclient-0.1.5/openpluginclient.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      372 2023-06-27 17:56:53.000000 openpluginclient-0.1.5/openpluginclient.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 17:56:53.000000 openpluginclient-0.1.5/openpluginclient.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-27 17:56:53.000000 openpluginclient-0.1.5/openpluginclient.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-27 17:56:53.000000 openpluginclient-0.1.5/openpluginclient.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 17:56:53.480650 openpluginclient-0.1.5/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1207 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 17:56:53.480650 openpluginclient-0.1.5/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/tests/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1978 2023-06-27 17:56:43.000000 openpluginclient-0.1.5/tests/test_completion.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:33:56.037680 openpluginclient-0.1.6/
+-rw-r--r--   0 runner    (1001) docker     (123)      646 2023-06-27 22:33:56.033680 openpluginclient-0.1.6/PKG-INFO
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:33:56.033680 openpluginclient-0.1.6/openpluginclient/
+-rw-r--r--   0 runner    (1001) docker     (123)       51 2023-06-27 22:33:40.000000 openpluginclient-0.1.6/openpluginclient/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2190 2023-06-27 22:33:40.000000 openpluginclient-0.1.6/openpluginclient/openpluginclient.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17652 2023-06-27 22:33:40.000000 openpluginclient-0.1.6/openpluginclient/plugins.json
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 22:33:40.000000 openpluginclient-0.1.6/openpluginclient/types.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:33:56.033680 openpluginclient-0.1.6/openpluginclient.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      646 2023-06-27 22:33:55.000000 openpluginclient-0.1.6/openpluginclient.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      372 2023-06-27 22:33:55.000000 openpluginclient-0.1.6/openpluginclient.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 22:33:55.000000 openpluginclient-0.1.6/openpluginclient.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-27 22:33:55.000000 openpluginclient-0.1.6/openpluginclient.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       23 2023-06-27 22:33:55.000000 openpluginclient-0.1.6/openpluginclient.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 22:33:56.037680 openpluginclient-0.1.6/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1207 2023-06-27 22:33:40.000000 openpluginclient-0.1.6/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 22:33:56.033680 openpluginclient-0.1.6/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 22:33:40.000000 openpluginclient-0.1.6/tests/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1978 2023-06-27 22:33:40.000000 openpluginclient-0.1.6/tests/test_completion.py
```

### Comparing `openpluginclient-0.1.5/PKG-INFO` & `openpluginclient-0.1.6/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: openpluginclient
-Version: 0.1.5
+Version: 0.1.6
 Summary: Python package for accessing ChatGPT plugins via API
 Home-page: UNKNOWN
 Author: Sebastian Sosa
 Author-email: 1sebastian1sosa1@gmail.com
 License: UNKNOWN
 Description: Client for accessing ChatGPT plugins via OpenPlugin API
 Keywords: python,openai,chatgpt,chat,plugin
```

### Comparing `openpluginclient-0.1.5/openpluginclient/openpluginclient.py` & `openpluginclient-0.1.6/openpluginclient/openpluginclient.py`

 * *Files identical despite different names*

### Comparing `openpluginclient-0.1.5/openpluginclient/plugins.json` & `openpluginclient-0.1.6/openpluginclient/plugins.json`

 * *Files 1% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9429824561403509%*

 * *Differences: {"'currencyconverter'": "'https://currency-convert-chatgpt-plugin.vercel.app'",*

 * * "'repo_radar'": "'https://reporadar.computercomputer.computer'",*

 * * 'delete': "['ArtCollection', 'AskMarcie', 'Avalara', 'BOXIL_SaaS', 'Bohita', 'Broadway', "*

 * *           "'BubbleGoods', 'C3_Glide', 'ChatWithBible', 'ChatWithQuran', 'CheckTheChain', "*

 * *           "'Checkers', 'CloudDiagramGen', 'CryptoPrices', 'DAIZY', 'Diagrams', 'FreshTech', "*

 * *           "'game_info_fetcher']"}*

```diff
@@ -2,51 +2,34 @@
     "ABCmouse": "https://ai.abcmouse.com",
     "AMAZON_product_desc_generator": "https://turboooo.com",
     "Agones": "https://agones.gr",
     "Ai_PDF": "https://plugin-3c56b9d4c8a6465998395f28b6a445b2-jexkai4vea-uc.a.run.app",
     "Algorithma": "https://algorithma.ruvnet.repl.co",
     "ApexMap": "https://apex-map-plugin-d1u8.vercel.app",
     "AppyPieAIAppBuilder": "https://appypie.com",
-    "ArtCollection": "https://artcollection--chao-gu-ge-lei.repl.co",
     "AskCars": "https://askcars.ai",
-    "AskMarcie": "https://askmarcie-backend.herokuapp.com",
     "AskTheCode": "https://askthecode.dsomok.online",
     "Austrian_Bank_Rates": "https://banken-vergleich.net",
-    "Avalara": "https://plugins.midgard.avalara.io",
-    "BOXIL_SaaS": "https://boxil.jp",
     "Bardeen": "https://bardeen.ai",
-    "Bohita": "https://gptshop.bohita.com",
-    "Broadway": "https://www.broadway.com",
-    "BubbleGoods": "https://chatgpt.bubblegoods.com",
     "ByByAI": "https://byby.ai",
-    "C3_Glide": "https://c3glide-d9g5.boldstratus.com",
     "CTCP": "https://ctcp.japaneast.cloudapp.azure.com",
-    "ChatWithBible": "https://bible.religions.chat",
-    "ChatWithQuran": "https://quran.religions.chat",
-    "CheckTheChain": "https://www.nani.ooo",
-    "Checkers": "https://0a8e9b8e7f0912323de2d3653f1ea597.preview.pluginlab.ai",
-    "CloudDiagramGen": "https://ei6xvhnd3r.eu-west-1.awsapprunner.com",
     "Company_Transcripts": "https://transcripts.koyfin.com",
     "Coupert": "https://www.coupert.com",
     "CranePumpsManuals": "https://cpsconnect.cranepumps.com",
     "Creaticode_Extension_of_MIT_Scratch": "https://openai.creaticode.com",
     "CreatuityStores": "https://chatgpt.wild.creatuity.net",
     "CreditYelp": "https://credityelp.com",
     "CribbageScorer": "https://cribbage.azurewebsites.net",
-    "CryptoPrices": "https://data-api.cryptocompare.com",
-    "DAIZY": "https://plugin.daizy.com",
-    "Diagrams": "https://diagrams.herokuapp.com",
     "Dr_Thoths_Tarot": "https://dr-thoth-tarot.herokuapp.com",
     "DreamInterpreter": "https://dreamplugin.bgnetmobile.com",
     "DuoduoEnglish": "https://n4nbxo32xi.execute-api.ap-northeast-1.amazonaws.com",
     "EasyProductSearch": "https://easy-search.techno-gauss.com",
     "Etihad_Airline": "https://gpt-etihad.botim.me",
     "Ferryhopper": "https://openai.ferryhopper.com",
     "Figlet": "https://figletgptplugin.wisemonkey.repl.co",
-    "FreshTech": "https://6yq93jqsc3.execute-api.us-west-1.amazonaws.com",
     "GameSight": "https://openai.tapapis.com",
     "Gate2AI": "https://gate2ai.com",
     "GifApi": "https://chat-plugin-giphy.efficiency.tools",
     "Google_Ads_Shopping_Microsoft_Ads_pay_per_click": "https://www.storeya.com",
     "Horoscopes_by_Inner_Self": "https://innerself.ai",
     "ImageSearch": "https://imgser.aigenprompt.com",
     "IndoorPlants": "https://kirill.customgpt.ai",
@@ -174,15 +157,15 @@
     "create_qr_code": "https://create-qr-code.modelxy.com",
     "creativemind": "https://gpt-4dall-e.pranavbhatt402.repl.co",
     "cryptoPriceAndNews": "https://crypto-news.replit.app",
     "crypto_price_checker": "https://cryptoprices.smoothplugins.com",
     "cryptomation": "https://chat.cryptomation.com",
     "cryptopulse": "https://crypto-pulse-top.vercel.app",
     "currency_today": "https://today-currency-converter.oiconma.repl.co",
-    "currencyconverter": "https://currency-conversion--nerrosa.repl.co",
+    "currencyconverter": "https://currency-convert-chatgpt-plugin.vercel.app",
     "customplugin": "https://customplugin.customplugin.ai",
     "daigram": "https://daigr.am",
     "deepmemory": "https://apiv2.deepmemory.io",
     "defillama": "https://llamawrapper-prod.onrender.com",
     "dev": "https://dev.to",
     "dfa": "https://domainfinderai.com",
     "diceroller": "https://dmtoolkit.magejosh.repl.co",
@@ -207,15 +190,14 @@
     "findagift": "https://gift.pluginbuilders.repl.co",
     "finnabolag": "https://finna-bolag.fly.dev",
     "fiscalnote": "https://api.factba.se",
     "forex_gpt": "https://live.forex-gpt.ai",
     "form": "https://openai-plugin.yayforms.com",
     "formgenerator": "https://ai.forms.app",
     "fundsdbsearch": "https://fundsdbsearch.azurewebsites.net",
-    "game_info_fetcher": "https://api.gamebase.chat",
     "getyourguide_activity_search": "https://llmsearch.gygservice.com",
     "giftwrap": "https://api.giftwrap.ai",
     "gitUserRepoStats": "https://chat-gpt-github-stat-plugin.vercel.app",
     "gofynd": "https://www.gofynd.com",
     "golden_data_plugin": "https://chatgpt-plugin.prod.golden.dev",
     "got2go_plugin_v1": "https://got2go.com",
     "hackit_web_scanner": "https://hackit.co.il",
@@ -276,14 +258,15 @@
     "property_search": "https://propertysearch-5831-openai.langdock.com",
     "ptcg_price_research": "https://ai.toreris.com",
     "qreator": "https://letai.help",
     "questmate": "https://chatgpt-plugin.questmate.com",
     "recipe_retrieval": "https://api.tasty.co",
     "rephrase": "https://promptperfect.xyz",
     "repo_inspector": "https://repoinspector.onrender.com",
+    "repo_radar": "https://reporadar.computercomputer.computer",
     "resume": "https://easy-resume.net",
     "savvy_trader_ai": "https://savvytrader.com",
     "scholarai": "https://scholar-ai.net",
     "scholarly": "https://scholarly.maila.ai",
     "search": "https://gpt.plugin.procreator.in",
     "seo_assistant": "https://webfx.ai",
     "seoanalysis": "https://ai.seovendor.co",
```

### Comparing `openpluginclient-0.1.5/openpluginclient.egg-info/PKG-INFO` & `openpluginclient-0.1.6/openpluginclient.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: openpluginclient
-Version: 0.1.5
+Version: 0.1.6
 Summary: Python package for accessing ChatGPT plugins via API
 Home-page: UNKNOWN
 Author: Sebastian Sosa
 Author-email: 1sebastian1sosa1@gmail.com
 License: UNKNOWN
 Description: Client for accessing ChatGPT plugins via OpenPlugin API
 Keywords: python,openai,chatgpt,chat,plugin
```

### Comparing `openpluginclient-0.1.5/setup.py` & `openpluginclient-0.1.6/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 from setuptools import setup, find_packages
 
 # Setting up
 setup(
        # the name must match the folder name 'verysimplemodule'
         name='openpluginclient', 
-        version="0.1.5",
+        version="0.1.6",
         author="Sebastian Sosa",
         author_email="1sebastian1sosa1@gmail.com",
         description='Python package for accessing ChatGPT plugins via API',
         long_description='Client for accessing ChatGPT plugins via OpenPlugin API',
         packages=find_packages(),
         package_data={
             "openpluginclient": ["*.json"],  # include all .json files in the openplugin package
```

### Comparing `openpluginclient-0.1.5/tests/test_completion.py` & `openpluginclient-0.1.6/tests/test_completion.py`

 * *Files identical despite different names*

