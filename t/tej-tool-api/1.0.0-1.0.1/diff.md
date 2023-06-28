# Comparing `tmp/tej-tool-api-1.0.0.tar.gz` & `tmp/tej-tool-api-1.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tej-tool-api-1.0.0.tar", last modified: Thu Jun  8 07:04:24 2023, max compression
+gzip compressed data, was "tej-tool-api-1.0.1.tar", last modified: Wed Jun 28 03:40:59 2023, max compression
```

## Comparing `tej-tool-api-1.0.0.tar` & `tej-tool-api-1.0.1.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxrwxrwx   0        0        0        0 2023-06-08 07:04:24.121853 tej-tool-api-1.0.0/
--rw-rw-rw-   0        0        0     5553 2023-06-08 07:04:24.121853 tej-tool-api-1.0.0/PKG-INFO
--rw-rw-rw-   0        0        0     5143 2023-06-08 06:00:16.000000 tej-tool-api-1.0.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-08 07:04:24.121853 tej-tool-api-1.0.0/TejTOolAPI/
--rw-rw-rw-   0        0        0      197 2023-05-19 07:13:38.000000 tej-tool-api-1.0.0/TejTOolAPI/Error.py
--rw-rw-rw-   0        0        0     8312 2023-06-05 01:09:57.000000 tej-tool-api-1.0.0/TejTOolAPI/Map_Dask_API.py
--rw-rw-rw-   0        0        0    10457 2023-06-05 01:09:57.000000 tej-tool-api-1.0.0/TejTOolAPI/TejToolAPI.py
--rw-rw-rw-   0        0        0     1551 2023-06-01 01:35:27.000000 tej-tool-api-1.0.0/TejTOolAPI/parameters.py
-drwxrwxrwx   0        0        0        0 2023-06-08 07:04:24.115348 tej-tool-api-1.0.0/TejTOolAPI/tables/
--rw-rw-rw-   0        0        0    38911 2023-06-05 09:52:31.000000 tej-tool-api-1.0.0/TejTOolAPI/tables/columns_group.xlsx
--rw-rw-rw-   0        0        0   137941 2023-05-19 07:13:38.000000 tej-tool-api-1.0.0/TejTOolAPI/tables/mktboard.csv
--rw-rw-rw-   0        0        0       42 2023-06-08 07:04:24.121853 tej-tool-api-1.0.0/setup.cfg
--rw-rw-rw-   0        0        0     1450 2023-06-08 07:04:17.000000 tej-tool-api-1.0.0/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-08 07:04:24.121853 tej-tool-api-1.0.0/tej_tool_api.egg-info/
--rw-rw-rw-   0        0        0     5553 2023-06-08 07:04:23.000000 tej-tool-api-1.0.0/tej_tool_api.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      362 2023-06-08 07:04:24.000000 tej-tool-api-1.0.0/tej_tool_api.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-08 07:04:23.000000 tej-tool-api-1.0.0/tej_tool_api.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       44 2023-06-08 07:04:23.000000 tej-tool-api-1.0.0/tej_tool_api.egg-info/requires.txt
--rw-rw-rw-   0        0        0       22 2023-06-08 07:04:23.000000 tej-tool-api-1.0.0/tej_tool_api.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 03:40:59.384963 tej-tool-api-1.0.1/
+-rw-rw-rw-   0        0        0     5553 2023-06-28 03:40:59.383965 tej-tool-api-1.0.1/PKG-INFO
+-rw-rw-rw-   0        0        0     5143 2023-06-08 06:00:16.000000 tej-tool-api-1.0.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 03:40:59.372905 tej-tool-api-1.0.1/TejTOolAPI/
+-rw-rw-rw-   0        0        0      197 2023-05-19 07:13:38.000000 tej-tool-api-1.0.1/TejTOolAPI/Error.py
+-rw-rw-rw-   0        0        0    15389 2023-06-12 05:47:06.000000 tej-tool-api-1.0.1/TejTOolAPI/Map_Dask_API.py
+-rw-rw-rw-   0        0        0    10547 2023-06-12 05:47:06.000000 tej-tool-api-1.0.1/TejTOolAPI/TejToolAPI.py
+-rw-rw-rw-   0        0        0     1542 2023-06-12 05:47:06.000000 tej-tool-api-1.0.1/TejTOolAPI/parameters.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:40:59.365927 tej-tool-api-1.0.1/TejTOolAPI/tables/
+-rw-rw-rw-   0        0        0    38911 2023-06-05 09:52:31.000000 tej-tool-api-1.0.1/TejTOolAPI/tables/columns_group.xlsx
+-rw-rw-rw-   0        0        0   137941 2023-05-19 07:13:38.000000 tej-tool-api-1.0.1/TejTOolAPI/tables/mktboard.csv
+-rw-rw-rw-   0        0        0       42 2023-06-28 03:40:59.384963 tej-tool-api-1.0.1/setup.cfg
+-rw-rw-rw-   0        0        0     1490 2023-06-28 03:40:19.000000 tej-tool-api-1.0.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:40:59.380973 tej-tool-api-1.0.1/tej_tool_api.egg-info/
+-rw-rw-rw-   0        0        0     5553 2023-06-28 03:40:58.000000 tej-tool-api-1.0.1/tej_tool_api.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      362 2023-06-28 03:40:59.000000 tej-tool-api-1.0.1/tej_tool_api.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 03:40:58.000000 tej-tool-api-1.0.1/tej_tool_api.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       65 2023-06-28 03:40:58.000000 tej-tool-api-1.0.1/tej_tool_api.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       22 2023-06-28 03:40:58.000000 tej-tool-api-1.0.1/tej_tool_api.egg-info/top_level.txt
```

### Comparing `tej-tool-api-1.0.0/PKG-INFO` & `tej-tool-api-1.0.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tej-tool-api
-Version: 1.0.0
+Version: 1.0.1
 Summary: Package to fetch a large quantity of data from tejapi.
 Home-page: https://api.tej.com.tw
 Author: tej
 Author-email: tej@tej.com.tw
 Maintainer: tej api Development Team
 Maintainer-email: tej@tej.com
 License: MIT
```

### Comparing `tej-tool-api-1.0.0/README.md` & `tej-tool-api-1.0.1/README.md`

 * *Files identical despite different names*

### Comparing `tej-tool-api-1.0.0/TejTOolAPI/TejToolAPI.py` & `tej-tool-api-1.0.1/TejTOolAPI/TejToolAPI.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,68 +1,65 @@
 import tejapi 
 tejapi.ApiConfig.ignoretz = True
 tejapi.ApiConfig.page_limit=10000
 import dask.dataframe as dd
 import pandas as pd
 import gc
-from TejToolAPI import parameters as para
+from . import parameters as para
 import dask
 import dask.dataframe as dd
 
 
 
-def get_history_data(ticker:list, columns:list = [], fin_type:list = ['A','Q','TTM'], include_self_acc:str = 'N', **kwargs):
+def get_history_data(tickers:list, columns:list = [], fin_type:list = ['A','Q','TTM'], include_self_acc:str = 'N', **kwargs):
     # Setting default value of the corresponding parameters
     start = kwargs.get('start', para.default_start)
     end = kwargs.get('end', para.default_end)
     transfer_to_chinese = kwargs.get('transfer_to_chinese', False)
     npartitions = kwargs.get('npartitions',  para.npartitions_local)
-    all_tables = triggers(ticker = ticker, columns= columns, start= start, end= end, fin_type= fin_type, include_self_acc= include_self_acc, npartitions = npartitions)
+    all_tables = triggers(ticker = tickers, columns= columns, start= start, end= end, fin_type= fin_type, include_self_acc= include_self_acc, npartitions = npartitions)
+
+    def process_fin_data(all_tables, variable, tickers, start, end):
+        # transfer to daily basis
+        days = para.dask_mpf.generate_multicalendars(tickers, start = start, end = end)
+        all_tables[variable] = dd.merge(days, all_tables[variable], left_on=['coid','all_dates'], right_on=['coid', 'annd'], how='left')
+        
+        # Drop mdate column
+        all_tables[variable] = all_tables[variable].drop(columns = 'mdate')
+
+        # Delete the redundant dataframe to release memory space
+        del days
+        gc.collect()
+
+        # Filling NaN with the precending value
+        all_tables[variable] = all_tables[variable].groupby('coid', group_keys = False).apply(para.dask_mpf.fillna_multicolumns, meta = all_tables[variable])
+        
+        return all_tables[variable]
     
+       
     # 針對自結損益和財簽資料作處理
-    if include_self_acc == 'Y':
-        try:
-            # Concate fin_self_acc with fin_auditor
-            data_concat = pd.concat([all_tables['fin_self_acc'], all_tables['fin_auditor']]).reset_index(drop=True)
-            all_tables['fin_self_acc'] = data_concat.drop_duplicates(subset=['coid','mdate','annd'], keep='last')
-
-            # transfer to daily basis
-            days = para.dask_mpf.generate_multicalendars(ticker, start = start, end = end)
-            all_tables['fin_self_acc'] = dd.merge(days, all_tables['fin_self_acc'], left_on=['coid','all_dates'], right_on=['coid', 'annd'], how='left')
-            
-            # Drop mdate column
-            all_tables['fin_self_acc'] = all_tables['fin_self_acc'].drop(columns = 'mdate')
-
-            # Delete the redundant dataframe to release memory space
-            del all_tables['fin_auditor'], days, data_concat
-            gc.collect()
-
-            # Filling NaN with the precending value
-            all_tables['fin_self_acc'] = all_tables['fin_self_acc'].groupby('coid', group_keys = False).apply(para.dask_mpf.fillna_multicolumns, meta = all_tables['fin_self_acc'])
-            
-        except:
-            pass
+    try:
+        # Concate fin_self_acc with fin_auditor
+        data_concat = dd.concat([all_tables['fin_self_acc'], all_tables['fin_auditor']]).reset_index(drop=True)
+        all_tables['fin_auditor'] = data_concat.drop_duplicates(subset=['coid','mdate','annd'], keep='last')
 
-    else:
-        try:
-            # transfer to daily basis
-            days = para.dask_mpf.generate_multicalendars(ticker, start = start, end = end)
-            all_tables['fin_auditor'] = dd.merge(days, all_tables['fin_auditor'], left_on=['coid','all_dates'], right_on=['coid', 'annd'], how='left')
-
-            # Drop mdate column
-            all_tables['fin_auditor'] = all_tables['fin_auditor'].drop(columns = 'mdate')
-
-            # Delete the redundant dataframe to release memory space
-            del days
-            gc.collect()
+        # Process two fin dataframe
+        all_tables['fin_auditor'] = process_fin_data(all_tables=all_tables, variable='fin_auditor', tickers=tickers, start=start, end= end)
+        
+        del all_tables['fin_self_acc']
+        # return all_tables
 
-            # Filling NaN with the precending value
-            all_tables['fin_auditor'] = all_tables['fin_auditor'].groupby('coid', group_keys = False).apply(para.dask_mpf.fillna_multicolumns, meta = all_tables['fin_auditor'])
+    except:
+        if 'fin_auditor' in all_tables.keys():
+            all_tables['fin_auditor'] = process_fin_data(all_tables=all_tables, variable='fin_auditor', tickers=tickers, start=start, end= end)
+
+        elif 'fin_self_acc' in all_tables.keys():
+            all_tables['fin_self_acc'] = process_fin_data(all_tables=all_tables, variable='fin_self_acc', tickers=tickers, start=start, end= end)
         
-        except:
+        else:
             pass
 
     # 搜尋觸發到那些 table
     trigger_tables = [i for i in all_tables.keys() if i in para.fin_invest_tables['TABLE_NAMES'].unique().tolist()]
 
     # 根據 OD 進行排序
     trigger_tables.sort(key = lambda x: para.map_table.loc[para.map_table['TABLE_NAMES']==x, 'OD'].item())
@@ -131,41 +128,41 @@
     index = para.table_columns['COLUMNS'].isin(columns)
     tables = para.table_columns.loc[index, :]
     return tables
 
 def search_columns(columns:list):
     index = para.transfer_language_table['COLUMNS'].isin(columns)
     tables = para.transfer_language_table.loc[index, :]
-    # tables = tables.merge(para.fin_invest_tables, left_on = 'table_names', right_on='TABLE_NAMES')
     return tables
 
-def triggers(ticker:list, columns:list = [], fin_type:list = ['A','Q','TTM'],  include_self_acc:str = 'Y', **kwargs):
+def triggers(ticker:list, columns:list = [], fin_type:list = ['A','Q','TTM'],  include_self_acc:str = 'N', **kwargs):
     # Setting default value of the corresponding parameters
     start = kwargs.get('start', para.default_start)
     end = kwargs.get('end', para.default_end)
     npartitions = kwargs.get('npartitions',  para.npartitions_local)
     
     # Tranfer columns from any type (chinese, english) to internal code  
     columns = get_internal_code(columns)    
 
-    # Get trading calendar of all given tickers
-    trading_calendar = get_trading_calendar(ticker, start = start, end = end, npartitions = npartitions)
-
     # Kick out `coid` and `mdate` from
     columns = [i for i in columns if i !='coid' or i!='mdate']
 
     # Qualify the table triggered by the given `columns`
     trigger_tables = search_table(columns)
 
+    # Get trading calendar of all given tickers
+    # if 'stk_price' not in trigger_tables['TABLE_NAMES'].unique():
+    trading_calendar = get_trading_calendar(ticker, start = start, end = end, npartitions = npartitions)
+
     # If include_self_acc equals to 'N', then delete the fin_self_acc in the trigger_tables list
     if include_self_acc =='N':
         trigger_tables = trigger_tables.loc[trigger_tables['TABLE_NAMES']!='fin_self_acc',:]
 
     for table_name in trigger_tables['TABLE_NAMES'].unique():
-        # 
+        # print(table_name)
         selected_columns = trigger_tables.loc[trigger_tables['TABLE_NAMES']==table_name, 'COLUMNS'].tolist()
         api_code = para.table_API.loc[para.table_API['TABLE_NAMES']==table_name, 'API_CODE'].item()
         api_table = para.fin_invest_tables.loc[para.fin_invest_tables['TABLE_NAMES']==table_name,'API_TABLE'].item()
 
         if api_code == 'A0002' or api_code == 'A0004':
             exec(f'{table_name} = para.funct_map[api_code](api_table, ticker, selected_columns, start = start,  end = end, fin_type = fin_type, npartitions = npartitions)')
         
@@ -179,57 +176,70 @@
     for c in ['ENG_COLUMN_NAMES', 'CHN_COLUMN_NAMES', 'COLUMNS']:
         temp = para.transfer_language_table.loc[para.transfer_language_table[c].isin(fields), 'COLUMNS'].tolist()
         columns += temp
     columns = list(set(columns))
     return columns
 
 def consecutive_merge(local_var, loop_array):
+    #
     table_keys = para.map_table.merge(para.merge_keys)
+
     # tables 兩兩合併
     data = local_var['trading_calendar']
+
     for i in range(len(loop_array)):
         right_keys = table_keys.loc[table_keys['TABLE_NAMES']==loop_array[i], 'KEYS'].tolist()
         # dask merge
+        # print(loop_array[i])
         data = dd.merge(data, local_var[loop_array[i]], left_on = ['coid', 'mdate'], right_on = right_keys, how = 'left', suffixes = ('','_surfeit'))
         
         # Clear the right table to release memory
         del local_var[loop_array[i]]
         gc.collect()
         
         # Drop surfeit columns
         data = data.loc[:,~data.columns.str.contains('_surfeit')]
+
     # Ensure the type of mdate is appropriate
     data['mdate'] = dd.to_datetime(data['mdate'])
+
     return data
 
 def get_trading_calendar(tickers, **kwargs):
+    # Setting default value of the corresponding parameters
     start = kwargs.get('start', para.default_start)
     end = kwargs.get('end', para.default_end)
     npartitions = kwargs.get('npartitions',  para.npartitions_local)
-    trading_calendar = pd.DataFrame()
-    def _get_data(ticker):
+
+    def get_data(tickers):
         # trading calendar
         data = tejapi.get('TWN/APIPRCD',
-                        coid = ticker,
+                        coid = tickers,
                         paginate = True,
                         chinese_column_name=False,
                         mdate = {'gte':start,'lte':end},
-                        opts = {'columns':['coid','mdate'], 'sort':{'coid.desc', 'mdate.desc'}})
+                        opts = {'columns':['coid','mdate'], 'sort':{'coid.asc', 'mdate.asc'}})
         if len(data)>1:
             return data
         else:
             return pd.DataFrame({'coid': pd.Series(dtype='object'), 'mdate': pd.Series(dtype='datetime64[ns]')})
     
+    # Define the meta of the dataframe
     meta = pd.DataFrame({'coid': pd.Series(dtype='object'), 'mdate': pd.Series(dtype='datetime64[ns]')})
-    trading_calendar = dd.from_delayed([dask.delayed(_get_data)(ticker) for ticker in tickers], meta = meta)
-    # trading_calendar = dd.from_delayed([dask.delayed(_get_data)(ticker) for ticker in tickers])
-    trading_calendar = trading_calendar.repartition(npartitions=npartitions)
-    trading_calendar['mdate'] = dd.to_datetime(trading_calendar['mdate'])
 
-    return trading_calendar
+    # Calculate the number of tickers in each partition. 
+    ticker_partitions = para.dask_mpf.get_partition_group(tickers = tickers, npartitions= npartitions)
 
+    # Submit jobs to the parallel cores
+    trading_calendar = dd.from_delayed([dask.delayed(get_data)(tickers[(i-1)*npartitions:i*npartitions]) for i in range(1, ticker_partitions)], meta = meta)
+
+    # If ticker smaller than defaulted partitions, then transform it into defaulted partitions
+    if trading_calendar.npartitions < 12:
+        trading_calendar = trading_calendar.repartition(npartitions=npartitions)
+
+    return trading_calendar
```

### Comparing `tej-tool-api-1.0.0/TejTOolAPI/parameters.py` & `tej-tool-api-1.0.1/TejTOolAPI/parameters.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 import pandas as pd
 import datetime
-from TejToolAPI import Map_Dask_API as dask_mpf
+from . import Map_Dask_API as dask_mpf
 import multiprocessing
 import os
 
 # current directory
 module_dir = os.path.dirname(os.path.abspath(__file__))
 xlsx_path = os.path.join(module_dir,'tables','columns_group.xlsx')
 # print(module_dir, xlsx_path)
```

### Comparing `tej-tool-api-1.0.0/TejTOolAPI/tables/columns_group.xlsx` & `tej-tool-api-1.0.1/TejTOolAPI/tables/columns_group.xlsx`

 * *Files identical despite different names*

### Comparing `tej-tool-api-1.0.0/TejTOolAPI/tables/mktboard.csv` & `tej-tool-api-1.0.1/TejTOolAPI/tables/mktboard.csv`

 * *Files identical despite different names*

### Comparing `tej-tool-api-1.0.0/setup.py` & `tej-tool-api-1.0.1/setup.py`

 * *Files 14% similar despite different names*

```diff
@@ -6,15 +6,17 @@
 
   
 
 
 install_requires = [
     'dask == 2022.4.1',
     'pandas == 1.2.5',
-    'tejapi >= 0.1.23'
+    'tejapi >= 0.1.23',
+    'xlrd >= 1.0.0',
+    'openpyxl',
 ]
 
 installs_for_two = [
     'pyOpenSSL',
     'ndg-httpsclient',
     'pyasn1'
 ]
@@ -31,15 +33,15 @@
 long_description = (this_directionary/"README.md").read_text(encoding='utf-8')
 setup(
     name='tej-tool-api',
     description='Package to fetch a large quantity of data from tejapi.',
     keywords=['tej', 'big data', 'data', 'financial', 'economic','stock','TEJ',],
     long_description=long_description,
     long_description_content_type='text/markdown',
-    version='1.0.0',
+    version='1.0.1',
     author='tej',
     author_email='tej@tej.com.tw',
     maintainer='tej api Development Team',
     maintainer_email='tej@tej.com',
     url='https://api.tej.com.tw',
     license='MIT',
     install_requires=install_requires,
```

### Comparing `tej-tool-api-1.0.0/tej_tool_api.egg-info/PKG-INFO` & `tej-tool-api-1.0.1/tej_tool_api.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tej-tool-api
-Version: 1.0.0
+Version: 1.0.1
 Summary: Package to fetch a large quantity of data from tejapi.
 Home-page: https://api.tej.com.tw
 Author: tej
 Author-email: tej@tej.com.tw
 Maintainer: tej api Development Team
 Maintainer-email: tej@tej.com
 License: MIT
```

