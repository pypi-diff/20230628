# Comparing `tmp/pydns3-0.0.8.tar.gz` & `tmp/pydns3-0.0.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pydns3-0.0.8.tar", last modified: Sun Jun 25 08:03:48 2023, max compression
+gzip compressed data, was "pydns3-0.0.9.tar", last modified: Wed Jun 28 01:49:35 2023, max compression
```

## Comparing `pydns3-0.0.8.tar` & `pydns3-0.0.9.tar`

### file list

```diff
@@ -1,36 +1,36 @@
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:03:48.356862 pydns3-0.0.8/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      688 2023-06-25 08:03:48.356862 pydns3-0.0.8/PKG-INFO
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      243 2023-03-26 23:42:47.000000 pydns3-0.0.8/README.md
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:03:48.352862 pydns3-0.0.8/pydns/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      562 2023-04-18 21:16:11.000000 pydns3-0.0.8/pydns/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     3031 2023-06-25 08:01:07.000000 pydns3-0.0.8/pydns/answer.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:03:48.352862 pydns3-0.0.8/pydns/client/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1173 2023-03-26 23:42:47.000000 pydns3-0.0.8/pydns/client/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1083 2023-06-25 08:01:07.000000 pydns3-0.0.8/pydns/client/https.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     3148 2023-06-25 08:01:07.000000 pydns3-0.0.8/pydns/client/standard.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2335 2023-06-25 08:01:07.000000 pydns3-0.0.8/pydns/content.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:03:48.352862 pydns3-0.0.8/pydns/edns/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      197 2023-03-26 23:42:47.000000 pydns3-0.0.8/pydns/edns/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1468 2023-06-25 08:01:07.000000 pydns3-0.0.8/pydns/edns/record.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2591 2023-03-29 22:05:52.000000 pydns3-0.0.8/pydns/enum.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1406 2023-03-26 23:42:47.000000 pydns3-0.0.8/pydns/exceptions.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2117 2023-06-25 08:01:07.000000 pydns3-0.0.8/pydns/flags.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     4158 2023-06-25 08:01:07.000000 pydns3-0.0.8/pydns/message.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      467 2023-06-25 08:01:07.000000 pydns3-0.0.8/pydns/question.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:03:48.352862 pydns3-0.0.8/pydns/server/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      132 2023-03-26 23:42:47.000000 pydns3-0.0.8/pydns/server/__init__.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:03:48.352862 pydns3-0.0.8/pydns/server/backend/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      994 2023-03-30 07:56:17.000000 pydns3-0.0.8/pydns/server/backend/__init__.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     5253 2023-06-25 08:01:07.000000 pydns3-0.0.8/pydns/server/backend/blacklist.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     4060 2023-06-25 08:01:07.000000 pydns3-0.0.8/pydns/server/backend/cache.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     1250 2023-06-25 08:01:07.000000 pydns3-0.0.8/pydns/server/backend/forwarder.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     2647 2023-03-30 08:23:38.000000 pydns3-0.0.8/pydns/server/backend/memory.py
--rw-rw-r--   0 andrew    (1000) andrew    (1000)     5156 2023-06-25 08:01:07.000000 pydns3-0.0.8/pydns/server/server.py
-drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-25 08:03:48.356862 pydns3-0.0.8/pydns3.egg-info/
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      688 2023-06-25 08:03:48.000000 pydns3-0.0.8/pydns3.egg-info/PKG-INFO
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      628 2023-06-25 08:03:48.000000 pydns3-0.0.8/pydns3.egg-info/SOURCES.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)        1 2023-06-25 08:03:48.000000 pydns3-0.0.8/pydns3.egg-info/dependency_links.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)       56 2023-06-25 08:03:48.000000 pydns3-0.0.8/pydns3.egg-info/requires.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)        6 2023-06-25 08:03:48.000000 pydns3-0.0.8/pydns3.egg-info/top_level.txt
--rw-rw-r--   0 andrew    (1000) andrew    (1000)       38 2023-06-25 08:03:48.356862 pydns3-0.0.8/setup.cfg
--rw-rw-r--   0 andrew    (1000) andrew    (1000)      811 2023-06-25 08:03:25.000000 pydns3-0.0.8/setup.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:49:35.144377 pydns3-0.0.9/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      688 2023-06-28 01:49:35.144377 pydns3-0.0.9/PKG-INFO
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      243 2023-03-26 23:42:47.000000 pydns3-0.0.9/README.md
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:49:35.140376 pydns3-0.0.9/pydns/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      562 2023-04-18 21:16:11.000000 pydns3-0.0.9/pydns/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     3031 2023-06-25 08:01:07.000000 pydns3-0.0.9/pydns/answer.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:49:35.140376 pydns3-0.0.9/pydns/client/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1173 2023-03-26 23:42:47.000000 pydns3-0.0.9/pydns/client/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1083 2023-06-25 08:01:07.000000 pydns3-0.0.9/pydns/client/https.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     3148 2023-06-25 08:01:07.000000 pydns3-0.0.9/pydns/client/standard.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2335 2023-06-25 08:01:07.000000 pydns3-0.0.9/pydns/content.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:49:35.140376 pydns3-0.0.9/pydns/edns/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      197 2023-03-26 23:42:47.000000 pydns3-0.0.9/pydns/edns/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1468 2023-06-25 08:01:07.000000 pydns3-0.0.9/pydns/edns/record.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2591 2023-03-29 22:05:52.000000 pydns3-0.0.9/pydns/enum.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1406 2023-03-26 23:42:47.000000 pydns3-0.0.9/pydns/exceptions.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2117 2023-06-25 08:01:07.000000 pydns3-0.0.9/pydns/flags.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     4158 2023-06-25 08:01:07.000000 pydns3-0.0.9/pydns/message.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      467 2023-06-25 08:01:07.000000 pydns3-0.0.9/pydns/question.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:49:35.140376 pydns3-0.0.9/pydns/server/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      132 2023-03-26 23:42:47.000000 pydns3-0.0.9/pydns/server/__init__.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:49:35.144377 pydns3-0.0.9/pydns/server/backend/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      994 2023-03-30 07:56:17.000000 pydns3-0.0.9/pydns/server/backend/__init__.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     5253 2023-06-25 08:01:07.000000 pydns3-0.0.9/pydns/server/backend/blacklist.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     4604 2023-06-28 01:17:59.000000 pydns3-0.0.9/pydns/server/backend/cache.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     1250 2023-06-25 08:01:07.000000 pydns3-0.0.9/pydns/server/backend/forwarder.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     2663 2023-06-27 23:39:48.000000 pydns3-0.0.9/pydns/server/backend/memory.py
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)     5156 2023-06-25 08:01:07.000000 pydns3-0.0.9/pydns/server/server.py
+drwxrwxr-x   0 andrew    (1000) andrew    (1000)        0 2023-06-28 01:49:35.144377 pydns3-0.0.9/pydns3.egg-info/
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      688 2023-06-28 01:49:35.000000 pydns3-0.0.9/pydns3.egg-info/PKG-INFO
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      628 2023-06-28 01:49:35.000000 pydns3-0.0.9/pydns3.egg-info/SOURCES.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)        1 2023-06-28 01:49:35.000000 pydns3-0.0.9/pydns3.egg-info/dependency_links.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)       56 2023-06-28 01:49:35.000000 pydns3-0.0.9/pydns3.egg-info/requires.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)        6 2023-06-28 01:49:35.000000 pydns3-0.0.9/pydns3.egg-info/top_level.txt
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)       38 2023-06-28 01:49:35.144377 pydns3-0.0.9/setup.cfg
+-rw-rw-r--   0 andrew    (1000) andrew    (1000)      811 2023-06-28 01:49:09.000000 pydns3-0.0.9/setup.py
```

### Comparing `pydns3-0.0.8/PKG-INFO` & `pydns3-0.0.9/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pydns3
-Version: 0.0.8
+Version: 0.0.9
 Summary: Simple Python DNS Library. DNS Packet-Parsing/Client/Server
 Home-page: https://github.com/imgurbot12/pydns
 Author: Andrew Scott
 Author-email: imgurbot12@gmail.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `pydns3-0.0.8/pydns/__init__.py` & `pydns3-0.0.9/pydns/__init__.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/answer.py` & `pydns3-0.0.9/pydns/answer.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/client/__init__.py` & `pydns3-0.0.9/pydns/client/__init__.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/client/https.py` & `pydns3-0.0.9/pydns/client/https.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/client/standard.py` & `pydns3-0.0.9/pydns/client/standard.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/content.py` & `pydns3-0.0.9/pydns/content.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/edns/record.py` & `pydns3-0.0.9/pydns/edns/record.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/enum.py` & `pydns3-0.0.9/pydns/enum.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/exceptions.py` & `pydns3-0.0.9/pydns/exceptions.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/flags.py` & `pydns3-0.0.9/pydns/flags.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/message.py` & `pydns3-0.0.9/pydns/message.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/server/backend/__init__.py` & `pydns3-0.0.9/pydns/server/backend/__init__.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/server/backend/blacklist.py` & `pydns3-0.0.9/pydns/server/backend/blacklist.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/server/backend/cache.py` & `pydns3-0.0.9/pydns/server/backend/cache.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,16 +1,17 @@
 """
 Backend Extension to support In-Memory Answer Caching
 """
 import time
 import math
+from logging import Logger, getLogger
 from threading import Lock
-from typing import List, Set, Dict, ClassVar
+from typing import List, Set, Dict, ClassVar, Optional
 
-from pyderive import dataclass, field
+from pyderive import InitVar, dataclass, field
 
 from . import Answers, Backend, RType, Answer
 from .memory import MemoryBackend
 from .blacklist import Blacklist
 
 #** Variables **#
 __all__ = ['Cache']
@@ -21,49 +22,63 @@
 #** Classes **#
 
 @dataclass(slots=True)
 class CacheRecord:
     """
     Record Entry for In-Memory Cache
     """
-    answers:      List[Answer]
-    expiration:   float
-    ttl:          int
-    lifetime_mod: int = field(default=0, init=False)
-
-    def lifetime(self):
-        """calculate lifetime remaining of record"""
-        return int(math.floor(self.expiration - time.time()))
-
-    def ttl_mod(self, lifetime: int) -> int:
-        """calculate ttl modifier based on the given lifetime"""
-        elapsed = self.ttl - lifetime
-        ttl_mod = elapsed - self.lifetime_mod
-        self.lifetime_mod = elapsed
-        return ttl_mod
+    answers:    List[Answer]
+    expiration: InitVar[int]
+    expires:    float = field(init=False)
+    accessed:   float = field(init=False)
+
+    def __post_init__(self, expiration: int):
+        """calculate expiration-time and last-accessed time"""
+        ttl = min(a.ttl for a in self.answers)
+        ttl = min(ttl, expiration) if expiration else ttl
+        now = time.time()
+        self.expires  = now + ttl
+        self.accessed = now
+
+    def is_expired(self) -> bool:
+        """calculate if expiration has passed or ttl is expired"""
+        now = time.time()
+        if self.expires <= now:
+            return True
+        elapsed = math.floor(now - self.accessed)
+        if not elapsed:
+            return False
+        for answer in self.answers:
+            answer.ttl -= elapsed
+            if answer.ttl <= 0:
+                return True
+        self.accessed = now
+        return False
 
 @dataclass(slots=True, repr=False)
 class Cache(Backend):
     """
     In-Memory Cache Extension for Backend Results
     """
     source: ClassVar[str] = 'Cache'
 
     backend:    Backend
-    expiration: int = 30
-    maxsize:    int = 10000
+    expiration: int      = 30
+    maxsize:    int      = 10000
     ignore:     Set[str] = field(default_factory=lambda: IGNORE)
+    logger:     Logger   = field(default_factory=lambda: getLogger('pydns'))
  
     mutex:       Lock                   = field(default_factory=Lock, init=False)
     cache:       Dict[str, CacheRecord] = field(default_factory=dict, init=False)
     authorities: Dict[bytes, bool]      = field(default_factory=dict, init=False)
 
     recursion_available: bool = field(default=False, init=False)
  
     def __post_init__(self):
+        self.logger              = self.logger.getChild('cache')
         self.recursion_available = self.backend.recursion_available
 
     def is_authority(self, domain: bytes) -> bool:
         """
         retrieve if domain is authority from cache before checking backend
         """
         # check cache before querying backend
@@ -72,46 +87,49 @@
         # query backend and then permanently cache authority result
         authority = self.backend.is_authority(domain)
         with self.mutex:
             if len(self.authorities) >= self.maxsize:
                 self.authorities.clear()
             self.authorities[domain] = authority
         return authority
+ 
+    def get_cache(self, domain: bytes, rtype: RType) -> Optional[Answers]:
+        """
+        retrieve from cache directly if present
+        """
+        key = f'{domain}->{rtype.name}'
+        with self.mutex:
+            if key not in self.cache:
+                return
+            record = self.cache[key]
+            if record.is_expired():
+                self.logger.debug(f'{key} expired')
+                del self.cache[key]
+                return
+            return Answers(record.answers, self.source)
+
+    def set_cache(self, domain: bytes, rtype: RType, answers: Answers):
+        """
+        save the given answers to cache for the specified domain/rtype
+        """
+        key = f'{domain}->{rtype.name}'
+        with self.mutex:
+            if len(self.cache) >= self.maxsize:
+                self.logger.debug(f'maxsize: {self.maxsize} exceeded. clearing cache!')
+                self.cache.clear()
+            self.cache[key] = CacheRecord(answers.answers, self.expiration)
 
     def get_answers(self, domain: bytes, rtype: RType) -> Answers:
         """
         retrieve answers from cache before checking supplied backend
         """
         # attempt to retrieve from cache if it exists
-        key     = f'{domain}->{rtype.name}'
-        answers = None
-        if key in self.cache:
-            with self.mutex:
-                record   = self.cache[key]
-                lifetime = record.lifetime()
-                if lifetime > 0:
-                    # modify answer TTLs as cache begins to expire
-                    expire  = False
-                    ttl_mod = record.ttl_mod(lifetime)
-                    for answer in record.answers:
-                        answer.ttl -= ttl_mod
-                        if answer.ttl <= 0:
-                            expire = True
-                    # only return answers if none are expired
-                    if not expire:
-                        return Answers(record.answers, self.source)
-                del self.cache[key]
+        answers = self.get_cache(domain, rtype)
+        if answers is not None:
+            return answers
         # complete standard lookup for answers
         answers = self.backend.get_answers(domain, rtype)
         if answers.source in self.ignore:
             return answers
-        # cache result w/ optional expiration and return results
-        answers, source = answers
-        ttl        = max(a.ttl for a in answers) if answers else self.expiration
-        ttl        = min(ttl, self.expiration)
-        expiration = time.time() + ttl
-        with self.mutex:
-            if len(self.cache) >= self.maxsize:
-                self.cache.clear()
-            self.cache[key] = CacheRecord(answers, expiration, ttl)
-        return Answers(answers, source)
-
+        # save results to cache and return results
+        self.set_cache(domain, rtype, answers)
+        return answers
```

### Comparing `pydns3-0.0.8/pydns/server/backend/forwarder.py` & `pydns3-0.0.9/pydns/server/backend/forwarder.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns/server/backend/memory.py` & `pydns3-0.0.9/pydns/server/backend/memory.py`

 * *Files 1% similar despite different names*

```diff
@@ -17,17 +17,18 @@
 #: raw record entry configuration
 RecordEntries = Dict[str, List[Dict[str, Any]]]
 
 #** Classes **#
 
 class MemoryBackend(Backend):
     """Simple In-Memory Backend for DNS Records"""
-    source: ClassVar[str] = 'MemDB'
-    
-    __slots__ = ('records', 'authorities', 'recursion_available')
+    source: ClassVar[str]     = 'MemDB'
+    recursion_available: bool = False
+ 
+    __slots__ = ('records', 'authorities')
 
     def __init__(self):
         self.records:     RecordDB   = {}
         self.authorities: Set[bytes] = set()
 
     def add_answer(self, domain: bytes, answer: Answer):
         """
```

### Comparing `pydns3-0.0.8/pydns/server/server.py` & `pydns3-0.0.9/pydns/server/server.py`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/pydns3.egg-info/PKG-INFO` & `pydns3-0.0.9/pydns3.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pydns3
-Version: 0.0.8
+Version: 0.0.9
 Summary: Simple Python DNS Library. DNS Packet-Parsing/Client/Server
 Home-page: https://github.com/imgurbot12/pydns
 Author: Andrew Scott
 Author-email: imgurbot12@gmail.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `pydns3-0.0.8/pydns3.egg-info/SOURCES.txt` & `pydns3-0.0.9/pydns3.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pydns3-0.0.8/setup.py` & `pydns3-0.0.9/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup, find_packages
 
 with open('README.md', 'r') as f:
     readme = f.read()
 
 setup(
     name='pydns3',
-    version='0.0.8',
+    version='0.0.9',
     license='MIT',
     packages=find_packages(),
     url='https://github.com/imgurbot12/pydns',
     author='Andrew Scott',
     author_email='imgurbot12@gmail.com',
     description='Simple Python DNS Library. DNS Packet-Parsing/Client/Server',
     python_requires='>=3.7',
```

