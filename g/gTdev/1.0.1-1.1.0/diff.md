# Comparing `tmp/gTdev-1.0.1.tar.gz` & `tmp/gTdev-1.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "gTdev-1.0.1.tar", last modified: Wed Jun 28 03:12:56 2023, max compression
+gzip compressed data, was "gTdev-1.1.0.tar", last modified: Wed Jun 28 09:10:31 2023, max compression
```

## Comparing `gTdev-1.0.1.tar` & `gTdev-1.1.0.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 03:12:56.633982 gTdev-1.0.1/
--rw-rw-rw-   0        0        0     1091 2022-12-02 07:39:30.000000 gTdev-1.0.1/LICENSE
--rw-rw-rw-   0        0        0      123 2023-04-19 01:59:01.000000 gTdev-1.0.1/MANIFEST.in
--rw-rw-rw-   0        0        0     7208 2023-06-28 03:12:56.633014 gTdev-1.0.1/PKG-INFO
--rw-rw-rw-   0        0        0     6785 2023-06-28 03:12:03.000000 gTdev-1.0.1/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 03:12:56.599996 gTdev-1.0.1/gTdev/
--rw-rw-rw-   0        0        0      129 2023-05-22 03:09:44.000000 gTdev-1.0.1/gTdev/__init__.py
--rw-rw-rw-   0        0        0     2548 2023-05-22 02:15:58.000000 gTdev-1.0.1/gTdev/gtInv.py
--rw-rw-rw-   0        0        0     2957 2023-06-28 02:26:44.000000 gTdev-1.0.1/gTdev/gtcurve.py
--rw-rw-rw-   0        0        0      187 2023-05-16 06:36:50.000000 gTdev-1.0.1/gTdev/gtdevCommon.py
--rw-rw-rw-   0        0        0     1561 2023-05-24 00:29:00.000000 gTdev-1.0.1/gTdev/gtfile.py
--rw-rw-rw-   0        0        0     4205 2023-06-28 02:33:49.000000 gTdev-1.0.1/gTdev/gtmos.py
-drwxrwxrwx   0        0        0        0 2023-06-28 03:12:56.630013 gTdev-1.0.1/gTdev.egg-info/
--rw-rw-rw-   0        0        0     7208 2023-06-28 03:12:55.000000 gTdev-1.0.1/gTdev.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      256 2023-06-28 03:12:56.000000 gTdev-1.0.1/gTdev.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 03:12:55.000000 gTdev-1.0.1/gTdev.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        6 2023-06-28 03:12:55.000000 gTdev-1.0.1/gTdev.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 03:12:56.633982 gTdev-1.0.1/setup.cfg
--rw-rw-rw-   0        0        0      689 2023-06-28 03:12:50.000000 gTdev-1.0.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:10:31.169007 gTdev-1.1.0/
+-rw-rw-rw-   0        0        0     1091 2022-12-02 07:39:30.000000 gTdev-1.1.0/LICENSE
+-rw-rw-rw-   0        0        0      123 2023-04-19 01:59:01.000000 gTdev-1.1.0/MANIFEST.in
+-rw-rw-rw-   0        0        0     7464 2023-06-28 09:10:31.168007 gTdev-1.1.0/PKG-INFO
+-rw-rw-rw-   0        0        0     7041 2023-06-28 09:09:36.000000 gTdev-1.1.0/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 09:10:31.141008 gTdev-1.1.0/gTdev/
+-rw-rw-rw-   0        0        0      129 2023-05-22 03:09:44.000000 gTdev-1.1.0/gTdev/__init__.py
+-rw-rw-rw-   0        0        0     2548 2023-05-22 02:15:58.000000 gTdev-1.1.0/gTdev/gtInv.py
+-rw-rw-rw-   0        0        0     2957 2023-06-28 02:26:44.000000 gTdev-1.1.0/gTdev/gtcurve.py
+-rw-rw-rw-   0        0        0      187 2023-05-16 06:36:50.000000 gTdev-1.1.0/gTdev/gtdevCommon.py
+-rw-rw-rw-   0        0        0     1561 2023-05-24 00:29:00.000000 gTdev-1.1.0/gTdev/gtfile.py
+-rw-rw-rw-   0        0        0     4205 2023-06-28 02:33:49.000000 gTdev-1.1.0/gTdev/gtmos.py
+drwxrwxrwx   0        0        0        0 2023-06-28 09:10:31.165010 gTdev-1.1.0/gTdev.egg-info/
+-rw-rw-rw-   0        0        0     7464 2023-06-28 09:10:30.000000 gTdev-1.1.0/gTdev.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      256 2023-06-28 09:10:30.000000 gTdev-1.1.0/gTdev.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 09:10:30.000000 gTdev-1.1.0/gTdev.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 09:10:30.000000 gTdev-1.1.0/gTdev.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 09:10:31.169007 gTdev-1.1.0/setup.cfg
+-rw-rw-rw-   0        0        0      689 2023-06-28 09:10:14.000000 gTdev-1.1.0/setup.py
```

### Comparing `gTdev-1.0.1/LICENSE` & `gTdev-1.1.0/LICENSE`

 * *Files identical despite different names*

### Comparing `gTdev-1.0.1/PKG-INFO` & `gTdev-1.1.0/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gTdev
-Version: 1.0.1
+Version: 1.1.0
 Summary: 高效碳基测试运算模块
 Home-page: https://gitee.com/lxwk1spectre/gdevsample
 Author: Spectre Lee
 Author-email: lxwk1spectre@foxmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
@@ -96,14 +96,17 @@
 根据self.X_Axis和self.Y_Axis获取曲线。
 - absY
     - bool
     - 在提取Y_Axis时，默认会对Y的值取绝对值。设置为False时，Y轴数据不会取绝对值。
 
 在实例化gtfile类时，会自动运行getfile()和getcurves()函数进行提取曲线，一般不需要使用这两个函数进行手动添加。
 
+#### gtfile.cutcurve(start,end)
+根据start和end的值，对曲线进行截取
+
 ## 通用: gTdev.gtdevCommon
 ### 物理量: gTdev.gtdevCommon.physicalQuantity
 - class
 - 用于存储提取出的参数的类
 #### physicalQuantity(num,unit)
 - 根据物理量的值和单位初始化物理量
 #### physicalQuantity.num
@@ -179,16 +182,18 @@
         - NMH = xH-yL, NML = yH - xL
     - hys: 回滞
         - 反相器曲线与 y = (max(Vout)+min(Vout)) / 2 有两个交点
         - 两个交点的差作为回滞
     - gain：增益
         - dVout/dVin的最大值作为反相器增益
 # 版本迭代
-## 1.0.1
+## 1.1.0
 - 230628
     - 优化了亚阈值摆幅的算法，如果关态附近电流波动太大，会尝试用不同的limit切除一部分数据，最终判断出最合适的线性区，再进行亚阈值摆幅的提取。
+    - 将优化关态波动的算法应用的阈值电压的提取，和最大跨导的提取上
+    - 曲线增加cut函数，可以截取一部分曲线进行分析。
 ## 1.0.0
 - 230601
     - 正式上线
 ## 0.0.3
 - 230522
     - 初始版本发布。
```

### Comparing `gTdev-1.0.1/README.md` & `gTdev-1.1.0/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -83,14 +83,17 @@
 根据self.X_Axis和self.Y_Axis获取曲线。
 - absY
     - bool
     - 在提取Y_Axis时，默认会对Y的值取绝对值。设置为False时，Y轴数据不会取绝对值。
 
 在实例化gtfile类时，会自动运行getfile()和getcurves()函数进行提取曲线，一般不需要使用这两个函数进行手动添加。
 
+#### gtfile.cutcurve(start,end)
+根据start和end的值，对曲线进行截取
+
 ## 通用: gTdev.gtdevCommon
 ### 物理量: gTdev.gtdevCommon.physicalQuantity
 - class
 - 用于存储提取出的参数的类
 #### physicalQuantity(num,unit)
 - 根据物理量的值和单位初始化物理量
 #### physicalQuantity.num
@@ -166,16 +169,18 @@
         - NMH = xH-yL, NML = yH - xL
     - hys: 回滞
         - 反相器曲线与 y = (max(Vout)+min(Vout)) / 2 有两个交点
         - 两个交点的差作为回滞
     - gain：增益
         - dVout/dVin的最大值作为反相器增益
 # 版本迭代
-## 1.0.1
+## 1.1.0
 - 230628
     - 优化了亚阈值摆幅的算法，如果关态附近电流波动太大，会尝试用不同的limit切除一部分数据，最终判断出最合适的线性区，再进行亚阈值摆幅的提取。
+    - 将优化关态波动的算法应用的阈值电压的提取，和最大跨导的提取上
+    - 曲线增加cut函数，可以截取一部分曲线进行分析。
 ## 1.0.0
 - 230601
     - 正式上线
 ## 0.0.3
 - 230522
     - 初始版本发布。
```

### Comparing `gTdev-1.0.1/gTdev/gtInv.py` & `gTdev-1.1.0/gTdev/gtInv.py`

 * *Files identical despite different names*

### Comparing `gTdev-1.0.1/gTdev/gtcurve.py` & `gTdev-1.1.0/gTdev/gtcurve.py`

 * *Files identical despite different names*

### Comparing `gTdev-1.0.1/gTdev/gtfile.py` & `gTdev-1.1.0/gTdev/gtfile.py`

 * *Files identical despite different names*

### Comparing `gTdev-1.0.1/gTdev/gtmos.py` & `gTdev-1.1.0/gTdev/gtmos.py`

 * *Files identical despite different names*

### Comparing `gTdev-1.0.1/gTdev.egg-info/PKG-INFO` & `gTdev-1.1.0/gTdev.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gTdev
-Version: 1.0.1
+Version: 1.1.0
 Summary: 高效碳基测试运算模块
 Home-page: https://gitee.com/lxwk1spectre/gdevsample
 Author: Spectre Lee
 Author-email: lxwk1spectre@foxmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
@@ -96,14 +96,17 @@
 根据self.X_Axis和self.Y_Axis获取曲线。
 - absY
     - bool
     - 在提取Y_Axis时，默认会对Y的值取绝对值。设置为False时，Y轴数据不会取绝对值。
 
 在实例化gtfile类时，会自动运行getfile()和getcurves()函数进行提取曲线，一般不需要使用这两个函数进行手动添加。
 
+#### gtfile.cutcurve(start,end)
+根据start和end的值，对曲线进行截取
+
 ## 通用: gTdev.gtdevCommon
 ### 物理量: gTdev.gtdevCommon.physicalQuantity
 - class
 - 用于存储提取出的参数的类
 #### physicalQuantity(num,unit)
 - 根据物理量的值和单位初始化物理量
 #### physicalQuantity.num
@@ -179,16 +182,18 @@
         - NMH = xH-yL, NML = yH - xL
     - hys: 回滞
         - 反相器曲线与 y = (max(Vout)+min(Vout)) / 2 有两个交点
         - 两个交点的差作为回滞
     - gain：增益
         - dVout/dVin的最大值作为反相器增益
 # 版本迭代
-## 1.0.1
+## 1.1.0
 - 230628
     - 优化了亚阈值摆幅的算法，如果关态附近电流波动太大，会尝试用不同的limit切除一部分数据，最终判断出最合适的线性区，再进行亚阈值摆幅的提取。
+    - 将优化关态波动的算法应用的阈值电压的提取，和最大跨导的提取上
+    - 曲线增加cut函数，可以截取一部分曲线进行分析。
 ## 1.0.0
 - 230601
     - 正式上线
 ## 0.0.3
 - 230522
     - 初始版本发布。
```

### Comparing `gTdev-1.0.1/setup.py` & `gTdev-1.1.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="gTdev",
-    version="1.0.1",
+    version="1.1.0",
     author="Spectre Lee",
     author_email="lxwk1spectre@foxmail.com",
     description="高效碳基测试运算模块",
     long_description=long_description,
     long_description_content_type="text/markdown",
     include_package_data=True,
     url="https://gitee.com/lxwk1spectre/gdevsample",
```

