# Comparing `tmp/perming-1.1.1-py3-none-any.whl.zip` & `tmp/perming-1.2.0-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,12 +1,12 @@
-Zip file size: 12489 bytes, number of entries: 10
--rw-rw-rw-  2.0 fat      849 b- defN 23-May-29 18:05 perming/__init__.py
+Zip file size: 12716 bytes, number of entries: 10
+-rw-rw-rw-  2.0 fat      849 b- defN 23-Jun-28 11:12 perming/__init__.py
 -rw-rw-rw-  2.0 fat      176 b- defN 23-May-29 15:03 perming/_typing.py
--rw-rw-rw-  2.0 fat    19369 b- defN 23-May-29 18:06 perming/_utils.py
+-rw-rw-rw-  2.0 fat    20144 b- defN 23-Jun-28 11:39 perming/_utils.py
 -rw-rw-rw-  2.0 fat      568 b- defN 23-May-29 16:53 perming/_version.py
--rw-rw-rw-  2.0 fat    10419 b- defN 23-May-29 16:22 perming/common.py
--rw-rw-rw-  2.0 fat     5523 b- defN 23-May-29 15:25 perming/general.py
--rw-rw-rw-  2.0 fat     7672 b- defN 23-May-29 18:12 perming-1.1.1.dist-info/METADATA
--rw-rw-rw-  2.0 fat       92 b- defN 23-May-29 18:12 perming-1.1.1.dist-info/WHEEL
--rw-rw-rw-  2.0 fat        8 b- defN 23-May-29 18:12 perming-1.1.1.dist-info/top_level.txt
--rw-rw-r--  2.0 fat      746 b- defN 23-May-29 18:12 perming-1.1.1.dist-info/RECORD
-10 files, 45422 bytes uncompressed, 11235 bytes compressed:  75.3%
+-rw-rw-rw-  2.0 fat    10402 b- defN 23-Jun-28 11:36 perming/common.py
+-rw-rw-rw-  2.0 fat     5523 b- defN 23-Jun-28 11:35 perming/general.py
+-rw-rw-rw-  2.0 fat     7523 b- defN 23-Jun-28 11:42 perming-1.2.0.dist-info/METADATA
+-rw-rw-rw-  2.0 fat       92 b- defN 23-Jun-28 11:42 perming-1.2.0.dist-info/WHEEL
+-rw-rw-rw-  2.0 fat        8 b- defN 23-Jun-28 11:42 perming-1.2.0.dist-info/top_level.txt
+-rw-rw-r--  2.0 fat      746 b- defN 23-Jun-28 11:42 perming-1.2.0.dist-info/RECORD
+10 files, 46031 bytes uncompressed, 11462 bytes compressed:  75.1%
```

## zipnote {}

```diff
@@ -12,20 +12,20 @@
 
 Filename: perming/common.py
 Comment: 
 
 Filename: perming/general.py
 Comment: 
 
-Filename: perming-1.1.1.dist-info/METADATA
+Filename: perming-1.2.0.dist-info/METADATA
 Comment: 
 
-Filename: perming-1.1.1.dist-info/WHEEL
+Filename: perming-1.2.0.dist-info/WHEEL
 Comment: 
 
-Filename: perming-1.1.1.dist-info/top_level.txt
+Filename: perming-1.2.0.dist-info/top_level.txt
 Comment: 
 
-Filename: perming-1.1.1.dist-info/RECORD
+Filename: perming-1.2.0.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## perming/__init__.py

```diff
@@ -22,8 +22,8 @@
 
 COMMON_MODELS = {
     'Regression': Regressier,
     'Binary-classification': Binarier,
     'Multi-classification': Mutipler
 }
 
-__version__ = '1.1.1'
+__version__ = '1.2.0'
```

## perming/_utils.py

```diff
@@ -1,10 +1,10 @@
 # Copyright (c) 2023 linjing-lab
 
-import torch, random, numpy, gc, sortingx
+import torch, random, numpy, gc
 from joblib import parallel_backend
 from collections import OrderedDict
 from ._typing import TabularData, Tuple, Dict, Optional, Any
 from ._version import parse_torch_version
 
 class TabularDataset(torch.utils.data.Dataset):
     '''
@@ -29,15 +29,15 @@
     :param input_: int, features' dimension of tabular data is input_.
     :param num_classes: int, total number of correct label categories.
     :param hidden_layer_sizes: Tuple[int], configure the size of each hidden layer. default: (100,).
     :param activation:, activation configured by Classfier. default: torch.nn.ReLU().
     '''
     def __init__(self, input_: int, num_classes: int, hidden_layer_sizes: Tuple[int], activation) -> None:
         super(MLP, self).__init__()
-        self.squeeze = False if num_classes > 1 else True
+        self.squeeze: bool = False if num_classes > 1 else True
         if hidden_layer_sizes:
             assert hidden_layer_sizes[0] > 0, "Please ensure any layer of hidden_layer_sizes > 0"
             model_layers, hidden_length = OrderedDict(), len(hidden_layer_sizes)
             model_layers['Linear0'] = torch.nn.Linear(input_, hidden_layer_sizes[0])
             model_layers['Activation0'] = activation
             for index in range(1, hidden_length):
                 assert hidden_layer_sizes[index] > 0, "Please ensure any layer of hidden_layer_sizes > 0"
@@ -48,45 +48,45 @@
             self.mlp = torch.nn.Sequential(model_layers)
         else:
             self.mlp = torch.nn.Linear(input_, num_classes)
 
     def forward(self, x):
         output = self.mlp(x)
         return output.squeeze(-1) if self.squeeze else output
-    
+
 class BaseModel:
     '''
     Basic Model for Configuring Common Models and General Box.
     :param input_: int, features' dimension of tabular data is input_.
     :param num_classes: int, total number of correct label categories.
     :param hidden_layer_sizes: Tuple[int], configure the size of each hidden layer.
     :param device: Any, device configured by common models and general box.
     :param activation: Any, activated function configured by common models and general box.
     :param criterion: Any, loss function determined by common models and general box.
-    :param solver: str, optimization coordinated with `torch.optim.lr_scheduler`. default: adam. (modified more params in `_solver`.)
-    :param batch_size: int, batch size of tabular dataset in one training process. default: 32.
-    :param learning_rate_init: float, initialize the learning rate of the optimizer. default: 1e-3.
+    :param solver: str, optimization coordinated with `torch.optim.lr_scheduler`. (modified more params in `_solver`.)
+    :param batch_size: int, batch size of tabular dataset in one training process.
+    :param learning_rate_init: float, initialize the learning rate of the optimizer.
     :param lr_scheduler: str | None, set the learning rate scheduler integrated with the optimizer. default: None. (modifier more params in `_scheduler`.)
     '''
     def __init__(self,
                  input_: int,
                  num_classes: int,
                  hidden_layer_sizes: Tuple[int],
                  device: Any,
                  activation: Any,
                  criterion: Any,
                  solver: str, 
                  batch_size: int, 
                  learning_rate_init: float,
                  lr_scheduler: Optional[str]=None) -> None:
 
-        assert input_ > 0
-        assert num_classes > 0
-        assert batch_size > 0
-        assert learning_rate_init > 0
+        assert input_ > 0, 'BaseModel need samples with dataset features named input_ > 0.'
+        assert num_classes > 0, 'Supervised learning problems with num_classes ranges from (1, 2, 3, ...).'
+        assert batch_size > 0, 'Batch size initialized with int value mostly 2^n(n=1, 2, 3), like 64, 128, 256.'
+        assert learning_rate_init > 0 and learning_rate_init < 1.0, 'Please assert learning rate initialized value in (0, 1.0).'
         self.input: int = input_
         self.num_classes: int = num_classes
         self.activation = activation
         self.device = device # device configuration
         self.criterion = criterion
         self.batch_size: int = batch_size
         self.lr: float = learning_rate_init
@@ -147,50 +147,56 @@
                     features: TabularData, 
                     target: TabularData, 
                     ratio_set: Dict[str, int]={'train': 8, 'test': 1, 'val': 1}, 
                     worker_set: Dict[str, int]={'train': 8, 'test': 2, 'val': 1},
                     random_seed: Optional[int]=None) -> None:
         '''
         Encapsulate Dataset to DataLoader from Tabular Dataset.
-        :param features: TabularData, composed of n-row samples and m-column features.
-        :param target: TabularData, consists of correct labels or values with size at n.
-        :param ratio_set: Dict[str, int], stores the proportion of train-set, test-set and val-set. default: {'train': 7, 'test': 2, 'val': 1}.
+        :param features: TabularData, composed of n-row samples and m-column features: (n_samples, n_features).
+        :param target: TabularData, consists of correct labels or values: (n_samples,) or (n_samples, n_outputs).
+        :param ratio_set: Dict[str, int], stores the proportion of train-set, test-set and val-set. default: {'train': 8, 'test': 1, 'val': 1}.
         :param worker_set: Dict[str, int], load the configuration of DataLoader with multi-threaded. default: {'train': 8, 'test': 2, 'val': 1}.
         :param random_seed: int | None, random.seed(random_seed) used for fixed random datasets. default: None.
         '''
         assert ratio_set['train'] > 0 and ratio_set['test'] > 0 and ratio_set['val'] > 0
         assert ratio_set['train'] > 4 * ratio_set['test'], "The training set needs to be larger than the test set."
         assert ratio_set['train'] + ratio_set['test'] + ratio_set['val'] == 10, "The sum of 3 datasets' ratio needs to be 10."
-        assert features.shape[1] == self.input, "Please ensure `input_` is equal to `features.shape[1]`."
-        if self.num_classes >= 2:
-            self.unique = numpy.unique(target)
-            assert len(self.unique) == self.num_classes, "Please ensure `num_classes` is equal to `len(numpy.unique(labels))`."
-            self.indices = dict(zip(self.unique, range(self.num_classes)))
-            target = numpy.array([self.indices[value] for value in target], dtype=numpy.int8)
-        else:
-            assert str(target.dtype).startswith("float"), "Please ensure target.dtype in any float type of numpy.dtype"
+        assert isinstance(features, TabularData) and features.ndim == 2, 'Please ensure features with dimension at (n_samples, n_features).'
+        assert features.shape[1] > 1 and features.shape[1] == self.input, "Please ensure `input_` is equal to `features.shape[1]`."
+        assert isinstance(target, TabularData), "Please ensure target format at numpy.ndarray noted as TabularData."
+        if isinstance(target[0], TabularData): # (n_samples, n_outputs)
+            raise RuntimeError("data_loader not support target with (n_samples, n_ouputs) yet.")
+        else: # (n_samples,)
+            assert len(target.shape) == 1 and target.shape[0] > 0, "Please ensure target is 1d scalar value."
+            if self.num_classes >= 2:
+                self.unique = numpy.unique(target) # int indexes -> any class with single value noted
+                assert len(self.unique) == self.num_classes, "Please ensure `num_classes` is equal to `len(numpy.unique(labels))`."
+                self.indices = dict(zip(self.unique, range(self.num_classes))) # original classes -> int indexes
+                target = numpy.array([self.indices[value] for value in target], dtype=numpy.int8) # adjust int8 -> any int dtype
+            else:
+                assert str(target.dtype).startswith("float"), "Please ensure target.dtype in any float type of numpy.dtype"
         train_, test_, val_ = train_test_val_split(features, target, ratio_set, random_seed)
         self.train_loader = torch.utils.data.DataLoader(TabularDataset(train_['features'], train_['target'], self.model.squeeze), batch_size=self.batch_size, shuffle=True, num_workers=worker_set['train'], )
         self.test_loader = torch.utils.data.DataLoader(TabularDataset(test_['features'], test_['target'], self.model.squeeze), batch_size=self.batch_size, shuffle=True, num_workers=worker_set['test'])
         self.val_loader = torch.utils.data.DataLoader(TabularDataset(val_['features'], val_['target'], self.model.squeeze), batch_size=self.batch_size, shuffle=False, num_workers=worker_set['val'])
 
     def train_val(self, 
                   num_epochs: int=2, 
                   interval: int=100, 
                   backend: str="threading", 
                   n_jobs: int=-1) -> None:
         '''
         Training and Validation with `train_loader` and `val_container`.
         :param num_epochs: int, training epochs for `self.model`. default: 2.
         :param interval: int, console output interval. default: 100.
-        :param backend: str, "threading", "multiprocessing, 'locky'. default: "threading".
+        :param backend: str, "threading", "multiprocessing, "locky". default: "threading".
         :param n_jobs: int, accelerate processing of validation. default: -1.
         '''
-        assert num_epochs > 0 and interval > 0
-        assert n_jobs == -1 or n_jobs > 0
+        assert num_epochs > 0 and interval > 0, 'With num_epochs > 0 and interval > 0 to train parameters into outputs.'
+        assert n_jobs == -1 or n_jobs > 0, 'Take full jobs with setting n_jobs=-1 or manually set nums of jobs.'
         total_step = len(self.train_loader)
         self._set_container(backend, n_jobs)
         for epoch in range(num_epochs):
             gc.collect()
             torch.cuda.empty_cache()
             for i, (features, target) in enumerate(self.train_loader):
                 features = features.to(self.device)
@@ -200,36 +206,34 @@
                 outputs = self.model(features)
                 self.train_loss = self.criterion(outputs, target)
 
                 # backward and optimize
                 self.solver.zero_grad()
                 self.train_loss.backward()
                 _ = self.solver.step() if self.lr_scheduler == None else self.lr_scheduler.step()
-                
+
                 # validation with val_container
                 self.val_loss = 0
                 with parallel_backend(backend, n_jobs=n_jobs):
                     for val_set in self.val_container:
                         outputs_val = self.model(val_set[0].to(self.device))
                         self.val_loss += self.criterion(outputs_val, val_set[1].to(self.device))
 
                 self.val_loss /= len(self.val_container)
 
                 # console print
                 if (i + 1) % interval == 0:
-                    print ('Epoch [{}/{}], Step [{}/{}], Training Loss: {:.4f}, Validation Loss: {:.4f}' .format(epoch+1, num_epochs, i+1, total_step, self.train_loss.item(), self.val_loss.item()))
+                    print ('Epoch [{}/{}], Step [{}/{}], Training Loss: {:.4f}, Validation Loss: {:.4f}'.format(epoch+1, num_epochs, i+1, total_step, self.train_loss.item(), self.val_loss.item()))
 
     def test(self, 
-             sort_by: str='accuracy', 
-             sort_kernel: str='bubble', 
+             sort_by: str='accuracy',
              sort_state: bool=True):
         '''
-        Test with Initialized Configuration. `accuracy > 0`, 'correct_class != None' and the underline keywords only appears when `num_classes >= 2`.
+        Test with Initialized Configuration. `accuracy > 0`, 'correct_class != None' and keywords only appears when `num_classes >= 2`.
         :param sort_by: str, 'accuracy', 'numbers', 'num-total'. default: 'accuracy'.
-        :param sort_kernel: 'bubble', 'insert', 'shell', 'heap', 'quick', 'merge'. default: 'bubble'.
         :param sort_state: bool, whether to use descending order when sorting. default: True.
         '''
         with torch.no_grad():
             self.test_loss, correct, self.correct_class, test_loader_step = 0, 0, dict.fromkeys(self.unique, [0, 0]) if self.num_classes >= 2 else None, len(self.test_loader)
             test_total = test_loader_step * self.batch_size
             for features, target in self.test_loader:
                 features = features.to(self.device)
@@ -240,15 +244,15 @@
                     for index, value in enumerate(predicted):
                         self.correct_class[self.unique[value]][1] += 1 # record total numbers of each class
                         self.correct_class[self.unique[value]][0] += (value == target[index]).item() # record total true numbers of each class
                     correct += (predicted == target).sum().item()
                 self.test_loss += self.criterion(outputs, target)
             self.test_loss /= test_loader_step
             print('loss of {0} on the {1} test dataset: {2}. accuracy: {3:.4f} %'.format(self.__class__.__name__, test_total, self.test_loss.item(), 100 * correct / test_total))
-        return OrderedDict(self._packing(sort_by, sort_kernel, sort_state))
+        return OrderedDict(self._packing(sort_by, sort_state))
     
     def save(self, show: bool=True, dir: str='./model') -> None:
         '''
         Save Model Checkpoint with Classifier and Regressier.
         :param show: bool, whether to show `model.state_dict()`. default: True.
         :param dir: str, model save to dir. default: './model'.
         '''
@@ -263,41 +267,38 @@
         :param dir: str, model load from dir. default: './model'.
         '''
         params = torch.load(dir)
         self.model.load_state_dict(params)
         if show:
             print(self.model.state_dict())
 
-    def _packing(self, by: str, kernel: str, state: bool) -> Dict[str, Any]:
+    def _packing(self, by: str, state: bool) -> Dict[str, Any]:
         '''
-        Pack Test Returned Data including `correct_class` and returned result of `sortingx.[method]()`.
+        Pack Test Returned Data including `correct_class` and returned result of `sorted`.
         :param by: str, choose which way to sort the order of 'correct_class'.
-        :param kernel: str, choose which kernel used for sorting `correct_class.items()`.
         :param state: bool, choose the state when `correct_class` is sorting.
         '''
-        assert kernel in sortingx.__all__, "Please ensure kernel is sortingx.__all__."
-        kernel = eval('sortingx.' + kernel)
         loss_, classify, regress = {
             'loss': {'train': self.train_loss.item(), 
                      'val': self.val_loss.item(),
                      'test': self.test_loss.item()}
         }, {'problem': 'classification',
             'num_classes': self.num_classes,
             'column': ('label name', ('true numbers', 'total numbers')),
             'labels': self.correct_class}, {'problem': 'regression'}
         if self.num_classes >= 2:
             classify.update(loss_)
             if by == 'numbers':
-                classify.update({'sorted': kernel(self.correct_class.items(), lambda d: d[1][0], reverse=state)})
+                classify.update({'sorted': sorted(self.correct_class.items(), key=lambda d: d[1][0], reverse=state)})
                 return classify
             elif by == 'accuracy':
-                classify.update({'sorted': kernel(self.correct_class.items(), lambda d: d[1][0]/d[1][1], reverse=state)})
+                classify.update({'sorted': sorted(self.correct_class.items(), key=lambda d: d[1][0]/d[1][1], reverse=state)})
                 return classify
             elif by == 'num-total':
-                classify.update({'sorted': kernel(self.correct_class.items(), lambda d: (d[1][0], d[1][1]), reverse=state)})
+                classify.update({'sorted': sorted(self.correct_class.items(), key=lambda d: (d[1][0], d[1][1]), reverse=state)})
                 return classify
             else:
                 raise ValueError("`lambda` Caused with `by` Configuration Supports: numbers, accuracy, num-total.")
         else:
             regress.update(loss_)
             return regress
```

## perming/common.py

```diff
@@ -8,15 +8,15 @@
     Supervised Learning Regressier for Tabular Data.
     :param input_: int, features' dimension of tabular data is input_.
     :param hidden_layer_sizes: Tuple[int], configure the size of each hidden layer. default: (100,).
     :param activation: str, configure function that activates the hidden layer. default: relu.
     :param criterion: str, loss function determined by different learning problem. default: MSELoss.
     :param solver: str, optimization function initialized with `learning_rate_init`. default: adam.
     :param batch_size: int, batch size of dataset in one training process. default: 32.
-    :param learning_rate_init: float, initialize the learning rate of the optimizer. default: 1e-3.
+    :param learning_rate_init: float, initialize the learning rate of the optimizer. default: 1e-2.
     :param lr_scheduler: str | None, set the learning rate scheduler integrated with the optimizer. default: None.
     '''
     def __init__(self, 
                  input_: int, 
                  hidden_layer_sizes: Tuple[int]=(100,),
                  *,
                  activation: str='relu', 
@@ -73,18 +73,18 @@
 
 class Binarier(BaseModel):
     '''
     Binary Supervised Learning Classifier for Tabular Data.
     :param input_: int, features' dimension of tabular data is input_.
     :param hidden_layer_sizes: Tuple[int], configure the size of each hidden layer. default: (100,).
     :param activation: str, configure function that activates the hidden layer. default: relu.
-    :param criterion: str, loss function determined by different learning problem. default: CrossEntropyLoss.
+    :param criterion: str, loss function determined by different learning problem. default: BCELoss.
     :param solver: str, optimization function coordinated with `torch.optim.lr_scheduler`. default: adam.
     :param batch_size: int, batch size of dataset in one training process. default: 32.
-    :param learning_rate_init: float, initialize the learning rate of the optimizer. default: 1e-3.
+    :param learning_rate_init: float, initialize the learning rate of the optimizer. default: 1e-2.
     :param lr_scheduler: str | None, set the learning rate scheduler integrated with the optimizer. default: None.
     '''
     def __init__(self, 
                  input_: int, 
                  hidden_layer_sizes: Tuple[int]=(100,),
                  *,
                  activation: str='relu', 
@@ -146,29 +146,29 @@
     :param num_classes: int, total number of correct label categories.
     :param hidden_layer_sizes: Tuple[int], configure the size of each hidden layer. default: (100,).
     :param activation: str, configure function that activates the hidden layer. default: relu.
     :param inplace_on: bool, whether to use `inplace=True` on activation. default: False.
     :param criterion: str, loss function determined by different learning problem. default: CrossEntropyLoss.
     :param solver: str, optimization function coordinated with `torch.optim.lr_scheduler`. default: adam.
     :param batch_size: int, batch size of dataset in one training process. default: 32.
-    :param learning_rate_init: float, initialize the learning rate of the optimizer. default: 1e-3.
+    :param learning_rate_init: float, initialize the learning rate of the optimizer. default: 1e-2.
     :param lr_scheduler: str | None, set the learning rate scheduler integrated with the optimizer. default: None.
     '''
     def __init__(self, 
                  input_: int, 
                  num_classes: int,
                  hidden_layer_sizes: Tuple[int]=(100,),
                  *,
                  activation: str='relu', 
                  criterion: str='CrossEntropyLoss',
                  solver: str='adam', 
                  batch_size: int=32, 
                  learning_rate_init: float=1e-2,
                  lr_scheduler: Optional[str]=None) -> None:
-        
+
         super(Mutipler, self).__init__(input_, 
                                        num_classes, 
                                        hidden_layer_sizes, 
                                        torch.device("cuda" if torch.cuda.is_available() else "cpu"), 
                                        self._activate(activation), 
                                        self._criterion(criterion), 
                                        solver,
```

## perming/general.py

```diff
@@ -11,15 +11,15 @@
     :param hidden_layer_sizes: Tuple[int], configure the size of each hidden layer. default: (100,).
     :param device: str, configure hardware environment for training. options: "cuda", "cpu". default: cuda.
     :param activation: str, configure function that activates the hidden layer. default: relu.
     :param inplace_on: bool, whether to use `inplace=True` on activation. default: False.
     :param criterion: str, loss function determined by different learning problem. default: CrossEntropyLoss.
     :param solver: str, optimization coordinated with `torch.optim.lr_scheduler`. default: adam.
     :param batch_size: int, batch size of tabular dataset in one training process. default: 32.
-    :param learning_rate_init: float, initialize the learning rate of the optimizer. default: 1e-3.
+    :param learning_rate_init: float, initialize the learning rate of the optimizer. default: 1e-2.
     :param lr_scheduler: str | None, set the learning rate scheduler integrated with the optimizer. default: None.
     '''
     def __init__(self, 
                  input_: int, 
                  num_classes: int, # num_classes=1
                  hidden_layer_sizes: Tuple[int]=(100,),
                  device: str="cuda",
```

## Comparing `perming-1.1.1.dist-info/METADATA` & `perming-1.2.0.dist-info/METADATA`

 * *Files 7% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: perming
-Version: 1.1.1
+Version: 1.2.0
 Summary: The supervised learning framework based on perceptron for tabular data.
 Home-page: https://github.com/linjing-lab/easy-pytorch/tree/main/released_box
 Download-URL: https://github.com/linjing-lab/easy-pytorch/tags
 Author: 林景
 Author-email: linjing010729@163.com
 License: MPL 2.0
 Project-URL: Source, https://github.com/linjing-lab/easy-pytorch/tree/main/released_box/perming
@@ -19,19 +19,18 @@
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: License :: OSI Approved :: Mozilla Public License 2.0 (MPL 2.0)
 Classifier: Topic :: Software Development
 Classifier: Topic :: Software Development :: Libraries
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
+Classifier: Topic :: Scientific/Engineering
 Classifier: Topic :: Scientific/Engineering :: Artificial Intelligence
 Description-Content-Type: text/markdown
-Requires-Dist: polars[pandas] (>=0.17.0)
 Requires-Dist: numpy (>=1.21.0)
-Requires-Dist: sortingx (>=1.2.2)
 Requires-Dist: joblib (>=1.1.0)
 
 # perming
 
 perming: Perceptron Models Are Training on Windows Platform with Default GPU Acceleration.
 
 - p: use polars or pandas to read dataset.
@@ -48,51 +47,51 @@
 ## general model
 
 |GENERAL_BOX(Box)|Parameters|Meaning|
 |--|--|--|
 |`__init__`|input_: int<br />num_classes: int<br />hidden_layer_sizes: Tuple[int]=(100,)<br />device: str="cuda"<br />*<br />activation: str="relu"<br />inplace_on: bool=True<br />criterion: str="CrossEntropyLoss"<br />solver: str="adam"<br />batch_size: int=32<br />learning_rate_init: float=1e-2<br />lr_scheduler: Optional[str]=None|Initialize Classifier or Regressier Based on Basic Information of the Dataset Obtained through Data Preprocessing and Feature Engineering.|
 |print_config|/|Return Initialized Parameters of Multi-layer Perceptron and Graph.|
 |data_loader|features: TabularData<br />labels: TabularData<br />ratio_set: Dict[str, int]={'train': 8, 'test': 1, 'val': 1}<br />worker_set: Dict[str, int]={'train': 8, 'test': 2, 'val': 1}<br />random_seed: Optional[int]=None|Using `ratio_set` and `worker_set` to Load the Numpy Dataset into `torch.utils.data.DataLoader`.|
-|train_val|num_epochs: int=5<br />interval: int=100<br />backend: str="threading"<br />n_jobs: int=-1|Using `num_epochs` to Control Training Process and `interval` to Adjust Print Interval with Accelerated Validation Combined with `backend` and `n_jobs`.|
-|test|sort_by: str="accuracy"<br />sort_kernel: str="bubble"<br />sort_state: bool=True|Sort Returned Test Result about Correct Classes with `sort_by`, `sort_kernel`, `sort_state` Which Only Appears in Classification.|
+|train_val|num_epochs: int=2<br />interval: int=100<br />backend: str="threading"<br />n_jobs: int=-1|Using `num_epochs` to Control Training Process and `interval` to Adjust Print Interval with Accelerated Validation Combined with `backend` and `n_jobs`.|
+|test|sort_by: str="accuracy"<br />sort_state: bool=True|Sort Returned Test Result about Correct Classes with `sort_by` and `sort_state` Which Only Appears in Classification.|
 |save|show: bool=True<br />dir: str='./model'|Save Trained Model Parameters with Model `state_dict` Control by `show`.|
 |load|show: bool=True<br />dir: str='./model'|Load Trained Model Parameters with Model `state_dict` Control by `show`.|
 
 ## common models (cuda first)
 
 - Regression
 
 |Regressier|Parameters|Meaning|
 |--|--|--|
 |`__init__`|input_: int<br />hidden_layer_sizes: Tuple[int]=(100,)*<br /><br />activation: str="relu"<br />criterion: str="MSELoss"<br />solver: str="adam"<br />batch_size: int=32<br />learning_rate_init: float=1e-2<br />lr_scheduler: Optional[str]=None|Initialize Regressier Based on Basic Information of the Regression Dataset Obtained through Data Preprocessing and Feature Engineering with `num_classes=1`.|
 |print_config|/|Return Initialized Parameters of Multi-layer Perceptron and Graph.|
-|train_val|num_epochs: int=5<br />interval: int=100<br />backend: str="threading"<br />n_jobs: int=-1|Using `ratio_set` and `worker_set` to Load the Regression Dataset with Numpy format into `torch.utils.data.DataLoader`.|
+|train_val|num_epochs: int=2<br />interval: int=100<br />backend: str="threading"<br />n_jobs: int=-1|Using `ratio_set` and `worker_set` to Load the Regression Dataset with Numpy format into `torch.utils.data.DataLoader`.|
 |test|/|Test Module Only Show with Loss at 3 Stages: Train, Test, Val|
 |save|show: bool=True<br />dir: str='./model'|Save Trained Model Parameters with Model `state_dict` Control by `show`.|
 |load|show: bool=True<br />dir: str='./model'|Load Trained Model Parameters with Model `state_dict` Control by `show`.|
 
 - Binary-classification
 
 |Binarier|Parameters|Meaning|
 |--|--|--|
 |`__init__`|input_: int<br />hidden_layer_sizes: Tuple[int]=(100,)*<br /><br />activation: str="relu"<br />criterion: str="BCELoss"<br />solver: str="adam"<br />batch_size: int=32<br />learning_rate_init: float=1e-2<br />lr_scheduler: Optional[str]=None|Initialize Classifier Based on Basic Information of the Classification Dataset Obtained through Data Preprocessing and Feature Engineering with `num_classes=2`.|
 |print_config|/|Return Initialized Parameters of Multi-layer Perceptron and Graph.|
 |train_val|num_epochs: int=2<br />interval: int=100<br />backend: str="threading"<br />n_jobs: int=-1|Using `ratio_set` and `worker_set` to Load the Regression Dataset with Numpy format into `torch.utils.data.DataLoader`.|
-|test|sort_by: str="accuracy"<br />sort_kernel: str="bubble"<br />sort_state: bool=True|Test Module Show with Correct Class and Loss at 3 Stages: Train, Test, Val|
+|test|sort_by: str="accuracy"<br />sort_state: bool=True|Test Module Show with Correct Class and Loss at 3 Stages: Train, Test, Val|
 |save|show: bool=True<br />dir: str='./model'|Save Trained Model Parameters with Model `state_dict` Control by `show`.|
 |load|show: bool=True<br />dir: str='./model'|Load Trained Model Parameters with Model `state_dict` Control by `show`.|
 
 - Multi-classification
 
 |Multipler|Parameters|Meaning|
 |--|--|--|
 |`__init__`|input_: int<br />num_classes: int<br />hidden_layer_sizes: Tuple[int]=(100,)*<br /><br />activation: str="relu"<br />criterion: str="CrossEntropyLoss"<br />solver: str="adam"<br />batch_size: int=32<br />learning_rate_init: float=1e-2<br />lr_scheduler: Optional[str]=None|Initialize Classifier Based on Basic Information of the Classification Dataset Obtained through Data Preprocessing and Feature Engineering with `num_classes>2`.|
 |print_config|/|Return Initialized Parameters of Multi-layer Perceptron and Graph.|
 |train_val|num_epochs: int=2<br />interval: int=100<br />backend: str="threading"<br />n_jobs: int=-1|Using `ratio_set` and `worker_set` to Load the Regression Dataset with Numpy format into `torch.utils.data.DataLoader`.|
-|test|sort_by: str="accuracy"<br />sort_kernel: str="bubble"<br />sort_state: bool=True|Sort Returned Test Result about Correct Classes with `sort_by`, `sort_kernel`, `sort_state` Which Only Appears in Classification.|
+|test|sort_by: str="accuracy"<br />sort_state: bool=True|Sort Returned Test Result about Correct Classes with `sort_by` and `sort_state` Which Only Appears in Classification.|
 |save|show: bool=True<br />dir: str='./model'|Save Trained Model Parameters with Model `state_dict` Control by `show`.|
 |load|show: bool=True<br />dir: str='./model'|Load Trained Model Parameters with Model `state_dict` Control by `show`.|
 
 ## pip install
 
 download latest version:
 ```text
```

