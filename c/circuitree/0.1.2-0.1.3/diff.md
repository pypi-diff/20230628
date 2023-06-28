# Comparing `tmp/circuitree-0.1.2.tar.gz` & `tmp/circuitree-0.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "circuitree-0.1.2.tar", max compression
+gzip compressed data, was "circuitree-0.1.3.tar", max compression
```

## Comparing `circuitree-0.1.2.tar` & `circuitree-0.1.3.tar`

### file list

```diff
@@ -1,14 +1,14 @@
--rw-r--r--   0        0        0    35149 2023-04-06 18:32:42.965443 circuitree-0.1.2/LICENSE
--rw-r--r--   0        0        0     1011 2023-06-09 16:36:39.964761 circuitree-0.1.2/README.md
--rwxr-xr-x   0        0        0      117 2023-05-26 21:21:11.249063 circuitree-0.1.2/circuitree/__init__.py
--rwxr-xr-x   0        0        0    15789 2023-06-09 16:17:43.194776 circuitree-0.1.2/circuitree/circuitree.py
--rwxr-xr-x   0        0        0     5381 2023-06-01 21:21:07.888185 circuitree-0.1.2/circuitree/models.py
--rw-r--r--   0        0        0     3991 2023-05-26 18:27:42.279204 circuitree-0.1.2/circuitree/modularity.py
--rw-r--r--   0        0        0     8695 2023-06-08 20:21:23.933282 circuitree-0.1.2/circuitree/parallel.py
--rw-r--r--   0        0        0      267 2023-05-26 18:24:06.289207 circuitree-0.1.2/circuitree/regret.py
--rw-r--r--   0        0        0      750 2023-05-13 02:24:31.319175 circuitree-0.1.2/circuitree/rewards.py
--rw-r--r--   0        0        0      224 2023-06-09 00:12:32.253104 circuitree-0.1.2/circuitree/utils.py
--rw-r--r--   0        0        0      407 2023-05-26 18:26:21.149205 circuitree-0.1.2/circuitree/viz.py
--rw-r--r--   0        0        0     1469 2023-06-10 07:29:13.219330 circuitree-0.1.2/pyproject.toml
--rw-r--r--   0        0        0     1705 1970-01-01 00:00:00.000000 circuitree-0.1.2/setup.py
--rw-r--r--   0        0        0     1596 1970-01-01 00:00:00.000000 circuitree-0.1.2/PKG-INFO
+-rw-r--r--   0        0        0    35149 2023-04-06 18:32:42.965443 circuitree-0.1.3/LICENSE
+-rw-r--r--   0        0        0     1011 2023-06-09 16:36:39.964761 circuitree-0.1.3/README.md
+-rwxr-xr-x   0        0        0      117 2023-06-23 05:39:39.142840 circuitree-0.1.3/circuitree/__init__.py
+-rwxr-xr-x   0        0        0    15843 2023-06-23 06:25:24.652892 circuitree-0.1.3/circuitree/circuitree.py
+-rwxr-xr-x   0        0        0     5381 2023-06-23 20:46:19.095399 circuitree-0.1.3/circuitree/models.py
+-rw-r--r--   0        0        0     3991 2023-05-26 18:27:42.279204 circuitree-0.1.3/circuitree/modularity.py
+-rw-r--r--   0        0        0     9417 2023-06-28 00:46:06.604507 circuitree-0.1.3/circuitree/parallel.py
+-rw-r--r--   0        0        0      267 2023-05-26 18:24:06.289207 circuitree-0.1.3/circuitree/regret.py
+-rw-r--r--   0        0        0      750 2023-05-13 02:24:31.319175 circuitree-0.1.3/circuitree/rewards.py
+-rw-r--r--   0        0        0     1442 2023-06-23 05:30:14.382829 circuitree-0.1.3/circuitree/utils.py
+-rw-r--r--   0        0        0    10132 2023-06-27 21:29:15.594283 circuitree-0.1.3/circuitree/viz.py
+-rw-r--r--   0        0        0     1469 2023-06-28 02:20:46.494615 circuitree-0.1.3/pyproject.toml
+-rw-r--r--   0        0        0     1705 1970-01-01 00:00:00.000000 circuitree-0.1.3/setup.py
+-rw-r--r--   0        0        0     1596 1970-01-01 00:00:00.000000 circuitree-0.1.3/PKG-INFO
```

### Comparing `circuitree-0.1.2/LICENSE` & `circuitree-0.1.3/LICENSE`

 * *Files identical despite different names*

### Comparing `circuitree-0.1.2/README.md` & `circuitree-0.1.3/README.md`

 * *Files identical despite different names*

### Comparing `circuitree-0.1.2/circuitree/circuitree.py` & `circuitree-0.1.3/circuitree/circuitree.py`

 * *Files 1% similar despite different names*

```diff
@@ -216,18 +216,18 @@
         if metric_func is None:
             metric_func = lambda *a, **kw: None
 
         metrics = [metric_func(self.graph, [], root, None, **kwargs)]
         if progress_bar:
             from tqdm import trange
 
-            _range = trange
+            iterator = trange(n_steps, desc="MCTS search")
         else:
-            _range = range
-        for i in _range(n_steps):
+            iterator = range(n_steps)
+        for i in iterator:
             selection_path, reward, sim_node = self.traverse(
                 root, accumulate=accumulate, **kwargs
             )
             if not i % save_every:
                 m = metric_func(self.graph, selection_path, sim_node, reward, **kwargs)
                 metrics.append(m)
 
@@ -379,15 +379,15 @@
         ]
         bfs = cycle(leaves)
         n_steps = min(n_repeats * len(leaves), max_steps)
         iterator = range(n_steps)
         if progress:
             from tqdm import tqdm
 
-            iterator = tqdm(iterator)
+            iterator = tqdm(iterator, desc="BFS search")
         for i in iterator:
             n = next(bfs)
             reward = sum(self.get_reward(n) for _ in range(n_steps_per_node))
             self.graph.nodes[n]["reward"] += reward
             self.graph.nodes[n]["visits"] += n_steps_per_node
             # self.graph.nodes[n]["history"].append(reward)
             metrics.append(metric_func(self.graph, n, reward, **kwargs))
```

### Comparing `circuitree-0.1.2/circuitree/models.py` & `circuitree-0.1.3/circuitree/models.py`

 * *Files identical despite different names*

### Comparing `circuitree-0.1.2/circuitree/modularity.py` & `circuitree-0.1.3/circuitree/modularity.py`

 * *Files identical despite different names*

### Comparing `circuitree-0.1.2/circuitree/parallel.py` & `circuitree-0.1.3/circuitree/parallel.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,27 +1,24 @@
-from collections import Counter
 from dataclasses import dataclass, field
 from pathlib import Path
-from typing import Any, Callable, Iterable, Optional
+from typing import Any, Callable, Iterable, Mapping, Optional
+import numpy as np
 import pandas as pd
-import threading
 
-from .circuitree import CircuiTree
+from .utils import DefaultFactoryDict, DefaultMapping
 
 __all__ = [
-    "MCTSResults",
-    "TranspositionTable",
-    "TableBuffer",
-    "DefaultFactoryDict",
-    "ParallelTree",
+    "MCTSResult",
+    "ResultsRegistry",
+    "TranspositionTable"
 ]
 
 
 @dataclass
-class MCTSResults:
+class MCTSResult:
     reward: float
     initial_conditions: Iterable[float | int]
     params: Iterable[float | int]
     _metadata: Optional[Any] = None
 
     @property
     def metadata(self):
@@ -33,36 +30,40 @@
             return (self._metadata,)
 
     def unpack(self):
         return self.reward, *self.initial_conditions, *self.params, *self.metadata
 
 
 @dataclass
-class StateTable:
+class ResultsRegistry:
     state: str
-    visit_results: list[MCTSResults] = field(default_factory=list)
+    visit_results: list[MCTSResult] = field(default_factory=list)
 
-    def __getitem__(self, visit):
+    def __getitem__(self, visit: int):
         return self.visit_results[visit]
 
     def __len__(self):
         return len(self.visit_results)
 
     def __iter__(self):
         return iter(self.visit_results)
 
     def append(self, results):
-        self.visit_results.append(MCTSResults(results))
+        self.visit_results.append(MCTSResult(results))
 
     def extend(self, batch_results):
-        self.visit_results.extend([MCTSResults(r) for r in batch_results])
+        self.visit_results.extend([MCTSResult(*r) for r in batch_results])
 
-    def unpack(self):
+    def unpack_results(self):
         return list(zip(*(results.unpack() for results in self.visit_results)))
 
+    @property
+    def rewards(self):
+        return (r.reward for r in self.visit_results)
+
 
 class TranspositionTable:
     """
     A transposition table for storing results of MCTS with stochastic playouts.
 
     In a stochastic game, each visit to a terminal state yields a different result.
     For a given random series of playouts, the result `vals` of visit number `i` to
@@ -75,39 +76,194 @@
 
     The first element of `vals` is the reward value, which will be accessed by the
     MCTS algorithm. The next elements are the initial conditions of the playout and
     the parameters used. The remaining elements of `vals` are other metadata of the
     simulated playout (returned by the `metric_func` function).
     """
 
-    def __init__(self, results_colnames: Iterable[str], **kwargs):
+    def __new__(cls, *args, **kwargs):
+        # Idempotent
+        if not kwargs and len(args) == 1 and isinstance(args[0], cls):
+            return args[0]
+        else:
+            return super().__new__(cls)
+
+    def __init__(
+        self,
+        results_colnames: Iterable[str],
+        table: Optional[DefaultMapping[str, ResultsRegistry]] = None,
+    ):
         self.columns = tuple(results_colnames)
         self.ncols = len(self.columns)
+        if table is None:
+            _table = DefaultFactoryDict(default_factory=ResultsRegistry)
+        elif isinstance(table, DefaultMapping):
+            _table = table
+        else:
+            raise TypeError(
+                f"table must be a DefaultMapping, not {type(table).__name__}"
+            )
 
-        self.table: dict[str, StateTable] = dict()
-
-    def __getitem__(self, state):
-        return self.table[state]
-
-    def __missing__(self, state):
-        self.table[state] = StateTable(state)
-        return self.table[state]
+        self.table: DefaultMapping[str, ResultsRegistry] = _table
 
-    def __contains__(self, state_visit):
-        return state_visit in self.table
+    def __getitem__(self, state_wwo_visit):
+        """Access the results of visit(s) to a state. If no visit number is specified,
+        return the list of all visit results."""
+        match state_wwo_visit:
+            case (state, visit):
+                return self.table[state][visit]
+            case state:
+                return self.table[state]
+
+    def __missing__(self, state_wwo_visit):
+        """If the state is not in the table, create a new entry. If the visit number
+        is not in the registry for that state, raise an IndexError."""
+        match state_wwo_visit:
+            case (state, visit):
+                n_visits = len(self.table[state])
+                raise IndexError(
+                    f"Visit index {visit} does not exist for state {state} with "
+                    f"{n_visits} total visits."
+                )
+            case state:
+                self.table[state] = ResultsRegistry(state)
+                return self.table[state]
+
+    def __contains__(self, state_wwo_visit):
+        match state_wwo_visit:
+            case (state, visit):
+                return state in self.table and visit < len(self.table[state])
+            case state:
+                return state in self.table
 
     def __len__(self):
         return len(self.table)
 
     def n_visits(self, state):
-        return len(self.table[state])
+        """Return number of visits with triggering a default factory call."""
+        if state in self.table:
+            return len(self.table[state])
+        else:
+            return 0
 
-    def get_reward(self, state, visit):
+    def get_reward(self, state: str, visit: int):
         return self.table[state][visit].reward
 
+    def keys(self):
+        return self.table.keys()
+
+    def values(self):
+        return self.table.values()
+
+    def items(self):
+        return self.table.items()
+
+    def draw_random_result(self, state: str, rg: Optional[np.random.Generator] = None):
+        """Draw a random result from state `state`."""
+        index = rg.integers(0, len(self.table[state]))
+        return self.table[state][index]
+
+    def draw_random_reward(self, state: str, rg: Optional[np.random.Generator] = None):
+        """Draw a random result from state `state`."""
+        index = rg.integers(0, len(self.table[state]))
+        return self.table[state][index].reward
+
+    def draw_bootstrap(
+        self, state: str, size: int, rg: Optional[np.random.Generator] = None
+    ):
+        """Draw a bootstrap sample of size `size` from the results for `state`."""
+        if rg is None:
+            rg = np.random.default_rng()
+        indices = rg.integers(0, len(self.table[state]), size=size)
+        return [self.table[state][i] for i in indices]
+
+    def draw_bootstrap_reward(
+        self, state: str, size: int, rg: Optional[np.random.Generator] = None
+    ):
+        """Draw a bootstrap sample of size `size` from the reward values for `state`."""
+        if rg is None:
+            rg = np.random.default_rng()
+        indices = rg.integers(0, len(self.table[state]), size=size)
+        return np.array([self.table[state][i].reward for i in indices])
+
+    @classmethod
+    def _load_from_source(
+        cls,
+        read_func: Callable,
+        src: Iterable[Path | str] | Path | str,
+        progress: bool = False,
+        visit_col: str = "visit",
+        load_kw: Mapping[str, Any] = {},
+        **kwargs,
+    ):
+        if isinstance(src, Iterable):
+            if progress:
+                from tqdm import tqdm
+
+                df = pd.concat(
+                    [read_func(f, **load_kw) for f in tqdm(src, desc="Loading data")]
+                )
+            else:
+                df = pd.concat([read_func(f, **load_kw) for f in src])
+        else:
+            df = read_func(src, **load_kw)
+
+        df["state"] = pd.Categorical(df["state"])
+        if visit_col not in df.columns:
+            df[visit_col] = df.groupby("state").cumcount()
+
+        return cls.from_dataframe(df, visit_column=visit_col, **kwargs)
+
+    @classmethod
+    def from_csv(cls, source, **kwargs):
+        return cls._load_from_source(pd.read_csv, source, **kwargs)
+
+    @classmethod
+    def from_parquet(cls, source, **kwargs):
+        return cls._load_from_source(pd.read_parquet, source, **kwargs)
+
+    @classmethod
+    def from_feather(cls, source, **kwargs):
+        return cls._load_from_source(pd.read_feather, source, **kwargs)
+
+    @classmethod
+    def from_hdf(cls, source, **kwargs):
+        return cls._load_from_source(pd.read_hdf, source, **kwargs)
+
+    @classmethod
+    def from_json(cls, source, **kwargs):
+        return cls._load_from_source(pd.read_json, source, **kwargs)
+
+    @classmethod
+    def from_pickle(cls, source, **kwargs):
+        return cls._load_from_source(pd.read_pickle, source, **kwargs)
+
+    @classmethod
+    def from_dataframe(
+        cls,
+        df: pd.DataFrame,
+        init_columns: Optional[Iterable[str]] = None,
+        param_columns: Optional[Iterable[str]] = None,
+        visit_column: str = "visit",
+        reward_column: str = "reward",
+        state_column: str = "state",
+    ):
+        table = DefaultFactoryDict(default_factory=ResultsRegistry)
+        init_columns = init_columns or []
+        param_columns = param_columns or []
+        for state, state_table in df.sort_values(visit_column).groupby(state_column):
+            rewards = state_table[reward_column]
+            init_conds = state_table[init_columns].values
+            params = state_table[param_columns].values
+            table[state].extend(zip(rewards, init_conds, params))
+            ...
+
+        colnames = [reward_column] + list(init_columns) + list(param_columns)
+        return cls(results_colnames=colnames, table=table)
+
     def to_dataframe(self):
         data = {
             state: pd.DataFrame([v.unpack() for v in res], columns=self.columns)
             for state, res in self.table.items()
         }
         df = pd.concat(data, names=["state", "visit"])
         df = df.reset_index(level="visit")
@@ -118,166 +274,7 @@
         self.to_dataframe().to_csv(fname, index=True, **kwargs)
 
     def to_parquet(self, fname, **kwargs):
         self.to_dataframe().to_parquet(fname, index=True, **kwargs)
 
     def to_hdf(self, fname, **kwargs):
         self.to_dataframe().to_hdf(fname, index=True, **kwargs)
-
-
-class TableBuffer(TranspositionTable):
-    """A buffer for storing results of MCTS with stochastic playouts.
-    Results are stored the same as TranspositionTable, but when the buffer reaches
-    a certain size, it is flushed to disk to periodically save results."""
-
-    def __init__(
-        self,
-        columns: Iterable[str],
-        save_dir: Path,
-        maxsize: int = 1000,
-        extension: str = "parquet",
-        save_kwargs: dict = None,
-        **kwargs,
-    ):
-        super().__init__(columns, **kwargs)
-        self.maxsize = maxsize
-        self.extension = extension
-        self.flush_counter = 0
-        self.save_dir = Path(save_dir)
-        self.save_kwargs = save_kwargs or {}
-
-    def __setitem__(self, state_visit, value):
-        super().__setitem__(state_visit, value)
-        if len(self) >= self.maxsize:
-            self.flush()
-
-    def clear(self):
-        self.table = dict()
-
-    def flush(self, extension: str = None, **kwargs):
-        """Save buffer to disk, clear buffer, and increment flush counter."""
-        extension = extension or self.extension
-        filename = self.save_dir.joinpath(f"{self.flush_counter}.{extension}")
-        kw = kwargs | self.save_kwargs
-        if extension == "csv":
-            self.to_csv(filename, **kw)
-        elif extension == "parquet":
-            self.to_parquet(filename, **kw)
-        elif extension == "hdf":
-            self.to_hdf(filename, **kw)
-        else:
-            raise ValueError(f"Unknown file extension {extension}")
-
-        self.flush_counter += 1
-        self.clear()
-
-    def reset(self, flush: bool = False, **kwargs):
-        if flush:
-            self.flush()
-        else:
-            self.clear()
-        self.flush_counter = 0
-
-
-class DefaultFactoryDict(dict):
-    """Similar to a defaultdict, but the default value is a function of the key."""
-
-    def __init__(self, *args, default_factory=None, **kwargs):
-        if default_factory is None:
-            raise ValueError("Must provide a default_factory")
-        super().__init__(*args, **kwargs)
-        self._default_factory = default_factory
-
-    def __missing__(self, key):
-        self[key] = self._default_factory(key)
-        return self[key]
-
-
-class ParallelTree(CircuiTree):
-    def __init__(
-        self,
-        *args,
-        model_factory: Optional[Callable] = None,
-        model_table: Optional[DefaultFactoryDict] = None,
-        transposition_table: Optional[TranspositionTable | bool] = None,
-        columns: Optional[Iterable[str]] = None,
-        buffer: Optional[TableBuffer | bool] = None,
-        save_dir: Optional[Path] = None,
-        maxsize: int = 1000,
-        extension: str = "parquet",
-        save_kwargs: dict = None,
-        counter: Counter = None,
-        table_lock: Any = None,
-        **kwargs,
-    ):
-        super().__init__(*args, **kwargs)
-        if model_table is None:
-            self._model_table = DefaultFactoryDict(default_factory=model_factory)
-        else:
-            self._model_table = model_table
-
-        if transposition_table is False:
-            self._transposition_table = None
-        elif transposition_table is None:
-            self._transposition_table = TranspositionTable(results_colnames=columns)
-        else:
-            self._transposition_table = transposition_table
-
-        if buffer is False:
-            self._buffer = None
-        elif buffer is None:
-            if columns is None or save_dir is None:
-                raise ValueError("Must provide a save_dir for buffer")
-            self._buffer = TableBuffer(
-                columns=columns,
-                save_dir=save_dir,
-                maxsize=maxsize,
-                extension=extension,
-                save_kwargs=save_kwargs,
-            )
-        else:
-            self._buffer = buffer
-
-        self.visit_counter = Counter(counter)
-
-        if table_lock is None:
-            self._table_lock = threading.Lock()
-        else:
-            self._table_lock = table_lock
-
-    @property
-    def table_lock(self):
-        return self._table_lock
-
-    @property
-    def model_table(self):
-        return self._model_table
-
-    @property
-    def transposition_table(self):
-        return self._transposition_table
-
-    @property
-    def buffer(self):
-        return self._buffer
-
-    def get_reward(self, state) -> float | int:
-        visit_num = self.visit_counter.get(state, 0)
-        state_visit = (state, visit_num)
-        if state_visit in self.transposition_table:
-            reward = self.transposition_table.get_reward(state_visit)
-        else:
-            results = self._compute_results(state)
-
-            # Acquire a lock to prevent race conditions - i.e. multiple threads writing
-            # to the transposition table and buffer table at the same time
-            with self.table_lock:
-                self.transposition_table[state_visit] = results
-                self.buffer[state_visit] = results
-
-            reward = results[0]
-
-        self.visit_counter[state] += 1
-        return reward
-
-    def _compute_results(self, state) -> float | int:
-        raise NotImplementedError
```

### Comparing `circuitree-0.1.2/circuitree/rewards.py` & `circuitree-0.1.3/circuitree/rewards.py`

 * *Files identical despite different names*

### Comparing `circuitree-0.1.2/pyproject.toml` & `circuitree-0.1.3/pyproject.toml`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "circuitree"
-version = "0.1.2"
+version = "0.1.3"
 description = "Genetic circuit design using Monte Carlo tree search"
 authors = ["pranav-bhamidipati <pbhamidi@usc.edu>"]
 license = "GPLv3"
 readme = "README.md"
 
 [tool.poetry.dependencies]
 python = "^3.10"
```

### Comparing `circuitree-0.1.2/setup.py` & `circuitree-0.1.3/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -8,15 +8,15 @@
 {'': ['*']}
 
 install_requires = \
 ['networkx>=3.1,<4.0', 'numpy>=1.23.0,<2.0.0']
 
 setup_kwargs = {
     'name': 'circuitree',
-    'version': '0.1.2',
+    'version': '0.1.3',
     'description': 'Genetic circuit design using Monte Carlo tree search',
     'long_description': '# CircuiTree\nGenetic circuit design using Monte Carlo tree search\n\n## Installation\n\n### From a package repository\nTo install using `pip`:\n\n```pip install circuitree```\n\n### From the GitHub repository\n\nTo install and use `circuitree` from the GitHub source code, first clone the repo into a directory.\n\n```git clone https://github.com/pranav-bhamidipati/circuitree.git[ dir_name]```\n\nThen, you can build the environment using the command-line tool `poetry`. Instructions for installation can be [found here](https://python-poetry.org/). \n\nFrom the main project directory, run `poetry install` to install a virtual environment with `circuitree` installed. The easiest way to use this environment is to run it interactively with `poetry shell`. Alternatively, you can run a command in the virtual environment with `poetry run <command>`. For instance, to launch a Jupyter notebook with `circuitree` pre-loaded, run `poetry run jupyter notebook`. \n\n## Usage\n\nSee the [quick-start demo](examples/quick_start.ipynb).\n',
     'author': 'pranav-bhamidipati',
     'author_email': 'pbhamidi@usc.edu',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'None',
```

### Comparing `circuitree-0.1.2/PKG-INFO` & `circuitree-0.1.3/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: circuitree
-Version: 0.1.2
+Version: 0.1.3
 Summary: Genetic circuit design using Monte Carlo tree search
 License: GPLv3
 Author: pranav-bhamidipati
 Author-email: pbhamidi@usc.edu
 Requires-Python: >=3.10,<4.0
 Classifier: License :: Other/Proprietary License
 Classifier: Programming Language :: Python :: 3
```

