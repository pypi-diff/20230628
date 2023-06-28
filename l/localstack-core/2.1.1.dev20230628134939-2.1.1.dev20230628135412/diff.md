# Comparing `tmp/localstack-core-2.1.1.dev20230628134939.tar.gz` & `tmp/localstack-core-2.1.1.dev20230628135412.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "localstack-core-2.1.1.dev20230628134939.tar", last modified: Wed Jun 28 13:49:46 2023, max compression
+gzip compressed data, was "localstack-core-2.1.1.dev20230628135412.tar", last modified: Wed Jun 28 13:55:53 2023, max compression
```

## Comparing `localstack-core-2.1.1.dev20230628134939.tar` & `localstack-core-2.1.1.dev20230628135412.tar`

### file list

```diff
@@ -1,867 +1,867 @@
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.963989 localstack-core-2.1.1.dev20230628134939/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      606 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/LICENSE.txt
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      216 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/MANIFEST.in
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    15152 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/Makefile
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      652 2023-06-28 13:49:46.963989 localstack-core-2.1.1.dev20230628134939/PKG-INFO
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    11768 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/README.md
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.835990 localstack-core-2.1.1.dev20230628134939/bin/
--rwxrwxr-x   0 circleci  (1001) circleci  (1002)      543 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/bin/localstack
--rwxrwxr-x   0 circleci  (1001) circleci  (1002)     5936 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/bin/localstack-supervisor
--rw-rw-r--   0 circleci  (1001) circleci  (1002)       29 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/bin/localstack.bat
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.835990 localstack-core-2.1.1.dev20230628134939/localstack/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)       40 2023-06-28 13:49:39.000000 localstack-core-2.1.1.dev20230628134939/localstack/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.835990 localstack-core-2.1.1.dev20230628134939/localstack/aws/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3959 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/accounts.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.839990 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      371 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.839990 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/acm/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    17594 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/acm/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.839990 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/apigateway/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    72874 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/apigateway/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.839990 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/cloudcontrol/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    10727 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/cloudcontrol/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.839990 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/cloudformation/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    86365 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/cloudformation/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.839990 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/cloudwatch/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    42875 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/cloudwatch/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.839990 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/config/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)   127167 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/config/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6224 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/core.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.855989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/dynamodb/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    81315 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/dynamodb/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.855989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/dynamodbstreams/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6998 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/dynamodbstreams/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.855989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/ec2/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)   759908 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/ec2/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/es/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    60425 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/es/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/events/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    55327 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/events/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/firehose/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    42200 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/firehose/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/iam/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)   102907 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/iam/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/kinesis/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    25818 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/kinesis/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/kms/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    48826 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/kms/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/lambda_/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    72128 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/lambda_/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/logs/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    38087 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/logs/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/opensearch/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    68386 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/opensearch/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/redshift/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)   133756 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/redshift/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/resource_groups/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    14546 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/resource_groups/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/resourcegroupstaggingapi/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     8578 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/resourcegroupstaggingapi/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/route53/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    67927 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/route53/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/route53resolver/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    52075 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/route53resolver/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/s3/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)   133075 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/s3/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/s3control/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    65907 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/s3control/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/secretsmanager/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    21744 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/secretsmanager/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/ses/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    54804 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/ses/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/sns/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    27429 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/sns/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/sqs/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    18818 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/sqs/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/ssm/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)   215900 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/ssm/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/stepfunctions/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    39472 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/stepfunctions/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/sts/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     9713 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/sts/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/support/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    16691 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/support/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/swf/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    59679 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/swf/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.859989 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/transcribe/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    40302 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/api/transcribe/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4447 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/app.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     8455 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/chain.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     8023 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/client.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    22554 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/connect.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     8959 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/forwarder.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      998 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/gateway.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.863989 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1665 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2548 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/analytics.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2137 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/auth.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1337 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/codec.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     9926 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/cors.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2285 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/fallback.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1320 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/internal.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      843 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/internal_requests.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6990 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/legacy.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5983 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/logging.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6368 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/metric_handler.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    10511 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/partition_rewriter.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      650 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/proxy.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      665 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/region.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      862 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/routes.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    11961 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/service.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2924 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/service_plugin.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    13758 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/mocking.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.863989 localstack-core-2.1.1.dev20230628134939/localstack/aws/protocol/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/protocol/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    15278 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/protocol/op_router.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    49972 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/protocol/parser.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    75997 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/protocol/serializer.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    14590 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/protocol/service_router.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5316 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/protocol/validate.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1912 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/proxy.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    20281 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/scaffold.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.863989 localstack-core-2.1.1.dev20230628134939/localstack/aws/serving/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/serving/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2377 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/serving/asgi.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1060 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/serving/edge.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1424 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/serving/hypercorn.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      775 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/serving/werkzeug.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1446 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/serving/wsgi.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7908 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/skeleton.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    28256 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/spec-patches.json
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7072 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/spec.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    12624 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/aws/trace.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.863989 localstack-core-2.1.1.dev20230628134939/localstack/cli/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      176 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/cli/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      346 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/cli/console.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    27824 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/cli/localstack.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4220 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/cli/lpm.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      477 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/cli/main.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      879 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/cli/plugin.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3429 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/cli/plugins.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1385 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/cli/profiles.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    50628 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/config.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     8070 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/constants.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.863989 localstack-core-2.1.1.dev20230628134939/localstack/contrib/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      144 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/contrib/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    11774 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/deprecations.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.863989 localstack-core-2.1.1.dev20230628134939/localstack/extensions/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)       95 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/extensions/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.863989 localstack-core-2.1.1.dev20230628134939/localstack/extensions/api/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      138 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/extensions/api/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      686 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/extensions/api/aws.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2588 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/extensions/api/extension.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      422 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/extensions/api/http.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)       84 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/extensions/api/runtime.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      104 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/extensions/api/services.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.867989 localstack-core-2.1.1.dev20230628134939/localstack/http/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      213 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/http/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2933 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/http/adapters.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    14626 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/http/asgi.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5518 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/http/client.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2397 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/http/dispatcher.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5116 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/http/hypercorn.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7159 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/http/proxy.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    11089 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/http/request.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4124 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/http/resource.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3232 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/http/response.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    17344 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/http/router.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.867989 localstack-core-2.1.1.dev20230628134939/localstack/logging/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/logging/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4844 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/logging/format.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4230 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/logging/setup.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.867989 localstack-core-2.1.1.dev20230628134939/localstack/packages/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      533 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/packages/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    15427 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/packages/api.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6728 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/packages/core.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1296 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/packages/debugpy.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1390 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/packages/ffmpeg.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      337 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/packages/plugins.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1313 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/packages/terraform.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1174 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/plugins.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.867989 localstack-core-2.1.1.dev20230628134939/localstack/runtime/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/runtime/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2672 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/runtime/analytics.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      154 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/runtime/events.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      289 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/runtime/exceptions.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3114 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/runtime/hooks.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6440 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/runtime/init.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      817 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/runtime/main.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1415 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/runtime/shutdown.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.867989 localstack-core-2.1.1.dev20230628134939/localstack/services/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.867989 localstack-core-2.1.1.dev20230628134939/localstack/services/acm/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/acm/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6530 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/acm/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.871989 localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6200 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/context.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    63526 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/helpers.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    38422 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/integration.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    14794 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/invocations.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2725 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    11959 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/patches.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    74955 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5657 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/router_asf.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    10909 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/templates.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.871989 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    24315 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/api_utils.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.871989 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    11079 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/adapters.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3046 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/dynamodb_event_source_listener.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3064 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/event_source_listener.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3999 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/kinesis_event_source_listener.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    12154 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/sqs_event_source_listener.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    19280 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/stream_event_source_listener.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      519 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/hooks.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.871989 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      202 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    17831 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/docker_runtime_executor.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4894 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/executor_endpoint.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    19612 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/lambda_models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    28306 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/lambda_service.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      914 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      406 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/plugins.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    12705 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/runtime_environment.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3908 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/runtime_executor.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    32558 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/version_manager.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    91684 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/lambda_api.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    72329 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/lambda_executors.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1012 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/lambda_models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4273 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/lambda_starter.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    17196 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/lambda_utils.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.871989 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/layerfetcher/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/layerfetcher/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      603 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/layerfetcher/layer_fetcher.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4843 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/packages.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1504 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/plugins.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)   155061 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7878 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/urlrouter.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      396 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/usage.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.875989 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3644 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/api_utils.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2083 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/cfn_utils.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6247 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/deploy.html
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     8939 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/deployment_utils.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.875989 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    12829 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/entities.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7994 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/parameters.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      454 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/policy_loader.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    58585 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/template_deployer.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7483 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/template_preparer.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2341 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/transformers.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1518 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/types.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2044 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/yaml_parser.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.879989 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      428 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    33203 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/apigateway.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    21531 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/awslambda.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1228 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/cdk.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2575 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/certificatemanager.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7311 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/cloudformation.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2283 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/cloudwatch.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5756 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/dynamodb.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    21650 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/ec2.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2890 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/ecr.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3340 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/elasticsearch.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     9484 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/events.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    27850 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/iam.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3365 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/kinesis.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2042 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/kinesisfirehose.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4684 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/kms.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5007 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/logs.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2735 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/opensearch.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1267 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/redshift.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1513 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/resourcegroups.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3727 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/route53.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    13537 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/s3.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6732 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/secretsmanager.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     8861 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/sns.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5059 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/sqs.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3927 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/ssm.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5845 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/stepfunctions.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      668 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/packages.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      247 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/plugins.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    39646 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    23683 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/resource_provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5500 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/service_models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2983 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/stores.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      205 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/usage.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.879989 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudwatch/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudwatch/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    15545 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudwatch/alarm_scheduler.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    16188 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/cloudwatch/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.879989 localstack-core-2.1.1.dev20230628134939/localstack/services/configservice/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/configservice/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)       92 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/configservice/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.879989 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1435 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3959 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/packages.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      234 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/plugins.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    73285 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6106 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/server.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    10712 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/utils.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.879989 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodbstreams/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodbstreams/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4420 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodbstreams/dynamodbstreams_api.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      359 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodbstreams/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6039 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodbstreams/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.879989 localstack-core-2.1.1.dev20230628134939/localstack/services/ec2/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/ec2/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1801 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/ec2/exceptions.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      553 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/ec2/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    20653 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/ec2/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    19131 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/edge.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.887989 localstack-core-2.1.1.dev20230628134939/localstack/services/es/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/es/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      234 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/es/plugins.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    17407 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/es/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.887989 localstack-core-2.1.1.dev20230628134939/localstack/services/events/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/events/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      306 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/events/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    23351 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/events/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2675 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/events/scheduler.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.887989 localstack-core-2.1.1.dev20230628134939/localstack/services/firehose/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/firehose/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6345 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/firehose/mappers.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      620 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/firehose/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    31864 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/firehose/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    24573 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/generic_proxy.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.887989 localstack-core-2.1.1.dev20230628134939/localstack/services/iam/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/iam/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    19690 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/iam/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    16051 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/infra.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    12094 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/internal.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.887989 localstack-core-2.1.1.dev20230628134939/localstack/services/kinesis/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kinesis/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6613 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kinesis/kinesis_mock_server.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)       75 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kinesis/kinesis_starter.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      641 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kinesis/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1719 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kinesis/packages.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      224 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kinesis/plugins.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7005 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kinesis/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.887989 localstack-core-2.1.1.dev20230628134939/localstack/services/kms/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kms/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      376 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kms/exceptions.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2688 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kms/local_kms_provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2592 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kms/local_kms_server.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    28575 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kms/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      837 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kms/packages.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      211 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kms/plugins.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    59738 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kms/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1256 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/kms/utils.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.887989 localstack-core-2.1.1.dev20230628134939/localstack/services/logs/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/logs/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      570 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/logs/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    16491 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/logs/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1411 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/messages.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7244 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/moto.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1903 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/motoserver.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.887989 localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    24407 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/cluster.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    15264 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/cluster_manager.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      631 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    13589 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/packages.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      222 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/plugins.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    27010 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.891989 localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/resource_providers/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/resource_providers/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7615 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/resource_providers/aws_opensearchservice_domain.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     9592 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/versions.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    26188 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/plugins.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    11565 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/providers.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.891989 localstack-core-2.1.1.dev20230628134939/localstack/services/redshift/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/redshift/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2039 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/redshift/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.891989 localstack-core-2.1.1.dev20230628134939/localstack/services/resourcegroups/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/resourcegroups/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      125 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/resourcegroups/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.891989 localstack-core-2.1.1.dev20230628134939/localstack/services/resourcegroupstaggingapi/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/resourcegroupstaggingapi/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      190 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/resourcegroupstaggingapi/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.891989 localstack-core-2.1.1.dev20230628134939/localstack/services/route53/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/route53/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      411 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/route53/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2682 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/route53/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.891989 localstack-core-2.1.1.dev20230628134939/localstack/services/route53resolver/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/route53resolver/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     8323 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/route53resolver/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    33479 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/route53resolver/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2223 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/route53resolver/utils.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.891989 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1974 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/constants.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    12543 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/cors.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3411 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3609 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/multipart_content.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    27704 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/notifications.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    31371 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/presigned_url.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    71397 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    68303 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/s3_listener.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    15062 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/s3_starter.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    17709 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/s3_utils.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     9945 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/utils.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5562 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/virtual_host.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    15516 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3/website_hosting.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.895989 localstack-core-2.1.1.dev20230628134939/localstack/services/s3control/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3control/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      104 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/s3control/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.895989 localstack-core-2.1.1.dev20230628134939/localstack/services/secretsmanager/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/secretsmanager/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    27770 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/secretsmanager/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.895989 localstack-core-2.1.1.dev20230628134939/localstack/services/ses/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/ses/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      441 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/ses/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    21127 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/ses/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.895989 localstack-core-2.1.1.dev20230628134939/localstack/services/sns/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sns/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      778 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sns/constants.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5649 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sns/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    43901 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sns/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    54630 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sns/publisher.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.899989 localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1616 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/constants.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      518 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/exceptions.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    39491 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    54649 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7517 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/query_api.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6878 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/utils.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.899989 localstack-core-2.1.1.dev20230628134939/localstack/services/ssm/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/ssm/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     9298 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/ssm/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.899989 localstack-core-2.1.1.dev20230628134939/localstack/services/ssm/resource_providers/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/ssm/resource_providers/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4055 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/ssm/resource_providers/aws_ssm_parameter.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.899989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.899989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.899989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/antlt4utils/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/antlt4utils/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      844 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/antlt4utils/antlr4utils.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.899989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.899989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.899989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/catch/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/catch/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1098 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/catch/catch_decl.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      155 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/catch/catch_outcome.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3706 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/catch/catcher_decl.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      165 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/catch/catcher_outcome.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      122 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/catch/catcher_props.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      211 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/cause_decl.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      215 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/comment.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      211 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_decl.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.899989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      618 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/custom_error_name.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2660 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/error_equals_decl.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      518 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/error_name.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      646 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/failure_event.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      686 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/states_error_name.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1961 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/states_error_name_type.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.903989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/flow/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/flow/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      299 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/flow/end.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      421 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/flow/next.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      233 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/flow/start_at.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      568 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/parameters.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.903989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/path/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/path/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      708 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/path/input_path.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      719 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/path/items_path.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      649 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/path/output_path.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      767 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/path/result_path.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.903989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.903989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      155 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payload_value.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.903989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadarr/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadarr/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      625 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadarr/payload_arr.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.903989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      643 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1037 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_intrinsic_func.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      803 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_path.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1246 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_path_context_obj.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      699 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_value.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.903989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadtmpl/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadtmpl/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      727 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadtmpl/payload_tmpl.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.907989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      287 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/payload_value_bool.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      277 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/payload_value_float.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      271 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/payload_value_int.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      450 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/payload_value_lit.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      264 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/payload_value_null.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      271 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/payload_value_str.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      659 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/result_selector.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.907989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      679 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/backoff_rate_decl.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      604 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/interval_seconds_decl.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      550 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/max_attempts_decl.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3289 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/retrier_decl.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)       95 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/retrier_outcome.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      122 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/retrier_props.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1434 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/retry_decl.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      105 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/retry_outcome.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.907989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/timeouts/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/timeouts/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1832 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/timeouts/timeout.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      180 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/component.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      890 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/eval_component.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.907989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.915989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      452 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      268 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_bool.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      269 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_float.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      661 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_function.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      265 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_int.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      623 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_json_path.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      647 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_list.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      266 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_string.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      175 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/component.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.915989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      606 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/function.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.915989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.915989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1153 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1698 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_contains.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1760 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_get_item.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1570 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_length.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2277 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_partition.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2077 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_range.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1869 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_unique.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.915989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/encoding_decoding/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/encoding_decoding/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2006 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/encoding_decoding/base_64_decode.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1988 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/encoding_decoding/base_64_encode.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4499 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/factory.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.915989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/generic/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/generic/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3708 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/generic/string_format.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.915989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/hash_calculations/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/hash_calculations/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      154 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/hash_calculations/hash_algorithm.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2837 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/hash_calculations/hash_func.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.915989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3146 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/json_merge.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1297 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/json_to_string.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1387 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/string_to_json.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.923989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/math_operations/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/math_operations/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1936 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/math_operations/math_add.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2307 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/math_operations/math_random.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      576 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1167 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_array.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2143 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_format.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1288 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_json_to_string.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1288 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_string_to_json.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1190 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_uuid.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.923989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/string_operations/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/string_operations/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2138 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/string_operations/string_split.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.923989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/unique_id_generation/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/unique_id_generation/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1176 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/unique_id_generation/uuid.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.923989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/functionname/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/functionname/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      232 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/functionname/custom_function_name.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      209 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/functionname/function_name.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1071 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/functionname/state_fuinction_name_types.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1071 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/functionname/state_function_name_types.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      484 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/functionname/states_function_name.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      398 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/member.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      287 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/member_access.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      221 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/program.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.923989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/program/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/program/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3890 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/program/program.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.923989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5996 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.923989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1559 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/choice_rule.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      144 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/choice_rule_stmt.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      350 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/choices_decl.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.927989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      999 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3059 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_composite.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1268 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_func.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2309 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_operator_type.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1063 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_props.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      157 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_stmt.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.927989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1236 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/factory.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.931989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1422 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/boolean_equals.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3490 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/is_operator.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4233 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/numeric.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4496 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/string_operators.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5038 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/timestamp_operators.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      334 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/operator.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      228 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/default_decl.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2479 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/state_choice.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      361 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_continue_with.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.931989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     8738 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/execute_state.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.931989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.931989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/itemprocessor/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/itemprocessor/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3857 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/itemprocessor/item_processor.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      128 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/itemprocessor/item_processor_props.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      450 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/itemprocessor/processor_config.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      263 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/max_concurrency.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      154 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/mode.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2938 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/state_map.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.935989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_parallel/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_parallel/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1550 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_parallel/branches_decl.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1445 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_parallel/state_parallel.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.935989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2069 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/lambda_eval_utils.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.935989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4102 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/resource.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2785 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5181 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_aws_sdk.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5790 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_callback.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4003 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_lambda.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3954 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_sqs.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4137 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/state_task.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5263 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/state_task_lambda.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.935989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_fail/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_fail/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1150 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_fail/state_fail.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.935989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_pass/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_pass/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      205 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_pass/result.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2524 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_pass/state_pass.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1611 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_props.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.935989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_succeed/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_succeed/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1416 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_succeed/state_succeed.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      346 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_type.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.939989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1151 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/state_wait.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      776 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/variable.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.943989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      600 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/seconds.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      762 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/seconds_path.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1352 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/timestamp.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1041 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/timestamp_path.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1694 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/wait_function.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      278 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/states.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.943989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.943989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/callback/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/callback/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3387 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/callback/callback.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.943989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/contextobject/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/contextobject/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1366 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/contextobject/contex_object.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      498 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/count_down_latch.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5122 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/environment.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.943989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/event/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/event/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3681 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/event/event_detail.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1207 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/event/event_history.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1707 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/program_worker.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.943989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/programstate/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/programstate/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      140 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/programstate/program_ended.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      347 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/programstate/program_error.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      945 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/programstate/program_running.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)       50 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/programstate/program_state.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      464 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/programstate/program_stopped.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.943989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      790 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/asl_parser.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.943989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/intrinsic/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/intrinsic/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      876 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/intrinsic/intrinsic_parser.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5292 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/intrinsic/preprocessor.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    31716 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/preprocessor.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      964 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/typed_props.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.943989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/utils/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/utils/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      373 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/utils/encoding.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      352 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/utils/json_path.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.943989 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/backend/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/backend/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6485 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/backend/execution.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2617 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/backend/execution_worker.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      386 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/backend/execution_worker_comm.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1540 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/backend/state_machine.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      778 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/backend/store.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7014 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/packages.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      262 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/plugins.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2587 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/provider.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    12375 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/provider_v2.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4342 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/stepfunctions_starter.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      629 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/stepfunctions_utils.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    11179 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/stores.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.943989 localstack-core-2.1.1.dev20230628134939/localstack/services/sts/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sts/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      621 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/sts/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.943989 localstack-core-2.1.1.dev20230628134939/localstack/services/support/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/support/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      122 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/support/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.947989 localstack-core-2.1.1.dev20230628134939/localstack/services/swf/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/swf/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      106 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/swf/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.947989 localstack-core-2.1.1.dev20230628134939/localstack/services/transcribe/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/transcribe/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      376 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/transcribe/models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    12937 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/services/transcribe/provider.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.951989 localstack-core-2.1.1.dev20230628134939/localstack/state/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      307 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/state/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3774 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/state/core.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6216 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/state/inspect.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    11061 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/state/pickle.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      751 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/state/snapshot.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.951989 localstack-core-2.1.1.dev20230628134939/localstack/testing/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.951989 localstack-core-2.1.1.dev20230628134939/localstack/testing/aws/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/aws/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5828 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/aws/asf_utils.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1466 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/aws/cloudformation_utils.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4452 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/aws/lambda_utils.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6709 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/aws/util.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.951989 localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2847 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/cloudtrail_tracking.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1611 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/detect_thread_leakage.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1089 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/filters.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1337 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/find_orphaned_snapshots.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1473 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/fixture_conflicts.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    69752 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/fixtures.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2320 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/metric_collection.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4565 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/snapshot.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      941 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/util.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.951989 localstack-core-2.1.1.dev20230628134939/localstack/testing/snapshots/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      158 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/snapshots/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    12355 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/snapshots/prototype.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5012 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/snapshots/report.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     9496 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/snapshots/transformer.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    26679 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/testing/snapshots/transformer_utility.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.955989 localstack-core-2.1.1.dev20230628134939/localstack/utils/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/__init__.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.955989 localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      290 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2410 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/cli.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3102 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/client.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      582 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/events.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1397 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/logger.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3324 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/metadata.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     8421 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/publisher.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3926 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/service_request_aggregator.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3841 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/usage.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     8479 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/archives.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      282 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/async_utils.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4396 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/asyncio.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2415 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/auth.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.959989 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    13775 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/arns.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    14834 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/aws_models.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    10896 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/aws_responses.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    17098 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/aws_stack.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2926 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/client.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    13571 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/client_types.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5833 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/dead_letter_queue.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    11782 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/message_forwarding.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3437 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/queries.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7927 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/request_context.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7915 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/resources.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6780 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/templating.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    24132 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/bootstrap.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.959989 localstack-core-2.1.1.dev20230628134939/localstack/utils/cloudwatch/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/cloudwatch/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6253 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/cloudwatch/cloudwatch_util.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    16629 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/collections.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6561 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/common.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2343 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/config_listener.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5253 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/container_networking.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.959989 localstack-core-2.1.1.dev20230628134939/localstack/utils/container_utils/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/container_utils/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    45834 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/container_utils/container_client.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    32496 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/container_utils/docker_cmd_client.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    33160 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/container_utils/docker_sdk_client.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      701 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/coverage_docs.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     7181 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/crypto.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4683 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/diagnose.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     9032 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/docker_utils.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     9365 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/files.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2966 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/functions.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     9391 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/http.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6182 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/json.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.959989 localstack-core-2.1.1.dev20230628134939/localstack/utils/kinesis/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/kinesis/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4127 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/kinesis/kclipy_helper.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    19202 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/kinesis/kinesis_connector.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2416 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/kinesis/kinesis_util.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    10069 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/net.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      811 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/no_exit_argument_parser.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1288 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/numbers.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6176 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/objects.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4923 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/patch.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1553 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/platform.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    16617 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/run.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6547 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/scheduler.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.959989 localstack-core-2.1.1.dev20230628134939/localstack/utils/server/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/server/__init__.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    12408 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/server/http2_server.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      149 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/server/multiserver.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5822 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/server/proxy_server.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     6037 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/serving.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2300 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/ssl.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5724 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/strings.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3776 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/sync.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      829 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/tagging.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2952 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/tail.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    23579 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/testutil.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     4851 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/threads.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1834 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/time.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1235 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/urls.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3202 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/venv.py
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1146 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/localstack/utils/xml.py
-drwxrwxr-x   0 circleci  (1001) circleci  (1002)        0 2023-06-28 13:49:46.963989 localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/
--rw-rw-r--   0 circleci  (1001) circleci  (1002)      652 2023-06-28 13:49:46.000000 localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/PKG-INFO
--rw-rw-r--   0 circleci  (1001) circleci  (1002)    38661 2023-06-28 13:49:46.000000 localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/SOURCES.txt
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        1 2023-06-28 13:49:46.000000 localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/dependency_links.txt
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5258 2023-06-28 13:49:46.000000 localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/entry_points.txt
--rw-rw-r--   0 circleci  (1001) circleci  (1002)        1 2023-06-28 13:49:42.000000 localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/not-zip-safe
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     5349 2023-06-28 13:49:42.000000 localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/plux.json
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     2855 2023-06-28 13:49:46.000000 localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/requires.txt
--rw-rw-r--   0 circleci  (1001) circleci  (1002)       11 2023-06-28 13:49:46.000000 localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/top_level.txt
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     1450 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/pyproject.toml
--rw-rw-r--   0 circleci  (1001) circleci  (1002)     3186 2023-06-28 13:49:46.963989 localstack-core-2.1.1.dev20230628134939/setup.cfg
--rwxrwxr-x   0 circleci  (1001) circleci  (1002)       60 2023-06-28 13:04:13.000000 localstack-core-2.1.1.dev20230628134939/setup.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.203004 localstack-core-2.1.1.dev20230628135412/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      606 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/LICENSE.txt
+-rw-rw-r--   0 runner    (1000) runner    (1001)      216 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/MANIFEST.in
+-rw-rw-r--   0 runner    (1000) runner    (1001)    15152 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/Makefile
+-rw-rw-r--   0 runner    (1000) runner    (1001)      652 2023-06-28 13:55:53.203004 localstack-core-2.1.1.dev20230628135412/PKG-INFO
+-rw-rw-r--   0 runner    (1000) runner    (1001)    11768 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/README.md
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.115001 localstack-core-2.1.1.dev20230628135412/bin/
+-rwxrwxr-x   0 runner    (1000) runner    (1001)      543 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/bin/localstack
+-rwxrwxr-x   0 runner    (1000) runner    (1001)     5936 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/bin/localstack-supervisor
+-rw-rw-r--   0 runner    (1000) runner    (1001)       29 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/bin/localstack.bat
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.115001 localstack-core-2.1.1.dev20230628135412/localstack/
+-rw-rw-r--   0 runner    (1000) runner    (1001)       40 2023-06-28 13:54:12.000000 localstack-core-2.1.1.dev20230628135412/localstack/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.119001 localstack-core-2.1.1.dev20230628135412/localstack/aws/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3959 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/accounts.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.119001 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      371 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.119001 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/acm/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    17594 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/acm/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.119001 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/apigateway/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    72874 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/apigateway/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.119001 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/cloudcontrol/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    10727 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/cloudcontrol/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.119001 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/cloudformation/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    86365 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/cloudformation/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.119001 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/cloudwatch/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    42875 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/cloudwatch/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.119001 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/config/
+-rw-rw-r--   0 runner    (1000) runner    (1001)   127167 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/config/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6224 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/core.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.119001 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/dynamodb/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    81315 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/dynamodb/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.119001 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/dynamodbstreams/
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6998 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/dynamodbstreams/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.119001 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/ec2/
+-rw-rw-r--   0 runner    (1000) runner    (1001)   759908 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/ec2/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/es/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    60425 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/es/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/events/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    55327 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/events/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/firehose/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    42200 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/firehose/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/iam/
+-rw-rw-r--   0 runner    (1000) runner    (1001)   102907 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/iam/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/kinesis/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    25818 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/kinesis/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/kms/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    48826 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/kms/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/lambda_/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    72128 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/lambda_/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/logs/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    38087 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/logs/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/opensearch/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    68386 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/opensearch/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/redshift/
+-rw-rw-r--   0 runner    (1000) runner    (1001)   133756 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/redshift/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/resource_groups/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    14546 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/resource_groups/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/resourcegroupstaggingapi/
+-rw-rw-r--   0 runner    (1000) runner    (1001)     8578 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/resourcegroupstaggingapi/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/route53/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    67927 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/route53/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/route53resolver/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    52075 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/route53resolver/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/s3/
+-rw-rw-r--   0 runner    (1000) runner    (1001)   133075 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/s3/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/s3control/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    65907 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/s3control/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/secretsmanager/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    21744 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/secretsmanager/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/ses/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    54804 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/ses/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/sns/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    27429 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/sns/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/sqs/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    18818 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/sqs/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/ssm/
+-rw-rw-r--   0 runner    (1000) runner    (1001)   215900 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/ssm/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/stepfunctions/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    39472 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/stepfunctions/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/sts/
+-rw-rw-r--   0 runner    (1000) runner    (1001)     9713 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/sts/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.123002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/support/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    16691 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/support/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.127002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/swf/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    59679 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/swf/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.127002 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/transcribe/
+-rw-rw-r--   0 runner    (1000) runner    (1001)    40302 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/api/transcribe/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4447 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/app.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     8455 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/chain.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     8023 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/client.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    22554 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/connect.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     8959 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/forwarder.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      998 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/gateway.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.127002 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1665 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2548 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/analytics.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2137 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/auth.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1337 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/codec.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     9926 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/cors.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2285 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/fallback.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1320 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/internal.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      843 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/internal_requests.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6990 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/legacy.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5983 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/logging.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6368 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/metric_handler.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    10511 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/partition_rewriter.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      650 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/proxy.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      665 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/region.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      862 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/routes.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    11961 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/service.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2924 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/service_plugin.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    13758 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/mocking.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.127002 localstack-core-2.1.1.dev20230628135412/localstack/aws/protocol/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/protocol/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    15278 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/protocol/op_router.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    49972 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/protocol/parser.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    75997 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/protocol/serializer.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    14590 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/protocol/service_router.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5316 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/protocol/validate.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1912 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/proxy.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    20281 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/scaffold.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.131002 localstack-core-2.1.1.dev20230628135412/localstack/aws/serving/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/serving/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2377 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/serving/asgi.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1060 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/serving/edge.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1424 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/serving/hypercorn.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      775 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/serving/werkzeug.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1446 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/serving/wsgi.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7908 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/skeleton.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    28256 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/spec-patches.json
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7072 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/spec.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    12624 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/aws/trace.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.131002 localstack-core-2.1.1.dev20230628135412/localstack/cli/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      176 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/cli/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      346 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/cli/console.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    28010 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/cli/localstack.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4220 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/cli/lpm.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      477 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/cli/main.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      879 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/cli/plugin.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3429 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/cli/plugins.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1385 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/cli/profiles.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    50628 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/config.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     8070 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/constants.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.131002 localstack-core-2.1.1.dev20230628135412/localstack/contrib/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      144 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/contrib/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    11774 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/deprecations.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.131002 localstack-core-2.1.1.dev20230628135412/localstack/extensions/
+-rw-rw-r--   0 runner    (1000) runner    (1001)       95 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/extensions/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.131002 localstack-core-2.1.1.dev20230628135412/localstack/extensions/api/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      138 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/extensions/api/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      686 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/extensions/api/aws.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2588 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/extensions/api/extension.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      422 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/extensions/api/http.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)       84 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/extensions/api/runtime.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      104 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/extensions/api/services.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.131002 localstack-core-2.1.1.dev20230628135412/localstack/http/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      213 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/http/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2933 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/http/adapters.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    14626 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/http/asgi.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5518 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/http/client.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2397 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/http/dispatcher.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5116 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/http/hypercorn.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7159 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/http/proxy.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    11089 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/http/request.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4124 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/http/resource.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3232 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/http/response.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    17344 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/http/router.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.135002 localstack-core-2.1.1.dev20230628135412/localstack/logging/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/logging/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4844 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/logging/format.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4230 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/logging/setup.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.135002 localstack-core-2.1.1.dev20230628135412/localstack/packages/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      533 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/packages/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    15427 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/packages/api.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6728 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/packages/core.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1296 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/packages/debugpy.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1390 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/packages/ffmpeg.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      337 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/packages/plugins.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1313 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/packages/terraform.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1174 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/plugins.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.135002 localstack-core-2.1.1.dev20230628135412/localstack/runtime/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/runtime/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2672 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/runtime/analytics.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      154 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/runtime/events.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      289 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/runtime/exceptions.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3114 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/runtime/hooks.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6440 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/runtime/init.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      817 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/runtime/main.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1415 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/runtime/shutdown.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.135002 localstack-core-2.1.1.dev20230628135412/localstack/services/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.135002 localstack-core-2.1.1.dev20230628135412/localstack/services/acm/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/acm/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6530 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/acm/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.139002 localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6200 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/context.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    63526 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/helpers.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    38422 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/integration.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    14794 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/invocations.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2725 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    11959 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/patches.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    74955 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5657 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/router_asf.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    10909 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/templates.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.139002 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    24315 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/api_utils.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.143002 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    11079 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/adapters.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3046 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/dynamodb_event_source_listener.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3064 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/event_source_listener.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3999 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/kinesis_event_source_listener.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    12154 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/sqs_event_source_listener.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    19280 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/stream_event_source_listener.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      519 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/hooks.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.143002 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      202 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    17831 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/docker_runtime_executor.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4894 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/executor_endpoint.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    19612 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/lambda_models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    28306 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/lambda_service.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      914 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      406 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/plugins.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    12705 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/runtime_environment.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3908 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/runtime_executor.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    32558 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/version_manager.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    91684 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/lambda_api.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    72329 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/lambda_executors.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1012 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/lambda_models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4273 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/lambda_starter.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    17196 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/lambda_utils.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.143002 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/layerfetcher/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/layerfetcher/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      603 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/layerfetcher/layer_fetcher.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4843 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/packages.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1504 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/plugins.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)   155061 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7878 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/urlrouter.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      396 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/usage.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.143002 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3644 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/api_utils.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2083 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/cfn_utils.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6247 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/deploy.html
+-rw-rw-r--   0 runner    (1000) runner    (1001)     8939 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/deployment_utils.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.147002 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    12922 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/entities.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     8428 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/parameters.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      454 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/policy_loader.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    59642 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/template_deployer.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7483 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/template_preparer.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2341 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/transformers.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1518 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/types.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2044 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/yaml_parser.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.151003 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      428 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    33203 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/apigateway.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    21531 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/awslambda.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1228 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/cdk.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2575 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/certificatemanager.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7311 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/cloudformation.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2283 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/cloudwatch.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5756 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/dynamodb.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    21650 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/ec2.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2890 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/ecr.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3340 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/elasticsearch.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     9484 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/events.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    27850 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/iam.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3365 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/kinesis.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2042 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/kinesisfirehose.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4684 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/kms.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5007 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/logs.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2735 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/opensearch.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1267 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/redshift.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1513 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/resourcegroups.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3727 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/route53.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    13537 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/s3.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6732 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/secretsmanager.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     8861 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/sns.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5059 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/sqs.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3927 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/ssm.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5845 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/stepfunctions.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      668 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/packages.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      247 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/plugins.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    39841 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    23683 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/resource_provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5500 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/service_models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2983 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/stores.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      205 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/usage.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.151003 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudwatch/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudwatch/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    15545 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudwatch/alarm_scheduler.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    16188 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/cloudwatch/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.151003 localstack-core-2.1.1.dev20230628135412/localstack/services/configservice/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/configservice/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)       92 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/configservice/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.151003 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1435 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3959 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/packages.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      234 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/plugins.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    73285 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6106 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/server.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    10712 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/utils.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.151003 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodbstreams/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodbstreams/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4420 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodbstreams/dynamodbstreams_api.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      359 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodbstreams/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6039 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodbstreams/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.151003 localstack-core-2.1.1.dev20230628135412/localstack/services/ec2/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/ec2/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1801 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/ec2/exceptions.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      553 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/ec2/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    20653 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/ec2/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    19131 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/edge.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.151003 localstack-core-2.1.1.dev20230628135412/localstack/services/es/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/es/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      234 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/es/plugins.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    17407 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/es/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.151003 localstack-core-2.1.1.dev20230628135412/localstack/services/events/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/events/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      306 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/events/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    23359 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/events/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2675 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/events/scheduler.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.155003 localstack-core-2.1.1.dev20230628135412/localstack/services/firehose/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/firehose/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6345 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/firehose/mappers.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      620 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/firehose/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    31864 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/firehose/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    24573 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/generic_proxy.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.155003 localstack-core-2.1.1.dev20230628135412/localstack/services/iam/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/iam/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    19690 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/iam/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    16051 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/infra.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    12094 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/internal.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.155003 localstack-core-2.1.1.dev20230628135412/localstack/services/kinesis/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kinesis/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6613 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kinesis/kinesis_mock_server.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)       75 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kinesis/kinesis_starter.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      641 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kinesis/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1719 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kinesis/packages.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      224 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kinesis/plugins.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7005 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kinesis/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.155003 localstack-core-2.1.1.dev20230628135412/localstack/services/kms/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kms/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      376 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kms/exceptions.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2688 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kms/local_kms_provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2592 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kms/local_kms_server.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    28575 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kms/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      837 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kms/packages.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      211 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kms/plugins.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    59738 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kms/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1256 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/kms/utils.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.155003 localstack-core-2.1.1.dev20230628135412/localstack/services/logs/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/logs/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      570 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/logs/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    16491 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/logs/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1411 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/messages.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7244 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/moto.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1903 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/motoserver.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.159003 localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    24407 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/cluster.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    15264 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/cluster_manager.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      631 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    13589 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/packages.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      222 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/plugins.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    27010 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.159003 localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/resource_providers/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/resource_providers/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7615 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/resource_providers/aws_opensearchservice_domain.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     9592 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/versions.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    26188 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/plugins.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    11565 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/providers.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.159003 localstack-core-2.1.1.dev20230628135412/localstack/services/redshift/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/redshift/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2039 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/redshift/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.159003 localstack-core-2.1.1.dev20230628135412/localstack/services/resourcegroups/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/resourcegroups/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      125 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/resourcegroups/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.159003 localstack-core-2.1.1.dev20230628135412/localstack/services/resourcegroupstaggingapi/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/resourcegroupstaggingapi/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      190 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/resourcegroupstaggingapi/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.159003 localstack-core-2.1.1.dev20230628135412/localstack/services/route53/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/route53/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      411 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/route53/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2682 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/route53/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.159003 localstack-core-2.1.1.dev20230628135412/localstack/services/route53resolver/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/route53resolver/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     8323 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/route53resolver/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    33479 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/route53resolver/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2223 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/route53resolver/utils.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.163003 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1974 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/constants.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    12543 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/cors.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3411 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3609 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/multipart_content.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    27704 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/notifications.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    31371 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/presigned_url.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    71397 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    68303 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/s3_listener.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    15062 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/s3_starter.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    17709 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/s3_utils.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     9945 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/utils.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5562 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/virtual_host.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    15516 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3/website_hosting.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.163003 localstack-core-2.1.1.dev20230628135412/localstack/services/s3control/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3control/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      104 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/s3control/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.163003 localstack-core-2.1.1.dev20230628135412/localstack/services/secretsmanager/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/secretsmanager/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    27770 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/secretsmanager/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.163003 localstack-core-2.1.1.dev20230628135412/localstack/services/ses/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/ses/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      441 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/ses/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    21127 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/ses/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.163003 localstack-core-2.1.1.dev20230628135412/localstack/services/sns/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sns/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      778 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sns/constants.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5649 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sns/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    43901 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sns/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    54630 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sns/publisher.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.163003 localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1616 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/constants.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      518 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/exceptions.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    39491 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    54649 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7517 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/query_api.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6878 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/utils.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.163003 localstack-core-2.1.1.dev20230628135412/localstack/services/ssm/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/ssm/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     9298 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/ssm/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.163003 localstack-core-2.1.1.dev20230628135412/localstack/services/ssm/resource_providers/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/ssm/resource_providers/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4055 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/ssm/resource_providers/aws_ssm_parameter.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.167003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.167003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.167003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/antlt4utils/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/antlt4utils/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      844 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/antlt4utils/antlr4utils.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.167003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.167003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.167003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/catch/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/catch/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1098 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/catch/catch_decl.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      155 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/catch/catch_outcome.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3706 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/catch/catcher_decl.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      165 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/catch/catcher_outcome.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      122 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/catch/catcher_props.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      211 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/cause_decl.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      215 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/comment.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      211 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_decl.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.167003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      618 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/custom_error_name.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2660 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/error_equals_decl.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      518 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/error_name.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      646 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/failure_event.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      686 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/states_error_name.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1961 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/states_error_name_type.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.171003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/flow/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/flow/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      299 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/flow/end.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      421 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/flow/next.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      233 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/flow/start_at.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      568 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/parameters.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.171003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/path/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/path/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      708 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/path/input_path.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      719 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/path/items_path.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      649 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/path/output_path.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      767 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/path/result_path.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.171003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.171003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      155 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payload_value.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.171003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadarr/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadarr/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      625 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadarr/payload_arr.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.171003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      643 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1037 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_intrinsic_func.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      803 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_path.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1246 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_path_context_obj.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      699 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_value.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.171003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadtmpl/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadtmpl/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      727 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadtmpl/payload_tmpl.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.171003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      287 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/payload_value_bool.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      277 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/payload_value_float.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      271 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/payload_value_int.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      450 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/payload_value_lit.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      264 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/payload_value_null.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      271 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadvaluelit/payload_value_str.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      659 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/result_selector.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.175003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      679 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/backoff_rate_decl.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      604 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/interval_seconds_decl.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      550 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/max_attempts_decl.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3289 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/retrier_decl.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)       95 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/retrier_outcome.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      122 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/retrier_props.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1434 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/retry_decl.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      105 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/retry_outcome.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.175003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/timeouts/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/timeouts/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1832 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/timeouts/timeout.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      180 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/component.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      890 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/eval_component.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.175003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.175003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      452 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      268 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_bool.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      269 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_float.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      661 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_function.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      265 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_int.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      623 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_json_path.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      647 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_list.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      266 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_string.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      175 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/component.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.175003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      606 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/function.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.175003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.179003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1153 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1698 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_contains.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1760 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_get_item.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1570 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_length.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2277 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_partition.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2077 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_range.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1869 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_unique.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.179003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/encoding_decoding/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/encoding_decoding/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2006 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/encoding_decoding/base_64_decode.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1988 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/encoding_decoding/base_64_encode.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4499 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/factory.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.179003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/generic/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/generic/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3708 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/generic/string_format.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.179003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/hash_calculations/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/hash_calculations/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      154 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/hash_calculations/hash_algorithm.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2837 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/hash_calculations/hash_func.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.179003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3146 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/json_merge.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1297 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/json_to_string.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1387 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/string_to_json.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.179003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/math_operations/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/math_operations/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1936 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/math_operations/math_add.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2307 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/math_operations/math_random.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      576 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1167 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_array.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2143 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_format.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1288 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_json_to_string.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1288 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_string_to_json.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1190 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_uuid.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.179003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/string_operations/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/string_operations/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2138 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/string_operations/string_split.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.179003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/unique_id_generation/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/unique_id_generation/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1176 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/unique_id_generation/uuid.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.179003 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/functionname/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/functionname/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      232 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/functionname/custom_function_name.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      209 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/functionname/function_name.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1071 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/functionname/state_fuinction_name_types.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1071 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/functionname/state_function_name_types.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      484 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/functionname/states_function_name.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      398 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/member.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      287 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/member_access.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      221 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/program.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.183004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/program/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/program/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3890 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/program/program.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.183004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5996 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.183004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1559 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/choice_rule.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      144 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/choice_rule_stmt.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      350 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/choices_decl.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.183004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      999 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3059 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_composite.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1268 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_func.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2309 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_operator_type.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1063 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_props.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      157 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_stmt.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.183004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1236 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/factory.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.183004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1422 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/boolean_equals.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3490 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/is_operator.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4233 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/numeric.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4496 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/string_operators.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5038 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/timestamp_operators.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      334 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/operator.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      228 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/default_decl.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2479 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/state_choice.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      361 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_continue_with.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.183004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     8738 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/execute_state.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.183004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.187004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/itemprocessor/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/itemprocessor/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3857 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/itemprocessor/item_processor.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      128 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/itemprocessor/item_processor_props.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      450 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/itemprocessor/processor_config.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      263 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/max_concurrency.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      154 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/mode.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2938 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/state_map.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.187004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_parallel/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_parallel/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1550 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_parallel/branches_decl.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1445 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_parallel/state_parallel.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.187004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2069 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/lambda_eval_utils.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.187004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4102 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/resource.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2785 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5181 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_aws_sdk.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5790 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_callback.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4003 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_lambda.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3954 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_sqs.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4137 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/state_task.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5263 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/state_task_lambda.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.187004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_fail/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_fail/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1150 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_fail/state_fail.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.187004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_pass/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_pass/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      205 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_pass/result.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2524 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_pass/state_pass.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1611 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_props.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.187004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_succeed/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_succeed/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1416 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_succeed/state_succeed.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      346 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_type.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.187004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1151 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/state_wait.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      776 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/variable.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.187004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      600 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/seconds.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      762 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/seconds_path.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1352 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/timestamp.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1041 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/timestamp_path.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1694 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/wait_function.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      278 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/states.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.187004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.187004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/callback/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/callback/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3387 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/callback/callback.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.187004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/contextobject/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/contextobject/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1366 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/contextobject/contex_object.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      498 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/count_down_latch.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5122 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/environment.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.191004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/event/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/event/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3681 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/event/event_detail.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1207 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/event/event_history.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1707 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/program_worker.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.191004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/programstate/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/programstate/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      140 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/programstate/program_ended.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      347 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/programstate/program_error.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      945 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/programstate/program_running.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)       50 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/programstate/program_state.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      464 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/programstate/program_stopped.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.191004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      790 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/asl_parser.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.191004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/intrinsic/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/intrinsic/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      876 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/intrinsic/intrinsic_parser.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5292 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/intrinsic/preprocessor.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    31716 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/preprocessor.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      964 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/typed_props.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.191004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/utils/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/utils/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      373 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/utils/encoding.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      352 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/utils/json_path.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.191004 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/backend/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/backend/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6485 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/backend/execution.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2617 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/backend/execution_worker.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      386 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/backend/execution_worker_comm.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1540 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/backend/state_machine.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      778 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/backend/store.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7014 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/packages.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      262 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/plugins.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2587 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/provider.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    12375 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/provider_v2.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4342 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/stepfunctions_starter.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      629 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/stepfunctions_utils.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    11179 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/stores.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.191004 localstack-core-2.1.1.dev20230628135412/localstack/services/sts/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sts/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      621 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/sts/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.191004 localstack-core-2.1.1.dev20230628135412/localstack/services/support/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/support/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      122 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/support/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.191004 localstack-core-2.1.1.dev20230628135412/localstack/services/swf/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/swf/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      106 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/swf/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.191004 localstack-core-2.1.1.dev20230628135412/localstack/services/transcribe/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/transcribe/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      376 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/transcribe/models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    12937 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/services/transcribe/provider.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.191004 localstack-core-2.1.1.dev20230628135412/localstack/state/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      307 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/state/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3774 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/state/core.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6216 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/state/inspect.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    11061 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/state/pickle.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      751 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/state/snapshot.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.191004 localstack-core-2.1.1.dev20230628135412/localstack/testing/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.195004 localstack-core-2.1.1.dev20230628135412/localstack/testing/aws/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/aws/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5828 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/aws/asf_utils.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1466 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/aws/cloudformation_utils.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4452 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/aws/lambda_utils.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6709 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/aws/util.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.195004 localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2847 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/cloudtrail_tracking.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1611 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/detect_thread_leakage.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1089 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/filters.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1337 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/find_orphaned_snapshots.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1473 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/fixture_conflicts.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    69752 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/fixtures.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2320 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/metric_collection.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4565 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/snapshot.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      941 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/util.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.195004 localstack-core-2.1.1.dev20230628135412/localstack/testing/snapshots/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      158 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/snapshots/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    12355 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/snapshots/prototype.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5012 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/snapshots/report.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     9496 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/snapshots/transformer.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    26679 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/testing/snapshots/transformer_utility.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.199004 localstack-core-2.1.1.dev20230628135412/localstack/utils/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/__init__.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.199004 localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      290 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2410 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/cli.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3102 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/client.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      582 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/events.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1397 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/logger.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3324 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/metadata.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     8421 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/publisher.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3926 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/service_request_aggregator.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3841 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/usage.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     8479 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/archives.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      282 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/async_utils.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4396 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/asyncio.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2415 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/auth.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.199004 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    13775 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/arns.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    14834 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/aws_models.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    10896 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/aws_responses.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    17098 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/aws_stack.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2926 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/client.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    13571 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/client_types.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5833 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/dead_letter_queue.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    11782 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/message_forwarding.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3437 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/queries.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7927 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/request_context.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7915 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/resources.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6780 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/templating.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    23586 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/bootstrap.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.199004 localstack-core-2.1.1.dev20230628135412/localstack/utils/cloudwatch/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/cloudwatch/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6253 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/cloudwatch/cloudwatch_util.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    16629 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/collections.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6561 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/common.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2343 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/config_listener.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5253 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/container_networking.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.203004 localstack-core-2.1.1.dev20230628135412/localstack/utils/container_utils/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/container_utils/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    46134 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/container_utils/container_client.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    32734 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/container_utils/docker_cmd_client.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    33236 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/container_utils/docker_sdk_client.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      701 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/coverage_docs.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     7181 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/crypto.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4683 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/diagnose.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     9032 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/docker_utils.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     9365 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/files.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2966 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/functions.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     9391 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/http.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6182 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/json.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.203004 localstack-core-2.1.1.dev20230628135412/localstack/utils/kinesis/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/kinesis/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4127 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/kinesis/kclipy_helper.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    19202 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/kinesis/kinesis_connector.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2416 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/kinesis/kinesis_util.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    10069 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/net.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      811 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/no_exit_argument_parser.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1288 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/numbers.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6176 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/objects.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4923 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/patch.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1553 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/platform.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    16615 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/run.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6547 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/scheduler.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.203004 localstack-core-2.1.1.dev20230628135412/localstack/utils/server/
+-rw-rw-r--   0 runner    (1000) runner    (1001)        0 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/server/__init__.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    12408 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/server/http2_server.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      149 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/server/multiserver.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5822 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/server/proxy_server.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     6037 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/serving.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2300 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/ssl.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5724 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/strings.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3776 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/sync.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)      829 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/tagging.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2952 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/tail.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)    23579 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/testutil.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     4851 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/threads.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1834 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/time.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1235 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/urls.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3202 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/venv.py
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1146 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/localstack/utils/xml.py
+drwxrwxr-x   0 runner    (1000) runner    (1001)        0 2023-06-28 13:55:53.203004 localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/
+-rw-rw-r--   0 runner    (1000) runner    (1001)      652 2023-06-28 13:55:52.000000 localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/PKG-INFO
+-rw-rw-r--   0 runner    (1000) runner    (1001)    38661 2023-06-28 13:55:53.000000 localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/SOURCES.txt
+-rw-rw-r--   0 runner    (1000) runner    (1001)        1 2023-06-28 13:55:52.000000 localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/dependency_links.txt
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5258 2023-06-28 13:55:53.000000 localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/entry_points.txt
+-rw-rw-r--   0 runner    (1000) runner    (1001)        1 2023-06-28 13:55:49.000000 localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/not-zip-safe
+-rw-rw-r--   0 runner    (1000) runner    (1001)     5349 2023-06-28 13:55:49.000000 localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/plux.json
+-rw-rw-r--   0 runner    (1000) runner    (1001)     2855 2023-06-28 13:55:52.000000 localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/requires.txt
+-rw-rw-r--   0 runner    (1000) runner    (1001)       11 2023-06-28 13:55:52.000000 localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/top_level.txt
+-rw-rw-r--   0 runner    (1000) runner    (1001)     1450 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/pyproject.toml
+-rw-rw-r--   0 runner    (1000) runner    (1001)     3186 2023-06-28 13:55:53.203004 localstack-core-2.1.1.dev20230628135412/setup.cfg
+-rwxrwxr-x   0 runner    (1000) runner    (1001)       60 2023-06-28 13:54:00.000000 localstack-core-2.1.1.dev20230628135412/setup.py
```

### Comparing `localstack-core-2.1.1.dev20230628134939/LICENSE.txt` & `localstack-core-2.1.1.dev20230628135412/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/Makefile` & `localstack-core-2.1.1.dev20230628135412/Makefile`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/PKG-INFO` & `localstack-core-2.1.1.dev20230628135412/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: localstack-core
-Version: 2.1.1.dev20230628134939
+Version: 2.1.1.dev20230628135412
 Summary: The core library and runtime of LocalStack
 Home-page: https://github.com/localstack/localstack
 Author: LocalStack Contributors
 Author-email: info@localstack.cloud
 License: Apache License 2.0
 Classifier: Programming Language :: Python :: 3.10
 Classifier: License :: OSI Approved :: Apache Software License
```

### Comparing `localstack-core-2.1.1.dev20230628134939/README.md` & `localstack-core-2.1.1.dev20230628135412/README.md`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/bin/localstack` & `localstack-core-2.1.1.dev20230628135412/bin/localstack`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/bin/localstack-supervisor` & `localstack-core-2.1.1.dev20230628135412/bin/localstack-supervisor`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/accounts.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/accounts.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/acm/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/acm/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/apigateway/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/apigateway/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/cloudcontrol/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/cloudcontrol/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/cloudformation/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/cloudformation/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/cloudwatch/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/cloudwatch/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/config/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/config/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/core.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/core.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/dynamodb/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/dynamodb/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/dynamodbstreams/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/dynamodbstreams/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/ec2/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/ec2/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/es/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/es/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/events/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/events/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/firehose/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/firehose/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/iam/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/iam/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/kinesis/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/kinesis/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/kms/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/kms/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/lambda_/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/lambda_/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/logs/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/logs/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/opensearch/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/opensearch/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/redshift/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/redshift/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/resource_groups/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/resource_groups/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/resourcegroupstaggingapi/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/resourcegroupstaggingapi/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/route53/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/route53/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/route53resolver/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/route53resolver/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/s3/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/s3/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/s3control/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/s3control/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/secretsmanager/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/secretsmanager/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/ses/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/ses/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/sns/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/sns/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/sqs/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/sqs/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/ssm/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/ssm/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/stepfunctions/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/stepfunctions/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/sts/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/sts/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/support/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/support/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/swf/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/swf/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/api/transcribe/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/api/transcribe/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/app.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/app.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/chain.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/chain.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/client.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/client.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/connect.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/connect.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/forwarder.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/forwarder.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/gateway.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/gateway.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/analytics.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/analytics.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/auth.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/auth.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/codec.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/codec.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/cors.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/cors.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/fallback.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/fallback.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/internal.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/internal.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/internal_requests.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/internal_requests.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/legacy.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/legacy.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/logging.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/logging.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/metric_handler.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/metric_handler.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/partition_rewriter.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/partition_rewriter.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/proxy.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/proxy.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/region.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/region.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/routes.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/routes.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/service.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/service.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/handlers/service_plugin.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/handlers/service_plugin.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/mocking.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/mocking.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/protocol/op_router.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/protocol/op_router.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/protocol/parser.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/protocol/parser.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/protocol/serializer.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/protocol/serializer.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/protocol/service_router.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/protocol/service_router.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/protocol/validate.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/protocol/validate.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/proxy.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/proxy.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/scaffold.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/scaffold.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/serving/asgi.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/serving/asgi.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/serving/edge.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/serving/edge.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/serving/hypercorn.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/serving/hypercorn.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/serving/werkzeug.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/serving/werkzeug.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/serving/wsgi.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/serving/wsgi.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/skeleton.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/skeleton.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/spec-patches.json` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/spec-patches.json`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/spec.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/spec.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/aws/trace.py` & `localstack-core-2.1.1.dev20230628135412/localstack/aws/trace.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/cli/localstack.py` & `localstack-core-2.1.1.dev20230628135412/localstack/cli/localstack.py`

 * *Files 0% similar despite different names*

```diff
@@ -404,20 +404,21 @@
 
     if not no_banner:
         if host:
             console.log("starting LocalStack in host mode :laptop_computer:")
         else:
             console.log("starting LocalStack in Docker mode :whale:")
 
-    bootstrap.prepare_host(console)
-
     if not no_banner and not detached:
         console.rule("LocalStack Runtime Log (press [bold][yellow]CTRL-C[/yellow][/bold] to quit)")
 
     if host:
+        # call hooks to prepare host
+        bootstrap.prepare_host(console)
+
         # from here we abandon the regular CLI control path and start treating the process like a localstack
         # runtime process
         os.environ["LOCALSTACK_CLI"] = "0"
         config.dirs = config.init_directories()
 
         try:
             bootstrap.start_infra_locally()
@@ -432,14 +433,17 @@
     else:
         # make sure to initialize the bootstrap environment and directories for the host (even if we're executing
         # in Docker), to allow starting the container from within other containers (e.g., Github Codespaces).
         config.OVERRIDE_IN_DOCKER = False
         config.is_in_docker = False
         config.dirs = config.init_directories()
 
+        # call hooks to prepare host (note that this call should stay below the config overrides above)
+        bootstrap.prepare_host(console)
+
         if detached:
             bootstrap.start_infra_in_docker_detached(console)
         else:
             bootstrap.start_infra_in_docker()
 
 
 @localstack.command(name="stop", short_help="Stop LocalStack")
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/cli/lpm.py` & `localstack-core-2.1.1.dev20230628135412/localstack/cli/lpm.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/cli/plugin.py` & `localstack-core-2.1.1.dev20230628135412/localstack/cli/plugin.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/cli/plugins.py` & `localstack-core-2.1.1.dev20230628135412/localstack/cli/plugins.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/cli/profiles.py` & `localstack-core-2.1.1.dev20230628135412/localstack/cli/profiles.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/config.py` & `localstack-core-2.1.1.dev20230628135412/localstack/config.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/constants.py` & `localstack-core-2.1.1.dev20230628135412/localstack/constants.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/deprecations.py` & `localstack-core-2.1.1.dev20230628135412/localstack/deprecations.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/extensions/api/aws.py` & `localstack-core-2.1.1.dev20230628135412/localstack/extensions/api/aws.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/extensions/api/extension.py` & `localstack-core-2.1.1.dev20230628135412/localstack/extensions/api/extension.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/http/adapters.py` & `localstack-core-2.1.1.dev20230628135412/localstack/http/adapters.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/http/asgi.py` & `localstack-core-2.1.1.dev20230628135412/localstack/http/asgi.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/http/client.py` & `localstack-core-2.1.1.dev20230628135412/localstack/http/client.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/http/dispatcher.py` & `localstack-core-2.1.1.dev20230628135412/localstack/http/dispatcher.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/http/hypercorn.py` & `localstack-core-2.1.1.dev20230628135412/localstack/http/hypercorn.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/http/proxy.py` & `localstack-core-2.1.1.dev20230628135412/localstack/http/proxy.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/http/request.py` & `localstack-core-2.1.1.dev20230628135412/localstack/http/request.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/http/resource.py` & `localstack-core-2.1.1.dev20230628135412/localstack/http/resource.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/http/response.py` & `localstack-core-2.1.1.dev20230628135412/localstack/http/response.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/http/router.py` & `localstack-core-2.1.1.dev20230628135412/localstack/http/router.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/logging/format.py` & `localstack-core-2.1.1.dev20230628135412/localstack/logging/format.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/logging/setup.py` & `localstack-core-2.1.1.dev20230628135412/localstack/logging/setup.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/packages/__init__.py` & `localstack-core-2.1.1.dev20230628135412/localstack/packages/__init__.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/packages/api.py` & `localstack-core-2.1.1.dev20230628135412/localstack/packages/api.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/packages/core.py` & `localstack-core-2.1.1.dev20230628135412/localstack/packages/core.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/packages/debugpy.py` & `localstack-core-2.1.1.dev20230628135412/localstack/packages/debugpy.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/packages/ffmpeg.py` & `localstack-core-2.1.1.dev20230628135412/localstack/packages/ffmpeg.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/packages/terraform.py` & `localstack-core-2.1.1.dev20230628135412/localstack/packages/terraform.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/plugins.py` & `localstack-core-2.1.1.dev20230628135412/localstack/plugins.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/runtime/analytics.py` & `localstack-core-2.1.1.dev20230628135412/localstack/runtime/analytics.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/runtime/hooks.py` & `localstack-core-2.1.1.dev20230628135412/localstack/runtime/hooks.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/runtime/init.py` & `localstack-core-2.1.1.dev20230628135412/localstack/runtime/init.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/runtime/main.py` & `localstack-core-2.1.1.dev20230628135412/localstack/runtime/main.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/runtime/shutdown.py` & `localstack-core-2.1.1.dev20230628135412/localstack/runtime/shutdown.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/acm/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/acm/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/context.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/context.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/helpers.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/helpers.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/integration.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/integration.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/invocations.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/invocations.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/patches.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/patches.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/router_asf.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/router_asf.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/apigateway/templates.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/apigateway/templates.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/api_utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/api_utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/adapters.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/adapters.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/dynamodb_event_source_listener.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/dynamodb_event_source_listener.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/event_source_listener.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/event_source_listener.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/kinesis_event_source_listener.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/kinesis_event_source_listener.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/sqs_event_source_listener.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/sqs_event_source_listener.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/event_source_listeners/stream_event_source_listener.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/event_source_listeners/stream_event_source_listener.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/hooks.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/hooks.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/docker_runtime_executor.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/docker_runtime_executor.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/executor_endpoint.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/executor_endpoint.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/lambda_models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/lambda_models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/lambda_service.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/lambda_service.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/runtime_environment.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/runtime_environment.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/runtime_executor.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/runtime_executor.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/invocation/version_manager.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/invocation/version_manager.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/lambda_api.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/lambda_api.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/lambda_executors.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/lambda_executors.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/lambda_models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/lambda_models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/lambda_starter.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/lambda_starter.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/lambda_utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/lambda_utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/layerfetcher/layer_fetcher.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/layerfetcher/layer_fetcher.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/packages.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/packages.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/plugins.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/plugins.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/awslambda/urlrouter.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/awslambda/urlrouter.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/api_utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/api_utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/cfn_utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/cfn_utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/deploy.html` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/deploy.html`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/deployment_utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/deployment_utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/entities.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/entities.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,16 @@
 import logging
 from typing import Optional, TypedDict
 
 from localstack.aws.api.cloudformation import Capability, ChangeSetType, Parameter
 from localstack.services.cloudformation.engine.parameters import (
+    StackParameter,
     convert_stack_parameters_to_list,
     map_to_legacy_structure,
+    strip_parameter_type,
 )
 from localstack.utils.aws import arns
 from localstack.utils.collections import select_attributes
 from localstack.utils.json import clone_safe
 from localstack.utils.objects import recurse_object
 from localstack.utils.strings import long_uid, short_uid
 from localstack.utils.time import timestamp_millis
@@ -65,15 +67,15 @@
         template: Optional[StackTemplate] = None,
         template_body: Optional[str] = None,
     ):
         if template is None:
             template = {}
 
         self.resolved_outputs = list()  # TODO
-        self.resolved_parameters: dict[str, Parameter] = {}
+        self.resolved_parameters: dict[str, StackParameter] = {}
 
         self.metadata = metadata or {}
         self.template = template or {}
         self.template_body = template_body
         self._template_raw = clone_safe(self.template)
         self.template_original = clone_safe(self.template)
         # initialize resources
@@ -102,15 +104,15 @@
         self._resource_states = {}
         # list of stack events
         self.events = []
         # list of stack change sets
         self.change_sets = []
         # self.evaluated_conditions = {}
 
-    def set_resolved_parameters(self, resolved_parameters: dict[str, Parameter]):
+    def set_resolved_parameters(self, resolved_parameters: dict[str, StackParameter]):
         self.resolved_parameters = resolved_parameters
         if resolved_parameters:
             self.metadata["Parameters"] = list(resolved_parameters.values())
 
     def describe_details(self):
         attrs = [
             "StackId",
@@ -134,15 +136,15 @@
         result = select_attributes(self.metadata, attrs)
         result["Tags"] = self.tags
         outputs = self.resolved_outputs
         if outputs:
             result["Outputs"] = outputs
         stack_parameters = convert_stack_parameters_to_list(self.resolved_parameters)
         if stack_parameters:
-            result["Parameters"] = stack_parameters
+            result["Parameters"] = [strip_parameter_type(sp) for sp in stack_parameters]
         if not result.get("DriftInformation"):
             result["DriftInformation"] = {"StackDriftStatus": "NOT_CHECKED"}
         for attr in ["Tags", "NotificationARNs"]:
             result.setdefault(attr, [])
         return result
 
     def set_stack_status(self, status):
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/parameters.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/parameters.py`

 * *Files 10% similar despite different names*

```diff
@@ -40,19 +40,25 @@
             # NoEcho=?,
             # ParameterConstraints=?,
             # Description=?
         )
     return result
 
 
+class StackParameter(Parameter):
+    # we need the type information downstream when actually using the resolved value
+    # e.g. in case of lists so that we know that we should interpret the string as a comma-separated list.
+    ParameterType: str
+
+
 def resolve_parameters(
     parameter_declarations: dict[str, ParameterDeclaration],
     new_parameters: dict[str, Parameter],
     old_parameters: dict[str, Parameter],
-) -> dict[str, Parameter]:
+) -> dict[str, StackParameter]:
     """
     Resolves stack parameters or raises an exception if any parameter can not be resolved.
 
     Assumptions:
         - There are no extra undeclared parameters given (validate before calling this method)
 
     TODO: is UsePreviousValue=False equivalent to not specifying it, in all situations?
@@ -63,15 +69,15 @@
     :return: a copy of new_parameters with resolved values
     """
     resolved_parameters = dict()
 
     # populate values for every parameter declared in the template
     for pm in parameter_declarations.values():
         pm_key = pm["ParameterKey"]
-        resolved_param = Parameter(ParameterKey=pm_key)
+        resolved_param = StackParameter(ParameterKey=pm_key, ParameterType=pm["ParameterType"])
         new_parameter = new_parameters.get(pm_key)
         old_parameter = old_parameters.get(pm_key)
 
         if new_parameter is None:
             # since no value has been specified for the deployment, we need to be able to resolve the default or fail
             default_value = pm["DefaultValue"]
             if default_value is None:
@@ -122,15 +128,23 @@
 def resolve_ssm_parameter(stack_parameter_value: str) -> str:
     """
     Resolve the SSM stack parameter from the SSM service with a name equal to the stack parameter value.
     """
     return connect_to().ssm.get_parameter(Name=stack_parameter_value)["Parameter"]["Value"]
 
 
-def convert_stack_parameters_to_list(in_params: dict[str, Parameter] | None) -> list[Parameter]:
+def strip_parameter_type(in_param: StackParameter) -> Parameter:
+    result = in_param.copy()
+    result.pop("ParameterType", None)
+    return result
+
+
+def convert_stack_parameters_to_list(
+    in_params: dict[str, StackParameter] | None
+) -> list[StackParameter]:
     if not in_params:
         return []
     return list(in_params.values())
 
 
 def convert_stack_parameters_to_dict(in_params: list[Parameter] | None) -> dict[str, Parameter]:
     if not in_params:
@@ -147,25 +161,25 @@
 
 class LegacyParameter(TypedDict):
     LogicalResourceId: str
     Type: Literal["Parameter"]
     Properties: LegacyParameterProperties
 
 
-def map_to_legacy_structure(parameter_type: str, new_parameter: Parameter) -> LegacyParameter:
+# TODO: not actually parameter_type but the logical "ID"
+def map_to_legacy_structure(parameter_name: str, new_parameter: StackParameter) -> LegacyParameter:
     """
     Helper util to convert a normal (resolved) stack parameter to a legacy parameter structure that can then be merged with stack resources.
 
-    :param parameter_type: the stack parameter type (e.g. "String", "AWS::SSM::Parameter::Value<String>", ...)
     :param new_parameter: a resolved stack parameter
     :return: legacy parameter that can be merged with stack resources for uniform lookup based on logical ID
     """
     return LegacyParameter(
         LogicalResourceId=new_parameter["ParameterKey"],
         Type="Parameter",
         Properties=LegacyParameterProperties(
-            ParameterType=parameter_type,
+            ParameterType=new_parameter.get("ParameterType"),
             ParameterValue=new_parameter.get("ParameterValue"),
             ResolvedValue=new_parameter.get("ResolvedValue"),
             Value=new_parameter.get("ResolvedValue", new_parameter.get("ParameterValue")),
         ),
     )
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/template_deployer.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/template_deployer.py`

 * *Files 1% similar despite different names*

```diff
@@ -257,16 +257,28 @@
         # 3. the "value" of a resource
 
         resource = resources.get(ref)
         if not resource:
             raise Exception("Should be detected earlier")
 
         # TODO: remove after refactoring parameter resolution
+        # TODO: split this apart in parameter resource types and stack parameter handling
         if resource["Type"] == "Parameter":
-            return resource["Properties"]["Value"]
+            # https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/parameters-section-structure.html
+            # TODO: extract this into a util function and extend type support
+            parameter_type = resource.get("Properties", {}).get("ParameterType")
+            if not parameter_type:
+                # assuming this is an actual resource type now
+                return resource["Properties"]["Value"]
+            else:
+                parameter_type: str = resource["Properties"]["ParameterType"]
+                if parameter_type in ["CommaDelimitedList"] or parameter_type.startswith("List<"):
+                    return [p.strip() for p in resource["Properties"]["Value"].split(",")]
+                else:
+                    return resource["Properties"]["Value"]
         else:
             # TODO: this shouldn't be needed when dependency graph and deployment status is honored
             resolve_refs_recursively(stack_name, resources, mappings, resources.get(ref))
             return get_ref_from_model(resources, ref)
 
     # TODO: remove if tests pass
     is_ref_attribute = attribute in ["Arn"]
@@ -424,17 +436,23 @@
             # TODO: we should check the deployment state and not try to GetAtt from a resource that is still IN_PROGRESS or hasn't started yet.
             if resolved_getatt is None:
                 raise DependencyNotYetSatisfied(resource_ids=resource_logical_id, message="")
             return resolved_getatt
 
         if stripped_fn_lower == "join":
             join_values = value[keys_list[0]][1]
+
+            # this can actually be another ref that produces a list as output
+            if isinstance(join_values, dict):
+                join_values = resolve_refs_recursively(stack_name, resources, mappings, join_values)
+
             join_values = [
                 resolve_refs_recursively(stack_name, resources, mappings, v) for v in join_values
             ]
+
             none_values = [v for v in join_values if v is None]
             if none_values:
                 raise Exception(
                     "Cannot resolve CF fn::Join %s due to null values: %s" % (value, join_values)
                 )
             return value[keys_list[0]][0].join([str(v) for v in join_values])
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/template_preparer.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/template_preparer.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/transformers.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/transformers.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/types.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/types.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/engine/yaml_parser.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/engine/yaml_parser.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/apigateway.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/apigateway.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/awslambda.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/awslambda.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/cdk.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/cdk.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/certificatemanager.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/certificatemanager.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/cloudformation.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/cloudformation.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/cloudwatch.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/cloudwatch.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/dynamodb.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/dynamodb.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/ec2.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/ec2.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/ecr.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/ecr.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/elasticsearch.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/elasticsearch.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/events.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/events.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/iam.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/iam.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/kinesis.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/kinesis.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/kinesisfirehose.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/kinesisfirehose.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/kms.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/kms.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/logs.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/logs.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/opensearch.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/opensearch.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/redshift.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/redshift.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/resourcegroups.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/resourcegroups.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/route53.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/route53.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/s3.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/s3.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/secretsmanager.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/secretsmanager.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/sns.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/sns.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/sqs.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/sqs.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/ssm.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/ssm.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/models/stepfunctions.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/models/stepfunctions.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/packages.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/packages.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/provider.py`

 * *Files 0% similar despite different names*

```diff
@@ -76,14 +76,15 @@
 from localstack.services.cloudformation.engine import template_deployer, template_preparer
 from localstack.services.cloudformation.engine.entities import (
     Stack,
     StackChangeSet,
     StackInstance,
     StackSet,
 )
+from localstack.services.cloudformation.engine.parameters import strip_parameter_type
 from localstack.services.cloudformation.engine.template_deployer import NoStackUpdates
 from localstack.services.cloudformation.engine.template_preparer import (
     FailedTransformationException,
 )
 from localstack.services.cloudformation.stores import (
     find_change_set,
     find_stack,
@@ -186,17 +187,15 @@
             and "Transform" in template.keys()
         ):
             raise InsufficientCapabilitiesException(
                 "Requires capabilities : [CAPABILITY_AUTO_EXPAND]"
             )
 
         # resolve stack parameters
-        new_parameters: dict[str, Parameter] = param_resolver.convert_stack_parameters_to_dict(
-            request.get("Parameters")
-        )
+        new_parameters = param_resolver.convert_stack_parameters_to_dict(request.get("Parameters"))
         parameter_declarations = param_resolver.extract_stack_parameter_declarations(template)
         resolved_parameters = param_resolver.resolve_parameters(
             parameter_declarations=parameter_declarations,
             new_parameters=new_parameters,
             old_parameters={},
         )
 
@@ -486,15 +485,17 @@
         old_parameters: dict[str, Parameter] = {}
         if change_set_type == "UPDATE":
             # add changeset to existing stack
             if stack is None:
                 raise ValidationError(
                     f"Stack '{stack_name}' does not exist."
                 )  # stack should exist already
-            old_parameters = stack.resolved_parameters
+            old_parameters = {
+                k: strip_parameter_type(v) for k, v in stack.resolved_parameters.items()
+            }
         elif change_set_type == "CREATE":
             # create new (empty) stack
             if stack is not None:
                 raise ValidationError(
                     f"Stack {stack_name} already exists"
                 )  # stack should not exist yet (TODO: check proper message)
             empty_stack_template = dict(template)
@@ -608,15 +609,16 @@
             "StackStatus",
             "LastUpdatedTime",
             "DisableRollback",
             "EnableTerminationProtection",
             "Transform",
         ]
         result = remove_attributes(deepcopy(change_set.metadata), attrs)
-        # result["Parameters"] = list(change_set.resolved_parameters.values())
+        # TODO: replace this patch with a better solution
+        result["Parameters"] = [strip_parameter_type(p) for p in result.get("Parameters", [])]
         return result
 
     @handler("DeleteChangeSet")
     def delete_change_set(
         self,
         context: RequestContext,
         change_set_name: ChangeSetNameOrId,
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/resource_provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/resource_provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/service_models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/service_models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudformation/stores.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudformation/stores.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudwatch/alarm_scheduler.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudwatch/alarm_scheduler.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/cloudwatch/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/cloudwatch/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/packages.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/packages.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/server.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/server.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodb/utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodb/utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodbstreams/dynamodbstreams_api.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodbstreams/dynamodbstreams_api.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/dynamodbstreams/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/dynamodbstreams/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/ec2/exceptions.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/ec2/exceptions.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/ec2/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/ec2/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/ec2/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/ec2/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/edge.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/edge.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/es/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/es/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/events/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/events/provider.py`

 * *Files 0% similar despite different names*

```diff
@@ -320,15 +320,15 @@
                 lower_limit = list_of_operators[index + 1]
             if upper_limit and lower_limit and upper_limit < lower_limit:
                 return False
             index = index + 1
     return True
 
 
-def filter_event_with_content_base_parameter(pattern_value, event_value):
+def filter_event_with_content_base_parameter(pattern_value: list, event_value: str | int):
     for element in pattern_value:
         if (isinstance(element, (str, int))) and (event_value == element or element in event_value):
             return True
         elif isinstance(element, dict):
             element_key = list(element.keys())[0]
             element_value = element.get(element_key)
             if element_key.lower() == "prefix":
@@ -444,15 +444,15 @@
                     if isinstance(value.get(key_a), (int, str)):
                         if value_a != value.get(key_a):
                             return False
                     if isinstance(value.get(key_a), list) and value_a not in value.get(key_a):
                         if not handle_prefix_filtering(value.get(key_a), value_a):
                             return False
 
-            # 2. check if the pattern is a list and event values are not contained in itEventsApi
+            # 2. check if the pattern is a list and event values are not contained in it
             if isinstance(value, list):
                 if identify_content_base_parameter_in_pattern(value):
                     if not filter_event_with_content_base_parameter(value, event_value):
                         return False
                 else:
                     if (
                         isinstance(event_value, list)
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/events/scheduler.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/events/scheduler.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/firehose/mappers.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/firehose/mappers.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/firehose/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/firehose/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/firehose/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/firehose/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/generic_proxy.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/generic_proxy.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/iam/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/iam/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/infra.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/infra.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/internal.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/internal.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/kinesis/kinesis_mock_server.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/kinesis/kinesis_mock_server.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/kinesis/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/kinesis/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/kinesis/packages.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/kinesis/packages.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/kinesis/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/kinesis/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/kms/local_kms_provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/kms/local_kms_provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/kms/local_kms_server.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/kms/local_kms_server.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/kms/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/kms/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/kms/packages.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/kms/packages.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/kms/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/kms/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/kms/utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/kms/utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/logs/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/logs/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/logs/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/logs/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/messages.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/messages.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/moto.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/moto.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/motoserver.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/motoserver.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/cluster.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/cluster.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/cluster_manager.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/cluster_manager.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/packages.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/packages.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/resource_providers/aws_opensearchservice_domain.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/resource_providers/aws_opensearchservice_domain.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/opensearch/versions.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/opensearch/versions.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/plugins.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/plugins.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/providers.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/providers.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/redshift/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/redshift/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/route53/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/route53/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/route53resolver/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/route53resolver/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/route53resolver/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/route53resolver/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/route53resolver/utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/route53resolver/utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/constants.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/constants.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/cors.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/cors.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/multipart_content.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/multipart_content.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/notifications.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/notifications.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/presigned_url.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/presigned_url.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/s3_listener.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/s3_listener.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/s3_starter.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/s3_starter.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/s3_utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/s3_utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/virtual_host.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/virtual_host.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/s3/website_hosting.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/s3/website_hosting.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/secretsmanager/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/secretsmanager/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/ses/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/ses/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/sns/constants.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/sns/constants.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/sns/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/sns/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/sns/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/sns/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/sns/publisher.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/sns/publisher.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/constants.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/constants.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/exceptions.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/exceptions.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/query_api.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/query_api.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/sqs/utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/sqs/utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/ssm/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/ssm/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/ssm/resource_providers/aws_ssm_parameter.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/ssm/resource_providers/aws_ssm_parameter.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/antlt4utils/antlr4utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/antlt4utils/antlr4utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/catch/catch_decl.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/catch/catch_decl.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/catch/catcher_decl.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/catch/catcher_decl.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/custom_error_name.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/custom_error_name.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/error_equals_decl.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/error_equals_decl.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/error_name.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/error_name.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/failure_event.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/failure_event.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/states_error_name.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/states_error_name.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/error_name/states_error_name_type.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/error_name/states_error_name_type.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/parameters.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/parameters.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/path/input_path.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/path/input_path.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/path/items_path.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/path/items_path.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/path/output_path.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/path/output_path.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/path/result_path.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/path/result_path.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadarr/payload_arr.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadarr/payload_arr.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_intrinsic_func.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_intrinsic_func.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_path.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_path.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_path_context_obj.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_path_context_obj.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_value.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadbinding/payload_binding_value.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadtmpl/payload_tmpl.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/payload/payloadvalue/payloadtmpl/payload_tmpl.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/result_selector.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/result_selector.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/backoff_rate_decl.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/backoff_rate_decl.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/interval_seconds_decl.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/interval_seconds_decl.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/max_attempts_decl.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/max_attempts_decl.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/retrier_decl.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/retrier_decl.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/retry/retry_decl.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/retry/retry_decl.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/common/timeouts/timeout.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/common/timeouts/timeout.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/eval_component.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/eval_component.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_function.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_function.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_json_path.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_json_path.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_list.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/argument/function_argument_list.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/function.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/function.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_contains.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_contains.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_get_item.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_get_item.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_length.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_length.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_partition.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_partition.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_range.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_range.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_unique.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/array/array_unique.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/encoding_decoding/base_64_decode.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/encoding_decoding/base_64_decode.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/encoding_decoding/base_64_encode.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/encoding_decoding/base_64_encode.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/factory.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/factory.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/generic/string_format.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/generic/string_format.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/hash_calculations/hash_func.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/hash_calculations/hash_func.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/json_merge.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/json_merge.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/json_to_string.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/json_to_string.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/string_to_json.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/json_manipulation/string_to_json.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/math_operations/math_add.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/math_operations/math_add.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/math_operations/math_random.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/math_operations/math_random.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_array.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_array.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_format.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_format.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_json_to_string.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_json_to_string.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_string_to_json.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_string_to_json.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_uuid.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/states_function_uuid.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/string_operations/string_split.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/string_operations/string_split.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/unique_id_generation/uuid.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/function/statesfunction/unique_id_generation/uuid.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/functionname/state_fuinction_name_types.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/functionname/state_fuinction_name_types.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/intrinsic/functionname/state_function_name_types.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/intrinsic/functionname/state_function_name_types.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/program/program.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/program/program.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/choice_rule.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/choice_rule.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_composite.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_composite.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_func.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_func.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_operator_type.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_operator_type.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_props.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/comparison_props.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/factory.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/factory.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/boolean_equals.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/boolean_equals.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/is_operator.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/is_operator.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/numeric.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/numeric.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/string_operators.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/string_operators.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/timestamp_operators.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/comparison/operator/implementations/timestamp_operators.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_choice/state_choice.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_choice/state_choice.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/execute_state.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/execute_state.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/itemprocessor/item_processor.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/itemprocessor/item_processor.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/state_map.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_map/state_map.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_parallel/branches_decl.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_parallel/branches_decl.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_parallel/state_parallel.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_parallel/state_parallel.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/lambda_eval_utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/lambda_eval_utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/resource.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/resource.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_aws_sdk.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_aws_sdk.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_callback.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_callback.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_lambda.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_lambda.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_sqs.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/service/state_task_service_sqs.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/state_task.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/state_task.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/state_task_lambda.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_execution/state_task/state_task_lambda.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_fail/state_fail.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_fail/state_fail.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_pass/state_pass.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_pass/state_pass.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_props.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_props.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_succeed/state_succeed.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_succeed/state_succeed.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/state_wait.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/state_wait.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/variable.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/variable.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/seconds.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/seconds.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/seconds_path.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/seconds_path.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/timestamp.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/timestamp.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/timestamp_path.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/timestamp_path.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/wait_function.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/component/state/state_wait/wait_function/wait_function.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/callback/callback.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/callback/callback.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/contextobject/contex_object.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/contextobject/contex_object.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/environment.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/environment.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/event/event_detail.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/event/event_detail.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/event/event_history.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/event/event_history.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/program_worker.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/program_worker.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/eval/programstate/program_running.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/eval/programstate/program_running.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/asl_parser.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/asl_parser.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/intrinsic/intrinsic_parser.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/intrinsic/intrinsic_parser.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/intrinsic/preprocessor.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/intrinsic/preprocessor.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/preprocessor.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/preprocessor.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/asl/parse/typed_props.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/asl/parse/typed_props.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/backend/execution.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/backend/execution.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/backend/execution_worker.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/backend/execution_worker.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/backend/state_machine.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/backend/state_machine.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/backend/store.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/backend/store.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/packages.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/packages.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/provider_v2.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/provider_v2.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/stepfunctions_starter.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/stepfunctions_starter.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stepfunctions/stepfunctions_utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stepfunctions/stepfunctions_utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/stores.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/stores.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/sts/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/sts/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/services/transcribe/provider.py` & `localstack-core-2.1.1.dev20230628135412/localstack/services/transcribe/provider.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/state/core.py` & `localstack-core-2.1.1.dev20230628135412/localstack/state/core.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/state/inspect.py` & `localstack-core-2.1.1.dev20230628135412/localstack/state/inspect.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/state/pickle.py` & `localstack-core-2.1.1.dev20230628135412/localstack/state/pickle.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/state/snapshot.py` & `localstack-core-2.1.1.dev20230628135412/localstack/state/snapshot.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/aws/asf_utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/aws/asf_utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/aws/cloudformation_utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/aws/cloudformation_utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/aws/lambda_utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/aws/lambda_utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/aws/util.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/aws/util.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/cloudtrail_tracking.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/cloudtrail_tracking.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/detect_thread_leakage.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/detect_thread_leakage.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/filters.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/filters.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/find_orphaned_snapshots.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/find_orphaned_snapshots.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/fixture_conflicts.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/fixture_conflicts.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/fixtures.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/fixtures.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/metric_collection.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/metric_collection.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/snapshot.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/snapshot.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/pytest/util.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/pytest/util.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/snapshots/prototype.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/snapshots/prototype.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/snapshots/report.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/snapshots/report.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/snapshots/transformer.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/snapshots/transformer.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/testing/snapshots/transformer_utility.py` & `localstack-core-2.1.1.dev20230628135412/localstack/testing/snapshots/transformer_utility.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/cli.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/cli.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/client.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/client.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/events.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/events.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/logger.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/logger.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/metadata.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/metadata.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/publisher.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/publisher.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/service_request_aggregator.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/service_request_aggregator.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/analytics/usage.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/analytics/usage.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/archives.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/archives.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/asyncio.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/asyncio.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/auth.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/auth.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/arns.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/arns.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/aws_models.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/aws_models.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/aws_responses.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/aws_responses.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/aws_stack.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/aws_stack.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/client.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/client.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/client_types.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/client_types.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/dead_letter_queue.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/dead_letter_queue.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/message_forwarding.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/message_forwarding.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/queries.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/queries.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/request_context.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/request_context.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/resources.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/resources.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/aws/templating.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/aws/templating.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/bootstrap.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/bootstrap.py`

 * *Files 2% similar despite different names*

```diff
@@ -240,15 +240,15 @@
 def is_api_enabled(api: str) -> bool:
     apis = get_enabled_apis()
 
     if api in apis:
         return True
 
     for enabled_api in apis:
-        if api.startswith("%s:" % enabled_api):
+        if api.startswith(f"{enabled_api}:"):
             return True
 
     return False
 
 
 def start_infra_locally():
     from localstack.services import infra
@@ -271,17 +271,17 @@
     cmd = ["docker-compose", "-f", compose_file_name, "config"]
     try:
         run(cmd, shell=False, print_error=False)
     except CalledProcessError as e:
         msg = f"{e}\n{to_str(e.output)}".strip()
         raise ValueError(msg)
 
-    # validating docker-compose variable
     import yaml  # keep import here to avoid issues in test Lambdas
 
+    # validating docker-compose variable
     with open(compose_file_name) as file:
         compose_content = yaml.full_load(file)
     services_config = compose_content.get("services", {})
     ls_service_name = [
         name for name, svc in services_config.items() if "localstack" in svc.get("image", "")
     ]
     if not ls_service_name:
@@ -291,69 +291,58 @@
     if len(ls_service_name) > 1:
         warns.append(f"Multiple candidates found for LocalStack service: {ls_service_name}")
     ls_service_name = ls_service_name[0]
     ls_service_details = services_config[ls_service_name]
     image_name = ls_service_details.get("image", "")
     if image_name.split(":")[0] not in constants.OFFICIAL_IMAGES:
         warns.append(
-            'Using custom image "%s", we recommend using an official image: %s'
-            % (image_name, constants.OFFICIAL_IMAGES)
+            f'Using custom image "{image_name}", we recommend using an official image: {constants.OFFICIAL_IMAGES}'
         )
 
     # prepare config options
-    image_name = ls_service_details.get("image")
     container_name = ls_service_details.get("container_name") or ""
     docker_ports = (port.split(":")[-2] for port in ls_service_details.get("ports", []))
     docker_env = dict(
         (env.split("=")[0], env.split("=")[1]) for env in ls_service_details.get("environment", {})
     )
     edge_port = str(docker_env.get("EDGE_PORT") or config.EDGE_PORT)
     main_container = config.MAIN_CONTAINER_NAME
 
     # docker-compose file validation cases
 
     if (main_container not in container_name) and not docker_env.get("MAIN_CONTAINER_NAME"):
         warns.append(
-            'Please use "container_name: %s" or add "MAIN_CONTAINER_NAME" in "environment".'
-            % main_container
+            f'Please use "container_name: {main_container}" or add "MAIN_CONTAINER_NAME" in "environment".'
         )
 
     def port_exposed(port):
         for exposed in docker_ports:
             if re.match(r"^([0-9]+-)?%s(-[0-9]+)?$" % port, exposed):
                 return True
 
     if not port_exposed(edge_port):
         warns.append(
             (
-                "Edge port %s is not exposed. You may have to add the entry "
+                f"Edge port {edge_port} is not exposed. You may have to add the entry "
                 'to the "ports" section of the docker-compose file.'
             )
-            % edge_port
         )
 
     # print warning/info messages
     for warning in warns:
         console.print("[yellow]:warning:[/yellow]", warning)
     if not warns:
         return True
     return False
 
 
 def get_docker_image_to_start():
     image_name = os.environ.get("IMAGE_NAME")
     if not image_name:
         image_name = constants.DOCKER_IMAGE_NAME
-        if os.environ.get("USE_LIGHT_IMAGE") in constants.FALSE_STRINGS:
-            # FIXME deprecated - remove with 2.0
-            LOG.warning(
-                "USE_LIGHT_IMAGE is deprecated (since 1.3.0) and will be removed in upcoming releases of LocalStack! "
-                "The localstack/localstack-full image is deprecated. Please remove this environment variable."
-            )
-            image_name = constants.DOCKER_IMAGE_NAME_FULL
         if is_api_key_configured():
             image_name = constants.DOCKER_IMAGE_NAME_PRO
     return image_name
 
 
 def extract_port_flags(user_flags, port_mappings: PortMappings):
     regex = r"-p\s+([0-9]+)(\-([0-9]+))?:([0-9]+)(\-([0-9]+))?"
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/cloudwatch/cloudwatch_util.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/cloudwatch/cloudwatch_util.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/collections.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/collections.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/common.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/common.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/config_listener.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/config_listener.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/container_networking.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/container_networking.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/container_utils/container_client.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/container_utils/container_client.py`

 * *Files 0% similar despite different names*

```diff
@@ -452,14 +452,22 @@
 
 # TODO: remove Docker/Podman compatibility switches (in particular strip_wellknown_repo_prefixes=...)
 #  from the container client base interface and introduce derived Podman client implementations instead!
 class ContainerClient(metaclass=ABCMeta):
     STOP_TIMEOUT = 0
 
     @abstractmethod
+    def get_system_info(self) -> dict:
+        """Returns the docker system-wide information as dictionary (``docker info``)."""
+
+    def get_system_id(self) -> str:
+        """Returns the unique and stable ID of the docker daemon."""
+        return self.get_system_info()["ID"]
+
+    @abstractmethod
     def get_container_status(self, container_name: str) -> DockerContainerStatus:
         """Returns the status of the container with the given name"""
         pass
 
     def get_networks(self, container_name: str) -> List[str]:
         LOG.debug("Getting networks for container: %s", container_name)
         container_attrs = self.inspect_container(container_name_or_id=container_name)
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/container_utils/docker_cmd_client.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/container_utils/docker_cmd_client.py`

 * *Files 2% similar despite different names*

```diff
@@ -64,14 +64,25 @@
 
     default_run_outfile: Optional[str] = None
 
     def _docker_cmd(self) -> List[str]:
         """Return the string to be used for running Docker commands."""
         return config.DOCKER_CMD.split()
 
+    def get_system_info(self) -> dict:
+        cmd = [
+            *self._docker_cmd(),
+            "info",
+            "--format",
+            "{{json .}}",
+        ]
+        cmd_result = run(cmd)
+
+        return json.loads(cmd_result)
+
     def get_container_status(self, container_name: str) -> DockerContainerStatus:
         cmd = self._docker_cmd()
         cmd += [
             "ps",
             "-a",
             "--filter",
             f"name={container_name}",
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/container_utils/docker_sdk_client.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/container_utils/docker_sdk_client.py`

 * *Files 1% similar despite different names*

```diff
@@ -121,14 +121,17 @@
         target_exists = result.ok
 
         if target_exists:
             stats = json.loads(base64.b64decode(stats).decode("utf-8"))
         target_is_dir = target_exists and bool(stats["mode"] & SDK_ISDIR)
         return target_exists, target_is_dir
 
+    def get_system_info(self) -> dict:
+        return self.client().info()
+
     def get_container_status(self, container_name: str) -> DockerContainerStatus:
         # LOG.debug("Getting container status for container: %s", container_name) #  too verbose
         try:
             container = self.client().containers.get(container_name)
             if container.status == "running":
                 return DockerContainerStatus.UP
             elif container.status == "paused":
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/coverage_docs.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/coverage_docs.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/crypto.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/crypto.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/diagnose.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/diagnose.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/docker_utils.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/docker_utils.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/files.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/files.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/functions.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/functions.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/http.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/http.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/json.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/json.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/kinesis/kclipy_helper.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/kinesis/kclipy_helper.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/kinesis/kinesis_connector.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/kinesis/kinesis_connector.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/kinesis/kinesis_util.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/kinesis/kinesis_util.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/net.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/net.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/no_exit_argument_parser.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/no_exit_argument_parser.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/numbers.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/numbers.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/objects.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/objects.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/patch.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/patch.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/platform.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/platform.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/run.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/run.py`

 * *Files 0% similar despite different names*

```diff
@@ -149,15 +149,15 @@
         if time.time() - start >= max_secs:
             return
         time.sleep(0.5)
 
 
 def is_command_available(cmd: str) -> bool:
     try:
-        run("which %s" % cmd, print_error=False)
+        run(["which", cmd], print_error=False)
         return True
     except Exception:
         return False
 
 
 def kill_process_tree(parent_pid):
     # Note: Do NOT import "psutil" at the root scope
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/scheduler.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/scheduler.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/server/http2_server.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/server/http2_server.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/server/proxy_server.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/server/proxy_server.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/serving.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/serving.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/ssl.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/ssl.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/strings.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/strings.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/sync.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/sync.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/tagging.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/tagging.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/tail.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/tail.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/testutil.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/testutil.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/threads.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/threads.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/time.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/time.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/urls.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/urls.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/venv.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/venv.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack/utils/xml.py` & `localstack-core-2.1.1.dev20230628135412/localstack/utils/xml.py`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/PKG-INFO` & `localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: localstack-core
-Version: 2.1.1.dev20230628134939
+Version: 2.1.1.dev20230628135412
 Summary: The core library and runtime of LocalStack
 Home-page: https://github.com/localstack/localstack
 Author: LocalStack Contributors
 Author-email: info@localstack.cloud
 License: Apache License 2.0
 Classifier: Programming Language :: Python :: 3.10
 Classifier: License :: OSI Approved :: Apache Software License
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/SOURCES.txt` & `localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/entry_points.txt` & `localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/entry_points.txt`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/plux.json` & `localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/plux.json`

 * *Files 1% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.8146198830409357%*

 * *Differences: {"'localstack.cloudformation.resource_providers'": '{insert: [(1, '*

 * *                                                   "'AWS::SSM::Parameter=localstack.services.ssm.resource_providers.aws_ssm_parameter:SSMParameterProviderPlugin')], "*

 * *                                                   'delete: [0]}',*

 * * "'localstack.hooks.on_infra_ready'": '{insert: [(1, '*

 * *                                      "'register_virtual_host_routes=localstack.services.s3.virtual_host:register_virtual_host_routes')], "*

 * *                […]*

```diff
@@ -42,51 +42,51 @@
         "stepfunctions:v2=localstack.services.providers:stepfunctions_v2",
         "sts:default=localstack.services.providers:sts",
         "support:default=localstack.services.providers:support",
         "swf:default=localstack.services.providers:swf",
         "transcribe:default=localstack.services.providers:transcribe"
     ],
     "localstack.cloudformation.resource_providers": [
-        "AWS::SSM::Parameter=localstack.services.ssm.resource_providers.aws_ssm_parameter:SSMParameterProviderPlugin",
-        "AWS::OpenSearchService::Domain=localstack.services.opensearch.resource_providers.aws_opensearchservice_domain:OpenSearchDomainProviderPlugin"
+        "AWS::OpenSearchService::Domain=localstack.services.opensearch.resource_providers.aws_opensearchservice_domain:OpenSearchDomainProviderPlugin",
+        "AWS::SSM::Parameter=localstack.services.ssm.resource_providers.aws_ssm_parameter:SSMParameterProviderPlugin"
     ],
     "localstack.hooks.configure_localstack_container": [
         "configure_edge_port=localstack.plugins:configure_edge_port"
     ],
     "localstack.hooks.on_infra_ready": [
-        "register_virtual_host_routes=localstack.services.s3.virtual_host:register_virtual_host_routes",
-        "_run_init_scripts_on_ready=localstack.runtime.init:_run_init_scripts_on_ready"
+        "_run_init_scripts_on_ready=localstack.runtime.init:_run_init_scripts_on_ready",
+        "register_virtual_host_routes=localstack.services.s3.virtual_host:register_virtual_host_routes"
     ],
     "localstack.hooks.on_infra_shutdown": [
-        "run_shutdown_handlers=localstack.runtime.shutdown:run_shutdown_handlers",
-        "_run_init_scripts_on_shutdown=localstack.runtime.init:_run_init_scripts_on_shutdown"
+        "_run_init_scripts_on_shutdown=localstack.runtime.init:_run_init_scripts_on_shutdown",
+        "run_shutdown_handlers=localstack.runtime.shutdown:run_shutdown_handlers"
     ],
     "localstack.hooks.on_infra_start": [
-        "deprecation_warnings=localstack.plugins:deprecation_warnings",
-        "register_partition_adjusting_proxy_listener=localstack.plugins:register_partition_adjusting_proxy_listener",
+        "_run_init_scripts_on_start=localstack.runtime.init:_run_init_scripts_on_start",
         "_publish_config_as_analytics_event=localstack.runtime.analytics:_publish_config_as_analytics_event",
         "_publish_container_info=localstack.runtime.analytics:_publish_container_info",
-        "_run_init_scripts_on_start=localstack.runtime.init:_run_init_scripts_on_start",
         "_patch_botocore_json_parser=localstack.aws.client:_patch_botocore_json_parser",
+        "deprecation_warnings=localstack.plugins:deprecation_warnings",
+        "register_partition_adjusting_proxy_listener=localstack.plugins:register_partition_adjusting_proxy_listener",
         "validate_configuration=localstack.services.awslambda.plugins:validate_configuration"
     ],
     "localstack.hooks.prepare_host": [
         "prepare_host_machine_id=localstack.utils.analytics.metadata:prepare_host_machine_id"
     ],
     "localstack.lambda.runtime_executor": [
         "docker=localstack.services.awslambda.invocation.plugins:DockerRuntimeExecutorPlugin"
     ],
     "localstack.packages": [
-        "stepfunctions-local/community=localstack.services.stepfunctions.plugins:stepfunctions_local_packages",
-        "cloudformation-libs/community=localstack.services.cloudformation.plugins:cloudformation_package",
+        "ffmpeg/community=localstack.packages.plugins:ffmpeg_package",
+        "terraform/community=localstack.packages.plugins:terraform_package",
         "kinesis-mock/community=localstack.services.kinesis.plugins:kinesismock_package",
-        "opensearch/community=localstack.services.opensearch.plugins:opensearch_package",
+        "cloudformation-libs/community=localstack.services.cloudformation.plugins:cloudformation_package",
+        "stepfunctions-local/community=localstack.services.stepfunctions.plugins:stepfunctions_local_packages",
         "local-kms/community=localstack.services.kms.plugins:local_kms_package",
+        "elasticsearch/community=localstack.services.es.plugins:elasticsearch_package",
+        "opensearch/community=localstack.services.opensearch.plugins:opensearch_package",
+        "dynamodb-local/community=localstack.services.dynamodb.plugins:dynamodb_local_package",
         "awslambda-go-runtime/community=localstack.services.awslambda.plugins:awslambda_go_runtime_package",
         "awslambda-runtime/community=localstack.services.awslambda.plugins:awslambda_runtime_package",
-        "lambda-java-libs/community=localstack.services.awslambda.plugins:lambda_java_libs",
-        "elasticsearch/community=localstack.services.es.plugins:elasticsearch_package",
-        "ffmpeg/community=localstack.packages.plugins:ffmpeg_package",
-        "terraform/community=localstack.packages.plugins:terraform_package",
-        "dynamodb-local/community=localstack.services.dynamodb.plugins:dynamodb_local_package"
+        "lambda-java-libs/community=localstack.services.awslambda.plugins:lambda_java_libs"
     ]
 }
```

### Comparing `localstack-core-2.1.1.dev20230628134939/localstack_core.egg-info/requires.txt` & `localstack-core-2.1.1.dev20230628135412/localstack_core.egg-info/requires.txt`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/pyproject.toml` & `localstack-core-2.1.1.dev20230628135412/pyproject.toml`

 * *Files identical despite different names*

### Comparing `localstack-core-2.1.1.dev20230628134939/setup.cfg` & `localstack-core-2.1.1.dev20230628135412/setup.cfg`

 * *Files identical despite different names*

