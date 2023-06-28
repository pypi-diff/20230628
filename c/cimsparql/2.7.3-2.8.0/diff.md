# Comparing `tmp/cimsparql-2.7.3.tar.gz` & `tmp/cimsparql-2.8.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "cimsparql-2.7.3.tar", max compression
+gzip compressed data, was "cimsparql-2.8.0.tar", max compression
```

## Comparing `cimsparql-2.7.3.tar` & `cimsparql-2.8.0.tar`

### file list

```diff
@@ -1,50 +1,52 @@
--rw-r--r--   0        0        0     1065 2023-05-31 11:59:12.768054 cimsparql-2.7.3/LICENSE
--rw-r--r--   0        0        0     5330 2023-05-31 11:59:12.768054 cimsparql-2.7.3/README.md
--rw-r--r--   0        0        0       61 2023-05-31 11:59:46.820465 cimsparql-2.7.3/cimsparql/__init__.py
--rw-r--r--   0        0        0     1322 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/async_sparql_wrapper.py
--rw-r--r--   0        0        0     1642 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/constants.py
--rw-r--r--   0        0        0     8200 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/data_models.py
--rw-r--r--   0        0        0    15571 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/graphdb.py
--rw-r--r--   0        0        0    26077 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/model.py
--rw-r--r--   0        0        0     4851 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/ac_lines.sparql
--rw-r--r--   0        0        0      221 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/add_mrid.sparql
--rw-r--r--   0        0        0     1761 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/borders.sparql
--rw-r--r--   0        0        0     1929 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/branch_node_withdraw.sparql
--rw-r--r--   0        0        0     1657 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/bus.sparql
--rw-r--r--   0        0        0      984 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/connections.sparql
--rw-r--r--   0        0        0      676 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/converter_hvdc_bidzones.sparql
--rw-r--r--   0        0        0     2266 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/converters.sparql
--rw-r--r--   0        0        0      588 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/coordinates.sparql
--rw-r--r--   0        0        0     2458 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/dc_active_power_flow.sparql
--rw-r--r--   0        0        0      242 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/disconnected.sparql
--rw-r--r--   0        0        0     3658 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/exchange.sparql
--rw-r--r--   0        0        0     1062 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/full_model.sparql
--rw-r--r--   0        0        0     2786 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/loads.sparql
--rw-r--r--   0        0        0      287 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/market_dates.sparql
--rw-r--r--   0        0        0      429 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/power_flow.sparql
--rw-r--r--   0        0        0      415 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/protective_action.sparql
--rw-r--r--   0        0        0      573 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/regions.sparql
--rw-r--r--   0        0        0     3289 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/series_compensators.sparql
--rw-r--r--   0        0        0      426 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/station_group_code_and_names.sparql
--rw-r--r--   0        0        0      645 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/substation_voltage_level.sparql
--rw-r--r--   0        0        0     2813 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/sv_branch.sparql
--rw-r--r--   0        0        0     3735 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/synchronous_machines.sparql
--rw-r--r--   0        0        0     3127 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/three_winding.sparql
--rw-r--r--   0        0        0     1647 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/three_winding_dummy_nodes.sparql
--rw-r--r--   0        0        0     1656 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/three_winding_loss.sparql
--rw-r--r--   0        0        0      363 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/transformer_windings.sparql
--rw-r--r--   0        0        0     1269 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/transformers.sparql
--rw-r--r--   0        0        0     1844 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/transformers_connected_to_converter.sparql
--rw-r--r--   0        0        0     5276 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/two_winding_transformer.sparql
--rw-r--r--   0        0        0      972 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/two_winding_transformer_angle.sparql
--rw-r--r--   0        0        0      461 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/type_mapper.sparql
--rw-r--r--   0        0        0      814 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/sparql/wind_generating_units.sparql
--rw-r--r--   0        0        0     2918 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/templates.py
--rw-r--r--   0        0        0     5473 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/type_mapper.py
--rw-r--r--   0        0        0     1937 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/url.py
--rw-r--r--   0        0        0      600 2023-05-31 11:59:12.768054 cimsparql-2.7.3/cimsparql/value_mapper.py
--rw-r--r--   0        0        0      459 2023-05-31 11:59:12.776054 cimsparql-2.7.3/pkg_data/blazegraph_repo_config.xml
--rw-r--r--   0        0        0      636 2023-05-31 11:59:12.776054 cimsparql-2.7.3/pkg_data/namespaces.json
--rw-r--r--   0        0        0      805 2023-05-31 11:59:12.776054 cimsparql-2.7.3/pkg_data/native_store_config_template.ttl
--rw-r--r--   0        0        0     2620 2023-05-31 11:59:46.816465 cimsparql-2.7.3/pyproject.toml
--rw-r--r--   0        0        0     6017 1970-01-01 00:00:00.000000 cimsparql-2.7.3/PKG-INFO
+-rw-r--r--   0        0        0     1065 2023-06-28 15:30:52.763646 cimsparql-2.8.0/LICENSE
+-rw-r--r--   0        0        0     5330 2023-06-28 15:30:52.763646 cimsparql-2.8.0/README.md
+-rw-r--r--   0        0        0       61 2023-06-28 15:31:17.135764 cimsparql-2.8.0/cimsparql/__init__.py
+-rw-r--r--   0        0        0     1322 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/async_sparql_wrapper.py
+-rw-r--r--   0        0        0     1642 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/constants.py
+-rw-r--r--   0        0        0     8635 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/data_models.py
+-rw-r--r--   0        0        0    15859 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/graphdb.py
+-rw-r--r--   0        0        0    26922 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/model.py
+-rw-r--r--   0        0        0     4795 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/ac_lines.sparql
+-rw-r--r--   0        0        0      221 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/add_mrid.sparql
+-rw-r--r--   0        0        0     1761 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/borders.sparql
+-rw-r--r--   0        0        0     1929 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/branch_node_withdraw.sparql
+-rw-r--r--   0        0        0     1657 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/bus.sparql
+-rw-r--r--   0        0        0      984 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/connections.sparql
+-rw-r--r--   0        0        0      676 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/converter_hvdc_bidzones.sparql
+-rw-r--r--   0        0        0     2266 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/converters.sparql
+-rw-r--r--   0        0        0      588 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/coordinates.sparql
+-rw-r--r--   0        0        0     2458 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/dc_active_power_flow.sparql
+-rw-r--r--   0        0        0      242 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/disconnected.sparql
+-rw-r--r--   0        0        0     3658 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/exchange.sparql
+-rw-r--r--   0        0        0     1062 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/full_model.sparql
+-rw-r--r--   0        0        0     2786 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/loads.sparql
+-rw-r--r--   0        0        0      287 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/market_dates.sparql
+-rw-r--r--   0        0        0      429 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/power_flow.sparql
+-rw-r--r--   0        0        0      397 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/ras_equipment.sparql
+-rw-r--r--   0        0        0      573 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/regions.sparql
+-rw-r--r--   0        0        0     3289 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/series_compensators.sparql
+-rw-r--r--   0        0        0      426 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/station_group_code_and_names.sparql
+-rw-r--r--   0        0        0      645 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/substation_voltage_level.sparql
+-rw-r--r--   0        0        0     2813 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/sv_branch.sparql
+-rw-r--r--   0        0        0      245 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/sv_injection.sparql
+-rw-r--r--   0        0        0     3735 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/synchronous_machines.sparql
+-rw-r--r--   0        0        0     3127 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/three_winding.sparql
+-rw-r--r--   0        0        0     1647 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/three_winding_dummy_nodes.sparql
+-rw-r--r--   0        0        0     1656 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/three_winding_loss.sparql
+-rw-r--r--   0        0        0      363 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/transformer_windings.sparql
+-rw-r--r--   0        0        0     1269 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/transformers.sparql
+-rw-r--r--   0        0        0     1844 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/transformers_connected_to_converter.sparql
+-rw-r--r--   0        0        0     5276 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/two_winding_transformer.sparql
+-rw-r--r--   0        0        0      972 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/two_winding_transformer_angle.sparql
+-rw-r--r--   0        0        0      461 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/type_mapper.sparql
+-rw-r--r--   0        0        0      814 2023-06-28 15:30:52.763646 cimsparql-2.8.0/cimsparql/sparql/wind_generating_units.sparql
+-rw-r--r--   0        0        0      922 2023-06-28 15:30:52.767646 cimsparql-2.8.0/cimsparql/sparql/winding.sparql
+-rw-r--r--   0        0        0     3044 2023-06-28 15:30:52.767646 cimsparql-2.8.0/cimsparql/templates.py
+-rw-r--r--   0        0        0     5473 2023-06-28 15:30:52.767646 cimsparql-2.8.0/cimsparql/type_mapper.py
+-rw-r--r--   0        0        0     1937 2023-06-28 15:30:52.767646 cimsparql-2.8.0/cimsparql/url.py
+-rw-r--r--   0        0        0      600 2023-06-28 15:30:52.767646 cimsparql-2.8.0/cimsparql/value_mapper.py
+-rw-r--r--   0        0        0      459 2023-06-28 15:30:52.775646 cimsparql-2.8.0/pkg_data/blazegraph_repo_config.xml
+-rw-r--r--   0        0        0      676 2023-06-28 15:30:52.775646 cimsparql-2.8.0/pkg_data/namespaces.json
+-rw-r--r--   0        0        0      805 2023-06-28 15:30:52.775646 cimsparql-2.8.0/pkg_data/native_store_config_template.ttl
+-rw-r--r--   0        0        0     2535 2023-06-28 15:31:17.135764 cimsparql-2.8.0/pyproject.toml
+-rw-r--r--   0        0        0     6017 1970-01-01 00:00:00.000000 cimsparql-2.8.0/PKG-INFO
```

### Comparing `cimsparql-2.7.3/LICENSE` & `cimsparql-2.8.0/LICENSE`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/README.md` & `cimsparql-2.8.0/README.md`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/async_sparql_wrapper.py` & `cimsparql-2.8.0/cimsparql/async_sparql_wrapper.py`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/constants.py` & `cimsparql-2.8.0/cimsparql/constants.py`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/data_models.py` & `cimsparql-2.8.0/cimsparql/data_models.py`

 * *Files 1% similar despite different names*

```diff
@@ -299,7 +299,25 @@
 class TransformerWindingsSchema(JsonSchemaOut):
     mrid: Series[str] = pa.Field()
     end_number: Series[int] = pa.Field(gt=0)
     w_mrid: Index[str] = pa.Field(unique=True)
 
 
 TransformerWindingsDataFrame = DataFrame[TransformerWindingsSchema]
+
+
+class SvInjectionSchema(JsonSchemaOut):
+    node: Series[str] = pa.Field(unique=True)
+    p: Series[float] = pa.Field()
+    q: Series[float] = pa.Field()
+
+
+SvInjectionDataFrame = DataFrame[SvInjectionSchema]
+
+
+class RASEquipmentSchema(JsonSchemaOut):
+    mrid: Series[str] = pa.Field(unique=True)
+    equipment_mrid: Series[str] = pa.Field()
+    name: Series[str] = pa.Field()
+
+
+RASEquipmentDataFrame = DataFrame[RASEquipmentSchema]
```

### Comparing `cimsparql-2.7.3/cimsparql/graphdb.py` & `cimsparql-2.8.0/cimsparql/graphdb.py`

 * *Files 8% similar despite different names*

```diff
@@ -122,35 +122,48 @@
             raise NotImplementedError("Function only implemented for RDF4J")
         return f(*args)
 
     return wrapper
 
 
 class GraphDBClient:
-    def __init__(self, service_cfg: Optional[ServiceConfig] = None) -> None:
-        """GraphDB client
+    """GraphDB client for sending sparql queries to GraphDB server
 
-        Args:
-           service: string with url to graphdb repository. See cimsparql.url.service
-           mapper: GraphDBClient with the mapper (Default to self).
-           infer: deduce further knowledge based on existing RDF data and a formal set of
-           sameas: map same concepts from two or more datasets
-        """
-        self.service_cfg = service_cfg or ServiceConfig()
-        self.sparql = SPARQLWrapper(self.service_cfg.url)
-        self._init_sparql_wrapper()
-        self._prefixes = None
+    Args:
+        service_cfg: Service configuration (see ServiceConfig)
+        custom_headers: Added to SPARQLWrapper using addCustomHttpHeader
+
+    Example:
+    >>> from cimsparql.graphdb import GraphDBClient
+    >>> gdbc = GraphDBClient()
+    >>> query = 'select * where { ?subject ?predicate ?object } limit 10'
+    >>> df, row = gdbc.get_table(query)xs
 
-    def _init_sparql_wrapper(self):
+    Where row is the output of graphdb.data_row
+    """
+
+    sparql_wrapper = SPARQLWrapper
+
+    def __init__(
+        self,
+        service_cfg: Optional[ServiceConfig] = None,
+        custom_headers: Optional[Dict[str, str]] = None,
+    ) -> None:
+        self.service_cfg = service_cfg or ServiceConfig()
+        self.sparql = self.sparql_wrapper(self.service_cfg.url, self.service_cfg.ca_bundle)
         self.sparql.setReturnFormat(JSON)
         self.sparql.setMethod(POST)
         self.sparql.setCredentials(self.service_cfg.user, self.service_cfg.passwd)
         if self.service_cfg.timeout:
             self.sparql.setTimeout(self.service_cfg.timeout)
         self._update_sparql_parameters()
+        if custom_headers:
+            for name, value in custom_headers.items():
+                self.sparql.addCustomHttpHeader(name, value)
+        self._prefixes = None
 
     def _update_sparql_parameters(self):
         for key, value in self.service_cfg.parameters.items():
             if value is not None:
                 self.set_parameter(key, str(value))
 
     def set_parameter(self, key: str, value: str) -> None:
@@ -196,24 +209,19 @@
         return out["out"]
 
     def _convert_query_result_to_df(self, res: SparqlResult) -> Tuple[pd.DataFrame, Dict[str, str]]:
         df = pd.DataFrame(res["out"]) if len(res["out"]) else pd.DataFrame(columns=res["cols"])
         return df, data_row(res["cols"], res["data"])
 
     def get_table(self, query: str) -> Tuple[pd.DataFrame, Dict[str, str]]:
-        """
+        """Get result from sparql query as a pandas dataframe
+
         Args:
            query: to sparql server
            limit: limit number of resulting rows
-        Example:
-           >>> from cimsparql.graphdb import GraphDBClient
-           >>> from cimsparql.url import service
-           >>> gdbc = GraphDBClient(service('LATEST'))
-           >>> query = 'select * where { ?subject ?predicate ?object }'
-           >>> gdbc.get_table(query, limit=10)
         """
         res = self._exec_query(query)
         return self._convert_query_result_to_df(res)
 
     @property
     def empty(self) -> bool:
         """Identify empty GraphDB repo"""
@@ -224,15 +232,17 @@
 
         if self.service_cfg.rest_api in (RestApi.BLAZEGRAPH, RestApi.DIRECT_SPARQL_ENDPOINT):
             # These APis does not expose prefixes. Custom prefixes must be added
             # via `update_prefixes`. By default we load a pre-defined set of prefixes
             return prefixes
 
         auth = requests.auth.HTTPBasicAuth(self.service_cfg.user, self.service_cfg.passwd)
-        response = requests.get(self.service_cfg.url + "/namespaces", auth=auth)
+        response = requests.get(
+            self.service_cfg.url + "/namespaces", auth=auth, headers=self.sparql.customHttpHeaders
+        )
         if response.ok:
             prefixes.update(parse_namespaces_rdf4j(response))
             return prefixes
         msg = (
             "Could not fetch namespaces and prefixes from graphdb "
             "Verify that user and password are correctly set in the "
             "GRAPHDB_USER and GRAPHDB_USER_PASSWD environment variable"
@@ -273,15 +283,16 @@
         """
         Function that passes a query via a post API call
         """
         auth = requests.auth.HTTPBasicAuth(self.service_cfg.user, self.service_cfg.passwd)
         response = requests.post(
             self.service_cfg.url + UPLOAD_END_POINT[self.service_cfg.rest_api],
             data={"update": query},
-            headers={"Content-Type": "application/x-www-form-urlencoded"},
+            headers=self.sparql.customHttpHeaders
+            | {"Content-Type": "application/x-www-form-urlencoded"},
             auth=auth,
         )
         response.raise_for_status()
 
     @require_rdf4j
     def set_namespace(self, prefix: str, value: str) -> None:
         auth = requests.auth.HTTPBasicAuth(self.service_cfg.user, self.service_cfg.passwd)
@@ -410,39 +421,47 @@
     if config.rest_api == RestApi.BLAZEGRAPH:
         # Remove /sparql at the end
         return config.url.rpartition("/")[0]
     return config.url
 
 
 class AsyncGraphDBClient(GraphDBClient):
-    def __init__(self, service_cfg: Optional[ServiceConfig] = None) -> None:
-        super().__init__(service_cfg)
-        self.sparql = AsyncSparqlWrapper(self.service_cfg.url, self.service_cfg.ca_bundle)
-        self._init_sparql_wrapper()
+    """Asynchronous GraphDB client for sending sparql queries to GraphDB server
+
+    Args:
+        service_cfg: Service configuration (see ServiceConfig)
+        custom_headers: Added to SPARQLWrapper using addCustomHttpHeader
+
+    Example:
+    >>> import asyncio
+    >>> from cimsparql.graphdb import AsyncGraphDBClient
+    >>> gdbc = AsyncGraphDBClient()
+    >>> query = 'select * where { ?subject ?predicate ?object } limit 10'
+    >>> df, row = await gdbc.get_table(query)
+
+    Where row is the output of graphdb.data_row
+    """
+
+    sparql_wrapper = AsyncSparqlWrapper
 
     async def _exec_query(self, query: str) -> SparqlResult:
         self._prep_query(query)
         results = await self.sparql.queryAndConvert()
         return self._process_result(results)
 
     async def exec_query(self, query: str) -> List[Dict[str, str]]:
         out = await self._exec_query(query)
         return out["out"]
 
     async def get_table(self, query: str) -> Tuple[pd.DataFrame, Dict[str, str]]:
-        """
+        """Get result from sparql query as a pandas dataframe
+
         Args:
            query: to sparql server
            limit: limit number of resulting rows
-        Example:
-           >>> from cimsparql.graphdb import GraphDBClient
-           >>> from cimsparql.url import service
-           >>> gdbc = GraphDBClient(service('LATEST'))
-           >>> query = 'select * where { ?subject ?predicate ?object }'
-           >>> gdbc.get_table(query, limit=10)
         """
         res = await self._exec_query(query)
         return self._convert_query_result_to_df(res)
 
 
 def make_async(client: GraphDBClient) -> AsyncGraphDBClient:
     """
```

### Comparing `cimsparql-2.7.3/cimsparql/model.py` & `cimsparql-2.8.0/cimsparql/model.py`

 * *Files 2% similar despite different names*

```diff
@@ -24,17 +24,19 @@
     DisconnectedDataFrame,
     ExchangeDataFrame,
     FullModelDataFrame,
     HVDCBidzonesDataFrame,
     LoadsDataFrame,
     MarketDatesDataFrame,
     PowerFlowDataFrame,
+    RASEquipmentDataFrame,
     RegionsDataFrame,
     StationGroupCodeNameDataFrame,
     SubstationVoltageDataFrame,
+    SvInjectionDataFrame,
     SynchronousMachinesDataFrame,
     TransfConToConverterDataFrame,
     TransformersDataFrame,
     TransformerWindingDataFrame,
     TransformerWindingsDataFrame,
     WindGeneratingUnitsDataFrame,
 )
@@ -420,14 +422,18 @@
         query_angle = self.two_winding_angle_query(region)
         data = await self.get_table_and_convert(query, index="mrid")
         angle = await self.get_table_and_convert(query_angle, index="mrid")
         if not angle.empty:
             data["angle"] += angle.reindex(index=data.index, fill_value=0.0).squeeze()
         return TransformerWindingDataFrame(data)
 
+    @property
+    def winding_query(self) -> str:
+        return self.template_to_query(templates.WINDING)
+
     def three_winding_loss_query(self, region: Optional[str] = None) -> str:
         substitutes = {"region": region or ".*"}
         return self.template_to_query(templates.THREE_WINDING_LOSS_QUERY, substitutes)
 
     def three_winding_transformers_query(
         self, region: Optional[str] = None, rate: Optional[str] = None
     ) -> str:
@@ -522,14 +528,22 @@
         df = await self.get_table_and_convert(query)
         # Unable to group on max within the sparql query so we do it here.
         df = df.iloc[df.groupby("mrid")["p"].idxmax()].set_index("mrid")
         df["p"] *= df["direction"]
         return DcActiveFlowDataFrame(df.drop(columns="direction"))
 
     @property
+    def sv_injection_query(self) -> str:
+        return self.template_to_query(templates.SV_INJECTION_QUERY)
+
+    async def sv_injection(self) -> SvInjectionDataFrame:
+        df = await self.get_table_and_convert(self.sv_injection_query)
+        return SvInjectionDataFrame(df)
+
+    @property
     def regions_query(self) -> str:
         return self.template_to_query(templates.REGIONS_QUERY)
 
     async def regions(self) -> RegionsDataFrame:
         """Query regions
 
         Property:
@@ -555,16 +569,20 @@
         Fetching mrid of converters placed on HVDC exchange corridors together with
         to/from bidzone
         """
         df = await self.get_table_and_convert(self.hvdc_converter_bidzone_query, index="mrid")
         return HVDCBidzonesDataFrame(df)
 
     @property
-    def protective_action_query(self) -> str:
-        return self.template_to_query(templates.PROTECTIVE_ACTION_QUERY)
+    def ras_equipment_query(self) -> str:
+        return self.template_to_query(templates.RAS_EQUIPMENT_QUERY)
+
+    async def ras_equipment(self) -> RASEquipmentDataFrame:
+        df = await self.get_table_and_convert(self.ras_equipment_query)
+        return RASEquipmentDataFrame(df)
 
     def add_mrid_query(self, rdf_type: Optional[str] = None, graph: Optional[str] = None) -> str:
         substitutes = {"rdf_type": rdf_type or "?rdf_type", "g": graph or "?g"}
         return self.template_to_query(templates.ADD_MRID_QUERY, substitutes)
 
     def add_mrid(
         self,
@@ -598,37 +616,39 @@
         super().__init__(clients, config, mapper)
 
 
 def get_cim_model(
     service_cfg: Optional[ServiceConfig] = None,
     model_cfg: Optional[ModelConfig] = None,
     async_sparql_wrapper: bool = False,
+    custom_headers: Optional[Dict[str, str]] = None,
 ) -> SingleClientModel:
     """
     Function kept for backward compatibility. Use `get_single_client_model` instead.
     """
-    return get_single_client_model(service_cfg, model_cfg, async_sparql_wrapper)
+    return get_single_client_model(service_cfg, model_cfg, async_sparql_wrapper, custom_headers)
 
 
 def get_single_client_model(
     service_cfg: Optional[ServiceConfig] = None,
     model_cfg: Optional[ModelConfig] = None,
     async_sparql_wrapper: bool = False,
+    custom_headers: Optional[Dict[str, str]] = None,
 ) -> SingleClientModel:
     """Get a CIM Model.
 
-
     Args:
         service_cfg: Configurations for the triple store service
-        model_cfg: Conifugrations for the CIM mode
+        model_cfg: Configurations for the CIM mode
         async_sparql_wrapper: If True http calls are made via asynchronous requests.
             If False, the native SparqlWrapper sends requests via urllib
+        custom_headers: Custom headers to be added to the requests
     """
-    c = AsyncGraphDBClient(service_cfg) if async_sparql_wrapper else GraphDBClient(service_cfg)
-    return SingleClientModel(c, model_cfg)
+    Client = AsyncGraphDBClient if async_sparql_wrapper else GraphDBClient
+    return SingleClientModel(Client(service_cfg, custom_headers), model_cfg)
 
 
 def query_name(query: str) -> str:
     """
     Extract the name of the query provided that the first line starts with # Name: <name>.
     If no match is found, an empty string is returned
     """
@@ -660,11 +680,12 @@
         "Disconnected",
         "Loads",
         "Branch node withdraw",
         "DC Active Power Flow",
         "Series compensators",
         "SV branch",
         "Power flow",
+        "SvInjection",
     )
     for query in exec_from_tpssvssh:
         clients[query] = tpsvssh_client
     return Model(clients, model_cfg, mapper)
```

### Comparing `cimsparql-2.7.3/cimsparql/sparql/ac_lines.sparql` & `cimsparql-2.8.0/cimsparql/sparql/ac_lines.sparql`

 * *Files 2% similar despite different names*

```diff
@@ -38,15 +38,14 @@
           cim:ACLineSegment.bch ?b;
           cim:IdentifiedObject.mRID ?mrid;
           cim:IdentifiedObject.name ?name;
           cim:ConductingEquipment.BaseVoltage/cim:BaseVoltage.nominalVoltage ?un;
           cim:Conductor.length ?length .
 
   ?terminal cim:Terminal.ConductingEquipment ?acline;
-            cim:IdentifiedObject.mRID ?t_mrid;
             cim:Terminal.ConnectivityNode ?con_node;
             cim:Terminal.sequenceNumber|cim:ACDCTerminal.sequenceNumber ?nr .
 
   # Find substation of each connectivity node of the terminals above
   ?con_node cim:ConnectivityNode.ConnectivityNodeContainer/cim:VoltageLevel.Substation ?substation .
 
   # Find area and optionally bidzone for each substation
@@ -74,15 +73,15 @@
   optional {?terminal cim:Terminal.TopologicalNode/cim:IdentifiedObject.mRID ?term_top_node_mrid} .
   optional {?terminal ^cim:SvPowerFlow.Terminal/cim:SvPowerFlow.p ?p .}
 
   # Assign an mrid to the ?node_<nr> variable. The mrid is set to the first that exist
   # 1) mRID of the topological node of the connectivity node for each terminal
   # 2) mRID of the topological node of each terminal
   # 3) mrID of the terminal
-  bind(coalesce(?con_top_node_mrid, ?term_top_node_mrid, ?t_mrid) as ?node)
+  bind(coalesce(?con_top_node_mrid, ?term_top_node_mrid) as ?node)
 
   # Create variables for node 1 and node 2
   bind(if(?nr = 1, str(?p), '') as ?p_1)
   bind(if(?nr = 1, ?node, '') as ?node_1)
   bind(if(?nr = 1, ?connected, False) as ?connected_1)
   bind(if(?nr = 1, ?bidzone, '') as ?bidzone_1)
   bind(if(?nr = 2, str(?p), '') as ?p_2)
```

### Comparing `cimsparql-2.7.3/cimsparql/sparql/borders.sparql` & `cimsparql-2.8.0/cimsparql/sparql/borders.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/branch_node_withdraw.sparql` & `cimsparql-2.8.0/cimsparql/sparql/branch_node_withdraw.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/bus.sparql` & `cimsparql-2.8.0/cimsparql/sparql/bus.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/connections.sparql` & `cimsparql-2.8.0/cimsparql/sparql/connections.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/converter_hvdc_bidzones.sparql` & `cimsparql-2.8.0/cimsparql/sparql/converter_hvdc_bidzones.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/converters.sparql` & `cimsparql-2.8.0/cimsparql/sparql/converters.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/coordinates.sparql` & `cimsparql-2.8.0/cimsparql/sparql/coordinates.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/dc_active_power_flow.sparql` & `cimsparql-2.8.0/cimsparql/sparql/dc_active_power_flow.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/exchange.sparql` & `cimsparql-2.8.0/cimsparql/sparql/exchange.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/full_model.sparql` & `cimsparql-2.8.0/cimsparql/sparql/full_model.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/loads.sparql` & `cimsparql-2.8.0/cimsparql/sparql/loads.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/regions.sparql` & `cimsparql-2.8.0/cimsparql/sparql/regions.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/series_compensators.sparql` & `cimsparql-2.8.0/cimsparql/sparql/series_compensators.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/substation_voltage_level.sparql` & `cimsparql-2.8.0/cimsparql/sparql/substation_voltage_level.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/sv_branch.sparql` & `cimsparql-2.8.0/cimsparql/sparql/sv_branch.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/synchronous_machines.sparql` & `cimsparql-2.8.0/cimsparql/sparql/synchronous_machines.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/three_winding.sparql` & `cimsparql-2.8.0/cimsparql/sparql/three_winding.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/three_winding_dummy_nodes.sparql` & `cimsparql-2.8.0/cimsparql/sparql/three_winding_dummy_nodes.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/three_winding_loss.sparql` & `cimsparql-2.8.0/cimsparql/sparql/three_winding_loss.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/transformers.sparql` & `cimsparql-2.8.0/cimsparql/sparql/transformers.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/transformers_connected_to_converter.sparql` & `cimsparql-2.8.0/cimsparql/sparql/transformers_connected_to_converter.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/two_winding_transformer.sparql` & `cimsparql-2.8.0/cimsparql/sparql/two_winding_transformer.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/two_winding_transformer_angle.sparql` & `cimsparql-2.8.0/cimsparql/sparql/two_winding_transformer_angle.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/sparql/wind_generating_units.sparql` & `cimsparql-2.8.0/cimsparql/sparql/wind_generating_units.sparql`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/templates.py` & `cimsparql-2.8.0/cimsparql/templates.py`

 * *Files 2% similar despite different names*

```diff
@@ -21,28 +21,30 @@
 DISCONNECTED_QUERY = _read_template(sparql_folder / "disconnected.sparql")
 EXCHANGE_QUERY = _read_template(sparql_folder / "exchange.sparql")
 FULL_MODEL_QUERY = _read_template(sparql_folder / "full_model.sparql")
 HVDC_CONVERTER_BIDZONES = _read_template(sparql_folder / "converter_hvdc_bidzones.sparql")
 LOADS_QUERY = _read_template(sparql_folder / "loads.sparql")
 MARKET_DATES_QUERY = _read_template(sparql_folder / "market_dates.sparql")
 POWER_FLOW_QUERY = _read_template(sparql_folder / "power_flow.sparql")
-PROTECTIVE_ACTION_QUERY = _read_template(sparql_folder / "protective_action.sparql")
+RAS_EQUIPMENT_QUERY = _read_template(sparql_folder / "ras_equipment.sparql")
 REGIONS_QUERY = _read_template(sparql_folder / "regions.sparql")
 SERIES_COMPENSATORS_QUERY = _read_template(sparql_folder / "series_compensators.sparql")
 STATION_GROUP_CODE_NAME_QUERY = _read_template(
     sparql_folder / "station_group_code_and_names.sparql"
 )
 SUBSTATION_VOLTAGE_LEVEL_QUERY = _read_template(sparql_folder / "substation_voltage_level.sparql")
 SV_BRANCH_QUERY = _read_template(sparql_folder / "sv_branch.sparql")
+SV_INJECTION_QUERY = _read_template(sparql_folder / "sv_injection.sparql")
 SYNCHRONOUS_MACHINES_QUERY = _read_template(sparql_folder / "synchronous_machines.sparql")
 THREE_WINDING_DUMMY_NODES_QUERY = _read_template(sparql_folder / "three_winding_dummy_nodes.sparql")
 THREE_WINDING_LOSS_QUERY = _read_template(sparql_folder / "three_winding_loss.sparql")
 THREE_WINDING_QUERY = _read_template(sparql_folder / "three_winding.sparql")
 TRANSFORMERS_QUERY = _read_template(sparql_folder / "transformers.sparql")
 TRANSFORMERS_CONNECTED_TO_CONVERTER_QUERY = _read_template(
     sparql_folder / "transformers_connected_to_converter.sparql"
 )
 TWO_WINDING_ANGLE_QUERY = _read_template(sparql_folder / "two_winding_transformer_angle.sparql")
 TWO_WINDING_QUERY = _read_template(sparql_folder / "two_winding_transformer.sparql")
 TYPE_MAPPER_QUERY = _read_template(sparql_folder / "type_mapper.sparql")
 WIND_GENERATING_UNITS_QUERY = _read_template(sparql_folder / "wind_generating_units.sparql")
 TRANSFORMER_WINDINGS_QUERY = _read_template(sparql_folder / "transformer_windings.sparql")
+WINDING = _read_template(sparql_folder / "winding.sparql")
```

### Comparing `cimsparql-2.7.3/cimsparql/type_mapper.py` & `cimsparql-2.8.0/cimsparql/type_mapper.py`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/url.py` & `cimsparql-2.8.0/cimsparql/url.py`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/cimsparql/value_mapper.py` & `cimsparql-2.8.0/cimsparql/value_mapper.py`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/pkg_data/namespaces.json` & `cimsparql-2.8.0/pkg_data/namespaces.json`

 * *Files 12% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9583333333333334%*

 * *Differences: {"'SN'": "'http://www.statnett.no/CIM-schema-cim15-extension#'"}*

```diff
@@ -1,10 +1,10 @@
 {
     "ALG": "http://www.alstom.com/grid/CIM-schema-cim15-extension#",
-    "SN": "http://SN#",
+    "SN": "http://www.statnett.no/CIM-schema-cim15-extension#",
     "cim": "http://iec.ch/TC57/2013/CIM-schema-cim16#",
     "cims": "http://iec.ch/TC57/1999/rdf-schema-extensions-19990926#",
     "dc": "http://purl.org/dc/elements/1.1/",
     "entsoe": "http://entsoe.eu/CIM/SchemaExtension/3/1#",
     "foaf": "http://xmlns.com/foaf/0.1/",
     "md": "http://iec.ch/TC57/61970-552/ModelDescription/1#",
     "owl": "http://www.w3.org/2002/07/owl#",
```

### Comparing `cimsparql-2.7.3/pkg_data/native_store_config_template.ttl` & `cimsparql-2.8.0/pkg_data/native_store_config_template.ttl`

 * *Files identical despite different names*

### Comparing `cimsparql-2.7.3/pyproject.toml` & `cimsparql-2.8.0/pyproject.toml`

 * *Files 7% similar despite different names*

```diff
@@ -1,21 +1,16 @@
-# Example configuration for Black.
-
-# NOTE: you have to use single-quoted strings in TOML for regular expressions.
-# It's the equivalent of r-strings in Python.  Multiline strings are treated as
-# verbose regular expressions by Black.  Use [ ] to denote a significant space
-# character.
 [tool.poetry]
 name = "cimsparql"
-version = "2.7.3"
+version = "2.8.0"
 description = "CIM query utilities"
 readme = "README.md"
 authors = ["Statnett Datascience <Datascience.Drift@Statnett.no>"]
 repository = "https://github.com/statnett/cimsparql.git"
 include = ["pkg_data/*"]
+exclude = ["tests/*"]
 
 [tool.poetry.dependencies]
 SPARQLWrapper = "*"
 StrEnum = "*"
 pandera = "*"
 pandas = "*"
 python = "^3.9"
@@ -45,20 +40,28 @@
 pytest = ">= 6"
 pytest-asyncio = "*"
 pytest-cov = "*"
 pytest-integration = "*"
 pytest-profiling = "*"
 pytest-httpserver = "*"
 
+[tool.poetry.group.docs]
+optional = true
+
+[tool.poetry.group.docs.dependencies]
+sphinx = "^5.2.3"
+sphinx_autodoc_typehints = "^1.23.0"
+recommonmark = "^0.7.1"
+sphinx_rtd_theme = "^0.5.1"
 
 [tool.poetry-dynamic-versioning]
 enable = false
 vcs = "git"
 style = "semver"
-pattern = "^(?P<base>\\d+\\.\\d+\\.\\d+)(-?((?P<stage>[a-zA-Z]+)\\.?(?P<revision>\\d+)?))?$"
+pattern = '^(?P<base>\d+\.\d+\.\d+)(-?((?P<stage>[a-zA-Z]+)\.?(?P<revision>\d+)?))?$'
 
 [tool.isort]
 profile = "black"
 line_length = 100
 
 [tool.black]
 line-length = 100
```

### Comparing `cimsparql-2.7.3/PKG-INFO` & `cimsparql-2.8.0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: cimsparql
-Version: 2.7.3
+Version: 2.8.0
 Summary: CIM query utilities
 Home-page: https://github.com/statnett/cimsparql.git
 Author: Statnett Datascience
 Author-email: Datascience.Drift@Statnett.no
 Requires-Python: >=3.9,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
```

