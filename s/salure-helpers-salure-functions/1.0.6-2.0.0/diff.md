# Comparing `tmp/salure_helpers_salure_functions-1.0.6.tar.gz` & `tmp/salure_helpers_salure_functions-2.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/salure_helpers_salure_functions-1.0.6.tar", last modified: Wed Jan 25 13:00:24 2023, max compression
+gzip compressed data, was "dist/salure_helpers_salure_functions-2.0.0.tar", last modified: Wed Jun 28 11:49:18 2023, max compression
```

## Comparing `salure_helpers_salure_functions-1.0.6.tar` & `salure_helpers_salure_functions-2.0.0.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-25 13:00:24.000000 salure_helpers_salure_functions-1.0.6/
--rw-r--r--   0 root         (0) root         (0)      278 2023-01-25 13:00:24.000000 salure_helpers_salure_functions-1.0.6/PKG-INFO
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-25 13:00:24.000000 salure_helpers_salure_functions-1.0.6/salure_helpers/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-25 13:00:24.000000 salure_helpers_salure_functions-1.0.6/salure_helpers/salure_functions/
--rw-rw-rw-   0 root         (0) root         (0)       76 2023-01-25 13:00:09.000000 salure_helpers_salure_functions-1.0.6/salure_helpers/salure_functions/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)    32956 2023-01-25 13:00:09.000000 salure_helpers_salure_functions-1.0.6/salure_helpers/salure_functions/salure_functions.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-25 13:00:24.000000 salure_helpers_salure_functions-1.0.6/salure_helpers_salure_functions.egg-info/
--rw-r--r--   0 root         (0) root         (0)      278 2023-01-25 13:00:24.000000 salure_helpers_salure_functions-1.0.6/salure_helpers_salure_functions.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      432 2023-01-25 13:00:24.000000 salure_helpers_salure_functions-1.0.6/salure_helpers_salure_functions.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-01-25 13:00:24.000000 salure_helpers_salure_functions-1.0.6/salure_helpers_salure_functions.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-01-25 13:00:24.000000 salure_helpers_salure_functions-1.0.6/salure_helpers_salure_functions.egg-info/not-zip-safe
--rw-r--r--   0 root         (0) root         (0)       50 2023-01-25 13:00:24.000000 salure_helpers_salure_functions-1.0.6/salure_helpers_salure_functions.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       15 2023-01-25 13:00:24.000000 salure_helpers_salure_functions-1.0.6/salure_helpers_salure_functions.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)       38 2023-01-25 13:00:24.000000 salure_helpers_salure_functions-1.0.6/setup.cfg
--rw-rw-rw-   0 root         (0) root         (0)      491 2023-01-25 13:00:09.000000 salure_helpers_salure_functions-1.0.6/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:49:18.000000 salure_helpers_salure_functions-2.0.0/
+-rw-r--r--   0 root         (0) root         (0)      278 2023-06-28 11:49:18.000000 salure_helpers_salure_functions-2.0.0/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:49:18.000000 salure_helpers_salure_functions-2.0.0/salure_helpers/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:49:18.000000 salure_helpers_salure_functions-2.0.0/salure_helpers/salure_functions/
+-rw-rw-rw-   0 root         (0) root         (0)       76 2023-06-28 11:49:00.000000 salure_helpers_salure_functions-2.0.0/salure_helpers/salure_functions/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)    33540 2023-06-28 11:49:00.000000 salure_helpers_salure_functions-2.0.0/salure_helpers/salure_functions/salure_functions.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 11:49:18.000000 salure_helpers_salure_functions-2.0.0/salure_helpers_salure_functions.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      278 2023-06-28 11:49:17.000000 salure_helpers_salure_functions-2.0.0/salure_helpers_salure_functions.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      432 2023-06-28 11:49:17.000000 salure_helpers_salure_functions-2.0.0/salure_helpers_salure_functions.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 11:49:17.000000 salure_helpers_salure_functions-2.0.0/salure_helpers_salure_functions.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 11:49:17.000000 salure_helpers_salure_functions-2.0.0/salure_helpers_salure_functions.egg-info/not-zip-safe
+-rw-r--r--   0 root         (0) root         (0)       50 2023-06-28 11:49:17.000000 salure_helpers_salure_functions-2.0.0/salure_helpers_salure_functions.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       15 2023-06-28 11:49:17.000000 salure_helpers_salure_functions-2.0.0/salure_helpers_salure_functions.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 11:49:18.000000 salure_helpers_salure_functions-2.0.0/setup.cfg
+-rw-rw-rw-   0 root         (0) root         (0)      491 2023-06-28 11:49:00.000000 salure_helpers_salure_functions-2.0.0/setup.py
```

### Comparing `salure_helpers_salure_functions-1.0.6/salure_helpers/salure_functions/salure_functions.py` & `salure_helpers_salure_functions-2.0.0/salure_helpers/salure_functions/salure_functions.py`

 * *Files 2% similar despite different names*

```diff
@@ -179,14 +179,23 @@
         :return: Returns a dataframe with the new colums change_type (deleted, new or edited) and changed_fields (contains all the names of the changed fields)
         """
         # Set default if parameter outside possible options is given
         if keep_old_values not in ['dict', 'rows', 'list', False]:
             keep_old_values = False
             warnings.warn('Value for keep_old_values was outside list of possible parameters, defaulting to False')
 
+        if not df_old[unique_key].is_unique:
+            print("Duplicated records:")
+            print(df_old[df_old[unique_key].duplicated(keep=False)].to_string())
+            raise ValueError('The unique_key column is not unique in the old dataframe')
+        if not df_actual[unique_key].is_unique:
+            print("Duplicated records:")
+            print(df_actual[df_actual[unique_key].duplicated(keep=False)].to_string())
+            raise ValueError('The unique_key column is not unique in the actual dataframe')
+
         if detect_column_changes:
             deleted_columns = [column for column in df_old.columns.values if column not in df_actual.columns.values]
             added_columns = [column for column in df_actual.columns.values if column not in df_old.columns.values]
             df_old[added_columns] = [pd.NA] * len(added_columns)
             # set values of columns to object because one of the dataframes only contains NA values
             df_old = df_old.astype(dtype={key: 'object' for key in added_columns})
             df_actual = df_actual.astype(dtype={key: 'object' for key in added_columns})
@@ -205,42 +214,43 @@
         df_actual['flag_old'] = 0
 
         # Removed sort parameter from concat because this sort columns alphabetically (for no reason)
         df = pd.concat([df_old, df_actual]).drop_duplicates(subset=check_columns + [unique_key], keep=False)
         df['freq'] = df.groupby(unique_key, observed=True)[unique_key].transform('count')  # observed parameter is for Categorical data (it will check if the possible values for a column are the same as another column). But you only want to compare the actually present value
         df['change_type'] = np.where(np.logical_and(df.freq == 1, df.flag_old == 0), 'new',
                                      np.where(np.logical_and(df.freq == 1, df.flag_old == 1), 'deleted',
-                                              np.where(df.freq >= 2, 'edited',
-                                                       'nothing'
+                                              np.where(df.freq == 2, 'edited',
+                                                       'duplicates in data'
                                                        )
                                               )
                                      )
         # Now check which values in which column are changed. Add the names of this columns to the column 'changed_fields'
         df.sort_values(by=[unique_key] + ['flag_old'], inplace=True, ascending=False)
         df.reset_index(inplace=True, drop=True)
         df['changed_fields'] = ''
         # If the unique key is already in the columns which need to be checked, then don't add this double. Otherwise comparison of rows won't work because two values are returned for an index
         if unique_key in check_columns:
-            df_changes = df.loc[:, check_columns].fillna('')
+            df_changes = df.loc[:, check_columns]
         else:
-            df_changes = df.loc[:, check_columns + [unique_key]].fillna('')
+            df_changes = df.loc[:, check_columns + [unique_key]]
         for i in df_changes.index.values:
             curr_row: pd.Series = df_changes.iloc[i]
             prev_row = df_changes.iloc[i - 1]
             if curr_row[unique_key] == prev_row[unique_key] and i != 0:
+                # returns a series with a boolean for the columns which are different
                 unique_columns = curr_row != prev_row
                 if keep_old_values in ['list', 'dict']:
                     if keep_old_values == 'list':
-                        df.loc[i, 'changed_fields'] = str([key for key, value in unique_columns.iteritems() if value is True and key != 'flag_old'])
-                        df.loc[i, 'old_values'] = str([prev_row[key] for key, value in unique_columns.iteritems() if value is True and key != 'flag_old'])
+                        df.loc[i, 'changed_fields'] = str([key for key, value in unique_columns.items() if value is True and key != 'flag_old'])
+                        df.loc[i, 'old_values'] = str([prev_row[key] for key, value in unique_columns.items() if value is True and key != 'flag_old'])
                     else:
                         import json
-                        df.loc[i, 'changes'] = json.dumps({key: str(prev_row[key]) for key, value in unique_columns.iteritems() if value is True and key != 'flag_old'})
+                        df.loc[i, 'changes'] = json.dumps({key: str(prev_row[key]) for key, value in unique_columns.items() if value is True and key != 'flag_old'})
                 elif keep_old_values == 'rows' or keep_old_values is False:
-                    df.loc[i, 'changed_fields'] = str([key for key, value in unique_columns.iteritems() if value is True and key != 'flag_old'])
+                    df.loc[i, 'changed_fields'] = str([key for key, value in unique_columns.items() if value is True and key != 'flag_old'])
         # remove old rows except for when return type is rows
         if keep_old_values != 'rows':
             df = df[(df['flag_old'] == 0) | (df['change_type'] == 'deleted')]
             df.drop(labels=['flag_old', 'freq'], axis='columns', inplace=True, errors='ignore')
         else:
             df['changed_fields'].fillna('', inplace=True)
```

