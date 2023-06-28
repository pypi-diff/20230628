# Comparing `tmp/open_flamingo-1.0.2.tar.gz` & `tmp/open_flamingo-2.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "open_flamingo-1.0.2.tar", last modified: Tue Mar 14 14:29:11 2023, max compression
+gzip compressed data, was "open_flamingo-2.0.0.tar", last modified: Wed Jun 28 16:42:40 2023, max compression
```

## Comparing `open_flamingo-1.0.2.tar` & `open_flamingo-2.0.0.tar`

### file list

```diff
@@ -1,13 +1,38 @@
-drwxr-xr-x   0 anasawadalla   (501) staff       (20)        0 2023-03-14 14:29:11.026250 open_flamingo-1.0.2/
--rw-r--r--   0 anasawadalla   (501) staff       (20)    10378 2023-03-14 14:29:11.026020 open_flamingo-1.0.2/PKG-INFO
--rw-r--r--   0 anasawadalla   (501) staff       (20)     9920 2023-03-14 14:19:03.000000 open_flamingo-1.0.2/README.md
-drwxr-xr-x   0 anasawadalla   (501) staff       (20)        0 2023-03-14 14:29:11.025134 open_flamingo-1.0.2/open_flamingo/
--rw-r--r--   0 anasawadalla   (501) staff       (20)       88 2023-03-12 22:18:45.000000 open_flamingo-1.0.2/open_flamingo/__init__.py
-drwxr-xr-x   0 anasawadalla   (501) staff       (20)        0 2023-03-14 14:29:11.025806 open_flamingo-1.0.2/open_flamingo.egg-info/
--rw-r--r--   0 anasawadalla   (501) staff       (20)    10378 2023-03-14 14:29:11.000000 open_flamingo-1.0.2/open_flamingo.egg-info/PKG-INFO
--rw-r--r--   0 anasawadalla   (501) staff       (20)      228 2023-03-14 14:29:11.000000 open_flamingo-1.0.2/open_flamingo.egg-info/SOURCES.txt
--rw-r--r--   0 anasawadalla   (501) staff       (20)        1 2023-03-14 14:29:11.000000 open_flamingo-1.0.2/open_flamingo.egg-info/dependency_links.txt
--rw-r--r--   0 anasawadalla   (501) staff       (20)      146 2023-03-14 14:29:11.000000 open_flamingo-1.0.2/open_flamingo.egg-info/requires.txt
--rw-r--r--   0 anasawadalla   (501) staff       (20)       14 2023-03-14 14:29:11.000000 open_flamingo-1.0.2/open_flamingo.egg-info/top_level.txt
--rw-r--r--   0 anasawadalla   (501) staff       (20)       38 2023-03-14 14:29:11.026302 open_flamingo-1.0.2/setup.cfg
--rw-r--r--   0 anasawadalla   (501) staff       (20)     1623 2023-03-14 14:29:07.000000 open_flamingo-1.0.2/setup.py
+drwxr-xr-x   0 anasawadalla   (501) staff       (20)        0 2023-06-28 16:42:40.982278 open_flamingo-2.0.0/
+-rw-r--r--   0 anasawadalla   (501) staff       (20)     1284 2023-04-15 00:19:15.000000 open_flamingo-2.0.0/LICENSE
+-rw-r--r--   0 anasawadalla   (501) staff       (20)    12775 2023-06-28 16:42:40.982083 open_flamingo-2.0.0/PKG-INFO
+-rw-r--r--   0 anasawadalla   (501) staff       (20)    12285 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/README.md
+drwxr-xr-x   0 anasawadalla   (501) staff       (20)        0 2023-06-28 16:42:40.978597 open_flamingo-2.0.0/open_flamingo/
+-rw-r--r--   0 anasawadalla   (501) staff       (20)       88 2023-03-29 22:47:10.000000 open_flamingo-2.0.0/open_flamingo/__init__.py
+drwxr-xr-x   0 anasawadalla   (501) staff       (20)        0 2023-06-28 16:42:40.980273 open_flamingo-2.0.0/open_flamingo/eval/
+-rw-r--r--   0 anasawadalla   (501) staff       (20)        1 2023-03-29 22:47:10.000000 open_flamingo-2.0.0/open_flamingo/eval/__init__.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)    19136 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/eval/classification_utils.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)      585 2023-05-24 23:36:53.000000 open_flamingo-2.0.0/open_flamingo/eval/coco_metric.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)     5385 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/eval/eval_datasets.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)     2577 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/eval/eval_model.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)    44486 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/eval/evaluate.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)     5960 2023-06-05 17:09:48.000000 open_flamingo-2.0.0/open_flamingo/eval/ok_vqa_utils.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)    21751 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/eval/vqa_metric.py
+drwxr-xr-x   0 anasawadalla   (501) staff       (20)        0 2023-06-28 16:42:40.980999 open_flamingo-2.0.0/open_flamingo/src/
+-rw-r--r--   0 anasawadalla   (501) staff       (20)        0 2023-03-29 22:47:10.000000 open_flamingo-2.0.0/open_flamingo/src/__init__.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)     5076 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/src/factory.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)    15244 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/src/flamingo.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)     6381 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/src/flamingo_lm.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)     8743 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/src/helpers.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)     1433 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/src/utils.py
+drwxr-xr-x   0 anasawadalla   (501) staff       (20)        0 2023-06-28 16:42:40.981877 open_flamingo-2.0.0/open_flamingo/train/
+-rw-r--r--   0 anasawadalla   (501) staff       (20)        1 2023-03-29 22:47:10.000000 open_flamingo-2.0.0/open_flamingo/train/__init__.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)     2559 2023-06-28 16:35:58.000000 open_flamingo-2.0.0/open_flamingo/train/convert_mmc4_to_wds.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)    15627 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/train/data.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)     7910 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/train/data_utils.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)     4163 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/train/distributed.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)    17559 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/train/train.py
+-rw-r--r--   0 anasawadalla   (501) staff       (20)    13766 2023-06-28 16:36:00.000000 open_flamingo-2.0.0/open_flamingo/train/train_utils.py
+drwxr-xr-x   0 anasawadalla   (501) staff       (20)        0 2023-06-28 16:42:40.979237 open_flamingo-2.0.0/open_flamingo.egg-info/
+-rw-r--r--   0 anasawadalla   (501) staff       (20)    12775 2023-06-28 16:42:40.000000 open_flamingo-2.0.0/open_flamingo.egg-info/PKG-INFO
+-rw-r--r--   0 anasawadalla   (501) staff       (20)      926 2023-06-28 16:42:40.000000 open_flamingo-2.0.0/open_flamingo.egg-info/SOURCES.txt
+-rw-r--r--   0 anasawadalla   (501) staff       (20)        1 2023-06-28 16:42:40.000000 open_flamingo-2.0.0/open_flamingo.egg-info/dependency_links.txt
+-rw-r--r--   0 anasawadalla   (501) staff       (20)      193 2023-06-28 16:42:40.000000 open_flamingo-2.0.0/open_flamingo.egg-info/requires.txt
+-rw-r--r--   0 anasawadalla   (501) staff       (20)       14 2023-06-28 16:42:40.000000 open_flamingo-2.0.0/open_flamingo.egg-info/top_level.txt
+-rw-r--r--   0 anasawadalla   (501) staff       (20)       38 2023-06-28 16:42:40.982324 open_flamingo-2.0.0/setup.cfg
+-rw-r--r--   0 anasawadalla   (501) staff       (20)     1809 2023-06-28 16:40:56.000000 open_flamingo-2.0.0/setup.py
```

### Comparing `open_flamingo-1.0.2/README.md` & `open_flamingo-2.0.0/open_flamingo.egg-info/PKG-INFO`

 * *Files 22% similar despite different names*

```diff
@@ -1,18 +1,31 @@
-# 🦩 OpenFlamingo
+Metadata-Version: 2.1
+Name: open-flamingo
+Version: 2.0.0
+Summary: An open-source framework for training large multimodal models
+License: MIT
+Keywords: machine learning
+Classifier: Development Status :: 4 - Beta
+Classifier: Intended Audience :: Developers
+Classifier: Topic :: Scientific/Engineering :: Artificial Intelligence
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Programming Language :: Python :: 3.9
+Description-Content-Type: text/markdown
+License-File: LICENSE
 
-## Note: I see there are many folks that have starred the repo. Welcome! We are preparing things for release in under 24 hours. I would wait until then to use the repo :).
+# 🦩 OpenFlamingo
 
 [![PyPI version](https://badge.fury.io/py/open_flamingo.svg)](https://badge.fury.io/py/open_flamingo)
 
-Blog post (coming soon) | Twitter thread (coming soon) | Paper (coming soon)
+Blog posts: [1](https://laion.ai/blog/open-flamingo/), [2](https://laion.ai/blog/open-flamingo-v2/) | Paper (coming soon) | [Demo](https://huggingface.co/spaces/openflamingo/OpenFlamingo)
 
-Welcome to our open source version of DeepMind's [Flamingo](https://www.deepmind.com/blog/tackling-multiple-tasks-with-a-single-visual-language-model) model! In this repository, we provide a PyTorch implementation for training and evaluating OpenFlamingo models. We also provide an initial [OpenFlamingo 3B model](#api) trained on a new Multimodal C4 dataset. Please refer to our blog post for more details.
+Welcome to our open source implementation of DeepMind's [Flamingo](https://www.deepmind.com/blog/tackling-multiple-tasks-with-a-single-visual-language-model)! 
 
-This repo is still under development. You can expect us to release better performing and larger Flamingo models soon. If you have any questions, please feel free to open an issue. We also welcome pull requests!
+In this repository, we provide a PyTorch implementation for training and evaluating OpenFlamingo models.
+If you have any questions, please feel free to open an issue. We also welcome contributions!
 
 # Table of Contents
 - [Installation](#installation)
 - [Approach](#approach)
   * [Model architecture](#model-architecture)
 - [Usage](#usage)
   * [Initializing an OpenFlamingo model](#initializing-an-openflamingo-model)
@@ -23,53 +36,87 @@
 - [Future plans](#future-plans)
 - [Team](#team)
 - [Acknowledgments](#acknowledgments)
 - [Citing](#citing)
 
 # Installation
 
-To create a conda environment for running OpenFlamingo, run
-
+To install the package in an existing environment, run 
 ```
-conda env create -f environment.yml
+pip install open-flamingo
 ```
 
-Alternatively, to install the package in an existing environment, run 
+or to create a conda environment for running OpenFlamingo, run
 ```
-pip install open-flamingo
+conda env create -f environment.yml
 ```
 
-# Usage
-We provide an initial [OpenFlamingo 3B model](https://huggingface.co/openflamingo/OpenFlamingo-3b) using a CLIP ViT-Large vision encoder and an OPT 1.3B language encoder. In general, we support any [CLIP vision encoder](https://huggingface.co/models?search=clip). For the language model, we support [OPT](https://huggingface.co/models?search=opt), [GPT-Neo](https://huggingface.co/models?search=gpt-neo), [GPT-J](https://huggingface.co/models?search=gptj), and [Pythia](https://huggingface.co/models?search=pythia) models.
+# Approach
+OpenFlamingo is a multimodal language model that can be used for a variety of tasks. It is trained on a large multimodal dataset (e.g. Multimodal C4) and can be used to generate text conditioned on interleaved images/text. For example, OpenFlamingo can be used to generate a caption for an image, or to generate a question given an image and a text passage. The benefit of this approach is that we are able to rapidly adapt to new tasks using in-context learning.
+
+## Model architecture
+OpenFlamingo combines a pretrained vision encoder and a language model using cross attention layers. The model architecture is shown below.
 
+![OpenFlamingo architecture](docs/flamingo.png) 
+Credit: [Flamingo](https://www.deepmind.com/blog/tackling-multiple-tasks-with-a-single-visual-language-model)
+
+# Usage
 ## Initializing an OpenFlamingo model
+We support pretrained vision encoders from the [OpenCLIP](https://github.com/mlfoundations/open_clip) package, which includes OpenAI's pretrained models. 
+We also support pretrained language models from the `transformers` package, such as [MPT](https://huggingface.co/models?search=mosaicml%20mpt), [RedPajama](https://huggingface.co/models?search=redpajama), [LLaMA](https://huggingface.co/models?search=llama), [OPT](https://huggingface.co/models?search=opt), [GPT-Neo](https://huggingface.co/models?search=gpt-neo), [GPT-J](https://huggingface.co/models?search=gptj), and [Pythia](https://huggingface.co/models?search=pythia) models.
+
 ``` python
 from open_flamingo import create_model_and_transforms
 
 model, image_processor, tokenizer = create_model_and_transforms(
-    clip_vision_encoder_path="openai/clip-vit-large-patch14",
-    clip_processor_path="openai/clip-vit-large-patch14",
-    lang_encoder_path="facebook/opt-1.3b",
-    tokenizer_path="facebook/opt-1.3b",
+    clip_vision_encoder_path="ViT-L-14",
+    clip_vision_encoder_pretrained="openai",
+    lang_encoder_path="anas-awadalla/mpt-1b-redpajama-200b",
+    tokenizer_path="anas-awadalla/mpt-1b-redpajama-200b",
+    cross_attn_every_n_layers=1
 )
+```
+
+## Released OpenFlamingo models
+We have trained the following OpenFlamingo models so far.
+
+|# params|Language model|Vision encoder|Xattn interval*|COCO 4-shot CIDEr**|VQAv2 4-shot Accuracy**|Weights|
+|------------|--------------|--------------|----------|-----------|-------|----|
+|3B| mosaicml/mpt-1b-redpajama-200b | openai CLIP ViT-L/14 | 1 | 77.3 | 45.9 |[Link](https://huggingface.co/openflamingo/OpenFlamingo-3B-vitl-mpt1b)|
+|3B| mosaicml/mpt-1b-redpajama-200b-dolly | openai CLIP ViT-L/14 | 1 | 82.7 | 46.8 |[Link](https://huggingface.co/openflamingo/OpenFlamingo-3B-vitl-mpt1b-langinstruct)|
+|4B| togethercomputer/RedPajama-INCITE-Base-3B-v1 | openai CLIP ViT-L/14 | 2 | 81.8 | 48.1| [Link](https://huggingface.co/openflamingo/OpenFlamingo-4B-vitl-rpj3b)|
+|4B| togethercomputer/RedPajama-INCITE-Instruct-3B-v1 | openai CLIP ViT-L/14 | 2 | 85.8 | 49.1 | [Link](https://huggingface.co/openflamingo/OpenFlamingo-4B-vitl-rpj3b-langinstruct)|
+|9B| mosaicml/mpt-7b | openai CLIP ViT-L/14 | 4 | 89.0 | 52.3 | [Link](https://huggingface.co/openflamingo/OpenFlamingo-9B-vitl-mpt7b)|
+
+*\* Xattn interval refers to the `--cross_attn_every_n_layers` argument.*
+
+*\*\* 4-shot COCO and VQAv2 performances were calculated over a sample of 5000 test split examples, following the [Flamingo paper](https://arxiv.org/abs/2204.14198).*
+
+Note: as part of our v2 release, we have deprecated a previous LLaMA-based checkpoint. However, you can continue to use our older checkpoint using the new codebase.
 
+## Downloading pretrained weights
+
+To instantiate an OpenFlamingo model with one of our released weights, initialize the model as above and use the following code.
+
+```python
 # grab model checkpoint from huggingface hub
 from huggingface_hub import hf_hub_download
 import torch
 
-checkpoint_path = hf_hub_download("openflamingo/OpenFlamingo-3b", "checkpoint.pt")
+checkpoint_path = hf_hub_download("openflamingo/OpenFlamingo-3B-vitl-mpt1b", "checkpoint.pt")
 model.load_state_dict(torch.load(checkpoint_path), strict=False)
 ```
 
 ## Generating text
-Here is an example of generating text conditioned on interleaved images/text, in this case we will do few-shot image captioning.
+Below is an example of generating text conditioned on interleaved images/text. In particular, let's try few-shot image captioning.
 
 ``` python
 from PIL import Image
 import requests
+import torch
 
 """
 Step 1: Load images
 """
 demo_image_one = Image.open(
     requests.get(
         "http://images.cocodataset.org/val2017/000000039769.jpg", stream=True
@@ -91,34 +138,30 @@
 )
 
 
 """
 Step 2: Preprocessing images
 Details: For OpenFlamingo, we expect the image to be a torch tensor of shape 
  batch_size x num_media x num_frames x channels x height x width. 
- In this case batch_size = 1, num_media = 3, num_frames = 1 
- (this will always be one expect for video which we don't support yet), 
+ In this case batch_size = 1, num_media = 3, num_frames = 1,
  channels = 3, height = 224, width = 224.
 """
-vision_x = image_processor(images=[demo_image_one, demo_image_two, query_image], 
- return_tensors="pt")["pixel_values"]
+vision_x = [image_processor(demo_image_one).unsqueeze(0), image_processor(demo_image_two).unsqueeze(0), image_processor(query_image).unsqueeze(0)]
+vision_x = torch.cat(vision_x, dim=0)
 vision_x = vision_x.unsqueeze(1).unsqueeze(0)
 
-
 """
 Step 3: Preprocessing text
 Details: In the text we expect an <image> special token to indicate where an image is.
  We also expect an <|endofchunk|> special token to indicate the end of the text 
  portion associated with an image.
 """
 tokenizer.padding_side = "left" # For generation padding tokens should be on the left
 lang_x = tokenizer(
     ["<image>An image of two cats.<|endofchunk|><image>An image of a bathroom sink.<|endofchunk|><image>An image of"],
-    max_length=128,
-    padding=True,
     return_tensors="pt",
 )
 
 
 """
 Step 4: Generate text
 """
@@ -129,108 +172,83 @@
     max_new_tokens=20,
     num_beams=3,
 )
 
 print("Generated text: ", tokenizer.decode(generated_text[0]))
 ```
 
-# Approach
-OpenFlamingo is a multimodal language model that can be used for a variety of tasks. It is trained on a large multimodal dataset (e.g. Multimodal C4) and can be used to generate text conditioned on interleaved images/text. For example, OpenFlamingo can be used to generate a caption for an image, or to generate a question given an image and a text passage. The benefit of this approach is that we are able to rapidly adapt to new tasks using in-context training.
-
-## Model architecture
-OpenFlamingo seeks to fuse pretrained a vision encoder and a language model using cross attention layers. The model architecture is shown below.
-
-![OpenFlamingo architecture](docs/flamingo.png) 
-Credit: [Flamingo](https://www.deepmind.com/blog/tackling-multiple-tasks-with-a-single-visual-language-model)
-
 # Training
-To train a model, modify the following example command:
+We provide training scripts in `open_flamingo/train`. We provide an example Slurm script in `open_flamingo/scripts/run_train.py`, as well as the following example command:
+```
+torchrun --nnodes=1 --nproc_per_node=4 open_flamingo/train/train.py \
+  --lm_path anas-awadalla/mpt-1b-redpajama-200b \
+  --tokenizer_path anas-awadalla/mpt-1b-redpajama-200b \
+  --cross_attn_every_n_layers 1 \
+  --dataset_resampled \
+  --batch_size_mmc4 32 \
+  --batch_size_laion 64 \
+  --train_num_samples_mmc4 125000\
+  --train_num_samples_laion 250000 \
+  --loss_multiplier_laion 0.2 \
+  --workers=4 \
+  --run_name OpenFlamingo-3B-vitl-mpt1b \
+  --num_epochs 480 \
+  --warmup_steps  1875 \
+  --mmc4_textsim_threshold 0.24 \
+  --laion_shards "/path/to/shards/shard-{0000..0999}.tar" \
+  --mmc4_shards "/path/to/shards/shard-{0000..0999}.tar" \
+  --report_to_wandb
 ```
-torchrun --nnodes=1 --nproc_per_node=2
-train.py 
---run_name flamingo3B
---lm_path facebook/opt-1.3b \
---dataset_resampled \
---batch_size_c4 4 \
---batch_size_laion 8 \
---train_num_samples_c4 125000 \
---train_num_samples_laion 250000 \
---loss_multiplier_laion 0.2 \
---workers=6 \
---report_to_wandb \
---num_epochs 250 \
---lr_scheduler constant \
---warmup_steps 5000 \
---use_media_placement_augmentation \
---c4_textsim_threshold 30
-```
-
-## Dataset
-We expect all our training datasets to be [WebDataset](https://github.com/webdataset/webdataset) shards.
-We train our models on the [LAION 2B](https://huggingface.co/datasets/laion/laion2B-en) and multimodal C4 (coming soon) datasets. By default the LAION 2B dataset is in WebDataset format if it is downloaded using the [img2dataset tool](https://github.com/rom1504/img2dataset) and the multimodal C4 dataset comes packaged in the WebDataset format.
 
+*Note: The MPT-1B [base](https://huggingface.co/mosaicml/mpt-1b-redpajama-200b)  and [instruct](https://huggingface.co/mosaicml/mpt-1b-redpajama-200b-dolly) modeling code does not accept the `labels` kwarg or compute cross-entropy loss directly within `forward()`, as expected by our codebase. We suggest using a modified version of the MPT-1B models found [here](https://huggingface.co/anas-awadalla/mpt-1b-redpajama-200b) and [here](https://huggingface.co/anas-awadalla/mpt-1b-redpajama-200b-dolly).*
 
-# Evaluation
-We currently support running evaluations on [COCO](https://cocodataset.org/#home), [VQAv2](https://visualqa.org/index.html), [OKVQA](https://okvqa.allenai.org), [Flickr30k](https://www.kaggle.com/datasets/hsankesara/flickr-image-dataset), and [ImageNet](https://image-net.org/index.php). Note that currently these evaluations are ran in validation mode (as specified in the Flamingo paper). We will be adding support for running evaluations in test mode in the future. Moreover we will be adding support [very soon](https://github.com/mlfoundations/open_flamingo/pull/93) for querying demonstrations directly from the training dataset rather than picking a fixed set of demonstrations for evaluation. 
+For more details, see our [training README](https://github.com/mlfoundations/open_flamingo/tree/main/open_flamingo/train).
 
 
-Before evaluating the model, you will need to install the coco evaluation package by running the following command:
-```
-pip install pycocoevalcap
-```
+# Evaluation
+An example evaluation script is at `open_flamingo/scripts/run_eval.sh`. Please see our [evaluation README](https://github.com/mlfoundations/open_flamingo/tree/main/open_flamingo/eval) for more details.
+
 
 To run evaluations on OKVQA you will need to run the following command:
 ```
 import nltk
 nltk.download('wordnet')
 ```
 
-To evaluate the model, use script open_flamingo/eval/evaluate.py. For example, to evaluate the model on COCO and VQAv2, run the following command:
-
-```
-python evaluate.py
---lm_path facebook/opt-1.3b
---lm_tokenizer_path facebook/opt-1.3b
---clip_path openai/clip-vit-large-patch14
---checkpoint_path path/to/checkpoint.pt
---device 0
---coco_image_dir_path path/to/coco/images
---coco_annotations_json_path path/to/coco/captions_train2017.json
---vqav2_image_dir_path path/to/vqav2/images
---vqav2_annotations_json_path path/to/vqav2/v2_mscoco_train2014_annotations.json
---vqav2_questions_json_path path/to/vqav2/v2_OpenEnded_mscoco_train2014_questions.json
---eval_coco
---eval_vqav2
-``` 
 
 # Future plans
 - [ ] Add support for video input
-- [ ] Release better performing and larger OpenFlamingo models
-- [ ] Expand our evaluation suite
-- [ ] Add support for FSDP training
 
 # Team
 
+OpenFlamingo is developed by:
+
+[Anas Awadalla*](https://anas-awadalla.streamlit.app/), [Irena Gao*](https://i-gao.github.io/), [Joshua Gardner](https://homes.cs.washington.edu/~jpgard/), [Jack Hessel](https://jmhessel.com/), [Yusuf Hanafy](https://www.linkedin.com/in/yusufhanafy/), [Wanrong Zhu](https://wanrong-zhu.com/), [Kalyani Marathe](https://sites.google.com/uw.edu/kalyanimarathe/home?authuser=0), [Yonatan Bitton](https://yonatanbitton.github.io/), [Samir Gadre](https://sagadre.github.io/), [Shiori Sagawa](https://cs.stanford.edu/~ssagawa/), [Jenia Jitsev](https://scholar.google.de/citations?user=p1FuAMkAAAAJ&hl=en), [Simon Kornblith](https://simonster.com/), [Pang Wei Koh](https://koh.pw/), [Gabriel Ilharco](https://gabrielilharco.com/), [Mitchell Wortsman](https://mitchellnw.github.io/), [Ludwig Schmidt](https://people.csail.mit.edu/ludwigs/).
+
+The team is primarily from the University of Washington, Stanford, AI2, UCSB, and Google.
 
 # Acknowledgments
-This code is based on Lucidrains' [flamingo implementation](https://github.com/lucidrains/flamingo-pytorch) and David Hansmair's [flamingo-mini repo](https://github.com/dhansmair/flamingo-mini). Thank you for making your code public!
+This code is based on Lucidrains' [flamingo implementation](https://github.com/lucidrains/flamingo-pytorch) and David Hansmair's [flamingo-mini repo](https://github.com/dhansmair/flamingo-mini). Thank you for making your code public! We also thank the [OpenCLIP](https://github.com/mlfoundations/open_clip) team as we use their data loading code and take inspiration from their library design.
 
-We would also like to thank [Jean-Baptiste Alayrac](https://www.jbalayrac.com) and [Antoine Miech](https://antoine77340.github.io) for their advice and thanks to [Stability AI](https://stability.ai) for providing us with compute resources to train these models.
+We would also like to thank [Jean-Baptiste Alayrac](https://www.jbalayrac.com) and [Antoine Miech](https://antoine77340.github.io) for their advice, [Rohan Taori](https://www.rohantaori.com/), [Nicholas Schiefer](https://nicholasschiefer.com/), [Deep Ganguli](https://hai.stanford.edu/people/deep-ganguli), [Thomas Liao](https://thomasliao.com/), [Tatsunori Hashimoto](https://thashim.github.io/), and [Nicholas Carlini](https://nicholas.carlini.com/) for their help with assessing the safety risks of our release, and to [Stability AI](https://stability.ai) for providing us with compute resources to train these models.
 
 # Citing
 If you found this repository useful, please consider citing:
 
 ```
-@software{open_flamingo,
-    author = {...},
-    title = {OpenFlamingo},
-    month = march,
-    year = 2023,
-    note = {If you use this software, please cite it as below.},
-    ... TBD
+@software{anas_awadalla_2023_7733589,
+  author = {Awadalla, Anas and Gao, Irena and Gardner, Joshua and Hessel, Jack and Hanafy, Yusuf and Zhu, Wanrong and Marathe, Kalyani and Bitton, Yonatan and Gadre, Samir and Jitsev, Jenia and Kornblith, Simon and Koh, Pang Wei and Ilharco, Gabriel and Wortsman, Mitchell and Schmidt, Ludwig},
+  title = {OpenFlamingo},
+  month        = mar,
+  year         = 2023,
+  publisher    = {Zenodo},
+  version      = {v0.1.1},
+  doi          = {10.5281/zenodo.7733589},
+  url          = {https://doi.org/10.5281/zenodo.7733589}
+}
 ```
 
 ```
 @article{Alayrac2022FlamingoAV,
   title={Flamingo: a Visual Language Model for Few-Shot Learning},
   author={Jean-Baptiste Alayrac and Jeff Donahue and Pauline Luc and Antoine Miech and Iain Barr and Yana Hasson and Karel Lenc and Arthur Mensch and Katie Millican and Malcolm Reynolds and Roman Ring and Eliza Rutherford and Serkan Cabi and Tengda Han and Zhitao Gong and Sina Samangooei and Marianne Monteiro and Jacob Menick and Sebastian Borgeaud and Andy Brock and Aida Nematzadeh and Sahand Sharifzadeh and Mikolaj Binkowski and Ricardo Barreira and Oriol Vinyals and Andrew Zisserman and Karen Simonyan},
   journal={ArXiv},
```

### Comparing `open_flamingo-1.0.2/open_flamingo.egg-info/PKG-INFO` & `open_flamingo-2.0.0/README.md`

 * *Files 24% similar despite different names*

```diff
@@ -1,31 +1,17 @@
-Metadata-Version: 2.1
-Name: open-flamingo
-Version: 1.0.2
-Summary: A library for training large visual language models
-License: MIT
-Keywords: machine learning
-Classifier: Development Status :: 4 - Beta
-Classifier: Intended Audience :: Developers
-Classifier: Topic :: Scientific/Engineering :: Artificial Intelligence
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Programming Language :: Python :: 3.9
-Description-Content-Type: text/markdown
-
 # 🦩 OpenFlamingo
 
-## Note: I see there are many folks that have starred the repo. Welcome! We are preparing things for release in under 24 hours. I would wait until then to use the repo :).
-
 [![PyPI version](https://badge.fury.io/py/open_flamingo.svg)](https://badge.fury.io/py/open_flamingo)
 
-Blog post (coming soon) | Twitter thread (coming soon) | Paper (coming soon)
+Blog posts: [1](https://laion.ai/blog/open-flamingo/), [2](https://laion.ai/blog/open-flamingo-v2/) | Paper (coming soon) | [Demo](https://huggingface.co/spaces/openflamingo/OpenFlamingo)
 
-Welcome to our open source version of DeepMind's [Flamingo](https://www.deepmind.com/blog/tackling-multiple-tasks-with-a-single-visual-language-model) model! In this repository, we provide a PyTorch implementation for training and evaluating OpenFlamingo models. We also provide an initial [OpenFlamingo 3B model](#api) trained on a new Multimodal C4 dataset. Please refer to our blog post for more details.
+Welcome to our open source implementation of DeepMind's [Flamingo](https://www.deepmind.com/blog/tackling-multiple-tasks-with-a-single-visual-language-model)! 
 
-This repo is still under development. You can expect us to release better performing and larger Flamingo models soon. If you have any questions, please feel free to open an issue. We also welcome pull requests!
+In this repository, we provide a PyTorch implementation for training and evaluating OpenFlamingo models.
+If you have any questions, please feel free to open an issue. We also welcome contributions!
 
 # Table of Contents
 - [Installation](#installation)
 - [Approach](#approach)
   * [Model architecture](#model-architecture)
 - [Usage](#usage)
   * [Initializing an OpenFlamingo model](#initializing-an-openflamingo-model)
@@ -36,53 +22,87 @@
 - [Future plans](#future-plans)
 - [Team](#team)
 - [Acknowledgments](#acknowledgments)
 - [Citing](#citing)
 
 # Installation
 
-To create a conda environment for running OpenFlamingo, run
-
+To install the package in an existing environment, run 
 ```
-conda env create -f environment.yml
+pip install open-flamingo
 ```
 
-Alternatively, to install the package in an existing environment, run 
+or to create a conda environment for running OpenFlamingo, run
 ```
-pip install open-flamingo
+conda env create -f environment.yml
 ```
 
-# Usage
-We provide an initial [OpenFlamingo 3B model](https://huggingface.co/openflamingo/OpenFlamingo-3b) using a CLIP ViT-Large vision encoder and an OPT 1.3B language encoder. In general, we support any [CLIP vision encoder](https://huggingface.co/models?search=clip). For the language model, we support [OPT](https://huggingface.co/models?search=opt), [GPT-Neo](https://huggingface.co/models?search=gpt-neo), [GPT-J](https://huggingface.co/models?search=gptj), and [Pythia](https://huggingface.co/models?search=pythia) models.
+# Approach
+OpenFlamingo is a multimodal language model that can be used for a variety of tasks. It is trained on a large multimodal dataset (e.g. Multimodal C4) and can be used to generate text conditioned on interleaved images/text. For example, OpenFlamingo can be used to generate a caption for an image, or to generate a question given an image and a text passage. The benefit of this approach is that we are able to rapidly adapt to new tasks using in-context learning.
+
+## Model architecture
+OpenFlamingo combines a pretrained vision encoder and a language model using cross attention layers. The model architecture is shown below.
 
+![OpenFlamingo architecture](docs/flamingo.png) 
+Credit: [Flamingo](https://www.deepmind.com/blog/tackling-multiple-tasks-with-a-single-visual-language-model)
+
+# Usage
 ## Initializing an OpenFlamingo model
+We support pretrained vision encoders from the [OpenCLIP](https://github.com/mlfoundations/open_clip) package, which includes OpenAI's pretrained models. 
+We also support pretrained language models from the `transformers` package, such as [MPT](https://huggingface.co/models?search=mosaicml%20mpt), [RedPajama](https://huggingface.co/models?search=redpajama), [LLaMA](https://huggingface.co/models?search=llama), [OPT](https://huggingface.co/models?search=opt), [GPT-Neo](https://huggingface.co/models?search=gpt-neo), [GPT-J](https://huggingface.co/models?search=gptj), and [Pythia](https://huggingface.co/models?search=pythia) models.
+
 ``` python
 from open_flamingo import create_model_and_transforms
 
 model, image_processor, tokenizer = create_model_and_transforms(
-    clip_vision_encoder_path="openai/clip-vit-large-patch14",
-    clip_processor_path="openai/clip-vit-large-patch14",
-    lang_encoder_path="facebook/opt-1.3b",
-    tokenizer_path="facebook/opt-1.3b",
+    clip_vision_encoder_path="ViT-L-14",
+    clip_vision_encoder_pretrained="openai",
+    lang_encoder_path="anas-awadalla/mpt-1b-redpajama-200b",
+    tokenizer_path="anas-awadalla/mpt-1b-redpajama-200b",
+    cross_attn_every_n_layers=1
 )
+```
+
+## Released OpenFlamingo models
+We have trained the following OpenFlamingo models so far.
+
+|# params|Language model|Vision encoder|Xattn interval*|COCO 4-shot CIDEr**|VQAv2 4-shot Accuracy**|Weights|
+|------------|--------------|--------------|----------|-----------|-------|----|
+|3B| mosaicml/mpt-1b-redpajama-200b | openai CLIP ViT-L/14 | 1 | 77.3 | 45.9 |[Link](https://huggingface.co/openflamingo/OpenFlamingo-3B-vitl-mpt1b)|
+|3B| mosaicml/mpt-1b-redpajama-200b-dolly | openai CLIP ViT-L/14 | 1 | 82.7 | 46.8 |[Link](https://huggingface.co/openflamingo/OpenFlamingo-3B-vitl-mpt1b-langinstruct)|
+|4B| togethercomputer/RedPajama-INCITE-Base-3B-v1 | openai CLIP ViT-L/14 | 2 | 81.8 | 48.1| [Link](https://huggingface.co/openflamingo/OpenFlamingo-4B-vitl-rpj3b)|
+|4B| togethercomputer/RedPajama-INCITE-Instruct-3B-v1 | openai CLIP ViT-L/14 | 2 | 85.8 | 49.1 | [Link](https://huggingface.co/openflamingo/OpenFlamingo-4B-vitl-rpj3b-langinstruct)|
+|9B| mosaicml/mpt-7b | openai CLIP ViT-L/14 | 4 | 89.0 | 52.3 | [Link](https://huggingface.co/openflamingo/OpenFlamingo-9B-vitl-mpt7b)|
+
+*\* Xattn interval refers to the `--cross_attn_every_n_layers` argument.*
+
+*\*\* 4-shot COCO and VQAv2 performances were calculated over a sample of 5000 test split examples, following the [Flamingo paper](https://arxiv.org/abs/2204.14198).*
+
+Note: as part of our v2 release, we have deprecated a previous LLaMA-based checkpoint. However, you can continue to use our older checkpoint using the new codebase.
 
+## Downloading pretrained weights
+
+To instantiate an OpenFlamingo model with one of our released weights, initialize the model as above and use the following code.
+
+```python
 # grab model checkpoint from huggingface hub
 from huggingface_hub import hf_hub_download
 import torch
 
-checkpoint_path = hf_hub_download("openflamingo/OpenFlamingo-3b", "checkpoint.pt")
+checkpoint_path = hf_hub_download("openflamingo/OpenFlamingo-3B-vitl-mpt1b", "checkpoint.pt")
 model.load_state_dict(torch.load(checkpoint_path), strict=False)
 ```
 
 ## Generating text
-Here is an example of generating text conditioned on interleaved images/text, in this case we will do few-shot image captioning.
+Below is an example of generating text conditioned on interleaved images/text. In particular, let's try few-shot image captioning.
 
 ``` python
 from PIL import Image
 import requests
+import torch
 
 """
 Step 1: Load images
 """
 demo_image_one = Image.open(
     requests.get(
         "http://images.cocodataset.org/val2017/000000039769.jpg", stream=True
@@ -104,34 +124,30 @@
 )
 
 
 """
 Step 2: Preprocessing images
 Details: For OpenFlamingo, we expect the image to be a torch tensor of shape 
  batch_size x num_media x num_frames x channels x height x width. 
- In this case batch_size = 1, num_media = 3, num_frames = 1 
- (this will always be one expect for video which we don't support yet), 
+ In this case batch_size = 1, num_media = 3, num_frames = 1,
  channels = 3, height = 224, width = 224.
 """
-vision_x = image_processor(images=[demo_image_one, demo_image_two, query_image], 
- return_tensors="pt")["pixel_values"]
+vision_x = [image_processor(demo_image_one).unsqueeze(0), image_processor(demo_image_two).unsqueeze(0), image_processor(query_image).unsqueeze(0)]
+vision_x = torch.cat(vision_x, dim=0)
 vision_x = vision_x.unsqueeze(1).unsqueeze(0)
 
-
 """
 Step 3: Preprocessing text
 Details: In the text we expect an <image> special token to indicate where an image is.
  We also expect an <|endofchunk|> special token to indicate the end of the text 
  portion associated with an image.
 """
 tokenizer.padding_side = "left" # For generation padding tokens should be on the left
 lang_x = tokenizer(
     ["<image>An image of two cats.<|endofchunk|><image>An image of a bathroom sink.<|endofchunk|><image>An image of"],
-    max_length=128,
-    padding=True,
     return_tensors="pt",
 )
 
 
 """
 Step 4: Generate text
 """
@@ -142,108 +158,83 @@
     max_new_tokens=20,
     num_beams=3,
 )
 
 print("Generated text: ", tokenizer.decode(generated_text[0]))
 ```
 
-# Approach
-OpenFlamingo is a multimodal language model that can be used for a variety of tasks. It is trained on a large multimodal dataset (e.g. Multimodal C4) and can be used to generate text conditioned on interleaved images/text. For example, OpenFlamingo can be used to generate a caption for an image, or to generate a question given an image and a text passage. The benefit of this approach is that we are able to rapidly adapt to new tasks using in-context training.
-
-## Model architecture
-OpenFlamingo seeks to fuse pretrained a vision encoder and a language model using cross attention layers. The model architecture is shown below.
-
-![OpenFlamingo architecture](docs/flamingo.png) 
-Credit: [Flamingo](https://www.deepmind.com/blog/tackling-multiple-tasks-with-a-single-visual-language-model)
-
 # Training
-To train a model, modify the following example command:
+We provide training scripts in `open_flamingo/train`. We provide an example Slurm script in `open_flamingo/scripts/run_train.py`, as well as the following example command:
+```
+torchrun --nnodes=1 --nproc_per_node=4 open_flamingo/train/train.py \
+  --lm_path anas-awadalla/mpt-1b-redpajama-200b \
+  --tokenizer_path anas-awadalla/mpt-1b-redpajama-200b \
+  --cross_attn_every_n_layers 1 \
+  --dataset_resampled \
+  --batch_size_mmc4 32 \
+  --batch_size_laion 64 \
+  --train_num_samples_mmc4 125000\
+  --train_num_samples_laion 250000 \
+  --loss_multiplier_laion 0.2 \
+  --workers=4 \
+  --run_name OpenFlamingo-3B-vitl-mpt1b \
+  --num_epochs 480 \
+  --warmup_steps  1875 \
+  --mmc4_textsim_threshold 0.24 \
+  --laion_shards "/path/to/shards/shard-{0000..0999}.tar" \
+  --mmc4_shards "/path/to/shards/shard-{0000..0999}.tar" \
+  --report_to_wandb
 ```
-torchrun --nnodes=1 --nproc_per_node=2
-train.py 
---run_name flamingo3B
---lm_path facebook/opt-1.3b \
---dataset_resampled \
---batch_size_c4 4 \
---batch_size_laion 8 \
---train_num_samples_c4 125000 \
---train_num_samples_laion 250000 \
---loss_multiplier_laion 0.2 \
---workers=6 \
---report_to_wandb \
---num_epochs 250 \
---lr_scheduler constant \
---warmup_steps 5000 \
---use_media_placement_augmentation \
---c4_textsim_threshold 30
-```
-
-## Dataset
-We expect all our training datasets to be [WebDataset](https://github.com/webdataset/webdataset) shards.
-We train our models on the [LAION 2B](https://huggingface.co/datasets/laion/laion2B-en) and multimodal C4 (coming soon) datasets. By default the LAION 2B dataset is in WebDataset format if it is downloaded using the [img2dataset tool](https://github.com/rom1504/img2dataset) and the multimodal C4 dataset comes packaged in the WebDataset format.
 
+*Note: The MPT-1B [base](https://huggingface.co/mosaicml/mpt-1b-redpajama-200b)  and [instruct](https://huggingface.co/mosaicml/mpt-1b-redpajama-200b-dolly) modeling code does not accept the `labels` kwarg or compute cross-entropy loss directly within `forward()`, as expected by our codebase. We suggest using a modified version of the MPT-1B models found [here](https://huggingface.co/anas-awadalla/mpt-1b-redpajama-200b) and [here](https://huggingface.co/anas-awadalla/mpt-1b-redpajama-200b-dolly).*
 
-# Evaluation
-We currently support running evaluations on [COCO](https://cocodataset.org/#home), [VQAv2](https://visualqa.org/index.html), [OKVQA](https://okvqa.allenai.org), [Flickr30k](https://www.kaggle.com/datasets/hsankesara/flickr-image-dataset), and [ImageNet](https://image-net.org/index.php). Note that currently these evaluations are ran in validation mode (as specified in the Flamingo paper). We will be adding support for running evaluations in test mode in the future. Moreover we will be adding support [very soon](https://github.com/mlfoundations/open_flamingo/pull/93) for querying demonstrations directly from the training dataset rather than picking a fixed set of demonstrations for evaluation. 
+For more details, see our [training README](https://github.com/mlfoundations/open_flamingo/tree/main/open_flamingo/train).
 
 
-Before evaluating the model, you will need to install the coco evaluation package by running the following command:
-```
-pip install pycocoevalcap
-```
+# Evaluation
+An example evaluation script is at `open_flamingo/scripts/run_eval.sh`. Please see our [evaluation README](https://github.com/mlfoundations/open_flamingo/tree/main/open_flamingo/eval) for more details.
+
 
 To run evaluations on OKVQA you will need to run the following command:
 ```
 import nltk
 nltk.download('wordnet')
 ```
 
-To evaluate the model, use script open_flamingo/eval/evaluate.py. For example, to evaluate the model on COCO and VQAv2, run the following command:
-
-```
-python evaluate.py
---lm_path facebook/opt-1.3b
---lm_tokenizer_path facebook/opt-1.3b
---clip_path openai/clip-vit-large-patch14
---checkpoint_path path/to/checkpoint.pt
---device 0
---coco_image_dir_path path/to/coco/images
---coco_annotations_json_path path/to/coco/captions_train2017.json
---vqav2_image_dir_path path/to/vqav2/images
---vqav2_annotations_json_path path/to/vqav2/v2_mscoco_train2014_annotations.json
---vqav2_questions_json_path path/to/vqav2/v2_OpenEnded_mscoco_train2014_questions.json
---eval_coco
---eval_vqav2
-``` 
 
 # Future plans
 - [ ] Add support for video input
-- [ ] Release better performing and larger OpenFlamingo models
-- [ ] Expand our evaluation suite
-- [ ] Add support for FSDP training
 
 # Team
 
+OpenFlamingo is developed by:
+
+[Anas Awadalla*](https://anas-awadalla.streamlit.app/), [Irena Gao*](https://i-gao.github.io/), [Joshua Gardner](https://homes.cs.washington.edu/~jpgard/), [Jack Hessel](https://jmhessel.com/), [Yusuf Hanafy](https://www.linkedin.com/in/yusufhanafy/), [Wanrong Zhu](https://wanrong-zhu.com/), [Kalyani Marathe](https://sites.google.com/uw.edu/kalyanimarathe/home?authuser=0), [Yonatan Bitton](https://yonatanbitton.github.io/), [Samir Gadre](https://sagadre.github.io/), [Shiori Sagawa](https://cs.stanford.edu/~ssagawa/), [Jenia Jitsev](https://scholar.google.de/citations?user=p1FuAMkAAAAJ&hl=en), [Simon Kornblith](https://simonster.com/), [Pang Wei Koh](https://koh.pw/), [Gabriel Ilharco](https://gabrielilharco.com/), [Mitchell Wortsman](https://mitchellnw.github.io/), [Ludwig Schmidt](https://people.csail.mit.edu/ludwigs/).
+
+The team is primarily from the University of Washington, Stanford, AI2, UCSB, and Google.
 
 # Acknowledgments
-This code is based on Lucidrains' [flamingo implementation](https://github.com/lucidrains/flamingo-pytorch) and David Hansmair's [flamingo-mini repo](https://github.com/dhansmair/flamingo-mini). Thank you for making your code public!
+This code is based on Lucidrains' [flamingo implementation](https://github.com/lucidrains/flamingo-pytorch) and David Hansmair's [flamingo-mini repo](https://github.com/dhansmair/flamingo-mini). Thank you for making your code public! We also thank the [OpenCLIP](https://github.com/mlfoundations/open_clip) team as we use their data loading code and take inspiration from their library design.
 
-We would also like to thank [Jean-Baptiste Alayrac](https://www.jbalayrac.com) and [Antoine Miech](https://antoine77340.github.io) for their advice and thanks to [Stability AI](https://stability.ai) for providing us with compute resources to train these models.
+We would also like to thank [Jean-Baptiste Alayrac](https://www.jbalayrac.com) and [Antoine Miech](https://antoine77340.github.io) for their advice, [Rohan Taori](https://www.rohantaori.com/), [Nicholas Schiefer](https://nicholasschiefer.com/), [Deep Ganguli](https://hai.stanford.edu/people/deep-ganguli), [Thomas Liao](https://thomasliao.com/), [Tatsunori Hashimoto](https://thashim.github.io/), and [Nicholas Carlini](https://nicholas.carlini.com/) for their help with assessing the safety risks of our release, and to [Stability AI](https://stability.ai) for providing us with compute resources to train these models.
 
 # Citing
 If you found this repository useful, please consider citing:
 
 ```
-@software{open_flamingo,
-    author = {...},
-    title = {OpenFlamingo},
-    month = march,
-    year = 2023,
-    note = {If you use this software, please cite it as below.},
-    ... TBD
+@software{anas_awadalla_2023_7733589,
+  author = {Awadalla, Anas and Gao, Irena and Gardner, Joshua and Hessel, Jack and Hanafy, Yusuf and Zhu, Wanrong and Marathe, Kalyani and Bitton, Yonatan and Gadre, Samir and Jitsev, Jenia and Kornblith, Simon and Koh, Pang Wei and Ilharco, Gabriel and Wortsman, Mitchell and Schmidt, Ludwig},
+  title = {OpenFlamingo},
+  month        = mar,
+  year         = 2023,
+  publisher    = {Zenodo},
+  version      = {v0.1.1},
+  doi          = {10.5281/zenodo.7733589},
+  url          = {https://doi.org/10.5281/zenodo.7733589}
+}
 ```
 
 ```
 @article{Alayrac2022FlamingoAV,
   title={Flamingo: a Visual Language Model for Few-Shot Learning},
   author={Jean-Baptiste Alayrac and Jeff Donahue and Pauline Luc and Antoine Miech and Iain Barr and Yana Hasson and Karel Lenc and Arthur Mensch and Katie Millican and Malcolm Reynolds and Roman Ring and Eliza Rutherford and Serkan Cabi and Tengda Han and Zhitao Gong and Sina Samangooei and Marianne Monteiro and Jacob Menick and Sebastian Borgeaud and Andy Brock and Aida Nematzadeh and Sahand Sharifzadeh and Mikolaj Binkowski and Ricardo Barreira and Oriol Vinyals and Andrew Zisserman and Karen Simonyan},
   journal={ArXiv},
```

### Comparing `open_flamingo-1.0.2/setup.py` & `open_flamingo-2.0.0/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,10 @@
-from setuptools import setup, find_packages
 from pathlib import Path
-import os
+
+from setuptools import find_packages, setup
 
 if __name__ == "__main__":
     with Path(Path(__file__).parent, "README.md").open(encoding="utf-8") as file:
         long_description = file.read()
 
     # TODO: This is a hack to get around the fact that we can't read the requirements.txt file, we should fix this.
     # def _read_reqs(relpath):
@@ -12,23 +12,40 @@
     #     with open(fullpath) as f:
     #         return [
     #             s.strip()
     #             for s in f.readlines()
     #             if (s.strip() and not s.startswith("#"))
     #         ]
 
-    REQUIREMENTS = ["einops", "einops-exts", "transformers", "torch", "torchvision", "pillow", "more-itertools", "datasets", "braceexpand", "webdataset", "wandb", "nltk", "bloom_filter2", "scipy", "inflection"]
+    REQUIREMENTS = [
+        "einops",
+        "einops-exts",
+        "transformers>=4.28.1",
+        "torch==2.0.1",
+        "torchvision",
+        "pillow",
+        "more-itertools",
+        "datasets",
+        "braceexpand",
+        "webdataset",
+        "wandb",
+        "nltk",
+        "scipy",
+        "inflection",
+        "sentencepiece==0.1.98",
+        "open_clip_torch>=2.16.0",
+    ]
 
     setup(
         name="open_flamingo",
         packages=find_packages(),
         include_package_data=True,
-        version="1.0.2",
+        version="2.0.0",
         license="MIT",
-        description="A library for training large visual language models",
+        description="An open-source framework for training large multimodal models",
         long_description=long_description,
         long_description_content_type="text/markdown",
         data_files=[(".", ["README.md"])],
         keywords=["machine learning"],
         install_requires=REQUIREMENTS,
         classifiers=[
             "Development Status :: 4 - Beta",
```

