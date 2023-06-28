# Comparing `tmp/cerebrium-1.1.3.tar.gz` & `tmp/cerebrium-1.1.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cerebrium-1.1.3.tar", max compression
+gzip compressed data, was "cerebrium-1.1.4.tar", max compression
```

## Comparing `cerebrium-1.1.3.tar` & `cerebrium-1.1.4.tar`

### file list

```diff
@@ -1,21 +1,32 @@
--rw-r--r--   0        0        0    34594 2023-06-22 13:13:58.786651 cerebrium-1.1.3/LICENSE
--rw-r--r--   0        0        0     3473 2023-06-22 13:13:58.786651 cerebrium-1.1.3/README.md
--rw-r--r--   0        0        0      330 2023-06-22 13:18:23.835744 cerebrium-1.1.3/cerebrium/__init__.py
--rwxr-xr-x   0        0        0    10167 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/cli.py
--rw-r--r--   0        0        0    31667 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/conduit.py
--rw-r--r--   0        0        0     5049 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/core.py
--rw-r--r--   0        0        0     2476 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/errors.py
--rw-r--r--   0        0        0    11299 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/flow.py
--rw-r--r--   0        0        0     2807 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/logging/arize.py
--rw-r--r--   0        0        0      705 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/logging/base.py
--rw-r--r--   0        0        0     3855 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/logging/censius.py
--rw-r--r--   0        0        0      911 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/models/base.py
--rw-r--r--   0        0        0      446 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/models/hf_pipeline.py
--rw-r--r--   0        0        0      418 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/models/onnx.py
--rw-r--r--   0        0        0     1116 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/models/sklearn.py
--rw-r--r--   0        0        0      244 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/models/spacy.py
--rw-r--r--   0        0        0      342 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/models/torch.py
--rw-r--r--   0        0        0     8540 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/requests.py
--rw-r--r--   0        0        0      465 2023-06-22 13:13:58.786651 cerebrium-1.1.3/cerebrium/utils.py
--rw-r--r--   0        0        0     2546 2023-06-22 13:18:23.831744 cerebrium-1.1.3/pyproject.toml
--rw-r--r--   0        0        0     5617 1970-01-01 00:00:00.000000 cerebrium-1.1.3/PKG-INFO
+-rw-r--r--   0        0        0    34594 2023-06-28 15:08:02.800964 cerebrium-1.1.4/LICENSE
+-rw-r--r--   0        0        0     3473 2023-06-28 15:08:02.800964 cerebrium-1.1.4/README.md
+-rw-r--r--   0        0        0      381 2023-06-28 15:12:01.841640 cerebrium-1.1.4/cerebrium/__init__.py
+-rwxr-xr-x   0        0        0    21379 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/cli.py
+-rw-r--r--   0        0        0    31606 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/conduit.py
+-rw-r--r--   0        0        0     5050 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/core.py
+-rw-r--r--   0        0        0     2476 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/errors.py
+-rw-r--r--   0        0        0    11300 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/flow.py
+-rw-r--r--   0        0        0     2777 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/logging/arize.py
+-rw-r--r--   0        0        0      705 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/logging/base.py
+-rw-r--r--   0        0        0     3798 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/logging/censius.py
+-rw-r--r--   0        0        0      914 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/models/base.py
+-rw-r--r--   0        0        0      447 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/models/hf_pipeline.py
+-rw-r--r--   0        0        0      419 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/models/onnx.py
+-rw-r--r--   0        0        0     1118 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/models/sklearn.py
+-rw-r--r--   0        0        0      150 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/models/spacy.py
+-rw-r--r--   0        0        0      344 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/models/torch.py
+-rw-r--r--   0        0        0     8753 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/requests.py
+-rw-r--r--   0        0        0     5297 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/trainer/README.md
+-rw-r--r--   0        0        0        0 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/trainer/__init__.py
+-rw-r--r--   0        0        0     9013 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/trainer/fine_tuner.py
+-rw-r--r--   0        0        0     1520 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/trainer/finetuning_model.py
+-rw-r--r--   0        0        0        0 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/trainer/userDataset/__init__.py
+-rw-r--r--   0        0        0     2703 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/trainer/userDataset/base_dataset.py
+-rw-r--r--   0        0        0     3750 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/trainer/userDataset/data_validator.py
+-rw-r--r--   0        0        0     2007 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/trainer/userDataset/templates/README.md
+-rw-r--r--   0        0        0      530 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/trainer/userDataset/templates/alpaca.json
+-rw-r--r--   0        0        0      269 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/trainer/userDataset/templates/alpaca_short.json
+-rw-r--r--   0        0        0      597 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/trainer/userDataset/templates/vigogne.json
+-rw-r--r--   0        0        0      466 2023-06-28 15:08:02.800964 cerebrium-1.1.4/cerebrium/utils.py
+-rw-r--r--   0        0        0     2611 2023-06-28 15:12:01.837640 cerebrium-1.1.4/pyproject.toml
+-rw-r--r--   0        0        0     5617 1970-01-01 00:00:00.000000 cerebrium-1.1.4/PKG-INFO
```

### Comparing `cerebrium-1.1.3/LICENSE` & `cerebrium-1.1.4/LICENSE`

 * *Files identical despite different names*

### Comparing `cerebrium-1.1.3/README.md` & `cerebrium-1.1.4/README.md`

 * *Files identical despite different names*

### Comparing `cerebrium-1.1.3/cerebrium/conduit.py` & `cerebrium-1.1.4/cerebrium/conduit.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,31 +1,31 @@
-from cloudpickle import load as pickle_load
-from torch.jit import load as torchscript_load  # type: ignore
-from tqdm import tqdm
-from tqdm.utils import CallbackIOWrapper
+import enum
+import json
 import os
 import re
 import tempfile
 import zipfile
-import requests
-import json
-import enum
 from copy import deepcopy
-from typing import Any, Dict, Literal, Union
+from inspect import getsource, signature
 from types import FunctionType
+from typing import Any, Dict, Literal, Union
 
-from torch.nn import Module as TorchModule
-from torch.cuda import is_available
+import requests
+from cloudpickle import load as pickle_load
 from numpy import atleast_2d, ndarray
-from inspect import getsource, signature
+from torch.cuda import is_available
+from torch.jit import load as torchscript_load  # type: ignore
+from torch.nn import Module as TorchModule
+from tqdm import tqdm
+from tqdm.utils import CallbackIOWrapper
 
 from cerebrium import __version__
 from cerebrium.flow import CerebriumFlow, _check_flow_type, _flow_string
-from cerebrium.models.base import ModelType
 from cerebrium.logging.base import LoggingPlatform
+from cerebrium.models.base import ModelType
 from cerebrium.requests import _cerebrium_request, _poll_deployment_status
 
 REGEX_NAME_PATTERN = "^[a-z0-9-]*$"
 API_KEY = None
 
 
 def _set_api_key(api_key):
@@ -430,16 +430,14 @@
                     config["targets"],
                     config["platform_args"],
                     config["log_ms"],
                 )
             elif platform == "Arize":
                 from cerebrium.logging.arize import ArizeLogger
                 from arize.utils.types import (
-                    ModelTypes,
-                    Metrics,
                     Schema,
                     Embedding,
                 )
 
                 # If there are processors, recreate the model type, metrics, schema, and embedding objects
                 if self._processors:
                     from pandas import Series
```

### Comparing `cerebrium-1.1.3/cerebrium/core.py` & `cerebrium-1.1.4/cerebrium/core.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,21 +1,22 @@
-from cerebrium.flow import CerebriumFlow
-from cerebrium.conduit import Conduit
-from cerebrium.utils import _convert_input_data
-
-import requests
 import json
-from typing import Union, List
-import boto3
 import os
+from typing import Union, List
 from uuid import uuid4
+
+import boto3
+import requests
 import yaml
 from numpy import ndarray
 from torch import Tensor
+
+from cerebrium.conduit import Conduit
+from cerebrium.flow import CerebriumFlow
 from cerebrium.requests import _cerebrium_request, ENV
+from cerebrium.utils import _convert_input_data
 
 IS_SERVER = os.getenv("IS_SERVER", "false")
 _objects = {}
 if os.path.exists("secrets.json"):
     with open("secrets.json") as f:
         SECRETS = json.load(f)
 elif os.path.exists("secrets.yaml"):
```

### Comparing `cerebrium-1.1.3/cerebrium/errors.py` & `cerebrium-1.1.4/cerebrium/errors.py`

 * *Files identical despite different names*

### Comparing `cerebrium-1.1.3/cerebrium/flow.py` & `cerebrium-1.1.4/cerebrium/flow.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,12 @@
-from typing import Tuple, List, Dict, Literal, Union
-from types import FunctionType
 from inspect import getsource
 from pathlib import Path
+from types import FunctionType
+from typing import Tuple, List, Dict, Literal, Union
+
 from cerebrium.models.base import ModelType
 
 CerebriumModel = Tuple[
     ModelType,
     Union[str, dict],
     Union[Dict[Union[Literal["pre"], Literal["post"]], FunctionType], None],
 ]
```

### Comparing `cerebrium-1.1.3/cerebrium/logging/arize.py` & `cerebrium-1.1.4/cerebrium/logging/arize.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,14 +1,14 @@
-from cerebrium.logging.base import ConduitLogger
-from arize.pandas.logger import Client
-from arize.utils.types import ModelTypes, Environments, Metrics
-from tenacity import retry, stop_after_attempt, wait_fixed
-from time import time
 import numpy as np
 import pandas as pd
+from arize.pandas.logger import Client
+from arize.utils.types import ModelTypes, Environments
+from tenacity import retry, stop_after_attempt, wait_fixed
+
+from cerebrium.logging.base import ConduitLogger
 
 
 class ArizeLogger(ConduitLogger):
     def __init__(
         self,
         platform_authentication: dict,
         platform_model_id: str,
```

### Comparing `cerebrium-1.1.3/cerebrium/logging/base.py` & `cerebrium-1.1.4/cerebrium/logging/base.py`

 * *Ordering differences only*

 * *Files 1% similar despite different names*

```diff
@@ -1,9 +1,9 @@
-from enum import Enum
 from abc import ABC, abstractmethod
+from enum import Enum
 
 
 class LoggingPlatform(Enum):
     CENSIUS = "Censius"
     ARIZE = "Arize"
```

### Comparing `cerebrium-1.1.3/cerebrium/logging/censius.py` & `cerebrium-1.1.4/cerebrium/logging/censius.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,14 +1,15 @@
-from cerebrium.logging.base import ConduitLogger
-from censius import CensiusClient, ModelType
-from tenacity import retry, stop_after_attempt, wait_fixed
 from time import time
+
 import numpy as np
 from tenacity import retry, stop_after_attempt, wait_fixed
 
+from censius import CensiusClient, ModelType
+from cerebrium.logging.base import ConduitLogger
+
 
 class CensiusLogger(ConduitLogger):
     def __init__(
         self,
         platform_authentication: dict,
         platform_model_id: str,
         features: list,
```

### Comparing `cerebrium-1.1.3/cerebrium/models/base.py` & `cerebrium-1.1.4/cerebrium/models/base.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,15 @@
 from abc import ABC, abstractmethod
+from enum import Enum
 from typing import Union, List
-from torch import Tensor
+
 from numpy import ndarray
-from enum import Enum
+
+from torch import Tensor
+
 
 # from sklearn.base import BaseEstimator
 # from torch.nn import Module as TorchModule
 # from transformers import Pipeline
 # from spacy.language import Language
 # from onnxruntime import InferenceSession
```

### Comparing `cerebrium-1.1.3/cerebrium/models/sklearn.py` & `cerebrium-1.1.4/cerebrium/models/sklearn.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,13 @@
-from torch import Tensor
-from numpy import atleast_2d, ndarray
 from typing import Union, List
+
+from numpy import atleast_2d, ndarray
+
 from cerebrium.models.base import BaseModel
+from torch import Tensor
 
 
 class SKClassifierModel(BaseModel):
     def predict(self, input: Union[Tensor, ndarray, List]) -> list:
         if not isinstance(input, ndarray):
             if isinstance(input, Tensor):
                 input = input.detach().cpu().numpy()
```

### Comparing `cerebrium-1.1.3/cerebrium/requests.py` & `cerebrium-1.1.4/cerebrium/requests.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,26 +1,31 @@
-import requests
 import json
 import os
-import time
 import re
-from termcolor import colored
+import time
 from typing import Tuple, Union
+
+import requests
 from tenacity import retry, stop_after_delay, wait_fixed
+from termcolor import colored
 from yaspin import yaspin
 from yaspin.spinners import Spinners
-from cerebrium.errors import CerebriumRequestError, CerebriumDeploymentError
 
+from cerebrium.errors import CerebriumRequestError, CerebriumDeploymentError
 
-ENV = os.getenv("DEVELOPMENT_ENV", "prod")
+ENV = os.getenv("ENV", "prod")
 if ENV == "dev":
     print("Using development environment")
     BASE_CEREBRIUM_URL = "https://dev-rest-api.cerebrium.ai"
+    DASHBOARD_URL = "https://dev-dashboard.cerebrium.ai"
+    TRAINING_URL = "http://dev-training-api.cerebrium.ai/"
 else:
     BASE_CEREBRIUM_URL = "https://rest-api.cerebrium.ai"
+    DASHBOARD_URL = "https://dashboard.cerebrium.ai"
+    TRAINING_URL = "http://training-api.cerebrium.ai/"
 
 
 def _check_payload(method: str, payload: dict) -> bool:
     """
     Check that the payload for a given method is valid.
 
     Args:
```

### Comparing `cerebrium-1.1.3/pyproject.toml` & `cerebrium-1.1.4/pyproject.toml`

 * *Files 9% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 [tool.poetry]
 name = "cerebrium"
-version = "1.1.3"
+version = "1.1.4"
 description = ""
 authors = ["Elijah Roussos <elijah@cerebrium.ai>"]
 license = "AGPL-3.0-only"
 readme = "README.md"
-exclude = ["tests/*", "dist/*", "worker/*", "builder/*", "prebuilt/*", "common/*", "examples/*"]
+exclude = ["tests/*", "dist/*", "webhook/*", "builder/*", "prebuilt/*", "common/*", "examples/*", "trainer/*"]
 
 [tool.poetry.urls]
 "Homepage" = "https://www.cerebrium.ai"
 "Documentation" = "https://docs.cerebrium.ai/"
 
 [[tool.poetry.source]]
 name = "cerebrium"
@@ -62,14 +62,16 @@
 poetry-dynamic-versioning = {extras = ["plugin"], version = ">=0.21,<0.22"}
 torchvision = ">=0.14,<0.15"
 pytest = ">=7.2,<7.3"
 coverage = ">=7.1,<7.2"
 pytest-cov = ">=4.0,<4.1"
 notebook = ">=6.5,<6.6"
 torchinfo = ">=1.7,<1.8"
+peft = ">=0.3.0"
+sentencepiece = ">=0.1.99,<0.2.0"
 
 [tool.poetry.extras]
 onnxruntime = ["onnxruntime"]
 onnxruntime-gpu = ["onnxruntime-gpu"]
 worker = ["loguru", "ddtrace", "datadog", "Pillow", "chitra", "datasets", "celery", "accelerate", "bitsandbytes", "xformers"]
 tensorflow = ["tensorflow", "keras"]
```

### Comparing `cerebrium-1.1.3/PKG-INFO` & `cerebrium-1.1.4/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cerebrium
-Version: 1.1.3
+Version: 1.1.4
 Summary: 
 License: AGPL-3.0-only
 Author: Elijah Roussos
 Author-email: elijah@cerebrium.ai
 Requires-Python: >=3.8,<3.11
 Classifier: License :: OSI Approved :: GNU Affero General Public License v3
 Classifier: Programming Language :: Python :: 3
```

