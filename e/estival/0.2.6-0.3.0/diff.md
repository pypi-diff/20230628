# Comparing `tmp/estival-0.2.6.tar.gz` & `tmp/estival-0.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "estival-0.2.6.tar", max compression
+gzip compressed data, was "estival-0.3.0.tar", max compression
```

## Comparing `estival-0.2.6.tar` & `estival-0.3.0.tar`

### file list

```diff
@@ -1,26 +1,17 @@
--rw-r--r--   0        0        0     3458 2023-05-18 00:47:35.180316 estival-0.2.6/estival/calibration/__pycache__/pymc.cpython-310.pyc
--rw-r--r--   0        0        0     4772 2023-05-06 03:26:51.437183 estival-0.2.6/estival/calibration/__pycache__/pymc.cpython-311.pyc
--rw-r--r--   0        0        0    14995 2023-05-05 04:48:51.863477 estival-0.2.6/estival/calibration/mcmc/__pycache__/adaptive.cpython-310.pyc
--rw-r--r--   0        0        0    25353 2023-05-05 05:24:17.406283 estival-0.2.6/estival/calibration/mcmc/__pycache__/adaptive.cpython-311.pyc
--rw-r--r--   0        0        0    14860 2023-02-20 23:46:02.295570 estival-0.2.6/estival/calibration/mcmc/__pycache__/adaptive.cpython-39.pyc
--rw-r--r--   0        0        0     2324 2023-05-05 04:48:54.568004 estival-0.2.6/estival/calibration/mcmc/__pycache__/covariance.cpython-310.pyc
--rw-r--r--   0        0        0     3213 2023-05-05 05:24:18.633294 estival-0.2.6/estival/calibration/mcmc/__pycache__/covariance.cpython-311.pyc
--rw-r--r--   0        0        0     2328 2023-02-21 00:23:32.275795 estival-0.2.6/estival/calibration/mcmc/__pycache__/covariance.cpython-39.pyc
--rw-r--r--   0        0        0     3211 2023-05-05 04:48:54.551505 estival-0.2.6/estival/calibration/mcmc/__pycache__/transformations.cpython-310.pyc
--rw-r--r--   0        0        0     5303 2023-05-05 05:24:18.606294 estival-0.2.6/estival/calibration/mcmc/__pycache__/transformations.cpython-311.pyc
--rw-r--r--   0        0        0     3288 2022-11-22 23:17:43.763620 estival-0.2.6/estival/calibration/mcmc/__pycache__/transformations.cpython-39.pyc
--rw-r--r--   0        0        0    23290 2023-05-03 06:12:36.018586 estival-0.2.6/estival/calibration/mcmc/adaptive.py
--rw-r--r--   0        0        0     1916 2023-02-21 00:23:01.508628 estival-0.2.6/estival/calibration/mcmc/covariance.py
--rw-r--r--   0        0        0     3408 2023-03-27 20:16:03.557131 estival-0.2.6/estival/calibration/mcmc/transformations.py
--rw-r--r--   0        0        0     3080 2023-05-11 03:41:35.661930 estival-0.2.6/estival/calibration/pymc.py
--rw-r--r--   0        0        0     3957 2023-06-14 03:12:11.683431 estival-0.2.6/estival/model.py
--rw-r--r--   0        0        0     2666 2023-05-03 21:37:51.092087 estival-0.2.6/estival/optimization/__pycache__/nevergrad.cpython-310.pyc
--rw-r--r--   0        0        0     4511 2023-05-05 05:24:18.926797 estival-0.2.6/estival/optimization/__pycache__/nevergrad.cpython-311.pyc
--rw-r--r--   0        0        0     2635 2023-05-03 21:00:19.800964 estival-0.2.6/estival/optimization/nevergrad.py
--rw-r--r--   0        0        0     4192 2023-06-14 03:24:25.980234 estival-0.2.6/estival/priors.py
--rw-r--r--   0        0        0    11486 2023-05-19 02:24:52.265480 estival-0.2.6/estival/targets.py
--rw-r--r--   0        0        0     2806 2023-03-29 04:09:12.012193 estival-0.2.6/estival/utils.py
--rw-r--r--   0        0        0     1320 2022-11-20 23:56:33.173670 estival-0.2.6/LICENSE
--rw-r--r--   0        0        0     1034 2023-06-14 03:13:47.826686 estival-0.2.6/pyproject.toml
--rw-r--r--   0        0        0      669 2023-06-14 03:14:19.151101 estival-0.2.6/README.md
--rw-r--r--   0        0        0     1799 1970-01-01 00:00:00.000000 estival-0.2.6/PKG-INFO
+-rw-r--r--   0        0        0     4837 2023-06-22 22:51:47.913836 estival-0.3.0/estival/model.py
+-rw-r--r--   0        0        0     4396 2023-06-26 23:39:41.366366 estival-0.3.0/estival/priors.py
+-rw-r--r--   0        0        0       69 2023-06-26 23:53:46.119711 estival-0.3.0/estival/sampling/__init__.py
+-rw-r--r--   0        0        0      220 2023-06-27 02:39:58.936134 estival-0.3.0/estival/sampling/__pycache__/__init__.cpython-310.pyc
+-rw-r--r--   0        0        0     2987 2023-06-28 02:53:51.550147 estival-0.3.0/estival/sampling/__pycache__/tools.cpython-310.pyc
+-rw-r--r--   0        0        0     3617 2023-06-28 02:36:09.560248 estival-0.3.0/estival/sampling/tools.py
+-rw-r--r--   0        0        0    11486 2023-05-19 02:24:52.265480 estival-0.3.0/estival/targets.py
+-rw-r--r--   0        0        0     1696 2023-06-28 02:36:46.808894 estival-0.3.0/estival/utils/__pycache__/parallel.cpython-310.pyc
+-rw-r--r--   0        0        0     1636 2023-06-28 02:36:36.802184 estival-0.3.0/estival/utils/parallel.py
+-rw-r--r--   0        0        0     3030 2023-06-28 01:48:29.525182 estival-0.3.0/estival/wrappers/__pycache__/nevergrad.cpython-310.pyc
+-rw-r--r--   0        0        0     3465 2023-06-28 01:50:17.395604 estival-0.3.0/estival/wrappers/__pycache__/pymc.cpython-310.pyc
+-rw-r--r--   0        0        0     2906 2023-06-28 02:05:42.685331 estival-0.3.0/estival/wrappers/nevergrad.py
+-rw-r--r--   0        0        0     3091 2023-06-25 23:10:26.123729 estival-0.3.0/estival/wrappers/pymc.py
+-rw-r--r--   0        0        0     1320 2022-11-20 23:56:33.173670 estival-0.3.0/LICENSE
+-rw-r--r--   0        0        0     1034 2023-06-28 01:49:42.426551 estival-0.3.0/pyproject.toml
+-rw-r--r--   0        0        0      834 2023-06-28 02:57:17.837902 estival-0.3.0/README.md
+-rw-r--r--   0        0        0     1964 1970-01-01 00:00:00.000000 estival-0.3.0/PKG-INFO
```

### Comparing `estival-0.2.6/estival/calibration/__pycache__/pymc.cpython-310.pyc` & `estival-0.3.0/estival/wrappers/__pycache__/pymc.cpython-310.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.10, timestamp-based, .py timestamp: Thu May 11 03:41:35 2023 UTC, .py size: 3080 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 4% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-00000000: 6f0d 0d0a 0000 0000 ef63 5c64 080c 0000  o........c\d....
+00000000: 6f0d 0d0a 0000 0000 62c9 9864 130c 0000  o.......b..d....
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0005 0000 0040 0000 0073 5e00 0000 6400  .....@...s^...d.
 00000030: 6401 6c00 5a01 6400 6401 6c02 5a03 6400  d.l.Z.d.d.l.Z.d.
 00000040: 6401 6c04 6d05 5a06 0100 6400 6402 6c07  d.l.m.Z...d.d.l.
 00000050: 6d08 5a08 0100 6400 6401 6c09 5a09 6403  m.Z...d.d.l.Z.d.
 00000060: 6508 6602 6404 6405 8404 5a0a 640c 6403  e.f.d.d...Z.d.d.
 00000070: 6508 6407 650b 6604 6408 6409 8405 5a0c  e.d.e.f.d.d...Z.
@@ -67,151 +67,151 @@
 00000420: 2020 2020 2020 2020 2020 2050 6172 616d             Param
 00000430: 6574 6572 730a 2020 2020 2020 2020 2020  eters.          
 00000440: 2020 2d2d 2d2d 2d2d 2d2d 2d2d 0a20 2020    ----------.   
 00000450: 2020 2020 2020 2020 2062 636d 3a20 4261           bcm: Ba
 00000460: 7965 7369 616e 436f 6d70 6172 746d 656e  yesianCompartmen
 00000470: 7461 6c4d 6f64 656c 0a20 2020 2020 2020  talModel.       
 00000480: 2020 2020 204e a901 7203 0000 0029 01da       N..r....)..
-00000490: 0473 656c 6672 0500 0000 a900 fa2e 433a  .selfr........C:
+00000490: 0473 656c 6672 0500 0000 a900 fa2b 433a  .selfr.......+C:
 000004a0: 5c64 6576 5c45 4d55 5c65 7374 6976 616c  \dev\EMU\estival
-000004b0: 5c65 7374 6976 616c 5c63 616c 6962 7261  \estival\calibra
-000004c0: 7469 6f6e 5c70 796d 632e 7079 da08 5f5f  tion\pymc.py..__
-000004d0: 696e 6974 5f5f 2b00 0000 7302 0000 000a  init__+...s.....
-000004e0: 0c7a 2b67 6574 5f77 7261 7070 6564 5f6c  .z+get_wrapped_l
-000004f0: 6c2e 3c6c 6f63 616c 733e 2e42 434d 4c6f  l.<locals>.BCMLo
-00000500: 674c 696b 652e 5f5f 696e 6974 5f5f 6304  gLike.__init__c.
-00000510: 0000 0000 0000 0000 0000 0006 0000 0004  ................
-00000520: 0000 0013 0000 0073 4600 0000 7c02 8900  .......sF...|...
-00000530: 8700 6601 6401 6402 8408 7400 7c00 6a01  ..f.d.d...t.|.j.
-00000540: 6a02 8301 4400 8301 7d04 7c00 6a01 6a03  j...D...}.|.j.j.
-00000550: 6404 6900 7c04 a401 8e01 7d05 7404 a005  d.i.|.....}.t...
-00000560: 7c05 a101 7c03 6403 1900 6403 3c00 6400  |...|.d...d.<.d.
-00000570: 5300 2905 4e63 0100 0000 0000 0000 0000  S.).Nc..........
-00000580: 0000 0300 0000 0500 0000 1300 0000 731a  ..............s.
-00000590: 0000 0069 007c 005d 095c 027d 017d 027c  ...i.|.].\.}.}.|
-000005a0: 0288 007c 0119 0093 0271 0253 0072 0700  ...|.....q.S.r..
-000005b0: 0000 7207 0000 0029 03da 022e 30da 0169  ..r....)....0..i
-000005c0: da01 6ba9 01da 0670 6172 616d 7372 0700  ..k....paramsr..
-000005d0: 0000 7208 0000 00da 0a3c 6469 6374 636f  ..r......<dictco
-000005e0: 6d70 3e3b 0000 0073 0200 0000 1a00 7a3e  mp>;...s......z>
-000005f0: 6765 745f 7772 6170 7065 645f 6c6c 2e3c  get_wrapped_ll.<
-00000600: 6c6f 6361 6c73 3e2e 4243 4d4c 6f67 4c69  locals>.BCMLogLi
-00000610: 6b65 2e70 6572 666f 726d 2e3c 6c6f 6361  ke.perform.<loca
-00000620: 6c73 3e2e 3c64 6963 7463 6f6d 703e 7201  ls>.<dictcomp>r.
-00000630: 0000 0072 0700 0000 2906 da09 656e 756d  ...r....)...enum
-00000640: 6572 6174 6572 0300 0000 da06 7072 696f  erater......prio
-00000650: 7273 da0d 6c6f 676c 696b 656c 6968 6f6f  rs..loglikelihoo
-00000660: 64da 026e 70da 0561 7272 6179 2906 7206  d..np..array).r.
-00000670: 0000 00da 046e 6f64 65da 0669 6e70 7574  .....node..input
-00000680: 73da 076f 7574 7075 7473 da06 6b77 6172  s..outputs..kwar
-00000690: 6773 da04 6c6f 676c 7207 0000 0072 0d00  gs..loglr....r..
-000006a0: 0000 7208 0000 00da 0770 6572 666f 726d  ..r......perform
-000006b0: 3900 0000 7308 0000 0004 011a 0112 0316  9...s...........
-000006c0: 027a 2a67 6574 5f77 7261 7070 6564 5f6c  .z*get_wrapped_l
-000006d0: 6c2e 3c6c 6f63 616c 733e 2e42 434d 4c6f  l.<locals>.BCMLo
-000006e0: 674c 696b 652e 7065 7266 6f72 6d4e 290a  gLike.performN).
-000006f0: da08 5f5f 6e61 6d65 5f5f da0a 5f5f 6d6f  ..__name__..__mo
-00000700: 6475 6c65 5f5f da0c 5f5f 7175 616c 6e61  dule__..__qualna
-00000710: 6d65 5f5f da07 5f5f 646f 635f 5fda 0669  me__..__doc__..i
-00000720: 7479 7065 73da 0270 74da 0764 7363 616c  types..pt..dscal
-00000730: 6172 da06 6f74 7970 6573 7209 0000 0072  ar..otypesr....r
-00000740: 1a00 0000 7207 0000 00a9 0272 0300 0000  ....r......r....
-00000750: 5a0b 7072 696f 725f 7479 7065 7372 0700  Z.prior_typesr..
-00000760: 0000 7208 0000 00da 0a42 434d 4c6f 674c  ..r......BCMLogL
-00000770: 696b 651c 0000 0073 0c00 0000 0800 0401  ike....s........
-00000780: 0407 0805 0c02 0c0e 7224 0000 0029 0872  ........r$...).r
-00000790: 1100 0000 da05 6974 656d 73da 0473 697a  ......items..siz
-000007a0: 65da 0661 7070 656e 6472 2000 0000 da07  e..appendr .....
-000007b0: 6476 6563 746f 7272 2100 0000 da02 4f70  dvectorr!.....Op
-000007c0: 2904 7203 0000 0072 0c00 0000 da05 7072  ).r....r......pr
-000007d0: 696f 7272 2400 0000 7207 0000 0072 2300  iorr$...r....r#.
-000007e0: 0000 7208 0000 00da 0e67 6574 5f77 7261  ..r......get_wra
-000007f0: 7070 6564 5f6c 6c0a 0000 0073 0e00 0000  pped_ll....s....
-00000800: 040a 1201 0a01 0e01 0e02 1803 0426 722b  .............&r+
-00000810: 0000 0046 da06 7265 7475 726e 6302 0000  ...F..returnc...
-00000820: 0000 0000 0000 0000 0008 0000 0005 0000  ................
-00000830: 0043 0000 0073 6200 0000 7400 7c00 8301  .C...sb...t.|...
-00000840: 8300 7d02 6700 7d03 7c00 6a01 a002 a100  ..}.g.}.|.j.....
-00000850: 4400 5d0b 5c02 7d04 7d05 7c03 a003 7c05  D.].\.}.}.|...|.
-00000860: a004 a100 a101 0100 710c 6401 6402 8400  ........q.d.d...
-00000870: 7c03 4400 8301 7d06 7405 a006 6403 7c02  |.D...}.t...d.|.
-00000880: 7c06 8e00 a102 7d07 7c01 722f 7405 a007  |.....}.|.r/t...
-00000890: 6404 7c07 a102 0100 7c03 5300 2905 61a3  d.|.....|.S.).a.
-000008a0: 0100 0055 7365 2061 2067 6976 656e 2042  ...Use a given B
-000008b0: 6179 6573 6961 6e43 6f6d 7061 7274 6d65  ayesianCompartme
-000008c0: 6e74 616c 4d6f 6465 6c20 666f 7220 7079  ntalModel for py
-000008d0: 6d63 2073 616d 706c 696e 670a 2020 2020  mc sampling.    
-000008e0: 5468 6973 2073 686f 756c 6420 6265 2063  This should be c
-000008f0: 616c 6c65 6420 696e 7369 6465 2061 206d  alled inside a m
-00000900: 6f64 656c 2063 6f6e 7465 7874 206c 696b  odel context lik
-00000910: 6520 736f 0a0a 2020 2020 7769 7468 2070  e so..    with p
-00000920: 6d2e 4d6f 6465 6c28 293a 0a20 2020 2020  m.Model():.     
-00000930: 2020 2076 6172 6961 626c 6573 203d 2075     variables = u
-00000940: 7365 5f6d 6f64 656c 2862 636d 290a 2020  se_model(bcm).  
-00000950: 2020 2020 2020 706d 2e73 616d 706c 6528        pm.sample(
-00000960: 7374 6570 3d5b 706d 2e44 454d 6574 726f  step=[pm.DEMetro
-00000970: 706f 6c69 7328 7661 7269 6162 6c65 7329  polis(variables)
-00000980: 5d29 0a0a 2020 2020 4172 6773 3a0a 2020  ])..    Args:.  
-00000990: 2020 2020 2020 6263 6d3a 2054 6865 2042        bcm: The B
-000009a0: 434d 2074 6f20 7573 6520 666f 7220 7361  CM to use for sa
-000009b0: 6d70 6c69 6e67 0a20 2020 2020 2020 2069  mpling.        i
-000009c0: 6e63 6c75 6465 5f6c 6c3a 2049 6e63 6c75  nclude_ll: Inclu
-000009d0: 6465 206c 6f67 6c69 6b65 6c69 686f 6f64  de loglikelihood
-000009e0: 2069 6e20 7468 6520 7361 6d70 6c65 206f   in the sample o
-000009f0: 7574 7075 7473 0a0a 2020 2020 5265 7475  utputs..    Retu
-00000a00: 726e 733a 0a20 2020 2020 2020 2054 6865  rns:.        The
-00000a10: 206c 6973 7420 6f66 2076 6172 6961 626c   list of variabl
-00000a20: 6573 2074 6f20 6265 2070 6173 7365 6420  es to be passed 
-00000a30: 746f 2061 2073 616d 706c 6572 2073 7465  to a sampler ste
-00000a40: 700a 2020 2020 6301 0000 0000 0000 0000  p.    c.........
-00000a50: 0000 0002 0000 0005 0000 0053 0000 0073  ...........S...s
-00000a60: 1600 0000 6700 7c00 5d07 7d01 7400 a001  ....g.|.].}.t...
-00000a70: 7c01 a101 9102 7102 5300 7207 0000 0029  |.....q.S.r....)
-00000a80: 0272 2000 0000 da12 6173 5f74 656e 736f  .r .....as_tenso
-00000a90: 725f 7661 7269 6162 6c65 2902 720a 0000  r_variable).r...
-00000aa0: 00da 0176 7207 0000 0072 0700 0000 7208  ...vr....r....r.
-00000ab0: 0000 00da 0a3c 6c69 7374 636f 6d70 3e5b  .....<listcomp>[
-00000ac0: 0000 0073 0200 0000 1600 7a1d 7573 655f  ...s......z.use_
-00000ad0: 6d6f 6465 6c2e 3c6c 6f63 616c 733e 2e3c  model.<locals>.<
-00000ae0: 6c69 7374 636f 6d70 3e72 1200 0000 da07  listcomp>r......
-00000af0: 6c6f 676c 696b 6529 0872 2b00 0000 7211  loglike).r+...r.
-00000b00: 0000 0072 2500 0000 7227 0000 00da 0774  ...r%...r'.....t
-00000b10: 6f5f 7079 6d63 da02 706d da09 506f 7465  o_pymc..pm..Pote
-00000b20: 6e74 6961 6cda 0d44 6574 6572 6d69 6e69  ntial..Determini
-00000b30: 7374 6963 2908 7203 0000 00da 0a69 6e63  stic).r......inc
-00000b40: 6c75 6465 5f6c 6c72 1900 0000 5a0b 7079  lude_llr....Z.py
-00000b50: 6d63 5f70 7269 6f72 7372 0c00 0000 722a  mc_priorsr....r*
-00000b60: 0000 00da 0669 6e76 6172 73da 0370 6f74  .....invars..pot
-00000b70: 7207 0000 0072 0700 0000 7208 0000 00da  r....r....r.....
-00000b80: 0975 7365 5f6d 6f64 656c 4500 0000 7312  .use_modelE...s.
-00000b90: 0000 000a 0f04 0212 0210 010e 0210 0304  ................
-00000ba0: 020c 0104 0272 3800 0000 6302 0000 0000  .....r8...c.....
-00000bb0: 0000 0000 0000 0006 0000 0008 0000 0043  ...............C
-00000bc0: 0000 0073 5400 0000 7400 a001 7c00 a101  ...sT...t...|...
-00000bd0: 7d02 7402 a003 a100 8f17 7d03 7404 7c02  }.t.......}.t.|.
-00000be0: 6401 6402 8d02 7d04 7402 6a05 7c01 6401  d.d...}.t.j.|.d.
-00000bf0: 6401 6403 8d03 7d05 5700 6400 0400 0400  d.d...}.W.d.....
-00000c00: 8303 0100 7c05 5300 3100 7323 7701 0100  ....|.S.1.s#w...
-00000c10: 0100 0100 5900 0100 7c05 5300 2904 4e46  ....Y...|.S.).NF
-00000c20: 2901 7235 0000 0029 02da 1369 6e63 6c75  ).r5...)...inclu
-00000c30: 6465 5f74 7261 6e73 666f 726d 6564 da0b  de_transformed..
-00000c40: 7072 6f67 7265 7373 6261 7229 06da 0b63  progressbar)...c
-00000c50: 6c6f 7564 7069 636b 6c65 da05 6c6f 6164  loudpickle..load
-00000c60: 7372 3200 0000 da05 4d6f 6465 6c72 3800  sr2.....Modelr8.
-00000c70: 0000 da08 6669 6e64 5f4d 4150 2906 5a07  ....find_MAP).Z.
-00000c80: 6263 6d5f 706b 6cda 0469 7661 6c72 0300  bcm_pkl..ivalr..
-00000c90: 0000 da05 6d6f 6465 6cda 0976 6172 6961  ....model..varia
-00000ca0: 626c 6573 5a07 6d61 705f 6573 7472 0700  blesZ.map_estr..
-00000cb0: 0000 7207 0000 0072 0800 0000 da07 7275  ..r....r......ru
-00000cc0: 6e5f 6d61 7066 0000 0073 1000 0000 0a01  n_mapf...s......
-00000cd0: 0a01 0c01 1201 0afe 0403 10fd 0403 7242  ..............rB
-00000ce0: 0000 0029 0146 290e da05 6e75 6d70 7972  ...).F)...numpyr
-00000cf0: 1300 0000 da04 7079 6d63 7232 0000 00da  ......pymcr2....
-00000d00: 0f70 7974 656e 736f 722e 7465 6e73 6f72  .pytensor.tensor
-00000d10: da06 7465 6e73 6f72 7220 0000 00da 0d65  ..tensorr .....e
-00000d20: 7374 6976 616c 2e6d 6f64 656c 7202 0000  stival.modelr...
-00000d30: 0072 3b00 0000 722b 0000 00da 046c 6973  .r;...r+.....lis
-00000d40: 7472 3800 0000 7242 0000 0072 0700 0000  tr8...rB...r....
-00000d50: 7207 0000 0072 0700 0000 7208 0000 00da  r....r....r.....
-00000d60: 083c 6d6f 6475 6c65 3e01 0000 0073 1000  .<module>....s..
-00000d70: 0000 0800 0801 0c01 0c02 0802 0e03 143b  ...............;
-00000d80: 0c21                                     .!
+000004b0: 5c65 7374 6976 616c 5c77 7261 7070 6572  \estival\wrapper
+000004c0: 735c 7079 6d63 2e70 79da 085f 5f69 6e69  s\pymc.py..__ini
+000004d0: 745f 5f2b 0000 0073 0200 0000 0a0c 7a2b  t__+...s......z+
+000004e0: 6765 745f 7772 6170 7065 645f 6c6c 2e3c  get_wrapped_ll.<
+000004f0: 6c6f 6361 6c73 3e2e 4243 4d4c 6f67 4c69  locals>.BCMLogLi
+00000500: 6b65 2e5f 5f69 6e69 745f 5f63 0400 0000  ke.__init__c....
+00000510: 0000 0000 0000 0000 0600 0000 0400 0000  ................
+00000520: 1300 0000 7346 0000 007c 0289 0087 0066  ....sF...|.....f
+00000530: 0164 0164 0284 0874 007c 006a 016a 0283  .d.d...t.|.j.j..
+00000540: 0144 0083 017d 047c 006a 016a 0364 0469  .D...}.|.j.j.d.i
+00000550: 007c 04a4 018e 017d 0574 04a0 057c 05a1  .|.....}.t...|..
+00000560: 017c 0364 0319 0064 033c 0064 0053 0029  .|.d...d.<.d.S.)
+00000570: 054e 6301 0000 0000 0000 0000 0000 0003  .Nc.............
+00000580: 0000 0005 0000 0013 0000 0073 1a00 0000  ...........s....
+00000590: 6900 7c00 5d09 5c02 7d01 7d02 7c02 8800  i.|.].\.}.}.|...
+000005a0: 7c01 1900 9302 7102 5300 7207 0000 0072  |.....q.S.r....r
+000005b0: 0700 0000 2903 da02 2e30 da01 69da 016b  ....)....0..i..k
+000005c0: a901 da06 7061 7261 6d73 7207 0000 0072  ....paramsr....r
+000005d0: 0800 0000 da0a 3c64 6963 7463 6f6d 703e  ......<dictcomp>
+000005e0: 3b00 0000 7302 0000 001a 007a 3e67 6574  ;...s......z>get
+000005f0: 5f77 7261 7070 6564 5f6c 6c2e 3c6c 6f63  _wrapped_ll.<loc
+00000600: 616c 733e 2e42 434d 4c6f 674c 696b 652e  als>.BCMLogLike.
+00000610: 7065 7266 6f72 6d2e 3c6c 6f63 616c 733e  perform.<locals>
+00000620: 2e3c 6469 6374 636f 6d70 3e72 0100 0000  .<dictcomp>r....
+00000630: 7207 0000 0029 06da 0965 6e75 6d65 7261  r....)...enumera
+00000640: 7465 7203 0000 00da 0670 7269 6f72 73da  ter......priors.
+00000650: 0d6c 6f67 6c69 6b65 6c69 686f 6f64 da02  .loglikelihood..
+00000660: 6e70 da05 6172 7261 7929 0672 0600 0000  np..array).r....
+00000670: da04 6e6f 6465 da06 696e 7075 7473 da07  ..node..inputs..
+00000680: 6f75 7470 7574 73da 066b 7761 7267 73da  outputs..kwargs.
+00000690: 046c 6f67 6c72 0700 0000 720d 0000 0072  .loglr....r....r
+000006a0: 0800 0000 da07 7065 7266 6f72 6d39 0000  ......perform9..
+000006b0: 0073 0800 0000 0401 1a01 1203 1602 7a2a  .s............z*
+000006c0: 6765 745f 7772 6170 7065 645f 6c6c 2e3c  get_wrapped_ll.<
+000006d0: 6c6f 6361 6c73 3e2e 4243 4d4c 6f67 4c69  locals>.BCMLogLi
+000006e0: 6b65 2e70 6572 666f 726d 4e29 0ada 085f  ke.performN)..._
+000006f0: 5f6e 616d 655f 5fda 0a5f 5f6d 6f64 756c  _name__..__modul
+00000700: 655f 5fda 0c5f 5f71 7561 6c6e 616d 655f  e__..__qualname_
+00000710: 5fda 075f 5f64 6f63 5f5f da06 6974 7970  _..__doc__..ityp
+00000720: 6573 da02 7074 da07 6473 6361 6c61 72da  es..pt..dscalar.
+00000730: 066f 7479 7065 7372 0900 0000 721a 0000  .otypesr....r...
+00000740: 0072 0700 0000 a902 7203 0000 005a 0b70  .r......r....Z.p
+00000750: 7269 6f72 5f74 7970 6573 7207 0000 0072  rior_typesr....r
+00000760: 0800 0000 da0a 4243 4d4c 6f67 4c69 6b65  ......BCMLogLike
+00000770: 1c00 0000 730c 0000 0008 0004 0104 0708  ....s...........
+00000780: 050c 020c 0e72 2400 0000 2908 7211 0000  .....r$...).r...
+00000790: 00da 0569 7465 6d73 da04 7369 7a65 da06  ...items..size..
+000007a0: 6170 7065 6e64 7220 0000 00da 0764 7665  appendr .....dve
+000007b0: 6374 6f72 7221 0000 00da 024f 7029 0472  ctorr!.....Op).r
+000007c0: 0300 0000 720c 0000 00da 0570 7269 6f72  ....r......prior
+000007d0: 7224 0000 0072 0700 0000 7223 0000 0072  r$...r....r#...r
+000007e0: 0800 0000 da0e 6765 745f 7772 6170 7065  ......get_wrappe
+000007f0: 645f 6c6c 0a00 0000 730e 0000 0004 0a12  d_ll....s.......
+00000800: 010a 010e 010e 0218 0304 2672 2b00 0000  ..........&r+...
+00000810: 46da 0672 6574 7572 6e63 0200 0000 0000  F..returnc......
+00000820: 0000 0000 0000 0900 0000 0500 0000 4300  ..............C.
+00000830: 0000 7366 0000 0074 007c 0083 0183 007d  ..sf...t.|.....}
+00000840: 0267 007d 037c 006a 01a0 02a1 0044 005d  .g.}.|.j.....D.]
+00000850: 0b5c 027d 047d 057c 03a0 037c 05a0 04a1  .\.}.}.|...|....
+00000860: 00a1 0101 0071 0c64 0164 0284 007c 0344  .....q.d.d...|.D
+00000870: 0083 017d 067c 027c 068e 007d 0774 05a0  ...}.|.|...}.t..
+00000880: 0664 037c 07a1 027d 087c 0172 3174 05a0  .d.|...}.|.r1t..
+00000890: 0764 047c 07a1 0201 007c 0353 0029 0561  .d.|.....|.S.).a
+000008a0: a301 0000 5573 6520 6120 6769 7665 6e20  ....Use a given 
+000008b0: 4261 7965 7369 616e 436f 6d70 6172 746d  BayesianCompartm
+000008c0: 656e 7461 6c4d 6f64 656c 2066 6f72 2070  entalModel for p
+000008d0: 796d 6320 7361 6d70 6c69 6e67 0a20 2020  ymc sampling.   
+000008e0: 2054 6869 7320 7368 6f75 6c64 2062 6520   This should be 
+000008f0: 6361 6c6c 6564 2069 6e73 6964 6520 6120  called inside a 
+00000900: 6d6f 6465 6c20 636f 6e74 6578 7420 6c69  model context li
+00000910: 6b65 2073 6f0a 0a20 2020 2077 6974 6820  ke so..    with 
+00000920: 706d 2e4d 6f64 656c 2829 3a0a 2020 2020  pm.Model():.    
+00000930: 2020 2020 7661 7269 6162 6c65 7320 3d20      variables = 
+00000940: 7573 655f 6d6f 6465 6c28 6263 6d29 0a20  use_model(bcm). 
+00000950: 2020 2020 2020 2070 6d2e 7361 6d70 6c65         pm.sample
+00000960: 2873 7465 703d 5b70 6d2e 4445 4d65 7472  (step=[pm.DEMetr
+00000970: 6f70 6f6c 6973 2876 6172 6961 626c 6573  opolis(variables
+00000980: 295d 290a 0a20 2020 2041 7267 733a 0a20  )])..    Args:. 
+00000990: 2020 2020 2020 2062 636d 3a20 5468 6520         bcm: The 
+000009a0: 4243 4d20 746f 2075 7365 2066 6f72 2073  BCM to use for s
+000009b0: 616d 706c 696e 670a 2020 2020 2020 2020  ampling.        
+000009c0: 696e 636c 7564 655f 6c6c 3a20 496e 636c  include_ll: Incl
+000009d0: 7564 6520 6c6f 676c 696b 656c 6968 6f6f  ude loglikelihoo
+000009e0: 6420 696e 2074 6865 2073 616d 706c 6520  d in the sample 
+000009f0: 6f75 7470 7574 730a 0a20 2020 2052 6574  outputs..    Ret
+00000a00: 7572 6e73 3a0a 2020 2020 2020 2020 5468  urns:.        Th
+00000a10: 6520 6c69 7374 206f 6620 7661 7269 6162  e list of variab
+00000a20: 6c65 7320 746f 2062 6520 7061 7373 6564  les to be passed
+00000a30: 2074 6f20 6120 7361 6d70 6c65 7220 7374   to a sampler st
+00000a40: 6570 0a20 2020 2063 0100 0000 0000 0000  ep.    c........
+00000a50: 0000 0000 0200 0000 0500 0000 5300 0000  ............S...
+00000a60: 7316 0000 0067 007c 005d 077d 0174 00a0  s....g.|.].}.t..
+00000a70: 017c 01a1 0191 0271 0253 0072 0700 0000  .|.....q.S.r....
+00000a80: 2902 7220 0000 00da 1261 735f 7465 6e73  ).r .....as_tens
+00000a90: 6f72 5f76 6172 6961 626c 6529 0272 0a00  or_variable).r..
+00000aa0: 0000 da01 7672 0700 0000 7207 0000 0072  ....vr....r....r
+00000ab0: 0800 0000 da0a 3c6c 6973 7463 6f6d 703e  ......<listcomp>
+00000ac0: 5b00 0000 7302 0000 0016 007a 1d75 7365  [...s......z.use
+00000ad0: 5f6d 6f64 656c 2e3c 6c6f 6361 6c73 3e2e  _model.<locals>.
+00000ae0: 3c6c 6973 7463 6f6d 703e 7212 0000 00da  <listcomp>r.....
+00000af0: 076c 6f67 6c69 6b65 2908 722b 0000 0072  .loglike).r+...r
+00000b00: 1100 0000 7225 0000 0072 2700 0000 da07  ....r%...r'.....
+00000b10: 746f 5f70 796d 63da 0270 6dda 0950 6f74  to_pymc..pm..Pot
+00000b20: 656e 7469 616c da0d 4465 7465 726d 696e  ential..Determin
+00000b30: 6973 7469 6329 0972 0300 0000 da0a 696e  istic).r......in
+00000b40: 636c 7564 655f 6c6c 7219 0000 005a 0b70  clude_llr....Z.p
+00000b50: 796d 635f 7072 696f 7273 720c 0000 0072  ymc_priorsr....r
+00000b60: 2a00 0000 da06 696e 7661 7273 da02 6c6c  *.....invars..ll
+00000b70: da03 706f 7472 0700 0000 7207 0000 0072  ..potr....r....r
+00000b80: 0800 0000 da09 7573 655f 6d6f 6465 6c45  ......use_modelE
+00000b90: 0000 0073 1400 0000 0a0f 0402 1202 1001  ...s............
+00000ba0: 0e02 0803 0c01 0402 0c01 0402 7239 0000  ............r9..
+00000bb0: 0063 0200 0000 0000 0000 0000 0000 0600  .c..............
+00000bc0: 0000 0800 0000 4300 0000 7354 0000 0074  ......C...sT...t
+00000bd0: 00a0 017c 00a1 017d 0274 02a0 03a1 008f  ...|...}.t......
+00000be0: 177d 0374 047c 0264 0164 028d 027d 0474  .}.t.|.d.d...}.t
+00000bf0: 026a 057c 0164 0164 0164 038d 037d 0557  .j.|.d.d.d...}.W
+00000c00: 0064 0004 0004 0083 0301 007c 0553 0031  .d.........|.S.1
+00000c10: 0073 2377 0101 0001 0001 0059 0001 007c  .s#w.......Y...|
+00000c20: 0553 0029 044e 4629 0172 3500 0000 2902  .S.).NF).r5...).
+00000c30: da13 696e 636c 7564 655f 7472 616e 7366  ..include_transf
+00000c40: 6f72 6d65 64da 0b70 726f 6772 6573 7362  ormed..progressb
+00000c50: 6172 2906 da0b 636c 6f75 6470 6963 6b6c  ar)...cloudpickl
+00000c60: 65da 056c 6f61 6473 7232 0000 00da 054d  e..loadsr2.....M
+00000c70: 6f64 656c 7239 0000 00da 0866 696e 645f  odelr9.....find_
+00000c80: 4d41 5029 065a 0762 636d 5f70 6b6c da04  MAP).Z.bcm_pkl..
+00000c90: 6976 616c 7203 0000 00da 056d 6f64 656c  ivalr......model
+00000ca0: da09 7661 7269 6162 6c65 735a 076d 6170  ..variablesZ.map
+00000cb0: 5f65 7374 7207 0000 0072 0700 0000 7208  _estr....r....r.
+00000cc0: 0000 00da 0772 756e 5f6d 6170 6700 0000  .....run_mapg...
+00000cd0: 7310 0000 000a 010a 010c 0112 010a fe04  s...............
+00000ce0: 0310 fd04 0372 4300 0000 2901 4629 0eda  .....rC...).F)..
+00000cf0: 056e 756d 7079 7213 0000 00da 0470 796d  .numpyr......pym
+00000d00: 6372 3200 0000 da0f 7079 7465 6e73 6f72  cr2.....pytensor
+00000d10: 2e74 656e 736f 72da 0674 656e 736f 7272  .tensor..tensorr
+00000d20: 2000 0000 da0d 6573 7469 7661 6c2e 6d6f   .....estival.mo
+00000d30: 6465 6c72 0200 0000 723c 0000 0072 2b00  delr....r<...r+.
+00000d40: 0000 da04 6c69 7374 7239 0000 0072 4300  ....listr9...rC.
+00000d50: 0000 7207 0000 0072 0700 0000 7207 0000  ..r....r....r...
+00000d60: 0072 0800 0000 da08 3c6d 6f64 756c 653e  .r......<module>
+00000d70: 0100 0000 7310 0000 0008 0008 010c 010c  ....s...........
+00000d80: 0208 020e 0314 3b0c 22                   ......;."
```

### Comparing `estival-0.2.6/estival/calibration/pymc.py` & `estival-0.3.0/estival/wrappers/pymc.py`

 * *Files 6% similar despite different names*

```diff
@@ -87,18 +87,19 @@
 
     for k, prior in bcm.priors.items():
         pymc_priors.append(prior.to_pymc())
 
     invars = [pt.as_tensor_variable(v) for v in pymc_priors]
 
     # use a Potential to "call" the Op and include it in the logp computation
-    pot = pm.Potential("loglikelihood", logl(*invars))
+    ll = logl(*invars)
+    pot = pm.Potential("loglikelihood", ll)
 
     if include_ll:
-        pm.Deterministic("loglike", pot)
+        pm.Deterministic("loglike", ll)
 
     return pymc_priors
 
 
 def run_map(bcm_pkl, ival):
     bcm = cloudpickle.loads(bcm_pkl)
     with pm.Model() as model:
```

### Comparing `estival-0.2.6/estival/model.py` & `estival-0.3.0/estival/model.py`

 * *Files 27% similar despite different names*

```diff
@@ -7,14 +7,15 @@
 
 import pandas as pd
 
 
 @dataclass
 class ResultsData:
     derived_outputs: pd.DataFrame
+    extras: dict
 
 
 class BayesianCompartmentalModel:
     def __init__(
         self,
         model: CompartmentalModel,
         parameters: dict,
@@ -34,17 +35,17 @@
         self.priors = {p.name: p for p in priors}
 
         self._ref_idx = self.model._get_ref_idx()
         if not isinstance(self._ref_idx, pd.Index):
             self._ref_idx = pd.Index(self._ref_idx)
         self.epoch = self.model.get_epoch()
 
-        self.loglikelihood = self._build_logll_func(extra_ll)
+        self._build_logll_funcs(extra_ll)
 
-    def _build_logll_func(self, extra_ll=None):
+    def _build_logll_funcs(self, extra_ll=None):
         model_params = self.model.get_input_parameters()
         dyn_params = list(model_params.intersection(set(self.priors)))
         self.model.set_derived_outputs_whitelist(list(self.targets))
 
         self._ll_runner = self.model.get_runner(self.parameters, dyn_params)
 
         self.model.set_derived_outputs_whitelist([])
@@ -70,41 +71,66 @@
 
             return logdens
 
         logll.__doc__ = f"""logll({', '.join([k for k in self.priors])})\n
         Run the model for a given set of parameters, and 
         return the loglikelihood of its outputs, including any values from extrall"""
 
-        return logll
+        @jit
+        def logll_multi(modelled_do, **kwargs):
+            out_ll = {}
+
+            for tk, te in self._evaluators.items():
+                modelled = modelled_do[tk]
+                out_ll[tk] = te(modelled, kwargs)
+
+            if extra_ll:
+                out_ll["extra_ll"] = extra_ll(kwargs)
+
+            return out_ll
+
+        self._logll_multi = logll_multi
+        self.loglikelihood = logll
 
     def logprior(self, **parameters):
         lp = 0.0
         for k, p in self.priors.items():
             lp += p.logpdf(parameters[k])
         return lp
 
     def logposterior(self, **parameters):
         return self.loglikelihood(**parameters) + self.logprior(**parameters)
 
-    def run(self, parameters: dict) -> ResultsData:
+    def run(self, parameters: dict, include_extras=False) -> ResultsData:
         """Run the model for a given set of parameters.
         Note that only parameters specified as priors affect the outputs; other parameters
         are in-filled from the initial arguments supplied to BayesianCompartmentalModel
 
         Args:
             parameters: Dict of parameter key/values (as specified in priors)
 
         Returns:
             ResultsData, an extensible container with derived_outputs as a DataFrame
         """
         run_params = {k: v for k, v in parameters.items() if k in self._model_parameters}
         results = self._full_runner._run_func(run_params)
 
+        if include_extras:
+            extras = {}
+            ll_components = self._logll_multi(results["derived_outputs"], **parameters)
+            extras["ll_components"] = ll_components
+            extras["loglikelihood"] = sum(ll_components.values())
+            extras["logprior"] = self.logprior(**parameters)
+            extras["logposterior"] = extras["logprior"] + extras["loglikelihood"]
+        else:
+            extras = {}
+
         return ResultsData(
-            derived_outputs=pd.DataFrame(results["derived_outputs"], index=self._ref_idx)
+            derived_outputs=pd.DataFrame(results["derived_outputs"], index=self._ref_idx),
+            extras=extras,
         )
 
     def run_jax(self, parameters: dict) -> dict:
         """Run the jax run function for the model directly with the supplied parameters;
         meaning bcm.run_jax can be included in JIT calls
 
         Args:
```

### Comparing `estival-0.2.6/estival/optimization/__pycache__/nevergrad.cpython-310.pyc` & `estival-0.3.0/estival/wrappers/__pycache__/nevergrad.cpython-310.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.10, timestamp-based, .py timestamp: Wed May  3 21:00:19 2023 UTC, .py size: 2635 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 21% similar despite different names*

```diff
@@ -1,167 +1,190 @@
-00000000: 6f0d 0d0a 0000 0000 63cb 5264 4b0a 0000  o.......c.RdK...
+00000000: 6f0d 0d0a 0000 0000 0e91 9b64 510b 0000  o..........dQ...
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
-00000020: 000d 0000 0040 0000 0073 ac00 0000 6400  .....@...s....d.
+00000020: 000d 0000 0040 0000 0073 a800 0000 6400  .....@...s....d.
 00000030: 6401 6c00 6d01 5a01 0100 6400 6402 6c02  d.l.m.Z...d.d.l.
 00000040: 6d03 5a03 0100 6400 6403 6c04 6d05 5a05  m.Z...d.d.l.m.Z.
 00000050: 0100 6400 6404 6c06 5a07 6400 6405 6c08  ..d.d.l.Z.d.d.l.
-00000060: 6d09 5a09 0100 6400 6406 6c0a 6d0b 5a0b  m.Z...d.d.l.m.Z.
-00000070: 0100 7a06 6400 6404 6c0c 5a0d 5700 6e04  ..z.d.d.l.Z.W.n.
-00000080: 0100 0100 0100 5900 6416 6408 6409 8401  ......Y.d.d.d...
-00000090: 5a0e 4700 640a 640b 8400 640b 8302 5a0f  Z.G.d.d...d...Z.
-000000a0: 640c 650d 6a10 6a11 6404 6404 6407 6404  d.e.j.j.d.d.d.d.
-000000b0: 640d 6607 640e 6509 640f 6512 6410 6512  d.f.d.e.d.e.d.e.
-000000c0: 6411 6513 6412 6514 6413 6501 660c 6414  d.e.d.e.d.e.f.d.
-000000d0: 6415 8405 5a15 6404 5300 2917 e900 0000  d...Z.d.S.).....
-000000e0: 0029 01da 0843 616c 6c61 626c 6529 01da  .)...Callable)..
-000000f0: 0766 7574 7572 6573 2901 da09 6370 755f  .futures)...cpu_
-00000100: 636f 756e 744e 2901 da1a 4261 7965 7369  countN)...Bayesi
-00000110: 616e 436f 6d70 6172 746d 656e 7461 6c4d  anCompartmentalM
-00000120: 6f64 656c 2901 da08 6e65 6761 7469 7665  odel)...negative
-00000130: da08 6d69 6470 6f69 6e74 6303 0000 0000  ..midpointc.....
-00000140: 0000 0000 0000 000b 0000 0006 0000 0043  ...............C
-00000150: 0000 0073 f400 0000 6900 7d03 7c01 7005  ...s....i.}.|.p.
-00000160: 6900 7d01 6900 7d04 7c00 a000 a100 4400  i.}.i.}.|.....D.
-00000170: 5d35 5c02 7d05 7d06 7c01 a001 7c05 a101  ]5\.}.}.|...|...
-00000180: 0400 7d07 721c 7c07 7c04 7c05 3c00 710c  ..}.r.|.|.|.<.q.
-00000190: 7c02 6401 6b02 7228 7402 a003 6402 7c06  |.d.k.r(t...d.|.
-000001a0: 6a04 a102 7d08 6e12 7c02 6403 6b02 7235  j...}.n.|.d.k.r5
-000001b0: 7402 6a05 6a06 7c06 6a04 6404 8d01 7d08  t.j.j.|.j.d...}.
-000001c0: 6e05 7407 6405 7c02 8302 8201 7c06 a008  n.t.d.|.....|...
-000001d0: 7c08 a101 7c04 7c05 3c00 710c 7c00 a000  |...|.|.<.q.|...
-000001e0: a100 4400 5d2a 5c02 7d05 7d06 7c06 a009  ..D.]*\.}.}.|...
-000001f0: a100 5c02 7d09 7d0a 7c06 6a04 6406 6b02  ..\.}.}.|.j.d.k.
-00000200: 7263 740a 6a0b 6a0c 7c04 7c05 1900 7c09  rct.j.j.|.|...|.
-00000210: 7c0a 6407 8d03 7c03 7c05 3c00 7146 740a  |.d...|.|.<.qFt.
-00000220: 6a0b 6a0d 7c04 7c05 1900 7c09 7c0a 6407  j.j.|.|...|.|.d.
-00000230: 8d03 7c03 7c05 3c00 7146 740a 6a0b 6a0e  ..|.|.<.qFt.j.j.
-00000240: 6408 6900 7c03 a401 8e01 5300 2909 4e72  d.i.|.....S.).Nr
-00000250: 0700 0000 6700 0000 0000 00e0 3fda 0775  ....g.......?..u
-00000260: 6e69 666f 726d 2901 da04 7369 7a65 7a13  niform)...sizez.
-00000270: 496e 7661 6c69 6420 696e 6974 206d 6574  Invalid init met
-00000280: 686f 64e9 0100 0000 2903 da04 696e 6974  hod.....)...init
-00000290: da05 6c6f 7765 72da 0575 7070 6572 a900  ..lower..upper..
-000002a0: 290f da05 6974 656d 73da 0367 6574 da02  )...items..get..
-000002b0: 6e70 da06 7265 7065 6174 7209 0000 00da  np..repeatr.....
-000002c0: 0672 616e 646f 6d72 0800 0000 da0a 5661  .randomr......Va
-000002d0: 6c75 6545 7272 6f72 da03 7070 66da 0662  lueError..ppf..b
-000002e0: 6f75 6e64 73da 026e 67da 0170 da06 5363  ounds..ng..p..Sc
-000002f0: 616c 6172 da05 4172 7261 795a 0f49 6e73  alar..ArrayZ.Ins
-00000300: 7472 756d 656e 7461 7469 6f6e 290b da06  trumentation)...
-00000310: 7072 696f 7273 da09 7375 6767 6573 7465  priors..suggeste
-00000320: 64da 0b69 6e69 745f 6d65 7468 6f64 5a05  d..init_methodZ.
-00000330: 6964 6963 74da 0f73 7461 7274 696e 675f  idict..starting_
-00000340: 706f 696e 7473 da02 706b 7218 0000 005a  points..pkr....Z
-00000350: 0673 7567 5f70 74da 0270 7072 0c00 0000  .sug_pt..ppr....
-00000360: 720d 0000 0072 0e00 0000 720e 0000 00fa  r....r....r.....
-00000370: 382f 6d6e 742f 632f 6465 762f 454d 552f  8/mnt/c/dev/EMU/
-00000380: 6573 7469 7661 6c2f 6573 7469 7661 6c2f  estival/estival/
-00000390: 6f70 7469 6d69 7a61 7469 6f6e 2f6e 6576  optimization/nev
-000003a0: 6572 6772 6164 2e70 79da 1367 6574 5f69  ergrad.py..get_i
-000003b0: 6e73 7472 756d 656e 7461 7469 6f6e 1200  nstrumentation..
-000003c0: 0000 7324 0000 0004 0108 0204 0110 010e  ..s$............
-000003d0: 010a 0108 0210 0108 0112 010a 0210 0110  ................
-000003e0: 020c 010a 011c 011c 0212 0272 2200 0000  ...........r"...
-000003f0: 6300 0000 0000 0000 0000 0000 0000 0000  c...............
-00000400: 0002 0000 0040 0000 0073 1c00 0000 6500  .....@...s....e.
-00000410: 5a01 6400 5a02 6401 6402 8400 5a03 6403  Z.d.Z.d.d...Z.d.
-00000420: 6404 8400 5a04 6405 5300 2906 da09 4f70  d...Z.d.S.)...Op
-00000430: 7452 756e 6e65 7263 0400 0000 0000 0000  tRunnerc........
-00000440: 0000 0000 0400 0000 0200 0000 4300 0000  ............C...
-00000450: 7316 0000 007c 017c 005f 007c 027c 005f  s....|.|._.|.|._
-00000460: 017c 037c 005f 0264 0053 0029 014e 2903  .|.|._.d.S.).N).
-00000470: da09 6f70 7469 6d69 7a65 72da 086d 696e  ..optimizer..min
-00000480: 5f66 756e 63da 0b6e 756d 5f77 6f72 6b65  _func..num_worke
-00000490: 7273 2904 da04 7365 6c66 7224 0000 0072  rs)...selfr$...r
-000004a0: 2500 0000 7226 0000 0072 0e00 0000 720e  %...r&...r....r.
-000004b0: 0000 0072 2100 0000 da08 5f5f 696e 6974  ...r!.....__init
-000004c0: 5f5f 2e00 0000 7306 0000 0006 0106 010a  __....s.........
-000004d0: 017a 124f 7074 5275 6e6e 6572 2e5f 5f69  .z.OptRunner.__i
-000004e0: 6e69 745f 5f63 0200 0000 0000 0000 0000  nit__c..........
-000004f0: 0000 0500 0000 0800 0000 4300 0000 735a  ..........C...sZ
-00000500: 0000 007c 006a 006a 017d 027c 027c 0117  ...|.j.j.}.|.|..
-00000510: 007c 006a 005f 0274 036a 047c 006a 0564  .|.j._.t.j.|.j.d
-00000520: 018d 018f 127d 037c 006a 006a 067c 006a  .....}.|.j.j.|.j
-00000530: 077c 0364 028d 027d 0457 0064 0004 0004  .|.d...}.W.d....
-00000540: 0083 0301 007c 0453 0031 0073 2677 0101  .....|.S.1.s&w..
-00000550: 0001 0001 0059 0001 007c 0453 0029 034e  .....Y...|.S.).N
-00000560: 2901 da0b 6d61 785f 776f 726b 6572 7329  )...max_workers)
-00000570: 01da 0865 7865 6375 746f 7229 0872 2400  ...executor).r$.
-00000580: 0000 5a07 6e75 6d5f 6173 6bda 0662 7564  ..Z.num_ask..bud
-00000590: 6765 7472 0300 0000 da12 5468 7265 6164  getr......Thread
-000005a0: 506f 6f6c 4578 6563 7574 6f72 7226 0000  PoolExecutorr&..
-000005b0: 00da 086d 696e 696d 697a 6572 2500 0000  ...minimizer%...
-000005c0: 2905 7227 0000 0072 2b00 0000 5a07 6375  ).r'...r+...Z.cu
-000005d0: 725f 6173 6b72 2a00 0000 da03 7265 6372  r_askr*.....recr
-000005e0: 0e00 0000 720e 0000 0072 2100 0000 722d  ....r....r!...r-
-000005f0: 0000 0033 0000 0073 1000 0000 0801 0c01  ...3...s........
-00000600: 1001 1401 0aff 0402 10fe 0402 7a12 4f70  ............z.Op
-00000610: 7452 756e 6e65 722e 6d69 6e69 6d69 7a65  tRunner.minimize
-00000620: 4e29 05da 085f 5f6e 616d 655f 5fda 0a5f  N)...__name__.._
-00000630: 5f6d 6f64 756c 655f 5fda 0c5f 5f71 7561  _module__..__qua
-00000640: 6c6e 616d 655f 5f72 2800 0000 722d 0000  lname__r(...r-..
-00000650: 0072 0e00 0000 720e 0000 0072 0e00 0000  .r....r....r....
-00000660: 7221 0000 0072 2300 0000 2d00 0000 7306  r!...r#...-...s.
-00000670: 0000 0008 0008 010c 0572 2300 0000 69e8  .........r#...i.
-00000680: 0300 0054 da03 6263 6d72 2b00 0000 7226  ...T..bcmr+...r&
-00000690: 0000 0072 1c00 0000 721d 0000 00da 0c6f  ...r....r......o
-000006a0: 626a 5f66 756e 6374 696f 6e63 0800 0000  bj_functionc....
-000006b0: 0000 0000 0000 0000 0c00 0000 0500 0000  ................
-000006c0: 4300 0000 7362 0000 007c 0373 0574 0083  C...sb...|.s.t..
-000006d0: 007d 0374 017c 006a 027c 047c 0583 037d  .}.t.|.j.|.|...}
-000006e0: 0864 0164 0284 007d 097c 0664 0075 0072  .d.d...}.|.d.u.r
-000006f0: 177c 006a 037d 067c 0772 1e74 047c 0683  .|.j.}.|.r.t.|..
-00000700: 017d 066e 047c 097c 0683 017d 067c 067d  .}.n.|.|...}.|.}
-00000710: 0a7c 027c 087c 017c 0364 038d 037d 0b74  .|.|.|.|.d...}.t
-00000720: 057c 0b7c 0a7c 0383 0353 0029 044e 6301  .|.|.|...S.).Nc.
-00000730: 0000 0000 0000 0000 0000 0002 0000 0003  ................
-00000740: 0000 0013 0000 0073 1000 0000 8700 6601  .......s......f.
-00000750: 6401 6402 8408 7d01 7c01 5300 2903 4e63  d.d...}.|.S.).Nc
-00000760: 0000 0000 0000 0000 0000 0000 0100 0000  ................
-00000770: 0500 0000 1b00 0000 7312 0000 0074 0088  ........s....t..
-00000780: 0064 0169 007c 00a4 018e 0183 0153 0029  .d.i.|.......S.)
-00000790: 024e 720e 0000 0029 01da 0566 6c6f 6174  .Nr....)...float
-000007a0: 2901 da0a 7061 7261 6d65 7465 7273 a901  )...parameters..
-000007b0: da07 7772 6170 7065 6472 0e00 0000 7221  ..wrappedr....r!
-000007c0: 0000 00da 0d66 6c6f 6174 5f77 7261 7070  .....float_wrapp
-000007d0: 6572 4b00 0000 7302 0000 0012 017a 376f  erK...s......z7o
-000007e0: 7074 696d 697a 655f 6d6f 6465 6c2e 3c6c  ptimize_model.<l
-000007f0: 6f63 616c 733e 2e61 735f 666c 6f61 742e  ocals>.as_float.
-00000800: 3c6c 6f63 616c 733e 2e66 6c6f 6174 5f77  <locals>.float_w
-00000810: 7261 7070 6572 720e 0000 0029 0272 3700  rapperr....).r7.
-00000820: 0000 7238 0000 0072 0e00 0000 7236 0000  ..r8...r....r6..
-00000830: 0072 2100 0000 da08 6173 5f66 6c6f 6174  .r!.....as_float
-00000840: 4a00 0000 7304 0000 000c 0104 037a 206f  J...s........z o
-00000850: 7074 696d 697a 655f 6d6f 6465 6c2e 3c6c  ptimize_model.<l
-00000860: 6f63 616c 733e 2e61 735f 666c 6f61 7429  ocals>.as_float)
-00000870: 035a 0f70 6172 616d 6574 7269 7a61 7469  .Z.parametrizati
-00000880: 6f6e 722b 0000 0072 2600 0000 2906 7204  onr+...r&...).r.
-00000890: 0000 0072 2200 0000 721b 0000 00da 0d6c  ...r"...r......l
-000008a0: 6f67 6c69 6b65 6c69 686f 6f64 7206 0000  oglikelihoodr...
-000008b0: 0072 2300 0000 290c 7232 0000 0072 2b00  .r#...).r2...r+.
-000008c0: 0000 5a09 6f70 745f 636c 6173 7372 2600  ..Z.opt_classr&.
-000008d0: 0000 721c 0000 0072 1d00 0000 7233 0000  ..r....r....r3..
-000008e0: 005a 0f69 6e76 6572 745f 6675 6e63 7469  .Z.invert_functi
-000008f0: 6f6e 5a07 696e 7374 7275 6d72 3900 0000  onZ.instrumr9...
-00000900: 7225 0000 0072 2400 0000 720e 0000 0072  r%...r$...r....r
-00000910: 0e00 0000 7221 0000 00da 0e6f 7074 696d  ....r!.....optim
-00000920: 697a 655f 6d6f 6465 6c3b 0000 0073 1800  ize_model;...s..
-00000930: 0000 040a 0601 0e02 0802 0806 0601 0401  ................
-00000940: 0a01 0802 0402 0e01 0c01 723b 0000 0029  ..........r;...)
-00000950: 024e 7207 0000 0029 16da 0674 7970 696e  .Nr....)...typin
-00000960: 6772 0200 0000 da0a 636f 6e63 7572 7265  gr......concurre
-00000970: 6e74 7203 0000 00da 0f6d 756c 7469 7072  ntr......multipr
-00000980: 6f63 6573 7369 6e67 7204 0000 00da 056e  ocessingr......n
-00000990: 756d 7079 7211 0000 00da 0d65 7374 6976  umpyr......estiv
-000009a0: 616c 2e6d 6f64 656c 7205 0000 005a 0d65  al.modelr....Z.e
-000009b0: 7374 6976 616c 2e75 7469 6c73 7206 0000  stival.utilsr...
-000009c0: 00da 096e 6576 6572 6772 6164 7217 0000  ...nevergradr...
-000009d0: 0072 2200 0000 7223 0000 00da 0a6f 7074  .r"...r#.....opt
-000009e0: 696d 697a 6572 735a 054e 474f 7074 da03  imizersZ.NGOpt..
-000009f0: 696e 74da 0464 6963 74da 0373 7472 723b  int..dict..strr;
-00000a00: 0000 0072 0e00 0000 720e 0000 0072 0e00  ...r....r....r..
-00000a10: 0000 7221 0000 00da 083c 6d6f 6475 6c65  ..r!.....<module
-00000a20: 3e01 0000 0073 4000 0000 0c00 0c02 0c01  >....s@.........
-00000a30: 0801 0c02 0c01 0204 0c01 0601 0201 0a03  ................
-00000a40: 0e1b 0210 0601 0201 0201 0201 0201 0201  ................
-00000a50: 04f8 0201 02ff 0202 02fe 0204 02fc 0205  ................
-00000a60: 02fb 0206 02fa 0207 0ef9                 ..........
+00000060: 6d09 5a09 0100 7a06 6400 6404 6c0a 5a0b  m.Z...z.d.d.l.Z.
+00000070: 5700 6e04 0100 0100 0100 5900 6417 6407  W.n.......Y.d.d.
+00000080: 6408 8401 5a0c 4700 6409 640a 8400 640a  d...Z.G.d.d...d.
+00000090: 8302 5a0d 640b 650b 6a0e 6a0f 6404 6404  ..Z.d.e.j.j.d.d.
+000000a0: 6406 6404 640c 6607 640d 6509 640e 6510  d.d.d.f.d.e.d.e.
+000000b0: 640f 6510 6410 6511 6411 6512 6412 6501  d.e.d.e.d.e.d.e.
+000000c0: 660c 6413 6414 8405 5a13 6415 6416 8400  f.d.d...Z.d.d...
+000000d0: 5a14 6404 5300 2918 e900 0000 0029 01da  Z.d.S.)......)..
+000000e0: 0843 616c 6c61 626c 6529 01da 0766 7574  .Callable)...fut
+000000f0: 7572 6573 2901 da09 6370 755f 636f 756e  ures)...cpu_coun
+00000100: 744e 2901 da1a 4261 7965 7369 616e 436f  tN)...BayesianCo
+00000110: 6d70 6172 746d 656e 7461 6c4d 6f64 656c  mpartmentalModel
+00000120: da08 6d69 6470 6f69 6e74 6303 0000 0000  ..midpointc.....
+00000130: 0000 0000 0000 000b 0000 0006 0000 0043  ...............C
+00000140: 0000 0073 f800 0000 6900 7d03 7c01 6400  ...s....i.}.|.d.
+00000150: 7500 7208 6900 7d01 6900 7d04 7c00 a000  u.r.i.}.i.}.|...
+00000160: a100 4400 5d35 5c02 7d05 7d06 7c01 a001  ..D.]5\.}.}.|...
+00000170: 7c05 a101 0400 7d07 721e 7c07 7c04 7c05  |.....}.r.|.|.|.
+00000180: 3c00 710e 7c02 6401 6b02 722a 7402 a003  <.q.|.d.k.r*t...
+00000190: 6402 7c06 6a04 a102 7d08 6e12 7c02 6403  d.|.j...}.n.|.d.
+000001a0: 6b02 7237 7402 6a05 6a06 7c06 6a04 6404  k.r7t.j.j.|.j.d.
+000001b0: 8d01 7d08 6e05 7407 6405 7c02 8302 8201  ..}.n.t.d.|.....
+000001c0: 7c06 a008 7c08 a101 7c04 7c05 3c00 710e  |...|...|.|.<.q.
+000001d0: 7c00 a000 a100 4400 5d2a 5c02 7d05 7d06  |.....D.]*\.}.}.
+000001e0: 7c06 a009 a100 5c02 7d09 7d0a 7c06 6a04  |.....\.}.}.|.j.
+000001f0: 6406 6b02 7265 740a 6a0b 6a0c 7c04 7c05  d.k.ret.j.j.|.|.
+00000200: 1900 7c09 7c0a 6407 8d03 7c03 7c05 3c00  ..|.|.d...|.|.<.
+00000210: 7148 740a 6a0b 6a0d 7c04 7c05 1900 7c09  qHt.j.j.|.|...|.
+00000220: 7c0a 6407 8d03 7c03 7c05 3c00 7148 740a  |.d...|.|.<.qHt.
+00000230: 6a0b 6a0e 6408 6900 7c03 a401 8e01 5300  j.j.d.i.|.....S.
+00000240: 2909 4e72 0600 0000 6700 0000 0000 00e0  ).Nr....g.......
+00000250: 3fda 0775 6e69 666f 726d 2901 da04 7369  ?..uniform)...si
+00000260: 7a65 7a13 496e 7661 6c69 6420 696e 6974  zez.Invalid init
+00000270: 206d 6574 686f 64e9 0100 0000 2903 da04   method.....)...
+00000280: 696e 6974 da05 6c6f 7765 72da 0575 7070  init..lower..upp
+00000290: 6572 a900 290f da05 6974 656d 73da 0367  er..)...items..g
+000002a0: 6574 da02 6e70 da06 7265 7065 6174 7208  et..np..repeatr.
+000002b0: 0000 00da 0672 616e 646f 6d72 0700 0000  .....randomr....
+000002c0: da0a 5661 6c75 6545 7272 6f72 da03 7070  ..ValueError..pp
+000002d0: 66da 0662 6f75 6e64 73da 026e 67da 0170  f..bounds..ng..p
+000002e0: da06 5363 616c 6172 da05 4172 7261 795a  ..Scalar..ArrayZ
+000002f0: 0f49 6e73 7472 756d 656e 7461 7469 6f6e  .Instrumentation
+00000300: 290b da06 7072 696f 7273 da09 7375 6767  )...priors..sugg
+00000310: 6573 7465 64da 0b69 6e69 745f 6d65 7468  ested..init_meth
+00000320: 6f64 5a05 6964 6963 745a 0f73 7461 7274  odZ.idictZ.start
+00000330: 696e 675f 706f 696e 7473 da02 706b 7217  ing_points..pkr.
+00000340: 0000 005a 0673 7567 5f70 74da 0270 7072  ...Z.sug_pt..ppr
+00000350: 0b00 0000 720c 0000 0072 0d00 0000 720d  ....r....r....r.
+00000360: 0000 00fa 3043 3a5c 6465 765c 454d 555c  ....0C:\dev\EMU\
+00000370: 6573 7469 7661 6c5c 6573 7469 7661 6c5c  estival\estival\
+00000380: 7772 6170 7065 7273 5c6e 6576 6572 6772  wrappers\nevergr
+00000390: 6164 2e70 79da 1367 6574 5f69 6e73 7472  ad.py..get_instr
+000003a0: 756d 656e 7461 7469 6f6e 1100 0000 7326  umentation....s&
+000003b0: 0000 0004 0108 0204 0104 0210 010e 010a  ................
+000003c0: 0108 0210 0108 0112 010a 0210 0110 020c  ................
+000003d0: 010a 011c 011c 0212 0272 2000 0000 6300  .........r ...c.
+000003e0: 0000 0000 0000 0000 0000 0000 0000 0002  ................
+000003f0: 0000 0040 0000 0073 1c00 0000 6500 5a01  ...@...s....e.Z.
+00000400: 6400 5a02 6401 6402 8400 5a03 6403 6404  d.Z.d.d...Z.d.d.
+00000410: 8400 5a04 6405 5300 2906 da09 4f70 7452  ..Z.d.S.)...OptR
+00000420: 756e 6e65 7263 0400 0000 0000 0000 0000  unnerc..........
+00000430: 0000 0400 0000 0200 0000 4300 0000 7316  ..........C...s.
+00000440: 0000 007c 017c 005f 007c 027c 005f 017c  ...|.|._.|.|._.|
+00000450: 037c 005f 0264 0053 0029 014e 2903 da09  .|._.d.S.).N)...
+00000460: 6f70 7469 6d69 7a65 72da 086d 696e 5f66  optimizer..min_f
+00000470: 756e 63da 0b6e 756d 5f77 6f72 6b65 7273  unc..num_workers
+00000480: 2904 da04 7365 6c66 7222 0000 0072 2300  )...selfr"...r#.
+00000490: 0000 7224 0000 0072 0d00 0000 720d 0000  ..r$...r....r...
+000004a0: 0072 1f00 0000 da08 5f5f 696e 6974 5f5f  .r......__init__
+000004b0: 2f00 0000 7306 0000 0006 0106 010a 017a  /...s..........z
+000004c0: 124f 7074 5275 6e6e 6572 2e5f 5f69 6e69  .OptRunner.__ini
+000004d0: 745f 5f63 0200 0000 0000 0000 0000 0000  t__c............
+000004e0: 0500 0000 0800 0000 4300 0000 735a 0000  ........C...sZ..
+000004f0: 007c 006a 006a 017d 027c 027c 0117 007c  .|.j.j.}.|.|...|
+00000500: 006a 005f 0274 036a 047c 006a 0564 018d  .j._.t.j.|.j.d..
+00000510: 018f 127d 037c 006a 006a 067c 006a 077c  ...}.|.j.j.|.j.|
+00000520: 0364 028d 027d 0457 0064 0004 0004 0083  .d...}.W.d......
+00000530: 0301 007c 0453 0031 0073 2677 0101 0001  ...|.S.1.s&w....
+00000540: 0001 0059 0001 007c 0453 0029 034e 2901  ...Y...|.S.).N).
+00000550: da0b 6d61 785f 776f 726b 6572 7329 01da  ..max_workers)..
+00000560: 0865 7865 6375 746f 7229 0872 2200 0000  .executor).r"...
+00000570: 5a07 6e75 6d5f 6173 6bda 0662 7564 6765  Z.num_ask..budge
+00000580: 7472 0300 0000 da12 5468 7265 6164 506f  tr......ThreadPo
+00000590: 6f6c 4578 6563 7574 6f72 7224 0000 00da  olExecutorr$....
+000005a0: 086d 696e 696d 697a 6572 2300 0000 2905  .minimizer#...).
+000005b0: 7225 0000 0072 2900 0000 5a07 6375 725f  r%...r)...Z.cur_
+000005c0: 6173 6b72 2800 0000 da03 7265 6372 0d00  askr(.....recr..
+000005d0: 0000 720d 0000 0072 1f00 0000 722b 0000  ..r....r....r+..
+000005e0: 0034 0000 0073 1000 0000 0801 0c01 1001  .4...s..........
+000005f0: 1401 0aff 0402 10fe 0402 7a12 4f70 7452  ..........z.OptR
+00000600: 756e 6e65 722e 6d69 6e69 6d69 7a65 4e29  unner.minimizeN)
+00000610: 05da 085f 5f6e 616d 655f 5fda 0a5f 5f6d  ...__name__..__m
+00000620: 6f64 756c 655f 5fda 0c5f 5f71 7561 6c6e  odule__..__qualn
+00000630: 616d 655f 5f72 2600 0000 722b 0000 0072  ame__r&...r+...r
+00000640: 0d00 0000 720d 0000 0072 0d00 0000 721f  ....r....r....r.
+00000650: 0000 0072 2100 0000 2e00 0000 7306 0000  ...r!.......s...
+00000660: 0008 0008 010c 0572 2100 0000 69e8 0300  .......r!...i...
+00000670: 0054 da03 6263 6d72 2900 0000 7224 0000  .T..bcmr)...r$..
+00000680: 0072 1b00 0000 721c 0000 00da 0c6f 626a  .r....r......obj
+00000690: 5f66 756e 6374 696f 6e63 0800 0000 0000  _functionc......
+000006a0: 0000 0000 0000 0c00 0000 0500 0000 4300  ..............C.
+000006b0: 0000 7362 0000 007c 0373 0574 0083 007d  ..sb...|.s.t...}
+000006c0: 0374 017c 006a 027c 047c 0583 037d 0864  .t.|.j.|.|...}.d
+000006d0: 0164 0284 007d 097c 0664 0075 0072 177c  .d...}.|.d.u.r.|
+000006e0: 006a 037d 067c 0772 1e74 047c 0683 017d  .j.}.|.r.t.|...}
+000006f0: 066e 047c 097c 0683 017d 067c 067d 0a7c  .n.|.|...}.|.}.|
+00000700: 027c 087c 017c 0364 038d 037d 0b74 057c  .|.|.|.d...}.t.|
+00000710: 0b7c 0a7c 0383 0353 0029 044e 6301 0000  .|.|...S.).Nc...
+00000720: 0000 0000 0000 0000 0002 0000 0003 0000  ................
+00000730: 0013 0000 0073 1000 0000 8700 6601 6401  .....s......f.d.
+00000740: 6402 8408 7d01 7c01 5300 2903 4e63 0000  d...}.|.S.).Nc..
+00000750: 0000 0000 0000 0000 0000 0100 0000 0500  ................
+00000760: 0000 1b00 0000 7312 0000 0074 0088 0064  ......s....t...d
+00000770: 0169 007c 00a4 018e 0183 0153 0029 024e  .i.|.......S.).N
+00000780: 720d 0000 00a9 01da 0566 6c6f 6174 2901  r........float).
+00000790: da0a 7061 7261 6d65 7465 7273 a901 da07  ..parameters....
+000007a0: 7772 6170 7065 6472 0d00 0000 721f 0000  wrappedr....r...
+000007b0: 00da 0d66 6c6f 6174 5f77 7261 7070 6572  ...float_wrapper
+000007c0: 4c00 0000 7302 0000 0012 017a 376f 7074  L...s......z7opt
+000007d0: 696d 697a 655f 6d6f 6465 6c2e 3c6c 6f63  imize_model.<loc
+000007e0: 616c 733e 2e61 735f 666c 6f61 742e 3c6c  als>.as_float.<l
+000007f0: 6f63 616c 733e 2e66 6c6f 6174 5f77 7261  ocals>.float_wra
+00000800: 7070 6572 720d 0000 0029 0272 3600 0000  pperr....).r6...
+00000810: 7237 0000 0072 0d00 0000 7235 0000 0072  r7...r....r5...r
+00000820: 1f00 0000 da08 6173 5f66 6c6f 6174 4b00  ......as_floatK.
+00000830: 0000 7304 0000 000c 0104 037a 206f 7074  ..s........z opt
+00000840: 696d 697a 655f 6d6f 6465 6c2e 3c6c 6f63  imize_model.<loc
+00000850: 616c 733e 2e61 735f 666c 6f61 7429 035a  als>.as_float).Z
+00000860: 0f70 6172 616d 6574 7269 7a61 7469 6f6e  .parametrization
+00000870: 7229 0000 0072 2400 0000 2906 7204 0000  r)...r$...).r...
+00000880: 0072 2000 0000 721a 0000 00da 0d6c 6f67  .r ...r......log
+00000890: 6c69 6b65 6c69 686f 6f64 da08 6e65 6761  likelihood..nega
+000008a0: 7469 7665 7221 0000 0029 0c72 3000 0000  tiver!...).r0...
+000008b0: 7229 0000 005a 096f 7074 5f63 6c61 7373  r)...Z.opt_class
+000008c0: 7224 0000 0072 1b00 0000 721c 0000 0072  r$...r....r....r
+000008d0: 3100 0000 5a0f 696e 7665 7274 5f66 756e  1...Z.invert_fun
+000008e0: 6374 696f 6e5a 0769 6e73 7472 756d 7238  ctionZ.instrumr8
+000008f0: 0000 0072 2300 0000 7222 0000 0072 0d00  ...r#...r"...r..
+00000900: 0000 720d 0000 0072 1f00 0000 da0e 6f70  ..r....r......op
+00000910: 7469 6d69 7a65 5f6d 6f64 656c 3c00 0000  timize_model<...
+00000920: 7318 0000 0004 0a06 010e 0208 0208 0606  s...............
+00000930: 0104 010a 0108 0204 020e 010c 0172 3b00  .............r;.
+00000940: 0000 6301 0000 0000 0000 0000 0000 0004  ..c.............
+00000950: 0000 0003 0000 000f 0000 0073 1000 0000  ...........s....
+00000960: 8700 6601 6401 6402 8408 7d03 7c03 5300  ..f.d.d...}.|.S.
+00000970: 2903 7a7c 5772 6170 2061 2070 6f73 6974  ).z|Wrap a posit
+00000980: 6976 6520 6675 6e63 7469 6f6e 2073 7563  ive function suc
+00000990: 6820 7468 6174 2061 206d 696e 696d 697a  h that a minimiz
+000009a0: 6162 6c65 2076 6572 7369 6f6e 2069 7320  able version is 
+000009b0: 7265 7475 726e 6564 2069 6e73 7465 6164  returned instead
+000009c0: 0a0a 2020 2020 4172 6773 3a0a 2020 2020  ..    Args:.    
+000009d0: 2020 2020 663a 2054 6865 2063 616c 6c61      f: The calla
+000009e0: 626c 6520 746f 2077 7261 700a 2020 2020  ble to wrap.    
+000009f0: 6300 0000 0000 0000 0000 0000 0002 0000  c...............
+00000a00: 0006 0000 001f 0000 0073 1600 0000 7400  .........s....t.
+00000a10: 6401 8800 7c00 6900 7c01 a401 8e01 1800  d...|.i.|.......
+00000a20: 8301 5300 2902 4e67 0000 0000 0000 0000  ..S.).Ng........
+00000a30: 7232 0000 0029 02da 0461 7267 73da 066b  r2...)...args..k
+00000a40: 7761 7267 73a9 01da 0166 720d 0000 0072  wargs....fr....r
+00000a50: 1f00 0000 da0a 5f72 6566 6c65 6374 6564  ......_reflected
+00000a60: 6400 0000 7302 0000 0016 017a 1c6e 6567  d...s......z.neg
+00000a70: 6174 6976 652e 3c6c 6f63 616c 733e 2e5f  ative.<locals>._
+00000a80: 7265 666c 6563 7465 6472 0d00 0000 2904  reflectedr....).
+00000a90: 723f 0000 0072 3c00 0000 723d 0000 0072  r?...r<...r=...r
+00000aa0: 4000 0000 720d 0000 0072 3e00 0000 721f  @...r....r>...r.
+00000ab0: 0000 0072 3a00 0000 5d00 0000 7304 0000  ...r:...]...s...
+00000ac0: 000c 0704 0372 3a00 0000 2902 4e72 0600  .....r:...).Nr..
+00000ad0: 0000 2915 da06 7479 7069 6e67 7202 0000  ..)...typingr...
+00000ae0: 00da 0a63 6f6e 6375 7272 656e 7472 0300  ...concurrentr..
+00000af0: 0000 da0f 6d75 6c74 6970 726f 6365 7373  ....multiprocess
+00000b00: 696e 6772 0400 0000 da05 6e75 6d70 7972  ingr......numpyr
+00000b10: 1000 0000 da0d 6573 7469 7661 6c2e 6d6f  ......estival.mo
+00000b20: 6465 6c72 0500 0000 5a09 6e65 7665 7267  delr....Z.neverg
+00000b30: 7261 6472 1600 0000 7220 0000 0072 2100  radr....r ...r!.
+00000b40: 0000 5a0a 6f70 7469 6d69 7a65 7273 5a05  ..Z.optimizersZ.
+00000b50: 4e47 4f70 74da 0369 6e74 da04 6469 6374  NGOpt..int..dict
+00000b60: da03 7374 7272 3b00 0000 723a 0000 0072  ..strr;...r:...r
+00000b70: 0d00 0000 720d 0000 0072 0d00 0000 721f  ....r....r....r.
+00000b80: 0000 00da 083c 6d6f 6475 6c65 3e01 0000  .....<module>...
+00000b90: 0073 4000 0000 0c00 0c02 0c01 0802 0c02  .s@.............
+00000ba0: 0203 0c01 0601 0201 0a03 0e1d 0210 0601  ................
+00000bb0: 0201 0201 0201 0201 0201 04f8 0201 02ff  ................
+00000bc0: 0202 02fe 0204 02fc 0205 02fb 0206 02fa  ................
+00000bd0: 0207 0af9 0c21                           .....!
```

### Comparing `estival-0.2.6/estival/optimization/nevergrad.py` & `estival-0.3.0/estival/wrappers/nevergrad.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,29 @@
 from typing import Callable
 
 from concurrent import futures
 from multiprocessing import cpu_count
+
 import numpy as np
 
 from estival.model import BayesianCompartmentalModel
-from estival.utils import negative
-
 
 # This is optional, just be silent if it's not installed...
 try:
     import nevergrad as ng
 except:
     pass
 
 
 def get_instrumentation(priors, suggested=None, init_method="midpoint"):
     idict = {}
 
-    suggested = suggested or {}
+    if suggested is None:
+        suggested = {}
+
     starting_points = {}
     for pk, p in priors.items():
         if sug_pt := suggested.get(pk):
             starting_points[pk] = sug_pt
         else:
             if init_method == "midpoint":
                 pp = np.repeat(0.5, p.size)
@@ -63,15 +64,15 @@
     num_workers: int = None,
     suggested: dict = None,
     init_method: str = "midpoint",
     obj_function: Callable = None,
     invert_function=True,
 ):
     if not num_workers:
-        num_workers = cpu_count()
+        num_workers = int(cpu_count() / 2)
 
     instrum = get_instrumentation(bcm.priors, suggested, init_method)
 
     def as_float(wrapped):
         def float_wrapper(**parameters):
             return float(wrapped(**parameters))
 
@@ -83,7 +84,20 @@
         obj_function = negative(obj_function)
     else:
         obj_function = as_float(obj_function)
 
     min_func = obj_function
     optimizer = opt_class(parametrization=instrum, budget=budget, num_workers=num_workers)
     return OptRunner(optimizer, min_func, num_workers)
+
+
+def negative(f, *args, **kwargs):
+    """Wrap a positive function such that a minimizable version is returned instead
+
+    Args:
+        f: The callable to wrap
+    """
+
+    def _reflected(*args, **kwargs):
+        return float(0.0 - f(*args, **kwargs))
+
+    return _reflected
```

### Comparing `estival-0.2.6/estival/priors.py` & `estival-0.3.0/estival/priors.py`

 * *Files 6% similar despite different names*

```diff
@@ -110,14 +110,17 @@
         if self.size > 1:
             lower = np.repeat(self.start, self.size)
             upper = np.repeat(self.end, self.size)
         else:
             lower, upper = self.start, self.end
         return pm.Uniform(self.name, lower=lower, upper=upper)
 
+    def __repr__(self):
+        return f"UniformPrior bounds: {self.bounds()}"
+
 
 class TruncNormalPrior(BasePrior):
     """
     A prior with a truncated normal distribution.
     """
 
     def __init__(
@@ -138,7 +141,10 @@
         lower, upper = self.trunc_range
         if self.size > 1:
             lower = np.repeat(lower, self.size)
             upper = np.repeat(upper, self.size)
         return pm.TruncatedNormal(
             self.name, mu=self.mean, sigma=self.stdev, lower=lower, upper=upper
         )
+
+    def __repr__(self):
+        return f"TruncNormalPrior mean: {self.mean}, stdev: {self.stdev}, bounds: {self.bounds()}"
```

### Comparing `estival-0.2.6/estival/targets.py` & `estival-0.3.0/estival/targets.py`

 * *Files identical despite different names*

### Comparing `estival-0.2.6/LICENSE` & `estival-0.3.0/LICENSE`

 * *Files identical despite different names*

### Comparing `estival-0.2.6/pyproject.toml` & `estival-0.3.0/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "estival"
-version = "0.2.6"
+version = "0.3.0"
 readme = "README.md"
 license = "BSD-2-Clause"
 homepage = "https://github.com/monash-emu/estival"
 repository = "https://github.com/monash-emu/estival"
 documentation = "https://github.com/monash-emu/estival"
 keywords = [
     "calibration",
```

### Comparing `estival-0.2.6/README.md` & `estival-0.3.0/README.md`

 * *Files 10% similar despite different names*

```diff
@@ -14,8 +14,14 @@
 Include tensorflow-probability(jax) for more (and better tested) stats modules
 - 0.2.4
 Bugfix (vector priors were not exported to pymc correctly)
 Add Epoch support to allow DatetimeIndex targets
 - 0.2.5
 Bugfix for BinomialTarget (wasn't indexing modelled data)
 - 0.2.6
-Bugfix (reference index for models without date returned incorrect type)
+Bugfix (reference index for models without date returned incorrect type)
+- 0.3.0
+Note - breaking changes!
+Remove old AuTuMN MCMC implementation
+Move nevergrad/pymc -> wrappers
+Expand likelihood output tools
+Include parallelism framework
```

### Comparing `estival-0.2.6/PKG-INFO` & `estival-0.3.0/PKG-INFO`

 * *Files 26% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: estival
-Version: 0.2.6
+Version: 0.3.0
 Summary: A set of calibration and probabilistic programming tools for use with summerepi2
 Home-page: https://github.com/monash-emu/estival
 License: BSD-2-Clause
 Keywords: calibration,optimization,bayesian,compartmental modelling,summerepi
 Author: David Shipman
 Author-email: dshipman@gmail.com
 Requires-Python: >=3.8.0,<4.0.0
@@ -43,7 +43,14 @@
 - 0.2.4
 Bugfix (vector priors were not exported to pymc correctly)
 Add Epoch support to allow DatetimeIndex targets
 - 0.2.5
 Bugfix for BinomialTarget (wasn't indexing modelled data)
 - 0.2.6
 Bugfix (reference index for models without date returned incorrect type)
+- 0.3.0
+Note - breaking changes!
+Remove old AuTuMN MCMC implementation
+Move nevergrad/pymc -> wrappers
+Expand likelihood output tools
+Include parallelism framework
+
```

