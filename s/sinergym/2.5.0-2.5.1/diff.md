# Comparing `tmp/sinergym-2.5.0.tar.gz` & `tmp/sinergym-2.5.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sinergym-2.5.0.tar", last modified: Thu Jun  1 14:14:15 2023, max compression
+gzip compressed data, was "sinergym-2.5.1.tar", last modified: Wed Jun 28 09:24:39 2023, max compression
```

## Comparing `sinergym-2.5.0.tar` & `sinergym-2.5.1.tar`

### file list

```diff
@@ -1,82 +1,82 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 14:14:15.225474 sinergym-2.5.0/
--rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-06-01 14:14:12.000000 sinergym-2.5.0/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       87 2023-06-01 14:14:12.000000 sinergym-2.5.0/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)    12180 2023-06-01 14:14:15.225474 sinergym-2.5.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11272 2023-06-01 14:14:12.000000 sinergym-2.5.0/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-01 14:14:14.000000 sinergym-2.5.0/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-01 14:14:15.225474 sinergym-2.5.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2803 2023-06-01 14:14:14.000000 sinergym-2.5.0/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 14:14:15.193473 sinergym-2.5.0/sinergym/
--rw-r--r--   0 runner    (1001) docker     (123)    95280 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 14:14:15.193473 sinergym-2.5.0/sinergym/config/
--rw-r--r--   0 runner    (1001) docker     (123)      106 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/config/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    36311 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/config/modeling.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 14:14:15.193473 sinergym-2.5.0/sinergym/data/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 14:14:15.197473 sinergym-2.5.0/sinergym/data/buildings/
--rw-r--r--   0 runner    (1001) docker     (123)   167116 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/buildings/2ZoneDataCenterHVAC_wEconomizer.epJSON
--rw-r--r--   0 runner    (1001) docker     (123)   153252 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/buildings/5ZoneAutoDXVAV.epJSON
--rw-r--r--   0 runner    (1001) docker     (123)   595916 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/buildings/ASHRAE901_OfficeMedium_STD2019_Denver.epJSON
--rw-r--r--   0 runner    (1001) docker     (123)   273893 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/buildings/ASHRAE901_Warehouse_STD2019_Denver.epJSON
--rw-r--r--   0 runner    (1001) docker     (123)   522393 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/buildings/LrgOff_GridStorageScheduled.epJSON
--rw-r--r--   0 runner    (1001) docker     (123)   251679 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/buildings/ShopWithPVandBattery.epJSON
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 14:14:15.197473 sinergym-2.5.0/sinergym/data/variables/
--rw-r--r--   0 runner    (1001) docker     (123)    39571 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/variables/2ZoneDataCenterHVAC_wEconomizer.rdd
--rw-r--r--   0 runner    (1001) docker     (123)    35724 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/variables/5ZoneAutoDXVAV.rdd
--rw-r--r--   0 runner    (1001) docker     (123)    43088 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/variables/ASHRAE901_OfficeMedium_STD2019_Denver.rdd
--rw-r--r--   0 runner    (1001) docker     (123)    40843 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/variables/ASHRAE901_Warehouse_STD2019_Denver.rdd
--rw-r--r--   0 runner    (1001) docker     (123)    45556 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/variables/LrgOff_GridStorageScheduled.rdd
--rw-r--r--   0 runner    (1001) docker     (123)    46370 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/variables/ShopWithPVandBattery.rdd
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 14:14:15.221474 sinergym-2.5.0/sinergym/data/weather/
--rw-r--r--   0 runner    (1001) docker     (123)    28629 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1565086 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28503 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/COL_Bogota.802220_IWEC.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1550279 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/COL_Bogota.802220_IWEC.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28704 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/ESP_Granada.084190_SWEC.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1621761 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/ESP_Granada.084190_SWEC.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28716 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/FIN_Helsinki.029740_IWEC.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1553382 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/FIN_Helsinki.029740_IWEC.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28801 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1558629 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28740 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1558423 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28659 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/PRT_Lisboa.085360_INETI.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1601571 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/PRT_Lisboa.085360_INETI.epw
--rw-r--r--   0 runner    (1001) docker     (123)    29016 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1637298 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.epw
--rw-r--r--   0 runner    (1001) docker     (123)    29489 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1629153 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28793 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1639985 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.epw
--rw-r--r--   0 runner    (1001) docker     (123)    29614 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1613784 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.epw
--rw-r--r--   0 runner    (1001) docker     (123)    29529 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1624547 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.epw
--rw-r--r--   0 runner    (1001) docker     (123)    29243 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1625209 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.epw
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 14:14:15.221474 sinergym-2.5.0/sinergym/envs/
--rw-r--r--   0 runner    (1001) docker     (123)       73 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/envs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    20725 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/envs/eplus_env.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 14:14:15.225474 sinergym-2.5.0/sinergym/simulators/
--rw-r--r--   0 runner    (1001) docker     (123)       78 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/simulators/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      768 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/simulators/base.py
--rw-r--r--   0 runner    (1001) docker     (123)    25211 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/simulators/eplus.py
--rw-r--r--   0 runner    (1001) docker     (123)     3686 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/simulators/eplus_alpha.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 14:14:15.225474 sinergym-2.5.0/sinergym/utils/
--rw-r--r--   0 runner    (1001) docker     (123)       86 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13969 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/utils/callbacks.py
--rw-r--r--   0 runner    (1001) docker     (123)    11122 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/utils/common.py
--rw-r--r--   0 runner    (1001) docker     (123)    39016 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/utils/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)     3815 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/utils/controllers.py
--rw-r--r--   0 runner    (1001) docker     (123)    10129 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/utils/env_checker.py
--rw-r--r--   0 runner    (1001) docker     (123)     5340 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/utils/evaluation.py
--rw-r--r--   0 runner    (1001) docker     (123)     5572 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/utils/gcloud.py
--rw-r--r--   0 runner    (1001) docker     (123)    12757 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/utils/logger.py
--rw-r--r--   0 runner    (1001) docker     (123)    11986 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/utils/rewards.py
--rw-r--r--   0 runner    (1001) docker     (123)    24284 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/utils/wrappers.py
--rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-01 14:14:14.000000 sinergym-2.5.0/sinergym/version.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-01 14:14:15.193473 sinergym-2.5.0/sinergym.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12180 2023-06-01 14:14:15.000000 sinergym-2.5.0/sinergym.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3093 2023-06-01 14:14:15.000000 sinergym-2.5.0/sinergym.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-01 14:14:15.000000 sinergym-2.5.0/sinergym.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      921 2023-06-01 14:14:15.000000 sinergym-2.5.0/sinergym.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-01 14:14:15.000000 sinergym-2.5.0/sinergym.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.202886 sinergym-2.5.1/
+-rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-06-28 09:24:36.000000 sinergym-2.5.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       87 2023-06-28 09:24:36.000000 sinergym-2.5.1/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)    12180 2023-06-28 09:24:39.202886 sinergym-2.5.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11272 2023-06-28 09:24:36.000000 sinergym-2.5.1/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-28 09:24:38.000000 sinergym-2.5.1/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-28 09:24:39.202886 sinergym-2.5.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2785 2023-06-28 09:24:38.000000 sinergym-2.5.1/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.178886 sinergym-2.5.1/sinergym/
+-rw-r--r--   0 runner    (1001) docker     (123)    95280 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.178886 sinergym-2.5.1/sinergym/config/
+-rw-r--r--   0 runner    (1001) docker     (123)      106 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/config/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36311 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/config/modeling.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.174886 sinergym-2.5.1/sinergym/data/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.178886 sinergym-2.5.1/sinergym/data/buildings/
+-rw-r--r--   0 runner    (1001) docker     (123)   167116 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/buildings/2ZoneDataCenterHVAC_wEconomizer.epJSON
+-rw-r--r--   0 runner    (1001) docker     (123)   153252 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/buildings/5ZoneAutoDXVAV.epJSON
+-rw-r--r--   0 runner    (1001) docker     (123)   595916 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/buildings/ASHRAE901_OfficeMedium_STD2019_Denver.epJSON
+-rw-r--r--   0 runner    (1001) docker     (123)   273893 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/buildings/ASHRAE901_Warehouse_STD2019_Denver.epJSON
+-rw-r--r--   0 runner    (1001) docker     (123)   522393 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/buildings/LrgOff_GridStorageScheduled.epJSON
+-rw-r--r--   0 runner    (1001) docker     (123)   251679 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/buildings/ShopWithPVandBattery.epJSON
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.178886 sinergym-2.5.1/sinergym/data/variables/
+-rw-r--r--   0 runner    (1001) docker     (123)    39571 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/variables/2ZoneDataCenterHVAC_wEconomizer.rdd
+-rw-r--r--   0 runner    (1001) docker     (123)    35724 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/variables/5ZoneAutoDXVAV.rdd
+-rw-r--r--   0 runner    (1001) docker     (123)    43088 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/variables/ASHRAE901_OfficeMedium_STD2019_Denver.rdd
+-rw-r--r--   0 runner    (1001) docker     (123)    40843 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/variables/ASHRAE901_Warehouse_STD2019_Denver.rdd
+-rw-r--r--   0 runner    (1001) docker     (123)    45556 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/variables/LrgOff_GridStorageScheduled.rdd
+-rw-r--r--   0 runner    (1001) docker     (123)    46370 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/variables/ShopWithPVandBattery.rdd
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.198886 sinergym-2.5.1/sinergym/data/weather/
+-rw-r--r--   0 runner    (1001) docker     (123)    28629 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1565086 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28503 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/COL_Bogota.802220_IWEC.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1550279 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/COL_Bogota.802220_IWEC.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28704 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/ESP_Granada.084190_SWEC.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1621761 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/ESP_Granada.084190_SWEC.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28716 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/FIN_Helsinki.029740_IWEC.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1553382 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/FIN_Helsinki.029740_IWEC.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28801 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1558629 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28740 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1558423 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28659 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/PRT_Lisboa.085360_INETI.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1601571 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/PRT_Lisboa.085360_INETI.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    29016 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1637298 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    29489 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1629153 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28793 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1639985 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    29614 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1613784 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    29529 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1624547 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    29243 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1625209 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.epw
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.202886 sinergym-2.5.1/sinergym/envs/
+-rw-r--r--   0 runner    (1001) docker     (123)       73 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/envs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21786 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/envs/eplus_env.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.202886 sinergym-2.5.1/sinergym/simulators/
+-rw-r--r--   0 runner    (1001) docker     (123)       78 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/simulators/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      768 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/simulators/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25211 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/simulators/eplus.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3686 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/simulators/eplus_alpha.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.202886 sinergym-2.5.1/sinergym/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)       86 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13969 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/callbacks.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11122 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)    39016 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3815 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/controllers.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10129 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/env_checker.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5340 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/evaluation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5572 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/gcloud.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12757 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11986 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/rewards.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24284 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/wrappers.py
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/version.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.178886 sinergym-2.5.1/sinergym.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12180 2023-06-28 09:24:39.000000 sinergym-2.5.1/sinergym.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3093 2023-06-28 09:24:39.000000 sinergym-2.5.1/sinergym.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 09:24:39.000000 sinergym-2.5.1/sinergym.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      903 2023-06-28 09:24:39.000000 sinergym-2.5.1/sinergym.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 09:24:39.000000 sinergym-2.5.1/sinergym.egg-info/top_level.txt
```

### Comparing `sinergym-2.5.0/LICENSE` & `sinergym-2.5.1/LICENSE`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/PKG-INFO` & `sinergym-2.5.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sinergym
-Version: 2.5.0
+Version: 2.5.1
 Summary: The goal of sinergym is to create an environment following OpenAI Gym interface for wrapping simulation engines for building control using deep reinforcement learning.
 Home-page: https://github.com/ugr-sail/sinergym
 Author: J. Jiménez, J. Gómez, M. Molina, A. Manjavacas, A. Campoy
 Author-email: alejandroac79@gmail.com
 License: MIT
 Keywords: control reinforcement-learning buildings reinforcement-learning-environments
 Platform: UNKNOWN
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: sinergym Version: 2.5.0 Summary: The goal of
+Metadata-Version: 2.1 Name: sinergym Version: 2.5.1 Summary: The goal of
 sinergym is to create an environment following OpenAI Gym interface for
 wrapping simulation engines for building control using deep reinforcement
 learning. Home-page: https://github.com/ugr-sail/sinergym Author: J. JimÃ©nez,
 J. GÃ³mez, M. Molina, A. Manjavacas, A. Campoy Author-email:
 alejandroac79@gmail.com License: MIT Keywords: control reinforcement-learning
 buildings reinforcement-learning-environments Platform: UNKNOWN Classifier:
 Development Status :: 5 - Production/Stable Classifier: Programming Language ::
```

### Comparing `sinergym-2.5.0/README.md` & `sinergym-2.5.1/README.md`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/setup.py` & `sinergym-2.5.1/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,15 +20,15 @@
       keywords='control reinforcement-learning buildings reinforcement-learning-environments',
       install_requires=reqs,
       include_package_data=True,
       extras_require={
           'extras': [
               'matplotlib',  # visualization
               # DRL with pytorch
-              'stable-baselines3==2.0.0a5',
+              'stable-baselines3',
               'wandb',
               'pytest',
               'pytest-cov',
               'pytest-xdist',  # Unit test repository
               'sphinx',  # documentation
               'sphinx-rtd-theme',  # documentation theme
               'sphinxcontrib-spelling',  # documentation spelling
@@ -46,15 +46,15 @@
           ],
           'test': [
               'pytest',
               'pytest-cov',
               'pytest-xdist',
           ],
           'DRL': [
-              'stable-baselines3==2.0.0a5',
+              'stable-baselines3',
               'wandb'
           ],
           'doc': [
               'sphinx',
               'sphinx-rtd-theme',
               'sphinxcontrib-spelling',
               'sphinxcontrib-jquery',
```

### Comparing `sinergym-2.5.0/sinergym/__init__.py` & `sinergym-2.5.1/sinergym/__init__.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/config/modeling.py` & `sinergym-2.5.1/sinergym/config/modeling.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/buildings/2ZoneDataCenterHVAC_wEconomizer.epJSON` & `sinergym-2.5.1/sinergym/data/buildings/2ZoneDataCenterHVAC_wEconomizer.epJSON`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/buildings/5ZoneAutoDXVAV.epJSON` & `sinergym-2.5.1/sinergym/data/buildings/5ZoneAutoDXVAV.epJSON`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/buildings/ASHRAE901_OfficeMedium_STD2019_Denver.epJSON` & `sinergym-2.5.1/sinergym/data/buildings/ASHRAE901_OfficeMedium_STD2019_Denver.epJSON`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/buildings/ASHRAE901_Warehouse_STD2019_Denver.epJSON` & `sinergym-2.5.1/sinergym/data/buildings/ASHRAE901_Warehouse_STD2019_Denver.epJSON`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/buildings/LrgOff_GridStorageScheduled.epJSON` & `sinergym-2.5.1/sinergym/data/buildings/LrgOff_GridStorageScheduled.epJSON`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/buildings/ShopWithPVandBattery.epJSON` & `sinergym-2.5.1/sinergym/data/buildings/ShopWithPVandBattery.epJSON`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/variables/2ZoneDataCenterHVAC_wEconomizer.rdd` & `sinergym-2.5.1/sinergym/data/variables/2ZoneDataCenterHVAC_wEconomizer.rdd`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/variables/5ZoneAutoDXVAV.rdd` & `sinergym-2.5.1/sinergym/data/variables/5ZoneAutoDXVAV.rdd`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/variables/ASHRAE901_OfficeMedium_STD2019_Denver.rdd` & `sinergym-2.5.1/sinergym/data/variables/ASHRAE901_OfficeMedium_STD2019_Denver.rdd`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/variables/ASHRAE901_Warehouse_STD2019_Denver.rdd` & `sinergym-2.5.1/sinergym/data/variables/ASHRAE901_Warehouse_STD2019_Denver.rdd`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/variables/LrgOff_GridStorageScheduled.rdd` & `sinergym-2.5.1/sinergym/data/variables/LrgOff_GridStorageScheduled.rdd`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/variables/ShopWithPVandBattery.rdd` & `sinergym-2.5.1/sinergym/data/variables/ShopWithPVandBattery.rdd`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.ddy` & `sinergym-2.5.1/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.epw` & `sinergym-2.5.1/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/COL_Bogota.802220_IWEC.ddy` & `sinergym-2.5.1/sinergym/data/weather/COL_Bogota.802220_IWEC.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/COL_Bogota.802220_IWEC.epw` & `sinergym-2.5.1/sinergym/data/weather/COL_Bogota.802220_IWEC.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/ESP_Granada.084190_SWEC.ddy` & `sinergym-2.5.1/sinergym/data/weather/ESP_Granada.084190_SWEC.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/ESP_Granada.084190_SWEC.epw` & `sinergym-2.5.1/sinergym/data/weather/ESP_Granada.084190_SWEC.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/FIN_Helsinki.029740_IWEC.ddy` & `sinergym-2.5.1/sinergym/data/weather/FIN_Helsinki.029740_IWEC.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/FIN_Helsinki.029740_IWEC.epw` & `sinergym-2.5.1/sinergym/data/weather/FIN_Helsinki.029740_IWEC.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.ddy` & `sinergym-2.5.1/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.epw` & `sinergym-2.5.1/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.ddy` & `sinergym-2.5.1/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.epw` & `sinergym-2.5.1/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/PRT_Lisboa.085360_INETI.ddy` & `sinergym-2.5.1/sinergym/data/weather/PRT_Lisboa.085360_INETI.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/PRT_Lisboa.085360_INETI.epw` & `sinergym-2.5.1/sinergym/data/weather/PRT_Lisboa.085360_INETI.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.ddy` & `sinergym-2.5.1/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.epw` & `sinergym-2.5.1/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.ddy` & `sinergym-2.5.1/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.epw` & `sinergym-2.5.1/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.ddy` & `sinergym-2.5.1/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.epw` & `sinergym-2.5.1/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.ddy` & `sinergym-2.5.1/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.epw` & `sinergym-2.5.1/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.ddy` & `sinergym-2.5.1/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.epw` & `sinergym-2.5.1/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.ddy` & `sinergym-2.5.1/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.epw` & `sinergym-2.5.1/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/envs/eplus_env.py` & `sinergym-2.5.1/sinergym/envs/eplus_env.py`

 * *Files 21% similar despite different names*

```diff
@@ -29,14 +29,15 @@
         observation_space: gym.spaces.Box = gym.spaces.Box(
             low=-5e6, high=5e6, shape=(4,), dtype=np.float32),
         observation_variables: List[str] = [],
         action_space: Union[gym.spaces.Box, gym.spaces.Discrete] = gym.spaces.Box(
             low=0, high=0, shape=(0,), dtype=np.float32),
         action_variables: List[str] = [],
         action_mapping: Dict[int, Tuple[float, ...]] = {},
+        flag_normalization: bool = True,
         weather_variability: Optional[Tuple[float]] = None,
         reward: Any = LinearReward,
         reward_kwargs: Optional[Dict[str, Any]] = {},
         act_repeat: int = 1,
         max_ep_data_store_num: int = 10,
         action_definition: Optional[Dict[str, Any]] = None,
         env_name: str = 'eplus-env-v1',
@@ -48,14 +49,15 @@
             building_file (str): Name of the JSON file with the building definition.
             weather_file (Union[str,List[str]]): Name of the EPW file for weather conditions. It can be specified a list of weathers files in order to sample a weather in each episode randomly.
             observation_space (gym.spaces.Box, optional): Gym Observation Space definition. Defaults to an empty observation_space (no control).
             observation_variables (List[str], optional): List with variables names in building. Defaults to an empty observation variables (no control).
             action_space (Union[gym.spaces.Box, gym.spaces.Discrete], optional): Gym Action Space definition. Defaults to an empty action_space (no control).
             action_variables (List[str],optional): Action variables to be controlled in building, if that actions names have not been configured manually in building, you should configure or use action_definition. Default to empty List.
             action_mapping (Dict[int, Tuple[float, ...]], optional): Action mapping list for discrete actions spaces only. Defaults to empty list.
+            flag_normalization (bool): Flag indicating if action space must be normalized to [-1,1]. This flag only take effect in continuous environments. Default to true.
             weather_variability (Optional[Tuple[float]], optional): Tuple with sigma, mu and tao of the Ornstein-Uhlenbeck process to be applied to weather data. Defaults to None.
             reward (Any, optional): Reward function instance used for agent feedback. Defaults to LinearReward.
             reward_kwargs (Optional[Dict[str, Any]], optional): Parameters to be passed to the reward function. Defaults to empty dict.
             act_repeat (int, optional): Number of timesteps that an action is repeated in the simulator, regardless of the actions it receives during that repetition interval.
             max_ep_data_store_num (int, optional): Number of last sub-folders (one for each episode) generated during execution on the simulation.
             action_definition (Optional[Dict[str, Any]): Dict with building components to being controlled by Sinergym automatically if it is supported. Default value to None.
             env_name (str, optional): Env name used for working directory generation. Defaults to eplus-env-v1.
@@ -144,25 +146,36 @@
 
         # Discrete
         if self.flag_discrete:
             self.action_mapping = action_mapping
             self._action_space = action_space
         # Continuous
         else:
-            # Defining action values setpoints (one per value)
-            self.setpoints_space = action_space
-
-            self._action_space = gym.spaces.Box(
+            # Defining the normalized space (always [-1,1])
+            self.normalized_space = gym.spaces.Box(
                 # continuous_action_def[2] --> shape
                 low=np.array(
                     np.repeat(-1, action_space.shape[0]), dtype=np.float32),
                 high=np.array(
                     np.repeat(1, action_space.shape[0]), dtype=np.float32),
                 dtype=action_space.dtype
             )
+            # Defining the real space (defined by the user in environment
+            # constructor)
+            self.real_space = action_space
+
+            # Determine if action is normalized or not using flag
+            self.flag_normalization = flag_normalization
+
+            # Depending on the normalized flag, action space will be the normalized space
+            # or the real space.
+            if self.flag_normalization:
+                self._action_space = self.normalized_space
+            else:
+                self._action_space = self.real_space
 
         # ---------------------------------------------------------------------------- #
         #                                    Reward                                    #
         # ---------------------------------------------------------------------------- #
         self.reward_fn = reward(**reward_kwargs)
 
         # ---------------------------------------------------------------------------- #
@@ -219,15 +232,19 @@
         Args:
             action (Union[int, float, np.integer, np.ndarray, List[Any], Tuple[Any]]): Action selected by the agent.
 
         Returns:
             Tuple[np.ndarray, float, bool, Dict[str, Any]]: Observation for next timestep, reward obtained, Whether the episode has ended or not, Whether episode has been truncated or not, and a dictionary with extra information
         """
 
-        # Get action
+        # Check if action is correct for the current action space
+        assert self._action_space.contains(
+            action), 'Step: The action {} is not correct for the Action Space {}'.format(action, self._action_space)
+
+        # Get real action (action --> action_)
         action_ = self._get_action(action)
         # Send action to the simulator
         self.simulator.logger_main.debug(action_)
         # Execute action in simulation
         obs, terminated, truncated, info = self.simulator.step(action_)
         obs_dict = dict(zip(self.original_obs, obs))
 
@@ -268,107 +285,110 @@
                                                 float,
                                                 np.integer,
                                                 np.ndarray,
                                                 List[Any],
                                                 Tuple[Any]]:
         """Transform the action for sending it to the simulator."""
 
-        # Get action depending on flag_discrete
+        # Discrete
         if self.flag_discrete:
             # Index for action_mapping
-            if np.issubdtype(type(action), np.integer):
-                if isinstance(action, int):
-                    setpoints = self.action_mapping[action]
-                else:
-                    setpoints = self.action_mapping[action.item()]
-            # Manual action
-            elif isinstance(action, tuple) or isinstance(action, list):
-                # stable-baselines DQN bug prevention
-                if len(action) == 1:
-                    setpoints = self.action_mapping[action[0]]
-                else:
-                    setpoints = action
-            elif isinstance(action, np.ndarray):
-                setpoints = self.action_mapping[action.item()]
-            else:
-                raise RuntimeError(
-                    'action type not supported by Sinergym environment')
-            action_ = list(setpoints)
+            # Some SB3 algorithms returns array(int) in their predictions
+            if isinstance(action, np.ndarray):
+                action = int(action.item())
+            action_ = list(self.action_mapping[action])
+
+        # Continuous
         else:
-            # transform action to setpoints simulation
-            action_ = self._setpoints_transform(action)
+            # Transform action to real space simulation if normalized flag is
+            # true
+            action_ = self._action_transform(
+                action) if self.flag_normalization else action
 
         return action_
 
-    def _setpoints_transform(self,
-                             action: Union[int,
-                                           float,
-                                           np.integer,
-                                           np.ndarray,
-                                           List[Any],
-                                           Tuple[Any]]) -> Union[int,
-                                                                 float,
-                                                                 np.integer,
-                                                                 np.ndarray,
-                                                                 List[Any],
-                                                                 Tuple[Any]]:
+    def _action_transform(self,
+                          action: Union[int,
+                                        float,
+                                        np.integer,
+                                        np.ndarray,
+                                        List[Any],
+                                        Tuple[Any]]) -> Union[int,
+                                                              float,
+                                                              np.integer,
+                                                              np.ndarray,
+                                                              List[Any],
+                                                              Tuple[Any]]:
         """ This method transforms an action defined in gym (-1,1 in all continuous environment) action space to simulation real action space.
 
         Args:
             action (Union[int, float, np.integer, np.ndarray, List[Any], Tuple[Any]]): Action received in environment
 
         Returns:
             Union[int, float, np.integer, np.ndarray, List[Any], Tuple[Any]]: Action transformed in simulator action space.
         """
         action_ = []
 
         for i, value in enumerate(action):
-            if self._action_space.low[i] <= value <= self._action_space.high[i]:
-                a_max_min = self._action_space.high[i] - \
-                    self._action_space.low[i]
-                sp_max_min = self.setpoints_space.high[i] - \
-                    self.setpoints_space.low[i]
-
-                action_.append(
-                    self.setpoints_space.low[i] +
-                    (
-                        value -
-                        self._action_space.low[i]) *
-                    sp_max_min /
-                    a_max_min)
-            else:
-                # If action is outer action_space already, it don't need
-                # transformation
-                action_.append(value)
+            a_max_min = self._action_space.high[i] - \
+                self._action_space.low[i]
+            sp_max_min = self.real_space.high[i] - \
+                self.real_space.low[i]
+
+            action_.append(
+                self.real_space.low[i] +
+                (
+                    value -
+                    self._action_space.low[i]) *
+                sp_max_min /
+                a_max_min)
 
         return action_
 
+    def update_flag_normalization(self, value: bool) -> None:
+        """Update the normalized flag in continuous environments and update the action space
+
+        Args:
+            value (bool): New flag_normalization attribute value
+        """
+
+        self.flag_normalization = value
+        self._action_space = self.normalized_space if value else self.real_space
+
     def _check_eplus_env(self) -> None:
         """This method checks that environment definition is correct and it has not inconsistencies.
         """
         # OBSERVATION
         assert len(self.variables['observation']) == self._observation_space.shape[
             0], 'Observation space has not the same length than variable names specified.'
 
         # ACTION
         if self.flag_discrete:
             assert hasattr(
                 self, 'action_mapping'), 'Discrete environment: action mapping should have been defined.'
             assert not hasattr(
-                self, 'setpoints_space'), 'Discrete environment: setpoints space should not have been defined.'
+                self, 'real_space'), 'Discrete environment: real_space should not have been defined.'
+            assert not hasattr(
+                self, 'normalized_space'), 'Discrete environment: normalized_space should not have been defined.'
+            assert not hasattr(
+                self, 'flag_normalization'), 'Discrete environment: flag_normalization should not have been defined.'
             assert self._action_space.n == len(
                 self.action_mapping), 'Discrete environment: The length of the action_mapping must match the dimension of the discrete action space.'
             for values in self.action_mapping.values():
                 assert len(values) == len(
                     self.variables['action']), 'Discrete environment: Action mapping tuples values must have the same length than action variables specified.'
         else:
             assert len(self.variables['action']) == self._action_space.shape[
                 0], 'Action space shape must match with number of action variables specified.'
             assert hasattr(
-                self, 'setpoints_space'), 'Continuous environment: setpoints_space attribute should have been defined.'
+                self, 'flag_normalization'), 'Continuous environment: flag_normalization attribute should have been defined.'
+            assert hasattr(
+                self, 'normalized_space'), 'Continuous environment: normalized_space attribute should have been defined.'
+            assert hasattr(
+                self, 'real_space'), 'Continuous environment: real_space attribute should have been defined.'
             assert not hasattr(
                 self, 'action_mapping'), 'Continuous environment: action mapping should not have been defined.'
             assert len(self._action_space.low) == len(self.variables['action']) and len(self._action_space.high) == len(
                 self.variables['action']), 'Continuous environment: low and high values action space definition should have the same number of values than action variables.'
 
     def get_schedulers(
             self, path: Optional[str] = None) -> Dict[str, Dict[str, Union[str, Dict[str, str]]]]:
```

### Comparing `sinergym-2.5.0/sinergym/simulators/base.py` & `sinergym-2.5.1/sinergym/simulators/base.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/simulators/eplus.py` & `sinergym-2.5.1/sinergym/simulators/eplus.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/simulators/eplus_alpha.py` & `sinergym-2.5.1/sinergym/simulators/eplus_alpha.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/utils/callbacks.py` & `sinergym-2.5.1/sinergym/utils/callbacks.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/utils/common.py` & `sinergym-2.5.1/sinergym/utils/common.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/utils/constants.py` & `sinergym-2.5.1/sinergym/utils/constants.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/utils/controllers.py` & `sinergym-2.5.1/sinergym/utils/controllers.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/utils/env_checker.py` & `sinergym-2.5.1/sinergym/utils/env_checker.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/utils/evaluation.py` & `sinergym-2.5.1/sinergym/utils/evaluation.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/utils/gcloud.py` & `sinergym-2.5.1/sinergym/utils/gcloud.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/utils/logger.py` & `sinergym-2.5.1/sinergym/utils/logger.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/utils/rewards.py` & `sinergym-2.5.1/sinergym/utils/rewards.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym/utils/wrappers.py` & `sinergym-2.5.1/sinergym/utils/wrappers.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym.egg-info/PKG-INFO` & `sinergym-2.5.1/sinergym.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sinergym
-Version: 2.5.0
+Version: 2.5.1
 Summary: The goal of sinergym is to create an environment following OpenAI Gym interface for wrapping simulation engines for building control using deep reinforcement learning.
 Home-page: https://github.com/ugr-sail/sinergym
 Author: J. Jiménez, J. Gómez, M. Molina, A. Manjavacas, A. Campoy
 Author-email: alejandroac79@gmail.com
 License: MIT
 Keywords: control reinforcement-learning buildings reinforcement-learning-environments
 Platform: UNKNOWN
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: sinergym Version: 2.5.0 Summary: The goal of
+Metadata-Version: 2.1 Name: sinergym Version: 2.5.1 Summary: The goal of
 sinergym is to create an environment following OpenAI Gym interface for
 wrapping simulation engines for building control using deep reinforcement
 learning. Home-page: https://github.com/ugr-sail/sinergym Author: J. JimÃ©nez,
 J. GÃ³mez, M. Molina, A. Manjavacas, A. Campoy Author-email:
 alejandroac79@gmail.com License: MIT Keywords: control reinforcement-learning
 buildings reinforcement-learning-environments Platform: UNKNOWN Classifier:
 Development Status :: 5 - Production/Stable Classifier: Programming Language ::
```

### Comparing `sinergym-2.5.0/sinergym.egg-info/SOURCES.txt` & `sinergym-2.5.1/sinergym.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.0/sinergym.egg-info/requires.txt` & `sinergym-2.5.1/sinergym.egg-info/requires.txt`

 * *Files 9% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 pandas
 pipdeptree
 pytype
 twine
 xlsxwriter
 
 [DRL]
-stable-baselines3==2.0.0a5
+stable-baselines3
 wandb
 
 [doc]
 IPython
 nbsphinx
 nbsphinx_link
 pyenchant
@@ -40,15 +40,15 @@
 pytest-xdist
 sphinx
 sphinx-multitoc-numbering
 sphinx-multiversion@ git+https://github.com/Holzhaus/sphinx-multiversion#egg=sphinx-multiversion
 sphinx-rtd-theme
 sphinxcontrib-jquery
 sphinxcontrib-spelling
-stable-baselines3==2.0.0a5
+stable-baselines3
 wandb
 
 [gcloud]
 google-api-python-client==2.58.0
 google-cloud-storage==2.5.0
 oauth2client==4.1.3
```

