# Comparing `tmp/alphawave-0.2.9.tar.gz` & `tmp/alphawave-0.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "alphawave-0.2.9.tar", last modified: Mon Jun 26 19:40:52 2023, max compression
+gzip compressed data, was "alphawave-0.3.0.tar", last modified: Wed Jun 28 02:46:39 2023, max compression
```

## Comparing `alphawave-0.2.9.tar` & `alphawave-0.3.0.tar`

### file list

```diff
@@ -1,62 +1,62 @@
-drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-26 19:40:52.623031 alphawave-0.2.9/
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1070 2023-06-05 21:12:30.000000 alphawave-0.2.9/LICENSE
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     9441 2023-06-26 19:40:52.623031 alphawave-0.2.9/PKG-INFO
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     8859 2023-06-18 19:15:49.000000 alphawave-0.2.9/README.md
--rw-rw-r--   0 bruce     (1000) bruce     (1000)      945 2023-06-26 19:40:43.000000 alphawave-0.2.9/pyproject.toml
--rw-rw-r--   0 bruce     (1000) bruce     (1000)       38 2023-06-26 19:40:52.623031 alphawave-0.2.9/setup.cfg
-drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-26 19:40:52.619031 alphawave-0.2.9/src/
-drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-26 19:40:52.623031 alphawave-0.2.9/src/alphawave/
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     9267 2023-06-20 23:20:58.000000 alphawave-0.2.9/src/alphawave/AlphaWave.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1370 2023-06-10 00:08:35.000000 alphawave-0.2.9/src/alphawave/Colorize.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)      740 2023-06-18 18:50:38.000000 alphawave-0.2.9/src/alphawave/DefaultResponseValidator.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     6405 2023-06-26 03:01:54.000000 alphawave-0.2.9/src/alphawave/JSONResponseValidator.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1173 2023-06-19 22:47:36.000000 alphawave-0.2.9/src/alphawave/MemoryFork.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     8905 2023-06-19 15:46:26.000000 alphawave-0.2.9/src/alphawave/OSClient.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     8916 2023-06-19 16:39:38.000000 alphawave-0.2.9/src/alphawave/OpenAIClient.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1377 2023-06-15 04:11:41.000000 alphawave-0.2.9/src/alphawave/RepairTestClient.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     3008 2023-06-15 23:14:04.000000 alphawave-0.2.9/src/alphawave/Response.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)      800 2023-06-15 04:12:01.000000 alphawave-0.2.9/src/alphawave/TestClient.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1515 2023-06-15 04:12:10.000000 alphawave-0.2.9/src/alphawave/TestClientTest.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)        0 2023-06-06 23:52:12.000000 alphawave-0.2.9/src/alphawave/__init__.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1359 2023-06-15 04:10:27.000000 alphawave-0.2.9/src/alphawave/alphawaveTypes.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     4163 2023-06-04 18:16:08.000000 alphawave-0.2.9/src/alphawave/internalTypes.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)      782 2023-06-07 21:02:29.000000 alphawave-0.2.9/src/alphawave/jsonParser.py
-drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-26 19:40:52.623031 alphawave-0.2.9/src/alphawave.egg-info/
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     9441 2023-06-26 19:40:52.000000 alphawave-0.2.9/src/alphawave.egg-info/PKG-INFO
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1758 2023-06-26 19:40:52.000000 alphawave-0.2.9/src/alphawave.egg-info/SOURCES.txt
--rw-rw-r--   0 bruce     (1000) bruce     (1000)        1 2023-06-26 19:40:52.000000 alphawave-0.2.9/src/alphawave.egg-info/dependency_links.txt
--rw-rw-r--   0 bruce     (1000) bruce     (1000)      155 2023-06-26 19:40:52.000000 alphawave-0.2.9/src/alphawave.egg-info/requires.txt
--rw-rw-r--   0 bruce     (1000) bruce     (1000)       44 2023-06-26 19:40:52.000000 alphawave-0.2.9/src/alphawave.egg-info/top_level.txt
-drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-26 19:40:52.623031 alphawave-0.2.9/src/alphawave_agents/
--rw-rw-r--   0 bruce     (1000) bruce     (1000)    16612 2023-06-19 22:45:42.000000 alphawave-0.2.9/src/alphawave_agents/Agent.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1332 2023-06-11 16:22:40.000000 alphawave-0.2.9/src/alphawave_agents/AgentCommandSection.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     2956 2023-06-19 02:42:43.000000 alphawave-0.2.9/src/alphawave_agents/AgentCommandValidator.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1428 2023-06-11 19:07:37.000000 alphawave-0.2.9/src/alphawave_agents/AskCommand.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1871 2023-06-07 03:14:30.000000 alphawave-0.2.9/src/alphawave_agents/CompleteTaskCommand.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1336 2023-06-06 16:52:41.000000 alphawave-0.2.9/src/alphawave_agents/ConfirmAnswerCommand.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1425 2023-06-22 21:06:20.000000 alphawave-0.2.9/src/alphawave_agents/FinalAnswerCommand.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1509 2023-06-07 03:15:08.000000 alphawave-0.2.9/src/alphawave_agents/MathCommand.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     3130 2023-06-18 18:54:41.000000 alphawave-0.2.9/src/alphawave_agents/PromptCommand.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     3874 2023-06-23 16:34:08.000000 alphawave-0.2.9/src/alphawave_agents/SchemaBasedCommand.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     2452 2023-06-09 18:41:37.000000 alphawave-0.2.9/src/alphawave_agents/SentimentAnalysis.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     2149 2023-06-06 16:59:49.000000 alphawave-0.2.9/src/alphawave_agents/SetPropertyCommand.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)        0 2023-06-06 23:52:38.000000 alphawave-0.2.9/src/alphawave_agents/__init__.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     2134 2023-06-19 01:22:49.000000 alphawave-0.2.9/src/alphawave_agents/agentTypes.py
-drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-26 19:40:52.623031 alphawave-0.2.9/src/alphawave_pyexts/
--rw-rw-r--   0 bruce     (1000) bruce     (1000)    11096 2023-06-24 23:27:36.000000 alphawave-0.2.9/src/alphawave_pyexts/FsInference.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     7572 2023-06-25 22:36:27.000000 alphawave-0.2.9/src/alphawave_pyexts/LLMClient.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     2687 2023-06-19 22:44:59.000000 alphawave-0.2.9/src/alphawave_pyexts/SearchCommand.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)    11610 2023-06-22 19:47:31.000000 alphawave-0.2.9/src/alphawave_pyexts/chat.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     2607 2023-06-24 00:18:59.000000 alphawave-0.2.9/src/alphawave_pyexts/configuration_RW.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)    23163 2023-06-26 17:52:47.000000 alphawave-0.2.9/src/alphawave_pyexts/conversation.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     1154 2023-06-24 03:11:55.000000 alphawave-0.2.9/src/alphawave_pyexts/handler.py
-drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-26 19:40:52.623031 alphawave-0.2.9/src/alphawave_pyexts/llmsearch/
--rw-rw-r--   0 bruce     (1000) bruce     (1000)    13725 2023-06-19 22:24:29.000000 alphawave-0.2.9/src/alphawave_pyexts/llmsearch/google_search_concurrent.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)      972 2023-06-19 22:47:56.000000 alphawave-0.2.9/src/alphawave_pyexts/llmsearch/search_service.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)    47520 2023-06-24 00:15:02.000000 alphawave-0.2.9/src/alphawave_pyexts/modelling_RW.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)    12403 2023-06-26 16:54:42.000000 alphawave-0.2.9/src/alphawave_pyexts/serverUtils.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)     6684 2023-06-23 16:42:51.000000 alphawave-0.2.9/src/alphawave_pyexts/utilityV2.py
-drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-26 19:40:52.623031 alphawave-0.2.9/tests/
--rw-rw-r--   0 bruce     (1000) bruce     (1000)    14779 2023-06-07 17:09:31.000000 alphawave-0.2.9/tests/testOSClient.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)    14639 2023-06-18 18:49:14.000000 alphawave-0.2.9/tests/testOpenAiClient.py
--rw-rw-r--   0 bruce     (1000) bruce     (1000)      948 2023-06-06 20:59:59.000000 alphawave-0.2.9/tests/testSchema.py
+drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-28 02:46:39.277962 alphawave-0.3.0/
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1070 2023-06-05 21:12:30.000000 alphawave-0.3.0/LICENSE
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     9441 2023-06-28 02:46:39.277962 alphawave-0.3.0/PKG-INFO
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     8859 2023-06-18 19:15:49.000000 alphawave-0.3.0/README.md
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)      945 2023-06-28 02:46:30.000000 alphawave-0.3.0/pyproject.toml
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)       38 2023-06-28 02:46:39.277962 alphawave-0.3.0/setup.cfg
+drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-28 02:46:39.269962 alphawave-0.3.0/src/
+drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-28 02:46:39.273962 alphawave-0.3.0/src/alphawave/
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     9427 2023-06-27 18:52:28.000000 alphawave-0.3.0/src/alphawave/AlphaWave.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1370 2023-06-10 00:08:35.000000 alphawave-0.3.0/src/alphawave/Colorize.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)      740 2023-06-18 18:50:38.000000 alphawave-0.3.0/src/alphawave/DefaultResponseValidator.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     6405 2023-06-26 03:01:54.000000 alphawave-0.3.0/src/alphawave/JSONResponseValidator.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1173 2023-06-19 22:47:36.000000 alphawave-0.3.0/src/alphawave/MemoryFork.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     8905 2023-06-19 15:46:26.000000 alphawave-0.3.0/src/alphawave/OSClient.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     8940 2023-06-27 16:04:31.000000 alphawave-0.3.0/src/alphawave/OpenAIClient.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1377 2023-06-15 04:11:41.000000 alphawave-0.3.0/src/alphawave/RepairTestClient.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     3008 2023-06-15 23:14:04.000000 alphawave-0.3.0/src/alphawave/Response.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)      800 2023-06-15 04:12:01.000000 alphawave-0.3.0/src/alphawave/TestClient.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1515 2023-06-15 04:12:10.000000 alphawave-0.3.0/src/alphawave/TestClientTest.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)        0 2023-06-06 23:52:12.000000 alphawave-0.3.0/src/alphawave/__init__.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1359 2023-06-15 04:10:27.000000 alphawave-0.3.0/src/alphawave/alphawaveTypes.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     4163 2023-06-04 18:16:08.000000 alphawave-0.3.0/src/alphawave/internalTypes.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)      782 2023-06-07 21:02:29.000000 alphawave-0.3.0/src/alphawave/jsonParser.py
+drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-28 02:46:39.273962 alphawave-0.3.0/src/alphawave.egg-info/
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     9441 2023-06-28 02:46:39.000000 alphawave-0.3.0/src/alphawave.egg-info/PKG-INFO
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1758 2023-06-28 02:46:39.000000 alphawave-0.3.0/src/alphawave.egg-info/SOURCES.txt
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)        1 2023-06-28 02:46:39.000000 alphawave-0.3.0/src/alphawave.egg-info/dependency_links.txt
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)      155 2023-06-28 02:46:39.000000 alphawave-0.3.0/src/alphawave.egg-info/requires.txt
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)       44 2023-06-28 02:46:39.000000 alphawave-0.3.0/src/alphawave.egg-info/top_level.txt
+drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-28 02:46:39.273962 alphawave-0.3.0/src/alphawave_agents/
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)    16543 2023-06-28 02:17:08.000000 alphawave-0.3.0/src/alphawave_agents/Agent.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1332 2023-06-11 16:22:40.000000 alphawave-0.3.0/src/alphawave_agents/AgentCommandSection.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     2956 2023-06-19 02:42:43.000000 alphawave-0.3.0/src/alphawave_agents/AgentCommandValidator.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1428 2023-06-11 19:07:37.000000 alphawave-0.3.0/src/alphawave_agents/AskCommand.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1871 2023-06-07 03:14:30.000000 alphawave-0.3.0/src/alphawave_agents/CompleteTaskCommand.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1336 2023-06-06 16:52:41.000000 alphawave-0.3.0/src/alphawave_agents/ConfirmAnswerCommand.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1425 2023-06-22 21:06:20.000000 alphawave-0.3.0/src/alphawave_agents/FinalAnswerCommand.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1509 2023-06-07 03:15:08.000000 alphawave-0.3.0/src/alphawave_agents/MathCommand.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     3130 2023-06-18 18:54:41.000000 alphawave-0.3.0/src/alphawave_agents/PromptCommand.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     3874 2023-06-23 16:34:08.000000 alphawave-0.3.0/src/alphawave_agents/SchemaBasedCommand.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     2452 2023-06-09 18:41:37.000000 alphawave-0.3.0/src/alphawave_agents/SentimentAnalysis.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     2149 2023-06-06 16:59:49.000000 alphawave-0.3.0/src/alphawave_agents/SetPropertyCommand.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)        0 2023-06-06 23:52:38.000000 alphawave-0.3.0/src/alphawave_agents/__init__.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     2134 2023-06-19 01:22:49.000000 alphawave-0.3.0/src/alphawave_agents/agentTypes.py
+drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-28 02:46:39.273962 alphawave-0.3.0/src/alphawave_pyexts/
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)    11096 2023-06-24 23:27:36.000000 alphawave-0.3.0/src/alphawave_pyexts/FsInference.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     7791 2023-06-27 19:17:46.000000 alphawave-0.3.0/src/alphawave_pyexts/LLMClient.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     2687 2023-06-19 22:44:59.000000 alphawave-0.3.0/src/alphawave_pyexts/SearchCommand.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)    11610 2023-06-22 19:47:31.000000 alphawave-0.3.0/src/alphawave_pyexts/chat.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     2607 2023-06-24 00:18:59.000000 alphawave-0.3.0/src/alphawave_pyexts/configuration_RW.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)    23229 2023-06-27 19:16:18.000000 alphawave-0.3.0/src/alphawave_pyexts/conversation.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     1154 2023-06-24 03:11:55.000000 alphawave-0.3.0/src/alphawave_pyexts/handler.py
+drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-28 02:46:39.273962 alphawave-0.3.0/src/alphawave_pyexts/llmsearch/
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)    13725 2023-06-19 22:24:29.000000 alphawave-0.3.0/src/alphawave_pyexts/llmsearch/google_search_concurrent.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)      972 2023-06-19 22:47:56.000000 alphawave-0.3.0/src/alphawave_pyexts/llmsearch/search_service.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)    47520 2023-06-24 00:15:02.000000 alphawave-0.3.0/src/alphawave_pyexts/modelling_RW.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)    12703 2023-06-28 02:40:52.000000 alphawave-0.3.0/src/alphawave_pyexts/serverUtils.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)     6684 2023-06-23 16:42:51.000000 alphawave-0.3.0/src/alphawave_pyexts/utilityV2.py
+drwxrwxr-x   0 bruce     (1000) bruce     (1000)        0 2023-06-28 02:46:39.277962 alphawave-0.3.0/tests/
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)    14779 2023-06-07 17:09:31.000000 alphawave-0.3.0/tests/testOSClient.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)    14639 2023-06-18 18:49:14.000000 alphawave-0.3.0/tests/testOpenAiClient.py
+-rw-rw-r--   0 bruce     (1000) bruce     (1000)      948 2023-06-06 20:59:59.000000 alphawave-0.3.0/tests/testSchema.py
```

### Comparing `alphawave-0.2.9/LICENSE` & `alphawave-0.3.0/LICENSE`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/PKG-INFO` & `alphawave-0.3.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: alphawave
-Version: 0.2.9
+Version: 0.3.0
 Summary: AlphaWave - a client for interfacing with Large Language Models (LLM)
 Author-email: Steven Ickman <author@example.com>, Bruce DAmbrosio <bruce.dambrosio@gmail.com>
 Project-URL: Homepage, https://tuuyi.io/alphawave
 Project-URL: Bug Tracker, https://github.com/Stevenic/alphawave-py/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `alphawave-0.2.9/README.md` & `alphawave-0.3.0/README.md`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/pyproject.toml` & `alphawave-0.3.0/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "alphawave"
-version = "0.2.9"
+version = "0.3.0"
 authors = [
   { name="Steven Ickman", email="author@example.com" },
   { name="Bruce DAmbrosio", email="bruce.dambrosio@gmail.com" },
 ]
 
 description = "AlphaWave - a client for interfacing with Large Language Models (LLM)"
```

### Comparing `alphawave-0.2.9/src/alphawave/AlphaWave.py` & `alphawave-0.3.0/src/alphawave/AlphaWave.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,15 @@
 from typing import Callable, Dict, Optional, Any
 from dataclasses import dataclass, asdict
 from pyee import AsyncIOEventEmitter
 import readline as re
 
 from promptrix.promptrixTypes import Message, PromptFunctions, PromptSection, PromptMemory, Tokenizer
 from promptrix.ConversationHistory import ConversationHistory
+from promptrix.AssistantMessage import AssistantMessage
 from promptrix.FunctionRegistry import  FunctionRegistry
 from promptrix.GPT3Tokenizer import GPT3Tokenizer
 from promptrix.Prompt import Prompt
 from promptrix.VolatileMemory import VolatileMemory
 from promptrix.Utilities import Utilities
 
 from alphawave.alphawaveTypes import  PromptCompletionClient, PromptCompletionOptions, PromptResponse,Validation, PromptResponseValidator 
@@ -96,16 +97,16 @@
                 self.addResponseToHistory(memory, history_variable, response['message'])
                 return response
 
             if self.options.logRepairs:
                 print(Colorize.title('REPAIRING RESPONSE:'))
                 print(Colorize.output(memory))
             fork = MemoryFork(memory)
-            #self.addInputToHistory(fork, history_variable, input)
-            #self.addResponseToHistory(fork, history_variable, response['message'])
+            self.addInputToHistory(fork, history_variable, input)
+            self.addResponseToHistory(fork, history_variable, response['message'])
 
             if self.options.logRepairs:
                 print(Colorize.output(response['message']['content']))
 
             self.emit('beforeRepair', fork, functions, tokenizer, response, max_repair_attempts, validation)
             repair = self.repairResponse(fork, functions, tokenizer, response, validation, max_repair_attempts)
             if 'coroutine' in str(type(repair)).lower():
@@ -160,15 +161,16 @@
         # Add response and feedback to repair history
         self.addResponseToHistory(fork, f"{self.options.history_variable}-repair", response['message'])
         self.addInputToHistory(fork, f"{self.options.history_variable}-repair", feedback)
 
         # Append repair history to prompt
         repair_prompt = Prompt([
             prompt,
-            ConversationHistory(f"{self.options.history_variable}-repair")
+            ConversationHistory(f"{self.options.history_variable}-repair"),
+            AssistantMessage('')       # not sure all models need this, but some do, maybe doesn't hurt?
         ])
 
         # Log the repair
         if self.options.logRepairs:
             print(Colorize.value('feedback', feedback))
 
         # Ask client to complete prompt
```

### Comparing `alphawave-0.2.9/src/alphawave/Colorize.py` & `alphawave-0.3.0/src/alphawave/Colorize.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave/DefaultResponseValidator.py` & `alphawave-0.3.0/src/alphawave/DefaultResponseValidator.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave/JSONResponseValidator.py` & `alphawave-0.3.0/src/alphawave/JSONResponseValidator.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave/MemoryFork.py` & `alphawave-0.3.0/src/alphawave/MemoryFork.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave/OSClient.py` & `alphawave-0.3.0/src/alphawave/OSClient.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave/OpenAIClient.py` & `alphawave-0.3.0/src/alphawave/OpenAIClient.py`

 * *Files 1% similar despite different names*

```diff
@@ -150,12 +150,13 @@
         }
         self.addRequestHeaders(requestHeaders, self.options)
         jsonbody = asdict(body)
         keys = list(jsonbody.keys())
         for key in keys:
             if jsonbody[key] is None:
                 del jsonbody[key]
+        print(jsonbody)
         result = self._session.post(url, json=jsonbody, headers=requestHeaders)
         if result.status_code < 300:
             completion = result.json().get('choices')[0]
         return result
```

### Comparing `alphawave-0.2.9/src/alphawave/RepairTestClient.py` & `alphawave-0.3.0/src/alphawave/RepairTestClient.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave/Response.py` & `alphawave-0.3.0/src/alphawave/Response.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave/TestClient.py` & `alphawave-0.3.0/src/alphawave/TestClient.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave/TestClientTest.py` & `alphawave-0.3.0/src/alphawave/TestClientTest.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave/alphawaveTypes.py` & `alphawave-0.3.0/src/alphawave/alphawaveTypes.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave/internalTypes.py` & `alphawave-0.3.0/src/alphawave/internalTypes.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave/jsonParser.py` & `alphawave-0.3.0/src/alphawave/jsonParser.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave.egg-info/PKG-INFO` & `alphawave-0.3.0/src/alphawave.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: alphawave
-Version: 0.2.9
+Version: 0.3.0
 Summary: AlphaWave - a client for interfacing with Large Language Models (LLM)
 Author-email: Steven Ickman <author@example.com>, Bruce DAmbrosio <bruce.dambrosio@gmail.com>
 Project-URL: Homepage, https://tuuyi.io/alphawave
 Project-URL: Bug Tracker, https://github.com/Stevenic/alphawave-py/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `alphawave-0.2.9/src/alphawave.egg-info/SOURCES.txt` & `alphawave-0.3.0/src/alphawave.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_agents/Agent.py` & `alphawave-0.3.0/src/alphawave_agents/Agent.py`

 * *Files 4% similar despite different names*

```diff
@@ -9,14 +9,16 @@
 from promptrix.promptrixTypes import Message, PromptFunctions, PromptSection, PromptMemory, Tokenizer
 from promptrix.FunctionRegistry import  FunctionRegistry
 from promptrix.GroupSection import GroupSection
 from promptrix.GPT3Tokenizer import GPT3Tokenizer
 from promptrix.VolatileMemory import VolatileMemory
 from promptrix.ConversationHistory import ConversationHistory
 from promptrix.TextSection import TextSection
+from promptrix.AssistantMessage import AssistantMessage
+from promptrix.UserMessage import UserMessage
 from promptrix.Utilities import Utilities
 from promptrix.TemplateSection import TemplateSection
 from promptrix.Prompt import Prompt
 
 from alphawave.AlphaWave import AlphaWave, AlphaWaveOptions
 from alphawave.alphawaveTypes import PromptCompletionClient, PromptCompletionOptions, PromptResponse, Validation, PromptResponseValidator
 from alphawave.JSONResponseValidator import JSONResponseValidator
@@ -38,30 +40,25 @@
         "input": {
             "type": "string",
             "description": "input for command",
         }
     }
     required: list[str] = ["input"]
 
-PromptInstructionSection = TemplateSection("\n".join([
-    "Return a JSON object with your thoughts and the next command to perform",
-    "Only respond with the JSON format below and based your plan on the commands above",
-    "Response Format:",
-    '{"thoughts":{"thought":"<your current thought>","reasoning":"<self reflect on why you made this decision>","plan":"- short bulleted\n- list that conveys\n- long-term plan"},"command":{"name":"<command name>","input":{"<name>":"<value>"}}}'
-]), 'system')
-
-PromptInstructionSection_py = TemplateSection(\
+PromptInstructionSection = TemplateSection(\
 """
 Reason step by step how to answer the users query below.
 Return a JSON object with your thoughts and the next command to perform, using the following format and available commands.
 Response Format:
 
 {\"reasoning\":\"<reflections on how to construct an answerto the user query>\",\"plan\":\"concise plan for constructing answer\",\"command\":{\"name\":\"<command name of next action to perform>\",\"input\":{\"<key>\":\"<value>\"}}</s>"
 """
                                               , 'system')
+OneShot = [UserMessage('What is 3 + 4?'),
+           AssistantMessage('{"reasoning":"I\' not good at math, I\'ll use the math command", "command":{"name":"math", "input":{"code":3+4"}}')]
 
 @dataclass
 class AgentOptions:
     client: PromptCompletionClient
     context_variable: Optional[str] = None
     prompt: Union[str, list[str], PromptSection] = None
     prompt_options: PromptCompletionOptions = None
@@ -278,21 +275,26 @@
                 self.memory.set(self.options['context_variable'], state['context'])
 
             # Create prompt
             history_variable = self.get_agent_history_variable(agent_id)
             sections = [agent_prompt]
             sections.append(AgentCommandSection(self._commands))
             pis = PromptInstructionSection
-            if not (self._options['prompt_options']['model']).lower().startswith('gpt'):
-                pis = PromptInstructionSection_py
             sections.append(pis)
-            prompt = Prompt([
-                GroupSection(sections, 'system'),
-                ConversationHistory(history_variable, 1.0, True)
-            ])
+            if OneShot is not None:
+                prompt = Prompt([
+                    GroupSection(sections, 'system'),
+                    OneShot[0], OneShot[1],
+                    ConversationHistory(history_variable, 1.0, True)
+                ])
+            else:
+                prompt = Prompt([
+                    GroupSection(sections, 'system'),
+                    ConversationHistory(history_variable, 1.0, True)
+                ])
             if input:
                 prompt.sections.append(TextSection(input, 'user', -1, True, '\n', 'user'))
                 # Ensure input variable is set otherwise the history will be wrong.
                 self.memory.set(self.options['input_variable'], input)
 
 
             if execute_initial_thought and self._options['initial_thought']:
```

### Comparing `alphawave-0.2.9/src/alphawave_agents/AgentCommandSection.py` & `alphawave-0.3.0/src/alphawave_agents/AgentCommandSection.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_agents/AgentCommandValidator.py` & `alphawave-0.3.0/src/alphawave_agents/AgentCommandValidator.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_agents/AskCommand.py` & `alphawave-0.3.0/src/alphawave_agents/AskCommand.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_agents/CompleteTaskCommand.py` & `alphawave-0.3.0/src/alphawave_agents/CompleteTaskCommand.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_agents/ConfirmAnswerCommand.py` & `alphawave-0.3.0/src/alphawave_agents/ConfirmAnswerCommand.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_agents/FinalAnswerCommand.py` & `alphawave-0.3.0/src/alphawave_agents/FinalAnswerCommand.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_agents/MathCommand.py` & `alphawave-0.3.0/src/alphawave_agents/MathCommand.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_agents/PromptCommand.py` & `alphawave-0.3.0/src/alphawave_agents/PromptCommand.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_agents/SchemaBasedCommand.py` & `alphawave-0.3.0/src/alphawave_agents/SchemaBasedCommand.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_agents/SentimentAnalysis.py` & `alphawave-0.3.0/src/alphawave_agents/SentimentAnalysis.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_agents/SetPropertyCommand.py` & `alphawave-0.3.0/src/alphawave_agents/SetPropertyCommand.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_agents/agentTypes.py` & `alphawave-0.3.0/src/alphawave_agents/agentTypes.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_pyexts/FsInference.py` & `alphawave-0.3.0/src/alphawave_pyexts/FsInference.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_pyexts/LLMClient.py` & `alphawave-0.3.0/src/alphawave_pyexts/LLMClient.py`

 * *Files 2% similar despite different names*

```diff
@@ -21,15 +21,15 @@
     Conversation(
         name="falcon_instruct",
         system="",
         roles=("User", "Assistant"),
         messages=(),
         offset=0,
         sep_style=SeparatorStyle.ADD_COLON_SINGLE,
-        stop_str=["User:"],
+        stop_str=["User:", "Assistant:"],
         stop_token_ids=[11],
         sep="\n",
         sep2="<|endoftext|>",
         first_msg_no_role=False,
     )
 )
 cv.register_conv_template(Conversation(
@@ -85,14 +85,15 @@
     ASSISTANT_PREFIX = conv.roles[1]
     SYSTEM_PREFIX = conv.system
     
     # set this so client can check for run-on, although this test should pbly be here!
     if format:
         prime=''
         for msg_idx, msg in enumerate(messages):
+            #print(msg_idx, msg)
             role = msg['role']
             ### conv.system is a prompt msg, and will be inserted as the first entry by conv.get_prompt()
             if role.lower() == 'system' and msg_idx==0:
                 if len(conv.system)>0:
                     prime = msg['content']+' '+conv.system
                 else:
                     prime = msg['content']
@@ -101,17 +102,17 @@
                     prime=''
             elif role.lower() == 'user' or role.lower() == 'system' or role == conv.roles[0]:
                 role_index = 0
                 conv.append_message(conv.roles[role_index], msg['content'])
             else:
                 role_index = 1
                 conv.append_message(conv.roles[role_index], msg['content'])
-            
-        #priming prompt
-        conv.append_message(conv.roles[1], '')
+                #print(conv.messages[-1])
+        #priming prompt - removed, user will add?
+        #conv.append_message(conv.roles[1], '')
         prompt = conv.get_prompt()
         if len(prime) > 0:
             prompt = prime+conv.sep+prompt
     else:
         prompt = messages
     prompt = re.sub('\n{3,}', '\n\n', prompt)
     #print(f'***** llm output prompt string {prompt}')
@@ -145,18 +146,20 @@
                 s = s.replace('</s>', '')
                 s = s.replace('<s>', '')
                 if tkdisplay is not None:
                     tkdisplay.insert(tk.END, s)
                     if tkroot is not None:
                         tkroot.update()
                 response += s
-                sep2_idx = response.find(conv.sep2)
-                if sep2_idx >= 0:
-                    response = response[sep2_idx:]
-                    break
+                # not sure why sep2 code below is here???
+                if conv.sep2 is not None:
+                    sep2_idx = response.find(conv.sep2)
+                    if sep2_idx >= 0:
+                        response = response[sep2_idx:]
+                        break
         client_socket.close()  # close the connection
         #check for run on hallucination in response 
         runon_idx = response.find(conv.roles[0])
         if runon_idx > 0:
             response = response[:runon_idx]
         return response
     except:
```

### Comparing `alphawave-0.2.9/src/alphawave_pyexts/SearchCommand.py` & `alphawave-0.3.0/src/alphawave_pyexts/SearchCommand.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_pyexts/chat.py` & `alphawave-0.3.0/src/alphawave_pyexts/chat.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_pyexts/configuration_RW.py` & `alphawave-0.3.0/src/alphawave_pyexts/configuration_RW.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_pyexts/conversation.py` & `alphawave-0.3.0/src/alphawave_pyexts/conversation.py`

 * *Files 0% similar despite different names*

```diff
@@ -458,20 +458,20 @@
         sep="</s>",
     )
 )
 
 # ChatGPT default template
 register_conv_template(
     Conversation(
-        name="chatgpt",
+        name="gpt-3.5-turbo",
         system="",
         roles=("user", "assistant"),
         messages=(),
         offset=0,
-        sep_style=None,
+        sep_style=SeparatorStyle.NO_COLON_SINGLE,
         sep=None,
     )
 )
 
 # Claude default template
 register_conv_template(
     Conversation(
@@ -496,14 +496,15 @@
 - You are more than just an information source, you are also able to write poetry, short stories, and make jokes.
 """,
         roles=("<|im_start|>user", "<|im_start|>assistant", "<|im_start|>system"),
         messages=(),
         offset=0,
         sep_style=SeparatorStyle.ADD_NEW_LINE_SINGLE,
         sep="<|im_end|>",
+        sep2='',
         stop_token_ids=[50278, 0],
     )
 )
 # MPT instruct template as per HG MPT 30b instruct model page
 register_conv_template(
     Conversation(
         name="mpt_instruct",
@@ -511,14 +512,15 @@
 
 """,
         roles=("### Instruction", "### Response",""),
         messages=(),
         offset=0,
         sep_style=SeparatorStyle.ADD_NEW_LINE_SINGLE,
         sep="\n",
+        sep2='',
         stop_token_ids=[50278, 0],
     )
 )
 
 # Bard default template
 # Reference: https://github.com/google/generative-ai-python/blob/9c99bcb474a991a97a2e7d62fcdb52db7ce40729/google/generativeai/discuss.py#L150
 #            https://github.com/google/generative-ai-python/blob/9c99bcb474a991a97a2e7d62fcdb52db7ce40729/google/generativeai/discuss.py#L40
```

### Comparing `alphawave-0.2.9/src/alphawave_pyexts/handler.py` & `alphawave-0.3.0/src/alphawave_pyexts/handler.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_pyexts/llmsearch/google_search_concurrent.py` & `alphawave-0.3.0/src/alphawave_pyexts/llmsearch/google_search_concurrent.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_pyexts/llmsearch/search_service.py` & `alphawave-0.3.0/src/alphawave_pyexts/llmsearch/search_service.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_pyexts/modelling_RW.py` & `alphawave-0.3.0/src/alphawave_pyexts/modelling_RW.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/src/alphawave_pyexts/serverUtils.py` & `alphawave-0.3.0/src/alphawave_pyexts/serverUtils.py`

 * *Files 2% similar despite different names*

```diff
@@ -6,14 +6,15 @@
 import os
 from threading import Event, Thread
 from uuid import uuid4
 import requests, socket
 from queue import Queue
 import json
 import sys
+import gc
 import time
 import string
 import traceback
 from collections.abc import Iterable
 
 # Load the model.
 
@@ -114,16 +115,16 @@
     else:
       printable_text = ""
     self.next_tokens_are_prompt = True
     self.on_finalized_text(printable_text, stream_end=True)
 
   def on_finalized_text(self, text: str, stream_end: bool = False):
       """Put the new text in the queue. If the stream is ending, also put a stop signal in the queue."""
-      filtered_text = filter(lambda x: x in string.printable, text)
-      self.text_queue.put(text, timeout=self.timeout)
+      filtered_text = "".join(filter(lambda x: x in string.printable, text))
+      self.text_queue.put(filtered_text, timeout=self.timeout)
       if stream_end:
         self.text_queue.put(self.stop_signal, timeout=self.timeout)
 
   def __iter__(self):
     return self
 
   def __next__(self):
@@ -264,20 +265,20 @@
             server_socket.setsockopt(socket.SOL_SOCKET, socket.SO_REUSEADDR, 1)
             server_socket.bind((host, port))  # bind host address and port together
             server_socket.settimeout(3)
 
             while True:
                 try:
                     conn = None
-                    server_socket.listen(10)
+                    server_socket.listen(30)
                     #print("waiting...")
                     try:
                       conn, address = server_socket.accept()  # accept new connection
                     except Exception:
-                      pass
+                        pass
                     if conn is None: continue
                     print("Connection from: " + str(address))
                     query_string = ''
                     while True:
                       s = conn.recv(1024)
                       if s is None or not s:
                         break
@@ -287,26 +288,33 @@
                         break
                       else:
                         query_string += s.decode('utf-8')
                     print("got string:", query_string)
                     if query_string is not None and len(query_string) > 0:
                         message_j = json.loads(query_string)
                         submit(query_string, model=model, tokenizer=tokenizer, pipeline=pipeline, stop_event=stop_event, conn=conn, stop_str=stop_str)
+                        gc.collect()
+                        torch.cuda.empty_cache()
                         print('sending termination')
                         conn.sendall(b'x00xff')
+                        time.sleep(0.5)
                     if conn is not None: conn.close()
                 except TimeoutError:
                   #traceback.print_exc()
-                  if conn is not None: conn.close()
+                    if conn is not None:
+                        conn.sendall(b'x00xff')
+                        time.sleep(0.5)
+                        conn.close()
                 except KeyboardInterrupt:
                   print("idle loop interrrupt")
                   traceback.print_exc()
                   sys.exit(0)
         print("resetting socket")
         server_socket.close()
       except BrokenPipeError:
+        traceback.print_exc()
         pass
       except KeyboardInterrupt:
         sys.exit(0)
       except Exception:
         traceback.print_exc()
```

### Comparing `alphawave-0.2.9/src/alphawave_pyexts/utilityV2.py` & `alphawave-0.3.0/src/alphawave_pyexts/utilityV2.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/tests/testOSClient.py` & `alphawave-0.3.0/tests/testOSClient.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/tests/testOpenAiClient.py` & `alphawave-0.3.0/tests/testOpenAiClient.py`

 * *Files identical despite different names*

### Comparing `alphawave-0.2.9/tests/testSchema.py` & `alphawave-0.3.0/tests/testSchema.py`

 * *Files identical despite different names*

