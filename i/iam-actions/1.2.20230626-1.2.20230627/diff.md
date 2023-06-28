# Comparing `tmp/iam_actions-1.2.20230626.tar.gz` & `tmp/iam_actions-1.2.20230627.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "iam_actions-1.2.20230626.tar", max compression
+gzip compressed data, was "iam_actions-1.2.20230627.tar", max compression
```

## Comparing `iam_actions-1.2.20230626.tar` & `iam_actions-1.2.20230627.tar`

### file list

```diff
@@ -1,18 +1,18 @@
--rw-r--r--   0        0        0     1071 2023-06-26 02:58:32.711314 iam_actions-1.2.20230626/LICENSE
--rw-r--r--   0        0        0     2302 2023-06-26 02:58:32.711314 iam_actions-1.2.20230626/README.md
--rw-r--r--   0        0        0      228 2023-06-26 02:58:32.711314 iam_actions-1.2.20230626/iam_actions/__init__.py
--rw-r--r--   0        0        0  4345395 2023-06-26 03:00:08.135606 iam_actions-1.2.20230626/iam_actions/actions.json
--rw-r--r--   0        0        0      496 2023-06-26 02:58:32.711314 iam_actions-1.2.20230626/iam_actions/data.py
--rw-r--r--   0        0        0       80 2023-06-26 02:58:32.711314 iam_actions-1.2.20230626/iam_actions/generate/__init__.py
--rw-r--r--   0        0        0     3097 2023-06-26 02:58:32.711314 iam_actions-1.2.20230626/iam_actions/generate/action_map.py
--rw-r--r--   0        0        0    23329 2023-06-26 02:58:32.711314 iam_actions-1.2.20230626/iam_actions/generate/aws_docs.py
--rw-r--r--   0        0        0     3739 2023-06-26 02:58:32.711314 iam_actions-1.2.20230626/iam_actions/generate/generate.py
--rw-r--r--   0        0        0     3272 2023-06-26 02:58:32.711314 iam_actions-1.2.20230626/iam_actions/generate/notifier.py
--rw-r--r--   0        0        0     1902 2023-06-26 02:58:32.715314 iam_actions-1.2.20230626/iam_actions/generate/resource_type.py
--rw-r--r--   0        0        0     2277 2023-06-26 02:58:32.715314 iam_actions-1.2.20230626/iam_actions/generate/services.py
--rw-r--r--   0        0        0   558814 2023-06-26 03:00:08.135606 iam_actions-1.2.20230626/iam_actions/policies.json
--rw-r--r--   0        0        0   196908 2023-06-26 03:00:08.135606 iam_actions-1.2.20230626/iam_actions/resourcetypes.json
--rw-r--r--   0        0        0   541974 2023-06-26 03:00:08.135606 iam_actions-1.2.20230626/iam_actions/services.json
--rw-r--r--   0        0        0     1154 2023-06-26 03:00:09.151609 iam_actions-1.2.20230626/pyproject.toml
--rw-r--r--   0        0        0     3024 1970-01-01 00:00:00.000000 iam_actions-1.2.20230626/setup.py
--rw-r--r--   0        0        0     2915 1970-01-01 00:00:00.000000 iam_actions-1.2.20230626/PKG-INFO
+-rw-r--r--   0        0        0     1071 2023-06-27 02:54:42.091114 iam_actions-1.2.20230627/LICENSE
+-rw-r--r--   0        0        0     2302 2023-06-27 02:54:42.091114 iam_actions-1.2.20230627/README.md
+-rw-r--r--   0        0        0      228 2023-06-27 02:54:42.091114 iam_actions-1.2.20230627/iam_actions/__init__.py
+-rw-r--r--   0        0        0  4348656 2023-06-27 02:56:03.843399 iam_actions-1.2.20230627/iam_actions/actions.json
+-rw-r--r--   0        0        0      496 2023-06-27 02:54:42.091114 iam_actions-1.2.20230627/iam_actions/data.py
+-rw-r--r--   0        0        0       80 2023-06-27 02:54:42.091114 iam_actions-1.2.20230627/iam_actions/generate/__init__.py
+-rw-r--r--   0        0        0     3097 2023-06-27 02:54:42.091114 iam_actions-1.2.20230627/iam_actions/generate/action_map.py
+-rw-r--r--   0        0        0    23329 2023-06-27 02:54:42.091114 iam_actions-1.2.20230627/iam_actions/generate/aws_docs.py
+-rw-r--r--   0        0        0     3739 2023-06-27 02:54:42.091114 iam_actions-1.2.20230627/iam_actions/generate/generate.py
+-rw-r--r--   0        0        0     3272 2023-06-27 02:54:42.091114 iam_actions-1.2.20230627/iam_actions/generate/notifier.py
+-rw-r--r--   0        0        0     1902 2023-06-27 02:54:42.091114 iam_actions-1.2.20230627/iam_actions/generate/resource_type.py
+-rw-r--r--   0        0        0     2277 2023-06-27 02:54:42.091114 iam_actions-1.2.20230627/iam_actions/generate/services.py
+-rw-r--r--   0        0        0   559144 2023-06-27 02:56:03.843399 iam_actions-1.2.20230627/iam_actions/policies.json
+-rw-r--r--   0        0        0   197024 2023-06-27 02:56:03.843399 iam_actions-1.2.20230627/iam_actions/resourcetypes.json
+-rw-r--r--   0        0        0   542293 2023-06-27 02:56:03.843399 iam_actions-1.2.20230627/iam_actions/services.json
+-rw-r--r--   0        0        0     1154 2023-06-27 02:56:04.807402 iam_actions-1.2.20230627/pyproject.toml
+-rw-r--r--   0        0        0     3024 1970-01-01 00:00:00.000000 iam_actions-1.2.20230627/setup.py
+-rw-r--r--   0        0        0     2915 1970-01-01 00:00:00.000000 iam_actions-1.2.20230627/PKG-INFO
```

### Comparing `iam_actions-1.2.20230626/LICENSE` & `iam_actions-1.2.20230627/LICENSE`

 * *Files identical despite different names*

### Comparing `iam_actions-1.2.20230626/README.md` & `iam_actions-1.2.20230627/README.md`

 * *Files identical despite different names*

### Comparing `iam_actions-1.2.20230626/iam_actions/actions.json` & `iam_actions-1.2.20230627/iam_actions/actions.json`

 * *Files 0% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9996868262028856%*

 * *Differences: {"'appflow'": "{'ResetConnectorMetadataCache': OrderedDict([('access_level', 'Undocumented'), "*

 * *              "('action', 'ResetConnectorMetadataCache'), ('condition_keys', []), ('description', "*

 * *              "'Not Documented by AWS'), ('orphan', False), ('resources', [])])}",*

 * * "'cloudformation'": "{'ActivateOrganizationsAccess': OrderedDict([('access_level', "*

 * *                     "'Undocumented'), ('action', 'ActivateOrganizationsAccess'), "*

 * *                     "('condition_keys', []), ('description', ' […]*

```diff
@@ -4332,14 +4332,22 @@
                 "aws:RequestTag/${TagKey}",
                 "aws:TagKeys"
             ],
             "description": "Grants permission to register an Amazon AppFlow connector",
             "orphan": false,
             "resources": []
         },
+        "ResetConnectorMetadataCache": {
+            "access_level": "Undocumented",
+            "action": "ResetConnectorMetadataCache",
+            "condition_keys": [],
+            "description": "Not Documented by AWS",
+            "orphan": false,
+            "resources": []
+        },
         "RunFlow": {
             "access_level": "Write",
             "action": "RunFlow",
             "condition_keys": [],
             "description": "Grants permission to run a flow configured in Amazon AppFlow (Console Only)",
             "orphan": false,
             "resources": [
@@ -18565,14 +18573,22 @@
             "resources": [
                 "developmentSchema",
                 "publishedSchema"
             ]
         }
     },
     "cloudformation": {
+        "ActivateOrganizationsAccess": {
+            "access_level": "Undocumented",
+            "action": "ActivateOrganizationsAccess",
+            "condition_keys": [],
+            "description": "Not Documented by AWS",
+            "orphan": false,
+            "resources": []
+        },
         "ActivateType": {
             "access_level": "Write",
             "action": "ActivateType",
             "condition_keys": [],
             "description": "Grants permission to activate a public third-party extension, making it available for use in stack templates",
             "orphan": false,
             "resources": []
@@ -18691,14 +18707,22 @@
             "access_level": "Write",
             "action": "CreateUploadBucket",
             "condition_keys": [],
             "description": "Grants permission to upload templates to Amazon S3 buckets. Used only by the AWS CloudFormation console and is not documented in the API reference",
             "orphan": false,
             "resources": []
         },
+        "DeactivateOrganizationsAccess": {
+            "access_level": "Undocumented",
+            "action": "DeactivateOrganizationsAccess",
+            "condition_keys": [],
+            "description": "Not Documented by AWS",
+            "orphan": false,
+            "resources": []
+        },
         "DeactivateType": {
             "access_level": "Write",
             "action": "DeactivateType",
             "condition_keys": [],
             "description": "Grants permission to deactivate a public extension that was previously activated in this account and region",
             "orphan": false,
             "resources": []
@@ -18795,14 +18819,22 @@
             ],
             "description": "Grants permission to return the Hook invocation information for the specified change set",
             "orphan": false,
             "resources": [
                 "stack"
             ]
         },
+        "DescribeOrganizationsAccess": {
+            "access_level": "Undocumented",
+            "action": "DescribeOrganizationsAccess",
+            "condition_keys": [],
+            "description": "Not Documented by AWS",
+            "orphan": false,
+            "resources": []
+        },
         "DescribePublisher": {
             "access_level": "Read",
             "action": "DescribePublisher",
             "condition_keys": [],
             "description": "Grants permission to return information about a CloudFormation extension publisher",
             "orphan": false,
             "resources": []
@@ -19056,14 +19088,22 @@
             "access_level": "Read",
             "action": "ListResources",
             "condition_keys": [],
             "description": "Grants permission to list resources in your account",
             "orphan": false,
             "resources": []
         },
+        "ListStackInstanceResourceDrifts": {
+            "access_level": "Undocumented",
+            "action": "ListStackInstanceResourceDrifts",
+            "condition_keys": [],
+            "description": "Not Documented by AWS",
+            "orphan": false,
+            "resources": []
+        },
         "ListStackInstances": {
             "access_level": "List",
             "action": "ListStackInstances",
             "condition_keys": [],
             "description": "Grants permission to return summary information about stack instances that are associated with the specified stack set",
             "orphan": false,
             "resources": [
@@ -31603,14 +31643,22 @@
             ],
             "description": "Grants permission to search quick connect resources in an Amazon Connect instance",
             "orphan": false,
             "resources": [
                 "instance"
             ]
         },
+        "SearchResourceTags": {
+            "access_level": "Undocumented",
+            "action": "SearchResourceTags",
+            "condition_keys": [],
+            "description": "Not Documented by AWS",
+            "orphan": false,
+            "resources": []
+        },
         "SearchRoutingProfiles": {
             "access_level": "Read",
             "action": "SearchRoutingProfiles",
             "condition_keys": [
                 "connect:InstanceId",
                 "connect:SearchTag/${TagKey}"
             ],
@@ -82828,14 +82876,22 @@
             "condition_keys": [],
             "description": "Grants permission to get the channel configuration for a specified channel ARN",
             "orphan": false,
             "resources": [
                 "Channel"
             ]
         },
+        "GetParticipant": {
+            "access_level": "Undocumented",
+            "action": "GetParticipant",
+            "condition_keys": [],
+            "description": "Not Documented by AWS",
+            "orphan": false,
+            "resources": []
+        },
         "GetPlaybackKeyPair": {
             "access_level": "Read",
             "action": "GetPlaybackKeyPair",
             "condition_keys": [],
             "description": "Grants permission to get the playback keypair information for a specified ARN",
             "orphan": false,
             "resources": [
@@ -82858,14 +82914,22 @@
             "condition_keys": [],
             "description": "Grants permission to get stage information for a specified ARN",
             "orphan": false,
             "resources": [
                 "Stage"
             ]
         },
+        "GetStageSession": {
+            "access_level": "Undocumented",
+            "action": "GetStageSession",
+            "condition_keys": [],
+            "description": "Not Documented by AWS",
+            "orphan": false,
+            "resources": []
+        },
         "GetStream": {
             "access_level": "Read",
             "action": "GetStream",
             "condition_keys": [],
             "description": "Grants permission to get information about the active (live) stream on a specified channel",
             "orphan": false,
             "resources": [
@@ -82911,14 +82975,30 @@
             "condition_keys": [],
             "description": "Grants permission to get summary information about channels",
             "orphan": false,
             "resources": [
                 "Channel"
             ]
         },
+        "ListParticipantEvents": {
+            "access_level": "Undocumented",
+            "action": "ListParticipantEvents",
+            "condition_keys": [],
+            "description": "Not Documented by AWS",
+            "orphan": false,
+            "resources": []
+        },
+        "ListParticipants": {
+            "access_level": "Undocumented",
+            "action": "ListParticipants",
+            "condition_keys": [],
+            "description": "Not Documented by AWS",
+            "orphan": false,
+            "resources": []
+        },
         "ListPlaybackKeyPairs": {
             "access_level": "List",
             "action": "ListPlaybackKeyPairs",
             "condition_keys": [],
             "description": "Grants permission to get summary information about playback key pairs",
             "orphan": false,
             "resources": [
@@ -82931,14 +83011,22 @@
             "condition_keys": [],
             "description": "Grants permission to get summary information about recording configurations",
             "orphan": false,
             "resources": [
                 "Recording-Configuration"
             ]
         },
+        "ListStageSessions": {
+            "access_level": "Undocumented",
+            "action": "ListStageSessions",
+            "condition_keys": [],
+            "description": "Not Documented by AWS",
+            "orphan": false,
+            "resources": []
+        },
         "ListStages": {
             "access_level": "List",
             "action": "ListStages",
             "condition_keys": [],
             "description": "Grants permission to get summary information about stages",
             "orphan": false,
             "resources": [
@@ -87838,15 +87926,17 @@
         "CreateExport": {
             "access_level": "Write",
             "action": "CreateExport",
             "condition_keys": [],
             "description": "Grants permission to create an export for an existing resource",
             "orphan": false,
             "resources": [
-                "bot"
+                "bot",
+                "set",
+                "test"
             ]
         },
         "CreateIntent": {
             "access_level": "Write",
             "action": "CreateIntent",
             "condition_keys": [],
             "description": "Grants permission to create a new intent in an existing bot locale",
@@ -87905,28 +87995,31 @@
             "orphan": false,
             "resources": [
                 "slottype",
                 "version"
             ]
         },
         "CreateTestSet": {
-            "access_level": "Undocumented",
+            "access_level": "Write",
             "action": "CreateTestSet",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to import a new test-set",
             "orphan": false,
             "resources": []
         },
         "CreateTestSetDiscrepancyReport": {
-            "access_level": "Undocumented",
+            "access_level": "Write",
             "action": "CreateTestSetDiscrepancyReport",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to create a test set discrepancy report",
             "orphan": false,
-            "resources": []
+            "resources": [
+                "set",
+                "test"
+            ]
         },
         "CreateUploadUrl": {
             "access_level": "Write",
             "action": "CreateUploadUrl",
             "condition_keys": [],
             "description": "Grants permission to create an upload url for import file",
             "orphan": false,
@@ -88007,25 +88100,29 @@
         "DeleteExport": {
             "access_level": "Write",
             "action": "DeleteExport",
             "condition_keys": [],
             "description": "Grants permission to delete an existing export",
             "orphan": false,
             "resources": [
-                "bot"
+                "bot",
+                "set",
+                "test"
             ]
         },
         "DeleteImport": {
             "access_level": "Write",
             "action": "DeleteImport",
             "condition_keys": [],
             "description": "Grants permission to delete an existing import",
             "orphan": false,
             "resources": [
-                "bot"
+                "bot",
+                "set",
+                "test"
             ]
         },
         "DeleteIntent": {
             "access_level": "Write",
             "action": "DeleteIntent",
             "condition_keys": [],
             "description": "Grants permission to delete an existing intent in a bot locale",
@@ -88095,20 +88192,23 @@
             "orphan": false,
             "resources": [
                 "slottype",
                 "version"
             ]
         },
         "DeleteTestSet": {
-            "access_level": "Undocumented",
+            "access_level": "Write",
             "action": "DeleteTestSet",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to delete an existing test set",
             "orphan": false,
-            "resources": []
+            "resources": [
+                "set",
+                "test"
+            ]
         },
         "DeleteUtterances": {
             "access_level": "Write",
             "action": "DeleteUtterances",
             "condition_keys": [],
             "description": "Grants permission to delete utterance data for a bot",
             "orphan": false,
@@ -88200,25 +88300,29 @@
         "DescribeExport": {
             "access_level": "Read",
             "action": "DescribeExport",
             "condition_keys": [],
             "description": "Grants permission to retrieve an existing export",
             "orphan": false,
             "resources": [
-                "bot"
+                "bot",
+                "set",
+                "test"
             ]
         },
         "DescribeImport": {
             "access_level": "Read",
             "action": "DescribeImport",
             "condition_keys": [],
             "description": "Grants permission to retrieve an existing import",
             "orphan": false,
             "resources": [
-                "bot"
+                "bot",
+                "set",
+                "test"
             ]
         },
         "DescribeIntent": {
             "access_level": "Read",
             "action": "DescribeIntent",
             "condition_keys": [],
             "description": "Grants permission to retrieve an existing intent",
@@ -88255,44 +88359,56 @@
             "description": "Grants permission to retrieve an existing slot type",
             "orphan": false,
             "resources": [
                 "bot"
             ]
         },
         "DescribeTestExecution": {
-            "access_level": "Undocumented",
+            "access_level": "Read",
             "action": "DescribeTestExecution",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to retrieve test execution metadata",
             "orphan": false,
-            "resources": []
+            "resources": [
+                "set",
+                "test"
+            ]
         },
         "DescribeTestSet": {
-            "access_level": "Undocumented",
+            "access_level": "Read",
             "action": "DescribeTestSet",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to retrieve an existing test set",
             "orphan": false,
-            "resources": []
+            "resources": [
+                "set",
+                "test"
+            ]
         },
         "DescribeTestSetDiscrepancyReport": {
-            "access_level": "Undocumented",
+            "access_level": "Read",
             "action": "DescribeTestSetDiscrepancyReport",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to retrieve test set discrepancy report metadata",
             "orphan": false,
-            "resources": []
+            "resources": [
+                "set",
+                "test"
+            ]
         },
         "DescribeTestSetGeneration": {
-            "access_level": "Undocumented",
+            "access_level": "Read",
             "action": "DescribeTestSetGeneration",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to retrieve test set generation metadata",
             "orphan": false,
-            "resources": []
+            "resources": [
+                "set",
+                "test"
+            ]
         },
         "GetBot": {
             "access_level": "Read",
             "action": "GetBot",
             "condition_keys": [],
             "description": "Returns information for a specific bot. In addition to the bot name, the bot version or alias is required",
             "orphan": false,
@@ -88487,20 +88603,23 @@
             "action": "GetSlotTypes",
             "condition_keys": [],
             "description": "Returns information for the $LATEST version of all slot types, subject to filters provided by the client",
             "orphan": false,
             "resources": []
         },
         "GetTestExecutionArtifactsUrl": {
-            "access_level": "Undocumented",
+            "access_level": "Read",
             "action": "GetTestExecutionArtifactsUrl",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to retrieve artifacts URL for a test execution",
             "orphan": false,
-            "resources": []
+            "resources": [
+                "set",
+                "test"
+            ]
         },
         "GetUtterancesView": {
             "access_level": "List",
             "action": "GetUtterancesView",
             "condition_keys": [],
             "description": "Returns a view of aggregate utterance data for versions of a bot for a recent time period",
             "orphan": false,
@@ -88663,46 +88782,54 @@
             "access_level": "Read",
             "action": "ListTagsForResource",
             "condition_keys": [],
             "description": "Grants permission to lists tags for a Lex resource",
             "orphan": false,
             "resources": [
                 "alias",
-                "bot"
+                "bot",
+                "set",
+                "test"
             ]
         },
         "ListTestExecutionResultItems": {
-            "access_level": "Undocumented",
+            "access_level": "Read",
             "action": "ListTestExecutionResultItems",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to retrieve test results data for a test execution",
             "orphan": false,
-            "resources": []
+            "resources": [
+                "set",
+                "test"
+            ]
         },
         "ListTestExecutions": {
-            "access_level": "Undocumented",
+            "access_level": "List",
             "action": "ListTestExecutions",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to list test executions",
             "orphan": false,
             "resources": []
         },
         "ListTestSetRecords": {
-            "access_level": "Undocumented",
+            "access_level": "Read",
             "action": "ListTestSetRecords",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to retrieve records inside an existing test set",
             "orphan": false,
-            "resources": []
+            "resources": [
+                "set",
+                "test"
+            ]
         },
         "ListTestSets": {
-            "access_level": "Undocumented",
+            "access_level": "List",
             "action": "ListTestSets",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to list test sets",
             "orphan": false,
             "resources": []
         },
         "PostContent": {
             "access_level": "Write",
             "action": "PostContent",
             "condition_keys": [],
@@ -88847,43 +88974,51 @@
                 "aws:RequestTag/${TagKey}",
                 "aws:TagKeys"
             ],
             "description": "Grants permission to start a new import with the uploaded import file",
             "orphan": false,
             "resources": [
                 "alias",
-                "bot"
+                "bot",
+                "set",
+                "test"
             ]
         },
         "StartMigration": {
             "access_level": "Write",
             "action": "StartMigration",
             "condition_keys": [],
             "description": "Grants permission to migrate a bot from Amazon Lex v1 to Amazon Lex v2",
             "orphan": false,
             "resources": [
                 "bot",
                 "version"
             ]
         },
         "StartTestExecution": {
-            "access_level": "Undocumented",
+            "access_level": "Write",
             "action": "StartTestExecution",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to start a test execution using a test set",
             "orphan": false,
-            "resources": []
+            "resources": [
+                "set",
+                "test"
+            ]
         },
         "StartTestSetGeneration": {
-            "access_level": "Undocumented",
+            "access_level": "Write",
             "action": "StartTestSetGeneration",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to generate a test set",
             "orphan": false,
-            "resources": []
+            "resources": [
+                "set",
+                "test"
+            ]
         },
         "StopBotRecommendation": {
             "access_level": "Write",
             "action": "StopBotRecommendation",
             "condition_keys": [],
             "description": "Grants permission to stop a bot recommendation for an existing bot locale",
             "orphan": false,
@@ -88898,29 +89033,33 @@
                 "aws:RequestTag/${TagKey}",
                 "aws:TagKeys"
             ],
             "description": "Grants permission to add or overwrite tags of a Lex resource",
             "orphan": false,
             "resources": [
                 "alias",
-                "bot"
+                "bot",
+                "set",
+                "test"
             ]
         },
         "UntagResource": {
             "access_level": "Tagging",
             "action": "UntagResource",
             "condition_keys": [
                 "aws:RequestTag/${TagKey}",
                 "aws:TagKeys"
             ],
             "description": "Grants permission to remove tags from a Lex resource",
             "orphan": false,
             "resources": [
                 "alias",
-                "bot"
+                "bot",
+                "set",
+                "test"
             ]
         },
         "UpdateBot": {
             "access_level": "Write",
             "action": "UpdateBot",
             "condition_keys": [],
             "description": "Grants permission to update an existing bot",
@@ -89018,20 +89157,23 @@
             "description": "Grants permission to update an existing slot type",
             "orphan": false,
             "resources": [
                 "bot"
             ]
         },
         "UpdateTestSet": {
-            "access_level": "Undocumented",
+            "access_level": "Write",
             "action": "UpdateTestSet",
             "condition_keys": [],
-            "description": "Not Documented by AWS",
+            "description": "Grants permission to update an existing test set",
             "orphan": false,
-            "resources": []
+            "resources": [
+                "set",
+                "test"
+            ]
         }
     },
     "license-manager": {
         "AcceptGrant": {
             "access_level": "Write",
             "action": "AcceptGrant",
             "condition_keys": [],
```

### Comparing `iam_actions-1.2.20230626/iam_actions/generate/action_map.py` & `iam_actions-1.2.20230627/iam_actions/generate/action_map.py`

 * *Files identical despite different names*

### Comparing `iam_actions-1.2.20230626/iam_actions/generate/aws_docs.py` & `iam_actions-1.2.20230627/iam_actions/generate/aws_docs.py`

 * *Files identical despite different names*

### Comparing `iam_actions-1.2.20230626/iam_actions/generate/generate.py` & `iam_actions-1.2.20230627/iam_actions/generate/generate.py`

 * *Files identical despite different names*

### Comparing `iam_actions-1.2.20230626/iam_actions/generate/notifier.py` & `iam_actions-1.2.20230627/iam_actions/generate/notifier.py`

 * *Files identical despite different names*

### Comparing `iam_actions-1.2.20230626/iam_actions/generate/resource_type.py` & `iam_actions-1.2.20230627/iam_actions/generate/resource_type.py`

 * *Files identical despite different names*

### Comparing `iam_actions-1.2.20230626/iam_actions/generate/services.py` & `iam_actions-1.2.20230627/iam_actions/generate/services.py`

 * *Files identical despite different names*

### Comparing `iam_actions-1.2.20230626/iam_actions/policies.json` & `iam_actions-1.2.20230627/iam_actions/policies.json`

 * *Files 0% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9999976145702127%*

 * *Differences: {"'serviceMap'": "{'Amazon Connect': {'Actions': {insert: [(143, 'SearchResourceTags')]}}, 'Amazon "*

 * *                 "AppFlow': {'Actions': {insert: [(20, 'ResetConnectorMetadataCache')]}}, 'Amazon "*

 * *                 "Interactive Video Service': {'Actions': {insert: [(14, 'GetParticipant'), (18, "*

 * *                 "'GetStageSession'), (24, 'ListParticipantEvents'), (25, 'ListParticipants'), "*

 * *                 "(28, 'ListStageSessions')]}}, 'AWS CloudFormation': {'Actions': {insert: [(0, "*

 * *                  […]*

```diff
@@ -1466,32 +1466,35 @@
                 "cloud9:UserArn"
             ]
         },
         "AWS CloudFormation": {
             "ARNFormat": "arn:aws:cloudformation:${Region}:${Account}:${ResourceType}/${Id}",
             "ARNRegex": "^arn:aws:cloudformation:.+:[0-9]+:.+",
             "Actions": [
+                "ActivateOrganizationsAccess",
                 "ActivateType",
                 "BatchDescribeTypeConfigurations",
                 "CancelUpdateStack",
                 "ContinueUpdateRollback",
                 "CreateChangeSet",
                 "CreateStack",
                 "CreateStackInstances",
                 "CreateStackSet",
                 "CreateUploadBucket",
+                "DeactivateOrganizationsAccess",
                 "DeactivateType",
                 "DeleteChangeSet",
                 "DeleteStack",
                 "DeleteStackInstances",
                 "DeleteStackSet",
                 "DeregisterType",
                 "DescribeAccountLimits",
                 "DescribeChangeSet",
                 "DescribeChangeSetHooks",
+                "DescribeOrganizationsAccess",
                 "DescribePublisher",
                 "DescribeStackDriftDetectionStatus",
                 "DescribeStackEvents",
                 "DescribeStackInstance",
                 "DescribeStackResource",
                 "DescribeStackResourceDrifts",
                 "DescribeStackResources",
@@ -1508,14 +1511,15 @@
                 "GetStackPolicy",
                 "GetTemplate",
                 "GetTemplateSummary",
                 "ImportStacksToStackSet",
                 "ListChangeSets",
                 "ListExports",
                 "ListImports",
+                "ListStackInstanceResourceDrifts",
                 "ListStackInstances",
                 "ListStackResources",
                 "ListStackSetOperationResults",
                 "ListStackSetOperations",
                 "ListStackSets",
                 "ListStacks",
                 "ListTypeRegistrations",
@@ -9968,14 +9972,15 @@
                 "DescribeFlows",
                 "ListConnectorEntities",
                 "ListConnectorFields",
                 "ListConnectors",
                 "ListFlows",
                 "ListTagsForResource",
                 "RegisterConnector",
+                "ResetConnectorMetadataCache",
                 "RunFlow",
                 "StartFlow",
                 "StopFlow",
                 "TagResource",
                 "UnRegisterConnector",
                 "UntagResource",
                 "UpdateConnectorProfile",
@@ -11686,14 +11691,15 @@
                 "ReplicateInstance",
                 "ResumeContactRecording",
                 "SearchAvailablePhoneNumbers",
                 "SearchHoursOfOperations",
                 "SearchPrompts",
                 "SearchQueues",
                 "SearchQuickConnects",
+                "SearchResourceTags",
                 "SearchRoutingProfiles",
                 "SearchSecurityProfiles",
                 "SearchUsers",
                 "SearchVocabularies",
                 "StartChatContact",
                 "StartContactEvaluation",
                 "StartContactRecording",
@@ -14723,24 +14729,29 @@
                 "DeleteChannel",
                 "DeletePlaybackKeyPair",
                 "DeleteRecordingConfiguration",
                 "DeleteStage",
                 "DeleteStreamKey",
                 "DisconnectParticipant",
                 "GetChannel",
+                "GetParticipant",
                 "GetPlaybackKeyPair",
                 "GetRecordingConfiguration",
                 "GetStage",
+                "GetStageSession",
                 "GetStream",
                 "GetStreamKey",
                 "GetStreamSession",
                 "ImportPlaybackKeyPair",
                 "ListChannels",
+                "ListParticipantEvents",
+                "ListParticipants",
                 "ListPlaybackKeyPairs",
                 "ListRecordingConfigurations",
+                "ListStageSessions",
                 "ListStages",
                 "ListStreamKeys",
                 "ListStreamSessions",
                 "ListStreams",
                 "ListTagsForResource",
                 "PutMetadata",
                 "StopStream",
```

### Comparing `iam_actions-1.2.20230626/iam_actions/resourcetypes.json` & `iam_actions-1.2.20230627/iam_actions/resourcetypes.json`

 * *Files 0% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.999802683504341%*

 * *Differences: {"'lex'": "{'test set': OrderedDict([('arn_pattern', 'arn:*:lex:*:*:test-set/*'), "*

 * *          "('condition_keys', 'aws:ResourceTag/${TagKey}')])}"}*

```diff
@@ -3844,14 +3844,18 @@
         "intent version": {
             "arn_pattern": "arn:*:lex:*:*:intent:*:*",
             "condition_keys": null
         },
         "slottype version": {
             "arn_pattern": "arn:*:lex:*:*:slottype:*:*",
             "condition_keys": null
+        },
+        "test set": {
+            "arn_pattern": "arn:*:lex:*:*:test-set/*",
+            "condition_keys": "aws:ResourceTag/${TagKey}"
         }
     },
     "license-manager": {
         "grant": {
             "arn_pattern": "arn:*:license-manager::*:grant:*",
             "condition_keys": null
         },
```

### Comparing `iam_actions-1.2.20230626/iam_actions/services.json` & `iam_actions-1.2.20230627/iam_actions/services.json`

 * *Files 0% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9999756483783449%*

 * *Differences: {"'appflow'": "{'Actions': {insert: [(20, 'ResetConnectorMetadataCache')]}}",*

 * * "'cloudformation'": "{'Actions': {insert: [(0, 'ActivateOrganizationsAccess'), (12, "*

 * *                     "'DeactivateOrganizationsAccess'), (23, 'DescribeOrganizationsAccess'), (52, "*

 * *                     "'ListStackInstanceResourceDrifts')]}}",*

 * * "'connect'": "{'Actions': {insert: [(143, 'SearchResourceTags')]}}",*

 * * "'ivs'": "{'Actions': {insert: [(14, 'GetParticipant'), (18, 'GetStageSession'), (24, "*

 * *          "'ListParticipan […]*

```diff
@@ -727,14 +727,15 @@
             "DescribeFlows",
             "ListConnectorEntities",
             "ListConnectorFields",
             "ListConnectors",
             "ListFlows",
             "ListTagsForResource",
             "RegisterConnector",
+            "ResetConnectorMetadataCache",
             "RunFlow",
             "StartFlow",
             "StopFlow",
             "TagResource",
             "UnRegisterConnector",
             "UntagResource",
             "UpdateConnectorProfile",
@@ -2856,35 +2857,38 @@
             "arn:aws:cloudformation:${Region}:${Account}:${RelativeId}",
             "arn:aws:cloudformation:${Region}:${Account}:${ResourceType}/${Id}"
         ],
         "ARNRegexes": [
             "^arn:aws:cloudformation:.+:[0-9]+:.+"
         ],
         "Actions": [
+            "ActivateOrganizationsAccess",
             "ActivateType",
             "BatchDescribeTypeConfigurations",
             "CancelResourceRequest",
             "CancelUpdateStack",
             "ContinueUpdateRollback",
             "CreateChangeSet",
             "CreateResource",
             "CreateStack",
             "CreateStackInstances",
             "CreateStackSet",
             "CreateUploadBucket",
+            "DeactivateOrganizationsAccess",
             "DeactivateType",
             "DeleteChangeSet",
             "DeleteResource",
             "DeleteStack",
             "DeleteStackInstances",
             "DeleteStackSet",
             "DeregisterType",
             "DescribeAccountLimits",
             "DescribeChangeSet",
             "DescribeChangeSetHooks",
+            "DescribeOrganizationsAccess",
             "DescribePublisher",
             "DescribeStackDriftDetectionStatus",
             "DescribeStackEvents",
             "DescribeStackInstance",
             "DescribeStackResource",
             "DescribeStackResourceDrifts",
             "DescribeStackResources",
@@ -2905,14 +2909,15 @@
             "GetTemplateSummary",
             "ImportStacksToStackSet",
             "ListChangeSets",
             "ListExports",
             "ListImports",
             "ListResourceRequests",
             "ListResources",
+            "ListStackInstanceResourceDrifts",
             "ListStackInstances",
             "ListStackResources",
             "ListStackSetOperationResults",
             "ListStackSetOperations",
             "ListStackSets",
             "ListStacks",
             "ListTypeRegistrations",
@@ -4699,14 +4704,15 @@
             "ReplicateInstance",
             "ResumeContactRecording",
             "SearchAvailablePhoneNumbers",
             "SearchHoursOfOperations",
             "SearchPrompts",
             "SearchQueues",
             "SearchQuickConnects",
+            "SearchResourceTags",
             "SearchRoutingProfiles",
             "SearchSecurityProfiles",
             "SearchUsers",
             "SearchVocabularies",
             "StartChatContact",
             "StartContactEvaluation",
             "StartContactRecording",
@@ -11441,24 +11447,29 @@
             "DeleteChannel",
             "DeletePlaybackKeyPair",
             "DeleteRecordingConfiguration",
             "DeleteStage",
             "DeleteStreamKey",
             "DisconnectParticipant",
             "GetChannel",
+            "GetParticipant",
             "GetPlaybackKeyPair",
             "GetRecordingConfiguration",
             "GetStage",
+            "GetStageSession",
             "GetStream",
             "GetStreamKey",
             "GetStreamSession",
             "ImportPlaybackKeyPair",
             "ListChannels",
+            "ListParticipantEvents",
+            "ListParticipants",
             "ListPlaybackKeyPairs",
             "ListRecordingConfigurations",
+            "ListStageSessions",
             "ListStages",
             "ListStreamKeys",
             "ListStreamSessions",
             "ListStreams",
             "ListTagsForResource",
             "PutMetadata",
             "StopStream",
```

### Comparing `iam_actions-1.2.20230626/pyproject.toml` & `iam_actions-1.2.20230627/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "iam-actions"
-version = "1.2.20230626"
+version = "1.2.20230627"
 description = "JSON of AWS policy components"
 authors = ["Constable <info@constableapp.com>"]
 license = "MIT"
 readme = "README.md"
 repository = "https://github.com/constableapp/iam_actions"
 packages = [{include = "iam_actions"}]
```

### Comparing `iam_actions-1.2.20230626/setup.py` & `iam_actions-1.2.20230627/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 ['iam_actions', 'iam_actions.generate']
 
 package_data = \
 {'': ['*']}
 
 setup_kwargs = {
     'name': 'iam-actions',
-    'version': '1.2.20230626',
+    'version': '1.2.20230627',
     'description': 'JSON of AWS policy components',
     'long_description': '# iam_actions\n\n`iam_actions` is a python module which contains a dictionary of AWS IAM information. Ideally, it is a complete catalog of all AWS services, actions, and resource types. The information is scraped from the AWS documentation pages.\n\nNightly, the scraping service runs, and publishes a new version with the date appended. \n\nThe package is meant to be used as a consumable package, but it also contains the code to generate the definitions for packaging.\n\nThere are three "roots" that you can consume: actions, resource_types, and services. They all currently return as dict\'s. *However, in a future release, it will be returned as python data structures*\n\n## Actions\n\nActions is a listing of all the actions for a given service. The structure is as follows:\n```\n{\n    "service_name": {\n        "action_name: {\n            "access_level": access_level,\n            "action": action_name,\n            "condition_keys": [condition_key1, ...],\n            "description": description\n        }\n    }\n}\n```\n\nTherefore, you can find information about an action as follows\n\n```\n>>> iam_actions.actions[\'s3\'][\'GetObject\']\n{\'access_level\': \'Read\', \'action\': \'GetObject\', \'condition_keys\': [\'s3:AccessPointNetworkOrigin\', \'s3:DataAccessPointAccount\', \'s3:DataAccessPointArn\', \'s3:ExistingObjectTag/<key>\', \'s3:ResourceAccount\', \'s3:TlsVersion\', \'s3:authType\', \'s3:signatureAge\', \'s3:signatureversion\', \'s3:x-amz-content-sha256\'], \'description\': \'Grants permission to retrieve objects from Amazon S3\', \'orphan\': False, \'resources\': [\'object\']}\n```\n\n## Services\n\nServices list information about the service. The structure is as follows:\n\n```\n{\n    "service_name": {\n        "Actions": [action1, ...]\n        "ServiceNames": [service_name1, ...]\n        "ARNFormats": [arn_format1, ...]\n        "ConditionKeys": [condition_key1, ...]\n        "HasResource": bool\n    }\n}\n```\n\n## Resource Types\n\nResource Types list information about the resource types for the service. The structure is as follows:\n\n```\n{\n    "service_name": {\n        "resource_name": {\n            "arn_pattern": arn_pattern,\n            "condition_keys": [condition_key1, ...]\n        }\n    }\n}\n```\n\n## Usage\n\n```python\nimport iam_actions\n\nprint(item_actions.services)\nprint(item_actions.actions)\nprint(item_actions.resource_types)\n```\n',
     'author': 'Constable',
     'author_email': 'info@constableapp.com',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'https://github.com/constableapp/iam_actions',
```

### Comparing `iam_actions-1.2.20230626/PKG-INFO` & `iam_actions-1.2.20230627/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: iam-actions
-Version: 1.2.20230626
+Version: 1.2.20230627
 Summary: JSON of AWS policy components
 Home-page: https://github.com/constableapp/iam_actions
 License: MIT
 Author: Constable
 Author-email: info@constableapp.com
 Requires-Python: >=3.9,<4.0
 Classifier: License :: OSI Approved :: MIT License
```

