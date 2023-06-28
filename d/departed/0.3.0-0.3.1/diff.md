# Comparing `tmp/departed-0.3.0-py3-none-any.whl.zip` & `tmp/departed-0.3.1-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,11 +1,11 @@
-Zip file size: 9836 bytes, number of entries: 9
--rw-r--r--  2.0 unx      522 b- defN 23-Apr-06 10:46 departed/__init__.py
--rw-r--r--  2.0 unx     2942 b- defN 23-Apr-06 10:46 departed/_ptrace.py
--rw-r--r--  2.0 unx     1865 b- defN 23-Apr-06 10:46 departed/_ptranspose.py
--rw-r--r--  2.0 unx     1207 b- defN 23-Apr-06 10:46 departed/_utils.py
--rw-r--r--  2.0 unx     7652 b- defN 23-Apr-06 10:47 departed-0.3.0.dist-info/LICENSE
--rw-r--r--  2.0 unx     8464 b- defN 23-Apr-06 10:47 departed-0.3.0.dist-info/METADATA
--rw-r--r--  2.0 unx       92 b- defN 23-Apr-06 10:47 departed-0.3.0.dist-info/WHEEL
--rw-r--r--  2.0 unx        9 b- defN 23-Apr-06 10:47 departed-0.3.0.dist-info/top_level.txt
--rw-rw-r--  2.0 unx      697 b- defN 23-Apr-06 10:47 departed-0.3.0.dist-info/RECORD
-9 files, 23450 bytes uncompressed, 8642 bytes compressed:  63.1%
+Zip file size: 9870 bytes, number of entries: 9
+-rw-r--r--  2.0 unx      522 b- defN 23-Jun-28 00:40 departed/__init__.py
+-rw-r--r--  2.0 unx     2942 b- defN 23-Jun-28 00:40 departed/_ptrace.py
+-rw-r--r--  2.0 unx     1865 b- defN 23-Jun-28 00:40 departed/_ptranspose.py
+-rw-r--r--  2.0 unx     1207 b- defN 23-Jun-28 00:40 departed/_utils.py
+-rw-r--r--  2.0 unx     7652 b- defN 23-Jun-28 00:40 departed-0.3.1.dist-info/LICENSE
+-rw-r--r--  2.0 unx     8649 b- defN 23-Jun-28 00:40 departed-0.3.1.dist-info/METADATA
+-rw-r--r--  2.0 unx       92 b- defN 23-Jun-28 00:40 departed-0.3.1.dist-info/WHEEL
+-rw-r--r--  2.0 unx        9 b- defN 23-Jun-28 00:40 departed-0.3.1.dist-info/top_level.txt
+-rw-rw-r--  2.0 unx      697 b- defN 23-Jun-28 00:40 departed-0.3.1.dist-info/RECORD
+9 files, 23635 bytes uncompressed, 8676 bytes compressed:  63.3%
```

## zipnote {}

```diff
@@ -6,23 +6,23 @@
 
 Filename: departed/_ptranspose.py
 Comment: 
 
 Filename: departed/_utils.py
 Comment: 
 
-Filename: departed-0.3.0.dist-info/LICENSE
+Filename: departed-0.3.1.dist-info/LICENSE
 Comment: 
 
-Filename: departed-0.3.0.dist-info/METADATA
+Filename: departed-0.3.1.dist-info/METADATA
 Comment: 
 
-Filename: departed-0.3.0.dist-info/WHEEL
+Filename: departed-0.3.1.dist-info/WHEEL
 Comment: 
 
-Filename: departed-0.3.0.dist-info/top_level.txt
+Filename: departed-0.3.1.dist-info/top_level.txt
 Comment: 
 
-Filename: departed-0.3.0.dist-info/RECORD
+Filename: departed-0.3.1.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## departed/__init__.py

```diff
@@ -1,15 +1,15 @@
 # 2021 - 2023 Jan Provaznik (jan@provaznik.pro)
 #
 # Partial trace and transpose operations
 # for matrices with a structure induced by the Kronecker product.
 #
 # See README for detailed discussion of its operating principles.
 
-version = '0.3.0'
+version = '0.3.1'
 
 # Partial trace and partial transpose.
 
 from ._ptrace import ptrace
 from ._ptranspose import ptranspose
 
 # Utilities.
```

## Comparing `departed-0.3.0.dist-info/LICENSE` & `departed-0.3.1.dist-info/LICENSE`

 * *Files identical despite different names*

## Comparing `departed-0.3.0.dist-info/METADATA` & `departed-0.3.1.dist-info/METADATA`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: departed
-Version: 0.3.0
+Version: 0.3.1
 Summary: Partial trace and partial transpose for matrices with Kronecker product structure.
 Home-page: https://provaznik.pro/departed
 Author: Jan Provaznik
 Author-email: jan@provaznik.pro
 License: LGPL
 Description-Content-Type: text/plain
 License-File: LICENSE
@@ -98,86 +98,93 @@
       Suppose that the partial operation should NOT affect the 3rd and 5th
       component. The respective mask [ 1, 1, 0, 1, 0 ] can be constructed with
 
         mask_from_component_list([ 2, 4 ], 5, invert = True),
 
       where setting the optional parameter (invert = True) inverts the mask.
 
-Operating principles of Kronecker product and tensor representation
+Operating principles of Kronecker product and its tensor representation
 
   An understanding of the internal memory layout of matrices with a
   Kronecker-product structure is crucial for both the partial trace and partial
   transpose operations. In both algorithms, the matrix is first reshaped into a
   tensor with the axes of its constituent matrices arranged according to their
   direction, with row axes preceding column axes.
 
   In particular, consider a matrix with a Kronecker-product structure
   comprising N matrices and its tensor representation. The first N axes of the
   tensor are the row axes of its matrix constituents and the last N axes are
   their column axes.
 
   This ordering appears counter-intuitive, however, it follows from the
   internal memory layout of the underlying numpy.ndarray object.
+
+  Example
   
-  To illustrate this concept in greater detail, consider a tensor product of
-  three matrix spaces, where the first matrix space comprises (m x m) matrices,
-  the second one (n x n) matrices, and finally, the third one (o x o) matrices.
-  The product space contains (mno x mno) matrices.
+    To illustrate this concept in greater detail, we consider a tensor product
+    of three matrix spaces, where the first matrix space comprises (m x m)
+    matrices, the second one (n x n) matrices, and finally, the third
+    one (o x o) matrices. The product space contains (mno x mno) matrices.
 
-  Let R be a matrix (with a Kronecker-product structure) from this product
-  space. Its tensor representation can be obtained through
+    Let Q be a matrix (with a Kronecker-product structure) from this product
+    space. Its tensor representation can be obtained through
 
-                    T = R.reshape([ m, n, o, m, n, o ]),
+                      T = Q.reshape([ m, n, o, m, n, o ]),
 
-  where the first three axes of T each correspond to the row axes of matrices
-  from the constituent matrix spaces. The last three axes of T each correspond
-  to the column axes of these matrices. 
+    where the first three axes of the tensor T each correspond to the row axes
+    of matrices from the constituent matrix spaces and the last three axes of
+    the tensor each correspond to the column axes of these matrices. 
 
-  For example, should one have three matrices - A, B, and C - and their 
-  Kronecker product, kron(kron(A, B), C), the element 
+    For example, should one have three matrices - A, B, and C - and their 
+    Kronecker product, kron(kron(A, B), C), the element 
 
-                            T[:, 0, 2, :, 1, 3 ]
+                              T[:, 0, 2, :, 1, 3 ]
 
-  of its tensor representation equals to
+    of its tensor representation equals to
 
-                             A * B[0, 1], * C[2, 3].
+                               A * B[0, 1], * C[2, 3].
+  Remarks
+  
+    Some software libraries use tensors structurally compatible with
+    Kronecker-product matrices to represent quantum states and operations.
 
 Operating principles of partial transpose
 
-  Consider an arbitrary bipartite quantum state
+  Consider an arbitrary bipartite quantum state defined by its density operator
 
-               rho = sum(i, j, k, l) Q(i, j, k, l) |i><j| |k><l|.
+               rho = sum(i, j, k, l) R(i, k, j, l) |i><j| |k><l|,
+
+  where the rank four tensor R(i, k, j, l) determines its coefficients. The
+  order of its indices (axes) follows the tensor representation of matrices
+  with a Kronecker-product structure. Its row indices precede column indices.
 
   We define the partial transpose over the second system as
 
-             pt(rho) = sum(i, j, k, l) Q(i, j, k, l) |i><j| |l><k|
-                     = sum(i, j, k, l) Q(i, j, l, k) |i><j| |k><l|.
+             pt(rho) = sum(i, j, k, l) R(i, k, j, l) |i><j| |l><k|
+                     = sum(i, j, k, l) R(i, l, j, k) |i><j| |k><l|.
 
   If the density operator is encoded in a matrix with a Kronecker-product
-  structure, the partial transpose no longer amounts to a simple exchange of
-  axes. It can be realized by determining the affected indices of the matrix
+  structure, rather than a rank four tensor, the partial transpose no longer
+  amounts to a simple exchange of axes.
+
+  It can be realized by determining the affected indices of the matrix
   and exchanging their values. Not only is this approach cumbersome, but also
   extremely inelegant.
 
   A better alternative is to reshape the matrix into a tensor of appropriate
   rank. The reshaping operation is computationally cheap as it only affects the
   interpretation of the underlying numpy.ndarray object.
 
-  Suppose R is the matrix representation of the state rho. Suppose m and n are
+  Suppose Q is the matrix representation of the state rho. Suppose m and n are
   the dimensions of the individual systems comprising the state. With
 
-                         T = reshape(R, [ m, n, m, n ])
+                         T = reshape(Q, [ m, n, m, n ])
 
-  we obtain a rank four tensor T. But alas, the tensor T is not the same as
-  the tensor Q. The order of their indices is different. We have
-
-                                 T(i, k, j, l)
-
-  instead of the theoretical Q(i, j, k, l). Consequently, the partial transpose
-  corresponds to the exchange of the 2nd and 4th indices
+  we obtain a rank four tensor T. Consequently, the partial transpose
+  corresponds to the exchange of the 2nd and the 4th index,
 
                        pt(T)(i, k, j, l) = T(i, l, j, k).
 
   We can reconstruct the Kronecker representation by reshaping the tensor back
   into the original matrix shape.
 
   This idea can be generalized to an arbitrary number of components. It is
@@ -186,34 +193,32 @@
 
 Operating principles of partial trace
   
   We build on the same ideas we have explored for partial transpose and then
   add a figurative cherry on top: by reordering the tensor, we can perform only
   a single trace operation even if multiple components are to be traced out.
 
-  Let us begin with a bipartite system again with a density matrix
+  Let us begin with a bipartite system again and a density matrix
 
-               rho = sum(i, j, k, l) Q(i, j, k, l) |i><j| |k><l|.
+               rho = sum(i, j, k, l) R(i, k, j, l) |i><j| |k><l|.
 
   We define the partial trace performed over its second component as
 
-         rho' = sum(u) sum(i, j, k, l) Q(i, j, k, l) |i><j| <u|k> <l|u>
-              = sum(i, j, k) Q(i, j, k, k) |i><j|
-              = sum(i, j) [ sum(k) Q(i, j, k, k) ] |i><j|,
+         rho' = sum(u) sum(i, j, k, l) R(i, k, j, l) |i><j| <u|k> <l|u>
+              = sum(i, j, k) R(i, k, j, k) |i><j|
+              = sum(i, j) [ sum(k) R(i, k, j, k) ] |i><j|,
 
   where we have presumed that the individual { |k>, |l> } kets are orthonormal.
 
-  If the density operator is encoded in a matrix with a Kronecker-product
-  structure, the partial trace no longer amounts to a sum over the affected
-  axes. We have already established that the matrix R can be reshaped into
+  If the density operator is encoded in a matrix Q with a Kronecker-product
+  structure, the partial trace can be obtained from its tensor representation
 
-                                 T(i, k, j, l),
+                         T = reshape(Q, [ m, n, m, n ]).
 
-  a tensor with indices different from Q(i, j, k, l). This means that if we
-  wish to obtain the partial trace, we must evaluate
+  To obtain the partial trace, we must evaluate
 
                          M(i, j) = sum(k) T(i, k, j, k),
 
   which defines the elements M(i, j) of the marginal tensor. This approach can
   be extended for multi-partite systems and further optimized. We can permute
   the axes to gather the parts to be traced out into a single block and then
   compute the trace in one go.
```

