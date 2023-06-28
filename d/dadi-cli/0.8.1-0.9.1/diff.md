# Comparing `tmp/dadi_cli-0.8.1.tar.gz` & `tmp/dadi_cli-0.9.1.tar.gz`

## Comparing `dadi_cli-0.8.1.tar` & `dadi_cli-0.9.1.tar`

### file list

```diff
@@ -1,19 +1,19 @@
--rw-r--r--   0        0        0     3718 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/BestFit.py
--rw-r--r--   0        0        0     2498 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/GenerateCache.py
--rw-r--r--   0        0        0     4670 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/GenerateFs.py
--rw-r--r--   0        0        0     3727 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/InferDFE.py
--rw-r--r--   0        0        0     6413 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/InferDM.py
--rw-r--r--   0        0        0     3640 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/Models.py
--rw-r--r--   0        0        0     5347 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/Pdfs.py
--rw-r--r--   0        0        0     8068 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/Plot.py
--rw-r--r--   0        0        0     4112 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/SimulateFs.py
--rw-r--r--   0        0        0     9874 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/Stat.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/__init__.py
--rw-r--r--   0        0        0    57937 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/__main__.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/conftest.py
--rw-r--r--   0        0        0     2586 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/dadi_cli/utilities.py
--rw-r--r--   0        0        0      260 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/.gitignore
--rw-r--r--   0        0        0    11339 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/LICENSE
--rw-r--r--   0        0        0    32821 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/README.md
--rw-r--r--   0        0        0      718 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/pyproject.toml
--rw-r--r--   0        0        0    33294 2020-02-02 00:00:00.000000 dadi_cli-0.8.1/PKG-INFO
+-rw-r--r--   0        0        0     5501 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/BestFit.py
+-rw-r--r--   0        0        0     2587 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/GenerateCache.py
+-rw-r--r--   0        0        0     4670 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/GenerateFs.py
+-rw-r--r--   0        0        0     3727 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/InferDFE.py
+-rw-r--r--   0        0        0     6098 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/InferDM.py
+-rw-r--r--   0        0        0     3640 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/Models.py
+-rw-r--r--   0        0        0     5347 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/Pdfs.py
+-rw-r--r--   0        0        0     7928 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/Plot.py
+-rw-r--r--   0        0        0     4112 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/SimulateFs.py
+-rw-r--r--   0        0        0     9874 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/Stat.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/__init__.py
+-rw-r--r--   0        0        0    63709 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/__main__.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/conftest.py
+-rw-r--r--   0        0        0     2586 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/dadi_cli/utilities.py
+-rw-r--r--   0        0        0      287 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/.gitignore
+-rw-r--r--   0        0        0    11339 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/LICENSE
+-rw-r--r--   0        0        0     1005 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/README.md
+-rw-r--r--   0        0        0      853 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/pyproject.toml
+-rw-r--r--   0        0        0     1565 2020-02-02 00:00:00.000000 dadi_cli-0.9.1/PKG-INFO
```

### Comparing `dadi_cli-0.8.1/dadi_cli/GenerateCache.py` & `dadi_cli-0.9.1/dadi_cli/GenerateCache.py`

 * *Files 2% similar despite different names*

```diff
@@ -33,15 +33,18 @@
         output str: Name of the output file.
         sample_sizes list: Sample sizes of populations.
         cpus int: Number of CPUs to use in cache generation.
         gpus int: Number of GPUs to use in cache generation.
         dimensionality int: Dimensionality of the frequency spectrum.
     """
 
-    popt, theta = get_opts_and_theta(popt, gen_cache=True)
+    if func is not getattr(DFE.DemogSelModels, 'equil'):
+        popt, theta = get_opts_and_theta(popt, gen_cache=True)
+    else:
+        popt = []
 
     if grids == None:
         grids = cache_pts_l_func(sample_sizes)
 
     if dimensionality == 1:
         spectra = DFE.Cache1D(
             popt,
```

### Comparing `dadi_cli-0.8.1/dadi_cli/GenerateFs.py` & `dadi_cli-0.9.1/dadi_cli/GenerateFs.py`

 * *Files identical despite different names*

### Comparing `dadi_cli-0.8.1/dadi_cli/InferDFE.py` & `dadi_cli-0.9.1/dadi_cli/InferDFE.py`

 * *Files identical despite different names*

### Comparing `dadi_cli-0.8.1/dadi_cli/InferDM.py` & `dadi_cli-0.9.1/dadi_cli/InferDM.py`

 * *Files 9% similar despite different names*

```diff
@@ -79,32 +79,27 @@
             pts_l,
             lower_bound=lower_bounds,
             upper_bound=upper_bounds,
             fixed_params=fixed_params,
             algorithm=nlopt.LN_BOBYQA,
             maxeval=maxeval,
             maxtime=maxtime,
-            verbose=250,
+            verbose=0,
         )
 
         # Calculate the best-fit model to get ll and theta
         model = func_ex(popt, fs.sample_sizes, pts_l)
         ll_model = dadi.Inference.ll_multinom(model, fs)
         theta = dadi.Inference.optimal_sfs_scaling(model, fs)
     except nlopt.RoundoffLimited:
         print('nlopt.RoundoffLimited occured, other jobs still running. Users might want to adjust their boundaries or starting parameters if this message occures many times.')
         ll_model = -np.inf
         theta = np.nan
         popt = [np.nan for ele in p0]
 
-    if (model < 0).sum() > 0:
-        print(
-            f"!!!WARNING!!!\nPotentially large negative values!\nMost negative value is: {model.min()}"
-            + f"\nSum of negative entries is: {np.sum(model[model<0])}\nIf negative values are very negative (<-1), rerun with larger values for --grids"
-        )
 
     return ll_model, popt, theta
 
 
 
 def infer_global_opt(
     fs,
```

### Comparing `dadi_cli-0.8.1/dadi_cli/Models.py` & `dadi_cli-0.9.1/dadi_cli/Models.py`

 * *Files identical despite different names*

### Comparing `dadi_cli-0.8.1/dadi_cli/Pdfs.py` & `dadi_cli-0.9.1/dadi_cli/Pdfs.py`

 * *Files identical despite different names*

### Comparing `dadi_cli-0.8.1/dadi_cli/Plot.py` & `dadi_cli-0.9.1/dadi_cli/Plot.py`

 * *Files 6% similar despite different names*

```diff
@@ -190,54 +190,52 @@
         model = model.project(projections)
         dadi.Plotting.plot_2d_comp_Poisson(
             model, fs, vmin=vmin, resid_range=resid_range
         )
     fig.savefig(output)
 
 
-def plot_mut_prop(dfe_popt, nomisid, mut_rate, seq_len, ratio, output):
+def plot_mut_prop(pdf, dfe_popt, output):
     """
     Description:
-        Plots proportions of mutations with different selection coefficients given a DFE.
+        Plots proportions of mutations with different selection coefficients given a DFE in 2Ns unit.
 
     Arguments:
+        pdf: Type of the probability distribution for the best-fit DFE.
         dfe_popt str: Name of the file containing the best-fit DFE parameters.
-        nomisid bool: If False, add a parameter for modeling ancestral state misidentification when data are polarized.
-        mut_rate float: Mutation rate per base.
-        seq_len float: Sequence length.
-        ratio float: Ratio of synonymous to non-synonymous mutations.
         output str: Name of the output file.
     """
-    dfe_params, theta = get_opts_and_theta(dfe_popt)
-
-    Na = theta / (4 * mut_rate * seq_len * (ratio / (1 + ratio)))
-
-    def mut_prop(shape, scale, Na):
-        from scipy import stats
-
-        scale = scale / (2 * Na)
-        p1 = stats.gamma.cdf(1e-5, a=shape, scale=scale)
-        p2 = stats.gamma.cdf(1e-4, a=shape, scale=scale)
-        p3 = stats.gamma.cdf(1e-3, a=shape, scale=scale)
-        p4 = stats.gamma.cdf(1e-2, a=shape, scale=scale)
+    from scipy import stats
 
-        return p1, p2 - p1, p3 - p2, p4 - p3, 1 - p4
-
-    props = mut_prop(dfe_params[0], dfe_params[1], Na)
+    dfe_params, theta = get_opts_and_theta(dfe_popt)
 
+    if pdf == 'beta':
+        ps = stats.beta.cdf([1, 10, 100], dfe_params[0], dfe_params[1])
+    elif pdf == 'exponential':
+        ps = stats.expon.cdf([1, 10, 100], scale=dfe_params[0])
+    elif pdf == 'gamma':
+        ps = stats.gamma.cdf([1, 10, 100], dfe_params[0], scale=dfe_params[1])
+    elif pdf == 'lognormal':
+        ps = stats.lognorm.cdf([1, 10, 100], dfe_params[1], scale=np.exp(dfe_params[0]))
+    elif pdf == 'normal':
+        ps = stats.norm.cdf([1, 10, 100], loc=dfe_params[0], scale=dfe_params[1])
+    else:
+        raise Exception(f'The {pdf} distribution is NOT supported!')
+    
+    props = [ps[0], ps[1]-ps[0], ps[2]-ps[1], 1-ps[2]]
+    
     fig = plt.figure(219033)
-    plt.bar([0, 1, 2, 3, 4], props, alpha=0.7)
+    plt.bar([0, 1, 2, 3], props, alpha=0.7)
     plt.ylabel("Proportion")
-    plt.xlabel("Selection coefficient")
+    plt.xlabel("2N|s|")
     plt.xticks(
-        [0, 1, 2, 3, 4],
+        [0, 1, 2, 3],
         [
-            "0<=|s|<1e-5",
-            "1e-5<=|s|<1e-4",
-            "1e-4<=|s|<1e-3",
-            "1e-3<=|s|<1e-2",
-            "1e-2<=|s|",
+            "<1",
+            "1–10",
+            "10–100",
+            ">100",
         ],
-        rotation=45,
     )
     plt.grid(alpha=0.3)
+
     fig.savefig(output, bbox_inches="tight")
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `dadi_cli-0.8.1/dadi_cli/SimulateFs.py` & `dadi_cli-0.9.1/dadi_cli/SimulateFs.py`

 * *Files identical despite different names*

### Comparing `dadi_cli-0.8.1/dadi_cli/Stat.py` & `dadi_cli-0.9.1/dadi_cli/Stat.py`

 * *Files identical despite different names*

### Comparing `dadi_cli-0.8.1/dadi_cli/__main__.py` & `dadi_cli-0.9.1/dadi_cli/__main__.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-import argparse, glob, os.path, sys, signal
+import argparse, glob, os.path, sys, signal, warnings
 import numpy as np
 import random
 import dadi
 import multiprocessing
 
 from dadi_cli.GenerateFs import *
 from dadi_cli.GenerateCache import *
@@ -36,14 +36,15 @@
 def run_generate_fs(args):
     if args.mask_shared:
         mask = "shared"
     elif args.mask:
         mask = "singletons"
     else:
         mask = ""
+    _make_dir(args.output)
     generate_fs(
         vcf=args.vcf,
         output=args.output,
         bootstrap=args.bootstrap,
         chunk_size=args.chunk_size,
         seed=args.seed,
         pop_ids=args.pop_ids,
@@ -55,22 +56,34 @@
         masking=mask,
     )
 
 
 def run_generate_cache(args):
     if args.model_file is None and args.model not in [m[0] for m in getmembers(DFE.DemogSelModels, isfunction)]:
         raise ValueError(f"{args.model} is not in dadi.DFE.DemogSelModels, did you mean to include _sel or _single_sel in the model name or specify a --model-file?")
+
     if args.model_file is not None:
         if "://" in args.model_file:
+            import urllib.request
             model_fi = open("dadi_models.py","w")
             with urllib.request.urlopen(args.model_file) as f:
                 model_fi.write(f.read().decode('utf-8'))
             model_fi.close()
             args.model_file = "dadi_models"
+
+    if "://" in args.demo_popt:
+        import urllib.request
+        popt_fi = open("demo-popt.bestfits","w")
+        with urllib.request.urlopen(args.demo_popt) as f:
+            popt_fi.write(f.read().decode('utf-8'))
+        popt_fi.close()
+        args.demo_popt = "demo-popt.bestfits"
+
     func, _ = get_model(args.model, args.model_file)
+    _make_dir(args.output)
     generate_cache(
         func=func,
         grids=args.grids,
         popt=args.demo_popt,
         gamma_bounds=args.gamma_bounds,
         gamma_pts=args.gamma_pts,
         additional_gammas=args.additional_gammas,
@@ -84,19 +97,21 @@
 
 def run_simulate_dm(args):
     from dadi_cli.SimulateFs import simulate_demography
     # Due to development history, much of the code expects a args.misid variable, so create it.
     args.misid = not args.nomisid
     if args.model_file is not None:
         if "://" in args.model_file:
+            import urllib.request
             model_fi = open("dadi_models.py","w")
             with urllib.request.urlopen(args.model_file) as f:
                 model_fi.write(f.read().decode('utf-8'))
             model_fi.close()
             args.model_file = "dadi_models"
+    _make_dir(args.output)
     simulate_demography(
         args.model,
         args.model_file,
         args.p0,
         args.sample_sizes,
         args.grids,
         args.misid,
@@ -107,78 +122,96 @@
 
 def run_simulate_dfe(args):
     from dadi_cli.SimulateFs import simulate_dfe
 
     import pickle
 
     if args.cache1d != None:
-        cache1d = pickle.load(open(args.cache1d, "rb"))
+        if "://" in args.cache1d:
+            from urllib.request import urlopen
+            cache1d = pickle.load(urlopen(args.cache1d))
+        else:
+            cache1d = pickle.load(open(args.cache1d, "rb"))
     else:
         cache1d = args.cache1d
+
     if args.cache2d != None:
-        cache2d = pickle.load(open(args.cache2d, "rb"))
+        if "://" in args.cache2d:
+            from urllib.request import urlopen
+            cache2d = pickle.load(urlopen(args.cache2d))
+        else:
+            cache2d = pickle.load(open(args.cache2d, "rb"))
     else:
         cache2d = args.cache2d
 
     # Due to development history, much of the code expects a args.misid variable, so create it.
     args.misid = not args.nomisid
-
+    _make_dir(args.output)
     simulate_dfe(
         args.p0,
         cache1d,
         cache2d,
         args.pdf1d,
         args.pdf2d,
         args.ratio,
         args.misid,
         args.output,
     )
 
 
 def run_simulate_demes(args):
     from dadi_cli.SimulateFs import simulate_demes
-
-    simulate_demes(args.demes_file, atgs.sample_sizes, args.grids, args.output)
+    if "://" in args.demes_file:
+        import urllib.request
+        model_fi = open("demes_file.yml","w")
+        with urllib.request.urlopen(args.demes_file) as f:
+            model_fi.write(f.read().decode('utf-8'))
+        model_fi.close()
+        args.demes_file = "demes_file.yml"
+    _make_dir(args.output)
+    simulate_demes(args.demes_file, args.sample_sizes, args.grids, args.pop_ids, args.output)
 
 
 def run_infer_dm(args):
 
     if "://" in args.fs:
         import urllib.request
         sfs_fi = open("sfs.fs","w")
         with urllib.request.urlopen(args.fs) as f:
             sfs_fi.write(f.read().decode('utf-8'))
         sfs_fi.close()
         args.fs ="sfs.fs"
-        if args.model_file is not None:
-            if "://" in args.model_file:
-                model_fi = open("dadi_models.py","w")
-                with urllib.request.urlopen(args.model_file) as f:
-                    model_fi.write(f.read().decode('utf-8'))
-                model_fi.close()
-                args.model_file = "dadi_models"
+    if args.model_file is not None:
+        if "://" in args.model_file:
+            model_fi = open("dadi_models.py","w")
+            with urllib.request.urlopen(args.model_file) as f:
+                model_fi.write(f.read().decode('utf-8'))
+            model_fi.close()
+            args.model_file = "dadi_models"
 
     fs = dadi.Spectrum.from_file(args.fs)
 
+    _make_dir(args.output_prefix)
+
     # Because basic standard neutral models do not need to optimized
     # we can calculate the log-likelihood and theta
     if args.model in ['snm_1d', 'snm_2d'] and args.p0 == -1 and args.lbounds == None and args.ubounds == None:
-        fid = open(args.output_prefix + ".InferDM.simple.snm.txt", "w")
+        fid = open(args.output_prefix + ".InferDM.bestfits", "w")
         # Write command line to results file
         import sys
         fid.write("# {0}\n".format(" ".join(sys.argv)))
 
         # Extract model function and parameter names, from custom model_file if necessary
         func, param_names = get_model(args.model, args.model_file)
         if args.grids is None:
-            pts_l = pts_l_func(fs.sample_sizes)
+            args.grids = pts_l_func(fs.sample_sizes)
 
         fid.write("# Log(likelihood)\t" + "\t".join(param_names) + "\ttheta\n")
         from sys import exit
-        model = dadi.Numerics.make_extrap_func(func)([], fs.sample_sizes, pts_l)
+        model = dadi.Numerics.make_extrap_func(func)([], fs.sample_sizes, args.grids)
         ll_model = dadi.Inference.ll_multinom(model, fs)
         theta = dadi.Inference.optimal_sfs_scaling(model, fs)
         fid.write('\t'.join(str(_) for _ in [ll_model, theta])+'\n')
         fid.close()
         exit()
     else:
         pass
@@ -237,15 +270,15 @@
         args.seed = int(time.time()) + int(os.getpid())
     import random
 
     np.random.seed(args.seed)
 
     if args.global_optimization:
         if inbreeding:
-            print("Warning: can't down project inbreeding data for global optimization")
+            warnings.warn("Warning: can't down project inbreeding data for global optimization\n")
         else:
             existing_files = glob.glob(args.output_prefix + ".global.InferDM.opts.*")
             try:
                 newest_file_num = (
                     max([int(ele.split(".")[-1]) for ele in existing_files]) + 1
                 )
             except:
@@ -368,35 +401,53 @@
                 result = get_bestfit_params(
                     path=args.output_prefix + ".global.InferDM.opts.*",
                     lbounds=args.lbounds,
                     ubounds=args.ubounds,
                     output=args.output_prefix + ".global.InferDM.bestfits",
                     delta=args.delta_ll,
                 )
-                if result is not None:
-                    args.force_convergence = False
-                    break
+                ### Place holder if we want check convergence for global optimization
+                # if result is not None:
+                #    args.force_convergence = False
+                #    break
             if not args.work_queue:
                 # Stop the workers
                 for worker in workers:
                     worker.terminate()
             from dadi_cli.utilities import get_opts_and_theta
             import os
 
             args.p0, _ = get_opts_and_theta(
                 args.output_prefix + ".global.InferDM.bestfits"
             )
 
+    # Keep track of number of optimizations before checking convergence
+    num_opts = 0
+
+    # Keep track when optimization happens with force-convergence
     converged = False
+
+    # Raise warning if --check-convergence larger than --optimizations
+    # This isn't required for --force-convergence, as it optimizes until convergence occures.
+    if args.optimizations < args.check_convergence:
+        warnings.warn("WARNING: Number of optimizations is less than the number requested before checking convergence. Convergence will not be checked. \n" +
+            "Note: if using --global-optimization, ~25% of requested optimizations are used for the gloabal optimization.\n")
     while not converged:
         if not args.force_convergence:
             converged = True
 
         # Check if we can get a list of top fits
         if args.bestfit_p0 is not None: 
+            if "://" in args.bestfit_p0:
+                import urllib.request
+                best_fi = open("bestfits_file.bestfits","w")
+                with urllib.request.urlopen(args.bestfit_p0) as f:
+                    best_fi.write(f.read().decode('utf-8'))
+                best_fi.close()
+                args.bestfit_p0 = "bestfits_file.bestfits"
             bestfits = _top_opts(args.bestfit_p0)
             # args.p0 = bestfits[np.random.randint(len(bestfits)%10)]
         else:
             bestfits = None
 
         # Worker arguments, leave seed argmument out as it is added in as workers are created
         worker_args = [fs,
@@ -462,44 +513,44 @@
         from dadi_cli.BestFit import get_bestfit_params
 
         for _ in range(args.optimizations):
             if args.work_queue:
                 result = q.wait().output
             else:
                 result = out_queue.get()
+            num_opts += 1
             # Write latest result to file
             # Check that the log-likelihood is not a weird value
             if result[0] in [np.ma.core.MaskedConstant, np.inf]:
                 result = (-np.inf,) + result[1:]
 
             fid.write(
                 "{0}\t{1}\t{2}\n".format(
                     result[0], "\t".join(str(_) for _ in result[1]), result[2]
                 )
             )
             fid.flush()
-            if args.check_convergence or args.force_convergence:
+            if (args.check_convergence or args.force_convergence) and num_opts >= (args.check_convergence or args.force_convergence):
                 results_file = args.output_prefix + ".InferDM.bestfits"
                 result = get_bestfit_params(
                     path=args.output_prefix + ".InferDM.opts.*",
                     lbounds=args.lbounds,
                     ubounds=args.ubounds,
                     output=args.output_prefix + ".InferDM.bestfits",
                     delta=args.delta_ll,
                 )
                 if result is not None:
-                    args.force_convergence = False
+                    converged = True
                     break
+
         if not args.work_queue:
             # Stop the workers
             for worker in workers:
                 worker.terminate()
     fid.close()
-    if args.email is not None:
-        send_email(args.email, results_file)
     # TODO: Stop the remaining work_queue workers
 
 
 def run_infer_dfe(args):
     if "://" in args.fs:
         import urllib.request
         sfs_fi = open("sfs.fs","w")
@@ -508,14 +559,16 @@
         sfs_fi.close()
         args.fs ="sfs.fs"
 
     fs = dadi.Spectrum.from_file(args.fs)
     # Due to development history, much of the code expects a args.misid variable, so create it.
     args.misid = not (fs.folded or args.nomisid)
 
+    _make_dir(args.output_prefix)
+
     # # Things need to be updated for these to work
     if None not in [args.pdf1d, args.pdf2d]:
         pass
     else:
         for pdf in [args.pdf1d, args.pdf2d]:
             if pdf != None:
                 if not args.pdf_file and args.constants != -1:
@@ -532,26 +585,44 @@
                     )
 
     if args.p0 == -1:
         args.p0 = _calc_p0_from_bounds(args.lbounds, args.ubounds)
 
     from dadi_cli.utilities import get_opts_and_theta
 
+    if "://" in args.demo_popt:
+        import urllib.request
+        popt_fi = open("demo-popt.bestfits","w")
+        with urllib.request.urlopen(args.demo_popt) as f:
+            popt_fi.write(f.read().decode('utf-8'))
+        popt_fi.close()
+        args.demo_popt = "demo-popt.bestfits"
+
     _, theta = get_opts_and_theta(args.demo_popt)
     theta *= args.ratio
 
     import pickle
 
+
     if args.cache1d != None:
-        cache1d = pickle.load(open(args.cache1d, "rb"))
+        if "://" in args.cache1d:
+            from urllib.request import urlopen
+            cache1d = pickle.load(urlopen(args.cache1d))
+        else:
+            cache1d = pickle.load(open(args.cache1d, "rb"))
         cache_ns = cache1d.ns
     else:
         cache1d = args.cache1d
+
     if args.cache2d != None:
-        cache2d = pickle.load(open(args.cache2d, "rb"))
+        if "://" in args.cache2d:
+            from urllib.request import urlopen
+            cache2d = pickle.load(urlopen(args.cache2d))
+        else:
+            cache2d = pickle.load(open(args.cache2d, "rb"))
         cache_ns = cache2d.ns
     else:
         cache2d = args.cache2d
 
     if not np.all(cache_ns == fs.sample_sizes):
         raise ValueError('Cache and frequencey spectrum do not have the same sample sizes')
 
@@ -591,21 +662,39 @@
 
         ts = time.time()
         args.seed = int(time.time()) + int(os.getpid())
     import random
 
     np.random.seed(args.seed)
 
+    # Keep track of number of optimizations before checking convergence
+    num_opts = 0
+
+    # Keep track when optimization happens with force-convergence
     converged = False
+
+    # Raise warning if --check-convergence larger than --optimizations
+    # This isn't required for --force-convergence, as it optimizes until convergence occures.
+    if args.optimizations < args.check_convergence:
+        warnings.warn("WARNING: Number of optimizations is less than the number requested before checking convergence. Convergence will not be checked. \n" +
+            "Note: if using --global-optimization, ~25% of requested optimizations are used for the gloabal optimization.\n")
+
     while not converged:
         if not args.force_convergence:
             converged = True
 
         # Check if we can get a list of top fits
         if args.bestfit_p0 is not None: 
+            if "://" in args.bestfit_p0:
+                import urllib.request
+                best_fi = open("bestfits_file.bestfits","w")
+                with urllib.request.urlopen(args.bestfit_p0) as f:
+                    best_fi.write(f.read().decode('utf-8'))
+                best_fi.close()
+                args.bestfit_p0 = "bestfits_file.bestfits"
             bestfits = _top_opts(args.bestfit_p0)
         else:
             bestfits = None
 
         if args.work_queue:
             import work_queue as wq
 
@@ -701,31 +790,33 @@
                 len_params = len(args.p0)
                 if args.misid:
                     len_params - 1
                 if len_params == 3:
                     independent_selection = False
                 else:
                     independent_selection = True
+
         for _ in range(args.optimizations):
             if args.work_queue:
                 result = q.wait().output
             else:
                 result = out_queue.get()
+            num_opts += 1
             # Write latest result to file
             # Check that the log-likelihood is not a weird value
             # print('\n\n\n\n\n\nCACHE LL:',float(result[0]),'\n\n\n\n\n')
             if result[0] in [np.ma.core.MaskedConstant, np.inf]:
                 result = (-np.inf,) + result[1:]
             fid.write(
                 "{0}\t{1}\t{2}\n".format(
                     result[0], "\t".join(str(_) for _ in result[1]), result[2]
                 )
             )
             fid.flush()
-            if args.check_convergence or args.force_convergence:
+            if (args.check_convergence or args.force_convergence) and num_opts >= (args.check_convergence or args.force_convergence):
                 results_file = args.output_prefix + ".InferDFE.bestfits"
                 result = get_bestfit_params(
                     path=args.output_prefix + ".InferDFE.opts.*",
                     lbounds=args.lbounds,
                     ubounds=args.ubounds,
                     output=args.output_prefix + ".InferDFE.bestfits",
                     delta=args.delta_ll,
@@ -734,16 +825,14 @@
                     converged = True
                     break
         if not args.work_queue:
             # Stop the workers
             for worker in workers:
                 worker.terminate()
     fid.close()
-    if args.email is not None:
-        send_email(args.email, results_file)
 
 def run_bestfit(args):
     from dadi_cli.BestFit import get_bestfit_params
 
     get_bestfit_params(
         path=args.input_prefix + ".opts.*",
         delta=args.delta_ll,
@@ -752,25 +841,43 @@
         output=args.input_prefix + ".bestfits",
     )
 
 
 def run_stat_demography(args):
     from dadi_cli.Stat import godambe_stat_demograpy
 
-    if args.model_file is not None:
-        if "://" in args.model_file:
-            model_fi = open("dadi_models.py","w")
-            with urllib.request.urlopen(args.model_file) as f:
-                model_fi.write(f.read().decode('utf-8'))
-            model_fi.close()
-            args.model_file = "dadi_models"
+    # # Code kept just in case user requests functionality if the future
+    # if args.fs is not None:
+    #     if "://" in args.fs:
+    #         import urllib.request
+    #         sfs_fi = open("sfs.fs","w")
+    #         with urllib.request.urlopen(args.fs) as f:
+    #             sfs_fi.write(f.read().decode('utf-8'))
+    #         sfs_fi.close()
+    #         args.fs ="sfs.fs"
+    # if args.model_file is not None:
+    #     if "://" in args.model_file:
+    #         model_fi = open("dadi_models.py","w")
+    #         with urllib.request.urlopen(args.model_file) as f:
+    #             model_fi.write(f.read().decode('utf-8'))
+    #         model_fi.close()
+    #         args.model_file = "dadi_models"
+    # if args.demo_popt is not None:
+    #     if "://" in args.model_file:
+    #         model_fi = open("demo_popt.bestfits","w")
+    #         with urllib.request.urlopen(args.model_file) as f:
+    #             model_fi.write(f.read().decode('utf-8'))
+    #         model_fi.close()
+    #         args.model_file = "demo_popt.bestfits"
 
     # Extract model function, from custom model_file if necessary
     func, _ = get_model(args.model, args.model_file)
 
+    _make_dir(args.output)
+
     godambe_stat_demograpy(
         fs=args.fs,
         func=func,
         bootstrap_dir=args.bootstrapping_dir,
         grids=args.grids,
         nomisid=args.nomisid,
         demo_popt=args.demo_popt,
@@ -779,14 +886,33 @@
         output=args.output,
     )
 
 
 def run_stat_dfe(args):
     from dadi_cli.Stat import godambe_stat_dfe
 
+    # # Code kept just in case user requests functionality if the future
+    # if args.fs is not None:
+    #     if "://" in args.fs:
+    #         import urllib.request
+    #         sfs_fi = open("sfs.fs","w")
+    #         with urllib.request.urlopen(args.fs) as f:
+    #             sfs_fi.write(f.read().decode('utf-8'))
+    #         sfs_fi.close()
+    #         args.fs ="sfs.fs"
+    # if args.dfe_popt is not None:
+    #     if "://" in args.model_file:
+    #         model_fi = open("dfe_popt.bestfits","w")
+    #         with urllib.request.urlopen(args.model_file) as f:
+    #             model_fi.write(f.read().decode('utf-8'))
+    #         model_fi.close()
+    #         args.model_file = "dfe_popt.bestfits"
+
+    _make_dir(args.output)
+
     godambe_stat_dfe(
         fs=args.fs,
         bootstrap_non_dir=args.bootstrapping_non_dir,
         bootstrap_syn_dir=args.bootstrapping_syn_dir,
         cache1d=args.cache1d,
         cache2d=args.cache2d,
         sele_dist=args.pdf1d,
@@ -804,24 +930,51 @@
         plot_comparison,
         plot_fitted_demography,
         plot_fitted_dfe,
         plot_single_sfs,
         plot_mut_prop,
     )
 
+    # # Code kept just in case user requests functionality if the future
+    # if args.fs is not None:
+    #     if "://" in args.fs:
+    #         import urllib.request
+    #         sfs_fi = open("sfs.fs","w")
+    #         with urllib.request.urlopen(args.fs) as f:
+    #             sfs_fi.write(f.read().decode('utf-8'))
+    #         sfs_fi.close()
+    #         args.fs ="sfs.fs"
+    # if args.model_file is not None:
+    #     if "://" in args.model_file:
+    #         model_fi = open("dadi_models.py","w")
+    #         with urllib.request.urlopen(args.model_file) as f:
+    #             model_fi.write(f.read().decode('utf-8'))
+    #         model_fi.close()
+    #         args.model_file = "dadi_models"
+    # if args.demo_popt is not None:
+    #     if "://" in args.model_file:
+    #         model_fi = open("demo_popt.bestfits","w")
+    #         with urllib.request.urlopen(args.model_file) as f:
+    #             model_fi.write(f.read().decode('utf-8'))
+    #         model_fi.close()
+    #         args.model_file = "demo_popt.bestfits"
+    # if args.dfe_popt is not None:
+    #     if "://" in args.model_file:
+    #         model_fi = open("dfe_popt.bestfits","w")
+    #         with urllib.request.urlopen(args.model_file) as f:
+    #             model_fi.write(f.read().decode('utf-8'))
+    #         model_fi.close()
+    #         args.model_file = "dfe_popt.bestfits"
+
+    _make_dir(args.output)
+
     if args.fs == None:
-        if args.ratio == False:
-            raise Exception("Need to pass value to --ratio option")
         plot_mut_prop(
+            pdf=args.pdf1d,
             dfe_popt=args.dfe_popt,
-            pdf1d=args.pdf1d,
-            nomisid=args.nomisid,
-            mut_rate=args.mut_rate,
-            seq_len=args.seq_len,
-            ratio=args.ratio,
             output=args.output,
         )
     elif args.dfe_popt != None:
         plot_fitted_dfe(
             fs=args.fs,
             cache1d=args.cache1d,
             cache2d=args.cache2d,
@@ -833,21 +986,14 @@
             resid_range=args.resid_range,
             projections=args.projections,
             output=args.output,
         )
     elif args.demo_popt != None:
         if args.model is None:
             raise ValueError("--model is missing")
-        if args.model_file is not None:
-            if "://" in args.model_file:
-                model_fi = open("dadi_models.py","w")
-                with urllib.request.urlopen(args.model_file) as f:
-                    model_fi.write(f.read().decode('utf-8'))
-                model_fi.close()
-                args.model_file = "dadi_models"
         func, _ = get_model(args.model, args.model_file)
         plot_fitted_demography(
             fs=args.fs,
             func=func,
             popt=args.demo_popt,
             vmin=args.vmin,
             projections=args.projections,
@@ -888,22 +1034,22 @@
 
 def add_output_argument(parser):
     parser.add_argument(
         "--output", type=str, required=True, help="Name of the output file."
     )
 
 def add_bounds_argument(parser):
-    # Check that the model is not a 
+    # Check that the model is not a standard neutral model
     if 'snm_1d' not in sys.argv and 'snm_2d' not in sys.argv:
         boundary_req = True
     else:
-        if '--p0' in sys.argv:
-            boundary_req = True
-        else:
+        if '--nomisid' in sys.argv:
             boundary_req = False
+        else:
+            boundary_req = True
     parser.add_argument(
         "--lbounds",
         type=float,
         nargs="+",
         required=boundary_req,
         help="Lower bounds of the optimized parameters.",
     )
@@ -913,29 +1059,33 @@
         nargs="+",
         required=boundary_req,
         help="Upper bounds of the optimized parameters.",
     )
 
 
 def add_demo_popt_argument(parser):
+    # Check that the model is not a standard neutral model
+    bestfit_req = False
+    if 'equil' not in sys.argv:
+        bestfit_req = True
     parser.add_argument(
         "--demo-popt",
         type=str,
-        required=True,
+        required=bestfit_req,
         help="File containing the bestfit parameters for the demographic model.",
         dest="demo_popt",
     )
 
 
 def add_grids_argument(parser):
     parser.add_argument(
         "--grids",
         type=_check_positive_int,
         nargs=3,
-        help="Sizes of grids. Default: None.",
+        help="Sizes of grids. Default is based on sample size.",
     )
 
 
 def add_misid_argument(parser):
     # Note that the code previously had a --misid function that did the opposite, but this ia more sensible default.
     parser.add_argument(
         "--nomisid",
@@ -1081,41 +1231,35 @@
         "--optimizations",
         default=100,
         type=_check_positive_int,
         help="Total number of optimizations to run. Default: 100.",
     )
     parser.add_argument(
         "--check-convergence",
-        default=False,
-        action="store_true",
+        default=0,
+        type=_check_positive_int,
         dest="check_convergence",
-        help="Stop optimization runs when convergence criteria are reached. BestFit results file will be call <output_prefix>.InferDM.bestfits. Default: False.",
+        help="Start checking for convergence after a chosen number of optimizations. Stop optimization runs when convergence criteria are reached. BestFit results file will be call <output_prefix>.InferDM.bestfits. Convergence not checked by default.",
     )
     parser.add_argument(
         "--force-convergence",
-        default=False,
-        action="store_true",
+        default=0,
+        type=_check_positive_int,
         dest="force_convergence",
-        help="Only stop optimization once convergence criteria is reached. BestFit results file will be call <output_prefix>.InferDM.bestfits. Default: False.",
+        help="Start checking for convergence after a chosen number of optimizations. Only stop optimization once convergence criteria is reached. BestFit results file will be call <output_prefix>.InferDM.bestfits. Convergence not checked by default.",
     )
     parser.add_argument(
         "--work-queue",
         nargs=2,
         default=[],
         action="store",
         dest="work_queue",
         help="Enable Work Queue. Additional arguments are the WorkQueue project name, the name of the password file.",
     )
     parser.add_argument(
-        "--email",
-        type=str,
-        dest="email",
-        help="Enter user email address for terraform to send inference results to user.",
-    )
-    parser.add_argument(
         "--port",
         default=9123,
         type=_check_positive_int,
         dest="port",
         help="Choose a specific port for Work Queue communication. Default 9123.",
     )
     parser.add_argument(
@@ -1153,19 +1297,26 @@
         "--bestfit-p0-file", 
         type=str, 
         dest="bestfit_p0", 
         help="Pass in a .bestfit or .opt.<N> file name to cycle --p0 between up to the top 10 best fits for each optimization."
     )
 
 def add_p0_argument(parser):
+    p0_req = False
+    if 'snm_1d' not in sys.argv and 'snm_2d' not in sys.argv:
+        p0_req = True
+    else:
+        if '--nomisid' not in sys.argv:
+            p0_req = True
+
     parser.add_argument(
         "--p0",
         type=float,
         nargs="+",
-        required=True,
+        required=p0_req,
         help="Parameters for simulated demography or dfe.",
     )
 
 
 def dadi_cli_parser():
     top_parser = argparse.ArgumentParser()
     subparsers = top_parser.add_subparsers(dest="subcommand")
@@ -1411,38 +1562,30 @@
     add_misid_argument(parser)
     add_constant_argument(parser)
     add_bounds_argument(parser)
     add_seed_argument(parser)
     parser.set_defaults(runner=run_infer_dfe)
 
     parser = subparsers.add_parser("Plot", help="Plot 1D/2D frequency spectrum.")
-    add_fs_argument(parser)
+    parser.add_argument(
+        "--fs",
+        type=str,
+        help="Frequency spectrum of mutations used for inference. To generate the frequency spectrum, please use `dadi-cli GenerateFs`. Can be an HTML link.",
+    )
     parser.add_argument(
         "--fs2",
         type=str,
         help="Name of the second frequency spectrum for comparison, generated by `dadi-cli GenerateFs`.",
     )
     add_popt_argument(parser)
     add_model_argument(parser)
     add_dfe_argument(parser)
     add_misid_argument(parser)
     add_output_argument(parser)
     parser.add_argument(
-        "--mut-rate",
-        type=float,
-        dest="mut_rate",
-        help="Mutation rate for estimating the ancestral population size.",
-    )
-    parser.add_argument(
-        "--seq-len",
-        type=int,
-        dest="seq_len",
-        help="Sequence length for estimating the ancestral population size.",
-    )
-    parser.add_argument(
         "--projections", type=int, nargs="+", help="Sample sizes after projection."
     )
     parser.add_argument(
         "--resid-range",
         type=float,
         dest="resid_range",
         help="Ranges of the residual plots.",
@@ -1534,15 +1677,28 @@
     parser.add_argument(
         "--input-prefix",
         type=str,
         required=True,
         dest="input_prefix",
         help='Prefix for input files, which is named <input-prefix ending with ".InferDM">.opts.<N> or <input-prefix ending with "InferDFE">.opts.<N>, containing the inferred demographic or DFE parameters.',
     )
-    add_bounds_argument(parser)
+    parser.add_argument(
+        "--lbounds",
+        type=float,
+        nargs="+",
+        required=False,
+        help="Lower bounds of the optimized parameters.",
+    )
+    parser.add_argument(
+        "--ubounds",
+        type=float,
+        nargs="+",
+        required=False,
+        help="Upper bounds of the optimized parameters.",
+    )
     add_delta_ll_argument(parser)
     parser.set_defaults(runner=run_bestfit)
 
     parser = subparsers.add_parser(
         "Model", help="Display available demographic models."
     )
     parser.add_argument(
@@ -1649,93 +1805,65 @@
 
 
 def _calc_p0_from_bounds(lb, ub):
     p0 = []
     for l, u in zip(lb, ub):
         if l == 0:
             p0.append((l + u) / 2)
-        else:
+        elif l*u > 0:
             p0.append(np.sqrt(l * u))
+        else:
+            p0.append((l+u) / 2)
+
     return p0
 
 
-def _check_dir(path):
+def _make_dir(path):
     parent_dir = os.path.dirname(path)
-    if not os.path.isdir(parent_dir):
-        raise argparse.ArgumentTypeError("directory %s does not exist" % parent_dir)
-    return path
+    if parent_dir != '':
+        os.makedirs(parent_dir, exist_ok=True)
+
 
 def _top_opts(filename):
     """
     Description:
         Obtains optimized parameters and theta.
 
     Arguments:
         filename str: Name of the file.
 
     Returns:
         opts list: Optimized parameters.
         theta float: Population-scaled mutation rate.
     """
-    opts = []
-    is_here = False
     fid = open(filename, 'r')
     for line in fid.readlines():
-        if line.startswith('# Top'):
-            is_here = True
+        if line.startswith('# Log'):
+            # Reset opts variable to avoid repeating entries.
+            opts = []
+            continue
+        elif line.startswith('#'):
             continue
-        elif line.startswith('#'): continue
         else:
             try:
                 opts.append([float(_) for _ in line.rstrip().split("\t")])
             except ValueError:
                 pass
     fid.close()
 
-    opts = [opt[1:-1] for opt in opts]
+    try:
+        # Sort entries by log-likelihood
+        opts = np.array(sorted(opts, reverse=True))
+        # Remove log-likelihood and theta
+        opts = [opt[1:-1] for opt in opts]
+    except UnboundLocalError: 
+        raise ValueError(f"Fits not found in file {filename}.")
 
-    if not is_here: print('No file found.')
     return opts
 
-from os.path import basename
-import smtplib
-from email.mime.multipart import MIMEMultipart
-from email.mime.text import MIMEText
-from email.mime.application import MIMEApplication
-
-def send_email(user_email, results_file):
-    #The mail addresses and password
-    sender_address = "dadi.results@gmail.com"
-    sender_pass = "yfjbdeaijwaosdck"
-    #Setup the MIME
-    message = MIMEMultipart()
-    message['From'] = sender_address
-    message['To'] = user_email
-    message['Subject'] = 'Dadi-cli results for ' + results_file   #The subject line
-    #The body and the attachments for the mail
-    message.attach(MIMEText('', 'plain'))
-
-
-    with open(results_file, "rb") as res:
-        part = MIMEApplication(
-            res.read(),
-            Name=basename(results_file)
-        )
-    # After the file is closed
-    part['Content-Disposition'] = 'attachment; filename="%s"' % basename(results_file)
-    message.attach(part)
-
-    #Create SMTP session for sending the mail
-    session = smtplib.SMTP('smtp.gmail.com', 587) #use gmail with port
-    session.starttls() #enable security
-    session.login(sender_address, sender_pass) #login with mail_id and password
-    text = message.as_string()
-    session.sendmail(sender_address, user_email, text)
-    session.quit()
-    print('Mail Sent')
 
 # Main function
 def main(arg_list=None):
     set_sigpipe_handler()
     parser = dadi_cli_parser()
     args = parser.parse_args(arg_list)
     args.runner(args)
```

### Comparing `dadi_cli-0.8.1/dadi_cli/utilities.py` & `dadi_cli-0.9.1/dadi_cli/utilities.py`

 * *Files identical despite different names*

### Comparing `dadi_cli-0.8.1/LICENSE` & `dadi_cli-0.9.1/LICENSE`

 * *Files identical despite different names*

