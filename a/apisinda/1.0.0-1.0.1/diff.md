# Comparing `tmp/apisinda-1.0.0.tar.gz` & `tmp/apisinda-1.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "apisinda-1.0.0.tar", last modified: Sat Jun 24 19:59:17 2023, max compression
+gzip compressed data, was "apisinda-1.0.1.tar", last modified: Wed Jun 28 12:54:26 2023, max compression
```

## Comparing `apisinda-1.0.0.tar` & `apisinda-1.0.1.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxrwxrwx   0        0        0        0 2023-06-24 19:59:17.355602 apisinda-1.0.0/
--rw-rw-rw-   0        0        0     1061 2023-06-21 22:35:59.000000 apisinda-1.0.0/LICENSE
--rw-rw-rw-   0        0        0     1830 2023-06-24 19:59:17.354613 apisinda-1.0.0/PKG-INFO
--rw-rw-rw-   0        0        0      159 2023-06-21 22:36:33.000000 apisinda-1.0.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-24 19:59:17.339970 apisinda-1.0.0/apisinda/
--rw-rw-rw-   0        0        0        0 2023-06-23 20:20:50.000000 apisinda-1.0.0/apisinda/__init__.py
--rw-rw-rw-   0        0        0    13108 2023-06-24 19:48:53.000000 apisinda-1.0.0/apisinda/pcds.py
--rw-rw-rw-   0        0        0     1464 2023-06-23 20:26:47.000000 apisinda-1.0.0/apisinda/session.py
-drwxrwxrwx   0        0        0        0 2023-06-24 19:59:17.352662 apisinda-1.0.0/apisinda.egg-info/
--rw-rw-rw-   0        0        0     1830 2023-06-24 19:59:17.000000 apisinda-1.0.0/apisinda.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      249 2023-06-24 19:59:17.000000 apisinda-1.0.0/apisinda.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-24 19:59:17.000000 apisinda-1.0.0/apisinda.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       37 2023-06-24 19:59:17.000000 apisinda-1.0.0/apisinda.egg-info/requires.txt
--rw-rw-rw-   0        0        0        9 2023-06-24 19:59:17.000000 apisinda-1.0.0/apisinda.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      612 2023-06-24 19:58:45.000000 apisinda-1.0.0/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-24 19:59:17.356567 apisinda-1.0.0/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 12:54:26.815643 apisinda-1.0.1/
+-rw-rw-rw-   0        0        0     1061 2023-06-21 22:35:59.000000 apisinda-1.0.1/LICENSE
+-rw-rw-rw-   0        0        0     1830 2023-06-28 12:54:26.813690 apisinda-1.0.1/PKG-INFO
+-rw-rw-rw-   0        0        0      159 2023-06-21 22:36:33.000000 apisinda-1.0.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 12:54:26.747288 apisinda-1.0.1/apisinda/
+-rw-rw-rw-   0        0        0        0 2023-06-23 20:20:50.000000 apisinda-1.0.1/apisinda/__init__.py
+-rw-rw-rw-   0        0        0    13016 2023-06-28 01:33:36.000000 apisinda-1.0.1/apisinda/pcds.py
+-rw-rw-rw-   0        0        0     1464 2023-06-23 20:26:47.000000 apisinda-1.0.1/apisinda/session.py
+drwxrwxrwx   0        0        0        0 2023-06-28 12:54:26.811737 apisinda-1.0.1/apisinda.egg-info/
+-rw-rw-rw-   0        0        0     1830 2023-06-28 12:54:26.000000 apisinda-1.0.1/apisinda.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      249 2023-06-28 12:54:26.000000 apisinda-1.0.1/apisinda.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 12:54:26.000000 apisinda-1.0.1/apisinda.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       37 2023-06-28 12:54:26.000000 apisinda-1.0.1/apisinda.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        9 2023-06-28 12:54:26.000000 apisinda-1.0.1/apisinda.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      612 2023-06-28 12:52:17.000000 apisinda-1.0.1/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 12:54:26.815643 apisinda-1.0.1/setup.cfg
```

### Comparing `apisinda-1.0.0/LICENSE` & `apisinda-1.0.1/LICENSE`

 * *Files identical despite different names*

### Comparing `apisinda-1.0.0/PKG-INFO` & `apisinda-1.0.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: apisinda
-Version: 1.0.0
+Version: 1.0.1
 Summary: SINDA API
 Author-email: Alessandro Cerioli <ceriolialessandro98@gmail.com>
 License: MIT License
         
         Copyright (c) API SINDA
         
         Permission is hereby granted, free of charge, to any person obtaining a copy
```

### Comparing `apisinda-1.0.0/apisinda/pcds.py` & `apisinda-1.0.1/apisinda/pcds.py`

 * *Files 2% similar despite different names*

```diff
@@ -35,57 +35,54 @@
 }
 
 def createHeader(token):
     accessToken = 'Bearer ' + token
     return {'Authorization' : accessToken}
 
 class PCD:
-    def __init__(self, id, token):
-        if type(id) == int and type(token) == str:
-            self.id = id
+    def __init__(self, numero, token):
+        if type(numero) == int and type(token) == str:
+            self.numero = numero
             self.token = token
         else:
-            print("Id must be integer and token must be string")
-
-    def get_id(self):
-        return self.id
+            print("Numero must be integer and token must be string")
 
     def get_metadata(self):
         try:
-            metadados = requests.get(url + 'buscar/' + str(self.id), headers=createHeader(self.token))
+            metadados = requests.get(url + 'buscar/' + str(self.numero), headers=createHeader(self.token))
             if metadados.ok:
                 return metadados.json()
             else:
                 return metadados.text
         except:
             return("Error fetching metadata")
 
     def get_metadata_serie(self):
         metadados = self.get_metadata()
         try:
             return pd.Series(metadados)
         except:
             return metadados
 
-    def get_resumed_metadata(self):
+    def get_metadata_resumed(self):
         metadados = self.get_metadata()
         try:
             extra_field = ['latitude', 'longitude', 'estado', 'cidade']
             metadados_filtered = {'id': metadados['id'], 'numero': metadados['numero'],
                 'ativo': metadados['ativo'], 'proprietario': metadados['proprietario']['nome']}
             for field in extra_field:
                 if field in metadados:
                     metadados_filtered[field] = metadados[field]
             return metadados_filtered
         except:
             return("Error fetching resumed metadata")
 
     def get_owner(self):
         try:
-            metadados = requests.get(url + 'buscar/' + str(self.id), headers=createHeader(self.token))
+            metadados = requests.get(url + 'buscar/' + str(self.numero), headers=createHeader(self.token))
             if metadados.ok:
                 return metadados.json()['proprietario']
             else:
                 return metadados.text
         except:
             return("Error fetching owner")
     
@@ -94,25 +91,25 @@
         try:
             return proprietario['nome']
         except:
             return proprietario
 
     def get_pcd_family(self):
         try:
-            metadados = requests.get(url + 'buscar/' + str(self.id), headers=createHeader(self.token))
+            metadados = requests.get(url + 'buscar/' + str(self.numero), headers=createHeader(self.token))
             if metadados.ok:
                 return metadados.json()['familiaPCD']
             else:
                 return metadados.text
         except:
             return("Error fetching pcd family")
 
     def get_sensors(self):
         try:
-            sensores = requests.get(url + 'buscar/sensores/' + str(self.id), headers=createHeader(self.token))
+            sensores = requests.get(url + 'buscar/sensores/' + str(self.numero), headers=createHeader(self.token))
             if sensores.ok:
                 return sensores.json()
             else:
                 return sensores.text
         except:
             return("Error fetching sensors")
 
@@ -121,31 +118,29 @@
         try:
             return pd.DataFrame(sensores)
         except:
             return sensores
 
     def get_available_period(self):
         try:
-            periodo = requests.get(url + 'buscar/periodo-disponivel/' + str(self.id), headers=createHeader(self.token))
+            periodo = requests.get(url + 'buscar/periodo-disponivel/' + str(self.numero), headers=createHeader(self.token))
             if periodo.ok:
                 return periodo.json()
             else:
                 return periodo.text
         except:
             return("Error fetching available period")
 
-    def get_data(self, dataInicial="", dataFinal="", sensores=[]):
+    def get_data(self, dataInicial="", dataFinal=""):
         try:
             if dataInicial == "" or dataFinal ==  "":
                 periodo = self.get_available_period()
                 dataInicial = periodo['dataInicial']
                 dataFinal = periodo['dataFinal']
-            analisePCD = {'pcd': {'numero': self.id}, 'dataInicial': dataInicial, 'dataFinal': dataFinal}
-            if sensores != []:
-                analisePCD['sensores'] = sensores
+            analisePCD = {'pcd': {'numero': self.numero}, 'dataInicial': dataInicial, 'dataFinal': dataFinal}
             dados = requests.post(url + 'buscar/dados', json=analisePCD, headers=createHeader(self.token))
             return dados.json()
         except:
             return("Error fetching data")
 
     def get_data_df(self):
         dados = self.get_data()
@@ -167,15 +162,15 @@
             dados_df1 = dados_df[dados_df.index>dataInicial1]
             return dados_df1
         except:
             return("Error fetching small data")
 
     def is_private(self):
         try:
-            metadados = requests.get(url + 'buscar/' + str(self.id), headers=createHeader(self.token))
+            metadados = requests.get(url + 'buscar/' + str(self.numero), headers=createHeader(self.token))
             if metadados.ok:
                 return metadados.json()['privado']
             else:
                 return metadados.text
         except:
             return("Error checking if pcd is private")
```

### Comparing `apisinda-1.0.0/apisinda/session.py` & `apisinda-1.0.1/apisinda/session.py`

 * *Files identical despite different names*

### Comparing `apisinda-1.0.0/apisinda.egg-info/PKG-INFO` & `apisinda-1.0.1/apisinda.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: apisinda
-Version: 1.0.0
+Version: 1.0.1
 Summary: SINDA API
 Author-email: Alessandro Cerioli <ceriolialessandro98@gmail.com>
 License: MIT License
         
         Copyright (c) API SINDA
         
         Permission is hereby granted, free of charge, to any person obtaining a copy
```

### Comparing `apisinda-1.0.0/pyproject.toml` & `apisinda-1.0.1/pyproject.toml`

 * *Files 19% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires      = ["setuptools>=61.0.0", "wheel"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "apisinda"
-version = "1.0.0"
+version = "1.0.1"
 description = "SINDA API"
 readme = "README.md"
 authors = [{ name = "Alessandro Cerioli", email = "ceriolialessandro98@gmail.com" }]
 license = { file = "LICENSE" }
 classifiers = [
     "License :: OSI Approved :: MIT License",
     "Programming Language :: Python :: 3",
```

