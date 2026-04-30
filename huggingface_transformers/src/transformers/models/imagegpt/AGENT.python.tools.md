# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/imagegpt/convert_imagegpt_original_tf2_to_pytorch.py

Prompts

```
['convert a TensorFlow ImageGPT checkpoint to a PyTorch model with specified size and output path', 'load TensorFlow checkpoint weights into an ImageGPT PyTorch model', 'run the ImageGPT TensorFlow to PyTorch conversion CLI with checkpoint path, model size, and output folder', 'build an ImageGPT PyTorch causal language model from a TensorFlow checkpoint', 'save the converted PyTorch ImageGPT model weights and configuration to a folder', 'create an ImageGPTImageProcessor with custom color clusters and preprocessing settings', 'run color quantization to assign each pixel to its nearest color cluster index', 'build squared Euclidean distance computation between pixel values and color clusters', 'review the ImageGPTImageProcessor preprocess method for resizing, normalization, and color quantization', 'summarize the ImageGPTImageProcessor to_dict method for JSON-serializable configuration output', 'create an ImageGPTImageProcessorPil instance with custom color clusters for discrete token modeling', 'build color quantization by assigning each pixel to its nearest color cluster using squared Euclidean distance', 'test the squared_euclidean_distance function that computes pairwise squared distances between two sets of vectors', 'run the _preprocess method on a batch of images to resize, rescale, normalize, and optionally color-quantize them', 'summarize the to_dict method that serializes the processor configuration, converting arrays to lists', 'build an ImageGPTModel transformer with word-piece embeddings and positional embeddings for image token sequences', 'create an ImageGPTForCausalImageModeling model with a language modeling head for unconditional image generation', 'run image classification with ImageGPTForImageClassification by average-pooling hidden states and projecting to label logits', 'test the ImageGPTAttention forward pass with self-attention, cross-attention, layer past caching, and causal masking', 'review the ImageGPTMLP forward pass that applies a feed-forward network with gelu activation and residual dropout']
```

Usage

```
{'convert_tf_imagegpt_checkpoint': 'convert a TensorFlow ImageGPT checkpoint to a PyTorch model with specified size and output path', 'load_tf_weights_in_imagegpt': 'load TensorFlow checkpoint weights into an ImageGPT PyTorch model', 'run_imagegpt_tf_to_pytorch_cli': 'run the ImageGPT TensorFlow to PyTorch conversion CLI with checkpoint path, model size, and output folder', 'build_imagegpt_pytorch_model': 'build an ImageGPT PyTorch causal language model from a TensorFlow checkpoint', 'save_imagegpt_pytorch_weights': 'save the converted PyTorch ImageGPT model weights and configuration to a folder'}
```

## File: huggingface_transformers/src/transformers/models/imagegpt/image_processing_imagegpt.py

Prompts

```
['convert a TensorFlow ImageGPT checkpoint to a PyTorch model with specified size and output path', 'load TensorFlow checkpoint weights into an ImageGPT PyTorch model', 'run the ImageGPT TensorFlow to PyTorch conversion CLI with checkpoint path, model size, and output folder', 'build an ImageGPT PyTorch causal language model from a TensorFlow checkpoint', 'save the converted PyTorch ImageGPT model weights and configuration to a folder', 'create an ImageGPTImageProcessor with custom color clusters and preprocessing settings', 'run color quantization to assign each pixel to its nearest color cluster index', 'build squared Euclidean distance computation between pixel values and color clusters', 'review the ImageGPTImageProcessor preprocess method for resizing, normalization, and color quantization', 'summarize the ImageGPTImageProcessor to_dict method for JSON-serializable configuration output', 'create an ImageGPTImageProcessorPil instance with custom color clusters for discrete token modeling', 'build color quantization by assigning each pixel to its nearest color cluster using squared Euclidean distance', 'test the squared_euclidean_distance function that computes pairwise squared distances between two sets of vectors', 'run the _preprocess method on a batch of images to resize, rescale, normalize, and optionally color-quantize them', 'summarize the to_dict method that serializes the processor configuration, converting arrays to lists', 'build an ImageGPTModel transformer with word-piece embeddings and positional embeddings for image token sequences', 'create an ImageGPTForCausalImageModeling model with a language modeling head for unconditional image generation', 'run image classification with ImageGPTForImageClassification by average-pooling hidden states and projecting to label logits', 'test the ImageGPTAttention forward pass with self-attention, cross-attention, layer past caching, and causal masking', 'review the ImageGPTMLP forward pass that applies a feed-forward network with gelu activation and residual dropout']
```

Usage

```
{'create_imagegpt_image_processor': 'create an ImageGPTImageProcessor with custom color clusters and preprocessing settings', 'run_color_quantize_torch': 'run color quantization to assign each pixel to its nearest color cluster index', 'build_squared_euclidean_distance_torch': 'build squared Euclidean distance computation between pixel values and color clusters', 'review_imagegpt_image_processor_preprocess': 'review the ImageGPTImageProcessor preprocess method for resizing, normalization, and color quantization', 'summarize_imagegpt_image_processor_to_dict': 'summarize the ImageGPTImageProcessor to_dict method for JSON-serializable configuration output'}
```

## File: huggingface_transformers/src/transformers/models/imagegpt/image_processing_pil_imagegpt.py

Prompts

```
['convert a TensorFlow ImageGPT checkpoint to a PyTorch model with specified size and output path', 'load TensorFlow checkpoint weights into an ImageGPT PyTorch model', 'run the ImageGPT TensorFlow to PyTorch conversion CLI with checkpoint path, model size, and output folder', 'build an ImageGPT PyTorch causal language model from a TensorFlow checkpoint', 'save the converted PyTorch ImageGPT model weights and configuration to a folder', 'create an ImageGPTImageProcessor with custom color clusters and preprocessing settings', 'run color quantization to assign each pixel to its nearest color cluster index', 'build squared Euclidean distance computation between pixel values and color clusters', 'review the ImageGPTImageProcessor preprocess method for resizing, normalization, and color quantization', 'summarize the ImageGPTImageProcessor to_dict method for JSON-serializable configuration output', 'create an ImageGPTImageProcessorPil instance with custom color clusters for discrete token modeling', 'build color quantization by assigning each pixel to its nearest color cluster using squared Euclidean distance', 'test the squared_euclidean_distance function that computes pairwise squared distances between two sets of vectors', 'run the _preprocess method on a batch of images to resize, rescale, normalize, and optionally color-quantize them', 'summarize the to_dict method that serializes the processor configuration, converting arrays to lists', 'build an ImageGPTModel transformer with word-piece embeddings and positional embeddings for image token sequences', 'create an ImageGPTForCausalImageModeling model with a language modeling head for unconditional image generation', 'run image classification with ImageGPTForImageClassification by average-pooling hidden states and projecting to label logits', 'test the ImageGPTAttention forward pass with self-attention, cross-attention, layer past caching, and causal masking', 'review the ImageGPTMLP forward pass that applies a feed-forward network with gelu activation and residual dropout']
```

Usage

```
{'create_ImageGPTImageProcessorPil': 'create an ImageGPTImageProcessorPil instance with custom color clusters for discrete token modeling', 'build_color_quantize': 'build color quantization by assigning each pixel to its nearest color cluster using squared Euclidean distance', 'test_squared_euclidean_distance': 'test the squared_euclidean_distance function that computes pairwise squared distances between two sets of vectors', 'run_ImageGPTImageProcessorPil_preprocess': 'run the _preprocess method on a batch of images to resize, rescale, normalize, and optionally color-quantize them', 'summarize_ImageGPTImageProcessorPil_to_dict': 'summarize the to_dict method that serializes the processor configuration, converting arrays to lists'}
```

## File: huggingface_transformers/src/transformers/models/imagegpt/modeling_imagegpt.py

Prompts

```
['convert a TensorFlow ImageGPT checkpoint to a PyTorch model with specified size and output path', 'load TensorFlow checkpoint weights into an ImageGPT PyTorch model', 'run the ImageGPT TensorFlow to PyTorch conversion CLI with checkpoint path, model size, and output folder', 'build an ImageGPT PyTorch causal language model from a TensorFlow checkpoint', 'save the converted PyTorch ImageGPT model weights and configuration to a folder', 'create an ImageGPTImageProcessor with custom color clusters and preprocessing settings', 'run color quantization to assign each pixel to its nearest color cluster index', 'build squared Euclidean distance computation between pixel values and color clusters', 'review the ImageGPTImageProcessor preprocess method for resizing, normalization, and color quantization', 'summarize the ImageGPTImageProcessor to_dict method for JSON-serializable configuration output', 'create an ImageGPTImageProcessorPil instance with custom color clusters for discrete token modeling', 'build color quantization by assigning each pixel to its nearest color cluster using squared Euclidean distance', 'test the squared_euclidean_distance function that computes pairwise squared distances between two sets of vectors', 'run the _preprocess method on a batch of images to resize, rescale, normalize, and optionally color-quantize them', 'summarize the to_dict method that serializes the processor configuration, converting arrays to lists', 'build an ImageGPTModel transformer with word-piece embeddings and positional embeddings for image token sequences', 'create an ImageGPTForCausalImageModeling model with a language modeling head for unconditional image generation', 'run image classification with ImageGPTForImageClassification by average-pooling hidden states and projecting to label logits', 'test the ImageGPTAttention forward pass with self-attention, cross-attention, layer past caching, and causal masking', 'review the ImageGPTMLP forward pass that applies a feed-forward network with gelu activation and residual dropout']
```

Usage

```
{'build_imagegpt_model': 'build an ImageGPTModel transformer with word-piece embeddings and positional embeddings for image token sequences', 'create_causal_image_modeling': 'create an ImageGPTForCausalImageModeling model with a language modeling head for unconditional image generation', 'run_image_classification': 'run image classification with ImageGPTForImageClassification by average-pooling hidden states and projecting to label logits', 'test_attention_forward': 'test the ImageGPTAttention forward pass with self-attention, cross-attention, layer past caching, and causal masking', 'review_mlp_forward': 'review the ImageGPTMLP forward pass that applies a feed-forward network with gelu activation and residual dropout'}
```

