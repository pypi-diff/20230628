# Comparing `tmp/ovos_tts_plugin_piper-0.0.1a3-py3-none-any.whl.zip` & `tmp/ovos_tts_plugin_piper-0.0.1a4-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,12 +1,12 @@
-Zip file size: 11158 bytes, number of entries: 10
--rw-r--r--  2.0 unx    11941 b- defN 23-Jun-16 15:09 ovos_tts_plugin_piper/__init__.py
--rw-r--r--  2.0 unx     4518 b- defN 23-Jun-16 15:09 ovos_tts_plugin_piper/engine.py
--rw-r--r--  2.0 unx      178 b- defN 23-Jun-16 15:10 ovos_tts_plugin_piper/version.py
--rw-r--r--  2.0 unx    11349 b- defN 23-Jun-16 15:10 ovos_tts_plugin_piper-0.0.1a3.dist-info/LICENSE
--rw-r--r--  2.0 unx     1149 b- defN 23-Jun-16 15:10 ovos_tts_plugin_piper-0.0.1a3.dist-info/METADATA
--rw-r--r--  2.0 unx       92 b- defN 23-Jun-16 15:10 ovos_tts_plugin_piper-0.0.1a3.dist-info/WHEEL
--rw-r--r--  2.0 unx      186 b- defN 23-Jun-16 15:10 ovos_tts_plugin_piper-0.0.1a3.dist-info/entry_points.txt
--rw-r--r--  2.0 unx       22 b- defN 23-Jun-16 15:10 ovos_tts_plugin_piper-0.0.1a3.dist-info/top_level.txt
--rw-r--r--  2.0 unx        1 b- defN 23-Jun-16 15:10 ovos_tts_plugin_piper-0.0.1a3.dist-info/zip-safe
--rw-rw-r--  2.0 unx      948 b- defN 23-Jun-16 15:10 ovos_tts_plugin_piper-0.0.1a3.dist-info/RECORD
-10 files, 30384 bytes uncompressed, 9498 bytes compressed:  68.7%
+Zip file size: 11733 bytes, number of entries: 10
+-rw-r--r--  2.0 unx    14121 b- defN 23-Jun-28 04:38 ovos_tts_plugin_piper/__init__.py
+-rw-r--r--  2.0 unx     4775 b- defN 23-Jun-28 04:38 ovos_tts_plugin_piper/engine.py
+-rw-r--r--  2.0 unx      178 b- defN 23-Jun-28 04:38 ovos_tts_plugin_piper/version.py
+-rw-r--r--  2.0 unx    11349 b- defN 23-Jun-28 04:38 ovos_tts_plugin_piper-0.0.1a4.dist-info/LICENSE
+-rw-r--r--  2.0 unx     1149 b- defN 23-Jun-28 04:38 ovos_tts_plugin_piper-0.0.1a4.dist-info/METADATA
+-rw-r--r--  2.0 unx       92 b- defN 23-Jun-28 04:38 ovos_tts_plugin_piper-0.0.1a4.dist-info/WHEEL
+-rw-r--r--  2.0 unx      186 b- defN 23-Jun-28 04:38 ovos_tts_plugin_piper-0.0.1a4.dist-info/entry_points.txt
+-rw-r--r--  2.0 unx       22 b- defN 23-Jun-28 04:38 ovos_tts_plugin_piper-0.0.1a4.dist-info/top_level.txt
+-rw-r--r--  2.0 unx        1 b- defN 23-Jun-28 04:38 ovos_tts_plugin_piper-0.0.1a4.dist-info/zip-safe
+-rw-rw-r--  2.0 unx      948 b- defN 23-Jun-28 04:38 ovos_tts_plugin_piper-0.0.1a4.dist-info/RECORD
+10 files, 32821 bytes uncompressed, 10073 bytes compressed:  69.3%
```

## zipnote {}

```diff
@@ -3,29 +3,29 @@
 
 Filename: ovos_tts_plugin_piper/engine.py
 Comment: 
 
 Filename: ovos_tts_plugin_piper/version.py
 Comment: 
 
-Filename: ovos_tts_plugin_piper-0.0.1a3.dist-info/LICENSE
+Filename: ovos_tts_plugin_piper-0.0.1a4.dist-info/LICENSE
 Comment: 
 
-Filename: ovos_tts_plugin_piper-0.0.1a3.dist-info/METADATA
+Filename: ovos_tts_plugin_piper-0.0.1a4.dist-info/METADATA
 Comment: 
 
-Filename: ovos_tts_plugin_piper-0.0.1a3.dist-info/WHEEL
+Filename: ovos_tts_plugin_piper-0.0.1a4.dist-info/WHEEL
 Comment: 
 
-Filename: ovos_tts_plugin_piper-0.0.1a3.dist-info/entry_points.txt
+Filename: ovos_tts_plugin_piper-0.0.1a4.dist-info/entry_points.txt
 Comment: 
 
-Filename: ovos_tts_plugin_piper-0.0.1a3.dist-info/top_level.txt
+Filename: ovos_tts_plugin_piper-0.0.1a4.dist-info/top_level.txt
 Comment: 
 
-Filename: ovos_tts_plugin_piper-0.0.1a3.dist-info/zip-safe
+Filename: ovos_tts_plugin_piper-0.0.1a4.dist-info/zip-safe
 Comment: 
 
-Filename: ovos_tts_plugin_piper-0.0.1a3.dist-info/RECORD
+Filename: ovos_tts_plugin_piper-0.0.1a4.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## ovos_tts_plugin_piper/__init__.py

```diff
@@ -119,87 +119,142 @@
         'southern_english_female-low': 'https://github.com/rhasspy/piper/releases/download/v0.0.2/voice-en-gb-southern_english_female-low.tar.gz',
         'talesyntese-medium': 'https://github.com/rhasspy/piper/releases/download/v0.0.2/voice-no-talesyntese-medium.tar.gz',
         'thorsten-low': 'https://github.com/rhasspy/piper/releases/download/v0.0.2/voice-de-thorsten-low.tar.gz',
         'upc_ona-x-low': 'https://github.com/rhasspy/piper/releases/download/v0.0.2/voice-ca-upc_ona-x-low.tar.gz',
         'upc_pau-x-low': 'https://github.com/rhasspy/piper/releases/download/v0.0.2/voice-ca-upc_pau-x-low.tar.gz',
         'vos-x-low': 'https://github.com/rhasspy/piper/releases/download/v0.0.2/voice-vi-vivos-x-low.tar.gz'
     }
+    engines = {}
 
     def __init__(self, lang="en-us", config=None):
         super(PiperTTSPlugin, self).__init__(lang, config)
-        model = self.config.get("model") or \
-                self.lang2voices.get(lang) or \
-                self.lang2voices.get(lang.split("-"[0]))
-        if isinstance(model, list):
-            model = model[0]
-
-        if not os.path.isfile(model) and model in self.voice2url:
-            xdg_p = f"{xdg_data_home()}/piper_tts/{model}"
-            if not os.path.isdir(xdg_p):
-                model = self.voice2url[model]
-
-        if model.startswith("http"):
-            m = model.split("/")[-1]
-            xdg_p = f"{xdg_data_home()}/piper_tts/{m.split('.')[0]}"
-
-            model_tar = f"{xdg_p}/{m}"
-            if not os.path.isfile(model_tar):
-                LOG.info(f"downloading piper model: {model}")
-                os.makedirs(xdg_p, exist_ok=True)
-                data = requests.get(model)
-                with open(model_tar, "wb") as f:
-                    f.write(data.content)
-
-                with tarfile.open(model_tar) as file:
-                    file.extractall(xdg_p)
-            for f in os.listdir(xdg_p):
-                if f.endswith(".onnx"):
-                    model = f"{xdg_p}/{f}"
-                    LOG.debug(f"selected model: {model}")
-                    break
+        if self.voice == "default":
+            if self.lang.startswith("en"):
+                # alan pope is the default english voice of mycroft/OVOS
+                self.voice = "alan-low"
             else:
-                raise FileNotFoundError("onnx model not found")
+                self.voice = self.lang2voices.get(lang) or \
+                             self.lang2voices.get(lang.split("-"[0])) or \
+                             "alan-low"
 
-        self.model = model
-        self.model_json = self.config.get("model_json") or self.model + ".json"
         self.use_cuda = self.config.get("use_cuda", False)
-        self.engine = Piper(self.model, config_path=self.model_json, use_cuda=self.use_cuda)
-
-        self.speaker = self.config.get("speaker")  # "Id of speaker (default: 0)"
         self.noise_scale = self.config.get("noise-scale")  # generator noise
         self.length_scale = self.config.get("length-scale")  # Phoneme length
         self.noise_w = self.config.get("noise-w")  # Phoneme width noise
-        self.g2p = PiperG2P(self.engine)
 
-    def get_tts(self, sentence, wav_file, lang=None, speaker=None):
+        # pre-load models
+        preload_voices = self.config.get("preload_voices") or []
+        preload_langs = self.config.get("preload_langs") or [self.lang]
+
+        for lang in preload_langs:
+            if lang not in self.lang2voices:
+                lang = lang.split("-")[0]
+            voice = self.lang2voices.get(lang)
+            if voice and voice not in preload_voices:
+                preload_voices.append(voice)
+
+        for voice in preload_voices:
+            self.get_model(voice=voice)
+
+    def get_model(self, lang=None, voice=None, speaker=None):
+
+        # find default voice  (should be called model not voice....)
+        if voice is None and lang is not None:
+            if lang.startswith("en"):
+                # alan pope is the default english voice of mycroft/OVOS
+                voice = "alan-low"
+            else:
+                voice = self.lang2voices.get(lang) or \
+                        self.lang2voices.get(lang.split("-"[0]))
+
+        voice = voice or self.voice
+
+        if isinstance(voice, list):
+            voice = voice[0]
+
+        # find speaker  (should be called voice not speaker...)
+        if "#" in voice:
+            voice, speaker2 = voice.split("#")
+            try:
+                speaker2 = int(speaker2)
+                if speaker is not None:
+                    LOG.warning("requested voice and speaker args conflict, "
+                                "ignoring requested speaker in favor of speaker defined in voice string")
+                    speaker = speaker2
+            except:
+                LOG.warning("invalid speaker requested in voice string, ignoring it")
+
+        speaker = speaker or 0  # default for this model
+
+        # pre-loaded models
+        if voice in PiperTTSPlugin.engines:
+            return PiperTTSPlugin.engines[voice], speaker
+
+        # find requested voice
+        if voice in self.voice2url:
+            xdg_p = f"{xdg_data_home()}/piper_tts/{voice}"
+            if not os.path.isdir(xdg_p):
+                url = self.voice2url[voice]
+
+                m = url.split("/")[-1]
+                xdg_p = f"{xdg_data_home()}/piper_tts/{m.split('.')[0]}"
+
+                model_tar = f"{xdg_p}/{m}"
+                if not os.path.isfile(model_tar):
+                    LOG.info(f"downloading piper model: {url}")
+                    os.makedirs(xdg_p, exist_ok=True)
+                    # TODO - streaming download
+                    data = requests.get(url)
+                    with open(model_tar, "wb") as f:
+                        f.write(data.content)
+                    with tarfile.open(model_tar) as file:
+                        file.extractall(xdg_p)
+
+                for f in os.listdir(xdg_p):
+                    if f.endswith(".onnx"):
+                        model = f"{xdg_p}/{f}"
+                        engine = Piper(model, config_path=model + ".json", use_cuda=self.use_cuda)
+                        LOG.debug(f"loaded model: {model}")
+                        PiperTTSPlugin.engines[voice] = engine
+                        return engine, speaker
+                else:
+                    raise FileNotFoundError("onnx model not found")
+        else:
+            raise ValueError(f"invalid voice: {voice}")
+
+    def get_tts(self, sentence, wav_file, lang=None, voice=None, speaker=None):
         """Generate WAV and phonemes.
 
         Arguments:
             sentence (str): sentence to generate audio for
             wav_file (str): output file
             lang (str): optional lang override
+            voice (str): optional voice override
             speaker (int): optional speaker override
 
         Returns:
             tuple ((str) file location, (str) generated phonemes)
         """
         lang = lang or self.lang
         # HACK: bug in some neon-core versions - neon_audio.tts.neon:_get_tts:198 - INFO - Legacy Neon TTS signature found 
         if isinstance(speaker, dict):
             LOG.warning("Legacy Neon TTS signature found, pass speaker as a str")
             speaker = None
-        wav_bytes = self.engine.synthesize(sentence,
-                                           speaker_id=speaker or self.speaker,
-                                           length_scale=self.length_scale,
-                                           noise_scale=self.noise_scale,
-                                           noise_w=self.noise_w)
+
+        engine, speaker = self.get_model(lang, voice, speaker)
+
+        wav_bytes = engine.synthesize(sentence,
+                                      speaker_id=speaker,
+                                      length_scale=self.length_scale,
+                                      noise_scale=self.noise_scale,
+                                      noise_w=self.noise_w)
         with open(wav_file, "wb") as f:
             f.write(wav_bytes)
 
-        phonemes = self.g2p.utterance2arpa(sentence, lang, ignore_oov=True)
+        phonemes = PiperG2P(engine).utterance2arpa(sentence, lang, ignore_oov=True)
         phonemes = " ".join([f"{p}:0.4" for p in phonemes])
 
         return wav_file, phonemes
 
     def available_languages(self) -> set:
         return set(self.lang2voices.keys())
 
@@ -208,10 +263,11 @@
     lang: [{v: {"model": PiperTTSPlugin.voice2url[v], "offline": True}}
            for v in voices]
     for lang, voices in PiperTTSPlugin.lang2voices.items()
 }
 
 if __name__ == "__main__":
     config = {}
-    config["model"] = "alan-low"
+    config["lang"] = "en-us"
     e = PiperTTSPlugin(config=config)
-    e.get_tts( "one oh clock", "hello.wav")
+    e.get_tts("one oh clock", "hello.wav")
+    e.get_tts("one oh clock", "libritts-high.wav", voice="libritts-high")
```

## ovos_tts_plugin_piper/engine.py

```diff
@@ -5,14 +5,15 @@
 from dataclasses import dataclass
 from pathlib import Path
 from typing import List, Mapping, Optional, Sequence, Union
 
 import numpy as np
 import onnxruntime
 from espeak_phonemizer import Phonemizer
+from ovos_utils.log import LOG
 
 _BOS = "^"
 _EOS = "$"
 _PAD = "_"
 
 
 @dataclass
@@ -25,18 +26,18 @@
     noise_scale: float
     noise_w: float
     phoneme_id_map: Mapping[str, Sequence[int]]
 
 
 class Piper:
     def __init__(
-        self,
-        model_path: Union[str, Path],
-        config_path: Optional[Union[str, Path]] = None,
-        use_cuda: bool = False,
+            self,
+            model_path: Union[str, Path],
+            config_path: Optional[Union[str, Path]] = None,
+            use_cuda: bool = False,
     ):
         if config_path is None:
             config_path = f"{model_path}.json"
 
         self.config = load_config(config_path)
         self.phonemizer = Phonemizer(self.config.espeak_voice)
         self.onnx_options = onnxruntime.SessionOptions()
@@ -46,20 +47,20 @@
             sess_options=self.onnx_options,
             providers=["CPUExecutionProvider"]
             if not use_cuda
             else ["CUDAExecutionProvider"],
         )
 
     def synthesize(
-        self,
-        text: str,
-        speaker_id: Optional[int] = None,
-        length_scale: Optional[float] = None,
-        noise_scale: Optional[float] = None,
-        noise_w: Optional[float] = None,
+            self,
+            text: str,
+            speaker_id: Optional[int] = None,
+            length_scale: Optional[float] = None,
+            noise_scale: Optional[float] = None,
+            noise_w: Optional[float] = None,
     ) -> bytes:
         """Synthesize WAV audio from text."""
         if length_scale is None:
             length_scale = self.config.length_scale
 
         if noise_scale is None:
             noise_scale = self.config.noise_scale
@@ -68,45 +69,48 @@
             noise_w = self.config.noise_w
 
         phonemes_str = self.phonemizer.phonemize(text)
         phonemes = [_BOS] + list(phonemes_str)
         phoneme_ids: List[int] = []
 
         for phoneme in phonemes:
-            phoneme_ids.extend(self.config.phoneme_id_map[phoneme])
-            phoneme_ids.extend(self.config.phoneme_id_map[_PAD])
+            if phoneme in self.config.phoneme_id_map:
+                phoneme_ids.extend(self.config.phoneme_id_map[phoneme])
+                phoneme_ids.extend(self.config.phoneme_id_map[_PAD])
+            else:
+                LOG.warning("No id for phoneme: %s", phoneme)
 
         phoneme_ids.extend(self.config.phoneme_id_map[_EOS])
 
         phoneme_ids_array = np.expand_dims(np.array(phoneme_ids, dtype=np.int64), 0)
         phoneme_ids_lengths = np.array([phoneme_ids_array.shape[1]], dtype=np.int64)
         scales = np.array(
             [noise_scale, length_scale, noise_w],
             dtype=np.float32,
         )
 
-        if (self.config.num_speakers > 1) and (speaker_id is not None):
+        args = {
+                "input": phoneme_ids_array,
+                "input_lengths": phoneme_ids_lengths,
+                "scales": scales
+            }
+
+        if self.config.num_speakers <= 1:
+            speaker_id = None
+
+        if (self.config.num_speakers > 1) and (speaker_id is None):
             # Default speaker
             speaker_id = 0
 
-        sid = None
-
         if speaker_id is not None:
             sid = np.array([speaker_id], dtype=np.int64)
+            args["sid"] = sid
 
         # Synthesize through Onnx
-        audio = self.model.run(
-            None,
-            {
-                "input": phoneme_ids_array,
-                "input_lengths": phoneme_ids_lengths,
-                "scales": scales,
-                "sid": sid,
-            },
-        )[0].squeeze((0, 1))
+        audio = self.model.run(  None, args, )[0].squeeze((0, 1))
         audio = audio_float_to_int16(audio.squeeze())
 
         # Convert to WAV
         with io.BytesIO() as wav_io:
             wav_file: wave.Wave_write = wave.open(wav_io, "wb")
             with wav_file:
                 wav_file.setframerate(self.config.sample_rate)
@@ -131,14 +135,14 @@
             length_scale=inference.get("length_scale", 1.0),
             noise_w=inference.get("noise_w", 0.8),
             phoneme_id_map=config_dict["phoneme_id_map"],
         )
 
 
 def audio_float_to_int16(
-    audio: np.ndarray, max_wav_value: float = 32767.0
+        audio: np.ndarray, max_wav_value: float = 32767.0
 ) -> np.ndarray:
     """Normalize audio and convert to int16 range"""
     audio_norm = audio * (max_wav_value / max(0.01, np.max(np.abs(audio))))
     audio_norm = np.clip(audio_norm, -max_wav_value, max_wav_value)
     audio_norm = audio_norm.astype("int16")
     return audio_norm
```

## ovos_tts_plugin_piper/version.py

```diff
@@ -1,8 +1,8 @@
 
 # The following lines are replaced during the release process.
 # START_VERSION_BLOCK
 VERSION_MAJOR = 0
 VERSION_MINOR = 0
 VERSION_BUILD = 1
-VERSION_ALPHA = 3
+VERSION_ALPHA = 4
 # END_VERSION_BLOCK
```

## Comparing `ovos_tts_plugin_piper-0.0.1a3.dist-info/LICENSE` & `ovos_tts_plugin_piper-0.0.1a4.dist-info/LICENSE`

 * *Files identical despite different names*

## Comparing `ovos_tts_plugin_piper-0.0.1a3.dist-info/METADATA` & `ovos_tts_plugin_piper-0.0.1a4.dist-info/METADATA`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ovos-tts-plugin-piper
-Version: 0.0.1a3
+Version: 0.0.1a4
 Summary: piper tts plugin for OpenVoiceOS
 Home-page: https://github.com/OpenVoiceOS/ovos-tts-plugin-piper
 Author: JarbasAi
 Author-email: jarbasai@mailfence.com
 License: Apache-2.0
 Keywords: mycroft plugin tts OVOS OpenVoiceOS
 Platform: UNKNOWN
@@ -19,13 +19,13 @@
 Classifier: Programming Language :: Python :: 3.1
 Classifier: Programming Language :: Python :: 3.2
 Classifier: Programming Language :: Python :: 3.3
 Classifier: Programming Language :: Python :: 3.4
 Classifier: Programming Language :: Python :: 3.5
 Classifier: Programming Language :: Python :: 3.6
 Requires-Dist: espeak-phonemizer (<2,>=1.1.0)
-Requires-Dist: onnxruntime (~=1.11.0)
+Requires-Dist: onnxruntime (>=1.11.0)
 Requires-Dist: ovos-plugin-manager (>=0.0.5)
 
 UNKNOWN
```

## Comparing `ovos_tts_plugin_piper-0.0.1a3.dist-info/RECORD` & `ovos_tts_plugin_piper-0.0.1a4.dist-info/RECORD`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
-ovos_tts_plugin_piper/__init__.py,sha256=i_13K29JY_mQ5PRTUzrIASjlp8fIpWfLaTIdKsMB0ao,11941
-ovos_tts_plugin_piper/engine.py,sha256=WEB-2Uu9cmN3UQrltWYbB0PH1H0X03Fg6OnGXW-GS0s,4518
-ovos_tts_plugin_piper/version.py,sha256=1kOb_nNh8ZsaH74zSf8NWpgMXkebA0xQj0qV5fxYHQw,178
-ovos_tts_plugin_piper-0.0.1a3.dist-info/LICENSE,sha256=fYHkowW9JcaEcqCPTXYBayNJ9J1lGdYVb7Mf9oy6oEY,11349
-ovos_tts_plugin_piper-0.0.1a3.dist-info/METADATA,sha256=1HbturDPM797qXxfbQFA4N48RkH07zV6wMQ58GOcJ5A,1149
-ovos_tts_plugin_piper-0.0.1a3.dist-info/WHEEL,sha256=pkctZYzUS4AYVn6dJ-7367OJZivF2e8RA9b_ZBjif18,92
-ovos_tts_plugin_piper-0.0.1a3.dist-info/entry_points.txt,sha256=eHpADEdMHzf8Y-h30EKm587TkxMsv91Xb98ph3DgRUY,186
-ovos_tts_plugin_piper-0.0.1a3.dist-info/top_level.txt,sha256=WTvxxS42UAwh0oi25ypLaxvMGD85j_wGzrux2QFoqLs,22
-ovos_tts_plugin_piper-0.0.1a3.dist-info/zip-safe,sha256=AbpHGcgLb-kRsJGnwFEktk7uzpZOCcBY74-YBdrKVGs,1
-ovos_tts_plugin_piper-0.0.1a3.dist-info/RECORD,,
+ovos_tts_plugin_piper/__init__.py,sha256=-VeFKYWzADQnZSBixDtv1S6liFX2WcH-UE6NQg9Wwck,14121
+ovos_tts_plugin_piper/engine.py,sha256=zCEcyQiCkqMp_JZgkLUdKniZdV_S7bAuAqbEIXLBwkw,4775
+ovos_tts_plugin_piper/version.py,sha256=pPGons65SGY5CFphxdRwgUgJMA4kd2_LF5pAGxgWu-k,178
+ovos_tts_plugin_piper-0.0.1a4.dist-info/LICENSE,sha256=fYHkowW9JcaEcqCPTXYBayNJ9J1lGdYVb7Mf9oy6oEY,11349
+ovos_tts_plugin_piper-0.0.1a4.dist-info/METADATA,sha256=flO4dUXKXU_6xKaMDQ_QkaSpmD5s9KJyGosqY_2uWSg,1149
+ovos_tts_plugin_piper-0.0.1a4.dist-info/WHEEL,sha256=pkctZYzUS4AYVn6dJ-7367OJZivF2e8RA9b_ZBjif18,92
+ovos_tts_plugin_piper-0.0.1a4.dist-info/entry_points.txt,sha256=eHpADEdMHzf8Y-h30EKm587TkxMsv91Xb98ph3DgRUY,186
+ovos_tts_plugin_piper-0.0.1a4.dist-info/top_level.txt,sha256=WTvxxS42UAwh0oi25ypLaxvMGD85j_wGzrux2QFoqLs,22
+ovos_tts_plugin_piper-0.0.1a4.dist-info/zip-safe,sha256=AbpHGcgLb-kRsJGnwFEktk7uzpZOCcBY74-YBdrKVGs,1
+ovos_tts_plugin_piper-0.0.1a4.dist-info/RECORD,,
```

