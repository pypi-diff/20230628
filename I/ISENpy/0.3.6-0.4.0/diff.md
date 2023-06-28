# Comparing `tmp/ISENpy-0.3.6.tar.gz` & `tmp/ISENpy-0.4.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ISENpy-0.3.6.tar", last modified: Tue Apr 18 12:55:03 2023, max compression
+gzip compressed data, was "ISENpy-0.4.0.tar", last modified: Wed Jun 28 13:58:53 2023, max compression
```

## Comparing `ISENpy-0.3.6.tar` & `ISENpy-0.4.0.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxr-xr-x   0 corentin   (501) staff       (20)        0 2023-04-18 12:55:03.134698 ISENpy-0.3.6/
-drwxr-xr-x   0 corentin   (501) staff       (20)        0 2023-04-18 12:55:03.133801 ISENpy-0.3.6/ISENpy/
--rwxrwxrwx   0 corentin   (501) staff       (20)     1343 2023-04-18 12:54:49.000000 ISENpy-0.3.6/ISENpy/__init__.py
--rwxrwxrwx   0 corentin   (501) staff       (20)     6318 2023-03-22 13:06:10.000000 ISENpy-0.3.6/ISENpy/client.py
--rwxrwxrwx   0 corentin   (501) staff       (20)    29767 2023-04-18 12:53:40.000000 ISENpy-0.3.6/ISENpy/dataClasses.py
-drwxr-xr-x   0 corentin   (501) staff       (20)        0 2023-04-18 12:55:03.134408 ISENpy-0.3.6/ISENpy.egg-info/
--rw-r--r--   0 corentin   (501) staff       (20)     5166 2023-04-18 12:55:03.000000 ISENpy-0.3.6/ISENpy.egg-info/PKG-INFO
--rw-r--r--   0 corentin   (501) staff       (20)      233 2023-04-18 12:55:03.000000 ISENpy-0.3.6/ISENpy.egg-info/SOURCES.txt
--rw-r--r--   0 corentin   (501) staff       (20)        1 2023-04-18 12:55:03.000000 ISENpy-0.3.6/ISENpy.egg-info/dependency_links.txt
--rw-r--r--   0 corentin   (501) staff       (20)       18 2023-04-18 12:55:03.000000 ISENpy-0.3.6/ISENpy.egg-info/requires.txt
--rw-r--r--   0 corentin   (501) staff       (20)        7 2023-04-18 12:55:03.000000 ISENpy-0.3.6/ISENpy.egg-info/top_level.txt
--rwxrwxrwx   0 corentin   (501) staff       (20)     1068 2022-08-01 16:04:58.000000 ISENpy-0.3.6/LICENSE
--rw-r--r--   0 corentin   (501) staff       (20)     5166 2023-04-18 12:55:03.134585 ISENpy-0.3.6/PKG-INFO
--rwxrwxrwx   0 corentin   (501) staff       (20)     4730 2023-03-22 13:41:56.000000 ISENpy-0.3.6/README.md
--rw-r--r--   0 corentin   (501) staff       (20)       38 2023-04-18 12:55:03.134736 ISENpy-0.3.6/setup.cfg
--rw-r--r--   0 corentin   (501) staff       (20)      848 2023-04-18 12:54:46.000000 ISENpy-0.3.6/setup.py
+drwxr-xr-x   0 corentin   (501) staff       (20)        0 2023-06-28 13:58:53.135733 ISENpy-0.4.0/
+drwxr-xr-x   0 corentin   (501) staff       (20)        0 2023-06-28 13:58:53.134927 ISENpy-0.4.0/ISENpy/
+-rwxr-xr-x   0 corentin   (501) staff       (20)     1343 2023-06-28 13:58:17.000000 ISENpy-0.4.0/ISENpy/__init__.py
+-rwxr-xr-x   0 corentin   (501) staff       (20)     6915 2023-06-28 13:47:10.000000 ISENpy-0.4.0/ISENpy/client.py
+-rwxr-xr-x   0 corentin   (501) staff       (20)    35038 2023-06-28 13:57:42.000000 ISENpy-0.4.0/ISENpy/dataClasses.py
+drwxr-xr-x   0 corentin   (501) staff       (20)        0 2023-06-28 13:58:53.135463 ISENpy-0.4.0/ISENpy.egg-info/
+-rw-r--r--   0 corentin   (501) staff       (20)     5427 2023-06-28 13:58:53.000000 ISENpy-0.4.0/ISENpy.egg-info/PKG-INFO
+-rw-r--r--   0 corentin   (501) staff       (20)      233 2023-06-28 13:58:53.000000 ISENpy-0.4.0/ISENpy.egg-info/SOURCES.txt
+-rw-r--r--   0 corentin   (501) staff       (20)        1 2023-06-28 13:58:53.000000 ISENpy-0.4.0/ISENpy.egg-info/dependency_links.txt
+-rw-r--r--   0 corentin   (501) staff       (20)       18 2023-06-28 13:58:53.000000 ISENpy-0.4.0/ISENpy.egg-info/requires.txt
+-rw-r--r--   0 corentin   (501) staff       (20)        7 2023-06-28 13:58:53.000000 ISENpy-0.4.0/ISENpy.egg-info/top_level.txt
+-rwxrwxrwx   0 corentin   (501) staff       (20)     1068 2022-08-01 16:04:58.000000 ISENpy-0.4.0/LICENSE
+-rw-r--r--   0 corentin   (501) staff       (20)     5427 2023-06-28 13:58:53.135614 ISENpy-0.4.0/PKG-INFO
+-rwxr-xr-x   0 corentin   (501) staff       (20)     4991 2023-06-28 13:43:43.000000 ISENpy-0.4.0/README.md
+-rw-r--r--   0 corentin   (501) staff       (20)       38 2023-06-28 13:58:53.135772 ISENpy-0.4.0/setup.cfg
+-rw-r--r--   0 corentin   (501) staff       (20)      848 2023-06-28 13:58:09.000000 ISENpy-0.4.0/setup.py
```

### Comparing `ISENpy-0.3.6/ISENpy/__init__.py` & `ISENpy-0.4.0/ISENpy/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,12 +19,12 @@
 """
 
 
 __title__ = "ISENpy"
 __author__ = "CorentinMre"
 __license__ = "MIT"
 __copyright__ = "Copyright (c) CorentinMre"
-__version__ = "0.3.6"
+__version__ = "0.4.0"
 
 
 from .dataClasses import *
 from .client import *
```

### Comparing `ISENpy-0.3.6/ISENpy/client.py` & `ISENpy-0.4.0/ISENpy/client.py`

 * *Files 12% similar despite different names*

```diff
@@ -27,14 +27,36 @@
         classMember(cycle:str, annee:str, ville:str) -> dict
         webAurion() -> dataClasses.WebAurion
             grades() -> dict of grades of the user
             absences() -> list of dict of absences of the user
             planning() -> list ofdict of planning of the user
                 start_date:str Optional -> The start of the planning (format : "dd-mm-yyyy")
                 end_end:str Optional -> The end of the planning  (format : "dd-mm-yyyy")
+                
+            getOtherPlanning() -> list of dict of planning of the user
+                start_date:str Optional -> The start of the planning (format : "dd-mm-yyyy")
+                end_end:str Optional -> The end of the planning  (format : "dd-mm-yyyy")
+                classPlanning:str -> The class planning you want to get (Default: "CIR")
+                classCity:str -> The class city you want to get (Default: "Caen")
+                classYear:str -> The class year you want to get (Default: "1")
+                classGroup:str -> The class group you want to get (Default: "CBIO1 CIR1 Caen 2022-2023 Groupe 1")
+                
+            getSchoolReport() -> dict of school report of the user (format : {"nbReport": int, "data": {"name": "id"}})
+            
+            downloadReport() -> Download the school report
+                path (str, optional): path of the report. Defaults to the name in WebAurion.
+                idReport (str, optional): id of the report. Defaults all the report of the user
+            
+                
+        moodle() -> dataClasses.Moodle
+            getCoursesLink() -> dict of courses link
+            getCourseResources(courseId:str) -> dict of course resources
+            downloadResources(courseId:str, resourceId:str) -> Download the resource
+
+            
         userInfo() -> dict
         logout() Optional -> Logout from the session
     """
 
 
     def __init__(self, username:str, password:str) -> None:
         #Set the user info
@@ -168,36 +190,7 @@
         #Get the user info
         req = self.session.get("https://web.isen-ouest.fr/uPortal/api/v5-1/userinfo")
         #Scrap the user info
         info  = json.loads(base64.urlsafe_b64decode(req.text.split(".")[1].encode()).decode())
         #Return the user info
         return info
 
-
-
-if __name__ == "__main__":
-
-
-    client = ISEN("", "")
-
-    if not client.logged_in:
-        print("Identifiant ou mot de passe incorect !!")
-        exit()
-
-
-    #print(client.classMember("CIR", "1", "Caen")) #Get all the students of the class CIR1 Caen
-    #print(client.classMember()) #Get all the students of the class you are in
-    #print(client.userInfo()) #Get your user info
-
-    #webAurion = client.webAurion() #Get the webAurion object
-    #absence = webAurion.absences() #Get your absences
-    #grade = webAurion.grades() #Get your grades
-
-    #print(absence)
-    #print(grade)
-
-    moodle = client.moodle() #Get the moodle object
-    
-    moodle.getPageInformation() #Get all the assignments
-
-
-    client.logout()
```

### Comparing `ISENpy-0.3.6/ISENpy/dataClasses.py` & `ISENpy-0.4.0/ISENpy/dataClasses.py`

 * *Files 15% similar despite different names*

```diff
@@ -35,21 +35,28 @@
         getClassYear() -> list of dict of year in webAurion
             classPlanning:str Optional -> The class of the planning (Ex. : "CIR")
             classCity:str Optional -> The city of the planning (Ex. : "Caen")
         getClassGroup() -> list of dict of group in webAurion
             classPlanning:str Optional -> The class of the planning (Ex. : "CIR")
             classCity:str Optional -> The city of the planning (Ex. : "Caen")
             classYear:str Optional -> The year of the planning (Ex. : "1")
+            
+        getSchoolReport() -> dict of report of the user
+        downloadReport() -> download the report of the user
+            path:str Optional -> The path of the report (Default : the name of the file in WebAurion)
+            idReport:str Optional -> The id of the report (Default : all the report of the user)
+        
         """
     
         def __init__(self, session):
             #Get the session of the user
             self.session = session
             #Base WebAurion url
             self.baseWebAurionUrl = "https://web.isen-ouest.fr/webAurion/?portail=false"
+            self.baseMainPageUrl = "https://web.isen-ouest.fr/webAurion/faces/MainMenuPage.xhtml"
             baseReq = self.session.get(self.baseWebAurionUrl)
             if baseReq.status_code != 200:
                 raise Exception(f"WebAuiron is not available for the moment: Error {baseReq.status_code}")
             #Get the payload of the page
             self.payload = self.__getPayloadOfThePage(baseReq.text, {})[0]
             #Set the language to french
             self.language = {"form:j_idt755_input" : "275805"} # Langue Francaise
@@ -95,28 +102,31 @@
                 "javax.faces.source": id_selection,
                 "javax.faces.partial.execute": id_selection,
                 "javax.faces.partial.render": "form:sidebar",
                 id_selection: id_selection,
             }
             self.dataOtherPlanning.update(self.payload)
             
+            self.payloadReport = {}
+            self.infoReport = {}
+            
             
         def __webAurion(self, url:str, data:dict) -> requests.Response:
             """Requests a page of WebAurion
 
             Args:
                 url (str): The url of the page we want to request
                 data (dict): The data we want to send
 
             Returns:
                 requests.Response: The response of the request
             """
 
             #Url of the main page of webAurion
-            mainPageUrl = "https://web.isen-ouest.fr/webAurion/faces/MainMenuPage.xhtml"
+            mainPageUrl = self.baseMainPageUrl
             #Set the payload
             data.update(self.payload)
             self.session.post(mainPageUrl, data=data)
             
             #return the requests.Response of the url
             return self.session.get(url)
 
@@ -353,15 +363,15 @@
                 id (str): id of the next page
 
             Returns:
                 BeautifulSoup: soup page
             """
 
             
-            url = "https://web.isen-ouest.fr/webAurion/faces/MainMenuPage.xhtml"
+            url = self.baseMainPageUrl
             data["webscolaapp.Sidebar.ID_SUBMENU"] = "submenu_"+id
             
             req = self.session.post(url, data=data)
             
             soup = BeautifulSoup(req.text, "xml")
             
             inf = soup.find("update", {"id": "form:sidebar"}).text
@@ -458,15 +468,15 @@
             classCity = classPlanning + " " + classCity
             classYear = classPlanning + " " + classYear
             
             payloadOfLastClass = self.classYear[classYear]
             
             payloadOfLastClass.update(self.payload)
             
-            req = self.session.post("https://web.isen-ouest.fr/webAurion/faces/MainMenuPage.xhtml", data=payloadOfLastClass)
+            req = self.session.post(self.baseMainPageUrl, data=payloadOfLastClass)
             
             soup = BeautifulSoup(req.text, "html.parser")
             
             allLastClass = soup.find("tbody", {"class": "ui-datatable-data"}).find_all("tr")
             
             for child in allLastClass:
                 self.classGroup[child.find("span", {"class": "preformatted"}).text] = child["data-rk"]
@@ -583,14 +593,133 @@
             payloadForChoicePlanning[classYear].update(lastPayload)
 
             req = self.session.post("https://web.isen-ouest.fr/webAurion/faces/ChoixPlanning.xhtml", data=payloadForChoicePlanning[classYear])
 
             return self.__getWorkingTime(req, start_date, end_date, True ,classGroup)
         
 
+        
+        
+        def getSchoolReport(self) -> dict:
+            """ Get the report of the user
+
+            Returns:
+                dict: dict of the report
+                    format : {"nbReport": int, "data": {"name": "id"}}
+            
+            Raises:
+                Exception: if the user not have any report
+            """
+            
+            urlPost = self.baseMainPageUrl
+            
+            information = "Scolarité"
+            id_information = self.id_leftMenu[information]
+            soup = self.__soupForPlanning(self.dataOtherPlanning, id_information)
+            
+            id_info = {}
+            listOfInformation = soup.find("li", {"class": "enfants-entierement-charges"}).find_all("li")
+            for child in listOfInformation:
+                id_info[child.find("span", {"class": "ui-menuitem-text"}).text] = child["class"][-2].split("_")[-1]
+                
+            information2 = "Mes documents"
+            id_information2 = id_info[information2]
+            
+            soup = self.__soupForPlanning(self.dataOtherPlanning, id_information2)
+            id_info2 = {}
+            listOfInformation2 = soup.find("li", {"class": "enfants-entierement-charges"}).find_all("li")
+            for child in listOfInformation2:
+                id_info2[child.find("span", {"class": "ui-menuitem-text"}).text] = child.find("a", {"class": "ui-menuitem-link"})["class"][-2].split("_")[-1]
+            
+
+            payload = {
+                'form:sidebar':'form:sidebar','form:sidebar_menuid':'1_0_1',
+                "form:j_idt780:j_idt782_dropdown":"1", "form:j_idt780:j_idt782_mobiledropdown":"1"
+            }
+            
+            req = self.session.post(urlPost, data=payload)
+            
+            if req.status_code != 200:
+                raise Exception(f"WebAuiron is not available for the moment: Error {req.status_code}, 1")
+            
+            payload2 = self.__getPayloadOfThePage(req.text, {})[0]
+            
+            payload2.update(payload)
+            payload2.update(self.language)
+            
+            req = self.session.post(urlPost, data=payload2)
+            
+            if req.status_code != 200:
+                raise Exception(f"WebAuiron is not available for the moment: Error {req.status_code}, 2")
+            
+            self.payloadReport = self.__getPayloadOfThePage(req.text, {})[0]
+            
+            soup = BeautifulSoup(req.text, "html.parser")
+            
+            report = soup.find("div", {"class": "ui-datatable-tablewrapper"}).find("select").find_all("option")
+            
+            result = {"nbReport": len(report), "data":{}}
+            
+            for i in report:
+                nameFile = i.text.split(".pdf")[0] # because we have space after the name of the file
+                nameFile += ".pdf"
+                result["data"][nameFile] = i["value"]
+            
+            
+            self.infoReport = result
+        
+            return result
+        
+        def downloadReport(self, path:str = None, idReport:str = None) -> None:
+            """ Download the report of the user
+
+            Args:
+                path (str, optional): path of the report. Defaults to the name in WebAurion.
+                idReport (str, optional): id of the report. Defaults all the report of the user
+
+            Raises:
+                Exception: if the user not have any report
+                Exception: if the report is not found
+            """
+            
+            if self.payloadReport == {}:
+                self.infoReport = self.getSchoolReport()
+                
+
+            if self.infoReport["nbReport"] == 0:
+                raise Exception("The user not have any report")
+            
+            if self.infoReport["nbReport"] > 1 and path != None:
+                raise Exception("The user have more than one report, please choose no one path or no path")
+            
+            if idReport == None:
+                for i in self.infoReport["data"].keys():
+                    if path == None:
+                        path = i
+                    self.downloadReport(path, self.infoReport["data"][i])
+                    return
+                    
+
+            urlChoixDonnee = "https://web.isen-ouest.fr/webAurion/faces/ChoixDonnee.xhtml"
+            
+            payload = {
+                'form:j_idt193:0:j_idt209':'form:j_idt193:0:j_idt209',
+                "form:j_idt193:0:documents_input":idReport,
+            }
+            
+            payload.update(self.payloadReport)
+            
+            req = self.session.post(urlChoixDonnee, data=payload)
+            
+            if req.status_code != 200:
+                raise Exception(f"WebAuiron is not available for the moment: Error {req.status_code}")
+            
+            with open(path, "wb") as f:
+                f.write(req.content)
+            
 
 class Moodle:
     
     def __init__(self, session):
         #Get the session of the user
         self.session = session
```

### Comparing `ISENpy-0.3.6/ISENpy.egg-info/PKG-INFO` & `ISENpy-0.4.0/ISENpy.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ISENpy
-Version: 0.3.6
+Version: 0.4.0
 Summary: A python API wrapper for ISEN-OUEST
 Home-page: https://github.com/CorentinMre/ISENpy
 Author: CorentinMre
 Author-email: corentin.marie@isen-ouest.yncrea.fr
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
@@ -75,14 +75,20 @@
 
 grade = webAurion.grades() #Get your grades
 print(grade)
 
 planning = webAurion.planning() #Get your planning of the week. Argument(Optional) : 'start_date' (format : "dd-mm-yyyy") and 'end_date' (format : "dd-mm-yyyy")
 print(planning)
 
+schoolReport = webAurion.getSchoolReport() #Get your school report
+print(schoolReport)
+
+# for download the report
+#webAurion.downloadReport() #Download the school report. Argument(Optional) : 'path' (format : "path/to/file.pdf") and 'idReport' (format : "id")
+
 ```
 
 ## Other example if you  want to get your planning in the calendar of your computer
 
 - This script uses the 'ics' and 'datetime' modules
 - `pip3 install ics datetime`
```

### Comparing `ISENpy-0.3.6/LICENSE` & `ISENpy-0.4.0/LICENSE`

 * *Files identical despite different names*

### Comparing `ISENpy-0.3.6/PKG-INFO` & `ISENpy-0.4.0/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ISENpy
-Version: 0.3.6
+Version: 0.4.0
 Summary: A python API wrapper for ISEN-OUEST
 Home-page: https://github.com/CorentinMre/ISENpy
 Author: CorentinMre
 Author-email: corentin.marie@isen-ouest.yncrea.fr
 License: MIT
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
@@ -75,14 +75,20 @@
 
 grade = webAurion.grades() #Get your grades
 print(grade)
 
 planning = webAurion.planning() #Get your planning of the week. Argument(Optional) : 'start_date' (format : "dd-mm-yyyy") and 'end_date' (format : "dd-mm-yyyy")
 print(planning)
 
+schoolReport = webAurion.getSchoolReport() #Get your school report
+print(schoolReport)
+
+# for download the report
+#webAurion.downloadReport() #Download the school report. Argument(Optional) : 'path' (format : "path/to/file.pdf") and 'idReport' (format : "id")
+
 ```
 
 ## Other example if you  want to get your planning in the calendar of your computer
 
 - This script uses the 'ics' and 'datetime' modules
 - `pip3 install ics datetime`
```

### Comparing `ISENpy-0.3.6/README.md` & `ISENpy-0.4.0/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -61,14 +61,20 @@
 
 grade = webAurion.grades() #Get your grades
 print(grade)
 
 planning = webAurion.planning() #Get your planning of the week. Argument(Optional) : 'start_date' (format : "dd-mm-yyyy") and 'end_date' (format : "dd-mm-yyyy")
 print(planning)
 
+schoolReport = webAurion.getSchoolReport() #Get your school report
+print(schoolReport)
+
+# for download the report
+#webAurion.downloadReport() #Download the school report. Argument(Optional) : 'path' (format : "path/to/file.pdf") and 'idReport' (format : "id")
+
 ```
 
 ## Other example if you  want to get your planning in the calendar of your computer
 
 - This script uses the 'ics' and 'datetime' modules
 - `pip3 install ics datetime`
```

### Comparing `ISENpy-0.3.6/setup.py` & `ISENpy-0.4.0/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name='ISENpy',
-    version='0.3.6',    
+    version='0.4.0',    
     description='A python API wrapper for ISEN-OUEST',
     long_description_content_type = "text/markdown",
     long_description=long_description,
     url='https://github.com/CorentinMre/ISENpy',
     author='CorentinMre',
     author_email='corentin.marie@isen-ouest.yncrea.fr',
     license='MIT',
```

