# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/trocr/convert_trocr_unilm_to_pytorch.py

Prompts

```
['convert a TrOCR checkpoint from the unilm repository to a HuggingFace VisionEncoderDecoderModel', 'create a list of weight key renaming mappings from DEIT encoder to HuggingFace ViT encoder structure', 'split a combined qkv weight matrix into separate query, key, and value weight tensors for each encoder layer', 'download and prepare a test image from the IAM Handwriting Database or SROIE dataset for checkpoint verification', 'run the CLI script with --checkpoint_url and --pytorch_dump_folder_path to convert and save a TrOCR model', 'create a TrOCR decoder model for optical character recognition using TrOCRDecoder with learned positional embeddings', 'build a TrOCRForCausalLM model with a language modeling head for text generation', 'run TrOCR inference to generate text from image pixel values using VisionEncoderDecoderModel', 'test TrOCR training with labels using cross-entropy loss on decoder outputs', 'summarize the TrOCRAttention multi-headed attention mechanism with cross-attention support', 'create a TrOCRProcessor with an image processor and tokenizer for optical character recognition', 'call the TrOCRProcessor with images to produce image-encoded model inputs', 'call the TrOCRProcessor with text to tokenize and produce encoded text inputs', 'call the TrOCRProcessor with both images and text to produce model inputs with labels for training', 'get the model input names from the TrOCRProcessor including image inputs and labels']
```

Usage

```
{'convert_tr_ocr_checkpoint': 'convert a TrOCR checkpoint from the unilm repository to a HuggingFace VisionEncoderDecoderModel', 'create_rename_keys': 'create a list of weight key renaming mappings from DEIT encoder to HuggingFace ViT encoder structure', 'read_in_q_k_v': 'split a combined qkv weight matrix into separate query, key, and value weight tensors for each encoder layer', 'prepare_img': 'download and prepare a test image from the IAM Handwriting Database or SROIE dataset for checkpoint verification', 'run_convert_script': 'run the CLI script with --checkpoint_url and --pytorch_dump_folder_path to convert and save a TrOCR model'}
```

## File: huggingface_transformers/src/transformers/models/trocr/modeling_trocr.py

Prompts

```
['convert a TrOCR checkpoint from the unilm repository to a HuggingFace VisionEncoderDecoderModel', 'create a list of weight key renaming mappings from DEIT encoder to HuggingFace ViT encoder structure', 'split a combined qkv weight matrix into separate query, key, and value weight tensors for each encoder layer', 'download and prepare a test image from the IAM Handwriting Database or SROIE dataset for checkpoint verification', 'run the CLI script with --checkpoint_url and --pytorch_dump_folder_path to convert and save a TrOCR model', 'create a TrOCR decoder model for optical character recognition using TrOCRDecoder with learned positional embeddings', 'build a TrOCRForCausalLM model with a language modeling head for text generation', 'run TrOCR inference to generate text from image pixel values using VisionEncoderDecoderModel', 'test TrOCR training with labels using cross-entropy loss on decoder outputs', 'summarize the TrOCRAttention multi-headed attention mechanism with cross-attention support', 'create a TrOCRProcessor with an image processor and tokenizer for optical character recognition', 'call the TrOCRProcessor with images to produce image-encoded model inputs', 'call the TrOCRProcessor with text to tokenize and produce encoded text inputs', 'call the TrOCRProcessor with both images and text to produce model inputs with labels for training', 'get the model input names from the TrOCRProcessor including image inputs and labels']
```

Usage

```
{'create_trOCR_decoder': 'create a TrOCR decoder model for optical character recognition using TrOCRDecoder with learned positional embeddings', 'build_trOCR_causal_lm': 'build a TrOCRForCausalLM model with a language modeling head for text generation', 'run_trOCR_inference': 'run TrOCR inference to generate text from image pixel values using VisionEncoderDecoderModel', 'test_trOCR_training': 'test TrOCR training with labels using cross-entropy loss on decoder outputs', 'summarize_trOCR_attention': 'summarize the TrOCRAttention multi-headed attention mechanism with cross-attention support'}
```

## File: huggingface_transformers/src/transformers/models/trocr/processing_trocr.py

Prompts

```
['convert a TrOCR checkpoint from the unilm repository to a HuggingFace VisionEncoderDecoderModel', 'create a list of weight key renaming mappings from DEIT encoder to HuggingFace ViT encoder structure', 'split a combined qkv weight matrix into separate query, key, and value weight tensors for each encoder layer', 'download and prepare a test image from the IAM Handwriting Database or SROIE dataset for checkpoint verification', 'run the CLI script with --checkpoint_url and --pytorch_dump_folder_path to convert and save a TrOCR model', 'create a TrOCR decoder model for optical character recognition using TrOCRDecoder with learned positional embeddings', 'build a TrOCRForCausalLM model with a language modeling head for text generation', 'run TrOCR inference to generate text from image pixel values using VisionEncoderDecoderModel', 'test TrOCR training with labels using cross-entropy loss on decoder outputs', 'summarize the TrOCRAttention multi-headed attention mechanism with cross-attention support', 'create a TrOCRProcessor with an image processor and tokenizer for optical character recognition', 'call the TrOCRProcessor with images to produce image-encoded model inputs', 'call the TrOCRProcessor with text to tokenize and produce encoded text inputs', 'call the TrOCRProcessor with both images and text to produce model inputs with labels for training', 'get the model input names from the TrOCRProcessor including image inputs and labels']
```

Usage

```
{'create_TrocrProcessor': 'create a TrOCRProcessor with an image processor and tokenizer for optical character recognition', 'call_TrocrProcessor_images': 'call the TrOCRProcessor with images to produce image-encoded model inputs', 'call_TrocrProcessor_text': 'call the TrOCRProcessor with text to tokenize and produce encoded text inputs', 'call_TrocrProcessor_images_text': 'call the TrOCRProcessor with both images and text to produce model inputs with labels for training', 'get_TrocrProcessor_model_input_names': 'get the model input names from the TrOCRProcessor including image inputs and labels'}
```

