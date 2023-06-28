# Comparing `tmp/kuflow_temporal_activity_kuflow-0.7.1.tar.gz` & `tmp/kuflow_temporal_activity_kuflow-0.8.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kuflow_temporal_activity_kuflow-0.7.1.tar", max compression
+gzip compressed data, was "kuflow_temporal_activity_kuflow-0.8.0.tar", max compression
```

## Comparing `kuflow_temporal_activity_kuflow-0.7.1.tar` & `kuflow_temporal_activity_kuflow-0.8.0.tar`

### file list

```diff
@@ -1,22 +1,22 @@
--rw-r--r--   0        0        0      878 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/README.md
--rw-r--r--   0        0        0        6 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/VERSION
--rw-r--r--   0        0        0     1320 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/__init__.py
--rw-r--r--   0        0        0     8623 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/_validation.py
--rw-r--r--   0        0        0     5176 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/converter.py
--rw-r--r--   0        0        0     2226 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/kuflow_async_activities.py
--rw-r--r--   0        0        0    15503 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/kuflow_sync_activities.py
--rw-r--r--   0        0        0     3553 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/models/__init__.py
--rw-r--r--   0        0        0     1949 2023-06-20 07:21:29.632378 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/models/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0        0        0    22540 2023-06-20 07:21:29.632378 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/models/__pycache__/_models.cpython-38.pyc
--rw-r--r--   0        0        0    22235 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/models/_models.py
--rw-r--r--   0        0        0     1478 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/__init__.py
--rw-r--r--   0        0        0      499 2023-06-20 07:21:29.640379 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0        0        0    10493 2023-06-20 07:21:29.640379 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/__pycache__/_save_process_element_utils.cpython-38.pyc
--rw-r--r--   0        0        0    13245 2023-06-20 07:21:29.644379 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/__pycache__/_save_task_element_utils.cpython-38.pyc
--rw-r--r--   0        0        0    14343 2023-06-20 07:21:29.644379 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/__pycache__/_save_task_json_forms_value_data_request_utils.cpython-38.pyc
--rw-r--r--   0        0        0    11220 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/_save_process_element_utils.py
--rw-r--r--   0        0        0    14103 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/_save_task_element_utils.py
--rw-r--r--   0        0        0    15436 2023-06-20 07:20:29.819020 kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/_save_task_json_forms_value_data_request_utils.py
--rw-r--r--   0        0        0     1017 2023-06-20 07:21:48.218041 kuflow_temporal_activity_kuflow-0.7.1/pyproject.toml
--rw-r--r--   0        0        0     1705 1970-01-01 00:00:00.000000 kuflow_temporal_activity_kuflow-0.7.1/setup.py
--rw-r--r--   0        0        0     1667 1970-01-01 00:00:00.000000 kuflow_temporal_activity_kuflow-0.7.1/PKG-INFO
+-rw-r--r--   0        0        0      878 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/README.md
+-rw-r--r--   0        0        0        6 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/VERSION
+-rw-r--r--   0        0        0     1320 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/__init__.py
+-rw-r--r--   0        0        0     8623 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/_validation.py
+-rw-r--r--   0        0        0     5176 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/converter.py
+-rw-r--r--   0        0        0     2227 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/kuflow_async_activities.py
+-rw-r--r--   0        0        0    15516 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/kuflow_sync_activities.py
+-rw-r--r--   0        0        0     3553 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/models/__init__.py
+-rw-r--r--   0        0        0     1949 2023-06-28 08:19:28.662284 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/models/__pycache__/__init__.cpython-38.pyc
+-rw-r--r--   0        0        0    22540 2023-06-28 08:19:28.666284 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/models/__pycache__/_models.cpython-38.pyc
+-rw-r--r--   0        0        0    22235 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/models/_models.py
+-rw-r--r--   0        0        0     1477 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/__init__.py
+-rw-r--r--   0        0        0      499 2023-06-28 08:19:28.678285 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/__pycache__/__init__.cpython-38.pyc
+-rw-r--r--   0        0        0    10493 2023-06-28 08:19:28.678285 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/__pycache__/_save_process_element_utils.cpython-38.pyc
+-rw-r--r--   0        0        0    13245 2023-06-28 08:19:28.682286 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/__pycache__/_save_task_element_utils.cpython-38.pyc
+-rw-r--r--   0        0        0    14343 2023-06-28 08:19:28.686286 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/__pycache__/_save_task_json_forms_value_data_request_utils.cpython-38.pyc
+-rw-r--r--   0        0        0    11204 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/_save_process_element_utils.py
+-rw-r--r--   0        0        0    14070 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/_save_task_element_utils.py
+-rw-r--r--   0        0        0    15424 2023-06-28 08:18:27.332639 kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/_save_task_json_forms_value_data_request_utils.py
+-rw-r--r--   0        0        0     1017 2023-06-28 08:19:46.879958 kuflow_temporal_activity_kuflow-0.8.0/pyproject.toml
+-rw-r--r--   0        0        0     1705 1970-01-01 00:00:00.000000 kuflow_temporal_activity_kuflow-0.8.0/setup.py
+-rw-r--r--   0        0        0     1667 1970-01-01 00:00:00.000000 kuflow_temporal_activity_kuflow-0.8.0/PKG-INFO
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/README.md` & `kuflow_temporal_activity_kuflow-0.8.0/README.md`

 * *Files identical despite different names*

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/__init__.py` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -23,8 +23,8 @@
 # SOFTWARE.
 #
 
 from .kuflow_async_activities import KuFlowAsyncActivities
 from .kuflow_sync_activities import KuFlowSyncActivities
 
 __all__ = ["KuFlowAsyncActivities", "KuFlowSyncActivities"]
-__version__ = "0.7.1"
+__version__ = "0.8.0"
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/_validation.py` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/_validation.py`

 * *Files identical despite different names*

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/converter.py` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/converter.py`

 * *Files 1% similar despite different names*

```diff
@@ -19,16 +19,16 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import Any, Optional, Type
 import json
+from typing import Any, Optional, Type
 
 from temporalio import workflow
 from temporalio.api.common.v1 import Payload
 from temporalio.converter import (
     CompositePayloadConverter,
     DefaultPayloadConverter,
     EncodingPayloadConverter,
@@ -36,15 +36,15 @@
 )
 
 from kuflow_rest import models as models_rest
 
 from . import models as models_temporal
 
 with workflow.unsafe.imports_passed_through():
-    from kuflow_rest import Serializer, Deserializer, Model
+    from kuflow_rest import Deserializer, Model, Serializer
 
 
 class KuFlowComposableEncodingPayloadConverter(EncodingPayloadConverter):
     _default_json_converter: JSONPlainPayloadConverter
 
     _serialize: Serializer
     _deserialize: Deserializer
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/kuflow_async_activities.py` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/kuflow_async_activities.py`

 * *Files 1% similar despite different names*

```diff
@@ -22,19 +22,20 @@
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
 import base64
 
 from temporalio import activity
+
 from kuflow_rest import KuFlowRestClient
 from kuflow_temporal_common import converter
 
-from .converter import KuFlowComposableEncodingPayloadConverter
 from . import models as models_temporal
+from .converter import KuFlowComposableEncodingPayloadConverter
 
 
 class KuFlowAsyncActivities:
     def __init__(self, kuflow_client: KuFlowRestClient) -> None:
         self._kuflow_client = kuflow_client
         self.activities = [self.create_task_and_wait_finished]
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/kuflow_sync_activities.py` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/kuflow_sync_activities.py`

 * *Files 1% similar despite different names*

```diff
@@ -22,17 +22,18 @@
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
 from temporalio import activity
 
 from kuflow_rest import KuFlowRestClient, models
-from kuflow_temporal_common import exceptions, converter
+from kuflow_temporal_common import converter, exceptions
 
-from . import _validation as validation, models as models_temporal
+from . import _validation as validation
+from . import models as models_temporal
 from .converter import KuFlowComposableEncodingPayloadConverter
 
 
 class KuFlowSyncActivities:
     def __init__(self, kuflow_client: KuFlowRestClient) -> None:
         self._kuflow_client = kuflow_client
         self.activities = [
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/models/__init__.py` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/models/__init__.py`

 * *Ordering differences only*

 * *Files 0% similar despite different names*

```diff
@@ -52,18 +52,18 @@
     RetrievePrincipalResponse,
     RetrieveProcessRequest,
     RetrieveProcessResponse,
     RetrieveTaskRequest,
     RetrieveTaskResponse,
     SaveProcessElementRequest,
     SaveProcessElementResponse,
-    SaveTaskJsonFormsValueDataRequest,
-    SaveTaskJsonFormsValueDataResponse,
     SaveTaskElementRequest,
     SaveTaskElementResponse,
+    SaveTaskJsonFormsValueDataRequest,
+    SaveTaskJsonFormsValueDataResponse,
     UserActionWorkflowRequest,
     UserActionWorkflowResponse,
     WorkflowRequest,
     WorkflowResponse,
 )
 
 __all__ = [
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/models/__pycache__/__init__.cpython-38.pyc` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/models/__pycache__/__init__.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 3553 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 5% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 e10d 0000  U.......=S.d....
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 e10d 0000  U..........d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0028 0000 0040 0000 0073 0001 0000 6400  .(...@...s....d.
 00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
 00000040: 6d04 5a04 6d05 5a05 6d06 5a06 6d07 5a07  m.Z.m.Z.m.Z.m.Z.
 00000050: 6d08 5a08 6d09 5a09 6d0a 5a0a 6d0b 5a0b  m.Z.m.Z.m.Z.m.Z.
 00000060: 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f  m.Z.m.Z.m.Z.m.Z.
 00000070: 6d10 5a10 6d11 5a11 6d12 5a12 6d13 5a13  m.Z.m.Z.m.Z.m.Z.
@@ -62,22 +62,22 @@
 000003d0: 5265 7472 6965 7665 5072 6f63 6573 7352  RetrieveProcessR
 000003e0: 6573 706f 6e73 65da 1352 6574 7269 6576  esponse..Retriev
 000003f0: 6554 6173 6b52 6571 7565 7374 da14 5265  eTaskRequest..Re
 00000400: 7472 6965 7665 5461 736b 5265 7370 6f6e  trieveTaskRespon
 00000410: 7365 da19 5361 7665 5072 6f63 6573 7345  se..SaveProcessE
 00000420: 6c65 6d65 6e74 5265 7175 6573 74da 1a53  lementRequest..S
 00000430: 6176 6550 726f 6365 7373 456c 656d 656e  aveProcessElemen
-00000440: 7452 6573 706f 6e73 65da 2153 6176 6554  tResponse.!SaveT
-00000450: 6173 6b4a 736f 6e46 6f72 6d73 5661 6c75  askJsonFormsValu
-00000460: 6544 6174 6152 6571 7565 7374 da22 5361  eDataRequest."Sa
-00000470: 7665 5461 736b 4a73 6f6e 466f 726d 7356  veTaskJsonFormsV
-00000480: 616c 7565 4461 7461 5265 7370 6f6e 7365  alueDataResponse
-00000490: da16 5361 7665 5461 736b 456c 656d 656e  ..SaveTaskElemen
-000004a0: 7452 6571 7565 7374 da17 5361 7665 5461  tRequest..SaveTa
-000004b0: 736b 456c 656d 656e 7452 6573 706f 6e73  skElementRespons
+00000440: 7452 6573 706f 6e73 65da 1653 6176 6554  tResponse..SaveT
+00000450: 6173 6b45 6c65 6d65 6e74 5265 7175 6573  askElementReques
+00000460: 74da 1753 6176 6554 6173 6b45 6c65 6d65  t..SaveTaskEleme
+00000470: 6e74 5265 7370 6f6e 7365 da21 5361 7665  ntResponse.!Save
+00000480: 5461 736b 4a73 6f6e 466f 726d 7356 616c  TaskJsonFormsVal
+00000490: 7565 4461 7461 5265 7175 6573 74da 2253  ueDataRequest."S
+000004a0: 6176 6554 6173 6b4a 736f 6e46 6f72 6d73  aveTaskJsonForms
+000004b0: 5661 6c75 6544 6174 6152 6573 706f 6e73  ValueDataRespons
 000004c0: 65da 1955 7365 7241 6374 696f 6e57 6f72  e..UserActionWor
 000004d0: 6b66 6c6f 7752 6571 7565 7374 da1a 5573  kflowRequest..Us
 000004e0: 6572 4163 7469 6f6e 576f 726b 666c 6f77  erActionWorkflow
 000004f0: 5265 7370 6f6e 7365 da0f 576f 726b 666c  Response..Workfl
 00000500: 6f77 5265 7175 6573 74da 1057 6f72 6b66  owRequest..Workf
 00000510: 6c6f 7752 6573 706f 6e73 6572 0200 0000  lowResponser....
 00000520: 7203 0000 0072 0400 0000 7205 0000 0072  r....r....r....r
@@ -85,16 +85,16 @@
 00000540: 0000 0072 0a00 0000 720b 0000 0072 0c00  ...r....r....r..
 00000550: 0000 720d 0000 0072 0e00 0000 720f 0000  ..r....r....r...
 00000560: 0072 1000 0000 7211 0000 0072 1200 0000  .r....r....r....
 00000570: 7213 0000 0072 1400 0000 7215 0000 0072  r....r....r....r
 00000580: 1600 0000 7217 0000 0072 1800 0000 7219  ....r....r....r.
 00000590: 0000 0072 1a00 0000 721b 0000 0072 1c00  ...r....r....r..
 000005a0: 0000 721d 0000 0072 1e00 0000 721f 0000  ..r....r....r...
-000005b0: 0072 2000 0000 7221 0000 0072 2200 0000  .r ...r!...r"...
-000005c0: 7223 0000 0072 2400 0000 7225 0000 0072  r#...r$...r%...r
+000005b0: 0072 2000 0000 7221 0000 0072 2400 0000  .r ...r!...r$...
+000005c0: 7225 0000 0072 2200 0000 7223 0000 0072  r%...r"...r#...r
 000005d0: 2600 0000 7227 0000 0072 2800 0000 7229  &...r'...r(...r)
 000005e0: 0000 004e 292a da07 5f6d 6f64 656c 7372  ...N)*.._modelsr
 000005f0: 0200 0000 7203 0000 0072 0400 0000 7205  ....r....r....r.
 00000600: 0000 0072 0600 0000 7207 0000 0072 0800  ...r....r....r..
 00000610: 0000 7209 0000 0072 0a00 0000 720b 0000  ..r....r....r...
 00000620: 0072 0c00 0000 720d 0000 0072 0e00 0000  .r....r....r....
 00000630: 720f 0000 0072 1000 0000 7211 0000 0072  r....r....r....r
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/models/__pycache__/_models.cpython-38.pyc` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/models/__pycache__/_models.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 22235 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 4% similar despite different names*

```diff
@@ -1,63 +1,63 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 db56 0000  U.......=S.d.V..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 db56 0000  U..........d.V..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 0403 0000 6400  .....@...s....d.
 00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
-00000040: 6d04 5a04 0100 6400 6402 6c05 6d06 5a06  m.Z...d.d.l.m.Z.
-00000050: 0100 6400 6403 6c07 6d08 5a09 0100 4700  ..d.d.l.m.Z...G.
-00000060: 6404 6405 8400 6405 6506 6a0a 8303 5a0b  d.d...d.e.j...Z.
-00000070: 4700 6406 6407 8400 6407 6506 6a0a 8303  G.d.d...d.e.j...
-00000080: 5a0c 4700 6408 6409 8400 6409 6506 6a0a  Z.G.d.d...d.e.j.
-00000090: 8303 5a0d 4700 640a 640b 8400 640b 6506  ..Z.G.d.d...d.e.
+00000040: 6d04 5a04 0100 6400 6402 6c05 6d06 5a07  m.Z...d.d.l.m.Z.
+00000050: 0100 6400 6403 6c08 6d09 5a09 0100 4700  ..d.d.l.m.Z...G.
+00000060: 6404 6405 8400 6405 6509 6a0a 8303 5a0b  d.d...d.e.j...Z.
+00000070: 4700 6406 6407 8400 6407 6509 6a0a 8303  G.d.d...d.e.j...
+00000080: 5a0c 4700 6408 6409 8400 6409 6509 6a0a  Z.G.d.d...d.e.j.
+00000090: 8303 5a0d 4700 640a 640b 8400 640b 6509  ..Z.G.d.d...d.e.
 000000a0: 6a0a 8303 5a0e 4700 640c 640d 8400 640d  j...Z.G.d.d...d.
-000000b0: 6506 6a0a 8303 5a0f 4700 640e 640f 8400  e.j...Z.G.d.d...
-000000c0: 640f 6506 6a0a 8303 5a10 4700 6410 6411  d.e.j...Z.G.d.d.
-000000d0: 8400 6411 6506 6a0a 8303 5a11 4700 6412  ..d.e.j...Z.G.d.
-000000e0: 6413 8400 6413 6506 6a0a 8303 5a12 4700  d...d.e.j...Z.G.
-000000f0: 6414 6415 8400 6415 6506 6a0a 8303 5a13  d.d...d.e.j...Z.
-00000100: 4700 6416 6417 8400 6417 6506 6a0a 8303  G.d.d...d.e.j...
-00000110: 5a14 4700 6418 6419 8400 6419 6506 6a0a  Z.G.d.d...d.e.j.
-00000120: 8303 5a15 4700 641a 641b 8400 641b 6506  ..Z.G.d.d...d.e.
+000000b0: 6509 6a0a 8303 5a0f 4700 640e 640f 8400  e.j...Z.G.d.d...
+000000c0: 640f 6509 6a0a 8303 5a10 4700 6410 6411  d.e.j...Z.G.d.d.
+000000d0: 8400 6411 6509 6a0a 8303 5a11 4700 6412  ..d.e.j...Z.G.d.
+000000e0: 6413 8400 6413 6509 6a0a 8303 5a12 4700  d...d.e.j...Z.G.
+000000f0: 6414 6415 8400 6415 6509 6a0a 8303 5a13  d.d...d.e.j...Z.
+00000100: 4700 6416 6417 8400 6417 6509 6a0a 8303  G.d.d...d.e.j...
+00000110: 5a14 4700 6418 6419 8400 6419 6509 6a0a  Z.G.d.d...d.e.j.
+00000120: 8303 5a15 4700 641a 641b 8400 641b 6509  ..Z.G.d.d...d.e.
 00000130: 6a0a 8303 5a16 4700 641c 641d 8400 641d  j...Z.G.d.d...d.
-00000140: 6506 6a0a 8303 5a17 4700 641e 641f 8400  e.j...Z.G.d.d...
-00000150: 641f 6506 6a0a 8303 5a18 4700 6420 6421  d.e.j...Z.G.d d!
-00000160: 8400 6421 6506 6a0a 8303 5a19 4700 6422  ..d!e.j...Z.G.d"
-00000170: 6423 8400 6423 6506 6a0a 8303 5a1a 4700  d#..d#e.j...Z.G.
-00000180: 6424 6425 8400 6425 6506 6a0a 8303 5a1b  d$d%..d%e.j...Z.
-00000190: 4700 6426 6427 8400 6427 6506 6a0a 8303  G.d&d'..d'e.j...
-000001a0: 5a1c 4700 6428 6429 8400 6429 6506 6a0a  Z.G.d(d)..d)e.j.
-000001b0: 8303 5a1d 4700 642a 642b 8400 642b 6506  ..Z.G.d*d+..d+e.
+00000140: 6509 6a0a 8303 5a17 4700 641e 641f 8400  e.j...Z.G.d.d...
+00000150: 641f 6509 6a0a 8303 5a18 4700 6420 6421  d.e.j...Z.G.d d!
+00000160: 8400 6421 6509 6a0a 8303 5a19 4700 6422  ..d!e.j...Z.G.d"
+00000170: 6423 8400 6423 6509 6a0a 8303 5a1a 4700  d#..d#e.j...Z.G.
+00000180: 6424 6425 8400 6425 6509 6a0a 8303 5a1b  d$d%..d%e.j...Z.
+00000190: 4700 6426 6427 8400 6427 6509 6a0a 8303  G.d&d'..d'e.j...
+000001a0: 5a1c 4700 6428 6429 8400 6429 6509 6a0a  Z.G.d(d)..d)e.j.
+000001b0: 8303 5a1d 4700 642a 642b 8400 642b 6509  ..Z.G.d*d+..d+e.
 000001c0: 6a0a 8303 5a1e 4700 642c 642d 8400 642d  j...Z.G.d,d-..d-
-000001d0: 6506 6a0a 8303 5a1f 4700 642e 642f 8400  e.j...Z.G.d.d/..
-000001e0: 642f 6506 6a0a 8303 5a20 4700 6430 6431  d/e.j...Z G.d0d1
-000001f0: 8400 6431 6506 6a0a 8303 5a21 4700 6432  ..d1e.j...Z!G.d2
-00000200: 6433 8400 6433 6506 6a0a 8303 5a22 4700  d3..d3e.j...Z"G.
-00000210: 6434 6435 8400 6435 6506 6a0a 8303 5a23  d4d5..d5e.j...Z#
-00000220: 4700 6436 6437 8400 6437 6506 6a0a 8303  G.d6d7..d7e.j...
-00000230: 5a24 4700 6438 6439 8400 6439 6506 6a0a  Z$G.d8d9..d9e.j.
-00000240: 8303 5a25 4700 643a 643b 8400 643b 6506  ..Z%G.d:d;..d;e.
+000001d0: 6509 6a0a 8303 5a1f 4700 642e 642f 8400  e.j...Z.G.d.d/..
+000001e0: 642f 6509 6a0a 8303 5a20 4700 6430 6431  d/e.j...Z G.d0d1
+000001f0: 8400 6431 6509 6a0a 8303 5a21 4700 6432  ..d1e.j...Z!G.d2
+00000200: 6433 8400 6433 6509 6a0a 8303 5a22 4700  d3..d3e.j...Z"G.
+00000210: 6434 6435 8400 6435 6509 6a0a 8303 5a23  d4d5..d5e.j...Z#
+00000220: 4700 6436 6437 8400 6437 6509 6a0a 8303  G.d6d7..d7e.j...
+00000230: 5a24 4700 6438 6439 8400 6439 6509 6a0a  Z$G.d8d9..d9e.j.
+00000240: 8303 5a25 4700 643a 643b 8400 643b 6509  ..Z%G.d:d;..d;e.
 00000250: 6a0a 8303 5a26 4700 643c 643d 8400 643d  j...Z&G.d<d=..d=
-00000260: 6506 6a0a 8303 5a27 4700 643e 643f 8400  e.j...Z'G.d>d?..
-00000270: 643f 6506 6a0a 8303 5a28 4700 6440 6441  d?e.j...Z(G.d@dA
-00000280: 8400 6441 6506 6a0a 8303 5a29 4700 6442  ..dAe.j...Z)G.dB
-00000290: 6443 8400 6443 6506 6a0a 8303 5a2a 4700  dC..dCe.j...Z*G.
-000002a0: 6444 6445 8400 6445 6506 6a0a 8303 5a2b  dDdE..dEe.j...Z+
-000002b0: 4700 6446 6447 8400 6447 6506 6a0a 8303  G.dFdG..dGe.j...
-000002c0: 5a2c 4700 6448 6449 8400 6449 6506 6a0a  Z,G.dHdI..dIe.j.
-000002d0: 8303 5a2d 4700 644a 644b 8400 644b 6506  ..Z-G.dJdK..dKe.
+00000260: 6509 6a0a 8303 5a27 4700 643e 643f 8400  e.j...Z'G.d>d?..
+00000270: 643f 6509 6a0a 8303 5a28 4700 6440 6441  d?e.j...Z(G.d@dA
+00000280: 8400 6441 6509 6a0a 8303 5a29 4700 6442  ..dAe.j...Z)G.dB
+00000290: 6443 8400 6443 6509 6a0a 8303 5a2a 4700  dC..dCe.j...Z*G.
+000002a0: 6444 6445 8400 6445 6509 6a0a 8303 5a2b  dDdE..dEe.j...Z+
+000002b0: 4700 6446 6447 8400 6447 6509 6a0a 8303  G.dFdG..dGe.j...
+000002c0: 5a2c 4700 6448 6449 8400 6449 6509 6a0a  Z,G.dHdI..dIe.j.
+000002d0: 8303 5a2d 4700 644a 644b 8400 644b 6509  ..Z-G.dJdK..dKe.
 000002e0: 6a0a 8303 5a2e 4700 644c 644d 8400 644d  j...Z.G.dLdM..dM
-000002f0: 6506 6a0a 8303 5a2f 4700 644e 644f 8400  e.j...Z/G.dNdO..
-00000300: 644f 6506 6a0a 8303 5a30 4700 6450 6451  dOe.j...Z0G.dPdQ
-00000310: 8400 6451 6506 6a0a 8303 5a31 4700 6452  ..dQe.j...Z1G.dR
-00000320: 6453 8400 6453 6506 6a0a 8303 5a32 6454  dS..dSe.j...Z2dT
-00000330: 5300 2955 e900 0000 0029 04da 044c 6973  S.)U.....)...Lis
-00000340: 74da 084f 7074 696f 6e61 6cda 0341 6e79  t..Optional..Any
-00000350: da04 4469 6374 2901 da0e 5f73 6572 6961  ..Dict)..._seria
-00000360: 6c69 7a61 7469 6f6e 2901 da06 6d6f 6465  lization)...mode
-00000370: 6c73 6300 0000 0000 0000 0000 0000 0000  lsc.............
+000002f0: 6509 6a0a 8303 5a2f 4700 644e 644f 8400  e.j...Z/G.dNdO..
+00000300: 644f 6509 6a0a 8303 5a30 4700 6450 6451  dOe.j...Z0G.dPdQ
+00000310: 8400 6451 6509 6a0a 8303 5a31 4700 6452  ..dQe.j...Z1G.dR
+00000320: 6453 8400 6453 6509 6a0a 8303 5a32 6454  dS..dSe.j...Z2dT
+00000330: 5300 2955 e900 0000 0029 04da 0341 6e79  S.)U.....)...Any
+00000340: da04 4469 6374 da04 4c69 7374 da08 4f70  ..Dict..List..Op
+00000350: 7469 6f6e 616c 2901 da06 6d6f 6465 6c73  tional)...models
+00000360: 2901 da0e 5f73 6572 6961 6c69 7a61 7469  )..._serializati
+00000370: 6f6e 6300 0000 0000 0000 0000 0000 0000  onc.............
 00000380: 0000 0004 0000 0000 0000 0073 4200 0000  ...........sB...
 00000390: 6500 5a01 6400 5a02 5500 6401 5a03 6504  e.Z.d.Z.U.d.Z.e.
 000003a0: 6505 6402 3c00 6402 6403 6404 6405 9c02  e.d.<.d.d.d.d...
 000003b0: 6901 5a06 6504 6507 6406 6407 9c03 8700  i.Z.e.e.d.d.....
 000003c0: 6601 6408 6409 840c 5a08 8700 0400 5a09  f.d.d...Z.....Z.
 000003d0: 5300 290a da0f 576f 726b 666c 6f77 5265  S.)...WorkflowRe
 000003e0: 7175 6573 747a 530a 2020 2020 4174 7472  questzS.    Attr
@@ -87,15 +87,15 @@
 00000560: 0073 0400 0000 0001 0e01 7a18 576f 726b  .s........z.Work
 00000570: 666c 6f77 5265 7175 6573 742e 5f5f 696e  flowRequest.__in
 00000580: 6974 5f5f a90a da08 5f5f 6e61 6d65 5f5f  it__....__name__
 00000590: da0a 5f5f 6d6f 6475 6c65 5f5f da0c 5f5f  ..__module__..__
 000005a0: 7175 616c 6e61 6d65 5f5f da07 5f5f 646f  qualname__..__do
 000005b0: 635f 5f72 0b00 0000 da0f 5f5f 616e 6e6f  c__r......__anno
 000005c0: 7461 7469 6f6e 735f 5fda 0e5f 6174 7472  tations__.._attr
-000005d0: 6962 7574 655f 6d61 7072 0400 0000 7215  ibute_mapr....r.
+000005d0: 6962 7574 655f 6d61 7072 0200 0000 7215  ibute_mapr....r.
 000005e0: 0000 00da 0d5f 5f63 6c61 7373 6365 6c6c  .....__classcell
 000005f0: 5f5f 721a 0000 0072 1a00 0000 7218 0000  __r....r....r...
 00000600: 0072 1b00 0000 7208 0000 0024 0000 0073  .r....r....$...s
 00000610: 0c00 0000 0a01 0405 0803 0200 08ff 0404  ................
 00000620: 7208 0000 0063 0000 0000 0000 0000 0000  r....c..........
 00000630: 0000 0000 0000 0500 0000 0000 0000 734c  ..............sL
 00000640: 0000 0065 005a 0164 005a 0255 0064 015a  ...e.Z.d.Z.U.d.Z
@@ -117,16 +117,16 @@
 00000740: 0000 0072 1500 0000 7225 0000 00a9 0372  ...r....r%.....r
 00000750: 1700 0000 7225 0000 0072 1000 0000 7218  ....r%...r....r.
 00000760: 0000 0072 1a00 0000 721b 0000 0072 1500  ...r....r....r..
 00000770: 0000 4100 0000 7304 0000 0000 010e 017a  ..A...s........z
 00000780: 1957 6f72 6b66 6c6f 7752 6573 706f 6e73  .WorkflowRespons
 00000790: 652e 5f5f 696e 6974 5f5f 2901 4ea9 0b72  e.__init__).N..r
 000007a0: 1d00 0000 721e 0000 0072 1f00 0000 7220  ....r....r....r 
-000007b0: 0000 0072 0300 0000 720b 0000 0072 2100  ...r....r....r!.
-000007c0: 0000 7222 0000 0072 0400 0000 7215 0000  ..r"...r....r...
+000007b0: 0000 0072 0500 0000 720b 0000 0072 2100  ...r....r....r!.
+000007c0: 0000 7222 0000 0072 0200 0000 7215 0000  ..r"...r....r...
 000007d0: 0072 2300 0000 721a 0000 0072 1a00 0000  .r#...r....r....
 000007e0: 7218 0000 0072 1b00 0000 7224 0000 0035  r....r....r$...5
 000007f0: 0000 0073 0c00 0000 0a01 0405 0c03 0200  ...s............
 00000800: 08ff 0404 7224 0000 0063 0000 0000 0000  ....r$...c......
 00000810: 0000 0000 0000 0000 0000 0700 0000 0000  ................
 00000820: 0000 7378 0000 0065 005a 0164 005a 0255  ..sx...e.Z.d.Z.U
 00000830: 0064 015a 0365 0465 0564 023c 0065 0465  .d.Z.e.e.d.<.e.e
@@ -268,15 +268,15 @@
 000010b0: 0072 1a00 0000 721b 0000 0072 1500 0000  .r....r....r....
 000010c0: 9d00 0000 7304 0000 0000 010e 017a 2252  ....s........z"R
 000010d0: 6574 7269 6576 6550 7269 6e63 6970 616c  etrievePrincipal
 000010e0: 5265 7370 6f6e 7365 2e5f 5f69 6e69 745f  Response.__init_
 000010f0: 5f29 0b72 1d00 0000 721e 0000 0072 1f00  _).r....r....r..
 00001100: 0000 7220 0000 00da 0b6d 6f64 656c 735f  ..r .....models_
 00001110: 7265 7374 7234 0000 0072 2100 0000 7222  restr4...r!...r"
-00001120: 0000 0072 0400 0000 7215 0000 0072 2300  ...r....r....r#.
+00001120: 0000 0072 0200 0000 7215 0000 0072 2300  ...r....r....r#.
 00001130: 0000 721a 0000 0072 1a00 0000 7218 0000  ..r....r....r...
 00001140: 0072 1b00 0000 7232 0000 0091 0000 0073  .r....r2.......s
 00001150: 0c00 0000 0a01 0405 0a03 0200 08ff 0404  ................
 00001160: 7232 0000 0063 0000 0000 0000 0000 0000  r2...c..........
 00001170: 0000 0000 0000 0700 0000 0000 0000 7388  ..............s.
 00001180: 0000 0065 005a 0164 005a 0255 0064 015a  ...e.Z.d.Z.U.d.Z
 00001190: 0365 0465 0519 0065 0664 023c 0065 0465  .e.e...e.d.<.e.e
@@ -313,17 +313,17 @@
 00001380: 0000 2905 7217 0000 0072 3700 0000 7238  ..).r....r7...r8
 00001390: 0000 0072 3900 0000 7210 0000 0072 1800  ...r9...r....r..
 000013a0: 0000 721a 0000 0072 1b00 0000 7215 0000  ..r....r....r...
 000013b0: 00b4 0000 0073 0800 0000 0003 0e01 0601  .....s..........
 000013c0: 0601 7a1d 4669 6e64 5072 6f63 6573 7365  ..z.FindProcesse
 000013d0: 7352 6571 7565 7374 2e5f 5f69 6e69 745f  sRequest.__init_
 000013e0: 5f29 034e 4e4e 290d 721d 0000 0072 1e00  _).NNN).r....r..
-000013f0: 0000 721f 0000 0072 2000 0000 7203 0000  ..r....r ...r...
-00001400: 0072 3a00 0000 7221 0000 0072 0200 0000  .r:...r!...r....
-00001410: 720b 0000 0072 2200 0000 7204 0000 0072  r....r"...r....r
+000013f0: 0000 721f 0000 0072 2000 0000 7205 0000  ..r....r ...r...
+00001400: 0072 3a00 0000 7221 0000 0072 0400 0000  .r:...r!...r....
+00001410: 720b 0000 0072 2200 0000 7202 0000 0072  r....r"...r....r
 00001420: 1500 0000 7223 0000 0072 1a00 0000 721a  ....r#...r....r.
 00001430: 0000 0072 1800 0000 721b 0000 0072 3600  ...r....r....r6.
 00001440: 0000 a200 0000 7324 0000 000a 0104 070c  ......s$........
 00001450: 010c 0110 0308 0108 0108 fd06 0700 0000  ................
 00001460: 0000 ff02 0106 0006 000a 0002 0102 fe72  ...............r
 00001470: 3600 0000 6300 0000 0000 0000 0000 0000  6...c...........
 00001480: 0000 0000 0004 0000 0000 0000 0073 4600  .............sF.
@@ -350,15 +350,15 @@
 000015d0: 7210 0000 0072 1800 0000 721a 0000 0072  r....r....r....r
 000015e0: 1b00 0000 7215 0000 00c9 0000 0073 0400  ....r........s..
 000015f0: 0000 0001 0e01 7a1e 4669 6e64 5072 6f63  ......z.FindProc
 00001600: 6573 7365 7352 6573 706f 6e73 652e 5f5f  essesResponse.__
 00001610: 696e 6974 5f5f 290b 721d 0000 0072 1e00  init__).r....r..
 00001620: 0000 721f 0000 0072 2000 0000 7235 0000  ..r....r ...r5..
 00001630: 0072 3e00 0000 7221 0000 0072 2200 0000  .r>...r!...r"...
-00001640: 7204 0000 0072 1500 0000 7223 0000 0072  r....r....r#...r
+00001640: 7202 0000 0072 1500 0000 7223 0000 0072  r....r....r#...r
 00001650: 1a00 0000 721a 0000 0072 1800 0000 721b  ....r....r....r.
 00001660: 0000 0072 3c00 0000 bd00 0000 730c 0000  ...r<.......s...
 00001670: 000a 0104 050a 0302 0008 ff04 0472 3c00  .............r<.
 00001680: 0000 6300 0000 0000 0000 0000 0000 0000  ..c.............
 00001690: 0000 0004 0000 0000 0000 0073 4200 0000  ...........sB...
 000016a0: 6500 5a01 6400 5a02 5500 6401 5a03 6504  e.Z.d.Z.U.d.Z.e.
 000016b0: 6505 6402 3c00 6402 6403 6404 6405 9c02  e.d.<.d.d.d.d...
@@ -407,15 +407,15 @@
 00001960: 0000 0072 1800 0000 721a 0000 0072 1b00  ...r....r....r..
 00001970: 0000 7215 0000 00eb 0000 0073 0400 0000  ..r........s....
 00001980: 0001 0e01 7a20 5265 7472 6965 7665 5072  ....z RetrievePr
 00001990: 6f63 6573 7352 6573 706f 6e73 652e 5f5f  ocessResponse.__
 000019a0: 696e 6974 5f5f a90b 721d 0000 0072 1e00  init__..r....r..
 000019b0: 0000 721f 0000 0072 2000 0000 7235 0000  ..r....r ...r5..
 000019c0: 0072 4200 0000 7221 0000 0072 2200 0000  .rB...r!...r"...
-000019d0: 7204 0000 0072 1500 0000 7223 0000 0072  r....r....r#...r
+000019d0: 7202 0000 0072 1500 0000 7223 0000 0072  r....r....r#...r
 000019e0: 1a00 0000 721a 0000 0072 1800 0000 721b  ....r....r....r.
 000019f0: 0000 0072 4000 0000 df00 0000 730c 0000  ...r@.......s...
 00001a00: 000a 0104 050a 0302 0008 ff04 0472 4000  .............r@.
 00001a10: 0000 6300 0000 0000 0000 0000 0000 0000  ..c.............
 00001a20: 0000 0007 0000 0000 0000 0073 7800 0000  ...........sx...
 00001a30: 6500 5a01 6400 5a02 5500 6401 5a03 6504  e.Z.d.Z.U.d.Z.e.
 00001a40: 6505 6402 3c00 6504 6505 6403 3c00 6506  e.d.<.e.e.d.<.e.
@@ -458,17 +458,17 @@
 00001c90: 7210 0000 0072 1800 0000 721a 0000 0072  r....r....r....r
 00001ca0: 1b00 0000 7215 0000 0002 0100 0073 0800  ....r........s..
 00001cb0: 0000 0007 0e01 0601 0601 7a22 5361 7665  ..........z"Save
 00001cc0: 5072 6f63 6573 7345 6c65 6d65 6e74 5265  ProcessElementRe
 00001cd0: 7175 6573 742e 5f5f 696e 6974 5f5f 2901  quest.__init__).
 00001ce0: 4e29 0e72 1d00 0000 721e 0000 0072 1f00  N).r....r....r..
 00001cf0: 0000 7220 0000 0072 0b00 0000 7221 0000  ..r ...r....r!..
-00001d00: 0072 0200 0000 7235 0000 00da 1350 726f  .r....r5.....Pro
+00001d00: 0072 0400 0000 7235 0000 00da 1350 726f  .r....r5.....Pro
 00001d10: 6365 7373 456c 656d 656e 7456 616c 7565  cessElementValue
-00001d20: 7222 0000 0072 0300 0000 7204 0000 0072  r"...r....r....r
+00001d20: 7222 0000 0072 0500 0000 7202 0000 0072  r"...r....r....r
 00001d30: 1500 0000 7223 0000 0072 1a00 0000 721a  ....r#...r....r.
 00001d40: 0000 0072 1800 0000 721b 0000 0072 4700  ...r....r....rG.
 00001d50: 0000 f000 0000 7320 0000 000a 0104 0708  ......s ........
 00001d60: 0108 010e 0308 0108 0108 fd06 0a00 fc02  ................
 00001d70: 0202 0102 010c 0102 0102 fa72 4700 0000  ...........rG...
 00001d80: 6300 0000 0000 0000 0000 0000 0000 0000  c...............
 00001d90: 0004 0000 0000 0000 0073 4600 0000 6500  .........sF...e.
@@ -651,15 +651,15 @@
 000028a0: 0000 0072 1a00 0000 721b 0000 0072 1500  ...r....r....r..
 000028b0: 0000 7b01 0000 7308 0000 0000 030e 0106  ..{...s.........
 000028c0: 0106 017a 2643 6861 6e67 6550 726f 6365  ...z&ChangeProce
 000028d0: 7373 496e 6974 6961 746f 7252 6571 7565  ssInitiatorReque
 000028e0: 7374 2e5f 5f69 6e69 745f 5f29 024e 4ea9  st.__init__).NN.
 000028f0: 0b72 1d00 0000 721e 0000 0072 1f00 0000  .r....r....r....
 00002900: 7220 0000 0072 0b00 0000 7221 0000 0072  r ...r....r!...r
-00002910: 0300 0000 7222 0000 0072 0400 0000 7215  ....r"...r....r.
+00002910: 0500 0000 7222 0000 0072 0200 0000 7215  ....r"...r....r.
 00002920: 0000 0072 2300 0000 721a 0000 0072 1a00  ...r#...r....r..
 00002930: 0000 7218 0000 0072 1b00 0000 7253 0000  ..r....r....rS..
 00002940: 0068 0100 0073 2200 0000 0a01 0408 0801  .h...s".........
 00002950: 0c01 0c03 0801 0801 08fd 0607 0000 00ff  ................
 00002960: 0201 0200 0600 0600 0201 02fe 7253 0000  ............rS..
 00002970: 0063 0000 0000 0000 0000 0000 0000 0000  .c..............
 00002980: 0000 0400 0000 0000 0000 7346 0000 0065  ..........sF...e
@@ -748,18 +748,18 @@
 00002eb0: 0000 7239 0000 0072 5800 0000 7259 0000  ..r9...rX...rY..
 00002ec0: 0072 5a00 0000 7210 0000 0072 1800 0000  .rZ...r....r....
 00002ed0: 721a 0000 0072 1b00 0000 7215 0000 00b0  r....r....r.....
 00002ee0: 0100 0073 0e00 0000 000a 0e01 0601 0601  ...s............
 00002ef0: 0601 0601 0601 7a18 4669 6e64 5461 736b  ......z.FindTask
 00002f00: 5265 7175 6573 742e 5f5f 696e 6974 5f5f  Request.__init__
 00002f10: 2906 4e4e 4e4e 4e4e 290f 721d 0000 0072  ).NNNNNN).r....r
-00002f20: 1e00 0000 721f 0000 0072 2000 0000 7203  ....r....r ...r.
-00002f30: 0000 0072 3a00 0000 7221 0000 0072 0200  ...r:...r!...r..
+00002f20: 1e00 0000 721f 0000 0072 2000 0000 7205  ....r....r ...r.
+00002f30: 0000 0072 3a00 0000 7221 0000 0072 0400  ...r:...r!...r..
 00002f40: 0000 720b 0000 0072 3500 0000 da09 5461  ..r....r5.....Ta
-00002f50: 736b 5374 6174 6572 2200 0000 7204 0000  skStater"...r...
+00002f50: 736b 5374 6174 6572 2200 0000 7202 0000  skStater"...r...
 00002f60: 0072 1500 0000 7223 0000 0072 1a00 0000  .r....r#...r....
 00002f70: 721a 0000 0072 1800 0000 721b 0000 0072  r....r....r....r
 00002f80: 5700 0000 9501 0000 733c 0000 000a 0104  W.......s<......
 00002f90: 0a0c 010c 0110 0110 0112 0110 0308 0108  ................
 00002fa0: 0108 0108 0108 0108 fa06 0b00 0100 0100  ................
 00002fb0: 0100 0100 0100 f902 0206 0106 010a 010a  ................
 00002fc0: 010c 010a 0102 0102 f772 5700 0000 6300  .........rW...c.
@@ -785,15 +785,15 @@
 00003100: 0372 1700 0000 725d 0000 0072 1000 0000  .r....r]...r....
 00003110: 7218 0000 0072 1a00 0000 721b 0000 0072  r....r....r....r
 00003120: 1500 0000 cd01 0000 7304 0000 0000 010e  ........s.......
 00003130: 017a 1946 696e 6454 6173 6b52 6573 706f  .z.FindTaskRespo
 00003140: 6e73 652e 5f5f 696e 6974 5f5f 290a 721d  nse.__init__).r.
 00003150: 0000 0072 1e00 0000 721f 0000 0072 2000  ...r....r....r .
 00003160: 0000 7222 0000 0072 3500 0000 725e 0000  ..r"...r5...r^..
-00003170: 0072 0400 0000 7215 0000 0072 2300 0000  .r....r....r#...
+00003170: 0072 0200 0000 7215 0000 0072 2300 0000  .r....r....r#...
 00003180: 721a 0000 0072 1a00 0000 7218 0000 0072  r....r....r....r
 00003190: 1b00 0000 725c 0000 00c3 0100 0073 0a00  ....r\.......s..
 000031a0: 0000 0801 0406 0200 08ff 0404 725c 0000  ............r\..
 000031b0: 0063 0000 0000 0000 0000 0000 0000 0000  .c..............
 000031c0: 0000 0400 0000 0000 0000 7342 0000 0065  ..........sB...e
 000031d0: 005a 0164 005a 0255 0064 015a 0365 0465  .Z.d.Z.U.d.Z.e.e
 000031e0: 0564 023c 0064 0264 0364 0464 059c 0269  .d.<.d.d.d.d...i
@@ -842,15 +842,15 @@
 00003490: 0000 0072 1000 0000 7218 0000 0072 1a00  ...r....r....r..
 000034a0: 0000 721b 0000 0072 1500 0000 ef01 0000  ..r....r........
 000034b0: 7304 0000 0000 010e 017a 1d52 6574 7269  s........z.Retri
 000034c0: 6576 6554 6173 6b52 6573 706f 6e73 652e  eveTaskResponse.
 000034d0: 5f5f 696e 6974 5f5f a90b 721d 0000 0072  __init__..r....r
 000034e0: 1e00 0000 721f 0000 0072 2000 0000 7235  ....r....r ...r5
 000034f0: 0000 0072 6700 0000 7221 0000 0072 2200  ...rg...r!...r".
-00003500: 0000 7204 0000 0072 1500 0000 7223 0000  ..r....r....r#..
+00003500: 0000 7202 0000 0072 1500 0000 7223 0000  ..r....r....r#..
 00003510: 0072 1a00 0000 721a 0000 0072 1800 0000  .r....r....r....
 00003520: 721b 0000 0072 6500 0000 e301 0000 730c  r....re.......s.
 00003530: 0000 000a 0104 050a 0302 0008 ff04 0472  ...............r
 00003540: 6500 0000 6300 0000 0000 0000 0000 0000  e...c...........
 00003550: 0000 0000 0004 0000 0000 0000 0073 4600  .............sF.
 00003560: 0000 6500 5a01 6400 5a02 5500 6401 5a03  ..e.Z.d.Z.U.d.Z.
 00003570: 6504 6a05 6506 6402 3c00 6402 6402 6403  e.j.e.d.<.d.d.d.
@@ -1108,17 +1108,17 @@
 00004530: 0000 7210 0000 0072 1800 0000 721a 0000  ..r....r....r...
 00004540: 0072 1b00 0000 7215 0000 0098 0200 0073  .r....r........s
 00004550: 0800 0000 0007 0e01 0601 0601 7a1f 5361  ............z.Sa
 00004560: 7665 5461 736b 456c 656d 656e 7452 6571  veTaskElementReq
 00004570: 7565 7374 2e5f 5f69 6e69 745f 5f29 014e  uest.__init__).N
 00004580: 290e 721d 0000 0072 1e00 0000 721f 0000  ).r....r....r...
 00004590: 0072 2000 0000 720b 0000 0072 2100 0000  .r ...r....r!...
-000045a0: 7202 0000 0072 3500 0000 da10 5461 736b  r....r5.....Task
+000045a0: 7204 0000 0072 3500 0000 da10 5461 736b  r....r5.....Task
 000045b0: 456c 656d 656e 7456 616c 7565 7222 0000  ElementValuer"..
-000045c0: 0072 0300 0000 7204 0000 0072 1500 0000  .r....r....r....
+000045c0: 0072 0500 0000 7202 0000 0072 1500 0000  .r....r....r....
 000045d0: 7223 0000 0072 1a00 0000 721a 0000 0072  r#...r....r....r
 000045e0: 1800 0000 721b 0000 0072 7500 0000 8602  ....r....ru.....
 000045f0: 0000 7320 0000 000a 0104 0708 0108 010e  ..s ............
 00004600: 0308 0108 0108 fd06 0a00 fc02 0202 0102  ................
 00004610: 010c 0102 0102 fa72 7500 0000 6300 0000  .......ru...c...
 00004620: 0000 0000 0000 0000 0000 0000 0004 0000  ................
 00004630: 0000 0000 0073 4600 0000 6500 5a01 6400  .....sF...e.Z.d.
@@ -1290,16 +1290,16 @@
 00005090: 7210 0000 0072 1800 0000 721a 0000 0072  r....r....r....r
 000050a0: 1b00 0000 7215 0000 0011 0300 0073 0600  ....r........s..
 000050b0: 0000 0001 0e01 0601 7a2a 5361 7665 5461  ........z*SaveTa
 000050c0: 736b 4a73 6f6e 466f 726d 7356 616c 7565  skJsonFormsValue
 000050d0: 4461 7461 5265 7175 6573 742e 5f5f 696e  DataRequest.__in
 000050e0: 6974 5f5f 2901 4e29 0c72 1d00 0000 721e  it__).N).r....r.
 000050f0: 0000 0072 1f00 0000 7220 0000 0072 0b00  ...r....r ...r..
-00005100: 0000 7221 0000 0072 0500 0000 7204 0000  ..r!...r....r...
-00005110: 0072 2200 0000 7203 0000 0072 1500 0000  .r"...r....r....
+00005100: 0000 7221 0000 0072 0300 0000 7202 0000  ..r!...r....r...
+00005110: 0072 2200 0000 7205 0000 0072 1500 0000  .r"...r....r....
 00005120: 7223 0000 0072 1a00 0000 721a 0000 0072  r#...r....r....r
 00005130: 1800 0000 721b 0000 0072 7e00 0000 0203  ....r....r~.....
 00005140: 0000 730e 0000 000a 0104 0608 0110 0308  ..s.............
 00005150: 0108 fe06 0572 7e00 0000 6300 0000 0000  .....r~...c.....
 00005160: 0000 0000 0000 0000 0000 0004 0000 0000  ................
 00005170: 0000 0073 4600 0000 6500 5a01 6400 5a02  ...sF...e.Z.d.Z.
 00005180: 5500 6401 5a03 6504 6a05 6506 6402 3c00  U.d.Z.e.j.e.d.<.
@@ -1351,15 +1351,15 @@
 00005460: 7210 0000 0072 1800 0000 721a 0000 0072  r....r....r....r
 00005470: 1b00 0000 7215 0000 0037 0300 0073 0600  ....r....7...s..
 00005480: 0000 0001 0e01 0601 7a1d 4170 7065 6e64  ........z.Append
 00005490: 5461 736b 4c6f 6752 6571 7565 7374 2e5f  TaskLogRequest._
 000054a0: 5f69 6e69 745f 5f29 0c72 1d00 0000 721e  _init__).r....r.
 000054b0: 0000 0072 1f00 0000 7220 0000 0072 0b00  ...r....r ...r..
 000054c0: 0000 7221 0000 0072 3500 0000 7283 0000  ..r!...r5...r...
-000054d0: 0072 2200 0000 7204 0000 0072 1500 0000  .r"...r....r....
+000054d0: 0072 2200 0000 7202 0000 0072 1500 0000  .r"...r....r....
 000054e0: 7223 0000 0072 1a00 0000 721a 0000 0072  r#...r....r....r
 000054f0: 1800 0000 721b 0000 0072 8100 0000 2803  ....r....r....(.
 00005500: 0000 730e 0000 000a 0104 0608 010a 0308  ..s.............
 00005510: 0108 fe06 0572 8100 0000 6300 0000 0000  .....r....c.....
 00005520: 0000 0000 0000 0000 0000 0004 0000 0000  ................
 00005530: 0000 0073 4600 0000 6500 5a01 6400 5a02  ...sF...e.Z.d.Z.
 00005540: 5500 6401 5a03 6504 6a05 6506 6402 3c00  U.d.Z.e.j.e.d.<.
@@ -1378,18 +1378,18 @@
 00005610: 0000 0000 010e 017a 1e41 7070 656e 6454  .......z.AppendT
 00005620: 6173 6b4c 6f67 5265 7370 6f6e 7365 2e5f  askLogResponse._
 00005630: 5f69 6e69 745f 5f72 6b00 0000 721a 0000  _init__rk...r...
 00005640: 0072 1a00 0000 7218 0000 0072 1b00 0000  .r....r....r....
 00005650: 7284 0000 003d 0300 0073 0c00 0000 0a01  r....=...s......
 00005660: 0405 0a03 0200 08ff 0404 7284 0000 004e  ..........r....N
 00005670: 2933 da06 7479 7069 6e67 7202 0000 0072  )3..typingr....r
-00005680: 0300 0000 7204 0000 0072 0500 0000 5a16  ....r....r....Z.
-00005690: 6b75 666c 6f77 5f72 6573 742e 5f67 656e  kuflow_rest._gen
-000056a0: 6572 6174 6564 7206 0000 00da 0b6b 7566  eratedr......kuf
-000056b0: 6c6f 775f 7265 7374 7207 0000 0072 3500  low_restr....r5.
+00005680: 0300 0000 7204 0000 0072 0500 0000 da0b  ....r....r......
+00005690: 6b75 666c 6f77 5f72 6573 7472 0600 0000  kuflow_restr....
+000056a0: 7235 0000 005a 166b 7566 6c6f 775f 7265  r5...Z.kuflow_re
+000056b0: 7374 2e5f 6765 6e65 7261 7465 6472 0700  st._generatedr..
 000056c0: 0000 da05 4d6f 6465 6c72 0800 0000 7224  ....Modelr....r$
 000056d0: 0000 0072 2a00 0000 722e 0000 0072 2f00  ...r*...r....r/.
 000056e0: 0000 7232 0000 0072 3600 0000 723c 0000  ..r2...r6...r<..
 000056f0: 0072 3f00 0000 7240 0000 0072 4700 0000  .r?...r@...rG...
 00005700: 724d 0000 0072 4f00 0000 7250 0000 0072  rM...rO...rP...r
 00005710: 5100 0000 7252 0000 0072 5300 0000 7256  Q...rR...rS...rV
 00005720: 0000 0072 5700 0000 725c 0000 0072 5f00  ...rW...r\...r_.
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/models/_models.py` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/models/_models.py`

 * *Files 1% similar despite different names*

```diff
@@ -19,18 +19,18 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import List, Optional, Any, Dict
+from typing import Any, Dict, List, Optional
 
-from kuflow_rest._generated import _serialization
 from kuflow_rest import models as models_rest
+from kuflow_rest._generated import _serialization
 
 ########################
 # For Workflows
 ########################
 
 
 class WorkflowRequest(_serialization.Model):
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/__init__.py` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -23,9 +23,8 @@
 # SOFTWARE.
 #
 
 from ._save_process_element_utils import SaveProcessElementRequestUtils
 from ._save_task_element_utils import SaveTaskElementRequestUtils
 from ._save_task_json_forms_value_data_request_utils import SaveTaskJsonFormsValueDataRequestUtils
 
-
 __all__ = ["SaveProcessElementRequestUtils", "SaveTaskElementRequestUtils", "SaveTaskJsonFormsValueDataRequestUtils"]
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/__pycache__/_save_process_element_utils.cpython-38.pyc` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/__pycache__/_save_process_element_utils.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 11220 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 1% similar despite different names*

```diff
@@ -1,64 +1,64 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 d42b 0000  U.......=S.d.+..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 c42b 0000  U..........d.+..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 c200 0000 6400  .....@...s....d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 0100 6400  d.l.m.Z.m.Z...d.
-00000040: 6402 6c03 6d04 5a04 0100 6400 6403 6c05  d.l.m.Z...d.d.l.
+00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
+00000040: 6d03 5a03 6d04 5a04 0100 6400 6403 6c05  m.Z.m.Z...d.d.l.
 00000050: 6d06 5a06 0100 6400 6404 6c07 6d08 5a08  m.Z...d.d.l.m.Z.
 00000060: 6d09 5a09 6d0a 5a0a 0100 6400 6405 6c0b  m.Z.m.Z...d.d.l.
 00000070: 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f  m.Z.m.Z.m.Z.m.Z.
 00000080: 6d10 5a10 6d11 5a11 6d12 5a12 6d13 5a13  m.Z.m.Z.m.Z.m.Z.
 00000090: 6d14 5a14 6d15 5a15 6d16 5a16 6d17 5a17  m.Z.m.Z.m.Z.m.Z.
 000000a0: 6d18 5a18 6d19 5a19 6d1a 5a1a 6d1b 5a1b  m.Z.m.Z.m.Z.m.Z.
 000000b0: 6d1c 5a1c 6d1d 5a1d 6d1e 5a1e 6d1f 5a1f  m.Z.m.Z.m.Z.m.Z.
 000000c0: 0100 6406 6407 6c20 6d21 5a21 0100 4700  ..d.d.l m!Z!..G.
-000000d0: 6408 6409 8400 6409 6508 8303 5a22 4700  d.d...d.e...Z"G.
+000000d0: 6408 6409 8400 6409 650a 8303 5a22 4700  d.d...d.e...Z"G.
 000000e0: 640a 640b 8400 640b 8302 5a23 640c 5300  d.d...d...Z#d.S.
-000000f0: 290d e900 0000 0029 02da 044c 6973 74da  )......)...List.
-00000100: 084f 7074 696f 6e61 6c29 01da 0464 6174  .Optional)...dat
-00000110: 6529 01da 1350 726f 6365 7373 456c 656d  e)...ProcessElem
-00000120: 656e 7456 616c 7565 2903 da1b 5072 6f63  entValue)...Proc
-00000130: 6573 7345 6c65 6d65 6e74 5661 6c75 6541  essElementValueA
-00000140: 6363 6573 736f 72da 1145 6c65 6d65 6e74  ccessor..Element
-00000150: 5661 6c75 6555 6e69 6f6e da16 456c 656d  ValueUnion..Elem
-00000160: 656e 7456 616c 7565 5369 6d70 6c65 5479  entValueSimpleTy
-00000170: 7065 2914 da17 6765 745f 656c 656d 656e  pe)...get_elemen
-00000180: 745f 7661 6c75 655f 7661 6c69 64da 1a67  t_value_valid..g
-00000190: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
-000001a0: 5f76 616c 6964 5f61 74da 1773 6574 5f65  _valid_at..set_e
-000001b0: 6c65 6d65 6e74 5f76 616c 7565 5f76 616c  lement_value_val
-000001c0: 6964 da1a 7365 745f 656c 656d 656e 745f  id..set_element_
-000001d0: 7661 6c75 655f 7661 6c69 645f 6174 da11  value_valid_at..
-000001e0: 7365 745f 656c 656d 656e 745f 7661 6c75  set_element_valu
-000001f0: 65da 1673 6574 5f65 6c65 6d65 6e74 5f76  e..set_element_v
-00000200: 616c 7565 5f6c 6973 74da 1161 6464 5f65  alue_list..add_e
-00000210: 6c65 6d65 6e74 5f76 616c 7565 da16 6164  lement_value..ad
-00000220: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
-00000230: 6c69 7374 da18 6765 745f 656c 656d 656e  list..get_elemen
-00000240: 745f 7661 6c75 655f 6173 5f73 7472 da19  t_value_as_str..
-00000250: 6669 6e64 5f65 6c65 6d65 6e74 5f76 616c  find_element_val
-00000260: 7565 5f61 735f 7374 72da 1d67 6574 5f65  ue_as_str..get_e
-00000270: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
-00000280: 7374 725f 6c69 7374 da1a 6765 745f 656c  str_list..get_el
-00000290: 656d 656e 745f 7661 6c75 655f 6173 5f66  ement_value_as_f
-000002a0: 6c6f 6174 da1b 6669 6e64 5f65 6c65 6d65  loat..find_eleme
-000002b0: 6e74 5f76 616c 7565 5f61 735f 666c 6f61  nt_value_as_floa
-000002c0: 74da 1f67 6574 5f65 6c65 6d65 6e74 5f76  t..get_element_v
-000002d0: 616c 7565 5f61 735f 666c 6f61 745f 6c69  alue_as_float_li
-000002e0: 7374 da19 6765 745f 656c 656d 656e 745f  st..get_element_
-000002f0: 7661 6c75 655f 6173 5f64 6174 65da 1a66  value_as_date..f
-00000300: 696e 645f 656c 656d 656e 745f 7661 6c75  ind_element_valu
-00000310: 655f 6173 5f64 6174 65da 1e67 6574 5f65  e_as_date..get_e
-00000320: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
-00000330: 6461 7465 5f6c 6973 74da 1967 6574 5f65  date_list..get_e
-00000340: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
-00000350: 6469 6374 da1a 6669 6e64 5f65 6c65 6d65  dict..find_eleme
-00000360: 6e74 5f76 616c 7565 5f61 735f 6469 6374  nt_value_as_dict
-00000370: da1e 6765 745f 656c 656d 656e 745f 7661  ..get_element_va
-00000380: 6c75 655f 6173 5f64 6963 745f 6c69 7374  lue_as_dict_list
+000000f0: 290d e900 0000 0029 01da 0464 6174 6529  )......)...date)
+00000100: 02da 044c 6973 74da 084f 7074 696f 6e61  ...List..Optiona
+00000110: 6c29 01da 1350 726f 6365 7373 456c 656d  l)...ProcessElem
+00000120: 656e 7456 616c 7565 2903 da16 456c 656d  entValue)...Elem
+00000130: 656e 7456 616c 7565 5369 6d70 6c65 5479  entValueSimpleTy
+00000140: 7065 da11 456c 656d 656e 7456 616c 7565  pe..ElementValue
+00000150: 556e 696f 6eda 1b50 726f 6365 7373 456c  Union..ProcessEl
+00000160: 656d 656e 7456 616c 7565 4163 6365 7373  ementValueAccess
+00000170: 6f72 2914 da11 6164 645f 656c 656d 656e  or)...add_elemen
+00000180: 745f 7661 6c75 65da 1661 6464 5f65 6c65  t_value..add_ele
+00000190: 6d65 6e74 5f76 616c 7565 5f6c 6973 74da  ment_value_list.
+000001a0: 1a66 696e 645f 656c 656d 656e 745f 7661  .find_element_va
+000001b0: 6c75 655f 6173 5f64 6174 65da 1a66 696e  lue_as_date..fin
+000001c0: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
+000001d0: 6173 5f64 6963 74da 1b66 696e 645f 656c  as_dict..find_el
+000001e0: 656d 656e 745f 7661 6c75 655f 6173 5f66  ement_value_as_f
+000001f0: 6c6f 6174 da19 6669 6e64 5f65 6c65 6d65  loat..find_eleme
+00000200: 6e74 5f76 616c 7565 5f61 735f 7374 72da  nt_value_as_str.
+00000210: 1967 6574 5f65 6c65 6d65 6e74 5f76 616c  .get_element_val
+00000220: 7565 5f61 735f 6461 7465 da1e 6765 745f  ue_as_date..get_
+00000230: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
+00000240: 5f64 6174 655f 6c69 7374 da19 6765 745f  _date_list..get_
+00000250: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
+00000260: 5f64 6963 74da 1e67 6574 5f65 6c65 6d65  _dict..get_eleme
+00000270: 6e74 5f76 616c 7565 5f61 735f 6469 6374  nt_value_as_dict
+00000280: 5f6c 6973 74da 1a67 6574 5f65 6c65 6d65  _list..get_eleme
+00000290: 6e74 5f76 616c 7565 5f61 735f 666c 6f61  nt_value_as_floa
+000002a0: 74da 1f67 6574 5f65 6c65 6d65 6e74 5f76  t..get_element_v
+000002b0: 616c 7565 5f61 735f 666c 6f61 745f 6c69  alue_as_float_li
+000002c0: 7374 da18 6765 745f 656c 656d 656e 745f  st..get_element_
+000002d0: 7661 6c75 655f 6173 5f73 7472 da1d 6765  value_as_str..ge
+000002e0: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
+000002f0: 6173 5f73 7472 5f6c 6973 74da 1767 6574  as_str_list..get
+00000300: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
+00000310: 616c 6964 da1a 6765 745f 656c 656d 656e  alid..get_elemen
+00000320: 745f 7661 6c75 655f 7661 6c69 645f 6174  t_value_valid_at
+00000330: da11 7365 745f 656c 656d 656e 745f 7661  ..set_element_va
+00000340: 6c75 65da 1673 6574 5f65 6c65 6d65 6e74  lue..set_element
+00000350: 5f76 616c 7565 5f6c 6973 74da 1773 6574  _value_list..set
+00000360: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
+00000370: 616c 6964 da1a 7365 745f 656c 656d 656e  alid..set_elemen
+00000380: 745f 7661 6c75 655f 7661 6c69 645f 6174  t_value_valid_at
 00000390: e902 0000 0029 01da 1953 6176 6550 726f  .....)...SavePro
 000003a0: 6365 7373 456c 656d 656e 7452 6571 7565  cessElementReque
 000003b0: 7374 6300 0000 0000 0000 0000 0000 0000  stc.............
 000003c0: 0000 0003 0000 0040 0000 0073 3e00 0000  .......@...s>...
 000003d0: 6500 5a01 6400 5a02 6503 6401 9c01 6402  e.Z.d.Z.e.d...d.
 000003e0: 6403 8404 5a04 6505 6506 1900 6404 9c01  d...Z.e.e...d...
 000003f0: 6405 6406 8404 5a07 6505 6508 1900 6407  d.d...Z.e.e...d.
@@ -73,49 +73,49 @@
 00000480: 646b 2d70 7974 686f 6e2f 6b75 666c 6f77  dk-python/kuflow
 00000490: 2d74 656d 706f 7261 6c2d 6163 7469 7669  -temporal-activi
 000004a0: 7479 2d6b 7566 6c6f 772f 6b75 666c 6f77  ty-kuflow/kuflow
 000004b0: 5f74 656d 706f 7261 6c5f 6163 7469 7669  _temporal_activi
 000004c0: 7479 5f6b 7566 6c6f 772f 7574 696c 732f  ty_kuflow/utils/
 000004d0: 5f73 6176 655f 7072 6f63 6573 735f 656c  _save_process_el
 000004e0: 656d 656e 745f 7574 696c 732e 7079 da08  ement_utils.py..
-000004f0: 5f5f 696e 6974 5f5f 3d00 0000 7302 0000  __init__=...s...
+000004f0: 5f5f 696e 6974 5f5f 3a00 0000 7302 0000  __init__:...s...
 00000500: 0000 017a 1843 7572 7265 6e74 4163 6365  ...z.CurrentAcce
 00000510: 7373 6f72 2e5f 5f69 6e69 745f 5f29 01da  ssor.__init__)..
 00000520: 0e65 6c65 6d65 6e74 5f76 616c 7565 7363  .element_valuesc
 00000530: 0200 0000 0000 0000 0000 0000 0200 0000  ................
 00000540: 0200 0000 4300 0000 7322 0000 0074 007c  ....C...s"...t.|
 00000550: 0183 0164 016b 0272 1664 007c 006a 015f  ...d.k.r.d.|.j._
 00000560: 026e 087c 017c 006a 015f 0264 0053 00a9  .n.|.|.j._.d.S..
 00000570: 024e 7201 0000 0029 03da 036c 656e 7221  .Nr....)...lenr!
 00000580: 0000 0072 2600 0000 2902 7222 0000 0072  ...r&...).r"...r
 00000590: 2600 0000 7223 0000 0072 2300 0000 7224  &...r#...r#...r$
 000005a0: 0000 00da 1273 6574 5f65 6c65 6d65 6e74  .....set_element
-000005b0: 5f76 616c 7565 7340 0000 0073 0600 0000  _values@...s....
+000005b0: 5f76 616c 7565 733d 0000 0073 0600 0000  _values=...s....
 000005c0: 0001 0c01 0a02 7a22 4375 7272 656e 7441  ......z"CurrentA
 000005d0: 6363 6573 736f 722e 7365 745f 656c 656d  ccessor.set_elem
 000005e0: 656e 745f 7661 6c75 6573 2901 da06 7265  ent_values)...re
 000005f0: 7475 726e 6301 0000 0000 0000 0000 0000  turnc...........
 00000600: 0001 0000 0002 0000 0043 0000 0073 2800  .........C...s(.
 00000610: 0000 7c00 6a00 6a01 6400 6b08 731c 7402  ..|.j.j.d.k.s.t.
 00000620: 7c00 6a00 6a01 8301 6401 6b02 7220 6700  |.j.j...d.k.r g.
 00000630: 5300 7c00 6a00 6a01 5300 7227 0000 0029  S.|.j.j.S.r'...)
 00000640: 0372 2100 0000 7226 0000 0072 2800 0000  .r!...r&...r(...
 00000650: 2901 7222 0000 0072 2300 0000 7223 0000  ).r"...r#...r#..
 00000660: 0072 2400 0000 da12 6765 745f 656c 656d  .r$.....get_elem
-00000670: 656e 745f 7661 6c75 6573 4600 0000 7306  ent_valuesF...s.
+00000670: 656e 745f 7661 6c75 6573 4300 0000 7306  ent_valuesC...s.
 00000680: 0000 0000 011c 0104 027a 2243 7572 7265  .........z"Curre
 00000690: 6e74 4163 6365 7373 6f72 2e67 6574 5f65  ntAccessor.get_e
 000006a0: 6c65 6d65 6e74 5f76 616c 7565 734e 290a  lement_valuesN).
 000006b0: da08 5f5f 6e61 6d65 5f5f da0a 5f5f 6d6f  ..__name__..__mo
 000006c0: 6475 6c65 5f5f da0c 5f5f 7175 616c 6e61  dule__..__qualna
-000006d0: 6d65 5f5f 721e 0000 0072 2500 0000 7202  me__r....r%...r.
+000006d0: 6d65 5f5f 721e 0000 0072 2500 0000 7203  me__r....r%...r.
 000006e0: 0000 0072 0700 0000 7229 0000 0072 0500  ...r....r)...r..
 000006f0: 0000 722b 0000 0072 2300 0000 7223 0000  ..r+...r#...r#..
 00000700: 0072 2300 0000 7224 0000 0072 1f00 0000  .r#...r$...r....
-00000710: 3c00 0000 7306 0000 0008 010e 0312 0672  <...s..........r
+00000710: 3900 0000 7306 0000 0008 010e 0312 0672  9...s..........r
 00000720: 1f00 0000 6300 0000 0000 0000 0000 0000  ....c...........
 00000730: 0000 0000 0006 0000 0040 0000 0073 f001  .........@...s..
 00000740: 0000 6500 5a01 6400 5a02 6503 6504 6505  ..e.Z.d.Z.e.e.e.
 00000750: 6401 9c02 6402 6403 8404 8301 5a06 6503  d...d.d.....Z.e.
 00000760: 6504 6507 6505 6404 9c03 6405 6406 8404  e.e.e.d...d.d...
 00000770: 8301 5a08 6503 6504 6509 6505 1900 6504  ..Z.e.e.e.e...e.
 00000780: 6407 9c03 6408 6409 8404 8301 5a0a 6503  d...d.d.....Z.e.
@@ -160,18 +160,18 @@
 000009f0: 5361 7665 5461 736b 456c 656d 656e 7420  SaveTaskElement 
 00000a00: 7265 7175 6573 742e 0a0a 2020 2020 2020  request...      
 00000a10: 2020 5265 7475 726e 733a 0a20 2020 2020    Returns:.     
 00000a20: 2020 2020 2020 2054 7275 6520 6966 2061         True if a
 00000a30: 6c6c 2072 656c 6174 6564 2076 616c 6964  ll related valid
 00000a40: 2076 616c 7565 7320 6172 6520 5452 5545   values are TRUE
 00000a50: 2c20 6f74 6865 7277 6973 6520 4661 6c73  , otherwise Fals
-00000a60: 652e 0a20 2020 2020 2020 2029 0272 0900  e..        ).r..
+00000a60: 652e 0a20 2020 2020 2020 2029 0272 1700  e..        ).r..
 00000a70: 0000 721f 0000 0072 2000 0000 7223 0000  ..r....r ...r#..
-00000a80: 0072 2300 0000 7224 0000 0072 0900 0000  .r#...r$...r....
-00000a90: 4e00 0000 7302 0000 0000 0b7a 3653 6176  N...s......z6Sav
+00000a80: 0072 2300 0000 7224 0000 0072 1700 0000  .r#...r$...r....
+00000a90: 4b00 0000 7302 0000 0000 0b7a 3653 6176  K...s......z6Sav
 00000aa0: 6550 726f 6365 7373 456c 656d 656e 7452  eProcessElementR
 00000ab0: 6571 7565 7374 5574 696c 732e 6765 745f  equestUtils.get_
 00000ac0: 656c 656d 656e 745f 7661 6c75 655f 7661  element_value_va
 00000ad0: 6c69 6429 0372 2100 0000 da05 696e 6465  lid).r!.....inde
 00000ae0: 7872 2a00 0000 6302 0000 0000 0000 0000  xr*...c.........
 00000af0: 0000 0002 0000 0003 0000 0043 0000 0073  ...........C...s
 00000b00: 0e00 0000 7400 7401 7c00 8301 7c01 8302  ....t.t.|...|...
@@ -189,17 +189,17 @@
 00000bc0: 656d 656e 7420 7661 6c75 6520 696e 6465  ement value inde
 00000bd0: 782e 0a0a 2020 2020 2020 2020 5265 7475  x...        Retu
 00000be0: 726e 733a 0a20 2020 2020 2020 2020 2020  rns:.           
 00000bf0: 2054 6865 2072 6571 7565 7374 6564 2076   The requested v
 00000c00: 616c 6964 2076 616c 7565 2069 6620 6974  alid value if it
 00000c10: 2065 7869 7374 732c 206f 7468 6572 7769   exists, otherwi
 00000c20: 7365 204e 6f6e 652e 0a20 2020 2020 2020  se None..       
-00000c30: 2029 0272 0a00 0000 721f 0000 0029 0272   ).r....r....).r
+00000c30: 2029 0272 1800 0000 721f 0000 0029 0272   ).r....r....).r
 00000c40: 2100 0000 7230 0000 0072 2300 0000 7223  !...r0...r#...r#
-00000c50: 0000 0072 2400 0000 720a 0000 005b 0000  ...r$...r....[..
+00000c50: 0000 0072 2400 0000 7218 0000 0058 0000  ...r$...r....X..
 00000c60: 0073 0200 0000 000c 7a39 5361 7665 5072  .s......z9SavePr
 00000c70: 6f63 6573 7345 6c65 6d65 6e74 5265 7175  ocessElementRequ
 00000c80: 6573 7455 7469 6c73 2e67 6574 5f65 6c65  estUtils.get_ele
 00000c90: 6d65 6e74 5f76 616c 7565 5f76 616c 6964  ment_value_valid
 00000ca0: 5f61 7429 0372 2100 0000 da05 7661 6c69  _at).r!.....vali
 00000cb0: 6472 2a00 0000 6302 0000 0000 0000 0000  dr*...c.........
 00000cc0: 0000 0002 0000 0003 0000 0043 0000 0073  ...........C...s
@@ -214,17 +214,17 @@
 00000d50: 5461 736b 456c 656d 656e 7420 7265 7175  TaskElement requ
 00000d60: 6573 742e 0a20 2020 2020 2020 2020 2020  est..           
 00000d70: 2076 616c 6964 3a20 5468 6520 7661 6c69   valid: The vali
 00000d80: 6420 7661 6c75 652e 0a0a 2020 2020 2020  d value...      
 00000d90: 2020 5265 7475 726e 733a 0a20 2020 2020    Returns:.     
 00000da0: 2020 2020 2020 2054 6865 2070 6173 7365         The passe
 00000db0: 6420 7461 736b 2e0a 2020 2020 2020 2020  d task..        
-00000dc0: 2902 720b 0000 0072 1f00 0000 2902 7221  ).r....r....).r!
+00000dc0: 2902 721b 0000 0072 1f00 0000 2902 7221  ).r....r....).r!
 00000dd0: 0000 0072 3100 0000 7223 0000 0072 2300  ...r1...r#...r#.
-00000de0: 0000 7224 0000 0072 0b00 0000 6900 0000  ..r$...r....i...
+00000de0: 0000 7224 0000 0072 1b00 0000 6600 0000  ..r$...r....f...
 00000df0: 7304 0000 0000 0c0e 027a 3653 6176 6550  s........z6SaveP
 00000e00: 726f 6365 7373 456c 656d 656e 7452 6571  rocessElementReq
 00000e10: 7565 7374 5574 696c 732e 7365 745f 656c  uestUtils.set_el
 00000e20: 656d 656e 745f 7661 6c75 655f 7661 6c69  ement_value_vali
 00000e30: 6429 0472 2100 0000 7231 0000 0072 3000  d).r!...r1...r0.
 00000e40: 0000 722a 0000 0063 0300 0000 0000 0000  ..r*...c........
 00000e50: 0000 0000 0300 0000 0400 0000 4300 0000  ............C...
@@ -242,18 +242,18 @@
 00000f10: 6520 7661 6c69 6420 7661 6c75 652e 0a20  e valid value.. 
 00000f20: 2020 2020 2020 2020 2020 2069 6e64 6578             index
 00000f30: 3a20 5468 6520 656c 656d 656e 7420 7661  : The element va
 00000f40: 6c75 6520 696e 6465 782e 0a0a 2020 2020  lue index...    
 00000f50: 2020 2020 5265 7475 726e 733a 0a20 2020      Returns:.   
 00000f60: 2020 2020 2020 2020 2054 6865 2070 6173           The pas
 00000f70: 7365 6420 7461 736b 2e0a 2020 2020 2020  sed task..      
-00000f80: 2020 2902 720c 0000 0072 1f00 0000 2903    ).r....r....).
+00000f80: 2020 2902 721c 0000 0072 1f00 0000 2903    ).r....r....).
 00000f90: 7221 0000 0072 3100 0000 7230 0000 0072  r!...r1...r0...r
-00000fa0: 2300 0000 7223 0000 0072 2400 0000 720c  #...r#...r$...r.
-00000fb0: 0000 0079 0000 0073 0400 0000 000f 1002  ...y...s........
+00000fa0: 2300 0000 7223 0000 0072 2400 0000 721c  #...r#...r$...r.
+00000fb0: 0000 0076 0000 0073 0400 0000 000f 1002  ...v...s........
 00000fc0: 7a39 5361 7665 5072 6f63 6573 7345 6c65  z9SaveProcessEle
 00000fd0: 6d65 6e74 5265 7175 6573 7455 7469 6c73  mentRequestUtils
 00000fe0: 2e73 6574 5f65 6c65 6d65 6e74 5f76 616c  .set_element_val
 00000ff0: 7565 5f76 616c 6964 5f61 744e 2903 7221  ue_valid_atN).r!
 00001000: 0000 00da 0d65 6c65 6d65 6e74 5f76 616c  .....element_val
 00001010: 7565 722a 0000 0063 0200 0000 0000 0000  uer*...c........
 00001020: 0000 0000 0200 0000 0300 0000 4300 0000  ............C...
@@ -271,17 +271,17 @@
 000010e0: 2049 6620 7468 6520 7661 6c75 6520 6973   If the value is
 000010f0: 204e 6f6e 652c 2061 6c6c 2063 7572 7265   None, all curre
 00001100: 6e74 2076 616c 7565 7320 6172 6520 7265  nt values are re
 00001110: 6d6f 7665 642e 0a0a 2020 2020 2020 2020  moved...        
 00001120: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 00001130: 2020 2020 2054 6865 2070 6173 7365 6420       The passed 
 00001140: 7461 736b 2e0a 2020 2020 2020 2020 2902  task..        ).
-00001150: 720d 0000 0072 1f00 0000 a902 7221 0000  r....r......r!..
+00001150: 7219 0000 0072 1f00 0000 a902 7221 0000  r....r......r!..
 00001160: 0072 3200 0000 7223 0000 0072 2300 0000  .r2...r#...r#...
-00001170: 7224 0000 0072 0d00 0000 8c00 0000 7304  r$...r........s.
+00001170: 7224 0000 0072 1900 0000 8900 0000 7304  r$...r........s.
 00001180: 0000 0000 0e0e 027a 3053 6176 6550 726f  .......z0SavePro
 00001190: 6365 7373 456c 656d 656e 7452 6571 7565  cessElementReque
 000011a0: 7374 5574 696c 732e 7365 745f 656c 656d  stUtils.set_elem
 000011b0: 656e 745f 7661 6c75 6529 0372 2100 0000  ent_value).r!...
 000011c0: 7226 0000 0072 2a00 0000 6302 0000 0000  r&...r*...c.....
 000011d0: 0000 0000 0000 0002 0000 0003 0000 0043  ...............C
 000011e0: 0000 0073 1200 0000 7400 7401 7c00 8301  ...s....t.t.|...
@@ -298,18 +298,18 @@
 00001290: 6c75 652e 2049 6620 7468 6520 7661 6c75  lue. If the valu
 000012a0: 6520 6973 204e 6f6e 6520 6f72 2065 6d70  e is None or emp
 000012b0: 7479 2c20 616c 6c20 6375 7272 656e 7420  ty, all current 
 000012c0: 7661 6c75 6573 2061 7265 2072 656d 6f76  values are remov
 000012d0: 6564 2e0a 0a20 2020 2020 2020 2052 6574  ed...        Ret
 000012e0: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 000012f0: 2020 5468 6520 7061 7373 6564 2074 6173    The passed tas
-00001300: 6b2e 0a20 2020 2020 2020 2029 0272 0e00  k..        ).r..
+00001300: 6b2e 0a20 2020 2020 2020 2029 0272 1a00  k..        ).r..
 00001310: 0000 721f 0000 00a9 0272 2100 0000 7226  ..r......r!...r&
 00001320: 0000 0072 2300 0000 7223 0000 0072 2400  ...r#...r#...r$.
-00001330: 0000 720e 0000 009e 0000 0073 0400 0000  ..r........s....
+00001330: 0000 721a 0000 009b 0000 0073 0400 0000  ..r........s....
 00001340: 000e 0e02 7a35 5361 7665 5072 6f63 6573  ....z5SaveProces
 00001350: 7345 6c65 6d65 6e74 5265 7175 6573 7455  sElementRequestU
 00001360: 7469 6c73 2e73 6574 5f65 6c65 6d65 6e74  tils.set_element
 00001370: 5f76 616c 7565 5f6c 6973 7463 0200 0000  _value_listc....
 00001380: 0000 0000 0000 0000 0200 0000 0300 0000  ................
 00001390: 4300 0000 7312 0000 0074 0074 017c 0083  C...s....t.t.|..
 000013a0: 017c 0183 0201 007c 0053 0029 0161 0001  .|.....|.S.).a..
@@ -325,17 +325,17 @@
 00001440: 6c75 652e 2049 6620 7468 6520 7661 6c75  lue. If the valu
 00001450: 6520 6973 204e 6f6e 652c 2061 6c6c 2063  e is None, all c
 00001460: 7572 7265 6e74 2076 616c 7565 7320 6172  urrent values ar
 00001470: 6520 7265 6d6f 7665 642e 0a0a 2020 2020  e removed...    
 00001480: 2020 2020 5265 7475 726e 733a 0a20 2020      Returns:.   
 00001490: 2020 2020 2020 2020 2054 6865 2070 6173           The pas
 000014a0: 7365 6420 7461 736b 2e0a 2020 2020 2020  sed task..      
-000014b0: 2020 2902 720f 0000 0072 1f00 0000 7233    ).r....r....r3
+000014b0: 2020 2902 7209 0000 0072 1f00 0000 7233    ).r....r....r3
 000014c0: 0000 0072 2300 0000 7223 0000 0072 2400  ...r#...r#...r$.
-000014d0: 0000 720f 0000 00b0 0000 0073 0400 0000  ..r........s....
+000014d0: 0000 7209 0000 00ad 0000 0073 0400 0000  ..r........s....
 000014e0: 000e 0e02 7a30 5361 7665 5072 6f63 6573  ....z0SaveProces
 000014f0: 7345 6c65 6d65 6e74 5265 7175 6573 7455  sElementRequestU
 00001500: 7469 6c73 2e61 6464 5f65 6c65 6d65 6e74  tils.add_element
 00001510: 5f76 616c 7565 6302 0000 0000 0000 0000  _valuec.........
 00001520: 0000 0002 0000 0003 0000 0043 0000 0073  ...........C...s
 00001530: 1200 0000 7400 7401 7c00 8301 7c01 8302  ....t.t.|...|...
 00001540: 0100 7c00 5300 2901 611a 0100 000a 2020  ..|.S.).a.....  
@@ -352,17 +352,17 @@
 000015f0: 204e 6f6e 6520 6f72 2065 6d70 7479 2c20   None or empty, 
 00001600: 616c 6c20 6375 7272 656e 7420 7661 6c75  all current valu
 00001610: 6573 2061 7265 2072 656d 6f76 6564 2e0a  es are removed..
 00001620: 0a20 2020 2020 2020 2052 6574 7572 6e73  .        Returns
 00001630: 3a0a 2020 2020 2020 2020 2020 2020 5468  :.            Th
 00001640: 6520 7061 7373 6564 206d 6f64 656c 2072  e passed model r
 00001650: 656c 6174 6564 206f 626a 6563 742e 0a20  elated object.. 
-00001660: 2020 2020 2020 2029 0272 1000 0000 721f         ).r....r.
+00001660: 2020 2020 2020 2029 0272 0a00 0000 721f         ).r....r.
 00001670: 0000 0072 3400 0000 7223 0000 0072 2300  ...r4...r#...r#.
-00001680: 0000 7224 0000 0072 1000 0000 c200 0000  ..r$...r........
+00001680: 0000 7224 0000 0072 0a00 0000 bf00 0000  ..r$...r........
 00001690: 7304 0000 0000 0e0e 027a 3553 6176 6550  s........z5SaveP
 000016a0: 726f 6365 7373 456c 656d 656e 7452 6571  rocessElementReq
 000016b0: 7565 7374 5574 696c 732e 6164 645f 656c  uestUtils.add_el
 000016c0: 656d 656e 745f 7661 6c75 655f 6c69 7374  ement_value_list
 000016d0: 6301 0000 0000 0000 0000 0000 0001 0000  c...............
 000016e0: 0003 0000 0043 0000 0073 0c00 0000 7400  .....C...s....t.
 000016f0: 7401 7c00 8301 8301 5300 2901 7aaa 0a20  t.|.....S.).z.. 
@@ -372,17 +372,17 @@
 00001730: 7473 3a0a 2020 2020 2020 2020 2020 2020  ts:.            
 00001740: 7265 7175 6573 743a 2054 6865 2053 6176  request: The Sav
 00001750: 6554 6173 6b45 6c65 6d65 6e74 2072 6571  eTaskElement req
 00001760: 7565 7374 2e0a 0a20 2020 2020 2020 2052  uest...        R
 00001770: 6574 7572 6e73 3a0a 2020 2020 2020 2020  eturns:.        
 00001780: 2020 2020 5468 6520 656c 656d 656e 7420      The element 
 00001790: 7661 6c75 6520 6173 2061 2073 7472 2e0a  value as a str..
-000017a0: 2020 2020 2020 2020 2902 7211 0000 0072          ).r....r
+000017a0: 2020 2020 2020 2020 2902 7215 0000 0072          ).r....r
 000017b0: 1f00 0000 7220 0000 0072 2300 0000 7223  ....r ...r#...r#
-000017c0: 0000 0072 2400 0000 7211 0000 00d4 0000  ...r$...r.......
+000017c0: 0000 0072 2400 0000 7215 0000 00d1 0000  ...r$...r.......
 000017d0: 0073 0200 0000 000b 7a37 5361 7665 5072  .s......z7SavePr
 000017e0: 6f63 6573 7345 6c65 6d65 6e74 5265 7175  ocessElementRequ
 000017f0: 6573 7455 7469 6c73 2e67 6574 5f65 6c65  estUtils.get_ele
 00001800: 6d65 6e74 5f76 616c 7565 5f61 735f 7374  ment_value_as_st
 00001810: 7263 0100 0000 0000 0000 0000 0000 0100  rc..............
 00001820: 0000 0300 0000 4300 0000 730c 0000 0074  ......C...s....t
 00001830: 0074 017c 0083 0183 0153 0029 017a b10a  .t.|.....S.).z..
@@ -393,17 +393,17 @@
 00001880: 2020 2020 2020 2020 7265 7175 6573 743a          request:
 00001890: 2054 6865 2053 6176 6554 6173 6b45 6c65   The SaveTaskEle
 000018a0: 6d65 6e74 2072 6571 7565 7374 2e0a 0a20  ment request... 
 000018b0: 2020 2020 2020 2052 6574 7572 6e73 3a0a         Returns:.
 000018c0: 2020 2020 2020 2020 2020 2020 5468 6520              The 
 000018d0: 656c 656d 656e 7420 7661 6c75 6520 6173  element value as
 000018e0: 2061 2073 7472 2e0a 2020 2020 2020 2020   a str..        
-000018f0: 2902 7212 0000 0072 1f00 0000 7220 0000  ).r....r....r ..
+000018f0: 2902 720e 0000 0072 1f00 0000 7220 0000  ).r....r....r ..
 00001900: 0072 2300 0000 7223 0000 0072 2400 0000  .r#...r#...r$...
-00001910: 7212 0000 00e1 0000 0073 0200 0000 000b  r........s......
+00001910: 720e 0000 00de 0000 0073 0200 0000 000b  r........s......
 00001920: 7a38 5361 7665 5072 6f63 6573 7345 6c65  z8SaveProcessEle
 00001930: 6d65 6e74 5265 7175 6573 7455 7469 6c73  mentRequestUtils
 00001940: 2e66 696e 645f 656c 656d 656e 745f 7661  .find_element_va
 00001950: 6c75 655f 6173 5f73 7472 6301 0000 0000  lue_as_strc.....
 00001960: 0000 0000 0000 0001 0000 0003 0000 0043  ...............C
 00001970: 0000 0073 0c00 0000 7400 7401 7c00 8301  ...s....t.t.|...
 00001980: 8301 5300 2901 7abc 0a20 2020 2020 2020  ..S.).z..       
@@ -414,17 +414,17 @@
 000019d0: 2020 2020 2020 7265 7175 6573 743a 2054        request: T
 000019e0: 6865 2053 6176 6554 6173 6b45 6c65 6d65  he SaveTaskEleme
 000019f0: 6e74 2072 6571 7565 7374 2e0a 0a20 2020  nt request...   
 00001a00: 2020 2020 2052 6574 7572 6e73 3a0a 2020       Returns:.  
 00001a10: 2020 2020 2020 2020 2020 5468 6520 656c            The el
 00001a20: 656d 656e 7420 7661 6c75 6573 2061 7320  ement values as 
 00001a30: 6120 7374 7220 6c69 7374 2e0a 2020 2020  a str list..    
-00001a40: 2020 2020 2902 7213 0000 0072 1f00 0000      ).r....r....
+00001a40: 2020 2020 2902 7216 0000 0072 1f00 0000      ).r....r....
 00001a50: 7220 0000 0072 2300 0000 7223 0000 0072  r ...r#...r#...r
-00001a60: 2400 0000 7213 0000 00ee 0000 0073 0200  $...r........s..
+00001a60: 2400 0000 7216 0000 00eb 0000 0073 0200  $...r........s..
 00001a70: 0000 000b 7a3c 5361 7665 5072 6f63 6573  ....z<SaveProces
 00001a80: 7345 6c65 6d65 6e74 5265 7175 6573 7455  sElementRequestU
 00001a90: 7469 6c73 2e67 6574 5f65 6c65 6d65 6e74  tils.get_element
 00001aa0: 5f76 616c 7565 5f61 735f 7374 725f 6c69  _value_as_str_li
 00001ab0: 7374 6301 0000 0000 0000 0000 0000 0001  stc.............
 00001ac0: 0000 0003 0000 0043 0000 0073 0c00 0000  .......C...s....
 00001ad0: 7400 7401 7c00 8301 8301 5300 2901 7aae  t.t.|.....S.).z.
@@ -435,17 +435,17 @@
 00001b20: 2020 2020 7265 7175 6573 743a 2054 6865      request: The
 00001b30: 2053 6176 6554 6173 6b45 6c65 6d65 6e74   SaveTaskElement
 00001b40: 2072 6571 7565 7374 2e0a 0a20 2020 2020   request...     
 00001b50: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00001b60: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 00001b70: 656e 7420 7661 6c75 6520 6173 2061 2066  ent value as a f
 00001b80: 6c6f 6174 2e0a 2020 2020 2020 2020 2902  loat..        ).
-00001b90: 7214 0000 0072 1f00 0000 7220 0000 0072  r....r....r ...r
-00001ba0: 2300 0000 7223 0000 0072 2400 0000 7214  #...r#...r$...r.
-00001bb0: 0000 00fb 0000 0073 0200 0000 000b 7a39  .......s......z9
+00001b90: 7213 0000 0072 1f00 0000 7220 0000 0072  r....r....r ...r
+00001ba0: 2300 0000 7223 0000 0072 2400 0000 7213  #...r#...r$...r.
+00001bb0: 0000 00f8 0000 0073 0200 0000 000b 7a39  .......s......z9
 00001bc0: 5361 7665 5072 6f63 6573 7345 6c65 6d65  SaveProcessEleme
 00001bd0: 6e74 5265 7175 6573 7455 7469 6c73 2e67  ntRequestUtils.g
 00001be0: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
 00001bf0: 5f61 735f 666c 6f61 7463 0100 0000 0000  _as_floatc......
 00001c00: 0000 0000 0000 0100 0000 0300 0000 4300  ..............C.
 00001c10: 0000 730c 0000 0074 0074 017c 0083 0183  ..s....t.t.|....
 00001c20: 0153 0029 017a b50a 2020 2020 2020 2020  .S.).z..        
@@ -455,18 +455,18 @@
 00001c60: 656e 7473 3a0a 2020 2020 2020 2020 2020  ents:.          
 00001c70: 2020 7265 7175 6573 743a 2054 6865 2053    request: The S
 00001c80: 6176 6554 6173 6b45 6c65 6d65 6e74 2072  aveTaskElement r
 00001c90: 6571 7565 7374 2e0a 0a20 2020 2020 2020  equest...       
 00001ca0: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00001cb0: 2020 2020 2020 5468 6520 656c 656d 656e        The elemen
 00001cc0: 7420 7661 6c75 6520 6173 2061 2066 6c6f  t value as a flo
-00001cd0: 6174 2e0a 2020 2020 2020 2020 2902 7215  at..        ).r.
+00001cd0: 6174 2e0a 2020 2020 2020 2020 2902 720d  at..        ).r.
 00001ce0: 0000 0072 1f00 0000 7220 0000 0072 2300  ...r....r ...r#.
-00001cf0: 0000 7223 0000 0072 2400 0000 7215 0000  ..r#...r$...r...
-00001d00: 0008 0100 0073 0200 0000 000b 7a3a 5361  .....s......z:Sa
+00001cf0: 0000 7223 0000 0072 2400 0000 720d 0000  ..r#...r$...r...
+00001d00: 0005 0100 0073 0200 0000 000b 7a3a 5361  .....s......z:Sa
 00001d10: 7665 5072 6f63 6573 7345 6c65 6d65 6e74  veProcessElement
 00001d20: 5265 7175 6573 7455 7469 6c73 2e66 696e  RequestUtils.fin
 00001d30: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
 00001d40: 6173 5f66 6c6f 6174 6301 0000 0000 0000  as_floatc.......
 00001d50: 0000 0000 0001 0000 0003 0000 0043 0000  .............C..
 00001d60: 0073 0c00 0000 7400 7401 7c00 8301 8301  .s....t.t.|.....
 00001d70: 5300 2901 7ab5 0a20 2020 2020 2020 2047  S.).z..        G
@@ -476,18 +476,18 @@
 00001db0: 6e74 733a 0a20 2020 2020 2020 2020 2020  nts:.           
 00001dc0: 2072 6571 7565 7374 3a20 5468 6520 5361   request: The Sa
 00001dd0: 7665 5461 736b 456c 656d 656e 7420 7265  veTaskElement re
 00001de0: 7175 6573 742e 0a0a 2020 2020 2020 2020  quest...        
 00001df0: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 00001e00: 2020 2020 2054 6865 2065 6c65 6d65 6e74       The element
 00001e10: 2076 616c 7565 2061 7320 6120 666c 6f61   value as a floa
-00001e20: 742e 0a20 2020 2020 2020 2029 0272 1600  t..        ).r..
+00001e20: 742e 0a20 2020 2020 2020 2029 0272 1400  t..        ).r..
 00001e30: 0000 721f 0000 0072 2000 0000 7223 0000  ..r....r ...r#..
-00001e40: 0072 2300 0000 7224 0000 0072 1600 0000  .r#...r$...r....
-00001e50: 1501 0000 7302 0000 0000 0b7a 3e53 6176  ....s......z>Sav
+00001e40: 0072 2300 0000 7224 0000 0072 1400 0000  .r#...r$...r....
+00001e50: 1201 0000 7302 0000 0000 0b7a 3e53 6176  ....s......z>Sav
 00001e60: 6550 726f 6365 7373 456c 656d 656e 7452  eProcessElementR
 00001e70: 6571 7565 7374 5574 696c 732e 6765 745f  equestUtils.get_
 00001e80: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
 00001e90: 5f66 6c6f 6174 5f6c 6973 7463 0100 0000  _float_listc....
 00001ea0: 0000 0000 0000 0000 0100 0000 0300 0000  ................
 00001eb0: 4300 0000 730c 0000 0074 0074 017c 0083  C...s....t.t.|..
 00001ec0: 0183 0153 0029 017a ac0a 2020 2020 2020  ...S.).z..      
@@ -497,17 +497,17 @@
 00001f00: 2020 2020 2020 2020 2020 2020 7265 7175              requ
 00001f10: 6573 743a 2054 6865 2053 6176 6554 6173  est: The SaveTas
 00001f20: 6b45 6c65 6d65 6e74 2072 6571 7565 7374  kElement request
 00001f30: 2e0a 0a20 2020 2020 2020 2052 6574 7572  ...        Retur
 00001f40: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 00001f50: 5468 6520 656c 656d 656e 7420 7661 6c75  The element valu
 00001f60: 6520 6173 2061 2064 6174 652e 0a20 2020  e as a date..   
-00001f70: 2020 2020 2029 0272 1700 0000 721f 0000       ).r....r...
+00001f70: 2020 2020 2029 0272 0f00 0000 721f 0000       ).r....r...
 00001f80: 0072 2000 0000 7223 0000 0072 2300 0000  .r ...r#...r#...
-00001f90: 7224 0000 0072 1700 0000 2201 0000 7302  r$...r...."...s.
+00001f90: 7224 0000 0072 0f00 0000 1f01 0000 7302  r$...r........s.
 00001fa0: 0000 0000 0b7a 3853 6176 6550 726f 6365  .....z8SaveProce
 00001fb0: 7373 456c 656d 656e 7452 6571 7565 7374  ssElementRequest
 00001fc0: 5574 696c 732e 6765 745f 656c 656d 656e  Utils.get_elemen
 00001fd0: 745f 7661 6c75 655f 6173 5f64 6174 6563  t_value_as_datec
 00001fe0: 0100 0000 0000 0000 0000 0000 0100 0000  ................
 00001ff0: 0300 0000 4300 0000 730c 0000 0074 0074  ....C...s....t.t
 00002000: 017c 0083 0183 0153 0029 017a b40a 2020  .|.....S.).z..  
@@ -518,17 +518,17 @@
 00002050: 2020 2020 2020 2020 7265 7175 6573 743a          request:
 00002060: 2054 6865 2053 6176 6554 6173 6b45 6c65   The SaveTaskEle
 00002070: 6d65 6e74 2072 6571 7565 7374 2e0a 0a20  ment request... 
 00002080: 2020 2020 2020 2052 6574 7572 6e73 3a0a         Returns:.
 00002090: 2020 2020 2020 2020 2020 2020 5468 6520              The 
 000020a0: 656c 656d 656e 7420 7661 6c75 6520 6173  element value as
 000020b0: 2061 2064 6174 652e 0a20 2020 2020 2020   a date..       
-000020c0: 2029 0272 1800 0000 721f 0000 0072 2000   ).r....r....r .
+000020c0: 2029 0272 0b00 0000 721f 0000 0072 2000   ).r....r....r .
 000020d0: 0000 7223 0000 0072 2300 0000 7224 0000  ..r#...r#...r$..
-000020e0: 0072 1800 0000 2f01 0000 7302 0000 0000  .r..../...s.....
+000020e0: 0072 0b00 0000 2c01 0000 7302 0000 0000  .r....,...s.....
 000020f0: 0b7a 3953 6176 6550 726f 6365 7373 456c  .z9SaveProcessEl
 00002100: 656d 656e 7452 6571 7565 7374 5574 696c  ementRequestUtil
 00002110: 732e 6669 6e64 5f65 6c65 6d65 6e74 5f76  s.find_element_v
 00002120: 616c 7565 5f61 735f 6461 7465 6301 0000  alue_as_datec...
 00002130: 0000 0000 0000 0000 0001 0000 0003 0000  ................
 00002140: 0043 0000 0073 0c00 0000 7400 7401 7c00  .C...s....t.t.|.
 00002150: 8301 8301 5300 2901 7ab5 0a20 2020 2020  ....S.).z..     
@@ -539,17 +539,17 @@
 000021a0: 2020 7265 7175 6573 743a 2054 6865 2053    request: The S
 000021b0: 6176 6554 6173 6b45 6c65 6d65 6e74 2072  aveTaskElement r
 000021c0: 6571 7565 7374 2e0a 0a20 2020 2020 2020  equest...       
 000021d0: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 000021e0: 2020 2020 2020 5468 6520 656c 656d 656e        The elemen
 000021f0: 7420 7661 6c75 6573 2061 7320 6461 7465  t values as date
 00002200: 206c 6973 742e 0a20 2020 2020 2020 2029   list..        )
-00002210: 0272 1900 0000 721f 0000 0072 2000 0000  .r....r....r ...
+00002210: 0272 1000 0000 721f 0000 0072 2000 0000  .r....r....r ...
 00002220: 7223 0000 0072 2300 0000 7224 0000 0072  r#...r#...r$...r
-00002230: 1900 0000 3c01 0000 7302 0000 0000 0b7a  ....<...s......z
+00002230: 1000 0000 3901 0000 7302 0000 0000 0b7a  ....9...s......z
 00002240: 3d53 6176 6550 726f 6365 7373 456c 656d  =SaveProcessElem
 00002250: 656e 7452 6571 7565 7374 5574 696c 732e  entRequestUtils.
 00002260: 6765 745f 656c 656d 656e 745f 7661 6c75  get_element_valu
 00002270: 655f 6173 5f64 6174 655f 6c69 7374 6301  e_as_date_listc.
 00002280: 0000 0000 0000 0000 0000 0001 0000 0003  ................
 00002290: 0000 0043 0000 0073 0c00 0000 7400 7401  ...C...s....t.t.
 000022a0: 7c00 8301 8301 5300 2901 7aac 0a20 2020  |.....S.).z..   
@@ -559,17 +559,17 @@
 000022e0: 733a 0a20 2020 2020 2020 2020 2020 2072  s:.            r
 000022f0: 6571 7565 7374 3a20 5468 6520 5361 7665  equest: The Save
 00002300: 5461 736b 456c 656d 656e 7420 7265 7175  TaskElement requ
 00002310: 6573 742e 0a0a 2020 2020 2020 2020 5265  est...        Re
 00002320: 7475 726e 733a 0a20 2020 2020 2020 2020  turns:.         
 00002330: 2020 2054 6865 2065 6c65 6d65 6e74 2076     The element v
 00002340: 616c 7565 2061 7320 6120 6469 6374 2e0a  alue as a dict..
-00002350: 2020 2020 2020 2020 2902 721a 0000 0072          ).r....r
+00002350: 2020 2020 2020 2020 2902 7211 0000 0072          ).r....r
 00002360: 1f00 0000 7220 0000 0072 2300 0000 7223  ....r ...r#...r#
-00002370: 0000 0072 2400 0000 721a 0000 0049 0100  ...r$...r....I..
+00002370: 0000 0072 2400 0000 7211 0000 0046 0100  ...r$...r....F..
 00002380: 0073 0200 0000 000b 7a38 5361 7665 5072  .s......z8SavePr
 00002390: 6f63 6573 7345 6c65 6d65 6e74 5265 7175  ocessElementRequ
 000023a0: 6573 7455 7469 6c73 2e67 6574 5f65 6c65  estUtils.get_ele
 000023b0: 6d65 6e74 5f76 616c 7565 5f61 735f 6469  ment_value_as_di
 000023c0: 6374 6301 0000 0000 0000 0000 0000 0001  ctc.............
 000023d0: 0000 0003 0000 0043 0000 0073 0c00 0000  .......C...s....
 000023e0: 7400 7401 7c00 8301 8301 5300 2901 7ab3  t.t.|.....S.).z.
@@ -580,17 +580,17 @@
 00002430: 2020 2020 2020 2020 2020 7265 7175 6573            reques
 00002440: 743a 2054 6865 2053 6176 6554 6173 6b45  t: The SaveTaskE
 00002450: 6c65 6d65 6e74 2072 6571 7565 7374 2e0a  lement request..
 00002460: 0a20 2020 2020 2020 2052 6574 7572 6e73  .        Returns
 00002470: 3a0a 2020 2020 2020 2020 2020 2020 5468  :.            Th
 00002480: 6520 656c 656d 656e 7420 7661 6c75 6520  e element value 
 00002490: 6173 2061 2064 6963 742e 0a20 2020 2020  as a dict..     
-000024a0: 2020 2029 0272 1b00 0000 721f 0000 0072     ).r....r....r
+000024a0: 2020 2029 0272 0c00 0000 721f 0000 0072     ).r....r....r
 000024b0: 2000 0000 7223 0000 0072 2300 0000 7224   ...r#...r#...r$
-000024c0: 0000 0072 1b00 0000 5601 0000 7302 0000  ...r....V...s...
+000024c0: 0000 0072 0c00 0000 5301 0000 7302 0000  ...r....S...s...
 000024d0: 0000 0b7a 3953 6176 6550 726f 6365 7373  ...z9SaveProcess
 000024e0: 456c 656d 656e 7452 6571 7565 7374 5574  ElementRequestUt
 000024f0: 696c 732e 6669 6e64 5f65 6c65 6d65 6e74  ils.find_element
 00002500: 5f76 616c 7565 5f61 735f 6469 6374 6301  _value_as_dictc.
 00002510: 0000 0000 0000 0000 0000 0001 0000 0003  ................
 00002520: 0000 0043 0000 0073 0c00 0000 7400 7401  ...C...s....t.t.
 00002530: 7c00 8301 8301 5300 2901 7ab5 0a20 2020  |.....S.).z..   
@@ -601,46 +601,46 @@
 00002580: 2020 2020 7265 7175 6573 743a 2054 6865      request: The
 00002590: 2053 6176 6554 6173 6b45 6c65 6d65 6e74   SaveTaskElement
 000025a0: 2072 6571 7565 7374 2e0a 0a20 2020 2020   request...     
 000025b0: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 000025c0: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 000025d0: 656e 7420 7661 6c75 6573 2061 7320 6469  ent values as di
 000025e0: 6374 206c 6973 742e 0a20 2020 2020 2020  ct list..       
-000025f0: 2029 0272 1c00 0000 721f 0000 0072 2000   ).r....r....r .
+000025f0: 2029 0272 1200 0000 721f 0000 0072 2000   ).r....r....r .
 00002600: 0000 7223 0000 0072 2300 0000 7224 0000  ..r#...r#...r$..
-00002610: 0072 1c00 0000 6301 0000 7302 0000 0000  .r....c...s.....
+00002610: 0072 1200 0000 6001 0000 7302 0000 0000  .r....`...s.....
 00002620: 0b7a 3d53 6176 6550 726f 6365 7373 456c  .z=SaveProcessEl
 00002630: 656d 656e 7452 6571 7565 7374 5574 696c  ementRequestUtil
 00002640: 732e 6765 745f 656c 656d 656e 745f 7661  s.get_element_va
 00002650: 6c75 655f 6173 5f64 6963 745f 6c69 7374  lue_as_dict_list
 00002660: 2901 4e29 014e 2901 4e29 014e 2922 722c  ).N).N).N).N)"r,
 00002670: 0000 0072 2d00 0000 722e 0000 00da 0c73  ...r-...r......s
 00002680: 7461 7469 636d 6574 686f 6472 1e00 0000  taticmethodr....
-00002690: da04 626f 6f6c 7209 0000 00da 0369 6e74  ..boolr......int
-000026a0: 720a 0000 0072 0300 0000 720b 0000 0072  r....r....r....r
-000026b0: 0c00 0000 7208 0000 0072 0d00 0000 7202  ....r....r....r.
-000026c0: 0000 0072 0e00 0000 720f 0000 0072 1000  ...r....r....r..
-000026d0: 0000 da03 7374 7272 1100 0000 7212 0000  ....strr....r...
-000026e0: 0072 1300 0000 da05 666c 6f61 7472 1400  .r......floatr..
-000026f0: 0000 7215 0000 0072 1600 0000 7204 0000  ..r....r....r...
-00002700: 0072 1700 0000 7218 0000 0072 1900 0000  .r....r....r....
-00002710: da04 6469 6374 721a 0000 0072 1b00 0000  ..dictr....r....
-00002720: 721c 0000 0072 2300 0000 7223 0000 0072  r....r#...r#...r
-00002730: 2300 0000 7224 0000 0072 2f00 0000 4d00  #...r$...r/...M.
+00002690: da04 626f 6f6c 7217 0000 00da 0369 6e74  ..boolr......int
+000026a0: 7218 0000 0072 0400 0000 721b 0000 0072  r....r....r....r
+000026b0: 1c00 0000 7206 0000 0072 1900 0000 7203  ....r....r....r.
+000026c0: 0000 0072 1a00 0000 7209 0000 0072 0a00  ...r....r....r..
+000026d0: 0000 da03 7374 7272 1500 0000 720e 0000  ....strr....r...
+000026e0: 0072 1600 0000 da05 666c 6f61 7472 1300  .r......floatr..
+000026f0: 0000 720d 0000 0072 1400 0000 7202 0000  ..r....r....r...
+00002700: 0072 0f00 0000 720b 0000 0072 1000 0000  .r....r....r....
+00002710: da04 6469 6374 7211 0000 0072 0c00 0000  ..dictr....r....
+00002720: 7212 0000 0072 2300 0000 7223 0000 0072  r....r#...r#...r
+00002730: 2300 0000 7224 0000 0072 2f00 0000 4a00  #...r$...r/...J.
 00002740: 0000 7380 0000 0008 0102 0112 0c02 0114  ..s.............
 00002750: 0d02 0118 0f02 0202 0006 0002 0102 fe0e  ................
 00002760: 1202 0200 ff02 0102 0006 0102 fe0e 1102  ................
 00002770: 0200 ff02 0102 000a 0102 fe0e 1102 0200  ................
 00002780: ff02 0102 0006 0102 fe0e 1102 0200 ff02  ................
 00002790: 0102 000a 0102 fe0e 1102 0112 0c02 0116  ................
 000027a0: 0c02 0116 0c02 0112 0c02 0112 0c02 0116  ................
 000027b0: 0c02 0112 0c02 0116 0c02 0116 0c02 0112  ................
 000027c0: 0c02 0116 0c02 0172 2f00 0000 4e29 24da  .......r/...N)$.
-000027d0: 0674 7970 696e 6772 0200 0000 7203 0000  .typingr....r...
-000027e0: 00da 0864 6174 6574 696d 6572 0400 0000  ...datetimer....
+000027d0: 0864 6174 6574 696d 6572 0200 0000 da06  .datetimer......
+000027e0: 7479 7069 6e67 7203 0000 0072 0400 0000  typingr....r....
 000027f0: da12 6b75 666c 6f77 5f72 6573 742e 6d6f  ..kuflow_rest.mo
 00002800: 6465 6c73 7205 0000 005a 116b 7566 6c6f  delsr....Z.kuflo
 00002810: 775f 7265 7374 2e75 7469 6c73 7206 0000  w_rest.utilsr...
 00002820: 0072 0700 0000 7208 0000 005a 206b 7566  .r....r....Z kuf
 00002830: 6c6f 775f 7265 7374 2e75 7469 6c73 2e65  low_rest.utils.e
 00002840: 6c65 6d65 6e74 5f76 616c 7565 7372 0900  lement_valuesr..
 00002850: 0000 720a 0000 0072 0b00 0000 720c 0000  ..r....r....r...
@@ -648,9 +648,9 @@
 00002870: 7210 0000 0072 1100 0000 7212 0000 0072  r....r....r....r
 00002880: 1300 0000 7214 0000 0072 1500 0000 7216  ....r....r....r.
 00002890: 0000 0072 1700 0000 7218 0000 0072 1900  ...r....r....r..
 000028a0: 0000 721a 0000 0072 1b00 0000 721c 0000  ..r....r....r...
 000028b0: 00da 066d 6f64 656c 7372 1e00 0000 721f  ...modelsr....r.
 000028c0: 0000 0072 2f00 0000 7223 0000 0072 2300  ...r/...r#...r#.
 000028d0: 0000 7223 0000 0072 2400 0000 da08 3c6d  ..r#...r$.....<m
-000028e0: 6f64 756c 653e 1a00 0000 730e 0000 0010  odule>....s.....
-000028f0: 010c 020c 0114 0558 160c 0310 11         .......X.....
+000028e0: 6f64 756c 653e 1a00 0000 730e 0000 000c  odule>....s.....
+000028f0: 0110 020c 0114 0158 170c 0310 11         .......X.....
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/__pycache__/_save_task_element_utils.cpython-38.pyc` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/__pycache__/_save_task_element_utils.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 14103 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 2% similar despite different names*

```diff
@@ -1,82 +1,82 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 1737 0000  U.......=S.d.7..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 f636 0000  U..........d.6..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 e200 0000 6400  .....@...s....d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 0100 6400  d.l.m.Z.m.Z...d.
-00000040: 6402 6c03 6d04 5a04 0100 6400 6403 6c05  d.l.m.Z...d.d.l.
+00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
+00000040: 6d03 5a03 6d04 5a04 0100 6400 6403 6c05  m.Z.m.Z...d.d.l.
 00000050: 6d06 5a06 6d07 5a07 6d08 5a08 0100 6400  m.Z.m.Z.m.Z...d.
 00000060: 6404 6c09 6d0a 5a0a 6d0b 5a0b 6d0c 5a0c  d.l.m.Z.m.Z.m.Z.
 00000070: 0100 6400 6405 6c0d 6d0e 5a0e 6d0f 5a0f  ..d.d.l.m.Z.m.Z.
 00000080: 6d10 5a10 6d11 5a11 6d12 5a12 6d13 5a13  m.Z.m.Z.m.Z.m.Z.
 00000090: 6d14 5a14 6d15 5a15 6d16 5a16 6d17 5a17  m.Z.m.Z.m.Z.m.Z.
 000000a0: 6d18 5a18 6d19 5a19 6d1a 5a1a 6d1b 5a1b  m.Z.m.Z.m.Z.m.Z.
 000000b0: 6d1c 5a1c 6d1d 5a1d 6d1e 5a1e 6d1f 5a1f  m.Z.m.Z.m.Z.m.Z.
 000000c0: 6d20 5a20 6d21 5a21 6d22 5a22 6d23 5a23  m Z m!Z!m"Z"m#Z#
 000000d0: 6d24 5a24 6d25 5a25 6d26 5a26 6d27 5a27  m$Z$m%Z%m&Z&m'Z'
 000000e0: 0100 6406 6407 6c28 6d29 5a29 0100 4700  ..d.d.l(m)Z)..G.
-000000f0: 6408 6409 8400 6409 650a 8303 5a2a 4700  d.d...d.e...Z*G.
+000000f0: 6408 6409 8400 6409 650c 8303 5a2a 4700  d.d...d.e...Z*G.
 00000100: 640a 640b 8400 640b 8302 5a2b 640c 5300  d.d...d...Z+d.S.
-00000110: 290d e900 0000 0029 02da 044c 6973 74da  )......)...List.
-00000120: 084f 7074 696f 6e61 6c29 01da 0464 6174  .Optional)...dat
-00000130: 6529 03da 1054 6173 6b45 6c65 6d65 6e74  e)...TaskElement
+00000110: 290d e900 0000 0029 01da 0464 6174 6529  )......)...date)
+00000120: 02da 044c 6973 74da 084f 7074 696f 6e61  ...List..Optiona
+00000130: 6c29 03da 1054 6173 6b45 6c65 6d65 6e74  l)...TaskElement
 00000140: 5661 6c75 65da 1c54 6173 6b45 6c65 6d65  Value..TaskEleme
 00000150: 6e74 5661 6c75 6544 6f63 756d 656e 7449  ntValueDocumentI
 00000160: 7465 6dda 1d54 6173 6b45 6c65 6d65 6e74  tem..TaskElement
 00000170: 5661 6c75 6550 7269 6e63 6970 616c 4974  ValuePrincipalIt
-00000180: 656d 2903 da18 5461 736b 456c 656d 656e  em)...TaskElemen
-00000190: 7456 616c 7565 4163 6365 7373 6f72 da11  tValueAccessor..
-000001a0: 456c 656d 656e 7456 616c 7565 556e 696f  ElementValueUnio
-000001b0: 6eda 1645 6c65 6d65 6e74 5661 6c75 6553  n..ElementValueS
-000001c0: 696d 706c 6554 7970 6529 1ada 1767 6574  impleType)...get
-000001d0: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
-000001e0: 616c 6964 da1a 6765 745f 656c 656d 656e  alid..get_elemen
-000001f0: 745f 7661 6c75 655f 7661 6c69 645f 6174  t_value_valid_at
-00000200: da17 7365 745f 656c 656d 656e 745f 7661  ..set_element_va
-00000210: 6c75 655f 7661 6c69 64da 1a73 6574 5f65  lue_valid..set_e
-00000220: 6c65 6d65 6e74 5f76 616c 7565 5f76 616c  lement_value_val
-00000230: 6964 5f61 74da 1173 6574 5f65 6c65 6d65  id_at..set_eleme
-00000240: 6e74 5f76 616c 7565 da16 7365 745f 656c  nt_value..set_el
-00000250: 656d 656e 745f 7661 6c75 655f 6c69 7374  ement_value_list
-00000260: da11 6164 645f 656c 656d 656e 745f 7661  ..add_element_va
-00000270: 6c75 65da 1661 6464 5f65 6c65 6d65 6e74  lue..add_element
-00000280: 5f76 616c 7565 5f6c 6973 74da 1867 6574  _value_list..get
-00000290: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
-000002a0: 735f 7374 72da 1966 696e 645f 656c 656d  s_str..find_elem
-000002b0: 656e 745f 7661 6c75 655f 6173 5f73 7472  ent_value_as_str
-000002c0: da1d 6765 745f 656c 656d 656e 745f 7661  ..get_element_va
-000002d0: 6c75 655f 6173 5f73 7472 5f6c 6973 74da  lue_as_str_list.
-000002e0: 1a67 6574 5f65 6c65 6d65 6e74 5f76 616c  .get_element_val
-000002f0: 7565 5f61 735f 666c 6f61 74da 1b66 696e  ue_as_float..fin
-00000300: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
-00000310: 6173 5f66 6c6f 6174 da1f 6765 745f 656c  as_float..get_el
-00000320: 656d 656e 745f 7661 6c75 655f 6173 5f66  ement_value_as_f
-00000330: 6c6f 6174 5f6c 6973 74da 1967 6574 5f65  loat_list..get_e
-00000340: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
-00000350: 6461 7465 da1a 6669 6e64 5f65 6c65 6d65  date..find_eleme
-00000360: 6e74 5f76 616c 7565 5f61 735f 6461 7465  nt_value_as_date
-00000370: da1e 6765 745f 656c 656d 656e 745f 7661  ..get_element_va
-00000380: 6c75 655f 6173 5f64 6174 655f 6c69 7374  lue_as_date_list
-00000390: da19 6765 745f 656c 656d 656e 745f 7661  ..get_element_va
-000003a0: 6c75 655f 6173 5f64 6963 74da 1a66 696e  lue_as_dict..fin
-000003b0: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
-000003c0: 6173 5f64 6963 74da 1e67 6574 5f65 6c65  as_dict..get_ele
-000003d0: 6d65 6e74 5f76 616c 7565 5f61 735f 6469  ment_value_as_di
-000003e0: 6374 5f6c 6973 74da 1d67 6574 5f65 6c65  ct_list..get_ele
-000003f0: 6d65 6e74 5f76 616c 7565 5f61 735f 646f  ment_value_as_do
-00000400: 6375 6d65 6e74 da1e 6669 6e64 5f65 6c65  cument..find_ele
-00000410: 6d65 6e74 5f76 616c 7565 5f61 735f 646f  ment_value_as_do
-00000420: 6375 6d65 6e74 da22 6765 745f 656c 656d  cument."get_elem
-00000430: 656e 745f 7661 6c75 655f 6173 5f64 6f63  ent_value_as_doc
-00000440: 756d 656e 745f 6c69 7374 da1e 6765 745f  ument_list..get_
-00000450: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
-00000460: 5f70 7269 6e63 6970 616c da1f 6669 6e64  _principal..find
-00000470: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
-00000480: 735f 7072 696e 6369 7061 6cda 2367 6574  s_principal.#get
-00000490: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
-000004a0: 735f 7072 696e 6369 7061 6c5f 6c69 7374  s_principal_list
+00000180: 656d 2903 da16 456c 656d 656e 7456 616c  em)...ElementVal
+00000190: 7565 5369 6d70 6c65 5479 7065 da11 456c  ueSimpleType..El
+000001a0: 656d 656e 7456 616c 7565 556e 696f 6eda  ementValueUnion.
+000001b0: 1854 6173 6b45 6c65 6d65 6e74 5661 6c75  .TaskElementValu
+000001c0: 6541 6363 6573 736f 7229 1ada 1161 6464  eAccessor)...add
+000001d0: 5f65 6c65 6d65 6e74 5f76 616c 7565 da16  _element_value..
+000001e0: 6164 645f 656c 656d 656e 745f 7661 6c75  add_element_valu
+000001f0: 655f 6c69 7374 da1a 6669 6e64 5f65 6c65  e_list..find_ele
+00000200: 6d65 6e74 5f76 616c 7565 5f61 735f 6461  ment_value_as_da
+00000210: 7465 da1a 6669 6e64 5f65 6c65 6d65 6e74  te..find_element
+00000220: 5f76 616c 7565 5f61 735f 6469 6374 da1e  _value_as_dict..
+00000230: 6669 6e64 5f65 6c65 6d65 6e74 5f76 616c  find_element_val
+00000240: 7565 5f61 735f 646f 6375 6d65 6e74 da1b  ue_as_document..
+00000250: 6669 6e64 5f65 6c65 6d65 6e74 5f76 616c  find_element_val
+00000260: 7565 5f61 735f 666c 6f61 74da 1f66 696e  ue_as_float..fin
+00000270: 645f 656c 656d 656e 745f 7661 6c75 655f  d_element_value_
+00000280: 6173 5f70 7269 6e63 6970 616c da19 6669  as_principal..fi
+00000290: 6e64 5f65 6c65 6d65 6e74 5f76 616c 7565  nd_element_value
+000002a0: 5f61 735f 7374 72da 1967 6574 5f65 6c65  _as_str..get_ele
+000002b0: 6d65 6e74 5f76 616c 7565 5f61 735f 6461  ment_value_as_da
+000002c0: 7465 da1e 6765 745f 656c 656d 656e 745f  te..get_element_
+000002d0: 7661 6c75 655f 6173 5f64 6174 655f 6c69  value_as_date_li
+000002e0: 7374 da19 6765 745f 656c 656d 656e 745f  st..get_element_
+000002f0: 7661 6c75 655f 6173 5f64 6963 74da 1e67  value_as_dict..g
+00000300: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
+00000310: 5f61 735f 6469 6374 5f6c 6973 74da 1d67  _as_dict_list..g
+00000320: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
+00000330: 5f61 735f 646f 6375 6d65 6e74 da22 6765  _as_document."ge
+00000340: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
+00000350: 6173 5f64 6f63 756d 656e 745f 6c69 7374  as_document_list
+00000360: da1a 6765 745f 656c 656d 656e 745f 7661  ..get_element_va
+00000370: 6c75 655f 6173 5f66 6c6f 6174 da1f 6765  lue_as_float..ge
+00000380: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
+00000390: 6173 5f66 6c6f 6174 5f6c 6973 74da 1e67  as_float_list..g
+000003a0: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
+000003b0: 5f61 735f 7072 696e 6369 7061 6cda 2367  _as_principal.#g
+000003c0: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
+000003d0: 5f61 735f 7072 696e 6369 7061 6c5f 6c69  _as_principal_li
+000003e0: 7374 da18 6765 745f 656c 656d 656e 745f  st..get_element_
+000003f0: 7661 6c75 655f 6173 5f73 7472 da1d 6765  value_as_str..ge
+00000400: 745f 656c 656d 656e 745f 7661 6c75 655f  t_element_value_
+00000410: 6173 5f73 7472 5f6c 6973 74da 1767 6574  as_str_list..get
+00000420: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
+00000430: 616c 6964 da1a 6765 745f 656c 656d 656e  alid..get_elemen
+00000440: 745f 7661 6c75 655f 7661 6c69 645f 6174  t_value_valid_at
+00000450: da11 7365 745f 656c 656d 656e 745f 7661  ..set_element_va
+00000460: 6c75 65da 1673 6574 5f65 6c65 6d65 6e74  lue..set_element
+00000470: 5f76 616c 7565 5f6c 6973 74da 1773 6574  _value_list..set
+00000480: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f76  _element_value_v
+00000490: 616c 6964 da1a 7365 745f 656c 656d 656e  alid..set_elemen
+000004a0: 745f 7661 6c75 655f 7661 6c69 645f 6174  t_value_valid_at
 000004b0: e902 0000 0029 01da 1653 6176 6554 6173  .....)...SaveTas
 000004c0: 6b45 6c65 6d65 6e74 5265 7175 6573 7463  kElementRequestc
 000004d0: 0000 0000 0000 0000 0000 0000 0000 0000  ................
 000004e0: 0300 0000 4000 0000 733e 0000 0065 005a  ....@...s>...e.Z
 000004f0: 0164 005a 0265 0364 019c 0164 0264 0384  .d.Z.e.d...d.d..
 00000500: 045a 0465 0565 0619 0064 049c 0164 0564  .Z.e.e...d...d.d
 00000510: 0684 045a 0765 0565 0819 0064 079c 0164  ...Z.e.e...d...d
@@ -91,48 +91,48 @@
 000005a0: 7079 7468 6f6e 2f6b 7566 6c6f 772d 7465  python/kuflow-te
 000005b0: 6d70 6f72 616c 2d61 6374 6976 6974 792d  mporal-activity-
 000005c0: 6b75 666c 6f77 2f6b 7566 6c6f 775f 7465  kuflow/kuflow_te
 000005d0: 6d70 6f72 616c 5f61 6374 6976 6974 795f  mporal_activity_
 000005e0: 6b75 666c 6f77 2f75 7469 6c73 2f5f 7361  kuflow/utils/_sa
 000005f0: 7665 5f74 6173 6b5f 656c 656d 656e 745f  ve_task_element_
 00000600: 7574 696c 732e 7079 da08 5f5f 696e 6974  utils.py..__init
-00000610: 5f5f 4700 0000 7302 0000 0000 017a 1843  __G...s......z.C
+00000610: 5f5f 4000 0000 7302 0000 0000 017a 1843  __@...s......z.C
 00000620: 7572 7265 6e74 4163 6365 7373 6f72 2e5f  urrentAccessor._
 00000630: 5f69 6e69 745f 5f29 01da 0e65 6c65 6d65  _init__)...eleme
 00000640: 6e74 5f76 616c 7565 7363 0200 0000 0000  nt_valuesc......
 00000650: 0000 0000 0000 0200 0000 0200 0000 4300  ..............C.
 00000660: 0000 7322 0000 0074 007c 0183 0164 016b  ..s"...t.|...d.k
 00000670: 0272 1664 007c 006a 015f 026e 087c 017c  .r.d.|.j._.n.|.|
 00000680: 006a 015f 0264 0053 00a9 024e 7201 0000  .j._.d.S...Nr...
 00000690: 0029 03da 036c 656e 7229 0000 0072 2e00  .)...lenr)...r..
 000006a0: 0000 2902 722a 0000 0072 2e00 0000 722b  ..).r*...r....r+
 000006b0: 0000 0072 2b00 0000 722c 0000 00da 1273  ...r+...r,.....s
 000006c0: 6574 5f65 6c65 6d65 6e74 5f76 616c 7565  et_element_value
-000006d0: 734a 0000 0073 0600 0000 0001 0c01 0a02  sJ...s..........
+000006d0: 7343 0000 0073 0600 0000 0001 0c01 0a02  sC...s..........
 000006e0: 7a22 4375 7272 656e 7441 6363 6573 736f  z"CurrentAccesso
 000006f0: 722e 7365 745f 656c 656d 656e 745f 7661  r.set_element_va
 00000700: 6c75 6573 2901 da06 7265 7475 726e 6301  lues)...returnc.
 00000710: 0000 0000 0000 0000 0000 0001 0000 0002  ................
 00000720: 0000 0043 0000 0073 2800 0000 7c00 6a00  ...C...s(...|.j.
 00000730: 6a01 6400 6b08 731c 7402 7c00 6a00 6a01  j.d.k.s.t.|.j.j.
 00000740: 8301 6401 6b02 7220 6700 5300 7c00 6a00  ..d.k.r g.S.|.j.
 00000750: 6a01 5300 722f 0000 0029 0372 2900 0000  j.S.r/...).r)...
 00000760: 722e 0000 0072 3000 0000 2901 722a 0000  r....r0...).r*..
 00000770: 0072 2b00 0000 722b 0000 0072 2c00 0000  .r+...r+...r,...
 00000780: da12 6765 745f 656c 656d 656e 745f 7661  ..get_element_va
-00000790: 6c75 6573 5000 0000 7306 0000 0000 011c  luesP...s.......
+00000790: 6c75 6573 4900 0000 7306 0000 0000 011c  luesI...s.......
 000007a0: 0104 027a 2243 7572 7265 6e74 4163 6365  ...z"CurrentAcce
 000007b0: 7373 6f72 2e67 6574 5f65 6c65 6d65 6e74  ssor.get_element
 000007c0: 5f76 616c 7565 734e 290a da08 5f5f 6e61  _valuesN)...__na
 000007d0: 6d65 5f5f da0a 5f5f 6d6f 6475 6c65 5f5f  me__..__module__
 000007e0: da0c 5f5f 7175 616c 6e61 6d65 5f5f 7226  ..__qualname__r&
-000007f0: 0000 0072 2d00 0000 7202 0000 0072 0900  ...r-...r....r..
+000007f0: 0000 0072 2d00 0000 7203 0000 0072 0900  ...r-...r....r..
 00000800: 0000 7231 0000 0072 0500 0000 7233 0000  ..r1...r....r3..
 00000810: 0072 2b00 0000 722b 0000 0072 2b00 0000  .r+...r+...r+...
-00000820: 722c 0000 0072 2700 0000 4600 0000 7306  r,...r'...F...s.
+00000820: 722c 0000 0072 2700 0000 3f00 0000 7306  r,...r'...?...s.
 00000830: 0000 0008 010e 0312 0672 2700 0000 6300  .........r'...c.
 00000840: 0000 0000 0000 0000 0000 0000 0000 0006  ................
 00000850: 0000 0040 0000 0073 7802 0000 6500 5a01  ...@...sx...e.Z.
 00000860: 6400 5a02 6503 6504 6505 6401 9c02 6402  d.Z.e.e.e.d...d.
 00000870: 6403 8404 8301 5a06 6503 6504 6507 6505  d.....Z.e.e.e.e.
 00000880: 6404 9c03 6405 6406 8404 8301 5a08 6503  d...d.d.....Z.e.
 00000890: 6504 6509 6505 1900 6504 6407 9c03 6408  e.e.e...e.d...d.
@@ -186,17 +186,17 @@
 00000b90: 6176 6554 6173 6b45 6c65 6d65 6e74 2072  aveTaskElement r
 00000ba0: 6571 7565 7374 2e0a 0a20 2020 2020 2020  equest...       
 00000bb0: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00000bc0: 2020 2020 2020 5472 7565 2069 6620 616c        True if al
 00000bd0: 6c20 7265 6c61 7465 6420 7661 6c69 6420  l related valid 
 00000be0: 7661 6c75 6573 2061 7265 2054 5255 452c  values are TRUE,
 00000bf0: 206f 7468 6572 7769 7365 2046 616c 7365   otherwise False
-00000c00: 2e0a 2020 2020 2020 2020 2902 720b 0000  ..        ).r...
+00000c00: 2e0a 2020 2020 2020 2020 2902 721f 0000  ..        ).r...
 00000c10: 0072 2700 0000 7228 0000 0072 2b00 0000  .r'...r(...r+...
-00000c20: 722b 0000 0072 2c00 0000 720b 0000 0058  r+...r,...r....X
+00000c20: 722b 0000 0072 2c00 0000 721f 0000 0051  r+...r,...r....Q
 00000c30: 0000 0073 0200 0000 000b 7a33 5361 7665  ...s......z3Save
 00000c40: 5461 736b 456c 656d 656e 7452 6571 7565  TaskElementReque
 00000c50: 7374 5574 696c 732e 6765 745f 656c 656d  stUtils.get_elem
 00000c60: 656e 745f 7661 6c75 655f 7661 6c69 6429  ent_value_valid)
 00000c70: 0372 2900 0000 da05 696e 6465 7872 3200  .r).....indexr2.
 00000c80: 0000 6302 0000 0000 0000 0000 0000 0002  ..c.............
 00000c90: 0000 0003 0000 0043 0000 0073 0e00 0000  .......C...s....
@@ -215,17 +215,17 @@
 00000d60: 7420 7661 6c75 6520 696e 6465 782e 0a0a  t value index...
 00000d70: 2020 2020 2020 2020 5265 7475 726e 733a          Returns:
 00000d80: 0a20 2020 2020 2020 2020 2020 2054 6865  .            The
 00000d90: 2072 6571 7565 7374 6564 2076 616c 6964   requested valid
 00000da0: 2076 616c 7565 2069 6620 6974 2065 7869   value if it exi
 00000db0: 7374 732c 206f 7468 6572 7769 7365 204e  sts, otherwise N
 00000dc0: 6f6e 652e 0a20 2020 2020 2020 2029 0272  one..        ).r
-00000dd0: 0c00 0000 7227 0000 0029 0272 2900 0000  ....r'...).r)...
+00000dd0: 2000 0000 7227 0000 0029 0272 2900 0000   ...r'...).r)...
 00000de0: 7238 0000 0072 2b00 0000 722b 0000 0072  r8...r+...r+...r
-00000df0: 2c00 0000 720c 0000 0065 0000 0073 0200  ,...r....e...s..
+00000df0: 2c00 0000 7220 0000 005e 0000 0073 0200  ,...r ...^...s..
 00000e00: 0000 000c 7a36 5361 7665 5461 736b 456c  ....z6SaveTaskEl
 00000e10: 656d 656e 7452 6571 7565 7374 5574 696c  ementRequestUtil
 00000e20: 732e 6765 745f 656c 656d 656e 745f 7661  s.get_element_va
 00000e30: 6c75 655f 7661 6c69 645f 6174 2903 7229  lue_valid_at).r)
 00000e40: 0000 00da 0576 616c 6964 7232 0000 0063  .....validr2...c
 00000e50: 0200 0000 0000 0000 0000 0000 0200 0000  ................
 00000e60: 0300 0000 4300 0000 7312 0000 0074 0074  ....C...s....t.t
@@ -239,18 +239,18 @@
 00000ee0: 2054 6865 2053 6176 6554 6173 6b45 6c65   The SaveTaskEle
 00000ef0: 6d65 6e74 2072 6571 7565 7374 2e0a 2020  ment request..  
 00000f00: 2020 2020 2020 2020 2020 7661 6c69 643a            valid:
 00000f10: 2054 6865 2076 616c 6964 2076 616c 7565   The valid value
 00000f20: 2e0a 0a20 2020 2020 2020 2052 6574 7572  ...        Retur
 00000f30: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 00000f40: 5468 6520 7061 7373 6564 2074 6173 6b2e  The passed task.
-00000f50: 0a20 2020 2020 2020 2029 0272 0d00 0000  .        ).r....
+00000f50: 0a20 2020 2020 2020 2029 0272 2300 0000  .        ).r#...
 00000f60: 7227 0000 0029 0272 2900 0000 7239 0000  r'...).r)...r9..
 00000f70: 0072 2b00 0000 722b 0000 0072 2c00 0000  .r+...r+...r,...
-00000f80: 720d 0000 0073 0000 0073 0400 0000 000c  r....s...s......
+00000f80: 7223 0000 006c 0000 0073 0400 0000 000c  r#...l...s......
 00000f90: 0e02 7a33 5361 7665 5461 736b 456c 656d  ..z3SaveTaskElem
 00000fa0: 656e 7452 6571 7565 7374 5574 696c 732e  entRequestUtils.
 00000fb0: 7365 745f 656c 656d 656e 745f 7661 6c75  set_element_valu
 00000fc0: 655f 7661 6c69 6429 0472 2900 0000 7239  e_valid).r)...r9
 00000fd0: 0000 0072 3800 0000 7232 0000 0063 0300  ...r8...r2...c..
 00000fe0: 0000 0000 0000 0000 0000 0300 0000 0400  ................
 00000ff0: 0000 4300 0000 7314 0000 0074 0074 017c  ..C...s....t.t.|
@@ -267,18 +267,18 @@
 000010a0: 6964 3a20 5468 6520 7661 6c69 6420 7661  id: The valid va
 000010b0: 6c75 652e 0a20 2020 2020 2020 2020 2020  lue..           
 000010c0: 2069 6e64 6578 3a20 5468 6520 656c 656d   index: The elem
 000010d0: 656e 7420 7661 6c75 6520 696e 6465 782e  ent value index.
 000010e0: 0a0a 2020 2020 2020 2020 5265 7475 726e  ..        Return
 000010f0: 733a 0a20 2020 2020 2020 2020 2020 2054  s:.            T
 00001100: 6865 2070 6173 7365 6420 7461 736b 2e0a  he passed task..
-00001110: 2020 2020 2020 2020 2902 720e 0000 0072          ).r....r
+00001110: 2020 2020 2020 2020 2902 7224 0000 0072          ).r$...r
 00001120: 2700 0000 2903 7229 0000 0072 3900 0000  '...).r)...r9...
 00001130: 7238 0000 0072 2b00 0000 722b 0000 0072  r8...r+...r+...r
-00001140: 2c00 0000 720e 0000 0083 0000 0073 0400  ,...r........s..
+00001140: 2c00 0000 7224 0000 007c 0000 0073 0400  ,...r$...|...s..
 00001150: 0000 000f 1002 7a36 5361 7665 5461 736b  ......z6SaveTask
 00001160: 456c 656d 656e 7452 6571 7565 7374 5574  ElementRequestUt
 00001170: 696c 732e 7365 745f 656c 656d 656e 745f  ils.set_element_
 00001180: 7661 6c75 655f 7661 6c69 645f 6174 4e29  value_valid_atN)
 00001190: 0372 2900 0000 da0d 656c 656d 656e 745f  .r).....element_
 000011a0: 7661 6c75 6572 3200 0000 6302 0000 0000  valuer2...c.....
 000011b0: 0000 0000 0000 0002 0000 0003 0000 0043  ...............C
@@ -296,17 +296,17 @@
 00001270: 7565 2e20 4966 2074 6865 2076 616c 7565  ue. If the value
 00001280: 2069 7320 4e6f 6e65 2c20 616c 6c20 6375   is None, all cu
 00001290: 7272 656e 7420 7661 6c75 6573 2061 7265  rrent values are
 000012a0: 2072 656d 6f76 6564 2e0a 0a20 2020 2020   removed...     
 000012b0: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 000012c0: 2020 2020 2020 2020 5468 6520 7061 7373          The pass
 000012d0: 6564 2074 6173 6b2e 0a20 2020 2020 2020  ed task..       
-000012e0: 2029 0272 0f00 0000 7227 0000 00a9 0272   ).r....r'.....r
+000012e0: 2029 0272 2100 0000 7227 0000 00a9 0272   ).r!...r'.....r
 000012f0: 2900 0000 723a 0000 0072 2b00 0000 722b  )...r:...r+...r+
-00001300: 0000 0072 2c00 0000 720f 0000 0096 0000  ...r,...r.......
+00001300: 0000 0072 2c00 0000 7221 0000 008f 0000  ...r,...r!......
 00001310: 0073 0400 0000 000e 0e02 7a2d 5361 7665  .s........z-Save
 00001320: 5461 736b 456c 656d 656e 7452 6571 7565  TaskElementReque
 00001330: 7374 5574 696c 732e 7365 745f 656c 656d  stUtils.set_elem
 00001340: 656e 745f 7661 6c75 6529 0372 2900 0000  ent_value).r)...
 00001350: 722e 0000 0072 3200 0000 6302 0000 0000  r....r2...c.....
 00001360: 0000 0000 0000 0002 0000 0003 0000 0043  ...............C
 00001370: 0000 0073 1200 0000 7400 7401 7c00 8301  ...s....t.t.|...
@@ -323,18 +323,18 @@
 00001420: 6c75 652e 2049 6620 7468 6520 7661 6c75  lue. If the valu
 00001430: 6520 6973 204e 6f6e 6520 6f72 2065 6d70  e is None or emp
 00001440: 7479 2c20 616c 6c20 6375 7272 656e 7420  ty, all current 
 00001450: 7661 6c75 6573 2061 7265 2072 656d 6f76  values are remov
 00001460: 6564 2e0a 0a20 2020 2020 2020 2052 6574  ed...        Ret
 00001470: 7572 6e73 3a0a 2020 2020 2020 2020 2020  urns:.          
 00001480: 2020 5468 6520 7061 7373 6564 2074 6173    The passed tas
-00001490: 6b2e 0a20 2020 2020 2020 2029 0272 1000  k..        ).r..
+00001490: 6b2e 0a20 2020 2020 2020 2029 0272 2200  k..        ).r".
 000014a0: 0000 7227 0000 00a9 0272 2900 0000 722e  ..r'.....r)...r.
 000014b0: 0000 0072 2b00 0000 722b 0000 0072 2c00  ...r+...r+...r,.
-000014c0: 0000 7210 0000 00a8 0000 0073 0400 0000  ..r........s....
+000014c0: 0000 7222 0000 00a1 0000 0073 0400 0000  ..r".......s....
 000014d0: 000e 0e02 7a32 5361 7665 5461 736b 456c  ....z2SaveTaskEl
 000014e0: 656d 656e 7452 6571 7565 7374 5574 696c  ementRequestUtil
 000014f0: 732e 7365 745f 656c 656d 656e 745f 7661  s.set_element_va
 00001500: 6c75 655f 6c69 7374 6302 0000 0000 0000  lue_listc.......
 00001510: 0000 0000 0002 0000 0003 0000 0043 0000  .............C..
 00001520: 0073 1200 0000 7400 7401 7c00 8301 7c01  .s....t.t.|...|.
 00001530: 8302 0100 7c00 5300 2901 6100 0100 000a  ....|.S.).a.....
@@ -350,17 +350,17 @@
 000015d0: 2e20 4966 2074 6865 2076 616c 7565 2069  . If the value i
 000015e0: 7320 4e6f 6e65 2c20 616c 6c20 6375 7272  s None, all curr
 000015f0: 656e 7420 7661 6c75 6573 2061 7265 2072  ent values are r
 00001600: 656d 6f76 6564 2e0a 0a20 2020 2020 2020  emoved...       
 00001610: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00001620: 2020 2020 2020 5468 6520 7061 7373 6564        The passed
 00001630: 2074 6173 6b2e 0a20 2020 2020 2020 2029   task..        )
-00001640: 0272 1100 0000 7227 0000 0072 3b00 0000  .r....r'...r;...
+00001640: 0272 0b00 0000 7227 0000 0072 3b00 0000  .r....r'...r;...
 00001650: 722b 0000 0072 2b00 0000 722c 0000 0072  r+...r+...r,...r
-00001660: 1100 0000 ba00 0000 7304 0000 0000 0e0e  ........s.......
+00001660: 0b00 0000 b300 0000 7304 0000 0000 0e0e  ........s.......
 00001670: 027a 2d53 6176 6554 6173 6b45 6c65 6d65  .z-SaveTaskEleme
 00001680: 6e74 5265 7175 6573 7455 7469 6c73 2e61  ntRequestUtils.a
 00001690: 6464 5f65 6c65 6d65 6e74 5f76 616c 7565  dd_element_value
 000016a0: 6302 0000 0000 0000 0000 0000 0002 0000  c...............
 000016b0: 0003 0000 0043 0000 0073 1200 0000 7400  .....C...s....t.
 000016c0: 7401 7c00 8301 7c01 8302 0100 7c00 5300  t.|...|.....|.S.
 000016d0: 2901 611a 0100 000a 2020 2020 2020 2020  ).a.....        
@@ -377,17 +377,17 @@
 00001780: 6f72 2065 6d70 7479 2c20 616c 6c20 6375  or empty, all cu
 00001790: 7272 656e 7420 7661 6c75 6573 2061 7265  rrent values are
 000017a0: 2072 656d 6f76 6564 2e0a 0a20 2020 2020   removed...     
 000017b0: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 000017c0: 2020 2020 2020 2020 5468 6520 7061 7373          The pass
 000017d0: 6564 206d 6f64 656c 2072 656c 6174 6564  ed model related
 000017e0: 206f 626a 6563 742e 0a20 2020 2020 2020   object..       
-000017f0: 2029 0272 1200 0000 7227 0000 0072 3c00   ).r....r'...r<.
+000017f0: 2029 0272 0c00 0000 7227 0000 0072 3c00   ).r....r'...r<.
 00001800: 0000 722b 0000 0072 2b00 0000 722c 0000  ..r+...r+...r,..
-00001810: 0072 1200 0000 cc00 0000 7304 0000 0000  .r........s.....
+00001810: 0072 0c00 0000 c500 0000 7304 0000 0000  .r........s.....
 00001820: 0e0e 027a 3253 6176 6554 6173 6b45 6c65  ...z2SaveTaskEle
 00001830: 6d65 6e74 5265 7175 6573 7455 7469 6c73  mentRequestUtils
 00001840: 2e61 6464 5f65 6c65 6d65 6e74 5f76 616c  .add_element_val
 00001850: 7565 5f6c 6973 7463 0100 0000 0000 0000  ue_listc........
 00001860: 0000 0000 0100 0000 0300 0000 4300 0000  ............C...
 00001870: 730c 0000 0074 0074 017c 0083 0183 0153  s....t.t.|.....S
 00001880: 0029 017a aa0a 2020 2020 2020 2020 4765  .).z..        Ge
@@ -397,17 +397,17 @@
 000018c0: 2020 2020 2020 2072 6571 7565 7374 3a20         request: 
 000018d0: 5468 6520 5361 7665 5461 736b 456c 656d  The SaveTaskElem
 000018e0: 656e 7420 7265 7175 6573 742e 0a0a 2020  ent request...  
 000018f0: 2020 2020 2020 5265 7475 726e 733a 0a20        Returns:. 
 00001900: 2020 2020 2020 2020 2020 2054 6865 2065             The e
 00001910: 6c65 6d65 6e74 2076 616c 7565 2061 7320  lement value as 
 00001920: 6120 7374 722e 0a20 2020 2020 2020 2029  a str..        )
-00001930: 0272 1300 0000 7227 0000 0072 2800 0000  .r....r'...r(...
+00001930: 0272 1d00 0000 7227 0000 0072 2800 0000  .r....r'...r(...
 00001940: 722b 0000 0072 2b00 0000 722c 0000 0072  r+...r+...r,...r
-00001950: 1300 0000 de00 0000 7302 0000 0000 0b7a  ........s......z
+00001950: 1d00 0000 d700 0000 7302 0000 0000 0b7a  ........s......z
 00001960: 3453 6176 6554 6173 6b45 6c65 6d65 6e74  4SaveTaskElement
 00001970: 5265 7175 6573 7455 7469 6c73 2e67 6574  RequestUtils.get
 00001980: 5f65 6c65 6d65 6e74 5f76 616c 7565 5f61  _element_value_a
 00001990: 735f 7374 7263 0100 0000 0000 0000 0000  s_strc..........
 000019a0: 0000 0100 0000 0300 0000 4300 0000 730c  ..........C...s.
 000019b0: 0000 0074 0074 017c 0083 0183 0153 0029  ...t.t.|.....S.)
 000019c0: 017a b10a 2020 2020 2020 2020 5472 7920  .z..        Try 
@@ -417,17 +417,17 @@
 00001a00: 2020 2020 2020 2020 2020 2020 7265 7175              requ
 00001a10: 6573 743a 2054 6865 2053 6176 6554 6173  est: The SaveTas
 00001a20: 6b45 6c65 6d65 6e74 2072 6571 7565 7374  kElement request
 00001a30: 2e0a 0a20 2020 2020 2020 2052 6574 7572  ...        Retur
 00001a40: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 00001a50: 5468 6520 656c 656d 656e 7420 7661 6c75  The element valu
 00001a60: 6520 6173 2061 2073 7472 2e0a 2020 2020  e as a str..    
-00001a70: 2020 2020 2902 7214 0000 0072 2700 0000      ).r....r'...
+00001a70: 2020 2020 2902 7212 0000 0072 2700 0000      ).r....r'...
 00001a80: 7228 0000 0072 2b00 0000 722b 0000 0072  r(...r+...r+...r
-00001a90: 2c00 0000 7214 0000 00eb 0000 0073 0200  ,...r........s..
+00001a90: 2c00 0000 7212 0000 00e4 0000 0073 0200  ,...r........s..
 00001aa0: 0000 000b 7a35 5361 7665 5461 736b 456c  ....z5SaveTaskEl
 00001ab0: 656d 656e 7452 6571 7565 7374 5574 696c  ementRequestUtil
 00001ac0: 732e 6669 6e64 5f65 6c65 6d65 6e74 5f76  s.find_element_v
 00001ad0: 616c 7565 5f61 735f 7374 7263 0100 0000  alue_as_strc....
 00001ae0: 0000 0000 0000 0000 0100 0000 0300 0000  ................
 00001af0: 4300 0000 730c 0000 0074 0074 017c 0083  C...s....t.t.|..
 00001b00: 0183 0153 0029 017a bc0a 2020 2020 2020  ...S.).z..      
@@ -438,17 +438,17 @@
 00001b50: 2020 2020 2020 2072 6571 7565 7374 3a20         request: 
 00001b60: 5468 6520 5361 7665 5461 736b 456c 656d  The SaveTaskElem
 00001b70: 656e 7420 7265 7175 6573 742e 0a0a 2020  ent request...  
 00001b80: 2020 2020 2020 5265 7475 726e 733a 0a20        Returns:. 
 00001b90: 2020 2020 2020 2020 2020 2054 6865 2065             The e
 00001ba0: 6c65 6d65 6e74 2076 616c 7565 7320 6173  lement values as
 00001bb0: 2061 2073 7472 206c 6973 742e 0a20 2020   a str list..   
-00001bc0: 2020 2020 2029 0272 1500 0000 7227 0000       ).r....r'..
+00001bc0: 2020 2020 2029 0272 1e00 0000 7227 0000       ).r....r'..
 00001bd0: 0072 2800 0000 722b 0000 0072 2b00 0000  .r(...r+...r+...
-00001be0: 722c 0000 0072 1500 0000 f800 0000 7302  r,...r........s.
+00001be0: 722c 0000 0072 1e00 0000 f100 0000 7302  r,...r........s.
 00001bf0: 0000 0000 0b7a 3953 6176 6554 6173 6b45  .....z9SaveTaskE
 00001c00: 6c65 6d65 6e74 5265 7175 6573 7455 7469  lementRequestUti
 00001c10: 6c73 2e67 6574 5f65 6c65 6d65 6e74 5f76  ls.get_element_v
 00001c20: 616c 7565 5f61 735f 7374 725f 6c69 7374  alue_as_str_list
 00001c30: 6301 0000 0000 0000 0000 0000 0001 0000  c...............
 00001c40: 0003 0000 0043 0000 0073 0c00 0000 7400  .....C...s....t.
 00001c50: 7401 7c00 8301 8301 5300 2901 7aae 0a20  t.|.....S.).z.. 
@@ -458,18 +458,18 @@
 00001c90: 656e 7473 3a0a 2020 2020 2020 2020 2020  ents:.          
 00001ca0: 2020 7265 7175 6573 743a 2054 6865 2053    request: The S
 00001cb0: 6176 6554 6173 6b45 6c65 6d65 6e74 2072  aveTaskElement r
 00001cc0: 6571 7565 7374 2e0a 0a20 2020 2020 2020  equest...       
 00001cd0: 2052 6574 7572 6e73 3a0a 2020 2020 2020   Returns:.      
 00001ce0: 2020 2020 2020 5468 6520 656c 656d 656e        The elemen
 00001cf0: 7420 7661 6c75 6520 6173 2061 2066 6c6f  t value as a flo
-00001d00: 6174 2e0a 2020 2020 2020 2020 2902 7216  at..        ).r.
+00001d00: 6174 2e0a 2020 2020 2020 2020 2902 7219  at..        ).r.
 00001d10: 0000 0072 2700 0000 7228 0000 0072 2b00  ...r'...r(...r+.
-00001d20: 0000 722b 0000 0072 2c00 0000 7216 0000  ..r+...r,...r...
-00001d30: 0005 0100 0073 0200 0000 000b 7a36 5361  .....s......z6Sa
+00001d20: 0000 722b 0000 0072 2c00 0000 7219 0000  ..r+...r,...r...
+00001d30: 00fe 0000 0073 0200 0000 000b 7a36 5361  .....s......z6Sa
 00001d40: 7665 5461 736b 456c 656d 656e 7452 6571  veTaskElementReq
 00001d50: 7565 7374 5574 696c 732e 6765 745f 656c  uestUtils.get_el
 00001d60: 656d 656e 745f 7661 6c75 655f 6173 5f66  ement_value_as_f
 00001d70: 6c6f 6174 6301 0000 0000 0000 0000 0000  loatc...........
 00001d80: 0001 0000 0003 0000 0043 0000 0073 0c00  .........C...s..
 00001d90: 0000 7400 7401 7c00 8301 8301 5300 2901  ..t.t.|.....S.).
 00001da0: 7ab5 0a20 2020 2020 2020 2054 7279 2074  z..        Try t
@@ -479,17 +479,17 @@
 00001de0: 0a20 2020 2020 2020 2020 2020 2072 6571  .            req
 00001df0: 7565 7374 3a20 5468 6520 5361 7665 5461  uest: The SaveTa
 00001e00: 736b 456c 656d 656e 7420 7265 7175 6573  skElement reques
 00001e10: 742e 0a0a 2020 2020 2020 2020 5265 7475  t...        Retu
 00001e20: 726e 733a 0a20 2020 2020 2020 2020 2020  rns:.           
 00001e30: 2054 6865 2065 6c65 6d65 6e74 2076 616c   The element val
 00001e40: 7565 2061 7320 6120 666c 6f61 742e 0a20  ue as a float.. 
-00001e50: 2020 2020 2020 2029 0272 1700 0000 7227         ).r....r'
+00001e50: 2020 2020 2020 2029 0272 1000 0000 7227         ).r....r'
 00001e60: 0000 0072 2800 0000 722b 0000 0072 2b00  ...r(...r+...r+.
-00001e70: 0000 722c 0000 0072 1700 0000 1201 0000  ..r,...r........
+00001e70: 0000 722c 0000 0072 1000 0000 0b01 0000  ..r,...r........
 00001e80: 7302 0000 0000 0b7a 3753 6176 6554 6173  s......z7SaveTas
 00001e90: 6b45 6c65 6d65 6e74 5265 7175 6573 7455  kElementRequestU
 00001ea0: 7469 6c73 2e66 696e 645f 656c 656d 656e  tils.find_elemen
 00001eb0: 745f 7661 6c75 655f 6173 5f66 6c6f 6174  t_value_as_float
 00001ec0: 6301 0000 0000 0000 0000 0000 0001 0000  c...............
 00001ed0: 0003 0000 0043 0000 0073 0c00 0000 7400  .....C...s....t.
 00001ee0: 7401 7c00 8301 8301 5300 2901 7ab5 0a20  t.|.....S.).z.. 
@@ -500,17 +500,17 @@
 00001f30: 2020 2020 2020 2020 2072 6571 7565 7374           request
 00001f40: 3a20 5468 6520 5361 7665 5461 736b 456c  : The SaveTaskEl
 00001f50: 656d 656e 7420 7265 7175 6573 742e 0a0a  ement request...
 00001f60: 2020 2020 2020 2020 5265 7475 726e 733a          Returns:
 00001f70: 0a20 2020 2020 2020 2020 2020 2054 6865  .            The
 00001f80: 2065 6c65 6d65 6e74 2076 616c 7565 2061   element value a
 00001f90: 7320 6120 666c 6f61 742e 0a20 2020 2020  s a float..     
-00001fa0: 2020 2029 0272 1800 0000 7227 0000 0072     ).r....r'...r
+00001fa0: 2020 2029 0272 1a00 0000 7227 0000 0072     ).r....r'...r
 00001fb0: 2800 0000 722b 0000 0072 2b00 0000 722c  (...r+...r+...r,
-00001fc0: 0000 0072 1800 0000 1f01 0000 7302 0000  ...r........s...
+00001fc0: 0000 0072 1a00 0000 1801 0000 7302 0000  ...r........s...
 00001fd0: 0000 0b7a 3b53 6176 6554 6173 6b45 6c65  ...z;SaveTaskEle
 00001fe0: 6d65 6e74 5265 7175 6573 7455 7469 6c73  mentRequestUtils
 00001ff0: 2e67 6574 5f65 6c65 6d65 6e74 5f76 616c  .get_element_val
 00002000: 7565 5f61 735f 666c 6f61 745f 6c69 7374  ue_as_float_list
 00002010: 6301 0000 0000 0000 0000 0000 0001 0000  c...............
 00002020: 0003 0000 0043 0000 0073 0c00 0000 7400  .....C...s....t.
 00002030: 7401 7c00 8301 8301 5300 2901 7aac 0a20  t.|.....S.).z.. 
@@ -520,17 +520,17 @@
 00002070: 6e74 733a 0a20 2020 2020 2020 2020 2020  nts:.           
 00002080: 2072 6571 7565 7374 3a20 5468 6520 5361   request: The Sa
 00002090: 7665 5461 736b 456c 656d 656e 7420 7265  veTaskElement re
 000020a0: 7175 6573 742e 0a0a 2020 2020 2020 2020  quest...        
 000020b0: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 000020c0: 2020 2020 2054 6865 2065 6c65 6d65 6e74       The element
 000020d0: 2076 616c 7565 2061 7320 6120 6461 7465   value as a date
-000020e0: 2e0a 2020 2020 2020 2020 2902 7219 0000  ..        ).r...
+000020e0: 2e0a 2020 2020 2020 2020 2902 7213 0000  ..        ).r...
 000020f0: 0072 2700 0000 7228 0000 0072 2b00 0000  .r'...r(...r+...
-00002100: 722b 0000 0072 2c00 0000 7219 0000 002c  r+...r,...r....,
+00002100: 722b 0000 0072 2c00 0000 7213 0000 0025  r+...r,...r....%
 00002110: 0100 0073 0200 0000 000b 7a35 5361 7665  ...s......z5Save
 00002120: 5461 736b 456c 656d 656e 7452 6571 7565  TaskElementReque
 00002130: 7374 5574 696c 732e 6765 745f 656c 656d  stUtils.get_elem
 00002140: 656e 745f 7661 6c75 655f 6173 5f64 6174  ent_value_as_dat
 00002150: 6563 0100 0000 0000 0000 0000 0000 0100  ec..............
 00002160: 0000 0300 0000 4300 0000 730c 0000 0074  ......C...s....t
 00002170: 0074 017c 0083 0183 0153 0029 017a b40a  .t.|.....S.).z..
@@ -541,17 +541,17 @@
 000021c0: 2020 2020 2020 2020 2020 7265 7175 6573            reques
 000021d0: 743a 2054 6865 2053 6176 6554 6173 6b45  t: The SaveTaskE
 000021e0: 6c65 6d65 6e74 2072 6571 7565 7374 2e0a  lement request..
 000021f0: 0a20 2020 2020 2020 2052 6574 7572 6e73  .        Returns
 00002200: 3a0a 2020 2020 2020 2020 2020 2020 5468  :.            Th
 00002210: 6520 656c 656d 656e 7420 7661 6c75 6520  e element value 
 00002220: 6173 2061 2064 6174 652e 0a20 2020 2020  as a date..     
-00002230: 2020 2029 0272 1a00 0000 7227 0000 0072     ).r....r'...r
+00002230: 2020 2029 0272 0d00 0000 7227 0000 0072     ).r....r'...r
 00002240: 2800 0000 722b 0000 0072 2b00 0000 722c  (...r+...r+...r,
-00002250: 0000 0072 1a00 0000 3901 0000 7302 0000  ...r....9...s...
+00002250: 0000 0072 0d00 0000 3201 0000 7302 0000  ...r....2...s...
 00002260: 0000 0b7a 3653 6176 6554 6173 6b45 6c65  ...z6SaveTaskEle
 00002270: 6d65 6e74 5265 7175 6573 7455 7469 6c73  mentRequestUtils
 00002280: 2e66 696e 645f 656c 656d 656e 745f 7661  .find_element_va
 00002290: 6c75 655f 6173 5f64 6174 6563 0100 0000  lue_as_datec....
 000022a0: 0000 0000 0000 0000 0100 0000 0300 0000  ................
 000022b0: 4300 0000 730c 0000 0074 0074 017c 0083  C...s....t.t.|..
 000022c0: 0183 0153 0029 017a b50a 2020 2020 2020  ...S.).z..      
@@ -562,17 +562,17 @@
 00002310: 2072 6571 7565 7374 3a20 5468 6520 5361   request: The Sa
 00002320: 7665 5461 736b 456c 656d 656e 7420 7265  veTaskElement re
 00002330: 7175 6573 742e 0a0a 2020 2020 2020 2020  quest...        
 00002340: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 00002350: 2020 2020 2054 6865 2065 6c65 6d65 6e74       The element
 00002360: 2076 616c 7565 7320 6173 2064 6174 6520   values as date 
 00002370: 6c69 7374 2e0a 2020 2020 2020 2020 2902  list..        ).
-00002380: 721b 0000 0072 2700 0000 7228 0000 0072  r....r'...r(...r
-00002390: 2b00 0000 722b 0000 0072 2c00 0000 721b  +...r+...r,...r.
-000023a0: 0000 0046 0100 0073 0200 0000 000b 7a3a  ...F...s......z:
+00002380: 7214 0000 0072 2700 0000 7228 0000 0072  r....r'...r(...r
+00002390: 2b00 0000 722b 0000 0072 2c00 0000 7214  +...r+...r,...r.
+000023a0: 0000 003f 0100 0073 0200 0000 000b 7a3a  ...?...s......z:
 000023b0: 5361 7665 5461 736b 456c 656d 656e 7452  SaveTaskElementR
 000023c0: 6571 7565 7374 5574 696c 732e 6765 745f  equestUtils.get_
 000023d0: 656c 656d 656e 745f 7661 6c75 655f 6173  element_value_as
 000023e0: 5f64 6174 655f 6c69 7374 6301 0000 0000  _date_listc.....
 000023f0: 0000 0000 0000 0001 0000 0003 0000 0043  ...............C
 00002400: 0000 0073 0c00 0000 7400 7401 7c00 8301  ...s....t.t.|...
 00002410: 8301 5300 2901 7aac 0a20 2020 2020 2020  ..S.).z..       
@@ -582,17 +582,17 @@
 00002450: 2020 2020 2020 2020 2020 2072 6571 7565             reque
 00002460: 7374 3a20 5468 6520 5361 7665 5461 736b  st: The SaveTask
 00002470: 456c 656d 656e 7420 7265 7175 6573 742e  Element request.
 00002480: 0a0a 2020 2020 2020 2020 5265 7475 726e  ..        Return
 00002490: 733a 0a20 2020 2020 2020 2020 2020 2054  s:.            T
 000024a0: 6865 2065 6c65 6d65 6e74 2076 616c 7565  he element value
 000024b0: 2061 7320 6120 6469 6374 2e0a 2020 2020   as a dict..    
-000024c0: 2020 2020 2902 721c 0000 0072 2700 0000      ).r....r'...
+000024c0: 2020 2020 2902 7215 0000 0072 2700 0000      ).r....r'...
 000024d0: 7228 0000 0072 2b00 0000 722b 0000 0072  r(...r+...r+...r
-000024e0: 2c00 0000 721c 0000 0053 0100 0073 0200  ,...r....S...s..
+000024e0: 2c00 0000 7215 0000 004c 0100 0073 0200  ,...r....L...s..
 000024f0: 0000 000b 7a35 5361 7665 5461 736b 456c  ....z5SaveTaskEl
 00002500: 656d 656e 7452 6571 7565 7374 5574 696c  ementRequestUtil
 00002510: 732e 6765 745f 656c 656d 656e 745f 7661  s.get_element_va
 00002520: 6c75 655f 6173 5f64 6963 7463 0100 0000  lue_as_dictc....
 00002530: 0000 0000 0000 0000 0100 0000 0300 0000  ................
 00002540: 4300 0000 730c 0000 0074 0074 017c 0083  C...s....t.t.|..
 00002550: 0183 0153 0029 017a b30a 2020 2020 2020  ...S.).z..      
@@ -602,18 +602,18 @@
 00002590: 6d65 6e74 733a 0a20 2020 2020 2020 2020  ments:.         
 000025a0: 2020 2072 6571 7565 7374 3a20 5468 6520     request: The 
 000025b0: 5361 7665 5461 736b 456c 656d 656e 7420  SaveTaskElement 
 000025c0: 7265 7175 6573 742e 0a0a 2020 2020 2020  request...      
 000025d0: 2020 5265 7475 726e 733a 0a20 2020 2020    Returns:.     
 000025e0: 2020 2020 2020 2054 6865 2065 6c65 6d65         The eleme
 000025f0: 6e74 2076 616c 7565 2061 7320 6120 6469  nt value as a di
-00002600: 6374 2e0a 2020 2020 2020 2020 2902 721d  ct..        ).r.
+00002600: 6374 2e0a 2020 2020 2020 2020 2902 720e  ct..        ).r.
 00002610: 0000 0072 2700 0000 7228 0000 0072 2b00  ...r'...r(...r+.
-00002620: 0000 722b 0000 0072 2c00 0000 721d 0000  ..r+...r,...r...
-00002630: 0060 0100 0073 0200 0000 000b 7a36 5361  .`...s......z6Sa
+00002620: 0000 722b 0000 0072 2c00 0000 720e 0000  ..r+...r,...r...
+00002630: 0059 0100 0073 0200 0000 000b 7a36 5361  .Y...s......z6Sa
 00002640: 7665 5461 736b 456c 656d 656e 7452 6571  veTaskElementReq
 00002650: 7565 7374 5574 696c 732e 6669 6e64 5f65  uestUtils.find_e
 00002660: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
 00002670: 6469 6374 6301 0000 0000 0000 0000 0000  dictc...........
 00002680: 0001 0000 0003 0000 0043 0000 0073 0c00  .........C...s..
 00002690: 0000 7400 7401 7c00 8301 8301 5300 2901  ..t.t.|.....S.).
 000026a0: 7ab5 0a20 2020 2020 2020 2047 6574 2061  z..        Get a
@@ -623,17 +623,17 @@
 000026e0: 2020 2020 2020 2020 2020 7265 7175 6573            reques
 000026f0: 743a 2054 6865 2053 6176 6554 6173 6b45  t: The SaveTaskE
 00002700: 6c65 6d65 6e74 2072 6571 7565 7374 2e0a  lement request..
 00002710: 0a20 2020 2020 2020 2052 6574 7572 6e73  .        Returns
 00002720: 3a0a 2020 2020 2020 2020 2020 2020 5468  :.            Th
 00002730: 6520 656c 656d 656e 7420 7661 6c75 6573  e element values
 00002740: 2061 7320 6469 6374 206c 6973 742e 0a20   as dict list.. 
-00002750: 2020 2020 2020 2029 0272 1e00 0000 7227         ).r....r'
+00002750: 2020 2020 2020 2029 0272 1600 0000 7227         ).r....r'
 00002760: 0000 0072 2800 0000 722b 0000 0072 2b00  ...r(...r+...r+.
-00002770: 0000 722c 0000 0072 1e00 0000 6d01 0000  ..r,...r....m...
+00002770: 0000 722c 0000 0072 1600 0000 6601 0000  ..r,...r....f...
 00002780: 7302 0000 0000 0b7a 3a53 6176 6554 6173  s......z:SaveTas
 00002790: 6b45 6c65 6d65 6e74 5265 7175 6573 7455  kElementRequestU
 000027a0: 7469 6c73 2e67 6574 5f65 6c65 6d65 6e74  tils.get_element
 000027b0: 5f76 616c 7565 5f61 735f 6469 6374 5f6c  _value_as_dict_l
 000027c0: 6973 7463 0100 0000 0000 0000 0000 0000  istc............
 000027d0: 0100 0000 0300 0000 4300 0000 730c 0000  ........C...s...
 000027e0: 0074 0074 017c 0083 0183 0153 0029 017a  .t.t.|.....S.).z
@@ -647,17 +647,17 @@
 00002860: 6b45 6c65 6d65 6e74 2072 6571 7565 7374  kElement request
 00002870: 2e0a 0a20 2020 2020 2020 2052 6574 7572  ...        Retur
 00002880: 6e73 3a0a 2020 2020 2020 2020 2020 2020  ns:.            
 00002890: 5468 6520 656c 656d 656e 7420 7661 6c75  The element valu
 000028a0: 6520 6173 2061 2054 6173 6b45 6c65 6d65  e as a TaskEleme
 000028b0: 6e74 5661 6c75 6544 6f63 756d 656e 7449  ntValueDocumentI
 000028c0: 7465 6d2e 0a20 2020 2020 2020 2029 0272  tem..        ).r
-000028d0: 1f00 0000 7227 0000 0072 2800 0000 722b  ....r'...r(...r+
-000028e0: 0000 0072 2b00 0000 722c 0000 0072 1f00  ...r+...r,...r..
-000028f0: 0000 7a01 0000 7302 0000 0000 0b7a 3953  ..z...s......z9S
+000028d0: 1700 0000 7227 0000 0072 2800 0000 722b  ....r'...r(...r+
+000028e0: 0000 0072 2b00 0000 722c 0000 0072 1700  ...r+...r,...r..
+000028f0: 0000 7301 0000 7302 0000 0000 0b7a 3953  ..s...s......z9S
 00002900: 6176 6554 6173 6b45 6c65 6d65 6e74 5265  aveTaskElementRe
 00002910: 7175 6573 7455 7469 6c73 2e67 6574 5f65  questUtils.get_e
 00002920: 6c65 6d65 6e74 5f76 616c 7565 5f61 735f  lement_value_as_
 00002930: 646f 6375 6d65 6e74 6301 0000 0000 0000  documentc.......
 00002940: 0000 0000 0001 0000 0003 0000 0043 0000  .............C..
 00002950: 0073 0c00 0000 7400 7401 7c00 8301 8301  .s....t.t.|.....
 00002960: 5300 2901 7ae4 0a20 2020 2020 2020 2054  S.).z..        T
@@ -670,17 +670,17 @@
 000029d0: 3a20 5468 6520 5361 7665 5461 736b 456c  : The SaveTaskEl
 000029e0: 656d 656e 7420 7265 7175 6573 742e 0a0a  ement request...
 000029f0: 2020 2020 2020 2020 5265 7475 726e 733a          Returns:
 00002a00: 0a20 2020 2020 2020 2020 2020 2054 6865  .            The
 00002a10: 2065 6c65 6d65 6e74 2076 616c 7565 2061   element value a
 00002a20: 7320 6120 5461 736b 456c 656d 656e 7456  s a TaskElementV
 00002a30: 616c 7565 446f 6375 6d65 6e74 4974 656d  alueDocumentItem
-00002a40: 2e0a 2020 2020 2020 2020 2902 7220 0000  ..        ).r ..
+00002a40: 2e0a 2020 2020 2020 2020 2902 720f 0000  ..        ).r...
 00002a50: 0072 2700 0000 7228 0000 0072 2b00 0000  .r'...r(...r+...
-00002a60: 722b 0000 0072 2c00 0000 7220 0000 0087  r+...r,...r ....
+00002a60: 722b 0000 0072 2c00 0000 720f 0000 0080  r+...r,...r.....
 00002a70: 0100 0073 0200 0000 000b 7a3a 5361 7665  ...s......z:Save
 00002a80: 5461 736b 456c 656d 656e 7452 6571 7565  TaskElementReque
 00002a90: 7374 5574 696c 732e 6669 6e64 5f65 6c65  stUtils.find_ele
 00002aa0: 6d65 6e74 5f76 616c 7565 5f61 735f 646f  ment_value_as_do
 00002ab0: 6375 6d65 6e74 6301 0000 0000 0000 0000  cumentc.........
 00002ac0: 0000 0001 0000 0003 0000 0043 0000 0073  ...........C...s
 00002ad0: 0c00 0000 7400 7401 7c00 8301 8301 5300  ....t.t.|.....S.
@@ -694,17 +694,17 @@
 00002b50: 2053 6176 6554 6173 6b45 6c65 6d65 6e74   SaveTaskElement
 00002b60: 2072 6571 7565 7374 2e0a 0a20 2020 2020   request...     
 00002b70: 2020 2052 6574 7572 6e73 3a0a 2020 2020     Returns:.    
 00002b80: 2020 2020 2020 2020 5468 6520 656c 656d          The elem
 00002b90: 656e 7420 7661 6c75 6573 2061 7320 5461  ent values as Ta
 00002ba0: 736b 456c 656d 656e 7456 616c 7565 446f  skElementValueDo
 00002bb0: 6375 6d65 6e74 4974 656d 206c 6973 742e  cumentItem list.
-00002bc0: 0a20 2020 2020 2020 2029 0272 2100 0000  .        ).r!...
+00002bc0: 0a20 2020 2020 2020 2029 0272 1800 0000  .        ).r....
 00002bd0: 7227 0000 0072 2800 0000 722b 0000 0072  r'...r(...r+...r
-00002be0: 2b00 0000 722c 0000 0072 2100 0000 9401  +...r,...r!.....
+00002be0: 2b00 0000 722c 0000 0072 1800 0000 8d01  +...r,...r......
 00002bf0: 0000 7302 0000 0000 0b7a 3e53 6176 6554  ..s......z>SaveT
 00002c00: 6173 6b45 6c65 6d65 6e74 5265 7175 6573  askElementReques
 00002c10: 7455 7469 6c73 2e67 6574 5f65 6c65 6d65  tUtils.get_eleme
 00002c20: 6e74 5f76 616c 7565 5f61 735f 646f 6375  nt_value_as_docu
 00002c30: 6d65 6e74 5f6c 6973 7463 0100 0000 0000  ment_listc......
 00002c40: 0000 0000 0000 0100 0000 0300 0000 4300  ..............C.
 00002c50: 0000 730c 0000 0074 0074 017c 0083 0183  ..s....t.t.|....
@@ -718,17 +718,17 @@
 00002cd0: 5361 7665 5461 736b 456c 656d 656e 7420  SaveTaskElement 
 00002ce0: 7265 7175 6573 742e 0a0a 2020 2020 2020  request...      
 00002cf0: 2020 5265 7475 726e 733a 0a20 2020 2020    Returns:.     
 00002d00: 2020 2020 2020 2054 6865 2065 6c65 6d65         The eleme
 00002d10: 6e74 2076 616c 7565 2061 7320 6120 5461  nt value as a Ta
 00002d20: 736b 456c 656d 656e 7456 616c 7565 5072  skElementValuePr
 00002d30: 696e 6369 7061 6c49 7465 6d2e 0a20 2020  incipalItem..   
-00002d40: 2020 2020 2029 0272 2200 0000 7227 0000       ).r"...r'..
+00002d40: 2020 2020 2029 0272 1b00 0000 7227 0000       ).r....r'..
 00002d50: 0072 2800 0000 722b 0000 0072 2b00 0000  .r(...r+...r+...
-00002d60: 722c 0000 0072 2200 0000 a101 0000 7302  r,...r".......s.
+00002d60: 722c 0000 0072 1b00 0000 9a01 0000 7302  r,...r........s.
 00002d70: 0000 0000 0b7a 3a53 6176 6554 6173 6b45  .....z:SaveTaskE
 00002d80: 6c65 6d65 6e74 5265 7175 6573 7455 7469  lementRequestUti
 00002d90: 6c73 2e67 6574 5f65 6c65 6d65 6e74 5f76  ls.get_element_v
 00002da0: 616c 7565 5f61 735f 7072 696e 6369 7061  alue_as_principa
 00002db0: 6c63 0100 0000 0000 0000 0000 0000 0100  lc..............
 00002dc0: 0000 0300 0000 4300 0000 730c 0000 0074  ......C...s....t
 00002dd0: 0074 017c 0083 0183 0153 0029 017a e60a  .t.|.....S.).z..
@@ -742,17 +742,17 @@
 00002e50: 5361 7665 5461 736b 456c 656d 656e 7420  SaveTaskElement 
 00002e60: 7265 7175 6573 742e 0a0a 2020 2020 2020  request...      
 00002e70: 2020 5265 7475 726e 733a 0a20 2020 2020    Returns:.     
 00002e80: 2020 2020 2020 2054 6865 2065 6c65 6d65         The eleme
 00002e90: 6e74 2076 616c 7565 2061 7320 6120 5461  nt value as a Ta
 00002ea0: 736b 456c 656d 656e 7456 616c 7565 5072  skElementValuePr
 00002eb0: 696e 6369 7061 6c49 7465 6d2e 0a20 2020  incipalItem..   
-00002ec0: 2020 2020 2029 0272 2300 0000 7227 0000       ).r#...r'..
+00002ec0: 2020 2020 2029 0272 1100 0000 7227 0000       ).r....r'..
 00002ed0: 0072 2800 0000 722b 0000 0072 2b00 0000  .r(...r+...r+...
-00002ee0: 722c 0000 0072 2300 0000 ae01 0000 7302  r,...r#.......s.
+00002ee0: 722c 0000 0072 1100 0000 a701 0000 7302  r,...r........s.
 00002ef0: 0000 0000 0b7a 3b53 6176 6554 6173 6b45  .....z;SaveTaskE
 00002f00: 6c65 6d65 6e74 5265 7175 6573 7455 7469  lementRequestUti
 00002f10: 6c73 2e66 696e 645f 656c 656d 656e 745f  ls.find_element_
 00002f20: 7661 6c75 655f 6173 5f70 7269 6e63 6970  value_as_princip
 00002f30: 616c 6301 0000 0000 0000 0000 0000 0001  alc.............
 00002f40: 0000 0003 0000 0043 0000 0073 0c00 0000  .......C...s....
 00002f50: 7400 7401 7c00 8301 8301 5300 2901 7ae7  t.t.|.....S.).z.
@@ -766,51 +766,51 @@
 00002fd0: 7665 5461 736b 456c 656d 656e 7420 7265  veTaskElement re
 00002fe0: 7175 6573 742e 0a0a 2020 2020 2020 2020  quest...        
 00002ff0: 5265 7475 726e 733a 0a20 2020 2020 2020  Returns:.       
 00003000: 2020 2020 2054 6865 2065 6c65 6d65 6e74       The element
 00003010: 2076 616c 7565 7320 6173 2054 6173 6b45   values as TaskE
 00003020: 6c65 6d65 6e74 5661 6c75 6550 7269 6e63  lementValuePrinc
 00003030: 6970 616c 4974 656d 206c 6973 742e 0a20  ipalItem list.. 
-00003040: 2020 2020 2020 2029 0272 2400 0000 7227         ).r$...r'
+00003040: 2020 2020 2020 2029 0272 1c00 0000 7227         ).r....r'
 00003050: 0000 0072 2800 0000 722b 0000 0072 2b00  ...r(...r+...r+.
-00003060: 0000 722c 0000 0072 2400 0000 bb01 0000  ..r,...r$.......
+00003060: 0000 722c 0000 0072 1c00 0000 b401 0000  ..r,...r........
 00003070: 7302 0000 0000 0b7a 3f53 6176 6554 6173  s......z?SaveTas
 00003080: 6b45 6c65 6d65 6e74 5265 7175 6573 7455  kElementRequestU
 00003090: 7469 6c73 2e67 6574 5f65 6c65 6d65 6e74  tils.get_element
 000030a0: 5f76 616c 7565 5f61 735f 7072 696e 6369  _value_as_princi
 000030b0: 7061 6c5f 6c69 7374 2901 4e29 014e 2901  pal_list).N).N).
 000030c0: 4e29 014e 292a 7234 0000 0072 3500 0000  N).N)*r4...r5...
 000030d0: 7236 0000 00da 0c73 7461 7469 636d 6574  r6.....staticmet
-000030e0: 686f 6472 2600 0000 da04 626f 6f6c 720b  hodr&.....boolr.
-000030f0: 0000 00da 0369 6e74 720c 0000 0072 0300  .....intr....r..
-00003100: 0000 720d 0000 0072 0e00 0000 720a 0000  ..r....r....r...
-00003110: 0072 0f00 0000 7202 0000 0072 1000 0000  .r....r....r....
-00003120: 7211 0000 0072 1200 0000 da03 7374 7272  r....r......strr
-00003130: 1300 0000 7214 0000 0072 1500 0000 da05  ....r....r......
-00003140: 666c 6f61 7472 1600 0000 7217 0000 0072  floatr....r....r
-00003150: 1800 0000 7204 0000 0072 1900 0000 721a  ....r....r....r.
-00003160: 0000 0072 1b00 0000 da04 6469 6374 721c  ...r......dictr.
-00003170: 0000 0072 1d00 0000 721e 0000 0072 0600  ...r....r....r..
-00003180: 0000 721f 0000 0072 2000 0000 7221 0000  ..r....r ...r!..
-00003190: 0072 0700 0000 7222 0000 0072 2300 0000  .r....r"...r#...
-000031a0: 7224 0000 0072 2b00 0000 722b 0000 0072  r$...r+...r+...r
-000031b0: 2b00 0000 722c 0000 0072 3700 0000 5700  +...r,...r7...W.
+000030e0: 686f 6472 2600 0000 da04 626f 6f6c 721f  hodr&.....boolr.
+000030f0: 0000 00da 0369 6e74 7220 0000 0072 0400  .....intr ...r..
+00003100: 0000 7223 0000 0072 2400 0000 7208 0000  ..r#...r$...r...
+00003110: 0072 2100 0000 7203 0000 0072 2200 0000  .r!...r....r"...
+00003120: 720b 0000 0072 0c00 0000 da03 7374 7272  r....r......strr
+00003130: 1d00 0000 7212 0000 0072 1e00 0000 da05  ....r....r......
+00003140: 666c 6f61 7472 1900 0000 7210 0000 0072  floatr....r....r
+00003150: 1a00 0000 7202 0000 0072 1300 0000 720d  ....r....r....r.
+00003160: 0000 0072 1400 0000 da04 6469 6374 7215  ...r......dictr.
+00003170: 0000 0072 0e00 0000 7216 0000 0072 0600  ...r....r....r..
+00003180: 0000 7217 0000 0072 0f00 0000 7218 0000  ..r....r....r...
+00003190: 0072 0700 0000 721b 0000 0072 1100 0000  .r....r....r....
+000031a0: 721c 0000 0072 2b00 0000 722b 0000 0072  r....r+...r+...r
+000031b0: 2b00 0000 722c 0000 0072 3700 0000 5000  +...r,...r7...P.
 000031c0: 0000 7398 0000 0008 0102 0112 0c02 0114  ..s.............
 000031d0: 0d02 0118 0f02 0202 0006 0002 0102 fe0e  ................
 000031e0: 1202 0200 ff02 0102 0006 0102 fe0e 1102  ................
 000031f0: 0200 ff02 0102 000a 0102 fe0e 1102 0200  ................
 00003200: ff02 0102 0006 0102 fe0e 1102 0200 ff02  ................
 00003210: 0102 000a 0102 fe0e 1102 0112 0c02 0116  ................
 00003220: 0c02 0116 0c02 0112 0c02 0112 0c02 0116  ................
 00003230: 0c02 0112 0c02 0116 0c02 0116 0c02 0112  ................
 00003240: 0c02 0116 0c02 0116 0c02 0112 0c02 0116  ................
 00003250: 0c02 0116 0c02 0112 0c02 0116 0c02 0172  ...............r
-00003260: 3700 0000 4e29 2cda 0674 7970 696e 6772  7...N),..typingr
-00003270: 0200 0000 7203 0000 00da 0864 6174 6574  ....r......datet
-00003280: 696d 6572 0400 0000 da12 6b75 666c 6f77  imer......kuflow
+00003260: 3700 0000 4e29 2cda 0864 6174 6574 696d  7...N),..datetim
+00003270: 6572 0200 0000 da06 7479 7069 6e67 7203  er......typingr.
+00003280: 0000 0072 0400 0000 da12 6b75 666c 6f77  ...r......kuflow
 00003290: 5f72 6573 742e 6d6f 6465 6c73 7205 0000  _rest.modelsr...
 000032a0: 0072 0600 0000 7207 0000 00da 116b 7566  .r....r......kuf
 000032b0: 6c6f 775f 7265 7374 2e75 7469 6c73 7208  low_rest.utilsr.
 000032c0: 0000 0072 0900 0000 720a 0000 005a 206b  ...r....r....Z k
 000032d0: 7566 6c6f 775f 7265 7374 2e75 7469 6c73  uflow_rest.utils
 000032e0: 2e65 6c65 6d65 6e74 5f76 616c 7565 7372  .element_valuesr
 000032f0: 0b00 0000 720c 0000 0072 0d00 0000 720e  ....r....r....r.
@@ -820,9 +820,9 @@
 00003330: 7218 0000 0072 1900 0000 721a 0000 0072  r....r....r....r
 00003340: 1b00 0000 721c 0000 0072 1d00 0000 721e  ....r....r....r.
 00003350: 0000 0072 1f00 0000 7220 0000 0072 2100  ...r....r ...r!.
 00003360: 0000 7222 0000 0072 2300 0000 7224 0000  ..r"...r#...r$..
 00003370: 00da 066d 6f64 656c 7372 2600 0000 7227  ...modelsr&...r'
 00003380: 0000 0072 3700 0000 722b 0000 0072 2b00  ...r7...r+...r+.
 00003390: 0000 722b 0000 0072 2c00 0000 da08 3c6d  ..r+...r,.....<m
-000033a0: 6f64 756c 653e 1a00 0000 730e 0000 0010  odule>....s.....
-000033b0: 010c 0214 0514 0570 1c0c 0310 11         .......p.....
+000033a0: 6f64 756c 653e 1a00 0000 730e 0000 000c  odule>....s.....
+000033b0: 0110 0214 0114 0170 1d0c 0310 11         .......p.....
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/__pycache__/_save_task_json_forms_value_data_request_utils.cpython-38.pyc` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/__pycache__/_save_task_json_forms_value_data_request_utils.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Tue Jun 20 07:20:29 2023 UTC, .py size: 15436 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 2% similar despite different names*

```diff
@@ -1,74 +1,74 @@
-00000000: 550d 0d0a 0000 0000 3d53 9164 4c3c 0000  U.......=S.dL<..
+00000000: 550d 0d0a 0000 0000 d3ec 9b64 403c 0000  U..........d@<..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 be00 0000 6400  .....@...s....d.
-00000030: 6401 6c00 6d01 5a01 6d02 5a02 6d03 5a03  d.l.m.Z.m.Z.m.Z.
-00000040: 0100 6400 6402 6c04 6d05 5a05 6d04 5a04  ..d.d.l.m.Z.m.Z.
+00000030: 6401 6c00 6d01 5a01 6d00 5a00 0100 6400  d.l.m.Z.m.Z...d.
+00000040: 6402 6c02 6d03 5a03 6d04 5a04 6d05 5a05  d.l.m.Z.m.Z.m.Z.
 00000050: 0100 6400 6403 6c06 6d07 5a07 6d08 5a08  ..d.d.l.m.Z.m.Z.
-00000060: 6d09 5a09 6d0a 5a0a 6d0b 5a0b 6d0c 5a0c  m.Z.m.Z.m.Z.m.Z.
-00000070: 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f 6d10 5a10  m.Z.m.Z.m.Z.m.Z.
-00000080: 6d11 5a11 6d12 5a12 6d13 5a13 6d14 5a14  m.Z.m.Z.m.Z.m.Z.
-00000090: 6d15 5a15 6d16 5a16 6d17 5a17 6d18 5a18  m.Z.m.Z.m.Z.m.Z.
-000000a0: 6d19 5a19 6d1a 5a1a 6d1b 5a1b 0100 6400  m.Z.m.Z.m.Z...d.
-000000b0: 6404 6c1c 6d1d 5a1d 6d1e 5a1e 0100 6405  d.l.m.Z.m.Z...d.
+00000060: 0100 6400 6404 6c09 6d0a 5a0a 6d0b 5a0b  ..d.d.l.m.Z.m.Z.
+00000070: 6d0c 5a0c 6d0d 5a0d 6d0e 5a0e 6d0f 5a0f  m.Z.m.Z.m.Z.m.Z.
+00000080: 6d10 5a10 6d11 5a11 6d12 5a12 6d13 5a13  m.Z.m.Z.m.Z.m.Z.
+00000090: 6d14 5a14 6d15 5a15 6d16 5a16 6d17 5a17  m.Z.m.Z.m.Z.m.Z.
+000000a0: 6d18 5a18 6d19 5a19 6d1a 5a1a 6d1b 5a1b  m.Z.m.Z.m.Z.m.Z.
+000000b0: 6d1c 5a1c 6d1d 5a1d 6d1e 5a1e 0100 6405  m.Z.m.Z.m.Z...d.
 000000c0: 6406 6c1f 6d20 5a20 0100 4700 6407 6408  d.l.m Z ..G.d.d.
-000000d0: 8400 6408 6507 8303 5a21 4700 6409 640a  ..d.e...Z!G.d.d.
+000000d0: 8400 6408 650a 8303 5a21 4700 6409 640a  ..d.e...Z!G.d.d.
 000000e0: 8400 640a 8302 5a22 640b 5300 290c e900  ..d...Z"d.S.)...
-000000f0: 0000 0029 03da 0341 6e79 da04 4469 6374  ...)...Any..Dict
-00000100: da08 4f70 7469 6f6e 616c 2902 da04 6461  ..Optional)...da
-00000110: 7465 da08 6461 7465 7469 6d65 2915 da14  te..datetime)...
-00000120: 4a73 6f6e 466f 726d 4461 7461 4163 6365  JsonFormDataAcce
-00000130: 7373 6f72 da13 4a73 6f6e 466f 726d 7353  ssor..JsonFormsS
-00000140: 696d 706c 6554 7970 65da 2066 696e 645f  impleType. find_
-00000150: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
-00000160: 7274 795f 6173 5f64 6174 65da 2466 696e  rty_as_date.$fin
-00000170: 645f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  d_json_forms_pro
-00000180: 7065 7274 795f 6173 5f64 6174 6574 696d  perty_as_datetim
-00000190: 65da 2066 696e 645f 6a73 6f6e 5f66 6f72  e. find_json_for
-000001a0: 6d73 5f70 726f 7065 7274 795f 6173 5f64  ms_property_as_d
-000001b0: 6963 74da 2166 696e 645f 6a73 6f6e 5f66  ict.!find_json_f
-000001c0: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
-000001d0: 5f66 6c6f 6174 da1f 6669 6e64 5f6a 736f  _float..find_jso
-000001e0: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
-000001f0: 5f61 735f 696e 74da 2b66 696e 645f 6a73  _as_int.+find_js
-00000200: 6f6e 5f66 6f72 6d73 5f70 726f 7065 7274  on_forms_propert
-00000210: 795f 6173 5f6a 736f 6e5f 666f 726d 735f  y_as_json_forms_
-00000220: 6669 6c65 da30 6669 6e64 5f6a 736f 6e5f  file.0find_json_
-00000230: 666f 726d 735f 7072 6f70 6572 7479 5f61  forms_property_a
-00000240: 735f 6a73 6f6e 5f66 6f72 6d73 5f70 7269  s_json_forms_pri
-00000250: 6e63 6970 616c da20 6669 6e64 5f6a 736f  ncipal. find_jso
-00000260: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
-00000270: 5f61 735f 6c69 7374 da1f 6669 6e64 5f6a  _as_list..find_j
-00000280: 736f 6e5f 666f 726d 735f 7072 6f70 6572  son_forms_proper
-00000290: 7479 5f61 735f 7374 72da 1f67 6574 5f6a  ty_as_str..get_j
-000002a0: 736f 6e5f 666f 726d 735f 7072 6f70 6572  son_forms_proper
-000002b0: 7479 5f61 735f 6461 7465 da23 6765 745f  ty_as_date.#get_
-000002c0: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
-000002d0: 7274 795f 6173 5f64 6174 6574 696d 65da  rty_as_datetime.
-000002e0: 1f67 6574 5f6a 736f 6e5f 666f 726d 735f  .get_json_forms_
-000002f0: 7072 6f70 6572 7479 5f61 735f 6469 6374  property_as_dict
-00000300: da20 6765 745f 6a73 6f6e 5f66 6f72 6d73  . get_json_forms
-00000310: 5f70 726f 7065 7274 795f 6173 5f66 6c6f  _property_as_flo
-00000320: 6174 da1e 6765 745f 6a73 6f6e 5f66 6f72  at..get_json_for
-00000330: 6d73 5f70 726f 7065 7274 795f 6173 5f69  ms_property_as_i
-00000340: 6e74 da2a 6765 745f 6a73 6f6e 5f66 6f72  nt.*get_json_for
-00000350: 6d73 5f70 726f 7065 7274 795f 6173 5f6a  ms_property_as_j
-00000360: 736f 6e5f 666f 726d 735f 6669 6c65 da2f  son_forms_file./
-00000370: 6765 745f 6a73 6f6e 5f66 6f72 6d73 5f70  get_json_forms_p
-00000380: 726f 7065 7274 795f 6173 5f6a 736f 6e5f  roperty_as_json_
-00000390: 666f 726d 735f 7072 696e 6369 7061 6cda  forms_principal.
-000003a0: 1f67 6574 5f6a 736f 6e5f 666f 726d 735f  .get_json_forms_
-000003b0: 7072 6f70 6572 7479 5f61 735f 6c69 7374  property_as_list
-000003c0: da1e 6765 745f 6a73 6f6e 5f66 6f72 6d73  ..get_json_forms
-000003d0: 5f70 726f 7065 7274 795f 6173 5f73 7472  _property_as_str
-000003e0: da1a 7570 6461 7465 5f6a 736f 6e5f 666f  ..update_json_fo
-000003f0: 726d 735f 7072 6f70 6572 7479 2902 da0d  rms_property)...
-00000400: 4a73 6f6e 466f 726d 7346 696c 65da 124a  JsonFormsFile..J
-00000410: 736f 6e46 6f72 6d73 5072 696e 6369 7061  sonFormsPrincipa
-00000420: 6ce9 0200 0000 2901 da21 5361 7665 5461  l.....)..!SaveTa
+000000f0: 0000 0029 02da 0464 6174 65da 0864 6174  ...)...date..dat
+00000100: 6574 696d 6529 03da 0341 6e79 da04 4469  etime)...Any..Di
+00000110: 6374 da08 4f70 7469 6f6e 616c 2902 da0d  ct..Optional)...
+00000120: 4a73 6f6e 466f 726d 7346 696c 65da 124a  JsonFormsFile..J
+00000130: 736f 6e46 6f72 6d73 5072 696e 6369 7061  sonFormsPrincipa
+00000140: 6c29 15da 144a 736f 6e46 6f72 6d44 6174  l)...JsonFormDat
+00000150: 6141 6363 6573 736f 72da 134a 736f 6e46  aAccessor..JsonF
+00000160: 6f72 6d73 5369 6d70 6c65 5479 7065 da20  ormsSimpleType. 
+00000170: 6669 6e64 5f6a 736f 6e5f 666f 726d 735f  find_json_forms_
+00000180: 7072 6f70 6572 7479 5f61 735f 6461 7465  property_as_date
+00000190: da24 6669 6e64 5f6a 736f 6e5f 666f 726d  .$find_json_form
+000001a0: 735f 7072 6f70 6572 7479 5f61 735f 6461  s_property_as_da
+000001b0: 7465 7469 6d65 da20 6669 6e64 5f6a 736f  tetime. find_jso
+000001c0: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
+000001d0: 5f61 735f 6469 6374 da21 6669 6e64 5f6a  _as_dict.!find_j
+000001e0: 736f 6e5f 666f 726d 735f 7072 6f70 6572  son_forms_proper
+000001f0: 7479 5f61 735f 666c 6f61 74da 1f66 696e  ty_as_float..fin
+00000200: 645f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  d_json_forms_pro
+00000210: 7065 7274 795f 6173 5f69 6e74 da2b 6669  perty_as_int.+fi
+00000220: 6e64 5f6a 736f 6e5f 666f 726d 735f 7072  nd_json_forms_pr
+00000230: 6f70 6572 7479 5f61 735f 6a73 6f6e 5f66  operty_as_json_f
+00000240: 6f72 6d73 5f66 696c 65da 3066 696e 645f  orms_file.0find_
+00000250: 6a73 6f6e 5f66 6f72 6d73 5f70 726f 7065  json_forms_prope
+00000260: 7274 795f 6173 5f6a 736f 6e5f 666f 726d  rty_as_json_form
+00000270: 735f 7072 696e 6369 7061 6cda 2066 696e  s_principal. fin
+00000280: 645f 6a73 6f6e 5f66 6f72 6d73 5f70 726f  d_json_forms_pro
+00000290: 7065 7274 795f 6173 5f6c 6973 74da 1f66  perty_as_list..f
+000002a0: 696e 645f 6a73 6f6e 5f66 6f72 6d73 5f70  ind_json_forms_p
+000002b0: 726f 7065 7274 795f 6173 5f73 7472 da1f  roperty_as_str..
+000002c0: 6765 745f 6a73 6f6e 5f66 6f72 6d73 5f70  get_json_forms_p
+000002d0: 726f 7065 7274 795f 6173 5f64 6174 65da  roperty_as_date.
+000002e0: 2367 6574 5f6a 736f 6e5f 666f 726d 735f  #get_json_forms_
+000002f0: 7072 6f70 6572 7479 5f61 735f 6461 7465  property_as_date
+00000300: 7469 6d65 da1f 6765 745f 6a73 6f6e 5f66  time..get_json_f
+00000310: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
+00000320: 5f64 6963 74da 2067 6574 5f6a 736f 6e5f  _dict. get_json_
+00000330: 666f 726d 735f 7072 6f70 6572 7479 5f61  forms_property_a
+00000340: 735f 666c 6f61 74da 1e67 6574 5f6a 736f  s_float..get_jso
+00000350: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
+00000360: 5f61 735f 696e 74da 2a67 6574 5f6a 736f  _as_int.*get_jso
+00000370: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
+00000380: 5f61 735f 6a73 6f6e 5f66 6f72 6d73 5f66  _as_json_forms_f
+00000390: 696c 65da 2f67 6574 5f6a 736f 6e5f 666f  ile./get_json_fo
+000003a0: 726d 735f 7072 6f70 6572 7479 5f61 735f  rms_property_as_
+000003b0: 6a73 6f6e 5f66 6f72 6d73 5f70 7269 6e63  json_forms_princ
+000003c0: 6970 616c da1f 6765 745f 6a73 6f6e 5f66  ipal..get_json_f
+000003d0: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
+000003e0: 5f6c 6973 74da 1e67 6574 5f6a 736f 6e5f  _list..get_json_
+000003f0: 666f 726d 735f 7072 6f70 6572 7479 5f61  forms_property_a
+00000400: 735f 7374 72da 1a75 7064 6174 655f 6a73  s_str..update_js
+00000410: 6f6e 5f66 6f72 6d73 5f70 726f 7065 7274  on_forms_propert
+00000420: 79e9 0200 0000 2901 da21 5361 7665 5461  y.....)..!SaveTa
 00000430: 736b 4a73 6f6e 466f 726d 7356 616c 7565  skJsonFormsValue
 00000440: 4461 7461 5265 7175 6573 7463 0000 0000  DataRequestc....
 00000450: 0000 0000 0000 0000 0000 0000 0400 0000  ................
 00000460: 4000 0000 734e 0000 0065 005a 0164 005a  @...sN...e.Z.d.Z
 00000470: 0265 0364 019c 0164 0264 0384 045a 0465  .e.d...d.d...Z.e
 00000480: 0565 0665 0765 0866 0219 0019 0064 049c  .e.e.e.f.....d..
 00000490: 0164 0564 0684 045a 0965 0565 0665 0765  .d.d...Z.e.e.e.e
@@ -86,42 +86,42 @@
 00000550: 6374 6976 6974 792d 6b75 666c 6f77 2f6b  ctivity-kuflow/k
 00000560: 7566 6c6f 775f 7465 6d70 6f72 616c 5f61  uflow_temporal_a
 00000570: 6374 6976 6974 795f 6b75 666c 6f77 2f75  ctivity_kuflow/u
 00000580: 7469 6c73 2f5f 7361 7665 5f74 6173 6b5f  tils/_save_task_
 00000590: 6a73 6f6e 5f66 6f72 6d73 5f76 616c 7565  json_forms_value
 000005a0: 5f64 6174 615f 7265 7175 6573 745f 7574  _data_request_ut
 000005b0: 696c 732e 7079 da08 5f5f 696e 6974 5f5f  ils.py..__init__
-000005c0: 3c00 0000 7302 0000 0000 017a 2443 7572  <...s......z$Cur
+000005c0: 3a00 0000 7302 0000 0000 017a 2443 7572  :...s......z$Cur
 000005d0: 7265 6e74 4a73 6f6e 466f 726d 4461 7461  rentJsonFormData
 000005e0: 4163 6365 7373 6f72 2e5f 5f69 6e69 745f  Accessor.__init_
 000005f0: 5f29 01da 0672 6574 7572 6e63 0100 0000  _)...returnc....
 00000600: 0000 0000 0000 0000 0100 0000 0100 0000  ................
 00000610: 4300 0000 7308 0000 007c 006a 006a 0153  C...s....|.j.j.S
 00000620: 0072 2300 0000 a902 7222 0000 00da 0464  .r#.....r".....d
 00000630: 6174 6129 0172 2400 0000 7225 0000 0072  ata).r$...r%...r
 00000640: 2500 0000 7226 0000 00da 0867 6574 5f64  %...r&.....get_d
-00000650: 6174 613f 0000 0073 0200 0000 0001 7a24  ata?...s......z$
+00000650: 6174 613d 0000 0073 0200 0000 0001 7a24  ata=...s......z$
 00000660: 4375 7272 656e 744a 736f 6e46 6f72 6d44  CurrentJsonFormD
 00000670: 6174 6141 6363 6573 736f 722e 6765 745f  ataAccessor.get_
 00000680: 6461 7461 2901 722a 0000 0063 0200 0000  data).r*...c....
 00000690: 0000 0000 0000 0000 0200 0000 0200 0000  ................
 000006a0: 4300 0000 730c 0000 007c 017c 006a 005f  C...s....|.|.j._
 000006b0: 0164 0053 0072 2300 0000 7229 0000 0029  .d.S.r#...r)...)
 000006c0: 0272 2400 0000 722a 0000 0072 2500 0000  .r$...r*...r%...
 000006d0: 7225 0000 0072 2600 0000 da08 7365 745f  r%...r&.....set_
-000006e0: 6461 7461 4200 0000 7302 0000 0000 017a  dataB...s......z
+000006e0: 6461 7461 4000 0000 7302 0000 0000 017a  data@...s......z
 000006f0: 2443 7572 7265 6e74 4a73 6f6e 466f 726d  $CurrentJsonForm
 00000700: 4461 7461 4163 6365 7373 6f72 2e73 6574  DataAccessor.set
 00000710: 5f64 6174 614e 290b da08 5f5f 6e61 6d65  _dataN)...__name
 00000720: 5f5f da0a 5f5f 6d6f 6475 6c65 5f5f da0c  __..__module__..
 00000730: 5f5f 7175 616c 6e61 6d65 5f5f 721f 0000  __qualname__r...
-00000740: 0072 2700 0000 7204 0000 0072 0300 0000  .r'...r....r....
-00000750: da03 7374 7272 0200 0000 722b 0000 0072  ..strr....r+...r
+00000740: 0072 2700 0000 7206 0000 0072 0500 0000  .r'...r....r....
+00000750: da03 7374 7272 0400 0000 722b 0000 0072  ..strr....r+...r
 00000760: 2c00 0000 7225 0000 0072 2500 0000 7225  ,...r%...r%...r%
-00000770: 0000 0072 2600 0000 7220 0000 003b 0000  ...r&...r ...;..
+00000770: 0000 0072 2600 0000 7220 0000 0039 0000  ...r&...r ...9..
 00000780: 0073 0600 0000 0801 0e03 1a03 7220 0000  .s..........r ..
 00000790: 0063 0000 0000 0000 0000 0000 0000 0000  .c..............
 000007a0: 0000 0600 0000 4000 0000 73d8 0100 0065  ......@...s....e
 000007b0: 005a 0164 005a 0265 0365 0465 0565 0564  .Z.d.Z.e.e.e.e.d
 000007c0: 019c 0364 0264 0384 0483 015a 0665 0365  ...d.d.....Z.e.e
 000007d0: 0465 0565 0765 0519 0064 019c 0364 0464  .e.e.e...d...d.d
 000007e0: 0584 0483 015a 0865 0365 0465 0565 0964  .....Z.e.e.e.e.d
@@ -179,18 +179,18 @@
 00000b20: 6c75 6520 6966 2065 7869 7374 732e 0a0a  lue if exists...
 00000b30: 2020 2020 2020 2020 5261 6973 6573 3a0a          Raises:.
 00000b40: 2020 2020 2020 2020 2020 2020 5661 6c75              Valu
 00000b50: 6545 7272 6f72 3a20 4966 2070 726f 7065  eError: If prope
 00000b60: 7274 7920 7661 6c75 6520 646f 6573 6e27  rty value doesn'
 00000b70: 7420 6578 6973 7420 6f72 2068 6173 2069  t exist or has i
 00000b80: 6e63 6f72 7265 6374 2066 6f72 6d61 740a  ncorrect format.
-00000b90: 2020 2020 2020 2020 2902 721a 0000 0072          ).r....r
+00000b90: 2020 2020 2020 2020 2902 721c 0000 0072          ).r....r
 00000ba0: 2000 0000 a902 7222 0000 0072 3200 0000   .....r"...r2...
 00000bb0: 7225 0000 0072 2500 0000 7226 0000 0072  r%...r%...r&...r
-00000bc0: 1a00 0000 4700 0000 7302 0000 0000 0f7a  ....G...s......z
+00000bc0: 1c00 0000 4500 0000 7302 0000 0000 0f7a  ....E...s......z
 00000bd0: 4553 6176 6554 6173 6b4a 736f 6e46 6f72  ESaveTaskJsonFor
 00000be0: 6d73 5661 6c75 6544 6174 6152 6571 7565  msValueDataReque
 00000bf0: 7374 5574 696c 732e 6765 745f 6a73 6f6e  stUtils.get_json
 00000c00: 5f66 6f72 6d73 5f70 726f 7065 7274 795f  _forms_property_
 00000c10: 6173 5f73 7472 6302 0000 0000 0000 0000  as_strc.........
 00000c20: 0000 0002 0000 0003 0000 0043 0000 0073  ...........C...s
 00000c30: 0e00 0000 7400 7401 7c00 8301 7c01 8302  ....t.t.|...|...
@@ -215,17 +215,17 @@
 00000d60: 2020 2054 6865 2070 726f 7065 7274 7920     The property 
 00000d70: 7661 6c75 6520 6966 2065 7869 7374 732e  value if exists.
 00000d80: 0a0a 2020 2020 2020 2020 5261 6973 6573  ..        Raises
 00000d90: 3a0a 2020 2020 2020 2020 2020 2020 5661  :.            Va
 00000da0: 6c75 6545 7272 6f72 3a20 4966 2070 726f  lueError: If pro
 00000db0: 7065 7274 7920 7661 6c75 6520 6861 7320  perty value has 
 00000dc0: 696e 636f 7272 6563 7420 666f 726d 6174  incorrect format
-00000dd0: 0a20 2020 2020 2020 2029 0272 1100 0000  .        ).r....
+00000dd0: 0a20 2020 2020 2020 2029 0272 1300 0000  .        ).r....
 00000de0: 7220 0000 0072 3300 0000 7225 0000 0072  r ...r3...r%...r
-00000df0: 2500 0000 7226 0000 0072 1100 0000 5800  %...r&...r....X.
+00000df0: 2500 0000 7226 0000 0072 1300 0000 5600  %...r&...r....V.
 00000e00: 0000 7302 0000 0000 117a 4653 6176 6554  ..s......zFSaveT
 00000e10: 6173 6b4a 736f 6e46 6f72 6d73 5661 6c75  askJsonFormsValu
 00000e20: 6544 6174 6152 6571 7565 7374 5574 696c  eDataRequestUtil
 00000e30: 732e 6669 6e64 5f6a 736f 6e5f 666f 726d  s.find_json_form
 00000e40: 735f 7072 6f70 6572 7479 5f61 735f 7374  s_property_as_st
 00000e50: 7263 0200 0000 0000 0000 0000 0000 0200  rc..............
 00000e60: 0000 0300 0000 4300 0000 730e 0000 0074  ......C...s....t
@@ -252,17 +252,17 @@
 00000fb0: 7473 2e0a 0a20 2020 2020 2020 2052 6169  ts...        Rai
 00000fc0: 7365 733a 0a20 2020 2020 2020 2020 2020  ses:.           
 00000fd0: 2056 616c 7565 4572 726f 723a 2049 6620   ValueError: If 
 00000fe0: 7072 6f70 6572 7479 2076 616c 7565 2064  property value d
 00000ff0: 6f65 736e 2774 2065 7869 7374 206f 7220  oesn't exist or 
 00001000: 6861 7320 696e 636f 7272 6563 7420 666f  has incorrect fo
 00001010: 726d 6174 0a20 2020 2020 2020 2029 0272  rmat.        ).r
-00001020: 1600 0000 7220 0000 0072 3300 0000 7225  ....r ...r3...r%
-00001030: 0000 0072 2500 0000 7226 0000 0072 1600  ...r%...r&...r..
-00001040: 0000 6b00 0000 7302 0000 0000 0f7a 4553  ..k...s......zES
+00001020: 1800 0000 7220 0000 0072 3300 0000 7225  ....r ...r3...r%
+00001030: 0000 0072 2500 0000 7226 0000 0072 1800  ...r%...r&...r..
+00001040: 0000 6900 0000 7302 0000 0000 0f7a 4553  ..i...s......zES
 00001050: 6176 6554 6173 6b4a 736f 6e46 6f72 6d73  aveTaskJsonForms
 00001060: 5661 6c75 6544 6174 6152 6571 7565 7374  ValueDataRequest
 00001070: 5574 696c 732e 6765 745f 6a73 6f6e 5f66  Utils.get_json_f
 00001080: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
 00001090: 5f69 6e74 6302 0000 0000 0000 0000 0000  _intc...........
 000010a0: 0002 0000 0003 0000 0043 0000 0073 0e00  .........C...s..
 000010b0: 0000 7400 7401 7c00 8301 7c01 8302 5300  ..t.t.|...|...S.
@@ -287,17 +287,17 @@
 000011e0: 2054 6865 2070 726f 7065 7274 7920 7661   The property va
 000011f0: 6c75 6520 6966 2065 7869 7374 732e 0a0a  lue if exists...
 00001200: 2020 2020 2020 2020 5261 6973 6573 3a0a          Raises:.
 00001210: 2020 2020 2020 2020 2020 2020 5661 6c75              Valu
 00001220: 6545 7272 6f72 3a20 4966 2070 726f 7065  eError: If prope
 00001230: 7274 7920 7661 6c75 6520 6861 7320 696e  rty value has in
 00001240: 636f 7272 6563 7420 666f 726d 6174 0a20  correct format. 
-00001250: 2020 2020 2020 2029 0272 0d00 0000 7220         ).r....r 
+00001250: 2020 2020 2020 2029 0272 0f00 0000 7220         ).r....r 
 00001260: 0000 0072 3300 0000 7225 0000 0072 2500  ...r3...r%...r%.
-00001270: 0000 7226 0000 0072 0d00 0000 7c00 0000  ..r&...r....|...
+00001270: 0000 7226 0000 0072 0f00 0000 7a00 0000  ..r&...r....z...
 00001280: 7302 0000 0000 117a 4653 6176 6554 6173  s......zFSaveTas
 00001290: 6b4a 736f 6e46 6f72 6d73 5661 6c75 6544  kJsonFormsValueD
 000012a0: 6174 6152 6571 7565 7374 5574 696c 732e  ataRequestUtils.
 000012b0: 6669 6e64 5f6a 736f 6e5f 666f 726d 735f  find_json_forms_
 000012c0: 7072 6f70 6572 7479 5f61 735f 696e 7463  property_as_intc
 000012d0: 0200 0000 0000 0000 0000 0000 0200 0000  ................
 000012e0: 0300 0000 4300 0000 730e 0000 0074 0074  ....C...s....t.t
@@ -324,17 +324,17 @@
 00001430: 7473 2e0a 0a20 2020 2020 2020 2052 6169  ts...        Rai
 00001440: 7365 733a 0a20 2020 2020 2020 2020 2020  ses:.           
 00001450: 2056 616c 7565 4572 726f 723a 2049 6620   ValueError: If 
 00001460: 7072 6f70 6572 7479 2076 616c 7565 2064  property value d
 00001470: 6f65 736e 2774 2065 7869 7374 206f 7220  oesn't exist or 
 00001480: 6861 7320 696e 636f 7272 6563 7420 666f  has incorrect fo
 00001490: 726d 6174 0a20 2020 2020 2020 2029 0272  rmat.        ).r
-000014a0: 1500 0000 7220 0000 0072 3300 0000 7225  ....r ...r3...r%
-000014b0: 0000 0072 2500 0000 7226 0000 0072 1500  ...r%...r&...r..
-000014c0: 0000 8f00 0000 7302 0000 0000 0f7a 4753  ......s......zGS
+000014a0: 1700 0000 7220 0000 0072 3300 0000 7225  ....r ...r3...r%
+000014b0: 0000 0072 2500 0000 7226 0000 0072 1700  ...r%...r&...r..
+000014c0: 0000 8d00 0000 7302 0000 0000 0f7a 4753  ......s......zGS
 000014d0: 6176 6554 6173 6b4a 736f 6e46 6f72 6d73  aveTaskJsonForms
 000014e0: 5661 6c75 6544 6174 6152 6571 7565 7374  ValueDataRequest
 000014f0: 5574 696c 732e 6765 745f 6a73 6f6e 5f66  Utils.get_json_f
 00001500: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
 00001510: 5f66 6c6f 6174 6302 0000 0000 0000 0000  _floatc.........
 00001520: 0000 0002 0000 0003 0000 0043 0000 0073  ...........C...s
 00001530: 0e00 0000 7400 7401 7c00 8301 7c01 8302  ....t.t.|...|...
@@ -359,18 +359,18 @@
 00001660: 2020 2020 2054 6865 2070 726f 7065 7274       The propert
 00001670: 7920 7661 6c75 6520 6966 2065 7869 7374  y value if exist
 00001680: 732e 0a0a 2020 2020 2020 2020 5261 6973  s...        Rais
 00001690: 6573 3a0a 2020 2020 2020 2020 2020 2020  es:.            
 000016a0: 5661 6c75 6545 7272 6f72 3a20 4966 2070  ValueError: If p
 000016b0: 726f 7065 7274 7920 7661 6c75 6520 6861  roperty value ha
 000016c0: 7320 696e 636f 7272 6563 7420 666f 726d  s incorrect form
-000016d0: 6174 0a20 2020 2020 2020 2029 0272 0c00  at.        ).r..
+000016d0: 6174 0a20 2020 2020 2020 2029 0272 0e00  at.        ).r..
 000016e0: 0000 7220 0000 0072 3300 0000 7225 0000  ..r ...r3...r%..
-000016f0: 0072 2500 0000 7226 0000 0072 0c00 0000  .r%...r&...r....
-00001700: a000 0000 7302 0000 0000 117a 4853 6176  ....s......zHSav
+000016f0: 0072 2500 0000 7226 0000 0072 0e00 0000  .r%...r&...r....
+00001700: 9e00 0000 7302 0000 0000 117a 4853 6176  ....s......zHSav
 00001710: 6554 6173 6b4a 736f 6e46 6f72 6d73 5661  eTaskJsonFormsVa
 00001720: 6c75 6544 6174 6152 6571 7565 7374 5574  lueDataRequestUt
 00001730: 696c 732e 6669 6e64 5f6a 736f 6e5f 666f  ils.find_json_fo
 00001740: 726d 735f 7072 6f70 6572 7479 5f61 735f  rms_property_as_
 00001750: 666c 6f61 7463 0200 0000 0000 0000 0000  floatc..........
 00001760: 0000 0200 0000 0300 0000 4300 0000 730e  ..........C...s.
 00001770: 0000 0074 0074 017c 0083 017c 0183 0253  ...t.t.|...|...S
@@ -396,17 +396,17 @@
 000018b0: 2065 7869 7374 732e 0a0a 2020 2020 2020   exists...      
 000018c0: 2020 5261 6973 6573 3a0a 2020 2020 2020    Raises:.      
 000018d0: 2020 2020 2020 5661 6c75 6545 7272 6f72        ValueError
 000018e0: 3a20 4966 2070 726f 7065 7274 7920 7661  : If property va
 000018f0: 6c75 6520 646f 6573 6e27 7420 6578 6973  lue doesn't exis
 00001900: 7420 6f72 2068 6173 2069 6e63 6f72 7265  t or has incorre
 00001910: 6374 2066 6f72 6d61 740a 2020 2020 2020  ct format.      
-00001920: 2020 2902 7212 0000 0072 2000 0000 7233    ).r....r ...r3
+00001920: 2020 2902 7214 0000 0072 2000 0000 7233    ).r....r ...r3
 00001930: 0000 0072 2500 0000 7225 0000 0072 2600  ...r%...r%...r&.
-00001940: 0000 7212 0000 00b3 0000 0073 0200 0000  ..r........s....
+00001940: 0000 7214 0000 00b1 0000 0073 0200 0000  ..r........s....
 00001950: 000f 7a46 5361 7665 5461 736b 4a73 6f6e  ..zFSaveTaskJson
 00001960: 466f 726d 7356 616c 7565 4461 7461 5265  FormsValueDataRe
 00001970: 7175 6573 7455 7469 6c73 2e67 6574 5f6a  questUtils.get_j
 00001980: 736f 6e5f 666f 726d 735f 7072 6f70 6572  son_forms_proper
 00001990: 7479 5f61 735f 6461 7465 6302 0000 0000  ty_as_datec.....
 000019a0: 0000 0000 0000 0002 0000 0003 0000 0043  ...............C
 000019b0: 0000 0073 0e00 0000 7400 7401 7c00 8301  ...s....t.t.|...
@@ -432,17 +432,17 @@
 00001af0: 6572 7479 2076 616c 7565 2069 6620 6578  erty value if ex
 00001b00: 6973 7473 2e0a 0a20 2020 2020 2020 2052  ists...        R
 00001b10: 6169 7365 733a 0a20 2020 2020 2020 2020  aises:.         
 00001b20: 2020 2056 616c 7565 4572 726f 723a 2049     ValueError: I
 00001b30: 6620 7072 6f70 6572 7479 2076 616c 7565  f property value
 00001b40: 2068 6173 2069 6e63 6f72 7265 6374 2066   has incorrect f
 00001b50: 6f72 6d61 740a 2020 2020 2020 2020 2902  ormat.        ).
-00001b60: 7209 0000 0072 2000 0000 7233 0000 0072  r....r ...r3...r
-00001b70: 2500 0000 7225 0000 0072 2600 0000 7209  %...r%...r&...r.
-00001b80: 0000 00c4 0000 0073 0200 0000 0011 7a47  .......s......zG
+00001b60: 720b 0000 0072 2000 0000 7233 0000 0072  r....r ...r3...r
+00001b70: 2500 0000 7225 0000 0072 2600 0000 720b  %...r%...r&...r.
+00001b80: 0000 00c2 0000 0073 0200 0000 0011 7a47  .......s......zG
 00001b90: 5361 7665 5461 736b 4a73 6f6e 466f 726d  SaveTaskJsonForm
 00001ba0: 7356 616c 7565 4461 7461 5265 7175 6573  sValueDataReques
 00001bb0: 7455 7469 6c73 2e66 696e 645f 6a73 6f6e  tUtils.find_json
 00001bc0: 5f66 6f72 6d73 5f70 726f 7065 7274 795f  _forms_property_
 00001bd0: 6173 5f64 6174 6563 0200 0000 0000 0000  as_datec........
 00001be0: 0000 0000 0200 0000 0300 0000 4300 0000  ............C...
 00001bf0: 730e 0000 0074 0074 017c 0083 017c 0183  s....t.t.|...|..
@@ -468,17 +468,17 @@
 00001d30: 6c75 6520 6966 2065 7869 7374 732e 0a0a  lue if exists...
 00001d40: 2020 2020 2020 2020 5261 6973 6573 3a0a          Raises:.
 00001d50: 2020 2020 2020 2020 2020 2020 5661 6c75              Valu
 00001d60: 6545 7272 6f72 3a20 4966 2070 726f 7065  eError: If prope
 00001d70: 7274 7920 7661 6c75 6520 646f 6573 6e27  rty value doesn'
 00001d80: 7420 6578 6973 7420 6f72 2068 6173 2069  t exist or has i
 00001d90: 6e63 6f72 7265 6374 2066 6f72 6d61 740a  ncorrect format.
-00001da0: 2020 2020 2020 2020 2902 7213 0000 0072          ).r....r
+00001da0: 2020 2020 2020 2020 2902 7215 0000 0072          ).r....r
 00001db0: 2000 0000 7233 0000 0072 2500 0000 7225   ...r3...r%...r%
-00001dc0: 0000 0072 2600 0000 7213 0000 00d7 0000  ...r&...r.......
+00001dc0: 0000 0072 2600 0000 7215 0000 00d5 0000  ...r&...r.......
 00001dd0: 0073 0200 0000 000f 7a4a 5361 7665 5461  .s......zJSaveTa
 00001de0: 736b 4a73 6f6e 466f 726d 7356 616c 7565  skJsonFormsValue
 00001df0: 4461 7461 5265 7175 6573 7455 7469 6c73  DataRequestUtils
 00001e00: 2e67 6574 5f6a 736f 6e5f 666f 726d 735f  .get_json_forms_
 00001e10: 7072 6f70 6572 7479 5f61 735f 6461 7465  property_as_date
 00001e20: 7469 6d65 6302 0000 0000 0000 0000 0000  timec...........
 00001e30: 0002 0000 0003 0000 0043 0000 0073 0e00  .........C...s..
@@ -504,18 +504,18 @@
 00001f70: 2020 2020 2020 5468 6520 7072 6f70 6572        The proper
 00001f80: 7479 2076 616c 7565 2069 6620 6578 6973  ty value if exis
 00001f90: 7473 2e0a 0a20 2020 2020 2020 2052 6169  ts...        Rai
 00001fa0: 7365 733a 0a20 2020 2020 2020 2020 2020  ses:.           
 00001fb0: 2056 616c 7565 4572 726f 723a 2049 6620   ValueError: If 
 00001fc0: 7072 6f70 6572 7479 2076 616c 7565 2068  property value h
 00001fd0: 6173 2069 6e63 6f72 7265 6374 2066 6f72  as incorrect for
-00001fe0: 6d61 740a 2020 2020 2020 2020 2902 720a  mat.        ).r.
+00001fe0: 6d61 740a 2020 2020 2020 2020 2902 720c  mat.        ).r.
 00001ff0: 0000 0072 2000 0000 7233 0000 0072 2500  ...r ...r3...r%.
-00002000: 0000 7225 0000 0072 2600 0000 720a 0000  ..r%...r&...r...
-00002010: 00e8 0000 0073 0200 0000 0011 7a4b 5361  .....s......zKSa
+00002000: 0000 7225 0000 0072 2600 0000 720c 0000  ..r%...r&...r...
+00002010: 00e6 0000 0073 0200 0000 0011 7a4b 5361  .....s......zKSa
 00002020: 7665 5461 736b 4a73 6f6e 466f 726d 7356  veTaskJsonFormsV
 00002030: 616c 7565 4461 7461 5265 7175 6573 7455  alueDataRequestU
 00002040: 7469 6c73 2e66 696e 645f 6a73 6f6e 5f66  tils.find_json_f
 00002050: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
 00002060: 5f64 6174 6574 696d 6563 0200 0000 0000  _datetimec......
 00002070: 0000 0000 0000 0200 0000 0300 0000 4300  ..............C.
 00002080: 0000 730e 0000 0074 0074 017c 0083 017c  ..s....t.t.|...|
@@ -542,19 +542,19 @@
 000021d0: 6973 7473 2e0a 0a20 2020 2020 2020 2052  ists...        R
 000021e0: 6169 7365 733a 0a20 2020 2020 2020 2020  aises:.         
 000021f0: 2020 2056 616c 7565 4572 726f 723a 2049     ValueError: I
 00002200: 6620 7072 6f70 6572 7479 2076 616c 7565  f property value
 00002210: 2064 6f65 736e 2774 2065 7869 7374 206f   doesn't exist o
 00002220: 7220 6861 7320 696e 636f 7272 6563 7420  r has incorrect 
 00002230: 666f 726d 6174 0a20 2020 2020 2020 2029  format.        )
-00002240: 0272 1700 0000 7220 0000 0072 3300 0000  .r....r ...r3...
+00002240: 0272 1900 0000 7220 0000 0072 3300 0000  .r....r ...r3...
 00002250: 7225 0000 0072 2500 0000 7226 0000 00da  r%...r%...r&....
 00002260: 1f67 6574 5f6a 736f 6e5f 666f 726d 735f  .get_json_forms_
 00002270: 7072 6f70 6572 7479 5f61 735f 6669 6c65  property_as_file
-00002280: fb00 0000 7302 0000 0000 117a 4653 6176  ....s......zFSav
+00002280: f900 0000 7302 0000 0000 117a 4653 6176  ....s......zFSav
 00002290: 6554 6173 6b4a 736f 6e46 6f72 6d73 5661  eTaskJsonFormsVa
 000022a0: 6c75 6544 6174 6152 6571 7565 7374 5574  lueDataRequestUt
 000022b0: 696c 732e 6765 745f 6a73 6f6e 5f66 6f72  ils.get_json_for
 000022c0: 6d73 5f70 726f 7065 7274 795f 6173 5f66  ms_property_as_f
 000022d0: 696c 6563 0200 0000 0000 0000 0000 0000  ilec............
 000022e0: 0200 0000 0300 0000 4300 0000 730e 0000  ........C...s...
 000022f0: 0074 0074 017c 0083 017c 0183 0253 0029  .t.t.|...|...S.)
@@ -580,19 +580,19 @@
 00002430: 6f70 6572 7479 2076 616c 7565 2069 6620  operty value if 
 00002440: 6578 6973 7473 2e0a 0a20 2020 2020 2020  exists...       
 00002450: 2052 6169 7365 733a 0a20 2020 2020 2020   Raises:.       
 00002460: 2020 2020 2056 616c 7565 4572 726f 723a       ValueError:
 00002470: 2049 6620 7072 6f70 6572 7479 2076 616c   If property val
 00002480: 7565 2068 6173 2069 6e63 6f72 7265 6374  ue has incorrect
 00002490: 2066 6f72 6d61 740a 2020 2020 2020 2020   format.        
-000024a0: 2902 720e 0000 0072 2000 0000 7233 0000  ).r....r ...r3..
+000024a0: 2902 7210 0000 0072 2000 0000 7233 0000  ).r....r ...r3..
 000024b0: 0072 2500 0000 7225 0000 0072 2600 0000  .r%...r%...r&...
 000024c0: da20 6669 6e64 5f6a 736f 6e5f 666f 726d  . find_json_form
 000024d0: 735f 7072 6f70 6572 7479 5f61 735f 6669  s_property_as_fi
-000024e0: 6c65 0e01 0000 7302 0000 0000 117a 4753  le....s......zGS
+000024e0: 6c65 0c01 0000 7302 0000 0000 117a 4753  le....s......zGS
 000024f0: 6176 6554 6173 6b4a 736f 6e46 6f72 6d73  aveTaskJsonForms
 00002500: 5661 6c75 6544 6174 6152 6571 7565 7374  ValueDataRequest
 00002510: 5574 696c 732e 6669 6e64 5f6a 736f 6e5f  Utils.find_json_
 00002520: 666f 726d 735f 7072 6f70 6572 7479 5f61  forms_property_a
 00002530: 735f 6669 6c65 6302 0000 0000 0000 0000  s_filec.........
 00002540: 0000 0002 0000 0003 0000 0043 0000 0073  ...........C...s
 00002550: 0e00 0000 7400 7401 7c00 8301 7c01 8302  ....t.t.|...|...
@@ -619,19 +619,19 @@
 000026a0: 6578 6973 7473 2e0a 0a20 2020 2020 2020  exists...       
 000026b0: 2052 6169 7365 733a 0a20 2020 2020 2020   Raises:.       
 000026c0: 2020 2020 2056 616c 7565 4572 726f 723a       ValueError:
 000026d0: 2049 6620 7072 6f70 6572 7479 2076 616c   If property val
 000026e0: 7565 2064 6f65 736e 2774 2065 7869 7374  ue doesn't exist
 000026f0: 206f 7220 6861 7320 696e 636f 7272 6563   or has incorrec
 00002700: 7420 666f 726d 6174 0a20 2020 2020 2020  t format.       
-00002710: 2029 0272 1800 0000 7220 0000 0072 3300   ).r....r ...r3.
+00002710: 2029 0272 1a00 0000 7220 0000 0072 3300   ).r....r ...r3.
 00002720: 0000 7225 0000 0072 2500 0000 7226 0000  ..r%...r%...r&..
 00002730: 00da 2467 6574 5f6a 736f 6e5f 666f 726d  ..$get_json_form
 00002740: 735f 7072 6f70 6572 7479 5f61 735f 7072  s_property_as_pr
-00002750: 696e 6369 7061 6c21 0100 0073 0200 0000  incipal!...s....
+00002750: 696e 6369 7061 6c1f 0100 0073 0200 0000  incipal....s....
 00002760: 0011 7a4b 5361 7665 5461 736b 4a73 6f6e  ..zKSaveTaskJson
 00002770: 466f 726d 7356 616c 7565 4461 7461 5265  FormsValueDataRe
 00002780: 7175 6573 7455 7469 6c73 2e67 6574 5f6a  questUtils.get_j
 00002790: 736f 6e5f 666f 726d 735f 7072 6f70 6572  son_forms_proper
 000027a0: 7479 5f61 735f 7072 696e 6369 7061 6c63  ty_as_principalc
 000027b0: 0200 0000 0000 0000 0000 0000 0200 0000  ................
 000027c0: 0300 0000 4300 0000 730e 0000 0074 0074  ....C...s....t.t
@@ -658,19 +658,19 @@
 00002910: 726f 7065 7274 7920 7661 6c75 6520 6966  roperty value if
 00002920: 2065 7869 7374 732e 0a0a 2020 2020 2020   exists...      
 00002930: 2020 5261 6973 6573 3a0a 2020 2020 2020    Raises:.      
 00002940: 2020 2020 2020 5661 6c75 6545 7272 6f72        ValueError
 00002950: 3a20 4966 2070 726f 7065 7274 7920 7661  : If property va
 00002960: 6c75 6520 6861 7320 696e 636f 7272 6563  lue has incorrec
 00002970: 7420 666f 726d 6174 0a20 2020 2020 2020  t format.       
-00002980: 2029 0272 0f00 0000 7220 0000 0072 3300   ).r....r ...r3.
+00002980: 2029 0272 1100 0000 7220 0000 0072 3300   ).r....r ...r3.
 00002990: 0000 7225 0000 0072 2500 0000 7226 0000  ..r%...r%...r&..
 000029a0: 00da 2566 696e 645f 6a73 6f6e 5f66 6f72  ..%find_json_for
 000029b0: 6d73 5f70 726f 7065 7274 795f 6173 5f70  ms_property_as_p
-000029c0: 7269 6e63 6970 616c 3401 0000 7302 0000  rincipal4...s...
+000029c0: 7269 6e63 6970 616c 3201 0000 7302 0000  rincipal2...s...
 000029d0: 0000 117a 4c53 6176 6554 6173 6b4a 736f  ...zLSaveTaskJso
 000029e0: 6e46 6f72 6d73 5661 6c75 6544 6174 6152  nFormsValueDataR
 000029f0: 6571 7565 7374 5574 696c 732e 6669 6e64  equestUtils.find
 00002a00: 5f6a 736f 6e5f 666f 726d 735f 7072 6f70  _json_forms_prop
 00002a10: 6572 7479 5f61 735f 7072 696e 6369 7061  erty_as_principa
 00002a20: 6c63 0200 0000 0000 0000 0000 0000 0200  lc..............
 00002a30: 0000 0300 0000 4300 0000 730e 0000 0074  ......C...s....t
@@ -697,17 +697,17 @@
 00002b80: 7374 732e 0a0a 2020 2020 2020 2020 5261  sts...        Ra
 00002b90: 6973 6573 3a0a 2020 2020 2020 2020 2020  ises:.          
 00002ba0: 2020 5661 6c75 6545 7272 6f72 3a20 4966    ValueError: If
 00002bb0: 2070 726f 7065 7274 7920 7661 6c75 6520   property value 
 00002bc0: 646f 6573 6e27 7420 6578 6973 7420 6f72  doesn't exist or
 00002bd0: 2068 6173 2069 6e63 6f72 7265 6374 2066   has incorrect f
 00002be0: 6f72 6d61 740a 2020 2020 2020 2020 2902  ormat.        ).
-00002bf0: 7219 0000 0072 2000 0000 7233 0000 0072  r....r ...r3...r
-00002c00: 2500 0000 7225 0000 0072 2600 0000 7219  %...r%...r&...r.
-00002c10: 0000 0047 0100 0073 0200 0000 000f 7a46  ...G...s......zF
+00002bf0: 721b 0000 0072 2000 0000 7233 0000 0072  r....r ...r3...r
+00002c00: 2500 0000 7225 0000 0072 2600 0000 721b  %...r%...r&...r.
+00002c10: 0000 0045 0100 0073 0200 0000 000f 7a46  ...E...s......zF
 00002c20: 5361 7665 5461 736b 4a73 6f6e 466f 726d  SaveTaskJsonForm
 00002c30: 7356 616c 7565 4461 7461 5265 7175 6573  sValueDataReques
 00002c40: 7455 7469 6c73 2e67 6574 5f6a 736f 6e5f  tUtils.get_json_
 00002c50: 666f 726d 735f 7072 6f70 6572 7479 5f61  forms_property_a
 00002c60: 735f 6c69 7374 6302 0000 0000 0000 0000  s_listc.........
 00002c70: 0000 0002 0000 0003 0000 0043 0000 0073  ...........C...s
 00002c80: 0e00 0000 7400 7401 7c00 8301 7c01 8302  ....t.t.|...|...
@@ -732,17 +732,17 @@
 00002db0: 2020 2020 5468 6520 7072 6f70 6572 7479      The property
 00002dc0: 2076 616c 7565 2069 6620 6578 6973 7473   value if exists
 00002dd0: 2e0a 0a20 2020 2020 2020 2052 6169 7365  ...        Raise
 00002de0: 733a 0a20 2020 2020 2020 2020 2020 2056  s:.            V
 00002df0: 616c 7565 4572 726f 723a 2049 6620 7072  alueError: If pr
 00002e00: 6f70 6572 7479 2076 616c 7565 2068 6173  operty value has
 00002e10: 2069 6e63 6f72 7265 6374 2066 6f72 6d61   incorrect forma
-00002e20: 740a 2020 2020 2020 2020 2902 7210 0000  t.        ).r...
+00002e20: 740a 2020 2020 2020 2020 2902 7212 0000  t.        ).r...
 00002e30: 0072 2000 0000 7233 0000 0072 2500 0000  .r ...r3...r%...
-00002e40: 7225 0000 0072 2600 0000 7210 0000 0058  r%...r&...r....X
+00002e40: 7225 0000 0072 2600 0000 7212 0000 0056  r%...r&...r....V
 00002e50: 0100 0073 0200 0000 0011 7a47 5361 7665  ...s......zGSave
 00002e60: 5461 736b 4a73 6f6e 466f 726d 7356 616c  TaskJsonFormsVal
 00002e70: 7565 4461 7461 5265 7175 6573 7455 7469  ueDataRequestUti
 00002e80: 6c73 2e66 696e 645f 6a73 6f6e 5f66 6f72  ls.find_json_for
 00002e90: 6d73 5f70 726f 7065 7274 795f 6173 5f6c  ms_property_as_l
 00002ea0: 6973 7463 0200 0000 0000 0000 0000 0000  istc............
 00002eb0: 0200 0000 0300 0000 4300 0000 730e 0000  ........C...s...
@@ -769,17 +769,17 @@
 00003000: 7869 7374 732e 0a0a 2020 2020 2020 2020  xists...        
 00003010: 5261 6973 6573 3a0a 2020 2020 2020 2020  Raises:.        
 00003020: 2020 2020 5661 6c75 6545 7272 6f72 3a20      ValueError: 
 00003030: 4966 2070 726f 7065 7274 7920 7661 6c75  If property valu
 00003040: 6520 646f 6573 6e27 7420 6578 6973 7420  e doesn't exist 
 00003050: 6f72 2068 6173 2069 6e63 6f72 7265 6374  or has incorrect
 00003060: 2066 6f72 6d61 740a 2020 2020 2020 2020   format.        
-00003070: 2902 7214 0000 0072 2000 0000 7233 0000  ).r....r ...r3..
+00003070: 2902 7216 0000 0072 2000 0000 7233 0000  ).r....r ...r3..
 00003080: 0072 2500 0000 7225 0000 0072 2600 0000  .r%...r%...r&...
-00003090: 7214 0000 006b 0100 0073 0200 0000 000f  r....k...s......
+00003090: 7216 0000 0069 0100 0073 0200 0000 000f  r....i...s......
 000030a0: 7a46 5361 7665 5461 736b 4a73 6f6e 466f  zFSaveTaskJsonFo
 000030b0: 726d 7356 616c 7565 4461 7461 5265 7175  rmsValueDataRequ
 000030c0: 6573 7455 7469 6c73 2e67 6574 5f6a 736f  estUtils.get_jso
 000030d0: 6e5f 666f 726d 735f 7072 6f70 6572 7479  n_forms_property
 000030e0: 5f61 735f 6469 6374 6302 0000 0000 0000  _as_dictc.......
 000030f0: 0000 0000 0002 0000 0003 0000 0043 0000  .............C..
 00003100: 0073 0e00 0000 7400 7401 7c00 8301 7c01  .s....t.t.|...|.
@@ -804,18 +804,18 @@
 00003230: 2020 2020 2020 5468 6520 7072 6f70 6572        The proper
 00003240: 7479 2076 616c 7565 2069 6620 6578 6973  ty value if exis
 00003250: 7473 2e0a 0a20 2020 2020 2020 2052 6169  ts...        Rai
 00003260: 7365 733a 0a20 2020 2020 2020 2020 2020  ses:.           
 00003270: 2056 616c 7565 4572 726f 723a 2049 6620   ValueError: If 
 00003280: 7072 6f70 6572 7479 2076 616c 7565 2068  property value h
 00003290: 6173 2069 6e63 6f72 7265 6374 2066 6f72  as incorrect for
-000032a0: 6d61 740a 2020 2020 2020 2020 2902 720b  mat.        ).r.
+000032a0: 6d61 740a 2020 2020 2020 2020 2902 720d  mat.        ).r.
 000032b0: 0000 0072 2000 0000 7233 0000 0072 2500  ...r ...r3...r%.
-000032c0: 0000 7225 0000 0072 2600 0000 720b 0000  ..r%...r&...r...
-000032d0: 007c 0100 0073 0200 0000 0011 7a47 5361  .|...s......zGSa
+000032c0: 0000 7225 0000 0072 2600 0000 720d 0000  ..r%...r&...r...
+000032d0: 007a 0100 0073 0200 0000 0011 7a47 5361  .z...s......zGSa
 000032e0: 7665 5461 736b 4a73 6f6e 466f 726d 7356  veTaskJsonFormsV
 000032f0: 616c 7565 4461 7461 5265 7175 6573 7455  alueDataRequestU
 00003300: 7469 6c73 2e66 696e 645f 6a73 6f6e 5f66  tils.find_json_f
 00003310: 6f72 6d73 5f70 726f 7065 7274 795f 6173  orms_property_as
 00003320: 5f64 6963 744e 2904 7222 0000 0072 3200  _dictN).r"...r2.
 00003330: 0000 da05 7661 6c75 6572 2800 0000 6303  ....valuer(...c.
 00003340: 0000 0000 0000 0000 0000 0003 0000 0004  ................
@@ -841,57 +841,57 @@
 00003480: 2020 2020 2020 2020 2020 7661 6c75 653a            value:
 00003490: 2056 616c 7565 2074 6f20 7570 6461 7465   Value to update
 000034a0: 0a0a 2020 2020 2020 2020 5261 6973 6573  ..        Raises
 000034b0: 3a0a 2020 2020 2020 2020 2020 2020 5661  :.            Va
 000034c0: 6c75 6545 7272 6f72 3a20 4966 2070 726f  lueError: If pro
 000034d0: 7065 7274 7920 7661 6c75 6520 6861 7320  perty value has 
 000034e0: 696e 636f 7272 6563 7420 666f 726d 6174  incorrect format
-000034f0: 0a20 2020 2020 2020 204e 2902 721b 0000  .        N).r...
+000034f0: 0a20 2020 2020 2020 204e 2902 721d 0000  .        N).r...
 00003500: 0072 2000 0000 2903 7222 0000 0072 3200  .r ...).r"...r2.
 00003510: 0000 7238 0000 0072 2500 0000 7225 0000  ..r8...r%...r%..
-00003520: 0072 2600 0000 721b 0000 008f 0100 0073  .r&...r........s
+00003520: 0072 2600 0000 721d 0000 008d 0100 0073  .r&...r........s
 00003530: 0200 0000 000f 7a41 5361 7665 5461 736b  ......zASaveTask
 00003540: 4a73 6f6e 466f 726d 7356 616c 7565 4461  JsonFormsValueDa
 00003550: 7461 5265 7175 6573 7455 7469 6c73 2e75  taRequestUtils.u
 00003560: 7064 6174 655f 6a73 6f6e 5f66 6f72 6d73  pdate_json_forms
 00003570: 5f70 726f 7065 7274 7929 2372 2d00 0000  _property)#r-...
 00003580: 722e 0000 0072 2f00 0000 da0c 7374 6174  r....r/.....stat
 00003590: 6963 6d65 7468 6f64 721f 0000 0072 3000  icmethodr....r0.
-000035a0: 0000 721a 0000 0072 0400 0000 7211 0000  ..r....r....r...
-000035b0: 00da 0369 6e74 7216 0000 0072 0d00 0000  ...intr....r....
-000035c0: da05 666c 6f61 7472 1500 0000 720c 0000  ..floatr....r...
-000035d0: 0072 0500 0000 7212 0000 0072 0900 0000  .r....r....r....
-000035e0: 7206 0000 0072 1300 0000 720a 0000 0072  r....r....r....r
-000035f0: 1c00 0000 7234 0000 0072 3500 0000 721d  ....r4...r5...r.
+000035a0: 0000 721c 0000 0072 0600 0000 7213 0000  ..r....r....r...
+000035b0: 00da 0369 6e74 7218 0000 0072 0f00 0000  ...intr....r....
+000035c0: da05 666c 6f61 7472 1700 0000 720e 0000  ..floatr....r...
+000035d0: 0072 0200 0000 7214 0000 0072 0b00 0000  .r....r....r....
+000035e0: 7203 0000 0072 1500 0000 720c 0000 0072  r....r....r....r
+000035f0: 0700 0000 7234 0000 0072 3500 0000 7208  ....r4...r5...r.
 00003600: 0000 0072 3600 0000 7237 0000 00da 046c  ...r6...r7.....l
-00003610: 6973 7472 1900 0000 7210 0000 00da 0464  istr....r......d
-00003620: 6963 7472 1400 0000 720b 0000 0072 0800  ictr....r....r..
-00003630: 0000 721b 0000 0072 2500 0000 7225 0000  ..r....r%...r%..
+00003610: 6973 7472 1b00 0000 7212 0000 00da 0464  istr....r......d
+00003620: 6963 7472 1600 0000 720d 0000 0072 0a00  ictr....r....r..
+00003630: 0000 721d 0000 0072 2500 0000 7225 0000  ..r....r%...r%..
 00003640: 0072 2500 0000 7226 0000 0072 3100 0000  .r%...r&...r1...
-00003650: 4600 0000 7396 0000 0008 0102 0114 1002  F...s...........
+00003650: 4400 0000 7396 0000 0008 0102 0114 1002  D...s...........
 00003660: 0202 0002 0106 fe0e 1202 0114 1002 0202  ................
 00003670: 0002 0106 fe0e 1202 0114 1002 0202 0002  ................
 00003680: 0106 fe0e 1202 0114 1002 0202 0002 0106  ................
 00003690: fe0e 1202 0114 1002 0202 0002 0106 fe0e  ................
 000036a0: 1202 0202 0002 0102 fe0e 1202 0202 0002  ................
 000036b0: 0106 fe0e 1202 0202 0002 0102 fe0e 1202  ................
 000036c0: 0202 0002 0106 fe0e 1202 0114 1002 0202  ................
 000036d0: 0002 0106 fe0e 1202 0114 1002 0202 0002  ................
 000036e0: 0106 fe0e 1202 0202 0002 0006 0102 fe72  ...............r
-000036f0: 3100 0000 4e29 23da 0674 7970 696e 6772  1...N)#..typingr
-00003700: 0200 0000 7203 0000 0072 0400 0000 7206  ....r....r....r.
-00003710: 0000 0072 0500 0000 5a1c 6b75 666c 6f77  ...r....Z.kuflow
-00003720: 5f72 6573 742e 7574 696c 732e 6a73 6f6e  _rest.utils.json
-00003730: 5f66 6f72 6d73 7207 0000 0072 0800 0000  _formsr....r....
-00003740: 7209 0000 0072 0a00 0000 720b 0000 0072  r....r....r....r
-00003750: 0c00 0000 720d 0000 0072 0e00 0000 720f  ....r....r....r.
-00003760: 0000 0072 1000 0000 7211 0000 0072 1200  ...r....r....r..
-00003770: 0000 7213 0000 0072 1400 0000 7215 0000  ..r....r....r...
-00003780: 0072 1600 0000 7217 0000 0072 1800 0000  .r....r....r....
-00003790: 7219 0000 0072 1a00 0000 721b 0000 00da  r....r....r.....
-000037a0: 126b 7566 6c6f 775f 7265 7374 2e6d 6f64  .kuflow_rest.mod
-000037b0: 656c 7372 1c00 0000 721d 0000 00da 066d  elsr....r......m
+000036f0: 3100 0000 4e29 2372 0300 0000 7202 0000  1...N)#r....r...
+00003700: 00da 0674 7970 696e 6772 0400 0000 7205  ...typingr....r.
+00003710: 0000 0072 0600 0000 da12 6b75 666c 6f77  ...r......kuflow
+00003720: 5f72 6573 742e 6d6f 6465 6c73 7207 0000  _rest.modelsr...
+00003730: 0072 0800 0000 5a1c 6b75 666c 6f77 5f72  .r....Z.kuflow_r
+00003740: 6573 742e 7574 696c 732e 6a73 6f6e 5f66  est.utils.json_f
+00003750: 6f72 6d73 7209 0000 0072 0a00 0000 720b  ormsr....r....r.
+00003760: 0000 0072 0c00 0000 720d 0000 0072 0e00  ...r....r....r..
+00003770: 0000 720f 0000 0072 1000 0000 7211 0000  ..r....r....r...
+00003780: 0072 1200 0000 7213 0000 0072 1400 0000  .r....r....r....
+00003790: 7215 0000 0072 1600 0000 7217 0000 0072  r....r....r....r
+000037a0: 1800 0000 7219 0000 0072 1a00 0000 721b  ....r....r....r.
+000037b0: 0000 0072 1c00 0000 721d 0000 00da 066d  ...r....r......m
 000037c0: 6f64 656c 7372 1f00 0000 7220 0000 0072  odelsr....r ...r
 000037d0: 3100 0000 7225 0000 0072 2500 0000 7225  1...r%...r%...r%
 000037e0: 0000 0072 2600 0000 da08 3c6d 6f64 756c  ...r&.....<modul
-000037f0: 653e 1a00 0000 730c 0000 0014 0110 025c  e>....s........\
-00003800: 1710 040c 0310 0b                        .......
+000037f0: 653e 1a00 0000 730c 0000 0010 0114 0210  e>....s.........
+00003800: 015c 180c 0310 0b                        .\.....
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/_save_process_element_utils.py` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/_save_process_element_utils.py`

 * *Files 1% similar despite different names*

```diff
@@ -19,45 +19,42 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import List, Optional
 from datetime import date
+from typing import List, Optional
 
 from kuflow_rest.models import ProcessElementValue
-from kuflow_rest.utils import (
-    ProcessElementValueAccessor,
-    ElementValueUnion,
-    ElementValueSimpleType,
-)
+from kuflow_rest.utils import ElementValueSimpleType, ElementValueUnion, ProcessElementValueAccessor
 from kuflow_rest.utils.element_values import (
-    get_element_value_valid,
-    get_element_value_valid_at,
-    set_element_value_valid,
-    set_element_value_valid_at,
-    set_element_value,
-    set_element_value_list,
     add_element_value,
     add_element_value_list,
-    get_element_value_as_str,
-    find_element_value_as_str,
-    get_element_value_as_str_list,
-    get_element_value_as_float,
+    find_element_value_as_date,
+    find_element_value_as_dict,
     find_element_value_as_float,
-    get_element_value_as_float_list,
+    find_element_value_as_str,
     get_element_value_as_date,
-    find_element_value_as_date,
     get_element_value_as_date_list,
     get_element_value_as_dict,
-    find_element_value_as_dict,
     get_element_value_as_dict_list,
+    get_element_value_as_float,
+    get_element_value_as_float_list,
+    get_element_value_as_str,
+    get_element_value_as_str_list,
+    get_element_value_valid,
+    get_element_value_valid_at,
+    set_element_value,
+    set_element_value_list,
+    set_element_value_valid,
+    set_element_value_valid_at,
 )
+
 from ..models import SaveProcessElementRequest
 
 
 class CurrentAccessor(ProcessElementValueAccessor):
     def __init__(self, request: SaveProcessElementRequest):
         self.request = request
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/_save_task_element_utils.py` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/_save_task_element_utils.py`

 * *Files 1% similar despite different names*

```diff
@@ -19,55 +19,48 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import List, Optional
 from datetime import date
+from typing import List, Optional
 
-from kuflow_rest.models import (
-    TaskElementValue,
-    TaskElementValueDocumentItem,
-    TaskElementValuePrincipalItem,
-)
-from kuflow_rest.utils import (
-    TaskElementValueAccessor,
-    ElementValueUnion,
-    ElementValueSimpleType,
-)
+from kuflow_rest.models import TaskElementValue, TaskElementValueDocumentItem, TaskElementValuePrincipalItem
+from kuflow_rest.utils import ElementValueSimpleType, ElementValueUnion, TaskElementValueAccessor
 from kuflow_rest.utils.element_values import (
-    get_element_value_valid,
-    get_element_value_valid_at,
-    set_element_value_valid,
-    set_element_value_valid_at,
-    set_element_value,
-    set_element_value_list,
     add_element_value,
     add_element_value_list,
-    get_element_value_as_str,
-    find_element_value_as_str,
-    get_element_value_as_str_list,
-    get_element_value_as_float,
+    find_element_value_as_date,
+    find_element_value_as_dict,
+    find_element_value_as_document,
     find_element_value_as_float,
-    get_element_value_as_float_list,
+    find_element_value_as_principal,
+    find_element_value_as_str,
     get_element_value_as_date,
-    find_element_value_as_date,
     get_element_value_as_date_list,
     get_element_value_as_dict,
-    find_element_value_as_dict,
     get_element_value_as_dict_list,
     get_element_value_as_document,
-    find_element_value_as_document,
     get_element_value_as_document_list,
+    get_element_value_as_float,
+    get_element_value_as_float_list,
     get_element_value_as_principal,
-    find_element_value_as_principal,
     get_element_value_as_principal_list,
+    get_element_value_as_str,
+    get_element_value_as_str_list,
+    get_element_value_valid,
+    get_element_value_valid_at,
+    set_element_value,
+    set_element_value_list,
+    set_element_value_valid,
+    set_element_value_valid_at,
 )
+
 from ..models import SaveTaskElementRequest
 
 
 class CurrentAccessor(TaskElementValueAccessor):
     def __init__(self, request: SaveTaskElementRequest):
         self.request = request
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/kuflow_temporal_activity_kuflow/utils/_save_task_json_forms_value_data_request_utils.py` & `kuflow_temporal_activity_kuflow-0.8.0/kuflow_temporal_activity_kuflow/utils/_save_task_json_forms_value_data_request_utils.py`

 * *Files 1% similar despite different names*

```diff
@@ -19,17 +19,18 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-from typing import Any, Dict, Optional
 from datetime import date, datetime
+from typing import Any, Dict, Optional
 
+from kuflow_rest.models import JsonFormsFile, JsonFormsPrincipal
 from kuflow_rest.utils.json_forms import (
     JsonFormDataAccessor,
     JsonFormsSimpleType,
     find_json_forms_property_as_date,
     find_json_forms_property_as_datetime,
     find_json_forms_property_as_dict,
     find_json_forms_property_as_float,
@@ -45,18 +46,15 @@
     get_json_forms_property_as_int,
     get_json_forms_property_as_json_forms_file,
     get_json_forms_property_as_json_forms_principal,
     get_json_forms_property_as_list,
     get_json_forms_property_as_str,
     update_json_forms_property,
 )
-from kuflow_rest.models import (
-    JsonFormsFile,
-    JsonFormsPrincipal,
-)
+
 from ..models import SaveTaskJsonFormsValueDataRequest
 
 
 class CurrentJsonFormDataAccessor(JsonFormDataAccessor):
     def __init__(self, command: SaveTaskJsonFormsValueDataRequest):
         self.command = command
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/pyproject.toml` & `kuflow_temporal_activity_kuflow-0.8.0/pyproject.toml`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "kuflow-temporal-activity-kuflow"
-version = "0.7.1"
+version = "0.8.0"
 description = "KuFlow SDK :: Temporal.io activities to interact with KuFlow"
 license = "MIT"
 authors = ["KuFlow S.L. <kuflow@kuflow.com>"]
 homepage = "https://kuflow.com/"
 documentation = "https://docs.kuflow.com/"
 repository = "https://github.com/kuflow/kuflow-sdk-python"
 readme = "README.md"
@@ -13,15 +13,15 @@
 
 [build-system]
 requires = ["poetry_core>=1.0.0"]
 build-backend = "poetry.core.masonry.api"
 
 [tool.poetry.dependencies]
 python = "^3.8"
-kuflow-temporal-common = "^0.7.1"
+kuflow-temporal-common = "^0.8.0"
 
 [tool.poetry.group.dev.dependencies]
 mypy = "^1.3.0"
 flake8 = "^5.0.4"
 black = "^23.3.0"
 pytest = "^7.3.1"
 pyyaml = "^6.0"
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/setup.py` & `kuflow_temporal_activity_kuflow-0.8.0/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -6,19 +6,19 @@
  'kuflow_temporal_activity_kuflow.models',
  'kuflow_temporal_activity_kuflow.utils']
 
 package_data = \
 {'': ['*']}
 
 install_requires = \
-['kuflow-temporal-common>=0.7.1,<0.8.0']
+['kuflow-temporal-common>=0.8.0,<0.9.0']
 
 setup_kwargs = {
     'name': 'kuflow-temporal-activity-kuflow',
-    'version': '0.7.1',
+    'version': '0.8.0',
     'description': 'KuFlow SDK :: Temporal.io activities to interact with KuFlow',
     'long_description': '[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/kuflow/kuflow-sdk-python/blob/master/LICENSE)\n[![Python](https://img.shields.io/pypi/pyversions/kuflow-temporal-activity-kuflow.svg)](https://pypi.org/project/kuflow-temporal-activity-kuflow)\n[![PyPI](https://img.shields.io/pypi/v/kuflow-temporal-activity-kuflow.svg)](https://pypi.org/project/kuflow-temporal-activity-kuflow)\n\n# KuFlow Temporal Activities KuFlow\n\nTemporal.io activities to interact with KuFlow\n\n## Documentation\n\nMore detailed docs are available in the [documentation pages](https://docs.kuflow.com/developers/).\n\n## Contributing\n\nWe are happy to receive your help and comments, together we will dance a wonderful KuFlow. Please review our [contribution guide](CONTRIBUTING.md).\n\n## License\n\n[MIT License](https://github.com/kuflow/kuflow-sdk-python/blob/master/LICENSE)\n',
     'author': 'KuFlow S.L.',
     'author_email': 'kuflow@kuflow.com',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'https://kuflow.com/',
```

### Comparing `kuflow_temporal_activity_kuflow-0.7.1/PKG-INFO` & `kuflow_temporal_activity_kuflow-0.8.0/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,23 +1,23 @@
 Metadata-Version: 2.1
 Name: kuflow-temporal-activity-kuflow
-Version: 0.7.1
+Version: 0.8.0
 Summary: KuFlow SDK :: Temporal.io activities to interact with KuFlow
 Home-page: https://kuflow.com/
 License: MIT
 Author: KuFlow S.L.
 Author-email: kuflow@kuflow.com
 Requires-Python: >=3.8,<4.0
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
-Requires-Dist: kuflow-temporal-common (>=0.7.1,<0.8.0)
+Requires-Dist: kuflow-temporal-common (>=0.8.0,<0.9.0)
 Project-URL: Documentation, https://docs.kuflow.com/
 Project-URL: Repository, https://github.com/kuflow/kuflow-sdk-python
 Description-Content-Type: text/markdown
 
 [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/kuflow/kuflow-sdk-python/blob/master/LICENSE)
 [![Python](https://img.shields.io/pypi/pyversions/kuflow-temporal-activity-kuflow.svg)](https://pypi.org/project/kuflow-temporal-activity-kuflow)
 [![PyPI](https://img.shields.io/pypi/v/kuflow-temporal-activity-kuflow.svg)](https://pypi.org/project/kuflow-temporal-activity-kuflow)
```

