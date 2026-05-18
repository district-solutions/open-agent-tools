# Agent Python Tools

- repo: facebookresearch/metamorph
- repo_uri: https://github.com/facebookresearch/metamorph

## File: facebookresearch_metamorph/inference/adapter.py

Prompts

```
['build a SimplifiedSigLIPProjector in MLP mode to project visual features to a target embedding dimension', 'build a SimplifiedSigLIPProjector in xattn mode using cross-attention blocks to project visual features', 'build a SimplifiedSigLIPProjector in xattnffn mode with cross-attention and feed-forward network blocks', 'create a CrossAttentionBlock with multihead attention and optional feed-forward network for token transformation', 'run the forward pass of a SimplifiedSigLIPProjector on a batch of input feature tensors', 'run the MetaMorph model inference on an image or video with a custom prompt', 'run the MetaMorph model with --chat-with-vision to generate visualizations from image embeddings', 'run the demo to extract frames from a video file at a specified FPS rate', 'run the MetaMorph model to chat with an image and get a text response', 'run the visualization pipeline to generate images at multiple guidance scales from model embeddings', 'load the MetaMorph model from a given path and return the tokenizer, model, image processor, and context length', 'review the load_metamorph_model function to understand how it handles CUDA fallback and dtype selection', 'refactor the load_metamorph_model function to support additional device types beyond cuda and cpu', 'test the load_metamorph_model function by loading a model and verifying the returned tokenizer and model objects', 'load the Stable Diffusion pipeline and projector model from a HuggingFace repo for visualization', 'download the UNet, adapter, and config checkpoints from a HuggingFace repository to a local directory', 'load the SimplifiedSigLIPProjector model from a checkpoint file and config JSON onto the specified device', 'run the load_visualization function to initialize the Stable Diffusion pipeline with a fine-tuned UNet and projector', 'review the load_visualization function to understand how it downloads checkpoints and loads the Stable Diffusion pipeline']
```

Usage

```
{'build_mlp_projector': 'build a SimplifiedSigLIPProjector in MLP mode to project visual features to a target embedding dimension', 'build_xattn_projector': 'build a SimplifiedSigLIPProjector in xattn mode using cross-attention blocks to project visual features', 'build_xattnffn_projector': 'build a SimplifiedSigLIPProjector in xattnffn mode with cross-attention and feed-forward network blocks', 'create_cross_attention_block': 'create a CrossAttentionBlock with multihead attention and optional feed-forward network for token transformation', 'run_projector_forward': 'run the forward pass of a SimplifiedSigLIPProjector on a batch of input feature tensors'}
```

## File: facebookresearch_metamorph/inference/demo.py

Prompts

```
['build a SimplifiedSigLIPProjector in MLP mode to project visual features to a target embedding dimension', 'build a SimplifiedSigLIPProjector in xattn mode using cross-attention blocks to project visual features', 'build a SimplifiedSigLIPProjector in xattnffn mode with cross-attention and feed-forward network blocks', 'create a CrossAttentionBlock with multihead attention and optional feed-forward network for token transformation', 'run the forward pass of a SimplifiedSigLIPProjector on a batch of input feature tensors', 'run the MetaMorph model inference on an image or video with a custom prompt', 'run the MetaMorph model with --chat-with-vision to generate visualizations from image embeddings', 'run the demo to extract frames from a video file at a specified FPS rate', 'run the MetaMorph model to chat with an image and get a text response', 'run the visualization pipeline to generate images at multiple guidance scales from model embeddings', 'load the MetaMorph model from a given path and return the tokenizer, model, image processor, and context length', 'review the load_metamorph_model function to understand how it handles CUDA fallback and dtype selection', 'refactor the load_metamorph_model function to support additional device types beyond cuda and cpu', 'test the load_metamorph_model function by loading a model and verifying the returned tokenizer and model objects', 'load the Stable Diffusion pipeline and projector model from a HuggingFace repo for visualization', 'download the UNet, adapter, and config checkpoints from a HuggingFace repository to a local directory', 'load the SimplifiedSigLIPProjector model from a checkpoint file and config JSON onto the specified device', 'run the load_visualization function to initialize the Stable Diffusion pipeline with a fine-tuned UNet and projector', 'review the load_visualization function to understand how it downloads checkpoints and loads the Stable Diffusion pipeline']
```

Usage

```
{'run_metamorph_inference': 'run the MetaMorph model inference on an image or video with a custom prompt', 'run_visualization_generation': 'run the MetaMorph model with --chat-with-vision to generate visualizations from image embeddings', 'run_video_frame_extraction': 'run the demo to extract frames from a video file at a specified FPS rate', 'run_image_chat': 'run the MetaMorph model to chat with an image and get a text response', 'run_guided_image_synthesis': 'run the visualization pipeline to generate images at multiple guidance scales from model embeddings'}
```

## File: facebookresearch_metamorph/inference/load_metamorph.py

Prompts

```
['build a SimplifiedSigLIPProjector in MLP mode to project visual features to a target embedding dimension', 'build a SimplifiedSigLIPProjector in xattn mode using cross-attention blocks to project visual features', 'build a SimplifiedSigLIPProjector in xattnffn mode with cross-attention and feed-forward network blocks', 'create a CrossAttentionBlock with multihead attention and optional feed-forward network for token transformation', 'run the forward pass of a SimplifiedSigLIPProjector on a batch of input feature tensors', 'run the MetaMorph model inference on an image or video with a custom prompt', 'run the MetaMorph model with --chat-with-vision to generate visualizations from image embeddings', 'run the demo to extract frames from a video file at a specified FPS rate', 'run the MetaMorph model to chat with an image and get a text response', 'run the visualization pipeline to generate images at multiple guidance scales from model embeddings', 'load the MetaMorph model from a given path and return the tokenizer, model, image processor, and context length', 'review the load_metamorph_model function to understand how it handles CUDA fallback and dtype selection', 'refactor the load_metamorph_model function to support additional device types beyond cuda and cpu', 'test the load_metamorph_model function by loading a model and verifying the returned tokenizer and model objects', 'load the Stable Diffusion pipeline and projector model from a HuggingFace repo for visualization', 'download the UNet, adapter, and config checkpoints from a HuggingFace repository to a local directory', 'load the SimplifiedSigLIPProjector model from a checkpoint file and config JSON onto the specified device', 'run the load_visualization function to initialize the Stable Diffusion pipeline with a fine-tuned UNet and projector', 'review the load_visualization function to understand how it downloads checkpoints and loads the Stable Diffusion pipeline']
```

Usage

```
{'load_metamorph_model': 'load the MetaMorph model from a given path and return the tokenizer, model, image processor, and context length', 'run_metamorph_inference': 'run the load_metamorph script to load a MetaMorph model and print model info including context length and device', 'review_load_metamorph_model': 'review the load_metamorph_model function to understand how it handles CUDA fallback and dtype selection', 'refactor_load_metamorph_model': 'refactor the load_metamorph_model function to support additional device types beyond cuda and cpu', 'test_load_metamorph_model': 'test the load_metamorph_model function by loading a model and verifying the returned tokenizer and model objects'}
```

## File: facebookresearch_metamorph/inference/load_visualization.py

Prompts

```
['build a SimplifiedSigLIPProjector in MLP mode to project visual features to a target embedding dimension', 'build a SimplifiedSigLIPProjector in xattn mode using cross-attention blocks to project visual features', 'build a SimplifiedSigLIPProjector in xattnffn mode with cross-attention and feed-forward network blocks', 'create a CrossAttentionBlock with multihead attention and optional feed-forward network for token transformation', 'run the forward pass of a SimplifiedSigLIPProjector on a batch of input feature tensors', 'run the MetaMorph model inference on an image or video with a custom prompt', 'run the MetaMorph model with --chat-with-vision to generate visualizations from image embeddings', 'run the demo to extract frames from a video file at a specified FPS rate', 'run the MetaMorph model to chat with an image and get a text response', 'run the visualization pipeline to generate images at multiple guidance scales from model embeddings', 'load the MetaMorph model from a given path and return the tokenizer, model, image processor, and context length', 'review the load_metamorph_model function to understand how it handles CUDA fallback and dtype selection', 'refactor the load_metamorph_model function to support additional device types beyond cuda and cpu', 'test the load_metamorph_model function by loading a model and verifying the returned tokenizer and model objects', 'load the Stable Diffusion pipeline and projector model from a HuggingFace repo for visualization', 'download the UNet, adapter, and config checkpoints from a HuggingFace repository to a local directory', 'load the SimplifiedSigLIPProjector model from a checkpoint file and config JSON onto the specified device', 'run the load_visualization function to initialize the Stable Diffusion pipeline with a fine-tuned UNet and projector', 'review the load_visualization function to understand how it downloads checkpoints and loads the Stable Diffusion pipeline']
```

Usage

```
{'load_visualization_models': 'load the Stable Diffusion pipeline and projector model from a HuggingFace repo for visualization', 'download_checkpoints_from_hf': 'download the UNet, adapter, and config checkpoints from a HuggingFace repository to a local directory', 'load_projector_model': 'load the SimplifiedSigLIPProjector model from a checkpoint file and config JSON onto the specified device', 'run_visualization_pipeline': 'run the load_visualization function to initialize the Stable Diffusion pipeline with a fine-tuned UNet and projector', 'review_load_visualization': 'review the load_visualization function to understand how it downloads checkpoints and loads the Stable Diffusion pipeline'}
```

