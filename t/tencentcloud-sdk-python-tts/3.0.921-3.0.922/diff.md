# Comparing `tmp/tencentcloud-sdk-python-tts-3.0.921.tar.gz` & `tmp/tencentcloud-sdk-python-tts-3.0.922.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/tencentcloud-sdk-python-tts-3.0.921.tar", last modified: Mon Jun 26 00:36:35 2023, max compression
+gzip compressed data, was "dist/tencentcloud-sdk-python-tts-3.0.922.tar", last modified: Tue Jun 27 00:36:56 2023, max compression
```

## Comparing `tencentcloud-sdk-python-tts-3.0.921.tar` & `tencentcloud-sdk-python-tts-3.0.922.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/
--rw-r--r--   0 root         (0) root         (0)       88 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud/
--rw-r--r--   0 root         (0) root         (0)      630 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud/tts/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud/tts/v20190823/
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud/tts/v20190823/__init__.py
--rw-r--r--   0 root         (0) root         (0)    15193 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud/tts/v20190823/models.py
--rw-r--r--   0 root         (0) root         (0)     5910 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud/tts/v20190823/tts_client.py
--rw-r--r--   0 root         (0) root         (0)     5572 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud/tts/v20190823/errorcodes.py
--rw-r--r--   0 root         (0) root         (0)        0 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud/tts/__init__.py
--rw-r--r--   0 root         (0) root         (0)      737 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/README.rst
--rw-r--r--   0 root         (0) root         (0)     1659 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud_sdk_python_tts.egg-info/
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud_sdk_python_tts.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)      445 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud_sdk_python_tts.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)     1659 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud_sdk_python_tts.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       13 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/tencentcloud_sdk_python_tts.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)     1006 2023-06-26 00:36:35.000000 tencentcloud-sdk-python-tts-3.0.921/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/
+-rw-r--r--   0 root         (0) root         (0)       88 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud/
+-rw-r--r--   0 root         (0) root         (0)      630 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud/tts/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud/tts/v20190823/
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud/tts/v20190823/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    15556 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud/tts/v20190823/models.py
+-rw-r--r--   0 root         (0) root         (0)     5910 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud/tts/v20190823/tts_client.py
+-rw-r--r--   0 root         (0) root         (0)     5572 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud/tts/v20190823/errorcodes.py
+-rw-r--r--   0 root         (0) root         (0)        0 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud/tts/__init__.py
+-rw-r--r--   0 root         (0) root         (0)      737 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/README.rst
+-rw-r--r--   0 root         (0) root         (0)     1659 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud_sdk_python_tts.egg-info/
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud_sdk_python_tts.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)      445 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud_sdk_python_tts.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)     1659 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud_sdk_python_tts.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       13 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/tencentcloud_sdk_python_tts.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)     1006 2023-06-27 00:36:56.000000 tencentcloud-sdk-python-tts-3.0.922/setup.py
```

### Comparing `tencentcloud-sdk-python-tts-3.0.921/tencentcloud/__init__.py` & `tencentcloud-sdk-python-tts-3.0.922/tencentcloud/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -10,8 +10,8 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
 
-__version__ = '3.0.921'
+__version__ = '3.0.922'
```

### Comparing `tencentcloud-sdk-python-tts-3.0.921/tencentcloud/tts/v20190823/models.py` & `tencentcloud-sdk-python-tts-3.0.922/tencentcloud/tts/v20190823/models.py`

 * *Files 10% similar despite different names*

```diff
@@ -27,15 +27,15 @@
         r"""
         :param Text: 合成语音的源文本，按UTF-8编码统一计算，最多支持10万字符
         :type Text: str
         :param ModelType: 模型类型，1-默认模型。
         :type ModelType: int
         :param Volume: 音量大小，范围：[0，10]，分别对应11个等级的音量，默认为0，代表正常音量。没有静音选项。
         :type Volume: float
-        :param Speed: 语速，范围：[-2，2]，分别对应不同语速：<li>-2代表0.6倍</li><li>-1代表0.8倍</li><li>0代表1.0倍（默认）</li><li>1代表1.2倍</li><li>2代表1.5倍</li>如果需要更细化的语速，可以保留小数点后一位，例如0.5 1.1 1.8等。<br>
+        :param Speed: 语速，范围：[-2，2]，分别对应不同语速：<li>-2代表0.6倍</li><li>-1代表0.8倍</li><li>0代表1.0倍（默认）</li><li>1代表1.2倍</li><li>2代表1.5倍</li>如果需要更细化的语速，可以保留小数点后 2 位，例如0.5 1.1 1.8等。<br>参数值与实际语速转换，可参考[代码示例](https://sdk-1300466766.cos.ap-shanghai.myqcloud.com/sample/speed_sample.tar.gz)
         :type Speed: float
         :param ProjectId: 项目id，用户自定义，默认为0。
         :type ProjectId: int
         :param VoiceType: 音色 ID，包括标准音色与精品音色，精品音色拟真度更高，价格不同于标准音色，请参见[购买指南](https://cloud.tencent.com/document/product/1073/34112)。完整的音色 ID 列表请参见[音色列表](https://cloud.tencent.com/document/product/1073/92668)。
         :type VoiceType: int
         :param PrimaryLanguage: 主语言类型：<li>1-中文（默认）</li><li>2-英文</li>
         :type PrimaryLanguage: int
@@ -271,15 +271,15 @@
         :param Text: 合成语音的源文本，按UTF-8编码统一计算。
 中文最大支持150个汉字（全角标点符号算一个汉字）；英文最大支持500个字母（半角标点符号算一个字母）。
         :type Text: str
         :param SessionId: 一次请求对应一个SessionId，会原样返回，建议传入类似于uuid的字符串防止重复。
         :type SessionId: str
         :param Volume: 音量大小，范围：[0，10]，分别对应11个等级的音量，默认为0，代表正常音量。没有静音选项。
         :type Volume: float
-        :param Speed: 语速，范围：[-2，6]，分别对应不同语速：<li>-2代表0.6倍</li><li>-1代表0.8倍</li><li>0代表1.0倍（默认）</li><li>1代表1.2倍</li><li>2代表1.5倍</li><li>6代表2.5倍</li>如果需要更细化的语速，可以保留小数点后一位，例如0.5 1.1 1.8等。<br>
+        :param Speed: 语速，范围：[-2，6]，分别对应不同语速：<li>-2代表0.6倍</li><li>-1代表0.8倍</li><li>0代表1.0倍（默认）</li><li>1代表1.2倍</li><li>2代表1.5倍</li><li>6代表2.5倍</li>如果需要更细化的语速，可以保留小数点后 2 位，例如0.5 1.1 1.8等。<br>参数值与实际语速转换，可参考[代码示例](https://sdk-1300466766.cos.ap-shanghai.myqcloud.com/sample/speed_sample.tar.gz)
         :type Speed: float
         :param ProjectId: 项目id，用户自定义，默认为0。
         :type ProjectId: int
         :param ModelType: 模型类型，1-默认模型。
         :type ModelType: int
         :param VoiceType: 音色 ID，包括标准音色与精品音色，精品音色拟真度更高，价格不同于标准音色，请参见[购买指南](https://cloud.tencent.com/document/product/1073/34112)。完整的音色 ID 列表请参见[音色列表](https://cloud.tencent.com/document/product/1073/92668)。
         :type VoiceType: int
@@ -289,15 +289,15 @@
         :type SampleRate: int
         :param Codec: 返回音频格式，可取值：wav（默认），mp3，pcm
         :type Codec: str
         :param EnableSubtitle: 是否开启时间戳功能，默认为false。
         :type EnableSubtitle: bool
         :param SegmentRate: 断句敏感阈值，默认值为：0，取值范围：[0,1,2]。该值越大越不容易断句，模型会更倾向于仅按照标点符号断句。此参数建议不要随意调整，可能会影响合成效果。
         :type SegmentRate: int
-        :param EmotionCategory: 控制合成音频的情感，仅支持多情感音色使用。取值: neutral(中性)、sad(悲伤)、happy(高兴)、angry(生气)、fear(恐惧)、news(新闻)、story(故事)、radio(广播)、poetry(诗歌)、call(客服)
+        :param EmotionCategory: 控制合成音频的情感，仅支持多情感音色使用。取值: neutral(中性)、sad(悲伤)、happy(高兴)、angry(生气)、fear(恐惧)、news(新闻)、story(故事)、radio(广播)、poetry(诗歌)、call(客服)、撒娇(sajiao)、厌恶(disgusted)、震惊(amaze)、平静(peaceful)、兴奋(exciting)
         :type EmotionCategory: str
         :param EmotionIntensity: 控制合成音频情感程度，取值范围为[50,200],默认为100；只有EmotionCategory不为空时生效；
         :type EmotionIntensity: int
         """
         self.Text = None
         self.SessionId = None
         self.Volume = None
```

### Comparing `tencentcloud-sdk-python-tts-3.0.921/tencentcloud/tts/v20190823/tts_client.py` & `tencentcloud-sdk-python-tts-3.0.922/tencentcloud/tts/v20190823/tts_client.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-tts-3.0.921/tencentcloud/tts/v20190823/errorcodes.py` & `tencentcloud-sdk-python-tts-3.0.922/tencentcloud/tts/v20190823/errorcodes.py`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-tts-3.0.921/README.rst` & `tencentcloud-sdk-python-tts-3.0.922/README.rst`

 * *Files identical despite different names*

### Comparing `tencentcloud-sdk-python-tts-3.0.921/PKG-INFO` & `tencentcloud-sdk-python-tts-3.0.922/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-tts
-Version: 3.0.921
+Version: 3.0.922
 Summary: Tencent Cloud Tts SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-tts-3.0.921/tencentcloud_sdk_python_tts.egg-info/PKG-INFO` & `tencentcloud-sdk-python-tts-3.0.922/tencentcloud_sdk_python_tts.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: tencentcloud-sdk-python-tts
-Version: 3.0.921
+Version: 3.0.922
 Summary: Tencent Cloud Tts SDK for Python
 Home-page: https://github.com/TencentCloud/tencentcloud-sdk-python
 Author: Tencent Cloud
 Author-email: tencentcloudapi@tencent.com
 License: Apache License 2.0
 Description: ============================
         Tencent Cloud SDK for Python
```

### Comparing `tencentcloud-sdk-python-tts-3.0.921/setup.py` & `tencentcloud-sdk-python-tts-3.0.922/setup.py`

 * *Files identical despite different names*

