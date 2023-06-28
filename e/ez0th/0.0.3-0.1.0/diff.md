# Comparing `tmp/ez0th-0.0.3.tar.gz` & `tmp/ez0th-0.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ez0th-0.0.3.tar", last modified: Mon May 29 10:31:53 2023, max compression
+gzip compressed data, was "ez0th-0.1.0.tar", last modified: Wed Jun 28 08:28:25 2023, max compression
```

## Comparing `ez0th-0.0.3.tar` & `ez0th-0.1.0.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxrwxrwx   0        0        0        0 2023-05-29 10:31:53.897068 ez0th-0.0.3/
--rw-rw-rw-   0        0        0    11225 2023-05-29 10:31:53.897068 ez0th-0.0.3/PKG-INFO
--rw-rw-rw-   0        0        0     9291 2023-05-29 10:31:14.000000 ez0th-0.0.3/README.md
-drwxrwxrwx   0        0        0        0 2023-05-29 10:31:53.883283 ez0th-0.0.3/ez0th/
--rw-rw-rw-   0        0        0     7763 2023-05-29 10:07:37.000000 ez0th-0.0.3/ez0th/__init__.py
--rw-rw-rw-   0        0        0     2127 2023-05-29 10:08:47.000000 ez0th-0.0.3/ez0th/test.py
-drwxrwxrwx   0        0        0        0 2023-05-29 10:31:53.895117 ez0th-0.0.3/ez0th.egg-info/
--rw-rw-rw-   0        0        0    11225 2023-05-29 10:31:53.000000 ez0th-0.0.3/ez0th.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      194 2023-05-29 10:31:53.000000 ez0th-0.0.3/ez0th.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-05-29 10:31:53.000000 ez0th-0.0.3/ez0th.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       45 2023-05-29 10:31:53.000000 ez0th-0.0.3/ez0th.egg-info/requires.txt
--rw-rw-rw-   0        0        0        6 2023-05-29 10:31:53.000000 ez0th-0.0.3/ez0th.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-05-29 10:31:53.898147 ez0th-0.0.3/setup.cfg
--rw-rw-rw-   0        0        0      801 2023-05-29 10:31:49.000000 ez0th-0.0.3/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:28:25.880144 ez0th-0.1.0/
+-rw-rw-rw-   0        0        0    12347 2023-06-28 08:28:25.880144 ez0th-0.1.0/PKG-INFO
+-rw-rw-rw-   0        0        0    10141 2023-06-28 08:27:15.000000 ez0th-0.1.0/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 08:28:25.867735 ez0th-0.1.0/ez0th/
+-rw-rw-rw-   0        0        0     9321 2023-06-28 08:22:15.000000 ez0th-0.1.0/ez0th/__init__.py
+-rw-rw-rw-   0        0        0     2686 2023-06-28 08:24:43.000000 ez0th-0.1.0/ez0th/test.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:28:25.878644 ez0th-0.1.0/ez0th.egg-info/
+-rw-rw-rw-   0        0        0    12347 2023-06-28 08:28:25.000000 ez0th-0.1.0/ez0th.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      194 2023-06-28 08:28:25.000000 ez0th-0.1.0/ez0th.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:28:25.000000 ez0th-0.1.0/ez0th.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       45 2023-06-28 08:28:25.000000 ez0th-0.1.0/ez0th.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 08:28:25.000000 ez0th-0.1.0/ez0th.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 08:28:25.881149 ez0th-0.1.0/setup.cfg
+-rw-rw-rw-   0        0        0      801 2023-06-28 08:28:00.000000 ez0th-0.1.0/setup.py
```

### Comparing `ez0th-0.0.3/PKG-INFO` & `ez0th-0.1.0/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ez0th
-Version: 0.0.3
+Version: 0.1.0
 Summary: Python Library for Easy Authentication and Authorization
 Home-page: https://github.co.jp/
 Author: bib_inf
 Author-email: contact.bibinf@gmail.com
 License: CC0 v1.0
 Description: # ez0th - Python Library for Easy Authentication and Authorization
         
@@ -75,14 +75,31 @@
             send_func = send_func,  # Mail sending function etc. (argument: sess_token (for creating confirmation URL))
             db = db,    # Database
             timeout = 1 # Timeout period (in hours; infinite if specified as inf)
         )
         # Result confirmation
         print(sent_flag)
         
+        # Password change [ez0th]
+        success_flag = ez0th.change_pw(
+            sess_token = sess_token,    # Session token
+            password = "abc123456", # New password
+            db = db,    # Database
+        )
+        # Check result
+        print(success_flag)
+        
+        # Logout [ez0th]
+        success_flag = ez0th.logout(
+            sess_token = sess_token,    # Session token
+            db = db # Database
+        )
+        # Check result
+        print(success_flag)
+        
         # Check the database
         import json_stock as jst
         print("db_state:")
         print(jst.JsonStock("__ez0th_user_db__"))
         ```
         
         ## Creating Custom Connection Functions
@@ -169,14 +186,31 @@
             send_func = send_func,  # メール送信等の関数 (引数: sess_token (確認URL作成用))
             db = db,    # データベース
             timeout = 1 # タイムアウト時間 (時間単位; inf指定で無限大)
         )
         # 結果確認
         print(sent_flag)
         
+        # パスワード変更 [ez0th]
+        success_flag = ez0th.change_pw(
+            sess_token = sess_token,    # セッショントークン
+            password = "abc123456", # 変更後のパスワード
+            db = db,    # データベース
+        )
+        # 結果確認
+        print(success_flag)
+        
+        # ログアウト [ez0th]
+        success_flag = ez0th.logout(
+            sess_token = sess_token,    # セッショントークン
+            db = db # データベース
+        )
+        # 結果確認
+        print(success_flag)
+        
         # db確認
         import json_stock as jst
         print("db_state:")
         print(jst.JsonStock("__ez0th_user_db__"))
         ```
         
         ## カスタム接続関数の作成方法
```

### Comparing `ez0th-0.0.3/README.md` & `ez0th-0.1.0/README.md`

 * *Files 10% similar despite different names*

```diff
@@ -67,14 +67,31 @@
     send_func = send_func,  # Mail sending function etc. (argument: sess_token (for creating confirmation URL))
     db = db,    # Database
     timeout = 1 # Timeout period (in hours; infinite if specified as inf)
 )
 # Result confirmation
 print(sent_flag)
 
+# Password change [ez0th]
+success_flag = ez0th.change_pw(
+    sess_token = sess_token,    # Session token
+    password = "abc123456", # New password
+    db = db,    # Database
+)
+# Check result
+print(success_flag)
+
+# Logout [ez0th]
+success_flag = ez0th.logout(
+    sess_token = sess_token,    # Session token
+    db = db # Database
+)
+# Check result
+print(success_flag)
+
 # Check the database
 import json_stock as jst
 print("db_state:")
 print(jst.JsonStock("__ez0th_user_db__"))
 ```
 
 ## Creating Custom Connection Functions
@@ -161,14 +178,31 @@
     send_func = send_func,  # メール送信等の関数 (引数: sess_token (確認URL作成用))
     db = db,    # データベース
     timeout = 1 # タイムアウト時間 (時間単位; inf指定で無限大)
 )
 # 結果確認
 print(sent_flag)
 
+# パスワード変更 [ez0th]
+success_flag = ez0th.change_pw(
+    sess_token = sess_token,    # セッショントークン
+    password = "abc123456", # 変更後のパスワード
+    db = db,    # データベース
+)
+# 結果確認
+print(success_flag)
+
+# ログアウト [ez0th]
+success_flag = ez0th.logout(
+    sess_token = sess_token,    # セッショントークン
+    db = db # データベース
+)
+# 結果確認
+print(success_flag)
+
 # db確認
 import json_stock as jst
 print("db_state:")
 print(jst.JsonStock("__ez0th_user_db__"))
 ```
 
 ## カスタム接続関数の作成方法
```

### Comparing `ez0th-0.0.3/ez0th/__init__.py` & `ez0th-0.1.0/ez0th/__init__.py`

 * *Files 14% similar despite different names*

```diff
@@ -154,14 +154,16 @@
 		check_injection(sess_token, ptn = "sess_token_")	# 引数インジェクションチェック (セキュリティー対策; ptnを満たす文字列かどうかをチェック)
 	except:
 		return False, "invalid_sess_token"
 	# セッショントークンの実在性確認
 	if db["contains"](sess_token) is False: return False, "invalid_sess_token"
 	# セッション情報の取得
 	sess_info = db["read"](sess_token)
+	# アカウント情報を追記
+	sess_info["account_info"] = db["read"](sess_info["inner_id"])
 	# セッションの有効期限の確認
 	if sess_info["expire_time"] != "inf":
 		if time.time() > sess_info["expire_time"]: return False, "the_session_has_expired"
 	# 有効なセッショントークン
 	return True, sess_info
 
 # 連絡先実在確認機能 (メール確認等) [ez0th]
@@ -181,7 +183,47 @@
 	sess_token = gen_sess_token(inner_id, timeout, db)
 	# メール送信等
 	try:
 		send_func(sess_token)
 		return True
 	except:
 		return False
+
+# ログアウト [ez0th]
+def logout(
+	sess_token,	# セッショントークン
+	db = "auto"	# データベース
+):
+	# 引数インジェクションチェック (セキュリティー対策; ptnを満たす文字列かどうかをチェック)
+	check_injection(sess_token, ptn = "sess_token_")
+	try:
+		# セッションを無効化 (DBから削除)
+		db["delete"](sess_token)
+		return True
+	except:
+		return False
+
+# パスワード変更 [ez0th]
+def change_pw(
+	sess_token,	# セッショントークン
+	password,	# パスワード
+	db = "auto",	# データベース
+):
+	if db == "auto": db = json_stock("./__ez0th_user_db__/")
+	# 引数インジェクションチェック (セキュリティー対策; ptnを満たす文字列かどうかをチェック)
+	check_injection(sess_token, ptn = "sess_token_")
+	check_injection(password)	# 引数インジェクションチェック (セキュリティー対策; ptnを満たす文字列かどうかをチェック)
+	# 認可 (ログイン確認) [ez0th]
+	flag, info = auth(sess_token, db)
+	if flag is False: return False
+	# 内部ユーザーidの取得
+	inner_id = info["inner_id"]
+	# パスワードのハッシュ化 (パスワードを安全に保管するため)
+	pw_salt, pw_hash = gen_pw_hash(password)
+	# DBの更新
+	try:
+		db["update"](inner_id,
+			{**db["read"](inner_id), "pw_salt": pw_salt, "pw_hash": pw_hash}
+		)
+		return True
+	except:
+		return False
```

### Comparing `ez0th-0.0.3/ez0th/test.py` & `ez0th-0.1.0/ez0th/test.py`

 * *Files 8% similar despite different names*

```diff
@@ -30,15 +30,15 @@
 # 結果確認
 print(success_flag)
 print(sess_token)
 
 # 認可 (ログイン確認) [ez0th]
 success_flag, info = ez0th.auth(
 	sess_token = sess_token,	# セッショントークン
-	db = "auto"	# データベース
+	db = db	# データベース
 )
 # 結果確認
 print(success_flag)
 print(info)
 
 # 連絡先確認関数
 def send_func(sess_token):
@@ -50,12 +50,32 @@
 	send_func = send_func,	# メール送信等の関数 (引数: sess_token (確認URL作成用))
 	db = db,	# データベース
 	timeout = 1	# タイムアウト時間 (時間単位; inf指定で無限大)
 )
 # 結果確認
 print(sent_flag)
 
+# パスワード変更 [ez0th]
+success_flag = ez0th.change_pw(
+	sess_token = sess_token,	# セッショントークン
+	password = "abc123456",	# 変更後のパスワード
+	db = db,	# データベース
+)
+# 結果確認
+print(success_flag)
+
+# 次回のための再変更
+success_flag = ez0th.change_pw(sess_token, "abc123", db)	# パスワード変更 [ez0th]
+
+# ログアウト [ez0th]
+success_flag = ez0th.logout(
+	sess_token = sess_token,	# セッショントークン
+	db = db	# データベース
+)
+# 結果確認
+print(success_flag)
+
 # db確認
 import json_stock as jst
 print("db_state:")
 print(jst.JsonStock("__ez0th_user_db__"))
 sys.exit()
```

### Comparing `ez0th-0.0.3/ez0th.egg-info/PKG-INFO` & `ez0th-0.1.0/ez0th.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ez0th
-Version: 0.0.3
+Version: 0.1.0
 Summary: Python Library for Easy Authentication and Authorization
 Home-page: https://github.co.jp/
 Author: bib_inf
 Author-email: contact.bibinf@gmail.com
 License: CC0 v1.0
 Description: # ez0th - Python Library for Easy Authentication and Authorization
         
@@ -75,14 +75,31 @@
             send_func = send_func,  # Mail sending function etc. (argument: sess_token (for creating confirmation URL))
             db = db,    # Database
             timeout = 1 # Timeout period (in hours; infinite if specified as inf)
         )
         # Result confirmation
         print(sent_flag)
         
+        # Password change [ez0th]
+        success_flag = ez0th.change_pw(
+            sess_token = sess_token,    # Session token
+            password = "abc123456", # New password
+            db = db,    # Database
+        )
+        # Check result
+        print(success_flag)
+        
+        # Logout [ez0th]
+        success_flag = ez0th.logout(
+            sess_token = sess_token,    # Session token
+            db = db # Database
+        )
+        # Check result
+        print(success_flag)
+        
         # Check the database
         import json_stock as jst
         print("db_state:")
         print(jst.JsonStock("__ez0th_user_db__"))
         ```
         
         ## Creating Custom Connection Functions
@@ -169,14 +186,31 @@
             send_func = send_func,  # メール送信等の関数 (引数: sess_token (確認URL作成用))
             db = db,    # データベース
             timeout = 1 # タイムアウト時間 (時間単位; inf指定で無限大)
         )
         # 結果確認
         print(sent_flag)
         
+        # パスワード変更 [ez0th]
+        success_flag = ez0th.change_pw(
+            sess_token = sess_token,    # セッショントークン
+            password = "abc123456", # 変更後のパスワード
+            db = db,    # データベース
+        )
+        # 結果確認
+        print(success_flag)
+        
+        # ログアウト [ez0th]
+        success_flag = ez0th.logout(
+            sess_token = sess_token,    # セッショントークン
+            db = db # データベース
+        )
+        # 結果確認
+        print(success_flag)
+        
         # db確認
         import json_stock as jst
         print("db_state:")
         print(jst.JsonStock("__ez0th_user_db__"))
         ```
         
         ## カスタム接続関数の作成方法
```

### Comparing `ez0th-0.0.3/setup.py` & `ez0th-0.1.0/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -9,15 +9,15 @@
 00000080: 205b 657a 7069 705d 0d0a 7769 7468 2065   [ezpip]..with e
 00000090: 7a70 6970 2e70 6163 6b61 6765 7228 6465  zpip.packager(de
 000000a0: 7665 6c6f 705f 6469 7220 3d20 222e 2f5f  velop_dir = "./_
 000000b0: 6465 7665 6c6f 705f 657a 3074 682f 2229  develop_ez0th/")
 000000c0: 2061 7320 703a 0d0a 0973 6574 7570 280d   as p:...setup(.
 000000d0: 0a09 096e 616d 6520 3d20 2265 7a30 7468  ...name = "ez0th
 000000e0: 222c 0d0a 0909 7665 7273 696f 6e20 3d20  ",....version = 
-000000f0: 2230 2e30 2e33 222c 0d0a 0909 6465 7363  "0.0.3",....desc
+000000f0: 2230 2e31 2e30 222c 0d0a 0909 6465 7363  "0.1.0",....desc
 00000100: 7269 7074 696f 6e20 3d20 2250 7974 686f  ription = "Pytho
 00000110: 6e20 4c69 6272 6172 7920 666f 7220 4561  n Library for Ea
 00000120: 7379 2041 7574 6865 6e74 6963 6174 696f  sy Authenticatio
 00000130: 6e20 616e 6420 4175 7468 6f72 697a 6174  n and Authorizat
 00000140: 696f 6e22 2c0d 0a09 0961 7574 686f 7220  ion",....author 
 00000150: 3d20 2262 6962 5f69 6e66 222c 0d0a 0909  = "bib_inf",....
 00000160: 6175 7468 6f72 5f65 6d61 696c 203d 2022  author_email = "
```

