# Comparing `tmp/simple_pygame-0.0.5.tar.gz` & `tmp/simple_pygame-0.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "simple_pygame-0.0.5.tar", last modified: Tue May 16 16:35:38 2023, max compression
+gzip compressed data, was "simple_pygame-0.0.6.tar", last modified: Wed Jun 28 14:18:20 2023, max compression
```

## Comparing `simple_pygame-0.0.5.tar` & `simple_pygame-0.0.6.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxrwxrwx   0        0        0        0 2023-05-16 16:35:38.075778 simple_pygame-0.0.5/
--rw-rw-rw-   0        0        0     1087 2023-02-13 12:51:16.000000 simple_pygame-0.0.5/LICENSE
--rw-rw-rw-   0        0        0     1416 2023-05-16 16:35:38.075778 simple_pygame-0.0.5/PKG-INFO
--rw-rw-rw-   0        0        0      897 2023-05-16 16:09:43.000000 simple_pygame-0.0.5/README.md
--rw-rw-rw-   0        0        0      602 2023-05-16 16:09:00.000000 simple_pygame-0.0.5/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-05-16 16:35:38.075778 simple_pygame-0.0.5/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-05-16 16:35:38.060154 simple_pygame-0.0.5/src/
-drwxrwxrwx   0        0        0        0 2023-05-16 16:35:38.060154 simple_pygame-0.0.5/src/simple_pygame/
--rw-rw-rw-   0        0        0     1355 2023-05-16 15:52:52.000000 simple_pygame-0.0.5/src/simple_pygame/__init__.py
--rw-rw-rw-   0        0        0      282 2023-05-16 15:50:51.000000 simple_pygame-0.0.5/src/simple_pygame/constants.py
--rw-rw-rw-   0        0        0     1172 2023-05-16 15:54:05.000000 simple_pygame-0.0.5/src/simple_pygame/mixer.py
--rw-rw-rw-   0        0        0    34033 2023-05-16 15:55:07.000000 simple_pygame-0.0.5/src/simple_pygame/music.py
--rw-rw-rw-   0        0        0     3232 2023-05-16 15:32:02.000000 simple_pygame-0.0.5/src/simple_pygame/transform.py
-drwxrwxrwx   0        0        0        0 2023-05-16 16:35:38.075778 simple_pygame-0.0.5/src/simple_pygame.egg-info/
--rw-rw-rw-   0        0        0     1416 2023-05-16 16:35:38.000000 simple_pygame-0.0.5/src/simple_pygame.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      342 2023-05-16 16:35:38.000000 simple_pygame-0.0.5/src/simple_pygame.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-05-16 16:35:38.000000 simple_pygame-0.0.5/src/simple_pygame.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       14 2023-05-16 16:35:38.000000 simple_pygame-0.0.5/src/simple_pygame.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 14:18:20.456643 simple_pygame-0.0.6/
+-rw-rw-rw-   0        0        0     1087 2023-02-13 12:51:16.000000 simple_pygame-0.0.6/LICENSE
+-rw-rw-rw-   0        0        0     1416 2023-06-28 14:18:20.456643 simple_pygame-0.0.6/PKG-INFO
+-rw-rw-rw-   0        0        0      897 2023-06-28 14:16:32.000000 simple_pygame-0.0.6/README.md
+-rw-rw-rw-   0        0        0      602 2023-06-28 14:16:13.000000 simple_pygame-0.0.6/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 14:18:20.456643 simple_pygame-0.0.6/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 14:18:20.425395 simple_pygame-0.0.6/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 14:18:20.425395 simple_pygame-0.0.6/src/simple_pygame/
+-rw-rw-rw-   0        0        0     1689 2023-06-28 14:11:02.000000 simple_pygame-0.0.6/src/simple_pygame/__init__.py
+-rw-rw-rw-   0        0        0      319 2023-06-28 14:11:01.000000 simple_pygame-0.0.6/src/simple_pygame/constants.py
+-rw-rw-rw-   0        0        0     1169 2023-06-28 14:10:59.000000 simple_pygame-0.0.6/src/simple_pygame/mixer.py
+-rw-rw-rw-   0        0        0    37405 2023-06-28 14:16:43.000000 simple_pygame-0.0.6/src/simple_pygame/music.py
+-rw-rw-rw-   0        0        0     3230 2023-06-28 14:10:51.000000 simple_pygame-0.0.6/src/simple_pygame/transform.py
+drwxrwxrwx   0        0        0        0 2023-06-28 14:18:20.441019 simple_pygame-0.0.6/src/simple_pygame.egg-info/
+-rw-rw-rw-   0        0        0     1416 2023-06-28 14:18:20.000000 simple_pygame-0.0.6/src/simple_pygame.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      342 2023-06-28 14:18:20.000000 simple_pygame-0.0.6/src/simple_pygame.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 14:18:20.000000 simple_pygame-0.0.6/src/simple_pygame.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       14 2023-06-28 14:18:20.000000 simple_pygame-0.0.6/src/simple_pygame.egg-info/top_level.txt
```

### Comparing `simple_pygame-0.0.5/LICENSE` & `simple_pygame-0.0.6/LICENSE`

 * *Files identical despite different names*

### Comparing `simple_pygame-0.0.5/PKG-INFO` & `simple_pygame-0.0.6/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: simple_pygame
-Version: 0.0.5
+Version: 0.0.6
 Summary: A Python library that provides many features using Pygame and other libraries.
 Author: YoutuberTom
 Project-URL: Source, https://github.com/YoutuberTom/Simple_Pygame
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Education
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
```

### Comparing `simple_pygame-0.0.5/README.md` & `simple_pygame-0.0.6/README.md`

 * *Files identical despite different names*

### Comparing `simple_pygame-0.0.5/pyproject.toml` & `simple_pygame-0.0.6/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools >= 61.0"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "simple_pygame"
-version = "0.0.5"
+version = "0.0.6"
 description = "A Python library that provides many features using Pygame and other libraries."
 readme = "README.md"
 requires-python = ">= 3.7"
 authors = [
     {name = "YoutuberTom"}
 ]
 classifiers = [
```

### Comparing `simple_pygame-0.0.5/src/simple_pygame/__init__.py` & `simple_pygame-0.0.6/src/simple_pygame/mixer.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,55 +1,59 @@
 """
-Simple Pygame is a Python library that provides many features using Pygame and other libraries. It can help you create multimedia programs much easier and cleaner.
+A module for playing music.
 """
 import gc
-from .constants import *
-from . import mixer
-from . import transform
+from .constants import MusicClass
 
 _init = False
 
 def get_init() -> bool:
     """
-    Returns `True` if Simple Pygame is currently initialized, otherwise `False`.
+    Return `True` if the mixer module is currently initialized, otherwise `False`.
     """
     return _init
 
 def init() -> tuple:
     """
-    Initializes all imported Simple Pygame modules and return successfully initialized modules.
+    Initialize the mixer module and return successfully initialized classes.
     """
     global _init
 
     if get_init():
         return ()
     _init = True
     
     successfully_imported = []
 
-    mixer_successfully_imported = mixer.init()
-    if mixer_successfully_imported:
-        successfully_imported.append(MixerModule)
+    try:
+        global Music
+        from .music import Music
+        successfully_imported.append(MusicClass)
+    except ImportError:
+        pass
 
     if len(successfully_imported) == 0:
         _init = False
-    
+
     return (*successfully_imported,)
 
 def quit() -> tuple:
     """
-    Uninitializes all imported Simple Pygame modules and return successfully uninitialized modules.
+    Uninitialize the mixer module and return successfully uninitialized classes.
     """
     global _init
 
-    if not get_init():
+    if not get_init:
         return ()
     _init = False
 
     successfully_quit = []
 
-    mixer_successfully_quit = mixer.quit()
-    if mixer_successfully_quit:
-        successfully_quit.append(MixerModule)
+    try:
+        global Music
+        del Music
+        successfully_quit.append(MusicClass)
+    except NameError:
+        pass
 
     gc.collect()
     return (*successfully_quit,)
```

### Comparing `simple_pygame-0.0.5/src/simple_pygame/music.py` & `simple_pygame-0.0.6/src/simple_pygame/music.py`

 * *Files 7% similar despite different names*

```diff
@@ -6,20 +6,20 @@
 
 - Pyaudio library.
 
 - FFmpeg.
 
 - FFprobe (optional).
 """
-import pyaudio, audioop, subprocess, threading, json, time, sys
+import pyaudio, audioop, subprocess, threading, platform, json, time, sys
 from .constants import SInt8, SInt16, SInt32, UInt8, MusicIsLoading, MusicEnded
 from typing import Optional, Union, Iterable
 
 class Music:
-    def __init__(self, path: Optional[str] = None, stream: int = 0, chunk: int = 4096, ffmpeg_path: str = "ffmpeg", ffprobe_path: str = "ffprobe") -> None:
+    def __init__(self, path: Optional[str] = None, stream: int = 0, chunk: int = 4096, frames_per_buffer: Optional[int] = None, ffmpeg_path: str = "ffmpeg", ffprobe_path: str = "ffprobe") -> None:
         """
         A music stream from a file contains audio. This class won't load the entire file.
 
         Requirements
         ------------
 
         - Pyaudio library.
@@ -33,36 +33,46 @@
 
         path (optional): Path to the file contains audio.
 
         stream (optional): Which stream to use if the file has more than 1 audio stream. Use the default stream if stream is invalid.
 
         chunk (optional): Number of bytes per chunk when playing music.
 
+        frames_per_buffer (optional): Specifies the number of frames per buffer. Set the value to `pyaudio.paFramesPerBufferUnspecified` if `None`.
+
         ffmpeg_path (optional): Path to ffmpeg.
 
         ffprobe_path (optional): Path to ffprobe.
         """
         if path != None and type(path) != str:
             raise TypeError("Path must be None or a string.")
 
         if type(stream) != int:
             raise TypeError("Stream must be an integer.")
 
         if type(chunk) != int:
             raise TypeError("Chunk must be an integer.")
+        elif chunk <= 0:
+            raise ValueError("Chunk must be greater than 0.")
+        
+        if frames_per_buffer != None and type(frames_per_buffer) != int:
+            raise TypeError("Frames per buffer must be None/an integer.")
+        elif type(frames_per_buffer) == int and frames_per_buffer < 0:
+            raise ValueError("Frames per buffer must be greater than or equal to 0.")
 
         if type(ffmpeg_path) != str:
             raise TypeError("FFmpeg path must be a string.")
 
         if type(ffprobe_path) != str:
             raise TypeError("FFprobe path must be a string.")
 
         self.path = path
         self.stream = stream
         self.chunk = chunk
+        self.frames_per_buffer = pyaudio.paFramesPerBufferUnspecified if frames_per_buffer == None else frames_per_buffer
         self.ffmpeg_path = ffmpeg_path
         self.ffprobe_path = ffprobe_path
         self.currently_pause = False
         self.exception = None
         self._output_device_index = None
         self._music_thread = None
         self._start = None
@@ -75,22 +85,22 @@
 
         self._pa = pyaudio.PyAudio()
         self.set_format()
 
     @classmethod
     def get_information(self, path: str, use_ffmpeg: bool = False, ffmpeg_or_ffprobe_path: str = "ffprobe", loglevel: str = "quiet") -> Optional[dict]:
         """
-        Returns a dict contains all the file information. Return `None` if cannot read the file.
+        Return a dict contains all the file information. Return `None` if cannot read the file.
 
         Parameters
         ----------
 
         path: Path to the file to get information.
 
-        use_ffmpeg (optional): Specify whether to use ffmpeg or ffprobe to get the file information.
+        use_ffmpeg (optional): Specifies whether to use ffmpeg or ffprobe to get the file information.
 
         ffmpeg_or_ffprobe_path (optional): Path to ffmpeg or ffprobe.
 
         loglevel (optional): Logging level and flags used by ffprobe.
         """
         if type(path) != str:
             raise TypeError("Path must be a string.")
@@ -131,15 +141,15 @@
                     raise ValueError("Invalid loglevel.") from None
                 else:
                     raise ValueError("Invalid ffprobe path or path or data.") from None
 
     @classmethod
     def extract_information(self, raw_data: Iterable[str]) -> dict:
         """
-        Returns a dict contains the processed information of the file. This function is meant for use by the `Class` and not for general use.
+        Return a dict contains the processed information of the file. This function is meant for use by the `Class` and not for general use.
 
         Parameters
         ----------
 
         raw_data: An iterable object contains raw information of the file from ffmpeg.
         """
         try:
@@ -273,40 +283,42 @@
                 del data["streams"][index]["tags"]
 
         return data
 
     @classmethod
     def create_pipe(self, path: str, position: Union[int, float] = 0, stream: int = 0, data_format: any = None, use_ffmpeg: bool = False, ffmpeg_path: str = "ffmpeg", ffprobe_path: str = "ffprobe", loglevel: str = "quiet") -> list:
         """
-        Returns a pipe contains ffmpeg output, a dict contains the file information and a dict contains the stream information. This function is meant for use by the `Class` and not for general use.
+        Return a pipe contains ffmpeg output, a dict contains the file information and a dict contains the stream information. This function is meant for use by the `Class` and not for general use.
 
         Parameters
         ----------
 
         path: Path to the file to create pipe.
 
         position (optional): Where to set the music position in seconds.
 
         stream (optional): Which stream to use if the file has more than 1 audio stream. Use the default stream if stream is invalid.
 
         data_format (optional): Output data format. Use format from the `set_format()` function if `None`.
 
-        use_ffmpeg (optional): Specify whether to use ffmpeg or ffprobe to get the file information.
+        use_ffmpeg (optional): Specifies whether to use ffmpeg or ffprobe to get the file information.
 
         ffmpeg_path (optional): Path to ffmpeg.
 
         ffprobe_path (optional): Path to ffprobe.
 
         loglevel (optional): Logging level and flags used by ffmpeg and ffprobe.
         """
         if type(path) != str:
             raise TypeError("Path must be a string.")
 
         if type(position) != int and type(position) != float:
             raise TypeError("Position must be an integer/a float.")
+        elif position < 0:
+            position = 0
 
         if type(stream) != int:
             raise TypeError("Stream must be an integer.")
 
         if data_format == None:
             try:
                 data_format = self.ffmpegFormat
@@ -331,75 +343,84 @@
         audio_streams = []
         for data in streams:
             if data["codec_type"] == "audio":
                 audio_streams.append(data)
         
         if len(audio_streams) == 0:
             raise ValueError("The file doesn't contain audio.")
-        else:
-            stream = int(stream)
-
-            if stream < 0:
-                stream = 0
-            elif stream >= len(audio_streams):
-                stream = 0
+        elif stream < 0 or stream >= len(audio_streams):
+            stream = 0
 
         ffmpeg_command = [ffmpeg_path, "-nostdin", "-loglevel", loglevel, "-accurate_seek", "-ss", str(position), "-vn", "-i", path, "-map", f"0:a:{stream}", "-f", data_format, "pipe:1"]
 
+        creationflags = 0
+        if platform.system() == "Windows":
+            creationflags = subprocess.CREATE_NO_WINDOW
+
         try:
-            return subprocess.Popen(ffmpeg_command, stdout = subprocess.PIPE, creationflags = subprocess.CREATE_NO_WINDOW), information, audio_streams[stream]
+            return subprocess.Popen(ffmpeg_command, stdout = subprocess.PIPE, creationflags = creationflags), information, audio_streams[stream]
         except FileNotFoundError:
             raise FileNotFoundError("No ffmpeg found on your system. Make sure you've it installed and you can try specifying the ffmpeg path.") from None
 
-    def change_attributes(self, path: Optional[str] = None, stream: int = 0, chunk: int = 4096, ffmpeg_path: str = "ffmpeg", ffprobe_path: str = "ffprobe") -> None:
+    def change_attributes(self, path: Optional[str] = None, stream: int = 0, chunk: int = 4096, frames_per_buffer: Optional[int] = None, ffmpeg_path: str = "ffmpeg", ffprobe_path: str = "ffprobe") -> None:
         """
         An easier way to change some attributes.
 
         Parameters
         ----------
 
         path (optional): Path to the file contains audio.
 
         stream (optional): Which stream to use if the file has more than 1 audio stream. Use the default stream if stream is invalid.
 
         chunk (optional): Number of bytes per chunk when playing music.
 
+        frames_per_buffer (optional): Specifies the number of frames per buffer. Set the value to `pyaudio.paFramesPerBufferUnspecified` if `None`.
+
         ffmpeg_path (optional): Path to ffmpeg.
 
         ffprobe_path (optional): Path to ffprobe.
         """
         if path != None and type(path) != str:
             raise TypeError("Path must be None or a string.")
 
         if type(stream) != int:
             raise TypeError("Stream must be an integer.")
 
         if type(chunk) != int:
             raise TypeError("Chunk must be an integer.")
+        elif chunk <= 0:
+            raise ValueError("Chunk must be greater than 0.")
+
+        if frames_per_buffer != None and type(frames_per_buffer) != int:
+            raise TypeError("Frames per buffer must be None/an integer.")
+        elif type(frames_per_buffer) == int and frames_per_buffer < 0:
+            raise ValueError("Frames per buffer must be greater than or equal to 0.")
 
         if type(ffmpeg_path) != str:
             raise TypeError("FFmpeg path must be a string.")
 
         if type(ffprobe_path) != str:
             raise TypeError("FFprobe path must be a string.")
 
         self.path = path
         self.stream = stream
         self.chunk = chunk
+        self.frames_per_buffer = pyaudio.paFramesPerBufferUnspecified if frames_per_buffer == None else frames_per_buffer
         self.ffmpeg_path = ffmpeg_path
         self.ffprobe_path = ffprobe_path
 
     def set_format(self, data_format: any = SInt16) -> None:
         """
-        Sets the output data format. Default is `simple_pygame.SInt16`.
+        Set the output data format. Default is `simple_pygame.SInt16`.
 
         Parameters
         ----------
 
-        data_format (optional): Specify what format to use.
+        data_format (optional): Specifies what format to use.
         """
         if data_format == SInt8:
             self.paFormat = pyaudio.paInt8
             self.ffmpegFormat = "s8"
             self.aoFormat = 1
         elif data_format == SInt16:
             self.paFormat = pyaudio.paInt16
@@ -414,21 +435,21 @@
             self.ffmpegFormat = "u8"
             self.aoFormat = 1
         else:
             raise ValueError("Invalid format.")
 
     def get_device_count(self) -> int:
         """
-        Returns the number of PortAudio Host APIs.
+        Return the number of PortAudio Host APIs.
         """
         return self._pa.get_device_count()
 
     def set_output_device_by_index(self, device_index: Optional[int] = None) -> None:
         """
-        Sets the output device by index.
+        Set the output device by index.
 
         Parameters
         ----------
 
         device_index: The device's index. Set the output device to default output device if `None`.
         """
         if device_index == None:
@@ -444,15 +465,15 @@
         if self.get_device_info(device_index)["maxOutputChannels"] == 0:
             raise ValueError("The device doesn't have any output channels.")
 
         self._output_device_index = device_index
 
     def get_device_info(self, device_index: Optional[int] = None) -> dict:
         """
-        Returns the device info.
+        Return the device info.
 
         Parameters
         ----------
 
         device_index: The device's index. Return the default output device info if `None`.
         """
         if device_index == None:
@@ -462,213 +483,243 @@
             raise TypeError("The device's index must be an integer.")
         
         if device_index < 0 or device_index > self.get_device_count() - 1:
             raise ValueError("Invalid index.")
     
         return self._pa.get_device_info_by_index(device_index)
 
-    def play(self, loop: int = 0, start: Union[int, float] = 0, exception_on_underflow: bool = False, use_ffmpeg: bool = False) -> None:
+    def play(self, loop: int = 0, start: Union[int, float] = 0, delay: Union[int, float] = 0.1, exception_on_underflow: bool = False, use_ffmpeg: bool = False) -> None:
         """
-        Starts the music stream. If the music stream is current playing it will be restarted.
+        Start the music stream. If the music stream is current playing it will be restarted.
 
         Parameters
         ----------
 
         loop (optional): How many times to repeat the music. If this args is set to `-1` repeats indefinitely.
 
         start (optional): Where the music stream starts playing in seconds.
 
-        exception_on_underflow (optional): Specify whether an exception should be thrown (or silently ignored) on buffer underflow. Default to `False` for improved performance, especially on slower platforms.
+        delay (optional): The interval between each check to determine if the music stream has resumed when it's currently paused in seconds.
 
-        use_ffmpeg (optional): Specify whether to use ffmpeg or ffprobe to get the file information.
+        exception_on_underflow (optional): Specifies whether an exception should be thrown (or silently ignored) on buffer underflow. Defaults to `False` for improved performance, especially on slower platforms.
+
+        use_ffmpeg (optional): Specifies whether to use ffmpeg or ffprobe to get the file information.
         """
         self.stop()
 
         if self.path == None:
             raise ValueError("Please specify the path before starting the music stream.")
 
         if type(loop) != int:
             raise TypeError("Loop must be an integer.")
         elif loop < -1:
-            return
+            raise ValueError("Loop must be greater than or equal to -1.")
 
         if type(start) != int and type(start) != float:
             raise TypeError("Start position must be an integer/a float.")
 
+        if type(delay) != int and type(delay) != float:
+            raise TypeError("Delay must be an integer/a float.")
+        elif delay < 0:
+            raise ValueError("Delay must be non-negative.")
+
         self.currently_pause = False
         self.exception = None
         self._start = None
         self._start_pause = None
         self._reposition = False
         self._terminate = False
 
         self._pause_time = 0
         if start < 0:
             self._position = 0
         else:
             self._position = start
 
-        self._music_thread = threading.Thread(target = self.music, args = (self.path, loop, self.stream, self.chunk, exception_on_underflow, use_ffmpeg))
+        self._music_thread = threading.Thread(target = self.music, args = (self.path, loop, self.stream, self.chunk, delay, exception_on_underflow, use_ffmpeg))
         self._music_thread.daemon = True
         self._music_thread.start()
 
     def pause(self) -> None:
         """
-        Pauses the music stream if it's current playing and not paused. It can be resumed with `resume()` function.
+        Pause the music stream if it's current playing and not paused. It can be resumed with `resume()` function.
         """
         if self.get_busy() and not self.get_pause():
             self.currently_pause = True
 
     def resume(self) -> None:
         """
-        Resumes the music stream after it has been paused.
+        Resume the music stream after it has been paused.
         """
         if self.get_busy() and self.get_pause():
             self.currently_pause = False
 
-    def stop(self) -> None:
+    def stop(self, delay: Union[int, float] = 0.1) -> None:
         """
-        Stops the music stream if it's current playing.
+        Stop the music stream if it's current playing.
+
+        Parameters
+        ----------
+
+        delay (optional): The interval between each check to determine if the music stream is currently busy in seconds.
         """
+        if type(delay) != int and type(delay) != float:
+            raise TypeError("Delay must be an integer/a float.")
+        elif delay < 0:
+            raise ValueError("Delay must be non-negative.")
+
         if self.get_busy():
             self._terminate = True
 
             while self.get_busy():
-                pass
-        
+                time.sleep(delay)
+
         self._music_thread = None
 
     def join(self, delay: Union[int, float] = 0.1, raise_exception: bool = True) -> None:
         """
-        Waits until the music stream stops.
+        Wait until the music stream stops.
 
         Parameters
         ----------
 
         delay (optional): The interval between each check to determine if the music stream is currently busy in seconds.
 
-        raise_exception (optional): Specify whether an exception should be thrown (or silently ignored).
+        raise_exception (optional): Specifies whether an exception should be thrown (or silently ignored).
         """
+        if type(delay) != int and type(delay) != float:
+            raise TypeError("Delay must be an integer/a float.")
+        elif delay < 0:
+            raise ValueError("Delay must be non-negative.")
+
         while self.get_busy():
             time.sleep(delay)
 
         if not raise_exception:
             return
 
         exception = self.get_exception()
         if exception:
             raise exception
     
     def get_pause(self) -> bool:
         """
-        Returns `True` if currently pausing the music stream, otherwise `False`.
+        Return `True` if currently pausing the music stream, otherwise `False`.
         """
         if self.get_busy():
             return self.currently_pause
         return False
 
     def set_position(self, position: Union[int, float]) -> None:
         """
-        Sets the current music position where the music will continue to play.
+        Set the current music position where the music will continue to play.
 
         Parameters
         ----------
 
         position: Where to set the music stream position in seconds.
         """
         if type(position) != int and type(position) != float:
             raise TypeError("Position must be an integer/a float.")
 
         if self.get_busy():
-            if position < 0:
-                self._position = 0
-            else:
-                self._position = position
+            self._position = 0 if position < 0 else position
             self._reposition = True
         else:
             self.play(start = position)
 
-    def get_position(self) -> any:
+    def get_position(self, digit: Optional[int] = 4) -> any:
         """
-        Returns the current music position in seconds if it's current playing or pausing, `simple_pygame.MusicIsLoading` if the music stream is loading, otherwise `simple_pygame.MusicEnded`.
+        Return the current music position in seconds if it's current playing or pausing, `simple_pygame.MusicIsLoading` if the music stream is loading, otherwise `simple_pygame.MusicEnded`.
+
+        Parameters
+        ----------
+
+        digit (optional): Number of digits to round.
         """
-        if self.get_busy():
-            position = self._start
+        if digit != None and type(digit) != int:
+            raise TypeError("Digit must be None/an integer.")
 
-            if position:
-                if self._start_pause:
-                    return self.nanoseconds_to_seconds(self._start_pause - position - self._pause_time)
-                else:
-                    return self.nanoseconds_to_seconds(time.time_ns() - position - self._pause_time)
-            else:
-                return MusicIsLoading
-        else:
+        if not self.get_busy():
             return MusicEnded
 
+        if self._start == None:
+            return MusicIsLoading
+
+        if self._start_pause == None:
+            position = self.nanoseconds_to_seconds(time.time_ns() - self._start - self._pause_time)
+        else:
+            position = self.nanoseconds_to_seconds(self._start_pause - self._start - self._pause_time)
+        return position if digit == None else round(position, digit)
+
     def set_volume(self, volume: Union[int, float]) -> None:
         """
-        Sets the music stream volume. The volume must be a int/float between `0` and `2`, `1` is the original volume.
+        Set the music stream volume. The volume must be an integer/a float between `0` and `2`, `1` is the original volume.
 
         Parameters
         ----------
 
         volume: Music stream volume.
         """
         if type(volume) != int and type(volume) != float:
             raise TypeError("Volume must be an integer/a float.")
 
-        if volume >= 0 and volume <= 2:
+        if 0 <= volume <= 2:
             self._volume = round(volume, 2)
+        else:
+            raise ValueError("Volume must be an integer/a float between 0 and 2.")
 
     def get_volume(self) -> Union[int, float]:
         """
-        Returns the music stream volume.
+        Return the music stream volume.
         """
         return self._volume
 
     def get_busy(self) -> bool:
         """
-        Returns `True` if currently playing or pausing the music stream, otherwise `False`.
+        Return `True` if currently playing or pausing the music stream, otherwise `False`.
         """
-        if self._music_thread:
-            if self._music_thread.is_alive():
-                return True
-            else:
-                return False
+        if not self._music_thread:
+            return False
+
+        if self._music_thread.is_alive():
+            return True
         else:
             return False
 
     def get_exception(self) -> Optional[Exception]:
         """
-        Returns `None` if no exception is found, otherwise the exception.
+        Return `None` if no exception is found, otherwise the exception.
         """
         return self.exception
 
-    def music(self, path: str, loop: int = 0, stream: int = 0, chunk: int = 4096, exception_on_underflow: bool = False, use_ffmpeg: bool = False) -> None:
+    def music(self, path: str, loop: int = 0, stream: int = 0, chunk: int = 4096, delay: Union[int, float] = 0.1, exception_on_underflow: bool = False, use_ffmpeg: bool = False) -> None:
         """
-        Starts the music stream. This function is meant for use by the `Class` and not for general use.
+        Start the music stream. This function is meant for use by the `Class` and not for general use.
 
         Parameters
         ----------
 
         path: Path to the file contains audio.
 
         loop (optional): How many times to repeat the music. If this args is set to `-1` repeats indefinitely.
 
         stream (optional): Which stream to use if the file has more than 1 audio stream. Use the default stream if stream is invalid.
 
         chunk (optional): Number of bytes per chunk when playing music.
 
-        exception_on_underflow (optional): Specifies whether an exception should be thrown (or silently ignored) on buffer underflow. Default to `False` for improved performance, especially on slower platforms.
+        delay (optional): The interval between each check to determine if the music stream has resumed when it's currently paused in seconds.
+
+        exception_on_underflow (optional): Specifies whether an exception should be thrown (or silently ignored) on buffer underflow. Defaults to `False` for improved performance, especially on slower platforms.
 
-        use_ffmpeg (optional): Specify whether to use ffmpeg or ffprobe to get the file information.
+        use_ffmpeg (optional): Specifies whether to use ffmpeg or ffprobe to get the file information.
         """
         def clean_up() -> None:
             """
-            Cleans up everything before stopping the music stream.
+            Clean up everything before stopping the music stream.
             """
             try:
                 pipe.terminate()
             except NameError:
                 pass
 
             try:
@@ -677,144 +728,151 @@
             except NameError:
                 pass
 
             self.currently_pause = False
 
         def calculate_offset(position: Union[int, float]) -> Union[int, float]:
             """
-            Returns the music stream offset position.
+            Return the music stream offset position.
 
             Parameters
             ----------
 
             position: The music stream position in seconds.
             """
-            try:
-                duration = float(stream_info["duration"])
-            except KeyError:
-                duration = float(info["format"]["duration"])
-
             if position >= duration:
                 return self.seconds_to_nanoseconds(duration)
             else:
                 return self.seconds_to_nanoseconds(position)
 
         try:
             ffmpeg_path = self.ffmpeg_path
             ffprobe_path = self.ffprobe_path
             paFormat = self.paFormat
             ffmpegFormat = self.ffmpegFormat
             aoFormat = self.aoFormat
-            position = self._position
+            frames_per_buffer = self.frames_per_buffer
+            position = 0 if self._position < 0 else self._position
 
             pipe, info, stream_info = self.create_pipe(path, position, stream, ffmpegFormat, use_ffmpeg, ffmpeg_path, ffprobe_path)
-            stream_out = self._pa.open(int(stream_info["sample_rate"]), stream_info["channels"], paFormat, output = True, output_device_index = self._output_device_index, frames_per_buffer = chunk)
+            stream_out = self._pa.open(int(stream_info["sample_rate"]), stream_info["channels"], paFormat, output = True, output_device_index = self._output_device_index, frames_per_buffer = frames_per_buffer)
+            try:
+                duration = float(stream_info["duration"])
+            except KeyError:
+                duration = float(info["format"]["duration"])
 
-            offset = calculate_offset(position)
-            self._start = time.time_ns() - offset
             while not self._terminate:
                 if self._reposition:
-                    position = self._position
+                    position = 0 if self._position < 0 else self._position
+
                     pipe, info, stream_info = self.create_pipe(path, position, stream, ffmpegFormat, use_ffmpeg, ffmpeg_path, ffprobe_path)
                     self._reposition = False
 
                     offset = calculate_offset(position)
-                    if self._start_pause:
-                        self._start = self._start_pause - offset - self._pause_time
-                    else:
-                        self._start = time.time_ns() - offset - self._pause_time
+                    self._start = time.time_ns() - offset - self._pause_time if self._start_pause == None else self._start_pause - offset - self._pause_time
 
-                if not self.get_pause():
-                    if self._start_pause:
-                        self._pause_time += time.time_ns() - self._start_pause
-                        self._start_pause = None
-
-                    data = pipe.stdout.read(chunk)
-
-                    if data:
-                        data = audioop.mul(data, aoFormat, self._volume)
-                        stream_out.write(data, exception_on_underflow = exception_on_underflow)
-                    else:
-                        self._pause_time = 0
+                if self.get_pause():
+                    if self._start_pause == None:
+                        self._start_pause = time.time_ns()
 
-                        if loop == -1:
-                            pipe, info, stream_info = self.create_pipe(path, 0, stream, ffmpegFormat, use_ffmpeg, ffmpeg_path, ffprobe_path)
-                            self._start = time.time_ns()
-                        elif loop == 0:
-                            break
-                        else:
-                            loop -= 1
+                    time.sleep(delay)
+                    continue
+
+                if self._start_pause != None:
+                    self._pause_time += time.time_ns() - self._start_pause
+                    self._start_pause = None
+
+                data = pipe.stdout.read(chunk)
+                if data:
+                    data = audioop.mul(data, aoFormat, self._volume)
+
+                    if self._start == None:
+                        offset = calculate_offset(position)
+                        self._start = time.time_ns() - offset
+
+                    stream_out.write(data, exception_on_underflow = exception_on_underflow)
+                    continue
+
+                self._pause_time = 0
+                if loop == -1:
+                    pipe, info, stream_info = self.create_pipe(path, 0, stream, ffmpegFormat, use_ffmpeg, ffmpeg_path, ffprobe_path)
+                    self._start = time.time_ns()
+                elif loop > 0:
+                    loop -= 1
 
-                            pipe, info, stream_info = self.create_pipe(path, 0, stream, ffmpegFormat, use_ffmpeg, ffmpeg_path, ffprobe_path)
-                            self._start = time.time_ns()
-                elif not self._start_pause:
-                    self._start_pause = time.time_ns()
+                    pipe, info, stream_info = self.create_pipe(path, 0, stream, ffmpegFormat, use_ffmpeg, ffmpeg_path, ffprobe_path)
+                    self._start = time.time_ns()
+                else:
+                    break
         except Exception as error:
             self.exception = error
         finally:
             clean_up()
 
     @classmethod
-    def nanoseconds_to_seconds(self, time: Union[int, float], digit: int = 4) -> Union[int, float]:
+    def enquote(self, value: any) -> any:
         """
-        Converts nanoseconds to seconds. It's meant for use by the `Class` and not for general use.
+        Add single quotation marks at the start and end of a string, while leaving other types unchanged.
 
         Parameters
         ----------
 
-        time: Time in nanoseconds.
+        value: Any value.
+        """
+        return f"'{value}'" if type(value) == str else value
 
-        digit: Number of digits to round.
+    @classmethod
+    def nanoseconds_to_seconds(self, time: Union[int, float]) -> Union[int, float]:
+        """
+        Convert nanoseconds to seconds. It's meant for use by the `Class` and not for general use.
+
+        Parameters
+        ----------
+
+        time: Time in nanoseconds.
         """
         if type(time) != int and type(time) != float:
             raise TypeError("Time must be an integer/a float.")
+        elif time < 0:
+            raise ValueError("Time must be non-negative.")
 
-        if type(digit) != int:
-            raise TypeError("Digit must be an integer.")
-
-        return round(time / 1000000000, digit)
+        return time / 1000000000
 
     @classmethod
-    def seconds_to_nanoseconds(self, time: Union[int, float], digit: int = 4) -> Union[int, float]:
+    def seconds_to_nanoseconds(self, time: Union[int, float]) -> Union[int, float]:
         """
-        Converts seconds to nanoseconds. It's meant for use by the `Class` and not for general use.
+        Convert seconds to nanoseconds. It's meant for use by the `Class` and not for general use.
 
         Parameters
         ----------
 
         time: Time in seconds.
-
-        digit: Number of digits to round.
         """
         if type(time) != int and type(time) != float:
             raise TypeError("Time must be an integer/a float.")
+        elif time < 0:
+            raise ValueError("Time must be non-negative.")
 
-        if type(digit) != int:
-            raise TypeError("Digit must be an integer.")
+        return time * 1000000000
 
-        return round(time * 1000000000, digit)
-    
     def __str__(self) -> str:
         """
-        Returns a string represents the object.
+        Return a string represents the object.
         """
-        if self.path == None:
-            return "<Music()>"
-
-        return f"<Music('{self.path}')>"
+        return f"<Music(path={self.enquote(self.path)}, stream={self.enquote(self.stream)}, chunk={self.enquote(self.chunk)}, ffmpeg_path={self.enquote(self.ffmpeg_path)}, ffprobe_path={self.enquote(self.ffprobe_path)})>"
 
     def __repr__(self) -> str:
         """
-        Returns a string represents the object.
+        Return a string represents the object.
         """
         return self.__str__()
 
     def __del__(self) -> None:
         """
-        Cleans up everything before deleting the class.
+        Clean up everything before deleting the class.
         """
         try:
             self.stop()
         except AttributeError:
             pass
 
         try:
```

### Comparing `simple_pygame-0.0.5/src/simple_pygame/transform.py` & `simple_pygame-0.0.6/src/simple_pygame/transform.py`

 * *Files 5% similar despite different names*

```diff
@@ -10,15 +10,15 @@
 os.environ["PYGAME_HIDE_SUPPORT_PROMPT"] = ""
 
 import pygame
 from typing import Union, Optional
 
 def fill(surface: pygame.Surface, color: Union[pygame.Color, tuple, list], rect: Optional[pygame.Rect] = None, special_flags: int = 0) -> pygame.Surface:
     """
-    Fills the given Surface with a solid color. If the Rect argument is given then only the area inside the specified Rect will be filled, otherwise the entire Surface will be filled.
+    Fill the given Surface with a solid color. If the Rect argument is given then only the area inside the specified Rect will be filled, otherwise the entire Surface will be filled.
 
     Parameters
     ----------
 
     surface: The Surface to be filled.
 
     color: The color to fill the Surface with.
@@ -48,15 +48,15 @@
 
     surface.fill(color, rect, special_flags)
 
     return rect
 
 def reverse_fill(surface: pygame.Surface, color: Union[pygame.Color, tuple, list], rect: pygame.Rect, special_flags: int = 0) -> pygame.Surface:
     """
-    Fills the area outside the specified Rect on the given Surface with a solid color.
+    Fill the area outside the specified Rect on the given Surface with a solid color.
 
     Parameters
     ----------
 
     surface: The Surface to be filled.
 
     color: The color to fill the Surface with.
```

### Comparing `simple_pygame-0.0.5/src/simple_pygame.egg-info/PKG-INFO` & `simple_pygame-0.0.6/src/simple_pygame.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: simple-pygame
-Version: 0.0.5
+Version: 0.0.6
 Summary: A Python library that provides many features using Pygame and other libraries.
 Author: YoutuberTom
 Project-URL: Source, https://github.com/YoutuberTom/Simple_Pygame
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Education
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
```

