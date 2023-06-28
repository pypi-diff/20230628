# Comparing `tmp/jellyash-0.4.1.tar.gz` & `tmp/jellyash-0.5.0.tar.gz`

## Comparing `jellyash-0.4.1.tar` & `jellyash-0.5.0.tar`

### file list

```diff
@@ -1,46 +1,47 @@
--rw-r--r--   0        0        0      405 2020-02-02 00:00:00.000000 jellyash-0.4.1/tox.ini
--rw-r--r--   0        0        0     2106 2020-02-02 00:00:00.000000 jellyash-0.4.1/.github/workflows/ci.yml
--rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 jellyash-0.4.1/jellyash/__init__.py
--rw-r--r--   0        0        0     1448 2020-02-02 00:00:00.000000 jellyash-0.4.1/jellyash/bundle.py
--rw-r--r--   0        0        0     1735 2020-02-02 00:00:00.000000 jellyash-0.4.1/jellyash/client.py
--rw-r--r--   0        0        0      894 2020-02-02 00:00:00.000000 jellyash-0.4.1/jellyash/duration.py
--rw-r--r--   0        0        0      557 2020-02-02 00:00:00.000000 jellyash-0.4.1/jellyash/nextup.py
--rw-r--r--   0        0        0      494 2020-02-02 00:00:00.000000 jellyash-0.4.1/jellyash/search.py
--rw-r--r--   0        0        0      906 2020-02-02 00:00:00.000000 jellyash-0.4.1/jellyash/token.py
--rw-r--r--   0        0        0     1446 2020-02-02 00:00:00.000000 jellyash-0.4.1/jellyash/unwatched.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/__init__.py
--rw-r--r--   0        0        0      776 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/conftest.py
--rw-r--r--   0        0        0     2372 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/test_bundle.py
--rw-r--r--   0        0        0     4981 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/test_client.py
--rw-r--r--   0        0        0     1245 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/test_duration.py
--rw-r--r--   0        0        0     1688 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/test_nextup.py
--rw-r--r--   0        0        0     1951 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/test_search.py
--rw-r--r--   0        0        0     1442 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/test_token.py
--rw-r--r--   0        0        0     2448 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/test_unwatched.py
--rw-r--r--   0        0        0     7508 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_bundle/TestApiResponse.client.yaml
--rw-r--r--   0        0        0     5106 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_bundle/TestApiResponse.setUp.yaml
--rw-r--r--   0        0        0     7600 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_bundle/TestUnwrappedApiResponse.client.yaml
--rw-r--r--   0        0        0     1511 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_bundle/TestUnwrappedApiResponse.test_unwrapped_response.yaml
--rw-r--r--   0        0        0     7498 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_client/TestAuthedClient.client.yaml
--rw-r--r--   0        0        0     3421 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_client/TestAuthedClient.test_authed_client.yaml
--rw-r--r--   0        0        0     2661 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_client/TestAuthedClient.test_authed_client_offline.yaml
--rw-r--r--   0        0        0     7258 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_client/TestClient.test_auth_with_password.yaml
--rw-r--r--   0        0        0     7458 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_duration/TestDuration.client.yaml
--rw-r--r--   0        0        0     9732 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_duration/TestDuration.test_calculate_duration.yaml
--rw-r--r--   0        0        0     1399 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_duration/TestDuration.test_calculate_duration_not_found.yaml
--rw-r--r--   0        0        0     7478 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_nextup/TestEpisodeStr.client.yaml
--rw-r--r--   0        0        0     3557 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_nextup/TestEpisodeStr.test_episode_str.yaml
--rw-r--r--   0        0        0     2117 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_search/TestSearch.test_multiple_terms_exact.yaml
--rw-r--r--   0        0        0     3008 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_search/TestSearch.test_multiple_terms_not_exact.yaml
--rw-r--r--   0        0        0     1098 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_search/TestSearch.test_single_term.yaml
--rw-r--r--   0        0        0       53 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_search/TestSearch.test_term_not_found.yaml
--rw-r--r--   0        0        0     7407 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_token/TestCreateJellyfinToken.test_create_token.yaml
--rw-r--r--   0        0        0     7469 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_unwatched/TestUnwatched.client.yaml
--rw-r--r--   0        0        0     2379 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_unwatched/TestUnwatched.test_all_unwatched.yaml
--rw-r--r--   0        0        0     5683 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_unwatched/TestUnwatched.test_specific_unwatched.yaml
--rw-r--r--   0        0        0     1401 2020-02-02 00:00:00.000000 jellyash-0.4.1/tests/cassettes/test_unwatched/TestUnwatched.test_specific_unwatched_not_found.yaml
--rw-r--r--   0        0        0       41 2020-02-02 00:00:00.000000 jellyash-0.4.1/.gitignore
--rw-r--r--   0        0        0     1080 2020-02-02 00:00:00.000000 jellyash-0.4.1/LICENSE
--rw-r--r--   0        0        0     1194 2020-02-02 00:00:00.000000 jellyash-0.4.1/README.md
--rw-r--r--   0        0        0      603 2020-02-02 00:00:00.000000 jellyash-0.4.1/pyproject.toml
--rw-r--r--   0        0        0     2584 2020-02-02 00:00:00.000000 jellyash-0.4.1/PKG-INFO
+-rw-r--r--   0        0        0      388 2020-02-02 00:00:00.000000 jellyash-0.5.0/tox.ini
+-rw-r--r--   0        0        0     2099 2020-02-02 00:00:00.000000 jellyash-0.5.0/.github/workflows/ci.yml
+-rw-r--r--   0        0        0       22 2020-02-02 00:00:00.000000 jellyash-0.5.0/jellyash/__init__.py
+-rw-r--r--   0        0        0     1448 2020-02-02 00:00:00.000000 jellyash-0.5.0/jellyash/bundle.py
+-rw-r--r--   0        0        0      223 2020-02-02 00:00:00.000000 jellyash-0.5.0/jellyash/cli.py
+-rw-r--r--   0        0        0     1735 2020-02-02 00:00:00.000000 jellyash-0.5.0/jellyash/client.py
+-rw-r--r--   0        0        0      903 2020-02-02 00:00:00.000000 jellyash-0.5.0/jellyash/duration.py
+-rw-r--r--   0        0        0      565 2020-02-02 00:00:00.000000 jellyash-0.5.0/jellyash/nextup.py
+-rw-r--r--   0        0        0      494 2020-02-02 00:00:00.000000 jellyash-0.5.0/jellyash/search.py
+-rw-r--r--   0        0        0      915 2020-02-02 00:00:00.000000 jellyash-0.5.0/jellyash/token.py
+-rw-r--r--   0        0        0     1444 2020-02-02 00:00:00.000000 jellyash-0.5.0/jellyash/unwatched.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/__init__.py
+-rw-r--r--   0        0        0      776 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/conftest.py
+-rw-r--r--   0        0        0     2372 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/test_bundle.py
+-rw-r--r--   0        0        0     4981 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/test_client.py
+-rw-r--r--   0        0        0     1245 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/test_duration.py
+-rw-r--r--   0        0        0     1688 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/test_nextup.py
+-rw-r--r--   0        0        0     1951 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/test_search.py
+-rw-r--r--   0        0        0     1442 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/test_token.py
+-rw-r--r--   0        0        0     2448 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/test_unwatched.py
+-rw-r--r--   0        0        0     7508 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_bundle/TestApiResponse.client.yaml
+-rw-r--r--   0        0        0     5106 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_bundle/TestApiResponse.setUp.yaml
+-rw-r--r--   0        0        0     7600 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_bundle/TestUnwrappedApiResponse.client.yaml
+-rw-r--r--   0        0        0     1511 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_bundle/TestUnwrappedApiResponse.test_unwrapped_response.yaml
+-rw-r--r--   0        0        0     7498 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_client/TestAuthedClient.client.yaml
+-rw-r--r--   0        0        0     3421 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_client/TestAuthedClient.test_authed_client.yaml
+-rw-r--r--   0        0        0     2661 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_client/TestAuthedClient.test_authed_client_offline.yaml
+-rw-r--r--   0        0        0     7258 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_client/TestClient.test_auth_with_password.yaml
+-rw-r--r--   0        0        0     7458 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_duration/TestDuration.client.yaml
+-rw-r--r--   0        0        0     9732 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_duration/TestDuration.test_calculate_duration.yaml
+-rw-r--r--   0        0        0     1399 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_duration/TestDuration.test_calculate_duration_not_found.yaml
+-rw-r--r--   0        0        0     7478 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_nextup/TestEpisodeStr.client.yaml
+-rw-r--r--   0        0        0     3557 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_nextup/TestEpisodeStr.test_episode_str.yaml
+-rw-r--r--   0        0        0     2117 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_search/TestSearch.test_multiple_terms_exact.yaml
+-rw-r--r--   0        0        0     3008 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_search/TestSearch.test_multiple_terms_not_exact.yaml
+-rw-r--r--   0        0        0     1098 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_search/TestSearch.test_single_term.yaml
+-rw-r--r--   0        0        0       53 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_search/TestSearch.test_term_not_found.yaml
+-rw-r--r--   0        0        0     7407 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_token/TestCreateJellyfinToken.test_create_token.yaml
+-rw-r--r--   0        0        0     7469 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_unwatched/TestUnwatched.client.yaml
+-rw-r--r--   0        0        0     2379 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_unwatched/TestUnwatched.test_all_unwatched.yaml
+-rw-r--r--   0        0        0     5683 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_unwatched/TestUnwatched.test_specific_unwatched.yaml
+-rw-r--r--   0        0        0     1401 2020-02-02 00:00:00.000000 jellyash-0.5.0/tests/cassettes/test_unwatched/TestUnwatched.test_specific_unwatched_not_found.yaml
+-rw-r--r--   0        0        0       41 2020-02-02 00:00:00.000000 jellyash-0.5.0/.gitignore
+-rw-r--r--   0        0        0     1080 2020-02-02 00:00:00.000000 jellyash-0.5.0/LICENSE
+-rw-r--r--   0        0        0     1194 2020-02-02 00:00:00.000000 jellyash-0.5.0/README.md
+-rw-r--r--   0        0        0      672 2020-02-02 00:00:00.000000 jellyash-0.5.0/pyproject.toml
+-rw-r--r--   0        0        0     2647 2020-02-02 00:00:00.000000 jellyash-0.5.0/PKG-INFO
```

### Comparing `jellyash-0.4.1/.github/workflows/ci.yml` & `jellyash-0.5.0/.github/workflows/ci.yml`

 * *Files 0% similar despite different names*

```diff
@@ -5,15 +5,15 @@
   pull_request:
 jobs:
   test:
     runs-on: ubuntu-latest
     name: Test (Python ${{ matrix.python-version }})
     strategy:
       matrix:
-        python-version: ["3.7", "3.8", "3.9", "3.10", "3.11"]
+        python-version: ["3.8", "3.9", "3.10", "3.11"]
     steps:
       - uses: actions/checkout@v3
       - name: Set up Python
         uses: actions/setup-python@v4
         with:
           python-version: "${{ matrix.python-version }}"
       - name: Install tox
```

### Comparing `jellyash-0.4.1/jellyash/bundle.py` & `jellyash-0.5.0/jellyash/bundle.py`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/jellyash/client.py` & `jellyash-0.5.0/jellyash/client.py`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/jellyash/duration.py` & `jellyash-0.5.0/jellyash/duration.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
-import argparse
 from decimal import Decimal
 
+from .cli import argparse_parser
 from .client import authed_client
 from .search import search_single_show
 
 
 def calculate_duration(client, show: str) -> str:
     try:
         show = search_single_show(client, show)
@@ -17,12 +17,12 @@
         episodes = client.jellyfin.get_season(show.Id, season.Id)
         duration += sum([e.RunTimeTicks for e in episodes])
     average = (duration / count) / int(Decimal("6E+008"))
     return f"Average duration over {count} episodes: {average:.1f} minutes"
 
 
 def average_duration() -> None:
-    parser = argparse.ArgumentParser()
+    parser = argparse_parser()
     parser.add_argument("show", nargs="+")
     args = parser.parse_args()
     client = authed_client()
     print(calculate_duration(client, " ".join(args.show)))
```

### Comparing `jellyash-0.4.1/jellyash/nextup.py` & `jellyash-0.5.0/jellyash/nextup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,18 +1,17 @@
-import argparse
-
 from .bundle import Item
+from .cli import argparse_parser
 from .client import authed_client
 
 
 def episode_str(episode: Item) -> str:
     seasonindex = f"{episode.ParentIndexNumber}x{episode.IndexNumber:0>2}"
     return f"{episode.SeriesName} [{seasonindex}] {episode.Name}"
 
 
 def nextup() -> None:
     client = authed_client()
-    parser = argparse.ArgumentParser()
+    parser = argparse_parser()
     parser.add_argument("-l", "--limit", dest="limit", type=int, default=30)
     args = parser.parse_args()
     for episode in client.jellyfin.get_next(limit=args.limit):
         print(episode_str(episode))
```

### Comparing `jellyash-0.4.1/jellyash/token.py` & `jellyash-0.5.0/jellyash/token.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,18 +1,18 @@
-import argparse
 import json
 from getpass import getpass as getpassword
 from getpass import getuser
 
+from .cli import argparse_parser
 from .client import CREDENTIALS_FILE, auth_with_password, create_client
 
 
 def create_jellyfin_token() -> None:
     client = create_client("create_jellyfin_token")
-    parser = argparse.ArgumentParser()
+    parser = argparse_parser()
     parser.add_argument("-u", "--user", dest="user", default=getuser())
     parser.add_argument(
         "server", nargs="?", default="https://jellyfin.wedontsleep.org/"
     )
     args = parser.parse_args()
     password = getpassword()
     result = auth_with_password(client, args.server, args.user, password)
```

### Comparing `jellyash-0.4.1/jellyash/unwatched.py` & `jellyash-0.5.0/jellyash/unwatched.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,33 +1,32 @@
-import argparse
 from operator import attrgetter
 
+from .cli import argparse_parser
 from .client import authed_client
 from .search import search_single_show
 
 
 def unwatched() -> None:
     client = authed_client()
-    parser = argparse.ArgumentParser()
+    parser = argparse_parser()
     parser.add_argument("show", nargs="*")
     args = parser.parse_args()
     if not args.show:
         all_unwatched(client)
     else:
         specific_unwatched(client, " ".join(args.show))
 
 
 def all_unwatched(client) -> None:
     r = client.jellyfin.search_media_items(
         term="", media="Series", limit=300
     )
     total = 0
     for series in sorted(r, key=attrgetter("Name")):
-        count = series.UserData.UnplayedItemCount
-        if count > 0:
+        if (count := series.UserData.UnplayedItemCount) > 0:
             ending = "s" if count != 1 else ""
             print(f"{series.Name}: {count} unwatched episode{ending}")
             total += count
     ending = "s" if total != 1 else ""
     print(f"Total: {total} unwatched episode{ending}")
```

### Comparing `jellyash-0.4.1/tests/conftest.py` & `jellyash-0.5.0/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/test_bundle.py` & `jellyash-0.5.0/tests/test_bundle.py`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/test_client.py` & `jellyash-0.5.0/tests/test_client.py`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/test_duration.py` & `jellyash-0.5.0/tests/test_duration.py`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/test_nextup.py` & `jellyash-0.5.0/tests/test_nextup.py`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/test_search.py` & `jellyash-0.5.0/tests/test_search.py`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/test_token.py` & `jellyash-0.5.0/tests/test_token.py`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/test_unwatched.py` & `jellyash-0.5.0/tests/test_unwatched.py`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_bundle/TestApiResponse.client.yaml` & `jellyash-0.5.0/tests/cassettes/test_bundle/TestApiResponse.client.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_bundle/TestApiResponse.setUp.yaml` & `jellyash-0.5.0/tests/cassettes/test_bundle/TestApiResponse.setUp.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_bundle/TestUnwrappedApiResponse.client.yaml` & `jellyash-0.5.0/tests/cassettes/test_bundle/TestUnwrappedApiResponse.client.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_bundle/TestUnwrappedApiResponse.test_unwrapped_response.yaml` & `jellyash-0.5.0/tests/cassettes/test_bundle/TestUnwrappedApiResponse.test_unwrapped_response.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_client/TestAuthedClient.client.yaml` & `jellyash-0.5.0/tests/cassettes/test_client/TestAuthedClient.client.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_client/TestAuthedClient.test_authed_client.yaml` & `jellyash-0.5.0/tests/cassettes/test_client/TestAuthedClient.test_authed_client.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_client/TestAuthedClient.test_authed_client_offline.yaml` & `jellyash-0.5.0/tests/cassettes/test_client/TestAuthedClient.test_authed_client_offline.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_client/TestClient.test_auth_with_password.yaml` & `jellyash-0.5.0/tests/cassettes/test_client/TestClient.test_auth_with_password.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_duration/TestDuration.client.yaml` & `jellyash-0.5.0/tests/cassettes/test_duration/TestDuration.client.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_duration/TestDuration.test_calculate_duration.yaml` & `jellyash-0.5.0/tests/cassettes/test_duration/TestDuration.test_calculate_duration.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_duration/TestDuration.test_calculate_duration_not_found.yaml` & `jellyash-0.5.0/tests/cassettes/test_duration/TestDuration.test_calculate_duration_not_found.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_nextup/TestEpisodeStr.client.yaml` & `jellyash-0.5.0/tests/cassettes/test_nextup/TestEpisodeStr.client.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_nextup/TestEpisodeStr.test_episode_str.yaml` & `jellyash-0.5.0/tests/cassettes/test_nextup/TestEpisodeStr.test_episode_str.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_search/TestSearch.test_multiple_terms_exact.yaml` & `jellyash-0.5.0/tests/cassettes/test_search/TestSearch.test_multiple_terms_exact.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_search/TestSearch.test_multiple_terms_not_exact.yaml` & `jellyash-0.5.0/tests/cassettes/test_search/TestSearch.test_multiple_terms_not_exact.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_search/TestSearch.test_single_term.yaml` & `jellyash-0.5.0/tests/cassettes/test_search/TestSearch.test_single_term.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_token/TestCreateJellyfinToken.test_create_token.yaml` & `jellyash-0.5.0/tests/cassettes/test_token/TestCreateJellyfinToken.test_create_token.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_unwatched/TestUnwatched.client.yaml` & `jellyash-0.5.0/tests/cassettes/test_unwatched/TestUnwatched.client.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_unwatched/TestUnwatched.test_all_unwatched.yaml` & `jellyash-0.5.0/tests/cassettes/test_unwatched/TestUnwatched.test_all_unwatched.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_unwatched/TestUnwatched.test_specific_unwatched.yaml` & `jellyash-0.5.0/tests/cassettes/test_unwatched/TestUnwatched.test_specific_unwatched.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/tests/cassettes/test_unwatched/TestUnwatched.test_specific_unwatched_not_found.yaml` & `jellyash-0.5.0/tests/cassettes/test_unwatched/TestUnwatched.test_specific_unwatched_not_found.yaml`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/LICENSE` & `jellyash-0.5.0/LICENSE`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/README.md` & `jellyash-0.5.0/README.md`

 * *Files identical despite different names*

### Comparing `jellyash-0.4.1/pyproject.toml` & `jellyash-0.5.0/pyproject.toml`

 * *Files 10% similar despite different names*

```diff
@@ -3,20 +3,23 @@
 build-backend = "hatchling.build"
 
 [project]
 name = "jellyash"
 dynamic = ["version"]
 license = {file = "LICENSE"}
 readme = "README.md"
-requires-python = ">= 3.7"
+requires-python = ">= 3.8"
 dependencies = [
     "jellyfin_apiclient_python",
     "typing_extensions;python_version<'3.11'",
 ]
 
+[project.urls]
+Source = "https://github.com/s-t-e-v-e-n-k/jellyash"
+
 [project.scripts]
 average_duration = "jellyash.duration:average_duration"
 create_jellyfin_token = "jellyash.token:create_jellyfin_token"
 nextup = "jellyash.nextup:nextup"
 unwatched = "jellyash.unwatched:unwatched"
 
 [tool.hatch.version]
```

### Comparing `jellyash-0.4.1/PKG-INFO` & `jellyash-0.5.0/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,21 +1,22 @@
 Metadata-Version: 2.1
 Name: jellyash
-Version: 0.4.1
+Version: 0.5.0
+Project-URL: Source, https://github.com/s-t-e-v-e-n-k/jellyash
 License: Copyright 2023 Steve Kowalik <steven@wedontsleep.org>
         
         Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
         
         The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
         
         THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
         
         
 License-File: LICENSE
-Requires-Python: >=3.7
+Requires-Python: >=3.8
 Requires-Dist: jellyfin-apiclient-python
 Requires-Dist: typing-extensions; python_version < '3.11'
 Description-Content-Type: text/markdown
 
 # Jellyash
 
 [![PyPI Version](https://badge.fury.io/py/jellyash.svg)](https://badge.fury.io/py/jellyash)[![Build](https://github.com/s-t-e-v-e-n-k/jellyash/actions/workflows/ci.yml/badge.svg)](https://github.com/s-t-e-v-e-n-k/jellyash/actions/workflows/ci.yml)[![Coverage](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/s-t-e-v-e-n-k/0926cbcb886804fa2c0fdb68212a367d/raw/coverage-badge.json)](https://gist.github.com/s-t-e-v-e-n-k/0926cbcb886804fa2c0fdb68212a367d/raw/coverage-badge.json)
```

