# Comparing `tmp/labelprinterkit-0.5.8.tar.gz` & `tmp/labelprinterkit-0.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "labelprinterkit-0.5.8.tar", max compression
+gzip compressed data, was "labelprinterkit-0.6.0.tar", max compression
```

## Comparing `labelprinterkit-0.5.8.tar` & `labelprinterkit-0.6.0.tar`

### file list

```diff
@@ -1,14 +1,14 @@
--rw-r--r--   0        0        0    11337 2018-12-03 22:08:27.602616 labelprinterkit-0.5.8/LICENSE
--rw-r--r--   0        0        0     2247 2023-06-24 11:50:05.192647 labelprinterkit-0.5.8/README.md
--rw-r--r--   0        0        0      152 2023-06-27 15:15:38.729521 labelprinterkit-0.5.8/labelprinterkit/__init__.py
--rw-r--r--   0        0        0      306 2023-06-27 16:05:21.969699 labelprinterkit-0.5.8/labelprinterkit/backends/__init__.py
--rw-r--r--   0        0        0      681 2023-06-23 22:30:20.680886 labelprinterkit-0.5.8/labelprinterkit/backends/bluetooth.py
--rw-r--r--   0        0        0      793 2023-06-23 21:07:41.479689 labelprinterkit-0.5.8/labelprinterkit/backends/network.py
--rw-r--r--   0        0        0      802 2023-06-23 21:07:41.480689 labelprinterkit-0.5.8/labelprinterkit/backends/usb.py
--rw-r--r--   0        0        0     2452 2023-06-27 15:15:38.730521 labelprinterkit-0.5.8/labelprinterkit/constants.py
--rw-r--r--   0        0        0     1864 2023-06-24 12:23:33.620108 labelprinterkit-0.5.8/labelprinterkit/job.py
--rw-r--r--   0        0        0     7007 2023-06-27 19:07:39.583475 labelprinterkit-0.5.8/labelprinterkit/label.py
--rw-r--r--   0        0        0     2176 2023-06-23 21:07:41.480689 labelprinterkit-0.5.8/labelprinterkit/page.py
--rw-r--r--   0        0        0     8694 2023-06-24 12:43:54.859120 labelprinterkit-0.5.8/labelprinterkit/printers.py
--rw-r--r--   0        0        0      689 2023-06-27 19:07:39.584475 labelprinterkit-0.5.8/pyproject.toml
--rw-r--r--   0        0        0     3134 1970-01-01 00:00:00.000000 labelprinterkit-0.5.8/PKG-INFO
+-rw-r--r--   0        0        0    11337 2018-12-03 22:08:27.602616 labelprinterkit-0.6.0/LICENSE
+-rw-r--r--   0        0        0     2239 2023-06-28 07:52:50.330988 labelprinterkit-0.6.0/README.md
+-rw-r--r--   0        0        0      152 2023-06-27 15:15:38.729521 labelprinterkit-0.6.0/labelprinterkit/__init__.py
+-rw-r--r--   0        0        0      306 2023-06-27 16:05:21.969699 labelprinterkit-0.6.0/labelprinterkit/backends/__init__.py
+-rw-r--r--   0        0        0      797 2023-06-28 07:52:50.331988 labelprinterkit-0.6.0/labelprinterkit/backends/bluetooth.py
+-rw-r--r--   0        0        0     2410 2023-06-28 07:52:50.332988 labelprinterkit-0.6.0/labelprinterkit/backends/network.py
+-rw-r--r--   0        0        0      802 2023-06-23 21:07:41.480689 labelprinterkit-0.6.0/labelprinterkit/backends/usb.py
+-rw-r--r--   0        0        0     3023 2023-06-28 07:52:50.333988 labelprinterkit-0.6.0/labelprinterkit/constants.py
+-rw-r--r--   0        0        0     1551 2023-06-28 07:52:50.334988 labelprinterkit-0.6.0/labelprinterkit/job.py
+-rw-r--r--   0        0        0     7122 2023-06-28 07:52:50.334988 labelprinterkit-0.6.0/labelprinterkit/label.py
+-rw-r--r--   0        0        0     2176 2023-06-23 21:07:41.480689 labelprinterkit-0.6.0/labelprinterkit/page.py
+-rw-r--r--   0        0        0     9206 2023-06-28 07:52:50.335988 labelprinterkit-0.6.0/labelprinterkit/printers.py
+-rw-r--r--   0        0        0      873 2023-06-28 07:52:50.336988 labelprinterkit-0.6.0/pyproject.toml
+-rw-r--r--   0        0        0     3262 1970-01-01 00:00:00.000000 labelprinterkit-0.6.0/PKG-INFO
```

### Comparing `labelprinterkit-0.5.8/LICENSE` & `labelprinterkit-0.6.0/LICENSE`

 * *Files identical despite different names*

### Comparing `labelprinterkit-0.5.8/README.md` & `labelprinterkit-0.6.0/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 Labelprinterkit's simple layout engine can be used to create simple labels:
 
 ```python
 from labelprinterkit.backends.usb import PyUSBBackend
 from labelprinterkit.printers import P700
 from labelprinterkit.label import Label, Text, Box, Padding
 from labelprinterkit.job import Job
-from labelprinterkit.constants import MediaType, MediaSize
+from labelprinterkit.constants import MediaType, Media
 from labelprinterkit.page import Page
 from PIL import Image
 
 # Create text for the label
 
 text1 = Text(45, "First line", 'comic.ttf', padding=Padding(0, 0, 1, 0))
 text2 = Text(25, "Some text", 'comic.ttf')
@@ -25,15 +25,15 @@
 box1 = Box(45, text1)
 box2 = Box(25, text2, text3)
 
 # Create label with rows from above
 label = Label(box1, box2)
 
 # Create job with configuration and add label as page
-job = Job(MediaSize.W12, MediaType.LAMINATED_TAPE)
+job = Job(Media.W12, MediaType.LAMINATED_TAPE)
 job.add_page(label)
 
 # Create a page from a Pillow image and add it to the job
 image = Image.new("1", (70, 200), "white")
 page = Page.from_image(image)
 job.add_page(page)
```

### Comparing `labelprinterkit-0.5.8/labelprinterkit/backends/bluetooth.py` & `labelprinterkit-0.6.0/labelprinterkit/backends/bluetooth.py`

 * *Files 7% similar despite different names*

```diff
@@ -3,14 +3,16 @@
 except ImportError:
     serial = None
 from . import BiDirectionalBackend
 
 
 class BTSerialBackend(BiDirectionalBackend):
     def __init__(self, dev_path: str):
+        if serial is None:
+            raise RuntimeError('Bluetooth is not supported. Pacakge serial is missing.')
         dev = serial.Serial(
             dev_path,
             baudrate=9600,
             stopbits=serial.STOPBITS_ONE,
             parity=serial.PARITY_NONE,
             bytesize=8,
             dsrdtr=False,
```

### Comparing `labelprinterkit-0.5.8/labelprinterkit/backends/usb.py` & `labelprinterkit-0.6.0/labelprinterkit/backends/usb.py`

 * *Files identical despite different names*

### Comparing `labelprinterkit-0.5.8/labelprinterkit/constants.py` & `labelprinterkit-0.6.0/labelprinterkit/constants.py`

 * *Files 20% similar despite different names*

```diff
@@ -26,39 +26,49 @@
     WEAK_BATTERY = 0x0008
     HIGH_VOLTAGE_ADAPTER = 0x0040
     REPLACE_MEDIA = 0x0100
     COVER_OPEN = 0x1000
     OVERHEATING = 0x2000
 
 
+class MediaType(Enum):
+    NO_MEDIA = 0x00
+    LAMINATED_TAPE = 0x01
+    NON_LAMINATED_TAPE = 0x03
+    HEATSHRINK_TUBE_21 = 0x11
+    HEATSHRINK_TUBE_31 = 0x17
+    INCOMPATIBLE_TAPE = 0xFF
+
+
 class TapeInfo(NamedTuple):
     width: int
     length: int
     lmargin: int | None
     printarea: int | None
     rmargin: int | None
+    media_type: MediaType | None
 
 
-class MediaSize(Enum):
-    NO_MEDIA = TapeInfo(0, 0, None, None, None)
-    W3_5 = TapeInfo(4, 0, 52, 24, 52)
-    W6 = TapeInfo(6, 0, 48, 32, 48)
-    W9 = TapeInfo(9, 0, 39, 50, 39)
-    W12 = TapeInfo(12, 0, 29, 70, 29)
-    W18 = TapeInfo(18, 0, 8, 112, 8)
-    W24 = TapeInfo(24, 0, 0, 128, 0)
-
-
-class MediaType(Enum):
-    NO_MEDIA = 0x00
-    LAMINATED_TAPE = 0x01
-    NON_LAMINATED_TAPE = 0x03
-    HEATSHRINK_TUBE_21 = 0x11
-    HEATSHRINK_TUBE_31 = 0x17
-    INCOMPATIBLE_TAPE = 0xFF
+class Media(Enum):
+    UNSUPPORTED_MEDIA = TapeInfo(0, 0, None, None, None, None)
+    NO_MEDIA = TapeInfo(0, 0, None, None, None, None)
+    W3_5 = TapeInfo(4, 0, 52, 24, 52, MediaType.LAMINATED_TAPE)
+    W6 = TapeInfo(6, 0, 48, 32, 48, MediaType.LAMINATED_TAPE)
+    W9 = TapeInfo(9, 0, 39, 50, 39, MediaType.LAMINATED_TAPE)
+    W12 = TapeInfo(12, 0, 29, 70, 29, MediaType.LAMINATED_TAPE)
+    W18 = TapeInfo(18, 0, 8, 112, 8, MediaType.LAMINATED_TAPE)
+    W24 = TapeInfo(24, 0, 0, 128, 0, MediaType.LAMINATED_TAPE)
+
+    @classmethod
+    def get_media(cls, width: int, media_type: MediaType):
+        medias = [media_size for media_size in cls
+                  if media_size.value.width == width and media_size.value.media_type == media_type]
+        if not medias:
+            return cls.UNSUPPORTED_MEDIA
+        return medias[0]
 
 
 class StatusCodes(Enum):
     STATUS_REPLY = 0x00
     PRINTING_DONE = 0x01
     ERROR_OCCURRED = 0x02
     EDIT_IF_MODE = 0x03
```

### Comparing `labelprinterkit-0.5.8/labelprinterkit/label.py` & `labelprinterkit-0.6.0/labelprinterkit/label.py`

 * *Files 5% similar despite different names*

```diff
@@ -103,18 +103,20 @@
                 upper = test
             elif font_height < height:
                 lower = test
             else:
                 return test
 
 
-class QrCode(Item):
+class QRCode(Item):
     def __init__(self, width: int, data: str,
                  error_correction: Optional[ERROR_CORRECT_M | ERROR_CORRECT_H | ERROR_CORRECT_Q] = None,
                  box_size: int | None = None, border: int = 0):
+        if _QRCode is None:
+            raise RuntimeError('No QR code support. Package qrcode is not installed.')
         self._width = width
         self._data = data
         self._error_correction = error_correction
         self._box_size = box_size
         self._border = border
 
     def render(self) -> Image:
```

### Comparing `labelprinterkit-0.5.8/labelprinterkit/page.py` & `labelprinterkit-0.6.0/labelprinterkit/page.py`

 * *Files identical despite different names*

### Comparing `labelprinterkit-0.5.8/labelprinterkit/printers.py` & `labelprinterkit-0.6.0/labelprinterkit/printers.py`

 * *Files 5% similar despite different names*

```diff
@@ -2,17 +2,17 @@
 from abc import ABC, abstractmethod
 from logging import getLogger
 import struct
 from typing import TypeVar
 
 import packbits
 
-from .backends import BaseBackend
+from .backends import BaseBackend, UniDirectionalBackend
 from .constants import Resolution, ErrorCodes, MediaType, StatusCodes, NotificationCodes, TapeColor, \
-    TextColor, VariousModesSettings, AdvancedModeSettings
+    TextColor, VariousModesSettings, AdvancedModeSettings, Media
 from .job import Job
 
 logger = getLogger(__name__)
 
 BackendType = TypeVar('BackendType', bound=BaseBackend)
 
 
@@ -77,24 +77,31 @@
             _data['text_color'] = {x.value: x for x in TextColor}[int(data[25])]
         except IndexError:
             raise RuntimeError("Unknown text color {data[18]}")
         # data[26:29]  # Hardware settings
         # data[30:31] Reserved
 
         self._data = _data
+        self._media = None
 
-    def __repr__(self):
+    def __repr__(self) -> str:
         return "<Status {}>".format(self._data)
 
     def __getattr__(self, attr):
         return self._data[attr]
 
-    def ready(self):
+    def ready(self) -> bool:
         return not self.errors.any()
 
+    @property
+    def media(self) -> Media:
+        if self._media is None:
+            self._media = Media.get_media(self.media_width, self.media_type)
+        return self._media
+
 
 class BasePrinter(ABC):
     """Base class for printers. All printers define this API.  Any other
     methods are prefixed with a _ to indicate they are not part of the
     printer API"""
 
     def __init__(self, backend: BackendType):
@@ -134,38 +141,44 @@
         super().__init__(backend)
 
     def reset(self):
         self._backend.write(b'\x00' * 100)  # Invalidate command
         self._backend.write(b'\x1b@')  # Initialize command 1b 40
 
     def get_status(self) -> Status:
-        if not hasattr(self._backend, 'read'):
+        if hasattr(self._backend, 'get_status'):
+            data = self._backend.get_status()
+        elif isinstance(self._backend, UniDirectionalBackend):
             raise RuntimeError("Backend is unidirectional")
-        self.reset()
-        self._backend.write(b'\x1BiS')
-        data = self._backend.read(32)
+        else:
+            self.reset()
+            self._backend.write(b'\x1BiS')
+            data = self._backend.read(32)
         if not data:
             raise IOError("No Response from printer")
 
         if len(data) < 32:
             raise IOError("Invalid Response from printer")
 
         return Status(data)
 
     def print(self, job: Job):
         logger.info("starting print")
 
         self.reset()
 
+        if job.media in (Media.NO_MEDIA, Media.UNSUPPORTED_MEDIA):
+            raise RuntimeError('Unsupported Media')
+
         if job.resolution not in self._SUPPORTED_RESOLUTIONS:
             raise RuntimeError('Resolution is not supported by this printer.')
 
-        media_type = job.media_type.value.to_bytes(1, 'big')
-        media_size = job.media_size.value.width.to_bytes(1, 'big')
-        offset = job.media_size.value.lmargin
+        media_type = job.media.value.media_type.value.to_bytes(1, 'big')
+        media_size = job.media.value.width.to_bytes(1, 'big')
+        offset = job.media.value.lmargin
 
         various_mode = 0
         if job.auto_cut:
             various_mode = various_mode | VariousModesSettings.AUTO_CUT.value
             auto_cut = True
         else:
             auto_cut = False
```

### Comparing `labelprinterkit-0.5.8/PKG-INFO` & `labelprinterkit-0.6.0/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,25 +1,28 @@
 Metadata-Version: 2.1
 Name: labelprinterkit
-Version: 0.5.8
+Version: 0.6.0
 Summary: A library for creating and printing labels for Brother P-Touch devices
 License: Apache License, Version 2.0
 Author: Adrian Tschira
 Author-email: packages@notafile.com
 Requires-Python: >=3.9,<4.0
 Classifier: License :: Other/Proprietary License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Provides-Extra: bluetooth
 Provides-Extra: qrcode
+Provides-Extra: snmp
 Requires-Dist: packbits (>=0.6,<0.7)
 Requires-Dist: pillow (>=9.5.0,<10.0.0)
+Requires-Dist: pyasn1 (>=0.4.8,<0.5.0) ; extra == "snmp"
 Requires-Dist: pyserial (>=3.5,<4.0) ; extra == "bluetooth"
+Requires-Dist: pysnmp (>=4.4.12,<5.0.0) ; extra == "snmp"
 Requires-Dist: pyusb (>=1.2.1,<2.0.0)
 Requires-Dist: qrcode[pil] (>=7.4.2,<8.0.0) ; extra == "qrcode"
 Requires-Dist: setuptools (>=68.0.0,<69.0.0)
 Description-Content-Type: text/markdown
 
 ### Labelprinterkit
 
@@ -30,15 +33,15 @@
 Labelprinterkit's simple layout engine can be used to create simple labels:
 
 ```python
 from labelprinterkit.backends.usb import PyUSBBackend
 from labelprinterkit.printers import P700
 from labelprinterkit.label import Label, Text, Box, Padding
 from labelprinterkit.job import Job
-from labelprinterkit.constants import MediaType, MediaSize
+from labelprinterkit.constants import MediaType, Media
 from labelprinterkit.page import Page
 from PIL import Image
 
 # Create text for the label
 
 text1 = Text(45, "First line", 'comic.ttf', padding=Padding(0, 0, 1, 0))
 text2 = Text(25, "Some text", 'comic.ttf')
@@ -48,15 +51,15 @@
 box1 = Box(45, text1)
 box2 = Box(25, text2, text3)
 
 # Create label with rows from above
 label = Label(box1, box2)
 
 # Create job with configuration and add label as page
-job = Job(MediaSize.W12, MediaType.LAMINATED_TAPE)
+job = Job(Media.W12, MediaType.LAMINATED_TAPE)
 job.add_page(label)
 
 # Create a page from a Pillow image and add it to the job
 image = Image.new("1", (70, 200), "white")
 page = Page.from_image(image)
 job.add_page(page)
```

