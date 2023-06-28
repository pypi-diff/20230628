# Comparing `tmp/BODSDataExtractor-1.1.1.tar.gz` & `tmp/BODSDataExtractor-1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "BODSDataExtractor-1.1.1.tar", last modified: Mon Mar 20 16:26:26 2023, max compression
+gzip compressed data, was "BODSDataExtractor-1.2.tar", last modified: Wed Jun 28 13:21:28 2023, max compression
```

## Comparing `BODSDataExtractor-1.1.1.tar` & `BODSDataExtractor-1.2.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxrwxrwx   0        0        0        0 2023-03-20 16:26:26.231473 BODSDataExtractor-1.1.1/
--rw-rw-rw-   0        0        0     1491 2023-02-15 11:08:55.000000 BODSDataExtractor-1.1.1/LICENCE
--rw-rw-rw-   0        0        0      109 2023-02-15 11:08:55.000000 BODSDataExtractor-1.1.1/MANIFEST.in
--rw-rw-rw-   0        0        0    38727 2023-03-20 16:26:26.229402 BODSDataExtractor-1.1.1/PKG-INFO
--rw-rw-rw-   0        0        0    38009 2023-03-20 14:25:45.000000 BODSDataExtractor-1.1.1/README.md
--rw-rw-rw-   0        0        0     1060 2023-03-20 16:25:56.000000 BODSDataExtractor-1.1.1/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-03-20 16:26:26.231473 BODSDataExtractor-1.1.1/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-03-20 16:26:26.148388 BODSDataExtractor-1.1.1/src/
-drwxrwxrwx   0        0        0        0 2023-03-20 16:26:26.186387 BODSDataExtractor-1.1.1/src/BODSDataExtractor/
--rw-rw-rw-   0        0        0     6320 2023-02-15 16:27:59.000000 BODSDataExtractor-1.1.1/src/BODSDataExtractor/ATCO_code_to_LA_lookup.csv
--rw-rw-rw-   0        0        0        2 2023-02-15 11:08:55.000000 BODSDataExtractor-1.1.1/src/BODSDataExtractor/__init__.py
--rw-rw-rw-   0        0        0     3801 2023-03-20 16:25:40.000000 BODSDataExtractor-1.1.1/src/BODSDataExtractor/example.py
--rw-rw-rw-   0        0        0    94235 2023-03-20 14:25:45.000000 BODSDataExtractor-1.1.1/src/BODSDataExtractor/extractor.py
--rw-rw-rw-   0        0        0     2827 2023-03-20 14:25:45.000000 BODSDataExtractor-1.1.1/src/BODSDataExtractor/otc_db_download.py
--rw-rw-rw-   0        0        0      558 2023-03-17 15:02:50.000000 BODSDataExtractor-1.1.1/src/BODSDataExtractor/sb_sandbox.py
-drwxrwxrwx   0        0        0        0 2023-03-20 16:26:26.225428 BODSDataExtractor-1.1.1/src/BODSDataExtractor.egg-info/
--rw-rw-rw-   0        0        0    38727 2023-03-20 16:26:26.000000 BODSDataExtractor-1.1.1/src/BODSDataExtractor.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      496 2023-03-20 16:26:26.000000 BODSDataExtractor-1.1.1/src/BODSDataExtractor.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-03-20 16:26:26.000000 BODSDataExtractor-1.1.1/src/BODSDataExtractor.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      127 2023-03-20 16:26:26.000000 BODSDataExtractor-1.1.1/src/BODSDataExtractor.egg-info/requires.txt
--rw-rw-rw-   0        0        0       18 2023-03-20 16:26:26.000000 BODSDataExtractor-1.1.1/src/BODSDataExtractor.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 13:21:28.325192 BODSDataExtractor-1.2/
+-rw-rw-rw-   0        0        0     1491 2023-02-15 11:08:55.000000 BODSDataExtractor-1.2/LICENCE
+-rw-rw-rw-   0        0        0      109 2023-02-15 11:08:55.000000 BODSDataExtractor-1.2/MANIFEST.in
+-rw-rw-rw-   0        0        0    38390 2023-06-28 13:21:28.322192 BODSDataExtractor-1.2/PKG-INFO
+-rw-rw-rw-   0        0        0    37674 2023-06-28 13:06:10.000000 BODSDataExtractor-1.2/README.md
+-rw-rw-rw-   0        0        0     1058 2023-06-28 13:14:56.000000 BODSDataExtractor-1.2/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 13:21:28.326191 BODSDataExtractor-1.2/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 13:21:28.153473 BODSDataExtractor-1.2/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 13:21:28.257513 BODSDataExtractor-1.2/src/BODSDataExtractor/
+-rw-rw-rw-   0        0        0     6320 2023-02-15 16:27:59.000000 BODSDataExtractor-1.2/src/BODSDataExtractor/ATCO_code_to_LA_lookup.csv
+-rw-rw-rw-   0        0        0        2 2023-02-15 11:08:55.000000 BODSDataExtractor-1.2/src/BODSDataExtractor/__init__.py
+-rw-rw-rw-   0        0        0     4676 2023-06-28 13:06:10.000000 BODSDataExtractor-1.2/src/BODSDataExtractor/classes.py
+-rw-rw-rw-   0        0        0     3807 2023-06-28 13:06:47.000000 BODSDataExtractor-1.2/src/BODSDataExtractor/example.py
+-rw-rw-rw-   0        0        0    93029 2023-06-28 13:06:10.000000 BODSDataExtractor-1.2/src/BODSDataExtractor/extractor.py
+-rw-rw-rw-   0        0        0     2827 2023-03-31 15:04:55.000000 BODSDataExtractor-1.2/src/BODSDataExtractor/otc_db_download.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:21:28.312550 BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/
+-rw-rw-rw-   0        0        0    38390 2023-06-28 13:21:28.000000 BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      493 2023-06-28 13:21:28.000000 BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 13:21:28.000000 BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      127 2023-06-28 13:21:28.000000 BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       18 2023-06-28 13:21:28.000000 BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/top_level.txt
```

### Comparing `BODSDataExtractor-1.1.1/LICENCE` & `BODSDataExtractor-1.2/LICENCE`

 * *Files identical despite different names*

### Comparing `BODSDataExtractor-1.1.1/PKG-INFO` & `BODSDataExtractor-1.2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: BODSDataExtractor
-Version: 1.1.1
+Version: 1.2
 Summary: This project was created to lower the barrier to entry for analysis of UK Bus Open Data. It facilitates the fetching and extraction of clean data, currently focussed on Timetables, into tables to be used for analysis or your own projects.
 Author-email: "Ali Partner, Spencer Brittain" <bodshelpdesk@kpmg.co.uk>
 Project-URL: Homepage, https://github.com/department-for-transport-BODS/bods-data-extractor
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.8
@@ -187,15 +187,15 @@
 #Dataset Level
 TimetableExtractor.metadata
 
 #Service Line Level
 TimetableExtractor.service_line_extract
 
 #Stop Level
-TimetableExtractor.timetable_dict
+TimetableExtractor.stop_level_extract
 ```
 
 ### Example of timetables output
 
 Timetable data can be extracted at 3 levels (note that these examples are restricted to 1 dataset, of ID 322):
 
 * Dataset level - High level overview of key dataset information (each row represents 1 dataset on BODS platform)
@@ -204,15 +204,16 @@
 
 * Service Line Level - Detailed information about each service and line extracted from individual files within datasets (each row represents 1 timetables xml file)
 
 <img width="1400" alt="image" src="https://user-images.githubusercontent.com/81578708/189094457-ee19dc5b-97b8-409c-a75d-04ca4adb5016.png">
 
 * Stop level - Stop level data in the form of a traditional timetable (1 timetable from each xml file)
 
-<img width="1362" alt="image" src="https://user-images.githubusercontent.com/81578708/189094683-ce047d25-051c-470e-be8e-70e6b5d47eab.png">
+![image](https://github.com/department-for-transport-BODS/bods-data-extractor/assets/114913914/fad1be30-01da-4373-8f63-ed11b3994e5e)
+
 
 ### Fundamentals of extracting data using this package
 
 This package is written using object orientated python principles. Put simply, one must initiate an object based upon the subset of BODS timetables data they wish to extract data on, or analyse. Upon initiating an instance of this object, parameters can be specified to select the desired subset. Once this object instance has been initiated, there is no immediate output in the python console. One can now access attributes of the instance by calling them. 
 
 Note that for the data extraction, all of the processing is done in the initiation of the object instance, and not in the accessing of the attributes. This means it make take some time to initiate the object instance, but should take almost no time to access your desired data once the object instance has been initiated.
 
@@ -268,33 +269,31 @@
 my_bus_data_object = TimetableExtractor(api_key=api # Your API Key Here
                                  ,limit=1 # How many datasets to view
                                  ,status = 'published' # Only view published datasets
                                  ,service_line_level=True # True if you require Service line data 
                                  ,stop_level=True # True if you require stop level data
                                  )
 
-#save the extracted stop level data to stop_level variable
-stop_level = my_bus_data_object.timetable_dict
-
-#note that in downloading stop level the  data, the dataset and service line level will also be downloaded. Can access this as below:
-dataset_level = my_bus_data_object.metadata
-service_line_level = my_bus_data_object.service_line_extract
+#save the extracted dataset level data to filtered_dataset_level variable
+filtered_dataset_level = my_bus_data_object.metadata
 
-#save metadata and service line level data to csv file in your downloads directory
+#save the extracted dataset level data to lcoal csv file
 my_bus_data_object.save_metadata_to_csv()
-my_bus_data_object.save_service_line_extract_to_csv()
 
-#stop_level variable is a dictionary of dataframes, which can be saved to csv as follows (saves in downloads directory)
-my_bus_data_object.save_all_timetables_to_csv()
+#save the extracted service line level data to dataset_level variable
+filtered_service_line_level = my_bus_data_object.service_line_extract
+
+#save the extracted service line level data to lcoal csv file
+my_bus_data_object.save_service_line_extract_to_csv()
 
-#or can filter to filter timetable results to a specfic licence number of service code (saves in downloads directory)
-my_bus_data_object.save_filtered_timetables_to_csv('PC0001838:41')
+#stop_level_extract is a dataframe, which contains a collumn of timetables (inbound/outbound) to be saved to csv as follows (saves in project folder)
+my_bus_data_object.save_timetables()
 
 #visualise a particular service line on an interactive map
-my_bus_data_object.visualise_service_line('PC0001838:41')
+#my_bus_data_object.visualise_service_line('PC0001838:41')
 
 ```
 ### Expected run times and performance
 
 The volume of timetables data available on the BODS platform is very significant, and while this package simplifies the extraction of this data, and processes it into a analytical ready form, the sheer amount of data dictates that it can take a non trivial amount of time to initiate the above object instances. 
 
 One way of getting around this problem is to narrow your requested data request using additional parameters. Another is to run the download once, and save the output to disk as a csv, to allow re loading of this at a later data for reporting analysis. Both of these approaches are outlined in more detail in below sections.
@@ -314,14 +313,15 @@
 
 As well as specifying the granularity of data to extract (dataset, service line or stop level), limiting the number of datasets, and restricting to just published datasets, there are a number of additional parameters that the object instance can be initiated with. These are as follows:
 
 - nocs - _accepts list input of valid National Operator Codes e.g. ['HIPK', 'YCST']_
 - search -  _accepts string input of key-words to filter for the data set name, data set description, organisation name, or admin name e.g. 'Arriva'_
 - bods_compliant - _accepts boolean input (True or False), where True filters for only BODS Compliant datasets. Default value is True_
 - atco_code - _accepts list input of the first three characters of ATCO codes (ATCO codes are unique identifiers of UK bus stops, where first three characters signify the admin area they are within). This filters datasets and/or service lines that have stops within the specified admin areas. e.g. ['320','450']_
+- limit - _accepts an integer value which specifies the amount of datasets will be downloaded. For example, if there were 5 datasets present and the limit was set to 5, all datasets would be downloaded. Comparitively, if the limit was set to 1 , only 1 dataset of the 5 will be downloaded._
 
 Example of this:
 ```python
 #intiate an object instance called my_bus_data_object with desired parameters
 from BODSDataExtractor.extractor import TimetableExtractor
 
 my_bus_data_object = TimetableExtractor(api_key=api # Your API Key Here
@@ -451,17 +451,14 @@
 ## Roadmap & Limitations
 
 As the first release of this project, the focus was on getting analytical ready timetable data in the hands of consumers. As a result, there are a number of limitations to bear in mind when using this package. These aim to be addressed in subsequent releases. 
 
 #### Handling non standard files
 Whilst all BODS compliant files meet a certain set of standards, there is still variation in exactly how timetables xml files can be populated. This pacakge currently handles files that meet the most common structure, and a number of notable exceptions, however there are some files that stop level timetables will not be generated for. It will, however, generate dataset level and service line level data for all published files. Future releases will aim to close this gap so timetables can be generated for most, if not all files.
 
-#### Handling vehicle journeys that cross midnight
-As the PTI standards dictate, sequence number logic is different for services that have stop times which cross midnight. This currently results in the stop level timetable output having vehicle journeys that do not start at sequence number 1. Future releases will include logic that better handles this to provide a more uniform output for such vehicle journeys.
-
 #### Providing additional detail about services
 Future releases will extract additional data from timetables xml files in order to provide further detail on services; for example details regarding the days of operation and exceptions around bank holidays, as well as more detailed route information including distance between stops, in addition to time.
 
 #### Incorporating AVL and Fares data
 The BODS platform also provides live vehicle location data (AVL), as well as Fares data. Future releases will aim to incorporate functionality for downloading and analysis AVL data initially, and subsequently Fares data once this has been validated. 
 
 #### Optimising performance
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: BODSDataExtractor Version: 1.1.1 Summary: This
+Metadata-Version: 2.1 Name: BODSDataExtractor Version: 1.2 Summary: This
 project was created to lower the barrier to entry for analysis of UK Bus Open
 Data. It facilitates the fetching and extraction of clean data, currently
 focussed on Timetables, into tables to be used for analysis or your own
 projects. Author-email: "Ali Partner, Spencer Brittain"
 kpmg.co.uk> Project-URL: Homepage, https://github.com/department-for-transport-
 BODS/bods-data-extractor Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License Classifier: Operating System
@@ -139,42 +139,43 @@
 section. The code examples are ready to copy and paste into your .py file.
                                                                   (back_to_top)
  ## Usage ### Quick Reference The below code acts as a quick reference guide to
 calling the attributes of a TimetableExtractor object at each level as
 explained below in this document. ```python #Dataset Level
 TimetableExtractor.metadata #Service Line Level
 TimetableExtractor.service_line_extract #Stop Level
-TimetableExtractor.timetable_dict ``` ### Example of timetables output
+TimetableExtractor.stop_level_extract ``` ### Example of timetables output
 Timetable data can be extracted at 3 levels (note that these examples are
 restricted to 1 dataset, of ID 322): * Dataset level - High level overview of
 key dataset information (each row represents 1 dataset on BODS platform)
 [image] * Service Line Level - Detailed information about each service and line
 extracted from individual files within datasets (each row represents 1
 timetables xml file) [image] * Stop level - Stop level data in the form of a
-traditional timetable (1 timetable from each xml file) [image] ### Fundamentals
-of extracting data using this package This package is written using object
-orientated python principles. Put simply, one must initiate an object based
-upon the subset of BODS timetables data they wish to extract data on, or
-analyse. Upon initiating an instance of this object, parameters can be
-specified to select the desired subset. Once this object instance has been
-initiated, there is no immediate output in the python console. One can now
-access attributes of the instance by calling them. Note that for the data
-extraction, all of the processing is done in the initiation of the object
-instance, and not in the accessing of the attributes. This means it make take
-some time to initiate the object instance, but should take almost no time to
-access your desired data once the object instance has been initiated. The
-examples below should bring this to life. ### How to extract Dataset Level data
-```python #intiate an object instance called my_bus_data_object with desired
-parameters from BODSDataExtractor.extractor import TimetableExtractor
-my_bus_data_object = TimetableExtractor(api_key=api # Your API Key Here
-,limit=1 # How many datasets to view ,status = 'published' # Only view
-published datasets ,service_line_level=False # True if you require Service line
-data ,stop_level=False # True if you require stop level data ) #save the
-extracted dataset level data to dataset_level variable dataset_level =
-my_bus_data_object.metadata #save this data to a csv file in your downloads
+traditional timetable (1 timetable from each xml file) ![image](https://
+github.com/department-for-transport-BODS/bods-data-extractor/assets/114913914/
+fad1be30-01da-4373-8f63-ed11b3994e5e) ### Fundamentals of extracting data using
+this package This package is written using object orientated python principles.
+Put simply, one must initiate an object based upon the subset of BODS
+timetables data they wish to extract data on, or analyse. Upon initiating an
+instance of this object, parameters can be specified to select the desired
+subset. Once this object instance has been initiated, there is no immediate
+output in the python console. One can now access attributes of the instance by
+calling them. Note that for the data extraction, all of the processing is done
+in the initiation of the object instance, and not in the accessing of the
+attributes. This means it make take some time to initiate the object instance,
+but should take almost no time to access your desired data once the object
+instance has been initiated. The examples below should bring this to life. ###
+How to extract Dataset Level data ```python #intiate an object instance called
+my_bus_data_object with desired parameters from BODSDataExtractor.extractor
+import TimetableExtractor my_bus_data_object = TimetableExtractor(api_key=api #
+Your API Key Here ,limit=1 # How many datasets to view ,status = 'published' #
+Only view published datasets ,service_line_level=False # True if you require
+Service line data ,stop_level=False # True if you require stop level data )
+#save the extracted dataset level data to dataset_level variable dataset_level
+= my_bus_data_object.metadata #save this data to a csv file in your downloads
 directory #note that entries in the 'localities' field may be truncated to
 comply with excel cell limits my_bus_data_object.save_metadata_to_csv() ``` ###
 How to extract Service Line Level data ```python #intiate an object instance
 called my_bus_data_object with desired parameters from
 BODSDataExtractor.extractor import TimetableExtractor my_bus_data_object =
 TimetableExtractor(api_key=api # Your API Key Here ,limit=1 # How many datasets
 to view ,status = 'published' # Only view published datasets
@@ -188,76 +189,76 @@
 my_bus_data_object.save_service_line_extract_to_csv() ``` ### How to extract
 Stop Level data ```python #intiate an object instance called my_bus_data_object
 with desired parameters from BODSDataExtractor.extractor import
 TimetableExtractor my_bus_data_object = TimetableExtractor(api_key=api # Your
 API Key Here ,limit=1 # How many datasets to view ,status = 'published' # Only
 view published datasets ,service_line_level=True # True if you require Service
 line data ,stop_level=True # True if you require stop level data ) #save the
-extracted stop level data to stop_level variable stop_level =
-my_bus_data_object.timetable_dict #note that in downloading stop level the
-data, the dataset and service line level will also be downloaded. Can access
-this as below: dataset_level = my_bus_data_object.metadata service_line_level =
-my_bus_data_object.service_line_extract #save metadata and service line level
-data to csv file in your downloads directory
-my_bus_data_object.save_metadata_to_csv()
-my_bus_data_object.save_service_line_extract_to_csv() #stop_level variable is a
-dictionary of dataframes, which can be saved to csv as follows (saves in
-downloads directory) my_bus_data_object.save_all_timetables_to_csv() #or can
-filter to filter timetable results to a specfic licence number of service code
-(saves in downloads directory)
-my_bus_data_object.save_filtered_timetables_to_csv('PC0001838:41') #visualise a
-particular service line on an interactive map
-my_bus_data_object.visualise_service_line('PC0001838:41') ``` ### Expected run
-times and performance The volume of timetables data available on the BODS
-platform is very significant, and while this package simplifies the extraction
-of this data, and processes it into a analytical ready form, the sheer amount
-of data dictates that it can take a non trivial amount of time to initiate the
-above object instances. One way of getting around this problem is to narrow
-your requested data request using additional parameters. Another is to run the
-download once, and save the output to disk as a csv, to allow re loading of
-this at a later data for reporting analysis. Both of these approaches are
-outlined in more detail in below sections. Directly below are some sample
-expected run times for extracting data using this package. This should still
-give you a very approximate idea of how long to expect your code to execute,
-depending on how much data you are trying to extract. It is important to note
-that this can vary depending on your local processing power, internet
-connection and on the nature of the datasets you are extracting (a dataset may
-contain one xml file, or several hundred). | Granularity of data extraction | 1
-dataset timing | 20 dataset timing | 200 datasets timing | | ------------------
---------------- |------------------|-------------------|-----------------------
----| | Dataset | < 0 hrs 1 min | < 0 hrs 1 min | 0 hrs 2 min | | Service line |
-< 0 hrs 1 min | < 0 hrs 1 min | 0 hrs 6 min | | Stop | 0 hrs 3 min | < 0 hrs 6
-min | Memory issues @ 16Gb RAM | ### How to fine tune your results using
-additional parameters As well as specifying the granularity of data to extract
-(dataset, service line or stop level), limiting the number of datasets, and
-restricting to just published datasets, there are a number of additional
-parameters that the object instance can be initiated with. These are as
-follows: - nocs - _accepts list input of valid National Operator Codes e.g.
+extracted dataset level data to filtered_dataset_level variable
+filtered_dataset_level = my_bus_data_object.metadata #save the extracted
+dataset level data to lcoal csv file my_bus_data_object.save_metadata_to_csv()
+#save the extracted service line level data to dataset_level variable
+filtered_service_line_level = my_bus_data_object.service_line_extract #save the
+extracted service line level data to lcoal csv file
+my_bus_data_object.save_service_line_extract_to_csv() #stop_level_extract is a
+dataframe, which contains a collumn of timetables (inbound/outbound) to be
+saved to csv as follows (saves in project folder)
+my_bus_data_object.save_timetables() #visualise a particular service line on an
+interactive map #my_bus_data_object.visualise_service_line('PC0001838:41') ```
+### Expected run times and performance The volume of timetables data available
+on the BODS platform is very significant, and while this package simplifies the
+extraction of this data, and processes it into a analytical ready form, the
+sheer amount of data dictates that it can take a non trivial amount of time to
+initiate the above object instances. One way of getting around this problem is
+to narrow your requested data request using additional parameters. Another is
+to run the download once, and save the output to disk as a csv, to allow re
+loading of this at a later data for reporting analysis. Both of these
+approaches are outlined in more detail in below sections. Directly below are
+some sample expected run times for extracting data using this package. This
+should still give you a very approximate idea of how long to expect your code
+to execute, depending on how much data you are trying to extract. It is
+important to note that this can vary depending on your local processing power,
+internet connection and on the nature of the datasets you are extracting (a
+dataset may contain one xml file, or several hundred). | Granularity of data
+extraction | 1 dataset timing | 20 dataset timing | 200 datasets timing | | ---
+------------------------------ |------------------|-------------------|--------
+------------------| | Dataset | < 0 hrs 1 min | < 0 hrs 1 min | 0 hrs 2 min | |
+Service line | < 0 hrs 1 min | < 0 hrs 1 min | 0 hrs 6 min | | Stop | 0 hrs 3
+min | < 0 hrs 6 min | Memory issues @ 16Gb RAM | ### How to fine tune your
+results using additional parameters As well as specifying the granularity of
+data to extract (dataset, service line or stop level), limiting the number of
+datasets, and restricting to just published datasets, there are a number of
+additional parameters that the object instance can be initiated with. These are
+as follows: - nocs - _accepts list input of valid National Operator Codes e.g.
 ['HIPK', 'YCST']_ - search - _accepts string input of key-words to filter for
 the data set name, data set description, organisation name, or admin name e.g.
 'Arriva'_ - bods_compliant - _accepts boolean input (True or False), where True
 filters for only BODS Compliant datasets. Default value is True_ - atco_code -
 _accepts list input of the first three characters of ATCO codes (ATCO codes are
 unique identifiers of UK bus stops, where first three characters signify the
 admin area they are within). This filters datasets and/or service lines that
-have stops within the specified admin areas. e.g. ['320','450']_ Example of
-this: ```python #intiate an object instance called my_bus_data_object with
-desired parameters from BODSDataExtractor.extractor import TimetableExtractor
-my_bus_data_object = TimetableExtractor(api_key=api # Your API Key Here
-#,limit=1 # commented out limit so will return all results within other
-parameters ,status = 'published' ,service_line_level=True ,stop_level=False
-,nocs=['FSCE','FGLA','FCYM'] #values must be entered in this list format - each
-noc within quotes, separated by comma, all within [] ,search='First Bus' # this
-is actually redundant as nocs are specific to this operator, but included for
-demo purpose ,bods_compliant=True ,atco_code=['320', '450'] # filter to stops
-within just north and west yorkshire. Values must be entered in this list
-format - each code within quotes, separated by comma, all within [] ) #save the
-extracted dataset level data to filtered_dataset_level variable
-filtered_dataset_level = my_bus_data_object.metadata #save the extracted
-service line level data to dataset_level variable filtered_service_line_level =
+have stops within the specified admin areas. e.g. ['320','450']_ - limit -
+_accepts an integer value which specifies the amount of datasets will be
+downloaded. For example, if there were 5 datasets present and the limit was set
+to 5, all datasets would be downloaded. Comparitively, if the limit was set to
+1 , only 1 dataset of the 5 will be downloaded._ Example of this: ```python
+#intiate an object instance called my_bus_data_object with desired parameters
+from BODSDataExtractor.extractor import TimetableExtractor my_bus_data_object =
+TimetableExtractor(api_key=api # Your API Key Here #,limit=1 # commented out
+limit so will return all results within other parameters ,status = 'published'
+,service_line_level=True ,stop_level=False ,nocs=['FSCE','FGLA','FCYM'] #values
+must be entered in this list format - each noc within quotes, separated by
+comma, all within [] ,search='First Bus' # this is actually redundant as nocs
+are specific to this operator, but included for demo purpose
+,bods_compliant=True ,atco_code=['320', '450'] # filter to stops within just
+north and west yorkshire. Values must be entered in this list format - each
+code within quotes, separated by comma, all within [] ) #save the extracted
+dataset level data to filtered_dataset_level variable filtered_dataset_level =
+my_bus_data_object.metadata #save the extracted service line level data to
+dataset_level variable filtered_service_line_level =
 my_bus_data_object.service_line_extract #export to csv if you wish to save this
 data filtered_service_line_level.to_csv
 ('filtered_service_line_level_export.csv') ``` ### ATCO Code to Local Authority
 Lookup Table The package contains an unofficial lookup table used to map bus
 stop ATCO codes to Local Authorities. This may be useful as a rough guide to
 filtering services around a certain area of England. Please note that this is
 not an official definition of ATCO / LA mappings and has been manually created.
@@ -360,36 +361,31 @@
 standard files Whilst all BODS compliant files meet a certain set of standards,
 there is still variation in exactly how timetables xml files can be populated.
 This pacakge currently handles files that meet the most common structure, and a
 number of notable exceptions, however there are some files that stop level
 timetables will not be generated for. It will, however, generate dataset level
 and service line level data for all published files. Future releases will aim
 to close this gap so timetables can be generated for most, if not all files.
-#### Handling vehicle journeys that cross midnight As the PTI standards
-dictate, sequence number logic is different for services that have stop times
-which cross midnight. This currently results in the stop level timetable output
-having vehicle journeys that do not start at sequence number 1. Future releases
-will include logic that better handles this to provide a more uniform output
-for such vehicle journeys. #### Providing additional detail about services
-Future releases will extract additional data from timetables xml files in order
-to provide further detail on services; for example details regarding the days
-of operation and exceptions around bank holidays, as well as more detailed
-route information including distance between stops, in addition to time. ####
-Incorporating AVL and Fares data The BODS platform also provides live vehicle
-location data (AVL), as well as Fares data. Future releases will aim to
-incorporate functionality for downloading and analysis AVL data initially, and
-subsequently Fares data once this has been validated. #### Optimising
-performance Generating stop level timetables requires downloading and parsing a
-significant volume of data. It therefore takes quite some time to run the code.
-Future releases will aim to reduce execution time through optimisations. ####
-And more! This project has consumers of BODS data at its heart, and so if any
-other features would be valuable, or any bugs are noticed please get in touch.
-Details of how to do this can be found in the 'Contributing' section below. See
-the [open issues](https://github.com/KPMG-UK/bods_pseudo_test/issues) for a
-full list of proposed features (and known issues).
+#### Providing additional detail about services Future releases will extract
+additional data from timetables xml files in order to provide further detail on
+services; for example details regarding the days of operation and exceptions
+around bank holidays, as well as more detailed route information including
+distance between stops, in addition to time. #### Incorporating AVL and Fares
+data The BODS platform also provides live vehicle location data (AVL), as well
+as Fares data. Future releases will aim to incorporate functionality for
+downloading and analysis AVL data initially, and subsequently Fares data once
+this has been validated. #### Optimising performance Generating stop level
+timetables requires downloading and parsing a significant volume of data. It
+therefore takes quite some time to run the code. Future releases will aim to
+reduce execution time through optimisations. #### And more! This project has
+consumers of BODS data at its heart, and so if any other features would be
+valuable, or any bugs are noticed please get in touch. Details of how to do
+this can be found in the 'Contributing' section below. See the [open issues]
+(https://github.com/KPMG-UK/bods_pseudo_test/issues) for a full list of
+proposed features (and known issues).
                                                                   (back_to_top)
  ## Contribute / Contact ### Contribute to this project Contributions are what
 make the open source community such an amazing place to learn, inspire, and
 create. Any contributions you make are **greatly appreciated**. If you want to
 suggest an new or improved feature, open an issue with the tag "enhancement".
 If you want to develop a new or improved feature yourself, fork the repo,
 develop within a new branch, then create a pull request back to this repo. We
```

### Comparing `BODSDataExtractor-1.1.1/README.md` & `BODSDataExtractor-1.2/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -174,15 +174,15 @@
 #Dataset Level
 TimetableExtractor.metadata
 
 #Service Line Level
 TimetableExtractor.service_line_extract
 
 #Stop Level
-TimetableExtractor.timetable_dict
+TimetableExtractor.stop_level_extract
 ```
 
 ### Example of timetables output
 
 Timetable data can be extracted at 3 levels (note that these examples are restricted to 1 dataset, of ID 322):
 
 * Dataset level - High level overview of key dataset information (each row represents 1 dataset on BODS platform)
@@ -191,15 +191,16 @@
 
 * Service Line Level - Detailed information about each service and line extracted from individual files within datasets (each row represents 1 timetables xml file)
 
 <img width="1400" alt="image" src="https://user-images.githubusercontent.com/81578708/189094457-ee19dc5b-97b8-409c-a75d-04ca4adb5016.png">
 
 * Stop level - Stop level data in the form of a traditional timetable (1 timetable from each xml file)
 
-<img width="1362" alt="image" src="https://user-images.githubusercontent.com/81578708/189094683-ce047d25-051c-470e-be8e-70e6b5d47eab.png">
+![image](https://github.com/department-for-transport-BODS/bods-data-extractor/assets/114913914/fad1be30-01da-4373-8f63-ed11b3994e5e)
+
 
 ### Fundamentals of extracting data using this package
 
 This package is written using object orientated python principles. Put simply, one must initiate an object based upon the subset of BODS timetables data they wish to extract data on, or analyse. Upon initiating an instance of this object, parameters can be specified to select the desired subset. Once this object instance has been initiated, there is no immediate output in the python console. One can now access attributes of the instance by calling them. 
 
 Note that for the data extraction, all of the processing is done in the initiation of the object instance, and not in the accessing of the attributes. This means it make take some time to initiate the object instance, but should take almost no time to access your desired data once the object instance has been initiated.
 
@@ -255,33 +256,31 @@
 my_bus_data_object = TimetableExtractor(api_key=api # Your API Key Here
                                  ,limit=1 # How many datasets to view
                                  ,status = 'published' # Only view published datasets
                                  ,service_line_level=True # True if you require Service line data 
                                  ,stop_level=True # True if you require stop level data
                                  )
 
-#save the extracted stop level data to stop_level variable
-stop_level = my_bus_data_object.timetable_dict
-
-#note that in downloading stop level the  data, the dataset and service line level will also be downloaded. Can access this as below:
-dataset_level = my_bus_data_object.metadata
-service_line_level = my_bus_data_object.service_line_extract
+#save the extracted dataset level data to filtered_dataset_level variable
+filtered_dataset_level = my_bus_data_object.metadata
 
-#save metadata and service line level data to csv file in your downloads directory
+#save the extracted dataset level data to lcoal csv file
 my_bus_data_object.save_metadata_to_csv()
-my_bus_data_object.save_service_line_extract_to_csv()
 
-#stop_level variable is a dictionary of dataframes, which can be saved to csv as follows (saves in downloads directory)
-my_bus_data_object.save_all_timetables_to_csv()
+#save the extracted service line level data to dataset_level variable
+filtered_service_line_level = my_bus_data_object.service_line_extract
+
+#save the extracted service line level data to lcoal csv file
+my_bus_data_object.save_service_line_extract_to_csv()
 
-#or can filter to filter timetable results to a specfic licence number of service code (saves in downloads directory)
-my_bus_data_object.save_filtered_timetables_to_csv('PC0001838:41')
+#stop_level_extract is a dataframe, which contains a collumn of timetables (inbound/outbound) to be saved to csv as follows (saves in project folder)
+my_bus_data_object.save_timetables()
 
 #visualise a particular service line on an interactive map
-my_bus_data_object.visualise_service_line('PC0001838:41')
+#my_bus_data_object.visualise_service_line('PC0001838:41')
 
 ```
 ### Expected run times and performance
 
 The volume of timetables data available on the BODS platform is very significant, and while this package simplifies the extraction of this data, and processes it into a analytical ready form, the sheer amount of data dictates that it can take a non trivial amount of time to initiate the above object instances. 
 
 One way of getting around this problem is to narrow your requested data request using additional parameters. Another is to run the download once, and save the output to disk as a csv, to allow re loading of this at a later data for reporting analysis. Both of these approaches are outlined in more detail in below sections.
@@ -301,14 +300,15 @@
 
 As well as specifying the granularity of data to extract (dataset, service line or stop level), limiting the number of datasets, and restricting to just published datasets, there are a number of additional parameters that the object instance can be initiated with. These are as follows:
 
 - nocs - _accepts list input of valid National Operator Codes e.g. ['HIPK', 'YCST']_
 - search -  _accepts string input of key-words to filter for the data set name, data set description, organisation name, or admin name e.g. 'Arriva'_
 - bods_compliant - _accepts boolean input (True or False), where True filters for only BODS Compliant datasets. Default value is True_
 - atco_code - _accepts list input of the first three characters of ATCO codes (ATCO codes are unique identifiers of UK bus stops, where first three characters signify the admin area they are within). This filters datasets and/or service lines that have stops within the specified admin areas. e.g. ['320','450']_
+- limit - _accepts an integer value which specifies the amount of datasets will be downloaded. For example, if there were 5 datasets present and the limit was set to 5, all datasets would be downloaded. Comparitively, if the limit was set to 1 , only 1 dataset of the 5 will be downloaded._
 
 Example of this:
 ```python
 #intiate an object instance called my_bus_data_object with desired parameters
 from BODSDataExtractor.extractor import TimetableExtractor
 
 my_bus_data_object = TimetableExtractor(api_key=api # Your API Key Here
@@ -438,17 +438,14 @@
 ## Roadmap & Limitations
 
 As the first release of this project, the focus was on getting analytical ready timetable data in the hands of consumers. As a result, there are a number of limitations to bear in mind when using this package. These aim to be addressed in subsequent releases. 
 
 #### Handling non standard files
 Whilst all BODS compliant files meet a certain set of standards, there is still variation in exactly how timetables xml files can be populated. This pacakge currently handles files that meet the most common structure, and a number of notable exceptions, however there are some files that stop level timetables will not be generated for. It will, however, generate dataset level and service line level data for all published files. Future releases will aim to close this gap so timetables can be generated for most, if not all files.
 
-#### Handling vehicle journeys that cross midnight
-As the PTI standards dictate, sequence number logic is different for services that have stop times which cross midnight. This currently results in the stop level timetable output having vehicle journeys that do not start at sequence number 1. Future releases will include logic that better handles this to provide a more uniform output for such vehicle journeys.
-
 #### Providing additional detail about services
 Future releases will extract additional data from timetables xml files in order to provide further detail on services; for example details regarding the days of operation and exceptions around bank holidays, as well as more detailed route information including distance between stops, in addition to time.
 
 #### Incorporating AVL and Fares data
 The BODS platform also provides live vehicle location data (AVL), as well as Fares data. Future releases will aim to incorporate functionality for downloading and analysis AVL data initially, and subsequently Fares data once this has been validated. 
 
 #### Optimising performance
```

#### html2text {}

```diff
@@ -130,42 +130,43 @@
 section. The code examples are ready to copy and paste into your .py file.
                                                                   (back_to_top)
  ## Usage ### Quick Reference The below code acts as a quick reference guide to
 calling the attributes of a TimetableExtractor object at each level as
 explained below in this document. ```python #Dataset Level
 TimetableExtractor.metadata #Service Line Level
 TimetableExtractor.service_line_extract #Stop Level
-TimetableExtractor.timetable_dict ``` ### Example of timetables output
+TimetableExtractor.stop_level_extract ``` ### Example of timetables output
 Timetable data can be extracted at 3 levels (note that these examples are
 restricted to 1 dataset, of ID 322): * Dataset level - High level overview of
 key dataset information (each row represents 1 dataset on BODS platform)
 [image] * Service Line Level - Detailed information about each service and line
 extracted from individual files within datasets (each row represents 1
 timetables xml file) [image] * Stop level - Stop level data in the form of a
-traditional timetable (1 timetable from each xml file) [image] ### Fundamentals
-of extracting data using this package This package is written using object
-orientated python principles. Put simply, one must initiate an object based
-upon the subset of BODS timetables data they wish to extract data on, or
-analyse. Upon initiating an instance of this object, parameters can be
-specified to select the desired subset. Once this object instance has been
-initiated, there is no immediate output in the python console. One can now
-access attributes of the instance by calling them. Note that for the data
-extraction, all of the processing is done in the initiation of the object
-instance, and not in the accessing of the attributes. This means it make take
-some time to initiate the object instance, but should take almost no time to
-access your desired data once the object instance has been initiated. The
-examples below should bring this to life. ### How to extract Dataset Level data
-```python #intiate an object instance called my_bus_data_object with desired
-parameters from BODSDataExtractor.extractor import TimetableExtractor
-my_bus_data_object = TimetableExtractor(api_key=api # Your API Key Here
-,limit=1 # How many datasets to view ,status = 'published' # Only view
-published datasets ,service_line_level=False # True if you require Service line
-data ,stop_level=False # True if you require stop level data ) #save the
-extracted dataset level data to dataset_level variable dataset_level =
-my_bus_data_object.metadata #save this data to a csv file in your downloads
+traditional timetable (1 timetable from each xml file) ![image](https://
+github.com/department-for-transport-BODS/bods-data-extractor/assets/114913914/
+fad1be30-01da-4373-8f63-ed11b3994e5e) ### Fundamentals of extracting data using
+this package This package is written using object orientated python principles.
+Put simply, one must initiate an object based upon the subset of BODS
+timetables data they wish to extract data on, or analyse. Upon initiating an
+instance of this object, parameters can be specified to select the desired
+subset. Once this object instance has been initiated, there is no immediate
+output in the python console. One can now access attributes of the instance by
+calling them. Note that for the data extraction, all of the processing is done
+in the initiation of the object instance, and not in the accessing of the
+attributes. This means it make take some time to initiate the object instance,
+but should take almost no time to access your desired data once the object
+instance has been initiated. The examples below should bring this to life. ###
+How to extract Dataset Level data ```python #intiate an object instance called
+my_bus_data_object with desired parameters from BODSDataExtractor.extractor
+import TimetableExtractor my_bus_data_object = TimetableExtractor(api_key=api #
+Your API Key Here ,limit=1 # How many datasets to view ,status = 'published' #
+Only view published datasets ,service_line_level=False # True if you require
+Service line data ,stop_level=False # True if you require stop level data )
+#save the extracted dataset level data to dataset_level variable dataset_level
+= my_bus_data_object.metadata #save this data to a csv file in your downloads
 directory #note that entries in the 'localities' field may be truncated to
 comply with excel cell limits my_bus_data_object.save_metadata_to_csv() ``` ###
 How to extract Service Line Level data ```python #intiate an object instance
 called my_bus_data_object with desired parameters from
 BODSDataExtractor.extractor import TimetableExtractor my_bus_data_object =
 TimetableExtractor(api_key=api # Your API Key Here ,limit=1 # How many datasets
 to view ,status = 'published' # Only view published datasets
@@ -179,76 +180,76 @@
 my_bus_data_object.save_service_line_extract_to_csv() ``` ### How to extract
 Stop Level data ```python #intiate an object instance called my_bus_data_object
 with desired parameters from BODSDataExtractor.extractor import
 TimetableExtractor my_bus_data_object = TimetableExtractor(api_key=api # Your
 API Key Here ,limit=1 # How many datasets to view ,status = 'published' # Only
 view published datasets ,service_line_level=True # True if you require Service
 line data ,stop_level=True # True if you require stop level data ) #save the
-extracted stop level data to stop_level variable stop_level =
-my_bus_data_object.timetable_dict #note that in downloading stop level the
-data, the dataset and service line level will also be downloaded. Can access
-this as below: dataset_level = my_bus_data_object.metadata service_line_level =
-my_bus_data_object.service_line_extract #save metadata and service line level
-data to csv file in your downloads directory
-my_bus_data_object.save_metadata_to_csv()
-my_bus_data_object.save_service_line_extract_to_csv() #stop_level variable is a
-dictionary of dataframes, which can be saved to csv as follows (saves in
-downloads directory) my_bus_data_object.save_all_timetables_to_csv() #or can
-filter to filter timetable results to a specfic licence number of service code
-(saves in downloads directory)
-my_bus_data_object.save_filtered_timetables_to_csv('PC0001838:41') #visualise a
-particular service line on an interactive map
-my_bus_data_object.visualise_service_line('PC0001838:41') ``` ### Expected run
-times and performance The volume of timetables data available on the BODS
-platform is very significant, and while this package simplifies the extraction
-of this data, and processes it into a analytical ready form, the sheer amount
-of data dictates that it can take a non trivial amount of time to initiate the
-above object instances. One way of getting around this problem is to narrow
-your requested data request using additional parameters. Another is to run the
-download once, and save the output to disk as a csv, to allow re loading of
-this at a later data for reporting analysis. Both of these approaches are
-outlined in more detail in below sections. Directly below are some sample
-expected run times for extracting data using this package. This should still
-give you a very approximate idea of how long to expect your code to execute,
-depending on how much data you are trying to extract. It is important to note
-that this can vary depending on your local processing power, internet
-connection and on the nature of the datasets you are extracting (a dataset may
-contain one xml file, or several hundred). | Granularity of data extraction | 1
-dataset timing | 20 dataset timing | 200 datasets timing | | ------------------
---------------- |------------------|-------------------|-----------------------
----| | Dataset | < 0 hrs 1 min | < 0 hrs 1 min | 0 hrs 2 min | | Service line |
-< 0 hrs 1 min | < 0 hrs 1 min | 0 hrs 6 min | | Stop | 0 hrs 3 min | < 0 hrs 6
-min | Memory issues @ 16Gb RAM | ### How to fine tune your results using
-additional parameters As well as specifying the granularity of data to extract
-(dataset, service line or stop level), limiting the number of datasets, and
-restricting to just published datasets, there are a number of additional
-parameters that the object instance can be initiated with. These are as
-follows: - nocs - _accepts list input of valid National Operator Codes e.g.
+extracted dataset level data to filtered_dataset_level variable
+filtered_dataset_level = my_bus_data_object.metadata #save the extracted
+dataset level data to lcoal csv file my_bus_data_object.save_metadata_to_csv()
+#save the extracted service line level data to dataset_level variable
+filtered_service_line_level = my_bus_data_object.service_line_extract #save the
+extracted service line level data to lcoal csv file
+my_bus_data_object.save_service_line_extract_to_csv() #stop_level_extract is a
+dataframe, which contains a collumn of timetables (inbound/outbound) to be
+saved to csv as follows (saves in project folder)
+my_bus_data_object.save_timetables() #visualise a particular service line on an
+interactive map #my_bus_data_object.visualise_service_line('PC0001838:41') ```
+### Expected run times and performance The volume of timetables data available
+on the BODS platform is very significant, and while this package simplifies the
+extraction of this data, and processes it into a analytical ready form, the
+sheer amount of data dictates that it can take a non trivial amount of time to
+initiate the above object instances. One way of getting around this problem is
+to narrow your requested data request using additional parameters. Another is
+to run the download once, and save the output to disk as a csv, to allow re
+loading of this at a later data for reporting analysis. Both of these
+approaches are outlined in more detail in below sections. Directly below are
+some sample expected run times for extracting data using this package. This
+should still give you a very approximate idea of how long to expect your code
+to execute, depending on how much data you are trying to extract. It is
+important to note that this can vary depending on your local processing power,
+internet connection and on the nature of the datasets you are extracting (a
+dataset may contain one xml file, or several hundred). | Granularity of data
+extraction | 1 dataset timing | 20 dataset timing | 200 datasets timing | | ---
+------------------------------ |------------------|-------------------|--------
+------------------| | Dataset | < 0 hrs 1 min | < 0 hrs 1 min | 0 hrs 2 min | |
+Service line | < 0 hrs 1 min | < 0 hrs 1 min | 0 hrs 6 min | | Stop | 0 hrs 3
+min | < 0 hrs 6 min | Memory issues @ 16Gb RAM | ### How to fine tune your
+results using additional parameters As well as specifying the granularity of
+data to extract (dataset, service line or stop level), limiting the number of
+datasets, and restricting to just published datasets, there are a number of
+additional parameters that the object instance can be initiated with. These are
+as follows: - nocs - _accepts list input of valid National Operator Codes e.g.
 ['HIPK', 'YCST']_ - search - _accepts string input of key-words to filter for
 the data set name, data set description, organisation name, or admin name e.g.
 'Arriva'_ - bods_compliant - _accepts boolean input (True or False), where True
 filters for only BODS Compliant datasets. Default value is True_ - atco_code -
 _accepts list input of the first three characters of ATCO codes (ATCO codes are
 unique identifiers of UK bus stops, where first three characters signify the
 admin area they are within). This filters datasets and/or service lines that
-have stops within the specified admin areas. e.g. ['320','450']_ Example of
-this: ```python #intiate an object instance called my_bus_data_object with
-desired parameters from BODSDataExtractor.extractor import TimetableExtractor
-my_bus_data_object = TimetableExtractor(api_key=api # Your API Key Here
-#,limit=1 # commented out limit so will return all results within other
-parameters ,status = 'published' ,service_line_level=True ,stop_level=False
-,nocs=['FSCE','FGLA','FCYM'] #values must be entered in this list format - each
-noc within quotes, separated by comma, all within [] ,search='First Bus' # this
-is actually redundant as nocs are specific to this operator, but included for
-demo purpose ,bods_compliant=True ,atco_code=['320', '450'] # filter to stops
-within just north and west yorkshire. Values must be entered in this list
-format - each code within quotes, separated by comma, all within [] ) #save the
-extracted dataset level data to filtered_dataset_level variable
-filtered_dataset_level = my_bus_data_object.metadata #save the extracted
-service line level data to dataset_level variable filtered_service_line_level =
+have stops within the specified admin areas. e.g. ['320','450']_ - limit -
+_accepts an integer value which specifies the amount of datasets will be
+downloaded. For example, if there were 5 datasets present and the limit was set
+to 5, all datasets would be downloaded. Comparitively, if the limit was set to
+1 , only 1 dataset of the 5 will be downloaded._ Example of this: ```python
+#intiate an object instance called my_bus_data_object with desired parameters
+from BODSDataExtractor.extractor import TimetableExtractor my_bus_data_object =
+TimetableExtractor(api_key=api # Your API Key Here #,limit=1 # commented out
+limit so will return all results within other parameters ,status = 'published'
+,service_line_level=True ,stop_level=False ,nocs=['FSCE','FGLA','FCYM'] #values
+must be entered in this list format - each noc within quotes, separated by
+comma, all within [] ,search='First Bus' # this is actually redundant as nocs
+are specific to this operator, but included for demo purpose
+,bods_compliant=True ,atco_code=['320', '450'] # filter to stops within just
+north and west yorkshire. Values must be entered in this list format - each
+code within quotes, separated by comma, all within [] ) #save the extracted
+dataset level data to filtered_dataset_level variable filtered_dataset_level =
+my_bus_data_object.metadata #save the extracted service line level data to
+dataset_level variable filtered_service_line_level =
 my_bus_data_object.service_line_extract #export to csv if you wish to save this
 data filtered_service_line_level.to_csv
 ('filtered_service_line_level_export.csv') ``` ### ATCO Code to Local Authority
 Lookup Table The package contains an unofficial lookup table used to map bus
 stop ATCO codes to Local Authorities. This may be useful as a rough guide to
 filtering services around a certain area of England. Please note that this is
 not an official definition of ATCO / LA mappings and has been manually created.
@@ -351,36 +352,31 @@
 standard files Whilst all BODS compliant files meet a certain set of standards,
 there is still variation in exactly how timetables xml files can be populated.
 This pacakge currently handles files that meet the most common structure, and a
 number of notable exceptions, however there are some files that stop level
 timetables will not be generated for. It will, however, generate dataset level
 and service line level data for all published files. Future releases will aim
 to close this gap so timetables can be generated for most, if not all files.
-#### Handling vehicle journeys that cross midnight As the PTI standards
-dictate, sequence number logic is different for services that have stop times
-which cross midnight. This currently results in the stop level timetable output
-having vehicle journeys that do not start at sequence number 1. Future releases
-will include logic that better handles this to provide a more uniform output
-for such vehicle journeys. #### Providing additional detail about services
-Future releases will extract additional data from timetables xml files in order
-to provide further detail on services; for example details regarding the days
-of operation and exceptions around bank holidays, as well as more detailed
-route information including distance between stops, in addition to time. ####
-Incorporating AVL and Fares data The BODS platform also provides live vehicle
-location data (AVL), as well as Fares data. Future releases will aim to
-incorporate functionality for downloading and analysis AVL data initially, and
-subsequently Fares data once this has been validated. #### Optimising
-performance Generating stop level timetables requires downloading and parsing a
-significant volume of data. It therefore takes quite some time to run the code.
-Future releases will aim to reduce execution time through optimisations. ####
-And more! This project has consumers of BODS data at its heart, and so if any
-other features would be valuable, or any bugs are noticed please get in touch.
-Details of how to do this can be found in the 'Contributing' section below. See
-the [open issues](https://github.com/KPMG-UK/bods_pseudo_test/issues) for a
-full list of proposed features (and known issues).
+#### Providing additional detail about services Future releases will extract
+additional data from timetables xml files in order to provide further detail on
+services; for example details regarding the days of operation and exceptions
+around bank holidays, as well as more detailed route information including
+distance between stops, in addition to time. #### Incorporating AVL and Fares
+data The BODS platform also provides live vehicle location data (AVL), as well
+as Fares data. Future releases will aim to incorporate functionality for
+downloading and analysis AVL data initially, and subsequently Fares data once
+this has been validated. #### Optimising performance Generating stop level
+timetables requires downloading and parsing a significant volume of data. It
+therefore takes quite some time to run the code. Future releases will aim to
+reduce execution time through optimisations. #### And more! This project has
+consumers of BODS data at its heart, and so if any other features would be
+valuable, or any bugs are noticed please get in touch. Details of how to do
+this can be found in the 'Contributing' section below. See the [open issues]
+(https://github.com/KPMG-UK/bods_pseudo_test/issues) for a full list of
+proposed features (and known issues).
                                                                   (back_to_top)
  ## Contribute / Contact ### Contribute to this project Contributions are what
 make the open source community such an amazing place to learn, inspire, and
 create. Any contributions you make are **greatly appreciated**. If you want to
 suggest an new or improved feature, open an issue with the tag "enhancement".
 If you want to develop a new or improved feature yourself, fork the repo,
 develop within a new branch, then create a pull request back to this repo. We
```

### Comparing `BODSDataExtractor-1.1.1/pyproject.toml` & `BODSDataExtractor-1.2/pyproject.toml`

 * *Files 8% similar despite different names*

```diff
@@ -3,15 +3,15 @@
     "setuptools>=42"
 ]
 build-backend = "setuptools.build_meta"
 
 
 [project]
 name = "BODSDataExtractor"
-version = "1.1.1"
+version = "1.2"
 authors = [
   { name="Ali Partner, Spencer Brittain", email="bodshelpdesk@kpmg.co.uk" }
 ]
 description = "This project was created to lower the barrier to entry for analysis of UK Bus Open Data. It facilitates the fetching and extraction of clean data, currently focussed on Timetables, into tables to be used for analysis or your own projects."
 readme = "README.md"
 license = { file="LICENSE" }
 requires-python = ">=3.8"
```

### Comparing `BODSDataExtractor-1.1.1/src/BODSDataExtractor/ATCO_code_to_LA_lookup.csv` & `BODSDataExtractor-1.2/src/BODSDataExtractor/ATCO_code_to_LA_lookup.csv`

 * *Files identical despite different names*

### Comparing `BODSDataExtractor-1.1.1/src/BODSDataExtractor/example.py` & `BODSDataExtractor-1.2/src/BODSDataExtractor/example.py`

 * *Files 4% similar despite different names*

```diff
@@ -11,25 +11,27 @@
   from BODSDataExtractor.extractor import TimetableExtractor
 except:
   from extractor import TimetableExtractor
   
 import os
 
 #retrieve api key from environment variables
-api = os.environ.get('api_key')
+api = os.environ.get('BODS_API_KEY')
 
 #-------------------------------------------
 #            FINE TUNED RESULTS
 #-------------------------------------------
 #intiate an object instance called my_bus_data_object with desired parameters 
 
 my_bus_data_object = TimetableExtractor(api_key=api
+                                 ,limit=1
+                                 ,offset=0
                                  ,status = 'published' 
                                  ,service_line_level=True 
-                                 ,stop_level=True 
+                                 ,stop_level=True
                                  ,nocs=['BPTR','RBTS']
                                  ,bods_compliant=True
                                  )
 
 #save the extracted dataset level data to filtered_dataset_level variable
 filtered_dataset_level = my_bus_data_object.metadata
 
@@ -38,22 +40,19 @@
 
 #save the extracted service line level data to dataset_level variable
 filtered_service_line_level = my_bus_data_object.service_line_extract
 
 #save the extracted service line level data to lcoal csv file
 my_bus_data_object.save_service_line_extract_to_csv()
 
-#save the extracted stop level data to stop_level variable
-stop_level = my_bus_data_object.timetable_dict
-
-#stop_level variable is a dictionary of dataframes, which can be saved to csv as follows (saves in downloads folder)
-my_bus_data_object.save_all_timetables_to_csv()
+#stop_level_extract is a dataframe, which contains a collumn of timetables (inbound/outbound) to be saved to csv as follows (saves in project folder)
+my_bus_data_object.save_timetables()
 
 #visualise a particular service line on an interactive map
-my_bus_data_object.visualise_service_line('PB0001746:3')
+#my_bus_data_object.visualise_service_line('PB0001746:3')
 
 
 #-------------------------------------------
 #       REPORTING / ANALYTICS
 #-------------------------------------------
 count_of_operators = my_bus_data_object.count_operators() #returns count of distinct operators (measured by operator_name) in a chosen dataset
 
@@ -67,7 +66,8 @@
 
 red_dq = my_bus_data_object.red_dq_scores() #returns the number of operators in a table with red dq scores
 
 less_than_10 = my_bus_data_object.dq_less_than_x(90) # takes an integer as input (in this case 10) and returns a list of operators with a data quality score less than that integer
 
 no_lic_no = my_bus_data_object.no_licence_no() # returns a report listing which datasets contain files which do not have a licence number
 
+
```

### Comparing `BODSDataExtractor-1.1.1/src/BODSDataExtractor/extractor.py` & `BODSDataExtractor-1.2/src/BODSDataExtractor/extractor.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,115 +1,118 @@
-import pandas as pd
-import json
 import requests
 import zipfile
 import io
 import os
 from bods_client.client import BODSClient
 from bods_client.models import timetables
 from bods_client.models.base import APIError as BodsApiError
 from bods_client.models.timetables import TimetableResponse
 import lxml.etree as ET
-import xmltodict
 import itertools
 from itertools import zip_longest
-import numpy as np
 from pathlib import Path
 from sys import platform
 import re
 import concurrent.futures
-from typing import Union
-# try except ensures that this reads in lookup file whether pip installing the library, or cloning the repo from GitHub
+
 try:
     import BODSDataExtractor.otc_db_download as otc_db_download
 except:
     import otc_db_download
 from datetime import date
-import datetime
 from collections import Counter
 import importlib.resources
-
 from shapely.geometry import Point
 from geopandas import GeoDataFrame
-import plotly.express as px
-import plotly.io as pio
-
-class TimetableExtractor:
+import pandas as pd
+from dacite import from_dict
+import xmltodict
+import datetime
+from classes import *
 
 
+class TimetableExtractor:
     error_list = []
 
-    def __init__(self, api_key, limit=10_000, nocs=None, status='published', search=None, bods_compliant=True, atco_code=None, service_line_level=False, stop_level=False, threaded=False):
+    def __init__(self, api_key, limit=10_000, offset=0, nocs=None, status='published',
+                 search=None, bods_compliant=True, atco_code=None, service_line_level=False,
+                 stop_level=False, threaded=False):
         self.api_key = api_key
         self.limit = limit
+        self.offset = offset
         self.nocs = nocs
         self.status = status
         self.search = search
         self.bods_compliant = bods_compliant
         self.atco_code = atco_code
         self.service_line_level = service_line_level
         self.stop_level = stop_level
         self.threaded = threaded
 
         self.pull_timetable_data()
 
         if self.metadata is None:
-            return # early return if no results to process
+            return  # early return if no results to process
 
         self.otc_db = otc_db_download.fetch_otc_db()
 
         if service_line_level or stop_level:
             self.analytical_timetable_data()
             self.analytical_timetable_data_analysis()
 
         if stop_level:
             self.generate_timetable()
 
     def create_metadata_df(self, timetable_api_response):
         """Converts BODS Timetable API results into a Pandas dataframe."""
-        df =  pd.DataFrame([vars(t_dataset) for t_dataset in timetable_api_response.results])
+        df = pd.DataFrame([vars(t_dataset) for t_dataset in timetable_api_response.results])
         df['filetype'] = df['extension']
         return df
 
     def extract_dataset_level_atco_codes(self):
 
-        #initiate list for atco codes
+        # initiate list for atco codes
         atco_codes = []
-        #extract atco code from admin_area list of dicts on each row
+        # extract atco code from admin_area list of dicts on each row
         for r in self.metadata['admin_areas']:
             atco_codes.append([d['atco_code'] for d in r])
 
-        #flatten list of lists to list, and ensure only unique values
+        # flatten list of lists to list, and ensure only unique values
         atco_codes = list(set((itertools.chain(*atco_codes))))
 
         return atco_codes
 
     def _handle_api_response(self, response: Union[TimetableResponse, BodsApiError]):
         """Handle and validate the API response. Inform the user of any issues."""
         if type(response) is BodsApiError:
             if response.status_code == 401:
                 self.metadata = None
                 print('Invalid API token used.')
                 return
+            elif response.status_code == 504:
+                self.metadata = None
+                print('Gateway error, please check BODS website.')
+                return
             else:
                 raise ValueError(repr(response))
-            
+
         if type(response) is TimetableResponse and response.count == 0:
             self.metadata = None
             print('No results returned from BODS Timetable API. Please check input parameters.')
             return
-        
+
         return response
 
     def _get_timetable_datasets(self):
         """Queries the BODS Timetable API as per the parameters set at instance
         initialisation.
         """
         bods = BODSClient(api_key=self.api_key)
         params = timetables.TimetableParams(limit=self.limit,
+                                            offset=self.offset,
                                             nocs=self.nocs,
                                             status=self.status,
                                             admin_areas=self.atco_code,
                                             search=self.search)
         api_response = bods.get_timetable_datasets(params=params)
         return self._handle_api_response(api_response)
 
@@ -122,46 +125,46 @@
         """
         print(f"Fetching timetable metadata for up to {self.limit:,} datasets...")
         timetable_datasets = self._get_timetable_datasets()
         if not timetable_datasets:
             return
         self.metadata = self.create_metadata_df(timetable_datasets)
 
-        if self.bods_compliant == True:
+        if self.bods_compliant:
             self.metadata = self.metadata[self.metadata['bods_compliance'] == True]
 
         print(f"Metadata downloaded for {self.metadata.shape[0]:,} datasets.")
 
     def xml_metadata(self, url, error_list):
 
         '''' This function assumes the file at the end of the URL is an xml file.
              If so, it returns the filename, size and url link as a tuple. If
              file type is invalid it will print an error and skip.
-             
+
              Arguments: URL and a list in which to pass urls which could not be treated as xmls
         '''
 
         try:
             resp = requests.get(url)
 
-            #create a temporary file in the local directory to get the file size
+            # create a temporary file in the local directory to get the file size
             with open(r'temp.xml', 'w', encoding="utf-8") as file:
                 file.write(resp.text)
                 size = os.path.getsize(r'temp.xml')
 
-                #dig into the headers of the file to pull the file name
+                # dig into the headers of the file to pull the file name
                 meta = resp.headers
                 filename = str(meta["Content-Disposition"].split('"')[1])
 
             print("xml file found and appended to list\n")
-            return(filename, size, url)
+            return (filename, size, url)
 
 
         except:
-            #if we reach this then the filetype may not be xml or zip and needs investigating
+            # if we reach this then the filetype may not be xml or zip and needs investigating
             print(f"*****Error in dataset. Please check filetype: {url}*****\n")
             TimetableExtractor.error_list.append(url)
             pass
 
     def _dataset_filetype(self, response_headers):
         """Determines the filetype of the dataset served up by a dataset url.
         Returns None if it can't be determined.
@@ -173,14 +176,18 @@
         except AttributeError:
             return None
 
     def download_extract_txc(self, url):
         """Download the txc data from a dataset url (can be zip or single xml) and
         extracts the data into a Pandas dataframe."""
         response = requests.get(url)
+        try:
+            response.raise_for_status()
+        except requests.exceptions.HTTPError as e:
+            raise e
         filetype = self._dataset_filetype(response.headers)
 
         if filetype == '.zip':
             print(f'Fetching zip file from {url}...')
             txc_df = self._extract_zip(response)
         elif filetype == '.xml':
             print(f'Fetching xml file from {url}...')
@@ -205,68 +212,83 @@
                     print(f'Found "{extension}" file in zip folder, passing...')
                     continue
 
                 with thezip.open(zipinfo) as thefile:
                     try:
                         xml_output = self._extract_xml(response.url, thefile)
                         output.append(xml_output)
-                    except: # TODO really should be catching specific errors
+                    except:  # TODO really should be catching specific errors
                         TimetableExtractor.error_list.append(response.url)
 
         return pd.concat(output)
 
     def _extract_xml(self, url, xml):
         xml_output = [url]
         xml_data_extractor = xmlDataExtractor(xml)
         xml_output.extend(xml_data_extractor.extract_service_level_info())
 
         # if stop level data is requested, then need the additional columns that contain jsons of the stop level info
-        if self.stop_level == True:
-
-# =============================================================================
-#               also read in xml as a text string
-#               this is required for extracting sections of the xml for further stop level extraction, not just elements or attribs
-# =============================================================================
+        if self.stop_level:
+            # =============================================================================
+            #               also read in xml as a text string
+            #               this is required for extracting sections of the xml for further stop level extraction, not just elements or attribs
+            # =============================================================================
             xml.seek(0)
             xml_text = xml.read()
             xml_json = xmltodict.parse(
                 xml_text,
-                process_namespaces=False, 
-                force_list=('JourneyPatternSection','JourneyPatternTimingLink','VehicleJourney','VehicleJourneyTimingLink'))
+                process_namespaces=False,
+                attr_prefix='_',
+                force_list=(
+                    'JourneyPatternSection',
+                    'JourneyPatternTimingLink',
+                    'VehicleJourney',
+                    'VehicleJourneyTimingLink',
+                    'JourneyPattern'))
 
-            journey_pattern_json = xml_json['TransXChange']['JourneyPatternSections']['JourneyPatternSection']
+            journey_pattern_json = xml_json['TransXChange']['JourneyPatternSections']  # ['JourneyPatternSection']
             xml_output.append(journey_pattern_json)
 
-            vehicle_journey_json = xml_json['TransXChange']['VehicleJourneys']['VehicleJourney']
+            vehicle_journey_json = xml_json['TransXChange']['VehicleJourneys']  # ['VehicleJourney']
             xml_output.append(vehicle_journey_json)
 
             services_json = xml_json['TransXChange']['Services']['Service']
             xml_output.append(services_json)
 
+            stops_json = xml_json['TransXChange']['StopPoints']
+            xml_output.append(stops_json)
+
         output_df = pd.DataFrame(xml_output).T
 
-        if self.stop_level == True:
-            output_df.columns = ['URL', 'FileName', 'NOC', 'TradingName', 'LicenceNumber', 'OperatorShortName', 'OperatorCode', 'ServiceCode', 'LineName', 'PublicUse','OperatingDays', 'Origin', 'Destination', 'OperatingPeriodStartDate', 'OperatingPeriodEndDate', 'SchemaVersion', 'RevisionNumber','la_code','journey_pattern_json', 'vehicle_journey_json','services_json']
+        if self.stop_level:
+            output_df.columns = ['URL', 'FileName', 'NOC', 'TradingName', 'LicenceNumber', 'OperatorShortName',
+                                 'OperatorCode', 'ServiceCode', 'LineName', 'PublicUse', 'OperatingDays', 'Origin',
+                                 'Destination', 'OperatingPeriodStartDate', 'OperatingPeriodEndDate', 'SchemaVersion',
+                                 'RevisionNumber', 'la_code', 'journey_pattern_json', 'vehicle_journey_json',
+                                 'services_json', 'stops_json']
         else:
-            output_df.columns = ['URL', 'FileName', 'NOC', 'TradingName', 'LicenceNumber', 'OperatorShortName', 'OperatorCode', 'ServiceCode', 'LineName', 'PublicUse','OperatingDays', 'Origin', 'Destination', 'OperatingPeriodStartDate', 'OperatingPeriodEndDate', 'SchemaVersion', 'RevisionNumber','la_code']
+            output_df.columns = ['URL', 'FileName', 'NOC', 'TradingName', 'LicenceNumber', 'OperatorShortName',
+                                 'OperatorCode', 'ServiceCode', 'LineName', 'PublicUse', 'OperatingDays', 'Origin',
+                                 'Destination', 'OperatingPeriodStartDate', 'OperatingPeriodEndDate', 'SchemaVersion',
+                                 'RevisionNumber', 'la_code']
 
         return output_df
 
     def fetch_xml_filenames(self):
 
         metadata_table = TimetableExtractor.pull_timetable_data(self)
 
         xml_filenames = TimetableExtractor.open_urls(self, metadata_table)
 
-        full_table = metadata_table.merge(xml_filenames, on = 'url', how = 'left')
+        full_table = metadata_table.merge(xml_filenames, on='url', how='left')
 
         return full_table
 
     def analytical_timetable_data(self):
-        """Uses a collection of extraction functions to extract data from within xml files. 
+        """Uses a collection of extraction functions to extract data from within xml files.
         Some of these xml files are within zip files, and so these are processed differently.
         This extracted data is combined with the metadata of each file, and columns renamed to
         yield analytical ready timetable data.
         """
         orig_cols = [
             "url",
             "id",
@@ -329,641 +351,100 @@
         )
         self.service_line_extract_with_stop_level_json = self.xplode(
             self.service_line_extract_with_stop_level_json, ['LineName']
         )
         self.service_line_extract_with_stop_level_json = self.xplode(
             self.service_line_extract_with_stop_level_json, ['la_code']
         )
-        # Why is this needed?
-        self.service_line_extract_with_stop_level_json.to_csv("output.csv")
 
         self.service_line_extract_with_stop_level_json["dq_score"] = (
             self.service_line_extract_with_stop_level_json["dq_score"]
             .str.rstrip("%")
             .astype("float")
         )
 
         print(f'The following URLs failed: {TimetableExtractor.error_list}')
 
-# =============================================================================
-#         dataset level filtering by atco codes has already been handled if requested
-#         however, within a dataset some service lines will not have stops within all atco codes
-#         that the dataset as a whole has. Therefore now we filter again to return just specifc service
-#         lines for requested atcos
-# =============================================================================
+        # =============================================================================
+        #         dataset level filtering by atco codes has already been handled if requested
+        #         however, within a dataset some service lines will not have stops within all atco codes
+        #         that the dataset as a whole has. Therefore now we filter again to return just specifc service
+        #         lines for requested atcos
+        # =============================================================================
         if self.atco_code is not None:
-            self.service_line_extract_with_stop_level_json = self.service_line_extract_with_stop_level_json[self.service_line_extract_with_stop_level_json['la_code'].isin(self.atco_code)]
+            self.service_line_extract_with_stop_level_json = self.service_line_extract_with_stop_level_json[
+                self.service_line_extract_with_stop_level_json['la_code'].isin(self.atco_code)]
 
     def analytical_timetable_data_analysis(self):
         """Returns a copy of the service line level data suitable for analysis. Omits the columns with jsons
-        of the final stop level data required for further processing and stop level analysis, for 
-        performance and storage sake. Also omits la_code column, as if user is not interested in 
+        of the final stop level data required for further processing and stop level analysis, for
+        performance and storage sake. Also omits la_code column, as if user is not interested in
         local authorities of services then this adds unnecessary duplication (one service line can be in
         multiple las.)
         """
         self.service_line_extract = self.service_line_extract_with_stop_level_json.drop(
             ["la_code"], axis=1
         )
 
         if self.stop_level:
             self.service_line_extract = self.service_line_extract_with_stop_level_json.drop(
-                ["journey_pattern_json", "vehicle_journey_json", "services_json"], axis=1
+                ["journey_pattern_json", "vehicle_journey_json", "services_json", "stops_json"], axis=1
             )
 
         self.service_line_extract = self.service_line_extract.drop_duplicates()
-        self.check_for_expired_operators()
+        self.check_for_expired_services()
 
-    def check_for_expired_operators(self):
+    def check_for_expired_services(self):
         """Adds service expiry status (True or False) to service level extract,
         based on "OperatingPeriodEndDate" and today's date, where applicable.
         If no end date provided then "No End Date" entered.
         """
         today = datetime.datetime.now()
-        self.service_line_extract["Expired_Operator"] = (
-            pd.to_datetime(self.service_line_extract["OperatingPeriodEndDate"]) < today
+        self.service_line_extract["expired service"] = (
+                pd.to_datetime(self.service_line_extract["OperatingPeriodEndDate"]) < today
         )
         self.service_line_extract.loc[
-            self.service_line_extract["OperatingPeriodEndDate"].isna(), "Expired_Operator"
+            self.service_line_extract["OperatingPeriodEndDate"].isna(), "expired service"
         ] = 'No End Date'
 
     def xplode(self, df, cols_to_explode):
         """Explode out lists in dataframes.
         Taken from https://stackoverflow.com/a/61390677"""
         rest = {*df} - {*cols_to_explode}
         zipped = zip(zip(*map(df.get, rest)), zip(*map(df.get, cols_to_explode)))
         tups = [tup + exploded for tup, pre in zipped for exploded in zip_longest(*pre)]
 
         return pd.DataFrame(tups, columns=[*rest, *cols_to_explode])
 
-# =============================================================================
-#       FUNCTIONS FOR EXTRACTING STOP LEVEL DATA
-# =============================================================================
-    def unwrap_journey_pattern_json(self, json):
-
-        """
-        For each record in the service line level table, this function extracts journey pattern 
-        (route pattern and time taken to travel from each stop) stop level info
-        by unwrapping the json like structure in the line level table.
-        This is used by the produce_stop_level_df_journey function to create a dataframe 
-        of journey stop level info
-        """
-
-        #initiate empty lists for results to be appended to
-        js_id = []
-        jptl_id = []
-        runtime = []
-        stop_from = []
-        stop_to = []
-        sequence_number = []
-        timingstatus = []
-
-        #loop through the JourneyPatternSection elements within the JourneyPatternSections frame
-        for js in range(0,len(json)):
-
-            #loops through the JourneyPatternTimingLink elements within the JourneyPatternSection element to get relevant info
-            for jptl in range(0,len(json[js]['JourneyPatternTimingLink'])):
-                js_id.append(json[js]['@id'])
-                jptl_id.append(json[js]['JourneyPatternTimingLink'][jptl]['@id'])
-                runtime.append(json[js]['JourneyPatternTimingLink'][jptl]['RunTime'])
-                stop_from.append(json[js]['JourneyPatternTimingLink'][jptl]['From']['StopPointRef'])
-                stop_to.append(json[js]['JourneyPatternTimingLink'][jptl]['To']['StopPointRef'])
-                # sequence no and timing status not mandated by schema so must use try except
-                try:
-                    sequence_number.append(json[js]['JourneyPatternTimingLink'][jptl]['From']['@SequenceNumber'])
-                except:
-                    sequence_number.append(np.NaN)
-                try:
-                    timingstatus.append(json[js]['JourneyPatternTimingLink'][jptl]['From']['TimingStatus'])
-                except:
-                    timingstatus.append(np.NaN)
-
-
-        #zip these lists into a dict            
-        journey_pattern_dict = {
-            "JourneyPatternSectionID": js_id
-            ,"journey_pattern_timing_link": jptl_id
-            ,"stop_from": stop_from
-            ,"stop_to": stop_to
-            ,"sequence_number": sequence_number
-            ,"timingstatus": timingstatus
-            ,"runtime": runtime
-            }
-
-        return journey_pattern_dict
-
-
-    def unwrap_vehicle_journey_json(self, json):
-
-        """
-        For each record in the service line level table, this function extracts vehicle journey 
-        (specific vehicle depature times) 
-        stop level info by unwrapping the json like structure in the line level table.
-        This is used by the produce_stop_level_df_vehicle function to create a dataframe 
-        of vehicle stop level info.
-        """
-
-        #initiate empty lists for results to be appended to
-        VehicleJourneyCode = []
-        JourneyPatternRef = []
-        DepartureTime = []
-        LineRef = []
-
-        #loop through the VehicleJourney elements within the VehicleJourneys frame
-        for v in range(0,len(json)):
-            LineRef.append(json[v]['LineRef'])
-            VehicleJourneyCode.append(json[v]['VehicleJourneyCode'])
-            JourneyPatternRef.append(json[v]['JourneyPatternRef']  )
-            DepartureTime.append(json[v]['DepartureTime'])
-
-        #zip these lists into a dict                               
-        vehicle_journey_dict = {
-            "VehicleJourneyCode": VehicleJourneyCode
-            ,"JourneyPatternRef": JourneyPatternRef
-            ,"DepartureTime": DepartureTime
-            ,"LineRef": LineRef
-            }
-
-        return vehicle_journey_dict
-
-
-    #test to get run times where necessary
-    def unwrap_vehicle_journey_json_for_runtime(self, json):
-
-        """
-        For each record in the service line level table, this function extracts vehicle journey 
-        (specific vehicle depature times and cases time taken to travel from each stop) 
-        stop level info by unwrapping the json like structure in the line level table.
-        This is used by the produce_stop_level_df_vehicle function to create a dataframe 
-        of vehicle stop level info.
-        This differs from the the unwrap_vehicle_journey_json in that it handles xml files 
-        where they contain runtime info in the vehicle frame, and not the journey pattern frame.
-        """
-
-        #initiate empty lists for results to be appended to
-        JourneyPatternRef = []
-        LineRef = []
-        jptl_id = []
-        runtime = []
-
-        for v in range(0,len(json)):
-
-            #loops through the VehicleJourneyTimingLink elements within the VehicleJourney element to get relevant info
-             for vjtl in range(0,len(json[v]['VehicleJourneyTimingLink'])):
-                LineRef.append(json[v]['LineRef'])
-                JourneyPatternRef.append(json[v]['JourneyPatternRef']  )
-                jptl_id.append(json[v]['VehicleJourneyTimingLink'][vjtl]['JourneyPatternTimingLinkRef'])
-                runtime.append(json[v]['VehicleJourneyTimingLink'][vjtl]['RunTime'])
-
-
-        #zip these lists into a dict            
-        vehicle_journey_runtime_dict = {
-            "JourneyPatternRef": JourneyPatternRef
-            ,"LineRef": LineRef
-            ,"journey_pattern_timing_link": jptl_id
-            ,"runtime": runtime
-            }
-
-        return vehicle_journey_runtime_dict
-
-    def unwrap_service_json(self, json):
-
-        """
-        For each record in the service line level table, this function extracts service
-        info by unwrapping the json like structure in the line level table. This service info
-        is used to join the vehicle journey and journey pattern data together.
-        This is used by the produce_stop_level_df_service function to create a dataframe 
-        of stop level info.
-        """
-
-        #initiate empty lists for results to be appended to
-        jp_id = []
-        jpsf_id = []
-
-        #if there is just one journeypattern in a service frame, must treat as a dict, not a list
-        if type(json['StandardService']['JourneyPattern']) is list:
-            #list handling
-            for jp in range(0,len(json['StandardService']['JourneyPattern'])):
-                jp_id.append(json['StandardService']['JourneyPattern'][jp]['@id'])
-                jpsf_id.append(json['StandardService']['JourneyPattern'][jp]['JourneyPatternSectionRefs'])
-        else:
-            #dict handling
-            jp_id.append(json['StandardService']['JourneyPattern']['@id'])
-            jpsf_id.append(json['StandardService']['JourneyPattern']['JourneyPatternSectionRefs'])
-
-        #zip these lists into a dict
-        service_pattern_dict = {
-            #"ServiceCode":service_list
-            "JourneyPattern_id": jp_id
-            ,"JourneyPatternSectionRef": jpsf_id
-
-            }
-
-        return service_pattern_dict
-
-
-    def produce_stop_level_df_journey(self):
-
-        """
-        Using the unwrap_journey_pattern_json function, this produces a dataframe 
-        that describes the journey patterns detailed in each xml file
-        """
-
-
-        #select just relevant columns
-        full_data_extract_no_la_code = self.service_line_extract_with_stop_level_json.drop('la_code',axis=1)
-        full_data_extract_no_la_code = full_data_extract_no_la_code.drop_duplicates(subset=['URL','DatasetID','FileName','NOC','ServiceCode','ServiceCode','LineName','RevisionNumber','Origin','Destination']).reset_index()
-
-        #initiate list for results to be added to
-        stop_level_list_journey = []
-
-        #loop through each record (xml file) in the service line level extract, and unwrap the journey pattern json
-        for i in range(0,len(full_data_extract_no_la_code)):
-            try:
-                stop_level_list_journey_pre = TimetableExtractor.unwrap_journey_pattern_json(self, full_data_extract_no_la_code['journey_pattern_json'][i])
-            except:
-                print(full_data_extract_no_la_code['DatasetID'][i], full_data_extract_no_la_code['FileName'][i], 'journey extraction error')
-                pass
-
-            #add relevant meta data from that file to the unwrapped journey pattern details
-            stop_level_list_journey_pre['DatasetID'] = full_data_extract_no_la_code['DatasetID'][i]
-            stop_level_list_journey_pre['FileName'] = full_data_extract_no_la_code['FileName'][i]
-            stop_level_list_journey_pre['ServiceCode'] = full_data_extract_no_la_code['ServiceCode'][i]
-            stop_level_list_journey_pre['LineName'] = full_data_extract_no_la_code['LineName'][i]
-            stop_level_list_journey_pre['RevisionNumber'] = full_data_extract_no_la_code['RevisionNumber'][i]
-
-            #append results to list
-            stop_level_list_journey.append(stop_level_list_journey_pre)
-
-        #convert list to dataframe
-        stop_level_df_journey = pd.DataFrame(stop_level_list_journey)
-
-        #explode out lists in dataframe
-        stop_level_df_journey = self.xplode(stop_level_df_journey,['JourneyPatternSectionID'
-                                          ,"journey_pattern_timing_link"
-                                          ,"stop_from"
-                                          ,"stop_to"
-                                          ,"sequence_number"
-                                          ,"timingstatus"
-                                          ,"runtime"
-                                             ])
-
-        return stop_level_df_journey
-
-
-
-    def produce_stop_level_df_vehicle(self):
-
-        """
-        Using the unwrap_journey_pattern_vehicle function, this produces a dataframe 
-        that describes the vehicle journeys detailed in each xml file
-        """
-
-        #select just relevant columns
-        full_data_extract_no_la_code = self.service_line_extract_with_stop_level_json.drop('la_code',axis=1)
-        full_data_extract_no_la_code = full_data_extract_no_la_code.drop_duplicates(subset=['URL','DatasetID','FileName','NOC','ServiceCode','ServiceCode','LineName','RevisionNumber','Origin','Destination']).reset_index()
-
-        #initiate list for results to be added to
-        stop_level_list_vehicle = []
-
-        #loop through each record (xml file) in the service line level extract, and unwrap the vehicle journey json
-        for i in range(0,len(full_data_extract_no_la_code)):
-            try:
-                stop_level_list_vehicle_pre = TimetableExtractor.unwrap_vehicle_journey_json(self, full_data_extract_no_la_code['vehicle_journey_json'][i])
-            except:
-                print(full_data_extract_no_la_code['DatasetID'][i], full_data_extract_no_la_code['FileName'][i], 'vehicle extraction error')
-                pass
-
-            #add relevant meta data from that file to the unwrapped vehicle journey details
-            stop_level_list_vehicle_pre['DatasetID'] = full_data_extract_no_la_code['DatasetID'][i]
-            stop_level_list_vehicle_pre['FileName'] = full_data_extract_no_la_code['FileName'][i]
-            stop_level_list_vehicle_pre['ServiceCode'] = full_data_extract_no_la_code['ServiceCode'][i]
-            stop_level_list_vehicle_pre['LineName'] = full_data_extract_no_la_code['LineName'][i]
-            stop_level_list_vehicle_pre['RevisionNumber'] = full_data_extract_no_la_code['RevisionNumber'][i]
-
-            #append results to list
-            stop_level_list_vehicle.append(stop_level_list_vehicle_pre)
-
-        #convert list to dataframe
-        stop_level_df_vehicle = pd.DataFrame(stop_level_list_vehicle)
-
-        #explode out lists in dataframe
-        stop_level_df_vehicle = self.xplode(stop_level_df_vehicle,[
-                                            "VehicleJourneyCode"
-                                            ,"JourneyPatternRef"
-                                            ,"DepartureTime"
-                                            ,"LineRef"
-                                              ])
-
-        return stop_level_df_vehicle
-
-    def produce_stop_level_df_vehicle_for_runtime(self):
-
-        """
-        Using the unwrap_journey_pattern_vehicle function, this produces a dataframe 
-        that describes the vehicle journeys detailed in each xml file. 
-        This differes from the produce_stop_level_df_vehicle in that it handles xml files 
-        where they contain runtime info in the vehicle frame, and not the journey pattern frame.
-        """
-            
-        #select just relevant columns
-        full_data_extract_no_la_code = self.service_line_extract_with_stop_level_json.drop('la_code',axis=1)
-        full_data_extract_no_la_code = full_data_extract_no_la_code.drop_duplicates(subset=['URL','DatasetID','FileName','NOC','ServiceCode','ServiceCode','LineName','RevisionNumber','Origin','Destination']).reset_index()
-
-        #initiate list for results to be added to
-        stop_level_list_vehicle = []
-
-        #loop through each record (xml file) in the service line level extract, and unwrap the vehicle journey json
-        for i in range(0,len(full_data_extract_no_la_code)):
-            try:
-                stop_level_list_vehicle_pre = TimetableExtractor.unwrap_vehicle_journey_json_for_runtime(self, full_data_extract_no_la_code['vehicle_journey_json'][i])
-            except:
-                # print(full_data_extract_no_la_code['DatasetID'][i], full_data_extract_no_la_code['FileName'][i], 'vehicle for runtime extraction error')
-                stop_level_list_vehicle_pre = {'JourneyPatternRef':'N/A','LineRef':'N/A','journey_pattern_timing_link':'N/A','runtime':'N/A'}
-
-            #add relevant meta data from that file to the unwrapped vehicle journey details
-            stop_level_list_vehicle_pre['DatasetID'] = full_data_extract_no_la_code['DatasetID'][i]
-            stop_level_list_vehicle_pre['FileName'] = full_data_extract_no_la_code['FileName'][i]
-            stop_level_list_vehicle_pre['ServiceCode'] = full_data_extract_no_la_code['ServiceCode'][i]
-            stop_level_list_vehicle_pre['LineName'] = full_data_extract_no_la_code['LineName'][i]
-            stop_level_list_vehicle_pre['RevisionNumber'] = full_data_extract_no_la_code['RevisionNumber'][i]
-
-            #append results to list
-            stop_level_list_vehicle.append(stop_level_list_vehicle_pre)
-
-        #convert list to dataframe
-        stop_level_df_vehicle = pd.DataFrame(stop_level_list_vehicle)
-
-        #explode out lists in dataframe
-        stop_level_df_vehicle = self.xplode(stop_level_df_vehicle,[
-                                                # "VehicleJourneyCode"
-                                                "JourneyPatternRef"
-                                                ,"LineRef"
-                                                ,'journey_pattern_timing_link'
-                                                ,'runtime'
-                                                ])
-
-        stop_level_df_vehicle = stop_level_df_vehicle.drop_duplicates()
-
-        return stop_level_df_vehicle
-    
-
-    def produce_stop_level_df_service(self):
-
-        """
-        Using the unwrap_journey_pattern_service function, this produces a dataframe 
-        that provides key info from the service frames in each xml file, that will
-        allow vehicle journey and journey pattern info to be joined together.
-        """
-
-        #select just relevant columns
-        full_data_extract_no_la_code = self.service_line_extract_with_stop_level_json.drop('la_code',axis=1)
-        full_data_extract_no_la_code = full_data_extract_no_la_code.drop_duplicates(subset=['URL','DatasetID','FileName','NOC','ServiceCode','ServiceCode','LineName','RevisionNumber','Origin','Destination']).reset_index()
-
-        #initiate list for results to be added to
-        stop_level_list_service = []
-
-        #loop through each record (xml file) in the service line level extract, and unwrap the service json
-        for i in range(0,len(full_data_extract_no_la_code)):
-
-            try:
-                stop_level_list_service_pre = TimetableExtractor.unwrap_service_json(self, full_data_extract_no_la_code['services_json'][i])
-            except:
-                print(full_data_extract_no_la_code['DatasetID'][i], full_data_extract_no_la_code['FileName'][i],'service frame extraction error')
-                pass
-
-            #add relevant meta data from that file to the unwrapped service details
-            stop_level_list_service_pre['DatasetID'] = full_data_extract_no_la_code['DatasetID'][i]
-            stop_level_list_service_pre['FileName'] = full_data_extract_no_la_code['FileName'][i]
-            stop_level_list_service_pre['ServiceCode'] = full_data_extract_no_la_code['ServiceCode'][i]
-            stop_level_list_service_pre['LineName'] = full_data_extract_no_la_code['LineName'][i]
-            stop_level_list_service_pre['RevisionNumber'] = full_data_extract_no_la_code['RevisionNumber'][i]
-
-            #append results to list
-            stop_level_list_service.append(stop_level_list_service_pre)
-
-            #convert list to dataframe
-        stop_level_df_service = pd.DataFrame(stop_level_list_service)
-
-        #explode out lists in dataframe
-        stop_level_df_service = self.xplode(stop_level_df_service,['JourneyPattern_id', 'JourneyPatternSectionRef'])
-        stop_level_df_service = stop_level_df_service.explode(['JourneyPatternSectionRef']).reset_index()
-        del stop_level_df_service['index']
-
-        return stop_level_df_service
-
-
+    # =============================================================================
+    #       FUNCTIONS FOR EXTRACTING STOP LEVEL DATA
+    # =============================================================================
 
     def fetch_naptan_data(self):
 
         '''
         Access NAPTAN API to fetch lat and long coordinates for all relevant stops.
         Edited to fetch of all stops to avoid bugs. This could be improved in future.
         '''
 
-        #get list of relevant admin area codes, to target api call
+        # get list of relevant admin area codes, to target api call
         # atcos = list(self.service_line_extract_with_stop_level_json['la_code'].unique())
         # atcos = ",".join(atcos)
 
-        #call naptan api
+        # call naptan api
         # url = f"https://naptan.api.dft.gov.uk/v1/access-nodes?atcoAreaCodes={atcos}&dataFormat=csv"
         url = "https://naptan.api.dft.gov.uk/v1/access-nodes?&dataFormat=csv"
 
         # filter results within call to those needed (just lat and long)
         r = requests.get(url).content
-        naptan = pd.read_csv(io.StringIO(r.decode('utf-8')), usecols=['ATCOCode','CommonName','Longitude','Latitude'])
+        naptan = pd.read_csv(io.StringIO(r.decode('utf-8')),
+                             usecols=['ATCOCode', 'CommonName', 'Longitude', 'Latitude'])
 
         return naptan
 
-    def join_stop_level_data(self):
-
-        '''
-        Stitch together the journey, vehicle and service stop level data, which
-        are extracted and processed in other functions in this class.
-        '''
-
-        print('Extracting stop level data... \n')
-
-        #call functions to extract stop level data
-        vehicle_stop_level = TimetableExtractor.produce_stop_level_df_vehicle(self)
-        vehicle_with_runtime_stop_level = TimetableExtractor.produce_stop_level_df_vehicle_for_runtime(self)
-        journey_stop_level = TimetableExtractor.produce_stop_level_df_journey(self)
-        service_stop_level = TimetableExtractor.produce_stop_level_df_service(self)
-
-
-        #join vehicle stop level data to services (this will allow subsequent join to journey data)
-        stop_level_joined = vehicle_stop_level.merge(service_stop_level[['JourneyPattern_id','JourneyPatternSectionRef','ServiceCode','LineName','RevisionNumber']]
-                                                            ,how='left'
-                                                            ,left_on=['JourneyPatternRef','ServiceCode','LineName','RevisionNumber']
-                                                            ,right_on=['JourneyPattern_id','ServiceCode','LineName','RevisionNumber']).drop_duplicates()
-        #remove extra col added in join
-        del stop_level_joined['JourneyPattern_id']
-
-        #join on each stop from journey frame
-        stop_level_joined = stop_level_joined.merge(journey_stop_level[['JourneyPatternSectionID','ServiceCode','journey_pattern_timing_link','stop_from','stop_to','sequence_number','timingstatus','runtime','LineName','RevisionNumber' ]]#,'Longitude','Latitude']]
-                                                    ,how='left'
-                                                    ,left_on=['JourneyPatternSectionRef','ServiceCode','LineName','RevisionNumber']
-                                                    ,right_on=['JourneyPatternSectionID','ServiceCode','LineName','RevisionNumber']).drop_duplicates()
-
-        #remove extra col added in join
-        del stop_level_joined['JourneyPatternSectionID']
-
-        #remove null sequence numbers - in 1.1 release fix will ensure null seq numbers can be handled
-        stop_level_joined = stop_level_joined[~stop_level_joined['sequence_number'].isnull()]
-
-        #convert data type of seq number to int
-        stop_level_joined['sequence_number'] = stop_level_joined['sequence_number'].astype('int')
-
-        #join on vehicle for runtime frame to get runtimes where not in journey frame
-        stop_level_joined = stop_level_joined.merge(vehicle_with_runtime_stop_level[['ServiceCode','JourneyPatternRef','journey_pattern_timing_link','runtime','LineName','RevisionNumber']]
-                                                                                             ,how='left'
-                                                                                             ,left_on=['ServiceCode','JourneyPatternRef','journey_pattern_timing_link','LineName','RevisionNumber']
-                                                                                             ,right_on=['ServiceCode','JourneyPatternRef','journey_pattern_timing_link','LineName','RevisionNumber']
-                                                                                             ).drop_duplicates()
-
-        
-        return stop_level_joined
-
-
-    def clean_stop_level_data(self):
-
-        '''
-        Process and clean the joined stop level data, to return stop level data
-        that has correct depature times for the start of each vehicle journey,
-        and run time in minutes for subsequent stops.
-        '''
-
-        #call function to return joined stop level data
-        stop_level_joined_clean = TimetableExtractor.join_stop_level_data(self)
-
-        print('Cleaning stop level data... \n')
-
-        #extract minute from runtime col (regex find numeric characters)
-        stop_level_joined_clean['runtime_x'] = stop_level_joined_clean['runtime_x'].astype('str').str.extract(r'(\d+)')
-        stop_level_joined_clean['runtime_y'] = stop_level_joined_clean['runtime_y'].astype('str').str.extract(r'(\d+)')
-
-        #coalesce these cols - PTI logic dictates that if there is no runtime in the vehicle frame, then use the journey frame
-        stop_level_joined_clean['runtime'] = stop_level_joined_clean['runtime_y'].combine_first(stop_level_joined_clean['runtime_x'])
-
-        #remove unnecessary cols
-        del stop_level_joined_clean['runtime_y']
-        del stop_level_joined_clean['runtime_x']
-
-        #convert to time delta
-        stop_level_joined_clean['runtime'] = stop_level_joined_clean['runtime'].apply(lambda x: pd.Timedelta(minutes=int(x)))
-
-        #get depature times for the first stop
-        stop_level_joined_clean.loc[stop_level_joined_clean["sequence_number"] == 1, "runtime"] = stop_level_joined_clean['DepartureTime']
-
-        return stop_level_joined_clean
-
-
-    def pivot_clean_stop_level_data(self):
-
-        '''
-        Pivot the cleaned stop level data, to return stop level data in a more
-        usable timetable format; with each unique vehicle journey as a column,
-        and the service code, stop code and sequence number as row headers
-        '''
-
-        #call function to return joined and cleaned stop level data
-        stop_level_clean_pivoted = TimetableExtractor.clean_stop_level_data(self)
-
-        print('Pivoting stop level data... \n')
-
-        #create composite key field within each dataset
-        stop_level_clean_pivoted['ServiceCode_LineName_RevisionNumber'] = stop_level_clean_pivoted['ServiceCode'] +'_'+ stop_level_clean_pivoted['LineName']  +'_'+ stop_level_clean_pivoted['RevisionNumber']
-
-        #select just relevant cols
-        stop_level_clean_pivoted = stop_level_clean_pivoted[['DatasetID','ServiceCode','LineName','RevisionNumber','ServiceCode_LineName_RevisionNumber', 'VehicleJourneyCode','sequence_number','stop_from','runtime']].drop_duplicates()
-                                                             #,'Longitude','Latitude',]].drop_duplicates()
-
-        #handle entries where exact same service line revision number combo appears in multiple files - take just the first file's runtime in these cases
-        stop_level_clean_pivoted = stop_level_clean_pivoted.groupby(['DatasetID','ServiceCode_LineName_RevisionNumber','ServiceCode','LineName','RevisionNumber','sequence_number','stop_from','VehicleJourneyCode']).first().reset_index()
-
-        #pivot by vehicle code
-        stop_level_clean_pivoted = stop_level_clean_pivoted.pivot(index=['DatasetID','ServiceCode_LineName_RevisionNumber','ServiceCode','LineName','RevisionNumber','sequence_number','stop_from'],columns='VehicleJourneyCode', values = 'runtime')
-
-        return stop_level_clean_pivoted
-
-    def generate_timetable(self):
-
-        '''
-        Return a dictionary of timetable like dataframes, with each unique vehicle journey as a column,
-        and the service code, stop code and sequence number as row headers.
-        The dictionary key is composed of DatasetID, ServiceCode, LineName, RevisionNumber all separated 
-        by '_'. The values are the timetable dataframes.
-        
-        '''
-
-        #call function to return  pivoted stop level data
-        stop_level_clean_pivoted = TimetableExtractor.pivot_clean_stop_level_data(self)
-
-        #call naptan api so that lat lon can be added later in for loop below
-        #enrich with lat long data from Naptan API
-        print('Calling Naptan API to get lat/lon for each stop... \n')
-
-        naptan = TimetableExtractor.fetch_naptan_data(self)
-        print('Generating timetable... \n')
-
-        #initialise lists to add each service code and its timetable df too
-        list_of_datasets = []
-        list_of_dfs = []
-        list_of_service_codes = []
-
-        #split for each dataset, so can assign dataset id to each service code
-        for dataset in set(stop_level_clean_pivoted.reset_index()['DatasetID']):
-            timetable_df_pre_pre = stop_level_clean_pivoted.loc[[dataset]].dropna(axis=1, how='all')
-
-            #split for each service code, so that final timetable output is specific to each service code
-            for service in set(timetable_df_pre_pre.reset_index()['ServiceCode_LineName_RevisionNumber']):
-                timetable_df_pre = timetable_df_pre_pre.loc[(slice(None),[service]),:].dropna(axis=1, how='all')
-                timetable_df = pd.DataFrame(index=timetable_df_pre.index)
-
-                #for each col (vehicle journey), add each time delta to the depature time to find the time of each stop
-                #to do this nas (representing the bus not stopping at a certain stop, or not at the sequence number) must be removed
-                #these must later be added to ensure the timetable is correct across multiple journeys
-                for c in timetable_df_pre.columns:
-                    timetable_df_temp = timetable_df_pre[c]
-                    timetable_df_temp.dropna(inplace=True)
-
-                    #add times together
-                    timetable_df_temp = timetable_df_temp.cumsum()
-                    #join back to main df
-                    timetable_df = timetable_df.merge(timetable_df_temp,how='left',left_index=True,right_index=True)
-
-                #set base datetime for deltas to be added too
-                base_time = datetime.datetime(1900,1,1,0,0,0)
-                timetable_df = timetable_df.applymap(lambda x: x + base_time)
-
-                #convert back to just times
-                timetable_df.fillna('null',inplace=True)
-                timetable_df=timetable_df.applymap(lambda x: x.strftime('%H:%M') if x != 'null' else np.nan).reset_index()
-
-                #merge to get lon and lat of stop_from 
-                # timetable_df = timetable_df.merge(naptan, how='left',left_on='stop_from',right_on='ATCOCode')
-                timetable_df = naptan.merge(timetable_df, how='right',right_on='stop_from',left_on='ATCOCode')
-
-                del timetable_df['ATCOCode']
-                
-                #get columns in right order
-                timetable_df = timetable_df.set_index(['DatasetID','ServiceCode_LineName_RevisionNumber','ServiceCode','LineName','RevisionNumber','sequence_number','stop_from'])
-                timetable_df = timetable_df.reset_index()
-                
-                #append result for 1 service code to lists
-                list_of_datasets.append(dataset)
-                list_of_dfs.append(timetable_df)
-                list_of_service_codes.append(service)
-
-            #concat lists together
-            self.timetable_dict = {f'{i}_{j}': k for i, j, k in zip(list_of_datasets, list_of_service_codes, list_of_dfs)}
-
-        print('Timetable generated!')
-        return self.timetable_dict
-
-
     def get_user_downloads_folder(self):
         if platform == "win32":
             downloads_folder = str(Path.home() / "Downloads")
 
         elif platform == "darwin" or "linux":
             # for macOS or linux
             downloads_folder = str(os.path.join(Path.home(), "Downloads"))
@@ -1018,290 +499,353 @@
         '''
         Filter the timetable dictionary for a specific service code.
         This can also be used to filter for a specific licence number, or anything else
         in the composite key (DatasetID_ServiceCode_LineName_RevisionNumber), using free
         text arguement.
         '''
 
-        filtered_dict = {k:v for k,v in self.timetable_dict.items() if service_code in k}
+        filtered_dict = {k: v for k, v in self.timetable_dict.items() if service_code in k}
         return filtered_dict
 
-
     def save_metadata_to_csv(self):
         """
         Save metadata table to csv file
         """
-        
-        
-        #ensure no cell value exceeds 32,767 characters (this is excel limit)
+
+        # ensure no cell value exceeds 32,767 characters (this is excel limit)
         metadata = self.metadata
         metadata['localities'] = metadata['localities'].apply(lambda x: x[0:400])
 
-        
         destination = TimetableExtractor.create_today_folder(self)
         metadata.to_csv(f'{destination}/metadata.csv', index=False)
 
-
     def save_service_line_extract_to_csv(self):
         """
         Save service line table to csv file
         """
 
         destination = TimetableExtractor.create_today_folder(self)
         self.service_line_extract.to_csv(f'{destination}/service_line_extract.csv', index=False)
 
     def save_all_timetables_to_csv(self):
 
         '''
         Save all timetables from the timetable_dict attribute as local csv files.
         '''
 
-        #create folder to save timetables int and get name of new folder
+        # create folder to save timetables int and get name of new folder
         destination = TimetableExtractor.create_today_folder(self)
 
-        for k,v in self.timetable_dict.items():
-            print (f'writing {k} to csv...')
+        for k, v in self.my_bus_data_object.stop_level_extract.items():
+            print(f'writing {k} to csv...')
             k = str(k)
-            k = k.replace(':','_')
+            k = k.replace(':', '_')
             v.to_csv(f'{destination}/{k}_timetable.csv', index=False)
 
+    def save_dataframe_to_csv(self,dataframe, column_name, folder_path):
+        '''
+        Create the name of the timetable file and save the timetable to the project folder in the specified folders "outbound_timetable_folder" and "inbound_timetable_folder"
+        '''
+
+        if not os.path.exists(folder_path):
+            os.makedirs(folder_path)
+
+        for index, row in dataframe.iterrows():
+            #Create a dataframe from the specified column name, either for inbound or outbound timetables
+            df = row[column_name]
+            #Extract information for each timetable
+            ServiceCode=str(dataframe.loc[index, "ServiceCode"])
+            LineName=str(dataframe.loc[index, "LineName"])
+            OperatingDays = str(dataframe.loc[index, "OperatingDays"])
+            RevisionNumber = str(dataframe.loc[index, "RevisionNumber"])
+            Filename=str(dataframe.loc[index, "FileName"])
+
+            #Clean the data gathered above so that it can be saved
+            Filename=(Filename.split("\\")[-1]).replace(".xml","")
+            Filename = Filename.replace(":", ";")
+            ServiceCode = ServiceCode.replace(":", ";")
+
+            #Shorten the filename if it exceeds 80 characters
+            if len(Filename)>80:
+                Filename=Filename[:77]
+            else:
+                pass
+
+            #Create the name of the timetable file
+            timetable_file= ServiceCode+"-"+LineName+"_"+OperatingDays+"_"+"RN-"+RevisionNumber+"-"+Filename
+
+            #If the dataframe is empty, continue
+            if df.empty:
+                continue
+            else:
+                #If the service doesn't exist, create a folder for it, otherwise save the new timetable inside of it
+                if not os.path.exists(folder_path + "/" + ServiceCode):
+                    os.makedirs(folder_path + "/" + ServiceCode)
+                csv_file_path = os.path.join(folder_path, ServiceCode, f"{''}{timetable_file}.csv")
+
+                df.to_csv(csv_file_path, index=False)
+                print(f"Saved {timetable_file}.csv to {folder_path}")
+
+    def save_timetables(self):
+        '''
+        Save the timetable dataframe to a csv file, seperated into inbound and outbound journeys
+        '''
+
+        df = self.stop_level_extract
+        self.save_dataframe_to_csv(df, 'collated_timetable_outbound', 'outbound_timetable_folder')
+        self.save_dataframe_to_csv(df, 'collated_timetable_inbound', 'inbound_timetable_folder')
+
 
     def save_filtered_timetables_to_csv(self, service_code):
 
         '''
         Save a filtered subset of timetables from the timetable_dict attribute as local csv files.
         The timetable dictionary can be filtered for a specific service code.
         This can also be used to filter for a specific licence number, or anything else
         in the composite key (DatasetID_ServiceCode_LineName_RevisionNumber), using free
         text argument.
         '''
 
-        #create folder to save timetables int and get name of new folder
+        # create folder to save timetables int and get name of new folder
         destination = TimetableExtractor.create_today_folder(self)
 
-
         filtered_dict = TimetableExtractor.filter_timetable_dict(self, service_code)
 
         for k, v in filtered_dict.items():
-            print (f'writing {k} to csv...')
+            print(f'writing {k} to csv...')
             k = str(k)
-            k = k.replace(':','_')
+            k = k.replace(':', '_')
             v.to_csv(f'{destination}/{k}_timetable.csv', index=False)
-            
-            
+
     def visualise_service_line(self, service_code):
         '''
        Visualise the route and timings of vehicle journeys from a specified
        service code.
         '''
-        
-        #filter dictionary of dataframes to just service code of interest and access df
+
+        # filter dictionary of dataframes to just service code of interest and access df
         filtered_dict = TimetableExtractor.filter_timetable_dict(self, service_code)
         for k, v in filtered_dict.items():
             df = v
 
-        #df must be processed from wide to long for visualisation
-        df_melt = pd.melt(df, id_vars=['DatasetID','ServiceCode_LineName_RevisionNumber','ServiceCode','LineName','RevisionNumber','sequence_number','stop_from','CommonName','Longitude','Latitude'])
-        #remove nulls that represent where a bus doesnt stop at that stop
+        # df must be processed from wide to long for visualisation
+        df_melt = pd.melt(df, id_vars=['DatasetID', 'ServiceCode_LineName_RevisionNumber', 'ServiceCode', 'LineName',
+                                       'RevisionNumber', 'sequence_number', 'stop_from', 'CommonName', 'Longitude',
+                                       'Latitude'])
+        # remove nulls that represent where a bus doesnt stop at that stop
         df_melt = df_melt.dropna(subset=['value'])
-        
-        #get names of service, line, revision number needed for the title of the viz
+
+        # get names of service, line, revision number needed for the title of the viz
         service_code = df_melt['ServiceCode'].iloc[0]
         line_name = df_melt['LineName'].iloc[0]
         revision_number = df_melt['RevisionNumber'].iloc[0]
-        
-        #create geo df 
+
+        # create geo df
         geometry = [Point(xy) for xy in zip(df_melt['Longitude'], df_melt['Latitude'])]
-        gdf = GeoDataFrame(df_melt, geometry=geometry)   
+        gdf = GeoDataFrame(df_melt, geometry=geometry)
 
-        #create viz
-        pio.renderers.default='browser'
+        # create viz
+        pio.renderers.default = 'browser'
         fig = px.line_mapbox(
             lat=gdf.geometry.y,
             lon=gdf.geometry.x,
             color=gdf.variable
-            ,hover_data={'Stop name':gdf.CommonName,'Stop number':gdf.sequence_number, 'time at stop':gdf.value,}
-            ,title = f'Vehicle Journeys (VJ) for: Service code - {service_code}, Line - {line_name}, File revision number - {revision_number}'
+            , hover_data={'Stop name': gdf.CommonName, 'Stop number': gdf.sequence_number, 'time at stop': gdf.value, }
+            ,
+            title=f'Vehicle Journeys (VJ) for: Service code - {service_code}, Line - {line_name}, File revision number - {revision_number}'
         ).update_traces(mode="lines+markers").update_layout(
             mapbox={
                 "style": "carto-positron",
                 "zoom": 12,
             },
             margin={"l": 25, "r": 25, "t": 50},
         )
-            
+
         print('\nTimetable visualised in browser!')
         return fig.show()
 
-# =============================================================================
-#       REPORTING FUNCTIONS
-# =============================================================================
+    # =============================================================================
+    #       REPORTING FUNCTIONS
+    # =============================================================================
 
     def red_dq_scores(self):
         ''' returns number of operators in a table with red dq scores as well as which ones'''
 
         red_score = self.metadata.query('dq_rag == "red"')
 
         red_count = red_score['operator_name'].unique()
 
         datasets = red_score['url']
 
         dataset_ids = red_score['id']
 
         print(f'\nNumber of operators with red dq score: {len(red_count)}')
-        print(*red_count, sep = ', ')
+        print(*red_count, sep=', ')
         print(f'\nNumber of datasets with red dq score: {len(red_score)}')
-        print(*datasets, sep = ', ')
+        print(*datasets, sep=', ')
 
         return red_score
-    
 
     def dq_less_than_x(self, score):
 
         ''' returns number of operators in a table with dq scores less than input amount'''
 
         self.metadata['dq_score'] = self.metadata['dq_score'].astype(str)
         self.metadata['dq_score'] = self.metadata['dq_score'].str.rstrip('%').astype('float')
 
         score_filter = self.metadata.query(f'dq_score < {score}')
 
         output = score_filter['operator_name'].unique()
-        
-        datasets = score_filter['url']
 
+        datasets = score_filter['url']
 
         print(f'\nNumber of operators with dq score less than {score}: {len(output)}')
-        print(*output, sep = ', ')
-        
-        print(f'\nNumber of datasets with dq score less than {score}: {len(score_filter)}')
-        print(*datasets, sep = ', ')
+        print(*output, sep=', ')
 
+        print(f'\nNumber of datasets with dq score less than {score}: {len(score_filter)}')
+        print(*datasets, sep=', ')
 
         return score_filter
 
     def no_licence_no(self):
         '''how many files have no licence number'''
 
-        #analytical_data = TimetableExtractor.analytical_timetable_data(self)
-        grouped = self.service_line_extract_with_stop_level_json[self.service_line_extract_with_stop_level_json['LicenceNumber'].map(len) == 0]
-
-        datasets = grouped['URL'].unique()
-
-        print(f'\nNumber of datasets with files containing no licence number: {len(datasets)}')
-        print(*datasets, sep = ', ')
-
-        return grouped
-
+        no_licence_number_total=self.service_line_extract_with_stop_level_json['LicenceNumber'].isna().sum()
 
-# =============================================================================
-#     ## DFT Reporting ###
-# =============================================================================
+        if no_licence_number_total<=0:
+            # analytical_data = TimetableExtractor.analytical_timetable_data(self)
+            grouped = self.service_line_extract_with_stop_level_json[
+                self.service_line_extract_with_stop_level_json['LicenceNumber'].map(len) == 0]
+            datasets = grouped['URL'].unique()
+            print(f'\nNumber of datasets with files containing no licence number: {len(datasets)}')
+            print(*datasets, sep=', ')
+            return grouped
+
+        elif no_licence_number_total>0:
+            print(f'\nNumber of datasets with files containing no licence number: {no_licence_number_total}')
+            return no_licence_number_total
+
+
+    # =============================================================================
+    #     ## DFT Reporting ###
+    # =============================================================================
 
     def count_operators(self):
-        ''' 
+        '''
         returns count of distinct operators (measured by operator_name) in a chosen dataset
         '''
         num_ops = len(self.metadata['operator_name'].unique())
         print(f'\nNumber of distinct operator names in chosen dataset: {num_ops}\n')
         return num_ops
 
-
     def count_service_codes(self):
-        ''' 
+        '''
         returns count of unique service codes chosen dataset
         '''
-        non_null_service_codes = self.service_line_extract_with_stop_level_json[self.service_line_extract_with_stop_level_json['ServiceCode'] != None]
+        non_null_service_codes = self.service_line_extract_with_stop_level_json[
+            self.service_line_extract_with_stop_level_json['ServiceCode'] != None]
         unique_service_codes = len(non_null_service_codes['ServiceCode'].unique())
         print(f'\nNumber of unique service codes in chosen dataset: {unique_service_codes}\n')
         return unique_service_codes
 
     def valid_service_codes(self):
-        ''' 
+        '''
         returns count of unique and valid service codes chosen dataset, a dataframe with all the records with valid service codes
         and a dataframe with all the invalid service codes.
         '''
-        #left 2 are characters
-        correct_service_code = self.service_line_extract_with_stop_level_json[self.service_line_extract_with_stop_level_json['ServiceCode'].str[:2].str.isalpha()==True]
-        #10th is colon
-        correct_service_code = correct_service_code[correct_service_code['ServiceCode'].str[9:10]==':']
-        #> than 10 characters
+        # left 2 are characters
+        correct_service_code = self.service_line_extract_with_stop_level_json[
+            self.service_line_extract_with_stop_level_json['ServiceCode'].str[:2].str.isalpha() == True]
+        # 10th is colon
+        correct_service_code = correct_service_code[correct_service_code['ServiceCode'].str[9:10] == ':']
+        # > than 10 characters
         correct_service_code = correct_service_code[correct_service_code['ServiceCode'].str.len() > 10]
-        #unreg must be handled differently
+        # unreg must be handled differently
         correct_service_code_unreg = correct_service_code[correct_service_code['ServiceCode'].str[:2] == 'UZ']
         correct_service_code_reg = correct_service_code[correct_service_code['ServiceCode'].str[:2] != 'UZ']
-        #next 7 are int unless first two of whole thing are UZ
-        correct_service_code_reg = correct_service_code_reg[correct_service_code_reg['ServiceCode'].str[2:9].str.isnumeric()==True]
-        #right after colon are int, unless first two of whole thing are UZ
-        correct_service_code_reg = correct_service_code_reg[correct_service_code_reg['ServiceCode'].str[10:].str.isnumeric()==True]
-        correct_service_code_final = pd.concat([correct_service_code_reg,correct_service_code_unreg])
+        # next 7 are int unless first two of whole thing are UZ
+        correct_service_code_reg = correct_service_code_reg[
+            correct_service_code_reg['ServiceCode'].str[2:9].str.isnumeric() == True]
+        # right after colon are int, unless first two of whole thing are UZ
+        correct_service_code_reg = correct_service_code_reg[
+            correct_service_code_reg['ServiceCode'].str[10:].str.isnumeric() == True]
+        correct_service_code_final = pd.concat([correct_service_code_reg, correct_service_code_unreg])
 
-        #return the invalid service codes
+        # return the invalid service codes
         valid_serv = correct_service_code_final[['ServiceCode']]
         all_serv = self.service_line_extract_with_stop_level_json[['ServiceCode']]
-        invalid_serv = all_serv[~all_serv.apply(tuple,1).isin(valid_serv.apply(tuple,1))]
-        invalid_service_codes = invalid_serv.merge(self.service_line_extract_with_stop_level_json,how='left',on='ServiceCode')
+        invalid_serv = all_serv[~all_serv.apply(tuple, 1).isin(valid_serv.apply(tuple, 1))]
+        invalid_service_codes = invalid_serv.merge(self.service_line_extract_with_stop_level_json, how='left',
+                                                   on='ServiceCode')
 
         unique_valid_service_codes = len(correct_service_code_final['ServiceCode'].unique())
         print(f'\nNumber of unique valid service codes in chosen dataset: {unique_valid_service_codes}\n')
         return correct_service_code_final, invalid_service_codes
 
     def services_published_in_TXC_2_4(self):
-        ''' 
-        returns percentage of services published in TXC 2.4 schema, and a dataframe of these records, and a dataframe of the records 
+        '''
+        returns percentage of services published in TXC 2.4 schema, and a dataframe of these records, and a dataframe of the records
         that are not published in this schema
         '''
-        count_published_in_2_4_schema = len(self.service_line_extract_with_stop_level_json[self.service_line_extract_with_stop_level_json['SchemaVersion']=='2.4'])
-        TXC_2_4_schema = self.service_line_extract_with_stop_level_json[self.service_line_extract_with_stop_level_json['SchemaVersion']=='2.4']
-        not_TXC_2_4_schema = self.service_line_extract_with_stop_level_json[self.service_line_extract_with_stop_level_json['SchemaVersion']!='2.4']
-        perc_published_in_2_4_schema = (count_published_in_2_4_schema / len(self.service_line_extract_with_stop_level_json)) * 100
+        count_published_in_2_4_schema = len(self.service_line_extract_with_stop_level_json[
+                                                self.service_line_extract_with_stop_level_json[
+                                                    'SchemaVersion'] == '2.4'])
+        TXC_2_4_schema = self.service_line_extract_with_stop_level_json[
+            self.service_line_extract_with_stop_level_json['SchemaVersion'] == '2.4']
+        not_TXC_2_4_schema = self.service_line_extract_with_stop_level_json[
+            self.service_line_extract_with_stop_level_json['SchemaVersion'] != '2.4']
+        perc_published_in_2_4_schema = (count_published_in_2_4_schema / len(
+            self.service_line_extract_with_stop_level_json)) * 100
         print(f'\nPercentage of services published in TXC 2.4 schema: {perc_published_in_2_4_schema}\n')
         return perc_published_in_2_4_schema, TXC_2_4_schema, not_TXC_2_4_schema
 
     def datasets_published_in_TXC_2_4(self):
-        ''' 
-        returns percentage of datasets published in TXC 2.4 schema, and a dataframe of these records, and a dataframe of the records 
+        '''
+        returns percentage of datasets published in TXC 2.4 schema, and a dataframe of these records, and a dataframe of the records
         that are not published in this schema
         '''
         datasets_schema_pre = self.service_line_extract_with_stop_level_json.copy()
         datasets_schema_pre['SchemaVersion'] = datasets_schema_pre['SchemaVersion'].astype('float')
-        datasets_schema = datasets_schema_pre.groupby('DatasetID').agg({'SchemaVersion':'min'})
-        count_datasets_published_in_2_4_schema = len(datasets_schema[datasets_schema['SchemaVersion']==2.4])
+        datasets_schema = datasets_schema_pre.groupby('DatasetID').agg({'SchemaVersion': 'min'})
+        count_datasets_published_in_2_4_schema = len(datasets_schema[datasets_schema['SchemaVersion'] == 2.4])
         perc_datasets_published_in_2_4_schema = (count_datasets_published_in_2_4_schema / len(datasets_schema)) * 100
-        TXC_2_4_schema = self.service_line_extract_with_stop_level_json[self.service_line_extract_with_stop_level_json['SchemaVersion']=='2.4']
-        not_TXC_2_4_schema = self.service_line_extract_with_stop_level_json[self.service_line_extract_with_stop_level_json['SchemaVersion']!='2.4']
+        TXC_2_4_schema = self.service_line_extract_with_stop_level_json[
+            self.service_line_extract_with_stop_level_json['SchemaVersion'] == '2.4']
+        not_TXC_2_4_schema = self.service_line_extract_with_stop_level_json[
+            self.service_line_extract_with_stop_level_json['SchemaVersion'] != '2.4']
         print(f'\nPercentage of datasets published in TXC 2.4 schema: {perc_datasets_published_in_2_4_schema}\n')
         return perc_datasets_published_in_2_4_schema, TXC_2_4_schema, not_TXC_2_4_schema
 
     def timetables_publishing_mi(self):
-        ''' 
+        '''
         returns high level MI for reporting into DFT on progress
         of publishing of timetables data
         '''
         TimetableExtractor.count_operators(self)
         TimetableExtractor.count_service_codes(self)
         TimetableExtractor.valid_service_codes(self)
         TimetableExtractor.services_published_in_TXC_2_4(self)
         TimetableExtractor.datasets_published_in_TXC_2_4(self)
 
-# =============================================================================
-#     ## OTC reporting - to only be run on all published datasets ###
-# =============================================================================
+    # =============================================================================
+    #     ## OTC reporting - to only be run on all published datasets ###
+    # =============================================================================
 
     def licence_from_sc(self):
         """Returns the licence number from the service code column of the OTC Database
         file input if the service code is properly formatted as a published service code"""
-        
+
         registered_licence_from_sc = self.otc_db['service_code'].str.split(':', expand=True)
         registered_licence_from_sc = pd.Series(registered_licence_from_sc[0])
 
         return registered_licence_from_sc
 
     def registered_published_services_all(self):
         """This function returns a dataframe with two columns: Licence number, taken from the service code column of OTC Database (input) and the number of registered services associated to that licence number in the published data (input) """
-        
+
         # unique licences from service code column in otc_db
         registered_licence_from_sc = self.otc_db['service_code'].str.split(':', expand=True)
         unique_registered_licence_from_sc = pd.Series(registered_licence_from_sc[0])
 
         # a list of licence codes from the published data, derived from the service codes
         published_licence_from_sc = self.service_line_extract['ServiceCode'].str.split(':', expand=True)
         published_licence_from_sc = published_licence_from_sc[0]
@@ -1342,279 +886,774 @@
         '''percentage of registered licences with at least one published service
         Note - only to be run on all published datasets'''
 
         all_services = TimetableExtractor.registered_published_services_all(self)
         published = TimetableExtractor.count_registered_published_services(self)
 
         percentage = round(float((len(published) / len(all_services)) * 100), 2)
-        
-        print(f'\nPercentage of registered licences (on OTC) with at least one published service on BODS: {percentage}%')
+
+        print(
+            f'\nPercentage of registered licences (on OTC) with at least one published service on BODS: {percentage}%')
 
         return f'{percentage}%'
 
     def registered_not_published_services(self):
         '''returns a dataframe of services found in the otc database (input) which are not found in the published data from the api (input)
         Note - only to be run on all published datasets'''
-        
+
         service_line_lite = self.service_line_extract[
             ['DatasetID', 'OperatorName', 'bods_compliance', 'NOC', 'TradingName', 'LicenceNumber', 'OperatorShortName',
              'OperatorCode', 'ServiceCode']]
 
         full_merge = self.otc_db[['service_code', 'op_name', 'lic_no', 'auth_description']].merge(service_line_lite,
-                                                                                             how='outer',
-                                                                                             right_on='ServiceCode',
-                                                                                             left_on='service_code')
+                                                                                                  how='outer',
+                                                                                                  right_on='ServiceCode',
+                                                                                                  left_on='service_code')
         not_published_full = full_merge[full_merge['ServiceCode'].isnull()]
         not_published = not_published_full[['service_code', 'op_name', 'lic_no', 'auth_description']]
 
         not_published = not_published.drop_duplicates()
 
         print(f'\nNumber of service codes in OTC database that are not published on BODS: {len(not_published)}')
-        
+
         return not_published
 
     def published_not_registered_services(self):
         '''returns a dataframe of services found in the published data from the api (input) which are not found in the otc database (input)
         Note - only to be run on all published datasets'''
-        
+
         service_line_lite = self.service_line_extract[
             ['DatasetID', 'OperatorName', 'bods_compliance', 'NOC', 'TradingName', 'LicenceNumber', 'OperatorShortName',
              'OperatorCode', 'ServiceCode', ]]
 
         full_merge = self.otc_db[['service_code', 'op_name', 'lic_no', 'auth_description']].merge(service_line_lite,
-                                                                                             how='outer',
-                                                                                             right_on='ServiceCode',
-                                                                                             left_on='service_code')
+                                                                                                  how='outer',
+                                                                                                  right_on='ServiceCode',
+                                                                                                  left_on='service_code')
 
         not_registered_full = full_merge[full_merge['service_code'].isnull()]
         not_registered = not_registered_full[
             ['DatasetID', 'OperatorName', 'bods_compliance', 'NOC', 'TradingName', 'LicenceNumber', 'OperatorShortName',
              'OperatorCode', 'ServiceCode']]
 
         not_registered = not_registered.drop_duplicates()
-        
+
         print(f'\nNumber of service codes published on BODS not in OTC database: {len(not_registered)}')
 
         return not_registered
-        
+
     def services_on_bods_or_otc_by_area(self):
         '''
         Generates a dataframe of all service codes published on BODS and/or
-        in the OTC database, indicates whether they are published on both or one 
+        in the OTC database, indicates whether they are published on both or one
         of BODS and OTC, and provides the admin area the services has stops within
         Note - only to be run on all published datasets
         '''
 
         # read in lookup file from repo that links admin areas to ATCO codes
 
-        #try except ensures that this reads in lookup file whether pip installing the library, or cloning the repo from GitHub
+        # try except ensures that this reads in lookup file whether pip installing the library, or cloning the repo from GitHub
         try:
-            #import the csv file as a text string from the BODSDataExtractor package
+            # import the csv file as a text string from the BODSDataExtractor package
             atco_lookup_file = importlib.resources.read_text('BODSDataExtractor',
                                                              'BODSDataExtractor/ATCO_code_to_LA_lookup.csv')
-            #wrap lookup_file string into a stringIO object so it can be read by pandas
+            # wrap lookup_file string into a stringIO object so it can be read by pandas
             atco_lookup_string = io.StringIO(atco_lookup_file)
 
-            la_lookup = pd.read_csv(atco_lookup_string ,dtype={'ATCO Code':str})
+            la_lookup = pd.read_csv(atco_lookup_string, dtype={'ATCO Code': str})
         except:
-            la_lookup = pd.read_csv('ATCO_code_to_LA_lookup.csv',dtype={'ATCO Code':str})
-    
-
+            la_lookup = pd.read_csv('ATCO_code_to_LA_lookup.csv', dtype={'ATCO Code': str})
 
-        #fetch latest version of OTC database
+        # fetch latest version of OTC database
         otc = self.otc_db.drop_duplicates()
 
-        #enrich OTC data with ATCO code
-        otc_la_merge = otc[['service_code','service_number','op_name','auth_description']].merge(la_lookup[['Auth_Description','ATCO Code']], how='left', right_on= 'Auth_Description', left_on= 'auth_description').drop_duplicates()
+        # enrich OTC data with ATCO code
+        otc_la_merge = otc[['service_code', 'service_number', 'op_name', 'auth_description']].merge(
+            la_lookup[['Auth_Description', 'ATCO Code']], how='left', right_on='Auth_Description',
+            left_on='auth_description').drop_duplicates()
+
+        # call full BODS timetables data extract and enrich with admin area name
+        bods_la_merge = self.service_line_extract_with_stop_level_json[
+            ['ServiceCode', 'LineName', 'la_code', 'OperatorName']].merge(
+            la_lookup[['Admin Area Name associated with ATCO Code', 'ATCO Code']], how='left', right_on='ATCO Code',
+            left_on='la_code').drop_duplicates()
 
-        #call full BODS timetables data extract and enrich with admin area name
-        bods_la_merge = self.service_line_extract_with_stop_level_json[['ServiceCode','LineName','la_code','OperatorName']].merge(la_lookup[['Admin Area Name associated with ATCO Code','ATCO Code']], how='left', right_on= 'ATCO Code', left_on= 'la_code').drop_duplicates()
-
-        #add cols to distinguish if in otc and if in bods
+        # add cols to distinguish if in otc and if in bods
         otc_la_merge['in'] = 1
         bods_la_merge['in'] = 1
 
-        #ensure linename col is consistent across bods and otc
-        otc_la_merge.rename(columns = {'service_number':'LineName'}, inplace = True)
-        
-        #merge OTC service level data with BODS service level data
+        # ensure linename col is consistent across bods and otc
+        otc_la_merge.rename(columns={'service_number': 'LineName'}, inplace=True)
+
+        # merge OTC service level data with BODS service level data
         full_service_code_with_atco = otc_la_merge[
             ['service_code', 'LineName', 'op_name', 'ATCO Code', 'in', 'auth_description']].add_suffix('_otc').merge(
             bods_la_merge.add_suffix('_bods'), how='outer', right_on=['ServiceCode_bods', 'ATCO Code_bods'],
             left_on=['service_code_otc', 'ATCO Code_otc']).drop_duplicates()
 
-        #coalesce service code and atco code cols
-        full_service_code_with_atco['service_code'] = full_service_code_with_atco['service_code_otc'].combine_first(full_service_code_with_atco['ServiceCode_bods'])
-        full_service_code_with_atco['atco_code'] = full_service_code_with_atco['ATCO Code_otc'].combine_first(full_service_code_with_atco['ATCO Code_bods'])
+        # coalesce service code and atco code cols
+        full_service_code_with_atco['service_code'] = full_service_code_with_atco['service_code_otc'].combine_first(
+            full_service_code_with_atco['ServiceCode_bods'])
+        full_service_code_with_atco['atco_code'] = full_service_code_with_atco['ATCO Code_otc'].combine_first(
+            full_service_code_with_atco['ATCO Code_bods'])
 
-        #keep only necessary cols
+        # keep only necessary cols
         full_service_code_with_atco = full_service_code_with_atco[
             ['service_code', 'LineName_otc', 'LineName_bods', 'op_name_otc', 'OperatorName_bods', 'atco_code', 'in_otc',
              'in_bods', 'auth_description_otc']]
 
-        #add admin area name
-        full_service_code_with_atco = full_service_code_with_atco.merge(la_lookup[['Admin Area Name associated with ATCO Code','ATCO Code']],how='left',left_on='atco_code',right_on='ATCO Code').drop_duplicates()
+        # add admin area name
+        full_service_code_with_atco = full_service_code_with_atco.merge(
+            la_lookup[['Admin Area Name associated with ATCO Code', 'ATCO Code']], how='left', left_on='atco_code',
+            right_on='ATCO Code').drop_duplicates()
 
-        #remove dupicate atco code col
+        # remove dupicate atco code col
         del full_service_code_with_atco['ATCO Code']
 
-        #replace nans with 0s (necessary for mi reporting calculations)
+        # replace nans with 0s (necessary for mi reporting calculations)
         full_service_code_with_atco['in_otc'] = full_service_code_with_atco['in_otc'].fillna(0)
         full_service_code_with_atco['in_bods'] = full_service_code_with_atco['in_bods'].fillna(0)
-        
-        #format line nos into desired list format, so as to not explode rest of dataframe
-        #replace nulls with string so groupby doesnt omit them
+
+        # format line nos into desired list format, so as to not explode rest of dataframe
+        # replace nulls with string so groupby doesnt omit them
         full_service_code_with_atco['LineName_bods'] = full_service_code_with_atco['LineName_bods'].fillna('xxxxx')
-        #groupby to concat the bods line nos together
+        # groupby to concat the bods line nos together
         full_service_code_with_atco = full_service_code_with_atco.groupby(
             ['service_code', 'LineName_otc', 'op_name_otc', 'OperatorName_bods', 'atco_code', 'in_otc', 'in_bods',
              'auth_description_otc', 'Admin Area Name associated with ATCO Code'], as_index=False, dropna=False).agg(
             {'LineName_bods': lambda x: ','.join(x)})
-        #regenerate the nulls
-        full_service_code_with_atco['LineName_bods'] = full_service_code_with_atco['LineName_bods'].replace('xxxxx',None)
-        #reorder cols
+        # regenerate the nulls
+        full_service_code_with_atco['LineName_bods'] = full_service_code_with_atco['LineName_bods'].replace('xxxxx',
+                                                                                                            None)
+        # reorder cols
         full_service_code_with_atco = full_service_code_with_atco[
             ['service_code', 'LineName_otc', 'LineName_bods', 'op_name_otc', 'OperatorName_bods', 'atco_code', 'in_otc',
              'in_bods', 'auth_description_otc', 'Admin Area Name associated with ATCO Code']]
         return full_service_code_with_atco
 
     def services_on_bods_or_otc_by_area_mi(self):
         '''
         Generates MI from dataframe that lists all service codes from BODS and/or
         OTC database, by admin area. Specifically notes the number of services from
         these sources, and the fraction of all within BODS and OTC respectively.
         Note - only to be run on all published datasets
         '''
 
         full_service_code_with_atco = TimetableExtractor.services_on_bods_or_otc_by_area(self)
-        service_atco_mi = full_service_code_with_atco.groupby('atco_code').agg({'service_code':'count'
-                                                                                     ,'Admin Area Name associated with ATCO Code':'first'
-                                                                                     ,'in_otc':'mean'
-                                                                                     , 'in_bods':'mean'})
+        service_atco_mi = full_service_code_with_atco.groupby('atco_code').agg({'service_code': 'count'
+                                                                                   ,
+                                                                                'Admin Area Name associated with ATCO Code': 'first'
+                                                                                   , 'in_otc': 'mean'
+                                                                                   , 'in_bods': 'mean'})
 
-        service_atco_mi.rename(columns={'service_code':'count_services'},inplace=True)
+        service_atco_mi.rename(columns={'service_code': 'count_services'}, inplace=True)
 
-        #round fractions to 2 decimals 
+        # round fractions to 2 decimals
         service_atco_mi = service_atco_mi.round(2)
 
         return service_atco_mi
-    
-    
+
     def services_on_bods_or_otc_by_area_just_otc(self):
         '''
         Generates a dataframe of all service codes published
-        in the OTC database, indicates whether they are published on 
+        in the OTC database, indicates whether they are published on
         BODS as well, and provides the admin area the services has stops within
         Note - only to be run on all published datasets
         '''
 
         # read in lookup file from repo that links admin areas to ATCO codes
 
-        #try except ensures that this reads in lookup file whether pip installing the library, or cloning the repo from GitHub
+        # try except ensures that this reads in lookup file whether pip installing the library, or cloning the repo from GitHub
         try:
-            #import the csv file as a text string from the BODSDataExtractor package
+            # import the csv file as a text string from the BODSDataExtractor package
             atco_lookup_file = importlib.resources.read_text('BODSDataExtractor',
                                                              'BODSDataExtractor/ATCO_code_to_LA_lookup.csv')
-            #wrap lookup_file string into a stringIO object so it can be read by pandas
+            # wrap lookup_file string into a stringIO object so it can be read by pandas
             atco_lookup_string = io.StringIO(atco_lookup_file)
 
-            la_lookup = pd.read_csv(atco_lookup_string ,dtype={'ATCO Code':str})
-
+            la_lookup = pd.read_csv(atco_lookup_string, dtype={'ATCO Code': str})
 
-            
-        except:
-            la_lookup = pd.read_csv('ATCO_code_to_LA_lookup.csv',dtype={'ATCO Code':str})
 
 
+        except:
+            la_lookup = pd.read_csv('ATCO_code_to_LA_lookup.csv', dtype={'ATCO Code': str})
 
-        #fetch latest version of OTC database
+        # fetch latest version of OTC database
         otc = self.otc_db.drop_duplicates()
 
-        #enrich OTC data with ATCO code
-        otc_la_merge = otc[['service_code','service_number','op_name','auth_description']].merge(la_lookup[['Auth_Description','ATCO Code']], how='left', right_on= 'Auth_Description', left_on= 'auth_description').drop_duplicates()
+        # enrich OTC data with ATCO code
+        otc_la_merge = otc[['service_code', 'service_number', 'op_name', 'auth_description']].merge(
+            la_lookup[['Auth_Description', 'ATCO Code']], how='left', right_on='Auth_Description',
+            left_on='auth_description').drop_duplicates()
+
+        # call full BODS timetables data extract and enrich with admin area name
+        bods_la_merge = self.service_line_extract_with_stop_level_json[
+            ['ServiceCode', 'LineName', 'la_code', 'OperatorName']].merge(
+            la_lookup[['Admin Area Name associated with ATCO Code', 'ATCO Code']], how='left', right_on='ATCO Code',
+            left_on='la_code').drop_duplicates()
 
-        #call full BODS timetables data extract and enrich with admin area name
-        bods_la_merge = self.service_line_extract_with_stop_level_json[['ServiceCode','LineName','la_code','OperatorName']].merge(la_lookup[['Admin Area Name associated with ATCO Code','ATCO Code']], how='left', right_on= 'ATCO Code', left_on= 'la_code').drop_duplicates()
-
-        #add cols to distinguish if in otc and if in bods
+        # add cols to distinguish if in otc and if in bods
         otc_la_merge['in'] = 1
         bods_la_merge['in'] = 1
 
-        #ensure linename col is consistent across bods and otc
-        otc_la_merge.rename(columns = {'service_number':'LineName'}, inplace = True)
-        
-        #merge OTC service level data with BODS service level data
+        # ensure linename col is consistent across bods and otc
+        otc_la_merge.rename(columns={'service_number': 'LineName'}, inplace=True)
+
+        # merge OTC service level data with BODS service level data
         full_service_code_with_atco = otc_la_merge[
             ['service_code', 'LineName', 'op_name', 'ATCO Code', 'in', 'auth_description']].add_suffix('_otc').merge(
             bods_la_merge.add_suffix('_bods'), how='outer', right_on=['ServiceCode_bods', 'ATCO Code_bods'],
             left_on=['service_code_otc', 'ATCO Code_otc']).drop_duplicates()
 
-        #coalesce service code and atco code cols
-        full_service_code_with_atco['service_code'] = full_service_code_with_atco['service_code_otc'].combine_first(full_service_code_with_atco['ServiceCode_bods'])
-        full_service_code_with_atco['atco_code'] = full_service_code_with_atco['ATCO Code_otc'].combine_first(full_service_code_with_atco['ATCO Code_bods'])
+        # coalesce service code and atco code cols
+        full_service_code_with_atco['service_code'] = full_service_code_with_atco['service_code_otc'].combine_first(
+            full_service_code_with_atco['ServiceCode_bods'])
+        full_service_code_with_atco['atco_code'] = full_service_code_with_atco['ATCO Code_otc'].combine_first(
+            full_service_code_with_atco['ATCO Code_bods'])
 
-        #keep only necessary cols
+        # keep only necessary cols
         full_service_code_with_atco = full_service_code_with_atco[
             ['service_code', 'LineName_otc', 'LineName_bods', 'op_name_otc', 'OperatorName_bods', 'atco_code', 'in_otc',
              'in_bods', 'auth_description_otc']]
 
-        #add admin area name
-        full_service_code_with_atco = full_service_code_with_atco.merge(la_lookup[['Admin Area Name associated with ATCO Code','ATCO Code']],how='left',left_on='atco_code',right_on='ATCO Code').drop_duplicates()
+        # add admin area name
+        full_service_code_with_atco = full_service_code_with_atco.merge(
+            la_lookup[['Admin Area Name associated with ATCO Code', 'ATCO Code']], how='left', left_on='atco_code',
+            right_on='ATCO Code').drop_duplicates()
 
-        #remove dupicate atco code col
+        # remove dupicate atco code col
         del full_service_code_with_atco['ATCO Code']
 
-        #replace nans with 0s (necessary for mi reporting calculations)
+        # replace nans with 0s (necessary for mi reporting calculations)
         full_service_code_with_atco['in_otc'] = full_service_code_with_atco['in_otc'].fillna(0)
         full_service_code_with_atco['in_bods'] = full_service_code_with_atco['in_bods'].fillna(0)
-        
-        #remove services not in otc
-        full_service_code_with_atco = full_service_code_with_atco[full_service_code_with_atco['in_otc']==1]
 
-        #format line nos into desired list format, so as to not explode rest of dataframe
-        #replace nulls with string so groupby doesnt omit them
+        # remove services not in otc
+        full_service_code_with_atco = full_service_code_with_atco[full_service_code_with_atco['in_otc'] == 1]
+
+        # format line nos into desired list format, so as to not explode rest of dataframe
+        # replace nulls with string so groupby doesnt omit them
         full_service_code_with_atco['LineName_bods'] = full_service_code_with_atco['LineName_bods'].fillna('xxxxx')
-        #groupby to concat the bods line nos together
+        # groupby to concat the bods line nos together
         full_service_code_with_atco = full_service_code_with_atco.groupby(
             ['service_code', 'LineName_otc', 'op_name_otc', 'OperatorName_bods', 'atco_code', 'in_otc', 'in_bods',
              'auth_description_otc', 'Admin Area Name associated with ATCO Code'], as_index=False, dropna=False).agg(
             {'LineName_bods': lambda x: ','.join(x)})
-        #regenerate the nulls
-        full_service_code_with_atco['LineName_bods'] = full_service_code_with_atco['LineName_bods'].replace('xxxxx',None)
-        #reorder cols
+        # regenerate the nulls
+        full_service_code_with_atco['LineName_bods'] = full_service_code_with_atco['LineName_bods'].replace('xxxxx',
+                                                                                                            None)
+        # reorder cols
         full_service_code_with_atco = full_service_code_with_atco[
             ['service_code', 'LineName_otc', 'LineName_bods', 'op_name_otc', 'OperatorName_bods', 'atco_code', 'in_otc',
              'in_bods', 'auth_description_otc', 'Admin Area Name associated with ATCO Code']]
         return full_service_code_with_atco
 
     def services_on_bods_or_otc_by_area_mi_just_otc(self):
         '''
         Generates MI of all service codes published
-        in the OTC database, indicates whether they are published on 
+        in the OTC database, indicates whether they are published on
         BODS as well, and provides the admin area the services has stops within
         Note - only to be run on all published datasets
         '''
 
         full_service_code_with_atco = TimetableExtractor.services_on_bods_or_otc_by_area_just_otc(self)
-        service_atco_mi = full_service_code_with_atco.groupby('atco_code').agg({'service_code':'count'
-                                                                                     ,'Admin Area Name associated with ATCO Code':'first'
-                                                                                     ,'in_otc':'mean'
-                                                                                     , 'in_bods':'mean'})
+        service_atco_mi = full_service_code_with_atco.groupby('atco_code').agg({'service_code': 'count'
+                                                                                   ,
+                                                                                'Admin Area Name associated with ATCO Code': 'first'
+                                                                                   , 'in_otc': 'mean'
+                                                                                   , 'in_bods': 'mean'})
 
-        service_atco_mi.rename(columns={'service_code':'count_services'},inplace=True)
+        service_atco_mi.rename(columns={'service_code': 'count_services'}, inplace=True)
 
-        #round fractions to 2 decimals 
+        # round fractions to 2 decimals
         service_atco_mi = service_atco_mi.round(2)
 
         return service_atco_mi
-    
+
+    def extract_timetable_operating_days(self, days):
+        ''' Ensuring the operating days are ordered appropriately '''
+
+        if days is not None:
+            operating_day_list = list(days)
+            if any(day in {"Monday","Tuesday","Wednesday","Thursday","Friday","Saturday","Sunday"} for day in operating_day_list):
+                pass
+            else:
+                operating_days=', '.join(operating_day_list)
+                return operating_days
+
+        else:
+            operating_days= None
+            return operating_days
+
+
+
+        # adding dictionary variables and values to "day" dictionary
+
+        day = {}
+        day['Monday'] = 1
+        day['Tuesday'] = 2
+        day['Wednesday'] = 3
+        day['Thursday'] = 4
+        day['Friday'] = 5
+        day['Saturday'] = 6
+        day['Sunday'] = 7
+
+        brand_new = {}
+
+        # checking if the day of the week is in the above dictionary so we can sort the days
+        for i in operating_day_list:
+            if i in day:
+                brand_new.update({i: day[i]})
+
+            # sorting the days of operation
+        sortit = sorted(brand_new.items(), key=lambda x: x[1])
+
+        length = len(sortit)
+
+        operating_days = ""
+
+        consecutive = True
+
+        # checking to see if the days in the list are not consective
+
+        for i in range(length - 1):
+            if sortit[i + 1][1] - sortit[i][1] != 1:
+                consecutive = False
+                break
+
+        # if there are no days of operation entered
+        if length == 0:
+            operating_days = "None"
+
+        # if there is only one day of operation
+        elif length == 1:
+            operating_days = sortit[0][0]
+
+            # if the operating days are not consecutive, they're seperated by commas
+        elif consecutive:
+            for i in range(length):
+                operating_days = operating_days + sortit[i][0] + ","
+
+            # if consecutive, operating days are given as a range
+        else:
+            # print(sortit)
+            operating_days = sortit[0][0] + "-" + sortit[-1][0]
+
+        return operating_days
+
+    def extract_runtimes(self, vj, journey_pattern_timing_link, vjtl_index):
+
+        """Extract the runtimes from timing links as a string. If JPTL run time is 0, VJTL will be checked"""
+
+        # extract run times from jptl
+        runtime = journey_pattern_timing_link.RunTime
+
+        # if jptl runtime is 0, find equivalent vehicle journey pattern timing link run time
+        if pd.Timedelta(runtime).value == 0:
+
+            if vj.VehicleJourneyTimingLink is not None:
+                runtime = vj.VehicleJourneyTimingLink[vjtl_index[journey_pattern_timing_link.id]].RunTime
+
+                return runtime
+
+        return runtime
+
+    def extract_common_name(self, stop_object, StopPointRef, stop_point_index):
+        """Extract information about the name of the stop including longitude and latitude"""
+
+        stop_common_name = stop_object.AnnotatedStopPointRef[stop_point_index[StopPointRef]].CommonName
+        stop_location = stop_object.AnnotatedStopPointRef[stop_point_index[StopPointRef]].Location
+
+        if not stop_location:
+            stop_lat = "-"
+            stop_long = "-"
+
+        else:
+            stop_lat = stop_object.AnnotatedStopPointRef[stop_point_index[StopPointRef]].Location.Latitude
+            stop_long = stop_object.AnnotatedStopPointRef[stop_point_index[StopPointRef]].Location.Longitude
+
+        return stop_common_name, stop_lat, stop_long
+
+    def next_jptl_in_sequence(self, jptl, vj_departure_time, vj, vjtl_index, stop_object, stop_point_index,
+                              first_jptl=False):
+        """Returns the sequence number, stop point ref and time for a JPTL to be added to a outboud or inbound df"""
+
+        runtime = self.extract_runtimes(vj, jptl, vjtl_index)
+        common_name, latitude, longitude = self.extract_common_name(stop_object, str(jptl.To.StopPointRef),
+                                                                    stop_point_index)
+
+        to_sequence = [int(jptl.To.sequence_number),
+                       str(jptl.To.StopPointRef),
+                       latitude,
+                       longitude,
+                       str(common_name),
+                       pd.Timedelta(runtime)]
+
+        if first_jptl:
+            common_name, latitude, longitude = self.extract_common_name(stop_object, jptl.From.StopPointRef,
+                                                                        stop_point_index)
+
+            from_sequence = [int(jptl.From.sequence_number),
+                             str(jptl.From.StopPointRef),
+                             latitude,
+                             longitude,
+                             str(common_name),
+                             vj_departure_time]
+
+            return from_sequence, to_sequence
+
+        if not first_jptl:
+            return to_sequence
+
+    def collate_vjs(self, direction_df, collated_timetable):
+        """Combines all vehicle journeys together for inbound or outbound"""
+
+        if direction_df.empty:
+            pass
+        elif collated_timetable.empty:
+            # match stop point ref + sequence number with the initial timetable's stop point ref+sequence number
+            collated_timetable = collated_timetable.merge(direction_df, how='outer', left_index=True, right_index=True)
+
+        else:
+
+            if direction_df["Sequence Number"].equals(collated_timetable["Sequence Number"]) and direction_df['Stop Point Ref'].equals(collated_timetable['Stop Point Ref']) and direction_df["Common Name"].equals(collated_timetable["Common Name"]):
+                last_column = direction_df.iloc[:, -1]
+                collated_timetable=pd.concat([collated_timetable, last_column], axis=1)
+
+            else:
+                # match stop point ref + sequence number with the initial timetable's stop point ref+sequence number
+                collated_timetable = pd.merge(collated_timetable, direction_df, on=["Sequence Number",
+                                                                                'Stop Point Ref',
+                                                                                "Latitude",
+                                                                                "Longitude",
+                                                                                "Common Name"],
+                                              validate='1:m', how='outer').fillna("-")
+
+        return collated_timetable
+
+    def reformat_times(self, timetable, vj, base_time):
+        '''Turns the time deltas into time of day, final column is formatted as string'''
+
+        timetable[f"{vj.VehicleJourneyCode}"] = timetable[f"{vj.VehicleJourneyCode}"].cumsum()
+        timetable[f"{vj.VehicleJourneyCode}"] = timetable[f"{vj.VehicleJourneyCode}"].map(lambda x: x + base_time)
+        timetable[f"{vj.VehicleJourneyCode}"] = timetable[f"{vj.VehicleJourneyCode}"].map(lambda x: x.strftime('%H:%M'))
+
+        return timetable[f"{vj.VehicleJourneyCode}"]
+
+    def add_dataframe_headers(self, direction, operating_days, JourneyPattern_id, RouteRef, lineref, JourneyCode):
+        """Populate headers with information associated to each individual VJ"""
+
+        direction.loc[-1] = ["Operating Days ", "->", "->", "->", "->", operating_days]
+        direction.loc[-2] = ["Journey Pattern ", "->", "->", "->", "->", JourneyPattern_id]
+        direction.loc[-3] = ["Journey Code", "->", "->", "->", "->", JourneyCode]
+        direction.loc[-4] = ["RouteID", "->", "->", "->", "->", RouteRef]
+        direction.loc[-5] = ["Line", "->", "->", "->", "->", lineref]
+        direction.index = direction.index + 1  # shifting index
+        direction.sort_index(inplace=True)
+
+        return direction
+
+    def create_journey_pattern_section_object(self, journey_pattern_json):
+
+        if isinstance(journey_pattern_json['JourneyPatternSection'], dict):
+            journey_pattern_json['JourneyPatternSection'] = [journey_pattern_json['JourneyPatternSection']]
+
+        journey_pattern_section_object = from_dict(data_class=JourneyPatternSections, data=journey_pattern_json)
+
+        return journey_pattern_section_object
+
+    def create_vehicle_journey_object(self, vehicle_journey_json):
+
+        if isinstance(vehicle_journey_json['VehicleJourney'], dict):
+            vehicle_journey_json['VehicleJourney'] = [vehicle_journey_json['VehicleJourney']]
+
+        vehicle_journey = from_dict(data_class=VehicleJourneys, data=vehicle_journey_json)
+
+        return vehicle_journey
+
+    def create_service_object(self, services_json):
+
+        if isinstance(services_json['Lines']['Line'], dict):
+            services_json['Lines']['Line'] = [services_json['Lines']['Line']]
+
+        if isinstance(services_json['StandardService']['JourneyPattern'], dict):
+            services_json['StandardService']['JourneyPattern'] = [services_json['StandardService']['JourneyPattern']]
+
+        service_object = from_dict(data_class=Service, data=services_json)
+
+        return service_object
+
+    def create_stop_object(self, stops_json):
+
+        stop_object = from_dict(data_class=StopPoints, data=stops_json)
+
+        return stop_object
+
+    def map_indicies(self, service_object, stop_object, journey_pattern_section_object):
+        """Initialise values to be used when generating timetables"""
+
+        # List of journey patterns in service object
+        journey_pattern_list = service_object.StandardService.JourneyPattern
+
+        # Iterate once through JPs and JPS to find the indices in the list of each id
+        journey_pattern_index = {key.id: value for value, key in
+                                 enumerate(service_object.StandardService.JourneyPattern)}
+        journey_pattern_section_index = {key.id: value for value, key in
+                                         enumerate(journey_pattern_section_object.JourneyPatternSection)}
+
+        # Map stop point refs
+        stop_point_index = {key.StopPointRef: value for value, key in enumerate(stop_object.AnnotatedStopPointRef)}
+
+        return journey_pattern_section_index, journey_pattern_index, journey_pattern_list, stop_point_index
+
+    def create_txc_objects(self):
+
+        self.stop_level_extract = self.service_line_extract_with_stop_level_json.copy(deep=True)
+
+        self.stop_level_extract['vj_objects'] = self.stop_level_extract[
+            'vehicle_journey_json'].apply(self.create_vehicle_journey_object)
+
+        self.stop_level_extract['jps_objects'] = self.stop_level_extract[
+            'journey_pattern_json'].apply(self.create_journey_pattern_section_object)
+
+        self.stop_level_extract['service_object'] = self.stop_level_extract[
+            'services_json'].apply(self.create_service_object)
+
+        self.stop_level_extract['stop_objects'] = self.stop_level_extract[
+            'stops_json'].apply(self.create_stop_object)
+
+    def iterate_vjs(self, service_object, stop_object, vehicle_journey, journey_pattern_section_object,
+                    collated_timetable_outbound, collated_timetable_inbound, base_time, journey_pattern_section_index,
+                    journey_pattern_index, journey_pattern_list, stop_point_index):
+
+        for vj in vehicle_journey.VehicleJourney:
+
+            # take vehicle journey departure time
+            departure_time = pd.Timedelta(vj.DepartureTime)
+
+            vj_columns = ["Sequence Number", "Stop Point Ref", "Latitude", "Longitude", "Common Name",
+                          f"{vj.VehicleJourneyCode}"]
+
+            # init empty timetable for outbound Vehicle journey
+            outbound = pd.DataFrame(columns=vj_columns)
+
+            # init empty timetable for inbound Vehicle journey
+            inbound = pd.DataFrame(columns=vj_columns)
+
+            if vj.LineRef[-1] == ":":
+                lineref = vj.LineRef.split(':')[-2]
+            else:
+                lineref = vj.LineRef.split(':')[-1]
+
+            vjtl_index = {}
+
+            if vj.VehicleJourneyTimingLink is not None:
+                vjtl_index = {key.JourneyPatternTimingLinkRef: value for value, key in
+                              enumerate(vj.VehicleJourneyTimingLink)}
+
+            # Create vars for relevant indices of this vehicle journey
+            vehicle_journey_jp_index = journey_pattern_index[vj.JourneyPatternRef]
+
+            direction = service_object.StandardService.JourneyPattern[vehicle_journey_jp_index].Direction
+            RouteRef = service_object.StandardService.JourneyPattern[vehicle_journey_jp_index].RouteRef
+            JourneyPattern_id = service_object.StandardService.JourneyPattern[vehicle_journey_jp_index].id
+            if vj.Operational is None or vj.Operational.TicketMachine is None:
+                JourneyCode=None
+            else:
+                JourneyCode=str(vj.Operational.TicketMachine.JourneyCode)
+
+            # Get the journey pattern sections for this vehicle journey, can be a single string or a list of strings
+            vehicle_journey_jps_list = service_object.StandardService.JourneyPattern[
+                journey_pattern_index[vj.JourneyPatternRef]].JourneyPatternSectionRefs
+
+            # If there are multiple JPS, put them into a single list for later
+            if isinstance(vehicle_journey_jps_list, list):
+                vehicle_journey_jps_index = [journey_pattern_section_index[jpsr] for jpsr in
+                                             journey_pattern_list[vehicle_journey_jp_index].JourneyPatternSectionRefs]
+                all_jptl = [
+                    [jptl for jptl in journey_pattern_section_object.JourneyPatternSection[x].JourneyPatternTimingLink]
+                    for x in vehicle_journey_jps_index]
+                flat_jptl = [jptl for sublist in all_jptl for jptl in sublist]
+
+            # if just one JPS, find the journey pattern section directly for later
+            else:
+                vehicle_journey_jps_index = journey_pattern_section_index[vehicle_journey_jps_list]
+                flat_jptl = journey_pattern_section_object.JourneyPatternSection[
+                    vehicle_journey_jps_index].JourneyPatternTimingLink
+
+            # Mark the first JPTL
+            first = True
+
+            # Loop through relevant timing links
+
+            for JourneyPatternTimingLink in flat_jptl:
+
+                # first JPTL should use 'From' AND 'To' stop data
+                if first:
+
+                    # remaining JPTLs are not the first one
+                    first = False
+
+                    timetable_sequence = self.next_jptl_in_sequence(JourneyPatternTimingLink,
+                                                                    departure_time,
+                                                                    vj,
+                                                                    vjtl_index,
+                                                                    stop_object,
+                                                                    stop_point_index,
+                                                                    first_jptl=True)
+
+                    # Add first sequence, stop ref and departure time
+                    first_timetable_row = pd.DataFrame([timetable_sequence[0]], columns=outbound.columns)
+
+                    # Add To sequence number and stop point ref to the initial timetable
+
+                    if direction == 'outbound':
+                        outbound = pd.concat([outbound, first_timetable_row], ignore_index=True)
+                        outbound.loc[len(outbound)] = timetable_sequence[1]
+
+                    elif direction == 'inbound':
+                        inbound = pd.concat([inbound, first_timetable_row], ignore_index=True)
+                        inbound.loc[len(inbound)] = timetable_sequence[1]
+                    else:
+                        print(f'Unknown Direction in vehicle journey:{vj}: {direction}')
+
+                # if not first JPTL use 'to' sequence only
+                else:
+                    timetable_sequence = self.next_jptl_in_sequence(JourneyPatternTimingLink, departure_time, vj,
+                                                                    vjtl_index,
+                                                                    stop_object, stop_point_index)
+
+                    if direction == 'outbound':
+                        outbound.loc[len(outbound)] = timetable_sequence
+                    elif direction == 'inbound':
+                        inbound.loc[len(inbound)] = timetable_sequence
+                    else:
+                        print(f'Unknown Direction in vehicle journey:{vj}: {direction}')
+
+            # Fetch operating profile from either service object or vehicle journey
+           # if vj.OperatingProfile is None and service_object.OperatingProfile is not None:
+           #     days = service_object.OperatingProfile.RegularDayType.DaysOfWeek
+           # elif vj.OperatingProfile is not None:
+           #     days = vj.OperatingProfile.RegularDayType.DaysOfWeek
+
+            if vj.OperatingProfile is not None:
+                if vj.OperatingProfile.RegularDayType.DaysOfWeek is not None:
+                    days = vj.OperatingProfile.RegularDayType.DaysOfWeek
+                elif vj.OperatingProfile.BankHolidayOperation is not None:
+                    days = vj.OperatingProfile.BankHolidayOperation.DaysOfOperation
+
+                else:
+                    days = "Days Not Found"
+
+            elif service_object.OperatingProfile is not None:
+                if service_object.OperatingProfile.RegularDayType.DaysOfWeek is not None:
+                    days = service_object.OperatingProfile.RegularDayType.DaysOfWeek
+                elif service_object.OperatingProfile.BankHolidayOperation is not None:
+                    days = service_object.OperatingProfile.BankHolidayOperation.DaysOfOperation
+                else:
+                    days = "Days Not Found"
+            else:
+                days = "Days Not Found"
+
+            if days is None and (service_object.OperatingProfile is None):
+                operating_days = "Error: Check File"
+            else:
+                operating_days = self.extract_timetable_operating_days(days)
+
+            if not outbound.empty:
+                outbound[f"{vj.VehicleJourneyCode}"] = self.reformat_times(outbound, vj, base_time)
+                outbound = self.add_dataframe_headers(outbound, operating_days, JourneyPattern_id, RouteRef, lineref,JourneyCode)
+
+            if not inbound.empty:
+                inbound[f"{vj.VehicleJourneyCode}"] = self.reformat_times(inbound, vj, base_time)
+                inbound = self.add_dataframe_headers(inbound, operating_days, JourneyPattern_id, RouteRef, lineref,JourneyCode)
+
+            # collect vj information together for outbound
+            collated_timetable_outbound = self.collate_vjs(outbound, collated_timetable_outbound)
+
+            # collect vj information together for inbound
+            collated_timetable_inbound = self.collate_vjs(inbound, collated_timetable_inbound)
+
+        collated_timetable_outbound, collated_timetable_inbound = self.organise_timetables(service_object,
+                                                                                           collated_timetable_outbound,
+                                                                                           collated_timetable_inbound)
+
+        return collated_timetable_outbound, collated_timetable_inbound
+
+    def generate_timetable(self):
+
+        """Extracts timetable information for a VJ individually and
+        adds to a collated dataframe of vjs, split by outbound and inbound"""
+        print('Generating Timetables...')
+        # Define a base time to add run times to
+        base_time = datetime.datetime(2000, 1, 1, 0, 0, 0)
+
+        # Dataframe to store all inbound vjs together
+        self.collated_timetable_inbound = pd.DataFrame()
+
+        # Dataframe to store all outbound vjs together
+        self.collated_timetable_outbound = pd.DataFrame()
+
+        self.create_txc_objects()
+
+        print('Mapping service indexes...')
+        # Map Indicies based on objects present on dataframe row
+        self.stop_level_extract[
+            ['jps_index', 'jpindex', 'jplist', 'stop_index']] = self.stop_level_extract.apply(
+            lambda x: TimetableExtractor.map_indicies(self, x.service_object, x.stop_objects,
+                                                      x.jps_objects), axis=1).apply(pd.Series)
+        print('Calculating vehicle journeys...')
+        # Create Inbound and Outbound Timetables based on objects and indices
+        self.stop_level_extract[
+            ['collated_timetable_outbound', 'collated_timetable_inbound']] = self.stop_level_extract.apply(
+            lambda x: TimetableExtractor.iterate_vjs(self, x.service_object,
+                                                     x.stop_objects,
+                                                     x.vj_objects,
+                                                     x.jps_objects,
+                                                     self.collated_timetable_outbound,
+                                                     self.collated_timetable_inbound,
+                                                     base_time,
+                                                     x.jps_index,
+                                                     x.jpindex,
+                                                     x.jplist,
+                                                     x.stop_index), axis=1).apply(pd.Series)
+        # Reduce size of stop level extract
+        self.stop_level_extract = self.stop_level_extract.drop(
+            columns=['dq_score', 'OperatorShortName', 'Status', 'services_json', 'NOC', 'PublicUse', 'TradingName',
+                     'SchemaVersion', 'OperatorName', 'LicenceNumber', 'Origin', 'vehicle_journey_json', 'OperatorCode',
+                     'Destination', 'dq_rag', 'Description', 'Comment', 'FileType', 'bods_compliance',
+                     'journey_pattern_json', 'stops_json', 'OperatingPeriodEndDate', 'la_code', 'vj_objects',
+                     'jps_objects', 'service_object', 'stop_objects', 'jps_index', 'jpindex', 'jplist', 'stop_index'])
+        print('Timetables Generated!')
+
+        #self.stop_level_extract = self.stop_level_extract.to_dict()
+
+        return self.stop_level_extract
+
+    def organise_timetables(self, service_object, collated_timetable_outbound, collated_timetable_inbound):
+        """Ordering the timetables correctly"""
+
+        service_code = str(service_object.ServiceCode)
+
+        if not collated_timetable_outbound.empty:
+
+            # ensuring the sequence numbers are sorted in ascending order
+            collated_timetable_outbound.iloc[5:] = collated_timetable_outbound.iloc[5:].sort_values(by="Sequence Number"
+                                                                                                    , ascending=True)
+
+        if not collated_timetable_inbound.empty:
+
+            collated_timetable_inbound.iloc[5:] = collated_timetable_inbound.iloc[5:].sort_values(by="Sequence Number"
+                                                                                                  , ascending=True)
+
+        return collated_timetable_outbound, collated_timetable_inbound
+
+
 class xmlDataExtractor:
-    
-    
-    
+
     def __init__(self, filepath):
         self.root = ET.parse(filepath).getroot()
         self.namespace = self.root.nsmap
 
     def extract_service_level_info(self):
         filename = self.extract_filename()
         noc = self.extract_noc()
@@ -1651,356 +1690,341 @@
             operating_period_end_date,
             schema_version,
             revision_number,
             la_code,
         ]
 
     def extract_filename(self):
-        
+
         ''''
         Return the filename of a file extracted from the BODS platform.
         '''
-        
+
         try:
-        
+
             return self.root.attrib['FileName']
-        
+
         except:
-            return 'Not Found'        
+            return 'Not Found'
 
-    
     def extract_noc(self):
-        
+
         ''''
         Extracts the National Operator Code from an xml file in a given location with a known namespace
         Namespace can be found in constants.py and depends on if data is timetable or fares data
         '''
 
-        #find all text in the given xpath, return as a element object
+        # find all text in the given xpath, return as a element object
         data = self.root.findall(f'Operators/.//NationalOperatorCode', self.namespace)
-        
-        #iterate through the data element and add the text to a list of NOCs
+
+        # iterate through the data element and add the text to a list of NOCs
         noc = [i.text for i in data]
-        
+
         return noc
-        
+
     def extract_trading_name(self):
-        
+
         '''
         Extracts the Trading Name from an xml file in a given location with a known namespace
         Namespace can be found in constants.py and depends on if data is timetable or fares data
         '''
 
-        #find all text in the given xpath, return as a element object
+        # find all text in the given xpath, return as a element object
         data = self.root.findall(f'Operators/.//TradingName', self.namespace)
-        
+
         trading_name = [i.text for i in data]
-        
+
         return trading_name
 
-   
     def extract_licence_number(self):
-        
+
         '''
         Extracts the Licence Number from an xml file in a given location with a known namespace
         Namespace can be found in constants.py and depends on if data is timetable or fares data
         '''
-   
-        #find all text in the given xpath, return as a element object
+
+        # find all text in the given xpath, return as a element object
         data = self.root.findall(f'Operators/.//LicenceNumber', self.namespace)
-        
-        licence_number = [i.text for i in data] 
-        
-        return licence_number
-    
 
+        licence_number = [i.text for i in data]
+
+        return licence_number
 
     def extract_operator_short_name(self):
-        
+
         '''
         Extracts the Operator Short Name from an xml file in a given location with a known namespace.
         Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        
-        #find all text in the given xpath, return as a element object
+
+        # find all text in the given xpath, return as a element object
         data = self.root.findall(f'Operators/.//OperatorShortName', self.namespace)
-        
+
         operator_short_name = [i.text for i in data]
-        
+
         return operator_short_name
-    
+
     def extract_operator_code(self):
-        
+
         '''
         Extracts the Operator Code from an xml file in a given location with a known namespace.
         Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        
-        #find all text in the given xpath, return as a element object
+
+        # find all text in the given xpath, return as a element object
         data = self.root.findall(f'Operators/.//OperatorCode', self.namespace)
-        
+
         operator_code = [i.text for i in data]
-        
+
         return operator_code
 
     def extract_service_code(self):
-        
+
         '''
         Extracts the Service Code from an xml file in a given location with a known namespace.
         Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        
-        #find all text in the given xpath, return as a element object
+
+        # find all text in the given xpath, return as a element object
         data = self.root.findall(f'Services//Service/ServiceCode', self.namespace)
-        
+
         service_code = [i.text for i in data]
-        
-        return service_code
 
+        return service_code
 
     def extract_line_name(self):
-        
+
         '''
         Extracts the Line Name from an xml file in a given location with a known namespace.
         Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        
-        #find all text in the given xpath, return as a element object
+
+        # find all text in the given xpath, return as a element object
         data = self.root.findall(f'Services//Service/Lines/Line/LineName', self.namespace)
-        
+
         line_name = [i.text for i in data]
-        
-        return line_name 
-    
+
+        return line_name
+
     def extract_public_use(self):
-        
+
         '''
         Extracts the public use boolean from an xml file in a given location with a known namespace.
         Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        
-        #find all text in the given xpath, return as a element object
+
+        # find all text in the given xpath, return as a element object
         data = self.root.findall(f'Services//Service/PublicUse', self.namespace)
-        
+
         public_use = [i.text for i in data]
-        
+
         return public_use
-    
+
     def extract_operating_days(self):
-        
+
         '''
         Extracts the regular operating days from an xml file in a given location with a known namespace.
         Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        #find all text in the given xpath, return as a element object
-        #Check service line level first
+        # find all text in the given xpath, return as a element object
+        # Check service line level first
         data = self.root.findall("Services//Service/OperatingProfile/RegularDayType/DaysOfWeek/", self.namespace)
-        
-        #if empty we proceed to service line level
-        if data==[]:
-            data = self.root.findall("VehicleJourneys//VehicleJourney/OperatingProfile/RegularDayType/DaysOfWeek/", self.namespace)
+
+        # if empty we proceed to service line level
+        if data == []:
+            data = self.root.findall("VehicleJourneys//VehicleJourney/OperatingProfile/RegularDayType/DaysOfWeek/",
+                                     self.namespace)
         else:
             pass
 
-        daysoperating=[]
-        
+        daysoperating = []
+
         for count, value in enumerate(data):
-            
-            #convert each element into a string
-            day=str(data[count])
-            
-            #only keep the element data associated with the day of the week
-            changedday=day[42:52]
-            
-            #split up the weekday string
+            # convert each element into a string
+            day = str(data[count])
+
+            # only keep the element data associated with the day of the week
+            changedday = day[42:52]
+
+            # split up the weekday string
             before, sep, after = changedday.partition(' ')
-            
-            #keep the string data before the partition mentioned above
+
+            # keep the string data before the partition mentioned above
             changedday = before
-        
+
             daysoperating.append(changedday)
-            
-        #remove duplicates from the operating days extracted
-        setoperatingdays=set(daysoperating)
-        
-        #change the operating days into a list format so they can be ordered
-        operating_day_list=list(setoperatingdays)
-        
-        #adding dictionary variables and values to "day" dictionary
-        
-        day={}
-        day['Monday']=1
-        day['Tuesday']=2
-        day['Wednesday']=3
-        day['Thursday']=4
-        day['Friday']=5
-        day['Saturday']=6
-        day['Sunday']=7
-        
-        brand_new={}
 
-        
-        #checking if the day of the week is in the above dictionary so we can sort the days
+        # remove duplicates from the operating days extracted
+        setoperatingdays = set(daysoperating)
+
+        # change the operating days into a list format so they can be ordered
+        operating_day_list = list(setoperatingdays)
+
+        # adding dictionary variables and values to "day" dictionary
+
+        day = {}
+        day['Monday'] = 1
+        day['Tuesday'] = 2
+        day['Wednesday'] = 3
+        day['Thursday'] = 4
+        day['Friday'] = 5
+        day['Saturday'] = 6
+        day['Sunday'] = 7
+
+        brand_new = {}
+
+        # checking if the day of the week is in the above dictionary so we can sort the days
         for i in operating_day_list:
             if i in day:
-                brand_new.update({i:day[i]})
-        
-        #sorting the days of operation
-        sortit=sorted(brand_new.items(), key=lambda x:x[1])
-        
-        length=len(sortit)
-
-        operating_days=""
-        
-        consecutive=True
-        
-        
-        #checking to see if the days in the list are not consective
-        
-        for i in range(length-1):
-            if sortit[i+1][1]-sortit[i][1]!=1:
-                consecutive=False
+                brand_new.update({i: day[i]})
+
+        # sorting the days of operation
+        sortit = sorted(brand_new.items(), key=lambda x: x[1])
+
+        length = len(sortit)
+
+        operating_days = ""
+
+        consecutive = True
+
+        # checking to see if the days in the list are not consective
+
+        for i in range(length - 1):
+            if sortit[i + 1][1] - sortit[i][1] != 1:
+                consecutive = False
                 break
 
-                     
         # if there are no days of operation entered
-        if length==0:
-            operating_days="None"
-        
-        #if there is only one day of operation
-        elif length==1:
-            operating_days=sortit[0][0]
-        
-        #if the operating days are not consecutive, they're seperated by commas
-        elif consecutive==False:
+        if length == 0:
+            operating_days = "Other"
+
+        # if there is only one day of operation
+        elif length == 1:
+            operating_days = sortit[0][0]
+
+        # if the operating days are not consecutive, they're seperated by commas
+        elif consecutive == False:
             for i in range(length):
-                operating_days= operating_days + sortit[i][0] + ","
-                
-        #if consecutive, operating days are given as a range           
+                operating_days = operating_days + sortit[i][0] + ","
+
+        # if consecutive, operating days are given as a range
         else:
-           # print(sortit)
-            operating_days=sortit[0][0] + "-" + sortit[-1][0]
-                
+            # print(sortit)
+            operating_days = sortit[0][0] + "-" + sortit[-1][0]
 
-        operating_days=[operating_days]
-        
+        operating_days = [operating_days]
 
         return operating_days
 
     def extract_service_origin(self):
-        
+
         '''
         Extracts the service origin from an xml file in a given location with a known namespace.
         Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        
-        #find all text in the given xpath, return as a element object
+
+        # find all text in the given xpath, return as a element object
         data = self.root.findall(f'Services//Service/StandardService/Origin', self.namespace)
-        
+
         service_origin = [i.text for i in data]
-        
-        return service_origin    
-    
+
+        return service_origin
+
     def extract_service_destination(self):
-        
+
         '''
         Extracts the service destination from an xml file in a given location with a known namespace.
         Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        
-        #find all text in the given xpath, return as a element object
+
+        # find all text in the given xpath, return as a element object
         data = self.root.findall(f'Services//Service/StandardService/Destination', self.namespace)
-        
+
         service_destination = [i.text for i in data]
-        
-        return service_destination     
-    
+
+        return service_destination
+
     def extract_operating_period_start_date(self):
-        
+
         '''
         Extracts the service start date from an xml file in a given location with a known namespace.
         Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        
-        #find all text in the given xpath, return as a element object
+
+        # find all text in the given xpath, return as a element object
         data = self.root.findall(f'Services//Service/OperatingPeriod/StartDate', self.namespace)
-        
+
         operating_period_start_date = [i.text for i in data]
-        
-        return operating_period_start_date    
-    
-    
+
+        return operating_period_start_date
+
     def extract_operating_period_end_date(self):
-        
+
         '''
         Extracts the service end date from an xml file in a given location with a known namespace.
         Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        
-        #find all text in the given xpath, return as a element object
+
+        # find all text in the given xpath, return as a element object
         data = self.root.findall(f'Services//Service/OperatingPeriod/EndDate', self.namespace)
-        
-        operating_period_end_date = [i.text if len(i.text) >0 else 'No Data' for i in data]
-        
+
+        operating_period_end_date = [i.text if len(i.text) > 0 else 'No Data' for i in data]
+
         return operating_period_end_date
-    
-             
-       
+
     def extract_schema_version(self):
-        
+
         '''
         Extracts the schema version from an xml file in a given location with a known namespace.
         Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        
+
         try:
-        
+
             return self.root.attrib['SchemaVersion']
-        
+
         except:
             return 'Not Found'
 
-    
     def extract_revision_number(self):
-        
+
         '''
         Extracts the schema version from an xml file in a given location with a known namespace.
         Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        
+
         try:
             return self.root.attrib['RevisionNumber']
         except:
             return 'Not Found'
-        
-        
+
     def extract_la_code(self):
-        
+
         '''
-        Extracts the first 3 characters of the ATCO code (unique stop ref) from an xml file in a 
+        Extracts the first 3 characters of the ATCO code (unique stop ref) from an xml file in a
         given location with a known namespace. First 3 characters correspond to the asspciate Admin
         Area. Namespace can be found in constants.py and depends on if data is timetable or fares data
-        
+
         '''
-        
-        #find all text in the given xpath, return as a element object
-        #atco_first_3_letters = []
-        
+
+        # find all text in the given xpath, return as a element object
+        # atco_first_3_letters = []
+
         data = self.root.findall(f'StopPoints//StopPointRef', self.namespace)
-                
+
         atco_first_3_letters = [i.text[0:3] for i in data]
-        
+
         unique_atco_first_3_letters = list(set(atco_first_3_letters))
-        
+
         return unique_atco_first_3_letters
```

### Comparing `BODSDataExtractor-1.1.1/src/BODSDataExtractor/otc_db_download.py` & `BODSDataExtractor-1.2/src/BODSDataExtractor/otc_db_download.py`

 * *Files identical despite different names*

### Comparing `BODSDataExtractor-1.1.1/src/BODSDataExtractor.egg-info/PKG-INFO` & `BODSDataExtractor-1.2/src/BODSDataExtractor.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: BODSDataExtractor
-Version: 1.1.1
+Version: 1.2
 Summary: This project was created to lower the barrier to entry for analysis of UK Bus Open Data. It facilitates the fetching and extraction of clean data, currently focussed on Timetables, into tables to be used for analysis or your own projects.
 Author-email: "Ali Partner, Spencer Brittain" <bodshelpdesk@kpmg.co.uk>
 Project-URL: Homepage, https://github.com/department-for-transport-BODS/bods-data-extractor
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Requires-Python: >=3.8
@@ -187,15 +187,15 @@
 #Dataset Level
 TimetableExtractor.metadata
 
 #Service Line Level
 TimetableExtractor.service_line_extract
 
 #Stop Level
-TimetableExtractor.timetable_dict
+TimetableExtractor.stop_level_extract
 ```
 
 ### Example of timetables output
 
 Timetable data can be extracted at 3 levels (note that these examples are restricted to 1 dataset, of ID 322):
 
 * Dataset level - High level overview of key dataset information (each row represents 1 dataset on BODS platform)
@@ -204,15 +204,16 @@
 
 * Service Line Level - Detailed information about each service and line extracted from individual files within datasets (each row represents 1 timetables xml file)
 
 <img width="1400" alt="image" src="https://user-images.githubusercontent.com/81578708/189094457-ee19dc5b-97b8-409c-a75d-04ca4adb5016.png">
 
 * Stop level - Stop level data in the form of a traditional timetable (1 timetable from each xml file)
 
-<img width="1362" alt="image" src="https://user-images.githubusercontent.com/81578708/189094683-ce047d25-051c-470e-be8e-70e6b5d47eab.png">
+![image](https://github.com/department-for-transport-BODS/bods-data-extractor/assets/114913914/fad1be30-01da-4373-8f63-ed11b3994e5e)
+
 
 ### Fundamentals of extracting data using this package
 
 This package is written using object orientated python principles. Put simply, one must initiate an object based upon the subset of BODS timetables data they wish to extract data on, or analyse. Upon initiating an instance of this object, parameters can be specified to select the desired subset. Once this object instance has been initiated, there is no immediate output in the python console. One can now access attributes of the instance by calling them. 
 
 Note that for the data extraction, all of the processing is done in the initiation of the object instance, and not in the accessing of the attributes. This means it make take some time to initiate the object instance, but should take almost no time to access your desired data once the object instance has been initiated.
 
@@ -268,33 +269,31 @@
 my_bus_data_object = TimetableExtractor(api_key=api # Your API Key Here
                                  ,limit=1 # How many datasets to view
                                  ,status = 'published' # Only view published datasets
                                  ,service_line_level=True # True if you require Service line data 
                                  ,stop_level=True # True if you require stop level data
                                  )
 
-#save the extracted stop level data to stop_level variable
-stop_level = my_bus_data_object.timetable_dict
-
-#note that in downloading stop level the  data, the dataset and service line level will also be downloaded. Can access this as below:
-dataset_level = my_bus_data_object.metadata
-service_line_level = my_bus_data_object.service_line_extract
+#save the extracted dataset level data to filtered_dataset_level variable
+filtered_dataset_level = my_bus_data_object.metadata
 
-#save metadata and service line level data to csv file in your downloads directory
+#save the extracted dataset level data to lcoal csv file
 my_bus_data_object.save_metadata_to_csv()
-my_bus_data_object.save_service_line_extract_to_csv()
 
-#stop_level variable is a dictionary of dataframes, which can be saved to csv as follows (saves in downloads directory)
-my_bus_data_object.save_all_timetables_to_csv()
+#save the extracted service line level data to dataset_level variable
+filtered_service_line_level = my_bus_data_object.service_line_extract
+
+#save the extracted service line level data to lcoal csv file
+my_bus_data_object.save_service_line_extract_to_csv()
 
-#or can filter to filter timetable results to a specfic licence number of service code (saves in downloads directory)
-my_bus_data_object.save_filtered_timetables_to_csv('PC0001838:41')
+#stop_level_extract is a dataframe, which contains a collumn of timetables (inbound/outbound) to be saved to csv as follows (saves in project folder)
+my_bus_data_object.save_timetables()
 
 #visualise a particular service line on an interactive map
-my_bus_data_object.visualise_service_line('PC0001838:41')
+#my_bus_data_object.visualise_service_line('PC0001838:41')
 
 ```
 ### Expected run times and performance
 
 The volume of timetables data available on the BODS platform is very significant, and while this package simplifies the extraction of this data, and processes it into a analytical ready form, the sheer amount of data dictates that it can take a non trivial amount of time to initiate the above object instances. 
 
 One way of getting around this problem is to narrow your requested data request using additional parameters. Another is to run the download once, and save the output to disk as a csv, to allow re loading of this at a later data for reporting analysis. Both of these approaches are outlined in more detail in below sections.
@@ -314,14 +313,15 @@
 
 As well as specifying the granularity of data to extract (dataset, service line or stop level), limiting the number of datasets, and restricting to just published datasets, there are a number of additional parameters that the object instance can be initiated with. These are as follows:
 
 - nocs - _accepts list input of valid National Operator Codes e.g. ['HIPK', 'YCST']_
 - search -  _accepts string input of key-words to filter for the data set name, data set description, organisation name, or admin name e.g. 'Arriva'_
 - bods_compliant - _accepts boolean input (True or False), where True filters for only BODS Compliant datasets. Default value is True_
 - atco_code - _accepts list input of the first three characters of ATCO codes (ATCO codes are unique identifiers of UK bus stops, where first three characters signify the admin area they are within). This filters datasets and/or service lines that have stops within the specified admin areas. e.g. ['320','450']_
+- limit - _accepts an integer value which specifies the amount of datasets will be downloaded. For example, if there were 5 datasets present and the limit was set to 5, all datasets would be downloaded. Comparitively, if the limit was set to 1 , only 1 dataset of the 5 will be downloaded._
 
 Example of this:
 ```python
 #intiate an object instance called my_bus_data_object with desired parameters
 from BODSDataExtractor.extractor import TimetableExtractor
 
 my_bus_data_object = TimetableExtractor(api_key=api # Your API Key Here
@@ -451,17 +451,14 @@
 ## Roadmap & Limitations
 
 As the first release of this project, the focus was on getting analytical ready timetable data in the hands of consumers. As a result, there are a number of limitations to bear in mind when using this package. These aim to be addressed in subsequent releases. 
 
 #### Handling non standard files
 Whilst all BODS compliant files meet a certain set of standards, there is still variation in exactly how timetables xml files can be populated. This pacakge currently handles files that meet the most common structure, and a number of notable exceptions, however there are some files that stop level timetables will not be generated for. It will, however, generate dataset level and service line level data for all published files. Future releases will aim to close this gap so timetables can be generated for most, if not all files.
 
-#### Handling vehicle journeys that cross midnight
-As the PTI standards dictate, sequence number logic is different for services that have stop times which cross midnight. This currently results in the stop level timetable output having vehicle journeys that do not start at sequence number 1. Future releases will include logic that better handles this to provide a more uniform output for such vehicle journeys.
-
 #### Providing additional detail about services
 Future releases will extract additional data from timetables xml files in order to provide further detail on services; for example details regarding the days of operation and exceptions around bank holidays, as well as more detailed route information including distance between stops, in addition to time.
 
 #### Incorporating AVL and Fares data
 The BODS platform also provides live vehicle location data (AVL), as well as Fares data. Future releases will aim to incorporate functionality for downloading and analysis AVL data initially, and subsequently Fares data once this has been validated. 
 
 #### Optimising performance
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: BODSDataExtractor Version: 1.1.1 Summary: This
+Metadata-Version: 2.1 Name: BODSDataExtractor Version: 1.2 Summary: This
 project was created to lower the barrier to entry for analysis of UK Bus Open
 Data. It facilitates the fetching and extraction of clean data, currently
 focussed on Timetables, into tables to be used for analysis or your own
 projects. Author-email: "Ali Partner, Spencer Brittain"
 kpmg.co.uk> Project-URL: Homepage, https://github.com/department-for-transport-
 BODS/bods-data-extractor Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License Classifier: Operating System
@@ -139,42 +139,43 @@
 section. The code examples are ready to copy and paste into your .py file.
                                                                   (back_to_top)
  ## Usage ### Quick Reference The below code acts as a quick reference guide to
 calling the attributes of a TimetableExtractor object at each level as
 explained below in this document. ```python #Dataset Level
 TimetableExtractor.metadata #Service Line Level
 TimetableExtractor.service_line_extract #Stop Level
-TimetableExtractor.timetable_dict ``` ### Example of timetables output
+TimetableExtractor.stop_level_extract ``` ### Example of timetables output
 Timetable data can be extracted at 3 levels (note that these examples are
 restricted to 1 dataset, of ID 322): * Dataset level - High level overview of
 key dataset information (each row represents 1 dataset on BODS platform)
 [image] * Service Line Level - Detailed information about each service and line
 extracted from individual files within datasets (each row represents 1
 timetables xml file) [image] * Stop level - Stop level data in the form of a
-traditional timetable (1 timetable from each xml file) [image] ### Fundamentals
-of extracting data using this package This package is written using object
-orientated python principles. Put simply, one must initiate an object based
-upon the subset of BODS timetables data they wish to extract data on, or
-analyse. Upon initiating an instance of this object, parameters can be
-specified to select the desired subset. Once this object instance has been
-initiated, there is no immediate output in the python console. One can now
-access attributes of the instance by calling them. Note that for the data
-extraction, all of the processing is done in the initiation of the object
-instance, and not in the accessing of the attributes. This means it make take
-some time to initiate the object instance, but should take almost no time to
-access your desired data once the object instance has been initiated. The
-examples below should bring this to life. ### How to extract Dataset Level data
-```python #intiate an object instance called my_bus_data_object with desired
-parameters from BODSDataExtractor.extractor import TimetableExtractor
-my_bus_data_object = TimetableExtractor(api_key=api # Your API Key Here
-,limit=1 # How many datasets to view ,status = 'published' # Only view
-published datasets ,service_line_level=False # True if you require Service line
-data ,stop_level=False # True if you require stop level data ) #save the
-extracted dataset level data to dataset_level variable dataset_level =
-my_bus_data_object.metadata #save this data to a csv file in your downloads
+traditional timetable (1 timetable from each xml file) ![image](https://
+github.com/department-for-transport-BODS/bods-data-extractor/assets/114913914/
+fad1be30-01da-4373-8f63-ed11b3994e5e) ### Fundamentals of extracting data using
+this package This package is written using object orientated python principles.
+Put simply, one must initiate an object based upon the subset of BODS
+timetables data they wish to extract data on, or analyse. Upon initiating an
+instance of this object, parameters can be specified to select the desired
+subset. Once this object instance has been initiated, there is no immediate
+output in the python console. One can now access attributes of the instance by
+calling them. Note that for the data extraction, all of the processing is done
+in the initiation of the object instance, and not in the accessing of the
+attributes. This means it make take some time to initiate the object instance,
+but should take almost no time to access your desired data once the object
+instance has been initiated. The examples below should bring this to life. ###
+How to extract Dataset Level data ```python #intiate an object instance called
+my_bus_data_object with desired parameters from BODSDataExtractor.extractor
+import TimetableExtractor my_bus_data_object = TimetableExtractor(api_key=api #
+Your API Key Here ,limit=1 # How many datasets to view ,status = 'published' #
+Only view published datasets ,service_line_level=False # True if you require
+Service line data ,stop_level=False # True if you require stop level data )
+#save the extracted dataset level data to dataset_level variable dataset_level
+= my_bus_data_object.metadata #save this data to a csv file in your downloads
 directory #note that entries in the 'localities' field may be truncated to
 comply with excel cell limits my_bus_data_object.save_metadata_to_csv() ``` ###
 How to extract Service Line Level data ```python #intiate an object instance
 called my_bus_data_object with desired parameters from
 BODSDataExtractor.extractor import TimetableExtractor my_bus_data_object =
 TimetableExtractor(api_key=api # Your API Key Here ,limit=1 # How many datasets
 to view ,status = 'published' # Only view published datasets
@@ -188,76 +189,76 @@
 my_bus_data_object.save_service_line_extract_to_csv() ``` ### How to extract
 Stop Level data ```python #intiate an object instance called my_bus_data_object
 with desired parameters from BODSDataExtractor.extractor import
 TimetableExtractor my_bus_data_object = TimetableExtractor(api_key=api # Your
 API Key Here ,limit=1 # How many datasets to view ,status = 'published' # Only
 view published datasets ,service_line_level=True # True if you require Service
 line data ,stop_level=True # True if you require stop level data ) #save the
-extracted stop level data to stop_level variable stop_level =
-my_bus_data_object.timetable_dict #note that in downloading stop level the
-data, the dataset and service line level will also be downloaded. Can access
-this as below: dataset_level = my_bus_data_object.metadata service_line_level =
-my_bus_data_object.service_line_extract #save metadata and service line level
-data to csv file in your downloads directory
-my_bus_data_object.save_metadata_to_csv()
-my_bus_data_object.save_service_line_extract_to_csv() #stop_level variable is a
-dictionary of dataframes, which can be saved to csv as follows (saves in
-downloads directory) my_bus_data_object.save_all_timetables_to_csv() #or can
-filter to filter timetable results to a specfic licence number of service code
-(saves in downloads directory)
-my_bus_data_object.save_filtered_timetables_to_csv('PC0001838:41') #visualise a
-particular service line on an interactive map
-my_bus_data_object.visualise_service_line('PC0001838:41') ``` ### Expected run
-times and performance The volume of timetables data available on the BODS
-platform is very significant, and while this package simplifies the extraction
-of this data, and processes it into a analytical ready form, the sheer amount
-of data dictates that it can take a non trivial amount of time to initiate the
-above object instances. One way of getting around this problem is to narrow
-your requested data request using additional parameters. Another is to run the
-download once, and save the output to disk as a csv, to allow re loading of
-this at a later data for reporting analysis. Both of these approaches are
-outlined in more detail in below sections. Directly below are some sample
-expected run times for extracting data using this package. This should still
-give you a very approximate idea of how long to expect your code to execute,
-depending on how much data you are trying to extract. It is important to note
-that this can vary depending on your local processing power, internet
-connection and on the nature of the datasets you are extracting (a dataset may
-contain one xml file, or several hundred). | Granularity of data extraction | 1
-dataset timing | 20 dataset timing | 200 datasets timing | | ------------------
---------------- |------------------|-------------------|-----------------------
----| | Dataset | < 0 hrs 1 min | < 0 hrs 1 min | 0 hrs 2 min | | Service line |
-< 0 hrs 1 min | < 0 hrs 1 min | 0 hrs 6 min | | Stop | 0 hrs 3 min | < 0 hrs 6
-min | Memory issues @ 16Gb RAM | ### How to fine tune your results using
-additional parameters As well as specifying the granularity of data to extract
-(dataset, service line or stop level), limiting the number of datasets, and
-restricting to just published datasets, there are a number of additional
-parameters that the object instance can be initiated with. These are as
-follows: - nocs - _accepts list input of valid National Operator Codes e.g.
+extracted dataset level data to filtered_dataset_level variable
+filtered_dataset_level = my_bus_data_object.metadata #save the extracted
+dataset level data to lcoal csv file my_bus_data_object.save_metadata_to_csv()
+#save the extracted service line level data to dataset_level variable
+filtered_service_line_level = my_bus_data_object.service_line_extract #save the
+extracted service line level data to lcoal csv file
+my_bus_data_object.save_service_line_extract_to_csv() #stop_level_extract is a
+dataframe, which contains a collumn of timetables (inbound/outbound) to be
+saved to csv as follows (saves in project folder)
+my_bus_data_object.save_timetables() #visualise a particular service line on an
+interactive map #my_bus_data_object.visualise_service_line('PC0001838:41') ```
+### Expected run times and performance The volume of timetables data available
+on the BODS platform is very significant, and while this package simplifies the
+extraction of this data, and processes it into a analytical ready form, the
+sheer amount of data dictates that it can take a non trivial amount of time to
+initiate the above object instances. One way of getting around this problem is
+to narrow your requested data request using additional parameters. Another is
+to run the download once, and save the output to disk as a csv, to allow re
+loading of this at a later data for reporting analysis. Both of these
+approaches are outlined in more detail in below sections. Directly below are
+some sample expected run times for extracting data using this package. This
+should still give you a very approximate idea of how long to expect your code
+to execute, depending on how much data you are trying to extract. It is
+important to note that this can vary depending on your local processing power,
+internet connection and on the nature of the datasets you are extracting (a
+dataset may contain one xml file, or several hundred). | Granularity of data
+extraction | 1 dataset timing | 20 dataset timing | 200 datasets timing | | ---
+------------------------------ |------------------|-------------------|--------
+------------------| | Dataset | < 0 hrs 1 min | < 0 hrs 1 min | 0 hrs 2 min | |
+Service line | < 0 hrs 1 min | < 0 hrs 1 min | 0 hrs 6 min | | Stop | 0 hrs 3
+min | < 0 hrs 6 min | Memory issues @ 16Gb RAM | ### How to fine tune your
+results using additional parameters As well as specifying the granularity of
+data to extract (dataset, service line or stop level), limiting the number of
+datasets, and restricting to just published datasets, there are a number of
+additional parameters that the object instance can be initiated with. These are
+as follows: - nocs - _accepts list input of valid National Operator Codes e.g.
 ['HIPK', 'YCST']_ - search - _accepts string input of key-words to filter for
 the data set name, data set description, organisation name, or admin name e.g.
 'Arriva'_ - bods_compliant - _accepts boolean input (True or False), where True
 filters for only BODS Compliant datasets. Default value is True_ - atco_code -
 _accepts list input of the first three characters of ATCO codes (ATCO codes are
 unique identifiers of UK bus stops, where first three characters signify the
 admin area they are within). This filters datasets and/or service lines that
-have stops within the specified admin areas. e.g. ['320','450']_ Example of
-this: ```python #intiate an object instance called my_bus_data_object with
-desired parameters from BODSDataExtractor.extractor import TimetableExtractor
-my_bus_data_object = TimetableExtractor(api_key=api # Your API Key Here
-#,limit=1 # commented out limit so will return all results within other
-parameters ,status = 'published' ,service_line_level=True ,stop_level=False
-,nocs=['FSCE','FGLA','FCYM'] #values must be entered in this list format - each
-noc within quotes, separated by comma, all within [] ,search='First Bus' # this
-is actually redundant as nocs are specific to this operator, but included for
-demo purpose ,bods_compliant=True ,atco_code=['320', '450'] # filter to stops
-within just north and west yorkshire. Values must be entered in this list
-format - each code within quotes, separated by comma, all within [] ) #save the
-extracted dataset level data to filtered_dataset_level variable
-filtered_dataset_level = my_bus_data_object.metadata #save the extracted
-service line level data to dataset_level variable filtered_service_line_level =
+have stops within the specified admin areas. e.g. ['320','450']_ - limit -
+_accepts an integer value which specifies the amount of datasets will be
+downloaded. For example, if there were 5 datasets present and the limit was set
+to 5, all datasets would be downloaded. Comparitively, if the limit was set to
+1 , only 1 dataset of the 5 will be downloaded._ Example of this: ```python
+#intiate an object instance called my_bus_data_object with desired parameters
+from BODSDataExtractor.extractor import TimetableExtractor my_bus_data_object =
+TimetableExtractor(api_key=api # Your API Key Here #,limit=1 # commented out
+limit so will return all results within other parameters ,status = 'published'
+,service_line_level=True ,stop_level=False ,nocs=['FSCE','FGLA','FCYM'] #values
+must be entered in this list format - each noc within quotes, separated by
+comma, all within [] ,search='First Bus' # this is actually redundant as nocs
+are specific to this operator, but included for demo purpose
+,bods_compliant=True ,atco_code=['320', '450'] # filter to stops within just
+north and west yorkshire. Values must be entered in this list format - each
+code within quotes, separated by comma, all within [] ) #save the extracted
+dataset level data to filtered_dataset_level variable filtered_dataset_level =
+my_bus_data_object.metadata #save the extracted service line level data to
+dataset_level variable filtered_service_line_level =
 my_bus_data_object.service_line_extract #export to csv if you wish to save this
 data filtered_service_line_level.to_csv
 ('filtered_service_line_level_export.csv') ``` ### ATCO Code to Local Authority
 Lookup Table The package contains an unofficial lookup table used to map bus
 stop ATCO codes to Local Authorities. This may be useful as a rough guide to
 filtering services around a certain area of England. Please note that this is
 not an official definition of ATCO / LA mappings and has been manually created.
@@ -360,36 +361,31 @@
 standard files Whilst all BODS compliant files meet a certain set of standards,
 there is still variation in exactly how timetables xml files can be populated.
 This pacakge currently handles files that meet the most common structure, and a
 number of notable exceptions, however there are some files that stop level
 timetables will not be generated for. It will, however, generate dataset level
 and service line level data for all published files. Future releases will aim
 to close this gap so timetables can be generated for most, if not all files.
-#### Handling vehicle journeys that cross midnight As the PTI standards
-dictate, sequence number logic is different for services that have stop times
-which cross midnight. This currently results in the stop level timetable output
-having vehicle journeys that do not start at sequence number 1. Future releases
-will include logic that better handles this to provide a more uniform output
-for such vehicle journeys. #### Providing additional detail about services
-Future releases will extract additional data from timetables xml files in order
-to provide further detail on services; for example details regarding the days
-of operation and exceptions around bank holidays, as well as more detailed
-route information including distance between stops, in addition to time. ####
-Incorporating AVL and Fares data The BODS platform also provides live vehicle
-location data (AVL), as well as Fares data. Future releases will aim to
-incorporate functionality for downloading and analysis AVL data initially, and
-subsequently Fares data once this has been validated. #### Optimising
-performance Generating stop level timetables requires downloading and parsing a
-significant volume of data. It therefore takes quite some time to run the code.
-Future releases will aim to reduce execution time through optimisations. ####
-And more! This project has consumers of BODS data at its heart, and so if any
-other features would be valuable, or any bugs are noticed please get in touch.
-Details of how to do this can be found in the 'Contributing' section below. See
-the [open issues](https://github.com/KPMG-UK/bods_pseudo_test/issues) for a
-full list of proposed features (and known issues).
+#### Providing additional detail about services Future releases will extract
+additional data from timetables xml files in order to provide further detail on
+services; for example details regarding the days of operation and exceptions
+around bank holidays, as well as more detailed route information including
+distance between stops, in addition to time. #### Incorporating AVL and Fares
+data The BODS platform also provides live vehicle location data (AVL), as well
+as Fares data. Future releases will aim to incorporate functionality for
+downloading and analysis AVL data initially, and subsequently Fares data once
+this has been validated. #### Optimising performance Generating stop level
+timetables requires downloading and parsing a significant volume of data. It
+therefore takes quite some time to run the code. Future releases will aim to
+reduce execution time through optimisations. #### And more! This project has
+consumers of BODS data at its heart, and so if any other features would be
+valuable, or any bugs are noticed please get in touch. Details of how to do
+this can be found in the 'Contributing' section below. See the [open issues]
+(https://github.com/KPMG-UK/bods_pseudo_test/issues) for a full list of
+proposed features (and known issues).
                                                                   (back_to_top)
  ## Contribute / Contact ### Contribute to this project Contributions are what
 make the open source community such an amazing place to learn, inspire, and
 create. Any contributions you make are **greatly appreciated**. If you want to
 suggest an new or improved feature, open an issue with the tag "enhancement".
 If you want to develop a new or improved feature yourself, fork the repo,
 develop within a new branch, then create a pull request back to this repo. We
```

