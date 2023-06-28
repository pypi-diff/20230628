# Comparing `tmp/fastapi_orm_manager-0.0.1.tar.gz` & `tmp/fastapi_orm_manager-0.0.2.tar.gz`

## Comparing `fastapi_orm_manager-0.0.1.tar` & `fastapi_orm_manager-0.0.2.tar`

### file list

```diff
@@ -1,18 +1,18 @@
--rw-r--r--   0        0        0       35 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/requirements.txt
--rw-r--r--   0        0        0      176 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/.idea/.gitignore
--rw-r--r--   0        0        0      206 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/.idea/misc.xml
--rw-r--r--   0        0        0      288 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/.idea/modules.xml
--rw-r--r--   0        0        0      338 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/.idea/sqlalchemy_manager.iml
--rw-r--r--   0        0        0      167 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/.idea/vcs.xml
--rw-r--r--   0        0        0     4978 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/.idea/workspace.xml
--rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/.idea/inspectionProfiles/Project_Default.xml
--rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/.idea/inspectionProfiles/profiles_settings.xml
--rw-r--r--   0        0        0       70 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/fastapi_manager/__init__.py
--rw-r--r--   0        0        0      713 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/fastapi_manager/decorators.py
--rw-r--r--   0        0        0     2510 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/fastapi_manager/managers.py
--rw-r--r--   0        0        0      513 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/fastapi_manager/meta.py
--rw-r--r--   0        0        0       11 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/.gitignore
--rw-r--r--   0        0        0     1073 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/LICENSE
--rw-r--r--   0        0        0      130 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/README.md
--rw-r--r--   0        0        0      663 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/pyproject.toml
--rw-r--r--   0        0        0      733 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.1/PKG-INFO
+-rw-r--r--   0        0        0       35 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/requirements.txt
+-rw-r--r--   0        0        0      176 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/.gitignore
+-rw-r--r--   0        0        0      206 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/misc.xml
+-rw-r--r--   0        0        0      288 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/modules.xml
+-rw-r--r--   0        0        0      338 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/sqlalchemy_manager.iml
+-rw-r--r--   0        0        0      167 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/vcs.xml
+-rw-r--r--   0        0        0     4997 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/workspace.xml
+-rw-r--r--   0        0        0     4741 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/inspectionProfiles/Project_Default.xml
+-rw-r--r--   0        0        0      174 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.idea/inspectionProfiles/profiles_settings.xml
+-rw-r--r--   0        0        0       70 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/fastapi_manager/__init__.py
+-rw-r--r--   0        0        0      713 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/fastapi_manager/decorators.py
+-rw-r--r--   0        0        0     2437 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/fastapi_manager/managers.py
+-rw-r--r--   0        0        0      513 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/fastapi_manager/meta.py
+-rw-r--r--   0        0        0     3077 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/.gitignore
+-rw-r--r--   0        0        0     1073 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/LICENSE
+-rw-r--r--   0        0        0      130 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/README.md
+-rw-r--r--   0        0        0      730 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/pyproject.toml
+-rw-r--r--   0        0        0      796 2020-02-02 00:00:00.000000 fastapi_orm_manager-0.0.2/PKG-INFO
```

### Comparing `fastapi_orm_manager-0.0.1/.idea/workspace.xml` & `fastapi_orm_manager-0.0.2/.idea/workspace.xml`

 * *Files 6% similar despite different names*

#### Comparing `fastapi_orm_manager-0.0.1/.idea/workspace.xml` & `fastapi_orm_manager-0.0.2/.idea/workspace.xml`

```diff
@@ -2,14 +2,15 @@
 <project version="4">
   <component name="AutoImportSettings">
     <option name="autoReloadType" value="SELECTIVE"/>
   </component>
   <component name="ChangeListManager">
     <list default="true" id="ce161eba-d1fe-4cab-9a80-9296ac460fb7" name="Changes" comment="">
       <change afterPath="$PROJECT_DIR$/.gitignore" afterDir="false"/>
+      <change afterPath="$PROJECT_DIR$/LICENSE" afterDir="false"/>
       <change afterPath="$PROJECT_DIR$/README.md" afterDir="false"/>
       <change afterPath="$PROJECT_DIR$/fastapi_manager/__init__.py" afterDir="false"/>
       <change afterPath="$PROJECT_DIR$/fastapi_manager/decorators.py" afterDir="false"/>
       <change afterPath="$PROJECT_DIR$/fastapi_manager/managers.py" afterDir="false"/>
       <change afterPath="$PROJECT_DIR$/fastapi_manager/meta.py" afterDir="false"/>
       <change afterPath="$PROJECT_DIR$/pyproject.toml" afterDir="false"/>
       <change afterPath="$PROJECT_DIR$/requirements.txt" afterDir="false"/>
@@ -25,38 +26,42 @@
         <option value="Python Script"/>
       </list>
     </option>
   </component>
   <component name="Git.Settings">
     <option name="RECENT_GIT_ROOT_PATH" value="$PROJECT_DIR$"/>
   </component>
+  <component name="MarkdownSettingsMigration">
+    <option name="stateVersion" value="1"/>
+  </component>
   <component name="OptimizeOnSaveOptions">
     <option name="myRunOnSave" value="true"/>
   </component>
   <component name="ProjectId" id="2RnZwfNM6OCOCh13tWZg5ENVSuh"/>
   <component name="ProjectViewState">
     <option name="autoscrollFromSource" value="true"/>
     <option name="autoscrollToSource" value="true"/>
     <option name="hideEmptyMiddlePackages" value="true"/>
     <option name="showLibraryContents" value="true"/>
   </component>
-  <component name="PropertiesComponent">{
-  &quot;keyToString&quot;: {
-    &quot;RunOnceActivity.OpenProjectViewOnStart&quot;: &quot;true&quot;,
-    &quot;RunOnceActivity.ShowReadmeOnStart&quot;: &quot;true&quot;,
-    &quot;WebServerToolWindowFactoryState&quot;: &quot;false&quot;,
-    &quot;git-widget-placeholder&quot;: &quot;main&quot;,
-    &quot;node.js.detected.package.eslint&quot;: &quot;true&quot;,
-    &quot;node.js.detected.package.tslint&quot;: &quot;true&quot;,
-    &quot;node.js.selected.package.eslint&quot;: &quot;(autodetect)&quot;,
-    &quot;node.js.selected.package.tslint&quot;: &quot;(autodetect)&quot;,
-    &quot;settings.editor.selected.configurable&quot;: &quot;preferences.sourceCode&quot;,
-    &quot;vue.rearranger.settings.migration&quot;: &quot;true&quot;
+  <component name="PropertiesComponent"><![CDATA[{
+  "keyToString": {
+    "RunOnceActivity.OpenProjectViewOnStart": "true",
+    "RunOnceActivity.ShowReadmeOnStart": "true",
+    "WebServerToolWindowFactoryState": "false",
+    "git-widget-placeholder": "main",
+    "node.js.detected.package.eslint": "true",
+    "node.js.detected.package.tslint": "true",
+    "node.js.selected.package.eslint": "(autodetect)",
+    "node.js.selected.package.tslint": "(autodetect)",
+    "nodejs_package_manager_path": "npm",
+    "settings.editor.selected.configurable": "preferences.sourceCode",
+    "vue.rearranger.settings.migration": "true"
   }
-}</component>
+}]]></component>
   <component name="RecentsManager">
     <key name="MoveFile.RECENT_KEYS">
       <recent name="$PROJECT_DIR$/fastapi_manager"/>
     </key>
   </component>
   <component name="RunManager">
     <configuration name="main" type="PythonConfigurationType" factoryName="Python" nameIsGenerated="true">
@@ -89,15 +94,15 @@
       <created>1687888046904</created>
       <option name="number" value="Default"/>
       <option name="presentableId" value="Default"/>
       <updated>1687888046904</updated>
       <workItem from="1687888048319" duration="1312000"/>
       <workItem from="1687889475147" duration="17000"/>
       <workItem from="1687890160329" duration="4729000"/>
-      <workItem from="1687954925025" duration="2331000"/>
+      <workItem from="1687954925025" duration="4250000"/>
     </task>
     <servers/>
   </component>
   <component name="TypeScriptGeneratedFilesManager">
     <option name="version" value="3"/>
   </component>
 </project>
```

### Comparing `fastapi_orm_manager-0.0.1/.idea/inspectionProfiles/Project_Default.xml` & `fastapi_orm_manager-0.0.2/.idea/inspectionProfiles/Project_Default.xml`

 * *Files identical despite different names*

### Comparing `fastapi_orm_manager-0.0.1/fastapi_manager/decorators.py` & `fastapi_orm_manager-0.0.2/fastapi_manager/decorators.py`

 * *Files identical despite different names*

### Comparing `fastapi_orm_manager-0.0.1/fastapi_manager/managers.py` & `fastapi_orm_manager-0.0.2/fastapi_manager/managers.py`

 * *Files 11% similar despite different names*

```diff
@@ -10,58 +10,58 @@
 
 T = TypeVar('T')
 
 
 class BaseManager(metaclass=SQLAlchemyErrorHandlerMeta):
     model: Type[T] = None
 
-    class Filters(BaseModel):
+    class Params(BaseModel):
         pass
 
     @classmethod
     def add(cls, session: Session, instance: T):
         session.add(instance)
         session.commit()
 
     @classmethod
     async def async_add(cls, session: AsyncSession, instance: T):
         session.add(instance)
         await session.commit()
 
     @classmethod
-    def get(cls, session: Session, filters: Filters) -> T:
-        statement = select(cls.model).filter_by(**filters.dict(exclude_none=True))
+    def get(cls, session: Session, **kwargs) -> T:
+        statement = select(cls.model).filter_by(**kwargs)
 
         item = session.execute(statement)
 
         try:
             return item.scalar()
         except NoResultFound:
             return None
 
     @classmethod
-    async def async_get(cls, session: AsyncSession, filters: Filters) -> T:
-        statement = select(cls.model).filter_by(**filters.dict(exclude_none=True))
+    async def async_get(cls, session: AsyncSession, **kwargs) -> T:
+        statement = select(cls.model).filter_by(**kwargs)
         item = await session.execute(statement)
 
         try:
             return item.scalar()
         except NoResultFound:
             return None
 
     @classmethod
-    def search(cls, session: Session, filters: Filters) -> [T]:
-        statement = select(cls.model).filter_by(**filters.dict(exclude_none=True))
+    def search(cls, session: Session, params: Params) -> [T]:
+        statement = select(cls.model).filter_by(**params.dict(exclude_none=True))
 
         items = session.execute(statement)
         return items.scalars().all()
 
     @classmethod
-    async def async_search(cls, session: AsyncSession, filters: Filters) -> [T]:
-        statement = select(cls.model).filter_by(**filters.dict(exclude_none=True))
+    async def async_search(cls, session: AsyncSession, params: Params) -> [T]:
+        statement = select(cls.model).filter_by(**params.dict(exclude_none=True))
 
         items = await session.execute(statement)
         return items.scalars().all()
 
     @classmethod
     def update(cls, session: Session, instance: T, **kwargs):
         for key, value in kwargs.items():
```

### Comparing `fastapi_orm_manager-0.0.1/fastapi_manager/meta.py` & `fastapi_orm_manager-0.0.2/fastapi_manager/meta.py`

 * *Files identical despite different names*

### Comparing `fastapi_orm_manager-0.0.1/LICENSE` & `fastapi_orm_manager-0.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `fastapi_orm_manager-0.0.1/PKG-INFO` & `fastapi_orm_manager-0.0.2/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,17 +1,19 @@
 Metadata-Version: 2.1
 Name: fastapi-orm-manager
-Version: 0.0.1
+Version: 0.0.2
 Summary: A base manager class to handle CRUD on SQLAlchemy models. Suitable to use in FastAPI projects.
 Project-URL: Homepage, https://github.com/nakeeon/FastAPI-ORM-Manager
 Project-URL: Bug Tracker, https://github.com/nakeeon/FastAPI-ORM-Manager/issues
 Author-email: Nazar Kaliuzhnyi <kaluzghnyy@gmail.com>
 License-File: LICENSE
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3.7
+Requires-Dist: pydantic>=1.10.9
+Requires-Dist: sqlalchemy>=1.4
 Description-Content-Type: text/markdown
 
 # FastAPI ORM Manager
 
 A base manager class to easily create managers for SQLAlchemy models. Suitable to use in FastAPI projects.
```

