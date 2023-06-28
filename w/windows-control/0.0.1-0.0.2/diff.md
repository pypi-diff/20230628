# Comparing `tmp/windows_control-0.0.1.tar.gz` & `tmp/windows_control-0.0.2.tar.gz`

## Comparing `windows_control-0.0.1.tar` & `windows_control-0.0.2.tar`

### file list

```diff
@@ -1,8 +1,11 @@
--rw-r--r--   0        0        0      634 1970-01-01 00:00:00.000000 windows_control-0.0.1/Cargo.toml
--rw-r--r--   0        0        0       20 2023-05-17 08:59:42.000000 windows_control-0.0.1/.gitignore
--rw-r--r--   0        0        0      233 2023-05-17 10:53:50.000000 windows_control-0.0.1/README.md
--rw-r--r--   0        0        0       34 2023-05-17 09:39:23.000000 windows_control-0.0.1/main.py
--rw-r--r--   0        0        0      608 2023-05-17 10:16:25.000000 windows_control-0.0.1/pyproject.toml
--rw-r--r--   0        0        0     1824 2023-05-17 09:23:43.000000 windows_control-0.0.1/src/lib.rs
--rw-r--r--   0        0        0     7913 2023-05-17 09:19:04.000000 windows_control-0.0.1/Cargo.lock
--rw-r--r--   0        0        0      547 1970-01-01 00:00:00.000000 windows_control-0.0.1/PKG-INFO
+-rw-r--r--   0        0        0      488 1970-01-01 00:00:00.000000 windows_control-0.0.2/Cargo.toml
+-rw-r--r--   0        0        0     2807 2023-06-28 03:33:37.000000 windows_control-0.0.2/.github/workflows/CI.yml
+-rw-r--r--   0        0        0      756 2023-06-28 03:33:37.000000 windows_control-0.0.2/.gitignore
+-rw-r--r--   0        0        0     1936 2023-06-28 08:23:20.000000 windows_control-0.0.2/README.md
+-rw-r--r--   0        0        0      821 2023-06-28 08:30:46.000000 windows_control-0.0.2/justfile
+-rw-r--r--   0        0        0      812 2023-06-28 08:29:56.000000 windows_control-0.0.2/pyproject.toml
+-rw-r--r--   0        0        0       90 2023-06-28 05:39:06.000000 windows_control-0.0.2/src/keyboard/mod.rs
+-rw-r--r--   0        0        0     1201 2023-06-28 05:51:30.000000 windows_control-0.0.2/src/lib.rs
+-rw-r--r--   0        0        0      508 2023-06-28 05:39:46.000000 windows_control-0.0.2/test.py
+-rw-r--r--   0        0        0     7435 2023-06-28 06:00:28.000000 windows_control-0.0.2/Cargo.lock
+-rw-r--r--   0        0        0     2432 1970-01-01 00:00:00.000000 windows_control-0.0.2/PKG-INFO
```

### Comparing `windows_control-0.0.1/Cargo.lock` & `windows_control-0.0.2/Cargo.lock`

 * *Files 20% similar despite different names*

```diff
@@ -17,214 +17,156 @@
 [[package]]
 name = "cfg-if"
 version = "1.0.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "baf1de4339761588bc0619e3cbc0120ee582ebb74b53b4efbf79117bd2da40fd"
 
 [[package]]
-name = "getrandom"
-version = "0.2.9"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "c85e1d9ab2eadba7e5040d4e09cbd6d072b76a557ad64e797c2cb9d4da21d7e4"
-dependencies = [
- "cfg-if",
- "libc",
- "wasi",
-]
-
-[[package]]
 name = "indoc"
 version = "1.0.9"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "bfa799dd5ed20a7e349f3b4639aa80d74549c81716d9ec4f994c9b5815598306"
 
 [[package]]
-name = "instant"
-version = "0.1.12"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "7a5bbe824c507c5da5956355e86a746d82e0e1464f65d862cc5e71da70e94b2c"
-dependencies = [
- "cfg-if",
-]
-
-[[package]]
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
 name = "once_cell"
-version = "1.17.1"
+version = "1.18.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "b7e5500299e16ebb147ae15a00a942af264cf3688f47923b8fc2cd5858f23ad3"
+checksum = "dd8b5dd2ae5ed71462c540258bedcb51965123ad7e7ccf4b9a8cafaa4a63576d"
 
 [[package]]
 name = "parking_lot"
-version = "0.11.2"
+version = "0.12.1"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "7d17b78036a60663b797adeaee46f5c9dfebb86948d1255007a1d6be0271ff99"
+checksum = "3742b2c103b9f06bc9fff0a37ff4912935851bee6d36f3c02bcc755bcfec228f"
 dependencies = [
- "instant",
  "lock_api",
  "parking_lot_core",
 ]
 
 [[package]]
 name = "parking_lot_core"
-version = "0.8.6"
+version = "0.9.8"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "60a2cfe6f0ad2bfc16aefa463b497d5c7a5ecd44a23efa72aa342d90177356dc"
+checksum = "93f00c865fe7cabf650081affecd3871070f26767e7b2070a3ffae14c654b447"
 dependencies = [
  "cfg-if",
- "instant",
  "libc",
  "redox_syscall",
  "smallvec",
- "winapi",
+ "windows-targets",
 ]
 
 [[package]]
-name = "ppv-lite86"
-version = "0.2.17"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "5b40af805b3121feab8a3c29f04d8ad262fa8e0561883e7653e024ae4479e6de"
-
-[[package]]
 name = "proc-macro2"
-version = "1.0.57"
+version = "1.0.63"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "c4ec6d5fe0b140acb27c9a0444118cf55bfbb4e0b259739429abb4521dd67c16"
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
  "indoc",
  "libc",
  "memoffset",
  "parking_lot",
  "pyo3-build-config",
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
  "syn",
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
  "syn",
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
-name = "rand"
-version = "0.8.5"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "34af8d1a0e25924bc5b7c43c079c942339d8f0a8b57c39049bef581b46327404"
-dependencies = [
- "libc",
- "rand_chacha",
- "rand_core",
-]
-
-[[package]]
-name = "rand_chacha"
-version = "0.3.1"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "e6c10a63a0fa32252be49d21e7709d4d4baf8d231c2dbce1eaa8141b9b127d88"
-dependencies = [
- "ppv-lite86",
- "rand_core",
-]
-
-[[package]]
-name = "rand_core"
-version = "0.6.4"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "ec0be4795e2f6a28069bec0b5ff3e2ac9bafc99e6a9a7dc3547996c5c816922c"
-dependencies = [
- "getrandom",
-]
-
-[[package]]
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
 name = "scopeguard"
 version = "1.1.0"
@@ -246,58 +188,86 @@
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
 name = "unicode-ident"
-version = "1.0.8"
+version = "1.0.9"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "e5464a87b239f13a63a501f2701565754bae92d243d4bb7eb12f6d57d2269bf4"
+checksum = "b15811caf2415fb889178633e7724bad2509101cde276048e013b9def5e51fa0"
 
 [[package]]
 name = "unindent"
 version = "0.1.11"
 source = "registry+https://github.com/rust-lang/crates.io-index"
 checksum = "e1766d682d402817b5ac4490b3c3002d91dfa0d22812f341609f97b08757359c"
 
 [[package]]
-name = "wasi"
-version = "0.11.0+wasi-snapshot-preview1"
+name = "windows-targets"
+version = "0.48.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "9c8d87e72b64a3b4db28d11ce29237c246188f4f51057d65a7eab63b7987e423"
-
-[[package]]
-name = "winapi"
-version = "0.3.9"
-source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "5c839a674fcd7a98952e593242ea400abe93992746761e38641405d28b00f419"
+checksum = "7b1eb6f0cd7c80c79759c929114ef071b87354ce476d9d94271031c0497adfd5"
 dependencies = [
- "winapi-i686-pc-windows-gnu",
- "winapi-x86_64-pc-windows-gnu",
+ "windows_aarch64_gnullvm",
+ "windows_aarch64_msvc",
+ "windows_i686_gnu",
+ "windows_i686_msvc",
+ "windows_x86_64_gnu",
+ "windows_x86_64_gnullvm",
+ "windows_x86_64_msvc",
 ]
 
 [[package]]
-name = "winapi-i686-pc-windows-gnu"
-version = "0.4.0"
+name = "windows_aarch64_gnullvm"
+version = "0.48.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "ac3b87c63620426dd9b991e5ce0329eff545bccbbb34f3be09ff6fb6ab51b7b6"
+checksum = "91ae572e1b79dba883e0d315474df7305d12f569b400fcf90581b06062f7e1bc"
 
 [[package]]
-name = "winapi-x86_64-pc-windows-gnu"
-version = "0.4.0"
+name = "windows_aarch64_msvc"
+version = "0.48.0"
 source = "registry+https://github.com/rust-lang/crates.io-index"
-checksum = "712e227841d057c1ee1cd2fb22fa7e5a5461ae8e48fa2ca79ec42cfc1931183f"
+checksum = "b2ef27e0d7bdfcfc7b868b317c1d32c641a6fe4629c171b8928c7b08d98d7cf3"
 
 [[package]]
-name = "windows_control"
+name = "windows_control_python"
 version = "0.1.0"
 dependencies = [
  "pyo3",
- "rand",
 ]
+
+[[package]]
+name = "windows_i686_gnu"
+version = "0.48.0"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "622a1962a7db830d6fd0a69683c80a18fda201879f0f447f065a3b7467daa241"
+
+[[package]]
+name = "windows_i686_msvc"
+version = "0.48.0"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "4542c6e364ce21bf45d69fdd2a8e455fa38d316158cfd43b3ac1c5b1b19f8e00"
+
+[[package]]
+name = "windows_x86_64_gnu"
+version = "0.48.0"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "ca2b8a661f7628cbd23440e50b05d705db3686f894fc9580820623656af974b1"
+
+[[package]]
+name = "windows_x86_64_gnullvm"
+version = "0.48.0"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "7896dbc1f41e08872e9d5e8f8baa8fdd2677f29468c4e156210174edc7f7b953"
+
+[[package]]
+name = "windows_x86_64_msvc"
+version = "0.48.0"
+source = "registry+https://github.com/rust-lang/crates.io-index"
+checksum = "1a515f5799fe4961cb532f983ce2b23082366b898e52ffbce459c86f67c8378a"
```

