# Comparing `tmp/osl-dynamics-1.2.3.tar.gz` & `tmp/osl-dynamics-1.2.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "osl-dynamics-1.2.3.tar", last modified: Thu May 11 16:43:18 2023, max compression
+gzip compressed data, was "osl-dynamics-1.2.4.tar", last modified: Wed Jun 28 11:56:25 2023, max compression
```

## Comparing `osl-dynamics-1.2.3.tar` & `osl-dynamics-1.2.4.tar`

### file list

```diff
@@ -1,195 +1,194 @@
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:18.981915 osl-dynamics-1.2.3/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     4561 2023-05-11 16:43:18.982335 osl-dynamics-1.2.3/PKG-INFO
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     4248 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/README.rst
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:17.543504 osl-dynamics-1.2.3/osl_dynamics/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      643 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/__init__.py
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:17.652257 osl-dynamics-1.2.3/osl_dynamics/analysis/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      250 2023-05-09 14:36:05.000000 osl-dynamics-1.2.3/osl_dynamics/analysis/__init__.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    27101 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/analysis/connectivity.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6437 2023-05-09 14:35:55.000000 osl-dynamics-1.2.3/osl_dynamics/analysis/fisher_kernel.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6165 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/analysis/gmm.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    23992 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/analysis/modes.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    19627 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/analysis/power.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     3268 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/analysis/regression.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    44348 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/analysis/spectral.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     7487 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/analysis/static.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     8486 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/analysis/statistics.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    29697 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/analysis/tinda.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5688 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/analysis/workbench.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    10899 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/array_ops.py
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:17.660911 osl-dynamics-1.2.3/osl_dynamics/config_api/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      909 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/config_api/__init__.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5911 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/config_api/pipeline.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    50607 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/config_api/wrappers.py
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:17.730284 osl-dynamics-1.2.3/osl_dynamics/data/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      185 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/data/__init__.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    36748 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/data/base.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5833 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/data/osl.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6757 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/data/processing.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     8574 2023-05-10 09:37:57.000000 osl-dynamics-1.2.3/osl_dynamics/data/rw.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2809 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/data/spm.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2447 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/data/task.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     4726 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/data/tf.py
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:17.740887 osl-dynamics-1.2.3/osl_dynamics/files/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      883 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/__init__.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      434 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/functions.py
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:17.849839 osl-dynamics-1.2.3/osl_dynamics/files/mask/
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)     7241 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/mask/MNI152_T1_8mm_brain.nii.gz
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)   724726 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/mask/ParcellationPilot.L.inflated.32k_fs_LR.surf.gii
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)   723434 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/mask/ParcellationPilot.L.midthickness.32k_fs_LR.surf.gii
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)   723505 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/mask/ParcellationPilot.L.very_inflated.32k_fs_LR.surf.gii
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)   713031 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/mask/ParcellationPilot.R.inflated.32k_fs_LR.surf.gii
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)   710727 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/mask/ParcellationPilot.R.midthickness.32k_fs_LR.surf.gii
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)   712178 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/mask/ParcellationPilot.R.very_inflated.32k_fs_LR.surf.gii
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     1649 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/mask/__init__.py
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)      971 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/mask/ft_8mm_brain_mask.nii.gz
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:18.045358 osl-dynamics-1.2.3/osl_dynamics/files/parcellation/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    41373 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/parcellation/Glasser50_space-MNI152NLin6_res-8x8x8.nii.gz
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     9131 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/parcellation/Glasser52_binary_space-MNI152NLin6_res-8x8x8.nii.gz
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      669 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/parcellation/__init__.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    36166 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/parcellation/aal_cortical_merged_8mm_stacked.nii.gz
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)    23705 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/parcellation/fMRI_parcellation_ds8mm.nii.gz
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    24111 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_3PCC_ips_reduced_2mm_ss5mm_ds8mm.nii.gz
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    33885 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_3PCC_ips_reduced_2mm_ss5mm_ds8mm_adj.nii.gz
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)    23705 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_PCC_reduced_2mm_ss5mm_ds8mm.nii.gz
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)    63185 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_PCC_tighterMay15_v2_6mm_exclusive.nii.gz
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)    63835 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_PCC_tighterMay15_v2_8mm.nii.gz
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)     5233 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/parcellation/giles_39_binary.nii.gz
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:18.072484 osl-dynamics-1.2.3/osl_dynamics/files/scanner/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      268 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/__init__.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5568 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/ctf275_channel_names.npy
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:18.694018 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6679 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/4D148.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    11272 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/4D248.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    22296 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/4D248_helmet.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    42102 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/4D248_helmet.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     7077 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/CTF151.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    13813 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/CTF151_helmet.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    46654 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/CTF151_helmet.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    12927 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/CTF275.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    25461 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/CTF275_helmet.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    46654 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/CTF275_helmet.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    15330 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/EEG1005.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     3827 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/EEG1010.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      985 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/EEG1020.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     7134 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/QuikCap_NSL_128.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5164 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/QuikCap_NSL_128.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5813 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/acticap-64ch-standard2.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/acticap-64ch-standard2.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5697 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/biosemi128.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      770 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/biosemi16.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     7128 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/biosemi160.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    11414 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/biosemi256.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     1470 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/biosemi32.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2860 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/biosemi64.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5110 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/dccn_customized_acticap64.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6161 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/dccn_customized_acticap64.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6696 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM1.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM1.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5581 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM10.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6361 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM10.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5833 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM11.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6367 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM11.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    11302 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM14.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6361 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM14.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    11794 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM15.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6361 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM15.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     7800 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM16.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6362 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM16.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2643 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM17.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM17.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6873 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM20.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM20.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2547 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM22.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM22.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2985 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM23.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM23.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     3165 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM24.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM24.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2016 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM25.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM25.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2906 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM3.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM3.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2989 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM7.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6361 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM7.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    15330 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/elec1005.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     3827 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/elec1010.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      985 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/elec1020.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5269 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/mpi_customized_acticap64.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6161 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/mpi_customized_acticap64.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6127 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/natmeg_customized_eeg1005.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     3249 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag122cmb.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5961 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag122planar.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    14973 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306all.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2643 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306all_helmet.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306all_helmet.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5489 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306cmb.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6873 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306cmb_helmet.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306cmb_helmet.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     4979 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306mag.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2547 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306mag_helmet.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306mag_helmet.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     9969 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306planar.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2985 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306planar_helmet.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306planar_helmet.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5691 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/quickcap64.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6366 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/quickcap64.outline
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    20670 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/yokogawa440.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    19775 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/yokogawa440_old.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    14079 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/yokogawa440ag.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    20655 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/yokogawa440all.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6565 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/yokogawa440pg.lay
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     8696 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scanner/neuromag306_channel_names.npy
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:18.703959 osl-dynamics-1.2.3/osl_dynamics/files/scene/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)       82 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scene/__init__.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)  1511998 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/files/scene/mode_scene.scene
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:18.791588 osl-dynamics-1.2.3/osl_dynamics/inference/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      160 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/inference/__init__.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     7118 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/inference/callbacks.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     7410 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/inference/initializers.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    42321 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/inference/layers.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    11394 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/inference/metrics.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    19804 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/inference/modes.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6797 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/inference/regularizers.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     1647 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/inference/tf_ops.py
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:18.870350 osl-dynamics-1.2.3/osl_dynamics/models/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     1426 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/__init__.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    16781 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/dynemo.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    11105 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/dynemo_obs.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    42668 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/hmm.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    15849 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/inf_mod_base.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    23641 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/mage.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    20241 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/mdynemo.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    11366 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/mdynemo_obs.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    16639 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/mod_base.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    19196 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/sage.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    28945 2023-05-11 16:41:15.000000 osl-dynamics-1.2.3/osl_dynamics/models/sedynemo.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    30491 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/sedynemo_obs.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    36299 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/sehmm.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    13439 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/models/state_dynemo.py
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:18.918348 osl-dynamics-1.2.3/osl_dynamics/simulation/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      566 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/simulation/__init__.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      974 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/simulation/base.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    30162 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/simulation/hmm.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    12958 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/simulation/hsmm.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2710 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/simulation/mar.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    26028 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/simulation/mvn.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     4809 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/simulation/sin.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    10563 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/simulation/sm.py
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:18.973554 osl-dynamics-1.2.3/osl_dynamics/utils/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      287 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/utils/__init__.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     5701 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/utils/decorators.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    13545 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/utils/misc.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     6997 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/utils/model.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     2206 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/utils/parcellation.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)    59142 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/utils/plotting.py
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     9063 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/osl_dynamics/utils/topoplots.py
-drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-05-11 16:43:17.565668 osl-dynamics-1.2.3/osl_dynamics.egg-info/
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     4561 2023-05-11 16:43:17.562185 osl-dynamics-1.2.3/osl_dynamics.egg-info/PKG-INFO
--rw-r--r--   0 wlo995   (37469) woolrich (37107)     8308 2023-05-11 16:43:17.563420 osl-dynamics-1.2.3/osl_dynamics.egg-info/SOURCES.txt
--rw-r--r--   0 wlo995   (37469) woolrich (37107)        1 2023-05-11 16:43:17.564129 osl-dynamics-1.2.3/osl_dynamics.egg-info/dependency_links.txt
--rw-r--r--   0 wlo995   (37469) woolrich (37107)       85 2023-05-11 16:43:17.564572 osl-dynamics-1.2.3/osl_dynamics.egg-info/entry_points.txt
--rw-r--r--   0 wlo995   (37469) woolrich (37107)      141 2023-05-11 16:43:17.565173 osl-dynamics-1.2.3/osl_dynamics.egg-info/requires.txt
--rw-r--r--   0 wlo995   (37469) woolrich (37107)       13 2023-05-11 16:43:17.565881 osl-dynamics-1.2.3/osl_dynamics.egg-info/top_level.txt
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)     1175 2023-05-11 16:43:18.983535 osl-dynamics-1.2.3/setup.cfg
--rwxr-xr-x   0 wlo995   (37469) woolrich (37107)      189 2023-05-09 14:22:26.000000 osl-dynamics-1.2.3/setup.py
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:25.024306 osl-dynamics-1.2.4/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     4561 2023-06-28 11:56:25.024640 osl-dynamics-1.2.4/PKG-INFO
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     4248 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/README.rst
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:23.710602 osl-dynamics-1.2.4/osl_dynamics/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      643 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/__init__.py
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:23.844957 osl-dynamics-1.2.4/osl_dynamics/analysis/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      250 2023-05-09 14:36:05.000000 osl-dynamics-1.2.4/osl_dynamics/analysis/__init__.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    27101 2023-06-22 11:45:55.000000 osl-dynamics-1.2.4/osl_dynamics/analysis/connectivity.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6437 2023-05-09 14:35:55.000000 osl-dynamics-1.2.4/osl_dynamics/analysis/fisher_kernel.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6165 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/analysis/gmm.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    25514 2023-06-22 15:05:16.000000 osl-dynamics-1.2.4/osl_dynamics/analysis/modes.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    20303 2023-06-26 18:57:47.000000 osl-dynamics-1.2.4/osl_dynamics/analysis/power.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     3268 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/analysis/regression.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    46846 2023-06-22 08:42:10.000000 osl-dynamics-1.2.4/osl_dynamics/analysis/spectral.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     7487 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/analysis/static.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     8486 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/analysis/statistics.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    29690 2023-06-08 09:36:36.000000 osl-dynamics-1.2.4/osl_dynamics/analysis/tinda.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5688 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/analysis/workbench.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    10899 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/array_ops.py
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:23.876316 osl-dynamics-1.2.4/osl_dynamics/config_api/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      895 2023-06-19 18:50:42.000000 osl-dynamics-1.2.4/osl_dynamics/config_api/__init__.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5896 2023-06-19 18:50:42.000000 osl-dynamics-1.2.4/osl_dynamics/config_api/pipeline.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    56168 2023-06-22 15:05:16.000000 osl-dynamics-1.2.4/osl_dynamics/config_api/wrappers.py
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:23.952554 osl-dynamics-1.2.4/osl_dynamics/data/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      112 2023-06-28 08:10:13.000000 osl-dynamics-1.2.4/osl_dynamics/data/__init__.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    37114 2023-06-26 18:57:47.000000 osl-dynamics-1.2.4/osl_dynamics/data/base.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6757 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/data/processing.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     8574 2023-05-10 09:37:57.000000 osl-dynamics-1.2.4/osl_dynamics/data/rw.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2809 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/data/spm.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2447 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/data/task.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     4726 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/data/tf.py
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:23.970040 osl-dynamics-1.2.4/osl_dynamics/files/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      883 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/__init__.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      434 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/functions.py
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:24.092386 osl-dynamics-1.2.4/osl_dynamics/files/mask/
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)     7241 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/mask/MNI152_T1_8mm_brain.nii.gz
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)   724726 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/mask/ParcellationPilot.L.inflated.32k_fs_LR.surf.gii
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)   723434 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/mask/ParcellationPilot.L.midthickness.32k_fs_LR.surf.gii
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)   723505 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/mask/ParcellationPilot.L.very_inflated.32k_fs_LR.surf.gii
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)   713031 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/mask/ParcellationPilot.R.inflated.32k_fs_LR.surf.gii
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)   710727 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/mask/ParcellationPilot.R.midthickness.32k_fs_LR.surf.gii
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)   712178 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/mask/ParcellationPilot.R.very_inflated.32k_fs_LR.surf.gii
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     1649 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/mask/__init__.py
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)      971 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/mask/ft_8mm_brain_mask.nii.gz
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:24.186442 osl-dynamics-1.2.4/osl_dynamics/files/parcellation/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    41373 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/parcellation/Glasser50_space-MNI152NLin6_res-8x8x8.nii.gz
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     9131 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/parcellation/Glasser52_binary_space-MNI152NLin6_res-8x8x8.nii.gz
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      669 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/parcellation/__init__.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    36166 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/parcellation/aal_cortical_merged_8mm_stacked.nii.gz
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)    23705 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/parcellation/fMRI_parcellation_ds8mm.nii.gz
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    24111 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_3PCC_ips_reduced_2mm_ss5mm_ds8mm.nii.gz
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    33885 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_3PCC_ips_reduced_2mm_ss5mm_ds8mm_adj.nii.gz
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)    23705 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_PCC_reduced_2mm_ss5mm_ds8mm.nii.gz
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)    63185 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_PCC_tighterMay15_v2_6mm_exclusive.nii.gz
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)    63835 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_PCC_tighterMay15_v2_8mm.nii.gz
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)     5233 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/parcellation/giles_39_binary.nii.gz
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:24.210483 osl-dynamics-1.2.4/osl_dynamics/files/scanner/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      268 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/__init__.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5568 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/ctf275_channel_names.npy
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:24.684585 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6679 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/4D148.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    11272 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/4D248.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    22296 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/4D248_helmet.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    42102 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/4D248_helmet.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     7077 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/CTF151.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    13813 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/CTF151_helmet.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    46654 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/CTF151_helmet.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    12927 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/CTF275.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    25461 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/CTF275_helmet.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    46654 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/CTF275_helmet.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    15330 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/EEG1005.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     3827 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/EEG1010.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      985 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/EEG1020.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     7134 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/QuikCap_NSL_128.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5164 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/QuikCap_NSL_128.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5813 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/acticap-64ch-standard2.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/acticap-64ch-standard2.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5697 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/biosemi128.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      770 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/biosemi16.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     7128 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/biosemi160.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    11414 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/biosemi256.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     1470 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/biosemi32.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2860 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/biosemi64.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5110 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/dccn_customized_acticap64.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6161 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/dccn_customized_acticap64.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6696 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM1.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM1.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5581 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM10.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6361 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM10.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5833 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM11.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6367 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM11.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    11302 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM14.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6361 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM14.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    11794 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM15.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6361 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM15.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     7800 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM16.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6362 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM16.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2643 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM17.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM17.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6873 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM20.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM20.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2547 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM22.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM22.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2985 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM23.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM23.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     3165 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM24.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM24.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2016 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM25.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM25.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2906 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM3.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM3.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2989 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM7.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6361 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM7.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    15330 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/elec1005.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     3827 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/elec1010.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      985 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/elec1020.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5269 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/mpi_customized_acticap64.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6161 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/mpi_customized_acticap64.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6127 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/natmeg_customized_eeg1005.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     3249 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag122cmb.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5961 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag122planar.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    14973 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306all.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2643 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306all_helmet.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306all_helmet.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5489 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306cmb.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6873 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306cmb_helmet.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306cmb_helmet.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     4979 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306mag.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2547 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306mag_helmet.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306mag_helmet.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     9969 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306planar.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2985 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306planar_helmet.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6363 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306planar_helmet.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5691 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/quickcap64.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6366 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/quickcap64.outline
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    20670 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/yokogawa440.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    19775 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/yokogawa440_old.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    14079 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/yokogawa440ag.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    20655 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/yokogawa440all.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6565 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/yokogawa440pg.lay
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     8696 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scanner/neuromag306_channel_names.npy
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:24.686856 osl-dynamics-1.2.4/osl_dynamics/files/scene/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)       82 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scene/__init__.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)  1511998 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/files/scene/mode_scene.scene
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:24.801735 osl-dynamics-1.2.4/osl_dynamics/inference/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      160 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/inference/__init__.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     7118 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/inference/callbacks.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     7382 2023-06-27 10:28:22.000000 osl-dynamics-1.2.4/osl_dynamics/inference/initializers.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    43495 2023-06-08 10:40:24.000000 osl-dynamics-1.2.4/osl_dynamics/inference/layers.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    11394 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/inference/metrics.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    20066 2023-06-22 15:05:16.000000 osl-dynamics-1.2.4/osl_dynamics/inference/modes.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6797 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/inference/regularizers.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     1647 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/inference/tf_ops.py
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:24.922124 osl-dynamics-1.2.4/osl_dynamics/models/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     1426 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/models/__init__.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    17504 2023-06-26 18:57:47.000000 osl-dynamics-1.2.4/osl_dynamics/models/dynemo.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    11105 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/models/dynemo_obs.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    44792 2023-06-27 10:28:22.000000 osl-dynamics-1.2.4/osl_dynamics/models/hmm.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    24034 2023-06-27 14:18:42.000000 osl-dynamics-1.2.4/osl_dynamics/models/inf_mod_base.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    23641 2023-06-26 18:57:47.000000 osl-dynamics-1.2.4/osl_dynamics/models/mage.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    21074 2023-06-26 18:57:47.000000 osl-dynamics-1.2.4/osl_dynamics/models/mdynemo.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    11366 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/models/mdynemo_obs.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    16837 2023-06-27 14:18:42.000000 osl-dynamics-1.2.4/osl_dynamics/models/mod_base.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    19196 2023-06-26 18:57:47.000000 osl-dynamics-1.2.4/osl_dynamics/models/sage.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    31151 2023-06-26 18:57:47.000000 osl-dynamics-1.2.4/osl_dynamics/models/sedynemo.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    32160 2023-06-08 09:36:36.000000 osl-dynamics-1.2.4/osl_dynamics/models/sedynemo_obs.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    38592 2023-06-26 19:15:14.000000 osl-dynamics-1.2.4/osl_dynamics/models/sehmm.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    13448 2023-06-08 10:40:24.000000 osl-dynamics-1.2.4/osl_dynamics/models/state_dynemo.py
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:25.009595 osl-dynamics-1.2.4/osl_dynamics/simulation/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      566 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/simulation/__init__.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      974 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/simulation/base.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    30162 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/simulation/hmm.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    12958 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/simulation/hsmm.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2710 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/simulation/mar.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    26028 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/simulation/mvn.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     4809 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/simulation/sin.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    10563 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/simulation/sm.py
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:25.023256 osl-dynamics-1.2.4/osl_dynamics/utils/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      287 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/utils/__init__.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     5701 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/utils/decorators.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    13545 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/utils/misc.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     6997 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/utils/model.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     2206 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/utils/parcellation.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)    63282 2023-06-26 18:57:47.000000 osl-dynamics-1.2.4/osl_dynamics/utils/plotting.py
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     9063 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/osl_dynamics/utils/topoplots.py
+drwxr-sr-x   0 wlo995   (37469) woolrich (37107)        0 2023-06-28 11:56:23.728532 osl-dynamics-1.2.4/osl_dynamics.egg-info/
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     4561 2023-06-28 11:56:23.726351 osl-dynamics-1.2.4/osl_dynamics.egg-info/PKG-INFO
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)     8283 2023-06-28 11:56:23.726956 osl-dynamics-1.2.4/osl_dynamics.egg-info/SOURCES.txt
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)        1 2023-06-28 11:56:23.727411 osl-dynamics-1.2.4/osl_dynamics.egg-info/dependency_links.txt
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)       83 2023-06-28 11:56:23.727759 osl-dynamics-1.2.4/osl_dynamics.egg-info/entry_points.txt
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)      141 2023-06-28 11:56:23.728179 osl-dynamics-1.2.4/osl_dynamics.egg-info/requires.txt
+-rw-r--r--   0 wlo995   (37469) woolrich (37107)       13 2023-06-28 11:56:23.728653 osl-dynamics-1.2.4/osl_dynamics.egg-info/top_level.txt
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)     1173 2023-06-28 11:56:25.025452 osl-dynamics-1.2.4/setup.cfg
+-rwxr-xr-x   0 wlo995   (37469) woolrich (37107)      189 2023-05-09 14:22:26.000000 osl-dynamics-1.2.4/setup.py
```

### Comparing `osl-dynamics-1.2.3/PKG-INFO` & `osl-dynamics-1.2.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: osl-dynamics
-Version: 1.2.3
+Version: 1.2.4
 Summary: Models for infering dynamics in neuroimaging data
 Home-page: https://github.com/OHBA-analysis/osl-dynamics
 License: MIT
 Project-URL: Documentation, https://osl-dynamics.readthedocs.io/en/latest/
 Description-Content-Type: text/x-rst; charset=UTF-8
 
 ============
```

### Comparing `osl-dynamics-1.2.3/README.rst` & `osl-dynamics-1.2.4/README.rst`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/__init__.py` & `osl-dynamics-1.2.4/osl_dynamics/__init__.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/analysis/connectivity.py` & `osl-dynamics-1.2.4/osl_dynamics/analysis/connectivity.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/analysis/fisher_kernel.py` & `osl-dynamics-1.2.4/osl_dynamics/analysis/fisher_kernel.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/analysis/gmm.py` & `osl-dynamics-1.2.4/osl_dynamics/analysis/gmm.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/analysis/modes.py` & `osl-dynamics-1.2.4/osl_dynamics/analysis/modes.py`

 * *Files 4% similar despite different names*

```diff
@@ -2,14 +2,15 @@
 
 """
 
 import itertools
 import logging
 
 import numpy as np
+from scipy import signal
 
 from osl_dynamics import array_ops, inference
 
 _logger = logging.getLogger("osl-dynamics")
 
 
 def autocorrelation_functions(
@@ -398,19 +399,19 @@
         n_samples, n_states) or (n_samples, n_states).
     sampling_frequency : float
         Sampling frequency in Hz. If passed returns the lifetimes in seconds.
 
     Returns
     -------
     means : np.ndarray
-        Mean interval of each state. Shape is (n_subjects, n_states) or
-        (n_states,).
+        Mean interval of each state.
+        Shape is (n_subjects, n_states) or (n_states,).
     std : np.ndarray
-        Standard deviation of each state. Shape is (n_subjects, n_states) or
-        (n_states,).
+        Standard deviation of each state.
+        Shape is (n_subjects, n_states) or (n_states,).
     """
     intervals_ = intervals(
         state_time_course, sampling_frequency=sampling_frequency, squeeze=False
     )
     means = np.squeeze(array_ops.list_means(intervals_))
     stds = np.squeeze(array_ops.list_stds(intervals_))
     return means, stds
@@ -426,16 +427,16 @@
         n_samples, n_states) or (n_samples, n_states).
     sampling_frequency : float
         Sampling frequency in Hz. If passed returns the intervals in seconds.
 
     Returns
     -------
     mlt : np.ndarray
-        Mean interval of each state. Shape is (n_subjects, n_states) or
-        (n_states,).
+        Mean interval of each state.
+        Shape is (n_subjects, n_states) or (n_states,).
     """
     return interval_statistics(state_time_course, sampling_frequency)[0]
 
 
 def fractional_occupancies(state_time_course):
     """Calculate the fractional occupancy.
 
@@ -444,16 +445,16 @@
     state_time_course : list or np.ndarray
         State time course (strictly binary). Shape must be (n_subjects,
         n_samples, n_states) or (n_samples, n_states).
 
     Returns
     -------
     fo : np.ndarray
-        The fractional occupancy of each state. Shape is (n_subjects, n_states)
-        or (n_states,).
+        The fractional occupancy of each state.
+        Shape is (n_subjects, n_states) or (n_states,).
     """
     if isinstance(state_time_course, np.ndarray):
         if state_time_course.ndim == 2:
             state_time_course = [state_time_course]
         elif state_time_course.ndim != 3:
             raise ValueError(
                 "A (n_subjects, n_samples, n_states) or "
@@ -475,16 +476,16 @@
         n_samples, n_states) or (n_samples, n_states).
     sampling_frequency : float
         Sampling frequency in Hz. If None, defaults to 1 Hz.
 
     Returns
     -------
     sr : np.ndarray
-        The switching rate of each state. Shape is (n_subjects, n_states)
-        or (n_states,).
+        The switching rate of each state.
+        Shape is (n_subjects, n_states) or (n_states,).
     """
     if isinstance(state_time_course, np.ndarray):
         if state_time_course.ndim == 2:
             state_time_course = [state_time_course]
         elif state_time_course.ndim == 3:
             state_time_course = list(state_time_course)
 
@@ -502,14 +503,60 @@
 
         # Calculate switching rates
         sr.append(counts * sampling_frequency / n_samples)
 
     return np.squeeze(sr)
 
 
+def mean_amplitudes(state_time_course, data):
+    """Calculate mean amplitude for bursts.
+
+    Parameters
+    ----------
+    state_time_course : list or np.ndarray
+        State time course (strictly binary). Shape must be (n_subjects,
+        n_samples, n_states) or (n_samples, n_states).
+    data : list or np.ndarray
+        Single channel time series data (before calculating the amplitude envelope).
+        Shape must be (n_subjects, n_samples, 1) or
+        (n_samples, 1).
+
+    Returns
+    -------
+    amp : np.ndarray
+        Mean amplitude of the data for each state.
+        Shape is (n_subjects, n_states) or (n_states,).
+    """
+    if isinstance(state_time_course, np.ndarray):
+        if state_time_course.ndim == 2:
+            state_time_course = [state_time_course]
+        elif state_time_course.ndim == 3:
+            state_time_course = list(state_time_course)
+
+    if isinstance(data, np.ndarray):
+        if data.ndim == 2:
+            data = [data]
+        elif data.ndim == 3:
+            data = list(data)
+
+    n_subjects = len(state_time_course)
+    n_states = state_time_course[0].shape[1]
+
+    # Calculate amplitude envelope of data
+    data = [abs(signal.hilbert(d, axis=0)) for d in data]
+
+    # Calculate mean amplitude envelope when each state is on
+    amp = np.empty([n_subjects, n_states])
+    for i in range(n_subjects):
+        for j in range(n_states):
+            amp[i, j] = np.mean(data[i][state_time_course[i][:, j] == 1])
+
+    return np.squeeze(amp)
+
+
 def fano_factor(
     state_time_course,
     window_lengths,
     sampling_frequency=1.0,
 ):
     """Calculate the Fano factor.
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/analysis/power.py` & `osl-dynamics-1.2.4/osl_dynamics/analysis/power.py`

 * *Files 2% similar despite different names*

```diff
@@ -356,23 +356,23 @@
         power_map -= np.average(power_map, axis=1, weights=mean_weights)[
             :, np.newaxis, ...
         ]
 
     # Select the component to plot
     power_map = power_map[component]
 
-    original_max = power_map.max()
-    original_min = power_map.min()
-
     if asymmetric_data:
         # Scale power map to be between -1 and 1
-        power_map -= power_map.min()
-        power_map /= power_map.max()
-        power_map *= 2
-        power_map -= 1
+        original_mins = power_map.min(axis=-1)
+        original_maxs = power_map.max(axis=-1)
+        for p, min_, max_ in zip(power_map, original_mins, original_maxs):
+            p -= min_
+            p /= max_ - min_
+            p *= 2
+            p -= 1
 
     # Calculate power map grid
     power_map = power_map_grid(mask_file, parcellation_file, power_map)
 
     # Load the mask
     mask = nib.load(mask_file)
 
@@ -382,29 +382,30 @@
     # Keyword arguments to pass to nilearn.plotting.plot_img_on_surf
     default_plot_kwargs = {
         "views": ["lateral", "medial"],
         "hemisphere": ["left", "right"],
         "colorbar": True,
     }
     plot_kwargs = utils.misc.override_dict_defaults(default_plot_kwargs, plot_kwargs)
-    cmap = plot_kwargs.get("cmap", "cold_hot")
 
     # Just display the power map
     if filename is None:
         figures, axes = [], []
         for i in trange(n_modes, desc="Saving images"):
             nii = nib.Nifti1Image(power_map[:, :, :, i], mask.affine, mask.header)
             fig, ax = plotting.plot_img_on_surf(nii, output_file=None, **plot_kwargs)
             figures.append(fig)
             axes.append(ax)
             if asymmetric_data:
                 plt.colorbar(
                     plt.cm.ScalarMappable(
-                        plt.matplotlib.colors.Normalize(original_min, original_max),
-                        cmap=cmap,
+                        plt.matplotlib.colors.Normalize(
+                            original_mins[i], original_maxs[i]
+                        ),
+                        cmap=plot_kwargs.get("cmap", "cold_hot"),
                     ),
                     cax=ax[-1],
                     orientation="horizontal",
                 )
         return figures, axes
 
     else:
@@ -414,18 +415,32 @@
             nii = nib.Nifti1Image(power_map, mask.affine, mask.header)
             nib.save(nii, filename)
 
         else:
             # Save each map as an image
             for i in trange(n_modes, desc="Saving images"):
                 nii = nib.Nifti1Image(power_map[:, :, :, i], mask.affine, mask.header)
+                fig, ax = plotting.plot_img_on_surf(
+                    nii, output_file=None, **plot_kwargs
+                )
+                if asymmetric_data:
+                    plt.colorbar(
+                        plt.cm.ScalarMappable(
+                            plt.matplotlib.colors.Normalize(
+                                original_mins[i], original_maxs[i]
+                            ),
+                            cmap=plot_kwargs.get("cmap", "cold_hot"),
+                        ),
+                        cax=ax[-1],
+                        orientation="horizontal",
+                    )
                 output_file = "{fn.parent}/{fn.stem}{i:0{w}d}{fn.suffix}".format(
                     fn=Path(filename), i=i, w=len(str(n_modes))
                 )
-                plotting.plot_img_on_surf(nii, output_file=output_file, **plot_kwargs)
+                fig.savefig(output_file)
 
 
 def multi_save(
     group_power_map,
     subject_power_map,
     mask_file,
     parcellation_file,
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/analysis/regression.py` & `osl-dynamics-1.2.4/osl_dynamics/analysis/regression.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/analysis/spectral.py` & `osl-dynamics-1.2.4/osl_dynamics/analysis/spectral.py`

 * *Files 2% similar despite different names*

```diff
@@ -3,14 +3,15 @@
 """
 
 import logging
 import warnings
 
 import numpy as np
 from pqdm.processes import pqdm
+from scipy import signal
 from scipy.signal.windows import dpss, hann
 from sklearn.decomposition import non_negative_factorization
 from tqdm.auto import trange
 
 from osl_dynamics import array_ops
 from osl_dynamics.analysis import regression
 
@@ -1392,7 +1393,90 @@
     max_alpha = [np.max(a, axis=0) for a in alpha]
 
     # Rescale the regression coefficients
     for n in range(n_subjects):
         psd[n, 0] *= np.expand_dims(max_alpha[n], axis=(1, 2))
 
     return psd
+
+
+def wavelet(
+    data,
+    sampling_frequency,
+    w=5,
+    standardize=True,
+    time_range=None,
+    frequency_range=None,
+):
+    """Calculate a wavelet transform.
+
+    This function uses a scipy.signal.morlet2 window to calculate
+    the wavelet transform.
+
+    Parameters
+    ----------
+    data : np.ndarray
+        1D time series data.
+    sampling_frequency : float
+        Sampling frequency in Hz.
+    w : float
+        w parameter to pass to scipy.signal.morlet2.
+    standardize : bool
+        Should we standardize the data before calculating the wavelet?
+    time_range : list
+        Start time and end time to plot in seconds.
+        Default is the full time axis of the data.
+    frequency_range : list of length 2
+        Start and end frequency to plot in Hertz.
+        Default is [1, sampling_frequency / 2].
+
+    Returns
+    -------
+    t : np.ndarray
+        1D numpy array for the time axis.
+    f : np.ndarray
+        1D numpy array for the frequency axis.
+    wt : np.ndarray
+        2D numpy array (frequency, time) containing the wavelet transform.
+    """
+    # Validation
+    if np.array(data).ndim != 1:
+        raise ValueError("data must be a 1D numpy array.")
+
+    if time_range is None:
+        time_range = [0, data.shape[0] / sampling_frequency]
+    if time_range[0] is None:
+        time_range[0] = 0
+    if time_range[1] is None:
+        time_range[1] = data.shape[0] / sampling_frequency
+
+    if frequency_range is None:
+        frequency_range = [1, sampling_frequency / 2]
+    if frequency_range[0] is None:
+        frequency_range[0] = 1
+    if frequency_range[1] is None:
+        frequency_range[1] = sampling_frequency / 2
+
+    # Standardize the data
+    if standardize:
+        data = (data - np.mean(data)) / np.std(data)
+
+    # Keep selected time points
+    start_index = int(time_range[0] * sampling_frequency)
+    end_index = int(time_range[1] * sampling_frequency)
+    data = data[start_index:end_index]
+
+    # Time axis (s)
+    t = np.arange(time_range[0], time_range[1], 1 / sampling_frequency)
+
+    # Frequency axis (Hz)
+    # Use 100 equally spaced points (on a linear scale)
+    f = np.linspace(frequency_range[0], frequency_range[1], 100)
+
+    # Calculate the width for each Morlet window based on the frequency
+    widths = w * sampling_frequency / (2 * f * np.pi)
+
+    # Calculate wavelet transform
+    wt = signal.cwt(data=data, wavelet=signal.morlet2, widths=widths, w=w)
+    wt = abs(wt)
+
+    return t, f, wt
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/analysis/static.py` & `osl-dynamics-1.2.4/osl_dynamics/analysis/static.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/analysis/statistics.py` & `osl-dynamics-1.2.4/osl_dynamics/analysis/statistics.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/analysis/tinda.py` & `osl-dynamics-1.2.4/osl_dynamics/analysis/tinda.py`

 * *Files 1% similar despite different names*

```diff
@@ -297,18 +297,18 @@
 def collate_stats(stats, field, all_to_all=False, ignore_elements=[]):
     """Collate list of stats (e.g., of different states) into a single array.
 
     Parameters
     ----------
     stats : list
         List of stats (dict) for each state. Each element is a dictionary with keys that
-        at least should include "field" (e.g., interval_wavgs), that is the output of
+        at least should include "field" (e.g., interval_wavg), that is the output of
         compute_fo_stats.
     field : str
-        Field of stats to collate, e.g., "interval_wavgs", "interval_sums".
+        Field of stats to collate, e.g., "interval_wavg", "interval_sum".
     all_to_all : bool
         Whether the density_of was used to compute the stats (in which case the first
         2 dimensions are not n_states x n_states). Default is False.
     ignore_elements : list
         List of indices in stats to ignore (i.e. because they don't contain binary
         events).
 
@@ -371,15 +371,15 @@
         Array of bin edges (in samples, seconds, or percentiles) used to split durations
         into bins (default None), e.g. np.arange(0, 1, 0.1) for 100ms bins.
     sampling_frequency : float
         Sampling frequency of tc (in Hz), only used if interval_mode is "sec".
     return_all_intervals : bool
         Whether to return the density/sum of all intervals in addition to the interval
         averages/sums. If True, will return a list of arrays in
-        stats[i]['all_interval_wavgs'/'all_interval_sums'], each corresponding to an
+        stats[i]['all_interval_wavg'/'all_interval_sum'], each corresponding to an
         interval range.
 
     Returns
     -------
     fo_density : array_like
         Time-in-state densities array of shape (n_interval_states, n_density_states,
         n_bins, n_interval_ranges). n_interval_states is the number of states in the
@@ -506,21 +506,21 @@
                         "all_interval_sum": all_interval_sum,
                     }
                 )
 
         # Get a full matrix of FO densities and sums
         fo_density = collate_stats(
             stats,
-            "interval_wavgs",
+            "interval_wavg",
             all_to_all=density_of is None,
             ignore_elements=ignore_elements,
         )
         fo_sum = collate_stats(
             stats,
-            "interval_sums",
+            "interval_sum",
             all_to_all=density_of is None,
             ignore_elements=ignore_elements,
         )
 
     return fo_density, fo_sum, stats
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/analysis/workbench.py` & `osl-dynamics-1.2.4/osl_dynamics/analysis/workbench.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/array_ops.py` & `osl-dynamics-1.2.4/osl_dynamics/array_ops.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/config_api/__init__.py` & `osl-dynamics-1.2.4/osl_dynamics/config_api/__init__.py`

 * *Files 12% similar despite different names*

```diff
@@ -2,28 +2,28 @@
 
 See the `toolbox examples
 <https://github.com/OHBA-analysis/osl-dynamics/tree/main/examples/toolbox_paper>`_
 for scripts that use the config API.
 
 Note, the config API can be used via the command line with::
 
-    % osld-pipeline <config-file> <output-directory> <restrict>
+    % osl-dynamics <config-file> <output-directory>
 
 where
 
 - :code:`<config-file>` is a yaml file containing the config.
 - :code:`<output-directory>` is the output directory.
 
 Optionally, you can specify a particular GPU to use with::
 
-    % osld-pipeline <config-file> <output-directory> --restrict <restrict>
+    % osl-dynamics <config-file> <output-directory> --restrict <restrict>
 
 where :code:`<restrict>` is an integer specifying the GPU number. E.g. if you would
 just like to use the first GPU, you can pass::
 
-    % osld-pipeline <config-file> <output-directory> --restrict 0
+    % osl-dynamics <config-file> <output-directory> --restrict 0
 
 Remember you need to activate the :code:`osld` conda environment to use the
 command line interface.
 """
 
 from osl_dynamics.config_api import pipeline, wrappers
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/config_api/pipeline.py` & `osl-dynamics-1.2.4/osl_dynamics/config_api/pipeline.py`

 * *Files 3% similar despite different names*

```diff
@@ -2,29 +2,29 @@
 
 See the `toolbox examples
 <https://github.com/OHBA-analysis/osl-dynamics/tree/main/examples/toolbox_paper>`_
 for scripts that use the config API.
 
 Note, the config API can be used via the command line with::
 
-    % osld-pipeline <config-file> <output-directory> <restrict>
+    % osl-dynamics <config-file> <output-directory>
 
 where
 
 - :code:`<config-file>` is a yaml file containing the config.
 - :code:`<output-directory>` is the output directory.
 
 Optionally, you can specify a particular GPU to use with::
 
-    % osld-pipeline <config-file> <output-directory> --restrict <restrict>
+    % osl-dynamics <config-file> <output-directory> --restrict <restrict>
 
 where :code:`<restrict>` is an integer specifying the GPU number. E.g. if you would
 just like to use the first GPU, you can pass::
 
-    % osld-pipeline <config-file> <output-directory> --restrict 0
+    % osl-dynamics <config-file> <output-directory> --restrict 0
 
 Remember you need to activate the :code:`osld` conda environment to use the
 command line interface.
 """
 
 import argparse
 import logging
@@ -181,15 +181,15 @@
         tp_ops.gpu_growth()
     config_path = Path(config_file)
     config = config_path.read_text()
 
     run_pipeline(config, output_directory)
 
 
-def osld_pipeline_cli():
+def osl_dynamics_cli():
     """Command line interface function for running a pipeline from a config file."""
 
     # Arguments
     parser = argparse.ArgumentParser()
     parser.add_argument(
         "config_file",
         type=str,
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/config_api/wrappers.py` & `osl-dynamics-1.2.4/osl_dynamics/config_api/wrappers.py`

 * *Files 4% similar despite different names*

```diff
@@ -276,14 +276,85 @@
 
         # Save inferred parameters
         save(f"{inf_params_dir}/alp.pkl", alpha)
         save(f"{inf_params_dir}/means.npy", means)
         save(f"{inf_params_dir}/covs.npy", covs)
 
 
+def plot_tde_covariances(data, output_dir):
+    """Plot inferred covariance of the time-delay embedded data.
+
+    This function expects a model has already been trained and the following
+    directory to exist:
+
+    - :code:`<output_dir>/inf_params`, which contains the inferred parameters.
+
+    This function will output a :code:`tde_covs.png` file containing a plot of
+    the covariances in the :code:`<output_dir>/inf_params` directory.
+
+    Parameters
+    ----------
+    data : osl_dynamics.data.Data
+        Data object.
+    output_dir : str
+        Path to output directory.
+    """
+    inf_params_dir = f"{output_dir}/inf_params"
+
+    covs = load(f"{inf_params_dir}/covs.npy")
+
+    if hasattr(data, "pca_components"):
+        if data.pca_components is not None:
+            from osl_dynamics.analysis import modes
+
+            covs = modes.reverse_pca(covs, pca_components)
+
+    from osl_dynamics.utils import plotting
+
+    plotting.plot_matrices(covs, filename=f"{inf_params_dir}/tde_covs.png")
+
+
+def plot_state_psds(data, output_dir):
+    """Plot state PSDs.
+
+    This function expects multitaper spectra to have already been calculated
+    and are in:
+
+    - :code:`<output_dir>/spectra`.
+
+    This function will output a file called :code:`psds.png` which contains
+    a plot of each state PSD.
+
+    Parameters
+    ----------
+    data : osl_dynamics.data.Data
+        Data object.
+    output_dir : str
+        Path to output directory.
+    """
+    spectra_dir = f"{output_dir}/spectra"
+
+    f = load(f"{spectra_dir}/f.npy")
+    psd = load(f"{spectra_dir}/psd.npy")
+    psd = np.mean(psd, axis=(0, 2))  # average over subjects and channels
+    n_states = psd.shape[0]
+
+    from osl_dynamics.utils import plotting
+
+    plotting.plot_line(
+        [f] * n_states,
+        psd,
+        labels=[f"State {i + 1}" for i in range(n_states)],
+        x_label="Frequency (Hz)",
+        y_label="PSD (a.u.)",
+        x_range=[f[0], f[-1]],
+        filename=f"{spectra_dir}/psds.png",
+    )
+
+
 def calc_subject_ae_hmm_networks(data, output_dir):
     """Calculate subject-specific AE-HMM networks.
 
     This function expects a model has already been trained and the following
     directory to exist:
 
     - :code:`<output_dir>/inf_params`, which contains the inferred parameters.
@@ -396,15 +467,15 @@
     # Unpack spectra and save
     return_weights = kwargs.pop("return_weights", False)
     if return_weights:
         f, psd, coh, w = spectra
         save(f"{spectra_dir}/f.npy", f)
         save(f"{spectra_dir}/psd.npy", psd)
         save(f"{spectra_dir}/coh.npy", coh)
-        save(f"{spectra_dir}/w.npy")
+        save(f"{spectra_dir}/w.npy", w)
     else:
         f, psd, coh = spectra
         save(f"{spectra_dir}/f.npy", f)
         save(f"{spectra_dir}/psd.npy", psd)
         save(f"{spectra_dir}/coh.npy", coh)
 
     if nnmf_components is not None:
@@ -1262,16 +1333,18 @@
     from osl_dynamics.inference import modes
 
     _logger.info(f"Using kwargs: {kwargs}")
     gmm_alp = modes.gmm_time_courses(alp, **kwargs)
     save(f"{inf_params_dir}/gmm_alp.pkl", gmm_alp)
 
 
-def plot_summary_stats(data, output_dir, use_gmm_alpha=False, sampling_frequency=None):
-    """Plot summary statistics as violin plots.
+def plot_hmm_network_summary_stats(
+    data, output_dir, use_gmm_alpha=False, sampling_frequency=None
+):
+    """Plot HMM summary statistics for networks as violin plots.
 
     This function will plot the distribution over subjects for the following summary
     statistics:
 
     - Fractional occupancy.
     - Mean lifetime (s).
     - Mean interval (s).
@@ -1515,7 +1588,118 @@
         plotting.plot_summary_stats_group_diff(
             name=labels[i],
             summary_stats=sum_stats[:, i],
             pvalues=pvalues[i],
             assignments=assignments,
             filename=f"{group_diff_dir}/{names[i]}.png",
         )
+
+
+def plot_burst_summary_stats(data, output_dir, sampling_frequency=None):
+    """Plot burst summary statistics as violin plots.
+
+    This function will plot the distribution over subjects for the following summary
+    statistics:
+
+    - Mean lifetime (s).
+    - Mean interval (s).
+    - Burst count (Hz).
+    - Mean amplitude (a.u.).
+
+    This function expects a model has been trained and the following directories to exist:
+
+    - :code:`<output_dir>/model`, which contains the trained model.
+    - :code:`<output_dir>/inf_params`, which contains the inferred parameters.
+
+    This function will create:
+
+    - :code:`<output_dir>/summary_stats`, which contains plots of the summary statistics.
+
+    The :code:`<output_dir>/summary_stats` directory will also contain numpy files
+    with the summary statistics.
+
+    Parameters
+    ----------
+    data : osl_dynamics.data.Data
+        Data object.
+    output_dir : str
+        Path to output directory.
+    sampling_frequency : float
+        Sampling frequency in Hz. Optional. If :code:`None`, we use
+        :code:`data.sampling_frequency`.
+    """
+    if sampling_frequency is None:
+        if data is None or data.sampling_frequency is None:
+            raise ValueError(
+                "sampling_frequency must be passed or specified in the Data object."
+            )
+        else:
+            sampling_frequency = data.sampling_frequency
+
+    # Directories
+    model_dir = output_dir + "/model"
+    inf_params_dir = output_dir + "/inf_params"
+    summary_stats_dir = output_dir + "/summary_stats"
+    os.makedirs(summary_stats_dir, exist_ok=True)
+
+    from osl_dynamics.inference import modes
+
+    # Load state time course
+    alp = load(f"{inf_params_dir}/alp.pkl")
+    stc = modes.argmax_time_courses(alp)
+
+    # Get the config used to create the model
+    from osl_dynamics.models.mod_base import ModelBase
+
+    model_config, _ = ModelBase.load_config(model_dir)
+
+    # Get unprepared data (i.e. the data before calling Data.prepare)
+    # We also trim the data to account for the data points lost to
+    # time embedding or applying a sliding window
+    data = data.trim_time_series(
+        sequence_length=model_config["sequence_length"], prepared=False
+    )
+
+    # Calculate summary stats
+    lt = modes.mean_lifetimes(stc, sampling_frequency)
+    intv = modes.mean_intervals(stc, sampling_frequency)
+    bc = modes.switching_rates(stc, sampling_frequency)
+    amp = modes.mean_amplitudes(stc, data)
+
+    # Save summary stats
+    save(f"{summary_stats_dir}/lt.npy", lt)
+    save(f"{summary_stats_dir}/intv.npy", intv)
+    save(f"{summary_stats_dir}/bc.npy", bc)
+    save(f"{summary_stats_dir}/amp.npy", amp)
+
+    from osl_dynamics.utils import plotting
+
+    # Plot
+    n_states = lt.shape[1]
+    plotting.plot_violin(
+        lt.T,
+        x=range(1, n_states + 1),
+        x_label="State",
+        y_label="Mean Lifetime (s)",
+        filename=f"{summary_stats_dir}/fo.png",
+    )
+    plotting.plot_violin(
+        intv.T,
+        x=range(1, n_states + 1),
+        x_label="State",
+        y_label="Mean Interval (s)",
+        filename=f"{summary_stats_dir}/intv.png",
+    )
+    plotting.plot_violin(
+        bc.T,
+        x=range(1, n_states + 1),
+        x_label="State",
+        y_label="Burst Count (Hz)",
+        filename=f"{summary_stats_dir}/bc.png",
+    )
+    plotting.plot_violin(
+        amp.T,
+        x=range(1, n_states + 1),
+        x_label="State",
+        y_label="Mean Amplitude (a.u.)",
+        filename=f"{summary_stats_dir}/amp.png",
+    )
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/data/base.py` & `osl-dynamics-1.2.4/osl_dynamics/data/base.py`

 * *Files 2% similar despite different names*

```diff
@@ -193,31 +193,41 @@
         Parameters
         ----------
         sampling_frequency : float
             Sampling frequency in Hz.
         """
         self.sampling_frequency = sampling_frequency
 
-    def time_series(self, concatenate=False):
+    def time_series(self, prepared=True, concatenate=False):
         """Time series data for all subjects.
 
         Parameters
         ----------
+        prepared : bool
+            Should we return the latest data after we have prepared it or
+            the original data we loaded into the Data object?
         concatenate : bool
             Should we return the time series for each subject concatenated?
 
         Returns
         -------
         ts : list or np.ndarray
             Time series data for each subject.
         """
+        # What data should we return?
+        if prepared:
+            memmaps = self.subjects
+        else:
+            memmaps = self.raw_data_memmaps
+
+        # Should we return one long time series?
         if concatenate or self.n_subjects == 1:
-            return np.concatenate(self.subjects)
+            return np.concatenate(memmaps)
         else:
-            return self.subjects
+            return memmaps
 
     def delete_dir(self):
         """Deletes store_dir."""
         if self.store_dir.exists():
             rmtree(self.store_dir)
 
     def load_preparation(self, inputs):
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/data/processing.py` & `osl-dynamics-1.2.4/osl_dynamics/data/processing.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/data/rw.py` & `osl-dynamics-1.2.4/osl_dynamics/data/rw.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/data/spm.py` & `osl-dynamics-1.2.4/osl_dynamics/data/spm.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/data/task.py` & `osl-dynamics-1.2.4/osl_dynamics/data/task.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/data/tf.py` & `osl-dynamics-1.2.4/osl_dynamics/data/tf.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/__init__.py` & `osl-dynamics-1.2.4/osl_dynamics/files/__init__.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/mask/MNI152_T1_8mm_brain.nii.gz` & `osl-dynamics-1.2.4/osl_dynamics/files/mask/MNI152_T1_8mm_brain.nii.gz`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/mask/ParcellationPilot.L.inflated.32k_fs_LR.surf.gii` & `osl-dynamics-1.2.4/osl_dynamics/files/mask/ParcellationPilot.L.inflated.32k_fs_LR.surf.gii`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/mask/ParcellationPilot.L.midthickness.32k_fs_LR.surf.gii` & `osl-dynamics-1.2.4/osl_dynamics/files/mask/ParcellationPilot.L.midthickness.32k_fs_LR.surf.gii`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/mask/ParcellationPilot.L.very_inflated.32k_fs_LR.surf.gii` & `osl-dynamics-1.2.4/osl_dynamics/files/mask/ParcellationPilot.L.very_inflated.32k_fs_LR.surf.gii`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/mask/ParcellationPilot.R.inflated.32k_fs_LR.surf.gii` & `osl-dynamics-1.2.4/osl_dynamics/files/mask/ParcellationPilot.R.inflated.32k_fs_LR.surf.gii`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/mask/ParcellationPilot.R.midthickness.32k_fs_LR.surf.gii` & `osl-dynamics-1.2.4/osl_dynamics/files/mask/ParcellationPilot.R.midthickness.32k_fs_LR.surf.gii`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/mask/ParcellationPilot.R.very_inflated.32k_fs_LR.surf.gii` & `osl-dynamics-1.2.4/osl_dynamics/files/mask/ParcellationPilot.R.very_inflated.32k_fs_LR.surf.gii`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/mask/__init__.py` & `osl-dynamics-1.2.4/osl_dynamics/files/mask/__init__.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/mask/ft_8mm_brain_mask.nii.gz` & `osl-dynamics-1.2.4/osl_dynamics/files/mask/ft_8mm_brain_mask.nii.gz`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/parcellation/Glasser50_space-MNI152NLin6_res-8x8x8.nii.gz` & `osl-dynamics-1.2.4/osl_dynamics/files/parcellation/Glasser50_space-MNI152NLin6_res-8x8x8.nii.gz`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/parcellation/Glasser52_binary_space-MNI152NLin6_res-8x8x8.nii.gz` & `osl-dynamics-1.2.4/osl_dynamics/files/parcellation/Glasser52_binary_space-MNI152NLin6_res-8x8x8.nii.gz`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/parcellation/__init__.py` & `osl-dynamics-1.2.4/osl_dynamics/files/parcellation/__init__.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/parcellation/aal_cortical_merged_8mm_stacked.nii.gz` & `osl-dynamics-1.2.4/osl_dynamics/files/parcellation/aal_cortical_merged_8mm_stacked.nii.gz`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/parcellation/fMRI_parcellation_ds8mm.nii.gz` & `osl-dynamics-1.2.4/osl_dynamics/files/parcellation/fMRI_parcellation_ds8mm.nii.gz`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_3PCC_ips_reduced_2mm_ss5mm_ds8mm.nii.gz` & `osl-dynamics-1.2.4/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_3PCC_ips_reduced_2mm_ss5mm_ds8mm.nii.gz`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_3PCC_ips_reduced_2mm_ss5mm_ds8mm_adj.nii.gz` & `osl-dynamics-1.2.4/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_3PCC_ips_reduced_2mm_ss5mm_ds8mm_adj.nii.gz`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_PCC_reduced_2mm_ss5mm_ds8mm.nii.gz` & `osl-dynamics-1.2.4/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_PCC_reduced_2mm_ss5mm_ds8mm.nii.gz`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_PCC_tighterMay15_v2_6mm_exclusive.nii.gz` & `osl-dynamics-1.2.4/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_PCC_tighterMay15_v2_6mm_exclusive.nii.gz`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_PCC_tighterMay15_v2_8mm.nii.gz` & `osl-dynamics-1.2.4/osl_dynamics/files/parcellation/fmri_d100_parcellation_with_PCC_tighterMay15_v2_8mm.nii.gz`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/parcellation/giles_39_binary.nii.gz` & `osl-dynamics-1.2.4/osl_dynamics/files/parcellation/giles_39_binary.nii.gz`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/ctf275_channel_names.npy` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/ctf275_channel_names.npy`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/4D148.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/4D148.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/4D248.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/4D248.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/4D248_helmet.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/4D248_helmet.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/4D248_helmet.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/4D248_helmet.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/CTF151.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/CTF151.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/CTF151_helmet.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/CTF151_helmet.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/CTF151_helmet.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/CTF151_helmet.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/CTF275.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/CTF275.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/CTF275_helmet.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/CTF275_helmet.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/CTF275_helmet.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/CTF275_helmet.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/EEG1005.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/EEG1005.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/EEG1010.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/EEG1010.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/EEG1020.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/EEG1020.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/QuikCap_NSL_128.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/QuikCap_NSL_128.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/QuikCap_NSL_128.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/QuikCap_NSL_128.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/acticap-64ch-standard2.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/acticap-64ch-standard2.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/acticap-64ch-standard2.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/acticap-64ch-standard2.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/biosemi128.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/biosemi128.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/biosemi16.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/biosemi16.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/biosemi160.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/biosemi160.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/biosemi256.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/biosemi256.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/biosemi32.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/biosemi32.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/biosemi64.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/biosemi64.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/dccn_customized_acticap64.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/dccn_customized_acticap64.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/dccn_customized_acticap64.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/dccn_customized_acticap64.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM1.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM1.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM1.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM1.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM10.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM10.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM10.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM10.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM11.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM11.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM11.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM11.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM14.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM14.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM14.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM14.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM15.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM15.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM15.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM15.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM16.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM16.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM16.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM16.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM17.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM17.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM17.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM17.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM20.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM20.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM20.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM20.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM22.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM22.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM22.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM22.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM23.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM23.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM23.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM23.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM24.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM24.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM24.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM24.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM25.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM25.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM25.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM25.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM3.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM3.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM3.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM3.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM7.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM7.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/easycapM7.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/easycapM7.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/elec1005.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/elec1005.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/elec1010.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/elec1010.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/elec1020.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/elec1020.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/mpi_customized_acticap64.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/mpi_customized_acticap64.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/mpi_customized_acticap64.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/mpi_customized_acticap64.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/natmeg_customized_eeg1005.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/natmeg_customized_eeg1005.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag122cmb.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag122cmb.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag122planar.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag122planar.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306all.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306all.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306all_helmet.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306all_helmet.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306all_helmet.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306all_helmet.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306cmb.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306cmb.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306cmb_helmet.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306cmb_helmet.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306cmb_helmet.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306cmb_helmet.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306mag.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306mag.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306mag_helmet.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306mag_helmet.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306mag_helmet.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306mag_helmet.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306planar.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306planar.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306planar_helmet.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306planar_helmet.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/neuromag306planar_helmet.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/neuromag306planar_helmet.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/quickcap64.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/quickcap64.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/quickcap64.outline` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/quickcap64.outline`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/yokogawa440.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/yokogawa440.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/yokogawa440_old.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/yokogawa440_old.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/yokogawa440ag.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/yokogawa440ag.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/yokogawa440all.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/yokogawa440all.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/layouts/yokogawa440pg.lay` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/layouts/yokogawa440pg.lay`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scanner/neuromag306_channel_names.npy` & `osl-dynamics-1.2.4/osl_dynamics/files/scanner/neuromag306_channel_names.npy`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/files/scene/mode_scene.scene` & `osl-dynamics-1.2.4/osl_dynamics/files/scene/mode_scene.scene`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/inference/callbacks.py` & `osl-dynamics-1.2.4/osl_dynamics/inference/callbacks.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/inference/initializers.py` & `osl-dynamics-1.2.4/osl_dynamics/inference/initializers.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,19 @@
 """Initializers for TensorFlow layers.
 
 """
 
+from copy import deepcopy
+
 import numpy as np
-import tensorflow_probability as tfp
 import tensorflow as tf
+import tensorflow_probability as tfp
 from tensorflow.keras import Model, layers, initializers
 from tensorflow.keras.initializers import Initializer
+
 from osl_dynamics import inference
 
 tfb = tfp.bijectors
 
 
 class WeightInitializer(Initializer):
     """Initialize weights to given value.
@@ -179,16 +182,15 @@
             new_initializer = initializer
 
         elif isinstance(init_container.__dict__[key], Initializer):
             # We have a standard TensorFlow initializer
             #
             # We need to create a new initializer to get new
             # random values
-            new_initializer = initializer_type()
-            init_container.__dict__[key] = new_initializer
+            new_initializer = deepcopy(initializer)
 
         # Get the variable (i.e. weights) we want to re-initialize
         if key == "recurrent_initializer":
             var = getattr(init_container, "recurrent_kernel")
         else:
             var = getattr(init_container, key.replace("_initializer", ""))
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/inference/layers.py` & `osl-dynamics-1.2.4/osl_dynamics/inference/layers.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 """Custom Tensorflow layers.
 
 """
 
 import numpy as np
 import tensorflow as tf
 import tensorflow_probability as tfp
-from tensorflow.keras import activations, layers, initializers
+from tensorflow.keras import activations, layers, initializers, regularizers
 
 import osl_dynamics.inference.initializers as osld_initializers
 
 tfb = tfp.bijectors
 
 
 @tf.function
@@ -96,15 +96,15 @@
     strength : float
         Strength of regularization. The regularization is multiplied
         by the strength before being added to the loss
     """
 
     def __init__(self, reg, strength, **kwargs):
         super().__init__(**kwargs)
-        self.reg = tf.keras.regularizers.get(reg)
+        self.reg = regularizers.get(reg)
         self.strength = strength
 
     def call(self, inputs, **kwargs):
         reg_loss = self.reg(inputs)
         self.add_loss(self.strength * reg_loss)
         return inputs
 
@@ -306,15 +306,15 @@
                 initial_value=initial_temperature,
                 name=self.name + "_kernel",
             )
         ]
 
     def call(self, inputs, **kwargs):
         temperature = self.layers[0](inputs)
-        return activations.softmax(inputs / temperature, axis=2)
+        return activations.softmax(inputs / temperature, axis=-1)
 
 
 class LearnableTensorLayer(layers.Layer):
     """Layer to learn a tensor.
 
     Parameters
     ----------
@@ -416,16 +416,16 @@
         Number of vectors.
     m : int
         Number of elements.
     learn : bool
         Should we learn the vectors?
     initial_value : np.ndarray
         Initial value for the vectors.
-    regularizer : tf.keras.regularizers.Regularizer
-        Regularizer for vectors.
+    regularizer : osl-dynamics regularizer
+        Regularizer for the tensor. Must be from osl_dynamics.inference.regularizers.
     """
 
     def __init__(
         self,
         n,
         m,
         learn,
@@ -484,16 +484,16 @@
         Number of rows/columns.
     learn : bool
         Should the matrices be learnable?
     initial_value : np.ndarray
         Initial values for the matrices.
     epsilon : float
         Error added to the diagonal of covariances matrices for numerical stability.
-    regularizer : tf.keras.regularizers.Regularizer
-        Regularizer for matrices.
+    regularizer : osl-dynamics regularizer
+        Regularizer for the tensor. Must be from osl_dynamics.inference.regularizers.
     """
 
     def __init__(
         self,
         n,
         m,
         learn,
@@ -569,16 +569,16 @@
         Number of rows/columns.
     learn : bool
         Should the matrices be learnable?
     initial_value : np.ndarray
         Initial values for the matrices.
     epsilon : float
         Error added to the diagonal of correlation matrices for numerical stability.
-    regularizer : tf.keras.regularizers.Regularizer
-        Regularizer for matrices.
+    regularizer : osl-dynamics regularizer
+        Regularizer for the tensor. Must be from osl_dynamics.inference.regularizers.
     """
 
     def __init__(
         self,
         n,
         m,
         learn,
@@ -655,16 +655,16 @@
         Number of rows/columns.
     learn : bool
         Should the matrices be learnable?
     initial_value : np.ndarray
         Initial values for the matrices.
     epsilon : float
         Error added to the diagonal matrices for numerical stability.
-    regularizer : tf.keras.regularizers.Regularizer
-        Regularizer for the diagonal entries.
+    regularizer : osl-dynamics regularizer
+        Regularizer for the tensor. Must be from osl_dynamics.inference.regularizers.
     """
 
     def __init__(
         self,
         n,
         m,
         learn,
@@ -740,16 +740,16 @@
         Either 'covariance' or 'diagonal'.
     learn : bool
         Should the matrix be trainable?
     initial_value : np.ndarray
         Initial value for the matrix.
     epsilon : float
         Error added to the matrices for numerical stability.
-    regularizer : tf.keras.regularizers.Regularizer
-        Regularizer for the diagonal entries.
+    regularizer : osl-dynamics regularizer
+        Regularizer for the tensor. Must be from osl_dynamics.inference.regularizers.
     """
 
     def __init__(
         self, m, constraint, learn, initial_value, epsilon, regularizer=None, **kwargs
     ):
         super().__init__(**kwargs)
         self.constraint = constraint
@@ -1157,18 +1157,20 @@
     def __init__(self, n_states, epsilon, **kwargs):
         super().__init__(**kwargs)
         self.n_states = n_states
         self.epsilon = epsilon
 
     def call(self, inputs, **kwargs):
         x, mu, sigma, probs, subj_id = inputs
+
         # Add a small error for numerical stability
         sigma = add_epsilon(sigma, self.epsilon, diag=True)
 
         if subj_id is not None:
+            # Get the mean and covariance for the requested subject
             subj_id = tf.cast(subj_id, tf.int32)
             mu = tf.gather(mu, subj_id)
             sigma = tf.gather(sigma, subj_id)
 
         # Log-likelihood for each state
         ll_loss = tf.zeros(shape=tf.shape(x)[:-1])
         for i in range(self.n_states):
@@ -1348,30 +1350,54 @@
         Number of units/neurons.
     norm_type : str
         Normalization layer type. Can be None, "layer" or "batch".
     act_type : str
         Activation type.
     drop_rate : float
         Dropout rate.
+    regularizer : str
+        Regularizer type.
+    regularizer_factor : float
+        Regularizer factor.
     """
 
     def __init__(
         self,
         n_layers,
         n_units,
         norm_type,
         act_type,
         drop_rate,
+        regularizer=None,
+        regularizer_factor=0.0,
+        n_batches=1,
         **kwargs,
     ):
         super().__init__(**kwargs)
+        self.regularizer = regularizers.get(regularizer)
+        self.regularizer_factor = regularizer_factor
+        self.n_batches = n_batches
         self.layers = []
-        for n in range(n_layers):
+        for _ in range(n_layers):
             self.layers.append(layers.Dense(n_units))
             self.layers.append(NormalizationLayer(norm_type))
             self.layers.append(layers.Activation(act_type))
             self.layers.append(layers.Dropout(drop_rate))
 
-    def call(self, inputs, **kwargs):
+    def call(self, inputs, training=None, **kwargs):
+        reg = 0.0
+        data, inputs = inputs
+
+        batch_size = tf.cast(tf.shape(data)[0], tf.float32)
+        scaling_factor = batch_size * self.n_batches
         for layer in self.layers:
             inputs = layer(inputs, **kwargs)
+            if self.regularizer is not None and isinstance(layer, layers.Dense):
+                reg += self.regularizer(layer.kernel)
+                reg += self.regularizer(layer.bias)
+
+        if self.regularizer is not None and training:
+            reg *= self.regularizer_factor
+            reg /= scaling_factor
+            self.add_loss(reg)
+            self.add_metric(reg, name=self.name)
         return inputs
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/inference/metrics.py` & `osl-dynamics-1.2.4/osl_dynamics/inference/metrics.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/inference/modes.py` & `osl-dynamics-1.2.4/osl_dynamics/inference/modes.py`

 * *Files 2% similar despite different names*

```diff
@@ -237,14 +237,15 @@
     # Number of arguments and number of matrices in each argument passed
     n_args = len(covariances)
     n_matrices = covariances[0].shape[0]
 
     # Calculate the similarity between matrices
     F = np.empty([n_matrices, n_matrices])
     matched_covariances = [covariances[0]]
+    orders = [np.arange(covariances[0].shape[0])]
     for i in range(1, n_args):
         for j in range(n_matrices):
             # Find the matrix that is most similar to matrix j
             for k in range(n_matrices):
                 if comparison == "frobenius":
                     A = abs(
                         np.diagonal(covariances[i][k]) - np.diagonal(covariances[0][j])
@@ -258,17 +259,18 @@
                     F[j, k] = -metrics.pairwise_rv_coefficient(
                         np.array([covariances[i][k], covariances[0][j]])
                     )[0, 1]
         order = linear_sum_assignment(F)[1]
 
         # Add the ordered matrix to the list
         matched_covariances.append(covariances[i][order])
+        orders.append(order)
 
     if return_order:
-        return order
+        return orders
     else:
         return tuple(matched_covariances)
 
 
 def match_modes(*mode_time_courses, return_order=False):
     """Find correlated modes between mode time courses.
 
@@ -346,14 +348,19 @@
 
 
 def switching_rates(state_time_course, sampling_frequency=None):
     """Wrapper for osl_dynamics.analysis.modes.switching_rates."""
     return analysis.modes.switching_rates(state_time_course, sampling_frequency)
 
 
+def mean_amplitudes(state_time_course, data):
+    """Wrapper for osl.dynamics.analysis.modes.mean_amplitudes."""
+    return analysis.modes.mean_amplitudes(state_time_course, data)
+
+
 def convert_to_mne_raw(
     alpha,
     raw,
     ch_names=None,
     n_embeddings=None,
     n_window=None,
     extra_chans="stim",
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/inference/regularizers.py` & `osl-dynamics-1.2.4/osl_dynamics/inference/regularizers.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/inference/tf_ops.py` & `osl-dynamics-1.2.4/osl_dynamics/inference/tf_ops.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/__init__.py` & `osl-dynamics-1.2.4/osl_dynamics/models/__init__.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/dynemo.py` & `osl-dynamics-1.2.4/osl_dynamics/models/dynemo.py`

 * *Files 2% similar despite different names*

```diff
@@ -361,14 +361,39 @@
             theta_norm[-1] = theta_norm_layer(theta[np.newaxis, np.newaxis, :])[0]
 
             # Calculate the mode mixing factors
             alpha[i] = alpha_layer(mod_mu[np.newaxis, np.newaxis, :])[0, 0]
 
         return alpha
 
+    def get_n_params_generative_model(self):
+        """Get the number of trainable parameters in the generative model.
+
+        This includes the model RNN weights and biases, mixing coefficients, mode
+        means and covariances.
+
+        Returns
+        -------
+        n_params : int
+            Number of parameters in the generative model.
+        """
+        n_params = 0
+
+        for var in self.trainable_weights:
+            var_name = var.name
+            if (
+                "mod_" in var_name
+                or "alpha" in var_name
+                or "means" in var_name
+                or "covs" in var_name
+            ):
+                n_params += np.prod(var.shape)
+
+        return int(n_params)
+
 
 def _model_structure(config):
     # Layer for input
     inputs = layers.Input(
         shape=(config.sequence_length, config.n_channels), name="data"
     )
 
@@ -485,9 +510,9 @@
     mod_rnn = mod_rnn_layer(theta_norm_drop)
     mod_mu = mod_mu_layer(mod_rnn)
     mod_sigma = mod_sigma_layer(mod_rnn)
     kl_div = kl_div_layer([inf_mu, inf_sigma, mod_mu, mod_sigma])
     kl_loss = kl_loss_layer(kl_div)
 
     return tf.keras.Model(
-        inputs=inputs, outputs=[ll_loss, kl_loss, alpha], name="DyNeMo"
+        inputs=inputs, outputs=[ll_loss, kl_loss, theta_norm], name="DyNeMo"
     )
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/dynemo_obs.py` & `osl-dynamics-1.2.4/osl_dynamics/models/dynemo_obs.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/hmm.py` & `osl-dynamics-1.2.4/osl_dynamics/models/hmm.py`

 * *Files 5% similar despite different names*

```diff
@@ -301,16 +301,15 @@
             if history is None:
                 continue
             loss = history["loss"][-1]
             if loss < best_loss:
                 best_initialization = n
                 best_loss = loss
                 best_history = history
-                best_weights = self.get_weights()
-                best_trans_prob = self.trans_prob
+                best_weights, best_trans_prob = self.get_weights()
 
         if best_loss == np.Inf:
             _logger.error("Initialization failed")
             return
 
         _logger.info(f"Using initialization {best_initialization}")
         self.set_weights(best_weights, best_trans_prob)
@@ -371,16 +370,15 @@
             if history is None:
                 continue
             loss = history["loss"][-1]
             if loss < best_loss:
                 best_initialization = n
                 best_loss = loss
                 best_history = history
-                best_weights = self.get_weights()
-                best_trans_prob = self.trans_prob
+                best_weights, best_trans_prob = self.get_weights()
 
         if best_loss == np.Inf:
             _logger.error("Initialization failed")
             return
 
         _logger.info(f"Using initialization {best_initialization}")
         self.set_weights(best_weights, best_trans_prob)
@@ -1101,14 +1099,71 @@
             alpha.append(np.concatenate(gamma).astype(np.float32))
 
         if concatenate or len(alpha) == 1:
             alpha = np.concatenate(alpha)
 
         return alpha
 
+    def get_n_params_generative_model(self):
+        """Get the number of trainable parameters in the generative model.
+
+        This includes the transition probabiltity matrix, state means and
+        covariances.
+
+        Returns
+        -------
+        n_params : int
+            Number of parameters in the generative model.
+        """
+        n_params = 0
+        if self.config.learn_trans_prob:
+            n_params += self.config.n_states * (self.config.n_states - 1)
+
+        for var in self.trainable_weights:
+            var_name = var.name
+            if "means" in var_name or "covs" in var_name:
+                n_params += np.prod(var.shape)
+
+        return int(n_params)
+
+    def bayesian_information_criterion(self, dataset, loss_type="free_energy"):
+        """Calculate the Bayesian Information Criterion (BIC) for the model.
+
+        Parameters
+        ----------
+        dataset : osl_dynamics.data.Data
+            Dataset to calculate the BIC for.
+        loss_type : str
+            Which loss to use for the BIC. Can be "free_energy" or "evidence".
+
+        Returns
+        -------
+        bic : float
+            Bayesian Information Criterion for the model (for each sequence).
+        """
+        if loss_type == "free_energy":
+            loss = self.free_energy(dataset)
+        elif loss_type == "evidence":
+            loss = -self.evidence(dataset)
+        else:
+            raise ValueError("loss_type must be 'free_energy' or 'evidence'")
+
+        n_params = self.get_n_params_generative_model()
+        n_sequences = dtf.n_batches(
+            dataset.time_series(concatenate=True), self.config.sequence_length
+        )
+
+        bic = (
+            2 * loss
+            + (np.log(self.config.sequence_length) + np.log(n_sequences))
+            * n_params
+            / n_sequences
+        )
+        return bic
+
     def get_training_time_series(self, training_data, prepared=True, concatenate=False):
         """Get the time series used for training from a Data object.
 
         Parameters
         ----------
         training_data : osl_dynamics.data.Data
             Data object.
@@ -1144,14 +1199,26 @@
         ----------
         filepath : str
             Location to load model weights from.
         """
         self.trans_prob = np.load(op.join(str(Path(filepath).parent), "trans_prob.npy"))
         return self.model.load_weights(filepath)
 
+    def get_weights(self):
+        """Get model parameter weights.
+
+        Returns
+        -------
+        weights : tensorflow weights
+            TensorFlow weights for the observation model.
+        trans_prob : np.ndarray
+            Transition probability matrix.
+        """
+        return self.model.get_weights(), self.trans_prob
+
     def set_weights(self, weights, trans_prob):
         """Set model parameter weights.
 
         Parameters
         ----------
         weights : tensorflow weights
             TensorFlow weights for the observation model.
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/mage.py` & `osl-dynamics-1.2.4/osl_dynamics/models/mage.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/mdynemo.py` & `osl-dynamics-1.2.4/osl_dynamics/models/mdynemo.py`

 * *Files 3% similar despite different names*

```diff
@@ -393,14 +393,41 @@
             fc_theta_norm[-1] = fc_theta_norm_layer(fc_theta[np.newaxis, np.newaxis, :])
 
             alpha[i] = alpha_layer(mean_theta_norm[-1][np.newaxis, np.newaxis, :])[0, 0]
             gamma[i] = gamma_layer(fc_theta_norm[-1][np.newaxis, np.newaxis, :])[0, 0]
 
         return alpha, gamma
 
+    def get_n_params_generative_model(self):
+        """Get the number of trainable parameters in the generative model.
+
+        This includes the model RNN weights and biases, mixing coefficients, mode
+        means and covariances.
+
+        Returns
+        -------
+        n_params : int
+            Number of parameters in the generative model.
+        """
+        n_params = 0
+
+        for var in self.trainable_weights:
+            var_name = var.name
+            if (
+                "mod_" in var_name
+                or "alpha" in var_name
+                or "gamma" in var_name
+                or "means" in var_name
+                or "stds" in var_name
+                or "fcs" in var_name
+            ):
+                n_params += np.prod(var.shape)
+
+            return int(n_params)
+
 
 def _model_structure(config):
     # Layer for input
     inputs = layers.Input(
         shape=(config.sequence_length, config.n_channels), name="data"
     )
 
@@ -592,9 +619,11 @@
     #
     # Total KL loss
     #
     kl_loss_layer = KLLossLayer(config.do_kl_annealing, name="kl_loss")
     kl_loss = kl_loss_layer([mean_kl_div, fc_kl_div])
 
     return tf.keras.Model(
-        inputs=inputs, outputs=[ll_loss, kl_loss, alpha, gamma], name="M-DyNeMo"
+        inputs=inputs,
+        outputs=[ll_loss, kl_loss, mean_theta_norm, fc_theta_norm],
+        name="M-DyNeMo",
     )
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/mdynemo_obs.py` & `osl-dynamics-1.2.4/osl_dynamics/models/mdynemo_obs.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/mod_base.py` & `osl-dynamics-1.2.4/osl_dynamics/models/mod_base.py`

 * *Files 1% similar despite different names*

```diff
@@ -250,28 +250,33 @@
         initializers.reinitialize_model_weights(self.model)
 
     def reset(self):
         """Reset the model as if you've built a new model."""
         self.reset_weights()
         self.compile()
 
-    def make_dataset(self, inputs, shuffle=False, concatenate=False, subj_id=False):
+    def make_dataset(
+        self, inputs, shuffle=False, concatenate=False, subj_id=False, step_size=None
+    ):
         """Converts a Data object into a TensorFlow Dataset.
 
         Parameters
         ----------
         inputs : osl_dynamics.data.Data
             Data object. If a str or numpy array is passed this function will
             convert it into a Data object.
         shuffle : bool
             Should we shuffle the data?
         concatenate : bool
             Should we return a single TensorFlow Dataset or a list of Datasets.
         subj_id : bool
             Should we include the subject id in the dataset?
+        step_size : int
+            Number of samples to slide the sequence across the dataset.
+            Default is no overlap.
 
         Returns
         -------
         dataset : tensorflow.data.Dataset or list
             TensorFlow Dataset (or list of Datasets) that can be used for
             training/evaluating.
         """
@@ -284,14 +289,15 @@
             # Data object -> Dataset if concatenate=True
             outputs = inputs.dataset(
                 self.config.sequence_length,
                 self.config.batch_size,
                 shuffle=shuffle,
                 concatenate=concatenate,
                 subj_id=subj_id,
+                step_size=step_size,
             )
         elif isinstance(inputs, Dataset) and not concatenate:
             # Dataset -> list of Dataset if concatenate=False
             outputs = [inputs]
         else:
             outputs = inputs
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/sage.py` & `osl-dynamics-1.2.4/osl_dynamics/models/sage.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/sedynemo.py` & `osl-dynamics-1.2.4/osl_dynamics/models/sedynemo.py`

 * *Files 4% similar despite different names*

```diff
@@ -150,14 +150,19 @@
         Number of units for the MLP for deviations.
     dev_normalization : str
         Type of normalization for the MLP for deviations.
     dev_activation : str
         Type of activation to use for the MLP for deviations.
     dev_dropout : float
         Dropout rate for the MLP for deviations.
+    dev_regularizer : str
+        Regularizer for the MLP for deviations.
+    dev_regularizer_factor : float
+        Regularizer factor for the MLP for deviations.
+        This will be scaled by the amount of data.
     """
 
     model_name: str = "SE-DyNeMo"
 
     # Inference network parameters
     inference_rnn: Literal["gru", "lstm"] = "lstm"
     inference_n_layers: int = 1
@@ -191,14 +196,16 @@
     mode_embeddings_dim: int = None
 
     dev_n_layers: int = 0
     dev_n_units: int = None
     dev_normalization: str = None
     dev_activation: str = None
     dev_dropout: float = 0.0
+    dev_regularizer: str = None
+    dev_regularizer_factor: float = 0.0
 
     def __post_init__(self):
         self.validate_rnn_parameters()
         self.validate_observation_model_parameters()
         self.validate_alpha_parameters()
         self.validate_kl_annealing_parameters()
         self.validate_dimension_parameters()
@@ -251,15 +258,16 @@
         self.model = _model_structure(self.config)
 
     def make_dataset(self, inputs, shuffle=False, concatenate=False, subj_id=True):
         """SE-DyNeMo requires subject id to be included in the dataset."""
         return super().make_dataset(inputs, shuffle, concatenate, subj_id)
 
     def fit(self, training_data, *args, **kwargs):
-        # Set Bayesian KL scaling
+        # Set the scalings
+        self.set_dev_mlp_reg_scaling(training_data)
         self.set_bayesian_kl_scaling(training_data)
         return super().fit(training_data, *args, **kwargs)
 
     def get_group_means(self):
         """Get the group means.
 
         Returns
@@ -416,20 +424,63 @@
         n_batches = dtf.get_n_batches(training_dataset)
         learn_means = self.config.learn_means
         learn_covariances = self.config.learn_covariances
         sedynemo_obs.set_bayesian_kl_scaling(
             self.model, n_batches, learn_means, learn_covariances
         )
 
+    def set_dev_mlp_reg_scaling(self, training_dataset):
+        """Set the correct scaling for the deviation MLP regularization.
+
+        Parameters
+        ----------
+        training_dataset : tensorflow.data.Dataset or osl_dynamics.data.Data
+            Training dataset.
+        """
+        training_dataset = self.make_dataset(training_dataset, concatenate=True)
+        n_batches = dtf.get_n_batches(training_dataset)
+        learn_means = self.config.learn_means
+        learn_covariances = self.config.learn_covariances
+        sedynemo_obs.set_dev_mlp_reg_scaling(
+            self.model, n_batches, learn_means, learn_covariances
+        )
+
     def random_subject_initialization(self, **kwargs):
         """random subject initialisation not compatible with SE-DyNeMo."""
         raise AttributeError(
             " 'Model' object has no attribute 'random_subject_initialization'."
         )
 
+    def get_n_params_generative_model(self):
+        """Get the number of trainable parameters in the generative model.
+
+        This includes the model RNN weights and biases, mixing coefficients, mode
+        means and covariances (group and subject deviation) and subject embeddings.
+
+        Returns
+        -------
+        n_params : int
+            Number of parameters in the generative model.
+        """
+        n_params = 0
+
+        for var in self.trainable_weights:
+            var_name = var.name
+            if (
+                "mod_" in var_name
+                or "alpha" in var_name
+                or "group_means" in var_name
+                or "group_covs" in var_name
+                or "_embeddings" in var_name
+                or "dev_map" in var_name
+            ):
+                n_params += np.prod(var.shape)
+
+        return int(n_params)
+
 
 def _model_structure(config):
     # Layers for inputs
     data = layers.Input(shape=(config.sequence_length, config.n_channels), name="data")
     subj_id = layers.Input(shape=(config.sequence_length,), name="subj_id")
 
     # Inference RNN:
@@ -520,14 +571,16 @@
 
         means_dev_map_input_layer = MultiLayerPerceptronLayer(
             config.dev_n_layers,
             config.dev_n_units,
             config.dev_normalization,
             config.dev_activation,
             config.dev_dropout,
+            config.dev_regularizer,
+            config.dev_regularizer_factor,
             name="means_dev_map_input",
         )
         means_dev_map_layer = layers.Dense(config.n_channels, name="means_dev_map")
 
         norm_means_dev_map_layer = layers.LayerNormalization(
             axis=-1, name="norm_means_dev_map"
         )
@@ -561,15 +614,15 @@
         # Get the concatenated embeddings
         means_mode_embeddings = means_mode_embeddings_layer(group_mu)
         means_concat_embeddings = means_concat_embeddings_layer(
             [subject_embeddings, means_mode_embeddings]
         )
 
         # Get the mean deviation maps (no global magnitude information)
-        means_dev_map_input = means_dev_map_input_layer(means_concat_embeddings)
+        means_dev_map_input = means_dev_map_input_layer([data, means_concat_embeddings])
         means_dev_map = means_dev_map_layer(means_dev_map_input)
         norm_means_dev_map = norm_means_dev_map_layer(means_dev_map)
 
         # Get the deviation magnitudes (scale deviation maps globally)
 
         means_dev_mag_inf_alpha_input = means_dev_mag_inf_alpha_input_layer(data)
         means_dev_mag_inf_alpha = means_dev_mag_inf_alpha_layer(
@@ -605,14 +658,16 @@
 
         covs_dev_map_input_layer = MultiLayerPerceptronLayer(
             config.dev_n_layers,
             config.dev_n_units,
             config.dev_normalization,
             config.dev_activation,
             config.dev_dropout,
+            config.dev_regularizer,
+            config.dev_regularizer_factor,
             name="covs_dev_map_input",
         )
         covs_dev_map_layer = layers.Dense(
             config.n_channels * (config.n_channels + 1) // 2, name="covs_dev_map"
         )
         norm_covs_dev_map_layer = layers.LayerNormalization(
             axis=-1, name="norm_covs_dev_map"
@@ -648,15 +703,15 @@
             InverseCholeskyLayer(config.covariances_epsilon)(group_D)
         )
         covs_concat_embeddings = covs_concat_embeddings_layer(
             [subject_embeddings, covs_mode_embeddings]
         )
 
         # Get the covariance deviation maps (no global magnitude information)
-        covs_dev_map_input = covs_dev_map_input_layer(covs_concat_embeddings)
+        covs_dev_map_input = covs_dev_map_input_layer([data, covs_concat_embeddings])
         covs_dev_map = covs_dev_map_layer(covs_dev_map_input)
         norm_covs_dev_map = norm_covs_dev_map_layer(covs_dev_map)
 
         # Get the deviation magnitudes (scale deviation maps globally)
         covs_dev_mag_inf_alpha_input = covs_dev_mag_inf_alpha_input_layer(data)
         covs_dev_mag_inf_alpha = covs_dev_mag_inf_alpha_layer(
             covs_dev_mag_inf_alpha_input
@@ -743,29 +798,31 @@
         # Layer definitions
         means_dev_mag_mod_beta_input_layer = MultiLayerPerceptronLayer(
             config.dev_n_layers,
             config.dev_n_units,
             config.dev_normalization,
             config.dev_activation,
             config.dev_dropout,
+            config.dev_regularizer,
+            config.dev_regularizer_factor,
             name="means_dev_mag_mod_beta_input",
         )
         means_dev_mag_mod_beta_layer = layers.Dense(
             1,
             activation="softplus",
             name="means_dev_mag_mod_beta",
         )
 
         means_dev_mag_kl_loss_layer = StaticKLDivergenceLayer(
             config.covariances_epsilon, name="means_dev_mag_kl_loss"
         )
 
         # Data flow
         means_dev_mag_mod_beta_input = means_dev_mag_mod_beta_input_layer(
-            means_concat_embeddings
+            [data, means_concat_embeddings]
         )
         means_dev_mag_mod_beta = means_dev_mag_mod_beta_layer(
             means_dev_mag_mod_beta_input
         )
         means_dev_mag_kl_loss = means_dev_mag_kl_loss_layer(
             [
                 data,
@@ -782,29 +839,31 @@
         # Layer definitions
         covs_dev_mag_mod_beta_input_layer = MultiLayerPerceptronLayer(
             config.dev_n_layers,
             config.dev_n_units,
             config.dev_normalization,
             config.dev_activation,
             config.dev_dropout,
+            config.dev_regularizer,
+            config.dev_regularizer_factor,
             name="covs_dev_mag_mod_beta_input",
         )
         covs_dev_mag_mod_beta_layer = layers.Dense(
             1,
             activation="softplus",
             name="covs_dev_mag_mod_beta",
         )
 
         covs_dev_mag_kl_loss_layer = StaticKLDivergenceLayer(
             config.covariances_epsilon, name="covs_dev_mag_kl_loss"
         )
 
         # Data flow
         covs_dev_mag_mod_beta_input = covs_dev_mag_mod_beta_input_layer(
-            covs_concat_embeddings
+            [data, covs_concat_embeddings]
         )
         covs_dev_mag_mod_beta = covs_dev_mag_mod_beta_layer(covs_dev_mag_mod_beta_input)
         covs_dev_mag_kl_loss = covs_dev_mag_kl_loss_layer(
             [
                 data,
                 covs_dev_mag_inf_alpha,
                 covs_dev_mag_inf_beta,
@@ -820,10 +879,10 @@
     kl_loss_layer = KLLossLayer(config.do_kl_annealing, name="kl_loss")
 
     # Data flow
     kl_loss = kl_loss_layer([kl_div, means_dev_mag_kl_loss, covs_dev_mag_kl_loss])
 
     return tf.keras.Model(
         inputs=[data, subj_id],
-        outputs=[ll_loss, kl_loss, alpha],
+        outputs=[ll_loss, kl_loss, theta_norm],
         name="Se-DyNeMo",
     )
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/sedynemo_obs.py` & `osl-dynamics-1.2.4/osl_dynamics/models/sedynemo_obs.py`

 * *Files 6% similar despite different names*

```diff
@@ -74,14 +74,19 @@
         Type of normalization for the MLP for deviations.
         Either None, 'batch' or 'layer'.
     dev_activation : str
         Type of activation to use for the MLP for deviations.
         E.g. 'relu', 'sigmoid', 'tanh', etc.
     dev_dropout : float
         Dropout rate for the MLP for deviations.
+    dev_regularizer : str
+        Regularizer for the MLP for deviations.
+    dev_regularizer_factor : float
+        Regularizer factor for the MLP for deviations.
+        This will be scaled by the amount of data.
 
     batch_size : int
         Mini-batch size.
     learning_rate : float
         Learning rate.
     gradient_clip : float
         Value to clip gradients by. This is the clipnorm argument passed to
@@ -113,14 +118,16 @@
     mode_embeddings_dim: int = None
 
     dev_n_layers: int = 0
     dev_n_units: int = None
     dev_normalization: str = None
     dev_activation: str = None
     dev_dropout: float = 0.0
+    dev_regularizer: str = None
+    dev_regularizer_factor: float = 0.0
 
     def __post_init__(self):
         self.validate_observation_model_parameters()
         self.validate_dimension_parameters()
         self.validate_training_parameters()
         self.validate_subject_embedding_parameters()
 
@@ -158,14 +165,20 @@
 
     config_type = Config
 
     def build_model(self):
         """Builds a keras model."""
         self.model = _model_structure(self.config)
 
+    def fit(self, training_data, *args, **kwargs):
+        # Set the scalings
+        self.set_dev_mlp_reg_scaling(training_data)
+        self.set_bayesian_kl_scaling(training_data)
+        return super().fit(training_data, *args, **kwargs)
+
     def get_group_means(self):
         """Get the group means.
 
         Returns
         -------
         means : np.ndarray
             Group means. Shape is (n_modes, n_channels).
@@ -259,14 +272,21 @@
     def set_bayesian_kl_scaling(self, training_dataset):
         """Set the correct scaling for KL loss between deviation posterior and prior."""
         n_batches = dtf.get_n_batches(training_dataset)
         learn_means = self.config.learn_means
         learn_covariances = self.config.learn_covariances
         set_bayesian_kl_scaling(self.model, n_batches, learn_means, learn_covariances)
 
+    def set_dev_mlp_reg_scaling(self, training_dataset):
+        """Set the correct scaling for the dev mlp regularization."""
+        n_batches = dtf.get_n_batches(training_dataset)
+        learn_means = self.config.learn_means
+        learn_covariances = self.config.learn_covariances
+        set_dev_mlp_reg_scaling(self.model, n_batches, learn_means, learn_covariances)
+
     def set_group_means(self, group_means, update_initializer=True):
         """Set the group means of each mode.
 
         Parameters
         ----------
         group_means : np.ndarray
             Mode means.
@@ -348,14 +368,16 @@
 
         means_dev_map_input_layer = MultiLayerPerceptronLayer(
             config.dev_n_layers,
             config.dev_n_units,
             config.dev_normalization,
             config.dev_activation,
             config.dev_dropout,
+            config.dev_regularizer,
+            config.dev_regularizer_factor,
             name="means_dev_map_input",
         )
         means_dev_map_layer = layers.Dense(config.n_channels, name="means_dev_map")
         norm_means_dev_map_layer = layers.LayerNormalization(
             axis=-1, name="norm_means_dev_map"
         )
 
@@ -388,15 +410,15 @@
         # Get the concatenated embeddings
         means_mode_embeddings = means_mode_embeddings_layer(group_mu)
         means_concat_embeddings = means_concat_embeddings_layer(
             [subject_embeddings, means_mode_embeddings]
         )
 
         # Get the mean deviation maps (no global magnitude information)
-        means_dev_map_input = means_dev_map_input_layer(means_concat_embeddings)
+        means_dev_map_input = means_dev_map_input_layer([data, means_concat_embeddings])
         means_dev_map = means_dev_map_layer(means_dev_map_input)
         norm_means_dev_map = norm_means_dev_map_layer(means_dev_map)
 
         # Get the deviation magnitudes (scale deviation maps globally)
 
         means_dev_mag_inf_alpha_input = means_dev_mag_inf_alpha_input_layer(data)
         means_dev_mag_inf_alpha = means_dev_mag_inf_alpha_layer(
@@ -432,14 +454,16 @@
 
         covs_dev_map_input_layer = MultiLayerPerceptronLayer(
             config.dev_n_layers,
             config.dev_n_units,
             config.dev_normalization,
             config.dev_activation,
             config.dev_dropout,
+            config.dev_regularizer,
+            config.dev_regularizer_factor,
             name="covs_dev_map_input",
         )
         covs_dev_map_layer = layers.Dense(
             config.n_channels * (config.n_channels + 1) // 2, name="covs_dev_map"
         )
         norm_covs_dev_map_layer = layers.LayerNormalization(
             axis=-1, name="norm_covs_dev_map"
@@ -475,15 +499,15 @@
             InverseCholeskyLayer(config.covariances_epsilon)(group_D)
         )
         covs_concat_embeddings = covs_concat_embeddings_layer(
             [subject_embeddings, covs_mode_embeddings]
         )
 
         # Get the covariance deviation maps (no global magnitude information)
-        covs_dev_map_input = covs_dev_map_input_layer(covs_concat_embeddings)
+        covs_dev_map_input = covs_dev_map_input_layer([data, covs_concat_embeddings])
         covs_dev_map = covs_dev_map_layer(covs_dev_map_input)
         norm_covs_dev_map = norm_covs_dev_map_layer(covs_dev_map)
 
         # Get the deviation magnitudes (scale deviation maps globally)
         covs_dev_mag_inf_alpha_input = covs_dev_mag_inf_alpha_input_layer(data)
         covs_dev_mag_inf_alpha = covs_dev_mag_inf_alpha_layer(
             covs_dev_mag_inf_alpha_input
@@ -542,29 +566,31 @@
         # Layer definitions
         means_dev_mag_mod_beta_input_layer = MultiLayerPerceptronLayer(
             config.dev_n_layers,
             config.dev_n_units,
             config.dev_normalization,
             config.dev_activation,
             config.dev_dropout,
+            config.dev_regularizer,
+            config.dev_regularizer_factor,
             name="means_dev_mag_mod_beta_input",
         )
         means_dev_mag_mod_beta_layer = layers.Dense(
             1,
             activation="softplus",
             name="means_dev_mag_mod_beta",
         )
 
         means_dev_mag_kl_loss_layer = StaticKLDivergenceLayer(
             config.covariances_epsilon, name="means_dev_mag_kl_loss"
         )
 
         # Data flow
         means_dev_mag_mod_beta_input = means_dev_mag_mod_beta_input_layer(
-            means_concat_embeddings
+            [data, means_concat_embeddings]
         )
         means_dev_mag_mod_beta = means_dev_mag_mod_beta_layer(
             means_dev_mag_mod_beta_input
         )
         means_dev_mag_kl_loss = means_dev_mag_kl_loss_layer(
             [
                 data,
@@ -581,29 +607,31 @@
         # Layer definitions
         covs_dev_mag_mod_beta_input_layer = MultiLayerPerceptronLayer(
             config.dev_n_layers,
             config.dev_n_units,
             config.dev_normalization,
             config.dev_activation,
             config.dev_dropout,
+            config.dev_regularizer,
+            config.dev_regularizer_factor,
             name="covs_dev_mag_mod_beta_input",
         )
         covs_dev_mag_mod_beta_layer = layers.Dense(
             1,
             activation="softplus",
             name="covs_dev_mag_mod_beta",
         )
 
         covs_dev_mag_kl_loss_layer = StaticKLDivergenceLayer(
             config.covariances_epsilon, name="covs_dev_mag_kl_loss"
         )
 
         # Data flow
         covs_dev_mag_mod_beta_input = covs_dev_mag_mod_beta_input_layer(
-            covs_concat_embeddings
+            [data, covs_concat_embeddings]
         )
         covs_dev_mag_mod_beta = covs_dev_mag_mod_beta_layer(covs_dev_mag_mod_beta_input)
         covs_dev_mag_kl_loss = covs_dev_mag_kl_loss_layer(
             [
                 data,
                 covs_dev_mag_inf_alpha,
                 covs_dev_mag_inf_beta,
@@ -612,15 +640,15 @@
         )
     else:
         covs_dev_mag_kl_loss_layer = ZeroLayer((), name="covs_dev_mag_kl_loss")
         covs_dev_mag_kl_loss = covs_dev_mag_kl_loss_layer(data)
 
     # Total KL loss
     # Layer definitions
-    kl_loss_layer = KLLossLayer(config.do_kl_annealing, name="kl_loss")
+    kl_loss_layer = KLLossLayer(False, name="kl_loss")
 
     # Data flow
     kl_loss = kl_loss_layer([means_dev_mag_kl_loss, covs_dev_mag_kl_loss])
 
     return tf.keras.Model(
         inputs=[data, alpha, subj_id],
         outputs=[ll_loss, kl_loss],
@@ -701,15 +729,15 @@
         norm_dev_map_layer = model.get_layer("norm_means_dev_map")
     elif map == "covs":
         dev_map_input_layer = model.get_layer("covs_dev_map_input")
         dev_map_layer = model.get_layer("covs_dev_map")
         norm_dev_map_layer = model.get_layer("norm_covs_dev_map")
     else:
         raise ValueError("map must be either 'means' or 'covs'")
-    dev_map_input = dev_map_input_layer(concat_embeddings)
+    dev_map_input = dev_map_input_layer([np.zeros(1), concat_embeddings])
     dev_map = dev_map_layer(dev_map_input)
     norm_dev_map = norm_dev_map_layer(dev_map)
     return norm_dev_map.numpy()
 
 
 def get_subject_dev(
     model, learn_means, learn_covariances, subject_embeddings=None, n_neighbours=2
@@ -833,7 +861,16 @@
         axis=-1,
     )
 
     # Sort distances and get indices of nearest neighbours
     sorted_distances = np.argsort(distances, axis=1)
     nearest_neighbours = sorted_distances[:, :n_neighbours]
     return nearest_neighbours
+
+
+def set_dev_mlp_reg_scaling(model, n_batches, learn_means, learn_covariances):
+    if learn_means:
+        model.get_layer("means_dev_map_input").n_batches = n_batches
+        model.get_layer("means_dev_mag_mod_beta_input").n_batches = n_batches
+    if learn_covariances:
+        model.get_layer("covs_dev_map_input").n_batches = n_batches
+        model.get_layer("covs_dev_mag_mod_beta_input").n_batches = n_batches
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/sehmm.py` & `osl-dynamics-1.2.4/osl_dynamics/models/sehmm.py`

 * *Files 2% similar despite different names*

```diff
@@ -80,14 +80,19 @@
         Type of normalization for the MLP for deviations.
         Either None, 'batch' or 'layer'.
     dev_activation : str
         Type of activation to use for the MLP for deviations.
         E.g. 'relu', 'sigmoid', 'tanh', etc.
     dev_dropout : float
         Dropout rate for the MLP for deviations.
+    dev_regularizer : str
+        Regularizer for the MLP for deviations.
+    dev_regularizer_factor : float
+        Regularizer factor for the MLP for deviations.
+        This will be scaled by the amount of data.
 
     initial_trans_prob : np.ndarray
         Initialisation for trans prob matrix
     learn_trans_prob : bool
         Should we make the trans prob matrix trainable?
     state_probs_t0: np.ndarray
         State probabilities at time=0. Not trainable.
@@ -137,14 +142,16 @@
     mode_embeddings_dim: int = None
 
     dev_n_layers: int = 0
     dev_n_units: int = None
     dev_normalization: str = None
     dev_activation: str = None
     dev_dropout: float = 0.0
+    dev_regularizer: str = None
+    dev_regularizer_factor: float = 0.0
 
     # KL annealing parameters
     do_kl_annealing: bool = False
     kl_annealing_curve: Literal["linear", "tanh"] = None
     kl_annealing_sharpness: float = None
     n_kl_annealing_epochs: int = None
 
@@ -240,15 +247,16 @@
         -------
         history : dict
             Dictionary with history of the loss and learning rates (lr and rho).
         """
         if epochs is None:
             epochs = self.config.n_epochs
 
-        # Set bayesian KL scaling
+        # Set the scalings
+        self.set_dev_mlp_reg_scaling(dataset)
         self.set_bayesian_kl_scaling(dataset)
 
         # Make a TensorFlow dataset
         dataset = self.make_dataset(
             dataset, shuffle=True, concatenate=True, subj_id=True
         )
 
@@ -555,14 +563,30 @@
         n_batches = dtf.get_n_batches(training_dataset)
         learn_means = self.config.learn_means
         learn_covariances = self.config.learn_covariances
         sedynemo_obs.set_bayesian_kl_scaling(
             self.model, n_batches, learn_means, learn_covariances
         )
 
+    def set_dev_mlp_reg_scaling(self, training_dataset):
+        """Set the correct scaling for the deviation MLP regularization.
+
+        Parameters
+        ----------
+        training_dataset : tensorflow.data.Dataset or osl_dynamics.data.Data
+            Training dataset.
+        """
+        training_dataset = self.make_dataset(training_dataset, concatenate=True)
+        n_batches = dtf.get_n_batches(training_dataset)
+        learn_means = self.config.learn_means
+        learn_covariances = self.config.learn_covariances
+        sedynemo_obs.set_dev_mlp_reg_scaling(
+            self.model, n_batches, learn_means, learn_covariances
+        )
+
     def free_energy(self, dataset):
         """Get the variational free energy.
 
         This calculates:
 
         .. math::
             \mathcal{F} = \int q(s_{1:T}) \log \left[ \\frac{q(s_{1:T})}{p(x_{1:T}, s_{1:T})} \\right] ds_{1:T}
@@ -696,14 +720,43 @@
             alpha.append(np.concatenate(gamma).astype(np.float32))
 
         if concatenate or len(alpha) == 1:
             alpha = np.concatenate(alpha)
 
         return alpha
 
+    def get_n_params_generative_model(self):
+        """Get the number of trainable parameters in the generative model.
+
+        This includes the transition probability matrix, state means and
+        covariances (group and subject deviation) and subject embeddings.
+
+        Returns
+        -------
+        n_params : int
+            Number of parameters in the generative model.
+        """
+        n_params = 0
+        if self.config.learn_trans_prob:
+            n_params += self.config.n_states * (self.config.n_states - 1)
+
+        for var in self.trainable_variables:
+            var_name = var.name
+            if (
+                "mod_" in var_name
+                or "alpha" in var_name
+                or "group_means" in var_name
+                or "group_covs" in var_name
+                or "_embeddings" in var_name
+                or "dev_map" in var_name
+            ):
+                n_params += np.prod(var.shape)
+
+        return int(n_params)
+
 
 def _model_structure(config):
     # Inputs
     inputs = layers.Input(
         shape=(config.sequence_length, config.n_channels + config.n_states + 1),
         name="input",
     )
@@ -758,14 +811,16 @@
 
         means_dev_map_input_layer = MultiLayerPerceptronLayer(
             config.dev_n_layers,
             config.dev_n_units,
             config.dev_normalization,
             config.dev_activation,
             config.dev_dropout,
+            config.dev_regularizer,
+            config.dev_regularizer_factor,
             name="means_dev_map_input",
         )
         means_dev_map_layer = layers.Dense(config.n_channels, name="means_dev_map")
         norm_means_dev_map_layer = layers.LayerNormalization(
             axis=-1, name="norm_means_dev_map"
         )
 
@@ -798,15 +853,15 @@
         # Get the concatenated embeddings
         means_mode_embeddings = means_mode_embeddings_layer(group_mu)
         means_concat_embeddings = means_concat_embeddings_layer(
             [subject_embeddings, means_mode_embeddings]
         )
 
         # Get the mean deviation maps (no global magnitude information)
-        means_dev_map_input = means_dev_map_input_layer(means_concat_embeddings)
+        means_dev_map_input = means_dev_map_input_layer([data, means_concat_embeddings])
         means_dev_map = means_dev_map_layer(means_dev_map_input)
         norm_means_dev_map = norm_means_dev_map_layer(means_dev_map)
 
         # Get the deviation magnitudes (scale deviation maps globally)
 
         means_dev_mag_inf_alpha_input = means_dev_mag_inf_alpha_input_layer(data)
         means_dev_mag_inf_alpha = means_dev_mag_inf_alpha_layer(
@@ -842,14 +897,16 @@
 
         covs_dev_map_input_layer = MultiLayerPerceptronLayer(
             config.dev_n_layers,
             config.dev_n_units,
             config.dev_normalization,
             config.dev_activation,
             config.dev_dropout,
+            config.dev_regularizer,
+            config.dev_regularizer_factor,
             name="covs_dev_map_input",
         )
         covs_dev_map_layer = layers.Dense(
             config.n_channels * (config.n_channels + 1) // 2, name="covs_dev_map"
         )
         norm_covs_dev_map_layer = layers.LayerNormalization(
             axis=-1, name="norm_covs_dev_map"
@@ -885,15 +942,15 @@
             InverseCholeskyLayer(config.covariances_epsilon)(group_D)
         )
         covs_concat_embeddings = covs_concat_embeddings_layer(
             [subject_embeddings, covs_mode_embeddings]
         )
 
         # Get the covariance deviation maps (no global magnitude information)
-        covs_dev_map_input = covs_dev_map_input_layer(covs_concat_embeddings)
+        covs_dev_map_input = covs_dev_map_input_layer([data, covs_concat_embeddings])
         covs_dev_map = covs_dev_map_layer(covs_dev_map_input)
         norm_covs_dev_map = norm_covs_dev_map_layer(covs_dev_map)
 
         # Get the deviation magnitudes (scale deviation maps globally)
         covs_dev_mag_inf_alpha_input = covs_dev_mag_inf_alpha_input_layer(data)
         covs_dev_mag_inf_alpha = covs_dev_mag_inf_alpha_layer(
             covs_dev_mag_inf_alpha_input
@@ -950,29 +1007,31 @@
         # Layer definitions
         means_dev_mag_mod_beta_input_layer = MultiLayerPerceptronLayer(
             config.dev_n_layers,
             config.dev_n_units,
             config.dev_normalization,
             config.dev_activation,
             config.dev_dropout,
+            config.dev_regularizer,
+            config.dev_regularizer_factor,
             name="means_dev_mag_mod_beta_input",
         )
         means_dev_mag_mod_beta_layer = layers.Dense(
             1,
             activation="softplus",
             name="means_dev_mag_mod_beta",
         )
 
         means_dev_mag_kl_loss_layer = StaticKLDivergenceLayer(
             config.covariances_epsilon, name="means_dev_mag_kl_loss"
         )
 
         # Data flow
         means_dev_mag_mod_beta_input = means_dev_mag_mod_beta_input_layer(
-            means_concat_embeddings
+            [data, means_concat_embeddings]
         )
         means_dev_mag_mod_beta = means_dev_mag_mod_beta_layer(
             means_dev_mag_mod_beta_input
         )
         means_dev_mag_kl_loss = means_dev_mag_kl_loss_layer(
             [
                 data,
@@ -989,29 +1048,31 @@
         # Layer definitions
         covs_dev_mag_mod_beta_input_layer = MultiLayerPerceptronLayer(
             config.dev_n_layers,
             config.dev_n_units,
             config.dev_normalization,
             config.dev_activation,
             config.dev_dropout,
+            config.dev_regularizer,
+            config.dev_regularizer_factor,
             name="covs_dev_mag_mod_beta_input",
         )
         covs_dev_mag_mod_beta_layer = layers.Dense(
             1,
             activation="softplus",
             name="covs_dev_mag_mod_beta",
         )
 
         covs_dev_mag_kl_loss_layer = StaticKLDivergenceLayer(
             config.covariances_epsilon, name="covs_dev_mag_kl_loss"
         )
 
         # Data flow
         covs_dev_mag_mod_beta_input = covs_dev_mag_mod_beta_input_layer(
-            covs_concat_embeddings
+            [data, covs_concat_embeddings]
         )
         covs_dev_mag_mod_beta = covs_dev_mag_mod_beta_layer(covs_dev_mag_mod_beta_input)
         covs_dev_mag_kl_loss = covs_dev_mag_kl_loss_layer(
             [
                 data,
                 covs_dev_mag_inf_alpha,
                 covs_dev_mag_inf_beta,
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/models/state_dynemo.py` & `osl-dynamics-1.2.4/osl_dynamics/models/state_dynemo.py`

 * *Files 1% similar despite different names*

```diff
@@ -228,15 +228,15 @@
         training_dataset = self.make_dataset(
             training_data, shuffle=True, concatenate=True
         )
 
         # Calculate the number of batches to use
         n_total_batches = dtf.get_n_batches(training_dataset)
         n_batches = max(round(n_total_batches * take), 1)
-        _logging.info(f"Using {n_batches} out of {n_total_batches} batches")
+        _logger.info(f"Using {n_batches} out of {n_total_batches} batches")
 
         # Pick the initialization with the lowest free energy
         best_loss = np.Inf
         for n in range(n_init):
             _logger.info(f"Initialization {n}")
             self.reset()
             self.set_random_state_time_course_initialization(training_data)
@@ -368,15 +368,15 @@
         )
     ll_loss_layer = CategoricalLogLikelihoodLossLayer(
         config.n_states, config.covariances_epsilon, name="ll_loss"
     )
 
     mu = means_layer(data)  # data not used
     D = covs_layer(data)  # data not used
-    ll_loss = ll_loss_layer([data, mu, D, alpha])
+    ll_loss = ll_loss_layer([data, mu, D, alpha, None])
 
     # Model RNN:
     # - p(theta_t | state_<t), predicts logits for the next state based
     #   on a history of states.
     mod_rnn_layer = ModelRNNLayer(
         config.model_rnn,
         config.model_normalization,
@@ -393,9 +393,9 @@
 
     mod_rnn = mod_rnn_layer(states)
     mod_theta = mod_theta_layer(mod_rnn)
     kl_div = kl_div_layer([inf_theta, mod_theta])
     kl_loss = kl_loss_layer(kl_div)
 
     return tf.keras.Model(
-        inputs=data, outputs=[ll_loss, kl_loss, alpha], name="State-DyNeMo"
+        inputs=data, outputs=[ll_loss, kl_loss, inf_theta], name="State-DyNeMo"
     )
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/simulation/__init__.py` & `osl-dynamics-1.2.4/osl_dynamics/simulation/__init__.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/simulation/base.py` & `osl-dynamics-1.2.4/osl_dynamics/simulation/base.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/simulation/hmm.py` & `osl-dynamics-1.2.4/osl_dynamics/simulation/hmm.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/simulation/hsmm.py` & `osl-dynamics-1.2.4/osl_dynamics/simulation/hsmm.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/simulation/mar.py` & `osl-dynamics-1.2.4/osl_dynamics/simulation/mar.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/simulation/mvn.py` & `osl-dynamics-1.2.4/osl_dynamics/simulation/mvn.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/simulation/sin.py` & `osl-dynamics-1.2.4/osl_dynamics/simulation/sin.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/simulation/sm.py` & `osl-dynamics-1.2.4/osl_dynamics/simulation/sm.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/utils/decorators.py` & `osl-dynamics-1.2.4/osl_dynamics/utils/decorators.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/utils/misc.py` & `osl-dynamics-1.2.4/osl_dynamics/utils/misc.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/utils/model.py` & `osl-dynamics-1.2.4/osl_dynamics/utils/model.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/utils/parcellation.py` & `osl-dynamics-1.2.4/osl_dynamics/utils/parcellation.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics/utils/plotting.py` & `osl-dynamics-1.2.4/osl_dynamics/utils/plotting.py`

 * *Files 6% similar despite different names*

```diff
@@ -48,30 +48,30 @@
     fig_kwargs
         Arguments to pass to plt.subplots().
     """
     fig, ax = plt.subplots(*args, **kwargs)
     return fig, ax
 
 
-def show(tight_layout=True):
+def show(tight_layout=False):
     """Displays all figures in memory.
 
     Wrapper for plt.show().
 
     Parameters
     ----------
     tight_layout : bool
         Should we call plt.tight_layout()?
     """
     if tight_layout:
         plt.tight_layout()
     plt.show()
 
 
-def save(fig, filename, tight_layout=True):
+def save(fig, filename, tight_layout=False):
     """Save and close a figure.
 
     Parameters
     ----------
     fig : matplotlib.figure.Figure
         matplotlib figure object.
     filename : str
@@ -284,15 +284,15 @@
 
     # Add a legend
     if add_legend:
         ax.legend(loc=legend_loc)
 
     # Save figure
     if filename is not None:
-        save(fig, filename)
+        save(fig, filename, tight_layout=True)
     elif create_fig:
         return fig, ax
 
 
 def plot_scatter(
     x,
     y,
@@ -446,15 +446,15 @@
 
     # Add a legend
     if add_legend:
         ax.legend(loc=legend_loc)
 
     # Save figure
     if filename is not None:
-        save(fig, filename)
+        save(fig, filename, tight_layout=True)
     elif create_fig:
         return fig, ax
 
 
 def plot_hist(
     data,
     bins,
@@ -569,15 +569,15 @@
 
     # Add a legend
     if add_legend:
         ax.legend(loc=legend_loc)
 
     # Save the figure if a filename has been pass
     if filename is not None:
-        save(fig, filename)
+        save(fig, filename, tight_layout=True)
     elif create_fig:
         return fig, ax
 
 
 def plot_bar_chart(
     counts,
     x=None,
@@ -672,15 +672,15 @@
     # Set title and axis labels
     ax.set_title(title)
     ax.set_xlabel(x_label)
     ax.set_ylabel(y_label)
 
     # Save the figure if a filename has been pass
     if filename is not None:
-        save(fig, filename)
+        save(fig, filename, tight_layout=True)
     elif create_fig:
         return fig, ax
 
 
 def plot_gmm(
     data,
     amplitudes,
@@ -789,15 +789,15 @@
 
     # Add legend
     if legend_loc is not None:
         ax.legend(loc=legend_loc)
 
     # Save the figure if a filename has been pass
     if filename is not None:
-        save(fig, filename)
+        save(fig, filename, tight_layout=True)
     elif create_fig:
         return fig, ax
 
 
 def plot_violin(
     data,
     x=None,
@@ -881,15 +881,15 @@
     # Set title and axis labels
     ax.set_title(title)
     ax.set_xlabel(x_label)
     ax.set_ylabel(y_label)
 
     # Save the figure if a filename has been pass
     if filename is not None:
-        save(fig, filename)
+        save(fig, filename, tight_layout=True)
     elif create_fig:
         return fig, ax
 
 
 def plot_time_series(
     time_series,
     n_samples=None,
@@ -974,15 +974,15 @@
         ax.set_yticks(gaps)
         ax.set_yticklabels(y_tick_values)
     else:
         ax.set_yticks([])
 
     # Save figure
     if filename is not None:
-        save(fig, filename)
+        save(fig, filename, tight_layout=True)
     elif create_fig:
         return fig, ax
 
 
 def plot_separate_time_series(
     *time_series,
     n_samples=None,
@@ -1051,15 +1051,15 @@
     if sampling_frequency is not None:
         axes[-1].set_xlabel("Time (s)")
     else:
         axes[-1].set_xlabel("Sample")
 
     # Save figure
     if filename is not None:
-        save(fig, filename)
+        save(fig, filename, tight_layout=True)
     else:
         return fig, axes
 
 
 def plot_epoched_time_series(
     data,
     time_index,
@@ -1163,15 +1163,15 @@
 
     # Add a legend
     if legend:
         ax.legend(loc=legend_loc)
 
     # Save the figure if a filename has been passed
     if filename is not None:
-        save(fig, filename)
+        save(fig, filename, tight_layout=True)
     elif create_fig:
         return fig, ax
 
 
 def plot_matrices(
     matrix,
     group_color_scale=True,
@@ -1265,15 +1265,15 @@
             cax = divider.append_axes("right", size="5%", pad=0.05)
             plt.colorbar(pl, cax=cax)
         plt.tight_layout()
 
     fig.suptitle(main_title)
 
     if filename is not None:
-        save(fig, filename, tight_layout=False)
+        save(fig, filename)
     else:
         return fig, axes
 
 
 def plot_connections(
     weights,
     labels=None,
@@ -1436,15 +1436,15 @@
                 verticalalignment=vertical_alignment,
             )
 
         ax.autoscale_view()
         plt.setp(ax.spines.values(), visible=False)
 
     if filename is not None:
-        save(fig, filename)
+        save(fig, filename, tight_layout=True)
     else:
         return fig, ax
 
 
 def topoplot(
     layout,
     data,
@@ -1513,15 +1513,15 @@
         colorbar=colorbar,
         axis=axis,
         cmap=cmap,
         n_contours=n_contours,
     )
 
     if filename is not None:
-        save(fig, filename)
+        save(fig, filename, tight_layout=True)
     else:
         return fig
 
 
 def plot_brain_surface(
     values,
     mask_file,
@@ -1711,15 +1711,15 @@
     fig.subplots_adjust(right=0.94)
     cb_ax = fig.add_axes([0.95, 0.15, 0.025, 0.7])
     cb = fig.colorbar(mappable, cax=cb_ax, ticks=np.arange(0.5, n_modes, 1))
     cb.ax.set_yticklabels(range(1, n_modes + 1))
 
     # Save to file if a filename as been passed
     if filename is not None:
-        save(fig, filename, tight_layout=False)
+        save(fig, filename)
     else:
         return fig, axes
 
 
 def plot_mode_lifetimes(
     mode_time_course,
     bins="auto",
@@ -1845,30 +1845,37 @@
                 raise ValueError("x_range must be [x_min, x_max].")
             axis.set_xlim(x_range[0], x_range[1])
         axis.set_xlabel(x_label)
         axis.set_ylabel(y_label)
 
     # Save file is a filename has been passed
     if filename is not None:
-        save(fig, filename)
+        save(fig, filename, tight_layout=True)
     else:
         return fig, axes
 
 
 def plot_psd_topo(
-    f, psd, parcellation_file=None, topomap_pos=[0.45, 0.55, 0.5, 0.55], filename=None
+    f,
+    psd,
+    only_show=None,
+    parcellation_file=None,
+    topomap_pos=[0.45, 0.55, 0.5, 0.55],
+    filename=None,
 ):
     """PLot PSDs for parcels and a topomap.
 
     Parameters
     ----------
     f : np.ndarray
         Frequency axis. Shape must be (n_freq,).
     psd : np.ndarray
         PSD for each parcel. Shape must be (n_parcels, n_freq).
+    only_show : list
+        Indices for parcels to include in the plot. Defaults to all parcels.
     parcellation_file : str
         Path to parcellation file.
     topomap_pos : list
         Positioning and size of the topomap: [x0, y0, width, height].
         x0, y0, width, height should be floats between 0 and 1.
         E.g. [0.45, 0.55, 0.5, 0.55] to place the topomap on the top
         right. This is not used if parcellation_file=None.
@@ -1891,19 +1898,24 @@
         # Re-order to use colour to indicate anterior->posterior location
         order = np.argsort(roi_centers[:, 1])
         roi_centers = roi_centers[order]
         psd = np.copy(psd)[order]
 
     n_parcels = psd.shape[0]
 
+    # Which parcels should we plot the PSD for?
+    if only_show is None:
+        only_show = np.arange(n_parcels)
+
     # Plot PSDs
     fig, ax = create_figure()
     cmap = plt.cm.viridis_r
     for i in reversed(range(n_parcels)):
-        ax.plot(f, psd[i], c=cmap(i / n_parcels))
+        if i in only_show:
+            ax.plot(f, psd[i], c=cmap(i / n_parcels))
     ax.set_xlabel("Frequency (Hz)")
     ax.set_ylabel("PSD (a.u.)")
     ax.set_xlim(f[0], f[-1])
     plt.tight_layout()
 
     if parcellation_file is not None:
         # Plot parcel topomap
@@ -1914,61 +1926,95 @@
             node_size=12,
             colorbar=False,
             axes=inside_ax,
         )
 
     # Save
     if filename is not None:
-        save(fig, filename, tight_layout=False)
+        save(fig, filename)
     else:
         return fig, ax
 
 
-def plot_summary_stats_group_diff(name, summary_stats, pvalues, assignments, filename):
+def plot_summary_stats_group_diff(
+    name,
+    summary_stats,
+    pvalues,
+    assignments,
+    ax=None,
+    filename=None,
+):
     """Plot summary statistics for two groups as violin plots.
 
     Parameters
     ----------
     name : str
         Name of the summary statistic.
     summary_stats : np.ndarray
         Summary statistics. Shape is (n_subjects, n_states).
     pvalues : np.ndarray
         p-values for each summary statistic difference. Shape is (n_states,).
     assignments : np.ndarray
         Array of 1s and 2s indicating group assignment. Shape is (n_subjects,).
+    ax : matplotlib.axes.axes
+        Axis object to plot on.
     filename : str
         Output filename.
+
+    Returns
+    -------
+    fig : matplotlib.pyplot.figure
+        Matplotlib figure object. Only returned if filename=None.
+    ax : matplotlib.pyplot.axis.
+        Matplotlib axis object(s). Only returned if filename=None.
     """
+    # Validation
+    if ax is not None:
+        if filename is not None:
+            raise ValueError(
+                "Please use plotting.save() to save the figure instead of the "
+                + "filename argument."
+            )
+        if isinstance(ax, np.ndarray):
+            raise ValueError("Only pass one axis.")
+
     # Create a pandas DataFrame to hold the summary stats
     ss_dict = {name: [], "State": [], "Group": []}
     n_subjects, n_states = summary_stats.shape
     for subject in range(n_subjects):
         for state in range(n_states):
             ss_dict[name].append(summary_stats[subject, state])
             ss_dict["State"].append(state + 1)
             ss_dict["Group"].append(assignments[subject])
     ss_df = pd.DataFrame(ss_dict)
 
+    # Create figure
+    create_fig = ax is None
+    if create_fig:
+        fig, ax = create_figure(**fig_kwargs)
+
     # Plot a half violin for each group
-    sns.violinplot(data=ss_df, x="State", y=name, hue="Group", split=True)
+    sns.violinplot(data=ss_df, x="State", y=name, hue="Group", split=True, ax=ax)
 
     # Add a star above the violin to indicate significance
     scatter_kwargs = {"c": "black", "s": 32, "marker": "*"}
     for i in range(n_states):
         if pvalues[i] < 0.01:
-            plt.scatter(i - 0.075, summary_stats[:, i].max() * 1.6, **scatter_kwargs)
-            plt.scatter(i + 0.075, summary_stats[:, i].max() * 1.6, **scatter_kwargs)
+            ax.scatter(i - 0.075, summary_stats[:, i].max() * 1.6, **scatter_kwargs)
+            ax.scatter(i + 0.075, summary_stats[:, i].max() * 1.6, **scatter_kwargs)
         elif pvalues[i] < 0.05:
-            plt.scatter(i, summary_stats[:, i].max() * 1.6, **scatter_kwargs)
+            ax.scatter(i, summary_stats[:, i].max() * 1.6, **scatter_kwargs)
 
-    # Save
-    _logger.info(f"Saving {filename}")
-    plt.savefig(filename)
-    plt.close()
+    # Save figure
+    if filename is not None:
+        _logger.info(f"Saving {filename}")
+        plt.savefig(filename)
+        plt.close()
+    elif create_fig:
+        return fig, ax
 
 
 def plot_evoked_response(
     t,
     epochs,
     pvalues,
     significance_level=0.05,
@@ -2081,10 +2127,107 @@
 
     # Add a legend
     if add_legend:
         ax.legend(loc=legend_loc)
 
     # Save figure
     if filename is not None:
+        save(fig, filename, tight_layout=True)
+    elif create_fig:
+        return fig, ax
+
+
+def plot_wavelet(
+    data,
+    sampling_frequency,
+    w=5,
+    standardize=True,
+    time_range=None,
+    frequency_range=None,
+    title=None,
+    add_colorbar=True,
+    fig_kwargs=None,
+    plot_kwargs=None,
+    ax=None,
+    filename=None,
+):
+    """Plot a wavelet transform.
+
+    Parameters
+    ----------
+    data : np.ndarray
+        1D time series data.
+    sampling_frequency : float
+        Sampling frequency in Hz.
+    w : float
+        w parameter to pass to scipy.signal.morlet2.
+    standardize : bool
+        Should we standardize the data before calculating the wavelet?
+    time_range : list
+        Start time and end time to plot in seconds.
+        Default is the full time axis of the data.
+    frequency_range : list of length 2
+        Start and end frequency to plot in Hertz.
+        Default is [1, sampling_frequency / 2].
+    title : str
+        Figure title.
+    add_colorbar : bool
+        If True (default), space will be stolen from the figure to create a colorbar.
+    fig_kwargs : dict
+        Keyword arguments to pass to plt.subplots. Default to {"figsize": (12, 3)}.
+    plot_kwargs : dict
+        Keyword arguments to pass to pcolormesh. Defaults to {"cmap": "rainbow"}.
+    ax : matplotlib.axes.axes
+        Axis object to plot on.
+    filename : str
+        Output filename.
+
+    Returns
+    -------
+    fig : matplotlib.pyplot.figure
+        Matplotlib figure object. Only returned if filename=None.
+    ax : matplotlib.pyplot.axis.
+        Matplotlib axis object(s). Only returned if filename=None.
+    """
+    from osl_dynamics.analysis import spectral
+
+    # Calculate wavelet transform
+    t, f, wt = spectral.wavelet(
+        data=data,
+        sampling_frequency=sampling_frequency,
+        w=w,
+        standardize=standardize,
+        time_range=time_range,
+        frequency_range=frequency_range,
+    )
+
+    # Create figure
+    if fig_kwargs is None:
+        fig_kwargs = {}
+    default_fig_kwargs = {"figsize": (12, 3)}
+    fig_kwargs = override_dict_defaults(default_fig_kwargs, fig_kwargs)
+    create_fig = ax is None
+    if create_fig:
+        fig, ax = create_figure(**fig_kwargs)
+
+    # Plot
+    if plot_kwargs is None:
+        plot_kwargs = {}
+    default_plot_kwargs = {"cmap": "rainbow"}
+    plot_kwargs = override_dict_defaults(default_plot_kwargs, plot_kwargs)
+    mappable = ax.pcolormesh(t, f, wt, **plot_kwargs)
+
+    if add_colorbar:
+        plt.subplots_adjust(bottom=0.2, right=0.8, top=0.9)
+        cax = plt.axes([0.825, 0.1, 0.025, 0.8])
+        plt.colorbar(mappable=mappable, cax=cax)
+
+    # Set title and axis labels
+    ax.set_title(title)
+    ax.set_xlabel("Time (s)")
+    ax.set_ylabel("Frequency (Hz)")
+
+    # Save figure
+    if filename is not None:
         save(fig, filename)
     elif create_fig:
         return fig, ax
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics/utils/topoplots.py` & `osl-dynamics-1.2.4/osl_dynamics/utils/topoplots.py`

 * *Files identical despite different names*

### Comparing `osl-dynamics-1.2.3/osl_dynamics.egg-info/PKG-INFO` & `osl-dynamics-1.2.4/osl_dynamics.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: osl-dynamics
-Version: 1.2.3
+Version: 1.2.4
 Summary: Models for infering dynamics in neuroimaging data
 Home-page: https://github.com/OHBA-analysis/osl-dynamics
 License: MIT
 Project-URL: Documentation, https://osl-dynamics.readthedocs.io/en/latest/
 Description-Content-Type: text/x-rst; charset=UTF-8
 
 ============
```

### Comparing `osl-dynamics-1.2.3/osl_dynamics.egg-info/SOURCES.txt` & `osl-dynamics-1.2.4/osl_dynamics.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -22,15 +22,14 @@
 osl_dynamics/analysis/tinda.py
 osl_dynamics/analysis/workbench.py
 osl_dynamics/config_api/__init__.py
 osl_dynamics/config_api/pipeline.py
 osl_dynamics/config_api/wrappers.py
 osl_dynamics/data/__init__.py
 osl_dynamics/data/base.py
-osl_dynamics/data/osl.py
 osl_dynamics/data/processing.py
 osl_dynamics/data/rw.py
 osl_dynamics/data/spm.py
 osl_dynamics/data/task.py
 osl_dynamics/data/tf.py
 osl_dynamics/files/__init__.py
 osl_dynamics/files/functions.py
```

### Comparing `osl-dynamics-1.2.3/setup.cfg` & `osl-dynamics-1.2.4/setup.cfg`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = osl-dynamics
-version = 1.2.3
+version = 1.2.4
 description = Models for infering dynamics in neuroimaging data
 license = MIT
 long_description = file: README.rst
 long_description_content_type = text/x-rst; charset=UTF-8
 url = https://github.com/OHBA-analysis/osl-dynamics
 project_urls = 
 	Documentation = https://osl-dynamics.readthedocs.io/en/latest/
@@ -52,13 +52,13 @@
 
 [build_sphinx]
 source_dir = doc
 build_dir = build/sphinx
 
 [options.entry_points]
 console_scripts = 
-	osld-pipeline = osl_dynamics.config_api.pipeline:osld_pipeline_cli
+	osl-dynamics = osl_dynamics.config_api.pipeline:osl_dynamics_cli
 
 [egg_info]
 tag_build = 
 tag_date = 0
```

