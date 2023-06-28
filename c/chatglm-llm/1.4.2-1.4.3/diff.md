# Comparing `tmp/chatglm-llm-1.4.2.tar.gz` & `tmp/chatglm-llm-1.4.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "chatglm-llm-1.4.2.tar", last modified: Wed Jun 28 01:04:02 2023, max compression
+gzip compressed data, was "chatglm-llm-1.4.3.tar", last modified: Wed Jun 28 09:08:57 2023, max compression
```

## Comparing `chatglm-llm-1.4.2.tar` & `chatglm-llm-1.4.3.tar`

### file list

```diff
@@ -1,26 +1,27 @@
-drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 01:04:02.930417 chatglm-llm-1.4.2/
--rw-r--r--   0 mroy       (501) staff       (20)       36 2023-05-10 01:48:15.000000 chatglm-llm-1.4.2/MANIFEST.in
--rw-r--r--   0 mroy       (501) staff       (20)      212 2023-06-28 01:04:02.930297 chatglm-llm-1.4.2/PKG-INFO
--rw-r--r--   0 mroy       (501) staff       (20)     1887 2023-05-04 01:08:28.000000 chatglm-llm-1.4.2/README.md
-drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 01:04:02.929171 chatglm-llm-1.4.2/chatglm_llm.egg-info/
--rw-r--r--   0 mroy       (501) staff       (20)      212 2023-06-28 01:04:02.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/PKG-INFO
--rw-r--r--   0 mroy       (501) staff       (20)      511 2023-06-28 01:04:02.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/SOURCES.txt
--rw-r--r--   0 mroy       (501) staff       (20)        1 2023-06-28 01:04:02.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/dependency_links.txt
--rw-r--r--   0 mroy       (501) staff       (20)       53 2023-06-28 01:04:02.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/entry_points.txt
--rw-r--r--   0 mroy       (501) staff       (20)        1 2023-05-04 01:12:10.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/not-zip-safe
--rw-r--r--   0 mroy       (501) staff       (20)      266 2023-06-28 01:04:02.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/requires.txt
--rw-r--r--   0 mroy       (501) staff       (20)       12 2023-06-28 01:04:02.000000 chatglm-llm-1.4.2/chatglm_llm.egg-info/top_level.txt
-drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 01:04:02.929792 chatglm-llm-1.4.2/chatglm_src/
--rw-r--r--   0 mroy       (501) staff       (20)      755 2023-06-16 02:41:40.000000 chatglm-llm-1.4.2/chatglm_src/__init__.py
--rw-r--r--   0 mroy       (501) staff       (20)     4201 2023-05-13 02:36:58.000000 chatglm-llm-1.4.2/chatglm_src/callbacks.py
-drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 01:04:02.930029 chatglm-llm-1.4.2/chatglm_src/chains/
--rw-r--r--   0 mroy       (501) staff       (20)       69 2023-05-10 01:48:15.000000 chatglm-llm-1.4.2/chatglm_src/chains/__init__.py
--rw-r--r--   0 mroy       (501) staff       (20)     4402 2023-05-11 09:17:21.000000 chatglm-llm-1.4.2/chatglm_src/chains/local_qa.py
--rw-r--r--   0 mroy       (501) staff       (20)     2777 2023-06-16 06:08:22.000000 chatglm-llm-1.4.2/chatglm_src/cluster_and_smi.py
--rw-r--r--   0 mroy       (501) staff       (20)      537 2023-05-30 04:20:56.000000 chatglm-llm-1.4.2/chatglm_src/cmd.py
--rw-r--r--   0 mroy       (501) staff       (20)     3052 2023-06-15 08:48:00.000000 chatglm-llm-1.4.2/chatglm_src/embeding.py
--rw-r--r--   0 mroy       (501) staff       (20)    38577 2023-06-16 07:01:29.000000 chatglm-llm-1.4.2/chatglm_src/llm.py
-drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 01:04:02.930130 chatglm-llm-1.4.2/chatglm_src/loader/
--rw-r--r--   0 mroy       (501) staff       (20)     1403 2023-05-11 01:28:05.000000 chatglm-llm-1.4.2/chatglm_src/loader/__init__.py
--rw-r--r--   0 mroy       (501) staff       (20)       38 2023-06-28 01:04:02.930455 chatglm-llm-1.4.2/setup.cfg
--rw-r--r--   0 mroy       (501) staff       (20)     1078 2023-06-28 01:02:51.000000 chatglm-llm-1.4.2/setup.py
+drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 09:08:57.807364 chatglm-llm-1.4.3/
+-rw-r--r--   0 mroy       (501) staff       (20)       36 2023-05-10 01:48:15.000000 chatglm-llm-1.4.3/MANIFEST.in
+-rw-r--r--   0 mroy       (501) staff       (20)      212 2023-06-28 09:08:57.807227 chatglm-llm-1.4.3/PKG-INFO
+-rw-r--r--   0 mroy       (501) staff       (20)     1887 2023-05-04 01:08:28.000000 chatglm-llm-1.4.3/README.md
+drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 09:08:57.805982 chatglm-llm-1.4.3/chatglm_llm.egg-info/
+-rw-r--r--   0 mroy       (501) staff       (20)      212 2023-06-28 09:08:57.000000 chatglm-llm-1.4.3/chatglm_llm.egg-info/PKG-INFO
+-rw-r--r--   0 mroy       (501) staff       (20)      540 2023-06-28 09:08:57.000000 chatglm-llm-1.4.3/chatglm_llm.egg-info/SOURCES.txt
+-rw-r--r--   0 mroy       (501) staff       (20)        1 2023-06-28 09:08:57.000000 chatglm-llm-1.4.3/chatglm_llm.egg-info/dependency_links.txt
+-rw-r--r--   0 mroy       (501) staff       (20)       53 2023-06-28 09:08:57.000000 chatglm-llm-1.4.3/chatglm_llm.egg-info/entry_points.txt
+-rw-r--r--   0 mroy       (501) staff       (20)        1 2023-05-04 01:12:10.000000 chatglm-llm-1.4.3/chatglm_llm.egg-info/not-zip-safe
+-rw-r--r--   0 mroy       (501) staff       (20)      266 2023-06-28 09:08:57.000000 chatglm-llm-1.4.3/chatglm_llm.egg-info/requires.txt
+-rw-r--r--   0 mroy       (501) staff       (20)       12 2023-06-28 09:08:57.000000 chatglm-llm-1.4.3/chatglm_llm.egg-info/top_level.txt
+drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 09:08:57.806709 chatglm-llm-1.4.3/chatglm_src/
+-rw-r--r--   0 mroy       (501) staff       (20)      755 2023-06-16 02:41:40.000000 chatglm-llm-1.4.3/chatglm_src/__init__.py
+-rw-r--r--   0 mroy       (501) staff       (20)     4201 2023-05-13 02:36:58.000000 chatglm-llm-1.4.3/chatglm_src/callbacks.py
+drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 09:08:57.806949 chatglm-llm-1.4.3/chatglm_src/chains/
+-rw-r--r--   0 mroy       (501) staff       (20)       69 2023-05-10 01:48:15.000000 chatglm-llm-1.4.3/chatglm_src/chains/__init__.py
+-rw-r--r--   0 mroy       (501) staff       (20)     4402 2023-05-11 09:17:21.000000 chatglm-llm-1.4.3/chatglm_src/chains/local_qa.py
+-rw-r--r--   0 mroy       (501) staff       (20)     2272 2023-06-28 08:26:21.000000 chatglm-llm-1.4.3/chatglm_src/chatglm_utils.py
+-rw-r--r--   0 mroy       (501) staff       (20)     2777 2023-06-16 06:08:22.000000 chatglm-llm-1.4.3/chatglm_src/cluster_and_smi.py
+-rw-r--r--   0 mroy       (501) staff       (20)      537 2023-05-30 04:20:56.000000 chatglm-llm-1.4.3/chatglm_src/cmd.py
+-rw-r--r--   0 mroy       (501) staff       (20)     3052 2023-06-15 08:48:00.000000 chatglm-llm-1.4.3/chatglm_src/embeding.py
+-rw-r--r--   0 mroy       (501) staff       (20)    40968 2023-06-28 09:06:45.000000 chatglm-llm-1.4.3/chatglm_src/llm.py
+drwxr-xr-x   0 mroy       (501) staff       (20)        0 2023-06-28 09:08:57.807054 chatglm-llm-1.4.3/chatglm_src/loader/
+-rw-r--r--   0 mroy       (501) staff       (20)     1403 2023-05-11 01:28:05.000000 chatglm-llm-1.4.3/chatglm_src/loader/__init__.py
+-rw-r--r--   0 mroy       (501) staff       (20)       38 2023-06-28 09:08:57.807418 chatglm-llm-1.4.3/setup.cfg
+-rw-r--r--   0 mroy       (501) staff       (20)     1078 2023-06-28 08:53:27.000000 chatglm-llm-1.4.3/setup.py
```

### Comparing `chatglm-llm-1.4.2/README.md` & `chatglm-llm-1.4.3/README.md`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.2/chatglm_src/__init__.py` & `chatglm-llm-1.4.3/chatglm_src/__init__.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.2/chatglm_src/callbacks.py` & `chatglm-llm-1.4.3/chatglm_src/callbacks.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.2/chatglm_src/chains/local_qa.py` & `chatglm-llm-1.4.3/chatglm_src/chains/local_qa.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.2/chatglm_src/cluster_and_smi.py` & `chatglm-llm-1.4.3/chatglm_src/cluster_and_smi.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.2/chatglm_src/cmd.py` & `chatglm-llm-1.4.3/chatglm_src/cmd.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.2/chatglm_src/embeding.py` & `chatglm-llm-1.4.3/chatglm_src/embeding.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.2/chatglm_src/llm.py` & `chatglm-llm-1.4.3/chatglm_src/llm.py`

 * *Files 3% similar despite different names*

```diff
@@ -489,15 +489,25 @@
             mo.cpu = True
         if model_path is not None:
             mo.model_path = pathlib.Path(model_path)
         # load from local
         if mo.model_path.exists() and mo.remote_host is None:
             if torch.cuda.device_count() > 0:
                 print(colored("[GPU]","green"),":",torch.cuda.device_count(), "GPUs" )
-                mo.model = load_model_on_gpus_old(mo.model_path, num_gpus=torch.cuda.device_count())
+                # use chatglm
+                try:
+                    mo.model = load_model_on_gpus_old(mo.model_path, num_gpus=torch.cuda.device_count())
+                except Exception as e:
+                    print(colored("[GPU]","yellow"),": failed !! but try load use new way " + str(e),torch.cuda.device_count(), "GPUs" )
+                    try:
+                        from .chatglm_utils import load_model_on_gpus
+                        mo.model = load_model_on_gpus(mo.model_path, num_gpus=torch.cuda.device_count())
+                    except Exception as e:
+                        print(colored("[GPU]","red"),": failed !! " + str(e),torch.cuda.device_count(), "GPUs" )
+
             else:
                 mo.model = AutoModel.from_pretrained(mo.model_path, trust_remote_code=True, device_map="auto")
             mo.tokenizer = AutoTokenizer.from_pretrained(mo.model_path, trust_remote_code=True)
         else:
             # load from huggingface
             # use os.system to call git lfs download model
             # then load from local
@@ -613,14 +623,57 @@
                 max_length=self.max_token,
                 top_p=self.top_p,
                 temperature=self.temperature,
             )
             response = enforce_stop_tokens(response, stop or [])
             self.history = self.history+[[prompt, response]]
             return response
+    
+    def stream(self,prompt: str, stop: List[str] = None):
+        assert self.remote_host is not None
+        uri = f"ws://{self.remote_host}:15000"
+        result = ''
+        # self.callback_manager =  BaseCallbackManager(self.callbacks)
+        # self.callback_manager.set_handlers(self.callbacks)
+        
+        ws = create_connection(f"ws://{self.remote_host}:15000")
+        user_id = md5(time.asctime().encode()).hexdigest()
+        # self.callback_manager =  langchain.callbacks.base.BaseCallbackManager(self.callbacks)
+        
+        # self.callback_manager =  BaseCallbackManager(self.callbacks)
+        # self.callback_manager.set_handlers(self.callbacks)
+        ws.send(json.dumps({"user_id":user_id, "password":PASSWORD}))
+        # time.sleep(0.5)
+        res = ws.recv()
+        if res != "ok":
+            print(colored("[info]:","yellow") ,res)
+            raise Exception("password error")
+        result = ''
+            
+            
+        data = json.dumps({"prompt":prompt, "history":self.history,"model":"chatglm", "temperature": self.temperature})
+        self.send_to_remote(data, ws)
+        while 1:
+            res = ws.recv()
+            msg = json.loads(res)
+            # { "new":delta,"response": response, "history": history,"query": prompt}
+            if "stop" in msg:
+                break
+            new_token = msg["new"]
+            response = msg["response"]
+            history = msg["history"]
+            msg["verbose"] = self.verbose
+            result = msg
+            yield msg
+            
+            # for call in self.callbacks:
+            #     if is_async_method(call.on_llm_start):
+                    # await call.on_llm_end(result, verbose=self.verbose)
+        self.history = self.history+[[prompt, result]]
+        # yield result
 
     def send_to_remote(self,data,ws):
         """
         every chunk of data is 2M
         """
         for i in range(0, len(data), 1024*1024*2):
             ws.send(data[i:i+1024*1024*2])
```

### Comparing `chatglm-llm-1.4.2/chatglm_src/loader/__init__.py` & `chatglm-llm-1.4.3/chatglm_src/loader/__init__.py`

 * *Files identical despite different names*

### Comparing `chatglm-llm-1.4.2/setup.py` & `chatglm-llm-1.4.3/setup.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 
 from setuptools import setup, find_packages
 
 
 setup(name='chatglm-llm',
-    version='1.4.2',
+    version='1.4.3',
     description='chatglm llm',
     url='https://github.com/xxx',
     author='auth',
     author_email='xxx@gmail.com',
     license='MIT',
     include_package_data=True,
     zip_safe=False,
```

