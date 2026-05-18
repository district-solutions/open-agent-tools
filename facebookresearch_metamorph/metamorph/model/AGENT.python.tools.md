# Agent Python Tools

- repo: facebookresearch/metamorph
- repo_uri: https://github.com/facebookresearch/metamorph

## File: facebookresearch_metamorph/metamorph/model/builder.py

Prompts

```
['load a pretrained MetaMorph multimodal model with vision tower and image processor from a model path', 'load a MetaMorph model with LoRA weights merged from a base model and non-LoRA trainables', 'load a MetaMorph model from a base model with additional mm projector weights', 'load a pretrained model with 8-bit or 4-bit quantization using BitsAndBytesConfig for memory efficiency', 'load a standard language model or PEFT model with optional flash attention support', 'run the python module to consolidate a model checkpoint from source to destination path', 'build a python CLI tool that consolidates a HuggingFace model and tokenizer checkpoint to a new path', 'create a function that loads a pretrained model and tokenizer then saves them to a new directory', 'test the python module consolidate_ckpt by passing source and destination checkpoint paths', 'review the python module consolidate_ckpt to understand how it upgrades and saves model checkpoints', 'build a vision tower module using MetaMorphMetaModel with a given config and delay loading', 'encode image tensors into feature embeddings using MetaMorphMetaForCausalLM encode_images method', 'prepare multimodal input embeddings and labels for training using prepare_inputs_labels_for_multimodal', 'unpad a PyTorch image tensor to its original aspect ratio using unpad_image function', 'initialize vision tokenizer with image patch and start end tokens using initialize_vision_tokenizer']
```

Usage

```
{'load_metamorph_model': 'load a pretrained MetaMorph multimodal model with vision tower and image processor from a model path', 'load_metamorph_lora_model': 'load a MetaMorph model with LoRA weights merged from a base model and non-LoRA trainables', 'load_metamorph_projector': 'load a MetaMorph model from a base model with additional mm projector weights', 'load_quantized_model': 'load a pretrained model with 8-bit or 4-bit quantization using BitsAndBytesConfig for memory efficiency', 'load_language_model': 'load a standard language model or PEFT model with optional flash attention support'}
```

## File: facebookresearch_metamorph/metamorph/model/consolidate.py

Prompts

```
['load a pretrained MetaMorph multimodal model with vision tower and image processor from a model path', 'load a MetaMorph model with LoRA weights merged from a base model and non-LoRA trainables', 'load a MetaMorph model from a base model with additional mm projector weights', 'load a pretrained model with 8-bit or 4-bit quantization using BitsAndBytesConfig for memory efficiency', 'load a standard language model or PEFT model with optional flash attention support', 'run the python module to consolidate a model checkpoint from source to destination path', 'build a python CLI tool that consolidates a HuggingFace model and tokenizer checkpoint to a new path', 'create a function that loads a pretrained model and tokenizer then saves them to a new directory', 'test the python module consolidate_ckpt by passing source and destination checkpoint paths', 'review the python module consolidate_ckpt to understand how it upgrades and saves model checkpoints', 'build a vision tower module using MetaMorphMetaModel with a given config and delay loading', 'encode image tensors into feature embeddings using MetaMorphMetaForCausalLM encode_images method', 'prepare multimodal input embeddings and labels for training using prepare_inputs_labels_for_multimodal', 'unpad a PyTorch image tensor to its original aspect ratio using unpad_image function', 'initialize vision tokenizer with image patch and start end tokens using initialize_vision_tokenizer']
```

Usage

```
{'run_consolidate_ckpt': 'run the python module to consolidate a model checkpoint from source to destination path', 'build_consolidate_ckpt_cli': 'build a python CLI tool that consolidates a HuggingFace model and tokenizer checkpoint to a new path', 'create_consolidate_ckpt_function': 'create a function that loads a pretrained model and tokenizer then saves them to a new directory', 'test_consolidate_ckpt': 'test the python module consolidate_ckpt by passing source and destination checkpoint paths', 'review_consolidate_ckpt': 'review the python module consolidate_ckpt to understand how it upgrades and saves model checkpoints'}
```

## File: facebookresearch_metamorph/metamorph/model/metamorph_arch.py

Prompts

```
['load a pretrained MetaMorph multimodal model with vision tower and image processor from a model path', 'load a MetaMorph model with LoRA weights merged from a base model and non-LoRA trainables', 'load a MetaMorph model from a base model with additional mm projector weights', 'load a pretrained model with 8-bit or 4-bit quantization using BitsAndBytesConfig for memory efficiency', 'load a standard language model or PEFT model with optional flash attention support', 'run the python module to consolidate a model checkpoint from source to destination path', 'build a python CLI tool that consolidates a HuggingFace model and tokenizer checkpoint to a new path', 'create a function that loads a pretrained model and tokenizer then saves them to a new directory', 'test the python module consolidate_ckpt by passing source and destination checkpoint paths', 'review the python module consolidate_ckpt to understand how it upgrades and saves model checkpoints', 'build a vision tower module using MetaMorphMetaModel with a given config and delay loading', 'encode image tensors into feature embeddings using MetaMorphMetaForCausalLM encode_images method', 'prepare multimodal input embeddings and labels for training using prepare_inputs_labels_for_multimodal', 'unpad a PyTorch image tensor to its original aspect ratio using unpad_image function', 'initialize vision tokenizer with image patch and start end tokens using initialize_vision_tokenizer']
```

Usage

```
{'build_vision_tower': 'build a vision tower module using MetaMorphMetaModel with a given config and delay loading', 'encode_images': 'encode image tensors into feature embeddings using MetaMorphMetaForCausalLM encode_images method', 'prepare_multimodal_inputs': 'prepare multimodal input embeddings and labels for training using prepare_inputs_labels_for_multimodal', 'unpad_image': 'unpad a PyTorch image tensor to its original aspect ratio using unpad_image function', 'initialize_vision_tokenizer': 'initialize vision tokenizer with image patch and start end tokens using initialize_vision_tokenizer'}
```

