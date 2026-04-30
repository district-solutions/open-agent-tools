# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/kosmos2/convert_kosmos2_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert a Kosmos2 fairseq checkpoint to a PyTorch model using rename_key mappings', 'rename fairseq checkpoint keys to match HuggingFace Kosmos2 model key names', 'load a fairseq Kosmos2 checkpoint into CPU memory for key conversion', 'save the converted Kosmos2 model weights to a PyTorch dump folder', 'run the Kosmos2 checkpoint conversion CLI with checkpoint path and output folder arguments', 'generate text from an image using Kosmos2ForConditionalGeneration with pixel values and input tokens', 'create grounded text output with phrase and object tags using Kosmos2ForConditionalGeneration post_process_generation', 'build a KOSMOS-2 vision-language model with Kosmos2Model combining vision encoder and text decoder', 'run image feature extraction with Kosmos2Model get_image_features using pixel values and positional encoding', 'test the Kosmos2TextForCausalLM forward pass with input ids, labels, and image embeddings for next-token prediction', 'create a Kosmos2Processor instance with an image processor, tokenizer, and optional patch index token count', 'call the Kosmos2Processor to encode images and text with optional bounding boxes and image token count', 'run preprocess_examples to insert image placeholders and bounding box patch index tokens into text', 'run post_process_generation to extract clean text and entities with bounding box coordinates from model output', 'run post_process_image_text_to_text to batch-decode model generate outputs and extract grounded text entities']
```

Usage

```
{'convert_kosmos2_checkpoint': 'convert a Kosmos2 fairseq checkpoint to a PyTorch model using rename_key mappings', 'rename_checkpoint_keys': 'rename fairseq checkpoint keys to match HuggingFace Kosmos2 model key names', 'load_fairseq_checkpoint': 'load a fairseq Kosmos2 checkpoint into CPU memory for key conversion', 'save_converted_model': 'save the converted Kosmos2 model weights to a PyTorch dump folder', 'run_checkpoint_conversion_cli': 'run the Kosmos2 checkpoint conversion CLI with checkpoint path and output folder arguments'}
```

## File: huggingface_transformers/src/transformers/models/kosmos2/modeling_kosmos2.py

Prompts

```
['convert a Kosmos2 fairseq checkpoint to a PyTorch model using rename_key mappings', 'rename fairseq checkpoint keys to match HuggingFace Kosmos2 model key names', 'load a fairseq Kosmos2 checkpoint into CPU memory for key conversion', 'save the converted Kosmos2 model weights to a PyTorch dump folder', 'run the Kosmos2 checkpoint conversion CLI with checkpoint path and output folder arguments', 'generate text from an image using Kosmos2ForConditionalGeneration with pixel values and input tokens', 'create grounded text output with phrase and object tags using Kosmos2ForConditionalGeneration post_process_generation', 'build a KOSMOS-2 vision-language model with Kosmos2Model combining vision encoder and text decoder', 'run image feature extraction with Kosmos2Model get_image_features using pixel values and positional encoding', 'test the Kosmos2TextForCausalLM forward pass with input ids, labels, and image embeddings for next-token prediction', 'create a Kosmos2Processor instance with an image processor, tokenizer, and optional patch index token count', 'call the Kosmos2Processor to encode images and text with optional bounding boxes and image token count', 'run preprocess_examples to insert image placeholders and bounding box patch index tokens into text', 'run post_process_generation to extract clean text and entities with bounding box coordinates from model output', 'run post_process_image_text_to_text to batch-decode model generate outputs and extract grounded text entities']
```

Usage

```
{'generate_text_from_image': 'generate text from an image using Kosmos2ForConditionalGeneration with pixel values and input tokens', 'create_grounding_output': 'create grounded text output with phrase and object tags using Kosmos2ForConditionalGeneration post_process_generation', 'build_vision_language_model': 'build a KOSMOS-2 vision-language model with Kosmos2Model combining vision encoder and text decoder', 'run_image_feature_extraction': 'run image feature extraction with Kosmos2Model get_image_features using pixel values and positional encoding', 'test_causal_language_model': 'test the Kosmos2TextForCausalLM forward pass with input ids, labels, and image embeddings for next-token prediction'}
```

## File: huggingface_transformers/src/transformers/models/kosmos2/processing_kosmos2.py

Prompts

```
['convert a Kosmos2 fairseq checkpoint to a PyTorch model using rename_key mappings', 'rename fairseq checkpoint keys to match HuggingFace Kosmos2 model key names', 'load a fairseq Kosmos2 checkpoint into CPU memory for key conversion', 'save the converted Kosmos2 model weights to a PyTorch dump folder', 'run the Kosmos2 checkpoint conversion CLI with checkpoint path and output folder arguments', 'generate text from an image using Kosmos2ForConditionalGeneration with pixel values and input tokens', 'create grounded text output with phrase and object tags using Kosmos2ForConditionalGeneration post_process_generation', 'build a KOSMOS-2 vision-language model with Kosmos2Model combining vision encoder and text decoder', 'run image feature extraction with Kosmos2Model get_image_features using pixel values and positional encoding', 'test the Kosmos2TextForCausalLM forward pass with input ids, labels, and image embeddings for next-token prediction', 'create a Kosmos2Processor instance with an image processor, tokenizer, and optional patch index token count', 'call the Kosmos2Processor to encode images and text with optional bounding boxes and image token count', 'run preprocess_examples to insert image placeholders and bounding box patch index tokens into text', 'run post_process_generation to extract clean text and entities with bounding box coordinates from model output', 'run post_process_image_text_to_text to batch-decode model generate outputs and extract grounded text entities']
```

Usage

```
{'create_Kosmos2Processor': 'create a Kosmos2Processor instance with an image processor, tokenizer, and optional patch index token count', 'call_Kosmos2Processor': 'call the Kosmos2Processor to encode images and text with optional bounding boxes and image token count', 'run_preprocess_examples': 'run preprocess_examples to insert image placeholders and bounding box patch index tokens into text', 'run_post_process_generation': 'run post_process_generation to extract clean text and entities with bounding box coordinates from model output', 'run_post_process_image_text_to_text': 'run post_process_image_text_to_text to batch-decode model generate outputs and extract grounded text entities'}
```

