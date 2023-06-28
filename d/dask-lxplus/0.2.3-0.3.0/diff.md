# Comparing `tmp/dask_lxplus-0.2.3.tar.gz` & `tmp/dask_lxplus-0.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dask_lxplus-0.2.3.tar", last modified: Thu Jan 12 14:42:08 2023, max compression
+gzip compressed data, was "dask_lxplus-0.3.0.tar", last modified: Wed Jun 28 14:50:58 2023, max compression
```

## Comparing `dask_lxplus-0.2.3.tar` & `dask_lxplus-0.3.0.tar`

### file list

```diff
@@ -1,18 +1,20 @@
-drwxr-xr-x   0 ben        (501) staff       (20)        0 2023-01-12 14:42:08.006002 dask_lxplus-0.2.3/
--rw-r--r--   0 ben        (501) staff       (20)      589 2022-08-10 12:35:46.000000 dask_lxplus-0.2.3/LICENSE.txt
--rw-r--r--   0 ben        (501) staff       (20)       27 2022-08-10 15:10:59.000000 dask_lxplus-0.2.3/MANIFEST.in
--rw-r--r--   0 ben        (501) staff       (20)     2799 2023-01-12 14:42:08.006071 dask_lxplus-0.2.3/PKG-INFO
--rw-r--r--   0 ben        (501) staff       (20)     2064 2022-08-10 14:26:52.000000 dask_lxplus-0.2.3/README.md
-drwxr-xr-x   0 ben        (501) staff       (20)        0 2023-01-12 14:42:08.005278 dask_lxplus-0.2.3/dask_lxplus/
--rw-r--r--   0 ben        (501) staff       (20)      286 2021-11-26 14:54:16.000000 dask_lxplus-0.2.3/dask_lxplus/__init__.py
--rw-r--r--   0 ben        (501) staff       (20)     8331 2023-01-12 10:49:40.000000 dask_lxplus-0.2.3/dask_lxplus/cluster.py
--rw-r--r--   0 ben        (501) staff       (20)      525 2021-11-26 14:54:16.000000 dask_lxplus-0.2.3/dask_lxplus/config.py
--rw-r--r--   0 ben        (501) staff       (20)      625 2022-04-25 16:22:55.000000 dask_lxplus-0.2.3/dask_lxplus/jobqueue-cern.yaml
-drwxr-xr-x   0 ben        (501) staff       (20)        0 2023-01-12 14:42:08.005914 dask_lxplus-0.2.3/dask_lxplus.egg-info/
--rw-r--r--   0 ben        (501) staff       (20)     2799 2023-01-12 14:42:07.000000 dask_lxplus-0.2.3/dask_lxplus.egg-info/PKG-INFO
--rw-r--r--   0 ben        (501) staff       (20)      326 2023-01-12 14:42:08.000000 dask_lxplus-0.2.3/dask_lxplus.egg-info/SOURCES.txt
--rw-r--r--   0 ben        (501) staff       (20)        1 2023-01-12 14:42:07.000000 dask_lxplus-0.2.3/dask_lxplus.egg-info/dependency_links.txt
--rw-r--r--   0 ben        (501) staff       (20)      159 2023-01-12 14:42:07.000000 dask_lxplus-0.2.3/dask_lxplus.egg-info/requires.txt
--rw-r--r--   0 ben        (501) staff       (20)       12 2023-01-12 14:42:08.000000 dask_lxplus-0.2.3/dask_lxplus.egg-info/top_level.txt
--rw-r--r--   0 ben        (501) staff       (20)     1003 2023-01-12 14:42:08.006363 dask_lxplus-0.2.3/setup.cfg
--rw-r--r--   0 ben        (501) staff       (20)       61 2021-11-26 14:54:16.000000 dask_lxplus-0.2.3/setup.py
+drwxr-xr-x   0 ben        (501) staff       (20)        0 2023-06-28 14:50:58.384212 dask_lxplus-0.3.0/
+-rw-r--r--   0 ben        (501) staff       (20)      589 2022-08-10 12:35:46.000000 dask_lxplus-0.3.0/LICENSE.txt
+-rw-r--r--   0 ben        (501) staff       (20)       27 2022-08-10 15:10:59.000000 dask_lxplus-0.3.0/MANIFEST.in
+-rw-r--r--   0 ben        (501) staff       (20)     2799 2023-06-28 14:50:58.384298 dask_lxplus-0.3.0/PKG-INFO
+-rw-r--r--   0 ben        (501) staff       (20)     2064 2022-08-10 14:26:52.000000 dask_lxplus-0.3.0/README.md
+drwxr-xr-x   0 ben        (501) staff       (20)        0 2023-06-28 14:50:58.382810 dask_lxplus-0.3.0/dask_lxplus/
+-rw-r--r--   0 ben        (501) staff       (20)      286 2021-11-26 14:54:16.000000 dask_lxplus-0.3.0/dask_lxplus/__init__.py
+-rw-r--r--   0 ben        (501) staff       (20)     8965 2023-06-28 14:50:15.000000 dask_lxplus-0.3.0/dask_lxplus/cluster.py
+-rw-r--r--   0 ben        (501) staff       (20)      525 2021-11-26 14:54:16.000000 dask_lxplus-0.3.0/dask_lxplus/config.py
+-rw-r--r--   0 ben        (501) staff       (20)      743 2023-06-28 14:50:15.000000 dask_lxplus-0.3.0/dask_lxplus/jobqueue-cern.yaml
+drwxr-xr-x   0 ben        (501) staff       (20)        0 2023-06-28 14:50:58.383785 dask_lxplus-0.3.0/dask_lxplus.egg-info/
+-rw-r--r--   0 ben        (501) staff       (20)     2799 2023-06-28 14:50:58.000000 dask_lxplus-0.3.0/dask_lxplus.egg-info/PKG-INFO
+-rw-r--r--   0 ben        (501) staff       (20)      348 2023-06-28 14:50:58.000000 dask_lxplus-0.3.0/dask_lxplus.egg-info/SOURCES.txt
+-rw-r--r--   0 ben        (501) staff       (20)        1 2023-06-28 14:50:58.000000 dask_lxplus-0.3.0/dask_lxplus.egg-info/dependency_links.txt
+-rw-r--r--   0 ben        (501) staff       (20)      166 2023-06-28 14:50:58.000000 dask_lxplus-0.3.0/dask_lxplus.egg-info/requires.txt
+-rw-r--r--   0 ben        (501) staff       (20)       12 2023-06-28 14:50:58.000000 dask_lxplus-0.3.0/dask_lxplus.egg-info/top_level.txt
+-rw-r--r--   0 ben        (501) staff       (20)     1010 2023-06-28 14:50:58.384640 dask_lxplus-0.3.0/setup.cfg
+-rw-r--r--   0 ben        (501) staff       (20)       61 2021-11-26 14:54:16.000000 dask_lxplus-0.3.0/setup.py
+drwxr-xr-x   0 ben        (501) staff       (20)        0 2023-06-28 14:50:58.384010 dask_lxplus-0.3.0/tests/
+-rw-r--r--   0 ben        (501) staff       (20)     4100 2023-06-28 14:50:15.000000 dask_lxplus-0.3.0/tests/test_cluster.py
```

### Comparing `dask_lxplus-0.2.3/LICENSE.txt` & `dask_lxplus-0.3.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `dask_lxplus-0.2.3/PKG-INFO` & `dask_lxplus-0.3.0/dask_lxplus.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: dask_lxplus
-Version: 0.2.3
+Name: dask-lxplus
+Version: 0.3.0
 Home-page: https://github.com/cernops/dask-lxplus
 Author: Ben Jones
 Author-email: b.jones@cern.ch
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Science/Research
 Classifier: Operating System :: OS Independent
```

### Comparing `dask_lxplus-0.2.3/README.md` & `dask_lxplus-0.3.0/README.md`

 * *Files identical despite different names*

### Comparing `dask_lxplus-0.2.3/dask_lxplus/cluster.py` & `dask_lxplus-0.3.0/dask_lxplus/cluster.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,46 +1,46 @@
 import logging
 
 from collections import ChainMap
+import warnings
 import dask
 from dask_jobqueue import HTCondorCluster
 from dask_jobqueue.htcondor import HTCondorJob
 import re
 import sys
-from warnings import warn
 
 
 logger = logging.getLogger(__name__)
 logger.setLevel(logging.DEBUG)
 
 
 def merge(*args):
     # This will merge dicts, but earlier definitions win
     return dict(ChainMap(*filter(None, args)))
 
 
-def check_env_extra(var, env_extra):
+def check_job_script_prologue(var, job_script_prologue):
     """
-    Check if an environment variable is set in env_extra.
+    Check if an environment variable is set in job_script_prologue.
 
     Parameters
     ----------
     var : str
         Name of the environment variable to check.
 
-    env_extra: list of k=v strings
+    job_script_prologue: list of k=v strings
 
     Returns
     -------
     bool
         True if the environment variable is set.
     """
-    if not env_extra:
+    if not job_script_prologue:
         return False
-    matches = list(filter(lambda x: re.match(f"\W*{var}\s*=.*", x), env_extra))
+    matches = list(filter(lambda x: re.match(f"\W*export {var}\s*=.*", x), job_script_prologue))
     if matches:
         return True
     return False
 
 
 def get_xroot_url(eos_path):
     """
@@ -65,38 +65,41 @@
     if not eos_match:
         return None
     return f"root://eosuser.cern.ch//eos/user/{eos_match.group('username')[:1]}/{eos_match.group('username')}{eos_match.group('path')}"
 
 
 class CernJob(HTCondorJob):
     config_name = "cern"
-    submit_command = "condor_submit -spool"
 
     def __init__(self,
                  scheduler=None,
                  name=None,
                  disk=None,
                  **base_class_kwargs
                  ):
 
         if disk is None:
             num_cores = base_class_kwargs.get("cores", 1)
             disk = f'{int(num_cores) * 20} GB'
 
+        warnings.simplefilter(action='ignore', category=FutureWarning)
+
         super().__init__(scheduler=scheduler, name=name, disk=disk, **base_class_kwargs)
 
+        warnings.resetwarnings()
+
         if hasattr(self, "log_directory"):
                 self.job_header_dict.pop("Stream_Output", None)
                 self.job_header_dict.pop("Stream_Error", None)
 
 
 class CernCluster(HTCondorCluster):
     __doc__ = (
         HTCondorCluster.__doc__
-    + """
+    """
     A customized :class:`dask_jobqueue.HTCondorCluster` subclass for spawning Dask workers in the CERN HTCondor pool
 
     It provides the customizations and submit options required for the CERN pool.
     
     Additional CERN parameters:
     worker_image: The container to run the Dask workers inside. Defaults to: 
     ``"/cvmfs/unpacked.cern.ch/gitlab-registry.cern.ch/batch-team/dask-lxplus/lxdask-cc7:latest"``
@@ -137,15 +140,15 @@
         :param lcg: If True, use the LCG environment from cvmfs. Please note you need to have
         loaded the environment before running the python interpreter. Defaults to False.
         :param kwargs: Additional keyword arguments like ``cores`` or ``memory`` to pass
         to `dask_jobqueue.HTCondorCluster`.
         """
 
         if image_type is not None:
-            warn(
+            warnings.warn(
                 "The `image_type` parameter is deprecated. Please use `container_runtime` instead.",
                 DeprecationWarning,
             )
             container_runtime = container_runtime or image_type
 
         if lcg:
             if not re.match('^/cvmfs/sft(?:-nightlies)?.cern.ch/lcg/.+/python[2,3]?$', sys.executable):
@@ -156,16 +159,20 @@
             worker_image=worker_image,
             container_runtime=container_runtime,
             gpus=gpus,
             batch_name=batch_name,
             lcg=lcg,
         )
 
+        warnings.simplefilter(action='ignore', category=FutureWarning)
+
         super().__init__(**base_class_kwargs)
 
+        warnings.resetwarnings()
+
     @classmethod
     def _modify_kwargs(cls,
                        kwargs,
                        *,
                        worker_image = None,
                        container_runtime = None,
                        gpus = None,
@@ -182,35 +189,41 @@
         container_runtime = container_runtime or dask.config.get(f"jobqueue.{cls.config_name}.container-runtime")
         worker_image = worker_image or dask.config.get(f"jobqueue.{cls.config_name}.worker-image")
 
 
         has_logdir = "log_directory" in modified and modified["log_directory"]
         xroot_url = get_xroot_url(modified["log_directory"]) if has_logdir and modified["log_directory"].startswith("/eos/") else None
 
-        modified["job_extra"] = merge(
+        modified["job_extra_directives"] = merge(
             {"universe": "docker" if container_runtime == "docker" else "vanilla"},
             {"docker_image": f'"{worker_image}"'} if container_runtime == "docker" else None,
             {"MY.SingularityImage": f'"{worker_image}"'} if container_runtime == "singularity" else None,
             {"request_gpus": str(gpus)} if gpus is not None else None,
             {"MY.IsDaskWorker": "true"},
             # getenv justified in case of LCG as both sides have to be the same environment
             {"getenv": "true"} if lcg else None,
             {"output_destination": f"{xroot_url}"} if xroot_url else None,
             {"Output": "worker-$(ClusterId).$(ProcId).out"} if xroot_url else None,
             {"Error": "worker-$(ClusterId).$(ProcId).err"} if xroot_url else None,
             {"Log": "worker-$(ClusterId).log"} if xroot_url else None,
             {"MY.SpoolOnEvict": False} if has_logdir else None,
             # extra user input
-            kwargs.get("job_extra", dask.config.get(f"jobqueue.{cls.config_name}.job-extra")),
+            kwargs.get("job_extra_directives", dask.config.get(f"jobqueue.{cls.config_name}.job_extra_directives")),
+            kwargs.get("job_extra", dask.config.get(f"jobqueue.{cls.config_name}.job_extra")),
             {"JobBatchName": f'"{batch_name or dask.config.get(f"jobqueue.{cls.config_name}.batch-name")}"'},
             # never transfer files
             {"transfer_output_files": '""'}
         )
 
-        modified["extra"] = [
-                *kwargs.get("extra", dask.config.get(f"jobqueue.{cls.config_name}.extra")),
+        submit_command_extra = kwargs.get("submit_command_extra", [])
+        if "-spool" not in submit_command_extra:
+            submit_command_extra.append('-spool')
+            modified["submit_command_extra"] = submit_command_extra
+
+        modified["worker_extra_args"] = [
+                *kwargs.get("worker_extra_args", dask.config.get(f"jobqueue.{cls.config_name}.worker_extra_args")),
             "--worker-port",
             "10000:10100",
         ]
         return modified
```

### Comparing `dask_lxplus-0.2.3/dask_lxplus/config.py` & `dask_lxplus-0.3.0/dask_lxplus/config.py`

 * *Files identical despite different names*

### Comparing `dask_lxplus-0.2.3/dask_lxplus/jobqueue-cern.yaml` & `dask_lxplus-0.3.0/dask_lxplus/jobqueue-cern.yaml`

 * *Files 20% similar despite different names*

```diff
@@ -13,25 +13,32 @@
 
     # default worker image
     worker-image: "/cvmfs/unpacked.cern.ch/gitlab-registry.cern.ch/batch-team/dask-lxplus/lxdask-cc7:latest"
 
     # default container runtime:
     container-runtime: "singularity"
 
-    log-directory: null
-
     extra: []
 
-    env-extra: []
+    env_extra: []
 
-    job-extra: {}
+    job_extra: {}
+
+    log-directory: null
+
+    job_extra_directives: {}
 
     scheduler-options: {}
 
     death-timeout: 60
 
     local-directory: "/tmp/"
 
     shebang: "#!/usr/bin/env bash"
 
     interface: null
 
+    shared_temp_directory: null
+
+    worker_extra_args: []
+
+    job_script_prologue: []
```

### Comparing `dask_lxplus-0.2.3/dask_lxplus.egg-info/PKG-INFO` & `dask_lxplus-0.3.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
-Name: dask-lxplus
-Version: 0.2.3
+Name: dask_lxplus
+Version: 0.3.0
 Home-page: https://github.com/cernops/dask-lxplus
 Author: Ben Jones
 Author-email: b.jones@cern.ch
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Science/Research
 Classifier: Operating System :: OS Independent
```

### Comparing `dask_lxplus-0.2.3/setup.cfg` & `dask_lxplus-0.3.0/setup.cfg`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = dask_lxplus
-version = 0.2.3
+version = 0.3.0
 long_description = file: README.md
 long_description_content_type = text/markdown
 license_files = LICENSE.txt
 author = Ben Jones
 author_email = b.jones@cern.ch
 url = https://github.com/cernops/dask-lxplus
 classifiers = 
@@ -23,15 +23,15 @@
 packages = 
 	dask_lxplus
 install_requires = 
 	click>=7.0
 	click-didyoumean
 	cryptography
 	dask
-	dask-jobqueue
+	dask-jobqueue>=0.8.1
 	htcondor>=8.9.8
 	humanize
 	psutil
 	pyyaml
 	watchdog
 	importlib-metadata>=1.0;python_version < "3.9"
 python_requires = >=3.6
```

