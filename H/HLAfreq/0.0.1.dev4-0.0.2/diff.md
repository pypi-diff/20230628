# Comparing `tmp/HLAfreq-0.0.1.dev4.tar.gz` & `tmp/HLAfreq-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "HLAfreq-0.0.1.dev4.tar", last modified: Wed Mar  8 15:08:37 2023, max compression
+gzip compressed data, was "HLAfreq-0.0.2.tar", last modified: Wed Jun 28 09:56:32 2023, max compression
```

## Comparing `HLAfreq-0.0.1.dev4.tar` & `HLAfreq-0.0.2.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxrwxr-x   0 dwells    (1000) dwells    (1000)        0 2023-03-08 15:08:37.193646 HLAfreq-0.0.1.dev4/
--rw-rw-r--   0 dwells    (1000) dwells    (1000)     1070 2023-01-18 21:40:26.000000 HLAfreq-0.0.1.dev4/LICENSE
--rw-rw-r--   0 dwells    (1000) dwells    (1000)       30 2022-10-14 15:49:57.000000 HLAfreq-0.0.1.dev4/MANIFEST.in
--rw-rw-r--   0 dwells    (1000) dwells    (1000)     3679 2023-03-08 15:08:37.193646 HLAfreq-0.0.1.dev4/PKG-INFO
--rw-rw-r--   0 dwells    (1000) dwells    (1000)     3218 2023-03-08 15:07:50.000000 HLAfreq-0.0.1.dev4/README.md
--rw-rw-r--   0 dwells    (1000) dwells    (1000)       80 2022-10-14 15:46:12.000000 HLAfreq-0.0.1.dev4/pyproject.toml
--rw-rw-r--   0 dwells    (1000) dwells    (1000)       38 2023-03-08 15:08:37.193646 HLAfreq-0.0.1.dev4/setup.cfg
--rw-rw-r--   0 dwells    (1000) dwells    (1000)      868 2023-03-08 15:07:25.000000 HLAfreq-0.0.1.dev4/setup.py
-drwxrwxr-x   0 dwells    (1000) dwells    (1000)        0 2023-03-08 15:08:37.189646 HLAfreq-0.0.1.dev4/src/
-drwxrwxr-x   0 dwells    (1000) dwells    (1000)        0 2023-03-08 15:08:37.189646 HLAfreq-0.0.1.dev4/src/HLAfreq/
--rw-rw-r--   0 dwells    (1000) dwells    (1000)    28087 2023-03-08 14:59:43.000000 HLAfreq-0.0.1.dev4/src/HLAfreq/HLAfreq.py
--rw-rw-r--   0 dwells    (1000) dwells    (1000)      392 2022-10-14 10:05:54.000000 HLAfreq-0.0.1.dev4/src/HLAfreq/HLAfreq_data.py
--rw-rw-r--   0 dwells    (1000) dwells    (1000)     6455 2023-03-08 15:01:21.000000 HLAfreq-0.0.1.dev4/src/HLAfreq/HLAfreq_pymc.py
--rw-rw-r--   0 dwells    (1000) dwells    (1000)       22 2023-01-19 17:18:22.000000 HLAfreq-0.0.1.dev4/src/HLAfreq/__init__.py
-drwxrwxr-x   0 dwells    (1000) dwells    (1000)        0 2023-03-08 15:08:37.193646 HLAfreq-0.0.1.dev4/src/HLAfreq/data/
--rw-rw-r--   0 dwells    (1000) dwells    (1000)    12117 2022-07-21 11:19:34.000000 HLAfreq-0.0.1.dev4/src/HLAfreq/data/HLA1supertypes_Sidney2008.csv
--rw-rw-r--   0 dwells    (1000) dwells    (1000)     8988 2022-08-30 15:30:16.000000 HLAfreq-0.0.1.dev4/src/HLAfreq/data/countries.csv
-drwxrwxr-x   0 dwells    (1000) dwells    (1000)        0 2023-03-08 15:08:37.189646 HLAfreq-0.0.1.dev4/src/HLAfreq.egg-info/
--rw-rw-r--   0 dwells    (1000) dwells    (1000)     3679 2023-03-08 15:08:37.000000 HLAfreq-0.0.1.dev4/src/HLAfreq.egg-info/PKG-INFO
--rw-rw-r--   0 dwells    (1000) dwells    (1000)      441 2023-03-08 15:08:37.000000 HLAfreq-0.0.1.dev4/src/HLAfreq.egg-info/SOURCES.txt
--rw-rw-r--   0 dwells    (1000) dwells    (1000)        1 2023-03-08 15:08:37.000000 HLAfreq-0.0.1.dev4/src/HLAfreq.egg-info/dependency_links.txt
--rw-rw-r--   0 dwells    (1000) dwells    (1000)       48 2023-03-08 15:08:37.000000 HLAfreq-0.0.1.dev4/src/HLAfreq.egg-info/requires.txt
--rw-rw-r--   0 dwells    (1000) dwells    (1000)        8 2023-03-08 15:08:37.000000 HLAfreq-0.0.1.dev4/src/HLAfreq.egg-info/top_level.txt
-drwxrwxr-x   0 dwells    (1000) dwells    (1000)        0 2023-03-08 15:08:37.193646 HLAfreq-0.0.1.dev4/tests/
--rw-rw-r--   0 dwells    (1000) dwells    (1000)     1501 2022-10-17 09:00:36.000000 HLAfreq-0.0.1.dev4/tests/test_single_country_caf.py
+drwxrwxr-x   0 dwells    (1000) dwells    (1000)        0 2023-06-28 09:56:32.181143 HLAfreq-0.0.2/
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)     1070 2023-01-18 21:40:26.000000 HLAfreq-0.0.2/LICENSE
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)       30 2022-10-14 15:49:57.000000 HLAfreq-0.0.2/MANIFEST.in
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)     3674 2023-06-28 09:56:32.181143 HLAfreq-0.0.2/PKG-INFO
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)     3218 2023-03-08 15:07:50.000000 HLAfreq-0.0.2/README.md
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)       80 2022-10-14 15:46:12.000000 HLAfreq-0.0.2/pyproject.toml
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)       38 2023-06-28 09:56:32.181143 HLAfreq-0.0.2/setup.cfg
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)      884 2023-06-28 09:55:17.000000 HLAfreq-0.0.2/setup.py
+drwxrwxr-x   0 dwells    (1000) dwells    (1000)        0 2023-06-28 09:56:32.177143 HLAfreq-0.0.2/src/
+drwxrwxr-x   0 dwells    (1000) dwells    (1000)        0 2023-06-28 09:56:32.177143 HLAfreq-0.0.2/src/HLAfreq/
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)    28743 2023-06-02 15:15:00.000000 HLAfreq-0.0.2/src/HLAfreq/HLAfreq.py
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)      408 2023-06-02 15:15:00.000000 HLAfreq-0.0.2/src/HLAfreq/HLAfreq_data.py
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)     6655 2023-06-02 15:15:00.000000 HLAfreq-0.0.2/src/HLAfreq/HLAfreq_pymc.py
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)       23 2023-06-02 15:15:00.000000 HLAfreq-0.0.2/src/HLAfreq/__init__.py
+drwxrwxr-x   0 dwells    (1000) dwells    (1000)        0 2023-06-28 09:56:32.181143 HLAfreq-0.0.2/src/HLAfreq/data/
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)    12117 2022-07-21 11:19:34.000000 HLAfreq-0.0.2/src/HLAfreq/data/HLA1supertypes_Sidney2008.csv
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)     8988 2022-08-30 15:30:16.000000 HLAfreq-0.0.2/src/HLAfreq/data/countries.csv
+drwxrwxr-x   0 dwells    (1000) dwells    (1000)        0 2023-06-28 09:56:32.181143 HLAfreq-0.0.2/src/HLAfreq.egg-info/
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)     3674 2023-06-28 09:56:32.000000 HLAfreq-0.0.2/src/HLAfreq.egg-info/PKG-INFO
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)      441 2023-06-28 09:56:32.000000 HLAfreq-0.0.2/src/HLAfreq.egg-info/SOURCES.txt
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)        1 2023-06-28 09:56:32.000000 HLAfreq-0.0.2/src/HLAfreq.egg-info/dependency_links.txt
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)       57 2023-06-28 09:56:32.000000 HLAfreq-0.0.2/src/HLAfreq.egg-info/requires.txt
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)        8 2023-06-28 09:56:32.000000 HLAfreq-0.0.2/src/HLAfreq.egg-info/top_level.txt
+drwxrwxr-x   0 dwells    (1000) dwells    (1000)        0 2023-06-28 09:56:32.181143 HLAfreq-0.0.2/tests/
+-rw-rw-r--   0 dwells    (1000) dwells    (1000)     1636 2023-06-02 15:15:10.000000 HLAfreq-0.0.2/tests/test_single_country_caf.py
```

### Comparing `HLAfreq-0.0.1.dev4/LICENSE` & `HLAfreq-0.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `HLAfreq-0.0.1.dev4/PKG-INFO` & `HLAfreq-0.0.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: HLAfreq
-Version: 0.0.1.dev4
+Version: 0.0.2
 Summary: Download and combine HLA frequency data from multiple studies
 Home-page: https://github.com/Vaccitech/HLAfreq
 Author: David Wells
 Author-email: david.wells@vaccitech.co.uk
 Project-URL: Tracker, https://github.com/Vaccitech/HLAfreq/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: OS Independent
```

### Comparing `HLAfreq-0.0.1.dev4/README.md` & `HLAfreq-0.0.2/README.md`

 * *Files identical despite different names*

### Comparing `HLAfreq-0.0.1.dev4/setup.py` & `HLAfreq-0.0.2/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from setuptools import setup, find_packages
 
 setup(
     name="HLAfreq",
-    version="0.0.1dev4",
+    version="0.0.2",
     url="https://github.com/Vaccitech/HLAfreq",
     project_urls={
         'Tracker': "https://github.com/Vaccitech/HLAfreq/issues"
     },
     author="David Wells",
     author_email="david.wells@vaccitech.co.uk",
     description="Download and combine HLA frequency data from multiple studies",
@@ -15,15 +15,16 @@
     install_requires=[
         'bs4',
         'requests',
         'pandas',
         'numpy',
         'matplotlib',
         'scipy',
-        'pymc'
+        'pymc>=3',
+        'arviz'
     ],
     classifiers=[
     "Programming Language :: Python :: 3",
     "Operating System :: OS Independent",
     ],
     package_dir={'':'src'},
     packages=find_packages(
```

### Comparing `HLAfreq-0.0.1.dev4/src/HLAfreq/HLAfreq.py` & `HLAfreq-0.0.2/src/HLAfreq/HLAfreq.py`

 * *Files 4% similar despite different names*

```diff
@@ -15,29 +15,30 @@
 import matplotlib.pyplot as plt
 import math
 import scipy as sp
 import logging
 import warnings
 import matplotlib.colors as mcolors
 
+
 def makeURL(
-        country="",
-        standard='s',
-        locus="",
-        resolution_pattern="bigger_equal_than",
-        resolution=2,
-        region="",
-        ethnic="",
-        study_type="",
-        dataset_source="",
-        sample_year="",
-        sample_year_pattern="",
-        sample_size="",
-        sample_size_pattern=""
-    ):
+    country="",
+    standard="s",
+    locus="",
+    resolution_pattern="bigger_equal_than",
+    resolution=2,
+    region="",
+    ethnic="",
+    study_type="",
+    dataset_source="",
+    sample_year="",
+    sample_year_pattern="",
+    sample_size="",
+    sample_size_pattern="",
+):
     """Create URL for search of allele frequency net database. All arguments are documented [here](http://www.allelefrequencies.net/extaccess.asp)
     Args:
         country (str, optional): Country name to retrieve records from. Defaults to "".
         standard (str, optional): Filter study quality standard to this or higher. {'g', 's', 'a'} Gold, silver, all. Defaults to 's'.
         locus (str, optional): The locus to return allele data for. Defaults to "".
         resolution_pattern (str, optional): Resolution comparitor {'equal', 'different', 'less_than', 'bigger_than', 'less_equal_than', 'bigger_equal_than'}. Filter created using `resolution` and `resolution_pattern`. Defaults to "bigger_equal_than".
         resolution (int, optional): Number of fields of resolution of allele. Filter created using `resolution` and `resolution_pattern`. Defaults to 2.
@@ -51,88 +52,118 @@
         sample_size_pattern (str, optional): Pattern to compare sample size to. Filter created using sample_size and sample_size_pattern. {'equal', 'different', 'less_than', 'bigger_than', 'less_equal_than', 'bigger_equal_than'}. Defaults to "".
 
     Returns:
         str: URL to search allelefrequencies.net
     """
     base = "http://www.allelefrequencies.net/hla6006a.asp?"
     locus_type = "hla_locus_type=Classical&"
-    hla_locus = "hla_locus=%s&" %(locus)
-    country = "hla_country=%s&" %(country)
-    region = "hla_region=%s&" %(region)
-    ethnic = "hla_ethnic=%s&" %(ethnic)
-    study_type = "hla_study=%s&" %(study_type)
-    dataset_source = "hla_dataset_source=%s&" %(dataset_source)
-    sample_year = "hla_sample_year=%s&" %(sample_year)
-    sample_year_pattern = "hla_sample_year_pattern=%s&" %(sample_year_pattern)
-    sample_size = "hla_sample_size=%s&" %(sample_size)
-    sample_size_pattern = "hla_sample_size_pattern=%s&" %(sample_size_pattern)
-    hla_level_pattern = "hla_level_pattern=%s&" %(resolution_pattern)
-    hla_level = "hla_level=%s&" %(resolution)
-    standard = "standard=%s&" %standard
-    url = base + locus_type + hla_locus + country + hla_level_pattern + hla_level + standard + region + ethnic + study_type + dataset_source + sample_year + sample_year_pattern + sample_size + sample_size_pattern
+    hla_locus = "hla_locus=%s&" % (locus)
+    country = "hla_country=%s&" % (country)
+    region = "hla_region=%s&" % (region)
+    ethnic = "hla_ethnic=%s&" % (ethnic)
+    study_type = "hla_study=%s&" % (study_type)
+    dataset_source = "hla_dataset_source=%s&" % (dataset_source)
+    sample_year = "hla_sample_year=%s&" % (sample_year)
+    sample_year_pattern = "hla_sample_year_pattern=%s&" % (sample_year_pattern)
+    sample_size = "hla_sample_size=%s&" % (sample_size)
+    sample_size_pattern = "hla_sample_size_pattern=%s&" % (sample_size_pattern)
+    hla_level_pattern = "hla_level_pattern=%s&" % (resolution_pattern)
+    hla_level = "hla_level=%s&" % (resolution)
+    standard = "standard=%s&" % standard
+    url = (
+        base
+        + locus_type
+        + hla_locus
+        + country
+        + hla_level_pattern
+        + hla_level
+        + standard
+        + region
+        + ethnic
+        + study_type
+        + dataset_source
+        + sample_year
+        + sample_year_pattern
+        + sample_size
+        + sample_size_pattern
+    )
     return url
 
+
 def parseAF(bs):
     """Generate a dataframe from a given html page
 
     Args:
         bs (bs4.BeautifulSoup): BeautifulSoup object from allelefrequencies.net page
 
     Returns:
         pd.DataFrame: Table of allele, allele frequency, samplesize, and population
     """
     # Get the results table from the div `divGenDetail`
-    tab = bs.find('div', {'id': 'divGenDetail'}).find('table', {'class': 'tblNormal'})
+    tab = bs.find("div", {"id": "divGenDetail"}).find("table", {"class": "tblNormal"})
     # Get the column headers from the first row of the table
     columns = [
-        'line', 'allele', 'flag', 'population', 'carriers%',
-        'allele_freq', 'AF_graphic', 'sample_size', 'database',
-        'distribution','haplotype_association', 'notes'
-        ]
-    rows =[]
-    for row in tab.find_all('tr'):
-        rows.append(
-            [td.get_text(strip=True) for td in row.find_all('td')]
-            )
+        "line",
+        "allele",
+        "flag",
+        "population",
+        "carriers%",
+        "allele_freq",
+        "AF_graphic",
+        "sample_size",
+        "database",
+        "distribution",
+        "haplotype_association",
+        "notes",
+    ]
+    rows = []
+    for row in tab.find_all("tr"):
+        rows.append([td.get_text(strip=True) for td in row.find_all("td")])
     # Make dataframe of table rows
     # skip the first row as it's `th` headers
-    df = pd.DataFrame(rows[1:], columns = columns)
+    df = pd.DataFrame(rows[1:], columns=columns)
 
     # Get HLA loci
-    df['loci'] = df.allele.apply(lambda x: x.split("*")[0])
+    df["loci"] = df.allele.apply(lambda x: x.split("*")[0])
 
     # Drop unwanted columns
-    df = df[['allele', 'loci', 'population', 'allele_freq', 'carriers%', 'sample_size']]
+    df = df[["allele", "loci", "population", "allele_freq", "carriers%", "sample_size"]]
     return df
-   
+
+
 def Npages(bs):
     """How many pages of results are there?
 
     Args:
         bs (bs4.BeautifulSoup): BS object of allelefrequencies.net results page
 
     Returns:
         int: Total number of results pages
     """
     # Get the table with number of pages
-    navtab = bs.find('div', {'id': 'divGenNavig'}).find('table', {'class': 'table10'})
-    assert navtab, f"navtab does not evaluate to True. Check URL returns results in web browser."
-    # Get cell with ' of ' in 
-    pagesOfN = [td.get_text(strip=True) for td in navtab.find_all('td') if " of " in td.text]
+    navtab = bs.find("div", {"id": "divGenNavig"}).find("table", {"class": "table10"})
+    assert (
+        navtab
+    ), f"navtab does not evaluate to True. Check URL returns results in web browser."
+    # Get cell with ' of ' in
+    pagesOfN = [
+        td.get_text(strip=True) for td in navtab.find_all("td") if " of " in td.text
+    ]
     # Check single cell returned
-    assert len(pagesOfN) == 1, "divGenNavig should contain 1 of not %s" %len(pagesOfN)
+    assert len(pagesOfN) == 1, "divGenNavig should contain 1 of not %s" % len(pagesOfN)
     # Get total number of pages
     N = pagesOfN[0].split("of ")[1]
     N = int(N)
     return N
 
+
 def formatAF(AFtab, ignoreG=True):
     """Format allele frequency table.
     Convert sample_size and allele_freq to numeric data type.
-    Removes commas from sample size. Removes "(*)" from allele frequency if 
+    Removes commas from sample size. Removes "(*)" from allele frequency if
     `ignoreG` is `True`. `formatAF()` is used internally by combineAF and getAFdata by default.
 
     Args:
         AFtab (pd.DataFrame): Allele frequency data downloaded from allelefrequency.net using `getAFdata()`.
         ignoreG (bool, optional): Treat G group alleles as normal. See http://hla.alleles.org/alleles/g_groups.html for details. Defaults to True.
 
     Returns:
@@ -143,92 +174,100 @@
         df.sample_size = pd.to_numeric(df.sample_size.str.replace(",", ""))
     if df.allele_freq.dtype == "O":
         if ignoreG:
             df.allele_freq = df.allele_freq.str.replace("(*)", "", regex=False)
         df.allele_freq = pd.to_numeric(df.allele_freq)
     return df
 
+
 def getAFdata(base_url, format=True, ignoreG=True):
     """Get all allele frequency data from a search base url. Iterates over all
         pages regardless of which page is based.
 
     Args:
         base_url (str): URL for base search.
         format (bool): Format the downloaded data using `formatAF()`.
         ignoreG (bool): treat allele G groups as normal. See http://hla.alleles.org/alleles/g_groups.html for details. Default = True
 
     Returns:
         pd.DataFrame: allele frequency data parsed into a pandas dataframe
     """
     # Get BS object from base search
-    bs = BeautifulSoup(requests.get(base_url).text, 'html.parser')
+    bs = BeautifulSoup(requests.get(base_url).text, "html.parser")
     # How many pages of results
     N = Npages(bs)
-    print("%s pages of results" %N)
+    print("%s pages of results" % N)
     # iterate over pages, parse and combine data from each
     tabs = []
     for i in range(N):
         # print (" Parsing page %s" %(i+1))
-        print (" Parsing page %s" %(i+1), end="\r")
-        url = base_url + "page=" + str(i+1)
-        bs = BeautifulSoup(requests.get(url).text, 'html.parser')
+        print(" Parsing page %s" % (i + 1), end="\r")
+        url = base_url + "page=" + str(i + 1)
+        bs = BeautifulSoup(requests.get(url).text, "html.parser")
         tab = parseAF(bs)
         tabs.append(tab)
     print("Download complete")
     tabs = pd.concat(tabs)
     if format:
         try:
             tabs = formatAF(tabs, ignoreG)
         except:
             print("Formatting failed, non-numeric datatypes may remain.")
     return tabs
 
-def incomplete_studies(AFtab, llimit=0.95, ulimit=1.1, datasetID='population'):
+
+def incomplete_studies(AFtab, llimit=0.95, ulimit=1.1, datasetID="population"):
     """Report any studies with allele freqs that don't sum to 1
 
     Args:
         AFtab (pd.DataFrame): Dataframe containing multiple studies
         llimit (float, optional): Lower allele_freq sum limit that counts as complete. Defaults to 0.95.
         ulimit (float, optional): Upper allele_freq sum limit that will not be reported. Defaults to 1.1.
         datasetID (str): Unique identifier column for study
     """
-    poplocs = AFtab.groupby([datasetID, 'loci']).allele_freq.sum()
+    poplocs = AFtab.groupby([datasetID, "loci"]).allele_freq.sum()
     lmask = poplocs < llimit
-    if sum(lmask>0):
+    if sum(lmask > 0):
         print(poplocs[lmask])
         print(f"{sum(lmask)} studies have total allele frequency < {llimit}")
     umask = poplocs > ulimit
-    if sum(umask>0):
+    if sum(umask > 0):
         print(poplocs[umask])
         print(f"{sum(umask)} studies have total allele frequency > {ulimit}")
     incomplete = pd.concat([poplocs[lmask], poplocs[umask]])
     return incomplete
 
-def only_complete(AFtab, llimit=0.95, ulimit=1.1, datasetID='population'):
+
+def only_complete(AFtab, llimit=0.95, ulimit=1.1, datasetID="population"):
     """Returns only complete studies. Studies are only dropped if their population and loci are in noncomplete together.
     This prevents throwing away data if another loci in the population is incomplete
 
     Args:
         AFtab (pd.DataFrame): Dataframe containing multiple studies
         llimit (float, optional): Lower allele_freq sum limit that counts as complete. Defaults to 0.95.
         ulimit (float, optional): Upper allele_freq sum limit that will not be reported. Defaults to 1.1.
         datasetID (str): Unique identifier column for study. Defaults to 'population'.
 
     Returns:
         pd.DataFrame: Allele frequency data of multiple studies, but only complete studies.
     """
-    noncomplete = incomplete_studies(AFtab=AFtab, llimit=llimit, ulimit=ulimit, datasetID=datasetID)
+    noncomplete = incomplete_studies(
+        AFtab=AFtab, llimit=llimit, ulimit=ulimit, datasetID=datasetID
+    )
     # Returns False if population AND loci are in the noncomplete.index
     # AS A PAIR
     # This is important so that we don't throw away all data on a population
     # just because one loci is incomplete.
-    complete_mask = AFtab.apply(lambda x: (x[datasetID], x.loci) not in noncomplete.index, axis=1)
+    complete_mask = AFtab.apply(
+        lambda x: (x[datasetID], x.loci) not in noncomplete.index, axis=1
+    )
     df = AFtab[complete_mask]
     return df
 
+
 def check_resolution(AFtab):
     """Check if all alleles in AFtab have the same resolution.
     Will print the number of records with each resolution.
 
     Args:
         AFtab (pd.DataFrame): Allele frequency data
 
@@ -239,95 +278,135 @@
     resVC = resolution.value_counts()
     pass_check = len(resVC) == 1
     if not pass_check:
         print(resVC)
         print(f"Multiple resolutions in AFtab. Fix with decrease_resolution()")
     return pass_check
 
-def decrease_resolution(AFtab, newres, datasetID='population'):
+
+def decrease_resolution(AFtab, newres, datasetID="population"):
     """Decrease allele resolution to a specified value so all alleles have the same resolution.
 
     Args:
         AFtab (pd.DataFrame): Allele frequency data.
         newres (int): The desired number of fields for resolution.
         datasetID (str, optional): Column to use as stud identifier. Defaults to 'population'.
 
     Returns:
         pd.DataFrame: Allele frequency data with all alleles of requested resolution.
     """
     df = AFtab.copy()
     resolution = 1 + df.allele.str.count(":")
-    assert all(resolution >= newres), f"Some alleles have resolution below {newres} fields"
+    assert all(
+        resolution >= newres
+    ), f"Some alleles have resolution below {newres} fields"
     new_allele = df.allele.str.split(":").apply(lambda x: ":".join(x[:newres]))
     df.allele = new_allele
     collapsed = collapse_reduced_alleles(df, datasetID=datasetID)
     return collapsed
 
-def collapse_reduced_alleles(AFtab, datasetID='population'):
+
+def collapse_reduced_alleles(AFtab, datasetID="population"):
     df = AFtab.copy()
     # Group by alleles within datasets
-    grouped = df.groupby([datasetID,'allele'])
+    grouped = df.groupby([datasetID, "allele"])
     # Sum allele freq but keep other columns
     collapsed = grouped.apply(
         lambda row: [
             sum(row.allele_freq),
             row.sample_size.unique()[0],
             row.loci.unique()[0],
             len(row.loci.unique()),
-            len(row.sample_size.unique())
+            len(row.sample_size.unique()),
         ]
     )
     collapsed = pd.DataFrame(
         collapsed.tolist(),
         index=collapsed.index,
-        columns = ['allele_freq', 'sample_size', 'loci', '#loci', '#sample_sizes']
+        columns=["allele_freq", "sample_size", "loci", "#loci", "#sample_sizes"],
     ).reset_index()
     # Within a study each all identical alleles should have the same loci and sample size
-    assert all(collapsed['#loci'] == 1), "Multiple loci found for a single allele in a single population"
-    assert all(collapsed['#sample_sizes'] == 1), "Multiple sample_sizes found for a single allele in a single population"
-    collapsed = collapsed[['allele', 'loci','population','allele_freq','sample_size']]
+    assert all(
+        collapsed["#loci"] == 1
+    ), "Multiple loci found for a single allele in a single population"
+    assert all(
+        collapsed["#sample_sizes"] == 1
+    ), "Multiple sample_sizes found for a single allele in a single population"
+    collapsed = collapsed[
+        ["allele", "loci", "population", "allele_freq", "sample_size"]
+    ]
     alleles_unique_in_study(collapsed)
     return collapsed
 
-def unmeasured_alleles(AFtab, datasetID='population'):
+
+def unmeasured_alleles(AFtab, datasetID="population"):
     """When combining AF estimates, unreported alleles can inflate frequencies
         so AF sums to >1. Therefore we add unreported alleles with frequency zero.
 
     Args:
         AFtab (pd.DataFrame): Formatted allele frequency data
         datasetID (str): Unique identifier column for study
 
     Returns:
-        pd.DataFrame: Allele frequency data with all locus alleles reported 
+        pd.DataFrame: Allele frequency data with all locus alleles reported
             for each dataset
     """
     df = AFtab.copy()
     loci = df.loci.unique()
     # Iterate over loci separately
     for locus in loci:
         # Iterate over each dataset reporting that locus
         datasets = df[df.loci == locus][datasetID].unique()
         for dataset in datasets:
             # Single locus, single dataset
             datasetAF = df[(df[datasetID] == dataset) & (df.loci == locus)]
             # What was the sample size for this data?
             dataset_sample_size = datasetAF.sample_size.unique()
-            assert len(dataset_sample_size) == 1, "dataset_sample_size must be 1, not %s" %len(dataset_sample_size)
+            assert (
+                len(dataset_sample_size) == 1
+            ), "dataset_sample_size must be 1, not %s" % len(dataset_sample_size)
             dataset_sample_size = dataset_sample_size[0]
             # Get all alleles for this locus (across datasets)
             ualleles = df[df.loci == locus].allele.unique()
             # Which of these alleles are not in this dataset?
-            missing_alleles = [allele for allele in ualleles if not allele in datasetAF.allele.values]
-            missing_rows = [(al, locus, dataset, 0, 0, dataset_sample_size) for al in missing_alleles]
-            missing_rows = pd.DataFrame(missing_rows, columns=['allele','loci',datasetID,'allele_freq','carriers%','sample_size'])
+            missing_alleles = [
+                allele for allele in ualleles if not allele in datasetAF.allele.values
+            ]
+            missing_rows = [
+                (al, locus, dataset, 0, 0, dataset_sample_size)
+                for al in missing_alleles
+            ]
+            missing_rows = pd.DataFrame(
+                missing_rows,
+                columns=[
+                    "allele",
+                    "loci",
+                    datasetID,
+                    "allele_freq",
+                    "carriers%",
+                    "sample_size",
+                ],
+            )
             # Add them in with zero frequency
             df = pd.concat([df, missing_rows], ignore_index=True)
     return df
 
-def combineAF(AFtab, weights='2n', alpha = [], datasetID='population', format=True, ignoreG=True, add_unmeasured=True, complete=True, resolution=True, unique=True):
+
+def combineAF(
+    AFtab,
+    weights="2n",
+    alpha=[],
+    datasetID="population",
+    format=True,
+    ignoreG=True,
+    add_unmeasured=True,
+    complete=True,
+    resolution=True,
+    unique=True,
+):
     """Combine allele frequencies from multiple studies. `datasetID` is the unique identifier for studies to combine.
     Allele frequencies combined using a Dirichlet distribution where each study's contribution to the concentration parameter is $2 * sample_size * allele_frequency$.
     Sample size is doubled to get `2n` due to diploidy. If an alternative `weights` is set it is not doubled.
     The total concentration parameter of the Dirichlet distribution is the contributions from all studies plus the prior `alpha`.
     If `alpha` is not set the prior defaults to 1 observation of each allele.
 
     Args:
@@ -349,133 +428,149 @@
         *c* is the observations used for the Dirichlet distribution.
         *sample_size* is the total sample size of all combined studies.
         *wav* is the weighted average.
     """
     df = AFtab.copy()
     single_loci(df)
     if unique:
-        assert alleles_unique_in_study(df, datasetID=datasetID), "The same allele appears multiple times in a dataset"
+        assert alleles_unique_in_study(
+            df, datasetID=datasetID
+        ), "The same allele appears multiple times in a dataset"
     if complete:
-        assert incomplete_studies(df, datasetID=datasetID).empty, "AFtab contains studies with AF that doesn't sum to 1. Check incomplete_studies(AFtab)"
+        assert incomplete_studies(
+            df, datasetID=datasetID
+        ).empty, "AFtab contains studies with AF that doesn't sum to 1. Check incomplete_studies(AFtab)"
     if resolution:
-        assert check_resolution(df), "AFtab conains alleles at multiple resolutions, check check_resolution(AFtab)"
+        assert check_resolution(
+            df
+        ), "AFtab conains alleles at multiple resolutions, check check_resolution(AFtab)"
     if format:
         df = formatAF(df, ignoreG)
     if add_unmeasured:
         df = unmeasured_alleles(df, datasetID)
     try:
-        df['2n'] = df.sample_size * 2
+        df["2n"] = df.sample_size * 2
     except:
         print("column '2n' could not be created")
-    df['c'] =  df.allele_freq * df[weights]
-    grouped = df.groupby('allele', sort=True)
+    df["c"] = df.allele_freq * df[weights]
+    grouped = df.groupby("allele", sort=True)
     combined = grouped.apply(
         lambda row: [
-        row.name,
-        row.loci.unique()[0],
-        np.average(row.allele_freq, weights=row[weights]),
-        row.c.sum(),
-        row.sample_size.sum()
+            row.name,
+            row.loci.unique()[0],
+            np.average(row.allele_freq, weights=row[weights]),
+            row.c.sum(),
+            row.sample_size.sum(),
         ]
     )
     combined = pd.DataFrame(
-        combined.tolist(),
-        columns = ['allele', 'loci',
-            'wav',
-            'c', 'sample_size']
+        combined.tolist(), columns=["allele", "loci", "wav", "c", "sample_size"]
     )
     combined = combined.reset_index(drop=True)
     # Check that all alleles in a locus have the same sample size
     # after merging
     if duplicated_sample_size(combined):
         id_duplicated_allele(grouped)
     if not alpha:
         alpha = default_prior(len(combined.allele))
-    combined['alpha'] = alpha
+    combined["alpha"] = alpha
     # Calculate Dirichlet mean for each allele
-    combined['allele_freq'] = sp.stats.dirichlet(combined.alpha + combined.c).mean()
+    combined["allele_freq"] = sp.stats.dirichlet(combined.alpha + combined.c).mean()
 
     return combined
 
+
 def default_prior(k):
     """Calculate a default prior, 1 observation of each class.
 
     Args:
         k (int): Number of classes in the Dirichlet distribution.
 
     Returns:
         list: List of k 1s to use as prior.
     """
     alpha = [1] * k
     return alpha
 
+
 def single_loci(AFtab):
     """Check that allele frequency data is only of one locus
 
     Args:
         AFtab (pd.DataFrame): Allele frequency data
     """
     assert len(AFtab.loci.unique()) == 1, f"'AFtab' must conatain only 1 loci"
 
-def alleles_unique_in_study(AFtab, datasetID='population'):
+
+def alleles_unique_in_study(AFtab, datasetID="population"):
     """Are all alleles unique in each study? Checks that no alleles are reported more than once in a single study. Study is defined by `datasetID`.
 
     Args:
         AFtab (pd.DataFrame): Allele frequency data
         datasetID (str, optional): Unique identifier column to define study. Defaults to 'population'.
 
     Returns:
         bool: `True` on if no alleles occur more than once in any study, otherwise `False`.
     """
     df = AFtab.copy()
-    grouped = df.groupby([datasetID,'allele'])
+    grouped = df.groupby([datasetID, "allele"])
     # Are allele alleles unique? i.e. do any occur multiple times in grouping?
-    unique = grouped.size()[grouped.size()>1].empty
+    unique = grouped.size()[grouped.size() > 1].empty
     if not unique:
         print(f"Non unique alleles in study, is datasetID correct? {datasetID}")
-        print(grouped.size()[grouped.size()>1])
+        print(grouped.size()[grouped.size() > 1])
     return unique
 
+
 def duplicated_sample_size(AFtab):
     """Returns True if any loci has more than 1 unique sample size"""
-    locus_sample_sizes = AFtab.groupby('loci').sample_size.apply(lambda x: len(x.unique()))
+    locus_sample_sizes = AFtab.groupby("loci").sample_size.apply(
+        lambda x: len(x.unique())
+    )
     return any(locus_sample_sizes != 1)
 
+
 def id_duplicated_allele(grouped):
-    """ Reports the allele that has mupltiple sample sizes """
+    """Reports the allele that has mupltiple sample sizes"""
     duplicated_population = grouped.population.apply(lambda x: any(x.duplicated()))
-    assert all(~duplicated_population), "duplicated population within allele %s" %duplicated_population[duplicated_population].index.tolist()
+    assert all(~duplicated_population), (
+        "duplicated population within allele %s"
+        % duplicated_population[duplicated_population].index.tolist()
+    )
+
 
 def population_coverage(p):
     """Calculate the proportion of people with at least 1 copy of this allele
         assuming HWE.
 
     Args:
         p (float): Allele frequency
 
     Returns:
         float: Sum of homozygotes and heterozygotes for this allele
     """
-    q = 1-p
+    q = 1 - p
     homo = p**2
-    hetero = 2*p*q
+    hetero = 2 * p * q
     return homo + hetero
 
+
 def betaAB(alpha):
     """Given the alpha vector defining a Dirichlet distribution calculate the a b values for all composite beta distributions.
 
     Args:
         alpha (list): Values defining a Dirichlet distribution. This will be the prior (for a naive distribution) or the prior + caf.c for a posterior distribution.
 
     Returns:
         list: List of a b values defining beta values, i.e. for each allele it is the number of times it was and wasn't observed.
     """
-    ab = [(a,sum(alpha)-a) for a in alpha]
+    ab = [(a, sum(alpha) - a) for a in alpha]
     return ab
 
+
 # def betaCI(a,b,credible_interval=0.95):
 #     """Calculat the central credible interval of a beta distribution
 
 #     Args:
 #         a (float): Beta shape parameter `a`, i.e. the number of times the allele was observed.
 #         b (float): Beta shape parameter `b`, i.e. the number of times the allele was not observed.
 #         credible_interval (float, optional): The size of the credible interval requested. Defaults to 0.95.
@@ -504,53 +599,57 @@
 #     """
 #     ab = betaAB(
 #         caf.alpha + caf.c,
 #     )
 #     ci = [betaCI(a, b, credible_interval) for a,b in ab]
 #     return ci
 
+
 def plot_prior(concentration, ncol=2, psteps=1000, labels=""):
     """Plot probability density function for prior values.
 
     Args:
         concentration (list): Vector of the prior Dirichlet concentration values.
         ncol (int, optional): Number of columns. Defaults to 2.
         labels (list, optional): Labels for elements of concentration in the same order. Defaults to "".
     """
     ab = betaAB(concentration)
     pline = np.linspace(0, 1, psteps)
-    nrow = math.ceil(len(concentration)/ncol)
+    nrow = math.ceil(len(concentration) / ncol)
     fig, ax = plt.subplots(nrow, ncol, sharex=True)
     fig.suptitle("Probability density")
     # If labels is a list nothing happens,
     # But if it's a series it converts to a list
     labels = list(labels)
     if not labels:
         labels = [""] * len(concentration)
-    assert len(concentration) == len(labels), "concentration must be same length as labels"
-    for i,alpha in enumerate(concentration):
-        a,b = ab[i]
-        bd = sp.stats.beta(a,b)
+    assert len(concentration) == len(
+        labels
+    ), "concentration must be same length as labels"
+    for i, alpha in enumerate(concentration):
+        a, b = ab[i]
+        bd = sp.stats.beta(a, b)
         pdf = [bd.pdf(p) for p in pline]
         ax.flat[i].plot(pline, pdf)
         ax.flat[i].set_title(labels[i])
-    for axi in ax[-1,:]:
-        axi.set(xlabel='Allele freq')
-    for axi in ax[:,0]:
-        axi.set(ylabel='PDF')
+    for axi in ax[-1, :]:
+        axi.set(xlabel="Allele freq")
+    for axi in ax[:, 0]:
+        axi.set(ylabel="PDF")
     plt.show()
 
+
 def plotAF(
     caf=pd.DataFrame(),
     AFtab=pd.DataFrame(),
-    cols = list(mcolors.TABLEAU_COLORS.keys()),
+    cols=list(mcolors.TABLEAU_COLORS.keys()),
     datasetID="population",
     hdi=pd.DataFrame(),
-    compound_mean=pd.DataFrame()
-    ):
+    compound_mean=pd.DataFrame(),
+):
     """Plot combined allele frequencies, individual allele frequencies,
     and credible intervals on combined allele frequency estimates.
     Credible interval is only plotted if a value is given for `hdi`.
     The plotted Credible interval is whatever was passed to HLAfreq_pymc.AFhdi() when calculating hdi.
 
     Args:
         caf (pd.DataFrame, optional): Combined allele frequency estimates from HLAfreq.combineAF. Defaults to pd.DataFrame().
@@ -561,53 +660,50 @@
         hdi (pd.DataFrame, optional): The high density interval object to plot credible intervals. Produced by HLAfreq.HLA_pymc.AFhdi(). Defaults to pd.DataFrame().
         compound_mean (pd.DataFrame, optional): The high density interval object to plot post_mean. Produced by HLAfreq.HLA_pymc.AFhdi(). Defaults to pd.DataFrame().
     """
     # Plot allele frequency for each dataset
     if not AFtab.empty:
         # Cols must be longer than the list of alleles
         # If not, repeat the list of cols
-        repeat_cols = np.ceil(len(AFtab[datasetID])/len(cols))
+        repeat_cols = np.ceil(len(AFtab[datasetID]) / len(cols))
         repeat_cols = int(repeat_cols)
         cols = cols * repeat_cols
         # Make a dictionary mapping datasetID to colours
         cmap = dict(zip(AFtab[datasetID].unique(), cols))
         plt.scatter(
-            x = AFtab.allele_freq,
-            y = AFtab.allele,
-            c = [cmap[x] for x in AFtab[datasetID]],
-            alpha = 0.7,
-            zorder=2
-            )
+            x=AFtab.allele_freq,
+            y=AFtab.allele,
+            c=[cmap[x] for x in AFtab[datasetID]],
+            alpha=0.7,
+            zorder=2,
+        )
     # Plot combined allele frequency
     if not caf.empty:
         plt.scatter(
-            x = caf.allele_freq,
-            y = caf.allele,
-            edgecolors='black',
-            facecolors='none',
-            zorder=3
-            )
+            x=caf.allele_freq,
+            y=caf.allele,
+            edgecolors="black",
+            facecolors="none",
+            zorder=3,
+        )
     # Plot high density interval
     if not hdi.empty:
         # assert not AFtab.empty, "AFtab is needed to calculate credible interval"
         # from HLAfreq import HLAfreq_pymc as HLAhdi
         # print("Fitting model with PyMC, make take a few seconds")
         # hdi = HLAhdi.AFhdi(AFtab=AFtab, weights=weights, datasetID=datasetID, credible_interval=credible_interval, conc_mu=conc_mu, conc_sigma=conc_sigma)
         for interval in hdi.iterrows():
             # .iterrows returns a index and data as a tuple for each row
             plt.hlines(
-                y = interval[1]['allele'],
-                xmin = interval[1]['lo'],
-                xmax = interval[1]['hi'],
-                color="black"
+                y=interval[1]["allele"],
+                xmin=interval[1]["lo"],
+                xmax=interval[1]["hi"],
+                color="black",
             )
     if not compound_mean.empty:
         for row in compound_mean.iterrows():
             plt.scatter(
-                y = row[1]['allele'],
-                x = row[1]['post_mean'],
-                color = 'black',
-                marker = "|"
+                y=row[1]["allele"], x=row[1]["post_mean"], color="black", marker="|"
             )
     plt.xlabel("Allele frequency")
     plt.grid(zorder=0)
     plt.show()
```

### Comparing `HLAfreq-0.0.1.dev4/src/HLAfreq/HLAfreq_pymc.py` & `HLAfreq-0.0.2/src/HLAfreq/HLAfreq_pymc.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,75 +1,103 @@
 import math
 import pymc as pm
 import numpy as np
 import arviz as az
 import pandas as pd
 import HLAfreq
 
-def _make_c_array(AFtab, weights="2n", datasetID="population",
-                  format=True, ignoreG=True, add_unmeasured=True, complete=True, resolution=True, unique=True):
+
+def _make_c_array(
+    AFtab,
+    weights="2n",
+    datasetID="population",
+    format=True,
+    ignoreG=True,
+    add_unmeasured=True,
+    complete=True,
+    resolution=True,
+    unique=True,
+):
     df = AFtab.copy()
     HLAfreq.single_loci(df)
     if unique:
-        assert HLAfreq.alleles_unique_in_study(df, datasetID=datasetID), "The same allele appears multiple times in a dataset"
+        assert HLAfreq.alleles_unique_in_study(
+            df, datasetID=datasetID
+        ), "The same allele appears multiple times in a dataset"
     if complete:
-        assert HLAfreq.incomplete_studies(df, datasetID=datasetID).empty, "AFtab contains studies with AF that doesn't sum to 1. Check incomplete_studies(AFtab)"
+        assert HLAfreq.incomplete_studies(
+            df, datasetID=datasetID
+        ).empty, "AFtab contains studies with AF that doesn't sum to 1. Check incomplete_studies(AFtab)"
     if resolution:
-        assert HLAfreq.check_resolution(df), "AFtab conains alleles at multiple resolutions, check check_resolution(AFtab)"
+        assert HLAfreq.check_resolution(
+            df
+        ), "AFtab conains alleles at multiple resolutions, check check_resolution(AFtab)"
     if format:
         df = HLAfreq.formatAF(df, ignoreG)
     if add_unmeasured:
         df = HLAfreq.unmeasured_alleles(df, datasetID)
     try:
-        df['2n'] = df.sample_size * 2
+        df["2n"] = df.sample_size * 2
     except:
         print("column '2n' could not be created")
-    df['c'] =  df.allele_freq * df[weights]
+    df["c"] = df.allele_freq * df[weights]
 
     # Sort by alleles so it matches the combined alleles
-    df = df.sort_values('allele')
+    df = df.sort_values("allele")
     c_array = np.array(df.groupby(datasetID).c.apply(list).tolist())
     allele_names = sorted(df.allele.unique())
     # Imperfect check that allele order matches between caf and c_array.
     # caf is sorted automatically so should match sorted AFloc
     # Therefore we check that sorted AFloc matches c_array
     # The check is that the sum of allele i is the same
-    for a,b in zip(
-        np.apply_along_axis(sum, 0, c_array),
-        df.groupby('allele').c.sum()
-        ):
-        assert math.isclose(a,b), "Error making c_array sum of single allele frequency differs between c_array and AFloc"
+    for a, b in zip(np.apply_along_axis(sum, 0, c_array), df.groupby("allele").c.sum()):
+        assert math.isclose(
+            a, b
+        ), "Error making c_array sum of single allele frequency differs between c_array and AFloc"
     return c_array, allele_names
 
+
 def _fit_Dirichlet_Multinomial(c_array, prior=[], conc_mu=1, conc_sigma=1):
     # Number of populations
     n = c_array.shape[0]
     # number of alleles
     k = c_array.shape[1]
 
     # Round c array so that it and effective ssamples are whole numbers
     # for the multinomial
     c_array = np.round(c_array)
     effective_samples = np.apply_along_axis(sum, 1, c_array)
-    if len(prior)==0:
+    if len(prior) == 0:
         prior = HLAfreq.default_prior(k)
     assert len(prior) == k, "For k alleles, prior must be length k"
     with pm.Model() as mod:
-        frac = pm.Dirichlet('frac', a=prior)
-        conc = pm.Lognormal('conc', mu=conc_mu, sigma=conc_sigma)
-        y = pm.DirichletMultinomial('y', n=effective_samples, a=frac*conc, shape=(n,k), observed=c_array)
+        frac = pm.Dirichlet("frac", a=prior)
+        conc = pm.Lognormal("conc", mu=conc_mu, sigma=conc_sigma)
+        y = pm.DirichletMultinomial(
+            "y", n=effective_samples, a=frac * conc, shape=(n, k), observed=c_array
+        )
 
     with mod:
         idata = pm.sample()
     return idata
 
-def AFhdi(AFtab, weights="2n", datasetID="population", credible_interval=0.95, prior=[], conc_mu=1, conc_sigma=1, compare_models=True):
+
+def AFhdi(
+    AFtab,
+    weights="2n",
+    datasetID="population",
+    credible_interval=0.95,
+    prior=[],
+    conc_mu=1,
+    conc_sigma=1,
+    compare_models=True,
+):
     """Calculate mean and high posterior density interval on combined allele frequency.
     Fits a Marginalized Dirichlet-Multinomial Model in PyMc as described [here](https://docs.pymc.io/en/v3/pymc-examples/examples/mixture_models/dirichlet_mixture_of_multinomials.html).
-    
+
     In brief, the global allele frequency is modelled as a Dirichlet distribution,
     and each population (defined by `datasetID`) is a Dirichlet distribution draw from
     the global Dirichlet distribution, and the observed allele count data of that
     population is multinomial count data drawn from the population Dirichlet distribution.
 
     The observed allele frequencies are transformed into allele counts using `weights`.
     The variability of population allele frequencies around the global mean is defined
@@ -89,35 +117,41 @@
         np.array: Pairs of high density interval limits, allele name, and posterior mean.
             as a 4 by n array.
             In alphabetical order of alleles, regardless of input order.
             This way it matches the output of combineAF().
     """
 
     c_array, allele_names = _make_c_array(AFtab, weights, datasetID)
-    idata = _fit_Dirichlet_Multinomial(c_array, prior, conc_mu=conc_mu, conc_sigma=conc_sigma)
+    idata = _fit_Dirichlet_Multinomial(
+        c_array, prior, conc_mu=conc_mu, conc_sigma=conc_sigma
+    )
     hdi = az.hdi(idata, hdi_prob=credible_interval).frac.values
-    post_mean = az.summary(idata, var_names='frac')['mean']
-    post = pd.DataFrame([hdi[:,0], hdi[:,1], allele_names, post_mean]).T
-    post.columns = ['lo','hi','allele','post_mean']
+    post_mean = az.summary(idata, var_names="frac")["mean"]
+    post = pd.DataFrame([hdi[:, 0], hdi[:, 1], allele_names, post_mean]).T
+    post.columns = ["lo", "hi", "allele", "post_mean"]
     if compare_models:
         compare_estimates(AFtab, post, datasetID)
     return post
 
+
 def compare_estimates(AFtab, hdi, datasetID):
     """Does the defaul estimate of `allele_freq` sit within the compound
     model's estimated credible intervals? If not, print warnings.
 
     Args:
         AFtab (pd.DataFrame): Table of allele frequency data
         hdi (np.array): Pairs of high density interval limits, allele name, and posterior mean from compound model.
         datasetID (str, optional): Unique identifier column for study.
     """
-    
+
     caf = HLAfreq.combineAF(AFtab, datasetID=datasetID)
     caf = pd.merge(caf, hdi, how="left", on="allele")
     mask = (caf.allele_freq < caf.lo) | (caf.allele_freq > caf.hi)
     if mask.sum() > 0:
         print()
-        print("WARNING: The default allele frequency estimate is outside of the CI estimated by the compound method for some alleles!")
-        print("There are several possible reasons, see the credible intervals example: https://github.com/Vaccitech/HLAfreq/blob/main/examples/credible_intervals.ipynb")
+        print(
+            "WARNING: The default allele frequency estimate is outside of the CI estimated by the compound method for some alleles!"
+        )
+        print(
+            "There are several possible reasons, see the credible intervals example: https://github.com/Vaccitech/HLAfreq/blob/main/examples/credible_intervals.ipynb"
+        )
         print("If you have set `credible_interval` to < 0.95, this may be a non-issue.")
-
```

### Comparing `HLAfreq-0.0.1.dev4/src/HLAfreq/data/HLA1supertypes_Sidney2008.csv` & `HLAfreq-0.0.2/src/HLAfreq/data/HLA1supertypes_Sidney2008.csv`

 * *Files identical despite different names*

### Comparing `HLAfreq-0.0.1.dev4/src/HLAfreq/data/countries.csv` & `HLAfreq-0.0.2/src/HLAfreq/data/countries.csv`

 * *Files identical despite different names*

### Comparing `HLAfreq-0.0.1.dev4/src/HLAfreq.egg-info/PKG-INFO` & `HLAfreq-0.0.2/src/HLAfreq.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: HLAfreq
-Version: 0.0.1.dev4
+Version: 0.0.2
 Summary: Download and combine HLA frequency data from multiple studies
 Home-page: https://github.com/Vaccitech/HLAfreq
 Author: David Wells
 Author-email: david.wells@vaccitech.co.uk
 Project-URL: Tracker, https://github.com/Vaccitech/HLAfreq/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: OS Independent
```

### Comparing `HLAfreq-0.0.1.dev4/tests/test_single_country_caf.py` & `HLAfreq-0.0.2/tests/test_single_country_caf.py`

 * *Files 23% similar despite different names*

```diff
@@ -6,48 +6,62 @@
 """
 import pytest
 import HLAfreq
 
 import pandas as pd
 from scipy.stats import dirichlet
 
-dfa =  pd.DataFrame({
-    'allele':['A*02:03','A*02:05','A*02:07'],
-    'loci':['A','A','A'],
-    'population':['test1','test1','test1'],
-    'allele_freq':[0.1, 0.3, 0.6],
-    'sample_size':[10,10,10]
-})
-dfb =  pd.DataFrame({
-    'allele':['A*02:03','A*02:05:01','A*02:05:02'],
-    'loci':['A','A', 'A'],
-    'population':['test2','test2', 'test2'],
-    'allele_freq':[0.5, 0.25, 0.25],
-    'sample_size':[5, 5, 5]
-})
-dfc =  pd.DataFrame({
-    'allele':['A*02:03','A*02:05'],
-    'loci':['A','A'],
-    'population':['test3','test3'],
-    'allele_freq':[0.5, 0.1],
-    'sample_size':[5, 5]
-})
+dfa = pd.DataFrame(
+    {
+        "allele": ["A*02:03", "A*02:05", "A*02:07"],
+        "loci": ["A", "A", "A"],
+        "population": ["test1", "test1", "test1"],
+        "allele_freq": [0.1, 0.3, 0.6],
+        "sample_size": [10, 10, 10],
+    }
+)
+dfb = pd.DataFrame(
+    {
+        "allele": ["A*02:03", "A*02:05:01", "A*02:05:02"],
+        "loci": ["A", "A", "A"],
+        "population": ["test2", "test2", "test2"],
+        "allele_freq": [0.5, 0.25, 0.25],
+        "sample_size": [5, 5, 5],
+    }
+)
+dfc = pd.DataFrame(
+    {
+        "allele": ["A*02:03", "A*02:05"],
+        "loci": ["A", "A"],
+        "population": ["test3", "test3"],
+        "allele_freq": [0.5, 0.1],
+        "sample_size": [5, 5],
+    }
+)
 aftab = pd.concat([dfa, dfb, dfc])
 
 # Drop incomplete test3
 aftab = HLAfreq.only_complete(aftab)
+
+
 def test_drop_incomplete_test():
-    assert not any(aftab.population == 'test3')
+    assert not any(aftab.population == "test3")
+
 
 # Collapse 3 field alleles
 aftab = HLAfreq.decrease_resolution(aftab, 2)
+
+
 def test_resolution_decreased_correctly():
-    mask = (aftab.allele=="A*02:05") & (aftab.population=='test2')
+    mask = (aftab.allele == "A*02:05") & (aftab.population == "test2")
     assert sum(mask) == 1
     collapsed = aftab[mask]
     assert all(collapsed.allele_freq == 0.5)
     assert all(collapsed.sample_size == 5)
 
+
 # Combine allele frequencies
 caf = HLAfreq.combineAF(aftab)
+
+
 def test_combined_allele_freq():
-    assert all(caf.allele_freq == dirichlet([8,12,13]).mean())
+    assert all(caf.allele_freq == dirichlet([8, 12, 13]).mean())
```

