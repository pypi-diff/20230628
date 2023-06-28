# Comparing `tmp/streamlit_chatbox-0.2.0-py3-none-any.whl.zip` & `tmp/streamlit_chatbox-0.2.1-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,7 +1,7 @@
-Zip file size: 4318 bytes, number of entries: 5
--rw-rw-rw-  2.0 fat     8577 b- defN 23-May-30 13:45 streamlit_chatbox/__init__.py
--rw-rw-rw-  2.0 fat     1927 b- defN 23-May-31 04:24 streamlit_chatbox-0.2.0.dist-info/METADATA
--rw-rw-rw-  2.0 fat       92 b- defN 23-May-31 04:24 streamlit_chatbox-0.2.0.dist-info/WHEEL
--rw-rw-rw-  2.0 fat       18 b- defN 23-May-31 04:24 streamlit_chatbox-0.2.0.dist-info/top_level.txt
-?rw-rw-r--  2.0 fat      424 b- defN 23-May-31 04:24 streamlit_chatbox-0.2.0.dist-info/RECORD
-5 files, 11038 bytes uncompressed, 3522 bytes compressed:  68.1%
+Zip file size: 4845 bytes, number of entries: 5
+-rw-rw-rw-  2.0 fat    10013 b- defN 23-Jun-28 13:06 streamlit_chatbox/__init__.py
+-rw-rw-rw-  2.0 fat     2057 b- defN 23-Jun-28 13:09 streamlit_chatbox-0.2.1.dist-info/METADATA
+-rw-rw-rw-  2.0 fat       92 b- defN 23-Jun-28 13:09 streamlit_chatbox-0.2.1.dist-info/WHEEL
+-rw-rw-rw-  2.0 fat       18 b- defN 23-Jun-28 13:09 streamlit_chatbox-0.2.1.dist-info/top_level.txt
+?rw-rw-r--  2.0 fat      425 b- defN 23-Jun-28 13:09 streamlit_chatbox-0.2.1.dist-info/RECORD
+5 files, 12605 bytes uncompressed, 4049 bytes compressed:  67.9%
```

## zipnote {}

```diff
@@ -1,16 +1,16 @@
 Filename: streamlit_chatbox/__init__.py
 Comment: 
 
-Filename: streamlit_chatbox-0.2.0.dist-info/METADATA
+Filename: streamlit_chatbox-0.2.1.dist-info/METADATA
 Comment: 
 
-Filename: streamlit_chatbox-0.2.0.dist-info/WHEEL
+Filename: streamlit_chatbox-0.2.1.dist-info/WHEEL
 Comment: 
 
-Filename: streamlit_chatbox-0.2.0.dist-info/top_level.txt
+Filename: streamlit_chatbox-0.2.1.dist-info/top_level.txt
 Comment: 
 
-Filename: streamlit_chatbox-0.2.0.dist-info/RECORD
+Filename: streamlit_chatbox-0.2.1.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## streamlit_chatbox/__init__.py

```diff
@@ -1,9 +1,10 @@
 import streamlit as st
 import time
+# from streamlit_option_menu import option_menu
 
 
 class MsgType:
     TEXT = 1
     IMAGE = 2
     VIDEO = 3
     AUDIO = 4
@@ -51,14 +52,15 @@
     def welcomed(self, val):
         st.session_state[self.session_var]['welcomed'] = bool(val)
 
     def format_md(self, msg, is_user=False, bg_color=None, margin=None, border=None):
         '''
         将文本消息格式化为markdown文本
         '''
+        msg = '\n' + msg.strip() # prepend '\n' to make first line paragraph
         margin = margin or self.box_margin
         border = border or self.box_border
         if is_user:
             bg_color = bg_color or self.user_bg_color
             text = f'''
                     <div style="background:{bg_color};
                             margin-left:{margin};
@@ -225,7 +227,45 @@
         box_margin=box_margin,
         box_border=box_border,
         user_bg_color=user_bg_color,
         user_icon=user_icon,
         robot_bg_color=robot_bg_color,
         robot_icon=robot_icon
     )
+
+
+def _msg_type_format_func(val):
+    return {
+        MsgType.TEXT: 'TEXT',
+        MsgType.IMAGE: 'IMAGE',
+        MsgType.VIDEO: 'VIDEO',
+        MsgType.AUDIO: 'AUDIO',
+    }[val]
+
+
+# def st_chat_input(
+#     prefix='chat',
+#     send_btn='send',
+#     ):
+
+#     cols1 = st.columns([1, 5])
+#     msg_type = cols1[0].selectbox(
+#                     'MsgType',
+#                     [MsgType.TEXT, MsgType.IMAGE, MsgType.VIDEO, MsgType.AUDIO],
+#                     # label_visibility='collapsed',
+#                     format_func=_msg_type_format_func,
+#                     )
+#     with cols1[1].form(f'{prefix}_input_form', clear_on_submit=True):
+#         cols2 = st.columns([5, 1])
+#         if msg_type == MsgType.TEXT:
+#             msg = cols2[0].text_input('text', label_visibility='collapsed')
+#         elif msg_type == MsgType.IMAGE:
+#             msg = None
+#             cols3 = cols2[0].columns(2)
+#             file = cols3[0].file_uploader('file', ['jpg', 'bmp', 'jpeg', 'png'], label_visibility='collapsed')
+#             clipboard = cols3[0].button('从剪切板粘贴')
+#             if file:
+#                 cols3[1].image(file)
+#                 msg = file.getvalue()
+                
+
+#         submit = cols2[1].form_submit_button(send_btn)
```

## Comparing `streamlit_chatbox-0.2.0.dist-info/METADATA` & `streamlit_chatbox-0.2.1.dist-info/METADATA`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: streamlit-chatbox
-Version: 0.2.0
+Version: 0.2.1
 Summary: A chat box used in streamlit
 Home-page: https://github.com/liunux4odoo/streamlit-chatbox
 Author: liunux
 Author-email: liunux@qq.com
 License: UNKNOWN
 Platform: UNKNOWN
 Requires-Python: >=3.6
@@ -63,19 +63,24 @@
 
 ![demo](https://github.com/liunux4odoo/streamlit-chatbox/blob/master/demo.gif)
 
 
 ## Todos
 
 - input messages:
-	- [ x ] TEXT
-	- [   ] IMAGE
-	- [   ] VIDEO
-	- [   ] AUDIO
+	- [x] TEXT
+	- [ ] IMAGE
+		- [ ] file upload
+		- [ ] paste from clipboard(streamlit_bokeh_events)
+	- [ ] VIDEO
+		- [ ] file upload
+	- [ ] AUDIO
+		- [ ] file upload
+		- [ ] audio-recorder-streamlit
 
 - output messages:
-	- [ x ] TEXT
-	- [ x ] IMAGE
-	- [ x ] VIDEO
-	- [ x ] AUDIO
+	- [x] TEXT
+	- [x] IMAGE
+	- [x] VIDEO
+	- [x] AUDIO
```

