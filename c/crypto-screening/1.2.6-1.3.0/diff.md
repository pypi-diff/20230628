# Comparing `tmp/crypto-screening-1.2.6.tar.gz` & `tmp/crypto-screening-1.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "crypto-screening-1.2.6.tar", last modified: Tue Jun 27 13:28:14 2023, max compression
+gzip compressed data, was "crypto-screening-1.3.0.tar", last modified: Wed Jun 28 10:30:21 2023, max compression
```

## Comparing `crypto-screening-1.2.6.tar` & `crypto-screening-1.3.0.tar`

### file list

```diff
@@ -1,35 +1,35 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 13:28:14.515418 crypto-screening-1.2.6/
--rw-rw-rw-   0        0        0       98 2023-06-27 13:28:14.000000 crypto-screening-1.2.6/MANIFEST.in
--rw-rw-rw-   0        0        0     2085 2023-06-27 13:28:14.515418 crypto-screening-1.2.6/PKG-INFO
--rw-rw-rw-   0        0        0     1264 2023-06-23 16:52:27.000000 crypto-screening-1.2.6/README.md
--rw-rw-rw-   0        0        0    12920 2023-06-23 16:52:27.000000 crypto-screening-1.2.6/build.py
-drwxrwxrwx   0        0        0        0 2023-06-27 13:28:14.495418 crypto-screening-1.2.6/crypto_screening/
--rw-rw-rw-   0        0        0     6694 2023-06-23 16:52:27.000000 crypto-screening-1.2.6/crypto_screening/base.py
-drwxrwxrwx   0        0        0        0 2023-06-27 13:28:14.514419 crypto-screening-1.2.6/crypto_screening/collect/
--rw-rw-rw-   0        0        0    17317 2023-06-27 13:26:05.000000 crypto-screening-1.2.6/crypto_screening/collect/assets.py
--rw-rw-rw-   0        0        0      496 2023-06-27 10:17:11.000000 crypto-screening-1.2.6/crypto_screening/collect/document.py
--rw-rw-rw-   0        0        0     4056 2023-06-27 13:26:48.000000 crypto-screening-1.2.6/crypto_screening/collect/exchanges.py
--rw-rw-rw-   0        0        0     8370 2023-06-27 10:25:51.000000 crypto-screening-1.2.6/crypto_screening/collect/screeners.py
--rw-rw-rw-   0        0        0    17997 2023-06-27 13:27:39.000000 crypto-screening-1.2.6/crypto_screening/collect/symbols.py
--rw-rw-rw-   0        0        0    12447 2023-06-25 20:15:20.000000 crypto-screening-1.2.6/crypto_screening/dataset.py
--rw-rw-rw-   0        0        0      869 2023-06-27 10:20:56.000000 crypto-screening-1.2.6/crypto_screening/document.py
--rw-rw-rw-   0        0        0      258 2023-06-25 14:21:21.000000 crypto-screening-1.2.6/crypto_screening/exchanges.py
--rw-rw-rw-   0        0        0      180 2023-06-23 16:52:27.000000 crypto-screening-1.2.6/crypto_screening/hints.py
--rw-rw-rw-   0        0        0     2665 2023-06-23 16:52:27.000000 crypto-screening-1.2.6/crypto_screening/interval.py
--rw-rw-rw-   0        0        0    32476 2023-06-25 20:34:03.000000 crypto-screening-1.2.6/crypto_screening/ohlcv.py
--rw-rw-rw-   0        0        0    24555 2023-06-25 15:03:52.000000 crypto-screening-1.2.6/crypto_screening/orderbook.py
--rw-rw-rw-   0        0        0     2378 2023-06-27 10:23:45.000000 crypto-screening-1.2.6/crypto_screening/process.py
--rw-rw-rw-   0        0        0    31848 2023-06-27 09:29:28.000000 crypto-screening-1.2.6/crypto_screening/screener.py
--rw-rw-rw-   0        0        0     9894 2023-06-25 16:31:01.000000 crypto-screening-1.2.6/crypto_screening/symbols.py
--rw-rw-rw-   0        0        0     3845 2023-06-27 09:22:00.000000 crypto-screening-1.2.6/crypto_screening/validate.py
-drwxrwxrwx   0        0        0        0 2023-06-27 13:28:14.510418 crypto-screening-1.2.6/crypto_screening.egg-info/
--rw-rw-rw-   0        0        0     2085 2023-06-27 13:28:14.000000 crypto-screening-1.2.6/crypto_screening.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      812 2023-06-27 13:28:14.000000 crypto-screening-1.2.6/crypto_screening.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 13:28:14.000000 crypto-screening-1.2.6/crypto_screening.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       88 2023-06-27 13:28:14.000000 crypto-screening-1.2.6/crypto_screening.egg-info/requires.txt
--rw-rw-rw-   0        0        0       17 2023-06-27 13:28:14.000000 crypto-screening-1.2.6/crypto_screening.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      652 2023-06-27 13:28:14.000000 crypto-screening-1.2.6/pyproject.toml
--rw-rw-rw-   0        0        0       92 2023-06-27 07:30:41.000000 crypto-screening-1.2.6/requirements-dev.txt
--rw-rw-rw-   0        0        0       64 2023-06-23 16:55:08.000000 crypto-screening-1.2.6/requirements.txt
--rw-rw-rw-   0        0        0       42 2023-06-27 13:28:14.516419 crypto-screening-1.2.6/setup.cfg
--rw-rw-rw-   0        0        0     1579 2023-06-27 13:28:05.000000 crypto-screening-1.2.6/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:30:21.903037 crypto-screening-1.3.0/
+-rw-rw-rw-   0        0        0       98 2023-06-28 10:30:21.000000 crypto-screening-1.3.0/MANIFEST.in
+-rw-rw-rw-   0        0        0     2085 2023-06-28 10:30:21.903037 crypto-screening-1.3.0/PKG-INFO
+-rw-rw-rw-   0        0        0     1264 2023-06-23 16:52:27.000000 crypto-screening-1.3.0/README.md
+-rw-rw-rw-   0        0        0    12920 2023-06-23 16:52:27.000000 crypto-screening-1.3.0/build.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:30:21.853418 crypto-screening-1.3.0/crypto_screening/
+-rw-rw-rw-   0        0        0     6694 2023-06-23 16:52:27.000000 crypto-screening-1.3.0/crypto_screening/base.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:30:21.902008 crypto-screening-1.3.0/crypto_screening/collect/
+-rw-rw-rw-   0        0        0    17317 2023-06-27 13:26:05.000000 crypto-screening-1.3.0/crypto_screening/collect/assets.py
+-rw-rw-rw-   0        0        0      496 2023-06-27 10:17:11.000000 crypto-screening-1.3.0/crypto_screening/collect/document.py
+-rw-rw-rw-   0        0        0     4056 2023-06-27 13:26:48.000000 crypto-screening-1.3.0/crypto_screening/collect/exchanges.py
+-rw-rw-rw-   0        0        0     8376 2023-06-28 09:37:02.000000 crypto-screening-1.3.0/crypto_screening/collect/screeners.py
+-rw-rw-rw-   0        0        0    17997 2023-06-27 13:27:39.000000 crypto-screening-1.3.0/crypto_screening/collect/symbols.py
+-rw-rw-rw-   0        0        0    12447 2023-06-25 20:15:20.000000 crypto-screening-1.3.0/crypto_screening/dataset.py
+-rw-rw-rw-   0        0        0      869 2023-06-27 10:20:56.000000 crypto-screening-1.3.0/crypto_screening/document.py
+-rw-rw-rw-   0        0        0      258 2023-06-25 14:21:21.000000 crypto-screening-1.3.0/crypto_screening/exchanges.py
+-rw-rw-rw-   0        0        0      180 2023-06-23 16:52:27.000000 crypto-screening-1.3.0/crypto_screening/hints.py
+-rw-rw-rw-   0        0        0     2665 2023-06-23 16:52:27.000000 crypto-screening-1.3.0/crypto_screening/interval.py
+-rw-rw-rw-   0        0        0    32971 2023-06-28 09:48:08.000000 crypto-screening-1.3.0/crypto_screening/ohlcv.py
+-rw-rw-rw-   0        0        0    25246 2023-06-28 10:22:01.000000 crypto-screening-1.3.0/crypto_screening/orderbook.py
+-rw-rw-rw-   0        0        0     2378 2023-06-27 10:23:45.000000 crypto-screening-1.3.0/crypto_screening/process.py
+-rw-rw-rw-   0        0        0    32975 2023-06-28 09:52:38.000000 crypto-screening-1.3.0/crypto_screening/screener.py
+-rw-rw-rw-   0        0        0     9894 2023-06-25 16:31:01.000000 crypto-screening-1.3.0/crypto_screening/symbols.py
+-rw-rw-rw-   0        0        0     3845 2023-06-27 09:22:00.000000 crypto-screening-1.3.0/crypto_screening/validate.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:30:21.870045 crypto-screening-1.3.0/crypto_screening.egg-info/
+-rw-rw-rw-   0        0        0     2085 2023-06-28 10:30:21.000000 crypto-screening-1.3.0/crypto_screening.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      812 2023-06-28 10:30:21.000000 crypto-screening-1.3.0/crypto_screening.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 10:30:21.000000 crypto-screening-1.3.0/crypto_screening.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       94 2023-06-28 10:30:21.000000 crypto-screening-1.3.0/crypto_screening.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       17 2023-06-28 10:30:21.000000 crypto-screening-1.3.0/crypto_screening.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      652 2023-06-28 10:30:21.000000 crypto-screening-1.3.0/pyproject.toml
+-rw-rw-rw-   0        0        0       99 2023-06-28 09:56:21.000000 crypto-screening-1.3.0/requirements-dev.txt
+-rw-rw-rw-   0        0        0       64 2023-06-23 16:55:08.000000 crypto-screening-1.3.0/requirements.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 10:30:21.904006 crypto-screening-1.3.0/setup.cfg
+-rw-rw-rw-   0        0        0     1579 2023-06-28 10:28:27.000000 crypto-screening-1.3.0/setup.py
```

### Comparing `crypto-screening-1.2.6/PKG-INFO` & `crypto-screening-1.3.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: crypto-screening
-Version: 1.2.6
+Version: 1.3.0
 Summary: A software for automatically recording real-time crypto exchanges and pairs OHLCV and Orderbook rates.
 Home-page: https://github.com/Shahaf-F-S/crypto-screening
 Author: Shahaf Frank-Shapir
 Author-email: shahaffrs@gmail.com
 License: MIT
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `crypto-screening-1.2.6/README.md` & `crypto-screening-1.3.0/README.md`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/build.py` & `crypto-screening-1.3.0/build.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/crypto_screening/base.py` & `crypto-screening-1.3.0/crypto_screening/base.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/crypto_screening/collect/assets.py` & `crypto-screening-1.3.0/crypto_screening/collect/assets.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/crypto_screening/collect/exchanges.py` & `crypto-screening-1.3.0/crypto_screening/collect/exchanges.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/crypto_screening/collect/screeners.py` & `crypto-screening-1.3.0/crypto_screening/collect/screeners.py`

 * *Files 0% similar despite different names*

```diff
@@ -197,15 +197,15 @@
 
     :return: A list the live create_screeners.
     """
 
     return [
         screener for screener in screeners
         if (
-            screener.running and (
+                screener.screening and (
                 isinstance(screener, BaseMultiScreener) or
                 len(screener.market) > 0
             )
         )
     ]
 # end live_screeners
```

### Comparing `crypto-screening-1.2.6/crypto_screening/collect/symbols.py` & `crypto-screening-1.3.0/crypto_screening/collect/symbols.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/crypto_screening/dataset.py` & `crypto-screening-1.3.0/crypto_screening/dataset.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/crypto_screening/document.py` & `crypto-screening-1.3.0/crypto_screening/document.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/crypto_screening/interval.py` & `crypto-screening-1.3.0/crypto_screening/interval.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/crypto_screening/ohlcv.py` & `crypto-screening-1.3.0/crypto_screening/ohlcv.py`

 * *Files 2% similar despite different names*

```diff
@@ -430,19 +430,19 @@
 
         return asyncio.run(self.async_get_market())
     # end get_market
 
     async def async_run_loop(self) -> None:
         """Runs the processes of price screening."""
 
-        self.running = True
+        self.screening = True
 
         delay = interval_to_total_time(self.interval).seconds
 
-        while self.running:
+        while self.screening:
             start = time.time()
 
             try:
                 await self.async_update_market()
 
             except Exception as e:
                 self.terminate()
@@ -456,15 +456,15 @@
 
             if delay:
                 time.sleep(max([delay - (end - start), 0]))
             # end if
         # end while
     # end async_run
 
-    def run_loop(self) -> None:
+    def screening_loop(self) -> None:
         """Runs the process of the price screening."""
 
         task = self.async_run_loop()
 
         try:
             loop = asyncio.new_event_loop()
 
@@ -473,15 +473,15 @@
             if not loop.is_running():
                 loop.run_forever()
             # end if
 
         except RuntimeError:
             asyncio.run(task)
         # end try
-    # end run_loop
+    # end screening_loop
 
     def run_new_loop(self) -> None:
         """Runs the process of the price screening."""
 
         task = self.async_run_loop()
 
         try:
@@ -492,15 +492,15 @@
             if not loop.is_running():
                 loop.run_forever()
             # end if
 
         except RuntimeError:
             asyncio.run(task)
         # end try
-    # end run_loop
+    # end screening_loop
 
     def stop(self) -> None:
         """Stops the screening process."""
 
         super().stop()
 
         if self.task is not None:
@@ -992,55 +992,70 @@
         super().terminate()
 
         for screener in self.screeners:
             screener.terminate()
         # end for
     # end terminate
 
+    def start_screening(
+            self,
+            save: Optional[bool] = True,
+            timeout: Optional[Union[Number, dt.timedelta, dt.datetime]] = None
+    ) -> None:
+        """
+        Starts the screening process.
+
+        :param save: The value to save the data.
+        :param timeout: The valur to add a timeout to the process.
+        """
+
+        if self.screening:
+            warnings.warn(f"Screening process of {self} is already running.")
+
+            return
+        # end if
+
+        for screener in self.screeners:
+            screener.run(
+                timeout=timeout, wait=False,
+                block=False, save=save
+            )
+        # end for
+    # end start_screening
+
     def run(
             self,
-            start: Optional[bool] = True,
+            screen: Optional[bool] = True,
             save: Optional[bool] = True,
             block: Optional[bool] = False,
             update: Optional[bool] = True,
             wait: Optional[Union[bool, Number, dt.timedelta, dt.datetime]] = False,
             timeout: Optional[Union[Number, dt.timedelta, dt.datetime]] = None
     ) -> None:
         """
         Runs the process of the price screening.
 
-        :param start: The value to start the screening.
+        :param screen: The value to start the screening.
         :param save: The value to save the data.
         :param wait: The value to wait after starting to run the process.
         :param block: The value to block the execution.
         :param update: The value to update the screeners.
         :param timeout: The valur to add a timeout to the process.
         """
 
-        if self.running:
-            warnings.warn(f"Screener is already running.")
-
-            return
-        # end if
-
-        if start:
-            for screener in self.screeners:
-                screener.run(
-                    timeout=timeout, wait=False,
-                    block=False, save=save
-                )
-            # end for
+        if screen:
+            self.start_screening(save=save, timeout=timeout)
         # end if
 
         super().run(
-            start=start, save=save, block=block,
+            screen=False, save=save, block=block,
             update=update, wait=wait, timeout=timeout
         )
     # end run
-# end Screener
+# end MarketOHLCVScreener
 
 Market = Dict[str, Dict[str, pd.DataFrame]]
 
 def market_ohlcv_screener(
         data: Dict[str, Iterable[str]],
         interval: Optional[str] = None,
         delay: Optional[Union[Number, dt.timedelta]] = None,
```

### Comparing `crypto-screening-1.2.6/crypto_screening/orderbook.py` & `crypto-screening-1.3.0/crypto_screening/orderbook.py`

 * *Files 4% similar despite different names*

```diff
@@ -223,15 +223,15 @@
     # end start
 # end ExchangeFeed
 
 def add_feeds(
         handler: FeedHandler,
         data: Dict[str, Iterable[str]],
         fixed: Optional[bool] = False,
-        amount: Optional[int] = 5,
+        amount: Optional[int] = 50,
         separator: Optional[str] = None,
         parameters: Optional[Union[Dict[str, Dict[str, Any]], Dict[str, Any]]] = None
 ) -> None:
     """
     Adds the symbols to the handler for each exchange.
 
     :param handler: The handler object.
@@ -349,19 +349,19 @@
     modifiers.excluded.extend(
         ['screening_parameters', 'feeds_parameters', 'handler']
     )
 
     __slots__ = (
         "handler", 'amount',
         "loop", "limited", "feeds_parameters",
-        "screening_parameters", 'refresh'
+        "running_parameters", 'refresh'
     )
 
-    DELAY = 10
-    AMOUNT = 50
+    DELAY = 5
+    AMOUNT = 20
 
     REFRESH = dt.timedelta(minutes=5)
 
     screeners: List[OrderbookScreener]
     recorder: MarketOrderbookRecorder
 
     COLUMNS = MarketOrderbookRecorder.COLUMNS
@@ -408,15 +408,15 @@
         self.refresh = refresh
 
         self.screeners[:] = list(screeners or []) or self.create_screeners()
 
         self.loop: Optional[asyncio.AbstractEventLoop] = None
 
         self.feeds_parameters: Optional[Dict[str, Any]] = None
-        self.screening_parameters: Optional[Dict[str, Any]] = None
+        self.running_parameters: Optional[Dict[str, Any]] = None
     # end __init__
 
     def create_screener(
             self,
             symbol: str,
             exchange: str,
             location: Optional[str] = None,
@@ -541,26 +541,26 @@
 
         self.add_feeds(**self.feeds_parameters)
     # end refresh
 
     def rerun(self) -> None:
         """Refreshes the process."""
 
-        if self.screening_parameters is None:
+        if self.running_parameters is None:
             warnings.warn(
                 "Cannot rerun as there was "
                 "no initial process to repeat."
             )
 
             return
         # end if
 
         self.terminate()
         self.refresh_feeds()
-        self.run(**self.screening_parameters)
+        self.run(**self.running_parameters)
     # end rerun
 
     def orderbook(self, exchange: str, symbol: str) -> pd.DataFrame:
         """
         Returns the market data of the symbol from the exchange.
 
         :param exchange: The source name of the exchange.
@@ -568,15 +568,15 @@
 
         :return: The dataset of the spread data.
         """
 
         return self.recorder.orderbook(exchange=exchange, symbol=symbol)
     # end orderbook
 
-    def run_loop(
+    def screening_loop(
             self,
             start: Optional[bool] = True,
             loop: Optional[asyncio.AbstractEventLoop] = None
     ) -> None:
         """
         Runs the process of the price screening.
 
@@ -588,25 +588,25 @@
             loop = asyncio.new_event_loop()
         # end if
 
         self.loop = loop
 
         asyncio.set_event_loop(loop)
 
-        self.running = True
+        self.screening = True
 
         for screener in self.screeners:
-            screener.running = True
+            screener.screening = True
         # end for
 
         self.handler.run(
             start_loop=start and (not loop.is_running()),
             install_signal_handlers=False
         )
-    # end run_loop
+    # end screening_loop
 
     def saving_loop(self) -> None:
         """Runs the process of the price screening."""
 
         for screener in self.screeners:
             screener.saving_process = threading.Thread(
                 target=screener.saving_loop
@@ -625,15 +625,15 @@
         if isinstance(refresh, dt.timedelta):
             refresh = refresh.total_seconds()
         # end if
 
         start = time.time()
 
         while self.updating:
-            if self.running:
+            if self.screening:
                 self.update()
 
                 current = time.time()
 
                 if refresh and ((current - start) >= refresh):
                     self.rerun()
 
@@ -664,15 +664,15 @@
     # end update
 
     def stop(self) -> None:
         """Stops the data handling loop."""
 
         super().stop()
 
-        self.running = False
+        self.screening = False
 
         if self.loop is None:
             return
         # end if
 
         if (
             self.updating and
@@ -683,14 +683,16 @@
 
             self.update_process = None
         # end if
 
         self.loop: asyncio.AbstractEventLoop
 
         async def stop() -> None:
+            """Stops the handler."""
+
             self.handler.stop(self.loop)
             self.handler.close(self.loop)
         # end stop
 
         self.loop.create_task(stop())
 
         for task in asyncio.all_tasks(self.loop):
@@ -698,59 +700,80 @@
         # end for
 
         self.loop = None
 
         self.handler.running = False
     # end stop
 
+    def start_screening(
+            self,
+            start: Optional[bool] = True,
+            loop: Optional[asyncio.AbstractEventLoop] = None
+    ) -> None:
+        """
+        Starts the screening process.
+
+        :param start: The value to start the loop.
+        :param loop: The event loop.
+        """
+
+        if self.screening:
+            warnings.warn(f"Timeout process of {self} is already running.")
+
+            return
+        # end if
+
+        self.screening_process = threading.Thread(
+            target=lambda: self.screening_loop(loop=loop, start=start)
+        )
+
+        self.screening_process.start()
+    # end start_screening
+
     def run(
             self,
             save: Optional[bool] = True,
             block: Optional[bool] = False,
+            update: Optional[bool] = True,
+            screen: Optional[bool] = True,
+            loop: Optional[asyncio.AbstractEventLoop] = None,
             wait: Optional[Union[bool, Number, dt.timedelta, dt.datetime]] = False,
             timeout: Optional[Union[Number, dt.timedelta, dt.datetime]] = None,
-            update: Optional[bool] = True,
-            start: Optional[bool] = True,
-            loop: Optional[asyncio.AbstractEventLoop] = None
     ) -> None:
         """
         Runs the program.
 
         :param save: The value to save the data.
         :param wait: The value to wait after starting to run the process.
         :param block: The value to block the execution.
-        :param timeout: The valur to add a timeout to the process.
+        :param timeout: The valur to add a start_timeout to the process.
         :param update: The value to update the screeners.
-        :param start: The value to start the loop.
+        :param screen: The value to start the loop.
         :param loop: The event loop.
 
-        :return: The timeout process.
+        :return: The start_timeout process.
         """
 
-        if self.running:
-            warnings.warn(f"Screener is already running.")
-
-            return
-        # end if
+        self.running_parameters = dict(
+            save=save, block=block, update=update, screen=screen,
+            loop=loop, wait=wait, timeout=timeout
+        )
 
         if not block:
-            self.screening_process = threading.Thread(
-                target=lambda: self.run_loop(loop=loop, start=start)
-            )
-
-            self.screening_process.start()
-
-        else:
-            self.run_loop(loop=loop, start=start)
+            self.start_screening(loop=loop, start=screen)
         # end if
 
         super().run(
-            start=False, block=False, wait=wait,
+            screen=False, block=False, wait=wait,
             timeout=timeout, update=update, save=save
         )
+
+        if block:
+            self.screening_loop(loop=loop, start=screen)
+        # end if
     # end run
 # end MarketScreener
 
 def market_orderbook_recorder(data: Dict[str, Iterable[str]]) -> MarketOrderbookRecorder:
     """
     Creates the market recorder object for the data.
```

### Comparing `crypto-screening-1.2.6/crypto_screening/process.py` & `crypto-screening-1.3.0/crypto_screening/process.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/crypto_screening/screener.py` & `crypto-screening-1.3.0/crypto_screening/screener.py`

 * *Files 6% similar despite different names*

```diff
@@ -34,60 +34,73 @@
     "wait_for_dynamic_update",
     "wait_for_dynamic_initialization",
     "BaseMultiScreener",
     "create_market_dataframe",
     "MarketRecorder",
     "structure_screeners_datasets",
     "structure_screener_datasets",
-    "validate_market"
+    "validate_market",
+    "gather_screeners"
 ]
 
 class WaitingState(BaseModel):
     """A class to represent the waiting state of screener objects."""
 
     modifiers = Modifiers(hidden=["screeners"], properties=["time"])
 
-    __slots__ = "screeners", "delay", "count", "canceled", "cancel"
+    __slots__ = (
+        "screeners", "delay", "count",
+        "canceled", "cancel", "start", "end"
+    )
 
     def __init__(
             self,
             screeners: Iterable,
-            delay: Number,
-            count: int,
-            canceled: bool,
+            start: dt.datetime,
+            end: dt.datetime,
+            stop: Optional[bool] = None,
+            delay: Optional[Number] = None,
+            count: Optional[int] = None,
+            canceled: Optional[bool] = None,
             cancel: Optional[Union[Number, dt.timedelta, dt.datetime]] = None
     ) -> None:
         """
         Defines the class attributes.
 
         :param screeners: The screener objects.
+        :param start: The start time.
+        :param end: The end time.
+        :param stop: The stop value.
         :param delay: The waiting delay.
         :param count: The iterations count.
         :param canceled: The value for the waiting being canceled.
         :param cancel: The time to cancel the waiting.
         """
 
         self.screeners: Iterable[Union[BaseScreener, BaseMultiScreener]] = screeners
 
-        self.delay = delay
+        self.start = start
+        self.end = end
         self.cancel = cancel
-        self.count = count
 
-        self.canceled = canceled
+        self.stop = stop or False
+        self.canceled = canceled or False
+        self.delay = delay or 0
+        self.count = count or 0
     # end __init__
 
     @property
     def time(self) -> dt.timedelta:
         """
         Returns the amount of waited time.
 
         :return: The waiting time.
         """
 
-        return dt.timedelta(seconds=self.delay * self.count)
+        return self.end - self.start
     # end time
 # end WaitingState
 
 class DataCollector(BaseModel, metaclass=ABCMeta):
     """A class to represent an abstract parent class of data collectors."""
 
     modifiers = Modifiers(**BaseModel.modifiers)
@@ -97,15 +110,15 @@
             'saving_process', 'update_process'
         ]
     )
 
     __slots__ = (
         'screening_process', 'timeout_process',
         'saving_process', 'update_process',
-        "location", "cancel", "delay", "market"
+        'location', 'cancel', 'delay', 'market'
     )
 
     LOCATION = "datasets"
 
     DELAY = 0.0
     CANCEL = 0
 
@@ -132,15 +145,15 @@
         # end if
 
         self.cancel = cancel
         self.delay = delay
 
         self.location = location or self.LOCATION
 
-        self.running = False
+        self.screening = False
         self.block = False
         self.saving = False
         self.updating = False
 
         self.screening_process = None
         self.timeout_process = None
         self.saving_process = None
@@ -171,145 +184,148 @@
 
         :return: The value.
         """
 
         return self.block
     # end blocking
 
-    def run_loop(self) -> None:
+    def screening_loop(self) -> None:
         """Runs the process of the price screening."""
-    # end run_loop
+    # end screening_loop
 
     def saving_loop(self) -> None:
         """Runs the process of the price screening."""
     # end saving_loop
 
     def update_loop(self) -> None:
         """Updates the state of the screeners."""
     # end update_loop
 
     def wait_for_initialization(
             self,
-            delay: Optional[Union[Number, dt.timedelta]] = None,
-            once: Optional[bool] = False,
             stop: Optional[Union[bool, int]] = False,
+            delay: Optional[Union[Number, dt.timedelta]] = None,
             cancel: Optional[Union[Number, dt.timedelta, dt.datetime]] = None
     ) -> WaitingState:
         """
         Waits for all the create_screeners to update.
 
         :param delay: The delay for the waiting.
-        :param once: The value to get data only once.
         :param stop: The value to stop the screener objects.
         :param cancel: The time to cancel the waiting.
 
         :returns: The total delay.
         """
 
         self: Union[BaseScreener, BaseMultiScreener]
 
         return wait_for_initialization(
-            self, delay=delay, once=once,
-            stop=stop, cancel=cancel or self.cancel
+            self, delay=delay, stop=stop,
+            cancel=cancel or self.cancel
         )
     # end wait_for_initialization
 
     def wait_for_update(
             self,
-            delay: Optional[Union[Number, dt.timedelta]] = None,
-            once: Optional[bool] = False,
             stop: Optional[Union[bool, int]] = False,
+            delay: Optional[Union[Number, dt.timedelta]] = None,
             cancel: Optional[Union[Number, dt.timedelta, dt.datetime]] = None
     ) -> WaitingState:
         """
         Waits for all the create_screeners to update.
 
         :param delay: The delay for the waiting.
-        :param once: The value to get data only once.
         :param stop: The value to stop the screener objects.
         :param cancel: The time to cancel the waiting.
 
         :returns: The total delay.
         """
 
         self: Union[BaseScreener, BaseMultiScreener]
 
         return wait_for_update(
-            self, delay=delay, once=once,
-            stop=stop, cancel=cancel or self.cancel
+            self, delay=delay, stop=stop,
+            cancel=cancel or self.cancel
         )
     # end wait_for_update
 
-    def run(
-            self,
-            start: Optional[bool] = True,
-            save: Optional[bool] = True,
-            block: Optional[bool] = False,
-            update: Optional[bool] = True,
-            wait: Optional[Union[bool, Number, dt.timedelta, dt.datetime]] = False,
-            timeout: Optional[Union[Number, dt.timedelta, dt.datetime]] = None
-    ) -> None:
-        """
-        Runs the process of the price screening.
+    def start_blocking(self) -> None:
+        """Starts the blocking process."""
 
-        :param start: The value to start the screening.
-        :param save: The value to save the data.
-        :param wait: The value to wait after starting to run the process.
-        :param block: The value to block the execution.
-        :param update: The value to update the screeners.
-        :param timeout: The valur to add a timeout to the process.
-        """
+        if self.saving:
+            warnings.warn(f"Blocking process of {self} is already running.")
+        # end if
 
-        if self.running:
-            warnings.warn(f"Screener object {self} is already running.")
+        self.block = True
 
-            return self.screening_process
-        # end if
+        while self.blocking():
+            time.sleep(0.005)
+        # end while
+    # end start_blocking
 
-        if start:
-            self.running = True
+    def start_screening(self) -> None:
+        """Starts the screening process."""
 
-            self.screening_process = threading.Thread(
-                target=self.run_loop
-            )
+        if self.screening:
+            warnings.warn(f"Screening process of {self} is already running.")
 
-            self.screening_process.start()
+            return
         # end if
 
-        if save:
-            self.saving = True
+        self.screening = True
 
-            self.saving_process = threading.Thread(
-                target=self.saving_loop
-            )
+        self.screening_process = threading.Thread(
+            target=self.screening_loop
+        )
+
+        self.screening_process.start()
+    # end start_screening
+
+    def start_saving(self) -> None:
+        """Starts the saving process."""
 
-            self.saving_process.start()
+        if self.saving:
+            warnings.warn(f"Saving process of {self} is already running.")
         # end if
 
-        if update:
-            self.updating = True
+        self.saving = True
 
-            self.update_process = threading.Thread(
-                target=self.update_loop
-            )
+        self.saving_process = threading.Thread(
+            target=self.saving_loop
+        )
 
-            self.update_process.start()
-        # end if
+        self.saving_process.start()
+    # end start_saving
 
-        if timeout:
-            self.timeout(timeout)
+    def start_updating(self) -> None:
+        """Starts the updating process."""
+
+        if self.updating:
+            warnings.warn(f"Updating process of {self} is already running.")
         # end if
 
-        if block:
-            self.block = block
+        self.updating = True
 
-            while self.blocking():
-                pass
-            # end while
-        # end if
+        self.update_process = threading.Thread(
+            target=self.update_loop
+        )
+
+        self.update_process.start()
+    # end start_updating
+
+    def start_waiting(
+            self, wait: Union[Number, dt.timedelta, dt.datetime]
+    ) -> None:
+        """
+        Runs a waiting for the process.
+
+        :param wait: The duration of the start_timeout.
+
+        :return: The start_timeout process.
+        """
 
         if isinstance(wait, dt.datetime):
             wait = wait - dt.datetime.now()
         # end if
 
         if isinstance(wait, dt.timedelta):
             wait = wait.total_seconds()
@@ -317,61 +333,113 @@
 
         if isinstance(wait, bool) and wait:
             self.wait_for_initialization()
 
         elif isinstance(wait, (int, float)):
             time.sleep(wait)
         # end if
-    # end run
+    # end start_waiting
 
-    def timeout(
+    def start_timeout(
             self, duration: Union[Number, dt.timedelta, dt.datetime]
-    ) -> threading.Thread:
+    ) -> None:
         """
         Runs a timeout for the process.
 
-        :param duration: The duration of the timeout.
+        :param duration: The duration of the start_timeout.
 
-        :return: The timeout process.
+        :return: The start_timeout process.
         """
 
+        if (
+            isinstance(self.timeout_process, threading.Thread) and
+            self.timeout_process.is_alive()
+        ):
+            warnings.warn(f"Timeout process of {self} is already running.")
+
+            return
+        # end if
+
         if isinstance(duration, dt.datetime):
             duration = duration - dt.datetime.now()
         # end if
 
         if isinstance(duration, dt.timedelta):
             duration = duration.total_seconds()
         # end if
 
         self.timeout_process = threading.Thread(
             target=lambda: (time.sleep(duration), self.terminate())
         )
 
         self.timeout_process.start()
+    # end start_timeout
+
+    def run(
+            self,
+            screen: Optional[bool] = True,
+            save: Optional[bool] = True,
+            block: Optional[bool] = False,
+            update: Optional[bool] = True,
+            wait: Optional[Union[bool, Number, dt.timedelta, dt.datetime]] = False,
+            timeout: Optional[Union[Number, dt.timedelta, dt.datetime]] = None
+    ) -> None:
+        """
+        Runs the process of the price screening.
 
-        return self.timeout_process
-    # end timeout
+        :param screen: The value to start the screening.
+        :param save: The value to save the data.
+        :param wait: The value to wait after starting to run the process.
+        :param block: The value to block the execution.
+        :param update: The value to update the screeners.
+        :param timeout: The valur to add a start_timeout to the process.
+        """
+
+        if screen:
+            self.start_screening()
+        # end if
+
+        if save:
+            self.start_saving()
+        # end if
+
+        if update:
+            self.start_updating()
+        # end if
+
+        if timeout:
+            self.start_timeout(timeout)
+        # end if
+
+        if wait:
+            self.start_waiting(wait)
+        # end if
+
+        if block:
+            self.start_blocking()
+        # end if
+    # end run
 
     def terminate(self) -> None:
         """Stops the trading process."""
 
         self.stop()
     # end terminate
 
     def stop(self) -> None:
         """Stops the screening process."""
 
         if (
-            self.running and
+            self.screening and
             isinstance(self.screening_process, threading.Thread) and
             self.screening_process.is_alive()
         ):
             self.screening_process = None
 
-            self.running = False
+            self.screening = False
         # end if
 
         if (
             self.saving and
             isinstance(self.saving_process, threading.Thread) and
             self.saving_process.is_alive()
         ):
@@ -382,25 +450,25 @@
 
         if self.block:
             self.block = False
         # end if
     # end stop
 # end DataCollector
 
-def create_market_dataframe(columns: Iterable[str]) -> pd.DataFrame:
+def create_market_dataframe(columns: Optional[Iterable[str]] = None) -> pd.DataFrame:
     """
     Creates a dataframe for the order book data.
 
     :param columns: The dataset columns.
 
     :return: The dataframe.
     """
 
     market = pd.DataFrame(
-        {column: [] for column in columns}, index=[]
+        {column: [] for column in columns or []}, index=[]
     )
     market.index.name = DATE_TIME
 
     return market
 # end create_market_dataframe
 
 class BaseScreener(DataCollector):
@@ -450,30 +518,42 @@
         :param exchange: The exchange to get source data from.
         :param location: The saving location for the data.
         :param delay: The delay for the process.
         :param cancel: The cancel time for the loops.
         :param market: The data for the market.
         """
 
-        super().__init__(
-            location=location, cancel=cancel, delay=delay
-        )
-
-        self.exchange = exchange
+        super().__init__(location=location, cancel=cancel, delay=delay)
 
-        self.symbol = self.validate_symbol(exchange=exchange, symbol=symbol)
+        self.exchange = self.validate_exchange(exchange=exchange)
+        self.symbol = self.validate_symbol(
+            exchange=self.exchange, symbol=symbol
+        )
 
         if market is None:
-            market = create_market_dataframe(())
+            market = create_market_dataframe()
         # end if
 
         self.market = market
     # end __init__
 
     @staticmethod
+    def validate_exchange(exchange: str) -> str:
+        """
+        Validates the symbol value.
+
+        :param exchange: The exchange name.
+
+        :return: The validates symbol.
+        """
+
+        return validate_exchange(exchange=exchange)
+    # end validate_exchange
+
+    @staticmethod
     def validate_symbol(exchange: str, symbol: Any) -> str:
         """
         Validates the symbol value.
 
         :param exchange: The exchange name.
         :param symbol: The name of the symbol.
 
@@ -552,20 +632,20 @@
 
             self.save_dataset()
 
             end = time.time()
 
             time.sleep(max(delay - (end - start), 1))
         # end while
-    # end run_loop
+    # end saving_loop
 # end BaseScreener
 
 Market = Dict[str, Dict[str, pd.DataFrame]]
 
-def validate_market(data: Any) -> Dict[str, Iterable[str]]:
+def validate_market(data: Any) -> Market:
     """
     Validates the data.
 
     :param data: The data to validate.
 
     :return: The valid data.
     """
@@ -575,34 +655,35 @@
     # end if
 
     try:
         if not isinstance(data, dict):
             raise ValueError
         # end if
 
-        new_data = {}
-
-        for key, values in data.items():
+        for exchange, values in data.items():
             if not (
-                isinstance(key, str) and
-                all(isinstance(value, str) for value in values)
+                isinstance(exchange, str) and
+                isinstance(values, dict) and
+                all(
+                    isinstance(symbol, str) and
+                    isinstance(dataset, pd.DataFrame)
+                    for symbol, dataset in values.items()
+                )
             ):
                 raise ValueError
             # end if
         # end for
 
     except (TypeError, ValueError):
         raise ValueError(
-            f"Exchanges data must be a dictionary of "
-            f"exchange names as keys and iterables of "
-            f"symbol names as values, not {data}."
+            f"Data must be of type {Market}, not: {data}."
         )
     # end try
 
-    return new_data
+    return data
 # end validate_market
 
 class MarketRecorder(BaseModel):
     """
     A class to represent a crypto data feed recorder.
     This object passes the record method to the handler object to record
     the data fetched by the handler.
@@ -631,22 +712,29 @@
     def __init__(self, market: Optional[Market] = None) -> None:
         """
         Defines the class attributes.
 
         :param market: The object to fill with the crypto feed record.
         """
 
-        if market is None:
-            market = {}
-        # end if
+        self.market = self.validate_market(data=market)
+    # end __init__
 
-        validate_market(data=market)
+    @staticmethod
+    def validate_market(data: Any) -> Market:
+        """
+        Validates the data.
 
-        self.market: Market = market
-    # end __init__
+        :param data: The data to validate.
+
+        :return: The valid data.
+        """
+
+        return validate_market(data=data)
+    # end validate_market
 
     def structure(self) -> Dict[str, List[str]]:
         """
         Returns the structure of the market data.
 
         :return: The structure of the market.
         """
@@ -838,261 +926,244 @@
             )
         # end for
 
         multi_threaded_call(callers=callers)
     # end load_datasets
 # end BaseScreener
 
+def gather_screeners(
+        screeners: Iterable[Union[BaseScreener, BaseMultiScreener]]
+) -> List[BaseScreener]:
+    """
+    Gathers the base screeners.
+
+    :param screeners: The screeners to process.
+
+    :return: The gathered base screeners.
+    """
+
+    checked_screeners = []
+
+    for screener in screeners:
+        if isinstance(screener, BaseScreener):
+            checked_screeners.append(screener)
+
+        elif isinstance(screener, BaseMultiScreener):
+            checked_screeners.extend(screener.screeners)
+        # end if
+    # end for
+
+    return checked_screeners
+# end gather_screeners
+
 def wait_for_dynamic_initialization(
         screeners: Iterable[Union[BaseScreener, BaseMultiScreener]],
+        stop: Optional[bool] = None,
         delay: Optional[Union[Number, dt.timedelta]] = None,
-        once: Optional[bool] = False,
-        stop: Optional[Union[bool, int]] = False,
         cancel: Optional[Union[Number, dt.timedelta, dt.datetime]] = None
 ) -> WaitingState:
     """
     Waits for all the create_screeners to update.
 
     :param screeners: The create_screeners to wait for them to update.
     :param delay: The delay for the waiting.
-    :param once: The value to get data only once.
     :param stop: The value to stop the screener objects.
     :param cancel: The time to cancel the waiting.
 
     :returns: The total delay.
     """
 
-    if cancel == 0:
-        cancel = None
+    if cancel is None:
+        cancel = 0
     # end if
 
-    if isinstance(cancel, (int, float)):
-        cancel = dt.timedelta(seconds=cancel)
+    if delay is None:
+        delay = 0
     # end if
 
-    current_time = dt.datetime.now()
-
-    if isinstance(cancel, dt.timedelta):
-        cancel = current_time + cancel
+    if isinstance(cancel, (int, float)):
+        cancel = dt.timedelta(seconds=cancel)
     # end if
 
     if isinstance(delay, dt.timedelta):
         delay = delay.total_seconds()
     # end if
 
-    delay = delay or 0
+    start = dt.datetime.now()
     count = 0
+    canceled = False
 
-    saved_screeners = screeners
-    checked_screeners = []
-
-    while True:
-        for screener in saved_screeners:
-            if isinstance(screener, BaseScreener):
-                checked_screeners.append(screener)
+    while screeners:
+        checked_screeners = gather_screeners(screeners=screeners)
 
-            elif isinstance(screener, BaseMultiScreener):
-                checked_screeners.extend(screener.screeners)
-            # end if
-        # end for
+        if all(
+            len(screener.market) > 0
+            for screener in checked_screeners
+        ):
+            break
+        # end if
 
         if (
-            (
-                not any(
-                    len(screener.market) == 0
-                    for screener in checked_screeners
-                )
-            ) or
-            (
-                (cancel is not None) and
-                ((current_time := dt.datetime.now()) > cancel)
-            )
+            isinstance(cancel, dt.timedelta) and
+            (canceled := ((dt.datetime.now() - start) > cancel))
         ):
             break
         # end if
 
         count += 1
 
-        if isinstance(delay, (int, float)) and (count > 0):
+        if isinstance(delay, (int, float)):
             time.sleep(delay)
         # end if
     # end while
 
-    if stop and ((stop == count) or once):
-        for screener in checked_screeners:
+    if stop:
+        for screener in screeners:
             screener.stop()
         # end for
     # end if
 
     return WaitingState(
-        screeners=screeners, delay=delay, count=count,
-        cancel=cancel, canceled=(cancel is None) or (current_time > cancel)
+        screeners=screeners, delay=delay,
+        count=count, end=dt.datetime.now(), start=start,
+        cancel=cancel, canceled=canceled
     )
 # end wait_for_dynamic_initialization
 
 def wait_for_initialization(
         *screeners: Union[BaseScreener, BaseMultiScreener],
+        stop: Optional[bool] = False,
         delay: Optional[Union[Number, dt.timedelta]] = None,
-        once: Optional[bool] = False,
-        stop: Optional[Union[bool, int]] = False,
         cancel: Optional[Union[Number, dt.timedelta, dt.datetime]] = None
 ) -> WaitingState:
     """
     Waits for all the create_screeners to update.
 
     :param screeners: The create_screeners to wait for them to update.
     :param delay: The delay for the waiting.
-    :param once: The value to get data only once.
     :param stop: The value to stop the screener objects.
     :param cancel: The time to cancel the waiting.
 
     :returns: The total delay.
     """
 
     return wait_for_dynamic_initialization(
-        screeners, delay=delay, once=once,
+        screeners, delay=delay,
         stop=stop, cancel=cancel
     )
 # end wait_for_initialization
 
 def wait_for_dynamic_update(
         screeners: Iterable[Union[BaseScreener, BaseMultiScreener]],
+        stop: Optional[bool] = False,
         delay: Optional[Union[Number, dt.timedelta]] = None,
-        once: Optional[bool] = False,
-        stop: Optional[Union[bool, int]] = False,
         cancel: Optional[Union[Number, dt.timedelta, dt.datetime]] = None
 ) -> WaitingState:
     """
     Waits for all the create_screeners to update.
 
     :param screeners: The create_screeners to wait for them to update.
     :param delay: The delay for the waiting.
-    :param once: The value to get data only once.
     :param stop: The value to stop the screener objects.
     :param cancel: The time to cancel the waiting.
 
     :returns: The total delay.
     """
 
-    if cancel == 0:
-        cancel = None
+    if cancel is None:
+        cancel = 0
     # end if
 
-    if isinstance(cancel, (int, float)):
-        cancel = dt.timedelta(seconds=cancel)
+    if delay is None:
+        delay = 0
     # end if
 
-    current_time = dt.datetime.now()
-
-    if isinstance(cancel, dt.timedelta):
-        cancel = current_time + cancel
+    if isinstance(cancel, (int, float)):
+        cancel = dt.timedelta(seconds=cancel)
     # end if
 
     if isinstance(delay, dt.timedelta):
         delay = delay.total_seconds()
     # end if
 
-    delay = delay or 0
+    start = dt.datetime.now()
     count = 0
+    canceled = False
 
-    if screeners:
-        wait_for_dynamic_initialization(
-            screeners, delay=delay, once=once
-        )
+    wait = wait_for_dynamic_initialization(
+        screeners, delay=delay, cancel=cancel, stop=stop
+    )
 
-        saved_screeners = screeners
-        checked_screeners = []
+    if not screeners:
+        return wait
+    # end if
 
-        for screener in saved_screeners:
-            if isinstance(screener, BaseScreener):
-                checked_screeners.append(screener)
+    while screeners:
+        checked_screeners = gather_screeners(screeners=screeners)
 
-            elif isinstance(screener, BaseMultiScreener):
-                checked_screeners.extend(screener.screeners)
-            # end if
-        # end for
-
-        indexes = [
-            screener.market.index[-1]
+        indexes = {
+            screener: len(screener.market)
             for screener in checked_screeners
-        ]
-
-        new_indexes = indexes
-
-        length = len(tuple(checked_screeners))
-
-        while True:
-            for screener in saved_screeners:
-                if isinstance(screener, BaseScreener):
-                    checked_screeners.append(screener)
-
-                elif isinstance(screener, BaseMultiScreener):
-                    checked_screeners.extend(screener.screeners)
-                # end if
-            # end for
+        }
 
-            if (
-                all(
-                    indexes[i] != new_indexes[i]
-                    for i in range(length)
-                ) or
-                (
-                    (cancel is not None) and
-                    ((current_time := dt.datetime.now()) > cancel)
-                )
-            ):
-                break
-            # end if
+        if (
+            isinstance(cancel, dt.timedelta) and
+            (canceled := ((dt.datetime.now() - start) > cancel))
+        ):
+            break
+        # end if
 
-            count += 1
+        if isinstance(delay, (int, float)):
+            time.sleep(delay)
+        # end if
 
-            new_indexes = [
-                screener.market.index[-1]
-                for screener in checked_screeners
-            ]
+        count += 1
 
-            if isinstance(delay, (int, float)) and (count > 0):
-                time.sleep(delay)
-            # end if
-        # end while
+        new_indexes = {
+            screener: len(screener.market)
+            for screener in checked_screeners
+        }
 
-        if stop and ((stop == count) or once):
-            for screener in checked_screeners:
-                screener.stop()
-            # end for
+        if indexes == new_indexes:
+            break
         # end if
+    # end while
+
+    if stop:
+        for screener in screeners:
+            screener.stop()
+        # end for
     # end if
 
     return WaitingState(
-        screeners=screeners, delay=delay, count=count, cancel=cancel,
-        canceled=(cancel is None) or (current_time > cancel)
+        screeners=screeners, delay=delay,
+        count=count, end=dt.datetime.now(), start=start,
+        cancel=cancel, canceled=canceled
     )
 # end wait_for_dynamic_update
 
 def wait_for_update(
         *screeners: Union[BaseScreener, BaseMultiScreener],
+        stop: Optional[bool] = False,
         delay: Optional[Union[Number, dt.timedelta]] = None,
-        once: Optional[bool] = False,
-        stop: Optional[Union[bool, int]] = False,
         cancel: Optional[Union[Number, dt.timedelta, dt.datetime]] = None
 ) -> WaitingState:
     """
     Waits for all the create_screeners to update.
 
     :param screeners: The create_screeners to wait for them to update.
     :param delay: The delay for the waiting.
-    :param once: The value to get data only once.
     :param stop: The value to stop the screener objects.
     :param cancel: The time to cancel the waiting.
 
     :returns: The total delay.
     """
 
     return wait_for_dynamic_update(
-        screeners, delay=delay, once=once,
+        screeners, delay=delay,
         stop=stop, cancel=cancel
     )
 # end wait_for_update
 
 def structure_screeners_datasets(
         screeners: Iterable[BaseScreener]
 ) -> Dict[str, Dict[str, List[pd.DataFrame]]]:
```

### Comparing `crypto-screening-1.2.6/crypto_screening/symbols.py` & `crypto-screening-1.3.0/crypto_screening/symbols.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/crypto_screening/validate.py` & `crypto-screening-1.3.0/crypto_screening/validate.py`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/crypto_screening.egg-info/PKG-INFO` & `crypto-screening-1.3.0/crypto_screening.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: crypto-screening
-Version: 1.2.6
+Version: 1.3.0
 Summary: A software for automatically recording real-time crypto exchanges and pairs OHLCV and Orderbook rates.
 Home-page: https://github.com/Shahaf-F-S/crypto-screening
 Author: Shahaf Frank-Shapir
 Author-email: shahaffrs@gmail.com
 License: MIT
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `crypto-screening-1.2.6/crypto_screening.egg-info/SOURCES.txt` & `crypto-screening-1.3.0/crypto_screening.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `crypto-screening-1.2.6/pyproject.toml` & `crypto-screening-1.3.0/pyproject.toml`

 * *Files 12% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = 'crypto-screening'
-version = '1.2.6'
+version = '1.3.0'
 description = 'A software for automatically recording real-time crypto exchanges and pairs OHLCV and Orderbook rates.'
 classifiers = [
 	'Intended Audience :: Developers',
 	'License :: OSI Approved :: MIT License',
 	'Programming Language :: Python',
 	'Programming Language :: Python :: 3',
 	'Programming Language :: Python :: 3.8',
```

### Comparing `crypto-screening-1.2.6/setup.py` & `crypto-screening-1.3.0/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -20,15 +20,15 @@
         exclude=[
             "__pycache__",
             "*.pyc"
         ],
         requirements="requirements.txt",
         dev_requirements="requirements-dev.txt",
         name='crypto-screening',
-        version='1.2.6',
+        version='1.3.0',
         description=(
             "A software for automatically recording "
             "real-time crypto exchanges and pairs "
             "OHLCV and Orderbook rates."
         ),
         license='MIT',
         author="Shahaf Frank-Shapir",
```

