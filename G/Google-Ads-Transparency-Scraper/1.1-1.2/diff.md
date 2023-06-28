# Comparing `tmp/Google Ads Transparency Scraper-1.1.tar.gz` & `tmp/Google Ads Transparency Scraper-1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "Google Ads Transparency Scraper-1.1.tar", last modified: Mon Jun 26 11:24:49 2023, max compression
+gzip compressed data, was "Google Ads Transparency Scraper-1.2.tar", last modified: Wed Jun 28 07:52:46 2023, max compression
```

## Comparing `Google Ads Transparency Scraper-1.1.tar` & `Google Ads Transparency Scraper-1.2.tar`

### file list

```diff
@@ -1,14 +1,15 @@
-drwxrwxrwx   0        0        0        0 2023-06-26 11:24:49.886142 Google Ads Transparency Scraper-1.1/
-drwxrwxrwx   0        0        0        0 2023-06-26 11:24:49.822079 Google Ads Transparency Scraper-1.1/GoogleAdsTransparency/
--rw-rw-rw-   0        0        0       48 2023-06-26 11:13:29.000000 Google Ads Transparency Scraper-1.1/GoogleAdsTransparency/__init__.py
--rw-rw-rw-   0        0        0     9845 2023-06-26 11:22:33.000000 Google Ads Transparency Scraper-1.1/GoogleAdsTransparency/main.py
-drwxrwxrwx   0        0        0        0 2023-06-26 11:24:49.886142 Google Ads Transparency Scraper-1.1/Google_Ads_Transparency_Scraper.egg-info/
--rw-rw-rw-   0        0        0      849 2023-06-26 11:24:49.000000 Google Ads Transparency Scraper-1.1/Google_Ads_Transparency_Scraper.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      366 2023-06-26 11:24:49.000000 Google Ads Transparency Scraper-1.1/Google_Ads_Transparency_Scraper.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-26 11:24:49.000000 Google Ads Transparency Scraper-1.1/Google_Ads_Transparency_Scraper.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       57 2023-06-26 11:24:49.000000 Google Ads Transparency Scraper-1.1/Google_Ads_Transparency_Scraper.egg-info/requires.txt
--rw-rw-rw-   0        0        0       22 2023-06-26 11:24:49.000000 Google Ads Transparency Scraper-1.1/Google_Ads_Transparency_Scraper.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      849 2023-06-26 11:24:49.890153 Google Ads Transparency Scraper-1.1/PKG-INFO
--rw-rw-rw-   0        0        0       29 2023-06-26 11:23:38.000000 Google Ads Transparency Scraper-1.1/README.md
--rw-rw-rw-   0        0        0       86 2023-06-26 11:24:49.892862 Google Ads Transparency Scraper-1.1/setup.cfg
--rw-rw-rw-   0        0        0     1243 2023-06-26 11:23:04.000000 Google Ads Transparency Scraper-1.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:52:46.454018 Google Ads Transparency Scraper-1.2/
+drwxrwxrwx   0        0        0        0 2023-06-28 07:52:46.445019 Google Ads Transparency Scraper-1.2/GoogleAdsTransparency/
+-rw-rw-rw-   0        0        0      106 2023-06-28 05:20:16.000000 Google Ads Transparency Scraper-1.2/GoogleAdsTransparency/__init__.py
+-rw-rw-rw-   0        0        0    10314 2023-06-28 07:22:06.000000 Google Ads Transparency Scraper-1.2/GoogleAdsTransparency/main.py
+-rw-rw-rw-   0        0        0    11448 2023-06-28 06:06:26.000000 Google Ads Transparency Scraper-1.2/GoogleAdsTransparency/regions.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:52:46.453020 Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/
+-rw-rw-rw-   0        0        0      855 2023-06-28 07:52:46.000000 Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      399 2023-06-28 07:52:46.000000 Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 07:52:46.000000 Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       69 2023-06-28 07:52:46.000000 Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       22 2023-06-28 07:52:46.000000 Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      855 2023-06-28 07:52:46.455020 Google Ads Transparency Scraper-1.2/PKG-INFO
+-rw-rw-rw-   0        0        0       29 2023-06-26 11:23:38.000000 Google Ads Transparency Scraper-1.2/README.md
+-rw-rw-rw-   0        0        0       86 2023-06-28 07:52:46.456020 Google Ads Transparency Scraper-1.2/setup.cfg
+-rw-rw-rw-   0        0        0     1273 2023-06-28 07:52:18.000000 Google Ads Transparency Scraper-1.2/setup.py
```

### Comparing `Google Ads Transparency Scraper-1.1/GoogleAdsTransparency/main.py` & `Google Ads Transparency Scraper-1.2/GoogleAdsTransparency/main.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 import datetime
 import requests
 from typing import Union
 from bs4 import BeautifulSoup as soap
+from regions import Regions
 
-headers = {
+HEADERS = {
     'authority': 'adstransparency.google.com',
     'accept': 'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7',
     'accept-language': 'en-US,en;q=0.9',
     'sec-ch-ua': '"Not.A/Brand";v="8", "Chromium";v="114", "Google Chrome";v="114"',
     'sec-ch-ua-arch': '"x86"',
     'sec-ch-ua-bitness': '"64"',
     'sec-ch-ua-full-version-list': '"Not.A/Brand";v="8.0.0.0", "Chromium";v="114.0.5735.134", "Google Chrome";v="114.0.5735.134"',
@@ -20,175 +21,178 @@
     'sec-fetch-mode': 'navigate',
     'sec-fetch-site': 'none',
     'sec-fetch-user': '?1',
     'upgrade-insecure-requests': '1',
     'user-agent': 'Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/114.0.0.0 Safari/537.36',
 }
 
+def show_regions_list():
+    """Displays Supported Regions Name along with their Region Codes"""
+    print("Regions List")
+    for region_code in Regions.keys():
+        print(f"Region Name: {Regions[region_code]['Region']}\tRegion Code: {region_code}")
+
 class GoogleAds:
-    def __init__(self,  headers):
+    def __init__(self, region="anywhere"):
         self.reqs = requests.Session()
-        self.headers = headers
+        self.headers = HEADERS
+        self.r_check = True
+        if region == "anywhere":
+            self.r_check = False
+        if not Regions.get(region) and not self.r_check:
+            raise Exception("Invalid Region Code")
+        self.region = region
+        self.region_num = Regions[region]["1"] if self.r_check else 0
         self.get_cookies()
 
     def get_cookies(self):
         """Get Cookies from the main url https://adstransparency.google.com/ and store them in requests Session"""
         params = {
-            'region': 'anywhere',
+            'region': self.region,
         }
-        self.reqs.get('https://adstransparency.google.com/', params=params, headers=headers)#.text.replace("\/","")
+        self.reqs.get('https://adstransparency.google.com/', params=params, headers=self.headers)#.text.replace("\/","")
         #response = str(response[response.find("tfaaReportAppInfo"):]).encode('utf8').decode('unicode_escape')
         #print(json.loads(response[response.find("["):response.find(']')+1]))
 
     def refresh_session(self):
         """Refresh Session cookies"""
         self.reqs = requests.Session()
         self.get_cookies()
 
-    def get_all_search_suggestions(self, keyword: str) -> list :
+    def get_all_search_suggestions(self, keyword: str) -> list:
         """
             Gets All suggestions from the Google Ads Transparency for given keyword.
             Returns list of Suggestions along with their details
             Returns Empty list [] if no suggestion found"""
         data = {
-            'f.req': '{"1":"' + keyword + '","2":10,"3":10}',
-        }
+                'f.req': '{"1":"' + keyword + '","2":10,"3":10}',
+                }            
         response = self.reqs.post(
             'https://adstransparency.google.com/anji/_/rpc/SearchService/SearchSuggestions',
             params={'authuser': '0'},
             data=data,
         )
-        suggestions = response.json()["1"]
-        if suggestions:    
-            return suggestions
-        return []
+        return suggestions if (suggestions := response.json()["1"]) else []
 
     def get_first_search_suggestion(self, keyword: str) -> Union[dict,None]:
         """
            Gets First Suggestions from the Google Ads Transparency for given keyword.
            Returns dict of Suggestion details
            Returns None if no suggestion found"""
         
         if suggestions := self.get_all_search_suggestions(keyword):
             return suggestions[0]
         return None
 
-    def get_advistisor_by_domain(self, domain: str)-> Union[dict,None]:
+    def get_advistisor_by_domain(self, domain: str) -> Union[dict,None]:
         """
             Makes search of domain/url and returns the Company Name and It's Advertisor Id 
         """
         data = {
             "f.req": '{"2":40,"3":{"12":{"1":"' + domain + '"}}}'
         }
         response = self.reqs.post(
             'https://adstransparency.google.com/anji/_/rpc/SearchService/SearchCreatives',
             params={'authuser': ''},
             data=data,
         )
-        response = response.json().get("1")
-        if response:
+        if response := response.json().get("1"):
             ad = response[0]
             return {"Advertisor Id": ad["1"], "Name":ad["12"]}
         return None
-        """if ads := response.json().get("1"):
-            with open("new.json", "w") as f:
-                json.dump(ads, f)
-            return [{"Advertisor Id": ad[1],"Creative Id":ad["2"]} for ad in ads]
-        return []"""
+        #if ads := response.json().get("1"):
+        #    with open("new.json", "w") as f:
+        #        json.dump(ads, f)
+        #    return [{"Advertisor Id": ad[1],"Creative Id":ad["2"]} for ad in ads]
+        #return []
 
-    def creative_search_by_advertiser_id(self, advertiser_id: str) -> list: #TODO do region search
+    def creative_search_by_advertiser_id(self, advertiser_id: str) -> list:    #TODO do region search
         """Get Creatives or ads by quering given Advertisor Id
         If no Ad found return []"""
         data = {
             'f.req': '{"2":40,"3":{"12":{"1":"","2":true},"13":{"1":["' + advertiser_id + '"]}}, "7":{"1":1}}',
         }
+        if self.r_check:
+            data = {
+            'f.req': '{"2":40,"3":{"8":[' + str(self.region_num) + '],"12":{"1":"","2":true},"13":{"1":["' + advertiser_id + '"]}}, "7":{"1":1}}',
+        }
         response = self.reqs.post(
             'https://adstransparency.google.com/anji/_/rpc/SearchService/SearchCreatives',
             params={'authuser': ''},
             data=data,
         )
-        if ads := response.json().get("1"):
-            return [ad["2"] for ad in ads]
-        return []
+        return [ad["2"] for ad in ads] if (ads := response.json().get("1")) else []
 
     def get_creative_Ids(self, keyword: str) -> dict:
         """Makes search for given keyword and gets the first Suggestion. Then gets the Creatives for that.
         Returns Advertisor Name, Id, Ad count and List of Creatives"""
-        if search := self.get_first_search_suggestion(keyword):
-            print(search)
-
-            if search.get("2"): 
-                if advertisor := self.get_advistisor_by_domain(domain=search["2"]["1"]):
-                    suggestions = self.get_all_search_suggestions(advertisor["Name"])
-                    search = next((suggestion for suggestion in suggestions if suggestion["1"]["1"] == advertisor["Name"] and suggestion["1"]["2"] == advertisor["Advertisor Id"]), None)
-                else:
-                    return {"Advertisor": "", "Advertisor Id":"", "Ad Count": 0, "Creatives": []}
-            advertisor = search["1"]["1"]
-            Ad_count = search['1']['4']['2']['2'] if search["1"].get("4") else 0
-            if Ad_count:
-                return {"Advertisor": advertisor, "Advertisor Id": search["1"]["2"], "Ad Count": Ad_count, "Creative_Ids": self.creative_search_by_advertiser_id(advertiser_id=search["1"]["2"])}
-            return {"Advertisor": advertisor, "Advertisor Id":search["1"]["2"], "Ad Count": Ad_count, "Creative_Ids": []}
-        return {"Advertisor": "", "Advertisor Id":"", "Ad Count": 0, "Creatives": []}
+        if not (search := self.get_first_search_suggestion(keyword)):
+            return {"Advertisor": "", "Advertisor Id":"", "Ad Count": 0, "Creatives": []}
+        print(search)
+
+        if search.get("2"): 
+            if not (advertisor := self.get_advistisor_by_domain(domain=search["2"]["1"])):
+                return {"Advertisor": "", "Advertisor Id":"", "Ad Count": 0, "Creatives": []}
+            suggestions = self.get_all_search_suggestions(advertisor["Name"])
+            search = next((suggestion for suggestion in suggestions if suggestion["1"]["1"] == advertisor["Name"] and suggestion["1"]["2"] == advertisor["Advertisor Id"]), None)
+        advertisor = search["1"]["1"]
+        Ad_count = search['1']['4']['2']['2'] if search["1"].get("4") else 0
+        if Ad_count:
+            return {"Advertisor": advertisor, "Advertisor Id": search["1"]["2"], "Ad Count": Ad_count, "Creative_Ids": self.creative_search_by_advertiser_id(advertiser_id=search["1"]["2"])}
+        return {"Advertisor": advertisor, "Advertisor Id":search["1"]["2"], "Ad Count": Ad_count, "Creative_Ids": []}
 
     def get_link_to_video(self, link: str) -> str:
         """Get the JS response from the link given and parse the Video/Image Link. Returns input Link if any error occurs"""
         response = requests.post(link)
         try:
             txt = next((x for x in response.text.split("CDATA[") if "googlevideo.com" in x))
             x = str(txt.split("]")[0]).encode("utf-8").decode("unicode_escape")
             return x.encode("utf-8").decode("unicode_escape")
-        except:
+        except Exception:
             return link
 
-    def get_breif_ads(self, advertisor_id: str, creative_id: str) -> dict: # TODO do region search
+    def get_breif_ads(self, advertisor_id: str, creative_id: str) -> dict:    # TODO do region search
         """Takes the Advertisor Id and Creative ID and returns the breif details of that particular Ad"""
         data = {
             'f.req': '{"1":"' + advertisor_id + '","2":"' + creative_id + '","5":{"1":1}}',
         }
         response = self.reqs.post(
             'https://adstransparency.google.com/anji/_/rpc/LookupService/GetCreativeById',
             params={'authuser': '0'},
             data=data,
         )
         response = response.json()["1"]
         format_int = response["8"]
-        format = "Text" if format_int == 1 else "Image" if format_int == 2 else "Video"
-        if format == "Video":
-            try:
-                link = response["5"][0]["2"]["4"]  
-            except:
-                link = response["5"][0]["1"]["4"]
-            if "displayads" in link:
-                link = self.get_link_to_video(link)
-        else:
-            try:
-                link = response["5"][0]["3"]["2"].split("'")[1]  
-            except:
-                link = response["5"][0]["1"]["4"]
-            if "displayads" in link:
-                link = self.get_link_to_video(link)
-
+        format_ = "Text" if format_int == 1 else "Image" if format_int == 2 else "Video"
+        try:
+            if format_ == "Video":
+                link = response["5"][0]["2"]["4"]
+            else:
+                link = response["5"][0]["3"]["2"].split("'")[1]
+        except Exception:
+            link = response["5"][0]["1"]["4"]
+        if "displayads" in link:
+            link = self.get_link_to_video(link)
         date = datetime.datetime.fromtimestamp(int(response["4"]["1"])).strftime('%Y-%m-%d')
         return {"Adverisor Id" : advertisor_id,  # TODO Add Country
                 "Creative Id" : creative_id,
-                "Ad Format": format,
+                "Ad Format": format_,
                 "Last Shown" : date,
                 "Ad Link" : link}
     
     def parse_ad_link(self, html: str) -> dict:
         """Parse the Ad Body and Ad title from the html"""
         page = soap(html, 'lxml')
         try:
             ad_body = page.find("div", {"data-highlight-id-inside":"36"}).text
-        except:
+        except Exception:
             ad_body = ""
-            #ad_body = page.find_all("div", recursive=False)[0].text
-        try: 
+        try:
             ad_title = page.find("div", {"aria-level":"3"}).text
-        except:
+        except Exception:
             ad_title = ""
         return {"Ad Body":ad_body, "Ad Title": ad_title}
 
     def get_detailed_ad(self, advertisor_id: str, creative_id: str) -> dict:
         """Takes the Advertisor Id and Creative ID and returns the details of that particular Ad"""
         ad_detail = self.get_breif_ads(advertisor_id, creative_id)
         response = self.reqs.get(
@@ -200,15 +204,15 @@
         elif ad_detail["Ad Format"] == "Image":
             ad_detail["Image URL"] = ad_detail["Ad Link"]
         else:
             ad_detail["Video URL"] = ad_detail["Ad Link"]
         return ad_detail
 
 if __name__ == '__main__':
-    a = GoogleAds(headers)
+    a = GoogleAds()
     keyword = "ibbedesign"
     keyword = "facebook"
     creatives = a.get_creative_Ids(keyword)
     if creatives["Ad Count"]:
         advertisor_id = creatives["Advertisor Id"]
         for creative_id in creatives["Creative_Ids"]:
             #print(a.get_breif_ads(advertisor_id, creative_id))
```

### Comparing `Google Ads Transparency Scraper-1.1/Google_Ads_Transparency_Scraper.egg-info/PKG-INFO` & `Google Ads Transparency Scraper-1.2/Google_Ads_Transparency_Scraper.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,17 +1,17 @@
 Metadata-Version: 2.1
 Name: Google-Ads-Transparency-Scraper
-Version: 1.1
+Version: 1.2
 Summary: A scraper for getting Ads from Google Transparency
 Home-page: https://github.com/faniAhmed/GoogleAdsTransparencyScraper
-Download-URL: https://github.com/faniAhmed/GoogleAdsTransparencyScraper/archive/refs/tags/v0.1.tar.gz
+Download-URL: https://github.com/faniAhmed/GoogleAdsTransparencyScraper/archive/refs/tags/v1.2.tar.gz
 Author: Farhan Ahmed
 Author-email: jattfarhan10@gmail.com
 License: Securely Incorporation
-Keywords: Google,Trends,Scraper,API,Google Ads,Ads,Google Transparency,Google Transparency Scraper,Google Ads Scrapre
+Keywords: Google,Transparency,Scraper,API,Google Ads,Ads,Google Transparency,Google Transparency Scraper,Google Ads Scrapre
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Intended Audience :: Developers
 Classifier: License :: Free for non-commercial use
 Classifier: Natural Language :: Urdu
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3.9
```

### Comparing `Google Ads Transparency Scraper-1.1/PKG-INFO` & `Google Ads Transparency Scraper-1.2/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,17 +1,17 @@
 Metadata-Version: 2.1
 Name: Google Ads Transparency Scraper
-Version: 1.1
+Version: 1.2
 Summary: A scraper for getting Ads from Google Transparency
 Home-page: https://github.com/faniAhmed/GoogleAdsTransparencyScraper
-Download-URL: https://github.com/faniAhmed/GoogleAdsTransparencyScraper/archive/refs/tags/v0.1.tar.gz
+Download-URL: https://github.com/faniAhmed/GoogleAdsTransparencyScraper/archive/refs/tags/v1.2.tar.gz
 Author: Farhan Ahmed
 Author-email: jattfarhan10@gmail.com
 License: Securely Incorporation
-Keywords: Google,Trends,Scraper,API,Google Ads,Ads,Google Transparency,Google Transparency Scraper,Google Ads Scrapre
+Keywords: Google,Transparency,Scraper,API,Google Ads,Ads,Google Transparency,Google Transparency Scraper,Google Ads Scrapre
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Intended Audience :: Developers
 Classifier: License :: Free for non-commercial use
 Classifier: Natural Language :: Urdu
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3.9
```

### Comparing `Google Ads Transparency Scraper-1.1/setup.py` & `Google Ads Transparency Scraper-1.2/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -3,23 +3,24 @@
 
 setup(
     name="Google Ads Transparency Scraper",
     author="Farhan Ahmed",
     author_email="jattfarhan10@gmail.com",
     url="https://github.com/faniAhmed/GoogleAdsTransparencyScraper",
     description="A scraper for getting Ads from Google Transparency",
-    version="1.1",
+    version="1.2",
     packages=find_packages(where=".", exclude=["tests"]),
-    download_url= 'https://github.com/faniAhmed/GoogleAdsTransparencyScraper/archive/refs/tags/v0.1.tar.gz',
-    keywords= ['Google', 'Trends', 'Scraper', 'API', 'Google Ads', 'Ads', 'Google Transparency', 'Google Transparency Scraper', 'Google Ads Scrapre'],
+    download_url= 'https://github.com/faniAhmed/GoogleAdsTransparencyScraper/archive/refs/tags/v1.2.tar.gz',
+    keywords= ['Google', 'Transparency', 'Scraper', 'API', 'Google Ads', 'Ads', 'Google Transparency', 'Google Transparency Scraper', 'Google Ads Scrapre'],
     license='Securely Incorporation',
     install_requires=[
         "setuptools>=45.0",
         "beautifulsoup4>=4.12.2",
         "Requests>=2.31.0",
+        "lxml>=4.6.3",
     ],
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Environment :: Console",
         "Intended Audience :: Developers",
         "License :: Free for non-commercial use",
         "Natural Language :: Urdu",
```

