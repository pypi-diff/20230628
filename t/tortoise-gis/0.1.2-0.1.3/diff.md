# Comparing `tmp/tortoise-gis-0.1.2.tar.gz` & `tmp/tortoise_gis-0.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tortoise-gis-0.1.2.tar", last modified: Sun Oct  4 00:27:40 2020, max compression
+gzip compressed data, was "tortoise_gis-0.1.3.tar", max compression
```

## Comparing `tortoise-gis-0.1.2.tar` & `tortoise_gis-0.1.3.tar`

### file list

```diff
@@ -1,9 +1,16 @@
--rw-r--r--   0        0        0     1101 2020-09-21 05:45:20.695415 tortoise-gis-0.1.2/LICENSE
--rw-r--r--   0        0        0      387 2020-09-21 05:45:20.695415 tortoise-gis-0.1.2/README.md
--rw-r--r--   0        0        0      957 2020-10-04 00:23:27.657461 tortoise-gis-0.1.2/pyproject.toml
--rw-r--r--   0        0        0        0 2020-09-21 05:45:20.695415 tortoise-gis-0.1.2/src/tortoise_gis/__init__.py
--rw-r--r--   0        0        0      538 2020-10-03 22:07:17.940000 tortoise-gis-0.1.2/src/tortoise_gis/_base_functions.py
--rw-r--r--   0        0        0     6124 2020-10-03 21:48:36.850000 tortoise-gis-0.1.2/src/tortoise_gis/fields.py
--rw-r--r--   0        0        0      317 2020-10-03 22:07:12.960000 tortoise-gis-0.1.2/src/tortoise_gis/functions.py
--rw-r--r--   0        0        0     1186 2020-10-04 00:27:40.691736 tortoise-gis-0.1.2/setup.py
--rw-r--r--   0        0        0     1123 2020-10-04 00:27:40.692072 tortoise-gis-0.1.2/PKG-INFO
+-rw-r--r--   0        0        0     1101 2023-06-20 21:10:15.017730 tortoise_gis-0.1.3/LICENSE
+-rw-r--r--   0        0        0      362 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/README.md
+-rw-r--r--   0        0        0      933 2023-06-27 21:57:57.520748 tortoise_gis-0.1.3/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/tortoise_gis/__init__.py
+-rw-r--r--   0        0        0    11500 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/tortoise_gis/_pypika_functions.py
+-rw-r--r--   0        0        0      749 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/tortoise_gis/fields/__init__.py
+-rw-r--r--   0        0        0      644 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/tortoise_gis/fields/geometry_collection_field.py
+-rw-r--r--   0        0        0     5675 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/tortoise_gis/fields/geometry_field.py
+-rw-r--r--   0        0        0      479 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/tortoise_gis/fields/line_string_field.py
+-rw-r--r--   0        0        0      518 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/tortoise_gis/fields/multi_line_string_field.py
+-rw-r--r--   0        0        0      449 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/tortoise_gis/fields/multi_point_field.py
+-rw-r--r--   0        0        0      491 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/tortoise_gis/fields/multi_polygon_field.py
+-rw-r--r--   0        0        0      405 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/tortoise_gis/fields/point_field.py
+-rw-r--r--   0        0        0      515 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/tortoise_gis/fields/polygon_field.py
+-rw-r--r--   0        0        0     6752 2023-06-27 21:57:27.208512 tortoise_gis-0.1.3/tortoise_gis/functions.py
+-rw-r--r--   0        0        0     1249 1970-01-01 00:00:00.000000 tortoise_gis-0.1.3/PKG-INFO
```

### Comparing `tortoise-gis-0.1.2/LICENSE` & `tortoise_gis-0.1.3/LICENSE`

 * *Files identical despite different names*

### Comparing `tortoise-gis-0.1.2/pyproject.toml` & `tortoise_gis-0.1.3/pyproject.toml`

 * *Files 10% similar despite different names*

```diff
@@ -1,35 +1,36 @@
 [tool.poetry]
 name = "tortoise-gis"
-version = "0.1.2"
+version = "0.1.3"
 description = "Geometrical and Geographical support for Tortoise ORM."
 authors = ["Eduardo Rezende <eduardorbr7@gmail.com>"]
 license = "MIT"
 readme = "README.md"
 homepage = "https://github.com/revensky/tortoise-gis"
 repository = "https://github.com/revensky/tortoise-gis.git"
 keywords = ["Tortoise", "GIS"]
 classifiers = [
     "Development Status :: 3 - Alpha",
     "Programming Language :: Python :: 3",
     "License :: OSI Approved :: MIT License",
     "Operating System :: OS Independent",
 ]
-packages = [{ include = "tortoise_gis", from = "src" }]
+packages = [{ include = "tortoise_gis" }]
 
 [tool.poetry.dependencies]
 python = "^3.8"
-tortoise-orm = "^0.16.14"
-shapely = "^1.7.1"
+tortoise-orm = "^0.19.3"
+shapely = "^2.0.1"
 
-[tool.poetry.dev-dependencies]
-pylint = "^2.6.0"
-black = "^20.8b1"
-asyncpg = "^0.21.0"
-python-dotenv = "^0.14.0"
-sphinx = "^3.2.1"
-sphinx_rtd_theme = "^0.5.0"
-rstcheck = "^3.3.1"
+[tool.poetry.group.dev.dependencies]
+pylint = "^2.17.4"
+black = "^23.3.0"
+asyncpg = "^0.27.0"
+python-dotenv = "^1.0.0"
+rstcheck = "^6.1.2"
+
+[tool.isort]
+profile = "black"
 
 [build-system]
-requires = ["poetry>=1.0.10"]
+requires = ["poetry>=1.5.0"]
 build-backend = "poetry.masonry.api"
```

### Comparing `tortoise-gis-0.1.2/src/tortoise_gis/fields.py` & `tortoise_gis-0.1.3/tortoise_gis/fields/geometry_field.py`

 * *Files 26% similar despite different names*

```diff
@@ -1,28 +1,22 @@
-from typing import Any, Type, Union
-
-import shapely.wkb
-import shapely.wkt
-from tortoise import Model
+from shapely.errors import ShapelyError
+from shapely.geometry.base import BaseGeometry
+from shapely.wkb import dumps as shapely_wkb_dumps, loads as shapely_wkb_loads
+from shapely.wkt import loads as shapely_wkt_loads
 from tortoise.exceptions import FieldError, OperationalError
 from tortoise.fields import Field
-from shapely.errors import WKBReadingError, WKTReadingError
-from shapely.geometry import (
-    GeometryCollection,
-    LineString,
-    MultiPoint,
-    MultiLineString,
-    MultiPolygon,
-    Point,
-    Polygon,
-)
-from shapely.geometry.base import BaseGeometry
+from tortoise.models import Model
+from tortoise.validators import Validator
+from typing import Any, Callable, List, Optional, Type, TypeVar, Union
+
+
+T = TypeVar("T", bound=BaseGeometry)
 
 
-class GeometryField(Field):
+class GeometryField(Field[T]):
     """
     Base Geometry Field.
 
     To save a data to the database, it **MUST** be either a string containing
     its Well-Known Text (WKT) value or a Shapely Geometry instance.
 
     Columns defined with restrictions, such as :class:`PointField`, will **ONLY** accept
@@ -47,175 +41,124 @@
         the values belong to the application.
     :type srid: int
 
     :param spatial_index: Defines whether the column will have a Spatial Index.
         This index is created by defining an index using *GIST* on the column.
         The default is True.
     :type spatial_index: bool
+
+    :param source_field: Provide a source_field name if the DB column name needs to be
+        something specific instead of generated off the field name.
+
+    :param generated: Is this field DB-generated?
+
+    :param pk: Is this field a Primary Key? Can only have a single such field on the Model,
+        and if none is specified it will autogenerate a default primary key called ``id``.
+
+    :param null: Is this field nullable?
+
+    :param default: A default value for the field if not specified on Model creation.
+        This can also be a callable for dynamic defaults in which case we will call it.
+        The default value will not be part of the schema.
+
+    :param unique: Is this field unique?
+
+    :param index: Should this field be indexed by itself?
+
+    :param description: Field description. Will also appear in ``Tortoise.describe_model()``
+        and as DB comments in the generated DDL.
+
+    :param validators: Validators for this field.
     """
 
     SQL_TYPE: str = "GEOMETRY"
 
     def __init__(
         self,
-        srid: int = None,
+        srid: Optional[int] = None,
         spatial_index: bool = True,
+        source_field: Optional[str] = None,
+        generated: bool = False,
+        pk: bool = False,
+        null: bool = False,
+        default: Any = None,
+        unique: bool = False,
+        index: bool = False,
+        description: Optional[str] = None,
+        model: Optional[Model] = None,
+        validators: Optional[List[Union[Validator, Callable]]] = None,
         **kwargs: Any,
     ) -> None:
         self.srid = srid
         self.spatial_index = spatial_index
-        super().__init__(**kwargs)
+
+        super().__init__(
+            source_field,
+            generated,
+            pk,
+            null,
+            default,
+            unique,
+            index,
+            description,
+            model,
+            validators,
+            **kwargs,
+        )
 
     def to_db_value(
-        self,
-        value: BaseGeometry,
-        instance: Union[Type[Model], Model],
-    ) -> str:
+        self, value: Optional[Union[T, str, bytes]], instance: Union[Type[Model], Model]
+    ) -> Optional[str]:
+        """
+        Converts from the Python type to the DB type.
+
+        :param value: Current python value in model.
+        :param instance: Model class or Model instance provided to look up.
+        """
+
         if value is None:
             return value
 
-        if not isinstance(value, BaseGeometry):
-            raise FieldError("The value to be saved must be a Shapely geometry.")
+        if not isinstance(value, (BaseGeometry, str, bytes)):
+            raise FieldError(
+                'The value to be saved must be one of ["BaseGeometry", "str", "bytes"].'
+            )
 
-        return shapely.wkb.dumps(value, hex=True, srid=self.srid)
+        if isinstance(value, str):
+            return value
+
+        if isinstance(value, bytes):
+            return value.hex()
+
+        return shapely_wkb_dumps(value, hex=True, srid=self.srid)
+
+    def to_python_value(self, value: Optional[Union[T, str, bytes]]) -> Optional[T]:
+        """
+        Converts from the DB type to the Python type.
+
+        :param value: Value from DB
+        """
 
-    def to_python_value(self, value: Any) -> BaseGeometry:
         if value is None or isinstance(value, BaseGeometry):
             return value
 
-        if not isinstance(value, (bytes, str)):
-            raise FieldError(f'Invalid type: "{type(value)}", expected "bytes or str".')
+        if not isinstance(value, (str, bytes)):
+            raise FieldError(f'Invalid type: "{type(value)}", expected "str or bytes".')
 
         if isinstance(value, bytes):
             try:
-                return shapely.wkb.loads(value)
-            except WKBReadingError as exc:
+                return shapely_wkb_loads(value)
+            except ShapelyError as exc:
                 raise OperationalError("Could not parse the provided data.") from exc
 
         try:
             int(value, 16)  # Prevents "ParseException: Invalid HEX char."
-            return shapely.wkb.loads(value, hex=True)
-        except (ValueError, WKBReadingError):
+            return shapely_wkb_loads(value, hex=True)
+        except (ValueError, ShapelyError):
             pass
 
         try:
-            return shapely.wkt.loads(value)
-        except WKTReadingError:
+            return shapely_wkt_loads(value)
+        except ShapelyError:
             pass
 
         raise OperationalError("Could not parse the provided data.")
-
-
-class PointField(GeometryField):
-    """
-    Point field.
-
-    This field is used to save points in the format (longitude, latitude).
-    """
-
-    field_type = Point
-
-    @property
-    def SQL_TYPE(self) -> str:
-        return f"GEOMETRY(POINT,{self.srid})" if self.srid else "GEOMETRY(POINT)"
-
-
-class LineStringField(GeometryField):
-    """
-    LineString field.
-
-    This field is used to save a line. It takes a collection of at least two points.
-    """
-
-    field_type = LineString
-
-    @property
-    def SQL_TYPE(self) -> str:
-        return (
-            f"GEOMETRY(LINESTRING,{self.srid})" if self.srid else "GEOMETRY(LINESTRING)"
-        )
-
-
-class PolygonField(GeometryField):
-    """
-    Polygon field.
-
-    This field is used to save a polygon. It takes at least three points to create
-    a polygon. The polygon can have one shell and one or more holes inside the shell.
-    """
-
-    field_type = Polygon
-
-    @property
-    def SQL_TYPE(self) -> str:
-        return f"GEOMETRY(POLYGON,{self.srid})" if self.srid else "GEOMETRY(POLYGON)"
-
-
-class MultiPointField(GeometryField):
-    """
-    MultiPoint field.
-
-    This field is used to save a collection of points.
-    """
-
-    field_type = MultiPoint
-
-    @property
-    def SQL_TYPE(self) -> str:
-        return (
-            f"GEOMETRY(MULTIPOINT,{self.srid})" if self.srid else "GEOMETRY(MULTIPOINT)"
-        )
-
-
-class MultiLineStringField(GeometryField):
-    """
-    MultiLineString field.
-
-    This field is used to save a collection of linestrings.
-    """
-
-    field_type = MultiLineString
-
-    @property
-    def SQL_TYPE(self) -> str:
-        return (
-            f"GEOMETRY(MULTILINESTRING,{self.srid})"
-            if self.srid
-            else "GEOMETRY(MULTILINESTRING)"
-        )
-
-
-class MultiPolygonField(GeometryField):
-    """
-    MultiPolygon field.
-
-    This field is used to save a collection of polygons.
-    """
-
-    field_type = MultiPolygon
-
-    @property
-    def SQL_TYPE(self) -> str:
-        return (
-            f"GEOMETRY(MULTIPOLYGON,{self.srid})"
-            if self.srid
-            else "GEOMETRY(MULTIPOLYGON)"
-        )
-
-
-class GeometryCollectionField(GeometryField):
-    """
-    GeometryCollection field.
-
-    This field is used to save a collection of geometries and/or multi-geometries.
-    Note that it does not restrict the type of geometry or multi-geometry it supports.
-    """
-
-    field_type = GeometryCollection
-
-    @property
-    def SQL_TYPE(self) -> str:
-        return (
-            f"GEOMETRY(GEOMETRYCOLLECTION,{self.srid})"
-            if self.srid
-            else "GEOMETRY(GEOMETRYCOLLECTION)"
-        )
```

### Comparing `tortoise-gis-0.1.2/PKG-INFO` & `tortoise_gis-0.1.3/PKG-INFO`

 * *Files 16% similar despite different names*

```diff
@@ -1,37 +1,39 @@
 Metadata-Version: 2.1
 Name: tortoise-gis
-Version: 0.1.2
+Version: 0.1.3
 Summary: Geometrical and Geographical support for Tortoise ORM.
 Home-page: https://github.com/revensky/tortoise-gis
 License: MIT
 Keywords: Tortoise,GIS
 Author: Eduardo Rezende
 Author-email: eduardorbr7@gmail.com
 Requires-Python: >=3.8,<4.0
 Classifier: Development Status :: 3 - Alpha
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
-Requires-Dist: shapely (>=1.7.1,<2.0.0)
-Requires-Dist: tortoise-orm (>=0.16.14,<0.17.0)
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Requires-Dist: shapely (>=2.0.1,<3.0.0)
+Requires-Dist: tortoise-orm (>=0.19.3,<0.20.0)
 Project-URL: Repository, https://github.com/revensky/tortoise-gis.git
 Description-Content-Type: text/markdown
 
 # Tortoise ORM GIS
 
 This package is intended to provide support for GIS Operations to Tortoise ORM.
 
 Currently it only supports PostGIS and **IS NOT** production ready.
 
 Roadmap:
 
--   [] Support Geometry
+-   [X] Support Geometry
 -   [] Support Geography
--   [] Support SpatiaLite
 
 # License
 
 This project is licensed under MIT license.
 For more information, please refer to the `LICENSE` file of the repository.
```

