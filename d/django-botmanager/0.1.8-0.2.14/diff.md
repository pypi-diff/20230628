# Comparing `tmp/django-botmanager-0.1.8.tar.gz` & `tmp/django-botmanager-0.2.14.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/django-botmanager-0.1.8.tar", last modified: Wed Nov 11 13:47:06 2020, max compression
+gzip compressed data, was "django-botmanager-0.2.14.tar", last modified: Wed Jun 28 11:25:20 2023, max compression
```

## Comparing `django-botmanager-0.1.8.tar` & `django-botmanager-0.2.14.tar`

### file list

```diff
@@ -1,36 +1,38 @@
-drwxrwxr-x   0 titov     (1000) titov     (1000)        0 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/
-drwxrwxr-x   0 titov     (1000) titov     (1000)        0 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/django_botmanager.egg-info/
--rw-rw-r--   0 titov     (1000) titov     (1000)      994 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/django_botmanager.egg-info/SOURCES.txt
--rw-rw-r--   0 titov     (1000) titov     (1000)      256 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/django_botmanager.egg-info/PKG-INFO
--rw-rw-r--   0 titov     (1000) titov     (1000)       11 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/django_botmanager.egg-info/top_level.txt
--rw-rw-r--   0 titov     (1000) titov     (1000)       38 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/django_botmanager.egg-info/requires.txt
--rw-rw-r--   0 titov     (1000) titov     (1000)        1 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/django_botmanager.egg-info/dependency_links.txt
--rw-rw-r--   0 titov     (1000) titov     (1000)      256 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/PKG-INFO
--rw-rw-r--   0 titov     (1000) titov     (1000)       38 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/setup.cfg
-drwxrwxr-x   0 titov     (1000) titov     (1000)        0 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/botmanager/
--rw-rw-r--   0 titov     (1000) titov     (1000)     7691 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/basetask.py
--rw-rw-r--   0 titov     (1000) titov     (1000)      135 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/apps.py
-drwxrwxr-x   0 titov     (1000) titov     (1000)        0 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/botmanager/migrations/
--rw-rw-r--   0 titov     (1000) titov     (1000)      712 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/migrations/0005_task_parent.py
--rw-rw-r--   0 titov     (1000) titov     (1000)     1935 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/migrations/0003_auto_20161208_1529.py
--rw-rw-r--   0 titov     (1000) titov     (1000)      489 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/migrations/0009_task_extra_params.py
--rw-rw-r--   0 titov     (1000) titov     (1000)      673 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/migrations/0008_auto_20170331_1752.py
--rw-rw-r--   0 titov     (1000) titov     (1000)      448 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/migrations/0006_task_priority.py
--rw-rw-r--   0 titov     (1000) titov     (1000)     2880 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/migrations/0004_auto_20161219_1931.py
--rw-rw-r--   0 titov     (1000) titov     (1000)      653 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/migrations/0010_auto_20170531_1321.py
--rw-rw-r--   0 titov     (1000) titov     (1000)      742 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/migrations/0002_auto_20161208_1406.py
--rw-rw-r--   0 titov     (1000) titov     (1000)     3357 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/migrations/0001_initial.py
--rw-rw-r--   0 titov     (1000) titov     (1000)      667 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/migrations/0007_task_is_persistent.py
--rw-rw-r--   0 titov     (1000) titov     (1000)        0 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/migrations/__init__.py
--rw-rw-r--   0 titov     (1000) titov     (1000)     3557 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/models.py
--rw-rw-r--   0 titov     (1000) titov     (1000)      653 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/utils.py
-drwxrwxr-x   0 titov     (1000) titov     (1000)        0 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/botmanager/management/
-drwxrwxr-x   0 titov     (1000) titov     (1000)        0 2020-11-11 13:47:06.000000 django-botmanager-0.1.8/botmanager/management/commands/
--rw-rw-r--   0 titov     (1000) titov     (1000)    15575 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/management/commands/bot_manager.py
--rw-rw-r--   0 titov     (1000) titov     (1000)      542 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/management/commands/__init__.py
--rw-rw-r--   0 titov     (1000) titov     (1000)        0 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/management/__init__.py
--rw-rw-r--   0 titov     (1000) titov     (1000)     3184 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/settings.py
--rw-rw-r--   0 titov     (1000) titov     (1000)       73 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/__init__.py
--rw-rw-r--   0 titov     (1000) titov     (1000)     1482 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/botmanager/admin.py
--rw-rw-r--   0 titov     (1000) titov     (1000)      562 2020-11-11 13:45:11.000000 django-botmanager-0.1.8/README.md
--rw-rw-r--   0 titov     (1000) titov     (1000)      406 2020-11-11 13:46:43.000000 django-botmanager-0.1.8/setup.py
+drwxrwxr-x   0 titov     (1000) titov     (1000)        0 2023-06-28 11:25:20.145034 django-botmanager-0.2.14/
+-rw-rw-r--   0 titov     (1000) titov     (1000)     1479 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/LICENSE
+-rw-rw-r--   0 titov     (1000) titov     (1000)      223 2023-06-28 11:25:20.145034 django-botmanager-0.2.14/PKG-INFO
+-rw-rw-r--   0 titov     (1000) titov     (1000)      562 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/README.md
+drwxrwxr-x   0 titov     (1000) titov     (1000)        0 2023-06-28 11:25:20.141034 django-botmanager-0.2.14/botmanager/
+-rw-rw-r--   0 titov     (1000) titov     (1000)       73 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/__init__.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)     1482 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/admin.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)      135 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/apps.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)     7829 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/basetask.py
+drwxrwxr-x   0 titov     (1000) titov     (1000)        0 2023-06-28 11:25:20.141034 django-botmanager-0.2.14/botmanager/management/
+-rw-rw-r--   0 titov     (1000) titov     (1000)        0 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/management/__init__.py
+drwxrwxr-x   0 titov     (1000) titov     (1000)        0 2023-06-28 11:25:20.141034 django-botmanager-0.2.14/botmanager/management/commands/
+-rw-rw-r--   0 titov     (1000) titov     (1000)      542 2023-06-28 11:16:25.000000 django-botmanager-0.2.14/botmanager/management/commands/__init__.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)    18210 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/management/commands/bot_manager.py
+drwxrwxr-x   0 titov     (1000) titov     (1000)        0 2023-06-28 11:25:20.141034 django-botmanager-0.2.14/botmanager/migrations/
+-rw-rw-r--   0 titov     (1000) titov     (1000)     3357 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/migrations/0001_initial.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)      742 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/migrations/0002_auto_20161208_1406.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)     1935 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/migrations/0003_auto_20161208_1529.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)     2880 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/migrations/0004_auto_20161219_1931.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)      712 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/migrations/0005_task_parent.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)      448 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/migrations/0006_task_priority.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)      667 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/migrations/0007_task_is_persistent.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)      673 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/migrations/0008_auto_20170331_1752.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)      489 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/migrations/0009_task_extra_params.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)      653 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/migrations/0010_auto_20170531_1321.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)      706 2023-06-28 11:19:02.000000 django-botmanager-0.2.14/botmanager/migrations/0011_alter_task_create_dt_alter_task_id.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)        0 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/migrations/__init__.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)     3665 2023-06-28 11:18:48.000000 django-botmanager-0.2.14/botmanager/models.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)     3266 2023-06-28 11:15:43.000000 django-botmanager-0.2.14/botmanager/settings.py
+-rw-rw-r--   0 titov     (1000) titov     (1000)     1105 2023-06-28 10:28:59.000000 django-botmanager-0.2.14/botmanager/utils.py
+drwxrwxr-x   0 titov     (1000) titov     (1000)        0 2023-06-28 11:25:20.145034 django-botmanager-0.2.14/django_botmanager.egg-info/
+-rw-rw-r--   0 titov     (1000) titov     (1000)      223 2023-06-28 11:25:20.000000 django-botmanager-0.2.14/django_botmanager.egg-info/PKG-INFO
+-rw-rw-r--   0 titov     (1000) titov     (1000)     1067 2023-06-28 11:25:20.000000 django-botmanager-0.2.14/django_botmanager.egg-info/SOURCES.txt
+-rw-rw-r--   0 titov     (1000) titov     (1000)        1 2023-06-28 11:25:20.000000 django-botmanager-0.2.14/django_botmanager.egg-info/dependency_links.txt
+-rw-rw-r--   0 titov     (1000) titov     (1000)       52 2023-06-28 11:25:20.000000 django-botmanager-0.2.14/django_botmanager.egg-info/requires.txt
+-rw-rw-r--   0 titov     (1000) titov     (1000)       11 2023-06-28 11:25:20.000000 django-botmanager-0.2.14/django_botmanager.egg-info/top_level.txt
+-rw-rw-r--   0 titov     (1000) titov     (1000)       38 2023-06-28 11:25:20.145034 django-botmanager-0.2.14/setup.cfg
+-rw-rw-r--   0 titov     (1000) titov     (1000)      432 2023-06-28 10:59:06.000000 django-botmanager-0.2.14/setup.py
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `django-botmanager-0.1.8/django_botmanager.egg-info/SOURCES.txt` & `django-botmanager-0.2.14/django_botmanager.egg-info/SOURCES.txt`

 * *Files 2% similar despite different names*

```diff
@@ -1,7 +1,8 @@
+LICENSE
 README.md
 setup.py
 botmanager/__init__.py
 botmanager/admin.py
 botmanager/apps.py
 botmanager/basetask.py
 botmanager/models.py
@@ -16,13 +17,14 @@
 botmanager/migrations/0004_auto_20161219_1931.py
 botmanager/migrations/0005_task_parent.py
 botmanager/migrations/0006_task_priority.py
 botmanager/migrations/0007_task_is_persistent.py
 botmanager/migrations/0008_auto_20170331_1752.py
 botmanager/migrations/0009_task_extra_params.py
 botmanager/migrations/0010_auto_20170531_1321.py
+botmanager/migrations/0011_alter_task_create_dt_alter_task_id.py
 botmanager/migrations/__init__.py
 django_botmanager.egg-info/PKG-INFO
 django_botmanager.egg-info/SOURCES.txt
 django_botmanager.egg-info/dependency_links.txt
 django_botmanager.egg-info/requires.txt
 django_botmanager.egg-info/top_level.txt
```

### Comparing `django-botmanager-0.1.8/botmanager/basetask.py` & `django-botmanager-0.2.14/botmanager/basetask.py`

 * *Files 2% similar despite different names*

```diff
@@ -17,14 +17,18 @@
 LOGGING = settings.TASKS_LOGGING
 
 
 class StopTaskSuccess(BotManagerTaskError):
     pass
 
 
+class TaskTemporarilyException(BotManagerTaskError):
+    pass
+
+
 class BotManagerBaseTask(object):
 
     actions = []
     name = 'unknown'
     DEFAULT_ATTEMPT_PERIOD = 1
     SELF_SUPPORT = True
 
@@ -186,15 +190,18 @@
                 try:
                     action_method()
                     logging.info(u'End action {}. id {}'.format(action, self.task.pk))
                 except StopTaskSuccess:
                     logging.info(u'Stop actions because StopTaskSuccess caught')
                     break
                 except Exception as e:
-                    logging.exception(e)
+
+                    if not isinstance(e, TaskTemporarilyException):
+                        logging.exception(e)
+
                     self.task.failed_action = action
                     is_error_handled = self._handle_error(e)
                     self.task.last_error_dt = timezone.now()
                     self.task.last_error = {
                         'error': str(e),
                         'trace': traceback.format_exc(),
                     }
```

### Comparing `django-botmanager-0.1.8/botmanager/migrations/0005_task_parent.py` & `django-botmanager-0.2.14/botmanager/migrations/0005_task_parent.py`

 * *Files identical despite different names*

### Comparing `django-botmanager-0.1.8/botmanager/migrations/0003_auto_20161208_1529.py` & `django-botmanager-0.2.14/botmanager/migrations/0003_auto_20161208_1529.py`

 * *Files identical despite different names*

### Comparing `django-botmanager-0.1.8/botmanager/migrations/0008_auto_20170331_1752.py` & `django-botmanager-0.2.14/botmanager/migrations/0008_auto_20170331_1752.py`

 * *Files identical despite different names*

### Comparing `django-botmanager-0.1.8/botmanager/migrations/0004_auto_20161219_1931.py` & `django-botmanager-0.2.14/botmanager/migrations/0004_auto_20161219_1931.py`

 * *Files identical despite different names*

### Comparing `django-botmanager-0.1.8/botmanager/migrations/0010_auto_20170531_1321.py` & `django-botmanager-0.2.14/botmanager/migrations/0010_auto_20170531_1321.py`

 * *Files identical despite different names*

### Comparing `django-botmanager-0.1.8/botmanager/migrations/0002_auto_20161208_1406.py` & `django-botmanager-0.2.14/botmanager/migrations/0002_auto_20161208_1406.py`

 * *Files identical despite different names*

### Comparing `django-botmanager-0.1.8/botmanager/migrations/0001_initial.py` & `django-botmanager-0.2.14/botmanager/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `django-botmanager-0.1.8/botmanager/migrations/0007_task_is_persistent.py` & `django-botmanager-0.2.14/botmanager/migrations/0007_task_is_persistent.py`

 * *Files identical despite different names*

### Comparing `django-botmanager-0.1.8/botmanager/models.py` & `django-botmanager-0.2.14/botmanager/models.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,50 +1,50 @@
 # -*- coding: utf-8 -*-
 from __future__ import unicode_literals
 from django.db import models
 from jsonfield import JSONField
 from datetime import timedelta, datetime
 from django.utils import timezone
-
+from django.utils.translation import gettext_lazy as _
 
 class Task(models.Model):
 
     STATUS_NEW = 'NEW'
     STATUS_IN_PROCESS = 'IN_PROCESS'
     STATUS_OK = 'OK'
 
     STATUSES = (
         (STATUS_NEW, u'В ожидании'),
         (STATUS_IN_PROCESS, u'Идет загрузка'),
         (STATUS_OK, u'Данные загружены'),
     )
 
-    name = models.CharField(max_length=256, verbose_name=u'Название')
-    create_dt = models.DateTimeField(verbose_name=u"Дата создания задачи", auto_now_add=True)
-    finish_dt = models.DateTimeField(verbose_name=u"Дата завершения", null=True, blank=True)
-    is_complete = models.BooleanField(verbose_name=u"Выполнена", default=False)
-    is_failed = models.BooleanField(verbose_name=u"Аварийное завершение", default=False)
-    is_persistent = models.BooleanField(verbose_name=u"Выполнять пока не завершится успешно", default=True)
-    in_process = models.BooleanField(verbose_name=u"В процессе", default=False)
+    name = models.CharField(max_length=256, verbose_name=_(u'Название'))
+    create_dt = models.DateTimeField(verbose_name=_(u"Дата создания задачи"), default=timezone.now)
+    finish_dt = models.DateTimeField(verbose_name=_(u"Дата завершения"), null=True, blank=True)
+    is_complete = models.BooleanField(verbose_name=_(u"Выполнена"), default=False)
+    is_failed = models.BooleanField(verbose_name=_(u"Аварийное завершение"), default=False)
+    is_persistent = models.BooleanField(verbose_name=_(u"Выполнять пока не завершится успешно"), default=True)
+    in_process = models.BooleanField(verbose_name=_(u"В процессе"), default=False)
 
     input = JSONField(null=True, blank=True)
     output = JSONField(null=True, blank=True)
     last_error = JSONField(null=True, blank=True)
     extra_params = JSONField(null=True, blank=True)
 
-    last_error_dt = models.DateTimeField(verbose_name=u"Дата последнего fail-а", null=True, blank=True)
-    queue_key = models.CharField(max_length=32, verbose_name=u'Ключ группировки задач')
-    failed_action = models.CharField(max_length=256, verbose_name=u'Action, на котором произошла ошибка', null=True, blank=True)
-    attempt_count = models.SmallIntegerField(verbose_name=u'Счетчик попыток', default=0)
-    last_attempt_dt = models.DateTimeField(verbose_name=u"Последняя попытка выполнения", null=True, blank=True)
+    last_error_dt = models.DateTimeField(verbose_name=_(u"Дата последнего fail-а"), null=True, blank=True)
+    queue_key = models.CharField(max_length=32, verbose_name=_(u'Ключ группировки задач'))
+    failed_action = models.CharField(max_length=256, verbose_name=_(u'Action, на котором произошла ошибка'), null=True, blank=True)
+    attempt_count = models.SmallIntegerField(verbose_name=_(u'Счетчик попыток'), default=0)
+    last_attempt_dt = models.DateTimeField(verbose_name=_(u"Последняя попытка выполнения"), null=True, blank=True)
     max_attempt_count = models.IntegerField(
-        verbose_name=u"Максимальное кол-во попыток выполнение (если None, то бесконечно)", null=True, blank=True
+        verbose_name=_(u"Максимальное кол-во попыток выполнение (если None, то бесконечно)"), null=True, blank=True
     )
-    attempt_period = models.DurationField(verbose_name=u'Период между попытками', default=timedelta(hours=1))
-    parent = models.ForeignKey('self', verbose_name=u'Родительская задача', null=True, blank=True, related_name='child_tasks', on_delete=models.CASCADE)
+    attempt_period = models.DurationField(verbose_name=_(u'Период между попытками'), default=timedelta(hours=1))
+    parent = models.ForeignKey('self', verbose_name=_(u'Родительская задача'), null=True, blank=True, related_name='child_tasks', on_delete=models.CASCADE)
     priority = models.SmallIntegerField(default=0)
 
     def __unicode__(self):
         return "Task {0} #{1}".format(self.name, self.id)
 
     @property
     def can_execute(self):
@@ -63,9 +63,9 @@
             else:
                 return True
         else:
             return False
 
     class Meta:
         db_table = 'botmanager_task'
-        verbose_name = u"Задача для BotManager"
-        verbose_name_plural = u"Задачи для BotManager"
+        verbose_name = _(u"Задача для BotManager")
+        verbose_name_plural = _(u"Задачи для BotManager")
```

### Comparing `django-botmanager-0.1.8/botmanager/management/commands/bot_manager.py` & `django-botmanager-0.2.14/botmanager/management/commands/bot_manager.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,25 +1,27 @@
 # -*- coding: utf-8 -*-
 import importlib
+import json
 import logging
 import os
 import sys
 from datetime import datetime, timedelta
 from multiprocessing import Queue, Process
 from time import sleep, time
 
+import psutil
 import six
-from django.db import connections
+from django.db import connections, transaction, connection
 from django.db.models import Q
 from django.utils import timezone
 
 from botmanager import settings
 from botmanager.management.commands import BotManagerBaseCommand, BotManagerBaseCommandException
 from botmanager.models import Task
-from botmanager.utils import management_lock
+from botmanager.utils import management_lock, lock_task
 
 if six.PY2:
     from Queue import Empty as QueueEmpty
 else:
     from queue import Empty as QueueEmpty
 
 try:
@@ -129,15 +131,20 @@
     def run(self, *args, **options):
 
         self.set_logging()
 
         logging.info(u"Starting BotManager")
         setproctitle(u"BotManager.General")
 
+        if PidsFileController.check_running_processes():
+            logging.info(u"BotManager is stopped. A running process was found")
+            return
+
         current_pid = os.getpid()
+        PidsFileController.add_pid(current_pid)
 
         processes = []
         queue_dict = {}
         for task_class_string, processes_count in self.config['tasks'].items():
             cls_name = task_class_string.split('.')[-1]
             if options['task_cls'] and cls_name != options['task_cls']:
                 logging.info('Continue task class {}'.format(cls_name))
@@ -153,29 +160,32 @@
             for i in range(processes_count):
                 tm = TaskManager(task_class, queue_dict[task_class.name], i + 1, current_pid)
                 p = Process(target=Command.start_service, args=(tm,))
                 p.name = tm.process_name
                 p.daemon = True
                 p.start()
                 processes.append(p)
+                PidsFileController.add_pid(p.pid)
 
         tf = TaskFetcher(queue_dict, current_pid)
         p = Process(target=Command.start_service, args=(tf,))
         p.name = tf.process_name
         p.daemon = True
         p.start()
         processes.append(p)
+        PidsFileController.add_pid(p.pid)
 
         if not options.get('without_sheduller'):
             ts = TaskSheduler(self.config, current_pid)
             p = Process(target=Command.start_service, args=(ts,))
             p.name = ts.process_name
             p.daemon = True
             p.start()
             processes.append(p)
+            PidsFileController.add_pid(p.pid)
 
         next_clean_logs_dt = next_clean_tasks_dt = datetime.now() + timedelta(seconds=10)
         logs_life_hours = self.config['logs']['logs_life_hours']
         tasks_life_hours = self.config['logs']['success_tasks_life_hours']
         need_remove_logs = self.config['logs']['task_logs_separated'] and logs_life_hours is not None
         need_remove_tasks = tasks_life_hours is not None
 
@@ -375,7 +385,77 @@
                     pass
             except QueueEmpty:
                 sleep(1)
             except Exception as e:
                 logging.exception(
                     u"Error in queue preparing: %s".format(e)
                 )
+
+
+class PidsFileController(object):
+    def __init__(self):
+        pass
+
+    @classmethod
+    def get_pids_filename(cls):
+        from django.conf import settings
+
+        if not settings.BASE_DIR:
+            raise BotManagerCommandException(u"settings.BASE_DIR is empty")
+
+        if not os.path.exists(settings.BASE_DIR):
+            raise BotManagerCommandException(u"settings.BASE_DIR not exists")
+
+        return os.path.join(settings.BASE_DIR, 'botmanager.pids')
+
+    @classmethod
+    def get_process_create_time(cls, pid):
+        try:
+            p = psutil.Process(pid)
+            return p.create_time()
+        except psutil.NoSuchProcess:
+            return
+
+    @classmethod
+    def add_pid(cls, pid):
+        create_time = cls.get_process_create_time(pid)
+        if not create_time:
+            return
+
+        with open(cls.get_pids_filename(), 'a+') as f:
+            f.write('{}\n'.format(json.dumps({'pid': pid, 'create_time': create_time})))
+
+    @classmethod
+    def check_running_processes(cls):
+        logging.info(u"Start check_running_processes")
+
+        pids_file_name = cls.get_pids_filename()
+        if not os.path.exists(pids_file_name):
+            return
+
+        with open(pids_file_name) as f:
+            for line in f:
+                line = line.strip()
+                if not line:
+                    continue
+                process = json.loads(line)
+                logging.info(u"\tchecking process: {}".format(process))
+
+                create_time = cls.get_process_create_time(process['pid'])
+                if not create_time:
+                    logging.info(u"\tprocess: {} is not running".format(process))
+                    continue
+
+                if create_time != process['create_time']:
+                    logging.info(
+                        u"\tprocess: {} is not running, process create_time={} != saved create_time={}".format(
+                            process, create_time, process['create_time']
+                        )
+                    )
+                    continue
+
+                logging.info('\tprocess: {} is running'.format(process))
+                return True
+
+        if os.path.exists(pids_file_name):
+            os.remove(pids_file_name)
+
```

### Comparing `django-botmanager-0.1.8/botmanager/management/commands/__init__.py` & `django-botmanager-0.2.14/botmanager/management/commands/__init__.py`

 * *Files identical despite different names*

### Comparing `django-botmanager-0.1.8/botmanager/settings.py` & `django-botmanager-0.2.14/botmanager/settings.py`

 * *Files 5% similar despite different names*

```diff
@@ -12,81 +12,89 @@
     MAIN_CONFIG['logs'] = {}
 if 'tasks' not in MAIN_CONFIG:
     MAIN_CONFIG['tasks'] = []
 
 if 'task_logs_separated' not in MAIN_CONFIG['logs']:
     MAIN_CONFIG['logs']['task_logs_separated'] = False
 if MAIN_CONFIG['logs']['task_logs_separated'] and 'logs_life_hours' not in MAIN_CONFIG['logs']:
-    MAIN_CONFIG['logs']['logs_life_hours'] = 7*24
+    MAIN_CONFIG['logs']['logs_life_hours'] = 7 * 24
 if 'success_tasks_life_hours' not in MAIN_CONFIG['logs']:
-    MAIN_CONFIG['logs']['success_tasks_life_hours'] = 7*24
+    MAIN_CONFIG['logs']['success_tasks_life_hours'] = 7 * 24
 
 DEFAULT_LOG_LEVEL = 'INFO'
 
 if 'dir' in MAIN_CONFIG['logs'] and MAIN_CONFIG['logs']['dir'] is not None:
 
     log_conf = MAIN_CONFIG['logs']
-    max_bytes = log_conf['maxBytes'] if 'maxBytes' in log_conf and log_conf['maxBytes'] else 1024*1024*100
+    max_bytes = log_conf['maxBytes'] if 'maxBytes' in log_conf and log_conf['maxBytes'] else 1024 * 1024 * 100
     backupCount = log_conf['backupCount'] if 'backupCount' in log_conf and log_conf['backupCount'] else 10
     level = log_conf['level'] if 'level' in log_conf and log_conf['level'] else DEFAULT_LOG_LEVEL
     sentry_enabled = log_conf.get('sentry_enabled', False)
 
     handlers = ['console', 'common_errors', 'common']
 
+    handlers_config = {
+        'mail_admins': {
+            'level': 'ERROR',
+            'class': 'django.utils.log.AdminEmailHandler',
+        },
+        'console': {
+            'level': level,
+            'class': 'logging.StreamHandler',
+            'formatter': 'default',
+            'stream': sys.stdout
+        },
+        'common_errors': {
+            'level': 'ERROR',
+            'class': 'logging.handlers.RotatingFileHandler',
+            'filename': os.path.join(log_conf['dir'], 'botmanager_errors.log'),
+            'maxBytes': max_bytes,
+            'formatter': 'default',
+            'encoding': 'utf-8',
+            'backupCount': backupCount,
+        },
+        'common': {
+            'level': level,
+            'class': 'logging.handlers.RotatingFileHandler',
+            'filename': os.path.join(log_conf['dir'], 'botmanager.log'),
+            'maxBytes': max_bytes,
+            'formatter': 'default',
+            'encoding': 'utf-8',
+            'backupCount': backupCount,
+        }
+    }
+
     if sentry_enabled:
-        handlers.append('sentry')
+        try:
+            import raven
+
+            handlers.append('sentry')
+            handlers_config['sentry'] = {
+                'level': 'ERROR',
+                'class': 'raven.contrib.django.raven_compat.handlers.SentryHandler',
+            }
+        except ImportError:
+            raise ImportError('module "raven" not installed')
 
     if 'mail_admins' in log_conf and log_conf['mail_admins']:
         handlers.append('mail_admins')
 
     TASKS_LOGGING = {
         'version': 1,
         'disable_existing_loggers': True,
         'formatters': {
             'default': {
                 'format': '%(asctime)s - %(processName)s - %(levelname)s - %(message)s'
             }
         },
-        'handlers': {
-            'sentry': {
-                'level': 'ERROR',
-                'class': 'raven.contrib.django.raven_compat.handlers.SentryHandler',
-            },
-            'mail_admins': {
-                'level': 'ERROR',
-                'class': 'django.utils.log.AdminEmailHandler',
-            },
-            'console': {
-                'level': level,
-                'class': 'logging.StreamHandler',
-                'formatter': 'default',
-                'stream': sys.stdout
-            },
-            'common_errors': {
-                'level': 'ERROR',
-                'class': 'logging.handlers.RotatingFileHandler',
-                'filename': os.path.join(log_conf['dir'], 'botmanager_errors.log'),
-                'maxBytes': max_bytes,
-                'formatter': 'default',
-                'encoding': 'utf-8',
-                'backupCount': backupCount,
-            },
-            'common': {
-                'level': level,
-                'class': 'logging.handlers.RotatingFileHandler',
-                'filename': os.path.join(log_conf['dir'], 'botmanager.log'),
-                'maxBytes': max_bytes,
-                'formatter': 'default',
-                'encoding': 'utf-8',
-                'backupCount': backupCount,
-            }
-        },
+        'handlers': handlers_config,
         'loggers': {
             'default': {
                 'handlers': handlers,
                 'level': level,
                 'propagate': False
             },
         }
     }
+
 else:
     TASKS_LOGGING = None
```

### Comparing `django-botmanager-0.1.8/botmanager/admin.py` & `django-botmanager-0.2.14/botmanager/admin.py`

 * *Files identical despite different names*

### Comparing `django-botmanager-0.1.8/README.md` & `django-botmanager-0.2.14/README.md`

 * *Files identical despite different names*

