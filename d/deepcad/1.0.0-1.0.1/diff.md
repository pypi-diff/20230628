# Comparing `tmp/deepcad-1.0.0.tar.gz` & `tmp/deepcad-1.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/deepcad-1.0.0.tar", last modified: Sun Jun 18 09:17:41 2023, max compression
+gzip compressed data, was "dist/deepcad-1.0.1.tar", last modified: Wed Jun 28 12:09:20 2023, max compression
```

## Comparing `deepcad-1.0.0.tar` & `deepcad-1.0.1.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-18 09:17:41.000000 deepcad-1.0.0/
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-18 09:17:41.000000 deepcad-1.0.0/deepcad/
--rwxrwxrwx   0 root         (0) root         (0)    14145 2023-06-18 09:16:12.000000 deepcad-1.0.0/deepcad/buildingblocks.py
--rwxrwxrwx   0 root         (0) root         (0)    26692 2023-06-18 09:16:12.000000 deepcad-1.0.0/deepcad/data_process.py
--rwxrwxrwx   0 root         (0) root         (0)    23139 2023-06-18 09:16:12.000000 deepcad-1.0.0/deepcad/model_3DUnet.py
--rwxrwxrwx   0 root         (0) root         (0)     2078 2023-06-18 09:16:12.000000 deepcad-1.0.0/deepcad/movie_display.py
--rwxrwxrwx   0 root         (0) root         (0)      764 2023-06-18 09:16:12.000000 deepcad-1.0.0/deepcad/network.py
--rwxrwxrwx   0 root         (0) root         (0)    15458 2023-06-18 09:16:12.000000 deepcad-1.0.0/deepcad/test_collection.py
--rwxrwxrwx   0 root         (0) root         (0)    21593 2023-06-18 09:16:12.000000 deepcad-1.0.0/deepcad/train_collection.py
--rwxrwxrwx   0 root         (0) root         (0)    11185 2023-06-18 09:16:12.000000 deepcad-1.0.0/deepcad/utils.py
--rwxrwxrwx   0 root         (0) root         (0)        0 2023-06-18 09:16:12.000000 deepcad-1.0.0/deepcad/__init__.py
-drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-18 09:17:41.000000 deepcad-1.0.0/deepcad.egg-info/
--rwxrwxrwx   0 root         (0) root         (0)        1 2023-06-18 09:17:41.000000 deepcad-1.0.0/deepcad.egg-info/dependency_links.txt
--rwxrwxrwx   0 root         (0) root         (0)    10742 2023-06-18 09:17:41.000000 deepcad-1.0.0/deepcad.egg-info/PKG-INFO
--rwxrwxrwx   0 root         (0) root         (0)       75 2023-06-18 09:17:41.000000 deepcad-1.0.0/deepcad.egg-info/requires.txt
--rwxrwxrwx   0 root         (0) root         (0)      382 2023-06-18 09:17:41.000000 deepcad-1.0.0/deepcad.egg-info/SOURCES.txt
--rwxrwxrwx   0 root         (0) root         (0)        8 2023-06-18 09:17:41.000000 deepcad-1.0.0/deepcad.egg-info/top_level.txt
--rwxrwxrwx   0 root         (0) root         (0)    10742 2023-06-18 09:17:41.000000 deepcad-1.0.0/PKG-INFO
--rwxrwxrwx   0 root         (0) root         (0)     9288 2023-06-18 09:16:12.000000 deepcad-1.0.0/README.md
--rwxrwxrwx   0 root         (0) root         (0)       38 2023-06-18 09:17:41.000000 deepcad-1.0.0/setup.cfg
--rwxrwxrwx   0 root         (0) root         (0)      895 2023-06-18 09:16:12.000000 deepcad-1.0.0/setup.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 12:09:20.000000 deepcad-1.0.1/
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 12:09:20.000000 deepcad-1.0.1/deepcad/
+-rwxrwxrwx   0 root         (0) root         (0)    14145 2023-06-28 12:02:58.000000 deepcad-1.0.1/deepcad/buildingblocks.py
+-rwxrwxrwx   0 root         (0) root         (0)    26692 2023-06-28 12:02:58.000000 deepcad-1.0.1/deepcad/data_process.py
+-rwxrwxrwx   0 root         (0) root         (0)    23139 2023-06-28 12:02:58.000000 deepcad-1.0.1/deepcad/model_3DUnet.py
+-rwxrwxrwx   0 root         (0) root         (0)     2078 2023-06-28 12:02:58.000000 deepcad-1.0.1/deepcad/movie_display.py
+-rwxrwxrwx   0 root         (0) root         (0)      764 2023-06-28 12:02:58.000000 deepcad-1.0.1/deepcad/network.py
+-rwxrwxrwx   0 root         (0) root         (0)    15462 2023-06-28 12:06:41.000000 deepcad-1.0.1/deepcad/test_collection.py
+-rwxrwxrwx   0 root         (0) root         (0)    21597 2023-06-28 12:04:41.000000 deepcad-1.0.1/deepcad/train_collection.py
+-rwxrwxrwx   0 root         (0) root         (0)    11185 2023-06-28 12:02:58.000000 deepcad-1.0.1/deepcad/utils.py
+-rwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 12:02:58.000000 deepcad-1.0.1/deepcad/__init__.py
+drwxrwxrwx   0 root         (0) root         (0)        0 2023-06-28 12:09:20.000000 deepcad-1.0.1/deepcad.egg-info/
+-rwxrwxrwx   0 root         (0) root         (0)        1 2023-06-28 12:09:20.000000 deepcad-1.0.1/deepcad.egg-info/dependency_links.txt
+-rwxrwxrwx   0 root         (0) root         (0)     9475 2023-06-28 12:09:20.000000 deepcad-1.0.1/deepcad.egg-info/PKG-INFO
+-rwxrwxrwx   0 root         (0) root         (0)       75 2023-06-28 12:09:20.000000 deepcad-1.0.1/deepcad.egg-info/requires.txt
+-rwxrwxrwx   0 root         (0) root         (0)      382 2023-06-28 12:09:20.000000 deepcad-1.0.1/deepcad.egg-info/SOURCES.txt
+-rwxrwxrwx   0 root         (0) root         (0)        8 2023-06-28 12:09:20.000000 deepcad-1.0.1/deepcad.egg-info/top_level.txt
+-rwxrwxrwx   0 root         (0) root         (0)     9475 2023-06-28 12:09:20.000000 deepcad-1.0.1/PKG-INFO
+-rwxrwxrwx   0 root         (0) root         (0)     9288 2023-06-28 12:02:58.000000 deepcad-1.0.1/README.md
+-rwxrwxrwx   0 root         (0) root         (0)       38 2023-06-28 12:09:20.000000 deepcad-1.0.1/setup.cfg
+-rwxrwxrwx   0 root         (0) root         (0)      895 2023-06-28 12:03:42.000000 deepcad-1.0.1/setup.py
```

### Comparing `deepcad-1.0.0/deepcad/buildingblocks.py` & `deepcad-1.0.1/deepcad/buildingblocks.py`

 * *Files identical despite different names*

### Comparing `deepcad-1.0.0/deepcad/data_process.py` & `deepcad-1.0.1/deepcad/data_process.py`

 * *Files identical despite different names*

### Comparing `deepcad-1.0.0/deepcad/model_3DUnet.py` & `deepcad-1.0.1/deepcad/model_3DUnet.py`

 * *Files identical despite different names*

### Comparing `deepcad-1.0.0/deepcad/movie_display.py` & `deepcad-1.0.1/deepcad/movie_display.py`

 * *Files identical despite different names*

### Comparing `deepcad-1.0.0/deepcad/network.py` & `deepcad-1.0.1/deepcad/network.py`

 * *Files identical despite different names*

### Comparing `deepcad-1.0.0/deepcad/test_collection.py` & `deepcad-1.0.1/deepcad/test_collection.py`

 * *Files 0% similar despite different names*

```diff
@@ -333,8 +333,8 @@
 
                     if pth_count == self.model_list_length:
                         if self.colab_display:
                             self.result_display = output_path_name + '//' + self.img_list[N].replace('.tif','') + '_' + pth_name.replace(
                             '.pth', '') + '_output.tif'
 
 
-        print('Test finished. Save all results to disk.')
+        print('Testing finished. All results saved to disk.')
```

### Comparing `deepcad-1.0.0/deepcad/train_collection.py` & `deepcad-1.0.1/deepcad/train_collection.py`

 * *Files 1% similar despite different names*

```diff
@@ -327,15 +327,15 @@
                     # Save model at the end of every epoch
                     self.save_model(epoch, iteration)
                     # Start inference using the denoise model at the end of every epoch (optional)
                     if (self.visualize_images_per_epoch | self.save_test_images_per_epoch):
                         print('Testing model of epoch {} on the first noisy file ----->'.format(epoch + 1))
                         self.test(epoch, iteration)
                         print('\n', end=' ')
-        print('Train finished. Save all models to disk.')
+        print('Training finished. All models saved to disk.')
         if self.colab_display:
             result_img_list = []
             results_path = self.pth_path
             results_list = list(os.walk(results_path, topdown=False))[-1][-1]
             for i in range(len(results_list)):
               aaa = results_list[i]
               if '.tif' in aaa:
```

### Comparing `deepcad-1.0.0/deepcad/utils.py` & `deepcad-1.0.1/deepcad/utils.py`

 * *Files identical despite different names*

### Comparing `deepcad-1.0.0/deepcad.egg-info/PKG-INFO` & `deepcad-1.0.1/README.md`

 * *Files 20% similar despite different names*

```diff
@@ -1,168 +1,157 @@
-Metadata-Version: 2.1
-Name: deepcad
-Version: 1.0.0
-Summary: Implement DeepCAD-RT to denoise data by removing independent noise
-Home-page: https://github.com/cabooster/DeepCAD-RT
-Author: Xinyang Li, Yixin Li
-Author-email: liyixin318@gmail.com
-License: GNU General Public License v2.0
-Description: # DeepCAD-RT: Real-time denoising of fluorescence time-lapse imaging using deep self-supervised learning
-        
-        <img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/logo.PNG?raw=true" width="700" align="middle" />
-        
-        ### [Project page](https://cabooster.github.io/DeepCAD-RT/) | [Paper](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1)
-        
-        
-        
-        ## Overview
-        
-        **Among the challenges of fluorescence microscopy, poor imaging signal-to-noise ratio (SNR) caused by limited photon budget lingeringly stands in the central position.** Fluorescence microscopy is inherently sensitive to detection noise because the photon flux in fluorescence imaging is far lower than that in photography. For almost all fluorescence imaging technologies, the inherent [**shot-noise limit**](https://cabooster.github.io/DeepCAD-RT/About/) determines the upper bound of imaging SNR and restricts the imaging resolution, speed, and sensitivity. To capture enough fluorescence photons for satisfactory SNR, researchers have to sacrifice imaging resolution, speed, and even sample health.  
-        
-        We present a versatile method **DeepCAD-RT** to denoise fluorescence time-lapse images with rapid processing speed that can be incorporated with the microscope acquisition system to achieve real-time denoising. Our method is based on deep self-supervised learning and the original low-SNR data can be directly used for training convolutional networks, making it particularly advantageous in functional imaging where the sample is undergoing fast dynamics and capturing ground-truth data is hard or impossible. We have demonstrated extensive experiments including calcium imaging in mice, zebrafish, and flies, cell migration observations, and the imaging of a new genetically encoded ATP sensor, covering both 2D single-plane imaging and 3D volumetric imaging. **Qualitative and quantitative evaluations show that our method can substantially enhance fluorescence time-lapse imaging data and permit high-sensitivity imaging of biological dynamics beyond the shot-noise limit.**
-        
-        For more details, please see the companion paper where the method first appeared: 
-        ["*Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit, bioRxiv (2022)*"](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1).
-        
-        
-        
-        <img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/schematic.png?raw=true" width="800" align="middle">
-        
-        
-        
-        ## Pytorch code
-        
-        ### Our environment 
-        
-        * Ubuntu 16.04 
-        * Python 3.6
-        * Pytorch 1.8.0
-        * NVIDIA GPU (GeForce RTX 3090) + CUDA (11.1)
-        
-        ### Environment configuration
-        
-        1. Create a virtual environment and install PyTorch. In the 3rd step, please select the correct Pytorch version that matches your CUDA version from [https://pytorch.org/get-started/previous-versions/](https://pytorch.org/get-started/previous-versions/). 
-        
-           ```
-           $ conda create -n deepcadrt python=3.6
-           $ conda activate deepcadrt
-           $ pip install torch==1.8.0+cu111 torchvision==0.9.0+cu111 torchaudio==0.8.0 -f https://download.pytorch.org/whl/torch_stable.html
-           ```
-           
-              *Note:  `pip install` command is required for Pytorch installation.*
-          
-        2. We made a installable pip realease of DeepCAD-RT [[pypi](https://pypi.org/project/deepcad/)]. You can install it by entering the following command:
-        
-           ```
-           $ pip install deepcad
-           ```
-        
-        ### Download the source code
-        
-        ```
-        $ git clone https://github.com/cabooster/DeepCAD-RT
-        $ cd DeepCAD-RT/DeepCAD_RT_pytorch/
-        ```
-        
-        ### Demos
-        
-        To try out the Python code, please activate the `deepcadrt` environment first:
-        
-        ```
-        $ conda activate deepcadrt
-        $ cd DeepCAD-RT/DeepCAD_RT_pytorch/
-        ```
-        
-        **Example training**
-        
-        To train a DeepCAD-RT model, we recommend starting with the demo script `demo_train_pipeline.py`. One demo dataset will be downloaded to the `DeepCAD_RT_pytorch/datasets` folder automatically. You can also download other data from [the companion webpage](https://cabooster.github.io/DeepCAD-RT/Datasets/) or use your own data by changing the training parameter `datasets_path`. 
-        
-        ```
-        python demo_train_pipeline.py
-        ```
-        
-        **Example testing**
-        
-        To test the denoising performance with pre-trained models, you can run the demo script `demo_test_pipeline.py` . A demo dataset and its denoising model will be automatically downloaded to `DeepCAD_RT_pytorch/datasets` and `DeepCAD_RT_pytorch/pth`, respectively. You can change the dataset and the model by changing the parameters `datasets_path` and `denoise_model`.
-        
-        ```
-        python demo_test_pipeline.py
-        ```
-        
-        ### Jupyter notebook
-        
-        We provide simple and user-friendly Jupyter notebooks to implement DeepCAD-RT. They are in the `DeepCAD_RT_pytorch/notebooks` folder. Before you launch the notebooks, please configure an environment following the instruction in [Environment configuration](#environment-configuration) . And then, you can launch the notebooks through the following commands:
-        
-        ```
-        $ conda activate deepcadrt
-        $ cd DeepCAD-RT/DeepCAD_RT_pytorch/notebooks
-        $ jupyter notebook
-        ```
-        
-        ### Colab notebook
-        
-        We also provide a cloud-based notebook implemented with Google Colab. You can run DeepCAD-RT directly in your browser using a cloud GPU without configuring the environment. 
-        
-        [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cabooster/DeepCAD-RT/blob/main/DeepCAD_RT_pytorch/notebooks/DeepCAD_RT_demo_colab.ipynb)
-        
-        *Note: The Colab notebook needs much longer time to train and test because of the limited GPU performance offered by Colab.*
-        
-        
-        
-        ## Matlab GUI
-        
-        To achieve real-time denoising, DeepCAD-RT was optimally deployed on GPU using TensorRT (Nvidia) for further acceleration and memory reduction. We also designed a sophisticated time schedule for multi-thread processing. Based on a two-photon microscope, real-time denoising has been achieved with our Matlab GUI of DeepCAD-RT (tested on a Windows desktop with Intel i9 CPU and 128 GB RAM).  **Tutorials** on installing and using the GUI has been moved to [**this page**](https://github.com/cabooster/DeepCAD-RT/tree/main/DeepCAD_RT_GUI).  
-        
-        <center><img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/GUI2.png?raw=true" width="950" align="middle"></center> 
-        
-        ## Results
-        
-        **1. Universal denoising for calcium imaging in zebrafish.**
-        
-        [![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv3_video.png?raw=true.png)]( https://www.youtube.com/embed/GN0IO7bGoGg "Video Title")
-        
-        **2. Denoising performance of DeepCAD-RT of neutrophils in the mouse brain in vivo.** 
-        
-        [![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv8_video.png?raw=true.png)]( https://www.youtube.com/embed/eyLPVRcEGHs "Video Title")
-        
-        **3. Denoising performance of DeepCAD-RT on a recently developed genetically encoded ATP sensor.**
-        
-        [![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv10_video.png?raw=true.png)](https://www.youtube.com/embed/u1ejSaVvWiY "Video Title")
-        
-        More demo videos are demonstrated on [our website](https://cabooster.github.io/DeepCAD-RT/Gallery/).
-        
-        ## Citation
-        
-        If you use this code please cite the companion paper where the original method appeared: 
-        
-        - Xinyang Li, Yixin Li, Yiliang Zhou, et al. Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit. bioRxiv (2022). [https://doi.org/10.1101/2022.03.14.484230](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1)
-        
-        - Xinyang Li, Guoxun Zhang, Jiamin Wu, et al. Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising. Nat Methods 18, 1395–1400 (2021). [https://doi.org/10.1038/s41592-021-01225-0](https://www.nature.com/articles/s41592-021-01225-0) 
-        
-        
-        ```
-        @article {Li2022.03.14.484230,
-          author = {Li, Xinyang and Li, Yixin and Zhou, Yiliang and Wu, Jiamin and Zhao, Zhifeng and Fan, Jiaqi and Deng, Fei and Wu, Zhaofa and Xiao, Guihua and He, Jing and Zhang, Yuanlong and Zhang, Guoxun and Hu, Xiaowan and Zhang, Yi and Qiao, Hui and Xie, Hao and Li, Yulong and Wang, Haoqian and Fang, Lu and Dai, Qionghai},
-          title = {Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit},
-          elocation-id = {2022.03.14.484230},
-          year = {2022},
-          doi = {10.1101/2022.03.14.484230},
-          publisher = {Cold Spring Harbor Laboratory},
-          URL = {https://www.biorxiv.org/content/early/2022/03/14/2022.03.14.484230},
-          eprint = {https://www.biorxiv.org/content/early/2022/03/14/2022.03.14.484230.full.pdf},
-          journal = {bioRxiv}
-        }
-        @article{li2021reinforcing,
-          title={Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising},
-          author={Li, Xinyang and Zhang, Guoxun and Wu, Jiamin and Zhang, Yuanlong and Zhao, Zhifeng and Lin, Xing and Qiao, Hui and Xie, Hao and Wang, Haoqian and Fang, Lu and others},
-          journal={Nature Methods},
-          volume={18},
-          number={11},
-          pages={1395--1400},
-          year={2021},
-          publisher={Nature Publishing Group}
-        }
-        ```
-        
-        
-Platform: UNKNOWN
-Description-Content-Type: text/markdown
+# DeepCAD-RT: Real-time denoising of fluorescence time-lapse imaging using deep self-supervised learning
+
+<img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/logo.PNG?raw=true" width="700" align="middle" />
+
+### [Project page](https://cabooster.github.io/DeepCAD-RT/) | [Paper](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1)
+
+
+
+## Overview
+
+**Among the challenges of fluorescence microscopy, poor imaging signal-to-noise ratio (SNR) caused by limited photon budget lingeringly stands in the central position.** Fluorescence microscopy is inherently sensitive to detection noise because the photon flux in fluorescence imaging is far lower than that in photography. For almost all fluorescence imaging technologies, the inherent [**shot-noise limit**](https://cabooster.github.io/DeepCAD-RT/About/) determines the upper bound of imaging SNR and restricts the imaging resolution, speed, and sensitivity. To capture enough fluorescence photons for satisfactory SNR, researchers have to sacrifice imaging resolution, speed, and even sample health.  
+
+We present a versatile method **DeepCAD-RT** to denoise fluorescence time-lapse images with rapid processing speed that can be incorporated with the microscope acquisition system to achieve real-time denoising. Our method is based on deep self-supervised learning and the original low-SNR data can be directly used for training convolutional networks, making it particularly advantageous in functional imaging where the sample is undergoing fast dynamics and capturing ground-truth data is hard or impossible. We have demonstrated extensive experiments including calcium imaging in mice, zebrafish, and flies, cell migration observations, and the imaging of a new genetically encoded ATP sensor, covering both 2D single-plane imaging and 3D volumetric imaging. **Qualitative and quantitative evaluations show that our method can substantially enhance fluorescence time-lapse imaging data and permit high-sensitivity imaging of biological dynamics beyond the shot-noise limit.**
+
+For more details, please see the companion paper where the method first appeared: 
+["*Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit, bioRxiv (2022)*"](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1).
+
+
+
+<img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/schematic.png?raw=true" width="800" align="middle">
+
+
+
+## Pytorch code
+
+### Our environment 
+
+* Ubuntu 16.04 
+* Python 3.6
+* Pytorch 1.8.0
+* NVIDIA GPU (GeForce RTX 3090) + CUDA (11.1)
+
+### Environment configuration
+
+1. Create a virtual environment and install PyTorch. In the 3rd step, please select the correct Pytorch version that matches your CUDA version from [https://pytorch.org/get-started/previous-versions/](https://pytorch.org/get-started/previous-versions/). 
+
+   ```
+   $ conda create -n deepcadrt python=3.6
+   $ conda activate deepcadrt
+   $ pip install torch==1.8.0+cu111 torchvision==0.9.0+cu111 torchaudio==0.8.0 -f https://download.pytorch.org/whl/torch_stable.html
+   ```
+   
+      *Note:  `pip install` command is required for Pytorch installation.*
+  
+2. We made a installable pip realease of DeepCAD-RT [[pypi](https://pypi.org/project/deepcad/)]. You can install it by entering the following command:
+
+   ```
+   $ pip install deepcad
+   ```
+
+### Download the source code
+
+```
+$ git clone https://github.com/cabooster/DeepCAD-RT
+$ cd DeepCAD-RT/DeepCAD_RT_pytorch/
+```
+
+### Demos
+
+To try out the Python code, please activate the `deepcadrt` environment first:
+
+```
+$ conda activate deepcadrt
+$ cd DeepCAD-RT/DeepCAD_RT_pytorch/
+```
+
+**Example training**
+
+To train a DeepCAD-RT model, we recommend starting with the demo script `demo_train_pipeline.py`. One demo dataset will be downloaded to the `DeepCAD_RT_pytorch/datasets` folder automatically. You can also download other data from [the companion webpage](https://cabooster.github.io/DeepCAD-RT/Datasets/) or use your own data by changing the training parameter `datasets_path`. 
+
+```
+python demo_train_pipeline.py
+```
+
+**Example testing**
+
+To test the denoising performance with pre-trained models, you can run the demo script `demo_test_pipeline.py` . A demo dataset and its denoising model will be automatically downloaded to `DeepCAD_RT_pytorch/datasets` and `DeepCAD_RT_pytorch/pth`, respectively. You can change the dataset and the model by changing the parameters `datasets_path` and `denoise_model`.
+
+```
+python demo_test_pipeline.py
+```
+
+### Jupyter notebook
+
+We provide simple and user-friendly Jupyter notebooks to implement DeepCAD-RT. They are in the `DeepCAD_RT_pytorch/notebooks` folder. Before you launch the notebooks, please configure an environment following the instruction in [Environment configuration](#environment-configuration) . And then, you can launch the notebooks through the following commands:
+
+```
+$ conda activate deepcadrt
+$ cd DeepCAD-RT/DeepCAD_RT_pytorch/notebooks
+$ jupyter notebook
+```
+
+### Colab notebook
+
+We also provide a cloud-based notebook implemented with Google Colab. You can run DeepCAD-RT directly in your browser using a cloud GPU without configuring the environment. 
+
+[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cabooster/DeepCAD-RT/blob/main/DeepCAD_RT_pytorch/notebooks/DeepCAD_RT_demo_colab.ipynb)
+
+*Note: The Colab notebook needs much longer time to train and test because of the limited GPU performance offered by Colab.*
+
+
+
+## Matlab GUI
+
+To achieve real-time denoising, DeepCAD-RT was optimally deployed on GPU using TensorRT (Nvidia) for further acceleration and memory reduction. We also designed a sophisticated time schedule for multi-thread processing. Based on a two-photon microscope, real-time denoising has been achieved with our Matlab GUI of DeepCAD-RT (tested on a Windows desktop with Intel i9 CPU and 128 GB RAM).  **Tutorials** on installing and using the GUI has been moved to [**this page**](https://github.com/cabooster/DeepCAD-RT/tree/main/DeepCAD_RT_GUI).  
+
+<center><img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/GUI2.png?raw=true" width="950" align="middle"></center> 
+
+## Results
+
+**1. Universal denoising for calcium imaging in zebrafish.**
+
+[![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv3_video.png?raw=true.png)]( https://www.youtube.com/embed/GN0IO7bGoGg "Video Title")
+
+**2. Denoising performance of DeepCAD-RT of neutrophils in the mouse brain in vivo.** 
+
+[![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv8_video.png?raw=true.png)]( https://www.youtube.com/embed/eyLPVRcEGHs "Video Title")
+
+**3. Denoising performance of DeepCAD-RT on a recently developed genetically encoded ATP sensor.**
+
+[![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv10_video.png?raw=true.png)](https://www.youtube.com/embed/u1ejSaVvWiY "Video Title")
+
+More demo videos are demonstrated on [our website](https://cabooster.github.io/DeepCAD-RT/Gallery/).
+
+## Citation
+
+If you use this code please cite the companion paper where the original method appeared: 
+
+- Xinyang Li, Yixin Li, Yiliang Zhou, et al. Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit. bioRxiv (2022). [https://doi.org/10.1101/2022.03.14.484230](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1)
+
+- Xinyang Li, Guoxun Zhang, Jiamin Wu, et al. Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising. Nat Methods 18, 1395–1400 (2021). [https://doi.org/10.1038/s41592-021-01225-0](https://www.nature.com/articles/s41592-021-01225-0) 
+
+
+```
+@article {Li2022.03.14.484230,
+  author = {Li, Xinyang and Li, Yixin and Zhou, Yiliang and Wu, Jiamin and Zhao, Zhifeng and Fan, Jiaqi and Deng, Fei and Wu, Zhaofa and Xiao, Guihua and He, Jing and Zhang, Yuanlong and Zhang, Guoxun and Hu, Xiaowan and Zhang, Yi and Qiao, Hui and Xie, Hao and Li, Yulong and Wang, Haoqian and Fang, Lu and Dai, Qionghai},
+  title = {Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit},
+  elocation-id = {2022.03.14.484230},
+  year = {2022},
+  doi = {10.1101/2022.03.14.484230},
+  publisher = {Cold Spring Harbor Laboratory},
+  URL = {https://www.biorxiv.org/content/early/2022/03/14/2022.03.14.484230},
+  eprint = {https://www.biorxiv.org/content/early/2022/03/14/2022.03.14.484230.full.pdf},
+  journal = {bioRxiv}
+}
+@article{li2021reinforcing,
+  title={Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising},
+  author={Li, Xinyang and Zhang, Guoxun and Wu, Jiamin and Zhang, Yuanlong and Zhao, Zhifeng and Lin, Xing and Qiao, Hui and Xie, Hao and Wang, Haoqian and Fang, Lu and others},
+  journal={Nature Methods},
+  volume={18},
+  number={11},
+  pages={1395--1400},
+  year={2021},
+  publisher={Nature Publishing Group}
+}
+```
+
```

### Comparing `deepcad-1.0.0/PKG-INFO` & `deepcad-1.0.1/deepcad.egg-info/PKG-INFO`

 * *Files 20% similar despite different names*

```diff
@@ -1,168 +1,170 @@
 Metadata-Version: 2.1
 Name: deepcad
-Version: 1.0.0
+Version: 1.0.1
 Summary: Implement DeepCAD-RT to denoise data by removing independent noise
 Home-page: https://github.com/cabooster/DeepCAD-RT
 Author: Xinyang Li, Yixin Li
 Author-email: liyixin318@gmail.com
 License: GNU General Public License v2.0
-Description: # DeepCAD-RT: Real-time denoising of fluorescence time-lapse imaging using deep self-supervised learning
-        
-        <img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/logo.PNG?raw=true" width="700" align="middle" />
-        
-        ### [Project page](https://cabooster.github.io/DeepCAD-RT/) | [Paper](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1)
-        
-        
-        
-        ## Overview
-        
-        **Among the challenges of fluorescence microscopy, poor imaging signal-to-noise ratio (SNR) caused by limited photon budget lingeringly stands in the central position.** Fluorescence microscopy is inherently sensitive to detection noise because the photon flux in fluorescence imaging is far lower than that in photography. For almost all fluorescence imaging technologies, the inherent [**shot-noise limit**](https://cabooster.github.io/DeepCAD-RT/About/) determines the upper bound of imaging SNR and restricts the imaging resolution, speed, and sensitivity. To capture enough fluorescence photons for satisfactory SNR, researchers have to sacrifice imaging resolution, speed, and even sample health.  
-        
-        We present a versatile method **DeepCAD-RT** to denoise fluorescence time-lapse images with rapid processing speed that can be incorporated with the microscope acquisition system to achieve real-time denoising. Our method is based on deep self-supervised learning and the original low-SNR data can be directly used for training convolutional networks, making it particularly advantageous in functional imaging where the sample is undergoing fast dynamics and capturing ground-truth data is hard or impossible. We have demonstrated extensive experiments including calcium imaging in mice, zebrafish, and flies, cell migration observations, and the imaging of a new genetically encoded ATP sensor, covering both 2D single-plane imaging and 3D volumetric imaging. **Qualitative and quantitative evaluations show that our method can substantially enhance fluorescence time-lapse imaging data and permit high-sensitivity imaging of biological dynamics beyond the shot-noise limit.**
-        
-        For more details, please see the companion paper where the method first appeared: 
-        ["*Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit, bioRxiv (2022)*"](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1).
-        
-        
-        
-        <img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/schematic.png?raw=true" width="800" align="middle">
-        
-        
-        
-        ## Pytorch code
-        
-        ### Our environment 
-        
-        * Ubuntu 16.04 
-        * Python 3.6
-        * Pytorch 1.8.0
-        * NVIDIA GPU (GeForce RTX 3090) + CUDA (11.1)
-        
-        ### Environment configuration
-        
-        1. Create a virtual environment and install PyTorch. In the 3rd step, please select the correct Pytorch version that matches your CUDA version from [https://pytorch.org/get-started/previous-versions/](https://pytorch.org/get-started/previous-versions/). 
-        
-           ```
-           $ conda create -n deepcadrt python=3.6
-           $ conda activate deepcadrt
-           $ pip install torch==1.8.0+cu111 torchvision==0.9.0+cu111 torchaudio==0.8.0 -f https://download.pytorch.org/whl/torch_stable.html
-           ```
-           
-              *Note:  `pip install` command is required for Pytorch installation.*
-          
-        2. We made a installable pip realease of DeepCAD-RT [[pypi](https://pypi.org/project/deepcad/)]. You can install it by entering the following command:
-        
-           ```
-           $ pip install deepcad
-           ```
-        
-        ### Download the source code
-        
-        ```
-        $ git clone https://github.com/cabooster/DeepCAD-RT
-        $ cd DeepCAD-RT/DeepCAD_RT_pytorch/
-        ```
-        
-        ### Demos
-        
-        To try out the Python code, please activate the `deepcadrt` environment first:
-        
-        ```
-        $ conda activate deepcadrt
-        $ cd DeepCAD-RT/DeepCAD_RT_pytorch/
-        ```
-        
-        **Example training**
-        
-        To train a DeepCAD-RT model, we recommend starting with the demo script `demo_train_pipeline.py`. One demo dataset will be downloaded to the `DeepCAD_RT_pytorch/datasets` folder automatically. You can also download other data from [the companion webpage](https://cabooster.github.io/DeepCAD-RT/Datasets/) or use your own data by changing the training parameter `datasets_path`. 
-        
-        ```
-        python demo_train_pipeline.py
-        ```
-        
-        **Example testing**
-        
-        To test the denoising performance with pre-trained models, you can run the demo script `demo_test_pipeline.py` . A demo dataset and its denoising model will be automatically downloaded to `DeepCAD_RT_pytorch/datasets` and `DeepCAD_RT_pytorch/pth`, respectively. You can change the dataset and the model by changing the parameters `datasets_path` and `denoise_model`.
-        
-        ```
-        python demo_test_pipeline.py
-        ```
-        
-        ### Jupyter notebook
-        
-        We provide simple and user-friendly Jupyter notebooks to implement DeepCAD-RT. They are in the `DeepCAD_RT_pytorch/notebooks` folder. Before you launch the notebooks, please configure an environment following the instruction in [Environment configuration](#environment-configuration) . And then, you can launch the notebooks through the following commands:
-        
-        ```
-        $ conda activate deepcadrt
-        $ cd DeepCAD-RT/DeepCAD_RT_pytorch/notebooks
-        $ jupyter notebook
-        ```
-        
-        ### Colab notebook
-        
-        We also provide a cloud-based notebook implemented with Google Colab. You can run DeepCAD-RT directly in your browser using a cloud GPU without configuring the environment. 
-        
-        [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cabooster/DeepCAD-RT/blob/main/DeepCAD_RT_pytorch/notebooks/DeepCAD_RT_demo_colab.ipynb)
-        
-        *Note: The Colab notebook needs much longer time to train and test because of the limited GPU performance offered by Colab.*
-        
-        
-        
-        ## Matlab GUI
-        
-        To achieve real-time denoising, DeepCAD-RT was optimally deployed on GPU using TensorRT (Nvidia) for further acceleration and memory reduction. We also designed a sophisticated time schedule for multi-thread processing. Based on a two-photon microscope, real-time denoising has been achieved with our Matlab GUI of DeepCAD-RT (tested on a Windows desktop with Intel i9 CPU and 128 GB RAM).  **Tutorials** on installing and using the GUI has been moved to [**this page**](https://github.com/cabooster/DeepCAD-RT/tree/main/DeepCAD_RT_GUI).  
-        
-        <center><img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/GUI2.png?raw=true" width="950" align="middle"></center> 
-        
-        ## Results
-        
-        **1. Universal denoising for calcium imaging in zebrafish.**
-        
-        [![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv3_video.png?raw=true.png)]( https://www.youtube.com/embed/GN0IO7bGoGg "Video Title")
-        
-        **2. Denoising performance of DeepCAD-RT of neutrophils in the mouse brain in vivo.** 
-        
-        [![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv8_video.png?raw=true.png)]( https://www.youtube.com/embed/eyLPVRcEGHs "Video Title")
-        
-        **3. Denoising performance of DeepCAD-RT on a recently developed genetically encoded ATP sensor.**
-        
-        [![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv10_video.png?raw=true.png)](https://www.youtube.com/embed/u1ejSaVvWiY "Video Title")
-        
-        More demo videos are demonstrated on [our website](https://cabooster.github.io/DeepCAD-RT/Gallery/).
-        
-        ## Citation
-        
-        If you use this code please cite the companion paper where the original method appeared: 
-        
-        - Xinyang Li, Yixin Li, Yiliang Zhou, et al. Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit. bioRxiv (2022). [https://doi.org/10.1101/2022.03.14.484230](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1)
-        
-        - Xinyang Li, Guoxun Zhang, Jiamin Wu, et al. Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising. Nat Methods 18, 1395–1400 (2021). [https://doi.org/10.1038/s41592-021-01225-0](https://www.nature.com/articles/s41592-021-01225-0) 
-        
-        
-        ```
-        @article {Li2022.03.14.484230,
-          author = {Li, Xinyang and Li, Yixin and Zhou, Yiliang and Wu, Jiamin and Zhao, Zhifeng and Fan, Jiaqi and Deng, Fei and Wu, Zhaofa and Xiao, Guihua and He, Jing and Zhang, Yuanlong and Zhang, Guoxun and Hu, Xiaowan and Zhang, Yi and Qiao, Hui and Xie, Hao and Li, Yulong and Wang, Haoqian and Fang, Lu and Dai, Qionghai},
-          title = {Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit},
-          elocation-id = {2022.03.14.484230},
-          year = {2022},
-          doi = {10.1101/2022.03.14.484230},
-          publisher = {Cold Spring Harbor Laboratory},
-          URL = {https://www.biorxiv.org/content/early/2022/03/14/2022.03.14.484230},
-          eprint = {https://www.biorxiv.org/content/early/2022/03/14/2022.03.14.484230.full.pdf},
-          journal = {bioRxiv}
-        }
-        @article{li2021reinforcing,
-          title={Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising},
-          author={Li, Xinyang and Zhang, Guoxun and Wu, Jiamin and Zhang, Yuanlong and Zhao, Zhifeng and Lin, Xing and Qiao, Hui and Xie, Hao and Wang, Haoqian and Fang, Lu and others},
-          journal={Nature Methods},
-          volume={18},
-          number={11},
-          pages={1395--1400},
-          year={2021},
-          publisher={Nature Publishing Group}
-        }
-        ```
-        
-        
 Platform: UNKNOWN
 Description-Content-Type: text/markdown
+
+# DeepCAD-RT: Real-time denoising of fluorescence time-lapse imaging using deep self-supervised learning
+
+<img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/logo.PNG?raw=true" width="700" align="middle" />
+
+### [Project page](https://cabooster.github.io/DeepCAD-RT/) | [Paper](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1)
+
+
+
+## Overview
+
+**Among the challenges of fluorescence microscopy, poor imaging signal-to-noise ratio (SNR) caused by limited photon budget lingeringly stands in the central position.** Fluorescence microscopy is inherently sensitive to detection noise because the photon flux in fluorescence imaging is far lower than that in photography. For almost all fluorescence imaging technologies, the inherent [**shot-noise limit**](https://cabooster.github.io/DeepCAD-RT/About/) determines the upper bound of imaging SNR and restricts the imaging resolution, speed, and sensitivity. To capture enough fluorescence photons for satisfactory SNR, researchers have to sacrifice imaging resolution, speed, and even sample health.  
+
+We present a versatile method **DeepCAD-RT** to denoise fluorescence time-lapse images with rapid processing speed that can be incorporated with the microscope acquisition system to achieve real-time denoising. Our method is based on deep self-supervised learning and the original low-SNR data can be directly used for training convolutional networks, making it particularly advantageous in functional imaging where the sample is undergoing fast dynamics and capturing ground-truth data is hard or impossible. We have demonstrated extensive experiments including calcium imaging in mice, zebrafish, and flies, cell migration observations, and the imaging of a new genetically encoded ATP sensor, covering both 2D single-plane imaging and 3D volumetric imaging. **Qualitative and quantitative evaluations show that our method can substantially enhance fluorescence time-lapse imaging data and permit high-sensitivity imaging of biological dynamics beyond the shot-noise limit.**
+
+For more details, please see the companion paper where the method first appeared: 
+["*Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit, bioRxiv (2022)*"](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1).
+
+
+
+<img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/schematic.png?raw=true" width="800" align="middle">
+
+
+
+## Pytorch code
+
+### Our environment 
+
+* Ubuntu 16.04 
+* Python 3.6
+* Pytorch 1.8.0
+* NVIDIA GPU (GeForce RTX 3090) + CUDA (11.1)
+
+### Environment configuration
+
+1. Create a virtual environment and install PyTorch. In the 3rd step, please select the correct Pytorch version that matches your CUDA version from [https://pytorch.org/get-started/previous-versions/](https://pytorch.org/get-started/previous-versions/). 
+
+   ```
+   $ conda create -n deepcadrt python=3.6
+   $ conda activate deepcadrt
+   $ pip install torch==1.8.0+cu111 torchvision==0.9.0+cu111 torchaudio==0.8.0 -f https://download.pytorch.org/whl/torch_stable.html
+   ```
+   
+      *Note:  `pip install` command is required for Pytorch installation.*
+  
+2. We made a installable pip realease of DeepCAD-RT [[pypi](https://pypi.org/project/deepcad/)]. You can install it by entering the following command:
+
+   ```
+   $ pip install deepcad
+   ```
+
+### Download the source code
+
+```
+$ git clone https://github.com/cabooster/DeepCAD-RT
+$ cd DeepCAD-RT/DeepCAD_RT_pytorch/
+```
+
+### Demos
+
+To try out the Python code, please activate the `deepcadrt` environment first:
+
+```
+$ conda activate deepcadrt
+$ cd DeepCAD-RT/DeepCAD_RT_pytorch/
+```
+
+**Example training**
+
+To train a DeepCAD-RT model, we recommend starting with the demo script `demo_train_pipeline.py`. One demo dataset will be downloaded to the `DeepCAD_RT_pytorch/datasets` folder automatically. You can also download other data from [the companion webpage](https://cabooster.github.io/DeepCAD-RT/Datasets/) or use your own data by changing the training parameter `datasets_path`. 
+
+```
+python demo_train_pipeline.py
+```
+
+**Example testing**
+
+To test the denoising performance with pre-trained models, you can run the demo script `demo_test_pipeline.py` . A demo dataset and its denoising model will be automatically downloaded to `DeepCAD_RT_pytorch/datasets` and `DeepCAD_RT_pytorch/pth`, respectively. You can change the dataset and the model by changing the parameters `datasets_path` and `denoise_model`.
+
+```
+python demo_test_pipeline.py
+```
+
+### Jupyter notebook
+
+We provide simple and user-friendly Jupyter notebooks to implement DeepCAD-RT. They are in the `DeepCAD_RT_pytorch/notebooks` folder. Before you launch the notebooks, please configure an environment following the instruction in [Environment configuration](#environment-configuration) . And then, you can launch the notebooks through the following commands:
+
+```
+$ conda activate deepcadrt
+$ cd DeepCAD-RT/DeepCAD_RT_pytorch/notebooks
+$ jupyter notebook
+```
+
+### Colab notebook
+
+We also provide a cloud-based notebook implemented with Google Colab. You can run DeepCAD-RT directly in your browser using a cloud GPU without configuring the environment. 
+
+[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cabooster/DeepCAD-RT/blob/main/DeepCAD_RT_pytorch/notebooks/DeepCAD_RT_demo_colab.ipynb)
+
+*Note: The Colab notebook needs much longer time to train and test because of the limited GPU performance offered by Colab.*
+
+
+
+## Matlab GUI
+
+To achieve real-time denoising, DeepCAD-RT was optimally deployed on GPU using TensorRT (Nvidia) for further acceleration and memory reduction. We also designed a sophisticated time schedule for multi-thread processing. Based on a two-photon microscope, real-time denoising has been achieved with our Matlab GUI of DeepCAD-RT (tested on a Windows desktop with Intel i9 CPU and 128 GB RAM).  **Tutorials** on installing and using the GUI has been moved to [**this page**](https://github.com/cabooster/DeepCAD-RT/tree/main/DeepCAD_RT_GUI).  
+
+<center><img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/GUI2.png?raw=true" width="950" align="middle"></center> 
+
+## Results
+
+**1. Universal denoising for calcium imaging in zebrafish.**
+
+[![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv3_video.png?raw=true.png)]( https://www.youtube.com/embed/GN0IO7bGoGg "Video Title")
+
+**2. Denoising performance of DeepCAD-RT of neutrophils in the mouse brain in vivo.** 
+
+[![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv8_video.png?raw=true.png)]( https://www.youtube.com/embed/eyLPVRcEGHs "Video Title")
+
+**3. Denoising performance of DeepCAD-RT on a recently developed genetically encoded ATP sensor.**
+
+[![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv10_video.png?raw=true.png)](https://www.youtube.com/embed/u1ejSaVvWiY "Video Title")
+
+More demo videos are demonstrated on [our website](https://cabooster.github.io/DeepCAD-RT/Gallery/).
+
+## Citation
+
+If you use this code please cite the companion paper where the original method appeared: 
+
+- Xinyang Li, Yixin Li, Yiliang Zhou, et al. Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit. bioRxiv (2022). [https://doi.org/10.1101/2022.03.14.484230](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1)
+
+- Xinyang Li, Guoxun Zhang, Jiamin Wu, et al. Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising. Nat Methods 18, 1395–1400 (2021). [https://doi.org/10.1038/s41592-021-01225-0](https://www.nature.com/articles/s41592-021-01225-0) 
+
+
+```
+@article {Li2022.03.14.484230,
+  author = {Li, Xinyang and Li, Yixin and Zhou, Yiliang and Wu, Jiamin and Zhao, Zhifeng and Fan, Jiaqi and Deng, Fei and Wu, Zhaofa and Xiao, Guihua and He, Jing and Zhang, Yuanlong and Zhang, Guoxun and Hu, Xiaowan and Zhang, Yi and Qiao, Hui and Xie, Hao and Li, Yulong and Wang, Haoqian and Fang, Lu and Dai, Qionghai},
+  title = {Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit},
+  elocation-id = {2022.03.14.484230},
+  year = {2022},
+  doi = {10.1101/2022.03.14.484230},
+  publisher = {Cold Spring Harbor Laboratory},
+  URL = {https://www.biorxiv.org/content/early/2022/03/14/2022.03.14.484230},
+  eprint = {https://www.biorxiv.org/content/early/2022/03/14/2022.03.14.484230.full.pdf},
+  journal = {bioRxiv}
+}
+@article{li2021reinforcing,
+  title={Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising},
+  author={Li, Xinyang and Zhang, Guoxun and Wu, Jiamin and Zhang, Yuanlong and Zhao, Zhifeng and Lin, Xing and Qiao, Hui and Xie, Hao and Wang, Haoqian and Fang, Lu and others},
+  journal={Nature Methods},
+  volume={18},
+  number={11},
+  pages={1395--1400},
+  year={2021},
+  publisher={Nature Publishing Group}
+}
+```
+
+
+
```

### Comparing `deepcad-1.0.0/README.md` & `deepcad-1.0.1/PKG-INFO`

 * *Files 25% similar despite different names*

```diff
@@ -1,157 +1,170 @@
-# DeepCAD-RT: Real-time denoising of fluorescence time-lapse imaging using deep self-supervised learning
-
-<img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/logo.PNG?raw=true" width="700" align="middle" />
-
-### [Project page](https://cabooster.github.io/DeepCAD-RT/) | [Paper](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1)
-
-
-
-## Overview
-
-**Among the challenges of fluorescence microscopy, poor imaging signal-to-noise ratio (SNR) caused by limited photon budget lingeringly stands in the central position.** Fluorescence microscopy is inherently sensitive to detection noise because the photon flux in fluorescence imaging is far lower than that in photography. For almost all fluorescence imaging technologies, the inherent [**shot-noise limit**](https://cabooster.github.io/DeepCAD-RT/About/) determines the upper bound of imaging SNR and restricts the imaging resolution, speed, and sensitivity. To capture enough fluorescence photons for satisfactory SNR, researchers have to sacrifice imaging resolution, speed, and even sample health.  
-
-We present a versatile method **DeepCAD-RT** to denoise fluorescence time-lapse images with rapid processing speed that can be incorporated with the microscope acquisition system to achieve real-time denoising. Our method is based on deep self-supervised learning and the original low-SNR data can be directly used for training convolutional networks, making it particularly advantageous in functional imaging where the sample is undergoing fast dynamics and capturing ground-truth data is hard or impossible. We have demonstrated extensive experiments including calcium imaging in mice, zebrafish, and flies, cell migration observations, and the imaging of a new genetically encoded ATP sensor, covering both 2D single-plane imaging and 3D volumetric imaging. **Qualitative and quantitative evaluations show that our method can substantially enhance fluorescence time-lapse imaging data and permit high-sensitivity imaging of biological dynamics beyond the shot-noise limit.**
-
-For more details, please see the companion paper where the method first appeared: 
-["*Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit, bioRxiv (2022)*"](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1).
-
-
-
-<img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/schematic.png?raw=true" width="800" align="middle">
-
-
-
-## Pytorch code
-
-### Our environment 
-
-* Ubuntu 16.04 
-* Python 3.6
-* Pytorch 1.8.0
-* NVIDIA GPU (GeForce RTX 3090) + CUDA (11.1)
-
-### Environment configuration
-
-1. Create a virtual environment and install PyTorch. In the 3rd step, please select the correct Pytorch version that matches your CUDA version from [https://pytorch.org/get-started/previous-versions/](https://pytorch.org/get-started/previous-versions/). 
-
-   ```
-   $ conda create -n deepcadrt python=3.6
-   $ conda activate deepcadrt
-   $ pip install torch==1.8.0+cu111 torchvision==0.9.0+cu111 torchaudio==0.8.0 -f https://download.pytorch.org/whl/torch_stable.html
-   ```
-   
-      *Note:  `pip install` command is required for Pytorch installation.*
-  
-2. We made a installable pip realease of DeepCAD-RT [[pypi](https://pypi.org/project/deepcad/)]. You can install it by entering the following command:
-
-   ```
-   $ pip install deepcad
-   ```
-
-### Download the source code
-
-```
-$ git clone https://github.com/cabooster/DeepCAD-RT
-$ cd DeepCAD-RT/DeepCAD_RT_pytorch/
-```
-
-### Demos
-
-To try out the Python code, please activate the `deepcadrt` environment first:
-
-```
-$ conda activate deepcadrt
-$ cd DeepCAD-RT/DeepCAD_RT_pytorch/
-```
-
-**Example training**
-
-To train a DeepCAD-RT model, we recommend starting with the demo script `demo_train_pipeline.py`. One demo dataset will be downloaded to the `DeepCAD_RT_pytorch/datasets` folder automatically. You can also download other data from [the companion webpage](https://cabooster.github.io/DeepCAD-RT/Datasets/) or use your own data by changing the training parameter `datasets_path`. 
-
-```
-python demo_train_pipeline.py
-```
-
-**Example testing**
-
-To test the denoising performance with pre-trained models, you can run the demo script `demo_test_pipeline.py` . A demo dataset and its denoising model will be automatically downloaded to `DeepCAD_RT_pytorch/datasets` and `DeepCAD_RT_pytorch/pth`, respectively. You can change the dataset and the model by changing the parameters `datasets_path` and `denoise_model`.
-
-```
-python demo_test_pipeline.py
-```
-
-### Jupyter notebook
-
-We provide simple and user-friendly Jupyter notebooks to implement DeepCAD-RT. They are in the `DeepCAD_RT_pytorch/notebooks` folder. Before you launch the notebooks, please configure an environment following the instruction in [Environment configuration](#environment-configuration) . And then, you can launch the notebooks through the following commands:
-
-```
-$ conda activate deepcadrt
-$ cd DeepCAD-RT/DeepCAD_RT_pytorch/notebooks
-$ jupyter notebook
-```
-
-### Colab notebook
-
-We also provide a cloud-based notebook implemented with Google Colab. You can run DeepCAD-RT directly in your browser using a cloud GPU without configuring the environment. 
-
-[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cabooster/DeepCAD-RT/blob/main/DeepCAD_RT_pytorch/notebooks/DeepCAD_RT_demo_colab.ipynb)
-
-*Note: The Colab notebook needs much longer time to train and test because of the limited GPU performance offered by Colab.*
-
-
-
-## Matlab GUI
-
-To achieve real-time denoising, DeepCAD-RT was optimally deployed on GPU using TensorRT (Nvidia) for further acceleration and memory reduction. We also designed a sophisticated time schedule for multi-thread processing. Based on a two-photon microscope, real-time denoising has been achieved with our Matlab GUI of DeepCAD-RT (tested on a Windows desktop with Intel i9 CPU and 128 GB RAM).  **Tutorials** on installing and using the GUI has been moved to [**this page**](https://github.com/cabooster/DeepCAD-RT/tree/main/DeepCAD_RT_GUI).  
-
-<center><img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/GUI2.png?raw=true" width="950" align="middle"></center> 
-
-## Results
-
-**1. Universal denoising for calcium imaging in zebrafish.**
-
-[![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv3_video.png?raw=true.png)]( https://www.youtube.com/embed/GN0IO7bGoGg "Video Title")
-
-**2. Denoising performance of DeepCAD-RT of neutrophils in the mouse brain in vivo.** 
-
-[![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv8_video.png?raw=true.png)]( https://www.youtube.com/embed/eyLPVRcEGHs "Video Title")
-
-**3. Denoising performance of DeepCAD-RT on a recently developed genetically encoded ATP sensor.**
-
-[![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv10_video.png?raw=true.png)](https://www.youtube.com/embed/u1ejSaVvWiY "Video Title")
-
-More demo videos are demonstrated on [our website](https://cabooster.github.io/DeepCAD-RT/Gallery/).
-
-## Citation
-
-If you use this code please cite the companion paper where the original method appeared: 
-
-- Xinyang Li, Yixin Li, Yiliang Zhou, et al. Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit. bioRxiv (2022). [https://doi.org/10.1101/2022.03.14.484230](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1)
-
-- Xinyang Li, Guoxun Zhang, Jiamin Wu, et al. Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising. Nat Methods 18, 1395–1400 (2021). [https://doi.org/10.1038/s41592-021-01225-0](https://www.nature.com/articles/s41592-021-01225-0) 
-
-
-```
-@article {Li2022.03.14.484230,
-  author = {Li, Xinyang and Li, Yixin and Zhou, Yiliang and Wu, Jiamin and Zhao, Zhifeng and Fan, Jiaqi and Deng, Fei and Wu, Zhaofa and Xiao, Guihua and He, Jing and Zhang, Yuanlong and Zhang, Guoxun and Hu, Xiaowan and Zhang, Yi and Qiao, Hui and Xie, Hao and Li, Yulong and Wang, Haoqian and Fang, Lu and Dai, Qionghai},
-  title = {Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit},
-  elocation-id = {2022.03.14.484230},
-  year = {2022},
-  doi = {10.1101/2022.03.14.484230},
-  publisher = {Cold Spring Harbor Laboratory},
-  URL = {https://www.biorxiv.org/content/early/2022/03/14/2022.03.14.484230},
-  eprint = {https://www.biorxiv.org/content/early/2022/03/14/2022.03.14.484230.full.pdf},
-  journal = {bioRxiv}
-}
-@article{li2021reinforcing,
-  title={Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising},
-  author={Li, Xinyang and Zhang, Guoxun and Wu, Jiamin and Zhang, Yuanlong and Zhao, Zhifeng and Lin, Xing and Qiao, Hui and Xie, Hao and Wang, Haoqian and Fang, Lu and others},
-  journal={Nature Methods},
-  volume={18},
-  number={11},
-  pages={1395--1400},
-  year={2021},
-  publisher={Nature Publishing Group}
-}
-```
-
+Metadata-Version: 2.1
+Name: deepcad
+Version: 1.0.1
+Summary: Implement DeepCAD-RT to denoise data by removing independent noise
+Home-page: https://github.com/cabooster/DeepCAD-RT
+Author: Xinyang Li, Yixin Li
+Author-email: liyixin318@gmail.com
+License: GNU General Public License v2.0
+Platform: UNKNOWN
+Description-Content-Type: text/markdown
+
+# DeepCAD-RT: Real-time denoising of fluorescence time-lapse imaging using deep self-supervised learning
+
+<img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/logo.PNG?raw=true" width="700" align="middle" />
+
+### [Project page](https://cabooster.github.io/DeepCAD-RT/) | [Paper](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1)
+
+
+
+## Overview
+
+**Among the challenges of fluorescence microscopy, poor imaging signal-to-noise ratio (SNR) caused by limited photon budget lingeringly stands in the central position.** Fluorescence microscopy is inherently sensitive to detection noise because the photon flux in fluorescence imaging is far lower than that in photography. For almost all fluorescence imaging technologies, the inherent [**shot-noise limit**](https://cabooster.github.io/DeepCAD-RT/About/) determines the upper bound of imaging SNR and restricts the imaging resolution, speed, and sensitivity. To capture enough fluorescence photons for satisfactory SNR, researchers have to sacrifice imaging resolution, speed, and even sample health.  
+
+We present a versatile method **DeepCAD-RT** to denoise fluorescence time-lapse images with rapid processing speed that can be incorporated with the microscope acquisition system to achieve real-time denoising. Our method is based on deep self-supervised learning and the original low-SNR data can be directly used for training convolutional networks, making it particularly advantageous in functional imaging where the sample is undergoing fast dynamics and capturing ground-truth data is hard or impossible. We have demonstrated extensive experiments including calcium imaging in mice, zebrafish, and flies, cell migration observations, and the imaging of a new genetically encoded ATP sensor, covering both 2D single-plane imaging and 3D volumetric imaging. **Qualitative and quantitative evaluations show that our method can substantially enhance fluorescence time-lapse imaging data and permit high-sensitivity imaging of biological dynamics beyond the shot-noise limit.**
+
+For more details, please see the companion paper where the method first appeared: 
+["*Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit, bioRxiv (2022)*"](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1).
+
+
+
+<img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/schematic.png?raw=true" width="800" align="middle">
+
+
+
+## Pytorch code
+
+### Our environment 
+
+* Ubuntu 16.04 
+* Python 3.6
+* Pytorch 1.8.0
+* NVIDIA GPU (GeForce RTX 3090) + CUDA (11.1)
+
+### Environment configuration
+
+1. Create a virtual environment and install PyTorch. In the 3rd step, please select the correct Pytorch version that matches your CUDA version from [https://pytorch.org/get-started/previous-versions/](https://pytorch.org/get-started/previous-versions/). 
+
+   ```
+   $ conda create -n deepcadrt python=3.6
+   $ conda activate deepcadrt
+   $ pip install torch==1.8.0+cu111 torchvision==0.9.0+cu111 torchaudio==0.8.0 -f https://download.pytorch.org/whl/torch_stable.html
+   ```
+   
+      *Note:  `pip install` command is required for Pytorch installation.*
+  
+2. We made a installable pip realease of DeepCAD-RT [[pypi](https://pypi.org/project/deepcad/)]. You can install it by entering the following command:
+
+   ```
+   $ pip install deepcad
+   ```
+
+### Download the source code
+
+```
+$ git clone https://github.com/cabooster/DeepCAD-RT
+$ cd DeepCAD-RT/DeepCAD_RT_pytorch/
+```
+
+### Demos
+
+To try out the Python code, please activate the `deepcadrt` environment first:
+
+```
+$ conda activate deepcadrt
+$ cd DeepCAD-RT/DeepCAD_RT_pytorch/
+```
+
+**Example training**
+
+To train a DeepCAD-RT model, we recommend starting with the demo script `demo_train_pipeline.py`. One demo dataset will be downloaded to the `DeepCAD_RT_pytorch/datasets` folder automatically. You can also download other data from [the companion webpage](https://cabooster.github.io/DeepCAD-RT/Datasets/) or use your own data by changing the training parameter `datasets_path`. 
+
+```
+python demo_train_pipeline.py
+```
+
+**Example testing**
+
+To test the denoising performance with pre-trained models, you can run the demo script `demo_test_pipeline.py` . A demo dataset and its denoising model will be automatically downloaded to `DeepCAD_RT_pytorch/datasets` and `DeepCAD_RT_pytorch/pth`, respectively. You can change the dataset and the model by changing the parameters `datasets_path` and `denoise_model`.
+
+```
+python demo_test_pipeline.py
+```
+
+### Jupyter notebook
+
+We provide simple and user-friendly Jupyter notebooks to implement DeepCAD-RT. They are in the `DeepCAD_RT_pytorch/notebooks` folder. Before you launch the notebooks, please configure an environment following the instruction in [Environment configuration](#environment-configuration) . And then, you can launch the notebooks through the following commands:
+
+```
+$ conda activate deepcadrt
+$ cd DeepCAD-RT/DeepCAD_RT_pytorch/notebooks
+$ jupyter notebook
+```
+
+### Colab notebook
+
+We also provide a cloud-based notebook implemented with Google Colab. You can run DeepCAD-RT directly in your browser using a cloud GPU without configuring the environment. 
+
+[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cabooster/DeepCAD-RT/blob/main/DeepCAD_RT_pytorch/notebooks/DeepCAD_RT_demo_colab.ipynb)
+
+*Note: The Colab notebook needs much longer time to train and test because of the limited GPU performance offered by Colab.*
+
+
+
+## Matlab GUI
+
+To achieve real-time denoising, DeepCAD-RT was optimally deployed on GPU using TensorRT (Nvidia) for further acceleration and memory reduction. We also designed a sophisticated time schedule for multi-thread processing. Based on a two-photon microscope, real-time denoising has been achieved with our Matlab GUI of DeepCAD-RT (tested on a Windows desktop with Intel i9 CPU and 128 GB RAM).  **Tutorials** on installing and using the GUI has been moved to [**this page**](https://github.com/cabooster/DeepCAD-RT/tree/main/DeepCAD_RT_GUI).  
+
+<center><img src="https://github.com/cabooster/DeepCAD-RT/blob/page/images/GUI2.png?raw=true" width="950" align="middle"></center> 
+
+## Results
+
+**1. Universal denoising for calcium imaging in zebrafish.**
+
+[![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv3_video.png?raw=true.png)]( https://www.youtube.com/embed/GN0IO7bGoGg "Video Title")
+
+**2. Denoising performance of DeepCAD-RT of neutrophils in the mouse brain in vivo.** 
+
+[![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv8_video.png?raw=true.png)]( https://www.youtube.com/embed/eyLPVRcEGHs "Video Title")
+
+**3. Denoising performance of DeepCAD-RT on a recently developed genetically encoded ATP sensor.**
+
+[![IMAGE ALT TEXT](https://github.com/cabooster/DeepCAD-RT/blob/page/images/sv10_video.png?raw=true.png)](https://www.youtube.com/embed/u1ejSaVvWiY "Video Title")
+
+More demo videos are demonstrated on [our website](https://cabooster.github.io/DeepCAD-RT/Gallery/).
+
+## Citation
+
+If you use this code please cite the companion paper where the original method appeared: 
+
+- Xinyang Li, Yixin Li, Yiliang Zhou, et al. Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit. bioRxiv (2022). [https://doi.org/10.1101/2022.03.14.484230](https://www.biorxiv.org/content/10.1101/2022.03.14.484230v1)
+
+- Xinyang Li, Guoxun Zhang, Jiamin Wu, et al. Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising. Nat Methods 18, 1395–1400 (2021). [https://doi.org/10.1038/s41592-021-01225-0](https://www.nature.com/articles/s41592-021-01225-0) 
+
+
+```
+@article {Li2022.03.14.484230,
+  author = {Li, Xinyang and Li, Yixin and Zhou, Yiliang and Wu, Jiamin and Zhao, Zhifeng and Fan, Jiaqi and Deng, Fei and Wu, Zhaofa and Xiao, Guihua and He, Jing and Zhang, Yuanlong and Zhang, Guoxun and Hu, Xiaowan and Zhang, Yi and Qiao, Hui and Xie, Hao and Li, Yulong and Wang, Haoqian and Fang, Lu and Dai, Qionghai},
+  title = {Real-time denoising of fluorescence time-lapse imaging enables high-sensitivity observations of biological dynamics beyond the shot-noise limit},
+  elocation-id = {2022.03.14.484230},
+  year = {2022},
+  doi = {10.1101/2022.03.14.484230},
+  publisher = {Cold Spring Harbor Laboratory},
+  URL = {https://www.biorxiv.org/content/early/2022/03/14/2022.03.14.484230},
+  eprint = {https://www.biorxiv.org/content/early/2022/03/14/2022.03.14.484230.full.pdf},
+  journal = {bioRxiv}
+}
+@article{li2021reinforcing,
+  title={Reinforcing neuron extraction and spike inference in calcium imaging using deep self-supervised denoising},
+  author={Li, Xinyang and Zhang, Guoxun and Wu, Jiamin and Zhang, Yuanlong and Zhao, Zhifeng and Lin, Xing and Qiao, Hui and Xie, Hao and Wang, Haoqian and Fang, Lu and others},
+  journal={Nature Methods},
+  volume={18},
+  number={11},
+  pages={1395--1400},
+  year={2021},
+  publisher={Nature Publishing Group}
+}
+```
+
+
+
```

### Comparing `deepcad-1.0.0/setup.py` & `deepcad-1.0.1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -11,15 +11,15 @@
 
 with open("README.md", 'r', encoding='utf-8') as f:
     readme = f.read()
 
 
 setup(
     name="deepcad",
-    version="1.0.0",
+    version="1.0.1",
     description=("Implement DeepCAD-RT to denoise data by "
                  "removing independent noise"),
     long_description=readme,
     long_description_content_type="text/markdown",
     author="Xinyang Li, Yixin Li",
     author_email="liyixin318@gmail.com",
     url="https://github.com/cabooster/DeepCAD-RT",
```

