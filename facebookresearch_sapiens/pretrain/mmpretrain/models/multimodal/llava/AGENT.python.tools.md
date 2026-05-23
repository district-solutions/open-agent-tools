# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/multimodal/llava/llava.py

Prompts

```
['build a LLaVA multimodal model with vision encoder and language encoder for image captioning', 'predict image captions using the LLaVA model with a batch of input images', 'predict visual question answering answers using the LLaVA model on input images', 'preprocess text prompts by tokenizing and padding them for the LLaVA language model', 'post process generated token outputs by decoding and assigning predictions to data samples', 'run a forward pass through LlavaLlamaForCausalLM with input_ids and images to get language model outputs', 'review the forward_vision_tower method that processes image features and merges them with text embeddings', 'test the prepare_inputs_for_generation method to handle past key values and image inputs during generation', 'summarize the _reorder_cache static method that reorders past key values for beam search decoding']
```

Usage

```
{'build_llava_model': 'build a LLaVA multimodal model with vision encoder and language encoder for image captioning', 'predict_llava_caption': 'predict image captions using the LLaVA model with a batch of input images', 'predict_llava_vqa': 'predict visual question answering answers using the LLaVA model on input images', 'preprocess_text_llava': 'preprocess text prompts by tokenizing and padding them for the LLaVA language model', 'post_process_llava': 'post process generated token outputs by decoding and assigning predictions to data samples'}
```

## File: facebookresearch_sapiens/pretrain/mmpretrain/models/multimodal/llava/modules.py

Prompts

```
['build a LLaVA multimodal model with vision encoder and language encoder for image captioning', 'predict image captions using the LLaVA model with a batch of input images', 'predict visual question answering answers using the LLaVA model on input images', 'preprocess text prompts by tokenizing and padding them for the LLaVA language model', 'post process generated token outputs by decoding and assigning predictions to data samples', 'run a forward pass through LlavaLlamaForCausalLM with input_ids and images to get language model outputs', 'review the forward_vision_tower method that processes image features and merges them with text embeddings', 'test the prepare_inputs_for_generation method to handle past key values and image inputs during generation', 'summarize the _reorder_cache static method that reorders past key values for beam search decoding']
```

Usage

```
{'build_llava_model': 'build a LlavaLlamaForCausalLM model with vision encoder and language encoder for multimodal causal language modeling', 'run_forward_pass': 'run a forward pass through LlavaLlamaForCausalLM with input_ids and images to get language model outputs', 'review_forward_vision_tower': 'review the forward_vision_tower method that processes image features and merges them with text embeddings', 'test_prepare_inputs_for_generation': 'test the prepare_inputs_for_generation method to handle past key values and image inputs during generation', 'summarize_reorder_cache': 'summarize the _reorder_cache static method that reorders past key values for beam search decoding'}
```

