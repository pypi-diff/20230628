# Comparing `tmp/types-aiobotocore-lite-2.5.0.post2.tar.gz` & `tmp/types-aiobotocore-lite-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "types-aiobotocore-lite-2.5.0.post2.tar", last modified: Fri Mar 31 00:10:15 2023, max compression
+gzip compressed data, was "types-aiobotocore-lite-2.5.1.tar", last modified: Wed Jun 28 01:43:06 2023, max compression
```

## Comparing `types-aiobotocore-lite-2.5.0.post2.tar` & `types-aiobotocore-lite-2.5.1.tar`

### file list

```diff
@@ -1,38 +1,38 @@
-drwxr-xr-x   0 vlad      (1000) vlad      (1000)        0 2023-03-31 00:10:15.684286 types-aiobotocore-lite-2.5.0.post2/
--rw-r--r--   0 vlad      (1000) vlad      (1000)     1070 2023-03-31 00:10:09.000000 types-aiobotocore-lite-2.5.0.post2/LICENSE
--rw-r--r--   0 vlad      (1000) vlad      (1000)    79876 2023-03-31 00:10:15.684286 types-aiobotocore-lite-2.5.0.post2/PKG-INFO
--rw-r--r--   0 vlad      (1000) vlad      (1000)    68706 2023-03-31 00:10:09.000000 types-aiobotocore-lite-2.5.0.post2/README.md
-drwxr-xr-x   0 vlad      (1000) vlad      (1000)        0 2023-03-31 00:10:15.684286 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/
--rw-r--r--   0 vlad      (1000) vlad      (1000)       17 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/__init__.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)     1466 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/args.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)      175 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/awsrequest.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)     1316 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/client.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)      300 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/config.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)      399 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/configprovider.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)     5528 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/credentials.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)      477 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/discovery.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)     1467 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/endpoint.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)      377 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/eventstream.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)      595 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/handlers.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)      261 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/hooks.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)      643 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/httpchecksum.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)      968 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/httpsession.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)      722 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/paginate.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)      745 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/parsers.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)        0 2023-03-31 00:10:09.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/py.typed
--rw-r--r--   0 vlad      (1000) vlad      (1000)     1389 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/response.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)      819 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/retryhandler.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)     2695 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/session.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)     2182 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/signers.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)     1803 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/utils.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)       65 2023-03-31 00:10:09.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/version.py
--rw-r--r--   0 vlad      (1000) vlad      (1000)      581 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/waiter.pyi
--rw-r--r--   0 vlad      (1000) vlad      (1000)       38 2023-03-31 00:10:15.684286 types-aiobotocore-lite-2.5.0.post2/setup.cfg
--rw-r--r--   0 vlad      (1000) vlad      (1000)    48257 2023-03-31 00:10:08.000000 types-aiobotocore-lite-2.5.0.post2/setup.py
-drwxr-xr-x   0 vlad      (1000) vlad      (1000)        0 2023-03-31 00:10:15.684286 types-aiobotocore-lite-2.5.0.post2/types_aiobotocore_lite.egg-info/
--rw-r--r--   0 vlad      (1000) vlad      (1000)    79876 2023-03-31 00:10:15.000000 types-aiobotocore-lite-2.5.0.post2/types_aiobotocore_lite.egg-info/PKG-INFO
--rw-r--r--   0 vlad      (1000) vlad      (1000)     1045 2023-03-31 00:10:15.000000 types-aiobotocore-lite-2.5.0.post2/types_aiobotocore_lite.egg-info/SOURCES.txt
--rw-r--r--   0 vlad      (1000) vlad      (1000)        1 2023-03-31 00:10:15.000000 types-aiobotocore-lite-2.5.0.post2/types_aiobotocore_lite.egg-info/dependency_links.txt
--rw-r--r--   0 vlad      (1000) vlad      (1000)        1 2023-03-31 00:10:15.000000 types-aiobotocore-lite-2.5.0.post2/types_aiobotocore_lite.egg-info/not-zip-safe
--rw-r--r--   0 vlad      (1000) vlad      (1000)    35675 2023-03-31 00:10:15.000000 types-aiobotocore-lite-2.5.0.post2/types_aiobotocore_lite.egg-info/requires.txt
--rw-r--r--   0 vlad      (1000) vlad      (1000)       18 2023-03-31 00:10:15.000000 types-aiobotocore-lite-2.5.0.post2/types_aiobotocore_lite.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.614094 types-aiobotocore-lite-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1070 2023-06-28 01:25:38.000000 types-aiobotocore-lite-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)    81849 2023-06-28 01:43:06.614094 types-aiobotocore-lite-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    70395 2023-06-28 01:25:38.000000 types-aiobotocore-lite-2.5.1/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.614094 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/__init__.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1466 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/args.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      175 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/awsrequest.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1316 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/client.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      300 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/config.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      399 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/configprovider.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     5528 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/credentials.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      477 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/discovery.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1467 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/endpoint.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      377 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/eventstream.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      595 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/handlers.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      261 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/hooks.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      643 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/httpchecksum.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      968 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/httpsession.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      722 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/paginate.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      745 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/parsers.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 01:25:38.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/py.typed
+-rw-r--r--   0 runner    (1001) docker     (123)     1389 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/response.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)      819 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/retryhandler.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2695 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/session.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     2182 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/signers.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)     1803 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/utils.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 01:25:38.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/version.py
+-rw-r--r--   0 runner    (1001) docker     (123)      581 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/aiobotocore-stubs/waiter.pyi
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 01:43:06.614094 types-aiobotocore-lite-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)    49563 2023-06-28 01:25:37.000000 types-aiobotocore-lite-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 01:43:06.614094 types-aiobotocore-lite-2.5.1/types_aiobotocore_lite.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    81849 2023-06-28 01:43:06.000000 types-aiobotocore-lite-2.5.1/types_aiobotocore_lite.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1045 2023-06-28 01:43:06.000000 types-aiobotocore-lite-2.5.1/types_aiobotocore_lite.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-lite-2.5.1/types_aiobotocore_lite.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 01:43:06.000000 types-aiobotocore-lite-2.5.1/types_aiobotocore_lite.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)    36717 2023-06-28 01:43:06.000000 types-aiobotocore-lite-2.5.1/types_aiobotocore_lite.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       18 2023-06-28 01:43:06.000000 types-aiobotocore-lite-2.5.1/types_aiobotocore_lite.egg-info/top_level.txt
```

### Comparing `types-aiobotocore-lite-2.5.0.post2/LICENSE` & `types-aiobotocore-lite-2.5.1/LICENSE`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/PKG-INFO` & `types-aiobotocore-lite-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lite
-Version: 2.5.0.post2
-Summary: Type annotations for aiobotocore 2.5.0 generated with mypy-boto3-builder 7.14.5
+Version: 2.5.1
+Summary: Type annotations for aiobotocore 2.5.1 generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -88,14 +88,15 @@
 Provides-Extra: cloudwatch
 Provides-Extra: codeartifact
 Provides-Extra: codebuild
 Provides-Extra: codecatalyst
 Provides-Extra: codecommit
 Provides-Extra: codedeploy
 Provides-Extra: codeguru-reviewer
+Provides-Extra: codeguru-security
 Provides-Extra: codeguruprofiler
 Provides-Extra: codepipeline
 Provides-Extra: codestar
 Provides-Extra: codestar-connections
 Provides-Extra: codestar-notifications
 Provides-Extra: cognito-identity
 Provides-Extra: cognito-idp
@@ -174,14 +175,15 @@
 Provides-Extra: honeycode
 Provides-Extra: iam
 Provides-Extra: identitystore
 Provides-Extra: imagebuilder
 Provides-Extra: importexport
 Provides-Extra: inspector
 Provides-Extra: inspector2
+Provides-Extra: internetmonitor
 Provides-Extra: iot
 Provides-Extra: iot-data
 Provides-Extra: iot-jobs-data
 Provides-Extra: iot-roborunner
 Provides-Extra: iot1click-devices
 Provides-Extra: iot1click-projects
 Provides-Extra: iotanalytics
@@ -192,14 +194,15 @@
 Provides-Extra: iotfleetwise
 Provides-Extra: iotsecuretunneling
 Provides-Extra: iotsitewise
 Provides-Extra: iotthingsgraph
 Provides-Extra: iottwinmaker
 Provides-Extra: iotwireless
 Provides-Extra: ivs
+Provides-Extra: ivs-realtime
 Provides-Extra: ivschat
 Provides-Extra: kafka
 Provides-Extra: kafkaconnect
 Provides-Extra: kendra
 Provides-Extra: kendra-ranking
 Provides-Extra: keyspaces
 Provides-Extra: kinesis
@@ -235,14 +238,15 @@
 Provides-Extra: marketplace-entitlement
 Provides-Extra: marketplacecommerceanalytics
 Provides-Extra: mediaconnect
 Provides-Extra: mediaconvert
 Provides-Extra: medialive
 Provides-Extra: mediapackage
 Provides-Extra: mediapackage-vod
+Provides-Extra: mediapackagev2
 Provides-Extra: mediastore
 Provides-Extra: mediastore-data
 Provides-Extra: mediatailor
 Provides-Extra: memorydb
 Provides-Extra: meteringmarketplace
 Provides-Extra: mgh
 Provides-Extra: mgn
@@ -261,16 +265,19 @@
 Provides-Extra: oam
 Provides-Extra: omics
 Provides-Extra: opensearch
 Provides-Extra: opensearchserverless
 Provides-Extra: opsworks
 Provides-Extra: opsworkscm
 Provides-Extra: organizations
+Provides-Extra: osis
 Provides-Extra: outposts
 Provides-Extra: panorama
+Provides-Extra: payment-cryptography
+Provides-Extra: payment-cryptography-data
 Provides-Extra: personalize
 Provides-Extra: personalize-events
 Provides-Extra: personalize-runtime
 Provides-Extra: pi
 Provides-Extra: pinpoint
 Provides-Extra: pinpoint-email
 Provides-Extra: pinpoint-sms-voice
@@ -354,15 +361,17 @@
 Provides-Extra: textract
 Provides-Extra: timestream-query
 Provides-Extra: timestream-write
 Provides-Extra: tnb
 Provides-Extra: transcribe
 Provides-Extra: transfer
 Provides-Extra: translate
+Provides-Extra: verifiedpermissions
 Provides-Extra: voice-id
+Provides-Extra: vpc-lattice
 Provides-Extra: waf
 Provides-Extra: waf-regional
 Provides-Extra: wafv2
 Provides-Extra: wellarchitected
 Provides-Extra: wisdom
 Provides-Extra: workdocs
 Provides-Extra: worklink
@@ -381,15 +390,15 @@
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lite.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lite)
 [![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lite?color=blue)](https://pypistats.org/packages/types-aiobotocore-lite)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore 2.5.0](https://github.com/aio-libs/aiobotocore) compatible with
+[aiobotocore 2.5.1](https://github.com/aio-libs/aiobotocore) compatible with
 [VSCode](https://code.visualstudio.com/),
 [PyCharm](https://www.jetbrains.com/pycharm/),
 [Emacs](https://www.gnu.org/software/emacs/),
 [Sublime Text](https://www.sublimetext.com/),
 [mypy](https://github.com/python/mypy),
 [pyright](https://github.com/microsoft/pyright) and other tools.
 
@@ -669,15 +678,15 @@
 in [mypy-boto3-builder](https://github.com/youtype/mypy_boto3_builder/issues/)
 repository.
 
 <a id="submodules"></a>
 
 ## Submodules
 
-- `types-aiobotocore-lite[all]` - Type annotations for all 340 services.
+- `types-aiobotocore-lite[all]` - Type annotations for all 349 services.
 - `types-aiobotocore-lite[essential]` - Type annotations for
   [CloudFormation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/),
   [DynamoDB](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/),
   [EC2](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ec2/),
   [Lambda](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/),
   [RDS](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/),
   [S3](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/)
@@ -865,14 +874,17 @@
   service.
 - `types-aiobotocore-lite[codedeploy]` - Type annotations for
   [CodeDeploy](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/)
   service.
 - `types-aiobotocore-lite[codeguru-reviewer]` - Type annotations for
   [CodeGuruReviewer](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/)
   service.
+- `types-aiobotocore-lite[codeguru-security]` - Type annotations for
+  [CodeGuruSecurity](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_security/)
+  service.
 - `types-aiobotocore-lite[codeguruprofiler]` - Type annotations for
   [CodeGuruProfiler](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/)
   service.
 - `types-aiobotocore-lite[codepipeline]` - Type annotations for
   [CodePipeline](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/)
   service.
 - `types-aiobotocore-lite[codestar]` - Type annotations for
@@ -1123,14 +1135,17 @@
   service.
 - `types-aiobotocore-lite[inspector]` - Type annotations for
   [Inspector](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/)
   service.
 - `types-aiobotocore-lite[inspector2]` - Type annotations for
   [Inspector2](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector2/)
   service.
+- `types-aiobotocore-lite[internetmonitor]` - Type annotations for
+  [CloudWatchInternetMonitor](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_internetmonitor/)
+  service.
 - `types-aiobotocore-lite[iot]` - Type annotations for
   [IoT](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/)
   service.
 - `types-aiobotocore-lite[iot-data]` - Type annotations for
   [IoTDataPlane](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/)
   service.
 - `types-aiobotocore-lite[iot-jobs-data]` - Type annotations for
@@ -1177,14 +1192,17 @@
   service.
 - `types-aiobotocore-lite[iotwireless]` - Type annotations for
   [IoTWireless](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/)
   service.
 - `types-aiobotocore-lite[ivs]` - Type annotations for
   [IVS](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/)
   service.
+- `types-aiobotocore-lite[ivs-realtime]` - Type annotations for
+  [ivsrealtime](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs_realtime/)
+  service.
 - `types-aiobotocore-lite[ivschat]` - Type annotations for
   [ivschat](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat/)
   service.
 - `types-aiobotocore-lite[kafka]` - Type annotations for
   [Kafka](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafka/)
   service.
 - `types-aiobotocore-lite[kafkaconnect]` - Type annotations for
@@ -1308,14 +1326,17 @@
   service.
 - `types-aiobotocore-lite[mediapackage]` - Type annotations for
   [MediaPackage](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/)
   service.
 - `types-aiobotocore-lite[mediapackage-vod]` - Type annotations for
   [MediaPackageVod](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/)
   service.
+- `types-aiobotocore-lite[mediapackagev2]` - Type annotations for
+  [mediapackagev2](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackagev2/)
+  service.
 - `types-aiobotocore-lite[mediastore]` - Type annotations for
   [MediaStore](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/)
   service.
 - `types-aiobotocore-lite[mediastore-data]` - Type annotations for
   [MediaStoreData](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/)
   service.
 - `types-aiobotocore-lite[mediatailor]` - Type annotations for
@@ -1387,20 +1408,29 @@
   service.
 - `types-aiobotocore-lite[opsworkscm]` - Type annotations for
   [OpsWorksCM](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/)
   service.
 - `types-aiobotocore-lite[organizations]` - Type annotations for
   [Organizations](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/)
   service.
+- `types-aiobotocore-lite[osis]` - Type annotations for
+  [OpenSearchIngestion](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_osis/)
+  service.
 - `types-aiobotocore-lite[outposts]` - Type annotations for
   [Outposts](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts/)
   service.
 - `types-aiobotocore-lite[panorama]` - Type annotations for
   [Panorama](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama/)
   service.
+- `types-aiobotocore-lite[payment-cryptography]` - Type annotations for
+  [PaymentCryptographyControlPlane](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_payment_cryptography/)
+  service.
+- `types-aiobotocore-lite[payment-cryptography-data]` - Type annotations for
+  [PaymentCryptographyDataPlane](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_payment_cryptography_data/)
+  service.
 - `types-aiobotocore-lite[personalize]` - Type annotations for
   [Personalize](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/)
   service.
 - `types-aiobotocore-lite[personalize-events]` - Type annotations for
   [PersonalizeEvents](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_events/)
   service.
 - `types-aiobotocore-lite[personalize-runtime]` - Type annotations for
@@ -1668,17 +1698,23 @@
   service.
 - `types-aiobotocore-lite[transfer]` - Type annotations for
   [Transfer](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/)
   service.
 - `types-aiobotocore-lite[translate]` - Type annotations for
   [Translate](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/)
   service.
+- `types-aiobotocore-lite[verifiedpermissions]` - Type annotations for
+  [VerifiedPermissions](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_verifiedpermissions/)
+  service.
 - `types-aiobotocore-lite[voice-id]` - Type annotations for
   [VoiceID](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/)
   service.
+- `types-aiobotocore-lite[vpc-lattice]` - Type annotations for
+  [VPCLattice](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_vpc_lattice/)
+  service.
 - `types-aiobotocore-lite[waf]` - Type annotations for
   [WAF](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_waf/)
   service.
 - `types-aiobotocore-lite[waf-regional]` - Type annotations for
   [WAFRegional](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_waf_regional/)
   service.
 - `types-aiobotocore-lite[wafv2]` - Type annotations for
```

### Comparing `types-aiobotocore-lite-2.5.0.post2/README.md` & `types-aiobotocore-lite-2.5.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lite.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lite)
 [![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lite?color=blue)](https://pypistats.org/packages/types-aiobotocore-lite)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore 2.5.0](https://github.com/aio-libs/aiobotocore) compatible with
+[aiobotocore 2.5.1](https://github.com/aio-libs/aiobotocore) compatible with
 [VSCode](https://code.visualstudio.com/),
 [PyCharm](https://www.jetbrains.com/pycharm/),
 [Emacs](https://www.gnu.org/software/emacs/),
 [Sublime Text](https://www.sublimetext.com/),
 [mypy](https://github.com/python/mypy),
 [pyright](https://github.com/microsoft/pyright) and other tools.
 
@@ -294,15 +294,15 @@
 in [mypy-boto3-builder](https://github.com/youtype/mypy_boto3_builder/issues/)
 repository.
 
 <a id="submodules"></a>
 
 ## Submodules
 
-- `types-aiobotocore-lite[all]` - Type annotations for all 340 services.
+- `types-aiobotocore-lite[all]` - Type annotations for all 349 services.
 - `types-aiobotocore-lite[essential]` - Type annotations for
   [CloudFormation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/),
   [DynamoDB](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/),
   [EC2](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ec2/),
   [Lambda](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/),
   [RDS](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/),
   [S3](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/)
@@ -490,14 +490,17 @@
   service.
 - `types-aiobotocore-lite[codedeploy]` - Type annotations for
   [CodeDeploy](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/)
   service.
 - `types-aiobotocore-lite[codeguru-reviewer]` - Type annotations for
   [CodeGuruReviewer](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/)
   service.
+- `types-aiobotocore-lite[codeguru-security]` - Type annotations for
+  [CodeGuruSecurity](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_security/)
+  service.
 - `types-aiobotocore-lite[codeguruprofiler]` - Type annotations for
   [CodeGuruProfiler](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/)
   service.
 - `types-aiobotocore-lite[codepipeline]` - Type annotations for
   [CodePipeline](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/)
   service.
 - `types-aiobotocore-lite[codestar]` - Type annotations for
@@ -748,14 +751,17 @@
   service.
 - `types-aiobotocore-lite[inspector]` - Type annotations for
   [Inspector](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/)
   service.
 - `types-aiobotocore-lite[inspector2]` - Type annotations for
   [Inspector2](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector2/)
   service.
+- `types-aiobotocore-lite[internetmonitor]` - Type annotations for
+  [CloudWatchInternetMonitor](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_internetmonitor/)
+  service.
 - `types-aiobotocore-lite[iot]` - Type annotations for
   [IoT](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/)
   service.
 - `types-aiobotocore-lite[iot-data]` - Type annotations for
   [IoTDataPlane](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/)
   service.
 - `types-aiobotocore-lite[iot-jobs-data]` - Type annotations for
@@ -802,14 +808,17 @@
   service.
 - `types-aiobotocore-lite[iotwireless]` - Type annotations for
   [IoTWireless](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/)
   service.
 - `types-aiobotocore-lite[ivs]` - Type annotations for
   [IVS](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/)
   service.
+- `types-aiobotocore-lite[ivs-realtime]` - Type annotations for
+  [ivsrealtime](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs_realtime/)
+  service.
 - `types-aiobotocore-lite[ivschat]` - Type annotations for
   [ivschat](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat/)
   service.
 - `types-aiobotocore-lite[kafka]` - Type annotations for
   [Kafka](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafka/)
   service.
 - `types-aiobotocore-lite[kafkaconnect]` - Type annotations for
@@ -933,14 +942,17 @@
   service.
 - `types-aiobotocore-lite[mediapackage]` - Type annotations for
   [MediaPackage](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/)
   service.
 - `types-aiobotocore-lite[mediapackage-vod]` - Type annotations for
   [MediaPackageVod](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/)
   service.
+- `types-aiobotocore-lite[mediapackagev2]` - Type annotations for
+  [mediapackagev2](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackagev2/)
+  service.
 - `types-aiobotocore-lite[mediastore]` - Type annotations for
   [MediaStore](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/)
   service.
 - `types-aiobotocore-lite[mediastore-data]` - Type annotations for
   [MediaStoreData](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/)
   service.
 - `types-aiobotocore-lite[mediatailor]` - Type annotations for
@@ -1012,20 +1024,29 @@
   service.
 - `types-aiobotocore-lite[opsworkscm]` - Type annotations for
   [OpsWorksCM](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/)
   service.
 - `types-aiobotocore-lite[organizations]` - Type annotations for
   [Organizations](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/)
   service.
+- `types-aiobotocore-lite[osis]` - Type annotations for
+  [OpenSearchIngestion](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_osis/)
+  service.
 - `types-aiobotocore-lite[outposts]` - Type annotations for
   [Outposts](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts/)
   service.
 - `types-aiobotocore-lite[panorama]` - Type annotations for
   [Panorama](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama/)
   service.
+- `types-aiobotocore-lite[payment-cryptography]` - Type annotations for
+  [PaymentCryptographyControlPlane](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_payment_cryptography/)
+  service.
+- `types-aiobotocore-lite[payment-cryptography-data]` - Type annotations for
+  [PaymentCryptographyDataPlane](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_payment_cryptography_data/)
+  service.
 - `types-aiobotocore-lite[personalize]` - Type annotations for
   [Personalize](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/)
   service.
 - `types-aiobotocore-lite[personalize-events]` - Type annotations for
   [PersonalizeEvents](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_events/)
   service.
 - `types-aiobotocore-lite[personalize-runtime]` - Type annotations for
@@ -1293,17 +1314,23 @@
   service.
 - `types-aiobotocore-lite[transfer]` - Type annotations for
   [Transfer](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/)
   service.
 - `types-aiobotocore-lite[translate]` - Type annotations for
   [Translate](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/)
   service.
+- `types-aiobotocore-lite[verifiedpermissions]` - Type annotations for
+  [VerifiedPermissions](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_verifiedpermissions/)
+  service.
 - `types-aiobotocore-lite[voice-id]` - Type annotations for
   [VoiceID](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/)
   service.
+- `types-aiobotocore-lite[vpc-lattice]` - Type annotations for
+  [VPCLattice](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_vpc_lattice/)
+  service.
 - `types-aiobotocore-lite[waf]` - Type annotations for
   [WAF](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_waf/)
   service.
 - `types-aiobotocore-lite[waf-regional]` - Type annotations for
   [WAFRegional](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_waf_regional/)
   service.
 - `types-aiobotocore-lite[wafv2]` - Type annotations for
```

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/args.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/args.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/client.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/client.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/credentials.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/credentials.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/endpoint.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/endpoint.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/handlers.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/handlers.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/httpchecksum.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/httpchecksum.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/httpsession.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/httpsession.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/paginate.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/paginate.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/parsers.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/parsers.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/response.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/response.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/retryhandler.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/retryhandler.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/session.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/session.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/signers.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/signers.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/utils.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/utils.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/aiobotocore-stubs/waiter.pyi` & `types-aiobotocore-lite-2.5.1/aiobotocore-stubs/waiter.pyi`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/setup.py` & `types-aiobotocore-lite-2.5.1/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -6,21 +6,21 @@
 from setuptools import setup
 
 LONG_DESCRIPTION = (Path(__file__).parent / "README.md").read_text()
 
 
 setup(
     name="types-aiobotocore-lite",
-    version="2.5.0.post2",
+    version="2.5.1",
     packages=["aiobotocore-stubs"],
     url="https://github.com/youtype/mypy_boto3_builder",
     license="MIT License",
     author="Vlad Emelianov",
     author_email="vlad.emelianov.nz@gmail.com",
-    description="Type annotations for aiobotocore 2.5.0 generated with mypy-boto3-builder 7.14.5",
+    description="Type annotations for aiobotocore 2.5.1 generated with mypy-boto3-builder 7.14.5",
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Intended Audience :: Developers",
         "Environment :: Console",
         "License :: OSI Approved :: MIT License",
         "Natural Language :: English",
         "Operating System :: OS Independent",
@@ -110,14 +110,15 @@
             "types-aiobotocore-cloudwatch>=2.5.0, <2.6.0",
             "types-aiobotocore-codeartifact>=2.5.0, <2.6.0",
             "types-aiobotocore-codebuild>=2.5.0, <2.6.0",
             "types-aiobotocore-codecatalyst>=2.5.0, <2.6.0",
             "types-aiobotocore-codecommit>=2.5.0, <2.6.0",
             "types-aiobotocore-codedeploy>=2.5.0, <2.6.0",
             "types-aiobotocore-codeguru-reviewer>=2.5.0, <2.6.0",
+            "types-aiobotocore-codeguru-security>=2.5.0, <2.6.0",
             "types-aiobotocore-codeguruprofiler>=2.5.0, <2.6.0",
             "types-aiobotocore-codepipeline>=2.5.0, <2.6.0",
             "types-aiobotocore-codestar>=2.5.0, <2.6.0",
             "types-aiobotocore-codestar-connections>=2.5.0, <2.6.0",
             "types-aiobotocore-codestar-notifications>=2.5.0, <2.6.0",
             "types-aiobotocore-cognito-identity>=2.5.0, <2.6.0",
             "types-aiobotocore-cognito-idp>=2.5.0, <2.6.0",
@@ -196,14 +197,15 @@
             "types-aiobotocore-honeycode>=2.5.0, <2.6.0",
             "types-aiobotocore-iam>=2.5.0, <2.6.0",
             "types-aiobotocore-identitystore>=2.5.0, <2.6.0",
             "types-aiobotocore-imagebuilder>=2.5.0, <2.6.0",
             "types-aiobotocore-importexport>=2.5.0, <2.6.0",
             "types-aiobotocore-inspector>=2.5.0, <2.6.0",
             "types-aiobotocore-inspector2>=2.5.0, <2.6.0",
+            "types-aiobotocore-internetmonitor>=2.5.0, <2.6.0",
             "types-aiobotocore-iot>=2.5.0, <2.6.0",
             "types-aiobotocore-iot-data>=2.5.0, <2.6.0",
             "types-aiobotocore-iot-jobs-data>=2.5.0, <2.6.0",
             "types-aiobotocore-iot-roborunner>=2.5.0, <2.6.0",
             "types-aiobotocore-iot1click-devices>=2.5.0, <2.6.0",
             "types-aiobotocore-iot1click-projects>=2.5.0, <2.6.0",
             "types-aiobotocore-iotanalytics>=2.5.0, <2.6.0",
@@ -214,14 +216,15 @@
             "types-aiobotocore-iotfleetwise>=2.5.0, <2.6.0",
             "types-aiobotocore-iotsecuretunneling>=2.5.0, <2.6.0",
             "types-aiobotocore-iotsitewise>=2.5.0, <2.6.0",
             "types-aiobotocore-iotthingsgraph>=2.5.0, <2.6.0",
             "types-aiobotocore-iottwinmaker>=2.5.0, <2.6.0",
             "types-aiobotocore-iotwireless>=2.5.0, <2.6.0",
             "types-aiobotocore-ivs>=2.5.0, <2.6.0",
+            "types-aiobotocore-ivs-realtime>=2.5.0, <2.6.0",
             "types-aiobotocore-ivschat>=2.5.0, <2.6.0",
             "types-aiobotocore-kafka>=2.5.0, <2.6.0",
             "types-aiobotocore-kafkaconnect>=2.5.0, <2.6.0",
             "types-aiobotocore-kendra>=2.5.0, <2.6.0",
             "types-aiobotocore-kendra-ranking>=2.5.0, <2.6.0",
             "types-aiobotocore-keyspaces>=2.5.0, <2.6.0",
             "types-aiobotocore-kinesis>=2.5.0, <2.6.0",
@@ -257,14 +260,15 @@
             "types-aiobotocore-marketplace-entitlement>=2.5.0, <2.6.0",
             "types-aiobotocore-marketplacecommerceanalytics>=2.5.0, <2.6.0",
             "types-aiobotocore-mediaconnect>=2.5.0, <2.6.0",
             "types-aiobotocore-mediaconvert>=2.5.0, <2.6.0",
             "types-aiobotocore-medialive>=2.5.0, <2.6.0",
             "types-aiobotocore-mediapackage>=2.5.0, <2.6.0",
             "types-aiobotocore-mediapackage-vod>=2.5.0, <2.6.0",
+            "types-aiobotocore-mediapackagev2>=2.5.0, <2.6.0",
             "types-aiobotocore-mediastore>=2.5.0, <2.6.0",
             "types-aiobotocore-mediastore-data>=2.5.0, <2.6.0",
             "types-aiobotocore-mediatailor>=2.5.0, <2.6.0",
             "types-aiobotocore-memorydb>=2.5.0, <2.6.0",
             "types-aiobotocore-meteringmarketplace>=2.5.0, <2.6.0",
             "types-aiobotocore-mgh>=2.5.0, <2.6.0",
             "types-aiobotocore-mgn>=2.5.0, <2.6.0",
@@ -283,16 +287,19 @@
             "types-aiobotocore-oam>=2.5.0, <2.6.0",
             "types-aiobotocore-omics>=2.5.0, <2.6.0",
             "types-aiobotocore-opensearch>=2.5.0, <2.6.0",
             "types-aiobotocore-opensearchserverless>=2.5.0, <2.6.0",
             "types-aiobotocore-opsworks>=2.5.0, <2.6.0",
             "types-aiobotocore-opsworkscm>=2.5.0, <2.6.0",
             "types-aiobotocore-organizations>=2.5.0, <2.6.0",
+            "types-aiobotocore-osis>=2.5.0, <2.6.0",
             "types-aiobotocore-outposts>=2.5.0, <2.6.0",
             "types-aiobotocore-panorama>=2.5.0, <2.6.0",
+            "types-aiobotocore-payment-cryptography>=2.5.0, <2.6.0",
+            "types-aiobotocore-payment-cryptography-data>=2.5.0, <2.6.0",
             "types-aiobotocore-personalize>=2.5.0, <2.6.0",
             "types-aiobotocore-personalize-events>=2.5.0, <2.6.0",
             "types-aiobotocore-personalize-runtime>=2.5.0, <2.6.0",
             "types-aiobotocore-pi>=2.5.0, <2.6.0",
             "types-aiobotocore-pinpoint>=2.5.0, <2.6.0",
             "types-aiobotocore-pinpoint-email>=2.5.0, <2.6.0",
             "types-aiobotocore-pinpoint-sms-voice>=2.5.0, <2.6.0",
@@ -376,15 +383,17 @@
             "types-aiobotocore-textract>=2.5.0, <2.6.0",
             "types-aiobotocore-timestream-query>=2.5.0, <2.6.0",
             "types-aiobotocore-timestream-write>=2.5.0, <2.6.0",
             "types-aiobotocore-tnb>=2.5.0, <2.6.0",
             "types-aiobotocore-transcribe>=2.5.0, <2.6.0",
             "types-aiobotocore-transfer>=2.5.0, <2.6.0",
             "types-aiobotocore-translate>=2.5.0, <2.6.0",
+            "types-aiobotocore-verifiedpermissions>=2.5.0, <2.6.0",
             "types-aiobotocore-voice-id>=2.5.0, <2.6.0",
+            "types-aiobotocore-vpc-lattice>=2.5.0, <2.6.0",
             "types-aiobotocore-waf>=2.5.0, <2.6.0",
             "types-aiobotocore-waf-regional>=2.5.0, <2.6.0",
             "types-aiobotocore-wafv2>=2.5.0, <2.6.0",
             "types-aiobotocore-wellarchitected>=2.5.0, <2.6.0",
             "types-aiobotocore-wisdom>=2.5.0, <2.6.0",
             "types-aiobotocore-workdocs>=2.5.0, <2.6.0",
             "types-aiobotocore-worklink>=2.5.0, <2.6.0",
@@ -399,15 +408,15 @@
             "types-aiobotocore-dynamodb>=2.5.0, <2.6.0",
             "types-aiobotocore-ec2>=2.5.0, <2.6.0",
             "types-aiobotocore-lambda>=2.5.0, <2.6.0",
             "types-aiobotocore-rds>=2.5.0, <2.6.0",
             "types-aiobotocore-s3>=2.5.0, <2.6.0",
             "types-aiobotocore-sqs>=2.5.0, <2.6.0",
         ],
-        "aiobotocore": ["aiobotocore==2.5.0", "botocore==1.29.76"],
+        "aiobotocore": ["aiobotocore==2.5.1", "botocore==1.29.161"],
         "accessanalyzer": ["types-aiobotocore-accessanalyzer>=2.5.0, <2.6.0"],
         "account": ["types-aiobotocore-account>=2.5.0, <2.6.0"],
         "acm": ["types-aiobotocore-acm>=2.5.0, <2.6.0"],
         "acm-pca": ["types-aiobotocore-acm-pca>=2.5.0, <2.6.0"],
         "alexaforbusiness": ["types-aiobotocore-alexaforbusiness>=2.5.0, <2.6.0"],
         "amp": ["types-aiobotocore-amp>=2.5.0, <2.6.0"],
         "amplify": ["types-aiobotocore-amplify>=2.5.0, <2.6.0"],
@@ -461,14 +470,15 @@
         "cloudwatch": ["types-aiobotocore-cloudwatch>=2.5.0, <2.6.0"],
         "codeartifact": ["types-aiobotocore-codeartifact>=2.5.0, <2.6.0"],
         "codebuild": ["types-aiobotocore-codebuild>=2.5.0, <2.6.0"],
         "codecatalyst": ["types-aiobotocore-codecatalyst>=2.5.0, <2.6.0"],
         "codecommit": ["types-aiobotocore-codecommit>=2.5.0, <2.6.0"],
         "codedeploy": ["types-aiobotocore-codedeploy>=2.5.0, <2.6.0"],
         "codeguru-reviewer": ["types-aiobotocore-codeguru-reviewer>=2.5.0, <2.6.0"],
+        "codeguru-security": ["types-aiobotocore-codeguru-security>=2.5.0, <2.6.0"],
         "codeguruprofiler": ["types-aiobotocore-codeguruprofiler>=2.5.0, <2.6.0"],
         "codepipeline": ["types-aiobotocore-codepipeline>=2.5.0, <2.6.0"],
         "codestar": ["types-aiobotocore-codestar>=2.5.0, <2.6.0"],
         "codestar-connections": ["types-aiobotocore-codestar-connections>=2.5.0, <2.6.0"],
         "codestar-notifications": ["types-aiobotocore-codestar-notifications>=2.5.0, <2.6.0"],
         "cognito-identity": ["types-aiobotocore-cognito-identity>=2.5.0, <2.6.0"],
         "cognito-idp": ["types-aiobotocore-cognito-idp>=2.5.0, <2.6.0"],
@@ -547,14 +557,15 @@
         "honeycode": ["types-aiobotocore-honeycode>=2.5.0, <2.6.0"],
         "iam": ["types-aiobotocore-iam>=2.5.0, <2.6.0"],
         "identitystore": ["types-aiobotocore-identitystore>=2.5.0, <2.6.0"],
         "imagebuilder": ["types-aiobotocore-imagebuilder>=2.5.0, <2.6.0"],
         "importexport": ["types-aiobotocore-importexport>=2.5.0, <2.6.0"],
         "inspector": ["types-aiobotocore-inspector>=2.5.0, <2.6.0"],
         "inspector2": ["types-aiobotocore-inspector2>=2.5.0, <2.6.0"],
+        "internetmonitor": ["types-aiobotocore-internetmonitor>=2.5.0, <2.6.0"],
         "iot": ["types-aiobotocore-iot>=2.5.0, <2.6.0"],
         "iot-data": ["types-aiobotocore-iot-data>=2.5.0, <2.6.0"],
         "iot-jobs-data": ["types-aiobotocore-iot-jobs-data>=2.5.0, <2.6.0"],
         "iot-roborunner": ["types-aiobotocore-iot-roborunner>=2.5.0, <2.6.0"],
         "iot1click-devices": ["types-aiobotocore-iot1click-devices>=2.5.0, <2.6.0"],
         "iot1click-projects": ["types-aiobotocore-iot1click-projects>=2.5.0, <2.6.0"],
         "iotanalytics": ["types-aiobotocore-iotanalytics>=2.5.0, <2.6.0"],
@@ -565,14 +576,15 @@
         "iotfleetwise": ["types-aiobotocore-iotfleetwise>=2.5.0, <2.6.0"],
         "iotsecuretunneling": ["types-aiobotocore-iotsecuretunneling>=2.5.0, <2.6.0"],
         "iotsitewise": ["types-aiobotocore-iotsitewise>=2.5.0, <2.6.0"],
         "iotthingsgraph": ["types-aiobotocore-iotthingsgraph>=2.5.0, <2.6.0"],
         "iottwinmaker": ["types-aiobotocore-iottwinmaker>=2.5.0, <2.6.0"],
         "iotwireless": ["types-aiobotocore-iotwireless>=2.5.0, <2.6.0"],
         "ivs": ["types-aiobotocore-ivs>=2.5.0, <2.6.0"],
+        "ivs-realtime": ["types-aiobotocore-ivs-realtime>=2.5.0, <2.6.0"],
         "ivschat": ["types-aiobotocore-ivschat>=2.5.0, <2.6.0"],
         "kafka": ["types-aiobotocore-kafka>=2.5.0, <2.6.0"],
         "kafkaconnect": ["types-aiobotocore-kafkaconnect>=2.5.0, <2.6.0"],
         "kendra": ["types-aiobotocore-kendra>=2.5.0, <2.6.0"],
         "kendra-ranking": ["types-aiobotocore-kendra-ranking>=2.5.0, <2.6.0"],
         "keyspaces": ["types-aiobotocore-keyspaces>=2.5.0, <2.6.0"],
         "kinesis": ["types-aiobotocore-kinesis>=2.5.0, <2.6.0"],
@@ -618,14 +630,15 @@
             "types-aiobotocore-marketplacecommerceanalytics>=2.5.0, <2.6.0"
         ],
         "mediaconnect": ["types-aiobotocore-mediaconnect>=2.5.0, <2.6.0"],
         "mediaconvert": ["types-aiobotocore-mediaconvert>=2.5.0, <2.6.0"],
         "medialive": ["types-aiobotocore-medialive>=2.5.0, <2.6.0"],
         "mediapackage": ["types-aiobotocore-mediapackage>=2.5.0, <2.6.0"],
         "mediapackage-vod": ["types-aiobotocore-mediapackage-vod>=2.5.0, <2.6.0"],
+        "mediapackagev2": ["types-aiobotocore-mediapackagev2>=2.5.0, <2.6.0"],
         "mediastore": ["types-aiobotocore-mediastore>=2.5.0, <2.6.0"],
         "mediastore-data": ["types-aiobotocore-mediastore-data>=2.5.0, <2.6.0"],
         "mediatailor": ["types-aiobotocore-mediatailor>=2.5.0, <2.6.0"],
         "memorydb": ["types-aiobotocore-memorydb>=2.5.0, <2.6.0"],
         "meteringmarketplace": ["types-aiobotocore-meteringmarketplace>=2.5.0, <2.6.0"],
         "mgh": ["types-aiobotocore-mgh>=2.5.0, <2.6.0"],
         "mgn": ["types-aiobotocore-mgn>=2.5.0, <2.6.0"],
@@ -646,16 +659,19 @@
         "oam": ["types-aiobotocore-oam>=2.5.0, <2.6.0"],
         "omics": ["types-aiobotocore-omics>=2.5.0, <2.6.0"],
         "opensearch": ["types-aiobotocore-opensearch>=2.5.0, <2.6.0"],
         "opensearchserverless": ["types-aiobotocore-opensearchserverless>=2.5.0, <2.6.0"],
         "opsworks": ["types-aiobotocore-opsworks>=2.5.0, <2.6.0"],
         "opsworkscm": ["types-aiobotocore-opsworkscm>=2.5.0, <2.6.0"],
         "organizations": ["types-aiobotocore-organizations>=2.5.0, <2.6.0"],
+        "osis": ["types-aiobotocore-osis>=2.5.0, <2.6.0"],
         "outposts": ["types-aiobotocore-outposts>=2.5.0, <2.6.0"],
         "panorama": ["types-aiobotocore-panorama>=2.5.0, <2.6.0"],
+        "payment-cryptography": ["types-aiobotocore-payment-cryptography>=2.5.0, <2.6.0"],
+        "payment-cryptography-data": ["types-aiobotocore-payment-cryptography-data>=2.5.0, <2.6.0"],
         "personalize": ["types-aiobotocore-personalize>=2.5.0, <2.6.0"],
         "personalize-events": ["types-aiobotocore-personalize-events>=2.5.0, <2.6.0"],
         "personalize-runtime": ["types-aiobotocore-personalize-runtime>=2.5.0, <2.6.0"],
         "pi": ["types-aiobotocore-pi>=2.5.0, <2.6.0"],
         "pinpoint": ["types-aiobotocore-pinpoint>=2.5.0, <2.6.0"],
         "pinpoint-email": ["types-aiobotocore-pinpoint-email>=2.5.0, <2.6.0"],
         "pinpoint-sms-voice": ["types-aiobotocore-pinpoint-sms-voice>=2.5.0, <2.6.0"],
@@ -747,15 +763,17 @@
         "textract": ["types-aiobotocore-textract>=2.5.0, <2.6.0"],
         "timestream-query": ["types-aiobotocore-timestream-query>=2.5.0, <2.6.0"],
         "timestream-write": ["types-aiobotocore-timestream-write>=2.5.0, <2.6.0"],
         "tnb": ["types-aiobotocore-tnb>=2.5.0, <2.6.0"],
         "transcribe": ["types-aiobotocore-transcribe>=2.5.0, <2.6.0"],
         "transfer": ["types-aiobotocore-transfer>=2.5.0, <2.6.0"],
         "translate": ["types-aiobotocore-translate>=2.5.0, <2.6.0"],
+        "verifiedpermissions": ["types-aiobotocore-verifiedpermissions>=2.5.0, <2.6.0"],
         "voice-id": ["types-aiobotocore-voice-id>=2.5.0, <2.6.0"],
+        "vpc-lattice": ["types-aiobotocore-vpc-lattice>=2.5.0, <2.6.0"],
         "waf": ["types-aiobotocore-waf>=2.5.0, <2.6.0"],
         "waf-regional": ["types-aiobotocore-waf-regional>=2.5.0, <2.6.0"],
         "wafv2": ["types-aiobotocore-wafv2>=2.5.0, <2.6.0"],
         "wellarchitected": ["types-aiobotocore-wellarchitected>=2.5.0, <2.6.0"],
         "wisdom": ["types-aiobotocore-wisdom>=2.5.0, <2.6.0"],
         "workdocs": ["types-aiobotocore-workdocs>=2.5.0, <2.6.0"],
         "worklink": ["types-aiobotocore-worklink>=2.5.0, <2.6.0"],
```

### Comparing `types-aiobotocore-lite-2.5.0.post2/types_aiobotocore_lite.egg-info/PKG-INFO` & `types-aiobotocore-lite-2.5.1/types_aiobotocore_lite.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 Metadata-Version: 2.1
 Name: types-aiobotocore-lite
-Version: 2.5.0.post2
-Summary: Type annotations for aiobotocore 2.5.0 generated with mypy-boto3-builder 7.14.5
+Version: 2.5.1
+Summary: Type annotations for aiobotocore 2.5.1 generated with mypy-boto3-builder 7.14.5
 Home-page: https://github.com/youtype/mypy_boto3_builder
 Author: Vlad Emelianov
 Author-email: vlad.emelianov.nz@gmail.com
 License: MIT License
 Project-URL: Documentation, https://youtype.github.io/types_aiobotocore_docs/
 Project-URL: Source, https://github.com/youtype/mypy_boto3_builder
 Project-URL: Tracker, https://github.com/youtype/mypy_boto3_builder/issues
@@ -88,14 +88,15 @@
 Provides-Extra: cloudwatch
 Provides-Extra: codeartifact
 Provides-Extra: codebuild
 Provides-Extra: codecatalyst
 Provides-Extra: codecommit
 Provides-Extra: codedeploy
 Provides-Extra: codeguru-reviewer
+Provides-Extra: codeguru-security
 Provides-Extra: codeguruprofiler
 Provides-Extra: codepipeline
 Provides-Extra: codestar
 Provides-Extra: codestar-connections
 Provides-Extra: codestar-notifications
 Provides-Extra: cognito-identity
 Provides-Extra: cognito-idp
@@ -174,14 +175,15 @@
 Provides-Extra: honeycode
 Provides-Extra: iam
 Provides-Extra: identitystore
 Provides-Extra: imagebuilder
 Provides-Extra: importexport
 Provides-Extra: inspector
 Provides-Extra: inspector2
+Provides-Extra: internetmonitor
 Provides-Extra: iot
 Provides-Extra: iot-data
 Provides-Extra: iot-jobs-data
 Provides-Extra: iot-roborunner
 Provides-Extra: iot1click-devices
 Provides-Extra: iot1click-projects
 Provides-Extra: iotanalytics
@@ -192,14 +194,15 @@
 Provides-Extra: iotfleetwise
 Provides-Extra: iotsecuretunneling
 Provides-Extra: iotsitewise
 Provides-Extra: iotthingsgraph
 Provides-Extra: iottwinmaker
 Provides-Extra: iotwireless
 Provides-Extra: ivs
+Provides-Extra: ivs-realtime
 Provides-Extra: ivschat
 Provides-Extra: kafka
 Provides-Extra: kafkaconnect
 Provides-Extra: kendra
 Provides-Extra: kendra-ranking
 Provides-Extra: keyspaces
 Provides-Extra: kinesis
@@ -235,14 +238,15 @@
 Provides-Extra: marketplace-entitlement
 Provides-Extra: marketplacecommerceanalytics
 Provides-Extra: mediaconnect
 Provides-Extra: mediaconvert
 Provides-Extra: medialive
 Provides-Extra: mediapackage
 Provides-Extra: mediapackage-vod
+Provides-Extra: mediapackagev2
 Provides-Extra: mediastore
 Provides-Extra: mediastore-data
 Provides-Extra: mediatailor
 Provides-Extra: memorydb
 Provides-Extra: meteringmarketplace
 Provides-Extra: mgh
 Provides-Extra: mgn
@@ -261,16 +265,19 @@
 Provides-Extra: oam
 Provides-Extra: omics
 Provides-Extra: opensearch
 Provides-Extra: opensearchserverless
 Provides-Extra: opsworks
 Provides-Extra: opsworkscm
 Provides-Extra: organizations
+Provides-Extra: osis
 Provides-Extra: outposts
 Provides-Extra: panorama
+Provides-Extra: payment-cryptography
+Provides-Extra: payment-cryptography-data
 Provides-Extra: personalize
 Provides-Extra: personalize-events
 Provides-Extra: personalize-runtime
 Provides-Extra: pi
 Provides-Extra: pinpoint
 Provides-Extra: pinpoint-email
 Provides-Extra: pinpoint-sms-voice
@@ -354,15 +361,17 @@
 Provides-Extra: textract
 Provides-Extra: timestream-query
 Provides-Extra: timestream-write
 Provides-Extra: tnb
 Provides-Extra: transcribe
 Provides-Extra: transfer
 Provides-Extra: translate
+Provides-Extra: verifiedpermissions
 Provides-Extra: voice-id
+Provides-Extra: vpc-lattice
 Provides-Extra: waf
 Provides-Extra: waf-regional
 Provides-Extra: wafv2
 Provides-Extra: wellarchitected
 Provides-Extra: wisdom
 Provides-Extra: workdocs
 Provides-Extra: worklink
@@ -381,15 +390,15 @@
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/types-aiobotocore-lite.svg?color=blue)](https://pypi.org/project/types-aiobotocore-lite)
 [![Docs](https://img.shields.io/readthedocs/types-aiobotocore.svg?color=blue)](https://youtype.github.io/types_aiobotocore_docs/)
 [![PyPI - Downloads](https://img.shields.io/pypi/dm/types-aiobotocore-lite?color=blue)](https://pypistats.org/packages/types-aiobotocore-lite)
 
 ![boto3.typed](https://github.com/youtype/mypy_boto3_builder/raw/main/logo.png)
 
 Type annotations for
-[aiobotocore 2.5.0](https://github.com/aio-libs/aiobotocore) compatible with
+[aiobotocore 2.5.1](https://github.com/aio-libs/aiobotocore) compatible with
 [VSCode](https://code.visualstudio.com/),
 [PyCharm](https://www.jetbrains.com/pycharm/),
 [Emacs](https://www.gnu.org/software/emacs/),
 [Sublime Text](https://www.sublimetext.com/),
 [mypy](https://github.com/python/mypy),
 [pyright](https://github.com/microsoft/pyright) and other tools.
 
@@ -669,15 +678,15 @@
 in [mypy-boto3-builder](https://github.com/youtype/mypy_boto3_builder/issues/)
 repository.
 
 <a id="submodules"></a>
 
 ## Submodules
 
-- `types-aiobotocore-lite[all]` - Type annotations for all 340 services.
+- `types-aiobotocore-lite[all]` - Type annotations for all 349 services.
 - `types-aiobotocore-lite[essential]` - Type annotations for
   [CloudFormation](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_cloudformation/),
   [DynamoDB](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_dynamodb/),
   [EC2](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ec2/),
   [Lambda](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_lambda/),
   [RDS](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_rds/),
   [S3](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_s3/)
@@ -865,14 +874,17 @@
   service.
 - `types-aiobotocore-lite[codedeploy]` - Type annotations for
   [CodeDeploy](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codedeploy/)
   service.
 - `types-aiobotocore-lite[codeguru-reviewer]` - Type annotations for
   [CodeGuruReviewer](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_reviewer/)
   service.
+- `types-aiobotocore-lite[codeguru-security]` - Type annotations for
+  [CodeGuruSecurity](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguru_security/)
+  service.
 - `types-aiobotocore-lite[codeguruprofiler]` - Type annotations for
   [CodeGuruProfiler](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codeguruprofiler/)
   service.
 - `types-aiobotocore-lite[codepipeline]` - Type annotations for
   [CodePipeline](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_codepipeline/)
   service.
 - `types-aiobotocore-lite[codestar]` - Type annotations for
@@ -1123,14 +1135,17 @@
   service.
 - `types-aiobotocore-lite[inspector]` - Type annotations for
   [Inspector](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector/)
   service.
 - `types-aiobotocore-lite[inspector2]` - Type annotations for
   [Inspector2](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_inspector2/)
   service.
+- `types-aiobotocore-lite[internetmonitor]` - Type annotations for
+  [CloudWatchInternetMonitor](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_internetmonitor/)
+  service.
 - `types-aiobotocore-lite[iot]` - Type annotations for
   [IoT](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot/)
   service.
 - `types-aiobotocore-lite[iot-data]` - Type annotations for
   [IoTDataPlane](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iot_data/)
   service.
 - `types-aiobotocore-lite[iot-jobs-data]` - Type annotations for
@@ -1177,14 +1192,17 @@
   service.
 - `types-aiobotocore-lite[iotwireless]` - Type annotations for
   [IoTWireless](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_iotwireless/)
   service.
 - `types-aiobotocore-lite[ivs]` - Type annotations for
   [IVS](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs/)
   service.
+- `types-aiobotocore-lite[ivs-realtime]` - Type annotations for
+  [ivsrealtime](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivs_realtime/)
+  service.
 - `types-aiobotocore-lite[ivschat]` - Type annotations for
   [ivschat](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_ivschat/)
   service.
 - `types-aiobotocore-lite[kafka]` - Type annotations for
   [Kafka](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_kafka/)
   service.
 - `types-aiobotocore-lite[kafkaconnect]` - Type annotations for
@@ -1308,14 +1326,17 @@
   service.
 - `types-aiobotocore-lite[mediapackage]` - Type annotations for
   [MediaPackage](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage/)
   service.
 - `types-aiobotocore-lite[mediapackage-vod]` - Type annotations for
   [MediaPackageVod](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackage_vod/)
   service.
+- `types-aiobotocore-lite[mediapackagev2]` - Type annotations for
+  [mediapackagev2](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediapackagev2/)
+  service.
 - `types-aiobotocore-lite[mediastore]` - Type annotations for
   [MediaStore](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore/)
   service.
 - `types-aiobotocore-lite[mediastore-data]` - Type annotations for
   [MediaStoreData](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_mediastore_data/)
   service.
 - `types-aiobotocore-lite[mediatailor]` - Type annotations for
@@ -1387,20 +1408,29 @@
   service.
 - `types-aiobotocore-lite[opsworkscm]` - Type annotations for
   [OpsWorksCM](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_opsworkscm/)
   service.
 - `types-aiobotocore-lite[organizations]` - Type annotations for
   [Organizations](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_organizations/)
   service.
+- `types-aiobotocore-lite[osis]` - Type annotations for
+  [OpenSearchIngestion](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_osis/)
+  service.
 - `types-aiobotocore-lite[outposts]` - Type annotations for
   [Outposts](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_outposts/)
   service.
 - `types-aiobotocore-lite[panorama]` - Type annotations for
   [Panorama](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_panorama/)
   service.
+- `types-aiobotocore-lite[payment-cryptography]` - Type annotations for
+  [PaymentCryptographyControlPlane](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_payment_cryptography/)
+  service.
+- `types-aiobotocore-lite[payment-cryptography-data]` - Type annotations for
+  [PaymentCryptographyDataPlane](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_payment_cryptography_data/)
+  service.
 - `types-aiobotocore-lite[personalize]` - Type annotations for
   [Personalize](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize/)
   service.
 - `types-aiobotocore-lite[personalize-events]` - Type annotations for
   [PersonalizeEvents](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_personalize_events/)
   service.
 - `types-aiobotocore-lite[personalize-runtime]` - Type annotations for
@@ -1668,17 +1698,23 @@
   service.
 - `types-aiobotocore-lite[transfer]` - Type annotations for
   [Transfer](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_transfer/)
   service.
 - `types-aiobotocore-lite[translate]` - Type annotations for
   [Translate](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_translate/)
   service.
+- `types-aiobotocore-lite[verifiedpermissions]` - Type annotations for
+  [VerifiedPermissions](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_verifiedpermissions/)
+  service.
 - `types-aiobotocore-lite[voice-id]` - Type annotations for
   [VoiceID](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_voice_id/)
   service.
+- `types-aiobotocore-lite[vpc-lattice]` - Type annotations for
+  [VPCLattice](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_vpc_lattice/)
+  service.
 - `types-aiobotocore-lite[waf]` - Type annotations for
   [WAF](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_waf/)
   service.
 - `types-aiobotocore-lite[waf-regional]` - Type annotations for
   [WAFRegional](https://youtype.github.io/types_aiobotocore_docs/types_aiobotocore_waf_regional/)
   service.
 - `types-aiobotocore-lite[wafv2]` - Type annotations for
```

### Comparing `types-aiobotocore-lite-2.5.0.post2/types_aiobotocore_lite.egg-info/SOURCES.txt` & `types-aiobotocore-lite-2.5.1/types_aiobotocore_lite.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `types-aiobotocore-lite-2.5.0.post2/types_aiobotocore_lite.egg-info/requires.txt` & `types-aiobotocore-lite-2.5.1/types_aiobotocore_lite.egg-info/requires.txt`

 * *Files 0% similar despite different names*

```diff
@@ -12,16 +12,16 @@
 [acm]
 types-aiobotocore-acm<2.6.0,>=2.5.0
 
 [acm-pca]
 types-aiobotocore-acm-pca<2.6.0,>=2.5.0
 
 [aiobotocore]
-aiobotocore==2.5.0
-botocore==1.29.76
+aiobotocore==2.5.1
+botocore==1.29.161
 
 [alexaforbusiness]
 types-aiobotocore-alexaforbusiness<2.6.0,>=2.5.0
 
 [all]
 types-aiobotocore-accessanalyzer<2.6.0,>=2.5.0
 types-aiobotocore-account<2.6.0,>=2.5.0
@@ -80,14 +80,15 @@
 types-aiobotocore-cloudwatch<2.6.0,>=2.5.0
 types-aiobotocore-codeartifact<2.6.0,>=2.5.0
 types-aiobotocore-codebuild<2.6.0,>=2.5.0
 types-aiobotocore-codecatalyst<2.6.0,>=2.5.0
 types-aiobotocore-codecommit<2.6.0,>=2.5.0
 types-aiobotocore-codedeploy<2.6.0,>=2.5.0
 types-aiobotocore-codeguru-reviewer<2.6.0,>=2.5.0
+types-aiobotocore-codeguru-security<2.6.0,>=2.5.0
 types-aiobotocore-codeguruprofiler<2.6.0,>=2.5.0
 types-aiobotocore-codepipeline<2.6.0,>=2.5.0
 types-aiobotocore-codestar<2.6.0,>=2.5.0
 types-aiobotocore-codestar-connections<2.6.0,>=2.5.0
 types-aiobotocore-codestar-notifications<2.6.0,>=2.5.0
 types-aiobotocore-cognito-identity<2.6.0,>=2.5.0
 types-aiobotocore-cognito-idp<2.6.0,>=2.5.0
@@ -166,14 +167,15 @@
 types-aiobotocore-honeycode<2.6.0,>=2.5.0
 types-aiobotocore-iam<2.6.0,>=2.5.0
 types-aiobotocore-identitystore<2.6.0,>=2.5.0
 types-aiobotocore-imagebuilder<2.6.0,>=2.5.0
 types-aiobotocore-importexport<2.6.0,>=2.5.0
 types-aiobotocore-inspector<2.6.0,>=2.5.0
 types-aiobotocore-inspector2<2.6.0,>=2.5.0
+types-aiobotocore-internetmonitor<2.6.0,>=2.5.0
 types-aiobotocore-iot<2.6.0,>=2.5.0
 types-aiobotocore-iot-data<2.6.0,>=2.5.0
 types-aiobotocore-iot-jobs-data<2.6.0,>=2.5.0
 types-aiobotocore-iot-roborunner<2.6.0,>=2.5.0
 types-aiobotocore-iot1click-devices<2.6.0,>=2.5.0
 types-aiobotocore-iot1click-projects<2.6.0,>=2.5.0
 types-aiobotocore-iotanalytics<2.6.0,>=2.5.0
@@ -184,14 +186,15 @@
 types-aiobotocore-iotfleetwise<2.6.0,>=2.5.0
 types-aiobotocore-iotsecuretunneling<2.6.0,>=2.5.0
 types-aiobotocore-iotsitewise<2.6.0,>=2.5.0
 types-aiobotocore-iotthingsgraph<2.6.0,>=2.5.0
 types-aiobotocore-iottwinmaker<2.6.0,>=2.5.0
 types-aiobotocore-iotwireless<2.6.0,>=2.5.0
 types-aiobotocore-ivs<2.6.0,>=2.5.0
+types-aiobotocore-ivs-realtime<2.6.0,>=2.5.0
 types-aiobotocore-ivschat<2.6.0,>=2.5.0
 types-aiobotocore-kafka<2.6.0,>=2.5.0
 types-aiobotocore-kafkaconnect<2.6.0,>=2.5.0
 types-aiobotocore-kendra<2.6.0,>=2.5.0
 types-aiobotocore-kendra-ranking<2.6.0,>=2.5.0
 types-aiobotocore-keyspaces<2.6.0,>=2.5.0
 types-aiobotocore-kinesis<2.6.0,>=2.5.0
@@ -227,14 +230,15 @@
 types-aiobotocore-marketplace-entitlement<2.6.0,>=2.5.0
 types-aiobotocore-marketplacecommerceanalytics<2.6.0,>=2.5.0
 types-aiobotocore-mediaconnect<2.6.0,>=2.5.0
 types-aiobotocore-mediaconvert<2.6.0,>=2.5.0
 types-aiobotocore-medialive<2.6.0,>=2.5.0
 types-aiobotocore-mediapackage<2.6.0,>=2.5.0
 types-aiobotocore-mediapackage-vod<2.6.0,>=2.5.0
+types-aiobotocore-mediapackagev2<2.6.0,>=2.5.0
 types-aiobotocore-mediastore<2.6.0,>=2.5.0
 types-aiobotocore-mediastore-data<2.6.0,>=2.5.0
 types-aiobotocore-mediatailor<2.6.0,>=2.5.0
 types-aiobotocore-memorydb<2.6.0,>=2.5.0
 types-aiobotocore-meteringmarketplace<2.6.0,>=2.5.0
 types-aiobotocore-mgh<2.6.0,>=2.5.0
 types-aiobotocore-mgn<2.6.0,>=2.5.0
@@ -253,16 +257,19 @@
 types-aiobotocore-oam<2.6.0,>=2.5.0
 types-aiobotocore-omics<2.6.0,>=2.5.0
 types-aiobotocore-opensearch<2.6.0,>=2.5.0
 types-aiobotocore-opensearchserverless<2.6.0,>=2.5.0
 types-aiobotocore-opsworks<2.6.0,>=2.5.0
 types-aiobotocore-opsworkscm<2.6.0,>=2.5.0
 types-aiobotocore-organizations<2.6.0,>=2.5.0
+types-aiobotocore-osis<2.6.0,>=2.5.0
 types-aiobotocore-outposts<2.6.0,>=2.5.0
 types-aiobotocore-panorama<2.6.0,>=2.5.0
+types-aiobotocore-payment-cryptography<2.6.0,>=2.5.0
+types-aiobotocore-payment-cryptography-data<2.6.0,>=2.5.0
 types-aiobotocore-personalize<2.6.0,>=2.5.0
 types-aiobotocore-personalize-events<2.6.0,>=2.5.0
 types-aiobotocore-personalize-runtime<2.6.0,>=2.5.0
 types-aiobotocore-pi<2.6.0,>=2.5.0
 types-aiobotocore-pinpoint<2.6.0,>=2.5.0
 types-aiobotocore-pinpoint-email<2.6.0,>=2.5.0
 types-aiobotocore-pinpoint-sms-voice<2.6.0,>=2.5.0
@@ -346,15 +353,17 @@
 types-aiobotocore-textract<2.6.0,>=2.5.0
 types-aiobotocore-timestream-query<2.6.0,>=2.5.0
 types-aiobotocore-timestream-write<2.6.0,>=2.5.0
 types-aiobotocore-tnb<2.6.0,>=2.5.0
 types-aiobotocore-transcribe<2.6.0,>=2.5.0
 types-aiobotocore-transfer<2.6.0,>=2.5.0
 types-aiobotocore-translate<2.6.0,>=2.5.0
+types-aiobotocore-verifiedpermissions<2.6.0,>=2.5.0
 types-aiobotocore-voice-id<2.6.0,>=2.5.0
+types-aiobotocore-vpc-lattice<2.6.0,>=2.5.0
 types-aiobotocore-waf<2.6.0,>=2.5.0
 types-aiobotocore-waf-regional<2.6.0,>=2.5.0
 types-aiobotocore-wafv2<2.6.0,>=2.5.0
 types-aiobotocore-wellarchitected<2.6.0,>=2.5.0
 types-aiobotocore-wisdom<2.6.0,>=2.5.0
 types-aiobotocore-workdocs<2.6.0,>=2.5.0
 types-aiobotocore-worklink<2.6.0,>=2.5.0
@@ -528,14 +537,17 @@
 
 [codedeploy]
 types-aiobotocore-codedeploy<2.6.0,>=2.5.0
 
 [codeguru-reviewer]
 types-aiobotocore-codeguru-reviewer<2.6.0,>=2.5.0
 
+[codeguru-security]
+types-aiobotocore-codeguru-security<2.6.0,>=2.5.0
+
 [codeguruprofiler]
 types-aiobotocore-codeguruprofiler<2.6.0,>=2.5.0
 
 [codepipeline]
 types-aiobotocore-codepipeline<2.6.0,>=2.5.0
 
 [codestar]
@@ -795,14 +807,17 @@
 
 [inspector]
 types-aiobotocore-inspector<2.6.0,>=2.5.0
 
 [inspector2]
 types-aiobotocore-inspector2<2.6.0,>=2.5.0
 
+[internetmonitor]
+types-aiobotocore-internetmonitor<2.6.0,>=2.5.0
+
 [iot]
 types-aiobotocore-iot<2.6.0,>=2.5.0
 
 [iot-data]
 types-aiobotocore-iot-data<2.6.0,>=2.5.0
 
 [iot-jobs-data]
@@ -849,14 +864,17 @@
 
 [iotwireless]
 types-aiobotocore-iotwireless<2.6.0,>=2.5.0
 
 [ivs]
 types-aiobotocore-ivs<2.6.0,>=2.5.0
 
+[ivs-realtime]
+types-aiobotocore-ivs-realtime<2.6.0,>=2.5.0
+
 [ivschat]
 types-aiobotocore-ivschat<2.6.0,>=2.5.0
 
 [kafka]
 types-aiobotocore-kafka<2.6.0,>=2.5.0
 
 [kafkaconnect]
@@ -978,14 +996,17 @@
 
 [mediapackage]
 types-aiobotocore-mediapackage<2.6.0,>=2.5.0
 
 [mediapackage-vod]
 types-aiobotocore-mediapackage-vod<2.6.0,>=2.5.0
 
+[mediapackagev2]
+types-aiobotocore-mediapackagev2<2.6.0,>=2.5.0
+
 [mediastore]
 types-aiobotocore-mediastore<2.6.0,>=2.5.0
 
 [mediastore-data]
 types-aiobotocore-mediastore-data<2.6.0,>=2.5.0
 
 [mediatailor]
@@ -1056,20 +1077,29 @@
 
 [opsworkscm]
 types-aiobotocore-opsworkscm<2.6.0,>=2.5.0
 
 [organizations]
 types-aiobotocore-organizations<2.6.0,>=2.5.0
 
+[osis]
+types-aiobotocore-osis<2.6.0,>=2.5.0
+
 [outposts]
 types-aiobotocore-outposts<2.6.0,>=2.5.0
 
 [panorama]
 types-aiobotocore-panorama<2.6.0,>=2.5.0
 
+[payment-cryptography]
+types-aiobotocore-payment-cryptography<2.6.0,>=2.5.0
+
+[payment-cryptography-data]
+types-aiobotocore-payment-cryptography-data<2.6.0,>=2.5.0
+
 [personalize]
 types-aiobotocore-personalize<2.6.0,>=2.5.0
 
 [personalize-events]
 types-aiobotocore-personalize-events<2.6.0,>=2.5.0
 
 [personalize-runtime]
@@ -1335,17 +1365,23 @@
 
 [transfer]
 types-aiobotocore-transfer<2.6.0,>=2.5.0
 
 [translate]
 types-aiobotocore-translate<2.6.0,>=2.5.0
 
+[verifiedpermissions]
+types-aiobotocore-verifiedpermissions<2.6.0,>=2.5.0
+
 [voice-id]
 types-aiobotocore-voice-id<2.6.0,>=2.5.0
 
+[vpc-lattice]
+types-aiobotocore-vpc-lattice<2.6.0,>=2.5.0
+
 [waf]
 types-aiobotocore-waf<2.6.0,>=2.5.0
 
 [waf-regional]
 types-aiobotocore-waf-regional<2.6.0,>=2.5.0
 
 [wafv2]
```

