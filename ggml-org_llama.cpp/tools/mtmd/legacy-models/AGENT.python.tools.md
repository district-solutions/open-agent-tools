# Agent Python Tools

- repo: ggml-org/llama.cpp
- repo_uri: https://github.com/ggml-org/llama.cpp

## File: ggml-org_llama.cpp/tools/mtmd/legacy-models/convert_image_encoder_to_gguf.py

Prompts

```
['convert a Hugging Face CLIP model directory to GGUF format with text and vision encoders', 'convert a CLIP model to GGUF text-only encoder for text encoding tasks', 'convert a CLIP model to GGUF vision-only encoder for image encoding tasks', 'convert a CLIP model with LLaVA projector to GGUF multimodal projector format', 'convert a SigLIP vision model to GGUF format with custom image normalization', 'convert a SigLIP vision model from HuggingFace to GGUF format for use with llama.cpp', 'build a text-only GGUF model by passing --text-only flag to exclude vision encoder tensors', 'build a vision-only GGUF model by passing --vision-only flag to exclude text encoder tensors', 'run the script with --llava-projector to extract and save an image encoder for LLaVA models', 'convert the model using custom image mean and standard deviation values for normalization', 'run the llava_surgery_v2 script to extract LLaVA projector tensors from a model directory into llava.projector', 'clean vision tower tensors from a LLaVA checkpoint and save them to llava.clip file', 'load a PyTorch or safetensors model checkpoint file and return its tensors with file type', 'save a model dictionary to a PyTorch .bin or safetensors .safetensors file', 'find checkpoint paths containing newline and projector tensors from a list of model shards', 'build a GGUF image encoder from MiniCPM-V model weights using the minicpmv-convert-image-encoder-to-gguf script', 'convert a MiniCPM-V vision encoder to GGUF format with vision-only output using the --vision-only flag', 'convert a MiniCPM-V text encoder to GGUF format with text-only output using the --text-only flag', 'extract and convert a MiniCPM-V projector to GGUF mmproj format using the --minicpmv-projector flag', 'convert a SigLIP vision transformer model to GGUF format for use with llama.cpp']
```

Usage

```
{'convert_clip_model_to_gguf': 'convert a Hugging Face CLIP model directory to GGUF format with text and vision encoders', 'convert_text_only_encoder': 'convert a CLIP model to GGUF text-only encoder for text encoding tasks', 'convert_vision_only_encoder': 'convert a CLIP model to GGUF vision-only encoder for image encoding tasks', 'convert_llava_projector_to_gguf': 'convert a CLIP model with LLaVA projector to GGUF multimodal projector format', 'convert_siglip_model_to_gguf': 'convert a SigLIP vision model to GGUF format with custom image normalization'}
```

## File: ggml-org_llama.cpp/tools/mtmd/legacy-models/glmedge-convert-image-encoder-to-gguf.py

Prompts

```
['convert a Hugging Face CLIP model directory to GGUF format with text and vision encoders', 'convert a CLIP model to GGUF text-only encoder for text encoding tasks', 'convert a CLIP model to GGUF vision-only encoder for image encoding tasks', 'convert a CLIP model with LLaVA projector to GGUF multimodal projector format', 'convert a SigLIP vision model to GGUF format with custom image normalization', 'convert a SigLIP vision model from HuggingFace to GGUF format for use with llama.cpp', 'build a text-only GGUF model by passing --text-only flag to exclude vision encoder tensors', 'build a vision-only GGUF model by passing --vision-only flag to exclude text encoder tensors', 'run the script with --llava-projector to extract and save an image encoder for LLaVA models', 'convert the model using custom image mean and standard deviation values for normalization', 'run the llava_surgery_v2 script to extract LLaVA projector tensors from a model directory into llava.projector', 'clean vision tower tensors from a LLaVA checkpoint and save them to llava.clip file', 'load a PyTorch or safetensors model checkpoint file and return its tensors with file type', 'save a model dictionary to a PyTorch .bin or safetensors .safetensors file', 'find checkpoint paths containing newline and projector tensors from a list of model shards', 'build a GGUF image encoder from MiniCPM-V model weights using the minicpmv-convert-image-encoder-to-gguf script', 'convert a MiniCPM-V vision encoder to GGUF format with vision-only output using the --vision-only flag', 'convert a MiniCPM-V text encoder to GGUF format with text-only output using the --text-only flag', 'extract and convert a MiniCPM-V projector to GGUF mmproj format using the --minicpmv-projector flag', 'convert a SigLIP vision transformer model to GGUF format for use with llama.cpp']
```

Usage

```
{'convert_siglip_vision_to_gguf': 'convert a SigLIP vision model from HuggingFace to GGUF format for use with llama.cpp', 'build_text_only_gguf_model': 'build a text-only GGUF model by passing --text-only flag to exclude vision encoder tensors', 'build_vision_only_gguf_model': 'build a vision-only GGUF model by passing --vision-only flag to exclude text encoder tensors', 'run_llava_projector_conversion': 'run the script with --llava-projector to extract and save an image encoder for LLaVA models', 'convert_with_custom_image_normalization': 'convert the model using custom image mean and standard deviation values for normalization'}
```

## File: ggml-org_llama.cpp/tools/mtmd/legacy-models/llava_surgery_v2.py

Prompts

```
['convert a Hugging Face CLIP model directory to GGUF format with text and vision encoders', 'convert a CLIP model to GGUF text-only encoder for text encoding tasks', 'convert a CLIP model to GGUF vision-only encoder for image encoding tasks', 'convert a CLIP model with LLaVA projector to GGUF multimodal projector format', 'convert a SigLIP vision model to GGUF format with custom image normalization', 'convert a SigLIP vision model from HuggingFace to GGUF format for use with llama.cpp', 'build a text-only GGUF model by passing --text-only flag to exclude vision encoder tensors', 'build a vision-only GGUF model by passing --vision-only flag to exclude text encoder tensors', 'run the script with --llava-projector to extract and save an image encoder for LLaVA models', 'convert the model using custom image mean and standard deviation values for normalization', 'run the llava_surgery_v2 script to extract LLaVA projector tensors from a model directory into llava.projector', 'clean vision tower tensors from a LLaVA checkpoint and save them to llava.clip file', 'load a PyTorch or safetensors model checkpoint file and return its tensors with file type', 'save a model dictionary to a PyTorch .bin or safetensors .safetensors file', 'find checkpoint paths containing newline and projector tensors from a list of model shards', 'build a GGUF image encoder from MiniCPM-V model weights using the minicpmv-convert-image-encoder-to-gguf script', 'convert a MiniCPM-V vision encoder to GGUF format with vision-only output using the --vision-only flag', 'convert a MiniCPM-V text encoder to GGUF format with text-only output using the --text-only flag', 'extract and convert a MiniCPM-V projector to GGUF mmproj format using the --minicpmv-projector flag', 'convert a SigLIP vision transformer model to GGUF format for use with llama.cpp']
```

Usage

```
{'run_extract_llava_projector': 'run the llava_surgery_v2 script to extract LLaVA projector tensors from a model directory into llava.projector', 'clean_vision_tower_from_checkpoint': 'clean vision tower tensors from a LLaVA checkpoint and save them to llava.clip file', 'load_model_from_file': 'load a PyTorch or safetensors model checkpoint file and return its tensors with file type', 'save_model_to_file': 'save a model dictionary to a PyTorch .bin or safetensors .safetensors file', 'find_relevant_checkpoints': 'find checkpoint paths containing newline and projector tensors from a list of model shards'}
```

## File: ggml-org_llama.cpp/tools/mtmd/legacy-models/minicpmv-convert-image-encoder-to-gguf.py

Prompts

```
['convert a Hugging Face CLIP model directory to GGUF format with text and vision encoders', 'convert a CLIP model to GGUF text-only encoder for text encoding tasks', 'convert a CLIP model to GGUF vision-only encoder for image encoding tasks', 'convert a CLIP model with LLaVA projector to GGUF multimodal projector format', 'convert a SigLIP vision model to GGUF format with custom image normalization', 'convert a SigLIP vision model from HuggingFace to GGUF format for use with llama.cpp', 'build a text-only GGUF model by passing --text-only flag to exclude vision encoder tensors', 'build a vision-only GGUF model by passing --vision-only flag to exclude text encoder tensors', 'run the script with --llava-projector to extract and save an image encoder for LLaVA models', 'convert the model using custom image mean and standard deviation values for normalization', 'run the llava_surgery_v2 script to extract LLaVA projector tensors from a model directory into llava.projector', 'clean vision tower tensors from a LLaVA checkpoint and save them to llava.clip file', 'load a PyTorch or safetensors model checkpoint file and return its tensors with file type', 'save a model dictionary to a PyTorch .bin or safetensors .safetensors file', 'find checkpoint paths containing newline and projector tensors from a list of model shards', 'build a GGUF image encoder from MiniCPM-V model weights using the minicpmv-convert-image-encoder-to-gguf script', 'convert a MiniCPM-V vision encoder to GGUF format with vision-only output using the --vision-only flag', 'convert a MiniCPM-V text encoder to GGUF format with text-only output using the --text-only flag', 'extract and convert a MiniCPM-V projector to GGUF mmproj format using the --minicpmv-projector flag', 'convert a SigLIP vision transformer model to GGUF format for use with llama.cpp']
```

Usage

```
{'build_minicpmv_gguf': 'build a GGUF image encoder from MiniCPM-V model weights using the minicpmv-convert-image-encoder-to-gguf script', 'convert_vision_only': 'convert a MiniCPM-V vision encoder to GGUF format with vision-only output using the --vision-only flag', 'convert_text_only': 'convert a MiniCPM-V text encoder to GGUF format with text-only output using the --text-only flag', 'extract_minicpmv_projector': 'extract and convert a MiniCPM-V projector to GGUF mmproj format using the --minicpmv-projector flag', 'convert_siglip_vision': 'convert a SigLIP vision transformer model to GGUF format for use with llama.cpp'}
```

