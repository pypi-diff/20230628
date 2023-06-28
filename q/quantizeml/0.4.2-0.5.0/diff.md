# Comparing `tmp/quantizeml-0.4.2.tar.gz` & `tmp/quantizeml-0.5.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "quantizeml-0.4.2.tar", last modified: Thu Mar 23 09:25:22 2023, max compression
+gzip compressed data, was "quantizeml-0.5.0.tar", last modified: Wed Jun 28 00:15:30 2023, max compression
```

## Comparing `quantizeml-0.4.2.tar` & `quantizeml-0.5.0.tar`

### file list

```diff
@@ -1,80 +1,80 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-23 09:25:22.135530 quantizeml-0.4.2/
--rw-r--r--   0 root         (0) root         (0)    11358 2023-03-23 09:25:20.000000 quantizeml-0.4.2/LICENSE
--rw-r--r--   0 root         (0) root         (0)       16 2023-03-23 09:25:20.000000 quantizeml-0.4.2/MANIFEST.in
--rw-r--r--   0 root         (0) root         (0)      477 2023-03-23 09:25:22.135530 quantizeml-0.4.2/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      168 2023-03-23 09:25:20.000000 quantizeml-0.4.2/README
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-23 09:25:22.131530 quantizeml-0.4.2/quantizeml/
--rw-r--r--   0 root         (0) root         (0)      122 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/__init__.py
--rw-r--r--   0 root         (0) root         (0)     8695 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/cli.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-23 09:25:22.131530 quantizeml-0.4.2/quantizeml/debugging/
--rw-r--r--   0 root         (0) root         (0)       26 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/debugging/__init__.py
--rw-r--r--   0 root         (0) root         (0)     3824 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/debugging/assertions.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-23 09:25:22.131530 quantizeml-0.4.2/quantizeml/layers/
--rw-r--r--   0 root         (0) root         (0)      511 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/__init__.py
--rw-r--r--   0 root         (0) root         (0)     4082 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/activations.py
--rw-r--r--   0 root         (0) root         (0)     8629 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/attention.py
--rw-r--r--   0 root         (0) root         (0)     7825 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/batch_normalization.py
--rw-r--r--   0 root         (0) root         (0)     2000 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/calibrable.py
--rw-r--r--   0 root         (0) root         (0)    11088 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/convolution.py
--rw-r--r--   0 root         (0) root         (0)    11067 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/decorators.py
--rw-r--r--   0 root         (0) root         (0)     2022 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/dense.py
--rw-r--r--   0 root         (0) root         (0)     9860 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/depthwise_convolution.py
--rw-r--r--   0 root         (0) root         (0)     1393 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/dropout.py
--rw-r--r--   0 root         (0) root         (0)     4761 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/layers.py
--rw-r--r--   0 root         (0) root         (0)     8744 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/normalization.py
--rw-r--r--   0 root         (0) root         (0)     3807 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/pooling.py
--rw-r--r--   0 root         (0) root         (0)     2994 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/quantization_params.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-23 09:25:22.131530 quantizeml-0.4.2/quantizeml/layers/quantizers/
--rw-r--r--   0 root         (0) root         (0)      130 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/quantizers/__init__.py
--rw-r--r--   0 root         (0) root         (0)     4012 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/quantizers/aligned_weight_quantizer.py
--rw-r--r--   0 root         (0) root         (0)     9960 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/quantizers/output_quantizer.py
--rw-r--r--   0 root         (0) root         (0)     4593 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/quantizers/quantizers.py
--rw-r--r--   0 root         (0) root         (0)     4668 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/quantizers/weight_quantizer.py
--rw-r--r--   0 root         (0) root         (0)     5576 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/recorders.py
--rw-r--r--   0 root         (0) root         (0)     2082 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/rescaling.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-23 09:25:22.135530 quantizeml-0.4.2/quantizeml/layers/reshaping/
--rw-r--r--   0 root         (0) root         (0)       93 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/reshaping/__init__.py
--rw-r--r--   0 root         (0) root         (0)     2065 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/reshaping/flatten.py
--rw-r--r--   0 root         (0) root         (0)     7630 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/reshaping/patchify.py
--rw-r--r--   0 root         (0) root         (0)     2195 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/reshaping/permute.py
--rw-r--r--   0 root         (0) root         (0)     1991 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/reshaping/reshape.py
--rw-r--r--   0 root         (0) root         (0)     3476 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/separable_convolution.py
--rw-r--r--   0 root         (0) root         (0)     8800 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/shiftmax.py
--rw-r--r--   0 root         (0) root         (0)     7151 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/layers/vit.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-23 09:25:22.135530 quantizeml-0.4.2/quantizeml/models/
--rw-r--r--   0 root         (0) root         (0)      149 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/__init__.py
--rw-r--r--   0 root         (0) root         (0)     4001 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/check_quantization.py
--rw-r--r--   0 root         (0) root         (0)    17381 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/quantize.py
--rw-r--r--   0 root         (0) root         (0)     1553 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/record.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-23 09:25:22.135530 quantizeml-0.4.2/quantizeml/models/transforms/
--rw-r--r--   0 root         (0) root         (0)      250 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/transforms/__init__.py
--rw-r--r--   0 root         (0) root         (0)     6605 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/transforms/align_relu.py
--rw-r--r--   0 root         (0) root         (0)     7694 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/transforms/align_rescaling.py
--rw-r--r--   0 root         (0) root         (0)     9727 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/transforms/fold_batchnorms.py
--rw-r--r--   0 root         (0) root         (0)     7115 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/transforms/insert_layer.py
--rw-r--r--   0 root         (0) root         (0)     2938 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/transforms/invert_batchnorm_pooling.py
--rw-r--r--   0 root         (0) root         (0)     1668 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/transforms/relu_maxpool.py
--rw-r--r--   0 root         (0) root         (0)     6523 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/transforms/remove_zeropadding2d.py
--rw-r--r--   0 root         (0) root         (0)     6031 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/transforms/replace_lambda.py
--rw-r--r--   0 root         (0) root         (0)     7768 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/transforms/transforms_utils.py
--rw-r--r--   0 root         (0) root         (0)     3202 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/models/utils.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-23 09:25:22.135530 quantizeml-0.4.2/quantizeml/tensors/
--rw-r--r--   0 root         (0) root         (0)      151 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/tensors/__init__.py
--rw-r--r--   0 root         (0) root         (0)    22032 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/tensors/fixed_point.py
--rw-r--r--   0 root         (0) root         (0)     8281 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/tensors/qfloat.py
--rw-r--r--   0 root         (0) root         (0)     6012 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/tensors/qtensor.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-23 09:25:22.135530 quantizeml-0.4.2/quantizeml/tensors/tf_dispatch/
--rw-r--r--   0 root         (0) root         (0)       63 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/tensors/tf_dispatch/__init__.py
--rw-r--r--   0 root         (0) root         (0)    10521 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/tensors/tf_dispatch/math.py
--rw-r--r--   0 root         (0) root         (0)    24855 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/tensors/tf_dispatch/nn.py
--rw-r--r--   0 root         (0) root         (0)    14430 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/tensors/tf_dispatch/reshaping.py
--rw-r--r--   0 root         (0) root         (0)      191 2023-03-23 09:25:20.000000 quantizeml-0.4.2/quantizeml/version.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-03-23 09:25:22.131530 quantizeml-0.4.2/quantizeml.egg-info/
--rw-r--r--   0 root         (0) root         (0)      477 2023-03-23 09:25:22.000000 quantizeml-0.4.2/quantizeml.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     2350 2023-03-23 09:25:22.000000 quantizeml-0.4.2/quantizeml.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-03-23 09:25:22.000000 quantizeml-0.4.2/quantizeml.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       51 2023-03-23 09:25:22.000000 quantizeml-0.4.2/quantizeml.egg-info/entry_points.txt
--rw-r--r--   0 root         (0) root         (0)       33 2023-03-23 09:25:22.000000 quantizeml-0.4.2/quantizeml.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       11 2023-03-23 09:25:22.000000 quantizeml-0.4.2/quantizeml.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)       38 2023-03-23 09:25:22.135530 quantizeml-0.4.2/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     1114 2023-03-23 09:25:19.000000 quantizeml-0.4.2/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:15:30.393261 quantizeml-0.5.0/
+-rw-r--r--   0 root         (0) root         (0)    11358 2023-06-28 00:15:28.000000 quantizeml-0.5.0/LICENSE
+-rw-r--r--   0 root         (0) root         (0)       16 2023-06-28 00:15:28.000000 quantizeml-0.5.0/MANIFEST.in
+-rw-r--r--   0 root         (0) root         (0)      477 2023-06-28 00:15:30.393261 quantizeml-0.5.0/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      168 2023-06-28 00:15:28.000000 quantizeml-0.5.0/README
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:15:30.389261 quantizeml-0.5.0/quantizeml/
+-rw-r--r--   0 root         (0) root         (0)      122 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    10463 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/cli.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:15:30.389261 quantizeml-0.5.0/quantizeml/debugging/
+-rw-r--r--   0 root         (0) root         (0)       26 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/debugging/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     3824 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/debugging/assertions.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:15:30.389261 quantizeml-0.5.0/quantizeml/layers/
+-rw-r--r--   0 root         (0) root         (0)      524 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     4193 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/activations.py
+-rw-r--r--   0 root         (0) root         (0)     8636 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/attention.py
+-rw-r--r--   0 root         (0) root         (0)     7897 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/batch_normalization.py
+-rw-r--r--   0 root         (0) root         (0)    11090 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/convolution.py
+-rw-r--r--   0 root         (0) root         (0)     2024 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/dense.py
+-rw-r--r--   0 root         (0) root         (0)    10067 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/depthwise_convolution.py
+-rw-r--r--   0 root         (0) root         (0)     1394 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/dropout.py
+-rw-r--r--   0 root         (0) root         (0)    10692 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/layers_base.py
+-rw-r--r--   0 root         (0) root         (0)     4763 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/multi_inbounds.py
+-rw-r--r--   0 root         (0) root         (0)     8790 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/normalization.py
+-rw-r--r--   0 root         (0) root         (0)     4147 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/output_observer.py
+-rw-r--r--   0 root         (0) root         (0)     3815 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/pooling.py
+-rw-r--r--   0 root         (0) root         (0)     3238 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/quantization_params.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:15:30.389261 quantizeml-0.5.0/quantizeml/layers/quantizers/
+-rw-r--r--   0 root         (0) root         (0)      130 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/quantizers/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     4012 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/quantizers/aligned_weight_quantizer.py
+-rw-r--r--   0 root         (0) root         (0)     6291 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/quantizers/output_quantizer.py
+-rw-r--r--   0 root         (0) root         (0)     4593 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/quantizers/quantizers.py
+-rw-r--r--   0 root         (0) root         (0)     4377 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/quantizers/weight_quantizer.py
+-rw-r--r--   0 root         (0) root         (0)     5576 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/recorders.py
+-rw-r--r--   0 root         (0) root         (0)     2019 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/rescaling.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:15:30.393261 quantizeml-0.5.0/quantizeml/layers/reshaping/
+-rw-r--r--   0 root         (0) root         (0)       69 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/reshaping/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     2067 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/reshaping/flatten.py
+-rw-r--r--   0 root         (0) root         (0)     2197 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/reshaping/permute.py
+-rw-r--r--   0 root         (0) root         (0)     1992 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/reshaping/reshape.py
+-rw-r--r--   0 root         (0) root         (0)     3478 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/separable_convolution.py
+-rw-r--r--   0 root         (0) root         (0)     8801 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/shiftmax.py
+-rw-r--r--   0 root         (0) root         (0)     7155 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/layers/vit.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:15:30.393261 quantizeml-0.5.0/quantizeml/models/
+-rw-r--r--   0 root         (0) root         (0)      174 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    11761 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/calibrate.py
+-rw-r--r--   0 root         (0) root         (0)     4001 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/check_quantization.py
+-rw-r--r--   0 root         (0) root         (0)    16664 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/quantize.py
+-rw-r--r--   0 root         (0) root         (0)     1553 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/record.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:15:30.393261 quantizeml-0.5.0/quantizeml/models/transforms/
+-rw-r--r--   0 root         (0) root         (0)      248 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/transforms/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     7694 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/transforms/align_rescaling.py
+-rw-r--r--   0 root         (0) root         (0)     9727 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/transforms/fold_batchnorms.py
+-rw-r--r--   0 root         (0) root         (0)     7714 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/transforms/insert_layer.py
+-rw-r--r--   0 root         (0) root         (0)     2938 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/transforms/invert_batchnorm_pooling.py
+-rw-r--r--   0 root         (0) root         (0)     1668 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/transforms/relu_maxpool.py
+-rw-r--r--   0 root         (0) root         (0)     6523 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/transforms/remove_zeropadding2d.py
+-rw-r--r--   0 root         (0) root         (0)     6031 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/transforms/replace_lambda.py
+-rw-r--r--   0 root         (0) root         (0)     1892 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/transforms/sanitize.py
+-rw-r--r--   0 root         (0) root         (0)     7768 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/transforms/transforms_utils.py
+-rw-r--r--   0 root         (0) root         (0)     3202 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/models/utils.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:15:30.393261 quantizeml-0.5.0/quantizeml/tensors/
+-rw-r--r--   0 root         (0) root         (0)       99 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/tensors/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    22032 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/tensors/fixed_point.py
+-rw-r--r--   0 root         (0) root         (0)     8281 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/tensors/qfloat.py
+-rw-r--r--   0 root         (0) root         (0)     6012 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/tensors/qtensor.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:15:30.393261 quantizeml-0.5.0/quantizeml/tensors/tf_dispatch/
+-rw-r--r--   0 root         (0) root         (0)       63 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/tensors/tf_dispatch/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    10521 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/tensors/tf_dispatch/math.py
+-rw-r--r--   0 root         (0) root         (0)    24855 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/tensors/tf_dispatch/nn.py
+-rw-r--r--   0 root         (0) root         (0)    14430 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/tensors/tf_dispatch/reshaping.py
+-rw-r--r--   0 root         (0) root         (0)      191 2023-06-28 00:15:28.000000 quantizeml-0.5.0/quantizeml/version.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 00:15:30.389261 quantizeml-0.5.0/quantizeml.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      477 2023-06-28 00:15:30.000000 quantizeml-0.5.0/quantizeml.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     2353 2023-06-28 00:15:30.000000 quantizeml-0.5.0/quantizeml.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 00:15:30.000000 quantizeml-0.5.0/quantizeml.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       51 2023-06-28 00:15:30.000000 quantizeml-0.5.0/quantizeml.egg-info/entry_points.txt
+-rw-r--r--   0 root         (0) root         (0)       33 2023-06-28 00:15:30.000000 quantizeml-0.5.0/quantizeml.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       11 2023-06-28 00:15:30.000000 quantizeml-0.5.0/quantizeml.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 00:15:30.393261 quantizeml-0.5.0/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     1114 2023-06-28 00:15:27.000000 quantizeml-0.5.0/setup.py
```

### Comparing `quantizeml-0.4.2/LICENSE` & `quantizeml-0.5.0/LICENSE`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/cli.py` & `quantizeml-0.5.0/quantizeml/cli.py`

 * *Files 14% similar despite different names*

```diff
@@ -19,62 +19,72 @@
 """
 
 import argparse
 import json
 import os
 import sys
 import re
+import numpy as np
 
 from .layers import QuantizationParams
 from .models import load_model, quantize, dump_config, check_quantization
 from .models.transforms import insert_rescaling
 
 
-def quantize_model(model_path, quant_config, qparams, output_name=None):
+def quantize_model(model_path, quant_config, qparams, samples, num_samples, batch_size, epochs,
+                   output_name=None):
     """ CLI entry point to quantize a model using the provided configuration.
 
     Args:
         model_path (str): Path to the model to quantize.
         quant_config (str): Path to the quantization configuration file.
-        qparams (QuantizationParams): global quantization parameters
+        qparams (QuantizationParams): global quantization parameters.
+        samples (str): calibration samples file path.
+        num_samples (int): number of samples to use in the provided samples.
+        batch_size (int): batch size for calibration.
+        epochs (int): number of epochs for calibration.
         output_name (str, optional): name of the output quantized model. If none provided
             set a default name as <model>_<config>.h5. Defaults to None.
     """
     # Build name for the output model
     model_name = os.path.splitext(model_path)[0]
 
     # Set default output_name using the config when there is one and the qparams otherwise
     if output_name is None:
         if quant_config:
             output_name = f"{model_name}_{os.path.splitext(os.path.basename(quant_config))[0]}.h5"
         else:
-            # Quantization suffix has a well-identified structure
-            suffix_re = r"(_i\d_w\d_a\d)"
-            p = re.compile(suffix_re)
-            # Look for an existing quantization suffix in the base name
-            match = p.match(model_name)
-            if match:
-                # Only keep the actual base name (group(2) contains the suffix)
-                model_name = match.group(1)
+            # Quantization suffix has a well-identified structure, only keep the actual base name
+            # without it
+            model_name = re.split(r'(_i\d_w\d_a\d)', model_name)[0]
             output_name = f"{model_name}_i{qparams.input_weight_bits}_w{qparams.weight_bits}"\
                           f"_a{qparams.activation_bits}.h5"
 
     # Load the configuration file
     if quant_config:
         with open(quant_config) as f:
             config = json.load(f)
     else:
         config = None
 
     # Load the model
     model = load_model(model_path)
 
+    # Load calibration samples
+    if samples:
+        data = np.load(samples)
+        samples_arr = np.concatenate([data[item] for item in data.files])
+        num_samples = len(samples_arr)
+    else:
+        samples_arr = None
+
     # Quantize the model and save it
     print(f"Quantizing model {model_path} with configuration file {quant_config}.")
-    model_q = quantize(model, q_config=config, qparams=qparams)
+    model_q = quantize(model, q_config=config, qparams=qparams, samples=samples_arr,
+                       num_samples=num_samples, batch_size=batch_size, epochs=epochs)
     model_q.save(output_name, include_optimizer=False)
     print(f"Saved quantized model to {output_name}.")
 
 
 def dump_model_config(model_path, output_name=None):
     """ CLI entry point to dump the quantization configuration from a model.
 
@@ -125,34 +135,52 @@
 def main():
     """ CLI entry point.
 
     Contains an argument parser with specific arguments depending on the model to be created.
     Complete arguments lists available using the -h or --help argument.
 
     """
+    # Define a strictly positive int type for parameters
+    def positive_int(value):
+        ivalue = int(value)
+        if ivalue <= 0:
+            raise argparse.ArgumentTypeError("%s is an invalid value, must be >0." % value)
+        return ivalue
+
     parser = argparse.ArgumentParser()
     sp = parser.add_subparsers(dest="action")
     sp.add_parser("version", help="Display quantizeml version.")
 
     # Quantize arguments
     q_parser = sp.add_parser(
         "quantize", help="Quantize an input model, given a quantization configuration file.")
     q_parser.add_argument("-m", "--model", type=str, required=True, help="Model to quantize")
     q_parser.add_argument("-c", "--quantization_config", type=str, default=None,
                           help="Quantization configuration file")
-    q_parser.add_argument("-a", "--activation_bits", type=int, default=4,
+    q_parser.add_argument("-a", "--activation_bits", type=positive_int, default=8,
                           help="Activation quantization bitwidth")
     q_parser.add_argument("--per_tensor_activations", action='store_true',
                           help="Quantize activations per-tensor")
-    q_parser.add_argument("-w", "--weight_bits", type=int, default=4,
+    q_parser.add_argument("-w", "--weight_bits", type=positive_int, default=8,
                           help="Weight quantization bitwidth")
-    q_parser.add_argument("-i", "--input_weight_bits", type=int, default=8,
+    q_parser.add_argument("-i", "--input_weight_bits", type=positive_int, default=8,
                           help="Input layer weight quantization bitwidth")
-    q_parser.add_argument("-o", "--out_name", type=str,
-                          help="Output quantized model name.")
+    q_parser.add_argument("-b", "--buffer_bits", type=positive_int, default=32,
+                          help="Buffer quantization bitwidth")
+    q_parser.add_argument("-s", "--save_name", type=str,
+                          help="Name for saving the quantized model.")
+    q_parser.add_argument("-sa", "--samples", type=str, default=None,
+                          help="Set of samples to calibrate the model (.npz file).")
+    q_parser.add_argument("-ns", "--num_samples", type=positive_int, default=1024,
+                          help="Number of samples to use for calibration, only used when 'samples'"
+                               " is not provided.")
+    q_parser.add_argument("-bs", "--batch_size", type=positive_int, default=32,
+                          help="Batch size for calibration.")
+    q_parser.add_argument("-e", "--epochs", type=positive_int, default=1,
+                          help="Number of epochs for calibration.")
 
     # Dump config arguments
     c_parser = sp.add_parser("config", help="Extract quantization configuration from a model.")
     c_parser.add_argument("-m", "--model", type=str, required=True,
                           help="Model to extract config from.")
     c_parser.add_argument("-o", "--output_path", type=str, help="Store quantization configuration. "
                           "Defaults to <model>_quant_config.json")
@@ -185,20 +213,25 @@
         else:
             import importlib_metadata as metadata
         print(metadata.version('quantizeml'))
     elif args.action == "quantize":
         qparams = QuantizationParams(activation_bits=args.activation_bits,
                                      per_tensor_activations=args.per_tensor_activations,
                                      weight_bits=args.weight_bits,
-                                     input_weight_bits=args.input_weight_bits)
+                                     input_weight_bits=args.input_weight_bits,
+                                     buffer_bits=args.buffer_bits)
         quantize_model(
             model_path=args.model,
             quant_config=args.quantization_config,
             qparams=qparams,
-            output_name=args.out_name
+            samples=args.samples,
+            num_samples=args.num_samples,
+            batch_size=args.batch_size,
+            epochs=args.epochs,
+            output_name=args.save_name
         )
     elif args.action == "config":
         dump_model_config(
             model_path=args.model,
             output_name=args.output_path,
         )
     elif args.action == "check":
```

### Comparing `quantizeml-0.4.2/quantizeml/debugging/assertions.py` & `quantizeml-0.5.0/quantizeml/debugging/assertions.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/layers/activations.py` & `quantizeml-0.5.0/quantizeml/layers/activations.py`

 * *Files 4% similar despite different names*

```diff
@@ -17,15 +17,16 @@
 
 __all__ = ["QuantizedReLU"]
 
 import numpy as np
 import tensorflow as tf
 import keras
 
-from .decorators import register_quantize_target, rescale_outputs, tensor_inputs
+from .layers_base import (register_quantize_target, rescale_outputs,
+                          tensor_inputs, apply_buffer_bitwidth)
 from .quantizers import AlignedWeightQuantizer, OutputQuantizer
 from ..tensors import FixedPoint, QFloat, QTensor
 
 
 @register_quantize_target(keras.layers.ReLU)
 @tf.keras.utils.register_keras_serializable()
 class QuantizedReLU(keras.layers.Layer):
@@ -38,29 +39,28 @@
     unsupported_args = {
         'negative_slope': 0,
         'threshold': 0}
 
     def __init__(self, *args, max_value=6, quant_config=None, **kwargs):
         super().__init__(*args, **kwargs)
 
-        self.quant_config = quant_config
-        quant_config = quant_config or dict()
+        self.quant_config = quant_config or dict()
 
         # Use quant_config to build quantizers
-        out_quant_cfg = quant_config.get("output_quantizer", False)
+        out_quant_cfg = self.quant_config.get("output_quantizer", False)
         if out_quant_cfg:
             self.out_quantizer = OutputQuantizer(name="output_quantizer", **out_quant_cfg)
         else:
             self.out_quantizer = None
-
+        self.buffer_bitwidth = apply_buffer_bitwidth(self.quant_config, signed=False)
         if max_value is not None:
             # Store max_value
             if isinstance(max_value, np.ndarray):
                 max_value = max_value.item()
-            max_value_quantizer_cfg = quant_config.get("max_value_quantizer", {})
+            max_value_quantizer_cfg = self.quant_config.get("max_value_quantizer", {})
             self.max_value_quantizer = AlignedWeightQuantizer(name="max_value_quantizer",
                                                               signed=False,
                                                               **max_value_quantizer_cfg)
         self.max_value = max_value
 
     @tensor_inputs([QTensor])
     @rescale_outputs
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/attention.py` & `quantizeml-0.5.0/quantizeml/layers/attention.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,20 +16,20 @@
 # ******************************************************************************
 
 __all__ = ["Attention", "string_to_softmax", "QuantizedAttention"]
 
 import keras
 import tensorflow as tf
 
-from .decorators import register_quantize_target, register_aligned_inputs
+from .layers_base import register_quantize_target, register_aligned_inputs, apply_buffer_bitwidth
 from .reshaping import QuantizedReshape, QuantizedPermute
 from .shiftmax import shiftmax, QuantizedShiftmax
 from .recorders import TensorRecorder
 from .quantizers import OutputQuantizer
-from ..tensors import FixedPoint, MAX_BUFFER_BITWIDTH, round_log2, pow2
+from ..tensors import FixedPoint, round_log2, pow2
 
 
 def string_to_softmax(s):
     """
     Convert a string to a softmax function.
     Available options are 'softmax' for standard softmax, 'shiftmax' for
     shiftmax.
@@ -164,29 +164,28 @@
     """
 
     def __init__(self, num_heads, quant_config=None, softmax='shiftmax', **kwargs):
         if softmax != 'shiftmax':
             raise ValueError(
                 "Only shiftmax is supported for quantized attention")
         super().__init__(num_heads=num_heads, softmax=softmax, **kwargs)
-        self.quant_config = quant_config
-        quant_config = quant_config or dict()
+        self.quant_config = quant_config or dict()
 
-        out_quant_cfg = quant_config.get("output_quantizer", False)
+        out_quant_cfg = self.quant_config.get("output_quantizer", False)
         if out_quant_cfg:
             self.out_quantizer = OutputQuantizer(
                 name="output_quantizer", **out_quant_cfg)
         else:
             self.out_quantizer = None
 
         # Override softmax operation
-        softmax_quant_conf = quant_config.get("softmax", None)
+        softmax_quant_conf = self.quant_config.get("softmax", None)
         self.softmax_op = QuantizedShiftmax(
             quant_config=softmax_quant_conf, name="quantized_softmax")
-        self.buffer_bitwidth = MAX_BUFFER_BITWIDTH - 1
+        self.buffer_bitwidth = apply_buffer_bitwidth(self.quant_config, signed=True)
         # Add objects that will store the shift values.
         self.values_shift = TensorRecorder()
 
     def separate_heads(self, x):
         x = QuantizedReshape((-1, self.num_heads, self.dim))(x)
         return QuantizedPermute((2, 1, 3))(x)
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/batch_normalization.py` & `quantizeml-0.5.0/quantizeml/layers/batch_normalization.py`

 * *Files 3% similar despite different names*

```diff
@@ -16,17 +16,18 @@
 # ******************************************************************************
 
 __all__ = ["QuantizedBatchNormalization"]
 
 import tensorflow as tf
 import keras
 
-from .decorators import register_quantize_target, rescale_outputs, tensor_inputs
+from .layers_base import (register_quantize_target, rescale_outputs,
+                          tensor_inputs, apply_buffer_bitwidth)
 from .quantizers import WeightQuantizer, AlignedWeightQuantizer, OutputQuantizer
-from ..tensors import QTensor, BASE_BUFFER_BITWIDTH
+from ..tensors import QTensor
 
 
 @register_quantize_target(keras.layers.BatchNormalization)
 @tf.keras.utils.register_keras_serializable()
 class QuantizedBatchNormalization(keras.layers.Layer):
     """Layer that normalizes its inputs, on the last axis.
 
@@ -87,28 +88,28 @@
     def __init__(self,
                  *args,
                  quant_config=None,
                  axis=-1,
                  epsilon=1e-3,
                  **kwargs):
         super().__init__(*args, **kwargs)
-        quant_config = quant_config or dict()
-        self.quant_config = quant_config
-        out_quant_cfg = quant_config.get("output_quantizer", False)
+        self.quant_config = quant_config or dict()
+        out_quant_cfg = self.quant_config.get("output_quantizer", False)
         if out_quant_cfg:
             self.out_quantizer = OutputQuantizer(
                 name="output_quantizer", **out_quant_cfg)
         else:
             self.out_quantizer = None
-        a_quantizer_cfg = quant_config.get("a_quantizer", {"bitwidth": 8})
-        self.quant_config["a_quantizer"] = a_quantizer_cfg
+        if "a_quantizer" not in self.quant_config:
+            self.quant_config["a_quantizer"] = {"bitwidth": 8}
+        a_quantizer_cfg = self.quant_config["a_quantizer"]
         self.a_quantizer = WeightQuantizer(name="a_quantizer", **a_quantizer_cfg)
-        b_quantizer_cfg = quant_config.get("b_quantizer", {})
+        b_quantizer_cfg = self.quant_config.get("b_quantizer", {})
         self.b_quantizer = AlignedWeightQuantizer(name="b_quantizer", **b_quantizer_cfg)
-        self.buffer_bitwidth = BASE_BUFFER_BITWIDTH - 1
+        self.buffer_bitwidth = apply_buffer_bitwidth(self.quant_config, signed=True)
 
         # Define a small float number to avoid dividing by zero.
         self.epsilon = epsilon
         # Axis on which operation is applied
         self.axis = axis
 
     def build(self, input_shape):
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/convolution.py` & `quantizeml-0.5.0/quantizeml/layers/convolution.py`

 * *Files 1% similar despite different names*

```diff
@@ -18,16 +18,16 @@
 __all__ = ["PaddedConv2D", "QuantizedConv2D", "QuantizedConv2DTranspose"]
 
 import tensorflow as tf
 
 from keras import layers, backend
 from keras.utils import conv_utils
 
-from .decorators import (register_quantize_target, rescale_outputs, tensor_inputs,
-                         neural_layer_init, register_aligned_inputs)
+from .layers_base import (register_quantize_target, rescale_outputs, tensor_inputs,
+                          neural_layer_init, register_aligned_inputs)
 from .quantizers import AlignedWeightQuantizer
 from ..tensors import QTensor, QFloat, FixedPoint
 
 
 def apply_padding(inputs, strides, kernel_size, padding_value):
     """Apply "SAME" padding to the inputs
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/decorators.py` & `quantizeml-0.5.0/quantizeml/layers/layers_base.py`

 * *Files 6% similar despite different names*

```diff
@@ -20,15 +20,15 @@
 
 import inspect
 import tensorflow as tf
 
 from .quantization_params import get_quantization_params
 from .quantizers import WeightQuantizer, AlignedWeightQuantizer, OutputQuantizer
 from .recorders import TensorRecorder
-from ..tensors import FixedPoint, MAX_BUFFER_BITWIDTH, BASE_BUFFER_BITWIDTH
+from ..tensors import FixedPoint
 
 # Mapper to match float layer with its quantized version, populated thanks to
 # `register_quantize_target` decorator on quantized layers.
 _GLOBAL_LAYER_TO_QLAYER = {}
 
 # List of quantized layers that cannot rescale their outputs (no output quantizer)
 _GLOBAL_NO_OUTPUT_QUANTIZER = []
@@ -116,14 +116,15 @@
 
     Args:
         call (Callable): the decorated call function
 
     Returns:
         Callable: the decorated function
     """
+
     def decorator(self, inputs):
         outputs = call(self, inputs)
         if self.out_quantizer is not None:
             outputs = self.out_quantizer(outputs)
         return outputs
     return decorator
 
@@ -133,54 +134,37 @@
 
     Args:
         supported (list): list of supported input types
 
     Returns:
         Callable: the decorated function
     """
-    def _get_weight_quantizer_bitwidth(obj):
-        quantizer_attr = [getattr(obj, name) for name in dir(obj) if name.endswith('quantizer')]
-        for quant in quantizer_attr:
-            if isinstance(quant, WeightQuantizer):
-                return quant.bitwidth
-        # Some layers only have an AlignedWeightQuantizer
-        for quant in quantizer_attr:
-            if isinstance(quant, AlignedWeightQuantizer):
-                return quant.bitwidth
-        return None
 
     def decorator(call):
         if not isinstance(supported, (list, tuple)):
             raise TypeError(f"'supported' must be a list or a tuple, received {type(supported)}.")
 
         def check_inputs(self, inputs):
             # Raise an error if the inputs are not in the 'supported' types
             if not isinstance(inputs, tuple(supported)):
                 raise TypeError(f"{self.__class__.__name__} only accepts {supported} inputs. "
                                 f"Receives {type(inputs)} inputs.")
 
             if isinstance(inputs, tf.Tensor):
-                # Assume the inputs are 8 bit integer stored as float, which is the only tf.Tensor
+                # Assume the inputs are 8 bit integer, which is the only tf.Tensor
                 # inputs that are allowed
+                if not inputs.dtype.is_integer:
+                    # Remove decimal part, through an intermediate cast
+                    inputs = tf.cast(inputs, tf.int32)
                 inputs = FixedPoint(inputs, 8, 0)
 
             if getattr(self, 'buffer_bitwidth', None) is not None:
-                # Adapt buffer_bitwidth: excluding the effect of accumulations (sums or negations)
-                # because the training regularization tends to center them around zero, worst case
-                # is: input_bits * 2 (with expand) + weights_bits + scale_bits,
-                # so as long as inputs or weights are not 4bits, buffer_bitwidth must be
-                # MAX_BUFFER_BITWIDTH - 1.
-                if self.buffer_bitwidth != MAX_BUFFER_BITWIDTH - 1:
-                    weight_bits = _get_weight_quantizer_bitwidth(self)
-                    if weight_bits and (inputs.value_bits > 4 or weight_bits > 4):
-                        self.buffer_bitwidth = MAX_BUFFER_BITWIDTH - 1
-
                 if (isinstance(inputs, FixedPoint) and not inputs.per_tensor
                         and self.__class__.__name__ not in
-                        ['QuantizedDepthwiseConv2D', 'QuantizedExtractToken']):
+                        ['QuantizedDepthwiseConv2D', 'QuantizedExtractToken', 'QuantizedReLU']):
                     # Expand the inputs to a higher bitwidth to avoid saturation and align them.
                     # Depthwise layers do not require input_shift because each channel is
                     # handled by a single filter.
                     inputs, shift = inputs.expand(self.buffer_bitwidth)
                     if getattr(self, 'input_shift', None) is None:
                         # Add object that will store the shift values.
                         # From Keras documentation, any variable creation taking place in call
@@ -211,49 +195,68 @@
             super_init = getattr(super(type(self), self), "__init__")
             # Handle special parameter "padding_value" that must not be passed to super()
             updated_kwargs = kwargs.copy()
             updated_kwargs.pop('padding_value', None)
             super_init(*args, **updated_kwargs)
 
             # Then start neural layer init
-            quant_config = quant_config or dict()
-            self.quant_config = quant_config
+            self.quant_config = quant_config or dict()
             default_weight_bits = get_quantization_params().weight_bits
 
             # Use quant_config to build quantizers
             if separable:
                 # Separable layer has two weights quantizers to handle different max values
-                dw_weight_quantizer_cfg = quant_config.get("dw_weight_quantizer",
-                                                           {"bitwidth": default_weight_bits})
-                # Separable depthwise weights are quantized per tensor
-                dw_weight_quantizer_cfg.update({'axis': "per-tensor"})
-                self.quant_config['dw_weight_quantizer'] = dw_weight_quantizer_cfg
+                if "dw_weight_quantizer" not in self.quant_config:
+                    self.quant_config["dw_weight_quantizer"] = {"bitwidth": default_weight_bits}
+                dw_weight_quantizer_cfg = self.quant_config["dw_weight_quantizer"]
+                # Separable depthwise weights are quantized per-tensor
+                dw_weight_quantizer_cfg.update({'axis': None})
                 self.dw_weight_quantizer = WeightQuantizer(name="dw_weight_quantizer",
                                                            **dw_weight_quantizer_cfg)
-                pw_weight_quantizer_cfg = quant_config.get("pw_weight_quantizer",
-                                                           {"bitwidth": default_weight_bits})
-                self.quant_config['pw_weight_quantizer'] = pw_weight_quantizer_cfg
+                if "pw_weight_quantizer" not in self.quant_config:
+                    self.quant_config["pw_weight_quantizer"] = {"bitwidth": default_weight_bits}
+                pw_weight_quantizer_cfg = self.quant_config["pw_weight_quantizer"]
                 self.pw_weight_quantizer = WeightQuantizer(name="pw_weight_quantizer",
                                                            **pw_weight_quantizer_cfg)
             else:
-                weight_quantizer_cfg = quant_config.get("weight_quantizer",
-                                                        {"bitwidth": default_weight_bits})
-                self.quant_config['weight_quantizer'] = weight_quantizer_cfg
+                if "weight_quantizer" not in self.quant_config:
+                    self.quant_config["weight_quantizer"] = {"bitwidth": default_weight_bits}
+                weight_quantizer_cfg = self.quant_config["weight_quantizer"]
                 self.weight_quantizer = WeightQuantizer(name="weight_quantizer",
                                                         **weight_quantizer_cfg)
 
             # Finalize output and bias quantizers
-            out_quant_cfg = quant_config.get("output_quantizer", False)
+            out_quant_cfg = self.quant_config.get("output_quantizer", False)
             if out_quant_cfg:
                 self.out_quantizer = OutputQuantizer(name="output_quantizer", **out_quant_cfg)
             else:
                 self.out_quantizer = None
             if self.use_bias:
-                bias_quantizer_cfg = quant_config.get("bias_quantizer", {})
+                bias_quantizer_cfg = self.quant_config.get("bias_quantizer", {})
                 self.bias_quantizer = AlignedWeightQuantizer(name="bias_quantizer",
                                                              **bias_quantizer_cfg)
-            self.buffer_bitwidth = BASE_BUFFER_BITWIDTH - 1
+            self.buffer_bitwidth = apply_buffer_bitwidth(self.quant_config, signed=True)
 
             # Baseline init
             init(self, *args, **kwargs)
         return wrapper
     return decorator
+
+
+def apply_buffer_bitwidth(quant_config, signed=True):
+    """ Read buffer_bitwidth on quant_config. If it is missing,
+    set 'buffer_bitwidth' parameter in ``quant_config`` with default value given by the context.
+
+    Args:
+        quant_config (dict): the serialized quantization configuration.
+        signed (bool, optional): whether operations will be done with sign. Defaults to True.
+
+    Returns:
+        int: buffer bitwidth value
+    """
+    buffer_bits = quant_config.get("buffer_bitwidth", None)
+    if buffer_bits is None:
+        buffer_bits = get_quantization_params().buffer_bits
+        quant_config["buffer_bitwidth"] = buffer_bits
+    if signed:
+        buffer_bits -= 1
+    return buffer_bits
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/dense.py` & `quantizeml-0.5.0/quantizeml/layers/dense.py`

 * *Files 11% similar despite different names*

```diff
@@ -16,16 +16,16 @@
 # ******************************************************************************
 
 __all__ = ["QuantizedDense"]
 
 import tensorflow as tf
 import keras
 
-from .decorators import (register_quantize_target, rescale_outputs, tensor_inputs,
-                         neural_layer_init, register_aligned_inputs)
+from .layers_base import (register_quantize_target, rescale_outputs, tensor_inputs,
+                          neural_layer_init, register_aligned_inputs)
 from ..tensors import QTensor
 
 
 @register_quantize_target(keras.layers.Dense)
 @register_aligned_inputs
 @tf.keras.utils.register_keras_serializable()
 class QuantizedDense(keras.layers.Dense):
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/depthwise_convolution.py` & `quantizeml-0.5.0/quantizeml/layers/depthwise_convolution.py`

 * *Files 3% similar despite different names*

```diff
@@ -23,31 +23,34 @@
 
 
 import tensorflow as tf
 from keras import backend
 from keras.layers import DepthwiseConv2D
 from keras.utils import conv_utils
 
-from .decorators import (register_quantize_target, rescale_outputs, tensor_inputs,
-                         neural_layer_init, register_aligned_inputs)
+from .layers_base import (register_quantize_target, rescale_outputs, tensor_inputs,
+                          neural_layer_init, register_aligned_inputs)
 from ..tensors import FixedPoint, QFloat
 
 
 @register_quantize_target(DepthwiseConv2D)
 @register_aligned_inputs
 @tf.keras.utils.register_keras_serializable()
 class QuantizedDepthwiseConv2D(DepthwiseConv2D):
     """ A depthwise convolutional layer that operates on quantized inputs and weights.
 
     Args:
         quant_config (dict, optional): the serialized quantization configuration. Defaults to None.
     """
     @neural_layer_init(False)
     def __init__(self, *args, quant_config=None, **kwargs):
-        pass
+        # Override WeightQuantizer axis to -2 which corresponds to the channel dimension of the
+        # depthwise operation.
+        self.weight_quantizer.axis = -2
+        self.quant_config['weight_quantizer']['axis'] = -2
 
     @tensor_inputs([FixedPoint, tf.Tensor])
     @rescale_outputs
     def call(self, inputs):
         # Quantize the weights
         depthwise_kernel = self.weight_quantizer(self.depthwise_kernel)
 
@@ -155,20 +158,20 @@
 
     Args:
         quant_config (dict, optional): the serialized quantization
           configuration. Defaults to None.
     """
     @neural_layer_init(separable=False)
     def __init__(self, *args, quant_config=None, **kwargs):
-        # By default neural_layer_init quantizer will be set per-axis, but
+        # By default neural_layer_init quantizer will be set to -1 (per-axis), but
         # in this very layer it will need to be set per-tensor to complete
         # the conv2d transpose operation. Weight quantizer axis is overridden,
         # and quant_config is updated accordingly.
-        self.weight_quantizer.axis = "per-tensor"
-        self.quant_config['weight_quantizer']['axis'] = 'per-tensor'
+        self.weight_quantizer.axis = None
+        self.quant_config['weight_quantizer']['axis'] = None
 
     @tensor_inputs([FixedPoint])
     @rescale_outputs
     def call(self, inputs):
         # Infer the dynamic output shape
         inputs_shape = tf.shape(inputs)
         out_height = conv_utils.deconv_output_length(
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/dropout.py` & `quantizeml-0.5.0/quantizeml/layers/dropout.py`

 * *Files 4% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 # ******************************************************************************
 
 __all__ = ["QuantizedDropout"]
 
 import keras
 import tensorflow as tf
 
-from .decorators import register_quantize_target, tensor_inputs, register_no_output_quantizer
+from .layers_base import register_quantize_target, tensor_inputs, register_no_output_quantizer
 from ..tensors import QTensor
 
 
 @register_quantize_target(keras.layers.Dropout)
 @register_no_output_quantizer
 @tf.keras.utils.register_keras_serializable()
 class QuantizedDropout(keras.layers.Dropout):
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/layers.py` & `quantizeml-0.5.0/quantizeml/layers/multi_inbounds.py`

 * *Files 6% similar despite different names*

```diff
@@ -16,19 +16,19 @@
 # ******************************************************************************
 
 __all__ = ["Add", "QuantizedAdd", "QuantizedConcatenate"]
 
 import keras
 import tensorflow as tf
 
-from .decorators import (register_quantize_target, rescale_outputs, register_no_output_quantizer,
-                         register_aligned_inputs)
+from .layers_base import (register_quantize_target, rescale_outputs, register_no_output_quantizer,
+                          register_aligned_inputs, apply_buffer_bitwidth)
 from .quantizers import OutputQuantizer
 from .recorders import TensorRecorder
-from ..tensors import FixedPoint, BASE_BUFFER_BITWIDTH
+from ..tensors import FixedPoint
 
 
 @tf.keras.utils.register_keras_serializable()
 class Add(keras.layers.Layer):
     """Wrapper class of `keras.layers.Add` that allows to average inputs.
 
     We only support a tuple of two inputs with the same shape.
@@ -71,18 +71,17 @@
 
     Args:
         quant_config (dict, optional): the serialized quantization configuration. Defaults to None.
     """
 
     def __init__(self, *args, quant_config=None, **kwargs):
         super().__init__(*args, **kwargs)
-        self.quant_config = quant_config
-        quant_config = quant_config or dict()
-        self.buffer_bitwidth = BASE_BUFFER_BITWIDTH - 1
-        out_quant_cfg = quant_config.get("output_quantizer", False)
+        self.quant_config = quant_config or dict()
+        self.buffer_bitwidth = apply_buffer_bitwidth(self.quant_config, signed=True)
+        out_quant_cfg = self.quant_config.get("output_quantizer", False)
         if out_quant_cfg:
             self.out_quantizer = OutputQuantizer(
                 name="output_quantizer", **out_quant_cfg)
         else:
             self.out_quantizer = None
         # Add objects that will store the shift values.
         self.a_shift = TensorRecorder()
@@ -119,14 +118,15 @@
 @register_quantize_target(keras.layers.Concatenate)
 @register_no_output_quantizer
 @register_aligned_inputs
 @tf.keras.utils.register_keras_serializable()
 class QuantizedConcatenate(keras.layers.Concatenate):
     """ A Concatenate layer that operates on quantized inputs
     """
+
     def call(self, inputs):
         a, b = inputs
         if not (isinstance(a, FixedPoint) and isinstance(b, FixedPoint)):
             # If any of the inputs is not a FixedPoint, raise an error
             raise TypeError(f"QuantizedConcatenate only accepts FixedPoint\
                               inputs. Receives {(type(a), type(b))} inputs.")
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/normalization.py` & `quantizeml-0.5.0/quantizeml/layers/normalization.py`

 * *Files 2% similar despite different names*

```diff
@@ -17,19 +17,19 @@
 
 __all__ = ["QuantizedLayerNormalization", "LayerMadNormalization"]
 
 import tensorflow as tf
 import keras
 from tensorflow.python.framework import ops
 
-from .decorators import (register_quantize_target, rescale_outputs, tensor_inputs,
-                         register_aligned_inputs)
+from .layers_base import (register_quantize_target, rescale_outputs, tensor_inputs,
+                          register_aligned_inputs, apply_buffer_bitwidth)
 from .recorders import TensorRecorder
 from .quantizers import AlignedWeightQuantizer, WeightQuantizer, OutputQuantizer
-from ..tensors import FixedPoint, BASE_BUFFER_BITWIDTH
+from ..tensors import FixedPoint
 
 
 @tf.keras.utils.register_keras_serializable()
 class LayerMadNormalization(keras.layers.LayerNormalization):
     r"""Approximates the `keras.layers.LayerNormalization` (LN), replacing the computation of
     the standard deviation by the mean average deviation (mad).
 
@@ -120,29 +120,30 @@
 @tf.keras.utils.register_keras_serializable()
 class QuantizedLayerNormalization(LayerMadNormalization):
     """ A LayerNormalization layer that operates on quantized inputs and weights.
 
     Args:
         quant_config (dict, optional): the serialized quantization configuration. Defaults to None.
     """
+
     def __init__(self, *args, quant_config=None, **kwargs):
         super().__init__(*args, **kwargs)
-        quant_config = quant_config or dict()
-        self.quant_config = quant_config
-        out_quant_cfg = quant_config.get("output_quantizer", False)
+        self.quant_config = quant_config or dict()
+        out_quant_cfg = self.quant_config.get("output_quantizer", False)
         if out_quant_cfg:
             self.out_quantizer = OutputQuantizer(
                 name="output_quantizer", **out_quant_cfg)
         else:
             self.out_quantizer = None
-        self.buffer_bitwidth = BASE_BUFFER_BITWIDTH - 1
-        gamma_quantizer_cfg = quant_config.get("gamma_quantizer", {"bitwidth": 8})
-        self.quant_config["gamma_quantizer"] = gamma_quantizer_cfg
+        self.buffer_bitwidth = apply_buffer_bitwidth(self.quant_config, signed=True)
+        if "gamma_quantizer" not in self.quant_config:
+            self.quant_config["gamma_quantizer"] = {"bitwidth": 8}
+        gamma_quantizer_cfg = self.quant_config["gamma_quantizer"]
         self.gamma_quantizer = WeightQuantizer(name="gamma_quantizer", **gamma_quantizer_cfg)
-        beta_quantizer_cfg = quant_config.get("beta_quantizer", {})
+        beta_quantizer_cfg = self.quant_config.get("beta_quantizer", {})
         self.beta_quantizer = AlignedWeightQuantizer(name="beta_quantizer", **beta_quantizer_cfg)
 
         # Add objects that will store the shift values.
         self.gamma_shift = TensorRecorder()
 
     @tensor_inputs([FixedPoint])
     @rescale_outputs
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/pooling.py` & `quantizeml-0.5.0/quantizeml/layers/pooling.py`

 * *Files 4% similar despite different names*

```diff
@@ -18,18 +18,18 @@
 __all__ = ["QuantizedMaxPool2D", "QuantizedGlobalAveragePooling2D"]
 
 import tensorflow as tf
 
 from keras.layers import MaxPool2D, GlobalAveragePooling2D
 from keras.utils import conv_utils
 
-from .decorators import (register_quantize_target, register_no_output_quantizer, rescale_outputs,
-                         tensor_inputs)
+from .layers_base import (register_quantize_target, register_no_output_quantizer, rescale_outputs,
+                          tensor_inputs, apply_buffer_bitwidth)
 from .quantizers import OutputQuantizer
-from ..tensors import FixedPoint, QTensor, QFloat, MAX_BUFFER_BITWIDTH
+from ..tensors import FixedPoint, QTensor, QFloat
 
 
 @register_quantize_target(MaxPool2D)
 @register_no_output_quantizer
 @tf.keras.utils.register_keras_serializable()
 class QuantizedMaxPool2D(MaxPool2D):
     """A max pooling layer that operates on quantized inputs.
@@ -58,23 +58,22 @@
 
      Args:
         quant_config (dict, optional): the serialized quantization configuration. Defaults to None.
     """
 
     def __init__(self, quant_config=None, **kwargs):
         super().__init__(**kwargs)
-        self.quant_config = quant_config
-        quant_config = quant_config or dict()
-        out_quant_cfg = quant_config.get("output_quantizer", False)
+        self.quant_config = quant_config or dict()
+        out_quant_cfg = self.quant_config.get("output_quantizer", False)
         if out_quant_cfg:
             self.out_quantizer = OutputQuantizer(
                 name="output_quantizer", **out_quant_cfg)
         else:
             self.out_quantizer = None
-        self.buffer_bitwidth = MAX_BUFFER_BITWIDTH
+        self.buffer_bitwidth = apply_buffer_bitwidth(self.quant_config, signed=False)
 
     def build(self, input_shape):
         super().build(input_shape)
         # Build the spatial size and its reciprocal
         self.spatial_size = (input_shape[1] * input_shape[2])
         self.spatial_size_rec = 1. / self.spatial_size
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/quantization_params.py` & `quantizeml-0.5.0/quantizeml/layers/quantization_params.py`

 * *Files 8% similar despite different names*

```diff
@@ -22,29 +22,33 @@
 
 class QuantizationParams:
     """ Class that holds quantization parameters.
 
     This is a read-only data class.
 
     Args:
-        activation_bits (int, optional): activations quantization bitwidth. Defaults to 4.
+        activation_bits (int, optional): activations quantization bitwidth. Defaults to 8.
         per_tensor_activations (bool, optional); whether to quantize activation per-tensor or
             per-axis. Defaults to False.
-        weight_bits (int, optional): weights quantization bitwidth. Defaults to 4.
+        weight_bits (int, optional): weights quantization bitwidth. Defaults to 8.
         output_bits (int, optional): outputs quantization bitwidth. Defaults to 8.
         input_weight_bits (int, optional): weights quantization bitwidth for the first layer.
             Defaults to 8.
+        buffer_bits (int, optional): maximal buffer bitwidth allowed in operations.
+            Defaults to 32.
     """
-    def __init__(self, activation_bits=4, per_tensor_activations=False, weight_bits=4,
-                 output_bits=8, input_weight_bits=8):
+
+    def __init__(self, activation_bits=8, per_tensor_activations=False, weight_bits=8,
+                 output_bits=8, input_weight_bits=8, buffer_bits=32):
         self._activation_bits = activation_bits
         self._per_tensor_activations = per_tensor_activations
         self._weight_bits = weight_bits
         self._output_bits = output_bits
         self._input_weight_bits = input_weight_bits
+        self._buffer_bits = buffer_bits
 
     @property
     def activation_bits(self):
         return self._activation_bits
 
     @property
     def per_tensor_activations(self):
@@ -58,14 +62,18 @@
     def output_bits(self):
         return self._output_bits
 
     @property
     def input_weight_bits(self):
         return self._input_weight_bits
 
+    @property
+    def buffer_bits(self):
+        return self._buffer_bits
+
 
 _quantization = QuantizationParams()
 
 
 def get_quantization_params():
     """ Returns global quantization parameters.
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/quantizers/aligned_weight_quantizer.py` & `quantizeml-0.5.0/quantizeml/layers/quantizers/aligned_weight_quantizer.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/layers/quantizers/quantizers.py` & `quantizeml-0.5.0/quantizeml/layers/quantizers/quantizers.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/layers/quantizers/weight_quantizer.py` & `quantizeml-0.5.0/quantizeml/layers/quantizers/weight_quantizer.py`

 * *Files 6% similar despite different names*

```diff
@@ -34,39 +34,36 @@
           quantization,
         - quantizes the rescaled Tensor as a FixedPoint and returns a QFloat.
 
     Args:
         bitwidth (int, optional): the quantization bitwidth, defaults to 4.
         signed (bool, optional): whether the quantizer expects signed values or unsigned.
             Defaults to True.
-        axis (str, optional): the quantization range is a scalar ('per-tensor') or a vector
-            corresponding to the last axis ('per-axis'). Defaults to 'per-axis'.
+        axis (int, optional): the quantization range is a scalar (None) or a vector corresponding to
+            the given axis. Defaults to -1.
     """
 
-    def __init__(self, bitwidth=4, signed=True, axis="per-axis", **kwargs):
+    def __init__(self, bitwidth=4, signed=True, axis=-1, **kwargs):
         super().__init__(bitwidth, signed, **kwargs)
         self.axis = axis
-        if not (isinstance(axis, str) and axis in ["per-tensor", "per-axis"]):
-            raise ValueError(f"Only support reduction 'per-tensor' or 'per-axis'. Given {axis}.")
         self.qweights = QFloatRecorder()
 
     def build(self, input_shape):
         """Build the layer.
 
         Args:
             input_shape (list): the shape of input tensor.
         """
         # Convert axis to a list of int
-        if self.axis == "per-axis" and len(input_shape) > 1:
-            axis_list = list(range(len(input_shape) - 1))
-            # When input_shape last dimension is 1, move operation from axis -1 to axis -2 by
-            # adding 1 to the last element in the list. Practical use case is for Depthwise kernels
-            # that will be quantized per-channel.
-            if input_shape[-1] == 1 and len(input_shape) > 2:
-                axis_list[-1] = axis_list[-1] + 1
+        if self.axis is not None and len(input_shape) > 1:
+            axis_list = list(range(len(input_shape)))
+            positive_axis = self.axis if self.axis >= 0 else len(axis_list) + self.axis
+            if positive_axis < 0 or positive_axis > len(axis_list) - 1:
+                raise ValueError(f"Axis {self.axis} is not valid in {self.name}.")
+            axis_list.pop(positive_axis)
             self._axis = axis_list
         else:
             self._axis = None
 
     def call(self, inputs):
         """Quantize the float inputs
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/recorders.py` & `quantizeml-0.5.0/quantizeml/layers/recorders.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/layers/rescaling.py` & `quantizeml-0.5.0/quantizeml/layers/rescaling.py`

 * *Files 19% similar despite different names*

```diff
@@ -16,16 +16,16 @@
 # ******************************************************************************
 
 __all__ = ["QuantizedRescaling"]
 
 import tensorflow as tf
 import keras
 
-from .decorators import register_quantize_target, register_no_output_quantizer
-from ..tensors import FixedPoint, QFloat
+from .layers_base import register_quantize_target, register_no_output_quantizer, tensor_inputs
+from ..tensors import QFloat
 
 
 @register_quantize_target(keras.layers.Rescaling)
 @register_no_output_quantizer
 @tf.keras.utils.register_keras_serializable()
 class QuantizedRescaling(keras.layers.Rescaling):
     """A layer that multiplies integer inputs by a scale
@@ -45,12 +45,11 @@
     def __init__(self, scale, **kwargs):
         super().__init__(scale, **kwargs)
         if tf.rank(self.scale) > 0:
             raise ValueError("QuantizedRescaling only accepts scalar scale.")
         if tf.reduce_any(self.offset != 0):
             raise ValueError("QuantizedRescaling only accepts zero offset.")
 
+    @tensor_inputs([tf.Tensor])
     def call(self, inputs):
-        # Assume the inputs are 8-bit unsigned integer
-        fp = FixedPoint(tf.round(inputs), 8, 0)
         # Wrap them into a QFloat with the specified scale
-        return QFloat(fp, self.scale)
+        return QFloat(inputs, self.scale)
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/reshaping/flatten.py` & `quantizeml-0.5.0/quantizeml/layers/reshaping/flatten.py`

 * *Files 7% similar despite different names*

```diff
@@ -18,16 +18,16 @@
 __all__ = ["QuantizedFlatten"]
 
 import tensorflow as tf
 import keras
 import functools
 import operator
 
-from ..decorators import (register_quantize_target, tensor_inputs, register_no_output_quantizer,
-                          register_aligned_inputs)
+from ..layers_base import (register_quantize_target, tensor_inputs, register_no_output_quantizer,
+                           register_aligned_inputs)
 from ..recorders import TensorRecorder
 from ...tensors import FixedPoint
 
 
 @register_quantize_target(keras.layers.Flatten)
 @register_no_output_quantizer
 @register_aligned_inputs
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/reshaping/permute.py` & `quantizeml-0.5.0/quantizeml/layers/reshaping/permute.py`

 * *Files 6% similar despite different names*

```diff
@@ -16,16 +16,16 @@
 # ******************************************************************************
 
 __all__ = ["QuantizedPermute"]
 
 import tensorflow as tf
 import keras
 
-from ..decorators import (register_quantize_target, tensor_inputs, register_no_output_quantizer,
-                          register_aligned_inputs)
+from ..layers_base import (register_quantize_target, tensor_inputs, register_no_output_quantizer,
+                           register_aligned_inputs)
 from ...tensors import FixedPoint
 from ...debugging import assert_equal
 
 
 @register_quantize_target(keras.layers.Permute)
 @register_no_output_quantizer
 @register_aligned_inputs
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/reshaping/reshape.py` & `quantizeml-0.5.0/quantizeml/layers/reshaping/reshape.py`

 * *Files 3% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 # ******************************************************************************
 
 __all__ = ["QuantizedReshape"]
 
 import tensorflow as tf
 import keras
 
-from ..decorators import register_quantize_target, tensor_inputs, register_no_output_quantizer
+from ..layers_base import register_quantize_target, tensor_inputs, register_no_output_quantizer
 from ...tensors import QTensor, FixedPoint
 
 
 @register_quantize_target(keras.layers.Reshape)
 @register_no_output_quantizer
 @tf.keras.utils.register_keras_serializable()
 class QuantizedReshape(keras.layers.Reshape):
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/separable_convolution.py` & `quantizeml-0.5.0/quantizeml/layers/separable_convolution.py`

 * *Files 1% similar despite different names*

```diff
@@ -21,16 +21,16 @@
 __all__ = ["QuantizedSeparableConv2D"]
 
 import tensorflow as tf
 from keras.layers import SeparableConv2D
 from keras.utils import conv_utils
 from keras import backend
 
-from .decorators import (register_quantize_target, rescale_outputs, tensor_inputs,
-                         neural_layer_init, register_aligned_inputs)
+from .layers_base import (register_quantize_target, rescale_outputs, tensor_inputs,
+                          neural_layer_init, register_aligned_inputs)
 from ..tensors import FixedPoint
 
 
 @register_quantize_target(SeparableConv2D)
 @register_aligned_inputs
 @tf.keras.utils.register_keras_serializable()
 class QuantizedSeparableConv2D(SeparableConv2D):
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/shiftmax.py` & `quantizeml-0.5.0/quantizeml/layers/shiftmax.py`

 * *Files 3% similar despite different names*

```diff
@@ -16,18 +16,18 @@
 # ******************************************************************************
 
 __all__ = ["shiftmax", "Shiftmax", "QuantizedShiftmax"]
 
 import tensorflow as tf
 import keras
 
-from .decorators import (register_quantize_target, register_no_output_quantizer,
-                         register_aligned_inputs)
+from .layers_base import (register_quantize_target, register_no_output_quantizer,
+                          register_aligned_inputs, apply_buffer_bitwidth)
 from .recorders import TensorRecorder
-from ..tensors import FixedPoint, floor_through, round_log2, MAX_BUFFER_BITWIDTH, pow2
+from ..tensors import FixedPoint, floor_through, round_log2, pow2
 
 
 def shiftmax(logits, axis=-1):
     """Computes softmax-like activations, but using base 2 for the exponential.
 
     Used as approximation of the softmax activation.
 
@@ -126,18 +126,17 @@
 
     Args:
         quant_config (dict, optional): the serialized quantization configuration. Defaults to None.
     """
 
     def __init__(self, *args, quant_config=None, **kwargs):
         super().__init__(*args, **kwargs)
-        self.quant_config = quant_config
-        quant_config = quant_config or dict()
-        self.buffer_bitwidth = MAX_BUFFER_BITWIDTH - 1
-        self.exp_bitwidth = quant_config.get("exp_bitwidth", 10)
+        self.quant_config = quant_config or dict()
+        self.buffer_bitwidth = apply_buffer_bitwidth(self.quant_config, signed=True)
+        self.exp_bitwidth = self.quant_config.get("exp_bitwidth", 10)
         if self.buffer_bitwidth <= 2 * self.exp_bitwidth:
             raise ValueError(f"exp_bitwidth={self.exp_bitwidth} must be less than "
                              f"half of buffer_size={self.buffer_bitwidth}.")
         # Add objects that will store the shift values.
         self.input_shift = TensorRecorder()
 
     def call(self, x):
@@ -147,15 +146,15 @@
                             f"{type(x)} inputs.")
 
         # To avoid overflowing, some modifications are made to the input.
         # First remove the fractional part of the input (floor(x)). We can do
         # this because the exponential function will return very big numbers,
         # so fractional ones can be ignored in the ratio with the sum.
         x, shift = x.floor()
-        # update shift values if calibration is enabled
+        # update shift values if recording is enabled
         self.input_shift(shift)
 
         # Since x has been floored, we can directly use its values
         x = x.values
 
         # The pseudo-softmax is defined as:
         #
```

### Comparing `quantizeml-0.4.2/quantizeml/layers/vit.py` & `quantizeml-0.5.0/quantizeml/layers/vit.py`

 * *Files 8% similar despite different names*

```diff
@@ -18,18 +18,18 @@
 __all__ = ["ClassToken", "QuantizedClassToken",
            "AddPositionEmbs", "QuantizedAddPositionEmbs",
            "ExtractToken", "QuantizedExtractToken"]
 
 import keras
 import tensorflow as tf
 
-from .decorators import (register_quantize_target, register_no_output_quantizer, rescale_outputs,
-                         tensor_inputs, register_aligned_inputs)
+from .layers_base import (register_quantize_target, register_no_output_quantizer, rescale_outputs,
+                          tensor_inputs, register_aligned_inputs, apply_buffer_bitwidth)
 from .quantizers import AlignedWeightQuantizer, OutputQuantizer
-from ..tensors import QFloat, FixedPoint, BASE_BUFFER_BITWIDTH
+from ..tensors import QFloat, FixedPoint
 
 
 @tf.keras.utils.register_keras_serializable()
 class ClassToken(keras.layers.Layer):
     """Append a class token to an input layer.
 
     Args:
@@ -101,19 +101,18 @@
 
     Args:
         quant_config (dict, optional): the serialized quantization configuration. Defaults to None.
     """
 
     def __init__(self, *args, quant_config=None, **kwargs):
         super().__init__(*args, **kwargs)
-        self.quant_config = quant_config
-        quant_config = quant_config or dict()
-        cls_quantizer_cfg = quant_config.get("cls_quantizer", {})
+        self.quant_config = quant_config or dict()
+        cls_quantizer_cfg = self.quant_config.get("cls_quantizer", {})
         self.cls_quantizer = AlignedWeightQuantizer(name="cls_quantizer", **cls_quantizer_cfg)
-        self.buffer_bitwidth = BASE_BUFFER_BITWIDTH - 1
+        self.buffer_bitwidth = apply_buffer_bitwidth(self.quant_config, signed=True)
 
     @tensor_inputs([QFloat])
     def call(self, inputs):
         batch_size = tf.shape(inputs.values)[0]
 
         # Quantize the token and align it with the inputs
         cls = self.cls_quantizer(self.cls, inputs)
@@ -136,25 +135,24 @@
 
     Args:
         quant_config (dict, optional): the serialized quantization configuration. Defaults to None.
     """
 
     def __init__(self, *args, quant_config=None, **kwargs):
         super().__init__(*args, **kwargs)
-        self.quant_config = quant_config
-        quant_config = quant_config or dict()
-        out_quant_cfg = quant_config.get("output_quantizer", False)
+        self.quant_config = quant_config or dict()
+        out_quant_cfg = self.quant_config.get("output_quantizer", False)
         if out_quant_cfg:
             self.out_quantizer = OutputQuantizer(
                 name="output_quantizer", **out_quant_cfg)
         else:
             self.out_quantizer = None
-        pe_quantizer_cfg = quant_config.get("pe_quantizer", {})
+        pe_quantizer_cfg = self.quant_config.get("pe_quantizer", {})
         self.pe_quantizer = AlignedWeightQuantizer(name="pe_quantizer", **pe_quantizer_cfg)
-        self.buffer_bitwidth = BASE_BUFFER_BITWIDTH - 1
+        self.buffer_bitwidth = apply_buffer_bitwidth(self.quant_config, signed=True)
 
     @tensor_inputs([QFloat])
     @rescale_outputs
     def call(self, inputs):
         # Quantize position embeddings and align them on the inputs
         pe = self.pe_quantizer(self.pe, inputs)
```

### Comparing `quantizeml-0.4.2/quantizeml/models/check_quantization.py` & `quantizeml-0.5.0/quantizeml/models/check_quantization.py`

 * *Files 4% similar despite different names*

```diff
@@ -39,16 +39,16 @@
     record_quantization_variables(model)
 
     messages = []
     for layer in model.layers:
         for _, attr in layer.__dict__.items():
             if isinstance(attr, OutputQuantizer):
                 quantizer = attr
-                max_value = quantizer.get_weights()[0]
-                if tf.reduce_all(max_value == 1):
+                range_max = quantizer.get_weights()[0]
+                if tf.reduce_all(range_max == 1):
                     messages.append(f"{layer.name}/{quantizer.name} is not calibrated.")
                     continue
                 # Evaluate the maximum left shift for this quantizer
                 maximum_shift = quantizer.value_bits - layer.buffer_bitwidth
                 # There might be a saturation in integer operations if we reached the maximum shift
                 output_shift = quantizer.shift.value
                 if tf.reduce_any(output_shift <= maximum_shift):
```

### Comparing `quantizeml-0.4.2/quantizeml/models/quantize.py` & `quantizeml-0.5.0/quantizeml/models/quantize.py`

 * *Files 5% similar despite different names*

```diff
@@ -11,29 +11,28 @@
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 # ******************************************************************************
 
+__all__ = ["quantize", "dump_config"]
+
 import warnings
-import tensorflow as tf
 
 from keras import Model, layers
 
 from .utils import deep_clone_model
-from .transforms import (insert_layer, align_rescaling, invert_batchnorm_pooling, fold_batchnorms,
-                         align_relu_max_value, remove_zeropadding2d, invert_relu_maxpool,
-                         replace_lambda)
-from ..layers import (OutputQuantizer, WeightQuantizer, QuantizedReLU, Dequantizer, quantization,
-                      QuantizationParams, get_quantization_params, UnfoldPatches, FoldPatches,
-                      Attention, QuantizedConv2D, QuantizedDepthwiseConv2D,
-                      QuantizedSeparableConv2D, QuantizedDense)
-from ..layers.decorators import (_GLOBAL_LAYER_TO_QLAYER, _GLOBAL_NO_OUTPUT_QUANTIZER,
-                                 _GLOBAL_ALIGNED_INPUTS)
+from .transforms import insert_layer, sanitize
+from .calibrate import calibrate
+from ..layers import (OutputQuantizer, WeightQuantizer, Dequantizer, quantization,
+                      QuantizationParams, get_quantization_params, Attention, QuantizedConv2D,
+                      QuantizedDepthwiseConv2D, QuantizedSeparableConv2D, QuantizedDense)
+from ..layers.layers_base import (_GLOBAL_LAYER_TO_QLAYER, _GLOBAL_NO_OUTPUT_QUANTIZER,
+                                  _GLOBAL_ALIGNED_INPUTS)
 
 
 # List of Quantizer layer's that do not have a float layer representation
 NO_FLOAT_CUSTOM_QLAYERS = [Dequantizer, OutputQuantizer, WeightQuantizer]
 
 
 def get_quantized_layer(layer):
@@ -96,29 +95,14 @@
                 warnings.warn(f"'{layer.name}' of type {layer.__class__} is not supported to "
                               "quantize, a Dequantizer is added before it and quantization will "
                               "stop at this layer.")
                 return model
     return model
 
 
-def _initialize_quantizedrelu_outquantizer(qmodel):
-    """ Initialize QuantizeReLU out_quantizer max_value in the given model.
-
-    Since inputs are clipped to the ReLU max_value, the upper bound of the OutputQuantizer max_value
-    is known.
-
-    Args:
-        qmodel (keras.Model): a quantized model
-    """
-    for ly in qmodel.layers:
-        if isinstance(ly, QuantizedReLU) and ly.out_quantizer and ly.max_value:
-            max_value = tf.fill(ly.out_quantizer.max_value.shape, ly.max_value)
-            OutputQuantizer._assign_new_value(ly.out_quantizer.max_value, max_value)
-
-
 def _prepare_output_quantizers(model):
     """ Parse the model and prepare OutputQuantizer configurations for layers requiring them.
 
     To ensure that an OutputQuantizer will be added to the latest possible layer in a 'block', the
     model is parsed in reverse order. If a layer requires aligned inputs, the function will find the
     preceding layer that can accept an OutputQuantizer and set it in the returned dictionary.
 
@@ -136,37 +120,37 @@
 
     def set_output_quantizer(layer_names, next_layer):
         """ Populates `out_quantizer_configs` with layer names and their OutputQuantizer. """
         for name in layer_names:
             current_layer = model.get_layer(name)
             # Handle special cases were the OutputQuantizer must be per-tensor:
             # - when current_layer has vector outputs,
-            # - when next_layer is an UnfoldPatches or FoldPatches layer
             # - when next_layer is an Attention layer and the layer is Query or Key
             #   (first and second inputs)
             if isinstance(current_layer, Attention):
                 output_shape = current_layer.output_shape[0]
             else:
                 output_shape = current_layer.output_shape
             vector_outputs = len(output_shape) < 3
-            patches_next = isinstance(next_layer, (UnfoldPatches, FoldPatches))
             query_or_key = (isinstance(current_layer, layers.Dense)
                             and isinstance(next_layer, Attention)
                             and next_layer.inbound_nodes[0].inbound_layers.
                             index(current_layer) in [0, 1])
-            per_tensor = patches_next or query_or_key or vector_outputs
+            per_tensor = query_or_key or vector_outputs
 
             if isinstance(current_layer, layers.ReLU):
                 per_tensor = per_tensor or qparams.per_tensor_activations
 
             # If this is a new entry, set a default configuration
             if name not in out_quantizer_configs:
                 axis = "per-tensor" if per_tensor else "per-axis"
                 if isinstance(current_layer, layers.ReLU):
-                    params = dict(bitwidth=qparams.activation_bits, signed=False, axis=axis)
+                    params = dict(bitwidth=qparams.activation_bits,
+                                  signed=qparams.activation_bits >= 8,
+                                  axis=axis)
                 else:
                     params = dict(bitwidth=qparams.output_bits, axis=axis)
                 out_quantizer_configs[name] = dict(output_quantizer=params)
 
             # If the layer OutputQuantizer configuration is already set, simply check the axis:
             # override the config if the outputs must be per-tensor
             else:
@@ -208,15 +192,16 @@
             previous_layers = get_preceding_layer_names(layer)
             # Set an OutputQuantizer in their inbounds
             set_output_quantizer(previous_layers, layer)
 
     return out_quantizer_configs
 
 
-def quantize(model, q_config=None, qparams=QuantizationParams()):
+def quantize(model, q_config=None, qparams=QuantizationParams(), samples=None, num_samples=1024,
+             batch_size=None, epochs=1):
     """Quantizes the model using the provided configuration or parameters.
 
     Details on how this function behaves:
 
     - `q_config` has priority over `qparams`, meaning that when a match is found in `q_config` the
       given configuration will be used instead of `qparams`. This is useful to handle specific cases
       (e.g per-tensor output quantizer).
@@ -224,20 +209,28 @@
       OutputQuantizers are automatically set on appropriate layers.
     - `qparams` are only applied to 'float' Keras layers when they are first quantized. As a result,
       when re-quantizing a model, one must provide a complete `q_config`. This is made easy with the
       `dump_config` helper.
 
     If not already present, a final Dequantizer will be added at the end of the Model.
 
+    The model will also be calibrated using the provided (or randomly generated inputs).
+
     Args:
         model (keras.Model): the model to quantize
         q_config (dict, optional): quantization configuration as a dictionary mapping layer names to
             their quantization configuration. Defaults to None.
         qparams (QuantizationParams, optional): global quantization parameters. Defaults to
             QuantizationParams().
+        samples (tf.Dataset, np.array or generator, optional): calibration samples. When no samples
+            are provided, random samples are generated. Defaults to None.
+        num_samples (int, optional): number of samples to use in the provided samples or number of
+            samples to generate. Defaults to 1024.
+        batch_size (int, optional): the batch size. Defaults to None.
+        epochs (int, optional): the number of epochs. Defaults to 1.
 
     Returns:
         keras.Model: the quantized model
     """
     q_config = q_config or dict()
 
     # Layers will no longer be quantized as soon as a Dequantizer is found
@@ -245,15 +238,16 @@
 
     # Handle input_weight_bits using another QuantizationParams where
     # weight_bits = qparams.input_weight_bits, it will be set to False once the input layer has been
     # quantized.
     input_qparams = QuantizationParams(activation_bits=qparams.activation_bits,
                                        per_tensor_activations=qparams.per_tensor_activations,
                                        weight_bits=qparams.input_weight_bits,
-                                       output_bits=qparams.output_bits)
+                                       output_bits=qparams.output_bits,
+                                       buffer_bits=qparams.buffer_bits)
 
     def _replace_layer(layer):
         nonlocal quantization_stopped, out_quantizer_configs, input_qparams
         config = layer.get_config()
 
         # Function to handle unsupported arguments in config
         def pop_unsupported_args(class_type):
@@ -321,56 +315,40 @@
         # When the qlayer is an input layer that has been quantized, disable input_qparams
         input_layers = (QuantizedConv2D, QuantizedDepthwiseConv2D, QuantizedSeparableConv2D,
                         QuantizedDense)
         if input_qparams and isinstance(qlayer, input_layers):
             input_qparams = False
         return qlayer
 
-    # Replace lambda layers
-    model = replace_lambda(model)
-
-    # Align Rescaling (if needed)
-    model = align_rescaling(model)
-
-    # Invert ReLU <-> MaxPool layers so that MaxPool comes first
-    model = invert_relu_maxpool(model)
-
-    # Invert BN <-> Pooling layers and fold BN into their preceding layers
-    model = invert_batchnorm_pooling(model)
-    model = fold_batchnorms(model)
-
-    # Remove unsupported ZeroPadding2D layers and replace them with 'same' padding convolution when
-    # possible
-    model = remove_zeropadding2d(model)
+    # Sanitize the model and make it quantization ready
+    model = sanitize(model)
 
     # Check if the model has not quantizable layers and add a Dequantizer before
     model = _handle_not_quantizable_layers(model)
 
     # Quantize the model replacing layers with their quantized version
     with quantization(qparams):
         # Determine where to set OutputQuantizers, the return dict will be used as a non-local
         # variable in the _replace_layer function.
         out_quantizer_configs = _prepare_output_quantizers(model)
 
         new_model = deep_clone_model(model, clone_function=_replace_layer)
-        out = new_model.outputs
-
-        # Append Dequantizer at the end of the model to convert the output to float value
-        if not isinstance(new_model.layers[-1], Dequantizer) and not quantization_stopped:
-            out = Dequantizer()(out)
-
-        # Build the model
-        qmodel = Model(new_model.input, out, name=model.name)
-
-        # Align ReLU max_value to the maximum integer value the OutputQuantizer can use
-        qmodel = align_relu_max_value(qmodel)
 
-        # Initialize QuantizeReLU out_quantizer max_value
-        _initialize_quantizedrelu_outquantizer(qmodel)
+    out = new_model.outputs
 
+    # Append Dequantizer at the end of the model to convert the output to float value
+    if not isinstance(new_model.layers[-1], Dequantizer) and not quantization_stopped:
+        out = Dequantizer()(out)
+
+    # Build the model
+    qmodel = Model(new_model.input, out, name=model.name)
+
+    # Now that the model is quantized, proceed to calibration
+    calibrate(model, qmodel, samples=samples, num_samples=num_samples, batch_size=batch_size,
+              epochs=epochs)
     return qmodel
 
 
 def dump_config(model):
     """Dump the quantization configuration of a quantized model, exporting the configuration for
     each quantized layer.
```

### Comparing `quantizeml-0.4.2/quantizeml/models/record.py` & `quantizeml-0.5.0/quantizeml/models/record.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/models/transforms/align_rescaling.py` & `quantizeml-0.5.0/quantizeml/models/transforms/align_rescaling.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/models/transforms/fold_batchnorms.py` & `quantizeml-0.5.0/quantizeml/models/transforms/fold_batchnorms.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/models/transforms/insert_layer.py` & `quantizeml-0.5.0/quantizeml/models/transforms/insert_layer.py`

 * *Files 7% similar despite different names*

```diff
@@ -27,33 +27,25 @@
 
 from .transforms_utils import (get_layer_index, inbound_node_generator,
                                replace_layer_name_for_connection_info)
 from ..utils import apply_weights_to_model
 from ...layers.quantizers import OutputQuantizer, Dequantizer
 
 
-def _insert_layer(model, target_layer_name, new_layer):
-    """ Inserts the given layer in the model after the layer with the name target_layer_name.
+def insert_in_config(model, target_layer_name, new_layer, config):
+    """ Inserts the given layer in the model after the layer with the name target_layer_name by
+    editing the given configuration.
 
     Args:
         model (keras.Model): the model to update
         target_layer_name (str): name of the layer after which to insert a layer
         new_layer (keras.layers.Layer): layer to insert
-
-    Returns:
-        keras.Model: the new model
+        config (dict): model dict config being updated
     """
-    # Check that the model has a layer with then given target_layer_name
-    if not any(ly.name == target_layer_name for ly in model.layers):
-        raise ValueError(f'{target_layer_name} not found in model.')
-
-    # get_config documentation mentions that a copy should be made when planning to modify the
-    # config
-    config = deepcopy(model.get_config())
-    layers = config['layers']
+    layers_config = config['layers']
 
     # Prepare the layer configuration to be inserted
     new_layer_config = serialize(new_layer)
 
     # Handling sequential and functional models differently:
     #   - sequential models 'layers' configuration is a sorted list of the layers, so we just need
     #     to insert the new layer within that list,
@@ -73,17 +65,17 @@
                                "is not supported.")
 
         if len(outbound_names):
             # Initialize the new layer inbounds
             new_layer_inbounds = []
 
             # Replace inbounds from the layers after the target layer with the inserted layer
-            outbound_ids = [get_layer_index(layers, outbound) for outbound in outbound_names]
+            outbound_ids = [get_layer_index(layers_config, outbound) for outbound in outbound_names]
             for id in outbound_ids:
-                for inbound_node in inbound_node_generator(layers[id]):
+                for inbound_node in inbound_node_generator(layers_config[id]):
                     if isinstance(inbound_node, dict):
                         inbound_node = inbound_node.values()
                     for connection_info in inbound_node:
                         matched = replace_layer_name_for_connection_info(connection_info,
                                                                          target_layer_name,
                                                                          new_layer.name)
                         # Store the replaced inbound as it will later be used by the inserted layer
@@ -100,15 +92,38 @@
                 if out_layer[0] == target_layer_name:
                     config['output_layers'][index][0] = new_layer.name
 
             # The inserted layer takes the target layer as its inbound
             new_layer_config['inbound_nodes'] = [[[target_layer_name, 0, 0, {}]]]
 
     # The new layer configuration can now be inserted into the layers config
-    layers.insert(get_layer_index(layers, target_layer_name) + 1, new_layer_config)
+    layers_config.insert(get_layer_index(layers_config, target_layer_name) + 1, new_layer_config)
+
+
+def _insert_layer(model, target_layer_name, new_layer):
+    """ Inserts the given layer in the model after the layer with the name target_layer_name.
+
+    Args:
+        model (keras.Model): the model to update
+        target_layer_name (str): name of the layer after which to insert a layer
+        new_layer (keras.layers.Layer): layer to insert
+
+    Returns:
+        keras.Model: the new model
+    """
+    # Check that the model has a layer with then given target_layer_name
+    if not any(ly.name == target_layer_name for ly in model.layers):
+        raise ValueError(f'{target_layer_name} not found in model.')
+
+    # get_config documentation mentions that a copy should be made when planning to modify the
+    # config
+    config = deepcopy(model.get_config())
+
+    # Insert layer in config graph
+    insert_in_config(model, target_layer_name, new_layer, config)
 
     # Reconstruct model from the config
     custom_objects = {"OutputQuantizer": OutputQuantizer, "Dequantizer": Dequantizer}
     if isinstance(model, Sequential):
         new_model = Sequential.from_config(config, custom_objects)
     else:
         new_model = Model.from_config(config, custom_objects)
```

### Comparing `quantizeml-0.4.2/quantizeml/models/transforms/invert_batchnorm_pooling.py` & `quantizeml-0.5.0/quantizeml/models/transforms/invert_batchnorm_pooling.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/models/transforms/relu_maxpool.py` & `quantizeml-0.5.0/quantizeml/models/transforms/relu_maxpool.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/models/transforms/remove_zeropadding2d.py` & `quantizeml-0.5.0/quantizeml/models/transforms/remove_zeropadding2d.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/models/transforms/replace_lambda.py` & `quantizeml-0.5.0/quantizeml/models/transforms/replace_lambda.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/models/transforms/transforms_utils.py` & `quantizeml-0.5.0/quantizeml/models/transforms/transforms_utils.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/models/utils.py` & `quantizeml-0.5.0/quantizeml/models/utils.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/tensors/fixed_point.py` & `quantizeml-0.5.0/quantizeml/tensors/fixed_point.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/tensors/qfloat.py` & `quantizeml-0.5.0/quantizeml/tensors/qfloat.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/tensors/qtensor.py` & `quantizeml-0.5.0/quantizeml/tensors/qtensor.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/tensors/tf_dispatch/math.py` & `quantizeml-0.5.0/quantizeml/tensors/tf_dispatch/math.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/tensors/tf_dispatch/nn.py` & `quantizeml-0.5.0/quantizeml/tensors/tf_dispatch/nn.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml/tensors/tf_dispatch/reshaping.py` & `quantizeml-0.5.0/quantizeml/tensors/tf_dispatch/reshaping.py`

 * *Files identical despite different names*

### Comparing `quantizeml-0.4.2/quantizeml.egg-info/SOURCES.txt` & `quantizeml-0.5.0/quantizeml.egg-info/SOURCES.txt`

 * *Files 5% similar despite different names*

```diff
@@ -13,53 +13,53 @@
 quantizeml.egg-info/top_level.txt
 quantizeml/debugging/__init__.py
 quantizeml/debugging/assertions.py
 quantizeml/layers/__init__.py
 quantizeml/layers/activations.py
 quantizeml/layers/attention.py
 quantizeml/layers/batch_normalization.py
-quantizeml/layers/calibrable.py
 quantizeml/layers/convolution.py
-quantizeml/layers/decorators.py
 quantizeml/layers/dense.py
 quantizeml/layers/depthwise_convolution.py
 quantizeml/layers/dropout.py
-quantizeml/layers/layers.py
+quantizeml/layers/layers_base.py
+quantizeml/layers/multi_inbounds.py
 quantizeml/layers/normalization.py
+quantizeml/layers/output_observer.py
 quantizeml/layers/pooling.py
 quantizeml/layers/quantization_params.py
 quantizeml/layers/recorders.py
 quantizeml/layers/rescaling.py
 quantizeml/layers/separable_convolution.py
 quantizeml/layers/shiftmax.py
 quantizeml/layers/vit.py
 quantizeml/layers/quantizers/__init__.py
 quantizeml/layers/quantizers/aligned_weight_quantizer.py
 quantizeml/layers/quantizers/output_quantizer.py
 quantizeml/layers/quantizers/quantizers.py
 quantizeml/layers/quantizers/weight_quantizer.py
 quantizeml/layers/reshaping/__init__.py
 quantizeml/layers/reshaping/flatten.py
-quantizeml/layers/reshaping/patchify.py
 quantizeml/layers/reshaping/permute.py
 quantizeml/layers/reshaping/reshape.py
 quantizeml/models/__init__.py
+quantizeml/models/calibrate.py
 quantizeml/models/check_quantization.py
 quantizeml/models/quantize.py
 quantizeml/models/record.py
 quantizeml/models/utils.py
 quantizeml/models/transforms/__init__.py
-quantizeml/models/transforms/align_relu.py
 quantizeml/models/transforms/align_rescaling.py
 quantizeml/models/transforms/fold_batchnorms.py
 quantizeml/models/transforms/insert_layer.py
 quantizeml/models/transforms/invert_batchnorm_pooling.py
 quantizeml/models/transforms/relu_maxpool.py
 quantizeml/models/transforms/remove_zeropadding2d.py
 quantizeml/models/transforms/replace_lambda.py
+quantizeml/models/transforms/sanitize.py
 quantizeml/models/transforms/transforms_utils.py
 quantizeml/tensors/__init__.py
 quantizeml/tensors/fixed_point.py
 quantizeml/tensors/qfloat.py
 quantizeml/tensors/qtensor.py
 quantizeml/tensors/tf_dispatch/__init__.py
 quantizeml/tensors/tf_dispatch/math.py
```

### Comparing `quantizeml-0.4.2/setup.py` & `quantizeml-0.5.0/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -14,15 +14,15 @@
 
 # Read the contents of the README file
 directory = path.abspath(path.dirname(__file__))
 with open(path.join(directory, 'README'), encoding='utf-8') as f:
     long_description = f.read()
 
 setup(name='quantizeml',
-      version='0.4.2',
+      version='0.5.0',
       description='Base layers and quantization tools',
       long_description=long_description,
       long_description_content_type='text/markdown',
       author='David Corvoysier',
       author_email='dcorvoysier@brainchip.com',
       url='https://doc.brainchipinc.com',
       license='Apache 2.0',
```

