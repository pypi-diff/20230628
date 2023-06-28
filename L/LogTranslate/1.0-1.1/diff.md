# Comparing `tmp/LogTranslate-1.0.tar.gz` & `tmp/LogTranslate-1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "LogTranslate-1.0.tar", last modified: Tue Jun 27 15:21:01 2023, max compression
+gzip compressed data, was "LogTranslate-1.1.tar", last modified: Wed Jun 28 15:57:11 2023, max compression
```

## Comparing `LogTranslate-1.0.tar` & `LogTranslate-1.1.tar`

### file list

```diff
@@ -1,28 +1,28 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 15:21:01.808447 LogTranslate-1.0/
--rw-rw-rw-   0        0        0     1059 2023-06-26 17:21:40.000000 LogTranslate-1.0/LICENSE.txt
-drwxrwxrwx   0        0        0        0 2023-06-27 15:21:01.791438 LogTranslate-1.0/LogTranslate.egg-info/
--rw-rw-rw-   0        0        0     3172 2023-06-27 15:21:01.000000 LogTranslate-1.0/LogTranslate.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      623 2023-06-27 15:21:01.000000 LogTranslate-1.0/LogTranslate.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 15:21:01.000000 LogTranslate-1.0/LogTranslate.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       32 2023-06-27 15:21:01.000000 LogTranslate-1.0/LogTranslate.egg-info/requires.txt
--rw-rw-rw-   0        0        0       14 2023-06-27 15:21:01.000000 LogTranslate-1.0/LogTranslate.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     3172 2023-06-27 15:21:01.808447 LogTranslate-1.0/PKG-INFO
--rw-rw-rw-   0        0        0     2379 2023-06-27 14:49:49.000000 LogTranslate-1.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-27 15:21:01.803436 LogTranslate-1.0/log_translate/
--rw-rw-rw-   0        0        0        0 2023-06-27 08:16:54.000000 LogTranslate-1.0/log_translate/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-27 15:21:01.806446 LogTranslate-1.0/log_translate/business/
--rw-rw-rw-   0        0        0      636 2023-06-27 14:14:13.000000 LogTranslate-1.0/log_translate/business/AndroidCrashPattern_translator.py
--rw-rw-rw-   0        0        0        0 2023-06-27 08:17:11.000000 LogTranslate-1.0/log_translate/business/__init__.py
--rw-rw-rw-   0        0        0     3751 2023-06-27 11:40:54.000000 LogTranslate-1.0/log_translate/business/bluetooth_translator.py
--rw-rw-rw-   0        0        0      324 2023-06-27 11:40:54.000000 LogTranslate-1.0/log_translate/config_default.py
--rw-rw-rw-   0        0        0     1294 2023-06-27 14:36:30.000000 LogTranslate-1.0/log_translate/data_struct.py
--rw-rw-rw-   0        0        0       10 2023-06-26 17:21:40.000000 LogTranslate-1.0/log_translate/gloable.py
--rw-rw-rw-   0        0        0     4236 2023-06-27 11:40:54.000000 LogTranslate-1.0/log_translate/log_translator.py
--rw-rw-rw-   0        0        0     3080 2023-06-27 15:20:40.000000 LogTranslate-1.0/log_translate/read_log_file.py
-drwxrwxrwx   0        0        0        0 2023-06-27 15:21:01.807450 LogTranslate-1.0/log_translate/res/
--rw-rw-rw-   0        0        0    10687 2023-06-27 14:36:27.000000 LogTranslate-1.0/log_translate/res/log_logo.ico
--rw-rw-rw-   0        0        0     6371 2023-06-27 15:14:55.000000 LogTranslate-1.0/log_translate/ui_pyqt6.py
--rw-rw-rw-   0        0        0     7708 2023-06-27 15:19:20.000000 LogTranslate-1.0/log_translate/ui_pyside2.py
--rw-rw-rw-   0        0        0      379 2023-06-26 17:21:40.000000 LogTranslate-1.0/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-27 15:21:01.809448 LogTranslate-1.0/setup.cfg
--rw-rw-rw-   0        0        0     2111 2023-06-27 15:20:59.000000 LogTranslate-1.0/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 15:57:11.797219 LogTranslate-1.1/
+-rw-rw-rw-   0        0        0     1079 2023-06-28 15:23:37.000000 LogTranslate-1.1/LICENSE.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 15:57:11.778278 LogTranslate-1.1/LogTranslate.egg-info/
+-rw-rw-rw-   0        0        0     3181 2023-06-28 15:57:11.000000 LogTranslate-1.1/LogTranslate.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      623 2023-06-28 15:57:11.000000 LogTranslate-1.1/LogTranslate.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 15:57:11.000000 LogTranslate-1.1/LogTranslate.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       32 2023-06-28 15:57:11.000000 LogTranslate-1.1/LogTranslate.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       14 2023-06-28 15:57:11.000000 LogTranslate-1.1/LogTranslate.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     3181 2023-06-28 15:57:11.796279 LogTranslate-1.1/PKG-INFO
+-rw-rw-rw-   0        0        0     2474 2023-06-28 15:23:37.000000 LogTranslate-1.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 15:57:11.789245 LogTranslate-1.1/log_translate/
+-rw-rw-rw-   0        0        0        0 2023-06-28 15:23:37.000000 LogTranslate-1.1/log_translate/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 15:57:11.793270 LogTranslate-1.1/log_translate/business/
+-rw-rw-rw-   0        0        0      618 2023-06-28 15:23:37.000000 LogTranslate-1.1/log_translate/business/AndroidCrashPattern_translator.py
+-rw-rw-rw-   0        0        0        0 2023-06-28 15:23:37.000000 LogTranslate-1.1/log_translate/business/__init__.py
+-rw-rw-rw-   0        0        0     3848 2023-06-28 15:23:37.000000 LogTranslate-1.1/log_translate/business/bluetooth_translator.py
+-rw-rw-rw-   0        0        0      329 2023-06-28 15:23:37.000000 LogTranslate-1.1/log_translate/config_default.py
+-rw-rw-rw-   0        0        0     1349 2023-06-28 15:23:37.000000 LogTranslate-1.1/log_translate/data_struct.py
+-rw-rw-rw-   0        0        0       11 2023-06-28 15:23:37.000000 LogTranslate-1.1/log_translate/gloable.py
+-rw-rw-rw-   0        0        0     4362 2023-06-28 15:23:37.000000 LogTranslate-1.1/log_translate/log_translator.py
+-rw-rw-rw-   0        0        0     3162 2023-06-28 15:23:37.000000 LogTranslate-1.1/log_translate/read_log_file.py
+drwxrwxrwx   0        0        0        0 2023-06-28 15:57:11.795226 LogTranslate-1.1/log_translate/res/
+-rw-rw-rw-   0        0        0    10687 2023-06-28 15:23:37.000000 LogTranslate-1.1/log_translate/res/log_logo.ico
+-rw-rw-rw-   0        0        0     7111 2023-06-28 15:47:22.000000 LogTranslate-1.1/log_translate/ui_pyqt6.py
+-rw-rw-rw-   0        0        0     7099 2023-06-28 15:47:22.000000 LogTranslate-1.1/log_translate/ui_pyside2.py
+-rw-rw-rw-   0        0        0      393 2023-06-28 15:23:37.000000 LogTranslate-1.1/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 15:57:11.797219 LogTranslate-1.1/setup.cfg
+-rw-rw-rw-   0        0        0     2165 2023-06-28 15:52:11.000000 LogTranslate-1.1/setup.py
```

### Comparing `LogTranslate-1.0/LICENSE.txt` & `LogTranslate-1.1/LICENSE.txt`

 * *Ordering differences only*

 * *Files 20% similar despite different names*

```diff
@@ -1,21 +1,21 @@
-MIT License
-
-Copyright (c) 2023 贇
-
-Permission is hereby granted, free of charge, to any person obtaining a copy
-of this software and associated documentation files (the "Software"), to deal
-in the Software without restriction, including without limitation the rights
-to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
-copies of the Software, and to permit persons to whom the Software is
-furnished to do so, subject to the following conditions:
-
-The above copyright notice and this permission notice shall be included in all
-copies or substantial portions of the Software.
-
-THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
-IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
-FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
-AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
-LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
-OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
+MIT License
+
+Copyright (c) 2023 贇
+
+Permission is hereby granted, free of charge, to any person obtaining a copy
+of this software and associated documentation files (the "Software"), to deal
+in the Software without restriction, including without limitation the rights
+to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
+copies of the Software, and to permit persons to whom the Software is
+furnished to do so, subject to the following conditions:
+
+The above copyright notice and this permission notice shall be included in all
+copies or substantial portions of the Software.
+
+THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
+IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
+FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
+AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
+LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
+OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 SOFTWARE.
```

### Comparing `LogTranslate-1.0/LogTranslate.egg-info/PKG-INFO` & `LogTranslate-1.1/LogTranslate.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: LogTranslate
-Version: 1.0
+Version: 1.1
 Summary: A Python library for translate log from log files
 Home-page: https://github.com/5hmlA/PyTools
 Author: 5hmlA
 Author-email: jonas.jzy@gmail.com
 License: MIT Licence
 Keywords: tools log translate
 Classifier: Development Status :: 3 - Alpha
@@ -19,15 +19,17 @@
 License-File: LICENSE.txt
 
 ## 作用
 
 把日志文件拖动到窗口即可解析日志
 
 ## 使用
+
 安装
+
 ```commandline
 pip install LogTranslate
 ```
 
 项目根目录 创建 config.py
 里面定义字段 translator数组
 
@@ -80,24 +82,27 @@
 
        def new_tag(self, tag, msg):# 这里两个参数
            return Log(translated=msg)
   ```
 
 ## 打包成 exe
 
- #### 1 ，项目根目录创建 ui.py
+#### 1 ，项目根目录创建 ui.py
+
 ```python
 
 if __name__ == "__main__":
     app = QApplication(sys.argv)
     window = PyQt6Window()
     window.show()
     sys.exit(app.exec())
 ```
+
 #### 2， 执行打包命令
+
 ```commandline
 
 pyinstaller -n [name] --hidden-import config -F -w [-i tools.ico] ui.py
 
 ```
 
 ### 库地址
```

### Comparing `LogTranslate-1.0/LogTranslate.egg-info/SOURCES.txt` & `LogTranslate-1.1/LogTranslate.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `LogTranslate-1.0/PKG-INFO` & `LogTranslate-1.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: LogTranslate
-Version: 1.0
+Version: 1.1
 Summary: A Python library for translate log from log files
 Home-page: https://github.com/5hmlA/PyTools
 Author: 5hmlA
 Author-email: jonas.jzy@gmail.com
 License: MIT Licence
 Keywords: tools log translate
 Classifier: Development Status :: 3 - Alpha
@@ -19,15 +19,17 @@
 License-File: LICENSE.txt
 
 ## 作用
 
 把日志文件拖动到窗口即可解析日志
 
 ## 使用
+
 安装
+
 ```commandline
 pip install LogTranslate
 ```
 
 项目根目录 创建 config.py
 里面定义字段 translator数组
 
@@ -80,24 +82,27 @@
 
        def new_tag(self, tag, msg):# 这里两个参数
            return Log(translated=msg)
   ```
 
 ## 打包成 exe
 
- #### 1 ，项目根目录创建 ui.py
+#### 1 ，项目根目录创建 ui.py
+
 ```python
 
 if __name__ == "__main__":
     app = QApplication(sys.argv)
     window = PyQt6Window()
     window.show()
     sys.exit(app.exec())
 ```
+
 #### 2， 执行打包命令
+
 ```commandline
 
 pyinstaller -n [name] --hidden-import config -F -w [-i tools.ico] ui.py
 
 ```
 
 ### 库地址
```

### Comparing `LogTranslate-1.0/README.md` & `LogTranslate-1.1/README.md`

 * *Files 24% similar despite different names*

```diff
@@ -1,86 +1,91 @@
-## 作用
-
-把日志文件拖动到窗口即可解析日志
-
-## 使用
-安装
-```commandline
-pip install LogTranslate
-```
-
-项目根目录 创建 config.py
-里面定义字段 translator数组
-
-```commandline
-translators = [SysLogTranslator(tag_translators=[BluetoothTranslator(), CrashPatternTranslator()])]
-```
-
-SysLogTranslator是将文件中每行字符串解析出 tag,time,pid,msg
-SysLogTranslator的参数 tag_translators 是数组 用来解析 各种tag对应的内容
-解析tag的基类有
-
-- TagPatternTranslator 通过正则匹配tag然后解析
-  ```python
-  class CrashPatternTranslator(TagPatternTranslator):
-       def __init__(self):
-           super().__init__({
-               r"AndroidRuntime|FATAL.*|System.err.*": activity_task_translator
-           })
-      
-       def activity_task_translator(tag, msg): # 这里两个参数
-           # todo 这里需要过滤包名
-           return Log(translated=" ------ %s > %s----- " % (tag, msg), level=Level.e)
-
-  ```
-
-- TagStrTranslator 通过字符串匹配tag然后解析
-   ```python
-  class BluetoothTranslator(TagStrTranslator):
-       def __init__(self):
-           super().__init__({
-               "BluetoothAdapter": bluetooth_adapter,
-           })
-          
-       def bluetooth_adapter(msg):# 这里一个参数
-           # todo 这里需要过滤包名
-           return Log(translated=" ------ %s > %s----- " % (tag, msg), level=Level.e)
-
-  ```
-- SecStrTagTranslator 解析二级tag
-   ```python
-   class SecTagDemoTranslator(SecStrTagTranslator):
-       def __init__(self):
-           super().__init__("DFJ",
-                            lambda string: re.search(r"(?P<tag>.*?) *:(?P<msg>.*)", string),
-                            [
-                                SysLogTranslator({
-                                    "sec_tag": self.new_tag
-                                })
-                            ])
-
-       def new_tag(self, tag, msg):# 这里两个参数
-           return Log(translated=msg)
-  ```
-
-## 打包成 exe
-
- #### 1 ，项目根目录创建 ui.py
-```python
-
-if __name__ == "__main__":
-    app = QApplication(sys.argv)
-    window = PyQt6Window()
-    window.show()
-    sys.exit(app.exec())
-```
-#### 2， 执行打包命令
-```commandline
-
-pyinstaller -n [name] --hidden-import config -F -w [-i tools.ico] ui.py
-
-```
-
-### 库地址
-
-https://pypi.org/project/LogTranslate/0.1/
-
+## 作用
+
+把日志文件拖动到窗口即可解析日志
+
+## 使用
+
+安装
+
+```commandline
+pip install LogTranslate
+```
+
+项目根目录 创建 config.py
+里面定义字段 translator数组
+
+```commandline
+translators = [SysLogTranslator(tag_translators=[BluetoothTranslator(), CrashPatternTranslator()])]
+```
+
+SysLogTranslator是将文件中每行字符串解析出 tag,time,pid,msg
+SysLogTranslator的参数 tag_translators 是数组 用来解析 各种tag对应的内容
+解析tag的基类有
+
+- TagPatternTranslator 通过正则匹配tag然后解析
+  ```python
+  class CrashPatternTranslator(TagPatternTranslator):
+       def __init__(self):
+           super().__init__({
+               r"AndroidRuntime|FATAL.*|System.err.*": activity_task_translator
+           })
+      
+       def activity_task_translator(tag, msg): # 这里两个参数
+           # todo 这里需要过滤包名
+           return Log(translated=" ------ %s > %s----- " % (tag, msg), level=Level.e)
+
+  ```
+
+- TagStrTranslator 通过字符串匹配tag然后解析
+   ```python
+  class BluetoothTranslator(TagStrTranslator):
+       def __init__(self):
+           super().__init__({
+               "BluetoothAdapter": bluetooth_adapter,
+           })
+          
+       def bluetooth_adapter(msg):# 这里一个参数
+           # todo 这里需要过滤包名
+           return Log(translated=" ------ %s > %s----- " % (tag, msg), level=Level.e)
+
+  ```
+- SecStrTagTranslator 解析二级tag
+   ```python
+   class SecTagDemoTranslator(SecStrTagTranslator):
+       def __init__(self):
+           super().__init__("DFJ",
+                            lambda string: re.search(r"(?P<tag>.*?) *:(?P<msg>.*)", string),
+                            [
+                                SysLogTranslator({
+                                    "sec_tag": self.new_tag
+                                })
+                            ])
+
+       def new_tag(self, tag, msg):# 这里两个参数
+           return Log(translated=msg)
+  ```
+
+## 打包成 exe
+
+#### 1 ，项目根目录创建 ui.py
+
+```python
+
+if __name__ == "__main__":
+    app = QApplication(sys.argv)
+    window = PyQt6Window()
+    window.show()
+    sys.exit(app.exec())
+```
+
+#### 2， 执行打包命令
+
+```commandline
+
+pyinstaller -n [name] --hidden-import config -F -w [-i tools.ico] ui.py
+
+```
+
+### 库地址
+
+https://pypi.org/project/LogTranslate/0.1/
+
```

### Comparing `LogTranslate-1.0/log_translate/business/bluetooth_translator.py` & `LogTranslate-1.1/log_translate/business/bluetooth_translator.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,97 +1,97 @@
-from log_translate.data_struct import Log, Level
-from log_translate.log_translator import *
-
-
-class SecTagDemoTranslator(SecStrTagTranslator):
-    def __init__(self):
-        super().__init__("DFJ",
-                         lambda string: re.search(r"(?P<tag>.*?) *:(?P<msg>.*)", string),
-                         [
-                             SysLogTranslator({
-                                 "sec_tag": self.new_tag
-                             })
-                         ])
-
-    def new_tag(self, tag, msg):
-        return Log(translated=msg)
-
-
-class BluetoothTranslator(TagStrTranslator):
-    def __init__(self):
-        super().__init__({
-            "BluetoothAdapter": bluetooth_adapter,
-            "BluetoothGatt": bluetooth_gatt,
-            "bt_rfcomm": bt_rfcomm,
-            "WS_BT_BluetoothPairingRequest": bluetooth_pairing_request,
-            "ActivityTaskManager": bluetooth_pairing_dialog
-        })
-
-
-code_state = {
-    "10": "手机系统蓝牙 已关闭",
-    "12": "手机系统蓝牙 已打开",
-    "OFF": "手机系统蓝牙 已关闭",
-    "ON": "手机系统蓝牙 已打开"
-}
-
-
-def bluetooth_pairing_dialog(msg):
-    # ActivityTaskManager: Displayed com.oplus.wirelesssettings/com.android.settings.bluetooth.BluetoothPairingDialog
-    # port_rfc_closed: RFCOMM connection closed, index=3, state=2 reason=Closed[19], UUID=111F, bd_addr=ac:73:52:3f:5b:0a, is_server=1
-    if "BluetoothPairingDialog" in msg:
-        result = re.search("Displayed.*BluetoothPairingDialog", msg)
-        if result:
-            return Log(translated=" ----------------------- 配对PIN码弹窗弹出 ----------------------- ")
-    return None
-
-
-def bluetooth_pairing_request(msg):
-    # port_rfc_closed: RFCOMM connection closed, index=3, state=2 reason=Closed[19], UUID=111F, bd_addr=ac:73:52:3f:5b:0a, is_server=1
-    if "PAIRING_REQUEST" in msg:
-        return Log(translated=" ----------------------- 设备请求配对 ----------------------- ")
-    return None
-
-
-def bt_rfcomm(msg):
-    # port_rfc_closed: RFCOMM connection closed, index=3, state=2 reason=Closed[19], UUID=111F, bd_addr=ac:73:52:3f:5b:0a, is_server=1
-    if "port_rfc_closed" in msg:
-        result = re.search(".*: (ON|OFF)", msg)
-        if result:
-            if result.group(1) in code_state:
-                return Log(translated=">>>>>>>>>>  %s  <<<<<<<< " % (code_state[result.group(1)]), level=Level.i)
-
-    return None
-
-
-def bluetooth_adapter(msg):
-    if "isLeEnabled" in msg:
-        result = re.search(".*: (ON|OFF)", msg)
-        if result:
-            if result.group(1) in code_state:
-                return Log(translated=">>>>>>>>>>  %s  <<<<<<<< " % (code_state[result.group(1)]), level=Level.i)
-
-    return None
-
-
-# noinspection PyTypeChecker
-def bluetooth_gatt(msg: object) -> object:
-    if "cancelOpen()" in msg:
-        result = re.search("device: (.*?)", msg)
-        return Log(translated=">>>>>>>>>>  gatt 手机主动断开连接 %s  <<<<<<<< " % (result.group(1)), level=Level.w)
-    if "close()" in msg:
-        return Log(translated=">>>>>>>>>>  gatt 手机主动关闭连接  <<<<<<<< ", level=Level.w)
-    if "connect()" in msg:
-        # connect() - device: 34:47:9A:31:52:CF, auto: false, eattSupport: false
-        result = re.search("device: (.*?),", msg)
-        return Log(translated=">>>>>>>>>>  gatt 发起设备连接 %s  <<<<<<<< " % (result.group(1)), level=Level.w)
-    return None
-
-
-if __name__ == '__main__':
-    result = re.search("device: (.*?),", "connect() - device: 34:47:9A:31:52:CF, auto: false, eattSupport: false")
-    print(result.group(1))
-    result = re.search("(?<=\*).*", "onReCreateBond: 24:*:35:06")
-
-    # (?<=A).+?(?=B) 匹配规则A和B之间的元素 不包括A和B
-    #
-    print(result.group())
+from log_translate.data_struct import Log, Level
+from log_translate.log_translator import *
+
+
+class SecTagDemoTranslator(SecStrTagTranslator):
+    def __init__(self):
+        super().__init__("DFJ",
+                         lambda string: re.search(r"(?P<tag>.*?) *:(?P<msg>.*)", string),
+                         [
+                             TagStrTranslator({
+                                 "sec_tag": self.new_tag
+                             })
+                         ])
+
+    def new_tag(self, tag, msg):
+        return Log(translated=msg)
+
+
+class BluetoothTranslator(TagStrTranslator):
+    def __init__(self):
+        super().__init__({
+            "BluetoothAdapter": bluetooth_adapter,
+            "BluetoothGatt": bluetooth_gatt,
+            "bt_rfcomm": bt_rfcomm,
+            "WS_BT_BluetoothPairingRequest": bluetooth_pairing_request,
+            "ActivityTaskManager": bluetooth_pairing_dialog
+        })
+
+
+code_state = {
+    "10": "手机系统蓝牙 已关闭",
+    "12": "手机系统蓝牙 已打开",
+    "OFF": "手机系统蓝牙 已关闭",
+    "ON": "手机系统蓝牙 已打开"
+}
+
+
+def bluetooth_pairing_dialog(msg):
+    # ActivityTaskManager: Displayed com.oplus.wirelesssettings/com.android.settings.bluetooth.BluetoothPairingDialog
+    # port_rfc_closed: RFCOMM connection closed, index=3, state=2 reason=Closed[19], UUID=111F, bd_addr=ac:73:52:3f:5b:0a, is_server=1
+    if "BluetoothPairingDialog" in msg:
+        result = re.search("Displayed.*BluetoothPairingDialog", msg)
+        if result:
+            return Log(translated=" ----------------------- 配对PIN码弹窗弹出 ----------------------- ")
+    return None
+
+
+def bluetooth_pairing_request(msg):
+    # port_rfc_closed: RFCOMM connection closed, index=3, state=2 reason=Closed[19], UUID=111F, bd_addr=ac:73:52:3f:5b:0a, is_server=1
+    if "PAIRING_REQUEST" in msg:
+        return Log(translated=" ----------------------- 设备请求配对 ----------------------- ")
+    return None
+
+
+def bt_rfcomm(msg):
+    # port_rfc_closed: RFCOMM connection closed, index=3, state=2 reason=Closed[19], UUID=111F, bd_addr=ac:73:52:3f:5b:0a, is_server=1
+    if "port_rfc_closed" in msg:
+        result = re.search(".*: (ON|OFF)", msg)
+        if result:
+            if result.group(1) in code_state:
+                return Log(translated=">>>>>>>>>>  %s  <<<<<<<< " % (code_state[result.group(1)]), level=Level.i)
+
+    return None
+
+
+def bluetooth_adapter(msg):
+    if "isLeEnabled" in msg:
+        result = re.search(".*: (ON|OFF)", msg)
+        if result:
+            if result.group(1) in code_state:
+                return Log(translated=">>>>>>>>>>  %s  <<<<<<<< " % (code_state[result.group(1)]), level=Level.i)
+
+    return None
+
+
+# noinspection PyTypeChecker
+def bluetooth_gatt(msg: object) -> object:
+    if "cancelOpen()" in msg:
+        result = re.search("device: (.*?)", msg)
+        return Log(translated=">>>>>>>>>>  gatt 手机主动断开连接 %s  <<<<<<<< " % (result.group(1)), level=Level.w)
+    if "close()" in msg:
+        return Log(translated=">>>>>>>>>>  gatt 手机主动关闭连接  <<<<<<<< ", level=Level.w)
+    if "connect()" in msg:
+        # connect() - device: 34:47:9A:31:52:CF, auto: false, eattSupport: false
+        result = re.search("device: (.*?),", msg)
+        return Log(translated=">>>>>>>>>>  gatt 发起设备连接 %s  <<<<<<<< " % (result.group(1)), level=Level.w)
+    return None
+
+
+if __name__ == '__main__':
+    result = re.search("device: (.*?),", "connect() - device: 34:47:9A:31:52:CF, auto: false, eattSupport: false")
+    print(result.group(1))
+    result = re.search("(?<=\*).*", "onReCreateBond: 24:*:35:06")
+
+    # (?<=A).+?(?=B) 匹配规则A和B之间的元素 不包括A和B
+    #
+    print(result.group())
```

### Comparing `LogTranslate-1.0/log_translate/log_translator.py` & `LogTranslate-1.1/log_translate/log_translator.py`

 * *Ordering differences only*

 * *Files 18% similar despite different names*

```diff
@@ -1,126 +1,126 @@
-import re
-from abc import abstractmethod
-
-from log_translate.gloable import pids
-
-
-# 通过正则表达式匹配tag解析
-# :param pattern_translators 是数据[tag,fun(tag, msg)] fun参数必须是(tag, msg)
-class TagPatternTranslator(object):
-    def __init__(self, pattern_translators):
-        self.pattern_translators = pattern_translators
-
-    def translate(self, tag, msg):
-        for pattern in self.pattern_translators:
-            match = re.compile(pattern, re.IGNORECASE).match(tag)
-            if match:
-                translator = self.pattern_translators[pattern]
-                if callable(translator):
-                    return translator(tag, msg)
-                else:
-                    return translator.translate(tag, msg)
-        return None
-
-
-# 字符串匹配tag  例子参考 BluetoothTranslator
-# :param str_translators是数组[tag, fun(msg)] fun方法参数是 (msg)
-class TagStrTranslator(object):
-    def __init__(self, str_translators):
-        self.str_translators = str_translators
-
-    def translate(self, tag, msg):
-        if tag in self.str_translators:
-            translator = self.str_translators[tag]
-            if callable(translator):
-                return translator(msg)
-            else:
-                return translator.translate(msg)
-        return None
-
-
-class SecStrTagTranslator(TagStrTranslator):
-    """
-    :param father表示上一级tag
-    :param tag_from_str_fun 从字符串解析tag的方法
-    :param tag_translators 用来解析二级tag的translator 是个数组必须是TagStrTranslator|TagPatternTranslator
-    """
-
-    def __init__(self, father, tag_from_str_fun, tag_translators):
-        super().__init__({
-            father: self.translate_new_tag
-        })
-        self.tag_from_str_fun = tag_from_str_fun
-        self.tag_translators = tag_translators
-
-    def translate_new_tag(self, msg):
-        log = self.tag_from_str_fun(msg)
-        if log:
-            sec_tag = log.group("tag")
-            sec_msg = log.group("msg")
-            for translator in self.tag_translators:
-                result = translator.translate(sec_tag, sec_msg)
-                if result:
-                    return result
-        return None
-
-
-class StringTranslator(object):
-    def __init__(self, tag_translators=None):
-        # 这里是 TagStrTranslator
-        if tag_translators is None:
-            tag_translators = []
-        self.tag_translators = tag_translators
-
-    def translate(self, string):
-        # 系统日志
-        # 03-21 21:31:45.534 12980 15281 I ActivityManager   : START 0 ooooo:
-        log = self.tag_from_str(string)
-        if log:
-            tag = log.group("tag")
-            msg = log.group("msg")
-            time = log.group("time")
-            try:
-                pid = log.group("pid")
-            except:
-                pid = "0000"
-            for translator in self.tag_translators:
-                show = translator.translate(tag, msg)
-                if show:
-                    show.time = time
-                    show.oring = msg
-                    show.process = pid
-                    if pids.count(pid) == 0:
-                        pids.append(pid)
-                    return show
-        return None
-
-    @abstractmethod
-    def tag_from_str(self, string):
-        pass
-
-
-class SysLogTranslator(StringTranslator):
-    def tag_from_str(self, string):
-        # 04-29 10:01:16.788935  1848  2303 D OGG_Detector: D:done mCurrStatus: 0
-        return re.search(r"(?P<time>\d+.*\.\d{3,}) +(?P<pid>\d+).* [A-Z] (?P<tag>.*?) *:(?P<msg>.*)", string)
-
-
-class LogcatTranslator(StringTranslator):
-
-    def tag_from_str(self, string):
-        pass
-
-
-if __name__ == '__main__':
-    result = re.search("device: (.*?),", "connect() - device: 34:47:9A:31:52:CF, auto: false, eattSupport: false")
-    print(result.group(1))
-    result = re.search("(?<=\*).*", "onReCreateBond: 24:*:35:06")
-
-    # (?<=A).+?(?=B) 匹配规则A和B之间的元素 不包括A和B
-    #
-    print(result.group())
-
-    str = "04-29 10:01:16.788935  1848  2303 D OGG_Detector: D:done mCurrStatus: 0"
-    f = re.search(r"(?P<time>\d+.*\.\d{3,}) +(?P<pid>\d+).* [A-Z] (?P<tag>.*?) *:(?P<msg>.*)", str)
-    print(f.group("pid"))
-    print(f.group("tag"))
+import re
+from abc import abstractmethod
+
+from log_translate.gloable import pids
+
+
+# 通过正则表达式匹配tag解析
+# :param pattern_translators 是数据[tag,fun(tag, msg)] fun参数必须是(tag, msg)
+class TagPatternTranslator(object):
+    def __init__(self, pattern_translators):
+        self.pattern_translators = pattern_translators
+
+    def translate(self, tag, msg):
+        for pattern in self.pattern_translators:
+            match = re.compile(pattern, re.IGNORECASE).match(tag)
+            if match:
+                translator = self.pattern_translators[pattern]
+                if callable(translator):
+                    return translator(tag, msg)
+                else:
+                    return translator.translate(tag, msg)
+        return None
+
+
+# 字符串匹配tag  例子参考 BluetoothTranslator
+# :param str_translators是数组[tag, fun(msg)] fun方法参数是 (msg)
+class TagStrTranslator(object):
+    def __init__(self, str_translators):
+        self.str_translators = str_translators
+
+    def translate(self, tag, msg):
+        if tag in self.str_translators:
+            translator = self.str_translators[tag]
+            if callable(translator):
+                return translator(msg)
+            else:
+                return translator.translate(msg)
+        return None
+
+
+class SecStrTagTranslator(TagStrTranslator):
+    """
+    :param father表示上一级tag
+    :param tag_from_str_fun 从字符串解析tag的方法
+    :param tag_translators 用来解析二级tag的translator 是个数组必须是TagStrTranslator|TagPatternTranslator
+    """
+
+    def __init__(self, father, tag_from_str_fun, tag_translators):
+        super().__init__({
+            father: self.translate_new_tag
+        })
+        self.tag_from_str_fun = tag_from_str_fun
+        self.tag_translators = tag_translators
+
+    def translate_new_tag(self, msg):
+        log = self.tag_from_str_fun(msg)
+        if log:
+            sec_tag = log.group("tag")
+            sec_msg = log.group("msg")
+            for translator in self.tag_translators:
+                result = translator.translate(sec_tag, sec_msg)
+                if result:
+                    return result
+        return None
+
+
+class StringTranslator(object):
+    def __init__(self, tag_translators=None):
+        # 这里是 TagStrTranslator
+        if tag_translators is None:
+            tag_translators = []
+        self.tag_translators = tag_translators
+
+    def translate(self, string):
+        # 系统日志
+        # 03-21 21:31:45.534 12980 15281 I ActivityManager   : START 0 ooooo:
+        log = self.tag_from_str(string)
+        if log:
+            tag = log.group("tag")
+            msg = log.group("msg")
+            time = log.group("time")
+            try:
+                pid = log.group("pid")
+            except:
+                pid = "0000"
+            for translator in self.tag_translators:
+                show = translator.translate(tag, msg)
+                if show:
+                    show.time = time
+                    show.oring = msg
+                    show.process = pid
+                    if pids.count(pid) == 0:
+                        pids.append(pid)
+                    return show
+        return None
+
+    @abstractmethod
+    def tag_from_str(self, string):
+        pass
+
+
+class SysLogTranslator(StringTranslator):
+    def tag_from_str(self, string):
+        # 04-29 10:01:16.788935  1848  2303 D OGG_Detector: D:done mCurrStatus: 0
+        return re.search(r"(?P<time>\d+.*\.\d{3,}) +(?P<pid>\d+).* [A-Z] (?P<tag>.*?) *:(?P<msg>.*)", string)
+
+
+class LogcatTranslator(StringTranslator):
+
+    def tag_from_str(self, string):
+        pass
+
+
+if __name__ == '__main__':
+    result = re.search("device: (.*?),", "connect() - device: 34:47:9A:31:52:CF, auto: false, eattSupport: false")
+    print(result.group(1))
+    result = re.search("(?<=\*).*", "onReCreateBond: 24:*:35:06")
+
+    # (?<=A).+?(?=B) 匹配规则A和B之间的元素 不包括A和B
+    #
+    print(result.group())
+
+    str = "04-29 10:01:16.788935  1848  2303 D OGG_Detector: D:done mCurrStatus: 0"
+    f = re.search(r"(?P<time>\d+.*\.\d{3,}) +(?P<pid>\d+).* [A-Z] (?P<tag>.*?) *:(?P<msg>.*)", str)
+    print(f.group("pid"))
+    print(f.group("tag"))
```

### Comparing `LogTranslate-1.0/log_translate/read_log_file.py` & `LogTranslate-1.1/log_translate/read_log_file.py`

 * *Ordering differences only*

 * *Files 22% similar despite different names*

```diff
@@ -1,82 +1,82 @@
-# This is a sample Python script.
-import importlib
-import os
-import threading
-import traceback
-from collections import deque
-from os import cpu_count
-
-from rx.subject import Subject
-
-from log_translate.config_default import translators
-from log_translate.data_struct import Log
-
-
-# //必须定义在使用者前面
-class LogReader(object):
-    def __init__(self,
-                 chunk_size=1024 * 1024 * 10,
-                 process_num_for_log_parsing=cpu_count()):
-        self.log_unparsed_queue = deque()  # 用于存储未解析日志
-        self.log_line_parsed_queue = deque()  # 用于存储已解析日志行
-        self.is_all_files_read = False  # 标识是否已读取所有日志文件
-        self.process_num_for_log_parsing = process_num_for_log_parsing  # 并发解析日志文件进程数
-        self.chunk_size = chunk_size  # 每次读取日志的日志块大小
-        self.files_read_list = []  # 存放已读取日志文件
-        self.log_parsing_finished = False  # 标识是否完成日志解析
-        self.log_stream = Subject()
-        # 翻译
-        try:
-            config = importlib.import_module("config")
-            self.log_translators = getattr(config, "translators")
-        except:
-            traceback.print_exc()
-            self.log_translators = translators
-
-    @staticmethod
-    def readFile(path="."):
-        with open(path, "rb") as f:
-            for fline in f:
-                yield fline
-            f.close()
-
-    def analyze(self, path):
-        # 分行读取数据
-        for datas in self.readFile(path):
-            # 对日志进行翻译
-            try:
-                str = datas.decode('ISO-8859-1').strip()
-                for translator in self.log_translators:
-                    try:
-                        result = translator.translate(str)
-                        # 翻译后的日志存起来
-                        if result:
-                            print(result)
-                            result.origin = str
-                            self.log_stream.on_next(result)
-                            break
-                    except Exception as e:
-                        print('日志翻译发生异常：', e)
-                        print(str)
-                        traceback.print_exc()
-                        raise e
-            except Exception as e:
-                print('文件解析发生异常：', e)
-                traceback.print_exc()
-                raise e
-        self.log_stream.on_next(Log(translated=None))
-
-    def concurrency(self, log_files):
-        # 多线程 解析
-        for file in log_files:
-            abspath = os.path.abspath(file)
-            print(abspath)
-            threading_thread = threading.Thread(target=self.analyze, name="read_log_file", args=(abspath,))
-            threading_thread.start()
-
-
-# Press the green button in the gutter to run the script.
-if __name__ == '__main__':
-    parse_log = LogReader()
-    # parse_log.concurrency(["D:\\main_log_1__2023_0429_100141"])
-    parse_log.concurrency(["./main_log_1__2023_0429_100141"])
+# This is a sample Python script.
+import importlib
+import os
+import threading
+import traceback
+from collections import deque
+from os import cpu_count
+
+from rx.subject import Subject
+
+from log_translate.config_default import translators
+from log_translate.data_struct import Log
+
+
+# //必须定义在使用者前面
+class LogReader(object):
+    def __init__(self,
+                 chunk_size=1024 * 1024 * 10,
+                 process_num_for_log_parsing=cpu_count()):
+        self.log_unparsed_queue = deque()  # 用于存储未解析日志
+        self.log_line_parsed_queue = deque()  # 用于存储已解析日志行
+        self.is_all_files_read = False  # 标识是否已读取所有日志文件
+        self.process_num_for_log_parsing = process_num_for_log_parsing  # 并发解析日志文件进程数
+        self.chunk_size = chunk_size  # 每次读取日志的日志块大小
+        self.files_read_list = []  # 存放已读取日志文件
+        self.log_parsing_finished = False  # 标识是否完成日志解析
+        self.log_stream = Subject()
+        # 翻译
+        try:
+            config = importlib.import_module("config")
+            self.log_translators = getattr(config, "translators")
+        except:
+            traceback.print_exc()
+            self.log_translators = translators
+
+    @staticmethod
+    def readFile(path="."):
+        with open(path, "rb") as f:
+            for fline in f:
+                yield fline
+            f.close()
+
+    def analyze(self, path):
+        # 分行读取数据
+        for datas in self.readFile(path):
+            # 对日志进行翻译
+            try:
+                str = datas.decode('ISO-8859-1').strip()
+                for translator in self.log_translators:
+                    try:
+                        result = translator.translate(str)
+                        # 翻译后的日志存起来
+                        if result:
+                            print(result)
+                            result.origin = str
+                            self.log_stream.on_next(result)
+                            break
+                    except Exception as e:
+                        print('日志翻译发生异常：', e)
+                        print(str)
+                        traceback.print_exc()
+                        raise e
+            except Exception as e:
+                print('文件解析发生异常：', e)
+                traceback.print_exc()
+                raise e
+        self.log_stream.on_next(Log(translated=None))
+
+    def concurrency(self, log_files):
+        # 多线程 解析
+        for file in log_files:
+            abspath = os.path.abspath(file)
+            print(abspath)
+            threading_thread = threading.Thread(target=self.analyze, name="read_log_file", args=(abspath,))
+            threading_thread.start()
+
+
+# Press the green button in the gutter to run the script.
+if __name__ == '__main__':
+    parse_log = LogReader()
+    # parse_log.concurrency(["D:\\main_log_1__2023_0429_100141"])
+    parse_log.concurrency(["./main_log_1__2023_0429_100141"])
```

### Comparing `LogTranslate-1.0/log_translate/res/log_logo.ico` & `LogTranslate-1.1/log_translate/res/log_logo.ico`

 * *Files identical despite different names*

### Comparing `LogTranslate-1.0/log_translate/ui_pyqt6.py` & `LogTranslate-1.1/log_translate/ui_pyside2.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,165 +1,181 @@
-import sys
-import traceback
-
-import keyboard as keyboard
-import pkg_resources
-from PyQt6.QtGui import QAction, QBrush, QColor, QIcon
-from PyQt6.QtWidgets import QApplication, QMainWindow, QListWidget, QListWidgetItem, QAbstractItemView
-
-from log_translate.data_struct import Log, Level
-from log_translate.read_log_file import LogReader
-
-
-class PyQt6Window(QMainWindow):
-    def __init__(self):
-        super().__init__()
-        self.setWindowTitle("🤖日志解析")
-        ico = pkg_resources.resource_filename('log_translate', 'res/log_logo.ico')
-        self.setWindowIcon(QIcon(ico))
-        self.list_widget = QListWidget()
-        self.list_widget.setSelectionMode(QAbstractItemView.SelectionMode.NoSelection)
-        self.setCentralWidget(self.list_widget)
-        self.setAcceptDrops(True)
-        self.create_menu()
-        self.log_reader = LogReader()
-        self.data_item_logs = {
-            Level.d.value: [],
-            Level.i.value: [],
-            Level.w.value: [],
-            Level.e.value: [],
-        }
-        self.show_level = Level.e.value
-        self.show_origin = False
-        self.log_reader.log_stream.subscribe_(lambda log: {
-            self.collect_logs_and_show(log),
-        })
-        self.list_widget.addItem("💫 💭 把文件拖入到窗口开始解析日志 💭 💫")
-
-    def create_menu(self):
-        menu_bar = self.menuBar()
-        action = menu_bar.addMenu("操作")
-
-        filter_action = QAction("Level_D", self)
-        filter_action.setShortcut('Ctrl+D')
-        filter_action.triggered.connect(self.filter_logs_d)
-        action.addAction(filter_action)
-
-        filter_action = QAction("Level_I", self)
-        filter_action.setShortcut('Ctrl+I')
-        filter_action.triggered.connect(self.filter_logs_i)
-        action.addAction(filter_action)
-
-        filter_action = QAction("Level_W", self)
-        filter_action.setShortcut('Ctrl+W')
-        filter_action.triggered.connect(self.filter_logs_w)
-        action.addAction(filter_action)
-
-        filter_action = QAction("Level_E", self)
-        filter_action.setShortcut('Ctrl+E')
-        filter_action.triggered.connect(self.filter_logs_e)
-        action.addAction(filter_action)
-
-        keyboard.add_hotkey('Ctrl+O', self.log_show_origin)
-
-    def dragEnterEvent(self, event):
-        if event.mimeData().hasUrls():
-            if not self.isMaximized():
-                self.showMaximized()
-            event.accept()
-        else:
-            event.ignore()
-
-    def dropEvent(self, event):
-        for url in event.mimeData().urls():
-            file = url.toLocalFile()
-            # f-string 可以使用 {变量} 语法将表达式嵌入到字符串中
-            self.list_widget.clear()
-            self.list_widget.addItem(f"\n👇👇👇👇👇👇👇👇 {file} 💥 日志解析如下 👇👇👇👇👇👇👇👇")
-            try:
-                self.log_reader.concurrency([file])
-            except:
-                item = QListWidgetItem(traceback.format_exc())
-                item.setForeground(QBrush(QColor("red")))
-                self.list_widget.addItem(item)
-            # for i in range(100):
-
-    def show_log_on_finish(self):
-        if len(self.data_item_logs[self.show_level]) == 0:
-            for level in range(self.show_level - 1, 0, -1):
-                if len(self.data_item_logs[level]) > 0:
-                    self.filter_logs(Level(level))
-                    return None
-
-    def collect_logs_and_show(self, log: Log):
-        if log.translated is None:
-            # 文件读取到最后
-            self.show_log_on_finish()
-            return
-
-        for log_level in self.data_item_logs:
-            if log.level.value >= log_level:
-                self.data_item_logs[log_level].append(log)
-        if log.level.value >= self.show_level:
-            self.list_widget.addItem(self.log_to_list_item(log))
-
-    def log_to_list_item(self, log: Log):
-        if self.show_origin:
-            log_str = log.str_with_origin()
-        else:
-            log_str = log.__str__()
-        item = QListWidgetItem(log_str)
-        item.setForeground(QBrush(QColor(log.level.color())))
-        return item
-
-    def filter_logs_d(self):
-        self.filter_logs(Level.d)
-
-    def filter_logs_i(self):
-        self.filter_logs(Level.i)
-
-    def filter_logs_w(self):
-        self.filter_logs(Level.w)
-
-    def filter_logs_e(self):
-        self.filter_logs(Level.e)
-
-    def log_show_origin(self):
-        self.show_origin = not self.show_origin
-        self.filter_logs(Level(self.show_level))
-
-    def filter_logs(self, level: Level):
-        self.show_level = level.value
-        first = self.list_widget.item(0).text()
-        self.list_widget.clear()
-        self.list_widget.addItem(first)
-        show_logs = self.data_item_logs[self.show_level]
-        for log in show_logs:
-            self.list_widget.addItem(self.log_to_list_item(log))
-
-
-if __name__ == "__main__":
-    app = QApplication(sys.argv)
-    window = PyQt6Window()
-    window.show()
-    sys.exit(app.exec())
-
-#  打包命令
-# pyinstaller --name=log_translator --onefile --windowed ui_pyqt6.py
-# -F, --onefile   产生单个的可执行文件
-# -n NAME, --name NAME   指定项目（产生的 spec）名字。如果省略该选项，那么第一个脚本的主文件名将作为 spec 的名字
-# -w, --windowed, --noconsole   指定程序运行时不显示命令行窗口（仅对 Windows 有效）
-# -i <FILE.ico>, --icon <FILE.ico>  指定icon
-
-#  打包执行以下命令
-# pyinstaller -n log_translator --hidden-import config -F -w -i tools.ico ui_pyqt6.py
-# --hidden-import 设置导入要动态加载的类 因为没被引用 所以不会导入需要手动设置
-
-# pip install PyInstaller
-# pyinstaller --name=<your_exe_name> --onefile --windowed --add-data "<your_data_folder>;<your_data_folder>" <your_script_name>.py
-
-# 上述命令中的选项说明：
-# --name: 可执行文件名称。
-# --onefile: 将整个项目打包为一个单独的可执行文件。
-# --windowed: 隐藏控制台窗口，将打包的应用程序显示为GUI应用程序。
-# --add-data: 添加项目资源，支持文件夹和文件，前面是资源路径，后面是输出路径，用分号进行分割。
-# 执行上述命令后，会在项目目录下生成一个.spec文件，这个文件会告诉PyInstaller如何将项目打包成exe文件。
+import sys
+import traceback
+
+import keyboard as keyboard
+import pkg_resources
+from PySide6.QtGui import QIcon, QFont, QAction, QColor
+from PySide6.QtWidgets import QMainWindow, QListWidget, QAbstractItemView, QApplication, QListWidgetItem
+
+from log_translate.data_struct import Log, Level
+from log_translate.read_log_file import LogReader
+
+
+class PySide6Window(QMainWindow):
+    def __init__(self):
+        super().__init__()
+        self.setWindowTitle("🤖日志解析")
+        ico = pkg_resources.resource_filename('log_translate', 'res/log_logo.ico')
+        self.setWindowIcon(QIcon(ico))
+        self.list_widget = QListWidget()
+        self.list_widget.setSelectionMode(QAbstractItemView.SelectionMode.NoSelection)
+        self.setCentralWidget(self.list_widget)
+        self.setAcceptDrops(True)
+        self.create_menu()
+        self.log_reader = LogReader()
+        self.data_item_logs = {
+            Level.d.value: [],
+            Level.i.value: [],
+            Level.w.value: [],
+            Level.e.value: [],
+        }
+        self.show_level = Level.e.value
+        self.show_origin = False
+        self.log_reader.log_stream.subscribe_(lambda log: {
+            self.collect_logs_and_show(log),
+        })
+        self.list_widget.addItem("💫 💭 把文件拖入到窗口开始解析日志 💭 💫")
+
+    def create_menu(self):
+        menu_bar = self.menuBar()
+        action = menu_bar.addMenu("操作")
+
+        filter_action = QAction("Level_D", self)
+        filter_action.setShortcut('Ctrl+D')
+        filter_action.triggered.connect(self.filter_logs_d)
+        action.addAction(filter_action)
+
+        filter_action = QAction("Level_I", self)
+        filter_action.setShortcut('Ctrl+I')
+        filter_action.triggered.connect(self.filter_logs_i)
+        action.addAction(filter_action)
+
+        filter_action = QAction("Level_W", self)
+        filter_action.setShortcut('Ctrl+W')
+        filter_action.triggered.connect(self.filter_logs_w)
+        action.addAction(filter_action)
+
+        filter_action = QAction("Level_E", self)
+        filter_action.setShortcut('Ctrl+E')
+        filter_action.triggered.connect(self.filter_logs_e)
+        action.addAction(filter_action)
+
+        keyboard.add_hotkey('Ctrl+O', self.log_show_origin)
+        keyboard.add_hotkey('Ctrl+Up', self.font_zoom_in)
+        keyboard.add_hotkey('Ctrl+Down', self.font_zoom_out)
+
+    def dragEnterEvent(self, event):
+        if event.mimeData().hasUrls():
+            if not self.isMaximized():
+                self.showMaximized()
+            event.accept()
+        else:
+            event.ignore()
+
+    def dropEvent(self, event):
+        for url in event.mimeData().urls():
+            file = url.toLocalFile()
+            # f-string 可以使用 {变量} 语法将表达式嵌入到字符串中
+            self.list_widget.clear()
+            self.list_widget.addItem(f"\n👇👇👇👇👇👇👇👇 {file} 💥 日志解析如下 👇👇👇👇👇👇👇👇")
+            try:
+                self.log_reader.concurrency([file])
+            except:
+                item = QListWidgetItem(traceback.format_exc())
+                item.setForeground(QColor("red"))
+                self.list_widget.addItem(item)
+            # for i in range(100):
+
+    def show_log_on_finish(self):
+        if len(self.data_item_logs[self.show_level]) == 0:
+            for level in range(self.show_level - 1, 0, -1):
+                if len(self.data_item_logs[level]) > 0:
+                    self.filter_logs(Level(level))
+                    return None
+
+    def collect_logs_and_show(self, log: Log):
+        if log.translated is None:
+            # 文件读取到最后
+            self.show_log_on_finish()
+            return
+
+        for log_level in self.data_item_logs:
+            if log.level.value >= log_level:
+                self.data_item_logs[log_level].append(log)
+        if log.level.value >= self.show_level:
+            self.list_widget.addItem(self.log_to_list_item(log))
+
+    def log_to_list_item(self, log: Log):
+        if self.show_origin:
+            log_str = log.str_with_origin()
+        else:
+            log_str = log.__str__()
+        item = QListWidgetItem(log_str)
+        item.setForeground(QColor(log.level.color()))
+        return item
+
+    def filter_logs_d(self):
+        self.filter_logs(Level.d)
+
+    def filter_logs_i(self):
+        self.filter_logs(Level.i)
+
+    def filter_logs_w(self):
+        self.filter_logs(Level.w)
+
+    def filter_logs_e(self):
+        self.filter_logs(Level.e)
+
+    def log_show_origin(self):
+        self.show_origin = not self.show_origin
+        self.filter_logs(Level(self.show_level))
+
+    # 字体缩小
+    def font_zoom_out(self):
+        font: QFont = self.list_widget.font()
+        new_font = QFont()
+        new_font.setPointSize(font.pointSize() - 1)
+        self.list_widget.setFont(new_font)
+
+    # 字体放大
+    def font_zoom_in(self):
+        font: QFont = self.list_widget.font()
+        new_font = QFont()
+        new_font.setPointSize(font.pointSize() + 1)
+        self.list_widget.setFont(new_font)
+
+    def filter_logs(self, level: Level):
+        self.show_level = level.value
+        first = self.list_widget.item(0).text()
+        self.list_widget.clear()
+        self.list_widget.addItem(first)
+        show_logs = self.data_item_logs[self.show_level]
+        for log in show_logs:
+            self.list_widget.addItem(self.log_to_list_item(log))
+
+
+if __name__ == "__main__":
+    app = QApplication(sys.argv)
+    window = PySide6Window()
+    window.show()
+    sys.exit(app.exec())
+
+#  打包命令
+# pyinstaller --name=log_translator --onefile --windowed ui_PySide6.py
+# -F, --onefile   产生单个的可执行文件
+# -n NAME, --name NAME   指定项目（产生的 spec）名字。如果省略该选项，那么第一个脚本的主文件名将作为 spec 的名字
+# -w, --windowed, --noconsole   指定程序运行时不显示命令行窗口（仅对 Windows 有效）
+# -i <FILE.ico>, --icon <FILE.ico>  指定icon
+
+#  打包执行以下命令
+# pyinstaller -n log_translator --hidden-import config -F -w -i tools.ico ui_PySide6.py
+# --hidden-import 设置导入要动态加载的类 因为没被引用 所以不会导入需要手动设置
+
+# pip install PyInstaller
+# pyinstaller --name=<your_exe_name> --onefile --windowed --add-data "<your_data_folder>;<your_data_folder>" <your_script_name>.py
+
+# 上述命令中的选项说明：
+# --name: 可执行文件名称。
+# --onefile: 将整个项目打包为一个单独的可执行文件。
+# --windowed: 隐藏控制台窗口，将打包的应用程序显示为GUI应用程序。
+# --add-data: 添加项目资源，支持文件夹和文件，前面是资源路径，后面是输出路径，用分号进行分割。
+# 执行上述命令后，会在项目目录下生成一个.spec文件，这个文件会告诉PyInstaller如何将项目打包成exe文件。
```

### Comparing `LogTranslate-1.0/setup.py` & `LogTranslate-1.1/setup.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,54 +1,54 @@
-from setuptools import setup, find_packages
-
-readme_path = 'README.md'
-# PACKAGE_NAME主要在使用的时候用到 pkg_resources.resource_filename('log_translate', 'res/log_logo.ico')
-PACKAGE_NAME = 'log_translate'
-# 需要写清楚路径
-ICON_PATH = 'res/*.ico'
-
-setup(
-    name='LogTranslate',
-    version='1.0',
-    author='5hmlA',
-    author_email='jonas.jzy@gmail.com',
-    # 指定运行时需要的Python版本
-    python_requires='>=3.6',
-    # 找到当前目录下有哪些包 当前(setup.py)目录下的文件夹 当前目录的py不包含 打包的是把所有代码放一个文件夹下文件名为库名字
-    packages=find_packages(),
-    # 配置readme
-    long_description=open(readme_path, encoding='utf-8').read(),
-    long_description_content_type='text/markdown',
-    license="MIT Licence",
-    # 配置要打包的文件
-    package_data={PACKAGE_NAME: [ICON_PATH]},
-    # 手动指定
-    # packages=['log_translate', 'log_translate/business'],
-    classifiers=[
-        'Development Status :: 3 - Alpha',
-        'Intended Audience :: Developers',
-        'License :: OSI Approved :: MIT License',
-        'Programming Language :: Python :: 3.8',
-        'Programming Language :: Python :: 3.9',
-        'Programming Language :: Python :: 3.10',
-        'Programming Language :: Python :: 3.11',
-    ],
-    install_requires=[
-        # 只包含包名。 这种形式只检查包的存在性，不检查版本。 方便，但不利于控制风险。
-        'PyQt6',
-        'PySide6',
-        'rx',
-        'typer',
-        'keyboard',
-        # 'setuptools==38.2.4'，指定版本。 这种形式把风险降到了最低，确保了开发、测试与部署的版本一致，不会出现意外。 缺点是不利于更新，每次更新都需要改动代码
-    ],
-    keywords='tools log translate',
-    url='https://github.com/5hmlA/PyTools',
-    description='A Python library for translate log from log files'
-)
-
-# python -m pip install --upgrade twine
-# python setup.py sdist bdist_wheel
-
-# 发布到测试地址
-# twine upload --repository testpypi dist/*
-# twine upload dist/*
+from setuptools import setup, find_packages
+
+readme_path = 'README.md'
+# PACKAGE_NAME主要在使用的时候用到 pkg_resources.resource_filename('log_translate', 'res/log_logo.ico')
+PACKAGE_NAME = 'log_translate'
+# 需要写清楚路径
+ICON_PATH = 'res/*.ico'
+
+setup(
+    name='LogTranslate',
+    version='1.1',
+    author='5hmlA',
+    author_email='jonas.jzy@gmail.com',
+    # 指定运行时需要的Python版本
+    python_requires='>=3.6',
+    # 找到当前目录下有哪些包 当前(setup.py)目录下的文件夹 当前目录的py不包含 打包的是把所有代码放一个文件夹下文件名为库名字
+    packages=find_packages(),
+    # 配置readme
+    long_description=open(readme_path, encoding='utf-8').read(),
+    long_description_content_type='text/markdown',
+    license="MIT Licence",
+    # 配置要打包的文件
+    package_data={PACKAGE_NAME: [ICON_PATH]},
+    # 手动指定
+    # packages=['log_translate', 'log_translate/business'],
+    classifiers=[
+        'Development Status :: 3 - Alpha',
+        'Intended Audience :: Developers',
+        'License :: OSI Approved :: MIT License',
+        'Programming Language :: Python :: 3.8',
+        'Programming Language :: Python :: 3.9',
+        'Programming Language :: Python :: 3.10',
+        'Programming Language :: Python :: 3.11',
+    ],
+    install_requires=[
+        # 只包含包名。 这种形式只检查包的存在性，不检查版本。 方便，但不利于控制风险。
+        'PyQt6',
+        'PySide6',
+        'rx',
+        'typer',
+        'keyboard',
+        # 'setuptools==38.2.4'，指定版本。 这种形式把风险降到了最低，确保了开发、测试与部署的版本一致，不会出现意外。 缺点是不利于更新，每次更新都需要改动代码
+    ],
+    keywords='tools log translate',
+    url='https://github.com/5hmlA/PyTools',
+    description='A Python library for translate log from log files'
+)
+
+# python -m pip install --upgrade twine
+# python setup.py sdist bdist_wheel
+
+# 发布到测试地址
+# twine upload --repository testpypi dist/*
+# twine upload dist/*
```

