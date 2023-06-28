# Comparing `tmp/roma-1.3.2.tar.gz` & `tmp/roma-1.3.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "roma-1.3.2.tar", last modified: Wed Apr 26 16:22:56 2023, max compression
+gzip compressed data, was "roma-1.3.3.tar", last modified: Wed Jun 28 08:51:02 2023, max compression
```

## Comparing `roma-1.3.2.tar` & `roma-1.3.3.tar`

### file list

```diff
@@ -1,24 +1,24 @@
-drwxr-xr-x   0 rbregier (1809414175) DomainUsers (1809400513)        0 2023-04-26 16:22:56.371088 roma-1.3.2/
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)    21068 2023-02-08 15:17:32.000000 roma-1.3.2/LICENSE
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     2276 2023-02-08 15:17:32.000000 roma-1.3.2/NOTICE
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     3987 2023-04-26 16:22:56.371088 roma-1.3.2/PKG-INFO
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     3509 2023-02-08 15:17:32.000000 roma-1.3.2/README.md
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)      103 2023-02-08 15:17:32.000000 roma-1.3.2/pyproject.toml
-drwxr-xr-x   0 rbregier (1809414175) DomainUsers (1809400513)        0 2023-04-26 16:22:56.371088 roma-1.3.2/roma/
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)      145 2023-02-08 15:17:32.000000 roma-1.3.2/roma/__init__.py
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     2433 2023-02-08 15:17:32.000000 roma-1.3.2/roma/internal.py
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)    18038 2023-04-26 08:34:41.000000 roma-1.3.2/roma/mappings copy.py
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)    17616 2023-04-26 08:34:54.000000 roma-1.3.2/roma/mappings.py
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)    18146 2023-04-26 15:40:11.000000 roma-1.3.2/roma/utils.py
-drwxr-xr-x   0 rbregier (1809414175) DomainUsers (1809400513)        0 2023-04-26 16:22:56.371088 roma-1.3.2/roma.egg-info/
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     3987 2023-04-26 16:22:56.000000 roma-1.3.2/roma.egg-info/PKG-INFO
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)      349 2023-04-26 16:22:56.000000 roma-1.3.2/roma.egg-info/SOURCES.txt
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)        1 2023-04-26 16:22:56.000000 roma-1.3.2/roma.egg-info/dependency_links.txt
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)        5 2023-04-26 16:22:56.000000 roma-1.3.2/roma.egg-info/top_level.txt
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)       38 2023-04-26 16:22:56.371088 roma-1.3.2/setup.cfg
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)      672 2023-04-26 10:34:33.000000 roma-1.3.2/setup.py
-drwxr-xr-x   0 rbregier (1809414175) DomainUsers (1809400513)        0 2023-04-26 16:22:56.371088 roma-1.3.2/test/
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     1018 2023-02-08 15:17:32.000000 roma-1.3.2/test/test_derivatives.py
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     8457 2023-02-08 15:17:32.000000 roma-1.3.2/test/test_mappings.py
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     3430 2023-02-08 15:17:32.000000 roma-1.3.2/test/test_procrustes_derivatives.py
--rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)    12634 2023-04-26 10:18:23.000000 roma-1.3.2/test/test_utils.py
+drwxr-xr-x   0 rbregier (1809414175) DomainUsers (1809400513)        0 2023-06-28 08:51:02.338345 roma-1.3.3/
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)    21068 2023-02-08 15:17:32.000000 roma-1.3.3/LICENSE
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     2276 2023-02-08 15:17:32.000000 roma-1.3.3/NOTICE
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     3987 2023-06-28 08:51:02.338345 roma-1.3.3/PKG-INFO
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     3509 2023-02-08 15:17:32.000000 roma-1.3.3/README.md
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)      103 2023-02-08 15:17:32.000000 roma-1.3.3/pyproject.toml
+drwxr-xr-x   0 rbregier (1809414175) DomainUsers (1809400513)        0 2023-06-28 08:51:02.334345 roma-1.3.3/roma/
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)      145 2023-02-08 15:17:32.000000 roma-1.3.3/roma/__init__.py
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     2793 2023-06-23 14:54:33.000000 roma-1.3.3/roma/internal.py
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)    18038 2023-04-26 08:34:41.000000 roma-1.3.3/roma/mappings copy.py
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)    18727 2023-06-23 14:28:54.000000 roma-1.3.3/roma/mappings.py
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)    19966 2023-06-23 15:01:06.000000 roma-1.3.3/roma/utils.py
+drwxr-xr-x   0 rbregier (1809414175) DomainUsers (1809400513)        0 2023-06-28 08:51:02.338345 roma-1.3.3/roma.egg-info/
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     3987 2023-06-28 08:51:02.000000 roma-1.3.3/roma.egg-info/PKG-INFO
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)      349 2023-06-28 08:51:02.000000 roma-1.3.3/roma.egg-info/SOURCES.txt
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)        1 2023-06-28 08:51:02.000000 roma-1.3.3/roma.egg-info/dependency_links.txt
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)        5 2023-06-28 08:51:02.000000 roma-1.3.3/roma.egg-info/top_level.txt
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)       38 2023-06-28 08:51:02.338345 roma-1.3.3/setup.cfg
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)      672 2023-06-21 22:54:26.000000 roma-1.3.3/setup.py
+drwxr-xr-x   0 rbregier (1809414175) DomainUsers (1809400513)        0 2023-06-28 08:51:02.338345 roma-1.3.3/test/
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     1018 2023-02-08 15:17:32.000000 roma-1.3.3/test/test_derivatives.py
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     8457 2023-02-08 15:17:32.000000 roma-1.3.3/test/test_mappings.py
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)     3808 2023-06-21 22:50:53.000000 roma-1.3.3/test/test_procrustes_derivatives.py
+-rw-r--r--   0 rbregier (1809414175) DomainUsers (1809400513)    14887 2023-06-17 20:02:02.000000 roma-1.3.3/test/test_utils.py
```

### Comparing `roma-1.3.2/LICENSE` & `roma-1.3.3/LICENSE`

 * *Files identical despite different names*

### Comparing `roma-1.3.2/NOTICE` & `roma-1.3.3/NOTICE`

 * *Files identical despite different names*

### Comparing `roma-1.3.2/PKG-INFO` & `roma-1.3.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: roma
-Version: 1.3.2
+Version: 1.3.3
 Summary: A lightweight library to deal with 3D rotations in PyTorch.
 Home-page: https://github.com/naver/roma
 Author: Romain Brégier
 Author-email: romain.bregier@naverlabs.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: Free for non-commercial use
 Classifier: Operating System :: OS Independent
```

### Comparing `roma-1.3.2/README.md` & `roma-1.3.3/README.md`

 * *Files identical despite different names*

### Comparing `roma-1.3.2/roma/internal.py` & `roma-1.3.3/roma/internal.py`

 * *Files 11% similar despite different names*

```diff
@@ -70,8 +70,18 @@
         return torch.linalg.eigh(A, UPLO='L')
 except (NameError, AttributeError):
     # Older PyTorch version
     def symeig_lower(A):
         """
         Batched eigenvalue decomposition. Only the lower part of the matrix is considered.
         """
-        return torch.symeig(A, upper=False, eigenvectors=True)
+        return torch.symeig(A, upper=False, eigenvectors=True)
+    
+# L2 normalization
+try:
+    torch.linalg.norm
+    def norm(x, dim=None, keepdim=False):
+        return torch.linalg.norm(x, dim=dim, keepdim=keepdim)
+except AttributeError:
+    # torch.linalg.norm was introduced in PyTorch 1.7, and torch.norm is deprecated.
+    def norm(x, dim=None, keepdim=False):
+        return torch.norm(x, dim=dim, keepdim=keepdim)
```

### Comparing `roma-1.3.2/roma/mappings copy.py` & `roma-1.3.3/roma/mappings copy.py`

 * *Files identical despite different names*

### Comparing `roma-1.3.2/roma/mappings.py` & `roma-1.3.3/roma/mappings.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,81 +18,91 @@
         U, D, V = roma.internal.svd(M)
         if force_rotation:
             # We flip the smallest singular value to ensure getting a rotation matrix
             with torch.no_grad():
                 flip = (torch.det(U) * torch.det(V) < 0)            
             # in-place modifications of variables not used afterwards.
             DS = D
-            DS[flip, -1] *= -1
+            DS[flip,-1] *= -1
             del D
             US = U
             US[flip,:,-1] *= -1
             del U
         else:
             flip = None
             DS = D
             US = U
         R = US @ V.transpose(-1, -2)
         # Store data for backprop:
         ctx.save_for_backward(US, DS, V, M, R)
         ctx.gradient_eps = gradient_eps
         ctx.regularization = regularization
-        return R
+        return R, DS
 
     @staticmethod
-    def backward(ctx, grad_R):
+    def backward(ctx, grad_R, grad_DS):
         US, DS, V, M, R = ctx.saved_tensors
         gradient_eps = ctx.gradient_eps
 
         USik_Vjl = torch.einsum('bik,bjl -> bklij', US, V)
         USil_Vjk = USik_Vjl.transpose(1,2)
         DSl = DS[:,None,:,None,None]
         DSk = DS[:,:,None,None,None]
         Omega_klij = (USik_Vjl - USil_Vjk) * roma.internal._pseudo_inverse(DSk + DSl, gradient_eps)
         # Note: this intermediary matrix may require lots of memory for large dimensional cases.
         # Diagonal k==l should always be 0 thanks to the clamping of the pseudo-inverse.
         
         grad_M = torch.einsum('bnm, bnk, bklij, bml -> bij', grad_R, US, Omega_klij, V)
+        # Gradient contribution from singular values
+        grad_M += (US * grad_DS[:,None,:]) @ V.transpose(-1, -2)
         if ctx.regularization != 0.0:
             # Add a regularization term in the direction of the orthonormalized output.
             grad_M += ctx.regularization * (M - R)
         return grad_M, None, None, None
 
-def procrustes(M, force_rotation=False, regularization=0.0, gradient_eps=1e-5):
+def procrustes(M, force_rotation=False, regularization=0.0, gradient_eps=1e-5, return_singular_values : bool = False):
     """ 
     Returns the orthonormal matrix :math:`R` minimizing Frobenius norm :math:`\| M - R \|_F`.
 
     Args:
         M (...xNxN tensor): batch of square matrices.
         force_rotation (bool): if True, forces the output to be a rotation matrix.
         regularization (float >= 0): weight of a regularization term added to the gradient.
             Using this regularization is equivalent to adding a term :math:`regularization * \| M - R \|_F^2` to the training loss function.
         gradient_eps (float > 0): small value used to enforce numerical stability during backpropagation.
     Returns:
-        batch of orthonormal matrices (...xNxN tensor).
+        batch of orthonormal matrices (...xNxN tensor) and optional singular values.
+        For advanced users, singular values of the SVD decomposition with sign flipping (... tensor) can optionally be returned by setting the argument :code:`return_singular_values` to :code:`True`.
     """
     M, batch_shape = roma.internal.flatten_batch_dims(M, -3)
-    R = _ProcrustesManualDerivatives.apply(M, force_rotation, regularization, gradient_eps)
-    return roma.internal.unflatten_batch_dims(R, batch_shape)
+    R, DS = _ProcrustesManualDerivatives.apply(M, force_rotation, regularization, gradient_eps)
+    R = roma.internal.unflatten_batch_dims(R, batch_shape)
+    if not return_singular_values:
+        return R
+    else:
+        DS = roma.internal.unflatten_batch_dims(DS, batch_shape)
+        return R, DS
 
-def special_procrustes(M, regularization=0.0, gradient_eps=1e-5):
+def special_procrustes(M, regularization=0.0, gradient_eps=1e-5, return_singular_values : bool = False):
     """
     Returns the rotation matrix :math:`R` minimizing Frobenius norm :math:`\| M - R \|_F`.
 
     Args:
         M (...xNxN tensor): batch of square matrices.
         regularization (float >= 0): weight of a regularization term added to the gradient.
             Using this regularization is equivalent to adding a term :math:`regularization * \| M - R \|_F^2` to the training loss function.
         gradient_eps (float > 0): small value used to enforce numerical stability during backpropagation.
     Returns:
         batch of rotation matrices (...xNxN tensor).
+        For advanced users, singular values of the SVD decomposition with sign flipping (... tensor) can optionally be returned by setting the argument :code:`return_singular_values` to :code:`True`.
+
     """
-    return procrustes(M, True, regularization, gradient_eps)
+    return procrustes(M, True, regularization, gradient_eps, return_singular_values)
 
-def procrustes_naive(M, force_rotation : bool = False):
+def procrustes_naive(M, force_rotation : bool = False, return_singular_values : bool = False):
     """
     Implementation of :func:`~roma.mappings.procrustes` relying on default backward pass of autograd and SVD decomposition.
     Could be slightly less stable than :func:`~roma.mappings.procrustes`.
     """
     M, batch_shape = roma.internal.flatten_batch_dims(M, -3)
     assert (M.dim() == 3 and M.shape[1] == M.shape[2]), "Input should be a BxDxD batch of matrices."
     U, D, V = roma.internal.svd(M)
@@ -103,23 +113,31 @@
         with torch.no_grad():
             flip = (torch.det(U) * torch.det(V) < 0)
         if torch.is_grad_enabled():
             # This is needed to avoid a runtime error "one of the variables needed for gradient computation has been modified by an inplace operation"
             SVt = SVt.clone()
         SVt[flip,-1,:] *= -1
     R = U @ SVt
-    return roma.internal.unflatten_batch_dims(R, batch_shape)
+    R = roma.internal.unflatten_batch_dims(R, batch_shape)
+    if not return_singular_values:
+        return R
+    else:
+        DS = D.clone()
+        if force_rotation:
+            DS[flip, -1] *= -1
+        del D
+        return R, DS
 
 
-def special_procrustes_naive(M):
+def special_procrustes_naive(M, return_singular_values : bool = False):
     """
     Implementation of :func:`~roma.mappings.special_procrustes` relying on default backward pass of autograd and SVD decomposition.
     Could be slightly less stable than :func:`~roma.mappings.special_procrustes`.
     """
-    return procrustes_naive(M, force_rotation=True)
+    return procrustes_naive(M, force_rotation=True, return_singular_values=return_singular_values)
 
 def special_gramschmidt(M, epsilon=0):
     """
     Returns the 3x3 rotation matrix obtained by Gram-Schmidt orthonormalization of two 3D input vectors (first two columns of input matrix M).
 
     Args:
         M (...x3xN tensor): batch of 3xN matrices, with N >= 2.
```

### Comparing `roma-1.3.2/roma/utils.py` & `roma-1.3.3/roma/utils.py`

 * *Files 6% similar despite different names*

```diff
@@ -137,14 +137,27 @@
     Returns:
         batch of angles in radians (... tensor).
     """
     R = R1.transpose(-1,-2) @ R2
     cos = rotmat_cosine_angle(R)
     return torch.acos(torch.clamp(cos, -1.0, 1.0))
 
+
+def unitquat_geodesic_distance(q1, q2):
+    """
+    Returns the angular distance alpha between rotations represented by **unit** quaternions.
+    Based on the equality :math:`min |q_2 \pm q_1| = 2 |sin(alpha/4)|`.
+
+    Args:
+        q1, q2 (...x4 tensor, XYZW convention): batch of unit quaternions.
+    Returns:
+        batch of angles in radians (... tensor).
+    """
+    return 4.0 * torch.asin(0.5 * torch.min(roma.internal.norm(q2 - q1, dim=-1), roma.internal.norm(q2 + q1, dim=-1)))
+
 def quat_conjugation(quat):
     """
     Returns the conjugation of input batch of quaternions.
 
     Args:
         quat (...x4 tensor, XYZW convention): batch of quaternions.
     Returns:
@@ -380,46 +393,64 @@
         batch of interpolated rotation matrices (BxAx3x3 tensor).
     """    
     q0 = roma.mappings.rotmat_to_unitquat(R0)
     q1 = roma.mappings.rotmat_to_unitquat(R1)
     interpolated_q = unitquat_slerp(q0, q1, steps, shortest_arc=True)
     return roma.mappings.unitquat_to_rotmat(interpolated_q)
 
-def rigid_vectors_registration(x, y, weights=None):
+def rigid_vectors_registration(x, y, weights=None, compute_scaling=False):
     """
-    Returns the rotation matrix :math:`R` that best aligns an input list of vectors :math:`(x_i)_{i=1...n}` to a target list of vectors :math:`(y_i)_{i=1...n}`
-    by minimizing the sum of square distance :math:`\sum_i w_i \|R x_i - y_i\|^2`, where :math:`(w_i)_{i=1...n}` denotes optional positive weights.
+    Returns the rotation matrix :math:`R` and the optional scaling :math:`s` that best align an input list of vectors :math:`(x_i)_{i=1...n}` to a target list of vectors :math:`(y_i)_{i=1...n}`
+    by minimizing the sum of square distance :math:`\sum_i w_i \|s R x_i - y_i\|^2`, where :math:`(w_i)_{i=1...n}` denotes optional positive weights.
     See :func:`~roma.utils.rigid_points_registration` for details.
 
     Args:
         x (...xNxD tensor): list of N vectors of dimension D.
         y (...xNxD tensor): list of corresponding target vectors.
         weights (None or ...xN tensor): optional list of weights associated to each vector.
     Returns:
-        The rotation matrix :math:`R` (...xDxD tensor).
+        A tuple :math:`(R, t)` consisting of the rotation matrix :math:`R` (...xDxD tensor) and the scaling :math:`s` (... tensor) 
+        if :code:`compute_scaling==True`, the rotation matrix :math:`R` otherwise.
     """
     if weights is None:
-        M = torch.einsum("...ki, ...kj -> ...ij", y, x)
+        n = x.shape[-2]
+        M = torch.einsum("...ki, ...kj -> ...ij", y, x / n)
     else:
+        # Normalize weights
+        weights = weights / torch.sum(weights, dim=-1, keepdim=True)
         M = torch.einsum("...k, ...ki, ...kj -> ...ij", weights, y, x)
-    R = roma.special_procrustes(M)
-    return R
+    if compute_scaling:
+        R, DS = roma.special_procrustes(M, return_singular_values=True)
+        # Using notations from (Umeyema, IEEE TPAMI 1991).
+        DS_trace = torch.sum(DS, dim=-1)
+        if weights is None:
+            sigma2_x = torch.mean(torch.sum(torch.square(x), dim=-1), dim=-1)
+        else:
+            sigma2_x = torch.sum(weights * torch.sum(torch.square(x), dim=-1), dim=-1)    
+        scale = DS_trace / sigma2_x
+        return R, scale
+    else:
+        R = roma.special_procrustes(M)
+        return R
 
-def rigid_points_registration(x, y, weights=None):
+def rigid_points_registration(x, y, weights=None, compute_scaling=False):
     """
-    Returns the rigid transformation :math:`(R,t)` that best aligns an input list of points :math:`(x_i)_{i=1...n}` to a target list of points :math:`(y_i)_{i=1...n}`,
-    by minimizing the sum of square distance :math:`\sum_i w_i \|R x_i + t - y_i\|^2`, where :math:`(w_i)_{i=1...n}` denotes optional positive weights.
+    Returns the rigid transformation :math:`(R,t)` and the optional scaling :math:`s` that best align an input list of points :math:`(x_i)_{i=1...n}` to a target list of points :math:`(y_i)_{i=1...n}`,
+    by minimizing the sum of square distance :math:`\sum_i w_i \|s R x_i + t - y_i\|^2`, where :math:`(w_i)_{i=1...n}` denotes optional positive weights.
     This is sometimes referred to as the Kabsch/Umeyama algorithm.
 
     Args:
         x (...xNxD tensor): list of N points of dimension D.
         y (...xNxD tensor): list of corresponding target points.
         weights (None or ...xN tensor): optional list of weights associated to each point.
     Returns:
-        a tuple :math:`(R, t)` consisting of a rotation matrix :math:`R` (...xDxD tensor) and a translation vector :math:`t` (...xD tensor).
+        a triplet :math:`(R, t, s)` consisting of a rotation matrix :math:`R` (...xDxD tensor), 
+        a translation vector :math:`t` (...xD tensor),
+        and a scaling :math:`s` (... tensor) if :code:`compute_scaling==True`.
+        Returns :math:`(R, t)` otherwise.
 
     References:
         S. Umeyama, “Least-squares estimation of transformation parameters between two point patterns,” IEEE Transactions on pattern analysis and machine intelligence, vol. 13, no. 4, Art. no. 4, 1991.        
 
         W. Kabsch, "A solution for the best rotation to relate two sets of vectors". Acta Crystallographica, A32, 1976.
     """
     # Center data
@@ -430,11 +461,15 @@
         normalized_weights = weights / torch.sum(weights, dim=-1, keepdim=True)
         xmean = torch.sum(normalized_weights[...,None] * x, dim=-2, keepdim=True)
         ymean = torch.sum(normalized_weights[...,None] * y, dim=-2, keepdim=True)
     xhat = x - xmean
     yhat = y - ymean
     
     # Solve the vectors registration problem
-    R = rigid_vectors_registration(xhat, yhat, weights)
-    t = (ymean - torch.einsum('...ik, ...jk -> ...ji', R, xmean)).squeeze(-2)
-    return R, t
-
+    if compute_scaling:
+        R, scale = rigid_vectors_registration(xhat, yhat, weights, compute_scaling=compute_scaling)
+        t = (ymean - torch.einsum('...ik, ...jk -> ...ji', scale[...,None, None] * R, xmean)).squeeze(-2)
+        return R, t, scale
+    else:
+        R = rigid_vectors_registration(xhat, yhat, weights, compute_scaling=compute_scaling)
+        t = (ymean - torch.einsum('...ik, ...jk -> ...ji', R, xmean)).squeeze(-2)
+        return R, t
```

### Comparing `roma-1.3.2/roma.egg-info/PKG-INFO` & `roma-1.3.3/roma.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: roma
-Version: 1.3.2
+Version: 1.3.3
 Summary: A lightweight library to deal with 3D rotations in PyTorch.
 Home-page: https://github.com/naver/roma
 Author: Romain Brégier
 Author-email: romain.bregier@naverlabs.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: Free for non-commercial use
 Classifier: Operating System :: OS Independent
```

### Comparing `roma-1.3.2/setup.py` & `roma-1.3.3/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r", encoding="utf-8") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="roma",
-    version="1.3.2",
+    version="1.3.3",
     author="Romain Brégier",
     author_email="romain.bregier@naverlabs.com",
     description="A lightweight library to deal with 3D rotations in PyTorch.",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/naver/roma",
     packages=["roma"],
```

### Comparing `roma-1.3.2/test/test_derivatives.py` & `roma-1.3.3/test/test_derivatives.py`

 * *Files identical despite different names*

### Comparing `roma-1.3.2/test/test_mappings.py` & `roma-1.3.3/test/test_mappings.py`

 * *Files identical despite different names*

### Comparing `roma-1.3.2/test/test_procrustes_derivatives.py` & `roma-1.3.3/test/test_procrustes_derivatives.py`

 * *Files 12% similar despite different names*

```diff
@@ -20,15 +20,20 @@
         M = torch.randn(batch_size, d, d, dtype=dtype, device=device)
         # Check derivatives
         eps = 1e-7
         eps2 = 1e-4
         for func in (lambda x : roma.procrustes(x),
                     lambda x : roma.special_procrustes(x),
                     lambda x: roma.procrustes_naive(x),
-                    lambda x: roma.special_procrustes_naive(x)):
+                    lambda x: roma.special_procrustes_naive(x),
+                    lambda x: roma.procrustes(x, return_singular_values=True)[1],
+                    lambda x: roma.special_procrustes(x, return_singular_values=True)[1],
+                    lambda x: roma.procrustes_naive(x, return_singular_values=True)[1],
+                    lambda x: roma.special_procrustes_naive(x, return_singular_values=True)[1],
+                    ):
             # Numerical gradient
             num = utils.numerical_jacobian(func, M, eps)
             auto = utils.automatic_jacobian(func, M)
             self.assertTrue(utils.is_close(num, auto, eps2=eps2))
 
     def _test_convergence(self, random_initialization, regularization=0.0):
         """
```

### Comparing `roma-1.3.2/test/test_utils.py` & `roma-1.3.3/test/test_utils.py`

 * *Files 18% similar despite different names*

```diff
@@ -43,15 +43,27 @@
             
             # Right-invariance of the metric
             geo_dist_ter = roma.rotmat_geodesic_distance(R @ M, I[None,:,:] @ M)
             self.assertTrue(is_close(geo_dist_ter, geo_dist))
             
             geo_dist_naive = roma.rotmat_geodesic_distance_naive(M @ R, M @ I[None,:,:])
             self.assertTrue(is_close(torch.abs(alpha), geo_dist_naive))
-        
+
+    def test_unitquat_geodesic_distance(self):
+        batch_size = 100
+        for dtype in (torch.float32, torch.float64):
+            q1 = roma.random_unitquat(batch_size, dtype=dtype)
+            q2 = roma.random_unitquat(batch_size, dtype=dtype)
+            alpha_q = roma.unitquat_geodesic_distance(q1, q2)
+            # Ensure consistency between functions
+            R1 = roma.unitquat_to_rotmat(q1)
+            R2 = roma.unitquat_to_rotmat(q2)
+            alpha_R = roma.rotmat_geodesic_distance(R1, R2)
+            self.assertTrue(is_close(alpha_q, alpha_R))
+
     def test_random_unitquat(self):
         q = roma.random_unitquat((3,5))
         self.assertTrue(q.shape == (3,5,4))
 
         batch_size = 100000
         repetitions = 10
         torch.manual_seed(565441)
@@ -225,25 +237,52 @@
             for weights in [None, torch.rand(size=batch_shape + (n,), dtype=dtype)]:
                 R_true = roma.random_rotmat(batch_shape, dtype=dtype)
                 X = torch.randn(batch_shape + (n, 3,), dtype=dtype)
                 Y = torch.einsum('...ik, ...jk -> ...ji', R_true, X)
                 R = roma.rigid_vectors_registration(X, Y, weights)
                 self.assertTrue(is_close(R, R_true))
 
+    def test_rigid_vectors_registration_with_scale(self):
+        batch_shape = (34, 16)
+        n = 100
+        for dtype in (torch.float32, torch.float64):
+            for weights in [None, torch.rand(size=batch_shape + (n,), dtype=dtype)]:
+                R_true = roma.random_rotmat(batch_shape, dtype=dtype)
+                scale_true = torch.exp(torch.randn(size=batch_shape, dtype=dtype))
+                X = torch.randn(batch_shape + (n, 3,), dtype=dtype)
+                Y = scale_true[...,None, None] * torch.einsum('...ik, ...jk -> ...ji', R_true, X)
+                R, scale = roma.rigid_vectors_registration(X, Y, weights, compute_scaling=True)
+                self.assertTrue(is_close(R, R_true))
+                self.assertTrue(is_close(scale, scale_true))
+
     def test_rigid_point_registration(self):
         batch_shape = (34, 16)
         n = 100
         for dtype in (torch.float32, torch.float64):
             for weights in [None, torch.rand(size=batch_shape + (n,), dtype=dtype)]:
                 R_true = roma.random_rotmat(batch_shape, dtype=dtype)
                 t_true = torch.randn(batch_shape + (3,), dtype=dtype)
                 X = torch.randn(batch_shape + (n, 3,), dtype=dtype)
                 Y = torch.einsum('...ik, ...jk -> ...ji', R_true, X) + t_true.unsqueeze(-2)
                 R, t = roma.rigid_points_registration(X, Y, weights)
 
                 self.assertTrue(is_close(R, R_true))
                 self.assertTrue(is_close(t, t_true))
-  
+
+    def test_rigid_points_registration_with_scale(self):
+        batch_shape = (34, 16)
+        n = 100
+        for dtype in (torch.float32, torch.float64):
+            for weights in [None, torch.rand(size=batch_shape + (n,), dtype=dtype)]:
+                R_true = roma.random_rotmat(batch_shape, dtype=dtype)
+                t_true = torch.randn(batch_shape + (3,), dtype=dtype)
+                scale_true = torch.exp(torch.randn(size=batch_shape, dtype=dtype))
+                X = torch.randn(batch_shape + (n, 3,), dtype=dtype)
+                Y = scale_true[...,None, None] * torch.einsum('...ik, ...jk -> ...ji', R_true, X) + t_true.unsqueeze(-2)
+                R, t, scale = roma.rigid_points_registration(X, Y, weights, compute_scaling=True)
+                self.assertTrue(is_close(R, R_true))
+                self.assertTrue(is_close(t, t_true))
+                self.assertTrue(is_close(scale, scale_true))
         
 if __name__ == "__main__":
     unittest.main()
```

