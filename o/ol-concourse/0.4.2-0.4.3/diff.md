# Comparing `tmp/ol-concourse-0.4.2.tar.gz` & `tmp/ol-concourse-0.4.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ol-concourse-0.4.2.tar", last modified: Tue Jun 20 18:39:17 2023, max compression
+gzip compressed data, was "ol-concourse-0.4.3.tar", last modified: Wed Jun 28 14:40:31 2023, max compression
```

## Comparing `ol-concourse-0.4.2.tar` & `ol-concourse-0.4.3.tar`

### file list

```diff
@@ -1,30 +1,30 @@
-drwxr-xr-x   0 tmacey    (1000) tmacey    (1000)        0 2023-06-20 18:39:17.930781 ol-concourse-0.4.2/
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)       12 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/MANIFEST.in
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)       79 2023-06-20 18:39:17.930781 ol-concourse-0.4.2/PKG-INFO
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)      762 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/backend_shim.py
-drwxr-xr-x   0 tmacey    (1000) tmacey    (1000)        0 2023-06-20 18:39:17.927447 ol-concourse-0.4.2/ol_concourse/
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)        0 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/__init__.py
-drwxr-xr-x   0 tmacey    (1000) tmacey    (1000)        0 2023-06-20 18:39:17.930781 ol-concourse-0.4.2/ol_concourse/lib/
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)        0 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/lib/__init__.py
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)       34 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/lib/constants.py
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)     1038 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/lib/containers.py
-drwxr-xr-x   0 tmacey    (1000) tmacey    (1000)        0 2023-06-20 18:39:17.930781 ol-concourse-0.4.2/ol_concourse/lib/jobs/
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)    11721 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/lib/jobs/infrastructure.py
-drwxr-xr-x   0 tmacey    (1000) tmacey    (1000)        0 2023-06-20 18:39:17.930781 ol-concourse-0.4.2/ol_concourse/lib/models/
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)        0 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/lib/models/__init__.py
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)     3678 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/lib/models/fragment.py
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)   106719 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/lib/models/pipeline.py
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)      303 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/lib/models/resource.py
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)     1191 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/lib/notifications.py
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)     2088 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/lib/resource_types.py
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)     4073 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/lib/resources.py
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)     3199 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse/lib/tasks.py
-drwxr-xr-x   0 tmacey    (1000) tmacey    (1000)        0 2023-06-20 18:39:17.930781 ol-concourse-0.4.2/ol_concourse.egg-info/
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)       79 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse.egg-info/PKG-INFO
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)      684 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse.egg-info/SOURCES.txt
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)        1 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse.egg-info/dependency_links.txt
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)        1 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse.egg-info/namespace_packages.txt
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)       19 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse.egg-info/requires.txt
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)       13 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/ol_concourse.egg-info/top_level.txt
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)       38 2023-06-20 18:39:17.930781 ol-concourse-0.4.2/setup.cfg
--rw-r--r--   0 tmacey    (1000) tmacey    (1000)      491 2023-06-20 18:39:17.000000 ol-concourse-0.4.2/setup.py
+drwxr-xr-x   0 tmacey    (1000) tmacey    (1000)        0 2023-06-28 14:40:31.741640 ol-concourse-0.4.3/
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)       12 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/MANIFEST.in
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)       79 2023-06-28 14:40:31.741640 ol-concourse-0.4.3/PKG-INFO
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)      762 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/backend_shim.py
+drwxr-xr-x   0 tmacey    (1000) tmacey    (1000)        0 2023-06-28 14:40:31.738307 ol-concourse-0.4.3/ol_concourse/
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)        0 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/__init__.py
+drwxr-xr-x   0 tmacey    (1000) tmacey    (1000)        0 2023-06-28 14:40:31.741640 ol-concourse-0.4.3/ol_concourse/lib/
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)        0 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/lib/__init__.py
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)       34 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/lib/constants.py
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)     1038 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/lib/containers.py
+drwxr-xr-x   0 tmacey    (1000) tmacey    (1000)        0 2023-06-28 14:40:31.741640 ol-concourse-0.4.3/ol_concourse/lib/jobs/
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)    11721 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/lib/jobs/infrastructure.py
+drwxr-xr-x   0 tmacey    (1000) tmacey    (1000)        0 2023-06-28 14:40:31.741640 ol-concourse-0.4.3/ol_concourse/lib/models/
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)        0 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/lib/models/__init__.py
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)     3678 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/lib/models/fragment.py
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)   107808 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/lib/models/pipeline.py
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)      303 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/lib/models/resource.py
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)     1191 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/lib/notifications.py
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)     2088 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/lib/resource_types.py
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)     4073 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/lib/resources.py
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)     3199 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse/lib/tasks.py
+drwxr-xr-x   0 tmacey    (1000) tmacey    (1000)        0 2023-06-28 14:40:31.741640 ol-concourse-0.4.3/ol_concourse.egg-info/
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)       79 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse.egg-info/PKG-INFO
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)      684 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse.egg-info/SOURCES.txt
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)        1 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse.egg-info/dependency_links.txt
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)        1 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse.egg-info/namespace_packages.txt
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)       19 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse.egg-info/requires.txt
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)       13 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/ol_concourse.egg-info/top_level.txt
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)       38 2023-06-28 14:40:31.741640 ol-concourse-0.4.3/setup.cfg
+-rw-r--r--   0 tmacey    (1000) tmacey    (1000)      491 2023-06-28 14:40:31.000000 ol-concourse-0.4.3/setup.py
```

### Comparing `ol-concourse-0.4.2/backend_shim.py` & `ol-concourse-0.4.3/backend_shim.py`

 * *Files identical despite different names*

### Comparing `ol-concourse-0.4.2/ol_concourse/lib/containers.py` & `ol-concourse-0.4.3/ol_concourse/lib/containers.py`

 * *Files identical despite different names*

### Comparing `ol-concourse-0.4.2/ol_concourse/lib/jobs/infrastructure.py` & `ol-concourse-0.4.3/ol_concourse/lib/jobs/infrastructure.py`

 * *Files identical despite different names*

### Comparing `ol-concourse-0.4.2/ol_concourse/lib/models/fragment.py` & `ol-concourse-0.4.3/ol_concourse/lib/models/fragment.py`

 * *Files identical despite different names*

### Comparing `ol-concourse-0.4.2/ol_concourse/lib/models/pipeline.py` & `ol-concourse-0.4.3/ol_concourse/lib/models/pipeline.py`

 * *Files 0% similar despite different names*

```diff
@@ -253,14 +253,49 @@
         "30 minutes.",
     )
     tags: Optional[list[str]] = Field(
         None,
         description="The tags by which to match workers. The step will be placed within"
         " the a pool of workers that match all of the given set of tags.",
     )
+    ensure: Optional[Step] = Field(
+        None,
+        description=(
+            "Step to execute regardless of whether the job succeeds, fails, errors, or "
+            " aborts. Equivalent to the  schema.ensure  hook."
+        ),
+    )
+    on_abort: Optional[Step] = Field(
+        None,
+        description=(
+            "Step to execute when the task aborts. Equivalent to the schema.on_abort"
+            " hook."
+        ),
+    )
+    on_error: Optional[Step] = Field(
+        None,
+        description=(
+            "Step to execute when the task errors. Equivalent to the schema.on_error"
+            " hook."
+        ),
+    )
+    on_failure: Optional[Step] = Field(
+        None,
+        description=(
+            "Step to execute when the task fails. Equivalent to the schema.on_failure"
+            " hook."
+        ),
+    )
+    on_success: Optional[Step] = Field(
+        None,
+        description=(
+            "Step to execute when the task succeeds. Equivalent to the"
+            " schema.on_success  hook."
+        ),
+    )
 
 
 class PutStep(Step, StepModifierMixin):
     class Config:
         extra = Extra.forbid
 
     resource: Optional[str] = Field(
@@ -1706,35 +1741,100 @@
     )
 
 
 class Job(BaseModel):
     class Config:
         extra = Extra.forbid
 
+    build_log_retention: Optional[BuildLogRetentionPolicy] = Field(
+        None,
+        description=(
+            "Configures the retention policy for build logs. This is useful if you have"
+            "  a job that runs often but after some amount of time the logs aren't"
+            " worth  keeping around.    Builds which are not retained by the configured"
+            " policy will have their logs  reaped. If this configuration is omitted,"
+            " logs are kept forever (unless    build-log-retention  is configured"
+            " globally).     \n@example  A complicated example \n   The following"
+            " example will keep logs for any builds that have completed in  the last 2"
+            " days, while also keeping the last 1000 builds and at least 1  succeeded"
+            " build.     ```yaml\njobs:\n- name: smoke-tests\n  build_log_retention:\n "
+            "   days: 2\n    builds: 1000\n    minimum_succeeded_builds: 1\n  plan:\n "
+            " - get: 10m\n  - task: smoke-tests\n    # ...\n```     If more than 1000"
+            " builds finish in the past 2 days,  all  of them  will be retained thanks"
+            " to the    schema.build_log_retention_policy.days `days`   configuration."
+            " Similarly, if there are 1000 builds spanning more than 2  days, they will"
+            " also be kept thanks to the    schema.build_log_retention_policy.builds"
+            " `builds`   configuration. And if they all happened to have failed, the   "
+            " schema.build_log_retention_policy.minimum_succeeded_builds"
+            " `minimum_succeeded_builds`   will keep around at least one successful"
+            " build. All policies operate  independently.         "
+            " build_log_retention_policy      days  number    Keep logs for builds"
+            " which have finished within the specified number of  days.          builds"
+            "  number    Keep logs for the last specified number of builds.         "
+            " minimum_succeeded_builds  number    Keep a minimum number of successful"
+            " build logs that would normally be  reaped.    Requires   "
+            " schema.build_log_retention_policy.builds `builds` to  be set to an"
+            " integer higher than 0 in order to work. For example, if   "
+            " schema.build_log_retention_policy.builds `builds` is  set to 5, and this"
+            " attribute to 1, say a job has the following build  history: 7(f), 6(f),"
+            " 5(f), 4(f), 3(f), 2(f), 1(s), where f means  failed and s means"
+            " succeeded, then builds 2 and 3 will be reaped,  because it retains 5"
+            " build logs, and at least 1 succeeded build log.  Default is 0."
+        ),
+    )
     build_logs_to_retain: Optional[Number] = Field(
         None,
         description=(
             "Deprecated.  Equivalent to setting   "
             " schema.build_log_retention_policy.builds"
             " `job.build_log_retention.builds` ."
         ),
     )
+    disable_manual_trigger: Optional[bool] = Field(
+        None,
+        description=(
+            "Default `false` .  If set to `true` , manual triggering of  the job (via"
+            " the web UI or  fly-trigger-job  ) will be disabled."
+        ),
+    )
+    ensure: Optional[Step] = Field(
+        None,
+        description=(
+            "Step to execute regardless of whether the job succeeds, fails, errors, or "
+            " aborts. Equivalent to the  schema.ensure  hook."
+        ),
+    )
+    interruptible: Optional[bool] = Field(
+        None,
+        description=(
+            "Default `false` .  Normally, when a worker is shutting down it  will wait"
+            " for builds with containers running on that worker to finish  before"
+            " exiting. If this value is set to `true` , the worker will not  wait on"
+            " the builds of this job. You may want this if e.g. you have a "
+            " self-deploying Concourse or long-running-but-low-importance jobs."
+        ),
+    )
     max_in_flight: Optional[Number] = Field(
         None,
         description=(
             "If set, specifies a maximum number of builds to run at a time. If  "
             " `serial` or `serial_groups` are set, they take precedence and  force this"
             " value to be `1` ."
         ),
     )
-    serial: Optional[bool] = Field(
+    name: Optional[Identifier] = Field(
         None,
         description=(
-            "Default `false` .  If set to `true` , builds will queue up  and execute"
-            " one-by-one, rather than executing in parallel."
+            "The name of the job. This should be short; it will show up in URLs."
+        ),
+    )
+    no_get: Optional[bool] = Field(
+        None,
+        description=(
+            "Skips the get step that usually follows the completion of the put step."
         ),
     )
     old_name: Optional[Identifier] = Field(
         None,
         description=(
             "The old name of the job. If configured, the history of old job will be "
             " inherited to the new one. Once the pipeline is set, this field can be "
@@ -1742,143 +1842,78 @@
             " job \n   This can be used to rename a job without losing its history,"
             " like so:     ```yaml\njobs:\n- name: new-name\n  old_name: current-name\n"
             "  plan: [{get: 10m}]\n```     After the pipeline is set, because the"
             " builds have been inherited, the job can  have the field removed:    "
             " ```yaml\njobs:\n- name: new-name\n  plan: [{get: 10m}]\n```"
         ),
     )
-    on_success: Optional[Step] = Field(
-        None,
-        description=(
-            "Step to execute when the job succeeds. Equivalent to the   "
-            " schema.on_success  hook."
-        ),
-    )
-    ensure: Optional[Step] = Field(
+    on_abort: Optional[Step] = Field(
         None,
         description=(
-            "Step to execute regardless of whether the job succeeds, fails, errors, or "
-            " aborts. Equivalent to the  schema.ensure  hook."
+            "Step to execute when the job aborts. Equivalent to the    schema.on_abort "
+            " hook."
         ),
     )
     on_error: Optional[Step] = Field(
         None,
         description=(
             "Step to execute when the job errors. Equivalent to the    schema.on_error "
             " hook."
         ),
     )
-    disable_manual_trigger: Optional[bool] = Field(
-        None,
-        description=(
-            "Default `false` .  If set to `true` , manual triggering of  the job (via"
-            " the web UI or  fly-trigger-job  ) will be disabled."
-        ),
-    )
-    serial_groups: Optional[list[Identifier]] = Field(
-        None,
-        description=(
-            "Default `[]` .  When set to an array of arbitrary tag-like  strings,"
-            " builds of this job and other jobs referencing the same tags will  be"
-            " serialized.     \n@example  Limiting parallelism \n   This can be used to"
-            " ensure that certain jobs do not run at the same time,  like so:    "
-            " ```yaml\njobs:\n- name: job-a\n  serial_groups: [some-tag]\n- name:"
-            " job-b\n  serial_groups: [some-tag, some-other-tag]\n- name: job-c\n "
-            " serial_groups: [some-other-tag]\n```     In this example, `job-a` and"
-            " `job-c` can run concurrently, but  neither job can run builds at the same"
-            " time as `job-b` .    The builds are executed in their order of creation,"
-            " across all jobs with  common tags."
-        ),
-    )
-    build_log_retention: Optional[BuildLogRetentionPolicy] = Field(
+    on_failure: Optional[Step] = Field(
         None,
         description=(
-            "Configures the retention policy for build logs. This is useful if you have"
-            "  a job that runs often but after some amount of time the logs aren't"
-            " worth  keeping around.    Builds which are not retained by the configured"
-            " policy will have their logs  reaped. If this configuration is omitted,"
-            " logs are kept forever (unless    build-log-retention  is configured"
-            " globally).     \n@example  A complicated example \n   The following"
-            " example will keep logs for any builds that have completed in  the last 2"
-            " days, while also keeping the last 1000 builds and at least 1  succeeded"
-            " build.     ```yaml\njobs:\n- name: smoke-tests\n  build_log_retention:\n "
-            "   days: 2\n    builds: 1000\n    minimum_succeeded_builds: 1\n  plan:\n "
-            " - get: 10m\n  - task: smoke-tests\n    # ...\n```     If more than 1000"
-            " builds finish in the past 2 days,  all  of them  will be retained thanks"
-            " to the    schema.build_log_retention_policy.days `days`   configuration."
-            " Similarly, if there are 1000 builds spanning more than 2  days, they will"
-            " also be kept thanks to the    schema.build_log_retention_policy.builds"
-            " `builds`   configuration. And if they all happened to have failed, the   "
-            " schema.build_log_retention_policy.minimum_succeeded_builds"
-            " `minimum_succeeded_builds`   will keep around at least one successful"
-            " build. All policies operate  independently.         "
-            " build_log_retention_policy      days  number    Keep logs for builds"
-            " which have finished within the specified number of  days.          builds"
-            "  number    Keep logs for the last specified number of builds.         "
-            " minimum_succeeded_builds  number    Keep a minimum number of successful"
-            " build logs that would normally be  reaped.    Requires   "
-            " schema.build_log_retention_policy.builds `builds` to  be set to an"
-            " integer higher than 0 in order to work. For example, if   "
-            " schema.build_log_retention_policy.builds `builds` is  set to 5, and this"
-            " attribute to 1, say a job has the following build  history: 7(f), 6(f),"
-            " 5(f), 4(f), 3(f), 2(f), 1(s), where f means  failed and s means"
-            " succeeded, then builds 2 and 3 will be reaped,  because it retains 5"
-            " build logs, and at least 1 succeeded build log.  Default is 0."
+            "Step to execute when the job fails. Equivalent to the    schema.on_failure"
+            "  hook."
         ),
     )
-    name: Optional[Identifier] = Field(
+    on_success: Optional[Step] = Field(
         None,
         description=(
-            "The name of the job. This should be short; it will show up in URLs."
+            "Step to execute when the job succeeds. Equivalent to the   "
+            " schema.on_success  hook."
         ),
     )
     plan: Optional[list[Step]] = Field(
         None, description="The sequence of  steps  steps  to execute."
     )
-    interruptible: Optional[bool] = Field(
-        None,
-        description=(
-            "Default `false` .  Normally, when a worker is shutting down it  will wait"
-            " for builds with containers running on that worker to finish  before"
-            " exiting. If this value is set to `true` , the worker will not  wait on"
-            " the builds of this job. You may want this if e.g. you have a "
-            " self-deploying Concourse or long-running-but-low-importance jobs."
-        ),
-    )
     public: Optional[bool] = Field(
         None,
         description=(
             "Default `false` .  If set to `true` , the build log of this  job will be"
             " viewable by unauthenticated users. Unauthenticated users will  always be"
             " able to see the inputs, outputs, and build status history of a  job. This"
             " is useful if you would like to expose your pipeline publicly  without"
             " showing sensitive information in the build log.    Note: when this is set"
             " to `true` , any  get-step  and    put-step  s will show the metadata for"
             " their resource version,  regardless of whether the resource itself has"
             " set  schema.resource.public    to `true` ."
         ),
     )
-    no_get: Optional[bool] = Field(
-        None,
-        description=(
-            "Skips the get step that usually follows the completion of the put step."
-        ),
-    )
-    on_failure: Optional[Step] = Field(
+    serial: Optional[bool] = Field(
         None,
         description=(
-            "Step to execute when the job fails. Equivalent to the    schema.on_failure"
-            "  hook."
+            "Default `false` .  If set to `true` , builds will queue up  and execute"
+            " one-by-one, rather than executing in parallel."
         ),
     )
-    on_abort: Optional[Step] = Field(
+    serial_groups: Optional[list[Identifier]] = Field(
         None,
         description=(
-            "Step to execute when the job aborts. Equivalent to the    schema.on_abort "
-            " hook."
+            "Default `[]` .  When set to an array of arbitrary tag-like  strings,"
+            " builds of this job and other jobs referencing the same tags will  be"
+            " serialized.     \n@example  Limiting parallelism \n   This can be used to"
+            " ensure that certain jobs do not run at the same time,  like so:    "
+            " ```yaml\njobs:\n- name: job-a\n  serial_groups: [some-tag]\n- name:"
+            " job-b\n  serial_groups: [some-tag, some-other-tag]\n- name: job-c\n "
+            " serial_groups: [some-other-tag]\n```     In this example, `job-a` and"
+            " `job-c` can run concurrently, but  neither job can run builds at the same"
+            " time as `job-b` .    The builds are executed in their order of creation,"
+            " across all jobs with  common tags."
         ),
     )
 
 
 class Pipeline(BaseModel):
     class Config:
         extra = Extra.forbid
@@ -1960,14 +1995,15 @@
         ),
     )
 
 
 class TryStep(Step, StepModifierMixin):
     class Config:
         extra = Extra.forbid
+        allow_population_by_field_name = True
 
     try_: Optional[Step] = Field(
         None,
         alias="try",
         description=(
             "Performs the given step, ignoring any failure and masking it with "
             " success.    This can be used when you want to perform some side-effect,"
```

### Comparing `ol-concourse-0.4.2/ol_concourse/lib/notifications.py` & `ol-concourse-0.4.3/ol_concourse/lib/notifications.py`

 * *Files identical despite different names*

### Comparing `ol-concourse-0.4.2/ol_concourse/lib/resource_types.py` & `ol-concourse-0.4.3/ol_concourse/lib/resource_types.py`

 * *Files identical despite different names*

### Comparing `ol-concourse-0.4.2/ol_concourse/lib/resources.py` & `ol-concourse-0.4.3/ol_concourse/lib/resources.py`

 * *Files identical despite different names*

### Comparing `ol-concourse-0.4.2/ol_concourse/lib/tasks.py` & `ol-concourse-0.4.3/ol_concourse/lib/tasks.py`

 * *Files identical despite different names*

### Comparing `ol-concourse-0.4.2/ol_concourse.egg-info/SOURCES.txt` & `ol-concourse-0.4.3/ol_concourse.egg-info/SOURCES.txt`

 * *Files identical despite different names*

