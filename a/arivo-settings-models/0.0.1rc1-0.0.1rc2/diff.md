# Comparing `tmp/arivo-settings_models-0.0.1rc1.tar.gz` & `tmp/arivo-settings_models-0.0.1rc2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/arivo-settings_models-0.0.1rc1.tar", last modified: Thu Jun 22 11:56:04 2023, max compression
+gzip compressed data, was "dist/arivo-settings_models-0.0.1rc2.tar", last modified: Wed Jun 28 12:22:28 2023, max compression
```

## Comparing `arivo-settings_models-0.0.1rc1.tar` & `arivo-settings_models-0.0.1rc2.tar`

### file list

```diff
@@ -1,42 +1,42 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/
--rw-rw-rw-   0 root         (0) root         (0)       62 2023-05-11 10:22:52.000000 arivo-settings_models-0.0.1rc1/.coveragerc
--rw-r--r--   0 root         (0) root         (0)      111 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/AUTHORS
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/settings_models/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-22 11:55:45.000000 arivo-settings_models-0.0.1rc1/settings_models/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     1977 2023-06-13 13:58:32.000000 arivo-settings_models-0.0.1rc1/settings_models/validators.py
--rw-rw-rw-   0 root         (0) root         (0)      372 2023-06-13 13:58:32.000000 arivo-settings_models-0.0.1rc1/settings_models/doc.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/settings_models/settings/
--rw-rw-rw-   0 root         (0) root         (0)      749 2023-06-13 13:58:32.000000 arivo-settings_models-0.0.1rc1/settings_models/settings/gate_control.py
--rw-rw-rw-   0 root         (0) root         (0)      332 2023-06-13 13:58:32.000000 arivo-settings_models-0.0.1rc1/settings_models/settings/intercom.py
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-22 11:55:45.000000 arivo-settings_models-0.0.1rc1/settings_models/settings/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)      477 2023-06-13 13:58:32.000000 arivo-settings_models-0.0.1rc1/settings_models/settings/enforcement.py
--rw-rw-rw-   0 root         (0) root         (0)    17036 2023-06-13 13:58:32.000000 arivo-settings_models-0.0.1rc1/settings_models/settings/common.py
--rw-rw-rw-   0 root         (0) root         (0)      524 2023-06-13 13:58:32.000000 arivo-settings_models-0.0.1rc1/settings_models/settings/device_keys.py
--rw-rw-rw-   0 root         (0) root         (0)      163 2023-06-13 13:58:32.000000 arivo-settings_models-0.0.1rc1/settings_models/_combat.py
--rw-rw-rw-   0 root         (0) root         (0)     6637 2023-06-22 11:55:45.000000 arivo-settings_models-0.0.1rc1/settings_models/serialization.py
--rw-rw-rw-   0 root         (0) root         (0)      360 2023-05-17 14:33:24.000000 arivo-settings_models-0.0.1rc1/tox.ini
--rw-rw-rw-   0 root         (0) root         (0)      445 2023-05-11 10:22:52.000000 arivo-settings_models-0.0.1rc1/setup.py
--rw-rw-rw-   0 root         (0) root         (0)       57 2023-05-17 14:33:24.000000 arivo-settings_models-0.0.1rc1/requirements.txt
--rw-r--r--   0 root         (0) root         (0)      707 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/PKG-INFO
--rw-rw-rw-   0 root         (0) root         (0)     1353 2023-06-22 11:55:45.000000 arivo-settings_models-0.0.1rc1/.gitlab-ci.yml
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/tools/
--rw-rw-rw-   0 root         (0) root         (0)      439 2023-05-17 14:33:24.000000 arivo-settings_models-0.0.1rc1/tools/pages.py
--rw-rw-rw-   0 root         (0) root         (0)      569 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/tests/
--rw-rw-rw-   0 root         (0) root         (0)     3417 2023-06-13 13:58:32.000000 arivo-settings_models-0.0.1rc1/tests/test_serialization.py
--rw-rw-rw-   0 root         (0) root         (0)    32787 2023-06-13 13:58:32.000000 arivo-settings_models-0.0.1rc1/tests/test_validation.py
--rw-rw-rw-   0 root         (0) root         (0)    11070 2023-06-13 13:58:32.000000 arivo-settings_models-0.0.1rc1/tests/test_models.py
--rw-rw-rw-   0 root         (0) root         (0)      873 2023-06-13 13:58:32.000000 arivo-settings_models-0.0.1rc1/tests/utils.py
--rw-rw-rw-   0 root         (0) root         (0)      183 2023-05-11 10:22:52.000000 arivo-settings_models-0.0.1rc1/README.md
--rw-r--r--   0 root         (0) root         (0)     1128 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/ChangeLog
--rw-rw-rw-   0 root         (0) root         (0)       18 2023-05-11 10:22:52.000000 arivo-settings_models-0.0.1rc1/test-requirements.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/docs/
--rw-rw-rw-   0 root         (0) root         (0)       27 2023-05-11 10:22:52.000000 arivo-settings_models-0.0.1rc1/docs/migrations.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/arivo_settings_models.egg-info/
--rw-r--r--   0 root         (0) root         (0)      707 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/arivo_settings_models.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)       57 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/arivo_settings_models.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/arivo_settings_models.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/arivo_settings_models.egg-info/not-zip-safe
--rw-r--r--   0 root         (0) root         (0)       47 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/arivo_settings_models.egg-info/pbr.json
--rw-r--r--   0 root         (0) root         (0)      922 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/arivo_settings_models.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)       16 2023-06-22 11:56:04.000000 arivo-settings_models-0.0.1rc1/arivo_settings_models.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/tests/
+-rw-rw-rw-   0 root         (0) root         (0)     3417 2023-05-31 10:49:14.000000 arivo-settings_models-0.0.1rc2/tests/test_serialization.py
+-rw-rw-rw-   0 root         (0) root         (0)    11501 2023-06-28 12:22:07.000000 arivo-settings_models-0.0.1rc2/tests/test_models.py
+-rw-rw-rw-   0 root         (0) root         (0)    36369 2023-06-28 12:22:07.000000 arivo-settings_models-0.0.1rc2/tests/test_validation.py
+-rw-rw-rw-   0 root         (0) root         (0)      873 2023-05-31 10:49:14.000000 arivo-settings_models-0.0.1rc2/tests/utils.py
+-rw-rw-rw-   0 root         (0) root         (0)      183 2023-05-19 07:50:33.000000 arivo-settings_models-0.0.1rc2/README.md
+-rw-r--r--   0 root         (0) root         (0)      111 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/AUTHORS
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/tools/
+-rw-rw-rw-   0 root         (0) root         (0)      439 2023-05-19 07:50:33.000000 arivo-settings_models-0.0.1rc2/tools/pages.py
+-rw-rw-rw-   0 root         (0) root         (0)      360 2023-05-19 07:50:33.000000 arivo-settings_models-0.0.1rc2/tox.ini
+-rw-rw-rw-   0 root         (0) root         (0)      445 2023-05-19 07:50:33.000000 arivo-settings_models-0.0.1rc2/setup.py
+-rw-rw-rw-   0 root         (0) root         (0)      569 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/setup.cfg
+-rw-rw-rw-   0 root         (0) root         (0)       57 2023-05-19 07:50:33.000000 arivo-settings_models-0.0.1rc2/requirements.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/arivo_settings_models.egg-info/
+-rw-r--r--   0 root         (0) root         (0)       57 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/arivo_settings_models.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       47 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/arivo_settings_models.egg-info/pbr.json
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/arivo_settings_models.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/arivo_settings_models.egg-info/not-zip-safe
+-rw-r--r--   0 root         (0) root         (0)      922 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/arivo_settings_models.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)      707 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/arivo_settings_models.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)       16 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/arivo_settings_models.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/docs/
+-rw-rw-rw-   0 root         (0) root         (0)       27 2023-05-19 07:50:33.000000 arivo-settings_models-0.0.1rc2/docs/migrations.md
+-rw-rw-rw-   0 root         (0) root         (0)     1353 2023-06-28 12:22:07.000000 arivo-settings_models-0.0.1rc2/.gitlab-ci.yml
+-rw-rw-rw-   0 root         (0) root         (0)       62 2023-05-19 07:50:33.000000 arivo-settings_models-0.0.1rc2/.coveragerc
+-rw-rw-rw-   0 root         (0) root         (0)       18 2023-05-19 07:50:33.000000 arivo-settings_models-0.0.1rc2/test-requirements.txt
+-rw-r--r--   0 root         (0) root         (0)     1274 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/ChangeLog
+-rw-r--r--   0 root         (0) root         (0)      707 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/PKG-INFO
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/settings_models/
+-rw-rw-rw-   0 root         (0) root         (0)     1977 2023-05-31 10:49:14.000000 arivo-settings_models-0.0.1rc2/settings_models/validators.py
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 12:22:07.000000 arivo-settings_models-0.0.1rc2/settings_models/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 12:22:28.000000 arivo-settings_models-0.0.1rc2/settings_models/settings/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 12:22:07.000000 arivo-settings_models-0.0.1rc2/settings_models/settings/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)      332 2023-05-31 10:49:14.000000 arivo-settings_models-0.0.1rc2/settings_models/settings/intercom.py
+-rw-rw-rw-   0 root         (0) root         (0)      524 2023-05-31 10:49:14.000000 arivo-settings_models-0.0.1rc2/settings_models/settings/device_keys.py
+-rw-rw-rw-   0 root         (0) root         (0)      749 2023-06-28 12:22:07.000000 arivo-settings_models-0.0.1rc2/settings_models/settings/gate_control.py
+-rw-rw-rw-   0 root         (0) root         (0)      477 2023-05-31 10:49:14.000000 arivo-settings_models-0.0.1rc2/settings_models/settings/enforcement.py
+-rw-rw-rw-   0 root         (0) root         (0)    20179 2023-06-28 12:22:07.000000 arivo-settings_models-0.0.1rc2/settings_models/settings/common.py
+-rw-rw-rw-   0 root         (0) root         (0)     6344 2023-06-28 12:22:07.000000 arivo-settings_models-0.0.1rc2/settings_models/serialization.py
+-rw-rw-rw-   0 root         (0) root         (0)      372 2023-06-28 12:22:07.000000 arivo-settings_models-0.0.1rc2/settings_models/doc.py
+-rw-rw-rw-   0 root         (0) root         (0)      163 2023-05-31 10:49:14.000000 arivo-settings_models-0.0.1rc2/settings_models/_combat.py
```

### Comparing `arivo-settings_models-0.0.1rc1/settings_models/validators.py` & `arivo-settings_models-0.0.1rc2/settings_models/validators.py`

 * *Files identical despite different names*

### Comparing `arivo-settings_models-0.0.1rc1/settings_models/settings/gate_control.py` & `arivo-settings_models-0.0.1rc2/settings_models/settings/gate_control.py`

 * *Files identical despite different names*

### Comparing `arivo-settings_models-0.0.1rc1/settings_models/settings/common.py` & `arivo-settings_models-0.0.1rc2/settings_models/settings/common.py`

 * *Files 18% similar despite different names*

```diff
@@ -147,62 +147,97 @@
         elif values.get("entry_type") in [CommandCostEntryTypes.cancel_remaining_costs,
                                           CommandCostEntryTypes.payoff_costs]:
             if values["group"] is not None:
                 raise ValueError("group must NOT be set")
         return values
 
 
+class ShorttermLimitType(str, Enum):
+    """
+    Types of shortterm limits
+    """
+    no_limit = "no_limit"
+    """no limit"""
+
+    shortterm_count = "shortterm_count"
+    """number of shortterm parkers in area is compared to limit"""
+
+    total_count = "total_count"
+    """number of all parkers in area are compared to limit"""
+
+
 class ParkingArea(SettingsModel):
     """
-    Defines a physical or logical areas of the whole parking lot by specifying the gates.
-       Physical area example: Garage1(entry Garage1 + exit Garage1) and Garage2(entry Garage2 + exit Garage2)
-       Logical area example: Shortterm area (entry + exit) and emergency area (entry + exit + emergency lane)
-    Also defines if shortterm parkers are allowed and the cost entries for shortterm parkers / default cost entries
+    Defines a physical area of the whole parking lot by specifying the gates of types entry, exit, bidirectional or
+    transit_barrier/transit_access_check. Also defines which gates allow shortterm parkers, the default cost entries
+    for unknown parkers and pay-per-use parkers and limits for shortterm parkers in this area.
+    This is the config for counters and shortterm parkers (registered and unregistered)
     """
     id: str = Field(..., description="Id of the parking area. UUID string in canonical textual representation")
     name: str = Field(..., description="Name for UIs", max_length=126)
-    gates: Optional[List[str]] = Field(None, description="Gates of this parking area. Mostly used for selection of "
-                                                         "parking area on enter. None means all gates")
-    shortterm_allowed: bool = Field(..., description="If this parking area can be selected for shortterm parkers")
+    gates: List[str] = Field(..., description="Gates in this physical area (only types entry, exit, bidirectional or "
+                                              "transit_barrier/transit_access_check)", min_items=1)
+    shortterm_gates: List[str] = Field(..., description="Gates in this physical area (only types entry, exit, "
+                                                        "bidirectional or transit_barrier/transit_access_check), where "
+                                                        "shortterm parkers are allowed")
     default_cost_entries: List[CostEntryData] = Field(..., description="Default cost entries added on entry in this "
-                                                                       "parking area, e.g. for shortterm parkers")
+                                                                       "parking area for unknown parkers")
+    pay_per_use_cost_entries: Optional[List[CostEntryData]] = \
+        Field(None, description="Default cost entries added on entry in this parking area for pay-per-use parkers. None"
+                                " is fallback to default_cost_entries")
+    shortterm_limit_type: ShorttermLimitType = Field(..., description="Type of shortterm limit")
+    shortterm_limit: int = Field(..., description="Limit value in this area. Compared to value specified in "
+                                                  "shortterm_limit_type", ge=0)
 
     id_validator = uuid_validator("id")
 
     @validator('default_cost_entries', each_item=True)
     def cost_entry_validator(cls, cost_entry):
         if cost_entry.entry_type in [CommandCostEntryTypes.partial_rate_change, CommandCostEntryTypes.payment,
                                      CommandCostEntryTypes.cancel_remaining_costs, CommandCostEntryTypes.payoff_costs]:
             raise ValueError(f"{cost_entry.entry_type} is not allowed as default cost entry in parking area")
         return cost_entry
 
+    @validator('pay_per_use_cost_entries', each_item=True)
+    def pay_per_use_cost_entries_validator(cls, cost_entry):
+        if cost_entry.entry_type in [CommandCostEntryTypes.partial_rate_change, CommandCostEntryTypes.payment,
+                                     CommandCostEntryTypes.cancel_remaining_costs, CommandCostEntryTypes.payoff_costs]:
+            raise ValueError(f"{cost_entry.entry_type} is not allowed as pay per use cost entry in parking area")
+        return cost_entry
+
+    @root_validator(skip_on_failure=True)
+    def validate_shortterm_gates_in_gates(cls, values):
+        """
+        check if all shortterm gates are in gates
+        """
+        if not all(gate in values["gates"] for gate in values["shortterm_gates"]):
+            raise ValueError("All shortterm gates must be in gates")
+        return values
+
 
 class Parksetting(SettingsModel):
     """
-    Defines the terms and conditions for parking sessions of registered users. At the moment only special parking rates
-    can be defined. The parking area, where this parksetting can be used, must be set.
+    Defines the terms and conditions for parking sessions of registered users. This is not used for registered
+    shortterm parkers.
     """
     id: str = Field(..., description="Id of the parksetting. UUID string in canonical textual representation")
     name: str = Field(..., description="Name for UIs", max_length=126)
-    parking_area_id: str = Field(..., description="id of parking area where this parksetting can be used")
-    default_cost_entries: Optional[List[CostEntryData]] \
-        = Field(None, description="Default cost entries added on entry. Empty list is free,"
-                                  "None means take cost entries set in parking area.")
+    gates: List[str] = Field(..., description="Gates this parksetting is valid for (only types entry, exit, "
+                                              "bidirectional or transit_barrier/transit_access_check", min_items=1)
+    default_cost_entries: List[CostEntryData] = Field(..., description="Default cost entries added on entry. "
+                                                                       "Empty list is free.")
 
     id_validator = uuid_validator("id")
-    parking_area_id_validator = uuid_validator("parking_area_id")
 
-    @validator('default_cost_entries')
-    def cost_entry_validator(cls, cost_entries):
-        for cost_entry in (cost_entries or []):
-            if cost_entry.entry_type in [CommandCostEntryTypes.partial_rate_change, CommandCostEntryTypes.payment,
-                                         CommandCostEntryTypes.cancel_remaining_costs,
-                                         CommandCostEntryTypes.payoff_costs]:
-                raise ValueError(f"{cost_entry.entry_type} is not allowed as default cost entry in parksetting")
-        return cost_entries
+    @validator('default_cost_entries', each_item=True)
+    def cost_entry_validator(cls, cost_entry):
+        if cost_entry.entry_type in [CommandCostEntryTypes.partial_rate_change, CommandCostEntryTypes.payment,
+                                     CommandCostEntryTypes.cancel_remaining_costs, CommandCostEntryTypes.payoff_costs]:
+            raise ValueError(f"{cost_entry.entry_type} is not allowed as default cost entry in parksetting")
+        return cost_entry
 
 
 class CostGroup(SettingsModel):
     """
     Definition of cost group, specifying name, account_id and VAT rate.
     """
     id: str = Field(..., description="Id of the cost group. Scheme of this ID see "
@@ -308,22 +343,54 @@
     address: AddressModel = Field(..., description="Address for written support letters")
     phone_number: constr(min_length=3, max_length=32, regex=r"^\+[0-9 ]+$") = \
         Field(..., description="Phone number for support (not emergency calls)")
     email_address: constr(min_length=3, max_length=254, regex=r"^[a-zA-Z0-9_.+-]+@[a-zA-Z0-9-]+\.[a-zA-Z0-9-.]+$") = \
         Field(..., description="Email address for support")
 
 
+class GarageModes(str, Enum):
+    """
+    Garage modes
+    """
+    barrier = "barrier"
+    """Standard barrier mode for commercial parking lots (barriers at entries and exits)"""
+
+    freeflow = "freeflow"
+    """Standard freeflow mode for commercial parking lots (no barriers at all)"""
+
+    freeflow_surveillance = "freeflow_surveillance"
+    """Surveillance only freeflow mode. No payments. Just observation of parking lot"""
+
+
 class GarageSettings(SettingsModel):
     """
     General garage settings defining general behavior of parking lot. Contains mode and flags for features which are
     enabled/disabled depending on the mode
     """
-    mode: str = Field(..., description="General parking lot mode, e.g. freeflow. More for information in UI and setup "
-                                       "than for real technical use")
+    mode: GarageModes = Field(..., description="General parking lot mode, e.g. freeflow. This field is more for "
+                                               "information in UI and setup than for real technical use.")
     honest_payment_enabled: bool = Field(..., description="If honest payments are allowed")
+    enforcement_enabled: bool = Field(..., description="If unpaid parking sessions can be enforced")
+    payment_possible: bool = Field(..., description="If any payments are possible at all")
+
+    @root_validator(skip_on_failure=True, pre=True)
+    def data_validation(cls, values):
+        if values["mode"] == GarageModes.freeflow:
+            values["honest_payment_enabled"] = True
+            values["enforcement_enabled"] = True
+            values["payment_possible"] = True
+        elif values["mode"] == GarageModes.barrier:
+            values["honest_payment_enabled"] = False
+            values["enforcement_enabled"] = False
+            values["payment_possible"] = True
+        elif values["mode"] == GarageModes.freeflow_surveillance:
+            values["honest_payment_enabled"] = False
+            values["enforcement_enabled"] = False
+            values["payment_possible"] = False
+        return values
 
 
 class GarageName(SettingsModel):
     """
     Names of Garage (directly set in Garage UI / iam)
     """
     name: str = Field(..., description="Name of Garage for UIs and end users", max_length=126)
```

### Comparing `arivo-settings_models-0.0.1rc1/settings_models/settings/device_keys.py` & `arivo-settings_models-0.0.1rc2/settings_models/settings/device_keys.py`

 * *Files identical despite different names*

### Comparing `arivo-settings_models-0.0.1rc1/settings_models/serialization.py` & `arivo-settings_models-0.0.1rc2/settings_models/serialization.py`

 * *Files 6% similar despite different names*

```diff
@@ -15,18 +15,18 @@
 from settings_models.settings.intercom import IntercomSettings
 
 T = TypeVar('T')
 
 _model_mapping = {
     "common/gates": Setting(Gates, "Has one entry for each gate of the garage."),
     "common/rates": Setting(Rates, "Defines the parking costs."),
-    "common/parking_areas": Setting(ParkingAreas, "Defines the physical or logical areas of parking lot "
-                                                  "by specifying the gates"),
-    "common/parksettings": Setting(Parksettings, "Defines the terms and conditions for parking sessions of "
-                                                 "registered users for different parking areas."),
+    "common/parking_areas2": Setting(ParkingAreas, "Defines the physical areas of parking lot by specifying the gates."
+                                                   "Also specifies settings for shortterm users."),
+    "common/parksettings2": Setting(Parksettings, "Defines the terms and conditions for parking sessions of "
+                                                  "registered users (not including registered shortterm users)."),
     "common/privacy_settings": Setting(PrivacySettings),
     "common/cost_groups": Setting(CostGroups, "Defines the costs for different activities."),
     "common/currency": Setting(str, "Defines the currency in which the parking costs are calculated."),
     "common/language": Setting(str, "Defines the language used for the user interface."),
     "common/timezone": Setting(str, "Defines the timezone in which the garage is located."),
     "common/garage_settings": Setting(GarageSettings),
     "common/location": Setting(Location),
@@ -56,21 +56,17 @@
 
 def _key_equal_id_in_value(k: str, v: Any, id_field: str = "id"):
     if k != getattr(v, id_field):
         raise ValueError(f"key must match field {id_field}")
 
 
 def _special_validation(key: str, obj: Any):
-    if key in ["common/rates", "common/parking_areas", "common/parksettings", "common/cost_groups"]:
+    if key in ["common/rates", "common/parking_areas2", "common/parksettings2", "common/cost_groups"]:
         for k, v in obj.items():  # those settings are always dicts
             _key_equal_id_in_value(k, v)
-        if key == "common/parking_areas":
-            shortterm_areas = [area for area in obj.values() if area.shortterm_allowed]
-            if any(area.gates is None for area in shortterm_areas) and len(shortterm_areas) > 1:
-                raise ValueError("No additional shortterm parking area is allowed if entire parking space is shortterm")
     elif key == "common/gates":
         for k, v in obj.items():  # those settings are always dicts
             _key_equal_id_in_value(k, v, "gate")
     elif key == "common/timezone":
         if gettz(obj) is None:
             raise ValueError(f"timezone {obj} unknown")
     elif key == "common/language":
```

### Comparing `arivo-settings_models-0.0.1rc1/PKG-INFO` & `arivo-settings_models-0.0.1rc2/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: arivo-settings_models
-Version: 0.0.1rc1
+Version: 0.0.1rc2
 Summary: Library for arivo parking system settings definitions and models
 Home-page: https://gitlab.com/accessio/onegate/settings-models
 Author: ARIVO
 Author-email: support@arivo.co
 License: "GPL-3",
 Description: # Settings Models
```

### Comparing `arivo-settings_models-0.0.1rc1/.gitlab-ci.yml` & `arivo-settings_models-0.0.1rc2/.gitlab-ci.yml`

 * *Files identical despite different names*

### Comparing `arivo-settings_models-0.0.1rc1/setup.cfg` & `arivo-settings_models-0.0.1rc2/setup.cfg`

 * *Files identical despite different names*

### Comparing `arivo-settings_models-0.0.1rc1/tests/test_serialization.py` & `arivo-settings_models-0.0.1rc2/tests/test_serialization.py`

 * *Files identical despite different names*

### Comparing `arivo-settings_models-0.0.1rc1/tests/test_validation.py` & `arivo-settings_models-0.0.1rc2/tests/test_validation.py`

 * *Files 6% similar despite different names*

```diff
@@ -36,124 +36,124 @@
         self.assertIn("string does not match regex", str(e.exception))
 
     def test_parksettings_success(self):
         self.maxDiff = None
         gt = dump_setting({
             "896150c9-5616-4406-a544-84c3824cfea9": {
                 "id": "896150c9-5616-4406-a544-84c3824cfea9", "name": "Dauerparker mit variablen Kosten",
-                "parking_area_id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac"},
+                "gates": ["gate1"], "default_cost_entries": []},
             "12e8a7e2-be78-488e-8d1a-1486f7da2179": {
                 "id": "12e8a7e2-be78-488e-8d1a-1486f7da2179", "name": "Dauerparker ohne Kosten",
-                "parking_area_id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac",
+                "gates": ["gate1"],
                 "default_cost_entries": [{"entry_type": "static_cost", "value": 123,
                                           "group": "parking_default", "account_id": "0"}]}
         })
-        res = parse_setting("common/parksettings", gt)
+        res = parse_setting("common/parksettings2", gt)
         self.assert_result(dump_setting(res), gt)
 
     def test_parksettings_not_a_uuid(self):
         with self.assertRaises(ValidationError) as e:
-            parse_setting("common/parksettings", dump_setting({
+            parse_setting("common/parksettings2", dump_setting({
                 "12e8a7e2-be78-488e-8d1a-1486f7da2179": {
                     "id": "123",
                     "name": "Dauerparker ohne Kosten",
-                    "parking_area_id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac",
+                    "gates": ["gate1"],
                     "default_cost_entries": []}}))
         self.assertEqual(str(e.exception).count("\n"), 2)
         self.assertIn("must be a uuid string", str(e.exception))
 
     def test_parksettings_id_does_not_match_field(self):
         with self.assertRaises(ValueError) as e:
-            parse_setting("common/parksettings", dump_setting({
+            parse_setting("common/parksettings2", dump_setting({
                 "9999a7e2-be78-488e-8d1a-1486f7da9999": {
                     "id": "0000a7e2-be78-488e-8d1a-1486f7da0000",
                     "name": "Dauerparker ohne Kosten",
-                    "parking_area_id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac",
+                    "gates": ["gate1"],
                     "default_cost_entries": []}}))
         self.assertEqual(str(e.exception).count("\n"), 0)
         self.assertEqual("key must match field id", str(e.exception))
 
         with self.assertRaises(ValueError) as e:
-            parse_setting("common/parksettings", dump_setting({
+            parse_setting("common/parksettings2", dump_setting({
                 "123": {
                     "id": "12e8a7e2-be78-488e-8d1a-1486f7da2179",
                     "name": "Dauerparker ohne Kosten",
-                    "parking_area_id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac",
+                    "gates": ["gate1"],
                     "default_cost_entries": []}}))
         self.assertEqual(str(e.exception).count("\n"), 0)
         self.assertIn("key must match field id", str(e.exception))
 
     def test_parksettings_invalid_default_cost_entry_type(self):
         with self.assertRaises(ValidationError) as e:
-            parse_setting("common/parksettings", dump_setting({
+            parse_setting("common/parksettings2", dump_setting({
                 "0000a7e2-be78-488e-8d1a-1486f7da0000": {
                     "id": "0000a7e2-be78-488e-8d1a-1486f7da0000",
                     "name": "Dauerparker ohne Kosten",
-                    "parking_area_id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac",
+                    "gates": ["gate1"],
                     "default_cost_entries": [
                         {"entry_type": "partial_rate_change", "value": 123,
                          "group": "parking_default", "account_id": "0", "source": "test",
                          "source_id": "1", "idempotency_key": "1234"}
                     ]}}))
         self.assertEqual(str(e.exception).count("\n"), 2)
         self.assertIn("is not allowed as default cost entry in parksetting", str(e.exception))
 
     def test_cost_entry_invalid_type(self):
         with self.assertRaises(ValidationError) as e:
-            parse_setting("common/parksettings", dump_setting({
+            parse_setting("common/parksettings2", dump_setting({
                 "12e8a7e2-be78-488e-8d1a-1486f7da2179": {
                     "id": "12e8a7e2-be78-488e-8d1a-1486f7da2179",
                     "name": "Dauerparker ohne Kosten",
-                    "parking_area_id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac",
+                    "gates": ["gate1"],
                     "default_cost_entries": [
                         {"entry_type": "static_cost123", "value": 123,
                          "group": "parking_default", "account_id": "0", "source": "test",
                          "source_id": "1", "idempotency_key": "1234"}
                     ]}}))
         self.assertEqual(str(e.exception).count("\n"), 2)
         self.assertIn("value is not a valid enumeration member", str(e.exception))
 
     def test_cost_entry_invalid_value(self):
         with self.assertRaises(ValidationError) as e:
-            parse_setting("common/parksettings", dump_setting({
+            parse_setting("common/parksettings2", dump_setting({
                 "12e8a7e2-be78-488e-8d1a-1486f7da2179": {
                     "id": "12e8a7e2-be78-488e-8d1a-1486f7da2179",
                     "name": "Dauerparker ohne Kosten",
-                    "parking_area_id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac",
+                    "gates": ["gate1"],
                     "default_cost_entries": [
                         {"entry_type": "static_cost", "value": "NaN",
                          "group": "parking_default", "account_id": "0", "source": "test",
                          "source_id": "1", "idempotency_key": "1234"}
                     ]}}))
         self.assertEqual(str(e.exception).count("\n"), 2)
         self.assertIn("value must be an integer greater 0", str(e.exception))
 
     def test_cost_entry_group_missing(self):
         with self.assertRaises(ValidationError) as e:
-            parse_setting("common/parksettings", dump_setting({
+            parse_setting("common/parksettings2", dump_setting({
                 "12e8a7e2-be78-488e-8d1a-1486f7da2179": {
                     "id": "12e8a7e2-be78-488e-8d1a-1486f7da2179",
                     "name": "Dauerparker ohne Kosten",
-                    "parking_area_id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac",
+                    "gates": ["gate1"],
                     "default_cost_entries": [
                         {"entry_type": "static_cost", "value": 123,
                          "account_id": "0", "source": "test",
                          "source_id": "1", "idempotency_key": "1234"}
                     ]}}))
         self.assertEqual(str(e.exception).count("\n"), 2)
         self.assertIn("group must be set", str(e.exception))
 
     def test_cost_entry_group_unexpectedly_set(self):
         # entry_type cancel_remaining_costs/payoff_costs
         with self.assertRaises(ValidationError) as e:
-            parse_setting("common/parksettings", dump_setting({
+            parse_setting("common/parksettings2", dump_setting({
                 "12e8a7e2-be78-488e-8d1a-1486f7da2179": {
                     "id": "12e8a7e2-be78-488e-8d1a-1486f7da2179",
                     "name": "Dauerparker ohne Kosten",
-                    "parking_area_id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac",
+                    "gates": ["gate1"],
                     "default_cost_entries": [
                         {"entry_type": "cancel_remaining_costs", "value": 123,
                          "account_id": "0", "source": "test", "group": "parking_default",
                          "source_id": "1", "idempotency_key": "1234"}
                     ]}}))
         self.assertEqual(str(e.exception).count("\n"), 2)
         self.assertIn("group must NOT be set", str(e.exception))
@@ -336,83 +336,112 @@
 
     def test_parking_areas_success(self):
         self.maxDiff = None
         gt = dump_setting({"0eec2445-15c3-4af8-b362-aeb1f278e3ac": {
             "id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac", "default_cost_entries":
                 [{"entry_type": "rate_change", "group": "parking_default",
                   "value": "7a50fafd-3426-42c8-bf3c-ca708638c327", "account_id": "0"}],
-            "gates": None, "name": "Gesamter Parkplatz", "shortterm_allowed": True}
+            "pay_per_use_cost_entries":
+                [{"entry_type": "rate_change", "group": "parking_default",
+                  "value": "7a50fafd-3426-42c8-bf3c-ca708638c327", "account_id": "0"}],
+            "gates": ["gate1"], "name": "Gesamter Parkplatz", "shortterm_gates": [],
+            "shortterm_limit_type": "no_limit", "shortterm_limit": 0}
         })
-        res = parse_setting("common/parking_areas", gt)
+        res = parse_setting("common/parking_areas2", gt)
         self.assert_result(dump_setting(res), gt)
 
     def test_parking_areas_not_a_uuid(self):
         with self.assertRaises(ValidationError) as e:
-            parse_setting("common/parking_areas", dump_setting({
+            parse_setting("common/parking_areas2", dump_setting({
                 "0eec2445-15c3-4af8-b362-aeb1f278e3ac": {
                     "id": "123", "default_cost_entries":
                         [{"entry_type": "rate_change", "group": "parking_default",
                           "value": "7a50fafd-3426-42c8-bf3c-ca708638c327", "account_id": "0"}],
-                    "gates": None, "name": "Gesamter Parkplatz", "shortterm_allowed": True}
+                    "gates": ["gate1"], "name": "Gesamter Parkplatz", "shortterm_gates": [],
+                    "shortterm_limit_type": "no_limit", "shortterm_limit": 0}
             }))
         self.assertEqual(str(e.exception).count("\n"), 2)
         self.assertIn("must be a uuid string", str(e.exception))
 
     def test_parking_areas_id_does_not_match_field(self):
         with self.assertRaises(ValueError) as e:
-            parse_setting("common/parking_areas", dump_setting({
+            parse_setting("common/parking_areas2", dump_setting({
                 "7a50fafd-3426-42c8-bf3c-ca708638c327": {
                     "id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac", "default_cost_entries":
                         [{"entry_type": "rate_change", "group": "parking_default",
                           "value": "7a50fafd-3426-42c8-bf3c-ca708638c327", "account_id": "0"}],
-                    "gates": None, "name": "Gesamter Parkplatz", "shortterm_allowed": True}
+                    "gates": ["gate1"], "name": "Gesamter Parkplatz", "shortterm_gates": [],
+                    "shortterm_limit_type": "no_limit", "shortterm_limit": 0}
             }))
         self.assertEqual(str(e.exception).count("\n"), 0)
         self.assertEqual("key must match field id", str(e.exception))
 
         with self.assertRaises(ValueError) as e:
-            parse_setting("common/parking_areas", dump_setting({
+            parse_setting("common/parking_areas2", dump_setting({
                 "123": {
                     "id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac", "default_cost_entries":
                         [{"entry_type": "rate_change", "group": "parking_default",
                           "value": "7a50fafd-3426-42c8-bf3c-ca708638c327", "account_id": "0"}],
-                    "gates": None, "name": "Gesamter Parkplatz", "shortterm_allowed": True}
+                    "gates": ["gate1"], "name": "Gesamter Parkplatz", "shortterm_gates": [],
+                    "shortterm_limit_type": "no_limit", "shortterm_limit": 0}
             }))
         self.assertEqual(str(e.exception).count("\n"), 0)
         self.assertIn("key must match field id", str(e.exception))
 
     def test_parking_areas_invalid_default_cost_entry_type(self):
         with self.assertRaises(ValidationError) as e:
-            parse_setting("common/parking_areas", dump_setting({
+            parse_setting("common/parking_areas2", dump_setting({
                 "0eec2445-15c3-4af8-b362-aeb1f278e3ac": {
                     "id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac", "default_cost_entries":
                         [{"entry_type": "partial_rate_change", "group": "parking_default",
                           "value": "7a50fafd-3426-42c8-bf3c-ca708638c327", "account_id": "0"}],
-                    "gates": None, "name": "Gesamter Parkplatz", "shortterm_allowed": True}
+                    "gates": ["gate1"], "name": "Gesamter Parkplatz", "shortterm_gates": [],
+                    "shortterm_limit_type": "no_limit", "shortterm_limit": 0}
             }))
         self.assertEqual(str(e.exception).count("\n"), 2)
         self.assertIn("is not allowed as default cost entry in parking area", str(e.exception))
 
-    def test_parking_areas_multiple_global_shortterm(self):
-        with self.assertRaises(ValueError) as e:
-            parse_setting("common/parking_areas", dump_setting({
+    def test_parking_areas_invalid_pay_per_use_cost_entry_type(self):
+        with self.assertRaises(ValidationError) as e:
+            parse_setting("common/parking_areas2", dump_setting({
+                "0eec2445-15c3-4af8-b362-aeb1f278e3ac": {
+                    "id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac", "default_cost_entries": [],
+                    "pay_per_use_cost_entries":
+                        [{"entry_type": "partial_rate_change", "group": "parking_default",
+                          "value": "7a50fafd-3426-42c8-bf3c-ca708638c327", "account_id": "0"}],
+                    "gates": ["gate1"], "name": "Gesamter Parkplatz", "shortterm_gates": [],
+                    "shortterm_limit_type": "no_limit", "shortterm_limit": 0}
+            }))
+        self.assertEqual(str(e.exception).count("\n"), 2)
+        self.assertIn("is not allowed as pay per use cost entry in parking area", str(e.exception))
+
+    def test_parking_areas_shortterm_gates_not_in_gates(self):
+        with self.assertRaises(ValidationError) as e:
+            parse_setting("common/parking_areas2", dump_setting({
                 "0eec2445-15c3-4af8-b362-aeb1f278e3ac": {
                     "id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac", "default_cost_entries":
                         [{"entry_type": "rate_change", "group": "parking_default",
                           "value": "7a50fafd-3426-42c8-bf3c-ca708638c327", "account_id": "0"}],
-                    "gates": None, "name": "Gesamter Parkplatz", "shortterm_allowed": True},
-                "7a50fafd-3426-42c8-bf3c-ca708638c327": {
-                    "id": "7a50fafd-3426-42c8-bf3c-ca708638c327", "default_cost_entries":
+                    "gates": ["gate1"], "name": "Gesamter Parkplatz", "shortterm_gates": ["gate1", "gate2"],
+                    "shortterm_limit_type": "no_limit", "shortterm_limit": 0}
+            }))
+        self.assertEqual(str(e.exception).count("\n"), 2)
+
+        self.assertIn("All shortterm gates must be in gates", str(e.exception))
+        with self.assertRaises(ValidationError) as e:
+            parse_setting("common/parking_areas2", dump_setting({
+                "0eec2445-15c3-4af8-b362-aeb1f278e3ac": {
+                    "id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac", "default_cost_entries":
                         [{"entry_type": "rate_change", "group": "parking_default",
                           "value": "7a50fafd-3426-42c8-bf3c-ca708638c327", "account_id": "0"}],
-                    "gates": ["gate1", "gate2"], "name": "Bereich 1", "shortterm_allowed": True}
+                    "gates": ["gate1"], "name": "Gesamter Parkplatz", "shortterm_gates": ["gate2"],
+                    "shortterm_limit_type": "no_limit", "shortterm_limit": 0}
             }))
-        self.assertEqual(str(e.exception).count("\n"), 0)
-        self.assertEqual("No additional shortterm parking area is allowed if entire parking space is shortterm",
-                         str(e.exception))
+        self.assertEqual(str(e.exception).count("\n"), 2)
+        self.assertIn("All shortterm gates must be in gates", str(e.exception))
 
     def test_timezone_unknown(self):
         parse_setting("common/timezone", dump_setting("Europe/Berlin"))
         with self.assertRaises(ValueError) as e:
             parse_setting("common/timezone", dump_setting("Europe/Graz"))
         self.assertEqual(str(e.exception).count("\n"), 0)
         self.assertEqual("timezone Europe/Graz unknown", str(e.exception))
@@ -492,14 +521,52 @@
         with self.assertRaises(ValidationError) as e:
             parse_setting("common/garage_name", dump_setting({
                 "name": "Test", "slug": "test", "technical_name": "TEST"
             }))
         self.assertEqual(str(e.exception).count("\n"), 2)
         self.assertIn("string does not match regex", str(e.exception))
 
+    def test_garage_settings_freeflow(self):
+        expected_gt = dump_setting({"mode": "freeflow", "honest_payment_enabled": True,
+                                    "enforcement_enabled": True, "payment_possible": True})
+        gt = dump_setting({"mode": "freeflow"})
+        res = parse_setting("common/garage_settings", gt)
+        self.assert_result(dump_setting(res), expected_gt)
+
+        gt = dump_setting({"mode": "freeflow", "honest_payment_enabled": False,
+                           "enforcement_enabled": False, "payment_possible": False})
+        res = parse_setting("common/garage_settings", gt)
+        self.assert_result(dump_setting(res), expected_gt)
+
+    def test_garage_settings_freeflow_surveillance(self):
+        expected_gt = dump_setting({"mode": "freeflow_surveillance", "honest_payment_enabled": False,
+                                    "enforcement_enabled": False, "payment_possible": False})
+
+        gt = dump_setting({"mode": "freeflow_surveillance"})
+        res = parse_setting("common/garage_settings", gt)
+        self.assert_result(dump_setting(res), expected_gt)
+
+        gt = dump_setting({"mode": "freeflow_surveillance", "honest_payment_enabled": True,
+                           "enforcement_enabled": True, "payment_possible": True})
+        res = parse_setting("common/garage_settings", gt)
+        self.assert_result(dump_setting(res), expected_gt)
+
+    def test_garage_settings_barrier(self):
+        expected_gt = dump_setting({"mode": "barrier", "honest_payment_enabled": False,
+                                    "enforcement_enabled": False, "payment_possible": True})
+
+        gt = dump_setting({"mode": "barrier"})
+        res = parse_setting("common/garage_settings", gt)
+        self.assert_result(dump_setting(res), expected_gt)
+
+        gt = dump_setting({"mode": "barrier", "honest_payment_enabled": True,
+                           "enforcement_enabled": True, "payment_possible": False})
+        res = parse_setting("common/garage_settings", gt)
+        self.assert_result(dump_setting(res), expected_gt)
+
     def test_gate_control_day_mode_invalid_format(self):
         # start
         with self.assertRaises(ValidationError) as e:
             parse_setting("gate_control/day_mode", dump_setting({
                 "start": "24", "end": "00:00", "enabled": True
             }))
         self.assertEqual(str(e.exception).count("\n"), 2)
@@ -543,11 +610,11 @@
         self.assertIn("Domains must not have a trailing /", str(e.exception))
 
     def test_custom_type_not_validated(self):
         # id does not match key, but custom type is used
         gt = {"9999a7e2-be78-488e-8d1a-1486f7da9999": {
             "id": "0000a7e2-be78-488e-8d1a-1486f7da0000",
             "name": "Dauerparker ohne Kosten",
-            "parking_area_id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac",
+            "gates": ["gate1"],
             "default_cost_entries": []}}
-        res = parse_setting("common/parksettings", dump_setting(gt), custom_type=Parksettings)
+        res = parse_setting("common/parksettings2", dump_setting(gt), custom_type=Parksettings)
         self.assert_result(res, gt)
```

### Comparing `arivo-settings_models-0.0.1rc1/tests/test_models.py` & `arivo-settings_models-0.0.1rc2/tests/test_models.py`

 * *Files 9% similar despite different names*

```diff
@@ -9,71 +9,68 @@
     def test_gates(self):
         setting_str = '{"gate1":{"gate":"gate1","name":"EF","type":"entry"},' \
                       '"gate2":{"gate":"gate2","name":"AF","type":"exit"}}'
         res = parse_setting("common/gates", setting_str)
         self.assert_result(setting_str, dump_setting(res))
 
     def test_rates(self):
-        setting_str = '{"7a50fafd-3426-42c8-bf3c-ca708638c327":{' \
-                      '"id":"7a50fafd-3426-42c8-bf3c-ca708638c327","name":"Kurzparktarif",' \
-                      '"rate_yaml":"!RateMatrix\\nconstraints: []\\ntables:\\n  - !RateTable\\n    ' \
-                      'active_times: !OverallPeriod \\n      exception_periods: []\\n      ' \
-                      'valid_periods: []\\n    constraints: []\\n    ' \
-                      'id: 186ad735-6bcf-4c0c-9811-32bc8f502e17\\n    name: 3.30€ / Stunde\\n    ' \
-                      'line_collections:\\n      - !RateLineCollection\\n        grace_period: 3m\\n        ' \
-                      'max_value: 2500\\n        reset_duration: 1d\\n        lines:\\n          ' \
-                      '- !RateLine\\n            value: 330\\n            increment_period: 1h\\n"}}'
+        setting_str = ('{"7a50fafd-3426-42c8-bf3c-ca708638c327":{'
+                       '"id":"7a50fafd-3426-42c8-bf3c-ca708638c327","name":"Kurzparktarif",'
+                       '"rate_yaml":"!RateMatrix\\nconstraints: []\\ntables:\\n  - !RateTable\\n    '
+                       'active_times: !OverallPeriod \\n      exception_periods: []\\n      '
+                       'valid_periods: []\\n    constraints: []\\n    '
+                       'id: 186ad735-6bcf-4c0c-9811-32bc8f502e17\\n    name: 3.30€ / Stunde\\n    '
+                       'line_collections:\\n      - !RateLineCollection\\n        grace_period: 3m\\n        '
+                       'max_value: 2500\\n        reset_duration: 1d\\n        lines:\\n          '
+                       '- !RateLine\\n            value: 330\\n            increment_period: 1h\\n"}}')
         res = parse_setting("common/rates", setting_str)
         self.assert_result(setting_str, dump_setting(res))
 
-    def test_parking_areas(self):
-        setting_str = '{"0eec2445-15c3-4af8-b362-aeb1f278e3ac": {"default_cost_entries": ' \
-                      '[{"entry_type": "rate_change", "group": "parking_default", ' \
-                      '"value": "7a50fafd-3426-42c8-bf3c-ca708638c327", "account_id": "0"}], ' \
-                      '"gates": null, "id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac", "name": "Gesamter Parkplatz", ' \
-                      '"shortterm_allowed": true}}'
-        res = parse_setting("common/parking_areas", setting_str)
-        self.assert_result(setting_str, dump_setting(res))
-
-    def test_parksettings(self):
-        setting_str = '{"ae2477d5-702f-4091-b93e-8c2d73c40cd7": {"name": "Dauerparker mit variablen Kosten", ' \
-                      '"id": "ae2477d5-702f-4091-b93e-8c2d73c40cd7", "default_cost_entries": null, ' \
-                      '"parking_area_id": "63981435-8da9-4b8a-98bb-d0fa0e9ef27c"}, ' \
-                      '"654cb72d-545c-48e1-9de7-146528affb6c": {"name": "Dauerparker ohne Kosten", ' \
-                      '"id": "654cb72d-545c-48e1-9de7-146528affb6c", "default_cost_entries": [], ' \
-                      '"parking_area_id": "63981435-8da9-4b8a-98bb-d0fa0e9ef27c"}, ' \
-                      '"70c3f84d-7408-487c-af0c-e41d8fe6c6ac": {"id": "70c3f84d-7408-487c-af0c-e41d8fe6c6ac", ' \
-                      '"name": "Rabattparker", "parking_area_id": "63981435-8da9-4b8a-98bb-d0fa0e9ef27c", ' \
-                      '"default_cost_entries": [{"entry_type": "rate_change", "group": "parking_default", ' \
-                      '"value": "75dadac3-2362-4075-bae1-8a26e06f2d76", "account_id": "0"}]}}'
-        res = parse_setting("common/parksettings", setting_str)
+    def test_parking_areas2(self):
+        setting_str = ('{"0eec2445-15c3-4af8-b362-aeb1f278e3ac": {"default_cost_entries": '
+                       '[{"entry_type": "rate_change", "group": "parking_default", '
+                       '"value": "7a50fafd-3426-42c8-bf3c-ca708638c327", "account_id": "0"}], '
+                       '"gates": ["gate1"], "id": "0eec2445-15c3-4af8-b362-aeb1f278e3ac", '
+                       '"name": "Gesamter Parkplatz", "shortterm_gates": ["gate1"],'
+                       '"shortterm_limit_type": "no_limit", "shortterm_limit": 0}}')
+        res = parse_setting("common/parking_areas2", setting_str)
+        self.assert_result(setting_str, dump_setting(res))
+
+    def test_parksettings2(self):
+        setting_str = ('{"654cb72d-545c-48e1-9de7-146528affb6c": {"name": "Dauerparker ohne Kosten", '
+                       '"id": "654cb72d-545c-48e1-9de7-146528affb6c", "default_cost_entries": [], "gates": ["gate1"]}, '
+                       '"70c3f84d-7408-487c-af0c-e41d8fe6c6ac": {"id": "70c3f84d-7408-487c-af0c-e41d8fe6c6ac", '
+                       '"name": "Rabattparker", "gates": ["gate1", "gate2"], '
+                       '"default_cost_entries": [{"entry_type": "rate_change", "group": "parking_default", '
+                       '"value": "75dadac3-2362-4075-bae1-8a26e06f2d76", "account_id": "0"}]}}')
+        res = parse_setting("common/parksettings2", setting_str)
         self.assert_result(setting_str, dump_setting(res))
 
     def test_privacy_settings(self):
-        setting_str = '{"paid": {"days": 1, "hours": 0, "minutes": 0}, ' \
-                      '"unpaid": {"days": 90, "hours": 0, "minutes": 0}, ' \
-                      '"registered_free": {"days": 30, "hours": 0, "minutes": 0}, ' \
-                      '"pay_via_invoice": {"days": 30, "hours": 0, "minutes": 0}, ' \
-                      '"open": {"days": 90, "hours": 0, "minutes": 0}, ' \
-                      '"free": {"days": 0, "hours": 0, "minutes": 5}, ' \
-                      '"honest_payment": {"days": 90, "hours": 0, "minutes": 0}, ' \
-                      '"erroneous": {"days": 30, "hours": 0, "minutes": 0}, ' \
-                      '"rejected": {"days": 7, "hours": 0, "minutes": 0}}'
+        setting_str = ('{"paid": {"days": 1, "hours": 0, "minutes": 0}, '
+                       '"unpaid": {"days": 90, "hours": 0, "minutes": 0}, '
+                       '"registered_free": {"days": 30, "hours": 0, "minutes": 0}, '
+                       '"pay_via_invoice": {"days": 30, "hours": 0, "minutes": 0}, '
+                       '"open": {"days": 90, "hours": 0, "minutes": 0}, '
+                       '"free": {"days": 0, "hours": 0, "minutes": 5}, '
+                       '"honest_payment": {"days": 90, "hours": 0, "minutes": 0}, '
+                       '"erroneous": {"days": 30, "hours": 0, "minutes": 0}, '
+                       '"rejected": {"days": 7, "hours": 0, "minutes": 0}}')
         res = parse_setting("common/privacy_settings", setting_str)
         self.assert_result(setting_str, dump_setting(res))
 
     def test_cost_groups(self):
-        setting_str = '{"fine_no-ticket": {"account_id": "100", "id": "fine_no-ticket", ' \
-                      '"name": "Strafe: Kein Ticket", "vat_rate": 0}, ' \
-                      '"fine_parking-violation": {"account_id": "101", "id": "fine_parking-violation", ' \
-                      '"name": "Strafe: Unerlaubter Stellplatz", "vat_rate": 0}, ' \
-                      '"honest-payment_default": {"account_id": "300", "id": "honest-payment_default", ' \
-                      '"name": "Ehrliche Zahlung", "vat_rate": 20}, ' \
-                      '"parking_default": {"account_id": "0", "id": "parking_default", "name": ' \
-                      '"Parkkosten", "vat_rate": 20}}'
+        setting_str = ('{"fine_no-ticket": {"account_id": "100", "id": "fine_no-ticket", '
+                       '"name": "Strafe: Kein Ticket", "vat_rate": 0}, '
+                       '"fine_parking-violation": {"account_id": "101", "id": "fine_parking-violation", '
+                       '"name": "Strafe: Unerlaubter Stellplatz", "vat_rate": 0}, '
+                       '"honest-payment_default": {"account_id": "300", "id": "honest-payment_default", '
+                       '"name": "Ehrliche Zahlung", "vat_rate": 20}, '
+                       '"parking_default": {"account_id": "0", "id": "parking_default", "name": '
+                       '"Parkkosten", "vat_rate": 20}}')
         res = parse_setting("common/cost_groups", setting_str)
         self.assert_result(setting_str, dump_setting(res))
 
     def test_currency(self):
         setting_str = '"EUR"'
         res = parse_setting("common/currency", setting_str)
         self.assertEqual(setting_str.encode("utf8"), dump_setting(res))
@@ -85,17 +82,26 @@
 
     def test_timezone(self):
         setting_str = '"Europe/Vienna"'
         res = parse_setting("common/timezone", setting_str)
         self.assertEqual(setting_str.encode("utf8"), dump_setting(res))
 
     def test_garage_settings(self):
-        setting_str = '{"mode": "freeflow", "honest_payment_enabled": true}'
+        setting_str = '{"mode": "freeflow", "honest_payment_enabled": false}'
         res = parse_setting("common/garage_settings", setting_str)
-        self.assert_result(setting_str, dump_setting(res))
+        self.assert_result('{"mode": "freeflow", "honest_payment_enabled": true, "enforcement_enabled": true, '
+                           '"payment_possible": true}', dump_setting(res))
+        setting_str = '{"mode": "freeflow_surveillance"}'
+        res = parse_setting("common/garage_settings", setting_str)
+        self.assert_result('{"mode": "freeflow_surveillance", "honest_payment_enabled": false, '
+                           '"enforcement_enabled": false, "payment_possible": false}', dump_setting(res))
+        setting_str = '{"mode": "barrier"}'
+        res = parse_setting("common/garage_settings", setting_str)
+        self.assert_result('{"mode": "barrier", "honest_payment_enabled": false, "enforcement_enabled": false, '
+                           '"payment_possible": true}', dump_setting(res))
 
     def test_location(self):
         setting_str = '{"name": "Garage", "street": "Garagestreet", "number": "12c", "floor": "2H", "door": "7a", ' \
                       '"supplements": "Frag nach Ines", "city": "Graz", "zip_code": "8020", "state": "Styria", ' \
                       '"country": "Österreich", "longitude": 15.441016366426302, "latitude": 47.041677687836156}'
         res = parse_setting("common/location", setting_str)
         self.assert_result(setting_str, dump_setting(res))
```

### Comparing `arivo-settings_models-0.0.1rc1/tests/utils.py` & `arivo-settings_models-0.0.1rc2/tests/utils.py`

 * *Files identical despite different names*

### Comparing `arivo-settings_models-0.0.1rc1/ChangeLog` & `arivo-settings_models-0.0.1rc2/ChangeLog`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,17 @@
 CHANGES
 =======
 
+v0.0.1rc2
+---------
+
+* fixes and full test coverage
+* validation for shortterm gates
+* changes in parking areas, parksettings and GarageSettings
+
 v0.0.1rc1
 ---------
 
 * marked gate\_control/day\_mode as unscoped
 
 v0.0.1rc0
 ---------
```

### Comparing `arivo-settings_models-0.0.1rc1/arivo_settings_models.egg-info/PKG-INFO` & `arivo-settings_models-0.0.1rc2/arivo_settings_models.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 1.1
 Name: arivo-settings-models
-Version: 0.0.1rc1
+Version: 0.0.1rc2
 Summary: Library for arivo parking system settings definitions and models
 Home-page: https://gitlab.com/accessio/onegate/settings-models
 Author: ARIVO
 Author-email: support@arivo.co
 License: "GPL-3",
 Description: # Settings Models
```

### Comparing `arivo-settings_models-0.0.1rc1/arivo_settings_models.egg-info/SOURCES.txt` & `arivo-settings_models-0.0.1rc2/arivo_settings_models.egg-info/SOURCES.txt`

 * *Files identical despite different names*

