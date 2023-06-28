# Comparing `tmp/http_content_parser-0.0.3.tar.gz` & `tmp/http_content_parser-0.0.4.tar.gz`

## Comparing `http_content_parser-0.0.3.tar` & `http_content_parser-0.0.4.tar`

### file list

```diff
@@ -1,14 +1,14 @@
--rw-r--r--   0        0        0        6 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/requirements.txt
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/src/http_content_parser/__init__.py
--rw-r--r--   0        0        0     5009 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/src/http_content_parser/curl_parser.py
--rw-r--r--   0        0        0     6291 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/src/http_content_parser/generate_api_file.py
--rw-r--r--   0        0        0     7619 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/src/http_content_parser/openapi_parser.py
--rw-r--r--   0        0        0     5100 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/src/http_content_parser/param_util.py
--rw-r--r--   0        0        0     1833 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/src/http_content_parser/postman_parser.py
--rw-r--r--   0        0        0     2629 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/src/http_content_parser/req_data.py
--rw-r--r--   0        0        0     6695 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/src/http_content_parser/swagger2_parser.py
--rw-r--r--   0        0        0      402 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/.gitignore
--rw-r--r--   0        0        0     1074 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/LICENSE
--rw-r--r--   0        0        0       61 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/README.md
--rw-r--r--   0        0        0      441 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/pyproject.toml
--rw-r--r--   0        0        0      441 2020-02-02 00:00:00.000000 http_content_parser-0.0.3/PKG-INFO
+-rw-r--r--   0        0        0        6 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/requirements.txt
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/src/http_content_parser/__init__.py
+-rw-r--r--   0        0        0     5009 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/src/http_content_parser/curl_parser.py
+-rw-r--r--   0        0        0     6291 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/src/http_content_parser/generate_api_file.py
+-rw-r--r--   0        0        0     7619 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/src/http_content_parser/openapi_parser.py
+-rw-r--r--   0        0        0     6045 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/src/http_content_parser/param_util.py
+-rw-r--r--   0        0        0     1833 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/src/http_content_parser/postman_parser.py
+-rw-r--r--   0        0        0     2629 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/src/http_content_parser/req_data.py
+-rw-r--r--   0        0        0     6695 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/src/http_content_parser/swagger2_parser.py
+-rw-r--r--   0        0        0      402 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/.gitignore
+-rw-r--r--   0        0        0     1074 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/LICENSE
+-rw-r--r--   0        0        0       61 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/README.md
+-rw-r--r--   0        0        0      441 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/pyproject.toml
+-rw-r--r--   0        0        0      441 2020-02-02 00:00:00.000000 http_content_parser-0.0.4/PKG-INFO
```

### Comparing `http_content_parser-0.0.3/src/http_content_parser/curl_parser.py` & `http_content_parser-0.0.4/src/http_content_parser/curl_parser.py`

 * *Files identical despite different names*

### Comparing `http_content_parser-0.0.3/src/http_content_parser/generate_api_file.py` & `http_content_parser-0.0.4/src/http_content_parser/generate_api_file.py`

 * *Files identical despite different names*

### Comparing `http_content_parser-0.0.3/src/http_content_parser/openapi_parser.py` & `http_content_parser-0.0.4/src/http_content_parser/openapi_parser.py`

 * *Files identical despite different names*

### Comparing `http_content_parser-0.0.3/src/http_content_parser/param_util.py` & `http_content_parser-0.0.4/src/http_content_parser/param_util.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,14 +1,37 @@
 # -*- coding: UTF-8 -*-
 
 class ParamUtil(object):
     def __init__(self) -> None:
         self._param_list = []
 
     @staticmethod
+    def merge_api_params(swagger_dict: dict, api_dict: dict) -> dict:
+        result = {}
+        swagger_fail_dict = []
+        for k, v in swagger_dict.items():
+            if v['path_param'] or v['query_param']:
+                if api_dict.get(k):
+                    temp_v = v
+                    temp_v['body_type'] = v['body']
+                    temp_v['body'] = api_dict[k]['body']
+                    temp_v['original_url'] = api_dict[k]['original_url']
+                    temp_v['query_param'] = api_dict[k]['query_param']
+                    result[k] = temp_v
+                else:
+                    swagger_fail_dict.append(k.replace('_', '/'))
+            else:
+                if api_dict.get(k):
+                    result[k] = api_dict[k]
+                else:
+                    swagger_fail_dict.append(k.replace('_', '/'))
+                    # result[k] = v
+        return result, swagger_fail_dict
+
+    @staticmethod
     def split_swagger_param_and_type(param, nontype=False):
         sp = SwaggerParam()
         return sp.split_params(param, '', nontype)
 
     def split_dict_params(self, params_dict, prefix_str, middle_char, nontype=False):
         for k, v in params_dict.items():
             new_v = self.adjust_type(v, nontype=nontype)
@@ -108,15 +131,15 @@
                 if isinstance(param[i], dict):
                     temp_prefix_str += f"[{i}]"
                     self.split_params_for_dict_type(
                         param[i], temp_prefix_str, nontype)
         elif isinstance(param, dict):
             self.split_params_for_dict_type(param, prefix_str, nontype)
         else:
-            print('param type is error: '+ type(param))
+            print('param type is error: ' + type(param))
         return self._param_list
 
     # nontype用来控制value值是否输出原值还是参数类型
     def adjust_type(self, value, nontype=False):
         if isinstance(value, (bool, int, dict, list)):
             return value
         else:
```

### Comparing `http_content_parser-0.0.3/src/http_content_parser/postman_parser.py` & `http_content_parser-0.0.4/src/http_content_parser/postman_parser.py`

 * *Files identical despite different names*

### Comparing `http_content_parser-0.0.3/src/http_content_parser/req_data.py` & `http_content_parser-0.0.4/src/http_content_parser/req_data.py`

 * *Files identical despite different names*

### Comparing `http_content_parser-0.0.3/src/http_content_parser/swagger2_parser.py` & `http_content_parser-0.0.4/src/http_content_parser/swagger2_parser.py`

 * *Files identical despite different names*

### Comparing `http_content_parser-0.0.3/LICENSE` & `http_content_parser-0.0.4/LICENSE`

 * *Files identical despite different names*

