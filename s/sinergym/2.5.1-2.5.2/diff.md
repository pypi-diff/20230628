# Comparing `tmp/sinergym-2.5.1.tar.gz` & `tmp/sinergym-2.5.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sinergym-2.5.1.tar", last modified: Wed Jun 28 09:24:39 2023, max compression
+gzip compressed data, was "sinergym-2.5.2.tar", last modified: Wed Jun 28 15:21:54 2023, max compression
```

## Comparing `sinergym-2.5.1.tar` & `sinergym-2.5.2.tar`

### file list

```diff
@@ -1,82 +1,82 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.202886 sinergym-2.5.1/
--rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-06-28 09:24:36.000000 sinergym-2.5.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)       87 2023-06-28 09:24:36.000000 sinergym-2.5.1/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)    12180 2023-06-28 09:24:39.202886 sinergym-2.5.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    11272 2023-06-28 09:24:36.000000 sinergym-2.5.1/README.md
--rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-28 09:24:38.000000 sinergym-2.5.1/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-28 09:24:39.202886 sinergym-2.5.1/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     2785 2023-06-28 09:24:38.000000 sinergym-2.5.1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.178886 sinergym-2.5.1/sinergym/
--rw-r--r--   0 runner    (1001) docker     (123)    95280 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.178886 sinergym-2.5.1/sinergym/config/
--rw-r--r--   0 runner    (1001) docker     (123)      106 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/config/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    36311 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/config/modeling.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.174886 sinergym-2.5.1/sinergym/data/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.178886 sinergym-2.5.1/sinergym/data/buildings/
--rw-r--r--   0 runner    (1001) docker     (123)   167116 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/buildings/2ZoneDataCenterHVAC_wEconomizer.epJSON
--rw-r--r--   0 runner    (1001) docker     (123)   153252 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/buildings/5ZoneAutoDXVAV.epJSON
--rw-r--r--   0 runner    (1001) docker     (123)   595916 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/buildings/ASHRAE901_OfficeMedium_STD2019_Denver.epJSON
--rw-r--r--   0 runner    (1001) docker     (123)   273893 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/buildings/ASHRAE901_Warehouse_STD2019_Denver.epJSON
--rw-r--r--   0 runner    (1001) docker     (123)   522393 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/buildings/LrgOff_GridStorageScheduled.epJSON
--rw-r--r--   0 runner    (1001) docker     (123)   251679 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/buildings/ShopWithPVandBattery.epJSON
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.178886 sinergym-2.5.1/sinergym/data/variables/
--rw-r--r--   0 runner    (1001) docker     (123)    39571 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/variables/2ZoneDataCenterHVAC_wEconomizer.rdd
--rw-r--r--   0 runner    (1001) docker     (123)    35724 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/variables/5ZoneAutoDXVAV.rdd
--rw-r--r--   0 runner    (1001) docker     (123)    43088 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/variables/ASHRAE901_OfficeMedium_STD2019_Denver.rdd
--rw-r--r--   0 runner    (1001) docker     (123)    40843 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/variables/ASHRAE901_Warehouse_STD2019_Denver.rdd
--rw-r--r--   0 runner    (1001) docker     (123)    45556 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/variables/LrgOff_GridStorageScheduled.rdd
--rw-r--r--   0 runner    (1001) docker     (123)    46370 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/variables/ShopWithPVandBattery.rdd
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.198886 sinergym-2.5.1/sinergym/data/weather/
--rw-r--r--   0 runner    (1001) docker     (123)    28629 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1565086 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28503 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/COL_Bogota.802220_IWEC.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1550279 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/COL_Bogota.802220_IWEC.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28704 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/ESP_Granada.084190_SWEC.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1621761 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/ESP_Granada.084190_SWEC.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28716 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/FIN_Helsinki.029740_IWEC.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1553382 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/FIN_Helsinki.029740_IWEC.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28801 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1558629 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28740 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1558423 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28659 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/PRT_Lisboa.085360_INETI.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1601571 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/PRT_Lisboa.085360_INETI.epw
--rw-r--r--   0 runner    (1001) docker     (123)    29016 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1637298 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.epw
--rw-r--r--   0 runner    (1001) docker     (123)    29489 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1629153 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.epw
--rw-r--r--   0 runner    (1001) docker     (123)    28793 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1639985 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.epw
--rw-r--r--   0 runner    (1001) docker     (123)    29614 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1613784 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.epw
--rw-r--r--   0 runner    (1001) docker     (123)    29529 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1624547 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.epw
--rw-r--r--   0 runner    (1001) docker     (123)    29243 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.ddy
--rw-r--r--   0 runner    (1001) docker     (123)  1625209 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.epw
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.202886 sinergym-2.5.1/sinergym/envs/
--rw-r--r--   0 runner    (1001) docker     (123)       73 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/envs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    21786 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/envs/eplus_env.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.202886 sinergym-2.5.1/sinergym/simulators/
--rw-r--r--   0 runner    (1001) docker     (123)       78 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/simulators/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      768 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/simulators/base.py
--rw-r--r--   0 runner    (1001) docker     (123)    25211 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/simulators/eplus.py
--rw-r--r--   0 runner    (1001) docker     (123)     3686 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/simulators/eplus_alpha.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.202886 sinergym-2.5.1/sinergym/utils/
--rw-r--r--   0 runner    (1001) docker     (123)       86 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    13969 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/callbacks.py
--rw-r--r--   0 runner    (1001) docker     (123)    11122 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/common.py
--rw-r--r--   0 runner    (1001) docker     (123)    39016 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/constants.py
--rw-r--r--   0 runner    (1001) docker     (123)     3815 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/controllers.py
--rw-r--r--   0 runner    (1001) docker     (123)    10129 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/env_checker.py
--rw-r--r--   0 runner    (1001) docker     (123)     5340 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/evaluation.py
--rw-r--r--   0 runner    (1001) docker     (123)     5572 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/gcloud.py
--rw-r--r--   0 runner    (1001) docker     (123)    12757 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/logger.py
--rw-r--r--   0 runner    (1001) docker     (123)    11986 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/rewards.py
--rw-r--r--   0 runner    (1001) docker     (123)    24284 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/utils/wrappers.py
--rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 09:24:38.000000 sinergym-2.5.1/sinergym/version.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:24:39.178886 sinergym-2.5.1/sinergym.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    12180 2023-06-28 09:24:39.000000 sinergym-2.5.1/sinergym.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3093 2023-06-28 09:24:39.000000 sinergym-2.5.1/sinergym.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 09:24:39.000000 sinergym-2.5.1/sinergym.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      903 2023-06-28 09:24:39.000000 sinergym-2.5.1/sinergym.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 09:24:39.000000 sinergym-2.5.1/sinergym.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:54.786263 sinergym-2.5.2/
+-rw-r--r--   0 runner    (1001) docker     (123)     1072 2023-06-28 15:21:51.000000 sinergym-2.5.2/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)       87 2023-06-28 15:21:51.000000 sinergym-2.5.2/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)    12180 2023-06-28 15:21:54.786263 sinergym-2.5.2/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    11272 2023-06-28 15:21:51.000000 sinergym-2.5.2/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-28 15:21:54.000000 sinergym-2.5.2/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      410 2023-06-28 15:21:54.790263 sinergym-2.5.2/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     2785 2023-06-28 15:21:54.000000 sinergym-2.5.2/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:54.762263 sinergym-2.5.2/sinergym/
+-rw-r--r--   0 runner    (1001) docker     (123)    95280 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:54.762263 sinergym-2.5.2/sinergym/config/
+-rw-r--r--   0 runner    (1001) docker     (123)      106 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/config/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    36311 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/config/modeling.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:54.758263 sinergym-2.5.2/sinergym/data/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:54.762263 sinergym-2.5.2/sinergym/data/buildings/
+-rw-r--r--   0 runner    (1001) docker     (123)   167116 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/buildings/2ZoneDataCenterHVAC_wEconomizer.epJSON
+-rw-r--r--   0 runner    (1001) docker     (123)   153252 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/buildings/5ZoneAutoDXVAV.epJSON
+-rw-r--r--   0 runner    (1001) docker     (123)   595916 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/buildings/ASHRAE901_OfficeMedium_STD2019_Denver.epJSON
+-rw-r--r--   0 runner    (1001) docker     (123)   273893 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/buildings/ASHRAE901_Warehouse_STD2019_Denver.epJSON
+-rw-r--r--   0 runner    (1001) docker     (123)   522393 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/buildings/LrgOff_GridStorageScheduled.epJSON
+-rw-r--r--   0 runner    (1001) docker     (123)   251679 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/buildings/ShopWithPVandBattery.epJSON
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:54.766263 sinergym-2.5.2/sinergym/data/variables/
+-rw-r--r--   0 runner    (1001) docker     (123)    39571 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/variables/2ZoneDataCenterHVAC_wEconomizer.rdd
+-rw-r--r--   0 runner    (1001) docker     (123)    35724 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/variables/5ZoneAutoDXVAV.rdd
+-rw-r--r--   0 runner    (1001) docker     (123)    43088 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/variables/ASHRAE901_OfficeMedium_STD2019_Denver.rdd
+-rw-r--r--   0 runner    (1001) docker     (123)    40843 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/variables/ASHRAE901_Warehouse_STD2019_Denver.rdd
+-rw-r--r--   0 runner    (1001) docker     (123)    45556 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/variables/LrgOff_GridStorageScheduled.rdd
+-rw-r--r--   0 runner    (1001) docker     (123)    46370 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/variables/ShopWithPVandBattery.rdd
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:54.786263 sinergym-2.5.2/sinergym/data/weather/
+-rw-r--r--   0 runner    (1001) docker     (123)    28629 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1565086 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28503 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/COL_Bogota.802220_IWEC.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1550279 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/COL_Bogota.802220_IWEC.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28704 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/ESP_Granada.084190_SWEC.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1621761 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/ESP_Granada.084190_SWEC.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28716 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/FIN_Helsinki.029740_IWEC.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1553382 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/FIN_Helsinki.029740_IWEC.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28801 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1558629 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28740 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1558423 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28659 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/PRT_Lisboa.085360_INETI.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1601571 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/PRT_Lisboa.085360_INETI.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    29016 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1637298 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    29489 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1629153 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    28793 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1639985 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    29614 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1613784 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    29529 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1624547 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.epw
+-rw-r--r--   0 runner    (1001) docker     (123)    29243 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.ddy
+-rw-r--r--   0 runner    (1001) docker     (123)  1625209 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.epw
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:54.786263 sinergym-2.5.2/sinergym/envs/
+-rw-r--r--   0 runner    (1001) docker     (123)       73 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/envs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    21786 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/envs/eplus_env.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:54.786263 sinergym-2.5.2/sinergym/simulators/
+-rw-r--r--   0 runner    (1001) docker     (123)       78 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/simulators/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      768 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/simulators/base.py
+-rw-r--r--   0 runner    (1001) docker     (123)    25211 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/simulators/eplus.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3686 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/simulators/eplus_alpha.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:54.786263 sinergym-2.5.2/sinergym/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)       86 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    13969 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/utils/callbacks.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11122 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/utils/common.py
+-rw-r--r--   0 runner    (1001) docker     (123)    39016 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/utils/constants.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3815 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/utils/controllers.py
+-rw-r--r--   0 runner    (1001) docker     (123)    10129 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/utils/env_checker.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5340 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/utils/evaluation.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5572 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/utils/gcloud.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12757 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/utils/logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11986 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/utils/rewards.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24377 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/utils/wrappers.py
+-rw-r--r--   0 runner    (1001) docker     (123)        6 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym/version.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:21:54.762263 sinergym-2.5.2/sinergym.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    12180 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3093 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      903 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 15:21:54.000000 sinergym-2.5.2/sinergym.egg-info/top_level.txt
```

### Comparing `sinergym-2.5.1/LICENSE` & `sinergym-2.5.2/LICENSE`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/PKG-INFO` & `sinergym-2.5.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sinergym
-Version: 2.5.1
+Version: 2.5.2
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
-Metadata-Version: 2.1 Name: sinergym Version: 2.5.1 Summary: The goal of
+Metadata-Version: 2.1 Name: sinergym Version: 2.5.2 Summary: The goal of
 sinergym is to create an environment following OpenAI Gym interface for
 wrapping simulation engines for building control using deep reinforcement
 learning. Home-page: https://github.com/ugr-sail/sinergym Author: J. JimÃ©nez,
 J. GÃ³mez, M. Molina, A. Manjavacas, A. Campoy Author-email:
 alejandroac79@gmail.com License: MIT Keywords: control reinforcement-learning
 buildings reinforcement-learning-environments Platform: UNKNOWN Classifier:
 Development Status :: 5 - Production/Stable Classifier: Programming Language ::
```

### Comparing `sinergym-2.5.1/README.md` & `sinergym-2.5.2/README.md`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/setup.py` & `sinergym-2.5.2/setup.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/__init__.py` & `sinergym-2.5.2/sinergym/__init__.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/config/modeling.py` & `sinergym-2.5.2/sinergym/config/modeling.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/buildings/2ZoneDataCenterHVAC_wEconomizer.epJSON` & `sinergym-2.5.2/sinergym/data/buildings/2ZoneDataCenterHVAC_wEconomizer.epJSON`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/buildings/5ZoneAutoDXVAV.epJSON` & `sinergym-2.5.2/sinergym/data/buildings/5ZoneAutoDXVAV.epJSON`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/buildings/ASHRAE901_OfficeMedium_STD2019_Denver.epJSON` & `sinergym-2.5.2/sinergym/data/buildings/ASHRAE901_OfficeMedium_STD2019_Denver.epJSON`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/buildings/ASHRAE901_Warehouse_STD2019_Denver.epJSON` & `sinergym-2.5.2/sinergym/data/buildings/ASHRAE901_Warehouse_STD2019_Denver.epJSON`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/buildings/LrgOff_GridStorageScheduled.epJSON` & `sinergym-2.5.2/sinergym/data/buildings/LrgOff_GridStorageScheduled.epJSON`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/buildings/ShopWithPVandBattery.epJSON` & `sinergym-2.5.2/sinergym/data/buildings/ShopWithPVandBattery.epJSON`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/variables/2ZoneDataCenterHVAC_wEconomizer.rdd` & `sinergym-2.5.2/sinergym/data/variables/2ZoneDataCenterHVAC_wEconomizer.rdd`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/variables/5ZoneAutoDXVAV.rdd` & `sinergym-2.5.2/sinergym/data/variables/5ZoneAutoDXVAV.rdd`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/variables/ASHRAE901_OfficeMedium_STD2019_Denver.rdd` & `sinergym-2.5.2/sinergym/data/variables/ASHRAE901_OfficeMedium_STD2019_Denver.rdd`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/variables/ASHRAE901_Warehouse_STD2019_Denver.rdd` & `sinergym-2.5.2/sinergym/data/variables/ASHRAE901_Warehouse_STD2019_Denver.rdd`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/variables/LrgOff_GridStorageScheduled.rdd` & `sinergym-2.5.2/sinergym/data/variables/LrgOff_GridStorageScheduled.rdd`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/variables/ShopWithPVandBattery.rdd` & `sinergym-2.5.2/sinergym/data/variables/ShopWithPVandBattery.rdd`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.ddy` & `sinergym-2.5.2/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.epw` & `sinergym-2.5.2/sinergym/data/weather/AUS_NSW.Sydney.947670_IWEC.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/COL_Bogota.802220_IWEC.ddy` & `sinergym-2.5.2/sinergym/data/weather/COL_Bogota.802220_IWEC.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/COL_Bogota.802220_IWEC.epw` & `sinergym-2.5.2/sinergym/data/weather/COL_Bogota.802220_IWEC.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/ESP_Granada.084190_SWEC.ddy` & `sinergym-2.5.2/sinergym/data/weather/ESP_Granada.084190_SWEC.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/ESP_Granada.084190_SWEC.epw` & `sinergym-2.5.2/sinergym/data/weather/ESP_Granada.084190_SWEC.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/FIN_Helsinki.029740_IWEC.ddy` & `sinergym-2.5.2/sinergym/data/weather/FIN_Helsinki.029740_IWEC.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/FIN_Helsinki.029740_IWEC.epw` & `sinergym-2.5.2/sinergym/data/weather/FIN_Helsinki.029740_IWEC.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.ddy` & `sinergym-2.5.2/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.epw` & `sinergym-2.5.2/sinergym/data/weather/JPN_Tokyo.Hyakuri.477150_IWEC.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.ddy` & `sinergym-2.5.2/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.epw` & `sinergym-2.5.2/sinergym/data/weather/MDG_Antananarivo.670830_IWEC.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/PRT_Lisboa.085360_INETI.ddy` & `sinergym-2.5.2/sinergym/data/weather/PRT_Lisboa.085360_INETI.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/PRT_Lisboa.085360_INETI.epw` & `sinergym-2.5.2/sinergym/data/weather/PRT_Lisboa.085360_INETI.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.ddy` & `sinergym-2.5.2/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.epw` & `sinergym-2.5.2/sinergym/data/weather/USA_AZ_Davis-Monthan.AFB.722745_TMY3.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.ddy` & `sinergym-2.5.2/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.epw` & `sinergym-2.5.2/sinergym/data/weather/USA_CO_Aurora-Buckley.Field.ANGB.724695_TMY3.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.ddy` & `sinergym-2.5.2/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.epw` & `sinergym-2.5.2/sinergym/data/weather/USA_IL_Chicago-OHare.Intl.AP.725300_TMY3.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.ddy` & `sinergym-2.5.2/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.epw` & `sinergym-2.5.2/sinergym/data/weather/USA_NY_New.York-J.F.Kennedy.Intl.AP.744860_TMY3.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.ddy` & `sinergym-2.5.2/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.epw` & `sinergym-2.5.2/sinergym/data/weather/USA_PA_Pittsburgh-Allegheny.County.AP.725205_TMY3.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.ddy` & `sinergym-2.5.2/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.ddy`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.epw` & `sinergym-2.5.2/sinergym/data/weather/USA_WA_Port.Angeles-William.R.Fairchild.Intl.AP.727885_TMY3.epw`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/envs/eplus_env.py` & `sinergym-2.5.2/sinergym/envs/eplus_env.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/simulators/base.py` & `sinergym-2.5.2/sinergym/simulators/base.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/simulators/eplus.py` & `sinergym-2.5.2/sinergym/simulators/eplus.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/simulators/eplus_alpha.py` & `sinergym-2.5.2/sinergym/simulators/eplus_alpha.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/utils/callbacks.py` & `sinergym-2.5.2/sinergym/utils/callbacks.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/utils/common.py` & `sinergym-2.5.2/sinergym/utils/common.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/utils/constants.py` & `sinergym-2.5.2/sinergym/utils/constants.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/utils/controllers.py` & `sinergym-2.5.2/sinergym/utils/controllers.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/utils/env_checker.py` & `sinergym-2.5.2/sinergym/utils/env_checker.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/utils/evaluation.py` & `sinergym-2.5.2/sinergym/utils/evaluation.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/utils/gcloud.py` & `sinergym-2.5.2/sinergym/utils/gcloud.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/utils/logger.py` & `sinergym-2.5.2/sinergym/utils/logger.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/utils/rewards.py` & `sinergym-2.5.2/sinergym/utils/rewards.py`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym/utils/wrappers.py` & `sinergym-2.5.2/sinergym/utils/wrappers.py`

 * *Files 3% similar despite different names*

```diff
@@ -464,16 +464,14 @@
     """A wrapper for an incremental setpoint discrete action space environment.
     WARNING: A environment with only temperature setpoints control must be used
     with this wrapper."""
 
     def __init__(
         self,
         env: gym.Env,
-        max_values: List[float],
-        min_values: List[float],
         delta_temp: float = 2.0,
         step_temp: float = 0.5,
     ):
         """
         Args:
             env: The original Sinergym env.
             action_names: Name of the action variables with the setpoint control you want to do incremental.
@@ -485,39 +483,33 @@
         """
 
         super().__init__(env)
 
         # Params
         self.env = env
         self.current_setpoints = []
-        self.max_values = max_values
-        self.min_values = min_values
 
         # calculate initial values for setpoints
         for external_schedule in list(
                 self.env.simulator._config.building['ExternalInterface:Schedule'].values()):
             self.current_setpoints.append(external_schedule['initial_value'])
 
         # Check environment is valid
+        assert not self.env.flag_discrete, 'DiscreteIncrementalWrapper: env wrapped by this wrapper must be continuous.'
         assert len(
             self.current_setpoints) == len(
-            self.env.variables['action']), 'IncrementalWrapper: Number of variables is different from environment'
-        assert len(
-            self.current_setpoints) == len(
-            self.max_values), 'IncrementalWrapper: max_values specified is incorrect for the number of action variables'
-        assert len(
-            self.current_setpoints) == len(
-            self.min_values), 'IncrementalWrapper: min_values specified is incorrect for the number of action variables'
-        assert self.env.flag_discrete, 'IncrementalWrapper: Environment wrapped must be discrete'
+            self.env.variables['action']), 'DiscreteIncrementalWrapper: Number of variables is different from environment'
 
         # Define all posible setpoint variations
         values = np.arange(step_temp, delta_temp + step_temp / 10, step_temp)
         values = [v for v in [*values, *-values]]
 
-        # Reset default environment action_mapping
+        # Reset default environment action_mapping and enable discrete
+        # environment flag
+        self.flag_discrete = True
         self.action_mapping = {}
         do_nothing = [0.0 for _ in range(
             len(self.env.variables['action']))]  # do nothing
         self.action_mapping[0] = do_nothing
         n = 1
 
         # Generate all posible actions
@@ -539,17 +531,26 @@
         self.current_setpoints = [
             sum(i) for i in zip(
                 self.current_setpoints,
                 action_)]
         # clip setpoints returned
         self.current_setpoints = np.clip(
             np.array(self.current_setpoints),
-            self.min_values,
-            self.max_values
+            self.env.real_space.low,
+            self.env.real_space.high
         )
+
+        # if normalization flag is active, this wrapper should normalize
+        # before.
+        if self.env.flag_normalization:
+            norm_values = self.env.normalized_space.high - self.env.normalized_space.low
+            setpoints_normalized = norm_values * ((self.current_setpoints - self.env.real_space.low) / (
+                self.env.real_space.high - self.env.real_space.low)) + self.env.normalized_space.low
+            return list(setpoints_normalized)
+
         return list(self.current_setpoints)
 
     # ---------------------- Specific environment wrappers ---------------------#
 
 
 class OfficeGridStorageSmoothingActionConstraintsWrapper(
         gym.ActionWrapper):  # pragma: no cover
```

### Comparing `sinergym-2.5.1/sinergym.egg-info/PKG-INFO` & `sinergym-2.5.2/sinergym.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sinergym
-Version: 2.5.1
+Version: 2.5.2
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
-Metadata-Version: 2.1 Name: sinergym Version: 2.5.1 Summary: The goal of
+Metadata-Version: 2.1 Name: sinergym Version: 2.5.2 Summary: The goal of
 sinergym is to create an environment following OpenAI Gym interface for
 wrapping simulation engines for building control using deep reinforcement
 learning. Home-page: https://github.com/ugr-sail/sinergym Author: J. JimÃ©nez,
 J. GÃ³mez, M. Molina, A. Manjavacas, A. Campoy Author-email:
 alejandroac79@gmail.com License: MIT Keywords: control reinforcement-learning
 buildings reinforcement-learning-environments Platform: UNKNOWN Classifier:
 Development Status :: 5 - Production/Stable Classifier: Programming Language ::
```

### Comparing `sinergym-2.5.1/sinergym.egg-info/SOURCES.txt` & `sinergym-2.5.2/sinergym.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `sinergym-2.5.1/sinergym.egg-info/requires.txt` & `sinergym-2.5.2/sinergym.egg-info/requires.txt`

 * *Files identical despite different names*

