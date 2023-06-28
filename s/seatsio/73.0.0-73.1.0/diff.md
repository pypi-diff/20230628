# Comparing `tmp/seatsio-73.0.0.tar.gz` & `tmp/seatsio-73.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "seatsio-73.0.0.tar", last modified: Tue May 30 08:30:10 2023, max compression
+gzip compressed data, was "seatsio-73.1.0.tar", last modified: Wed Jun 28 08:24:13 2023, max compression
```

## Comparing `seatsio-73.0.0.tar` & `seatsio-73.1.0.tar`

### file list

```diff
@@ -1,73 +1,73 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.854128 seatsio-73.0.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1064 2023-05-30 08:30:03.000000 seatsio-73.0.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       25 2023-05-30 08:30:03.000000 seatsio-73.0.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     6677 2023-05-30 08:30:10.854128 seatsio-73.0.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     6364 2023-05-30 08:30:03.000000 seatsio-73.0.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.846127 seatsio-73.0.0/seatsio/
--rw-r--r--   0 runner    (1001) docker     (123)       97 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.850127 seatsio-73.0.0/seatsio/charts/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/charts/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5822 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/charts/chartsClient.py
--rw-r--r--   0 runner    (1001) docker     (123)      264 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/charts/chartsRequest.py
--rw-r--r--   0 runner    (1001) docker     (123)     1078 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/charts/socialDistancingRulesetsRequest.py
--rw-r--r--   0 runner    (1001) docker     (123)     1120 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/client.py
--rw-r--r--   0 runner    (1001) docker     (123)    18953 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/domain.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.850127 seatsio-73.0.0/seatsio/events/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1091 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/changeBestAvailableObjectStatusRequest.py
--rw-r--r--   0 runner    (1001) docker     (123)     2026 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/changeObjectStatusRequest.py
--rw-r--r--   0 runner    (1001) docker     (123)      410 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/channelProperties.py
--rw-r--r--   0 runner    (1001) docker     (123)     1972 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/channelsClient.py
--rw-r--r--   0 runner    (1001) docker     (123)      868 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/channelsRequests.py
--rw-r--r--   0 runner    (1001) docker     (123)      223 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/createMultipleEventsRequest.py
--rw-r--r--   0 runner    (1001) docker     (123)      741 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/createSingleEventRequest.py
--rw-r--r--   0 runner    (1001) docker     (123)      633 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/eventProperties.py
--rw-r--r--   0 runner    (1001) docker     (123)    11408 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/eventsClient.py
--rw-r--r--   0 runner    (1001) docker     (123)      123 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/extraDataRequest.py
--rw-r--r--   0 runner    (1001) docker     (123)      265 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/forSaleRequest.py
--rw-r--r--   0 runner    (1001) docker     (123)      330 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/objectProperties.py
--rw-r--r--   0 runner    (1001) docker     (123)      705 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/events/statusChangeRequest.py
--rw-r--r--   0 runner    (1001) docker     (123)     1171 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/exceptions.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.850127 seatsio-73.0.0/seatsio/holdtokens/
--rw-r--r--   0 runner    (1001) docker     (123)      837 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/holdtokens/HoldTokenClient.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/holdtokens/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5983 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/httpClient.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.850127 seatsio-73.0.0/seatsio/pagination/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/pagination/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      867 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/pagination/listableObjectsClient.py
--rw-r--r--   0 runner    (1001) docker     (123)     1013 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/pagination/lister.py
--rw-r--r--   0 runner    (1001) docker     (123)     1273 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/pagination/page.py
--rw-r--r--   0 runner    (1001) docker     (123)     1129 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/pagination/pageFetcher.py
--rw-r--r--   0 runner    (1001) docker     (123)     1328 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/pagination/pagedIterator.py
--rw-r--r--   0 runner    (1001) docker     (123)      493 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/region.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.850127 seatsio-73.0.0/seatsio/reports/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/reports/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.850127 seatsio-73.0.0/seatsio/reports/charts/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/reports/charts/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2247 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/reports/charts/chartReports.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.850127 seatsio-73.0.0/seatsio/reports/events/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/reports/events/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4590 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/reports/events/eventReports.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.854128 seatsio-73.0.0/seatsio/reports/usage/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/reports/usage/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      996 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/reports/usage/usageReports.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.854128 seatsio-73.0.0/seatsio/seasons/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/seasons/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2774 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/seasons/seasonsClient.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.854128 seatsio-73.0.0/seatsio/subaccounts/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/subaccounts/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2594 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/subaccounts/subaccountsClient.py
--rw-r--r--   0 runner    (1001) docker     (123)      305 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/util.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.854128 seatsio-73.0.0/seatsio/workspaces/
--rw-r--r--   0 runner    (1001) docker     (123)       85 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/workspaces/UpdateWorkspaceRequest.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/workspaces/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      165 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/workspaces/createWorkspaceRequest.py
--rw-r--r--   0 runner    (1001) docker     (123)     1970 2023-05-30 08:30:03.000000 seatsio-73.0.0/seatsio/workspaces/workspacesClient.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-30 08:30:10.846127 seatsio-73.0.0/seatsio.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     6677 2023-05-30 08:30:10.000000 seatsio-73.0.0/seatsio.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1805 2023-05-30 08:30:10.000000 seatsio-73.0.0/seatsio.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-30 08:30:10.000000 seatsio-73.0.0/seatsio.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       70 2023-05-30 08:30:10.000000 seatsio-73.0.0/seatsio.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       14 2023-05-30 08:30:10.000000 seatsio-73.0.0/seatsio.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-30 08:30:10.854128 seatsio-73.0.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      663 2023-05-30 08:30:08.000000 seatsio-73.0.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.753538 seatsio-73.1.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1064 2023-06-28 08:24:06.000000 seatsio-73.1.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       25 2023-06-28 08:24:06.000000 seatsio-73.1.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     6677 2023-06-28 08:24:13.753538 seatsio-73.1.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     6364 2023-06-28 08:24:06.000000 seatsio-73.1.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.749538 seatsio-73.1.0/seatsio/
+-rw-r--r--   0 runner    (1001) docker     (123)       97 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.749538 seatsio-73.1.0/seatsio/charts/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/charts/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5822 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/charts/chartsClient.py
+-rw-r--r--   0 runner    (1001) docker     (123)      264 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/charts/chartsRequest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1078 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/charts/socialDistancingRulesetsRequest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1120 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19307 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/domain.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.749538 seatsio-73.1.0/seatsio/events/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1091 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/changeBestAvailableObjectStatusRequest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2026 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/changeObjectStatusRequest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/channelProperties.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1972 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/channelsClient.py
+-rw-r--r--   0 runner    (1001) docker     (123)      868 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/channelsRequests.py
+-rw-r--r--   0 runner    (1001) docker     (123)      223 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/createMultipleEventsRequest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      855 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/createSingleEventRequest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      747 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/eventProperties.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11476 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/eventsClient.py
+-rw-r--r--   0 runner    (1001) docker     (123)      123 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/extraDataRequest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      265 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/forSaleRequest.py
+-rw-r--r--   0 runner    (1001) docker     (123)      330 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/objectProperties.py
+-rw-r--r--   0 runner    (1001) docker     (123)      705 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/events/statusChangeRequest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1171 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/exceptions.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.749538 seatsio-73.1.0/seatsio/holdtokens/
+-rw-r--r--   0 runner    (1001) docker     (123)      837 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/holdtokens/HoldTokenClient.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/holdtokens/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5983 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/httpClient.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.749538 seatsio-73.1.0/seatsio/pagination/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/pagination/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      867 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/pagination/listableObjectsClient.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1013 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/pagination/lister.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1273 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/pagination/page.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1129 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/pagination/pageFetcher.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1328 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/pagination/pagedIterator.py
+-rw-r--r--   0 runner    (1001) docker     (123)      493 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/region.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.749538 seatsio-73.1.0/seatsio/reports/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/reports/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.749538 seatsio-73.1.0/seatsio/reports/charts/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/reports/charts/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2247 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/reports/charts/chartReports.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.749538 seatsio-73.1.0/seatsio/reports/events/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/reports/events/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4590 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/reports/events/eventReports.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.753538 seatsio-73.1.0/seatsio/reports/usage/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/reports/usage/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      996 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/reports/usage/usageReports.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.753538 seatsio-73.1.0/seatsio/seasons/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/seasons/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2774 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/seasons/seasonsClient.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.753538 seatsio-73.1.0/seatsio/subaccounts/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/subaccounts/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2594 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/subaccounts/subaccountsClient.py
+-rw-r--r--   0 runner    (1001) docker     (123)      305 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/util.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.753538 seatsio-73.1.0/seatsio/workspaces/
+-rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/workspaces/UpdateWorkspaceRequest.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/workspaces/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      165 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/workspaces/createWorkspaceRequest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1970 2023-06-28 08:24:06.000000 seatsio-73.1.0/seatsio/workspaces/workspacesClient.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 08:24:13.749538 seatsio-73.1.0/seatsio.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     6677 2023-06-28 08:24:13.000000 seatsio-73.1.0/seatsio.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1805 2023-06-28 08:24:13.000000 seatsio-73.1.0/seatsio.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 08:24:13.000000 seatsio-73.1.0/seatsio.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       70 2023-06-28 08:24:13.000000 seatsio-73.1.0/seatsio.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       14 2023-06-28 08:24:13.000000 seatsio-73.1.0/seatsio.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 08:24:13.753538 seatsio-73.1.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      663 2023-06-28 08:24:10.000000 seatsio-73.1.0/setup.py
```

### Comparing `seatsio-73.0.0/LICENSE` & `seatsio-73.1.0/LICENSE`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/PKG-INFO` & `seatsio-73.1.0/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: seatsio
-Version: 73.0.0
+Version: 73.1.0
 Summary: The official Seats.io Python client library
 Home-page: https://github.com/seatsio/seatsio-python
 Author: The seats.io dev team
 Author-email: hello@seats.io
 License: MIT
 Platform: UNKNOWN
 Description-Content-Type: text/markdown
```

### Comparing `seatsio-73.0.0/README.md` & `seatsio-73.1.0/README.md`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/charts/chartsClient.py` & `seatsio-73.1.0/seatsio/charts/chartsClient.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/charts/socialDistancingRulesetsRequest.py` & `seatsio-73.1.0/seatsio/charts/socialDistancingRulesetsRequest.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/client.py` & `seatsio-73.1.0/seatsio/client.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/domain.py` & `seatsio-73.1.0/seatsio/domain.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,7 +1,9 @@
+from datetime import date
+
 from six import iteritems
 
 from seatsio.util import parse_date
 
 
 class Chart:
 
@@ -54,14 +56,16 @@
             return list(map(Category.create, lst))
 
 
 class Event:
     def __init__(self, data):
         self.id = data.get("id")
         self.key = data.get("key")
+        self.name = data.get("name")
+        self.date = None if data.get("date") is None else date.fromisoformat(data.get("date"))
         self.chart_key = data.get("chartKey")
         self.table_booking_config = TableBookingConfig.create(data.get("tableBookingConfig"))
         self.supports_best_available = data.get("supportsBestAvailable")
         self.for_sale_config = ForSaleConfig.create(data.get("forSaleConfig"))
         self.created_on = parse_date(data.get("createdOn"))
         self.updated_on = parse_date(data.get("updatedOn"))
         self.channels = Channel.createList(data.get("channels"))
@@ -294,14 +298,17 @@
         self.capacity = item_data.get("capacity")
         self.book_as_a_whole = item_data.get("bookAsAWhole")
         self.object_type = item_data.get("objectType")
         self.left_neighbour = item_data.get('leftNeighbour')
         self.right_neighbour = item_data.get('rightNeighbour')
         self.distance_to_focal_point = item_data.get('distanceToFocalPoint')
         self.num_seats = item_data.get('numSeats')
+        self.is_accessible = item_data.get("isAccessible")
+        self.is_companion_seat = item_data.get("isCompanionSeat")
+        self.has_restricted_view = item_data.get("hasRestrictedView")
 
 
 class EventReport:
     def __init__(self, response_body):
         self.items = {}
         for key, value in iteritems(response_body):
             self.items[key] = []
```

### Comparing `seatsio-73.0.0/seatsio/events/changeBestAvailableObjectStatusRequest.py` & `seatsio-73.1.0/seatsio/events/changeBestAvailableObjectStatusRequest.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/events/changeObjectStatusRequest.py` & `seatsio-73.1.0/seatsio/events/changeObjectStatusRequest.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/events/channelsClient.py` & `seatsio-73.1.0/seatsio/events/channelsClient.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/events/channelsRequests.py` & `seatsio-73.1.0/seatsio/events/channelsRequests.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/events/createSingleEventRequest.py` & `seatsio-73.1.0/seatsio/events/eventProperties.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,16 +1,16 @@
-class CreateSingleEventRequest:
-    def __init__(self, chart_key, event_key=None, table_booking_config=None,
-                 social_distancing_ruleset_key=None, object_categories=None, categories=None):
-        if chart_key:
-            self.chartKey = chart_key
+class EventProperties:
+    def __init__(self, event_key=None, name=None, date=None, table_booking_config=None, social_distancing_ruleset_key=None, object_categories=None, categories=None):
         if event_key:
             self.eventKey = event_key
+        if name:
+            self.name = name
+        if date:
+            self.date = date
         if table_booking_config is not None:
-            self.tableBookingConfig = table_booking_config.to_json()
+            self.tableBookingConfig = table_booking_config
         if social_distancing_ruleset_key is not None:
             self.socialDistancingRulesetKey = social_distancing_ruleset_key
         if object_categories is not None:
             self.objectCategories = object_categories
         if categories is not None:
             self.categories = categories
-
```

### Comparing `seatsio-73.0.0/seatsio/events/eventProperties.py` & `seatsio-73.1.0/seatsio/events/createSingleEventRequest.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,12 +1,20 @@
-class EventProperties:
-    def __init__(self, event_key=None, table_booking_config=None, social_distancing_ruleset_key=None, object_categories=None, categories=None):
+class CreateSingleEventRequest:
+    def __init__(self, chart_key, event_key=None, name=None, date=None, table_booking_config=None,
+                 social_distancing_ruleset_key=None, object_categories=None, categories=None):
+        if chart_key:
+            self.chartKey = chart_key
         if event_key:
             self.eventKey = event_key
+        if name:
+            self.name = name
+        if date:
+            self.date = date
         if table_booking_config is not None:
-            self.tableBookingConfig = table_booking_config
+            self.tableBookingConfig = table_booking_config.to_json()
         if social_distancing_ruleset_key is not None:
             self.socialDistancingRulesetKey = social_distancing_ruleset_key
         if object_categories is not None:
             self.objectCategories = object_categories
         if categories is not None:
             self.categories = categories
+
```

### Comparing `seatsio-73.0.0/seatsio/events/eventsClient.py` & `seatsio-73.1.0/seatsio/events/eventsClient.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,30 +19,30 @@
 class EventsClient(ListableObjectsClient):
 
     def __init__(self, http_client):
         ListableObjectsClient.__init__(self, http_client, event_from_json, "/events")
         self.reports = EventReports(self.http_client)
         self.channels = ChannelsClient(self.http_client)
 
-    def create(self, chart_key, event_key=None, table_booking_config=None, social_distancing_ruleset_key=None,
+    def create(self, chart_key, event_key=None, name=None, date=None, table_booking_config=None, social_distancing_ruleset_key=None,
                object_categories=None, categories=None):
         response = self.http_client.url("/events").post(
-            CreateSingleEventRequest(chart_key, event_key, table_booking_config, social_distancing_ruleset_key,
+            CreateSingleEventRequest(chart_key, event_key, name, date, table_booking_config, social_distancing_ruleset_key,
                                      object_categories, categories))
         return Event(response.json())
 
     def create_multiple(self, chart_key, events_properties):
         response = self.http_client.url("/events/actions/create-multiple").post(
             CreateMultipleEventsRequest(chart_key, events_properties))
         return Event.create_list(response.json().get("events"))
 
-    def update(self, key, chart_key=None, event_key=None, table_booking_config=None,
+    def update(self, key, chart_key=None, event_key=None, name=None, date=None, table_booking_config=None,
                social_distancing_ruleset_key=None, object_categories=None, categories=None):
         self.http_client.url("/events/{key}", key=key).post(
-            CreateSingleEventRequest(chart_key, event_key, table_booking_config, social_distancing_ruleset_key,
+            CreateSingleEventRequest(chart_key, event_key, name, date, table_booking_config, social_distancing_ruleset_key,
                                      object_categories, categories))
 
     def remove_social_distancing_ruleset_key(self, key):
         self.update(key, social_distancing_ruleset_key='')
 
     def remove_object_categories(self, key):
         self.update(key, object_categories={})
```

### Comparing `seatsio-73.0.0/seatsio/events/statusChangeRequest.py` & `seatsio-73.1.0/seatsio/events/statusChangeRequest.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/exceptions.py` & `seatsio-73.1.0/seatsio/exceptions.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/holdtokens/HoldTokenClient.py` & `seatsio-73.1.0/seatsio/holdtokens/HoldTokenClient.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/httpClient.py` & `seatsio-73.1.0/seatsio/httpClient.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/pagination/listableObjectsClient.py` & `seatsio-73.1.0/seatsio/pagination/listableObjectsClient.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/pagination/lister.py` & `seatsio-73.1.0/seatsio/pagination/lister.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/pagination/page.py` & `seatsio-73.1.0/seatsio/pagination/page.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/pagination/pageFetcher.py` & `seatsio-73.1.0/seatsio/pagination/pageFetcher.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/pagination/pagedIterator.py` & `seatsio-73.1.0/seatsio/pagination/pagedIterator.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/reports/charts/chartReports.py` & `seatsio-73.1.0/seatsio/reports/charts/chartReports.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/reports/events/eventReports.py` & `seatsio-73.1.0/seatsio/reports/events/eventReports.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/reports/usage/usageReports.py` & `seatsio-73.1.0/seatsio/reports/usage/usageReports.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/seasons/seasonsClient.py` & `seatsio-73.1.0/seatsio/seasons/seasonsClient.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/subaccounts/subaccountsClient.py` & `seatsio-73.1.0/seatsio/subaccounts/subaccountsClient.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio/workspaces/workspacesClient.py` & `seatsio-73.1.0/seatsio/workspaces/workspacesClient.py`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/seatsio.egg-info/PKG-INFO` & `seatsio-73.1.0/seatsio.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: seatsio
-Version: 73.0.0
+Version: 73.1.0
 Summary: The official Seats.io Python client library
 Home-page: https://github.com/seatsio/seatsio-python
 Author: The seats.io dev team
 Author-email: hello@seats.io
 License: MIT
 Platform: UNKNOWN
 Description-Content-Type: text/markdown
```

### Comparing `seatsio-73.0.0/seatsio.egg-info/SOURCES.txt` & `seatsio-73.1.0/seatsio.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `seatsio-73.0.0/setup.py` & `seatsio-73.1.0/setup.py`

 * *Files 20% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup, find_packages
 
 with open('README.md') as f:
     readme = f.read()
 
 setup(
     name='seatsio',
-    version='v73.0.0',
+    version='v73.1.0',
     description='The official Seats.io Python client library',
     author='The seats.io dev team',
     author_email='hello@seats.io',
     url='https://github.com/seatsio/seatsio-python',
     license="MIT",
     long_description=open('README.md').read(),
     long_description_content_type="text/markdown",
```

