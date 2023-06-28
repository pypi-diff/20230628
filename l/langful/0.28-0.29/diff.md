# Comparing `tmp/langful-0.28-py2.py3-none-any.whl.zip` & `tmp/langful-0.29-py2.py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,9 +1,9 @@
-Zip file size: 4655 bytes, number of entries: 7
+Zip file size: 5118 bytes, number of entries: 7
 -rw-rw-rw-  2.0 fat      224 b- defN 23-Jun-20 12:20 langful/__init__.py
--rw-rw-rw-  2.0 fat     6933 b- defN 23-Jun-22 10:19 langful/lang.py
--rw-rw-rw-  2.0 fat     1066 b- defN 23-Jun-22 10:20 langful-0.28.dist-info/LICENSE
--rw-rw-rw-  2.0 fat     2650 b- defN 23-Jun-22 10:20 langful-0.28.dist-info/METADATA
--rw-rw-rw-  2.0 fat      110 b- defN 23-Jun-22 10:20 langful-0.28.dist-info/WHEEL
--rw-rw-rw-  2.0 fat        8 b- defN 23-Jun-22 10:20 langful-0.28.dist-info/top_level.txt
--rw-rw-r--  2.0 fat      528 b- defN 23-Jun-22 10:20 langful-0.28.dist-info/RECORD
-7 files, 11519 bytes uncompressed, 3725 bytes compressed:  67.7%
+-rw-rw-rw-  2.0 fat     9134 b- defN 23-Jun-28 10:37 langful/lang.py
+-rw-rw-rw-  2.0 fat     1066 b- defN 23-Jun-28 10:41 langful-0.29.dist-info/LICENSE
+-rw-rw-rw-  2.0 fat     2859 b- defN 23-Jun-28 10:41 langful-0.29.dist-info/METADATA
+-rw-rw-rw-  2.0 fat      110 b- defN 23-Jun-28 10:41 langful-0.29.dist-info/WHEEL
+-rw-rw-rw-  2.0 fat        8 b- defN 23-Jun-28 10:41 langful-0.29.dist-info/top_level.txt
+-rw-rw-r--  2.0 fat      528 b- defN 23-Jun-28 10:41 langful-0.29.dist-info/RECORD
+7 files, 13929 bytes uncompressed, 4188 bytes compressed:  69.9%
```

## zipnote {}

```diff
@@ -1,22 +1,22 @@
 Filename: langful/__init__.py
 Comment: 
 
 Filename: langful/lang.py
 Comment: 
 
-Filename: langful-0.28.dist-info/LICENSE
+Filename: langful-0.29.dist-info/LICENSE
 Comment: 
 
-Filename: langful-0.28.dist-info/METADATA
+Filename: langful-0.29.dist-info/METADATA
 Comment: 
 
-Filename: langful-0.28.dist-info/WHEEL
+Filename: langful-0.29.dist-info/WHEEL
 Comment: 
 
-Filename: langful-0.28.dist-info/top_level.txt
+Filename: langful-0.29.dist-info/top_level.txt
 Comment: 
 
-Filename: langful-0.28.dist-info/RECORD
+Filename: langful-0.29.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## langful/lang.py

```diff
@@ -7,88 +7,97 @@
 
 def lang_to_json( lang_file : str ) -> dict :
     """
     .lang -> .json
     """
     ret = {}
     for i in lang_file.split( "\n" ) :
-        i = i.split("#")[0]
-        i = "".join( i.split( maxsplit = 2 ) )
-        if i :
-            k , v = i.split( "=" , 1 )
-            ret[ k ] = v
+        text = i.split("#")[0]
+        line = "".join( text.split( maxsplit = 2 ) )
+        if line :
+            key_value = i.split( "=" , 1 )
+            if len( key_value ) == 2 :
+                key , value = i.split( "=" , 1 )
+            else :
+                raise SyntaxError( "can't to read .lang file" )
+            ret[ key ] = value
     return ret
 
 def json_to_lang( dict_file : dict ) -> str :
     """
     .json -> .lang
     """
     ret = ""
-    for k , v in dict_file.items() :
-        if not ( isinstance( v , int ) or isinstance( v , str ) ) :
-            raise TypeError( f"can't use type '{ type( v ) }'" )
-        ret += f"{ k } = { v }\n"
+    for key , value in dict_file.items() :
+        if not ( isinstance( value , int ) or isinstance( value , str ) ) :
+            raise TypeError( f"can't use type '{ type( value ) }'" )
+        ret += f"{ key } = { value }\n"
     return ret
 
 class lang :
     """
     # lang
     """
-
     def __init__( self , lang_dir : str  |  bool = "lang" , default_locale : str = "en_us" ) -> None :
         """
         lang_dir: lang files dir, if use dict to set that False
         default_locale: default locale
         """
+        self.lang_dir = lang_dir
         system_locale = self.get_system_locale
         self.default_locale = default_locale
         self.system_locale = system_locale
         self.replace_letter = "%"
-        self.lang_dir = lang_dir
         self.is_file = False
         self.languages = {}
         self.locales = []
         self.types = {}
         self.init()
 
     def init( self ) -> None :
         """
         # init
         """
         path = self.lang_dir
-        if not isinstance( path , str ) :
-            return
-        if not os.path.exists( path ) :
-            raise FileNotFoundError( f"can't find '{ os.path.abspath( path ) }'" )
-        self.is_file = True
-        files = []
-        for i in os.listdir( path ) :
-            name , suffix = os.path.splitext( i )
-            if ( suffix == ".json" ) or ( name + ".json" not in files ) :
-                files.append( i )
-                with open( os.path.join( path , i ) , encoding = "utf-8" ) as file :
-                    if suffix == ".json" :
-                        data = json.load( file )
-                    elif suffix == ".lang" :
-                        data = lang_to_json( file.read() )
-                    else :
-                        continue
-                self.locales.append( name )
-                self.languages[ name ] = data
-                self.types[ name ] = suffix
+        if isinstance( path , str ) :
+            self.is_file = True
+        if self.is_file :
+            if not os.path.exists( path ) :
+                raise FileNotFoundError( f"can't find '{ os.path.abspath( path ) }'" )
+            files = []
+            for i in os.listdir( path ) :
+                name , suffix = os.path.splitext( i )
+                if ( suffix == ".json" ) or ( name + ".json" not in files ) :
+                    files.append( i )
+                    with open( os.path.join( path , i ) , encoding = "utf-8" ) as file :
+                        if suffix == ".json" :
+                            try :
+                                data = json.load( file )
+                            except json.decoder.JSONDecodeError :
+                                raise SyntaxError( "can't to load .json file" )
+                        elif suffix == ".lang" :
+                            data = lang_to_json( file.read() )
+                        else :
+                            continue
+                    self.locales.append( name )
+                    self.languages[ name ] = data
+                    self.types[ name ] = suffix
 
     def init_dict( self , language : dict ) -> None :
         """
         init by a dictionary, but cant't to save
         """
         if self.is_file :
             raise TypeError( "can't init by a dictionary, because it's init by a dir" )
-        for k in language.keys() :
-            self.types[ k ] = ".json"
-            self.locales.append( k )
+        for value in language.values() :
+            if not isinstance( value , dict ) :
+                raise TypeError( f"can't use type '{ type( value ) }'" )
+        for key in language.keys() :
+            self.types[ key ] = ".json"
+            self.locales.append( key )
         self.languages = language
 
     @property
     def get_system_locale( self ) -> str :
         """
         get system locale
         """
@@ -110,51 +119,81 @@
     def language( self ) -> dict :
         """
         get now language
         """
         return self.languages[ self.locale ]
 
     @property
+    def lang( self ) -> dict :
+        """
+        same to language function
+        """
+        return self.language
+
+    @property
     def type( self ) -> str :
         """
         get type, '.json' or '.lang'
         """
         return self.types[ self.locale ]
 
+    def get_locale( self , locale : str = None ) -> str :
+        if locale :
+            return locale
+        else :
+            return self.locale
+
+    def get_replace_letter( self , replace_letter : str = None ) -> str :
+        if replace_letter :
+            return replace_letter
+        else :
+            return self.replace_letter
+
     def set_locale( self , locale : str = None  ) -> None :
         """
         set/reset locale
         """
         if locale != None :
             self.system_locale = locale
         else :
             self.system_locale = self.get_system_locale
 
+    def lang_set( self , locale : str , suffix : str , value : dict = {} ) -> None :
+        """
+        set lang
+        """
+        self.languages[ locale ] = value
+        self.types[ locale ] = suffix
+
+    def lang_del( self , locale : str ) -> None :
+        """
+        del lang
+        """
+        del self.languages[ locale ]
+        del self.types[ locale ]
+
     def get( self , key : str | int , locale : str = None ) -> str :
         """
         get
         """
-        if not locale :
-            locale = self.locale
+        locale = self.get_locale( locale )
         return self.languages[ locale ][ key ]
 
     def set( self , key : str | int , value : str , locale : str = None ) -> None :
         """
         set
         """
-        if not locale :
-            locale = self.locale
+        locale = self.get_locale( locale )
         self.languages[ locale ][ key ] = value
 
     def remove( self , key : str | int , locale : str = None ) -> None :
         """
         remove
         """
-        if not locale :
-            locale = self.locale
+        locale = self.get_locale( locale )
         del self.languages[ locale ][ key ]
 
     def save( self ) -> None :
         """
         save file, when is_file is true
         """
         if self.is_file :
@@ -163,20 +202,47 @@
                 print(suffix,value)
                 with open( os.path.join( self.lang_dir , key + suffix ) , "w+" , encoding = "utf-8" ) as file :
                     if suffix == ".json" :
                         file.write( json.dumps( value , indent = 4 , separators = ( " ," , ": " ) , ensure_ascii = False ) )
                     elif suffix == ".lang" :
                         file.write( json_to_lang( value ) )
         else :
-            raise TypeError( f"can't to save, because it's not a file" )
+            raise TypeError( "can't to save, because it's not a file" )
 
-    def replace( self , key : str = None , args : list = None , locale : str = None , replace_letter : str = None ) -> str :
+    def save_dict( self ) -> dict :
+        """
+        save dict. in fact, it just return the 'languages' variable
+        """
+        if not self.is_file :
+            return self.languages
+        else :
+            raise TypeError( "can't to save, because it's not a dict" )
+
+    def replace( self , key : str = None , args : list | str = None , locale : str = None , replace_letter : str = None ) -> str :
         """
         replace
         """
+        # locale = self.get_locale( locale )
+        # replace_letter = self.get_replace_letter( replace_letter )
+        # text = []
+        # ret = ""
+        # p = 0
+        # for i in self.get( key ).split( replace_letter * 2 ) :
+        #     if i :
+        #         print(i.split( replace_letter ))
+        #         text += i.split( replace_letter )
+        #     else :
+        #         text += replace_letter
+        # print(text)
+        # if not isinstance( args , list ) :
+        #     args = [ str( args ) ]
+        # for i in range ( len( text ) ) :
+        #     print(text[i])
+        #     p += 1
+        # return ret
         if not replace_letter :
             replace_letter = self.replace_letter
         if not locale :
             locale = self.locale
         text = self.get( key , locale ).split( replace_letter )
         if len( text ) == 1 :
             text = text[0]
@@ -189,29 +255,24 @@
                     ret += text[i] + args[-1]
             else :
                 ret += text[i]
         return ret
 
     def replace_str( self , text : str , locale : str = None , replace_letter : str = None ) -> str :
         """
-        replace_str
+        replace by str
         """
-        if not replace_letter :
-            replace_letter = self.replace_letter
-        if not locale :
-            locale = self.locale
-        i = 0
-        ret = ""
+        locale = self.get_locale( locale )
+        replace_letter = self.get_replace_letter( replace_letter )
         text = text.split( replace_letter )
-        language = self.languages[ locale ]
-        for split_text in text :
-            if i % 2 :
-                if split_text in language :
-                    ret += language[split_text]
-                elif not split_text :
-                    ret += replace_letter
+        ret = ""
+        p = 0
+        for i in text :
+            if p % 2 :
+                if i :
+                    ret += self.get( i )
                 else :
-                    raise KeyError( f"key '{split_text}' has not find!" )
+                    ret += replace_letter
             else :
-                ret += split_text
-            i += 1
+                ret += i
+            p += 1
         return ret
```

## Comparing `langful-0.28.dist-info/LICENSE` & `langful-0.29.dist-info/LICENSE`

 * *Files identical despite different names*

## Comparing `langful-0.28.dist-info/METADATA` & `langful-0.29.dist-info/METADATA`

 * *Files 18% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 00000000: 4d65 7461 6461 7461 2d56 6572 7369 6f6e  Metadata-Version
 00000010: 3a20 322e 310d 0a4e 616d 653a 206c 616e  : 2.1..Name: lan
 00000020: 6766 756c 0d0a 5665 7273 696f 6e3a 2030  gful..Version: 0
-00000030: 2e32 380d 0a48 6f6d 652d 7061 6765 3a20  .28..Home-page: 
+00000030: 2e32 390d 0a48 6f6d 652d 7061 6765 3a20  .29..Home-page: 
 00000040: 6874 7470 733a 2f2f 6769 7468 7562 2e63  https://github.c
 00000050: 6f6d 2f63 7565 6176 7971 7770 2f6c 616e  om/cueavyqwp/lan
 00000060: 6766 756c 0d0a 4175 7468 6f72 3a20 6375  gful..Author: cu
 00000070: 6561 7679 7177 700d 0a41 7574 686f 722d  eavyqwp..Author-
 00000080: 656d 6169 6c3a 2063 7565 6176 7971 7770  email: cueavyqwp
 00000090: 406f 7574 6c6f 6f6b 2e63 6f6d 0d0a 436c  @outlook.com..Cl
 000000a0: 6173 7369 6669 6572 3a20 5072 6f67 7261  assifier: Progra
@@ -18,149 +18,162 @@
 00000110: 7065 7261 7469 6e67 2053 7973 7465 6d20  perating System 
 00000120: 3a3a 204f 5320 496e 6465 7065 6e64 656e  :: OS Independen
 00000130: 740d 0a52 6571 7569 7265 732d 5079 7468  t..Requires-Pyth
 00000140: 6f6e 3a20 3e20 332e 360d 0a44 6573 6372  on: > 3.6..Descr
 00000150: 6970 7469 6f6e 2d43 6f6e 7465 6e74 2d54  iption-Content-T
 00000160: 7970 653a 2074 6578 742f 6d61 726b 646f  ype: text/markdo
 00000170: 776e 0d0a 4c69 6365 6e73 652d 4669 6c65  wn..License-File
-00000180: 3a20 4c49 4345 4e53 450d 0a0d 0a23 206c  : LICENSE....# l
-00000190: 616e 6766 756c 0d0a 0d0a 3c70 2061 6c69  angful....<p ali
-000001a0: 676e 3d22 6365 6e74 6572 223e 0d0a 2020  gn="center">..  
-000001b0: 2020 3c61 2068 7265 663d 2268 7474 7073    <a href="https
-000001c0: 3a2f 2f70 7970 692e 6f72 672f 7072 6f6a  ://pypi.org/proj
-000001d0: 6563 742f 6c61 6e67 6675 6c22 3e0d 0a20  ect/langful">.. 
-000001e0: 2020 2020 2020 203c 696d 6720 616c 743d         <img alt=
-000001f0: 2250 7950 4920 7665 7273 696f 6e22 2073  "PyPI version" s
-00000200: 7263 3d22 6874 7470 733a 2f2f 696d 672e  rc="https://img.
-00000210: 7368 6965 6c64 732e 696f 2f70 7970 692f  shields.io/pypi/
-00000220: 762f 6c61 6e67 6675 6c3f 636f 6c6f 723d  v/langful?color=
-00000230: 626c 7565 223e 0d0a 2020 2020 3c2f 613e  blue">..    </a>
-00000240: 0d0a 2020 2020 3c61 2068 7265 663d 2268  ..    <a href="h
-00000250: 7474 7073 3a2f 2f77 7777 2e70 7974 686f  ttps://www.pytho
-00000260: 6e2e 6f72 6722 3e0d 0a20 2020 2020 2020  n.org">..       
-00000270: 203c 696d 6720 616c 743d 2250 7974 686f   <img alt="Pytho
-00000280: 6e20 7665 7273 696f 6e22 2073 7263 3d22  n version" src="
-00000290: 6874 7470 733a 2f2f 696d 672e 7368 6965  https://img.shie
-000002a0: 6c64 732e 696f 2f62 6164 6765 2f70 7974  lds.io/badge/pyt
-000002b0: 686f 6e2d 332e 362b 2d62 6c75 6522 3e0d  hon-3.6+-blue">.
-000002c0: 0a20 2020 203c 2f61 3e0d 0a20 2020 203c  .    </a>..    <
-000002d0: 6120 6872 6566 3d22 6874 7470 733a 2f2f  a href="https://
-000002e0: 6f70 656e 736f 7572 6365 2e6f 7267 2f6c  opensource.org/l
-000002f0: 6963 656e 7365 2f6d 6974 2f22 3e0d 0a20  icense/mit/">.. 
-00000300: 2020 2020 2020 203c 696d 6720 616c 743d         <img alt=
-00000310: 226c 6963 656e 7365 2220 7372 633d 2268  "license" src="h
-00000320: 7474 7073 3a2f 2f69 6d67 2e73 6869 656c  ttps://img.shiel
-00000330: 6473 2e69 6f2f 6261 6467 652f 6c69 6365  ds.io/badge/lice
-00000340: 6e73 652d 4d49 542d 626c 7565 223e 0d0a  nse-MIT-blue">..
-00000350: 2020 2020 3c2f 613e 0d0a 2020 2020 3c61      </a>..    <a
-00000360: 2068 7265 663d 2268 7474 7073 3a2f 2f67   href="https://g
-00000370: 6974 6875 622e 636f 6d2f 6375 6561 7679  ithub.com/cueavy
-00000380: 7177 702f 6c61 6e67 6675 6c22 3e0d 0a20  qwp/langful">.. 
-00000390: 2020 2020 2020 203c 696d 6720 616c 743d         <img alt=
-000003a0: 2247 6974 6875 6220 7374 6172 7322 2073  "Github stars" s
-000003b0: 7263 3d22 6874 7470 733a 2f2f 696d 672e  rc="https://img.
-000003c0: 7368 6965 6c64 732e 696f 2f67 6974 6875  shields.io/githu
-000003d0: 622f 7374 6172 732f 6375 6561 7679 7177  b/stars/cueavyqw
-000003e0: 702f 6c61 6e67 6675 6c3f 636f 6c6f 723d  p/langful?color=
-000003f0: 626c 7565 223e 0d0a 2020 2020 3c2f 613e  blue">..    </a>
-00000400: 0d0a 2020 2020 3c61 2068 7265 663d 2268  ..    <a href="h
-00000410: 7474 7073 3a2f 2f67 6974 6875 622e 636f  ttps://github.co
-00000420: 6d2f 6375 6561 7679 7177 702f 6c61 6e67  m/cueavyqwp/lang
-00000430: 6675 6c22 3e0d 0a20 2020 2020 2020 203c  ful">..        <
-00000440: 696d 6720 616c 743d 2247 6974 6875 6220  img alt="Github 
-00000450: 6973 7375 6573 2220 7372 633d 2268 7474  issues" src="htt
-00000460: 7073 3a2f 2f69 6d67 2e73 6869 656c 6473  ps://img.shields
-00000470: 2e69 6f2f 6769 7468 7562 2f69 7373 7565  .io/github/issue
-00000480: 732f 6375 6561 7679 7177 702f 6c61 6e67  s/cueavyqwp/lang
-00000490: 6675 6c3f 636f 6c6f 723d 626c 7565 223e  ful?color=blue">
-000004a0: 0d0a 2020 2020 3c2f 613e 0d0a 3c2f 703e  ..    </a>..</p>
-000004b0: 0d0a 0d0a 2320 696e 7374 616c 6c0d 0a0d  ....# install...
-000004c0: 0a55 7365 2060 7069 7060 2074 6f20 696e  .Use `pip` to in
-000004d0: 7374 616c 6c20 6070 6970 2069 6e73 7461  stall `pip insta
-000004e0: 6c6c 206c 616e 6766 756c 6020 6f72 2060  ll langful` or `
-000004f0: 7069 7033 2069 6e73 7461 6c6c 206c 616e  pip3 install lan
-00000500: 6766 756c 600d 0a0d 0a23 2065 7861 6d70  gful`....# examp
-00000510: 6c65 2874 6f6f 206f 6c64 290d 0a0d 0a2d  le(too old)....-
-00000520: 2074 6573 742e 7079 0d0a 2d20 6c61 6e67   test.py..- lang
-00000530: 0d0a 2020 2020 2d20 7a68 5f63 6e2e 6a73  ..    - zh_cn.js
-00000540: 6f6e 0d0a 2020 2020 2d20 656e 5f75 732e  on..    - en_us.
-00000550: 6a73 6f6e 0d0a 0d0a 2323 207a 685f 636e  json....## zh_cn
-00000560: 2e6a 736f 6e0d 0a0d 0a60 6060 6a73 6f6e  .json....```json
-00000570: 0d0a 7b0d 0a20 2020 2022 6869 2220 3a20  ..{..    "hi" : 
-00000580: 22e4 bda0 e5a5 bd22 202c 0d0a 2020 2020  "......" ,..    
-00000590: 2277 656c 636f 6d65 2220 3a20 22e6 aca2  "welcome" : "...
-000005a0: e8bf 8e22 0d0a 7d0d 0a60 6060 0d0a 0d0a  ..."..}..```....
-000005b0: 2323 2065 6e5f 7573 2e6a 736f 6e0d 0a0d  ## en_us.json...
-000005c0: 0a60 6060 6a73 6f6e 0d0a 7b0d 0a20 2020  .```json..{..   
-000005d0: 2022 6869 2220 3a20 2248 6922 202c 0d0a   "hi" : "Hi" ,..
-000005e0: 2020 2020 2277 656c 636f 6d65 2220 3a20      "welcome" : 
-000005f0: 2257 656c 636f 6d65 220d 0a7d 0d0a 6060  "Welcome"..}..``
-00000600: 600d 0a0d 0a23 2320 7473 6574 2e70 790d  `....## tset.py.
-00000610: 0a0d 0a60 6060 7079 7468 6f6e 0d0a 696d  ...```python..im
-00000620: 706f 7274 206c 616e 6766 756c 0d0a 0d0a  port langful....
-00000630: 5465 7874 203d 206c 616e 6766 756c 2e6c  Text = langful.l
-00000640: 616e 6728 290d 0a0d 0a70 7269 6e74 2820  ang()....print( 
-00000650: 5465 7874 2e6c 616e 6775 6167 655f 6469  Text.language_di
-00000660: 6374 2029 0d0a 0d0a 7072 696e 7428 2054  ct )....print( T
-00000670: 6578 742e 7374 725f 7265 706c 6163 6528  ext.str_replace(
-00000680: 2022 2568 6925 2220 2c20 6c61 6e67 5f73   "%hi%" , lang_s
-00000690: 7472 203d 2022 7a68 5f63 6e22 2029 2029  tr = "zh_cn" ) )
-000006a0: 0d0a 0d0a 7072 696e 7428 2054 6578 742e  ....print( Text.
-000006b0: 7374 725f 7265 706c 6163 6528 2022 2168  str_replace( "!h
-000006c0: 6921 2220 2c20 6c61 6e67 5f73 7472 203d  i!" , lang_str =
-000006d0: 2022 7a68 5f63 6e22 202c 2063 6861 6e67   "zh_cn" , chang
-000006e0: 6520 3d20 2221 2220 2920 290d 0a0d 0a70  e = "!" ) )....p
-000006f0: 7269 6e74 2820 5465 7874 2e73 7472 5f72  rint( Text.str_r
-00000700: 6570 6c61 6365 2820 2225 7765 6c63 6f6d  eplace( "%welcom
-00000710: 6525 2220 2c20 6c61 6e67 5f73 7472 203d  e%" , lang_str =
-00000720: 2022 7a68 5f63 6e22 2029 2029 0d0a 0d0a   "zh_cn" ) )....
-00000730: 7072 696e 7428 2054 6578 742e 7374 725f  print( Text.str_
-00000740: 7265 706c 6163 6528 2022 2177 656c 636f  replace( "!welco
-00000750: 6d65 2122 202c 206c 616e 675f 7374 7220  me!" , lang_str 
-00000760: 3d20 227a 685f 636e 2220 2c20 6368 616e  = "zh_cn" , chan
-00000770: 6765 203d 2022 2122 2029 2029 0d0a 0d0a  ge = "!" ) )....
-00000780: 7072 696e 7428 2054 6578 742e 7374 725f  print( Text.str_
-00000790: 7265 706c 6163 6528 2022 2568 6925 2220  replace( "%hi%" 
-000007a0: 2c20 6c61 6e67 5f73 7472 203d 2022 656e  , lang_str = "en
-000007b0: 5f75 7322 2029 2029 0d0a 0d0a 7072 696e  _us" ) )....prin
-000007c0: 7428 2054 6578 742e 7374 725f 7265 706c  t( Text.str_repl
-000007d0: 6163 6528 2022 2168 6921 2220 2c20 6c61  ace( "!hi!" , la
-000007e0: 6e67 5f73 7472 203d 2022 656e 5f75 7322  ng_str = "en_us"
-000007f0: 202c 2063 6861 6e67 6520 3d20 2221 2220   , change = "!" 
-00000800: 2920 290d 0a0d 0a70 7269 6e74 2820 5465  ) )....print( Te
-00000810: 7874 2e73 7472 5f72 6570 6c61 6365 2820  xt.str_replace( 
-00000820: 2225 7765 6c63 6f6d 6525 2220 2c20 6c61  "%welcome%" , la
-00000830: 6e67 5f73 7472 203d 2022 656e 5f75 7322  ng_str = "en_us"
-00000840: 2029 2029 0d0a 0d0a 7072 696e 7428 2054   ) )....print( T
-00000850: 6578 742e 7374 725f 7265 706c 6163 6528  ext.str_replace(
-00000860: 2022 2177 656c 636f 6d65 2122 202c 206c   "!welcome!" , l
-00000870: 616e 675f 7374 7220 3d20 2265 6e5f 7573  ang_str = "en_us
-00000880: 2220 2c20 6368 616e 6765 203d 2022 2122  " , change = "!"
-00000890: 2029 2029 0d0a 0d0a 7072 696e 7428 2029   ) )....print( )
-000008a0: 0d0a 0d0a 7072 696e 7428 2054 6578 742e  ....print( Text.
-000008b0: 7374 725f 7265 706c 6163 6528 2022 2525  str_replace( "%%
-000008c0: 2220 2920 290d 0a70 7269 6e74 2820 5465  " ) )..print( Te
-000008d0: 7874 2e73 7472 5f72 6570 6c61 6365 2820  xt.str_replace( 
-000008e0: 2221 2122 202c 2063 6861 6e67 6520 3d20  "!!" , change = 
-000008f0: 2221 2220 2920 290d 0a60 6060 0d0a 0d0a  "!" ) )..```....
-00000900: 2323 204f 7574 7075 740d 0a0d 0a60 6060  ## Output....```
-00000910: 7079 7468 6f6e 0d0a 7b27 656e 5f75 7327  python..{'en_us'
-00000920: 3a20 7b27 7765 6c63 6f6d 6527 3a20 2757  : {'welcome': 'W
-00000930: 656c 636f 6d65 272c 2027 6869 273a 2027  elcome', 'hi': '
-00000940: 4869 277d 2c20 277a 685f 636e 273a 207b  Hi'}, 'zh_cn': {
-00000950: 2777 656c 636f 6d65 273a 2027 e6ac a2e8  'welcome': '....
-00000960: bf8e 272c 2027 6869 273a 2027 e4bd a0e5  ..', 'hi': '....
-00000970: a5bd 277d 7d0d 0ae4 bda0 e5a5 bd0d 0ae4  ..'}}...........
-00000980: bda0 e5a5 bd0d 0ae6 aca2 e8bf 8e0d 0ae6  ................
-00000990: aca2 e8bf 8e0d 0a48 690d 0a48 690d 0a57  .......Hi..Hi..W
-000009a0: 656c 636f 6d65 0d0a 5765 6c63 6f6d 650d  elcome..Welcome.
-000009b0: 0a0d 0a25 0d0a 210d 0a60 6060 0d0a 0d0a  ...%..!..```....
-000009c0: 2320 4162 6f75 740d 0a0d 0a67 6974 6875  # About....githu
-000009d0: 623a 2068 7474 7073 3a2f 2f67 6974 6875  b: https://githu
-000009e0: 622e 636f 6d2f 6375 6561 7679 7177 702f  b.com/cueavyqwp/
-000009f0: 6c61 6e67 6675 6c0d 0a0d 0a70 7970 693a  langful....pypi:
-00000a00: 2068 7474 7073 3a2f 2f70 7970 692e 6f72   https://pypi.or
-00000a10: 672f 7072 6f6a 6563 742f 6c61 6e67 6675  g/project/langfu
-00000a20: 6c0d 0a0d 0a69 7373 7565 733a 2068 7474  l....issues: htt
-00000a30: 7073 3a2f 2f67 6974 6875 622e 636f 6d2f  ps://github.com/
-00000a40: 6375 6561 7679 7177 702f 6c61 6e67 6675  cueavyqwp/langfu
-00000a50: 6c2f 6973 7375 6573 0d0a                 l/issues..
+00000180: 3a20 4c49 4345 4e53 450d 0a0d 0a3c 6469  : LICENSE....<di
+00000190: 7620 616c 6967 6e3d 2263 656e 7465 7222  v align="center"
+000001a0: 3e0d 0a20 2020 203c 6831 3e6c 616e 6766  >..    <h1>langf
+000001b0: 756c 3c2f 6831 3e0d 0a20 2020 203c 6120  ul</h1>..    <a 
+000001c0: 6872 6566 203d 2022 6874 7470 733a 2f2f  href = "https://
+000001d0: 7079 7069 2e6f 7267 2f70 726f 6a65 6374  pypi.org/project
+000001e0: 2f6c 616e 6766 756c 2220 3e0d 0a20 2020  /langful" >..   
+000001f0: 2020 2020 203c 696d 6720 616c 7420 3d20       <img alt = 
+00000200: 2250 7950 4920 7665 7273 696f 6e22 2073  "PyPI version" s
+00000210: 7263 203d 2022 6874 7470 733a 2f2f 696d  rc = "https://im
+00000220: 672e 7368 6965 6c64 732e 696f 2f70 7970  g.shields.io/pyp
+00000230: 692f 762f 6c61 6e67 6675 6c3f 636f 6c6f  i/v/langful?colo
+00000240: 723d 626c 7565 2220 3e0d 0a20 2020 203c  r=blue" >..    <
+00000250: 2f61 3e0d 0a20 2020 203c 6120 6872 6566  /a>..    <a href
+00000260: 203d 2022 6874 7470 733a 2f2f 7777 772e   = "https://www.
+00000270: 7079 7468 6f6e 2e6f 7267 2220 3e0d 0a20  python.org" >.. 
+00000280: 2020 2020 2020 203c 696d 6720 616c 7420         <img alt 
+00000290: 3d20 2250 7974 686f 6e20 7665 7273 696f  = "Python versio
+000002a0: 6e22 2073 7263 203d 2022 6874 7470 733a  n" src = "https:
+000002b0: 2f2f 696d 672e 7368 6965 6c64 732e 696f  //img.shields.io
+000002c0: 2f62 6164 6765 2f70 7974 686f 6e2d 332e  /badge/python-3.
+000002d0: 362b 2d62 6c75 6522 203e 0d0a 2020 2020  6+-blue" >..    
+000002e0: 3c2f 613e 0d0a 2020 2020 3c61 2068 7265  </a>..    <a hre
+000002f0: 6620 3d20 2268 7474 7073 3a2f 2f6f 7065  f = "https://ope
+00000300: 6e73 6f75 7263 652e 6f72 672f 6c69 6365  nsource.org/lice
+00000310: 6e73 652f 6d69 7422 203e 0d0a 2020 2020  nse/mit" >..    
+00000320: 2020 2020 3c69 6d67 2061 6c74 203d 2022      <img alt = "
+00000330: 6c69 6365 6e73 6522 2073 7263 203d 2022  license" src = "
+00000340: 6874 7470 733a 2f2f 696d 672e 7368 6965  https://img.shie
+00000350: 6c64 732e 696f 2f62 6164 6765 2f6c 6963  lds.io/badge/lic
+00000360: 656e 7365 2d4d 4954 2d62 6c75 6522 203e  ense-MIT-blue" >
+00000370: 0d0a 2020 2020 3c2f 613e 0d0a 2020 2020  ..    </a>..    
+00000380: 3c61 2068 7265 6620 3d20 2268 7474 7073  <a href = "https
+00000390: 3a2f 2f67 6974 6875 622e 636f 6d2f 6375  ://github.com/cu
+000003a0: 6561 7679 7177 702f 6c61 6e67 6675 6c22  eavyqwp/langful"
+000003b0: 203e 0d0a 2020 2020 2020 2020 3c69 6d67   >..        <img
+000003c0: 2061 6c74 203d 2022 4769 7468 7562 2073   alt = "Github s
+000003d0: 7461 7273 2220 7372 6320 3d20 2268 7474  tars" src = "htt
+000003e0: 7073 3a2f 2f69 6d67 2e73 6869 656c 6473  ps://img.shields
+000003f0: 2e69 6f2f 6769 7468 7562 2f73 7461 7273  .io/github/stars
+00000400: 2f63 7565 6176 7971 7770 2f6c 616e 6766  /cueavyqwp/langf
+00000410: 756c 3f63 6f6c 6f72 3d62 6c75 6522 203e  ul?color=blue" >
+00000420: 0d0a 2020 2020 3c2f 613e 0d0a 2020 2020  ..    </a>..    
+00000430: 3c61 2068 7265 6620 3d20 2268 7474 7073  <a href = "https
+00000440: 3a2f 2f67 6974 6875 622e 636f 6d2f 6375  ://github.com/cu
+00000450: 6561 7679 7177 702f 6c61 6e67 6675 6c22  eavyqwp/langful"
+00000460: 203e 0d0a 2020 2020 2020 2020 3c69 6d67   >..        <img
+00000470: 2061 6c74 203d 2022 4769 7468 7562 2069   alt = "Github i
+00000480: 7373 7565 7322 2073 7263 203d 2022 6874  ssues" src = "ht
+00000490: 7470 733a 2f2f 696d 672e 7368 6965 6c64  tps://img.shield
+000004a0: 732e 696f 2f67 6974 6875 622f 6973 7375  s.io/github/issu
+000004b0: 6573 2f63 7565 6176 7971 7770 2f6c 616e  es/cueavyqwp/lan
+000004c0: 6766 756c 3f63 6f6c 6f72 3d62 6c75 6522  gful?color=blue"
+000004d0: 203e 0d0a 2020 2020 3c2f 613e 0d0a 3c2f   >..    </a>..</
+000004e0: 6469 763e 0d0a 0d0a 2320 696e 7374 616c  div>....# instal
+000004f0: 6c0d 0a0d 0a60 7069 7033 2069 6e73 7461  l....`pip3 insta
+00000500: 6c6c 206c 616e 6766 756c 6020 6f72 2060  ll langful` or `
+00000510: 7069 7020 696e 7374 616c 6c20 6c61 6e67  pip install lang
+00000520: 6675 6c60 0d0a 0d0a 2320 7673 636f 6465  ful`....# vscode
+00000530: 2d6c 616e 6766 756c 0d0a 0d0a 5b47 6974  -langful....[Git
+00000540: 4875 625d 2868 7474 7073 3a2f 2f67 6974  Hub](https://git
+00000550: 6875 622e 636f 6d2f 6375 6561 7679 2f76  hub.com/cueavy/v
+00000560: 7363 6f64 652d 6c61 6e67 6675 6c29 0d0a  scode-langful)..
+00000570: 0d0a 5b56 5343 6f64 655d 2868 7474 7073  ..[VSCode](https
+00000580: 3a2f 2f6d 6172 6b65 7470 6c61 6365 2e76  ://marketplace.v
+00000590: 6973 7561 6c73 7475 6469 6f2e 636f 6d2f  isualstudio.com/
+000005a0: 6974 656d 733f 6974 656d 4e61 6d65 3d63  items?itemName=c
+000005b0: 7565 6176 7971 7770 2e6c 616e 6766 756c  ueavyqwp.langful
+000005c0: 290d 0a0d 0a23 2067 6574 2073 7461 7274  )....# get start
+000005d0: 0d0a 0d0a 2323 206c 616e 6720 6669 6c65  ....## lang file
+000005e0: 0d0a 0d0a 3e20 7073 3a20 606c 616e 6766  ....> ps: `langf
+000005f0: 756c 6020 6c6f 6164 206a 736f 6e20 6669  ul` load json fi
+00000600: 6c65 2066 6972 7374 0d0a 0d0a 2323 2320  le first....### 
+00000610: 2e6a 736f 6e0d 0a0d 0a60 6060 6a73 6f6e  .json....```json
+00000620: 0d0a 7b0d 0a20 2020 2022 6b65 7922 3a20  ..{..    "key": 
+00000630: 2276 616c 7565 2220 2c0d 0a20 2020 2022  "value" ,..    "
+00000640: 2e2e 2e22 203a 2022 2e2e 2e22 0d0a 7d0d  ..." : "..."..}.
+00000650: 0a60 6060 0d0a 0d0a 2323 2320 2e6c 616e  .```....### .lan
+00000660: 670d 0a0d 0a60 6060 0d0a 6b65 7920 3d20  g....```..key = 
+00000670: 7661 6c75 6520 2320 6869 2c20 7468 6973  value # hi, this
+00000680: 2069 7320 6120 6578 616d 706c 650d 0a23   is a example..#
+00000690: 2068 692c 2049 2061 6d20 6120 6578 616d   hi, I am a exam
+000006a0: 706c 652c 2074 6f6f 0d0a 2e2e 2e20 3d20  ple, too..... = 
+000006b0: 2e2e 2e0d 0a60 6060 0d0a 0d0a 2323 2069  .....```....## i
+000006c0: 6e69 740d 0a0d 0a74 6865 7265 2068 6176  nit....there hav
+000006d0: 6520 6074 776f 6020 7761 7973 2074 6f20  e `two` ways to 
+000006e0: 696e 6974 0d0a 0d0a 3e20 6279 2066 696c  init....> by fil
+000006f0: 6573 0d0a 0d0a 6060 6070 7974 686f 6e0d  es....```python.
+00000700: 0a69 6d70 6f72 7420 6c61 6e67 6675 6c0d  .import langful.
+00000710: 0a6c 616e 6720 3d20 6c61 6e67 6675 6c2e  .lang = langful.
+00000720: 6c61 6e67 2829 0d0a 6060 600d 0a0d 0a3e  lang()..```....>
+00000730: 2062 7920 6469 6374 696f 6e61 7279 0d0a   by dictionary..
+00000740: 0d0a 6060 6070 7974 686f 6e0d 0a69 6d70  ..```python..imp
+00000750: 6f72 7420 6c61 6e67 6675 6c0d 0a6c 616e  ort langful..lan
+00000760: 6720 3d20 6c61 6e67 6675 6c2e 6c61 6e67  g = langful.lang
+00000770: 2820 4661 6c73 6520 290d 0a6c 616e 672e  ( False )..lang.
+00000780: 696e 6974 5f64 6963 7428 207b 0d0a 2020  init_dict( {..  
+00000790: 2020 2265 6e5f 7573 2220 3a20 7b0d 0a20    "en_us" : {.. 
+000007a0: 2020 2020 2020 2022 6869 2220 3a20 2248         "hi" : "H
+000007b0: 6922 202c 0d0a 2020 2020 2020 2020 2277  i" ,..        "w
+000007c0: 656c 636f 6d65 2220 3a20 2257 656c 636f  elcome" : "Welco
+000007d0: 6d65 220d 0a20 2020 207d 202c 0d0a 2020  me"..    } ,..  
+000007e0: 2020 227a 685f 636e 2220 3a20 7b0d 0a20    "zh_cn" : {.. 
+000007f0: 2020 2020 2020 2022 6869 2220 3a20 22e4         "hi" : ".
+00000800: bda0 e5a5 bd22 202c 0d0a 2020 2020 2020  ....." ,..      
+00000810: 2020 2277 656c 636f 6d65 2220 3a20 22e6    "welcome" : ".
+00000820: aca2 e8bf 8e22 0d0a 2020 2020 7d0d 0a7d  ....."..    }..}
+00000830: 2029 0d0a 6060 600d 0a0d 0a23 2320 7265   )..```....## re
+00000840: 706c 6163 650d 0a0d 0a68 6176 6520 6275  place....have bu
+00000850: 670d 0a0d 0a3c 212d 2d20 6060 6070 7974  g....<!-- ```pyt
+00000860: 686f 6e0d 0a69 6d70 6f72 7420 6c61 6e67  hon..import lang
+00000870: 6675 6c0d 0a6c 616e 6720 3d20 6c61 6e67  ful..lang = lang
+00000880: 6675 6c2e 6c61 6e67 2820 4661 6c73 6520  ful.lang( False 
+00000890: 290d 0a6c 616e 672e 696e 6974 5f64 6963  )..lang.init_dic
+000008a0: 7428 207b 0d0a 2020 2020 2265 6e5f 7573  t( {..    "en_us
+000008b0: 2220 3a20 7b0d 0a20 2020 2020 2020 2022  " : {..        "
+000008c0: 6869 2220 3a20 2248 6922 202c 0d0a 2020  hi" : "Hi" ,..  
+000008d0: 2020 2020 2020 2277 656c 636f 6d65 2220        "welcome" 
+000008e0: 3a20 2257 656c 636f 6d65 220d 0a20 2020  : "Welcome"..   
+000008f0: 207d 202c 0d0a 2020 2020 227a 685f 636e   } ,..    "zh_cn
+00000900: 2220 3a20 7b0d 0a20 2020 2020 2020 2022  " : {..        "
+00000910: 6869 2220 3a20 22e4 bda0 e5a5 bd22 202c  hi" : "......" ,
+00000920: 0d0a 2020 2020 2020 2020 2277 656c 636f  ..        "welco
+00000930: 6d65 2220 3a20 22e6 aca2 e8bf 8e22 0d0a  me" : "......"..
+00000940: 2020 2020 7d0d 0a7d 2029 0d0a 6060 6020      }..} )..``` 
+00000950: 2d2d 3e0d 0a0d 0a23 2320 7265 706c 6163  -->....## replac
+00000960: 6520 7374 720d 0a0d 0a60 6060 7079 7468  e str....```pyth
+00000970: 6f6e 0d0a 696d 706f 7274 206c 616e 6766  on..import langf
+00000980: 756c 0d0a 6c61 6e67 203d 206c 616e 6766  ul..lang = langf
+00000990: 756c 2e6c 616e 6728 2046 616c 7365 2029  ul.lang( False )
+000009a0: 0d0a 6c61 6e67 2e69 6e69 745f 6469 6374  ..lang.init_dict
+000009b0: 2820 7b0d 0a20 2020 2022 656e 5f75 7322  ( {..    "en_us"
+000009c0: 203a 207b 0d0a 2020 2020 2020 2020 2268   : {..        "h
+000009d0: 6922 203a 2022 4869 2220 2c0d 0a20 2020  i" : "Hi" ,..   
+000009e0: 2020 2020 2022 7765 6c63 6f6d 6522 203a       "welcome" :
+000009f0: 2022 5765 6c63 6f6d 6522 0d0a 2020 2020   "Welcome"..    
+00000a00: 7d20 2c0d 0a20 2020 2022 7a68 5f63 6e22  } ,..    "zh_cn"
+00000a10: 203a 207b 0d0a 2020 2020 2020 2020 2268   : {..        "h
+00000a20: 6922 203a 2022 e4bd a0e5 a5bd 2220 2c0d  i" : "......" ,.
+00000a30: 0a20 2020 2020 2020 2022 7765 6c63 6f6d  .        "welcom
+00000a40: 6522 203a 2022 e6ac a2e8 bf8e 220d 0a20  e" : "......".. 
+00000a50: 2020 207d 0d0a 7d20 290d 0a70 7269 6e74     }..} )..print
+00000a60: 286c 616e 672e 7265 706c 6163 655f 7374  (lang.replace_st
+00000a70: 7228 2022 2568 6925 2c20 2577 656c 636f  r( "%hi%, %welco
+00000a80: 6d65 2521 2220 2929 0d0a 6060 600d 0a0d  me%!" ))..```...
+00000a90: 0a23 2041 626f 7574 0d0a 0d0a 6769 7468  .# About....gith
+00000aa0: 7562 3a20 6874 7470 733a 2f2f 6769 7468  ub: https://gith
+00000ab0: 7562 2e63 6f6d 2f63 7565 6176 7971 7770  ub.com/cueavyqwp
+00000ac0: 2f6c 616e 6766 756c 0d0a 0d0a 7079 7069  /langful....pypi
+00000ad0: 3a20 6874 7470 733a 2f2f 7079 7069 2e6f  : https://pypi.o
+00000ae0: 7267 2f70 726f 6a65 6374 2f6c 616e 6766  rg/project/langf
+00000af0: 756c 0d0a 0d0a 6973 7375 6573 3a20 6874  ul....issues: ht
+00000b00: 7470 733a 2f2f 6769 7468 7562 2e63 6f6d  tps://github.com
+00000b10: 2f63 7565 6176 7971 7770 2f6c 616e 6766  /cueavyqwp/langf
+00000b20: 756c 2f69 7373 7565 730d 0a              ul/issues..
```

