# Comparing `tmp/wxee-0.4.0.tar.gz` & `tmp/wxee-0.4.1.tar.gz`

## Comparing `wxee-0.4.0.tar` & `wxee-0.4.1.tar`

### file list

```diff
@@ -1,17 +1,17 @@
--rw-r--r--   0        0        0      189 2020-02-02 00:00:00.000000 wxee-0.4.0/wxee/__init__.py
--rw-r--r--   0        0        0      737 2020-02-02 00:00:00.000000 wxee-0.4.0/wxee/accessors.py
--rw-r--r--   0        0        0     2187 2020-02-02 00:00:00.000000 wxee-0.4.0/wxee/climatology.py
--rw-r--r--   0        0        0     9487 2020-02-02 00:00:00.000000 wxee-0.4.0/wxee/collection.py
--rw-r--r--   0        0        0       24 2020-02-02 00:00:00.000000 wxee-0.4.0/wxee/constants.py
--rw-r--r--   0        0        0      210 2020-02-02 00:00:00.000000 wxee-0.4.0/wxee/exceptions.py
--rw-r--r--   0        0        0    11403 2020-02-02 00:00:00.000000 wxee-0.4.0/wxee/image.py
--rw-r--r--   0        0        0     1197 2020-02-02 00:00:00.000000 wxee-0.4.0/wxee/interpolation.py
--rw-r--r--   0        0        0      968 2020-02-02 00:00:00.000000 wxee-0.4.0/wxee/params.py
--rw-r--r--   0        0        0    35987 2020-02-02 00:00:00.000000 wxee-0.4.0/wxee/time_series.py
--rw-r--r--   0        0        0     7884 2020-02-02 00:00:00.000000 wxee-0.4.0/wxee/utils.py
--rw-r--r--   0        0        0     4871 2020-02-02 00:00:00.000000 wxee-0.4.0/wxee/xarray.py
--rw-r--r--   0        0        0      167 2020-02-02 00:00:00.000000 wxee-0.4.0/.gitignore
--rw-r--r--   0        0        0     1068 2020-02-02 00:00:00.000000 wxee-0.4.0/LICENSE
--rw-r--r--   0        0        0     6052 2020-02-02 00:00:00.000000 wxee-0.4.0/README.rst
--rw-r--r--   0        0        0     2349 2020-02-02 00:00:00.000000 wxee-0.4.0/pyproject.toml
--rw-r--r--   0        0        0     8134 2020-02-02 00:00:00.000000 wxee-0.4.0/PKG-INFO
+-rw-r--r--   0        0        0      196 2020-02-02 00:00:00.000000 wxee-0.4.1/wxee/__init__.py
+-rw-r--r--   0        0        0      770 2020-02-02 00:00:00.000000 wxee-0.4.1/wxee/accessors.py
+-rw-r--r--   0        0        0     2253 2020-02-02 00:00:00.000000 wxee-0.4.1/wxee/climatology.py
+-rw-r--r--   0        0        0     9732 2020-02-02 00:00:00.000000 wxee-0.4.1/wxee/collection.py
+-rw-r--r--   0        0        0       25 2020-02-02 00:00:00.000000 wxee-0.4.1/wxee/constants.py
+-rw-r--r--   0        0        0      220 2020-02-02 00:00:00.000000 wxee-0.4.1/wxee/exceptions.py
+-rw-r--r--   0        0        0    11693 2020-02-02 00:00:00.000000 wxee-0.4.1/wxee/image.py
+-rw-r--r--   0        0        0     1235 2020-02-02 00:00:00.000000 wxee-0.4.1/wxee/interpolation.py
+-rw-r--r--   0        0        0     1000 2020-02-02 00:00:00.000000 wxee-0.4.1/wxee/params.py
+-rw-r--r--   0        0        0    36841 2020-02-02 00:00:00.000000 wxee-0.4.1/wxee/time_series.py
+-rw-r--r--   0        0        0     8452 2020-02-02 00:00:00.000000 wxee-0.4.1/wxee/utils.py
+-rw-r--r--   0        0        0     5007 2020-02-02 00:00:00.000000 wxee-0.4.1/wxee/xarray.py
+-rw-r--r--   0        0        0      180 2020-02-02 00:00:00.000000 wxee-0.4.1/.gitignore
+-rw-r--r--   0        0        0     1088 2020-02-02 00:00:00.000000 wxee-0.4.1/LICENSE
+-rw-r--r--   0        0        0     6225 2020-02-02 00:00:00.000000 wxee-0.4.1/README.rst
+-rw-r--r--   0        0        0     1961 2020-02-02 00:00:00.000000 wxee-0.4.1/pyproject.toml
+-rw-r--r--   0        0        0     7025 2020-02-02 00:00:00.000000 wxee-0.4.1/PKG-INFO
```

### Comparing `wxee-0.4.0/wxee/accessors.py` & `wxee-0.4.1/wxee/accessors.py`

 * *Ordering differences only*

 * *Files 24% similar despite different names*

```diff
@@ -1,33 +1,33 @@
-from typing import Any, Callable, Type
-
-
-class Accessor:
-    """Object for implementing class accessors."""
-
-    def __init__(self, name: str, accessor: Any):
-        self.name = name
-        self.accessor = accessor
-
-    def __get__(self, obj: Any, cls: Type) -> Any:
-        return self.accessor(obj)
-
-
-def wx_accessor(cls: Type) -> Callable:
-    """Create an accessor through the wx namespace to a given class.
-
-    Parameters
-    ----------
-    cls : class
-        The class to set the accessor to.
-
-    Returns
-    -------
-    function
-        The accessor function to to the class.
-    """
-
-    def decorator(accessor: Any) -> Any:
-        setattr(cls, "wx", Accessor("wx", accessor))
-        return accessor
-
-    return decorator
+from typing import Any, Callable, Type
+
+
+class Accessor:
+    """Object for implementing class accessors."""
+
+    def __init__(self, name: str, accessor: Any):
+        self.name = name
+        self.accessor = accessor
+
+    def __get__(self, obj: Any, cls: Type) -> Any:
+        return self.accessor(obj)
+
+
+def wx_accessor(cls: Type) -> Callable:
+    """Create an accessor through the wx namespace to a given class.
+
+    Parameters
+    ----------
+    cls : class
+        The class to set the accessor to.
+
+    Returns
+    -------
+    function
+        The accessor function to to the class.
+    """
+
+    def decorator(accessor: Any) -> Any:
+        setattr(cls, "wx", Accessor("wx", accessor))
+        return accessor
+
+    return decorator
```

### Comparing `wxee-0.4.0/wxee/collection.py` & `wxee-0.4.1/wxee/collection.py`

 * *Ordering differences only*

 * *Files 16% similar despite different names*

```diff
@@ -1,245 +1,245 @@
-import tempfile
-import warnings
-from typing import List, Optional
-
-import ee  # type: ignore
-import xarray as xr
-from joblib import Parallel, delayed  # type: ignore
-from tqdm.auto import tqdm  # type: ignore
-
-from wxee import constants
-from wxee.accessors import wx_accessor
-from wxee.time_series import TimeSeries
-from wxee.utils import _dataset_from_files, _flatten_list, parallel_tqdm
-
-
-@wx_accessor(ee.imagecollection.ImageCollection)
-class ImageCollection:
-    def __init__(self, obj: ee.imagecollection.ImageCollection):
-        """
-        Parameters
-        ----------
-        obj : ee.ImageCollection
-            The Image Collection instance extended by this class.
-        """
-        self._obj = obj
-
-    def _to_image_list(self) -> List[ee.Image]:
-        """Convert an image collection to a Python list of images."""
-        return [
-            ee.Image(self._obj.toList(self._obj.size()).get(i))
-            for i in range(self._obj.size().getInfo())
-        ]
-
-    def get_image(self, index: int) -> ee.Image:
-        """Return the image at the specified index in the collection. A negative index counts backwards from the end of
-        the collection.
-
-        Parameters
-        ----------
-        index : int
-            The index of the image in the collection.
-
-        Returns
-        -------
-        ee.Image
-            The image at the given index.
-        """
-        return ee.Image(self._obj.toList(self._obj.size()).get(index))
-
-    def last(self) -> ee.Image:
-        """Return the last image in the collection.
-
-        Returns
-        -------
-        ee.Image
-            The last image in the collection.
-        """
-        return self.get_image(self._obj.size().subtract(1))
-
-    def to_xarray(
-        self,
-        path: Optional[str] = None,
-        region: Optional[ee.Geometry] = None,
-        scale: Optional[int] = None,
-        crs: str = "EPSG:4326",
-        masked: bool = True,
-        nodata: int = -32_768,
-        num_cores: int = -1,
-        progress: bool = True,
-        max_attempts: int = 10,
-    ) -> xr.Dataset:
-        """Convert an image collection to an xarray.Dataset. The :code:`system:time_start` property of each image in the
-        collection is used to arrange the time dimension, and each image variable is loaded as a separate array in
-        the dataset.
-
-        Parameters
-        ----------
-        region : ee.Geometry, optional
-            The region to download the images within. If none is provided, the :code:`geometry` of the image collection
-            will be used. If geometry varies between images in the collection, the region will encompass all images
-            which may lead to very large arrays and download limits.
-        scale : int, optional
-            The scale to download the array at in the CRS units. If none is provided, the :code:`projection.nominalScale`
-            of the images will be used.
-        crs : str, default "EPSG:4326"
-            The coordinate reference system to download the array in.
-        masked : bool, default True
-            If true, nodata pixels in the array will be masked by replacing them with numpy.nan. This will silently
-            cast integer datatypes to float.
-        nodata : int, default -32,768
-            The value to set as nodata in the array. Any masked pixels will be filled with this value.
-        num_cores : int, default -1
-            The number of CPU cores to use for parallel operations. Defaults to -1 which will use all available cores.
-        progress : bool, default True
-            If true, a progress bar will be displayed to track download progress.
-        max_attempts: int, default 10
-            Download requests to Earth Engine may intermittently fail. Failed attempts will be retried up to
-            max_attempts. Must be between 1 and 99.
-
-        Returns
-        -------
-        xarray.Dataset
-            A dataset containing all images in the collection with an assigned time dimension and variables set from
-            each image.
-
-        Raises
-        ------
-        DownloadError
-            Raised if the image cannot be successfully downloaded after the maximum number of attempts.
-
-        Examples
-        --------
-        >>> col = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET").filterDate("2020-09-08", "2020-09-15")
-        >>> col.wx.to_xarray(scale=40000, crs="EPSG:5070", nodata=-9999)
-        """
-        with tempfile.TemporaryDirectory(prefix=constants.TMP_PREFIX) as tmp:
-            files = self._obj.wx.to_tif(
-                out_dir=tmp,
-                region=region,
-                scale=scale,
-                crs=crs,
-                file_per_band=True,
-                masked=masked,
-                nodata=nodata,
-                num_cores=num_cores,
-                progress=progress,
-                max_attempts=max_attempts,
-            )
-
-            ds = _dataset_from_files(files, masked, nodata)
-
-        if path:
-            msg = (
-                "The path argument is deprecated and will be removed in a future "
-                "release. Use the `xarray.Dataset.to_netcdf` method instead."
-            )
-            warnings.warn(category=DeprecationWarning, message=msg)
-            ds.to_netcdf(path, mode="w")
-
-        return ds
-
-    def to_tif(
-        self,
-        out_dir: str = ".",
-        prefix: Optional[str] = None,
-        region: Optional[ee.Geometry] = None,
-        scale: Optional[int] = None,
-        crs: str = "EPSG:4326",
-        file_per_band: bool = False,
-        masked: bool = True,
-        nodata: int = -32_768,
-        num_cores: int = -1,
-        progress: bool = True,
-        max_attempts: int = 10,
-    ) -> List[str]:
-        """Download all images in the collection to geoTIFF. Image file names will be the :code:`system:id` of each image
-        after replacing invalid characters with underscores, with an optional user-defined prefix.
-
-        Parameters
-        ----------
-        out_dir : str, default "."
-            The directory to save the images to.
-        prefix : str, optional
-            A description to prefix to all image file names. If none is provided, no prefix will be added.
-        region : ee.Geometry, optional
-            The region to download the image within. If none is provided, the :code:`geometry` of each image will be used.
-        scale : int, optional
-            The scale to download each image at in the CRS units. If none is provided, the :code:`projection.nominalScale`
-            of each image will be used.
-        crs : str, default "EPSG:4326"
-            The coordinate reference system to download each image in.
-        file_per_band : bool, default False
-            If true, one file will be downloaded per band per image. If false, one multiband file will be downloaded per
-            image instead.
-        masked : bool, default True
-            If true, the nodata value of each image will be set in the image metadata.
-        nodata : int, default -32,768
-            The value to set as nodata in each image. Any masked pixels in the images will be filled with this value.
-        num_cores : int, default -1
-            The number of CPU cores to use for parallel operations. Defaults to -1 which will use all available cores.
-        progress : bool, default True
-            If true, a progress bar will be displayed to track download progress.
-        max_attempts: int, default 10
-            Download requests to Earth Engine may intermittently fail. Failed attempts will be retried up to
-            max_attempts. Must be between 1 and 99.
-
-        Returns
-        -------
-        list[str]
-            Paths to downloaded images.
-
-        Raises
-        ------
-        DownloadError
-            Raised if the image cannot be successfully downloaded after the maximum number of attempts.
-
-        Example
-        -------
-        >>> col = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET").filterDate("2020-09-08", "2020-09-15")
-        >>> col.wx.to_tif(scale=40000, crs="EPSG:5070", nodata=-9999)
-        """
-        if prefix:
-            self._obj = self._obj.map(lambda img: img.wx._prefix_id(prefix))
-
-        imgs = self._to_image_list()
-        n = len(imgs)
-
-        with Parallel(n_jobs=num_cores, backend="threading") as p:
-            with parallel_tqdm(
-                tqdm(desc="Requesting data", total=n, disable=not progress)
-            ):
-                urls = p(
-                    delayed(img.wx._get_url)(
-                        region, scale, crs, file_per_band, nodata, max_attempts
-                    )
-                    for img in imgs
-                )
-
-            with parallel_tqdm(
-                tqdm(desc="Downloading data", total=n, disable=not progress)
-            ):
-                img_urls = zip(imgs, urls)
-                tifs = p(
-                    delayed(img.wx._url_to_tif)(
-                        url, out_dir, file_per_band, masked, nodata, False, max_attempts
-                    )
-                    for img, url in img_urls
-                )
-
-        return _flatten_list(tifs)
-
-    def to_time_series(self) -> TimeSeries:
-        """Convert to a :code:`wxee.TimeSeries` collection with associated methods.
-
-        Returns
-        -------
-        wxee.TimeSeries
-            The collection as a TimeSeries object.
-
-        Examples
-        --------
-        >>> col = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET")
-        >>> ts = col.wx.to_time_series()
-        """
-        return TimeSeries(self._obj)
+import tempfile
+import warnings
+from typing import List, Optional
+
+import ee  # type: ignore
+import xarray as xr
+from joblib import Parallel, delayed  # type: ignore
+from tqdm.auto import tqdm  # type: ignore
+
+from wxee import constants
+from wxee.accessors import wx_accessor
+from wxee.time_series import TimeSeries
+from wxee.utils import _dataset_from_files, _flatten_list, parallel_tqdm
+
+
+@wx_accessor(ee.imagecollection.ImageCollection)
+class ImageCollection:
+    def __init__(self, obj: ee.imagecollection.ImageCollection):
+        """
+        Parameters
+        ----------
+        obj : ee.ImageCollection
+            The Image Collection instance extended by this class.
+        """
+        self._obj = obj
+
+    def _to_image_list(self) -> List[ee.Image]:
+        """Convert an image collection to a Python list of images."""
+        return [
+            ee.Image(self._obj.toList(self._obj.size()).get(i))
+            for i in range(self._obj.size().getInfo())
+        ]
+
+    def get_image(self, index: int) -> ee.Image:
+        """Return the image at the specified index in the collection. A negative index counts backwards from the end of
+        the collection.
+
+        Parameters
+        ----------
+        index : int
+            The index of the image in the collection.
+
+        Returns
+        -------
+        ee.Image
+            The image at the given index.
+        """
+        return ee.Image(self._obj.toList(self._obj.size()).get(index))
+
+    def last(self) -> ee.Image:
+        """Return the last image in the collection.
+
+        Returns
+        -------
+        ee.Image
+            The last image in the collection.
+        """
+        return self.get_image(self._obj.size().subtract(1))
+
+    def to_xarray(
+        self,
+        path: Optional[str] = None,
+        region: Optional[ee.Geometry] = None,
+        scale: Optional[int] = None,
+        crs: str = "EPSG:4326",
+        masked: bool = True,
+        nodata: int = -32_768,
+        num_cores: int = -1,
+        progress: bool = True,
+        max_attempts: int = 10,
+    ) -> xr.Dataset:
+        """Convert an image collection to an xarray.Dataset. The :code:`system:time_start` property of each image in the
+        collection is used to arrange the time dimension, and each image variable is loaded as a separate array in
+        the dataset.
+
+        Parameters
+        ----------
+        region : ee.Geometry, optional
+            The region to download the images within. If none is provided, the :code:`geometry` of the image collection
+            will be used. If geometry varies between images in the collection, the region will encompass all images
+            which may lead to very large arrays and download limits.
+        scale : int, optional
+            The scale to download the array at in the CRS units. If none is provided, the :code:`projection.nominalScale`
+            of the images will be used.
+        crs : str, default "EPSG:4326"
+            The coordinate reference system to download the array in.
+        masked : bool, default True
+            If true, nodata pixels in the array will be masked by replacing them with numpy.nan. This will silently
+            cast integer datatypes to float.
+        nodata : int, default -32,768
+            The value to set as nodata in the array. Any masked pixels will be filled with this value.
+        num_cores : int, default -1
+            The number of CPU cores to use for parallel operations. Defaults to -1 which will use all available cores.
+        progress : bool, default True
+            If true, a progress bar will be displayed to track download progress.
+        max_attempts: int, default 10
+            Download requests to Earth Engine may intermittently fail. Failed attempts will be retried up to
+            max_attempts. Must be between 1 and 99.
+
+        Returns
+        -------
+        xarray.Dataset
+            A dataset containing all images in the collection with an assigned time dimension and variables set from
+            each image.
+
+        Raises
+        ------
+        DownloadError
+            Raised if the image cannot be successfully downloaded after the maximum number of attempts.
+
+        Examples
+        --------
+        >>> col = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET").filterDate("2020-09-08", "2020-09-15")
+        >>> col.wx.to_xarray(scale=40000, crs="EPSG:5070", nodata=-9999)
+        """
+        with tempfile.TemporaryDirectory(prefix=constants.TMP_PREFIX) as tmp:
+            files = self._obj.wx.to_tif(
+                out_dir=tmp,
+                region=region,
+                scale=scale,
+                crs=crs,
+                file_per_band=True,
+                masked=masked,
+                nodata=nodata,
+                num_cores=num_cores,
+                progress=progress,
+                max_attempts=max_attempts,
+            )
+
+            ds = _dataset_from_files(files, masked, nodata)
+
+        if path:
+            msg = (
+                "The path argument is deprecated and will be removed in a future "
+                "release. Use the `xarray.Dataset.to_netcdf` method instead."
+            )
+            warnings.warn(category=DeprecationWarning, message=msg)
+            ds.to_netcdf(path, mode="w")
+
+        return ds
+
+    def to_tif(
+        self,
+        out_dir: str = ".",
+        prefix: Optional[str] = None,
+        region: Optional[ee.Geometry] = None,
+        scale: Optional[int] = None,
+        crs: str = "EPSG:4326",
+        file_per_band: bool = False,
+        masked: bool = True,
+        nodata: int = -32_768,
+        num_cores: int = -1,
+        progress: bool = True,
+        max_attempts: int = 10,
+    ) -> List[str]:
+        """Download all images in the collection to geoTIFF. Image file names will be the :code:`system:id` of each image
+        after replacing invalid characters with underscores, with an optional user-defined prefix.
+
+        Parameters
+        ----------
+        out_dir : str, default "."
+            The directory to save the images to.
+        prefix : str, optional
+            A description to prefix to all image file names. If none is provided, no prefix will be added.
+        region : ee.Geometry, optional
+            The region to download the image within. If none is provided, the :code:`geometry` of each image will be used.
+        scale : int, optional
+            The scale to download each image at in the CRS units. If none is provided, the :code:`projection.nominalScale`
+            of each image will be used.
+        crs : str, default "EPSG:4326"
+            The coordinate reference system to download each image in.
+        file_per_band : bool, default False
+            If true, one file will be downloaded per band per image. If false, one multiband file will be downloaded per
+            image instead.
+        masked : bool, default True
+            If true, the nodata value of each image will be set in the image metadata.
+        nodata : int, default -32,768
+            The value to set as nodata in each image. Any masked pixels in the images will be filled with this value.
+        num_cores : int, default -1
+            The number of CPU cores to use for parallel operations. Defaults to -1 which will use all available cores.
+        progress : bool, default True
+            If true, a progress bar will be displayed to track download progress.
+        max_attempts: int, default 10
+            Download requests to Earth Engine may intermittently fail. Failed attempts will be retried up to
+            max_attempts. Must be between 1 and 99.
+
+        Returns
+        -------
+        list[str]
+            Paths to downloaded images.
+
+        Raises
+        ------
+        DownloadError
+            Raised if the image cannot be successfully downloaded after the maximum number of attempts.
+
+        Example
+        -------
+        >>> col = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET").filterDate("2020-09-08", "2020-09-15")
+        >>> col.wx.to_tif(scale=40000, crs="EPSG:5070", nodata=-9999)
+        """
+        if prefix:
+            self._obj = self._obj.map(lambda img: img.wx._prefix_id(prefix))
+
+        imgs = self._to_image_list()
+        n = len(imgs)
+
+        with Parallel(n_jobs=num_cores, backend="threading") as p:
+            with parallel_tqdm(
+                tqdm(desc="Requesting data", total=n, disable=not progress)
+            ):
+                urls = p(
+                    delayed(img.wx._get_url)(
+                        region, scale, crs, file_per_band, nodata, max_attempts
+                    )
+                    for img in imgs
+                )
+
+            with parallel_tqdm(
+                tqdm(desc="Downloading data", total=n, disable=not progress)
+            ):
+                img_urls = zip(imgs, urls)
+                tifs = p(
+                    delayed(img.wx._url_to_tif)(
+                        url, out_dir, file_per_band, masked, nodata, False, max_attempts
+                    )
+                    for img, url in img_urls
+                )
+
+        return _flatten_list(tifs)
+
+    def to_time_series(self) -> TimeSeries:
+        """Convert to a :code:`wxee.TimeSeries` collection with associated methods.
+
+        Returns
+        -------
+        wxee.TimeSeries
+            The collection as a TimeSeries object.
+
+        Examples
+        --------
+        >>> col = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET")
+        >>> ts = col.wx.to_time_series()
+        """
+        return TimeSeries(self._obj)
```

### Comparing `wxee-0.4.0/wxee/image.py` & `wxee-0.4.1/wxee/image.py`

 * *Ordering differences only*

 * *Files 16% similar despite different names*

```diff
@@ -1,290 +1,290 @@
-import tempfile
-import warnings
-from typing import List, Optional
-
-import ee  # type: ignore
-import rasterio  # type: ignore
-import xarray as xr
-from urllib3.exceptions import ProtocolError
-
-from wxee import constants
-from wxee.accessors import wx_accessor
-from wxee.exceptions import DownloadError, MissingPropertyError
-from wxee.utils import (
-    _dataset_from_files,
-    _download_url,
-    _format_date,
-    _replace_if_null,
-    _set_nodata,
-    _unpack_file,
-)
-
-
-@wx_accessor(ee.image.Image)
-class Image:
-    def __init__(self, obj: ee.image.Image):
-        self._obj = obj
-
-    def to_xarray(
-        self,
-        path: Optional[str] = None,
-        region: Optional[ee.Geometry] = None,
-        scale: Optional[int] = None,
-        crs: str = "EPSG:4326",
-        masked: bool = True,
-        nodata: int = -32_768,
-        progress: bool = True,
-        max_attempts: int = 10,
-    ) -> xr.Dataset:
-        """Convert an image to an xarray.Dataset. The :code:`system:time_start` property of the image is used to set the
-        time dimension, and each image variable is loaded as a separate array in the dataset.
-
-        Parameters
-        ----------
-        region : ee.Geometry, optional
-            The region to download the image within. If none is provided, the :code:`geometry` of the image will be used.
-        scale : int, optional
-            The scale to download the array at in the CRS units. If none is provided, the :code:`projection.nominalScale`
-            of the image will be used.
-        crs : str, default "EPSG:4326"
-            The coordinate reference system to download the array in.
-        masked : bool, default True
-            If true, nodata pixels in the array will be masked by replacing them with numpy.nan. This will silently
-            cast integer datatypes to float.
-        nodata : int, default -32,768
-            The value to set as nodata in the array. Any masked pixels will be filled with this value.
-        progress : bool, default True
-            If true, a progress bar will be displayed to track download progress.
-        max_attempts: int, default 10
-            Download requests to Earth Engine may intermittently fail. Failed attempts will be retried up to
-            max_attempts. Must be between 1 and 99.
-
-        Returns
-        -------
-        xarray.Dataset
-            A dataset containing the image with variables set.
-
-        Raises
-        ------
-        DownloadError
-            Raised if the image cannot be successfully downloaded after the maximum number of attempts.
-
-        Examples
-        --------
-        >>> col = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET").filterDate("2020-09-08", "2020-09-15")
-        >>> col.wx.to_xarray(scale=40000, crs="EPSG:5070", nodata=-9999)
-        """
-        with tempfile.TemporaryDirectory(prefix=constants.TMP_PREFIX) as tmp:
-            files = self.to_tif(
-                out_dir=tmp,
-                region=region,
-                scale=scale,
-                crs=crs,
-                file_per_band=True,
-                masked=masked,
-                nodata=nodata,
-                max_attempts=max_attempts,
-                progress=progress,
-            )
-
-            ds = _dataset_from_files(files, masked, nodata)
-
-        if path:
-            msg = (
-                "The path argument is deprecated and will be removed in a future "
-                "release. Use the `xarray.Dataset.to_netcdf` method instead."
-            )
-            warnings.warn(category=DeprecationWarning, message=msg)
-            ds.to_netcdf(path, mode="w")
-
-        return ds
-
-    def to_tif(
-        self,
-        out_dir: str = ".",
-        description: Optional[str] = None,
-        region: Optional[ee.Geometry] = None,
-        scale: Optional[int] = None,
-        crs: str = "EPSG:4326",
-        file_per_band: bool = False,
-        masked: bool = True,
-        nodata: int = -32_768,
-        progress: bool = True,
-        max_attempts: int = 10,
-    ) -> List[str]:
-        """Download an image to geoTIFF.
-
-        Parameters
-        ----------
-        out_dir : str, default "."
-            The directory to save the image to.
-        description : str, optional
-            The name to save the file as with no file extension. If none is provided, the :code:`system:id` of the image
-            will be used.
-        region : ee.Geometry, optional
-            The region to download the image within. If none is provided, the :code:`geometry` of the image will be used.
-        scale : int, optional
-            The scale to download the image at in the CRS units. If none is provided, the :code:`projection.nominalScale`
-            of the image will be used.
-        crs : str, default "EPSG:4326"
-            The coordinate reference system to download the image in.
-        file_per_band : bool, default False
-            If true, one file will be downloaded per band. If false, one multiband file will be downloaded instead.
-        masked : bool, default True
-            If true, the nodata value of the image will be set in the image metadata.
-        nodata : int, default -32,768
-            The value to set as nodata in the image. Any masked pixels in the image will be filled with this value.
-        progress : bool, default True
-            If true, a progress bar will be displayed to track download progress.
-        max_attempts: int, default 10
-            Download requests to Earth Engine may intermittently fail. Failed attempts will be retried up to
-            max_attempts. Must be between 1 and 99.
-
-        Returns
-        -------
-        list[str]
-            Paths to downloaded images.
-
-        Raises
-        ------
-        DownloadError
-            Raised if the image cannot be successfully downloaded after the maximum number of attempts.
-
-        Example
-        -------
-        >>> img = ee.Image("COPERNICUS/S2_SR/20200803T181931_20200803T182946_T11SPA")
-        >>> img.wx.to_tif(description="las_vegas", scale=200, crs="EPSG:5070", nodata=-9999)
-        """
-        self._obj = (
-            self._obj.set("system:id", description) if description else self._obj
-        )
-
-        url = self._get_url(region, scale, crs, file_per_band, nodata, max_attempts)
-
-        tifs = self._url_to_tif(
-            url, out_dir, file_per_band, masked, nodata, progress, max_attempts
-        )
-
-        return tifs
-
-    def _url_to_tif(
-        self,
-        url: str,
-        out_dir: str,
-        file_per_band: bool,
-        masked: bool,
-        nodata: int,
-        progress: bool,
-        max_attempts: int,
-    ) -> List[str]:
-        """Download a ZIP from a URL and unpack and process it by setting metadata."""
-        with tempfile.TemporaryDirectory(
-            dir=out_dir, prefix=constants.TMP_PREFIX
-        ) as tmp:
-            zipped = _download_url(url, tmp, progress, max_attempts)
-            tifs = _unpack_file(zipped, out_dir)
-        self._process_tifs(tifs, file_per_band, masked, nodata)
-
-        return tifs
-
-    def _process_tifs(
-        self, tifs: List[str], file_per_band: bool, masked: bool, nodata: int
-    ) -> None:
-        """Take downloaded images and process by setting nodata and assigning band names.
-        This is applied to files in place.
-        """
-        if masked:
-            for tif in tifs:
-                _set_nodata(tif, nodata)
-
-        if not file_per_band:
-            bandnames = self._obj.bandNames().getInfo()
-            for tif in tifs:
-                with rasterio.open(tif, mode="r+") as img:
-                    for i, band in enumerate(bandnames):
-                        img.set_band_description(i + 1, band)
-
-    def _get_url(
-        self,
-        region: Optional[ee.Geometry] = None,
-        scale: Optional[int] = None,
-        crs: str = "EPSG:4326",
-        file_per_band: bool = False,
-        nodata: int = -32_768,
-        max_attempts: int = 10,
-    ) -> str:
-        """Request and return the download URL from the Earth Engine server."""
-        if max_attempts < 1:
-            warnings.warn("Max attempts must be at least 1. Setting to 1.")
-            max_attempts = 1
-        elif max_attempts > 99:
-            warnings.warn("Max attempts must be less than 100. Setting to 99.")
-            max_attempts = 99
-
-        # Unmasking without sameFootprint (below) makes images unbounded, so store the bounded geometry before unmasking.
-        region = self._obj.geometry() if not region else region
-
-        # Set nodata values. If sameFootprint is true, areas outside of the image bounds will not be set.
-        img = self._obj.unmask(nodata, sameFootprint=False)
-
-        image_id = self._get_download_id()
-
-        url = None
-        attempts = 0
-        while attempts < max_attempts and not url:
-            try:
-                url = img.getDownloadURL(
-                    params=dict(
-                        name=image_id.getInfo(),
-                        scale=scale,
-                        crs=crs,
-                        region=region,
-                        filePerBand=file_per_band,
-                    )
-                )
-            # GEE has a habit of closing connections unexpectedly.
-            except ProtocolError:
-                attempts += 1
-
-        if not url:
-            raise DownloadError(
-                "Requested elements could not be downloaded from Earth Engine. Retrying may solve the issue."
-            )
-
-        return url
-
-    def _get_download_id(self) -> ee.String:
-        """Get the image's download ID by concatenating it's cleaned current ID with the time dimension and coordinate set by wxee. If
-        the wx:dimension and wx:coordinate have not been set, they will be set to "time" and the formatted system:time_start, respectively.
-        """
-        img = self._obj
-
-        original_id = _replace_if_null(img.get("system:id"), "null")
-        # Replace any invalid file path characters with underscores.
-        cleaned_id = ee.String(original_id).replace("([^a-z0-9]+)", "_", "gi")
-
-        date = _format_date(ee.Image(img).get("system:time_start"))
-        dimension = _replace_if_null(img.get("wx:dimension"), "time")
-        coordinate = _replace_if_null(img.get("wx:coordinate"), date)
-
-        try:
-            coordinate = coordinate.getInfo()
-        except ee.EEException as e:
-            if "Parameter 'value' is required" in str(e):
-                raise MissingPropertyError(
-                    f"Image is missing a `system:time_start` property which is required for "
-                    "downloading.\n\nEarth Engine properties can be lost when modifying images, so make sure to manually "
-                    "set or copy properties using the `.set` and `.copyProperties` methods after using methods like "
-                    "`.multiply` or `.median`. If you don't need time information, you can set an arbitrary time with "
-                    "`img = img.set('system:time_start', 0).`"
-                    "\n\nSee https://github.com/aazuspan/wxee/issues/43 for more details."
-                )
-            else:
-                raise e
-
-        return ee.List([cleaned_id, dimension, coordinate]).join(".")
-
-    def _prefix_id(self, prefix: str) -> ee.Image:
-        """Add a prefix to the image's system:id"""
-        original_id = _replace_if_null(self._obj.get("system:id"), "null")
-        return self._obj.set("system:id", ee.String(prefix).cat("_").cat(original_id))
+import tempfile
+import warnings
+from typing import List, Optional
+
+import ee  # type: ignore
+import rasterio  # type: ignore
+import xarray as xr
+from urllib3.exceptions import ProtocolError
+
+from wxee import constants
+from wxee.accessors import wx_accessor
+from wxee.exceptions import DownloadError, MissingPropertyError
+from wxee.utils import (
+    _dataset_from_files,
+    _download_url,
+    _format_date,
+    _replace_if_null,
+    _set_nodata,
+    _unpack_file,
+)
+
+
+@wx_accessor(ee.image.Image)
+class Image:
+    def __init__(self, obj: ee.image.Image):
+        self._obj = obj
+
+    def to_xarray(
+        self,
+        path: Optional[str] = None,
+        region: Optional[ee.Geometry] = None,
+        scale: Optional[int] = None,
+        crs: str = "EPSG:4326",
+        masked: bool = True,
+        nodata: int = -32_768,
+        progress: bool = True,
+        max_attempts: int = 10,
+    ) -> xr.Dataset:
+        """Convert an image to an xarray.Dataset. The :code:`system:time_start` property of the image is used to set the
+        time dimension, and each image variable is loaded as a separate array in the dataset.
+
+        Parameters
+        ----------
+        region : ee.Geometry, optional
+            The region to download the image within. If none is provided, the :code:`geometry` of the image will be used.
+        scale : int, optional
+            The scale to download the array at in the CRS units. If none is provided, the :code:`projection.nominalScale`
+            of the image will be used.
+        crs : str, default "EPSG:4326"
+            The coordinate reference system to download the array in.
+        masked : bool, default True
+            If true, nodata pixels in the array will be masked by replacing them with numpy.nan. This will silently
+            cast integer datatypes to float.
+        nodata : int, default -32,768
+            The value to set as nodata in the array. Any masked pixels will be filled with this value.
+        progress : bool, default True
+            If true, a progress bar will be displayed to track download progress.
+        max_attempts: int, default 10
+            Download requests to Earth Engine may intermittently fail. Failed attempts will be retried up to
+            max_attempts. Must be between 1 and 99.
+
+        Returns
+        -------
+        xarray.Dataset
+            A dataset containing the image with variables set.
+
+        Raises
+        ------
+        DownloadError
+            Raised if the image cannot be successfully downloaded after the maximum number of attempts.
+
+        Examples
+        --------
+        >>> col = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET").filterDate("2020-09-08", "2020-09-15")
+        >>> col.wx.to_xarray(scale=40000, crs="EPSG:5070", nodata=-9999)
+        """
+        with tempfile.TemporaryDirectory(prefix=constants.TMP_PREFIX) as tmp:
+            files = self.to_tif(
+                out_dir=tmp,
+                region=region,
+                scale=scale,
+                crs=crs,
+                file_per_band=True,
+                masked=masked,
+                nodata=nodata,
+                max_attempts=max_attempts,
+                progress=progress,
+            )
+
+            ds = _dataset_from_files(files, masked, nodata)
+
+        if path:
+            msg = (
+                "The path argument is deprecated and will be removed in a future "
+                "release. Use the `xarray.Dataset.to_netcdf` method instead."
+            )
+            warnings.warn(category=DeprecationWarning, message=msg)
+            ds.to_netcdf(path, mode="w")
+
+        return ds
+
+    def to_tif(
+        self,
+        out_dir: str = ".",
+        description: Optional[str] = None,
+        region: Optional[ee.Geometry] = None,
+        scale: Optional[int] = None,
+        crs: str = "EPSG:4326",
+        file_per_band: bool = False,
+        masked: bool = True,
+        nodata: int = -32_768,
+        progress: bool = True,
+        max_attempts: int = 10,
+    ) -> List[str]:
+        """Download an image to geoTIFF.
+
+        Parameters
+        ----------
+        out_dir : str, default "."
+            The directory to save the image to.
+        description : str, optional
+            The name to save the file as with no file extension. If none is provided, the :code:`system:id` of the image
+            will be used.
+        region : ee.Geometry, optional
+            The region to download the image within. If none is provided, the :code:`geometry` of the image will be used.
+        scale : int, optional
+            The scale to download the image at in the CRS units. If none is provided, the :code:`projection.nominalScale`
+            of the image will be used.
+        crs : str, default "EPSG:4326"
+            The coordinate reference system to download the image in.
+        file_per_band : bool, default False
+            If true, one file will be downloaded per band. If false, one multiband file will be downloaded instead.
+        masked : bool, default True
+            If true, the nodata value of the image will be set in the image metadata.
+        nodata : int, default -32,768
+            The value to set as nodata in the image. Any masked pixels in the image will be filled with this value.
+        progress : bool, default True
+            If true, a progress bar will be displayed to track download progress.
+        max_attempts: int, default 10
+            Download requests to Earth Engine may intermittently fail. Failed attempts will be retried up to
+            max_attempts. Must be between 1 and 99.
+
+        Returns
+        -------
+        list[str]
+            Paths to downloaded images.
+
+        Raises
+        ------
+        DownloadError
+            Raised if the image cannot be successfully downloaded after the maximum number of attempts.
+
+        Example
+        -------
+        >>> img = ee.Image("COPERNICUS/S2_SR/20200803T181931_20200803T182946_T11SPA")
+        >>> img.wx.to_tif(description="las_vegas", scale=200, crs="EPSG:5070", nodata=-9999)
+        """
+        self._obj = (
+            self._obj.set("system:id", description) if description else self._obj
+        )
+
+        url = self._get_url(region, scale, crs, file_per_band, nodata, max_attempts)
+
+        tifs = self._url_to_tif(
+            url, out_dir, file_per_band, masked, nodata, progress, max_attempts
+        )
+
+        return tifs
+
+    def _url_to_tif(
+        self,
+        url: str,
+        out_dir: str,
+        file_per_band: bool,
+        masked: bool,
+        nodata: int,
+        progress: bool,
+        max_attempts: int,
+    ) -> List[str]:
+        """Download a ZIP from a URL and unpack and process it by setting metadata."""
+        with tempfile.TemporaryDirectory(
+            dir=out_dir, prefix=constants.TMP_PREFIX
+        ) as tmp:
+            zipped = _download_url(url, tmp, progress, max_attempts)
+            tifs = _unpack_file(zipped, out_dir)
+        self._process_tifs(tifs, file_per_band, masked, nodata)
+
+        return tifs
+
+    def _process_tifs(
+        self, tifs: List[str], file_per_band: bool, masked: bool, nodata: int
+    ) -> None:
+        """Take downloaded images and process by setting nodata and assigning band names.
+        This is applied to files in place.
+        """
+        if masked:
+            for tif in tifs:
+                _set_nodata(tif, nodata)
+
+        if not file_per_band:
+            bandnames = self._obj.bandNames().getInfo()
+            for tif in tifs:
+                with rasterio.open(tif, mode="r+") as img:
+                    for i, band in enumerate(bandnames):
+                        img.set_band_description(i + 1, band)
+
+    def _get_url(
+        self,
+        region: Optional[ee.Geometry] = None,
+        scale: Optional[int] = None,
+        crs: str = "EPSG:4326",
+        file_per_band: bool = False,
+        nodata: int = -32_768,
+        max_attempts: int = 10,
+    ) -> str:
+        """Request and return the download URL from the Earth Engine server."""
+        if max_attempts < 1:
+            warnings.warn("Max attempts must be at least 1. Setting to 1.")
+            max_attempts = 1
+        elif max_attempts > 99:
+            warnings.warn("Max attempts must be less than 100. Setting to 99.")
+            max_attempts = 99
+
+        # Unmasking without sameFootprint (below) makes images unbounded, so store the bounded geometry before unmasking.
+        region = self._obj.geometry() if not region else region
+
+        # Set nodata values. If sameFootprint is true, areas outside of the image bounds will not be set.
+        img = self._obj.unmask(nodata, sameFootprint=False)
+
+        image_id = self._get_download_id()
+
+        url = None
+        attempts = 0
+        while attempts < max_attempts and not url:
+            try:
+                url = img.getDownloadURL(
+                    params=dict(
+                        name=image_id.getInfo(),
+                        scale=scale,
+                        crs=crs,
+                        region=region,
+                        filePerBand=file_per_band,
+                    )
+                )
+            # GEE has a habit of closing connections unexpectedly.
+            except ProtocolError:
+                attempts += 1
+
+        if not url:
+            raise DownloadError(
+                "Requested elements could not be downloaded from Earth Engine. Retrying may solve the issue."
+            )
+
+        return url
+
+    def _get_download_id(self) -> ee.String:
+        """Get the image's download ID by concatenating it's cleaned current ID with the time dimension and coordinate set by wxee. If
+        the wx:dimension and wx:coordinate have not been set, they will be set to "time" and the formatted system:time_start, respectively.
+        """
+        img = self._obj
+
+        original_id = _replace_if_null(img.get("system:id"), "null")
+        # Replace any invalid file path characters with underscores.
+        cleaned_id = ee.String(original_id).replace("([^a-z0-9]+)", "_", "gi")
+
+        date = _format_date(ee.Image(img).get("system:time_start"))
+        dimension = _replace_if_null(img.get("wx:dimension"), "time")
+        coordinate = _replace_if_null(img.get("wx:coordinate"), date)
+
+        try:
+            coordinate = coordinate.getInfo()
+        except ee.EEException as e:
+            if "Parameter 'value' is required" in str(e):
+                raise MissingPropertyError(
+                    f"Image is missing a `system:time_start` property which is required for "
+                    "downloading.\n\nEarth Engine properties can be lost when modifying images, so make sure to manually "
+                    "set or copy properties using the `.set` and `.copyProperties` methods after using methods like "
+                    "`.multiply` or `.median`. If you don't need time information, you can set an arbitrary time with "
+                    "`img = img.set('system:time_start', 0).`"
+                    "\n\nSee https://github.com/aazuspan/wxee/issues/43 for more details."
+                )
+            else:
+                raise e
+
+        return ee.List([cleaned_id, dimension, coordinate]).join(".")
+
+    def _prefix_id(self, prefix: str) -> ee.Image:
+        """Add a prefix to the image's system:id"""
+        original_id = _replace_if_null(self._obj.get("system:id"), "null")
+        return self._obj.set("system:id", ee.String(prefix).cat("_").cat(original_id))
```

### Comparing `wxee-0.4.0/wxee/params.py` & `wxee-0.4.1/wxee/params.py`

 * *Ordering differences only*

 * *Files 14% similar despite different names*

```diff
@@ -1,32 +1,32 @@
-import difflib
-from enum import Enum
-from typing import Any, Dict, Union
-
-
-class ParamEnum(Enum):
-    """An abstract class for automatically handling function parameters"""
-
-    @classmethod
-    def _options(cls) -> Dict[str, Any]:
-        return {option.name: option.value for option in cls}
-
-    @classmethod
-    def _get_closest_option(cls, name: str) -> Union[str, None]:
-        match = difflib.get_close_matches(
-            word=name, possibilities=cls._options().keys(), n=1
-        )
-        return match[0] if match else None
-
-    @classmethod
-    def get_option(cls, name: str) -> Any:
-        try:
-            return cls._options()[name]
-        except KeyError:
-            error_msg = (
-                f"Option must be in {sorted(cls._options().keys())}, not '{name}'."
-            )
-
-            closest = cls._get_closest_option(name)
-            hint = f" Did you mean '{closest}'?" if closest else ""
-
-            raise ValueError(error_msg + hint)
+import difflib
+from enum import Enum
+from typing import Any, Dict, Union
+
+
+class ParamEnum(Enum):
+    """An abstract class for automatically handling function parameters"""
+
+    @classmethod
+    def _options(cls) -> Dict[str, Any]:
+        return {option.name: option.value for option in cls}
+
+    @classmethod
+    def _get_closest_option(cls, name: str) -> Union[str, None]:
+        match = difflib.get_close_matches(
+            word=name, possibilities=cls._options().keys(), n=1
+        )
+        return match[0] if match else None
+
+    @classmethod
+    def get_option(cls, name: str) -> Any:
+        try:
+            return cls._options()[name]
+        except KeyError:
+            error_msg = (
+                f"Option must be in {sorted(cls._options().keys())}, not '{name}'."
+            )
+
+            closest = cls._get_closest_option(name)
+            hint = f" Did you mean '{closest}'?" if closest else ""
+
+            raise ValueError(error_msg + hint)
```

### Comparing `wxee-0.4.0/wxee/time_series.py` & `wxee-0.4.1/wxee/time_series.py`

 * *Ordering differences only*

 * *Files 13% similar despite different names*

```diff
@@ -1,854 +1,854 @@
-from typing import TYPE_CHECKING, Any, List, Optional, Union
-
-import ee  # type: ignore
-import pandas as pd  # type: ignore
-
-from wxee.climatology import Climatology, ClimatologyFrequencyEnum
-from wxee.exceptions import MissingPropertyError
-from wxee.interpolation import InterpolationMethodEnum
-from wxee.params import ParamEnum
-from wxee.utils import _millis_to_datetime, _normalize
-
-if TYPE_CHECKING:
-    import plotly.graph_objects as go  # type: ignore
-
-
-class TimeFrequencyEnum(ParamEnum):
-    """Parameters defining generic time frequnecies."""
-
-    year = "year"
-    month = "month"
-    week = "week"
-    day = "day"
-    hour = "hour"
-    minute = "minute"
-
-
-class WindowAlignEnum(ParamEnum):
-    """Parameters defining rolling window alignment options."""
-
-    left = "left"
-    center = "center"
-    right = "right"
-
-
-class TimeSeries(ee.imagecollection.ImageCollection):
-    """An image collection of chronological images."""
-
-    def __init__(self, *args: Any) -> None:
-        super().__init__(*args)
-
-    @property
-    def start_time(self) -> ee.Date:
-        """The :code:`system:time_start` of first chronological image in the collection.
-
-        Returns
-        -------
-        ee.Date
-            The start time of the collection.
-        """
-        return ee.Date(self.aggregate_min("system:time_start"))
-
-    @property
-    def end_time(self) -> ee.Date:
-        """The :code:`system:time_start` of last chronological image in the collection.
-
-        Returns
-        -------
-        ee.Date
-            The end time of the collection.
-        """
-        return ee.Date(self.aggregate_max("system:time_start"))
-
-    def interval(self, unit: str = "day") -> ee.Number:
-        """Compute the mean time interval between images in the time series.
-
-        Parameters
-        ----------
-        unit : str, default "day"
-            The unit to return the time interval in. One of "minute", "hour", "day", "week", "month", "year".
-
-        Returns
-        -------
-        ee.Number
-            The mean time interval between images.
-
-        Warning
-        -------
-        Calculating the interval of very large collections may exceed memory limits. If this happens, try selecting only
-        a portion of the collection dates.
-
-        Example
-        -------
-        >>> ts = wxee.TimeSeries("COPERNICUS/S2_SR")
-        >>> imgs = ts.filterBounds(ee.Geometry.Point([-105.787, 38.753]))
-        >>> imgs.interval("day").getInfo()
-        5.03
-        """
-        return self.end_time.difference(self.start_time, unit=unit).divide(
-            self.size().subtract(1)
-        )
-
-    def describe(self, unit: str = "day") -> None:  # pragma: no cover
-        """Generate and print descriptive statistics about the Time Series such as the ID, start and end dates, and time between images.
-        This requires pulling data from the server, so it may run slowly.
-
-        Parameters
-        ----------
-        unit : str, default "day"
-            The unit to return the time interval in. One of "second", "minute", "hour", "day", "week", "month", "year".
-
-        Returns
-        -------
-        None
-        """
-        size = self.size().getInfo()
-
-        # Pulling min and max out of the stats is slightly faster than using `aggregate_min` and `aggregate_max` separately
-        stats = self.aggregate_stats("system:time_start")
-        start_millis = ee.Date(stats.get("min"))
-        end_millis = ee.Date(stats.get("max"))
-
-        start = start_millis.format("yyyy-MM-dd HH:mm:ss z").getInfo()
-        end = end_millis.format("yyyy-MM-dd HH:mm:ss z").getInfo()
-
-        mean_interval = self.interval().getInfo()
-
-        id = self.get("system:id").getInfo()
-
-        print(
-            f"\033[1m{id}\033[0m"
-            f"\n\tImages: {size:,}"
-            f"\n\tStart date: {start}"
-            f"\n\tEnd date: {end}"
-            f"\n\tMean interval: {mean_interval:.2f} {unit}s"
-        )
-
-    def dataframe(self, props: Union[None, List[str], ee.List] = None) -> pd.DataFrame:
-        """Generate a Pandas dataframe describing properties of each image in the time series.
-
-        Parameters
-        ----------
-        props : Union[List[str], ee.List], optional
-            A list of property names to aggregate from all images into the dataframe. If none is
-            provided, all non-system properties of the first image in the time series will be used.
-
-        Returns
-        -------
-        pd.DataFrame
-            A Pandas dataframe where each row represents an image and columns represent system properties.
-        """
-        if props is None:
-            props = self.first().propertyNames().getInfo()
-            props = [
-                p
-                for p in props
-                if not p.startswith("system:")
-                or p in ["system:time_start", "system:id"]
-            ]
-        elif isinstance(props, ee.List):
-            props = props.getInfo()
-
-        df_dict = {}
-        n = self.size().getInfo()
-        for prop in set(props):
-            vals = self.aggregate_array(prop).getInfo()
-            if len(vals) == 0:
-                raise MissingPropertyError(
-                    f"The property `{prop}` is missing from all images!"
-                )
-            elif len(vals) < n:
-                raise MissingPropertyError(
-                    f"The property `{prop}` is missing from some images!"
-                )
-            if prop.startswith("system:time"):
-                vals = map(_millis_to_datetime, vals)
-
-            df_dict[prop] = vals
-
-        collection_id = self.get("system:id").getInfo()
-        df = pd.DataFrame.from_dict(df_dict)
-        df.index.id = collection_id
-        return df
-
-    def timeline(self) -> "go.Figure":  # pragma: no cover
-        """Generate an interactive plot showing the acquisition time of each image in the time series.
-
-        Returns
-        -------
-        go.Figure
-            A Plotly graph object interactive plot showing the acquisition time of each image in the time series.
-        """
-        try:
-            import plotly.express as px  # type: ignore
-        except ImportError:
-            raise ImportError(
-                "The `plotly` package is required for this feature. "
-                "Please install it with `pip install plotly` and try again."
-            ) from None
-
-        df = self.dataframe(props=["system:id", "system:time_start"])
-        df["y"] = 0
-
-        fig = px.line(
-            df,
-            x="system:time_start",
-            y="y",
-            hover_name="system:id",
-            markers=True,
-            labels={"system:time_start": ""},
-        )
-
-        fig.update_traces(
-            customdata=df[["system:id", "system:time_start"]],
-            hovertemplate="<b>%{customdata[0]}</b>"
-            + "<br>%{customdata[1]|%Y-%m-%d %H:%M:%S}",
-            line=dict(width=2, color="black"),
-            marker=dict(
-                size=12,
-                symbol="line-ns-open",
-                color="grey",
-                line=dict(width=1, color="black"),
-            ),
-        )
-
-        # Add circles for each image
-        fig.add_trace(
-            go.Scatter(
-                x=df["system:time_start"],
-                y=df.y,
-                mode="markers",
-                hoverinfo="skip",
-                marker=dict(
-                    size=6,
-                    symbol="circle",
-                    color="white",
-                    line=dict(width=1, color="black"),
-                ),
-            )
-        )
-
-        fig.update_layout(
-            plot_bgcolor="white",
-            height=200,
-            hoverlabel=dict(bgcolor="white"),
-            showlegend=False,
-        )
-
-        fig.update_yaxes(visible=False)
-        fig.update_xaxes(linecolor="black", ticks="outside")
-
-        return fig
-
-    def aggregate_time(
-        self, frequency: str, reducer: Optional[Any] = None, keep_bandnames: bool = True
-    ) -> "TimeSeries":
-        """Aggregate the collection over the time dimension to a specified frequency. This method can only be used to go from
-        small time frequencies to larger time frequencies, such as hours to days, not vice-versa. If the resampling frequency is smaller
-        than the time between images, un-aggregated images will be returned.
-
-        Parameters
-        ----------
-        frequency : str
-            The time frequency to aggregate to. One of 'year', 'month' 'week', 'day', 'hour'.
-        reducer : ee.Reducer, optional
-            The reducer to apply when aggregating over time. If none is provided, ee.Reducer.mean() will be used.
-        keep_bandnames : bool, default True
-            If true, the band names of the input images will be kept in the aggregated images. If false, the name of the
-            reducer will be appended to the band names, e.g. SR_B4 will become SR_B4_mean.
-
-        Returns
-        -------
-        TimeSeries
-            The input image collection aggregated to the specified time frequency.
-
-        Raises
-        ------
-        ValueError
-            If an invalid frequency is passed.
-
-        Example
-        -------
-        >>> ts_hourly = wxee.TimeSeries("NOAA/NWS/RTMA")
-        >>> daily_max = ts_hourly.aggregate_time(frequency="day", reducer=ee.Reducer.max())
-        """
-        # ee.Reducer can't be used without initializing ee (see https://github.com/google/earthengine-api/issues/164),
-        # so set the default reducer explicitly. This is also why the type hint above is set to Any.
-        reducer = ee.Reducer.mean() if not reducer else reducer
-        original_id = self.get("system:id")
-
-        TimeFrequencyEnum.get_option(frequency)
-
-        def resample_step(start: ee.Date) -> ee.Image:
-            """Resample one time step in the given unit from a specified start time."""
-            start = ee.Date(start)
-            end = start.advance(1, frequency)
-            imgs = self.filterDate(start, end)
-            resampled = imgs.reduce(reducer)
-            resampled = resampled.copyProperties(
-                imgs.first(), imgs.first().propertyNames()
-            )
-            resampled = resampled.set(
-                {
-                    "system:time_start": imgs.first().get("system:time_start"),
-                    "system:time_end": imgs.wx.last().get("system:time_end"),
-                }
-            )
-
-            if keep_bandnames:
-                resampled = ee.Image(resampled).rename(imgs.first().bandNames())
-
-            # If the resampling step falls between images, just return null
-            return ee.Algorithms.If(imgs.size().gt(0), resampled, None)
-
-        start_times = self._generate_steps_at_frequency(frequency)
-
-        return TimeSeries(start_times.map(resample_step, dropNulls=True)).set(
-            "system:id", original_id
-        )
-
-    def _generate_steps_at_frequency(self, frequency: str) -> "ee.List[ee.Date]":
-        """Generate a list of start dates that would split the time series into a given frequency. For example, a time series of daily
-        data at monthly frequency would return the start date of monthly periods starting from the first day.
-
-        In the example above, this is done by calculating the number of months that cover the time series and iteratively advancing
-        that many steps from the start time of the time series. This means that if the time series does not start on the first day of
-        a month, the steps will not line up with calendar months but will instead represent month-long groups of contiguous days.
-
-        A minimum of 1 step will be returned even if the time series period is smaller than the frequency.
-        """
-        TimeFrequencyEnum.get_option(frequency)
-
-        n_steps = self.end_time.difference(self.start_time, frequency).floor()
-        steps = ee.List.sequence(0, n_steps)
-
-        return steps.map(lambda x: self.start_time.advance(x, frequency))
-
-    def _calculate_climatology(
-        self,
-        climatology_reducer: Optional[Any],
-        frequency: str,
-        reducer: Optional[Any] = None,
-        start: Optional[int] = None,
-        end: Optional[int] = None,
-        keep_bandnames: bool = True,
-    ) -> Climatology:
-        """Calculate a climatology image collection with a given frequency and reducer.
-
-        Parameters
-        ----------
-        climatology_reducer: Optional[ee.Reducer]
-            The climatological reducer to apply to aggregated images. In most cases, this will be ee.Reducer.mean
-            or ee.Reducer.stdDev for generating climatological means and standard deviations, respectively.
-        frequency : str
-            The name of the time frequency. One of "day", "month".
-        reducer : Optional[ee.Reducer]
-            The reducer to apply when aggregating over time, e.g. aggregating hourly data to daily for a daily
-            climatology. If the data is already in the temporal scale of the climatology, e.g. creating a daily
-            climatology from daily data, the reducer will have no effect.
-        start : Optional[int]
-            The start coordinate in the time frequency to include in the climatology, e.g. 1 for January if the
-            frequency is "month". If none is provided, the default will be 1 for both "day" and "month".
-        end : Optional[int]
-            The end coordinate in the time frequency to include in the climatology, e.g. 8 for August if the
-            frequency is "month". If none is provided, the default will be 366 for "day" or 12 for "month"
-        keep_bandnames : bool, default True
-            If true, the band names of the input images will be kept in the aggregated images. If false, the name of the
-            reducer will be appended to the band names, e.g. SR_B4 will become SR_B4_mean.
-
-        Returns
-        -------
-        wxee.climatology.Climatology
-            The climatological collection.
-        """
-        reducer = ee.Reducer.mean() if not reducer else reducer
-
-        freq = ClimatologyFrequencyEnum.get_option(frequency)
-        start = freq.start if not start else start
-        end = freq.end if not end else end
-        prop = f"wx:{frequency}"
-
-        def reduce_frequency(x: ee.String) -> Union[None, ee.Image]:
-            """Apply a mean reducer over a time frequency, returning None if no images fall within the time window.
-
-            Parameters
-            ----------
-            x : ee.String
-                The time coordinate to reduce, such as "1" for January.
-            """
-            imgs = collection.filterMetadata(prop, "equals", x)
-            reduced = imgs.reduce(climatology_reducer)
-            # Retrieve the time from the image instead of using x because I need a formatted
-            # string for concatenating into the system:id later.
-            coord = ee.Date(imgs.first().get("system:time_start")).format(
-                freq.date_format
-            )
-            reduced = reduced.set("wx:dimension", frequency, "wx:coordinate", coord)
-
-            geom = collection.geometry()
-            # Reducing makes images unbounded, so re-clip bounded images
-            reduced = ee.Algorithms.If(geom.isUnbounded(), reduced, reduced.clip(geom))
-
-            reduced = ee.Image(reduced).rename(imgs.first().bandNames())
-
-            return ee.Algorithms.If(imgs.size().gt(0), reduced, None)
-
-        collection = self.aggregate_time(freq.name, reducer, keep_bandnames)
-        collection = collection.map(
-            lambda img: img.set(
-                prop,
-                ee.Number.parse(
-                    ee.Date(ee.Image(img).get("system:time_start")).format(
-                        freq.date_format
-                    )
-                ),
-            )
-        )
-        coord_list = ee.List.sequence(start, end)
-
-        clim = Climatology(
-            coord_list.map(lambda x: reduce_frequency(x), dropNulls=True)
-        )
-
-        clim = clim.set("system:id", self.get("system:id"))
-        clim.frequency = freq
-        clim.start = start
-        clim.end = end
-        clim.reducer = reducer
-
-        return clim
-
-    def climatology_mean(
-        self,
-        frequency: str,
-        reducer: Optional[Any] = None,
-        start: Optional[int] = None,
-        end: Optional[int] = None,
-        keep_bandnames: bool = True,
-    ) -> Climatology:
-        """Calculate a mean climatology image collection with a given frequency.
-
-        Parameters
-        ----------
-        frequency : str
-            The name of the time frequency. One of "day", "month".
-        reducer : Optional[ee.Reducer]
-            The reducer to apply when aggregating over time, e.g. aggregating hourly data to daily for a daily
-            climatology. If the data is already in the temporal scale of the climatology, e.g. creating a daily
-            climatology from daily data, the reducer will have no effect.
-        start : Optional[int]
-            The start coordinate in the time frequency to include in the climatology, e.g. 1 for January if the
-            frequency is "month". If none is provided, the default will be 1 for both "day" and "month".
-        end : Optional[int]
-            The end coordinate in the time frequency to include in the climatology, e.g. 8 for August if the
-            frequency is "month". If none is provided, the default will be 366 for "day" or 12 for "month"
-        keep_bandnames : bool, default True
-            If true, the band names of the input images will be kept in the aggregated images. If false, the name of the
-            reducer will be appended to the band names, e.g. SR_B4 will become SR_B4_mean.
-
-        Returns
-        -------
-        wxee.climatology.Climatology
-            The climatological mean collection.
-
-        Example
-        -------
-        >>> collection = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET")
-        >>> collection = collection.filterDate("1980", "2000")
-        >>> ts = wxee.TimeSeries(collection)
-        >>> daily_max = ts.climatology_mean(frequency="day", reducer=ee.Reducer.max())
-        >>> daily_max.size().getInfo()
-        366
-        """
-        mean_clim = self._calculate_climatology(
-            ee.Reducer.mean(), frequency, reducer, start, end, keep_bandnames
-        )
-        mean_clim.statistic = "mean"
-
-        return mean_clim
-
-    def climatology_std(
-        self,
-        frequency: str,
-        reducer: Optional[Any] = None,
-        start: Optional[int] = None,
-        end: Optional[int] = None,
-        keep_bandnames: bool = True,
-    ) -> Climatology:
-        """Calculate a standard deviation climatology image collection with a given frequency.
-
-        Parameters
-        ----------
-        frequency : str
-            The name of the time frequency. One of "day", "month".
-        reducer : Optional[ee.Reducer]
-            The reducer to apply when aggregating over time, e.g. aggregating hourly data to daily for a daily
-            climatology. If the data is already in the temporal scale of the climatology, e.g. creating a daily
-            climatology from daily data, the reducer will have no effect.
-        start : Optional[int]
-            The start coordinate in the time frequency to include in the climatology, e.g. 1 for January if the
-            frequency is "month". If none is provided, the default will be 1 for both "day" and "month".
-        end : Optional[int]
-            The end coordinate in the time frequency to include in the climatology, e.g. 8 for August if the
-            frequency is "month". If none is provided, the default will be 366 for "day" or 12 for "month"
-        keep_bandnames : bool, default True
-            If true, the band names of the input images will be kept in the aggregated images. If false, the name of the
-            reducer will be appended to the band names, e.g. SR_B4 will become SR_B4_stdDev.
-
-        Returns
-        -------
-        wxee.climatology.Climatology
-            The climatological standard deviation collection.
-
-        Example
-        -------
-        >>> collection = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET")
-        >>> collection = collection.filterDate("1980", "2000")
-        >>> ts = wxee.TimeSeries(collection)
-        >>> daily_max = ts.climatology_std(frequency="day", reducer=ee.Reducer.max())
-        >>> daily_max.size().getInfo()
-        366
-        """
-        mean_clim = self._calculate_climatology(
-            ee.Reducer.stdDev(), frequency, reducer, start, end, keep_bandnames
-        )
-        mean_clim.statistic = "standard deviation"
-
-        return mean_clim
-
-    def climatology_anomaly(
-        self,
-        mean: Climatology,
-        std: Optional[Climatology] = None,
-        keep_bandnames: bool = True,
-    ) -> "TimeSeries":
-        """Calculate climatological anomalies for the time series. The frequency and reducer will be the same as those
-        used in the :code:`mean` climatology. Standardized anomalies can be calculated by providing a climatological standard
-        deviation as :code:`std`.
-
-        A climatological anomaly is calculated as the difference between the climatological mean and a given observation.
-        For standardized anomalies, that difference is divided by the climatological standard deviation. Standardized
-        anomalies represent unitless measurements of how many standard deviations an observation was from the climatological
-        mean, and therefore allow easy comparisons between variables.
-
-        Note
-        ----
-        Climatological anomalies are generally calculated using long-term climatological normals (e.g. 30 years). If
-        the climatological mean and standard deviation represent a shorter period, interpretation of results may vary.
-
-        Parameters
-        ----------
-        mean : Climatology
-            The long-term climatological mean to calculate anomalies from. The climatological frequency and reducer will
-            be determined from this climatology.
-        std : Optional[Climatology]
-            The long-term climatological standard deviation to calculate anomalies from. If provided, standardized
-            climatological anomalies will be calculated. The climatological standard deviation frequency and reducer must
-            match the frequency and reducer used by the climatological mean.
-        keep_bandnames : bool, default True
-            If true, the band names of the input images will be kept in the aggregated images. If false, the name of the
-            reducer will be appended to the band names, e.g. SR_B4 will become SR_B4_mean.
-
-        Returns
-        -------
-        wxee.time_series.TimeSeries
-            Climatological anomalies within the TimeSeries period.
-
-        Raises
-        ------
-        ValueError
-            If the :code:`std` frequency or reducer do not match the :code:`mean` frequency or reducer. Only applies if
-            a :code:`std` is provided.
-
-        Example
-        -------
-        >>> collection = wxee.TimeSeries("IDAHO_EPSCOR/GRIDMET")
-        >>> reference = collection.filterDate("1980", "2010")
-        >>> mean = reference.climatology_mean("month")
-        >>> std = reference.climatology_std("month")
-        >>> observation = collection.filterDate("2020", "2021")
-        >>> anomaly = observation.climatology_anomaly(mean, std)
-        """
-        reducer = mean.reducer
-        freq = mean.frequency
-
-        if std:
-            if std.frequency != freq:
-                raise ValueError(
-                    f"Mean frequency '{mean.frequency.name}' does not match std frequency '{std.frequency.name}'."
-                )
-            if std.reducer != mean.reducer:
-                # There is no way to determine the type of reducer used after the fact, or else I would list them.
-                raise ValueError(f"Mean reducer does not match std reducer.")
-
-        def image_anomaly(img: ee.Image) -> ee.Image:
-            """Identify the climatological mean and std deviation for a given image
-            and use them to calculate and return the anomaly.
-            """
-            # Get the climatological coordinate of the image
-            coord = ee.Date(ee.Image(img).get("system:time_start")).format(
-                freq.date_format
-            )
-
-            # Get the climatological mean at that coordinate
-            coord_mean = mean.filterMetadata("wx:coordinate", "equals", coord)
-
-            anom = img.subtract(coord_mean.first())
-
-            # If a standard deviation is provided, standardize the anomalies
-            if std:
-                coord_std = std.filterMetadata("wx:coordinate", "equals", coord)
-                anom = anom.divide(coord_std.first())
-
-            anom = anom.copyProperties(img, img.propertyNames())
-
-            # This permits sparse mean and std climatologies, e.g. those with a start and end set.
-            return ee.Algorithms.If(coord_mean.size().gt(0), anom, None)
-
-        collection = self.aggregate_time(freq.name, reducer, keep_bandnames)
-
-        return collection.map(image_anomaly, opt_dropNulls=True)
-
-    def interpolate_time(self, time: ee.Date, method: str = "linear") -> ee.Image:
-        """Use interpolation to synthesize data at a given time within the time series. Based on the
-        interpolation method chosen, a certain number of images must be present in the time series
-        before and after the target date.
-
-        Nearest and linear interpolation require 1 image before and after the selected time while
-        cubic interpolation requires 2 images before and after the selected time.
-
-        Parameters
-        ----------
-        date : ee.Date
-            The target date to interpolate data at. This must be within the time series period.
-        method : str, default linear
-            The interpolation method to use, one of "nearest", "linear", or "cubic".
-
-        Returns
-        -------
-        ee.Image
-            Data interpolated to the target time from surrounding data in the time series.
-
-        Examples
-        --------
-        >>> ts = wxee.TimeSeries("IDAHO_EPSCOR/GRIDMET")
-        >>> target_date = ee.Date("2020-09-08T03")
-
-        Interpolate weather data at the target date using cubic interpolation.
-
-        >>> filled = ts.interpolate(target_date, "cubic")
-        """
-        method_func = InterpolationMethodEnum.get_option(method)
-
-        y1, y0 = self._get_n_images_before(time, 2)
-        y2, y3 = self._get_n_images_after(time, 2)
-
-        x1, x2 = [ee.Number(img.get("system:time_start")) for img in [y1, y2]]
-        mu = _normalize(time.millis(), ee.Date(x1).millis(), ee.Date(x2).millis())
-
-        if method in ["nearest", "linear"]:
-            interpolated = method_func(y1, y2, mu)
-        elif method == "cubic":
-            interpolated = method_func(y0, y1, y2, y3, mu)
-
-        interpolated = interpolated.set("system:time_start", time.millis())
-
-        return interpolated
-
-    def _get_n_images_before(self, date: ee.Date, n: int) -> List[ee.Image]:
-        """Get n images before a given date (inclusive) in the time series. The images will be selected
-        and returned in a list in order of their proximity to the target date."""
-        before_imgs = self.filterDate(self.start_time, date.advance(1, "second")).sort(
-            "system:time_start", opt_ascending=False
-        )
-        before_list = before_imgs.toList(n)
-
-        return [ee.Image(before_list.get(i)) for i in range(n)]
-
-    def _get_n_images_after(self, date: ee.Date, n: int) -> List[ee.Image]:
-        """Get n images after a given date (inclusive) in the time series. The images will be selected
-        and returned in order of their proximity to the target date."""
-        after_imgs = self.filterDate(date, self.end_time.advance(1, "second")).sort(
-            "system:time_start", opt_ascending=True
-        )
-        after_list = after_imgs.toList(n)
-
-        return [ee.Image(after_list.get(i)) for i in range(n)]
-
-    def insert_image(self, img: ee.Image) -> "TimeSeries":
-        """Insert an image into the time series and sort it by :code:`system:time_start`.
-
-        Parameters
-        ----------
-        img : ee.Image
-            The image to insert.
-
-        Returns
-        -------
-        wxee.TimeSeries
-            The time series with the image inserted in time order
-        """
-        merged = self.merge(ee.ImageCollection(img)).sort("system:time_start")
-        merged = ee.ImageCollection(merged.copyProperties(self, self.propertyNames()))
-        return merged.wx.to_time_series()
-
-    def rolling_time(
-        self,
-        window: int,
-        unit: str,
-        align: str = "left",
-        min_observations: int = 1,
-        reducer: Optional[Any] = None,
-        keep_bandnames: bool = True,
-    ) -> "TimeSeries":
-        """Apply a rolling reducer over the time dimension. Rolling windows are calculated around each image,
-        so if images are irregularly spaced in time, the windows will be as well. As long as the minimum
-        observations are met in each window, the output time series will contain the same number of images as
-        the input, with each image reduced over its surrounding window.
-
-        Parameters
-        ----------
-        window : int
-            The number of time units to include in each rolling period.
-        unit : str
-            The time frequency of the window. One of "hour", "day", "week", "month", "year".
-        align : str, default "left"
-            The start location of the rolling window, relative to the primary image time. One of "left", "center",
-            "right". For example, a 3-day left-aligned window will include all images up to (but not including)
-            3 days prior to the primary image. Date ranges are exclusive in the alignment direction and inclusive
-            in the opposite direction, so each primary image will be included in its own window.
-        min_observations : int, default 1
-            The minimum number of images to include in the rolling window (counting the primary image). If the
-            minimum observations are not met, the primary image will be dropped. For example, a monthly time series
-            reduced with a 10 day window and :code:`min_observations==3` would be empty because none of the
-            windows would include enough observations.
-        reducer : Optional[ee.Reducer]
-            The reducer to apply to each rolling window. If none is given, ee.Reducer.mean will be used.
-        keep_bandnames : bool, default True
-            If true, the band names of the input images will be kept in the reduced images. If false, the name of the
-            reducer will be appended to the band names, e.g. SR_B4 will become SR_B4_mean.
-
-        Returns
-        -------
-        wxee.time_series.TimeSeries
-            The time series with the rolling reducer applied to each image.
-
-        Example
-        -------
-        >>> ts = wxee.TimeSeries("MODIS/006/MOD13A2)
-        >>> ts_smooth = ts.rolling_time(90, "day", "center", reducer=ee.Reducer.median())
-        """
-        reducer = ee.Reducer.mean() if not reducer else reducer
-
-        def roll_image(img: ee.Image) -> ee.Image:
-            """Apply a rolling reducer to a single image using its temporal neighbors"""
-            center = ee.Date(img.get("system:time_start"))
-            neighbors = self._get_window(center, window, unit, align)
-            smooth = neighbors.reduce(reducer)
-
-            props = {
-                "wx:window_size": window,
-                "wx:window_unit": unit,
-                "wx:window_align": align,
-                "wx:window_includes": neighbors.size(),
-            }
-            smooth = ee.Image(
-                smooth.copyProperties(img, img.propertyNames()).set(props)
-            )
-
-            if keep_bandnames:
-                smooth = smooth.rename(img.bandNames())
-
-            return ee.Algorithms.If(neighbors.size().lt(min_observations), None, smooth)
-
-        return self.map(roll_image, opt_dropNulls=True)
-
-    def fill_gaps(
-        self,
-        window: int,
-        unit: str,
-        align: str = "center",
-        reducer: Optional[Any] = None,
-        fill_value: Optional[float] = None,
-    ) -> "TimeSeries":
-        """Apply gap-filling using a moving window reducer through time. Each image is unmasked using its reduced temporal neighbors.
-        If the window is not wide enough to include an unmasked value (e.g. if clouds occur in the same location in all images),
-        masked values will remain unless a :code:`fill_value` is specified.
-
-        Parameters
-        ----------
-        window : int
-            The number of time units to include in each rolling period.
-        unit : str
-            The time frequency of the window. One of "hour", "day", "week", "month", "year".
-        align : str, default "center"
-            The start location of the rolling window, relative to the primary image time. One of "left", "center",
-            "right". For example, a 3-day left-aligned window will include all images up to (but not including)
-            3 days prior to the primary image. Date ranges are exclusive in the alignment direction and inclusive
-            in the opposite direction, so each primary image will be included in its own window.
-        reducer : Optional[ee.Reducer]
-            The reducer to apply to each rolling window. If none is given, ee.Reducer.mean will be used.
-        fill_value : float
-            The value to fill any masked values with after applying initial gap-filling. If none is given, masked
-            values may remain if the window size is not large enough.
-
-        Returns
-        -------
-        wxee.time_series.TimeSeries
-            The time series with each image unmasked using its reduced neighbors.
-
-        Example
-        -------
-        >>> ts = wxee.TimeSeries("MODIS/006/MOD13A2)
-        >>> ts_filled = ts.fill_gaps(90, "day", "center", reducer=ee.Reducer.median())
-        """
-        reducer = ee.Reducer.mean() if not reducer else reducer
-
-        def fill_image(img: ee.Image) -> ee.Image:
-            """Unmask a single image by applying a rolling reducer to its temporal neighbors."""
-            center = ee.Date(img.get("system:time_start"))
-            neighbors = self._get_window(center, window, unit, align)
-            filler = neighbors.reduce(reducer)
-
-            filled = img.unmask(filler)
-            filled = filled.unmask(fill_value) if fill_value else filled
-
-            return filled
-
-        return self.map(fill_image)
-
-    def _get_window(
-        self, time: ee.Date, window: int, unit: str, align: str = "left"
-    ) -> "TimeSeries":
-        """Get all images within a window around a target date.
-
-        Parameters
-        ----------
-        time : ee.Date
-            The center date of the window.
-        window : int
-            The number of time units to include in the window.
-        unit : str
-            The time frequency of the window. One of "hour", "day", "week", "month", "year".
-        align : str, default "left"
-            The start location of the window, relative to the center time. One of "left", "center", "right". Date
-            ranges are exclusive in the alignment direction and inclusive in the opposite direction, so the center
-            date of the window is always included.
-
-        Returns
-        -------
-        wxee.time_series.TimeSeries
-            A time series containing all images in the window.
-        """
-        WindowAlignEnum.get_option(align)
-
-        offset = 1 if align == "left" else 0.5 if align == "center" else 0
-        nudge = 1 if align == "left" else 0 if align == "center" else -1
-
-        # The windows need to be nudged slightly to set the correct exclusive/inclusive order.
-        # For example, a left aligned window should exclude the left and include the right,
-        # and vice-versa for a right aligned window.
-        left = time.advance(window * offset * -1, unit).advance(nudge, "second")
-        right = left.advance(window, unit)
-
-        return self.filterDate(left, right)
+from typing import TYPE_CHECKING, Any, List, Optional, Union
+
+import ee  # type: ignore
+import pandas as pd  # type: ignore
+
+from wxee.climatology import Climatology, ClimatologyFrequencyEnum
+from wxee.exceptions import MissingPropertyError
+from wxee.interpolation import InterpolationMethodEnum
+from wxee.params import ParamEnum
+from wxee.utils import _millis_to_datetime, _normalize
+
+if TYPE_CHECKING:
+    import plotly.graph_objects as go  # type: ignore
+
+
+class TimeFrequencyEnum(ParamEnum):
+    """Parameters defining generic time frequnecies."""
+
+    year = "year"
+    month = "month"
+    week = "week"
+    day = "day"
+    hour = "hour"
+    minute = "minute"
+
+
+class WindowAlignEnum(ParamEnum):
+    """Parameters defining rolling window alignment options."""
+
+    left = "left"
+    center = "center"
+    right = "right"
+
+
+class TimeSeries(ee.imagecollection.ImageCollection):
+    """An image collection of chronological images."""
+
+    def __init__(self, *args: Any) -> None:
+        super().__init__(*args)
+
+    @property
+    def start_time(self) -> ee.Date:
+        """The :code:`system:time_start` of first chronological image in the collection.
+
+        Returns
+        -------
+        ee.Date
+            The start time of the collection.
+        """
+        return ee.Date(self.aggregate_min("system:time_start"))
+
+    @property
+    def end_time(self) -> ee.Date:
+        """The :code:`system:time_start` of last chronological image in the collection.
+
+        Returns
+        -------
+        ee.Date
+            The end time of the collection.
+        """
+        return ee.Date(self.aggregate_max("system:time_start"))
+
+    def interval(self, unit: str = "day") -> ee.Number:
+        """Compute the mean time interval between images in the time series.
+
+        Parameters
+        ----------
+        unit : str, default "day"
+            The unit to return the time interval in. One of "minute", "hour", "day", "week", "month", "year".
+
+        Returns
+        -------
+        ee.Number
+            The mean time interval between images.
+
+        Warning
+        -------
+        Calculating the interval of very large collections may exceed memory limits. If this happens, try selecting only
+        a portion of the collection dates.
+
+        Example
+        -------
+        >>> ts = wxee.TimeSeries("COPERNICUS/S2_SR")
+        >>> imgs = ts.filterBounds(ee.Geometry.Point([-105.787, 38.753]))
+        >>> imgs.interval("day").getInfo()
+        5.03
+        """
+        return self.end_time.difference(self.start_time, unit=unit).divide(
+            self.size().subtract(1)
+        )
+
+    def describe(self, unit: str = "day") -> None:  # pragma: no cover
+        """Generate and print descriptive statistics about the Time Series such as the ID, start and end dates, and time between images.
+        This requires pulling data from the server, so it may run slowly.
+
+        Parameters
+        ----------
+        unit : str, default "day"
+            The unit to return the time interval in. One of "second", "minute", "hour", "day", "week", "month", "year".
+
+        Returns
+        -------
+        None
+        """
+        size = self.size().getInfo()
+
+        # Pulling min and max out of the stats is slightly faster than using `aggregate_min` and `aggregate_max` separately
+        stats = self.aggregate_stats("system:time_start")
+        start_millis = ee.Date(stats.get("min"))
+        end_millis = ee.Date(stats.get("max"))
+
+        start = start_millis.format("yyyy-MM-dd HH:mm:ss z").getInfo()
+        end = end_millis.format("yyyy-MM-dd HH:mm:ss z").getInfo()
+
+        mean_interval = self.interval().getInfo()
+
+        id = self.get("system:id").getInfo()
+
+        print(
+            f"\033[1m{id}\033[0m"
+            f"\n\tImages: {size:,}"
+            f"\n\tStart date: {start}"
+            f"\n\tEnd date: {end}"
+            f"\n\tMean interval: {mean_interval:.2f} {unit}s"
+        )
+
+    def dataframe(self, props: Union[None, List[str], ee.List] = None) -> pd.DataFrame:
+        """Generate a Pandas dataframe describing properties of each image in the time series.
+
+        Parameters
+        ----------
+        props : Union[List[str], ee.List], optional
+            A list of property names to aggregate from all images into the dataframe. If none is
+            provided, all non-system properties of the first image in the time series will be used.
+
+        Returns
+        -------
+        pd.DataFrame
+            A Pandas dataframe where each row represents an image and columns represent system properties.
+        """
+        if props is None:
+            props = self.first().propertyNames().getInfo()
+            props = [
+                p
+                for p in props
+                if not p.startswith("system:")
+                or p in ["system:time_start", "system:id"]
+            ]
+        elif isinstance(props, ee.List):
+            props = props.getInfo()
+
+        df_dict = {}
+        n = self.size().getInfo()
+        for prop in set(props):
+            vals = self.aggregate_array(prop).getInfo()
+            if len(vals) == 0:
+                raise MissingPropertyError(
+                    f"The property `{prop}` is missing from all images!"
+                )
+            elif len(vals) < n:
+                raise MissingPropertyError(
+                    f"The property `{prop}` is missing from some images!"
+                )
+            if prop.startswith("system:time"):
+                vals = map(_millis_to_datetime, vals)
+
+            df_dict[prop] = vals
+
+        collection_id = self.get("system:id").getInfo()
+        df = pd.DataFrame.from_dict(df_dict)
+        df.index.id = collection_id
+        return df
+
+    def timeline(self) -> "go.Figure":  # pragma: no cover
+        """Generate an interactive plot showing the acquisition time of each image in the time series.
+
+        Returns
+        -------
+        go.Figure
+            A Plotly graph object interactive plot showing the acquisition time of each image in the time series.
+        """
+        try:
+            import plotly.express as px  # type: ignore
+        except ImportError:
+            raise ImportError(
+                "The `plotly` package is required for this feature. "
+                "Please install it with `pip install plotly` and try again."
+            ) from None
+
+        df = self.dataframe(props=["system:id", "system:time_start"])
+        df["y"] = 0
+
+        fig = px.line(
+            df,
+            x="system:time_start",
+            y="y",
+            hover_name="system:id",
+            markers=True,
+            labels={"system:time_start": ""},
+        )
+
+        fig.update_traces(
+            customdata=df[["system:id", "system:time_start"]],
+            hovertemplate="<b>%{customdata[0]}</b>"
+            + "<br>%{customdata[1]|%Y-%m-%d %H:%M:%S}",
+            line=dict(width=2, color="black"),
+            marker=dict(
+                size=12,
+                symbol="line-ns-open",
+                color="grey",
+                line=dict(width=1, color="black"),
+            ),
+        )
+
+        # Add circles for each image
+        fig.add_trace(
+            go.Scatter(
+                x=df["system:time_start"],
+                y=df.y,
+                mode="markers",
+                hoverinfo="skip",
+                marker=dict(
+                    size=6,
+                    symbol="circle",
+                    color="white",
+                    line=dict(width=1, color="black"),
+                ),
+            )
+        )
+
+        fig.update_layout(
+            plot_bgcolor="white",
+            height=200,
+            hoverlabel=dict(bgcolor="white"),
+            showlegend=False,
+        )
+
+        fig.update_yaxes(visible=False)
+        fig.update_xaxes(linecolor="black", ticks="outside")
+
+        return fig
+
+    def aggregate_time(
+        self, frequency: str, reducer: Optional[Any] = None, keep_bandnames: bool = True
+    ) -> "TimeSeries":
+        """Aggregate the collection over the time dimension to a specified frequency. This method can only be used to go from
+        small time frequencies to larger time frequencies, such as hours to days, not vice-versa. If the resampling frequency is smaller
+        than the time between images, un-aggregated images will be returned.
+
+        Parameters
+        ----------
+        frequency : str
+            The time frequency to aggregate to. One of 'year', 'month' 'week', 'day', 'hour'.
+        reducer : ee.Reducer, optional
+            The reducer to apply when aggregating over time. If none is provided, ee.Reducer.mean() will be used.
+        keep_bandnames : bool, default True
+            If true, the band names of the input images will be kept in the aggregated images. If false, the name of the
+            reducer will be appended to the band names, e.g. SR_B4 will become SR_B4_mean.
+
+        Returns
+        -------
+        TimeSeries
+            The input image collection aggregated to the specified time frequency.
+
+        Raises
+        ------
+        ValueError
+            If an invalid frequency is passed.
+
+        Example
+        -------
+        >>> ts_hourly = wxee.TimeSeries("NOAA/NWS/RTMA")
+        >>> daily_max = ts_hourly.aggregate_time(frequency="day", reducer=ee.Reducer.max())
+        """
+        # ee.Reducer can't be used without initializing ee (see https://github.com/google/earthengine-api/issues/164),
+        # so set the default reducer explicitly. This is also why the type hint above is set to Any.
+        reducer = ee.Reducer.mean() if not reducer else reducer
+        original_id = self.get("system:id")
+
+        TimeFrequencyEnum.get_option(frequency)
+
+        def resample_step(start: ee.Date) -> ee.Image:
+            """Resample one time step in the given unit from a specified start time."""
+            start = ee.Date(start)
+            end = start.advance(1, frequency)
+            imgs = self.filterDate(start, end)
+            resampled = imgs.reduce(reducer)
+            resampled = resampled.copyProperties(
+                imgs.first(), imgs.first().propertyNames()
+            )
+            resampled = resampled.set(
+                {
+                    "system:time_start": imgs.first().get("system:time_start"),
+                    "system:time_end": imgs.wx.last().get("system:time_end"),
+                }
+            )
+
+            if keep_bandnames:
+                resampled = ee.Image(resampled).rename(imgs.first().bandNames())
+
+            # If the resampling step falls between images, just return null
+            return ee.Algorithms.If(imgs.size().gt(0), resampled, None)
+
+        start_times = self._generate_steps_at_frequency(frequency)
+
+        return TimeSeries(start_times.map(resample_step, dropNulls=True)).set(
+            "system:id", original_id
+        )
+
+    def _generate_steps_at_frequency(self, frequency: str) -> "ee.List[ee.Date]":
+        """Generate a list of start dates that would split the time series into a given frequency. For example, a time series of daily
+        data at monthly frequency would return the start date of monthly periods starting from the first day.
+
+        In the example above, this is done by calculating the number of months that cover the time series and iteratively advancing
+        that many steps from the start time of the time series. This means that if the time series does not start on the first day of
+        a month, the steps will not line up with calendar months but will instead represent month-long groups of contiguous days.
+
+        A minimum of 1 step will be returned even if the time series period is smaller than the frequency.
+        """
+        TimeFrequencyEnum.get_option(frequency)
+
+        n_steps = self.end_time.difference(self.start_time, frequency).floor()
+        steps = ee.List.sequence(0, n_steps)
+
+        return steps.map(lambda x: self.start_time.advance(x, frequency))
+
+    def _calculate_climatology(
+        self,
+        climatology_reducer: Optional[Any],
+        frequency: str,
+        reducer: Optional[Any] = None,
+        start: Optional[int] = None,
+        end: Optional[int] = None,
+        keep_bandnames: bool = True,
+    ) -> Climatology:
+        """Calculate a climatology image collection with a given frequency and reducer.
+
+        Parameters
+        ----------
+        climatology_reducer: Optional[ee.Reducer]
+            The climatological reducer to apply to aggregated images. In most cases, this will be ee.Reducer.mean
+            or ee.Reducer.stdDev for generating climatological means and standard deviations, respectively.
+        frequency : str
+            The name of the time frequency. One of "day", "month".
+        reducer : Optional[ee.Reducer]
+            The reducer to apply when aggregating over time, e.g. aggregating hourly data to daily for a daily
+            climatology. If the data is already in the temporal scale of the climatology, e.g. creating a daily
+            climatology from daily data, the reducer will have no effect.
+        start : Optional[int]
+            The start coordinate in the time frequency to include in the climatology, e.g. 1 for January if the
+            frequency is "month". If none is provided, the default will be 1 for both "day" and "month".
+        end : Optional[int]
+            The end coordinate in the time frequency to include in the climatology, e.g. 8 for August if the
+            frequency is "month". If none is provided, the default will be 366 for "day" or 12 for "month"
+        keep_bandnames : bool, default True
+            If true, the band names of the input images will be kept in the aggregated images. If false, the name of the
+            reducer will be appended to the band names, e.g. SR_B4 will become SR_B4_mean.
+
+        Returns
+        -------
+        wxee.climatology.Climatology
+            The climatological collection.
+        """
+        reducer = ee.Reducer.mean() if not reducer else reducer
+
+        freq = ClimatologyFrequencyEnum.get_option(frequency)
+        start = freq.start if not start else start
+        end = freq.end if not end else end
+        prop = f"wx:{frequency}"
+
+        def reduce_frequency(x: ee.String) -> Union[None, ee.Image]:
+            """Apply a mean reducer over a time frequency, returning None if no images fall within the time window.
+
+            Parameters
+            ----------
+            x : ee.String
+                The time coordinate to reduce, such as "1" for January.
+            """
+            imgs = collection.filterMetadata(prop, "equals", x)
+            reduced = imgs.reduce(climatology_reducer)
+            # Retrieve the time from the image instead of using x because I need a formatted
+            # string for concatenating into the system:id later.
+            coord = ee.Date(imgs.first().get("system:time_start")).format(
+                freq.date_format
+            )
+            reduced = reduced.set("wx:dimension", frequency, "wx:coordinate", coord)
+
+            geom = collection.geometry()
+            # Reducing makes images unbounded, so re-clip bounded images
+            reduced = ee.Algorithms.If(geom.isUnbounded(), reduced, reduced.clip(geom))
+
+            reduced = ee.Image(reduced).rename(imgs.first().bandNames())
+
+            return ee.Algorithms.If(imgs.size().gt(0), reduced, None)
+
+        collection = self.aggregate_time(freq.name, reducer, keep_bandnames)
+        collection = collection.map(
+            lambda img: img.set(
+                prop,
+                ee.Number.parse(
+                    ee.Date(ee.Image(img).get("system:time_start")).format(
+                        freq.date_format
+                    )
+                ),
+            )
+        )
+        coord_list = ee.List.sequence(start, end)
+
+        clim = Climatology(
+            coord_list.map(lambda x: reduce_frequency(x), dropNulls=True)
+        )
+
+        clim = clim.set("system:id", self.get("system:id"))
+        clim.frequency = freq
+        clim.start = start
+        clim.end = end
+        clim.reducer = reducer
+
+        return clim
+
+    def climatology_mean(
+        self,
+        frequency: str,
+        reducer: Optional[Any] = None,
+        start: Optional[int] = None,
+        end: Optional[int] = None,
+        keep_bandnames: bool = True,
+    ) -> Climatology:
+        """Calculate a mean climatology image collection with a given frequency.
+
+        Parameters
+        ----------
+        frequency : str
+            The name of the time frequency. One of "day", "month".
+        reducer : Optional[ee.Reducer]
+            The reducer to apply when aggregating over time, e.g. aggregating hourly data to daily for a daily
+            climatology. If the data is already in the temporal scale of the climatology, e.g. creating a daily
+            climatology from daily data, the reducer will have no effect.
+        start : Optional[int]
+            The start coordinate in the time frequency to include in the climatology, e.g. 1 for January if the
+            frequency is "month". If none is provided, the default will be 1 for both "day" and "month".
+        end : Optional[int]
+            The end coordinate in the time frequency to include in the climatology, e.g. 8 for August if the
+            frequency is "month". If none is provided, the default will be 366 for "day" or 12 for "month"
+        keep_bandnames : bool, default True
+            If true, the band names of the input images will be kept in the aggregated images. If false, the name of the
+            reducer will be appended to the band names, e.g. SR_B4 will become SR_B4_mean.
+
+        Returns
+        -------
+        wxee.climatology.Climatology
+            The climatological mean collection.
+
+        Example
+        -------
+        >>> collection = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET")
+        >>> collection = collection.filterDate("1980", "2000")
+        >>> ts = wxee.TimeSeries(collection)
+        >>> daily_max = ts.climatology_mean(frequency="day", reducer=ee.Reducer.max())
+        >>> daily_max.size().getInfo()
+        366
+        """
+        mean_clim = self._calculate_climatology(
+            ee.Reducer.mean(), frequency, reducer, start, end, keep_bandnames
+        )
+        mean_clim.statistic = "mean"
+
+        return mean_clim
+
+    def climatology_std(
+        self,
+        frequency: str,
+        reducer: Optional[Any] = None,
+        start: Optional[int] = None,
+        end: Optional[int] = None,
+        keep_bandnames: bool = True,
+    ) -> Climatology:
+        """Calculate a standard deviation climatology image collection with a given frequency.
+
+        Parameters
+        ----------
+        frequency : str
+            The name of the time frequency. One of "day", "month".
+        reducer : Optional[ee.Reducer]
+            The reducer to apply when aggregating over time, e.g. aggregating hourly data to daily for a daily
+            climatology. If the data is already in the temporal scale of the climatology, e.g. creating a daily
+            climatology from daily data, the reducer will have no effect.
+        start : Optional[int]
+            The start coordinate in the time frequency to include in the climatology, e.g. 1 for January if the
+            frequency is "month". If none is provided, the default will be 1 for both "day" and "month".
+        end : Optional[int]
+            The end coordinate in the time frequency to include in the climatology, e.g. 8 for August if the
+            frequency is "month". If none is provided, the default will be 366 for "day" or 12 for "month"
+        keep_bandnames : bool, default True
+            If true, the band names of the input images will be kept in the aggregated images. If false, the name of the
+            reducer will be appended to the band names, e.g. SR_B4 will become SR_B4_stdDev.
+
+        Returns
+        -------
+        wxee.climatology.Climatology
+            The climatological standard deviation collection.
+
+        Example
+        -------
+        >>> collection = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET")
+        >>> collection = collection.filterDate("1980", "2000")
+        >>> ts = wxee.TimeSeries(collection)
+        >>> daily_max = ts.climatology_std(frequency="day", reducer=ee.Reducer.max())
+        >>> daily_max.size().getInfo()
+        366
+        """
+        mean_clim = self._calculate_climatology(
+            ee.Reducer.stdDev(), frequency, reducer, start, end, keep_bandnames
+        )
+        mean_clim.statistic = "standard deviation"
+
+        return mean_clim
+
+    def climatology_anomaly(
+        self,
+        mean: Climatology,
+        std: Optional[Climatology] = None,
+        keep_bandnames: bool = True,
+    ) -> "TimeSeries":
+        """Calculate climatological anomalies for the time series. The frequency and reducer will be the same as those
+        used in the :code:`mean` climatology. Standardized anomalies can be calculated by providing a climatological standard
+        deviation as :code:`std`.
+
+        A climatological anomaly is calculated as the difference between the climatological mean and a given observation.
+        For standardized anomalies, that difference is divided by the climatological standard deviation. Standardized
+        anomalies represent unitless measurements of how many standard deviations an observation was from the climatological
+        mean, and therefore allow easy comparisons between variables.
+
+        Note
+        ----
+        Climatological anomalies are generally calculated using long-term climatological normals (e.g. 30 years). If
+        the climatological mean and standard deviation represent a shorter period, interpretation of results may vary.
+
+        Parameters
+        ----------
+        mean : Climatology
+            The long-term climatological mean to calculate anomalies from. The climatological frequency and reducer will
+            be determined from this climatology.
+        std : Optional[Climatology]
+            The long-term climatological standard deviation to calculate anomalies from. If provided, standardized
+            climatological anomalies will be calculated. The climatological standard deviation frequency and reducer must
+            match the frequency and reducer used by the climatological mean.
+        keep_bandnames : bool, default True
+            If true, the band names of the input images will be kept in the aggregated images. If false, the name of the
+            reducer will be appended to the band names, e.g. SR_B4 will become SR_B4_mean.
+
+        Returns
+        -------
+        wxee.time_series.TimeSeries
+            Climatological anomalies within the TimeSeries period.
+
+        Raises
+        ------
+        ValueError
+            If the :code:`std` frequency or reducer do not match the :code:`mean` frequency or reducer. Only applies if
+            a :code:`std` is provided.
+
+        Example
+        -------
+        >>> collection = wxee.TimeSeries("IDAHO_EPSCOR/GRIDMET")
+        >>> reference = collection.filterDate("1980", "2010")
+        >>> mean = reference.climatology_mean("month")
+        >>> std = reference.climatology_std("month")
+        >>> observation = collection.filterDate("2020", "2021")
+        >>> anomaly = observation.climatology_anomaly(mean, std)
+        """
+        reducer = mean.reducer
+        freq = mean.frequency
+
+        if std:
+            if std.frequency != freq:
+                raise ValueError(
+                    f"Mean frequency '{mean.frequency.name}' does not match std frequency '{std.frequency.name}'."
+                )
+            if std.reducer != mean.reducer:
+                # There is no way to determine the type of reducer used after the fact, or else I would list them.
+                raise ValueError(f"Mean reducer does not match std reducer.")
+
+        def image_anomaly(img: ee.Image) -> ee.Image:
+            """Identify the climatological mean and std deviation for a given image
+            and use them to calculate and return the anomaly.
+            """
+            # Get the climatological coordinate of the image
+            coord = ee.Date(ee.Image(img).get("system:time_start")).format(
+                freq.date_format
+            )
+
+            # Get the climatological mean at that coordinate
+            coord_mean = mean.filterMetadata("wx:coordinate", "equals", coord)
+
+            anom = img.subtract(coord_mean.first())
+
+            # If a standard deviation is provided, standardize the anomalies
+            if std:
+                coord_std = std.filterMetadata("wx:coordinate", "equals", coord)
+                anom = anom.divide(coord_std.first())
+
+            anom = anom.copyProperties(img, img.propertyNames())
+
+            # This permits sparse mean and std climatologies, e.g. those with a start and end set.
+            return ee.Algorithms.If(coord_mean.size().gt(0), anom, None)
+
+        collection = self.aggregate_time(freq.name, reducer, keep_bandnames)
+
+        return collection.map(image_anomaly, opt_dropNulls=True)
+
+    def interpolate_time(self, time: ee.Date, method: str = "linear") -> ee.Image:
+        """Use interpolation to synthesize data at a given time within the time series. Based on the
+        interpolation method chosen, a certain number of images must be present in the time series
+        before and after the target date.
+
+        Nearest and linear interpolation require 1 image before and after the selected time while
+        cubic interpolation requires 2 images before and after the selected time.
+
+        Parameters
+        ----------
+        date : ee.Date
+            The target date to interpolate data at. This must be within the time series period.
+        method : str, default linear
+            The interpolation method to use, one of "nearest", "linear", or "cubic".
+
+        Returns
+        -------
+        ee.Image
+            Data interpolated to the target time from surrounding data in the time series.
+
+        Examples
+        --------
+        >>> ts = wxee.TimeSeries("IDAHO_EPSCOR/GRIDMET")
+        >>> target_date = ee.Date("2020-09-08T03")
+
+        Interpolate weather data at the target date using cubic interpolation.
+
+        >>> filled = ts.interpolate(target_date, "cubic")
+        """
+        method_func = InterpolationMethodEnum.get_option(method)
+
+        y1, y0 = self._get_n_images_before(time, 2)
+        y2, y3 = self._get_n_images_after(time, 2)
+
+        x1, x2 = [ee.Number(img.get("system:time_start")) for img in [y1, y2]]
+        mu = _normalize(time.millis(), ee.Date(x1).millis(), ee.Date(x2).millis())
+
+        if method in ["nearest", "linear"]:
+            interpolated = method_func(y1, y2, mu)
+        elif method == "cubic":
+            interpolated = method_func(y0, y1, y2, y3, mu)
+
+        interpolated = interpolated.set("system:time_start", time.millis())
+
+        return interpolated
+
+    def _get_n_images_before(self, date: ee.Date, n: int) -> List[ee.Image]:
+        """Get n images before a given date (inclusive) in the time series. The images will be selected
+        and returned in a list in order of their proximity to the target date."""
+        before_imgs = self.filterDate(self.start_time, date.advance(1, "second")).sort(
+            "system:time_start", opt_ascending=False
+        )
+        before_list = before_imgs.toList(n)
+
+        return [ee.Image(before_list.get(i)) for i in range(n)]
+
+    def _get_n_images_after(self, date: ee.Date, n: int) -> List[ee.Image]:
+        """Get n images after a given date (inclusive) in the time series. The images will be selected
+        and returned in order of their proximity to the target date."""
+        after_imgs = self.filterDate(date, self.end_time.advance(1, "second")).sort(
+            "system:time_start", opt_ascending=True
+        )
+        after_list = after_imgs.toList(n)
+
+        return [ee.Image(after_list.get(i)) for i in range(n)]
+
+    def insert_image(self, img: ee.Image) -> "TimeSeries":
+        """Insert an image into the time series and sort it by :code:`system:time_start`.
+
+        Parameters
+        ----------
+        img : ee.Image
+            The image to insert.
+
+        Returns
+        -------
+        wxee.TimeSeries
+            The time series with the image inserted in time order
+        """
+        merged = self.merge(ee.ImageCollection(img)).sort("system:time_start")
+        merged = ee.ImageCollection(merged.copyProperties(self, self.propertyNames()))
+        return merged.wx.to_time_series()
+
+    def rolling_time(
+        self,
+        window: int,
+        unit: str,
+        align: str = "left",
+        min_observations: int = 1,
+        reducer: Optional[Any] = None,
+        keep_bandnames: bool = True,
+    ) -> "TimeSeries":
+        """Apply a rolling reducer over the time dimension. Rolling windows are calculated around each image,
+        so if images are irregularly spaced in time, the windows will be as well. As long as the minimum
+        observations are met in each window, the output time series will contain the same number of images as
+        the input, with each image reduced over its surrounding window.
+
+        Parameters
+        ----------
+        window : int
+            The number of time units to include in each rolling period.
+        unit : str
+            The time frequency of the window. One of "hour", "day", "week", "month", "year".
+        align : str, default "left"
+            The start location of the rolling window, relative to the primary image time. One of "left", "center",
+            "right". For example, a 3-day left-aligned window will include all images up to (but not including)
+            3 days prior to the primary image. Date ranges are exclusive in the alignment direction and inclusive
+            in the opposite direction, so each primary image will be included in its own window.
+        min_observations : int, default 1
+            The minimum number of images to include in the rolling window (counting the primary image). If the
+            minimum observations are not met, the primary image will be dropped. For example, a monthly time series
+            reduced with a 10 day window and :code:`min_observations==3` would be empty because none of the
+            windows would include enough observations.
+        reducer : Optional[ee.Reducer]
+            The reducer to apply to each rolling window. If none is given, ee.Reducer.mean will be used.
+        keep_bandnames : bool, default True
+            If true, the band names of the input images will be kept in the reduced images. If false, the name of the
+            reducer will be appended to the band names, e.g. SR_B4 will become SR_B4_mean.
+
+        Returns
+        -------
+        wxee.time_series.TimeSeries
+            The time series with the rolling reducer applied to each image.
+
+        Example
+        -------
+        >>> ts = wxee.TimeSeries("MODIS/006/MOD13A2)
+        >>> ts_smooth = ts.rolling_time(90, "day", "center", reducer=ee.Reducer.median())
+        """
+        reducer = ee.Reducer.mean() if not reducer else reducer
+
+        def roll_image(img: ee.Image) -> ee.Image:
+            """Apply a rolling reducer to a single image using its temporal neighbors"""
+            center = ee.Date(img.get("system:time_start"))
+            neighbors = self._get_window(center, window, unit, align)
+            smooth = neighbors.reduce(reducer)
+
+            props = {
+                "wx:window_size": window,
+                "wx:window_unit": unit,
+                "wx:window_align": align,
+                "wx:window_includes": neighbors.size(),
+            }
+            smooth = ee.Image(
+                smooth.copyProperties(img, img.propertyNames()).set(props)
+            )
+
+            if keep_bandnames:
+                smooth = smooth.rename(img.bandNames())
+
+            return ee.Algorithms.If(neighbors.size().lt(min_observations), None, smooth)
+
+        return self.map(roll_image, opt_dropNulls=True)
+
+    def fill_gaps(
+        self,
+        window: int,
+        unit: str,
+        align: str = "center",
+        reducer: Optional[Any] = None,
+        fill_value: Optional[float] = None,
+    ) -> "TimeSeries":
+        """Apply gap-filling using a moving window reducer through time. Each image is unmasked using its reduced temporal neighbors.
+        If the window is not wide enough to include an unmasked value (e.g. if clouds occur in the same location in all images),
+        masked values will remain unless a :code:`fill_value` is specified.
+
+        Parameters
+        ----------
+        window : int
+            The number of time units to include in each rolling period.
+        unit : str
+            The time frequency of the window. One of "hour", "day", "week", "month", "year".
+        align : str, default "center"
+            The start location of the rolling window, relative to the primary image time. One of "left", "center",
+            "right". For example, a 3-day left-aligned window will include all images up to (but not including)
+            3 days prior to the primary image. Date ranges are exclusive in the alignment direction and inclusive
+            in the opposite direction, so each primary image will be included in its own window.
+        reducer : Optional[ee.Reducer]
+            The reducer to apply to each rolling window. If none is given, ee.Reducer.mean will be used.
+        fill_value : float
+            The value to fill any masked values with after applying initial gap-filling. If none is given, masked
+            values may remain if the window size is not large enough.
+
+        Returns
+        -------
+        wxee.time_series.TimeSeries
+            The time series with each image unmasked using its reduced neighbors.
+
+        Example
+        -------
+        >>> ts = wxee.TimeSeries("MODIS/006/MOD13A2)
+        >>> ts_filled = ts.fill_gaps(90, "day", "center", reducer=ee.Reducer.median())
+        """
+        reducer = ee.Reducer.mean() if not reducer else reducer
+
+        def fill_image(img: ee.Image) -> ee.Image:
+            """Unmask a single image by applying a rolling reducer to its temporal neighbors."""
+            center = ee.Date(img.get("system:time_start"))
+            neighbors = self._get_window(center, window, unit, align)
+            filler = neighbors.reduce(reducer)
+
+            filled = img.unmask(filler)
+            filled = filled.unmask(fill_value) if fill_value else filled
+
+            return filled
+
+        return self.map(fill_image)
+
+    def _get_window(
+        self, time: ee.Date, window: int, unit: str, align: str = "left"
+    ) -> "TimeSeries":
+        """Get all images within a window around a target date.
+
+        Parameters
+        ----------
+        time : ee.Date
+            The center date of the window.
+        window : int
+            The number of time units to include in the window.
+        unit : str
+            The time frequency of the window. One of "hour", "day", "week", "month", "year".
+        align : str, default "left"
+            The start location of the window, relative to the center time. One of "left", "center", "right". Date
+            ranges are exclusive in the alignment direction and inclusive in the opposite direction, so the center
+            date of the window is always included.
+
+        Returns
+        -------
+        wxee.time_series.TimeSeries
+            A time series containing all images in the window.
+        """
+        WindowAlignEnum.get_option(align)
+
+        offset = 1 if align == "left" else 0.5 if align == "center" else 0
+        nudge = 1 if align == "left" else 0 if align == "center" else -1
+
+        # The windows need to be nudged slightly to set the correct exclusive/inclusive order.
+        # For example, a left aligned window should exclude the left and include the right,
+        # and vice-versa for a right aligned window.
+        left = time.advance(window * offset * -1, unit).advance(nudge, "second")
+        right = left.advance(window, unit)
+
+        return self.filterDate(left, right)
```

### Comparing `wxee-0.4.0/wxee/utils.py` & `wxee-0.4.1/wxee/utils.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,250 +1,255 @@
-import contextlib
-import datetime
-import itertools
-import os
-import tempfile
-import warnings
-from typing import Any, List, Tuple, Union
-from zipfile import ZipFile
-
-import ee  # type: ignore
-import joblib  # type: ignore
-import rasterio  # type: ignore
-import requests
-import rioxarray  # type: ignore
-import xarray as xr
-from requests.adapters import HTTPAdapter
-from tqdm.auto import tqdm  # type: ignore
-from urllib3.util.retry import Retry
-
-
-def Initialize(**kwargs: Any) -> None:
-    """Initialize Earth Engine using the high-volume endpoint designed for automated requests.
-
-    Parameters
-    ----------
-    kwargs : Any
-        Additional keyword arguments passed to ee.Initialize().
-    """
-    ee.Initialize(opt_url="https://earthengine-highvolume.googleapis.com", **kwargs)
-
-
-def _set_nodata(file: str, nodata: Union[float, int]) -> None:
-    """Set the nodata value in the metadata of an image file.
-
-    Parameters
-    ----------
-    file : str
-        The path to the raster file to set.
-    nodata : Union[float, int]
-        The value to set as nodata.
-    """
-    with rasterio.open(file, "r+") as img:
-        img.nodata = nodata
-
-
-def _flatten_list(a: List[Any]) -> List[Any]:
-    """Flatten a nested list."""
-    return list(itertools.chain.from_iterable(a))
-
-
-def _unpack_file(file: str, out_dir: str) -> List[str]:
-    """Unpack a ZIP file to a directory.
-
-    Parameters
-    ----------
-    file : str
-        The path to a ZIP file.
-    out_dir : str
-        The path to a directory to unpack files within.
-
-    Returns
-    -------
-    List[str]
-        Paths to the unpacked files.
-    """
-    unzipped = []
-
-    with ZipFile(file, "r") as zipped:
-        unzipped += zipped.namelist()
-        zipped.extractall(out_dir)
-
-    return [os.path.join(out_dir, file) for file in unzipped]
-
-
-def _download_url(url: str, out_dir: str, progress: bool, max_attempts: int) -> str:
-    """Download a file from a URL to a specified directory.
-
-    Parameters
-    ----------
-    url : str
-        The URL address of the element to download.
-    out_dir : str
-        The directory path to save the temporary file to.
-    progress : bool
-        If true, a progress bar will be displayed to track download progress.
-    max_attempts : int
-        The maximum number of times to retry a connection.
-
-    Returns
-    -------
-    str
-        The path to the downloaded file.
-    """
-    filename = tempfile.NamedTemporaryFile(mode="w+b", dir=out_dir, delete=False).name
-    r = _create_retry_session(max_attempts).get(url, stream=True)
-
-    try:
-        r.raise_for_status()
-    except Exception as e:
-        # Delete the tempfile if it could not be downloaded
-        os.remove(filename)
-        raise e
-
-    file_size = int(r.headers.get("content-length", 0))
-
-    with open(filename, "w+b") as dst, tqdm(
-        total=file_size,
-        unit="iB",
-        unit_scale=True,
-        unit_divisor=1024,
-        desc="Downloading",
-        disable=not progress,
-    ) as bar:
-        for data in r.iter_content(chunk_size=1024):
-            size = dst.write(data)
-            bar.update(size)
-
-    return filename
-
-
-def _create_retry_session(max_attempts: int) -> requests.Session:
-    """Create a session with automatic retries.
-
-    https://www.peterbe.com/plog/best-practice-with-retries-with-requests
-    """
-    session = requests.Session()
-    retry = Retry(
-        total=max_attempts, read=max_attempts, connect=max_attempts, backoff_factor=0.1
-    )
-
-    adapter = HTTPAdapter(max_retries=retry)
-
-    session.mount("http://", adapter)
-    session.mount("https://", adapter)
-
-    return session
-
-
-def _dataset_from_files(files: List[str], masked: bool, nodata: int) -> xr.Dataset:
-    """Create an xarray.Dataset from a list of raster files."""
-    das = [_dataarray_from_file(file, masked, nodata) for file in files]
-
-    try:
-        # Allow conflicting values if one is null, take the non-null value
-        merged = xr.merge(das, compat="no_conflicts")
-    except xr.core.merge.MergeError:
-        # If non-null conflicting values occur, take the first value and warn the user
-        merged = xr.merge(das, compat="override")
-        warnings.warn(
-            "Different non-null values were encountered for the same variable at the same time coordinate. The first value was taken."
-        )
-
-    return merged
-
-
-def _dataarray_from_file(file: str, masked: bool, nodata: int) -> xr.DataArray:
-    """Create an xarray.DataArray from a single file by parsing datetimes and variables from the file name.
-
-    The file name must follow the format "{dimension}.{coordinate}.{variable}.{extension}".
-    """
-    da = rioxarray.open_rasterio(file)
-    dim, coord, var = _parse_filename(file)
-
-    da = da.expand_dims({dim: [coord]}).rename(var).squeeze("band").drop_vars("band")
-
-    # Mask the nodata values. This will convert int datasets to float.
-    if masked:
-        da = da.where(da != nodata)
-
-    return da
-
-
-def _parse_filename(file: str) -> Tuple[str, Union[str, int, datetime.datetime], str]:
-    """Parse the dimension, coordinate, and variable from a filename following the format
-    {id}.{dimension}.{coordinate}.{variable}.{extension}. Return as a tuple.
-    """
-    coord: Union[str, int, datetime.datetime]
-
-    basename = os.path.basename(file)
-    dim, coord_name, variable = basename.split(".")[1:4]
-    if dim == "time":
-        coord = _parse_time(coord_name)
-    else:
-        coord = int(coord_name)
-
-    return (dim, coord, variable)
-
-
-def _parse_time(time: str) -> Union[datetime.datetime, str]:
-    """Parse a time string as it is exported from Earth Engine and return as a datetime.
-    If the time cannot be parsed, it is returned as a string.
-    """
-    try:
-        return datetime.datetime.strptime(time, "%Y%m%dT%H%M%S")
-    except ValueError:
-        warnings.warn(
-            f"The time coordinate '{time}' could not be parsed into a valid datetime. Setting as raw value instead."
-        )
-        return time
-
-
-def _millis_to_datetime(millis: str) -> datetime.datetime:
-    """Convert a timestamp in UTC milliseconds (e.g. from Earth Engine) to a datetime object."""
-    return datetime.datetime.utcfromtimestamp(int(millis) / 1000.0)
-
-
-def _replace_if_null(val: Union[ee.String, ee.Number], replacement: Any) -> Any:
-    """Take an Earth Engine object and return either the original non-null object or the given replacement if it is null."""
-    return ee.Algorithms.If(val, val, replacement)
-
-
-def _format_date(d: ee.Date) -> ee.String:
-    """Format a date using a consistent pattern."""
-    return ee.Date(d).format("yyyyMMdd'T'HHmmss")
-
-
-@contextlib.contextmanager
-def parallel_tqdm(tqdm_object: tqdm) -> tqdm:
-    """Context manager to patch joblib to report into tqdm progress bar given as argument
-
-    Reference
-    ---------
-    https://stackoverflow.com/questions/24983493/tracking-progress-of-joblib-parallel-execution
-
-    Example
-    -------
-    >>> with Parallel(n_jobs=-1) as p:
-    >>>     with parallel_tqdm(tqdm(desc="Progress", total=10)):
-    >>>         urls = p(delayed(f)(x) for x in range(10))
-    """
-
-    class TqdmBatchCompletionCallback(joblib.parallel.BatchCompletionCallBack):
-        def __init__(self, *args: Any, **kwargs: Any) -> None:
-            super().__init__(*args, **kwargs)
-
-        def __call__(self, *args: Any, **kwargs: Any) -> None:
-            tqdm_object.update(n=self.batch_size)
-            return super().__call__(*args, **kwargs)
-
-    old_batch_callback = joblib.parallel.BatchCompletionCallBack
-    joblib.parallel.BatchCompletionCallBack = TqdmBatchCompletionCallback
-    try:
-        yield tqdm_object
-    finally:
-        joblib.parallel.BatchCompletionCallBack = old_batch_callback
-        tqdm_object.close()
-
-
-def _normalize(x: ee.Number, minx: ee.Number, maxx: ee.Number) -> ee.Number:
-    return ee.Number(x).subtract(minx).divide(ee.Number(maxx).subtract(minx))
+import contextlib
+import datetime
+import itertools
+import os
+import tempfile
+import warnings
+from typing import Any, List, Tuple, Union
+from zipfile import ZipFile
+
+import ee  # type: ignore
+import joblib  # type: ignore
+import rasterio  # type: ignore
+import requests
+import rioxarray  # type: ignore
+import xarray as xr
+from requests.adapters import HTTPAdapter
+from tqdm.auto import tqdm  # type: ignore
+from urllib3.util.retry import Retry
+
+
+def Initialize(**kwargs: Any) -> None:
+    """Initialize Earth Engine using the high-volume endpoint designed for automated requests.
+
+    Parameters
+    ----------
+    kwargs : Any
+        Additional keyword arguments passed to ee.Initialize().
+    """
+    ee.Initialize(opt_url="https://earthengine-highvolume.googleapis.com", **kwargs)
+
+
+def _set_nodata(file: str, nodata: Union[float, int]) -> None:
+    """Set the nodata value in the metadata of an image file.
+
+    Parameters
+    ----------
+    file : str
+        The path to the raster file to set.
+    nodata : Union[float, int]
+        The value to set as nodata.
+    """
+    with rasterio.open(file, "r+") as img:
+        img.nodata = nodata
+
+
+def _flatten_list(a: List[Any]) -> List[Any]:
+    """Flatten a nested list."""
+    return list(itertools.chain.from_iterable(a))
+
+
+def _unpack_file(file: str, out_dir: str) -> List[str]:
+    """Unpack a ZIP file to a directory.
+
+    Parameters
+    ----------
+    file : str
+        The path to a ZIP file.
+    out_dir : str
+        The path to a directory to unpack files within.
+
+    Returns
+    -------
+    List[str]
+        Paths to the unpacked files.
+    """
+    unzipped = []
+
+    with ZipFile(file, "r") as zipped:
+        unzipped += zipped.namelist()
+        zipped.extractall(out_dir)
+
+    return [os.path.join(out_dir, file) for file in unzipped]
+
+
+def _download_url(url: str, out_dir: str, progress: bool, max_attempts: int) -> str:
+    """Download a file from a URL to a specified directory.
+
+    Parameters
+    ----------
+    url : str
+        The URL address of the element to download.
+    out_dir : str
+        The directory path to save the temporary file to.
+    progress : bool
+        If true, a progress bar will be displayed to track download progress.
+    max_attempts : int
+        The maximum number of times to retry a connection.
+
+    Returns
+    -------
+    str
+        The path to the downloaded file.
+    """
+    filename = tempfile.NamedTemporaryFile(mode="w+b", dir=out_dir, delete=False).name
+    r = _create_retry_session(max_attempts).get(url, stream=True)
+
+    try:
+        r.raise_for_status()
+    except Exception as e:
+        # Delete the tempfile if it could not be downloaded
+        os.remove(filename)
+        raise e
+
+    file_size = int(r.headers.get("content-length", 0))
+
+    with open(filename, "w+b") as dst, tqdm(
+        total=file_size,
+        unit="iB",
+        unit_scale=True,
+        unit_divisor=1024,
+        desc="Downloading",
+        disable=not progress,
+    ) as bar:
+        for data in r.iter_content(chunk_size=1024):
+            size = dst.write(data)
+            bar.update(size)
+
+    return filename
+
+
+def _create_retry_session(max_attempts: int) -> requests.Session:
+    """Create a session with automatic retries.
+
+    https://www.peterbe.com/plog/best-practice-with-retries-with-requests
+    """
+    session = requests.Session()
+    retry = Retry(
+        total=max_attempts, read=max_attempts, connect=max_attempts, backoff_factor=0.1
+    )
+
+    adapter = HTTPAdapter(max_retries=retry)
+
+    session.mount("http://", adapter)
+    session.mount("https://", adapter)
+
+    return session
+
+
+def _dataset_from_files(files: List[str], masked: bool, nodata: int) -> xr.Dataset:
+    """Create an xarray.Dataset from a list of raster files."""
+    das = [_dataarray_from_file(file, masked, nodata) for file in files]
+
+    try:
+        # Allow conflicting values if one is null, take the non-null value
+        merged = xr.merge(das, compat="no_conflicts")
+    except xr.core.merge.MergeError:
+        # If non-null conflicting values occur, take the first value and warn the user
+        merged = xr.merge(das, compat="override")
+        warnings.warn(
+            "Different non-null values were encountered for the same variable at the same time coordinate. The first value was taken."
+        )
+
+    return merged
+
+
+def _dataarray_from_file(file: str, masked: bool, nodata: int) -> xr.DataArray:
+    """Create an xarray.DataArray from a single file by parsing datetimes and variables from the file name.
+
+    The file name must follow the format "{dimension}.{coordinate}.{variable}.{extension}".
+    """
+    with rioxarray.open_rasterio(file) as da:
+        # Load fully into memory rather than reading lazily from disk. This is needed to allow reading from tempfiles
+        # that will be deleted after the function returns. See https://github.com/corteva/rioxarray/issues/485 and
+        # https://github.com/aazuspan/wxee/issues/70.
+        da.load()
+
+    dim, coord, var = _parse_filename(file)
+
+    da = da.expand_dims({dim: [coord]}).rename(var).squeeze("band").drop_vars("band")
+
+    # Mask the nodata values. This will convert int datasets to float.
+    if masked:
+        da = da.where(da != nodata)
+
+    return da
+
+
+def _parse_filename(file: str) -> Tuple[str, Union[str, int, datetime.datetime], str]:
+    """Parse the dimension, coordinate, and variable from a filename following the format
+    {id}.{dimension}.{coordinate}.{variable}.{extension}. Return as a tuple.
+    """
+    coord: Union[str, int, datetime.datetime]
+
+    basename = os.path.basename(file)
+    dim, coord_name, variable = basename.split(".")[1:4]
+    if dim == "time":
+        coord = _parse_time(coord_name)
+    else:
+        coord = int(coord_name)
+
+    return (dim, coord, variable)
+
+
+def _parse_time(time: str) -> Union[datetime.datetime, str]:
+    """Parse a time string as it is exported from Earth Engine and return as a datetime.
+    If the time cannot be parsed, it is returned as a string.
+    """
+    try:
+        return datetime.datetime.strptime(time, "%Y%m%dT%H%M%S")
+    except ValueError:
+        warnings.warn(
+            f"The time coordinate '{time}' could not be parsed into a valid datetime. Setting as raw value instead."
+        )
+        return time
+
+
+def _millis_to_datetime(millis: str) -> datetime.datetime:
+    """Convert a timestamp in UTC milliseconds (e.g. from Earth Engine) to a datetime object."""
+    return datetime.datetime.utcfromtimestamp(int(millis) / 1000.0)
+
+
+def _replace_if_null(val: Union[ee.String, ee.Number], replacement: Any) -> Any:
+    """Take an Earth Engine object and return either the original non-null object or the given replacement if it is null."""
+    return ee.Algorithms.If(val, val, replacement)
+
+
+def _format_date(d: ee.Date) -> ee.String:
+    """Format a date using a consistent pattern."""
+    return ee.Date(d).format("yyyyMMdd'T'HHmmss")
+
+
+@contextlib.contextmanager
+def parallel_tqdm(tqdm_object: tqdm) -> tqdm:
+    """Context manager to patch joblib to report into tqdm progress bar given as argument
+
+    Reference
+    ---------
+    https://stackoverflow.com/questions/24983493/tracking-progress-of-joblib-parallel-execution
+
+    Example
+    -------
+    >>> with Parallel(n_jobs=-1) as p:
+    >>>     with parallel_tqdm(tqdm(desc="Progress", total=10)):
+    >>>         urls = p(delayed(f)(x) for x in range(10))
+    """
+
+    class TqdmBatchCompletionCallback(joblib.parallel.BatchCompletionCallBack):
+        def __init__(self, *args: Any, **kwargs: Any) -> None:
+            super().__init__(*args, **kwargs)
+
+        def __call__(self, *args: Any, **kwargs: Any) -> None:
+            tqdm_object.update(n=self.batch_size)
+            return super().__call__(*args, **kwargs)
+
+    old_batch_callback = joblib.parallel.BatchCompletionCallBack
+    joblib.parallel.BatchCompletionCallBack = TqdmBatchCompletionCallback
+    try:
+        yield tqdm_object
+    finally:
+        joblib.parallel.BatchCompletionCallBack = old_batch_callback
+        tqdm_object.close()
+
+
+def _normalize(x: ee.Number, minx: ee.Number, maxx: ee.Number) -> ee.Number:
+    return ee.Number(x).subtract(minx).divide(ee.Number(maxx).subtract(minx))
```

### Comparing `wxee-0.4.0/wxee/xarray.py` & `wxee-0.4.1/wxee/xarray.py`

 * *Ordering differences only*

 * *Files 20% similar despite different names*

```diff
@@ -1,136 +1,136 @@
-from typing import Any, List, Optional
-
-import xarray as xr
-
-
-@xr.register_dataset_accessor("wx")
-class DatasetAccessor:
-    def __init__(self, obj: xr.Dataset):
-        self._obj = obj
-
-    def rgb(
-        self,
-        bands: Optional[List[str]] = None,
-        stretch: float = 1.0,
-        interactive: bool = False,
-        **kwargs: Any,
-    ) -> Any:
-        """Generate an RGB color composite plot of the Dataset.
-
-        Parameters
-        ----------
-        bands : List[str], optional
-            A list of 3 data variable names to use as the red, green, and blue channels. If none is provided, the
-            first three data variables will be used in order.
-        stretch : float, default 1.0
-            A percentile stretch to apply to pixel values, between 0.0 and 1.0.
-        interactive : bool, default False
-            If False, a static plot is returned, faceted over the time dimension. If True, an interactive plot is
-            returned over the time dimension. interactive plots require the `hvplot` library to be installed
-            independently.
-        **kwargs
-            Keyword arguments passed to the plotting function. For static plots, arguments are passed to
-            :code:`xarray.Dataset.plot.imshow`. For interactive plots, arguments are passed to :code:`xarray.Dataset.hvplot.rgb`.
-
-        Returns
-        -------
-        Union[xarray.plot.facetgrid.FacetGrid, HoloViews object]
-            The RGB plot, either static or interactive.
-
-        Raises
-        ------
-        ValueError
-            If an incorrect number of bands are found, whether explicitly passed through the `bands` argument or
-            implicitly identified from the data variables.
-
-        ImportError
-            If the `interactive` argument is True and the `hvplot` package is not installed.
-
-        Examples
-        --------
-        Download one month of Sentinel-2 imagery over a point.
-
-        >>> pt = ee.Geometry.Point([5.40432,44.11541])
-        >>> ts = wxee.TimeSeries("COPERNICUS/S2_SR")
-        >>> ts = ts.filterDate("2020-07", "2020-08").filterBounds(pt)
-        >>> ds = ts.wx.to_xarray(region=pt.buffer(1000), scale=20)
-
-        Generate a static plot of the images as a true color composite. The col_wrap argument will be passed to
-        the plotting function.
-
-        >>> ds.wx.rgb(bands=["B4", "B3", "B2"], stretch=0.85, col_wrap=4)
-
-        Generate an interactive plot using a near-infrared false color composite. The aspect argument will be passed
-        to the plotting function.
-
-        >>> ds.wx.rgb(bands=["B8", "B4", "B3"], stretch=0.85, interactive=True, aspect=1.2)
-        """
-        if bands is not None:
-            if len(bands) != 3:
-                raise ValueError(f"Bands must be a list with exactly 3 names.")
-        else:
-            bands = list(self._obj.var())[:3]  # type: ignore
-
-            # Raise a different error if the bands were identified implicitly to avoid confusion
-            if len(bands) != 3:  # type: ignore
-                raise ValueError(
-                    f"The Dataset must contain at least 3 data variables for RGB plotting."
-                )
-
-        da = self._obj[bands].to_array(name="rgb")
-
-        da = da.wx.normalize(stretch)
-
-        if interactive:
-            try:
-                import hvplot.xarray  # type: ignore
-            except ImportError:
-                raise ImportError(
-                    "The `hvplot` package is required for interactive plots. Run `pip install hvplot`."
-                ) from None
-
-            default_kwargs = {
-                "groupby": "time",
-                "widget_location": "bottom",
-                "widget_type": "scrubber",
-            }
-            return da.hvplot.rgb(
-                x="x", y="y", bands="variable", **{**default_kwargs, **kwargs}
-            )
-
-        default_kwargs = {"col": "time"}
-        return da.plot.imshow(**{**default_kwargs, **kwargs})
-
-
-@xr.register_dataarray_accessor("wx")
-class DataArrayAccessor:
-    def __init__(self, obj: xr.DataArray):
-        self._obj = obj
-
-    def normalize(self, stretch: float = 1.0) -> xr.DataArray:
-        """Normalize a Dataset's values between 0 and 1.
-
-        Parameters
-        ----------
-        stretch : float, default 1.0
-            A percentile stretch to apply before normalization between 0.0 and 0.1.
-
-        Returns
-        -------
-        xarray.DataArray
-            The dataset with normalized values.
-
-        Raises
-        ------
-        ValueError
-            If the stretch value is outside the valid range.
-        """
-        da = self._obj
-
-        if stretch < 0 or stretch > 1:
-            raise ValueError("Stretch value must be in the range [0.0, 1.0].")
-
-        min_val = da.quantile(1 - stretch)
-        max_val = da.quantile(stretch)
-
-        return ((da - min_val) / (max_val - min_val)).clip(0, 1)
+from typing import Any, List, Optional
+
+import xarray as xr
+
+
+@xr.register_dataset_accessor("wx")
+class DatasetAccessor:
+    def __init__(self, obj: xr.Dataset):
+        self._obj = obj
+
+    def rgb(
+        self,
+        bands: Optional[List[str]] = None,
+        stretch: float = 1.0,
+        interactive: bool = False,
+        **kwargs: Any,
+    ) -> Any:
+        """Generate an RGB color composite plot of the Dataset.
+
+        Parameters
+        ----------
+        bands : List[str], optional
+            A list of 3 data variable names to use as the red, green, and blue channels. If none is provided, the
+            first three data variables will be used in order.
+        stretch : float, default 1.0
+            A percentile stretch to apply to pixel values, between 0.0 and 1.0.
+        interactive : bool, default False
+            If False, a static plot is returned, faceted over the time dimension. If True, an interactive plot is
+            returned over the time dimension. interactive plots require the `hvplot` library to be installed
+            independently.
+        **kwargs
+            Keyword arguments passed to the plotting function. For static plots, arguments are passed to
+            :code:`xarray.Dataset.plot.imshow`. For interactive plots, arguments are passed to :code:`xarray.Dataset.hvplot.rgb`.
+
+        Returns
+        -------
+        Union[xarray.plot.facetgrid.FacetGrid, HoloViews object]
+            The RGB plot, either static or interactive.
+
+        Raises
+        ------
+        ValueError
+            If an incorrect number of bands are found, whether explicitly passed through the `bands` argument or
+            implicitly identified from the data variables.
+
+        ImportError
+            If the `interactive` argument is True and the `hvplot` package is not installed.
+
+        Examples
+        --------
+        Download one month of Sentinel-2 imagery over a point.
+
+        >>> pt = ee.Geometry.Point([5.40432,44.11541])
+        >>> ts = wxee.TimeSeries("COPERNICUS/S2_SR")
+        >>> ts = ts.filterDate("2020-07", "2020-08").filterBounds(pt)
+        >>> ds = ts.wx.to_xarray(region=pt.buffer(1000), scale=20)
+
+        Generate a static plot of the images as a true color composite. The col_wrap argument will be passed to
+        the plotting function.
+
+        >>> ds.wx.rgb(bands=["B4", "B3", "B2"], stretch=0.85, col_wrap=4)
+
+        Generate an interactive plot using a near-infrared false color composite. The aspect argument will be passed
+        to the plotting function.
+
+        >>> ds.wx.rgb(bands=["B8", "B4", "B3"], stretch=0.85, interactive=True, aspect=1.2)
+        """
+        if bands is not None:
+            if len(bands) != 3:
+                raise ValueError(f"Bands must be a list with exactly 3 names.")
+        else:
+            bands = list(self._obj.var())[:3]  # type: ignore
+
+            # Raise a different error if the bands were identified implicitly to avoid confusion
+            if len(bands) != 3:  # type: ignore
+                raise ValueError(
+                    f"The Dataset must contain at least 3 data variables for RGB plotting."
+                )
+
+        da = self._obj[bands].to_array(name="rgb")
+
+        da = da.wx.normalize(stretch)
+
+        if interactive:
+            try:
+                import hvplot.xarray  # type: ignore
+            except ImportError:
+                raise ImportError(
+                    "The `hvplot` package is required for interactive plots. Run `pip install hvplot`."
+                ) from None
+
+            default_kwargs = {
+                "groupby": "time",
+                "widget_location": "bottom",
+                "widget_type": "scrubber",
+            }
+            return da.hvplot.rgb(
+                x="x", y="y", bands="variable", **{**default_kwargs, **kwargs}
+            )
+
+        default_kwargs = {"col": "time"}
+        return da.plot.imshow(**{**default_kwargs, **kwargs})
+
+
+@xr.register_dataarray_accessor("wx")
+class DataArrayAccessor:
+    def __init__(self, obj: xr.DataArray):
+        self._obj = obj
+
+    def normalize(self, stretch: float = 1.0) -> xr.DataArray:
+        """Normalize a Dataset's values between 0 and 1.
+
+        Parameters
+        ----------
+        stretch : float, default 1.0
+            A percentile stretch to apply before normalization between 0.0 and 0.1.
+
+        Returns
+        -------
+        xarray.DataArray
+            The dataset with normalized values.
+
+        Raises
+        ------
+        ValueError
+            If the stretch value is outside the valid range.
+        """
+        da = self._obj
+
+        if stretch < 0 or stretch > 1:
+            raise ValueError("Stretch value must be in the range [0.0, 1.0].")
+
+        min_val = da.quantile(1 - stretch)
+        max_val = da.quantile(stretch)
+
+        return ((da - min_val) / (max_val - min_val)).clip(0, 1)
```

### Comparing `wxee-0.4.0/LICENSE` & `wxee-0.4.1/LICENSE`

 * *Ordering differences only*

 * *Files 22% similar despite different names*

```diff
@@ -1,21 +1,21 @@
-MIT License
-
-Copyright (c) 2022 Aaron Zuspan
-
-Permission is hereby granted, free of charge, to any person obtaining a copy
-of this software and associated documentation files (the "Software"), to deal
-in the Software without restriction, including without limitation the rights
-to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
-copies of the Software, and to permit persons to whom the Software is
-furnished to do so, subject to the following conditions:
-
-The above copyright notice and this permission notice shall be included in all
-copies or substantial portions of the Software.
-
-THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
-IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
-FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
-AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
-LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
-OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
+MIT License
+
+Copyright (c) 2022 Aaron Zuspan
+
+Permission is hereby granted, free of charge, to any person obtaining a copy
+of this software and associated documentation files (the "Software"), to deal
+in the Software without restriction, including without limitation the rights
+to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
+copies of the Software, and to permit persons to whom the Software is
+furnished to do so, subject to the following conditions:
+
+The above copyright notice and this permission notice shall be included in all
+copies or substantial portions of the Software.
+
+THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
+IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
+FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
+AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
+LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
+OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 SOFTWARE.
```

### Comparing `wxee-0.4.0/README.rst` & `wxee-0.4.1/README.rst`

 * *Ordering differences only*

 * *Files 22% similar despite different names*

```diff
@@ -1,173 +1,173 @@
-.. image:: https://raw.githubusercontent.com/aazuspan/wxee/main/docs/_static/wxee.png
-   :alt: wxee .-- -..-
-   :width: 200
-   :target: https://github.com/aazuspan/wxee
-
-|
-
-.. image:: https://img.shields.io/badge/Earth%20Engine%20API-Python-green
-   :alt: Earth Engine Python
-   :target: https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api
-.. image:: https://img.shields.io/pypi/v/wxee
-   :alt: PyPI
-   :target: https://pypi.org/project/wxee/
-.. image:: https://img.shields.io/conda/vn/conda-forge/wxee.svg
-   :alt: conda-forge
-   :target: https://anaconda.org/conda-forge/wxee
-.. image:: https://colab.research.google.com/assets/colab-badge.svg
-   :alt: Open in Colab
-   :target: https://colab.research.google.com/github/aazuspan/wxee/blob/main/docs/examples/image_collection_to_xarray.ipynb
-.. image:: https://readthedocs.org/projects/wxee/badge/?version=latest&style=flat
-   :alt: Read the Docs
-   :target: https://wxee.readthedocs.io/en/latest/?badge=latest
-.. image:: https://github.com/aazuspan/wxee/actions/workflows/tests.yml/badge.svg
-   :alt: Build status
-   :target: https://github.com/aazuspan/wxee
-.. image:: https://codecov.io/gh/aazuspan/wxee/branch/main/graph/badge.svg?token=OeSeq4b7NF
-   :alt: Code coverage
-   :target: https://codecov.io/gh/aazuspan/wxee
-
-------------
-
-.. image:: https://raw.githubusercontent.com/aazuspan/wxee/main/docs/_static/demo_001.gif
-  :alt: Demo downloading weather data to xarray using wxee.
-
-
-What is wxee?
--------------
-`wxee <https://github.com/aazuspan/wxee>`_ was built to make processing gridded, mesoscale time series data quick 
-and easy by integrating the data catalog and processing power of `Google Earth Engine <https://earthengine.google.com/>`_ with the 
-flexibility of `xarray <https://github.com/pydata/xarray>`_, with no complicated setup required. To accomplish this, wxee implements 
-convenient methods for data processing, aggregation, downloading, and ingestion.
-
-`wxee <https://github.com/aazuspan/wxee>`__ can be found in the `Earth Engine Developer Resources <https://developers.google.com/earth-engine/tutorials/community/developer-resources#python>`_!
-
-
-Features
---------
-* Time series image collections to `xarray <https://wxee.readthedocs.io/en/latest/examples/image_collection_to_xarray.html>`__, `NetCDF <https://wxee.readthedocs.io/en/latest/examples/image_collection_to_xarray.html>`_, or `GeoTIFF <https://wxee.readthedocs.io/en/latest/examples/downloading_images_and_collections.html>`_ in one line of code
-* `Climatological anomalies <https://wxee.readthedocs.io/en/latest/examples/climatology_anomaly.html>`_ and temporal `aggregation <https://wxee.readthedocs.io/en/latest/examples/temporal_aggregation.html>`_, `interpolation <https://wxee.readthedocs.io/en/latest/examples/temporal_interpolation.html>`_, `smoothing <https://wxee.readthedocs.io/en/latest/generated/wxee.time_series.TimeSeries.rolling_time.html>`_, and `gap-filling <https://wxee.readthedocs.io/en/latest/generated/wxee.time_series.TimeSeries.fill_gaps.html>`_ in Earth Engine
-* `Color composite plots <https://wxee.readthedocs.io/en/latest/examples/color_composites.html>`_ from **xarray** datasets
-* Parallel processing for fast downloads
-
-
-To see some of the capabilities of wxee and try it yourself, check out the interactive notebooks `here <https://wxee.readthedocs.io/en/latest/examples.html>`__!
-
-Install
-------------
-
-Pip
-~~~
-
-.. code-block:: bash
-
-   pip install wxee
-
-Conda
-~~~~~
-
-.. code-block:: bash
-
-    conda install -c conda-forge wxee
-
-From Source
-~~~~~~~~~~~
-
-.. code-block:: bash
-
-   git clone https://github.com/aazuspan/wxee
-   cd wxee
-   make install
-
-
-Quickstart
-----------
-
-Setup
-~~~~~
-Once you have access to Google Earth Engine, just import and initialize :code:`ee` and :code:`wxee`.
-
-.. code-block:: python
-   
-   import ee
-   import wxee
-
-   wxee.Initialize()
-
-
-Download Images
-~~~~~~~~~~~~~~~
-
-Download and conversion methods are extended to :code:`ee.Image` and :code:`ee.ImageCollection` using the 
-:code:`wx` accessor. Just :code:`import wxee` and use the :code:`wx` accessor.
-
-xarray
-^^^^^^
-
-.. code-block:: python
-
-   ee.ImageCollection("IDAHO_EPSCOR/GRIDMET").wx.to_xarray()
-
-NetCDF
-^^^^^^
-
-.. code-block:: python
-
-   ee.ImageCollection("IDAHO_EPSCOR/GRIDMET").wx.to_xarray(path="data/gridmet.nc")
-
-GeoTIFF
-^^^^^^^
-
-.. code-block:: python
-
-   ee.ImageCollection("IDAHO_EPSCOR/GRIDMET").wx.to_tif()
-
-
-Create a Time Series
-~~~~~~~~~~~~~~~~~~~~
-
-Additional methods for processing image collections in the time dimension are available through the :code:`TimeSeries` subclass.
-A :code:`TimeSeries` can be created from an existing :code:`ee.ImageCollection`...
-
-.. code-block:: python
-
-   col = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET")
-   ts = col.wx.to_time_series()
-
-Or instantiated directly just like you would an :code:`ee.ImageCollection`!
-
-.. code-block:: python
-
-   ts = wxee.TimeSeries("IDAHO_EPSCOR/GRIDMET")
-
-
-Aggregate Daily Data
-~~~~~~~~~~~~~~~~~~~~
-
-Many weather datasets are in daily or hourly resolution. These can be aggregated to coarser resolutions using the :code:`aggregate_time`
-method of the :code:`TimeSeries` class.
-
-.. code-block:: python
-
-   ts = wxee.TimeSeries("IDAHO_EPSCOR/GRIDMET")
-   monthly_max = ts.aggregate_time(frequency="month", reducer=ee.Reducer.max())
-
-Calculate Climatological Means
-~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
-
-Long-term climatological means can be calculated using the :code:`climatology_mean` method of the :code:`TimeSeries` class.
-
-.. code-block:: python
-
-   ts = wxee.TimeSeries("IDAHO_EPSCOR/GRIDMET")
-   mean_clim = ts.climatology_mean(frequency="month")
-
-Contribute
-----------
-
-Bugs or feature requests are always appreciated! They can be submitted `here <https://github.com/aazuspan/wxee/issues>`__. 
-
-Code contributions are also welcome! Please open an `issue <https://github.com/aazuspan/wxee/issues>`__ to discuss implementation, 
-then follow the steps below. Developer setup instructions can be found `in the docs <https://wxee.readthedocs.io/en/latest/contributing.html>`__.
-
-
+.. image:: https://raw.githubusercontent.com/aazuspan/wxee/main/docs/_static/wxee.png
+   :alt: wxee .-- -..-
+   :width: 200
+   :target: https://github.com/aazuspan/wxee
+
+|
+
+.. image:: https://img.shields.io/badge/Earth%20Engine%20API-Python-green
+   :alt: Earth Engine Python
+   :target: https://developers.google.com/earth-engine/tutorials/community/intro-to-python-api
+.. image:: https://img.shields.io/pypi/v/wxee
+   :alt: PyPI
+   :target: https://pypi.org/project/wxee/
+.. image:: https://img.shields.io/conda/vn/conda-forge/wxee.svg
+   :alt: conda-forge
+   :target: https://anaconda.org/conda-forge/wxee
+.. image:: https://colab.research.google.com/assets/colab-badge.svg
+   :alt: Open in Colab
+   :target: https://colab.research.google.com/github/aazuspan/wxee/blob/main/docs/examples/image_collection_to_xarray.ipynb
+.. image:: https://readthedocs.org/projects/wxee/badge/?version=latest&style=flat
+   :alt: Read the Docs
+   :target: https://wxee.readthedocs.io/en/latest/?badge=latest
+.. image:: https://github.com/aazuspan/wxee/actions/workflows/tests.yml/badge.svg
+   :alt: Build status
+   :target: https://github.com/aazuspan/wxee
+.. image:: https://codecov.io/gh/aazuspan/wxee/branch/main/graph/badge.svg?token=OeSeq4b7NF
+   :alt: Code coverage
+   :target: https://codecov.io/gh/aazuspan/wxee
+
+------------
+
+.. image:: https://raw.githubusercontent.com/aazuspan/wxee/main/docs/_static/demo_001.gif
+  :alt: Demo downloading weather data to xarray using wxee.
+
+
+What is wxee?
+-------------
+`wxee <https://github.com/aazuspan/wxee>`_ was built to make processing gridded, mesoscale time series data quick 
+and easy by integrating the data catalog and processing power of `Google Earth Engine <https://earthengine.google.com/>`_ with the 
+flexibility of `xarray <https://github.com/pydata/xarray>`_, with no complicated setup required. To accomplish this, wxee implements 
+convenient methods for data processing, aggregation, downloading, and ingestion.
+
+`wxee <https://github.com/aazuspan/wxee>`__ can be found in the `Earth Engine Developer Resources <https://developers.google.com/earth-engine/tutorials/community/developer-resources#python>`_!
+
+
+Features
+--------
+* Time series image collections to `xarray <https://wxee.readthedocs.io/en/latest/examples/image_collection_to_xarray.html>`__, `NetCDF <https://wxee.readthedocs.io/en/latest/examples/image_collection_to_xarray.html>`_, or `GeoTIFF <https://wxee.readthedocs.io/en/latest/examples/downloading_images_and_collections.html>`_ in one line of code
+* `Climatological anomalies <https://wxee.readthedocs.io/en/latest/examples/climatology_anomaly.html>`_ and temporal `aggregation <https://wxee.readthedocs.io/en/latest/examples/temporal_aggregation.html>`_, `interpolation <https://wxee.readthedocs.io/en/latest/examples/temporal_interpolation.html>`_, `smoothing <https://wxee.readthedocs.io/en/latest/generated/wxee.time_series.TimeSeries.rolling_time.html>`_, and `gap-filling <https://wxee.readthedocs.io/en/latest/generated/wxee.time_series.TimeSeries.fill_gaps.html>`_ in Earth Engine
+* `Color composite plots <https://wxee.readthedocs.io/en/latest/examples/color_composites.html>`_ from **xarray** datasets
+* Parallel processing for fast downloads
+
+
+To see some of the capabilities of wxee and try it yourself, check out the interactive notebooks `here <https://wxee.readthedocs.io/en/latest/examples.html>`__!
+
+Install
+------------
+
+Pip
+~~~
+
+.. code-block:: bash
+
+   pip install wxee
+
+Conda
+~~~~~
+
+.. code-block:: bash
+
+    conda install -c conda-forge wxee
+
+From Source
+~~~~~~~~~~~
+
+.. code-block:: bash
+
+   git clone https://github.com/aazuspan/wxee
+   cd wxee
+   make install
+
+
+Quickstart
+----------
+
+Setup
+~~~~~
+Once you have access to Google Earth Engine, just import and initialize :code:`ee` and :code:`wxee`.
+
+.. code-block:: python
+   
+   import ee
+   import wxee
+
+   wxee.Initialize()
+
+
+Download Images
+~~~~~~~~~~~~~~~
+
+Download and conversion methods are extended to :code:`ee.Image` and :code:`ee.ImageCollection` using the 
+:code:`wx` accessor. Just :code:`import wxee` and use the :code:`wx` accessor.
+
+xarray
+^^^^^^
+
+.. code-block:: python
+
+   ee.ImageCollection("IDAHO_EPSCOR/GRIDMET").wx.to_xarray()
+
+NetCDF
+^^^^^^
+
+.. code-block:: python
+
+   ee.ImageCollection("IDAHO_EPSCOR/GRIDMET").wx.to_xarray(path="data/gridmet.nc")
+
+GeoTIFF
+^^^^^^^
+
+.. code-block:: python
+
+   ee.ImageCollection("IDAHO_EPSCOR/GRIDMET").wx.to_tif()
+
+
+Create a Time Series
+~~~~~~~~~~~~~~~~~~~~
+
+Additional methods for processing image collections in the time dimension are available through the :code:`TimeSeries` subclass.
+A :code:`TimeSeries` can be created from an existing :code:`ee.ImageCollection`...
+
+.. code-block:: python
+
+   col = ee.ImageCollection("IDAHO_EPSCOR/GRIDMET")
+   ts = col.wx.to_time_series()
+
+Or instantiated directly just like you would an :code:`ee.ImageCollection`!
+
+.. code-block:: python
+
+   ts = wxee.TimeSeries("IDAHO_EPSCOR/GRIDMET")
+
+
+Aggregate Daily Data
+~~~~~~~~~~~~~~~~~~~~
+
+Many weather datasets are in daily or hourly resolution. These can be aggregated to coarser resolutions using the :code:`aggregate_time`
+method of the :code:`TimeSeries` class.
+
+.. code-block:: python
+
+   ts = wxee.TimeSeries("IDAHO_EPSCOR/GRIDMET")
+   monthly_max = ts.aggregate_time(frequency="month", reducer=ee.Reducer.max())
+
+Calculate Climatological Means
+~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
+
+Long-term climatological means can be calculated using the :code:`climatology_mean` method of the :code:`TimeSeries` class.
+
+.. code-block:: python
+
+   ts = wxee.TimeSeries("IDAHO_EPSCOR/GRIDMET")
+   mean_clim = ts.climatology_mean(frequency="month")
+
+Contribute
+----------
+
+Bugs or feature requests are always appreciated! They can be submitted `here <https://github.com/aazuspan/wxee/issues>`__. 
+
+Code contributions are also welcome! Please open an `issue <https://github.com/aazuspan/wxee/issues>`__ to discuss implementation, 
+then follow the steps below. Developer setup instructions can be found `in the docs <https://wxee.readthedocs.io/en/latest/contributing.html>`__.
+
+
```

### Comparing `wxee-0.4.0/PKG-INFO` & `wxee-0.4.1/PKG-INFO`

 * *Files 23% similar despite different names*

```diff
@@ -1,63 +1,34 @@
 Metadata-Version: 2.1
 Name: wxee
-Version: 0.4.0
+Version: 0.4.1
 Summary: Earth Engine to xarray interface
 Project-URL: Homepage, https://github.com/aazuspan/wxee
 Author-email: Aaron Zuspan <aazuspan@gmail.com>
 License-Expression: MIT
 License-File: LICENSE
 Keywords: earth-engine,time-series,xarray
 Classifier: Development Status :: 4 - Beta
 Classifier: Intended Audience :: Science/Research
 Classifier: Natural Language :: English
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Classifier: Topic :: Scientific/Engineering :: GIS
 Classifier: Typing :: Typed
 Requires-Python: >=3.8
 Requires-Dist: earthengine-api
 Requires-Dist: joblib
 Requires-Dist: rasterio
 Requires-Dist: requests
 Requires-Dist: rioxarray
 Requires-Dist: tqdm
 Requires-Dist: xarray
-Provides-Extra: dev
-Requires-Dist: black; extra == 'dev'
-Requires-Dist: hatch; extra == 'dev'
-Requires-Dist: hvplot; extra == 'dev'
-Requires-Dist: isort; extra == 'dev'
-Requires-Dist: matplotlib; extra == 'dev'
-Requires-Dist: mock; extra == 'dev'
-Requires-Dist: mypy; extra == 'dev'
-Requires-Dist: nbsphinx; extra == 'dev'
-Requires-Dist: netcdf4; extra == 'dev'
-Requires-Dist: plotly>=5.2.2; extra == 'dev'
-Requires-Dist: pre-commit; extra == 'dev'
-Requires-Dist: pytest; extra == 'dev'
-Requires-Dist: pytest-cov; extra == 'dev'
-Requires-Dist: requests-mock; extra == 'dev'
-Requires-Dist: sphinx; extra == 'dev'
-Requires-Dist: sphinx-rtd-theme; extra == 'dev'
-Provides-Extra: doc
-Requires-Dist: nbsphinx; extra == 'doc'
-Requires-Dist: sphinx; extra == 'doc'
-Requires-Dist: sphinx-rtd-theme; extra == 'doc'
-Provides-Extra: test
-Requires-Dist: hvplot; extra == 'test'
-Requires-Dist: matplotlib; extra == 'test'
-Requires-Dist: mock; extra == 'test'
-Requires-Dist: netcdf4; extra == 'test'
-Requires-Dist: plotly>=5.2.2; extra == 'test'
-Requires-Dist: pytest; extra == 'test'
-Requires-Dist: pytest-cov; extra == 'test'
-Requires-Dist: requests-mock; extra == 'test'
 Description-Content-Type: text/x-rst
 
 .. image:: https://raw.githubusercontent.com/aazuspan/wxee/main/docs/_static/wxee.png
    :alt: wxee .-- -..-
    :width: 200
    :target: https://github.com/aazuspan/wxee
```

