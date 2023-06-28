# Comparing `tmp/kuflow_temporal_common-0.7.1.tar.gz` & `tmp/kuflow_temporal_common-0.8.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kuflow_temporal_common-0.7.1.tar", max compression
+gzip compressed data, was "kuflow_temporal_common-0.8.0.tar", max compression
```

## Comparing `kuflow_temporal_common-0.7.1.tar` & `kuflow_temporal_common-0.8.0.tar`

### file list

```diff
@@ -1,11 +1,11 @@
--rw-r--r--   0        0        0      789 2023-06-20 07:20:29.819020 kuflow_temporal_common-0.7.1/README.md
--rw-r--r--   0        0        0        6 2023-06-20 07:20:29.819020 kuflow_temporal_common-0.7.1/VERSION
--rw-r--r--   0        0        0     1143 2023-06-20 07:20:29.819020 kuflow_temporal_common-0.7.1/kuflow_temporal_common/__init__.py
--rw-r--r--   0        0        0     2467 2023-06-20 07:20:29.819020 kuflow_temporal_common-0.7.1/kuflow_temporal_common/activity_utils.py
--rw-r--r--   0        0        0     5197 2023-06-20 07:20:29.819020 kuflow_temporal_common-0.7.1/kuflow_temporal_common/authentication.py
--rw-r--r--   0        0        0    16326 2023-06-20 07:20:29.819020 kuflow_temporal_common-0.7.1/kuflow_temporal_common/connection.py
--rw-r--r--   0        0        0     2722 2023-06-20 07:20:29.819020 kuflow_temporal_common-0.7.1/kuflow_temporal_common/converter.py
--rw-r--r--   0        0        0     1849 2023-06-20 07:20:29.819020 kuflow_temporal_common-0.7.1/kuflow_temporal_common/exceptions.py
--rw-r--r--   0        0        0     1010 2023-06-20 07:21:47.225952 kuflow_temporal_common-0.7.1/pyproject.toml
--rw-r--r--   0        0        0     1555 1970-01-01 00:00:00.000000 kuflow_temporal_common-0.7.1/setup.py
--rw-r--r--   0        0        0     1653 1970-01-01 00:00:00.000000 kuflow_temporal_common-0.7.1/PKG-INFO
+-rw-r--r--   0        0        0      789 2023-06-28 08:18:27.332639 kuflow_temporal_common-0.8.0/README.md
+-rw-r--r--   0        0        0        6 2023-06-28 08:18:27.332639 kuflow_temporal_common-0.8.0/VERSION
+-rw-r--r--   0        0        0     1143 2023-06-28 08:18:27.332639 kuflow_temporal_common-0.8.0/kuflow_temporal_common/__init__.py
+-rw-r--r--   0        0        0     2467 2023-06-28 08:18:27.332639 kuflow_temporal_common-0.8.0/kuflow_temporal_common/activity_utils.py
+-rw-r--r--   0        0        0     5197 2023-06-28 08:18:27.332639 kuflow_temporal_common-0.8.0/kuflow_temporal_common/authentication.py
+-rw-r--r--   0        0        0    16233 2023-06-28 08:18:27.332639 kuflow_temporal_common-0.8.0/kuflow_temporal_common/connection.py
+-rw-r--r--   0        0        0     2722 2023-06-28 08:18:27.332639 kuflow_temporal_common-0.8.0/kuflow_temporal_common/converter.py
+-rw-r--r--   0        0        0     1841 2023-06-28 08:18:27.332639 kuflow_temporal_common-0.8.0/kuflow_temporal_common/exceptions.py
+-rw-r--r--   0        0        0     1010 2023-06-28 08:19:45.887867 kuflow_temporal_common-0.8.0/pyproject.toml
+-rw-r--r--   0        0        0     1555 1970-01-01 00:00:00.000000 kuflow_temporal_common-0.8.0/setup.py
+-rw-r--r--   0        0        0     1653 1970-01-01 00:00:00.000000 kuflow_temporal_common-0.8.0/PKG-INFO
```

### Comparing `kuflow_temporal_common-0.7.1/README.md` & `kuflow_temporal_common-0.8.0/README.md`

 * *Files identical despite different names*

### Comparing `kuflow_temporal_common-0.7.1/kuflow_temporal_common/__init__.py` & `kuflow_temporal_common-0.8.0/kuflow_temporal_common/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -19,8 +19,8 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-__version__ = "0.7.1"
+__version__ = "0.8.0"
```

### Comparing `kuflow_temporal_common-0.7.1/kuflow_temporal_common/activity_utils.py` & `kuflow_temporal_common-0.8.0/kuflow_temporal_common/activity_utils.py`

 * *Files identical despite different names*

### Comparing `kuflow_temporal_common-0.7.1/kuflow_temporal_common/authentication.py` & `kuflow_temporal_common-0.8.0/kuflow_temporal_common/authentication.py`

 * *Files 1% similar despite different names*

```diff
@@ -19,18 +19,18 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-import datetime
 import asyncio
+import datetime
 import logging
-from typing import Optional, Mapping
+from typing import Mapping, Optional
 
 from temporalio.client import Client
 
 from kuflow_rest import KuFlowRestClient, models
 
 logger = logging.getLogger(__name__)
```

### Comparing `kuflow_temporal_common-0.7.1/kuflow_temporal_common/connection.py` & `kuflow_temporal_common-0.8.0/kuflow_temporal_common/connection.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,51 +19,33 @@
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
-import dataclasses
 import concurrent.futures
+import dataclasses
 from dataclasses import dataclass
 from datetime import timedelta
-from typing import (
-    Awaitable,
-    Callable,
-    Dict,
-    List,
-    Mapping,
-    Optional,
-    Sequence,
-    Set,
-    Type,
-    Union,
-)
+from typing import Awaitable, Callable, Dict, List, Mapping, Optional, Sequence, Set, Type, Union
 
-import temporalio.converter
+import temporalio.activity
 import temporalio.common
+import temporalio.converter
 import temporalio.runtime
 import temporalio.workflow
-import temporalio.activity
-
-from temporalio.worker import Worker
-from temporalio.client import Client, Interceptor, TLSConfig, RetryConfig
-from temporalio.worker import (
-    SharedStateManager,
-    UnsandboxedWorkflowRunner,
-    WorkflowRunner,
-)
+from temporalio.client import Client, Interceptor, RetryConfig, TLSConfig
+from temporalio.worker import SharedStateManager, UnsandboxedWorkflowRunner, Worker, WorkflowRunner
 from temporalio.worker.workflow_sandbox import SandboxedWorkflowRunner
 
+from kuflow_rest import KuFlowRestClient
 from kuflow_temporal_common.authentication import KuFlowAuthorizationTokenProvider
 from kuflow_temporal_common.converter import CompositeEncodingPayloadConverter
 
-from kuflow_rest import KuFlowRestClient
-
 
 @dataclass
 class KuFlowConfig:
     """KuFlow configuration."""
 
     rest_client: KuFlowRestClient
     """TODO Root CA to validate the server certificate against."""
```

### Comparing `kuflow_temporal_common-0.7.1/kuflow_temporal_common/converter.py` & `kuflow_temporal_common-0.8.0/kuflow_temporal_common/converter.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-from typing import Any, Optional, Type, List, Union
+from typing import Any, List, Optional, Type, Union
 
 from temporalio.api.common.v1 import Payload
 from temporalio.converter import EncodingPayloadConverter
 from temporalio.types import CallableType, ClassType
 
 
 def register(
```

### Comparing `kuflow_temporal_common-0.7.1/kuflow_temporal_common/exceptions.py` & `kuflow_temporal_common-0.8.0/kuflow_temporal_common/exceptions.py`

 * *Files 1% similar despite different names*

```diff
@@ -20,17 +20,16 @@
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 #
 
 from enum import Enum
-from azure.core.exceptions import (
-    HttpResponseError,
-)
+
+from azure.core.exceptions import HttpResponseError
 from temporalio.exceptions import ApplicationError
 
 
 class KuFlowFailureType(str, Enum):
     ACTIVITIES_FAILURE = "KuFlowActivities.Failure"
 
     ACTIVITIES_REST_FAILURE = "KuFlowActivities.RestFailure"
```

### Comparing `kuflow_temporal_common-0.7.1/pyproject.toml` & `kuflow_temporal_common-0.8.0/pyproject.toml`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "kuflow-temporal-common"
-version = "0.7.1"
+version = "0.8.0"
 description = "KuFlow utilities to use Temporal.io"
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
-kuflow-rest = "^0.7.1"
+kuflow-rest = "^0.8.0"
 azure-core = "^1.26.4"
 isodate = "^0.6.1"
 temporalio = "1.2.0"
 
 [tool.poetry.group.dev.dependencies]
 mypy = "^1.3.0"
 flake8 = "^5.0.4"
```

### Comparing `kuflow_temporal_common-0.7.1/setup.py` & `kuflow_temporal_common-0.8.0/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -6,20 +6,20 @@
 
 package_data = \
 {'': ['*']}
 
 install_requires = \
 ['azure-core>=1.26.4,<2.0.0',
  'isodate>=0.6.1,<0.7.0',
- 'kuflow-rest>=0.7.1,<0.8.0',
+ 'kuflow-rest>=0.8.0,<0.9.0',
  'temporalio==1.2.0']
 
 setup_kwargs = {
     'name': 'kuflow-temporal-common',
-    'version': '0.7.1',
+    'version': '0.8.0',
     'description': 'KuFlow utilities to use Temporal.io',
     'long_description': '[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/kuflow/kuflow-sdk-python/blob/master/LICENSE)\n[![Python](https://img.shields.io/pypi/pyversions/kuflow-temporal-common.svg)](https://pypi.org/project/kuflow-temporal-common)\n[![PyPI](https://img.shields.io/pypi/v/kuflow-temporal-common.svg)](https://pypi.org/project/kuflow-temporal-common)\n\n# KuFlow Temporal Common\n\nTODO\n\n## Documentation\n\nMore detailed docs are available in the [documentation pages](https://docs.kuflow.com/developers/).\n\n## Contributing\n\nWe are happy to receive your help and comments, together we will dance a wonderful KuFlow. Please review our [contribution guide](CONTRIBUTING.md).\n\n## License\n\n[MIT License](https://github.com/kuflow/kuflow-sdk-python/blob/master/LICENSE)\n',
     'author': 'KuFlow S.L.',
     'author_email': 'kuflow@kuflow.com',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'https://kuflow.com/',
```

### Comparing `kuflow_temporal_common-0.7.1/PKG-INFO` & `kuflow_temporal_common-0.8.0/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,25 +1,25 @@
 Metadata-Version: 2.1
 Name: kuflow-temporal-common
-Version: 0.7.1
+Version: 0.8.0
 Summary: KuFlow utilities to use Temporal.io
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
 Requires-Dist: azure-core (>=1.26.4,<2.0.0)
 Requires-Dist: isodate (>=0.6.1,<0.7.0)
-Requires-Dist: kuflow-rest (>=0.7.1,<0.8.0)
+Requires-Dist: kuflow-rest (>=0.8.0,<0.9.0)
 Requires-Dist: temporalio (==1.2.0)
 Project-URL: Documentation, https://docs.kuflow.com/
 Project-URL: Repository, https://github.com/kuflow/kuflow-sdk-python
 Description-Content-Type: text/markdown
 
 [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/kuflow/kuflow-sdk-python/blob/master/LICENSE)
 [![Python](https://img.shields.io/pypi/pyversions/kuflow-temporal-common.svg)](https://pypi.org/project/kuflow-temporal-common)
```

