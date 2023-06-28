# Comparing `tmp/ocpa-1.2-py3-none-any.whl.zip` & `tmp/ocpa-1.3.1-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,154 +1,171 @@
-Zip file size: 126321 bytes, number of entries: 152
--rw-r--r--  2.0 unx      357 b- defN 22-Dec-12 15:30 ocpa/__init__.py
--rw-r--r--  2.0 unx      139 b- defN 22-Sep-07 09:25 ocpa/algo/__init__.py
--rw-r--r--  2.0 unx      102 b- defN 22-Sep-07 11:38 ocpa/algo/conformance/__init__.py
--rw-r--r--  2.0 unx      131 b- defN 22-Sep-07 09:25 ocpa/algo/conformance/constraint_monitoring/__init__.py
--rw-r--r--  2.0 unx     1946 b- defN 22-Sep-07 09:25 ocpa/algo/conformance/constraint_monitoring/algorithm.py
--rw-r--r--  2.0 unx      152 b- defN 22-Sep-07 09:25 ocpa/algo/conformance/constraint_monitoring/versions/__init__.py
--rw-r--r--  2.0 unx     5484 b- defN 22-Sep-07 09:25 ocpa/algo/conformance/constraint_monitoring/versions/log_based.py
--rw-r--r--  2.0 unx     5967 b- defN 22-Sep-07 09:25 ocpa/algo/conformance/constraint_monitoring/versions/model_based.py
--rw-r--r--  2.0 unx      117 b- defN 22-Sep-07 11:39 ocpa/algo/conformance/precision_and_fitness/__init__.py
--rw-r--r--  2.0 unx     1875 b- defN 22-Sep-07 09:25 ocpa/algo/conformance/precision_and_fitness/evaluator.py
--rw-r--r--  2.0 unx     1783 b- defN 22-Sep-07 09:25 ocpa/algo/conformance/precision_and_fitness/utils.py
--rw-r--r--  2.0 unx       74 b- defN 22-Sep-07 09:25 ocpa/algo/conformance/precision_and_fitness/variants/__init__.py
--rw-r--r--  2.0 unx    12153 b- defN 22-Sep-07 09:25 ocpa/algo/conformance/precision_and_fitness/variants/replay_context.py
--rw-r--r--  2.0 unx       73 b- defN 22-Sep-07 09:25 ocpa/algo/discovery/__init__.py
--rw-r--r--  2.0 unx       56 b- defN 22-Sep-07 09:25 ocpa/algo/discovery/enhanced_ocpn/__init__.py
--rw-r--r--  2.0 unx      885 b- defN 22-Sep-07 09:25 ocpa/algo/discovery/enhanced_ocpn/algorithm.py
+Zip file size: 139899 bytes, number of entries: 169
+-rw-r--r--  2.0 unx      359 b- defN 23-Jun-28 12:07 ocpa/__init__.py
+-rw-r--r--  2.0 unx      139 b- defN 23-May-28 07:45 ocpa/algo/__init__.py
+-rw-r--r--  2.0 unx      102 b- defN 23-May-28 07:45 ocpa/algo/conformance/__init__.py
+-rw-r--r--  2.0 unx      131 b- defN 23-May-28 07:45 ocpa/algo/conformance/constraint_monitoring/__init__.py
+-rw-r--r--  2.0 unx     2009 b- defN 23-May-28 07:45 ocpa/algo/conformance/constraint_monitoring/algorithm.py
+-rw-r--r--  2.0 unx      152 b- defN 23-May-28 07:45 ocpa/algo/conformance/constraint_monitoring/versions/__init__.py
+-rw-r--r--  2.0 unx     6615 b- defN 23-Jun-27 06:14 ocpa/algo/conformance/constraint_monitoring/versions/extensive_log_based.py
+-rw-r--r--  2.0 unx     5484 b- defN 23-May-28 07:45 ocpa/algo/conformance/constraint_monitoring/versions/log_based.py
+-rw-r--r--  2.0 unx     5967 b- defN 23-May-28 07:45 ocpa/algo/conformance/constraint_monitoring/versions/model_based.py
+-rw-r--r--  2.0 unx      117 b- defN 23-May-28 07:45 ocpa/algo/conformance/precision_and_fitness/__init__.py
+-rw-r--r--  2.0 unx     1875 b- defN 23-May-28 07:45 ocpa/algo/conformance/precision_and_fitness/evaluator.py
+-rw-r--r--  2.0 unx     1783 b- defN 23-May-28 07:45 ocpa/algo/conformance/precision_and_fitness/utils.py
+-rw-r--r--  2.0 unx       74 b- defN 23-May-28 07:45 ocpa/algo/conformance/precision_and_fitness/variants/__init__.py
+-rw-r--r--  2.0 unx    12156 b- defN 23-Jun-27 07:42 ocpa/algo/conformance/precision_and_fitness/variants/replay_context.py
+-rw-r--r--  2.0 unx       73 b- defN 23-May-28 07:45 ocpa/algo/discovery/__init__.py
+-rw-r--r--  2.0 unx       56 b- defN 23-May-28 07:45 ocpa/algo/discovery/enhanced_ocpn/__init__.py
+-rw-r--r--  2.0 unx      820 b- defN 23-May-28 07:45 ocpa/algo/discovery/enhanced_ocpn/algorithm.py
 -rw-r--r--  2.0 unx       83 b- defN 22-Sep-07 09:25 ocpa/algo/discovery/ocpn/__init__.py
--rw-r--r--  2.0 unx      681 b- defN 22-Nov-05 08:35 ocpa/algo/discovery/ocpn/algorithm.py
--rw-r--r--  2.0 unx       56 b- defN 22-Sep-07 09:25 ocpa/algo/discovery/ocpn/versions/__init__.py
--rw-r--r--  2.0 unx     8593 b- defN 22-Dec-12 15:26 ocpa/algo/discovery/ocpn/versions/inductive.py
--rw-r--r--  2.0 unx      119 b- defN 22-Sep-07 09:25 ocpa/algo/enhancement/__init__.py
+-rw-r--r--  2.0 unx      700 b- defN 23-Jun-27 06:14 ocpa/algo/discovery/ocpn/algorithm.py
+-rw-r--r--  2.0 unx      116 b- defN 23-Jun-27 06:14 ocpa/algo/discovery/ocpn/versions/__init__.py
+-rw-r--r--  2.0 unx     8579 b- defN 23-Jun-27 06:14 ocpa/algo/discovery/ocpn/versions/inductive.py
+-rw-r--r--  2.0 unx     7040 b- defN 23-Jun-27 06:14 ocpa/algo/discovery/ocpn/versions/new_inductive.py
+-rw-r--r--  2.0 unx      119 b- defN 22-Dec-19 14:59 ocpa/algo/enhancement/__init__.py
 -rw-r--r--  2.0 unx      137 b- defN 22-Sep-07 09:25 ocpa/algo/enhancement/event_graph_based_performance/__init__.py
--rw-r--r--  2.0 unx      322 b- defN 22-Sep-07 09:25 ocpa/algo/enhancement/event_graph_based_performance/algorithm.py
--rw-r--r--  2.0 unx       91 b- defN 22-Sep-07 09:25 ocpa/algo/enhancement/event_graph_based_performance/versions/__init__.py
--rw-r--r--  2.0 unx    14525 b- defN 22-Sep-07 09:25 ocpa/algo/enhancement/event_graph_based_performance/versions/perfectly_fitting.py
--rw-r--r--  2.0 unx       69 b- defN 22-Sep-07 09:25 ocpa/algo/enhancement/token_replay_based_performance/__init__.py
--rw-r--r--  2.0 unx     2262 b- defN 22-Sep-07 09:25 ocpa/algo/enhancement/token_replay_based_performance/algorithm.py
--rw-r--r--  2.0 unx    64144 b- defN 22-Sep-07 09:25 ocpa/algo/enhancement/token_replay_based_performance/util.py
--rw-r--r--  2.0 unx       75 b- defN 22-Sep-07 09:25 ocpa/algo/enhancement/token_replay_based_performance/versions/__init__.py
--rw-r--r--  2.0 unx    32803 b- defN 22-Nov-05 09:25 ocpa/algo/enhancement/token_replay_based_performance/versions/opera.py
--rw-r--r--  2.0 unx      124 b- defN 22-Sep-07 09:25 ocpa/algo/predictive_monitoring/__init__.py
--rw-r--r--  2.0 unx     9648 b- defN 22-Sep-07 11:41 ocpa/algo/predictive_monitoring/factory.py
--rw-r--r--  2.0 unx     8686 b- defN 22-Nov-04 13:28 ocpa/algo/predictive_monitoring/obj.py
--rw-r--r--  2.0 unx     1571 b- defN 22-Sep-07 09:25 ocpa/algo/predictive_monitoring/sequential.py
--rw-r--r--  2.0 unx     1041 b- defN 22-Sep-07 09:25 ocpa/algo/predictive_monitoring/tabular.py
--rw-r--r--  2.0 unx     3526 b- defN 22-Sep-07 09:25 ocpa/algo/predictive_monitoring/time_series.py
--rw-r--r--  2.0 unx       81 b- defN 22-Sep-07 11:36 ocpa/algo/predictive_monitoring/event_based_features/__init__.py
--rw-r--r--  2.0 unx    12568 b- defN 22-Sep-07 09:25 ocpa/algo/predictive_monitoring/event_based_features/extraction_functions.py
--rw-r--r--  2.0 unx       85 b- defN 22-Sep-07 11:36 ocpa/algo/predictive_monitoring/execution_based_features/__init__.py
--rw-r--r--  2.0 unx     2532 b- defN 22-Sep-07 09:25 ocpa/algo/predictive_monitoring/execution_based_features/extraction_functions.py
--rw-r--r--  2.0 unx      136 b- defN 22-Sep-07 11:36 ocpa/algo/util/__init__.py
--rw-r--r--  2.0 unx     1677 b- defN 22-Nov-10 10:22 ocpa/algo/util/util.py
--rw-r--r--  2.0 unx       74 b- defN 22-Sep-07 09:25 ocpa/algo/util/filtering/__init__.py
--rw-r--r--  2.0 unx       50 b- defN 22-Sep-07 09:25 ocpa/algo/util/filtering/graph/__init__.py
--rw-r--r--  2.0 unx       59 b- defN 22-Sep-07 09:25 ocpa/algo/util/filtering/graph/event_graph/__init__.py
--rw-r--r--  2.0 unx      669 b- defN 22-Sep-07 09:25 ocpa/algo/util/filtering/graph/event_graph/algorithm.py
--rw-r--r--  2.0 unx      231 b- defN 22-Sep-07 09:25 ocpa/algo/util/filtering/graph/event_graph/versions/__init__.py
--rw-r--r--  2.0 unx      379 b- defN 22-Sep-07 09:25 ocpa/algo/util/filtering/graph/event_graph/versions/filter_complete.py
--rw-r--r--  2.0 unx      500 b- defN 22-Sep-07 09:25 ocpa/algo/util/filtering/graph/event_graph/versions/filter_object_types.py
--rw-r--r--  2.0 unx     1649 b- defN 22-Sep-07 09:25 ocpa/algo/util/filtering/graph/event_graph/versions/filter_subprocess.py
--rw-r--r--  2.0 unx      210 b- defN 22-Sep-07 09:25 ocpa/algo/util/filtering/log/__init__.py
--rw-r--r--  2.0 unx     1238 b- defN 22-Sep-07 09:25 ocpa/algo/util/filtering/log/activity_filtering.py
--rw-r--r--  2.0 unx      705 b- defN 22-Nov-04 13:28 ocpa/algo/util/filtering/log/case_filtering.py
--rw-r--r--  2.0 unx     5504 b- defN 22-Sep-07 09:25 ocpa/algo/util/filtering/log/time_filtering.py
--rw-r--r--  2.0 unx     1484 b- defN 22-Nov-09 16:38 ocpa/algo/util/filtering/log/variant_filtering.py
--rw-r--r--  2.0 unx       99 b- defN 22-Sep-07 11:36 ocpa/algo/util/process_executions/__init__.py
--rw-r--r--  2.0 unx      414 b- defN 22-Sep-07 09:25 ocpa/algo/util/process_executions/factory.py
--rw-r--r--  2.0 unx      134 b- defN 22-Sep-07 11:36 ocpa/algo/util/process_executions/versions/__init__.py
--rw-r--r--  2.0 unx     1646 b- defN 22-Sep-07 09:25 ocpa/algo/util/process_executions/versions/connected_components.py
--rw-r--r--  2.0 unx     3766 b- defN 22-Sep-07 09:25 ocpa/algo/util/process_executions/versions/leading_type.py
--rw-r--r--  2.0 unx      163 b- defN 22-Sep-07 11:40 ocpa/algo/util/retrieval/__init__.py
--rw-r--r--  2.0 unx       64 b- defN 22-Sep-07 09:25 ocpa/algo/util/retrieval/constraint_graph/__init__.py
--rw-r--r--  2.0 unx     2288 b- defN 22-Sep-07 09:25 ocpa/algo/util/retrieval/constraint_graph/algorithm.py
--rw-r--r--  2.0 unx       70 b- defN 22-Sep-07 09:25 ocpa/algo/util/retrieval/correlated_event_graph/__init__.py
--rw-r--r--  2.0 unx      734 b- defN 22-Sep-07 09:25 ocpa/algo/util/retrieval/correlated_event_graph/algorithm.py
--rw-r--r--  2.0 unx       58 b- defN 22-Sep-07 11:40 ocpa/algo/util/retrieval/event_graph/__init__.py
--rw-r--r--  2.0 unx      307 b- defN 22-Sep-07 09:25 ocpa/algo/util/retrieval/event_graph/algorithm.py
--rw-r--r--  2.0 unx       66 b- defN 22-Sep-07 09:25 ocpa/algo/util/retrieval/event_graph/versions/__init__.py
--rw-r--r--  2.0 unx     2137 b- defN 22-Sep-07 09:25 ocpa/algo/util/retrieval/event_graph/versions/classic.py
--rw-r--r--  2.0 unx       40 b- defN 22-Sep-07 11:36 ocpa/algo/util/variants/__init__.py
--rw-r--r--  2.0 unx      348 b- defN 22-Sep-07 09:25 ocpa/algo/util/variants/factory.py
--rw-r--r--  2.0 unx      108 b- defN 22-Sep-07 11:36 ocpa/algo/util/variants/versions/__init__.py
--rw-r--r--  2.0 unx     4721 b- defN 22-Sep-07 09:25 ocpa/algo/util/variants/versions/onephase.py
--rw-r--r--  2.0 unx     4953 b- defN 22-Sep-07 09:25 ocpa/algo/util/variants/versions/twophase.py
--rw-r--r--  2.0 unx        0 b- defN 22-Sep-07 09:25 ocpa/algo/util/variants/versions/utils/__init__.py
--rw-r--r--  2.0 unx     1191 b- defN 22-Sep-07 09:25 ocpa/algo/util/variants/versions/utils/helper.py
--rw-r--r--  2.0 unx       83 b- defN 22-Sep-07 09:25 ocpa/objects/__init__.py
--rw-r--r--  2.0 unx      130 b- defN 22-Sep-07 09:25 ocpa/objects/graph/__init__.py
--rw-r--r--  2.0 unx        0 b- defN 22-Sep-07 09:25 ocpa/objects/graph/constraint_graph/__init__.py
--rw-r--r--  2.0 unx     5194 b- defN 22-Sep-07 09:25 ocpa/objects/graph/constraint_graph/obj.py
+-rw-r--r--  2.0 unx      447 b- defN 23-May-28 07:45 ocpa/algo/enhancement/event_graph_based_performance/algorithm.py
+-rw-r--r--  2.0 unx      117 b- defN 23-May-28 07:45 ocpa/algo/enhancement/event_graph_based_performance/versions/__init__.py
+-rw-r--r--  2.0 unx     9672 b- defN 23-Jun-27 06:14 ocpa/algo/enhancement/event_graph_based_performance/versions/event_object_graph_based.py
+-rw-r--r--  2.0 unx    14525 b- defN 23-May-28 07:45 ocpa/algo/enhancement/event_graph_based_performance/versions/perfectly_fitting.py
+-rw-r--r--  2.0 unx       69 b- defN 22-Dec-19 14:59 ocpa/algo/enhancement/token_replay_based_performance/__init__.py
+-rw-r--r--  2.0 unx     2262 b- defN 23-May-28 07:45 ocpa/algo/enhancement/token_replay_based_performance/algorithm.py
+-rw-r--r--  2.0 unx    61795 b- defN 23-Jun-28 09:11 ocpa/algo/enhancement/token_replay_based_performance/util.py
+-rw-r--r--  2.0 unx       75 b- defN 23-May-28 07:45 ocpa/algo/enhancement/token_replay_based_performance/versions/__init__.py
+-rw-r--r--  2.0 unx    28966 b- defN 23-Jun-28 09:28 ocpa/algo/enhancement/token_replay_based_performance/versions/opera.py
+-rw-r--r--  2.0 unx      124 b- defN 23-May-28 07:45 ocpa/algo/predictive_monitoring/__init__.py
+-rw-r--r--  2.0 unx     9804 b- defN 23-Jun-27 06:13 ocpa/algo/predictive_monitoring/factory.py
+-rw-r--r--  2.0 unx     9333 b- defN 23-Jun-27 06:53 ocpa/algo/predictive_monitoring/obj.py
+-rw-r--r--  2.0 unx     1541 b- defN 23-Jun-27 06:13 ocpa/algo/predictive_monitoring/sequential.py
+-rw-r--r--  2.0 unx      984 b- defN 23-Jun-27 06:13 ocpa/algo/predictive_monitoring/tabular.py
+-rw-r--r--  2.0 unx     3526 b- defN 23-May-28 07:45 ocpa/algo/predictive_monitoring/time_series.py
+-rw-r--r--  2.0 unx       81 b- defN 23-May-28 07:45 ocpa/algo/predictive_monitoring/event_based_features/__init__.py
+-rw-r--r--  2.0 unx    12130 b- defN 23-Jun-27 06:13 ocpa/algo/predictive_monitoring/event_based_features/extraction_functions.py
+-rw-r--r--  2.0 unx       85 b- defN 23-May-28 07:45 ocpa/algo/predictive_monitoring/execution_based_features/__init__.py
+-rw-r--r--  2.0 unx     2532 b- defN 23-May-28 07:45 ocpa/algo/predictive_monitoring/execution_based_features/extraction_functions.py
+-rw-r--r--  2.0 unx      163 b- defN 23-Jun-27 06:14 ocpa/algo/util/__init__.py
+-rw-r--r--  2.0 unx     1677 b- defN 23-May-28 07:45 ocpa/algo/util/util.py
+-rw-r--r--  2.0 unx       43 b- defN 23-Jun-27 06:14 ocpa/algo/util/aopm/__init__.py
+-rw-r--r--  2.0 unx        0 b- defN 23-Jun-27 06:14 ocpa/algo/util/aopm/action_engine/__init__.py
+-rw-r--r--  2.0 unx      525 b- defN 23-Jun-27 06:14 ocpa/algo/util/aopm/action_engine/algorithm.py
+-rw-r--r--  2.0 unx        0 b- defN 23-Jun-27 06:14 ocpa/algo/util/aopm/impact_analysis/__init__.py
+-rw-r--r--  2.0 unx      519 b- defN 23-Jun-27 06:14 ocpa/algo/util/aopm/impact_analysis/algorithm.py
+-rw-r--r--  2.0 unx       74 b- defN 23-May-28 07:45 ocpa/algo/util/filtering/__init__.py
+-rw-r--r--  2.0 unx       50 b- defN 23-May-28 07:45 ocpa/algo/util/filtering/graph/__init__.py
+-rw-r--r--  2.0 unx       59 b- defN 23-May-28 07:45 ocpa/algo/util/filtering/graph/event_graph/__init__.py
+-rw-r--r--  2.0 unx      669 b- defN 23-May-28 07:45 ocpa/algo/util/filtering/graph/event_graph/algorithm.py
+-rw-r--r--  2.0 unx      231 b- defN 23-May-28 07:45 ocpa/algo/util/filtering/graph/event_graph/versions/__init__.py
+-rw-r--r--  2.0 unx      379 b- defN 23-May-28 07:45 ocpa/algo/util/filtering/graph/event_graph/versions/filter_complete.py
+-rw-r--r--  2.0 unx      500 b- defN 23-May-28 07:45 ocpa/algo/util/filtering/graph/event_graph/versions/filter_object_types.py
+-rw-r--r--  2.0 unx     1649 b- defN 23-May-28 07:45 ocpa/algo/util/filtering/graph/event_graph/versions/filter_subprocess.py
+-rw-r--r--  2.0 unx      210 b- defN 23-May-28 07:45 ocpa/algo/util/filtering/log/__init__.py
+-rw-r--r--  2.0 unx     1249 b- defN 23-Jun-27 06:14 ocpa/algo/util/filtering/log/activity_filtering.py
+-rw-r--r--  2.0 unx      705 b- defN 23-Jun-16 15:22 ocpa/algo/util/filtering/log/case_filtering.py
+-rw-r--r--  2.0 unx     5922 b- defN 23-Jun-27 06:14 ocpa/algo/util/filtering/log/time_filtering.py
+-rw-r--r--  2.0 unx     1483 b- defN 23-May-28 07:45 ocpa/algo/util/filtering/log/variant_filtering.py
+-rw-r--r--  2.0 unx       99 b- defN 23-May-28 07:45 ocpa/algo/util/process_executions/__init__.py
+-rw-r--r--  2.0 unx      414 b- defN 23-May-28 07:45 ocpa/algo/util/process_executions/factory.py
+-rw-r--r--  2.0 unx      134 b- defN 23-May-28 07:45 ocpa/algo/util/process_executions/versions/__init__.py
+-rw-r--r--  2.0 unx     1646 b- defN 23-May-28 07:45 ocpa/algo/util/process_executions/versions/connected_components.py
+-rw-r--r--  2.0 unx     3766 b- defN 23-May-28 07:45 ocpa/algo/util/process_executions/versions/leading_type.py
+-rw-r--r--  2.0 unx      163 b- defN 23-May-28 07:45 ocpa/algo/util/retrieval/__init__.py
+-rw-r--r--  2.0 unx       64 b- defN 23-May-28 07:45 ocpa/algo/util/retrieval/constraint_graph/__init__.py
+-rw-r--r--  2.0 unx     2288 b- defN 23-May-28 07:45 ocpa/algo/util/retrieval/constraint_graph/algorithm.py
+-rw-r--r--  2.0 unx       70 b- defN 23-May-28 07:45 ocpa/algo/util/retrieval/correlated_event_graph/__init__.py
+-rw-r--r--  2.0 unx      734 b- defN 23-May-28 07:45 ocpa/algo/util/retrieval/correlated_event_graph/algorithm.py
+-rw-r--r--  2.0 unx       58 b- defN 23-May-28 07:45 ocpa/algo/util/retrieval/event_graph/__init__.py
+-rw-r--r--  2.0 unx      307 b- defN 23-May-28 07:45 ocpa/algo/util/retrieval/event_graph/algorithm.py
+-rw-r--r--  2.0 unx       66 b- defN 23-May-28 07:45 ocpa/algo/util/retrieval/event_graph/versions/__init__.py
+-rw-r--r--  2.0 unx     2137 b- defN 23-May-28 07:45 ocpa/algo/util/retrieval/event_graph/versions/classic.py
+-rw-r--r--  2.0 unx       40 b- defN 23-May-28 07:45 ocpa/algo/util/variants/__init__.py
+-rw-r--r--  2.0 unx      348 b- defN 23-May-28 07:45 ocpa/algo/util/variants/factory.py
+-rw-r--r--  2.0 unx      108 b- defN 23-May-28 07:45 ocpa/algo/util/variants/versions/__init__.py
+-rw-r--r--  2.0 unx     4721 b- defN 23-May-28 07:45 ocpa/algo/util/variants/versions/onephase.py
+-rw-r--r--  2.0 unx     4954 b- defN 23-Jun-27 06:14 ocpa/algo/util/variants/versions/twophase.py
+-rw-r--r--  2.0 unx        0 b- defN 23-May-28 07:45 ocpa/algo/util/variants/versions/utils/__init__.py
+-rw-r--r--  2.0 unx     1191 b- defN 23-May-28 07:45 ocpa/algo/util/variants/versions/utils/helper.py
+-rw-r--r--  2.0 unx      108 b- defN 23-Jun-27 06:14 ocpa/objects/__init__.py
+-rw-r--r--  2.0 unx       80 b- defN 23-Jun-27 06:14 ocpa/objects/aopm/__init__.py
+-rw-r--r--  2.0 unx        0 b- defN 23-Jun-27 06:14 ocpa/objects/aopm/action_interface_model/__init__.py
+-rw-r--r--  2.0 unx     2372 b- defN 23-Jun-27 06:14 ocpa/objects/aopm/action_interface_model/obj.py
+-rw-r--r--  2.0 unx        0 b- defN 23-Jun-27 06:14 ocpa/objects/aopm/impact/__init__.py
+-rw-r--r--  2.0 unx     1373 b- defN 23-Jun-27 06:14 ocpa/objects/aopm/impact/obj.py
+-rw-r--r--  2.0 unx      183 b- defN 23-May-28 07:45 ocpa/objects/graph/__init__.py
+-rw-r--r--  2.0 unx        0 b- defN 23-May-28 07:45 ocpa/objects/graph/constraint_graph/__init__.py
+-rw-r--r--  2.0 unx     5194 b- defN 23-May-28 07:45 ocpa/objects/graph/constraint_graph/obj.py
 -rw-r--r--  2.0 unx       59 b- defN 22-Sep-07 09:25 ocpa/objects/graph/correlated_event_graph/__init__.py
 -rw-r--r--  2.0 unx     2256 b- defN 22-Sep-07 09:25 ocpa/objects/graph/correlated_event_graph/obj.py
--rw-r--r--  2.0 unx        0 b- defN 22-Sep-07 09:25 ocpa/objects/graph/correlated_event_graph/retrieval/__init__.py
+-rw-r--r--  2.0 unx        0 b- defN 22-Dec-19 14:59 ocpa/objects/graph/correlated_event_graph/retrieval/__init__.py
 -rw-r--r--  2.0 unx      734 b- defN 22-Sep-07 09:25 ocpa/objects/graph/correlated_event_graph/retrieval/algorithm.py
 -rw-r--r--  2.0 unx       48 b- defN 22-Sep-07 09:25 ocpa/objects/graph/event_graph/__init__.py
 -rw-r--r--  2.0 unx      746 b- defN 22-Sep-07 09:25 ocpa/objects/graph/event_graph/obj.py
--rw-r--r--  2.0 unx        0 b- defN 22-Sep-07 09:25 ocpa/objects/graph/event_graph/retrieval/__init__.py
+-rw-r--r--  2.0 unx        0 b- defN 22-Dec-19 14:59 ocpa/objects/graph/event_graph/retrieval/__init__.py
 -rw-r--r--  2.0 unx     2154 b- defN 22-Sep-07 09:25 ocpa/objects/graph/event_graph/retrieval/algorithm.py
--rw-r--r--  2.0 unx      154 b- defN 22-Sep-07 11:41 ocpa/objects/log/__init__.py
--rw-r--r--  2.0 unx     9429 b- defN 22-Nov-09 16:47 ocpa/objects/log/ocel.py
+-rw-r--r--  2.0 unx        0 b- defN 23-May-28 07:45 ocpa/objects/graph/extensive_constraint_graph/__init__.py
+-rw-r--r--  2.0 unx     4424 b- defN 23-May-28 07:45 ocpa/objects/graph/extensive_constraint_graph/obj.py
+-rw-r--r--  2.0 unx      154 b- defN 23-May-28 07:45 ocpa/objects/log/__init__.py
+-rw-r--r--  2.0 unx     9429 b- defN 23-May-28 07:45 ocpa/objects/log/ocel.py
 -rw-r--r--  2.0 unx       85 b- defN 22-Sep-07 09:25 ocpa/objects/log/converter/__init__.py
--rw-r--r--  2.0 unx      391 b- defN 22-Nov-04 15:32 ocpa/objects/log/converter/factory.py
--rw-r--r--  2.0 unx      123 b- defN 22-Nov-04 15:17 ocpa/objects/log/converter/versions/__init__.py
--rw-r--r--  2.0 unx     2615 b- defN 22-Nov-05 09:26 ocpa/objects/log/converter/versions/df_to_ocel.py
--rw-r--r--  2.0 unx     1711 b- defN 22-Sep-07 09:25 ocpa/objects/log/converter/versions/jsonocel_to_csv.py
--rw-r--r--  2.0 unx       38 b- defN 22-Sep-07 09:25 ocpa/objects/log/exporter/__init__.py
--rw-r--r--  2.0 unx       47 b- defN 22-Sep-07 09:25 ocpa/objects/log/exporter/ocel/__init__.py
--rw-r--r--  2.0 unx      812 b- defN 22-Sep-07 09:25 ocpa/objects/log/exporter/ocel/factory.py
--rw-r--r--  2.0 unx       64 b- defN 22-Sep-07 09:25 ocpa/objects/log/exporter/ocel/versions/__init__.py
--rw-r--r--  2.0 unx     2127 b- defN 22-Nov-17 07:28 ocpa/objects/log/exporter/ocel/versions/export_ocel_json.py
--rw-r--r--  2.0 unx       75 b- defN 22-Sep-07 09:25 ocpa/objects/log/importer/__init__.py
--rw-r--r--  2.0 unx       91 b- defN 22-Sep-07 11:42 ocpa/objects/log/importer/csv/__init__.py
--rw-r--r--  2.0 unx     2620 b- defN 22-Nov-04 13:29 ocpa/objects/log/importer/csv/factory.py
--rw-r--r--  2.0 unx     5221 b- defN 22-Nov-04 13:06 ocpa/objects/log/importer/csv/util.py
--rw-r--r--  2.0 unx      159 b- defN 22-Sep-07 11:42 ocpa/objects/log/importer/csv/versions/__init__.py
--rw-r--r--  2.0 unx     1473 b- defN 22-Nov-16 10:10 ocpa/objects/log/importer/csv/versions/to_df.py
--rw-r--r--  2.0 unx     3293 b- defN 22-Nov-04 16:26 ocpa/objects/log/importer/csv/versions/to_obj.py
--rw-r--r--  2.0 unx      862 b- defN 22-Nov-04 15:31 ocpa/objects/log/importer/csv/versions/to_ocel.py
+-rw-r--r--  2.0 unx      391 b- defN 23-May-28 07:45 ocpa/objects/log/converter/factory.py
+-rw-r--r--  2.0 unx      123 b- defN 23-May-28 07:45 ocpa/objects/log/converter/versions/__init__.py
+-rw-r--r--  2.0 unx     3234 b- defN 23-Jun-27 06:14 ocpa/objects/log/converter/versions/df_to_ocel.py
+-rw-r--r--  2.0 unx     1711 b- defN 23-May-28 07:45 ocpa/objects/log/converter/versions/jsonocel_to_csv.py
+-rw-r--r--  2.0 unx       38 b- defN 22-Dec-19 14:59 ocpa/objects/log/exporter/__init__.py
+-rw-r--r--  2.0 unx       47 b- defN 22-Dec-19 14:59 ocpa/objects/log/exporter/ocel/__init__.py
+-rw-r--r--  2.0 unx      812 b- defN 23-May-28 07:45 ocpa/objects/log/exporter/ocel/factory.py
+-rw-r--r--  2.0 unx       64 b- defN 22-Dec-19 14:59 ocpa/objects/log/exporter/ocel/versions/__init__.py
+-rw-r--r--  2.0 unx     2127 b- defN 23-May-28 07:45 ocpa/objects/log/exporter/ocel/versions/export_ocel_json.py
+-rw-r--r--  2.0 unx       75 b- defN 23-May-28 07:45 ocpa/objects/log/importer/__init__.py
+-rw-r--r--  2.0 unx       91 b- defN 23-May-28 07:45 ocpa/objects/log/importer/csv/__init__.py
+-rw-r--r--  2.0 unx     2620 b- defN 23-May-28 07:45 ocpa/objects/log/importer/csv/factory.py
+-rw-r--r--  2.0 unx     5283 b- defN 23-Jun-27 06:14 ocpa/objects/log/importer/csv/util.py
+-rw-r--r--  2.0 unx      159 b- defN 23-May-28 07:45 ocpa/objects/log/importer/csv/versions/__init__.py
+-rw-r--r--  2.0 unx     1485 b- defN 23-Jun-27 06:14 ocpa/objects/log/importer/csv/versions/to_df.py
+-rw-r--r--  2.0 unx     3243 b- defN 23-Jun-27 06:14 ocpa/objects/log/importer/csv/versions/to_obj.py
+-rw-r--r--  2.0 unx     1007 b- defN 23-May-28 07:45 ocpa/objects/log/importer/csv/versions/to_ocel.py
 -rw-r--r--  2.0 unx       93 b- defN 22-Sep-07 09:25 ocpa/objects/log/importer/ocel/__init__.py
--rw-r--r--  2.0 unx     2317 b- defN 22-Sep-07 09:25 ocpa/objects/log/importer/ocel/factory.py
+-rw-r--r--  2.0 unx     2317 b- defN 23-May-28 07:45 ocpa/objects/log/importer/ocel/factory.py
 -rw-r--r--  2.0 unx     1431 b- defN 22-Sep-07 09:25 ocpa/objects/log/importer/ocel/parameters.py
 -rw-r--r--  2.0 unx      137 b- defN 22-Sep-07 09:25 ocpa/objects/log/importer/ocel/versions/__init__.py
--rw-r--r--  2.0 unx     4997 b- defN 22-Nov-04 13:30 ocpa/objects/log/importer/ocel/versions/import_ocel_json.py
--rw-r--r--  2.0 unx     3700 b- defN 22-Sep-07 09:25 ocpa/objects/log/importer/ocel/versions/import_ocel_xml.py
--rw-r--r--  2.0 unx       69 b- defN 22-Sep-07 11:42 ocpa/objects/log/util/__init__.py
--rw-r--r--  2.0 unx     1312 b- defN 22-Nov-09 16:44 ocpa/objects/log/util/misc.py
+-rw-r--r--  2.0 unx     5270 b- defN 23-May-28 07:45 ocpa/objects/log/importer/ocel/versions/import_ocel_json.py
+-rw-r--r--  2.0 unx     3700 b- defN 23-May-28 07:45 ocpa/objects/log/importer/ocel/versions/import_ocel_xml.py
+-rw-r--r--  2.0 unx       69 b- defN 23-May-28 07:45 ocpa/objects/log/util/__init__.py
+-rw-r--r--  2.0 unx     1312 b- defN 23-Jun-16 15:22 ocpa/objects/log/util/misc.py
 -rw-r--r--  2.0 unx     1662 b- defN 22-Sep-07 09:25 ocpa/objects/log/util/param.py
--rw-r--r--  2.0 unx      130 b- defN 22-Sep-07 09:25 ocpa/objects/log/variants/__init__.py
--rw-r--r--  2.0 unx      107 b- defN 22-Sep-07 09:25 ocpa/objects/log/variants/graph.py
--rw-r--r--  2.0 unx     6725 b- defN 22-Nov-05 09:22 ocpa/objects/log/variants/obj.py
--rw-r--r--  2.0 unx     2928 b- defN 22-Nov-04 13:30 ocpa/objects/log/variants/table.py
--rw-r--r--  2.0 unx        0 b- defN 22-Sep-07 09:25 ocpa/objects/log/variants/util/__init__.py
--rw-r--r--  2.0 unx      825 b- defN 22-Sep-07 09:25 ocpa/objects/log/variants/util/table.py
+-rw-r--r--  2.0 unx      130 b- defN 23-May-28 07:45 ocpa/objects/log/variants/__init__.py
+-rw-r--r--  2.0 unx      107 b- defN 23-May-28 07:45 ocpa/objects/log/variants/graph.py
+-rw-r--r--  2.0 unx    12391 b- defN 23-Jun-27 06:14 ocpa/objects/log/variants/obj.py
+-rw-r--r--  2.0 unx     2859 b- defN 23-Jun-27 06:14 ocpa/objects/log/variants/table.py
+-rw-r--r--  2.0 unx        0 b- defN 23-May-28 07:45 ocpa/objects/log/variants/util/__init__.py
+-rw-r--r--  2.0 unx      825 b- defN 23-May-28 07:45 ocpa/objects/log/variants/util/table.py
 -rw-r--r--  2.0 unx      124 b- defN 22-Sep-07 09:25 ocpa/objects/oc_petri_net/__init__.py
--rw-r--r--  2.0 unx    16287 b- defN 22-Nov-04 10:52 ocpa/objects/oc_petri_net/obj.py
+-rw-r--r--  2.0 unx    23248 b- defN 23-Jun-28 06:52 ocpa/objects/oc_petri_net/obj.py
 -rw-r--r--  2.0 unx        0 b- defN 22-Sep-07 09:25 ocpa/objects/oc_petri_net/properties.py
 -rw-r--r--  2.0 unx        0 b- defN 22-Sep-07 09:25 ocpa/objects/oc_petri_net/semantics.py
 -rw-r--r--  2.0 unx       53 b- defN 22-Sep-07 09:25 ocpa/util/__init__.py
 -rw-r--r--  2.0 unx      195 b- defN 22-Sep-07 09:25 ocpa/util/constants.py
+-rw-r--r--  2.0 unx     2706 b- defN 23-Jun-27 07:01 ocpa/util/util.py
 -rw-r--r--  2.0 unx     1051 b- defN 22-Sep-07 09:25 ocpa/util/vis_util.py
--rw-r--r--  2.0 unx       69 b- defN 22-Sep-07 11:42 ocpa/visualization/__init__.py
--rw-r--r--  2.0 unx      105 b- defN 22-Sep-07 09:25 ocpa/visualization/constraint_graph/__init__.py
--rw-r--r--  2.0 unx      248 b- defN 22-Sep-07 09:25 ocpa/visualization/constraint_graph/algorithm.py
--rw-r--r--  2.0 unx       70 b- defN 22-Sep-07 09:25 ocpa/visualization/constraint_graph/versions/__init__.py
--rw-r--r--  2.0 unx     2902 b- defN 22-Sep-07 09:25 ocpa/visualization/constraint_graph/versions/to_cytoscape.py
--rw-r--r--  2.0 unx       39 b- defN 22-Sep-07 11:36 ocpa/visualization/log/__init__.py
--rw-r--r--  2.0 unx       95 b- defN 22-Sep-07 11:36 ocpa/visualization/log/variants/__init__.py
--rw-r--r--  2.0 unx      694 b- defN 22-Sep-07 09:25 ocpa/visualization/log/variants/factory.py
--rw-r--r--  2.0 unx       66 b- defN 22-Sep-07 11:36 ocpa/visualization/log/variants/versions/__init__.py
--rw-r--r--  2.0 unx     6026 b- defN 22-Sep-07 09:25 ocpa/visualization/log/variants/versions/chevron_sequences.py
--rw-r--r--  2.0 unx      139 b- defN 22-Sep-07 09:25 ocpa/visualization/oc_petri_net/__init__.py
--rw-r--r--  2.0 unx      867 b- defN 22-Sep-07 09:25 ocpa/visualization/oc_petri_net/factory.py
+-rw-r--r--  2.0 unx       69 b- defN 23-May-28 07:45 ocpa/visualization/__init__.py
+-rw-r--r--  2.0 unx      105 b- defN 23-May-28 07:45 ocpa/visualization/constraint_graph/__init__.py
+-rw-r--r--  2.0 unx      248 b- defN 23-May-28 07:45 ocpa/visualization/constraint_graph/algorithm.py
+-rw-r--r--  2.0 unx       70 b- defN 23-May-28 07:45 ocpa/visualization/constraint_graph/versions/__init__.py
+-rw-r--r--  2.0 unx     2902 b- defN 23-May-28 07:45 ocpa/visualization/constraint_graph/versions/to_cytoscape.py
+-rw-r--r--  2.0 unx       39 b- defN 23-May-28 07:45 ocpa/visualization/log/__init__.py
+-rw-r--r--  2.0 unx       95 b- defN 23-May-28 07:45 ocpa/visualization/log/variants/__init__.py
+-rw-r--r--  2.0 unx      694 b- defN 23-May-28 07:45 ocpa/visualization/log/variants/factory.py
+-rw-r--r--  2.0 unx       66 b- defN 23-May-28 07:45 ocpa/visualization/log/variants/versions/__init__.py
+-rw-r--r--  2.0 unx     6026 b- defN 23-May-28 07:45 ocpa/visualization/log/variants/versions/chevron_sequences.py
+-rw-r--r--  2.0 unx      139 b- defN 23-Jun-28 10:01 ocpa/visualization/oc_petri_net/__init__.py
+-rw-r--r--  2.0 unx      973 b- defN 23-Jun-27 06:14 ocpa/visualization/oc_petri_net/factory.py
 -rw-r--r--  2.0 unx       49 b- defN 22-Sep-07 09:25 ocpa/visualization/oc_petri_net/util/__init__.py
 -rw-r--r--  2.0 unx      149 b- defN 22-Sep-07 09:25 ocpa/visualization/oc_petri_net/util/util.py
--rw-r--r--  2.0 unx       88 b- defN 22-Sep-07 09:25 ocpa/visualization/oc_petri_net/versions/__init__.py
--rw-r--r--  2.0 unx     8628 b- defN 22-Sep-07 09:25 ocpa/visualization/oc_petri_net/versions/annotated_with_opera.py
--rw-r--r--  2.0 unx     4295 b- defN 22-Sep-07 09:25 ocpa/visualization/oc_petri_net/versions/control_flow.py
--rw-r--r--  2.0 unx    34600 b- defN 22-Dec-12 15:31 ocpa-1.2.dist-info/LICENSE.txt
--rw-r--r--  2.0 unx      378 b- defN 22-Dec-12 15:31 ocpa-1.2.dist-info/METADATA
--rw-r--r--  2.0 unx       92 b- defN 22-Dec-12 15:31 ocpa-1.2.dist-info/WHEEL
--rw-r--r--  2.0 unx        5 b- defN 22-Dec-12 15:31 ocpa-1.2.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx    15585 b- defN 22-Dec-12 15:31 ocpa-1.2.dist-info/RECORD
-152 files, 395114 bytes uncompressed, 100511 bytes compressed:  74.6%
+-rw-r--r--  2.0 unx      195 b- defN 23-Jun-28 10:01 ocpa/visualization/oc_petri_net/versions/__init__.py
+-rw-r--r--  2.0 unx     4452 b- defN 23-Jun-27 13:00 ocpa/visualization/oc_petri_net/versions/annotated_with_opera.py
+-rw-r--r--  2.0 unx     4791 b- defN 23-Jun-27 06:14 ocpa/visualization/oc_petri_net/versions/control_flow.py
+-rw-r--r--  2.0 unx     3887 b- defN 23-Jun-27 06:14 ocpa/visualization/oc_petri_net/versions/new_control_flow.py
+-rw-r--r--  2.0 unx    34600 b- defN 23-Jun-28 12:07 ocpa-1.3.1.dist-info/LICENSE.txt
+-rw-r--r--  2.0 unx      341 b- defN 23-Jun-28 12:07 ocpa-1.3.1.dist-info/METADATA
+-rw-r--r--  2.0 unx       92 b- defN 23-Jun-28 12:07 ocpa-1.3.1.dist-info/WHEEL
+-rw-r--r--  2.0 unx        5 b- defN 23-Jun-28 12:07 ocpa-1.3.1.dist-info/top_level.txt
+?rw-rw-r--  2.0 unx    17359 b- defN 23-Jun-28 12:07 ocpa-1.3.1.dist-info/RECORD
+169 files, 441104 bytes uncompressed, 111155 bytes compressed:  74.8%
```

## zipnote {}

```diff
@@ -12,14 +12,17 @@
 
 Filename: ocpa/algo/conformance/constraint_monitoring/algorithm.py
 Comment: 
 
 Filename: ocpa/algo/conformance/constraint_monitoring/versions/__init__.py
 Comment: 
 
+Filename: ocpa/algo/conformance/constraint_monitoring/versions/extensive_log_based.py
+Comment: 
+
 Filename: ocpa/algo/conformance/constraint_monitoring/versions/log_based.py
 Comment: 
 
 Filename: ocpa/algo/conformance/constraint_monitoring/versions/model_based.py
 Comment: 
 
 Filename: ocpa/algo/conformance/precision_and_fitness/__init__.py
@@ -54,26 +57,32 @@
 
 Filename: ocpa/algo/discovery/ocpn/versions/__init__.py
 Comment: 
 
 Filename: ocpa/algo/discovery/ocpn/versions/inductive.py
 Comment: 
 
+Filename: ocpa/algo/discovery/ocpn/versions/new_inductive.py
+Comment: 
+
 Filename: ocpa/algo/enhancement/__init__.py
 Comment: 
 
 Filename: ocpa/algo/enhancement/event_graph_based_performance/__init__.py
 Comment: 
 
 Filename: ocpa/algo/enhancement/event_graph_based_performance/algorithm.py
 Comment: 
 
 Filename: ocpa/algo/enhancement/event_graph_based_performance/versions/__init__.py
 Comment: 
 
+Filename: ocpa/algo/enhancement/event_graph_based_performance/versions/event_object_graph_based.py
+Comment: 
+
 Filename: ocpa/algo/enhancement/event_graph_based_performance/versions/perfectly_fitting.py
 Comment: 
 
 Filename: ocpa/algo/enhancement/token_replay_based_performance/__init__.py
 Comment: 
 
 Filename: ocpa/algo/enhancement/token_replay_based_performance/algorithm.py
@@ -120,14 +129,29 @@
 
 Filename: ocpa/algo/util/__init__.py
 Comment: 
 
 Filename: ocpa/algo/util/util.py
 Comment: 
 
+Filename: ocpa/algo/util/aopm/__init__.py
+Comment: 
+
+Filename: ocpa/algo/util/aopm/action_engine/__init__.py
+Comment: 
+
+Filename: ocpa/algo/util/aopm/action_engine/algorithm.py
+Comment: 
+
+Filename: ocpa/algo/util/aopm/impact_analysis/__init__.py
+Comment: 
+
+Filename: ocpa/algo/util/aopm/impact_analysis/algorithm.py
+Comment: 
+
 Filename: ocpa/algo/util/filtering/__init__.py
 Comment: 
 
 Filename: ocpa/algo/util/filtering/graph/__init__.py
 Comment: 
 
 Filename: ocpa/algo/util/filtering/graph/event_graph/__init__.py
@@ -225,14 +249,29 @@
 
 Filename: ocpa/algo/util/variants/versions/utils/helper.py
 Comment: 
 
 Filename: ocpa/objects/__init__.py
 Comment: 
 
+Filename: ocpa/objects/aopm/__init__.py
+Comment: 
+
+Filename: ocpa/objects/aopm/action_interface_model/__init__.py
+Comment: 
+
+Filename: ocpa/objects/aopm/action_interface_model/obj.py
+Comment: 
+
+Filename: ocpa/objects/aopm/impact/__init__.py
+Comment: 
+
+Filename: ocpa/objects/aopm/impact/obj.py
+Comment: 
+
 Filename: ocpa/objects/graph/__init__.py
 Comment: 
 
 Filename: ocpa/objects/graph/constraint_graph/__init__.py
 Comment: 
 
 Filename: ocpa/objects/graph/constraint_graph/obj.py
@@ -258,14 +297,20 @@
 
 Filename: ocpa/objects/graph/event_graph/retrieval/__init__.py
 Comment: 
 
 Filename: ocpa/objects/graph/event_graph/retrieval/algorithm.py
 Comment: 
 
+Filename: ocpa/objects/graph/extensive_constraint_graph/__init__.py
+Comment: 
+
+Filename: ocpa/objects/graph/extensive_constraint_graph/obj.py
+Comment: 
+
 Filename: ocpa/objects/log/__init__.py
 Comment: 
 
 Filename: ocpa/objects/log/ocel.py
 Comment: 
 
 Filename: ocpa/objects/log/converter/__init__.py
@@ -381,14 +426,17 @@
 
 Filename: ocpa/util/__init__.py
 Comment: 
 
 Filename: ocpa/util/constants.py
 Comment: 
 
+Filename: ocpa/util/util.py
+Comment: 
+
 Filename: ocpa/util/vis_util.py
 Comment: 
 
 Filename: ocpa/visualization/__init__.py
 Comment: 
 
 Filename: ocpa/visualization/constraint_graph/__init__.py
@@ -435,23 +483,26 @@
 
 Filename: ocpa/visualization/oc_petri_net/versions/annotated_with_opera.py
 Comment: 
 
 Filename: ocpa/visualization/oc_petri_net/versions/control_flow.py
 Comment: 
 
-Filename: ocpa-1.2.dist-info/LICENSE.txt
+Filename: ocpa/visualization/oc_petri_net/versions/new_control_flow.py
+Comment: 
+
+Filename: ocpa-1.3.1.dist-info/LICENSE.txt
 Comment: 
 
-Filename: ocpa-1.2.dist-info/METADATA
+Filename: ocpa-1.3.1.dist-info/METADATA
 Comment: 
 
-Filename: ocpa-1.2.dist-info/WHEEL
+Filename: ocpa-1.3.1.dist-info/WHEEL
 Comment: 
 
-Filename: ocpa-1.2.dist-info/top_level.txt
+Filename: ocpa-1.3.1.dist-info/top_level.txt
 Comment: 
 
-Filename: ocpa-1.2.dist-info/RECORD
+Filename: ocpa-1.3.1.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## ocpa/__init__.py

```diff
@@ -1,11 +1,11 @@
 import ocpa.algo
 import ocpa.objects
 import ocpa.util
 import ocpa.visualization
 
-__version__ = '1.2'
+__version__ = '1.3.1'
 __doc__ = "Object-Centric Process Analysis"
 __author__ = 'Jan Niklas Adams and Gyunam Park'
 __author_email__ = 'niklas.adams@pads.rwth-aachen.de'
 __maintainer__ = 'Jan Niklas Adams and Gyunam Park'
 __maintainer_email__ = "niklas.adams@pads.rwth-aachen.de"
```

## ocpa/algo/conformance/constraint_monitoring/algorithm.py

```diff
@@ -1,21 +1,24 @@
 # from ocpa.objects.oc_petri_net.obj import EnhancedObjectCentricPetriNet
 from ocpa.algo.conformance.constraint_monitoring.versions import log_based
-from ocpa.objects.graph.constraint_graph.obj import ConstraintGraph
+from ocpa.algo.conformance.constraint_monitoring.versions import extensive_log_based
 from ocpa.objects.log.ocel import OCEL
 from typing import Dict
 
 
 # MODEL_BASED = "model_based"
 LOG_BASED = "log_based"
+EXTENSIVE = "extensive_log_based"
+VERSIONS = {
+    LOG_BASED: log_based.apply,
+    EXTENSIVE: extensive_log_based.apply
+}
 
-VERSIONS = {LOG_BASED: log_based.apply}
 
-
-def apply(cg: ConstraintGraph, ocel: OCEL, diag: Dict, variant=LOG_BASED, parameters=None):
+def apply(cg, ocel: OCEL, variant=EXTENSIVE, parameters=None):
     '''
     Monitoring the violation of constraints by analyzing object-centric event logs. The constraints are represented as object-centric constraint graphs. For each violation of the constraint, it provides the analysis of the violation.
 
     :param cg: Object-centric constraint graph
     :type ocpn: :class:`OCPN <ocpa.objects.graph.constraint_graph.ConstraintGraph>`
 
     :param ocel: Object-centric event log
@@ -24,8 +27,8 @@
     :param diag: performance measures per activity, e.g., {'Act1': {'Measure1': value, 'Measure2: value, ...}, 'Act2': {...}, ...}. Value has different formats depending on the performance measure, e.g., the one for 'act_freq' is Integer, the one for 'object_count', 'pooling_time', 'lagging_time', and 'synchronization_time' is a nested dictionary (e.g., {'ObjectType1': {'mean': Real, 'median': Real, ...}, 'ObjectType2': {...}, ...}), the one for 'waiting_time', 'service_time', 'sojourn_time', and 'flow_time' is a dictionary (e.g., {'mean': Real, 'median': Real, ...}).
     :type ocel: Dict
 
     :return: Violated, A List of diagnostics for the violation. Violated is a Boolean value where True denotes that the constraint is violated and False denotes that the constraint is not violated. Diagnostics explains why the constraint is violated by analyzing each edge of the constraint graph.
     :rtype: Boolean, List
 
     '''
-    return VERSIONS[variant](cg, ocel, diag, parameters=parameters)
+    return VERSIONS[variant](cg, ocel, parameters=parameters)
```

## ocpa/algo/conformance/precision_and_fitness/variants/replay_context.py

```diff
@@ -48,15 +48,15 @@
 def binding_possible(ocpn, state, binding, object_types):
     if len(binding) == 0:
         return False
     tokens = [o for ot in object_types for o in binding[0][1][ot]]
     input_places_tokens = []
     t = None
     for t_ in ocpn.transitions:
-        if t_.name == binding[0][0]:
+        if t_.label == binding[0][0]:
             t = t_
     if t == None:
         return False
     for a in t.in_arcs:
         input_places_tokens += state[a.source] if a.source in state.keys() else [
         ]
     if set(tokens).issubset(set(input_places_tokens)) or set(tokens) == set(input_places_tokens):
@@ -67,15 +67,15 @@
 
 def calculate_next_states_on_bindings(ocpn, state, binding, object_types):
     state_update_pairs = []
     possible = True
     if binding_possible(ocpn, state, binding, object_types):
         t = None
         for t_ in ocpn.transitions:
-            if t_.name == binding[0][0]:
+            if t_.label == binding[0][0]:
                 t = t_
         in_places = {}
         out_places = {}
         for ot in object_types:
             in_places[ot] = [(x, y) for (x, y) in [(a.source, a.variable)
                                                    for a in t.in_arcs] if x.object_type == ot]
             out_places[ot] = [x for x in [
@@ -223,15 +223,15 @@
 
         elem = q[index]
         index += 1
         ti = time.time()
         if len(elem[1]) == 0:
             for t in ocpn.transitions:
                 if model_enabled(ocpn, elem[0], t) and not t.silent:
-                    result[1].add(t.name)
+                    result[1].add(t.label)
         times[0] += time.time() - ti
         ti = time.time()
         state_update_pairs, binding_possible = calculate_next_states_on_bindings(
             ocpn, elem[0], elem[1], object_types)
         times[1] += time.time() - ti
         # for all next states
         # if the binding is possible, go to the end of the queue and append the next state there
```

## ocpa/algo/discovery/enhanced_ocpn/algorithm.py

```diff
@@ -1,15 +1,14 @@
 from ocpa.objects.oc_petri_net.obj import EnhancedObjectCentricPetriNet
 from ocpa.algo.enhancement.token_replay_based_performance import algorithm as performance_factory
 import ocpa.algo.util.retrieval.event_graph.algorithm as event_graph_factory
 import ocpa.algo.util.retrieval.correlated_event_graph.algorithm as correlated_event_graph_factory
 
 
 def apply(ocpn, ocel, parameters=None) -> EnhancedObjectCentricPetriNet:
-    # df, _ = convert_factory.apply(ocel, variant='json_to_mdl')
     diag = performance_factory.apply(ocpn, ocel, parameters=parameters)
     eog = event_graph_factory.apply(ocel, parameters=None)
     cegs = correlated_event_graph_factory.apply(eog)
     behavior = []
     for ceg in cegs:
         bv = ceg.get_sequence()
         if bv not in behavior:
```

## ocpa/algo/discovery/ocpn/algorithm.py

```diff
@@ -1,18 +1,18 @@
-from ocpa.algo.discovery.ocpn.versions import inductive
+from ocpa.algo.discovery.ocpn.versions import inductive, new_inductive
 from ocpa.objects.log.ocel import OCEL
 from ocpa.objects.log.variants.obj import ObjectCentricEventLog
 import ocpa.objects.log.converter.factory as convert_factory
 
 INDUCTIVE = "inductive"
 
-VERSIONS = {INDUCTIVE: inductive.apply}
+VERSIONS = {INDUCTIVE: new_inductive.apply}
 
 
 def apply(ocel, variant=INDUCTIVE, parameters=None):
     if type(ocel) == OCEL:
         return VERSIONS[variant](ocel.log.log, parameters=parameters)
     if type(ocel) == ObjectCentricEventLog:
-        df, _ = convert_factory.apply(ocel, variant='json_to_mdl')
+        df, _ = convert_factory.apply(ocel, variant='json_to_csv')
         return VERSIONS[variant](df, parameters=parameters)
     else:
         return VERSIONS[variant](ocel, parameters=parameters)
```

## ocpa/algo/discovery/ocpn/versions/__init__.py

```diff
@@ -1 +1,2 @@
 from ocpa.algo.discovery.ocpn.versions import inductive
+from ocpa.algo.discovery.ocpn.versions import new_inductive
```

## ocpa/algo/discovery/ocpn/versions/inductive.py

```diff
@@ -1,21 +1,21 @@
 from pm4py.algo.discovery.alpha import algorithm as alpha_miner
 from pm4py.algo.discovery.inductive import algorithm as inductive_miner
 from pm4py.algo.discovery.dfg import algorithm as dfg_discovery
 from pm4py.statistics.start_activities.log import get as sa_get
 from pm4py.statistics.end_activities.log import get as ea_get
 from pm4py.objects.conversion.dfg import converter as dfg_converter
-# from pm4py.algo.filtering.log.attributes import attributes_filter
-from pm4py.objects.petri.utils import add_arc_from_to
-from pm4py.objects.petri.utils import remove_place, remove_transition
+from pm4py.objects.petri_net.utils.petri_utils import add_arc_from_to
+from pm4py.objects.petri_net.utils.petri_utils import remove_place, remove_transition
 from ocpa.algo.util.util import project_log, project_log_with_object_count
 from ocpa.objects.oc_petri_net.obj import ObjectCentricPetriNet
 from ocpa.objects.log.importer.csv.util import succint_mdl_to_exploded_mdl, clean_frequency, clean_arc_frequency
 import pandas as pd
 import time
+import networkx as nx
 
 MAX_FREQUENCY = float("inf")
 
 
 def reduce_petri_net(net):
     transes = set([x for x in net.transitions if x.label is None])
     places = list(net.places)
```

## ocpa/algo/enhancement/event_graph_based_performance/algorithm.py

```diff
@@ -1,9 +1,13 @@
-from ocpa.algo.enhancement.event_graph_based_performance.versions import perfectly_fitting
+from ocpa.algo.enhancement.event_graph_based_performance.versions import perfectly_fitting, event_object_graph_based
 
 PERFECTLY_FITTING = "perfectly_fitting"
+EVENT_OBJECT_GRAPH = "event_object_graph_based"
 
-VERSIONS = {PERFECTLY_FITTING: perfectly_fitting.apply}
+VERSIONS = {
+    PERFECTLY_FITTING: perfectly_fitting.apply,
+    EVENT_OBJECT_GRAPH: event_object_graph_based.apply
+}
 
 
-def apply(ocpn, cegs, variant=PERFECTLY_FITTING, parameters=None):
-    return VERSIONS[variant](ocpn, cegs, parameters=parameters)
+def apply(ocel, variant=EVENT_OBJECT_GRAPH, parameters=None):
+    return VERSIONS[variant](ocel, parameters=parameters)
```

## ocpa/algo/enhancement/event_graph_based_performance/versions/__init__.py

```diff
@@ -1 +1 @@
-from ocpa.algo.enhancement.event_graph_based_performance.versions import perfectly_fitting
+from ocpa.algo.enhancement.event_graph_based_performance.versions import perfectly_fitting, event_object_graph_based
```

## ocpa/algo/enhancement/token_replay_based_performance/util.py

```diff
@@ -10,33 +10,38 @@
     but WITHOUT ANY WARRANTY; without even the implied warranty of
     MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
     GNU General Public License for more details.
 
     You should have received a copy of the GNU General Public License
     along with PM4Py.  If not, see <https://www.gnu.org/licenses/>.
 '''
+import pkgutil
 from pm4py.statistics.variants.log import get as variants_module
 from pm4py.util import xes_constants as xes_util
 from ocpa.util import constants as ocpa_constants
 from pm4py.objects.petri_net import semantics
+import pm4py.evaluation.replay_fitness.variants.token_replay as tb_replay
 from pm4py.objects.petri_net.obj import Marking
 from pm4py.objects.petri_net.utils.petri_utils import get_places_shortest_path_by_hidden, get_s_components_from_petri
 from pm4py.objects.log import obj as log_implementation
 from pm4py.objects.petri_net.utils import align_utils
 from copy import copy
 from enum import Enum
 from pm4py.util import exec_utils, constants
 from pm4py.util import variants_util
 import pkgutil
 from typing import Optional, Dict, Any, Union, Tuple
 from pm4py.objects.log.obj import EventLog, EventStream
 import pandas as pd
 from pm4py.objects.petri_net.obj import PetriNet, Marking
 from pm4py.util import typing
-from pm4py.visualization.petrinet.util import performance_map
+if pkgutil.find_loader("graphviz"):
+    from pm4py.visualization.petri_net.util import performance_map
+else:
+    print("GraphViz not installed. Might lead to visualization problems.")
 
 
 class Parameters(Enum):
     CASE_ID_KEY = constants.PARAMETER_CONSTANT_CASEID_KEY
     ACTIVITY_KEY = constants.PARAMETER_CONSTANT_ACTIVITY_KEY
     PARAMETER_VARIANT_DELIMITER = "variant_delimiter"
     VARIANTS = "variants"
@@ -73,14 +78,34 @@
     REACH_ITF2 = -1
 
 
 class NoConceptNameException(Exception):
     def __init__(self, message):
         self.message = message
 
+def execute_and_record(t, pn, m, token_visits, trace_id, prev_timestamp, timestamp):
+    if not semantics.is_enabled(t, pn, m):
+        return None
+
+    m_out = copy(m)
+    for a in t.in_arcs:
+        m_out[a.source] -= a.weight
+        if m_out[a.source] == 0:
+            del m_out[a.source]
+        # record token consumption
+        for _ in range(a.weight):
+            token_visits.append([(a.source, trace_id), prev_timestamp,timestamp])
+
+            
+    
+    for a in t.out_arcs:
+        m_out[a.target] += a.weight
+
+    return m_out, token_visits
+
 
 def add_missing_tokens(t, marking):
     """
     Adds missing tokens needed to activate a transition
 
     Parameters
     ----------
@@ -228,15 +253,15 @@
     hidden_transitions_to_enable = sorted(
         hidden_transitions_to_enable, key=lambda x: len(x))
 
     return hidden_transitions_to_enable
 
 
 def enable_hidden_transitions(net, marking, activated_transitions, visited_transitions, all_visited_markings,
-                              hidden_transitions_to_enable, t):
+                              hidden_transitions_to_enable, t, trace_id, timestamp):
     """
     Actually enable hidden transitions on the Petri net
 
     Parameters
     -----------
     net
         Petri net
@@ -277,15 +302,15 @@
         if not something_changed:
             break
     return [marking, activated_transitions, visited_transitions, all_visited_markings]
 
 
 def apply_hidden_trans(t, net, marking, places_shortest_paths_by_hidden, act_tr, rec_depth,
                        visit_trans,
-                       vis_mark):
+                       vis_mark, trace_id, timestamp):
     """
     Apply hidden transitions in order to enable a given transition
 
     Parameters
     ----------
     t
         Transition to eventually enable
@@ -317,15 +342,15 @@
     if hidden_transitions_to_enable:
         [marking, act_tr, visit_trans, vis_mark] = enable_hidden_transitions(net,
                                                                              marking,
                                                                              act_tr,
                                                                              visit_trans,
                                                                              vis_mark,
                                                                              hidden_transitions_to_enable,
-                                                                             t)
+                                                                             t, trace_id, timestamp)
         if not semantics.is_enabled(t, net, marking):
             hidden_transitions_to_enable = get_hidden_transitions_to_enable(marking, places_with_missing,
                                                                             places_shortest_paths_by_hidden)
             for z in range(len(hidden_transitions_to_enable)):
                 for k in range(len(hidden_transitions_to_enable[z])):
                     t4 = hidden_transitions_to_enable[z][k]
                     if not t4 == t:
@@ -334,28 +359,28 @@
                                 [net, marking, act_tr, vis_mark] = apply_hidden_trans(t4,
                                                                                       net,
                                                                                       marking,
                                                                                       places_shortest_paths_by_hidden,
                                                                                       act_tr,
                                                                                       rec_depth + 1,
                                                                                       visit_trans,
-                                                                                      vis_mark)
+                                                                                      vis_mark, trace_id, timestamp)
                             if semantics.is_enabled(t4, net, marking):
-                                marking = semantics.execute(t4, net, marking)
+                                marking = semantics.execute_and_record(t4, net, marking, trace_id, timestamp)
                                 act_tr.append(t4)
                                 visit_trans.add(t4)
                                 vis_mark.append(marking)
         if not semantics.is_enabled(t, net, marking):
             if not (marking_at_start == marking):
                 [net, marking, act_tr, vis_mark] = apply_hidden_trans(t, net, marking,
                                                                       places_shortest_paths_by_hidden,
                                                                       act_tr,
                                                                       rec_depth + 1,
                                                                       visit_trans,
-                                                                      vis_mark)
+                                                                      vis_mark, trace_id, timestamp)
 
     return [net, marking, act_tr, vis_mark]
 
 
 def break_condition_final_marking(marking, final_marking):
     """
     Verify break condition for final marking
@@ -436,23 +461,21 @@
     s_components
         S-components of the Petri net (if workflow net)
     """
     trace_activities = [event[activity_key] for event in trace]
     act_trans = []
     transitions_with_problems = []
     vis_mark = []
-    my_mark = {'history': [], 'start': [], 'end': []}
-    my_event_mark = []
+    token_visits = []
+    event_occurrences = []
     activating_transition_index = {}
     activating_transition_interval = []
     used_postfix_cache = False
     marking = copy(initial_marking)
     vis_mark.append(marking)
-    # my_mark['start'].append(
-    #     ["source", trace._attributes[xes_util.DEFAULT_TRACEID_KEY], 0])
     missing = 0
     consumed = 0
     sum_tokens_im = 0
     for place in initial_marking:
         sum_tokens_im = sum_tokens_im + initial_marking[place]
     sum_tokens_fm = 0
     for place in final_marking:
@@ -488,14 +511,20 @@
                 this_vis_markings = marking_to_activity_caching.cache[hash(marking)][trace[i][activity_key]][
                     "this_visited_markings"]
                 act_trans = act_trans + this_act_trans
                 vis_mark = vis_mark + this_vis_markings
                 marking = copy(this_end_marking)
             else:
                 if trace[i][activity_key] in trans_map:
+                    trace_id = trace._attributes[xes_util.DEFAULT_TRACEID_KEY]
+                    timestamp = trace[i][ocpa_constants.DEFAULT_TIMESTAMP_KEY]
+                    if i > 0:
+                        prev_timestamp = trace[i-1][ocpa_constants.DEFAULT_TIMESTAMP_KEY]
+                    else:
+                        prev_timestamp = trace[i][ocpa_constants.DEFAULT_TIMESTAMP_KEY]
                     current_event_map.update(trace[i])
                     # change 14/10/2020: to better support duplicate transitions with this approach, we check
                     # whether in the current marking there is at least one transition corresponding to the activity
                     # key without looking at the transition map (that contains one entry per label)
                     corr_en_t = [x for x in semantics.enabled_transitions(
                         net, marking) if x.label == trace[i][activity_key]]
                     if corr_en_t:
@@ -511,38 +540,20 @@
                                                                                                  marking),
                                                                                              places_shortest_path_by_hidden,
                                                                                              copy(
                                                                                                  act_trans),
                                                                                              0,
                                                                                              copy(
                                                                                                  visited_transitions),
-                                                                                             copy(vis_mark))
+                                                                                             copy(vis_mark), trace_id, timestamp)
                         for jj5 in range(len(act_trans), len(new_act_trans)):
                             tt5 = new_act_trans[jj5]
                             c, cmap = get_consumed_tokens(tt5)
-                            # TODO Double check the logic to handle silent transitions. It takes the timestamps from trace[i-1]
-                            for pl, count in cmap.items():
-                                for k in range(count):
-                                    if i > 0:
-                                        my_mark['end'].append(
-                                            [pl, trace._attributes[xes_util.DEFAULT_TRACEID_KEY], trace[i-1][ocpa_constants.DEFAULT_START_TIMESTAMP_KEY]])
-                                    else:
-                                        my_mark['end'].append(
-                                            [pl, trace._attributes[xes_util.DEFAULT_TRACEID_KEY], trace[i][ocpa_constants.DEFAULT_START_TIMESTAMP_KEY]])
-
                             p, pmap = get_produced_tokens(tt5)
-                            for pl, count in pmap.items():
-                                for k in range(count):
-                                    if i > 0:
-                                        my_mark['start'].append(
-                                            [pl, trace._attributes[xes_util.DEFAULT_TRACEID_KEY], trace[i-1][ocpa_constants.DEFAULT_TIMESTAMP_KEY]])
-                                    else:
-                                        my_mark['start'].append(
-                                            [pl, trace._attributes[xes_util.DEFAULT_TRACEID_KEY], trace[i][ocpa_constants.DEFAULT_TIMESTAMP_KEY]])
-
+                            
                             if enable_pltr_fitness:
                                 for pl2 in cmap:
                                     if pl2 in place_fitness:
                                         place_fitness[pl2]["c"] += cmap[pl2] * \
                                             trace_occurrences
                                 for pl2 in pmap:
                                     if pl2 in place_fitness:
@@ -573,38 +584,30 @@
                             transition_fitness[t]["underfed_traces"][trace].append(
                                 current_event_map)
                     elif enable_pltr_fitness:
                         if trace not in transition_fitness[t]["fit_traces"]:
                             transition_fitness[t]["fit_traces"][trace] = list()
                         transition_fitness[t]["fit_traces"][trace].append(
                             current_event_map)
-                    my_event_mark.append([t, trace[i]])
+                    event_occurrences.append([t, trace[i]])
                     c, cmap = get_consumed_tokens(t)
-                    for pl, count in cmap.items():
-                        for k in range(count):
-                            my_mark['end'].append(
-                                [pl, trace._attributes[xes_util.DEFAULT_TRACEID_KEY], trace[i][ocpa_constants.DEFAULT_START_TIMESTAMP_KEY]])
                     p, pmap = get_produced_tokens(t)
-                    for pl, count in pmap.items():
-                        for k in range(count):
-                            my_mark['start'].append(
-                                [pl, trace._attributes[xes_util.DEFAULT_TRACEID_KEY], trace[i][ocpa_constants.DEFAULT_TIMESTAMP_KEY]])
                     consumed = consumed + c
                     produced = produced + p
                     if enable_pltr_fitness:
                         for pl2 in cmap:
                             if pl2 in place_fitness:
                                 place_fitness[pl2]["c"] += cmap[pl2] * \
                                     trace_occurrences
                         for pl2 in pmap:
                             if pl2 in place_fitness:
                                 place_fitness[pl2]["p"] += pmap[pl2] * \
                                     trace_occurrences
                     if semantics.is_enabled(t, net, marking):
-                        marking = semantics.execute(t, net, marking)
+                        marking, token_visits = execute_and_record(t, net, marking, token_visits, trace_id, prev_timestamp, timestamp)
                         act_trans.append(t)
                         vis_mark.append(marking)
                     if not is_initially_enabled and cleaning_token_flood:
                         # here, a routine for cleaning token flood shall go
                         new_marking_names = [
                             x.name for x in list(marking.keys())]
                         new_marking_names_diff = [
@@ -652,24 +655,15 @@
                 for group in hidden_transitions_to_enable:
                     for t in group:
                         if semantics.is_enabled(t, net, marking):
                             marking = semantics.execute(t, net, marking)
                             act_trans.append(t)
                             vis_mark.append(marking)
                             c, cmap = get_consumed_tokens(t)
-                            for pl, count in cmap.items():
-                                for k in range(count):
-                                    my_mark['end'].append(
-                                        [pl, trace._attributes[xes_util.DEFAULT_TRACEID_KEY], trace[i][ocpa_constants.DEFAULT_START_TIMESTAMP_KEY]])
-
                             p, pmap = get_produced_tokens(t)
-                            for pl, count in pmap.items():
-                                for k in range(count):
-                                    my_mark['start'].append(
-                                        [pl, trace._attributes[xes_util.DEFAULT_TRACEID_KEY], trace[i][ocpa_constants.DEFAULT_TIMESTAMP_KEY]])
                             if enable_pltr_fitness:
                                 for pl2 in cmap:
                                     if pl2 in place_fitness:
                                         place_fitness[pl2]["c"] += cmap[pl2] * \
                                             trace_occurrences
                                 for pl2 in pmap:
                                     if pl2 in place_fitness:
@@ -696,27 +690,18 @@
                     connections_to_sink, key=lambda x: len(x[1]))
 
                 for i in range(TechnicalParameters.MAX_IT_FINAL2.value):
                     for j in range(len(connections_to_sink)):
                         for z in range(len(connections_to_sink[j][1])):
                             t = connections_to_sink[j][1][z]
                             if semantics.is_enabled(t, net, marking):
-                                marking = semantics.execute(t, net, marking)
+                                marking, token_visits = execute_and_record(t, net, marking, token_visits, trace_id, prev_timestamp, timestamp)
                                 act_trans.append(t)
                                 c, cmap = get_consumed_tokens(t)
-                                for pl, count in cmap.items():
-                                    for k in range(count):
-                                        my_mark['end'].append(
-                                            [pl, trace._attributes[xes_util.DEFAULT_TRACEID_KEY], trace[i][ocpa_constants.DEFAULT_START_TIMESTAMP_KEY]])
-
                                 p, pmap = get_produced_tokens(t)
-                                for pl, count in pmap.items():
-                                    for k in range(count):
-                                        my_mark['start'].append(
-                                            [pl, trace._attributes[xes_util.DEFAULT_TRACEID_KEY], trace[i][ocpa_constants.DEFAULT_TIMESTAMP_KEY]])
                                 if enable_pltr_fitness:
                                     for pl2 in cmap:
                                         if pl2 in place_fitness:
                                             place_fitness[pl2]["c"] += cmap[pl2] * \
                                                 trace_occurrences
                                     for pl2 in pmap:
                                         if pl2 in place_fitness:
@@ -824,32 +809,19 @@
                         }
                     if activity not in marking_to_activity_caching.cache[start_marking_hash]:
                         marking_to_activity_caching.cache[start_marking_hash][activity] = {
                             "start_marking": start_marking_object, "end_marking": end_marking_object,
                             "this_activated_transitions": this_activated_trans,
                             "this_visited_markings": this_visited_markings,
                             "previousActivity": previous_activity}
-    tvs = []
-    for start_token in my_mark['start']:
-        start_token_name = (start_token[0], start_token[1])
-        start = start_token[2]
-        for end_token in my_mark['end']:
-            end_token_name = (end_token[0], end_token[1])
-            if start_token_name == end_token_name:
-                end = end_token[2]
-                if start == 0:
-                    start = end
-                tvs.append([start_token_name, start, end])
-                my_mark['end'].remove(end_token)
-
     return [is_fit, trace_fitness, act_trans, transitions_with_problems, marking_before_cleaning,
             align_utils.get_visible_transitions_eventually_enabled_by_marking(
                 net, marking_before_cleaning), missing,
             consumed,
-            remaining, produced, tvs, my_event_mark]
+            remaining, produced, token_visits, event_occurrences]
 
 
 class ApplyTraceTokenReplay:
     def __init__(self, trace, net, initial_marking, final_marking, trans_map, enable_pltr_fitness, place_fitness,
                  transition_fitness, notexisting_activities_in_model,
                  places_shortest_path_by_hidden, consider_remaining_in_fitness, activity_key="concept:name",
                  reach_mark_through_hidden=True, stop_immediately_when_unfit=False,
@@ -1067,19 +1039,19 @@
 
     enable_pltr_fitness = exec_utils.get_param_value(
         Parameters.ENABLE_PLTR_FITNESS, parameters, False)
     # changed default to uniform behavior with token-based replay fitness
     consider_remaining_in_fitness = exec_utils.get_param_value(Parameters.CONSIDER_REMAINING_IN_FITNESS, parameters,
                                                                True)
     try_to_reach_final_marking_through_hidden = exec_utils.get_param_value(
-        Parameters.TRY_TO_REACH_FINAL_MARKING_THROUGH_HIDDEN, parameters, True)
+        Parameters.TRY_TO_REACH_FINAL_MARKING_THROUGH_HIDDEN, parameters, False)
     stop_immediately_unfit = exec_utils.get_param_value(
         Parameters.STOP_IMMEDIATELY_UNFIT, parameters, False)
     walk_through_hidden_trans = exec_utils.get_param_value(
-        Parameters.WALK_THROUGH_HIDDEN_TRANS, parameters, True)
+        Parameters.WALK_THROUGH_HIDDEN_TRANS, parameters, False)
     is_reduction = exec_utils.get_param_value(
         Parameters.IS_REDUCTION, parameters, False)
     cleaning_token_flood = exec_utils.get_param_value(
         Parameters.CLEANING_TOKEN_FLOOD, parameters, False)
     disable_variants = exec_utils.get_param_value(
         Parameters.DISABLE_VARIANTS, parameters, False)
     return_names = exec_utils.get_param_value(
@@ -1118,15 +1090,15 @@
     log = log_implementation.EventLog()
     for var_item in variants_list:
         trace = variants_util.variant_to_trace(
             var_item[0], parameters=parameters)
 
         log.append(trace)
 
-    return apply(log, net, initial_marking, final_marking, parameters=parameters)
+    return tb_replay.apply(log, net, initial_marking, final_marking, parameters=parameters)
 
 
 def apply_variants_dictionary(variants, net, initial_marking, final_marking, parameters=None):
     if parameters is None:
         parameters = {}
 
     var_list = {x: len(y) for x, y in variants.items()}
@@ -1281,14 +1253,15 @@
                     from tqdm.auto import tqdm
                     progress = tqdm(
                         total=len(log), desc="replaying log with TBR, completed variants :: ")
                 threads = {}
                 threads_results = {}
 
                 for idx, trace in enumerate(log):
+
                     threads[idx] = ApplyTraceTokenReplay(trace, net, initial_marking, final_marking,
                                                          trans_map, enable_pltr_fitness, place_fitness_per_trace,
                                                          transition_fitness_per_trace,
                                                          notexisting_activities_in_model,
                                                          places_shortest_path_by_hidden,
                                                          consider_remaining_in_fitness,
                                                          activity_key=activity_key,
@@ -1302,21 +1275,23 @@
                                                          cleaning_token_flood=cleaning_token_flood,
                                                          s_components=s_components,
                                                          consider_activities_not_in_model_in_fitness=consider_activities_not_in_model_in_fitness)
                     threads[idx].run()
                     if progress is not None:
                         progress.update()
                     t = threads[idx]
-                    threads_results[idx] = {"trace_is_fit": copy(t.t_fit),
-                                            "activated_transitions": copy(t.act_trans),
-                                            "reached_marking": copy(t.reached_marking),
-                                            "enabled_transitions_in_marking": copy(
-                        t.enabled_trans_in_mark),
+                    threads_results[idx] = {
+                        "trace_id": trace._attributes[xes_util.DEFAULT_TRACEID_KEY],
+                        "trace_is_fit": copy(t.t_fit),
+                        "activated_transitions": copy(t.act_trans),
+                        "reached_marking": (copy(t.reached_marking)),
+                        "enabled_transitions_in_marking": copy(
+                            t.enabled_trans_in_mark),
                         "transitions_with_problems": copy(
-                        t.trans_probl),
+                            t.trans_probl),
                         "token_visits": copy(t.tvs),
                         "event_occurrences": copy(t.ocs)}
 
                     del threads[idx]
                     replay_results.append(threads_results[idx])
 
                 # gracefully close progress bar
```

## ocpa/algo/enhancement/token_replay_based_performance/versions/opera.py

```diff
@@ -1,19 +1,16 @@
 from operator import attrgetter
-import ocpa.objects.log.converter.factory as convert_factory
-from typing import List, Dict, Set, Any, Optional, Union, Tuple
+from typing import Set, Any, Tuple
 from dataclasses import dataclass
-from ocpa.util.vis_util import human_readable_stat
 from statistics import median, mean
 from ocpa.util import constants as ocpa_constants
 import pandas as pd
 from statistics import stdev
-from ocpa.objects.oc_petri_net.obj import ObjectCentricPetriNet
-from pm4py.objects.petri.petrinet import PetriNet
-from ocpa.algo.enhancement.token_replay_based_performance.util import run_timed_replay, apply_trace, single_element_statistics
+from pm4py.objects.petri_net.obj import PetriNet
+from ocpa.algo.enhancement.token_replay_based_performance.util import run_timed_replay, single_element_statistics
 from ocpa.objects.log.importer.csv.util import succint_mdl_to_exploded_mdl, clean_frequency, clean_arc_frequency
 from ocpa.algo.util.util import project_log
 
 
 def apply(ocpn, ocel, parameters=None):
     if parameters is None:
         parameters = {}
@@ -89,49 +86,40 @@
     for persp in persps:
         net, im, fm = ocpn.nets[persp]
         object_map[persp] = set(df[persp])
         # remove nan
         object_map[persp] = {x for x in object_map[persp] if x == x}
         log = project_log(df, persp, parameters=parameters)
 
-        # # Diagonstics - Activity Counting
-        # activ_count = projection_factory.apply(
-        #     df, persp, variant="activity_occurrence", parameters=parameters)
-        # replay_diag["act_freq"][persp] = activ_count
-
         replay_results = run_timed_replay(log, net, im, fm)
 
         token_visits = [y for x in replay_results for y in x['token_visits']]
 
         for tv in token_visits:
             tvs.append(TokenVisit(tv[0], tv[1], tv[2]))
-        # for eo in event_occurrences:
-        #     eos.append(EventOccurrence(eo[0], eo[1]))
-        # variants_idx = variants_module.get_variants_from_log_trace_idx(log)
+
         element_statistics = single_element_statistics(
             log, net, im, replay_results)
 
         agg_statistics = aggregate_frequencies(element_statistics)
         replay_diag["arc_freq_persps"][persp] = agg_statistics
 
-    # replay_diag["act_freq"] = merge_act_freq(replay_diag["act_freq"])
     replay_diag["arc_freq"] = merge_replay(ocpn,
                                            replay_diag["arc_freq_persps"])
     replay_diag['agg_object_freq'] = {}
     for persp in persps:
         replay_diag['agg_object_freq'][persp] = aggregate_perf_records(
             replay_diag['object_count'], aggregation_measure='all', ot=persp)
     # replay_diag['agg_object_freq'] = replay_diag['object_count']
     replay_diag["place_fitness_per_trace"] = merge_place_fitness(
         replay_diag["place_fitness_per_trace"])
     replay_diag["object_count"] = replay_diag['agg_object_freq']
 
     tvs = list(set(tvs))
-    # eos = list(set(eos))
-    pa = PerformanceAnalysis(object_map)
+    pa = PerformanceAnalysis(object_map, ocpn.place_mapping)
     perf_diag = pa.analyze(eos, tvs, persps, parameters)
 
     # merge replay diagnostics and performance diagnostics
     diag = {**perf_diag, **replay_diag}
     transformed_diag = transform_diagnostics(ocpn, diag, parameters)
 
     return transformed_diag
@@ -152,38 +140,37 @@
     transition: Any
     event: Any
 
     # def __hash__(self):
     #     return hash(tuple([self.transition.label, self.event]))
 
     def __eq__(self, eo):
-        return self.transition.name == eo.transition.name and self.event == eo.event
+        return self.transition.label == eo.transition.label and self.event == eo.event
 
 
 class PerformanceAnalysis:
-    def __init__(self, object_map):
+    def __init__(self, object_map, place_mapping):
         self.perf_records = {}
         self.object_map = object_map
+        self.place_mapping = place_mapping
 
     def correspond(self, eo: EventOccurrence, V: Set[TokenVisit]):
         input_places = [
             in_arc.source for in_arc in eo.transition.in_arcs]
         temp_R = []
         for v in V:
             if v.token[1] in eo.event.omap:
-                if v.token[0].name in [p.name for p in input_places]:
+                if self.place_mapping[v.token[0]].name in [p.name for p in input_places]:
                     temp_R.append(v)
         objs = set([v.token[1] for v in temp_R])
         R = []
         for obj in objs:
             oi_tokens = [v for v in temp_R if v.token[1] == obj]
             selected_token = max(oi_tokens, key=attrgetter('start'))
             R.append(selected_token)
-
-        # return [v for v in V if v.end == eo.event[ocpa_constants.DEFAULT_OCEL_START_TIMESTAMP_KEY] and v.token[0].name in [p.name for p in input_places]]
         return R
 
     def analyze(self, eos: Set[EventOccurrence], tvs: Set[TokenVisit], ots: Set[str], parameters):
         # compute measures
         if 'waiting_time' in parameters['measures']:
             p_waiting = True
         else:
@@ -235,94 +222,87 @@
         eos_len = len(eos)
         i = 0
         for eo in eos:
             i += 1
             if i % 1000 == 0:
                 print(f'{i}/{eos_len}')
             R = self.correspond(eo, tvs)
+            
+            # Define values as None for further checking
+            waiting, service, sojourn, sync = None, None, None, None
+
             if p_waiting:
                 waiting = self.measure_waiting(eo, R)
-                if eo.transition.name in self.perf_records['waiting']:
-                    self.perf_records['waiting'][eo.transition.name].append(
-                        waiting)
-                else:
-                    self.perf_records['waiting'][eo.transition.name] = [
-                        waiting]
+                if waiting is not None and eo.transition.label in self.perf_records['waiting']:
+                    self.perf_records['waiting'][eo.transition.label].append(waiting)
+                elif waiting is not None:
+                    self.perf_records['waiting'][eo.transition.label] = [waiting]
+
             if p_service:
                 service = self.measure_service(eo, R)
-                if eo.transition.name in self.perf_records['service']:
-                    self.perf_records['service'][eo.transition.name].append(
-                        service)
-                else:
-                    self.perf_records['service'][eo.transition.name] = [
-                        service]
+                if service is not None and eo.transition.label in self.perf_records['service']:
+                    self.perf_records['service'][eo.transition.label].append(service)
+                elif service is not None:
+                    self.perf_records['service'][eo.transition.label] = [service]
+
             if p_sojourn:
-                if p_waiting is True and p_service is not True:
-                    service = self.measure_service(eo, R)
-                    sojourn = waiting + service
-                elif p_waiting is not True and p_service is True:
-                    waiting = self.measure_waiting(eo, R)
-                    sojourn = waiting + service
-                else:
-                    sojourn = self.measure_sojourn(eo, R)
+                sojourn = self.measure_sojourn(eo, R)
+                if sojourn is not None and eo.transition.label in self.perf_records['sojourn']:
+                    self.perf_records['sojourn'][eo.transition.label].append(sojourn)
+                elif sojourn is not None:
+                    self.perf_records['sojourn'][eo.transition.label] = [sojourn]
 
-                if eo.transition.name in self.perf_records['sojourn']:
-                    self.perf_records['sojourn'][eo.transition.name].append(
-                        sojourn)
-                else:
-                    self.perf_records['sojourn'][eo.transition.name] = [
-                        sojourn]
             if p_sync:
                 sync = self.measure_synchronization(eo, R)
-                if eo.transition.name in self.perf_records['synchronization']:
-                    self.perf_records['synchronization'][eo.transition.name].append(
-                        sync)
-                else:
-                    self.perf_records['synchronization'][eo.transition.name] = [
-                        sync]
+                if sync is not None and eo.transition.label in self.perf_records['synchronization']:
+                    self.perf_records['synchronization'][eo.transition.label].append(sync)
+                elif sync is not None:
+                    self.perf_records['synchronization'][eo.transition.label] = [sync]
+
             if p_pooling:
                 for ot in ots:
                     ot_pooling = self.measure_pooling(eo, R, ot)
-                    if eo.transition.name in self.perf_records['pooling'][ot]:
-                        self.perf_records['pooling'][ot][eo.transition.name].append(
-                            ot_pooling)
-                    else:
-                        self.perf_records['pooling'][ot][eo.transition.name] = [
-                            ot_pooling]
+                    if ot_pooling is not None and eo.transition.label in self.perf_records['pooling'][ot]:
+                        self.perf_records['pooling'][ot][eo.transition.label].append(ot_pooling)
+                    elif ot_pooling is not None:
+                        self.perf_records['pooling'][ot][eo.transition.label] = [ot_pooling]
+
             if p_lagging:
                 for ot in ots:
                     ot_lagging = self.measure_lagging(eo, R, ot)
-                    if eo.transition.name in self.perf_records['lagging'][ot]:
-                        self.perf_records['lagging'][ot][eo.transition.name].append(
-                            ot_lagging)
-                    else:
-                        self.perf_records['lagging'][ot][eo.transition.name] = [
-                            ot_lagging]
+                    if ot_lagging is not None and eo.transition.label in self.perf_records['lagging'][ot]:
+                        self.perf_records['lagging'][ot][eo.transition.label].append(ot_lagging)
+                    elif ot_lagging is not None:
+                        self.perf_records['lagging'][ot][eo.transition.label] = [ot_lagging]
+
             if p_flow:
-                if p_sojourn is not True and p_sync is True:
-                    if p_waiting is True and p_service is not True:
+                if p_sojourn is not True and p_sync is True and sync is not None:
+                    if p_waiting is True and p_service is not True and waiting is not None:
                         service = self.measure_service(eo, R)
-                        sojourn = waiting + service
-                    elif p_waiting is not True and p_service is True:
+                        sojourn = waiting + service if service is not None else None
+                    elif p_waiting is not True and p_service is True and service is not None:
                         waiting = self.measure_waiting(eo, R)
-                        sojourn = waiting + service
-                    else:
+                        sojourn = waiting + service if waiting is not None else None
+                    elif waiting is None or service is None:
                         sojourn = self.measure_sojourn(eo, R)
-                elif p_sojourn is True and p_sync is not True:
+                    flow = sojourn + sync if sojourn is not None else None
+                elif p_sojourn is True and p_sync is not True and sojourn is not None:
                     sync = self.measure_synchronization(eo, R)
+                    flow = sojourn + sync if sync is not None else None
                 else:
                     sojourn = self.measure_sojourn(eo, R)
                     sync = self.measure_synchronization(eo, R)
-                flow = sojourn + sync
-                if eo.transition.name in self.perf_records['flow']:
-                    self.perf_records['flow'][eo.transition.name].append(
-                        flow)
-                else:
-                    self.perf_records['flow'][eo.transition.name] = [
-                        flow]
+                    flow = sojourn + sync if sojourn is not None and sync is not None else None
+
+                if flow is not None and eo.transition.label in self.perf_records['flow']:
+                    self.perf_records['flow'][eo.transition.label].append(flow)
+                elif flow is not None:
+                    self.perf_records['flow'][eo.transition.label] = [flow]
+
+
 
         # aggregate measures
         perf_diag = {}
         if p_waiting:
             perf_diag['agg_waiting_time'] = aggregate_perf_records(
                 self.perf_records['waiting'], aggregation_measure='all')
         if p_service:
@@ -353,74 +333,64 @@
 
     def measure_waiting(self, eo: EventOccurrence, R: Set[TokenVisit]):
         if len(R) > 0:
             start_times = [r.start for r in R]
             waiting = (
                 eo.event.vmap[ocpa_constants.DEFAULT_OCEL_START_TIMESTAMP_KEY] - min(start_times)).total_seconds()
             if waiting < 0:
-                return 0
+                return None
             return waiting
-        else:
-            return 0
 
     def measure_service(self, eo: EventOccurrence, R: Set[TokenVisit]):
         service = (
             eo.event.time - eo.event.vmap[ocpa_constants.DEFAULT_OCEL_START_TIMESTAMP_KEY]).total_seconds()
         if service < 0:
-            return 0
+            return None
         return service
 
     def measure_sojourn(self, eo: EventOccurrence, R: Set[TokenVisit]):
         if len(R) > 0:
             start_times = [r.start for r in R]
             sojourn = (
                 eo.event.time - min(start_times)).total_seconds()
             if sojourn < 0:
-                return 0
+                return None
             return sojourn
-        else:
-            return 0
 
     def measure_synchronization(self, eo: EventOccurrence, R: Set[TokenVisit]):
         if len(R) > 0:
             start_times = [r.start for r in R]
             sync = (max(start_times) - min(start_times)).total_seconds()
             if sync < 0:
-                return 0
+                return None
             return sync
-        else:
-            return 0
 
     def measure_pooling(self, eo: EventOccurrence, R: Set[TokenVisit], ot: str):
         ot_R = [r for r in R if r.token[1] in self.object_map[ot]]
         if len(ot_R) > 0:
             ot_start_times = [
                 r.start for r in ot_R]
             pooling = (max(ot_start_times) -
                        min(ot_start_times)).total_seconds()
             if pooling < 0:
-                return 0
+                return None
             return pooling
-        else:
-            return 0
 
     def measure_lagging(self, eo: EventOccurrence, R: Set[TokenVisit], ot: str):
         ot_R = [r for r in R if r.token[1] in self.object_map[ot]]
         non_ot_R = [r for r in R if r.token[1] not in self.object_map[ot]]
         if len(ot_R) > 0 and len(non_ot_R) > 0:
             non_ot_start_times = [r.start for r in non_ot_R]
             ot_start_times = [
                 r.start for r in ot_R]
             lagging = (max(ot_start_times) -
                        min(non_ot_start_times)).total_seconds()
             if lagging < 0:
-                return 0
+                return None
             return lagging
-        else:
-            return 0
 
 
 def aggregate_stats(perf_records, elem, aggregation_measure):
     """
     Aggregate the perf_records
 
     Parameters
@@ -433,24 +403,24 @@
         Aggregation measure (e.g. mean, min) to use
 
     Returns
     -----------
     aggr_stat
         Aggregated perf_records
     """
-    aggr_stat = 0
+    aggr_stat = None
     if aggregation_measure == "mean" or aggregation_measure is None:
         aggr_stat = mean(perf_records[elem])
     elif aggregation_measure == "median":
         aggr_stat = median(perf_records[elem])
     elif aggregation_measure == "stdev":
         if len(perf_records[elem]) > 1:
             aggr_stat = stdev(perf_records[elem])
         else:
-            aggr_stat = 0
+            aggr_stat = None
     elif aggregation_measure == "sum":
         aggr_stat = sum(perf_records[elem])
     elif aggregation_measure == "min":
         aggr_stat = min(perf_records[elem])
     elif aggregation_measure == "max":
         aggr_stat = max(perf_records[elem])
     # aggr_stat = human_readable_stat(aggr_stat)
@@ -471,27 +441,27 @@
         Aggregation measure (e.g. mean, min) to use
 
     Returns
     -----------
     aggr_stat
         Aggregated perf_records
     """
-    aggr_stat = 0
+    aggr_stat = None
     if aggregation_measure == "mean" or aggregation_measure is None:
         if ot in perf_records:
             aggr_stat = mean(perf_records[ot][elem])
     elif aggregation_measure == "median":
         if ot in perf_records:
             aggr_stat = median(perf_records[ot][elem])
     elif aggregation_measure == "stdev":
         if ot in perf_records:
             if len(perf_records[ot][elem]) > 1:
                 aggr_stat = stdev(perf_records[ot][elem])
         else:
-            aggr_stat = 0
+            aggr_stat = None
     elif aggregation_measure == "sum":
         if ot in perf_records:
             aggr_stat = sum(perf_records[ot][elem])
     elif aggregation_measure == "min":
         if ot in perf_records:
             aggr_stat = min(perf_records[ot][elem])
     elif aggregation_measure == "max":
@@ -624,65 +594,56 @@
         p_arc_freq = False
     if 'flow_time' in parameters['measures']:
         p_flow = True
     else:
         p_flow = False
 
     transformed_diag = {}
-
     for tr in ocpn.transitions:
         if tr.silent == False:
-            transformed_diag[tr.name] = {}
-            transformed_diag[tr.name]["act_freq"] = diag['act_freq'][tr.name]
+            transformed_diag[tr.label] = {}
+            transformed_diag[tr.label]["act_freq"] = diag['act_freq'][tr.label]
 
             if p_object_count:
-                transformed_diag[tr.name]["object_count"] = textualize_object_count(
-                    tr.name, ocpn.object_types, parameters['agg'], diag["object_count"])
+                if 'object_count' in diag:
+                    transformed_diag[tr.label]['object_count'] = {ot: {agg: diag['object_count'][ot][tr.label][agg] for agg in parameters['agg'] if agg in diag['object_count'][ot][tr.label]} for ot in ocpn.object_types if tr.label in diag['object_count'][ot]}
 
             if p_waiting:
-                transformed_diag[tr.name]['waiting_time'] = textualize_waiting_time(
-                    tr.name, parameters['agg'], diag['agg_waiting_time'])
+                if 'agg_waiting_time' in diag and tr.label in diag['agg_waiting_time']:
+                    transformed_diag[tr.label]['waiting_time'] = {agg: diag['agg_waiting_time'][tr.label][agg] for agg in parameters['agg'] if agg in diag['agg_waiting_time'][tr.label]}
 
             if p_service:
-                transformed_diag[tr.name]['service_time'] = textualize_service_time(
-                    tr.name, parameters['agg'], diag['agg_service_time'])
+                if 'agg_service_time' in diag and tr.label in diag['agg_service_time']:
+                    transformed_diag[tr.label]['service_time'] = {agg: diag['agg_service_time'][tr.label][agg] for agg in parameters['agg'] if agg in diag['agg_service_time'][tr.label]}
 
             if p_sojourn:
-                transformed_diag[tr.name]['sojourn_time'] = textualize_sojourn_time(
-                    tr.name, parameters['agg'], diag['agg_sojourn_time'])
+                if 'agg_sojourn_time' in diag and tr.label in diag['agg_sojourn_time']:
+                    transformed_diag[tr.label]['sojourn_time'] = {agg: diag['agg_sojourn_time'][tr.label][agg] for agg in parameters['agg'] if agg in diag['agg_sojourn_time'][tr.label]}
 
             if p_sync:
-                transformed_diag[tr.name]['synchronization_time'] = textualize_synchronization_time(
-                    tr.name, parameters['agg'], diag['agg_synchronization_time'])
+                if 'agg_synchronization_time' in diag and tr.label in diag['agg_synchronization_time']:
+                    transformed_diag[tr.label]['synchronization_time'] = {agg: diag['agg_synchronization_time'][tr.label][agg] for agg in parameters['agg'] if agg in diag['agg_synchronization_time'][tr.label]}
 
             if p_pooling:
-                transformed_diag[tr.name]['pooling_time'] = textualize_pooling_time(
-                    tr.name, ocpn.object_types, parameters['agg'], diag['agg_pooling_time'])
+                if 'agg_pooling_time' in diag:
+                    transformed_diag[tr.label]['pooling_time'] = {ot: {agg: diag['agg_pooling_time'][ot][tr.label][agg] for agg in parameters['agg'] if agg in diag['agg_pooling_time'][ot][tr.label]} for ot in ocpn.object_types if tr.label in diag['agg_pooling_time'][ot]}
 
             if p_lagging:
-                transformed_diag[tr.name]['lagging_time'] = textualize_lagging_time(
-                    tr.name, ocpn.object_types, parameters['agg'], diag['agg_lagging_time'])
+                if 'agg_lagging_time' in diag:
+                    transformed_diag[tr.label]['lagging_time'] = {ot: {agg: diag['agg_lagging_time'][ot][tr.label][agg] for agg in parameters['agg'] if agg in diag['agg_lagging_time'][ot][tr.label]} for ot in ocpn.object_types if tr.label in diag['agg_lagging_time'][ot]}
 
             if p_flow:
-                transformed_diag[tr.name]['flow_time'] = textualize_flow_time(
-                    tr.name, parameters['agg'], diag['agg_flow_time'])
+                if 'agg_flow_time' in diag and tr.label in diag['agg_flow_time']:
+                    transformed_diag[tr.label]['flow_time'] = {agg: diag['agg_flow_time'][tr.label][agg] for agg in parameters['agg'] if agg in diag['agg_flow_time'][tr.label]}
+
 
     transformed_diag['arc_freq'] = diag['arc_freq']
 
     return transformed_diag
 
-
-# def merge_agg_performance(agg_performance):
-#     merged_agg_performance = dict()
-#     for persp in agg_performance:
-#         for el in agg_performance[persp]:
-#             merged_agg_performance[repr(el)] = agg_performance[persp][el]
-#     return merged_agg_performance
-
-
 def merge_replay(ocpn, replay):
     merged_replay = dict()
     arcs = [a for a in ocpn.arcs]
     for persp in replay.keys():
         for elem in replay[persp].keys():
             if type(elem) is PetriNet.Arc:
                 arc_name = ""
@@ -778,128 +739,7 @@
         # min
         agg_merged_object_count[act]["min"] = dict()
         for persp in merged_object_count[act].keys():
             agg_merged_object_count[act]["min"][persp] = mean(
                 merged_object_count[act][persp])
 
     return agg_merged_object_count
-
-
-def textualize_act_freq(tr_name, act_freq):
-    text = "Activity frequency: "
-    text += f'{act_freq[tr_name]}'
-    return text
-
-
-def textualize_waiting_time(tr_name, aggs, waiting_time):
-    record = {}
-    text = "Waiting time: {"
-    for agg in aggs:
-        text += f' {agg}: '
-        if agg in waiting_time[tr_name]:
-            record[agg] = waiting_time[tr_name][agg]
-            text += f'{waiting_time[tr_name][agg]}'
-    text += '}'
-    return record
-
-
-def textualize_service_time(tr_name, aggs, service_time):
-    record = {}
-    text = "Service time: {"
-    for agg in aggs:
-        text += f' {agg}: '
-        if agg in service_time[tr_name]:
-            record[agg] = service_time[tr_name][agg]
-            text += f'{service_time[tr_name][agg]}'
-    text += '}'
-    return record
-
-
-def textualize_sojourn_time(tr_name, aggs, sojourn_time):
-    record = {}
-    text = "sojourn time: {"
-    for agg in aggs:
-        text += f' {agg}: '
-        if agg in sojourn_time[tr_name]:
-            record[agg] = sojourn_time[tr_name][agg]
-            text += f'{sojourn_time[tr_name][agg]}'
-    text += '}'
-    return record
-
-
-def textualize_synchronization_time(tr_name, aggs, synchronization_time):
-    record = {}
-    text = "synchronization time: {"
-    for agg in aggs:
-        text += f' {agg}: '
-        if agg in synchronization_time[tr_name]:
-            record[agg] = synchronization_time[tr_name][agg]
-            text += f'{synchronization_time[tr_name][agg]}'
-    text += '}'
-    return record
-
-
-def textualize_object_count(tr_name, obj_types, aggs, object_count):
-    record = {}
-    text = "Number of objects: { "
-    for obj_type in obj_types:
-        record[obj_type] = {}
-        if tr_name in object_count[obj_type]:
-            text += f'{obj_type}: {{'
-            for agg in aggs:
-                if agg in object_count[obj_type][tr_name]:
-                    record[obj_type][agg] = object_count[obj_type][tr_name][agg]
-                    text += f'{agg}: {{'
-                    text += f" {obj_type}={object_count[obj_type][tr_name][agg]} "
-                    text += '} '
-            text += '} '
-    text += '}'
-    return record
-
-
-def textualize_lagging_time(tr_name, obj_types, aggs, lagging_time):
-    record = {}
-    text = "lagging time: { "
-    for obj_type in obj_types:
-        record[obj_type] = {}
-        if tr_name in lagging_time[obj_type]:
-            text += f'{obj_type}: {{'
-            for agg in aggs:
-                if agg in lagging_time[obj_type][tr_name]:
-                    record[obj_type][agg] = lagging_time[obj_type][tr_name][agg]
-                    text += f'{agg}: {{'
-                    text += f" {obj_type}={lagging_time[obj_type][tr_name][agg]} "
-                    text += '} '
-            text += '} '
-    text += '}'
-    return record
-
-
-def textualize_pooling_time(tr_name, obj_types, aggs, pooling_time):
-    record = {}
-    text = "Pooling time: { "
-    for obj_type in obj_types:
-        record[obj_type] = {}
-        if tr_name in pooling_time[obj_type]:
-            text += f'{obj_type}: {{'
-            for agg in aggs:
-                if agg in pooling_time[obj_type][tr_name]:
-                    record[obj_type][agg] = pooling_time[obj_type][tr_name][agg]
-                    text += f'{agg}: {{'
-                    text += f" {obj_type}={pooling_time[obj_type][tr_name][agg]} "
-                    text += '} '
-            text += '} '
-    text += '}'
-
-    return record
-
-
-def textualize_flow_time(tr_name, aggs, flow_time):
-    record = {}
-    text = "flow time: {"
-    for agg in aggs:
-        text += f' {agg}: '
-        if agg in flow_time[tr_name]:
-            record[agg] = flow_time[tr_name][agg]
-            text += f'{flow_time[tr_name][agg]}'
-    text += '}'
-    return record
```

## ocpa/algo/predictive_monitoring/factory.py

```diff
@@ -1,9 +1,10 @@
 import time
-
+import tqdm
+from multiprocessing.dummy import Pool as ThreadPool
 import ocpa.algo.predictive_monitoring.event_based_features.extraction_functions as event_features
 import ocpa.algo.predictive_monitoring.execution_based_features.extraction_functions as execution_features
 from ocpa.algo.predictive_monitoring.obj import Feature_Storage
 
 EVENT_BASED = "event_based"
 EXECUTION_BASED = "execution_based"
 
@@ -24,15 +25,14 @@
 EVENT_CURRENT_TOTAL_OBJECT_COUNT = "event_current_total_object_count"
 EVENT_PREVIOUS_OBJECT_COUNT = "event_previous_object_count"
 EVENT_PREVIOUS_TYPE_COUNT = "event_previous_type_count"
 EVENT_OBJECTS = "event_objects"
 EVENT_EXECUTION_DURATION = "event_execution_time"
 EVENT_ELAPSED_TIME = "event_elapsed_time"
 EVENT_REMAINING_TIME = "event_remaining_time"
-EVENT_DURATION = "event_duration"
 EVENT_FLOW_TIME = "event_flow_time"
 EVENT_SYNCHRONIZATION_TIME = "event_synchronization_time"
 EVENT_SOJOURN_TIME = "event_sojourn_time"
 EVENT_WAITING_TIME = "event_waiting_time"
 EVENT_POOLING_TIME = "event_pooling_time"
 EVENT_LAGGING_TIME = "event_lagging_time"
 
@@ -67,20 +67,19 @@
                   EVENT_CURRENT_TOTAL_OBJECT_COUNT: event_features.current_total_object_count,
                   EVENT_PREVIOUS_OBJECT_COUNT: event_features.previous_object_count,
                   EVENT_PREVIOUS_TYPE_COUNT: event_features.previous_type_count,
                   EVENT_OBJECTS: event_features.event_objects,
                   EVENT_EXECUTION_DURATION: event_features.execution_duration,
                   EVENT_ELAPSED_TIME: event_features.elapsed_time,
                   EVENT_REMAINING_TIME: event_features.remaining_time,
-                  EVENT_DURATION: event_features.event_duration,
                   EVENT_LAGGING_TIME: event_features.lagging_time,
                   EVENT_POOLING_TIME: event_features.pooling_time,
                   EVENT_WAITING_TIME: event_features.waiting_time,
                   EVENT_SOJOURN_TIME: event_features.sojourn_time,
-                  EVENT_SYNCHRONIZATION_TIME: event_features.sojourn_time,
+                  EVENT_SYNCHRONIZATION_TIME: event_features.synchronization_time,
                   EVENT_FLOW_TIME: event_features.flow_time
 
 
                   },
     EXECUTION_BASED: {EXECUTION_NUM_OF_EVENTS: execution_features.number_of_events,
                       EXECUTION_NUM_OF_END_EVENTS: execution_features.number_of_ending_events,
                       EXECUTION_THROUGHPUT: execution_features.throughput_time,
@@ -90,16 +89,46 @@
                       EXECUTION_NUM_OF_STARTING_EVENTS: execution_features.number_of_starting_events,
                       EXECUTION_LAST_EVENT_TIME_BEFORE: execution_features.delta_last_event,
                       EXECUTION_SERVICE_TIME: execution_features.service_time,
                       EXECUTION_AVG_SERVICE_TIME: execution_features.avg_service_time
                       }
 }
 
+def _apply_to_process_execution(args):
+    (c_id, ocel, event_based_features, execution_based_features, event_attributes, event_object_attributes, execution_object_attributes, multi_output_features) = args
+    case = ocel.process_executions[c_id]
+    case_graph = ocel.graph.eog.subgraph(case)
+    feature_graph = Feature_Storage.Feature_Graph(
+        pexec_id=c_id, graph=case_graph, ocel=ocel)
+    for execution_feature in execution_based_features:
+        execution_function, params = execution_feature
+        feature_graph.add_attribute(
+            execution_feature, VERSIONS[EXECUTION_BASED][execution_function](case_graph, ocel, params))
+        for (object_type, attr, fun) in execution_object_attributes:
+            feature_graph.add_attribute(
+                object_type + "_" + attr + fun.__name__, fun([object_type[attr]]))
+    for node in feature_graph.nodes:
+        for m_event_feature in multi_output_features:
+            event_function, params = m_event_feature
+            results =  VERSIONS[EVENT_BASED][event_function](node, ocel, params)
+            for res in results.keys():
+                node.add_attribute(
+                    (event_function, res), results[res])
+        for event_feature in event_based_features:
+            event_function, params = event_feature
+            node.add_attribute(
+                event_feature, VERSIONS[EVENT_BASED][event_function](node, ocel, params))
+        for attr in event_attributes:
+            node.add_attribute(attr, ocel.get_value(node.event_id, attr))
+        for (object_type, attr, fun) in event_object_attributes:
+            feature_graph.add_attribute(
+                object_type + "_" + attr + fun.__name__, fun([object_type[attr]]))
+    return feature_graph
 
-def apply(ocel, event_based_features=[], execution_based_features=[], event_attributes=[], event_object_attributes=[], execution_object_attributes=[]):
+def apply(ocel, event_based_features=[], execution_based_features=[], event_attributes=[], event_object_attributes=[], execution_object_attributes=[], workers = 4, multi_output_event_features = []):
     '''
     Creates a :class:`Feature Storage object <ocpa.algo.predictive_monitoring.obj.Feature_Storage>` from the object-centric
     event log considering the desired features. Features are passed as a list of Tuples, containing first the function
     to calculate the feature and second a tuple of parameter values (can be empty). The feature functions need to have
     a signature of (event_id (int), :class:`ocel <ocpa.objects.log.ocel.OCEL>`, parameters (Tuple)) for event-based
     features or (case (int), :class:`ocel <ocpa.objects.log.ocel.OCEL>`, parameters (Tuple)) for execution-based features.
     A set of predefined feature functions can be found in :mod:`event-based features <ocpa.algo.predictive_monitoring.event_based_features>`
@@ -116,66 +145,28 @@
 
     :param event_attributes: List of event attributes to be added to an event's features.
     :type event_attributes: str
 
     :param event_object_attributes: To be added in future
     :param execution_object_attributes: To be added in future
 
+    :param workers: Number of threads to extract the features
+    :type workers: int
+
     :return: Feature Storage
     :rtype: :class:`Feature Storage <ocpa.algo.predictive_monitoring.obj.Feature_Storage>`
 
     '''
 
-    s_time = time.time()
     ocel.log.log["event_objects"] = ocel.log.log.apply(
         lambda x: [(ot, o) for ot in ocel.object_types for o in x[ot]], axis=1)
     ocel.log.create_efficiency_objects()
     feature_storage = Feature_Storage(
         event_features=event_based_features, execution_features=execution_based_features, ocel=ocel)
-    object_f_time = time.time()-s_time
-    id = 0
-    subgraph_time = 0
-    execution_time = 0
-    nodes_time = 0
-    adding_time = 0
-    for case in ocel.process_executions:
-        s_time = time.time()
-        case_graph = ocel.graph.eog.subgraph(case)
-        feature_graph = Feature_Storage.Feature_Graph(
-            case_id=id, graph=case_graph, ocel=ocel)
-        subgraph_time += time.time() - s_time
-        s_time = time.time()
-        for execution_feature in execution_based_features:
-            execution_function, params = execution_feature
-            feature_graph.add_attribute(
-                execution_feature, VERSIONS[EXECUTION_BASED][execution_function](case_graph, ocel, params))
-            for (object_type, attr, fun) in execution_object_attributes:
-                # TODO add object frame
-                feature_graph.add_attribute(
-                    object_type+"_"+attr+fun.__name__, fun([object_type[attr]]))
-        execution_time += time.time() - s_time
-        s_time = time.time()
-        for node in feature_graph.nodes:
-            for event_feature in event_based_features:
-                event_function, params = event_feature
-                node.add_attribute(
-                    event_feature, VERSIONS[EVENT_BASED][event_function](node, ocel, params))
-            for attr in event_attributes:
-                node.add_attribute(attr, ocel.get_value(node.event_id, attr))
-                # node.add_attribute(attr,ocel.log.loc[node.event_id][attr])
-            for (object_type, attr, fun) in event_object_attributes:
-                # TODO add object frame
-                feature_graph.add_attribute(
-                    object_type+"_"+attr+fun.__name__, fun([object_type[attr]]))
-        nodes_time += time.time() - s_time
-        s_time = time.time()
-        feature_storage.add_feature_graph(feature_graph)
-        adding_time += time.time() - s_time
-        id += 1
+    pool = ThreadPool(workers)
+    parameter_space = [(c_id,ocel,event_based_features, execution_based_features, event_attributes, event_object_attributes, execution_object_attributes, multi_output_event_features ) for c_id in range(0,len(ocel.process_executions))]
+    print("Applying feature extraction to process executions")
+    results = list(tqdm.tqdm(pool.imap(_apply_to_process_execution, parameter_space), total=len(parameter_space)))
+    for f_g in results:
+        feature_storage.add_feature_graph(f_g)
     del ocel.log.log["event_objects"]
-    # print("___")
-    #print("Execution time "+str(execution_time))
-    #print("Node Features " + str(nodes_time))
-    #print("Adding Features " + str(adding_time))
-    #print("Subgraph Features " + str(subgraph_time))
-    #print("prep time " + str(object_f_time))
     return feature_storage
```

## ocpa/algo/predictive_monitoring/obj.py

```diff
@@ -1,40 +1,46 @@
 import pandas as pd
-from sklearn.preprocessing import StandardScaler
+# from sklearn.preprocessing import StandardScaler
+from ocpa.util.util import StandardScaler
 import random
 
-
 class Feature_Storage:
     '''
     The Feature Storage class stores features extracted for an obejct-centric event log. It stores it in form of feature
     graphs: Each feature graph contains the features for a process execution in form of labeled nodes and graph properties.
     Furthermore, the class provides the possibility to create a training/testing split on the basis of the graphs.
     '''
 
     class Feature_Graph:
         class Node:
-            def __init__(self, event_id, objects):
+            def __init__(self, event_id, objects,pexec_id):
                 self._event = event_id
                 self._attributes = {}
                 self._objects = objects
+                self._pexec_id = pexec_id
 
             def add_attribute(self, key, value):
                 self._attributes[key] = value
 
             def _get_attributes(self):
                 return self._attributes
 
             def _get_objects(self):
                 return self._objects
 
             def _get_event_id(self):
                 return self._event
+
+            def _get_pexec_id(self):
+                return self._pexec_id
+
             event_id = property(_get_event_id)
             attributes = property(_get_attributes)
             objects = property(_get_objects)
+            pexec_id = property(_get_pexec_id)
 
         class Edge:
             def __init__(self, source, target, objects):
                 self._source = source
                 self._target = target
                 self._objects = objects
                 self._attributes = {}
@@ -55,31 +61,34 @@
                 return self._attributes
 
             attributes = property(_get_attributes)
             source = property(_get_source)
             target = property(_get_target)
             objects = property(_get_objects)
 
-        def __init__(self, case_id, graph, ocel):
-            self._case_id = case_id
-            self._nodes = [Feature_Storage.Feature_Graph.Node(e_id, ocel.get_value(e_id, "event_objects")) for e_id in
+        def __init__(self, pexec_id, graph, ocel):
+            self._pexec_id = pexec_id
+            self._nodes = [Feature_Storage.Feature_Graph.Node(e_id, ocel.get_value(e_id, "event_objects"),pexec_id) for e_id in
                            graph.nodes]
             #self._nodes = [Feature_Storage.Feature_Graph.Node(e_id, ocel.log.loc[e_id]["event_objects"]) for e_id in graph.nodes]
             self._node_mapping = {node.event_id: node for node in self._nodes}
             self._objects = {(source, target): set(ocel.get_value(source, "event_objects")).intersection(
                 set(ocel.get_value(target, "event_objects"))) for source, target in graph.edges}
             #self._objects = {(source,target):set(ocel.log.loc[source]["event_objects"]).intersection(set(ocel.log.loc[target]["event_objects"])) for source,target in graph.edges}
             self._edges = [Feature_Storage.Feature_Graph.Edge(
                 source, target, objects=self._objects[(source, target)])for source, target in graph.edges]
             self._edge_mapping = {
                 (edge.source, edge.target): edge for edge in self._edges}
             self._attributes = {}
 
         def _get_nodes(self):
             return self._nodes
+        
+        def _get_pexec_id(self):
+            return self._pexec_id
 
         def _get_edges(self):
             return self._edges
 
         def _get_objects(self):
             return self._objects
 
@@ -96,14 +105,15 @@
         def get_edge_from_event_ids(self, source, target):
             return self._edge_mapping[(source, target)]
 
         def add_attribute(self, key, value):
             self._attributes[key] = value
 
         attributes = property(_get_attributes)
+        pexec_id = property(_get_pexec_id)
         nodes = property(_get_nodes)
         edges = property(_get_edges)
         objects = property(_get_objects)
 
     def __init__(self, event_features, execution_features, ocel):
         self._event_features = event_features
         self._edge_features = []
@@ -190,16 +200,22 @@
 
         graphs_indices = list(range(0, len(self.feature_graphs)))
         random.Random(state).shuffle(graphs_indices)
         split_index = int((1-test_size)*len(graphs_indices))
         # print(split_index)
         self._training_indices = graphs_indices[:split_index]
         self._test_indices = graphs_indices[split_index:]
-        train_graphs, test_graphs = [self.feature_graphs[i] for i in self._training_indices], [
-            self.feature_graphs[i] for i in self._test_indices]
+        train_graphs, test_graphs = [], []
+        for g in self.feature_graphs:
+            if g.pexec_id in self._training_indices:
+                train_graphs.append(g)
+            elif g.pexec_id in self._test_indices:
+                test_graphs.append(g)
+            else:
+                raise Exception("Graph not in training or test set")
         # Normalize
         features = self.event_features
         train_table = self._event_id_table(train_graphs)
         test_table = self._event_id_table(test_graphs)
         scaler = StandardScaler()
         train_table[self.event_features] = scaler.fit_transform(
             train_table[self.event_features])
@@ -207,15 +223,18 @@
             test_table[self.event_features])
         self._scaler = scaler
         # update features features
         # for efficiency
         train_mapper = self._create_mapper(train_table)
         test_mapper = self._create_mapper(test_table)
         # change original values!
-        for g in [self.feature_graphs[i] for i in self.training_indices]:
-            for node in g.nodes:
-                for att in node.attributes.keys():
-                    node.attributes[att] = train_mapper[node.event_id][att]
-        for g in [self.feature_graphs[i] for i in self.test_indices]:
-            for node in g.nodes:
-                for att in node.attributes.keys():
-                    node.attributes[att] = test_mapper[node.event_id][att]
+        for g in self.feature_graphs:
+            if g.pexec_id in self._training_indices:
+                for node in g.nodes:
+                    for att in node.attributes.keys():
+                        node.attributes[att] = train_mapper[node.event_id][att]
+            elif g.pexec_id in self._test_indices:
+                for node in g.nodes:
+                    for att in node.attributes.keys():
+                        node.attributes[att] = test_mapper[node.event_id][att]
+            else:
+                raise Exception("Graph not in training or test set")
```

## ocpa/algo/predictive_monitoring/sequential.py

```diff
@@ -8,27 +8,26 @@
     :param index_list: list of indices to be encoded as sequences. Default is "all"
     :type index_list: "all" or list(int)
 
     :return: List of sequential encodings: Each sequential encoding is a sequence of feature dicts.
     :rtype: list(list(dict))
 
     '''
-    if index_list == "all":
-        index_list = list(range(0, len(feature_storage.feature_graphs)))
     sequences = []
-    for g in [feature_storage.feature_graphs[i] for i in index_list]:
-        sequence = []
-        #sort nodes on event time (through the event id)
-        event_ids = [n.event_id for n in g.nodes]
-        event_ids.sort()
-        for e_id in event_ids:
-            for node in g.nodes:
-                if e_id == node.event_id:
-                    sequence.append(node.attributes)
-        sequences.append(sequence)
+    for g in feature_storage.feature_graphs:
+        if index_list == "all" or g.pexec_id in index_list:
+            sequence = []
+            #sort nodes on event time (through the event id)
+            event_ids = [n.event_id for n in g.nodes]
+            event_ids.sort()
+            for e_id in event_ids:
+                for node in g.nodes:
+                    if e_id == node.event_id:
+                        sequence.append(node.attributes)
+            sequences.append(sequence)
     return sequences
 
 def construct_k_dataset(sequences, k, features, target):
     X = []
     y = []
     for s in sequences:
         if len(s) != 0:
```

## ocpa/algo/predictive_monitoring/tabular.py

```diff
@@ -9,15 +9,14 @@
 
     :param index_list: list of indices to be encoded as sequences. Default is "all"
     :type index_list: "all" or list(int)
 
     :return: List of sequential encodings: Each sequential encoding is a sequence of feature dicts.
     :rtype: list(list(dict))
     '''
-    if index_list == "all":
-        index_list = list(range(0,len(feature_storage.feature_graphs)))
     dict_list = []
-    for g in [feature_storage.feature_graphs[i] for i in index_list]:
-        for node in g.nodes:
-            dict_list.append(node.attributes)
+    for g in feature_storage.feature_graphs:
+        if index_list == "all" or g.pexec_id in index_list:
+            for node in g.nodes:
+                dict_list.append(node.attributes)
     df = pd.DataFrame(dict_list)
     return df
```

## ocpa/algo/predictive_monitoring/event_based_features/extraction_functions.py

```diff
@@ -156,17 +156,16 @@
         duration = (max(timestamps) - min(timestamps)).total_seconds()
         value_array.append(duration)
 
     return sum(value_array) / len(value_array)
 
 def remaining_time(node, ocel, params):
     e_id = node.event_id
-    cases = ocel.process_execution_mappings[e_id]
     value_array = []
-    for case in cases:
+    for case in [node.pexec_id]:
         c_res = 0
         prev_events = get_recent_events(e_id, case, ocel)
         following_events = [e for e in ocel.process_executions[case] if e not in prev_events]
         following_events.append(e_id)
 
         timestamps = [ocel.get_value(e, "event_timestamp") for e in following_events]
         duration = (max(timestamps) - min(timestamps)).total_seconds()
@@ -278,26 +277,17 @@
             ot_end_timestamps = [ocel.get_value(e, "event_timestamp") for e in preset if
                                  ocel.get_value(e, object_type)]
             duration = (max(ot_end_timestamps) - min(ot_maxs)).total_seconds()
         res.append(duration)
 
     return sum(res) / len(res)
 
-def event_duration(node, ocel, params):
-    start_column = params[0]
-    return (ocel.get_value(node.event_id, "event_timestamp") - ocel.get_value(node.event_id,
-                                                                              start_column)).total_seconds()
-
 def service_time(node, ocel, params):
     start_column = params[0]
-    activity = params[1]
-    if ocel.get_value(node.event_id,"event_activity") == activity:
-        return (ocel.get_value(node.event_id,"event_timestamp") - ocel.get_value(node.event_id,start_column)).total_seconds()
-    else:
-        return None
+    return (ocel.get_value(node.event_id,"event_timestamp") - ocel.get_value(node.event_id,start_column)).total_seconds()
 
 
 #objects
 def current_total_object_count(node, ocel, params):
     time_horizon = params[0]
     t_e = ocel.get_value(node.event_id, "event_timestamp")
     all_events = ocel.log["event_id"].tolist()
```

## ocpa/algo/util/__init__.py

```diff
@@ -1,4 +1,5 @@
 import ocpa.algo.util.filtering
 import ocpa.algo.util.process_executions
 import ocpa.algo.util.retrieval
 import ocpa.algo.util.variants
+import ocpa.algo.util.aopm
```

## ocpa/algo/util/filtering/log/activity_filtering.py

```diff
@@ -1,31 +1,33 @@
 from collections import Counter
 from ocpa.objects.log.util import misc as log_util
 
+
 def filter_infrequent_activities(ocel, threshold):
     '''
     Filters infrequent activities from an OCEL
 
     :param ocel: Object-centric event log
     :type ocel: :class:`OCEL <ocpa.objects.log.ocel.OCEL>`
 
     :param threshold: Kumulative frequency of the most frequent activities to be included.
     :type threshold: float
 
     :return: Object-centric event log
     :rtype: :class:`OCEL <ocpa.objects.log.ocel.OCEL>`
 
     '''
-    activity_distribution = Counter(ocel.log.log["event_activity"].values.tolist())
+    activity_distribution = Counter(
+        ocel.log.log["event_activity"].values.tolist())
     activities, frequencies = map(list, zip(
         *[(a, f/len(list(activity_distribution.elements()))) for (a, f) in activity_distribution.most_common()]))
     freq_acc = [sum(frequencies[0:i+1]) for i in range(0, len(frequencies))]
     last_filtered_activity = len(freq_acc) - 1
     for i in range(0, len(freq_acc)):
         if freq_acc[i] > threshold:
             last_filtered_activity = i
             break
 
     filtered_activities = activities[:last_filtered_activity+1]
     sublog = ocel.log.log[ocel.log.log["event_activity"].isin(
         filtered_activities)].copy()
-    return log_util.copy_log_from_df(sublog,ocel.parameters)
+    return log_util.copy_log_from_df(sublog, ocel.parameters)
```

## ocpa/algo/util/filtering/log/time_filtering.py

```diff
@@ -1,10 +1,11 @@
 from ocpa.algo.util.filtering.log import case_filtering
 from ocpa.objects.log.util import misc as log_util
 
+
 def start(start, end, exec_start, exec_end):
     '''
     Indicates whether a process execution belongs to a window given window start and end, and process execution start
     and end. A process execution belongs to a window if the start is located in the window.
 
     :param start: Start of the window
     :type start: timestamp
@@ -115,33 +116,33 @@
     :type strategy: func
 
     :return: New sublog
     :rtype: :class:`OCEL <ocpa.objects.log.ocel.OCEL>`
 
     '''
 
-
     if strategy == events:
         return events(ocel, start, end)
     cases = []
-    mapping_time = dict(zip(ocel.log["event_id"], ocel.log["event_timestamp"]))
+    mapping_time = dict(
+        zip(ocel.log.log["event_id"], ocel.log.log["event_timestamp"]))
     #id_index = list(ocel.log.columns.values).index("event_id")
     #id_time = list(ocel.log.columns.values).index("event_timestamp")
     #arr = ocel.log.to_numpy()
     for i in range(0, len(ocel.process_executions)):
         case = ocel.process_executions[i]
         exec_start = min([mapping_time[e] for e in case])
         exec_end = max([mapping_time[e] for e in case])
         if strategy(start, end, exec_start, exec_end):
             cases += [ocel.process_executions[i]]
 
     return case_filtering.filter_process_executions(ocel, cases)
 
 
-def events(ocel, start, end):
+def events(ocel, start=None, end=None):
     '''
     Returns the sub event log for a time window.
 
     :param ocel: Object-centric event log
     :type ocel: :class:`OCEL <ocpa.objects.log.ocel.OCEL>`
 
     :param start: Start of the window
@@ -155,12 +156,21 @@
 
     '''
     events = []
     id_index = list(ocel.log.log.columns.values).index("event_id")
     id_time = list(ocel.log.log.columns.values).index("event_timestamp")
     arr = ocel.log.log.to_numpy()
     for line in arr:
-        if (start <= line[id_time]) & (line[id_time] <= end):
-            events.append(line[id_index])
+        if start != None and end == None:
+            if start <= line[id_time]:
+                events.append(line[id_index])
+        elif start == None and end != None:
+            if line[id_time] <= end:
+                events.append(line[id_index])
+        elif start != None and end != None:
+            if (start <= line[id_time]) & (line[id_time] <= end):
+                events.append(line[id_index])
+        else:
+            raise ValueError('Specify either start or end timestamp')
     new_event_df = ocel.log.log[ocel.log.log['event_id'].isin(events)]
-    new_ocel = log_util.copy_log_from_df(new_event_df,ocel.parameters)
+    new_ocel = log_util.copy_log_from_df(new_event_df, ocel.parameters)
     return new_ocel
```

## ocpa/algo/util/filtering/log/variant_filtering.py

```diff
@@ -32,10 +32,9 @@
     pref_sublog = log_util.remove_object_references(
         ocel.log.log, ocel.object_types, rel_obs)
     sublog = pref_sublog[pref_sublog["event_variant"].apply(
         lambda x: bool(set(x) & set(filtered_variants)))].copy()
     sublog = sublog.drop("event_variant", axis=1)
     sublog = log_util.remove_object_references(
         sublog, ocel.object_types, rel_obs)
-
     new_log = log_util.copy_log_from_df(sublog, ocel.parameters)
     return new_log
```

## ocpa/algo/util/variants/versions/twophase.py

 * *Ordering differences only*

```diff
@@ -88,8 +88,8 @@
         events = set().union(*cases)
         for e in events:
             if e not in variant_event_map.keys():
                 variant_event_map[e] = []
             variant_event_map[e] += [v_id]
     ocel.log.log["event_variant"] = ocel.log.log["event_id"].map(variant_event_map)
     ocel.log.log.drop('event_objects', axis=1, inplace=True)
-    return variants, v_freq_list, variant_graphs, variants_dict
+    return variants, v_freq_list, variant_graphs, variants_dict
```

## ocpa/objects/__init__.py

```diff
@@ -1,3 +1,4 @@
 import ocpa.objects.log
 import ocpa.objects.oc_petri_net
 import ocpa.objects.graph
+import ocpa.objects.aopm
```

## ocpa/objects/graph/__init__.py

```diff
@@ -1,3 +1,4 @@
 import ocpa.objects.graph.constraint_graph
 import ocpa.objects.graph.correlated_event_graph
 import ocpa.objects.graph.event_graph
+import ocpa.objects.graph.extensive_constraint_graph
```

## ocpa/objects/log/converter/factory.py

```diff
@@ -1,12 +1,12 @@
 from ocpa.objects.log.converter.versions import jsonocel_to_csv
 from ocpa.objects.log.converter.versions import df_to_ocel
 
-JSONOCEL_TO_MDL = "json_to_mdl"
+JSONOCEL_TO_CSV = "json_to_csv"
 DF_TO_OCEL = "df_to_ocel"
 
-VERSIONS = {JSONOCEL_TO_MDL: jsonocel_to_csv.apply,
+VERSIONS = {JSONOCEL_TO_CSV: jsonocel_to_csv.apply,
             DF_TO_OCEL: df_to_ocel.apply}
 
 
 def apply(ocel, variant=DF_TO_OCEL, parameters=None):
     return VERSIONS[variant](ocel, parameters=parameters)
```

## ocpa/objects/log/converter/versions/df_to_ocel.py

```diff
@@ -1,76 +1,88 @@
 from typing import Dict, List, Any
 import pandas as pd
 from pandas import to_datetime
 from ocpa.objects.log.variants.obj import Event, Obj, ObjectCentricEventLog, MetaObjectCentricData, RawObjectCentricData
+import time
 
 
 def apply(df: pd.DataFrame) -> ObjectCentricEventLog:
     events = {}
     objects = {}
     acts = set()
+    
+    df.sort_values(by='event_timestamp', inplace=True)
     obj_names = set([x for x in df.columns if not x.startswith("event_")])
     val_names = set([x for x in df.columns if x.startswith(
         "event_")]) - set(['event_activity', 'event_timestamp', 'event_start_timestamp'])
+    obj_event_mapping = {}
+    start = time.time()
     for index, row in df.iterrows():
         add_event(events, index, row, obj_names, val_names)
-        add_obj(objects, [(o, obj) for obj in obj_names for o in row[obj]])
+        add_obj(objects, index, [(o, obj)
+                for obj in obj_names if obj in row for o in row[obj]], obj_event_mapping)
         acts.add(row['event_activity'])
-
+    end = time.time()
     attr_typ = {attr: name_type(str(df.dtypes[attr]))
                 for attr in val_names}
     attr_types = list(set(typ for typ in attr_typ.values()))
     act_attr = {act: val_names for act in acts}
     meta = MetaObjectCentricData(
         attr_names=val_names,
         attr_types=attr_types,
         attr_typ=attr_typ,
         obj_types=obj_names,
         act_attr=act_attr
     )
     raw = RawObjectCentricData(
         events=events,
-        objects=objects
+        objects=objects,
+        obj_event_mapping=obj_event_mapping
     )
     return ObjectCentricEventLog(meta, raw)
 
 
 def add_event(events: Dict[str, Event], index, row, obj_names, val_names) -> None:
+    start = time.time()
     events[str(index)] = Event(
         id=str(index),
         act=row['event_activity'],
         time=to_datetime(row['event_timestamp']),
-        omap=[o for obj in obj_names for o in row[obj]],
+        omap=[o for obj in obj_names if obj in row for o in row[obj]],
         vmap={attr: row[attr] for attr in val_names})
     # add start time if exists, otherwise None for performance analysis
     if "event_start_timestamp" in val_names:
-        events[str(index)].vmap["start_timestamp"] = to_datetime(
-            row['event_start_timestamp'])
+        events[str(index)].vmap["start_timestamp"] = to_datetime(row['event_start_timestamp'])
     else:
-        events[str(index)].vmap["start_timestamp"] = to_datetime(
-            row['event_timestamp'])
-
+        events[str(index)].vmap["start_timestamp"] = to_datetime(row['event_timestamp'])
+    end = time.time()
+    # print(f'Add event: f{end - start}')
 
 def safe_split(row_obj):
     try:
         if '{' in row_obj:
             return [x.strip() for x in row_obj[1:-1].split(',')]
-
         else:
             return row_obj.split(',')
     except TypeError:
         return []  # f'NA-{next(counter)}'
 
-
-def add_obj(objects: Dict[str, Obj], objs: List[str]) -> None:
+def add_obj(objects: Dict[str, Obj], index, objs: List[str], obj_event_mapping: Dict[str, List[str]]) -> None:
+    start = time.time()
     for obj_id_typ in objs:
         obj_id = obj_id_typ[0]  # First entry is the id
         obj_typ = obj_id_typ[1]  # second entry is the object type
         if obj_id not in objects:
             objects[obj_id] = Obj(id=obj_id, type=obj_typ, ovmap={})
-
+        if obj_id in obj_event_mapping:
+            obj_event_mapping[obj_id].append(str(index))
+        else:
+            obj_event_mapping[obj_id] = [str(index)]
+    end = time.time()
+    # print(f'Add object: f{end - start}')
 
 def name_type(typ: str) -> str:
     if typ == 'object':
         return 'string'
     else:
         return typ
+
```

## ocpa/objects/log/importer/csv/util.py

```diff
@@ -1,12 +1,12 @@
 import pandas as pd
 from copy import deepcopy
-from pm4py.util.constants import PARAMETER_CONSTANT_CASEID_KEY, PARAMETER_CONSTANT_ATTRIBUTE_KEY
+from pm4py.util.constants import PARAMETER_CONSTANT_CASEID_KEY, PARAMETER_CONSTANT_ATTRIBUTE_KEY, CASE_CONCEPT_NAME
 from pm4py.algo.discovery.dfg.adapters.pandas import df_statistics
-
+DEFAULT_NAME_KEY = "default name key"
 
 def filter_by_timestamp(df, start_timestamp=None, end_timestamp=None):
     if start_timestamp is not None:
         df = df.loc[df["event_timestamp"] >= start_timestamp]
     if end_timestamp is not None:
         df = df.loc[df["event_timestamp"] <= end_timestamp]
     return df
@@ -42,15 +42,15 @@
                         event[k] = v
                         new_stream.append(event)
 
     return new_stream
 
 
 def succint_mdl_to_exploded_mdl(df):
-    stream = df.to_dict('r')
+    stream = df.to_dict('records')
 
     exploded_stream = succint_stream_to_exploded_stream(stream)
 
     df = pd.DataFrame(exploded_stream)
     df.type = "exploded"
 
     return df
```

## ocpa/objects/log/importer/csv/versions/to_df.py

```diff
@@ -3,44 +3,46 @@
 import math
 
 
 def apply(filepath, parameters=None):
     if parameters is None:
         raise ValueError("Specify parsing parameters")
     df = pd.read_csv(filepath, parameters["sep"])
-    # eve_cols = [x for x in df.columns if x.startswith("event_")]
-    # obj_cols = [x for x in df.columns if not x.startswith("event_")]
     obj_cols = parameters['obj_names']
 
     def _eval(x):
         if x == 'set()':
             return []
         elif type(x) == float and math.isnan(x):
             return []
         else:
             return literal_eval(x)
 
+    df_ocel = pd.DataFrame()
+
     if obj_cols:
         for c in obj_cols:
-            df[c] = df[c].apply(_eval)
+            df_ocel[c] = df[c].apply(_eval)
+
+    # if "event_id" in df.columns:
+    #     df_ocel["event_id"] = df["event_id"].astype(str)
+    # else:
+    df_ocel["event_id"] = [str(i) for i in range(len(df))]
+    df_ocel['event_activity'] = df[parameters['act_name']]
+    df_ocel['event_timestamp'] = pd.to_datetime(df[parameters['time_name']])
+
+    df_ocel.sort_values(by='event_timestamp', inplace=True)
 
-    df['activity'] = df[parameters['act_name']]
-    del df[parameters['act_name']]
-    df['timestamp'] = df[parameters['time_name']]
-    del df[parameters['time_name']]
     if "start_timestamp" in parameters:
-        df['start_timestamp'] = df[parameters['start_timestamp']]
-        del df[parameters['start_timestamp']]
+        df_ocel['event_start_timestamp'] = pd.to_datetime(
+            df[parameters['start_timestamp']])
     else:
-        df['start_timestamp'] = df['timestamp']
+        df_ocel['event_start_timestamp'] = pd.to_datetime(
+            df[parameters['time_name']])
+
+    for val_name in parameters['val_names']:
+        df_ocel[('event_' + val_name)] = df[parameters[val_name]]
 
-    rename_dict = {}
-    for col in [x for x in df.columns if not x.startswith("event_")]:
-        if col not in obj_cols:
-            rename_dict[col] = 'event_' + col
-    df.rename(columns=rename_dict, inplace=True)
-
-    df['event_timestamp'] = pd.to_datetime(df['event_timestamp'])
-    df = df.dropna(subset=["event_id"])
-    df["event_id"] = df["event_id"].astype(str)
-    #df.type = "succint"
-    return df
+    if 'obj_val_names' in parameters:
+        for obj_val_name in parameters['val_names']:
+            df_ocel[obj_val_name] = df[parameters[obj_val_name]]
+    return df_ocel
```

## ocpa/objects/log/importer/csv/versions/to_obj.py

```diff
@@ -17,54 +17,44 @@
             [row[obj]
              for obj in cfg["obj_names"] if (row[obj] != '{}' and row[obj] != [] and row[obj] != '[]' and row[obj] != '' and str(row[obj]).lower() != "nan")]
         )),
         vmap={attr: row[attr] for attr in cfg["val_names"]})
 
     # add start time if exists, otherwise None for performance analysis
     if "start_timestamp" in cfg:
-        events[str(index)].vmap["start_timestamp"] = to_datetime(
-            row[cfg["start_timestamp"]])
+        events[str(index)].vmap["start_timestamp"] = to_datetime(row[cfg["start_timestamp"]])
     else:
-        events[str(index)].vmap["start_timestamp"] = to_datetime(
-            row[cfg["time_name"]])
+        events[str(index)].vmap["start_timestamp"] = to_datetime(row[cfg["time_name"]])
 
-
-def safe_split(row_obj):
-    try:
-        if '{' in row_obj or '[' in row_obj:
-            return [x.strip() for x in row_obj[1:-1].split(',')]
-        else:
-            return row_obj.split(',')
-    except TypeError:
-        return []  # f'NA-{next(counter)}'
-
-
-def add_obj(objects: Dict[str, Obj], objs: List[str]) -> None:
+def add_obj(objects: Dict[str, Obj], index, objs: List[str], obj_event_mapping: Dict[str, List[str]]) -> None:
     for obj_id_typ in objs:
         obj_id_typ = obj_id_typ.split('/')  # Unpack
         obj_id = obj_id_typ[0]  # First entry is the id
         obj_typ = obj_id_typ[1]  # second entry is the object type
         if obj_id not in objects:
             objects[obj_id] = Obj(id=obj_id, type=obj_typ, ovmap={})
-
+        if obj_id in obj_event_mapping:
+            obj_event_mapping[obj_id].append(str(index))
+        else:
+            obj_event_mapping[obj_id] = [str(index)]
 
 def apply(df: pd.DataFrame, parameters: Dict) -> ObjectCentricEventLog:
     if parameters is None:
         raise ValueError("Specify parsing parameters")
     events = {}
     objects = {}
     acts = set()
+    obj_event_mapping = {}
     for index, row in df.iterrows():
         add_event(events, index, row, parameters)
-        add_obj(objects,
-                # Only nonempty sets of objects ids per object type
+        add_obj(objects, index,
                 list(itertools.chain.from_iterable(
                     [[obj_id + '/' + str(obj) for i, obj_id in enumerate(row[obj])]
                      for obj in parameters["obj_names"] if row[obj] != '{}' and row[obj] != [] and row[obj] != '[]' and row[obj] != '' and str(row[obj]).lower() != "nan"]
-                ))
+                )), obj_event_mapping
                 )
         acts.add(row[parameters["act_name"]])
 
     events = OrderedDict(sorted(events.items(), key=lambda kv: kv[1].time))
 
     attr_typ = {attr: name_type(str(df.dtypes[attr]))
                 for attr in parameters["val_names"]}
@@ -75,17 +65,17 @@
         attr_types=attr_types,
         attr_typ=attr_typ,
         obj_types=parameters["obj_names"],
         act_attr=act_attr
     )
     raw = RawObjectCentricData(
         events=events,
-        objects=objects
+        objects=objects,
+        obj_event_mapping=obj_event_mapping
     )
     return ObjectCentricEventLog(meta, raw)
 
-
 def name_type(typ: str) -> str:
     if typ == 'object':
         return 'string'
     else:
         return typ
```

## ocpa/objects/log/importer/csv/versions/to_ocel.py

```diff
@@ -10,11 +10,14 @@
 
 def apply(filepath, parameters: Dict, file_path_object_attribute_table=None) -> OCEL:
     df = df_importer.apply(filepath, parameters)
     obj_df = None
     if file_path_object_attribute_table:
         obj_df = pd.read_csv(file_path_object_attribute_table)
     log = Table(df, parameters=parameters, object_attributes=obj_df)
+    print("Table Format Successfully Imported")
     obj = obj_converter.apply(df)
+    print("Object Format Successfully Imported")
     graph = EventGraph(table_utils.eog_from_log(log))
+    print("Graph Format Successfully Imported")
     ocel = OCEL(log, obj, graph, parameters)
     return ocel
```

## ocpa/objects/log/importer/ocel/versions/import_ocel_json.py

```diff
@@ -13,48 +13,47 @@
 from ocpa.objects.log.variants.graph import EventGraph
 import ocpa.objects.log.variants.util.table as table_utils
 
 
 def apply(filepath, parameters: Dict, file_path_object_attribute_table=None) -> OCEL:
     if parameters is None:
         parameters = {}
-    obj = import_jsonocel(filepath, parameters)
-    df, _ = convert_factory.apply(obj, variant='json_to_mdl')
+    obj = import_jsonocel(filepath)
+    df, _ = convert_factory.apply(obj, variant='json_to_csv')
     obj_df = None
     if(file_path_object_attribute_table):
         obj_df = pd.read_csv(file_path_object_attribute_table)
     table_parameters = {"obj_names": obj.meta.obj_types,
                         # TODO check this in a future release
                         # "val_names": obj.meta.attr_types,
-                        "val_names": [],
+                        "val_names": ['event_'.join(name) for name in obj.meta.attr_events],
                         "act_name": "event_activity",
                         "time_name": "event_timestamp",
                         "sep": ","}
     table_parameters.update(parameters)
     # TODO see here
     # print(table_parameters)
     log = Table(df, parameters=table_parameters, object_attributes=obj_df)
     graph = EventGraph(table_utils.eog_from_log(log))
     ocel = OCEL(log, obj, graph, table_parameters)
     return ocel
 
 
 def import_jsonocel(file_path, parameters=None) -> ObjectCentricEventLog:
-    if parameters is None:
-        parameters = {}
     F = open(file_path, "rb")
     obj = json.load(F)
     F.close()
     return parse_json(obj)
 
 
 def parse_json(data: Dict[str, Any]) -> ObjectCentricEventLog:
     cfg = JsonParseParameters()
     # parses the given dict
-    events = parse_events(data[cfg.log_params['events']], cfg)
+    events, obj_event_mapping = parse_events(
+        data[cfg.log_params['events']], cfg)
     objects = parse_objects(data[cfg.log_params['objects']], cfg)
     # Uses the last found value type
     attr_events = {v:
                    str(type(events[eid].vmap[v])) for eid in events
                    for v in events[eid].vmap}
     attr_objects = {v:
                     str(type(objects[oid].ovmap[v])) for oid in objects
@@ -76,39 +75,49 @@
                                  obj_types=data[cfg.log_params['meta']
                                                 ][cfg.log_params['obj_types']],
                                  attr_types=attr_types,
                                  attr_typ=attr_typ,
                                  act_attr=act_attr,
                                  attr_events=list(attr_events.keys()))
     data = ObjectCentricEventLog(
-        meta, RawObjectCentricData(events, objects))
+        meta, RawObjectCentricData(events, objects, obj_event_mapping))
     return data
 
 
 def parse_events(data: Dict[str, Any], cfg: JsonParseParameters) -> Dict[str, Event]:
     # Transform events dict to list of events
     act_name = cfg.event_params['act']
     omap_name = cfg.event_params['omap']
     vmap_name = cfg.event_params['vmap']
     time_name = cfg.event_params['time']
     events = {}
+    obj_event_mapping = {}
+    eid = 0
     for item in data.items():
-        events[item[0]] = Event(id=item[0],
-                                act=item[1][act_name],
-                                omap=item[1][omap_name],
-                                vmap=item[1][vmap_name],
-                                time=datetime.fromisoformat(item[1][time_name]))
+        events[eid] = Event(id=eid,
+                            act=item[1][act_name],
+                            omap=item[1][omap_name],
+                            vmap=item[1][vmap_name],
+                            time=datetime.fromisoformat(item[1][time_name]))
         if "start_timestamp" not in item[1][vmap_name]:
-            events[item[0]].vmap["start_timestamp"] = datetime.fromisoformat(
+            events[eid].vmap["start_timestamp"] = datetime.fromisoformat(
                 item[1][time_name])
         else:
-            events[item[0]].vmap["start_timestamp"] = datetime.fromisoformat(
-                events[item[0]].vmap["start_timestamp"])
+            events[eid].vmap["start_timestamp"] = datetime.fromisoformat(
+                events[eid].vmap["start_timestamp"])
+
+        for oid in item[1][omap_name]:
+            if oid in obj_event_mapping:
+                obj_event_mapping[oid].append(eid)
+            else:
+                obj_event_mapping[oid] = [eid]
+        eid += 1
+
     sorted_events = sorted(events.items(), key=lambda kv: kv[1].time)
-    return OrderedDict(sorted_events)
+    return OrderedDict(sorted_events), obj_event_mapping
 
 
 def parse_objects(data: Dict[str, Any], cfg: JsonParseParameters) -> Dict[str, Obj]:
     # Transform objects dict to list of objects
     type_name = cfg.obj_params['type']
     ovmap_name = cfg.obj_params['ovmap']
     objects = {item[0]: Obj(id=item[0],
```

## ocpa/objects/log/variants/graph.py

 * *Ordering differences only*

```diff
@@ -1,7 +1,7 @@
 from dataclasses import dataclass
 import networkx as nx
 
+
 @dataclass
 class EventGraph:
     eog: nx.DiGraph
-
```

## ocpa/objects/log/variants/obj.py

```diff
@@ -1,10 +1,11 @@
 from dataclasses import dataclass, field
 from typing import List, Dict, Set, Any
 from datetime import datetime
+import time
 
 
 @dataclass
 class Event:
     id: str
     act: str
     time: datetime
@@ -48,106 +49,247 @@
     #     self.acts = {act for act in self.act_attr}
 
 
 @dataclass
 class RawObjectCentricData:
     events: Dict[str, Event]
     objects: Dict[str, Obj]
+    obj_event_mapping: Dict[str, List[str]]
 
     @property
     def obj_ids(self) -> List[str]:
         return list(self.objects.keys())
 
 
 @dataclass
 class ObjectCentricEventLog:
     meta: MetaObjectCentricData
     raw: RawObjectCentricData
 
     def __post_init__(self):
-        self.meta.locs = {}
 
-    @property
-    def activities(self) -> Set[str]:
-        return set([self.raw.events[e].act for e in self.raw.events])
-
-    def act_events(self, act: str) -> List[str]:
-        return [e for e in self.raw.events if self.raw.events[e].act == act]
-
-    @property
-    def types(self) -> Set[str]:
-        return set(self.meta.obj_types)
-
-    def ot_objects(self, ot: str) -> List[str]:
-        return [oid for oid in self.raw.objects if self.raw.objects[oid].type == ot]
-
-    def obj_events(self, oid: str) -> List[str]:
-        return [e for e in self.raw.events if oid in self.raw.events[e].omap]
-
-    def eve_objects(self, eid: str) -> List[str]:
-        return self.raw.events[eid].omap
+        self.types = set(self.meta.obj_types)
+        self.activities = set(
+            [self.raw.events[e].act for e in self.raw.events])
+        self.act_events = {}
+        for act in self.activities:
+            self.act_events[act] = [
+                e for e in self.raw.events if self.raw.events[e].act == act]
+
+        self.ot_objects = {}
+        for ot in self.meta.obj_types:
+            O = [oid for oid in self.raw.objects if self.raw.objects[oid].type == ot]
+            self.ot_objects[ot] = O
+
+        self.eve_objects = {}
+        for eid in self.raw.events:
+            self.eve_objects[eid] = self.raw.events[eid].omap
+
+        self.sequence = {}
+        self.trace = {}
+        for oid in self.raw.objects:
+            if oid in self.raw.obj_event_mapping:
+                events = [self.raw.events[e]
+                          for e in self.raw.obj_event_mapping[oid]]
+            else:
+                events = []
+            events.sort(key=lambda x: x.time)
+            self.sequence[oid] = events
+            self.trace[oid] = [e.act for e in self.sequence[oid]]
+
+    # @property
+    # def activities(self) -> Set[str]:
+    #     return set([self.raw.events[e].act for e in self.raw.events])
+
+    # def act_events(self, act: str) -> List[str]:
+    #     return [e for e in self.raw.events if self.raw.events[e].act == act]
+
+    # @property
+    # def types(self) -> Set[str]:
+    #     return set(self.meta.obj_types)
+
+    # def ot_objects(self, ot: str) -> List[str]:
+    #     start = time.time()
+    #     O = [oid for oid in self.raw.objects if self.raw.objects[oid].type == ot]
+    #     end = time.time()
+    #     print(f"Computing ot-objects took {end-start}")
+    #     return O
+
+    # replaced by obj_event_mapping of ocel
+    # def obj_events(self, oid: str) -> List[str]:
+    #     return [e for e in self.raw.events if oid in self.raw.events[e].omap]
+
+    # def eve_objects(self, eid: str) -> List[str]:
+    #     return self.raw.events[eid].omap
+
+    def eve_ot_objects(self, eid: str, ot: str) -> List[str]:
+        return [oid for oid in self.eve_objects[eid] if self.raw.objects[oid].type == ot]
+
+    # def sequence(self, oid: str) -> List[Event]:
+    #     events = [self.raw.events[e] for e in self.raw.obj_event_mapping[oid]]
+    #     events.sort(key=lambda x: x.time)
+    #     return events
+
+    # def trace(self, oid: str) -> List[str]:
+    #     trace = [e.act for e in self.sequence(oid)]
+    #     return trace
+
+    # def ot_events(self, ot: str) -> List[str]:
+    #     events = []
+    #     for e in self.raw.events:
+    #         if any(ot == self.raw.objects[oid].type for oid in self.raw.events[e].omap):
+    #             events.append(e)
+    #     return events
+
+    def existence(self, ot: str, act: str):
+        return [o for o in self.ot_objects[ot] if act in self.trace[o]]
+
+    def non_existence(self, ot: str, act: str):
+        return [o for o in self.ot_objects[ot] if act not in self.trace[o]]
+
+    def non_existence_metric(self, ot: str, act: str):
+        return self.calculate_metric(len(self.non_existence(ot, act)), len(self.ot_objects[ot]))
+
+    def coexistence(self, ot: str, act1: str, act2: str):
+        return [o for o in self.ot_objects[ot] if (act1 not in self.trace[o] and act2 not in self.trace[o]) or (act1 in self.trace[o] and act2 in self.trace[o])]
+
+    def coexistence_metric(self, ot: str, act1: str, act2: str):
+        return self.calculate_metric(len(self.coexistence(ot, act1, act2)), len(self.ot_objects[ot]))
+
+    def exclusiveness(self, ot: str, act1: str, act2: str):
+        return [o for o in self.ot_objects[ot]
+                if ~(set([act1, act2]) <= set(self.trace[o]))]
+
+    def choice(self, ot: str, act1: str, act2: str):
+        return [o for o in self.ot_objects[ot]
+                if act1 in self.trace[o] or act2 in self.trace[o]]
+
+    def xor_choice(self, ot: str, act1: str, act2: str):
+        return [o for o in self.ot_objects[ot] if (act1 in self.trace[o] or act2 in self.trace[o]) and ~(
+            set([act1, act2]) <= set(self.trace[o]))]
+
+    def followed_by(self, ot: str, act1: str, act2: str):
+        O = []
+        for oid in self.ot_objects[ot]:
+            trace = self.trace[oid]
+            if act1 not in trace:
+                O.append(oid)
+            elif act1 in trace and act2 in trace:
+                act1_idx = trace.index(act1)
+                act2_idx = trace.index(act2)
+                if act1_idx < act2_idx:
+                    O.append(oid)
+        return O
 
-    def sequence(self, oid: str) -> List[Event]:
-        events = [self.raw.events[e] for e in self.obj_events(oid)]
-        events.sort(key=lambda x: x.time)
-        return events
+    def directly_followed_by(self, ot: str, act1: str, act2: str):
+        O = []
+        for oid in self.ot_objects[ot]:
+            trace = self.trace[oid]
+            if act1 not in trace:
+                O.append(oid)
+            elif act1 in trace and act2 in trace:
+                act1_idx = trace.index(act1)
+                act2_idx = trace.index(act2)
+                if act1_idx+1 == act2_idx:
+                    O.append(oid)
+        return O
+
+    def precedence(self, ot: str, act1: str, act2: str):
+        O = []
+        for oid in self.ot_objects[ot]:
+            trace = self.trace[oid]
+            if act2 not in trace:
+                O.append(oid)
+            elif act1 in trace and act2 in trace:
+                act1_idx = trace.index(act1)
+                act2_idx = trace.index(act2)
+                if act1_idx < act2_idx:
+                    O.append(oid)
+        return O
 
-    def trace(self, oid: str) -> List[str]:
-        trace = [e.act for e in self.sequence(oid)]
-        return trace
 
-    def ot_events(self, ot: str) -> List[str]:
-        events = []
-        for e in self.raw.events:
-            if any(ot == self.raw.objects[oid].type for oid in self.raw.events[e].omap):
-                events.append(e)
-        return events
+    def block(self, ot: str, act1: str, act2: str):
+        O = []
+        for oid in self.ot_objects[ot]:
+            trace = self.trace[oid]
+            if act1 not in trace:
+                O.append(oid)
+            else:
+                act1_idx = trace.index(act1)
+                if act2 not in trace:
+                    O.append(oid)
+                else:
+                    act2_idx = trace.index(act2)
+                    if act1_idx > act2_idx:
+                        O.append(oid)
+        return O
+
+    def object_absence(self, ot: str, act: str) -> List[str]:
+        O = []
+        for eid in self.act_events[act]:
+            if len([oid for oid in self.eve_objects[eid] if self.raw.objects[oid].type == ot]) == 0:
+                O.append(eid)
+        return O
+
+    def object_singular(self, ot: str, act: str) -> List[str]:
+        O = []
+        for eid in self.act_events[act]:
+            if len([oid for oid in self.eve_objects[eid] if self.raw.objects[oid].type == ot]) == 1:
+                O.append(eid)
+        return O
+
+    def object_multiple(self, ot: str, act: str) -> List[str]:
+        O = []
+        for eid in self.act_events[act]:
+            if len([oid for oid in self.eve_objects[eid] if self.raw.objects[oid].type == ot]) > 1:
+                O.append(eid)
+        return O
 
     def ot_objects_of_an_event(self, eid: str, ot: str) -> List[str]:
         return [oid for oid in self.raw.events[eid].omap if self.raw.objects[oid].type == ot]
 
     def num_ot_objects_containing_acts(self, ot: str, acts: List[str]) -> int:
         objects = []
-        for oid in self.ot_objects(ot):
-            trace = self.trace(oid)
+        for oid in self.ot_objects[ot]:
+            trace = self.trace[oid]
             if all(act in trace for act in acts):
                 objects.append(oid)
         return len(objects)
 
-        # return len([oid for oid in self.raw.objects if self.raw.objects[oid].type == ot and act in self.trace(oid)])
+        # return len([oid for oid in self.raw.objects if self.raw.objects[oid].type == ot and act in self.trace[oid]])
 
     def num_ot_objects_containing_act1_followed_by_act2(self, ot: str, act1: str, act2: str) -> int:
         objects = []
-        for oid in self.ot_objects(ot):
-            trace = self.trace(oid)
+        for oid in self.ot_objects[ot]:
+            trace = self.trace[oid]
             if act1 in trace and act2 in trace:
                 act1_idx = trace.index(act1)
                 act2_idx = trace.index(act2)
                 if act1_idx < act2_idx:
                     objects.append(oid)
         return len(objects)
 
     def num_events_relating_one_ot(self, ot: str, act: str) -> int:
         events = []
-        for eid in self.act_events(act):
-            if len([oid for oid in self.eve_objects(eid) if self.raw.objects[oid].type == ot]) == 1:
+        for eid in self.act_events[act]:
+            if len([oid for oid in self.eve_objects[eid] if self.raw.objects[oid].type == ot]) == 1:
                 events.append(eid)
         return len(events)
 
     def num_events_relating_no_ot(self, ot: str, act: str) -> int:
         events = []
-        for eid in self.act_events(act):
-            if len([oid for oid in self.eve_objects(eid) if self.raw.objects[oid].type == ot]) == 0:
+        for eid in self.act_events[act]:
+            if len([oid for oid in self.eve_objects[eid] if self.raw.objects[oid].type == ot]) == 0:
                 events.append(eid)
         return len(events)
 
     def num_events_relating_multiple_ot(self, ot: str, act: str) -> int:
         events = []
-        for eid in self.act_events(act):
-            if len([oid for oid in self.eve_objects(eid) if self.raw.objects[oid].type == ot]) > 1:
+        for eid in self.act_events[act]:
+            if len([oid for oid in self.eve_objects[eid] if self.raw.objects[oid].type == ot]) > 1:
                 events.append(eid)
         return len(events)
 
     def causal_relation(self, ot: str, act1: str, act2: str):
         num_acts = self.num_ot_objects_containing_acts(ot, [act1, act2])
         if num_acts > 0:
             return self.num_ot_objects_containing_act1_followed_by_act2(ot, act1, act2)/num_acts
@@ -178,20 +320,26 @@
             num_act1_and_act2 = self.num_ot_objects_containing_acts(
                 ot, [act1, act2])
             return 1 - (num_act1_and_act2+num_act1_and_act2)/sum_num
         else:
             return 0
 
     def absent_involvement(self, ot: str, act: str):
-        if len(self.act_events(act)) == 0:
+        if len(self.act_events[act]) == 0:
             return 0
-        return self.num_events_relating_no_ot(ot, act)/len(self.act_events(act))
+        return self.num_events_relating_no_ot(ot, act)/len(self.act_events[act])
 
     def singular_involvement(self, ot: str, act: str):
-        if len(self.act_events(act)) == 0:
+        if len(self.act_events[act]) == 0:
             return 0
-        return self.num_events_relating_one_ot(ot, act)/len(self.act_events(act))
+        return self.num_events_relating_one_ot(ot, act)/len(self.act_events[act])
 
     def multiple_involvement(self, ot: str, act: str):
-        if len(self.act_events(act)) == 0:
+        if len(self.act_events[act]) == 0:
+            return 0
+        return self.num_events_relating_multiple_ot(ot, act)/len(self.act_events[act])
+
+    def calculate_metric(self, quantity: int, total: int):
+        if total > 0:
+            return quantity/total
+        else:
             return 0
-        return self.num_events_relating_multiple_ot(ot, act)/len(self.act_events(act))
```

## ocpa/objects/log/variants/table.py

```diff
@@ -6,18 +6,17 @@
 import pandas as pd
 from typing import Dict
 
 
 @dataclass
 class Table:
     def __init__(self, log, parameters, object_attributes=None):
-        self._log = log
-        self._log["event_id"] = self._log["event_id"].astype(int)
-        self._log["event_index"] = self._log["event_id"]
-        self._log = self._log.set_index("event_index")
+        self._log = log.copy()
+        self._log.set_index("event_id", inplace=True)
+        self._log['event_id'] = self._log.index
         self._object_types = parameters["obj_names"]
         self._object_attributes = object_attributes
         #self._event_mapping =  dict(zip(ocel["event_id"], ocel["event_objects"]))
         # clean empty events
         # self.clean_empty_events()
         self.create_efficiency_objects()
         #self._log = self._log[self._log.apply(lambda x: any([len(x[ot]) > 0 for ot in self._object_types]))]
```

## ocpa/objects/oc_petri_net/obj.py

```diff
@@ -1,9 +1,17 @@
+from copy import deepcopy
 from dataclasses import dataclass, field
 from typing import List, Dict, Set, Tuple, Any
+import time
+from copy import deepcopy
+from pm4py.objects.petri_net.obj import PetriNet
+from pm4py.objects.petri_net.utils.networkx_graph import create_networkx_directed_graph_ret_dict_both_ways
+from pm4py.objects.petri_net.utils.projection import project_net_on_matrix
+import networkx as nx
+from collections import Counter
 
 
 class ObjectCentricPetriNet(object):
     '''
     Storing an Object-Centric Petri Net.
 
 
@@ -69,15 +77,15 @@
             # keep the ID for now in places
             return id(self)
 
         def __deepcopy__(self, memodict={}):
             if id(self) in memodict:
                 return memodict[id(self)]
             new_place = ObjectCentricPetriNet.Place(
-                self.name, properties=self.properties)
+                self.name, self.object_type)
             memodict[id(self)] = new_place
             for arc in self.in_arcs:
                 new_arc = deepcopy(arc, memo=memodict)
                 new_place.in_arcs.add(new_arc)
             for arc in self.out_arcs:
                 new_arc = deepcopy(arc, memo=memodict)
                 new_place.out_arcs.add(new_arc)
@@ -86,14 +94,24 @@
         object_type = property(__get_object_type)
         initial = property(__get_initial)
         final = property(__get_final, __set_final)
         out_arcs = property(__get_out_arcs, __set_out_arcs)
         in_arcs = property(__get_in_arcs, __set_in_arcs)
         name = property(__get_name, __set_name)
 
+        def to_dict(self):
+            return {
+                "name": self.name,
+                "object_type": self.object_type,
+                "initial": self.initial,
+                "final": self.final,
+                "in_arcs": [arc.to_dict() for arc in self.__in_arcs],
+                "out_arcs": [arc.to_dict() for arc in self.__out_arcs],
+            }
+
     class Transition(object):
         def __init__(self, name, label=None, in_arcs=None, out_arcs=None, properties=None, silent=False):
             self.__name = name
             self.__label = None if label is None else label
             self.__in_arcs = set() if in_arcs is None else in_arcs
             self.__out_arcs = set() if out_arcs is None else out_arcs
             self.__silent = silent
@@ -110,17 +128,23 @@
 
         def __get_label(self):
             return self.__label
 
         def __get_out_arcs(self):
             return self.__out_arcs
 
+        def __set_out_arcs(self, out_arcs):
+            self.__out_arcs = out_arcs
+
         def __get_in_arcs(self):
             return self.__in_arcs
 
+        def __set_in_arcs(self, in_arcs):
+            self.__in_arcs = in_arcs
+
         def __set_properties(self, properties):
             self.__properties = properties
 
         def __get_properties(self):
             return self.__properties
 
         def __get_silent(self):
@@ -169,18 +193,28 @@
                 new_arc = deepcopy(arc, memo=memodict)
                 new_trans.in_arcs.add(new_arc)
             for arc in self.out_arcs:
                 new_arc = deepcopy(arc, memo=memodict)
                 new_trans.out_arcs.add(new_arc)
             return new_trans
 
+        def to_dict(self):
+            return {
+                "name": self.name,
+                "label": self.label,
+                "in_arcs": [arc.to_dict() for arc in self.__in_arcs],
+                "out_arcs": [arc.to_dict() for arc in self.__out_arcs],
+                "properties": self.__properties,
+                "silent": self.__silent,
+            }
+
         name = property(__get_name, __set_name)
         label = property(__get_label, __set_label)
-        in_arcs = property(__get_in_arcs)
-        out_arcs = property(__get_out_arcs)
+        in_arcs = property(__get_in_arcs, __set_in_arcs)
+        out_arcs = property(__get_out_arcs, __set_out_arcs)
         properties = property(__get_properties, __set_properties)
         silent = property(__get_silent, __set_silent)
 
     class Arc(object):
         def __init__(self, source, target, variable=False, weight=1, properties=None):
             if type(source) is type(target):
                 raise Exception('Petri nets are bipartite graphs!')
@@ -244,27 +278,39 @@
                                                                                                 memo=memodict)
             memodict[id(self.source)] = new_source
             memodict[id(self.target)] = new_target
             new_arc = ObjectCentricPetriNet.Arc(
                 new_source, new_target, weight=self.weight, properties=self.properties)
             memodict[id(self)] = new_arc
             return new_arc
+        
+        def to_dict(self):
+            return {
+                "source": self.source.name,
+                "target": self.target.name,
+                "weight": self.weight,
+                "variable": self.variable,
+                "properties": self.__properties,
+            }
 
         source = property(__get_source, __set_source)
         target = property(__get_target, __set_target)
         variable = property(__get_variable)
         weight = property(__get_weight, __set_weight)
         properties = property(__get_properties, __set_properties)
 
-    def __init__(self, name=None, places=None, transitions=None, arcs=None, properties=None, nets=None):
+    def __init__(self, name=None, places=None, transitions=None, arcs=None, properties=None, nets=None, place_mapping=None, transition_mapping=None, arc_mapping=None):
         self.__name = "" if name is None else name
         self.__places = places if places != None else set()
         self.__transitions = transitions if transitions != None else set()
         self.__arcs = arcs if arcs != None else set()
         self.__properties = dict() if properties is None else properties
+        self.__place_mapping = place_mapping if place_mapping is not None else dict()
+        self.__transition_mapping = transition_mapping if transition_mapping is not None else dict()
+        self.__arc_mapping = arc_mapping if arc_mapping is not None else dict()
         self.__nets = nets if nets is not None else dict()
 
     @property
     def name(self):
         return self.__name
 
     @name.setter
@@ -315,14 +361,26 @@
     def object_types(self):
         return list(set([pl.object_type for pl in self.__places]))
 
     @property
     def nets(self):
         return self.__nets
 
+    @property
+    def place_mapping(self):
+        return self.__place_mapping
+
+    @property
+    def transition_mapping(self):
+        return self.__transition_mapping
+
+    @property
+    def arc_mapping(self):
+        return self.__arc_mapping
+
     def add_arc(self, arc):
         '''
         Adds an arc to the object-centric Petri net.
         Parameters
         ----------
         arc: Arc
 
@@ -436,90 +494,212 @@
         Arc or None
         '''
         for arc in self.__arcs:
             if arc.source == source and arc.target == target:
                 return arc
         return None
 
-    def find_transition(self, name):
+    def find_transition(self, label):
         '''
-        finds a transition by name of the transition.
+        finds a transition by the label of the transition.
         Parameters
         ----------
         name: string
 
         Returns
         -------
         None
         '''
         for transition in self.__transitions:
-            if transition.name == name:
+            if transition.label == label:
                 return transition
         return None
 
+    def find_place(self, name):
+        '''
+        finds a transition by name of the transition.
+        Parameters
+        ----------
+        name: string
+
+        Returns
+        -------
+        None
+        '''
+        for place in self.__places:
+            if place.name == name:
+                return place
+        return None
+
+    def ancestor_transitions(self, t, ot):
+        ancestors = set()
+        net, im, fm = self.nets[ot]
+        graph, dictionary, inv_dictionary = create_networkx_directed_graph_ret_dict_both_ways(
+            net)
+        for tr in net.transitions:
+            if tr.label == t.label:
+                connected_nodes = nx.ancestors(graph, dictionary[tr])
+                for node in [node for node in connected_nodes if type(inv_dictionary[node]) == PetriNet.Transition]:
+                    connected_transition = self.transition_mapping[inv_dictionary[node]]
+                    ancestors.add(connected_transition)
+        return ancestors
+
+    def ancestor_places(self, t, ot):
+        ancestors = set()
+        net, im, fm = self.nets[ot]
+        graph, dictionary, inv_dictionary = create_networkx_directed_graph_ret_dict_both_ways(
+            net)
+        for tr in net.transitions:
+            if tr.label == t.label:
+                connected_nodes = nx.ancestors(graph, dictionary[tr])
+                for node in [node for node in connected_nodes if type(inv_dictionary[node]) == PetriNet.Place]:
+                    connected_place = self.place_mapping[
+                        inv_dictionary[node]]
+                    if connected_place is not None:
+                        ancestors.add(connected_place)
+        return ancestors
+
+    def descendant_transitions(self, t, ot):
+        descendants = set()
+        net, im, fm = self.nets[ot]
+        graph, dictionary, inv_dictionary = create_networkx_directed_graph_ret_dict_both_ways(
+            net)
+        for tr in net.transitions:
+            if tr.label == t.label:
+                connected_nodes = nx.descendants(graph, dictionary[tr])
+                for node in [node for node in connected_nodes if type(inv_dictionary[node]) == PetriNet.Transition]:
+                    connected_transition = self.transition_mapping[inv_dictionary[node]]
+                    descendants.add(connected_transition)
+        return descendants
+
+    def descendant_places(self, t, ot):
+        descendants = set()
+        net, im, fm = self.nets[ot]
+        graph, dictionary, inv_dictionary = create_networkx_directed_graph_ret_dict_both_ways(
+            net)
+        for tr in net.transitions:
+            if tr.label == t.label:
+                connected_nodes = nx.descendants(graph, dictionary[tr])
+                for node in [node for node in connected_nodes if type(inv_dictionary[node]) == PetriNet.Place]:
+                    connected_place = self.place_mapping[
+                        inv_dictionary[node]]
+                    if connected_place is not None:
+                        descendants.add(connected_place)
+        return descendants
+
+    def subnet(self, source_t, target_t, ot):
+        net, im, fm = self.nets[ot]
+        return project_net_on_matrix(net, [
+            source_t, target_t])
+    
+    def to_dict(self):
+        places_dicts = []
+        for place in self.__places:
+            print(place)
+            places_dicts.append(place.to_dict())
 
-@dataclass
-class Marking(object):
+        transitions_dicts = []
+        for transition in self.__transitions:
+            transitions_dicts.append(transition.to_dict())
+
+        arcs_dicts = []
+        for arc in self.__arcs:
+            arcs_dicts.append(arc.to_dict())
+
+        return {
+            "name": self.__name,
+            "places": places_dicts,
+            "transitions": transitions_dicts,
+            "arcs": arcs_dicts,
+            "properties": self.__properties,
+            "nets": self.__nets,
+            "place_mapping": self.__place_mapping,
+            "transition_mapping": self.__transition_mapping,
+            "arc_mapping": self.__arc_mapping,
+        }
+
+
+@ dataclass
+class Marking(Counter):
     '''
     Representing a Marking of an Object-Centric Petri Net.
 
     ...
 
     Attributes
-    tokens: set(Tuple)
 
     Methods
     -------
-    add_token(pl, obj):
-        adds an object obj to a place pl
     '''
-    _tokens: Set[Tuple[ObjectCentricPetriNet.Place, str]
-                 ] = field(default_factory=set)
 
-    @property
-    def tokens(self) -> Set[Tuple[ObjectCentricPetriNet.Place, str]]:
-        return self._tokens
+    def __hash__(self):
+        r = 0
+        for token in self.items():
+            r += 31 * hash(token[0]) * token[1]
+        return r
+
+    def __eq__(self, other):
+        if not self.keys() == other.keys():
+            return False
+        for token in self.keys():
+            if other.get(token) != self.get(token):
+                return False
+        return True
+
+    def __le__(self, other):
+        if not self.keys() <= other.keys():
+            return False
+        for token in self.keys():
+            if sum(other.get(token)) < sum(self.get(token)):
+                return False
+        return True
+
+    def __add__(self, other):
+        m = Marking()
+        for token in self.items():
+            m[token[0]] = token[1]
+        for token in other.items():
+            m[token[0]] += token[1]
+        return m
+
+    def __sub__(self, other):
+        m = Marking()
+        for token in self.items():
+            m[token[0]] = token[1]
+        for token in other.items():
+            m[token[0]] -= token[1]
+            if m[token[0]] == 0:
+                del m[token[0]]
+        return m
+
+    def __repr__(self):
+        # return str([str(p.name) + ":" + str(self.get(p)) for p in self.keys()])
+        # The previous representation had a bug, it took into account the order of the places with tokens
+        return str([f'({str(token[0].name)},{str(token[1])}):' + str(self.get(token)) for token in sorted(list(self.keys()), key=lambda x: x[0].name)])
 
-    def add_token(self, pl, obj):
-        '''
-        Add a token to a place in a marking.
-        Parameters
-        ----------
-        pl: Place
-        obj: string
-
-        Returns
-        -------
-        None
 
-        '''
-        temp_tokens = set([(pl, oi) for (pl, oi) in self._tokens if oi == obj])
-        self._tokens -= temp_tokens
-        self._tokens.add((pl, obj))
-
-
-@dataclass
+@ dataclass
 class Subprocess(object):
     _ocpn: ObjectCentricPetriNet
     _object_types: Set[str] = field(default_factory=set)
     _activities: Set[str] = field(
         default_factory=set)
     _transitions: Set[ObjectCentricPetriNet.Transition] = field(
         default_factory=set)
     _sound: Any = False
 
-    @property
+    @ property
     def object_types(self) -> Set[str]:
         return self._object_types
 
-    @property
+    @ property
     def transitions(self) -> Set[ObjectCentricPetriNet.Transition]:
         return self._transitions
 
-    @property
+    @ property
     def sound(self):
         return self._sound
 
     def __post_init__(self):
         if self._object_types != None:
             self._object_types = self._object_types
         else:
@@ -543,12 +723,12 @@
                        for tr in self._ocpn.transitions}
             tpl = {tr: in_tpl[tr]+out_tpl[tr] for tr in self._ocpn.transitions}
             self._transitions = list(set(
                 [tr for tr in self._ocpn.transitions for p in tpl[tr] if p.object_type in self._object_types]))
             self._sound = True
 
 
-@dataclass
+@ dataclass
 class EnhancedObjectCentricPetriNet(object):
     ocpn: ObjectCentricPetriNet
     behavior: List[str]
     diagnostics: Dict[str, Any]
```

## ocpa/visualization/oc_petri_net/factory.py

```diff
@@ -1,21 +1,23 @@
-from ocpa.visualization.oc_petri_net.versions import control_flow, annotated_with_opera
+from ocpa.visualization.oc_petri_net.versions import control_flow, annotated_with_opera, new_control_flow
 from pm4py.visualization.common import gview
 from pm4py.visualization.common import save as gsave
 
 
 CONTROL_FLOW = "control_flow"
+NEW_CONTROL_FLOW = "new_control_flow"
 ANNOTATED_WITH_OPERA = "annotated_with_opera"
 
 VERSIONS = {
     CONTROL_FLOW: control_flow.apply,
+    NEW_CONTROL_FLOW: new_control_flow.apply,
     ANNOTATED_WITH_OPERA: annotated_with_opera.apply}
 
 
-def apply(obj, variant=CONTROL_FLOW, **kwargs):
+def apply(obj, variant=NEW_CONTROL_FLOW, **kwargs):
     return VERSIONS[variant](obj, **kwargs)
 
 
 def save(gviz, output_file_path):
     """
     Save the diagram
```

## ocpa/visualization/oc_petri_net/versions/__init__.py

```diff
@@ -1 +1,3 @@
-from ocpa.visualization.oc_petri_net.versions import control_flow, annotated_with_opera
+import ocpa.visualization.oc_petri_net.versions.control_flow
+import ocpa.visualization.oc_petri_net.versions.annotated_with_opera
+import ocpa.visualization.oc_petri_net.versions.new_control_flow
```

## ocpa/visualization/oc_petri_net/versions/annotated_with_opera.py

```diff
@@ -1,17 +1,34 @@
 import uuid
 import tempfile
 from graphviz import Digraph
 from ocpa.objects.oc_petri_net.obj import ObjectCentricPetriNet
 from ocpa.visualization.oc_petri_net.util.util import equal_arc
 from statistics import median, mean
 
-COLORS = ["#05B202", "#A13CCD", "#BA0D39", "#39F6C0", "#E90638", "#07B423", "#306A8A", "#678225", "#2742FE", "#4C9A75",
-          "#4C36E9", "#7DB022", "#EDAC54", "#EAC439", "#EAC439", "#1A9C45", "#8A51C4", "#496A63", "#FB9543", "#2B49DD",
-          "#13ADA5", "#2DD8C1", "#2E53D7", "#EF9B77", "#06924F", "#AC2C4D", "#82193F", "#0140D3"]
+COLORS = ['#7f66ff',
+          '#ff3399',
+          '#f58b55',
+          '#f25e65',
+          '#261926',
+          '#ddb14d',
+          '#5387d5',
+          '#1c3474',
+          '#a37554',
+          '#8bc34a',
+          '#cddc39',
+          '#ffeb3b',
+          '#ffc107',
+          '#ff9800',
+          '#ff5722',
+          '#795548',
+          '#9e9e9e',
+          '#607d8b',
+          '#9affff',
+          '#000000']
 
 
 def apply(ocpn, diagnostics, parameters=None):
     if parameters is None:
         parameters = {}
 
     image_format = "png"
@@ -20,150 +37,62 @@
 
     filename = tempfile.NamedTemporaryFile(suffix='.gv').name
     g = Digraph("", filename=filename, engine='dot',
                 graph_attr={'bgcolor': 'transparent'})
 
     all_objs = {}
     trans_names = {}
-
-    # if 'waiting_time' in parameters['measures']:
-    #     p_waiting = True
-    # else:
-    #     p_waiting = False
-    # if 'service_time' in parameters['measures']:
-    #     p_service = True
-    # else:
-    #     p_service = False
-    # if 'sojourn_time' in parameters['measures']:
-    #     p_sojourn = True
-    # else:
-    #     p_sojourn = False
-    # if 'synchronization_time' in parameters['measures']:
-    #     p_sync = True
-    # else:
-    #     p_sync = False
-    # if 'pooling_time' in parameters['measures']:
-    #     p_pooling = True
-    # else:
-    #     p_pooling = False
-    # if 'lagging_time' in parameters['measures']:
-    #     p_lagging = True
-    # else:
-    #     p_lagging = False
-    # if 'object_count' in parameters['measures']:
-    #     p_object_count = True
-    # else:
-    #     p_object_count = False
-    # if 'act_freq' in parameters['measures']:
-    #     p_act_freq = True
-    # else:
-    #     p_act_freq = False
-    # if 'arc_freq' in parameters['measures']:
-    #     p_arc_freq = True
-    # else:
-    #     p_arc_freq = False
-
-    pl_count = 1
-    tr_count = 1
-    arc_count = 1
-
-    # color = COLORS[index % len(COLORS)]
-    color = "#05B202"
     color_mapping = dict()
     object_types = ocpn.object_types
     for index, ot in enumerate(object_types):
         color_mapping[ot] = COLORS[index % len(COLORS)]
 
     for pl in ocpn.places:
-        # this_uuid = str(uuid.uuid4())
-        this_uuid = "p%d" % (pl_count)
-        # pl_str = this_uuid
-        pl_count += 1
+        this_uuid = str(uuid.uuid4())
         color = color_mapping[pl.object_type]
-
         pl_label = pl.name
-        # if missing_token == True:
-        #     pl_str = "p=%d r=%d\\nc=%d m=%d" % (
-        #         diagnostics["place_fitness_per_trace"][pl.name]["p"], diagnostics["place_fitness_per_trace"][pl.name]["r"], diagnostics["place_fitness_per_trace"][pl.name]["c"], diagnostics["place_fitness_per_trace"][pl.name]["m"])
-        #     pl_label += "\n %s" % (pl_str)
 
-        if pl.initial == True:
-            g.node("(p)%s" % (pl.name), pl.name, shape="circle", style="filled", fillcolor=color, color=color,
-                   fontsize="13.0", labelfontsize="13.0")
-        elif pl.final == True:
-            g.node("(p)%s" % (pl.name), pl.name, shape="circle", style="filled", color=color, fillcolor=color,
+        if pl.initial == True or pl.final == True:
+            g.node(this_uuid, pl_label, shape="circle", style="filled", fillcolor=color, color=color,
                    fontsize="13.0", labelfontsize="13.0")
         else:
-            g.node("(p)%s" % (pl.name), pl_label, shape="circle", color=color,
+            g.node(this_uuid, pl_label, shape="circle", color=color,
                    fontsize="13.0", labelfontsize="13.0")
-        all_objs[pl] = "(p)%s" % (pl.name)
+        all_objs[pl] = this_uuid
 
     for tr in ocpn.transitions:
-        # this_uuid = str(uuid.uuid4())
-        this_uuid = "t%d" % (tr_count)
-        tr_count += 1
+        this_uuid = str(uuid.uuid4())
+        tr_label = tr.label
+
         if tr.silent == True:
-            g.node(this_uuid, this_uuid, fontcolor="#FFFFFF", shape="box",
+            g.node(this_uuid, "", fontcolor="#FFFFFF", shape="box",
                    fillcolor="#000000", style="filled", labelfontsize="18.0")
             all_objs[tr] = this_uuid
-        elif tr.name not in trans_names:
-            tr_label = tr.name
-            tr_xlabel = "?"
-            # tr_xlabel = "Performance of %s" % (tr.name)
-            tr_label += f"\n {diagnostics[tr.name]['act_freq']}"
-
-            # if p_object_count:
-            #     tr_xlabel += f'\n {diagnostics[tr.name]["object_count"]}'
-
-            # if p_waiting:
-            #     tr_xlabel += '<br/>'
-            #     tr_xlabel += diagnostics[tr.name]['waiting_time']
-
-            # if p_service:
-            #     tr_xlabel += '<br/>'
-            #     tr_xlabel += diagnostics[tr.name]['service_time']
-
-            # if p_sojourn:
-            #     tr_xlabel += '<br/>'
-            #     tr_xlabel += diagnostics[tr.name]['sojourn_time']
-
-            # if p_sync:
-            #     tr_xlabel += '<br/>'
-            #     tr_xlabel += diagnostics[tr.name]['synchronization_time']
-
-            # if p_pooling:
-            #     tr_xlabel += '<br/>'
-            #     tr_xlabel += diagnostics[tr.name]['pooling_time']
-
-            # if p_lagging:
-            #     tr_xlabel += '<br/>'
-            #     tr_xlabel += diagnostics[tr.name]['lagging_time']
-            #     tr_xlabel += '<br/>'
-            g.node("(t)%s" % (tr.name), "%s" % (tr_label), shape="box", fontsize="36.0",
-                   labelfontsize="36.0", xlabel='''<<FONT POINT-SIZE="5">%s</FONT>>''' % (tr_xlabel))
-            trans_names[tr.name] = tr.name
-            all_objs[tr] = "(t)%s" % (tr.name)
         else:
-            all_objs[tr] = trans_names[tr.name]
+            tr_label = tr.label
+            tr_label += f"<br/><FONT POINT-SIZE='36'>{diagnostics[tr.label]['act_freq']}</FONT>"
+            tr_xlabel = ""
+            for chosen_measure in diagnostics[tr.label].keys():
+                tr_xlabel += add_diagnostics(diagnostics[tr.label][chosen_measure], chosen_measure)
+            tr_label += f"<br/><FONT POINT-SIZE='15'>{tr_xlabel}</FONT>"
+            g.node(this_uuid, "<%s>" % tr_label, shape="box", fontsize="36.0", labelfontsize="36.0")
+
+            all_objs[tr] = this_uuid
 
     for arc in ocpn.arcs:
-        # this_uuid = str(uuid.uuid4())
-        this_uuid = "a%d" % (arc_count)
-        arc_count += 1
+        this_uuid = str(uuid.uuid4())
         arc_annotation = ""
 
         source_node = arc.source
         target_node = arc.target
 
         if type(source_node) == ObjectCentricPetriNet.Place:
-            object_type = source_node.object_type
+            color = color_mapping[source_node.object_type]
         elif type(target_node) == ObjectCentricPetriNet.Place:
-            object_type = target_node.object_type
-
-        color = color_mapping[object_type]
+            color = color_mapping[target_node.object_type]
 
         penwidth = "1"
         if arc.__repr__() in diagnostics["arc_freq"]:
             freq = diagnostics["arc_freq"][arc.__repr__()]
         else:
             freq = ""
         arc_annotation += f"{freq}"
@@ -174,61 +103,23 @@
             g.edge(all_objs[source_node], all_objs[target_node],
                    label=arc_annotation, color=color, fontsize="13.0", penwidth=penwidth)
 
         all_objs[arc] = this_uuid
 
     g.attr(overlap='false')
     g.attr(fontsize='11')
+    g.attr(ranksep='1')
+    g.attr(nodesep='1')
 
     g.format = image_format
     return g
 
-
-def add_object_count(tr_name, agg, object_count):
-    added_tr_xlabel = f"<br/> {agg} number of objects: "
-    if agg in object_count[tr_name]:
-        for obj_type in object_count[tr_name][agg].keys():
-            added_tr_xlabel += "%s=%d " % (obj_type,
-                                           object_count[tr_name][agg][obj_type])
-    return added_tr_xlabel
-
-
-def add_waiting_time(tr_name, agg, waiting_time):
-    added_tr_xlabel = f"<br/> {agg} waiting time: "
-    if tr_name in waiting_time and agg in waiting_time[tr_name]:
-        added_tr_xlabel += "%s " % (waiting_time[tr_name][agg])
-    return added_tr_xlabel
-
-
-def add_service_time(tr_name, agg, service_time):
-    added_tr_xlabel = f"<br/> {agg} service time: "
-    if tr_name in service_time and agg in service_time[tr_name]:
-        added_tr_xlabel += "%s " % (service_time[tr_name][agg])
-    return added_tr_xlabel
-
-
-def add_sojourn_time(tr_name, agg, sojourn_time):
-    added_tr_xlabel = f"<br/> {agg} sojourn time: "
-    if tr_name in sojourn_time and agg in sojourn_time[tr_name]:
-        added_tr_xlabel += "%s " % (sojourn_time[tr_name][agg])
-    return added_tr_xlabel
-
-
-def add_synchronization_time(tr_name, agg, synchronization_time):
-    added_tr_xlabel = f"<br/> {agg} synchronization time: "
-    if tr_name in synchronization_time and agg in synchronization_time[tr_name]:
-        added_tr_xlabel += "%s " % (synchronization_time[tr_name][agg])
-    return added_tr_xlabel
-
-
-def add_pooling_time(tr_name, ot, agg, pooling_time):
-    added_tr_xlabel = f"<br/> {agg} pooling time: "
-    if tr_name in pooling_time[ot] and agg in pooling_time[ot][tr_name]:
-        added_tr_xlabel += "%s " % (pooling_time[ot][tr_name][agg])
-    return added_tr_xlabel
-
-
-def add_lagging_time(tr_name, ot, agg, lagging_time):
-    added_tr_xlabel = f"<br/> {agg} lagging time: "
-    if tr_name in lagging_time[ot] and agg in lagging_time[ot][tr_name]:
-        added_tr_xlabel += "%s " % (lagging_time[ot][tr_name][agg])
-    return added_tr_xlabel
+def add_diagnostics(tr_diagnostics, performance_measure):
+    printed_diagnostics = ""
+    if performance_measure in ['waiting_time', 'service_time', 'sojourn_time', 'synchronization_time', 'object_count', 'flow_time']:
+        for agg in tr_diagnostics.keys():
+            printed_diagnostics += f'{agg} {performance_measure}: {tr_diagnostics[agg]}<br/>'
+    elif performance_measure in ['pooling_time', 'lagging_time']:
+        for obj_type in tr_diagnostics.keys():
+            for agg in tr_diagnostics[obj_type].keys():
+                printed_diagnostics += f'{agg} {performance_measure} of {obj_type}: {tr_diagnostics[obj_type][agg]}<br/>'
+    return printed_diagnostics
```

## ocpa/visualization/oc_petri_net/versions/control_flow.py

```diff
@@ -1,15 +1,36 @@
 import uuid
 import tempfile
 from graphviz import Digraph
 from ocpa.objects.oc_petri_net.obj import ObjectCentricPetriNet
 
-COLORS = ["#05B202", "#A13CCD", "#BA0D39", "#39F6C0", "#E90638", "#07B423", "#306A8A", "#678225", "#2742FE", "#4C9A75",
-          "#4C36E9", "#7DB022", "#EDAC54", "#EAC439", "#EAC439", "#1A9C45", "#8A51C4", "#496A63", "#FB9543", "#2B49DD",
-          "#13ADA5", "#2DD8C1", "#2E53D7", "#EF9B77", "#06924F", "#AC2C4D", "#82193F", "#0140D3"]
+# COLORS = ["#05B202", "#A13CCD", "#BA0D39", "#39F6C0", "#E90638", "#07B423", "#306A8A", "#678225", "#2742FE", "#4C9A75",
+#           "#4C36E9", "#7DB022", "#EDAC54", "#EAC439", "#EAC439", "#1A9C45", "#8A51C4", "#496A63", "#FB9543", "#2B49DD",
+#           "#13ADA5", "#2DD8C1", "#2E53D7", "#EF9B77", "#06924F", "#AC2C4D", "#82193F", "#0140D3"]
+
+COLORS = ['#7f66ff',
+          '#ff3399',
+          '#f58b55',
+          '#f25e65',
+          '#261926',
+          '#ddb14d',
+          '#5387d5',
+          '#1c3474',
+          '#a37554',
+          '#8bc34a',
+          '#cddc39',
+          '#ffeb3b',
+          '#ffc107',
+          '#ff9800',
+          '#ff5722',
+          '#795548',
+          '#9e9e9e',
+          '#607d8b',
+          '#9affff',
+          '#000000']
 
 
 def apply(obj, parameters=None):
     if parameters is None:
         parameters = {}
 
     image_format = "png"
@@ -37,42 +58,43 @@
     for index, ot in enumerate(object_types):
         color_mapping[ot] = COLORS[index % len(COLORS)]
 
     for pl in obj.places:
         # this_uuid = str(uuid.uuid4())
         this_uuid = "p%d" % (pl_count)
         # pl_str = this_uuid
+        pl_label = ''.join(w[0].upper() for w in pl.name.split())
         pl_count += 1
         color = color_mapping[pl.object_type]
         if pl.initial == True:
-            g.node(pl.name, pl.name, shape="circle", style="filled", fillcolor=color, color=color,
+            g.node(pl.name, pl_label, shape="circle", style="filled", fillcolor=color, color=color,
                    fontsize="13.0", labelfontsize="13.0")
         elif pl.final == True:
-            g.node(pl.name, pl.name, shape="circle", style="filled", color=color, fillcolor=color,
+            g.node(pl.name, pl_label, shape="circle", style="filled", color=color, fillcolor=color,
                    fontsize="13.0", labelfontsize="13.0")
         else:
-            g.node(pl.name, pl.name, shape="circle", color=color,
+            g.node(pl.name, pl_label, shape="circle", color=color,
                    fontsize="13.0", labelfontsize="13.0")
         all_objs[pl] = pl.name
 
     for tr in obj.transitions:
         # this_uuid = str(uuid.uuid4())
         this_uuid = "t%d" % (tr_count)
         tr_count += 1
         if tr.silent == True:
             # g.node(this_uuid, this_uuid, fontcolor="#FFFFFF", shape="box",
             #       fillcolor="#000000", style="filled", xlabel="Test", labelfontsize="18.0")
             g.node(tr.name, this_uuid, fontcolor="#FFFFFF", shape="box",
-                   fillcolor="#000000", style="filled", xlabel="Test", labelfontsize="18.0")
+                   fillcolor="#000000", style="filled", xlabel="Test", labelfontsize="13.0")
             all_objs[tr] = tr.name  # this_uuid
         elif tr.name not in trans_names:
             # g.node(this_uuid, "%s \n (%s)" % (tr.name, this_uuid), shape="box", fontsize="36.0",
             #       labelfontsize="36.0")
-            g.node(tr.name, tr.name, shape="box", fontsize="36.0",
-                   labelfontsize="36.0")
+            g.node(tr.name, tr.name, shape="box", fontsize="13.0",
+                   labelfontsize="13.0")
             trans_names[tr.name] = tr.name  # this_uuid
             all_objs[tr] = tr.name  # this_uuid
         else:
             all_objs[tr] = trans_names[tr.name]
 
     for arc in obj.arcs:
         # this_uuid = str(uuid.uuid4())
```

## Comparing `ocpa-1.2.dist-info/LICENSE.txt` & `ocpa-1.3.1.dist-info/LICENSE.txt`

 * *Files identical despite different names*

## Comparing `ocpa-1.2.dist-info/RECORD` & `ocpa-1.3.1.dist-info/RECORD`

 * *Files 12% similar despite different names*

```diff
@@ -1,62 +1,70 @@
-ocpa/__init__.py,sha256=j45Be8ofn_n-OSfavSBpa0_GYdKX2l_wvei2FBbKTv0,357
+ocpa/__init__.py,sha256=jI1NU9zkASNkB8ZgimdtjnGIMe9tfl6qUEDLh7-uSGQ,359
 ocpa/algo/__init__.py,sha256=hycn6UaGu16HJk4YO7OgPvGt-58zf06fc86fv_RZlQs,139
 ocpa/algo/conformance/__init__.py,sha256=AuPXVvlLqiiG2glUx7WEVQ4gV2aBD_nA0ZFJct_-5rM,102
 ocpa/algo/conformance/constraint_monitoring/__init__.py,sha256=DkJ54uM2vbVc4ZMFtBs-AaZ7Zh0awVlAytsgCUrXbtk,131
-ocpa/algo/conformance/constraint_monitoring/algorithm.py,sha256=pHVDexWjY1NohjWTdU58iExFEOTbVnb2xzR4cOZaECg,1946
+ocpa/algo/conformance/constraint_monitoring/algorithm.py,sha256=qQVYb9lGp6_8JLFrmFaTl9c4riAXbdCRn4Nr-TZ3VII,2009
 ocpa/algo/conformance/constraint_monitoring/versions/__init__.py,sha256=8Pgi_Ix8IJvtULbnDUrWj1-jcv6C4CzNrvPiJeR0YSM,152
+ocpa/algo/conformance/constraint_monitoring/versions/extensive_log_based.py,sha256=heb0n_PKSTIK1flErx6N4iAyvyRFT74FLHW-Fj2kdxA,6615
 ocpa/algo/conformance/constraint_monitoring/versions/log_based.py,sha256=uGaBI2ETX_ghnmQ8R2cBOAago6jHfMHBh3EFRGKgIZc,5484
 ocpa/algo/conformance/constraint_monitoring/versions/model_based.py,sha256=iO592PnSdOlWFqKGCBydxZOhdv_bPW90mbaMPj5wydw,5967
 ocpa/algo/conformance/precision_and_fitness/__init__.py,sha256=8tsPVrDSAyUUG20sBPAmeZTO70D6W7EKBTRuF93Wzp8,117
 ocpa/algo/conformance/precision_and_fitness/evaluator.py,sha256=Np8oXPnpFpjUr8G0q0dycUMUxXOy3YfUTa0TqBLxZJE,1875
 ocpa/algo/conformance/precision_and_fitness/utils.py,sha256=87OmlzY8T6JtJDooT9bPGj5qkxnhG_SX1Eb7PZX_IS8,1783
 ocpa/algo/conformance/precision_and_fitness/variants/__init__.py,sha256=u5vVan8Z_-v17QXiXT57fkIM0x3yWEBLmDFaXxXvXVc,74
-ocpa/algo/conformance/precision_and_fitness/variants/replay_context.py,sha256=-iFKKNrMrvWKsjHBdG9eYsiOs1-HHmFJzLqk0ObsVds,12153
+ocpa/algo/conformance/precision_and_fitness/variants/replay_context.py,sha256=8BR88rKtjluGh6xZXH2Gj60xhBNaodomd_vNvHPxFSk,12156
 ocpa/algo/discovery/__init__.py,sha256=H_KERWlWRuXFfWVVATBhlq3WdUtvg52OAJonou0Wook,73
 ocpa/algo/discovery/enhanced_ocpn/__init__.py,sha256=Yl6hPt1Y_OeiOYkOKH3Jq_9-USGy_HPscA5lIEsX-r8,56
-ocpa/algo/discovery/enhanced_ocpn/algorithm.py,sha256=8n_sa1xToxbzLZdCDFeg4jO2b7PkgZ-5ZQu3kUH56XQ,885
+ocpa/algo/discovery/enhanced_ocpn/algorithm.py,sha256=O8Qje7TWGUWZIzkUgcaitYnzVFp9fjIVHB--pbpelvo,820
 ocpa/algo/discovery/ocpn/__init__.py,sha256=iMNuu1q3ILZ6RaWoJ6ymML2kAvfk-A4aohLof7HVVZM,83
-ocpa/algo/discovery/ocpn/algorithm.py,sha256=jwtrPI7MaoLTAtLr6g5059YAOBCvDDr_lbYwNXpj0qs,681
-ocpa/algo/discovery/ocpn/versions/__init__.py,sha256=5BgIf11r7I-3Qz71RLo_8pBpMEEkJO_loxd-dksCFqE,56
-ocpa/algo/discovery/ocpn/versions/inductive.py,sha256=_8wsR3NRyDYyTPLbgdsdx9EkccGyK__H0_uV7DLMJKw,8593
+ocpa/algo/discovery/ocpn/algorithm.py,sha256=-uy9J56ZFlpvr4J-bp7sVJ0r95jvR2KnYVe4W21_ueU,700
+ocpa/algo/discovery/ocpn/versions/__init__.py,sha256=5r7hIVktjIRYWyKAqqP3g07KDH9yv6vDCXf6iaGUdeU,116
+ocpa/algo/discovery/ocpn/versions/inductive.py,sha256=o-VwChpzDz9otoqML_fpIWCG7N_xizpjVGDoNEbMcek,8579
+ocpa/algo/discovery/ocpn/versions/new_inductive.py,sha256=TsLES1UK8c9_JXf4PAbfNaP5Ll-pH_N7Ds5R9P4s3-o,7040
 ocpa/algo/enhancement/__init__.py,sha256=RXMCafav_noc69GpmfBbmvR_sAIeAhUqr37sY-k0JJc,119
 ocpa/algo/enhancement/event_graph_based_performance/__init__.py,sha256=Ws3D149sE0n5gE8EF9Lh1-JtHzScNHp0ert0hRDO_58,137
-ocpa/algo/enhancement/event_graph_based_performance/algorithm.py,sha256=7VWF2cyEQt6ERdn-NkXoNLL5wyHMzMcDFEAkvIA_ohM,322
-ocpa/algo/enhancement/event_graph_based_performance/versions/__init__.py,sha256=C2eLV3jC3ZqdgR0J-lJi789HLoYqkU41Na8H5ii6a0Q,91
+ocpa/algo/enhancement/event_graph_based_performance/algorithm.py,sha256=ZhugTJ3AztZWqmVRNJxlYkp-UXCv87zJNEiGPzPbQ8E,447
+ocpa/algo/enhancement/event_graph_based_performance/versions/__init__.py,sha256=lro4ijWdYHkRfasM7snC34vKJIKJh0300_tInCsLeuI,117
+ocpa/algo/enhancement/event_graph_based_performance/versions/event_object_graph_based.py,sha256=gHmTUvstgr4n8r9DpuMbDPtLhZzHzBiz92p8kauWcXU,9672
 ocpa/algo/enhancement/event_graph_based_performance/versions/perfectly_fitting.py,sha256=VTlagDr4AKGN8S636ZfVNYk0whZ2H7gKNsNOlHbDZqI,14525
 ocpa/algo/enhancement/token_replay_based_performance/__init__.py,sha256=vqpKnknjzDMfbXkiIimq2dbXXuIRxcuYb20UK0bqv1o,69
 ocpa/algo/enhancement/token_replay_based_performance/algorithm.py,sha256=MZGT5cDoyo3qzpLLGK5kFdC_e5X0TqdwaBYiKxz0dZk,2262
-ocpa/algo/enhancement/token_replay_based_performance/util.py,sha256=RWNT359UvMkJ62tSCnga4D8J7xuzELF9mMN4ICkKHiw,64144
+ocpa/algo/enhancement/token_replay_based_performance/util.py,sha256=YYOepk0YCc9elIjimBXtANeY-NKb541y8EicIt2i0QM,61795
 ocpa/algo/enhancement/token_replay_based_performance/versions/__init__.py,sha256=iraUezULbIXXaId9IXtF5aiRizsp3qGHrj2waDrhqCs,75
-ocpa/algo/enhancement/token_replay_based_performance/versions/opera.py,sha256=NTAizJFO62QybNiUpvnJ_xrFptHZ_Qy62tJpOZGtgQo,32803
+ocpa/algo/enhancement/token_replay_based_performance/versions/opera.py,sha256=-QoPrJiAPZ8PQaVqUsQR-xwaLTrPRCbtvFBxeqh8N7o,28966
 ocpa/algo/predictive_monitoring/__init__.py,sha256=chHy9aDyHU2zOhtEVFZNG1J0oF1Qv9tVwpVMt1EiX14,124
-ocpa/algo/predictive_monitoring/factory.py,sha256=sS3MRzZ25Os_Rit5uH2gmIdpy0XHx5-rdCAhM35fq7E,9648
-ocpa/algo/predictive_monitoring/obj.py,sha256=wuJZFuqRPW3pQ4wuIq55tAHfWyYh5Z6VWb1tAgOHGFs,8686
-ocpa/algo/predictive_monitoring/sequential.py,sha256=J8BG9Bz8mQVtk9AbVP04vedLXTfLZrjwoTRBGqDOQbQ,1571
-ocpa/algo/predictive_monitoring/tabular.py,sha256=ip_sRcRkHdE4xm2xuxp1u9EByWrbWpinINiarGGCIKk,1041
+ocpa/algo/predictive_monitoring/factory.py,sha256=IcyDv7c-BG8rBDB1EefjkUqoWFMlbwfHgnFtsmjy8XY,9804
+ocpa/algo/predictive_monitoring/obj.py,sha256=seXYgaGTkmlTj9MuGK0t7Ln2D7V9IZf9HV51DrHUGlE,9333
+ocpa/algo/predictive_monitoring/sequential.py,sha256=UkQar342JdySB7BVH67eO4PH8JQYFs6HooGYQDlNWGU,1541
+ocpa/algo/predictive_monitoring/tabular.py,sha256=pduyDczDrqtIFHk_pybHxWxZDd8LRPlPTobMs_eNMZ0,984
 ocpa/algo/predictive_monitoring/time_series.py,sha256=nFKgby4hJbl488Xrtpwmqew8tsSEYs2rNjlsljLXXCI,3526
 ocpa/algo/predictive_monitoring/event_based_features/__init__.py,sha256=YwwAijZR7NIinWtU2mHxfbm65InQ98j8aEidunw9E-w,81
-ocpa/algo/predictive_monitoring/event_based_features/extraction_functions.py,sha256=xTjoJ4UCjU4F8eaEI_nl2IkHF5TNZD0nvuYU6kxPlR0,12568
+ocpa/algo/predictive_monitoring/event_based_features/extraction_functions.py,sha256=h2NDCp9DdosS8beavFBV3wHsRHERNmAPlcQeycG2idY,12130
 ocpa/algo/predictive_monitoring/execution_based_features/__init__.py,sha256=3Od9OWR4CPqjsOWhKiR9KSCgJv9RM-34VoVVSn6jJaM,85
 ocpa/algo/predictive_monitoring/execution_based_features/extraction_functions.py,sha256=u7S9wiWMRZvm8sOo6YqC8x9Yc2j2kgYVdPG3ZD_DHZQ,2532
-ocpa/algo/util/__init__.py,sha256=2K6EqxRc_voSgkoFOllCM9xZ6TEWUNmIpPGZCyH7odI,136
+ocpa/algo/util/__init__.py,sha256=B9Mc7ydYC5mAcun2dPsHtjh_KGO-fAn4dUcGya0n0Oo,163
 ocpa/algo/util/util.py,sha256=gnMkiwwVXfbN1v7orPXgAGmg4L0D7YcEJPttQJd4zbw,1677
+ocpa/algo/util/aopm/__init__.py,sha256=eKbV5qcX77-lTQ8h97wqwUGqthtC3o4_CczmpnH7Gl0,43
+ocpa/algo/util/aopm/action_engine/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
+ocpa/algo/util/aopm/action_engine/algorithm.py,sha256=TnzRg-WKOhMojL0I2A6L5YUBf52yzti5MpfK1Jz8DYI,525
+ocpa/algo/util/aopm/impact_analysis/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
+ocpa/algo/util/aopm/impact_analysis/algorithm.py,sha256=VQCSsv49Z1vQjxNvucIOGSusNxU7Ort-926SiD4tcmQ,519
 ocpa/algo/util/filtering/__init__.py,sha256=UUFBvs15O-nTk63H1VU5h0iGLSyNqpVoFFcccM4Jpj0,74
 ocpa/algo/util/filtering/graph/__init__.py,sha256=6D_JLO1cdWyKnwByzKu0FTQyXLH42G0ETSKOpKcCIaY,50
 ocpa/algo/util/filtering/graph/event_graph/__init__.py,sha256=g2V9MBgIRy9ntz8M55T62B4MDfor1EbCat0_-cHJ1Zw,59
 ocpa/algo/util/filtering/graph/event_graph/algorithm.py,sha256=YbRKFnnCuNPTvo-Pg2Q6TpOadME2PxpDfjSlJykOdug,669
 ocpa/algo/util/filtering/graph/event_graph/versions/__init__.py,sha256=QRNYrqVreAb0LXuri5b4qZBb4y1j_16oxv3amDAV16Y,231
 ocpa/algo/util/filtering/graph/event_graph/versions/filter_complete.py,sha256=Mk4PeHfObo6W-9UeeSeEhqpUu0ouW1YUZ5Tp0GUJzok,379
 ocpa/algo/util/filtering/graph/event_graph/versions/filter_object_types.py,sha256=8GsRVs7TAL9dOz0kUoq7njU62ppfyEogp-lTF66SwoQ,500
 ocpa/algo/util/filtering/graph/event_graph/versions/filter_subprocess.py,sha256=Y8oAmFH6EQ__HjMAkBTpzFZCUnSuBB9csRgcA_-LoVg,1649
 ocpa/algo/util/filtering/log/__init__.py,sha256=OGxYhhV6KxWnMJDCHSiCDST5ByiYeo7DXUcm8HRRarA,210
-ocpa/algo/util/filtering/log/activity_filtering.py,sha256=J9NxbOHWbGmeU9wdS1b64wWtzbIDwSmNwAbHxnR8nps,1238
+ocpa/algo/util/filtering/log/activity_filtering.py,sha256=ZrwpfGI8Om6QgsqIBmsSuXCiFZztdURdLnMaly2bw_w,1249
 ocpa/algo/util/filtering/log/case_filtering.py,sha256=tRE1_17-TO5BwnuU_LipX2qlpqxUpsLBph3MWIzrEXE,705
-ocpa/algo/util/filtering/log/time_filtering.py,sha256=ENd_P9daG72SFDblmwrj4gLJlPZmU4nhjPrV9I36JRA,5504
-ocpa/algo/util/filtering/log/variant_filtering.py,sha256=XGzwdEh3CBfWwXDv04PZAGHSjDC7swMGnCNiKjD8j2g,1484
+ocpa/algo/util/filtering/log/time_filtering.py,sha256=3wVHTUm-wzkRWEbsv6sLw6fUoHOQWdbwqw5UmZ3oMtQ,5922
+ocpa/algo/util/filtering/log/variant_filtering.py,sha256=bZZHjReYiiW0HsD1w_sCgUrxu970k6jrlBRLRiV9nOU,1483
 ocpa/algo/util/process_executions/__init__.py,sha256=KNrx7t50DvNHWZxZv4jT_YoZPKnb4qzaCmUi17gfk3w,99
 ocpa/algo/util/process_executions/factory.py,sha256=Qran50a_ot3Gp4ssdSmfeKkYGBWJ_1FAXoZYzshyzMk,414
 ocpa/algo/util/process_executions/versions/__init__.py,sha256=MYJziAPnmOoQ5bzgi3SOY4SuJju8YcQRpzIkrpCuIPg,134
 ocpa/algo/util/process_executions/versions/connected_components.py,sha256=jIaVYjA8sS2VXAca1JDsziBkTJN67gKs-NzKH3r_igY,1646
 ocpa/algo/util/process_executions/versions/leading_type.py,sha256=uprTDgAJTcYJfh10Khv0cXOOWo01YlebevaoVtl5VD0,3766
 ocpa/algo/util/retrieval/__init__.py,sha256=NgQnO3xT1xYzU24-bQrZ_gIkqG0nTyWgqlZcDUgq-EE,163
 ocpa/algo/util/retrieval/constraint_graph/__init__.py,sha256=11of-yQjgL1XYEOvGJ4F2yy16SnJ2LEbNp60b_y84uQ,64
@@ -67,86 +75,95 @@
 ocpa/algo/util/retrieval/event_graph/algorithm.py,sha256=jr8IatS3qojvODgTa7b5pbA21aCKDQ5ZCsgIFaQZ7RU,307
 ocpa/algo/util/retrieval/event_graph/versions/__init__.py,sha256=d_qSMHcxV-755a18fRSHt2WenLvafMYkoqMmWVWMz-U,66
 ocpa/algo/util/retrieval/event_graph/versions/classic.py,sha256=olmizhx5YDkEHjdYeZgubCuE9_Hqy7o0LEHwaPsQ7qU,2137
 ocpa/algo/util/variants/__init__.py,sha256=o7vfHrcxzZFu8t2CiMThO9k_zH-g5aYNzgu3Sq_zX7s,40
 ocpa/algo/util/variants/factory.py,sha256=kGkpCsiLb4EQ87qU4Jup-uRkm8g0D469wLD59rm01mc,348
 ocpa/algo/util/variants/versions/__init__.py,sha256=eq3SRsmKZZKGOjRIPod6YeoZsRqQRx5ku2CcKY08YEk,108
 ocpa/algo/util/variants/versions/onephase.py,sha256=G7MRIiZr1jiXRtJiI5TIdx6nNpjxBsiBnRaIwhWtEDw,4721
-ocpa/algo/util/variants/versions/twophase.py,sha256=BTmhYb574VKf6s83Rr5wTfhLeFl3KMtw6c_DhTH34Pw,4953
+ocpa/algo/util/variants/versions/twophase.py,sha256=7c3V9ntIODkznU7CAlDRMt75Wh6Q4D7sx7XnQmA_H9M,4954
 ocpa/algo/util/variants/versions/utils/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 ocpa/algo/util/variants/versions/utils/helper.py,sha256=9akFcYeubsTvqej-KxWzyCyJtHY5NnkmE9sJF_8IhS8,1191
-ocpa/objects/__init__.py,sha256=hDjEjg9pORquoHB7gWJf5krMAv-ML8V2pNPtyg5OeXA,83
-ocpa/objects/graph/__init__.py,sha256=t-WyKrRKrkV5cKssAYR0K1dtOXB5EhnB70kiEOBMTUE,130
+ocpa/objects/__init__.py,sha256=EyCe4vfvOU_Prr_hEWlBMrA7r28UA3Oi_AdICWGCaz8,108
+ocpa/objects/aopm/__init__.py,sha256=3BUaPm7IjUqgJZTm61bG7SOsTnPWsVVvDZnKtQnno28,80
+ocpa/objects/aopm/action_interface_model/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
+ocpa/objects/aopm/action_interface_model/obj.py,sha256=TZw-ryjyu3ZtFKc9FVZOChW4gxLyBy9NKwsir9WpMaY,2372
+ocpa/objects/aopm/impact/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
+ocpa/objects/aopm/impact/obj.py,sha256=riFehVHrX-Tsd1xbbKLVOsC5_Tq-kW6hlY1AUL9G7aw,1373
+ocpa/objects/graph/__init__.py,sha256=6nkH4zfg6_11zHPCePvUF78B7KfOxmV1k58x1Tdtmr0,183
 ocpa/objects/graph/constraint_graph/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 ocpa/objects/graph/constraint_graph/obj.py,sha256=O1h_HczFWY4_uAHnfkoccnk2bHoqyUr6CEk8XWElNMY,5194
 ocpa/objects/graph/correlated_event_graph/__init__.py,sha256=XOvEOhl2008BRn2G6HZKRKSdP6OH1xH79WuTZy0mCL0,59
 ocpa/objects/graph/correlated_event_graph/obj.py,sha256=weW2UYLLNqIs8phnVNc1qDTcG2dBavgSpxYuVhTk4o4,2256
 ocpa/objects/graph/correlated_event_graph/retrieval/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 ocpa/objects/graph/correlated_event_graph/retrieval/algorithm.py,sha256=UzAYRcDBfc3F3HOOIzXfXb6NJeZNGRBPYQsFg5Bn-8E,734
 ocpa/objects/graph/event_graph/__init__.py,sha256=JSddpD0dCbo_jPdZkAnQoIqiuK7fpY4LNx29HxHSBec,48
 ocpa/objects/graph/event_graph/obj.py,sha256=huqUjvsq7bpQu1_O7IOj-PJchFD9YEWdcKted3aYaUA,746
 ocpa/objects/graph/event_graph/retrieval/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 ocpa/objects/graph/event_graph/retrieval/algorithm.py,sha256=LU4FvfHh0hUi2r1iLvTmLIHIGic0SJ7BhJAxWAIMIXc,2154
+ocpa/objects/graph/extensive_constraint_graph/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
+ocpa/objects/graph/extensive_constraint_graph/obj.py,sha256=FEakZHLce-leSyMICQIqZUD5osQDqm5Sga0cm7c_LqQ,4424
 ocpa/objects/log/__init__.py,sha256=waG4CpoYoV02mCkpxKyyWrriOByJsdpaBm-00DXpiHU,154
 ocpa/objects/log/ocel.py,sha256=wk3cTBlOnjgyV1q6dAu_fkR7vt0xA4a5dH_PuufHH5Q,9429
 ocpa/objects/log/converter/__init__.py,sha256=L9jZWnwCG5IDmAUbNrvSdAE3dm4yDnZz9NvNaKWWmJ8,85
-ocpa/objects/log/converter/factory.py,sha256=MZKSSR1Jx3AuctTNnVbpg-_J5mRyoeBTx1DnU2PCOnk,391
+ocpa/objects/log/converter/factory.py,sha256=y_0k1lhHiC1unFzXWpLzRoN5a2JDJxot-U-1ovIHjlE,391
 ocpa/objects/log/converter/versions/__init__.py,sha256=xRB8ZbiGbqo5YZTJcTIE3rmRXGMqvhp2PzRzPmxo8Wo,123
-ocpa/objects/log/converter/versions/df_to_ocel.py,sha256=mmi-E0kLhoHLxaRwnCDVGPYt8LVK3V2dyta5PURB5zM,2615
+ocpa/objects/log/converter/versions/df_to_ocel.py,sha256=kyxY0s_SgotnuMKVmbiqG11HkvWtvmI7X__NxHLT7Sg,3234
 ocpa/objects/log/converter/versions/jsonocel_to_csv.py,sha256=Fr4ghsU5J4-SeKCB-la-B782Vcg4WZpRkiuCkrIJIeo,1711
 ocpa/objects/log/exporter/__init__.py,sha256=JTgtXs4ukVzndTkSTFEDocY4xY_snkKR9MFmU_hSAU8,38
 ocpa/objects/log/exporter/ocel/__init__.py,sha256=_LCMrtlzJzz0xlELrP-tJeYzXhOlcukztVcJi25rXJY,47
 ocpa/objects/log/exporter/ocel/factory.py,sha256=7A7fyGkXX6EPNAebXn4UxOgbH5UoYor8TlwD-OoX5qs,812
 ocpa/objects/log/exporter/ocel/versions/__init__.py,sha256=UKVbwHgLveMJJgtOUBVOR7THqdwrjNM7k6Z7Vtv4Q3U,64
 ocpa/objects/log/exporter/ocel/versions/export_ocel_json.py,sha256=E0CYQJcgcp-yIpzgFDwklEFz9CRak4qW03qv_klRVfg,2127
 ocpa/objects/log/importer/__init__.py,sha256=tvA7VYoXEbyiwpKVePqMjmUNMiLvDz54OSrCQ-OCg7E,75
 ocpa/objects/log/importer/csv/__init__.py,sha256=pxcPcKeIcPiiWhCTa-kNI0jCQQQakybOFOzOcfhlok0,91
 ocpa/objects/log/importer/csv/factory.py,sha256=WLmOFY6QtjhXKtEqn-UKcToTp-2RDUfZOjNXRhZXA0Q,2620
-ocpa/objects/log/importer/csv/util.py,sha256=kd6SsS505Kp0K9icelK-L80ELoK6uniqI18C8B6pX2Y,5221
+ocpa/objects/log/importer/csv/util.py,sha256=VzQI5abjfxPfu_0Orsjsgrt_4XmId1-InDzw2pkz0KY,5283
 ocpa/objects/log/importer/csv/versions/__init__.py,sha256=iyb2ydJaq9ywEpglem1gA6MR_8yIlZK5BtzxMqYXmq4,159
-ocpa/objects/log/importer/csv/versions/to_df.py,sha256=YqEdtEBzfy7iWDFVKEnOcqSZnOQFqEhbMbxnU19Aiuk,1473
-ocpa/objects/log/importer/csv/versions/to_obj.py,sha256=BrW2s_nESllBOSZOS89EFmF0Gn9hknK7LJ91pFoLuXQ,3293
-ocpa/objects/log/importer/csv/versions/to_ocel.py,sha256=J-je9LTA6QgNx3EPCJGbf2BMPjbPLYdAg4kk5SjODfU,862
+ocpa/objects/log/importer/csv/versions/to_df.py,sha256=cB3zMEaZ740SauyWL08KetgJnF7avKqjGgXVz2tKW4w,1485
+ocpa/objects/log/importer/csv/versions/to_obj.py,sha256=KdnmN2aWAWatsKz7RQICaLkAJYc3j4pBi4mXuA5ciLs,3243
+ocpa/objects/log/importer/csv/versions/to_ocel.py,sha256=11yVKfSSZT416D9P1g6IdYSThf95uQyPSruY81iCKqg,1007
 ocpa/objects/log/importer/ocel/__init__.py,sha256=uOE-2zed1kqLpCZFlCt_wdy_XD0JJToQRE9mMKKg1Ng,93
 ocpa/objects/log/importer/ocel/factory.py,sha256=WUyt3TrkzTgQaXEN_4gFfXPi89NwFIyU_0-LINgoAHI,2317
 ocpa/objects/log/importer/ocel/parameters.py,sha256=L61pDC2ufbliUmX_DdDVVYS2ok5PPb2MVx-YA8HwhvE,1431
 ocpa/objects/log/importer/ocel/versions/__init__.py,sha256=7Ji1nF-ZidxO3LMYUda39PiSxEqsRuFjKl83gAlf_ac,137
-ocpa/objects/log/importer/ocel/versions/import_ocel_json.py,sha256=SHNihdupVeUfxXlcmtGyzd420Aj1riuveLZNdxQFSTs,4997
+ocpa/objects/log/importer/ocel/versions/import_ocel_json.py,sha256=DEua_57pno3AOk5C1IG7R5S1H0DpoEZ5fZoU8Dcyu98,5270
 ocpa/objects/log/importer/ocel/versions/import_ocel_xml.py,sha256=jvBBdrzKD1e9wSkoJBy8msjfKllQJzX1vpj7fd6l_L0,3700
 ocpa/objects/log/util/__init__.py,sha256=24enmE5xudpl361AGAke6jnzKQtde5yzgrB5ub-M_is,69
 ocpa/objects/log/util/misc.py,sha256=MviKwuMd76XRm1D45Wu-aU49vn-tOpDrn3CbKBpKuV4,1312
 ocpa/objects/log/util/param.py,sha256=umkhAXW578Sl_SXQ7YFhkQkXx2HGYZm31Zoqgj69ip4,1662
 ocpa/objects/log/variants/__init__.py,sha256=O36QtLN_9kqIbcQEYzQbGwpa45hv-pXr3MEcCQUj5R8,130
-ocpa/objects/log/variants/graph.py,sha256=Y9OPCB8Euvp4ap9rDitQNQe20T5PcmGgMsKAtTSyB1E,107
-ocpa/objects/log/variants/obj.py,sha256=Z_7ja5KGjhgHsYXhcX68_tt7hkC2KCUT7gdgTe2vgIo,6725
-ocpa/objects/log/variants/table.py,sha256=vrg31EE4NaoKEHhDsQQdWnY-QuHU9XmJ9MY0Hkl1Uj4,2928
+ocpa/objects/log/variants/graph.py,sha256=Pv1JD9t5ARPWJvDFIA2c1dcUA4X0R0oIAsktI8aDa1E,107
+ocpa/objects/log/variants/obj.py,sha256=argFLgYoiTzfJFcVpFUkI9JXVWlExCyyAlPk4IO8VIQ,12391
+ocpa/objects/log/variants/table.py,sha256=w5-f4U6N4T0a2_iDlYFTqHGHjrg5BsfP5IFshkrT8dY,2859
 ocpa/objects/log/variants/util/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 ocpa/objects/log/variants/util/table.py,sha256=6hWUgdnVC2jS9aFz51SnwhI2exo4NoiCnbjCQv-kjfU,825
 ocpa/objects/oc_petri_net/__init__.py,sha256=MOHbNb7RpsHChIdS_04Jxw1WXMEPtNNql_qSsjbLbwc,124
-ocpa/objects/oc_petri_net/obj.py,sha256=tR3dT0x8Rcwqvr_LvFZvh32HgTnTOihmZVckMDiX8GM,16287
+ocpa/objects/oc_petri_net/obj.py,sha256=XM2zvCvcYYwjky4sxN33emj-rsAl9Gw_NhKaz_gE8tM,23248
 ocpa/objects/oc_petri_net/properties.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 ocpa/objects/oc_petri_net/semantics.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
 ocpa/util/__init__.py,sha256=xunIQhWHof_8Xm2dUlJ2WdpiOE79pNS6l-EeD5ceAxM,53
 ocpa/util/constants.py,sha256=Vkb4raGsCy7X2klxXbeidMjDuwSFLEYdO7EFm1WF4XI,195
+ocpa/util/util.py,sha256=uJ26j8wtjXMxQpWumkvvqMMVK2P9uAOpCkBYXaXEiSw,2706
 ocpa/util/vis_util.py,sha256=z_gNdyaYs-JD3KuMUlW2Zyn-AZFLZLC7-O65PRn9i88,1051
 ocpa/visualization/__init__.py,sha256=yvPiIxcZr4LRxrq0mZv5sc6Y1mjZ5E4nBAfQFYQ_FO4,69
 ocpa/visualization/constraint_graph/__init__.py,sha256=vyTy5HJKWdf8RZjPw_SzFW0ru4nl4uXox9fdzobPh_g,105
 ocpa/visualization/constraint_graph/algorithm.py,sha256=FFQ7ZpttSuVuT2uaWkhhbhovEnOpdMUoloKLZvML4M0,248
 ocpa/visualization/constraint_graph/versions/__init__.py,sha256=UO7Ea7W6t8YmyOG5E5mb_gOox9vfK8xkEde2-_YUKAc,70
 ocpa/visualization/constraint_graph/versions/to_cytoscape.py,sha256=_j4uZpCWe9D9VfQ4bC4ikagRQQK04cSDoQUZhf7cz04,2902
 ocpa/visualization/log/__init__.py,sha256=Qe5jwQZ-HqSkcP_R0P2Ux3LVT0BHehS9x-H7BYA8Jf0,39
 ocpa/visualization/log/variants/__init__.py,sha256=5zzTsLrak38H0ivqxEH8xpQos2JH6ODw0J44qSAZDBI,95
 ocpa/visualization/log/variants/factory.py,sha256=8FDxmDylf375flGHAzoYsGTo8LNQ0JHgY26zCX_GBH8,694
 ocpa/visualization/log/variants/versions/__init__.py,sha256=i7Js0butp5f3HbFi9mfmdGGSWzltc22C24cC2gqchMo,66
 ocpa/visualization/log/variants/versions/chevron_sequences.py,sha256=zvyIb730Oxdq2O74QNlPnu1_xR4_fa_JK8zy7K6eGrw,6026
 ocpa/visualization/oc_petri_net/__init__.py,sha256=cMMwBkLwAqgNEZ2_GKugB68vDAchTnNP5jTpaNQIKW0,139
-ocpa/visualization/oc_petri_net/factory.py,sha256=OwFR9Vf8au-QZwIdU9iL17xZzmlzN79z5z33I0wpmrc,867
+ocpa/visualization/oc_petri_net/factory.py,sha256=C37f49RT4uiBbmBD5nKSzYadM6Zw_l4Io_iLDPTw-x4,973
 ocpa/visualization/oc_petri_net/util/__init__.py,sha256=669WMOCKIAPq8CKx9_Gn39H3Vxaac-owuoMTNhAuvyM,49
 ocpa/visualization/oc_petri_net/util/util.py,sha256=K9vIgIxFdKmCLSzIuZ1qHyBoLTt0ZJZP7YLDrSZuj9M,149
-ocpa/visualization/oc_petri_net/versions/__init__.py,sha256=k3bXwxjwY6qNpzw0MDGocXivpYD-nBCx5imHPZeC8DU,88
-ocpa/visualization/oc_petri_net/versions/annotated_with_opera.py,sha256=Bznzn24ob4DWfXV609KMxrIMnQMr8WUqlc2rf9sb7OI,8628
-ocpa/visualization/oc_petri_net/versions/control_flow.py,sha256=qCQmyAbNK4pqaaFV7F2B7b-pXyLJyfFoJY8dTPQZvL8,4295
-ocpa-1.2.dist-info/LICENSE.txt,sha256=21d6g8sSoL6AbNFmox-oYzV2jHmBQkGBAooaG_usDGI,34600
-ocpa-1.2.dist-info/METADATA,sha256=kwt5EEcVVlir73fyxYUu4m_yDV6CAm1hwl6wDXb0_Bo,378
-ocpa-1.2.dist-info/WHEEL,sha256=G16H4A3IeoQmnOrYV4ueZGKSjhipXx8zc8nu9FGlvMA,92
-ocpa-1.2.dist-info/top_level.txt,sha256=v6yPJtJm9FE3aX5vNeAUR4NEh3hlc7a2yBas0BRgsUY,5
-ocpa-1.2.dist-info/RECORD,,
+ocpa/visualization/oc_petri_net/versions/__init__.py,sha256=_651D31fLfRhWJvQhZiCAF57iCbHzbOlQP5WDcf1DxA,195
+ocpa/visualization/oc_petri_net/versions/annotated_with_opera.py,sha256=KZhAHuGd16wz6Wfto3tQedhr-Xt1Ru6BceykLpl_zlQ,4452
+ocpa/visualization/oc_petri_net/versions/control_flow.py,sha256=-axabBtoMJsD44ditxsPVZnU_ldSnOA5BujIWZBGhlU,4791
+ocpa/visualization/oc_petri_net/versions/new_control_flow.py,sha256=rrR0RZyrYCppiu6ti9ev1Mxv0a4Qo_3WpaimK5eKYww,3887
+ocpa-1.3.1.dist-info/LICENSE.txt,sha256=21d6g8sSoL6AbNFmox-oYzV2jHmBQkGBAooaG_usDGI,34600
+ocpa-1.3.1.dist-info/METADATA,sha256=vGTDM-rhuD0ZuYZ3ZPQ9f07M3W3NsA9Hg9aDD4x1J60,341
+ocpa-1.3.1.dist-info/WHEEL,sha256=G16H4A3IeoQmnOrYV4ueZGKSjhipXx8zc8nu9FGlvMA,92
+ocpa-1.3.1.dist-info/top_level.txt,sha256=v6yPJtJm9FE3aX5vNeAUR4NEh3hlc7a2yBas0BRgsUY,5
+ocpa-1.3.1.dist-info/RECORD,,
```

