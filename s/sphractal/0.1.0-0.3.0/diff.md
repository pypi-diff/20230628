# Comparing `tmp/sphractal-0.1.0.tar.gz` & `tmp/sphractal-0.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sphractal-0.1.0.tar", max compression
+gzip compressed data, was "sphractal-0.3.0.tar", max compression
```

## Comparing `sphractal-0.1.0.tar` & `sphractal-0.3.0.tar`

### file list

```diff
@@ -1,10 +1,15 @@
--rwxr-xr-x   0        0        0     1082 2023-06-27 05:21:43.041389 sphractal-0.1.0/LICENSE
--rwxr-xr-x   0        0        0     2477 2023-06-28 02:07:15.590589 sphractal-0.1.0/README.md
--rwxr-xr-x   0        0        0     1363 2023-06-28 03:21:54.792009 sphractal-0.1.0/pyproject.toml
--rwxr-xr-x   0        0        0      282 2023-06-27 15:08:25.209830 sphractal-0.1.0/src/sphractal/__init__.py
--rwxr-xr-x   0        0        0    17908 2023-06-28 04:03:39.683813 sphractal-0.1.0/src/sphractal/boxCnt.py
--rwxr-xr-x   0        0        0     3745 2023-06-27 10:58:38.205322 sphractal-0.1.0/src/sphractal/constants.py
--rwxr-xr-x   0        0        0     8771 2023-06-27 15:09:07.046097 sphractal-0.1.0/src/sphractal/surfExact.py
--rwxr-xr-x   0        0        0     7913 2023-06-28 01:21:54.752820 sphractal-0.1.0/src/sphractal/surfPointClouds.py
--rwxr-xr-x   0        0        0    10922 2023-06-28 01:22:42.270964 sphractal-0.1.0/src/sphractal/utils.py
--rw-r--r--   0        0        0     3237 1970-01-01 00:00:00.000000 sphractal-0.1.0/PKG-INFO
+-rwxr-xr-x   0        0        0     1082 2023-06-27 05:21:43.041389 sphractal-0.3.0/LICENSE
+-rwxr-xr-x   0        0        0     2693 2023-06-28 14:44:53.643623 sphractal-0.3.0/README.md
+-rwxr-xr-x   0        0        0     1428 2023-06-28 15:19:34.528180 sphractal-0.3.0/pyproject.toml
+-rwxr-xr-x   0        0        0      453 2023-06-28 14:00:33.841989 sphractal-0.3.0/src/sphractal/__init__.py
+-rwxr-xr-x   0        0        0    18314 2023-06-28 12:42:42.960692 sphractal-0.3.0/src/sphractal/boxCnt.py
+-rwxr-xr-x   0        0        0     3676 2023-06-28 06:45:14.599420 sphractal-0.3.0/src/sphractal/constants.py
+-rwxr-xr-x   0        0        0        0 2023-06-28 06:39:13.904193 sphractal-0.3.0/src/sphractal/data/__init__.py
+-rwxr-xr-x   0        0        0      204 2023-06-28 06:42:12.379670 sphractal-0.3.0/src/sphractal/data/__pycache__/__init__.cpython-39.pyc
+-rwxr-xr-x   0        0        0    20105 2023-06-28 13:54:13.190798 sphractal-0.3.0/src/sphractal/data/example.xyz
+-rwxr-xr-x   0        0        0      274 2023-06-28 13:54:43.744336 sphractal-0.3.0/src/sphractal/datasets.py
+-rwxr-xr-x   0        0        0     8771 2023-06-27 15:09:07.046097 sphractal-0.3.0/src/sphractal/surfExact.py
+-rwxr-xr-x   0        0        0     7913 2023-06-28 12:36:15.684837 sphractal-0.3.0/src/sphractal/surfPointClouds.py
+-rwxr-xr-x   0        0        0    10914 2023-06-28 06:22:38.627192 sphractal-0.3.0/src/sphractal/utils.py
+-rwxr-xr-x   0        0        0     5417 2023-06-28 15:03:31.949731 sphractal-0.3.0/tests/test_sphractal.py
+-rw-r--r--   0        0        0     3457 1970-01-01 00:00:00.000000 sphractal-0.3.0/PKG-INFO
```

### Comparing `sphractal-0.1.0/LICENSE` & `sphractal-0.3.0/LICENSE`

 * *Files identical despite different names*

### Comparing `sphractal-0.1.0/README.md` & `sphractal-0.3.0/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -3,23 +3,28 @@
 ## Description
 
 `Sphractal` is a package that provides functionality to estimate the fractal dimension of complex 3D surfaces formed 
 from overlapping spheres via box-counting algorithm. 
 
 ## Features
 
+### Current
 * Representation of the surface as either point clouds or exact surfaces.
 * Efficient algorithm for 3D box-counting calculations.
 * Customisable parameters to control the level of detail and accuracy of the calculation.
 
-TODO: 
-* Publish to conda
-* Complete example under `## Usage`
-* Complete `docs/example.ipynb` and `tests/`
-* Transform xyz coordinates when reading atoms to avoid using minXYZ repetitively in scanAtom().
+### To be Done
+* Installation from Conda, after publishing to Conda
+* Nested multiprocessing.
+* Complete docstrings for `findSurf()`.
+* Complete help function for all functions.
+* Complete example under `## Usage`.
+* Complete `docs/example.ipynb`.
+* Consider removing `tests/` from [tool.poetry].
+* Consider transforming xyz coordinates when reading atoms to avoid using minXYZ repetitively in `scanAtom()`.
 
 ## Installation
 
 Use `pip` or `conda` to install `Sphractal`:
 ```bash
 $ pip install sphractal
 ```
```

### Comparing `sphractal-0.1.0/pyproject.toml` & `sphractal-0.3.0/pyproject.toml`

 * *Files 6% similar despite different names*

```diff
@@ -1,30 +1,32 @@
 [tool.poetry]
 name = "sphractal"
-version = "0.1.0"
+version = "0.3.0"
 description = "Package to estimate fractal dimension of 3D surfaces formed from overlapping spheres via box-counting algorithm."
 authors = ["Jonathan Yik Chang Ting"]
 license = "MIT"
 readme = "README.md"
+include = ["tests/*"]
 
 [tool.poetry.dependencies]
 python = ">=3.9"
 matplotlib = ">=3.7.1"
 statsmodels = ">=0.14.0"
 scipy = {version = ">=1.11.0", python = ">=3.9,<3.13"}
 numba = ">=0.57.1"
-numpy = "1.24.3"
+numpy = ">=1.22,<1.25"
 
 [tool.poetry.group.dev.dependencies]
 pytest = ">=7.4.0"
 pytest-cov = ">=4.1.0"
 jupyter = ">=1.0.0"
 myst-nb = {version = ">=0.17.2", python = "^3.9"}
 sphinx-autoapi = ">=2.1.1"
 sphinx-rtd-theme = ">=1.2.2"
+python-semantic-release = ">=7.34.6"
 
 [tool.semantic_release]
 version_variable = "pyproject.toml:version" # version location
 branch = "main"                             # branch to make releases of
 changelog_file = "CHANGELOG.md"             # changelog file
 build_command = "poetry build"              # build dists
 dist_path = "dist/"                         # where to put dists
```

### Comparing `sphractal-0.1.0/src/sphractal/boxCnt.py` & `sphractal-0.3.0/src/sphractal/boxCnt.py`

 * *Files 2% similar despite different names*

```diff
@@ -17,17 +17,17 @@
 MIN_SAMPLE_NUM = 5
 CONF_INT_PERC = 95  # Percentage
 ALPHA_CI = 1 - CONF_INT_PERC/100
 
 
 # @annotate('getVoxelBoxCnts', color='blue')
 def getVoxelBoxCnts(atomsEle, atomsRad, atomsSurfIdxs, atomsXYZ, atomsNeighIdxs,
-                    npName, writeFileDir='.', exeDir='.', procUnit='cpu',
+                    npName, writeFileDir='boxCntOutputs', exeDir='../bin', procUnit='cpu',
                     radType='metallic', numPoint=300, gridNum=1024,
-                    rmInSurf=True, vis=False, verbose=False, genPCD=False):
+                    rmInSurf=True, vis=True, verbose=True, genPCD=False):
     """
     Count the boxes that cover the outer surface of a set of overlapping spheres represented as point clouds for
     different box sizes, using 3D box-counting algorithm written by Ruiz de Miras et al. in C++. All source codes are
     provided under {SPHRACTAL_DIR_PATH}/src/fbc/.
     
     Parameters
     ----------
@@ -93,27 +93,28 @@
     if verbose:
         print(f"  Approximating the surface with {numPoint} point clouds for each atom...")
 
     genSurfPoints(atomsEle, atomsRad, atomsSurfIdxs, atomsXYZ, atomsNeighIdxs,
                   npName, writeFileDir,
                   radType, numPoint, gridNum,
                   rmInSurf, vis, verbose, genPCD)
-    system(f"{exeDir}/3DbinImBC{procUnit}.exe {gridNum} {writeFileDir}/surfVoxelIdxs.txt {writeFileDir}/surfVoxelBoxCnts.txt")
+    system(f"{exeDir}/3DbinImBC{procUnit}.exe {gridNum} {writeFileDir}/surfVoxelIdxs.txt "
+           f"{writeFileDir}/surfVoxelBoxCnts.txt")
     scaleChange, cntChange = [], []
     with open(f"{writeFileDir}/surfVoxelBoxCnts.txt", 'r') as f:
         for line in f:
             scaleChange.append(log10(1 / int(line.split()[0])))
             cntChange.append(log10(int(line.split()[1])))
     return scaleChange[::-1], cntChange[::-1]
 
 
 # @annotate('getSphereBoxCnts', color='blue')
 def getSphereBoxCnts(atomsEle, atomsRad, atomsSurfIdxs, atomsXYZ, atomsNeighIdxs,
-                     maxDimDiff, minMaxBoxLens, minXYZ, npName, writeFileDir='.',
-                     rmInSurf=True, writeBox=False, verbose=False, boxLenConc=False, maxWorkers=2):
+                     maxDimDiff, minMaxBoxLens, minXYZ, npName, writeFileDir='boxCntOutputs',
+                     rmInSurf=True, writeBox=True, verbose=True, boxLenConc=False, maxWorkers=2):
     """
     Count the boxes that cover the outer surface of a set of overlapping spheres represented as exact spheres for
     different box sizes.
     
     Parameters
     ----------
     atomsEle : 1D ndarray
@@ -223,15 +224,16 @@
             plt.plot(x, yPred, label='OLS')
             predOLS = regModel.get_prediction()
             lowCIvals, upCIvals = predOLS.summary_frame()['mean_ci_lower'], predOLS.summary_frame()['mean_ci_upper']
             plt.plot(x, upCIvals, 'r--')
             plt.plot(x, lowCIvals, 'r--')
             plt.xlabel('log(1/r)')
             plt.ylabel('log(N)')
-            plt.title(f"{npName} R2: {r2score:.3f}, D_Box: {boxCntDim:.3f}, {CONF_INT_PERC}% CI: [{slopeCI[0]:.3f}, {slopeCI[1]:.3f}]")
+            plt.title(f"{npName} R2: {r2score:.3f}, D_Box: {boxCntDim:.3f}, {CONF_INT_PERC}% CI: "
+                      f"[{slopeCI[0]:.3f}, {slopeCI[1]:.3f}]")
         # Removal of next point (beware of weird behaviour in middle range)
         # lstSqErrs = np.subtract(y, yPred) ** 2
         # if len(y) % 2 == 0:
         #     lowBoundErrSum, upBoundErrSum = lstSqErrs[:len(y) // 2].sum(), lstSqErrs[len(y) // 2:].sum()
         # else:
         #     lowBoundErrSum, upBoundErrSum = lstSqErrs[:len(y) // 2].sum(), lstSqErrs[len(y) // 2 + 1:].sum()
         # if lowBoundErrSum > upBoundErrSum: firstPointIdx += 1
@@ -256,28 +258,32 @@
         if lenRange == 'full':
             return r2score, boxCntDim, slopeCI
     return r2score, boxCntDim, slopeCI
 
 
 # @annotate('runCase', color='cyan')
 @estDuration
-def runBoxCnt(xyzFilePath, radType='metallic', findSurfOption='alphaShape', alphaMult=2.5,
-              writeFileDir='.', lenRange='trim', rmInSurf=True, vis=True, saveFig=True, showPlot=False, verbose=False,
-              runPointCloudBoxCnt=True, numPoints=300, gridNum=1024, exeDir='.', procUnit='cpu', genPCD=False,
-              runExactSphereBoxCnt=True, minLenMult=0.25, maxLenMult=1, writeBox=False, boxLenConc=True, maxWorkers=2):
+def runBoxCnt(xyzFilePath, 
+              radType='metallic', calcBL=False, findSurfOption='alphaShape', alphaMult=2.5,
+              writeFileDir='boxCntOutputs', lenRange='trim', 
+              rmInSurf=True, vis=True, saveFig=True, showPlot=False, verbose=True,
+              runPointCloudBoxCnt=True, numPoints=300, gridNum=1024, exeDir='../bin', procUnit='cpu', genPCD=False,
+              runExactSphereBoxCnt=True, minLenMult=0.25, maxLenMult=1, writeBox=True, boxLenConc=False, maxWorkers=2):
     """
     Run box-counting algorithm on the surface of a given object consisting of a set of spheres represented as either
     point clouds or exact spherical surface.
     
     Parameters
     ----------
     xyzFilePath : str
         Path to an xyz file containing the Cartesian coordinates of a set of spheres.
     radType : {'metallic', 'atomic'}
         Type of radii to use for the spheres.
+    calcBL : bool
+        Whether to compute the average distance from its neighbours for each atom
     findSurfOption : {'alphaShape', 'convexHull', 'numNeigh'}
         Algorithm to identify the spheres on the surface.
     alphaMult : float 
         Multiplier to the minimum spherical radii to decide 'alpha' for the alpha shape algorithm, only used if
         'findSurfOption' is 'alphaShape'.
     writeFileDir : str
         Path to the directory to store the output files.
@@ -335,23 +341,26 @@
     confIntES : tuple
         Confidence interval of the box-counting dimension of the exact sphere surface.
     
     Examples
     --------
     >>> r2Points, bcDimPoints, confIntPoints, r2Exact, bcDimExact, confIntExact = runBoxCnt('example.xyz')
     """
+    radMult = 1.5 if radType == 'metallic' else 1.2  # Radius multiplier to identify nearest neighbour
     atomsEle, atomsRad, atomsXYZ, maxDimDiff, minXYZ, maxXYZ = readXYZ(xyzFilePath, radType)
-    atomsNeighIdxs, atomsAvgBondLen = findNN(atomsRad, atomsXYZ, minXYZ, maxXYZ, atomsRad.max())
+    atomsNeighIdxs, atomsAvgBondLen = findNN(atomsRad, atomsXYZ, minXYZ, maxXYZ, atomsRad.max(), radMult, calcBL)
     atomsSurfIdxs = findSurf(atomsXYZ, atomsNeighIdxs, findSurfOption, alphaMult * atomsRad.min())
     testCase = xyzFilePath.split('/')[-1][:-4]
     if verbose:
         print(f"\n{testCase}")
 
     r2PC, bcDimPC, confIntPC = np.nan, np.nan, (np.nan, np.nan)
     r2ES, bcDimES, confIntES = np.nan, np.nan, (np.nan, np.nan)
+    if not isdir(writeFileDir):
+        mkdir(writeFileDir)
     if runPointCloudBoxCnt:
         scalesPC, countsPC = getVoxelBoxCnts(atomsEle, atomsRad, atomsSurfIdxs, atomsXYZ, atomsNeighIdxs,
                                              testCase, writeFileDir, exeDir, procUnit,
                                              radType, numPoints, gridNum,
                                              rmInSurf, vis, verbose, genPCD)
         r2PC, bcDimPC, confIntPC = findSlope(scalesPC, countsPC, writeFileDir, testCase, lenRange,
                                              vis, saveFig, showPlot)
```

### Comparing `sphractal-0.1.0/src/sphractal/constants.py` & `sphractal-0.3.0/src/sphractal/constants.py`

 * *Files 5% similar despite different names*

```diff
@@ -33,8 +33,7 @@
     'Hf': 1.59, 'Ta': 1.46, 'W': 1.39, 'Re': 1.37, 'Os': 1.35, 'Ir': 1.355, 'Pt': 1.385, 'Au': 1.44, 'Hg': 1.51,
     'Tl': 1.70, 'Pb': defRad, 'Bi': defRad, 'Po': defRad, 'At': defRad, 'Rn': defRad, 'Fr': defRad, 'Ra': defRad,
     'Ac': defRad, 'Th': 1.79, 'Pa': 1.63, 'U': 1.56, 'Np': 1.55, 'Pu': 1.59, 'Am': 1.73, 'Cm': 1.74, 'Bk': 1.70,
     'Cf': 1.86, 'Es': 1.86, 'Fm': defRad, 'Md': defRad, 'No': defRad, 'Lr': defRad, 'Rf': defRad, 'Db': defRad,
     'Sg': defRad, 'Bh': defRad, 'Hs': defRad, 'Mt': defRad, 'Ds': defRad, 'Rg': defRad, 'Cn': defRad, 'Nh': defRad,
     'Fl': defRad, 'Mc': defRad, 'Lv': defRad, 'Ts': defRad, 'Og': defRad
 }
-NN_RAD_MULT = 1.5  # Radius multiplier to identify nearest neighbour
```

### Comparing `sphractal-0.1.0/src/sphractal/surfExact.py` & `sphractal-0.3.0/src/sphractal/surfExact.py`

 * *Files identical despite different names*

### Comparing `sphractal-0.1.0/src/sphractal/surfPointClouds.py` & `sphractal-0.3.0/src/sphractal/surfPointClouds.py`

 * *Files identical despite different names*

### Comparing `sphractal-0.1.0/src/sphractal/utils.py` & `sphractal-0.3.0/src/sphractal/utils.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from math import ceil, floor, sqrt
 from time import time
 
 from numba import njit, prange
 import numpy as np
 # from nvtx import annotate
 from scipy.spatial import ConvexHull, Delaunay
-from sphractal.constants import ATOMIC_RAD_DICT, BULK_CN, METALLIC_RAD_DICT, NN_RAD_MULT
+from sphractal.constants import ATOMIC_RAD_DICT, BULK_CN, METALLIC_RAD_DICT
 
 
 def estDuration(func):
     """Return time taken to run a function."""
     def wrap(*arg, **kwargs):
         start = time()
         result = func(*arg, **kwargs)
@@ -63,15 +63,15 @@
             for z in range(-1, 2):
                 dirVecs.append((x, y, z))
     return dirVecs
 
 
 # @annotate('findNN', color='magenta')
 @njit(fastmath=True, cache=True)
-def findNN(atomsRad, atomsXYZ, minXYZ, maxXYZ, maxAtomRad, calcBL=False):
+def findNN(atomsRad, atomsXYZ, minXYZ, maxXYZ, maxAtomRad, radMult, calcBL=False):
     """Compute the nearest neighbour list and average bond length for each atom."""
     (minX, minY, minZ), (maxX, maxY, maxZ) = minXYZ, maxXYZ
     atomsNeighIdxs = [[int(j) for j in range(0)] for _ in range(len(atomsRad))]
     atomsAvgBondLen = np.zeros_like(atomsRad)
     stepSize = ceil(maxAtomRad * 2)
     numX, numY, numZ = ceil((maxX-minX) / stepSize), ceil((maxY-minY) / stepSize), ceil((maxZ-minZ) / stepSize)
     boxes = [[[[int(i) for i in range(0)] for _ in range(numZ)] for _ in range(numY)] for _ in range(numX)]
@@ -84,15 +84,15 @@
             if 0 <= x + dirX < numX and 0 <= y + dirY < numY and 0 <= z + dirZ < numZ:
                 for j in boxes[x + dirX][y + dirY][z + dirZ]:
                     atom2X, atom2Y, atom2Z = atomsXYZ[j]
                     atom2rad = atomsRad[j]
 
                     diffX, diffY, diffZ = abs(atom1X - atom2X), abs(atom1Y - atom2Y), abs(atom1Z - atom2Z)
                     sumOfSquares = diffX * diffX + diffY * diffY + diffZ * diffZ
-                    if sumOfSquares < ((atom1rad+atom2rad)*NN_RAD_MULT) ** 2:
+                    if sumOfSquares < ((atom1rad+atom2rad)*radMult) ** 2:
                         atomsNeighIdxs[i].append(j)
                         atomsNeighIdxs[j].append(i)
                         if calcBL:
                             atomsAvgBondLen[i] += sqrt(diffX * diffX + diffY * diffY + diffZ * diffZ)
                             atomsAvgBondLen[j] += sqrt(diffX * diffX + diffY * diffY + diffZ * diffZ)
         boxes[x][y][z].append(i)
```

### Comparing `sphractal-0.1.0/PKG-INFO` & `sphractal-0.3.0/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,44 +1,49 @@
 Metadata-Version: 2.1
 Name: sphractal
-Version: 0.1.0
+Version: 0.3.0
 Summary: Package to estimate fractal dimension of 3D surfaces formed from overlapping spheres via box-counting algorithm.
 License: MIT
 Author: Jonathan Yik Chang Ting
 Requires-Python: >=3.9
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: matplotlib (>=3.7.1)
 Requires-Dist: numba (>=0.57.1)
-Requires-Dist: numpy (==1.24.3)
+Requires-Dist: numpy (>=1.22,<1.25)
 Requires-Dist: scipy (>=1.11.0) ; python_version >= "3.9" and python_version < "3.13"
 Requires-Dist: statsmodels (>=0.14.0)
 Description-Content-Type: text/markdown
 
 # Sphractal
 
 ## Description
 
 `Sphractal` is a package that provides functionality to estimate the fractal dimension of complex 3D surfaces formed 
 from overlapping spheres via box-counting algorithm. 
 
 ## Features
 
+### Current
 * Representation of the surface as either point clouds or exact surfaces.
 * Efficient algorithm for 3D box-counting calculations.
 * Customisable parameters to control the level of detail and accuracy of the calculation.
 
-TODO: 
-* Publish to conda
-* Complete example under `## Usage`
-* Complete `docs/example.ipynb` and `tests/`
-* Transform xyz coordinates when reading atoms to avoid using minXYZ repetitively in scanAtom().
+### To be Done
+* Installation from Conda, after publishing to Conda
+* Nested multiprocessing.
+* Complete docstrings for `findSurf()`.
+* Complete help function for all functions.
+* Complete example under `## Usage`.
+* Complete `docs/example.ipynb`.
+* Consider removing `tests/` from [tool.poetry].
+* Consider transforming xyz coordinates when reading atoms to avoid using minXYZ repetitively in `scanAtom()`.
 
 ## Installation
 
 Use `pip` or `conda` to install `Sphractal`:
 ```bash
 $ pip install sphractal
 ```
```

