# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/levit/convert_levit_timm_to_pytorch.py

Prompts

```
['convert a LeViT 128S timm checkpoint to HuggingFace LevitForImageClassificationWithTeacher format', 'convert a LeViT 384 timm checkpoint to HuggingFace LevitForImageClassificationWithTeacher format', 'convert all supported LeViT timm models (128S, 128, 192, 256, 384) to HuggingFace format', 'convert a LeViT timm model and push the checkpoint and image processor to HuggingFace Hub', 'run the LeViT timm-to-pytorch conversion script via argparse with custom output directory', 'create a LevitImageProcessor instance with custom kwargs for image preprocessing', 'resize an image tensor using LevitImageProcessor with shortest_edge scaling factor of 256/224', 'center crop an image tensor to 224x224 using LevitImageProcessor default crop size', 'normalize an image tensor using ImageNet mean and standard deviation via LevitImageProcessor', 'test the LevitImageProcessor resize method with a SizeDict containing shortest_edge key', 'test the resize method when size dict provides a shortest_edge key', 'review the LevitImageProcessorPil class and its PIL backend image processing pipeline', 'summarize the resize method that transforms shortest_edge to height and width via get_resize_output_image_size', 'build a LeViT image classifier model with a linear classification head for ImageNet', 'create a LeViT encoder model with multiple stages of attention and MLP layers for image feature extraction', 'run the LeViT attention mechanism with spatial biases and relative position encoding', 'test the LeViT patch embeddings that convert image patches to token sequences via convolutions', 'review the LeViT image classification with teacher model supporting distillation inference']
```

Usage

```
{'convert_levit_128s_timm_checkpoint': 'convert a LeViT 128S timm checkpoint to HuggingFace LevitForImageClassificationWithTeacher format', 'convert_levit_384_timm_checkpoint': 'convert a LeViT 384 timm checkpoint to HuggingFace LevitForImageClassificationWithTeacher format', 'convert_all_levit_models_timm': 'convert all supported LeViT timm models (128S, 128, 192, 256, 384) to HuggingFace format', 'push_levit_conversion_to_hub': 'convert a LeViT timm model and push the checkpoint and image processor to HuggingFace Hub', 'run_levit_conversion_cli': 'run the LeViT timm-to-pytorch conversion script via argparse with custom output directory'}
```

## File: huggingface_transformers/src/transformers/models/levit/image_processing_levit.py

Prompts

```
['convert a LeViT 128S timm checkpoint to HuggingFace LevitForImageClassificationWithTeacher format', 'convert a LeViT 384 timm checkpoint to HuggingFace LevitForImageClassificationWithTeacher format', 'convert all supported LeViT timm models (128S, 128, 192, 256, 384) to HuggingFace format', 'convert a LeViT timm model and push the checkpoint and image processor to HuggingFace Hub', 'run the LeViT timm-to-pytorch conversion script via argparse with custom output directory', 'create a LevitImageProcessor instance with custom kwargs for image preprocessing', 'resize an image tensor using LevitImageProcessor with shortest_edge scaling factor of 256/224', 'center crop an image tensor to 224x224 using LevitImageProcessor default crop size', 'normalize an image tensor using ImageNet mean and standard deviation via LevitImageProcessor', 'test the LevitImageProcessor resize method with a SizeDict containing shortest_edge key', 'test the resize method when size dict provides a shortest_edge key', 'review the LevitImageProcessorPil class and its PIL backend image processing pipeline', 'summarize the resize method that transforms shortest_edge to height and width via get_resize_output_image_size', 'build a LeViT image classifier model with a linear classification head for ImageNet', 'create a LeViT encoder model with multiple stages of attention and MLP layers for image feature extraction', 'run the LeViT attention mechanism with spatial biases and relative position encoding', 'test the LeViT patch embeddings that convert image patches to token sequences via convolutions', 'review the LeViT image classification with teacher model supporting distillation inference']
```

Usage

```
{'create_levit_image_processor': 'create a LevitImageProcessor instance with custom kwargs for image preprocessing', 'resize_levit_image': 'resize an image tensor using LevitImageProcessor with shortest_edge scaling factor of 256/224', 'center_crop_levit_image': 'center crop an image tensor to 224x224 using LevitImageProcessor default crop size', 'normalize_levit_image': 'normalize an image tensor using ImageNet mean and standard deviation via LevitImageProcessor', 'test_levit_image_processor_resize': 'test the LevitImageProcessor resize method with a SizeDict containing shortest_edge key'}
```

## File: huggingface_transformers/src/transformers/models/levit/image_processing_pil_levit.py

Prompts

```
['convert a LeViT 128S timm checkpoint to HuggingFace LevitForImageClassificationWithTeacher format', 'convert a LeViT 384 timm checkpoint to HuggingFace LevitForImageClassificationWithTeacher format', 'convert all supported LeViT timm models (128S, 128, 192, 256, 384) to HuggingFace format', 'convert a LeViT timm model and push the checkpoint and image processor to HuggingFace Hub', 'run the LeViT timm-to-pytorch conversion script via argparse with custom output directory', 'create a LevitImageProcessor instance with custom kwargs for image preprocessing', 'resize an image tensor using LevitImageProcessor with shortest_edge scaling factor of 256/224', 'center crop an image tensor to 224x224 using LevitImageProcessor default crop size', 'normalize an image tensor using ImageNet mean and standard deviation via LevitImageProcessor', 'test the LevitImageProcessor resize method with a SizeDict containing shortest_edge key', 'test the resize method when size dict provides a shortest_edge key', 'review the LevitImageProcessorPil class and its PIL backend image processing pipeline', 'summarize the resize method that transforms shortest_edge to height and width via get_resize_output_image_size', 'build a LeViT image classifier model with a linear classification head for ImageNet', 'create a LeViT encoder model with multiple stages of attention and MLP layers for image feature extraction', 'run the LeViT attention mechanism with spatial biases and relative position encoding', 'test the LeViT patch embeddings that convert image patches to token sequences via convolutions', 'review the LeViT image classification with teacher model supporting distillation inference']
```

Usage

```
{'create_levit_image_processor': 'create a LevitImageProcessorPil instance with custom resize, normalization, and crop settings', 'resize_levit_image': "resize a numpy image array using LeViT's shortest_edge scaling factor of 256/224", 'test_levit_resize_shortest_edge': 'test the resize method when size dict provides a shortest_edge key', 'review_levit_image_processor_pil': 'review the LevitImageProcessorPil class and its PIL backend image processing pipeline', 'summarize_levit_resize': 'summarize the resize method that transforms shortest_edge to height and width via get_resize_output_image_size'}
```

## File: huggingface_transformers/src/transformers/models/levit/modeling_levit.py

Prompts

```
['convert a LeViT 128S timm checkpoint to HuggingFace LevitForImageClassificationWithTeacher format', 'convert a LeViT 384 timm checkpoint to HuggingFace LevitForImageClassificationWithTeacher format', 'convert all supported LeViT timm models (128S, 128, 192, 256, 384) to HuggingFace format', 'convert a LeViT timm model and push the checkpoint and image processor to HuggingFace Hub', 'run the LeViT timm-to-pytorch conversion script via argparse with custom output directory', 'create a LevitImageProcessor instance with custom kwargs for image preprocessing', 'resize an image tensor using LevitImageProcessor with shortest_edge scaling factor of 256/224', 'center crop an image tensor to 224x224 using LevitImageProcessor default crop size', 'normalize an image tensor using ImageNet mean and standard deviation via LevitImageProcessor', 'test the LevitImageProcessor resize method with a SizeDict containing shortest_edge key', 'test the resize method when size dict provides a shortest_edge key', 'review the LevitImageProcessorPil class and its PIL backend image processing pipeline', 'summarize the resize method that transforms shortest_edge to height and width via get_resize_output_image_size', 'build a LeViT image classifier model with a linear classification head for ImageNet', 'create a LeViT encoder model with multiple stages of attention and MLP layers for image feature extraction', 'run the LeViT attention mechanism with spatial biases and relative position encoding', 'test the LeViT patch embeddings that convert image patches to token sequences via convolutions', 'review the LeViT image classification with teacher model supporting distillation inference']
```

Usage

```
{'build_levit_image_classifier': 'build a LeViT image classifier model with a linear classification head for ImageNet', 'create_levit_model_encoder': 'create a LeViT encoder model with multiple stages of attention and MLP layers for image feature extraction', 'run_levit_attention_forward': 'run the LeViT attention mechanism with spatial biases and relative position encoding', 'test_levit_patch_embeddings': 'test the LeViT patch embeddings that convert image patches to token sequences via convolutions', 'review_levit_teacher_classification': 'review the LeViT image classification with teacher model supporting distillation inference'}
```

