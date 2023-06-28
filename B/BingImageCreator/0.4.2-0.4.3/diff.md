# Comparing `tmp/BingImageCreator-0.4.2.tar.gz` & `tmp/BingImageCreator-0.4.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "BingImageCreator-0.4.2.tar", last modified: Fri Jun  9 09:46:30 2023, max compression
+gzip compressed data, was "BingImageCreator-0.4.3.tar", last modified: Wed Jun 28 06:09:42 2023, max compression
```

## Comparing `BingImageCreator-0.4.2.tar` & `BingImageCreator-0.4.3.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-09 09:46:30.273857 BingImageCreator-0.4.2/
--rw-r--r--   0 runner    (1001) docker     (123)     1211 2023-06-09 09:46:09.000000 BingImageCreator-0.4.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1981 2023-06-09 09:46:30.273857 BingImageCreator-0.4.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     1142 2023-06-09 09:46:09.000000 BingImageCreator-0.4.2/README.md
--rw-r--r--   0 runner    (1001) docker     (123)      103 2023-06-09 09:46:30.273857 BingImageCreator-0.4.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1215 2023-06-09 09:46:09.000000 BingImageCreator-0.4.2/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-09 09:46:30.273857 BingImageCreator-0.4.2/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-09 09:46:30.273857 BingImageCreator-0.4.2/src/BingImageCreator.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1981 2023-06-09 09:46:30.000000 BingImageCreator-0.4.2/src/BingImageCreator.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      300 2023-06-09 09:46:30.000000 BingImageCreator-0.4.2/src/BingImageCreator.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-09 09:46:30.000000 BingImageCreator-0.4.2/src/BingImageCreator.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-09 09:46:30.000000 BingImageCreator-0.4.2/src/BingImageCreator.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-09 09:46:30.000000 BingImageCreator-0.4.2/src/BingImageCreator.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)    16460 2023-06-09 09:46:09.000000 BingImageCreator-0.4.2/src/BingImageCreator.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-09 09:46:30.273857 BingImageCreator-0.4.2/test/
--rw-r--r--   0 runner    (1001) docker     (123)      752 2023-06-09 09:46:09.000000 BingImageCreator-0.4.2/test/test_example.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:09:42.813960 BingImageCreator-0.4.3/
+-rw-r--r--   0 runner    (1001) docker     (123)     1211 2023-06-28 06:09:21.000000 BingImageCreator-0.4.3/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1981 2023-06-28 06:09:42.813960 BingImageCreator-0.4.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     1142 2023-06-28 06:09:21.000000 BingImageCreator-0.4.3/README.md
+-rw-r--r--   0 runner    (1001) docker     (123)      103 2023-06-28 06:09:42.813960 BingImageCreator-0.4.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1215 2023-06-28 06:09:21.000000 BingImageCreator-0.4.3/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:09:42.813960 BingImageCreator-0.4.3/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:09:42.813960 BingImageCreator-0.4.3/src/BingImageCreator.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1981 2023-06-28 06:09:42.000000 BingImageCreator-0.4.3/src/BingImageCreator.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      300 2023-06-28 06:09:42.000000 BingImageCreator-0.4.3/src/BingImageCreator.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 06:09:42.000000 BingImageCreator-0.4.3/src/BingImageCreator.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       21 2023-06-28 06:09:42.000000 BingImageCreator-0.4.3/src/BingImageCreator.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       17 2023-06-28 06:09:42.000000 BingImageCreator-0.4.3/src/BingImageCreator.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)    16787 2023-06-28 06:09:21.000000 BingImageCreator-0.4.3/src/BingImageCreator.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:09:42.813960 BingImageCreator-0.4.3/test/
+-rw-r--r--   0 runner    (1001) docker     (123)      752 2023-06-28 06:09:21.000000 BingImageCreator-0.4.3/test/test_example.py
```

### Comparing `BingImageCreator-0.4.2/LICENSE` & `BingImageCreator-0.4.3/LICENSE`

 * *Files identical despite different names*

### Comparing `BingImageCreator-0.4.2/PKG-INFO` & `BingImageCreator-0.4.3/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: BingImageCreator
-Version: 0.4.2
+Version: 0.4.3
 Summary: High quality image generation by Microsoft. Reverse engineered API.
 Home-page: https://github.com/acheong08/BingImageCreator
 Author: Antonio Cheong
 Author-email: acheong@student.dalat.org
 License: GNU General Public License v2.0
 Project-URL: Bug Report, https://github.com/acheong08/BingImageCreator/issues/new
 Classifier: License :: OSI Approved :: GNU General Public License v2 (GPLv2)
```

### Comparing `BingImageCreator-0.4.2/README.md` & `BingImageCreator-0.4.3/README.md`

 * *Files identical despite different names*

### Comparing `BingImageCreator-0.4.2/setup.py` & `BingImageCreator-0.4.3/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,13 @@
 from setuptools import find_packages
 from setuptools import setup
 
 setup(
     name="BingImageCreator",
-    version="0.4.2",
+    version="0.4.3",
     license="GNU General Public License v2.0",
     author="Antonio Cheong",
     author_email="acheong@student.dalat.org",
     description="High quality image generation by Microsoft. Reverse engineered API.",
     packages=find_packages("src"),
     package_dir={"": "src"},
     url="https://github.com/acheong08/BingImageCreator",
```

### Comparing `BingImageCreator-0.4.2/src/BingImageCreator.egg-info/PKG-INFO` & `BingImageCreator-0.4.3/src/BingImageCreator.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: BingImageCreator
-Version: 0.4.2
+Version: 0.4.3
 Summary: High quality image generation by Microsoft. Reverse engineered API.
 Home-page: https://github.com/acheong08/BingImageCreator
 Author: Antonio Cheong
 Author-email: acheong@student.dalat.org
 License: GNU General Public License v2.0
 Project-URL: Bug Report, https://github.com/acheong08/BingImageCreator/issues/new
 Classifier: License :: OSI Approved :: GNU General Public License v2 (GPLv2)
```

### Comparing `BingImageCreator-0.4.2/src/BingImageCreator.py` & `BingImageCreator-0.4.3/src/BingImageCreator.py`

 * *Files 3% similar despite different names*

```diff
@@ -12,18 +12,15 @@
 from typing import Union
 
 import httpx
 import pkg_resources
 import regex
 import requests
 
-if os.environ.get("BING_URL") == None:
-    BING_URL = "https://www.bing.com"
-else:
-    BING_URL = os.environ.get("BING_URL")
+BING_URL = os.getenv("BING_URL", "https://www.bing.com")
 # Generate random IP between range 13.104.0.0/14
 FORWARDED_IP = (
     f"13.{random.randint(104, 107)}.{random.randint(0, 255)}.{random.randint(0, 255)}"
 )
 HEADERS = {
     "accept": "text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7",
     "accept-language": "en-US,en;q=0.9",
@@ -42,24 +39,25 @@
     "Your prompt has been blocked by Bing. Try to change any bad words and try again."
 )
 error_being_reviewed_prompt = "Your prompt is being reviewed by Bing. Try to change any sensitive words and try again."
 error_noresults = "Could not get results"
 error_unsupported_lang = "\nthis language is currently not supported by bing"
 error_bad_images = "Bad images"
 error_no_images = "No images"
-#
+# Action messages
 sending_message = "Sending request..."
 wait_message = "Waiting for results..."
 download_message = "\nDownloading images..."
 
 
 def debug(debug_file, text_var):
     """helper function for debug"""
     with open(f"{debug_file}", "a", encoding="utf-8") as f:
         f.write(str(text_var))
+        f.write("\n")
 
 
 class ImageGen:
     """
     Image generation by Microsoft Bing
     Parameters:
         auth_cookie: str
@@ -181,45 +179,44 @@
             if img in bad_images:
                 raise Exception("Bad images")
         # No images
         if not normal_image_links:
             raise Exception(error_no_images)
         return normal_image_links
 
-    def save_images(self, links: list, output_dir: str, file_name: str = None) -> None:
+    def save_images(self, links: list, download_count: int, output_dir: str, file_name: str = None) -> None:
         """
         Saves images to output directory
         Parameters:
             links: list[str]
             output_dir: str
             file_name: str
+            download_count: int
         """
         if self.debug_file:
             self.debug(download_message)
         if not self.quiet:
             print(download_message)
         with contextlib.suppress(FileExistsError):
             os.mkdir(output_dir)
         try:
             fn = f"{file_name}_" if file_name else ""
             jpeg_index = 0
-            for link in links:
-                while os.path.exists(
-                    os.path.join(output_dir, f"{fn}{jpeg_index}.jpeg"),
-                ):
+
+            for link in links[:download_count]:
+                while os.path.exists(os.path.join(output_dir, f"{fn}{jpeg_index}.jpeg")):
                     jpeg_index += 1
-                with self.session.get(link, stream=True) as response:
-                    # save response to file
-                    response.raise_for_status()
-                    with open(
-                        os.path.join(output_dir, f"{fn}{jpeg_index}.jpeg"),
-                        "wb",
-                    ) as output_file:
-                        for chunk in response.iter_content(chunk_size=8192):
-                            output_file.write(chunk)
+                response = self.session.get(link)
+                if response.status_code != 200:
+                    raise Exception("Could not download image")
+                # save response to file
+                with open(os.path.join(output_dir, f"{fn}{jpeg_index}.jpeg"), "wb") as output_file:
+                    output_file.write(response.content)
+                jpeg_index += 1
+
         except requests.exceptions.MissingSchema as url_exception:
             raise Exception(
                 "Inappropriate contents found in the generated images. Please try again or try another prompt.",
             ) from url_exception
 
 
 class ImageGenAsync:
@@ -339,64 +336,64 @@
             raise Exception("No images")
         return normal_image_links
 
     async def save_images(
         self,
         links: list,
         output_dir: str,
+        download_count: int,
         file_name: str = None,
     ) -> None:
         """
         Saves images to output directory
         """
+
         if self.debug_file:
             self.debug(download_message)
         if not self.quiet:
             print(download_message)
         with contextlib.suppress(FileExistsError):
             os.mkdir(output_dir)
         try:
             fn = f"{file_name}_" if file_name else ""
             jpeg_index = 0
-            for link in links:
-                while os.path.exists(
-                    os.path.join(output_dir, f"{fn}{jpeg_index}.jpeg"),
-                ):
+
+            for link in links[:download_count]:
+                while os.path.exists(os.path.join(output_dir, f"{fn}{jpeg_index}.jpeg")):
                     jpeg_index += 1
                 response = await self.session.get(link)
                 if response.status_code != 200:
                     raise Exception("Could not download image")
                 # save response to file
-                with open(
-                    os.path.join(output_dir, f"{fn}{jpeg_index}.jpeg"),
-                    "wb",
-                ) as output_file:
+                with open(os.path.join(output_dir, f"{fn}{jpeg_index}.jpeg"), "wb") as output_file:
                     output_file.write(response.content)
+                jpeg_index += 1
         except httpx.InvalidURL as url_exception:
             raise Exception(
                 "Inappropriate contents found in the generated images. Please try again or try another prompt.",
             ) from url_exception
 
 
 async def async_image_gen(
     prompt: str,
+    download_count: int,
     output_dir: str,
     u_cookie=None,
     debug_file=None,
     quiet=False,
     all_cookies=None,
 ):
     async with ImageGenAsync(
         u_cookie,
         debug_file=debug_file,
         quiet=quiet,
         all_cookies=all_cookies,
     ) as image_generator:
         images = await image_generator.get_images(prompt)
-        await image_generator.save_images(images, output_dir=output_dir)
+        await image_generator.save_images(images, output_dir=output_dir, download_count=download_count)
 
 
 def main():
     parser = argparse.ArgumentParser()
     parser.add_argument("-U", help="Auth cookie from browser", type=str)
     parser.add_argument("--cookie-file", help="File containing auth cookie", type=str)
     parser.add_argument(
@@ -410,14 +407,21 @@
         "--output-dir",
         help="Output directory",
         type=str,
         default="./output",
     )
 
     parser.add_argument(
+        "--download-count",
+        help="Number of images to download, value must be less than five",
+        type=int,
+        default=4
+    )
+
+    parser.add_argument(
         "--debug-file",
         help="Path to the file where debug information will be written.",
         type=str,
     )
 
     parser.add_argument(
         "--quiet",
@@ -447,30 +451,35 @@
         with contextlib.suppress(Exception):
             with open(args.cookie_file, encoding="utf-8") as file:
                 cookie_json = json.load(file)
 
     if args.U is None and args.cookie_file is None:
         raise Exception("Could not find auth cookie")
 
+    if args.download_count > 4:
+        raise Exception("The number of downloads must be less than five")
+
     if not args.asyncio:
         # Create image generator
         image_generator = ImageGen(
             args.U,
             args.debug_file,
             args.quiet,
             all_cookies=cookie_json,
         )
         image_generator.save_images(
             image_generator.get_images(args.prompt),
             output_dir=args.output_dir,
+            download_count=args.download_count,
         )
     else:
         asyncio.run(
             async_image_gen(
                 args.prompt,
+                args.download_count,
                 args.output_dir,
                 args.U,
                 args.debug_file,
                 args.quiet,
                 all_cookies=cookie_json,
             ),
         )
```

### Comparing `BingImageCreator-0.4.2/test/test_example.py` & `BingImageCreator-0.4.3/test/test_example.py`

 * *Files identical despite different names*

