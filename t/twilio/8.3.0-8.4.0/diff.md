# Comparing `tmp/twilio-8.3.0.tar.gz` & `tmp/twilio-8.4.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "twilio-8.3.0.tar", last modified: Thu Jun 15 07:43:44 2023, max compression
+gzip compressed data, was "twilio-8.4.0.tar", last modified: Wed Jun 28 11:34:08 2023, max compression
```

## Comparing `twilio-8.3.0.tar` & `twilio-8.4.0.tar`

### file list

```diff
@@ -1,855 +1,861 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.189010 twilio-8.3.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1387 2023-06-15 07:43:30.000000 twilio-8.3.0/AUTHORS.md
--rw-r--r--   0 runner    (1001) docker     (123)     1088 2023-06-15 07:43:30.000000 twilio-8.3.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)      117 2023-06-15 07:43:30.000000 twilio-8.3.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)    11938 2023-06-15 07:43:44.189010 twilio-8.3.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    10921 2023-06-15 07:43:30.000000 twilio-8.3.0/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      236 2023-06-15 07:43:44.189010 twilio-8.3.0/setup.cfg
--rwxr-xr-x   0 runner    (1001) docker     (123)     1694 2023-06-15 07:43:30.000000 twilio-8.3.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.016999 twilio-8.3.0/twilio/
--rw-r--r--   0 runner    (1001) docker     (123)       76 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.020999 twilio-8.3.0/twilio/base/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8153 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/client_base.py
--rw-r--r--   0 runner    (1001) docker     (123)     2019 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/deserialize.py
--rw-r--r--   0 runner    (1001) docker     (123)     2978 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/domain.py
--rw-r--r--   0 runner    (1001) docker     (123)     2890 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/exceptions.py
--rw-r--r--   0 runner    (1001) docker     (123)      147 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/instance_context.py
--rw-r--r--   0 runner    (1001) docker     (123)      148 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/instance_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)      144 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/list_resource.py
--rw-r--r--   0 runner    (1001) docker     (123)     1417 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/obsolete.py
--rw-r--r--   0 runner    (1001) docker     (123)     5181 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/page.py
--rw-r--r--   0 runner    (1001) docker     (123)     2039 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/serialize.py
--rw-r--r--   0 runner    (1001) docker     (123)      280 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/values.py
--rw-r--r--   0 runner    (1001) docker     (123)    14614 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/base/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.024999 twilio-8.3.0/twilio/http/
--rw-r--r--   0 runner    (1001) docker     (123)     3434 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/http/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4503 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/http/async_http_client.py
--rw-r--r--   0 runner    (1001) docker     (123)     3735 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/http/http_client.py
--rw-r--r--   0 runner    (1001) docker     (123)     2655 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/http/request.py
--rw-r--r--   0 runner    (1001) docker     (123)      518 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/http/response.py
--rw-r--r--   0 runner    (1001) docker     (123)     4810 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/http/validation_client.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.024999 twilio-8.3.0/twilio/jwt/
--rw-r--r--   0 runner    (1001) docker     (123)     5085 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/jwt/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.024999 twilio-8.3.0/twilio/jwt/access_token/
--rw-r--r--   0 runner    (1001) docker     (123)     2415 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/jwt/access_token/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4902 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/jwt/access_token/grants.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.024999 twilio-8.3.0/twilio/jwt/client/
--rw-r--r--   0 runner    (1001) docker     (123)     3982 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/jwt/client/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.024999 twilio-8.3.0/twilio/jwt/taskrouter/
--rw-r--r--   0 runner    (1001) docker     (123)     5726 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/jwt/taskrouter/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4309 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/jwt/taskrouter/capabilities.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.024999 twilio-8.3.0/twilio/jwt/validation/
--rw-r--r--   0 runner    (1001) docker     (123)     3156 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/jwt/validation/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4100 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/request_validator.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.024999 twilio-8.3.0/twilio/rest/
--rw-r--r--   0 runner    (1001) docker     (123)    21358 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.024999 twilio-8.3.0/twilio/rest/accounts/
--rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/accounts/AccountsBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     1168 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/accounts/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.028999 twilio-8.3.0/twilio/rest/accounts/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     2102 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/accounts/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5547 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/accounts/v1/auth_token_promotion.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.028999 twilio-8.3.0/twilio/rest/accounts/v1/credential/
--rw-r--r--   0 runner    (1001) docker     (123)     1766 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/accounts/v1/credential/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19489 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/accounts/v1/credential/aws.py
--rw-r--r--   0 runner    (1001) docker     (123)    20007 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/accounts/v1/credential/public_key.py
--rw-r--r--   0 runner    (1001) docker     (123)     6551 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/accounts/v1/secondary_auth_token.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.028999 twilio-8.3.0/twilio/rest/api/
--rw-r--r--   0 runner    (1001) docker     (123)     1208 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/ApiBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     8255 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.028999 twilio-8.3.0/twilio/rest/api/v2010/
--rw-r--r--   0 runner    (1001) docker     (123)     1805 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.033000 twilio-8.3.0/twilio/rest/api/v2010/account/
--rw-r--r--   0 runner    (1001) docker     (123)    36206 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.033000 twilio-8.3.0/twilio/rest/api/v2010/account/address/
--rw-r--r--   0 runner    (1001) docker     (123)    35858 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/address/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17044 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/address/dependent_phone_number.py
--rw-r--r--   0 runner    (1001) docker     (123)    47553 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/application.py
--rw-r--r--   0 runner    (1001) docker     (123)    17274 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/authorized_connect_app.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.037000 twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/
--rw-r--r--   0 runner    (1001) docker     (123)    21427 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    46239 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/local.py
--rw-r--r--   0 runner    (1001) docker     (123)    46210 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/machine_to_machine.py
--rw-r--r--   0 runner    (1001) docker     (123)    45860 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/mobile.py
--rw-r--r--   0 runner    (1001) docker     (123)    45930 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/national.py
--rw-r--r--   0 runner    (1001) docker     (123)    46000 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/shared_cost.py
--rw-r--r--   0 runner    (1001) docker     (123)    45930 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/toll_free.py
--rw-r--r--   0 runner    (1001) docker     (123)    45790 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/voip.py
--rw-r--r--   0 runner    (1001) docker     (123)     3186 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/balance.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.041000 twilio-8.3.0/twilio/rest/api/v2010/account/call/
--rw-r--r--   0 runner    (1001) docker     (123)    92392 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/call/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10658 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/call/event.py
--rw-r--r--   0 runner    (1001) docker     (123)    11932 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/call/feedback.py
--rw-r--r--   0 runner    (1001) docker     (123)    13986 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/call/feedback_summary.py
--rw-r--r--   0 runner    (1001) docker     (123)    28363 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/call/notification.py
--rw-r--r--   0 runner    (1001) docker     (123)    23472 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/call/payment.py
--rw-r--r--   0 runner    (1001) docker     (123)    38495 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/call/recording.py
--rw-r--r--   0 runner    (1001) docker     (123)    77226 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/call/siprec.py
--rw-r--r--   0 runner    (1001) docker     (123)    77116 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/call/stream.py
--rw-r--r--   0 runner    (1001) docker     (123)     5278 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/call/user_defined_message.py
--rw-r--r--   0 runner    (1001) docker     (123)    10898 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/call/user_defined_message_subscription.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.041000 twilio-8.3.0/twilio/rest/api/v2010/account/conference/
--rw-r--r--   0 runner    (1001) docker     (123)    41186 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/conference/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    75225 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/conference/participant.py
--rw-r--r--   0 runner    (1001) docker     (123)    32729 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/conference/recording.py
--rw-r--r--   0 runner    (1001) docker     (123)    26539 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/connect_app.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.041000 twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/
--rw-r--r--   0 runner    (1001) docker     (123)    73374 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.041000 twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/assigned_add_on/
--rw-r--r--   0 runner    (1001) docker     (123)    20750 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/assigned_add_on/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18341 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/assigned_add_on/assigned_add_on_extension.py
--rw-r--r--   0 runner    (1001) docker     (123)    36935 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/local.py
--rw-r--r--   0 runner    (1001) docker     (123)    37019 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/mobile.py
--rw-r--r--   0 runner    (1001) docker     (123)    37103 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/toll_free.py
--rw-r--r--   0 runner    (1001) docker     (123)    17989 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/key.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.041000 twilio-8.3.0/twilio/rest/api/v2010/account/message/
--rw-r--r--   0 runner    (1001) docker     (123)    53984 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/message/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5102 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/message/feedback.py
--rw-r--r--   0 runner    (1001) docker     (123)    27246 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/message/media.py
--rw-r--r--   0 runner    (1001) docker     (123)     4785 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/new_key.py
--rw-r--r--   0 runner    (1001) docker     (123)     4813 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/new_signing_key.py
--rw-r--r--   0 runner    (1001) docker     (123)    27505 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/notification.py
--rw-r--r--   0 runner    (1001) docker     (123)    22199 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/outgoing_caller_id.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.045000 twilio-8.3.0/twilio/rest/api/v2010/account/queue/
--rw-r--r--   0 runner    (1001) docker     (123)    22428 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/queue/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19131 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/queue/member.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.045000 twilio-8.3.0/twilio/rest/api/v2010/account/recording/
--rw-r--r--   0 runner    (1001) docker     (123)    37769 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/recording/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.045000 twilio-8.3.0/twilio/rest/api/v2010/account/recording/add_on_result/
--rw-r--r--   0 runner    (1001) docker     (123)    19239 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/recording/add_on_result/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19233 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/recording/add_on_result/payload.py
--rw-r--r--   0 runner    (1001) docker     (123)    19008 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/recording/transcription.py
--rw-r--r--   0 runner    (1001) docker     (123)    26406 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/short_code.py
--rw-r--r--   0 runner    (1001) docker     (123)    17376 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/signing_key.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.045000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/
--rw-r--r--   0 runner    (1001) docker     (123)     2871 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.045000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/credential_list/
--rw-r--r--   0 runner    (1001) docker     (123)    21278 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/credential_list/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22757 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/credential_list/credential.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.045000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/
--rw-r--r--   0 runner    (1001) docker     (123)    45116 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.045000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/
--rw-r--r--   0 runner    (1001) docker     (123)     2758 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.049001 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/
--rw-r--r--   0 runner    (1001) docker     (123)     3330 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20440 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/auth_calls_credential_list_mapping.py
--rw-r--r--   0 runner    (1001) docker     (123)    20981 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/auth_calls_ip_access_control_list_mapping.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.049001 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_registrations/
--rw-r--r--   0 runner    (1001) docker     (123)     2473 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_registrations/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21048 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_registrations/auth_registrations_credential_list_mapping.py
--rw-r--r--   0 runner    (1001) docker     (123)    19893 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/credential_list_mapping.py
--rw-r--r--   0 runner    (1001) docker     (123)    20164 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/ip_access_control_list_mapping.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.049001 twilio-8.3.0/twilio/rest/api/v2010/account/sip/ip_access_control_list/
--rw-r--r--   0 runner    (1001) docker     (123)    21808 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/ip_access_control_list/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    26238 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/sip/ip_access_control_list/ip_address.py
--rw-r--r--   0 runner    (1001) docker     (123)     4823 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/token.py
--rw-r--r--   0 runner    (1001) docker     (123)    18034 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/transcription.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.049001 twilio-8.3.0/twilio/rest/api/v2010/account/usage/
--rw-r--r--   0 runner    (1001) docker     (123)     2220 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/usage/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.053001 twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/
--rw-r--r--   0 runner    (1001) docker     (123)    41695 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    38339 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/all_time.py
--rw-r--r--   0 runner    (1001) docker     (123)    38247 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/daily.py
--rw-r--r--   0 runner    (1001) docker     (123)    38431 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/last_month.py
--rw-r--r--   0 runner    (1001) docker     (123)    38339 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/monthly.py
--rw-r--r--   0 runner    (1001) docker     (123)    38431 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/this_month.py
--rw-r--r--   0 runner    (1001) docker     (123)    38247 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/today.py
--rw-r--r--   0 runner    (1001) docker     (123)    38293 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/yearly.py
--rw-r--r--   0 runner    (1001) docker     (123)    38431 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/yesterday.py
--rw-r--r--   0 runner    (1001) docker     (123)    49245 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/usage/trigger.py
--rw-r--r--   0 runner    (1001) docker     (123)     7397 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/api/v2010/account/validation_request.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.053001 twilio-8.3.0/twilio/rest/autopilot/
--rw-r--r--   0 runner    (1001) docker     (123)     1217 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/AutopilotBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      778 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.053001 twilio-8.3.0/twilio/rest/autopilot/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1680 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.053001 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/
--rw-r--r--   0 runner    (1001) docker     (123)    35087 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8479 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/defaults.py
--rw-r--r--   0 runner    (1001) docker     (123)     6698 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/dialogue.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.057001 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/field_type/
--rw-r--r--   0 runner    (1001) docker     (123)    23752 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/field_type/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22246 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/field_type/field_value.py
--rw-r--r--   0 runner    (1001) docker     (123)    22851 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/model_build.py
--rw-r--r--   0 runner    (1001) docker     (123)    29877 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/query.py
--rw-r--r--   0 runner    (1001) docker     (123)     8288 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/style_sheet.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.057001 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/task/
--rw-r--r--   0 runner    (1001) docker     (123)    28213 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/task/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20115 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/task/field.py
--rw-r--r--   0 runner    (1001) docker     (123)    27891 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/task/sample.py
--rw-r--r--   0 runner    (1001) docker     (123)     9964 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/task/task_actions.py
--rw-r--r--   0 runner    (1001) docker     (123)     7530 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/task/task_statistics.py
--rw-r--r--   0 runner    (1001) docker     (123)    24728 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/assistant/webhook.py
--rw-r--r--   0 runner    (1001) docker     (123)     5222 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/autopilot/v1/restore_assistant.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.057001 twilio-8.3.0/twilio/rest/bulkexports/
--rw-r--r--   0 runner    (1001) docker     (123)     1231 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/bulkexports/BulkexportsBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      792 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/bulkexports/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.057001 twilio-8.3.0/twilio/rest/bulkexports/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1692 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/bulkexports/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.057001 twilio-8.3.0/twilio/rest/bulkexports/v1/export/
--rw-r--r--   0 runner    (1001) docker     (123)     7083 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/bulkexports/v1/export/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14521 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/bulkexports/v1/export/day.py
--rw-r--r--   0 runner    (1001) docker     (123)    17005 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/bulkexports/v1/export/export_custom_job.py
--rw-r--r--   0 runner    (1001) docker     (123)     8224 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/bulkexports/v1/export/job.py
--rw-r--r--   0 runner    (1001) docker     (123)    10811 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/bulkexports/v1/export_configuration.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.061001 twilio-8.3.0/twilio/rest/chat/
--rw-r--r--   0 runner    (1001) docker     (123)     1700 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/ChatBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      970 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.061001 twilio-8.3.0/twilio/rest/chat/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1569 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27856 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v1/credential.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.061001 twilio-8.3.0/twilio/rest/chat/v1/service/
--rw-r--r--   0 runner    (1001) docker     (123)    92674 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v1/service/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.061001 twilio-8.3.0/twilio/rest/chat/v1/service/channel/
--rw-r--r--   0 runner    (1001) docker     (123)    28967 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v1/service/channel/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22312 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v1/service/channel/invite.py
--rw-r--r--   0 runner    (1001) docker     (123)    27709 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v1/service/channel/member.py
--rw-r--r--   0 runner    (1001) docker     (123)    26356 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v1/service/channel/message.py
--rw-r--r--   0 runner    (1001) docker     (123)    21831 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v1/service/role.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.061001 twilio-8.3.0/twilio/rest/chat/v1/service/user/
--rw-r--r--   0 runner    (1001) docker     (123)    26317 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v1/service/user/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12925 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v1/service/user/user_channel.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.061001 twilio-8.3.0/twilio/rest/chat/v2/
--rw-r--r--   0 runner    (1001) docker     (123)     1569 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27486 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/credential.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.065002 twilio-8.3.0/twilio/rest/chat/v2/service/
--rw-r--r--   0 runner    (1001) docker     (123)    66570 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/service/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22118 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/service/binding.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.065002 twilio-8.3.0/twilio/rest/chat/v2/service/channel/
--rw-r--r--   0 runner    (1001) docker     (123)    39123 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/service/channel/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22292 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/service/channel/invite.py
--rw-r--r--   0 runner    (1001) docker     (123)    41109 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/service/channel/member.py
--rw-r--r--   0 runner    (1001) docker     (123)    37545 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/service/channel/message.py
--rw-r--r--   0 runner    (1001) docker     (123)    33770 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/service/channel/webhook.py
--rw-r--r--   0 runner    (1001) docker     (123)    22232 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/service/role.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.065002 twilio-8.3.0/twilio/rest/chat/v2/service/user/
--rw-r--r--   0 runner    (1001) docker     (123)    29035 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/service/user/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21909 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/service/user/user_binding.py
--rw-r--r--   0 runner    (1001) docker     (123)    27050 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v2/service/user/user_channel.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.065002 twilio-8.3.0/twilio/rest/chat/v3/
--rw-r--r--   0 runner    (1001) docker     (123)     1268 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v3/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11567 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/chat/v3/channel.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.069002 twilio-8.3.0/twilio/rest/content/
--rw-r--r--   0 runner    (1001) docker     (123)     1203 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/content/ContentBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     1110 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/content/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.069002 twilio-8.3.0/twilio/rest/content/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     2024 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/content/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.069002 twilio-8.3.0/twilio/rest/content/v1/content/
--rw-r--r--   0 runner    (1001) docker     (123)    16628 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/content/v1/content/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5839 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/content/v1/content/approval_fetch.py
--rw-r--r--   0 runner    (1001) docker     (123)    11924 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/content/v1/content_and_approvals.py
--rw-r--r--   0 runner    (1001) docker     (123)    12123 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/content/v1/legacy_content.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.069002 twilio-8.3.0/twilio/rest/conversations/
--rw-r--r--   0 runner    (1001) docker     (123)     1245 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/ConversationsBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     2760 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.069002 twilio-8.3.0/twilio/rest/conversations/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     3659 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    37619 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/address_configuration.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.073002 twilio-8.3.0/twilio/rest/conversations/v1/configuration/
--rw-r--r--   0 runner    (1001) docker     (123)    12497 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/configuration/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11083 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/configuration/webhook.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.073002 twilio-8.3.0/twilio/rest/conversations/v1/conversation/
--rw-r--r--   0 runner    (1001) docker     (123)    42957 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/conversation/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.073002 twilio-8.3.0/twilio/rest/conversations/v1/conversation/message/
--rw-r--r--   0 runner    (1001) docker     (123)    34972 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/conversation/message/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18063 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/conversation/message/delivery_receipt.py
--rw-r--r--   0 runner    (1001) docker     (123)    40116 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/conversation/participant.py
--rw-r--r--   0 runner    (1001) docker     (123)    27236 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/conversation/webhook.py
--rw-r--r--   0 runner    (1001) docker     (123)    27935 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/credential.py
--rw-r--r--   0 runner    (1001) docker     (123)    18739 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/participant_conversation.py
--rw-r--r--   0 runner    (1001) docker     (123)    20943 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/role.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.073002 twilio-8.3.0/twilio/rest/conversations/v1/service/
--rw-r--r--   0 runner    (1001) docker     (123)    20025 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22289 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/binding.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.073002 twilio-8.3.0/twilio/rest/conversations/v1/service/configuration/
--rw-r--r--   0 runner    (1001) docker     (123)    16088 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/configuration/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24410 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/configuration/notification.py
--rw-r--r--   0 runner    (1001) docker     (123)    13881 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/configuration/webhook.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.077003 twilio-8.3.0/twilio/rest/conversations/v1/service/conversation/
--rw-r--r--   0 runner    (1001) docker     (123)    44808 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/conversation/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.077003 twilio-8.3.0/twilio/rest/conversations/v1/service/conversation/message/
--rw-r--r--   0 runner    (1001) docker     (123)    36629 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/conversation/message/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19398 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/conversation/message/delivery_receipt.py
--rw-r--r--   0 runner    (1001) docker     (123)    41799 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/conversation/participant.py
--rw-r--r--   0 runner    (1001) docker     (123)    28926 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/conversation/webhook.py
--rw-r--r--   0 runner    (1001) docker     (123)    19530 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/participant_conversation.py
--rw-r--r--   0 runner    (1001) docker     (123)    22534 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/role.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.077003 twilio-8.3.0/twilio/rest/conversations/v1/service/user/
--rw-r--r--   0 runner    (1001) docker     (123)    29682 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/user/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    26510 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/service/user/user_conversation.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.077003 twilio-8.3.0/twilio/rest/conversations/v1/user/
--rw-r--r--   0 runner    (1001) docker     (123)    28016 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/user/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25215 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/conversations/v1/user/user_conversation.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.077003 twilio-8.3.0/twilio/rest/events/
--rw-r--r--   0 runner    (1001) docker     (123)     1196 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/events/EventsBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     1277 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/events/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.077003 twilio-8.3.0/twilio/rest/events/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     2133 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/events/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15317 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/events/v1/event_type.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.077003 twilio-8.3.0/twilio/rest/events/v1/schema/
--rw-r--r--   0 runner    (1001) docker     (123)     6417 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/events/v1/schema/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14920 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/events/v1/schema/schema_version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.081003 twilio-8.3.0/twilio/rest/events/v1/sink/
--rw-r--r--   0 runner    (1001) docker     (123)    22872 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/events/v1/sink/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2768 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/events/v1/sink/sink_test.py
--rw-r--r--   0 runner    (1001) docker     (123)     3358 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/events/v1/sink/sink_validate.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.081003 twilio-8.3.0/twilio/rest/events/v1/subscription/
--rw-r--r--   0 runner    (1001) docker     (123)    22609 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/events/v1/subscription/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20282 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/events/v1/subscription/subscribed_event.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.081003 twilio-8.3.0/twilio/rest/flex_api/
--rw-r--r--   0 runner    (1001) docker     (123)     1471 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/FlexApiBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     6332 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.085003 twilio-8.3.0/twilio/rest/flex_api/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     7374 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23439 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/assessments.py
--rw-r--r--   0 runner    (1001) docker     (123)    19793 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/channel.py
--rw-r--r--   0 runner    (1001) docker     (123)    13488 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/configuration.py
--rw-r--r--   0 runner    (1001) docker     (123)    46860 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/flex_flow.py
--rw-r--r--   0 runner    (1001) docker     (123)    17361 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/insights_assessments_comment.py
--rw-r--r--   0 runner    (1001) docker     (123)    12870 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/insights_conversations.py
--rw-r--r--   0 runner    (1001) docker     (123)    27954 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/insights_questionnaires.py
--rw-r--r--   0 runner    (1001) docker     (123)    21091 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/insights_questionnaires_category.py
--rw-r--r--   0 runner    (1001) docker     (123)    26772 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/insights_questionnaires_question.py
--rw-r--r--   0 runner    (1001) docker     (123)    15944 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/insights_segments.py
--rw-r--r--   0 runner    (1001) docker     (123)     5688 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/insights_session.py
--rw-r--r--   0 runner    (1001) docker     (123)     3164 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/insights_settings_answer_sets.py
--rw-r--r--   0 runner    (1001) docker     (123)     2745 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/insights_settings_comment.py
--rw-r--r--   0 runner    (1001) docker     (123)     5365 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/insights_user_roles.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.085003 twilio-8.3.0/twilio/rest/flex_api/v1/interaction/
--rw-r--r--   0 runner    (1001) docker     (123)     8562 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/interaction/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.085003 twilio-8.3.0/twilio/rest/flex_api/v1/interaction/interaction_channel/
--rw-r--r--   0 runner    (1001) docker     (123)    20915 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/interaction/interaction_channel/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13861 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/interaction/interaction_channel/interaction_channel_invite.py
--rw-r--r--   0 runner    (1001) docker     (123)    19858 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/interaction/interaction_channel/interaction_channel_participant.py
--rw-r--r--   0 runner    (1001) docker     (123)    20821 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v1/web_channel.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.085003 twilio-8.3.0/twilio/rest/flex_api/v2/
--rw-r--r--   0 runner    (1001) docker     (123)     1323 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5583 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/flex_api/v2/web_channels.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.089003 twilio-8.3.0/twilio/rest/frontline_api/
--rw-r--r--   0 runner    (1001) docker     (123)     1240 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/frontline_api/FrontlineApiBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/frontline_api/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.089003 twilio-8.3.0/twilio/rest/frontline_api/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1277 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/frontline_api/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10822 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/frontline_api/v1/user.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.089003 twilio-8.3.0/twilio/rest/insights/
--rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/InsightsBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     1579 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.089003 twilio-8.3.0/twilio/rest/insights/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     2419 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.089003 twilio-8.3.0/twilio/rest/insights/v1/call/
--rw-r--r--   0 runner    (1001) docker     (123)     6981 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/v1/call/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17445 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/v1/call/annotation.py
--rw-r--r--   0 runner    (1001) docker     (123)     9363 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/v1/call/call_summary.py
--rw-r--r--   0 runner    (1001) docker     (123)    12166 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/v1/call/event.py
--rw-r--r--   0 runner    (1001) docker     (123)    13146 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/v1/call/metric.py
--rw-r--r--   0 runner    (1001) docker     (123)    32001 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/v1/call_summaries.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.089003 twilio-8.3.0/twilio/rest/insights/v1/conference/
--rw-r--r--   0 runner    (1001) docker     (123)    31370 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/v1/conference/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25248 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/v1/conference/conference_participant.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.093004 twilio-8.3.0/twilio/rest/insights/v1/room/
--rw-r--r--   0 runner    (1001) docker     (123)    25243 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/v1/room/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17908 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/v1/room/participant.py
--rw-r--r--   0 runner    (1001) docker     (123)     8063 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/insights/v1/setting.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.093004 twilio-8.3.0/twilio/rest/ip_messaging/
--rw-r--r--   0 runner    (1001) docker     (123)     1507 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/IpMessagingBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      738 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.093004 twilio-8.3.0/twilio/rest/ip_messaging/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1615 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21632 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v1/credential.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.093004 twilio-8.3.0/twilio/rest/ip_messaging/v1/service/
--rw-r--r--   0 runner    (1001) docker     (123)    62960 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v1/service/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.093004 twilio-8.3.0/twilio/rest/ip_messaging/v1/service/channel/
--rw-r--r--   0 runner    (1001) docker     (123)    24064 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v1/service/channel/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18541 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v1/service/channel/invite.py
--rw-r--r--   0 runner    (1001) docker     (123)    21725 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v1/service/channel/member.py
--rw-r--r--   0 runner    (1001) docker     (123)    21818 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v1/service/channel/message.py
--rw-r--r--   0 runner    (1001) docker     (123)    18855 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v1/service/role.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.093004 twilio-8.3.0/twilio/rest/ip_messaging/v1/service/user/
--rw-r--r--   0 runner    (1001) docker     (123)    21365 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v1/service/user/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11548 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v1/service/user/user_channel.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.097004 twilio-8.3.0/twilio/rest/ip_messaging/v2/
--rw-r--r--   0 runner    (1001) docker     (123)     1615 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21632 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/credential.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.097004 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/
--rw-r--r--   0 runner    (1001) docker     (123)    45390 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17907 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/binding.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.097004 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/channel/
--rw-r--r--   0 runner    (1001) docker     (123)    30568 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/channel/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18541 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/channel/invite.py
--rw-r--r--   0 runner    (1001) docker     (123)    29520 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/channel/member.py
--rw-r--r--   0 runner    (1001) docker     (123)    28798 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/channel/message.py
--rw-r--r--   0 runner    (1001) docker     (123)    26175 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/channel/webhook.py
--rw-r--r--   0 runner    (1001) docker     (123)    18855 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/role.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.097004 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/user/
--rw-r--r--   0 runner    (1001) docker     (123)    24051 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/user/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18192 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/user/user_binding.py
--rw-r--r--   0 runner    (1001) docker     (123)    21476 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/ip_messaging/v2/service/user/user_channel.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.097004 twilio-8.3.0/twilio/rest/lookups/
--rw-r--r--   0 runner    (1001) docker     (123)     1468 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/lookups/LookupsBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      432 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/lookups/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.101004 twilio-8.3.0/twilio/rest/lookups/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1329 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/lookups/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13250 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/lookups/v1/phone_number.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.101004 twilio-8.3.0/twilio/rest/lookups/v2/
--rw-r--r--   0 runner    (1001) docker     (123)     1329 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/lookups/v2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20961 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/lookups/v2/phone_number.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.101004 twilio-8.3.0/twilio/rest/media/
--rw-r--r--   0 runner    (1001) docker     (123)     1189 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/media/MediaBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     1107 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/media/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.101004 twilio-8.3.0/twilio/rest/media/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     2030 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/media/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    26533 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/media/v1/media_processor.py
--rw-r--r--   0 runner    (1001) docker     (123)    22582 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/media/v1/media_recording.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.101004 twilio-8.3.0/twilio/rest/media/v1/player_streamer/
--rw-r--r--   0 runner    (1001) docker     (123)    25414 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/media/v1/player_streamer/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9432 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/media/v1/player_streamer/playback_grant.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.101004 twilio-8.3.0/twilio/rest/messaging/
--rw-r--r--   0 runner    (1001) docker     (123)     1217 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/MessagingBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     3308 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.105004 twilio-8.3.0/twilio/rest/messaging/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     5200 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.105004 twilio-8.3.0/twilio/rest/messaging/v1/brand_registration/
--rw-r--r--   0 runner    (1001) docker     (123)    24289 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/brand_registration/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3583 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/brand_registration/brand_registration_otp.py
--rw-r--r--   0 runner    (1001) docker     (123)    19914 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/brand_registration/brand_vetting.py
--rw-r--r--   0 runner    (1001) docker     (123)     5796 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/deactivations.py
--rw-r--r--   0 runner    (1001) docker     (123)    10495 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/domain_certs.py
--rw-r--r--   0 runner    (1001) docker     (123)    13875 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/domain_config.py
--rw-r--r--   0 runner    (1001) docker     (123)     7990 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/domain_config_messaging_service.py
--rw-r--r--   0 runner    (1001) docker     (123)     4360 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/external_campaign.py
--rw-r--r--   0 runner    (1001) docker     (123)     9216 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/linkshortening_messaging_service.py
--rw-r--r--   0 runner    (1001) docker     (123)     7383 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/linkshortening_messaging_service_domain_association.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.105004 twilio-8.3.0/twilio/rest/messaging/v1/service/
--rw-r--r--   0 runner    (1001) docker     (123)    54653 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/service/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18348 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/service/alpha_sender.py
--rw-r--r--   0 runner    (1001) docker     (123)    18413 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/service/phone_number.py
--rw-r--r--   0 runner    (1001) docker     (123)    18135 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/service/short_code.py
--rw-r--r--   0 runner    (1001) docker     (123)    33638 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/service/us_app_to_person.py
--rw-r--r--   0 runner    (1001) docker     (123)     3513 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/service/us_app_to_person_usecase.py
--rw-r--r--   0 runner    (1001) docker     (123)     2322 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/messaging/v1/usecase.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.105004 twilio-8.3.0/twilio/rest/microvisor/
--rw-r--r--   0 runner    (1001) docker     (123)     1224 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/microvisor/MicrovisorBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     1321 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/microvisor/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.109005 twilio-8.3.0/twilio/rest/microvisor/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     2211 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/microvisor/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    17838 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/microvisor/v1/account_config.py
--rw-r--r--   0 runner    (1001) docker     (123)    17723 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/microvisor/v1/account_secret.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.109005 twilio-8.3.0/twilio/rest/microvisor/v1/app/
--rw-r--r--   0 runner    (1001) docker     (123)    15664 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/microvisor/v1/app/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5534 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/microvisor/v1/app/app_manifest.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.109005 twilio-8.3.0/twilio/rest/microvisor/v1/device/
--rw-r--r--   0 runner    (1001) docker     (123)    20135 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/microvisor/v1/device/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19145 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/microvisor/v1/device/device_config.py
--rw-r--r--   0 runner    (1001) docker     (123)    19030 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/microvisor/v1/device/device_secret.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.109005 twilio-8.3.0/twilio/rest/monitor/
--rw-r--r--   0 runner    (1001) docker     (123)     1203 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/monitor/MonitorBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      658 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/monitor/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.109005 twilio-8.3.0/twilio/rest/monitor/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1517 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/monitor/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22723 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/monitor/v1/alert.py
--rw-r--r--   0 runner    (1001) docker     (123)    25437 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/monitor/v1/event.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.113005 twilio-8.3.0/twilio/rest/notify/
--rw-r--r--   0 runner    (1001) docker     (123)     1196 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/notify/NotifyBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      700 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/notify/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.113005 twilio-8.3.0/twilio/rest/notify/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1581 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/notify/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27961 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/notify/v1/credential.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.113005 twilio-8.3.0/twilio/rest/notify/v1/service/
--rw-r--r--   0 runner    (1001) docker     (123)    47060 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/notify/v1/service/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    30272 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/notify/v1/service/binding.py
--rw-r--r--   0 runner    (1001) docker     (123)    25490 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/notify/v1/service/notification.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.113005 twilio-8.3.0/twilio/rest/numbers/
--rw-r--r--   0 runner    (1001) docker     (123)     1468 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/NumbersBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      491 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.113005 twilio-8.3.0/twilio/rest/numbers/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1374 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7086 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v1/bulk_eligibility.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.113005 twilio-8.3.0/twilio/rest/numbers/v2/
--rw-r--r--   0 runner    (1001) docker     (123)     1414 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v2/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.117005 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/
--rw-r--r--   0 runner    (1001) docker     (123)     3690 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.117005 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/
--rw-r--r--   0 runner    (1001) docker     (123)    47502 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13880 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/bundle_copy.py
--rw-r--r--   0 runner    (1001) docker     (123)    16186 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/evaluation.py
--rw-r--r--   0 runner    (1001) docker     (123)    17833 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/item_assignment.py
--rw-r--r--   0 runner    (1001) docker     (123)     5665 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/replace_items.py
--rw-r--r--   0 runner    (1001) docker     (123)    20500 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/end_user.py
--rw-r--r--   0 runner    (1001) docker     (123)    14140 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/end_user_type.py
--rw-r--r--   0 runner    (1001) docker     (123)    18536 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/regulation.py
--rw-r--r--   0 runner    (1001) docker     (123)    22407 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/supporting_document.py
--rw-r--r--   0 runner    (1001) docker     (123)    14788 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/supporting_document_type.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.117005 twilio-8.3.0/twilio/rest/oauth/
--rw-r--r--   0 runner    (1001) docker     (123)     1189 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/oauth/OauthBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     1578 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/oauth/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.117005 twilio-8.3.0/twilio/rest/oauth/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     2434 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/oauth/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4598 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/oauth/v1/device_code.py
--rw-r--r--   0 runner    (1001) docker     (123)     4115 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/oauth/v1/oauth.py
--rw-r--r--   0 runner    (1001) docker     (123)     7059 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/oauth/v1/openid_discovery.py
--rw-r--r--   0 runner    (1001) docker     (123)     6329 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/oauth/v1/token.py
--rw-r--r--   0 runner    (1001) docker     (123)     4714 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/oauth/v1/user_info.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.121005 twilio-8.3.0/twilio/rest/preview/
--rw-r--r--   0 runner    (1001) docker     (123)     3081 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/PreviewBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     3528 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.121005 twilio-8.3.0/twilio/rest/preview/deployed_devices/
--rw-r--r--   0 runner    (1001) docker     (123)     1329 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/deployed_devices/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.121005 twilio-8.3.0/twilio/rest/preview/deployed_devices/fleet/
--rw-r--r--   0 runner    (1001) docker     (123)    22442 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/deployed_devices/fleet/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24118 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/deployed_devices/fleet/certificate.py
--rw-r--r--   0 runner    (1001) docker     (123)    22163 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/deployed_devices/fleet/deployment.py
--rw-r--r--   0 runner    (1001) docker     (123)    26656 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/deployed_devices/fleet/device.py
--rw-r--r--   0 runner    (1001) docker     (123)    22726 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/deployed_devices/fleet/key.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.121005 twilio-8.3.0/twilio/rest/preview/hosted_numbers/
--rw-r--r--   0 runner    (1001) docker     (123)     1892 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/hosted_numbers/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.121005 twilio-8.3.0/twilio/rest/preview/hosted_numbers/authorization_document/
--rw-r--r--   0 runner    (1001) docker     (123)    32009 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/hosted_numbers/authorization_document/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24829 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/hosted_numbers/authorization_document/dependent_hosted_number_order.py
--rw-r--r--   0 runner    (1001) docker     (123)    48143 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/hosted_numbers/hosted_number_order.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.121005 twilio-8.3.0/twilio/rest/preview/marketplace/
--rw-r--r--   0 runner    (1001) docker     (123)     1775 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/marketplace/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.121005 twilio-8.3.0/twilio/rest/preview/marketplace/available_add_on/
--rw-r--r--   0 runner    (1001) docker     (123)    15067 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/marketplace/available_add_on/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16163 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/marketplace/available_add_on/available_add_on_extension.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.125006 twilio-8.3.0/twilio/rest/preview/marketplace/installed_add_on/
--rw-r--r--   0 runner    (1001) docker     (123)    23293 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/marketplace/installed_add_on/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18542 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/marketplace/installed_add_on/installed_add_on_extension.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.125006 twilio-8.3.0/twilio/rest/preview/sync/
--rw-r--r--   0 runner    (1001) docker     (123)     1293 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/sync/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.125006 twilio-8.3.0/twilio/rest/preview/sync/service/
--rw-r--r--   0 runner    (1001) docker     (123)    22270 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/sync/service/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.125006 twilio-8.3.0/twilio/rest/preview/sync/service/document/
--rw-r--r--   0 runner    (1001) docker     (123)    20547 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/sync/service/document/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21455 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/sync/service/document/document_permission.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.125006 twilio-8.3.0/twilio/rest/preview/sync/service/sync_list/
--rw-r--r--   0 runner    (1001) docker     (123)    18339 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/sync/service/sync_list/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24174 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/sync/service/sync_list/sync_list_item.py
--rw-r--r--   0 runner    (1001) docker     (123)    21397 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/sync/service/sync_list/sync_list_permission.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.125006 twilio-8.3.0/twilio/rest/preview/sync/service/sync_map/
--rw-r--r--   0 runner    (1001) docker     (123)    18217 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/sync/service/sync_map/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    24063 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/sync/service/sync_map/sync_map_item.py
--rw-r--r--   0 runner    (1001) docker     (123)    21250 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/sync/service/sync_map/sync_map_permission.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.125006 twilio-8.3.0/twilio/rest/preview/understand/
--rw-r--r--   0 runner    (1001) docker     (123)     1343 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.129006 twilio-8.3.0/twilio/rest/preview/understand/assistant/
--rw-r--r--   0 runner    (1001) docker     (123)    35382 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     8318 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/assistant_fallback_actions.py
--rw-r--r--   0 runner    (1001) docker     (123)     8510 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/assistant_initiation_actions.py
--rw-r--r--   0 runner    (1001) docker     (123)     5976 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/dialogue.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.129006 twilio-8.3.0/twilio/rest/preview/understand/assistant/field_type/
--rw-r--r--   0 runner    (1001) docker     (123)    22348 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/field_type/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20410 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/field_type/field_value.py
--rw-r--r--   0 runner    (1001) docker     (123)    21062 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/model_build.py
--rw-r--r--   0 runner    (1001) docker     (123)    26433 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/query.py
--rw-r--r--   0 runner    (1001) docker     (123)     7799 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/style_sheet.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.129006 twilio-8.3.0/twilio/rest/preview/understand/assistant/task/
--rw-r--r--   0 runner    (1001) docker     (123)    26813 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/task/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19110 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/task/field.py
--rw-r--r--   0 runner    (1001) docker     (123)    24937 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/task/sample.py
--rw-r--r--   0 runner    (1001) docker     (123)     8816 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/task/task_actions.py
--rw-r--r--   0 runner    (1001) docker     (123)     6871 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/understand/assistant/task/task_statistics.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.129006 twilio-8.3.0/twilio/rest/preview/wireless/
--rw-r--r--   0 runner    (1001) docker     (123)     1849 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/wireless/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18911 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/wireless/command.py
--rw-r--r--   0 runner    (1001) docker     (123)    21681 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/wireless/rate_plan.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.133006 twilio-8.3.0/twilio/rest/preview/wireless/sim/
--rw-r--r--   0 runner    (1001) docker     (123)    28867 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/wireless/sim/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6592 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/preview/wireless/sim/usage.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.133006 twilio-8.3.0/twilio/rest/pricing/
--rw-r--r--   0 runner    (1001) docker     (123)     1468 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/PricingBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     1569 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.133006 twilio-8.3.0/twilio/rest/pricing/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1867 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.133006 twilio-8.3.0/twilio/rest/pricing/v1/messaging/
--rw-r--r--   0 runner    (1001) docker     (123)     1443 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v1/messaging/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14530 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v1/messaging/country.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.133006 twilio-8.3.0/twilio/rest/pricing/v1/phone_number/
--rw-r--r--   0 runner    (1001) docker     (123)     1455 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v1/phone_number/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14123 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v1/phone_number/country.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.133006 twilio-8.3.0/twilio/rest/pricing/v1/voice/
--rw-r--r--   0 runner    (1001) docker     (123)     1753 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v1/voice/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14416 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v1/voice/country.py
--rw-r--r--   0 runner    (1001) docker     (123)     5701 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v1/voice/number.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.133006 twilio-8.3.0/twilio/rest/pricing/v2/
--rw-r--r--   0 runner    (1001) docker     (123)     1801 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14470 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v2/country.py
--rw-r--r--   0 runner    (1001) docker     (123)     8966 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v2/number.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.133006 twilio-8.3.0/twilio/rest/pricing/v2/voice/
--rw-r--r--   0 runner    (1001) docker     (123)     1753 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v2/voice/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14446 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v2/voice/country.py
--rw-r--r--   0 runner    (1001) docker     (123)     9040 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/pricing/v2/voice/number.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.137006 twilio-8.3.0/twilio/rest/proxy/
--rw-r--r--   0 runner    (1001) docker     (123)     1189 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/proxy/ProxyBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      387 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/proxy/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.137006 twilio-8.3.0/twilio/rest/proxy/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1273 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/proxy/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.137006 twilio-8.3.0/twilio/rest/proxy/v1/service/
--rw-r--r--   0 runner    (1001) docker     (123)    38044 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/proxy/v1/service/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23754 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/proxy/v1/service/phone_number.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.137006 twilio-8.3.0/twilio/rest/proxy/v1/service/session/
--rw-r--r--   0 runner    (1001) docker     (123)    27767 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/proxy/v1/service/session/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21109 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/proxy/v1/service/session/interaction.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.137006 twilio-8.3.0/twilio/rest/proxy/v1/service/session/participant/
--rw-r--r--   0 runner    (1001) docker     (123)    22765 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/proxy/v1/service/session/participant/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23242 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/proxy/v1/service/session/participant/message_interaction.py
--rw-r--r--   0 runner    (1001) docker     (123)    21333 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/proxy/v1/service/short_code.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.137006 twilio-8.3.0/twilio/rest/routes/
--rw-r--r--   0 runner    (1001) docker     (123)     1196 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/routes/RoutesBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/routes/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.141007 twilio-8.3.0/twilio/rest/routes/v2/
--rw-r--r--   0 runner    (1001) docker     (123)     1876 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/routes/v2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9727 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/routes/v2/phone_number.py
--rw-r--r--   0 runner    (1001) docker     (123)     8319 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/routes/v2/sip_domain.py
--rw-r--r--   0 runner    (1001) docker     (123)     9536 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/routes/v2/trunk.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.141007 twilio-8.3.0/twilio/rest/serverless/
--rw-r--r--   0 runner    (1001) docker     (123)     1224 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/ServerlessBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      417 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.141007 twilio-8.3.0/twilio/rest/serverless/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1298 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.141007 twilio-8.3.0/twilio/rest/serverless/v1/service/
--rw-r--r--   0 runner    (1001) docker     (123)    25510 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/service/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.141007 twilio-8.3.0/twilio/rest/serverless/v1/service/asset/
--rw-r--r--   0 runner    (1001) docker     (123)    20582 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/service/asset/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    16714 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/service/asset/asset_version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.141007 twilio-8.3.0/twilio/rest/serverless/v1/service/build/
--rw-r--r--   0 runner    (1001) docker     (123)    20195 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/service/build/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6403 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/service/build/build_status.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.141007 twilio-8.3.0/twilio/rest/serverless/v1/service/environment/
--rw-r--r--   0 runner    (1001) docker     (123)    21009 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/service/environment/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18049 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/service/environment/deployment.py
--rw-r--r--   0 runner    (1001) docker     (123)    20926 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/service/environment/log.py
--rw-r--r--   0 runner    (1001) docker     (123)    22598 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/service/environment/variable.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.141007 twilio-8.3.0/twilio/rest/serverless/v1/service/function/
--rw-r--r--   0 runner    (1001) docker     (123)    20928 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/service/function/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.145007 twilio-8.3.0/twilio/rest/serverless/v1/service/function/function_version/
--rw-r--r--   0 runner    (1001) docker     (123)    18093 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/service/function/function_version/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7736 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/serverless/v1/service/function/function_version/function_version_content.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.145007 twilio-8.3.0/twilio/rest/studio/
--rw-r--r--   0 runner    (1001) docker     (123)     1459 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/StudioBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      694 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.145007 twilio-8.3.0/twilio/rest/studio/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1248 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.145007 twilio-8.3.0/twilio/rest/studio/v1/flow/
--rw-r--r--   0 runner    (1001) docker     (123)    16404 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v1/flow/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.145007 twilio-8.3.0/twilio/rest/studio/v1/flow/engagement/
--rw-r--r--   0 runner    (1001) docker     (123)    21366 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v1/flow/engagement/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6720 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v1/flow/engagement/engagement_context.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.145007 twilio-8.3.0/twilio/rest/studio/v1/flow/engagement/step/
--rw-r--r--   0 runner    (1001) docker     (123)    17219 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v1/flow/engagement/step/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7395 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v1/flow/engagement/step/step_context.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.145007 twilio-8.3.0/twilio/rest/studio/v1/flow/execution/
--rw-r--r--   0 runner    (1001) docker     (123)    27270 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v1/flow/execution/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6877 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v1/flow/execution/execution_context.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.145007 twilio-8.3.0/twilio/rest/studio/v1/flow/execution/execution_step/
--rw-r--r--   0 runner    (1001) docker     (123)    17888 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v1/flow/execution/execution_step/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7716 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v1/flow/execution/execution_step/execution_step_context.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.145007 twilio-8.3.0/twilio/rest/studio/v2/
--rw-r--r--   0 runner    (1001) docker     (123)     1572 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v2/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.149007 twilio-8.3.0/twilio/rest/studio/v2/flow/
--rw-r--r--   0 runner    (1001) docker     (123)    23658 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v2/flow/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.149007 twilio-8.3.0/twilio/rest/studio/v2/flow/execution/
--rw-r--r--   0 runner    (1001) docker     (123)    27154 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v2/flow/execution/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6877 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v2/flow/execution/execution_context.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.149007 twilio-8.3.0/twilio/rest/studio/v2/flow/execution/execution_step/
--rw-r--r--   0 runner    (1001) docker     (123)    17888 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v2/flow/execution/execution_step/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7716 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v2/flow/execution/execution_step/execution_step_context.py
--rw-r--r--   0 runner    (1001) docker     (123)    16059 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v2/flow/flow_revision.py
--rw-r--r--   0 runner    (1001) docker     (123)     7422 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v2/flow/flow_test_user.py
--rw-r--r--   0 runner    (1001) docker     (123)     3892 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/studio/v2/flow_validate.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.149007 twilio-8.3.0/twilio/rest/supersim/
--rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/SupersimBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     2908 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.149007 twilio-8.3.0/twilio/rest/supersim/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     3800 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23623 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/esim_profile.py
--rw-r--r--   0 runner    (1001) docker     (123)    35221 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/fleet.py
--rw-r--r--   0 runner    (1001) docker     (123)    26640 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/ip_command.py
--rw-r--r--   0 runner    (1001) docker     (123)    17582 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/network.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.153007 twilio-8.3.0/twilio/rest/supersim/v1/network_access_profile/
--rw-r--r--   0 runner    (1001) docker     (123)    20071 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/network_access_profile/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19359 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/network_access_profile/network_access_profile_network.py
--rw-r--r--   0 runner    (1001) docker     (123)    14206 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/settings_update.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.153007 twilio-8.3.0/twilio/rest/supersim/v1/sim/
--rw-r--r--   0 runner    (1001) docker     (123)    28732 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/sim/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    12030 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/sim/billing_period.py
--rw-r--r--   0 runner    (1001) docker     (123)    10625 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/sim/sim_ip_address.py
--rw-r--r--   0 runner    (1001) docker     (123)    23001 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/sms_command.py
--rw-r--r--   0 runner    (1001) docker     (123)    26841 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/supersim/v1/usage_record.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.153007 twilio-8.3.0/twilio/rest/sync/
--rw-r--r--   0 runner    (1001) docker     (123)     1182 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/SyncBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      381 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.153007 twilio-8.3.0/twilio/rest/sync/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1268 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.153007 twilio-8.3.0/twilio/rest/sync/v1/service/
--rw-r--r--   0 runner    (1001) docker     (123)    36623 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/v1/service/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.153007 twilio-8.3.0/twilio/rest/sync/v1/service/document/
--rw-r--r--   0 runner    (1001) docker     (123)    25373 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/v1/service/document/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21822 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/v1/service/document/document_permission.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.153007 twilio-8.3.0/twilio/rest/sync/v1/service/sync_list/
--rw-r--r--   0 runner    (1001) docker     (123)    25198 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/v1/service/sync_list/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    36671 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/v1/service/sync_list/sync_list_item.py
--rw-r--r--   0 runner    (1001) docker     (123)    21826 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/v1/service/sync_list/sync_list_permission.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.157008 twilio-8.3.0/twilio/rest/sync/v1/service/sync_map/
--rw-r--r--   0 runner    (1001) docker     (123)    24886 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/v1/service/sync_map/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    37230 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/v1/service/sync_map/sync_map_item.py
--rw-r--r--   0 runner    (1001) docker     (123)    21754 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/v1/service/sync_map/sync_map_permission.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.157008 twilio-8.3.0/twilio/rest/sync/v1/service/sync_stream/
--rw-r--r--   0 runner    (1001) docker     (123)    22899 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/v1/service/sync_stream/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4315 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/sync/v1/service/sync_stream/stream_message.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.157008 twilio-8.3.0/twilio/rest/taskrouter/
--rw-r--r--   0 runner    (1001) docker     (123)     1224 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/TaskrouterBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      431 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.157008 twilio-8.3.0/twilio/rest/taskrouter/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1318 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.157008 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/
--rw-r--r--   0 runner    (1001) docker     (123)    44452 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    25986 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/activity.py
--rw-r--r--   0 runner    (1001) docker     (123)    32776 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/event.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.161008 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task/
--rw-r--r--   0 runner    (1001) docker     (123)    51478 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    79751 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task/reservation.py
--rw-r--r--   0 runner    (1001) docker     (123)    23470 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_channel.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.161008 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_queue/
--rw-r--r--   0 runner    (1001) docker     (123)    39230 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_queue/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18318 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queue_cumulative_statistics.py
--rw-r--r--   0 runner    (1001) docker     (123)    10983 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queue_real_time_statistics.py
--rw-r--r--   0 runner    (1001) docker     (123)    13380 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queue_statistics.py
--rw-r--r--   0 runner    (1001) docker     (123)    21315 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queues_statistics.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.165008 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/
--rw-r--r--   0 runner    (1001) docker     (123)    43462 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    77533 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/reservation.py
--rw-r--r--   0 runner    (1001) docker     (123)    22091 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/worker_channel.py
--rw-r--r--   0 runner    (1001) docker     (123)    11730 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/worker_statistics.py
--rw-r--r--   0 runner    (1001) docker     (123)    13241 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/workers_cumulative_statistics.py
--rw-r--r--   0 runner    (1001) docker     (123)     7884 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/workers_real_time_statistics.py
--rw-r--r--   0 runner    (1001) docker     (123)    13545 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/workers_statistics.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.165008 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workflow/
--rw-r--r--   0 runner    (1001) docker     (123)    34579 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workflow/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    19228 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workflow/workflow_cumulative_statistics.py
--rw-r--r--   0 runner    (1001) docker     (123)     9689 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workflow/workflow_real_time_statistics.py
--rw-r--r--   0 runner    (1001) docker     (123)    14701 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workflow/workflow_statistics.py
--rw-r--r--   0 runner    (1001) docker     (123)    18165 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workspace_cumulative_statistics.py
--rw-r--r--   0 runner    (1001) docker     (123)     9027 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workspace_real_time_statistics.py
--rw-r--r--   0 runner    (1001) docker     (123)    13564 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workspace_statistics.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.165008 twilio-8.3.0/twilio/rest/trunking/
--rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trunking/TrunkingBase.py
--rw-r--r--   0 runner    (1001) docker     (123)      391 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trunking/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.165008 twilio-8.3.0/twilio/rest/trunking/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     1268 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trunking/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.165008 twilio-8.3.0/twilio/rest/trunking/v1/trunk/
--rw-r--r--   0 runner    (1001) docker     (123)    39976 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trunking/v1/trunk/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    18350 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trunking/v1/trunk/credential_list.py
--rw-r--r--   0 runner    (1001) docker     (123)    18720 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trunking/v1/trunk/ip_access_control_list.py
--rw-r--r--   0 runner    (1001) docker     (123)    27739 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trunking/v1/trunk/origination_url.py
--rw-r--r--   0 runner    (1001) docker     (123)    22459 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trunking/v1/trunk/phone_number.py
--rw-r--r--   0 runner    (1001) docker     (123)     8181 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trunking/v1/trunk/recording.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.165008 twilio-8.3.0/twilio/rest/trusthub/
--rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/TrusthubBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     2483 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.169008 twilio-8.3.0/twilio/rest/trusthub/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     3431 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.169008 twilio-8.3.0/twilio/rest/trusthub/v1/customer_profiles/
--rw-r--r--   0 runner    (1001) docker     (123)    30761 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/customer_profiles/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23437 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/customer_profiles/customer_profiles_channel_endpoint_assignment.py
--rw-r--r--   0 runner    (1001) docker     (123)    19934 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/customer_profiles/customer_profiles_entity_assignments.py
--rw-r--r--   0 runner    (1001) docker     (123)    18436 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/customer_profiles/customer_profiles_evaluations.py
--rw-r--r--   0 runner    (1001) docker     (123)    20560 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/end_user.py
--rw-r--r--   0 runner    (1001) docker     (123)    14103 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/end_user_type.py
--rw-r--r--   0 runner    (1001) docker     (123)    13542 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/policies.py
--rw-r--r--   0 runner    (1001) docker     (123)    22191 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/supporting_document.py
--rw-r--r--   0 runner    (1001) docker     (123)    14729 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/supporting_document_type.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.169008 twilio-8.3.0/twilio/rest/trusthub/v1/trust_products/
--rw-r--r--   0 runner    (1001) docker     (123)    30206 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/trust_products/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    23131 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/trust_products/trust_products_channel_endpoint_assignment.py
--rw-r--r--   0 runner    (1001) docker     (123)    19505 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/trust_products/trust_products_entity_assignments.py
--rw-r--r--   0 runner    (1001) docker     (123)    18057 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/trusthub/v1/trust_products/trust_products_evaluations.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.173009 twilio-8.3.0/twilio/rest/verify/
--rw-r--r--   0 runner    (1001) docker     (123)     1196 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/VerifyBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     2056 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.173009 twilio-8.3.0/twilio/rest/verify/v2/
--rw-r--r--   0 runner    (1001) docker     (123)     2992 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5695 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/form.py
--rw-r--r--   0 runner    (1001) docker     (123)     8036 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/safelist.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.173009 twilio-8.3.0/twilio/rest/verify/v2/service/
--rw-r--r--   0 runner    (1001) docker     (123)    55315 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    10267 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/access_token.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.177009 twilio-8.3.0/twilio/rest/verify/v2/service/entity/
--rw-r--r--   0 runner    (1001) docker     (123)    20668 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/entity/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.177009 twilio-8.3.0/twilio/rest/verify/v2/service/entity/challenge/
--rw-r--r--   0 runner    (1001) docker     (123)    34458 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/entity/challenge/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6557 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/entity/challenge/notification.py
--rw-r--r--   0 runner    (1001) docker     (123)    29593 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/entity/factor.py
--rw-r--r--   0 runner    (1001) docker     (123)    16164 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/entity/new_factor.py
--rw-r--r--   0 runner    (1001) docker     (123)    23201 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/messaging_configuration.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.177009 twilio-8.3.0/twilio/rest/verify/v2/service/rate_limit/
--rw-r--r--   0 runner    (1001) docker     (123)    21507 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/rate_limit/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22242 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/rate_limit/bucket.py
--rw-r--r--   0 runner    (1001) docker     (123)    21417 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/verification.py
--rw-r--r--   0 runner    (1001) docker     (123)     8363 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/verification_check.py
--rw-r--r--   0 runner    (1001) docker     (123)    25389 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/service/webhook.py
--rw-r--r--   0 runner    (1001) docker     (123)    11731 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/template.py
--rw-r--r--   0 runner    (1001) docker     (123)    29432 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/verification_attempt.py
--rw-r--r--   0 runner    (1001) docker     (123)    13009 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/verify/v2/verification_attempts_summary.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.177009 twilio-8.3.0/twilio/rest/video/
--rw-r--r--   0 runner    (1001) docker     (123)     1189 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/VideoBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     2050 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.177009 twilio-8.3.0/twilio/rest/video/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     2971 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    34977 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/composition.py
--rw-r--r--   0 runner    (1001) docker     (123)    54707 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/composition_hook.py
--rw-r--r--   0 runner    (1001) docker     (123)    14079 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/composition_settings.py
--rw-r--r--   0 runner    (1001) docker     (123)    27313 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/recording.py
--rw-r--r--   0 runner    (1001) docker     (123)    13910 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/recording_settings.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.181009 twilio-8.3.0/twilio/rest/video/v1/room/
--rw-r--r--   0 runner    (1001) docker     (123)    38074 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/room/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.181009 twilio-8.3.0/twilio/rest/video/v1/room/participant/
--rw-r--r--   0 runner    (1001) docker     (123)    28698 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/room/participant/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     7905 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/room/participant/anonymize.py
--rw-r--r--   0 runner    (1001) docker     (123)    16887 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/room/participant/published_track.py
--rw-r--r--   0 runner    (1001) docker     (123)     6391 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/room/participant/subscribe_rules.py
--rw-r--r--   0 runner    (1001) docker     (123)    17079 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/room/participant/subscribed_track.py
--rw-r--r--   0 runner    (1001) docker     (123)     5087 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/room/recording_rules.py
--rw-r--r--   0 runner    (1001) docker     (123)    24746 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/video/v1/room/room_recording.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.181009 twilio-8.3.0/twilio/rest/voice/
--rw-r--r--   0 runner    (1001) docker     (123)     1189 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/VoiceBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     2099 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.181009 twilio-8.3.0/twilio/rest/voice/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     3035 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3316 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/v1/archived_call.py
--rw-r--r--   0 runner    (1001) docker     (123)    37359 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/v1/byoc_trunk.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.181009 twilio-8.3.0/twilio/rest/voice/v1/connection_policy/
--rw-r--r--   0 runner    (1001) docker     (123)    20484 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/v1/connection_policy/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    29170 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/v1/connection_policy/connection_policy_target.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.185009 twilio-8.3.0/twilio/rest/voice/v1/dialing_permissions/
--rw-r--r--   0 runner    (1001) docker     (123)     2327 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/v1/dialing_permissions/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3837 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/v1/dialing_permissions/bulk_country_update.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.185009 twilio-8.3.0/twilio/rest/voice/v1/dialing_permissions/country/
--rw-r--r--   0 runner    (1001) docker     (123)    26486 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/v1/dialing_permissions/country/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11128 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/v1/dialing_permissions/country/highrisk_special_prefix.py
--rw-r--r--   0 runner    (1001) docker     (123)     6995 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/v1/dialing_permissions/settings.py
--rw-r--r--   0 runner    (1001) docker     (123)    20413 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/v1/ip_record.py
--rw-r--r--   0 runner    (1001) docker     (123)    19429 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/voice/v1/source_ip_mapping.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.185009 twilio-8.3.0/twilio/rest/wireless/
--rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/wireless/WirelessBase.py
--rw-r--r--   0 runner    (1001) docker     (123)     1261 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/wireless/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.185009 twilio-8.3.0/twilio/rest/wireless/v1/
--rw-r--r--   0 runner    (1001) docker     (123)     2135 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/wireless/v1/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    27361 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/wireless/v1/command.py
--rw-r--r--   0 runner    (1001) docker     (123)    29604 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/wireless/v1/rate_plan.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.185009 twilio-8.3.0/twilio/rest/wireless/v1/sim/
--rw-r--r--   0 runner    (1001) docker     (123)    46125 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/wireless/v1/sim/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    14307 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/wireless/v1/sim/data_session.py
--rw-r--r--   0 runner    (1001) docker     (123)    17463 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/wireless/v1/sim/usage_record.py
--rw-r--r--   0 runner    (1001) docker     (123)    16059 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/rest/wireless/v1/usage_record.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.189010 twilio-8.3.0/twilio/twiml/
--rw-r--r--   0 runner    (1001) docker     (123)     3471 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/twiml/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1435 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/twiml/fax_response.py
--rw-r--r--   0 runner    (1001) docker     (123)     2935 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/twiml/messaging_response.py
--rw-r--r--   0 runner    (1001) docker     (123)    82958 2023-06-15 07:43:30.000000 twilio-8.3.0/twilio/twiml/voice_response.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-15 07:43:44.020999 twilio-8.3.0/twilio.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    11938 2023-06-15 07:43:43.000000 twilio-8.3.0/twilio.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    30474 2023-06-15 07:43:43.000000 twilio-8.3.0/twilio.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-15 07:43:43.000000 twilio-8.3.0/twilio.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-15 07:43:43.000000 twilio-8.3.0/twilio.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-15 07:43:43.000000 twilio-8.3.0/twilio.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.848114 twilio-8.4.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1387 2023-06-28 11:33:54.000000 twilio-8.4.0/AUTHORS.md
+-rw-r--r--   0 runner    (1001) docker     (123)     1088 2023-06-28 11:33:54.000000 twilio-8.4.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      117 2023-06-28 11:33:54.000000 twilio-8.4.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)    11938 2023-06-28 11:34:08.848114 twilio-8.4.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    10921 2023-06-28 11:33:54.000000 twilio-8.4.0/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      236 2023-06-28 11:34:08.848114 twilio-8.4.0/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1694 2023-06-28 11:33:54.000000 twilio-8.4.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.736111 twilio-8.4.0/twilio/
+-rw-r--r--   0 runner    (1001) docker     (123)       76 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.740111 twilio-8.4.0/twilio/base/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8153 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/client_base.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2019 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/deserialize.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2978 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/domain.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2890 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/exceptions.py
+-rw-r--r--   0 runner    (1001) docker     (123)      147 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/instance_context.py
+-rw-r--r--   0 runner    (1001) docker     (123)      148 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/instance_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)      144 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/list_resource.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1417 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/obsolete.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5181 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/page.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2039 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/serialize.py
+-rw-r--r--   0 runner    (1001) docker     (123)      280 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/values.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14614 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/base/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.740111 twilio-8.4.0/twilio/http/
+-rw-r--r--   0 runner    (1001) docker     (123)     3434 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/http/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4503 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/http/async_http_client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3735 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/http/http_client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2655 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/http/request.py
+-rw-r--r--   0 runner    (1001) docker     (123)      518 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/http/response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4810 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/http/validation_client.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.740111 twilio-8.4.0/twilio/jwt/
+-rw-r--r--   0 runner    (1001) docker     (123)     5085 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/jwt/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.740111 twilio-8.4.0/twilio/jwt/access_token/
+-rw-r--r--   0 runner    (1001) docker     (123)     2415 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/jwt/access_token/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4902 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/jwt/access_token/grants.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.740111 twilio-8.4.0/twilio/jwt/client/
+-rw-r--r--   0 runner    (1001) docker     (123)     3982 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/jwt/client/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.740111 twilio-8.4.0/twilio/jwt/taskrouter/
+-rw-r--r--   0 runner    (1001) docker     (123)     5726 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/jwt/taskrouter/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4309 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/jwt/taskrouter/capabilities.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.740111 twilio-8.4.0/twilio/jwt/validation/
+-rw-r--r--   0 runner    (1001) docker     (123)     3156 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/jwt/validation/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4100 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/request_validator.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.740111 twilio-8.4.0/twilio/rest/
+-rw-r--r--   0 runner    (1001) docker     (123)    21358 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.740111 twilio-8.4.0/twilio/rest/accounts/
+-rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/accounts/AccountsBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1168 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/accounts/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.740111 twilio-8.4.0/twilio/rest/accounts/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     2102 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/accounts/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5547 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/accounts/v1/auth_token_promotion.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.740111 twilio-8.4.0/twilio/rest/accounts/v1/credential/
+-rw-r--r--   0 runner    (1001) docker     (123)     1766 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/accounts/v1/credential/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19489 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/accounts/v1/credential/aws.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20007 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/accounts/v1/credential/public_key.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6551 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/accounts/v1/secondary_auth_token.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.744111 twilio-8.4.0/twilio/rest/api/
+-rw-r--r--   0 runner    (1001) docker     (123)     1208 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/ApiBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8255 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.744111 twilio-8.4.0/twilio/rest/api/v2010/
+-rw-r--r--   0 runner    (1001) docker     (123)     1805 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.744111 twilio-8.4.0/twilio/rest/api/v2010/account/
+-rw-r--r--   0 runner    (1001) docker     (123)    36206 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.744111 twilio-8.4.0/twilio/rest/api/v2010/account/address/
+-rw-r--r--   0 runner    (1001) docker     (123)    35858 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/address/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17044 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/address/dependent_phone_number.py
+-rw-r--r--   0 runner    (1001) docker     (123)    47553 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/application.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17274 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/authorized_connect_app.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.748111 twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/
+-rw-r--r--   0 runner    (1001) docker     (123)    21427 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    46239 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/local.py
+-rw-r--r--   0 runner    (1001) docker     (123)    46210 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/machine_to_machine.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45860 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/mobile.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45930 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/national.py
+-rw-r--r--   0 runner    (1001) docker     (123)    46000 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/shared_cost.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45930 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/toll_free.py
+-rw-r--r--   0 runner    (1001) docker     (123)    45790 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/voip.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3186 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/balance.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.748111 twilio-8.4.0/twilio/rest/api/v2010/account/call/
+-rw-r--r--   0 runner    (1001) docker     (123)    92392 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/call/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10658 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/call/event.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11932 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/call/feedback.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13986 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/call/feedback_summary.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28363 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/call/notification.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23472 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/call/payment.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38495 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/call/recording.py
+-rw-r--r--   0 runner    (1001) docker     (123)    77226 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/call/siprec.py
+-rw-r--r--   0 runner    (1001) docker     (123)    77116 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/call/stream.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5278 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/call/user_defined_message.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10898 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/call/user_defined_message_subscription.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.752111 twilio-8.4.0/twilio/rest/api/v2010/account/conference/
+-rw-r--r--   0 runner    (1001) docker     (123)    41186 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/conference/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    75225 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/conference/participant.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32729 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/conference/recording.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26539 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/connect_app.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.752111 twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/
+-rw-r--r--   0 runner    (1001) docker     (123)    73374 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.752111 twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/assigned_add_on/
+-rw-r--r--   0 runner    (1001) docker     (123)    20750 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/assigned_add_on/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18341 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/assigned_add_on/assigned_add_on_extension.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36935 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/local.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37019 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/mobile.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37103 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/toll_free.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17989 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/key.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.752111 twilio-8.4.0/twilio/rest/api/v2010/account/message/
+-rw-r--r--   0 runner    (1001) docker     (123)    53984 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/message/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5102 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/message/feedback.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27246 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/message/media.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4785 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/new_key.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4813 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/new_signing_key.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27505 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/notification.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22199 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/outgoing_caller_id.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.752111 twilio-8.4.0/twilio/rest/api/v2010/account/queue/
+-rw-r--r--   0 runner    (1001) docker     (123)    22428 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/queue/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19131 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/queue/member.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.752111 twilio-8.4.0/twilio/rest/api/v2010/account/recording/
+-rw-r--r--   0 runner    (1001) docker     (123)    37769 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/recording/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.752111 twilio-8.4.0/twilio/rest/api/v2010/account/recording/add_on_result/
+-rw-r--r--   0 runner    (1001) docker     (123)    19239 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/recording/add_on_result/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19233 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/recording/add_on_result/payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19008 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/recording/transcription.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26406 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/short_code.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17376 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/signing_key.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.752111 twilio-8.4.0/twilio/rest/api/v2010/account/sip/
+-rw-r--r--   0 runner    (1001) docker     (123)     2871 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.752111 twilio-8.4.0/twilio/rest/api/v2010/account/sip/credential_list/
+-rw-r--r--   0 runner    (1001) docker     (123)    21278 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/credential_list/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22757 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/credential_list/credential.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.756111 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/
+-rw-r--r--   0 runner    (1001) docker     (123)    45116 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.756111 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/
+-rw-r--r--   0 runner    (1001) docker     (123)     2758 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.756111 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/
+-rw-r--r--   0 runner    (1001) docker     (123)     3330 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20440 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/auth_calls_credential_list_mapping.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20981 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/auth_calls_ip_access_control_list_mapping.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.756111 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_registrations/
+-rw-r--r--   0 runner    (1001) docker     (123)     2473 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_registrations/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21048 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_registrations/auth_registrations_credential_list_mapping.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19893 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/credential_list_mapping.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20164 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/ip_access_control_list_mapping.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.756111 twilio-8.4.0/twilio/rest/api/v2010/account/sip/ip_access_control_list/
+-rw-r--r--   0 runner    (1001) docker     (123)    21808 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/ip_access_control_list/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26238 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/sip/ip_access_control_list/ip_address.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4823 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/token.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18034 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/transcription.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.756111 twilio-8.4.0/twilio/rest/api/v2010/account/usage/
+-rw-r--r--   0 runner    (1001) docker     (123)     2220 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/usage/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.756111 twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/
+-rw-r--r--   0 runner    (1001) docker     (123)    41695 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38339 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/all_time.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38247 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/daily.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38431 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/last_month.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38339 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/monthly.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38431 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/this_month.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38247 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/today.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38293 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/yearly.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38431 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/yesterday.py
+-rw-r--r--   0 runner    (1001) docker     (123)    49245 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/usage/trigger.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7397 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/api/v2010/account/validation_request.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.760111 twilio-8.4.0/twilio/rest/autopilot/
+-rw-r--r--   0 runner    (1001) docker     (123)     1217 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/AutopilotBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      778 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.760111 twilio-8.4.0/twilio/rest/autopilot/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1680 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.760111 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/
+-rw-r--r--   0 runner    (1001) docker     (123)    35087 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8479 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/defaults.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6698 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/dialogue.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.760111 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/field_type/
+-rw-r--r--   0 runner    (1001) docker     (123)    23752 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/field_type/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22246 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/field_type/field_value.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22851 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/model_build.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29877 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/query.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8288 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/style_sheet.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.760111 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/task/
+-rw-r--r--   0 runner    (1001) docker     (123)    28213 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/task/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20115 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/task/field.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27891 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/task/sample.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9964 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/task/task_actions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7530 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/task/task_statistics.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24728 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/assistant/webhook.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5222 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/autopilot/v1/restore_assistant.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.760111 twilio-8.4.0/twilio/rest/bulkexports/
+-rw-r--r--   0 runner    (1001) docker     (123)     1231 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/bulkexports/BulkexportsBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      792 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/bulkexports/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.760111 twilio-8.4.0/twilio/rest/bulkexports/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1692 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/bulkexports/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.764112 twilio-8.4.0/twilio/rest/bulkexports/v1/export/
+-rw-r--r--   0 runner    (1001) docker     (123)     7083 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/bulkexports/v1/export/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14521 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/bulkexports/v1/export/day.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17005 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/bulkexports/v1/export/export_custom_job.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8224 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/bulkexports/v1/export/job.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10811 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/bulkexports/v1/export_configuration.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.764112 twilio-8.4.0/twilio/rest/chat/
+-rw-r--r--   0 runner    (1001) docker     (123)     1700 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/ChatBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      970 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.764112 twilio-8.4.0/twilio/rest/chat/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1569 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27856 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v1/credential.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.764112 twilio-8.4.0/twilio/rest/chat/v1/service/
+-rw-r--r--   0 runner    (1001) docker     (123)    92674 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v1/service/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.764112 twilio-8.4.0/twilio/rest/chat/v1/service/channel/
+-rw-r--r--   0 runner    (1001) docker     (123)    28967 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v1/service/channel/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22312 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v1/service/channel/invite.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27709 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v1/service/channel/member.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26356 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v1/service/channel/message.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21831 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v1/service/role.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.764112 twilio-8.4.0/twilio/rest/chat/v1/service/user/
+-rw-r--r--   0 runner    (1001) docker     (123)    26317 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v1/service/user/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12925 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v1/service/user/user_channel.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.764112 twilio-8.4.0/twilio/rest/chat/v2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1569 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27486 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/credential.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.764112 twilio-8.4.0/twilio/rest/chat/v2/service/
+-rw-r--r--   0 runner    (1001) docker     (123)    66570 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/service/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22118 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/service/binding.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.768112 twilio-8.4.0/twilio/rest/chat/v2/service/channel/
+-rw-r--r--   0 runner    (1001) docker     (123)    39123 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/service/channel/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22292 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/service/channel/invite.py
+-rw-r--r--   0 runner    (1001) docker     (123)    41109 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/service/channel/member.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37545 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/service/channel/message.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33770 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/service/channel/webhook.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22232 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/service/role.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.768112 twilio-8.4.0/twilio/rest/chat/v2/service/user/
+-rw-r--r--   0 runner    (1001) docker     (123)    29035 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/service/user/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21909 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/service/user/user_binding.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27050 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v2/service/user/user_channel.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.768112 twilio-8.4.0/twilio/rest/chat/v3/
+-rw-r--r--   0 runner    (1001) docker     (123)     1268 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v3/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11567 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/chat/v3/channel.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.768112 twilio-8.4.0/twilio/rest/content/
+-rw-r--r--   0 runner    (1001) docker     (123)     1203 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/content/ContentBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1110 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/content/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.768112 twilio-8.4.0/twilio/rest/content/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     2024 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/content/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.768112 twilio-8.4.0/twilio/rest/content/v1/content/
+-rw-r--r--   0 runner    (1001) docker     (123)    16628 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/content/v1/content/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5839 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/content/v1/content/approval_fetch.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11924 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/content/v1/content_and_approvals.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12123 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/content/v1/legacy_content.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.768112 twilio-8.4.0/twilio/rest/conversations/
+-rw-r--r--   0 runner    (1001) docker     (123)     1245 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/ConversationsBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2760 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.768112 twilio-8.4.0/twilio/rest/conversations/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     3659 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37619 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/address_configuration.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.772112 twilio-8.4.0/twilio/rest/conversations/v1/configuration/
+-rw-r--r--   0 runner    (1001) docker     (123)    12497 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/configuration/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11083 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/configuration/webhook.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.772112 twilio-8.4.0/twilio/rest/conversations/v1/conversation/
+-rw-r--r--   0 runner    (1001) docker     (123)    42957 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/conversation/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.772112 twilio-8.4.0/twilio/rest/conversations/v1/conversation/message/
+-rw-r--r--   0 runner    (1001) docker     (123)    34972 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/conversation/message/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18063 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/conversation/message/delivery_receipt.py
+-rw-r--r--   0 runner    (1001) docker     (123)    40116 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/conversation/participant.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27236 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/conversation/webhook.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27935 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/credential.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18739 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/participant_conversation.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20943 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/role.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.772112 twilio-8.4.0/twilio/rest/conversations/v1/service/
+-rw-r--r--   0 runner    (1001) docker     (123)    20025 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22289 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/binding.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.772112 twilio-8.4.0/twilio/rest/conversations/v1/service/configuration/
+-rw-r--r--   0 runner    (1001) docker     (123)    16088 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/configuration/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24410 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/configuration/notification.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13881 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/configuration/webhook.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.772112 twilio-8.4.0/twilio/rest/conversations/v1/service/conversation/
+-rw-r--r--   0 runner    (1001) docker     (123)    44808 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/conversation/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.772112 twilio-8.4.0/twilio/rest/conversations/v1/service/conversation/message/
+-rw-r--r--   0 runner    (1001) docker     (123)    36629 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/conversation/message/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19398 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/conversation/message/delivery_receipt.py
+-rw-r--r--   0 runner    (1001) docker     (123)    41799 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/conversation/participant.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28926 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/conversation/webhook.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19530 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/participant_conversation.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22534 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/role.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.772112 twilio-8.4.0/twilio/rest/conversations/v1/service/user/
+-rw-r--r--   0 runner    (1001) docker     (123)    29682 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/user/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26510 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/service/user/user_conversation.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.776112 twilio-8.4.0/twilio/rest/conversations/v1/user/
+-rw-r--r--   0 runner    (1001) docker     (123)    28016 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/user/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25215 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/conversations/v1/user/user_conversation.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.776112 twilio-8.4.0/twilio/rest/events/
+-rw-r--r--   0 runner    (1001) docker     (123)     1196 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/events/EventsBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1277 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/events/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.776112 twilio-8.4.0/twilio/rest/events/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     2133 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/events/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15317 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/events/v1/event_type.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.776112 twilio-8.4.0/twilio/rest/events/v1/schema/
+-rw-r--r--   0 runner    (1001) docker     (123)     6417 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/events/v1/schema/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14920 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/events/v1/schema/schema_version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.776112 twilio-8.4.0/twilio/rest/events/v1/sink/
+-rw-r--r--   0 runner    (1001) docker     (123)    22872 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/events/v1/sink/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2768 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/events/v1/sink/sink_test.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3358 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/events/v1/sink/sink_validate.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.776112 twilio-8.4.0/twilio/rest/events/v1/subscription/
+-rw-r--r--   0 runner    (1001) docker     (123)    22609 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/events/v1/subscription/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20282 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/events/v1/subscription/subscribed_event.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.776112 twilio-8.4.0/twilio/rest/flex_api/
+-rw-r--r--   0 runner    (1001) docker     (123)     1471 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/FlexApiBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6332 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.780112 twilio-8.4.0/twilio/rest/flex_api/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     7374 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23439 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/assessments.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19793 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/channel.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13488 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/configuration.py
+-rw-r--r--   0 runner    (1001) docker     (123)    46860 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/flex_flow.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17361 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/insights_assessments_comment.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12870 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/insights_conversations.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27954 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/insights_questionnaires.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21091 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/insights_questionnaires_category.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26772 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/insights_questionnaires_question.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15944 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/insights_segments.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5688 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/insights_session.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3164 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/insights_settings_answer_sets.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2745 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/insights_settings_comment.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5365 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/insights_user_roles.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.780112 twilio-8.4.0/twilio/rest/flex_api/v1/interaction/
+-rw-r--r--   0 runner    (1001) docker     (123)     8562 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/interaction/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.780112 twilio-8.4.0/twilio/rest/flex_api/v1/interaction/interaction_channel/
+-rw-r--r--   0 runner    (1001) docker     (123)    20915 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/interaction/interaction_channel/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13861 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/interaction/interaction_channel/interaction_channel_invite.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19858 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/interaction/interaction_channel/interaction_channel_participant.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20821 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v1/web_channel.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.780112 twilio-8.4.0/twilio/rest/flex_api/v2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1323 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5583 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/flex_api/v2/web_channels.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.780112 twilio-8.4.0/twilio/rest/frontline_api/
+-rw-r--r--   0 runner    (1001) docker     (123)     1240 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/frontline_api/FrontlineApiBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/frontline_api/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.780112 twilio-8.4.0/twilio/rest/frontline_api/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1277 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/frontline_api/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10822 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/frontline_api/v1/user.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.780112 twilio-8.4.0/twilio/rest/insights/
+-rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/InsightsBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1579 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.780112 twilio-8.4.0/twilio/rest/insights/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     2419 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.784112 twilio-8.4.0/twilio/rest/insights/v1/call/
+-rw-r--r--   0 runner    (1001) docker     (123)     6981 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/v1/call/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17572 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/v1/call/annotation.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11166 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/v1/call/call_summary.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13650 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/v1/call/event.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14822 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/v1/call/metric.py
+-rw-r--r--   0 runner    (1001) docker     (123)    46779 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/v1/call_summaries.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.784112 twilio-8.4.0/twilio/rest/insights/v1/conference/
+-rw-r--r--   0 runner    (1001) docker     (123)    31370 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/v1/conference/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25248 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/v1/conference/conference_participant.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.784112 twilio-8.4.0/twilio/rest/insights/v1/room/
+-rw-r--r--   0 runner    (1001) docker     (123)    25243 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/v1/room/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17908 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/v1/room/participant.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9037 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/insights/v1/setting.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.784112 twilio-8.4.0/twilio/rest/ip_messaging/
+-rw-r--r--   0 runner    (1001) docker     (123)     1507 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/IpMessagingBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      738 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.784112 twilio-8.4.0/twilio/rest/ip_messaging/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1615 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21632 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v1/credential.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.784112 twilio-8.4.0/twilio/rest/ip_messaging/v1/service/
+-rw-r--r--   0 runner    (1001) docker     (123)    62960 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v1/service/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.784112 twilio-8.4.0/twilio/rest/ip_messaging/v1/service/channel/
+-rw-r--r--   0 runner    (1001) docker     (123)    24064 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v1/service/channel/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18541 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v1/service/channel/invite.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21725 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v1/service/channel/member.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21818 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v1/service/channel/message.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18855 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v1/service/role.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.784112 twilio-8.4.0/twilio/rest/ip_messaging/v1/service/user/
+-rw-r--r--   0 runner    (1001) docker     (123)    21365 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v1/service/user/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11548 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v1/service/user/user_channel.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.784112 twilio-8.4.0/twilio/rest/ip_messaging/v2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1615 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21632 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/credential.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.788112 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/
+-rw-r--r--   0 runner    (1001) docker     (123)    45390 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17907 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/binding.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.788112 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/channel/
+-rw-r--r--   0 runner    (1001) docker     (123)    30568 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/channel/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18541 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/channel/invite.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29520 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/channel/member.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28798 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/channel/message.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26175 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/channel/webhook.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18855 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/role.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.788112 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/user/
+-rw-r--r--   0 runner    (1001) docker     (123)    24051 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/user/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18192 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/user/user_binding.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21476 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/ip_messaging/v2/service/user/user_channel.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.788112 twilio-8.4.0/twilio/rest/lookups/
+-rw-r--r--   0 runner    (1001) docker     (123)     1468 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/lookups/LookupsBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      432 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/lookups/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.788112 twilio-8.4.0/twilio/rest/lookups/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1329 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/lookups/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13250 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/lookups/v1/phone_number.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.788112 twilio-8.4.0/twilio/rest/lookups/v2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1329 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/lookups/v2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23018 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/lookups/v2/phone_number.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.788112 twilio-8.4.0/twilio/rest/media/
+-rw-r--r--   0 runner    (1001) docker     (123)     1189 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/media/MediaBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1107 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/media/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.792112 twilio-8.4.0/twilio/rest/media/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     2030 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/media/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26533 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/media/v1/media_processor.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22582 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/media/v1/media_recording.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.792112 twilio-8.4.0/twilio/rest/media/v1/player_streamer/
+-rw-r--r--   0 runner    (1001) docker     (123)    25414 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/media/v1/player_streamer/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9432 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/media/v1/player_streamer/playback_grant.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.792112 twilio-8.4.0/twilio/rest/messaging/
+-rw-r--r--   0 runner    (1001) docker     (123)     1217 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/MessagingBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3308 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.792112 twilio-8.4.0/twilio/rest/messaging/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     5200 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.792112 twilio-8.4.0/twilio/rest/messaging/v1/brand_registration/
+-rw-r--r--   0 runner    (1001) docker     (123)    24289 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/brand_registration/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3583 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/brand_registration/brand_registration_otp.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19914 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/brand_registration/brand_vetting.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5796 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/deactivations.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10495 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/domain_certs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13875 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/domain_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7990 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/domain_config_messaging_service.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4360 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/external_campaign.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9216 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/linkshortening_messaging_service.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7383 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/linkshortening_messaging_service_domain_association.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.792112 twilio-8.4.0/twilio/rest/messaging/v1/service/
+-rw-r--r--   0 runner    (1001) docker     (123)    54653 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/service/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18348 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/service/alpha_sender.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18413 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/service/phone_number.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18135 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/service/short_code.py
+-rw-r--r--   0 runner    (1001) docker     (123)    33638 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/service/us_app_to_person.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3513 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/service/us_app_to_person_usecase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2322 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/messaging/v1/usecase.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.792112 twilio-8.4.0/twilio/rest/microvisor/
+-rw-r--r--   0 runner    (1001) docker     (123)     1224 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/microvisor/MicrovisorBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1321 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/microvisor/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.796112 twilio-8.4.0/twilio/rest/microvisor/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     2211 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/microvisor/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17838 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/microvisor/v1/account_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17723 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/microvisor/v1/account_secret.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.796112 twilio-8.4.0/twilio/rest/microvisor/v1/app/
+-rw-r--r--   0 runner    (1001) docker     (123)    15664 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/microvisor/v1/app/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5534 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/microvisor/v1/app/app_manifest.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.796112 twilio-8.4.0/twilio/rest/microvisor/v1/device/
+-rw-r--r--   0 runner    (1001) docker     (123)    20135 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/microvisor/v1/device/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19145 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/microvisor/v1/device/device_config.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19030 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/microvisor/v1/device/device_secret.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.796112 twilio-8.4.0/twilio/rest/monitor/
+-rw-r--r--   0 runner    (1001) docker     (123)     1203 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/monitor/MonitorBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      658 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/monitor/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.796112 twilio-8.4.0/twilio/rest/monitor/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1517 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/monitor/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22723 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/monitor/v1/alert.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25437 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/monitor/v1/event.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.796112 twilio-8.4.0/twilio/rest/notify/
+-rw-r--r--   0 runner    (1001) docker     (123)     1196 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/notify/NotifyBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      700 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/notify/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.796112 twilio-8.4.0/twilio/rest/notify/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1581 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/notify/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27961 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/notify/v1/credential.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.796112 twilio-8.4.0/twilio/rest/notify/v1/service/
+-rw-r--r--   0 runner    (1001) docker     (123)    47060 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/notify/v1/service/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    30272 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/notify/v1/service/binding.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25490 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/notify/v1/service/notification.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.796112 twilio-8.4.0/twilio/rest/numbers/
+-rw-r--r--   0 runner    (1001) docker     (123)     1468 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/NumbersBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      491 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.796112 twilio-8.4.0/twilio/rest/numbers/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     2210 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7086 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v1/bulk_eligibility.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8744 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v1/porting_bulk_portability.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7631 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v1/porting_portability.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.800113 twilio-8.4.0/twilio/rest/numbers/v2/
+-rw-r--r--   0 runner    (1001) docker     (123)     2220 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.800113 twilio-8.4.0/twilio/rest/numbers/v2/authorization_document/
+-rw-r--r--   0 runner    (1001) docker     (123)    24508 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/authorization_document/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22095 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/authorization_document/dependent_hosted_number_order.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35471 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/hosted_number_order.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.800113 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/
+-rw-r--r--   0 runner    (1001) docker     (123)     3690 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.800113 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/
+-rw-r--r--   0 runner    (1001) docker     (123)    47502 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13880 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/bundle_copy.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16186 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/evaluation.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17833 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/item_assignment.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5665 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/replace_items.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20500 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/end_user.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14140 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/end_user_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18536 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/regulation.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22407 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/supporting_document.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14788 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/supporting_document_type.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.800113 twilio-8.4.0/twilio/rest/oauth/
+-rw-r--r--   0 runner    (1001) docker     (123)     1189 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/oauth/OauthBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1578 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/oauth/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.800113 twilio-8.4.0/twilio/rest/oauth/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     2434 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/oauth/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4598 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/oauth/v1/device_code.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4115 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/oauth/v1/oauth.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7059 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/oauth/v1/openid_discovery.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6329 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/oauth/v1/token.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4714 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/oauth/v1/user_info.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.804113 twilio-8.4.0/twilio/rest/preview/
+-rw-r--r--   0 runner    (1001) docker     (123)     3081 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/PreviewBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3528 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.804113 twilio-8.4.0/twilio/rest/preview/deployed_devices/
+-rw-r--r--   0 runner    (1001) docker     (123)     1329 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/deployed_devices/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.804113 twilio-8.4.0/twilio/rest/preview/deployed_devices/fleet/
+-rw-r--r--   0 runner    (1001) docker     (123)    22442 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/deployed_devices/fleet/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24118 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/deployed_devices/fleet/certificate.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22163 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/deployed_devices/fleet/deployment.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26656 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/deployed_devices/fleet/device.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22726 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/deployed_devices/fleet/key.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.804113 twilio-8.4.0/twilio/rest/preview/hosted_numbers/
+-rw-r--r--   0 runner    (1001) docker     (123)     1892 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/hosted_numbers/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.804113 twilio-8.4.0/twilio/rest/preview/hosted_numbers/authorization_document/
+-rw-r--r--   0 runner    (1001) docker     (123)    32009 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/hosted_numbers/authorization_document/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24829 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/hosted_numbers/authorization_document/dependent_hosted_number_order.py
+-rw-r--r--   0 runner    (1001) docker     (123)    48143 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/hosted_numbers/hosted_number_order.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.804113 twilio-8.4.0/twilio/rest/preview/marketplace/
+-rw-r--r--   0 runner    (1001) docker     (123)     1775 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/marketplace/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.804113 twilio-8.4.0/twilio/rest/preview/marketplace/available_add_on/
+-rw-r--r--   0 runner    (1001) docker     (123)    15067 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/marketplace/available_add_on/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16163 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/marketplace/available_add_on/available_add_on_extension.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.804113 twilio-8.4.0/twilio/rest/preview/marketplace/installed_add_on/
+-rw-r--r--   0 runner    (1001) docker     (123)    23293 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/marketplace/installed_add_on/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18542 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/marketplace/installed_add_on/installed_add_on_extension.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.804113 twilio-8.4.0/twilio/rest/preview/sync/
+-rw-r--r--   0 runner    (1001) docker     (123)     1293 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/sync/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.804113 twilio-8.4.0/twilio/rest/preview/sync/service/
+-rw-r--r--   0 runner    (1001) docker     (123)    22270 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/sync/service/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.804113 twilio-8.4.0/twilio/rest/preview/sync/service/document/
+-rw-r--r--   0 runner    (1001) docker     (123)    20547 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/sync/service/document/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21455 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/sync/service/document/document_permission.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.808113 twilio-8.4.0/twilio/rest/preview/sync/service/sync_list/
+-rw-r--r--   0 runner    (1001) docker     (123)    18339 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/sync/service/sync_list/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24174 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/sync/service/sync_list/sync_list_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21397 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/sync/service/sync_list/sync_list_permission.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.808113 twilio-8.4.0/twilio/rest/preview/sync/service/sync_map/
+-rw-r--r--   0 runner    (1001) docker     (123)    18217 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/sync/service/sync_map/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24063 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/sync/service/sync_map/sync_map_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21250 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/sync/service/sync_map/sync_map_permission.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.808113 twilio-8.4.0/twilio/rest/preview/understand/
+-rw-r--r--   0 runner    (1001) docker     (123)     1343 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.808113 twilio-8.4.0/twilio/rest/preview/understand/assistant/
+-rw-r--r--   0 runner    (1001) docker     (123)    35382 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8318 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/assistant_fallback_actions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8510 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/assistant_initiation_actions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5976 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/dialogue.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.808113 twilio-8.4.0/twilio/rest/preview/understand/assistant/field_type/
+-rw-r--r--   0 runner    (1001) docker     (123)    22348 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/field_type/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20410 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/field_type/field_value.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21062 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/model_build.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26433 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/query.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7799 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/style_sheet.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.808113 twilio-8.4.0/twilio/rest/preview/understand/assistant/task/
+-rw-r--r--   0 runner    (1001) docker     (123)    26813 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/task/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19110 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/task/field.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24937 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/task/sample.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8816 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/task/task_actions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6871 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/understand/assistant/task/task_statistics.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.812113 twilio-8.4.0/twilio/rest/preview/wireless/
+-rw-r--r--   0 runner    (1001) docker     (123)     1849 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/wireless/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18911 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/wireless/command.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21681 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/wireless/rate_plan.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.812113 twilio-8.4.0/twilio/rest/preview/wireless/sim/
+-rw-r--r--   0 runner    (1001) docker     (123)    28867 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/wireless/sim/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6592 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/preview/wireless/sim/usage.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.812113 twilio-8.4.0/twilio/rest/pricing/
+-rw-r--r--   0 runner    (1001) docker     (123)     1468 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/PricingBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1569 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.812113 twilio-8.4.0/twilio/rest/pricing/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1867 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.812113 twilio-8.4.0/twilio/rest/pricing/v1/messaging/
+-rw-r--r--   0 runner    (1001) docker     (123)     1443 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v1/messaging/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14530 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v1/messaging/country.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.812113 twilio-8.4.0/twilio/rest/pricing/v1/phone_number/
+-rw-r--r--   0 runner    (1001) docker     (123)     1455 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v1/phone_number/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14123 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v1/phone_number/country.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.812113 twilio-8.4.0/twilio/rest/pricing/v1/voice/
+-rw-r--r--   0 runner    (1001) docker     (123)     1753 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v1/voice/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14416 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v1/voice/country.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5701 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v1/voice/number.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.812113 twilio-8.4.0/twilio/rest/pricing/v2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1801 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14470 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v2/country.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8966 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v2/number.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.812113 twilio-8.4.0/twilio/rest/pricing/v2/voice/
+-rw-r--r--   0 runner    (1001) docker     (123)     1753 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v2/voice/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14446 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v2/voice/country.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9040 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/pricing/v2/voice/number.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.812113 twilio-8.4.0/twilio/rest/proxy/
+-rw-r--r--   0 runner    (1001) docker     (123)     1189 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/proxy/ProxyBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      387 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/proxy/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.812113 twilio-8.4.0/twilio/rest/proxy/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1273 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/proxy/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.812113 twilio-8.4.0/twilio/rest/proxy/v1/service/
+-rw-r--r--   0 runner    (1001) docker     (123)    38044 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/proxy/v1/service/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23754 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/proxy/v1/service/phone_number.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.816113 twilio-8.4.0/twilio/rest/proxy/v1/service/session/
+-rw-r--r--   0 runner    (1001) docker     (123)    27767 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/proxy/v1/service/session/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21109 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/proxy/v1/service/session/interaction.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.816113 twilio-8.4.0/twilio/rest/proxy/v1/service/session/participant/
+-rw-r--r--   0 runner    (1001) docker     (123)    22765 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/proxy/v1/service/session/participant/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23242 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/proxy/v1/service/session/participant/message_interaction.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21333 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/proxy/v1/service/short_code.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.816113 twilio-8.4.0/twilio/rest/routes/
+-rw-r--r--   0 runner    (1001) docker     (123)     1196 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/routes/RoutesBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1003 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/routes/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.816113 twilio-8.4.0/twilio/rest/routes/v2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1876 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/routes/v2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9727 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/routes/v2/phone_number.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8319 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/routes/v2/sip_domain.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9536 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/routes/v2/trunk.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.816113 twilio-8.4.0/twilio/rest/serverless/
+-rw-r--r--   0 runner    (1001) docker     (123)     1224 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/ServerlessBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      417 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.816113 twilio-8.4.0/twilio/rest/serverless/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1298 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.816113 twilio-8.4.0/twilio/rest/serverless/v1/service/
+-rw-r--r--   0 runner    (1001) docker     (123)    25510 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/service/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.816113 twilio-8.4.0/twilio/rest/serverless/v1/service/asset/
+-rw-r--r--   0 runner    (1001) docker     (123)    20582 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/service/asset/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16714 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/service/asset/asset_version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.816113 twilio-8.4.0/twilio/rest/serverless/v1/service/build/
+-rw-r--r--   0 runner    (1001) docker     (123)    20195 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/service/build/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6403 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/service/build/build_status.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.816113 twilio-8.4.0/twilio/rest/serverless/v1/service/environment/
+-rw-r--r--   0 runner    (1001) docker     (123)    21009 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/service/environment/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18049 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/service/environment/deployment.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20926 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/service/environment/log.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22598 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/service/environment/variable.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.816113 twilio-8.4.0/twilio/rest/serverless/v1/service/function/
+-rw-r--r--   0 runner    (1001) docker     (123)    20928 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/service/function/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/serverless/v1/service/function/function_version/
+-rw-r--r--   0 runner    (1001) docker     (123)    18093 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/service/function/function_version/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7736 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/serverless/v1/service/function/function_version/function_version_content.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/studio/
+-rw-r--r--   0 runner    (1001) docker     (123)     1459 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/StudioBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      694 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/studio/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1248 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/studio/v1/flow/
+-rw-r--r--   0 runner    (1001) docker     (123)    16404 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v1/flow/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/studio/v1/flow/engagement/
+-rw-r--r--   0 runner    (1001) docker     (123)    21366 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v1/flow/engagement/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6720 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v1/flow/engagement/engagement_context.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/studio/v1/flow/engagement/step/
+-rw-r--r--   0 runner    (1001) docker     (123)    17219 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v1/flow/engagement/step/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7395 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v1/flow/engagement/step/step_context.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/studio/v1/flow/execution/
+-rw-r--r--   0 runner    (1001) docker     (123)    27270 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v1/flow/execution/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6877 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v1/flow/execution/execution_context.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/studio/v1/flow/execution/execution_step/
+-rw-r--r--   0 runner    (1001) docker     (123)    17888 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v1/flow/execution/execution_step/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7716 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v1/flow/execution/execution_step/execution_step_context.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/studio/v2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1572 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v2/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/studio/v2/flow/
+-rw-r--r--   0 runner    (1001) docker     (123)    23658 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v2/flow/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/studio/v2/flow/execution/
+-rw-r--r--   0 runner    (1001) docker     (123)    27154 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v2/flow/execution/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6877 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v2/flow/execution/execution_context.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/studio/v2/flow/execution/execution_step/
+-rw-r--r--   0 runner    (1001) docker     (123)    17888 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v2/flow/execution/execution_step/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7716 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v2/flow/execution/execution_step/execution_step_context.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16059 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v2/flow/flow_revision.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7422 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v2/flow/flow_test_user.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3892 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/studio/v2/flow_validate.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.820113 twilio-8.4.0/twilio/rest/supersim/
+-rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/SupersimBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2908 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.824113 twilio-8.4.0/twilio/rest/supersim/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     3800 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23623 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/esim_profile.py
+-rw-r--r--   0 runner    (1001) docker     (123)    35221 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/fleet.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26640 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/ip_command.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17582 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/network.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.824113 twilio-8.4.0/twilio/rest/supersim/v1/network_access_profile/
+-rw-r--r--   0 runner    (1001) docker     (123)    20071 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/network_access_profile/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19359 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/network_access_profile/network_access_profile_network.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14206 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/settings_update.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.824113 twilio-8.4.0/twilio/rest/supersim/v1/sim/
+-rw-r--r--   0 runner    (1001) docker     (123)    28732 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/sim/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12030 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/sim/billing_period.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10625 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/sim/sim_ip_address.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23001 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/sms_command.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26841 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/supersim/v1/usage_record.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.824113 twilio-8.4.0/twilio/rest/sync/
+-rw-r--r--   0 runner    (1001) docker     (123)     1182 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/SyncBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      381 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.824113 twilio-8.4.0/twilio/rest/sync/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1268 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.824113 twilio-8.4.0/twilio/rest/sync/v1/service/
+-rw-r--r--   0 runner    (1001) docker     (123)    36623 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/v1/service/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.824113 twilio-8.4.0/twilio/rest/sync/v1/service/document/
+-rw-r--r--   0 runner    (1001) docker     (123)    25373 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/v1/service/document/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21822 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/v1/service/document/document_permission.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.824113 twilio-8.4.0/twilio/rest/sync/v1/service/sync_list/
+-rw-r--r--   0 runner    (1001) docker     (123)    25198 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/v1/service/sync_list/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36671 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/v1/service/sync_list/sync_list_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21826 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/v1/service/sync_list/sync_list_permission.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.828113 twilio-8.4.0/twilio/rest/sync/v1/service/sync_map/
+-rw-r--r--   0 runner    (1001) docker     (123)    24886 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/v1/service/sync_map/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37230 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/v1/service/sync_map/sync_map_item.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21754 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/v1/service/sync_map/sync_map_permission.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.828113 twilio-8.4.0/twilio/rest/sync/v1/service/sync_stream/
+-rw-r--r--   0 runner    (1001) docker     (123)    22899 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/v1/service/sync_stream/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4315 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/sync/v1/service/sync_stream/stream_message.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.828113 twilio-8.4.0/twilio/rest/taskrouter/
+-rw-r--r--   0 runner    (1001) docker     (123)     1224 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/TaskrouterBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      431 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.828113 twilio-8.4.0/twilio/rest/taskrouter/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1318 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.828113 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/
+-rw-r--r--   0 runner    (1001) docker     (123)    44452 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25986 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/activity.py
+-rw-r--r--   0 runner    (1001) docker     (123)    32776 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/event.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.828113 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task/
+-rw-r--r--   0 runner    (1001) docker     (123)    51478 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    79751 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task/reservation.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23470 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_channel.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.828113 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_queue/
+-rw-r--r--   0 runner    (1001) docker     (123)    39230 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_queue/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18318 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queue_cumulative_statistics.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10983 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queue_real_time_statistics.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13380 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queue_statistics.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21315 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queues_statistics.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.832113 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/
+-rw-r--r--   0 runner    (1001) docker     (123)    43912 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    77533 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/reservation.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22091 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/worker_channel.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11730 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/worker_statistics.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13241 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/workers_cumulative_statistics.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7884 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/workers_real_time_statistics.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13545 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/workers_statistics.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.832113 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workflow/
+-rw-r--r--   0 runner    (1001) docker     (123)    34579 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workflow/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19228 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workflow/workflow_cumulative_statistics.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9689 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workflow/workflow_real_time_statistics.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14701 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workflow/workflow_statistics.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18165 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workspace_cumulative_statistics.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9027 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workspace_real_time_statistics.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13564 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workspace_statistics.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.832113 twilio-8.4.0/twilio/rest/trunking/
+-rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trunking/TrunkingBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)      391 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trunking/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.832113 twilio-8.4.0/twilio/rest/trunking/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1268 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trunking/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.832113 twilio-8.4.0/twilio/rest/trunking/v1/trunk/
+-rw-r--r--   0 runner    (1001) docker     (123)    39976 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trunking/v1/trunk/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18350 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trunking/v1/trunk/credential_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18720 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trunking/v1/trunk/ip_access_control_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27739 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trunking/v1/trunk/origination_url.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22459 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trunking/v1/trunk/phone_number.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8181 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trunking/v1/trunk/recording.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.832113 twilio-8.4.0/twilio/rest/trusthub/
+-rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/TrusthubBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2483 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.836114 twilio-8.4.0/twilio/rest/trusthub/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     3431 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.836114 twilio-8.4.0/twilio/rest/trusthub/v1/customer_profiles/
+-rw-r--r--   0 runner    (1001) docker     (123)    30761 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/customer_profiles/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23437 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/customer_profiles/customer_profiles_channel_endpoint_assignment.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19934 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/customer_profiles/customer_profiles_entity_assignments.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18436 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/customer_profiles/customer_profiles_evaluations.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20560 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/end_user.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14103 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/end_user_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13542 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/policies.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22191 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/supporting_document.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14729 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/supporting_document_type.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.836114 twilio-8.4.0/twilio/rest/trusthub/v1/trust_products/
+-rw-r--r--   0 runner    (1001) docker     (123)    30206 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/trust_products/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23131 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/trust_products/trust_products_channel_endpoint_assignment.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19505 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/trust_products/trust_products_entity_assignments.py
+-rw-r--r--   0 runner    (1001) docker     (123)    18057 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/trusthub/v1/trust_products/trust_products_evaluations.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.836114 twilio-8.4.0/twilio/rest/verify/
+-rw-r--r--   0 runner    (1001) docker     (123)     1196 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/VerifyBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2056 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.836114 twilio-8.4.0/twilio/rest/verify/v2/
+-rw-r--r--   0 runner    (1001) docker     (123)     2992 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5695 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/form.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8036 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/safelist.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.840114 twilio-8.4.0/twilio/rest/verify/v2/service/
+-rw-r--r--   0 runner    (1001) docker     (123)    55315 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10267 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/access_token.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.840114 twilio-8.4.0/twilio/rest/verify/v2/service/entity/
+-rw-r--r--   0 runner    (1001) docker     (123)    20668 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/entity/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.840114 twilio-8.4.0/twilio/rest/verify/v2/service/entity/challenge/
+-rw-r--r--   0 runner    (1001) docker     (123)    34458 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/entity/challenge/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6557 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/entity/challenge/notification.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29593 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/entity/factor.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16164 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/entity/new_factor.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23201 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/messaging_configuration.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.840114 twilio-8.4.0/twilio/rest/verify/v2/service/rate_limit/
+-rw-r--r--   0 runner    (1001) docker     (123)    21507 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/rate_limit/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22242 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/rate_limit/bucket.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21417 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/verification.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8363 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/verification_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25389 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/service/webhook.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11731 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/template.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29432 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/verification_attempt.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13009 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/verify/v2/verification_attempts_summary.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.840114 twilio-8.4.0/twilio/rest/video/
+-rw-r--r--   0 runner    (1001) docker     (123)     1189 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/VideoBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2050 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.840114 twilio-8.4.0/twilio/rest/video/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     2971 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    34977 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/composition.py
+-rw-r--r--   0 runner    (1001) docker     (123)    54707 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/composition_hook.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14079 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/composition_settings.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27313 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/recording.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13910 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/recording_settings.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.840114 twilio-8.4.0/twilio/rest/video/v1/room/
+-rw-r--r--   0 runner    (1001) docker     (123)    38074 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/room/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.844114 twilio-8.4.0/twilio/rest/video/v1/room/participant/
+-rw-r--r--   0 runner    (1001) docker     (123)    28698 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/room/participant/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7905 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/room/participant/anonymize.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16887 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/room/participant/published_track.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6391 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/room/participant/subscribe_rules.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17079 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/room/participant/subscribed_track.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5087 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/room/recording_rules.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24746 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/video/v1/room/room_recording.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.844114 twilio-8.4.0/twilio/rest/voice/
+-rw-r--r--   0 runner    (1001) docker     (123)     1189 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/VoiceBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2099 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.844114 twilio-8.4.0/twilio/rest/voice/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     3035 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3316 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/v1/archived_call.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37359 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/v1/byoc_trunk.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.844114 twilio-8.4.0/twilio/rest/voice/v1/connection_policy/
+-rw-r--r--   0 runner    (1001) docker     (123)    20484 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/v1/connection_policy/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29170 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/v1/connection_policy/connection_policy_target.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.844114 twilio-8.4.0/twilio/rest/voice/v1/dialing_permissions/
+-rw-r--r--   0 runner    (1001) docker     (123)     2327 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/v1/dialing_permissions/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3837 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/v1/dialing_permissions/bulk_country_update.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.844114 twilio-8.4.0/twilio/rest/voice/v1/dialing_permissions/country/
+-rw-r--r--   0 runner    (1001) docker     (123)    26486 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/v1/dialing_permissions/country/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11128 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/v1/dialing_permissions/country/highrisk_special_prefix.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6995 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/v1/dialing_permissions/settings.py
+-rw-r--r--   0 runner    (1001) docker     (123)    20413 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/v1/ip_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19429 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/voice/v1/source_ip_mapping.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.844114 twilio-8.4.0/twilio/rest/wireless/
+-rw-r--r--   0 runner    (1001) docker     (123)     1210 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/wireless/WirelessBase.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1261 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/wireless/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.844114 twilio-8.4.0/twilio/rest/wireless/v1/
+-rw-r--r--   0 runner    (1001) docker     (123)     2135 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/wireless/v1/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    27361 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/wireless/v1/command.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29604 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/wireless/v1/rate_plan.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.844114 twilio-8.4.0/twilio/rest/wireless/v1/sim/
+-rw-r--r--   0 runner    (1001) docker     (123)    46125 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/wireless/v1/sim/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    14307 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/wireless/v1/sim/data_session.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17463 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/wireless/v1/sim/usage_record.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16059 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/rest/wireless/v1/usage_record.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.848114 twilio-8.4.0/twilio/twiml/
+-rw-r--r--   0 runner    (1001) docker     (123)     3471 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/twiml/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1435 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/twiml/fax_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2935 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/twiml/messaging_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)    82958 2023-06-28 11:33:54.000000 twilio-8.4.0/twilio/twiml/voice_response.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:34:08.736111 twilio-8.4.0/twilio.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    11938 2023-06-28 11:34:08.000000 twilio-8.4.0/twilio.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    30754 2023-06-28 11:34:08.000000 twilio-8.4.0/twilio.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:34:08.000000 twilio-8.4.0/twilio.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       77 2023-06-28 11:34:08.000000 twilio-8.4.0/twilio.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 11:34:08.000000 twilio-8.4.0/twilio.egg-info/top_level.txt
```

### Comparing `twilio-8.3.0/AUTHORS.md` & `twilio-8.4.0/AUTHORS.md`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/LICENSE` & `twilio-8.4.0/LICENSE`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/PKG-INFO` & `twilio-8.4.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: twilio
-Version: 8.3.0
+Version: 8.4.0
 Summary: Twilio API client and TwiML generator
 Home-page: https://github.com/twilio/twilio-python/
 Author: Twilio
 Author-email: help@twilio.com
 Keywords: twilio,twiml
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
```

### Comparing `twilio-8.3.0/README.md` & `twilio-8.4.0/README.md`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/setup.py` & `twilio-8.4.0/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -9,15 +9,15 @@
 # python setup.py install
 #
 # You need to have the setuptools module installed. Try reading the setuptools
 # documentation: http://pypi.python.org/pypi/setuptools
 
 setup(
     name="twilio",
-    version="8.3.0",
+    version="8.4.0",
     description="Twilio API client and TwiML generator",
     author="Twilio",
     author_email="help@twilio.com",
     url="https://github.com/twilio/twilio-python/",
     keywords=["twilio", "twiml"],
     python_requires=">=3.7.0",
     install_requires=[
```

### Comparing `twilio-8.3.0/twilio/base/client_base.py` & `twilio-8.4.0/twilio/base/client_base.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/base/deserialize.py` & `twilio-8.4.0/twilio/base/deserialize.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/base/domain.py` & `twilio-8.4.0/twilio/base/domain.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/base/exceptions.py` & `twilio-8.4.0/twilio/base/exceptions.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/base/obsolete.py` & `twilio-8.4.0/twilio/base/obsolete.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/base/page.py` & `twilio-8.4.0/twilio/base/page.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/base/serialize.py` & `twilio-8.4.0/twilio/base/serialize.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/base/version.py` & `twilio-8.4.0/twilio/base/version.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/http/__init__.py` & `twilio-8.4.0/twilio/http/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/http/async_http_client.py` & `twilio-8.4.0/twilio/http/async_http_client.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/http/http_client.py` & `twilio-8.4.0/twilio/http/http_client.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/http/request.py` & `twilio-8.4.0/twilio/http/request.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/http/response.py` & `twilio-8.4.0/twilio/http/response.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/http/validation_client.py` & `twilio-8.4.0/twilio/http/validation_client.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/jwt/__init__.py` & `twilio-8.4.0/twilio/jwt/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/jwt/access_token/__init__.py` & `twilio-8.4.0/twilio/jwt/access_token/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/jwt/access_token/grants.py` & `twilio-8.4.0/twilio/jwt/access_token/grants.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/jwt/client/__init__.py` & `twilio-8.4.0/twilio/jwt/client/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/jwt/taskrouter/__init__.py` & `twilio-8.4.0/twilio/jwt/taskrouter/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/jwt/taskrouter/capabilities.py` & `twilio-8.4.0/twilio/jwt/taskrouter/capabilities.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/jwt/validation/__init__.py` & `twilio-8.4.0/twilio/jwt/validation/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/request_validator.py` & `twilio-8.4.0/twilio/request_validator.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/__init__.py` & `twilio-8.4.0/twilio/rest/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/accounts/AccountsBase.py` & `twilio-8.4.0/twilio/rest/accounts/AccountsBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/accounts/__init__.py` & `twilio-8.4.0/twilio/rest/accounts/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/accounts/v1/__init__.py` & `twilio-8.4.0/twilio/rest/accounts/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/accounts/v1/auth_token_promotion.py` & `twilio-8.4.0/twilio/rest/accounts/v1/auth_token_promotion.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/accounts/v1/credential/__init__.py` & `twilio-8.4.0/twilio/rest/accounts/v1/credential/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/accounts/v1/credential/aws.py` & `twilio-8.4.0/twilio/rest/accounts/v1/credential/aws.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/accounts/v1/credential/public_key.py` & `twilio-8.4.0/twilio/rest/accounts/v1/credential/public_key.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/accounts/v1/secondary_auth_token.py` & `twilio-8.4.0/twilio/rest/accounts/v1/secondary_auth_token.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/ApiBase.py` & `twilio-8.4.0/twilio/rest/api/ApiBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/__init__.py` & `twilio-8.4.0/twilio/rest/api/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/address/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/address/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/address/dependent_phone_number.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/address/dependent_phone_number.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/application.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/application.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/authorized_connect_app.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/authorized_connect_app.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/local.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/local.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/machine_to_machine.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/machine_to_machine.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/mobile.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/mobile.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/national.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/national.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/shared_cost.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/shared_cost.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/toll_free.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/toll_free.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/available_phone_number_country/voip.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/available_phone_number_country/voip.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/balance.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/balance.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/call/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/call/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/call/event.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/call/event.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/call/feedback.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/call/feedback.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/call/feedback_summary.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/call/feedback_summary.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/call/notification.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/call/notification.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/call/payment.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/call/payment.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/call/recording.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/call/recording.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/call/siprec.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/call/siprec.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/call/stream.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/call/stream.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/call/user_defined_message.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/call/user_defined_message.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/call/user_defined_message_subscription.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/call/user_defined_message_subscription.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/conference/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/conference/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/conference/participant.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/conference/participant.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/conference/recording.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/conference/recording.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/connect_app.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/connect_app.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/assigned_add_on/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/assigned_add_on/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/assigned_add_on/assigned_add_on_extension.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/assigned_add_on/assigned_add_on_extension.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/local.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/local.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/mobile.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/mobile.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/incoming_phone_number/toll_free.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/incoming_phone_number/toll_free.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/key.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/key.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/message/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/message/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/message/feedback.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/message/feedback.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/message/media.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/message/media.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/new_key.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/new_key.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/new_signing_key.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/new_signing_key.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/notification.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/notification.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/outgoing_caller_id.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/outgoing_caller_id.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/queue/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/queue/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/queue/member.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/queue/member.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/recording/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/recording/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/recording/add_on_result/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/recording/add_on_result/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/recording/add_on_result/payload.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/recording/add_on_result/payload.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/recording/transcription.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/recording/transcription.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/short_code.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/short_code.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/signing_key.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/signing_key.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/credential_list/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/credential_list/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/credential_list/credential.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/credential_list/credential.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/auth_calls_credential_list_mapping.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/auth_calls_credential_list_mapping.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/auth_calls_ip_access_control_list_mapping.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_calls/auth_calls_ip_access_control_list_mapping.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_registrations/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_registrations/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_registrations/auth_registrations_credential_list_mapping.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/auth_types/auth_type_registrations/auth_registrations_credential_list_mapping.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/credential_list_mapping.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/credential_list_mapping.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/domain/ip_access_control_list_mapping.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/domain/ip_access_control_list_mapping.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/ip_access_control_list/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/ip_access_control_list/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/sip/ip_access_control_list/ip_address.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/sip/ip_access_control_list/ip_address.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/token.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/token.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/transcription.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/transcription.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/usage/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/usage/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/__init__.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/all_time.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/all_time.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/daily.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/daily.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/last_month.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/last_month.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/monthly.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/monthly.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/this_month.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/this_month.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/today.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/today.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/yearly.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/yearly.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/usage/record/yesterday.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/usage/record/yesterday.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/usage/trigger.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/usage/trigger.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/api/v2010/account/validation_request.py` & `twilio-8.4.0/twilio/rest/api/v2010/account/validation_request.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/AutopilotBase.py` & `twilio-8.4.0/twilio/rest/autopilot/AutopilotBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/__init__.py` & `twilio-8.4.0/twilio/rest/autopilot/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/__init__.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/__init__.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/defaults.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/defaults.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/dialogue.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/dialogue.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/field_type/__init__.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/field_type/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/field_type/field_value.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/field_type/field_value.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/model_build.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/model_build.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/query.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/query.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/style_sheet.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/style_sheet.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/task/__init__.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/task/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/task/field.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/task/field.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/task/sample.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/task/sample.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/task/task_actions.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/task/task_actions.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/task/task_statistics.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/task/task_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/assistant/webhook.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/assistant/webhook.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/autopilot/v1/restore_assistant.py` & `twilio-8.4.0/twilio/rest/autopilot/v1/restore_assistant.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/bulkexports/BulkexportsBase.py` & `twilio-8.4.0/twilio/rest/bulkexports/BulkexportsBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/bulkexports/__init__.py` & `twilio-8.4.0/twilio/rest/bulkexports/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/bulkexports/v1/__init__.py` & `twilio-8.4.0/twilio/rest/bulkexports/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/bulkexports/v1/export/__init__.py` & `twilio-8.4.0/twilio/rest/bulkexports/v1/export/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/bulkexports/v1/export/day.py` & `twilio-8.4.0/twilio/rest/bulkexports/v1/export/day.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/bulkexports/v1/export/export_custom_job.py` & `twilio-8.4.0/twilio/rest/bulkexports/v1/export/export_custom_job.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/bulkexports/v1/export/job.py` & `twilio-8.4.0/twilio/rest/bulkexports/v1/export/job.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/bulkexports/v1/export_configuration.py` & `twilio-8.4.0/twilio/rest/bulkexports/v1/export_configuration.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/ChatBase.py` & `twilio-8.4.0/twilio/rest/chat/ChatBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/__init__.py` & `twilio-8.4.0/twilio/rest/chat/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v1/__init__.py` & `twilio-8.4.0/twilio/rest/chat/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v1/credential.py` & `twilio-8.4.0/twilio/rest/chat/v1/credential.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v1/service/__init__.py` & `twilio-8.4.0/twilio/rest/chat/v1/service/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v1/service/channel/__init__.py` & `twilio-8.4.0/twilio/rest/chat/v1/service/channel/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v1/service/channel/invite.py` & `twilio-8.4.0/twilio/rest/chat/v1/service/channel/invite.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v1/service/channel/member.py` & `twilio-8.4.0/twilio/rest/chat/v1/service/channel/member.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v1/service/channel/message.py` & `twilio-8.4.0/twilio/rest/chat/v1/service/channel/message.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v1/service/role.py` & `twilio-8.4.0/twilio/rest/chat/v1/service/role.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v1/service/user/__init__.py` & `twilio-8.4.0/twilio/rest/chat/v1/service/user/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v1/service/user/user_channel.py` & `twilio-8.4.0/twilio/rest/chat/v1/service/user/user_channel.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/__init__.py` & `twilio-8.4.0/twilio/rest/chat/v2/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/credential.py` & `twilio-8.4.0/twilio/rest/chat/v2/credential.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/service/__init__.py` & `twilio-8.4.0/twilio/rest/chat/v2/service/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/service/binding.py` & `twilio-8.4.0/twilio/rest/chat/v2/service/binding.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/service/channel/__init__.py` & `twilio-8.4.0/twilio/rest/chat/v2/service/channel/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/service/channel/invite.py` & `twilio-8.4.0/twilio/rest/chat/v2/service/channel/invite.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/service/channel/member.py` & `twilio-8.4.0/twilio/rest/chat/v2/service/channel/member.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/service/channel/message.py` & `twilio-8.4.0/twilio/rest/chat/v2/service/channel/message.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/service/channel/webhook.py` & `twilio-8.4.0/twilio/rest/chat/v2/service/channel/webhook.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/service/role.py` & `twilio-8.4.0/twilio/rest/chat/v2/service/role.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/service/user/__init__.py` & `twilio-8.4.0/twilio/rest/chat/v2/service/user/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/service/user/user_binding.py` & `twilio-8.4.0/twilio/rest/chat/v2/service/user/user_binding.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v2/service/user/user_channel.py` & `twilio-8.4.0/twilio/rest/chat/v2/service/user/user_channel.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v3/__init__.py` & `twilio-8.4.0/twilio/rest/chat/v3/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/chat/v3/channel.py` & `twilio-8.4.0/twilio/rest/chat/v3/channel.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/content/ContentBase.py` & `twilio-8.4.0/twilio/rest/content/ContentBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/content/__init__.py` & `twilio-8.4.0/twilio/rest/content/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/content/v1/__init__.py` & `twilio-8.4.0/twilio/rest/content/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/content/v1/content/__init__.py` & `twilio-8.4.0/twilio/rest/content/v1/content/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/content/v1/content/approval_fetch.py` & `twilio-8.4.0/twilio/rest/content/v1/content/approval_fetch.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/content/v1/content_and_approvals.py` & `twilio-8.4.0/twilio/rest/content/v1/content_and_approvals.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/content/v1/legacy_content.py` & `twilio-8.4.0/twilio/rest/content/v1/legacy_content.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/ConversationsBase.py` & `twilio-8.4.0/twilio/rest/conversations/ConversationsBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/__init__.py` & `twilio-8.4.0/twilio/rest/conversations/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/__init__.py` & `twilio-8.4.0/twilio/rest/conversations/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/address_configuration.py` & `twilio-8.4.0/twilio/rest/conversations/v1/address_configuration.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/configuration/__init__.py` & `twilio-8.4.0/twilio/rest/conversations/v1/configuration/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/configuration/webhook.py` & `twilio-8.4.0/twilio/rest/conversations/v1/configuration/webhook.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/conversation/__init__.py` & `twilio-8.4.0/twilio/rest/conversations/v1/conversation/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/conversation/message/__init__.py` & `twilio-8.4.0/twilio/rest/conversations/v1/conversation/message/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/conversation/message/delivery_receipt.py` & `twilio-8.4.0/twilio/rest/conversations/v1/conversation/message/delivery_receipt.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/conversation/participant.py` & `twilio-8.4.0/twilio/rest/conversations/v1/conversation/participant.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/conversation/webhook.py` & `twilio-8.4.0/twilio/rest/conversations/v1/conversation/webhook.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/credential.py` & `twilio-8.4.0/twilio/rest/conversations/v1/credential.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/participant_conversation.py` & `twilio-8.4.0/twilio/rest/conversations/v1/participant_conversation.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/role.py` & `twilio-8.4.0/twilio/rest/conversations/v1/role.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/__init__.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/binding.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/binding.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/configuration/__init__.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/configuration/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/configuration/notification.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/configuration/notification.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/configuration/webhook.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/configuration/webhook.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/conversation/__init__.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/conversation/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/conversation/message/__init__.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/conversation/message/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/conversation/message/delivery_receipt.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/conversation/message/delivery_receipt.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/conversation/participant.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/conversation/participant.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/conversation/webhook.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/conversation/webhook.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/participant_conversation.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/participant_conversation.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/role.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/role.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/user/__init__.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/user/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/service/user/user_conversation.py` & `twilio-8.4.0/twilio/rest/conversations/v1/service/user/user_conversation.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/user/__init__.py` & `twilio-8.4.0/twilio/rest/conversations/v1/user/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/conversations/v1/user/user_conversation.py` & `twilio-8.4.0/twilio/rest/conversations/v1/user/user_conversation.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/events/EventsBase.py` & `twilio-8.4.0/twilio/rest/events/EventsBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/events/__init__.py` & `twilio-8.4.0/twilio/rest/events/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/events/v1/__init__.py` & `twilio-8.4.0/twilio/rest/events/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/events/v1/event_type.py` & `twilio-8.4.0/twilio/rest/events/v1/event_type.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/events/v1/schema/__init__.py` & `twilio-8.4.0/twilio/rest/events/v1/schema/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/events/v1/schema/schema_version.py` & `twilio-8.4.0/twilio/rest/events/v1/schema/schema_version.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/events/v1/sink/__init__.py` & `twilio-8.4.0/twilio/rest/events/v1/sink/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/events/v1/sink/sink_test.py` & `twilio-8.4.0/twilio/rest/events/v1/sink/sink_test.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/events/v1/sink/sink_validate.py` & `twilio-8.4.0/twilio/rest/events/v1/sink/sink_validate.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/events/v1/subscription/__init__.py` & `twilio-8.4.0/twilio/rest/events/v1/subscription/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/events/v1/subscription/subscribed_event.py` & `twilio-8.4.0/twilio/rest/events/v1/subscription/subscribed_event.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/FlexApiBase.py` & `twilio-8.4.0/twilio/rest/flex_api/FlexApiBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/__init__.py` & `twilio-8.4.0/twilio/rest/flex_api/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/__init__.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/assessments.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/assessments.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/channel.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/channel.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/configuration.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/configuration.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/flex_flow.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/flex_flow.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/insights_assessments_comment.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/insights_assessments_comment.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/insights_conversations.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/insights_conversations.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/insights_questionnaires.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/insights_questionnaires.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/insights_questionnaires_category.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/insights_questionnaires_category.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/insights_questionnaires_question.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/insights_questionnaires_question.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/insights_segments.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/insights_segments.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/insights_session.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/insights_session.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/insights_settings_answer_sets.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/insights_settings_answer_sets.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/insights_settings_comment.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/insights_settings_comment.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/insights_user_roles.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/insights_user_roles.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/interaction/__init__.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/interaction/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/interaction/interaction_channel/__init__.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/interaction/interaction_channel/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/interaction/interaction_channel/interaction_channel_invite.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/interaction/interaction_channel/interaction_channel_invite.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/interaction/interaction_channel/interaction_channel_participant.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/interaction/interaction_channel/interaction_channel_participant.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v1/web_channel.py` & `twilio-8.4.0/twilio/rest/flex_api/v1/web_channel.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v2/__init__.py` & `twilio-8.4.0/twilio/rest/flex_api/v2/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/flex_api/v2/web_channels.py` & `twilio-8.4.0/twilio/rest/flex_api/v2/web_channels.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/frontline_api/FrontlineApiBase.py` & `twilio-8.4.0/twilio/rest/frontline_api/FrontlineApiBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/frontline_api/v1/__init__.py` & `twilio-8.4.0/twilio/rest/frontline_api/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/frontline_api/v1/user.py` & `twilio-8.4.0/twilio/rest/frontline_api/v1/user.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/insights/InsightsBase.py` & `twilio-8.4.0/twilio/rest/insights/InsightsBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/insights/__init__.py` & `twilio-8.4.0/twilio/rest/insights/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/insights/v1/__init__.py` & `twilio-8.4.0/twilio/rest/insights/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/insights/v1/call/__init__.py` & `twilio-8.4.0/twilio/rest/insights/v1/call/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/insights/v1/call/annotation.py` & `twilio-8.4.0/twilio/rest/insights/v1/call/annotation.py`

 * *Files 7% similar despite different names*

```diff
@@ -36,19 +36,19 @@
         NUMBER_REACHABILITY = "number_reachability"
 
     """
     :ivar call_sid: The unique SID identifier of the Call.
     :ivar account_sid: The unique SID identifier of the Account.
     :ivar answered_by: 
     :ivar connectivity_issue: 
-    :ivar quality_issues: Specify if the call had any subjective quality issues. Possible values, one or more of:  no_quality_issue, low_volume, choppy_robotic, echo, dtmf, latency, owa, static_noise. Use comma separated values to indicate multiple quality issues for the same call
-    :ivar spam: Specify if the call was a spam call. Use this to provide feedback on whether calls placed from your account were marked as spam, or if inbound calls received by your account were unwanted spam. Is of type Boolean: true, false. Use true if the call was a spam call.
-    :ivar call_score: Specify the call score. This is of type integer. Use a range of 1-5 to indicate the call experience score, with the following mapping as a reference for rating the call [5: Excellent, 4: Good, 3 : Fair, 2 : Poor, 1: Bad].
-    :ivar comment: Specify any comments pertaining to the call. This of type string with a max limit of 100 characters. Twilio does not treat this field as PII, so don’t put any PII in here.
-    :ivar incident: Associate this call with an incident or support ticket. This is of type string with a max limit of 100 characters. Twilio does not treat this field as PII, so don’t put any PII in here.
+    :ivar quality_issues: Specifies if the call had any subjective quality issues. Possible values are one or more of `no_quality_issue`, `low_volume`, `choppy_robotic`, `echo`, `dtmf`, `latency`, `owa`, or `static_noise`.
+    :ivar spam: Specifies if the call was a spam call. Use this to provide feedback on whether calls placed from your account were marked as spam, or if inbound calls received by your account were unwanted spam. Is of type Boolean: true, false. Use true if the call was a spam call.
+    :ivar call_score: Specifies the Call Score, if available. This is of type integer. Use a range of 1-5 to indicate the call experience score, with the following mapping as a reference for rating the call [5: Excellent, 4: Good, 3 : Fair, 2 : Poor, 1: Bad].
+    :ivar comment: Specifies any comments pertaining to the call. Twilio does not treat this field as PII, so no PII should be included in comments.
+    :ivar incident: Incident or support ticket associated with this call. The `incident` property is of type string with a maximum character limit of 100. Twilio does not treat this field as PII, so no PII should be included in `incident`.
     :ivar url: The URL of this resource.
     """
 
     def __init__(self, version: Version, payload: Dict[str, Any], call_sid: str):
         super().__init__(version)
 
         self.call_sid: Optional[str] = payload.get("call_sid")
@@ -117,19 +117,19 @@
         incident: Union[str, object] = values.unset,
     ) -> "AnnotationInstance":
         """
         Update the AnnotationInstance
 
         :param answered_by:
         :param connectivity_issue:
-        :param quality_issues: Specify if the call had any subjective quality issues. Possible values, one or more of:  no_quality_issue, low_volume, choppy_robotic, echo, dtmf, latency, owa, static_noise. Use comma separated values to indicate multiple quality issues for the same call
-        :param spam: Specify if the call was a spam call. Use this to provide feedback on whether calls placed from your account were marked as spam, or if inbound calls received by your account were unwanted spam. Is of type Boolean: true, false. Use true if the call was a spam call.
+        :param quality_issues: Specify if the call had any subjective quality issues. Possible values, one or more of `no_quality_issue`, `low_volume`, `choppy_robotic`, `echo`, `dtmf`, `latency`, `owa`, `static_noise`. Use comma separated values to indicate multiple quality issues for the same call.
+        :param spam: A boolean flag to indicate if the call was a spam call. Use this to provide feedback on whether calls placed from your account were marked as spam, or if inbound calls received by your account were unwanted spam. Use `true` if the call was a spam call.
         :param call_score: Specify the call score. This is of type integer. Use a range of 1-5 to indicate the call experience score, with the following mapping as a reference for rating the call [5: Excellent, 4: Good, 3 : Fair, 2 : Poor, 1: Bad].
-        :param comment: Specify any comments pertaining to the call. This of type string with a max limit of 100 characters. Twilio does not treat this field as PII, so don’t put any PII in here.
-        :param incident: Associate this call with an incident or support ticket. This is of type string with a max limit of 100 characters. Twilio does not treat this field as PII, so don’t put any PII in here.
+        :param comment: Specify any comments pertaining to the call. `comment` has a maximum character limit of 100. Twilio does not treat this field as PII, so no PII should be included in the `comment`.
+        :param incident: Associate this call with an incident or support ticket. The `incident` parameter is of type string with a maximum character limit of 100. Twilio does not treat this field as PII, so no PII should be included in `incident`.
 
         :returns: The updated AnnotationInstance
         """
         return self._proxy.update(
             answered_by=answered_by,
             connectivity_issue=connectivity_issue,
             quality_issues=quality_issues,
@@ -152,19 +152,19 @@
         incident: Union[str, object] = values.unset,
     ) -> "AnnotationInstance":
         """
         Asynchronous coroutine to update the AnnotationInstance
 
         :param answered_by:
         :param connectivity_issue:
-        :param quality_issues: Specify if the call had any subjective quality issues. Possible values, one or more of:  no_quality_issue, low_volume, choppy_robotic, echo, dtmf, latency, owa, static_noise. Use comma separated values to indicate multiple quality issues for the same call
-        :param spam: Specify if the call was a spam call. Use this to provide feedback on whether calls placed from your account were marked as spam, or if inbound calls received by your account were unwanted spam. Is of type Boolean: true, false. Use true if the call was a spam call.
+        :param quality_issues: Specify if the call had any subjective quality issues. Possible values, one or more of `no_quality_issue`, `low_volume`, `choppy_robotic`, `echo`, `dtmf`, `latency`, `owa`, `static_noise`. Use comma separated values to indicate multiple quality issues for the same call.
+        :param spam: A boolean flag to indicate if the call was a spam call. Use this to provide feedback on whether calls placed from your account were marked as spam, or if inbound calls received by your account were unwanted spam. Use `true` if the call was a spam call.
         :param call_score: Specify the call score. This is of type integer. Use a range of 1-5 to indicate the call experience score, with the following mapping as a reference for rating the call [5: Excellent, 4: Good, 3 : Fair, 2 : Poor, 1: Bad].
-        :param comment: Specify any comments pertaining to the call. This of type string with a max limit of 100 characters. Twilio does not treat this field as PII, so don’t put any PII in here.
-        :param incident: Associate this call with an incident or support ticket. This is of type string with a max limit of 100 characters. Twilio does not treat this field as PII, so don’t put any PII in here.
+        :param comment: Specify any comments pertaining to the call. `comment` has a maximum character limit of 100. Twilio does not treat this field as PII, so no PII should be included in the `comment`.
+        :param incident: Associate this call with an incident or support ticket. The `incident` parameter is of type string with a maximum character limit of 100. Twilio does not treat this field as PII, so no PII should be included in `incident`.
 
         :returns: The updated AnnotationInstance
         """
         return await self._proxy.update_async(
             answered_by=answered_by,
             connectivity_issue=connectivity_issue,
             quality_issues=quality_issues,
@@ -251,19 +251,19 @@
         incident: Union[str, object] = values.unset,
     ) -> AnnotationInstance:
         """
         Update the AnnotationInstance
 
         :param answered_by:
         :param connectivity_issue:
-        :param quality_issues: Specify if the call had any subjective quality issues. Possible values, one or more of:  no_quality_issue, low_volume, choppy_robotic, echo, dtmf, latency, owa, static_noise. Use comma separated values to indicate multiple quality issues for the same call
-        :param spam: Specify if the call was a spam call. Use this to provide feedback on whether calls placed from your account were marked as spam, or if inbound calls received by your account were unwanted spam. Is of type Boolean: true, false. Use true if the call was a spam call.
+        :param quality_issues: Specify if the call had any subjective quality issues. Possible values, one or more of `no_quality_issue`, `low_volume`, `choppy_robotic`, `echo`, `dtmf`, `latency`, `owa`, `static_noise`. Use comma separated values to indicate multiple quality issues for the same call.
+        :param spam: A boolean flag to indicate if the call was a spam call. Use this to provide feedback on whether calls placed from your account were marked as spam, or if inbound calls received by your account were unwanted spam. Use `true` if the call was a spam call.
         :param call_score: Specify the call score. This is of type integer. Use a range of 1-5 to indicate the call experience score, with the following mapping as a reference for rating the call [5: Excellent, 4: Good, 3 : Fair, 2 : Poor, 1: Bad].
-        :param comment: Specify any comments pertaining to the call. This of type string with a max limit of 100 characters. Twilio does not treat this field as PII, so don’t put any PII in here.
-        :param incident: Associate this call with an incident or support ticket. This is of type string with a max limit of 100 characters. Twilio does not treat this field as PII, so don’t put any PII in here.
+        :param comment: Specify any comments pertaining to the call. `comment` has a maximum character limit of 100. Twilio does not treat this field as PII, so no PII should be included in the `comment`.
+        :param incident: Associate this call with an incident or support ticket. The `incident` parameter is of type string with a maximum character limit of 100. Twilio does not treat this field as PII, so no PII should be included in `incident`.
 
         :returns: The updated AnnotationInstance
         """
         data = values.of(
             {
                 "AnsweredBy": answered_by,
                 "ConnectivityIssue": connectivity_issue,
@@ -298,19 +298,19 @@
         incident: Union[str, object] = values.unset,
     ) -> AnnotationInstance:
         """
         Asynchronous coroutine to update the AnnotationInstance
 
         :param answered_by:
         :param connectivity_issue:
-        :param quality_issues: Specify if the call had any subjective quality issues. Possible values, one or more of:  no_quality_issue, low_volume, choppy_robotic, echo, dtmf, latency, owa, static_noise. Use comma separated values to indicate multiple quality issues for the same call
-        :param spam: Specify if the call was a spam call. Use this to provide feedback on whether calls placed from your account were marked as spam, or if inbound calls received by your account were unwanted spam. Is of type Boolean: true, false. Use true if the call was a spam call.
+        :param quality_issues: Specify if the call had any subjective quality issues. Possible values, one or more of `no_quality_issue`, `low_volume`, `choppy_robotic`, `echo`, `dtmf`, `latency`, `owa`, `static_noise`. Use comma separated values to indicate multiple quality issues for the same call.
+        :param spam: A boolean flag to indicate if the call was a spam call. Use this to provide feedback on whether calls placed from your account were marked as spam, or if inbound calls received by your account were unwanted spam. Use `true` if the call was a spam call.
         :param call_score: Specify the call score. This is of type integer. Use a range of 1-5 to indicate the call experience score, with the following mapping as a reference for rating the call [5: Excellent, 4: Good, 3 : Fair, 2 : Poor, 1: Bad].
-        :param comment: Specify any comments pertaining to the call. This of type string with a max limit of 100 characters. Twilio does not treat this field as PII, so don’t put any PII in here.
-        :param incident: Associate this call with an incident or support ticket. This is of type string with a max limit of 100 characters. Twilio does not treat this field as PII, so don’t put any PII in here.
+        :param comment: Specify any comments pertaining to the call. `comment` has a maximum character limit of 100. Twilio does not treat this field as PII, so no PII should be included in the `comment`.
+        :param incident: Associate this call with an incident or support ticket. The `incident` parameter is of type string with a maximum character limit of 100. Twilio does not treat this field as PII, so no PII should be included in `incident`.
 
         :returns: The updated AnnotationInstance
         """
         data = values.of(
             {
                 "AnsweredBy": answered_by,
                 "ConnectivityIssue": connectivity_issue,
```

#### encoding

```diff
@@ -1 +1 @@
-utf-8
+us-ascii
```

### Comparing `twilio-8.3.0/twilio/rest/insights/v1/call/call_summary.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/task/task_actions.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,308 +1,301 @@
 r"""
     This code was generated by
    ___ _ _ _ _ _    _ ____    ____ ____ _    ____ ____ _  _ ____ ____ ____ ___ __   __
     |  | | | | |    | |  | __ |  | |__| | __ | __ |___ |\ | |___ |__/ |__|  | |  | |__/
     |  |_|_| | |___ | |__|    |__| |  | |    |__] |___ | \| |___ |  \ |  |  | |__| |  \
 
-    Twilio - Insights
+    Twilio - Preview
     This is the public Twilio REST API.
 
     NOTE: This class is auto generated by OpenAPI Generator.
     https://openapi-generator.tech
     Do not edit the class manually.
 """
 
 
-from datetime import datetime
-from typing import Any, Dict, List, Optional, Union
-from twilio.base import deserialize, values
+from typing import Any, Dict, Optional, Union
+from twilio.base import serialize, values
 from twilio.base.instance_context import InstanceContext
 from twilio.base.instance_resource import InstanceResource
 from twilio.base.list_resource import ListResource
 from twilio.base.version import Version
 
 
-class CallSummaryInstance(InstanceResource):
-    class AnsweredBy(object):
-        UNKNOWN = "unknown"
-        MACHINE_START = "machine_start"
-        MACHINE_END_BEEP = "machine_end_beep"
-        MACHINE_END_SILENCE = "machine_end_silence"
-        MACHINE_END_OTHER = "machine_end_other"
-        HUMAN = "human"
-        FAX = "fax"
-
-    class CallState(object):
-        RINGING = "ringing"
-        COMPLETED = "completed"
-        BUSY = "busy"
-        FAIL = "fail"
-        NOANSWER = "noanswer"
-        CANCELED = "canceled"
-        ANSWERED = "answered"
-        UNDIALED = "undialed"
-
-    class CallType(object):
-        CARRIER = "carrier"
-        SIP = "sip"
-        TRUNKING = "trunking"
-        CLIENT = "client"
-
-    class ProcessingState(object):
-        COMPLETE = "complete"
-        PARTIAL = "partial"
+class TaskActionsInstance(InstanceResource):
 
     """
-    :ivar account_sid: 
-    :ivar call_sid: 
-    :ivar call_type: 
-    :ivar call_state: 
-    :ivar answered_by: 
-    :ivar processing_state: 
-    :ivar created_time: 
-    :ivar start_time: 
-    :ivar end_time: 
-    :ivar duration: 
-    :ivar connect_duration: 
-    :ivar _from: 
-    :ivar to: 
-    :ivar carrier_edge: 
-    :ivar client_edge: 
-    :ivar sdk_edge: 
-    :ivar sip_edge: 
-    :ivar tags: 
-    :ivar url: 
-    :ivar attributes: 
-    :ivar properties: 
-    :ivar trust: 
-    :ivar annotation: 
+    :ivar account_sid: The unique ID of the Account that created this Field.
+    :ivar assistant_sid: The unique ID of the parent Assistant.
+    :ivar task_sid: The unique ID of the Task.
+    :ivar url:
+    :ivar data:
     """
 
-    def __init__(self, version: Version, payload: Dict[str, Any], call_sid: str):
+    def __init__(
+        self,
+        version: Version,
+        payload: Dict[str, Any],
+        assistant_sid: str,
+        task_sid: str,
+    ):
         super().__init__(version)
 
         self.account_sid: Optional[str] = payload.get("account_sid")
-        self.call_sid: Optional[str] = payload.get("call_sid")
-        self.call_type: Optional["CallSummaryInstance.CallType"] = payload.get(
-            "call_type"
-        )
-        self.call_state: Optional["CallSummaryInstance.CallState"] = payload.get(
-            "call_state"
-        )
-        self.answered_by: Optional["CallSummaryInstance.AnsweredBy"] = payload.get(
-            "answered_by"
-        )
-        self.processing_state: Optional[
-            "CallSummaryInstance.ProcessingState"
-        ] = payload.get("processing_state")
-        self.created_time: Optional[datetime] = deserialize.iso8601_datetime(
-            payload.get("created_time")
-        )
-        self.start_time: Optional[datetime] = deserialize.iso8601_datetime(
-            payload.get("start_time")
-        )
-        self.end_time: Optional[datetime] = deserialize.iso8601_datetime(
-            payload.get("end_time")
-        )
-        self.duration: Optional[int] = deserialize.integer(payload.get("duration"))
-        self.connect_duration: Optional[int] = deserialize.integer(
-            payload.get("connect_duration")
-        )
-        self._from: Optional[Dict[str, object]] = payload.get("from")
-        self.to: Optional[Dict[str, object]] = payload.get("to")
-        self.carrier_edge: Optional[Dict[str, object]] = payload.get("carrier_edge")
-        self.client_edge: Optional[Dict[str, object]] = payload.get("client_edge")
-        self.sdk_edge: Optional[Dict[str, object]] = payload.get("sdk_edge")
-        self.sip_edge: Optional[Dict[str, object]] = payload.get("sip_edge")
-        self.tags: Optional[List[str]] = payload.get("tags")
+        self.assistant_sid: Optional[str] = payload.get("assistant_sid")
+        self.task_sid: Optional[str] = payload.get("task_sid")
         self.url: Optional[str] = payload.get("url")
-        self.attributes: Optional[Dict[str, object]] = payload.get("attributes")
-        self.properties: Optional[Dict[str, object]] = payload.get("properties")
-        self.trust: Optional[Dict[str, object]] = payload.get("trust")
-        self.annotation: Optional[Dict[str, object]] = payload.get("annotation")
+        self.data: Optional[Dict[str, object]] = payload.get("data")
 
         self._solution = {
-            "call_sid": call_sid,
+            "assistant_sid": assistant_sid,
+            "task_sid": task_sid,
         }
-        self._context: Optional[CallSummaryContext] = None
+        self._context: Optional[TaskActionsContext] = None
 
     @property
-    def _proxy(self) -> "CallSummaryContext":
+    def _proxy(self) -> "TaskActionsContext":
         """
         Generate an instance context for the instance, the context is capable of
         performing various actions. All instance actions are proxied to the context
 
-        :returns: CallSummaryContext for this CallSummaryInstance
+        :returns: TaskActionsContext for this TaskActionsInstance
         """
         if self._context is None:
-            self._context = CallSummaryContext(
+            self._context = TaskActionsContext(
                 self._version,
-                call_sid=self._solution["call_sid"],
+                assistant_sid=self._solution["assistant_sid"],
+                task_sid=self._solution["task_sid"],
             )
         return self._context
 
-    def fetch(
-        self,
-        processing_state: Union[
-            "CallSummaryInstance.ProcessingState", object
-        ] = values.unset,
-    ) -> "CallSummaryInstance":
+    def fetch(self) -> "TaskActionsInstance":
+        """
+        Fetch the TaskActionsInstance
+
+
+        :returns: The fetched TaskActionsInstance
+        """
+        return self._proxy.fetch()
+
+    async def fetch_async(self) -> "TaskActionsInstance":
+        """
+        Asynchronous coroutine to fetch the TaskActionsInstance
+
+
+        :returns: The fetched TaskActionsInstance
+        """
+        return await self._proxy.fetch_async()
+
+    def update(
+        self, actions: Union[object, object] = values.unset
+    ) -> "TaskActionsInstance":
         """
-        Fetch the CallSummaryInstance
+        Update the TaskActionsInstance
 
-        :param processing_state:
+        :param actions: The JSON actions that instruct the Assistant how to perform this task.
 
-        :returns: The fetched CallSummaryInstance
+        :returns: The updated TaskActionsInstance
         """
-        return self._proxy.fetch(
-            processing_state=processing_state,
+        return self._proxy.update(
+            actions=actions,
         )
 
-    async def fetch_async(
-        self,
-        processing_state: Union[
-            "CallSummaryInstance.ProcessingState", object
-        ] = values.unset,
-    ) -> "CallSummaryInstance":
+    async def update_async(
+        self, actions: Union[object, object] = values.unset
+    ) -> "TaskActionsInstance":
         """
-        Asynchronous coroutine to fetch the CallSummaryInstance
+        Asynchronous coroutine to update the TaskActionsInstance
 
-        :param processing_state:
+        :param actions: The JSON actions that instruct the Assistant how to perform this task.
 
-        :returns: The fetched CallSummaryInstance
+        :returns: The updated TaskActionsInstance
         """
-        return await self._proxy.fetch_async(
-            processing_state=processing_state,
+        return await self._proxy.update_async(
+            actions=actions,
         )
 
     def __repr__(self) -> str:
         """
         Provide a friendly representation
 
         :returns: Machine friendly representation
         """
         context = " ".join("{}={}".format(k, v) for k, v in self._solution.items())
-        return "<Twilio.Insights.V1.CallSummaryInstance {}>".format(context)
+        return "<Twilio.Preview.Understand.TaskActionsInstance {}>".format(context)
 
 
-class CallSummaryContext(InstanceContext):
-    def __init__(self, version: Version, call_sid: str):
+class TaskActionsContext(InstanceContext):
+    def __init__(self, version: Version, assistant_sid: str, task_sid: str):
         """
-        Initialize the CallSummaryContext
+        Initialize the TaskActionsContext
 
         :param version: Version that contains the resource
-        :param call_sid:
+        :param assistant_sid: The unique ID of the parent Assistant.
+        :param task_sid: The unique ID of the Task.
         """
         super().__init__(version)
 
         # Path Solution
         self._solution = {
-            "call_sid": call_sid,
+            "assistant_sid": assistant_sid,
+            "task_sid": task_sid,
         }
-        self._uri = "/Voice/{call_sid}/Summary".format(**self._solution)
+        self._uri = "/Assistants/{assistant_sid}/Tasks/{task_sid}/Actions".format(
+            **self._solution
+        )
 
-    def fetch(
-        self,
-        processing_state: Union[
-            "CallSummaryInstance.ProcessingState", object
-        ] = values.unset,
-    ) -> CallSummaryInstance:
+    def fetch(self) -> TaskActionsInstance:
+        """
+        Fetch the TaskActionsInstance
+
+
+        :returns: The fetched TaskActionsInstance
         """
-        Fetch the CallSummaryInstance
 
-        :param processing_state:
+        payload = self._version.fetch(
+            method="GET",
+            uri=self._uri,
+        )
+
+        return TaskActionsInstance(
+            self._version,
+            payload,
+            assistant_sid=self._solution["assistant_sid"],
+            task_sid=self._solution["task_sid"],
+        )
 
-        :returns: The fetched CallSummaryInstance
+    async def fetch_async(self) -> TaskActionsInstance:
         """
+        Asynchronous coroutine to fetch the TaskActionsInstance
 
+
+        :returns: The fetched TaskActionsInstance
+        """
+
+        payload = await self._version.fetch_async(
+            method="GET",
+            uri=self._uri,
+        )
+
+        return TaskActionsInstance(
+            self._version,
+            payload,
+            assistant_sid=self._solution["assistant_sid"],
+            task_sid=self._solution["task_sid"],
+        )
+
+    def update(
+        self, actions: Union[object, object] = values.unset
+    ) -> TaskActionsInstance:
+        """
+        Update the TaskActionsInstance
+
+        :param actions: The JSON actions that instruct the Assistant how to perform this task.
+
+        :returns: The updated TaskActionsInstance
+        """
         data = values.of(
             {
-                "ProcessingState": processing_state,
+                "Actions": serialize.object(actions),
             }
         )
 
-        payload = self._version.fetch(method="GET", uri=self._uri, params=data)
+        payload = self._version.update(
+            method="POST",
+            uri=self._uri,
+            data=data,
+        )
 
-        return CallSummaryInstance(
+        return TaskActionsInstance(
             self._version,
             payload,
-            call_sid=self._solution["call_sid"],
+            assistant_sid=self._solution["assistant_sid"],
+            task_sid=self._solution["task_sid"],
         )
 
-    async def fetch_async(
-        self,
-        processing_state: Union[
-            "CallSummaryInstance.ProcessingState", object
-        ] = values.unset,
-    ) -> CallSummaryInstance:
+    async def update_async(
+        self, actions: Union[object, object] = values.unset
+    ) -> TaskActionsInstance:
         """
-        Asynchronous coroutine to fetch the CallSummaryInstance
+        Asynchronous coroutine to update the TaskActionsInstance
 
-        :param processing_state:
+        :param actions: The JSON actions that instruct the Assistant how to perform this task.
 
-        :returns: The fetched CallSummaryInstance
+        :returns: The updated TaskActionsInstance
         """
-
         data = values.of(
             {
-                "ProcessingState": processing_state,
+                "Actions": serialize.object(actions),
             }
         )
 
-        payload = await self._version.fetch_async(
-            method="GET", uri=self._uri, params=data
+        payload = await self._version.update_async(
+            method="POST",
+            uri=self._uri,
+            data=data,
         )
 
-        return CallSummaryInstance(
+        return TaskActionsInstance(
             self._version,
             payload,
-            call_sid=self._solution["call_sid"],
+            assistant_sid=self._solution["assistant_sid"],
+            task_sid=self._solution["task_sid"],
         )
 
     def __repr__(self) -> str:
         """
         Provide a friendly representation
 
         :returns: Machine friendly representation
         """
         context = " ".join("{}={}".format(k, v) for k, v in self._solution.items())
-        return "<Twilio.Insights.V1.CallSummaryContext {}>".format(context)
+        return "<Twilio.Preview.Understand.TaskActionsContext {}>".format(context)
 
 
-class CallSummaryList(ListResource):
-    def __init__(self, version: Version, call_sid: str):
+class TaskActionsList(ListResource):
+    def __init__(self, version: Version, assistant_sid: str, task_sid: str):
         """
-        Initialize the CallSummaryList
+        Initialize the TaskActionsList
 
         :param version: Version that contains the resource
-        :param call_sid:
+        :param assistant_sid: The unique ID of the parent Assistant.
+        :param task_sid: The unique ID of the Task.
 
         """
         super().__init__(version)
 
         # Path Solution
         self._solution = {
-            "call_sid": call_sid,
+            "assistant_sid": assistant_sid,
+            "task_sid": task_sid,
         }
 
-    def get(self) -> CallSummaryContext:
+    def get(self) -> TaskActionsContext:
         """
-        Constructs a CallSummaryContext
+        Constructs a TaskActionsContext
 
         """
-        return CallSummaryContext(self._version, call_sid=self._solution["call_sid"])
+        return TaskActionsContext(
+            self._version,
+            assistant_sid=self._solution["assistant_sid"],
+            task_sid=self._solution["task_sid"],
+        )
 
-    def __call__(self) -> CallSummaryContext:
+    def __call__(self) -> TaskActionsContext:
         """
-        Constructs a CallSummaryContext
+        Constructs a TaskActionsContext
 
         """
-        return CallSummaryContext(self._version, call_sid=self._solution["call_sid"])
+        return TaskActionsContext(
+            self._version,
+            assistant_sid=self._solution["assistant_sid"],
+            task_sid=self._solution["task_sid"],
+        )
 
     def __repr__(self) -> str:
         """
         Provide a friendly representation
 
         :returns: Machine friendly representation
         """
-        return "<Twilio.Insights.V1.CallSummaryList>"
+        return "<Twilio.Preview.Understand.TaskActionsList>"
```

### Comparing `twilio-8.3.0/twilio/rest/insights/v1/call/event.py` & `twilio-8.4.0/twilio/rest/insights/v1/call/event.py`

 * *Files 6% similar despite different names*

```diff
@@ -34,25 +34,25 @@
         UNKNOWN_EDGE = "unknown_edge"
         CARRIER_EDGE = "carrier_edge"
         SIP_EDGE = "sip_edge"
         SDK_EDGE = "sdk_edge"
         CLIENT_EDGE = "client_edge"
 
     """
-    :ivar timestamp: 
-    :ivar call_sid: 
-    :ivar account_sid: 
+    :ivar timestamp: Event time.
+    :ivar call_sid: The unique SID identifier of the Call.
+    :ivar account_sid: The unique SID identifier of the Account.
     :ivar edge: 
-    :ivar group: 
+    :ivar group: Event group.
     :ivar level: 
-    :ivar name: 
-    :ivar carrier_edge: 
-    :ivar sip_edge: 
-    :ivar sdk_edge: 
-    :ivar client_edge: 
+    :ivar name: Event name.
+    :ivar carrier_edge: Represents the connection between Twilio and our immediate carrier partners. The events here describe the call lifecycle as reported by Twilio's carrier media gateways.
+    :ivar sip_edge: Represents the Twilio media gateway for SIP interface and SIP trunking calls. The events here describe the call lifecycle as reported by Twilio's public media gateways.
+    :ivar sdk_edge: Represents the Voice SDK running locally in the browser or in the Android/iOS application. The events here are emitted by the Voice SDK in response to certain call progress events, network changes, or call quality conditions.
+    :ivar client_edge: Represents the Twilio media gateway for Client calls. The events here describe the call lifecycle as reported by Twilio's Voice SDK media gateways.
     """
 
     def __init__(self, version: Version, payload: Dict[str, Any], call_sid: str):
         super().__init__(version)
 
         self.timestamp: Optional[str] = payload.get("timestamp")
         self.call_sid: Optional[str] = payload.get("call_sid")
@@ -102,15 +102,15 @@
 
 class EventList(ListResource):
     def __init__(self, version: Version, call_sid: str):
         """
         Initialize the EventList
 
         :param version: Version that contains the resource
-        :param call_sid:
+        :param call_sid: The unique SID identifier of the Call.
 
         """
         super().__init__(version)
 
         # Path Solution
         self._solution = {
             "call_sid": call_sid,
@@ -125,15 +125,15 @@
     ) -> Iterator[EventInstance]:
         """
         Streams EventInstance records from the API as a generator stream.
         This operation lazily loads records as efficiently as possible until the limit
         is reached.
         The results are returned as a generator, so this operation is memory efficient.
 
-        :param &quot;EventInstance.TwilioEdge&quot; edge:
+        :param &quot;EventInstance.TwilioEdge&quot; edge: The Edge of this Event. One of `unknown_edge`, `carrier_edge`, `sip_edge`, `sdk_edge` or `client_edge`.
         :param limit: Upper limit for the number of records to return. stream()
                       guarantees to never return more than limit.  Default is no limit
         :param page_size: Number of records to fetch per request, when not set will use
                           the default value of 50 records.  If no page_size is defined
                           but a limit is defined, stream() will attempt to read the
                           limit with the most efficient page size, i.e. min(limit, 1000)
 
@@ -152,15 +152,15 @@
     ) -> AsyncIterator[EventInstance]:
         """
         Asynchronously streams EventInstance records from the API as a generator stream.
         This operation lazily loads records as efficiently as possible until the limit
         is reached.
         The results are returned as a generator, so this operation is memory efficient.
 
-        :param &quot;EventInstance.TwilioEdge&quot; edge:
+        :param &quot;EventInstance.TwilioEdge&quot; edge: The Edge of this Event. One of `unknown_edge`, `carrier_edge`, `sip_edge`, `sdk_edge` or `client_edge`.
         :param limit: Upper limit for the number of records to return. stream()
                       guarantees to never return more than limit.  Default is no limit
         :param page_size: Number of records to fetch per request, when not set will use
                           the default value of 50 records.  If no page_size is defined
                           but a limit is defined, stream() will attempt to read the
                           limit with the most efficient page size, i.e. min(limit, 1000)
 
@@ -178,15 +178,15 @@
         page_size: Optional[int] = None,
     ) -> List[EventInstance]:
         """
         Lists EventInstance records from the API as a list.
         Unlike stream(), this operation is eager and will load `limit` records into
         memory before returning.
 
-        :param &quot;EventInstance.TwilioEdge&quot; edge:
+        :param &quot;EventInstance.TwilioEdge&quot; edge: The Edge of this Event. One of `unknown_edge`, `carrier_edge`, `sip_edge`, `sdk_edge` or `client_edge`.
         :param limit: Upper limit for the number of records to return. list() guarantees
                       never to return more than limit.  Default is no limit
         :param page_size: Number of records to fetch per request, when not set will use
                           the default value of 50 records.  If no page_size is defined
                           but a limit is defined, list() will attempt to read the limit
                           with the most efficient page size, i.e. min(limit, 1000)
 
@@ -207,15 +207,15 @@
         page_size: Optional[int] = None,
     ) -> List[EventInstance]:
         """
         Asynchronously lists EventInstance records from the API as a list.
         Unlike stream(), this operation is eager and will load `limit` records into
         memory before returning.
 
-        :param &quot;EventInstance.TwilioEdge&quot; edge:
+        :param &quot;EventInstance.TwilioEdge&quot; edge: The Edge of this Event. One of `unknown_edge`, `carrier_edge`, `sip_edge`, `sdk_edge` or `client_edge`.
         :param limit: Upper limit for the number of records to return. list() guarantees
                       never to return more than limit.  Default is no limit
         :param page_size: Number of records to fetch per request, when not set will use
                           the default value of 50 records.  If no page_size is defined
                           but a limit is defined, list() will attempt to read the limit
                           with the most efficient page size, i.e. min(limit, 1000)
 
@@ -237,15 +237,15 @@
         page_number: Union[int, object] = values.unset,
         page_size: Union[int, object] = values.unset,
     ) -> EventPage:
         """
         Retrieve a single page of EventInstance records from the API.
         Request is executed immediately
 
-        :param edge:
+        :param edge: The Edge of this Event. One of `unknown_edge`, `carrier_edge`, `sip_edge`, `sdk_edge` or `client_edge`.
         :param page_token: PageToken provided by the API
         :param page_number: Page Number, this value is simply for client state
         :param page_size: Number of records to return, defaults to 50
 
         :returns: Page of EventInstance
         """
         data = values.of(
@@ -267,15 +267,15 @@
         page_number: Union[int, object] = values.unset,
         page_size: Union[int, object] = values.unset,
     ) -> EventPage:
         """
         Asynchronously retrieve a single page of EventInstance records from the API.
         Request is executed immediately
 
-        :param edge:
+        :param edge: The Edge of this Event. One of `unknown_edge`, `carrier_edge`, `sip_edge`, `sdk_edge` or `client_edge`.
         :param page_token: PageToken provided by the API
         :param page_number: Page Number, this value is simply for client state
         :param page_size: Number of records to return, defaults to 50
 
         :returns: Page of EventInstance
         """
         data = values.of(
```

### Comparing `twilio-8.3.0/twilio/rest/insights/v1/call/metric.py` & `twilio-8.4.0/twilio/rest/insights/v1/call/metric.py`

 * *Files 14% similar despite different names*

```diff
@@ -33,23 +33,23 @@
         UNKNOWN_EDGE = "unknown_edge"
         CARRIER_EDGE = "carrier_edge"
         SIP_EDGE = "sip_edge"
         SDK_EDGE = "sdk_edge"
         CLIENT_EDGE = "client_edge"
 
     """
-    :ivar timestamp: 
-    :ivar call_sid: 
-    :ivar account_sid: 
+    :ivar timestamp: Timestamp of metric sample. Samples are taken every 10 seconds and contain the metrics for the previous 10 seconds.
+    :ivar call_sid: The unique SID identifier of the Call.
+    :ivar account_sid: The unique SID identifier of the Account.
     :ivar edge: 
     :ivar direction: 
-    :ivar carrier_edge: 
-    :ivar sip_edge: 
-    :ivar sdk_edge: 
-    :ivar client_edge: 
+    :ivar carrier_edge: Contains metrics and properties for the Twilio media gateway of a PSTN call.
+    :ivar sip_edge: Contains metrics and properties for the Twilio media gateway of a SIP Interface or Trunking call.
+    :ivar sdk_edge: Contains metrics and properties for the SDK sensor library for Client calls.
+    :ivar client_edge: Contains metrics and properties for the Twilio media gateway of a Client call.
     """
 
     def __init__(self, version: Version, payload: Dict[str, Any], call_sid: str):
         super().__init__(version)
 
         self.timestamp: Optional[str] = payload.get("timestamp")
         self.call_sid: Optional[str] = payload.get("call_sid")
@@ -99,15 +99,15 @@
 
 class MetricList(ListResource):
     def __init__(self, version: Version, call_sid: str):
         """
         Initialize the MetricList
 
         :param version: Version that contains the resource
-        :param call_sid:
+        :param call_sid: The unique SID identifier of the Call.
 
         """
         super().__init__(version)
 
         # Path Solution
         self._solution = {
             "call_sid": call_sid,
@@ -123,16 +123,16 @@
     ) -> Iterator[MetricInstance]:
         """
         Streams MetricInstance records from the API as a generator stream.
         This operation lazily loads records as efficiently as possible until the limit
         is reached.
         The results are returned as a generator, so this operation is memory efficient.
 
-        :param &quot;MetricInstance.TwilioEdge&quot; edge:
-        :param &quot;MetricInstance.StreamDirection&quot; direction:
+        :param &quot;MetricInstance.TwilioEdge&quot; edge: The Edge of this Metric. One of `unknown_edge`, `carrier_edge`, `sip_edge`, `sdk_edge` or `client_edge`.
+        :param &quot;MetricInstance.StreamDirection&quot; direction: The Direction of this Metric. One of `unknown`, `inbound`, `outbound` or `both`.
         :param limit: Upper limit for the number of records to return. stream()
                       guarantees to never return more than limit.  Default is no limit
         :param page_size: Number of records to fetch per request, when not set will use
                           the default value of 50 records.  If no page_size is defined
                           but a limit is defined, stream() will attempt to read the
                           limit with the most efficient page size, i.e. min(limit, 1000)
 
@@ -152,16 +152,16 @@
     ) -> AsyncIterator[MetricInstance]:
         """
         Asynchronously streams MetricInstance records from the API as a generator stream.
         This operation lazily loads records as efficiently as possible until the limit
         is reached.
         The results are returned as a generator, so this operation is memory efficient.
 
-        :param &quot;MetricInstance.TwilioEdge&quot; edge:
-        :param &quot;MetricInstance.StreamDirection&quot; direction:
+        :param &quot;MetricInstance.TwilioEdge&quot; edge: The Edge of this Metric. One of `unknown_edge`, `carrier_edge`, `sip_edge`, `sdk_edge` or `client_edge`.
+        :param &quot;MetricInstance.StreamDirection&quot; direction: The Direction of this Metric. One of `unknown`, `inbound`, `outbound` or `both`.
         :param limit: Upper limit for the number of records to return. stream()
                       guarantees to never return more than limit.  Default is no limit
         :param page_size: Number of records to fetch per request, when not set will use
                           the default value of 50 records.  If no page_size is defined
                           but a limit is defined, stream() will attempt to read the
                           limit with the most efficient page size, i.e. min(limit, 1000)
 
@@ -182,16 +182,16 @@
         page_size: Optional[int] = None,
     ) -> List[MetricInstance]:
         """
         Lists MetricInstance records from the API as a list.
         Unlike stream(), this operation is eager and will load `limit` records into
         memory before returning.
 
-        :param &quot;MetricInstance.TwilioEdge&quot; edge:
-        :param &quot;MetricInstance.StreamDirection&quot; direction:
+        :param &quot;MetricInstance.TwilioEdge&quot; edge: The Edge of this Metric. One of `unknown_edge`, `carrier_edge`, `sip_edge`, `sdk_edge` or `client_edge`.
+        :param &quot;MetricInstance.StreamDirection&quot; direction: The Direction of this Metric. One of `unknown`, `inbound`, `outbound` or `both`.
         :param limit: Upper limit for the number of records to return. list() guarantees
                       never to return more than limit.  Default is no limit
         :param page_size: Number of records to fetch per request, when not set will use
                           the default value of 50 records.  If no page_size is defined
                           but a limit is defined, list() will attempt to read the limit
                           with the most efficient page size, i.e. min(limit, 1000)
 
@@ -214,16 +214,16 @@
         page_size: Optional[int] = None,
     ) -> List[MetricInstance]:
         """
         Asynchronously lists MetricInstance records from the API as a list.
         Unlike stream(), this operation is eager and will load `limit` records into
         memory before returning.
 
-        :param &quot;MetricInstance.TwilioEdge&quot; edge:
-        :param &quot;MetricInstance.StreamDirection&quot; direction:
+        :param &quot;MetricInstance.TwilioEdge&quot; edge: The Edge of this Metric. One of `unknown_edge`, `carrier_edge`, `sip_edge`, `sdk_edge` or `client_edge`.
+        :param &quot;MetricInstance.StreamDirection&quot; direction: The Direction of this Metric. One of `unknown`, `inbound`, `outbound` or `both`.
         :param limit: Upper limit for the number of records to return. list() guarantees
                       never to return more than limit.  Default is no limit
         :param page_size: Number of records to fetch per request, when not set will use
                           the default value of 50 records.  If no page_size is defined
                           but a limit is defined, list() will attempt to read the limit
                           with the most efficient page size, i.e. min(limit, 1000)
 
@@ -247,16 +247,16 @@
         page_number: Union[int, object] = values.unset,
         page_size: Union[int, object] = values.unset,
     ) -> MetricPage:
         """
         Retrieve a single page of MetricInstance records from the API.
         Request is executed immediately
 
-        :param edge:
-        :param direction:
+        :param edge: The Edge of this Metric. One of `unknown_edge`, `carrier_edge`, `sip_edge`, `sdk_edge` or `client_edge`.
+        :param direction: The Direction of this Metric. One of `unknown`, `inbound`, `outbound` or `both`.
         :param page_token: PageToken provided by the API
         :param page_number: Page Number, this value is simply for client state
         :param page_size: Number of records to return, defaults to 50
 
         :returns: Page of MetricInstance
         """
         data = values.of(
@@ -280,16 +280,16 @@
         page_number: Union[int, object] = values.unset,
         page_size: Union[int, object] = values.unset,
     ) -> MetricPage:
         """
         Asynchronously retrieve a single page of MetricInstance records from the API.
         Request is executed immediately
 
-        :param edge:
-        :param direction:
+        :param edge: The Edge of this Metric. One of `unknown_edge`, `carrier_edge`, `sip_edge`, `sdk_edge` or `client_edge`.
+        :param direction: The Direction of this Metric. One of `unknown`, `inbound`, `outbound` or `both`.
         :param page_token: PageToken provided by the API
         :param page_number: Page Number, this value is simply for client state
         :param page_size: Number of records to return, defaults to 50
 
         :returns: Page of MetricInstance
         """
         data = values.of(
```

### Comparing `twilio-8.3.0/twilio/rest/insights/v1/conference/__init__.py` & `twilio-8.4.0/twilio/rest/insights/v1/conference/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/insights/v1/conference/conference_participant.py` & `twilio-8.4.0/twilio/rest/insights/v1/conference/conference_participant.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/insights/v1/room/__init__.py` & `twilio-8.4.0/twilio/rest/insights/v1/room/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/insights/v1/room/participant.py` & `twilio-8.4.0/twilio/rest/insights/v1/room/participant.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/insights/v1/setting.py` & `twilio-8.4.0/twilio/rest/insights/v1/setting.py`

 * *Files 20% similar despite different names*

```diff
@@ -20,18 +20,18 @@
 from twilio.base.list_resource import ListResource
 from twilio.base.version import Version
 
 
 class SettingInstance(InstanceResource):
 
     """
-    :ivar account_sid:
-    :ivar advanced_features:
-    :ivar voice_trace:
-    :ivar url:
+    :ivar account_sid: The unique SID identifier of the Account.
+    :ivar advanced_features: A boolean flag indicating whether Advanced Features for Voice Insights are enabled.
+    :ivar voice_trace: A boolean flag indicating whether Voice Trace is enabled.
+    :ivar url: The URL of this resource.
     """
 
     def __init__(self, version: Version, payload: Dict[str, Any]):
         super().__init__(version)
 
         self.account_sid: Optional[str] = payload.get("account_sid")
         self.advanced_features: Optional[bool] = payload.get("advanced_features")
@@ -56,29 +56,29 @@
 
     def fetch(
         self, subaccount_sid: Union[str, object] = values.unset
     ) -> "SettingInstance":
         """
         Fetch the SettingInstance
 
-        :param subaccount_sid:
+        :param subaccount_sid: The unique SID identifier of the Subaccount.
 
         :returns: The fetched SettingInstance
         """
         return self._proxy.fetch(
             subaccount_sid=subaccount_sid,
         )
 
     async def fetch_async(
         self, subaccount_sid: Union[str, object] = values.unset
     ) -> "SettingInstance":
         """
         Asynchronous coroutine to fetch the SettingInstance
 
-        :param subaccount_sid:
+        :param subaccount_sid: The unique SID identifier of the Subaccount.
 
         :returns: The fetched SettingInstance
         """
         return await self._proxy.fetch_async(
             subaccount_sid=subaccount_sid,
         )
 
@@ -87,17 +87,17 @@
         advanced_features: Union[bool, object] = values.unset,
         voice_trace: Union[bool, object] = values.unset,
         subaccount_sid: Union[str, object] = values.unset,
     ) -> "SettingInstance":
         """
         Update the SettingInstance
 
-        :param advanced_features:
-        :param voice_trace:
-        :param subaccount_sid:
+        :param advanced_features: A boolean flag to enable Advanced Features for Voice Insights.
+        :param voice_trace: A boolean flag to enable Voice Trace.
+        :param subaccount_sid: The unique SID identifier of the Subaccount.
 
         :returns: The updated SettingInstance
         """
         return self._proxy.update(
             advanced_features=advanced_features,
             voice_trace=voice_trace,
             subaccount_sid=subaccount_sid,
@@ -108,17 +108,17 @@
         advanced_features: Union[bool, object] = values.unset,
         voice_trace: Union[bool, object] = values.unset,
         subaccount_sid: Union[str, object] = values.unset,
     ) -> "SettingInstance":
         """
         Asynchronous coroutine to update the SettingInstance
 
-        :param advanced_features:
-        :param voice_trace:
-        :param subaccount_sid:
+        :param advanced_features: A boolean flag to enable Advanced Features for Voice Insights.
+        :param voice_trace: A boolean flag to enable Voice Trace.
+        :param subaccount_sid: The unique SID identifier of the Subaccount.
 
         :returns: The updated SettingInstance
         """
         return await self._proxy.update_async(
             advanced_features=advanced_features,
             voice_trace=voice_trace,
             subaccount_sid=subaccount_sid,
@@ -147,15 +147,15 @@
 
     def fetch(
         self, subaccount_sid: Union[str, object] = values.unset
     ) -> SettingInstance:
         """
         Fetch the SettingInstance
 
-        :param subaccount_sid:
+        :param subaccount_sid: The unique SID identifier of the Subaccount.
 
         :returns: The fetched SettingInstance
         """
 
         data = values.of(
             {
                 "SubaccountSid": subaccount_sid,
@@ -171,15 +171,15 @@
 
     async def fetch_async(
         self, subaccount_sid: Union[str, object] = values.unset
     ) -> SettingInstance:
         """
         Asynchronous coroutine to fetch the SettingInstance
 
-        :param subaccount_sid:
+        :param subaccount_sid: The unique SID identifier of the Subaccount.
 
         :returns: The fetched SettingInstance
         """
 
         data = values.of(
             {
                 "SubaccountSid": subaccount_sid,
@@ -200,17 +200,17 @@
         advanced_features: Union[bool, object] = values.unset,
         voice_trace: Union[bool, object] = values.unset,
         subaccount_sid: Union[str, object] = values.unset,
     ) -> SettingInstance:
         """
         Update the SettingInstance
 
-        :param advanced_features:
-        :param voice_trace:
-        :param subaccount_sid:
+        :param advanced_features: A boolean flag to enable Advanced Features for Voice Insights.
+        :param voice_trace: A boolean flag to enable Voice Trace.
+        :param subaccount_sid: The unique SID identifier of the Subaccount.
 
         :returns: The updated SettingInstance
         """
         data = values.of(
             {
                 "AdvancedFeatures": advanced_features,
                 "VoiceTrace": voice_trace,
@@ -231,17 +231,17 @@
         advanced_features: Union[bool, object] = values.unset,
         voice_trace: Union[bool, object] = values.unset,
         subaccount_sid: Union[str, object] = values.unset,
     ) -> SettingInstance:
         """
         Asynchronous coroutine to update the SettingInstance
 
-        :param advanced_features:
-        :param voice_trace:
-        :param subaccount_sid:
+        :param advanced_features: A boolean flag to enable Advanced Features for Voice Insights.
+        :param voice_trace: A boolean flag to enable Voice Trace.
+        :param subaccount_sid: The unique SID identifier of the Subaccount.
 
         :returns: The updated SettingInstance
         """
         data = values.of(
             {
                 "AdvancedFeatures": advanced_features,
                 "VoiceTrace": voice_trace,
```

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/IpMessagingBase.py` & `twilio-8.4.0/twilio/rest/ip_messaging/IpMessagingBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/__init__.py` & `twilio-8.4.0/twilio/rest/ip_messaging/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v1/__init__.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v1/credential.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v1/credential.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v1/service/__init__.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v1/service/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v1/service/channel/__init__.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v1/service/channel/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v1/service/channel/invite.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v1/service/channel/invite.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v1/service/channel/member.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v1/service/channel/member.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v1/service/channel/message.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v1/service/channel/message.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v1/service/role.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v1/service/role.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v1/service/user/__init__.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v1/service/user/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v1/service/user/user_channel.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v1/service/user/user_channel.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/__init__.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/credential.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/credential.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/service/__init__.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/service/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/service/binding.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/service/binding.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/service/channel/__init__.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/service/channel/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/service/channel/invite.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/service/channel/invite.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/service/channel/member.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/service/channel/member.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/service/channel/message.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/service/channel/message.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/service/channel/webhook.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/service/channel/webhook.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/service/role.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/service/role.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/service/user/__init__.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/service/user/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/service/user/user_binding.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/service/user/user_binding.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/ip_messaging/v2/service/user/user_channel.py` & `twilio-8.4.0/twilio/rest/ip_messaging/v2/service/user/user_channel.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/lookups/LookupsBase.py` & `twilio-8.4.0/twilio/rest/lookups/LookupsBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/lookups/v1/__init__.py` & `twilio-8.4.0/twilio/rest/lookups/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/lookups/v1/phone_number.py` & `twilio-8.4.0/twilio/rest/lookups/v1/phone_number.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/lookups/v2/__init__.py` & `twilio-8.4.0/twilio/rest/lookups/v2/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/lookups/v2/phone_number.py` & `twilio-8.4.0/twilio/rest/lookups/v2/phone_number.py`

 * *Files 6% similar despite different names*

```diff
@@ -39,14 +39,15 @@
     :ivar validation_errors: Contains reasons why a phone number is invalid. Possible values: TOO_SHORT, TOO_LONG, INVALID_BUT_POSSIBLE, INVALID_COUNTRY_CODE, INVALID_LENGTH, NOT_A_NUMBER.
     :ivar caller_name: An object that contains caller name information based on [CNAM](https://support.twilio.com/hc/en-us/articles/360051670533-Getting-Started-with-CNAM-Caller-ID).
     :ivar sim_swap: An object that contains information on the last date the subscriber identity module (SIM) was changed for a mobile phone number.
     :ivar call_forwarding: An object that contains information on the unconditional call forwarding status of mobile phone number.
     :ivar live_activity: An object that contains live activity information for a mobile phone number.
     :ivar line_type_intelligence: An object that contains line type information including the carrier name, mobile country code, and mobile network code.
     :ivar identity_match: An object that contains identity match information. The result of comparing user-provided information including name, address, date of birth, national ID, against authoritative phone-based data sources
+    :ivar reassigned_number: An object that contains reassigned number information. Reassigned Numbers will return a phone number's reassignment status given a phone number and date
     :ivar sms_pumping_risk: An object that contains information on if a phone number has been currently or previously blocked by Verify Fraud Guard for receiving malicious SMS pumping traffic as well as other signals associated with risky carriers and low conversion rates.
     :ivar url: The absolute URL of the resource.
     """
 
     def __init__(
         self,
         version: Version,
@@ -69,14 +70,17 @@
             "call_forwarding"
         )
         self.live_activity: Optional[Dict[str, object]] = payload.get("live_activity")
         self.line_type_intelligence: Optional[Dict[str, object]] = payload.get(
             "line_type_intelligence"
         )
         self.identity_match: Optional[Dict[str, object]] = payload.get("identity_match")
+        self.reassigned_number: Optional[Dict[str, object]] = payload.get(
+            "reassigned_number"
+        )
         self.sms_pumping_risk: Optional[Dict[str, object]] = payload.get(
             "sms_pumping_risk"
         )
         self.url: Optional[str] = payload.get("url")
 
         self._solution = {
             "phone_number": phone_number or self.phone_number,
@@ -108,30 +112,32 @@
         address_line2: Union[str, object] = values.unset,
         city: Union[str, object] = values.unset,
         state: Union[str, object] = values.unset,
         postal_code: Union[str, object] = values.unset,
         address_country_code: Union[str, object] = values.unset,
         national_id: Union[str, object] = values.unset,
         date_of_birth: Union[str, object] = values.unset,
+        last_verified_date: Union[str, object] = values.unset,
     ) -> "PhoneNumberInstance":
         """
         Fetch the PhoneNumberInstance
 
-        :param fields: A comma-separated list of fields to return. Possible values are caller_name, sim_swap, call_forwarding, live_activity, line_type_intelligence, identity_match.
+        :param fields: A comma-separated list of fields to return. Possible values are caller_name, sim_swap, call_forwarding, live_activity, line_type_intelligence, identity_match, reassigned_number.
         :param country_code: The [country code](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) used if the phone number provided is in national format.
         :param first_name: User’s first name. This query parameter is only used (optionally) for identity_match package requests.
         :param last_name: User’s last name. This query parameter is only used (optionally) for identity_match package requests.
         :param address_line1: User’s first address line. This query parameter is only used (optionally) for identity_match package requests.
         :param address_line2: User’s second address line. This query parameter is only used (optionally) for identity_match package requests.
         :param city: User’s city. This query parameter is only used (optionally) for identity_match package requests.
         :param state: User’s country subdivision, such as state, province, or locality. This query parameter is only used (optionally) for identity_match package requests.
         :param postal_code: User’s postal zip code. This query parameter is only used (optionally) for identity_match package requests.
         :param address_country_code: User’s country, up to two characters. This query parameter is only used (optionally) for identity_match package requests.
         :param national_id: User’s national ID, such as SSN or Passport ID. This query parameter is only used (optionally) for identity_match package requests.
         :param date_of_birth: User’s date of birth, in YYYYMMDD format. This query parameter is only used (optionally) for identity_match package requests.
+        :param last_verified_date: The date you obtained consent to call or text the end-user of the phone number or a date on which you are reasonably certain that the end-user could still be reached at that number. This query parameter is only used (optionally) for reassigned_number package requests.
 
         :returns: The fetched PhoneNumberInstance
         """
         return self._proxy.fetch(
             fields=fields,
             country_code=country_code,
             first_name=first_name,
@@ -140,14 +146,15 @@
             address_line2=address_line2,
             city=city,
             state=state,
             postal_code=postal_code,
             address_country_code=address_country_code,
             national_id=national_id,
             date_of_birth=date_of_birth,
+            last_verified_date=last_verified_date,
         )
 
     async def fetch_async(
         self,
         fields: Union[str, object] = values.unset,
         country_code: Union[str, object] = values.unset,
         first_name: Union[str, object] = values.unset,
@@ -156,30 +163,32 @@
         address_line2: Union[str, object] = values.unset,
         city: Union[str, object] = values.unset,
         state: Union[str, object] = values.unset,
         postal_code: Union[str, object] = values.unset,
         address_country_code: Union[str, object] = values.unset,
         national_id: Union[str, object] = values.unset,
         date_of_birth: Union[str, object] = values.unset,
+        last_verified_date: Union[str, object] = values.unset,
     ) -> "PhoneNumberInstance":
         """
         Asynchronous coroutine to fetch the PhoneNumberInstance
 
-        :param fields: A comma-separated list of fields to return. Possible values are caller_name, sim_swap, call_forwarding, live_activity, line_type_intelligence, identity_match.
+        :param fields: A comma-separated list of fields to return. Possible values are caller_name, sim_swap, call_forwarding, live_activity, line_type_intelligence, identity_match, reassigned_number.
         :param country_code: The [country code](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) used if the phone number provided is in national format.
         :param first_name: User’s first name. This query parameter is only used (optionally) for identity_match package requests.
         :param last_name: User’s last name. This query parameter is only used (optionally) for identity_match package requests.
         :param address_line1: User’s first address line. This query parameter is only used (optionally) for identity_match package requests.
         :param address_line2: User’s second address line. This query parameter is only used (optionally) for identity_match package requests.
         :param city: User’s city. This query parameter is only used (optionally) for identity_match package requests.
         :param state: User’s country subdivision, such as state, province, or locality. This query parameter is only used (optionally) for identity_match package requests.
         :param postal_code: User’s postal zip code. This query parameter is only used (optionally) for identity_match package requests.
         :param address_country_code: User’s country, up to two characters. This query parameter is only used (optionally) for identity_match package requests.
         :param national_id: User’s national ID, such as SSN or Passport ID. This query parameter is only used (optionally) for identity_match package requests.
         :param date_of_birth: User’s date of birth, in YYYYMMDD format. This query parameter is only used (optionally) for identity_match package requests.
+        :param last_verified_date: The date you obtained consent to call or text the end-user of the phone number or a date on which you are reasonably certain that the end-user could still be reached at that number. This query parameter is only used (optionally) for reassigned_number package requests.
 
         :returns: The fetched PhoneNumberInstance
         """
         return await self._proxy.fetch_async(
             fields=fields,
             country_code=country_code,
             first_name=first_name,
@@ -188,14 +197,15 @@
             address_line2=address_line2,
             city=city,
             state=state,
             postal_code=postal_code,
             address_country_code=address_country_code,
             national_id=national_id,
             date_of_birth=date_of_birth,
+            last_verified_date=last_verified_date,
         )
 
     def __repr__(self) -> str:
         """
         Provide a friendly representation
 
         :returns: Machine friendly representation
@@ -230,30 +240,32 @@
         address_line2: Union[str, object] = values.unset,
         city: Union[str, object] = values.unset,
         state: Union[str, object] = values.unset,
         postal_code: Union[str, object] = values.unset,
         address_country_code: Union[str, object] = values.unset,
         national_id: Union[str, object] = values.unset,
         date_of_birth: Union[str, object] = values.unset,
+        last_verified_date: Union[str, object] = values.unset,
     ) -> PhoneNumberInstance:
         """
         Fetch the PhoneNumberInstance
 
-        :param fields: A comma-separated list of fields to return. Possible values are caller_name, sim_swap, call_forwarding, live_activity, line_type_intelligence, identity_match.
+        :param fields: A comma-separated list of fields to return. Possible values are caller_name, sim_swap, call_forwarding, live_activity, line_type_intelligence, identity_match, reassigned_number.
         :param country_code: The [country code](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) used if the phone number provided is in national format.
         :param first_name: User’s first name. This query parameter is only used (optionally) for identity_match package requests.
         :param last_name: User’s last name. This query parameter is only used (optionally) for identity_match package requests.
         :param address_line1: User’s first address line. This query parameter is only used (optionally) for identity_match package requests.
         :param address_line2: User’s second address line. This query parameter is only used (optionally) for identity_match package requests.
         :param city: User’s city. This query parameter is only used (optionally) for identity_match package requests.
         :param state: User’s country subdivision, such as state, province, or locality. This query parameter is only used (optionally) for identity_match package requests.
         :param postal_code: User’s postal zip code. This query parameter is only used (optionally) for identity_match package requests.
         :param address_country_code: User’s country, up to two characters. This query parameter is only used (optionally) for identity_match package requests.
         :param national_id: User’s national ID, such as SSN or Passport ID. This query parameter is only used (optionally) for identity_match package requests.
         :param date_of_birth: User’s date of birth, in YYYYMMDD format. This query parameter is only used (optionally) for identity_match package requests.
+        :param last_verified_date: The date you obtained consent to call or text the end-user of the phone number or a date on which you are reasonably certain that the end-user could still be reached at that number. This query parameter is only used (optionally) for reassigned_number package requests.
 
         :returns: The fetched PhoneNumberInstance
         """
 
         data = values.of(
             {
                 "Fields": fields,
@@ -264,14 +276,15 @@
                 "AddressLine2": address_line2,
                 "City": city,
                 "State": state,
                 "PostalCode": postal_code,
                 "AddressCountryCode": address_country_code,
                 "NationalId": national_id,
                 "DateOfBirth": date_of_birth,
+                "LastVerifiedDate": last_verified_date,
             }
         )
 
         payload = self._version.fetch(method="GET", uri=self._uri, params=data)
 
         return PhoneNumberInstance(
             self._version,
@@ -289,30 +302,32 @@
         address_line2: Union[str, object] = values.unset,
         city: Union[str, object] = values.unset,
         state: Union[str, object] = values.unset,
         postal_code: Union[str, object] = values.unset,
         address_country_code: Union[str, object] = values.unset,
         national_id: Union[str, object] = values.unset,
         date_of_birth: Union[str, object] = values.unset,
+        last_verified_date: Union[str, object] = values.unset,
     ) -> PhoneNumberInstance:
         """
         Asynchronous coroutine to fetch the PhoneNumberInstance
 
-        :param fields: A comma-separated list of fields to return. Possible values are caller_name, sim_swap, call_forwarding, live_activity, line_type_intelligence, identity_match.
+        :param fields: A comma-separated list of fields to return. Possible values are caller_name, sim_swap, call_forwarding, live_activity, line_type_intelligence, identity_match, reassigned_number.
         :param country_code: The [country code](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) used if the phone number provided is in national format.
         :param first_name: User’s first name. This query parameter is only used (optionally) for identity_match package requests.
         :param last_name: User’s last name. This query parameter is only used (optionally) for identity_match package requests.
         :param address_line1: User’s first address line. This query parameter is only used (optionally) for identity_match package requests.
         :param address_line2: User’s second address line. This query parameter is only used (optionally) for identity_match package requests.
         :param city: User’s city. This query parameter is only used (optionally) for identity_match package requests.
         :param state: User’s country subdivision, such as state, province, or locality. This query parameter is only used (optionally) for identity_match package requests.
         :param postal_code: User’s postal zip code. This query parameter is only used (optionally) for identity_match package requests.
         :param address_country_code: User’s country, up to two characters. This query parameter is only used (optionally) for identity_match package requests.
         :param national_id: User’s national ID, such as SSN or Passport ID. This query parameter is only used (optionally) for identity_match package requests.
         :param date_of_birth: User’s date of birth, in YYYYMMDD format. This query parameter is only used (optionally) for identity_match package requests.
+        :param last_verified_date: The date you obtained consent to call or text the end-user of the phone number or a date on which you are reasonably certain that the end-user could still be reached at that number. This query parameter is only used (optionally) for reassigned_number package requests.
 
         :returns: The fetched PhoneNumberInstance
         """
 
         data = values.of(
             {
                 "Fields": fields,
@@ -323,14 +338,15 @@
                 "AddressLine2": address_line2,
                 "City": city,
                 "State": state,
                 "PostalCode": postal_code,
                 "AddressCountryCode": address_country_code,
                 "NationalId": national_id,
                 "DateOfBirth": date_of_birth,
+                "LastVerifiedDate": last_verified_date,
             }
         )
 
         payload = await self._version.fetch_async(
             method="GET", uri=self._uri, params=data
         )
```

### Comparing `twilio-8.3.0/twilio/rest/media/MediaBase.py` & `twilio-8.4.0/twilio/rest/media/MediaBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/media/__init__.py` & `twilio-8.4.0/twilio/rest/media/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/media/v1/__init__.py` & `twilio-8.4.0/twilio/rest/media/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/media/v1/media_processor.py` & `twilio-8.4.0/twilio/rest/media/v1/media_processor.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/media/v1/media_recording.py` & `twilio-8.4.0/twilio/rest/media/v1/media_recording.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/media/v1/player_streamer/__init__.py` & `twilio-8.4.0/twilio/rest/media/v1/player_streamer/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/media/v1/player_streamer/playback_grant.py` & `twilio-8.4.0/twilio/rest/media/v1/player_streamer/playback_grant.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/MessagingBase.py` & `twilio-8.4.0/twilio/rest/messaging/MessagingBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/__init__.py` & `twilio-8.4.0/twilio/rest/messaging/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/__init__.py` & `twilio-8.4.0/twilio/rest/messaging/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/brand_registration/__init__.py` & `twilio-8.4.0/twilio/rest/messaging/v1/brand_registration/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/brand_registration/brand_registration_otp.py` & `twilio-8.4.0/twilio/rest/messaging/v1/brand_registration/brand_registration_otp.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/brand_registration/brand_vetting.py` & `twilio-8.4.0/twilio/rest/messaging/v1/brand_registration/brand_vetting.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/deactivations.py` & `twilio-8.4.0/twilio/rest/messaging/v1/deactivations.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/domain_certs.py` & `twilio-8.4.0/twilio/rest/messaging/v1/domain_certs.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/domain_config.py` & `twilio-8.4.0/twilio/rest/messaging/v1/domain_config.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/domain_config_messaging_service.py` & `twilio-8.4.0/twilio/rest/messaging/v1/domain_config_messaging_service.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/external_campaign.py` & `twilio-8.4.0/twilio/rest/messaging/v1/external_campaign.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/linkshortening_messaging_service.py` & `twilio-8.4.0/twilio/rest/messaging/v1/linkshortening_messaging_service.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/linkshortening_messaging_service_domain_association.py` & `twilio-8.4.0/twilio/rest/messaging/v1/linkshortening_messaging_service_domain_association.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/service/__init__.py` & `twilio-8.4.0/twilio/rest/messaging/v1/service/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/service/alpha_sender.py` & `twilio-8.4.0/twilio/rest/messaging/v1/service/alpha_sender.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/service/phone_number.py` & `twilio-8.4.0/twilio/rest/messaging/v1/service/phone_number.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/service/short_code.py` & `twilio-8.4.0/twilio/rest/messaging/v1/service/short_code.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/service/us_app_to_person.py` & `twilio-8.4.0/twilio/rest/messaging/v1/service/us_app_to_person.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/service/us_app_to_person_usecase.py` & `twilio-8.4.0/twilio/rest/messaging/v1/service/us_app_to_person_usecase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/messaging/v1/usecase.py` & `twilio-8.4.0/twilio/rest/messaging/v1/usecase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/microvisor/MicrovisorBase.py` & `twilio-8.4.0/twilio/rest/microvisor/MicrovisorBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/microvisor/__init__.py` & `twilio-8.4.0/twilio/rest/microvisor/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/microvisor/v1/__init__.py` & `twilio-8.4.0/twilio/rest/microvisor/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/microvisor/v1/account_config.py` & `twilio-8.4.0/twilio/rest/microvisor/v1/account_config.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/microvisor/v1/account_secret.py` & `twilio-8.4.0/twilio/rest/microvisor/v1/account_secret.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/microvisor/v1/app/__init__.py` & `twilio-8.4.0/twilio/rest/microvisor/v1/app/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/microvisor/v1/app/app_manifest.py` & `twilio-8.4.0/twilio/rest/microvisor/v1/app/app_manifest.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/microvisor/v1/device/__init__.py` & `twilio-8.4.0/twilio/rest/microvisor/v1/device/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/microvisor/v1/device/device_config.py` & `twilio-8.4.0/twilio/rest/microvisor/v1/device/device_config.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/microvisor/v1/device/device_secret.py` & `twilio-8.4.0/twilio/rest/microvisor/v1/device/device_secret.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/monitor/MonitorBase.py` & `twilio-8.4.0/twilio/rest/monitor/MonitorBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/monitor/__init__.py` & `twilio-8.4.0/twilio/rest/monitor/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/monitor/v1/__init__.py` & `twilio-8.4.0/twilio/rest/monitor/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/monitor/v1/alert.py` & `twilio-8.4.0/twilio/rest/monitor/v1/alert.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/monitor/v1/event.py` & `twilio-8.4.0/twilio/rest/monitor/v1/event.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/notify/NotifyBase.py` & `twilio-8.4.0/twilio/rest/notify/NotifyBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/notify/__init__.py` & `twilio-8.4.0/twilio/rest/notify/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/notify/v1/__init__.py` & `twilio-8.4.0/twilio/rest/notify/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/notify/v1/credential.py` & `twilio-8.4.0/twilio/rest/notify/v1/credential.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/notify/v1/service/__init__.py` & `twilio-8.4.0/twilio/rest/notify/v1/service/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/notify/v1/service/binding.py` & `twilio-8.4.0/twilio/rest/notify/v1/service/binding.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/notify/v1/service/notification.py` & `twilio-8.4.0/twilio/rest/notify/v1/service/notification.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/NumbersBase.py` & `twilio-8.4.0/twilio/rest/numbers/NumbersBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/v1/__init__.py` & `twilio-8.4.0/twilio/rest/serverless/v1/__init__.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,42 +1,42 @@
 r"""
     This code was generated by
    ___ _ _ _ _ _    _ ____    ____ ____ _    ____ ____ _  _ ____ ____ ____ ___ __   __
     |  | | | | |    | |  | __ |  | |__| | __ | __ |___ |\ | |___ |__/ |__|  | |  | |__/
     |  |_|_| | |___ | |__|    |__| |  | |    |__] |___ | \| |___ |  \ |  |  | |__| |  \
 
-    Twilio - Numbers
+    Twilio - Serverless
     This is the public Twilio REST API.
 
     NOTE: This class is auto generated by OpenAPI Generator.
     https://openapi-generator.tech
     Do not edit the class manually.
 """
 
 from typing import Optional
 from twilio.base.version import Version
 from twilio.base.domain import Domain
-from twilio.rest.numbers.v1.bulk_eligibility import BulkEligibilityList
+from twilio.rest.serverless.v1.service import ServiceList
 
 
 class V1(Version):
     def __init__(self, domain: Domain):
         """
-        Initialize the V1 version of Numbers
+        Initialize the V1 version of Serverless
 
-        :param domain: The Twilio.numbers domain
+        :param domain: The Twilio.serverless domain
         """
         super().__init__(domain, "v1")
-        self._bulk_eligibilities: Optional[BulkEligibilityList] = None
+        self._services: Optional[ServiceList] = None
 
     @property
-    def bulk_eligibilities(self) -> BulkEligibilityList:
-        if self._bulk_eligibilities is None:
-            self._bulk_eligibilities = BulkEligibilityList(self)
-        return self._bulk_eligibilities
+    def services(self) -> ServiceList:
+        if self._services is None:
+            self._services = ServiceList(self)
+        return self._services
 
     def __repr__(self) -> str:
         """
         Provide a friendly representation
         :returns: Machine friendly representation
         """
-        return "<Twilio.Numbers.V1>"
+        return "<Twilio.Serverless.V1>"
```

### Comparing `twilio-8.3.0/twilio/rest/numbers/v1/bulk_eligibility.py` & `twilio-8.4.0/twilio/rest/numbers/v1/bulk_eligibility.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/v2/__init__.py` & `twilio-8.4.0/twilio/rest/preview/deployed_devices/__init__.py`

 * *Files 15% similar despite different names*

```diff
@@ -1,42 +1,42 @@
 r"""
     This code was generated by
    ___ _ _ _ _ _    _ ____    ____ ____ _    ____ ____ _  _ ____ ____ ____ ___ __   __
     |  | | | | |    | |  | __ |  | |__| | __ | __ |___ |\ | |___ |__/ |__|  | |  | |__/
     |  |_|_| | |___ | |__|    |__| |  | |    |__] |___ | \| |___ |  \ |  |  | |__| |  \
 
-    Twilio - Numbers
+    Twilio - Preview
     This is the public Twilio REST API.
 
     NOTE: This class is auto generated by OpenAPI Generator.
     https://openapi-generator.tech
     Do not edit the class manually.
 """
 
 from typing import Optional
 from twilio.base.version import Version
 from twilio.base.domain import Domain
-from twilio.rest.numbers.v2.regulatory_compliance import RegulatoryComplianceList
+from twilio.rest.preview.deployed_devices.fleet import FleetList
 
 
-class V2(Version):
+class DeployedDevices(Version):
     def __init__(self, domain: Domain):
         """
-        Initialize the V2 version of Numbers
+        Initialize the DeployedDevices version of Preview
 
-        :param domain: The Twilio.numbers domain
+        :param domain: The Twilio.preview domain
         """
-        super().__init__(domain, "v2")
-        self._regulatory_compliance: Optional[RegulatoryComplianceList] = None
+        super().__init__(domain, "DeployedDevices")
+        self._fleets: Optional[FleetList] = None
 
     @property
-    def regulatory_compliance(self) -> RegulatoryComplianceList:
-        if self._regulatory_compliance is None:
-            self._regulatory_compliance = RegulatoryComplianceList(self)
-        return self._regulatory_compliance
+    def fleets(self) -> FleetList:
+        if self._fleets is None:
+            self._fleets = FleetList(self)
+        return self._fleets
 
     def __repr__(self) -> str:
         """
         Provide a friendly representation
         :returns: Machine friendly representation
         """
-        return "<Twilio.Numbers.V2>"
+        return "<Twilio.Preview.DeployedDevices>"
```

### Comparing `twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/__init__.py` & `twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/__init__.py` & `twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/bundle_copy.py` & `twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/bundle_copy.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/evaluation.py` & `twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/evaluation.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/item_assignment.py` & `twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/item_assignment.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/replace_items.py` & `twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/bundle/replace_items.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/end_user.py` & `twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/end_user.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/end_user_type.py` & `twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/end_user_type.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/regulation.py` & `twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/regulation.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/supporting_document.py` & `twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/supporting_document.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/numbers/v2/regulatory_compliance/supporting_document_type.py` & `twilio-8.4.0/twilio/rest/numbers/v2/regulatory_compliance/supporting_document_type.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/oauth/OauthBase.py` & `twilio-8.4.0/twilio/rest/oauth/OauthBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/oauth/__init__.py` & `twilio-8.4.0/twilio/rest/oauth/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/oauth/v1/__init__.py` & `twilio-8.4.0/twilio/rest/oauth/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/oauth/v1/device_code.py` & `twilio-8.4.0/twilio/rest/oauth/v1/device_code.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/oauth/v1/oauth.py` & `twilio-8.4.0/twilio/rest/oauth/v1/oauth.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/oauth/v1/openid_discovery.py` & `twilio-8.4.0/twilio/rest/oauth/v1/openid_discovery.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/oauth/v1/token.py` & `twilio-8.4.0/twilio/rest/oauth/v1/token.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/oauth/v1/user_info.py` & `twilio-8.4.0/twilio/rest/oauth/v1/user_info.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/PreviewBase.py` & `twilio-8.4.0/twilio/rest/preview/PreviewBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/__init__.py` & `twilio-8.4.0/twilio/rest/preview/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/deployed_devices/__init__.py` & `twilio-8.4.0/twilio/rest/trunking/v1/__init__.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,42 +1,42 @@
 r"""
     This code was generated by
    ___ _ _ _ _ _    _ ____    ____ ____ _    ____ ____ _  _ ____ ____ ____ ___ __   __
     |  | | | | |    | |  | __ |  | |__| | __ | __ |___ |\ | |___ |__/ |__|  | |  | |__/
     |  |_|_| | |___ | |__|    |__| |  | |    |__] |___ | \| |___ |  \ |  |  | |__| |  \
 
-    Twilio - Preview
+    Twilio - Trunking
     This is the public Twilio REST API.
 
     NOTE: This class is auto generated by OpenAPI Generator.
     https://openapi-generator.tech
     Do not edit the class manually.
 """
 
 from typing import Optional
 from twilio.base.version import Version
 from twilio.base.domain import Domain
-from twilio.rest.preview.deployed_devices.fleet import FleetList
+from twilio.rest.trunking.v1.trunk import TrunkList
 
 
-class DeployedDevices(Version):
+class V1(Version):
     def __init__(self, domain: Domain):
         """
-        Initialize the DeployedDevices version of Preview
+        Initialize the V1 version of Trunking
 
-        :param domain: The Twilio.preview domain
+        :param domain: The Twilio.trunking domain
         """
-        super().__init__(domain, "DeployedDevices")
-        self._fleets: Optional[FleetList] = None
+        super().__init__(domain, "v1")
+        self._trunks: Optional[TrunkList] = None
 
     @property
-    def fleets(self) -> FleetList:
-        if self._fleets is None:
-            self._fleets = FleetList(self)
-        return self._fleets
+    def trunks(self) -> TrunkList:
+        if self._trunks is None:
+            self._trunks = TrunkList(self)
+        return self._trunks
 
     def __repr__(self) -> str:
         """
         Provide a friendly representation
         :returns: Machine friendly representation
         """
-        return "<Twilio.Preview.DeployedDevices>"
+        return "<Twilio.Trunking.V1>"
```

### Comparing `twilio-8.3.0/twilio/rest/preview/deployed_devices/fleet/__init__.py` & `twilio-8.4.0/twilio/rest/preview/deployed_devices/fleet/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/deployed_devices/fleet/certificate.py` & `twilio-8.4.0/twilio/rest/preview/deployed_devices/fleet/certificate.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/deployed_devices/fleet/deployment.py` & `twilio-8.4.0/twilio/rest/preview/deployed_devices/fleet/deployment.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/deployed_devices/fleet/device.py` & `twilio-8.4.0/twilio/rest/preview/deployed_devices/fleet/device.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/deployed_devices/fleet/key.py` & `twilio-8.4.0/twilio/rest/preview/deployed_devices/fleet/key.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/hosted_numbers/__init__.py` & `twilio-8.4.0/twilio/rest/preview/hosted_numbers/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/hosted_numbers/authorization_document/__init__.py` & `twilio-8.4.0/twilio/rest/preview/hosted_numbers/authorization_document/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/hosted_numbers/authorization_document/dependent_hosted_number_order.py` & `twilio-8.4.0/twilio/rest/preview/hosted_numbers/authorization_document/dependent_hosted_number_order.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/hosted_numbers/hosted_number_order.py` & `twilio-8.4.0/twilio/rest/preview/hosted_numbers/hosted_number_order.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/marketplace/__init__.py` & `twilio-8.4.0/twilio/rest/preview/marketplace/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/marketplace/available_add_on/__init__.py` & `twilio-8.4.0/twilio/rest/preview/marketplace/available_add_on/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/marketplace/available_add_on/available_add_on_extension.py` & `twilio-8.4.0/twilio/rest/preview/marketplace/available_add_on/available_add_on_extension.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/marketplace/installed_add_on/__init__.py` & `twilio-8.4.0/twilio/rest/preview/marketplace/installed_add_on/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/marketplace/installed_add_on/installed_add_on_extension.py` & `twilio-8.4.0/twilio/rest/preview/marketplace/installed_add_on/installed_add_on_extension.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/sync/__init__.py` & `twilio-8.4.0/twilio/rest/preview/sync/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/sync/service/__init__.py` & `twilio-8.4.0/twilio/rest/preview/sync/service/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/sync/service/document/__init__.py` & `twilio-8.4.0/twilio/rest/preview/sync/service/document/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/sync/service/document/document_permission.py` & `twilio-8.4.0/twilio/rest/preview/sync/service/document/document_permission.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/sync/service/sync_list/__init__.py` & `twilio-8.4.0/twilio/rest/preview/sync/service/sync_list/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/sync/service/sync_list/sync_list_item.py` & `twilio-8.4.0/twilio/rest/preview/sync/service/sync_list/sync_list_item.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/sync/service/sync_list/sync_list_permission.py` & `twilio-8.4.0/twilio/rest/preview/sync/service/sync_list/sync_list_permission.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/sync/service/sync_map/__init__.py` & `twilio-8.4.0/twilio/rest/preview/sync/service/sync_map/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/sync/service/sync_map/sync_map_item.py` & `twilio-8.4.0/twilio/rest/preview/sync/service/sync_map/sync_map_item.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/sync/service/sync_map/sync_map_permission.py` & `twilio-8.4.0/twilio/rest/preview/sync/service/sync_map/sync_map_permission.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/__init__.py` & `twilio-8.4.0/twilio/rest/preview/understand/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/__init__.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/assistant_fallback_actions.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/assistant_fallback_actions.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/assistant_initiation_actions.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/assistant_initiation_actions.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/dialogue.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/dialogue.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/field_type/__init__.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/field_type/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/field_type/field_value.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/field_type/field_value.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/model_build.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/model_build.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/query.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/query.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/style_sheet.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/style_sheet.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/task/__init__.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/task/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/task/field.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/task/field.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/task/sample.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/task/sample.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/understand/assistant/task/task_statistics.py` & `twilio-8.4.0/twilio/rest/preview/understand/assistant/task/task_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/wireless/__init__.py` & `twilio-8.4.0/twilio/rest/preview/wireless/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/wireless/command.py` & `twilio-8.4.0/twilio/rest/preview/wireless/command.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/wireless/rate_plan.py` & `twilio-8.4.0/twilio/rest/preview/wireless/rate_plan.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/wireless/sim/__init__.py` & `twilio-8.4.0/twilio/rest/preview/wireless/sim/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/preview/wireless/sim/usage.py` & `twilio-8.4.0/twilio/rest/preview/wireless/sim/usage.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/PricingBase.py` & `twilio-8.4.0/twilio/rest/pricing/PricingBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/__init__.py` & `twilio-8.4.0/twilio/rest/pricing/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v1/__init__.py` & `twilio-8.4.0/twilio/rest/pricing/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v1/messaging/__init__.py` & `twilio-8.4.0/twilio/rest/pricing/v1/messaging/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v1/messaging/country.py` & `twilio-8.4.0/twilio/rest/pricing/v1/messaging/country.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v1/phone_number/__init__.py` & `twilio-8.4.0/twilio/rest/pricing/v1/phone_number/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v1/phone_number/country.py` & `twilio-8.4.0/twilio/rest/pricing/v1/phone_number/country.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v1/voice/__init__.py` & `twilio-8.4.0/twilio/rest/pricing/v1/voice/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v1/voice/country.py` & `twilio-8.4.0/twilio/rest/pricing/v1/voice/country.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v1/voice/number.py` & `twilio-8.4.0/twilio/rest/pricing/v1/voice/number.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v2/__init__.py` & `twilio-8.4.0/twilio/rest/pricing/v2/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v2/country.py` & `twilio-8.4.0/twilio/rest/pricing/v2/country.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v2/number.py` & `twilio-8.4.0/twilio/rest/pricing/v2/number.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v2/voice/__init__.py` & `twilio-8.4.0/twilio/rest/pricing/v2/voice/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v2/voice/country.py` & `twilio-8.4.0/twilio/rest/pricing/v2/voice/country.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/pricing/v2/voice/number.py` & `twilio-8.4.0/twilio/rest/pricing/v2/voice/number.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/proxy/ProxyBase.py` & `twilio-8.4.0/twilio/rest/proxy/ProxyBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/proxy/v1/__init__.py` & `twilio-8.4.0/twilio/rest/proxy/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/proxy/v1/service/__init__.py` & `twilio-8.4.0/twilio/rest/proxy/v1/service/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/proxy/v1/service/phone_number.py` & `twilio-8.4.0/twilio/rest/proxy/v1/service/phone_number.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/proxy/v1/service/session/__init__.py` & `twilio-8.4.0/twilio/rest/proxy/v1/service/session/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/proxy/v1/service/session/interaction.py` & `twilio-8.4.0/twilio/rest/proxy/v1/service/session/interaction.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/proxy/v1/service/session/participant/__init__.py` & `twilio-8.4.0/twilio/rest/proxy/v1/service/session/participant/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/proxy/v1/service/session/participant/message_interaction.py` & `twilio-8.4.0/twilio/rest/proxy/v1/service/session/participant/message_interaction.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/proxy/v1/service/short_code.py` & `twilio-8.4.0/twilio/rest/proxy/v1/service/short_code.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/routes/RoutesBase.py` & `twilio-8.4.0/twilio/rest/routes/RoutesBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/routes/__init__.py` & `twilio-8.4.0/twilio/rest/routes/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/routes/v2/__init__.py` & `twilio-8.4.0/twilio/rest/routes/v2/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/routes/v2/phone_number.py` & `twilio-8.4.0/twilio/rest/routes/v2/phone_number.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/routes/v2/sip_domain.py` & `twilio-8.4.0/twilio/rest/routes/v2/sip_domain.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/routes/v2/trunk.py` & `twilio-8.4.0/twilio/rest/routes/v2/trunk.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/ServerlessBase.py` & `twilio-8.4.0/twilio/rest/serverless/ServerlessBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/__init__.py` & `twilio-8.4.0/twilio/rest/sync/v1/__init__.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,33 +1,33 @@
 r"""
     This code was generated by
    ___ _ _ _ _ _    _ ____    ____ ____ _    ____ ____ _  _ ____ ____ ____ ___ __   __
     |  | | | | |    | |  | __ |  | |__| | __ | __ |___ |\ | |___ |__/ |__|  | |  | |__/
     |  |_|_| | |___ | |__|    |__| |  | |    |__] |___ | \| |___ |  \ |  |  | |__| |  \
 
-    Twilio - Serverless
+    Twilio - Sync
     This is the public Twilio REST API.
 
     NOTE: This class is auto generated by OpenAPI Generator.
     https://openapi-generator.tech
     Do not edit the class manually.
 """
 
 from typing import Optional
 from twilio.base.version import Version
 from twilio.base.domain import Domain
-from twilio.rest.serverless.v1.service import ServiceList
+from twilio.rest.sync.v1.service import ServiceList
 
 
 class V1(Version):
     def __init__(self, domain: Domain):
         """
-        Initialize the V1 version of Serverless
+        Initialize the V1 version of Sync
 
-        :param domain: The Twilio.serverless domain
+        :param domain: The Twilio.sync domain
         """
         super().__init__(domain, "v1")
         self._services: Optional[ServiceList] = None
 
     @property
     def services(self) -> ServiceList:
         if self._services is None:
@@ -35,8 +35,8 @@
         return self._services
 
     def __repr__(self) -> str:
         """
         Provide a friendly representation
         :returns: Machine friendly representation
         """
-        return "<Twilio.Serverless.V1>"
+        return "<Twilio.Sync.V1>"
```

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/service/__init__.py` & `twilio-8.4.0/twilio/rest/serverless/v1/service/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/service/asset/__init__.py` & `twilio-8.4.0/twilio/rest/serverless/v1/service/asset/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/service/asset/asset_version.py` & `twilio-8.4.0/twilio/rest/serverless/v1/service/asset/asset_version.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/service/build/__init__.py` & `twilio-8.4.0/twilio/rest/serverless/v1/service/build/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/service/build/build_status.py` & `twilio-8.4.0/twilio/rest/serverless/v1/service/build/build_status.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/service/environment/__init__.py` & `twilio-8.4.0/twilio/rest/serverless/v1/service/environment/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/service/environment/deployment.py` & `twilio-8.4.0/twilio/rest/serverless/v1/service/environment/deployment.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/service/environment/log.py` & `twilio-8.4.0/twilio/rest/serverless/v1/service/environment/log.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/service/environment/variable.py` & `twilio-8.4.0/twilio/rest/serverless/v1/service/environment/variable.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/service/function/__init__.py` & `twilio-8.4.0/twilio/rest/serverless/v1/service/function/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/service/function/function_version/__init__.py` & `twilio-8.4.0/twilio/rest/serverless/v1/service/function/function_version/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/serverless/v1/service/function/function_version/function_version_content.py` & `twilio-8.4.0/twilio/rest/serverless/v1/service/function/function_version/function_version_content.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/StudioBase.py` & `twilio-8.4.0/twilio/rest/studio/StudioBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/__init__.py` & `twilio-8.4.0/twilio/rest/studio/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v1/__init__.py` & `twilio-8.4.0/twilio/rest/studio/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v1/flow/__init__.py` & `twilio-8.4.0/twilio/rest/studio/v1/flow/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v1/flow/engagement/__init__.py` & `twilio-8.4.0/twilio/rest/studio/v1/flow/engagement/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v1/flow/engagement/engagement_context.py` & `twilio-8.4.0/twilio/rest/studio/v1/flow/engagement/engagement_context.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v1/flow/engagement/step/__init__.py` & `twilio-8.4.0/twilio/rest/studio/v1/flow/engagement/step/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v1/flow/engagement/step/step_context.py` & `twilio-8.4.0/twilio/rest/studio/v1/flow/engagement/step/step_context.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v1/flow/execution/__init__.py` & `twilio-8.4.0/twilio/rest/studio/v1/flow/execution/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v1/flow/execution/execution_context.py` & `twilio-8.4.0/twilio/rest/studio/v1/flow/execution/execution_context.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v1/flow/execution/execution_step/__init__.py` & `twilio-8.4.0/twilio/rest/studio/v1/flow/execution/execution_step/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v1/flow/execution/execution_step/execution_step_context.py` & `twilio-8.4.0/twilio/rest/studio/v1/flow/execution/execution_step/execution_step_context.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v2/__init__.py` & `twilio-8.4.0/twilio/rest/studio/v2/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v2/flow/__init__.py` & `twilio-8.4.0/twilio/rest/studio/v2/flow/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v2/flow/execution/__init__.py` & `twilio-8.4.0/twilio/rest/studio/v2/flow/execution/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v2/flow/execution/execution_context.py` & `twilio-8.4.0/twilio/rest/studio/v2/flow/execution/execution_context.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v2/flow/execution/execution_step/__init__.py` & `twilio-8.4.0/twilio/rest/studio/v2/flow/execution/execution_step/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v2/flow/execution/execution_step/execution_step_context.py` & `twilio-8.4.0/twilio/rest/studio/v2/flow/execution/execution_step/execution_step_context.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v2/flow/flow_revision.py` & `twilio-8.4.0/twilio/rest/studio/v2/flow/flow_revision.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v2/flow/flow_test_user.py` & `twilio-8.4.0/twilio/rest/studio/v2/flow/flow_test_user.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/studio/v2/flow_validate.py` & `twilio-8.4.0/twilio/rest/studio/v2/flow_validate.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/SupersimBase.py` & `twilio-8.4.0/twilio/rest/supersim/SupersimBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/__init__.py` & `twilio-8.4.0/twilio/rest/supersim/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/__init__.py` & `twilio-8.4.0/twilio/rest/supersim/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/esim_profile.py` & `twilio-8.4.0/twilio/rest/supersim/v1/esim_profile.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/fleet.py` & `twilio-8.4.0/twilio/rest/supersim/v1/fleet.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/ip_command.py` & `twilio-8.4.0/twilio/rest/supersim/v1/ip_command.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/network.py` & `twilio-8.4.0/twilio/rest/supersim/v1/network.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/network_access_profile/__init__.py` & `twilio-8.4.0/twilio/rest/supersim/v1/network_access_profile/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/network_access_profile/network_access_profile_network.py` & `twilio-8.4.0/twilio/rest/supersim/v1/network_access_profile/network_access_profile_network.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/settings_update.py` & `twilio-8.4.0/twilio/rest/supersim/v1/settings_update.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/sim/__init__.py` & `twilio-8.4.0/twilio/rest/supersim/v1/sim/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/sim/billing_period.py` & `twilio-8.4.0/twilio/rest/supersim/v1/sim/billing_period.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/sim/sim_ip_address.py` & `twilio-8.4.0/twilio/rest/supersim/v1/sim/sim_ip_address.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/sms_command.py` & `twilio-8.4.0/twilio/rest/supersim/v1/sms_command.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/supersim/v1/usage_record.py` & `twilio-8.4.0/twilio/rest/supersim/v1/usage_record.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/sync/SyncBase.py` & `twilio-8.4.0/twilio/rest/sync/SyncBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/sync/v1/__init__.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/__init__.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,42 +1,42 @@
 r"""
     This code was generated by
    ___ _ _ _ _ _    _ ____    ____ ____ _    ____ ____ _  _ ____ ____ ____ ___ __   __
     |  | | | | |    | |  | __ |  | |__| | __ | __ |___ |\ | |___ |__/ |__|  | |  | |__/
     |  |_|_| | |___ | |__|    |__| |  | |    |__] |___ | \| |___ |  \ |  |  | |__| |  \
 
-    Twilio - Sync
+    Twilio - Taskrouter
     This is the public Twilio REST API.
 
     NOTE: This class is auto generated by OpenAPI Generator.
     https://openapi-generator.tech
     Do not edit the class manually.
 """
 
 from typing import Optional
 from twilio.base.version import Version
 from twilio.base.domain import Domain
-from twilio.rest.sync.v1.service import ServiceList
+from twilio.rest.taskrouter.v1.workspace import WorkspaceList
 
 
 class V1(Version):
     def __init__(self, domain: Domain):
         """
-        Initialize the V1 version of Sync
+        Initialize the V1 version of Taskrouter
 
-        :param domain: The Twilio.sync domain
+        :param domain: The Twilio.taskrouter domain
         """
         super().__init__(domain, "v1")
-        self._services: Optional[ServiceList] = None
+        self._workspaces: Optional[WorkspaceList] = None
 
     @property
-    def services(self) -> ServiceList:
-        if self._services is None:
-            self._services = ServiceList(self)
-        return self._services
+    def workspaces(self) -> WorkspaceList:
+        if self._workspaces is None:
+            self._workspaces = WorkspaceList(self)
+        return self._workspaces
 
     def __repr__(self) -> str:
         """
         Provide a friendly representation
         :returns: Machine friendly representation
         """
-        return "<Twilio.Sync.V1>"
+        return "<Twilio.Taskrouter.V1>"
```

### Comparing `twilio-8.3.0/twilio/rest/sync/v1/service/__init__.py` & `twilio-8.4.0/twilio/rest/sync/v1/service/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/sync/v1/service/document/__init__.py` & `twilio-8.4.0/twilio/rest/sync/v1/service/document/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/sync/v1/service/document/document_permission.py` & `twilio-8.4.0/twilio/rest/sync/v1/service/document/document_permission.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/sync/v1/service/sync_list/__init__.py` & `twilio-8.4.0/twilio/rest/sync/v1/service/sync_list/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/sync/v1/service/sync_list/sync_list_item.py` & `twilio-8.4.0/twilio/rest/sync/v1/service/sync_list/sync_list_item.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/sync/v1/service/sync_list/sync_list_permission.py` & `twilio-8.4.0/twilio/rest/sync/v1/service/sync_list/sync_list_permission.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/sync/v1/service/sync_map/__init__.py` & `twilio-8.4.0/twilio/rest/sync/v1/service/sync_map/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/sync/v1/service/sync_map/sync_map_item.py` & `twilio-8.4.0/twilio/rest/sync/v1/service/sync_map/sync_map_item.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/sync/v1/service/sync_map/sync_map_permission.py` & `twilio-8.4.0/twilio/rest/sync/v1/service/sync_map/sync_map_permission.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/sync/v1/service/sync_stream/__init__.py` & `twilio-8.4.0/twilio/rest/sync/v1/service/sync_stream/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/sync/v1/service/sync_stream/stream_message.py` & `twilio-8.4.0/twilio/rest/sync/v1/service/sync_stream/stream_message.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/TaskrouterBase.py` & `twilio-8.4.0/twilio/rest/taskrouter/TaskrouterBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/__init__.py` & `twilio-8.4.0/twilio/rest/trusthub/TrusthubBase.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,42 +1,43 @@
 r"""
-    This code was generated by
-   ___ _ _ _ _ _    _ ____    ____ ____ _    ____ ____ _  _ ____ ____ ____ ___ __   __
-    |  | | | | |    | |  | __ |  | |__| | __ | __ |___ |\ | |___ |__/ |__|  | |  | |__/
-    |  |_|_| | |___ | |__|    |__| |  | |    |__] |___ | \| |___ |  \ |  |  | |__| |  \
-
-    Twilio - Taskrouter
-    This is the public Twilio REST API.
-
-    NOTE: This class is auto generated by OpenAPI Generator.
-    https://openapi-generator.tech
-    Do not edit the class manually.
+  This code was generated by
+  ___ _ _ _ _ _    _ ____    ____ ____ _    ____ ____ _  _ ____ ____ ____ ___ __   __
+   |  | | | | |    | |  | __ |  | |__| | __ | __ |___ |\ | |___ |__/ |__|  | |  | |__/
+   |  |_|_| | |___ | |__|    |__| |  | |    |__] |___ | \| |___ |  \ |  |  | |__| |  \
+
+  NOTE: This class is auto generated by OpenAPI Generator.
+  https://openapi-generator.tech
+  Do not edit the class manually.
 """
 
 from typing import Optional
-from twilio.base.version import Version
+
 from twilio.base.domain import Domain
-from twilio.rest.taskrouter.v1.workspace import WorkspaceList
+from twilio.rest import Client
+from twilio.rest.trusthub.v1 import V1
 
 
-class V1(Version):
-    def __init__(self, domain: Domain):
+class TrusthubBase(Domain):
+    def __init__(self, twilio: Client):
         """
-        Initialize the V1 version of Taskrouter
+        Initialize the Trusthub Domain
 
-        :param domain: The Twilio.taskrouter domain
+        :returns: Domain for Trusthub
         """
-        super().__init__(domain, "v1")
-        self._workspaces: Optional[WorkspaceList] = None
+        super().__init__(twilio, "https://trusthub.twilio.com")
+        self._v1: Optional[V1] = None
 
     @property
-    def workspaces(self) -> WorkspaceList:
-        if self._workspaces is None:
-            self._workspaces = WorkspaceList(self)
-        return self._workspaces
+    def v1(self) -> V1:
+        """
+        :returns: Versions v1 of Trusthub
+        """
+        if self._v1 is None:
+            self._v1 = V1(self)
+        return self._v1
 
     def __repr__(self) -> str:
         """
         Provide a friendly representation
         :returns: Machine friendly representation
         """
-        return "<Twilio.Taskrouter.V1>"
+        return "<Twilio.Trusthub>"
```

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/__init__.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/activity.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/activity.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/event.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/event.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task/__init__.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task/reservation.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task/reservation.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_channel.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_channel.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_queue/__init__.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_queue/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queue_cumulative_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queue_cumulative_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queue_real_time_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queue_real_time_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queue_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queue_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queues_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/task_queue/task_queues_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/__init__.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -592,15 +592,15 @@
         is reached.
         The results are returned as a generator, so this operation is memory efficient.
 
         :param str activity_name: The `activity_name` of the Worker resources to read.
         :param str activity_sid: The `activity_sid` of the Worker resources to read.
         :param str available: Whether to return only Worker resources that are available or unavailable. Can be `true`, `1`, or `yes` to return Worker resources that are available, and `false`, or any value returns the Worker resources that are not available.
         :param str friendly_name: The `friendly_name` of the Worker resources to read.
-        :param str target_workers_expression: Filter by Workers that would match an expression on a TaskQueue. This is helpful for debugging which Workers would match a potential queue.
+        :param str target_workers_expression: Filter by Workers that would match an expression. In addition to fields in the workers' attributes, the expression can include the following worker fields: `sid`, `friendly_name`, `activity_sid`, or `activity_name`
         :param str task_queue_name: The `friendly_name` of the TaskQueue that the Workers to read are eligible for.
         :param str task_queue_sid: The SID of the TaskQueue that the Workers to read are eligible for.
         :param str ordering: Sorting parameter for Workers
         :param limit: Upper limit for the number of records to return. stream()
                       guarantees to never return more than limit.  Default is no limit
         :param page_size: Number of records to fetch per request, when not set will use
                           the default value of 50 records.  If no page_size is defined
@@ -643,15 +643,15 @@
         is reached.
         The results are returned as a generator, so this operation is memory efficient.
 
         :param str activity_name: The `activity_name` of the Worker resources to read.
         :param str activity_sid: The `activity_sid` of the Worker resources to read.
         :param str available: Whether to return only Worker resources that are available or unavailable. Can be `true`, `1`, or `yes` to return Worker resources that are available, and `false`, or any value returns the Worker resources that are not available.
         :param str friendly_name: The `friendly_name` of the Worker resources to read.
-        :param str target_workers_expression: Filter by Workers that would match an expression on a TaskQueue. This is helpful for debugging which Workers would match a potential queue.
+        :param str target_workers_expression: Filter by Workers that would match an expression. In addition to fields in the workers' attributes, the expression can include the following worker fields: `sid`, `friendly_name`, `activity_sid`, or `activity_name`
         :param str task_queue_name: The `friendly_name` of the TaskQueue that the Workers to read are eligible for.
         :param str task_queue_sid: The SID of the TaskQueue that the Workers to read are eligible for.
         :param str ordering: Sorting parameter for Workers
         :param limit: Upper limit for the number of records to return. stream()
                       guarantees to never return more than limit.  Default is no limit
         :param page_size: Number of records to fetch per request, when not set will use
                           the default value of 50 records.  If no page_size is defined
@@ -693,15 +693,15 @@
         Unlike stream(), this operation is eager and will load `limit` records into
         memory before returning.
 
         :param str activity_name: The `activity_name` of the Worker resources to read.
         :param str activity_sid: The `activity_sid` of the Worker resources to read.
         :param str available: Whether to return only Worker resources that are available or unavailable. Can be `true`, `1`, or `yes` to return Worker resources that are available, and `false`, or any value returns the Worker resources that are not available.
         :param str friendly_name: The `friendly_name` of the Worker resources to read.
-        :param str target_workers_expression: Filter by Workers that would match an expression on a TaskQueue. This is helpful for debugging which Workers would match a potential queue.
+        :param str target_workers_expression: Filter by Workers that would match an expression. In addition to fields in the workers' attributes, the expression can include the following worker fields: `sid`, `friendly_name`, `activity_sid`, or `activity_name`
         :param str task_queue_name: The `friendly_name` of the TaskQueue that the Workers to read are eligible for.
         :param str task_queue_sid: The SID of the TaskQueue that the Workers to read are eligible for.
         :param str ordering: Sorting parameter for Workers
         :param limit: Upper limit for the number of records to return. list() guarantees
                       never to return more than limit.  Default is no limit
         :param page_size: Number of records to fetch per request, when not set will use
                           the default value of 50 records.  If no page_size is defined
@@ -743,15 +743,15 @@
         Unlike stream(), this operation is eager and will load `limit` records into
         memory before returning.
 
         :param str activity_name: The `activity_name` of the Worker resources to read.
         :param str activity_sid: The `activity_sid` of the Worker resources to read.
         :param str available: Whether to return only Worker resources that are available or unavailable. Can be `true`, `1`, or `yes` to return Worker resources that are available, and `false`, or any value returns the Worker resources that are not available.
         :param str friendly_name: The `friendly_name` of the Worker resources to read.
-        :param str target_workers_expression: Filter by Workers that would match an expression on a TaskQueue. This is helpful for debugging which Workers would match a potential queue.
+        :param str target_workers_expression: Filter by Workers that would match an expression. In addition to fields in the workers' attributes, the expression can include the following worker fields: `sid`, `friendly_name`, `activity_sid`, or `activity_name`
         :param str task_queue_name: The `friendly_name` of the TaskQueue that the Workers to read are eligible for.
         :param str task_queue_sid: The SID of the TaskQueue that the Workers to read are eligible for.
         :param str ordering: Sorting parameter for Workers
         :param limit: Upper limit for the number of records to return. list() guarantees
                       never to return more than limit.  Default is no limit
         :param page_size: Number of records to fetch per request, when not set will use
                           the default value of 50 records.  If no page_size is defined
@@ -794,15 +794,15 @@
         Retrieve a single page of WorkerInstance records from the API.
         Request is executed immediately
 
         :param activity_name: The `activity_name` of the Worker resources to read.
         :param activity_sid: The `activity_sid` of the Worker resources to read.
         :param available: Whether to return only Worker resources that are available or unavailable. Can be `true`, `1`, or `yes` to return Worker resources that are available, and `false`, or any value returns the Worker resources that are not available.
         :param friendly_name: The `friendly_name` of the Worker resources to read.
-        :param target_workers_expression: Filter by Workers that would match an expression on a TaskQueue. This is helpful for debugging which Workers would match a potential queue.
+        :param target_workers_expression: Filter by Workers that would match an expression. In addition to fields in the workers' attributes, the expression can include the following worker fields: `sid`, `friendly_name`, `activity_sid`, or `activity_name`
         :param task_queue_name: The `friendly_name` of the TaskQueue that the Workers to read are eligible for.
         :param task_queue_sid: The SID of the TaskQueue that the Workers to read are eligible for.
         :param ordering: Sorting parameter for Workers
         :param page_token: PageToken provided by the API
         :param page_number: Page Number, this value is simply for client state
         :param page_size: Number of records to return, defaults to 50
 
@@ -845,15 +845,15 @@
         Asynchronously retrieve a single page of WorkerInstance records from the API.
         Request is executed immediately
 
         :param activity_name: The `activity_name` of the Worker resources to read.
         :param activity_sid: The `activity_sid` of the Worker resources to read.
         :param available: Whether to return only Worker resources that are available or unavailable. Can be `true`, `1`, or `yes` to return Worker resources that are available, and `false`, or any value returns the Worker resources that are not available.
         :param friendly_name: The `friendly_name` of the Worker resources to read.
-        :param target_workers_expression: Filter by Workers that would match an expression on a TaskQueue. This is helpful for debugging which Workers would match a potential queue.
+        :param target_workers_expression: Filter by Workers that would match an expression. In addition to fields in the workers' attributes, the expression can include the following worker fields: `sid`, `friendly_name`, `activity_sid`, or `activity_name`
         :param task_queue_name: The `friendly_name` of the TaskQueue that the Workers to read are eligible for.
         :param task_queue_sid: The SID of the TaskQueue that the Workers to read are eligible for.
         :param ordering: Sorting parameter for Workers
         :param page_token: PageToken provided by the API
         :param page_number: Page Number, this value is simply for client state
         :param page_size: Number of records to return, defaults to 50
```

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/reservation.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/reservation.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/worker_channel.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/worker_channel.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/worker_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/worker_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/workers_cumulative_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/workers_cumulative_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/workers_real_time_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/workers_real_time_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/worker/workers_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/worker/workers_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workflow/__init__.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workflow/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workflow/workflow_cumulative_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workflow/workflow_cumulative_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workflow/workflow_real_time_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workflow/workflow_real_time_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workflow/workflow_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workflow/workflow_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workspace_cumulative_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workspace_cumulative_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workspace_real_time_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workspace_real_time_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/taskrouter/v1/workspace/workspace_statistics.py` & `twilio-8.4.0/twilio/rest/taskrouter/v1/workspace/workspace_statistics.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trunking/TrunkingBase.py` & `twilio-8.4.0/twilio/rest/trunking/TrunkingBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trunking/v1/trunk/__init__.py` & `twilio-8.4.0/twilio/rest/trunking/v1/trunk/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trunking/v1/trunk/credential_list.py` & `twilio-8.4.0/twilio/rest/trunking/v1/trunk/credential_list.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trunking/v1/trunk/ip_access_control_list.py` & `twilio-8.4.0/twilio/rest/trunking/v1/trunk/ip_access_control_list.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trunking/v1/trunk/origination_url.py` & `twilio-8.4.0/twilio/rest/trunking/v1/trunk/origination_url.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trunking/v1/trunk/phone_number.py` & `twilio-8.4.0/twilio/rest/trunking/v1/trunk/phone_number.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trunking/v1/trunk/recording.py` & `twilio-8.4.0/twilio/rest/trunking/v1/trunk/recording.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/TrusthubBase.py` & `twilio-8.4.0/twilio/rest/voice/VoiceBase.py`

 * *Files 10% similar despite different names*

```diff
@@ -9,35 +9,35 @@
   Do not edit the class manually.
 """
 
 from typing import Optional
 
 from twilio.base.domain import Domain
 from twilio.rest import Client
-from twilio.rest.trusthub.v1 import V1
+from twilio.rest.voice.v1 import V1
 
 
-class TrusthubBase(Domain):
+class VoiceBase(Domain):
     def __init__(self, twilio: Client):
         """
-        Initialize the Trusthub Domain
+        Initialize the Voice Domain
 
-        :returns: Domain for Trusthub
+        :returns: Domain for Voice
         """
-        super().__init__(twilio, "https://trusthub.twilio.com")
+        super().__init__(twilio, "https://voice.twilio.com")
         self._v1: Optional[V1] = None
 
     @property
     def v1(self) -> V1:
         """
-        :returns: Versions v1 of Trusthub
+        :returns: Versions v1 of Voice
         """
         if self._v1 is None:
             self._v1 = V1(self)
         return self._v1
 
     def __repr__(self) -> str:
         """
         Provide a friendly representation
         :returns: Machine friendly representation
         """
-        return "<Twilio.Trusthub>"
+        return "<Twilio.Voice>"
```

### Comparing `twilio-8.3.0/twilio/rest/trusthub/__init__.py` & `twilio-8.4.0/twilio/rest/trusthub/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/__init__.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/customer_profiles/__init__.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/customer_profiles/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/customer_profiles/customer_profiles_channel_endpoint_assignment.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/customer_profiles/customer_profiles_channel_endpoint_assignment.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/customer_profiles/customer_profiles_entity_assignments.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/customer_profiles/customer_profiles_entity_assignments.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/customer_profiles/customer_profiles_evaluations.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/customer_profiles/customer_profiles_evaluations.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/end_user.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/end_user.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/end_user_type.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/end_user_type.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/policies.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/policies.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/supporting_document.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/supporting_document.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/supporting_document_type.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/supporting_document_type.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/trust_products/__init__.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/trust_products/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/trust_products/trust_products_channel_endpoint_assignment.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/trust_products/trust_products_channel_endpoint_assignment.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/trust_products/trust_products_entity_assignments.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/trust_products/trust_products_entity_assignments.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/trusthub/v1/trust_products/trust_products_evaluations.py` & `twilio-8.4.0/twilio/rest/trusthub/v1/trust_products/trust_products_evaluations.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/VerifyBase.py` & `twilio-8.4.0/twilio/rest/verify/VerifyBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/__init__.py` & `twilio-8.4.0/twilio/rest/verify/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/__init__.py` & `twilio-8.4.0/twilio/rest/verify/v2/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/form.py` & `twilio-8.4.0/twilio/rest/verify/v2/form.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/safelist.py` & `twilio-8.4.0/twilio/rest/verify/v2/safelist.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/__init__.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/access_token.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/access_token.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/entity/__init__.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/entity/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/entity/challenge/__init__.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/entity/challenge/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/entity/challenge/notification.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/entity/challenge/notification.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/entity/factor.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/entity/factor.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/entity/new_factor.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/entity/new_factor.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/messaging_configuration.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/messaging_configuration.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/rate_limit/__init__.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/rate_limit/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/rate_limit/bucket.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/rate_limit/bucket.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/verification.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/verification.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/verification_check.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/verification_check.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/service/webhook.py` & `twilio-8.4.0/twilio/rest/verify/v2/service/webhook.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/template.py` & `twilio-8.4.0/twilio/rest/verify/v2/template.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/verification_attempt.py` & `twilio-8.4.0/twilio/rest/verify/v2/verification_attempt.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/verify/v2/verification_attempts_summary.py` & `twilio-8.4.0/twilio/rest/verify/v2/verification_attempts_summary.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/VideoBase.py` & `twilio-8.4.0/twilio/rest/video/VideoBase.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/__init__.py` & `twilio-8.4.0/twilio/rest/video/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/__init__.py` & `twilio-8.4.0/twilio/rest/video/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/composition.py` & `twilio-8.4.0/twilio/rest/video/v1/composition.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/composition_hook.py` & `twilio-8.4.0/twilio/rest/video/v1/composition_hook.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/composition_settings.py` & `twilio-8.4.0/twilio/rest/video/v1/composition_settings.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/recording.py` & `twilio-8.4.0/twilio/rest/video/v1/recording.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/recording_settings.py` & `twilio-8.4.0/twilio/rest/video/v1/recording_settings.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/room/__init__.py` & `twilio-8.4.0/twilio/rest/video/v1/room/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/room/participant/__init__.py` & `twilio-8.4.0/twilio/rest/video/v1/room/participant/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/room/participant/anonymize.py` & `twilio-8.4.0/twilio/rest/video/v1/room/participant/anonymize.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/room/participant/published_track.py` & `twilio-8.4.0/twilio/rest/video/v1/room/participant/published_track.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/room/participant/subscribe_rules.py` & `twilio-8.4.0/twilio/rest/video/v1/room/participant/subscribe_rules.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/room/participant/subscribed_track.py` & `twilio-8.4.0/twilio/rest/video/v1/room/participant/subscribed_track.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/room/recording_rules.py` & `twilio-8.4.0/twilio/rest/video/v1/room/recording_rules.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/video/v1/room/room_recording.py` & `twilio-8.4.0/twilio/rest/video/v1/room/room_recording.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/VoiceBase.py` & `twilio-8.4.0/twilio/rest/wireless/WirelessBase.py`

 * *Files 9% similar despite different names*

```diff
@@ -9,35 +9,35 @@
   Do not edit the class manually.
 """
 
 from typing import Optional
 
 from twilio.base.domain import Domain
 from twilio.rest import Client
-from twilio.rest.voice.v1 import V1
+from twilio.rest.wireless.v1 import V1
 
 
-class VoiceBase(Domain):
+class WirelessBase(Domain):
     def __init__(self, twilio: Client):
         """
-        Initialize the Voice Domain
+        Initialize the Wireless Domain
 
-        :returns: Domain for Voice
+        :returns: Domain for Wireless
         """
-        super().__init__(twilio, "https://voice.twilio.com")
+        super().__init__(twilio, "https://wireless.twilio.com")
         self._v1: Optional[V1] = None
 
     @property
     def v1(self) -> V1:
         """
-        :returns: Versions v1 of Voice
+        :returns: Versions v1 of Wireless
         """
         if self._v1 is None:
             self._v1 = V1(self)
         return self._v1
 
     def __repr__(self) -> str:
         """
         Provide a friendly representation
         :returns: Machine friendly representation
         """
-        return "<Twilio.Voice>"
+        return "<Twilio.Wireless>"
```

### Comparing `twilio-8.3.0/twilio/rest/voice/__init__.py` & `twilio-8.4.0/twilio/rest/voice/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/v1/__init__.py` & `twilio-8.4.0/twilio/rest/voice/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/v1/archived_call.py` & `twilio-8.4.0/twilio/rest/voice/v1/archived_call.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/v1/byoc_trunk.py` & `twilio-8.4.0/twilio/rest/voice/v1/byoc_trunk.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/v1/connection_policy/__init__.py` & `twilio-8.4.0/twilio/rest/voice/v1/connection_policy/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/v1/connection_policy/connection_policy_target.py` & `twilio-8.4.0/twilio/rest/voice/v1/connection_policy/connection_policy_target.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/v1/dialing_permissions/__init__.py` & `twilio-8.4.0/twilio/rest/voice/v1/dialing_permissions/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/v1/dialing_permissions/bulk_country_update.py` & `twilio-8.4.0/twilio/rest/voice/v1/dialing_permissions/bulk_country_update.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/v1/dialing_permissions/country/__init__.py` & `twilio-8.4.0/twilio/rest/voice/v1/dialing_permissions/country/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/v1/dialing_permissions/country/highrisk_special_prefix.py` & `twilio-8.4.0/twilio/rest/voice/v1/dialing_permissions/country/highrisk_special_prefix.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/v1/dialing_permissions/settings.py` & `twilio-8.4.0/twilio/rest/voice/v1/dialing_permissions/settings.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/v1/ip_record.py` & `twilio-8.4.0/twilio/rest/voice/v1/ip_record.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/voice/v1/source_ip_mapping.py` & `twilio-8.4.0/twilio/rest/voice/v1/source_ip_mapping.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/wireless/__init__.py` & `twilio-8.4.0/twilio/rest/wireless/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/wireless/v1/__init__.py` & `twilio-8.4.0/twilio/rest/wireless/v1/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/wireless/v1/command.py` & `twilio-8.4.0/twilio/rest/wireless/v1/command.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/wireless/v1/rate_plan.py` & `twilio-8.4.0/twilio/rest/wireless/v1/rate_plan.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/wireless/v1/sim/__init__.py` & `twilio-8.4.0/twilio/rest/wireless/v1/sim/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/wireless/v1/sim/data_session.py` & `twilio-8.4.0/twilio/rest/wireless/v1/sim/data_session.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/wireless/v1/sim/usage_record.py` & `twilio-8.4.0/twilio/rest/wireless/v1/sim/usage_record.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/rest/wireless/v1/usage_record.py` & `twilio-8.4.0/twilio/rest/wireless/v1/usage_record.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/twiml/__init__.py` & `twilio-8.4.0/twilio/twiml/__init__.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/twiml/fax_response.py` & `twilio-8.4.0/twilio/twiml/fax_response.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/twiml/messaging_response.py` & `twilio-8.4.0/twilio/twiml/messaging_response.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio/twiml/voice_response.py` & `twilio-8.4.0/twilio/twiml/voice_response.py`

 * *Files identical despite different names*

### Comparing `twilio-8.3.0/twilio.egg-info/PKG-INFO` & `twilio-8.4.0/twilio.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: twilio
-Version: 8.3.0
+Version: 8.4.0
 Summary: Twilio API client and TwiML generator
 Home-page: https://github.com/twilio/twilio-python/
 Author: Twilio
 Author-email: help@twilio.com
 Keywords: twilio,twiml
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
```

### Comparing `twilio-8.3.0/twilio.egg-info/SOURCES.txt` & `twilio-8.4.0/twilio.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -351,15 +351,20 @@
 twilio/rest/notify/v1/service/__init__.py
 twilio/rest/notify/v1/service/binding.py
 twilio/rest/notify/v1/service/notification.py
 twilio/rest/numbers/NumbersBase.py
 twilio/rest/numbers/__init__.py
 twilio/rest/numbers/v1/__init__.py
 twilio/rest/numbers/v1/bulk_eligibility.py
+twilio/rest/numbers/v1/porting_bulk_portability.py
+twilio/rest/numbers/v1/porting_portability.py
 twilio/rest/numbers/v2/__init__.py
+twilio/rest/numbers/v2/hosted_number_order.py
+twilio/rest/numbers/v2/authorization_document/__init__.py
+twilio/rest/numbers/v2/authorization_document/dependent_hosted_number_order.py
 twilio/rest/numbers/v2/regulatory_compliance/__init__.py
 twilio/rest/numbers/v2/regulatory_compliance/end_user.py
 twilio/rest/numbers/v2/regulatory_compliance/end_user_type.py
 twilio/rest/numbers/v2/regulatory_compliance/regulation.py
 twilio/rest/numbers/v2/regulatory_compliance/supporting_document.py
 twilio/rest/numbers/v2/regulatory_compliance/supporting_document_type.py
 twilio/rest/numbers/v2/regulatory_compliance/bundle/__init__.py
```

