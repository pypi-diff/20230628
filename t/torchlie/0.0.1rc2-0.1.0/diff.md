# Comparing `tmp/torchlie-0.0.1rc2.tar.gz` & `tmp/torchlie-0.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "torchlie-0.0.1rc2.tar", last modified: Sat Jun 24 13:20:44 2023, max compression
+gzip compressed data, was "torchlie-0.1.0.tar", last modified: Wed Jun 28 01:56:02 2023, max compression
```

## Comparing `torchlie-0.0.1rc2.tar` & `torchlie-0.1.0.tar`

### file list

```diff
@@ -1,25 +1,25 @@
-drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-24 13:20:44.574214 torchlie-0.0.1rc2/
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1088 2023-06-24 02:43:57.000000 torchlie-0.0.1rc2/LICENSE
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)       43 2023-06-24 02:43:57.000000 torchlie-0.0.1rc2/MANIFEST.in
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      546 2023-06-24 13:20:44.572811 torchlie-0.0.1rc2/PKG-INFO
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)        0 2023-06-24 02:43:57.000000 torchlie-0.0.1rc2/README.md
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)       38 2023-06-24 13:20:44.575132 torchlie-0.0.1rc2/setup.cfg
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1199 2023-06-24 02:43:57.000000 torchlie-0.0.1rc2/setup.py
-drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-24 13:20:44.526805 torchlie-0.0.1rc2/torchlie/
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      586 2023-06-24 13:19:58.000000 torchlie-0.0.1rc2/torchlie/__init__.py
-drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-24 13:20:44.568364 torchlie-0.0.1rc2/torchlie/functional/
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      289 2023-06-24 02:43:57.000000 torchlie-0.0.1rc2/torchlie/functional/__init__.py
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1282 2023-06-24 02:43:57.000000 torchlie-0.0.1rc2/torchlie/functional/check_contexts.py
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      536 2023-06-24 13:08:40.000000 torchlie-0.0.1rc2/torchlie/functional/constants.py
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)    10768 2023-06-24 13:08:40.000000 torchlie-0.0.1rc2/torchlie/functional/lie_group.py
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)    32734 2023-06-24 13:11:27.000000 torchlie-0.0.1rc2/torchlie/functional/se3_impl.py
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)    36013 2023-06-24 13:11:42.000000 torchlie-0.0.1rc2/torchlie/functional/so3_impl.py
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1260 2023-06-24 13:08:41.000000 torchlie-0.0.1rc2/torchlie/functional/utils.py
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     2266 2023-06-24 13:10:17.000000 torchlie-0.0.1rc2/torchlie/global_params.py
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)    20273 2023-06-24 13:08:41.000000 torchlie-0.0.1rc2/torchlie/lie_tensor.py
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     3118 2023-06-24 13:08:41.000000 torchlie-0.0.1rc2/torchlie/types.py
-drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-24 13:20:44.541531 torchlie-0.0.1rc2/torchlie.egg-info/
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      546 2023-06-24 13:20:44.000000 torchlie-0.0.1rc2/torchlie.egg-info/PKG-INFO
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      483 2023-06-24 13:20:44.000000 torchlie-0.0.1rc2/torchlie.egg-info/SOURCES.txt
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)        1 2023-06-24 13:20:44.000000 torchlie-0.0.1rc2/torchlie.egg-info/dependency_links.txt
--rw-rw-r--   0 lep      (1185300626) lep      (1185300626)        9 2023-06-24 13:20:44.000000 torchlie-0.0.1rc2/torchlie.egg-info/top_level.txt
+drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-28 01:56:02.707307 torchlie-0.1.0/
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1088 2023-06-24 02:43:57.000000 torchlie-0.1.0/LICENSE
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)       43 2023-06-24 02:43:57.000000 torchlie-0.1.0/MANIFEST.in
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     8513 2023-06-28 01:56:02.706252 torchlie-0.1.0/PKG-INFO
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     7969 2023-06-27 19:20:40.000000 torchlie-0.1.0/README.md
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)       38 2023-06-28 01:56:02.708178 torchlie-0.1.0/setup.cfg
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1199 2023-06-24 02:43:57.000000 torchlie-0.1.0/setup.py
+drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-28 01:56:02.662660 torchlie-0.1.0/torchlie/
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      607 2023-06-28 01:54:23.000000 torchlie-0.1.0/torchlie/__init__.py
+drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-28 01:56:02.702091 torchlie-0.1.0/torchlie/functional/
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      289 2023-06-24 02:43:57.000000 torchlie-0.1.0/torchlie/functional/__init__.py
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1282 2023-06-24 02:43:57.000000 torchlie-0.1.0/torchlie/functional/check_contexts.py
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      536 2023-06-24 13:08:40.000000 torchlie-0.1.0/torchlie/functional/constants.py
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)    10844 2023-06-27 19:20:40.000000 torchlie-0.1.0/torchlie/functional/lie_group.py
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)    34979 2023-06-27 19:20:40.000000 torchlie-0.1.0/torchlie/functional/se3_impl.py
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)    37887 2023-06-27 19:20:40.000000 torchlie-0.1.0/torchlie/functional/so3_impl.py
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     1260 2023-06-24 13:08:41.000000 torchlie-0.1.0/torchlie/functional/utils.py
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     2266 2023-06-24 18:54:47.000000 torchlie-0.1.0/torchlie/global_params.py
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)    20801 2023-06-27 19:20:40.000000 torchlie-0.1.0/torchlie/lie_tensor.py
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     3118 2023-06-24 13:08:41.000000 torchlie-0.1.0/torchlie/types.py
+drwxrwxr-x   0 lep      (1185300626) lep      (1185300626)        0 2023-06-28 01:56:02.677029 torchlie-0.1.0/torchlie.egg-info/
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)     8513 2023-06-28 01:56:02.000000 torchlie-0.1.0/torchlie.egg-info/PKG-INFO
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)      483 2023-06-28 01:56:02.000000 torchlie-0.1.0/torchlie.egg-info/SOURCES.txt
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)        1 2023-06-28 01:56:02.000000 torchlie-0.1.0/torchlie.egg-info/dependency_links.txt
+-rw-rw-r--   0 lep      (1185300626) lep      (1185300626)        9 2023-06-28 01:56:02.000000 torchlie-0.1.0/torchlie.egg-info/top_level.txt
```

### Comparing `torchlie-0.0.1rc2/LICENSE` & `torchlie-0.1.0/LICENSE`

 * *Files identical despite different names*

### Comparing `torchlie-0.0.1rc2/setup.py` & `torchlie-0.1.0/setup.py`

 * *Files identical despite different names*

### Comparing `torchlie-0.0.1rc2/torchlie/__init__.py` & `torchlie-0.1.0/torchlie/__init__.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,27 +1,29 @@
 # Copyright (c) Meta Platforms, Inc. and affiliates.
 #
 # This source code is licensed under the MIT license found in the
 # LICENSE file in the root directory of this source tree.
-__version__ = "0.0.1.rc2"
+__version__ = "0.1.0"
 
 from .global_params import reset_global_params, set_global_params
 from .lie_tensor import (  # usort: skip
     LieTensor,
     adj,
     as_euclidean,
     as_lietensor,
     cast,
     compose,
     from_tensor,
     inv,
     jcompose,
     jinv,
     jlog,
-    jtransform_from,
+    jtransform,
+    juntransform,
     left_act,
     left_project,
     local,
     log,
-    transform_from,
+    transform,
+    untransform,
 )
 from .types import SE3, SO3, ltype
```

### Comparing `torchlie-0.0.1rc2/torchlie/functional/check_contexts.py` & `torchlie-0.1.0/torchlie/functional/check_contexts.py`

 * *Files identical despite different names*

### Comparing `torchlie-0.0.1rc2/torchlie/functional/constants.py` & `torchlie-0.1.0/torchlie/functional/constants.py`

 * *Files identical despite different names*

### Comparing `torchlie-0.0.1rc2/torchlie/functional/lie_group.py` & `torchlie-0.1.0/torchlie/functional/lie_group.py`

 * *Files 4% similar despite different names*

```diff
@@ -294,16 +294,17 @@
         self.hat = UnaryOperatorFactory(module, "hat")[0]
         self.vee = UnaryOperatorFactory(module, "vee")[0]
         self.lift = UnaryOperatorFactory(module, "lift")[0]
         self.project = UnaryOperatorFactory(module, "project")[0]
         self.compose, self.jcompose = BinaryOperatorFactory(module, "compose")
         self.left_act = GradientOperatorFactory(module, "left_act")[0]
         self.left_project = GradientOperatorFactory(module, "left_project")[0]
-        self.transform_from, self.jtransform_from = BinaryOperatorFactory(
-            module, "transform_from"
+        self.transform, self.jtransform = BinaryOperatorFactory(module, "transform")
+        self.untransform, self.juntransform = BinaryOperatorFactory(
+            module, "untransform"
         )
         if hasattr(module, "QuaternionToRotation"):
             (
                 self.quaternion_to_rotation,
                 self.jquaternion_to_rotation,
             ) = UnaryOperatorFactory(module, "quaternion_to_rotation")
         self.check_group_tensor: _CheckFnType = module.check_group_tensor
```

### Comparing `torchlie-0.0.1rc2/torchlie/functional/se3_impl.py` & `torchlie-0.1.0/torchlie/functional/se3_impl.py`

 * *Files 4% similar despite different names*

```diff
@@ -735,29 +735,29 @@
 
 
 _compose_autograd_fn = Compose.apply
 _jcompose_autograd_fn = _jcompose_impl
 
 
 # -----------------------------------------------------------------------------
-# Transform From
+# Transform
 # -----------------------------------------------------------------------------
-def _transform_from_impl(group: torch.Tensor, tensor: torch.Tensor) -> torch.Tensor:
+def _transform_impl(group: torch.Tensor, tensor: torch.Tensor) -> torch.Tensor:
     check_group_tensor(group)
     check_transform_tensor(tensor)
     ret = group[..., -1:] + group[..., :3] @ tensor.unsqueeze(-1)
     return ret.squeeze(-1)
 
 
-def _jtransform_from_impl(
+def _jtransform_impl(
     group: torch.Tensor, tensor: torch.Tensor
 ) -> Tuple[List[torch.Tensor], torch.Tensor]:
     check_group_tensor(group)
     check_transform_tensor(tensor)
-    ret = _transform_from_impl(group, tensor)
+    ret = _transform_impl(group, tensor)
     size = get_transform_tensor_size(ret)
     jacobian_g = group.new_empty(*size, 3, 6)
     jacobian_g[..., :3] = group[..., :3]
     jacobian_g[..., 3:] = -group[..., :3] @ SO3._hat_autograd_fn(tensor)
     jacobian_p = group[..., :3]
     jacobian_g = jacobian_g.expand(*size, 3, 6).clone()
     jacobian_p = jacobian_p.expand(*size, 3, 3).clone()
@@ -765,15 +765,15 @@
 
 
 class TransformFrom(lie_group.BinaryOperator):
     @classmethod
     def _forward_impl(cls, group, tensor):
         group: torch.Tensor = cast(torch.Tensor, group)
         tensor: torch.Tensor = cast(torch.Tensor, tensor)
-        ret = _transform_from_impl(group, tensor)
+        ret = _transform_impl(group, tensor)
         return ret
 
     @classmethod
     def setup_context(cls, ctx, inputs, outputs):
         # inputs is (group, tensor)
         ctx.save_for_backward(inputs[0], inputs[1])
 
@@ -786,16 +786,79 @@
         grad_input0 = torch.cat(
             (grad_output @ tensor.view(*tensor_size, 1, 3), grad_output), dim=-1
         )
         grad_input1 = group[..., :3].transpose(-1, -2) @ grad_output
         return grad_input0, grad_input1.squeeze(-1)
 
 
-_transform_from_autograd_fn = TransformFrom.apply
-_jtransform_from_autograd_fn = _jtransform_from_impl
+_transform_autograd_fn = TransformFrom.apply
+_jtransform_autograd_fn = _jtransform_impl
+
+
+# -----------------------------------------------------------------------------
+# Untransform
+# -----------------------------------------------------------------------------
+def _untransform_impl(group: torch.Tensor, tensor: torch.Tensor) -> torch.Tensor:
+    check_group_tensor(group)
+    check_transform_tensor(tensor)
+    ret = group[..., :3].transpose(-1, -2) @ (tensor.unsqueeze(-1) - group[..., -1:])
+    return ret.squeeze(-1)
+
+
+def _juntransform_impl(
+    group: torch.Tensor, tensor: torch.Tensor
+) -> Tuple[List[torch.Tensor], torch.Tensor]:
+    check_group_tensor(group)
+    check_transform_tensor(tensor)
+    ret = _untransform_impl(group, tensor)
+    size = get_transform_tensor_size(ret)
+    jacobian_g = group.new_zeros(*size, 3, 6)
+    jacobian_g[..., 0, 0] = -1
+    jacobian_g[..., 1, 1] = -1
+    jacobian_g[..., 2, 2] = -1
+    jacobian_g[..., 3:] = SO3._hat_autograd_fn(ret)
+    jacobian_p = group[..., :3].transpose(-1, -2)
+    jacobian_g = jacobian_g.expand(*size, 3, 6).clone()
+    jacobian_p = jacobian_p.expand(*size, 3, 3).clone()
+    return [jacobian_g, jacobian_p], ret
+
+
+class Untransform(lie_group.BinaryOperator):
+    @classmethod
+    def _forward_impl(cls, group, tensor):
+        group: torch.Tensor = cast(torch.Tensor, group)
+        tensor: torch.Tensor = cast(torch.Tensor, tensor)
+        ret = _untransform_impl(group, tensor)
+        return ret
+
+    @classmethod
+    def setup_context(cls, ctx, inputs, outputs):
+        # inputs is (group, tensor)
+        ctx.save_for_backward(inputs[0], inputs[1])
+
+    @classmethod
+    def backward(cls, ctx, grad_output):
+        group: torch.Tensor = ctx.saved_tensors[0]
+        tensor: torch.Tensor = ctx.saved_tensors[1]
+        tmp_tensor = tensor.unsqueeze(-1) - group[..., -1:]
+        grad_output: torch.Tensor = grad_output.unsqueeze(-1)
+        tensor_size = get_transform_tensor_size(tensor)
+        grad_input1 = group[..., :3] @ grad_output
+        grad_input0 = torch.cat(
+            (
+                tmp_tensor.view(*tensor_size, 3, 1) @ grad_output.transpose(-1, -2),
+                -grad_input1,
+            ),
+            dim=-1,
+        )
+        return grad_input0, grad_input1.squeeze(-1)
+
+
+_untransform_autograd_fn = Untransform.apply
+_juntransform_autograd_fn = _juntransform_impl
 
 
 # -----------------------------------------------------------------------------
 # Lift
 # -----------------------------------------------------------------------------
 def _lift_impl(tensor: torch.Tensor) -> torch.Tensor:
     check_lift_tensor(tensor)
```

### Comparing `torchlie-0.0.1rc2/torchlie/functional/so3_impl.py` & `torchlie-0.1.0/torchlie/functional/so3_impl.py`

 * *Files 4% similar despite different names*

```diff
@@ -667,43 +667,43 @@
 
 
 _compose_autograd_fn = Compose.apply
 _jcompose_autograd_fn = _jcompose_impl
 
 
 # -----------------------------------------------------------------------------
-# Transform From
+# Transform
 # -----------------------------------------------------------------------------
-def _transform_from_impl(group: torch.Tensor, tensor: torch.Tensor) -> torch.Tensor:
+def _transform_impl(group: torch.Tensor, tensor: torch.Tensor) -> torch.Tensor:
     check_group_tensor(group)
     check_transform_tensor(tensor)
     ret = group @ tensor.unsqueeze(-1)
     return ret.squeeze(-1)
 
 
-def _jtransform_from_impl(
+def _jtransform_impl(
     group: torch.Tensor, tensor: torch.Tensor
 ) -> Tuple[List[torch.Tensor], torch.Tensor]:
     check_group_tensor(group)
     check_transform_tensor(tensor)
-    ret = _transform_from_impl(group, tensor)
+    ret = _transform_impl(group, tensor)
     size = get_transform_tensor_size(ret)
     jacobian_g = -group @ _hat_autograd_fn(tensor)
     jacobian_p = group
     jacobian_g = jacobian_g.expand(*size, 3, 3).clone()
     jacobian_p = jacobian_p.expand(*size, 3, 3).clone()
     return [jacobian_g, jacobian_p], ret
 
 
 class TransformFrom(lie_group.BinaryOperator):
     @classmethod
     def _forward_impl(cls, group, tensor):
         group: torch.Tensor = cast(torch.Tensor, group)
         tensor: torch.Tensor = cast(torch.Tensor, tensor)
-        ret = _transform_from_impl(group, tensor)
+        ret = _transform_impl(group, tensor)
         return ret
 
     @classmethod
     def setup_context(cls, ctx, inputs, outputs):
         # inputs is (group, tensor)
         ctx.save_for_backward(inputs[0], inputs[1])
 
@@ -714,16 +714,68 @@
         grad_output: torch.Tensor = grad_output.unsqueeze(-1)
         tensor_size = get_transform_tensor_size(tensor)
         grad_input0 = grad_output @ tensor.view(*tensor_size, 1, 3)
         grad_input1 = group[..., :3].transpose(-1, -2) @ grad_output
         return grad_input0, grad_input1.squeeze(-1)
 
 
-_transform_from_autograd_fn = TransformFrom.apply
-_jtransform_from_autograd_fn = _jtransform_from_impl
+_transform_autograd_fn = TransformFrom.apply
+_jtransform_autograd_fn = _jtransform_impl
+
+
+# -----------------------------------------------------------------------------
+# Untransform
+# -----------------------------------------------------------------------------
+def _untransform_impl(group: torch.Tensor, tensor: torch.Tensor) -> torch.Tensor:
+    check_group_tensor(group)
+    check_transform_tensor(tensor)
+    ret = group.transpose(-1, -2) @ tensor.unsqueeze(-1)
+    return ret.squeeze(-1)
+
+
+def _juntransform_impl(
+    group: torch.Tensor, tensor: torch.Tensor
+) -> Tuple[List[torch.Tensor], torch.Tensor]:
+    check_group_tensor(group)
+    check_transform_tensor(tensor)
+    ret = _untransform_impl(group, tensor)
+    size = get_transform_tensor_size(ret)
+    jacobian_g = _hat_autograd_fn(ret)
+    jacobian_p = group.transpose(-1, -2)
+    jacobian_g = jacobian_g.expand(*size, 3, 3).clone()
+    jacobian_p = jacobian_p.expand(*size, 3, 3).clone()
+    return [jacobian_g, jacobian_p], ret
+
+
+class Untransform(lie_group.BinaryOperator):
+    @classmethod
+    def _forward_impl(cls, group, tensor):
+        group: torch.Tensor = cast(torch.Tensor, group)
+        tensor: torch.Tensor = cast(torch.Tensor, tensor)
+        ret = _untransform_impl(group, tensor)
+        return ret
+
+    @classmethod
+    def setup_context(cls, ctx, inputs, outputs):
+        # inputs is (group, tensor)
+        ctx.save_for_backward(inputs[0], inputs[1])
+
+    @classmethod
+    def backward(cls, ctx, grad_output):
+        group: torch.Tensor = ctx.saved_tensors[0]
+        tensor: torch.Tensor = ctx.saved_tensors[1]
+        grad_output: torch.Tensor = grad_output.unsqueeze(-1)
+        tensor_size = get_transform_tensor_size(tensor)
+        grad_input0 = tensor.view(*tensor_size, 3, 1) @ grad_output.transpose(-1, -2)
+        grad_input1 = group[..., :3] @ grad_output
+        return grad_input0, grad_input1.squeeze(-1)
+
+
+_untransform_autograd_fn = Untransform.apply
+_juntransform_autograd_fn = _juntransform_impl
 
 
 # -----------------------------------------------------------------------------
 # Unit Quaternion to Rotation Matrix
 # -----------------------------------------------------------------------------
 def _quaternion_to_rotation_impl(quaternion: torch.Tensor) -> torch.Tensor:
     check_unit_quaternion(quaternion)
```

### Comparing `torchlie-0.0.1rc2/torchlie/functional/utils.py` & `torchlie-0.1.0/torchlie/functional/utils.py`

 * *Files identical despite different names*

### Comparing `torchlie-0.0.1rc2/torchlie/global_params.py` & `torchlie-0.1.0/torchlie/global_params.py`

 * *Files identical despite different names*

### Comparing `torchlie-0.0.1rc2/torchlie/lie_tensor.py` & `torchlie-0.1.0/torchlie/lie_tensor.py`

 * *Files 5% similar despite different names*

```diff
@@ -279,16 +279,19 @@
 
     def compose(self, other: "LieTensor") -> "LieTensor":
         self._check_ltype(other, "compose")
         return self.from_tensor(
             self.ltype._fn_lib.compose(self._t, other._t), self.ltype
         )
 
-    def transform_from(self, point: torch.Tensor) -> torch.Tensor:
-        return self.ltype._fn_lib.transform_from(self._t, point)
+    def transform(self, point: torch.Tensor) -> torch.Tensor:
+        return self.ltype._fn_lib.transform(self._t, point)
+
+    def untransform(self, point: torch.Tensor) -> torch.Tensor:
+        return self.ltype._fn_lib.untransform(self._t, point)
 
     def left_act(self, matrix: torch.Tensor) -> torch.Tensor:
         return self.ltype._fn_lib.left_act(self._t, matrix)
 
     def left_project(self, matrix: torch.Tensor) -> torch.Tensor:
         return self.ltype._fn_lib.left_project(self._t, matrix)
 
@@ -317,17 +320,22 @@
         self._check_ltype(other, "jcompose")
         jacs: List[torch.Tensor] = []
         op_res = self.from_tensor(
             self.ltype._fn_lib.compose(self._t, other._t, jacobians=jacs), self.ltype
         )
         return jacs, op_res
 
-    def jtransform_from(self, point: torch.Tensor) -> _JFnReturnType:
+    def jtransform(self, point: torch.Tensor) -> _JFnReturnType:
+        jacs: List[torch.Tensor] = []
+        op_res = self.ltype._fn_lib.transform(self._t, point, jacobians=jacs)
+        return jacs, op_res
+
+    def juntransform(self, point: torch.Tensor) -> _JFnReturnType:
         jacs: List[torch.Tensor] = []
-        op_res = self.ltype._fn_lib.transform_from(self._t, point, jacobians=jacs)
+        op_res = self.ltype._fn_lib.untransform(self._t, point, jacobians=jacs)
         return jacs, op_res
 
     def _no_jop(self, input0: TensorType) -> _JFnReturnType:
         raise NotImplementedError
 
     jadjoint = _no_jop
     jhat = _no_jop
@@ -370,15 +378,15 @@
 
     def __matmul__(self, point: TensorType) -> torch.Tensor:
         if isinstance(point, LieTensor):
             raise TypeError(
                 "Incorrect argument for '@' operator. "
                 "Expected a torch.Tensor (x, y, z), but got a LieTensor."
             )
-        return self.transform_from(point)
+        return self.transform(point)
 
     def set_(self, tensor: "LieTensor"):  # type: ignore
         if not isinstance(tensor, LieTensor):
             raise RuntimeError(
                 "LieTensor.set_ is only supported for LieTensor arguments."
             )
         if not tensor.ltype == self.ltype:
@@ -559,16 +567,20 @@
     return group.inv()
 
 
 def compose(group1: LieTensor, group2: LieTensor) -> LieTensor:
     return group1.compose(group2)
 
 
-def transform_from(group1: LieTensor, tensor: torch.Tensor) -> torch.Tensor:
-    return group1.transform_from(tensor)
+def transform(group1: LieTensor, tensor: torch.Tensor) -> torch.Tensor:
+    return group1.transform(tensor)
+
+
+def untransform(group1: LieTensor, tensor: torch.Tensor) -> torch.Tensor:
+    return group1.untransform(tensor)
 
 
 def left_act(group: LieTensor, matrix: torch.Tensor) -> torch.Tensor:
     return group.left_act(matrix)
 
 
 def left_project(group: LieTensor, matrix: torch.Tensor) -> torch.Tensor:
@@ -583,16 +595,20 @@
     return group.jinv()
 
 
 def jcompose(group1: LieTensor, group2: LieTensor) -> _JFnReturnType:
     return group1.jcompose(group2)
 
 
-def jtransform_from(group1: LieTensor, tensor: torch.Tensor) -> _JFnReturnType:
-    return group1.jtransform_from(tensor)
+def jtransform(group1: LieTensor, tensor: torch.Tensor) -> _JFnReturnType:
+    return group1.jtransform(tensor)
+
+
+def juntransform(group1: LieTensor, tensor: torch.Tensor) -> _JFnReturnType:
+    return group1.juntransform(tensor)
 
 
 def retract(group: LieTensor, delta: TensorType) -> LieTensor:
     return group.retract(delta)
 
 
 def local(group1: LieTensor, group2: LieTensor) -> torch.Tensor:
```

### Comparing `torchlie-0.0.1rc2/torchlie/types.py` & `torchlie-0.1.0/torchlie/types.py`

 * *Files identical despite different names*

