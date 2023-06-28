# Comparing `tmp/voip-utils-0.0.7.tar.gz` & `tmp/voip-utils-0.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "voip-utils-0.0.7.tar", last modified: Tue May  2 19:51:42 2023, max compression
+gzip compressed data, was "voip-utils-0.1.0.tar", last modified: Wed Jun 28 14:30:10 2023, max compression
```

## Comparing `voip-utils-0.0.7.tar` & `voip-utils-0.1.0.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-05-02 19:51:42.322296 voip-utils-0.0.7/
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    11357 2022-11-22 20:23:02.000000 voip-utils-0.0.7/LICENSE.md
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      785 2023-05-02 19:51:42.322296 voip-utils-0.0.7/PKG-INFO
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)       39 2023-04-06 16:12:50.000000 voip-utils-0.0.7/README.md
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1977 2023-05-02 19:51:07.000000 voip-utils-0.0.7/pyproject.toml
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      299 2023-05-02 19:51:42.322296 voip-utils-0.0.7/setup.cfg
-drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-05-02 19:51:42.322296 voip-utils-0.0.7/voip_utils/
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      158 2023-04-06 17:22:11.000000 voip-utils-0.0.7/voip_utils/__init__.py
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)       83 2023-05-02 19:50:57.000000 voip-utils-0.0.7/voip_utils/const.py
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      170 2023-04-06 15:51:26.000000 voip-utils-0.0.7/voip_utils/error.py
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     7281 2023-05-02 19:50:57.000000 voip-utils-0.0.7/voip_utils/rtp_audio.py
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     7755 2023-05-02 19:50:57.000000 voip-utils-0.0.7/voip_utils/sip.py
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      257 2023-04-06 18:58:36.000000 voip-utils-0.0.7/voip_utils/util.py
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     6443 2023-05-02 19:50:57.000000 voip-utils-0.0.7/voip_utils/voip.py
-drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-05-02 19:51:42.322296 voip-utils-0.0.7/voip_utils.egg-info/
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      785 2023-05-02 19:51:42.000000 voip-utils-0.0.7/voip_utils.egg-info/PKG-INFO
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      386 2023-05-02 19:51:42.000000 voip-utils-0.0.7/voip_utils.egg-info/SOURCES.txt
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)        1 2023-05-02 19:51:42.000000 voip-utils-0.0.7/voip_utils.egg-info/dependency_links.txt
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)       15 2023-05-02 19:51:42.000000 voip-utils-0.0.7/voip_utils.egg-info/requires.txt
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)       11 2023-05-02 19:51:42.000000 voip-utils-0.0.7/voip_utils.egg-info/top_level.txt
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)        1 2023-04-06 18:58:14.000000 voip-utils-0.0.7/voip_utils.egg-info/zip-safe
+drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-28 14:30:10.625944 voip-utils-0.1.0/
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    11357 2022-11-22 20:23:02.000000 voip-utils-0.1.0/LICENSE.md
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      862 2023-06-28 14:30:10.625944 voip-utils-0.1.0/PKG-INFO
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      116 2023-06-27 15:29:04.000000 voip-utils-0.1.0/README.md
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1977 2023-06-27 15:29:04.000000 voip-utils-0.1.0/pyproject.toml
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      299 2023-06-28 14:30:10.625944 voip-utils-0.1.0/setup.cfg
+drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-28 14:30:10.625944 voip-utils-0.1.0/voip_utils/
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      212 2023-06-27 15:29:04.000000 voip-utils-0.1.0/voip_utils/__init__.py
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)       83 2023-05-02 19:50:57.000000 voip-utils-0.1.0/voip_utils/const.py
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      170 2023-04-06 15:51:26.000000 voip-utils-0.1.0/voip_utils/error.py
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     7281 2023-05-02 19:50:57.000000 voip-utils-0.1.0/voip_utils/rtp_audio.py
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     7956 2023-06-28 14:26:46.000000 voip-utils-0.1.0/voip_utils/sip.py
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      257 2023-04-06 18:58:36.000000 voip-utils-0.1.0/voip_utils/util.py
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     9507 2023-06-28 14:29:49.000000 voip-utils-0.1.0/voip_utils/voip.py
+drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-28 14:30:10.625944 voip-utils-0.1.0/voip_utils.egg-info/
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      862 2023-06-28 14:30:10.000000 voip-utils-0.1.0/voip_utils.egg-info/PKG-INFO
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      386 2023-06-28 14:30:10.000000 voip-utils-0.1.0/voip_utils.egg-info/SOURCES.txt
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)        1 2023-06-28 14:30:10.000000 voip-utils-0.1.0/voip_utils.egg-info/dependency_links.txt
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)       15 2023-06-28 14:30:10.000000 voip-utils-0.1.0/voip_utils.egg-info/requires.txt
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)       11 2023-06-28 14:30:10.000000 voip-utils-0.1.0/voip_utils.egg-info/top_level.txt
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)        1 2023-04-06 18:58:14.000000 voip-utils-0.1.0/voip_utils.egg-info/zip-safe
```

### Comparing `voip-utils-0.0.7/LICENSE.md` & `voip-utils-0.1.0/LICENSE.md`

 * *Files identical despite different names*

### Comparing `voip-utils-0.0.7/pyproject.toml` & `voip-utils-0.1.0/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools~=62.3", "wheel~=0.37.1"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name        = "voip-utils"
-version     = "0.0.7"
+version     = "0.1.0"
 license     = {text = "Apache-2.0"}
 description = "Voice over IP Utilities"
 readme      = "README.md"
 authors     = [
     {name = "The Home Assistant Authors", email = "hello@home-assistant.io"}
 ]
 keywords    = ["home", "assistant", "voip", "phone"]
```

### Comparing `voip-utils-0.0.7/voip_utils/rtp_audio.py` & `voip-utils-0.1.0/voip_utils/rtp_audio.py`

 * *Files identical despite different names*

### Comparing `voip-utils-0.0.7/voip_utils/sip.py` & `voip-utils-0.1.0/voip_utils/sip.py`

 * *Files 2% similar despite different names*

```diff
@@ -33,14 +33,19 @@
     caller_ip: str
     caller_sip_port: int
     caller_rtp_port: int
     server_ip: str
     headers: dict[str, str]
     opus_payload_type: int = OPUS_PAYLOAD_TYPE
 
+    @property
+    def caller_rtcp_port(self) -> int:
+        """Real-time Transport Control Protocol (RTCP) port."""
+        return self.caller_rtp_port + 1
+
 
 class SipDatagramProtocol(asyncio.DatagramProtocol, ABC):
     """UDP server for the Session Initiation Protocol (SIP)."""
 
     def __init__(self, sdp_info: SdpInfo) -> None:
         """Set up SIP server."""
         self.sdp_info = sdp_info
@@ -49,25 +54,28 @@
     def connection_made(self, transport):
         """Server ready."""
         self.transport = transport
 
     def datagram_received(self, data: bytes, addr):
         """Handle INVITE SIP messages."""
         try:
+            caller_ip, caller_sip_port = addr
             message = data.decode()
             method, ruri, headers, body = self._parse_sip(message)
 
-            if method and (method.lower() != "invite"):
+            if method:
+                method = method.lower()
+
+            if method != "invite":
                 # Not an INVITE message
                 return
 
             if not ruri:
                 raise ValueError("Empty receiver URI")
 
-            caller_ip, caller_sip_port = addr
             _LOGGER.debug(
                 "Incoming call from ip=%s, port=%s",
                 caller_ip,
                 caller_sip_port,
             )
 
             # Extract caller's RTP port from SDP.
```

