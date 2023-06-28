# Comparing `tmp/alice-onboarding-2.0.0.tar.gz` & `tmp/alice-onboarding-3.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "alice-onboarding-2.0.0.tar", last modified: Mon May 15 10:44:29 2023, max compression
+gzip compressed data, was "alice-onboarding-3.0.0.tar", last modified: Wed Jun 28 07:55:15 2023, max compression
```

## Comparing `alice-onboarding-2.0.0.tar` & `alice-onboarding-3.0.0.tar`

### file list

```diff
@@ -1,127 +1,128 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.091727 alice-onboarding-2.0.0/
--rw-r--r--   0 runner    (1001) docker     (123)       37 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       22 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     4506 2023-05-15 10:44:29.091727 alice-onboarding-2.0.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3697 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.083726 alice-onboarding-2.0.0/alice/
--rw-r--r--   0 runner    (1001) docker     (123)        5 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/VERSION
--rw-r--r--   0 runner    (1001) docker     (123)      213 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.083726 alice-onboarding-2.0.0/alice/auth/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/auth/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3379 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/auth/auth.py
--rw-r--r--   0 runner    (1001) docker     (123)     5522 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/auth/auth_client.py
--rw-r--r--   0 runner    (1001) docker     (123)      740 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/auth/auth_errors.py
--rw-r--r--   0 runner    (1001) docker     (123)     2488 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/auth/cached_token_stack.py
--rw-r--r--   0 runner    (1001) docker     (123)      678 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/auth/token_tools.py
--rw-r--r--   0 runner    (1001) docker     (123)      772 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/config.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.083726 alice-onboarding-2.0.0/alice/onboarding/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.083726 alice-onboarding-2.0.0/alice/onboarding/enums/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/enums/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)       83 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/enums/certificate_locale.py
--rw-r--r--   0 runner    (1001) docker     (123)      114 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/enums/decision.py
--rw-r--r--   0 runner    (1001) docker     (123)      114 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/enums/document_side.py
--rw-r--r--   0 runner    (1001) docker     (123)       92 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/enums/document_source.py
--rw-r--r--   0 runner    (1001) docker     (123)      227 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/enums/document_type.py
--rw-r--r--   0 runner    (1001) docker     (123)      113 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/enums/duplicates_resource_type.py
--rw-r--r--   0 runner    (1001) docker     (123)       95 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/enums/match_case.py
--rw-r--r--   0 runner    (1001) docker     (123)       95 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/enums/version.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.083726 alice-onboarding-2.0.0/alice/onboarding/models/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      464 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/bounding_box.py
--rw-r--r--   0 runner    (1001) docker     (123)      222 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/device_info.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.083726 alice-onboarding-2.0.0/alice/onboarding/models/report/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.083726 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      473 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/check.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.087726 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      397 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/authentic_nfc_chip_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      343 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/checked_info_code_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      363 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/coherent_document_dates_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      445 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/consistent_document_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      338 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/expected_document_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      354 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/face_in_document_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      366 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/face_matching_document_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      340 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/not_a_printed_document_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      362 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/not_a_screen_document_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      368 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/not_a_synthetic_document_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      396 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/uncompromised_document_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      310 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/document/unexpired_document_check.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.087726 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/field/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/field/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      301 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/field/cheked_field_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      337 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/field/complete_mrz_name_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      354 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/field/consistent_field_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      333 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/field/expected_field_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      255 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/field/over_18_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      294 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/field/unexpired_date_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      296 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/field/valid_date_format_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      303 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/field/valid_date_range_check.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.087726 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/selfie/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/selfie/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      320 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/selfie/liveness_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      332 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/selfie/only_one_face_check.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.087726 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/summary/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/summary/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      372 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/summary/only_one_device_check.py
--rw-r--r--   0 runner    (1001) docker     (123)      360 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/checks/summary/only_one_ip_check.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.087726 alice-onboarding-2.0.0/alice/onboarding/models/report/compliance/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/compliance/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      474 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/compliance/device_out.py
--rw-r--r--   0 runner    (1001) docker     (123)      376 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/compliance/domain_events_report.py
--rw-r--r--   0 runner    (1001) docker     (123)      675 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/compliance/user_event_out.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.087726 alice-onboarding-2.0.0/alice/onboarding/models/report/document/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/document/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1926 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/document/document_field.py
--rw-r--r--   0 runner    (1001) docker     (123)     3071 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/document/document_report.py
--rw-r--r--   0 runner    (1001) docker     (123)      534 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/document/document_report_meta.py
--rw-r--r--   0 runner    (1001) docker     (123)      114 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/document/document_side.py
--rw-r--r--   0 runner    (1001) docker     (123)     1672 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/document/document_side_report.py
--rw-r--r--   0 runner    (1001) docker     (123)      386 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/document/document_side_report_meta.py
--rw-r--r--   0 runner    (1001) docker     (123)      511 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/document/document_type.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.087726 alice-onboarding-2.0.0/alice/onboarding/models/report/face_matching/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/face_matching/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1028 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/face_matching/face_matching.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.087726 alice-onboarding-2.0.0/alice/onboarding/models/report/other_trusted_document/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/other_trusted_document/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      861 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/other_trusted_document/other_trusted_document_report.py
--rw-r--r--   0 runner    (1001) docker     (123)      403 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/other_trusted_document/other_trusted_document_report_meta.py
--rw-r--r--   0 runner    (1001) docker     (123)     1669 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/report.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.091727 alice-onboarding-2.0.0/alice/onboarding/models/report/selfie/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/selfie/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1810 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/selfie/selfie_report.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.091727 alice-onboarding-2.0.0/alice/onboarding/models/report/shared/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/shared/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      464 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/shared/bounding_box.py
--rw-r--r--   0 runner    (1001) docker     (123)      515 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/shared/href.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.091727 alice-onboarding-2.0.0/alice/onboarding/models/report/summary/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/summary/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      277 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/summary/external_user_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     1349 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/report/summary/report_summary.py
--rw-r--r--   0 runner    (1001) docker     (123)      194 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/models/user_info.py
--rw-r--r--   0 runner    (1001) docker     (123)    57159 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/onboarding.py
--rw-r--r--   0 runner    (1001) docker     (123)    64391 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/onboarding_client.py
--rw-r--r--   0 runner    (1001) docker     (123)     1203 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/onboarding_errors.py
--rw-r--r--   0 runner    (1001) docker     (123)     1455 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/onboarding/tools.py
--rw-r--r--   0 runner    (1001) docker     (123)     2198 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/public_api.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.091727 alice-onboarding-2.0.0/alice/sandbox/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/sandbox/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     6251 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/sandbox/sandbox.py
--rw-r--r--   0 runner    (1001) docker     (123)     4612 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/sandbox/sandbox_client.py
--rw-r--r--   0 runner    (1001) docker     (123)      933 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/sandbox/sandbox_errors.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.091727 alice-onboarding-2.0.0/alice/webhooks/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/webhooks/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2035 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/webhooks/webhook.py
--rw-r--r--   0 runner    (1001) docker     (123)    11796 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/webhooks/webhooks.py
--rw-r--r--   0 runner    (1001) docker     (123)    11234 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/alice/webhooks/webhooks_client.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-15 10:44:29.091727 alice-onboarding-2.0.0/alice_onboarding.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     4506 2023-05-15 10:44:29.000000 alice-onboarding-2.0.0/alice_onboarding.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     5061 2023-05-15 10:44:29.000000 alice-onboarding-2.0.0/alice_onboarding.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-15 10:44:29.000000 alice-onboarding-2.0.0/alice_onboarding.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-15 10:44:29.000000 alice-onboarding-2.0.0/alice_onboarding.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (123)       88 2023-05-15 10:44:29.000000 alice-onboarding-2.0.0/alice_onboarding.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        6 2023-05-15 10:44:29.000000 alice-onboarding-2.0.0/alice_onboarding.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      449 2023-05-15 10:44:29.091727 alice-onboarding-2.0.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1349 2023-05-15 10:44:23.000000 alice-onboarding-2.0.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.521479 alice-onboarding-3.0.0/
+-rw-r--r--   0 runner    (1001) docker     (123)       37 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       22 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     4506 2023-06-28 07:55:15.521479 alice-onboarding-3.0.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3697 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.505478 alice-onboarding-3.0.0/alice/
+-rw-r--r--   0 runner    (1001) docker     (123)        5 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/VERSION
+-rw-r--r--   0 runner    (1001) docker     (123)      213 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.505478 alice-onboarding-3.0.0/alice/auth/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/auth/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3379 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/auth/auth.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5522 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/auth/auth_client.py
+-rw-r--r--   0 runner    (1001) docker     (123)      740 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/auth/auth_errors.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2488 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/auth/cached_token_stack.py
+-rw-r--r--   0 runner    (1001) docker     (123)      678 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/auth/token_tools.py
+-rw-r--r--   0 runner    (1001) docker     (123)      772 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/config.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.509478 alice-onboarding-3.0.0/alice/onboarding/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.509478 alice-onboarding-3.0.0/alice/onboarding/enums/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/enums/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)       83 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/enums/certificate_locale.py
+-rw-r--r--   0 runner    (1001) docker     (123)      114 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/enums/decision.py
+-rw-r--r--   0 runner    (1001) docker     (123)      114 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/enums/document_side.py
+-rw-r--r--   0 runner    (1001) docker     (123)       92 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/enums/document_source.py
+-rw-r--r--   0 runner    (1001) docker     (123)      227 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/enums/document_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)      113 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/enums/duplicates_resource_type.py
+-rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/enums/match_case.py
+-rw-r--r--   0 runner    (1001) docker     (123)      191 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/enums/user_state.py
+-rw-r--r--   0 runner    (1001) docker     (123)       95 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/enums/version.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.509478 alice-onboarding-3.0.0/alice/onboarding/models/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      464 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/bounding_box.py
+-rw-r--r--   0 runner    (1001) docker     (123)      222 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/device_info.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.509478 alice-onboarding-3.0.0/alice/onboarding/models/report/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.509478 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      473 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/check.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.513479 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      397 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/authentic_nfc_chip_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      343 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/checked_info_code_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      363 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/coherent_document_dates_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/consistent_document_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      338 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/expected_document_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      354 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/face_in_document_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      366 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/face_matching_document_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      340 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/not_a_printed_document_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      362 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/not_a_screen_document_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      368 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/not_a_synthetic_document_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      396 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/uncompromised_document_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      310 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/document/unexpired_document_check.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.513479 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/field/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/field/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      301 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/field/cheked_field_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      337 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/field/complete_mrz_name_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      354 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/field/consistent_field_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      333 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/field/expected_field_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      255 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/field/over_18_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      294 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/field/unexpired_date_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      296 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/field/valid_date_format_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      303 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/field/valid_date_range_check.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.513479 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/selfie/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/selfie/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      320 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/selfie/liveness_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      332 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/selfie/only_one_face_check.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.513479 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/summary/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/summary/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      372 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/summary/only_one_device_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)      360 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/checks/summary/only_one_ip_check.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.517479 alice-onboarding-3.0.0/alice/onboarding/models/report/compliance/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/compliance/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      474 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/compliance/device_out.py
+-rw-r--r--   0 runner    (1001) docker     (123)      376 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/compliance/domain_events_report.py
+-rw-r--r--   0 runner    (1001) docker     (123)      675 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/compliance/user_event_out.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.517479 alice-onboarding-3.0.0/alice/onboarding/models/report/document/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/document/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1926 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/document/document_field.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3071 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/document/document_report.py
+-rw-r--r--   0 runner    (1001) docker     (123)      534 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/document/document_report_meta.py
+-rw-r--r--   0 runner    (1001) docker     (123)      114 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/document/document_side.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1672 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/document/document_side_report.py
+-rw-r--r--   0 runner    (1001) docker     (123)      386 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/document/document_side_report_meta.py
+-rw-r--r--   0 runner    (1001) docker     (123)      511 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/document/document_type.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.517479 alice-onboarding-3.0.0/alice/onboarding/models/report/face_matching/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/face_matching/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1028 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/face_matching/face_matching.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.517479 alice-onboarding-3.0.0/alice/onboarding/models/report/other_trusted_document/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/other_trusted_document/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      861 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/other_trusted_document/other_trusted_document_report.py
+-rw-r--r--   0 runner    (1001) docker     (123)      403 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/other_trusted_document/other_trusted_document_report_meta.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1669 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/report.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.517479 alice-onboarding-3.0.0/alice/onboarding/models/report/selfie/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/selfie/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1810 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/selfie/selfie_report.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.517479 alice-onboarding-3.0.0/alice/onboarding/models/report/shared/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/shared/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      464 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/shared/bounding_box.py
+-rw-r--r--   0 runner    (1001) docker     (123)      515 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/shared/href.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.517479 alice-onboarding-3.0.0/alice/onboarding/models/report/summary/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/summary/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      277 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/summary/external_user_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1349 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/report/summary/report_summary.py
+-rw-r--r--   0 runner    (1001) docker     (123)      194 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/models/user_info.py
+-rw-r--r--   0 runner    (1001) docker     (123)    56105 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/onboarding.py
+-rw-r--r--   0 runner    (1001) docker     (123)    63146 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/onboarding_client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1203 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/onboarding_errors.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1455 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/onboarding/tools.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2198 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/public_api.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.517479 alice-onboarding-3.0.0/alice/sandbox/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/sandbox/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6251 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/sandbox/sandbox.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4612 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/sandbox/sandbox_client.py
+-rw-r--r--   0 runner    (1001) docker     (123)      933 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/sandbox/sandbox_errors.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.517479 alice-onboarding-3.0.0/alice/webhooks/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/webhooks/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2035 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/webhooks/webhook.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11796 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/webhooks/webhooks.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11234 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/alice/webhooks/webhooks_client.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 07:55:15.521479 alice-onboarding-3.0.0/alice_onboarding.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     4506 2023-06-28 07:55:15.000000 alice-onboarding-3.0.0/alice_onboarding.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     5098 2023-06-28 07:55:15.000000 alice-onboarding-3.0.0/alice_onboarding.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:55:15.000000 alice-onboarding-3.0.0/alice_onboarding.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 07:55:15.000000 alice-onboarding-3.0.0/alice_onboarding.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (123)       88 2023-06-28 07:55:15.000000 alice-onboarding-3.0.0/alice_onboarding.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 07:55:15.000000 alice-onboarding-3.0.0/alice_onboarding.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      449 2023-06-28 07:55:15.521479 alice-onboarding-3.0.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1349 2023-06-28 07:55:11.000000 alice-onboarding-3.0.0/setup.py
```

### Comparing `alice-onboarding-2.0.0/PKG-INFO` & `alice-onboarding-3.0.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: alice-onboarding
-Version: 2.0.0
+Version: 3.0.0
 Summary: Alice Onboarding Python SDK
 Home-page: https://github.com/alice-biometrics/onboarding-python
 Author: Alice Biometrics
 Author-email: support@alicebiometrics.com
 License: Alice Copyright
 Keywords: onboarding,biometrics,kyc,alice
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `alice-onboarding-2.0.0/README.md` & `alice-onboarding-3.0.0/README.md`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/auth/auth.py` & `alice-onboarding-3.0.0/alice/auth/auth.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/auth/auth_client.py` & `alice-onboarding-3.0.0/alice/auth/auth_client.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/auth/auth_errors.py` & `alice-onboarding-3.0.0/alice/auth/auth_errors.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/auth/cached_token_stack.py` & `alice-onboarding-3.0.0/alice/auth/cached_token_stack.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/auth/token_tools.py` & `alice-onboarding-3.0.0/alice/auth/token_tools.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/config.py` & `alice-onboarding-3.0.0/alice/config.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/models/report/compliance/user_event_out.py` & `alice-onboarding-3.0.0/alice/onboarding/models/report/compliance/user_event_out.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/models/report/document/document_field.py` & `alice-onboarding-3.0.0/alice/onboarding/models/report/document/document_field.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/models/report/document/document_report.py` & `alice-onboarding-3.0.0/alice/onboarding/models/report/document/document_report.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/models/report/document/document_report_meta.py` & `alice-onboarding-3.0.0/alice/onboarding/models/report/document/document_report_meta.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/models/report/document/document_side_report.py` & `alice-onboarding-3.0.0/alice/onboarding/models/report/document/document_side_report.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/models/report/face_matching/face_matching.py` & `alice-onboarding-3.0.0/alice/onboarding/models/report/face_matching/face_matching.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/models/report/other_trusted_document/other_trusted_document_report.py` & `alice-onboarding-3.0.0/alice/onboarding/models/report/other_trusted_document/other_trusted_document_report.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/models/report/report.py` & `alice-onboarding-3.0.0/alice/onboarding/models/report/report.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/models/report/selfie/selfie_report.py` & `alice-onboarding-3.0.0/alice/onboarding/models/report/selfie/selfie_report.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/models/report/shared/href.py` & `alice-onboarding-3.0.0/alice/onboarding/models/report/shared/href.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/models/report/summary/report_summary.py` & `alice-onboarding-3.0.0/alice/onboarding/models/report/summary/report_summary.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/onboarding.py` & `alice-onboarding-3.0.0/alice/onboarding/onboarding.py`

 * *Files 1% similar despite different names*

```diff
@@ -10,14 +10,15 @@
 from alice.onboarding.enums.certificate_locale import CertificateLocale
 from alice.onboarding.enums.decision import Decision
 from alice.onboarding.enums.document_side import DocumentSide
 from alice.onboarding.enums.document_source import DocumentSource
 from alice.onboarding.enums.document_type import DocumentType
 from alice.onboarding.enums.duplicates_resource_type import DuplicatesResourceType
 from alice.onboarding.enums.match_case import MatchCase
+from alice.onboarding.enums.user_state import UserState
 from alice.onboarding.enums.version import Version
 from alice.onboarding.models.bounding_box import BoundingBox
 from alice.onboarding.models.device_info import DeviceInfo
 from alice.onboarding.models.report.report import Report
 from alice.onboarding.models.user_info import UserInfo
 from alice.onboarding.onboarding_client import OnboardingClient
 from alice.onboarding.onboarding_errors import OnboardingError
@@ -1690,79 +1691,44 @@
         else:
             return Failure(
                 OnboardingError.from_response(
                     operation="get_duplicates_searches", response=response
                 )
             )
 
-    def accept_user(
-        self, user_id: str, operator: str = "auto", verbose: bool = False
-    ) -> Result[bool, OnboardingError]:
-        """
-        Mark a user state as ACCEPTED
-        Parameters
-        ----------
-        user_id
-            User identifier
-        operator
-            Who is accepting the user
-        verbose
-            Used for print service response as well as the time elapsed
-        Returns
-        -------
-            A Result where if the operation is successful it returns True.
-            Otherwise, it returns an OnboardingError.
-        """
-        verbose = self.verbose or verbose
-        response = self.onboarding_client.accept_user(
-            user_id=user_id, operator=operator, verbose=verbose
-        ).unwrap_or_return()
-
-        if response.status_code == 200:
-            return isSuccess
-        else:
-            return Failure(
-                OnboardingError.from_response(
-                    operation="accept_user", response=response
-                )
-            )
-
-    def reject_user(
+    def update_user_state(
         self,
         user_id: str,
-        rejection_reasons: Optional[List[Dict[str, str]]] = None,
+        user_state: UserState,
         operator: str = "auto",
         verbose: bool = False,
     ) -> Result[bool, OnboardingError]:
         """
-        Mark a user state as REJECTED
+        Update the state of a user
         Parameters
         ----------
+        user_state
+            New State of the user
         user_id
             User identifier
-        rejection_reasons
-            List of rejection reasons
         operator
-            Who is rejecting the user
+            Who is accepting the user
         verbose
             Used for print service response as well as the time elapsed
         Returns
         -------
             A Result where if the operation is successful it returns True.
             Otherwise, it returns an OnboardingError.
         """
         verbose = self.verbose or verbose
-        response = self.onboarding_client.reject_user(
-            user_id=user_id,
-            rejection_reasons=rejection_reasons,
-            operator=operator,
-            verbose=verbose,
+        response = self.onboarding_client.update_user_state(
+            user_id=user_id, user_state=user_state, operator=operator, verbose=verbose
         ).unwrap_or_return()
 
         if response.status_code == 200:
             return isSuccess
         else:
             return Failure(
                 OnboardingError.from_response(
-                    operation="accept_user", response=response
+                    operation="update_user_state", response=response
                 )
             )
```

### Comparing `alice-onboarding-2.0.0/alice/onboarding/onboarding_client.py` & `alice-onboarding-3.0.0/alice/onboarding/onboarding_client.py`

 * *Files 0% similar despite different names*

```diff
@@ -12,14 +12,15 @@
 from alice.onboarding.enums.certificate_locale import CertificateLocale
 from alice.onboarding.enums.decision import Decision
 from alice.onboarding.enums.document_side import DocumentSide
 from alice.onboarding.enums.document_source import DocumentSource
 from alice.onboarding.enums.document_type import DocumentType
 from alice.onboarding.enums.duplicates_resource_type import DuplicatesResourceType
 from alice.onboarding.enums.match_case import MatchCase
+from alice.onboarding.enums.user_state import UserState
 from alice.onboarding.enums.version import Version
 from alice.onboarding.models.bounding_box import BoundingBox
 from alice.onboarding.models.device_info import DeviceInfo
 from alice.onboarding.models.user_info import UserInfo
 from alice.onboarding.onboarding_errors import OnboardingError
 from alice.onboarding.tools import print_intro, print_response, print_token, timeit
 
@@ -1944,99 +1945,57 @@
         except requests.exceptions.Timeout:
             return Failure(OnboardingError.timeout(operation="get_duplicates_searches"))
         print_response(response=response, verbose=verbose)
 
         return Success(response)
 
     @timeit
-    def accept_user(
-        self, user_id: str, operator: str = "auto", verbose: bool = False
-    ) -> Result[Response, Error]:
-        """
-        Mark a user state as ACCEPTED
-
-        Parameters
-        ----------
-        user_id
-            User identifier
-        operator
-            Who is accepting the user
-        verbose
-            Used for print service response as well as the time elapsed
-
-
-        Returns
-        -------
-            A Response object [requests library]
-        """
-        print_intro("accept_user", verbose=verbose)
-
-        backend_user_token = self.auth.create_backend_token(
-            user_id=user_id
-        ).unwrap_or_return()
-        print_token("backend_token_with_user", backend_user_token, verbose=verbose)
-
-        headers = self._auth_headers(backend_user_token)
-        try:
-            response = requests.post(
-                f"{self.url}/user/state/accept",
-                headers=headers,
-                json={
-                    "operator": operator,
-                },
-                timeout=self.timeout,
-            )
-        except requests.exceptions.Timeout:
-            return Failure(OnboardingError.timeout(operation="accept_user"))
-
-        print_response(response=response, verbose=verbose)
-
-        return Success(response)
-
-    @timeit
-    def reject_user(
+    def update_user_state(
         self,
         user_id: str,
-        rejection_reasons: Optional[List[Dict[str, str]]] = None,
+        user_state: UserState,
         operator: str = "auto",
         verbose: bool = False,
     ) -> Result[Response, Error]:
         """
-        Mark a user state as REJECTED
+        Update the state of a user
 
         Parameters
         ----------
+        user_state
+            New State of the user
         user_id
             User identifier
-        rejection_reasons
-            List of rejection reasons
         operator
-            Who is rejecting the user
+            Who is accepting the user
         verbose
             Used for print service response as well as the time elapsed
 
 
         Returns
         -------
             A Response object [requests library]
         """
-        print_intro("accept_user", verbose=verbose)
+        print_intro("update_user_state", verbose=verbose)
 
         backend_user_token = self.auth.create_backend_token(
             user_id=user_id
         ).unwrap_or_return()
         print_token("backend_token_with_user", backend_user_token, verbose=verbose)
 
         headers = self._auth_headers(backend_user_token)
         try:
-            response = requests.post(
-                f"{self.url}/user/state/reject",
+            response = requests.patch(
+                f"{self.url}/user/state",
                 headers=headers,
-                json={"operator": operator, "rejection_reasons": rejection_reasons},
+                json={
+                    "state": user_state.value,
+                    "operator": operator,
+                },
                 timeout=self.timeout,
             )
         except requests.exceptions.Timeout:
-            return Failure(OnboardingError.timeout(operation="accept_user"))
+            return Failure(OnboardingError.timeout(operation="update_user_state"))
 
         print_response(response=response, verbose=verbose)
 
         return Success(response)
```

### Comparing `alice-onboarding-2.0.0/alice/onboarding/onboarding_errors.py` & `alice-onboarding-3.0.0/alice/onboarding/onboarding_errors.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/onboarding/tools.py` & `alice-onboarding-3.0.0/alice/onboarding/tools.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/public_api.py` & `alice-onboarding-3.0.0/alice/public_api.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/sandbox/sandbox.py` & `alice-onboarding-3.0.0/alice/sandbox/sandbox.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/sandbox/sandbox_client.py` & `alice-onboarding-3.0.0/alice/sandbox/sandbox_client.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/sandbox/sandbox_errors.py` & `alice-onboarding-3.0.0/alice/sandbox/sandbox_errors.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/webhooks/webhook.py` & `alice-onboarding-3.0.0/alice/webhooks/webhook.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/webhooks/webhooks.py` & `alice-onboarding-3.0.0/alice/webhooks/webhooks.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice/webhooks/webhooks_client.py` & `alice-onboarding-3.0.0/alice/webhooks/webhooks_client.py`

 * *Files identical despite different names*

### Comparing `alice-onboarding-2.0.0/alice_onboarding.egg-info/PKG-INFO` & `alice-onboarding-3.0.0/alice_onboarding.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: alice-onboarding
-Version: 2.0.0
+Version: 3.0.0
 Summary: Alice Onboarding Python SDK
 Home-page: https://github.com/alice-biometrics/onboarding-python
 Author: Alice Biometrics
 Author-email: support@alicebiometrics.com
 License: Alice Copyright
 Keywords: onboarding,biometrics,kyc,alice
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `alice-onboarding-2.0.0/alice_onboarding.egg-info/SOURCES.txt` & `alice-onboarding-3.0.0/alice_onboarding.egg-info/SOURCES.txt`

 * *Files 0% similar despite different names*

```diff
@@ -22,14 +22,15 @@
 alice/onboarding/enums/certificate_locale.py
 alice/onboarding/enums/decision.py
 alice/onboarding/enums/document_side.py
 alice/onboarding/enums/document_source.py
 alice/onboarding/enums/document_type.py
 alice/onboarding/enums/duplicates_resource_type.py
 alice/onboarding/enums/match_case.py
+alice/onboarding/enums/user_state.py
 alice/onboarding/enums/version.py
 alice/onboarding/models/__init__.py
 alice/onboarding/models/bounding_box.py
 alice/onboarding/models/device_info.py
 alice/onboarding/models/user_info.py
 alice/onboarding/models/report/__init__.py
 alice/onboarding/models/report/report.py
```

### Comparing `alice-onboarding-2.0.0/setup.py` & `alice-onboarding-3.0.0/setup.py`

 * *Files identical despite different names*

