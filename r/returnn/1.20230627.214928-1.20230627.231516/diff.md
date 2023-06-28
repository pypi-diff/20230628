# Comparing `tmp/returnn-1.20230627.214928.tar.gz` & `tmp/returnn-1.20230627.231516.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/returnn-1.20230627.214928.tar", last modified: Tue Jun 27 20:12:07 2023, max compression
+gzip compressed data, was "dist/returnn-1.20230627.231516.tar", last modified: Tue Jun 27 21:28:37 2023, max compression
```

## Comparing `returnn-1.20230627.214928.tar` & `returnn-1.20230627.231516.tar`

### file list

```diff
@@ -1,448 +1,448 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/
--rw-r--r--   0 runner    (1001) docker     (123)      198 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/.editorconfig
--rw-r--r--   0 runner    (1001) docker     (123)      526 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)      828 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/.gitmodules
--rw-r--r--   0 runner    (1001) docker     (123)       79 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/.kateconfig
--rw-r--r--   0 runner    (1001) docker     (123)     8556 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/CHANGELOG.md
--rw-r--r--   0 runner    (1001) docker     (123)      704 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/CODEOWNERS
--rw-r--r--   0 runner    (1001) docker     (123)     4880 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/CONTRIBUTING.md
--rw-r--r--   0 runner    (1001) docker     (123)    10244 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      579 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     4718 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3573 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/README.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1171 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/_setup_info_generated.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/demos/
--rw-r--r--   0 runner    (1001) docker     (123)    36006 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/12AX.cluster_map
--rw-r--r--   0 runner    (1001) docker     (123)      476 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/_setup_returnn_env.py
--rw-r--r--   0 runner    (1001) docker     (123)     1174 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-fwd.config
--rw-r--r--   0 runner    (1001) docker     (123)     2703 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-horovod-mpi.py
--rw-r--r--   0 runner    (1001) docker     (123)      520 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-horovod-mpi.py.sh
--rwxr-xr-x   0 runner    (1001) docker     (123)      264 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-horovod-mpi.sh
--rw-r--r--   0 runner    (1001) docker     (123)     1756 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-hyper-param-tuning.config
--rwxr-xr-x   0 runner    (1001) docker     (123)     2396 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-iter-dataset.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     3635 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-list-devices.py
--rw-r--r--   0 runner    (1001) docker     (123)     2848 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-lua-torch-layer.config
--rw-r--r--   0 runner    (1001) docker     (123)      487 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-pretrain.config
--rwxr-xr-x   0 runner    (1001) docker     (123)     2331 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-record-and-push-to-webserver.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1950 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-returnn-as-framework.py
--rw-r--r--   0 runner    (1001) docker     (123)     3136 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-rf.config
--rw-r--r--   0 runner    (1001) docker     (123)     2331 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-rhn-enwik8.config
--rwxr-xr-x   0 runner    (1001) docker     (123)     1378 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-sprint-interface.py
--rw-r--r--   0 runner    (1001) docker     (123)     3147 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-att-copy.config
--rw-r--r--   0 runner    (1001) docker     (123)     2428 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-attention.config
--rw-r--r--   0 runner    (1001) docker     (123)     1481 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-chunking-blstm.12ax.config
--rw-r--r--   0 runner    (1001) docker     (123)     1416 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-contribrnn-lstm.12ax.config
--rw-r--r--   0 runner    (1001) docker     (123)     3073 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-enc-dec.config
--rwxr-xr-x   0 runner    (1001) docker     (123)    11615 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-hard-att-copy.config
--rwxr-xr-x   0 runner    (1001) docker     (123)     7287 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-lstm-benchmark.py
--rw-r--r--   0 runner    (1001) docker     (123)     1527 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-maxgradnorm-lstm.12ax.config
--rw-r--r--   0 runner    (1001) docker     (123)     1413 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-native-lstm-lowmem.12ax.config
--rw-r--r--   0 runner    (1001) docker     (123)     1576 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-native-lstm.12ax.config
--rw-r--r--   0 runner    (1001) docker     (123)     1768 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-native-lstm2.12ax.config
--rw-r--r--   0 runner    (1001) docker     (123)     1075 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-native-lstm2.12ax.tuned.config
--rw-r--r--   0 runner    (1001) docker     (123)     1794 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-neural-transducer.12ax.config
--rw-r--r--   0 runner    (1001) docker     (123)     1825 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-rec-explicit-lstm.config
--rw-r--r--   0 runner    (1001) docker     (123)     1202 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-rec-explicit-rnn.config
--rw-r--r--   0 runner    (1001) docker     (123)     2018 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-rec-self-att.config
--rw-r--r--   0 runner    (1001) docker     (123)     5188 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-search-compiled-graph.py
--rw-r--r--   0 runner    (1001) docker     (123)     1430 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-tf-vanilla-lstm.12ax.config
--rw-r--r--   0 runner    (1001) docker     (123)     4818 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-timit-lstm-ctc.config
--rw-r--r--   0 runner    (1001) docker     (123)     2975 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-torch.config
--rw-r--r--   0 runner    (1001) docker     (123)      766 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo-upd-mult-model.lstm.12ax.config
--rwxr-xr-x   0 runner    (1001) docker     (123)      651 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/demo.sh
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/demos/mdlstm/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/IAM_lines/
--rwxr-xr-x   0 runner    (1001) docker     (123)    43239 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/IAM_lines/a01-000u-00.png
--rwxr-xr-x   0 runner    (1001) docker     (123)    43552 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/IAM_lines/a01-007-04.png
--rwxr-xr-x   0 runner    (1001) docker     (123)    45111 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/IAM_lines/a01-007-06.png
--rw-r--r--   0 runner    (1001) docker     (123)     1709 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/README.txt
--rw-r--r--   0 runner    (1001) docker     (123)      158 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/chars.txt
--rw-r--r--   0 runner    (1001) docker     (123)     1896 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/config_demo
--rw-r--r--   0 runner    (1001) docker     (123)     1981 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/config_fwd
--rw-r--r--   0 runner    (1001) docker     (123)     1983 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/config_real
--rwxr-xr-x   0 runner    (1001) docker     (123)    10194 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/create_IAM_dataset.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      749 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/decode.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/features/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/features/raw/
--rw-r--r--   0 runner    (1001) docker     (123)   248580 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/features/raw/demo.h5
--rwxr-xr-x   0 runner    (1001) docker     (123)       86 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/go.sh
--rw-r--r--   0 runner    (1001) docker     (123)      235 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/lines.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/split/
--rw-r--r--   0 runner    (1001) docker     (123)     2712 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/split/eval.txt
--rw-r--r--   0 runner    (1001) docker     (123)    69536 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/split/train.txt
--rw-r--r--   0 runner    (1001) docker     (123)      934 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/IAM/split/valid.txt
--rw-r--r--   0 runner    (1001) docker     (123)      230 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/demos/mdlstm/artificial/
--rwxr-xr-x   0 runner    (1001) docker     (123)     2804 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/artificial/create_test_h5.py
--rw-r--r--   0 runner    (1001) docker     (123)     1055 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/artificial/forwardconfig
--rwxr-xr-x   0 runner    (1001) docker     (123)      105 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/artificial/go.sh
--rw-r--r--   0 runner    (1001) docker     (123)      970 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/artificial/trainconfig
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/demos/mdlstm/artificial_rgb/
--rwxr-xr-x   0 runner    (1001) docker     (123)     2966 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/artificial_rgb/create_test_h5.py
--rw-r--r--   0 runner    (1001) docker     (123)     1055 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/artificial_rgb/forwardconfig
--rwxr-xr-x   0 runner    (1001) docker     (123)      105 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/artificial_rgb/go.sh
--rw-r--r--   0 runner    (1001) docker     (123)      970 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/demos/mdlstm/artificial_rgb/trainconfig
--rw-r--r--   0 runner    (1001) docker     (123)      463 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)      110 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/requirements.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/
--rw-r--r--   0 runner    (1001) docker     (123)     1012 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25926 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6981 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/__old_mod_loader__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4659 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/__setup__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24267 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/config.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/datasets/
--rw-r--r--   0 runner    (1001) docker     (123)      390 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18032 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/audio.py
--rw-r--r--   0 runner    (1001) docker     (123)    63112 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/basic.py
--rw-r--r--   0 runner    (1001) docker     (123)     2388 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/bundle_file.py
--rw-r--r--   0 runner    (1001) docker     (123)    24892 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/cached.py
--rw-r--r--   0 runner    (1001) docker     (123)    11658 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/cached2.py
--rw-r--r--   0 runner    (1001) docker     (123)    94213 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/generating.py
--rw-r--r--   0 runner    (1001) docker     (123)    65113 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/hdf.py
--rw-r--r--   0 runner    (1001) docker     (123)    85120 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/lm.py
--rw-r--r--   0 runner    (1001) docker     (123)     9065 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/map.py
--rw-r--r--   0 runner    (1001) docker     (123)    76099 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/meta.py
--rw-r--r--   0 runner    (1001) docker     (123)    11167 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/multi_proc.py
--rw-r--r--   0 runner    (1001) docker     (123)    14596 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/normalization_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     5291 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/numpy_dump.py
--rw-r--r--   0 runner    (1001) docker     (123)     9127 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/raw_wav.py
--rw-r--r--   0 runner    (1001) docker     (123)    56015 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/sprint.py
--rw-r--r--   0 runner    (1001) docker     (123)    17608 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/stereo.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/datasets/util/
--rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/util/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23915 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/util/feature_extraction.py
--rw-r--r--   0 runner    (1001) docker     (123)    20445 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/datasets/util/vocabulary.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/engine/
--rw-r--r--   0 runner    (1001) docker     (123)      228 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/engine/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9920 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/engine/base.py
--rw-r--r--   0 runner    (1001) docker     (123)     9912 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/engine/batch.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/extern/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/
--rw-r--r--   0 runner    (1001) docker     (123)     4005 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4024 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/__main__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/
--rw-r--r--   0 runner    (1001) docker     (123)       65 2023-06-27 20:11:44.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/.git
--rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)     1069 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1448 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/README.md
--rw-r--r--   0 runner    (1001) docker     (123)    13770 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/aligner.gif
--rw-r--r--   0 runner    (1001) docker     (123)    51077 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/check.png
--rw-r--r--   0 runner    (1001) docker     (123)    11544 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/core.cu
--rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/core.h
--rw-r--r--   0 runner    (1001) docker     (123)     2512 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/core_cpu.cpp
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/
--rw-r--r--   0 runner    (1001) docker     (123)     1069 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       70 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     2089 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/README.md
--rw-r--r--   0 runner    (1001) docker     (123)     3485 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/binding.cpp
--rw-r--r--   0 runner    (1001) docker     (123)    11544 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/core.cu
--rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/core.h
--rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)     2079 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/warp_rna/
--rw-r--r--   0 runner    (1001) docker     (123)     2885 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/warp_rna/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6961 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/warp_rna/test.py
--rw-r--r--   0 runner    (1001) docker     (123)     4141 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/ref_rna.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/tensorflow_binding/
--rw-r--r--   0 runner    (1001) docker     (123)     6150 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/tensorflow_binding/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/tensorflow_binding/src/
--rw-r--r--   0 runner    (1001) docker     (123)     1693 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/tensorflow_binding/src/warp_rna_op.cc
--rw-r--r--   0 runner    (1001) docker     (123)     6030 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/tensorflow_binding/src/warp_rna_op_kernel_tmpl.h
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/tensorflow_binding/warp_rna/
--rw-r--r--   0 runner    (1001) docker     (123)     2076 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/tensorflow_binding/warp_rna/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4252 2023-06-27 20:11:47.000000 returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/test.cpp
--rw-r--r--   0 runner    (1001) docker     (123)      135 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/extern/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/extern/graph_editor/
--rw-r--r--   0 runner    (1001) docker     (123)      257 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/extern/graph_editor/README.md
--rw-r--r--   0 runner    (1001) docker     (123)     1239 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/extern/graph_editor/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8479 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/extern/graph_editor/edit.py
--rw-r--r--   0 runner    (1001) docker     (123)    19826 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/extern/graph_editor/reroute.py
--rw-r--r--   0 runner    (1001) docker     (123)    29772 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/extern/graph_editor/select.py
--rw-r--r--   0 runner    (1001) docker     (123)    26578 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/extern/graph_editor/subgraph.py
--rw-r--r--   0 runner    (1001) docker     (123)    30380 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/extern/graph_editor/transform.py
--rw-r--r--   0 runner    (1001) docker     (123)    18727 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/extern/graph_editor/util.py
--rw-r--r--   0 runner    (1001) docker     (123)      911 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/forward_iface.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/frontend/
--rw-r--r--   0 runner    (1001) docker     (123)     1260 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    40243 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/_backend.py
--rw-r--r--   0 runner    (1001) docker     (123)     5299 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/_numpy_backend.py
--rw-r--r--   0 runner    (1001) docker     (123)     5127 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)    20688 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/array_.py
--rw-r--r--   0 runner    (1001) docker     (123)    20878 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/attention.py
--rw-r--r--   0 runner    (1001) docker     (123)     1023 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/cond.py
--rw-r--r--   0 runner    (1001) docker     (123)     3550 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/const.py
--rw-r--r--   0 runner    (1001) docker     (123)     6015 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/container.py
--rw-r--r--   0 runner    (1001) docker     (123)      413 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/control_flow_ctx.py
--rw-r--r--   0 runner    (1001) docker     (123)    22357 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/conv.py
--rw-r--r--   0 runner    (1001) docker     (123)      519 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/device.py
--rw-r--r--   0 runner    (1001) docker     (123)     3538 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/dims.py
--rw-r--r--   0 runner    (1001) docker     (123)     3334 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/dropout.py
--rw-r--r--   0 runner    (1001) docker     (123)      964 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/dtype.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/frontend/encoder/
--rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/encoder/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2109 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/encoder/base.py
--rw-r--r--   0 runner    (1001) docker     (123)    15428 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/encoder/conformer.py
--rw-r--r--   0 runner    (1001) docker     (123)      330 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/gradient.py
--rw-r--r--   0 runner    (1001) docker     (123)     5855 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/init.py
--rw-r--r--   0 runner    (1001) docker     (123)     2186 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/linear.py
--rw-r--r--   0 runner    (1001) docker     (123)    15485 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/loop.py
--rw-r--r--   0 runner    (1001) docker     (123)     1898 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/loss.py
--rw-r--r--   0 runner    (1001) docker     (123)    13738 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/math_.py
--rw-r--r--   0 runner    (1001) docker     (123)     1945 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/matmul.py
--rw-r--r--   0 runner    (1001) docker     (123)     9877 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/module.py
--rw-r--r--   0 runner    (1001) docker     (123)     9687 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/normalization.py
--rw-r--r--   0 runner    (1001) docker     (123)     7158 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/parameter.py
--rw-r--r--   0 runner    (1001) docker     (123)    11035 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/rand.py
--rw-r--r--   0 runner    (1001) docker     (123)     7528 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/rec.py
--rw-r--r--   0 runner    (1001) docker     (123)     7225 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/reduce.py
--rw-r--r--   0 runner    (1001) docker     (123)    17654 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/run_ctx.py
--rw-r--r--   0 runner    (1001) docker     (123)     9385 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/signal.py
--rw-r--r--   0 runner    (1001) docker     (123)     2935 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/state.py
--rw-r--r--   0 runner    (1001) docker     (123)     4530 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/tensor_array.py
--rw-r--r--   0 runner    (1001) docker     (123)     1146 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/frontend/types.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/import_/
--rw-r--r--   0 runner    (1001) docker     (123)      243 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/import_/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8148 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/import_/common.py
--rw-r--r--   0 runner    (1001) docker     (123)    13961 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/import_/git.py
--rw-r--r--   0 runner    (1001) docker     (123)      798 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/import_/import_.py
--rw-r--r--   0 runner    (1001) docker     (123)    33063 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/learning_rate_control.py
--rw-r--r--   0 runner    (1001) docker     (123)    12235 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/log.py
--rw-r--r--   0 runner    (1001) docker     (123)    35760 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/native_op.cpp
--rw-r--r--   0 runner    (1001) docker     (123)   244393 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/native_op.py
--rw-r--r--   0 runner    (1001) docker     (123)    23542 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/pretrain.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/sprint/
--rw-r--r--   0 runner    (1001) docker     (123)       64 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/sprint/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    31545 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/sprint/cache.py
--rw-r--r--   0 runner    (1001) docker     (123)    31137 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/sprint/control.py
--rw-r--r--   0 runner    (1001) docker     (123)    23313 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/sprint/error_signals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12305 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/sprint/extern_interface.py
--rw-r--r--   0 runner    (1001) docker     (123)    36475 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/sprint/interface.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/tensor/
--rw-r--r--   0 runner    (1001) docker     (123)      501 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tensor/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      154 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tensor/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    99665 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tensor/_dim_extra.py
--rw-r--r--   0 runner    (1001) docker     (123)   158177 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tensor/_tensor_extra.py
--rw-r--r--   0 runner    (1001) docker     (123)      643 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tensor/_tensor_mixin_base.py
--rw-r--r--   0 runner    (1001) docker     (123)     4890 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tensor/_tensor_op_overloads.py
--rw-r--r--   0 runner    (1001) docker     (123)     5125 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tensor/control_flow_ctx.py
--rw-r--r--   0 runner    (1001) docker     (123)     3884 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tensor/dim.py
--rw-r--r--   0 runner    (1001) docker     (123)     1884 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tensor/marked_dim.py
--rw-r--r--   0 runner    (1001) docker     (123)     7680 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tensor/tensor.py
--rw-r--r--   0 runner    (1001) docker     (123)     5649 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tensor/tensor_dict.py
--rw-r--r--   0 runner    (1001) docker     (123)     4532 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tensor/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/tf/
--rw-r--r--   0 runner    (1001) docker     (123)       88 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1632 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/compat.py
--rw-r--r--   0 runner    (1001) docker     (123)    36852 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/data_pipeline.py
--rw-r--r--   0 runner    (1001) docker     (123)    15108 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/distributed.py
--rw-r--r--   0 runner    (1001) docker     (123)   152284 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/engine.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/tf/frontend_layers/
--rw-r--r--   0 runner    (1001) docker     (123)      452 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_layers/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    40275 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_layers/_backend.py
--rw-r--r--   0 runner    (1001) docker     (123)     3702 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_layers/_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)    14297 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_layers/cond.py
--rw-r--r--   0 runner    (1001) docker     (123)     4480 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_layers/config_entry_points.py
--rw-r--r--   0 runner    (1001) docker     (123)      888 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_layers/debug_eager_mode.py
--rw-r--r--   0 runner    (1001) docker     (123)     5712 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_layers/dims.py
--rw-r--r--   0 runner    (1001) docker     (123)    71987 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_layers/layer.py
--rw-r--r--   0 runner    (1001) docker     (123)    15829 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_layers/make_layer.py
--rw-r--r--   0 runner    (1001) docker     (123)     5107 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_layers/parameter_assign.py
--rw-r--r--   0 runner    (1001) docker     (123)     2239 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_layers/prev_tensor_ref.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/tf/frontend_low_level/
--rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_low_level/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20261 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/frontend_low_level/_backend.py
--rw-r--r--   0 runner    (1001) docker     (123)     5404 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/horovod.py
--rw-r--r--   0 runner    (1001) docker     (123)    31611 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/hyper_param_tuning.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/tf/layers/
--rw-r--r--   0 runner    (1001) docker     (123)       72 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/layers/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)   150722 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/layers/base.py
--rw-r--r--   0 runner    (1001) docker     (123)   586670 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/layers/basic.py
--rw-r--r--   0 runner    (1001) docker     (123)   539876 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/layers/rec.py
--rw-r--r--   0 runner    (1001) docker     (123)    21515 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/layers/segmental_model.py
--rw-r--r--   0 runner    (1001) docker     (123)    52409 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/layers/signal_processing.py
--rw-r--r--   0 runner    (1001) docker     (123)    11446 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/layers/variable.py
--rw-r--r--   0 runner    (1001) docker     (123)    79733 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/native_op.py
--rw-r--r--   0 runner    (1001) docker     (123)   223702 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/network.py
--rw-r--r--   0 runner    (1001) docker     (123)     5471 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/sprint.py
--rw-r--r--   0 runner    (1001) docker     (123)    71410 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/updater.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/tf/util/
--rw-r--r--   0 runner    (1001) docker     (123)       92 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/util/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)   297063 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/util/basic.py
--rw-r--r--   0 runner    (1001) docker     (123)    28839 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/util/data.py
--rw-r--r--   0 runner    (1001) docker     (123)    17333 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/util/ken_lm.py
--rw-r--r--   0 runner    (1001) docker     (123)    11277 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/tf/util/open_fst.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/torch/
--rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/torch/data/
--rw-r--r--   0 runner    (1001) docker     (123)      132 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/data/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11981 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/data/pipeline.py
--rw-r--r--   0 runner    (1001) docker     (123)     5502 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/data/returnn_dataset_wrapper.py
--rw-r--r--   0 runner    (1001) docker     (123)     1340 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/data/tensor_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)     6097 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/distributed.py
--rw-r--r--   0 runner    (1001) docker     (123)    35763 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/engine.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/torch/frontend/
--rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/frontend/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    72576 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/frontend/_backend.py
--rw-r--r--   0 runner    (1001) docker     (123)     1830 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/frontend/_rand.py
--rw-r--r--   0 runner    (1001) docker     (123)     2714 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/frontend/bridge.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/torch/functional/
--rw-r--r--   0 runner    (1001) docker     (123)      193 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/functional/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/functional/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11449 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/torch/updater.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn/util/
--rw-r--r--   0 runner    (1001) docker     (123)      336 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)   145021 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/basic.py
--rw-r--r--   0 runner    (1001) docker     (123)    59572 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/better_exchook.py
--rw-r--r--   0 runner    (1001) docker     (123)    17977 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/bpe.py
--rw-r--r--   0 runner    (1001) docker     (123)    15987 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/debug.py
--rw-r--r--   0 runner    (1001) docker     (123)     2905 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/debug_helpers.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    59177 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/fsa.py
--rw-r--r--   0 runner    (1001) docker     (123)     2009 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/literal_py_to_pickle.py
--rw-r--r--   0 runner    (1001) docker     (123)     8131 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/pprint.py
--rw-r--r--   0 runner    (1001) docker     (123)    14846 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/py-to-pickle.cpp
--rw-r--r--   0 runner    (1001) docker     (123)      277 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/py_compat.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     7273 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/sig_proc.py
--rw-r--r--   0 runner    (1001) docker     (123)    27230 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/returnn/util/task_system.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     4718 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    12482 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/returnn.egg-info/top_level.txt
--rwxr-xr-x   0 runner    (1001) docker     (123)      461 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/rnn.py
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     4159 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/tests/
--rwxr-xr-x   0 runner    (1001) docker     (123)     3392 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/DummySprintExec.py
--rw-r--r--   0 runner    (1001) docker     (123)     2743 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/PyCharm-inspection-profile.xml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/tests/PyCharm.idea/
--rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/PyCharm.idea/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/PyCharm.idea/.name
--rw-r--r--   0 runner    (1001) docker     (123)      512 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/PyCharm.idea/codeStyleSettings.xml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/tests/PyCharm.idea/codeStyles/
--rw-r--r--   0 runner    (1001) docker     (123)      328 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/PyCharm.idea/codeStyles/Project.xml
--rw-r--r--   0 runner    (1001) docker     (123)      142 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/PyCharm.idea/codeStyles/codeStyleConfig.xml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/tests/PyCharm.idea/inspectionProfiles/
--rw-r--r--   0 runner    (1001) docker     (123)     2743 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/PyCharm.idea/inspectionProfiles/Project_Default.xml
--rw-r--r--   0 runner    (1001) docker     (123)      181 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/PyCharm.idea/inspectionProfiles/profiles_settings.xml
--rw-r--r--   0 runner    (1001) docker     (123)      318 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/PyCharm.idea/misc.xml
--rw-r--r--   0 runner    (1001) docker     (123)      267 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/PyCharm.idea/modules.xml
--rw-r--r--   0 runner    (1001) docker     (123)      417 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/PyCharm.idea/returnn.iml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/tests/PyCharm.idea/scopes/
--rw-r--r--   0 runner    (1001) docker     (123)      139 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/PyCharm.idea/scopes/scope_settings.xml
--rw-r--r--   0 runner    (1001) docker     (123)      871 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/_set_num_threads1.py
--rw-r--r--   0 runner    (1001) docker     (123)      476 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/_setup_returnn_env.py
--rw-r--r--   0 runner    (1001) docker     (123)     9271 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/_setup_test_env.py
--rw-r--r--   0 runner    (1001) docker     (123)      794 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/bpe-unicode-demo.codes
--rw-r--r--   0 runner    (1001) docker     (123)     2205 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/bpe-unicode-demo.vocab
--rw-r--r--   0 runner    (1001) docker     (123)      386 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/lexicon_opt.fst
--rw-r--r--   0 runner    (1001) docker     (123)      520 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/lexicon_opt.isyms
--rw-r--r--   0 runner    (1001) docker     (123)    34282 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/lexicon_opt.jpg
--rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/lexicon_opt.osyms
--rw-r--r--   0 runner    (1001) docker     (123)     6880 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/lint_common.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    29203 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/pycharm-inspect.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     2960 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/pylint.py
--rw-r--r--   0 runner    (1001) docker     (123)     2963 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/returnn-as-framework.py
--rw-r--r--   0 runner    (1001) docker     (123)     9228 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/rf_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)      617 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/spelling.dic
--rw-r--r--   0 runner    (1001) docker     (123)     7845 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_Config.py
--rw-r--r--   0 runner    (1001) docker     (123)    18921 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_Dataset.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    13634 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_Fsa.py
--rw-r--r--   0 runner    (1001) docker     (123)     8904 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_GeneratingDataset.py
--rw-r--r--   0 runner    (1001) docker     (123)    32796 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_HDFDataset.py
--rw-r--r--   0 runner    (1001) docker     (123)    10326 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_LearningRateControl.py
--rw-r--r--   0 runner    (1001) docker     (123)     7187 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_Log.py
--rw-r--r--   0 runner    (1001) docker     (123)     3635 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_MultiProcDataset.py
--rw-r--r--   0 runner    (1001) docker     (123)     3333 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_PTDataset.py
--rw-r--r--   0 runner    (1001) docker     (123)     2465 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_Pretrain.py
--rw-r--r--   0 runner    (1001) docker     (123)    21403 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_ResNet.py
--rw-r--r--   0 runner    (1001) docker     (123)     5014 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_SprintDataset.py
--rw-r--r--   0 runner    (1001) docker     (123)     3330 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_SprintInterface.py
--rw-r--r--   0 runner    (1001) docker     (123)   238053 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_TFEngine.py
--rw-r--r--   0 runner    (1001) docker     (123)   135453 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_TFNativeOp.py
--rw-r--r--   0 runner    (1001) docker     (123)   552605 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_TFNetworkLayer.py
--rw-r--r--   0 runner    (1001) docker     (123)   561922 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_TFNetworkRecLayer.py
--rw-r--r--   0 runner    (1001) docker     (123)    14485 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_TFNetworkSigProcLayer.py
--rw-r--r--   0 runner    (1001) docker     (123)    20440 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_TFUpdater.py
--rw-r--r--   0 runner    (1001) docker     (123)   188146 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_TFUtil.py
--rw-r--r--   0 runner    (1001) docker     (123)     3082 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_TF_determinism.py
--rw-r--r--   0 runner    (1001) docker     (123)     2156 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_TaskSystem.py
--rw-r--r--   0 runner    (1001) docker     (123)     5088 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_TaskSystem_SharedMem.py
--rw-r--r--   0 runner    (1001) docker     (123)     9378 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_TranslationDataset.py
--rw-r--r--   0 runner    (1001) docker     (123)    14944 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_Util.py
--rw-r--r--   0 runner    (1001) docker     (123)    11304 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_demos.py
--rw-r--r--   0 runner    (1001) docker     (123)     7375 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_fork_exec.py
--rw-r--r--   0 runner    (1001) docker     (123)     2893 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_hdf_dump.py
--rw-r--r--   0 runner    (1001) docker     (123)     9127 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_array.py
--rw-r--r--   0 runner    (1001) docker     (123)     4491 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_attention.py
--rw-r--r--   0 runner    (1001) docker     (123)     8107 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_base.py
--rw-r--r--   0 runner    (1001) docker     (123)     9490 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_cond.py
--rw-r--r--   0 runner    (1001) docker     (123)     4591 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_container.py
--rw-r--r--   0 runner    (1001) docker     (123)    11673 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_conv.py
--rw-r--r--   0 runner    (1001) docker     (123)     1963 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_encoder_conformer.py
--rw-r--r--   0 runner    (1001) docker     (123)     6258 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_loop.py
--rw-r--r--   0 runner    (1001) docker     (123)     2960 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_math.py
--rw-r--r--   0 runner    (1001) docker     (123)     1933 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_normalization.py
--rw-r--r--   0 runner    (1001) docker     (123)    15470 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_rec.py
--rw-r--r--   0 runner    (1001) docker     (123)     3659 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_reduce.py
--rw-r--r--   0 runner    (1001) docker     (123)     1052 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_rf_signal.py
--rw-r--r--   0 runner    (1001) docker     (123)     1135 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_tensor.py
--rw-r--r--   0 runner    (1001) docker     (123)     8435 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_tools.py
--rw-r--r--   0 runner    (1001) docker     (123)     3122 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_torch_engine.py
--rw-r--r--   0 runner    (1001) docker     (123)    15594 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_torch_frontend.py
--rw-r--r--   0 runner    (1001) docker     (123)    15534 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tests/test_torch_internal_frontend.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/tools/
--rw-r--r--   0 runner    (1001) docker     (123)      476 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/_setup_returnn_env.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     9650 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/analyze-dataset-batches.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     3943 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/bliss-collect-seq-lens.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      780 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/bliss-dump-text.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     6608 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/bliss-get-segment-names.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    18221 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/bliss-to-ogg-zip.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     5644 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/bpe-create-lexicon.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    10532 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/calculate-word-error-rate.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1759 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/cleanup-old-models.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    10783 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/collect-orth-symbols.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     6801 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/collect-words.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     4395 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/compile_native_op.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    81620 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/compile_tf_graph.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     8500 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/debug-dump-search-scores.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    47001 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/debug-plot-search-scores.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     6048 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/dump-dataset-raw-strings.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    12524 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/dump-dataset.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     5770 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/dump-forward-stats.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     2576 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/dump-forward.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1596 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/dump-network-json.py
--rwxr-xr-x   0 runner    (1001) docker     (123)      719 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/dump-pickle.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    16425 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/extract_state_tying_from_dataset.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    14986 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/get-attention-weights.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     2936 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/get-best-model-epoch.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     3900 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/hdf_dump.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    19622 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/hdf_dump_translation_dataset.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    49563 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/import-blocks-mt-model.py
--rwxr-xr-x   0 runner    (1001) docker     (123)    31498 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/import-t2t-mt-model.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/tools/lattice_rescorer/
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)     2254 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/Makefile
--rw-r--r--   0 runner    (1001) docker     (123)     7825 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/tools/lattice_rescorer/example/
--rw-r--r--   0 runner    (1001) docker     (123)     1282 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/example/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      100 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/example/libs_list
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 20:12:07.000000 returnn-1.20230627.214928/tools/lattice_rescorer/example/network.040/
--rw-r--r--   0 runner    (1001) docker     (123)     5775 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/example/network.040/i600_m600_m600.sgd_b16_lr0_cl2.newbobabs.config
--rw-r--r--   0 runner    (1001) docker     (123)     6110 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/example/network.040/i600_m600_m600.sgd_b16_lr0_cl2.newbobabs.keep_over_epoch.lstm2.config
--rwxr-xr-x   0 runner    (1001) docker     (123)      800 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/example/rescore_lattice.sh
--rw-r--r--   0 runner    (1001) docker     (123)      296 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/example/state_vars_list
--rw-r--r--   0 runner    (1001) docker     (123)      155 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/example/tensor_names_list
--rw-r--r--   0 runner    (1001) docker     (123)     1687 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/file.h
--rw-r--r--   0 runner    (1001) docker     (123)    26055 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/htklatticerescorer.cc
--rw-r--r--   0 runner    (1001) docker     (123)    10856 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/htklatticerescorer.h
--rw-r--r--   0 runner    (1001) docker     (123)    12488 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/main.cc
--rw-r--r--   0 runner    (1001) docker     (123)     2184 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/rescorer.h
--rw-r--r--   0 runner    (1001) docker     (123)     5563 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/vocabulary.cc
--rw-r--r--   0 runner    (1001) docker     (123)     3023 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/lattice_rescorer/vocabulary.h
--rwxr-xr-x   0 runner    (1001) docker     (123)     5438 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/tf_avg_checkpoints.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     6269 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/tf_inspect_checkpoint.py
--rwxr-xr-x   0 runner    (1001) docker     (123)     1288 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/tf_inspect_summary_log.py
--rw-r--r--   0 runner    (1001) docker     (123)     8947 2023-06-27 20:11:42.000000 returnn-1.20230627.214928/tools/torch_export_to_onnx.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/
+-rw-r--r--   0 runner    (1001) docker     (123)      198 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/.editorconfig
+-rw-r--r--   0 runner    (1001) docker     (123)      526 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      828 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/.gitmodules
+-rw-r--r--   0 runner    (1001) docker     (123)       79 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/.kateconfig
+-rw-r--r--   0 runner    (1001) docker     (123)     8556 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/CHANGELOG.md
+-rw-r--r--   0 runner    (1001) docker     (123)      704 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/CODEOWNERS
+-rw-r--r--   0 runner    (1001) docker     (123)     4880 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/CONTRIBUTING.md
+-rw-r--r--   0 runner    (1001) docker     (123)    10244 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      579 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     4718 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3573 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/README.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1171 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/_setup_info_generated.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/demos/
+-rw-r--r--   0 runner    (1001) docker     (123)    36006 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/12AX.cluster_map
+-rw-r--r--   0 runner    (1001) docker     (123)      476 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/_setup_returnn_env.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1174 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-fwd.config
+-rw-r--r--   0 runner    (1001) docker     (123)     2703 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-horovod-mpi.py
+-rw-r--r--   0 runner    (1001) docker     (123)      520 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-horovod-mpi.py.sh
+-rwxr-xr-x   0 runner    (1001) docker     (123)      264 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-horovod-mpi.sh
+-rw-r--r--   0 runner    (1001) docker     (123)     1756 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-hyper-param-tuning.config
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2396 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-iter-dataset.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     3635 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-list-devices.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2848 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-lua-torch-layer.config
+-rw-r--r--   0 runner    (1001) docker     (123)      487 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-pretrain.config
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2331 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-record-and-push-to-webserver.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1950 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-returnn-as-framework.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3136 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-rf.config
+-rw-r--r--   0 runner    (1001) docker     (123)     2331 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-rhn-enwik8.config
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1378 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-sprint-interface.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3147 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-att-copy.config
+-rw-r--r--   0 runner    (1001) docker     (123)     2428 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-attention.config
+-rw-r--r--   0 runner    (1001) docker     (123)     1481 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-chunking-blstm.12ax.config
+-rw-r--r--   0 runner    (1001) docker     (123)     1416 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-contribrnn-lstm.12ax.config
+-rw-r--r--   0 runner    (1001) docker     (123)     3073 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-enc-dec.config
+-rwxr-xr-x   0 runner    (1001) docker     (123)    11615 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-hard-att-copy.config
+-rwxr-xr-x   0 runner    (1001) docker     (123)     7287 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-lstm-benchmark.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1527 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-maxgradnorm-lstm.12ax.config
+-rw-r--r--   0 runner    (1001) docker     (123)     1413 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-native-lstm-lowmem.12ax.config
+-rw-r--r--   0 runner    (1001) docker     (123)     1576 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-native-lstm.12ax.config
+-rw-r--r--   0 runner    (1001) docker     (123)     1768 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-native-lstm2.12ax.config
+-rw-r--r--   0 runner    (1001) docker     (123)     1075 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-native-lstm2.12ax.tuned.config
+-rw-r--r--   0 runner    (1001) docker     (123)     1794 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-neural-transducer.12ax.config
+-rw-r--r--   0 runner    (1001) docker     (123)     1825 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-rec-explicit-lstm.config
+-rw-r--r--   0 runner    (1001) docker     (123)     1202 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-rec-explicit-rnn.config
+-rw-r--r--   0 runner    (1001) docker     (123)     2018 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-rec-self-att.config
+-rw-r--r--   0 runner    (1001) docker     (123)     5188 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-search-compiled-graph.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1430 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-tf-vanilla-lstm.12ax.config
+-rw-r--r--   0 runner    (1001) docker     (123)     4818 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-timit-lstm-ctc.config
+-rw-r--r--   0 runner    (1001) docker     (123)     2975 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-torch.config
+-rw-r--r--   0 runner    (1001) docker     (123)      766 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo-upd-mult-model.lstm.12ax.config
+-rwxr-xr-x   0 runner    (1001) docker     (123)      651 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/demo.sh
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/demos/mdlstm/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/IAM_lines/
+-rwxr-xr-x   0 runner    (1001) docker     (123)    43239 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/IAM_lines/a01-000u-00.png
+-rwxr-xr-x   0 runner    (1001) docker     (123)    43552 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/IAM_lines/a01-007-04.png
+-rwxr-xr-x   0 runner    (1001) docker     (123)    45111 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/IAM_lines/a01-007-06.png
+-rw-r--r--   0 runner    (1001) docker     (123)     1709 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/README.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      158 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/chars.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     1896 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/config_demo
+-rw-r--r--   0 runner    (1001) docker     (123)     1981 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/config_fwd
+-rw-r--r--   0 runner    (1001) docker     (123)     1983 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/config_real
+-rwxr-xr-x   0 runner    (1001) docker     (123)    10194 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/create_IAM_dataset.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      749 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/decode.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/features/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/features/raw/
+-rw-r--r--   0 runner    (1001) docker     (123)   248580 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/features/raw/demo.h5
+-rwxr-xr-x   0 runner    (1001) docker     (123)       86 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/go.sh
+-rw-r--r--   0 runner    (1001) docker     (123)      235 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/lines.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/split/
+-rw-r--r--   0 runner    (1001) docker     (123)     2712 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/split/eval.txt
+-rw-r--r--   0 runner    (1001) docker     (123)    69536 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/split/train.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      934 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/IAM/split/valid.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      230 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/demos/mdlstm/artificial/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2804 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/artificial/create_test_h5.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1055 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/artificial/forwardconfig
+-rwxr-xr-x   0 runner    (1001) docker     (123)      105 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/artificial/go.sh
+-rw-r--r--   0 runner    (1001) docker     (123)      970 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/artificial/trainconfig
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/demos/mdlstm/artificial_rgb/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2966 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/artificial_rgb/create_test_h5.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1055 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/artificial_rgb/forwardconfig
+-rwxr-xr-x   0 runner    (1001) docker     (123)      105 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/artificial_rgb/go.sh
+-rw-r--r--   0 runner    (1001) docker     (123)      970 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/demos/mdlstm/artificial_rgb/trainconfig
+-rw-r--r--   0 runner    (1001) docker     (123)      463 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)      110 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/requirements.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/
+-rw-r--r--   0 runner    (1001) docker     (123)     1012 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25926 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6981 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/__old_mod_loader__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4659 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/__setup__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24267 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/config.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/datasets/
+-rw-r--r--   0 runner    (1001) docker     (123)      390 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18032 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/audio.py
+-rw-r--r--   0 runner    (1001) docker     (123)    63112 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/basic.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2388 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/bundle_file.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24892 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/cached.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11658 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/cached2.py
+-rw-r--r--   0 runner    (1001) docker     (123)    94213 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/generating.py
+-rw-r--r--   0 runner    (1001) docker     (123)    65113 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/hdf.py
+-rw-r--r--   0 runner    (1001) docker     (123)    85120 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/lm.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9065 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/map.py
+-rw-r--r--   0 runner    (1001) docker     (123)    76099 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/meta.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11167 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/multi_proc.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14596 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/normalization_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5291 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/numpy_dump.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9127 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/raw_wav.py
+-rw-r--r--   0 runner    (1001) docker     (123)    56015 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/sprint.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17608 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/stereo.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/datasets/util/
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/util/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23915 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/util/feature_extraction.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20445 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/datasets/util/vocabulary.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/engine/
+-rw-r--r--   0 runner    (1001) docker     (123)      228 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/engine/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9920 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/engine/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9912 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/engine/batch.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/extern/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/
+-rw-r--r--   0 runner    (1001) docker     (123)     4005 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4024 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/__main__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/
+-rw-r--r--   0 runner    (1001) docker     (123)       65 2023-06-27 21:28:15.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/.git
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)     1069 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1448 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)    13770 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/aligner.gif
+-rw-r--r--   0 runner    (1001) docker     (123)    51077 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/check.png
+-rw-r--r--   0 runner    (1001) docker     (123)    11544 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/core.cu
+-rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/core.h
+-rw-r--r--   0 runner    (1001) docker     (123)     2512 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/core_cpu.cpp
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/
+-rw-r--r--   0 runner    (1001) docker     (123)     1069 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       70 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     2089 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)     3485 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/binding.cpp
+-rw-r--r--   0 runner    (1001) docker     (123)    11544 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/core.cu
+-rw-r--r--   0 runner    (1001) docker     (123)      975 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/core.h
+-rw-r--r--   0 runner    (1001) docker     (123)       28 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     2079 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/warp_rna/
+-rw-r--r--   0 runner    (1001) docker     (123)     2885 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/warp_rna/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6961 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/warp_rna/test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4141 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/ref_rna.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/tensorflow_binding/
+-rw-r--r--   0 runner    (1001) docker     (123)     6150 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/tensorflow_binding/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/tensorflow_binding/src/
+-rw-r--r--   0 runner    (1001) docker     (123)     1693 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/tensorflow_binding/src/warp_rna_op.cc
+-rw-r--r--   0 runner    (1001) docker     (123)     6030 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/tensorflow_binding/src/warp_rna_op_kernel_tmpl.h
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/tensorflow_binding/warp_rna/
+-rw-r--r--   0 runner    (1001) docker     (123)     2076 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/tensorflow_binding/warp_rna/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4252 2023-06-27 21:28:19.000000 returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/test.cpp
+-rw-r--r--   0 runner    (1001) docker     (123)      135 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/extern/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/extern/graph_editor/
+-rw-r--r--   0 runner    (1001) docker     (123)      257 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/extern/graph_editor/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)     1239 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/extern/graph_editor/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8479 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/extern/graph_editor/edit.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19826 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/extern/graph_editor/reroute.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29772 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/extern/graph_editor/select.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26578 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/extern/graph_editor/subgraph.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30380 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/extern/graph_editor/transform.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18727 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/extern/graph_editor/util.py
+-rw-r--r--   0 runner    (1001) docker     (123)      911 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/forward_iface.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/frontend/
+-rw-r--r--   0 runner    (1001) docker     (123)     1260 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40243 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/_backend.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5299 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/_numpy_backend.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5127 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20688 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/array_.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20878 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/attention.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1023 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/cond.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3550 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/const.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6015 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/container.py
+-rw-r--r--   0 runner    (1001) docker     (123)      413 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/control_flow_ctx.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22357 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/conv.py
+-rw-r--r--   0 runner    (1001) docker     (123)      519 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/device.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3538 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/dims.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3334 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/dropout.py
+-rw-r--r--   0 runner    (1001) docker     (123)      964 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/dtype.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/frontend/encoder/
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/encoder/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2109 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/encoder/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15428 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/encoder/conformer.py
+-rw-r--r--   0 runner    (1001) docker     (123)      330 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/gradient.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5855 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/init.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2186 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/linear.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15485 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/loop.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1898 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/loss.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13738 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/math_.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1945 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/matmul.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9877 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/module.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9687 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/normalization.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7158 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/parameter.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11035 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/rand.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7528 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/rec.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7225 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/reduce.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17654 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/run_ctx.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9385 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/signal.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2935 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/state.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4530 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/tensor_array.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1146 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/frontend/types.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/import_/
+-rw-r--r--   0 runner    (1001) docker     (123)      243 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/import_/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8148 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/import_/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13961 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/import_/git.py
+-rw-r--r--   0 runner    (1001) docker     (123)      798 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/import_/import_.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33063 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/learning_rate_control.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12235 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/log.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35760 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/native_op.cpp
+-rw-r--r--   0 runner    (1001) docker     (123)   244393 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/native_op.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23542 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/pretrain.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/sprint/
+-rw-r--r--   0 runner    (1001) docker     (123)       64 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/sprint/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31545 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/sprint/cache.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31137 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/sprint/control.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23313 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/sprint/error_signals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12305 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/sprint/extern_interface.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36475 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/sprint/interface.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/tensor/
+-rw-r--r--   0 runner    (1001) docker     (123)      501 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tensor/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      154 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tensor/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    99665 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tensor/_dim_extra.py
+-rw-r--r--   0 runner    (1001) docker     (123)   158177 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tensor/_tensor_extra.py
+-rw-r--r--   0 runner    (1001) docker     (123)      643 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tensor/_tensor_mixin_base.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4890 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tensor/_tensor_op_overloads.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5125 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tensor/control_flow_ctx.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3884 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tensor/dim.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1884 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tensor/marked_dim.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7680 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tensor/tensor.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5649 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tensor/tensor_dict.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4532 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tensor/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/tf/
+-rw-r--r--   0 runner    (1001) docker     (123)       88 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1632 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/compat.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36852 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/data_pipeline.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15108 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/distributed.py
+-rw-r--r--   0 runner    (1001) docker     (123)   152284 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/engine.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/tf/frontend_layers/
+-rw-r--r--   0 runner    (1001) docker     (123)      452 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_layers/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40275 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_layers/_backend.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3702 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_layers/_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14297 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_layers/cond.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4480 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_layers/config_entry_points.py
+-rw-r--r--   0 runner    (1001) docker     (123)      888 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_layers/debug_eager_mode.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5712 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_layers/dims.py
+-rw-r--r--   0 runner    (1001) docker     (123)    71987 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_layers/layer.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15829 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_layers/make_layer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5107 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_layers/parameter_assign.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2239 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_layers/prev_tensor_ref.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/tf/frontend_low_level/
+-rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_low_level/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20261 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/frontend_low_level/_backend.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5404 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/horovod.py
+-rw-r--r--   0 runner    (1001) docker     (123)    31611 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/hyper_param_tuning.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/tf/layers/
+-rw-r--r--   0 runner    (1001) docker     (123)       72 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/layers/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)   150722 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/layers/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)   586670 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/layers/basic.py
+-rw-r--r--   0 runner    (1001) docker     (123)   543165 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/layers/rec.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21515 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/layers/segmental_model.py
+-rw-r--r--   0 runner    (1001) docker     (123)    52409 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/layers/signal_processing.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11446 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/layers/variable.py
+-rw-r--r--   0 runner    (1001) docker     (123)    79733 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/native_op.py
+-rw-r--r--   0 runner    (1001) docker     (123)   223702 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/network.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5471 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/sprint.py
+-rw-r--r--   0 runner    (1001) docker     (123)    71410 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/updater.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/tf/util/
+-rw-r--r--   0 runner    (1001) docker     (123)       92 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/util/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)   297063 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/util/basic.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28839 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/util/data.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17333 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/util/ken_lm.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11277 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/tf/util/open_fst.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/torch/
+-rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/torch/data/
+-rw-r--r--   0 runner    (1001) docker     (123)      132 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/data/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11981 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/data/pipeline.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5502 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/data/returnn_dataset_wrapper.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1340 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/data/tensor_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6097 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/distributed.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35763 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/engine.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/torch/frontend/
+-rw-r--r--   0 runner    (1001) docker     (123)       62 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/frontend/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    72576 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/frontend/_backend.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1830 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/frontend/_rand.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2714 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/frontend/bridge.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/torch/functional/
+-rw-r--r--   0 runner    (1001) docker     (123)      193 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/functional/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       26 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/functional/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11449 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/torch/updater.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn/util/
+-rw-r--r--   0 runner    (1001) docker     (123)      336 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)   145021 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/basic.py
+-rw-r--r--   0 runner    (1001) docker     (123)    59572 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/better_exchook.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17977 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/bpe.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15987 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/debug.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2905 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/debug_helpers.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    59177 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/fsa.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2009 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/literal_py_to_pickle.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8131 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/pprint.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14846 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/py-to-pickle.cpp
+-rw-r--r--   0 runner    (1001) docker     (123)      277 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/py_compat.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     7273 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/sig_proc.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27230 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/returnn/util/task_system.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4718 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    12482 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/returnn.egg-info/top_level.txt
+-rwxr-xr-x   0 runner    (1001) docker     (123)      461 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/rnn.py
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     4159 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/tests/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     3392 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/DummySprintExec.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2743 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/PyCharm-inspection-profile.xml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/tests/PyCharm.idea/
+-rw-r--r--   0 runner    (1001) docker     (123)       47 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/PyCharm.idea/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)        8 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/PyCharm.idea/.name
+-rw-r--r--   0 runner    (1001) docker     (123)      512 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/PyCharm.idea/codeStyleSettings.xml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/tests/PyCharm.idea/codeStyles/
+-rw-r--r--   0 runner    (1001) docker     (123)      328 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/PyCharm.idea/codeStyles/Project.xml
+-rw-r--r--   0 runner    (1001) docker     (123)      142 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/PyCharm.idea/codeStyles/codeStyleConfig.xml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/tests/PyCharm.idea/inspectionProfiles/
+-rw-r--r--   0 runner    (1001) docker     (123)     2743 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/PyCharm.idea/inspectionProfiles/Project_Default.xml
+-rw-r--r--   0 runner    (1001) docker     (123)      181 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/PyCharm.idea/inspectionProfiles/profiles_settings.xml
+-rw-r--r--   0 runner    (1001) docker     (123)      318 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/PyCharm.idea/misc.xml
+-rw-r--r--   0 runner    (1001) docker     (123)      267 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/PyCharm.idea/modules.xml
+-rw-r--r--   0 runner    (1001) docker     (123)      417 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/PyCharm.idea/returnn.iml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/tests/PyCharm.idea/scopes/
+-rw-r--r--   0 runner    (1001) docker     (123)      139 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/PyCharm.idea/scopes/scope_settings.xml
+-rw-r--r--   0 runner    (1001) docker     (123)      871 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/_set_num_threads1.py
+-rw-r--r--   0 runner    (1001) docker     (123)      476 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/_setup_returnn_env.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9271 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/_setup_test_env.py
+-rw-r--r--   0 runner    (1001) docker     (123)      794 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/bpe-unicode-demo.codes
+-rw-r--r--   0 runner    (1001) docker     (123)     2205 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/bpe-unicode-demo.vocab
+-rw-r--r--   0 runner    (1001) docker     (123)      386 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/lexicon_opt.fst
+-rw-r--r--   0 runner    (1001) docker     (123)      520 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/lexicon_opt.isyms
+-rw-r--r--   0 runner    (1001) docker     (123)    34282 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/lexicon_opt.jpg
+-rw-r--r--   0 runner    (1001) docker     (123)       41 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/lexicon_opt.osyms
+-rw-r--r--   0 runner    (1001) docker     (123)     6880 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/lint_common.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    29203 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/pycharm-inspect.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2960 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/pylint.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2963 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/returnn-as-framework.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9228 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/rf_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)      617 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/spelling.dic
+-rw-r--r--   0 runner    (1001) docker     (123)     7845 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_Config.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18921 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_Dataset.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    13634 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_Fsa.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8904 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_GeneratingDataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32796 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_HDFDataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10326 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_LearningRateControl.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7187 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_Log.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3635 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_MultiProcDataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3333 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_PTDataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2465 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_Pretrain.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21403 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_ResNet.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5014 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_SprintDataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3330 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_SprintInterface.py
+-rw-r--r--   0 runner    (1001) docker     (123)   238053 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_TFEngine.py
+-rw-r--r--   0 runner    (1001) docker     (123)   135453 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_TFNativeOp.py
+-rw-r--r--   0 runner    (1001) docker     (123)   552605 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_TFNetworkLayer.py
+-rw-r--r--   0 runner    (1001) docker     (123)   561922 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_TFNetworkRecLayer.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14485 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_TFNetworkSigProcLayer.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20440 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_TFUpdater.py
+-rw-r--r--   0 runner    (1001) docker     (123)   188146 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_TFUtil.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3082 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_TF_determinism.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2156 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_TaskSystem.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5088 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_TaskSystem_SharedMem.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9378 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_TranslationDataset.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14944 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_Util.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11304 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_demos.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7375 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_fork_exec.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2893 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_hdf_dump.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9127 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_array.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4491 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_attention.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8107 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_base.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9490 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_cond.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4591 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_container.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11673 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_conv.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1963 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_encoder_conformer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6258 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_loop.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2960 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_math.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1933 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_normalization.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15470 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_rec.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3659 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_reduce.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1052 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_rf_signal.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1135 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_tensor.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8435 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_tools.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3122 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_torch_engine.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15594 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_torch_frontend.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15534 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tests/test_torch_internal_frontend.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/tools/
+-rw-r--r--   0 runner    (1001) docker     (123)      476 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/_setup_returnn_env.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     9650 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/analyze-dataset-batches.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     3943 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/bliss-collect-seq-lens.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      780 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/bliss-dump-text.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     6608 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/bliss-get-segment-names.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    18221 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/bliss-to-ogg-zip.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     5644 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/bpe-create-lexicon.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    10532 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/calculate-word-error-rate.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1759 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/cleanup-old-models.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    10783 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/collect-orth-symbols.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     6801 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/collect-words.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     4395 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/compile_native_op.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    81620 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/compile_tf_graph.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     8500 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/debug-dump-search-scores.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    47001 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/debug-plot-search-scores.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     6048 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/dump-dataset-raw-strings.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    12524 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/dump-dataset.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     5770 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/dump-forward-stats.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2576 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/dump-forward.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1596 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/dump-network-json.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)      719 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/dump-pickle.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    16425 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/extract_state_tying_from_dataset.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    14986 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/get-attention-weights.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2936 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/get-best-model-epoch.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     3900 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/hdf_dump.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    19622 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/hdf_dump_translation_dataset.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    49563 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/import-blocks-mt-model.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)    31498 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/import-t2t-mt-model.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/tools/lattice_rescorer/
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)     2254 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/Makefile
+-rw-r--r--   0 runner    (1001) docker     (123)     7825 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/tools/lattice_rescorer/example/
+-rw-r--r--   0 runner    (1001) docker     (123)     1282 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/example/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      100 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/example/libs_list
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 21:28:37.000000 returnn-1.20230627.231516/tools/lattice_rescorer/example/network.040/
+-rw-r--r--   0 runner    (1001) docker     (123)     5775 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/example/network.040/i600_m600_m600.sgd_b16_lr0_cl2.newbobabs.config
+-rw-r--r--   0 runner    (1001) docker     (123)     6110 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/example/network.040/i600_m600_m600.sgd_b16_lr0_cl2.newbobabs.keep_over_epoch.lstm2.config
+-rwxr-xr-x   0 runner    (1001) docker     (123)      800 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/example/rescore_lattice.sh
+-rw-r--r--   0 runner    (1001) docker     (123)      296 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/example/state_vars_list
+-rw-r--r--   0 runner    (1001) docker     (123)      155 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/example/tensor_names_list
+-rw-r--r--   0 runner    (1001) docker     (123)     1687 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/file.h
+-rw-r--r--   0 runner    (1001) docker     (123)    26055 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/htklatticerescorer.cc
+-rw-r--r--   0 runner    (1001) docker     (123)    10856 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/htklatticerescorer.h
+-rw-r--r--   0 runner    (1001) docker     (123)    12488 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/main.cc
+-rw-r--r--   0 runner    (1001) docker     (123)     2184 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/rescorer.h
+-rw-r--r--   0 runner    (1001) docker     (123)     5563 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/vocabulary.cc
+-rw-r--r--   0 runner    (1001) docker     (123)     3023 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/lattice_rescorer/vocabulary.h
+-rwxr-xr-x   0 runner    (1001) docker     (123)     5438 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/tf_avg_checkpoints.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     6269 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/tf_inspect_checkpoint.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1288 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/tf_inspect_summary_log.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8947 2023-06-27 21:28:14.000000 returnn-1.20230627.231516/tools/torch_export_to_onnx.py
```

### Comparing `returnn-1.20230627.214928/.gitignore` & `returnn-1.20230627.231516/.gitignore`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/.gitmodules` & `returnn-1.20230627.231516/.gitmodules`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/CHANGELOG.md` & `returnn-1.20230627.231516/CHANGELOG.md`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/CODEOWNERS` & `returnn-1.20230627.231516/CODEOWNERS`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/CONTRIBUTING.md` & `returnn-1.20230627.231516/CONTRIBUTING.md`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/LICENSE` & `returnn-1.20230627.231516/LICENSE`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/MANIFEST.in` & `returnn-1.20230627.231516/MANIFEST.in`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/PKG-INFO` & `returnn-1.20230627.231516/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: returnn
-Version: 1.20230627.214928
+Version: 1.20230627.231516
 Summary: The RWTH extensible training framework for universal recurrent neural networks
 Home-page: https://github.com/rwth-i6/returnn/
 Author: Albert Zeyer
 Author-email: albzey@gmail.com
 License: RETURNN license
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
```

### Comparing `returnn-1.20230627.214928/README.rst` & `returnn-1.20230627.231516/README.rst`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/__init__.py` & `returnn-1.20230627.231516/__init__.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/12AX.cluster_map` & `returnn-1.20230627.231516/demos/12AX.cluster_map`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-fwd.config` & `returnn-1.20230627.231516/demos/demo-fwd.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-horovod-mpi.py` & `returnn-1.20230627.231516/demos/demo-horovod-mpi.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-horovod-mpi.py.sh` & `returnn-1.20230627.231516/demos/demo-horovod-mpi.py.sh`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-hyper-param-tuning.config` & `returnn-1.20230627.231516/demos/demo-hyper-param-tuning.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-iter-dataset.py` & `returnn-1.20230627.231516/demos/demo-iter-dataset.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-list-devices.py` & `returnn-1.20230627.231516/demos/demo-list-devices.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-lua-torch-layer.config` & `returnn-1.20230627.231516/demos/demo-lua-torch-layer.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-record-and-push-to-webserver.py` & `returnn-1.20230627.231516/demos/demo-record-and-push-to-webserver.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-returnn-as-framework.py` & `returnn-1.20230627.231516/demos/demo-returnn-as-framework.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-rf.config` & `returnn-1.20230627.231516/demos/demo-rf.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-rhn-enwik8.config` & `returnn-1.20230627.231516/demos/demo-rhn-enwik8.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-sprint-interface.py` & `returnn-1.20230627.231516/demos/demo-sprint-interface.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-att-copy.config` & `returnn-1.20230627.231516/demos/demo-tf-att-copy.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-attention.config` & `returnn-1.20230627.231516/demos/demo-tf-attention.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-chunking-blstm.12ax.config` & `returnn-1.20230627.231516/demos/demo-tf-chunking-blstm.12ax.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-contribrnn-lstm.12ax.config` & `returnn-1.20230627.231516/demos/demo-tf-contribrnn-lstm.12ax.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-enc-dec.config` & `returnn-1.20230627.231516/demos/demo-tf-enc-dec.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-hard-att-copy.config` & `returnn-1.20230627.231516/demos/demo-tf-hard-att-copy.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-lstm-benchmark.py` & `returnn-1.20230627.231516/demos/demo-tf-lstm-benchmark.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-maxgradnorm-lstm.12ax.config` & `returnn-1.20230627.231516/demos/demo-tf-maxgradnorm-lstm.12ax.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-native-lstm-lowmem.12ax.config` & `returnn-1.20230627.231516/demos/demo-tf-native-lstm-lowmem.12ax.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-native-lstm.12ax.config` & `returnn-1.20230627.231516/demos/demo-tf-native-lstm.12ax.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-native-lstm2.12ax.config` & `returnn-1.20230627.231516/demos/demo-tf-native-lstm2.12ax.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-native-lstm2.12ax.tuned.config` & `returnn-1.20230627.231516/demos/demo-tf-native-lstm2.12ax.tuned.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-neural-transducer.12ax.config` & `returnn-1.20230627.231516/demos/demo-tf-neural-transducer.12ax.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-rec-explicit-lstm.config` & `returnn-1.20230627.231516/demos/demo-tf-rec-explicit-lstm.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-rec-explicit-rnn.config` & `returnn-1.20230627.231516/demos/demo-tf-rec-explicit-rnn.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-rec-self-att.config` & `returnn-1.20230627.231516/demos/demo-tf-rec-self-att.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-search-compiled-graph.py` & `returnn-1.20230627.231516/demos/demo-tf-search-compiled-graph.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-tf-vanilla-lstm.12ax.config` & `returnn-1.20230627.231516/demos/demo-tf-vanilla-lstm.12ax.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-timit-lstm-ctc.config` & `returnn-1.20230627.231516/demos/demo-timit-lstm-ctc.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-torch.config` & `returnn-1.20230627.231516/demos/demo-torch.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo-upd-mult-model.lstm.12ax.config` & `returnn-1.20230627.231516/demos/demo-upd-mult-model.lstm.12ax.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/demo.sh` & `returnn-1.20230627.231516/demos/demo.sh`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/IAM_lines/a01-000u-00.png` & `returnn-1.20230627.231516/demos/mdlstm/IAM/IAM_lines/a01-000u-00.png`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/IAM_lines/a01-007-04.png` & `returnn-1.20230627.231516/demos/mdlstm/IAM/IAM_lines/a01-007-04.png`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/IAM_lines/a01-007-06.png` & `returnn-1.20230627.231516/demos/mdlstm/IAM/IAM_lines/a01-007-06.png`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/README.txt` & `returnn-1.20230627.231516/demos/mdlstm/IAM/README.txt`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/config_demo` & `returnn-1.20230627.231516/demos/mdlstm/IAM/config_demo`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/config_fwd` & `returnn-1.20230627.231516/demos/mdlstm/IAM/config_fwd`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/config_real` & `returnn-1.20230627.231516/demos/mdlstm/IAM/config_real`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/create_IAM_dataset.py` & `returnn-1.20230627.231516/demos/mdlstm/IAM/create_IAM_dataset.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/decode.py` & `returnn-1.20230627.231516/demos/mdlstm/IAM/decode.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/features/raw/demo.h5` & `returnn-1.20230627.231516/demos/mdlstm/IAM/features/raw/demo.h5`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/split/eval.txt` & `returnn-1.20230627.231516/demos/mdlstm/IAM/split/eval.txt`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/split/train.txt` & `returnn-1.20230627.231516/demos/mdlstm/IAM/split/train.txt`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/IAM/split/valid.txt` & `returnn-1.20230627.231516/demos/mdlstm/IAM/split/valid.txt`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/artificial/create_test_h5.py` & `returnn-1.20230627.231516/demos/mdlstm/artificial/create_test_h5.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/artificial/forwardconfig` & `returnn-1.20230627.231516/demos/mdlstm/artificial/forwardconfig`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/artificial/trainconfig` & `returnn-1.20230627.231516/demos/mdlstm/artificial/trainconfig`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/artificial_rgb/create_test_h5.py` & `returnn-1.20230627.231516/demos/mdlstm/artificial_rgb/create_test_h5.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/artificial_rgb/forwardconfig` & `returnn-1.20230627.231516/demos/mdlstm/artificial_rgb/forwardconfig`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/demos/mdlstm/artificial_rgb/trainconfig` & `returnn-1.20230627.231516/demos/mdlstm/artificial_rgb/trainconfig`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/__init__.py` & `returnn-1.20230627.231516/returnn/__init__.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/__main__.py` & `returnn-1.20230627.231516/returnn/__main__.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/__old_mod_loader__.py` & `returnn-1.20230627.231516/returnn/__old_mod_loader__.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/__setup__.py` & `returnn-1.20230627.231516/returnn/__setup__.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/config.py` & `returnn-1.20230627.231516/returnn/config.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/audio.py` & `returnn-1.20230627.231516/returnn/datasets/audio.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/basic.py` & `returnn-1.20230627.231516/returnn/datasets/basic.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/bundle_file.py` & `returnn-1.20230627.231516/returnn/datasets/bundle_file.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/cached.py` & `returnn-1.20230627.231516/returnn/datasets/cached.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/cached2.py` & `returnn-1.20230627.231516/returnn/datasets/cached2.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/generating.py` & `returnn-1.20230627.231516/returnn/datasets/generating.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/hdf.py` & `returnn-1.20230627.231516/returnn/datasets/hdf.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/lm.py` & `returnn-1.20230627.231516/returnn/datasets/lm.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/map.py` & `returnn-1.20230627.231516/returnn/datasets/map.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/meta.py` & `returnn-1.20230627.231516/returnn/datasets/meta.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/multi_proc.py` & `returnn-1.20230627.231516/returnn/datasets/multi_proc.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/normalization_data.py` & `returnn-1.20230627.231516/returnn/datasets/normalization_data.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/numpy_dump.py` & `returnn-1.20230627.231516/returnn/datasets/numpy_dump.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/raw_wav.py` & `returnn-1.20230627.231516/returnn/datasets/raw_wav.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/sprint.py` & `returnn-1.20230627.231516/returnn/datasets/sprint.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/stereo.py` & `returnn-1.20230627.231516/returnn/datasets/stereo.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/util/feature_extraction.py` & `returnn-1.20230627.231516/returnn/datasets/util/feature_extraction.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/datasets/util/vocabulary.py` & `returnn-1.20230627.231516/returnn/datasets/util/vocabulary.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/engine/base.py` & `returnn-1.20230627.231516/returnn/engine/base.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/engine/batch.py` & `returnn-1.20230627.231516/returnn/engine/batch.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/__init__.py` & `returnn-1.20230627.231516/returnn/extern/WarpRna/__init__.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/__main__.py` & `returnn-1.20230627.231516/returnn/extern/WarpRna/__main__.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/LICENSE` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/LICENSE`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/README.md` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/README.md`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/aligner.gif` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/aligner.gif`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/check.png` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/check.png`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/core.cu` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/core.cu`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/core.h` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/core.h`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/core_cpu.cpp` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/core_cpu.cpp`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/LICENSE` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/LICENSE`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/README.md` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/README.md`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/binding.cpp` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/binding.cpp`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/core.cu` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/core.cu`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/core.h` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/core.h`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/setup.py` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/setup.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/warp_rna/__init__.py` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/warp_rna/__init__.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/pytorch_binding/warp_rna/test.py` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/pytorch_binding/warp_rna/test.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/ref_rna.py` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/ref_rna.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/tensorflow_binding/setup.py` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/tensorflow_binding/setup.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/tensorflow_binding/src/warp_rna_op.cc` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/tensorflow_binding/src/warp_rna_op.cc`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/tensorflow_binding/src/warp_rna_op_kernel_tmpl.h` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/tensorflow_binding/src/warp_rna_op_kernel_tmpl.h`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/tensorflow_binding/warp_rna/__init__.py` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/tensorflow_binding/warp_rna/__init__.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/WarpRna/warp-rna/test.cpp` & `returnn-1.20230627.231516/returnn/extern/WarpRna/warp-rna/test.cpp`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/graph_editor/__init__.py` & `returnn-1.20230627.231516/returnn/extern/graph_editor/__init__.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/graph_editor/edit.py` & `returnn-1.20230627.231516/returnn/extern/graph_editor/edit.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/graph_editor/reroute.py` & `returnn-1.20230627.231516/returnn/extern/graph_editor/reroute.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/graph_editor/select.py` & `returnn-1.20230627.231516/returnn/extern/graph_editor/select.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/graph_editor/subgraph.py` & `returnn-1.20230627.231516/returnn/extern/graph_editor/subgraph.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/graph_editor/transform.py` & `returnn-1.20230627.231516/returnn/extern/graph_editor/transform.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/extern/graph_editor/util.py` & `returnn-1.20230627.231516/returnn/extern/graph_editor/util.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/forward_iface.py` & `returnn-1.20230627.231516/returnn/forward_iface.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/__init__.py` & `returnn-1.20230627.231516/returnn/frontend/__init__.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/_backend.py` & `returnn-1.20230627.231516/returnn/frontend/_backend.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/_numpy_backend.py` & `returnn-1.20230627.231516/returnn/frontend/_numpy_backend.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/_utils.py` & `returnn-1.20230627.231516/returnn/frontend/_utils.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/array_.py` & `returnn-1.20230627.231516/returnn/frontend/array_.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/attention.py` & `returnn-1.20230627.231516/returnn/frontend/attention.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/cond.py` & `returnn-1.20230627.231516/returnn/frontend/cond.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/const.py` & `returnn-1.20230627.231516/returnn/frontend/const.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/container.py` & `returnn-1.20230627.231516/returnn/frontend/container.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/conv.py` & `returnn-1.20230627.231516/returnn/frontend/conv.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/device.py` & `returnn-1.20230627.231516/returnn/frontend/device.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/dims.py` & `returnn-1.20230627.231516/returnn/frontend/dims.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/dropout.py` & `returnn-1.20230627.231516/returnn/frontend/dropout.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/dtype.py` & `returnn-1.20230627.231516/returnn/frontend/dtype.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/encoder/base.py` & `returnn-1.20230627.231516/returnn/frontend/encoder/base.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/encoder/conformer.py` & `returnn-1.20230627.231516/returnn/frontend/encoder/conformer.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/init.py` & `returnn-1.20230627.231516/returnn/frontend/init.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/linear.py` & `returnn-1.20230627.231516/returnn/frontend/linear.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/loop.py` & `returnn-1.20230627.231516/returnn/frontend/loop.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/loss.py` & `returnn-1.20230627.231516/returnn/frontend/loss.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/math_.py` & `returnn-1.20230627.231516/returnn/frontend/math_.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/matmul.py` & `returnn-1.20230627.231516/returnn/frontend/matmul.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/module.py` & `returnn-1.20230627.231516/returnn/frontend/module.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/normalization.py` & `returnn-1.20230627.231516/returnn/frontend/normalization.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/parameter.py` & `returnn-1.20230627.231516/returnn/frontend/parameter.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/rand.py` & `returnn-1.20230627.231516/returnn/frontend/rand.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/rec.py` & `returnn-1.20230627.231516/returnn/frontend/rec.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/reduce.py` & `returnn-1.20230627.231516/returnn/frontend/reduce.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/run_ctx.py` & `returnn-1.20230627.231516/returnn/frontend/run_ctx.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/signal.py` & `returnn-1.20230627.231516/returnn/frontend/signal.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/state.py` & `returnn-1.20230627.231516/returnn/frontend/state.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/tensor_array.py` & `returnn-1.20230627.231516/returnn/frontend/tensor_array.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/frontend/types.py` & `returnn-1.20230627.231516/returnn/frontend/types.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/import_/common.py` & `returnn-1.20230627.231516/returnn/import_/common.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/import_/git.py` & `returnn-1.20230627.231516/returnn/import_/git.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/import_/import_.py` & `returnn-1.20230627.231516/returnn/import_/import_.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/learning_rate_control.py` & `returnn-1.20230627.231516/returnn/learning_rate_control.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/log.py` & `returnn-1.20230627.231516/returnn/log.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/native_op.cpp` & `returnn-1.20230627.231516/returnn/native_op.cpp`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/native_op.py` & `returnn-1.20230627.231516/returnn/native_op.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/pretrain.py` & `returnn-1.20230627.231516/returnn/pretrain.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/sprint/cache.py` & `returnn-1.20230627.231516/returnn/sprint/cache.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/sprint/control.py` & `returnn-1.20230627.231516/returnn/sprint/control.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/sprint/error_signals.py` & `returnn-1.20230627.231516/returnn/sprint/error_signals.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/sprint/extern_interface.py` & `returnn-1.20230627.231516/returnn/sprint/extern_interface.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/sprint/interface.py` & `returnn-1.20230627.231516/returnn/sprint/interface.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tensor/_dim_extra.py` & `returnn-1.20230627.231516/returnn/tensor/_dim_extra.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tensor/_tensor_extra.py` & `returnn-1.20230627.231516/returnn/tensor/_tensor_extra.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tensor/_tensor_mixin_base.py` & `returnn-1.20230627.231516/returnn/tensor/_tensor_mixin_base.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tensor/_tensor_op_overloads.py` & `returnn-1.20230627.231516/returnn/tensor/_tensor_op_overloads.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tensor/control_flow_ctx.py` & `returnn-1.20230627.231516/returnn/tensor/control_flow_ctx.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tensor/dim.py` & `returnn-1.20230627.231516/returnn/tensor/dim.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tensor/marked_dim.py` & `returnn-1.20230627.231516/returnn/tensor/marked_dim.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tensor/tensor.py` & `returnn-1.20230627.231516/returnn/tensor/tensor.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tensor/tensor_dict.py` & `returnn-1.20230627.231516/returnn/tensor/tensor_dict.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tensor/utils.py` & `returnn-1.20230627.231516/returnn/tensor/utils.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/compat.py` & `returnn-1.20230627.231516/returnn/tf/compat.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/data_pipeline.py` & `returnn-1.20230627.231516/returnn/tf/data_pipeline.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/distributed.py` & `returnn-1.20230627.231516/returnn/tf/distributed.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/engine.py` & `returnn-1.20230627.231516/returnn/tf/engine.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/frontend_layers/_backend.py` & `returnn-1.20230627.231516/returnn/tf/frontend_layers/_backend.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/frontend_layers/_utils.py` & `returnn-1.20230627.231516/returnn/tf/frontend_layers/_utils.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/frontend_layers/cond.py` & `returnn-1.20230627.231516/returnn/tf/frontend_layers/cond.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/frontend_layers/config_entry_points.py` & `returnn-1.20230627.231516/returnn/tf/frontend_layers/config_entry_points.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/frontend_layers/debug_eager_mode.py` & `returnn-1.20230627.231516/returnn/tf/frontend_layers/debug_eager_mode.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/frontend_layers/dims.py` & `returnn-1.20230627.231516/returnn/tf/frontend_layers/dims.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/frontend_layers/layer.py` & `returnn-1.20230627.231516/returnn/tf/frontend_layers/layer.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/frontend_layers/make_layer.py` & `returnn-1.20230627.231516/returnn/tf/frontend_layers/make_layer.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/frontend_layers/parameter_assign.py` & `returnn-1.20230627.231516/returnn/tf/frontend_layers/parameter_assign.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/frontend_layers/prev_tensor_ref.py` & `returnn-1.20230627.231516/returnn/tf/frontend_layers/prev_tensor_ref.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/frontend_low_level/_backend.py` & `returnn-1.20230627.231516/returnn/tf/frontend_low_level/_backend.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/horovod.py` & `returnn-1.20230627.231516/returnn/tf/horovod.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/hyper_param_tuning.py` & `returnn-1.20230627.231516/returnn/tf/hyper_param_tuning.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/layers/base.py` & `returnn-1.20230627.231516/returnn/tf/layers/base.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/layers/basic.py` & `returnn-1.20230627.231516/returnn/tf/layers/basic.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/layers/rec.py` & `returnn-1.20230627.231516/returnn/tf/layers/rec.py`

 * *Files 1% similar despite different names*

```diff
@@ -11016,14 +11016,24 @@
 class RelativePositionalEncodingLayer(_ConcatInputLayer):
     """
     Relative positioning term as introduced by Shaw et al., 2018
 
     Usually added to Self-Attention using key_shift.
     Parts of the code are adapted from Tensor2Tensor (https://github.com/tensorflow/tensor2tensor).
 
+    In general, the output is [length|1 (query-len), length (key|value-len), n_out],
+    intended for self-attention.
+
+    If inside a recurrent loop, will take the current rec step as the position,
+    and relates it to self or previous positions, so the output is [1 (query-len), t+1 (key|value-len), n_out].
+    Otherwise, it assumes that the input has a time dimension, and relates each position to all others,
+    so the output is [length (query-len), length (key|value-len), n_out].
+
+    The input defines the query/key/value length by default.
+
     Example usage::
 
         d[output + '_rel_pos'] = {"class": "relative_positional_encoding",
                                   "from": [output + '_self_att_laynorm'],
                                   "n_out": self.EncKeyTotalDim // self.AttNumHeads,
                                   "forward_weights_init": self.ff_init}
         d[output + '_self_att_att'] = {"class": "self_attention",
@@ -11036,41 +11046,75 @@
 
     """
 
     layer_class = "relative_positional_encoding"
     recurrent = True
 
     def __init__(
-        self, out_dim=None, n_out=None, forward_weights_init="glorot_uniform", clipping=16, fixed=False, **kwargs
+        self,
+        out_dim=None,
+        n_out=None,
+        forward_weights_init="glorot_uniform",
+        clipping=16,
+        fixed=False,
+        query_spatial_dim=NotSpecified,
+        key_value_spatial_dim=NotSpecified,
+        query_offset=NotSpecified,
+        **kwargs,
     ):
         """
         :param Dim|None out_dim: Feature dimension of encoding.
         :param int|None n_out: Feature dimension of encoding.
         :param int clipping: After which distance to fallback to the last encoding
         :param bool fixed: Uses sinusoid positional encoding instead of learned parameters
         :param str forward_weights_init: see :func:`returnn.tf.util.basic.get_initializer`
+        :param Dim|str|None|NotSpecified query_spatial_dim: spatial dimension of query
+        :param Dim|str|NotSpecified key_value_spatial_dim: spatial dimension of key/value
+        :param int|NotSpecified query_offset: offset for query position.
+            The default behavior: In case key_value_spatial_dim is not specified, input has no time dim,
+            we assume that we are inside a rec loop and use the current step.
         """
         super(RelativePositionalEncodingLayer, self).__init__(**kwargs)
         from returnn.tf.util.basic import get_initializer
+        from returnn.tf.util.basic import is_axis_from_description_recurrent
 
         if out_dim:
             n_out = out_dim.dimension
 
-        if not self.input_data.have_time_axis():
-            offset = self.network.get_rec_step_index()
+        if self.output.batch_ndim == 3:
+            query_spatial_dim_ = self.output.dim_tags[0]
+            key_value_spatial_dim_ = self.output.dim_tags[1]
+        elif self.output.batch_ndim == 2:
+            query_spatial_dim_ = None
+            key_value_spatial_dim_ = self.output.dim_tags[0]
+        else:
+            raise RuntimeError(f"{self}: unexpected output {self.output}")
+
+        if (key_value_spatial_dim is NotSpecified and not self.input_data.have_time_axis()) or (
+            key_value_spatial_dim is not NotSpecified
+            and is_axis_from_description_recurrent(key_value_spatial_dim, network=self.network, data=self.input_data)
+        ):
             length = self.network.get_rec_step_index() + 1
-            time_dim_tag = self.output.dim_tags[1]
-            assert time_dim_tag.dimension is None, "%s: unexpected output time dim tag %r" % (self, time_dim_tag)
-            assert time_dim_tag.dyn_size_ext is not None
+            assert (
+                key_value_spatial_dim_.dimension is None
+            ), f"{self}: unexpected kv spatial dim {key_value_spatial_dim_}"
+            assert key_value_spatial_dim_.dyn_size_ext is not None
             # See CumConcatLayer for similar logic
-            if time_dim_tag.dyn_size_ext.placeholder is None:
-                time_dim_tag.dyn_size_ext.placeholder = length
-        else:
-            offset = 0
-            length = tf_util.get_shape_dim(self.input_data.placeholder, self.input_data.time_dim_axis)
+            if key_value_spatial_dim_.dyn_size_ext.placeholder is None:
+                assert key_value_spatial_dim_.dyn_size_ext.batch_shape == ()  # scalar
+                key_value_spatial_dim_.dyn_size_ext.placeholder = length
+
+        if query_offset is NotSpecified:
+            if (query_spatial_dim is NotSpecified and not self.input_data.have_time_axis()) or (
+                query_spatial_dim is not NotSpecified
+                and is_axis_from_description_recurrent(query_spatial_dim, network=self.network, data=self.input_data)
+            ):
+                query_offset = self.network.get_rec_step_index()
+            else:
+                query_offset = 0
 
         if fixed:
             from returnn.tf.util.basic import get_positional_encoding
 
             encoding_matrix = get_positional_encoding(
                 length=2 * clipping + 1, num_channels=n_out
             )  # shape [2 * clipping + 1, n_out]
@@ -11082,72 +11126,98 @@
                 encoding_matrix = self.add_param(
                     tf_compat.v1.get_variable(
                         name="encoding_matrix", shape=(2 * clipping + 1, n_out), initializer=fwd_weights_initializer
                     )
                 )
         # encoding_matrix has shape [2 * clipping + 1, n_out]
 
-        range_vec = tf.range(length) - offset  # [length]
+        kv_pos_vec = tf.range(key_value_spatial_dim_.get_dim_value())  # [kv_len]
+        q_pos_vec = tf.range(query_spatial_dim_.get_dim_value()) + query_offset  # [q_len]
 
-        if self.input_data.have_time_axis():
-            range_mat = tf.reshape(tf.tile(range_vec, [length]), [length, length])
-            distance_mat = range_mat - tf.transpose(range_mat)  # [length,length]
-        else:
-            distance_mat = tf.reshape(range_vec, [1, length])  # [1,length]
+        distance_mat = tf.expand_dims(kv_pos_vec, axis=0) - tf.expand_dims(q_pos_vec, axis=1)  # [q_len,kv_len]
         distance_mat_clipped = tf.clip_by_value(distance_mat, -clipping, clipping)
         # Shift values to be >= 0. Each integer still uniquely identifies a relative
         # position difference.
-        position_info_indices = distance_mat_clipped + clipping  # [length|1,length]
+        position_info_indices = distance_mat_clipped + clipping  # [q_len,kv_len]
 
-        encoding = tf.gather(encoding_matrix, position_info_indices)  # [length|1,length,n_out]
+        encoding = tf.gather(encoding_matrix, position_info_indices)  # [q_len,kv_len,n_out]
 
         self.output.placeholder = encoding
 
     @classmethod
-    def get_out_data_from_opts(cls, name, sources, network, out_dim=None, n_out=None, **kwargs):
+    def get_out_data_from_opts(
+        cls,
+        name,
+        sources,
+        network,
+        out_dim=None,
+        n_out=None,
+        query_spatial_dim=NotSpecified,
+        key_value_spatial_dim=NotSpecified,
+        **kwargs,
+    ):
         """
         :param str name:
         :param list[LayerBase] sources:
         :param Dim|None out_dim: Feature dimension of encoding.
         :param int|None n_out: Feature dimension of encoding.
         :param returnn.tf.network.TFNetwork network:
+        :param Dim|str|None|NotSpecified query_spatial_dim: spatial dimension of query
+        :param Dim|str|NotSpecified key_value_spatial_dim: spatial dimension of key/value
         :rtype: Data
         """
         data = get_concat_sources_data_template(sources, name="%s_output" % name)
         # The result will be without batch dim.
         if out_dim:
             feature_dim_tag = out_dim
         else:
             assert n_out is not None, "%s %r: specify out_dim or n_out" % (cls.__name__, name)
             feature_dim_tag = Dim(
                 kind=Dim.Types.Feature, description="%s_rel_pos_enc_feat" % name, dimension=n_out, auto_generated=True
             )
-        if data.have_time_axis():
-            time_dim_tag = data.get_time_dim_tag()
-            # TODO using same dim tag twice will not be supported at some future point...
-            data = data.copy_template_new_dim_tags((time_dim_tag, time_dim_tag, feature_dim_tag))
-        else:
-            # length will be ``network.get_rec_step_index() + 1``.
-            dummy_dim_tag = Dim(
-                kind=Dim.Types.Spatial, description="%s_rel_pos_enc_dummy" % name, dimension=1, auto_generated=True
-            )
-            time_dim_tag = Dim(
-                kind=Dim.Types.Spatial, description="%s_rel_pos_enc_time" % name, dimension=None, auto_generated=True
-            )
-            time_dim_tag.batch = data.batch
-            time_dim_tag.control_flow_ctx = network.get_control_flow_ctx()
-            time_dim_tag.dyn_size_ext = Data(
-                name="%s:size-inside" % name,
-                dim_tags=[],  # scalar
-                dtype="int32",
-                batch=data.batch,
-                control_flow_ctx=network.get_control_flow_ctx(),
-            )
-            data = data.copy_template_new_dim_tags((dummy_dim_tag, time_dim_tag, feature_dim_tag))
-        return data
+        if query_spatial_dim is NotSpecified:
+            if data.have_time_axis():
+                query_spatial_dim = data.get_time_dim_tag()
+            else:
+                query_spatial_dim = Dim(
+                    kind=Dim.Types.Spatial, description="%s_rel_pos_enc_dummy" % name, dimension=1, auto_generated=True
+                )
+        if query_spatial_dim is not None:
+            if isinstance(query_spatial_dim, str):
+                query_spatial_dim = data.get_dim_tag_from_description(query_spatial_dim)
+            assert isinstance(query_spatial_dim, Dim)
+        if key_value_spatial_dim is NotSpecified:
+            if data.have_time_axis():
+                key_value_spatial_dim = data.get_time_dim_tag()
+            else:
+                key_value_spatial_dim = Dim(
+                    kind=Dim.Types.Spatial,
+                    description="%s_rel_pos_enc_time" % name,
+                    dimension=None,
+                    auto_generated=True,
+                )
+                key_value_spatial_dim.batch = data.batch
+                key_value_spatial_dim.control_flow_ctx = network.get_control_flow_ctx()
+                key_value_spatial_dim.dyn_size_ext = Data(
+                    name="%s:size-inside" % name,
+                    dim_tags=[],  # scalar
+                    dtype="int32",
+                    batch=data.batch,
+                    control_flow_ctx=network.get_control_flow_ctx(),
+                )
+        if isinstance(key_value_spatial_dim, str):
+            key_value_spatial_dim = data.get_dim_tag_from_description(key_value_spatial_dim)
+        assert isinstance(key_value_spatial_dim, Dim)
+        # Note: The defaults would use the same dim tag twice when data.have_time_axis().
+        #   This will not be supported at some future point...
+        return data.copy_template_new_dim_tags(
+            (query_spatial_dim, key_value_spatial_dim, feature_dim_tag)
+            if query_spatial_dim is not None
+            else (key_value_spatial_dim, feature_dim_tag)
+        )
 
 
 class CumConcatLayer(_ConcatInputLayer):
     """
     Concatenates all previous frames of a time-axis.
     Like :class:`CumsumLayer` uses `sum`, this layer uses `concat`.
```

### Comparing `returnn-1.20230627.214928/returnn/tf/layers/segmental_model.py` & `returnn-1.20230627.231516/returnn/tf/layers/segmental_model.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/layers/signal_processing.py` & `returnn-1.20230627.231516/returnn/tf/layers/signal_processing.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/layers/variable.py` & `returnn-1.20230627.231516/returnn/tf/layers/variable.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/native_op.py` & `returnn-1.20230627.231516/returnn/tf/native_op.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/network.py` & `returnn-1.20230627.231516/returnn/tf/network.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/sprint.py` & `returnn-1.20230627.231516/returnn/tf/sprint.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/updater.py` & `returnn-1.20230627.231516/returnn/tf/updater.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/util/basic.py` & `returnn-1.20230627.231516/returnn/tf/util/basic.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/util/data.py` & `returnn-1.20230627.231516/returnn/tf/util/data.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/util/ken_lm.py` & `returnn-1.20230627.231516/returnn/tf/util/ken_lm.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/tf/util/open_fst.py` & `returnn-1.20230627.231516/returnn/tf/util/open_fst.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/torch/data/pipeline.py` & `returnn-1.20230627.231516/returnn/torch/data/pipeline.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/torch/data/returnn_dataset_wrapper.py` & `returnn-1.20230627.231516/returnn/torch/data/returnn_dataset_wrapper.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/torch/data/tensor_utils.py` & `returnn-1.20230627.231516/returnn/torch/data/tensor_utils.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/torch/distributed.py` & `returnn-1.20230627.231516/returnn/torch/distributed.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/torch/engine.py` & `returnn-1.20230627.231516/returnn/torch/engine.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/torch/frontend/_backend.py` & `returnn-1.20230627.231516/returnn/torch/frontend/_backend.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/torch/frontend/_rand.py` & `returnn-1.20230627.231516/returnn/torch/frontend/_rand.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/torch/frontend/bridge.py` & `returnn-1.20230627.231516/returnn/torch/frontend/bridge.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/torch/updater.py` & `returnn-1.20230627.231516/returnn/torch/updater.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/util/basic.py` & `returnn-1.20230627.231516/returnn/util/basic.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/util/better_exchook.py` & `returnn-1.20230627.231516/returnn/util/better_exchook.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/util/bpe.py` & `returnn-1.20230627.231516/returnn/util/bpe.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/util/debug.py` & `returnn-1.20230627.231516/returnn/util/debug.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/util/debug_helpers.py` & `returnn-1.20230627.231516/returnn/util/debug_helpers.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/util/fsa.py` & `returnn-1.20230627.231516/returnn/util/fsa.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/util/literal_py_to_pickle.py` & `returnn-1.20230627.231516/returnn/util/literal_py_to_pickle.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/util/pprint.py` & `returnn-1.20230627.231516/returnn/util/pprint.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/util/py-to-pickle.cpp` & `returnn-1.20230627.231516/returnn/util/py-to-pickle.cpp`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/util/sig_proc.py` & `returnn-1.20230627.231516/returnn/util/sig_proc.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn/util/task_system.py` & `returnn-1.20230627.231516/returnn/util/task_system.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/returnn.egg-info/PKG-INFO` & `returnn-1.20230627.231516/returnn.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: returnn
-Version: 1.20230627.214928
+Version: 1.20230627.231516
 Summary: The RWTH extensible training framework for universal recurrent neural networks
 Home-page: https://github.com/rwth-i6/returnn/
 Author: Albert Zeyer
 Author-email: albzey@gmail.com
 License: RETURNN license
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
```

### Comparing `returnn-1.20230627.214928/returnn.egg-info/SOURCES.txt` & `returnn-1.20230627.231516/returnn.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/setup.py` & `returnn-1.20230627.231516/setup.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/DummySprintExec.py` & `returnn-1.20230627.231516/tests/DummySprintExec.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/PyCharm-inspection-profile.xml` & `returnn-1.20230627.231516/tests/PyCharm-inspection-profile.xml`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/PyCharm.idea/codeStyleSettings.xml` & `returnn-1.20230627.231516/tests/PyCharm.idea/codeStyleSettings.xml`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/PyCharm.idea/inspectionProfiles/Project_Default.xml` & `returnn-1.20230627.231516/tests/PyCharm.idea/inspectionProfiles/Project_Default.xml`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/_set_num_threads1.py` & `returnn-1.20230627.231516/tests/_set_num_threads1.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/_setup_test_env.py` & `returnn-1.20230627.231516/tests/_setup_test_env.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/bpe-unicode-demo.codes` & `returnn-1.20230627.231516/tests/bpe-unicode-demo.codes`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/bpe-unicode-demo.vocab` & `returnn-1.20230627.231516/tests/bpe-unicode-demo.vocab`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/lexicon_opt.isyms` & `returnn-1.20230627.231516/tests/lexicon_opt.isyms`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/lexicon_opt.jpg` & `returnn-1.20230627.231516/tests/lexicon_opt.jpg`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/lint_common.py` & `returnn-1.20230627.231516/tests/lint_common.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/pycharm-inspect.py` & `returnn-1.20230627.231516/tests/pycharm-inspect.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/pylint.py` & `returnn-1.20230627.231516/tests/pylint.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/returnn-as-framework.py` & `returnn-1.20230627.231516/tests/returnn-as-framework.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/rf_utils.py` & `returnn-1.20230627.231516/tests/rf_utils.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/spelling.dic` & `returnn-1.20230627.231516/tests/spelling.dic`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_Config.py` & `returnn-1.20230627.231516/tests/test_Config.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_Dataset.py` & `returnn-1.20230627.231516/tests/test_Dataset.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_Fsa.py` & `returnn-1.20230627.231516/tests/test_Fsa.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_GeneratingDataset.py` & `returnn-1.20230627.231516/tests/test_GeneratingDataset.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_HDFDataset.py` & `returnn-1.20230627.231516/tests/test_HDFDataset.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_LearningRateControl.py` & `returnn-1.20230627.231516/tests/test_LearningRateControl.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_Log.py` & `returnn-1.20230627.231516/tests/test_Log.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_MultiProcDataset.py` & `returnn-1.20230627.231516/tests/test_MultiProcDataset.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_PTDataset.py` & `returnn-1.20230627.231516/tests/test_PTDataset.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_Pretrain.py` & `returnn-1.20230627.231516/tests/test_Pretrain.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_ResNet.py` & `returnn-1.20230627.231516/tests/test_ResNet.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_SprintDataset.py` & `returnn-1.20230627.231516/tests/test_SprintDataset.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_SprintInterface.py` & `returnn-1.20230627.231516/tests/test_SprintInterface.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_TFEngine.py` & `returnn-1.20230627.231516/tests/test_TFEngine.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_TFNativeOp.py` & `returnn-1.20230627.231516/tests/test_TFNativeOp.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_TFNetworkLayer.py` & `returnn-1.20230627.231516/tests/test_TFNetworkLayer.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_TFNetworkRecLayer.py` & `returnn-1.20230627.231516/tests/test_TFNetworkRecLayer.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_TFNetworkSigProcLayer.py` & `returnn-1.20230627.231516/tests/test_TFNetworkSigProcLayer.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_TFUpdater.py` & `returnn-1.20230627.231516/tests/test_TFUpdater.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_TFUtil.py` & `returnn-1.20230627.231516/tests/test_TFUtil.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_TF_determinism.py` & `returnn-1.20230627.231516/tests/test_TF_determinism.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_TaskSystem.py` & `returnn-1.20230627.231516/tests/test_TaskSystem.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_TaskSystem_SharedMem.py` & `returnn-1.20230627.231516/tests/test_TaskSystem_SharedMem.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_TranslationDataset.py` & `returnn-1.20230627.231516/tests/test_TranslationDataset.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_Util.py` & `returnn-1.20230627.231516/tests/test_Util.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_demos.py` & `returnn-1.20230627.231516/tests/test_demos.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_fork_exec.py` & `returnn-1.20230627.231516/tests/test_fork_exec.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_hdf_dump.py` & `returnn-1.20230627.231516/tests/test_hdf_dump.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_array.py` & `returnn-1.20230627.231516/tests/test_rf_array.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_attention.py` & `returnn-1.20230627.231516/tests/test_rf_attention.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_base.py` & `returnn-1.20230627.231516/tests/test_rf_base.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_cond.py` & `returnn-1.20230627.231516/tests/test_rf_cond.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_container.py` & `returnn-1.20230627.231516/tests/test_rf_container.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_conv.py` & `returnn-1.20230627.231516/tests/test_rf_conv.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_encoder_conformer.py` & `returnn-1.20230627.231516/tests/test_rf_encoder_conformer.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_loop.py` & `returnn-1.20230627.231516/tests/test_rf_loop.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_math.py` & `returnn-1.20230627.231516/tests/test_rf_math.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_normalization.py` & `returnn-1.20230627.231516/tests/test_rf_normalization.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_rec.py` & `returnn-1.20230627.231516/tests/test_rf_rec.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_reduce.py` & `returnn-1.20230627.231516/tests/test_rf_reduce.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_rf_signal.py` & `returnn-1.20230627.231516/tests/test_rf_signal.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_tensor.py` & `returnn-1.20230627.231516/tests/test_tensor.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_tools.py` & `returnn-1.20230627.231516/tests/test_tools.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_torch_engine.py` & `returnn-1.20230627.231516/tests/test_torch_engine.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_torch_frontend.py` & `returnn-1.20230627.231516/tests/test_torch_frontend.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tests/test_torch_internal_frontend.py` & `returnn-1.20230627.231516/tests/test_torch_internal_frontend.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/analyze-dataset-batches.py` & `returnn-1.20230627.231516/tools/analyze-dataset-batches.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/bliss-collect-seq-lens.py` & `returnn-1.20230627.231516/tools/bliss-collect-seq-lens.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/bliss-dump-text.py` & `returnn-1.20230627.231516/tools/bliss-dump-text.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/bliss-get-segment-names.py` & `returnn-1.20230627.231516/tools/bliss-get-segment-names.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/bliss-to-ogg-zip.py` & `returnn-1.20230627.231516/tools/bliss-to-ogg-zip.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/bpe-create-lexicon.py` & `returnn-1.20230627.231516/tools/bpe-create-lexicon.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/calculate-word-error-rate.py` & `returnn-1.20230627.231516/tools/calculate-word-error-rate.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/cleanup-old-models.py` & `returnn-1.20230627.231516/tools/cleanup-old-models.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/collect-orth-symbols.py` & `returnn-1.20230627.231516/tools/collect-orth-symbols.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/collect-words.py` & `returnn-1.20230627.231516/tools/collect-words.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/compile_native_op.py` & `returnn-1.20230627.231516/tools/compile_native_op.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/compile_tf_graph.py` & `returnn-1.20230627.231516/tools/compile_tf_graph.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/debug-dump-search-scores.py` & `returnn-1.20230627.231516/tools/debug-dump-search-scores.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/debug-plot-search-scores.py` & `returnn-1.20230627.231516/tools/debug-plot-search-scores.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/dump-dataset-raw-strings.py` & `returnn-1.20230627.231516/tools/dump-dataset-raw-strings.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/dump-dataset.py` & `returnn-1.20230627.231516/tools/dump-dataset.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/dump-forward-stats.py` & `returnn-1.20230627.231516/tools/dump-forward-stats.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/dump-forward.py` & `returnn-1.20230627.231516/tools/dump-forward.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/dump-network-json.py` & `returnn-1.20230627.231516/tools/dump-network-json.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/dump-pickle.py` & `returnn-1.20230627.231516/tools/dump-pickle.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/extract_state_tying_from_dataset.py` & `returnn-1.20230627.231516/tools/extract_state_tying_from_dataset.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/get-attention-weights.py` & `returnn-1.20230627.231516/tools/get-attention-weights.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/get-best-model-epoch.py` & `returnn-1.20230627.231516/tools/get-best-model-epoch.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/hdf_dump.py` & `returnn-1.20230627.231516/tools/hdf_dump.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/hdf_dump_translation_dataset.py` & `returnn-1.20230627.231516/tools/hdf_dump_translation_dataset.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/import-blocks-mt-model.py` & `returnn-1.20230627.231516/tools/import-blocks-mt-model.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/import-t2t-mt-model.py` & `returnn-1.20230627.231516/tools/import-t2t-mt-model.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/Makefile` & `returnn-1.20230627.231516/tools/lattice_rescorer/Makefile`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/README.md` & `returnn-1.20230627.231516/tools/lattice_rescorer/README.md`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/example/README.md` & `returnn-1.20230627.231516/tools/lattice_rescorer/example/README.md`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/example/network.040/i600_m600_m600.sgd_b16_lr0_cl2.newbobabs.config` & `returnn-1.20230627.231516/tools/lattice_rescorer/example/network.040/i600_m600_m600.sgd_b16_lr0_cl2.newbobabs.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/example/network.040/i600_m600_m600.sgd_b16_lr0_cl2.newbobabs.keep_over_epoch.lstm2.config` & `returnn-1.20230627.231516/tools/lattice_rescorer/example/network.040/i600_m600_m600.sgd_b16_lr0_cl2.newbobabs.keep_over_epoch.lstm2.config`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/example/rescore_lattice.sh` & `returnn-1.20230627.231516/tools/lattice_rescorer/example/rescore_lattice.sh`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/file.h` & `returnn-1.20230627.231516/tools/lattice_rescorer/file.h`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/htklatticerescorer.cc` & `returnn-1.20230627.231516/tools/lattice_rescorer/htklatticerescorer.cc`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/htklatticerescorer.h` & `returnn-1.20230627.231516/tools/lattice_rescorer/htklatticerescorer.h`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/main.cc` & `returnn-1.20230627.231516/tools/lattice_rescorer/main.cc`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/rescorer.h` & `returnn-1.20230627.231516/tools/lattice_rescorer/rescorer.h`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/vocabulary.cc` & `returnn-1.20230627.231516/tools/lattice_rescorer/vocabulary.cc`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/lattice_rescorer/vocabulary.h` & `returnn-1.20230627.231516/tools/lattice_rescorer/vocabulary.h`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/tf_avg_checkpoints.py` & `returnn-1.20230627.231516/tools/tf_avg_checkpoints.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/tf_inspect_checkpoint.py` & `returnn-1.20230627.231516/tools/tf_inspect_checkpoint.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/tf_inspect_summary_log.py` & `returnn-1.20230627.231516/tools/tf_inspect_summary_log.py`

 * *Files identical despite different names*

### Comparing `returnn-1.20230627.214928/tools/torch_export_to_onnx.py` & `returnn-1.20230627.231516/tools/torch_export_to_onnx.py`

 * *Files identical despite different names*

