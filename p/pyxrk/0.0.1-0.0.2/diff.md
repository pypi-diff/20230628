# Comparing `tmp/pyxrk-0.0.1.tar.gz` & `tmp/pyxrk-0.0.2.tar.gz`

## Comparing `pyxrk-0.0.1.tar` & `pyxrk-0.0.2.tar`

### file list

```diff
@@ -1,17 +1,22 @@
--rw-r--r--   0        0        0      450 1970-01-01 00:00:00.000000 pyxrk-0.0.1/Cargo.toml
--rw-r--r--   0     1001      123     3091 2023-06-24 14:57:02.000000 pyxrk-0.0.1/.github/workflows/CI.yml
--rw-r--r--   0     1001      123     1441 2023-06-24 14:57:02.000000 pyxrk-0.0.1/.github/workflows/lint.yml
--rw-r--r--   0     1001      123       40 2023-06-24 14:57:02.000000 pyxrk-0.0.1/.gitignore
--rw-r--r--   0     1001      123       14 2023-06-24 14:57:02.000000 pyxrk-0.0.1/.rustfmt.toml
--rw-r--r--   0     1001      123     1067 2023-06-24 14:57:02.000000 pyxrk-0.0.1/LICENSE
--rw-r--r--   0     1001      123      916 2023-06-24 14:57:02.000000 pyxrk-0.0.1/README.md
--rw-r--r--   0     1001      123       10 2023-06-24 14:57:14.000000 pyxrk-0.0.1/dist/pyxrk-0.0.1.tar.gz
--rw-r--r--   0     1001      123      751 2023-06-24 14:57:02.000000 pyxrk-0.0.1/pyproject.toml
--rw-r--r--   0     1001      123     1092 2023-06-24 14:57:02.000000 pyxrk-0.0.1/pyxrk.pyi
--rw-r--r--   0     1001      123     1809 2023-06-24 14:57:02.000000 pyxrk-0.0.1/src/channel.rs
--rw-r--r--   0     1001      123      223 2023-06-24 14:57:02.000000 pyxrk-0.0.1/src/lib.rs
--rw-r--r--   0     1001      123     3613 2023-06-24 14:57:02.000000 pyxrk-0.0.1/src/run.rs
--rw-r--r--   0     1001      123  7358957 2023-06-24 14:57:02.000000 pyxrk-0.0.1/test/data/test.xrk
--rw-r--r--   0     1001      123     4553 2023-06-24 14:57:02.000000 pyxrk-0.0.1/test/test_run.py
--rw-r--r--   0     1001      123    22298 2023-06-24 14:57:02.000000 pyxrk-0.0.1/Cargo.lock
--rw-r--r--   0        0        0     1569 1970-01-01 00:00:00.000000 pyxrk-0.0.1/PKG-INFO
+-rw-r--r--   0        0        0      468 1970-01-01 00:00:00.000000 pyxrk-0.0.2/Cargo.toml
+-rw-r--r--   0     1001      123     3091 2023-06-28 05:04:11.000000 pyxrk-0.0.2/.github/workflows/CI.yml
+-rw-r--r--   0     1001      123     1444 2023-06-28 05:04:11.000000 pyxrk-0.0.2/.github/workflows/lint.yml
+-rw-r--r--   0     1001      123       51 2023-06-28 05:04:11.000000 pyxrk-0.0.2/.gitignore
+-rw-r--r--   0     1001      123       14 2023-06-28 05:04:11.000000 pyxrk-0.0.2/.rustfmt.toml
+-rw-r--r--   0     1001      123     1067 2023-06-28 05:04:11.000000 pyxrk-0.0.2/LICENSE
+-rw-r--r--   0     1001      123     1356 2023-06-28 05:04:11.000000 pyxrk-0.0.2/README.md
+-rw-r--r--   0     1001      123       10 2023-06-28 05:04:20.000000 pyxrk-0.0.2/dist/pyxrk-0.0.2.tar.gz
+-rw-r--r--   0     1001      123      810 2023-06-28 05:04:11.000000 pyxrk-0.0.2/pyproject.toml
+-rw-r--r--   0     1001      123       35 2023-06-28 05:04:11.000000 pyxrk-0.0.2/pyxrk/__init__.py
+-rw-r--r--   0     1001      123        0 2023-06-28 05:04:11.000000 pyxrk-0.0.2/pyxrk/py.typed
+-rw-r--r--   0     1001      123     1254 2023-06-28 05:04:11.000000 pyxrk-0.0.2/pyxrk/pyxrk_raw.pyi
+-rw-r--r--   0     1001      123     2731 2023-06-28 05:04:11.000000 pyxrk-0.0.2/pyxrk/run.py
+-rw-r--r--   0     1001      123     2094 2023-06-28 05:04:11.000000 pyxrk-0.0.2/src/channel.rs
+-rw-r--r--   0     1001      123      238 2023-06-28 05:04:11.000000 pyxrk-0.0.2/src/lib.rs
+-rw-r--r--   0     1001      123     3613 2023-06-28 05:04:11.000000 pyxrk-0.0.2/src/run.rs
+-rw-r--r--   0     1001      123      784 2023-06-28 05:04:11.000000 pyxrk-0.0.2/src/utils.rs
+-rw-r--r--   0     1001      123  7358957 2023-06-28 05:04:11.000000 pyxrk-0.0.2/test/data/test.xrk
+-rw-r--r--   0     1001      123     4852 2023-06-28 05:04:11.000000 pyxrk-0.0.2/test/test_raw_run.py
+-rw-r--r--   0     1001      123      345 2023-06-28 05:04:11.000000 pyxrk-0.0.2/test/test_run.py
+-rw-r--r--   0     1001      123    23320 2023-06-28 05:04:11.000000 pyxrk-0.0.2/Cargo.lock
+-rw-r--r--   0        0        0     2032 1970-01-01 00:00:00.000000 pyxrk-0.0.2/PKG-INFO
```

### Comparing `pyxrk-0.0.1/.github/workflows/CI.yml` & `pyxrk-0.0.2/.github/workflows/CI.yml`

 * *Files identical despite different names*

### Comparing `pyxrk-0.0.1/.github/workflows/lint.yml` & `pyxrk-0.0.2/.github/workflows/lint.yml`

 * *Files 8% similar despite different names*

```diff
@@ -58,9 +58,9 @@
     name: Mypy
     runs-on: ubuntu-latest
     steps:
       - uses: actions/checkout@v3
       - uses: actions/setup-python@v4
         with:
           python-version: '3.x'
-      - run: pip install .[test]
-      - run: mypy .
+      - run: pip install . mypy
+      - run: mypy pyxrk
```

### Comparing `pyxrk-0.0.1/LICENSE` & `pyxrk-0.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `pyxrk-0.0.1/README.md` & `pyxrk-0.0.2/README.md`

 * *Files 22% similar despite different names*

```diff
@@ -1,23 +1,38 @@
 # pyxrk
-Python package for reading .xrk files. It wraps much of the functionality from the rust library [xdrk](https://github.com/bmc-labs/xdrk) while adding some convenience functionality.
+Python package for reading .xrk files. The `Run` class can be used to turn .xrk data files into pyarrow Tables.
 
 ---
 
 Install pyxrk using pip:
 
 ```shell
 $ pip install pyxrk
 ```
 
-To get started with basic usage:
+To load an .xrk file into a pyarrow Table:
+```pycon
+>>> from pyxrk import Run
+>>> run = Run.load("./my_run.xrk")
+>>> run.racer
+'Lewis Hamilton'
+>>> run.to_table()  # pyarrow.Table instance
+>>> # Or for specific laps
+>>> run.get_lap(1).to_table()
+```
+Channel unit information can be found in the arrow table metadata.
+
+---
+
+ The `pyxrk_raw` submodule wraps much of the functionality from the rust library [xdrk](https://github.com/bmc-labs/xdrk) while adding some convenience methods.
+To use the raw submodule for reading .xrk files:
 
 ```pycon
->>> import pyxrk
->>> run = pyxrk.load_run("./my_run.xrk")
+>>> from pyxrk import pyxrk_raw
+>>> run = pyxrk_raw.load_run("./my_run.xrk")
 >>> run.lap_count
 7
 >>> run.racer
 'Lewis Hamilton'
 >>> channel = run.get_channel("GPS Speed")
 >>> channel.unit
 'm/s'
@@ -26,13 +41,13 @@
 >>> for data in channel.data():
 ...     print(data)  # tuple of (time offset, data point)
 ...     break
 ...
 (0.0, 0.1846618503332138)
 ```
 
-In lieau of better API documentation, see `pyxrk.pyi` for full interface and `test/test_run.py` for more example usage.
+In lieau of better API documentation, see `pyxrk_raw.pyi` for full interface and tests for more example usage.
 
 
 ## Compatibility
 
 Currently known to work on Linux and Windows, but not Mac.  Contributions for getting it working on Mac are more than welcome.
```

### Comparing `pyxrk-0.0.1/pyproject.toml` & `pyxrk-0.0.2/pyproject.toml`

 * *Files 23% similar despite different names*

```diff
@@ -7,26 +7,28 @@
 requires-python = ">=3.7"
 readme = "README.md"
 classifiers = [
     "Programming Language :: Rust",
     "Programming Language :: Python :: Implementation :: CPython",
     "Programming Language :: Python :: Implementation :: PyPy",
 ]
+dependencies = ['pyarrow']
 
 [project.optional-dependencies]
 test = [
     'black',
     'isort',
     'mypy',
     'ruff',
     'pytest',
 ]
 
 [tool.maturin]
 features = ["pyo3/extension-module"]
+module-name = "pyxrk.pyxrk_raw"
 
 [tool.black]
 line-length = 88
 target-version = ["py37"]
 include = ".pyi?$"
 
 [tool.ruff]
```

### Comparing `pyxrk-0.0.1/pyxrk.pyi` & `pyxrk-0.0.2/pyxrk/pyxrk_raw.pyi`

 * *Files 10% similar despite different names*

```diff
@@ -1,25 +1,29 @@
 import datetime
 from collections.abc import Iterable, Iterator
 from typing import Tuple
 
+from pyarrow import Array  # type: ignore
+
 class ChannelDataIterator(Iterable):
     def __iter__(self) -> Iterator[Tuple[float, float]]: ...
 
 class Channel:
     name: str
     unit: str
     frequency: float
 
     def sample_count(self) -> int: ...
     def is_empty(self) -> bool: ...
     def sync_with(self, other: "Channel") -> "Channel": ...
     def samples(self) -> list[float]: ...
     def timestamps(self) -> list[float]: ...
     def data(self) -> ChannelDataIterator: ...
+    def get_timestamps_array(self) -> Array: ...
+    def get_samples_array(self) -> Array: ...
 
 class Run:
     lap_count: int
     championship: str
     track: str
     venue_type: str
     vehicle: str
@@ -28,10 +32,10 @@
     channel_names: list[str]
     channels_count: int
 
     def get_channel_idx(self, channel_name: str) -> int: ...
     def get_channel_unit(self, channel_name: str) -> str: ...
     def get_channel_unit_by_idx(self, idx: int) -> str: ...
     def get_channel(self, channel_name: str, lap: int | None = None) -> Channel: ...
-    def get_channel_by_idx(self, idx: int) -> Channel: ...
+    def get_channel_by_idx(self, idx: int, lap: int | None = None) -> Channel: ...
 
 def load_run(path: str) -> Run: ...
```

### Comparing `pyxrk-0.0.1/src/channel.rs` & `pyxrk-0.0.2/src/channel.rs`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
-use std::{iter::Zip, vec};
-
+use super::utils::to_array;
 use pyo3::{exceptions::PyValueError, prelude::*};
+use std::{iter::Zip, vec};
 use xdrk::Channel;
 
 #[pyclass(name = "Channel")]
 pub struct ChannelPy {
     channel: Channel,
     #[pyo3(get)]
     frequency: f64,
@@ -48,14 +48,21 @@
     pub fn data(&self) -> ChannelDataIterator {
         let data = self.channel.data();
         // Sadly using clone here https://github.com/PyO3/pyo3/issues/1085
         ChannelDataIterator {
             iter: data.clone().into_iter(),
         }
     }
+
+    pub fn get_timestamps_array(&self, py: Python) -> PyResult<PyObject> {
+        to_array("Time", self.timestamps(), py)
+    }
+    pub fn get_samples_array(&self, py: Python) -> PyResult<PyObject> {
+        to_array(self.name(), self.samples(), py)
+    }
 }
 
 impl ChannelPy {
     pub fn new(channel: Channel) -> Self {
         // frquency is static, so only compute it once
         let frequency = channel.frequency();
         Self { channel, frequency }
```

### Comparing `pyxrk-0.0.1/src/run.rs` & `pyxrk-0.0.2/src/run.rs`

 * *Files identical despite different names*

### Comparing `pyxrk-0.0.1/test/data/test.xrk` & `pyxrk-0.0.2/test/data/test.xrk`

 * *Files identical despite different names*

### Comparing `pyxrk-0.0.1/test/test_run.py` & `pyxrk-0.0.2/test/test_raw_run.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,58 +1,60 @@
 import datetime
 
+import pyarrow  # type: ignore
 import pytest
-import pyxrk
+
+from pyxrk import pyxrk_raw
 
 TEST_FILE = "./test/data/test.xrk"
 
 
 def test_load_run():
-    pyxrk.load_run(TEST_FILE)
+    pyxrk_raw.load_run(TEST_FILE)
     with pytest.raises(ValueError, match="does not exist"):
-        pyxrk.load_run("./non-existant-file.xrk")
+        pyxrk_raw.load_run("./non-existant-file.xrk")
 
 
 def test_run_attributes() -> None:
-    run = pyxrk.load_run(TEST_FILE)
+    run = pyxrk_raw.load_run(TEST_FILE)
     assert run.lap_count == 7
     assert run.championship == ""
     assert run.track == "Watkins Glen"
     assert run.venue_type == ""
     assert run.vehicle == "Porsche 981 GT4"
     assert run.racer == "Joe Portela"
     assert run.datetime == datetime.datetime(2023, 5, 11, 16, 5, 9)
 
 
 def test_channel_names() -> None:
-    run = pyxrk.load_run(TEST_FILE)
+    run = pyxrk_raw.load_run(TEST_FILE)
     assert len(run.channel_names) == 57
     assert run.channels_count == 57
     assert run.get_channel_idx("TRQ_LOSS") == 13
     assert run.get_channel_idx("OIL_TEMP") == 42
     assert run.get_channel_idx("GPS Speed") == 46
     assert run.get_channel_idx("GPS Radius") == 56
     with pytest.raises(ValueError, match="Channel not found"):
         run.get_channel_idx("foo")
 
 
 def test_channel_unit() -> None:
-    run = pyxrk.load_run(TEST_FILE)
+    run = pyxrk_raw.load_run(TEST_FILE)
     assert run.get_channel_unit("OIL_TEMP") == "C"
     assert run.get_channel_unit("GPS Speed") == "m/s"
     with pytest.raises(ValueError, match="Channel not found"):
         run.get_channel_unit("foo")
     assert run.get_channel_unit_by_idx(42) == "C"
     assert run.get_channel_unit_by_idx(46) == "m/s"
     with pytest.raises(ValueError, match="Couldn't get channel unit"):
         run.get_channel_unit_by_idx(1000)
 
 
 def test_channel() -> None:
-    run = pyxrk.load_run(TEST_FILE)
+    run = pyxrk_raw.load_run(TEST_FILE)
     oil_temp_channel = run.get_channel("OIL_TEMP")
     assert oil_temp_channel.name == "OIL_TEMP"
     assert oil_temp_channel.unit == "C"
     assert oil_temp_channel.frequency == 2.0
     assert oil_temp_channel.sample_count() == 2511
 
     gps_speed_channel = run.get_channel("GPS Speed")
@@ -78,15 +80,15 @@
 
     synced_trq_loss_channel = trq_loss_channel.sync_with(oil_temp_channel)
     assert synced_trq_loss_channel.frequency == 2.0
     assert synced_trq_loss_channel.sample_count() == 2511
 
 
 def test_channel_lap() -> None:
-    run = pyxrk.load_run(TEST_FILE)
+    run = pyxrk_raw.load_run(TEST_FILE)
     oil_temp_channel = run.get_channel("OIL_TEMP", 2)
     assert oil_temp_channel.name == "OIL_TEMP"
     assert oil_temp_channel.unit == "C"
     assert oil_temp_channel.frequency == 2.0
     assert oil_temp_channel.sample_count() == 255
 
     gps_speed_channel = run.get_channel("GPS Speed", 2)
@@ -108,17 +110,24 @@
 
 
 def test_combo_lap_channels():
     """
     Test that the total sample count is equal to the sum
     of the sample counts from each lap.
     """
-    run = pyxrk.load_run(TEST_FILE)
+    run = pyxrk_raw.load_run(TEST_FILE)
     full_oil_temp_channel = run.get_channel("OIL_TEMP")
     assert full_oil_temp_channel.sample_count() == 2511
 
     lap_oil_temp_sample_count = 0
     for i in range(run.lap_count):
         lap_count = run.get_channel("OIL_TEMP", i).sample_count()
         lap_oil_temp_sample_count += lap_count
 
     assert lap_oil_temp_sample_count == full_oil_temp_channel.sample_count()
+
+
+def test_channel_to_arrow_array():
+    run = pyxrk_raw.load_run(TEST_FILE)
+    channel = run.get_channel("GPS Speed", 2)
+    array = channel.get_samples_array()
+    assert isinstance(array, pyarrow.FloatingPointArray)
```

### Comparing `pyxrk-0.0.1/Cargo.lock` & `pyxrk-0.0.2/Cargo.lock`

 * *Files 5% similar despite different names*

```diff
@@ -14,23 +14,61 @@
 [[package]]
 name = "adler"
 version = "1.0.2"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "f26201604c87b1e01bd3d98f8d5d9a8fcbb815e8cedb41ffccbeb4bf593a35fe"
 
 [[package]]
+name = "ahash"
+version = "0.8.3"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "2c99f64d1e06488f620f932677e24bc6e2897582980441ae90a671415bd7ec2f"
+dependencies = [
+ "cfg-if",
+ "getrandom",
+ "once_cell",
+ "version_check",
+]
+
+[[package]]
+name = "android-tzdata"
+version = "0.1.1"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "e999941b234f3131b00bc13c22d06e8c5ff726d1b6318ac7eb276997bbb4fef0"
+
+[[package]]
 name = "android_system_properties"
 version = "0.1.5"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "819e7219dbd41043ac279b19830f2efc897156490d7fd6ea916720117ee66311"
 dependencies = [
  "libc",
 ]
 
 [[package]]
+name = "arrow2"
+version = "0.17.2"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "15ae0428d69ab31d7b2adad22a752d6f11fef2e901d2262d0cad4f5cb08b7093"
+dependencies = [
+ "ahash",
+ "bytemuck",
+ "chrono",
+ "dyn-clone",
+ "either",
+ "ethnum",
+ "foreign_vec",
+ "getrandom",
+ "hash_hasher",
+ "num-traits",
+ "rustc_version",
+ "simdutf8",
+]
+
+[[package]]
 name = "autocfg"
 version = "1.1.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "d468802bab17cbc0cc575e9b053f41e72aa36bfa6b7f55e3529ffa43161b97fa"
 
 [[package]]
 name = "backtrace"
@@ -56,34 +94,54 @@
 [[package]]
 name = "bumpalo"
 version = "3.13.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "a3e2c3daef883ecc1b5d58c15adae93470a91d425f3532ba1695849656af3fc1"
 
 [[package]]
+name = "bytemuck"
+version = "1.13.1"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "17febce684fd15d89027105661fec94afb475cb995fbc59d2865198446ba2eea"
+dependencies = [
+ "bytemuck_derive",
+]
+
+[[package]]
+name = "bytemuck_derive"
+version = "1.4.1"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "fdde5c9cd29ebd706ce1b35600920a33550e402fc998a2e53ad3b42c3c47a192"
+dependencies = [
+ "proc-macro2",
+ "quote",
+ "syn 2.0.22",
+]
+
+[[package]]
 name = "cc"
 version = "1.0.79"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "50d30906286121d95be3d479533b458f87493b30a4b5f79a607db8f5d11aa91f"
 
 [[package]]
 name = "cfg-if"
 version = "1.0.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "baf1de4339761588bc0619e3cbc0120ee582ebb74b53b4efbf79117bd2da40fd"
 
 [[package]]
 name = "chrono"
-version = "0.4.24"
+version = "0.4.26"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "4e3c5919066adf22df73762e50cffcde3a758f2a848b113b586d1f86728b673b"
+checksum = "ec837a71355b28f6556dbd569b37b3f363091c0bd4b2e735674521b4c5fd9bc5"
 dependencies = [
+ "android-tzdata",
  "iana-time-zone",
  "js-sys",
- "num-integer",
  "num-traits",
  "time",
  "wasm-bindgen",
  "winapi",
 ]
 
 [[package]]
@@ -116,46 +174,89 @@
 [[package]]
 name = "core-foundation-sys"
 version = "0.8.4"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "e496a50fda8aacccc86d7529e2c1e0892dbd0f898a6b5645b5561b89c3210efa"
 
 [[package]]
+name = "dyn-clone"
+version = "1.0.11"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "68b0cf012f1230e43cd00ebb729c6bb58707ecfa8ad08b52ef3a4ccd2697fc30"
+
+[[package]]
+name = "either"
+version = "1.8.1"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "7fcaabb2fef8c910e7f4c7ce9f67a1283a1715879a7c230ca9d6d1ae31f16d91"
+
+[[package]]
+name = "ethnum"
+version = "1.3.2"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "0198b9d0078e0f30dedc7acbb21c974e838fc8fae3ee170128658a98cb2c1c04"
+
+[[package]]
 name = "eyre"
 version = "0.6.8"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "4c2b6b5a29c02cdc822728b7d7b8ae1bab3e3b05d44522770ddd49722eeac7eb"
 dependencies = [
  "indenter",
  "once_cell",
 ]
 
 [[package]]
+name = "foreign_vec"
+version = "0.1.0"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "ee1b05cbd864bcaecbd3455d6d967862d446e4ebfc3c2e5e5b9841e53cba6673"
+
+[[package]]
+name = "getrandom"
+version = "0.2.10"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "be4136b2a15dd319360be1c07d9933517ccf0be8f16bf62a3bee4f0d618df427"
+dependencies = [
+ "cfg-if",
+ "js-sys",
+ "libc",
+ "wasi 0.11.0+wasi-snapshot-preview1",
+ "wasm-bindgen",
+]
+
+[[package]]
 name = "getset"
 version = "0.1.2"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "e45727250e75cc04ff2846a66397da8ef2b3db8e40e0cef4df67950a07621eb9"
 dependencies = [
  "proc-macro-error",
  "proc-macro2",
  "quote",
  "syn 1.0.109",
 ]
 
 [[package]]
 name = "gimli"
-version = "0.27.2"
+version = "0.27.3"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "ad0a93d233ebf96623465aad4046a8d3aa4da22d4f4beba5388838c8a434bbb4"
+checksum = "b6c80984affa11d98d1b88b66ac8853f143217b399d3c74116778ff8fdb4ed2e"
+
+[[package]]
+name = "hash_hasher"
+version = "2.0.3"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "74721d007512d0cb3338cd20f0654ac913920061a4c4d0d8708edb3f2a698c0c"
 
 [[package]]
 name = "iana-time-zone"
-version = "0.1.56"
+version = "0.1.57"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "0722cd7114b7de04316e7ea5456a0bbb20e4adb46fd27a3697adb812cff0f37c"
+checksum = "2fad5b825842d2b38bd206f3e81d6957625fd7f0a361e345c30e01a0ae2dd613"
 dependencies = [
  "android_system_properties",
  "core-foundation-sys",
  "iana-time-zone-haiku",
  "js-sys",
  "wasm-bindgen",
  "windows",
@@ -180,109 +281,96 @@
 name = "indoc"
 version = "1.0.9"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "bfa799dd5ed20a7e349f3b4639aa80d74549c81716d9ec4f994c9b5815598306"
 
 [[package]]
 name = "js-sys"
-version = "0.3.63"
+version = "0.3.64"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "2f37a4a5928311ac501dee68b3c7613a1037d0edb30c8e5427bd832d55d1b790"
+checksum = "c5f195fe497f702db0f318b07fdd68edb16955aed830df8363d837542f8f935a"
 dependencies = [
  "wasm-bindgen",
 ]
 
 [[package]]
 name = "lazy_static"
 version = "1.4.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "e2abad23fbc42b3700f2f279844dc832adb2b2eb069b2df918f455c4e18cc646"
 
 [[package]]
 name = "libc"
-version = "0.2.144"
+version = "0.2.147"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "2b00cc1c228a6782d0f076e7b232802e0c5689d41bb5df366f2a6b6621cfdfe1"
+checksum = "b4668fb0ea861c1df094127ac5f1da3409a82116a4ba74fca2e58ef927159bb3"
 
 [[package]]
 name = "lock_api"
-version = "0.4.9"
+version = "0.4.10"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "435011366fe56583b16cf956f9df0095b405b82d76425bc8981c0e22e60ec4df"
+checksum = "c1cc9717a20b1bb222f333e6a92fd32f7d8a18ddc5a3191a11af45dcbf4dcd16"
 dependencies = [
  "autocfg",
  "scopeguard",
 ]
 
 [[package]]
 name = "log"
-version = "0.4.17"
+version = "0.4.19"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "abb12e687cfb44aa40f41fc3978ef76448f9b6038cad6aef4259d3c095a2382e"
-dependencies = [
- "cfg-if",
-]
+checksum = "b06a4cde4c0f271a446782e3eff8de789548ce57dbc8eca9292c27f4a42004b4"
 
 [[package]]
 name = "memchr"
 version = "2.5.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "2dffe52ecf27772e601905b7522cb4ef790d2cc203488bbd0e2fe85fcb74566d"
 
 [[package]]
 name = "memoffset"
-version = "0.8.0"
+version = "0.9.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "d61c719bcfbcf5d62b3a09efa6088de8c54bc0bfcd3ea7ae39fcc186108b8de1"
+checksum = "5a634b1c61a95585bd15607c6ab0c4e5b226e695ff2800ba0cdccddf208c406c"
 dependencies = [
  "autocfg",
 ]
 
 [[package]]
 name = "miniz_oxide"
 version = "0.6.2"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "b275950c28b37e794e8c55d88aeb5e139d0ce23fdbbeda68f8d7174abdf9e8fa"
 dependencies = [
  "adler",
 ]
 
 [[package]]
-name = "num-integer"
-version = "0.1.45"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "225d3389fb3509a24c93f5c29eb6bde2586b98d9f016636dff58d7c6f7569cd9"
-dependencies = [
- "autocfg",
- "num-traits",
-]
-
-[[package]]
 name = "num-traits"
 version = "0.2.15"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "578ede34cf02f8924ab9447f50c28075b4d3e5b269972345e7e0372b38c6cdcd"
 dependencies = [
  "autocfg",
 ]
 
 [[package]]
 name = "object"
-version = "0.30.3"
+version = "0.30.4"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "ea86265d3d3dcb6a27fc51bd29a4bf387fae9d2986b823079d4986af253eb439"
+checksum = "03b4680b86d9cfafba8fc491dc9b6df26b68cf40e9e6cd73909194759a63c385"
 dependencies = [
  "memchr",
 ]
 
 [[package]]
 name = "once_cell"
-version = "1.17.1"
+version = "1.18.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "b7e5500299e16ebb147ae15a00a942af264cf3688f47923b8fc2cd5858f23ad3"
+checksum = "dd8b5dd2ae5ed71462c540258bedcb51965123ad7e7ccf4b9a8cafaa4a63576d"
 
 [[package]]
 name = "owo-colors"
 version = "1.3.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "2386b4ebe91c2f7f51082d4cefa145d030e33a1842a96b12e4885cc3c01f7a55"
 
@@ -294,23 +382,23 @@
 dependencies = [
  "lock_api",
  "parking_lot_core",
 ]
 
 [[package]]
 name = "parking_lot_core"
-version = "0.9.7"
+version = "0.9.8"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "9069cbb9f99e3a5083476ccb29ceb1de18b9118cafa53e90c9551235de2b9521"
+checksum = "93f00c865fe7cabf650081affecd3871070f26767e7b2070a3ffae14c654b447"
 dependencies = [
  "cfg-if",
  "libc",
  "redox_syscall",
  "smallvec",
- "windows-sys",
+ "windows-targets",
 ]
 
 [[package]]
 name = "pin-project-lite"
 version = "0.2.9"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "e0a7ae3ac2f1173085d398531c705756c94a4c56843785df85a60c1a0afac116"
@@ -337,26 +425,26 @@
  "proc-macro2",
  "quote",
  "version_check",
 ]
 
 [[package]]
 name = "proc-macro2"
-version = "1.0.58"
+version = "1.0.63"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "fa1fb82fc0c281dd9671101b66b771ebbe1eaf967b96ac8740dcba4b70005ca8"
+checksum = "7b368fba921b0dce7e60f5e04ec15e565b3303972b42bcfde1d0713b881959eb"
 dependencies = [
  "unicode-ident",
 ]
 
 [[package]]
 name = "pyo3"
-version = "0.18.3"
+version = "0.19.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "e3b1ac5b3731ba34fdaa9785f8d74d17448cd18f30cf19e0c7e7b1fdb5272109"
+checksum = "cffef52f74ec3b1a1baf295d9b8fcc3070327aefc39a6d00656b13c1d0b8885c"
 dependencies = [
  "cfg-if",
  "chrono",
  "indoc",
  "libc",
  "memoffset",
  "parking_lot",
@@ -364,124 +452,146 @@
  "pyo3-ffi",
  "pyo3-macros",
  "unindent",
 ]
 
 [[package]]
 name = "pyo3-build-config"
-version = "0.18.3"
+version = "0.19.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "9cb946f5ac61bb61a5014924910d936ebd2b23b705f7a4a3c40b05c720b079a3"
+checksum = "713eccf888fb05f1a96eb78c0dbc51907fee42b3377272dc902eb38985f418d5"
 dependencies = [
  "once_cell",
  "target-lexicon",
 ]
 
 [[package]]
 name = "pyo3-ffi"
-version = "0.18.3"
+version = "0.19.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "fd4d7c5337821916ea2a1d21d1092e8443cf34879e53a0ac653fbb98f44ff65c"
+checksum = "5b2ecbdcfb01cbbf56e179ce969a048fd7305a66d4cdf3303e0da09d69afe4c3"
 dependencies = [
  "libc",
  "pyo3-build-config",
 ]
 
 [[package]]
 name = "pyo3-macros"
-version = "0.18.3"
+version = "0.19.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "a9d39c55dab3fc5a4b25bbd1ac10a2da452c4aca13bb450f22818a002e29648d"
+checksum = "b78fdc0899f2ea781c463679b20cb08af9247febc8d052de941951024cd8aea0"
 dependencies = [
  "proc-macro2",
  "pyo3-macros-backend",
  "quote",
  "syn 1.0.109",
 ]
 
 [[package]]
 name = "pyo3-macros-backend"
-version = "0.18.3"
+version = "0.19.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "97daff08a4c48320587b5224cc98d609e3c27b6d437315bd40b605c98eeb5918"
+checksum = "60da7b84f1227c3e2fe7593505de274dcf4c8928b4e0a1c23d551a14e4e80a0f"
 dependencies = [
  "proc-macro2",
  "quote",
  "syn 1.0.109",
 ]
 
 [[package]]
 name = "pyxrk"
-version = "0.0.1"
+version = "0.0.2"
 dependencies = [
+ "arrow2",
  "chrono",
  "pyo3",
  "xdrk",
 ]
 
 [[package]]
 name = "quote"
-version = "1.0.27"
+version = "1.0.28"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "8f4f29d145265ec1c483c7c654450edde0bfe043d3938d6972630663356d9500"
+checksum = "1b9ab9c7eadfd8df19006f1cf1a4aed13540ed5cbc047010ece5826e10825488"
 dependencies = [
  "proc-macro2",
 ]
 
 [[package]]
 name = "redox_syscall"
-version = "0.2.16"
+version = "0.3.5"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "fb5a58c1855b4b6819d59012155603f0b22ad30cad752600aadfcb695265519a"
+checksum = "567664f262709473930a4bf9e51bf2ebf3348f2e748ccc50dea20646858f8f29"
 dependencies = [
  "bitflags",
 ]
 
 [[package]]
 name = "rustc-demangle"
 version = "0.1.23"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "d626bb9dae77e28219937af045c257c28bfd3f69333c512553507f5f9798cb76"
 
 [[package]]
+name = "rustc_version"
+version = "0.4.0"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "bfa0f585226d2e68097d4f95d113b15b83a82e819ab25717ec0590d9584ef366"
+dependencies = [
+ "semver",
+]
+
+[[package]]
 name = "scopeguard"
 version = "1.1.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "d29ab0c6d3fc0ee92fe66e2d99f700eab17a8d57d1c1d3b748380fb20baa78cd"
 
 [[package]]
+name = "semver"
+version = "1.0.17"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "bebd363326d05ec3e2f532ab7660680f3b02130d780c299bca73469d521bc0ed"
+
+[[package]]
 name = "serde"
-version = "1.0.163"
+version = "1.0.164"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "2113ab51b87a539ae008b5c6c02dc020ffa39afd2d83cffcb3f4eb2722cebec2"
+checksum = "9e8c8cf938e98f769bc164923b06dce91cea1751522f46f8466461af04c9027d"
 dependencies = [
  "serde_derive",
 ]
 
 [[package]]
 name = "serde_derive"
-version = "1.0.163"
+version = "1.0.164"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "8c805777e3930c8883389c602315a24224bcc738b63905ef87cd1420353ea93e"
+checksum = "d9735b638ccc51c28bf6914d90a2e9725b377144fc612c49a611fddd1b631d68"
 dependencies = [
  "proc-macro2",
  "quote",
- "syn 2.0.16",
+ "syn 2.0.22",
 ]
 
 [[package]]
 name = "sharded-slab"
 version = "0.1.4"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "900fba806f70c630b0a382d0d825e17a0f19fcd059a2ade1ff237bcddf446b31"
 dependencies = [
  "lazy_static",
 ]
 
 [[package]]
+name = "simdutf8"
+version = "0.1.4"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "f27f6278552951f1f2b8cf9da965d10969b2efdea95a6ec47987ab46edfe263a"
+
+[[package]]
 name = "smallvec"
 version = "1.10.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "a507befe795404456341dfab10cef66ead4c041f62b8b11bbb92bffe5d0953e0"
 
 [[package]]
 name = "syn"
@@ -492,28 +602,28 @@
  "proc-macro2",
  "quote",
  "unicode-ident",
 ]
 
 [[package]]
 name = "syn"
-version = "2.0.16"
+version = "2.0.22"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "a6f671d4b5ffdb8eadec19c0ae67fe2639df8684bd7bc4b83d986b8db549cf01"
+checksum = "2efbeae7acf4eabd6bcdcbd11c92f45231ddda7539edc7806bd1a04a03b24616"
 dependencies = [
  "proc-macro2",
  "quote",
  "unicode-ident",
 ]
 
 [[package]]
 name = "target-lexicon"
-version = "0.12.7"
+version = "0.12.8"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "fd1ba337640d60c3e96bc6f0638a939b9c9a7f2c316a1598c279828b3d1dc8c5"
+checksum = "1b1c7f239eb94671427157bd93b3694320f3668d4e1eff08c7285366fd777fac"
 
 [[package]]
 name = "thread_local"
 version = "1.1.7"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "3fdd6f064ccff2d6567adcb3873ca630700f00b5ad3f060c25b5dcfd9a4ce152"
 dependencies = [
@@ -524,15 +634,15 @@
 [[package]]
 name = "time"
 version = "0.1.45"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "1b797afad3f312d1c66a56d11d0316f916356d11bd158fbc6ca6389ff6bf805a"
 dependencies = [
  "libc",
- "wasi",
+ "wasi 0.10.0+wasi-snapshot-preview1",
  "winapi",
 ]
 
 [[package]]
 name = "tracing"
 version = "0.1.37"
 source = "registry+https://github.com/rust-lang/crates.io-index"
@@ -542,21 +652,21 @@
  "pin-project-lite",
  "tracing-attributes",
  "tracing-core",
 ]
 
 [[package]]
 name = "tracing-attributes"
-version = "0.1.24"
+version = "0.1.26"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "0f57e3ca2a01450b1a921183a9c9cbfda207fd822cef4ccb00a65402cbba7a74"
+checksum = "5f4f31f56159e98206da9efd823404b79b6ef3143b4a7ab76e67b1751b25a4ab"
 dependencies = [
  "proc-macro2",
  "quote",
- "syn 2.0.16",
+ "syn 2.0.22",
 ]
 
 [[package]]
 name = "tracing-core"
 version = "0.1.31"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "0955b8137a1df6f1a2e9a37d8a6656291ff0297c1a97c24e0d8425fe2312f79a"
@@ -613,66 +723,72 @@
 [[package]]
 name = "wasi"
 version = "0.10.0+wasi-snapshot-preview1"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "1a143597ca7c7793eff794def352d41792a93c481eb1042423ff7ff72ba2c31f"
 
 [[package]]
+name = "wasi"
+version = "0.11.0+wasi-snapshot-preview1"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "9c8d87e72b64a3b4db28d11ce29237c246188f4f51057d65a7eab63b7987e423"
+
+[[package]]
 name = "wasm-bindgen"
-version = "0.2.86"
+version = "0.2.87"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "5bba0e8cb82ba49ff4e229459ff22a191bbe9a1cb3a341610c9c33efc27ddf73"
+checksum = "7706a72ab36d8cb1f80ffbf0e071533974a60d0a308d01a5d0375bf60499a342"
 dependencies = [
  "cfg-if",
  "wasm-bindgen-macro",
 ]
 
 [[package]]
 name = "wasm-bindgen-backend"
-version = "0.2.86"
+version = "0.2.87"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "19b04bc93f9d6bdee709f6bd2118f57dd6679cf1176a1af464fca3ab0d66d8fb"
+checksum = "5ef2b6d3c510e9625e5fe6f509ab07d66a760f0885d858736483c32ed7809abd"
 dependencies = [
  "bumpalo",
  "log",
  "once_cell",
  "proc-macro2",
  "quote",
- "syn 2.0.16",
+ "syn 2.0.22",
  "wasm-bindgen-shared",
 ]
 
 [[package]]
 name = "wasm-bindgen-macro"
-version = "0.2.86"
+version = "0.2.87"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "14d6b024f1a526bb0234f52840389927257beb670610081360e5a03c5df9c258"
+checksum = "dee495e55982a3bd48105a7b947fd2a9b4a8ae3010041b9e0faab3f9cd028f1d"
 dependencies = [
  "quote",
  "wasm-bindgen-macro-support",
 ]
 
 [[package]]
 name = "wasm-bindgen-macro-support"
-version = "0.2.86"
+version = "0.2.87"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "e128beba882dd1eb6200e1dc92ae6c5dbaa4311aa7bb211ca035779e5efc39f8"
+checksum = "54681b18a46765f095758388f2d0cf16eb8d4169b639ab575a8f5693af210c7b"
 dependencies = [
  "proc-macro2",
  "quote",
- "syn 2.0.16",
+ "syn 2.0.22",
  "wasm-bindgen-backend",
  "wasm-bindgen-shared",
 ]
 
 [[package]]
 name = "wasm-bindgen-shared"
-version = "0.2.86"
+version = "0.2.87"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "ed9d5b4305409d1fc9482fee2d7f9bcbf24b3972bf59817ef757e23982242a93"
+checksum = "ca6ad05a4870b2bf5fe995117d3728437bd27d7cd5f06f13c17443ef369775a1"
 
 [[package]]
 name = "winapi"
 version = "0.3.9"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "5c839a674fcd7a98952e593242ea400abe93992746761e38641405d28b00f419"
 dependencies = [
@@ -694,136 +810,70 @@
 
 [[package]]
 name = "windows"
 version = "0.48.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "e686886bc078bc1b0b600cac0147aadb815089b6e4da64016cbd754b6342700f"
 dependencies = [
- "windows-targets 0.48.0",
-]
-
-[[package]]
-name = "windows-sys"
-version = "0.45.0"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "75283be5efb2831d37ea142365f009c02ec203cd29a3ebecbc093d52315b66d0"
-dependencies = [
- "windows-targets 0.42.2",
-]
-
-[[package]]
-name = "windows-targets"
-version = "0.42.2"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "8e5180c00cd44c9b1c88adb3693291f1cd93605ded80c250a75d472756b4d071"
-dependencies = [
- "windows_aarch64_gnullvm 0.42.2",
- "windows_aarch64_msvc 0.42.2",
- "windows_i686_gnu 0.42.2",
- "windows_i686_msvc 0.42.2",
- "windows_x86_64_gnu 0.42.2",
- "windows_x86_64_gnullvm 0.42.2",
- "windows_x86_64_msvc 0.42.2",
+ "windows-targets",
 ]
 
 [[package]]
 name = "windows-targets"
 version = "0.48.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "7b1eb6f0cd7c80c79759c929114ef071b87354ce476d9d94271031c0497adfd5"
 dependencies = [
- "windows_aarch64_gnullvm 0.48.0",
- "windows_aarch64_msvc 0.48.0",
- "windows_i686_gnu 0.48.0",
- "windows_i686_msvc 0.48.0",
- "windows_x86_64_gnu 0.48.0",
- "windows_x86_64_gnullvm 0.48.0",
- "windows_x86_64_msvc 0.48.0",
+ "windows_aarch64_gnullvm",
+ "windows_aarch64_msvc",
+ "windows_i686_gnu",
+ "windows_i686_msvc",
+ "windows_x86_64_gnu",
+ "windows_x86_64_gnullvm",
+ "windows_x86_64_msvc",
 ]
 
 [[package]]
 name = "windows_aarch64_gnullvm"
-version = "0.42.2"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "597a5118570b68bc08d8d59125332c54f1ba9d9adeedeef5b99b02ba2b0698f8"
-
-[[package]]
-name = "windows_aarch64_gnullvm"
 version = "0.48.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "91ae572e1b79dba883e0d315474df7305d12f569b400fcf90581b06062f7e1bc"
 
 [[package]]
 name = "windows_aarch64_msvc"
-version = "0.42.2"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "e08e8864a60f06ef0d0ff4ba04124db8b0fb3be5776a5cd47641e942e58c4d43"
-
-[[package]]
-name = "windows_aarch64_msvc"
 version = "0.48.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "b2ef27e0d7bdfcfc7b868b317c1d32c641a6fe4629c171b8928c7b08d98d7cf3"
 
 [[package]]
 name = "windows_i686_gnu"
-version = "0.42.2"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "c61d927d8da41da96a81f029489353e68739737d3beca43145c8afec9a31a84f"
-
-[[package]]
-name = "windows_i686_gnu"
 version = "0.48.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "622a1962a7db830d6fd0a69683c80a18fda201879f0f447f065a3b7467daa241"
 
 [[package]]
 name = "windows_i686_msvc"
-version = "0.42.2"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "44d840b6ec649f480a41c8d80f9c65108b92d89345dd94027bfe06ac444d1060"
-
-[[package]]
-name = "windows_i686_msvc"
 version = "0.48.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "4542c6e364ce21bf45d69fdd2a8e455fa38d316158cfd43b3ac1c5b1b19f8e00"
 
 [[package]]
 name = "windows_x86_64_gnu"
-version = "0.42.2"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "8de912b8b8feb55c064867cf047dda097f92d51efad5b491dfb98f6bbb70cb36"
-
-[[package]]
-name = "windows_x86_64_gnu"
 version = "0.48.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "ca2b8a661f7628cbd23440e50b05d705db3686f894fc9580820623656af974b1"
 
 [[package]]
 name = "windows_x86_64_gnullvm"
-version = "0.42.2"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "26d41b46a36d453748aedef1486d5c7a85db22e56aff34643984ea85514e94a3"
-
-[[package]]
-name = "windows_x86_64_gnullvm"
 version = "0.48.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "7896dbc1f41e08872e9d5e8f8baa8fdd2677f29468c4e156210174edc7f7b953"
 
 [[package]]
 name = "windows_x86_64_msvc"
-version = "0.42.2"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "9aec5da331524158c6d1a4ac0ab1541149c0b9505fde06423b02f5ef0106b9f0"
-
-[[package]]
-name = "windows_x86_64_msvc"
 version = "0.48.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "1a515f5799fe4961cb532f983ce2b23082366b898e52ffbce459c86f67c8378a"
 
 [[package]]
 name = "xdrk"
 version = "1.0.0"
```

### Comparing `pyxrk-0.0.1/PKG-INFO` & `pyxrk-0.0.2/PKG-INFO`

 * *Files 15% similar despite different names*

```diff
@@ -1,41 +1,57 @@
 Metadata-Version: 2.1
 Name: pyxrk
-Version: 0.0.1
+Version: 0.0.2
 Classifier: Programming Language :: Rust
 Classifier: Programming Language :: Python :: Implementation :: CPython
 Classifier: Programming Language :: Python :: Implementation :: PyPy
+Requires-Dist: pyarrow
 Requires-Dist: black ; extra == 'test'
 Requires-Dist: isort ; extra == 'test'
 Requires-Dist: mypy ; extra == 'test'
 Requires-Dist: ruff ; extra == 'test'
 Requires-Dist: pytest ; extra == 'test'
 Provides-Extra: test
 License-File: LICENSE
 Author: Joe Portela <jportela14@gmail.com>
 Author-email: Joe Portela <jportela14@gmail.com>
 Requires-Python: >=3.7
 Description-Content-Type: text/markdown; charset=UTF-8; variant=GFM
 
 # pyxrk
-Python package for reading .xrk files. It wraps much of the functionality from the rust library [xdrk](https://github.com/bmc-labs/xdrk) while adding some convenience functionality.
+Python package for reading .xrk files. The `Run` class can be used to turn .xrk data files into pyarrow Tables.
 
 ---
 
 Install pyxrk using pip:
 
 ```shell
 $ pip install pyxrk
 ```
 
-To get started with basic usage:
+To load an .xrk file into a pyarrow Table:
+```pycon
+>>> from pyxrk import Run
+>>> run = Run.load("./my_run.xrk")
+>>> run.racer
+'Lewis Hamilton'
+>>> run.to_table()  # pyarrow.Table instance
+>>> # Or for specific laps
+>>> run.get_lap(1).to_table()
+```
+Channel unit information can be found in the arrow table metadata.
+
+---
+
+ The `pyxrk_raw` submodule wraps much of the functionality from the rust library [xdrk](https://github.com/bmc-labs/xdrk) while adding some convenience methods.
+To use the raw submodule for reading .xrk files:
 
 ```pycon
->>> import pyxrk
->>> run = pyxrk.load_run("./my_run.xrk")
+>>> from pyxrk import pyxrk_raw
+>>> run = pyxrk_raw.load_run("./my_run.xrk")
 >>> run.lap_count
 7
 >>> run.racer
 'Lewis Hamilton'
 >>> channel = run.get_channel("GPS Speed")
 >>> channel.unit
 'm/s'
@@ -44,13 +60,13 @@
 >>> for data in channel.data():
 ...     print(data)  # tuple of (time offset, data point)
 ...     break
 ...
 (0.0, 0.1846618503332138)
 ```
 
-In lieau of better API documentation, see `pyxrk.pyi` for full interface and `test/test_run.py` for more example usage.
+In lieau of better API documentation, see `pyxrk_raw.pyi` for full interface and tests for more example usage.
 
 
 ## Compatibility
 
 Currently known to work on Linux and Windows, but not Mac.  Contributions for getting it working on Mac are more than welcome.
```

