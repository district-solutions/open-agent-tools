# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/opt/convert_opt_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert a fairseq OPT checkpoint to a HuggingFace PyTorch model saved to an output folder', 'load and transform a fairseq OPT checkpoint state dict into HuggingFace-compatible weight keys', 'run the CLI script to convert a fairseq OPT model.pt checkpoint to a HuggingFace OPTModel', 'split combined QKV projection weights into separate q_proj, k_proj, and v_proj tensors', 'rename legacy checkpoint keys to match HuggingFace OPTModel naming conventions', 'create an OPTForCausalLM model and generate text from a tokenizer prompt', 'build an OPTModel forward pass with input_ids and attention_mask to get hidden states', 'test OPTForSequenceClassification on a batch of text inputs with classification labels', 'review OPTForQuestionAnswering to extract start and end logits from a question and context', 'summarize the OPTDecoderLayer forward pass with self-attention and feed-forward layers']
```

Usage

```
{'convert_opt_checkpoint': 'convert a fairseq OPT checkpoint to a HuggingFace PyTorch model saved to an output folder', 'load_checkpoint': 'load and transform a fairseq OPT checkpoint state dict into HuggingFace-compatible weight keys', 'run_convert_cli': 'run the CLI script to convert a fairseq OPT model.pt checkpoint to a HuggingFace OPTModel', 'split_qkv_weights': 'split combined QKV projection weights into separate q_proj, k_proj, and v_proj tensors', 'rename_checkpoint_keys': 'rename legacy checkpoint keys to match HuggingFace OPTModel naming conventions'}
```

## File: huggingface_transformers/src/transformers/models/opt/modeling_opt.py

Prompts

```
['convert a fairseq OPT checkpoint to a HuggingFace PyTorch model saved to an output folder', 'load and transform a fairseq OPT checkpoint state dict into HuggingFace-compatible weight keys', 'run the CLI script to convert a fairseq OPT model.pt checkpoint to a HuggingFace OPTModel', 'split combined QKV projection weights into separate q_proj, k_proj, and v_proj tensors', 'rename legacy checkpoint keys to match HuggingFace OPTModel naming conventions', 'create an OPTForCausalLM model and generate text from a tokenizer prompt', 'build an OPTModel forward pass with input_ids and attention_mask to get hidden states', 'test OPTForSequenceClassification on a batch of text inputs with classification labels', 'review OPTForQuestionAnswering to extract start and end logits from a question and context', 'summarize the OPTDecoderLayer forward pass with self-attention and feed-forward layers']
```

Usage

```
{'create_OPTForCausalLM_generate': 'create an OPTForCausalLM model and generate text from a tokenizer prompt', 'build_OPTModel_forward': 'build an OPTModel forward pass with input_ids and attention_mask to get hidden states', 'test_OPTForSequenceClassification': 'test OPTForSequenceClassification on a batch of text inputs with classification labels', 'review_OPTForQuestionAnswering': 'review OPTForQuestionAnswering to extract start and end logits from a question and context', 'summarize_OPTDecoderLayer': 'summarize the OPTDecoderLayer forward pass with self-attention and feed-forward layers'}
```

