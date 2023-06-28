# Comparing `tmp/pipelime_python-1.5.0.tar.gz` & `tmp/pipelime_python-1.6.0.tar.gz`

## Comparing `pipelime_python-1.5.0.tar` & `pipelime_python-1.6.0.tar`

### file list

```diff
@@ -1,116 +1,119 @@
--rw-r--r--   0        0        0      115 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/__init__.py
--rw-r--r--   0        0        0       44 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/__init__.py
--rw-r--r--   0        0        0    10465 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/xconfig.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/ast/__init__.py
--rw-r--r--   0        0        0     9723 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/ast/nodes.py
--rw-r--r--   0        0        0    13790 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/ast/parser.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/utils/__init__.py
--rw-r--r--   0        0        0     3587 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/utils/common.py
--rw-r--r--   0        0        0     5108 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/utils/imports.py
--rw-r--r--   0        0        0     3789 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/utils/io.py
--rw-r--r--   0        0        0    13100 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/utils/rand.py
--rw-r--r--   0        0        0      277 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/visitors/__init__.py
--rw-r--r--   0        0        0     1279 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/visitors/decoder.py
--rw-r--r--   0        0        0     7805 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/visitors/inspector.py
--rw-r--r--   0        0        0    13803 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/visitors/processor.py
--rw-r--r--   0        0        0     7932 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/visitors/unparser.py
--rw-r--r--   0        0        0     2757 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/choixe/visitors/walker.py
--rw-r--r--   0        0        0     3023 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/cli/__init__.py
--rw-r--r--   0        0        0    26097 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/cli/main.py
--rw-r--r--   0        0        0     7310 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/cli/parser.py
--rw-r--r--   0        0        0    15208 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/cli/pretty_print.py
--rw-r--r--   0        0        0     1845 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/cli/subcommands.py
--rw-r--r--   0        0        0    22727 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/cli/utils.py
--rw-r--r--   0        0        0    13769 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/cli/wizard.py
--rw-r--r--   0        0        0      638 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/commands/__init__.py
--rw-r--r--   0        0        0    28610 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/commands/general.py
--rw-r--r--   0        0        0    28216 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/commands/interfaces.py
--rw-r--r--   0        0        0    11750 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/commands/piper.py
--rw-r--r--   0        0        0     2459 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/commands/shell.py
--rw-r--r--   0        0        0    13525 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/commands/split_ops.py
--rw-r--r--   0        0        0     9219 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/commands/tempman.py
--rw-r--r--   0        0        0     1059 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/commands/toy_dataset.py
--rw-r--r--   0        0        0      973 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/items/__init__.py
--rw-r--r--   0        0        0    30747 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/items/base.py
--rw-r--r--   0        0        0      770 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/items/binary_item.py
--rw-r--r--   0        0        0     3261 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/items/image_item.py
--rw-r--r--   0        0        0     2402 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/items/metadata_item.py
--rw-r--r--   0        0        0     2941 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/items/model3d_item.py
--rw-r--r--   0        0        0     1392 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/items/numpy_item.py
--rw-r--r--   0        0        0      395 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/items/pickle_item.py
--rw-r--r--   0        0        0       80 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/__init__.py
--rw-r--r--   0        0        0    18226 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/graph.py
--rw-r--r--   0        0        0    15533 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/model.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/drawing/__init__.py
--rw-r--r--   0        0        0     1055 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/drawing/base.py
--rw-r--r--   0        0        0      707 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/drawing/factory.py
--rw-r--r--   0        0        0    10954 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/drawing/graphviz.py
--rw-r--r--   0        0        0     7597 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/drawing/mermaid.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/executors/__init__.py
--rw-r--r--   0        0        0     5626 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/executors/base.py
--rw-r--r--   0        0        0     1023 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/executors/factory.py
--rw-r--r--   0        0        0     1319 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/executors/naive.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/parsers/__init__.py
--rw-r--r--   0        0        0     2116 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/parsers/base.py
--rw-r--r--   0        0        0      843 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/parsers/choixe_parser.py
--rw-r--r--   0        0        0      578 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/parsers/factory.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/__init__.py
--rw-r--r--   0        0        0      718 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/model.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/estimator/__init__.py
--rw-r--r--   0        0        0     1097 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/estimator/base.py
--rw-r--r--   0        0        0      440 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/estimator/factory.py
--rw-r--r--   0        0        0     1382 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/estimator/naive.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/listener/__init__.py
--rw-r--r--   0        0        0     3096 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/listener/base.py
--rw-r--r--   0        0        0     1295 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/listener/factory.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/listener/callbacks/__init__.py
--rw-r--r--   0        0        0     2215 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/listener/callbacks/file.py
--rw-r--r--   0        0        0     3442 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/listener/callbacks/rich_table.py
--rw-r--r--   0        0        0     1945 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/listener/callbacks/tqdm_bars.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/listener/receiver/__init__.py
--rw-r--r--   0        0        0     1621 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/listener/receiver/zmq.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/tracker/__init__.py
--rw-r--r--   0        0        0     5609 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/tracker/base.py
--rw-r--r--   0        0        0      803 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/tracker/direct.py
--rw-r--r--   0        0        0      728 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/tracker/factory.py
--rw-r--r--   0        0        0      749 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/tracker/loguru.py
--rw-r--r--   0        0        0     2791 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/piper/progress/tracker/zmq.py
--rw-r--r--   0        0        0      195 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/remotes/__init__.py
--rw-r--r--   0        0        0    12825 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/remotes/base.py
--rw-r--r--   0        0        0     6644 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/remotes/s3_remote.py
--rw-r--r--   0        0        0     4714 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/remotes/shared_folder_remote.py
--rw-r--r--   0        0        0      500 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/__init__.py
--rw-r--r--   0        0        0      949 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/direct_access.py
--rw-r--r--   0        0        0     6696 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/grabber.py
--rw-r--r--   0        0        0     8682 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/sample.py
--rw-r--r--   0        0        0    22718 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/samples_sequence.py
--rw-r--r--   0        0        0      432 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/torch.py
--rw-r--r--   0        0        0     7031 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/utils.py
--rw-r--r--   0        0        0      226 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/pipes/__init__.py
--rw-r--r--   0        0        0      525 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/pipes/base.py
--rw-r--r--   0        0        0     4356 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/pipes/mapping.py
--rw-r--r--   0        0        0    14141 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/pipes/operations.py
--rw-r--r--   0        0        0     1661 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/pipes/validation.py
--rw-r--r--   0        0        0     4613 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/pipes/writers.py
--rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/sources/__init__.py
--rw-r--r--   0        0        0      814 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/sources/from_callable.py
--rw-r--r--   0        0        0      633 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/sources/raw.py
--rw-r--r--   0        0        0     5542 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/sources/readers.py
--rw-r--r--   0        0        0     8015 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/sequences/sources/toy_dataset.py
--rw-r--r--   0        0        0      579 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/stages/__init__.py
--rw-r--r--   0        0        0     3626 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/stages/augmentations.py
--rw-r--r--   0        0        0     3143 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/stages/base.py
--rw-r--r--   0        0        0    13512 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/stages/entities.py
--rw-r--r--   0        0        0     1618 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/stages/item_info.py
--rw-r--r--   0        0        0     1266 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/stages/item_replacement.py
--rw-r--r--   0        0        0     2275 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/stages/item_sources.py
--rw-r--r--   0        0        0     3261 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/stages/key_transformations.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/utils/__init__.py
--rw-r--r--   0        0        0     1430 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/utils/context_managers.py
--rw-r--r--   0        0        0     1004 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/utils/inspection.py
--rw-r--r--   0        0        0    23458 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pipelime/utils/pydantic_types.py
--rw-r--r--   0        0        0     1268 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/.gitignore
--rw-r--r--   0        0        0     1525 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/LICENSE
--rw-r--r--   0        0        0     6062 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/README.md
--rw-r--r--   0        0        0     2131 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/pyproject.toml
--rw-r--r--   0        0        0     8418 2020-02-02 00:00:00.000000 pipelime_python-1.5.0/PKG-INFO
+-rw-r--r--   0        0        0      115 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/__init__.py
+-rw-r--r--   0        0        0       52 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/__init__.py
+-rw-r--r--   0        0        0    14915 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/xconfig.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/ast/__init__.py
+-rw-r--r--   0        0        0     9723 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/ast/nodes.py
+-rw-r--r--   0        0        0    13790 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/ast/parser.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/utils/__init__.py
+-rw-r--r--   0        0        0     3587 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/utils/common.py
+-rw-r--r--   0        0        0     5108 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/utils/imports.py
+-rw-r--r--   0        0        0     5314 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/utils/io.py
+-rw-r--r--   0        0        0    13100 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/utils/rand.py
+-rw-r--r--   0        0        0      277 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/visitors/__init__.py
+-rw-r--r--   0        0        0     1279 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/visitors/decoder.py
+-rw-r--r--   0        0        0     7805 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/visitors/inspector.py
+-rw-r--r--   0        0        0    13803 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/visitors/processor.py
+-rw-r--r--   0        0        0     7932 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/visitors/unparser.py
+-rw-r--r--   0        0        0     2757 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/visitors/walker.py
+-rw-r--r--   0        0        0     2905 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/__init__.py
+-rw-r--r--   0        0        0    27326 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/main.py
+-rw-r--r--   0        0        0     7310 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/parser.py
+-rw-r--r--   0        0        0    15208 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/pretty_print.py
+-rw-r--r--   0        0        0     1845 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/subcommands.py
+-rw-r--r--   0        0        0    22727 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/utils.py
+-rw-r--r--   0        0        0    13769 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/wizard.py
+-rw-r--r--   0        0        0       89 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/tui/__init__.py
+-rw-r--r--   0        0        0     9900 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/tui/tui.py
+-rw-r--r--   0        0        0     7248 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/tui/utils.py
+-rw-r--r--   0        0        0      695 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/__init__.py
+-rw-r--r--   0        0        0    34047 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/general.py
+-rw-r--r--   0        0        0    28216 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/interfaces.py
+-rw-r--r--   0        0        0    15995 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/piper.py
+-rw-r--r--   0        0        0     2459 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/shell.py
+-rw-r--r--   0        0        0    13525 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/split_ops.py
+-rw-r--r--   0        0        0     9227 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/tempman.py
+-rw-r--r--   0        0        0     1059 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/toy_dataset.py
+-rw-r--r--   0        0        0      973 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/__init__.py
+-rw-r--r--   0        0        0    30747 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/base.py
+-rw-r--r--   0        0        0      770 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/binary_item.py
+-rw-r--r--   0        0        0     3261 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/image_item.py
+-rw-r--r--   0        0        0     2402 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/metadata_item.py
+-rw-r--r--   0        0        0     2941 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/model3d_item.py
+-rw-r--r--   0        0        0     1392 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/numpy_item.py
+-rw-r--r--   0        0        0      395 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/pickle_item.py
+-rw-r--r--   0        0        0       80 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/__init__.py
+-rw-r--r--   0        0        0    18226 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/graph.py
+-rw-r--r--   0        0        0    17058 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/model.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/drawing/__init__.py
+-rw-r--r--   0        0        0     1055 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/drawing/base.py
+-rw-r--r--   0        0        0      707 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/drawing/factory.py
+-rw-r--r--   0        0        0    10954 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/drawing/graphviz.py
+-rw-r--r--   0        0        0     7597 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/drawing/mermaid.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/executors/__init__.py
+-rw-r--r--   0        0        0     6508 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/executors/base.py
+-rw-r--r--   0        0        0     1023 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/executors/factory.py
+-rw-r--r--   0        0        0     1319 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/executors/naive.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/parsers/__init__.py
+-rw-r--r--   0        0        0     2116 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/parsers/base.py
+-rw-r--r--   0        0        0      843 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/parsers/choixe_parser.py
+-rw-r--r--   0        0        0      578 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/parsers/factory.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/__init__.py
+-rw-r--r--   0        0        0      718 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/model.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/estimator/__init__.py
+-rw-r--r--   0        0        0     1097 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/estimator/base.py
+-rw-r--r--   0        0        0      440 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/estimator/factory.py
+-rw-r--r--   0        0        0     1382 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/estimator/naive.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/__init__.py
+-rw-r--r--   0        0        0     3096 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/base.py
+-rw-r--r--   0        0        0     1295 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/factory.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/__init__.py
+-rw-r--r--   0        0        0     2215 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/file.py
+-rw-r--r--   0        0        0     3442 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/rich_table.py
+-rw-r--r--   0        0        0     1945 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/tqdm_bars.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/receiver/__init__.py
+-rw-r--r--   0        0        0     1621 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/receiver/zmq.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/tracker/__init__.py
+-rw-r--r--   0        0        0     6366 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/tracker/base.py
+-rw-r--r--   0        0        0      803 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/tracker/direct.py
+-rw-r--r--   0        0        0      728 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/tracker/factory.py
+-rw-r--r--   0        0        0      749 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/tracker/loguru.py
+-rw-r--r--   0        0        0     2791 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/tracker/zmq.py
+-rw-r--r--   0        0        0      195 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/remotes/__init__.py
+-rw-r--r--   0        0        0    12825 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/remotes/base.py
+-rw-r--r--   0        0        0     6644 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/remotes/s3_remote.py
+-rw-r--r--   0        0        0     4714 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/remotes/shared_folder_remote.py
+-rw-r--r--   0        0        0      500 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/__init__.py
+-rw-r--r--   0        0        0      949 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/direct_access.py
+-rw-r--r--   0        0        0     6696 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/grabber.py
+-rw-r--r--   0        0        0     8682 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/sample.py
+-rw-r--r--   0        0        0    23171 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/samples_sequence.py
+-rw-r--r--   0        0        0      432 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/torch.py
+-rw-r--r--   0        0        0     7031 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/utils.py
+-rw-r--r--   0        0        0      226 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/pipes/__init__.py
+-rw-r--r--   0        0        0      525 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/pipes/base.py
+-rw-r--r--   0        0        0     4356 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/pipes/mapping.py
+-rw-r--r--   0        0        0    14141 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/pipes/operations.py
+-rw-r--r--   0        0        0     1661 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/pipes/validation.py
+-rw-r--r--   0        0        0     4613 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/pipes/writers.py
+-rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/sources/__init__.py
+-rw-r--r--   0        0        0      814 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/sources/from_callable.py
+-rw-r--r--   0        0        0      633 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/sources/raw.py
+-rw-r--r--   0        0        0     8094 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/sources/readers.py
+-rw-r--r--   0        0        0     8015 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/sources/toy_dataset.py
+-rw-r--r--   0        0        0      681 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/__init__.py
+-rw-r--r--   0        0        0     9973 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/augmentations.py
+-rw-r--r--   0        0        0     3280 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/base.py
+-rw-r--r--   0        0        0    13512 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/entities.py
+-rw-r--r--   0        0        0     1618 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/item_info.py
+-rw-r--r--   0        0        0     5065 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/item_replacement.py
+-rw-r--r--   0        0        0     2275 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/item_sources.py
+-rw-r--r--   0        0        0     3261 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/key_transformations.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/utils/__init__.py
+-rw-r--r--   0        0        0     1430 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/utils/context_managers.py
+-rw-r--r--   0        0        0     1004 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/utils/inspection.py
+-rw-r--r--   0        0        0    23458 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/utils/pydantic_types.py
+-rw-r--r--   0        0        0     1269 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/.gitignore
+-rw-r--r--   0        0        0     1525 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/LICENSE
+-rw-r--r--   0        0        0     6062 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/README.md
+-rw-r--r--   0        0        0     2173 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pyproject.toml
+-rw-r--r--   0        0        0     8494 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/PKG-INFO
```

### Comparing `pipelime_python-1.5.0/pipelime/choixe/ast/nodes.py` & `pipelime_python-1.6.0/pipelime/choixe/ast/nodes.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/choixe/ast/parser.py` & `pipelime_python-1.6.0/pipelime/choixe/ast/parser.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/choixe/utils/common.py` & `pipelime_python-1.6.0/pipelime/choixe/utils/common.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/choixe/utils/imports.py` & `pipelime_python-1.6.0/pipelime/choixe/utils/imports.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/choixe/utils/io.py` & `pipelime_python-1.6.0/pipelime/choixe/utils/io.py`

 * *Files 26% similar despite different names*

```diff
@@ -115,18 +115,71 @@
             if os.path.isdir(d):
                 names = os.path.basename(d).split("-")
                 if len(names) >= 3:
                     user_dirs.setdefault(names[2], []).append(d)
         return user_dirs
 
 
-class PipelimeTemporaryDirectory(tempfile.TemporaryDirectory):
-    """A tempfile.TemporaryDirectory within the session temporary directory."""
+class PipelimeTemporaryDirectory:
+    """A context manager creating a subfolder within the session temporary directory."""
 
     def __init__(self, name: Optional[str] = None):
         self.name = PipelimeTmp.make_subdir(name or uuid.uuid1().hex)
         self._finalizer = weakref.finalize(
             self,
             self._cleanup,  # type: ignore
             str(self.name),
             warn_message="Implicitly cleaning up {!r}".format(self),
         )
+
+    @classmethod
+    def _rmtree(cls, name):
+        import shutil
+
+        def onerror(func, path, exc_info):
+            if issubclass(exc_info[0], PermissionError):
+
+                def resetperms(path):
+                    try:
+                        os.chflags(path, 0)  # type: ignore
+                    except AttributeError:
+                        pass
+                    os.chmod(path, 0o700)
+
+                try:
+                    if path != name:
+                        resetperms(os.path.dirname(path))
+                    resetperms(path)
+
+                    try:
+                        os.unlink(path)
+                    # PermissionError is raised on FreeBSD for directories
+                    except (IsADirectoryError, PermissionError):
+                        cls._rmtree(path)
+                except FileNotFoundError:
+                    pass
+            elif issubclass(exc_info[0], FileNotFoundError):
+                pass
+            else:
+                raise
+
+        shutil.rmtree(name, onerror=onerror)
+
+    @classmethod
+    def _cleanup(cls, name, warn_message):
+        import warnings
+
+        cls._rmtree(name)
+        warnings.warn(warn_message, ResourceWarning)
+
+    def __repr__(self):
+        return "<{} {!r}>".format(self.__class__.__name__, self.name)
+
+    def __enter__(self):
+        return self.name
+
+    def __exit__(self, exc, value, tb):
+        self.cleanup()
+
+    def cleanup(self):
+        if self._finalizer.detach() or os.path.exists(self.name):
+            self._rmtree(self.name)
```

### Comparing `pipelime_python-1.5.0/pipelime/choixe/utils/rand.py` & `pipelime_python-1.6.0/pipelime/choixe/utils/rand.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/choixe/visitors/decoder.py` & `pipelime_python-1.6.0/pipelime/choixe/visitors/decoder.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/choixe/visitors/inspector.py` & `pipelime_python-1.6.0/pipelime/choixe/visitors/inspector.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/choixe/visitors/processor.py` & `pipelime_python-1.6.0/pipelime/choixe/visitors/processor.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/choixe/visitors/unparser.py` & `pipelime_python-1.6.0/pipelime/choixe/visitors/unparser.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/choixe/visitors/walker.py` & `pipelime_python-1.6.0/pipelime/choixe/visitors/walker.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/cli/__init__.py` & `pipelime_python-1.6.0/pipelime/cli/__init__.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,13 +1,7 @@
-from pipelime.cli.utils import (
-    print_command_op_stage_info,
-    print_commands_ops_stages_list,
-    pl_print,
-)
-
 import typing as t
 
 
 class PipelimeApp:
     def __init__(
         self,
         *extra_modules: str,
@@ -79,17 +73,18 @@
         def my_command():
             ...
 
         if __name__ == "__main__":
             run()
         ```
     """
-    from pipelime.utils.inspection import MyCaller
     from pathlib import Path
 
+    from pipelime.utils.inspection import MyCaller
+
     caller = MyCaller()
     caller_path = Path(caller.filename)
 
     app = PipelimeApp(
         caller.module,
         app_name=caller_path.stem,
         entry_point=f"python {caller_path.name}",
```

### Comparing `pipelime_python-1.5.0/pipelime/cli/main.py` & `pipelime_python-1.6.0/pipelime/cli/main.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,18 +1,18 @@
 from __future__ import annotations
 
-import typing as t
 import functools
 import itertools
+import typing as t
 from pathlib import Path
 
 import typer
 
+from pipelime.cli.parser import CLIParsingError, parse_pipelime_cli
 from pipelime.cli.subcommands import SubCommands as subc
-from pipelime.cli.parser import parse_pipelime_cli, CLIParsingError
 from pipelime.cli.utils import (
     PipelimeSymbolsHelper,
     print_command_op_stage_info,
     print_commands_ops_stages_list,
 )
 
 if t.TYPE_CHECKING:
@@ -88,16 +88,16 @@
     cfg_name: str,
     run_all: t.Optional[bool],
     output: t.Optional[Path],
     exit_on_error: bool,
     verbose: bool,
     print_all: bool,
 ) -> t.List["XConfig"]:
-    from pipelime.cli.pretty_print import print_error, print_info, print_warning
     from pipelime.choixe.visitors.processor import ChoixeProcessingError
+    from pipelime.cli.pretty_print import print_error, print_info, print_warning
 
     if verbose:
         print_info(f"> Processing {cfg_name}...")
 
     try:
         effective_configs = (
             [cfg.process(ctx)]
@@ -150,16 +150,16 @@
     base_cfg: t.List["XConfig"],
     effective_ctx: "XConfig",
     output: t.Optional[Path],
     run_all: t.Optional[bool],
     exit_on_error: bool,
     verbose: int,
 ):
-    from pipelime.cli.pretty_print import print_info
     from pipelime.choixe import XConfig
+    from pipelime.cli.pretty_print import print_info
 
     if verbose > 1:
         print_info("\nProcessing configurations:")
 
     # first process with no branch
     effective_configs = [
         _process_cfg_or_die(
@@ -294,14 +294,20 @@
     ),
     output_ctx: t.Optional[Path] = typer.Option(
         None,
         writable=True,
         resolve_path=True,
         help="Save final processed context to json/yaml.",
     ),
+    command_outputs: t.Optional[Path] = typer.Option(
+        None,
+        writable=True,
+        resolve_path=True,
+        help="Save command outputs to json/yaml.",
+    ),
     verbose: int = typer.Option(
         0,
         "--verbose",
         "-v",
         help="Verbose output. Can be specified multiple times.",
         count=True,
     ),
@@ -658,47 +664,59 @@
                         print_warning(
                             "You should use the `run` command to process a dag."
                         )
                         raise typer.Exit(1)
                     cmd_name = next(iter(cfg_dict))
                     cfg_dict = next(iter(cfg_dict.values()))
 
-                run_command(cmd_name, cfg_dict, verbose, dry_run, keep_tmp)
+                run_command(
+                    cmd_name, cfg_dict, verbose, dry_run, keep_tmp, command_outputs
+                )
     else:
         from pipelime.cli.pretty_print import print_error
 
         print_error("No command specified.")
         raise typer.Exit(1)
 
 
 def run_command(
-    command: str, cmd_args: t.Mapping, verbose: int, dry_run: bool, keep_tmp: bool
+    command: str,
+    cmd_args: t.Mapping,
+    verbose: int,
+    dry_run: bool,
+    keep_tmp: bool,
+    command_outputs: t.Optional[Path],
 ):
     """
     Run a pipelime command.
     """
 
     import time
-    from pydantic.error_wrappers import ValidationError
 
-    from pipelime.choixe.utils.io import PipelimeTmp
-    from pipelime.commands import TempCommand
+    from pydantic.error_wrappers import ValidationError
 
-    from pipelime.cli.pretty_print import print_info, print_command_outputs
+    from pipelime.choixe.utils.io import PipelimeTmp, dump
+    from pipelime.cli.pretty_print import print_command_outputs, print_info
+    from pipelime.cli.tui import TuiApp, is_tui_needed
     from pipelime.cli.utils import (
         get_pipelime_command_cls,
-        time_to_str,
         show_field_alias_valerr,
+        time_to_str,
     )
+    from pipelime.commands import TempCommand
 
     try:
         cmd_cls = get_pipelime_command_cls(command)
     except ValueError:
         raise typer.Exit(1)
 
+    if is_tui_needed(cmd_cls, cmd_args):
+        app = TuiApp(cmd_cls, cmd_args)
+        cmd_args = t.cast(t.Mapping, app.run())
+
     if verbose > 2:
         print_info(f"\nCreating command `{command}` with options:")
         print_info(cmd_args, pretty=True)
 
     try:
         cmd_obj = cmd_cls(**cmd_args)
     except ValidationError as e:
@@ -717,14 +735,33 @@
         cmd_obj()
     end_time = time.perf_counter_ns()
     print_info("\nCommand executed in " + time_to_str(end_time - start_time))
 
     print_info(f"\n`{command}` outputs:")
     print_command_outputs(cmd_obj)
 
+    if command_outputs:
+
+        def _cvt_data(data):
+            if hasattr(data, "__piper_repr__"):
+                return data.__piper_repr__()
+            if isinstance(data, (bytes, str)):
+                return str(data)
+            if isinstance(data, Path):
+                return data.resolve().absolute().as_posix()
+            elif isinstance(data, t.Mapping):
+                return {k: _cvt_data(v) for k, v in data.items()}
+            elif isinstance(data, t.Sequence):
+                return [_cvt_data(v) for v in data]
+            return repr(data)
+
+        print_info(f"\nSaving command outputs to `{command_outputs}`")
+        outs = {k: _cvt_data(v) for k, v in cmd_obj.get_outputs().items()}
+        dump(outs, command_outputs)
+
     if not keep_tmp and PipelimeTmp.SESSION_TMP_DIR:
         print_info("\nCleaning temporary files...")
         TempCommand(name=PipelimeTmp.SESSION_TMP_DIR.stem, force=True)()  # type: ignore
 
 
 def _create_typer_app(
     *,
```

### Comparing `pipelime_python-1.5.0/pipelime/cli/parser.py` & `pipelime_python-1.6.0/pipelime/cli/parser.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/cli/pretty_print.py` & `pipelime_python-1.6.0/pipelime/cli/pretty_print.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/cli/subcommands.py` & `pipelime_python-1.6.0/pipelime/cli/subcommands.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/cli/utils.py` & `pipelime_python-1.6.0/pipelime/cli/utils.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/cli/wizard.py` & `pipelime_python-1.6.0/pipelime/cli/wizard.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/commands/__init__.py` & `pipelime_python-1.6.0/pipelime/commands/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -8,14 +8,16 @@
     RemoveRemoteCommand,
     ValidateCommand,
     MapCommand,
     SortCommand,
     FilterCommand,
     SliceCommand,
     SetMetadataCommand,
+    FilterDuplicatesCommand,
+    CopySharedItemsCommand,
 )
 from pipelime.commands.shell import ShellCommand
 from pipelime.commands.split_ops import (
     SplitByQueryCommand,
     SplitByValueCommand,
     SplitCommand,
 )
```

### Comparing `pipelime_python-1.5.0/pipelime/commands/general.py` & `pipelime_python-1.6.0/pipelime/commands/general.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,13 +1,15 @@
 import typing as t
+
 import pydantic as pyd
 
 import pipelime.commands.interfaces as pl_interfaces
-from pipelime.piper import PipelimeCommand, PiperPortType
 import pipelime.utils.pydantic_types as pl_types
+from pipelime.piper import PipelimeCommand, PiperPortType
+from pipelime.stages import StageInput
 
 
 class TimeItCommand(PipelimeCommand, title="timeit"):
     """Measures the average time to get a sample from a sequence."""
 
     class OutputTime(pyd.BaseModel):
         nanosec: int
@@ -78,17 +80,18 @@
         description="The average time to get a sample from the sequence.",
         exclude=True,
         repr=False,
         piper_port=PiperPortType.OUTPUT,
     )
 
     def run(self):
-        import time
         import shutil
-        from pipelime.sequences import build_pipe, SamplesSequence
+        import time
+
+        from pipelime.sequences import SamplesSequence, build_pipe
 
         if self.input is None and self.operations is None:
             raise ValueError("No input dataset or operation defined.")
 
         clock_fn = time.process_time_ns if self.process else time.perf_counter_ns
 
         elapsed_times = []
@@ -172,15 +175,15 @@
     @pyd.validator("operations")
     def _validate_operations(cls, v: pl_types.YamlInput) -> pl_types.YamlInput:
         if not v.value or not isinstance(v.value, (t.Mapping, t.Sequence)):
             raise ValueError(f"Invalid pipeline: {v.value}")
         return v
 
     def run(self):
-        from pipelime.sequences import build_pipe, SamplesSequence
+        from pipelime.sequences import SamplesSequence, build_pipe
 
         seq = SamplesSequence if self.input is None else self.input.create_reader()
         seq = build_pipe(self.operations.value, seq)  # type: ignore
         seq = self.output.append_writer(seq)
 
         self.grabber.grab_all(
             seq,
@@ -579,15 +582,15 @@
             schema_def=sample_validation
         )
 
 
 class MapCommand(PipelimeCommand, title="map"):
     """Apply a stage on a dataset."""
 
-    stage: t.Union[str, t.Mapping[str, t.Mapping[str, t.Any]]] = pyd.Field(
+    stage: StageInput = pyd.Field(
         ...,
         alias="s",
         description=(
             "A stage to apply. Can be a stage name/class_path (with no arguments) or "
             "a dictionary with the stage name/class_path as key and the arguments "
             "passed by keywords."
         ),
@@ -856,7 +859,170 @@
         self.grabber.grab_all(
             seq,
             grab_context_manager=self.output.serialization_cm(),
             keep_order=False,
             parent_cmd=self,
             track_message=f"Setting metadata ({len(seq)} samples)",
         )
+
+
+class FilterDuplicatesCommand(PipelimeCommand, title="filter-duplicates"):
+    """Filter duplicated samples based on the hash of a set of items."""
+
+    input: pl_interfaces.InputDatasetInterface = (
+        pl_interfaces.InputDatasetInterface.pyd_field(
+            alias="i", piper_port=PiperPortType.INPUT
+        )
+    )
+
+    output: pl_interfaces.OutputDatasetInterface = (
+        pl_interfaces.OutputDatasetInterface.pyd_field(
+            alias="o", piper_port=PiperPortType.OUTPUT
+        )
+    )
+
+    algorithm: str = pyd.Field(
+        "sha256",
+        description=(
+            "The hashing algorithm from `hashlib` to use. Only algorithms that"
+            "do not require parameters are supported."
+        ),
+    )
+
+    keys: t.Union[str, t.Sequence[str]] = pyd.Field(
+        ...,
+        alias="k",
+        description=(
+            "The keys to use for comparison. All items selected must be equal to"
+            "consider two samples as duplicates."
+        ),
+    )
+
+    grabber: pl_interfaces.GrabberInterface = pl_interfaces.GrabberInterface.pyd_field(
+        alias="g"
+    )
+
+    def run(self):
+        from pipelime.stages import StageSampleHash
+        from pipelime.sequences import DataStream
+
+        seq = self.input.create_reader()
+        hash_key = self._get_hash_key(list(seq[0].keys()))
+        keys = [self.keys] if isinstance(self.keys, str) else self.keys
+        stage = StageSampleHash(algorithm=self.algorithm, keys=keys, hash_key=hash_key)
+        seq = seq.map(stage)
+
+        # multi-processing friendly filtering
+        class _WriterHelper:
+            def __init__(self, output_pipe):
+                self.stream = DataStream(output_pipe=output_pipe)
+                self.curr_idx = 0
+                self.unique_hashes = set()
+
+            def __call__(self, sample):
+                sample_hash = sample[hash_key]()
+                sample = sample.remove_keys(hash_key)
+                if sample_hash not in self.unique_hashes:
+                    self.unique_hashes.add(sample_hash)
+                    self.stream.set_output(self.curr_idx, sample)
+                    self.curr_idx += 1
+
+        if self.output.zfill is None:
+            self.output.zfill = seq.best_zfill()
+        writer_helper = _WriterHelper(output_pipe=self.output.as_pipe())
+
+        # filter out samples that have a hash that appears more than once
+        self.grabber.grab_all(
+            seq,
+            keep_order=True,
+            parent_cmd=self,
+            sample_fn=writer_helper,
+            track_message=f"Checking hashes ({len(seq)} samples)",
+        )
+
+    def _get_hash_key(self, keys: t.Sequence[str]) -> str:
+        """Get a key that has no conflict with the given keys.
+
+        Args:
+            keys (t.Sequence[str]): the keys of the samples
+
+        Returns:
+            str: the hash key
+        """
+        key = "hash"
+        while True:
+            if key not in keys:
+                return key
+            key += "_"
+
+
+class CopySharedItemsCommand(PipelimeCommand, title="copy-shared-items"):
+    """Copy shared items from a source dataset to a destination dataset. Datasets may
+    not have the same length."""
+
+    source: pl_interfaces.InputDatasetInterface = (
+        pl_interfaces.InputDatasetInterface.pyd_field(
+            alias="src",
+            piper_port=PiperPortType.INPUT,
+            description=(
+                "Where the shared items are copied from. Must have at least one "
+                "sample and one shared item."
+            ),
+        )
+    )
+    dest: pl_interfaces.InputDatasetInterface = (
+        pl_interfaces.InputDatasetInterface.pyd_field(
+            alias="dst",
+            piper_port=PiperPortType.INPUT,
+            description=(
+                "Where the shared items are copied to. Must have at least one sample "
+                "and any number of shared items. Source and destination datasets may "
+                "not have the same length, as only the shared items are copied."
+            ),
+        )
+    )
+    output: pl_interfaces.OutputDatasetInterface = (
+        pl_interfaces.OutputDatasetInterface.pyd_field(
+            alias="o",
+            piper_port=PiperPortType.OUTPUT,
+            description=("Where the resulting dataset is written to."),
+        )
+    )
+    grabber: pl_interfaces.GrabberInterface = pl_interfaces.GrabberInterface.pyd_field(
+        alias="g"
+    )
+    key_list: t.Sequence[str] = pyd.Field(
+        ...,
+        alias="k",
+        description=("The keys to copy. Must be present in source dataset."),
+    )
+    force_shared: bool = pyd.Field(
+        False,
+        alias="f",
+        description=("If True, the items will be copied as shared items"),
+    )
+
+    def run(self):
+        from pipelime.stages.item_replacement import StageCopyItems
+
+        src_seq = self.source.create_reader()
+        dst_seq = self.dest.create_reader()
+
+        src_sample = src_seq[0]
+
+        stage = StageCopyItems(
+            source=src_sample,
+            k=self.key_list,  # type: ignore
+            f=self.force_shared,  # type: ignore
+        )
+
+        out_seq = dst_seq.map(stage)
+
+        out_seq = self.output.append_writer(out_seq)
+
+        self.grabber.grab_all(
+            out_seq,
+            grab_context_manager=self.output.serialization_cm(),
+            keep_order=False,
+            parent_cmd=self,
+            track_message=f"Copying items ({len(out_seq)} samples)",
+        )
```

### Comparing `pipelime_python-1.5.0/pipelime/commands/interfaces.py` & `pipelime_python-1.6.0/pipelime/commands/interfaces.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/commands/piper.py` & `pipelime_python-1.6.0/pipelime/commands/piper.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,19 +1,26 @@
 import typing as t
+from abc import abstractmethod
 from enum import Enum
 from pathlib import Path
-from loguru import logger
 
-from pydantic import Field, PrivateAttr, PositiveInt
+from loguru import logger
+from pydantic import BaseModel, Field, PositiveInt, PrivateAttr
 
+from pipelime.choixe.utils.io import PipelimeTemporaryDirectory
 from pipelime.piper import PipelimeCommand, PiperPortType
 
 if t.TYPE_CHECKING:
     from pipelime.piper.graph import DAGNodesGraph
 
+T_NODES = t.Mapping[
+    str,
+    t.Union[PipelimeCommand, t.Mapping[str, t.Optional[t.Mapping[str, t.Any]]]],
+]
+
 
 class WatcherBackend(Enum):
     """The watcher backend to use."""
 
     RICH = "rich"
     TQDM = "tqdm"
 
@@ -23,51 +30,46 @@
             WatcherBackend.TQDM: "TQDM_BARS",
         }[self]
 
 
 class PiperGraphCommandBase(PipelimeCommand):
     """Base class for piper-aware commands."""
 
-    nodes: t.Mapping[
-        str, t.Union[PipelimeCommand, t.Mapping[str, t.Optional[t.Mapping[str, t.Any]]]]
-    ] = Field(
-        ...,
-        alias="n",
-        description=(
-            "A DAG of commands as a `<node>: <command>` mapping. The command can be a "
-            "`<name>: <args>` mapping, where `<name>` is `pipe`, `clone`, `split` etc, "
-            "while `<args>` is a mapping of its arguments."
-        ),
-        piper_port=PiperPortType.INPUT,
-    )
     include: t.Union[str, t.Sequence[str], None] = Field(
-        None, alias="i", description="Nodes not in this list are not run."
+        None, alias="in", description="Nodes not in this list are not run."
     )
     exclude: t.Union[str, t.Sequence[str], None] = Field(
-        None, alias="e", description="Nodes in this list are not run."
+        None, alias="ex", description="Nodes in this list are not run."
     )
 
     _piper_graph: t.Optional["DAGNodesGraph"] = PrivateAttr(None)
 
     @property
+    @abstractmethod
+    def nodes_graph(self) -> T_NODES:
+        """The DAG of commands as a `<node>: <command>` mapping."""
+
+    @property
     def piper_graph(self) -> "DAGNodesGraph":
-        from pipelime.piper.model import DAGModel, NodesDefinition
         from pipelime.piper.graph import DAGNodesGraph
+        from pipelime.piper.model import DAGModel, NodesDefinition
 
         if not self._piper_graph:
             inc_n = [self.include] if isinstance(self.include, str) else self.include
             exc_n = [self.exclude] if isinstance(self.exclude, str) else self.exclude
 
             def _node_to_run(node: str) -> bool:
                 return (inc_n is None or node in inc_n) and (
                     exc_n is None or node not in exc_n
                 )
 
             nodes = {
-                name: cmd for name, cmd in self.nodes.items() if _node_to_run(name)
+                name: cmd
+                for name, cmd in self.nodes_graph.items()
+                if _node_to_run(name)
             }
             dag = DAGModel(nodes=NodesDefinition.create(nodes))
             self._piper_graph = DAGNodesGraph.build_nodes_graph(
                 dag, **self._nodes_graph_building_kwargs()
             )
         return self._piper_graph
 
@@ -78,51 +80,61 @@
         return {}
 
 
 class GraphPortForwardingCommand(PiperGraphCommandBase):
     """A command that uses the root and leaf data nodes of the internal DAG
     as its own I/O ports."""
 
+    @property
+    def input_mapping(self) -> t.Optional[t.Mapping[str, str]]:
+        """Optional mapping from graph input data keys and desired keys."""
+        return None
+
+    @property
+    def output_mapping(self) -> t.Optional[t.Mapping[str, str]]:
+        """Optional mapping from graph output data keys and desired keys."""
+        return None
+
+    def _mapped_name(self, name: str, mapping: t.Optional[t.Mapping[str, str]]) -> str:
+        return mapping.get(name, "") if mapping else name
+
     def get_inputs(self) -> t.Dict[str, t.Any]:
+        inmap = self.input_mapping
         return {
-            self.piper_graph.get_input_port_name(x): x.path
+            self._mapped_name(self.piper_graph.get_input_port_name(x), inmap): x.path
             for x in self.piper_graph.input_data_nodes
         }
 
     def get_outputs(self) -> t.Dict[str, t.Any]:
+        outmap = self.output_mapping
         return {
-            self.piper_graph.get_output_port_name(x): x.path
+            self._mapped_name(self.piper_graph.get_output_port_name(x), outmap): x.path
             for x in self.piper_graph.output_data_nodes
         }
 
 
-class RunCommand(GraphPortForwardingCommand, title="run"):
-    """Executes a DAG of pipelime commands.
-    NB: when run inside a graph, `token` and `watch` are ignored."""
-
+class RunCommandBase(GraphPortForwardingCommand):
     token: t.Optional[str] = Field(
         None,
-        alias="t",
+        alias="tk",
         description=(
             "The execution token. If not specified, a new token will be generated."
         ),
     )
     watch: t.Union[bool, WatcherBackend, Path, None] = Field(
         None,
-        alias="w",
         description=(
             "Monitor the execution in the current console. "
             "Defaults to True if no token is provided, False othrewise. "
             "If a string is provided, it is used as the name of the watcher backend or "
             "the json/yaml progress file path."
         ),
     )
     force_gc: t.Union[bool, str, t.Sequence[str]] = Field(
         False,
-        alias="gc",
         description=(
             "Force garbage collection before and after the execution of all nodes, "
             "if True, or only for the specified nodes."
         ),
     )
 
     def run(self):
@@ -147,18 +159,16 @@
             prefix = ""
 
             # activate piper, so that this node will send updates to the watchers
             self.set_piper_info(token=token, node=message)
 
         # setup the direct track callback
         if watch:
+            from pipelime.piper.progress.listener.factory import ListenerCallbackFactory
             from pipelime.piper.progress.tracker.direct import DirectTrackCallback
-            from pipelime.piper.progress.listener.factory import (
-                ListenerCallbackFactory,
-            )
 
             if isinstance(watch, Path):
                 callback = ListenerCallbackFactory.get_callback("FILE", filename=watch)
             else:
                 callback = ListenerCallbackFactory.get_callback(
                     watch.listener_key()
                     if isinstance(watch, WatcherBackend)
@@ -181,18 +191,41 @@
                 ),
             )
 
             if not executor(self.piper_graph, token=token, force_gc=self.force_gc):
                 raise RuntimeError("Piper execution failed")
 
 
-class DrawCommand(PiperGraphCommandBase, title="draw"):
+class ClassicPiperGraphCommand(BaseModel):
+    nodes: T_NODES = Field(
+        ...,
+        alias="n",
+        description=(
+            "A DAG of commands as a `<node>: <command>` mapping. The command can be a "
+            "`<name>: <args>` mapping, where `<name>` is `pipe`, `clone`, `split` etc, "
+            "while `<args>` is a mapping of its arguments."
+        ),
+        piper_port=PiperPortType.INPUT,
+    )
+
+    @property
+    def nodes_graph(self) -> T_NODES:
+        return self.nodes
+
+
+class RunCommand(ClassicPiperGraphCommand, RunCommandBase, title="run"):
+    """Executes a DAG of pipelime commands.
+    NB: when run inside a graph, `token` and `watch` are ignored."""
+
+
+class DrawCommand(ClassicPiperGraphCommand, PiperGraphCommandBase, title="draw"):
     """Draws a pipelime DAG."""
 
     class DrawBackendChoice(Enum):
+        AUTO = "auto"
         GRAPHVIZ = "graphviz"
         MERMAID = "mermaid"
 
     class EllipsesChoice(Enum):
         START = "start"
         MIDDLE = "middle"
         END = "end"
@@ -210,15 +243,15 @@
         None,
         description="Raw graph representation",
         exclude=True,
         repr=False,
         piper_port=PiperPortType.OUTPUT,
     )
     backend: DrawBackendChoice = Field(
-        DrawBackendChoice.GRAPHVIZ, alias="b", description="The graph backend to use."
+        DrawBackendChoice.AUTO, alias="b", description="The graph backend to use."
     )
     open: bool = Field(
         False,
         description=(
             "If `output` has been set, open the image file in the default viewer."
         ),
     )
@@ -266,14 +299,22 @@
             if platform.system() == "Darwin":  # macOS
                 subprocess.call(("open", filename))
             elif platform.system() == "Windows":  # Windows
                 os.startfile(filename)
             else:  # linux variants #TODO: verify!
                 subprocess.call(("xdg-open", filename))
 
+        if self.backend == self.DrawBackendChoice.AUTO:
+            try:
+                import pygraphviz  # noqa: F401
+
+                self.backend = self.DrawBackendChoice.GRAPHVIZ
+            except ImportError:
+                self.backend = self.DrawBackendChoice.MERMAID
+
         graph = self.piper_graph
         drawer = NodesGraphDrawerFactory.create(self.backend.value)
 
         extra = self.extra_args or {}
 
         # raw graph representation
         if self.raw:
@@ -314,24 +355,25 @@
     port: t.Optional[int] = Field(
         None,
         alias="p",
         description="The port to listen to. Use the default port if not specified.",
     )
 
     def run(self):
+        from time import sleep
+
         from pipelime.piper.progress.listener.base import Listener
         from pipelime.piper.progress.listener.factory import (
             ListenerCallbackFactory,
             ProgressReceiverFactory,
         )
         from pipelime.utils.context_managers import CatchSignals
-        from time import sleep
 
         receiver = ProgressReceiverFactory.get_receiver(
-            self.token, **({"port": self.port} if self.port else {})
+            self.token, **({"port": self.port} if self.port else {})  # type: ignore
         )
         if isinstance(self.watcher, WatcherBackend):
             callback = ListenerCallbackFactory.get_callback(
                 self.watcher.listener_key(), show_token=self.token is None
             )
         else:
             callback = ListenerCallbackFactory.get_callback(
@@ -341,7 +383,92 @@
         listener.start()
 
         with CatchSignals() as catcher:
             while not catcher.interrupted:
                 sleep(0.1)
 
         listener.stop()
+
+
+class DagBaseCommand(RunCommandBase):
+    """Base class for Python DAG Object.
+    Derived class should add custom fields (beware to not overwrite
+    base class names and aliases!) and implement the `create_graph` method.
+    The `input_mapping` and `output_mapping` properties can be used to return
+    a custom name for the input and output data keys.
+    """
+
+    folder_debug: Path = Field(None, description="Path to Debug dir folder.")
+    draw: t.Union[bool, Path, t.Mapping] = Field(
+        False,
+        description=(
+            "Draw the graph and exit. `+draw` to just show, "
+            "`+draw graph.png` to save to disk or "
+            "`+draw.o graph.png +draw.b mermaid ...` for a full control on "
+            "the underlying DrawCommand."
+        ),
+    )
+
+    _temp_folder: PipelimeTemporaryDirectory = PrivateAttr(None)
+    _nodes: T_NODES = PrivateAttr(None)
+
+    def __init__(self, **data):
+        super().__init__(**data)
+
+        if not self.folder_debug:
+            self._temp_folder = PipelimeTemporaryDirectory()
+            self.folder_debug = self._temp_folder.name
+
+    def _validate_graph(self):
+        """Validates the graph before executing it.
+
+        Raises:
+            RuntimeError: if cycle is found.
+        """
+        from networkx.algorithms.cycles import find_cycle
+        from networkx.exception import NetworkXNoCycle
+
+        try:
+            edges_cycles = find_cycle(self.piper_graph.raw_graph)
+        except NetworkXNoCycle:
+            return
+
+        raise RuntimeError(f"Cycle found {edges_cycles}")  # type: ignore
+
+    def draw_graph(self, output: t.Optional[Path] = None, **kwargs) -> None:
+        """Draws a pipelime DAG.
+
+        Args:
+            output (Path, optional): The output file. If not specified, the graph will
+                be shown in a window. Defaults to None.
+            **kwargs: Any other argument accepted by the DrawCommand.
+        """
+        nodes = self.nodes_graph
+        if "o" not in kwargs and "output" not in kwargs:
+            kwargs["output"] = output
+        drawer = DrawCommand(nodes=nodes, **kwargs)  # type: ignore
+        drawer.run()
+
+    @abstractmethod
+    def create_graph(self) -> T_NODES:
+        """Creates the graph nodes.
+
+        Returns:
+            T_NODES: a dictionary containing the mapping between node names and nodes.
+        """
+        pass
+
+    @property
+    def nodes_graph(self) -> T_NODES:
+        if self._nodes is None:
+            self._nodes = self.create_graph()
+        return self._nodes
+
+    def run(self) -> None:
+        self._validate_graph()
+        if self.draw:
+            output = self.draw if isinstance(self.draw, Path) else None
+            self.draw_graph(
+                output, **(self.draw if isinstance(self.draw, t.Mapping) else {})
+            )
+            return
+        return super().run()
```

### Comparing `pipelime_python-1.5.0/pipelime/commands/shell.py` & `pipelime_python-1.6.0/pipelime/commands/shell.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/commands/split_ops.py` & `pipelime_python-1.6.0/pipelime/commands/split_ops.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/commands/tempman.py` & `pipelime_python-1.6.0/pipelime/commands/tempman.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,23 +1,17 @@
-import typing as t
 import datetime as dt
+import typing as t
 from enum import Enum
-from loguru import logger
 
-from pydantic import Field, ByteSize
+from loguru import logger
+from pydantic import ByteSize, Field
 
 from pipelime.piper import PipelimeCommand
 
 
-class FileTime(Enum):
-    CTIME = "ctime"
-    MTIME = "mtime"
-    ATIME = "atime"
-
-
 class SortBy(Enum):
     NAME = "name"
     SIZE = "size"
     TIME = "time"
 
 
 date_or_time_t = t.Union[dt.datetime, dt.date, dt.time]
@@ -77,25 +71,22 @@
         False,
         alias="au",
         description="Clear folders created by any user (overrides 'user' option)",
     )
 
     all: bool = Field(False, description="Clear all temporary folders")
 
-    file_time: FileTime = Field(
-        FileTime.ATIME, alias="t", description="File time to use"
-    )
     sort_by: SortBy = Field(
         SortBy.TIME, alias="s", description="Sort by name, size or time"
     )
 
     def run(self):
         import shutil
+
         from rich import print as rprint
-        from rich.rule import Rule
         from rich.prompt import Confirm
 
         if (
             self.after is None
             and self.before is None
             and self.delta_after is None
             and self.delta_before is None
@@ -108,17 +99,17 @@
         ):
             self.show_usage()
             return
 
         to_delete = self._folders_to_delete()
 
         if not self.force and to_delete:
-            grid, total_size = self._paths_table(to_delete)
-            rprint(Rule(title=f"Total clean up: {self._human_size(total_size)}"))
-            rprint(grid)
+            table, total_size = self._paths_table(to_delete)
+            table.title = f"\nTotal clean up: {self._human_size(total_size)}"
+            rprint(table)
             print("")
             if not Confirm.ask(
                 "Do you want to PERMANENTLY delete these folders?", default=False
             ):
                 return
 
         for p in to_delete:
@@ -129,30 +120,29 @@
                     f"Error deleting {pt}: {exc}"
                 ),
             )
 
     def show_usage(self):
         from rich import print as rprint
         from rich.markup import escape
-        from rich.rule import Rule
 
         from pipelime.choixe.utils.io import PipelimeTmp
-        from pipelime.cli.pretty_print import print_info, print_debug
+        from pipelime.cli.pretty_print import print_info
 
         print_info(f"Temporary folder: {PipelimeTmp.base_dir()}")
-        print_debug(f"showing {self.file_time.value}", end="\n\n")
 
         for user, paths in PipelimeTmp.get_temp_dirs().items():
-            grid, total_size = self._paths_table(paths)
-            rprint(Rule(title=f"{escape(user)} ({self._human_size(total_size)})"))
-            rprint(grid)
+            table, total_size = self._paths_table(paths)
+            table.title = f"\n{escape(user)} ({self._human_size(total_size)})"
+            rprint(table)
             print("")
 
     def _folders_to_delete(self):
         from pathlib import Path
+
         from pipelime.choixe.utils.io import PipelimeTmp
 
         if self.all:
             return [p for ps in PipelimeTmp.get_temp_dirs().values() for p in ps]
 
         delta_after_t = (
             dt.datetime.now() - self.delta_after if self.delta_after else None
@@ -197,21 +187,22 @@
                     continue
                 to_delete.append(p)
         return to_delete
 
     def _paths_table(self, paths: t.Sequence[str]):
         import time
         from pathlib import Path
+
         from rich.markup import escape
         from rich.table import Column, Table
 
-        grid = Table.grid(
-            Column(overflow="fold"),
-            Column(overflow="fold"),
-            Column(overflow="fold"),
+        table = Table(
+            Column("Path", justify="center", overflow="fold"),
+            Column("Last Modification Time", justify="center", overflow="fold"),
+            Column("Size", justify="center", overflow="fold"),
             padding=(0, 5),
         )
 
         total_size = 0
         rows = []
 
         for p in paths:
@@ -229,51 +220,57 @@
             key=lambda x: x[1]
             if self.sort_by is SortBy.TIME
             else (x[2] if self.sort_by is SortBy.SIZE else x[0].stem),
             reverse=self.sort_by is SortBy.SIZE,
         )
 
         for r in rows:
-            grid.add_row(
+            table.add_row(
                 f"[link={r[0].as_uri()}]{escape(r[0].stem)}[/link]",
                 escape(time.ctime(r[1])),
                 self._human_size(r[2]),
             )
 
-        return grid, total_size
+        return table, total_size
 
-    def _get_time(self, path: str):
-        import os
+    def _get_size(self, root_path: str):
+        return self._traverse(root_path, self._size_update, 0)
 
-        if self.file_time is FileTime.ATIME:
-            return os.path.getatime(path)
-        if self.file_time is FileTime.MTIME:
-            return os.path.getmtime(path)
-        return os.path.getctime(path)
+    def _get_time(self, root_path: str):
+        return self._traverse(root_path, self._time_update, 0)
 
-    def _get_size(self, root_path: str):
+    def _traverse(self, root_path: str, update_fn: t.Callable, total_init):
         import os
 
-        total_size = 0
+        total = total_init
         seen = set()
-        for dirpath, _, filenames in os.walk(root_path):
+        for dirpath, subdirs, filenames in os.walk(root_path):
+            if not subdirs and not filenames:
+                filenames = [dirpath]
+
             for f in filenames:
                 fp = os.path.join(dirpath, f)
                 try:
                     stat = os.stat(fp)
                 except OSError:
                     continue
 
                 if stat.st_ino in seen:
                     continue
 
                 seen.add(stat.st_ino)
-                total_size += stat.st_size
+                total = update_fn(fp, stat, total)
+
+        return total
+
+    def _size_update(self, fp: str, stat, total):
+        return total + stat.st_size
 
-        return total_size
+    def _time_update(self, fp: str, stat, total):
+        return max(total, stat.st_mtime)
 
     def _human_size(self, size, u=[" bytes", "KB", "MB", "GB", "TB", "PB", "EB"]):
         return str(size) + u[0] if size < 1024 else self._human_size(size >> 10, u[1:])
 
     def _as_ts(self, dttm: t.Optional[date_or_time_t], inf_limit: bool):
         if dttm:
             try:
```

### Comparing `pipelime_python-1.5.0/pipelime/commands/toy_dataset.py` & `pipelime_python-1.6.0/pipelime/commands/toy_dataset.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/items/__init__.py` & `pipelime_python-1.6.0/pipelime/items/__init__.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/items/base.py` & `pipelime_python-1.6.0/pipelime/items/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/items/binary_item.py` & `pipelime_python-1.6.0/pipelime/items/binary_item.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/items/image_item.py` & `pipelime_python-1.6.0/pipelime/items/image_item.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/items/metadata_item.py` & `pipelime_python-1.6.0/pipelime/items/metadata_item.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/items/model3d_item.py` & `pipelime_python-1.6.0/pipelime/items/model3d_item.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/items/numpy_item.py` & `pipelime_python-1.6.0/pipelime/items/numpy_item.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/graph.py` & `pipelime_python-1.6.0/pipelime/piper/graph.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/model.py` & `pipelime_python-1.6.0/pipelime/piper/model.py`

 * *Files 5% similar despite different names*

```diff
@@ -29,25 +29,35 @@
 ) -> t.Callable[..., t.Type["PipelimeCommand"]]:
     ...
 
 
 def command(__func=None, *, title: t.Optional[str] = None, **__config_kwargs):
     """Creates a full-fledged PipelimeCommand from a general function.
     The command will have the same exact signature and docstring of the function.
-    Field names and types will taken from the function parameters and validated as usual.
-    Any function signature is allowed, including positional-only, keyword-only,
+    Field names and types will taken from the function parameters and validated as
+    usual. Any function signature is allowed, including positional-only, keyword-only,
     variable positional, variable keyword parameters. Variable positional and keyword
     can be annotated to get type checking and validation.
 
     You are encouraged to use pydantic.Field as default value to further specify any
     field properties, such as `default_factory`, `alias`, `description`, etc, which
     are used to show meaningful help messages through `pipelime help`.
     Also, call it with extra `__config_kwargs` to add any pydantic config parameters,
     such as `title`, `arbitrary_types_allowed`, etc.
 
+    NB: if the first function argument is named `self`, the command will be bound to it.
+
+    Args:
+        __func: function to be converted to a PipelimeCommand.
+        title: the title of the command.
+        __config_kwargs: extra pydantic config parameters.
+
+    Returns:
+        A PipelimeCommand class.
+
     Examples:
         Create a command with the same name of the function::
 
             @command
             def addup(a: int, b: int):
                 print(a + b)
 
@@ -91,14 +101,33 @@
             ):
                 '''Merge and print two lists.'''
                 print(first + second)
 
         then show the command help::
 
             $ pipelime merge help
+
+        Create a command which starts a pipelime task::
+
+            @command(bind=True)
+            def copy_data(
+                self,
+                src: InputDatasetInterface,
+                dst: OutputDatasetInterface,
+                grabber: GrabberInterface,
+            ):
+                seq = src.create_reader()
+                seq = dst.append_writer(seq)
+                grabber.grab_all(
+                    seq,
+                    grab_context_manager=dst.serialization_cm(),
+                    keep_order=False,
+                    parent_cmd=self,
+                    track_message=f"Copying...",
+                )
     """
 
     if title is not None:
         __config_kwargs["title"] = title
 
     def _make_cmd(func):
         import inspect
@@ -126,35 +155,40 @@
                 ann = p.annotation
 
             return (ann, value)
 
         # Translates signature to pydantic fields
         # and gathers positional arguments
         fsig = inspect.signature(func)
-        fields = {n: _make_field(p) for n, p in fsig.parameters.items()}
+        fsig_params = fsig.parameters
+        is_bound = (
+            fsig.parameters and next(iter(fsig.parameters.values())).name == "self"
+        )
+        if is_bound:
+            fsig_params = {k: v for k, v in fsig_params.items() if k != "self"}
+
+        fields = {n: _make_field(p) for n, p in fsig_params.items()}
         posonly_names = [
-            p.name for p in fsig.parameters.values() if p.kind is p.POSITIONAL_ONLY
+            p.name for p in fsig_params.values() if p.kind is p.POSITIONAL_ONLY
         ]
         poskw_names = [
-            p.name
-            for p in fsig.parameters.values()
-            if p.kind is p.POSITIONAL_OR_KEYWORD
+            p.name for p in fsig_params.values() if p.kind is p.POSITIONAL_OR_KEYWORD
         ]
         kwonly_names = [
-            p.name for p in fsig.parameters.values() if p.kind is p.KEYWORD_ONLY
+            p.name for p in fsig_params.values() if p.kind is p.KEYWORD_ONLY
         ]
         try:
             varpos_name = next(
-                p.name for p in fsig.parameters.values() if p.kind is p.VAR_POSITIONAL
+                p.name for p in fsig_params.values() if p.kind is p.VAR_POSITIONAL
             )
         except StopIteration:
             varpos_name = ""
         try:
             varkw_name = next(
-                p.name for p in fsig.parameters.values() if p.kind is p.VAR_KEYWORD
+                p.name for p in fsig_params.values() if p.kind is p.VAR_KEYWORD
             )
         except StopIteration:
             varkw_name = ""
 
         # set title to function name, if not specified
         __config_kwargs.setdefault("title", func.__name__)
 
@@ -199,19 +233,27 @@
                     kwargs = {}
 
                 # kwargs should be passed (user may have set extra="allow")
                 super(_FnModel, self).__init__(**data, **kwargs)
 
             def run(self):
                 # get all arguments in the right order
-                func(
-                    *[getattr(self, n) for n in posonly_names + poskw_names],
-                    *getattr(self, varpos_name, tuple()),
-                    **self.dict(include=set(kwonly_names + [varkw_name])),
-                )
+                if is_bound:
+                    func(
+                        self,
+                        *[getattr(self, n) for n in posonly_names + poskw_names],
+                        *getattr(self, varpos_name, tuple()),
+                        **self.dict(include=set(kwonly_names + [varkw_name])),
+                    )
+                else:
+                    func(
+                        *[getattr(self, n) for n in posonly_names + poskw_names],
+                        *getattr(self, varpos_name, tuple()),
+                        **self.dict(include=set(kwonly_names + [varkw_name])),
+                    )
 
         # override base docstring with a custom description
         _FnModel.__doc__ = (
             f"Autogenerated Pipelime command from `{func.__module__}.{func.__name__}`."
         )
 
         # create the pipelime command class
@@ -243,15 +285,15 @@
                 if value in (Ellipsis, Undefined):
                     return inspect.Parameter.empty
             return value
 
         fmodel.__signature__ = fsig.replace(
             parameters=[
                 p.replace(default=_unwrap_default(p.default))
-                for p in fsig.parameters.values()
+                for p in fsig_params.values()
             ],
             return_annotation=inspect.Signature.empty,
         )
         return fmodel
 
     if __func is None:
         return _make_cmd
```

### Comparing `pipelime_python-1.5.0/pipelime/piper/drawing/base.py` & `pipelime_python-1.6.0/pipelime/piper/drawing/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/drawing/factory.py` & `pipelime_python-1.6.0/pipelime/piper/drawing/factory.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/drawing/graphviz.py` & `pipelime_python-1.6.0/pipelime/piper/drawing/graphviz.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/drawing/mermaid.py` & `pipelime_python-1.6.0/pipelime/piper/drawing/mermaid.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/executors/base.py` & `pipelime_python-1.6.0/pipelime/piper/executors/base.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,13 +1,15 @@
+import time
 from abc import ABC, abstractmethod
 from pathlib import Path
-from typing import Optional, Union, Sequence
+from typing import Optional, Sequence, Union
 
 from loguru import logger
 
+from pipelime.cli.utils import time_to_str
 from pipelime.piper.graph import DAGNodesGraph, GraphNodeOperation
 from pipelime.piper.progress.listener.base import Listener
 from pipelime.piper.progress.listener.factory import (
     ListenerCallbackFactory,
     ProgressReceiverFactory,
 )
 from pipelime.piper.progress.tracker.base import TrackedTask
@@ -18,76 +20,103 @@
     implement the execution of a NodesGraph made of Nodes.
     """
 
     def __init__(self, node_prefix: str) -> None:
         super().__init__()
         self._node_prefix = node_prefix
         self._task = None
+        self._timers = {}
 
     @property
     def task(self) -> Optional[TrackedTask]:
         return self._task
 
     @task.setter
     def task(self, task: Optional[TrackedTask]):
         self._task = task
 
     def _set_piper_info(self, node: GraphNodeOperation, token: str):
         node.command.set_piper_info(token=token, node=self._node_prefix + node.name)
 
+    def _original_node_name(self, node: GraphNodeOperation) -> str:
+        return node.command._piper.node[len(self._node_prefix) :]
+
     def _log_message(self, message: str, *, token: str):
-        logger.debug(f"[prefix={self._node_prefix},token={token}] {message}")
+        logger.debug(f"[{token}/{self._node_prefix}*] {message}")
 
     def preproc_node(
         self,
         node: GraphNodeOperation,
         graph: DAGNodesGraph,
         token: str,
         force_gc: Union[bool, str, Sequence[str]],
     ):
         self._set_piper_info(node=node, token=token)
-        self._log_message(f"Executing command: {node.command._piper.node}", token=token)
+        self._log_message(
+            f"[{self._original_node_name(node)}] Execution started", token=token
+        )
+        self._timers[node.command._piper.node] = time.perf_counter_ns()
 
     def postproc_node(
         self,
         node: GraphNodeOperation,
         graph: DAGNodesGraph,
         token: str,
         force_gc: Union[bool, str, Sequence[str]],
     ):
+        end_time = time.perf_counter_ns()
+        if node.command._piper.node in self._timers:
+            timestr = " in " + time_to_str(
+                end_time - self._timers[node.command._piper.node]
+            )
+        else:
+            timestr = ""
+
         if isinstance(force_gc, str):
             force_gc = [force_gc]
 
         if (isinstance(force_gc, bool) and force_gc) or (
             isinstance(force_gc, Sequence) and node.command._piper.node in force_gc
         ):
             import gc
 
-            self._log_message("Forcing garbage collection", token=token)
+            self._log_message(
+                f"[{self._original_node_name(node)}] Forcing garbage collection",
+                token=token,
+            )
             gc.collect()
 
         if self.task:
             self.task.advance()
-        self._log_message("Command execution completed", token=token)
+
+        self._log_message(
+            f"[{self._original_node_name(node)}] Execution completed{timestr}",
+            token=token,
+        )
 
     def __call__(
         self,
         graph: DAGNodesGraph,
         token: str = "",
         force_gc: Union[bool, str, Sequence[str]] = False,
     ) -> bool:
         self._log_message("Graph execution started", token=token)
         if self.task:
             self.task.restart()
 
+        start_time = time.perf_counter_ns()
         ret = self.exec(graph=graph, token=token, force_gc=force_gc)
+        end_time = time.perf_counter_ns()
 
         if self.task:
             self.task.finish()
-        self._log_message("Graph execution completed", token=token)
+        self._log_message(
+            f"Graph execution completed in {time_to_str(end_time - start_time)}",
+            token=token,
+        )
         return ret
 
     @abstractmethod
     def exec(
         self,
         graph: DAGNodesGraph,
         token: str,
```

### Comparing `pipelime_python-1.5.0/pipelime/piper/executors/factory.py` & `pipelime_python-1.6.0/pipelime/piper/executors/factory.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/executors/naive.py` & `pipelime_python-1.6.0/pipelime/piper/executors/naive.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/parsers/base.py` & `pipelime_python-1.6.0/pipelime/piper/parsers/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/parsers/choixe_parser.py` & `pipelime_python-1.6.0/pipelime/piper/parsers/choixe_parser.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/parsers/factory.py` & `pipelime_python-1.6.0/pipelime/piper/parsers/factory.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/model.py` & `pipelime_python-1.6.0/pipelime/piper/progress/model.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/estimator/base.py` & `pipelime_python-1.6.0/pipelime/piper/progress/estimator/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/estimator/naive.py` & `pipelime_python-1.6.0/pipelime/piper/progress/estimator/naive.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/listener/base.py` & `pipelime_python-1.6.0/pipelime/piper/progress/listener/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/listener/factory.py` & `pipelime_python-1.6.0/pipelime/piper/progress/listener/factory.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/listener/callbacks/file.py` & `pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/file.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/listener/callbacks/rich_table.py` & `pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/rich_table.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/listener/callbacks/tqdm_bars.py` & `pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/tqdm_bars.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/listener/receiver/zmq.py` & `pipelime_python-1.6.0/pipelime/piper/progress/listener/receiver/zmq.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/tracker/base.py` & `pipelime_python-1.6.0/pipelime/piper/progress/tracker/base.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,7 +1,8 @@
+import shutil
 from abc import ABC, abstractmethod
 from itertools import count
 from typing import Iterable, Optional, Sequence, Union
 
 from pipelime.piper.progress.model import OperationInfo, ProgressUpdate
 
 
@@ -77,43 +78,63 @@
         )
         for cb in self._callbacks:
             cb.update(prog)
 
 
 class TqdmTask(TrackedTask):
     @staticmethod
+    def _tty_length():
+        return shutil.get_terminal_size((80, 20)).columns
+
+    @staticmethod
+    def _clip_message(msg: str, length: int) -> str:
+        return msg if len(msg) <= length else msg[: length - 3] + "..."
+
+    @staticmethod
     def default_bar(
         iterable=None,
         *,
         total=None,
         message=None,
         bar_width=None,
         ncols=None,
         position=None,
     ):
         from tqdm import tqdm
 
+        tty_length = TqdmTask._tty_length()
         bar = tqdm(
             iterable,
             total=len(iterable) if total is None else total,  # type: ignore
             colour="#4CAE4F",
             position=position,
-            ncols=88 if ncols is None else (None if ncols <= 0 else ncols),
+            ncols=tty_length if ncols is None else (None if ncols <= 0 else ncols),
+            dynamic_ncols=ncols is None,
             bar_format=(
                 None
                 if bar_width is None
                 else "{desc} {percentage:3.0f}%|{bar:" + str(bar_width) + "}{r_bar}"
             ),
         )
         TqdmTask._set_description(bar, message)
         return bar
 
     @staticmethod
     def _set_description(bar, message: Optional[str]):
-        bar.set_description_str("🍋 " + message if message else "🍋")
+        # Hardcoded factor: the message will not be longer than the 40% of the
+        # TTY width. This should be appropriate for most cases.
+        factor = 0.4
+        maxlen = int(TqdmTask._tty_length() * factor)
+
+        # Format the message, adding emoji and clipping it if necessary
+        message = "🍋 " + message if message else "🍋"
+        message = TqdmTask._clip_message(message, maxlen)
+
+        # Set the description
+        bar.set_description_str(message)
 
     def __init__(
         self,
         total: int,
         message: str,
         bar_width: Optional[int] = None,
         total_width: Optional[int] = None,
```

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/tracker/direct.py` & `pipelime_python-1.6.0/pipelime/piper/progress/tracker/direct.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/tracker/factory.py` & `pipelime_python-1.6.0/pipelime/piper/progress/tracker/factory.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/tracker/loguru.py` & `pipelime_python-1.6.0/pipelime/piper/progress/tracker/loguru.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/piper/progress/tracker/zmq.py` & `pipelime_python-1.6.0/pipelime/piper/progress/tracker/zmq.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/remotes/base.py` & `pipelime_python-1.6.0/pipelime/remotes/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/remotes/s3_remote.py` & `pipelime_python-1.6.0/pipelime/remotes/s3_remote.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/remotes/shared_folder_remote.py` & `pipelime_python-1.6.0/pipelime/remotes/shared_folder_remote.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/sequences/direct_access.py` & `pipelime_python-1.6.0/pipelime/sequences/direct_access.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/sequences/grabber.py` & `pipelime_python-1.6.0/pipelime/sequences/grabber.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/sequences/sample.py` & `pipelime_python-1.6.0/pipelime/sequences/sample.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/sequences/samples_sequence.py` & `pipelime_python-1.6.0/pipelime/sequences/samples_sequence.py`

 * *Files 2% similar despite different names*

```diff
@@ -347,14 +347,29 @@
         """A SamplesSequence loading data from an Underfolder dataset.
         Run `pipelime help from_underfolder` to read the complete documentation.
         """
         ...
 
     @samples_sequence_stub
     @staticmethod
+    def from_images(
+        folder: "Path",  # type: ignore # noqa: E602,F821
+        *,
+        must_exist: bool = True,
+        image_key: str = "image",
+        sort_files: bool = True,
+        recursive: bool = True,
+    ) -> SamplesSequence:
+        """A SamplesSequence loading images from a folder.
+        Run `pipelime help from_images` to read the complete documentation.
+        """
+        ...
+
+    @samples_sequence_stub
+    @staticmethod
     def toy_dataset(
         length: int,
         *,
         with_images: bool = True,
         with_masks: bool = True,
         with_instances: bool = True,
         with_objects: bool = True,
```

### Comparing `pipelime_python-1.5.0/pipelime/sequences/utils.py` & `pipelime_python-1.6.0/pipelime/sequences/utils.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/sequences/pipes/base.py` & `pipelime_python-1.6.0/pipelime/sequences/pipes/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/sequences/pipes/mapping.py` & `pipelime_python-1.6.0/pipelime/sequences/pipes/mapping.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/sequences/pipes/operations.py` & `pipelime_python-1.6.0/pipelime/sequences/pipes/operations.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/sequences/pipes/validation.py` & `pipelime_python-1.6.0/pipelime/sequences/pipes/validation.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/sequences/pipes/writers.py` & `pipelime_python-1.6.0/pipelime/sequences/pipes/writers.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/sequences/sources/from_callable.py` & `pipelime_python-1.6.0/pipelime/sequences/sources/from_callable.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/sequences/sources/raw.py` & `pipelime_python-1.6.0/pipelime/sequences/sources/raw.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/sequences/sources/readers.py` & `pipelime_python-1.6.0/pipelime/sequences/sources/readers.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,49 +1,45 @@
 import os
 import typing as t
 from pathlib import Path
-from loguru import logger
 
-import pydantic as pyd
+from loguru import logger
+from pydantic import Field, PrivateAttr, validator
 
-import pipelime.sequences as pls
+from pipelime.sequences import Sample, SamplesSequence, source_sequence
 
 
-@pls.source_sequence
-class UnderfolderReader(pls.SamplesSequence, title="from_underfolder"):
+@source_sequence
+class UnderfolderReader(SamplesSequence, title="from_underfolder"):
     """A SamplesSequence loading data from an Underfolder dataset."""
 
-    folder: Path = pyd.Field(
-        ..., description="The root folder of the Underfolder dataset."
-    )
-    merge_root_items: bool = pyd.Field(
+    folder: Path = Field(..., description="The root folder of the Underfolder dataset.")
+    merge_root_items: bool = Field(
         True,
         description=(
             "Adds root items as shared items "
             "to each sample (sample values take precedence)."
         ),
     )
-    must_exist: bool = pyd.Field(
+    must_exist: bool = Field(
         True, description="If True raises an error when `folder` does not exist."
     )
-    watch: bool = pyd.Field(
+    watch: bool = Field(
         False,
         description=(
             "If True, the dataset is scanned every time a new Sample is requested."
         ),
     )
 
-    _samples: t.List[t.Union[pls.Sample, t.Dict[str, str]]] = pyd.PrivateAttr(
+    _samples: t.List[t.Union[Sample, t.Dict[str, str]]] = PrivateAttr(
         default_factory=list
     )
-    _root_sample: t.Optional[t.Union[pls.Sample, t.Dict[str, str]]] = pyd.PrivateAttr(
-        None
-    )
+    _root_sample: t.Optional[t.Union[Sample, t.Dict[str, str]]] = PrivateAttr(None)
 
-    @pyd.validator("must_exist", always=True)
+    @validator("must_exist", always=True)
     def check_folder_exists(cls, v, values):
         if v:
             root_folder = values["folder"]
             if not root_folder.exists() or not root_folder.is_dir():
                 raise ValueError(f"Root folder {root_folder} does not exist.")
 
             data_folder = cls.data_path(root_folder)
@@ -63,23 +59,23 @@
             self._scan_sample_files()
 
     @property
     def data_folder(self) -> Path:
         return self.data_path(self.folder)
 
     @property
-    def root_sample(self) -> pls.Sample:
+    def root_sample(self) -> Sample:
         from pipelime.items import Item
 
         # user may change the value of `self.watch` at any time,
         # so both checks are necessary
         if self.watch or self._root_sample is None:
             self._scan_root_files()
-        if not isinstance(self._root_sample, pls.Sample):
-            self._root_sample = pls.Sample(
+        if not isinstance(self._root_sample, Sample):
+            self._root_sample = Sample(
                 {
                     k: Item.get_instance(v, shared_item=True)
                     for k, v in self._root_sample.items()  # type: ignore
                 }
             )
         return self._root_sample
 
@@ -106,20 +102,20 @@
             root_items: t.Dict[str, str] = {}
             with os.scandir(str(self.folder)) as it:
                 for entry in it:
                     if entry.is_file():
                         key = self._extract_key(entry.name)
                         if key:
                             root_items[key] = entry.path
-            self._root_sample = root_items if root_items else pls.Sample()
+            self._root_sample = root_items if root_items else Sample()
         else:  # pragma: no cover
             logger.warning(
                 f"{self.__class__}: root folder `{self.folder}` does not exist"
             )
-            self._root_sample = pls.Sample()
+            self._root_sample = Sample()
 
     def _scan_sample_files(self):
         data_folder = self.data_folder
         if data_folder.exists():
             samples = []
             with os.scandir(str(data_folder)) as it:
                 for entry in it:
@@ -139,25 +135,94 @@
 
     def size(self) -> int:
         if self.watch:
             self._scan_sample_files()
 
         return len(self._samples)
 
-    def get_sample(self, idx: int) -> pls.Sample:
+    def get_sample(self, idx: int) -> Sample:
         from pipelime.items import Item
 
         if self.watch:
             self._scan_sample_files()
 
         sample = self._samples[idx]
-        if not isinstance(sample, pls.Sample):
-            sample = pls.Sample(
-                {
-                    k: Item.get_instance(v, shared_item=False)
-                    for k, v in sample.items()
-                }
+        if not isinstance(sample, Sample):
+            sample = Sample(
+                {k: Item.get_instance(v, shared_item=False) for k, v in sample.items()}
             )
             if self.merge_root_items:
                 sample = self.root_sample.merge(sample)
             self._samples[idx] = sample
         return sample
+
+
+@source_sequence
+class SequenceFromImageFolders(SamplesSequence, title="from_images"):
+    """Recursively scan a folder tree and load all the images as samples."""
+
+    folder: Path = Field(
+        ..., description="The root folder in which to scan for images."
+    )
+    must_exist: bool = Field(
+        True, description="If True raises an error when `folder` does not exist."
+    )
+    image_key: str = Field("image", description="The key of the image item.")
+    sort_files: bool = Field(
+        False, description="If True, read the files in sorted order."
+    )
+    recursive: bool = Field(True, description="If True, scan the `folder` recursively.")
+
+    _samples: t.List[t.Union[str, Sample]] = PrivateAttr(default_factory=list)
+
+    @validator("must_exist", always=True)
+    def check_folder_exists(cls, v, values):
+        p = values["folder"]
+        if v and not p.exists():
+            raise ValueError(f"Root folder {p} does not exist.")
+        return v
+
+    def __init__(self, folder: Path, **data):
+        from pipelime.items import Item, ImageItem
+
+        super().__init__(folder=folder, **data)  # type: ignore
+        self._samples = []
+        self._scan_folder(
+            self.folder.as_posix(),
+            # grab all the extensions of the ImageItem subclasses
+            {
+                ext
+                for ext, item_cls in Item.ITEM_CLASSES.items()
+                if issubclass(item_cls, ImageItem)
+            },
+        )
+
+    def _scan_folder(self, folder: str, extensions: t.Container[str]):
+        if not self.folder.exists():
+            logger.warning(f"{self.__class__}: folder `{folder}` does not exist")
+            return
+
+        # NB: os.scandir is faster than pathlib
+        with os.scandir(folder) as it:
+            if self.sort_files:
+                it = sorted(it, key=lambda entry: entry.name)
+            for entry in it:
+                if (
+                    entry.is_file()
+                    and os.path.splitext(entry.name)[1].lower() in extensions
+                ):
+                    self._samples.append(entry.path)
+                elif entry.is_dir() and self.recursive:
+                    self._scan_folder(entry.path, extensions)
+
+    def size(self) -> int:
+        return len(self._samples)
+
+    def get_sample(self, idx: int) -> Sample:
+        from pipelime.items import Item
+
+        sample = self._samples[idx]
+        if not isinstance(sample, Sample):
+            image_item = Item.get_instance(sample, shared_item=False)  # type: ignore
+            sample = Sample({self.image_key: image_item})
+            self._samples[idx] = sample
+        return sample
```

### Comparing `pipelime_python-1.5.0/pipelime/sequences/sources/toy_dataset.py` & `pipelime_python-1.6.0/pipelime/sequences/sources/toy_dataset.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/stages/__init__.py` & `pipelime_python-1.6.0/pipelime/stages/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,16 +1,25 @@
 from pipelime.stages.base import (
     SampleStage,
     StageCompose,
     StageIdentity,
     StageLambda,
     StageInput,
 )
-from pipelime.stages.augmentations import StageAlbumentations
-from pipelime.stages.item_replacement import StageReplaceItem, StageSetMetadata
+from pipelime.stages.augmentations import (
+    StageAlbumentations,
+    StageResize,
+    StageCropAndPad,
+)
+from pipelime.stages.item_replacement import (
+    StageReplaceItem,
+    StageSetMetadata,
+    StageSampleHash,
+    StageShareItems,
+)
 from pipelime.stages.item_sources import StageForgetSource, StageUploadToRemote
 from pipelime.stages.key_transformations import (
     StageDuplicateKey,
     StageKeyFormat,
     StageKeysFilter,
     StageRemap,
 )
```

### Comparing `pipelime_python-1.5.0/pipelime/stages/base.py` & `pipelime_python-1.6.0/pipelime/stages/base.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 from __future__ import annotations
+
+import inspect
+import typing as t
 from abc import ABC, abstractmethod
 
 import pydantic as pyd
-import typing as t
-import inspect
 
 if t.TYPE_CHECKING:
     from pipelime.sequences import Sample
 
 
 class SampleStage(pyd.BaseModel, ABC, extra="forbid", copy_on_model_validation="none"):
     """Base class for all sample stages."""
@@ -79,14 +80,17 @@
             return StageInput(__root__=create_stage_from_config(str(value), None))
         if isinstance(value, t.Mapping):
             return StageInput(
                 __root__=create_stage_from_config(*next(iter(value.items())))
             )
         raise ValueError(f"Invalid stage definition: {value}")
 
+    def dict(self, *args, **kwargs) -> t.Mapping:
+        return {self.__root__.__config__.title: self.__root__.dict(*args, **kwargs)}
+
 
 class StageCompose(SampleStage, title="compose"):
     """Applies a sequence of stages."""
 
     stages: t.Sequence[StageInput] = pyd.Field(
         ...,
         description="The stages to apply. " + str(inspect.getdoc(StageInput)),
```

### Comparing `pipelime_python-1.5.0/pipelime/stages/entities.py` & `pipelime_python-1.6.0/pipelime/stages/entities.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/stages/item_info.py` & `pipelime_python-1.6.0/pipelime/stages/item_info.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/stages/item_sources.py` & `pipelime_python-1.6.0/pipelime/stages/item_sources.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/stages/key_transformations.py` & `pipelime_python-1.6.0/pipelime/stages/key_transformations.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/utils/context_managers.py` & `pipelime_python-1.6.0/pipelime/utils/context_managers.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/utils/inspection.py` & `pipelime_python-1.6.0/pipelime/utils/inspection.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pipelime/utils/pydantic_types.py` & `pipelime_python-1.6.0/pipelime/utils/pydantic_types.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/.gitignore` & `pipelime_python-1.6.0/.gitignore`

 * *Files 8% similar despite different names*

```diff
@@ -84,15 +84,15 @@
 # SageMath parsed files
 *.sage.py
 
 # dotenv
 .env
 
 # virtualenv
-.venv
+.venv*
 venv/
 ENV/
 
 # Spyder project settings
 .spyderproject
 .spyproject
```

### Comparing `pipelime_python-1.5.0/LICENSE` & `pipelime_python-1.6.0/LICENSE`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/README.md` & `pipelime_python-1.6.0/README.md`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.5.0/pyproject.toml` & `pipelime_python-1.6.0/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -41,29 +41,31 @@
     "albumentations>=1.0.0",
     "trimesh",
     "astunparse",
     "python-box",
     "deepdiff",
     "filelock",
     "pydash",
-    "pydantic>=1.10",
+    "pydantic>=1.10.8,<2",
     "schema",
     "pyzmq",
     "dictquery",
     "minio",
     "requests",
     "billiard",
+    "textual",
 ]
 dynamic = [ "version" ]
 
 [project.optional-dependencies]
 draw = ["pygraphviz"]
 tests = [
     "pytest",
     "pytest-cov",
+    "pytest-asyncio",
 ]
 dev = [
     "pylama",
     "black",
     "flake8",
 ]
 build = [
```

### Comparing `pipelime_python-1.5.0/PKG-INFO` & `pipelime_python-1.6.0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pipelime-python
-Version: 1.5.0
+Version: 1.6.0
 Summary: Data workflows, cli and dataflow automation.
 Project-URL: Source, https://github.com/eyecan-ai/pipelime-python
 Project-URL: Issues, https://github.com/eyecan-ai/pipelime-python/issues
 Project-URL: Documentation, http://pipelime-python.readthedocs.io/
 Author-email: "Eyecan.ai" <info@eyecan.ai>
 License: GNU General Public License v3 (GPLv3)
 License-File: LICENSE
@@ -28,22 +28,23 @@
 Requires-Dist: deepdiff
 Requires-Dist: dictquery
 Requires-Dist: filelock
 Requires-Dist: imageio>=2.17.0
 Requires-Dist: loguru
 Requires-Dist: minio
 Requires-Dist: numpy
-Requires-Dist: pydantic>=1.10
+Requires-Dist: pydantic<2,>=1.10.8
 Requires-Dist: pydash
 Requires-Dist: python-box
 Requires-Dist: pyyaml
 Requires-Dist: pyzmq
 Requires-Dist: requests
 Requires-Dist: rich>=9.9.0
 Requires-Dist: schema
+Requires-Dist: textual
 Requires-Dist: tifffile
 Requires-Dist: toml
 Requires-Dist: tqdm
 Requires-Dist: trimesh
 Requires-Dist: typer>=0.6
 Provides-Extra: build
 Requires-Dist: build; extra == 'build'
@@ -57,14 +58,15 @@
 Requires-Dist: sphinx-immaterial==0.11.3; extra == 'docs'
 Requires-Dist: sphinx==5.1.1; extra == 'docs'
 Requires-Dist: sphinxcontrib-mermaid==0.7.1; extra == 'docs'
 Provides-Extra: draw
 Requires-Dist: pygraphviz; extra == 'draw'
 Provides-Extra: tests
 Requires-Dist: pytest; extra == 'tests'
+Requires-Dist: pytest-asyncio; extra == 'tests'
 Requires-Dist: pytest-cov; extra == 'tests'
 Description-Content-Type: text/markdown
 
 
 # 🍋 `pipelime`
 
 [![Documentation Status](https://readthedocs.org/projects/pipelime-python/badge/?version=latest)](https://pipelime-python.readthedocs.io/en/latest/?badge=latest)
```

