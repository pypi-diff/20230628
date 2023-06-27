# Comparing `tmp/allianceauth-discordbot-3.6.1.tar.gz` & `tmp/allianceauth-discordbot-3.6.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "allianceauth-discordbot-3.6.1.tar", last modified: Sun May  7 14:19:13 2023, max compression
+gzip compressed data, was "allianceauth-discordbot-3.6.2.tar", last modified: Tue Jun 27 23:30:52 2023, max compression
```

## Comparing `allianceauth-discordbot-3.6.1.tar` & `allianceauth-discordbot-3.6.2.tar`

### file list

```diff
@@ -1,63 +1,63 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-07 14:19:13.189020 allianceauth-discordbot-3.6.1/
--rw-r--r--   0 runner    (1001) docker     (123)      109 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)    14900 2023-05-07 14:19:13.189020 allianceauth-discordbot-3.6.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13993 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-07 14:19:13.185020 allianceauth-discordbot-3.6.1/aadiscordbot/
--rw-r--r--   0 runner    (1001) docker     (123)      133 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1854 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/admin.py
--rw-r--r--   0 runner    (1001) docker     (123)     3697 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/app_settings.py
--rw-r--r--   0 runner    (1001) docker     (123)      263 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/apps.py
--rw-r--r--   0 runner    (1001) docker     (123)      928 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/auth_hooks.py
--rw-r--r--   0 runner    (1001) docker     (123)    17005 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/bot.py
--rw-r--r--   0 runner    (1001) docker     (123)     3671 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/bot_tasks.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-07 14:19:13.189020 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3311 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/about.py
--rw-r--r--   0 runner    (1001) docker     (123)     2931 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/abuse.py
--rw-r--r--   0 runner    (1001) docker     (123)    16421 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/admin.py
--rw-r--r--   0 runner    (1001) docker     (123)     2722 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/auth.py
--rw-r--r--   0 runner    (1001) docker     (123)      909 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/eastereggs.py
--rw-r--r--   0 runner    (1001) docker     (123)     1459 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/eightball.py
--rw-r--r--   0 runner    (1001) docker     (123)     3827 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/facwar.py
--rw-r--r--   0 runner    (1001) docker     (123)    12559 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/members.py
--rw-r--r--   0 runner    (1001) docker     (123)     3531 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/models.py
--rw-r--r--   0 runner    (1001) docker     (123)     5632 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/price_check.py
--rw-r--r--   0 runner    (1001) docker     (123)     1495 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/prom_export.py
--rw-r--r--   0 runner    (1001) docker     (123)     5180 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/quote.py
--rw-r--r--   0 runner    (1001) docker     (123)     6214 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/reaction_roles.py
--rw-r--r--   0 runner    (1001) docker     (123)     1105 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/remind.py
--rw-r--r--   0 runner    (1001) docker     (123)     6532 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/services.py
--rw-r--r--   0 runner    (1001) docker     (123)    15830 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/sov.py
--rw-r--r--   0 runner    (1001) docker     (123)     1396 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/time.py
--rw-r--r--   0 runner    (1001) docker     (123)     2171 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/timers.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-07 14:19:13.189020 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/utils/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      207 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/utils/context.py
--rw-r--r--   0 runner    (1001) docker     (123)     3883 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/utils/decorators.py
--rw-r--r--   0 runner    (1001) docker     (123)      437 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/utils/exceptions.py
--rw-r--r--   0 runner    (1001) docker     (123)     4373 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/cogs/welcomegoodbye.py
--rw-r--r--   0 runner    (1001) docker     (123)      235 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/launcher.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-07 14:19:13.189020 allianceauth-discordbot-3.6.1/aadiscordbot/migrations/
--rw-r--r--   0 runner    (1001) docker     (123)     1621 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0001_initial.py
--rw-r--r--   0 runner    (1001) docker     (123)     1410 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0002_reactionrolebinding_reactionrolemessage.py
--rw-r--r--   0 runner    (1001) docker     (123)      636 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0003_authbotconfiguration.py
--rw-r--r--   0 runner    (1001) docker     (123)      485 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0004_settings.py
--rw-r--r--   0 runner    (1001) docker     (123)      759 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0005_rr_fixes_blank_admins.py
--rw-r--r--   0 runner    (1001) docker     (123)     1773 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0006_goodbyemessage_welcomemessage.py
--rw-r--r--   0 runner    (1001) docker     (123)     1219 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0007_quotemessage.py
--rw-r--r--   0 runner    (1001) docker     (123)      413 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0008_channels_deleted.py
--rw-r--r--   0 runner    (1001) docker     (123)      507 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0009_alter_quotemessage_options.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/migrations/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     4556 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/models.py
--rw-r--r--   0 runner    (1001) docker     (123)      317 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/providers.py
--rw-r--r--   0 runner    (1001) docker     (123)     3409 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/tasks.py
--rw-r--r--   0 runner    (1001) docker     (123)       45 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/urls.py
--rw-r--r--   0 runner    (1001) docker     (123)       15 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/aadiscordbot/views.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-07 14:19:13.189020 allianceauth-discordbot-3.6.1/allianceauth_discordbot.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    14900 2023-05-07 14:19:13.000000 allianceauth-discordbot-3.6.1/allianceauth_discordbot.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1818 2023-05-07 14:19:13.000000 allianceauth-discordbot-3.6.1/allianceauth_discordbot.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-07 14:19:13.000000 allianceauth-discordbot-3.6.1/allianceauth_discordbot.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       91 2023-05-07 14:19:13.000000 allianceauth-discordbot-3.6.1/allianceauth_discordbot.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       13 2023-05-07 14:19:13.000000 allianceauth-discordbot-3.6.1/allianceauth_discordbot.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-05-07 14:19:13.189020 allianceauth-discordbot-3.6.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1516 2023-05-07 14:18:28.000000 allianceauth-discordbot-3.6.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:30:51.992964 allianceauth-discordbot-3.6.2/
+-rw-r--r--   0 runner    (1001) docker     (123)      109 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)    14900 2023-06-27 23:30:51.992964 allianceauth-discordbot-3.6.2/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13993 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:30:51.988964 allianceauth-discordbot-3.6.2/aadiscordbot/
+-rw-r--r--   0 runner    (1001) docker     (123)      134 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1854 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/admin.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3768 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/app_settings.py
+-rw-r--r--   0 runner    (1001) docker     (123)      263 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/apps.py
+-rw-r--r--   0 runner    (1001) docker     (123)      928 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/auth_hooks.py
+-rw-r--r--   0 runner    (1001) docker     (123)    17002 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/bot.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4126 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/bot_tasks.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:30:51.988964 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3261 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/about.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2931 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/abuse.py
+-rw-r--r--   0 runner    (1001) docker     (123)    16421 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/admin.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2694 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/auth.py
+-rw-r--r--   0 runner    (1001) docker     (123)      909 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/eastereggs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1459 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/eightball.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3827 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/facwar.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12559 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/members.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3531 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5632 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/price_check.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1495 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/prom_export.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5180 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/quote.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6214 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/reaction_roles.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1105 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/remind.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6532 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/services.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15830 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/sov.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1396 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/time.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2171 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/timers.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:30:51.992964 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      207 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/utils/context.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3883 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/utils/decorators.py
+-rw-r--r--   0 runner    (1001) docker     (123)      437 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/utils/exceptions.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4373 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/cogs/welcomegoodbye.py
+-rw-r--r--   0 runner    (1001) docker     (123)      235 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/launcher.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:30:51.992964 allianceauth-discordbot-3.6.2/aadiscordbot/migrations/
+-rw-r--r--   0 runner    (1001) docker     (123)     1621 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0001_initial.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1410 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0002_reactionrolebinding_reactionrolemessage.py
+-rw-r--r--   0 runner    (1001) docker     (123)      636 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0003_authbotconfiguration.py
+-rw-r--r--   0 runner    (1001) docker     (123)      485 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0004_settings.py
+-rw-r--r--   0 runner    (1001) docker     (123)      759 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0005_rr_fixes_blank_admins.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1773 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0006_goodbyemessage_welcomemessage.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1219 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0007_quotemessage.py
+-rw-r--r--   0 runner    (1001) docker     (123)      413 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0008_channels_deleted.py
+-rw-r--r--   0 runner    (1001) docker     (123)      507 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0009_alter_quotemessage_options.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/migrations/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4556 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/models.py
+-rw-r--r--   0 runner    (1001) docker     (123)      317 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/providers.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3628 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/tasks.py
+-rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/urls.py
+-rw-r--r--   0 runner    (1001) docker     (123)       15 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/aadiscordbot/views.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-27 23:30:51.992964 allianceauth-discordbot-3.6.2/allianceauth_discordbot.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    14900 2023-06-27 23:30:51.000000 allianceauth-discordbot-3.6.2/allianceauth_discordbot.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1818 2023-06-27 23:30:51.000000 allianceauth-discordbot-3.6.2/allianceauth_discordbot.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-27 23:30:51.000000 allianceauth-discordbot-3.6.2/allianceauth_discordbot.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       91 2023-06-27 23:30:51.000000 allianceauth-discordbot-3.6.2/allianceauth_discordbot.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       13 2023-06-27 23:30:51.000000 allianceauth-discordbot-3.6.2/allianceauth_discordbot.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-27 23:30:51.992964 allianceauth-discordbot-3.6.2/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1516 2023-06-27 23:30:02.000000 allianceauth-discordbot-3.6.2/setup.py
```

### Comparing `allianceauth-discordbot-3.6.1/PKG-INFO` & `allianceauth-discordbot-3.6.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: allianceauth-discordbot
-Version: 3.6.1
+Version: 3.6.2
 Summary: Alliance Auth Discord Bot
 Home-page: https://github.com/pvyParts/allianceauth-discordbot
 Author: ak
 Author-email: ak@ak.auth
 License: GNU General Public License v3 (GPLv3)
 Platform: UNKNOWN
 Classifier: Environment :: Web Environment
```

### Comparing `allianceauth-discordbot-3.6.1/README.md` & `allianceauth-discordbot-3.6.2/README.md`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/admin.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/admin.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/app_settings.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/app_settings.py`

 * *Files 2% similar despite different names*

```diff
@@ -103,15 +103,16 @@
     settings, 'AUTHBOT_DISCORD_APP_ID', getattr(
         settings, 'DISCORD_APP_ID', None))
 
 
 DISCORD_BOT_TASK_RATE_LIMITS = getattr(settings, 'DISCORD_BOT_TASK_RATE_LIMITS',
                                        {"send_channel_message_by_discord_id": "100/s",
                                         "send_direct_message_by_discord_id": "100/s",
-                                        "send_direct_message_by_user_id": "100/s"})
+                                        "send_direct_message_by_user_id": "100/s",
+                                        "pop_user_group_cache": "5/s"})
 
 DISCORD_BOT_ESS_PING_CHANNEL_ID = getattr(
     settings, 'DISCORD_BOT_ESS_PING_CHANNEL_ID', None)
 
 DISCORD_BOT_SEND_FAILURE_MESSAGES = getattr(
     settings, 'DISCORD_BOT_SEND_FAILURE_MESSAGES', False)
 DISCORD_BOT_FAILURE_MESSAGES_CHANNEL = getattr(
```

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/auth_hooks.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/auth_hooks.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/bot.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/bot.py`

 * *Files 1% similar despite different names*

```diff
@@ -75,16 +75,17 @@
 
 
 class RateLimiter:
     def __init__(self):
         self.rate_buckets = {}
 
     def bucket_for_task(self, task):
-        limit = rate(app_settings.DISCORD_BOT_TASK_RATE_LIMITS.get(task, None))
-        return TokenBucket(limit, capacity=1) if limit else None
+        limit = rate(
+            app_settings.DISCORD_BOT_TASK_RATE_LIMITS.get(task, "100/s"))
+        return TokenBucket(limit, capacity=1)
 
     def check_rate_limit(self, task):
         if task not in self.rate_buckets:
             self.rate_buckets[task] = self.bucket_for_task(task)
         #logger.debug(f" {self.rate_buckets[task].capacity} {self.rate_buckets[task].fill_rate} {self.rate_buckets[task].expected_time()}")
         return self.rate_buckets[task].can_consume()
```

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/bot_tasks.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/bot_tasks.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,22 +1,25 @@
 import importlib
 import logging
 import warnings
 from datetime import timedelta
 
-from discord import Embed
+from discord import Embed, Member
 from discord.ext import tasks
 from discord.ext.commands import Bot
 from discord.ui import View
 
 import django
+from django.conf import settings
 from django.utils import timezone
 
 logger = logging.getLogger(__name__)
 
+GUILD_ID = settings.DISCORD_GUILD_ID
+
 
 @tasks.loop()
 async def run_tasks(bot: Bot):
     django.db.close_old_connections()
 
     if len(bot.tasks) > 0:
         task, args, kwargs = bot.tasks.pop(0)
@@ -34,15 +37,16 @@
             try:
                 await task(bot, *args, **kwargs)
                 bot.statistics.add_task(task.__name__)
                 bot.dispatch("authbot_task_completed", task.__name__)
             except Exception as e:
                 bot.dispatch("authbot_task_failed",
                              task.__name__, args, kwargs, e)
-                logger.error(f"Failed to run task {task} {args} {kwargs} {e}")
+                logger.error(
+                    f"Failed to run task {task} {args} {kwargs} {e}", exc_info=True)
     else:
         run_tasks.stop()
     django.db.close_old_connections()
 
 
 async def send_channel_message_by_discord_id(bot, channel_id, message, embed=False, view_class=False, view_args=[], view_kwargs={}):
     logger.debug(f"Sending Channel Message to Discord ID {channel_id}")
@@ -99,7 +103,17 @@
         if embed:
             e = Embed.from_dict(embed)
             await channel.send(message, embed=e)
         else:
             await channel.send(message)
     else:
         logger.debug(f"No discord account on record for user_pk={user_pk}")
+
+
+async def pop_user_group_cache(bot, user_pk):
+    logger.debug(f"Refreshing user cache {user_pk}")
+    user = bot.get_guild(int(GUILD_ID)).get_member(user_pk)
+    r = user.roles[-1]
+    await user.remove_roles(r)
+    await user.add_roles(r)
+    logger.info(
+        f"Removed and added '{r}' to {user} to try and bust the invalid cache")
```

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/about.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/about.py`

 * *Files 5% similar despite different names*

```diff
@@ -46,15 +46,15 @@
         )
         members = 0
         for g in self.bot.guilds:
             members += g.member_count
         embed.add_field(name="Unwilling Monitorees:",
                         value=members, inline=True)
         embed.add_field(
-            name="Auth Link", value=f"[{get_site_url()}]({get_site_url()})", inline=False
+            name="Auth Link", value=get_site_url(), inline=False
         )
         embed.add_field(
             name="Version", value=f"{__version__}@{__branch__}", inline=False
         )
 
         return await ctx.respond(embed=embed)
 
@@ -86,15 +86,15 @@
                         value=channels-cats, inline=True)
 
         roles = len(ctx.guild.roles)
         embed.add_field(name="Role Count:",
                         value=roles, inline=True)
 
         embed.add_field(
-            name="Auth Link", value=f"[{get_site_url()}]({get_site_url()})", inline=False
+            name="Auth Link", value=get_site_url(), inline=False
         )
 
         return await ctx.respond(embed=embed)
 
 
 def setup(bot):
     bot.add_cog(About(bot))
```

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/abuse.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/abuse.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/admin.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/admin.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/auth.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/auth.py`

 * *Files 1% similar despite different names*

```diff
@@ -39,15 +39,15 @@
         embed.colour = Color.blue()
 
         embed.description = "All Authentication functions for this Discord server are handled through our Alliance Auth install"
 
         url = get_site_url()
 
         embed.add_field(
-            name="Auth Link", value=f"[{url}]({url})", inline=False
+            name="Auth Link", value=url, inline=False
         )
 
         return await ctx.send(embed=embed)
 
     @commands.slash_command(name='auth', guild_ids=[int(settings.DISCORD_GUILD_ID)])
     async def auth_slash(self, ctx):
         """
@@ -61,15 +61,15 @@
         embed.colour = Color.blue()
 
         embed.description = "All Authentication functions for this Discord server are handled through our Alliance Auth install"
 
         url = get_site_url()
 
         embed.add_field(
-            name="Auth Link", value=f"[{url}]({url})", inline=False
+            name="Auth Link", value=url, inline=False
         )
         """
         embed.add_field(
             name="Number of Servers:", value=len(self.bot.guilds), inline=True
         )
         embed.add_field(name="Unwilling Monitorees:",
                         value=len(self.bot.users), inline=True)
```

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/eastereggs.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/eastereggs.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/eightball.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/eightball.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/facwar.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/facwar.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/members.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/members.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/models.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/models.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/price_check.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/price_check.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/prom_export.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/prom_export.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/quote.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/quote.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/reaction_roles.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/reaction_roles.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/remind.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/remind.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/services.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/services.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/sov.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/sov.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/time.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/time.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/timers.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/timers.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/utils/decorators.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/utils/decorators.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/cogs/welcomegoodbye.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/cogs/welcomegoodbye.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0001_initial.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0002_reactionrolebinding_reactionrolemessage.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0002_reactionrolebinding_reactionrolemessage.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0003_authbotconfiguration.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0003_authbotconfiguration.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0005_rr_fixes_blank_admins.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0005_rr_fixes_blank_admins.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0006_goodbyemessage_welcomemessage.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0006_goodbyemessage_welcomemessage.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/migrations/0007_quotemessage.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/migrations/0007_quotemessage.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/models.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/models.py`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/aadiscordbot/tasks.py` & `allianceauth-discordbot-3.6.2/aadiscordbot/tasks.py`

 * *Files 4% similar despite different names*

```diff
@@ -4,14 +4,16 @@
 from discord import Embed
 
 import django
 import django.db
 from django.conf import settings
 from django.contrib.auth.models import User
 
+from allianceauth.services.modules.discord.models import DiscordUser
+
 logger = logging.getLogger(__name__)
 
 
 def send_message(message="", channel_id: int = None, user_id: int = None, user: User = None, user_pk: User = None, embed: Embed = None, countdown: int = 0):
     ''' Helper function to queue discord messages from the bot
 
         :param message: (optional) The text to send (default "").
@@ -81,7 +83,13 @@
 
 
 @shared_task
 def send_direct_message_by_user_id(user_pk, message_content, embed=False):
     # Queue a Private Message to a specific user
     raise Exception(
         f"This function should be called asynchronously. Failed to queue a message to User {user_pk}")
+
+
+@shared_task
+def pop_user_group_cache(user_pk):
+    raise Exception(
+        f"This function should be called asynchronously. Failed to queue...")
```

### Comparing `allianceauth-discordbot-3.6.1/allianceauth_discordbot.egg-info/PKG-INFO` & `allianceauth-discordbot-3.6.2/allianceauth_discordbot.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: allianceauth-discordbot
-Version: 3.6.1
+Version: 3.6.2
 Summary: Alliance Auth Discord Bot
 Home-page: https://github.com/pvyParts/allianceauth-discordbot
 Author: ak
 Author-email: ak@ak.auth
 License: GNU General Public License v3 (GPLv3)
 Platform: UNKNOWN
 Classifier: Environment :: Web Environment
```

### Comparing `allianceauth-discordbot-3.6.1/allianceauth_discordbot.egg-info/SOURCES.txt` & `allianceauth-discordbot-3.6.2/allianceauth_discordbot.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `allianceauth-discordbot-3.6.1/setup.py` & `allianceauth-discordbot-3.6.2/setup.py`

 * *Files identical despite different names*

