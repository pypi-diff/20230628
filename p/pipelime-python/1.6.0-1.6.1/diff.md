# Comparing `tmp/pipelime_python-1.6.0.tar.gz` & `tmp/pipelime_python-1.6.1.tar.gz`

## Comparing `pipelime_python-1.6.0.tar` & `pipelime_python-1.6.1.tar`

### file list

```diff
@@ -1,119 +1,120 @@
--rw-r--r--   0        0        0      115 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/__init__.py
--rw-r--r--   0        0        0       52 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/__init__.py
--rw-r--r--   0        0        0    14915 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/xconfig.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/ast/__init__.py
--rw-r--r--   0        0        0     9723 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/ast/nodes.py
--rw-r--r--   0        0        0    13790 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/ast/parser.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/utils/__init__.py
--rw-r--r--   0        0        0     3587 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/utils/common.py
--rw-r--r--   0        0        0     5108 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/utils/imports.py
--rw-r--r--   0        0        0     5314 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/utils/io.py
--rw-r--r--   0        0        0    13100 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/utils/rand.py
--rw-r--r--   0        0        0      277 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/visitors/__init__.py
--rw-r--r--   0        0        0     1279 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/visitors/decoder.py
--rw-r--r--   0        0        0     7805 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/visitors/inspector.py
--rw-r--r--   0        0        0    13803 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/visitors/processor.py
--rw-r--r--   0        0        0     7932 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/visitors/unparser.py
--rw-r--r--   0        0        0     2757 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/choixe/visitors/walker.py
--rw-r--r--   0        0        0     2905 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/__init__.py
--rw-r--r--   0        0        0    27326 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/main.py
--rw-r--r--   0        0        0     7310 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/parser.py
--rw-r--r--   0        0        0    15208 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/pretty_print.py
--rw-r--r--   0        0        0     1845 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/subcommands.py
--rw-r--r--   0        0        0    22727 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/utils.py
--rw-r--r--   0        0        0    13769 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/wizard.py
--rw-r--r--   0        0        0       89 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/tui/__init__.py
--rw-r--r--   0        0        0     9900 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/tui/tui.py
--rw-r--r--   0        0        0     7248 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/cli/tui/utils.py
--rw-r--r--   0        0        0      695 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/__init__.py
--rw-r--r--   0        0        0    34047 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/general.py
--rw-r--r--   0        0        0    28216 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/interfaces.py
--rw-r--r--   0        0        0    15995 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/piper.py
--rw-r--r--   0        0        0     2459 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/shell.py
--rw-r--r--   0        0        0    13525 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/split_ops.py
--rw-r--r--   0        0        0     9227 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/tempman.py
--rw-r--r--   0        0        0     1059 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/commands/toy_dataset.py
--rw-r--r--   0        0        0      973 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/__init__.py
--rw-r--r--   0        0        0    30747 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/base.py
--rw-r--r--   0        0        0      770 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/binary_item.py
--rw-r--r--   0        0        0     3261 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/image_item.py
--rw-r--r--   0        0        0     2402 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/metadata_item.py
--rw-r--r--   0        0        0     2941 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/model3d_item.py
--rw-r--r--   0        0        0     1392 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/numpy_item.py
--rw-r--r--   0        0        0      395 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/items/pickle_item.py
--rw-r--r--   0        0        0       80 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/__init__.py
--rw-r--r--   0        0        0    18226 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/graph.py
--rw-r--r--   0        0        0    17058 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/model.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/drawing/__init__.py
--rw-r--r--   0        0        0     1055 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/drawing/base.py
--rw-r--r--   0        0        0      707 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/drawing/factory.py
--rw-r--r--   0        0        0    10954 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/drawing/graphviz.py
--rw-r--r--   0        0        0     7597 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/drawing/mermaid.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/executors/__init__.py
--rw-r--r--   0        0        0     6508 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/executors/base.py
--rw-r--r--   0        0        0     1023 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/executors/factory.py
--rw-r--r--   0        0        0     1319 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/executors/naive.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/parsers/__init__.py
--rw-r--r--   0        0        0     2116 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/parsers/base.py
--rw-r--r--   0        0        0      843 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/parsers/choixe_parser.py
--rw-r--r--   0        0        0      578 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/parsers/factory.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/__init__.py
--rw-r--r--   0        0        0      718 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/model.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/estimator/__init__.py
--rw-r--r--   0        0        0     1097 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/estimator/base.py
--rw-r--r--   0        0        0      440 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/estimator/factory.py
--rw-r--r--   0        0        0     1382 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/estimator/naive.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/__init__.py
--rw-r--r--   0        0        0     3096 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/base.py
--rw-r--r--   0        0        0     1295 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/factory.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/__init__.py
--rw-r--r--   0        0        0     2215 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/file.py
--rw-r--r--   0        0        0     3442 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/rich_table.py
--rw-r--r--   0        0        0     1945 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/tqdm_bars.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/receiver/__init__.py
--rw-r--r--   0        0        0     1621 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/listener/receiver/zmq.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/tracker/__init__.py
--rw-r--r--   0        0        0     6366 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/tracker/base.py
--rw-r--r--   0        0        0      803 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/tracker/direct.py
--rw-r--r--   0        0        0      728 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/tracker/factory.py
--rw-r--r--   0        0        0      749 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/tracker/loguru.py
--rw-r--r--   0        0        0     2791 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/piper/progress/tracker/zmq.py
--rw-r--r--   0        0        0      195 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/remotes/__init__.py
--rw-r--r--   0        0        0    12825 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/remotes/base.py
--rw-r--r--   0        0        0     6644 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/remotes/s3_remote.py
--rw-r--r--   0        0        0     4714 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/remotes/shared_folder_remote.py
--rw-r--r--   0        0        0      500 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/__init__.py
--rw-r--r--   0        0        0      949 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/direct_access.py
--rw-r--r--   0        0        0     6696 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/grabber.py
--rw-r--r--   0        0        0     8682 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/sample.py
--rw-r--r--   0        0        0    23171 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/samples_sequence.py
--rw-r--r--   0        0        0      432 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/torch.py
--rw-r--r--   0        0        0     7031 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/utils.py
--rw-r--r--   0        0        0      226 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/pipes/__init__.py
--rw-r--r--   0        0        0      525 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/pipes/base.py
--rw-r--r--   0        0        0     4356 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/pipes/mapping.py
--rw-r--r--   0        0        0    14141 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/pipes/operations.py
--rw-r--r--   0        0        0     1661 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/pipes/validation.py
--rw-r--r--   0        0        0     4613 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/pipes/writers.py
--rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/sources/__init__.py
--rw-r--r--   0        0        0      814 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/sources/from_callable.py
--rw-r--r--   0        0        0      633 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/sources/raw.py
--rw-r--r--   0        0        0     8094 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/sources/readers.py
--rw-r--r--   0        0        0     8015 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/sequences/sources/toy_dataset.py
--rw-r--r--   0        0        0      681 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/__init__.py
--rw-r--r--   0        0        0     9973 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/augmentations.py
--rw-r--r--   0        0        0     3280 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/base.py
--rw-r--r--   0        0        0    13512 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/entities.py
--rw-r--r--   0        0        0     1618 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/item_info.py
--rw-r--r--   0        0        0     5065 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/item_replacement.py
--rw-r--r--   0        0        0     2275 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/item_sources.py
--rw-r--r--   0        0        0     3261 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/stages/key_transformations.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/utils/__init__.py
--rw-r--r--   0        0        0     1430 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/utils/context_managers.py
--rw-r--r--   0        0        0     1004 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/utils/inspection.py
--rw-r--r--   0        0        0    23458 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pipelime/utils/pydantic_types.py
--rw-r--r--   0        0        0     1269 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/.gitignore
--rw-r--r--   0        0        0     1525 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/LICENSE
--rw-r--r--   0        0        0     6062 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/README.md
--rw-r--r--   0        0        0     2173 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/pyproject.toml
--rw-r--r--   0        0        0     8494 2020-02-02 00:00:00.000000 pipelime_python-1.6.0/PKG-INFO
+-rw-r--r--   0        0        0      115 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/__init__.py
+-rw-r--r--   0        0        0       52 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/__init__.py
+-rw-r--r--   0        0        0    14915 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/xconfig.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/ast/__init__.py
+-rw-r--r--   0        0        0     9723 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/ast/nodes.py
+-rw-r--r--   0        0        0    13790 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/ast/parser.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/utils/__init__.py
+-rw-r--r--   0        0        0     3587 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/utils/common.py
+-rw-r--r--   0        0        0     5108 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/utils/imports.py
+-rw-r--r--   0        0        0     5314 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/utils/io.py
+-rw-r--r--   0        0        0    13100 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/utils/rand.py
+-rw-r--r--   0        0        0      277 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/visitors/__init__.py
+-rw-r--r--   0        0        0     1279 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/visitors/decoder.py
+-rw-r--r--   0        0        0     7805 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/visitors/inspector.py
+-rw-r--r--   0        0        0    13803 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/visitors/processor.py
+-rw-r--r--   0        0        0     7932 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/visitors/unparser.py
+-rw-r--r--   0        0        0     2757 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/choixe/visitors/walker.py
+-rw-r--r--   0        0        0     2905 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/cli/__init__.py
+-rw-r--r--   0        0        0    27326 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/cli/main.py
+-rw-r--r--   0        0        0     7310 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/cli/parser.py
+-rw-r--r--   0        0        0    15208 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/cli/pretty_print.py
+-rw-r--r--   0        0        0     1845 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/cli/subcommands.py
+-rw-r--r--   0        0        0    22727 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/cli/utils.py
+-rw-r--r--   0        0        0    13769 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/cli/wizard.py
+-rw-r--r--   0        0        0       89 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/cli/tui/__init__.py
+-rw-r--r--   0        0        0      449 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/cli/tui/tui.css
+-rw-r--r--   0        0        0     9900 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/cli/tui/tui.py
+-rw-r--r--   0        0        0     7248 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/cli/tui/utils.py
+-rw-r--r--   0        0        0      695 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/commands/__init__.py
+-rw-r--r--   0        0        0    34047 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/commands/general.py
+-rw-r--r--   0        0        0    28216 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/commands/interfaces.py
+-rw-r--r--   0        0        0    15995 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/commands/piper.py
+-rw-r--r--   0        0        0     2459 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/commands/shell.py
+-rw-r--r--   0        0        0    13525 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/commands/split_ops.py
+-rw-r--r--   0        0        0     9227 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/commands/tempman.py
+-rw-r--r--   0        0        0     1059 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/commands/toy_dataset.py
+-rw-r--r--   0        0        0      973 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/items/__init__.py
+-rw-r--r--   0        0        0    30747 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/items/base.py
+-rw-r--r--   0        0        0      770 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/items/binary_item.py
+-rw-r--r--   0        0        0     3261 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/items/image_item.py
+-rw-r--r--   0        0        0     2402 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/items/metadata_item.py
+-rw-r--r--   0        0        0     2941 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/items/model3d_item.py
+-rw-r--r--   0        0        0     1392 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/items/numpy_item.py
+-rw-r--r--   0        0        0      395 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/items/pickle_item.py
+-rw-r--r--   0        0        0       80 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/__init__.py
+-rw-r--r--   0        0        0    18226 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/graph.py
+-rw-r--r--   0        0        0    17058 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/model.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/drawing/__init__.py
+-rw-r--r--   0        0        0     1055 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/drawing/base.py
+-rw-r--r--   0        0        0      707 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/drawing/factory.py
+-rw-r--r--   0        0        0    10954 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/drawing/graphviz.py
+-rw-r--r--   0        0        0     7597 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/drawing/mermaid.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/executors/__init__.py
+-rw-r--r--   0        0        0     6508 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/executors/base.py
+-rw-r--r--   0        0        0     1023 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/executors/factory.py
+-rw-r--r--   0        0        0     1319 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/executors/naive.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/parsers/__init__.py
+-rw-r--r--   0        0        0     2116 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/parsers/base.py
+-rw-r--r--   0        0        0      843 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/parsers/choixe_parser.py
+-rw-r--r--   0        0        0      578 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/parsers/factory.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/__init__.py
+-rw-r--r--   0        0        0      718 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/model.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/estimator/__init__.py
+-rw-r--r--   0        0        0     1097 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/estimator/base.py
+-rw-r--r--   0        0        0      440 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/estimator/factory.py
+-rw-r--r--   0        0        0     1382 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/estimator/naive.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/listener/__init__.py
+-rw-r--r--   0        0        0     3096 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/listener/base.py
+-rw-r--r--   0        0        0     1295 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/listener/factory.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/listener/callbacks/__init__.py
+-rw-r--r--   0        0        0     2215 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/listener/callbacks/file.py
+-rw-r--r--   0        0        0     3442 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/listener/callbacks/rich_table.py
+-rw-r--r--   0        0        0     1945 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/listener/callbacks/tqdm_bars.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/listener/receiver/__init__.py
+-rw-r--r--   0        0        0     1621 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/listener/receiver/zmq.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/tracker/__init__.py
+-rw-r--r--   0        0        0     6366 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/tracker/base.py
+-rw-r--r--   0        0        0      803 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/tracker/direct.py
+-rw-r--r--   0        0        0      728 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/tracker/factory.py
+-rw-r--r--   0        0        0      749 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/tracker/loguru.py
+-rw-r--r--   0        0        0     2791 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/piper/progress/tracker/zmq.py
+-rw-r--r--   0        0        0      195 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/remotes/__init__.py
+-rw-r--r--   0        0        0    12825 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/remotes/base.py
+-rw-r--r--   0        0        0     6644 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/remotes/s3_remote.py
+-rw-r--r--   0        0        0     4714 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/remotes/shared_folder_remote.py
+-rw-r--r--   0        0        0      500 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/__init__.py
+-rw-r--r--   0        0        0      949 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/direct_access.py
+-rw-r--r--   0        0        0     6696 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/grabber.py
+-rw-r--r--   0        0        0     8682 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/sample.py
+-rw-r--r--   0        0        0    23171 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/samples_sequence.py
+-rw-r--r--   0        0        0      432 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/torch.py
+-rw-r--r--   0        0        0     7031 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/utils.py
+-rw-r--r--   0        0        0      226 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/pipes/__init__.py
+-rw-r--r--   0        0        0      525 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/pipes/base.py
+-rw-r--r--   0        0        0     4356 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/pipes/mapping.py
+-rw-r--r--   0        0        0    14141 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/pipes/operations.py
+-rw-r--r--   0        0        0     1661 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/pipes/validation.py
+-rw-r--r--   0        0        0     4613 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/pipes/writers.py
+-rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/sources/__init__.py
+-rw-r--r--   0        0        0      814 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/sources/from_callable.py
+-rw-r--r--   0        0        0      633 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/sources/raw.py
+-rw-r--r--   0        0        0     8094 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/sources/readers.py
+-rw-r--r--   0        0        0     8015 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/sequences/sources/toy_dataset.py
+-rw-r--r--   0        0        0      681 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/stages/__init__.py
+-rw-r--r--   0        0        0     9973 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/stages/augmentations.py
+-rw-r--r--   0        0        0     3280 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/stages/base.py
+-rw-r--r--   0        0        0    13512 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/stages/entities.py
+-rw-r--r--   0        0        0     1618 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/stages/item_info.py
+-rw-r--r--   0        0        0     5065 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/stages/item_replacement.py
+-rw-r--r--   0        0        0     2275 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/stages/item_sources.py
+-rw-r--r--   0        0        0     3261 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/stages/key_transformations.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/utils/__init__.py
+-rw-r--r--   0        0        0     1430 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/utils/context_managers.py
+-rw-r--r--   0        0        0     1004 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/utils/inspection.py
+-rw-r--r--   0        0        0    23458 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pipelime/utils/pydantic_types.py
+-rw-r--r--   0        0        0     1269 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/.gitignore
+-rw-r--r--   0        0        0     1525 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/LICENSE
+-rw-r--r--   0        0        0     6062 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/README.md
+-rw-r--r--   0        0        0     2204 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/pyproject.toml
+-rw-r--r--   0        0        0     8502 2020-02-02 00:00:00.000000 pipelime_python-1.6.1/PKG-INFO
```

### Comparing `pipelime_python-1.6.0/pipelime/choixe/xconfig.py` & `pipelime_python-1.6.1/pipelime/choixe/xconfig.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/choixe/ast/nodes.py` & `pipelime_python-1.6.1/pipelime/choixe/ast/nodes.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/choixe/ast/parser.py` & `pipelime_python-1.6.1/pipelime/choixe/ast/parser.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/choixe/utils/common.py` & `pipelime_python-1.6.1/pipelime/choixe/utils/common.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/choixe/utils/imports.py` & `pipelime_python-1.6.1/pipelime/choixe/utils/imports.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/choixe/utils/io.py` & `pipelime_python-1.6.1/pipelime/choixe/utils/io.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/choixe/utils/rand.py` & `pipelime_python-1.6.1/pipelime/choixe/utils/rand.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/choixe/visitors/decoder.py` & `pipelime_python-1.6.1/pipelime/choixe/visitors/decoder.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/choixe/visitors/inspector.py` & `pipelime_python-1.6.1/pipelime/choixe/visitors/inspector.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/choixe/visitors/processor.py` & `pipelime_python-1.6.1/pipelime/choixe/visitors/processor.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/choixe/visitors/unparser.py` & `pipelime_python-1.6.1/pipelime/choixe/visitors/unparser.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/choixe/visitors/walker.py` & `pipelime_python-1.6.1/pipelime/choixe/visitors/walker.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/cli/__init__.py` & `pipelime_python-1.6.1/pipelime/cli/__init__.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/cli/main.py` & `pipelime_python-1.6.1/pipelime/cli/main.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/cli/parser.py` & `pipelime_python-1.6.1/pipelime/cli/parser.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/cli/pretty_print.py` & `pipelime_python-1.6.1/pipelime/cli/pretty_print.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/cli/subcommands.py` & `pipelime_python-1.6.1/pipelime/cli/subcommands.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/cli/utils.py` & `pipelime_python-1.6.1/pipelime/cli/utils.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/cli/wizard.py` & `pipelime_python-1.6.1/pipelime/cli/wizard.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/cli/tui/tui.py` & `pipelime_python-1.6.1/pipelime/cli/tui/tui.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/cli/tui/utils.py` & `pipelime_python-1.6.1/pipelime/cli/tui/utils.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/commands/__init__.py` & `pipelime_python-1.6.1/pipelime/commands/__init__.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/commands/general.py` & `pipelime_python-1.6.1/pipelime/commands/general.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/commands/interfaces.py` & `pipelime_python-1.6.1/pipelime/commands/interfaces.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/commands/piper.py` & `pipelime_python-1.6.1/pipelime/commands/piper.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/commands/shell.py` & `pipelime_python-1.6.1/pipelime/commands/shell.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/commands/split_ops.py` & `pipelime_python-1.6.1/pipelime/commands/split_ops.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/commands/tempman.py` & `pipelime_python-1.6.1/pipelime/commands/tempman.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/commands/toy_dataset.py` & `pipelime_python-1.6.1/pipelime/commands/toy_dataset.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/items/__init__.py` & `pipelime_python-1.6.1/pipelime/items/__init__.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/items/base.py` & `pipelime_python-1.6.1/pipelime/items/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/items/binary_item.py` & `pipelime_python-1.6.1/pipelime/items/binary_item.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/items/image_item.py` & `pipelime_python-1.6.1/pipelime/items/image_item.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/items/metadata_item.py` & `pipelime_python-1.6.1/pipelime/items/metadata_item.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/items/model3d_item.py` & `pipelime_python-1.6.1/pipelime/items/model3d_item.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/items/numpy_item.py` & `pipelime_python-1.6.1/pipelime/items/numpy_item.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/graph.py` & `pipelime_python-1.6.1/pipelime/piper/graph.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/model.py` & `pipelime_python-1.6.1/pipelime/piper/model.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/drawing/base.py` & `pipelime_python-1.6.1/pipelime/piper/drawing/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/drawing/factory.py` & `pipelime_python-1.6.1/pipelime/piper/drawing/factory.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/drawing/graphviz.py` & `pipelime_python-1.6.1/pipelime/piper/drawing/graphviz.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/drawing/mermaid.py` & `pipelime_python-1.6.1/pipelime/piper/drawing/mermaid.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/executors/base.py` & `pipelime_python-1.6.1/pipelime/piper/executors/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/executors/factory.py` & `pipelime_python-1.6.1/pipelime/piper/executors/factory.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/executors/naive.py` & `pipelime_python-1.6.1/pipelime/piper/executors/naive.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/parsers/base.py` & `pipelime_python-1.6.1/pipelime/piper/parsers/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/parsers/choixe_parser.py` & `pipelime_python-1.6.1/pipelime/piper/parsers/choixe_parser.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/parsers/factory.py` & `pipelime_python-1.6.1/pipelime/piper/parsers/factory.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/model.py` & `pipelime_python-1.6.1/pipelime/piper/progress/model.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/estimator/base.py` & `pipelime_python-1.6.1/pipelime/piper/progress/estimator/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/estimator/naive.py` & `pipelime_python-1.6.1/pipelime/piper/progress/estimator/naive.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/listener/base.py` & `pipelime_python-1.6.1/pipelime/piper/progress/listener/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/listener/factory.py` & `pipelime_python-1.6.1/pipelime/piper/progress/listener/factory.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/file.py` & `pipelime_python-1.6.1/pipelime/piper/progress/listener/callbacks/file.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/rich_table.py` & `pipelime_python-1.6.1/pipelime/piper/progress/listener/callbacks/rich_table.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/listener/callbacks/tqdm_bars.py` & `pipelime_python-1.6.1/pipelime/piper/progress/listener/callbacks/tqdm_bars.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/listener/receiver/zmq.py` & `pipelime_python-1.6.1/pipelime/piper/progress/listener/receiver/zmq.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/tracker/base.py` & `pipelime_python-1.6.1/pipelime/piper/progress/tracker/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/tracker/direct.py` & `pipelime_python-1.6.1/pipelime/piper/progress/tracker/direct.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/tracker/factory.py` & `pipelime_python-1.6.1/pipelime/piper/progress/tracker/factory.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/tracker/loguru.py` & `pipelime_python-1.6.1/pipelime/piper/progress/tracker/loguru.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/piper/progress/tracker/zmq.py` & `pipelime_python-1.6.1/pipelime/piper/progress/tracker/zmq.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/remotes/base.py` & `pipelime_python-1.6.1/pipelime/remotes/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/remotes/s3_remote.py` & `pipelime_python-1.6.1/pipelime/remotes/s3_remote.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/remotes/shared_folder_remote.py` & `pipelime_python-1.6.1/pipelime/remotes/shared_folder_remote.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/direct_access.py` & `pipelime_python-1.6.1/pipelime/sequences/direct_access.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/grabber.py` & `pipelime_python-1.6.1/pipelime/sequences/grabber.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/sample.py` & `pipelime_python-1.6.1/pipelime/sequences/sample.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/samples_sequence.py` & `pipelime_python-1.6.1/pipelime/sequences/samples_sequence.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/utils.py` & `pipelime_python-1.6.1/pipelime/sequences/utils.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/pipes/base.py` & `pipelime_python-1.6.1/pipelime/sequences/pipes/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/pipes/mapping.py` & `pipelime_python-1.6.1/pipelime/sequences/pipes/mapping.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/pipes/operations.py` & `pipelime_python-1.6.1/pipelime/sequences/pipes/operations.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/pipes/validation.py` & `pipelime_python-1.6.1/pipelime/sequences/pipes/validation.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/pipes/writers.py` & `pipelime_python-1.6.1/pipelime/sequences/pipes/writers.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/sources/from_callable.py` & `pipelime_python-1.6.1/pipelime/sequences/sources/from_callable.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/sources/raw.py` & `pipelime_python-1.6.1/pipelime/sequences/sources/raw.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/sources/readers.py` & `pipelime_python-1.6.1/pipelime/sequences/sources/readers.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/sequences/sources/toy_dataset.py` & `pipelime_python-1.6.1/pipelime/sequences/sources/toy_dataset.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/stages/__init__.py` & `pipelime_python-1.6.1/pipelime/stages/__init__.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/stages/augmentations.py` & `pipelime_python-1.6.1/pipelime/stages/augmentations.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/stages/base.py` & `pipelime_python-1.6.1/pipelime/stages/base.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/stages/entities.py` & `pipelime_python-1.6.1/pipelime/stages/entities.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/stages/item_info.py` & `pipelime_python-1.6.1/pipelime/stages/item_info.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/stages/item_replacement.py` & `pipelime_python-1.6.1/pipelime/stages/item_replacement.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/stages/item_sources.py` & `pipelime_python-1.6.1/pipelime/stages/item_sources.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/stages/key_transformations.py` & `pipelime_python-1.6.1/pipelime/stages/key_transformations.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/utils/context_managers.py` & `pipelime_python-1.6.1/pipelime/utils/context_managers.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/utils/inspection.py` & `pipelime_python-1.6.1/pipelime/utils/inspection.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pipelime/utils/pydantic_types.py` & `pipelime_python-1.6.1/pipelime/utils/pydantic_types.py`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/.gitignore` & `pipelime_python-1.6.1/.gitignore`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/LICENSE` & `pipelime_python-1.6.1/LICENSE`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/README.md` & `pipelime_python-1.6.1/README.md`

 * *Files identical despite different names*

### Comparing `pipelime_python-1.6.0/pyproject.toml` & `pipelime_python-1.6.1/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -48,15 +48,15 @@
     "pydantic>=1.10.8,<2",
     "schema",
     "pyzmq",
     "dictquery",
     "minio",
     "requests",
     "billiard",
-    "textual",
+    "textual>=0.26.0",
 ]
 dynamic = [ "version" ]
 
 [project.optional-dependencies]
 draw = ["pygraphviz"]
 tests = [
     "pytest",
@@ -90,9 +90,10 @@
 
 [tool.hatch.version]
 path = "pipelime/__init__.py"
 
 [tool.hatch.build]
 include = [
   "pipelime/**/*.py",
+  "pipelime/**/*.css",
   "LICENSE",
 ]
```

### Comparing `pipelime_python-1.6.0/PKG-INFO` & `pipelime_python-1.6.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pipelime-python
-Version: 1.6.0
+Version: 1.6.1
 Summary: Data workflows, cli and dataflow automation.
 Project-URL: Source, https://github.com/eyecan-ai/pipelime-python
 Project-URL: Issues, https://github.com/eyecan-ai/pipelime-python/issues
 Project-URL: Documentation, http://pipelime-python.readthedocs.io/
 Author-email: "Eyecan.ai" <info@eyecan.ai>
 License: GNU General Public License v3 (GPLv3)
 License-File: LICENSE
@@ -36,15 +36,15 @@
 Requires-Dist: pydash
 Requires-Dist: python-box
 Requires-Dist: pyyaml
 Requires-Dist: pyzmq
 Requires-Dist: requests
 Requires-Dist: rich>=9.9.0
 Requires-Dist: schema
-Requires-Dist: textual
+Requires-Dist: textual>=0.26.0
 Requires-Dist: tifffile
 Requires-Dist: toml
 Requires-Dist: tqdm
 Requires-Dist: trimesh
 Requires-Dist: typer>=0.6
 Provides-Extra: build
 Requires-Dist: build; extra == 'build'
```

