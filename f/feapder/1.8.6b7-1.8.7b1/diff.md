# Comparing `tmp/feapder-1.8.6b7.tar.gz` & `tmp/feapder-1.8.7b1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "feapder-1.8.6b7.tar", last modified: Mon May 22 04:00:03 2023, max compression
+gzip compressed data, was "feapder-1.8.7b1.tar", last modified: Wed Jun 28 13:19:58 2023, max compression
```

## Comparing `feapder-1.8.6b7.tar` & `feapder-1.8.7b1.tar`

### file list

```diff
@@ -1,220 +1,230 @@
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.578266 feapder-1.8.6b7/
--rw-r--r--   0 liubo      (501) staff       (20)     1102 2021-08-04 13:29:34.000000 feapder-1.8.6b7/LICENSE
--rw-r--r--   0 liubo      (501) staff       (20)      231 2021-08-12 03:51:27.000000 feapder-1.8.6b7/MANIFEST.in
--rw-r--r--   0 liubo      (501) staff       (20)     4568 2023-05-22 04:00:03.577899 feapder-1.8.6b7/PKG-INFO
--rw-r--r--   0 liubo      (501) staff       (20)     4144 2023-03-30 02:09:37.000000 feapder-1.8.6b7/README.md
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.378508 feapder-1.8.6b7/feapder/
--rw-r--r--   0 liubo      (501) staff       (20)       11 2023-05-22 03:59:20.000000 feapder-1.8.6b7/feapder/VERSION
--rw-r--r--   0 liubo      (501) staff       (20)      815 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/__init__.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.383382 feapder-1.8.6b7/feapder/buffer/
--rw-r--r--   0 liubo      (501) staff       (20)      136 2021-08-04 13:29:34.000000 feapder-1.8.6b7/feapder/buffer/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)    14141 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/buffer/item_buffer.py
--rw-r--r--   0 liubo      (501) staff       (20)     5356 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/buffer/request_buffer.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.386927 feapder-1.8.6b7/feapder/commands/
--rw-r--r--   0 liubo      (501) staff       (20)        0 2021-02-07 13:26:42.000000 feapder-1.8.6b7/feapder/commands/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     3824 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/commands/cmdline.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.394696 feapder-1.8.6b7/feapder/commands/create/
--rw-r--r--   0 liubo      (501) staff       (20)      543 2021-09-02 10:23:23.000000 feapder-1.8.6b7/feapder/commands/create/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)      975 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/commands/create/create_cookies.py
--rw-r--r--   0 liubo      (501) staff       (20)      670 2021-02-08 06:31:07.000000 feapder-1.8.6b7/feapder/commands/create/create_init.py
--rw-r--r--   0 liubo      (501) staff       (20)     6004 2022-09-07 03:39:37.000000 feapder-1.8.6b7/feapder/commands/create/create_item.py
--rw-r--r--   0 liubo      (501) staff       (20)     1366 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/commands/create/create_json.py
--rw-r--r--   0 liubo      (501) staff       (20)     1106 2021-09-02 10:23:23.000000 feapder-1.8.6b7/feapder/commands/create/create_params.py
--rw-r--r--   0 liubo      (501) staff       (20)     1360 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/commands/create/create_project.py
--rw-r--r--   0 liubo      (501) staff       (20)      693 2021-08-04 13:29:34.000000 feapder-1.8.6b7/feapder/commands/create/create_setting.py
--rw-r--r--   0 liubo      (501) staff       (20)     3648 2022-09-07 03:39:37.000000 feapder-1.8.6b7/feapder/commands/create/create_spider.py
--rw-r--r--   0 liubo      (501) staff       (20)     4288 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/commands/create/create_table.py
--rw-r--r--   0 liubo      (501) staff       (20)     3984 2022-10-21 10:06:04.000000 feapder-1.8.6b7/feapder/commands/create_builder.py
--rw-r--r--   0 liubo      (501) staff       (20)     1354 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/commands/retry.py
--rw-r--r--   0 liubo      (501) staff       (20)     5514 2022-10-21 10:06:04.000000 feapder-1.8.6b7/feapder/commands/shell.py
--rw-r--r--   0 liubo      (501) staff       (20)     2572 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/commands/zip.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.399515 feapder-1.8.6b7/feapder/core/
--rw-r--r--   0 liubo      (501) staff       (20)      136 2021-08-04 13:29:34.000000 feapder-1.8.6b7/feapder/core/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     6240 2022-12-01 11:29:17.000000 feapder-1.8.6b7/feapder/core/base_parser.py
--rw-r--r--   0 liubo      (501) staff       (20)     3256 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/core/collector.py
--rw-r--r--   0 liubo      (501) staff       (20)     2808 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/core/handle_failed_items.py
--rw-r--r--   0 liubo      (501) staff       (20)     1733 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/core/handle_failed_requests.py
--rw-r--r--   0 liubo      (501) staff       (20)    32694 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/core/parser_control.py
--rw-r--r--   0 liubo      (501) staff       (20)    21656 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/core/scheduler.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.403798 feapder-1.8.6b7/feapder/core/spiders/
--rw-r--r--   0 liubo      (501) staff       (20)      417 2022-07-25 12:58:57.000000 feapder-1.8.6b7/feapder/core/spiders/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     4368 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/core/spiders/air_spider.py
--rw-r--r--   0 liubo      (501) staff       (20)    49433 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/core/spiders/batch_spider.py
--rw-r--r--   0 liubo      (501) staff       (20)    13420 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/core/spiders/spider.py
--rw-r--r--   0 liubo      (501) staff       (20)    27875 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/core/spiders/task_spider.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.407432 feapder-1.8.6b7/feapder/db/
--rw-r--r--   0 liubo      (501) staff       (20)      136 2021-12-21 10:30:46.000000 feapder-1.8.6b7/feapder/db/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     1117 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/db/memorydb.py
--rw-r--r--   0 liubo      (501) staff       (20)    13606 2021-12-04 11:42:58.000000 feapder-1.8.6b7/feapder/db/mongodb.py
--rw-r--r--   0 liubo      (501) staff       (20)    10799 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/db/mysqldb.py
--rw-r--r--   0 liubo      (501) staff       (20)    29379 2023-05-22 03:57:39.000000 feapder-1.8.6b7/feapder/db/redisdb.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.411532 feapder-1.8.6b7/feapder/dedup/
--rw-r--r--   0 liubo      (501) staff       (20)     6616 2022-09-25 13:50:01.000000 feapder-1.8.6b7/feapder/dedup/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)      901 2022-09-25 13:50:01.000000 feapder-1.8.6b7/feapder/dedup/basefilter.py
--rw-r--r--   0 liubo      (501) staff       (20)     4131 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/dedup/bitarray.py
--rw-r--r--   0 liubo      (501) staff       (20)    12518 2022-09-25 13:50:01.000000 feapder-1.8.6b7/feapder/dedup/bloomfilter.py
--rw-r--r--   0 liubo      (501) staff       (20)     2309 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/dedup/expirefilter.py
--rw-r--r--   0 liubo      (501) staff       (20)     1854 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/dedup/litefilter.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.419527 feapder-1.8.6b7/feapder/network/
--rw-r--r--   0 liubo      (501) staff       (20)        0 2021-02-07 13:26:42.000000 feapder-1.8.6b7/feapder/network/__init__.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.450431 feapder-1.8.6b7/feapder/network/downloader/
--rw-r--r--   0 liubo      (501) staff       (20)      179 2022-09-25 13:50:01.000000 feapder-1.8.6b7/feapder/network/downloader/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     3217 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/network/downloader/_playwright.py
--rw-r--r--   0 liubo      (501) staff       (20)     1440 2022-09-09 06:16:43.000000 feapder-1.8.6b7/feapder/network/downloader/_requests.py
--rw-r--r--   0 liubo      (501) staff       (20)     3093 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/network/downloader/_selenium.py
--rw-r--r--   0 liubo      (501) staff       (20)      694 2022-09-07 03:39:37.000000 feapder-1.8.6b7/feapder/network/downloader/base.py
--rw-r--r--   0 liubo      (501) staff       (20)     4341 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/network/item.py
--rw-r--r--   0 liubo      (501) staff       (20)    23025 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/network/proxy_pool.py
--rw-r--r--   0 liubo      (501) staff       (20)    17351 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/network/request.py
--rw-r--r--   0 liubo      (501) staff       (20)    12743 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/network/response.py
--rw-r--r--   0 liubo      (501) staff       (20)     5661 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/network/selector.py
--rw-r--r--   0 liubo      (501) staff       (20)    42550 2023-04-11 08:22:57.000000 feapder-1.8.6b7/feapder/network/user_agent.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.459597 feapder-1.8.6b7/feapder/network/user_pool/
--rw-r--r--   0 liubo      (501) staff       (20)      329 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/network/user_pool/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     6397 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/network/user_pool/base_user_pool.py
--rw-r--r--   0 liubo      (501) staff       (20)    10762 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/network/user_pool/gold_user_pool.py
--rw-r--r--   0 liubo      (501) staff       (20)     5372 2022-09-25 13:50:01.000000 feapder-1.8.6b7/feapder/network/user_pool/guest_user_pool.py
--rw-r--r--   0 liubo      (501) staff       (20)     8648 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/network/user_pool/normal_user_pool.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.470777 feapder-1.8.6b7/feapder/pipelines/
--rw-r--r--   0 liubo      (501) staff       (20)     1382 2021-09-23 09:22:51.000000 feapder-1.8.6b7/feapder/pipelines/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     1392 2022-09-25 13:50:01.000000 feapder-1.8.6b7/feapder/pipelines/console_pipeline.py
--rw-r--r--   0 liubo      (501) staff       (20)     2405 2021-09-23 09:22:51.000000 feapder-1.8.6b7/feapder/pipelines/mongo_pipeline.py
--rw-r--r--   0 liubo      (501) staff       (20)     2088 2021-04-08 03:41:12.000000 feapder-1.8.6b7/feapder/pipelines/mysql_pipeline.py
--rw-r--r--   0 liubo      (501) staff       (20)      363 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/requirements.txt
--rw-r--r--   0 liubo      (501) staff       (20)    10826 2023-05-22 03:58:15.000000 feapder-1.8.6b7/feapder/setting.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.483927 feapder-1.8.6b7/feapder/templates/
--rw-r--r--   0 liubo      (501) staff       (20)     6148 2022-03-18 07:14:05.000000 feapder-1.8.6b7/feapder/templates/.DS_Store
--rw-r--r--   0 liubo      (501) staff       (20)      592 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/templates/air_spider_template.tmpl
--rw-r--r--   0 liubo      (501) staff       (20)     2083 2022-09-07 03:39:38.000000 feapder-1.8.6b7/feapder/templates/batch_spider_template.tmpl
--rw-r--r--   0 liubo      (501) staff       (20)      353 2021-12-22 05:53:07.000000 feapder-1.8.6b7/feapder/templates/item_template.tmpl
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.493509 feapder-1.8.6b7/feapder/templates/project_template/
--rw-r--r--   0 liubo      (501) staff       (20)     6148 2022-03-18 07:14:05.000000 feapder-1.8.6b7/feapder/templates/project_template/.DS_Store
--rw-r--r--   0 liubo      (501) staff       (20)     1574 2021-08-04 13:29:34.000000 feapder-1.8.6b7/feapder/templates/project_template/CHECK_DATA.md
--rw-r--r--   0 liubo      (501) staff       (20)       81 2021-08-04 13:29:34.000000 feapder-1.8.6b7/feapder/templates/project_template/README.md
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.494624 feapder-1.8.6b7/feapder/templates/project_template/items/
--rw-r--r--   0 liubo      (501) staff       (20)        0 2021-02-07 13:26:42.000000 feapder-1.8.6b7/feapder/templates/project_template/items/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     2089 2021-09-02 10:23:23.000000 feapder-1.8.6b7/feapder/templates/project_template/main.py
--rw-r--r--   0 liubo      (501) staff       (20)     8825 2023-05-22 03:59:20.000000 feapder-1.8.6b7/feapder/templates/project_template/setting.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.495507 feapder-1.8.6b7/feapder/templates/project_template/spiders/
--rw-r--r--   0 liubo      (501) staff       (20)        0 2021-02-07 13:26:42.000000 feapder-1.8.6b7/feapder/templates/project_template/spiders/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)      808 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/templates/spider_template.tmpl
--rw-r--r--   0 liubo      (501) staff       (20)     2336 2022-09-07 03:39:38.000000 feapder-1.8.6b7/feapder/templates/task_spider_template.tmpl
--rw-r--r--   0 liubo      (501) staff       (20)      365 2022-09-19 07:00:37.000000 feapder-1.8.6b7/feapder/templates/update_item_template.tmpl
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.505297 feapder-1.8.6b7/feapder/utils/
--rw-r--r--   0 liubo      (501) staff       (20)      135 2021-08-04 13:29:34.000000 feapder-1.8.6b7/feapder/utils/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     1959 2021-02-07 13:26:42.000000 feapder-1.8.6b7/feapder/utils/custom_argparse.py
--rw-r--r--   0 liubo      (501) staff       (20)     2537 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/utils/email_sender.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.508031 feapder-1.8.6b7/feapder/utils/js/
--rw-r--r--   0 liubo      (501) staff       (20)     6344 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/utils/js/intercept.js
--rw-r--r--   0 liubo      (501) staff       (20)   166307 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/utils/js/stealth.min.js
--rw-r--r--   0 liubo      (501) staff       (20)     8097 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/utils/log.py
--rw-r--r--   0 liubo      (501) staff       (20)    16820 2023-04-28 09:52:17.000000 feapder-1.8.6b7/feapder/utils/metrics.py
--rw-r--r--   0 liubo      (501) staff       (20)     2123 2021-08-12 03:51:27.000000 feapder-1.8.6b7/feapder/utils/perfect_dict.py
--rw-r--r--   0 liubo      (501) staff       (20)     3670 2022-06-10 02:51:23.000000 feapder-1.8.6b7/feapder/utils/redis_lock.py
--rw-r--r--   0 liubo      (501) staff       (20)    73692 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/utils/tools.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.516792 feapder-1.8.6b7/feapder/utils/webdriver/
--rw-r--r--   0 liubo      (501) staff       (20)      380 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/utils/webdriver/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     9330 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/utils/webdriver/playwright_driver.py
--rw-r--r--   0 liubo      (501) staff       (20)    12628 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/utils/webdriver/selenium_driver.py
--rw-r--r--   0 liubo      (501) staff       (20)     2574 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/utils/webdriver/webdirver.py
--rw-r--r--   0 liubo      (501) staff       (20)     3282 2023-03-30 02:09:37.000000 feapder-1.8.6b7/feapder/utils/webdriver/webdriver_pool.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.381182 feapder-1.8.6b7/feapder.egg-info/
--rw-r--r--   0 liubo      (501) staff       (20)     4568 2023-05-22 04:00:03.000000 feapder-1.8.6b7/feapder.egg-info/PKG-INFO
--rw-r--r--   0 liubo      (501) staff       (20)     5768 2023-05-22 04:00:03.000000 feapder-1.8.6b7/feapder.egg-info/SOURCES.txt
--rw-r--r--   0 liubo      (501) staff       (20)        1 2023-05-22 04:00:03.000000 feapder-1.8.6b7/feapder.egg-info/dependency_links.txt
--rw-r--r--   0 liubo      (501) staff       (20)       61 2023-05-22 04:00:03.000000 feapder-1.8.6b7/feapder.egg-info/entry_points.txt
--rw-r--r--   0 liubo      (501) staff       (20)      371 2023-05-22 04:00:03.000000 feapder-1.8.6b7/feapder.egg-info/requires.txt
--rw-r--r--   0 liubo      (501) staff       (20)        8 2023-05-22 04:00:03.000000 feapder-1.8.6b7/feapder.egg-info/top_level.txt
--rw-r--r--   0 liubo      (501) staff       (20)       38 2023-05-22 04:00:03.578376 feapder-1.8.6b7/setup.cfg
--rw-r--r--   0 liubo      (501) staff       (20)     2030 2023-04-11 08:22:57.000000 feapder-1.8.6b7/setup.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.537935 feapder-1.8.6b7/tests/
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.541024 feapder-1.8.6b7/tests/air-spider/
--rw-r--r--   0 liubo      (501) staff       (20)     1218 2022-11-29 03:10:00.000000 feapder-1.8.6b7/tests/air-spider/test_air_spider.py
--rw-r--r--   0 liubo      (501) staff       (20)     1075 2023-03-30 02:09:37.000000 feapder-1.8.6b7/tests/air-spider/test_air_spider_filter.py
--rw-r--r--   0 liubo      (501) staff       (20)     1094 2023-03-30 02:09:37.000000 feapder-1.8.6b7/tests/air-spider/test_air_spider_item.py
--rw-r--r--   0 liubo      (501) staff       (20)      638 2023-04-28 09:18:56.000000 feapder-1.8.6b7/tests/air-spider/test_render_spider.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.543723 feapder-1.8.6b7/tests/batch-spider/
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.551741 feapder-1.8.6b7/tests/batch-spider/items/
--rw-r--r--   0 liubo      (501) staff       (20)       36 2021-09-03 07:47:43.000000 feapder-1.8.6b7/tests/batch-spider/items/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)      586 2021-09-12 14:22:50.000000 feapder-1.8.6b7/tests/batch-spider/items/spider_data_item.py
--rw-r--r--   0 liubo      (501) staff       (20)     2020 2022-10-24 09:10:44.000000 feapder-1.8.6b7/tests/batch-spider/main.py
--rw-r--r--   0 liubo      (501) staff       (20)     2227 2021-09-02 10:23:23.000000 feapder-1.8.6b7/tests/batch-spider/setting.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.553382 feapder-1.8.6b7/tests/batch-spider/spiders/
--rw-r--r--   0 liubo      (501) staff       (20)       31 2021-02-08 08:09:47.000000 feapder-1.8.6b7/tests/batch-spider/spiders/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     1513 2021-10-09 11:17:03.000000 feapder-1.8.6b7/tests/batch-spider/spiders/test_spider.py
--rw-r--r--   0 liubo      (501) staff       (20)      851 2021-02-08 08:29:51.000000 feapder-1.8.6b7/tests/batch-spider/table.sql
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.546577 feapder-1.8.6b7/tests/batch-spider-integration/
--rw-r--r--   0 liubo      (501) staff       (20)      746 2021-03-03 03:39:52.000000 feapder-1.8.6b7/tests/batch-spider-integration/batch_spider_integration_task.sql
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.547601 feapder-1.8.6b7/tests/batch-spider-integration/items/
--rw-r--r--   0 liubo      (501) staff       (20)        0 2021-03-03 03:39:52.000000 feapder-1.8.6b7/tests/batch-spider-integration/items/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     1686 2021-12-30 08:52:14.000000 feapder-1.8.6b7/tests/batch-spider-integration/main.py
--rw-r--r--   0 liubo      (501) staff       (20)     2226 2021-09-02 10:23:23.000000 feapder-1.8.6b7/tests/batch-spider-integration/setting.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.549617 feapder-1.8.6b7/tests/batch-spider-integration/spiders/
--rw-r--r--   0 liubo      (501) staff       (20)       63 2021-03-03 03:39:52.000000 feapder-1.8.6b7/tests/batch-spider-integration/spiders/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)      581 2021-03-18 02:19:03.000000 feapder-1.8.6b7/tests/batch-spider-integration/spiders/sina_news_parser.py
--rw-r--r--   0 liubo      (501) staff       (20)      584 2021-03-18 02:19:03.000000 feapder-1.8.6b7/tests/batch-spider-integration/spiders/tencent_news_parser.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.554115 feapder-1.8.6b7/tests/db/
--rw-r--r--   0 liubo      (501) staff       (20)      373 2021-03-06 15:13:19.000000 feapder-1.8.6b7/tests/db/test_redis.py
--rw-r--r--   0 liubo      (501) staff       (20)     2087 2021-03-18 02:19:03.000000 feapder-1.8.6b7/tests/jd_spider.py
--rw-r--r--   0 liubo      (501) staff       (20)     1011 2021-12-01 05:56:45.000000 feapder-1.8.6b7/tests/mongo_spider.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.556328 feapder-1.8.6b7/tests/spider/
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.562682 feapder-1.8.6b7/tests/spider/items/
--rw-r--r--   0 liubo      (501) staff       (20)       36 2022-01-27 08:13:00.000000 feapder-1.8.6b7/tests/spider/items/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)      358 2021-12-22 05:05:06.000000 feapder-1.8.6b7/tests/spider/items/spider_data_item.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.563606 feapder-1.8.6b7/tests/spider/log/
--rw-r--r--   0 liubo      (501) staff       (20)     1719 2021-08-11 01:59:56.000000 feapder-1.8.6b7/tests/spider/log/haha.log
--rw-r--r--   0 liubo      (501) staff       (20)      296 2022-08-31 02:19:25.000000 feapder-1.8.6b7/tests/spider/main.py
--rw-r--r--   0 liubo      (501) staff       (20)     2676 2023-03-30 02:09:37.000000 feapder-1.8.6b7/tests/spider/setting.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.566478 feapder-1.8.6b7/tests/spider/spiders/
--rw-r--r--   0 liubo      (501) staff       (20)       42 2021-02-21 15:44:20.000000 feapder-1.8.6b7/tests/spider/spiders/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)      985 2022-10-25 08:22:40.000000 feapder-1.8.6b7/tests/spider/spiders/test_spider.py
--rw-r--r--   0 liubo      (501) staff       (20)      612 2021-08-04 13:29:34.000000 feapder-1.8.6b7/tests/spider/spiders/test_spider2.py
--rw-r--r--   0 liubo      (501) staff       (20)      320 2021-02-08 08:40:34.000000 feapder-1.8.6b7/tests/spider/table.sql
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.557861 feapder-1.8.6b7/tests/spider-integration/
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.558632 feapder-1.8.6b7/tests/spider-integration/items/
--rw-r--r--   0 liubo      (501) staff       (20)        0 2021-03-03 03:39:52.000000 feapder-1.8.6b7/tests/spider-integration/items/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)      517 2021-12-30 08:51:43.000000 feapder-1.8.6b7/tests/spider-integration/main.py
--rw-r--r--   0 liubo      (501) staff       (20)     2226 2021-09-02 10:23:23.000000 feapder-1.8.6b7/tests/spider-integration/setting.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.560809 feapder-1.8.6b7/tests/spider-integration/spiders/
--rw-r--r--   0 liubo      (501) staff       (20)       63 2021-03-03 03:39:52.000000 feapder-1.8.6b7/tests/spider-integration/spiders/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)      470 2023-03-29 13:31:04.000000 feapder-1.8.6b7/tests/spider-integration/spiders/sina_news_parser.py
--rw-r--r--   0 liubo      (501) staff       (20)      456 2021-09-24 05:52:08.000000 feapder-1.8.6b7/tests/spider-integration/spiders/tencent_news_parser.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.567407 feapder-1.8.6b7/tests/task-spider/
--rw-r--r--   0 liubo      (501) staff       (20)     2133 2023-03-30 02:09:37.000000 feapder-1.8.6b7/tests/task-spider/test_task_spider.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.571161 feapder-1.8.6b7/tests/test-pipeline/
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.573151 feapder-1.8.6b7/tests/test-pipeline/items/
--rw-r--r--   0 liubo      (501) staff       (20)       36 2021-03-18 02:19:03.000000 feapder-1.8.6b7/tests/test-pipeline/items/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)      586 2021-03-18 02:19:03.000000 feapder-1.8.6b7/tests/test-pipeline/items/spider_data_item.py
--rw-r--r--   0 liubo      (501) staff       (20)     1250 2022-09-07 03:39:38.000000 feapder-1.8.6b7/tests/test-pipeline/main.py
--rw-r--r--   0 liubo      (501) staff       (20)     1416 2021-04-08 03:41:12.000000 feapder-1.8.6b7/tests/test-pipeline/pipeline.py
--rw-r--r--   0 liubo      (501) staff       (20)     2336 2021-09-02 10:23:23.000000 feapder-1.8.6b7/tests/test-pipeline/setting.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.574483 feapder-1.8.6b7/tests/test-pipeline/spiders/
--rw-r--r--   0 liubo      (501) staff       (20)       31 2021-03-30 02:34:20.000000 feapder-1.8.6b7/tests/test-pipeline/spiders/__init__.py
--rw-r--r--   0 liubo      (501) staff       (20)     1514 2021-03-18 02:19:03.000000 feapder-1.8.6b7/tests/test-pipeline/spiders/test_spider.py
--rw-r--r--   0 liubo      (501) staff       (20)      851 2021-03-18 02:19:03.000000 feapder-1.8.6b7/tests/test-pipeline/table.sql
--rw-r--r--   0 liubo      (501) staff       (20)      281 2022-11-22 03:30:44.000000 feapder-1.8.6b7/tests/test.py
--rw-r--r--   0 liubo      (501) staff       (20)     3140 2023-03-30 02:09:37.000000 feapder-1.8.6b7/tests/test_dedup.py
--rw-r--r--   0 liubo      (501) staff       (20)      469 2021-09-02 10:22:59.000000 feapder-1.8.6b7/tests/test_lock.py
--rw-r--r--   0 liubo      (501) staff       (20)      189 2022-03-26 15:56:04.000000 feapder-1.8.6b7/tests/test_log.py
--rw-r--r--   0 liubo      (501) staff       (20)     1229 2023-05-22 03:51:23.000000 feapder-1.8.6b7/tests/test_metrics.py
--rw-r--r--   0 liubo      (501) staff       (20)     4678 2021-12-01 05:56:51.000000 feapder-1.8.6b7/tests/test_mongodb.py
--rw-r--r--   0 liubo      (501) staff       (20)      232 2021-10-14 08:25:11.000000 feapder-1.8.6b7/tests/test_mysqldb.py
--rw-r--r--   0 liubo      (501) staff       (20)     1086 2023-03-30 02:09:37.000000 feapder-1.8.6b7/tests/test_playwright.py
--rw-r--r--   0 liubo      (501) staff       (20)     3477 2023-03-30 02:09:37.000000 feapder-1.8.6b7/tests/test_playwright2.py
--rw-r--r--   0 liubo      (501) staff       (20)     1177 2021-04-08 03:41:12.000000 feapder-1.8.6b7/tests/test_proxies_pool.py
--rw-r--r--   0 liubo      (501) staff       (20)      660 2022-10-28 07:20:27.000000 feapder-1.8.6b7/tests/test_rander.py
--rw-r--r--   0 liubo      (501) staff       (20)      769 2021-07-08 11:51:50.000000 feapder-1.8.6b7/tests/test_rander2.py
--rw-r--r--   0 liubo      (501) staff       (20)      519 2022-09-14 07:25:07.000000 feapder-1.8.6b7/tests/test_rander3.py
--rw-r--r--   0 liubo      (501) staff       (20)     1983 2022-09-07 09:10:17.000000 feapder-1.8.6b7/tests/test_rander_xhr.py
--rw-r--r--   0 liubo      (501) staff       (20)      148 2021-08-12 03:51:27.000000 feapder-1.8.6b7/tests/test_redisdb.py
--rw-r--r--   0 liubo      (501) staff       (20)     1634 2022-09-25 13:50:01.000000 feapder-1.8.6b7/tests/test_request.py
--rw-r--r--   0 liubo      (501) staff       (20)      637 2021-04-08 03:41:12.000000 feapder-1.8.6b7/tests/test_spider_params.py
--rw-r--r--   0 liubo      (501) staff       (20)      593 2022-07-25 12:58:57.000000 feapder-1.8.6b7/tests/test_task.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.575089 feapder-1.8.6b7/tests/test_template/
--rw-r--r--   0 liubo      (501) staff       (20)     2336 2022-09-07 03:39:38.000000 feapder-1.8.6b7/tests/test_template/test_spider.py
--rw-r--r--   0 liubo      (501) staff       (20)      429 2022-05-17 07:19:13.000000 feapder-1.8.6b7/tests/test_tools.py
--rw-r--r--   0 liubo      (501) staff       (20)     1011 2022-09-07 09:10:23.000000 feapder-1.8.6b7/tests/test_webdriver.py
-drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-05-22 04:00:03.577173 feapder-1.8.6b7/tests/user_pool/
--rw-r--r--   0 liubo      (501) staff       (20)     2423 2022-06-10 02:51:23.000000 feapder-1.8.6b7/tests/user_pool/test_gold_user_pool.py
--rw-r--r--   0 liubo      (501) staff       (20)     2121 2022-06-10 02:51:23.000000 feapder-1.8.6b7/tests/user_pool/test_guest_user_pool.py
--rw-r--r--   0 liubo      (501) staff       (20)     1427 2022-06-10 02:51:23.000000 feapder-1.8.6b7/tests/user_pool/test_normal_user_pool.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.188048 feapder-1.8.7b1/
+-rw-r--r--   0 liubo      (501) staff       (20)     1102 2021-08-04 13:29:34.000000 feapder-1.8.7b1/LICENSE
+-rw-r--r--   0 liubo      (501) staff       (20)      231 2021-08-12 03:51:27.000000 feapder-1.8.7b1/MANIFEST.in
+-rw-r--r--   0 liubo      (501) staff       (20)     4813 2023-06-28 13:19:58.187377 feapder-1.8.7b1/PKG-INFO
+-rw-r--r--   0 liubo      (501) staff       (20)     4366 2023-06-28 12:11:24.000000 feapder-1.8.7b1/README.md
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:57.961220 feapder-1.8.7b1/feapder/
+-rw-r--r--   0 liubo      (501) staff       (20)       11 2023-06-28 13:19:39.000000 feapder-1.8.7b1/feapder/VERSION
+-rw-r--r--   0 liubo      (501) staff       (20)      815 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/__init__.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:57.966416 feapder-1.8.7b1/feapder/buffer/
+-rw-r--r--   0 liubo      (501) staff       (20)      136 2021-08-04 13:29:34.000000 feapder-1.8.7b1/feapder/buffer/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)    14141 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/buffer/item_buffer.py
+-rw-r--r--   0 liubo      (501) staff       (20)     5356 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/buffer/request_buffer.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:57.971031 feapder-1.8.7b1/feapder/commands/
+-rw-r--r--   0 liubo      (501) staff       (20)        0 2021-02-07 13:26:42.000000 feapder-1.8.7b1/feapder/commands/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     3824 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/commands/cmdline.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:57.982079 feapder-1.8.7b1/feapder/commands/create/
+-rw-r--r--   0 liubo      (501) staff       (20)      543 2021-09-02 10:23:23.000000 feapder-1.8.7b1/feapder/commands/create/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)      975 2022-06-10 02:51:23.000000 feapder-1.8.7b1/feapder/commands/create/create_cookies.py
+-rw-r--r--   0 liubo      (501) staff       (20)      670 2021-02-08 06:31:07.000000 feapder-1.8.7b1/feapder/commands/create/create_init.py
+-rw-r--r--   0 liubo      (501) staff       (20)     6004 2022-09-07 03:39:37.000000 feapder-1.8.7b1/feapder/commands/create/create_item.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1366 2022-06-10 02:51:23.000000 feapder-1.8.7b1/feapder/commands/create/create_json.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1106 2021-09-02 10:23:23.000000 feapder-1.8.7b1/feapder/commands/create/create_params.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1360 2022-06-10 02:51:23.000000 feapder-1.8.7b1/feapder/commands/create/create_project.py
+-rw-r--r--   0 liubo      (501) staff       (20)      693 2021-08-04 13:29:34.000000 feapder-1.8.7b1/feapder/commands/create/create_setting.py
+-rw-r--r--   0 liubo      (501) staff       (20)     3648 2022-09-07 03:39:37.000000 feapder-1.8.7b1/feapder/commands/create/create_spider.py
+-rw-r--r--   0 liubo      (501) staff       (20)     4288 2023-06-28 09:14:30.000000 feapder-1.8.7b1/feapder/commands/create/create_table.py
+-rw-r--r--   0 liubo      (501) staff       (20)     3984 2022-10-21 10:06:04.000000 feapder-1.8.7b1/feapder/commands/create_builder.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1354 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/commands/retry.py
+-rw-r--r--   0 liubo      (501) staff       (20)     5514 2022-10-21 10:06:04.000000 feapder-1.8.7b1/feapder/commands/shell.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2572 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/commands/zip.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:57.991056 feapder-1.8.7b1/feapder/core/
+-rw-r--r--   0 liubo      (501) staff       (20)      136 2021-08-04 13:29:34.000000 feapder-1.8.7b1/feapder/core/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     6240 2022-12-01 11:29:17.000000 feapder-1.8.7b1/feapder/core/base_parser.py
+-rw-r--r--   0 liubo      (501) staff       (20)     3256 2022-06-10 02:51:23.000000 feapder-1.8.7b1/feapder/core/collector.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2808 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/core/handle_failed_items.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1733 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/core/handle_failed_requests.py
+-rw-r--r--   0 liubo      (501) staff       (20)    32962 2023-06-28 13:10:40.000000 feapder-1.8.7b1/feapder/core/parser_control.py
+-rw-r--r--   0 liubo      (501) staff       (20)    21656 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/core/scheduler.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:57.998620 feapder-1.8.7b1/feapder/core/spiders/
+-rw-r--r--   0 liubo      (501) staff       (20)      417 2022-07-25 12:58:57.000000 feapder-1.8.7b1/feapder/core/spiders/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     4368 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/core/spiders/air_spider.py
+-rw-r--r--   0 liubo      (501) staff       (20)    49433 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/core/spiders/batch_spider.py
+-rw-r--r--   0 liubo      (501) staff       (20)    13420 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/core/spiders/spider.py
+-rw-r--r--   0 liubo      (501) staff       (20)    27875 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/core/spiders/task_spider.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.024833 feapder-1.8.7b1/feapder/db/
+-rw-r--r--   0 liubo      (501) staff       (20)      136 2021-12-21 10:30:46.000000 feapder-1.8.7b1/feapder/db/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1117 2023-06-28 09:14:30.000000 feapder-1.8.7b1/feapder/db/memorydb.py
+-rw-r--r--   0 liubo      (501) staff       (20)    13606 2021-12-04 11:42:58.000000 feapder-1.8.7b1/feapder/db/mongodb.py
+-rw-r--r--   0 liubo      (501) staff       (20)    10799 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/db/mysqldb.py
+-rw-r--r--   0 liubo      (501) staff       (20)    29545 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/db/redisdb.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.029853 feapder-1.8.7b1/feapder/dedup/
+-rw-r--r--   0 liubo      (501) staff       (20)     6616 2022-09-25 13:50:01.000000 feapder-1.8.7b1/feapder/dedup/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)      901 2022-09-25 13:50:01.000000 feapder-1.8.7b1/feapder/dedup/basefilter.py
+-rw-r--r--   0 liubo      (501) staff       (20)     4133 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/dedup/bitarray.py
+-rw-r--r--   0 liubo      (501) staff       (20)    12518 2022-09-25 13:50:01.000000 feapder-1.8.7b1/feapder/dedup/bloomfilter.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2309 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/dedup/expirefilter.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1854 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/dedup/litefilter.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.034330 feapder-1.8.7b1/feapder/network/
+-rw-r--r--   0 liubo      (501) staff       (20)        0 2021-02-07 13:26:42.000000 feapder-1.8.7b1/feapder/network/__init__.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.038284 feapder-1.8.7b1/feapder/network/downloader/
+-rw-r--r--   0 liubo      (501) staff       (20)      299 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/network/downloader/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     3217 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/network/downloader/_playwright.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1440 2022-09-09 06:16:43.000000 feapder-1.8.7b1/feapder/network/downloader/_requests.py
+-rw-r--r--   0 liubo      (501) staff       (20)     3093 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/network/downloader/_selenium.py
+-rw-r--r--   0 liubo      (501) staff       (20)      694 2022-09-07 03:39:37.000000 feapder-1.8.7b1/feapder/network/downloader/base.py
+-rw-r--r--   0 liubo      (501) staff       (20)     4341 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/network/item.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2070 2023-06-28 13:00:38.000000 feapder-1.8.7b1/feapder/network/proxy_pool.py
+-rw-r--r--   0 liubo      (501) staff       (20)    23025 2023-06-28 09:14:30.000000 feapder-1.8.7b1/feapder/network/proxy_pool_old.py
+-rw-r--r--   0 liubo      (501) staff       (20)    17719 2023-06-28 12:58:09.000000 feapder-1.8.7b1/feapder/network/request.py
+-rw-r--r--   0 liubo      (501) staff       (20)    12743 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/network/response.py
+-rw-r--r--   0 liubo      (501) staff       (20)     5661 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/network/selector.py
+-rw-r--r--   0 liubo      (501) staff       (20)   130399 2023-06-28 08:50:40.000000 feapder-1.8.7b1/feapder/network/user_agent.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.041290 feapder-1.8.7b1/feapder/network/user_pool/
+-rw-r--r--   0 liubo      (501) staff       (20)      329 2022-06-10 02:51:23.000000 feapder-1.8.7b1/feapder/network/user_pool/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     6397 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/network/user_pool/base_user_pool.py
+-rw-r--r--   0 liubo      (501) staff       (20)    10762 2022-06-10 02:51:23.000000 feapder-1.8.7b1/feapder/network/user_pool/gold_user_pool.py
+-rw-r--r--   0 liubo      (501) staff       (20)     5372 2022-09-25 13:50:01.000000 feapder-1.8.7b1/feapder/network/user_pool/guest_user_pool.py
+-rw-r--r--   0 liubo      (501) staff       (20)     8648 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/network/user_pool/normal_user_pool.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.043832 feapder-1.8.7b1/feapder/pipelines/
+-rw-r--r--   0 liubo      (501) staff       (20)     1382 2021-09-23 09:22:51.000000 feapder-1.8.7b1/feapder/pipelines/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1392 2022-09-25 13:50:01.000000 feapder-1.8.7b1/feapder/pipelines/console_pipeline.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2405 2021-09-23 09:22:51.000000 feapder-1.8.7b1/feapder/pipelines/mongo_pipeline.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2088 2021-04-08 03:41:12.000000 feapder-1.8.7b1/feapder/pipelines/mysql_pipeline.py
+-rw-r--r--   0 liubo      (501) staff       (20)      363 2023-06-28 09:14:30.000000 feapder-1.8.7b1/feapder/requirements.txt
+-rw-r--r--   0 liubo      (501) staff       (20)    10917 2023-06-28 13:08:22.000000 feapder-1.8.7b1/feapder/setting.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.048873 feapder-1.8.7b1/feapder/templates/
+-rw-r--r--   0 liubo      (501) staff       (20)     6148 2022-03-18 07:14:05.000000 feapder-1.8.7b1/feapder/templates/.DS_Store
+-rw-r--r--   0 liubo      (501) staff       (20)      592 2022-06-10 02:51:23.000000 feapder-1.8.7b1/feapder/templates/air_spider_template.tmpl
+-rw-r--r--   0 liubo      (501) staff       (20)     2083 2022-09-07 03:39:38.000000 feapder-1.8.7b1/feapder/templates/batch_spider_template.tmpl
+-rw-r--r--   0 liubo      (501) staff       (20)      353 2021-12-22 05:53:07.000000 feapder-1.8.7b1/feapder/templates/item_template.tmpl
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.052121 feapder-1.8.7b1/feapder/templates/project_template/
+-rw-r--r--   0 liubo      (501) staff       (20)     6148 2022-03-18 07:14:05.000000 feapder-1.8.7b1/feapder/templates/project_template/.DS_Store
+-rw-r--r--   0 liubo      (501) staff       (20)     1574 2021-08-04 13:29:34.000000 feapder-1.8.7b1/feapder/templates/project_template/CHECK_DATA.md
+-rw-r--r--   0 liubo      (501) staff       (20)       81 2021-08-04 13:29:34.000000 feapder-1.8.7b1/feapder/templates/project_template/README.md
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.052641 feapder-1.8.7b1/feapder/templates/project_template/items/
+-rw-r--r--   0 liubo      (501) staff       (20)        0 2021-02-07 13:26:42.000000 feapder-1.8.7b1/feapder/templates/project_template/items/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2089 2021-09-02 10:23:23.000000 feapder-1.8.7b1/feapder/templates/project_template/main.py
+-rw-r--r--   0 liubo      (501) staff       (20)     8918 2023-06-28 13:11:47.000000 feapder-1.8.7b1/feapder/templates/project_template/setting.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.053004 feapder-1.8.7b1/feapder/templates/project_template/spiders/
+-rw-r--r--   0 liubo      (501) staff       (20)        0 2021-02-07 13:26:42.000000 feapder-1.8.7b1/feapder/templates/project_template/spiders/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)      808 2022-06-10 02:51:23.000000 feapder-1.8.7b1/feapder/templates/spider_template.tmpl
+-rw-r--r--   0 liubo      (501) staff       (20)     2336 2022-09-07 03:39:38.000000 feapder-1.8.7b1/feapder/templates/task_spider_template.tmpl
+-rw-r--r--   0 liubo      (501) staff       (20)      365 2022-09-19 07:00:37.000000 feapder-1.8.7b1/feapder/templates/update_item_template.tmpl
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.058891 feapder-1.8.7b1/feapder/utils/
+-rw-r--r--   0 liubo      (501) staff       (20)      135 2021-08-04 13:29:34.000000 feapder-1.8.7b1/feapder/utils/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1959 2021-02-07 13:26:42.000000 feapder-1.8.7b1/feapder/utils/custom_argparse.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2537 2022-06-10 02:51:23.000000 feapder-1.8.7b1/feapder/utils/email_sender.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.060935 feapder-1.8.7b1/feapder/utils/js/
+-rw-r--r--   0 liubo      (501) staff       (20)     6344 2022-06-10 02:51:23.000000 feapder-1.8.7b1/feapder/utils/js/intercept.js
+-rw-r--r--   0 liubo      (501) staff       (20)   166307 2022-06-10 02:51:23.000000 feapder-1.8.7b1/feapder/utils/js/stealth.min.js
+-rw-r--r--   0 liubo      (501) staff       (20)     8468 2023-06-28 09:47:12.000000 feapder-1.8.7b1/feapder/utils/log.py
+-rw-r--r--   0 liubo      (501) staff       (20)    16820 2023-06-28 09:14:32.000000 feapder-1.8.7b1/feapder/utils/metrics.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2123 2021-08-12 03:51:27.000000 feapder-1.8.7b1/feapder/utils/perfect_dict.py
+-rw-r--r--   0 liubo      (501) staff       (20)     3670 2022-06-10 02:51:23.000000 feapder-1.8.7b1/feapder/utils/redis_lock.py
+-rw-r--r--   0 liubo      (501) staff       (20)    73692 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/utils/tools.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.065902 feapder-1.8.7b1/feapder/utils/webdriver/
+-rw-r--r--   0 liubo      (501) staff       (20)      380 2023-06-28 09:14:30.000000 feapder-1.8.7b1/feapder/utils/webdriver/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     9330 2023-06-28 09:14:30.000000 feapder-1.8.7b1/feapder/utils/webdriver/playwright_driver.py
+-rw-r--r--   0 liubo      (501) staff       (20)    12628 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/utils/webdriver/selenium_driver.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2574 2023-06-28 09:14:30.000000 feapder-1.8.7b1/feapder/utils/webdriver/webdirver.py
+-rw-r--r--   0 liubo      (501) staff       (20)     3282 2023-06-28 09:14:31.000000 feapder-1.8.7b1/feapder/utils/webdriver/webdriver_pool.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:57.964278 feapder-1.8.7b1/feapder.egg-info/
+-rw-r--r--   0 liubo      (501) staff       (20)     4813 2023-06-28 13:19:57.000000 feapder-1.8.7b1/feapder.egg-info/PKG-INFO
+-rw-r--r--   0 liubo      (501) staff       (20)     6017 2023-06-28 13:19:57.000000 feapder-1.8.7b1/feapder.egg-info/SOURCES.txt
+-rw-r--r--   0 liubo      (501) staff       (20)        1 2023-06-28 13:19:57.000000 feapder-1.8.7b1/feapder.egg-info/dependency_links.txt
+-rw-r--r--   0 liubo      (501) staff       (20)       61 2023-06-28 13:19:57.000000 feapder-1.8.7b1/feapder.egg-info/entry_points.txt
+-rw-r--r--   0 liubo      (501) staff       (20)      435 2023-06-28 13:19:57.000000 feapder-1.8.7b1/feapder.egg-info/requires.txt
+-rw-r--r--   0 liubo      (501) staff       (20)        8 2023-06-28 13:19:57.000000 feapder-1.8.7b1/feapder.egg-info/top_level.txt
+-rw-r--r--   0 liubo      (501) staff       (20)       38 2023-06-28 13:19:58.188334 feapder-1.8.7b1/setup.cfg
+-rw-r--r--   0 liubo      (501) staff       (20)     2103 2023-06-28 09:14:32.000000 feapder-1.8.7b1/setup.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.081125 feapder-1.8.7b1/tests/
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.105208 feapder-1.8.7b1/tests/air-spider/
+-rw-r--r--   0 liubo      (501) staff       (20)     1218 2022-11-29 03:10:00.000000 feapder-1.8.7b1/tests/air-spider/test_air_spider.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1075 2023-06-28 09:14:30.000000 feapder-1.8.7b1/tests/air-spider/test_air_spider_filter.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1094 2023-06-28 09:14:32.000000 feapder-1.8.7b1/tests/air-spider/test_air_spider_item.py
+-rw-r--r--   0 liubo      (501) staff       (20)      638 2023-06-28 09:14:32.000000 feapder-1.8.7b1/tests/air-spider/test_render_spider.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.106921 feapder-1.8.7b1/tests/batch-spider/
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.112504 feapder-1.8.7b1/tests/batch-spider/items/
+-rw-r--r--   0 liubo      (501) staff       (20)       36 2021-09-03 07:47:43.000000 feapder-1.8.7b1/tests/batch-spider/items/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)      586 2021-09-12 14:22:50.000000 feapder-1.8.7b1/tests/batch-spider/items/spider_data_item.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2020 2023-06-09 12:31:43.000000 feapder-1.8.7b1/tests/batch-spider/main.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2227 2021-09-02 10:23:23.000000 feapder-1.8.7b1/tests/batch-spider/setting.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.114090 feapder-1.8.7b1/tests/batch-spider/spiders/
+-rw-r--r--   0 liubo      (501) staff       (20)       31 2021-02-08 08:09:47.000000 feapder-1.8.7b1/tests/batch-spider/spiders/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1575 2023-06-28 09:14:32.000000 feapder-1.8.7b1/tests/batch-spider/spiders/test_spider.py
+-rw-r--r--   0 liubo      (501) staff       (20)      851 2021-02-08 08:29:51.000000 feapder-1.8.7b1/tests/batch-spider/table.sql
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.108780 feapder-1.8.7b1/tests/batch-spider-integration/
+-rw-r--r--   0 liubo      (501) staff       (20)      746 2021-03-03 03:39:52.000000 feapder-1.8.7b1/tests/batch-spider-integration/batch_spider_integration_task.sql
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.109495 feapder-1.8.7b1/tests/batch-spider-integration/items/
+-rw-r--r--   0 liubo      (501) staff       (20)        0 2021-03-03 03:39:52.000000 feapder-1.8.7b1/tests/batch-spider-integration/items/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1686 2021-12-30 08:52:14.000000 feapder-1.8.7b1/tests/batch-spider-integration/main.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2226 2021-09-02 10:23:23.000000 feapder-1.8.7b1/tests/batch-spider-integration/setting.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.111170 feapder-1.8.7b1/tests/batch-spider-integration/spiders/
+-rw-r--r--   0 liubo      (501) staff       (20)       63 2021-03-03 03:39:52.000000 feapder-1.8.7b1/tests/batch-spider-integration/spiders/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)      581 2021-03-18 02:19:03.000000 feapder-1.8.7b1/tests/batch-spider-integration/spiders/sina_news_parser.py
+-rw-r--r--   0 liubo      (501) staff       (20)      584 2021-03-18 02:19:03.000000 feapder-1.8.7b1/tests/batch-spider-integration/spiders/tencent_news_parser.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.114782 feapder-1.8.7b1/tests/db/
+-rw-r--r--   0 liubo      (501) staff       (20)      373 2021-03-06 15:13:19.000000 feapder-1.8.7b1/tests/db/test_redis.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2087 2021-03-18 02:19:03.000000 feapder-1.8.7b1/tests/jd_spider.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1011 2021-12-01 05:56:45.000000 feapder-1.8.7b1/tests/mongo_spider.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.116477 feapder-1.8.7b1/tests/spider/
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.121743 feapder-1.8.7b1/tests/spider/items/
+-rw-r--r--   0 liubo      (501) staff       (20)       36 2022-01-27 08:13:00.000000 feapder-1.8.7b1/tests/spider/items/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)      358 2021-12-22 05:05:06.000000 feapder-1.8.7b1/tests/spider/items/spider_data_item.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.122281 feapder-1.8.7b1/tests/spider/log/
+-rw-r--r--   0 liubo      (501) staff       (20)     1719 2021-08-11 01:59:56.000000 feapder-1.8.7b1/tests/spider/log/haha.log
+-rw-r--r--   0 liubo      (501) staff       (20)      296 2022-08-31 02:19:25.000000 feapder-1.8.7b1/tests/spider/main.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2676 2023-06-28 09:14:30.000000 feapder-1.8.7b1/tests/spider/setting.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.124183 feapder-1.8.7b1/tests/spider/spiders/
+-rw-r--r--   0 liubo      (501) staff       (20)       42 2021-02-21 15:44:20.000000 feapder-1.8.7b1/tests/spider/spiders/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)      985 2022-10-25 08:22:40.000000 feapder-1.8.7b1/tests/spider/spiders/test_spider.py
+-rw-r--r--   0 liubo      (501) staff       (20)      612 2021-08-04 13:29:34.000000 feapder-1.8.7b1/tests/spider/spiders/test_spider2.py
+-rw-r--r--   0 liubo      (501) staff       (20)      320 2021-02-08 08:40:34.000000 feapder-1.8.7b1/tests/spider/table.sql
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.117885 feapder-1.8.7b1/tests/spider-integration/
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.118370 feapder-1.8.7b1/tests/spider-integration/items/
+-rw-r--r--   0 liubo      (501) staff       (20)        0 2021-03-03 03:39:52.000000 feapder-1.8.7b1/tests/spider-integration/items/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)      517 2021-12-30 08:51:43.000000 feapder-1.8.7b1/tests/spider-integration/main.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2226 2021-09-02 10:23:23.000000 feapder-1.8.7b1/tests/spider-integration/setting.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.120628 feapder-1.8.7b1/tests/spider-integration/spiders/
+-rw-r--r--   0 liubo      (501) staff       (20)       63 2021-03-03 03:39:52.000000 feapder-1.8.7b1/tests/spider-integration/spiders/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)      470 2023-03-29 13:31:04.000000 feapder-1.8.7b1/tests/spider-integration/spiders/sina_news_parser.py
+-rw-r--r--   0 liubo      (501) staff       (20)      456 2021-09-24 05:52:08.000000 feapder-1.8.7b1/tests/spider-integration/spiders/tencent_news_parser.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.124986 feapder-1.8.7b1/tests/task-spider/
+-rw-r--r--   0 liubo      (501) staff       (20)     2133 2023-06-28 09:14:32.000000 feapder-1.8.7b1/tests/task-spider/test_task_spider.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.127493 feapder-1.8.7b1/tests/test-debugger/
+-rw-r--r--   0 liubo      (501) staff       (20)     6148 2022-03-18 07:14:05.000000 feapder-1.8.7b1/tests/test-debugger/.DS_Store
+-rw-r--r--   0 liubo      (501) staff       (20)       81 2023-06-28 09:14:32.000000 feapder-1.8.7b1/tests/test-debugger/README.md
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.128189 feapder-1.8.7b1/tests/test-debugger/items/
+-rw-r--r--   0 liubo      (501) staff       (20)        0 2023-06-28 09:14:32.000000 feapder-1.8.7b1/tests/test-debugger/items/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)      352 2023-06-28 09:14:32.000000 feapder-1.8.7b1/tests/test-debugger/main.py
+-rw-r--r--   0 liubo      (501) staff       (20)     8784 2023-06-28 09:14:32.000000 feapder-1.8.7b1/tests/test-debugger/setting.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.129330 feapder-1.8.7b1/tests/test-debugger/spiders/
+-rw-r--r--   0 liubo      (501) staff       (20)       33 2023-06-28 09:14:32.000000 feapder-1.8.7b1/tests/test-debugger/spiders/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)      724 2023-06-28 09:14:32.000000 feapder-1.8.7b1/tests/test-debugger/spiders/test_debugger.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.132474 feapder-1.8.7b1/tests/test-pipeline/
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.133868 feapder-1.8.7b1/tests/test-pipeline/items/
+-rw-r--r--   0 liubo      (501) staff       (20)       36 2021-03-18 02:19:03.000000 feapder-1.8.7b1/tests/test-pipeline/items/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)      586 2021-03-18 02:19:03.000000 feapder-1.8.7b1/tests/test-pipeline/items/spider_data_item.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1250 2022-09-07 03:39:38.000000 feapder-1.8.7b1/tests/test-pipeline/main.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1416 2021-04-08 03:41:12.000000 feapder-1.8.7b1/tests/test-pipeline/pipeline.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2336 2021-09-02 10:23:23.000000 feapder-1.8.7b1/tests/test-pipeline/setting.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.136106 feapder-1.8.7b1/tests/test-pipeline/spiders/
+-rw-r--r--   0 liubo      (501) staff       (20)       31 2021-03-30 02:34:20.000000 feapder-1.8.7b1/tests/test-pipeline/spiders/__init__.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1514 2021-03-18 02:19:03.000000 feapder-1.8.7b1/tests/test-pipeline/spiders/test_spider.py
+-rw-r--r--   0 liubo      (501) staff       (20)      851 2021-03-18 02:19:03.000000 feapder-1.8.7b1/tests/test-pipeline/table.sql
+-rw-r--r--   0 liubo      (501) staff       (20)      281 2022-11-22 03:30:44.000000 feapder-1.8.7b1/tests/test.py
+-rw-r--r--   0 liubo      (501) staff       (20)     3140 2023-06-28 09:14:32.000000 feapder-1.8.7b1/tests/test_dedup.py
+-rw-r--r--   0 liubo      (501) staff       (20)      469 2021-09-02 10:22:59.000000 feapder-1.8.7b1/tests/test_lock.py
+-rw-r--r--   0 liubo      (501) staff       (20)      329 2023-06-28 09:47:12.000000 feapder-1.8.7b1/tests/test_log.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1229 2023-06-28 09:14:32.000000 feapder-1.8.7b1/tests/test_metrics.py
+-rw-r--r--   0 liubo      (501) staff       (20)     4678 2021-12-01 05:56:51.000000 feapder-1.8.7b1/tests/test_mongodb.py
+-rw-r--r--   0 liubo      (501) staff       (20)      232 2021-10-14 08:25:11.000000 feapder-1.8.7b1/tests/test_mysqldb.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1086 2023-06-28 09:14:31.000000 feapder-1.8.7b1/tests/test_playwright.py
+-rw-r--r--   0 liubo      (501) staff       (20)     3477 2023-06-28 09:14:30.000000 feapder-1.8.7b1/tests/test_playwright2.py
+-rw-r--r--   0 liubo      (501) staff       (20)      660 2022-10-28 07:20:27.000000 feapder-1.8.7b1/tests/test_rander.py
+-rw-r--r--   0 liubo      (501) staff       (20)      769 2021-07-08 11:51:50.000000 feapder-1.8.7b1/tests/test_rander2.py
+-rw-r--r--   0 liubo      (501) staff       (20)      519 2022-09-14 07:25:07.000000 feapder-1.8.7b1/tests/test_rander3.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1983 2022-09-07 09:10:17.000000 feapder-1.8.7b1/tests/test_rander_xhr.py
+-rw-r--r--   0 liubo      (501) staff       (20)      148 2021-08-12 03:51:27.000000 feapder-1.8.7b1/tests/test_redisdb.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1634 2022-09-25 13:50:01.000000 feapder-1.8.7b1/tests/test_request.py
+-rw-r--r--   0 liubo      (501) staff       (20)      637 2021-04-08 03:41:12.000000 feapder-1.8.7b1/tests/test_spider_params.py
+-rw-r--r--   0 liubo      (501) staff       (20)      593 2022-07-25 12:58:57.000000 feapder-1.8.7b1/tests/test_task.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.160685 feapder-1.8.7b1/tests/test_template/
+-rw-r--r--   0 liubo      (501) staff       (20)     2336 2022-09-07 03:39:38.000000 feapder-1.8.7b1/tests/test_template/test_spider.py
+-rw-r--r--   0 liubo      (501) staff       (20)      429 2022-05-17 07:19:13.000000 feapder-1.8.7b1/tests/test_tools.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1011 2022-09-07 09:10:23.000000 feapder-1.8.7b1/tests/test_webdriver.py
+drwxr-xr-x   0 liubo      (501) staff       (20)        0 2023-06-28 13:19:58.185644 feapder-1.8.7b1/tests/user_pool/
+-rw-r--r--   0 liubo      (501) staff       (20)     2423 2022-06-10 02:51:23.000000 feapder-1.8.7b1/tests/user_pool/test_gold_user_pool.py
+-rw-r--r--   0 liubo      (501) staff       (20)     2121 2022-06-10 02:51:23.000000 feapder-1.8.7b1/tests/user_pool/test_guest_user_pool.py
+-rw-r--r--   0 liubo      (501) staff       (20)     1427 2022-06-10 02:51:23.000000 feapder-1.8.7b1/tests/user_pool/test_normal_user_pool.py
```

### Comparing `feapder-1.8.6b7/LICENSE` & `feapder-1.8.7b1/LICENSE`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/PKG-INFO` & `feapder-1.8.7b1/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,19 +1,20 @@
 Metadata-Version: 2.1
 Name: feapder
-Version: 1.8.6b7
-Summary: feapder是一款支持分布式、批次采集、任务防丢、报警丰富的python爬虫框架
+Version: 1.8.7b1
+Summary: feapder是一款支持分布式、批次采集、数据防丢、报警丰富的python爬虫框架
 Home-page: https://github.com/Boris-code/feapder.git
 Author: Boris
 Author-email: feapder@qq.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 Provides-Extra: all
+Provides-Extra: render
 License-File: LICENSE
 
 # FEAPDER
 
 ![](https://img.shields.io/badge/python-3.6-brightgreen)
 ![](https://img.shields.io/github/watchers/Boris-code/feapder?style=social)
 ![](https://img.shields.io/github/stars/Boris-code/feapder?style=social)
@@ -45,29 +46,36 @@
 - Python 3.6.0+
 - Works on Linux, Windows, macOS
 
 ## 安装
 
 From PyPi:
 
-通用版
+精简版
 
 ```shell
-pip3 install feapder
+pip install feapder
+```
+
+浏览器渲染版：
+```shell
+pip install "feapder[render]"
 ```
 
 完整版：
 
 ```shell
-pip3 install feapder[all]
+pip install "feapder[all]"
 ```
 
-通用版与完整版区别：
+三个版本区别：
 
-1. 完整版支持基于内存去重
+1. 精简版：不支持浏览器渲染、不支持基于内存去重、不支持入库mongo
+2. 浏览器渲染版：不支持基于内存去重、不支持入库mongo
+3. 完整版：支持所有功能
 
 完整版可能会安装出错，若安装出错，请参考[安装问题](question/安装问题)
 
 ## 小试一下
 
 创建爬虫
 
@@ -109,30 +117,30 @@
 ```
 
 代码解释如下：
 
 1. start_requests： 生产任务
 2. parse： 解析数据
 
-## 爬虫工具推荐
-
-1. 爬虫在线工具库：http://www.spidertools.cn
-2. 爬虫管理系统：http://feapder.com/#/feapder_platform/feaplat
-3. 验证码识别库：https://github.com/sml2h3/ddddocr
-
 ## 参与贡献
 
 贡献之前请先阅读 [贡献指南](./CONTRIBUTING.md)
 
 感谢所有做过贡献的人!
 
 <a href="https://github.com/Boris-code/feapder/graphs/contributors">
   <img src="https://contrib.rocks/image?repo=Boris-code/feapder" />
 </a>
 
+## 爬虫工具推荐
+
+1. 爬虫在线工具库：http://www.spidertools.cn
+2. 爬虫管理系统：http://feapder.com/#/feapder_platform/feaplat
+3. 验证码识别库：https://github.com/sml2h3/ddddocr
+
 ## 微信赞赏
 
 如果您觉得这个项目帮助到了您，您可以帮作者买一杯咖啡表示鼓励 🍹
 
 也可和作者交个朋友，解决您在使用过程中遇到的问题
```

### Comparing `feapder-1.8.6b7/README.md` & `feapder-1.8.7b1/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -31,29 +31,36 @@
 - Python 3.6.0+
 - Works on Linux, Windows, macOS
 
 ## 安装
 
 From PyPi:
 
-通用版
+精简版
 
 ```shell
-pip3 install feapder
+pip install feapder
+```
+
+浏览器渲染版：
+```shell
+pip install "feapder[render]"
 ```
 
 完整版：
 
 ```shell
-pip3 install feapder[all]
+pip install "feapder[all]"
 ```
 
-通用版与完整版区别：
+三个版本区别：
 
-1. 完整版支持基于内存去重
+1. 精简版：不支持浏览器渲染、不支持基于内存去重、不支持入库mongo
+2. 浏览器渲染版：不支持基于内存去重、不支持入库mongo
+3. 完整版：支持所有功能
 
 完整版可能会安装出错，若安装出错，请参考[安装问题](question/安装问题)
 
 ## 小试一下
 
 创建爬虫
 
@@ -95,30 +102,30 @@
 ```
 
 代码解释如下：
 
 1. start_requests： 生产任务
 2. parse： 解析数据
 
-## 爬虫工具推荐
-
-1. 爬虫在线工具库：http://www.spidertools.cn
-2. 爬虫管理系统：http://feapder.com/#/feapder_platform/feaplat
-3. 验证码识别库：https://github.com/sml2h3/ddddocr
-
 ## 参与贡献
 
 贡献之前请先阅读 [贡献指南](./CONTRIBUTING.md)
 
 感谢所有做过贡献的人!
 
 <a href="https://github.com/Boris-code/feapder/graphs/contributors">
   <img src="https://contrib.rocks/image?repo=Boris-code/feapder" />
 </a>
 
+## 爬虫工具推荐
+
+1. 爬虫在线工具库：http://www.spidertools.cn
+2. 爬虫管理系统：http://feapder.com/#/feapder_platform/feaplat
+3. 验证码识别库：https://github.com/sml2h3/ddddocr
+
 ## 微信赞赏
 
 如果您觉得这个项目帮助到了您，您可以帮作者买一杯咖啡表示鼓励 🍹
 
 也可和作者交个朋友，解决您在使用过程中遇到的问题
```

### Comparing `feapder-1.8.6b7/feapder/__init__.py` & `feapder-1.8.7b1/feapder/__init__.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/buffer/item_buffer.py` & `feapder-1.8.7b1/feapder/buffer/item_buffer.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/buffer/request_buffer.py` & `feapder-1.8.7b1/feapder/buffer/request_buffer.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/cmdline.py` & `feapder-1.8.7b1/feapder/commands/cmdline.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/create/__init__.py` & `feapder-1.8.7b1/feapder/commands/create/__init__.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/create/create_cookies.py` & `feapder-1.8.7b1/feapder/commands/create/create_cookies.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/create/create_init.py` & `feapder-1.8.7b1/feapder/commands/create/create_init.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/create/create_item.py` & `feapder-1.8.7b1/feapder/commands/create/create_item.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/create/create_json.py` & `feapder-1.8.7b1/feapder/commands/create/create_json.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/create/create_params.py` & `feapder-1.8.7b1/feapder/commands/create/create_params.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/create/create_project.py` & `feapder-1.8.7b1/feapder/commands/create/create_project.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/create/create_setting.py` & `feapder-1.8.7b1/feapder/commands/create/create_setting.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/create/create_spider.py` & `feapder-1.8.7b1/feapder/commands/create/create_spider.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/create/create_table.py` & `feapder-1.8.7b1/feapder/commands/create/create_table.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/create_builder.py` & `feapder-1.8.7b1/feapder/commands/create_builder.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/retry.py` & `feapder-1.8.7b1/feapder/commands/retry.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/shell.py` & `feapder-1.8.7b1/feapder/commands/shell.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/commands/zip.py` & `feapder-1.8.7b1/feapder/commands/zip.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/core/base_parser.py` & `feapder-1.8.7b1/feapder/core/base_parser.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/core/collector.py` & `feapder-1.8.7b1/feapder/core/collector.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/core/handle_failed_items.py` & `feapder-1.8.7b1/feapder/core/handle_failed_items.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/core/handle_failed_requests.py` & `feapder-1.8.7b1/feapder/core/handle_failed_requests.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/core/parser_control.py` & `feapder-1.8.7b1/feapder/core/parser_control.py`

 * *Files 2% similar despite different names*

```diff
@@ -234,14 +234,16 @@
                         str(type(e)).replace("<class '", "").replace("'>", "")
                     )
                     if exception_type.startswith("requests"):
                         # 记录下载失败的文档
                         self.record_download_status(
                             ParserControl.DOWNLOAD_EXCEPTION, parser.name
                         )
+                        if request.retry_times % setting.PROXY_MAX_FAILED_TIMES == 0:
+                            request.del_proxy()
 
                     else:
                         # 记录解析程序异常
                         self.record_download_status(
                             ParserControl.PAESERS_EXCEPTION, parser.name
                         )
 
@@ -607,14 +609,16 @@
                         str(type(e)).replace("<class '", "").replace("'>", "")
                     )
                     if exception_type.startswith("requests"):
                         # 记录下载失败的文档
                         self.record_download_status(
                             ParserControl.DOWNLOAD_EXCEPTION, parser.name
                         )
+                        if request.retry_times % setting.PROXY_MAX_FAILED_TIMES == 0:
+                            request.del_proxy()
 
                     else:
                         # 记录解析程序异常
                         self.record_download_status(
                             ParserControl.PAESERS_EXCEPTION, parser.name
                         )
```

### Comparing `feapder-1.8.6b7/feapder/core/scheduler.py` & `feapder-1.8.7b1/feapder/core/scheduler.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/core/spiders/air_spider.py` & `feapder-1.8.7b1/feapder/core/spiders/air_spider.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/core/spiders/batch_spider.py` & `feapder-1.8.7b1/feapder/core/spiders/batch_spider.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/core/spiders/spider.py` & `feapder-1.8.7b1/feapder/core/spiders/spider.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/core/spiders/task_spider.py` & `feapder-1.8.7b1/feapder/core/spiders/task_spider.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/db/memorydb.py` & `feapder-1.8.7b1/feapder/db/memorydb.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/db/mongodb.py` & `feapder-1.8.7b1/feapder/db/mongodb.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/db/mysqldb.py` & `feapder-1.8.7b1/feapder/db/mysqldb.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/db/redisdb.py` & `feapder-1.8.7b1/feapder/db/redisdb.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,24 +2,22 @@
 """
 Created on 2016-11-16 16:25
 ---------
 @summary: 操作redis数据库
 ---------
 @author: Boris
 """
-
+import os
 import time
 
 import redis
-from redis._compat import unicode, long, basestring
 from redis.connection import Encoder as _Encoder
 from redis.exceptions import ConnectionError, TimeoutError
 from redis.exceptions import DataError
 from redis.sentinel import Sentinel
-from rediscluster import RedisCluster
 
 import feapder.setting as setting
 from feapder.utils.log import log
 
 
 class Encoder(_Encoder):
     def encode(self, value):
@@ -30,27 +28,27 @@
         #     # special case bool since it is a subclass of int
         #     raise DataError(
         #         "Invalid input of type: 'bool'. Convert to a "
         #         "bytes, string, int or float first."
         #     )
         elif isinstance(value, float):
             value = repr(value).encode()
-        elif isinstance(value, (int, long)):
+        elif isinstance(value, int):
             # python 2 repr() on longs is '123L', so use str() instead
             value = str(value).encode()
         elif isinstance(value, (list, dict, tuple)):
-            value = unicode(value)
-        elif not isinstance(value, basestring):
+            value = str(value)
+        elif not isinstance(value, str):
             # a value we don't know how to deal with. throw an error
             typename = type(value).__name__
             raise DataError(
                 "Invalid input of type: '%s'. Convert to a "
                 "bytes, string, int or float first." % typename
             )
-        if isinstance(value, unicode):
+        if isinstance(value, str):
             value = value.encode(self.encoding, self.encoding_errors)
         return value
 
 
 redis.connection.Encoder = Encoder
 
 
@@ -154,14 +152,20 @@
                             redis_class=redis.StrictRedis,
                             decode_responses=self._decode_responses,
                             max_connections=self._max_connections,
                             **self._kwargs,
                         )
 
                     else:
+                        try:
+                            from rediscluster import RedisCluster
+                        except ModuleNotFoundError as e:
+                            log.error('请安装 pip install "feapder[all]"')
+                            os._exit(0)
+
                         # log.debug("使用redis集群模式")
                         self._redis = RedisCluster(
                             startup_nodes=startup_nodes,
                             decode_responses=self._decode_responses,
                             password=self._user_pass,
                             max_connections=self._max_connections,
                             **self._kwargs,
@@ -581,15 +585,14 @@
         else:
             is_exists = self._redis.zscore(table, values)
             is_exists = 1 if is_exists != None else 0
 
         return is_exists
 
     def lpush(self, table, values):
-
         if isinstance(values, list):
             pipe = self._redis.pipeline()
 
             if not self._is_redis_cluster:
                 pipe.multi()
             for value in values:
                 pipe.rpush(table, value)
```

### Comparing `feapder-1.8.6b7/feapder/dedup/__init__.py` & `feapder-1.8.7b1/feapder/dedup/__init__.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/dedup/basefilter.py` & `feapder-1.8.7b1/feapder/dedup/basefilter.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/dedup/bitarray.py` & `feapder-1.8.7b1/feapder/dedup/bitarray.py`

 * *Files 0% similar despite different names*

```diff
@@ -44,15 +44,15 @@
 
 class MemoryBitArray(BitArray):
     def __init__(self, num_bits):
         try:
             import bitarray
         except Exception as e:
             raise Exception(
-                "需要安装feapder完整版\ncommand: pip install feapder[all]\n若安装出错，参考：https://feapder.com/#/question/%E5%AE%89%E8%A3%85%E9%97%AE%E9%A2%98"
+                '需要安装feapder完整版\ncommand: pip install "feapder[all]"\n若安装出错，参考：https://feapder.com/#/question/%E5%AE%89%E8%A3%85%E9%97%AE%E9%A2%98'
             )
 
         self.num_bits = num_bits
         self.bitarray = bitarray.bitarray(num_bits, endian="little")
 
         self.setall(0)
```

### Comparing `feapder-1.8.6b7/feapder/dedup/bloomfilter.py` & `feapder-1.8.7b1/feapder/dedup/bloomfilter.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/dedup/expirefilter.py` & `feapder-1.8.7b1/feapder/dedup/expirefilter.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/dedup/litefilter.py` & `feapder-1.8.7b1/feapder/dedup/litefilter.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/network/downloader/_playwright.py` & `feapder-1.8.7b1/feapder/network/downloader/_playwright.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/network/downloader/_requests.py` & `feapder-1.8.7b1/feapder/network/downloader/_requests.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/network/downloader/_selenium.py` & `feapder-1.8.7b1/feapder/network/downloader/_selenium.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/network/downloader/base.py` & `feapder-1.8.7b1/feapder/network/downloader/base.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/network/item.py` & `feapder-1.8.7b1/feapder/network/item.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/network/proxy_pool.py` & `feapder-1.8.7b1/feapder/network/proxy_pool_old.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/network/request.py` & `feapder-1.8.7b1/feapder/network/request.py`

 * *Files 2% similar despite different names*

```diff
@@ -5,14 +5,15 @@
 @summary: 请求结构体
 ---------
 @author: Boris
 @email:  boris_liu@foxmail.com
 """
 
 import copy
+import os
 import re
 
 import requests
 from requests.cookies import RequestsCookieJar
 from requests.packages.urllib3.exceptions import InsecureRequestWarning
 
 import feapder.setting as setting
@@ -220,17 +221,21 @@
             )()
 
         return self.__class__.session_downloader
 
     @property
     def _render_downloader(self):
         if not self.__class__.render_downloader:
-            self.__class__.render_downloader = tools.import_cls(
-                setting.RENDER_DOWNLOADER
-            )()
+            try:
+                self.__class__.render_downloader = tools.import_cls(
+                    setting.RENDER_DOWNLOADER
+                )()
+            except AttributeError:
+                log.error('当前是渲染模式，请安装 pip install "feapder[render]"')
+                os._exit(0)
 
         return self.__class__.render_downloader
 
     @property
     def to_dict(self):
         request_dict = {}
 
@@ -418,14 +423,20 @@
         """
         proxies = self.get_proxies()
         if proxies:
             return re.sub(
                 "http.*?//", "", proxies.get("http", "") or proxies.get("https", "")
             )
 
+    def del_proxy(self):
+        proxy = self.get_proxy()
+        if proxy:
+            self._proxies_pool.del_proxy(proxy)
+            del self.requests_kwargs["proxies"]
+
     def get_headers(self) -> dict:
         return self.requests_kwargs.get("headers", {})
 
     def get_user_agent(self) -> str:
         return self.get_headers().get("user_agent") or self.get_headers().get(
             "User-Agent"
         )
```

### Comparing `feapder-1.8.6b7/feapder/network/response.py` & `feapder-1.8.7b1/feapder/network/response.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/network/selector.py` & `feapder-1.8.7b1/feapder/network/selector.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/network/user_pool/base_user_pool.py` & `feapder-1.8.7b1/feapder/network/user_pool/base_user_pool.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/network/user_pool/gold_user_pool.py` & `feapder-1.8.7b1/feapder/network/user_pool/gold_user_pool.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/network/user_pool/guest_user_pool.py` & `feapder-1.8.7b1/feapder/network/user_pool/guest_user_pool.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/network/user_pool/normal_user_pool.py` & `feapder-1.8.7b1/feapder/network/user_pool/normal_user_pool.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/pipelines/__init__.py` & `feapder-1.8.7b1/feapder/pipelines/__init__.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/pipelines/console_pipeline.py` & `feapder-1.8.7b1/feapder/pipelines/console_pipeline.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/pipelines/mongo_pipeline.py` & `feapder-1.8.7b1/feapder/pipelines/mongo_pipeline.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/pipelines/mysql_pipeline.py` & `feapder-1.8.7b1/feapder/pipelines/mysql_pipeline.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/setting.py` & `feapder-1.8.7b1/feapder/setting.py`

 * *Files 2% similar despite different names*

```diff
@@ -128,14 +128,15 @@
 REDIS_KEY = ""
 # 爬虫启动时删除的key，类型: 元组/bool/string。 支持正则; 常用于清空任务队列，否则重启时会断点续爬
 DELETE_KEYS = []
 
 # 设置代理
 PROXY_EXTRACT_API = None  # 代理提取API ，返回的代理分割符为\r\n
 PROXY_ENABLE = True
+PROXY_MAX_FAILED_TIMES = 5  # 代理最大失败次数，超过则不使用，自动删除
 
 # 随机headers
 RANDOM_HEADERS = True
 # UserAgent类型 支持 'chrome', 'opera', 'firefox', 'internetexplorer', 'safari'，'mobile' 若不指定则随机类型
 USER_AGENT_TYPE = "chrome"
 # 默认使用的浏览器头
 DEFAULT_USERAGENT = "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_2) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.103 Safari/537.36"
```

### Comparing `feapder-1.8.6b7/feapder/templates/.DS_Store` & `feapder-1.8.7b1/feapder/templates/.DS_Store`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/templates/air_spider_template.tmpl` & `feapder-1.8.7b1/feapder/templates/air_spider_template.tmpl`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/templates/batch_spider_template.tmpl` & `feapder-1.8.7b1/feapder/templates/batch_spider_template.tmpl`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/templates/project_template/.DS_Store` & `feapder-1.8.7b1/feapder/templates/project_template/.DS_Store`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/templates/project_template/CHECK_DATA.md` & `feapder-1.8.7b1/feapder/templates/project_template/CHECK_DATA.md`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/templates/project_template/main.py` & `feapder-1.8.7b1/feapder/templates/project_template/main.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/templates/project_template/setting.py` & `feapder-1.8.7b1/feapder/templates/project_template/setting.py`

 * *Files 2% similar despite different names*

```diff
@@ -117,14 +117,15 @@
 # RESPONSE_CACHED_ENABLE = False  # 是否启用下载缓存 成本高的数据或容易变需求的数据，建议设置为True
 # RESPONSE_CACHED_EXPIRE_TIME = 3600  # 缓存时间 秒
 # RESPONSE_CACHED_USED = False  # 是否使用缓存 补采数据时可设置为True
 #
 # # 设置代理
 # PROXY_EXTRACT_API = None  # 代理提取API ，返回的代理分割符为\r\n
 # PROXY_ENABLE = True
+# PROXY_MAX_FAILED_TIMES = 5  # 代理最大失败次数，超过则不使用，自动删除
 #
 # # 随机headers
 # RANDOM_HEADERS = True
 # # UserAgent类型 支持 'chrome', 'opera', 'firefox', 'internetexplorer', 'safari'，'mobile' 若不指定则随机类型
 # USER_AGENT_TYPE = "chrome"
 # # 默认使用的浏览器头
 # DEFAULT_USERAGENT = "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_14_2) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/73.0.3683.103 Safari/537.36"
```

### Comparing `feapder-1.8.6b7/feapder/templates/spider_template.tmpl` & `feapder-1.8.7b1/feapder/templates/spider_template.tmpl`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/templates/task_spider_template.tmpl` & `feapder-1.8.7b1/feapder/templates/task_spider_template.tmpl`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/utils/custom_argparse.py` & `feapder-1.8.7b1/feapder/utils/custom_argparse.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/utils/email_sender.py` & `feapder-1.8.7b1/feapder/utils/email_sender.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/utils/js/intercept.js` & `feapder-1.8.7b1/feapder/utils/js/intercept.js`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/utils/js/stealth.min.js` & `feapder-1.8.7b1/feapder/utils/js/stealth.min.js`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/utils/log.py` & `feapder-1.8.7b1/feapder/utils/log.py`

 * *Files 4% similar despite different names*

```diff
@@ -63,15 +63,14 @@
             # Issue 18940: A file may not have been created if delay is True.
             if os.path.exists(self.baseFilename):
                 os.rename(self.baseFilename, dfn)
         if not self.delay:
             self.stream = self._open()
 
     def shouldRollover(self, record):
-
         if self.stream is None:  # delay was set...
             self.stream = self._open()
         if self.max_bytes > 0:  # are we rolling over?
             msg = "%s\n" % self.format(record)
             self.stream.seek(0, 2)  # due to non-posix-compliant Windows feature
             if self.stream.tell() + len(msg) >= self.max_bytes:
                 return 1
@@ -221,14 +220,21 @@
 
 # 日志级别大小关系为：CRITICAL > ERROR > WARNING > INFO > DEBUG
 
 
 class Log:
     log = None
 
+    def func(self, log_level):
+        def wrapper(msg, *args, **kwargs):
+            if self.isEnabledFor(log_level):
+                self._log(log_level, msg, args, **kwargs)
+
+        return wrapper
+
     def __getattr__(self, name):
         # 调用log时再初始化，为了加载最新的setting
         if self.__class__.log is None:
             self.__class__.log = get_logger()
         return getattr(self.__class__.log, name)
 
     @property
@@ -236,14 +242,20 @@
         return self.__class__.log.debug
 
     @property
     def info(self):
         return self.__class__.log.info
 
     @property
+    def success(self):
+        log_level = logging.INFO + 1
+        logging.addLevelName(log_level, "success".upper())
+        return self.func(log_level)
+
+    @property
     def warning(self):
         return self.__class__.log.warning
 
     @property
     def exception(self):
         return self.__class__.log.exception
```

### Comparing `feapder-1.8.6b7/feapder/utils/metrics.py` & `feapder-1.8.7b1/feapder/utils/metrics.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/utils/perfect_dict.py` & `feapder-1.8.7b1/feapder/utils/perfect_dict.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/utils/redis_lock.py` & `feapder-1.8.7b1/feapder/utils/redis_lock.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/utils/tools.py` & `feapder-1.8.7b1/feapder/utils/tools.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/utils/webdriver/playwright_driver.py` & `feapder-1.8.7b1/feapder/utils/webdriver/playwright_driver.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/utils/webdriver/selenium_driver.py` & `feapder-1.8.7b1/feapder/utils/webdriver/selenium_driver.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/utils/webdriver/webdirver.py` & `feapder-1.8.7b1/feapder/utils/webdriver/webdirver.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder/utils/webdriver/webdriver_pool.py` & `feapder-1.8.7b1/feapder/utils/webdriver/webdriver_pool.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/feapder.egg-info/PKG-INFO` & `feapder-1.8.7b1/feapder.egg-info/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,19 +1,20 @@
 Metadata-Version: 2.1
 Name: feapder
-Version: 1.8.6b7
-Summary: feapder是一款支持分布式、批次采集、任务防丢、报警丰富的python爬虫框架
+Version: 1.8.7b1
+Summary: feapder是一款支持分布式、批次采集、数据防丢、报警丰富的python爬虫框架
 Home-page: https://github.com/Boris-code/feapder.git
 Author: Boris
 Author-email: feapder@qq.com
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3.6
 Description-Content-Type: text/markdown
 Provides-Extra: all
+Provides-Extra: render
 License-File: LICENSE
 
 # FEAPDER
 
 ![](https://img.shields.io/badge/python-3.6-brightgreen)
 ![](https://img.shields.io/github/watchers/Boris-code/feapder?style=social)
 ![](https://img.shields.io/github/stars/Boris-code/feapder?style=social)
@@ -45,29 +46,36 @@
 - Python 3.6.0+
 - Works on Linux, Windows, macOS
 
 ## 安装
 
 From PyPi:
 
-通用版
+精简版
 
 ```shell
-pip3 install feapder
+pip install feapder
+```
+
+浏览器渲染版：
+```shell
+pip install "feapder[render]"
 ```
 
 完整版：
 
 ```shell
-pip3 install feapder[all]
+pip install "feapder[all]"
 ```
 
-通用版与完整版区别：
+三个版本区别：
 
-1. 完整版支持基于内存去重
+1. 精简版：不支持浏览器渲染、不支持基于内存去重、不支持入库mongo
+2. 浏览器渲染版：不支持基于内存去重、不支持入库mongo
+3. 完整版：支持所有功能
 
 完整版可能会安装出错，若安装出错，请参考[安装问题](question/安装问题)
 
 ## 小试一下
 
 创建爬虫
 
@@ -109,30 +117,30 @@
 ```
 
 代码解释如下：
 
 1. start_requests： 生产任务
 2. parse： 解析数据
 
-## 爬虫工具推荐
-
-1. 爬虫在线工具库：http://www.spidertools.cn
-2. 爬虫管理系统：http://feapder.com/#/feapder_platform/feaplat
-3. 验证码识别库：https://github.com/sml2h3/ddddocr
-
 ## 参与贡献
 
 贡献之前请先阅读 [贡献指南](./CONTRIBUTING.md)
 
 感谢所有做过贡献的人!
 
 <a href="https://github.com/Boris-code/feapder/graphs/contributors">
   <img src="https://contrib.rocks/image?repo=Boris-code/feapder" />
 </a>
 
+## 爬虫工具推荐
+
+1. 爬虫在线工具库：http://www.spidertools.cn
+2. 爬虫管理系统：http://feapder.com/#/feapder_platform/feaplat
+3. 验证码识别库：https://github.com/sml2h3/ddddocr
+
 ## 微信赞赏
 
 如果您觉得这个项目帮助到了您，您可以帮作者买一杯咖啡表示鼓励 🍹
 
 也可和作者交个朋友，解决您在使用过程中遇到的问题
```

### Comparing `feapder-1.8.6b7/feapder.egg-info/SOURCES.txt` & `feapder-1.8.7b1/feapder.egg-info/SOURCES.txt`

 * *Files 6% similar despite different names*

```diff
@@ -53,14 +53,15 @@
 feapder/dedup/bitarray.py
 feapder/dedup/bloomfilter.py
 feapder/dedup/expirefilter.py
 feapder/dedup/litefilter.py
 feapder/network/__init__.py
 feapder/network/item.py
 feapder/network/proxy_pool.py
+feapder/network/proxy_pool_old.py
 feapder/network/request.py
 feapder/network/response.py
 feapder/network/selector.py
 feapder/network/user_agent.py
 feapder/network/downloader/__init__.py
 feapder/network/downloader/_playwright.py
 feapder/network/downloader/_requests.py
@@ -111,15 +112,14 @@
 tests/test_lock.py
 tests/test_log.py
 tests/test_metrics.py
 tests/test_mongodb.py
 tests/test_mysqldb.py
 tests/test_playwright.py
 tests/test_playwright2.py
-tests/test_proxies_pool.py
 tests/test_rander.py
 tests/test_rander2.py
 tests/test_rander3.py
 tests/test_rander_xhr.py
 tests/test_redisdb.py
 tests/test_request.py
 tests/test_spider_params.py
@@ -157,14 +157,21 @@
 tests/spider/items/__init__.py
 tests/spider/items/spider_data_item.py
 tests/spider/log/haha.log
 tests/spider/spiders/__init__.py
 tests/spider/spiders/test_spider.py
 tests/spider/spiders/test_spider2.py
 tests/task-spider/test_task_spider.py
+tests/test-debugger/.DS_Store
+tests/test-debugger/README.md
+tests/test-debugger/main.py
+tests/test-debugger/setting.py
+tests/test-debugger/items/__init__.py
+tests/test-debugger/spiders/__init__.py
+tests/test-debugger/spiders/test_debugger.py
 tests/test-pipeline/main.py
 tests/test-pipeline/pipeline.py
 tests/test-pipeline/setting.py
 tests/test-pipeline/table.sql
 tests/test-pipeline/items/__init__.py
 tests/test-pipeline/items/spider_data_item.py
 tests/test-pipeline/spiders/__init__.py
```

### Comparing `feapder-1.8.6b7/setup.py` & `feapder-1.8.7b1/setup.py`

 * *Files 14% similar despite different names*

```diff
@@ -38,40 +38,46 @@
     "DBUtils>=2.0",
     "parsel>=1.5.2",
     "PyMySQL>=0.9.3",
     "redis>=2.10.6,<4.0.0",
     "requests>=2.22.0",
     "bs4>=0.0.1",
     "ipython>=7.14.0",
-    "redis-py-cluster>=2.1.0",
     "cryptography>=3.3.2",
-    "selenium>=3.141.0",
-    "pymongo>=3.10.1",
     "urllib3>=1.25.8",
     "loguru>=0.5.3",
     "influxdb>=5.3.1",
     "pyperclip>=1.8.2",
-    "webdriver-manager>=3.5.3",
     "terminal-layout>=2.1.3",
+]
+
+render_requires = [
+    "webdriver-manager>=3.5.3",
     "playwright",
+    "selenium>=3.141.0",
 ]
 
-extras_requires = ["bitarray>=1.5.3", "PyExecJS>=1.5.1"]
+all_requires = [
+    "bitarray>=1.5.3",
+    "PyExecJS>=1.5.1",
+    "pymongo>=3.10.1",
+    "redis-py-cluster>=2.1.0",
+] + render_requires
 
 setuptools.setup(
     name="feapder",
     version=version,
     author="Boris",
     license="MIT",
     author_email="feapder@qq.com",
     python_requires=">=3.6",
-    description="feapder是一款支持分布式、批次采集、任务防丢、报警丰富的python爬虫框架",
+    description="feapder是一款支持分布式、批次采集、数据防丢、报警丰富的python爬虫框架",
     long_description=long_description,
     long_description_content_type="text/markdown",
     install_requires=requires,
-    extras_require={"all": extras_requires},
+    extras_require={"all": all_requires, "render": render_requires},
     entry_points={"console_scripts": ["feapder = feapder.commands.cmdline:execute"]},
     url="https://github.com/Boris-code/feapder.git",
     packages=packages,
     include_package_data=True,
     classifiers=["Programming Language :: Python :: 3"],
 )
```

### Comparing `feapder-1.8.6b7/tests/air-spider/test_air_spider.py` & `feapder-1.8.7b1/tests/air-spider/test_air_spider.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/air-spider/test_air_spider_filter.py` & `feapder-1.8.7b1/tests/air-spider/test_air_spider_filter.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/air-spider/test_air_spider_item.py` & `feapder-1.8.7b1/tests/air-spider/test_air_spider_item.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/air-spider/test_render_spider.py` & `feapder-1.8.7b1/tests/air-spider/test_render_spider.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/batch-spider/items/spider_data_item.py` & `feapder-1.8.7b1/tests/batch-spider/items/spider_data_item.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/batch-spider/main.py` & `feapder-1.8.7b1/tests/batch-spider/main.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/batch-spider/setting.py` & `feapder-1.8.7b1/tests/batch-spider/setting.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/batch-spider/spiders/test_spider.py` & `feapder-1.8.7b1/tests/test-pipeline/spiders/test_spider.py`

 * *Files 8% similar despite different names*

```diff
@@ -45,8 +45,10 @@
         ---------
         @param request:
         ---------
         @result: request / item / callback / None (返回值必须可迭代)
         """
 
         yield request
-        yield self.update_task_batch(request.task_id, -1)  # 更新任务状态为-1
+        yield self.update_task_batch(request.task_id, -1) # 更新任务状态为-1
+
+
```

### Comparing `feapder-1.8.6b7/tests/batch-spider/table.sql` & `feapder-1.8.7b1/tests/batch-spider/table.sql`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/batch-spider-integration/batch_spider_integration_task.sql` & `feapder-1.8.7b1/tests/batch-spider-integration/batch_spider_integration_task.sql`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/batch-spider-integration/main.py` & `feapder-1.8.7b1/tests/batch-spider-integration/main.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/batch-spider-integration/setting.py` & `feapder-1.8.7b1/tests/batch-spider-integration/setting.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/batch-spider-integration/spiders/sina_news_parser.py` & `feapder-1.8.7b1/tests/batch-spider-integration/spiders/sina_news_parser.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/batch-spider-integration/spiders/tencent_news_parser.py` & `feapder-1.8.7b1/tests/batch-spider-integration/spiders/tencent_news_parser.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/jd_spider.py` & `feapder-1.8.7b1/tests/jd_spider.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/mongo_spider.py` & `feapder-1.8.7b1/tests/mongo_spider.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/spider/log/haha.log` & `feapder-1.8.7b1/tests/spider/log/haha.log`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/spider/setting.py` & `feapder-1.8.7b1/tests/spider/setting.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/spider/spiders/test_spider.py` & `feapder-1.8.7b1/tests/spider/spiders/test_spider.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/spider/spiders/test_spider2.py` & `feapder-1.8.7b1/tests/spider/spiders/test_spider2.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/spider-integration/main.py` & `feapder-1.8.7b1/tests/spider-integration/main.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/spider-integration/setting.py` & `feapder-1.8.7b1/tests/spider-integration/setting.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/task-spider/test_task_spider.py` & `feapder-1.8.7b1/tests/task-spider/test_task_spider.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test-pipeline/items/spider_data_item.py` & `feapder-1.8.7b1/tests/test-pipeline/items/spider_data_item.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test-pipeline/main.py` & `feapder-1.8.7b1/tests/test-pipeline/main.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test-pipeline/pipeline.py` & `feapder-1.8.7b1/tests/test-pipeline/pipeline.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test-pipeline/setting.py` & `feapder-1.8.7b1/tests/test-pipeline/setting.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test-pipeline/spiders/test_spider.py` & `feapder-1.8.7b1/tests/batch-spider/spiders/test_spider.py`

 * *Files 11% similar despite different names*

```diff
@@ -14,15 +14,15 @@
 class TestSpider(feapder.BatchSpider):
     # def init_task(self):
     #     pass
 
     def start_requests(self, task):
         # task 为在任务表中取出的每一条任务
         id, url = task  # id， url为所取的字段，main函数中指定的
-        yield feapder.Request(url, task_id=id)
+        yield feapder.Request(url, task_id=id, render=True)  # task_id为任务id，用于更新任务状态
 
     def parse(self, request, response):
         title = response.xpath('//title/text()').extract_first()  # 取标题
         item = spider_data_item.SpiderDataItem()  # 声明一个item
         item.title = title  # 给item属性赋值
         yield item  # 返回item， item会自动批量入库
         yield self.update_task_batch(request.task_id, 1) # 更新任务状态为1
@@ -45,10 +45,8 @@
         ---------
         @param request:
         ---------
         @result: request / item / callback / None (返回值必须可迭代)
         """
 
         yield request
-        yield self.update_task_batch(request.task_id, -1) # 更新任务状态为-1
-
-
+        yield self.update_task_batch(request.task_id, -1)  # 更新任务状态为-1
```

### Comparing `feapder-1.8.6b7/tests/test-pipeline/table.sql` & `feapder-1.8.7b1/tests/test-pipeline/table.sql`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_dedup.py` & `feapder-1.8.7b1/tests/test_dedup.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_metrics.py` & `feapder-1.8.7b1/tests/test_metrics.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_mongodb.py` & `feapder-1.8.7b1/tests/test_mongodb.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_playwright.py` & `feapder-1.8.7b1/tests/test_playwright.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_playwright2.py` & `feapder-1.8.7b1/tests/test_playwright2.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_rander.py` & `feapder-1.8.7b1/tests/test_rander.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_rander2.py` & `feapder-1.8.7b1/tests/test_rander2.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_rander3.py` & `feapder-1.8.7b1/tests/test_rander3.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_rander_xhr.py` & `feapder-1.8.7b1/tests/test_rander_xhr.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_request.py` & `feapder-1.8.7b1/tests/test_request.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_spider_params.py` & `feapder-1.8.7b1/tests/test_spider_params.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_task.py` & `feapder-1.8.7b1/tests/test_task.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_template/test_spider.py` & `feapder-1.8.7b1/tests/test_template/test_spider.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/test_webdriver.py` & `feapder-1.8.7b1/tests/test_webdriver.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/user_pool/test_gold_user_pool.py` & `feapder-1.8.7b1/tests/user_pool/test_gold_user_pool.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/user_pool/test_guest_user_pool.py` & `feapder-1.8.7b1/tests/user_pool/test_guest_user_pool.py`

 * *Files identical despite different names*

### Comparing `feapder-1.8.6b7/tests/user_pool/test_normal_user_pool.py` & `feapder-1.8.7b1/tests/user_pool/test_normal_user_pool.py`

 * *Files identical despite different names*

