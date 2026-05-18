# Agent Python Tools

- repo: facebookresearch/metamorph
- repo_uri: https://github.com/facebookresearch/metamorph

## File: facebookresearch_metamorph/metamorph/train/llama_flash_attn_monkey_patch.py

Prompts

```
['replace Llama attention with Flash Attention by monkey-patching LlamaAttention.forward and LlamaModel._prepare_decoder_attention_mask', 'compute Flash Attention forward pass for LlamaAttention using qkv-packed format with causal masking and rotary embeddings', 'return the attention mask as-is without transformation for Flash Attention compatibility in LlamaModel', 'review the forward function that handles padded and unpadded Flash Attention paths with key padding mask support', 'test the monkey-patch function that replaces Llama attention with Flash Attention and checks CUDA capability', 'create a LengthGroupedSampler to group dataset indices by similar feature lengths for efficient batching', 'build a MetaMorphTrainer with separate learning rates for vision tower and projector parameters', 'run get_length_grouped_indices to generate batch indices sorted by sequence length for distributed training', 'test split_to_even_chunks to divide indices into evenly sized chunks by total length', 'review MetaMorphTrainer _save_checkpoint to save only mm_projector and vision_resampler adapter weights', 'run the MetaMorph multimodal model training pipeline with vision tower and LoRA support', 'create a lazy-loading supervised dataset that processes images, videos, and visual reasoning data on demand', 'create a data collator that pads and batches input IDs, labels, and images for supervised fine-tuning', 'run multimodal preprocessing to replace image tokens with start/end token wrappers in conversation sources', 'run conversation preprocessing with llama2, llama3, v1, or plain separator styles and mask human targets']
```

Usage

```
{'replace_llama_attn_with_flash_attn': 'replace Llama attention with Flash Attention by monkey-patching LlamaAttention.forward and LlamaModel._prepare_decoder_attention_mask', 'forward_flash_attention': 'compute Flash Attention forward pass for LlamaAttention using qkv-packed format with causal masking and rotary embeddings', 'prepare_decoder_attention_mask': 'return the attention mask as-is without transformation for Flash Attention compatibility in LlamaModel', 'review_forward_flash_attn': 'review the forward function that handles padded and unpadded Flash Attention paths with key padding mask support', 'test_replace_llama_attn': 'test the monkey-patch function that replaces Llama attention with Flash Attention and checks CUDA capability'}
```

## File: facebookresearch_metamorph/metamorph/train/metamorph_trainer.py

Prompts

```
['replace Llama attention with Flash Attention by monkey-patching LlamaAttention.forward and LlamaModel._prepare_decoder_attention_mask', 'compute Flash Attention forward pass for LlamaAttention using qkv-packed format with causal masking and rotary embeddings', 'return the attention mask as-is without transformation for Flash Attention compatibility in LlamaModel', 'review the forward function that handles padded and unpadded Flash Attention paths with key padding mask support', 'test the monkey-patch function that replaces Llama attention with Flash Attention and checks CUDA capability', 'create a LengthGroupedSampler to group dataset indices by similar feature lengths for efficient batching', 'build a MetaMorphTrainer with separate learning rates for vision tower and projector parameters', 'run get_length_grouped_indices to generate batch indices sorted by sequence length for distributed training', 'test split_to_even_chunks to divide indices into evenly sized chunks by total length', 'review MetaMorphTrainer _save_checkpoint to save only mm_projector and vision_resampler adapter weights', 'run the MetaMorph multimodal model training pipeline with vision tower and LoRA support', 'create a lazy-loading supervised dataset that processes images, videos, and visual reasoning data on demand', 'create a data collator that pads and batches input IDs, labels, and images for supervised fine-tuning', 'run multimodal preprocessing to replace image tokens with start/end token wrappers in conversation sources', 'run conversation preprocessing with llama2, llama3, v1, or plain separator styles and mask human targets']
```

Usage

```
{'create_LengthGroupedSampler': 'create a LengthGroupedSampler to group dataset indices by similar feature lengths for efficient batching', 'build_MetaMorphTrainer_optimizer': 'build a MetaMorphTrainer with separate learning rates for vision tower and projector parameters', 'run_get_length_grouped_indices': 'run get_length_grouped_indices to generate batch indices sorted by sequence length for distributed training', 'test_split_to_even_chunks': 'test split_to_even_chunks to divide indices into evenly sized chunks by total length', 'review_MetaMorphTrainer_save_checkpoint': 'review MetaMorphTrainer _save_checkpoint to save only mm_projector and vision_resampler adapter weights'}
```

## File: facebookresearch_metamorph/metamorph/train/train.py

Prompts

```
['replace Llama attention with Flash Attention by monkey-patching LlamaAttention.forward and LlamaModel._prepare_decoder_attention_mask', 'compute Flash Attention forward pass for LlamaAttention using qkv-packed format with causal masking and rotary embeddings', 'return the attention mask as-is without transformation for Flash Attention compatibility in LlamaModel', 'review the forward function that handles padded and unpadded Flash Attention paths with key padding mask support', 'test the monkey-patch function that replaces Llama attention with Flash Attention and checks CUDA capability', 'create a LengthGroupedSampler to group dataset indices by similar feature lengths for efficient batching', 'build a MetaMorphTrainer with separate learning rates for vision tower and projector parameters', 'run get_length_grouped_indices to generate batch indices sorted by sequence length for distributed training', 'test split_to_even_chunks to divide indices into evenly sized chunks by total length', 'review MetaMorphTrainer _save_checkpoint to save only mm_projector and vision_resampler adapter weights', 'run the MetaMorph multimodal model training pipeline with vision tower and LoRA support', 'create a lazy-loading supervised dataset that processes images, videos, and visual reasoning data on demand', 'create a data collator that pads and batches input IDs, labels, and images for supervised fine-tuning', 'run multimodal preprocessing to replace image tokens with start/end token wrappers in conversation sources', 'run conversation preprocessing with llama2, llama3, v1, or plain separator styles and mask human targets']
```

Usage

```
{'run_train': 'run the MetaMorph multimodal model training pipeline with vision tower and LoRA support', 'create_LazySupervisedDataset': 'create a lazy-loading supervised dataset that processes images, videos, and visual reasoning data on demand', 'create_DataCollatorForSupervisedDataset': 'create a data collator that pads and batches input IDs, labels, and images for supervised fine-tuning', 'run_preprocess_multimodal': 'run multimodal preprocessing to replace image tokens with start/end token wrappers in conversation sources', 'run_preprocess': 'run conversation preprocessing with llama2, llama3, v1, or plain separator styles and mask human targets'}
```

