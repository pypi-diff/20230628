# Comparing `tmp/api.video-1.2.8.tar.gz` & `tmp/api.video-1.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/api.video-1.2.8.tar", last modified: Wed Sep 14 07:39:07 2022, max compression
+gzip compressed data, was "dist/api.video-1.3.0.tar", last modified: Wed Jun 28 13:18:03 2023, max compression
```

## Comparing `api.video-1.2.8.tar` & `api.video-1.3.0.tar`

### file list

```diff
@@ -1,116 +1,125 @@
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-14 07:39:07.000000 api.video-1.2.8/
--rw-r--r--   0 runner    (1001) docker     (121)    22906 2022-09-14 07:39:07.000000 api.video-1.2.8/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)    20152 2022-09-14 07:38:58.000000 api.video-1.2.8/README.md
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-14 07:39:07.000000 api.video-1.2.8/api.video.egg-info/
--rw-r--r--   0 runner    (1001) docker     (121)    22906 2022-09-14 07:39:07.000000 api.video-1.2.8/api.video.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)     3715 2022-09-14 07:39:07.000000 api.video-1.2.8/api.video.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2022-09-14 07:39:07.000000 api.video-1.2.8/api.video.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (121)       58 2022-09-14 07:39:07.000000 api.video-1.2.8/api.video.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (121)        9 2022-09-14 07:39:07.000000 api.video-1.2.8/api.video.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-14 07:39:07.000000 api.video-1.2.8/apivideo/
--rw-r--r--   0 runner    (1001) docker     (121)      718 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-14 07:39:07.000000 api.video-1.2.8/apivideo/api/
--rw-r--r--   0 runner    (1001) docker     (121)      213 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/api/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)    29047 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/api/captions_api.py
--rw-r--r--   0 runner    (1001) docker     (121)    23289 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/api/chapters_api.py
--rw-r--r--   0 runner    (1001) docker     (121)    39947 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/api/live_streams_api.py
--rw-r--r--   0 runner    (1001) docker     (121)    38281 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/api/player_themes_api.py
--rw-r--r--   0 runner    (1001) docker     (121)    19929 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/api/raw_statistics_api.py
--rw-r--r--   0 runner    (1001) docker     (121)    22768 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/api/upload_tokens_api.py
--rw-r--r--   0 runner    (1001) docker     (121)    70459 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/api/videos_api.py
--rw-r--r--   0 runner    (1001) docker     (121)    16914 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/api/watermarks_api.py
--rw-r--r--   0 runner    (1001) docker     (121)    22231 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/api/webhooks_api.py
--rw-r--r--   0 runner    (1001) docker     (121)    37096 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/api_client.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-14 07:39:07.000000 api.video-1.2.8/apivideo/apis/
--rw-r--r--   0 runner    (1001) docker     (121)      901 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/apis/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     3091 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/auth_api_client.py
--rw-r--r--   0 runner    (1001) docker     (121)    16961 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/configuration.py
--rw-r--r--   0 runner    (1001) docker     (121)     4208 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/endpoint.py
--rw-r--r--   0 runner    (1001) docker     (121)     5319 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/exceptions.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-14 07:39:07.000000 api.video-1.2.8/apivideo/model/
--rw-r--r--   0 runner    (1001) docker     (121)      348 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)     7404 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/access_token.py
--rw-r--r--   0 runner    (1001) docker     (121)     6679 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/authenticate_payload.py
--rw-r--r--   0 runner    (1001) docker     (121)     7122 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/bad_request.py
--rw-r--r--   0 runner    (1001) docker     (121)     6950 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/bytes_range.py
--rw-r--r--   0 runner    (1001) docker     (121)     7102 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/caption.py
--rw-r--r--   0 runner    (1001) docker     (121)     6986 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/captions_list_response.py
--rw-r--r--   0 runner    (1001) docker     (121)     6560 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/captions_update_payload.py
--rw-r--r--   0 runner    (1001) docker     (121)     6868 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/chapter.py
--rw-r--r--   0 runner    (1001) docker     (121)     6986 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/chapters_list_response.py
--rw-r--r--   0 runner    (1001) docker     (121)     6633 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/link.py
--rw-r--r--   0 runner    (1001) docker     (121)     8892 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/live_stream.py
--rw-r--r--   0 runner    (1001) docker     (121)     7188 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/live_stream_assets.py
--rw-r--r--   0 runner    (1001) docker     (121)     7444 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/live_stream_creation_payload.py
--rw-r--r--   0 runner    (1001) docker     (121)     7009 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/live_stream_list_response.py
--rw-r--r--   0 runner    (1001) docker     (121)     8386 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/live_stream_session.py
--rw-r--r--   0 runner    (1001) docker     (121)     7007 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/live_stream_session_client.py
--rw-r--r--   0 runner    (1001) docker     (121)     6980 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/live_stream_session_device.py
--rw-r--r--   0 runner    (1001) docker     (121)     6786 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/live_stream_session_location.py
--rw-r--r--   0 runner    (1001) docker     (121)     7382 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/live_stream_session_referrer.py
--rw-r--r--   0 runner    (1001) docker     (121)     7150 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/live_stream_session_session.py
--rw-r--r--   0 runner    (1001) docker     (121)     7433 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/live_stream_update_payload.py
--rw-r--r--   0 runner    (1001) docker     (121)     6733 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/metadata.py
--rw-r--r--   0 runner    (1001) docker     (121)     6919 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/not_found.py
--rw-r--r--   0 runner    (1001) docker     (121)     7715 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/pagination.py
--rw-r--r--   0 runner    (1001) docker     (121)     6653 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/pagination_link.py
--rw-r--r--   0 runner    (1001) docker     (121)     7214 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/player_session_event.py
--rw-r--r--   0 runner    (1001) docker     (121)    10820 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/player_theme.py
--rw-r--r--   0 runner    (1001) docker     (121)     6770 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/player_theme_assets.py
--rw-r--r--   0 runner    (1001) docker     (121)    10247 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/player_theme_creation_payload.py
--rw-r--r--   0 runner    (1001) docker     (121)     9955 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/player_theme_update_payload.py
--rw-r--r--   0 runner    (1001) docker     (121)     7019 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/player_themes_list_response.py
--rw-r--r--   0 runner    (1001) docker     (121)     7623 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/quality.py
--rw-r--r--   0 runner    (1001) docker     (121)     7096 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/raw_statistics_list_live_stream_analytics_response.py
--rw-r--r--   0 runner    (1001) docker     (121)     7102 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/raw_statistics_list_player_session_events_response.py
--rw-r--r--   0 runner    (1001) docker     (121)     7043 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/raw_statistics_list_sessions_response.py
--rw-r--r--   0 runner    (1001) docker     (121)     6949 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/refresh_token_payload.py
--rw-r--r--   0 runner    (1001) docker     (121)     6850 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/token_creation_payload.py
--rw-r--r--   0 runner    (1001) docker     (121)     7005 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/token_list_response.py
--rw-r--r--   0 runner    (1001) docker     (121)     7360 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/upload_token.py
--rw-r--r--   0 runner    (1001) docker     (121)    10036 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video.py
--rw-r--r--   0 runner    (1001) docker     (121)     7490 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_assets.py
--rw-r--r--   0 runner    (1001) docker     (121)     7093 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_clip.py
--rw-r--r--   0 runner    (1001) docker     (121)     9710 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_creation_payload.py
--rw-r--r--   0 runner    (1001) docker     (121)     8486 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_id.py
--rw-r--r--   0 runner    (1001) docker     (121)     8221 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_session.py
--rw-r--r--   0 runner    (1001) docker     (121)     6979 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_session_client.py
--rw-r--r--   0 runner    (1001) docker     (121)     6970 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_session_device.py
--rw-r--r--   0 runner    (1001) docker     (121)     6760 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_session_location.py
--rw-r--r--   0 runner    (1001) docker     (121)     6967 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_session_os.py
--rw-r--r--   0 runner    (1001) docker     (121)     7389 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_session_referrer.py
--rw-r--r--   0 runner    (1001) docker     (121)     7607 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_session_session.py
--rw-r--r--   0 runner    (1001) docker     (121)     7062 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_source.py
--rw-r--r--   0 runner    (1001) docker     (121)     7009 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_source_live_stream.py
--rw-r--r--   0 runner    (1001) docker     (121)     6675 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_source_live_stream_link.py
--rw-r--r--   0 runner    (1001) docker     (121)     7037 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_status.py
--rw-r--r--   0 runner    (1001) docker     (121)     7291 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_status_encoding.py
--rw-r--r--   0 runner    (1001) docker     (121)     8611 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_status_encoding_metadata.py
--rw-r--r--   0 runner    (1001) docker     (121)     7894 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_status_ingest.py
--rw-r--r--   0 runner    (1001) docker     (121)     6994 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_status_ingest_received_parts.py
--rw-r--r--   0 runner    (1001) docker     (121)     7043 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_thumbnail_pick_payload.py
--rw-r--r--   0 runner    (1001) docker     (121)     8722 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_update_payload.py
--rw-r--r--   0 runner    (1001) docker     (121)     8267 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/video_watermark.py
--rw-r--r--   0 runner    (1001) docker     (121)     6970 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/videos_list_response.py
--rw-r--r--   0 runner    (1001) docker     (121)     6819 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/watermark.py
--rw-r--r--   0 runner    (1001) docker     (121)     7002 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/watermarks_list_response.py
--rw-r--r--   0 runner    (1001) docker     (121)     7132 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/webhook.py
--rw-r--r--   0 runner    (1001) docker     (121)     7842 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/webhooks_creation_payload.py
--rw-r--r--   0 runner    (1001) docker     (121)     6986 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model/webhooks_list_response.py
--rw-r--r--   0 runner    (1001) docker     (121)    75154 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/model_utils.py
--rw-r--r--   0 runner    (1001) docker     (121)    12565 2022-09-14 07:38:58.000000 api.video-1.2.8/apivideo/rest.py
--rw-r--r--   0 runner    (1001) docker     (121)       69 2022-09-14 07:39:07.000000 api.video-1.2.8/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (121)     1343 2022-09-14 07:38:58.000000 api.video-1.2.8/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2022-09-14 07:39:07.000000 api.video-1.2.8/test/
--rw-r--r--   0 runner    (1001) docker     (121)     3219 2022-09-14 07:38:58.000000 api.video-1.2.8/test/test_auth.py
--rw-r--r--   0 runner    (1001) docker     (121)     4843 2022-09-14 07:38:58.000000 api.video-1.2.8/test/test_captions_api.py
--rw-r--r--   0 runner    (1001) docker     (121)     3813 2022-09-14 07:38:58.000000 api.video-1.2.8/test/test_chapters_api.py
--rw-r--r--   0 runner    (1001) docker     (121)     2303 2022-09-14 07:38:58.000000 api.video-1.2.8/test/test_integration_raw_statistics_api.py
--rw-r--r--   0 runner    (1001) docker     (121)     5539 2022-09-14 07:38:58.000000 api.video-1.2.8/test/test_integration_videos_api.py
--rw-r--r--   0 runner    (1001) docker     (121)     5336 2022-09-14 07:38:58.000000 api.video-1.2.8/test/test_live_streams_api.py
--rw-r--r--   0 runner    (1001) docker     (121)     6242 2022-09-14 07:38:58.000000 api.video-1.2.8/test/test_player_themes_api.py
--rw-r--r--   0 runner    (1001) docker     (121)     4161 2022-09-14 07:38:58.000000 api.video-1.2.8/test/test_raw_statistics_api.py
--rw-r--r--   0 runner    (1001) docker     (121)     3838 2022-09-14 07:38:58.000000 api.video-1.2.8/test/test_upload_tokens_api.py
--rw-r--r--   0 runner    (1001) docker     (121)    10413 2022-09-14 07:38:58.000000 api.video-1.2.8/test/test_videos_api.py
--rw-r--r--   0 runner    (1001) docker     (121)     2803 2022-09-14 07:38:58.000000 api.video-1.2.8/test/test_watermarks_api.py
--rw-r--r--   0 runner    (1001) docker     (121)     3769 2022-09-14 07:38:58.000000 api.video-1.2.8/test/test_webhooks_api.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:18:03.000000 api.video-1.3.0/
+-rw-r--r--   0 runner    (1001) docker     (123)    24460 2023-06-28 13:18:03.000000 api.video-1.3.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    21570 2023-06-28 13:17:50.000000 api.video-1.3.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:18:03.000000 api.video-1.3.0/api.video.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    24460 2023-06-28 13:18:02.000000 api.video-1.3.0/api.video.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     4066 2023-06-28 13:18:03.000000 api.video-1.3.0/api.video.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 13:18:02.000000 api.video-1.3.0/api.video.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       58 2023-06-28 13:18:02.000000 api.video-1.3.0/api.video.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 13:18:02.000000 api.video-1.3.0/api.video.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:18:03.000000 api.video-1.3.0/apivideo/
+-rw-r--r--   0 runner    (1001) docker     (123)      718 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:18:03.000000 api.video-1.3.0/apivideo/api/
+-rw-r--r--   0 runner    (1001) docker     (123)      214 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/api/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17993 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/api/analytics_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    28915 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/api/captions_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23105 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/api/chapters_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38683 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/api/live_streams_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38017 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/api/player_themes_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19929 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/api/raw_statistics_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22328 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/api/upload_tokens_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    70084 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/api/videos_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16463 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/api/watermarks_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22129 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/api/webhooks_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    37161 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/api_client.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:18:03.000000 api.video-1.3.0/apivideo/apis/
+-rw-r--r--   0 runner    (1001) docker     (123)      955 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/apis/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3091 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/auth_api_client.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16961 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/configuration.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4208 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/endpoint.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5319 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/exceptions.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:18:03.000000 api.video-1.3.0/apivideo/model/
+-rw-r--r--   0 runner    (1001) docker     (123)      348 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7404 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/access_token.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7107 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/additional_bad_request_errors.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6956 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/analytics_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7263 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/analytics_plays400_error.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7027 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/analytics_plays_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6679 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/authenticate_payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7581 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/bad_request.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6950 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/bytes_range.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7102 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/caption.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/captions_list_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6560 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/captions_update_payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6868 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/chapter.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/chapters_list_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6633 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/link.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9310 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/live_stream.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7188 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/live_stream_assets.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8042 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/live_stream_creation_payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7009 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/live_stream_list_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8386 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/live_stream_session.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7007 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/live_stream_session_client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6980 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/live_stream_session_device.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6786 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/live_stream_session_location.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7382 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/live_stream_session_referrer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7150 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/live_stream_session_session.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8229 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/live_stream_update_payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6733 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7115 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/model403_error_schema.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6919 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/not_found.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7715 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/pagination.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6653 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/pagination_link.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7214 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/player_session_event.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10820 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/player_theme.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6770 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/player_theme_assets.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10247 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/player_theme_creation_payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9955 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/player_theme_update_payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7019 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/player_themes_list_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7623 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/quality.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7096 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/raw_statistics_list_live_stream_analytics_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7102 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/raw_statistics_list_player_session_events_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7043 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/raw_statistics_list_sessions_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6949 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/refresh_token_payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7146 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/restreams_request_object.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7023 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/restreams_response_object.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6850 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/token_creation_payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7005 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/token_list_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7360 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/upload_token.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10036 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7490 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_assets.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7093 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_clip.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9630 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_creation_payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8486 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_id.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8221 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_session.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6979 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_session_client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6970 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_session_device.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6760 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_session_location.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6967 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_session_os.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7389 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_session_referrer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7607 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_session_session.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7062 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_source.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7009 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_source_live_stream.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6675 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_source_live_stream_link.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7037 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_status.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7291 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_status_encoding.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8611 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_status_encoding_metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7894 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_status_ingest.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6994 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_status_ingest_received_parts.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7043 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_thumbnail_pick_payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8722 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_update_payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8274 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/video_watermark.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6970 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/videos_list_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6819 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/watermark.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7002 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/watermarks_list_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7132 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/webhook.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7783 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/webhooks_creation_payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6986 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model/webhooks_list_response.py
+-rw-r--r--   0 runner    (1001) docker     (123)    75154 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/model_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12565 2023-06-28 13:17:50.000000 api.video-1.3.0/apivideo/rest.py
+-rw-r--r--   0 runner    (1001) docker     (123)       69 2023-06-28 13:18:03.000000 api.video-1.3.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1343 2023-06-28 13:17:50.000000 api.video-1.3.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 13:18:03.000000 api.video-1.3.0/test/
+-rw-r--r--   0 runner    (1001) docker     (123)     3209 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_analytics_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3219 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_auth.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5111 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_captions_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4033 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_chapters_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2303 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_integration_raw_statistics_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5539 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_integration_videos_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6084 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_live_streams_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6510 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_player_themes_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4381 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_raw_statistics_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4057 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_upload_tokens_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10977 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_videos_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2975 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_watermarks_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3989 2023-06-28 13:17:50.000000 api.video-1.3.0/test/test_webhooks_api.py
```

### Comparing `api.video-1.2.8/PKG-INFO` & `api.video-1.3.0/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,17 +1,17 @@
 Metadata-Version: 2.1
 Name: api.video
-Version: 1.2.8
+Version: 1.3.0
 Summary: api.video Python API client
 Home-page: https://github.com/apivideo/api.video-python-client
 Author: api.video ecosystem team
 Author-email: ecosystem@api.video
 License: MIT
 Description: [![badge](https://img.shields.io/twitter/follow/api_video?style=social)](https://twitter.com/intent/follow?screen_name=api_video) &nbsp; [![badge](https://img.shields.io/github/stars/apivideo/api.video-python-client?style=social)](https://github.com/apivideo/api.video-python-client) &nbsp; [![badge](https://img.shields.io/discourse/topics?server=https%3A%2F%2Fcommunity.api.video)](https://community.api.video)
-        ![](https://github.com/apivideo/API_OAS_file/blob/master/apivideo_banner.png)
+        ![](https://github.com/apivideo/.github/blob/main/assets/apivideo_banner.png)
         <h1 align="center">api.video Python client</h1>
         
         [api.video](https://api.video) is the video infrastructure for product builders. Lightning fast video APIs for integrating, scaling, and managing on-demand & low latency live streaming features in your app.
         
         # Table of contents
         
         - [Table of contents](#table-of-contents)
@@ -20,14 +20,15 @@
           - [Requirements](#requirements)
           - [Installation](#installation)
           - [Code samples](#code-samples)
             - [Automatic authentication](#automatic-authentication)
             - [Manual authentication](#manual-authentication)
         - [Documentation](#documentation)
           - [API Endpoints](#api-endpoints)
+            - [AnalyticsApi](#)
             - [CaptionsApi](#)
             - [ChaptersApi](#)
             - [LiveStreamsApi](#)
             - [PlayerThemesApi](#)
             - [RawStatisticsApi](#)
             - [UploadTokensApi](#)
             - [VideosApi](#)
@@ -107,14 +108,23 @@
         # Documentation
         
         ## API Endpoints
         
         All URIs are relative to *https://ws.api.video*
         
         
+        ### AnalyticsApi
+        
+        
+        Method | HTTP request | Description
+        ------------- | ------------- | -------------
+        [**get_live_streams_plays**](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsApi.md#get_live_streams_plays) | **GET** /analytics/live-streams/plays | Get play events for live stream
+        [**get_videos_plays**](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsApi.md#get_videos_plays) | **GET** /analytics/videos/plays | Get play events for video
+        
+        
         ### CaptionsApi
         
         
         Method | HTTP request | Description
         ------------- | ------------- | -------------
         [**upload**](https://github.com/apivideo/api.video-python-client/blob/main/docs/CaptionsApi.md#upload) | **POST** /videos/{videoId}/captions/{language} | Upload a caption
         [**get**](https://github.com/apivideo/api.video-python-client/blob/main/docs/CaptionsApi.md#get) | **GET** /videos/{videoId}/captions/{language} | Retrieve a caption
@@ -176,32 +186,32 @@
         
         
         Method | HTTP request | Description
         ------------- | ------------- | -------------
         [**create_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#create_token) | **POST** /upload-tokens | Generate an upload token
         [**get_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#get_token) | **GET** /upload-tokens/{uploadToken} | Retrieve upload token
         [**delete_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#delete_token) | **DELETE** /upload-tokens/{uploadToken} | Delete an upload token
-        [**list**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#list) | **GET** /upload-tokens | List all active upload tokens.
+        [**list**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#list) | **GET** /upload-tokens | List all active upload tokens
         
         
         ### VideosApi
         
         
         Method | HTTP request | Description
         ------------- | ------------- | -------------
-        [**create**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#create) | **POST** /videos | Create a video
+        [**create**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#create) | **POST** /videos | Create a video object
         [**upload**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#upload) | **POST** /videos/{videoId}/source | Upload a video
-        [**upload_with_upload_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#upload_with_upload_token) | **POST** /upload | Upload with an upload token
-        [**get**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#get) | **GET** /videos/{videoId} | Retrieve a video
-        [**update**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#update) | **PATCH** /videos/{videoId} | Update a video
-        [**delete**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#delete) | **DELETE** /videos/{videoId} | Delete a video
-        [**list**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#list) | **GET** /videos | List all videos
+        [**upload_with_upload_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#upload_with_upload_token) | **POST** /upload | Upload with an delegated upload token
+        [**get**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#get) | **GET** /videos/{videoId} | Retrieve a video object
+        [**update**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#update) | **PATCH** /videos/{videoId} | Update a video object
+        [**delete**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#delete) | **DELETE** /videos/{videoId} | Delete a video object
+        [**list**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#list) | **GET** /videos | List all video objects
         [**upload_thumbnail**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#upload_thumbnail) | **POST** /videos/{videoId}/thumbnail | Upload a thumbnail
-        [**pick_thumbnail**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#pick_thumbnail) | **PATCH** /videos/{videoId}/thumbnail | Pick a thumbnail
-        [**get_status**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#get_status) | **GET** /videos/{videoId}/status | Retrieve video status
+        [**pick_thumbnail**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#pick_thumbnail) | **PATCH** /videos/{videoId}/thumbnail | Set a thumbnail
+        [**get_status**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#get_status) | **GET** /videos/{videoId}/status | Retrieve video status and details
         
         
         ### WatermarksApi
         
         
         Method | HTTP request | Description
         ------------- | ------------- | -------------
@@ -222,14 +232,18 @@
         
         
         
         
         ## Models
         
          - [AccessToken](https://github.com/apivideo/api.video-python-client/blob/main/docs/AccessToken.md)
+         - [AdditionalBadRequestErrors](https://github.com/apivideo/api.video-python-client/blob/main/docs/AdditionalBadRequestErrors.md)
+         - [AnalyticsData](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsData.md)
+         - [AnalyticsPlays400Error](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsPlays400Error.md)
+         - [AnalyticsPlaysResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsPlaysResponse.md)
          - [AuthenticatePayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/AuthenticatePayload.md)
          - [BadRequest](https://github.com/apivideo/api.video-python-client/blob/main/docs/BadRequest.md)
          - [BytesRange](https://github.com/apivideo/api.video-python-client/blob/main/docs/BytesRange.md)
          - [Caption](https://github.com/apivideo/api.video-python-client/blob/main/docs/Caption.md)
          - [CaptionsListResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/CaptionsListResponse.md)
          - [CaptionsUpdatePayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/CaptionsUpdatePayload.md)
          - [Chapter](https://github.com/apivideo/api.video-python-client/blob/main/docs/Chapter.md)
@@ -243,28 +257,31 @@
          - [LiveStreamSessionClient](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionClient.md)
          - [LiveStreamSessionDevice](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionDevice.md)
          - [LiveStreamSessionLocation](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionLocation.md)
          - [LiveStreamSessionReferrer](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionReferrer.md)
          - [LiveStreamSessionSession](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionSession.md)
          - [LiveStreamUpdatePayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamUpdatePayload.md)
          - [Metadata](https://github.com/apivideo/api.video-python-client/blob/main/docs/Metadata.md)
+         - [Model403ErrorSchema](https://github.com/apivideo/api.video-python-client/blob/main/docs/Model403ErrorSchema.md)
          - [NotFound](https://github.com/apivideo/api.video-python-client/blob/main/docs/NotFound.md)
          - [Pagination](https://github.com/apivideo/api.video-python-client/blob/main/docs/Pagination.md)
          - [PaginationLink](https://github.com/apivideo/api.video-python-client/blob/main/docs/PaginationLink.md)
          - [PlayerSessionEvent](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerSessionEvent.md)
          - [PlayerTheme](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerTheme.md)
          - [PlayerThemeAssets](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerThemeAssets.md)
          - [PlayerThemeCreationPayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerThemeCreationPayload.md)
          - [PlayerThemeUpdatePayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerThemeUpdatePayload.md)
          - [PlayerThemesListResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerThemesListResponse.md)
          - [Quality](https://github.com/apivideo/api.video-python-client/blob/main/docs/Quality.md)
          - [RawStatisticsListLiveStreamAnalyticsResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/RawStatisticsListLiveStreamAnalyticsResponse.md)
          - [RawStatisticsListPlayerSessionEventsResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/RawStatisticsListPlayerSessionEventsResponse.md)
          - [RawStatisticsListSessionsResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/RawStatisticsListSessionsResponse.md)
          - [RefreshTokenPayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/RefreshTokenPayload.md)
+         - [RestreamsRequestObject](https://github.com/apivideo/api.video-python-client/blob/main/docs/RestreamsRequestObject.md)
+         - [RestreamsResponseObject](https://github.com/apivideo/api.video-python-client/blob/main/docs/RestreamsResponseObject.md)
          - [TokenCreationPayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/TokenCreationPayload.md)
          - [TokenListResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/TokenListResponse.md)
          - [UploadToken](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadToken.md)
          - [Video](https://github.com/apivideo/api.video-python-client/blob/main/docs/Video.md)
          - [VideoAssets](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideoAssets.md)
          - [VideoClip](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideoClip.md)
          - [VideoCreationPayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideoCreationPayload.md)
```

### Comparing `api.video-1.2.8/README.md` & `api.video-1.3.0/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 [![badge](https://img.shields.io/twitter/follow/api_video?style=social)](https://twitter.com/intent/follow?screen_name=api_video) &nbsp; [![badge](https://img.shields.io/github/stars/apivideo/api.video-python-client?style=social)](https://github.com/apivideo/api.video-python-client) &nbsp; [![badge](https://img.shields.io/discourse/topics?server=https%3A%2F%2Fcommunity.api.video)](https://community.api.video)
-![](https://github.com/apivideo/API_OAS_file/blob/master/apivideo_banner.png)
+![](https://github.com/apivideo/.github/blob/main/assets/apivideo_banner.png)
 <h1 align="center">api.video Python client</h1>
 
 [api.video](https://api.video) is the video infrastructure for product builders. Lightning fast video APIs for integrating, scaling, and managing on-demand & low latency live streaming features in your app.
 
 # Table of contents
 
 - [Table of contents](#table-of-contents)
@@ -12,14 +12,15 @@
   - [Requirements](#requirements)
   - [Installation](#installation)
   - [Code samples](#code-samples)
     - [Automatic authentication](#automatic-authentication)
     - [Manual authentication](#manual-authentication)
 - [Documentation](#documentation)
   - [API Endpoints](#api-endpoints)
+    - [AnalyticsApi](#)
     - [CaptionsApi](#)
     - [ChaptersApi](#)
     - [LiveStreamsApi](#)
     - [PlayerThemesApi](#)
     - [RawStatisticsApi](#)
     - [UploadTokensApi](#)
     - [VideosApi](#)
@@ -99,14 +100,23 @@
 # Documentation
 
 ## API Endpoints
 
 All URIs are relative to *https://ws.api.video*
 
 
+### AnalyticsApi
+
+
+Method | HTTP request | Description
+------------- | ------------- | -------------
+[**get_live_streams_plays**](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsApi.md#get_live_streams_plays) | **GET** /analytics/live-streams/plays | Get play events for live stream
+[**get_videos_plays**](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsApi.md#get_videos_plays) | **GET** /analytics/videos/plays | Get play events for video
+
+
 ### CaptionsApi
 
 
 Method | HTTP request | Description
 ------------- | ------------- | -------------
 [**upload**](https://github.com/apivideo/api.video-python-client/blob/main/docs/CaptionsApi.md#upload) | **POST** /videos/{videoId}/captions/{language} | Upload a caption
 [**get**](https://github.com/apivideo/api.video-python-client/blob/main/docs/CaptionsApi.md#get) | **GET** /videos/{videoId}/captions/{language} | Retrieve a caption
@@ -168,32 +178,32 @@
 
 
 Method | HTTP request | Description
 ------------- | ------------- | -------------
 [**create_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#create_token) | **POST** /upload-tokens | Generate an upload token
 [**get_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#get_token) | **GET** /upload-tokens/{uploadToken} | Retrieve upload token
 [**delete_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#delete_token) | **DELETE** /upload-tokens/{uploadToken} | Delete an upload token
-[**list**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#list) | **GET** /upload-tokens | List all active upload tokens.
+[**list**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#list) | **GET** /upload-tokens | List all active upload tokens
 
 
 ### VideosApi
 
 
 Method | HTTP request | Description
 ------------- | ------------- | -------------
-[**create**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#create) | **POST** /videos | Create a video
+[**create**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#create) | **POST** /videos | Create a video object
 [**upload**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#upload) | **POST** /videos/{videoId}/source | Upload a video
-[**upload_with_upload_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#upload_with_upload_token) | **POST** /upload | Upload with an upload token
-[**get**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#get) | **GET** /videos/{videoId} | Retrieve a video
-[**update**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#update) | **PATCH** /videos/{videoId} | Update a video
-[**delete**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#delete) | **DELETE** /videos/{videoId} | Delete a video
-[**list**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#list) | **GET** /videos | List all videos
+[**upload_with_upload_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#upload_with_upload_token) | **POST** /upload | Upload with an delegated upload token
+[**get**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#get) | **GET** /videos/{videoId} | Retrieve a video object
+[**update**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#update) | **PATCH** /videos/{videoId} | Update a video object
+[**delete**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#delete) | **DELETE** /videos/{videoId} | Delete a video object
+[**list**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#list) | **GET** /videos | List all video objects
 [**upload_thumbnail**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#upload_thumbnail) | **POST** /videos/{videoId}/thumbnail | Upload a thumbnail
-[**pick_thumbnail**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#pick_thumbnail) | **PATCH** /videos/{videoId}/thumbnail | Pick a thumbnail
-[**get_status**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#get_status) | **GET** /videos/{videoId}/status | Retrieve video status
+[**pick_thumbnail**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#pick_thumbnail) | **PATCH** /videos/{videoId}/thumbnail | Set a thumbnail
+[**get_status**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#get_status) | **GET** /videos/{videoId}/status | Retrieve video status and details
 
 
 ### WatermarksApi
 
 
 Method | HTTP request | Description
 ------------- | ------------- | -------------
@@ -214,14 +224,18 @@
 
 
 
 
 ## Models
 
  - [AccessToken](https://github.com/apivideo/api.video-python-client/blob/main/docs/AccessToken.md)
+ - [AdditionalBadRequestErrors](https://github.com/apivideo/api.video-python-client/blob/main/docs/AdditionalBadRequestErrors.md)
+ - [AnalyticsData](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsData.md)
+ - [AnalyticsPlays400Error](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsPlays400Error.md)
+ - [AnalyticsPlaysResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsPlaysResponse.md)
  - [AuthenticatePayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/AuthenticatePayload.md)
  - [BadRequest](https://github.com/apivideo/api.video-python-client/blob/main/docs/BadRequest.md)
  - [BytesRange](https://github.com/apivideo/api.video-python-client/blob/main/docs/BytesRange.md)
  - [Caption](https://github.com/apivideo/api.video-python-client/blob/main/docs/Caption.md)
  - [CaptionsListResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/CaptionsListResponse.md)
  - [CaptionsUpdatePayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/CaptionsUpdatePayload.md)
  - [Chapter](https://github.com/apivideo/api.video-python-client/blob/main/docs/Chapter.md)
@@ -235,28 +249,31 @@
  - [LiveStreamSessionClient](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionClient.md)
  - [LiveStreamSessionDevice](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionDevice.md)
  - [LiveStreamSessionLocation](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionLocation.md)
  - [LiveStreamSessionReferrer](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionReferrer.md)
  - [LiveStreamSessionSession](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionSession.md)
  - [LiveStreamUpdatePayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamUpdatePayload.md)
  - [Metadata](https://github.com/apivideo/api.video-python-client/blob/main/docs/Metadata.md)
+ - [Model403ErrorSchema](https://github.com/apivideo/api.video-python-client/blob/main/docs/Model403ErrorSchema.md)
  - [NotFound](https://github.com/apivideo/api.video-python-client/blob/main/docs/NotFound.md)
  - [Pagination](https://github.com/apivideo/api.video-python-client/blob/main/docs/Pagination.md)
  - [PaginationLink](https://github.com/apivideo/api.video-python-client/blob/main/docs/PaginationLink.md)
  - [PlayerSessionEvent](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerSessionEvent.md)
  - [PlayerTheme](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerTheme.md)
  - [PlayerThemeAssets](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerThemeAssets.md)
  - [PlayerThemeCreationPayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerThemeCreationPayload.md)
  - [PlayerThemeUpdatePayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerThemeUpdatePayload.md)
  - [PlayerThemesListResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerThemesListResponse.md)
  - [Quality](https://github.com/apivideo/api.video-python-client/blob/main/docs/Quality.md)
  - [RawStatisticsListLiveStreamAnalyticsResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/RawStatisticsListLiveStreamAnalyticsResponse.md)
  - [RawStatisticsListPlayerSessionEventsResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/RawStatisticsListPlayerSessionEventsResponse.md)
  - [RawStatisticsListSessionsResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/RawStatisticsListSessionsResponse.md)
  - [RefreshTokenPayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/RefreshTokenPayload.md)
+ - [RestreamsRequestObject](https://github.com/apivideo/api.video-python-client/blob/main/docs/RestreamsRequestObject.md)
+ - [RestreamsResponseObject](https://github.com/apivideo/api.video-python-client/blob/main/docs/RestreamsResponseObject.md)
  - [TokenCreationPayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/TokenCreationPayload.md)
  - [TokenListResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/TokenListResponse.md)
  - [UploadToken](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadToken.md)
  - [Video](https://github.com/apivideo/api.video-python-client/blob/main/docs/Video.md)
  - [VideoAssets](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideoAssets.md)
  - [VideoClip](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideoClip.md)
  - [VideoCreationPayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideoCreationPayload.md)
```

### Comparing `api.video-1.2.8/api.video.egg-info/PKG-INFO` & `api.video-1.3.0/api.video.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,17 +1,17 @@
 Metadata-Version: 2.1
 Name: api.video
-Version: 1.2.8
+Version: 1.3.0
 Summary: api.video Python API client
 Home-page: https://github.com/apivideo/api.video-python-client
 Author: api.video ecosystem team
 Author-email: ecosystem@api.video
 License: MIT
 Description: [![badge](https://img.shields.io/twitter/follow/api_video?style=social)](https://twitter.com/intent/follow?screen_name=api_video) &nbsp; [![badge](https://img.shields.io/github/stars/apivideo/api.video-python-client?style=social)](https://github.com/apivideo/api.video-python-client) &nbsp; [![badge](https://img.shields.io/discourse/topics?server=https%3A%2F%2Fcommunity.api.video)](https://community.api.video)
-        ![](https://github.com/apivideo/API_OAS_file/blob/master/apivideo_banner.png)
+        ![](https://github.com/apivideo/.github/blob/main/assets/apivideo_banner.png)
         <h1 align="center">api.video Python client</h1>
         
         [api.video](https://api.video) is the video infrastructure for product builders. Lightning fast video APIs for integrating, scaling, and managing on-demand & low latency live streaming features in your app.
         
         # Table of contents
         
         - [Table of contents](#table-of-contents)
@@ -20,14 +20,15 @@
           - [Requirements](#requirements)
           - [Installation](#installation)
           - [Code samples](#code-samples)
             - [Automatic authentication](#automatic-authentication)
             - [Manual authentication](#manual-authentication)
         - [Documentation](#documentation)
           - [API Endpoints](#api-endpoints)
+            - [AnalyticsApi](#)
             - [CaptionsApi](#)
             - [ChaptersApi](#)
             - [LiveStreamsApi](#)
             - [PlayerThemesApi](#)
             - [RawStatisticsApi](#)
             - [UploadTokensApi](#)
             - [VideosApi](#)
@@ -107,14 +108,23 @@
         # Documentation
         
         ## API Endpoints
         
         All URIs are relative to *https://ws.api.video*
         
         
+        ### AnalyticsApi
+        
+        
+        Method | HTTP request | Description
+        ------------- | ------------- | -------------
+        [**get_live_streams_plays**](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsApi.md#get_live_streams_plays) | **GET** /analytics/live-streams/plays | Get play events for live stream
+        [**get_videos_plays**](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsApi.md#get_videos_plays) | **GET** /analytics/videos/plays | Get play events for video
+        
+        
         ### CaptionsApi
         
         
         Method | HTTP request | Description
         ------------- | ------------- | -------------
         [**upload**](https://github.com/apivideo/api.video-python-client/blob/main/docs/CaptionsApi.md#upload) | **POST** /videos/{videoId}/captions/{language} | Upload a caption
         [**get**](https://github.com/apivideo/api.video-python-client/blob/main/docs/CaptionsApi.md#get) | **GET** /videos/{videoId}/captions/{language} | Retrieve a caption
@@ -176,32 +186,32 @@
         
         
         Method | HTTP request | Description
         ------------- | ------------- | -------------
         [**create_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#create_token) | **POST** /upload-tokens | Generate an upload token
         [**get_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#get_token) | **GET** /upload-tokens/{uploadToken} | Retrieve upload token
         [**delete_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#delete_token) | **DELETE** /upload-tokens/{uploadToken} | Delete an upload token
-        [**list**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#list) | **GET** /upload-tokens | List all active upload tokens.
+        [**list**](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadTokensApi.md#list) | **GET** /upload-tokens | List all active upload tokens
         
         
         ### VideosApi
         
         
         Method | HTTP request | Description
         ------------- | ------------- | -------------
-        [**create**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#create) | **POST** /videos | Create a video
+        [**create**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#create) | **POST** /videos | Create a video object
         [**upload**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#upload) | **POST** /videos/{videoId}/source | Upload a video
-        [**upload_with_upload_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#upload_with_upload_token) | **POST** /upload | Upload with an upload token
-        [**get**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#get) | **GET** /videos/{videoId} | Retrieve a video
-        [**update**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#update) | **PATCH** /videos/{videoId} | Update a video
-        [**delete**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#delete) | **DELETE** /videos/{videoId} | Delete a video
-        [**list**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#list) | **GET** /videos | List all videos
+        [**upload_with_upload_token**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#upload_with_upload_token) | **POST** /upload | Upload with an delegated upload token
+        [**get**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#get) | **GET** /videos/{videoId} | Retrieve a video object
+        [**update**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#update) | **PATCH** /videos/{videoId} | Update a video object
+        [**delete**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#delete) | **DELETE** /videos/{videoId} | Delete a video object
+        [**list**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#list) | **GET** /videos | List all video objects
         [**upload_thumbnail**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#upload_thumbnail) | **POST** /videos/{videoId}/thumbnail | Upload a thumbnail
-        [**pick_thumbnail**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#pick_thumbnail) | **PATCH** /videos/{videoId}/thumbnail | Pick a thumbnail
-        [**get_status**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#get_status) | **GET** /videos/{videoId}/status | Retrieve video status
+        [**pick_thumbnail**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#pick_thumbnail) | **PATCH** /videos/{videoId}/thumbnail | Set a thumbnail
+        [**get_status**](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideosApi.md#get_status) | **GET** /videos/{videoId}/status | Retrieve video status and details
         
         
         ### WatermarksApi
         
         
         Method | HTTP request | Description
         ------------- | ------------- | -------------
@@ -222,14 +232,18 @@
         
         
         
         
         ## Models
         
          - [AccessToken](https://github.com/apivideo/api.video-python-client/blob/main/docs/AccessToken.md)
+         - [AdditionalBadRequestErrors](https://github.com/apivideo/api.video-python-client/blob/main/docs/AdditionalBadRequestErrors.md)
+         - [AnalyticsData](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsData.md)
+         - [AnalyticsPlays400Error](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsPlays400Error.md)
+         - [AnalyticsPlaysResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/AnalyticsPlaysResponse.md)
          - [AuthenticatePayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/AuthenticatePayload.md)
          - [BadRequest](https://github.com/apivideo/api.video-python-client/blob/main/docs/BadRequest.md)
          - [BytesRange](https://github.com/apivideo/api.video-python-client/blob/main/docs/BytesRange.md)
          - [Caption](https://github.com/apivideo/api.video-python-client/blob/main/docs/Caption.md)
          - [CaptionsListResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/CaptionsListResponse.md)
          - [CaptionsUpdatePayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/CaptionsUpdatePayload.md)
          - [Chapter](https://github.com/apivideo/api.video-python-client/blob/main/docs/Chapter.md)
@@ -243,28 +257,31 @@
          - [LiveStreamSessionClient](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionClient.md)
          - [LiveStreamSessionDevice](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionDevice.md)
          - [LiveStreamSessionLocation](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionLocation.md)
          - [LiveStreamSessionReferrer](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionReferrer.md)
          - [LiveStreamSessionSession](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamSessionSession.md)
          - [LiveStreamUpdatePayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/LiveStreamUpdatePayload.md)
          - [Metadata](https://github.com/apivideo/api.video-python-client/blob/main/docs/Metadata.md)
+         - [Model403ErrorSchema](https://github.com/apivideo/api.video-python-client/blob/main/docs/Model403ErrorSchema.md)
          - [NotFound](https://github.com/apivideo/api.video-python-client/blob/main/docs/NotFound.md)
          - [Pagination](https://github.com/apivideo/api.video-python-client/blob/main/docs/Pagination.md)
          - [PaginationLink](https://github.com/apivideo/api.video-python-client/blob/main/docs/PaginationLink.md)
          - [PlayerSessionEvent](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerSessionEvent.md)
          - [PlayerTheme](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerTheme.md)
          - [PlayerThemeAssets](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerThemeAssets.md)
          - [PlayerThemeCreationPayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerThemeCreationPayload.md)
          - [PlayerThemeUpdatePayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerThemeUpdatePayload.md)
          - [PlayerThemesListResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/PlayerThemesListResponse.md)
          - [Quality](https://github.com/apivideo/api.video-python-client/blob/main/docs/Quality.md)
          - [RawStatisticsListLiveStreamAnalyticsResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/RawStatisticsListLiveStreamAnalyticsResponse.md)
          - [RawStatisticsListPlayerSessionEventsResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/RawStatisticsListPlayerSessionEventsResponse.md)
          - [RawStatisticsListSessionsResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/RawStatisticsListSessionsResponse.md)
          - [RefreshTokenPayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/RefreshTokenPayload.md)
+         - [RestreamsRequestObject](https://github.com/apivideo/api.video-python-client/blob/main/docs/RestreamsRequestObject.md)
+         - [RestreamsResponseObject](https://github.com/apivideo/api.video-python-client/blob/main/docs/RestreamsResponseObject.md)
          - [TokenCreationPayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/TokenCreationPayload.md)
          - [TokenListResponse](https://github.com/apivideo/api.video-python-client/blob/main/docs/TokenListResponse.md)
          - [UploadToken](https://github.com/apivideo/api.video-python-client/blob/main/docs/UploadToken.md)
          - [Video](https://github.com/apivideo/api.video-python-client/blob/main/docs/Video.md)
          - [VideoAssets](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideoAssets.md)
          - [VideoClip](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideoClip.md)
          - [VideoCreationPayload](https://github.com/apivideo/api.video-python-client/blob/main/docs/VideoCreationPayload.md)
```

### Comparing `api.video-1.2.8/api.video.egg-info/SOURCES.txt` & `api.video-1.3.0/api.video.egg-info/SOURCES.txt`

 * *Files 3% similar despite different names*

```diff
@@ -11,26 +11,31 @@
 apivideo/auth_api_client.py
 apivideo/configuration.py
 apivideo/endpoint.py
 apivideo/exceptions.py
 apivideo/model_utils.py
 apivideo/rest.py
 apivideo/api/__init__.py
+apivideo/api/analytics_api.py
 apivideo/api/captions_api.py
 apivideo/api/chapters_api.py
 apivideo/api/live_streams_api.py
 apivideo/api/player_themes_api.py
 apivideo/api/raw_statistics_api.py
 apivideo/api/upload_tokens_api.py
 apivideo/api/videos_api.py
 apivideo/api/watermarks_api.py
 apivideo/api/webhooks_api.py
 apivideo/apis/__init__.py
 apivideo/model/__init__.py
 apivideo/model/access_token.py
+apivideo/model/additional_bad_request_errors.py
+apivideo/model/analytics_data.py
+apivideo/model/analytics_plays400_error.py
+apivideo/model/analytics_plays_response.py
 apivideo/model/authenticate_payload.py
 apivideo/model/bad_request.py
 apivideo/model/bytes_range.py
 apivideo/model/caption.py
 apivideo/model/captions_list_response.py
 apivideo/model/captions_update_payload.py
 apivideo/model/chapter.py
@@ -44,28 +49,31 @@
 apivideo/model/live_stream_session_client.py
 apivideo/model/live_stream_session_device.py
 apivideo/model/live_stream_session_location.py
 apivideo/model/live_stream_session_referrer.py
 apivideo/model/live_stream_session_session.py
 apivideo/model/live_stream_update_payload.py
 apivideo/model/metadata.py
+apivideo/model/model403_error_schema.py
 apivideo/model/not_found.py
 apivideo/model/pagination.py
 apivideo/model/pagination_link.py
 apivideo/model/player_session_event.py
 apivideo/model/player_theme.py
 apivideo/model/player_theme_assets.py
 apivideo/model/player_theme_creation_payload.py
 apivideo/model/player_theme_update_payload.py
 apivideo/model/player_themes_list_response.py
 apivideo/model/quality.py
 apivideo/model/raw_statistics_list_live_stream_analytics_response.py
 apivideo/model/raw_statistics_list_player_session_events_response.py
 apivideo/model/raw_statistics_list_sessions_response.py
 apivideo/model/refresh_token_payload.py
+apivideo/model/restreams_request_object.py
+apivideo/model/restreams_response_object.py
 apivideo/model/token_creation_payload.py
 apivideo/model/token_list_response.py
 apivideo/model/upload_token.py
 apivideo/model/video.py
 apivideo/model/video_assets.py
 apivideo/model/video_clip.py
 apivideo/model/video_creation_payload.py
@@ -90,14 +98,15 @@
 apivideo/model/video_watermark.py
 apivideo/model/videos_list_response.py
 apivideo/model/watermark.py
 apivideo/model/watermarks_list_response.py
 apivideo/model/webhook.py
 apivideo/model/webhooks_creation_payload.py
 apivideo/model/webhooks_list_response.py
+test/test_analytics_api.py
 test/test_auth.py
 test/test_captions_api.py
 test/test_chapters_api.py
 test/test_integration_raw_statistics_api.py
 test/test_integration_videos_api.py
 test/test_live_streams_api.py
 test/test_player_themes_api.py
```

### Comparing `api.video-1.2.8/apivideo/__init__.py` & `api.video-1.3.0/apivideo/__init__.py`

 * *Files 12% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 
     api.video is an API that encodes on the go to facilitate immediate playback, enhancing viewer streaming experiences across multiple devices and platforms. You can stream live or on-demand online videos within minutes.  # noqa: E501
 
     Contact: ecosystem@api.video
 """
 
 
-__version__ = "1.2.8"
+__version__ = "1.3.0"
 
 # import ApiVideoClient
 from apivideo.auth_api_client import AuthenticatedApiClient
 
 # import exceptions
 from apivideo.exceptions import OpenApiException
 from apivideo.exceptions import ApiAttributeError
```

### Comparing `api.video-1.2.8/apivideo/api/captions_api.py` & `api.video-1.3.0/apivideo/api/captions_api.py`

 * *Files 1% similar despite different names*

```diff
@@ -39,15 +39,15 @@
             video_id,
             language,
             file,
             **kwargs
         ):
             """Upload a caption  # noqa: E501
 
-            Upload a VTT file to add captions to your video.  Read our [captioning tutorial](https://api.video/blog/tutorials/adding-captions) for more details.  # noqa: E501
+            Upload a VTT file to add captions to your video. More information can be found [here](https://docs.api.video/reference/captions)  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.upload(video_id, language, file, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -473,15 +473,15 @@
             self,
             video_id,
             language,
             **kwargs
         ):
             """Delete a caption  # noqa: E501
 
-            Delete a caption in a specific language by providing the video ID for the video you want to delete the caption from and the language the caption is in.  # noqa: E501
+            Delete a caption in a specific language by by video id.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.delete(video_id, language, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -610,15 +610,15 @@
     def list(
             self,
             video_id,
             **kwargs
         ):
             """List video captions  # noqa: E501
 
-            Retrieve a list of available captions for the videoId you provide.  # noqa: E501
+            Retrieve a list of available captions by video id.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.list(video_id, async_req=True)
             >>> result = thread.get()
 
             Args:
```

### Comparing `api.video-1.2.8/apivideo/api/chapters_api.py` & `api.video-1.3.0/apivideo/api/chapters_api.py`

 * *Files 1% similar despite different names*

```diff
@@ -185,15 +185,15 @@
             self,
             video_id,
             language,
             **kwargs
         ):
             """Retrieve a chapter  # noqa: E501
 
-            Retrieve a chapter for a video in a specific language.  Chapters help your viewers find the sections of the video they are most interested in viewing. Tutorials that use the [chapters endpoint](https://api.video/blog/endpoints/chapters).  # noqa: E501
+            Retrieve a chapter for by video id in a specific language.   # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.get(video_id, language, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -460,15 +460,15 @@
     def list(
             self,
             video_id,
             **kwargs
         ):
             """List video chapters  # noqa: E501
 
-            Retrieve a list of all chapters for a specified video.  # noqa: E501
+            Retrieve a list of all chapters for by video id.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.list(video_id, async_req=True)
             >>> result = thread.get()
 
             Args:
```

### Comparing `api.video-1.2.8/apivideo/api/live_streams_api.py` & `api.video-1.3.0/apivideo/api/live_streams_api.py`

 * *Files 8% similar despite different names*

```diff
@@ -38,15 +38,15 @@
     def create(
             self,
             live_stream_creation_payload,
             **kwargs
         ):
             """Create live stream  # noqa: E501
 
-            A live stream will give you the 'connection point' to RTMP your video stream to api.video.  It will also give you the details for viewers to watch the same livestream.   The public=false 'private livestream' is available as a BETA feature, and should be limited to livestreams of 3,000 viewers or fewer.  See our [Live Stream Tutorial](https://api.video/blog/tutorials/live-stream-tutorial) for a walkthrough of this API with OBS.  Your RTMP endpoint for the livestream is rtmp://broadcast.api.video/s/{streamKey} Tutorials that [create live streams](https://api.video/blog/endpoints/live-create).  # noqa: E501
+            Creates a livestream object.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.create(live_stream_creation_payload, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -165,15 +165,15 @@
     def get(
             self,
             live_stream_id,
             **kwargs
         ):
             """Retrieve live stream  # noqa: E501
 
-            Supply a liveStreamId, and you'll get all the details for streaming into, and watching the livestream. Tutorials that use the [show livestream endpoint](https://api.video/blog/endpoints/live-stream-status).  # noqa: E501
+            Get a livestream by id.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.get(live_stream_id, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -294,15 +294,15 @@
             self,
             live_stream_id,
             live_stream_update_payload,
             **kwargs
         ):
             """Update a live stream  # noqa: E501
 
-            Use this endpoint to update the player, or to turn recording on/off (saving a copy of the livestream).  NOTE: If the livestream is actively streaming, changing the recording status will only affect the NEXT stream.     The public=false \"private livestream\" is available as a BETA feature, and should be limited to livestreams of 3,000 viewers or fewer.  # noqa: E501
+            Updates the livestream object.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.update(live_stream_id, live_stream_update_payload, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -557,15 +557,15 @@
 
     def list(
             self,
             **kwargs
         ):
             """List all live streams  # noqa: E501
 
-            With no parameters added to the url, this will return all livestreams. Query by name or key to limit the list.  # noqa: E501
+            Get the list of livestreams on the workspace.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.list(async_req=True)
             >>> result = thread.get()
 
 
@@ -717,15 +717,15 @@
             self,
             live_stream_id,
             file,
             **kwargs
         ):
             """Upload a thumbnail  # noqa: E501
 
-            Upload an image to use as a backdrop for your livestream. Tutorials that [update live stream thumbnails](https://api.video/blog/endpoints/live-upload-a-thumbnail).  # noqa: E501
+            Upload the thumbnail for the livestream.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.upload_thumbnail(live_stream_id, file, async_req=True)
             >>> result = thread.get()
 
             Args:
```

### Comparing `api.video-1.2.8/apivideo/api/player_themes_api.py` & `api.video-1.3.0/apivideo/api/player_themes_api.py`

 * *Files 1% similar despite different names*

```diff
@@ -165,15 +165,15 @@
     def get(
             self,
             player_id,
             **kwargs
         ):
             """Retrieve a player  # noqa: E501
 
-            Use a player ID to retrieve details about the player and display it for viewers.  # noqa: E501
+            Retreive a player theme by player id.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.get(player_id, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -557,15 +557,15 @@
 
     def list(
             self,
             **kwargs
         ):
             """List all player themes  # noqa: E501
 
-            Retrieve a list of all the player themes you created, as well as details about each one. Tutorials that use the [player endpoint](https://api.video/blog/endpoints/player).  # noqa: E501
+            Retrieve a list of all the player themes you created, as well as details about each one.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.list(async_req=True)
             >>> result = thread.get()
 
 
@@ -712,15 +712,15 @@
             self,
             player_id,
             file,
             **kwargs
         ):
             """Upload a logo  # noqa: E501
 
-            The uploaded image maximum size should be 200x100 and its weight should be 100KB.  It will be scaled down to 30px height and converted to PNG to be displayed in the player.  # noqa: E501
+            Upload an image logo for a player.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.upload_logo(player_id, file, async_req=True)
             >>> result = thread.get()
 
             Args:
```

### Comparing `api.video-1.2.8/apivideo/api/raw_statistics_api.py` & `api.video-1.3.0/apivideo/api/raw_statistics_api.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/api/upload_tokens_api.py` & `api.video-1.3.0/apivideo/api/upload_tokens_api.py`

 * *Files 2% similar despite different names*

```diff
@@ -37,15 +37,15 @@
     def create_token(
             self,
             token_creation_payload,
             **kwargs
         ):
             """Generate an upload token  # noqa: E501
 
-            Use this endpoint to generate an upload token. You can use this token to authenticate video uploads while keeping your API key safe. Tutorials using [delegated upload](https://api.video/blog/endpoints/delegated-upload).  # noqa: E501
+            Generates an upload token that can be used to replace the API Key. More information can be found [here](https://docs.api.video/reference/upload-tokens)  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.create_token(token_creation_payload, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -164,15 +164,15 @@
     def get_token(
             self,
             upload_token,
             **kwargs
         ):
             """Retrieve upload token  # noqa: E501
 
-            You can retrieve details about a specific upload token if you have the unique identifier for the upload token. Add it in the path of the endpoint. Details include time-to-live (ttl), when the token was created, and when it will expire.  # noqa: E501
+            Retrieve details about a specific upload token by id.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.get_token(upload_token, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -417,17 +417,17 @@
                 _request_timeout=kwargs['_request_timeout'],
                 collection_formats=params['collection_format'])
 
     def list(
             self,
             **kwargs
         ):
-            """List all active upload tokens.  # noqa: E501
+            """List all active upload tokens  # noqa: E501
 
-            A delegated token is used to allow secure uploads without exposing your API key. Use this endpoint to retrieve a list of all currently active delegated tokens. Tutorials using [delegated upload](https://api.video/blog/endpoints/delegated-upload).  # noqa: E501
+            Retrieve a list of all currently active delegated tokens.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.list(async_req=True)
             >>> result = thread.get()
```

### Comparing `api.video-1.2.8/apivideo/api/videos_api.py` & `api.video-1.3.0/apivideo/api/videos_api.py`

 * *Files 2% similar despite different names*

```diff
@@ -38,17 +38,17 @@
 class VideosApi(_EndPoint):
 
     def create(
             self,
             video_creation_payload,
             **kwargs
         ):
-            """Create a video  # noqa: E501
+            """Create a video object  # noqa: E501
 
-            We have tutorials on: * [Creating and uploading videos](https://api.video/blog/tutorials/video-upload-tutorial) * [Uploading large videos](https://api.video/blog/tutorials/video-upload-tutorial-large-videos) * [Using tags with videos](https://api.video/blog/tutorials/video-tagging-best-practices) * [Private videos](https://api.video/blog/tutorials/tutorial-private-videos) * [Using Dynamic Metadata](https://api.video/blog/tutorials/dynamic-metadata)  * Full list of [tutorials](https://api.video/blog/endpoints/video-create) that demonstrate this endpoint.   # noqa: E501
+            Creates a video object. More information on video objects can be found [here](https://docs.api.video/reference/videos-1).   # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.create(video_creation_payload, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -469,15 +469,15 @@
 
     def upload_with_upload_token(
             self,
             token,
             file,
             **kwargs
         ):
-            """Upload with an upload token  # noqa: E501
+            """Upload with an delegated upload token  # noqa: E501
 
             This method allows you to send a video using an upload token. Upload tokens are especially useful when the upload is done from the client side. If you want to upload a video from your server-side application, you'd better use the [standard upload method](#upload).  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.upload_with_upload_token(token, file, async_req=True)
             >>> result = thread.get()
@@ -772,15 +772,15 @@
         return ProgressiveSession(self, token, video_id)
 
     def get(
             self,
             video_id,
             **kwargs
         ):
-            """Retrieve a video  # noqa: E501
+            """Retrieve a video object  # noqa: E501
 
             This call provides the same information provided on video creation. For private videos, it will generate a unique token url. Use this to retrieve any details you need about a video, or set up a private viewing URL.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.get(video_id, async_req=True)
             >>> result = thread.get()
@@ -901,31 +901,31 @@
 
     def update(
             self,
             video_id,
             video_update_payload,
             **kwargs
         ):
-            """Update a video  # noqa: E501
+            """Update a video object  # noqa: E501
 
-            Updates the parameters associated with your video. The video you are updating is determined by the video ID you provide. 
+            Updates the parameters associated with a video ID. The video object you are updating is determined by the video ID you provide. 
 
 
 
 NOTE: If you are updating an array, you must provide the entire array as what you provide here overwrites what is in the system rather than appending to it.
 
   # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.update(video_id, video_update_payload, async_req=True)
             >>> result = thread.get()
 
             Args:
-                video_id (str): The video ID for the video you want to delete.
+                video_id (str): The video ID for the video you want to update.
                 video_update_payload (VideoUpdatePayload):
 
             Keyword Args:
                 _return_http_data_only (bool): response data without head status
                     code and headers. Default is True.
                 _preload_content (bool): if False, the urllib3.HTTPResponse object
                     will be returned without reading/decoding response data.
@@ -1043,15 +1043,15 @@
                 collection_formats=params['collection_format'])
 
     def delete(
             self,
             video_id,
             **kwargs
         ):
-            """Delete a video  # noqa: E501
+            """Delete a video object  # noqa: E501
 
             If you do not need a video any longer, you can send a request to delete it. All you need is the videoId.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.delete(video_id, async_req=True)
             >>> result = thread.get()
@@ -1170,15 +1170,15 @@
                 _request_timeout=kwargs['_request_timeout'],
                 collection_formats=params['collection_format'])
 
     def list(
             self,
             **kwargs
         ):
-            """List all videos  # noqa: E501
+            """List all video objects  # noqa: E501
 
             This method returns a list of your videos (with all their details). With no parameters added, the API returns the first page of all videos. You can filter videos using the parameters described below.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.list(async_req=True)
             >>> result = thread.get()
@@ -1494,15 +1494,15 @@
 
     def pick_thumbnail(
             self,
             video_id,
             video_thumbnail_pick_payload,
             **kwargs
         ):
-            """Pick a thumbnail  # noqa: E501
+            """Set a thumbnail  # noqa: E501
 
             Pick a thumbnail from the given time code. 
 
 
 
 If you'd like to upload an image for your thumbnail, use the dedicated [method](#uploadThumbnail). 
 
@@ -1640,15 +1640,15 @@
                 collection_formats=params['collection_format'])
 
     def get_status(
             self,
             video_id,
             **kwargs
         ):
-            """Retrieve video status  # noqa: E501
+            """Retrieve video status and details  # noqa: E501
 
             This method provides upload status & encoding status to determine when the video is uploaded or ready to playback. Once encoding is completed, the response also lists the available stream qualities.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.get_status(video_id, async_req=True)
             >>> result = thread.get()
```

### Comparing `api.video-1.2.8/apivideo/api/watermarks_api.py` & `api.video-1.3.0/apivideo/api/watermarks_api.py`

 * *Files 3% similar despite different names*

```diff
@@ -36,15 +36,15 @@
     def upload(
             self,
             file,
             **kwargs
         ):
             """Upload a watermark  # noqa: E501
 
-            Create a new watermark by uploading a `JPG` or a `PNG` image. A watermark is a static image, directly burnt into a video. After you have created your watermark, you can define its placement and aspect when you [create a video](https://docs.api.video/reference/post-video).  # noqa: E501
+            Create a new watermark by uploading a `JPG` or a `PNG` image.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.upload(file, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -164,15 +164,15 @@
     def delete(
             self,
             watermark_id,
             **kwargs
         ):
             """Delete a watermark  # noqa: E501
 
-            Delete a watermark. A watermark is a static image, directly burnt-into a video.  # noqa: E501
+            Delete a watermark.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.delete(watermark_id, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -291,15 +291,15 @@
 
     def list(
             self,
             **kwargs
         ):
             """List all watermarks  # noqa: E501
 
-            List all watermarks. A watermark is a static image, directly burnt into a video. After you have created your watermark, you can define its placement and aspect when you [create a video](https://docs.api.video/reference/post-video).  # noqa: E501
+            List all watermarks associated with your workspace.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.list(async_req=True)
             >>> result = thread.get()
```

### Comparing `api.video-1.2.8/apivideo/api/webhooks_api.py` & `api.video-1.3.0/apivideo/api/webhooks_api.py`

 * *Files 2% similar despite different names*

```diff
@@ -37,15 +37,15 @@
     def create(
             self,
             webhooks_creation_payload,
             **kwargs
         ):
             """Create Webhook  # noqa: E501
 
-            Webhooks can push notifications to your server, rather than polling api.video for changes. We currently offer four events:  * ```video.encoding.quality.completed``` Occurs when a new video is uploaded into your account, it will be encoded into several different HLS and mp4 qualities. When each version is encoded, your webhook will get a notification.  It will look like ```{ \"type\": \"video.encoding.quality.completed\", \"emittedAt\": \"2021-01-29T16:46:25.217+01:00\", \"videoId\": \"viXXXXXXXX\", \"encoding\": \"hls\", \"quality\": \"720p\"} ```. This request says that the 720p HLS encoding was completed. * ```live-stream.broadcast.started```  When a live stream begins broadcasting, the broadcasting parameter changes from false to true, and this webhook fires. * ```live-stream.broadcast.ended```  This event fires when the live stream has finished broadcasting, and the broadcasting parameter flips from false to true. * ```video.source.recorded```  This event occurs when a live stream is recorded and submitted for encoding.  # noqa: E501
+            Webhooks can push notifications to your server, rather than polling api.video for changes. We currently offer four events:  * ```video.encoding.quality.completed``` Occurs when a new video is uploaded into your account, it will be encoded into several different HLS and mp4 qualities. When each version is encoded, your webhook will get a notification.  It will look like ```{ \"type\": \"video.encoding.quality.completed\", \"emittedAt\": \"2021-01-29T16:46:25.217+01:00\", \"videoId\": \"viXXXXXXXX\", \"encoding\": \"hls\", \"quality\": \"720p\"} ```. This request says that the 720p HLS encoding was completed. * ```live-stream.broadcast.started```  When a live stream begins broadcasting, the broadcasting parameter changes from false to true, and this webhook fires. * ```live-stream.broadcast.ended```  This event fires when a live stream has finished broadcasting. * ```video.source.recorded```  This event occurs when a live stream is recorded and submitted for encoding.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.create(webhooks_creation_payload, async_req=True)
             >>> result = thread.get()
 
             Args:
@@ -164,15 +164,15 @@
     def get(
             self,
             webhook_id,
             **kwargs
         ):
             """Retrieve Webhook details  # noqa: E501
 
-            This call provides the same JSON information provided on Webhook creation.  # noqa: E501
+            Retrieve webhook details by id.  # noqa: E501
             This method makes a synchronous HTTP request by default. To make an
             asynchronous HTTP request, please pass async_req=True
 
             >>> thread = api.get(webhook_id, async_req=True)
             >>> result = thread.get()
 
             Args:
```

### Comparing `api.video-1.2.8/apivideo/api_client.py` & `api.video-1.3.0/apivideo/api_client.py`

 * *Files 1% similar despite different names*

```diff
@@ -71,15 +71,15 @@
 
         self.rest_client = rest.RESTClientObject(configuration)
         self.default_headers = {}
         if header_name is not None:
             self.default_headers[header_name] = header_value
         self.cookie = cookie
 
-        self.default_headers['AV-Origin-Client'] = "python:1.2.8"
+        self.default_headers['AV-Origin-Client'] = "python:1.3.0"
 
     def __enter__(self):
         return self
 
     def __exit__(self, exc_type, exc_value, traceback):
         self.close()
 
@@ -768,19 +768,19 @@
 
         return params
 
     def __call__(self, *args, **kwargs):
         """ This method is invoked when endpoints are called
         Example:
 
-        api_instance = CaptionsApi()
-        api_instance.upload  # this is an instance of the class Endpoint
-        api_instance.upload()  # this invokes api_instance.upload.__call__()
+        api_instance = AnalyticsApi()
+        api_instance.get_live_streams_plays  # this is an instance of the class Endpoint
+        api_instance.get_live_streams_plays()  # this invokes api_instance.get_live_streams_plays.__call__()
         which then invokes the callable functions stored in that endpoint at
-        api_instance.upload.callable or self.callable in this class
+        api_instance.get_live_streams_plays.callable or self.callable in this class
 
         """
         return self.callable(self, *args, **kwargs)
 
     def call_with_http_info(self, **kwargs):
 
         try:
```

### Comparing `api.video-1.2.8/apivideo/apis/__init__.py` & `api.video-1.3.0/apivideo/apis/__init__.py`

 * *Files 12% similar despite different names*

```diff
@@ -2,22 +2,23 @@
 # flake8: noqa
 
 # Import all APIs into this package.
 # If you have many APIs here with many many models used in each API this may
 # raise a `RecursionError`.
 # In order to avoid this, import only the API that you directly need like:
 #
-#   from .api.captions_api import CaptionsApi
+#   from .api.analytics_api import AnalyticsApi
 #
 # or import this package, but before doing it, use:
 #
 #   import sys
 #   sys.setrecursionlimit(n)
 
 # Import APIs into API package:
+from apivideo.api.analytics_api import AnalyticsApi
 from apivideo.api.captions_api import CaptionsApi
 from apivideo.api.chapters_api import ChaptersApi
 from apivideo.api.live_streams_api import LiveStreamsApi
 from apivideo.api.player_themes_api import PlayerThemesApi
 from apivideo.api.raw_statistics_api import RawStatisticsApi
 from apivideo.api.upload_tokens_api import UploadTokensApi
 from apivideo.api.videos_api import VideosApi
```

### Comparing `api.video-1.2.8/apivideo/auth_api_client.py` & `api.video-1.3.0/apivideo/auth_api_client.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/configuration.py` & `api.video-1.3.0/apivideo/configuration.py`

 * *Files 0% similar despite different names*

```diff
@@ -387,15 +387,15 @@
 
         :return: The report for debugging.
         """
         return "Python SDK Debug Report:\n"\
                "OS: {env}\n"\
                "Python Version: {pyversion}\n"\
                "Version of the API: 1\n"\
-               "SDK Package Version: 1.2.8".\
+               "SDK Package Version: 1.3.0".\
                format(env=sys.platform, pyversion=sys.version)
 
     def get_host_settings(self):
         """Gets an array of host settings
 
         :return: An array of host settings
         """
```

### Comparing `api.video-1.2.8/apivideo/endpoint.py` & `api.video-1.3.0/apivideo/endpoint.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/exceptions.py` & `api.video-1.3.0/apivideo/exceptions.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/access_token.py` & `api.video-1.3.0/apivideo/model/access_token.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/authenticate_payload.py` & `api.video-1.3.0/apivideo/model/authenticate_payload.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/bad_request.py` & `api.video-1.3.0/apivideo/model/player_session_event.py`

 * *Files 4% similar despite different names*

```diff
@@ -22,15 +22,15 @@
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
 )
 
 
-class BadRequest(ModelNormal):
+class PlayerSessionEvent(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -50,16 +50,14 @@
           as additional properties values.
     """
 
     allowed_values = {
     }
 
     validations = {
-        ('problems',): {
-        },
     }
 
     additional_properties_type = None
 
     _nullable = False
 
     @cached_property
@@ -70,31 +68,31 @@
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
             'type': (str,),  # noqa: E501
-            'title': (str,),  # noqa: E501
-            'name': (str,),  # noqa: E501
-            'status': (int,),  # noqa: E501
-            'problems': ([BadRequest],),  # noqa: E501
+            'emitted_at': (datetime,),  # noqa: E501
+            'at': (int,),  # noqa: E501
+            '_from': (int,),  # noqa: E501
+            'to': (int,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
         'type': 'type',  # noqa: E501
-        'title': 'title',  # noqa: E501
-        'name': 'name',  # noqa: E501
-        'status': 'status',  # noqa: E501
-        'problems': 'problems',  # noqa: E501
+        'emitted_at': 'emittedAt',  # noqa: E501
+        'at': 'at',  # noqa: E501
+        '_from': 'from',  # noqa: E501
+        'to': 'to',  # noqa: E501
     }
 
     _composed_schemas = {}
 
     required_properties = set([
         '_data_store',
         '_check_type',
@@ -102,15 +100,15 @@
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, *args, **kwargs):  # noqa: E501
-        """BadRequest - a model defined in OpenAPI
+        """PlayerSessionEvent - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -135,19 +133,19 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            type (str): [optional]  # noqa: E501
-            title (str): [optional]  # noqa: E501
-            name (str): [optional]  # noqa: E501
-            status (int): [optional]  # noqa: E501
-            problems ([BadRequest]): [optional]  # noqa: E501
+            type (str): Possible values are: ready, play, pause, resume, seek.backward, seek.forward, end. [optional]  # noqa: E501
+            emitted_at (datetime): When an event occurred, presented in ISO-8601 format.. [optional]  # noqa: E501
+            at (int): [optional]  # noqa: E501
+            _from (int): [optional]  # noqa: E501
+            to (int): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `api.video-1.2.8/apivideo/model/bytes_range.py` & `api.video-1.3.0/apivideo/model/bytes_range.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/caption.py` & `api.video-1.3.0/apivideo/model/caption.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/captions_list_response.py` & `api.video-1.3.0/apivideo/model/captions_list_response.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/captions_update_payload.py` & `api.video-1.3.0/apivideo/model/captions_update_payload.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/chapter.py` & `api.video-1.3.0/apivideo/model/chapter.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/chapters_list_response.py` & `api.video-1.3.0/apivideo/model/chapters_list_response.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/link.py` & `api.video-1.3.0/apivideo/model/link.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/live_stream.py` & `api.video-1.3.0/apivideo/model/live_stream.py`

 * *Files 6% similar despite different names*

```diff
@@ -23,15 +23,17 @@
     file_type,
     none_type,
     validate_get_composed_info,
 )
 
 def lazy_import():
     from apivideo.model.live_stream_assets import LiveStreamAssets
+    from apivideo.model.restreams_response_object import RestreamsResponseObject
     globals()['LiveStreamAssets'] = LiveStreamAssets
+    globals()['RestreamsResponseObject'] = RestreamsResponseObject
 
 
 class LiveStream(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
@@ -73,14 +75,15 @@
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         lazy_import()
         return {
             'live_stream_id': (str,),  # noqa: E501
+            'restreams': ([RestreamsResponseObject],),  # noqa: E501
             'name': (str,),  # noqa: E501
             'stream_key': (str,),  # noqa: E501
             'record': (bool,),  # noqa: E501
             'public': (bool,),  # noqa: E501
             'assets': (LiveStreamAssets,),  # noqa: E501
             'player_id': (str,),  # noqa: E501
             'broadcasting': (bool,),  # noqa: E501
@@ -91,14 +94,15 @@
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
         'live_stream_id': 'liveStreamId',  # noqa: E501
+        'restreams': 'restreams',  # noqa: E501
         'name': 'name',  # noqa: E501
         'stream_key': 'streamKey',  # noqa: E501
         'record': 'record',  # noqa: E501
         'public': 'public',  # noqa: E501
         'assets': 'assets',  # noqa: E501
         'player_id': 'playerId',  # noqa: E501
         'broadcasting': 'broadcasting',  # noqa: E501
@@ -114,19 +118,20 @@
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, live_stream_id, *args, **kwargs):  # noqa: E501
+    def __init__(self, live_stream_id, restreams, *args, **kwargs):  # noqa: E501
         """LiveStream - a model defined in OpenAPI
 
         Args:
             live_stream_id (str): The unique identifier for the live stream. Live stream IDs begin with \"li.\"
+            restreams ([RestreamsResponseObject]): Returns the list of RTMP restream destinations.
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -154,15 +159,15 @@
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
             name (str): The name of your live stream.. [optional]  # noqa: E501
             stream_key (str): The unique, private stream key that you use to begin streaming.. [optional]  # noqa: E501
             record (bool): Whether you are recording or not.. [optional]  # noqa: E501
-            public (bool): BETA FEATURE Please limit all public = false (\"private\") livestreams to 3,000 users. Whether your video can be viewed by everyone, or requires authentication to see it. A setting of false will require a unique token for each view.. [optional]  # noqa: E501
+            public (bool): Whether your video can be viewed by everyone, or requires authentication to see it. A setting of false will require a unique token for each view. Learn more about the Private Video feature [here](https://docs.api.video/docs/private-videos).. [optional]  # noqa: E501
             assets (LiveStreamAssets): [optional]  # noqa: E501
             player_id (str): The unique identifier for the player.. [optional]  # noqa: E501
             broadcasting (bool): Whether or not you are broadcasting the live video you recorded for others to see. True means you are broadcasting to viewers, false means you are not.. [optional]  # noqa: E501
             created_at (datetime): When the player was created, presented in ISO-8601 format.. [optional]  # noqa: E501
             updated_at (datetime): When the player was last updated, presented in ISO-8601 format.. [optional]  # noqa: E501
         """
 
@@ -186,14 +191,15 @@
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
         self.live_stream_id = live_stream_id
+        self.restreams = restreams
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `api.video-1.2.8/apivideo/model/live_stream_assets.py` & `api.video-1.3.0/apivideo/model/live_stream_assets.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/live_stream_creation_payload.py` & `api.video-1.3.0/apivideo/model/not_found.py`

 * *Files 4% similar despite different names*

```diff
@@ -22,15 +22,15 @@
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
 )
 
 
-class LiveStreamCreationPayload(ModelNormal):
+class NotFound(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -67,49 +67,46 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
+            'type': (str,),  # noqa: E501
+            'title': (str,),  # noqa: E501
             'name': (str,),  # noqa: E501
-            'record': (bool,),  # noqa: E501
-            'public': (bool,),  # noqa: E501
-            'player_id': (str,),  # noqa: E501
+            'status': (int,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
+        'type': 'type',  # noqa: E501
+        'title': 'title',  # noqa: E501
         'name': 'name',  # noqa: E501
-        'record': 'record',  # noqa: E501
-        'public': 'public',  # noqa: E501
-        'player_id': 'playerId',  # noqa: E501
+        'status': 'status',  # noqa: E501
     }
 
     _composed_schemas = {}
 
     required_properties = set([
         '_data_store',
         '_check_type',
         '_spec_property_naming',
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
-    def __init__(self, name, *args, **kwargs):  # noqa: E501
-        """LiveStreamCreationPayload - a model defined in OpenAPI
-
-        Args:
-            name (str): Add a name for your live stream here.
+    def __init__(self, *args, **kwargs):  # noqa: E501
+        """NotFound - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -134,17 +131,18 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            record (bool): Whether you are recording or not. True for record, false for not record.. [optional] if omitted the server will use the default value of False  # noqa: E501
-            public (bool): BETA FEATURE Please limit all public = false (\"private\") livestreams to 3,000 users. Whether your video can be viewed by everyone, or requires authentication to see it. A setting of false will require a unique token for each view.. [optional]  # noqa: E501
-            player_id (str): The unique identifier for the player.. [optional]  # noqa: E501
+            type (str): [optional]  # noqa: E501
+            title (str): [optional]  # noqa: E501
+            name (str): [optional]  # noqa: E501
+            status (int): [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
@@ -162,15 +160,14 @@
         self._data_store = {}
         self._check_type = _check_type
         self._spec_property_naming = _spec_property_naming
         self._path_to_item = _path_to_item
         self._configuration = _configuration
         self._visited_composed_classes = _visited_composed_classes + (self.__class__,)
 
-        self.name = name
         for var_name, var_value in kwargs.items():
             if var_name not in self.attribute_map and \
                         self._configuration is not None and \
                         self._configuration.discard_unknown_keys and \
                         self.additional_properties_type is None:
                 # discard variable.
                 continue
```

### Comparing `api.video-1.2.8/apivideo/model/live_stream_list_response.py` & `api.video-1.3.0/apivideo/model/live_stream_list_response.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/live_stream_session.py` & `api.video-1.3.0/apivideo/model/live_stream_session.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/live_stream_session_client.py` & `api.video-1.3.0/apivideo/model/live_stream_session_client.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/live_stream_session_device.py` & `api.video-1.3.0/apivideo/model/live_stream_session_device.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/live_stream_session_location.py` & `api.video-1.3.0/apivideo/model/live_stream_session_location.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/live_stream_session_referrer.py` & `api.video-1.3.0/apivideo/model/live_stream_session_referrer.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/live_stream_session_session.py` & `api.video-1.3.0/apivideo/model/live_stream_session_session.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/live_stream_update_payload.py` & `api.video-1.3.0/apivideo/model/analytics_plays400_error.py`

 * *Files 5% similar despite different names*

```diff
@@ -22,15 +22,15 @@
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
 )
 
 
-class LiveStreamUpdatePayload(ModelNormal):
+class AnalyticsPlays400Error(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -67,30 +67,32 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
+            'type': (str,),  # noqa: E501
+            'title': (str,),  # noqa: E501
+            'status': (int,),  # noqa: E501
+            'detail': (str,),  # noqa: E501
             'name': (str,),  # noqa: E501
-            'public': (bool,),  # noqa: E501
-            'record': (bool,),  # noqa: E501
-            'player_id': (str,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
+        'type': 'type',  # noqa: E501
+        'title': 'title',  # noqa: E501
+        'status': 'status',  # noqa: E501
+        'detail': 'detail',  # noqa: E501
         'name': 'name',  # noqa: E501
-        'public': 'public',  # noqa: E501
-        'record': 'record',  # noqa: E501
-        'player_id': 'playerId',  # noqa: E501
     }
 
     _composed_schemas = {}
 
     required_properties = set([
         '_data_store',
         '_check_type',
@@ -98,15 +100,15 @@
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, *args, **kwargs):  # noqa: E501
-        """LiveStreamUpdatePayload - a model defined in OpenAPI
+        """AnalyticsPlays400Error - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -131,18 +133,19 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            name (str): The name you want to use for your live stream.. [optional]  # noqa: E501
-            public (bool): BETA FEATURE Please limit all public = false (\"private\") livestreams to 3,000 users. Whether your video can be viewed by everyone, or requires authentication to see it. A setting of false will require a unique token for each view.. [optional]  # noqa: E501
-            record (bool): Use this to indicate whether you want the recording on or off. On is true, off is false.. [optional]  # noqa: E501
-            player_id (str): The unique ID for the player associated with a live stream that you want to update.. [optional]  # noqa: E501
+            type (str): A link to the error documentation.. [optional]  # noqa: E501
+            title (str): A description of the error that occurred.. [optional]  # noqa: E501
+            status (int): The HTTP status code.. [optional]  # noqa: E501
+            detail (str): A solution for the error.. [optional]  # noqa: E501
+            name (str): The name of the parameter that caused the error.. [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `api.video-1.2.8/apivideo/model/metadata.py` & `api.video-1.3.0/apivideo/model/metadata.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/not_found.py` & `api.video-1.3.0/apivideo/model/model403_error_schema.py`

 * *Files 4% similar despite different names*

```diff
@@ -22,15 +22,15 @@
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
 )
 
 
-class NotFound(ModelNormal):
+class Model403ErrorSchema(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -69,15 +69,15 @@
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
             'type': (str,),  # noqa: E501
             'title': (str,),  # noqa: E501
-            'name': (str,),  # noqa: E501
+            'name': (str, none_type,),  # noqa: E501
             'status': (int,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
@@ -98,15 +98,15 @@
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, *args, **kwargs):  # noqa: E501
-        """NotFound - a model defined in OpenAPI
+        """Model403ErrorSchema - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -131,18 +131,18 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            type (str): [optional]  # noqa: E501
-            title (str): [optional]  # noqa: E501
-            name (str): [optional]  # noqa: E501
-            status (int): [optional]  # noqa: E501
+            type (str): A link to the error documentation.. [optional]  # noqa: E501
+            title (str): A description of the error that occurred.. [optional]  # noqa: E501
+            name (str, none_type): The name of the parameter that caused the error.. [optional]  # noqa: E501
+            status (int): The HTTP status code.. [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `api.video-1.2.8/apivideo/model/pagination.py` & `api.video-1.3.0/apivideo/model/pagination.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/pagination_link.py` & `api.video-1.3.0/apivideo/model/pagination_link.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/player_session_event.py` & `api.video-1.3.0/apivideo/model/upload_token.py`

 * *Files 5% similar despite different names*

```diff
@@ -22,15 +22,15 @@
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
 )
 
 
-class PlayerSessionEvent(ModelNormal):
+class UploadToken(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -50,14 +50,18 @@
           as additional properties values.
     """
 
     allowed_values = {
     }
 
     validations = {
+        ('ttl',): {
+            'inclusive_maximum': 2147483647,
+            'inclusive_minimum': 0,
+        },
     }
 
     additional_properties_type = None
 
     _nullable = False
 
     @cached_property
@@ -67,32 +71,30 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'type': (str,),  # noqa: E501
-            'emitted_at': (datetime,),  # noqa: E501
-            'at': (int,),  # noqa: E501
-            '_from': (int,),  # noqa: E501
-            'to': (int,),  # noqa: E501
+            'token': (str,),  # noqa: E501
+            'ttl': (int,),  # noqa: E501
+            'created_at': (datetime,),  # noqa: E501
+            'expires_at': (datetime, none_type,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'type': 'type',  # noqa: E501
-        'emitted_at': 'emittedAt',  # noqa: E501
-        'at': 'at',  # noqa: E501
-        '_from': 'from',  # noqa: E501
-        'to': 'to',  # noqa: E501
+        'token': 'token',  # noqa: E501
+        'ttl': 'ttl',  # noqa: E501
+        'created_at': 'createdAt',  # noqa: E501
+        'expires_at': 'expiresAt',  # noqa: E501
     }
 
     _composed_schemas = {}
 
     required_properties = set([
         '_data_store',
         '_check_type',
@@ -100,15 +102,15 @@
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, *args, **kwargs):  # noqa: E501
-        """PlayerSessionEvent - a model defined in OpenAPI
+        """UploadToken - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -133,19 +135,18 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            type (str): Possible values are: ready, play, pause, resume, seek.backward, seek.forward, end. [optional]  # noqa: E501
-            emitted_at (datetime): When an event occurred, presented in ISO-8601 format.. [optional]  # noqa: E501
-            at (int): [optional]  # noqa: E501
-            _from (int): [optional]  # noqa: E501
-            to (int): [optional]  # noqa: E501
+            token (str): The unique identifier for the token you will use to authenticate an upload.. [optional]  # noqa: E501
+            ttl (int): Time-to-live - how long the upload token is valid for.. [optional]  # noqa: E501
+            created_at (datetime): When the token was created, displayed in ISO-8601 format.. [optional]  # noqa: E501
+            expires_at (datetime, none_type): When the token expires, displayed in ISO-8601 format.. [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `api.video-1.2.8/apivideo/model/player_theme.py` & `api.video-1.3.0/apivideo/model/player_theme.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/player_theme_assets.py` & `api.video-1.3.0/apivideo/model/player_theme_assets.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/player_theme_creation_payload.py` & `api.video-1.3.0/apivideo/model/player_theme_creation_payload.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/player_theme_update_payload.py` & `api.video-1.3.0/apivideo/model/player_theme_update_payload.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/player_themes_list_response.py` & `api.video-1.3.0/apivideo/model/player_themes_list_response.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/quality.py` & `api.video-1.3.0/apivideo/model/quality.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/raw_statistics_list_live_stream_analytics_response.py` & `api.video-1.3.0/apivideo/model/raw_statistics_list_live_stream_analytics_response.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/raw_statistics_list_player_session_events_response.py` & `api.video-1.3.0/apivideo/model/raw_statistics_list_player_session_events_response.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/raw_statistics_list_sessions_response.py` & `api.video-1.3.0/apivideo/model/raw_statistics_list_sessions_response.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/refresh_token_payload.py` & `api.video-1.3.0/apivideo/model/refresh_token_payload.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/token_creation_payload.py` & `api.video-1.3.0/apivideo/model/token_creation_payload.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/token_list_response.py` & `api.video-1.3.0/apivideo/model/token_list_response.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/upload_token.py` & `api.video-1.3.0/apivideo/model/additional_bad_request_errors.py`

 * *Files 6% similar despite different names*

```diff
@@ -22,15 +22,15 @@
     datetime,
     file_type,
     none_type,
     validate_get_composed_info,
 )
 
 
-class UploadToken(ModelNormal):
+class AdditionalBadRequestErrors(ModelNormal):
     """NOTE: This class is auto generated by OpenAPI Generator.
     Ref: https://openapi-generator.tech
 
     Do not edit the class manually.
 
     Attributes:
       allowed_values (dict): The key is the tuple path to the attribute
@@ -50,18 +50,14 @@
           as additional properties values.
     """
 
     allowed_values = {
     }
 
     validations = {
-        ('ttl',): {
-            'inclusive_maximum': 2147483647,
-            'inclusive_minimum': 0,
-        },
     }
 
     additional_properties_type = None
 
     _nullable = False
 
     @cached_property
@@ -71,30 +67,30 @@
         of type self, this must run after the class is loaded
 
         Returns
             openapi_types (dict): The key is attribute name
                 and the value is attribute type.
         """
         return {
-            'token': (str,),  # noqa: E501
-            'ttl': (int,),  # noqa: E501
-            'created_at': (datetime,),  # noqa: E501
-            'expires_at': (datetime, none_type,),  # noqa: E501
+            'type': (str,),  # noqa: E501
+            'title': (str,),  # noqa: E501
+            'name': (str,),  # noqa: E501
+            'status': (int,),  # noqa: E501
         }
 
     @cached_property
     def discriminator():
         return None
 
 
     attribute_map = {
-        'token': 'token',  # noqa: E501
-        'ttl': 'ttl',  # noqa: E501
-        'created_at': 'createdAt',  # noqa: E501
-        'expires_at': 'expiresAt',  # noqa: E501
+        'type': 'type',  # noqa: E501
+        'title': 'title',  # noqa: E501
+        'name': 'name',  # noqa: E501
+        'status': 'status',  # noqa: E501
     }
 
     _composed_schemas = {}
 
     required_properties = set([
         '_data_store',
         '_check_type',
@@ -102,15 +98,15 @@
         '_path_to_item',
         '_configuration',
         '_visited_composed_classes',
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, *args, **kwargs):  # noqa: E501
-        """UploadToken - a model defined in OpenAPI
+        """AdditionalBadRequestErrors - a model defined in OpenAPI
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
             _path_to_item (tuple/list): This is a list of keys or values to
@@ -135,18 +131,18 @@
                                 petType and we pass in "Dog", and the class Dog
                                 allOf includes Animal, we move through Animal
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
-            token (str): The unique identifier for the token you will use to authenticate an upload.. [optional]  # noqa: E501
-            ttl (int): Time-to-live - how long the upload token is valid for.. [optional]  # noqa: E501
-            created_at (datetime): When the token was created, displayed in ISO-8601 format.. [optional]  # noqa: E501
-            expires_at (datetime, none_type): When the token expires, displayed in ISO-8601 format.. [optional]  # noqa: E501
+            type (str): A link to the error documentation.. [optional]  # noqa: E501
+            title (str): A description of the error that occurred.. [optional]  # noqa: E501
+            name (str): The name of the parameter that caused the error.. [optional]  # noqa: E501
+            status (int): The HTTP status code.. [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
         _visited_composed_classes = kwargs.pop('_visited_composed_classes', ())
```

### Comparing `api.video-1.2.8/apivideo/model/video.py` & `api.video-1.3.0/apivideo/model/video.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_assets.py` & `api.video-1.3.0/apivideo/model/video_assets.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_clip.py` & `api.video-1.3.0/apivideo/model/video_clip.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_creation_payload.py` & `api.video-1.3.0/apivideo/model/video_creation_payload.py`

 * *Files 1% similar despite different names*

```diff
@@ -159,15 +159,15 @@
                                 once using the discriminator, and pick Dog.
                                 Then in Dog, we will make an instance of the
                                 Animal class but this time we won't travel
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
             description (str): A brief description of your video.. [optional]  # noqa: E501
             source (str): You can either add a video already on the web, by entering the URL of the video, or you can also enter the `videoId` of one of the videos you already have on your api.video acccount, and this will generate a copy of your video. Creating a copy of a video can be especially useful if you want to keep your original video and trim or apply a watermark onto the copy you would create.. [optional]  # noqa: E501
-            public (bool): Whether your video can be viewed by everyone, or requires authentication to see it. A setting of false will require a unique token for each view. Default is true. Tutorials on [private videos](https://api.video/blog/endpoints/private-videos).. [optional] if omitted the server will use the default value of True  # noqa: E501
+            public (bool): Default: True. If set to `false` the video will become private. More information on private videos can be found [here](https://docs.api.video/docs/private-videos). [optional] if omitted the server will use the default value of True  # noqa: E501
             panoramic (bool): Indicates if your video is a 360/immersive video.. [optional] if omitted the server will use the default value of False  # noqa: E501
             mp4_support (bool): Enables mp4 version in addition to streamed version.. [optional] if omitted the server will use the default value of True  # noqa: E501
             player_id (str): The unique identification number for your video player.. [optional]  # noqa: E501
             tags ([str]): A list of tags you want to use to describe your video.. [optional]  # noqa: E501
             metadata ([Metadata]): A list of key value pairs that you use to provide metadata for your video. These pairs can be made dynamic, allowing you to segment your audience. Read more on [dynamic metadata](https://api.video/blog/endpoints/dynamic-metadata).. [optional]  # noqa: E501
             clip (VideoClip): [optional]  # noqa: E501
             watermark (VideoWatermark): [optional]  # noqa: E501
```

### Comparing `api.video-1.2.8/apivideo/model/video_id.py` & `api.video-1.3.0/apivideo/model/video_id.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_session.py` & `api.video-1.3.0/apivideo/model/video_session.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_session_client.py` & `api.video-1.3.0/apivideo/model/video_session_client.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_session_device.py` & `api.video-1.3.0/apivideo/model/video_session_device.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_session_location.py` & `api.video-1.3.0/apivideo/model/video_session_location.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_session_os.py` & `api.video-1.3.0/apivideo/model/video_session_os.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_session_referrer.py` & `api.video-1.3.0/apivideo/model/video_session_referrer.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_session_session.py` & `api.video-1.3.0/apivideo/model/video_session_session.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_source.py` & `api.video-1.3.0/apivideo/model/video_source.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_source_live_stream.py` & `api.video-1.3.0/apivideo/model/video_source_live_stream.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_source_live_stream_link.py` & `api.video-1.3.0/apivideo/model/video_source_live_stream_link.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_status.py` & `api.video-1.3.0/apivideo/model/video_status.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_status_encoding.py` & `api.video-1.3.0/apivideo/model/video_status_encoding.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_status_encoding_metadata.py` & `api.video-1.3.0/apivideo/model/video_status_encoding_metadata.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_status_ingest.py` & `api.video-1.3.0/apivideo/model/video_status_ingest.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_status_ingest_received_parts.py` & `api.video-1.3.0/apivideo/model/video_status_ingest_received_parts.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_thumbnail_pick_payload.py` & `api.video-1.3.0/apivideo/model/video_thumbnail_pick_payload.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_update_payload.py` & `api.video-1.3.0/apivideo/model/video_update_payload.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/video_watermark.py` & `api.video-1.3.0/apivideo/model/video_watermark.py`

 * *Files 3% similar despite different names*

```diff
@@ -144,16 +144,16 @@
                                 through its discriminator because we passed in
                                 _visited_composed_classes = (Animal,)
             id (str): id of the watermark. [optional]  # noqa: E501
             top (str): Distance expressed in px or % between the top-border of the video and the watermark-image.. [optional]  # noqa: E501
             left (str): Distance expressed in px or % between the left-border of the video and the watermark-image.. [optional]  # noqa: E501
             bottom (str): Distance expressed in px or % between the bottom-border of the video and the watermark-image.. [optional]  # noqa: E501
             right (str): Distance expressed in px or % between the right-border of the video and the watermark-image.. [optional]  # noqa: E501
-            width (str): Width of the watermark-image relative to the video if expressed in %. Otherwise a fixed width. NOTE: To keep intrinsic watermark-image width use initial. [optional]  # noqa: E501
-            height (str): Width of the watermark-image relative to the video if expressed in %. Otherwise a fixed height. NOTE: To keep intrinsic watermark-image height use initial. [optional]  # noqa: E501
+            width (str): Width of the watermark-image relative to the video if expressed in %. Otherwise a fixed width. NOTE: To keep intrinsic watermark-image width use `initial`.. [optional]  # noqa: E501
+            height (str): Height of the watermark-image relative to the video if expressed in %. Otherwise a fixed height. NOTE: To keep intrinsic watermark-image height use `initial`.. [optional]  # noqa: E501
             opacity (str): Opacity expressed in % only to specify the degree of the watermark-image transparency with the video.. [optional]  # noqa: E501
         """
 
         _check_type = kwargs.pop('_check_type', True)
         _spec_property_naming = kwargs.pop('_spec_property_naming', False)
         _path_to_item = kwargs.pop('_path_to_item', ())
         _configuration = kwargs.pop('_configuration', None)
```

### Comparing `api.video-1.2.8/apivideo/model/videos_list_response.py` & `api.video-1.3.0/apivideo/model/videos_list_response.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/watermark.py` & `api.video-1.3.0/apivideo/model/watermark.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/watermarks_list_response.py` & `api.video-1.3.0/apivideo/model/watermarks_list_response.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/webhook.py` & `api.video-1.3.0/apivideo/model/webhook.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model/webhooks_creation_payload.py` & `api.video-1.3.0/apivideo/model/webhooks_creation_payload.py`

 * *Files 1% similar despite different names*

```diff
@@ -97,15 +97,15 @@
     ])
 
     @convert_js_args_to_python_args
     def __init__(self, events, url, *args, **kwargs):  # noqa: E501
         """WebhooksCreationPayload - a model defined in OpenAPI
 
         Args:
-            events ([str]): A list of the webhooks that you are subscribing to. There are Currently four webhook options: * ```video.encoding.quality.completed```  Occurs when a new video is uploaded into your account, it will be encoded into several different HLS and mp4 qualities. When each version is encoded, your webhook will get a notification.  It will look like ```{ \\\"type\\\": \\\"video.encoding.quality.completed\\\", \\\"emittedAt\\\": \\\"2021-01-29T16:46:25.217+01:00\\\", \\\"videoId\\\": \\\"viXXXXXXXX\\\", \\\"encoding\\\": \\\"hls\\\", \\\"quality\\\": \\\"720p\\\"} ```. This request says that the 720p HLS encoding was completed. * ```live-stream.broadcast.started```  When a live stream begins broadcasting, the broadcasting parameter changes from false to true, and this webhook fires. * ```live-stream.broadcast.ended```  This event fires when the live stream has finished broadcasting, and the broadcasting parameter flips from false to true. * ```video.source.recorded```  Occurs when a live stream is recorded and submitted for encoding.
+            events ([str]): A list of the webhooks that you are subscribing to. There are Currently four webhook options: * ```video.encoding.quality.completed```  Occurs when a new video is uploaded into your account, it will be encoded into several different HLS and mp4 qualities. When each version is encoded, your webhook will get a notification.  It will look like ```{ \\\"type\\\": \\\"video.encoding.quality.completed\\\", \\\"emittedAt\\\": \\\"2021-01-29T16:46:25.217+01:00\\\", \\\"videoId\\\": \\\"viXXXXXXXX\\\", \\\"encoding\\\": \\\"hls\\\", \\\"quality\\\": \\\"720p\\\"} ```. This request says that the 720p HLS encoding was completed. * ```live-stream.broadcast.started```  When a live stream begins broadcasting, the broadcasting parameter changes from false to true, and this webhook fires. * ```live-stream.broadcast.ended```  This event fires when a live stream has finished broadcasting. * ```video.source.recorded```  Occurs when a live stream is recorded and submitted for encoding.
             url (str): The the url to which HTTP notifications are sent. It could be any http or https URL.
 
         Keyword Args:
             _check_type (bool): if True, values for parameters in openapi_types
                                 will be type checked and a TypeError will be
                                 raised if the wrong type is input.
                                 Defaults to True
```

### Comparing `api.video-1.2.8/apivideo/model/webhooks_list_response.py` & `api.video-1.3.0/apivideo/model/webhooks_list_response.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/model_utils.py` & `api.video-1.3.0/apivideo/model_utils.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/apivideo/rest.py` & `api.video-1.3.0/apivideo/rest.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/setup.py` & `api.video-1.3.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -6,15 +6,15 @@
     Contact: ecosystem@api.video
 """
 
 import pathlib
 from setuptools import setup, find_packages  # noqa: H301
 
 NAME = "api.video"
-VERSION = "1.2.8"
+VERSION = "1.3.0"
 # To install the library, run the following
 #
 # python setup.py install
 #
 # prerequisite: setuptools
 # http://pypi.python.org/pypi/setuptools
```

### Comparing `api.video-1.2.8/test/test_auth.py` & `api.video-1.3.0/test/test_auth.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/test/test_captions_api.py` & `api.video-1.3.0/test/test_captions_api.py`

 * *Files 8% similar despite different names*

```diff
@@ -10,14 +10,16 @@
 from urllib3_mock import Responses
 
 from apivideo.api.captions_api import CaptionsApi  # noqa: E501
 from apivideo.exceptions import ApiException, NotFoundException
 from apivideo.model.metadata import Metadata
 from apivideo.model.video_clip import VideoClip
 from apivideo.model.video_watermark import VideoWatermark
+from apivideo.model.restreams_request_object import RestreamsRequestObject
+
 from apivideo.model.bad_request import BadRequest
 from apivideo.model.caption import Caption
 from apivideo.model.captions_list_response import CaptionsListResponse
 from apivideo.model.captions_update_payload import CaptionsUpdatePayload
 from apivideo.model.not_found import NotFound
 
 from helper import MainTest
@@ -35,15 +37,16 @@
 
     @responses.activate
     def test_upload(self):
         """Test case for upload
 
         Upload a caption  # noqa: E501
         """
-        for status, json in self.load_json('captions', 'upload'):
+        for file_name, json in self.load_json('captions', 'upload'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "vi4k0jvEUuaTdRAEjQ4Prklg",
                 'language': "en",
                 'file': open('test_file', 'rb'),
             }
@@ -61,15 +64,16 @@
 
     @responses.activate
     def test_get(self):
         """Test case for get
 
         Retrieve a caption  # noqa: E501
         """
-        for status, json in self.load_json('captions', 'get'):
+        for file_name, json in self.load_json('captions', 'get'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "vi4k0jvEUuaTdRAEjQ4Prklg",
                 'language': "en",
             }
             url = '/videos/{video_id}/captions/{language}'.format(**kwargs)
@@ -86,15 +90,16 @@
 
     @responses.activate
     def test_update(self):
         """Test case for update
 
         Update a caption  # noqa: E501
         """
-        for status, json in self.load_json('captions', 'update'):
+        for file_name, json in self.load_json('captions', 'update'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "vi4k0jvEUuaTdRAEjQ4Prklg",
                 'language': "en",
                 'captions_update_payload': CaptionsUpdatePayload(
         default=True,
@@ -122,15 +127,16 @@
 
     @responses.activate
     def test_list(self):
         """Test case for list
 
         List video captions  # noqa: E501
         """
-        for status, json in self.load_json('captions', 'list'):
+        for file_name, json in self.load_json('captions', 'list'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "vi4k0jvEUuaTdRAEjQ4Prklg",
             }
             url = '/videos/{video_id}/captions'.format(**kwargs)
```

### Comparing `api.video-1.2.8/test/test_chapters_api.py` & `api.video-1.3.0/test/test_chapters_api.py`

 * *Files 5% similar despite different names*

```diff
@@ -10,14 +10,16 @@
 from urllib3_mock import Responses
 
 from apivideo.api.chapters_api import ChaptersApi  # noqa: E501
 from apivideo.exceptions import ApiException, NotFoundException
 from apivideo.model.metadata import Metadata
 from apivideo.model.video_clip import VideoClip
 from apivideo.model.video_watermark import VideoWatermark
+from apivideo.model.restreams_request_object import RestreamsRequestObject
+
 from apivideo.model.bad_request import BadRequest
 from apivideo.model.chapter import Chapter
 from apivideo.model.chapters_list_response import ChaptersListResponse
 from apivideo.model.not_found import NotFound
 
 from helper import MainTest
 
@@ -34,15 +36,16 @@
 
     @responses.activate
     def test_upload(self):
         """Test case for upload
 
         Upload a chapter  # noqa: E501
         """
-        for status, json in self.load_json('chapters', 'upload'):
+        for file_name, json in self.load_json('chapters', 'upload'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "vi4k0jvEUuaTdRAEjQ4Jfrgz",
                 'language': "en",
                 'file': open('test_file', 'rb'),
             }
@@ -60,15 +63,16 @@
 
     @responses.activate
     def test_get(self):
         """Test case for get
 
         Retrieve a chapter  # noqa: E501
         """
-        for status, json in self.load_json('chapters', 'get'):
+        for file_name, json in self.load_json('chapters', 'get'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "vi4k0jvEUuaTdRAEjQ4Jfrgz",
                 'language': "en",
             }
             url = '/videos/{video_id}/chapters/{language}'.format(**kwargs)
@@ -93,15 +97,16 @@
 
     @responses.activate
     def test_list(self):
         """Test case for list
 
         List video chapters  # noqa: E501
         """
-        for status, json in self.load_json('chapters', 'list'):
+        for file_name, json in self.load_json('chapters', 'list'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "vi4k0jvEUuaTdRAEjQ4Jfrgz",
             }
             url = '/videos/{video_id}/chapters'.format(**kwargs)
```

### Comparing `api.video-1.2.8/test/test_integration_raw_statistics_api.py` & `api.video-1.3.0/test/test_integration_raw_statistics_api.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/test/test_integration_videos_api.py` & `api.video-1.3.0/test/test_integration_videos_api.py`

 * *Files identical despite different names*

### Comparing `api.video-1.2.8/test/test_live_streams_api.py` & `api.video-1.3.0/test/test_live_streams_api.py`

 * *Files 5% similar despite different names*

```diff
@@ -10,14 +10,16 @@
 from urllib3_mock import Responses
 
 from apivideo.api.live_streams_api import LiveStreamsApi  # noqa: E501
 from apivideo.exceptions import ApiException, NotFoundException
 from apivideo.model.metadata import Metadata
 from apivideo.model.video_clip import VideoClip
 from apivideo.model.video_watermark import VideoWatermark
+from apivideo.model.restreams_request_object import RestreamsRequestObject
+
 from apivideo.model.bad_request import BadRequest
 from apivideo.model.live_stream import LiveStream
 from apivideo.model.live_stream_creation_payload import LiveStreamCreationPayload
 from apivideo.model.live_stream_list_response import LiveStreamListResponse
 from apivideo.model.live_stream_update_payload import LiveStreamUpdatePayload
 from apivideo.model.not_found import NotFound
 
@@ -36,23 +38,31 @@
 
     @responses.activate
     def test_create(self):
         """Test case for create
 
         Create live stream  # noqa: E501
         """
-        for status, json in self.load_json('live_streams', 'create'):
+        for file_name, json in self.load_json('live_streams', 'create'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'live_stream_creation_payload': LiveStreamCreationPayload(
         name="My Live Stream Video",
         record=True,
         public=True,
         player_id="pl4f4ferf5erfr5zed4fsdd",
+        restreams=[
+            RestreamsRequestObject(
+                name="My RTMP server",
+                server_url="rtmp://my.broadcast.example.com/app",
+                stream_key="dw-dew8-q6w9-k67w-1ws8",
+            ),
+        ],
     ),
             }
             url = '/live-streams'.format(**kwargs)
 
             responses.add('POST', url, body=json, status=int(status), content_type='application/json')
 
             if status[0] == '4':
@@ -65,15 +75,16 @@
 
     @responses.activate
     def test_get(self):
         """Test case for get
 
         Retrieve live stream  # noqa: E501
         """
-        for status, json in self.load_json('live_streams', 'get'):
+        for file_name, json in self.load_json('live_streams', 'get'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'live_stream_id': "li400mYKSgQ6xs7taUeSaEKr",
             }
             url = '/live-streams/{live_stream_id}'.format(**kwargs)
 
@@ -89,24 +100,32 @@
 
     @responses.activate
     def test_update(self):
         """Test case for update
 
         Update a live stream  # noqa: E501
         """
-        for status, json in self.load_json('live_streams', 'update'):
+        for file_name, json in self.load_json('live_streams', 'update'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'live_stream_id': "li400mYKSgQ6xs7taUeSaEKr",
                 'live_stream_update_payload': LiveStreamUpdatePayload(
         name="My Live Stream Video",
         public=True,
         record=True,
         player_id="pl45KFKdlddgk654dspkze",
+        restreams=[
+            RestreamsRequestObject(
+                name="My RTMP server",
+                server_url="rtmp://my.broadcast.example.com/app",
+                stream_key="dw-dew8-q6w9-k67w-1ws8",
+            ),
+        ],
     ),
             }
             url = '/live-streams/{live_stream_id}'.format(**kwargs)
 
             responses.add('PATCH', url, body=json, status=int(status), content_type='application/json')
 
             if status[0] == '4':
@@ -127,15 +146,16 @@
 
     @responses.activate
     def test_list(self):
         """Test case for list
 
         List all live streams  # noqa: E501
         """
-        for status, json in self.load_json('live_streams', 'list'):
+        for file_name, json in self.load_json('live_streams', 'list'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
             }
             url = '/live-streams'.format(**kwargs)
 
             responses.add('GET', url, body=json, status=int(status), content_type='application/json')
```

### Comparing `api.video-1.2.8/test/test_player_themes_api.py` & `api.video-1.3.0/test/test_player_themes_api.py`

 * *Files 4% similar despite different names*

```diff
@@ -10,14 +10,16 @@
 from urllib3_mock import Responses
 
 from apivideo.api.player_themes_api import PlayerThemesApi  # noqa: E501
 from apivideo.exceptions import ApiException, NotFoundException
 from apivideo.model.metadata import Metadata
 from apivideo.model.video_clip import VideoClip
 from apivideo.model.video_watermark import VideoWatermark
+from apivideo.model.restreams_request_object import RestreamsRequestObject
+
 from apivideo.model.bad_request import BadRequest
 from apivideo.model.not_found import NotFound
 from apivideo.model.player_theme import PlayerTheme
 from apivideo.model.player_theme_creation_payload import PlayerThemeCreationPayload
 from apivideo.model.player_theme_update_payload import PlayerThemeUpdatePayload
 from apivideo.model.player_themes_list_response import PlayerThemesListResponse
 
@@ -36,15 +38,16 @@
 
     @responses.activate
     def test_create(self):
         """Test case for create
 
         Create a player  # noqa: E501
         """
-        for status, json in self.load_json('player_themes', 'create'):
+        for file_name, json in self.load_json('player_themes', 'create'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'player_theme_creation_payload': PlayerThemeCreationPayload(
         name="name_example",
         text="text_example",
         link="link_example",
@@ -77,15 +80,16 @@
 
     @responses.activate
     def test_get(self):
         """Test case for get
 
         Retrieve a player  # noqa: E501
         """
-        for status, json in self.load_json('player_themes', 'get'):
+        for file_name, json in self.load_json('player_themes', 'get'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'player_id': "pl45d5vFFGrfdsdsd156dGhh",
             }
             url = '/players/{player_id}'.format(**kwargs)
 
@@ -101,15 +105,16 @@
 
     @responses.activate
     def test_update(self):
         """Test case for update
 
         Update a player  # noqa: E501
         """
-        for status, json in self.load_json('player_themes', 'update'):
+        for file_name, json in self.load_json('player_themes', 'update'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'player_id': "pl45d5vFFGrfdsdsd156dGhh",
                 'player_theme_update_payload': PlayerThemeUpdatePayload(
         name="name_example",
         text="text_example",
@@ -151,15 +156,16 @@
 
     @responses.activate
     def test_list(self):
         """Test case for list
 
         List all player themes  # noqa: E501
         """
-        for status, json in self.load_json('player_themes', 'list'):
+        for file_name, json in self.load_json('player_themes', 'list'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
             }
             url = '/players'.format(**kwargs)
 
             responses.add('GET', url, body=json, status=int(status), content_type='application/json')
```

### Comparing `api.video-1.2.8/test/test_raw_statistics_api.py` & `api.video-1.3.0/test/test_raw_statistics_api.py`

 * *Files 5% similar despite different names*

```diff
@@ -10,14 +10,16 @@
 from urllib3_mock import Responses
 
 from apivideo.api.raw_statistics_api import RawStatisticsApi  # noqa: E501
 from apivideo.exceptions import ApiException, NotFoundException
 from apivideo.model.metadata import Metadata
 from apivideo.model.video_clip import VideoClip
 from apivideo.model.video_watermark import VideoWatermark
+from apivideo.model.restreams_request_object import RestreamsRequestObject
+
 from apivideo.model.not_found import NotFound
 from apivideo.model.raw_statistics_list_live_stream_analytics_response import RawStatisticsListLiveStreamAnalyticsResponse
 from apivideo.model.raw_statistics_list_player_session_events_response import RawStatisticsListPlayerSessionEventsResponse
 from apivideo.model.raw_statistics_list_sessions_response import RawStatisticsListSessionsResponse
 
 from helper import MainTest
 
@@ -34,15 +36,16 @@
 
     @responses.activate
     def test_list_live_stream_sessions(self):
         """Test case for list_live_stream_sessions
 
         List live stream player sessions  # noqa: E501
         """
-        for status, json in self.load_json('raw_statistics', 'list_live_stream_sessions'):
+        for file_name, json in self.load_json('raw_statistics', 'list_live_stream_sessions'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'live_stream_id': "vi4k0jvEUuaTdRAEjQ4Jfrgz",
                 'period': "2019-01-01T00:00:00.000Z",
             }
             url = '/analytics/live-streams/{live_stream_id}'.format(**kwargs)
@@ -59,15 +62,16 @@
 
     @responses.activate
     def test_list_session_events(self):
         """Test case for list_session_events
 
         List player session events  # noqa: E501
         """
-        for status, json in self.load_json('raw_statistics', 'list_session_events'):
+        for file_name, json in self.load_json('raw_statistics', 'list_session_events'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'session_id': "psEmFwGQUAXR2lFHj5nDOpy",
             }
             url = '/analytics/sessions/{session_id}/events'.format(**kwargs)
 
@@ -83,15 +87,16 @@
 
     @responses.activate
     def test_list_video_sessions(self):
         """Test case for list_video_sessions
 
         List video player sessions  # noqa: E501
         """
-        for status, json in self.load_json('raw_statistics', 'list_video_sessions'):
+        for file_name, json in self.load_json('raw_statistics', 'list_video_sessions'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "vi4k0jvEUuaTdRAEjQ4Prklg",
                 'period': "period_example",
             }
             url = '/analytics/videos/{video_id}'.format(**kwargs)
```

### Comparing `api.video-1.2.8/test/test_upload_tokens_api.py` & `api.video-1.3.0/test/test_webhooks_api.py`

 * *Files 17% similar despite different names*

```diff
@@ -5,108 +5,114 @@
 
     Contact: ecosystem@api.video
 """
 
 from dateutil.parser import parse as dateutil_parser
 from urllib3_mock import Responses
 
-from apivideo.api.upload_tokens_api import UploadTokensApi  # noqa: E501
+from apivideo.api.webhooks_api import WebhooksApi  # noqa: E501
 from apivideo.exceptions import ApiException, NotFoundException
 from apivideo.model.metadata import Metadata
 from apivideo.model.video_clip import VideoClip
 from apivideo.model.video_watermark import VideoWatermark
+from apivideo.model.restreams_request_object import RestreamsRequestObject
+
 from apivideo.model.bad_request import BadRequest
 from apivideo.model.not_found import NotFound
-from apivideo.model.token_creation_payload import TokenCreationPayload
-from apivideo.model.token_list_response import TokenListResponse
-from apivideo.model.upload_token import UploadToken
+from apivideo.model.webhook import Webhook
+from apivideo.model.webhooks_creation_payload import WebhooksCreationPayload
+from apivideo.model.webhooks_list_response import WebhooksListResponse
 
 from helper import MainTest
 
 
 responses = Responses()
 
 
-class TestUploadTokensApi(MainTest):
-    """UploadTokensApi unit test"""
+class TestWebhooksApi(MainTest):
+    """WebhooksApi unit test"""
 
     def setUp(self):
         super().setUp()
-        self.api = UploadTokensApi(self.client)  # noqa: E501
+        self.api = WebhooksApi(self.client)  # noqa: E501
 
     @responses.activate
-    def test_create_token(self):
-        """Test case for create_token
+    def test_create(self):
+        """Test case for create
 
-        Generate an upload token  # noqa: E501
+        Create Webhook  # noqa: E501
         """
-        for status, json in self.load_json('upload_tokens', 'create_token'):
+        for file_name, json in self.load_json('webhooks', 'create'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
-                'token_creation_payload': TokenCreationPayload(
-        ttl=0,
+                'webhooks_creation_payload': WebhooksCreationPayload(
+        events=["video.encoding.quality.completed"],
+        url="https://example.com/webhooks",
     ),
             }
-            url = '/upload-tokens'.format(**kwargs)
+            url = '/webhooks'.format(**kwargs)
 
             responses.add('POST', url, body=json, status=int(status), content_type='application/json')
 
             if status[0] == '4':
                 with self.assertRaises(ApiException) as context:
-                    self.api.create_token(**kwargs)
+                    self.api.create(**kwargs)
                 if status == '404':
                     self.assertIsInstance(context.exception, NotFoundException)
             else:
-                self.api.create_token(**kwargs)
+                self.api.create(**kwargs)
 
     @responses.activate
-    def test_get_token(self):
-        """Test case for get_token
+    def test_get(self):
+        """Test case for get
 
-        Retrieve upload token  # noqa: E501
+        Retrieve Webhook details  # noqa: E501
         """
-        for status, json in self.load_json('upload_tokens', 'get_token'):
+        for file_name, json in self.load_json('webhooks', 'get'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
-                'upload_token': "to1tcmSFHeYY5KzyhOqVKMKb",
+                'webhook_id': "webhookId_example",
             }
-            url = '/upload-tokens/{upload_token}'.format(**kwargs)
+            url = '/webhooks/{webhook_id}'.format(**kwargs)
 
             responses.add('GET', url, body=json, status=int(status), content_type='application/json')
 
             if status[0] == '4':
                 with self.assertRaises(ApiException) as context:
-                    self.api.get_token(**kwargs)
+                    self.api.get(**kwargs)
                 if status == '404':
                     self.assertIsInstance(context.exception, NotFoundException)
             else:
-                self.api.get_token(**kwargs)
+                self.api.get(**kwargs)
 
     @responses.activate
-    def test_delete_token(self):
-        """Test case for delete_token
+    def test_delete(self):
+        """Test case for delete
 
-        Delete an upload token  # noqa: E501
+        Delete a Webhook  # noqa: E501
         """
         pass
 
     @responses.activate
     def test_list(self):
         """Test case for list
 
-        List all active upload tokens.  # noqa: E501
+        List all webhooks  # noqa: E501
         """
-        for status, json in self.load_json('upload_tokens', 'list'):
+        for file_name, json in self.load_json('webhooks', 'list'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
             }
-            url = '/upload-tokens'.format(**kwargs)
+            url = '/webhooks'.format(**kwargs)
 
             responses.add('GET', url, body=json, status=int(status), content_type='application/json')
 
             if status[0] == '4':
                 with self.assertRaises(ApiException) as context:
                     self.api.list(**kwargs)
                 if status == '404':
```

### Comparing `api.video-1.2.8/test/test_videos_api.py` & `api.video-1.3.0/test/test_videos_api.py`

 * *Files 9% similar despite different names*

```diff
@@ -10,14 +10,16 @@
 from urllib3_mock import Responses
 
 from apivideo.api.videos_api import VideosApi  # noqa: E501
 from apivideo.exceptions import ApiException, NotFoundException
 from apivideo.model.metadata import Metadata
 from apivideo.model.video_clip import VideoClip
 from apivideo.model.video_watermark import VideoWatermark
+from apivideo.model.restreams_request_object import RestreamsRequestObject
+
 from apivideo.model.bad_request import BadRequest
 from apivideo.model.not_found import NotFound
 from apivideo.model.video import Video
 from apivideo.model.video_creation_payload import VideoCreationPayload
 from apivideo.model.video_status import VideoStatus
 from apivideo.model.video_thumbnail_pick_payload import VideoThumbnailPickPayload
 from apivideo.model.video_update_payload import VideoUpdatePayload
@@ -36,17 +38,18 @@
         super().setUp()
         self.api = VideosApi(self.client)  # noqa: E501
 
     @responses.activate
     def test_create(self):
         """Test case for create
 
-        Create a video  # noqa: E501
+        Create a video object  # noqa: E501
         """
-        for status, json in self.load_json('videos', 'create'):
+        for file_name, json in self.load_json('videos', 'create'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_creation_payload': VideoCreationPayload(
         title="Maths video",
         description="A video about string theory.",
         source="https://www.myvideo.url.com/video.mp4 OR vi4k0jvEUuaTdRAEjQ4JfOyl",
@@ -91,15 +94,16 @@
 
     @responses.activate
     def test_upload(self):
         """Test case for upload
 
         Upload a video  # noqa: E501
         """
-        for status, json in self.load_json('videos', 'upload'):
+        for file_name, json in self.load_json('videos', 'upload'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "vi4k0jvEUuaTdRAEjQ4Jfrgz",
                 'file': open('test_file', 'rb'),
             }
             url = '/videos/{video_id}/source'.format(**kwargs)
@@ -114,17 +118,18 @@
             else:
                 self.api.upload(**kwargs)
 
     @responses.activate
     def test_upload_with_upload_token(self):
         """Test case for upload_with_upload_token
 
-        Upload with an upload token  # noqa: E501
+        Upload with an delegated upload token  # noqa: E501
         """
-        for status, json in self.load_json('videos', 'upload_with_upload_token'):
+        for file_name, json in self.load_json('videos', 'upload_with_upload_token'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'token': "to1tcmSFHeYY5KzyhOqVKMKb",
                 'file': open('test_file', 'rb'),
             }
             url = '/upload'.format(**kwargs)
@@ -139,17 +144,18 @@
             else:
                 self.api.upload_with_upload_token(**kwargs)
 
     @responses.activate
     def test_get(self):
         """Test case for get
 
-        Retrieve a video  # noqa: E501
+        Retrieve a video object  # noqa: E501
         """
-        for status, json in self.load_json('videos', 'get'):
+        for file_name, json in self.load_json('videos', 'get'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "videoId_example",
             }
             url = '/videos/{video_id}'.format(**kwargs)
 
@@ -163,17 +169,18 @@
             else:
                 self.api.get(**kwargs)
 
     @responses.activate
     def test_update(self):
         """Test case for update
 
-        Update a video  # noqa: E501
+        Update a video object  # noqa: E501
         """
-        for status, json in self.load_json('videos', 'update'):
+        for file_name, json in self.load_json('videos', 'update'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "vi4k0jvEUuaTdRAEjQ4Jfrgz",
                 'video_update_payload': VideoUpdatePayload(
         player_id="pl4k0jvEUuaTdRAEjQ4Jfrgz",
         title="title_example",
@@ -202,25 +209,26 @@
             else:
                 self.api.update(**kwargs)
 
     @responses.activate
     def test_delete(self):
         """Test case for delete
 
-        Delete a video  # noqa: E501
+        Delete a video object  # noqa: E501
         """
         pass
 
     @responses.activate
     def test_list(self):
         """Test case for list
 
-        List all videos  # noqa: E501
+        List all video objects  # noqa: E501
         """
-        for status, json in self.load_json('videos', 'list'):
+        for file_name, json in self.load_json('videos', 'list'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
             }
             url = '/videos'.format(**kwargs)
 
             responses.add('GET', url, body=json, status=int(status), content_type='application/json')
@@ -235,15 +243,16 @@
 
     @responses.activate
     def test_upload_thumbnail(self):
         """Test case for upload_thumbnail
 
         Upload a thumbnail  # noqa: E501
         """
-        for status, json in self.load_json('videos', 'upload_thumbnail'):
+        for file_name, json in self.load_json('videos', 'upload_thumbnail'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "videoId_example",
                 'file': open('test_file', 'rb'),
             }
             url = '/videos/{video_id}/thumbnail'.format(**kwargs)
@@ -258,17 +267,18 @@
             else:
                 self.api.upload_thumbnail(**kwargs)
 
     @responses.activate
     def test_pick_thumbnail(self):
         """Test case for pick_thumbnail
 
-        Pick a thumbnail  # noqa: E501
+        Set a thumbnail  # noqa: E501
         """
-        for status, json in self.load_json('videos', 'pick_thumbnail'):
+        for file_name, json in self.load_json('videos', 'pick_thumbnail'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "vi4k0jvEUuaTdRAEjQ4Jfrgz",
                 'video_thumbnail_pick_payload': VideoThumbnailPickPayload(
         timecode="04:80:72",
     ),
@@ -285,17 +295,18 @@
             else:
                 self.api.pick_thumbnail(**kwargs)
 
     @responses.activate
     def test_get_status(self):
         """Test case for get_status
 
-        Retrieve video status  # noqa: E501
+        Retrieve video status and details  # noqa: E501
         """
-        for status, json in self.load_json('videos', 'get_status'):
+        for file_name, json in self.load_json('videos', 'get_status'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'video_id': "vi4k0jvEUuaTdRAEjQ4Jfrgz",
             }
             url = '/videos/{video_id}/status'.format(**kwargs)
```

### Comparing `api.video-1.2.8/test/test_watermarks_api.py` & `api.video-1.3.0/test/test_watermarks_api.py`

 * *Files 15% similar despite different names*

```diff
@@ -10,14 +10,16 @@
 from urllib3_mock import Responses
 
 from apivideo.api.watermarks_api import WatermarksApi  # noqa: E501
 from apivideo.exceptions import ApiException, NotFoundException
 from apivideo.model.metadata import Metadata
 from apivideo.model.video_clip import VideoClip
 from apivideo.model.video_watermark import VideoWatermark
+from apivideo.model.restreams_request_object import RestreamsRequestObject
+
 from apivideo.model.bad_request import BadRequest
 from apivideo.model.not_found import NotFound
 from apivideo.model.watermark import Watermark
 from apivideo.model.watermarks_list_response import WatermarksListResponse
 
 from helper import MainTest
 
@@ -34,15 +36,16 @@
 
     @responses.activate
     def test_upload(self):
         """Test case for upload
 
         Upload a watermark  # noqa: E501
         """
-        for status, json in self.load_json('watermarks', 'upload'):
+        for file_name, json in self.load_json('watermarks', 'upload'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
                 'file': open('test_file', 'rb'),
             }
             url = '/watermarks'.format(**kwargs)
 
@@ -66,15 +69,16 @@
 
     @responses.activate
     def test_list(self):
         """Test case for list
 
         List all watermarks  # noqa: E501
         """
-        for status, json in self.load_json('watermarks', 'list'):
+        for file_name, json in self.load_json('watermarks', 'list'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
             }
             url = '/watermarks'.format(**kwargs)
 
             responses.add('GET', url, body=json, status=int(status), content_type='application/json')
```

### Comparing `api.video-1.2.8/test/test_webhooks_api.py` & `api.video-1.3.0/test/test_analytics_api.py`

 * *Files 20% similar despite different names*

```diff
@@ -5,113 +5,84 @@
 
     Contact: ecosystem@api.video
 """
 
 from dateutil.parser import parse as dateutil_parser
 from urllib3_mock import Responses
 
-from apivideo.api.webhooks_api import WebhooksApi  # noqa: E501
+from apivideo.api.analytics_api import AnalyticsApi  # noqa: E501
 from apivideo.exceptions import ApiException, NotFoundException
 from apivideo.model.metadata import Metadata
 from apivideo.model.video_clip import VideoClip
 from apivideo.model.video_watermark import VideoWatermark
-from apivideo.model.bad_request import BadRequest
+from apivideo.model.restreams_request_object import RestreamsRequestObject
+
+from apivideo.model.analytics_plays400_error import AnalyticsPlays400Error
+from apivideo.model.analytics_plays_response import AnalyticsPlaysResponse
+from apivideo.model.model403_error_schema import Model403ErrorSchema
 from apivideo.model.not_found import NotFound
-from apivideo.model.webhook import Webhook
-from apivideo.model.webhooks_creation_payload import WebhooksCreationPayload
-from apivideo.model.webhooks_list_response import WebhooksListResponse
 
 from helper import MainTest
 
 
 responses = Responses()
 
 
-class TestWebhooksApi(MainTest):
-    """WebhooksApi unit test"""
+class TestAnalyticsApi(MainTest):
+    """AnalyticsApi unit test"""
 
     def setUp(self):
         super().setUp()
-        self.api = WebhooksApi(self.client)  # noqa: E501
-
-    @responses.activate
-    def test_create(self):
-        """Test case for create
-
-        Create Webhook  # noqa: E501
-        """
-        for status, json in self.load_json('webhooks', 'create'):
-            responses.reset()
-
-            kwargs = {
-                'webhooks_creation_payload': WebhooksCreationPayload(
-        events=["video.encoding.quality.completed"],
-        url="https://example.com/webhooks",
-    ),
-            }
-            url = '/webhooks'.format(**kwargs)
-
-            responses.add('POST', url, body=json, status=int(status), content_type='application/json')
-
-            if status[0] == '4':
-                with self.assertRaises(ApiException) as context:
-                    self.api.create(**kwargs)
-                if status == '404':
-                    self.assertIsInstance(context.exception, NotFoundException)
-            else:
-                self.api.create(**kwargs)
+        self.api = AnalyticsApi(self.client)  # noqa: E501
 
     @responses.activate
-    def test_get(self):
-        """Test case for get
+    def test_get_live_streams_plays(self):
+        """Test case for get_live_streams_plays
 
-        Retrieve Webhook details  # noqa: E501
+        Get play events for live stream  # noqa: E501
         """
-        for status, json in self.load_json('webhooks', 'get'):
+        for file_name, json in self.load_json('analytics', 'get_live_streams_plays'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
-                'webhook_id': "webhookId_example",
+                '_from': dateutil_parser('2023-06-01').date(),
+                'dimension': "browser",
             }
-            url = '/webhooks/{webhook_id}'.format(**kwargs)
+            url = '/analytics/live-streams/plays'.format(**kwargs)
 
             responses.add('GET', url, body=json, status=int(status), content_type='application/json')
 
             if status[0] == '4':
                 with self.assertRaises(ApiException) as context:
-                    self.api.get(**kwargs)
+                    self.api.get_live_streams_plays(**kwargs)
                 if status == '404':
                     self.assertIsInstance(context.exception, NotFoundException)
             else:
-                self.api.get(**kwargs)
-
-    @responses.activate
-    def test_delete(self):
-        """Test case for delete
-
-        Delete a Webhook  # noqa: E501
-        """
-        pass
+                self.api.get_live_streams_plays(**kwargs)
 
     @responses.activate
-    def test_list(self):
-        """Test case for list
+    def test_get_videos_plays(self):
+        """Test case for get_videos_plays
 
-        List all webhooks  # noqa: E501
+        Get play events for video  # noqa: E501
         """
-        for status, json in self.load_json('webhooks', 'list'):
+        for file_name, json in self.load_json('analytics', 'get_videos_plays'):
+            status = file_name.split("-")[0]
             responses.reset()
 
             kwargs = {
+                '_from': dateutil_parser('2023-06-01').date(),
+                'dimension': "browser",
             }
-            url = '/webhooks'.format(**kwargs)
+            url = '/analytics/videos/plays'.format(**kwargs)
 
             responses.add('GET', url, body=json, status=int(status), content_type='application/json')
 
             if status[0] == '4':
                 with self.assertRaises(ApiException) as context:
-                    self.api.list(**kwargs)
+                    self.api.get_videos_plays(**kwargs)
                 if status == '404':
                     self.assertIsInstance(context.exception, NotFoundException)
             else:
-                self.api.list(**kwargs)
+                self.api.get_videos_plays(**kwargs)
```

