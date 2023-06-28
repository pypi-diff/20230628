# Comparing `tmp/herbiv-0.1a6.tar.gz` & `tmp/herbiv-0.1a7.tar.gz`

## Comparing `herbiv-0.1a6.tar` & `herbiv-0.1a7.tar`

### file list

```diff
@@ -1,32 +1,16 @@
--rw-r--r--   0        0        0    61580 2020-02-02 00:00:00.000000 herbiv-0.1a6/demo.ipynb
--rw-r--r--   0        0        0    23588 2020-02-02 00:00:00.000000 herbiv-0.1a6/logo.png
--rw-r--r--   0        0        0     1858 2020-02-02 00:00:00.000000 herbiv-0.1a6/setup.py
--rw-r--r--   0        0        0      219 2020-02-02 00:00:00.000000 herbiv-0.1a6/.idea/.gitignore
--rw-r--r--   0        0        0      611 2020-02-02 00:00:00.000000 herbiv-0.1a6/.idea/HerbiV.iml
--rw-r--r--   0        0        0     1663 2020-02-02 00:00:00.000000 herbiv-0.1a6/.idea/csv-editor.xml
--rw-r--r--   0        0        0      184 2020-02-02 00:00:00.000000 herbiv-0.1a6/.idea/misc.xml
--rw-r--r--   0        0        0      271 2020-02-02 00:00:00.000000 herbiv-0.1a6/.idea/modules.xml
--rw-r--r--   0        0        0      172 2020-02-02 00:00:00.000000 herbiv-0.1a6/.idea/vcs.xml
--rw-r--r--   0        0        0    17647 2020-02-02 00:00:00.000000 herbiv-0.1a6/.idea/workspace.xml
--rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 herbiv-0.1a6/.idea/inspectionProfiles/profiles_settings.xml
--rw-r--r--   0        0        0      414 2020-02-02 00:00:00.000000 herbiv-0.1a6/.idea/shelf/_2023_5_27_20_12____.xml
--rw-r--r--   0        0        0   181921 2020-02-02 00:00:00.000000 herbiv-0.1a6/.idea/shelf/在进行更新之前于_2023_5_27_20_12_取消提交了更改_[更改]/shelved.patch
--rw-r--r--   0        0        0    85738 2020-02-02 00:00:00.000000 herbiv-0.1a6/.ipynb_checkpoints/demo-checkpoint.ipynb
--rw-r--r--   0        0        0    10849 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/analysis.py
--rw-r--r--   0        0        0     7820 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/compute.py
--rw-r--r--   0        0        0     7310 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/get.py
--rw-r--r--   0        0        0     5766 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/output.py
--rw-r--r--   0        0        0 13073523 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/data/HerbiV_chemical_protein_links.csv
--rw-r--r--   0        0        0  1377866 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/data/HerbiV_chemicals.csv
--rw-r--r--   0        0        0  1803372 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/data/HerbiV_formula.csv
--rw-r--r--   0        0        0   481317 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/data/HerbiV_formula_tcm_links.csv
--rw-r--r--   0        0        0  1978064 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/data/HerbiV_proteins.csv
--rw-r--r--   0        0        0  1227198 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/data/HerbiV_tcm.csv
--rw-r--r--   0        0        0  1029771 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/data/HerbiV_tcm_chemical_links.csv
--rw-r--r--   0        0        0    15258 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/result/Graph.html
--rw-r--r--   0        0        0     1287 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/result/Network.csv
--rw-r--r--   0        0        0      604 2020-02-02 00:00:00.000000 herbiv-0.1a6/herbiv/result/Type.csv
--rw-r--r--   0        0        0     1105 2020-02-02 00:00:00.000000 herbiv-0.1a6/LICENSE
--rw-r--r--   0        0        0    12056 2020-02-02 00:00:00.000000 herbiv-0.1a6/README.md
--rw-r--r--   0        0        0     1323 2020-02-02 00:00:00.000000 herbiv-0.1a6/pyproject.toml
--rw-r--r--   0        0        0    13005 2020-02-02 00:00:00.000000 herbiv-0.1a6/PKG-INFO
+-rw-r--r--   0        0        0     2035 2020-02-02 00:00:00.000000 herbiv-0.1a7/setup.py
+-rw-r--r--   0        0        0    12784 2020-02-02 00:00:00.000000 herbiv-0.1a7/herbiv/analysis.py
+-rw-r--r--   0        0        0     7820 2020-02-02 00:00:00.000000 herbiv-0.1a7/herbiv/compute.py
+-rw-r--r--   0        0        0     8398 2020-02-02 00:00:00.000000 herbiv-0.1a7/herbiv/get.py
+-rw-r--r--   0        0        0     7392 2020-02-02 00:00:00.000000 herbiv-0.1a7/herbiv/output.py
+-rw-r--r--   0        0        0 13073523 2020-02-02 00:00:00.000000 herbiv-0.1a7/herbiv/data/HerbiV_chemical_protein_links.csv
+-rw-r--r--   0        0        0  1377866 2020-02-02 00:00:00.000000 herbiv-0.1a7/herbiv/data/HerbiV_chemicals.csv
+-rw-r--r--   0        0        0  1803372 2020-02-02 00:00:00.000000 herbiv-0.1a7/herbiv/data/HerbiV_formula.csv
+-rw-r--r--   0        0        0   481317 2020-02-02 00:00:00.000000 herbiv-0.1a7/herbiv/data/HerbiV_formula_tcm_links.csv
+-rw-r--r--   0        0        0  1978064 2020-02-02 00:00:00.000000 herbiv-0.1a7/herbiv/data/HerbiV_proteins.csv
+-rw-r--r--   0        0        0  1227198 2020-02-02 00:00:00.000000 herbiv-0.1a7/herbiv/data/HerbiV_tcm.csv
+-rw-r--r--   0        0        0  1029771 2020-02-02 00:00:00.000000 herbiv-0.1a7/herbiv/data/HerbiV_tcm_chemical_links.csv
+-rw-r--r--   0        0        0     1105 2020-02-02 00:00:00.000000 herbiv-0.1a7/LICENSE
+-rw-r--r--   0        0        0     5960 2020-02-02 00:00:00.000000 herbiv-0.1a7/README.md
+-rw-r--r--   0        0        0     1500 2020-02-02 00:00:00.000000 herbiv-0.1a7/pyproject.toml
+-rw-r--r--   0        0        0     7187 2020-02-02 00:00:00.000000 herbiv-0.1a7/PKG-INFO
```

### Comparing `herbiv-0.1a6/herbiv/compute.py` & `herbiv-0.1a7/herbiv/compute.py`

 * *Files identical despite different names*

### Comparing `herbiv-0.1a6/herbiv/get.py` & `herbiv-0.1a7/herbiv/get.py`

 * *Files 14% similar despite different names*

```diff
@@ -149,15 +149,36 @@
 
     # 重置索引
     proteins.index = range(proteins.shape[0])
 
     return proteins
 
 
+def get_tcm_or_formula(tcm_or_formula):
+    """
+    获取tcm_or_formula中元素对应的中药、复方及其连接信息
+    :param tcm_or_formula: 任何可以使用in判断一个元素是否在其中的组合数据类型，拟获取的中药或复方的ID
+    :return: formula: pd.DataFrame类型，复方信息
+    :return: tcm: pd.DataFrame类型，中药信息
+    :return: formula_tcm_links: pd.DataFrame类型，复方-中药连接信息
+    """
+    if tcm_or_formula[0][2] == 'P':  # 判断输入是否为复方的HVPID
+        formula = get_formula('HVPID', tcm_or_formula)
+        formula_tcm_links = get_formula_tcm_links('HVPID', formula['HVPID'])
+        tcm = get_tcm('HVMID', formula_tcm_links['HVMID'])
+    else:
+        formula = None
+        formula_tcm_links = None
+        tcm = get_tcm('HVMID', tcm_or_formula)
+    return formula, tcm, formula_tcm_links
+
+
 if __name__ == '__main__':
     formula_info = get_formula('HVPID', ['HVP1625'])
     formula_tcm_links_info = get_formula_tcm_links('HVPID', formula_info['HVPID'])
     tcm_info = get_tcm('HVMID', formula_tcm_links_info['HVMID'])
     tcm_chem_links_info = get_tcm_chem_links('HVMID', tcm_info['HVMID'])
     chem_info = get_chemicals('HVCID', tcm_chem_links_info['HVCID'])
     chem_protein_links_info = get_chem_protein_links('HVCID', chem_info['HVCID'])
     protein_info = get_proteins('Ensembl_ID', chem_protein_links_info['Ensembl_ID'])
+    formula_info1, tcm_info1, formula_tcm_links_info1 = get_tcm_or_formula(['HVP1625'])
+    formula_info2, tcm_info2, formula_tcm_links_info2 = get_tcm_or_formula(['HVM0367', 'HVM1695'])
```

### Comparing `herbiv-0.1a6/herbiv/output.py` & `herbiv-0.1a7/herbiv/output.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 import os
 import pandas as pd
 from pyecharts import options as opts
 from pyecharts.charts import Graph
+from pyecharts.globals import ThemeType
 
 
 def out_for_cyto(tcm, tcm_chem_links, chem, chem_protein_links, protein, path='result/'):
     r"""
     输出Cytoscape用于作图的网络文件和属性文件
     :param tcm: pd.DataFrame类型，中药信息
     :param tcm_chem_links: pd.DataFrame类型，中药-化合物（中药成分）连接信息
@@ -75,57 +76,81 @@
 def vis(tcm, tcm_chem_links, chem, chem_protein_links, protein, path='result/'):
     r"""
     使用NetworkX可视化分析结果
     :param tcm: pd.DataFrame类型，中药信息
     :param tcm_chem_links: pd.DataFrame类型，中药-化合物（中药成分）连接信息
     :param chem: pd.DataFrame类型，化合物（中药成分）信息
     :param chem_protein_links: pd.DataFrame类型，化合物（中药成分）-蛋白质（靶点）连接信息
+    :param protein: pd.DataFrame类型，蛋白质（靶点）连接信息
     :param path: 字符串类型，存放结果的目录
     """
     # 若无path目录，先创建该目录
     if not os.path.exists(path):
         os.mkdir(path)
 
-    chem_protein_links = pd.DataFrame(chem_protein_links)
-    tcm_chem_links = pd.DataFrame(tcm_chem_links)
+    tcm_chem_links_c = tcm_chem_links.copy()
+    chem_protein_links_c = chem_protein_links.copy()
+
+    tcm_chem_merged_1 = pd.merge(tcm_chem_links_c, tcm, on='HVMID', how='left')
+    tcm_chem_links_c['HVMID'] = tcm_chem_merged_1['pinyin_name']
+
+    tcm_chem_merged_2 = pd.merge(tcm_chem_links_c, chem, on='HVCID', how='left')
+    tcm_chem_links_c['HVCID'] = tcm_chem_merged_2['Name']
+
+    tcm_chem_links_c = tcm_chem_links_c[['HVMID', 'HVCID']]
+
+    chem_protein_merged_1 = pd.merge(chem_protein_links_c, chem, on='HVCID', how='right')
+    chem_protein_links_c['HVCID'] = chem_protein_merged_1['Name']
+    chem_protein_merged_2 = pd.merge(chem_protein_links_c, protein, on='Ensembl_ID', how='left')
+    chem_protein_links_c['Ensembl_ID'] = chem_protein_merged_2['gene_name']
+
+    chem_protein_links_c = chem_protein_links_c[['HVCID', 'Ensembl_ID']]
 
     nodes = []
     edges = []
 
-    for index, row in tcm_chem_links.iloc[1:].iterrows():
+    for index, row in tcm_chem_links_c.iloc[1:].iterrows():
         chinese_medicine = row[0]
         chemical_component = row[1]
         nodes.append({'name': chinese_medicine, "symbolSize": 10})
         nodes.append({'name': chemical_component, "symbolSize": 20})
         edges.append({'source': chinese_medicine, 'target': chemical_component})
 
-    for index, row in chem_protein_links.iloc[1:].iterrows():
+    for index, row in chem_protein_links_c.iloc[1:].iterrows():
         chemical_component = row[0]
         target = row[1]
         nodes.append({'name': chemical_component, "symbolSize": 20})
         nodes.append({'name': target, "symbolSize": 30})
         edges.append({'source': chemical_component, 'target': target})
 
     unique_list = list(set(tuple(item.items()) for item in nodes))
     nodes = [dict(item) for item in unique_list]
 
     unique_list = list(set(tuple(item.items()) for item in edges))
     edges = [dict(item) for item in unique_list]
 
-    Graph(init_opts=opts.InitOpts(width='1000px', height='600px')).add(
-        '', nodes, edges, repulsion=8000).set_global_opts(
-        title_opts=opts.TitleOpts(title='')).render(path=path + 'Graph.html')
+    Graph(init_opts=opts.InitOpts(width="2500px", height="1200px", theme=ThemeType.LIGHT)).add(
+        '', nodes, edges, repulsion=8000, layout="circular", is_rotate_label=True, linestyle_opts=opts.LineStyleOpts(
+            color="source", curve=0.3), label_opts=opts.LabelOpts(position="right")).set_global_opts(
+        title_opts=opts.TitleOpts(title=''), legend_opts=opts.LegendOpts(
+            orient="vertical", pos_left="2%", pos_top="20%")).render(path=path + "Graph.html")
 
 
 if __name__ == '__main__':
     import get
 
     formula_info = get.get_formula('HVPID', ['HVP1625'])
     formula_tcm_links_info = get.get_formula_tcm_links('HVPID', formula_info['HVPID'])
     tcm_info = get.get_tcm('HVMID', formula_tcm_links_info['HVMID'])
     tcm_chem_links_info = get.get_tcm_chem_links('HVMID', tcm_info['HVMID'])
     chem_info = get.get_chemicals('HVCID', tcm_chem_links_info['HVCID'])
-    chem_protein_links_info = get.get_chem_protein_links('HVCID', chem_info['HVCID'])
+    chem_protein_links_info = get.get_chem_protein_links('HVCID', chem_info['HVCID'], 990)
     protein_info = get.get_proteins('Ensembl_ID', chem_protein_links_info['Ensembl_ID'])
 
+    chem_info = chem_info.loc[chem_info.loc[:, 'HVCID'].isin(chem_protein_links_info['HVCID'])]
+    tcm_chem_links_info = tcm_chem_links_info.loc[tcm_chem_links_info.loc[:, 'HVCID'].isin(chem_info['HVCID'])]
+    tcm_info = tcm_info.loc[tcm_info.loc[:, 'HVMID'].isin(tcm_chem_links_info['HVMID'])]
+    # 重新编号（chem和tcm在计算score时会重新编号，此处不再重新编号）
+    tcm_chem_links_info.index = range(tcm_chem_links_info.shape[0])
+
     vis(tcm_info, tcm_chem_links_info, chem_info, chem_protein_links_info, protein_info)
     out_for_cyto(tcm_info, tcm_chem_links_info, chem_info, chem_protein_links_info, protein_info)
```

### Comparing `herbiv-0.1a6/herbiv/data/HerbiV_chemical_protein_links.csv` & `herbiv-0.1a7/herbiv/data/HerbiV_chemical_protein_links.csv`

 * *Files identical despite different names*

### Comparing `herbiv-0.1a6/herbiv/data/HerbiV_chemicals.csv` & `herbiv-0.1a7/herbiv/data/HerbiV_chemicals.csv`

 * *Files identical despite different names*

### Comparing `herbiv-0.1a6/herbiv/data/HerbiV_formula.csv` & `herbiv-0.1a7/herbiv/data/HerbiV_formula.csv`

 * *Files identical despite different names*

### Comparing `herbiv-0.1a6/herbiv/data/HerbiV_formula_tcm_links.csv` & `herbiv-0.1a7/herbiv/data/HerbiV_formula_tcm_links.csv`

 * *Files identical despite different names*

### Comparing `herbiv-0.1a6/herbiv/data/HerbiV_proteins.csv` & `herbiv-0.1a7/herbiv/data/HerbiV_proteins.csv`

 * *Files identical despite different names*

### Comparing `herbiv-0.1a6/herbiv/data/HerbiV_tcm.csv` & `herbiv-0.1a7/herbiv/data/HerbiV_tcm.csv`

 * *Files identical despite different names*

### Comparing `herbiv-0.1a6/herbiv/data/HerbiV_tcm_chemical_links.csv` & `herbiv-0.1a7/herbiv/data/HerbiV_tcm_chemical_links.csv`

 * *Files identical despite different names*

### Comparing `herbiv-0.1a6/LICENSE` & `herbiv-0.1a7/LICENSE`

 * *Files identical despite different names*

### Comparing `herbiv-0.1a6/pyproject.toml` & `herbiv-0.1a7/pyproject.toml`

 * *Files 19% similar despite different names*

```diff
@@ -7,19 +7,19 @@
     "pyecharts",
     "typing-extensions",
 ]
 build-backend = "hatchling.build"
 
 [project]
 name = "herbiv"
-version = "0.1a6"
+version = "0.1a7"
 authors = [
   { name="王皓阳", email="Wesady@qq.com" },
 ]
-description = "HerbiV是一个具有多种功能的中药网络药理学分析工具，可进行经典的网络药理学及反向网络药理学分析。HerbiV is a multi-functional traditional chinese medicine network pharmacology analysis tool for classical network pharmacology and reverse network pharmacology."
+description = "HerbiV(Bidirectional and Visible Database of Herb)既是一个数据库，又是一个强大的数据分析平台，集成了50多万条方剂、中药、成分、靶点数据，以及经过检验的数据挖掘模型。HerbiV is far more than a database, which is also a powerful data analysis platform that integrates more than 500,000 prescriptions, traditional Chinese medicine, ingredients and target data. Moreover, two tested data mining models are contained in HerbiV."
 readme = "README.md"
 requires-python = ">=3.8"
 classifiers = [
     "Programming Language :: Python :: 3",
     "License :: OSI Approved :: MIT License",
     "Operating System :: OS Independent",
     "Development Status :: 3 - Alpha",
```

