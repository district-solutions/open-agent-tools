# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/flava/data/datamodules.py

Prompts

```
['create an ImageDataModule with HuggingFace dataset infos and custom image transforms for training', 'create a TextDataModule with dataset infos and text columns for language model training', 'create an MLMDataModule with masked language modeling probability for text pretraining', 'create a VLDataModule with vision-language dataset infos and image fetching parameters', 'create a TorchVisionDataModule with torchvision dataset info and image transforms', 'create default torchvision image transforms with resize, tensor conversion, and normalization', 'create FLAVA image pretraining transforms for training and evaluation pipelines', 'create a BERT-based text tokenization transform with padding and truncation', 'create a vision-language text transform using whole word masking tokenizer', 'use VLTransform to jointly transform image and text data with ITM labels', 'build a combined HuggingFace dataset from a list of HFDatasetInfo objects with column renaming and removal', 'fetch a single image from a URL with configurable retries, timeout, and sleep between attempts', 'fetch multiple images in parallel from a batch of URLs using a thread pool executor', 'review the build_datasets_from_info function to understand how it loads, transforms, and concatenates HuggingFace datasets', 'refactor the fetch_images function to support additional image preprocessing steps after parallel download']
```

Usage

```
{'create_ImageDataModule': 'create an ImageDataModule with HuggingFace dataset infos and custom image transforms for training', 'create_TextDataModule': 'create a TextDataModule with dataset infos and text columns for language model training', 'create_MLMDataModule': 'create an MLMDataModule with masked language modeling probability for text pretraining', 'create_VLDataModule': 'create a VLDataModule with vision-language dataset infos and image fetching parameters', 'create_TorchVisionDataModule': 'create a TorchVisionDataModule with torchvision dataset info and image transforms'}
```

## File: facebookresearch_multimodal/examples/flava/data/transforms.py

Prompts

```
['create an ImageDataModule with HuggingFace dataset infos and custom image transforms for training', 'create a TextDataModule with dataset infos and text columns for language model training', 'create an MLMDataModule with masked language modeling probability for text pretraining', 'create a VLDataModule with vision-language dataset infos and image fetching parameters', 'create a TorchVisionDataModule with torchvision dataset info and image transforms', 'create default torchvision image transforms with resize, tensor conversion, and normalization', 'create FLAVA image pretraining transforms for training and evaluation pipelines', 'create a BERT-based text tokenization transform with padding and truncation', 'create a vision-language text transform using whole word masking tokenizer', 'use VLTransform to jointly transform image and text data with ITM labels', 'build a combined HuggingFace dataset from a list of HFDatasetInfo objects with column renaming and removal', 'fetch a single image from a URL with configurable retries, timeout, and sleep between attempts', 'fetch multiple images in parallel from a batch of URLs using a thread pool executor', 'review the build_datasets_from_info function to understand how it loads, transforms, and concatenates HuggingFace datasets', 'refactor the fetch_images function to support additional image preprocessing steps after parallel download']
```

Usage

```
{'create_torchvision_transforms': 'create default torchvision image transforms with resize, tensor conversion, and normalization', 'create_image_pretraining_transforms': 'create FLAVA image pretraining transforms for training and evaluation pipelines', 'create_text_transform': 'create a BERT-based text tokenization transform with padding and truncation', 'create_vl_text_transform': 'create a vision-language text transform using whole word masking tokenizer', 'use_VLTransform': 'use VLTransform to jointly transform image and text data with ITM labels'}
```

## File: facebookresearch_multimodal/examples/flava/data/utils.py

Prompts

```
['create an ImageDataModule with HuggingFace dataset infos and custom image transforms for training', 'create a TextDataModule with dataset infos and text columns for language model training', 'create an MLMDataModule with masked language modeling probability for text pretraining', 'create a VLDataModule with vision-language dataset infos and image fetching parameters', 'create a TorchVisionDataModule with torchvision dataset info and image transforms', 'create default torchvision image transforms with resize, tensor conversion, and normalization', 'create FLAVA image pretraining transforms for training and evaluation pipelines', 'create a BERT-based text tokenization transform with padding and truncation', 'create a vision-language text transform using whole word masking tokenizer', 'use VLTransform to jointly transform image and text data with ITM labels', 'build a combined HuggingFace dataset from a list of HFDatasetInfo objects with column renaming and removal', 'fetch a single image from a URL with configurable retries, timeout, and sleep between attempts', 'fetch multiple images in parallel from a batch of URLs using a thread pool executor', 'review the build_datasets_from_info function to understand how it loads, transforms, and concatenates HuggingFace datasets', 'refactor the fetch_images function to support additional image preprocessing steps after parallel download']
```

Usage

```
{'build_datasets_from_info': 'build a combined HuggingFace dataset from a list of HFDatasetInfo objects with column renaming and removal', 'fetch_single_image': 'fetch a single image from a URL with configurable retries, timeout, and sleep between attempts', 'fetch_images': 'fetch multiple images in parallel from a batch of URLs using a thread pool executor', 'review_build_datasets_from_info': 'review the build_datasets_from_info function to understand how it loads, transforms, and concatenates HuggingFace datasets', 'refactor_fetch_images': 'refactor the fetch_images function to support additional image preprocessing steps after parallel download'}
```

