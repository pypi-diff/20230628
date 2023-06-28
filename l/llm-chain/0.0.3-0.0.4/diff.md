# Comparing `tmp/llm-chain-0.0.3.tar.gz` & `tmp/llm-chain-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "llm-chain-0.0.3.tar", last modified: Tue Jun 27 00:17:02 2023, max compression
+gzip compressed data, was "llm-chain-0.0.4.tar", last modified: Wed Jun 28 03:31:41 2023, max compression
```

## Comparing `llm-chain-0.0.3.tar` & `llm-chain-0.0.4.tar`

### file list

```diff
@@ -1,34 +1,34 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:17:02.446094 llm-chain-0.0.3/
--rw-r--r--   0 root         (0) root         (0)     1072 2023-02-25 17:02:25.000000 llm-chain-0.0.3/LICENSE
--rw-r--r--   0 root         (0) root         (0)    10350 2023-06-27 00:17:02.447234 llm-chain-0.0.3/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     9822 2023-06-26 22:06:13.000000 llm-chain-0.0.3/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:17:02.386967 llm-chain-0.0.3/llm_chain/
--rw-r--r--   0 root         (0) root         (0)       52 2023-06-09 17:08:19.000000 llm-chain-0.0.3/llm_chain/__init__.py
--rw-r--r--   0 root         (0) root         (0)    15474 2023-06-27 00:14:54.000000 llm-chain-0.0.3/llm_chain/base.py
--rw-r--r--   0 root         (0) root         (0)     2577 2023-06-26 01:19:40.000000 llm-chain-0.0.3/llm_chain/indexes.py
--rw-r--r--   0 root         (0) root         (0)     1253 2023-06-26 16:49:38.000000 llm-chain-0.0.3/llm_chain/memory.py
--rw-r--r--   0 root         (0) root         (0)     6458 2023-06-26 22:47:09.000000 llm-chain-0.0.3/llm_chain/models.py
--rw-r--r--   0 root         (0) root         (0)     2172 2023-06-26 23:23:59.000000 llm-chain-0.0.3/llm_chain/prompt_templates.py
--rw-r--r--   0 root         (0) root         (0)      695 2023-06-14 02:06:25.000000 llm-chain-0.0.3/llm_chain/resources.py
--rw-r--r--   0 root         (0) root         (0)     2714 2023-06-26 00:25:02.000000 llm-chain-0.0.3/llm_chain/tools.py
--rw-r--r--   0 root         (0) root         (0)     4202 2023-06-23 02:34:10.000000 llm-chain-0.0.3/llm_chain/utilities.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:17:02.405178 llm-chain-0.0.3/llm_chain.egg-info/
--rw-r--r--   0 root         (0) root         (0)    10350 2023-06-27 00:17:02.000000 llm-chain-0.0.3/llm_chain.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      642 2023-06-27 00:17:02.000000 llm-chain-0.0.3/llm_chain.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 00:17:02.000000 llm-chain-0.0.3/llm_chain.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       33 2023-06-27 00:17:02.000000 llm-chain-0.0.3/llm_chain.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       16 2023-06-27 00:17:02.000000 llm-chain-0.0.3/llm_chain.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)      104 2023-02-25 17:02:25.000000 llm-chain-0.0.3/pyproject.toml
--rw-r--r--   0 root         (0) root         (0)      666 2023-06-27 00:17:02.449079 llm-chain-0.0.3/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:17:02.443968 llm-chain-0.0.3/tests/
--rw-r--r--   0 root         (0) root         (0)       52 2023-06-10 00:17:26.000000 llm-chain-0.0.3/tests/__init__.py
--rw-r--r--   0 root         (0) root         (0)     4281 2023-06-24 02:22:45.000000 llm-chain-0.0.3/tests/conftest.py
--rw-r--r--   0 root         (0) root         (0)    23550 2023-06-26 23:23:05.000000 llm-chain-0.0.3/tests/test_chains.py
--rw-r--r--   0 root         (0) root         (0)    11370 2023-06-26 17:14:59.000000 llm-chain-0.0.3/tests/test_indexes.py
--rw-r--r--   0 root         (0) root         (0)    13991 2023-06-26 16:57:51.000000 llm-chain-0.0.3/tests/test_memory.py
--rw-r--r--   0 root         (0) root         (0)    26878 2023-06-26 17:13:47.000000 llm-chain-0.0.3/tests/test_models.py
--rw-r--r--   0 root         (0) root         (0)     1899 2023-06-23 05:43:22.000000 llm-chain-0.0.3/tests/test_prompt_templates.py
--rw-r--r--   0 root         (0) root         (0)     1998 2023-06-14 02:16:47.000000 llm-chain-0.0.3/tests/test_records.py
--rw-r--r--   0 root         (0) root         (0)     5349 2023-06-27 00:13:32.000000 llm-chain-0.0.3/tests/test_session.py
--rw-r--r--   0 root         (0) root         (0)    13510 2023-06-26 00:34:09.000000 llm-chain-0.0.3/tests/test_tools.py
--rw-r--r--   0 root         (0) root         (0)     3408 2023-06-26 17:18:37.000000 llm-chain-0.0.3/tests/test_utilities.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 03:31:41.447365 llm-chain-0.0.4/
+-rw-r--r--   0 root         (0) root         (0)     1072 2023-02-25 17:02:25.000000 llm-chain-0.0.4/LICENSE
+-rw-r--r--   0 root         (0) root         (0)    10352 2023-06-28 03:31:41.448496 llm-chain-0.0.4/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     9824 2023-06-27 20:16:34.000000 llm-chain-0.0.4/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 03:31:41.389157 llm-chain-0.0.4/llm_chain/
+-rw-r--r--   0 root         (0) root         (0)       52 2023-06-09 17:08:19.000000 llm-chain-0.0.4/llm_chain/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    16384 2023-06-27 19:59:06.000000 llm-chain-0.0.4/llm_chain/base.py
+-rw-r--r--   0 root         (0) root         (0)     2577 2023-06-26 01:19:40.000000 llm-chain-0.0.4/llm_chain/indexes.py
+-rw-r--r--   0 root         (0) root         (0)     1253 2023-06-26 16:49:38.000000 llm-chain-0.0.4/llm_chain/memory.py
+-rw-r--r--   0 root         (0) root         (0)     6458 2023-06-26 22:47:09.000000 llm-chain-0.0.4/llm_chain/models.py
+-rw-r--r--   0 root         (0) root         (0)     2172 2023-06-26 23:23:59.000000 llm-chain-0.0.4/llm_chain/prompt_templates.py
+-rw-r--r--   0 root         (0) root         (0)      695 2023-06-14 02:06:25.000000 llm-chain-0.0.4/llm_chain/resources.py
+-rw-r--r--   0 root         (0) root         (0)     2714 2023-06-26 00:25:02.000000 llm-chain-0.0.4/llm_chain/tools.py
+-rw-r--r--   0 root         (0) root         (0)     4202 2023-06-23 02:34:10.000000 llm-chain-0.0.4/llm_chain/utilities.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 03:31:41.410282 llm-chain-0.0.4/llm_chain.egg-info/
+-rw-r--r--   0 root         (0) root         (0)    10352 2023-06-28 03:31:41.000000 llm-chain-0.0.4/llm_chain.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      642 2023-06-28 03:31:41.000000 llm-chain-0.0.4/llm_chain.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 03:31:41.000000 llm-chain-0.0.4/llm_chain.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       33 2023-06-28 03:31:41.000000 llm-chain-0.0.4/llm_chain.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       16 2023-06-28 03:31:41.000000 llm-chain-0.0.4/llm_chain.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)      104 2023-02-25 17:02:25.000000 llm-chain-0.0.4/pyproject.toml
+-rw-r--r--   0 root         (0) root         (0)      666 2023-06-28 03:31:41.451468 llm-chain-0.0.4/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 03:31:41.444902 llm-chain-0.0.4/tests/
+-rw-r--r--   0 root         (0) root         (0)       52 2023-06-10 00:17:26.000000 llm-chain-0.0.4/tests/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     4281 2023-06-24 02:22:45.000000 llm-chain-0.0.4/tests/conftest.py
+-rw-r--r--   0 root         (0) root         (0)    23562 2023-06-27 19:55:50.000000 llm-chain-0.0.4/tests/test_chains.py
+-rw-r--r--   0 root         (0) root         (0)    11370 2023-06-26 17:14:59.000000 llm-chain-0.0.4/tests/test_indexes.py
+-rw-r--r--   0 root         (0) root         (0)    13991 2023-06-26 16:57:51.000000 llm-chain-0.0.4/tests/test_memory.py
+-rw-r--r--   0 root         (0) root         (0)    26878 2023-06-26 17:13:47.000000 llm-chain-0.0.4/tests/test_models.py
+-rw-r--r--   0 root         (0) root         (0)     1899 2023-06-23 05:43:22.000000 llm-chain-0.0.4/tests/test_prompt_templates.py
+-rw-r--r--   0 root         (0) root         (0)     1998 2023-06-14 02:16:47.000000 llm-chain-0.0.4/tests/test_records.py
+-rw-r--r--   0 root         (0) root         (0)     6227 2023-06-27 19:55:26.000000 llm-chain-0.0.4/tests/test_session.py
+-rw-r--r--   0 root         (0) root         (0)    13510 2023-06-26 00:34:09.000000 llm-chain-0.0.4/tests/test_tools.py
+-rw-r--r--   0 root         (0) root         (0)     3408 2023-06-26 17:18:37.000000 llm-chain-0.0.4/tests/test_utilities.py
```

### Comparing `llm-chain-0.0.3/LICENSE` & `llm-chain-0.0.4/LICENSE`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/PKG-INFO` & `llm-chain-0.0.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: llm-chain
-Version: 0.0.3
+Version: 0.0.4
 Summary: Simple and extensible LLM Chaining
 Home-page: https://github.com/shane-kercheval/llm-chain
 Author: Shane Kercheval
 Author-email: shane.kercheval@gmail.com
 Project-URL: Bug Tracker, https://github.com/shane-kercheval/llm-chain/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
@@ -158,15 +158,15 @@
     """
     For each url (i.e. `href` in `search_results`):
     - extracts text
     - replace new-lines with spaces
     - create a Document object
     """
     return [
-        Document(content=scrape_url(x['href']).replace('\n', ' '))
+        Document(content=re.sub(r'\s+', ' ', scrape_url(x['href'])))
         for x in search_results
     ]
 
 question_1 = Value()  # Value is a caching/reinjection mechanism; see note above
 question_2 = lambda x: f'Summarize the following in less than 20 words: "{x}"'
 
 # each link is a callable where the output of one link is the input to the next link
```

### Comparing `llm-chain-0.0.3/README.md` & `llm-chain-0.0.4/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -143,15 +143,15 @@
     """
     For each url (i.e. `href` in `search_results`):
     - extracts text
     - replace new-lines with spaces
     - create a Document object
     """
     return [
-        Document(content=scrape_url(x['href']).replace('\n', ' '))
+        Document(content=re.sub(r'\s+', ' ', scrape_url(x['href'])))
         for x in search_results
     ]
 
 question_1 = Value()  # Value is a caching/reinjection mechanism; see note above
 question_2 = lambda x: f'Summarize the following in less than 20 words: "{x}"'
 
 # each link is a callable where the output of one link is the input to the next link
```

### Comparing `llm-chain-0.0.3/llm_chain/base.py` & `llm-chain-0.0.4/llm_chain/base.py`

 * *Files 2% similar despite different names*

```diff
@@ -368,25 +368,53 @@
         if not totals:
             return None
         return sum(totals)
 
     @property
     def cost(self) -> float | None:
         """
-        Returns the total number of cost used by the all models during the chain/object's
+        Returns the total cost used by the all models during the chain/object's
         lifetime.
 
         Returns `None` if none of the models knows how to count cost.
         """
         records = self.usage_history
         totals = [x.cost for x in records if x.cost]
         if not totals:
             return None
         return sum(totals)
 
+    @property
+    def prompt_tokens(self) -> int | None:
+        """
+        Returns the total number of prompt tokens used by the all models during the chain/object's
+        lifetime.
+
+        Returns `None` if none of the models knows how to count tokens.
+        """
+        records = self.message_history
+        totals = [x.prompt_tokens for x in records if x.prompt_tokens]
+        if not totals:
+            return None
+        return sum(totals)
+
+    @property
+    def response_tokens(self) -> int | None:
+        """
+        Returns the total number of response tokens used by the all models during the
+        chain/object's lifetime.
+
+        Returns `None` if none of the models knows how to count tokens.
+        """
+        records = self.message_history
+        totals = [x.response_tokens for x in records if x.response_tokens]
+        if not totals:
+            return None
+        return sum(totals)
+
 
 class Chain(LinkAggregator):
     """TODO."""
 
     def __init__(self, links: list[Callable[[Any], Any]]):
         self._links = links
```

### Comparing `llm-chain-0.0.3/llm_chain/indexes.py` & `llm-chain-0.0.4/llm_chain/indexes.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/llm_chain/memory.py` & `llm-chain-0.0.4/llm_chain/memory.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/llm_chain/models.py` & `llm-chain-0.0.4/llm_chain/models.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/llm_chain/prompt_templates.py` & `llm-chain-0.0.4/llm_chain/prompt_templates.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/llm_chain/resources.py` & `llm-chain-0.0.4/llm_chain/resources.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/llm_chain/tools.py` & `llm-chain-0.0.4/llm_chain/tools.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/llm_chain/utilities.py` & `llm-chain-0.0.4/llm_chain/utilities.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/llm_chain.egg-info/PKG-INFO` & `llm-chain-0.0.4/llm_chain.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: llm-chain
-Version: 0.0.3
+Version: 0.0.4
 Summary: Simple and extensible LLM Chaining
 Home-page: https://github.com/shane-kercheval/llm-chain
 Author: Shane Kercheval
 Author-email: shane.kercheval@gmail.com
 Project-URL: Bug Tracker, https://github.com/shane-kercheval/llm-chain/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
@@ -158,15 +158,15 @@
     """
     For each url (i.e. `href` in `search_results`):
     - extracts text
     - replace new-lines with spaces
     - create a Document object
     """
     return [
-        Document(content=scrape_url(x['href']).replace('\n', ' '))
+        Document(content=re.sub(r'\s+', ' ', scrape_url(x['href'])))
         for x in search_results
     ]
 
 question_1 = Value()  # Value is a caching/reinjection mechanism; see note above
 question_2 = lambda x: f'Summarize the following in less than 20 words: "{x}"'
 
 # each link is a callable where the output of one link is the input to the next link
```

### Comparing `llm-chain-0.0.3/llm_chain.egg-info/SOURCES.txt` & `llm-chain-0.0.4/llm_chain.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/setup.cfg` & `llm-chain-0.0.4/setup.cfg`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = llm-chain
-version = 0.0.3
+version = 0.0.4
 author = Shane Kercheval
 author_email = shane.kercheval@gmail.com
 description = Simple and extensible LLM Chaining
 long_description = file: README.md
 long_description_content_type = text/markdown
 url = https://github.com/shane-kercheval/llm-chain
 project_urls =
```

### Comparing `llm-chain-0.0.3/tests/conftest.py` & `llm-chain-0.0.4/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/tests/test_chains.py` & `llm-chain-0.0.4/tests/test_chains.py`

 * *Files 0% similar despite different names*

```diff
@@ -71,15 +71,15 @@
 
 def test_Value():  # noqa
     value = Value()
     assert value() is None
     assert value('test') == 'test'
     assert value() == 'test'
 
-def test_chain():  # noqa
+def test_chain_propegation():  # noqa
     # test empty chain
     chain = Chain(links=[])
     assert chain() is None
     assert chain('param') is None
     assert chain(value=1) is None
 
     # test chain with one link
```

### Comparing `llm-chain-0.0.3/tests/test_indexes.py` & `llm-chain-0.0.4/tests/test_indexes.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/tests/test_memory.py` & `llm-chain-0.0.4/tests/test_memory.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/tests/test_models.py` & `llm-chain-0.0.4/tests/test_models.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/tests/test_prompt_templates.py` & `llm-chain-0.0.4/tests/test_prompt_templates.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/tests/test_records.py` & `llm-chain-0.0.4/tests/test_records.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/tests/test_session.py` & `llm-chain-0.0.4/tests/test_session.py`

 * *Files 18% similar despite different names*

```diff
@@ -27,33 +27,39 @@
     with pytest.raises(ValueError):  # noqa: PT011
         session('test')
     assert session.history == []
     assert session.usage_history == []
     assert session.message_history == []
     assert session.cost is None
     assert session.total_tokens is None
+    assert session.prompt_tokens is None
+    assert session.response_tokens is None
     assert len(session) == 0
 
     session.append(chain=Chain(links=[]))
     assert session('test') is None
     assert session.history == []
     assert session.usage_history == []
     assert session.message_history == []
     assert session.cost is None
     assert session.total_tokens is None
+    assert session.prompt_tokens is None
+    assert session.response_tokens is None
     assert len(session) == 1
 
     # test chain with a link that doesn't have a history property
     session.append(chain=Chain(links=[lambda x: x]))
     assert session('test') == 'test'
     assert session.history == []
     assert session.usage_history == []
     assert session.message_history == []
     assert session.cost is None
     assert session.total_tokens is None
+    assert session.prompt_tokens is None
+    assert session.response_tokens is None
     assert len(session) == 2
 
     record_a = UsageRecord(metadata={'id': 'record_a'}, total_tokens=None, cost=None)
     sleep(0.001)
     record_b = UsageRecord(metadata={'id': 'record_b'}, total_tokens=100, cost=0.01)
     sleep(0.001)
     record_c = Record(metadata={'id': 'record_d'})
@@ -62,85 +68,101 @@
     sleep(0.001)
     record_e = MessageRecord(
         metadata={'id': 'record_e'},
         prompt='prompt',
         response='response',
         cost=0.5,
         total_tokens=103,
+        prompt_tokens=34,
+        response_tokens=53,
     )
 
     session.append(chain=Chain(links=[MockHistoricalUsageRecords(mock_id='mock_a')]))
     return_value, mock_id = session(record_a)
     assert return_value == record_a
     assert mock_id == 'mock_a'
     assert session.history == [record_a]
     assert session.usage_history == [record_a]
     assert session.message_history == []
     assert session.cost is None
     assert session.total_tokens is None
+    assert session.prompt_tokens is None
+    assert session.response_tokens is None
     assert len(session) == 3
 
     # if we add the same record it should be ignored
     return_value, mock_id = session(record_a)
     assert return_value == record_a
     assert mock_id == 'mock_a'
     assert session.history == [record_a]
     assert session.usage_history == [record_a]
     assert session.message_history == []
     assert session.cost is None
     assert session.total_tokens is None
+    assert session.prompt_tokens is None
+    assert session.response_tokens is None
     assert len(session) == 3
 
     return_value, mock_id = session(record_b)
     assert return_value == record_b
     assert mock_id == 'mock_a'
     assert session.history == [record_a, record_b]
     assert session.usage_history == [record_a, record_b]
     assert session.message_history == []
     assert session.cost == 0.01
     assert session.total_tokens == 100
+    assert session.prompt_tokens is None
+    assert session.response_tokens is None
     assert len(session) == 3
 
     # add record `e` out of order; later, ensure the correct order is returned
     session.append(chain=Chain(links=[MockHistoricalUsageRecords(mock_id='mock_b')]))
     return_value, mock_id = session(record_e)
     assert return_value == record_e
     assert mock_id == 'mock_b'
     assert session.history == [record_a, record_b, record_e]
     assert session.usage_history == [record_a, record_b, record_e]
     assert session.message_history == [record_e]
     assert session.cost == 0.51
     assert session.total_tokens == 203
+    assert session.prompt_tokens == 34
+    assert session.response_tokens == 53
     assert len(session) == 4
 
     # adding the same record to a new link should not double-count
     return_value, mock_id = session(record_b)
     assert return_value == record_b
     assert mock_id == 'mock_b'
     assert session.history == [record_a, record_b, record_e]
     assert session.usage_history == [record_a, record_b, record_e]
     assert session.message_history == [record_e]
     assert session.cost == 0.51
     assert session.total_tokens == 203
+    assert session.prompt_tokens == 34
+    assert session.response_tokens == 53
     assert len(session) == 4
 
     # add record `d` out of order; later, ensure the correct order is returned
     return_value, mock_id = session(record_d)
     assert return_value == record_d
     assert mock_id == 'mock_b'
     assert session.history == [record_a, record_b, record_d, record_e]
     assert session.usage_history == [record_a, record_b, record_e]
     assert session.message_history == [record_e]
     assert session.cost == 0.51
     assert session.total_tokens == 203
+    assert session.prompt_tokens == 34
+    assert session.response_tokens == 53
     assert len(session) == 4
 
     # add record `c` out of order; c should be returned before d
     return_value, mock_id = session(record_c)
     assert return_value == record_c
     assert mock_id == 'mock_b'
     assert session.history == [record_a, record_b, record_c, record_d, record_e]
     assert session.usage_history == [record_a, record_b, record_e]
     assert session.message_history == [record_e]
     assert session.cost == 0.51
     assert session.total_tokens == 203
+    assert session.prompt_tokens == 34
+    assert session.response_tokens == 53
     assert len(session) == 4
```

### Comparing `llm-chain-0.0.3/tests/test_tools.py` & `llm-chain-0.0.4/tests/test_tools.py`

 * *Files identical despite different names*

### Comparing `llm-chain-0.0.3/tests/test_utilities.py` & `llm-chain-0.0.4/tests/test_utilities.py`

 * *Files identical despite different names*

