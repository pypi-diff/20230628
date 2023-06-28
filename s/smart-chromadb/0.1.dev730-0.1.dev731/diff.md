# Comparing `tmp/smart_chromadb-0.1.dev730.tar.gz` & `tmp/smart_chromadb-0.1.dev731.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "/Users/johnyan/Documents/project/chroma/dist/.tmp-by6e64ro/smart_chromadb-0.1.dev730.tar", last modified: Mon Jun 26 07:04:08 2023, max compression
+gzip compressed data, was "/Users/johnyan/Documents/project/chroma/dist/.tmp-5twmxy3t/smart_chromadb-0.1.dev731.tar", last modified: Wed Jun 28 02:16:30 2023, max compression
```

## Comparing `smart_chromadb-0.1.dev730.tar` & `smart_chromadb-0.1.dev731.tar`

### file list

```diff
@@ -1,231 +1,232 @@
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.584658 smart_chromadb-0.1.dev730/
--rw-r--r--   0 johnyan    (501) staff       (20)       84 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.dockerignore
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.304642 smart_chromadb-0.1.dev730/.github/
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.341766 smart_chromadb-0.1.dev730/.github/ISSUE_TEMPLATE/
--rw-r--r--   0 johnyan    (501) staff       (20)     1512 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.github/ISSUE_TEMPLATE/bug_report.yaml
--rw-r--r--   0 johnyan    (501) staff       (20)     1520 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.github/ISSUE_TEMPLATE/feature_request.yaml
--rw-r--r--   0 johnyan    (501) staff       (20)     1384 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.github/ISSUE_TEMPLATE/installation_trouble.yaml
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.348437 smart_chromadb-0.1.dev730/.github/workflows/
--rw-r--r--   0 johnyan    (501) staff       (20)      711 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.github/workflows/chroma-client-integration-test.yml
--rw-r--r--   0 johnyan    (501) staff       (20)     1187 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.github/workflows/chroma-integration-test.yml
--rw-r--r--   0 johnyan    (501) staff       (20)     1338 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.github/workflows/chroma-release-python-client.yml
--rw-r--r--   0 johnyan    (501) staff       (20)     4169 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.github/workflows/chroma-release.yml
--rw-r--r--   0 johnyan    (501) staff       (20)     1205 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.github/workflows/chroma-test.yml
--rw-r--r--   0 johnyan    (501) staff       (20)     1734 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.github/workflows/pr-review-checklist.yml
--rw-r--r--   0 johnyan    (501) staff       (20)      228 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.gitignore
--rw-r--r--   0 johnyan    (501) staff       (20)     1167 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.pre-commit-config.yaml
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.349140 smart_chromadb-0.1.dev730/.vscode/
--rw-r--r--   0 johnyan    (501) staff       (20)     1020 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/.vscode/settings.json
--rw-r--r--   0 johnyan    (501) staff       (20)     3323 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/DEVELOP.md
--rw-r--r--   0 johnyan    (501) staff       (20)      647 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/Dockerfile
--rw-r--r--   0 johnyan    (501) staff       (20)    11357 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/LICENSE
--rw-r--r--   0 johnyan    (501) staff       (20)     6220 2023-06-26 07:04:08.583960 smart_chromadb-0.1.dev730/PKG-INFO
--rw-r--r--   0 johnyan    (501) staff       (20)     5679 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/README.md
--rw-r--r--   0 johnyan    (501) staff       (20)      619 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/RELEASE_PROCESS.md
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.364423 smart_chromadb-0.1.dev730/bin/
--rw-r--r--   0 johnyan    (501) staff       (20)     1610 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/backup.sh
--rwxr-xr-x   0 johnyan    (501) staff       (20)      110 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/build
--rwxr-xr-x   0 johnyan    (501) staff       (20)      234 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/docker_entrypoint.sh
--rw-r--r--   0 johnyan    (501) staff       (20)     6462 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/generate_cloudformation.py
--rwxr-xr-x   0 johnyan    (501) staff       (20)      463 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/integration-test
--rw-r--r--   0 johnyan    (501) staff       (20)     1688 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/restore.sh
--rw-r--r--   0 johnyan    (501) staff       (20)     1105 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/setup_linux.sh
--rw-r--r--   0 johnyan    (501) staff       (20)      451 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/setup_mac.sh
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.365954 smart_chromadb-0.1.dev730/bin/templates/
--rw-r--r--   0 johnyan    (501) staff       (20)      985 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/templates/docker-compose.yml
--rwxr-xr-x   0 johnyan    (501) staff       (20)      451 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/test-package.sh
--rwxr-xr-x   0 johnyan    (501) staff       (20)      297 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/test-remote
--rw-r--r--   0 johnyan    (501) staff       (20)      205 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/test.py
--rwxr-xr-x   0 johnyan    (501) staff       (20)      151 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/bin/version
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.372599 smart_chromadb-0.1.dev730/chromadb/
--rw-r--r--   0 johnyan    (501) staff       (20)      894 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/__init__.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.380409 smart_chromadb-0.1.dev730/chromadb/api/
--rw-r--r--   0 johnyan    (501) staff       (20)    10898 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/api/__init__.py
--rw-r--r--   0 johnyan    (501) staff       (20)    12480 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/api/fastapi.py
--rw-r--r--   0 johnyan    (501) staff       (20)    17852 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/api/local.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.382186 smart_chromadb-0.1.dev730/chromadb/api/models/
--rw-r--r--   0 johnyan    (501) staff       (20)    15103 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/api/models/Collection.py
--rw-r--r--   0 johnyan    (501) staff       (20)    11270 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/api/types.py
--rw-r--r--   0 johnyan    (501) staff       (20)      168 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/app.py
--rw-r--r--   0 johnyan    (501) staff       (20)     6993 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/config.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.390694 smart_chromadb-0.1.dev730/chromadb/db/
--rw-r--r--   0 johnyan    (501) staff       (20)     3390 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/db/__init__.py
--rw-r--r--   0 johnyan    (501) staff       (20)     6004 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/db/base.py
--rw-r--r--   0 johnyan    (501) staff       (20)    22262 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/db/clickhouse.py
--rw-r--r--   0 johnyan    (501) staff       (20)    18795 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/db/duckdb.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.394794 smart_chromadb-0.1.dev730/chromadb/db/impl/
--rw-r--r--   0 johnyan    (501) staff       (20)        0 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/db/impl/__init__.py
--rw-r--r--   0 johnyan    (501) staff       (20)     6221 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/db/impl/sqlite.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.397973 smart_chromadb-0.1.dev730/chromadb/db/index/
--rw-r--r--   0 johnyan    (501) staff       (20)      447 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/db/index/__init__.py
--rw-r--r--   0 johnyan    (501) staff       (20)    11060 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/db/index/hnswlib.py
--rw-r--r--   0 johnyan    (501) staff       (20)     8096 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/db/migrations.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.400036 smart_chromadb-0.1.dev730/chromadb/db/mixins/
--rw-r--r--   0 johnyan    (501) staff       (20)     9193 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/db/mixins/embeddings_queue.py
--rw-r--r--   0 johnyan    (501) staff       (20)    15557 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/db/mixins/sysdb.py
--rw-r--r--   0 johnyan    (501) staff       (20)     2656 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/db/system.py
--rw-r--r--   0 johnyan    (501) staff       (20)     1293 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/errors.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.401298 smart_chromadb-0.1.dev730/chromadb/ingest/
--rw-r--r--   0 johnyan    (501) staff       (20)     3643 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/ingest/__init__.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.403150 smart_chromadb-0.1.dev730/chromadb/segment/
--rw-r--r--   0 johnyan    (501) staff       (20)     3059 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/segment/__init__.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.311159 smart_chromadb-0.1.dev730/chromadb/segment/impl/
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.405126 smart_chromadb-0.1.dev730/chromadb/segment/impl/manager/
--rw-r--r--   0 johnyan    (501) staff       (20)     4358 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/segment/impl/manager/local.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.405994 smart_chromadb-0.1.dev730/chromadb/segment/impl/metadata/
--rw-r--r--   0 johnyan    (501) staff       (20)    17879 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/segment/impl/metadata/sqlite.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.407602 smart_chromadb-0.1.dev730/chromadb/segment/impl/vector/
--rw-r--r--   0 johnyan    (501) staff       (20)    11965 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/segment/impl/vector/local_hnsw.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.408603 smart_chromadb-0.1.dev730/chromadb/server/
--rw-r--r--   0 johnyan    (501) staff       (20)      172 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/server/__init__.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.411280 smart_chromadb-0.1.dev730/chromadb/server/fastapi/
--rw-r--r--   0 johnyan    (501) staff       (20)     9064 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/server/fastapi/__init__.py
--rw-r--r--   0 johnyan    (501) staff       (20)     2134 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/server/fastapi/types.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.416839 smart_chromadb-0.1.dev730/chromadb/telemetry/
--rw-r--r--   0 johnyan    (501) staff       (20)     3214 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/telemetry/__init__.py
--rw-r--r--   0 johnyan    (501) staff       (20)      591 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/telemetry/events.py
--rw-r--r--   0 johnyan    (501) staff       (20)     1161 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/telemetry/posthog.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.420702 smart_chromadb-0.1.dev730/chromadb/test/
--rw-r--r--   0 johnyan    (501) staff       (20)     3993 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/conftest.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.426603 smart_chromadb-0.1.dev730/chromadb/test/db/
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.435554 smart_chromadb-0.1.dev730/chromadb/test/db/migrations/
--rw-r--r--   0 johnyan    (501) staff       (20)       51 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/db/migrations/00001-migration-1.psql.sql
--rw-r--r--   0 johnyan    (501) staff       (20)       51 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/db/migrations/00001-migration-1.sqlite.sql
--rw-r--r--   0 johnyan    (501) staff       (20)       51 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/db/migrations/00002-migration-2.psql.sql
--rw-r--r--   0 johnyan    (501) staff       (20)       51 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/db/migrations/00002-migration-2.sqlite.sql
--rw-r--r--   0 johnyan    (501) staff       (20)       51 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/db/migrations/00003-migration-3.psql.sql
--rw-r--r--   0 johnyan    (501) staff       (20)       51 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/db/migrations/00003-migration-3.sqlite.sql
--rw-r--r--   0 johnyan    (501) staff       (20)     1168 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/db/test_base.py
--rw-r--r--   0 johnyan    (501) staff       (20)     5026 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/db/test_migrations.py
--rw-r--r--   0 johnyan    (501) staff       (20)     9773 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/db/test_system.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.436899 smart_chromadb-0.1.dev730/chromadb/test/hnswlib/
--rw-r--r--   0 johnyan    (501) staff       (20)     2337 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/hnswlib/test_hnswlib.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.437961 smart_chromadb-0.1.dev730/chromadb/test/ingest/
--rw-r--r--   0 johnyan    (501) staff       (20)     8117 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/ingest/test_producer_consumer.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.450080 smart_chromadb-0.1.dev730/chromadb/test/property/
--rw-r--r--   0 johnyan    (501) staff       (20)    11294 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/property/invariants.py
--rw-r--r--   0 johnyan    (501) staff       (20)    18662 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/property/strategies.py
--rw-r--r--   0 johnyan    (501) staff       (20)     2213 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/property/test_add.py
--rw-r--r--   0 johnyan    (501) staff       (20)     6211 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/property/test_collections.py
--rw-r--r--   0 johnyan    (501) staff       (20)     9123 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/property/test_cross_version_persist.py
--rw-r--r--   0 johnyan    (501) staff       (20)    11073 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/property/test_embeddings.py
--rw-r--r--   0 johnyan    (501) staff       (20)     9062 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/property/test_filtering.py
--rw-r--r--   0 johnyan    (501) staff       (20)     5146 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/property/test_persist.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.455651 smart_chromadb-0.1.dev730/chromadb/test/segment/
--rw-r--r--   0 johnyan    (501) staff       (20)    15026 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/segment/test_metadata.py
--rw-r--r--   0 johnyan    (501) staff       (20)    12132 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/segment/test_vector.py
--rw-r--r--   0 johnyan    (501) staff       (20)    40340 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/test_api.py
--rw-r--r--   0 johnyan    (501) staff       (20)     2234 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/test_chroma.py
--rw-r--r--   0 johnyan    (501) staff       (20)     4127 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/test_config.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.457402 smart_chromadb-0.1.dev730/chromadb/test/utils/
--rw-r--r--   0 johnyan    (501) staff       (20)     3544 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/test/utils/test_messagid.py
--rw-r--r--   0 johnyan    (501) staff       (20)     3695 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/types.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.461688 smart_chromadb-0.1.dev730/chromadb/utils/
--rw-r--r--   0 johnyan    (501) staff       (20)        0 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/utils/__init__.py
--rw-r--r--   0 johnyan    (501) staff       (20)    16027 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/utils/embedding_functions.py
--rw-r--r--   0 johnyan    (501) staff       (20)     2301 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/chromadb/utils/messageid.py
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.317992 smart_chromadb-0.1.dev730/clients/
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.494345 smart_chromadb-0.1.dev730/clients/js/
--rw-r--r--   0 johnyan    (501) staff       (20)       66 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/.gitignore
--rw-r--r--   0 johnyan    (501) staff       (20)       32 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/.prettierignore
--rw-r--r--   0 johnyan    (501) staff       (20)        3 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/.prettierrc.json
--rw-r--r--   0 johnyan    (501) staff       (20)     1256 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/DEVELOP.md
--rw-r--r--   0 johnyan    (501) staff       (20)    11357 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/LICENSE
--rw-r--r--   0 johnyan    (501) staff       (20)     1266 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/README.md
--rw-r--r--   0 johnyan    (501) staff       (20)      324 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/config.yml
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.316583 smart_chromadb-0.1.dev730/clients/js/examples/
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.505622 smart_chromadb-0.1.dev730/clients/js/examples/browser/
--rw-r--r--   0 johnyan    (501) staff       (20)      358 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/examples/browser/README.md
--rw-r--r--   0 johnyan    (501) staff       (20)     1787 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/examples/browser/app.ts
--rw-r--r--   0 johnyan    (501) staff       (20)      834 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/examples/browser/index.html
--rw-r--r--   0 johnyan    (501) staff       (20)      409 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/examples/browser/package.json
--rw-r--r--   0 johnyan    (501) staff       (20)    71072 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/examples/browser/yarn.lock
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.515246 smart_chromadb-0.1.dev730/clients/js/examples/node/
--rw-r--r--   0 johnyan    (501) staff       (20)       57 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/examples/node/README.md
--rw-r--r--   0 johnyan    (501) staff       (20)     1191 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/examples/node/app.js
--rw-r--r--   0 johnyan    (501) staff       (20)    46542 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/examples/node/package-lock.json
--rw-r--r--   0 johnyan    (501) staff       (20)      503 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/examples/node/package.json
--rw-r--r--   0 johnyan    (501) staff       (20)    17116 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/examples/node/yarn.lock
--rwxr-xr-x   0 johnyan    (501) staff       (20)     1075 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/genapi.sh
--rw-r--r--   0 johnyan    (501) staff       (20)      469 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/jest.config.ts
--rw-r--r--   0 johnyan    (501) staff       (20)      153 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/openapitools.json
--rw-r--r--   0 johnyan    (501) staff       (20)   450648 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/package-lock.json
--rw-r--r--   0 johnyan    (501) staff       (20)     1455 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/package.json
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.519412 smart_chromadb-0.1.dev730/clients/js/src/
--rw-r--r--   0 johnyan    (501) staff       (20)     8171 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/ChromaClient.ts
--rw-r--r--   0 johnyan    (501) staff       (20)    19403 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/Collection.ts
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.526656 smart_chromadb-0.1.dev730/clients/js/src/embeddings/
--rw-r--r--   0 johnyan    (501) staff       (20)      938 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/embeddings/CohereEmbeddingFunction.ts
--rw-r--r--   0 johnyan    (501) staff       (20)       92 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/embeddings/IEmbeddingFunction.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     1563 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/embeddings/OpenAIEmbeddingFunction.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     2493 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/embeddings/TransformersEmbeddingFunction.ts
--rwxr-xr-x   0 johnyan    (501) staff       (20)     3402 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/embeddings/WebAIEmbeddingFunction.ts
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.536523 smart_chromadb-0.1.dev730/clients/js/src/generated/
--rw-r--r--   0 johnyan    (501) staff       (20)      921 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/generated/README.md
--rw-r--r--   0 johnyan    (501) staff       (20)    56700 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/generated/api.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     1478 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/generated/configuration.ts
--rw-r--r--   0 johnyan    (501) staff       (20)      429 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/generated/index.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     5862 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/generated/models.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     1307 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/generated/runtime.ts
--rw-r--r--   0 johnyan    (501) staff       (20)      490 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/index.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     1715 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/types.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     2002 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/src/utils.ts
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.554912 smart_chromadb-0.1.dev730/clients/js/test/
--rw-r--r--   0 johnyan    (501) staff       (20)     2625 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/test/add.collections.test.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     7586 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/test/client.test.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     3284 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/test/collection.client.test.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     2551 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/test/collection.test.ts
--rw-r--r--   0 johnyan    (501) staff       (20)      451 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/test/data.ts
--rw-r--r--   0 johnyan    (501) staff       (20)      711 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/test/delete.collection.test.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     2599 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/test/get.collection.test.ts
--rw-r--r--   0 johnyan    (501) staff       (20)      206 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/test/initClient.ts
--rw-r--r--   0 johnyan    (501) staff       (20)      577 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/test/peek.collection.test.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     1990 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/test/query.collection.test.ts
--rw-r--r--   0 johnyan    (501) staff       (20)     2160 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/test/update.collection.test.ts
--rw-r--r--   0 johnyan    (501) staff       (20)      802 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/test/upsert.collections.test.ts
--rw-r--r--   0 johnyan    (501) staff       (20)      367 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/tsconfig.json
--rw-r--r--   0 johnyan    (501) staff       (20)      110 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/tsconfig.module.json
--rw-r--r--   0 johnyan    (501) staff       (20)   157735 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/js/yarn.lock
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.558643 smart_chromadb-0.1.dev730/clients/python/
--rw-r--r--   0 johnyan    (501) staff       (20)     1627 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/python/README.md
--rwxr-xr-x   0 johnyan    (501) staff       (20)     1257 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/python/build_python_thin_client.sh
--rwxr-xr-x   0 johnyan    (501) staff       (20)      826 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/python/integration-test.sh
--rw-r--r--   0 johnyan    (501) staff       (20)       22 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/python/is_thin_client.py
--rw-r--r--   0 johnyan    (501) staff       (20)     1166 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/clients/python/pyproject.toml
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.560953 smart_chromadb-0.1.dev730/config/
--rw-r--r--   0 johnyan    (501) staff       (20)      385 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/config/backup_disk.xml
--rw-r--r--   0 johnyan    (501) staff       (20)      233 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/config/chroma_users.xml
--rw-r--r--   0 johnyan    (501) staff       (20)     1080 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/docker-compose.server.example.yml
--rw-r--r--   0 johnyan    (501) staff       (20)     1221 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/docker-compose.test.yml
--rw-r--r--   0 johnyan    (501) staff       (20)     1226 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/docker-compose.yml
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.564684 smart_chromadb-0.1.dev730/examples/
--rw-r--r--   0 johnyan    (501) staff       (20)    10346 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/examples/alternative_embeddings.ipynb
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.318785 smart_chromadb-0.1.dev730/examples/deployments/
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.569632 smart_chromadb-0.1.dev730/examples/deployments/google-cloud-compute/
--rw-r--r--   0 johnyan    (501) staff       (20)      611 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/examples/deployments/google-cloud-compute/README.md
--rw-r--r--   0 johnyan    (501) staff       (20)      752 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/examples/deployments/google-cloud-compute/chroma.tf
--rw-r--r--   0 johnyan    (501) staff       (20)      125 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/examples/deployments/google-cloud-compute/main.tf
--rw-r--r--   0 johnyan    (501) staff       (20)     2271 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/examples/deployments/google-cloud-compute/startup.sh
--rw-r--r--   0 johnyan    (501) staff       (20)      181 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/examples/deployments/google-cloud-compute/variables.tf
--rw-r--r--   0 johnyan    (501) staff       (20)     5830 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/examples/local_persistence.ipynb
--rw-r--r--   0 johnyan    (501) staff       (20)     5493 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/examples/where_filtering.ipynb
--rw-r--r--   0 johnyan    (501) staff       (20)      495 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/log_config.yml
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.320725 smart_chromadb-0.1.dev730/migrations/
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.571952 smart_chromadb-0.1.dev730/migrations/embeddings_queue/
--rw-r--r--   0 johnyan    (501) staff       (20)      261 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/migrations/embeddings_queue/00001-embeddings.sqlite.sql
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.573369 smart_chromadb-0.1.dev730/migrations/metadb/
--rw-r--r--   0 johnyan    (501) staff       (20)      620 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/migrations/metadb/00001-embedding-metadata.sqlite.sql
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.576210 smart_chromadb-0.1.dev730/migrations/sysdb/
--rw-r--r--   0 johnyan    (501) staff       (20)      336 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/migrations/sysdb/00001-collections.sqlite.sql
--rw-r--r--   0 johnyan    (501) staff       (20)      385 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/migrations/sysdb/00002-segments.sqlite.sql
--rw-r--r--   0 johnyan    (501) staff       (20)      372 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/pull_request_template.md
--rw-r--r--   0 johnyan    (501) staff       (20)     1442 2023-06-26 07:03:52.000000 smart_chromadb-0.1.dev730/pyproject.toml
--rw-r--r--   0 johnyan    (501) staff       (20)      352 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/requirements.txt
--rw-r--r--   0 johnyan    (501) staff       (20)      161 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev730/requirements_dev.txt
--rw-r--r--   0 johnyan    (501) staff       (20)       38 2023-06-26 07:04:08.584861 smart_chromadb-0.1.dev730/setup.cfg
-drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-26 07:04:08.582399 smart_chromadb-0.1.dev730/smart_chromadb.egg-info/
--rw-r--r--   0 johnyan    (501) staff       (20)     6220 2023-06-26 07:04:08.000000 smart_chromadb-0.1.dev730/smart_chromadb.egg-info/PKG-INFO
--rw-r--r--   0 johnyan    (501) staff       (20)     5777 2023-06-26 07:04:08.000000 smart_chromadb-0.1.dev730/smart_chromadb.egg-info/SOURCES.txt
--rw-r--r--   0 johnyan    (501) staff       (20)        1 2023-06-26 07:04:08.000000 smart_chromadb-0.1.dev730/smart_chromadb.egg-info/dependency_links.txt
--rw-r--r--   0 johnyan    (501) staff       (20)      332 2023-06-26 07:04:08.000000 smart_chromadb-0.1.dev730/smart_chromadb.egg-info/requires.txt
--rw-r--r--   0 johnyan    (501) staff       (20)        9 2023-06-26 07:04:08.000000 smart_chromadb-0.1.dev730/smart_chromadb.egg-info/top_level.txt
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.796071 smart_chromadb-0.1.dev731/
+-rw-r--r--   0 johnyan    (501) staff       (20)       84 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.dockerignore
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.470589 smart_chromadb-0.1.dev731/.github/
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.523072 smart_chromadb-0.1.dev731/.github/ISSUE_TEMPLATE/
+-rw-r--r--   0 johnyan    (501) staff       (20)     1512 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.github/ISSUE_TEMPLATE/bug_report.yaml
+-rw-r--r--   0 johnyan    (501) staff       (20)     1520 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.github/ISSUE_TEMPLATE/feature_request.yaml
+-rw-r--r--   0 johnyan    (501) staff       (20)     1384 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.github/ISSUE_TEMPLATE/installation_trouble.yaml
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.529232 smart_chromadb-0.1.dev731/.github/workflows/
+-rw-r--r--   0 johnyan    (501) staff       (20)      711 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.github/workflows/chroma-client-integration-test.yml
+-rw-r--r--   0 johnyan    (501) staff       (20)     1187 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.github/workflows/chroma-integration-test.yml
+-rw-r--r--   0 johnyan    (501) staff       (20)     1338 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.github/workflows/chroma-release-python-client.yml
+-rw-r--r--   0 johnyan    (501) staff       (20)     4169 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.github/workflows/chroma-release.yml
+-rw-r--r--   0 johnyan    (501) staff       (20)     1205 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.github/workflows/chroma-test.yml
+-rw-r--r--   0 johnyan    (501) staff       (20)     1734 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.github/workflows/pr-review-checklist.yml
+-rw-r--r--   0 johnyan    (501) staff       (20)      228 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.gitignore
+-rw-r--r--   0 johnyan    (501) staff       (20)     1167 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.pre-commit-config.yaml
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.538612 smart_chromadb-0.1.dev731/.vscode/
+-rw-r--r--   0 johnyan    (501) staff       (20)     1020 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/.vscode/settings.json
+-rw-r--r--   0 johnyan    (501) staff       (20)     3323 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/DEVELOP.md
+-rw-r--r--   0 johnyan    (501) staff       (20)      647 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/Dockerfile
+-rw-r--r--   0 johnyan    (501) staff       (20)    11357 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/LICENSE
+-rw-r--r--   0 johnyan    (501) staff       (20)     6220 2023-06-28 02:16:30.794772 smart_chromadb-0.1.dev731/PKG-INFO
+-rw-r--r--   0 johnyan    (501) staff       (20)     5679 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/README.md
+-rw-r--r--   0 johnyan    (501) staff       (20)      619 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/RELEASE_PROCESS.md
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.569257 smart_chromadb-0.1.dev731/bin/
+-rw-r--r--   0 johnyan    (501) staff       (20)     1610 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/backup.sh
+-rwxr-xr-x   0 johnyan    (501) staff       (20)      110 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/build
+-rwxr-xr-x   0 johnyan    (501) staff       (20)      234 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/docker_entrypoint.sh
+-rw-r--r--   0 johnyan    (501) staff       (20)     6462 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/generate_cloudformation.py
+-rwxr-xr-x   0 johnyan    (501) staff       (20)      463 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/integration-test
+-rw-r--r--   0 johnyan    (501) staff       (20)     1688 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/restore.sh
+-rw-r--r--   0 johnyan    (501) staff       (20)     1105 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/setup_linux.sh
+-rw-r--r--   0 johnyan    (501) staff       (20)      451 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/setup_mac.sh
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.570366 smart_chromadb-0.1.dev731/bin/templates/
+-rw-r--r--   0 johnyan    (501) staff       (20)      985 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/templates/docker-compose.yml
+-rwxr-xr-x   0 johnyan    (501) staff       (20)      451 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/test-package.sh
+-rwxr-xr-x   0 johnyan    (501) staff       (20)      297 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/test-remote
+-rw-r--r--   0 johnyan    (501) staff       (20)      205 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/test.py
+-rwxr-xr-x   0 johnyan    (501) staff       (20)      151 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/bin/version
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.576052 smart_chromadb-0.1.dev731/chromadb/
+-rw-r--r--   0 johnyan    (501) staff       (20)      894 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/__init__.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.581357 smart_chromadb-0.1.dev731/chromadb/api/
+-rw-r--r--   0 johnyan    (501) staff       (20)    10898 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/api/__init__.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    12480 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/api/fastapi.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    17852 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/api/local.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.582194 smart_chromadb-0.1.dev731/chromadb/api/models/
+-rw-r--r--   0 johnyan    (501) staff       (20)    15103 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/api/models/Collection.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    11270 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/api/types.py
+-rw-r--r--   0 johnyan    (501) staff       (20)      168 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/app.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     7132 2023-06-28 01:41:06.000000 smart_chromadb-0.1.dev731/chromadb/config.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.591613 smart_chromadb-0.1.dev731/chromadb/db/
+-rw-r--r--   0 johnyan    (501) staff       (20)     3390 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/db/__init__.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     6004 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/db/base.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    22207 2023-06-28 02:00:02.000000 smart_chromadb-0.1.dev731/chromadb/db/clickhouse.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    18795 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/db/duckdb.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.594527 smart_chromadb-0.1.dev731/chromadb/db/impl/
+-rw-r--r--   0 johnyan    (501) staff       (20)        0 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/db/impl/__init__.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     6221 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/db/impl/sqlite.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.597174 smart_chromadb-0.1.dev731/chromadb/db/index/
+-rw-r--r--   0 johnyan    (501) staff       (20)      447 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/db/index/__init__.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    11060 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/db/index/hnswlib.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     8096 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/db/migrations.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.599335 smart_chromadb-0.1.dev731/chromadb/db/mixins/
+-rw-r--r--   0 johnyan    (501) staff       (20)     9193 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/db/mixins/embeddings_queue.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    15557 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/db/mixins/sysdb.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    15068 2023-06-28 02:02:16.000000 smart_chromadb-0.1.dev731/chromadb/db/smartdb.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     2656 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/db/system.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     1293 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/errors.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.600100 smart_chromadb-0.1.dev731/chromadb/ingest/
+-rw-r--r--   0 johnyan    (501) staff       (20)     3643 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/ingest/__init__.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.601127 smart_chromadb-0.1.dev731/chromadb/segment/
+-rw-r--r--   0 johnyan    (501) staff       (20)     3059 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/segment/__init__.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.473779 smart_chromadb-0.1.dev731/chromadb/segment/impl/
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.601879 smart_chromadb-0.1.dev731/chromadb/segment/impl/manager/
+-rw-r--r--   0 johnyan    (501) staff       (20)     4358 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/segment/impl/manager/local.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.602811 smart_chromadb-0.1.dev731/chromadb/segment/impl/metadata/
+-rw-r--r--   0 johnyan    (501) staff       (20)    17879 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/segment/impl/metadata/sqlite.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.604308 smart_chromadb-0.1.dev731/chromadb/segment/impl/vector/
+-rw-r--r--   0 johnyan    (501) staff       (20)    11965 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/segment/impl/vector/local_hnsw.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.605319 smart_chromadb-0.1.dev731/chromadb/server/
+-rw-r--r--   0 johnyan    (501) staff       (20)      172 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/server/__init__.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.607364 smart_chromadb-0.1.dev731/chromadb/server/fastapi/
+-rw-r--r--   0 johnyan    (501) staff       (20)     9064 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/server/fastapi/__init__.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     2134 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/server/fastapi/types.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.611728 smart_chromadb-0.1.dev731/chromadb/telemetry/
+-rw-r--r--   0 johnyan    (501) staff       (20)     3214 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/telemetry/__init__.py
+-rw-r--r--   0 johnyan    (501) staff       (20)      591 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/telemetry/events.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     1161 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/telemetry/posthog.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.618221 smart_chromadb-0.1.dev731/chromadb/test/
+-rw-r--r--   0 johnyan    (501) staff       (20)     3993 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/conftest.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.621227 smart_chromadb-0.1.dev731/chromadb/test/db/
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.627370 smart_chromadb-0.1.dev731/chromadb/test/db/migrations/
+-rw-r--r--   0 johnyan    (501) staff       (20)       51 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/db/migrations/00001-migration-1.psql.sql
+-rw-r--r--   0 johnyan    (501) staff       (20)       51 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/db/migrations/00001-migration-1.sqlite.sql
+-rw-r--r--   0 johnyan    (501) staff       (20)       51 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/db/migrations/00002-migration-2.psql.sql
+-rw-r--r--   0 johnyan    (501) staff       (20)       51 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/db/migrations/00002-migration-2.sqlite.sql
+-rw-r--r--   0 johnyan    (501) staff       (20)       51 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/db/migrations/00003-migration-3.psql.sql
+-rw-r--r--   0 johnyan    (501) staff       (20)       51 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/db/migrations/00003-migration-3.sqlite.sql
+-rw-r--r--   0 johnyan    (501) staff       (20)     1168 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/db/test_base.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     5026 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/db/test_migrations.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     9773 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/db/test_system.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.628666 smart_chromadb-0.1.dev731/chromadb/test/hnswlib/
+-rw-r--r--   0 johnyan    (501) staff       (20)     2337 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/hnswlib/test_hnswlib.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.630064 smart_chromadb-0.1.dev731/chromadb/test/ingest/
+-rw-r--r--   0 johnyan    (501) staff       (20)     8117 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/ingest/test_producer_consumer.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.639135 smart_chromadb-0.1.dev731/chromadb/test/property/
+-rw-r--r--   0 johnyan    (501) staff       (20)    11294 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/property/invariants.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    18662 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/property/strategies.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     2213 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/property/test_add.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     6211 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/property/test_collections.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     9123 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/property/test_cross_version_persist.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    11073 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/property/test_embeddings.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     9062 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/property/test_filtering.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     5146 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/property/test_persist.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.640957 smart_chromadb-0.1.dev731/chromadb/test/segment/
+-rw-r--r--   0 johnyan    (501) staff       (20)    15026 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/segment/test_metadata.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    12132 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/segment/test_vector.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    40340 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/test_api.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     2234 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/test_chroma.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     4127 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/test_config.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.641518 smart_chromadb-0.1.dev731/chromadb/test/utils/
+-rw-r--r--   0 johnyan    (501) staff       (20)     3544 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/test/utils/test_messagid.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     3695 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/types.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.642592 smart_chromadb-0.1.dev731/chromadb/utils/
+-rw-r--r--   0 johnyan    (501) staff       (20)        0 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/utils/__init__.py
+-rw-r--r--   0 johnyan    (501) staff       (20)    16226 2023-06-28 02:15:34.000000 smart_chromadb-0.1.dev731/chromadb/utils/embedding_functions.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     2301 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/chromadb/utils/messageid.py
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.479513 smart_chromadb-0.1.dev731/clients/
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.659745 smart_chromadb-0.1.dev731/clients/js/
+-rw-r--r--   0 johnyan    (501) staff       (20)       66 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/.gitignore
+-rw-r--r--   0 johnyan    (501) staff       (20)       32 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/.prettierignore
+-rw-r--r--   0 johnyan    (501) staff       (20)        3 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/.prettierrc.json
+-rw-r--r--   0 johnyan    (501) staff       (20)     1256 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/DEVELOP.md
+-rw-r--r--   0 johnyan    (501) staff       (20)    11357 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/LICENSE
+-rw-r--r--   0 johnyan    (501) staff       (20)     1266 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/README.md
+-rw-r--r--   0 johnyan    (501) staff       (20)      324 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/config.yml
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.478499 smart_chromadb-0.1.dev731/clients/js/examples/
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.665893 smart_chromadb-0.1.dev731/clients/js/examples/browser/
+-rw-r--r--   0 johnyan    (501) staff       (20)      358 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/examples/browser/README.md
+-rw-r--r--   0 johnyan    (501) staff       (20)     1787 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/examples/browser/app.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)      834 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/examples/browser/index.html
+-rw-r--r--   0 johnyan    (501) staff       (20)      409 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/examples/browser/package.json
+-rw-r--r--   0 johnyan    (501) staff       (20)    71072 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/examples/browser/yarn.lock
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.670784 smart_chromadb-0.1.dev731/clients/js/examples/node/
+-rw-r--r--   0 johnyan    (501) staff       (20)       57 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/examples/node/README.md
+-rw-r--r--   0 johnyan    (501) staff       (20)     1191 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/examples/node/app.js
+-rw-r--r--   0 johnyan    (501) staff       (20)    46542 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/examples/node/package-lock.json
+-rw-r--r--   0 johnyan    (501) staff       (20)      503 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/examples/node/package.json
+-rw-r--r--   0 johnyan    (501) staff       (20)    17116 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/examples/node/yarn.lock
+-rwxr-xr-x   0 johnyan    (501) staff       (20)     1075 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/genapi.sh
+-rw-r--r--   0 johnyan    (501) staff       (20)      469 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/jest.config.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)      153 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/openapitools.json
+-rw-r--r--   0 johnyan    (501) staff       (20)   450648 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/package-lock.json
+-rw-r--r--   0 johnyan    (501) staff       (20)     1455 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/package.json
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.676257 smart_chromadb-0.1.dev731/clients/js/src/
+-rw-r--r--   0 johnyan    (501) staff       (20)     8171 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/ChromaClient.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)    19403 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/Collection.ts
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.682933 smart_chromadb-0.1.dev731/clients/js/src/embeddings/
+-rw-r--r--   0 johnyan    (501) staff       (20)      938 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/embeddings/CohereEmbeddingFunction.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)       92 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/embeddings/IEmbeddingFunction.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     1563 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/embeddings/OpenAIEmbeddingFunction.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     2493 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/embeddings/TransformersEmbeddingFunction.ts
+-rwxr-xr-x   0 johnyan    (501) staff       (20)     3402 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/embeddings/WebAIEmbeddingFunction.ts
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.688490 smart_chromadb-0.1.dev731/clients/js/src/generated/
+-rw-r--r--   0 johnyan    (501) staff       (20)      921 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/generated/README.md
+-rw-r--r--   0 johnyan    (501) staff       (20)    56700 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/generated/api.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     1478 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/generated/configuration.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)      429 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/generated/index.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     5862 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/generated/models.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     1307 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/generated/runtime.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)      490 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/index.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     1715 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/types.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     2002 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/src/utils.ts
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.702600 smart_chromadb-0.1.dev731/clients/js/test/
+-rw-r--r--   0 johnyan    (501) staff       (20)     2625 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/test/add.collections.test.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     7586 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/test/client.test.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     3284 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/test/collection.client.test.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     2551 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/test/collection.test.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)      451 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/test/data.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)      711 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/test/delete.collection.test.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     2599 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/test/get.collection.test.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)      206 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/test/initClient.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)      577 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/test/peek.collection.test.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     1990 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/test/query.collection.test.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)     2160 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/test/update.collection.test.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)      802 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/test/upsert.collections.test.ts
+-rw-r--r--   0 johnyan    (501) staff       (20)      367 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/tsconfig.json
+-rw-r--r--   0 johnyan    (501) staff       (20)      110 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/tsconfig.module.json
+-rw-r--r--   0 johnyan    (501) staff       (20)   157735 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/js/yarn.lock
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.708974 smart_chromadb-0.1.dev731/clients/python/
+-rw-r--r--   0 johnyan    (501) staff       (20)     1627 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/python/README.md
+-rwxr-xr-x   0 johnyan    (501) staff       (20)     1257 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/python/build_python_thin_client.sh
+-rwxr-xr-x   0 johnyan    (501) staff       (20)      826 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/python/integration-test.sh
+-rw-r--r--   0 johnyan    (501) staff       (20)       22 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/python/is_thin_client.py
+-rw-r--r--   0 johnyan    (501) staff       (20)     1166 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/clients/python/pyproject.toml
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.711104 smart_chromadb-0.1.dev731/config/
+-rw-r--r--   0 johnyan    (501) staff       (20)      385 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/config/backup_disk.xml
+-rw-r--r--   0 johnyan    (501) staff       (20)      233 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/config/chroma_users.xml
+-rw-r--r--   0 johnyan    (501) staff       (20)     1080 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/docker-compose.server.example.yml
+-rw-r--r--   0 johnyan    (501) staff       (20)     1221 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/docker-compose.test.yml
+-rw-r--r--   0 johnyan    (501) staff       (20)     1226 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/docker-compose.yml
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.714801 smart_chromadb-0.1.dev731/examples/
+-rw-r--r--   0 johnyan    (501) staff       (20)    10346 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/examples/alternative_embeddings.ipynb
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.480192 smart_chromadb-0.1.dev731/examples/deployments/
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.749932 smart_chromadb-0.1.dev731/examples/deployments/google-cloud-compute/
+-rw-r--r--   0 johnyan    (501) staff       (20)      611 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/examples/deployments/google-cloud-compute/README.md
+-rw-r--r--   0 johnyan    (501) staff       (20)      752 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/examples/deployments/google-cloud-compute/chroma.tf
+-rw-r--r--   0 johnyan    (501) staff       (20)      125 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/examples/deployments/google-cloud-compute/main.tf
+-rw-r--r--   0 johnyan    (501) staff       (20)     2271 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/examples/deployments/google-cloud-compute/startup.sh
+-rw-r--r--   0 johnyan    (501) staff       (20)      181 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/examples/deployments/google-cloud-compute/variables.tf
+-rw-r--r--   0 johnyan    (501) staff       (20)     5830 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/examples/local_persistence.ipynb
+-rw-r--r--   0 johnyan    (501) staff       (20)     5493 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/examples/where_filtering.ipynb
+-rw-r--r--   0 johnyan    (501) staff       (20)      495 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/log_config.yml
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.481329 smart_chromadb-0.1.dev731/migrations/
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.771082 smart_chromadb-0.1.dev731/migrations/embeddings_queue/
+-rw-r--r--   0 johnyan    (501) staff       (20)      261 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/migrations/embeddings_queue/00001-embeddings.sqlite.sql
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.781124 smart_chromadb-0.1.dev731/migrations/metadb/
+-rw-r--r--   0 johnyan    (501) staff       (20)      620 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/migrations/metadb/00001-embedding-metadata.sqlite.sql
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.785112 smart_chromadb-0.1.dev731/migrations/sysdb/
+-rw-r--r--   0 johnyan    (501) staff       (20)      336 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/migrations/sysdb/00001-collections.sqlite.sql
+-rw-r--r--   0 johnyan    (501) staff       (20)      385 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/migrations/sysdb/00002-segments.sqlite.sql
+-rw-r--r--   0 johnyan    (501) staff       (20)      372 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/pull_request_template.md
+-rw-r--r--   0 johnyan    (501) staff       (20)     1455 2023-06-26 07:09:55.000000 smart_chromadb-0.1.dev731/pyproject.toml
+-rw-r--r--   0 johnyan    (501) staff       (20)      352 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/requirements.txt
+-rw-r--r--   0 johnyan    (501) staff       (20)      161 2023-06-25 09:21:06.000000 smart_chromadb-0.1.dev731/requirements_dev.txt
+-rw-r--r--   0 johnyan    (501) staff       (20)       38 2023-06-28 02:16:30.796512 smart_chromadb-0.1.dev731/setup.cfg
+drwxr-xr-x   0 johnyan    (501) staff       (20)        0 2023-06-28 02:16:30.793679 smart_chromadb-0.1.dev731/smart_chromadb.egg-info/
+-rw-r--r--   0 johnyan    (501) staff       (20)     6220 2023-06-28 02:16:30.000000 smart_chromadb-0.1.dev731/smart_chromadb.egg-info/PKG-INFO
+-rw-r--r--   0 johnyan    (501) staff       (20)     5800 2023-06-28 02:16:30.000000 smart_chromadb-0.1.dev731/smart_chromadb.egg-info/SOURCES.txt
+-rw-r--r--   0 johnyan    (501) staff       (20)        1 2023-06-28 02:16:30.000000 smart_chromadb-0.1.dev731/smart_chromadb.egg-info/dependency_links.txt
+-rw-r--r--   0 johnyan    (501) staff       (20)      340 2023-06-28 02:16:30.000000 smart_chromadb-0.1.dev731/smart_chromadb.egg-info/requires.txt
+-rw-r--r--   0 johnyan    (501) staff       (20)        9 2023-06-28 02:16:30.000000 smart_chromadb-0.1.dev731/smart_chromadb.egg-info/top_level.txt
```

### Comparing `smart_chromadb-0.1.dev730/.github/ISSUE_TEMPLATE/bug_report.yaml` & `smart_chromadb-0.1.dev731/.github/ISSUE_TEMPLATE/bug_report.yaml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/.github/ISSUE_TEMPLATE/feature_request.yaml` & `smart_chromadb-0.1.dev731/.github/ISSUE_TEMPLATE/feature_request.yaml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/.github/ISSUE_TEMPLATE/installation_trouble.yaml` & `smart_chromadb-0.1.dev731/.github/ISSUE_TEMPLATE/installation_trouble.yaml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/.github/workflows/chroma-client-integration-test.yml` & `smart_chromadb-0.1.dev731/.github/workflows/chroma-client-integration-test.yml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/.github/workflows/chroma-integration-test.yml` & `smart_chromadb-0.1.dev731/.github/workflows/chroma-integration-test.yml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/.github/workflows/chroma-release-python-client.yml` & `smart_chromadb-0.1.dev731/.github/workflows/chroma-release-python-client.yml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/.github/workflows/chroma-release.yml` & `smart_chromadb-0.1.dev731/.github/workflows/chroma-release.yml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/.github/workflows/chroma-test.yml` & `smart_chromadb-0.1.dev731/.github/workflows/chroma-test.yml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/.github/workflows/pr-review-checklist.yml` & `smart_chromadb-0.1.dev731/.github/workflows/pr-review-checklist.yml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/.pre-commit-config.yaml` & `smart_chromadb-0.1.dev731/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/.vscode/settings.json` & `smart_chromadb-0.1.dev731/.vscode/settings.json`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/DEVELOP.md` & `smart_chromadb-0.1.dev731/DEVELOP.md`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/Dockerfile` & `smart_chromadb-0.1.dev731/Dockerfile`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/LICENSE` & `smart_chromadb-0.1.dev731/LICENSE`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/PKG-INFO` & `smart_chromadb-0.1.dev731/smart_chromadb.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: smart_chromadb
-Version: 0.1.dev730
+Name: smart-chromadb
+Version: 0.1.dev731
 Summary: Chroma.
 Author-email: Jeff Huber <jeff@trychroma.com>, Anton Troynikov <anton@trychroma.com>
 Project-URL: Homepage, https://github.com/chroma-core/chroma
 Project-URL: Bug Tracker, https://github.com/chroma-core/chroma/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Operating System :: OS Independent
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: smart_chromadb Version: 0.1.dev730 Summary: Chroma.
+Metadata-Version: 2.1 Name: smart-chromadb Version: 0.1.dev731 Summary: Chroma.
 Author-email: Jeff Huber
 trychroma.com>, Anton Troynikov
 trychroma.com> Project-URL: Homepage, https://github.com/chroma-core/chroma
 Project-URL: Bug Tracker, https://github.com/chroma-core/chroma/issues
 Classifier: Programming Language :: Python :: 3 Classifier: License :: OSI
 Approved :: Apache Software License Classifier: Operating System :: OS
 Independent Requires-Python: >=3.7 Description-Content-Type: text/markdown
```

### Comparing `smart_chromadb-0.1.dev730/README.md` & `smart_chromadb-0.1.dev731/README.md`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/RELEASE_PROCESS.md` & `smart_chromadb-0.1.dev731/RELEASE_PROCESS.md`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/bin/backup.sh` & `smart_chromadb-0.1.dev731/bin/backup.sh`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/bin/generate_cloudformation.py` & `smart_chromadb-0.1.dev731/bin/generate_cloudformation.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/bin/restore.sh` & `smart_chromadb-0.1.dev731/bin/restore.sh`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/bin/setup_linux.sh` & `smart_chromadb-0.1.dev731/bin/setup_linux.sh`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/bin/templates/docker-compose.yml` & `smart_chromadb-0.1.dev731/bin/templates/docker-compose.yml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/__init__.py` & `smart_chromadb-0.1.dev731/chromadb/__init__.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/api/__init__.py` & `smart_chromadb-0.1.dev731/chromadb/api/__init__.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/api/fastapi.py` & `smart_chromadb-0.1.dev731/chromadb/api/fastapi.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/api/local.py` & `smart_chromadb-0.1.dev731/chromadb/api/local.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/api/models/Collection.py` & `smart_chromadb-0.1.dev731/chromadb/api/models/Collection.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/api/types.py` & `smart_chromadb-0.1.dev731/chromadb/api/types.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/config.py` & `smart_chromadb-0.1.dev731/chromadb/config.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,14 +20,15 @@
 
 _legacy_config_values = {
     "duckdb": "chromadb.db.duckdb.DuckDB",
     "duckdb+parquet": "chromadb.db.duckdb.PersistentDuckDB",
     "clickhouse": "chromadb.db.clickhouse.Clickhouse",
     "rest": "chromadb.api.fastapi.FastAPI",
     "local": "chromadb.api.local.LocalAPI",
+    "starrocksdb": "chromadb.db.smartdb.StarRocksDB",
 }
 
 # TODO: Don't use concrete types here to avoid circular deps. Strings are fine for right here!
 _abstract_type_keys: Dict[str, str] = {
     "chromadb.db.DB": "chroma_db_impl",
     "chromadb.api.API": "chroma_api_impl",
     "chromadb.telemetry.Telemetry": "chroma_telemetry_impl",
@@ -49,14 +50,16 @@
     chroma_consumer_impl: str = "chromadb.db.impl.sqlite.SqliteDB"
 
     clickhouse_host: Optional[str] = None
     clickhouse_port: Optional[str] = None
 
     persist_directory: str = ".chroma"
 
+    db_config: dict = None
+
     chroma_server_host: Optional[str] = None
     chroma_server_http_port: Optional[str] = None
     chroma_server_ssl_enabled: Optional[bool] = False
     chroma_server_grpc_port: Optional[str] = None
     chroma_server_cors_allow_origins: List[str] = []  # eg ["http://localhost:3000"]
 
     anonymized_telemetry: bool = True
@@ -72,14 +75,16 @@
         val = self[key]
         if val is None:
             raise ValueError(f"Missing required config value '{key}'")
         return val
 
     def __getitem__(self, key: str) -> Any:
         val = getattr(self, key)
+        if isinstance(val, dict):
+            return val
         # Backwards compatibility with short names instead of full class names
         if val in _legacy_config_values:
             newval = _legacy_config_values[val]
             val = newval
         return val
 
     class Config:
```

### Comparing `smart_chromadb-0.1.dev730/chromadb/db/__init__.py` & `smart_chromadb-0.1.dev731/chromadb/db/__init__.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/db/base.py` & `smart_chromadb-0.1.dev731/chromadb/db/base.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/db/clickhouse.py` & `smart_chromadb-0.1.dev731/chromadb/db/clickhouse.py`

 * *Files 1% similar despite different names*

```diff
@@ -56,22 +56,21 @@
     #  INIT METHODS
     #
     def __init__(self, system: System):
         super().__init__(system)
         self._conn = None
         self._settings = system.settings
 
-        self._settings.require("clickhouse_host")
-        self._settings.require("clickhouse_port")
+        self._settings.require("db_config")
 
     def _init_conn(self):
         common.set_setting("autogenerate_session_id", False)
         self._conn = clickhouse_connect.get_client(
-            host=self._settings.clickhouse_host,
-            port=int(self._settings.clickhouse_port),
+            host=self._settings.db_config['host'],
+            port=int(self._settings.db_config['port']),
         )
         self._create_table_collections(self._conn)
         self._create_table_embeddings(self._conn)
 
     def _get_conn(self) -> Client:
         if self._conn is None:
             self._init_conn()
@@ -351,15 +350,15 @@
             # `get` current returns items in arbitrary order.
             # TODO if we fix `get`, we can remove this explicit mapping.
             uuid_mapping = {r[4]: r[1] for r in existing_items}
             update_uuids = [uuid_mapping[id] for id in ids]
             index = self._index(collection_uuid)
             index.add(update_uuids, embeddings, update=True)
 
-    def _get(self, where={}, columns: Optional[List] = None):
+    def _get(self, where, columns: Optional[List] = None):
         select_columns = db_schema_to_keys() if columns is None else columns
         val = (
             self._get_conn()
             .query(f"""SELECT {",".join(select_columns)} FROM embeddings {where}""")
             .result_rows
         )
         for i in range(len(val)):
```

### Comparing `smart_chromadb-0.1.dev730/chromadb/db/duckdb.py` & `smart_chromadb-0.1.dev731/chromadb/db/duckdb.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/db/impl/sqlite.py` & `smart_chromadb-0.1.dev731/chromadb/db/impl/sqlite.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/db/index/hnswlib.py` & `smart_chromadb-0.1.dev731/chromadb/db/index/hnswlib.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/db/migrations.py` & `smart_chromadb-0.1.dev731/chromadb/db/migrations.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/db/mixins/embeddings_queue.py` & `smart_chromadb-0.1.dev731/chromadb/db/mixins/embeddings_queue.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/db/mixins/sysdb.py` & `smart_chromadb-0.1.dev731/chromadb/db/mixins/sysdb.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/db/system.py` & `smart_chromadb-0.1.dev731/chromadb/db/system.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/errors.py` & `smart_chromadb-0.1.dev731/chromadb/errors.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/ingest/__init__.py` & `smart_chromadb-0.1.dev731/chromadb/ingest/__init__.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/segment/__init__.py` & `smart_chromadb-0.1.dev731/chromadb/segment/__init__.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/segment/impl/manager/local.py` & `smart_chromadb-0.1.dev731/chromadb/segment/impl/manager/local.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/segment/impl/metadata/sqlite.py` & `smart_chromadb-0.1.dev731/chromadb/segment/impl/metadata/sqlite.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/segment/impl/vector/local_hnsw.py` & `smart_chromadb-0.1.dev731/chromadb/segment/impl/vector/local_hnsw.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/server/fastapi/__init__.py` & `smart_chromadb-0.1.dev731/chromadb/server/fastapi/__init__.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/server/fastapi/types.py` & `smart_chromadb-0.1.dev731/chromadb/server/fastapi/types.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/telemetry/__init__.py` & `smart_chromadb-0.1.dev731/chromadb/telemetry/__init__.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/telemetry/events.py` & `smart_chromadb-0.1.dev731/chromadb/telemetry/events.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/telemetry/posthog.py` & `smart_chromadb-0.1.dev731/chromadb/telemetry/posthog.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/conftest.py` & `smart_chromadb-0.1.dev731/chromadb/test/conftest.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/db/test_base.py` & `smart_chromadb-0.1.dev731/chromadb/test/db/test_base.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/db/test_migrations.py` & `smart_chromadb-0.1.dev731/chromadb/test/db/test_migrations.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/db/test_system.py` & `smart_chromadb-0.1.dev731/chromadb/test/db/test_system.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/hnswlib/test_hnswlib.py` & `smart_chromadb-0.1.dev731/chromadb/test/hnswlib/test_hnswlib.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/ingest/test_producer_consumer.py` & `smart_chromadb-0.1.dev731/chromadb/test/ingest/test_producer_consumer.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/property/invariants.py` & `smart_chromadb-0.1.dev731/chromadb/test/property/invariants.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/property/strategies.py` & `smart_chromadb-0.1.dev731/chromadb/test/property/strategies.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/property/test_add.py` & `smart_chromadb-0.1.dev731/chromadb/test/property/test_add.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/property/test_collections.py` & `smart_chromadb-0.1.dev731/chromadb/test/property/test_collections.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/property/test_cross_version_persist.py` & `smart_chromadb-0.1.dev731/chromadb/test/property/test_cross_version_persist.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/property/test_embeddings.py` & `smart_chromadb-0.1.dev731/chromadb/test/property/test_embeddings.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/property/test_filtering.py` & `smart_chromadb-0.1.dev731/chromadb/test/property/test_filtering.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/property/test_persist.py` & `smart_chromadb-0.1.dev731/chromadb/test/property/test_persist.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/segment/test_metadata.py` & `smart_chromadb-0.1.dev731/chromadb/test/segment/test_metadata.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/segment/test_vector.py` & `smart_chromadb-0.1.dev731/chromadb/test/segment/test_vector.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/test_api.py` & `smart_chromadb-0.1.dev731/chromadb/test/test_api.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/test_chroma.py` & `smart_chromadb-0.1.dev731/chromadb/test/test_chroma.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/test_config.py` & `smart_chromadb-0.1.dev731/chromadb/test/test_config.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/test/utils/test_messagid.py` & `smart_chromadb-0.1.dev731/chromadb/test/utils/test_messagid.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/types.py` & `smart_chromadb-0.1.dev731/chromadb/types.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/chromadb/utils/embedding_functions.py` & `smart_chromadb-0.1.dev731/chromadb/utils/embedding_functions.py`

 * *Files 1% similar despite different names*

```diff
@@ -40,15 +40,18 @@
     def __init__(self, model_name: str = "shibing624/text2vec-base-chinese"):
         try:
             from text2vec import SentenceModel
         except ImportError:
             raise ValueError(
                 "The text2vec python package is not installed. Please install it with `pip install text2vec`"
             )
+        import time
+        start_time = time.time()
         self._model = SentenceModel(model_name_or_path=model_name)
+        print(f'load Text2Vec cost: {time.time() - start_time}')
 
     def __call__(self, texts: Documents) -> Embeddings:
         return self._model.encode(list(texts), convert_to_numpy=True).tolist()  # type: ignore # noqa E501
 
 
 class OpenAIEmbeddingFunction(EmbeddingFunction):
     def __init__(
@@ -310,19 +313,21 @@
             )
             with tarfile.open(
                 self.DOWNLOAD_PATH / self.ARCHIVE_FILENAME, "r:gz"
             ) as tar:
                 tar.extractall(self.DOWNLOAD_PATH)
 
 
+DefaultEmbedding = Text2VecEmbeddingFunction()
 def DefaultEmbeddingFunction() -> Optional[EmbeddingFunction]:
     if is_thin_client:
         return None
     else:
-        return ONNXMiniLM_L6_V2()
+        return DefaultEmbedding
+        # return ONNXMiniLM_L6_V2()
 
 
 class GooglePalmEmbeddingFunction(EmbeddingFunction):
     """To use this EmbeddingFunction, you must have the google.generativeai Python package installed and have a PaLM API key."""
 
     def __init__(self, api_key: str, model_name: str = "models/embedding-gecko-001"):
         if not api_key:
```

### Comparing `smart_chromadb-0.1.dev730/chromadb/utils/messageid.py` & `smart_chromadb-0.1.dev731/chromadb/utils/messageid.py`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/DEVELOP.md` & `smart_chromadb-0.1.dev731/clients/js/DEVELOP.md`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/LICENSE` & `smart_chromadb-0.1.dev731/clients/js/LICENSE`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/README.md` & `smart_chromadb-0.1.dev731/clients/js/README.md`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/examples/browser/app.ts` & `smart_chromadb-0.1.dev731/clients/js/examples/browser/app.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/examples/browser/index.html` & `smart_chromadb-0.1.dev731/clients/js/examples/browser/index.html`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/examples/browser/yarn.lock` & `smart_chromadb-0.1.dev731/clients/js/examples/browser/yarn.lock`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/examples/node/app.js` & `smart_chromadb-0.1.dev731/clients/js/examples/node/app.js`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/examples/node/package-lock.json` & `smart_chromadb-0.1.dev731/clients/js/examples/node/package-lock.json`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/examples/node/yarn.lock` & `smart_chromadb-0.1.dev731/clients/js/examples/node/yarn.lock`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/genapi.sh` & `smart_chromadb-0.1.dev731/clients/js/genapi.sh`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/package-lock.json` & `smart_chromadb-0.1.dev731/clients/js/package-lock.json`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/package.json` & `smart_chromadb-0.1.dev731/clients/js/package.json`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/ChromaClient.ts` & `smart_chromadb-0.1.dev731/clients/js/src/ChromaClient.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/Collection.ts` & `smart_chromadb-0.1.dev731/clients/js/src/Collection.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/embeddings/CohereEmbeddingFunction.ts` & `smart_chromadb-0.1.dev731/clients/js/src/embeddings/CohereEmbeddingFunction.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/embeddings/OpenAIEmbeddingFunction.ts` & `smart_chromadb-0.1.dev731/clients/js/src/embeddings/OpenAIEmbeddingFunction.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/embeddings/TransformersEmbeddingFunction.ts` & `smart_chromadb-0.1.dev731/clients/js/src/embeddings/TransformersEmbeddingFunction.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/embeddings/WebAIEmbeddingFunction.ts` & `smart_chromadb-0.1.dev731/clients/js/src/embeddings/WebAIEmbeddingFunction.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/generated/README.md` & `smart_chromadb-0.1.dev731/clients/js/src/generated/README.md`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/generated/api.ts` & `smart_chromadb-0.1.dev731/clients/js/src/generated/api.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/generated/configuration.ts` & `smart_chromadb-0.1.dev731/clients/js/src/generated/configuration.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/generated/models.ts` & `smart_chromadb-0.1.dev731/clients/js/src/generated/models.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/generated/runtime.ts` & `smart_chromadb-0.1.dev731/clients/js/src/generated/runtime.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/types.ts` & `smart_chromadb-0.1.dev731/clients/js/src/types.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/src/utils.ts` & `smart_chromadb-0.1.dev731/clients/js/src/utils.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/test/add.collections.test.ts` & `smart_chromadb-0.1.dev731/clients/js/test/add.collections.test.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/test/client.test.ts` & `smart_chromadb-0.1.dev731/clients/js/test/client.test.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/test/collection.client.test.ts` & `smart_chromadb-0.1.dev731/clients/js/test/collection.client.test.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/test/collection.test.ts` & `smart_chromadb-0.1.dev731/clients/js/test/collection.test.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/test/delete.collection.test.ts` & `smart_chromadb-0.1.dev731/clients/js/test/delete.collection.test.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/test/get.collection.test.ts` & `smart_chromadb-0.1.dev731/clients/js/test/get.collection.test.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/test/peek.collection.test.ts` & `smart_chromadb-0.1.dev731/clients/js/test/peek.collection.test.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/test/query.collection.test.ts` & `smart_chromadb-0.1.dev731/clients/js/test/query.collection.test.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/test/update.collection.test.ts` & `smart_chromadb-0.1.dev731/clients/js/test/update.collection.test.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/test/upsert.collections.test.ts` & `smart_chromadb-0.1.dev731/clients/js/test/upsert.collections.test.ts`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/js/yarn.lock` & `smart_chromadb-0.1.dev731/clients/js/yarn.lock`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/python/README.md` & `smart_chromadb-0.1.dev731/clients/python/README.md`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/python/build_python_thin_client.sh` & `smart_chromadb-0.1.dev731/clients/python/build_python_thin_client.sh`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/python/integration-test.sh` & `smart_chromadb-0.1.dev731/clients/python/integration-test.sh`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/clients/python/pyproject.toml` & `smart_chromadb-0.1.dev731/clients/python/pyproject.toml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/docker-compose.server.example.yml` & `smart_chromadb-0.1.dev731/docker-compose.server.example.yml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/docker-compose.test.yml` & `smart_chromadb-0.1.dev731/docker-compose.test.yml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/docker-compose.yml` & `smart_chromadb-0.1.dev731/docker-compose.yml`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/examples/alternative_embeddings.ipynb` & `smart_chromadb-0.1.dev731/examples/alternative_embeddings.ipynb`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/examples/deployments/google-cloud-compute/README.md` & `smart_chromadb-0.1.dev731/examples/deployments/google-cloud-compute/README.md`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/examples/deployments/google-cloud-compute/chroma.tf` & `smart_chromadb-0.1.dev731/examples/deployments/google-cloud-compute/chroma.tf`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/examples/deployments/google-cloud-compute/startup.sh` & `smart_chromadb-0.1.dev731/examples/deployments/google-cloud-compute/startup.sh`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/examples/local_persistence.ipynb` & `smart_chromadb-0.1.dev731/examples/local_persistence.ipynb`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/examples/where_filtering.ipynb` & `smart_chromadb-0.1.dev731/examples/where_filtering.ipynb`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/migrations/metadb/00001-embedding-metadata.sqlite.sql` & `smart_chromadb-0.1.dev731/migrations/metadb/00001-embedding-metadata.sqlite.sql`

 * *Files identical despite different names*

### Comparing `smart_chromadb-0.1.dev730/pyproject.toml` & `smart_chromadb-0.1.dev731/pyproject.toml`

 * *Files 6% similar despite different names*

```diff
@@ -27,15 +27,16 @@
   'posthog >= 2.4.0',
   'typing_extensions >= 4.5.0',
   'pulsar-client>=3.1.0',
   'onnxruntime >= 1.14.1',
   'tokenizers >= 0.13.2',
   'tqdm >= 4.65.0',
   'overrides >= 7.3.1',
-  'graphlib_backport >= 1.0.3; python_version < "3.9"'
+  'graphlib_backport >= 1.0.3; python_version < "3.9"',
+  'pymysql'
 ]
 
 [tool.black]
 line-length = 88
 required-version = "23.3.0" # Black will refuse to run if it's not this version.
 target-version = ['py36', 'py37', 'py38', 'py39', 'py310']
```

### Comparing `smart_chromadb-0.1.dev730/smart_chromadb.egg-info/PKG-INFO` & `smart_chromadb-0.1.dev731/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: smart-chromadb
-Version: 0.1.dev730
+Name: smart_chromadb
+Version: 0.1.dev731
 Summary: Chroma.
 Author-email: Jeff Huber <jeff@trychroma.com>, Anton Troynikov <anton@trychroma.com>
 Project-URL: Homepage, https://github.com/chroma-core/chroma
 Project-URL: Bug Tracker, https://github.com/chroma-core/chroma/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Operating System :: OS Independent
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: smart-chromadb Version: 0.1.dev730 Summary: Chroma.
+Metadata-Version: 2.1 Name: smart_chromadb Version: 0.1.dev731 Summary: Chroma.
 Author-email: Jeff Huber
 trychroma.com>, Anton Troynikov
 trychroma.com> Project-URL: Homepage, https://github.com/chroma-core/chroma
 Project-URL: Bug Tracker, https://github.com/chroma-core/chroma/issues
 Classifier: Programming Language :: Python :: 3 Classifier: License :: OSI
 Approved :: Apache Software License Classifier: Operating System :: OS
 Independent Requires-Python: >=3.7 Description-Content-Type: text/markdown
```

### Comparing `smart_chromadb-0.1.dev730/smart_chromadb.egg-info/SOURCES.txt` & `smart_chromadb-0.1.dev731/smart_chromadb.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -48,14 +48,15 @@
 chromadb/api/types.py
 chromadb/api/models/Collection.py
 chromadb/db/__init__.py
 chromadb/db/base.py
 chromadb/db/clickhouse.py
 chromadb/db/duckdb.py
 chromadb/db/migrations.py
+chromadb/db/smartdb.py
 chromadb/db/system.py
 chromadb/db/impl/__init__.py
 chromadb/db/impl/sqlite.py
 chromadb/db/index/__init__.py
 chromadb/db/index/hnswlib.py
 chromadb/db/mixins/embeddings_queue.py
 chromadb/db/mixins/sysdb.py
```

