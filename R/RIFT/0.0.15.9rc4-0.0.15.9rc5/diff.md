# Comparing `tmp/RIFT-0.0.15.9rc4.tar.gz` & `tmp/RIFT-0.0.15.9rc5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "RIFT-0.0.15.9rc4.tar", last modified: Mon Jun 19 13:22:14 2023, max compression
+gzip compressed data, was "RIFT-0.0.15.9rc5.tar", last modified: Wed Jun 28 10:21:01 2023, max compression
```

## Comparing `RIFT-0.0.15.9rc4.tar` & `RIFT-0.0.15.9rc5.tar`

### file list

```diff
@@ -1,193 +1,193 @@
-drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-19 13:22:14.535797 RIFT-0.0.15.9rc4/
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1042 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/AUTOMATED_OR_ONLINE.md
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1755 2023-04-20 10:32:56.000000 RIFT-0.0.15.9rc4/Dockerfile
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    22146 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/GETTING_STARTED.md
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3557 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/INSTALL.md
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1364 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/INSTALL_OPTIONAL_DEPENDENCIES.md
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1118 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/LICENSE.md
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      204 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MANIFEST.in
-drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-19 13:22:12.049787 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/
-drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-19 13:22:12.214788 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/
-drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-19 13:22:12.770790 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      173 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/__init__.py
-drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-19 13:22:12.830790 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/calmarg/
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)       22 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/calmarg/__init__.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6265 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/calmarg/rift_source.py
-drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-19 13:22:13.192791 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    18724 2023-04-16 18:23:39.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/MonteCarloEnsemble.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/__init__.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2592 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/direct_quadrature.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    20255 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/gaussian_mixture_model.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    53572 2023-05-30 17:28:25.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/mcsampler.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    28350 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/mcsamplerEnsemble.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    69417 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/mcsamplerGPU.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2901 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/multivariate_truncnorm.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     7235 2022-10-24 14:00:10.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/statutils.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    33113 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/weighted_gmm.py
-drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-19 13:22:13.211791 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     9944 2022-10-23 22:26:00.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/BayesianLeastSquares.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3835 2022-10-23 22:26:00.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/ConstrainedQuadraticLikelihood.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/__init__.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2658 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/efficient_save_sklearn_gp.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1655 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/gp.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2518 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/gpytorch_wrapper.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5558 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/internal_GP.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3488 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/interp_gpu.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    26826 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/senni.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)   249727 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/lalsimutils.py
-drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-19 13:22:13.230791 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1643 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/Q_inner_product.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    33438 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/SphericalHarmonics_gpu.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/__init__.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1525 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/cuda_Q_inner_product.cu
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    94340 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/factored_likelihood.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5269 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/optimized_gpu_tools.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1451 2023-05-30 17:28:25.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/priors_utils.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     4616 2023-06-07 15:16:25.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/vectorized_general_tools.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     4706 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/vectorized_lal_tools.py
-drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-19 13:22:13.790794 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    70947 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/ModifiedScikitFit.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)       65 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/__init__.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    29427 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/amrlib.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     7367 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/bounded_kde.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      229 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/common_cl.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)   109345 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/dag_utils.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     9324 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/modules.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    23083 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/our_corner.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    30542 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/ourparams.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    10915 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/samples_utils.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2901 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/sky_rotations.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    10623 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/spokes.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6975 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/tools.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2641 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/weight_simulations.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     8651 2023-05-30 17:28:25.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/xmlutils.py
-drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-19 13:22:13.824794 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    26126 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/EOBTidalExternal.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    31276 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/EOBTidalExternalC.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    63809 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/EOSManager.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     4776 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/GWSignal.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2654 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/MonotonicSpline.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    19507 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/PrecessingFisherMatrix.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    52302 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/ROMWaveformManager.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)       68 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/__init__.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    23733 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/effectiveFisher.py
-drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-19 13:22:12.781790 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT.egg-info/
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6360 2023-06-19 13:22:09.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT.egg-info/PKG-INFO
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    10749 2023-06-19 13:22:09.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT.egg-info/SOURCES.txt
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        1 2023-06-19 13:22:09.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT.egg-info/dependency_links.txt
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      142 2023-06-19 13:22:09.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT.egg-info/requires.txt
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        5 2023-06-19 13:22:09.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT.egg-info/top_level.txt
-drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-19 13:22:14.526797 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     8723 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/assess_propose_CIP_convergence_sequence.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    13848 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/calibration_reweighting.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2371 2023-04-22 14:25:02.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/combine_weights_and_rejection_sample.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2800 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/config_yank.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6140 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convergence_test_amr.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     9039 2023-06-07 15:16:25.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convergence_test_samples.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2239 2023-04-20 10:32:56.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_ascii_framechange_xphm.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1224 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_dat_to_hdf5.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1920 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_output_format_allnet2xml
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      541 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_output_format_ascii2h5.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    11799 2023-03-12 13:15:08.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_output_format_ile2inference
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     8166 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_output_format_inference2ile
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2013 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_psd_ascii2xml
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     9065 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_CIP_convergence_sequence.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    33506 2023-04-07 18:24:37.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_eos_posterior_pipeline
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    14569 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_event_dag_via_grid
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    88335 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_event_parameter_pipeline_AlternateIteration
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)   120192 2023-04-25 00:19:30.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_event_parameter_pipeline_BasicIteration
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    71601 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_event_parameter_pipeline_BasicMultiApproxIteration
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2768 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_ile_sub_dag.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    13979 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_postprocessing_event_dag.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    98022 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/helper_LDG_Events.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1886 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/helper_OnlinePSDCleanup.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    20152 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/ile_postproc_add_time
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    83560 2023-03-12 13:15:08.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/integrate_likelihood_extrinsic
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)   103850 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/integrate_likelihood_extrinsic_batchmode
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    18630 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/integrate_likelihood_extrinsic_no-op
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5408 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/make_uni_comov_skymap.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    37925 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/plot_posterior_corner.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3746 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/resample_uniform_comoving.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      354 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/switcheroo
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    34265 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_AMRGrid.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3696 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_AdaptiveExponent.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    18544 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_AnalyticFisherGrid.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     7348 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_BatchConvertResampleILEOutput.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1028 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CIPdagPostprocess.sh
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      219 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CacheFileConvert.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1436 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CharacterizePosterior.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3934 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CleanILE.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      876 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CoincIFOUtility.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    15127 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CompareWaveformsInDetectors.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      853 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ConsolidateDAGsUnderMaster.sh
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    10380 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ConstructBNSMarginalEOSRank.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    33198 2023-04-07 18:24:37.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ConstructEOSPosterior.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    55368 2022-11-28 22:41:57.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ConstructIntrinsicPosterior_GaussianResampling.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)   164113 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ConstructIntrinsicPosterior_GenericCoordinates.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2314 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CoordinateNamesAngularToCartesianSpins.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     9633 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_EOBTideWriteFrame.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      389 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_EstimateWaveformDuration.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3250 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_FetchExternalGrid.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    27796 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_FitAndEvaluate_GenericCoordinates.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      256 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ForOSG_MakeLocalFramesDir.sh
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1640 2023-03-12 13:15:08.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ForOSG_MakeTruncatedLocalFramesDir.sh
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3266 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_FrameZeroNoiseSNR.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    11553 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_GenerateMaxlnLWaveform.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6162 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_GenerateMaxlnLWaveform_NRFromIndex.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2223 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_GridRecenter.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    13919 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_GridSubsetOfTemplateBank.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2778 2023-04-07 18:24:37.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_HyperCombine.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1590 2023-04-07 18:24:37.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_HyperparameterGrid.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5156 2023-04-07 18:24:37.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_HyperparameterPuffball.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      829 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ILENextGeneration.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1018 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ILEROMdagPostprocess.sh
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1597 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ILEdagPostprocess.sh
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6780 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_InitMargTable
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     4553 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_IntermediateEOSIntegralFromFit.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    40228 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_IterativeFisher.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2698 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_JoinXML.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     8109 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_LALCompareApproximantsOnSamples.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     7660 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_LALWriteFrame.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    50356 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ManualOverlapGrid.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     7195 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_MarginalizedLikelihoodEOSIntegralFromIntermediate.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1214 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_MassGrid.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2450 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_MassGridCoalesce.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     8821 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRBestOfIndex.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6671 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRDumpDetectorResponse.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    20394 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRExtrudeOverlapGrid.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5672 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRIndexedFminCutToILE.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    10752 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRNearestSimulationTo.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     4794 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRRelabelILE.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     9830 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRWriteFrame.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3377 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NR_GWMemory.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1490 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRdagPostprocess.sh
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2349 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ParameterFilter.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    12414 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ParameterPuffball.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3665 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ParameterRandomize.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1087 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_PosteriorPostprocess.sh
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3302 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_PrintInjection.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5424 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_RIFT_MultiMetaPipe.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    79435 2023-06-07 15:16:25.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_RIFT_pseudo_pipe.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    35804 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_RIFT_pseudo_pipe_lowlatency.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6293 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ROMWriteFrame.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1675 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_RandomizeOverlapOrder.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3080 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ResampleILEOutputWithExtrinsic.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3792 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_SimInspiralToCoinc.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     7587 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_TEOBResumSWriteFrame.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     4982 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_TestSpokesIO.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      814 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_TestXMLParameterStorage.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    11254 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_TidalPlotSimulationStrain.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      457 2022-10-15 00:56:03.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_TruncateMergeFrames.py
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3430 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_WriteFrameAndCacheFromXML.sh
--rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2784 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_WriteInjectionFile.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1955 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_WriteXMLWithEOS.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      276 2023-04-22 14:25:02.000000 RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_shuffle_file.py
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3488 2022-09-24 12:18:48.000000 RIFT-0.0.15.9rc4/PACKAGING.md
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6360 2023-06-19 13:22:14.534797 RIFT-0.0.15.9rc4/PKG-INFO
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5821 2023-04-07 18:24:37.000000 RIFT-0.0.15.9rc4/README.md
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6132 2022-09-24 12:18:48.000000 RIFT-0.0.15.9rc4/TROUBLESHOOTING.md
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6136 2022-09-24 12:18:48.000000 RIFT-0.0.15.9rc4/howto.md
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)       96 2023-04-24 19:45:36.000000 RIFT-0.0.15.9rc4/pyproject.toml
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      184 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc4/requirements.txt
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)       38 2023-06-19 13:22:14.535797 RIFT-0.0.15.9rc4/setup.cfg
--rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2934 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc4/setup.py
+drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-28 10:21:01.986682 RIFT-0.0.15.9rc5/
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1042 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/AUTOMATED_OR_ONLINE.md
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1755 2023-04-20 10:32:56.000000 RIFT-0.0.15.9rc5/Dockerfile
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    22146 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/GETTING_STARTED.md
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3557 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/INSTALL.md
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1364 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/INSTALL_OPTIONAL_DEPENDENCIES.md
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1118 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/LICENSE.md
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      204 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MANIFEST.in
+drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-28 10:21:01.493681 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/
+drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-28 10:21:01.499681 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/
+drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-28 10:21:01.541681 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      173 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/__init__.py
+drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-28 10:21:01.558681 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/calmarg/
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)       22 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/calmarg/__init__.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6265 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/calmarg/rift_source.py
+drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-28 10:21:01.587681 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    18724 2023-04-16 18:23:39.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/MonteCarloEnsemble.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/__init__.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2592 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/direct_quadrature.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    20255 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/gaussian_mixture_model.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    53572 2023-05-30 17:28:25.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/mcsampler.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    28350 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/mcsamplerEnsemble.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    69417 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/mcsamplerGPU.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2901 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/multivariate_truncnorm.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     7235 2022-10-24 14:00:10.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/statutils.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    33113 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/weighted_gmm.py
+drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-28 10:21:01.612681 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     9944 2022-10-23 22:26:00.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/BayesianLeastSquares.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3835 2022-10-23 22:26:00.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/ConstrainedQuadraticLikelihood.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/__init__.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2658 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/efficient_save_sklearn_gp.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1655 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/gp.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2518 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/gpytorch_wrapper.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5558 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/internal_GP.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3488 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/interp_gpu.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    26826 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/senni.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)   249803 2023-06-28 10:20:41.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/lalsimutils.py
+drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-28 10:21:01.638681 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1643 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/Q_inner_product.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    33438 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/SphericalHarmonics_gpu.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/__init__.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1525 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/cuda_Q_inner_product.cu
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    94340 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/factored_likelihood.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5269 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/optimized_gpu_tools.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1451 2023-05-30 17:28:25.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/priors_utils.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     4616 2023-06-07 15:16:25.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/vectorized_general_tools.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     4706 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/vectorized_lal_tools.py
+drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-28 10:21:01.676681 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    70947 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/ModifiedScikitFit.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)       65 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/__init__.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    29427 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/amrlib.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     7367 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/bounded_kde.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      229 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/common_cl.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)   109345 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/dag_utils.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     9324 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/modules.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    23083 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/our_corner.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    30542 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/ourparams.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    10915 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/samples_utils.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2901 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/sky_rotations.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    10623 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/spokes.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6975 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/tools.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2641 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/weight_simulations.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     8651 2023-05-30 17:28:25.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/xmlutils.py
+drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-28 10:21:01.703681 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    26126 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/EOBTidalExternal.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    31276 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/EOBTidalExternalC.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    63809 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/EOSManager.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     4776 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/GWSignal.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2654 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/MonotonicSpline.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    19507 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/PrecessingFisherMatrix.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    52302 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/ROMWaveformManager.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)       68 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/__init__.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    23733 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/effectiveFisher.py
+drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-28 10:21:01.554681 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT.egg-info/
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6360 2023-06-28 10:20:58.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT.egg-info/PKG-INFO
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    10749 2023-06-28 10:20:59.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT.egg-info/SOURCES.txt
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        1 2023-06-28 10:20:58.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT.egg-info/dependency_links.txt
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      142 2023-06-28 10:20:58.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT.egg-info/requires.txt
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        5 2023-06-28 10:20:58.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT.egg-info/top_level.txt
+drwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)        0 2023-06-28 10:21:01.983682 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     8723 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/assess_propose_CIP_convergence_sequence.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    13848 2023-05-24 11:46:08.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/calibration_reweighting.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2371 2023-04-22 14:25:02.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/combine_weights_and_rejection_sample.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2800 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/config_yank.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6140 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convergence_test_amr.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     9039 2023-06-07 15:16:25.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convergence_test_samples.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2239 2023-04-20 10:32:56.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_ascii_framechange_xphm.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1224 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_dat_to_hdf5.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1920 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_output_format_allnet2xml
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      541 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_output_format_ascii2h5.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    11799 2023-03-12 13:15:08.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_output_format_ile2inference
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     8166 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_output_format_inference2ile
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2013 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_psd_ascii2xml
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     9065 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_CIP_convergence_sequence.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    33867 2023-06-28 10:20:41.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_eos_posterior_pipeline
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    14569 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_event_dag_via_grid
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    88335 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_event_parameter_pipeline_AlternateIteration
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)   120596 2023-06-28 10:20:41.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_event_parameter_pipeline_BasicIteration
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    71601 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_event_parameter_pipeline_BasicMultiApproxIteration
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2768 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_ile_sub_dag.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    13979 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_postprocessing_event_dag.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    98022 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/helper_LDG_Events.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1886 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/helper_OnlinePSDCleanup.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    20152 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/ile_postproc_add_time
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    83560 2023-03-12 13:15:08.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/integrate_likelihood_extrinsic
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)   103850 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/integrate_likelihood_extrinsic_batchmode
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    18630 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/integrate_likelihood_extrinsic_no-op
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5408 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/make_uni_comov_skymap.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    38440 2023-06-28 10:20:41.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/plot_posterior_corner.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3746 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/resample_uniform_comoving.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      354 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/switcheroo
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    34265 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_AMRGrid.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3696 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_AdaptiveExponent.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    18544 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_AnalyticFisherGrid.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     7348 2023-06-19 13:21:23.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_BatchConvertResampleILEOutput.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1028 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CIPdagPostprocess.sh
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      219 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CacheFileConvert.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1436 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CharacterizePosterior.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3934 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CleanILE.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      876 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CoincIFOUtility.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    15127 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CompareWaveformsInDetectors.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      853 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ConsolidateDAGsUnderMaster.sh
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    10380 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ConstructBNSMarginalEOSRank.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    33309 2023-06-28 10:20:41.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ConstructEOSPosterior.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    55368 2022-11-28 22:41:57.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ConstructIntrinsicPosterior_GaussianResampling.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)   164169 2023-06-28 10:20:41.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ConstructIntrinsicPosterior_GenericCoordinates.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2314 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CoordinateNamesAngularToCartesianSpins.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     9633 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_EOBTideWriteFrame.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      389 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_EstimateWaveformDuration.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3250 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_FetchExternalGrid.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    27796 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_FitAndEvaluate_GenericCoordinates.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      256 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ForOSG_MakeLocalFramesDir.sh
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1640 2023-03-12 13:15:08.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ForOSG_MakeTruncatedLocalFramesDir.sh
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3266 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_FrameZeroNoiseSNR.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    11553 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_GenerateMaxlnLWaveform.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6162 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_GenerateMaxlnLWaveform_NRFromIndex.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2223 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_GridRecenter.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    13919 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_GridSubsetOfTemplateBank.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2778 2023-04-07 18:24:37.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_HyperCombine.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1590 2023-04-07 18:24:37.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_HyperparameterGrid.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5168 2023-06-28 10:20:41.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_HyperparameterPuffball.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      829 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ILENextGeneration.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1018 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ILEROMdagPostprocess.sh
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1597 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ILEdagPostprocess.sh
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6780 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_InitMargTable
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     4553 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_IntermediateEOSIntegralFromFit.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    40228 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_IterativeFisher.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2698 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_JoinXML.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     8109 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_LALCompareApproximantsOnSamples.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     7660 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_LALWriteFrame.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    50356 2022-10-11 14:57:54.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ManualOverlapGrid.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     7195 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_MarginalizedLikelihoodEOSIntegralFromIntermediate.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1214 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_MassGrid.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2450 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_MassGridCoalesce.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     8821 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRBestOfIndex.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6671 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRDumpDetectorResponse.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    20394 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRExtrudeOverlapGrid.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5672 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRIndexedFminCutToILE.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    10752 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRNearestSimulationTo.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     4794 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRRelabelILE.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     9830 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRWriteFrame.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3377 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NR_GWMemory.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1490 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRdagPostprocess.sh
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2349 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ParameterFilter.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    12414 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ParameterPuffball.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3665 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ParameterRandomize.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1087 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_PosteriorPostprocess.sh
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3302 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_PrintInjection.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5424 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_RIFT_MultiMetaPipe.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    79440 2023-06-28 10:20:41.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_RIFT_pseudo_pipe.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    35804 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_RIFT_pseudo_pipe_lowlatency.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6293 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ROMWriteFrame.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1675 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_RandomizeOverlapOrder.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3080 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ResampleILEOutputWithExtrinsic.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3792 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_SimInspiralToCoinc.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     7587 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_TEOBResumSWriteFrame.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     4982 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_TestSpokesIO.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      814 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_TestXMLParameterStorage.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)    11254 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_TidalPlotSimulationStrain.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      457 2022-10-15 00:56:03.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_TruncateMergeFrames.py
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3430 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_WriteFrameAndCacheFromXML.sh
+-rwxrwxr-x   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2784 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_WriteInjectionFile.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     1955 2022-09-24 12:18:47.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_WriteXMLWithEOS.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      276 2023-04-22 14:25:02.000000 RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_shuffle_file.py
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     3488 2022-09-24 12:18:48.000000 RIFT-0.0.15.9rc5/PACKAGING.md
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6360 2023-06-28 10:21:01.985682 RIFT-0.0.15.9rc5/PKG-INFO
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     5821 2023-04-07 18:24:37.000000 RIFT-0.0.15.9rc5/README.md
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6132 2022-09-24 12:18:48.000000 RIFT-0.0.15.9rc5/TROUBLESHOOTING.md
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     6136 2022-09-24 12:18:48.000000 RIFT-0.0.15.9rc5/howto.md
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)       96 2023-04-24 19:45:36.000000 RIFT-0.0.15.9rc5/pyproject.toml
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)      184 2023-03-24 18:44:03.000000 RIFT-0.0.15.9rc5/requirements.txt
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)       38 2023-06-28 10:21:01.987682 RIFT-0.0.15.9rc5/setup.cfg
+-rw-rw-r--   0 richard.oshaughnessy (40428) richard.oshaughnessy (40428)     2934 2023-06-28 10:20:41.000000 RIFT-0.0.15.9rc5/setup.py
```

### Comparing `RIFT-0.0.15.9rc4/AUTOMATED_OR_ONLINE.md` & `RIFT-0.0.15.9rc5/AUTOMATED_OR_ONLINE.md`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/Dockerfile` & `RIFT-0.0.15.9rc5/Dockerfile`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/GETTING_STARTED.md` & `RIFT-0.0.15.9rc5/GETTING_STARTED.md`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/INSTALL.md` & `RIFT-0.0.15.9rc5/INSTALL.md`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/INSTALL_OPTIONAL_DEPENDENCIES.md` & `RIFT-0.0.15.9rc5/INSTALL_OPTIONAL_DEPENDENCIES.md`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/LICENSE.md` & `RIFT-0.0.15.9rc5/LICENSE.md`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/calmarg/rift_source.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/calmarg/rift_source.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/MonteCarloEnsemble.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/MonteCarloEnsemble.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/direct_quadrature.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/direct_quadrature.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/gaussian_mixture_model.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/gaussian_mixture_model.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/mcsampler.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/mcsampler.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/mcsamplerEnsemble.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/mcsamplerEnsemble.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/mcsamplerGPU.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/mcsamplerGPU.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/multivariate_truncnorm.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/multivariate_truncnorm.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/statutils.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/statutils.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/integrators/weighted_gmm.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/integrators/weighted_gmm.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/BayesianLeastSquares.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/BayesianLeastSquares.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/ConstrainedQuadraticLikelihood.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/ConstrainedQuadraticLikelihood.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/efficient_save_sklearn_gp.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/efficient_save_sklearn_gp.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/gp.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/gp.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/gpytorch_wrapper.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/gpytorch_wrapper.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/internal_GP.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/internal_GP.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/interp_gpu.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/interp_gpu.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/interpolators/senni.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/interpolators/senni.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/lalsimutils.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/lalsimutils.py`

 * *Files 0% similar despite different names*

```diff
@@ -2965,15 +2965,15 @@
         ht = lal.ResizeREAL8TimeSeries(ht, 0, TDlen)
     else: # Check zero-padding was done to expected length
         TDlen = int(1./P.deltaF * 1./P.deltaT)
         assert TDlen == ht.data.length
     
     if fwdplan==None:
         fwdplan=lal.CreateForwardREAL8FFTPlan(TDlen,0)
-    FDlen = TDlen/2+1
+    FDlen = int(TDlen/2+1)
     hf = lal.CreateCOMPLEX16FrequencySeries("Template h(f)", 
             ht.epoch, ht.f0, 1./ht.deltaT/TDlen, lsu_HertzUnit, 
             FDlen)
     lal.REAL8TimeFreqFFT(hf, ht, fwdplan)
     return hf
 
 def hoff_FD(P, Fp=None, Fc=None):
@@ -4021,15 +4021,15 @@
     else: # Check zero-padding was done to expected length
         TDlen = int(1./P.deltaF * 1./P.deltaT)
         assert TDlen == ht.data.length
 
     if fwdplan==None:
         fwdplan=lal.CreateForwardCOMPLEX16FFTPlan(TDlen,0)
 
-    FDlen = TDlen/2+1
+    FDlen = int(TDlen/2+1)
     hf = lal.CreateCOMPLEX16FrequencySeries("Template h(f)", 
             ht.epoch, ht.f0, 1./ht.deltaT/TDlen, lsu_HertzUnit, 
             TDlen)
     lal.COMPLEX16TimeFreqFFT(hf, ht, fwdplan)
     return hf
 
 def complex_norm_hoff(P, IP, sgn=-1, fwdplan=None):
@@ -4815,15 +4815,15 @@
 # lalsimutils.polar_angles_in_frame(lalsimutils.rotation_matrix(np.array([0,1,0]), 0.01), lalsimutils.nhat(0.1, 0.0))
 # lalsimutils.polar_angles_in_frame_alt(lalsimutils.rotation_matrix(np.array([0,0,1]), 0.1), 0.1, 0.2)
 # lalsimutils.polar_angles_in_frame_alt(lalsimutils.rotation_matrix(np.array([0,1,0]), 0.01), 0.1, 0.0)
 
 def DataFourierREAL8(ht):   # Complex fft wrapper (REAL8Time ->COMPLEX16Freq. No error checking or padding!
     TDlen = ht.data.length
     fwdplan=lal.CreateForwardREAL8FFTPlan(TDlen,0)
-    FDlen = TDlen/2+1
+    FDlen = int(TDlen/2+1)
     hf = lal.CreateCOMPLEX16FrequencySeries("Template h(f)", 
             ht.epoch, ht.f0, 1./ht.deltaT/TDlen, lsu_HertzUnit, 
             FDlen)
     lal.REAL8TimeFreqFFT(hf, ht, fwdplan)
     # assume memory freed by swig python
     return hf
 def DataInverseFourierREAL8(hf):   # Complex fft wrapper (COMPLEX16Freq ->REAL8TimeSeries. No error checking or padding!
@@ -4856,15 +4856,15 @@
             TDlen)
     lal.COMPLEX16TimeFreqFFT(hf, ht, fwdplan)
     # assume memory freed by swig python
     return hf
 def DataFourierREAL8(ht):   # Complex fft wrapper (REAL8Time ->COMPLEX16Freq. No error checking or padding!
     TDlen = ht.data.length
     fwdplan=lal.CreateForwardREAL8FFTPlan(TDlen,0)
-    FDlen = TDlen/2+1
+    FDlen = int(TDlen/2+1)
     hf = lal.CreateCOMPLEX16FrequencySeries("Template h(f)", 
             ht.epoch, ht.f0, 1./ht.deltaT/TDlen, lsu_HertzUnit, 
             FDlen)
     lal.REAL8TimeFreqFFT(hf, ht, fwdplan)
     # assume memory freed by swig python
     return hf
 
@@ -5247,14 +5247,15 @@
         # deal with scenario where only one of lambda1, lambda2 specified IN FUTURE
         indx_p_out = coord_names.index('LambdaTilde')
         indx_la1 = low_level_coord_names.index('lambda1')
         indx_la2 = low_level_coord_names.index('lambda2')
         la1_vals = x_in[:,indx_la1]
         la2_vals = x_in[:,indx_la2]
         if 'mc' in low_level_coord_names and 'delta_mc' in low_level_coord_names:
+            indx_mc = low_level_coord_names.index('mc')
             eta_vals = np.zeros(len(x_in))  
             m1_vals =np.zeros(len(x_in))  
             m2_vals =np.zeros(len(x_in))  
             if ('delta_mc' in low_level_coord_names):
                 indx_delta = low_level_coord_names.index('delta_mc')
                 eta_vals = 0.25*(1- x_in[:,indx_delta]**2)
             elif ('eta' in low_level_coord_names):
```

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/Q_inner_product.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/Q_inner_product.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/SphericalHarmonics_gpu.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/SphericalHarmonics_gpu.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/cuda_Q_inner_product.cu` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/cuda_Q_inner_product.cu`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/factored_likelihood.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/factored_likelihood.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/optimized_gpu_tools.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/optimized_gpu_tools.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/priors_utils.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/priors_utils.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/vectorized_general_tools.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/vectorized_general_tools.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/likelihood/vectorized_lal_tools.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/likelihood/vectorized_lal_tools.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/ModifiedScikitFit.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/ModifiedScikitFit.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/amrlib.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/amrlib.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/bounded_kde.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/bounded_kde.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/dag_utils.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/dag_utils.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/modules.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/modules.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/our_corner.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/our_corner.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/ourparams.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/ourparams.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/samples_utils.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/samples_utils.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/sky_rotations.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/sky_rotations.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/spokes.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/spokes.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/tools.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/tools.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/weight_simulations.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/weight_simulations.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/misc/xmlutils.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/misc/xmlutils.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/EOBTidalExternal.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/EOBTidalExternal.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/EOBTidalExternalC.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/EOBTidalExternalC.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/EOSManager.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/EOSManager.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/GWSignal.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/GWSignal.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/MonotonicSpline.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/MonotonicSpline.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/PrecessingFisherMatrix.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/PrecessingFisherMatrix.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/ROMWaveformManager.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/ROMWaveformManager.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT/physics/effectiveFisher.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT/physics/effectiveFisher.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT.egg-info/PKG-INFO` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: RIFT
-Version: 0.0.15.9rc4
+Version: 0.0.15.9rc5
 Summary: RIFT parameter estimation pipeline. Note branch used is temp-RIT-Tides-port_python3_restructure_package (which will become master shortly)!
 Home-page: https://git.ligo.org/rapidpe-rift/rift
 Author: Richard O'Shaughnessy
 Author-email: richard.oshaughnessy@ligo.org
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/RIFT.egg-info/SOURCES.txt` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/RIFT.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/assess_propose_CIP_convergence_sequence.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/assess_propose_CIP_convergence_sequence.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/calibration_reweighting.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/calibration_reweighting.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/combine_weights_and_rejection_sample.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/combine_weights_and_rejection_sample.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/config_yank.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/config_yank.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convergence_test_amr.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convergence_test_amr.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convergence_test_samples.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convergence_test_samples.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_ascii_framechange_xphm.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_ascii_framechange_xphm.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_dat_to_hdf5.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_dat_to_hdf5.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_output_format_allnet2xml` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_output_format_allnet2xml`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_output_format_ascii2h5.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_output_format_ascii2h5.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_output_format_ile2inference` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_output_format_ile2inference`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_output_format_inference2ile` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_output_format_inference2ile`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/convert_psd_ascii2xml` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/convert_psd_ascii2xml`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_CIP_convergence_sequence.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_CIP_convergence_sequence.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_eos_posterior_pipeline` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_eos_posterior_pipeline`

 * *Files 2% similar despite different names*

```diff
@@ -166,17 +166,18 @@
 
 # Load args.txt. Remove first item.  Store
 if True: # not (opts.eos_post_args is None):
     with open(opts.eos_post_args) as f:
         eos_post_args_list = f.readlines()
     eos_post_args = ' '.join( [x.replace('\\','') for x in eos_post_args_list] )
     eos_post_args = ' '.join(eos_post_args.split(' ')[1:])
-    # Some argument protection for later
-    eos_post_args = eos_post_args.replace('[', ' \'[')
-    eos_post_args = eos_post_args.replace(']', ']\'')
+    # Some argument protection for later.  Make sure spaces in place to avoid breaking compound arguments like g0:[a,b] for ranges.
+    # intended to make sure any spaces in arguments like [a, b] are encoded as '[a, b]' 
+    eos_post_args = eos_post_args.replace(' [', '  \'[')
+    eos_post_args = eos_post_args.replace('] ', ']\' ')
     eos_post_args=eos_post_args.rstrip()
     eos_post_args += ' --no-plots '  
     print("EOS_POST", eos_post_args)
 
 eospost_exe = which('util_ConstructEOSPosterior.py')
 if opts.eos_post_exe:
     eospost_exe = "{}".format(opts.eos_post_exe) # force clpy, so NOT BY REFERENCE
@@ -237,46 +238,46 @@
 #   - issue is that transfer files depend on event
 #   - all output goes into the same iter*_marg directory
 #   - join script will merge all together
     cip_job, cip_job_name = dag_utils.write_CIP_sub(tag='MARG',log_dir=None,arg_str=marg_event_args,using_eos='file:'+working_dir_inside_local+"/grid-$(macroiteration).dat",using_eos_index='$(macroevent)',request_memory=opts.request_memory_marg,input_net=working_dir_inside_local+'/event-$(macroid).net',output='MARG-$(macroid)-$(macroevent)',out_dir=out_dir_inside_marg,exe=marg_exe_master,universe=local_worker_universe,no_grid=not(opts.use_osg),use_osg=opts.use_osg,use_singularity=opts.use_osg and opts.use_singularity,singularity_image=singularity_image,use_simple_osg_requirements=opts.use_osg,transfer_files=['../event-$(macroid).net'])
     # Modify: set 'initialdir'
     cip_job.add_condor_cmd("initialdir",opts.working_directory+"/iteration_$(macroiteration)_marg")
     # Modify output argument: change logs and working directory to be subdirectory for the run
-    cip_job.set_log_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/marg-$(cluster)-$(process).log")
-    cip_job.set_stderr_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/marg-$(cluster)-$(process).err")
-    cip_job.set_stdout_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/marg-$(cluster)-$(process).out")
+    cip_job.set_log_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/marg-$(macroevent)-$(cluster)-$(process).log")
+    cip_job.set_stderr_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/marg-$(macroevent)-$(cluster)-$(process).err")
+    cip_job.set_stdout_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/marg-$(macroevent)-$(cluster)-$(process).out")
     cip_job.add_condor_cmd('request_disk',opts.general_request_disk)
     if opts.use_full_submit_paths:
         fname = opts.working_directory+"/"+cip_job.get_sub_file()
         cip_job.set_sub_file(fname)
     cip_job.write_sub_file()
 
     # PUFF variant
     cipPuff_job, cipPuff_job_name = dag_utils.write_CIP_sub(tag='MARG_PUFF',log_dir=None,arg_str=marg_event_args,using_eos='file:'+working_dir_inside_local+"/grid_puff-$(macroiteration).dat",using_eos_index='$(macroevent)',request_memory=opts.request_memory_marg,input_net=working_dir_inside_local+'/event-$(macroid).net',output='MARG-$(macroid)-$(macroevent)',out_dir=out_dir_inside_marg,exe=marg_exe_master,universe=local_worker_universe,no_grid=not(opts.use_osg),use_osg=opts.use_osg,use_singularity=opts.use_osg and opts.use_singularity,singularity_image=singularity_image,use_simple_osg_requirements=opts.use_osg,transfer_files=['../event-$(macroid).net'])
     # Modify: set 'initialdir'
     cipPuff_job.add_condor_cmd("initialdir",opts.working_directory+"/iteration_$(macroiteration)_marg")
     # Modify output argument: change logs and working directory to be subdirectory for the run
-    cipPuff_job.set_log_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/margPuff-$(cluster)-$(process).log")
-    cipPuff_job.set_stderr_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/margPuff-$(cluster)-$(process).err")
-    cipPuff_job.set_stdout_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/margPuff-$(cluster)-$(process).out")
+    cipPuff_job.set_log_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/margPuff-$(macroevent)-$(cluster)-$(process).log")
+    cipPuff_job.set_stderr_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/margPuff-$(macroevent)-$(cluster)-$(process).err")
+    cipPuff_job.set_stdout_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/margPuff-$(macroevent)-$(cluster)-$(process).out")
     cipPuff_job.add_condor_cmd('request_disk',opts.general_request_disk)
     if opts.use_full_submit_paths:
         fname = opts.working_directory+"/"+cipPuff_job.get_sub_file()
         cipPuff_job.set_sub_file(fname)
     cipPuff_job.write_sub_file()
 
 else:
     for indx in np.arange(len(marg_event_args_list)):
         cip_job, cip_job_name = dag_utils.write_CIP_sub(tag='MARG_{}'.format(indx),log_dir=None,exe=marg_event_exe_list[indx],arg_str=marg_event_args_list[indx],using_eos='file:'+working_dir_inside_local+"/grid-$(macroiteration).dat",using_eos_index='$(macroevent)',request_memory=opts.request_memory_marg,input_net=working_dir_inside_local+'/event-$(macroid).net',output='MARG-$(macroid)-$(macroevent)',out_dir=out_dir_inside_marg,universe=local_worker_universe,no_grid=not(opts.use_osg),use_osg=opts.use_osg,use_singularity=opts.use_osg and opts.use_singularity,singularity_image=singularity_image,use_simple_osg_requirements=opts.use_osg,transfer_files=['../event-$(macroid).net'])
         # Modify: set 'initialdir'
         cip_job.add_condor_cmd("initialdir",opts.working_directory+"/iteration_$(macroiteration)_marg")
         # Modify output argument: change logs and working directory to be subdirectory for the run
-        cip_job.set_log_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/marg-$(cluster)-$(process).log")
-        cip_job.set_stderr_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/marg-$(cluster)-$(process).err")
-        cip_job.set_stdout_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/marg-$(cluster)-$(process).out")
+        cip_job.set_log_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/marg-$(macroevent)-$(cluster)-$(process).log")
+        cip_job.set_stderr_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/marg-$(macroevent)-$(cluster)-$(process).err")
+        cip_job.set_stdout_file(opts.working_directory+"/iteration_$(macroiteration)_marg/logs/marg-$(macroevent)-$(cluster)-$(process).out")
         cip_job.add_condor_cmd('request_disk',opts.general_request_disk)
         if opts.use_full_submit_paths:
             fname = opts.working_directory+"/"+cip_job.get_sub_file()
             cip_job.set_sub_file(fname)
         cip_job.write_sub_file()
         cip_job_list.append(cip_job)
 
@@ -367,15 +368,15 @@
     unify_marg_job.add_condor_cmd("+DESIRED_SITES",'"nogrid"')
     unify_marg_job.add_condor_cmd("+flock_local",'true')
 unify_marg_job.write_sub_file()
 
 
 ##   EOS_POST job  (workers)
 #  - main hyperparameter integration executable
-eospost_marg_job, eospost_marg_job_name = dag_utils.write_hyperpost_sub(exe=eospost_exe,tag='EOS_POST_worker',arg_str=eos_post_args,out_dir=opts.working_directory,output='iteration_$(macroiteration)_post/output-$(macroiterationnext)-$(cluster)')
+eospost_marg_job, eospost_marg_job_name = dag_utils.write_hyperpost_sub(exe=eospost_exe,tag='EOS_POST_worker',arg_str=eos_post_args,out_dir=opts.working_directory,output='iteration_$(macroiteration)_post/output-$(macroiterationnext)-$(cluster)',input_net=working_dir_inside + "/all.marg_net")
 eospost_marg_job.add_condor_cmd("initialdir",opts.working_directory+"/iteration_$(macroiteration)_post")
 eospost_marg_job.set_log_file(opts.working_directory+"/iteration_$(macroiteration)_post/logs/post-$(cluster)-$(process).log")
 eospost_marg_job.set_stderr_file(opts.working_directory+"/iteration_$(macroiteration)_post/logs/post-$(cluster)-$(process).err")
 eospost_marg_job.set_stdout_file(opts.working_directory+"/iteration_$(macroiteration)_post/logs/post-$(cluster)-$(process).out")
 eospost_marg_job.add_condor_cmd('request_disk',opts.general_request_disk)
 if opts.use_full_submit_paths:
     fname = opts.working_directory+"/"+eospost_marg_job.get_sub_file()
@@ -403,15 +404,15 @@
     join_post_job.add_condor_cmd("+DESIRED_SITES",'"nogrid"')
     join_post_job.add_condor_cmd("+flock_local",'true')
 
 
 # PUFF job
 #   ... pending
 if puff_args and puff_cadence:
-    puff_job, puff_job_name = dag_utils.write_puff_sub(tag='PUFF',log_dir=None,arg_str=puff_args,request_memory=opts.request_memory_marg,input_net=opts.working_directory+'/grid-$(macroiterationnext).dat',output=opts.working_directory+'/puffball-$(macroiterationnext)',out_dir=opts.working_directory,exe=opts.puff_exe,universe=local_worker_universe,no_grid=no_worker_grid)
+    puff_job, puff_job_name = dag_utils.write_puff_sub(tag='PUFF',log_dir=None,arg_str=puff_args,request_memory=opts.request_memory_marg,input_net=opts.working_directory+'/grid-$(macroiterationnext).dat',output=opts.working_directory+'/puffball-$(macroiterationnext).dat',out_dir=opts.working_directory,exe=opts.puff_exe,universe=local_worker_universe,no_grid=no_worker_grid)
     # Modify: set 'initialdir' to CIP WORKING DIR 
     puff_job.add_condor_cmd("initialdir",opts.working_directory+"/iteration_$(macroiteration)_post")
     # Modify output argument: change logs and working directory to be subdirectory for the run
     puff_job.set_log_file(opts.working_directory+"/iteration_$(macroiteration)_post/logs/puff-$(cluster)-$(process).log")
     puff_job.set_stderr_file(opts.working_directory+"/iteration_$(macroiteration)_post/logs/puff-$(cluster)-$(process).err")
     puff_job.set_stdout_file(opts.working_directory+"/iteration_$(macroiteration)_post/logs/puff-$(cluster)-$(process).out")
     puff_job.add_condor_cmd('request_disk',opts.general_request_disk)
```

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_event_dag_via_grid` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_event_dag_via_grid`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_event_parameter_pipeline_AlternateIteration` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_event_parameter_pipeline_AlternateIteration`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_event_parameter_pipeline_BasicIteration` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_event_parameter_pipeline_BasicIteration`

 * *Files 0% similar despite different names*

```diff
@@ -829,15 +829,18 @@
     cip_args_base = cip_args_base.replace('fit-save-gp','fit-load-gp')
     n_explode =opts.cip_explode_jobs
     fname_out = 'overlap-grid-$(macroiterationnext)-$(process)'
     if opts.cip_explode_jobs_dag:
         n_explode=1
         fname_out = 'overlap-grid-$(macroiterationnext)-$(cluster)'
     cip_args_base = cip_args_base.replace('my_fit', 'my_fit.pkl')  # yes, asymmetric arguments
-    cip_job_worker, cip_job_worker_name = dag_utils.write_CIP_sub(tag='CIP_worker',log_dir=None,arg_str=cip_args_base,request_memory=opts.request_memory_CIP,input_net=working_dir_inside_cip+'/all.net',output=fname_out,out_dir=out_dir_inside_cip,exe=cip_exe,ncopies=n_explode,universe=local_worker_universe,no_grid=cip_no_grid,use_osg=opts.use_osg_cip,use_singularity=opts.use_osg_cip and opts.use_singularity,singularity_image=singularity_image,use_simple_osg_requirements=opts.use_osg_cip,transfer_files=['../all.net'])
+    transfer_files_cip =['../all.net']
+    if opts.use_osg_cip and 'fit-method gp' in cip_args_base:
+        transfer_files_cip += ['my_fit.pkl']  # transfer current working directory fit
+    cip_job_worker, cip_job_worker_name = dag_utils.write_CIP_sub(tag='CIP_worker',log_dir=None,arg_str=cip_args_base,request_memory=opts.request_memory_CIP,input_net=working_dir_inside_cip+'/all.net',output=fname_out,out_dir=out_dir_inside_cip,exe=cip_exe,ncopies=n_explode,universe=local_worker_universe,no_grid=cip_no_grid,use_osg=opts.use_osg_cip,use_singularity=opts.use_osg_cip and opts.use_singularity,singularity_image=singularity_image,use_simple_osg_requirements=opts.use_osg_cip,transfer_files=transfer_files_cip)
     # Modify: set 'initialdir'
     cip_job_worker.add_condor_cmd("initialdir",opts.working_directory+"/iteration_$(macroiteration)_cip")
     # Modify output argument: change logs and working directory to be subdirectory for the run
     cip_job_worker.set_log_file(opts.working_directory+"/iteration_$(macroiteration)_cip/logs/cip-$(cluster)-$(process).log")
     cip_job_worker.set_stderr_file(opts.working_directory+"/iteration_$(macroiteration)_cip/logs/cip-$(cluster)-$(process).err")
     cip_job_worker.set_stdout_file(opts.working_directory+"/iteration_$(macroiteration)_cip/logs/cip-$(cluster)-$(process).out")
     cip_job_worker.add_condor_cmd('request_disk',opts.general_request_disk)
@@ -951,15 +954,18 @@
                 fname_out = 'overlap-grid-$(macroiterationnext)-$(cluster)'
            cip_args_extra = cip_args_extra.replace('fit-save-gp','fit-load-gp')
            cip_args_extra = cip_args_extra.replace('my_fit','my_fit.pkl')
            # if the last set of workers, we are making extrinsic samples, so change the output samples  
            if indx == len(cip_args_lines) -1 and opts.last_iteration_extrinsic: # on last iteration, doing extrinsic phase
                n_samples_per_job = int(opts.last_iteration_extrinsic_nsamples/(1.0*opts.cip_explode_jobs))
                cip_args_extra +=" --n-eff {} --n-output-samples {} ".format(n_samples_per_job,n_samples_per_job)
-           cip_job_worker, cip_job_worker_name = dag_utils.write_CIP_sub(tag='CIP_worker'+str(indx),log_dir=None,arg_str=cip_args_lines[indx]+cip_args_extra,request_memory=opts.request_memory_CIP,input_net=working_dir_inside_cip+'/all.net',output=fname_out,out_dir=out_dir_inside_cip,exe=cip_exe_here,ncopies=n_explode,universe=local_worker_universe,no_grid=cip_no_grid,use_osg=opts.use_osg_cip,use_singularity=opts.use_osg_cip and opts.use_singularity,singularity_image=singularity_image,use_simple_osg_requirements=opts.use_osg_cip,transfer_files=['../all.net'])
+           transfer_files_cip=['../all.net']
+           if opts.use_osg_cip and 'fit-method gp' in cip_args_base:
+               transfer_files_cip += ['my_fit.pkl']  # transfer current working directory fit
+           cip_job_worker, cip_job_worker_name = dag_utils.write_CIP_sub(tag='CIP_worker'+str(indx),log_dir=None,arg_str=cip_args_lines[indx]+cip_args_extra,request_memory=opts.request_memory_CIP,input_net=working_dir_inside_cip+'/all.net',output=fname_out,out_dir=out_dir_inside_cip,exe=cip_exe_here,ncopies=n_explode,universe=local_worker_universe,no_grid=cip_no_grid,use_osg=opts.use_osg_cip,use_singularity=opts.use_osg_cip and opts.use_singularity,singularity_image=singularity_image,use_simple_osg_requirements=opts.use_osg_cip,transfer_files=transfer_files_cip)
            # Modify: set 'initialdir'
            cip_job_worker.add_condor_cmd("initialdir",opts.working_directory+"/iteration_$(macroiteration)_cip")
            # Modify output argument: change logs and working directory to be subdirectory for the run
            cip_job_worker.set_log_file(opts.working_directory+"/iteration_$(macroiteration)_cip/logs/cipworker-$(cluster)-$(process).log")
            cip_job_worker.set_stderr_file(opts.working_directory+"/iteration_$(macroiteration)_cip/logs/cipworker-$(cluster)-$(process).err")
            cip_job_worker.set_stdout_file(opts.working_directory+"/iteration_$(macroiteration)_cip/logs/cipworker-$(cluster)-$(process).out")
            cip_job_worker.add_condor_cmd('request_disk',opts.general_request_disk)
```

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_event_parameter_pipeline_BasicMultiApproxIteration` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_event_parameter_pipeline_BasicMultiApproxIteration`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_ile_sub_dag.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_ile_sub_dag.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/create_postprocessing_event_dag.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/create_postprocessing_event_dag.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/helper_LDG_Events.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/helper_LDG_Events.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/helper_OnlinePSDCleanup.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/helper_OnlinePSDCleanup.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/ile_postproc_add_time` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/ile_postproc_add_time`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/integrate_likelihood_extrinsic` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/integrate_likelihood_extrinsic`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/integrate_likelihood_extrinsic_batchmode` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/integrate_likelihood_extrinsic_batchmode`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/integrate_likelihood_extrinsic_no-op` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/integrate_likelihood_extrinsic_no-op`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/make_uni_comov_skymap.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/make_uni_comov_skymap.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/plot_posterior_corner.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/plot_posterior_corner.py`

 * *Files 1% similar despite different names*

```diff
@@ -201,14 +201,15 @@
 # Parse arguments
 parser = argparse.ArgumentParser()
 parser.add_argument("--posterior-file",action='append',help="filename of *.dat file [standard LI output]")
 parser.add_argument("--truth-file",type=str, help="file containing the true parameters")
 parser.add_argument("--posterior-distance-factor",action='append',help="Sequence of factors used to correct the distances")
 parser.add_argument("--truth-event",type=int, default=0,help="file containing the true parameters")
 parser.add_argument("--composite-file",action='append',help="filename of *.dat file [standard ILE intermediate]")
+parser.add_argument("--composite-file-has-labels",action='store_true',help="Assume header for composite file")
 parser.add_argument("--use-all-composite-but-grayscale",action='store_true',help="Composite")
 parser.add_argument("--flag-tides-in-composite",action='store_true',help='Required, if you want to parse files with tidal parameters')
 parser.add_argument("--flag-eos-index-in-composite",action='store_true',help='Required, if you want to parse files with EOS index in composite (and tides)')
 parser.add_argument("--posterior-label",action='append',help="label for posterior file")
 parser.add_argument("--posterior-color",action='append',help="color and linestyle for posterior. PREPENDED onto default list, so defaults exist")
 parser.add_argument("--posterior-linestyle",action='append',help="color and linestyle for posterior. PREPENDED onto default list, so defaults exist")
 parser.add_argument("--parameter", action='append',help="parameter name (ILE). Note source-frame masses are only natively supported for LI")
@@ -468,50 +469,55 @@
 field_formats = [np.float32 for x in field_names]
 composite_dtype = [ (x,float) for x in field_names] #np.dtype(names=field_names ,formats=field_formats)
 # Load posterior files
 if opts.composite_file:
  print(opts.composite_file)
  for fname in opts.composite_file[:1]:  # Only load the first one!
     print(" Loading ... ", fname)
-    samples = np.loadtxt(fname,dtype=composite_dtype)  # Names are not always available
+    if not(opts.composite_file_has_labels):
+        samples = np.loadtxt(fname,dtype=composite_dtype)  # Names are not always available
+    else:
+        samples = np.genfromtxt(fname,names=True)
     samples = samples[ ~np.isnan(samples["lnL"])] # remove nan likelihoods -- they can creep in with poor settings/overflows
+    name_ref = samples.dtype.names[0]
     if opts.sigma_cut >0:
-        npts = len(samples["m1"])
+        npts = len(samples[name_ref])
         # strip NAN
         sigma_vals = samples["sigmaOverL"]
         good_sigma = sigma_vals < opts.sigma_cut
         npts_out = np.sum(good_sigma)
         if npts_out < npts:
             new_samples = np.recarray( (npts_out,), dtype=samples.dtype)
             for name in samples.dtype.names:
                 new_samples[name] = samples[name][good_sigma]
             samples = new_samples
 
 #    samples = np.recarray(samples.T,names=field_names,dtype=field_formats) #,formats=field_formats)
     # If no record names
     # Add mtotal, q, 
-    samples=add_field(samples,[('mtotal',float)]); samples["mtotal"]= samples["m1"]+samples["m2"]; 
-    samples=add_field(samples,[('q',float)]); samples["q"]= samples["m2"]/samples["m1"]; 
-    samples=add_field(samples,[('mc',float)]); samples["mc"] = lalsimutils.mchirp(samples["m1"], samples["m2"])
-    samples=add_field(samples,[('eta',float)]); samples["eta"] = lalsimutils.symRatio(samples["m1"], samples["m2"])
-    samples=add_field(samples,[('chi_eff',float)]); samples["chi_eff"]= (samples["m1"]*samples["a1z"]+samples["m2"]*samples["a2z"])/(samples["mtotal"]); 
-    chi1_perp = np.sqrt(samples['a1x']*samples["a1x"] + samples['a1y']**2)
-    chi2_perp = np.sqrt(samples['a2x']**2 + samples['a2y']**2)
-    samples = add_field(samples, [('chi1_perp',float)]); samples['chi1_perp'] = chi1_perp
-    samples = add_field(samples, [('chi2_perp',float)]); samples['chi2_perp'] = chi2_perp
-
-    if ('lambda1' in samples.dtype.names):
-        Lt,dLt = lalsimutils.tidal_lambda_tilde(samples['m1'], samples['m2'],  samples['lambda1'], samples['lambda2'])
-        samples= add_field(samples, [('LambdaTilde',float), ('DeltaLambdaTilde',float),('lambdat',float),('dlambdat',float)])
-        samples['LambdaTilde'] = samples['lambdat']= Lt
-        samples['DeltaLambdaTilde'] = samples['dlambdat']= dLt
+    if 'm1' in samples.dtype.names:
+        samples=add_field(samples,[('mtotal',float)]); samples["mtotal"]= samples["m1"]+samples["m2"]; 
+        samples=add_field(samples,[('q',float)]); samples["q"]= samples["m2"]/samples["m1"]; 
+        samples=add_field(samples,[('mc',float)]); samples["mc"] = lalsimutils.mchirp(samples["m1"], samples["m2"])
+        samples=add_field(samples,[('eta',float)]); samples["eta"] = lalsimutils.symRatio(samples["m1"], samples["m2"])
+        samples=add_field(samples,[('chi_eff',float)]); samples["chi_eff"]= (samples["m1"]*samples["a1z"]+samples["m2"]*samples["a2z"])/(samples["mtotal"]); 
+        chi1_perp = np.sqrt(samples['a1x']*samples["a1x"] + samples['a1y']**2)
+        chi2_perp = np.sqrt(samples['a2x']**2 + samples['a2y']**2)
+        samples = add_field(samples, [('chi1_perp',float)]); samples['chi1_perp'] = chi1_perp
+        samples = add_field(samples, [('chi2_perp',float)]); samples['chi2_perp'] = chi2_perp
+
+        if ('lambda1' in samples.dtype.names):
+            Lt,dLt = lalsimutils.tidal_lambda_tilde(samples['m1'], samples['m2'],  samples['lambda1'], samples['lambda2'])
+            samples= add_field(samples, [('LambdaTilde',float), ('DeltaLambdaTilde',float),('lambdat',float),('dlambdat',float)])
+            samples['LambdaTilde'] = samples['lambdat']= Lt
+            samples['DeltaLambdaTilde'] = samples['dlambdat']= dLt
 
     samples_orig = samples
     if opts.lnL_cut:
-        npts = len(samples["m1"])
+        npts = len(samples[name_ref])
         # strip NAN
         lnL_vals = samples["lnL"]
         not_nan = np.logical_not(np.isnan(lnL_vals))
         npts_out = np.sum(not_nan)
         if npts_out < npts:
             new_samples = np.recarray( (npts_out,), dtype=samples.dtype)
             for name in samples.dtype.names:
@@ -526,16 +532,16 @@
         npts_out = np.sum(indx_ok)
         new_samples = np.recarray( (npts_out,), dtype=samples.dtype)
         for name in samples.dtype.names:
             new_samples[name] = samples[name][indx_ok]
         samples = new_samples
 
 
-    print(" Loaded samples from ", fname , len(samples["m1"]))
-    if True:
+    print(" Loaded samples from ", fname , len(samples[name_ref]))
+    if 'm1' in samples.dtype.names:
         # impose Kerr limit
         npts = len(samples["m1"])
         indx_ok =np.arange(npts)
         chi1_squared = samples["chi1_perp"]**2 + samples["a1z"]**2
         chi2_squared = samples["chi2_perp"]**2 + samples["a2z"]**2
         indx_ok = np.logical_and(chi1_squared < opts.chi_max ,chi2_squared < opts.chi_max)
         npts_out = np.sum(indx_ok)
@@ -745,17 +751,19 @@
         fig.savefig(param+"_cum"+fig_extension,dpi=dpi_base)
 
 
 if composite_list:
   for pIndex in [0]: # np.arange(len(composite_list)):  # should NEVER have more than one
     samples = composite_list[pIndex]
     samples_orig = composite_full_list[pIndex]
+    samples_ref_name = samples.dtype.names[0]
+    samples_orig_ref_name = samples_orig.dtype.names[0]
     # Create data for corner plot
-    dat_mass = np.zeros( (len(samples["m1"]), len(labels_tex)) )
-    dat_mass_orig = np.zeros( (len(samples_orig["m1"]), len(labels_tex)) )
+    dat_mass = np.zeros( (len(samples[samples_ref_name]), len(labels_tex)) )
+    dat_mass_orig = np.zeros( (len(samples_orig[samples_orig_ref_name]), len(labels_tex)) )
     lnL = samples["lnL"]
     indx_sorted = lnL.argsort()
     if len(lnL)<1:
         print(" Failed to retrieve lnL for composite file ", composite_list[0])
 
     cm = plt.cm.get_cmap('rainbow') #'RdYlBu_r')
     y_span = lnL.max() - lnL.min()
```

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/resample_uniform_comoving.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/resample_uniform_comoving.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_AMRGrid.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_AMRGrid.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_AdaptiveExponent.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_AdaptiveExponent.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_AnalyticFisherGrid.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_AnalyticFisherGrid.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_BatchConvertResampleILEOutput.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_BatchConvertResampleILEOutput.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CIPdagPostprocess.sh` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CIPdagPostprocess.sh`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CharacterizePosterior.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CharacterizePosterior.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CleanILE.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CleanILE.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CoincIFOUtility.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CoincIFOUtility.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CompareWaveformsInDetectors.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CompareWaveformsInDetectors.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ConsolidateDAGsUnderMaster.sh` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ConsolidateDAGsUnderMaster.sh`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ConstructBNSMarginalEOSRank.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ConstructBNSMarginalEOSRank.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ConstructEOSPosterior.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ConstructEOSPosterior.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-#! /usr/bin/env python
+#!/usr/bin/env python
 #
 #  util_ConstructEOSPosterior.py
 #     - takes in *generic-format* hyperparameter likelihood data
 #     - uses *uniform* prior on hyperparameters.  [non-uniform priors can  be applied by the user with a supplementary function]
 #     - generates posterior distribution by weighted Monte Carlo
 #
 # EXAMPLE:
@@ -458,28 +458,32 @@
     # Cap the total number of points retained, AFTER the threshold cut
     if opts.cap_points< len(Y) and opts.cap_points> 100:
         n_keep = opts.cap_points
         indx = np.random.choice(np.arange(len(Y)),size=n_keep,replace=False)
         Y=Y[indx]
         X=X[indx]
         Y_err=Y_err[indx]
+    if opts.ignore_errors_in_data:
+        Y_err=None
     my_fit = fit_gp(X,Y,y_errors=Y_err)
 elif opts.fit_method == 'rf':
     print( " FIT METHOD ", opts.fit_method, " IS RF ")
     # NO data truncation for NN needed?  To be *consistent*, have the code function the same way as the others
     X=X[indx_ok]
     Y=Y[indx_ok] - lnL_shift
     Y_err = Y_err[indx_ok]
     # Cap the total number of points retained, AFTER the threshold cut
     if opts.cap_points< len(Y) and opts.cap_points> 100:
         n_keep = opts.cap_points
         indx = np.random.choice(np.arange(len(Y)),size=n_keep,replace=False)
         Y=Y[indx]
         X=X[indx]
         Y_err=Y_err[indx]
+    if opts.ignore_errors_in_data:
+        Y_err=None
     my_fit = fit_rf(X,Y,y_errors=Y_err)
 
 
 # Sort for later convenience (scatterplots, etc)
 indx = Y.argsort()#[::-1]
 X=X[indx]
 Y=Y[indx]
```

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ConstructIntrinsicPosterior_GaussianResampling.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ConstructIntrinsicPosterior_GaussianResampling.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ConstructIntrinsicPosterior_GenericCoordinates.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ConstructIntrinsicPosterior_GenericCoordinates.py`

 * *Files 0% similar despite different names*

```diff
@@ -392,22 +392,24 @@
                 spec_params['gamma3']=spec_params['gamma4']=0
             else:
                 spec_params['gamma3']=spec_param_array[2]
                 spec_params['gamma4']=spec_param_array[3]
             eos_base = EOSManager.EOSLindblomSpectral(name=eos_name,spec_params=spec_params,use_lal_spec_eos=not opts.no_use_lal_eos)
             my_eos=eos_base
         elif opts.eos_param == 'cs_spectral' and len(spec_param_array >=4):
+            spec_params ={}
             spec_params['gamma1']=spec_param_array[0]
             spec_params['gamma2']=spec_param_array[1]
             spec_params['gamma3']=spec_params['gamma4']=0
             spec_params['gamma3']=spec_param_array[2]
             spec_params['gamma4']=spec_param_array[3]
             eos_base = EOSManager.EOSLindblomSpectralSoundSpeedVersusPressure(name=eos_name,spec_params=spec_params,use_lal_spec_eos=not opts.no_use_lal_eos)
             my_eos = eos_base
         elif opts.eos_param == 'PP' and len(spec_param_array >=4):
+            spec_params ={}
             spec_params['logP1'] = spec_param_array[0]
             spec_params['gamma1'] = spec_param_array[1]
             spec_params['gamma2'] = spec_param_array[2]
             spec_params['gamma3'] = spec_param_array[3]
             eos_base = EOSManager.EOSPiecewisePolytrope(name=eos_name,params_dict=spec_params)
             my_eos = eos_base
         else:
@@ -2289,15 +2291,15 @@
             return np.exp(my_fit([x,y,z,a,b,c,d,e,f]))*my_prior_scale([x,y,z,a,b,c,d,e,f])
         else:
             return np.exp(my_fit(convert_coords(np.c_[x,y,z,a,b,c,d,e,f]))) *my_prior_scale(np.c_[x,y,z,a,b,c,d,e,f])
     def log_likelihood_function(x,y,z,a,b,c,d,e,f):
         if isinstance(x,float):
             return my_fit([x,y,z,a,b,c,d,e,f]) + my_log_prior_scale([x,y,z,a,b,c,d,e,f])
         else:
-            return my_fit(convert_coords(np.c_[x,y,z,a,v,c,d,e,f]))+ my_log_prior_scale(np.c_[x,y,z,a,b,c,d,e,f])
+            return my_fit(convert_coords(np.c_[x,y,z,a,b,c,d,e,f]))+ my_log_prior_scale(np.c_[x,y,z,a,b,c,d,e,f])
 if len(low_level_coord_names) ==10:
     def likelihood_function(x,y,z,a,b,c,d,e,f,g):  
         if isinstance(x,float):
             return np.exp(my_fit([x,y,z,a,b,c,d,e,f,g]))*my_prior_scale([x,y,z,a,b,c,d,e,f,g])
         else:
             return np.exp(my_fit(convert_coords(np.c_[x,y,z,a,b,c,d,e,f,g])))*my_prior_scale(np.c_[x,y,z,a,b,c,d,e,f,g])
     def log_likelihood_function(x,y,z,a,b,c,d,e,f,g):
```

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_CoordinateNamesAngularToCartesianSpins.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_CoordinateNamesAngularToCartesianSpins.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_EOBTideWriteFrame.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_EOBTideWriteFrame.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_FetchExternalGrid.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_FetchExternalGrid.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_FitAndEvaluate_GenericCoordinates.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_FitAndEvaluate_GenericCoordinates.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ForOSG_MakeTruncatedLocalFramesDir.sh` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ForOSG_MakeTruncatedLocalFramesDir.sh`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_FrameZeroNoiseSNR.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_FrameZeroNoiseSNR.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_GenerateMaxlnLWaveform.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_GenerateMaxlnLWaveform.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_GenerateMaxlnLWaveform_NRFromIndex.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_GenerateMaxlnLWaveform_NRFromIndex.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_GridRecenter.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_GridRecenter.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_GridSubsetOfTemplateBank.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_GridSubsetOfTemplateBank.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_HyperCombine.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_HyperCombine.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_HyperparameterGrid.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_HyperparameterGrid.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_HyperparameterPuffball.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_HyperparameterPuffball.py`

 * *Files 10% similar despite different names*

```diff
@@ -9,16 +9,16 @@
 import lalsimulation as lalsim
 import lal
 import functools
 import itertools
 
 
 parser = argparse.ArgumentParser()
-parser.add_argument("--fname", help="Name of dat file")
-parser.add_argument("--fname-out", default="output-puffball.dat", help="Name of dat file")
+parser.add_argument("--inj-file", help="Name of dat file")
+parser.add_argument("--inj-file-out", default="output-puffball.dat", help="Name of dat file")
 parser.add_argument("--puff-factor", default=1,type=float)
 parser.add_argument("--force-away", default=0,type=float,help="If >0, uses the icov to compute a metric, and discards points which are close to existing points")
 parser.add_argument("--parameter", action='append', help="Parameters used as fitting parameters AND varied at a low level to make a posterior")
 parser.add_argument("--no-correlation", type=str,action='append', help="Pairs of parameters, in format [mc,eta]  The corresponding term in the covariance matrix is eliminated")
 #parser.add_argument("--parameter-implied", action='append', help="Parameter used in fit, but not independently varied for Monte Carlo")
 parser.add_argument("--random-parameter", action='append',help="These parameters are specified at random over the entire range, uncorrelated with the grid used for other parameters.  Use for variables which correlate weakly with others; helps with random exploration")
 parser.add_argument("--random-parameter-range", action='append', type=str,help="Add a range (pass as a string evaluating to a python 2-element list): --parameter-range '[0.,1000.]'   MUST specify ALL parameter ranges (min and max) in order if used.  ")
@@ -70,15 +70,15 @@
 for indx in np.arange(len(dlist_ranges)):
     downselect_dict[dlist[indx]] = dlist_ranges[indx]
 
 
 
 
 # Load data, keep parameter names
-dat_raw = np.genfromtxt(opts.fname,names=True)
+dat_raw = np.genfromtxt(opts.inj_file,names=True)
 X= np.zeros((len(dat_raw), len(coord_names)))
 # Copy over the parameters we use.  Note we have no way to create linear combinations or alternate coordinates here
 for p in coord_names:
 #    indx_p = list(dat_raw.dtype.names).index(p)
     indx_in = coord_names.index(p)
     X[:,indx_in] = dat_raw[p]
 
@@ -120,8 +120,8 @@
 
 # Write data back into correct format and save
 for p in coord_names:
 #    indx_p = dat_raw.dtype.names.index(p)
     indx_in = coord_names.index(p)
     dat_raw[p] = X_out[:,indx_in]
 
-np.savetxt(opts.fname_out, dat_raw,header=" ".join(dat_raw.dtype.names))
+np.savetxt(opts.inj_file_out, dat_raw,header=" ".join(dat_raw.dtype.names))
```

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ILENextGeneration.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ILENextGeneration.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ILEROMdagPostprocess.sh` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ILEROMdagPostprocess.sh`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ILEdagPostprocess.sh` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ILEdagPostprocess.sh`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_InitMargTable` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_InitMargTable`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_IntermediateEOSIntegralFromFit.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_IntermediateEOSIntegralFromFit.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_IterativeFisher.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_IterativeFisher.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_JoinXML.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_JoinXML.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_LALCompareApproximantsOnSamples.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_LALCompareApproximantsOnSamples.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_LALWriteFrame.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_LALWriteFrame.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ManualOverlapGrid.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ManualOverlapGrid.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_MarginalizedLikelihoodEOSIntegralFromIntermediate.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_MarginalizedLikelihoodEOSIntegralFromIntermediate.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_MassGrid.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_MassGrid.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_MassGridCoalesce.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_MassGridCoalesce.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRBestOfIndex.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRBestOfIndex.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRDumpDetectorResponse.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRDumpDetectorResponse.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRExtrudeOverlapGrid.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRExtrudeOverlapGrid.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRIndexedFminCutToILE.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRIndexedFminCutToILE.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRNearestSimulationTo.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRNearestSimulationTo.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRRelabelILE.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRRelabelILE.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRWriteFrame.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRWriteFrame.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NR_GWMemory.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NR_GWMemory.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_NRdagPostprocess.sh` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_NRdagPostprocess.sh`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ParameterFilter.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ParameterFilter.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ParameterPuffball.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ParameterPuffball.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ParameterRandomize.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ParameterRandomize.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_PosteriorPostprocess.sh` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_PosteriorPostprocess.sh`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_PrintInjection.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_PrintInjection.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_RIFT_MultiMetaPipe.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_RIFT_MultiMetaPipe.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_RIFT_pseudo_pipe.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_RIFT_pseudo_pipe.py`

 * *Files 1% similar despite different names*

```diff
@@ -530,15 +530,15 @@
     # Write 'target_params.xml.gz' file
     lalsimutils.ChooseWaveformParams_array_to_xml([P], "target_params")
 
     if opts.use_production_defaults:
         # use more workers for high-q triggers
         # worker scale = (1+2/q), max of 50
         q = P.m2/P.m1
-        opts.cip_explode_jobs = np.min([int(2+3./q),50])
+        opts.cip_explode_jobs = int(np.min([int(2+3./q),50]))
 
 
 helper_psd_args = ''
 srate=4096  # default, built into helper, unwise to go lower, LI will almost never do higher
 if opts.make_bw_psds:
     helper_psd_args += " --assume-fiducial-psd-files --fmax " + str(srate/2-1)
```

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_RIFT_pseudo_pipe_lowlatency.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_RIFT_pseudo_pipe_lowlatency.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ROMWriteFrame.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ROMWriteFrame.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_RandomizeOverlapOrder.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_RandomizeOverlapOrder.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_ResampleILEOutputWithExtrinsic.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_ResampleILEOutputWithExtrinsic.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_SimInspiralToCoinc.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_SimInspiralToCoinc.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_TEOBResumSWriteFrame.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_TEOBResumSWriteFrame.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_TestSpokesIO.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_TestSpokesIO.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_TestXMLParameterStorage.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_TestXMLParameterStorage.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_TidalPlotSimulationStrain.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_TidalPlotSimulationStrain.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_WriteFrameAndCacheFromXML.sh` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_WriteFrameAndCacheFromXML.sh`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_WriteInjectionFile.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_WriteInjectionFile.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/MonteCarloMarginalizeCode/Code/bin/util_WriteXMLWithEOS.py` & `RIFT-0.0.15.9rc5/MonteCarloMarginalizeCode/Code/bin/util_WriteXMLWithEOS.py`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/PACKAGING.md` & `RIFT-0.0.15.9rc5/PACKAGING.md`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/PKG-INFO` & `RIFT-0.0.15.9rc5/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: RIFT
-Version: 0.0.15.9rc4
+Version: 0.0.15.9rc5
 Summary: RIFT parameter estimation pipeline. Note branch used is temp-RIT-Tides-port_python3_restructure_package (which will become master shortly)!
 Home-page: https://git.ligo.org/rapidpe-rift/rift
 Author: Richard O'Shaughnessy
 Author-email: richard.oshaughnessy@ligo.org
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `RIFT-0.0.15.9rc4/README.md` & `RIFT-0.0.15.9rc5/README.md`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/TROUBLESHOOTING.md` & `RIFT-0.0.15.9rc5/TROUBLESHOOTING.md`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/howto.md` & `RIFT-0.0.15.9rc5/howto.md`

 * *Files identical despite different names*

### Comparing `RIFT-0.0.15.9rc4/setup.py` & `RIFT-0.0.15.9rc5/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -30,15 +30,15 @@
 #  - ourio.py, ourparams.py
 #  - anything with 'test'
 #print " Identified scripts ", my_scripts\
 #print setuptools.find_packages('MonteCarloMarginalizeCode/Code')
 
 setuptools.setup(
     name="RIFT",
-    version="0.0.15.9rc4", # do not build on OSX machine, side effects
+    version="0.0.15.9rc5", # do not build on OSX machine, side effects
     author="Richard O'Shaughnessy",
     author_email="richard.oshaughnessy@ligo.org",
     description="RIFT parameter estimation pipeline. Note branch used is temp-RIT-Tides-port_python3_restructure_package (which will become master shortly)!",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://git.ligo.org/rapidpe-rift/rift",
     package_dir = {'':'MonteCarloMarginalizeCode/Code'},
```

