# Comparing `tmp/proptables-0.0.7.tar.gz` & `tmp/proptables-0.0.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "proptables-0.0.7.tar", last modified: Tue Jun 13 19:26:21 2023, max compression
+gzip compressed data, was "proptables-0.0.8.tar", last modified: Wed Jun 28 13:29:35 2023, max compression
```

## Comparing `proptables-0.0.7.tar` & `proptables-0.0.8.tar`

### file list

```diff
@@ -1,42 +1,42 @@
-drwxrwxrwx   0        0        0        0 2023-06-13 19:26:21.679477 proptables-0.0.7/
--rw-rw-rw-   0        0        0     1070 2023-06-03 19:14:15.000000 proptables-0.0.7/LICENCE.txt
--rw-rw-rw-   0        0        0       62 2023-06-11 10:30:34.000000 proptables-0.0.7/MANIFEST.in
--rw-rw-rw-   0        0        0     2427 2023-06-13 19:26:21.679477 proptables-0.0.7/PKG-INFO
--rw-rw-rw-   0        0        0     1928 2023-06-13 19:26:16.000000 proptables-0.0.7/README.md
-drwxrwxrwx   0        0        0        0 2023-06-13 19:26:21.578243 proptables-0.0.7/proptables/
-drwxrwxrwx   0        0        0        0 2023-06-13 19:26:21.651538 proptables-0.0.7/proptables/R134a/
--rw-rw-rw-   0        0        0     2379 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/R134a/R134a_PresSat.csv
--rw-rw-rw-   0        0        0      239 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/R134a/R134a_SupPreSat.csv
--rw-rw-rw-   0        0        0     9904 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/R134a/R134a_Super.csv
--rw-rw-rw-   0        0        0     3782 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/R134a/R134a_TempSat.csv
--rw-rw-rw-   0        0        0       39 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/R134a/__init__.py
--rw-rw-rw-   0        0        0     4503 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/R134a/calSatData.py
--rw-rw-rw-   0        0        0     4210 2023-06-12 08:12:48.000000 proptables-0.0.7/proptables/R134a/calSuperHeatData.py
--rw-rw-rw-   0        0        0      574 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/R134a/import_data.py
--rw-rw-rw-   0        0        0      113 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/R134a/interpolate.py
--rw-rw-rw-   0        0        0     1389 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/R134a/main.py
--rw-rw-rw-   0        0        0     7334 2023-06-13 19:24:16.000000 proptables-0.0.7/proptables/R134a/superheated.py
--rw-rw-rw-   0        0        0     2068 2023-06-13 18:28:04.000000 proptables-0.0.7/proptables/R134a/test.py
--rw-rw-rw-   0        0        0       88 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-13 19:26:21.678480 proptables-0.0.7/proptables/water/
--rw-rw-rw-   0        0        0     3388 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/water/H2O_Compressed.csv
--rw-rw-rw-   0        0        0     3894 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/water/H2O_PresSat.csv
--rw-rw-rw-   0        0        0    15532 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/water/H2O_Super.csv
--rw-rw-rw-   0        0        0     4185 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/water/H2O_TempSat.csv
--rw-rw-rw-   0        0        0      395 2023-06-13 18:34:33.000000 proptables-0.0.7/proptables/water/H2O_superSat.csv
--rw-rw-rw-   0        0        0       39 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/water/__init__.py
--rw-rw-rw-   0        0        0        0 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/water/calwatercompressed.py
--rw-rw-rw-   0        0        0     4462 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/water/calwatersat.py
--rw-rw-rw-   0        0        0     4108 2023-06-13 18:34:33.000000 proptables-0.0.7/proptables/water/calwatersuperheat.py
--rw-rw-rw-   0        0        0      527 2023-06-13 18:34:33.000000 proptables-0.0.7/proptables/water/import_data_water.py
--rw-rw-rw-   0        0        0     1383 2023-06-13 18:34:33.000000 proptables-0.0.7/proptables/water/main.py
--rw-rw-rw-   0        0        0      161 2023-06-11 10:30:34.000000 proptables-0.0.7/proptables/water/mainwater.py
--rw-rw-rw-   0        0        0    10749 2023-06-13 19:23:27.000000 proptables-0.0.7/proptables/water/superheated.py
--rw-rw-rw-   0        0        0     1262 2023-06-13 18:34:33.000000 proptables-0.0.7/proptables/water/test.py
-drwxrwxrwx   0        0        0        0 2023-06-13 19:26:21.630002 proptables-0.0.7/proptables.egg-info/
--rw-rw-rw-   0        0        0     2427 2023-06-13 19:26:21.000000 proptables-0.0.7/proptables.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1055 2023-06-13 19:26:21.000000 proptables-0.0.7/proptables.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-13 19:26:21.000000 proptables-0.0.7/proptables.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       11 2023-06-13 19:26:21.000000 proptables-0.0.7/proptables.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      108 2023-06-05 08:01:30.000000 proptables-0.0.7/pyproject.toml
--rw-rw-rw-   0        0        0      593 2023-06-13 19:26:21.681510 proptables-0.0.7/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 13:29:35.718815 proptables-0.0.8/
+-rw-rw-rw-   0        0        0     1070 2023-06-03 19:14:15.000000 proptables-0.0.8/LICENCE.txt
+-rw-rw-rw-   0        0        0       62 2023-06-11 10:30:34.000000 proptables-0.0.8/MANIFEST.in
+-rw-rw-rw-   0        0        0      984 2023-06-28 13:29:35.718815 proptables-0.0.8/PKG-INFO
+-rw-rw-rw-   0        0        0      485 2023-06-28 13:28:57.000000 proptables-0.0.8/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 13:29:35.668592 proptables-0.0.8/proptables/
+drwxrwxrwx   0        0        0        0 2023-06-28 13:29:35.698798 proptables-0.0.8/proptables/R134a/
+-rw-rw-rw-   0        0        0     2379 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/R134a/R134a_PresSat.csv
+-rw-rw-rw-   0        0        0      239 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/R134a/R134a_SupPreSat.csv
+-rw-rw-rw-   0        0        0     9929 2023-06-28 13:27:00.000000 proptables-0.0.8/proptables/R134a/R134a_Super.csv
+-rw-rw-rw-   0        0        0     3782 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/R134a/R134a_TempSat.csv
+-rw-rw-rw-   0        0        0       39 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/R134a/__init__.py
+-rw-rw-rw-   0        0        0     4591 2023-06-28 13:28:32.000000 proptables-0.0.8/proptables/R134a/calSatData.py
+-rw-rw-rw-   0        0        0     4386 2023-06-28 13:18:24.000000 proptables-0.0.8/proptables/R134a/calSuperHeatData.py
+-rw-rw-rw-   0        0        0      574 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/R134a/import_data.py
+-rw-rw-rw-   0        0        0      113 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/R134a/interpolate.py
+-rw-rw-rw-   0        0        0     1389 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/R134a/main.py
+-rw-rw-rw-   0        0        0     7334 2023-06-15 19:19:09.000000 proptables-0.0.8/proptables/R134a/superheated.py
+-rw-rw-rw-   0        0        0     2068 2023-06-13 18:28:04.000000 proptables-0.0.8/proptables/R134a/test.py
+-rw-rw-rw-   0        0        0       88 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:29:35.718815 proptables-0.0.8/proptables/water/
+-rw-rw-rw-   0        0        0     3388 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/water/H2O_Compressed.csv
+-rw-rw-rw-   0        0        0     3894 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/water/H2O_PresSat.csv
+-rw-rw-rw-   0        0        0    15532 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/water/H2O_Super.csv
+-rw-rw-rw-   0        0        0     4185 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/water/H2O_TempSat.csv
+-rw-rw-rw-   0        0        0      395 2023-06-14 18:52:36.000000 proptables-0.0.8/proptables/water/H2O_superSat.csv
+-rw-rw-rw-   0        0        0       39 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/water/__init__.py
+-rw-rw-rw-   0        0        0        0 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/water/calwatercompressed.py
+-rw-rw-rw-   0        0        0     4550 2023-06-28 13:15:16.000000 proptables-0.0.8/proptables/water/calwatersat.py
+-rw-rw-rw-   0        0        0     4284 2023-06-28 13:13:33.000000 proptables-0.0.8/proptables/water/calwatersuperheat.py
+-rw-rw-rw-   0        0        0      527 2023-06-14 18:52:36.000000 proptables-0.0.8/proptables/water/import_data_water.py
+-rw-rw-rw-   0        0        0     1383 2023-06-14 18:52:36.000000 proptables-0.0.8/proptables/water/main.py
+-rw-rw-rw-   0        0        0      161 2023-06-11 10:30:34.000000 proptables-0.0.8/proptables/water/mainwater.py
+-rw-rw-rw-   0        0        0    10749 2023-06-14 18:52:36.000000 proptables-0.0.8/proptables/water/superheated.py
+-rw-rw-rw-   0        0        0     1262 2023-06-14 18:52:36.000000 proptables-0.0.8/proptables/water/test.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:29:35.688725 proptables-0.0.8/proptables.egg-info/
+-rw-rw-rw-   0        0        0      984 2023-06-28 13:29:35.000000 proptables-0.0.8/proptables.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     1055 2023-06-28 13:29:35.000000 proptables-0.0.8/proptables.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 13:29:35.000000 proptables-0.0.8/proptables.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       11 2023-06-28 13:29:35.000000 proptables-0.0.8/proptables.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      108 2023-06-05 08:01:30.000000 proptables-0.0.8/pyproject.toml
+-rw-rw-rw-   0        0        0      593 2023-06-28 13:29:35.718815 proptables-0.0.8/setup.cfg
```

### Comparing `proptables-0.0.7/LICENCE.txt` & `proptables-0.0.8/LICENCE.txt`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/R134a/R134a_PresSat.csv` & `proptables-0.0.8/proptables/R134a/R134a_PresSat.csv`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/R134a/R134a_Super.csv` & `proptables-0.0.8/proptables/R134a/R134a_Super.csv`

 * *Files 2% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 90,0.4903,306.0,335.4,1.326,,0.2930,305.7,335.0,1.284,,0.2085,305.4,334.6,1.255
 100,0.5041,314.8,345.0,1.352,,0.3014,314.5,344.6,1.310,,0.2145,314.2,344.2,1.282
 ,,,,,,,,,,,,,,
 ,P=0.18 MPa (-12.7 C),,,,,,P=0.20 MPa (-10.1 C),,,,,P=0.24 MPa (-5.4 C),,
   Temp, volume, energy,enthalpy, entropy,, volume, energy,enthalpy, entropy,, volume, energy,enthalpy, entropy
   Deg C,v (m^3/kg),u (kJ/kg),h (kJ/kg),s (kJ/kg.K),,v (m^3/kg),u (kJ/kg),h (kJ/kg),s (kJ/kg.K),,v (m^3/kg),u (kJ/kg),h (kJ/kg),s (kJ/kg.K)
      Sat.,0.1104,223.0,242.9,0.940,,0.0999,224.5,244.5,0.938,,0.0839,227.2,247.3,0.935
--10,0.1119,225.0,245.2,0.948,,,,,,,,,,
+-10,0.1119,225.0,245.2,0.948,,0.09991,224.57,244.56,0.9381,,,,,
 0,0.1172,232.5,253.6,0.980,,0.1048,232.1,253.1,0.970,,0.0862,231.3,252.0,0.952
 10,0.1224,240.0,262.0,1.010,,0.1096,239.7,261.6,1.001,,0.0903,239.0,260.7,0.983
 20,0.1275,247.6,270.6,1.040,,0.1142,247.4,270.2,1.030,,0.0942,246.8,269.4,1.013
 30,0.1325,255.4,279.3,1.069,,0.1187,255.2,278.9,1.060,,0.0981,254.6,278.2,1.043
 40,0.1374,263.3,288.1,1.098,,0.1232,263.1,287.7,1.088,,0.1019,262.6,287.1,1.072
 50,0.1423,271.4,297.0,1.126,,0.1277,271.2,296.7,1.116,,0.1057,270.7,296.1,1.100
 60,0.1472,279.6,306.1,1.153,,0.1321,279.4,305.8,1.144,,0.1094,279.0,305.2,1.128
```

### Comparing `proptables-0.0.7/proptables/R134a/R134a_TempSat.csv` & `proptables-0.0.8/proptables/R134a/R134a_TempSat.csv`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/R134a/calSatData.py` & `proptables-0.0.8/proptables/R134a/calSatData.py`

 * *Files 2% similar despite different names*

```diff
@@ -10,14 +10,15 @@
         self.dfTemperature=self.dfTemperature.iloc[: , :-1]
 
 
     def FindbyTemp(self,Temperature):
         if Temperature in self.dfTemperature["degC"].unique():
             indexing=self.dfTemperature[self.dfTemperature["degC"]==Temperature].index.values
             row=self.dfTemperature.iloc[indexing]
+            row=row.reset_index(drop=True)
             return row
         else:
             nearest=self.dfTemperature["degC"].sub(Temperature).abs().argsort()[:2]
             result=self.dfTemperature.iloc[nearest]
             result=result.copy()
             result.loc[-1,"degC"]=Temperature
             result =result.sort_values(by='degC')
@@ -33,14 +34,15 @@
             
 
 
     def FindbyPressure(self,Pressure):
         if Pressure in self.dfPressure["kPa"].unique():
             indexing=self.dfPressure[self.dfPressure["kPa"]==Pressure].index.values
             row=self.dfPressure.iloc[indexing]
+            row=row.reset_index(drop=True)
             return row
         else:
             nearest=self.dfPressure["kPa"].sub(Pressure).abs().argsort()[:2]
             result=self.dfPressure.iloc[nearest]
             result=result.copy()
             result.loc[-1,"kPa"]=Pressure
             result =result.sort_values(by='kPa')
```

### Comparing `proptables-0.0.7/proptables/R134a/calSuperHeatData.py` & `proptables-0.0.8/proptables/R134a/calSuperHeatData.py`

 * *Files 6% similar despite different names*

```diff
@@ -10,14 +10,15 @@
         return superheatedtable(Pressure)
 
     def findsuperTemp(self,Pressure,Temperature):
         ans=superheatedtable(Pressure)
         if Temperature in ans["Temp"].values:
             indexing=ans[ans["Temp"].values==Temperature].index.values
             row=ans.iloc[indexing]
+            row=row.reset_index(drop=True)
             return row
         else:
             nearest=ans["Temp"].sub(Temperature).abs().argsort()[:2]
             result=ans.iloc[nearest]
             result=result.copy()
             result.loc[-1,"Temp"]=Temperature
             result =result.sort_values(by='Temp')
@@ -32,14 +33,15 @@
             return result
         
     def findsuperEnthalpy(self,Pressure,Enthalpy):
         ans=superheatedtable(Pressure)
         if Enthalpy in ans["enthalpy"].values:
             indexing=ans[ans["enthalpy"].values==Enthalpy].index.values
             row=ans.iloc[indexing]
+            row=row.reset_index(drop=True)
             return row
         else:
             nearest=ans["enthalpy"].sub(Enthalpy).abs().argsort()[:2]
             result=ans.iloc[nearest]
             result=result.copy()
             result.loc[-1,"enthalpy"]=Enthalpy
             result =result.sort_values(by='enthalpy')
@@ -54,14 +56,15 @@
             return result
     
     def findsuperEntropy(self,Pressure,Entropy):
         ans=superheatedtable(Pressure)
         if Entropy in ans["entropy"].values:
             indexing=ans[ans["entropy"].values==Entropy].index.values
             row=ans.iloc[indexing]
+            row=row.reset_index(drop=True)
             return row
         else:
             nearest=ans["entropy"].sub(Entropy).abs().argsort()[:2]
             result=ans.iloc[nearest]
             result=result.copy()
             result.loc[-1,"entropy"]=Entropy
             result =result.sort_values(by='entropy')
@@ -76,14 +79,15 @@
             return result
         
     def findsuperspecificvolume(self,Pressure,specificvolume):
         ans=superheatedtable(Pressure)
         if specificvolume in ans["v"].values:
             indexing=ans[ans["v"].values==specificvolume].index.values
             row=ans.iloc[indexing]
+            row=row.reset_index(drop=True)
             return row
         else:
             nearest=ans["v"].sub(specificvolume).abs().argsort()[:2]
             result=ans.iloc[nearest]
             result=result.copy()
             result.loc[-1,"v"]=specificvolume
             result =result.sort_values(by='v')
```

### Comparing `proptables-0.0.7/proptables/R134a/import_data.py` & `proptables-0.0.8/proptables/R134a/import_data.py`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/R134a/main.py` & `proptables-0.0.8/proptables/R134a/main.py`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/R134a/superheated.py` & `proptables-0.0.8/proptables/R134a/superheated.py`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/R134a/test.py` & `proptables-0.0.8/proptables/R134a/test.py`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/water/H2O_Compressed.csv` & `proptables-0.0.8/proptables/water/H2O_Compressed.csv`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/water/H2O_PresSat.csv` & `proptables-0.0.8/proptables/water/H2O_PresSat.csv`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/water/H2O_Super.csv` & `proptables-0.0.8/proptables/water/H2O_Super.csv`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/water/H2O_TempSat.csv` & `proptables-0.0.8/proptables/water/H2O_TempSat.csv`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/water/calwatersat.py` & `proptables-0.0.8/proptables/water/calwatersat.py`

 * *Files 2% similar despite different names*

```diff
@@ -8,14 +8,15 @@
         self.Presdata=pd.read_csv(data_path_PresSat)
         self.Presdata=self.Presdata.iloc[:,:-1]
 
     def FindbyTemp(self,Temperature):
         if Temperature in self.Tempdata["degC"].unique():
             indexing=self.Tempdata[self.Tempdata["degC"]==Temperature].index.values
             row=self.Tempdata.iloc[indexing]
+            row=row.reset_index(drop=True)
             return row
         else:
             nearest=self.Tempdata["degC"].sub(Temperature).abs().argsort()[:2]
             result=self.Tempdata.iloc[nearest]
             result=result.copy()
             result.loc[-1,"degC"]=Temperature
             result =result.sort_values(by='degC')
@@ -30,14 +31,15 @@
             return result
         
     def FindbyPressure(self,Pressure):
         Pressure=float(Pressure)*0.001
         if Pressure in self.Presdata["MPa"].unique():
             indexing=self.Presdata[self.Presdata["MPa"]==Pressure].index.values
             row=self.Presdata.iloc[indexing]
+            row=row.reset_index(drop=True)
             return row
         else:
             nearest=self.Presdata["MPa"].sub(Pressure).abs().argsort()[:2]
             result=self.Presdata.iloc[nearest]
             result=result.copy()
             result.loc[-1,"MPa"]=Pressure
             result =result.sort_values(by='MPa')
```

### Comparing `proptables-0.0.7/proptables/water/calwatersuperheat.py` & `proptables-0.0.8/proptables/water/calwatersuperheat.py`

 * *Files 3% similar despite different names*

```diff
@@ -9,14 +9,15 @@
         return superheatedtable(Pressure)
 
     def findsuperTemp(self,Pressure,Temperature):
         ans=superheatedtable(Pressure)
         if Temperature in ans["Temp"].values:
             indexing=ans[ans["Temp"].values==Temperature].index.values
             row=ans.iloc[indexing]
+            row=row.reset_index(drop=True)
             return row
         else:
             nearest=ans["Temp"].sub(Temperature).abs().argsort()[:2]
             result=ans.iloc[nearest]
             result=result.copy()
             result.loc[-1,"Temp"]=Temperature
             result =result.sort_values(by='Temp')
@@ -31,14 +32,15 @@
             return result
         
     def findsuperEnthalpy(self,Pressure,Enthalpy):
         ans=superheatedtable(Pressure)
         if Enthalpy in ans["enthalpy"].values:
             indexing=ans[ans["enthalpy"].values==Enthalpy].index.values
             row=ans.iloc[indexing]
+            row=row.reset_index(drop=True)
             return row
         else:
             nearest=ans["enthalpy"].sub(Enthalpy).abs().argsort()[:2]
             result=ans.iloc[nearest]
             result=result.copy()
             result.loc[-1,"enthalpy"]=Enthalpy
             result =result.sort_values(by='enthalpy')
@@ -53,14 +55,15 @@
             return result
     
     def findsuperEntropy(self,Pressure,Entropy):
         ans=superheatedtable(Pressure)
         if Entropy in ans["entropy"].values:
             indexing=ans[ans["entropy"].values==Entropy].index.values
             row=ans.iloc[indexing]
+            row=row.reset_index(drop=True)
             return row
         else:
             nearest=ans["entropy"].sub(Entropy).abs().argsort()[:2]
             result=ans.iloc[nearest]
             result=result.copy()
             result.loc[-1,"entropy"]=Entropy
             result =result.sort_values(by='entropy')
@@ -75,14 +78,15 @@
             return result
         
     def findsuperspecificvolume(self,Pressure,specificvolume):
         ans=superheatedtable(Pressure)
         if specificvolume in ans["v"].values:
             indexing=ans[ans["v"].values==specificvolume].index.values
             row=ans.iloc[indexing]
+            row=row.reset_index(drop=True)
             return row
         else:
             nearest=ans["v"].sub(specificvolume).abs().argsort()[:2]
             result=ans.iloc[nearest]
             result=result.copy()
             result.loc[-1,"v"]=specificvolume
             result =result.sort_values(by='v')
```

### Comparing `proptables-0.0.7/proptables/water/import_data_water.py` & `proptables-0.0.8/proptables/water/import_data_water.py`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/water/main.py` & `proptables-0.0.8/proptables/water/main.py`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/water/superheated.py` & `proptables-0.0.8/proptables/water/superheated.py`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables/water/test.py` & `proptables-0.0.8/proptables/water/test.py`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/proptables.egg-info/SOURCES.txt` & `proptables-0.0.8/proptables.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `proptables-0.0.7/setup.cfg` & `proptables-0.0.8/setup.cfg`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 00000000: 5b6d 6574 6164 6174 615d 0d0a 6e61 6d65  [metadata]..name
 00000010: 203d 2070 726f 7074 6162 6c65 730d 0a76   = proptables..v
-00000020: 6572 7369 6f6e 203d 2030 2e30 2e37 0d0a  ersion = 0.0.7..
+00000020: 6572 7369 6f6e 203d 2030 2e30 2e38 0d0a  ersion = 0.0.8..
 00000030: 6175 7468 6f72 203d 2042 7564 6468 6920  author = Buddhi 
 00000040: 5769 6a65 6e61 7961 6b65 0d0a 6175 7468  Wijenayake..auth
 00000050: 6f72 5f65 6d61 696c 203d 2077 696a 656e  or_email = wijen
 00000060: 6179 616b 6562 7564 6468 6933 3438 3032  ayakebuddhi34802
 00000070: 4067 6d61 696c 2e63 6f6d 0d0a 6465 7363  @gmail.com..desc
 00000080: 7269 7074 696f 6e20 3d20 466f 7220 6765  ription = For ge
 00000090: 6e65 7261 7469 6e67 2070 726f 7065 7274  nerating propert
```

