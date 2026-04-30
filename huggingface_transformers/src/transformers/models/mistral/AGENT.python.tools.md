# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mistral/convert_mistral_weights_to_hf.py

Prompts

```
['convert Mistral model weights from original format to HuggingFace Transformers format', 'run the converter on sharded Mistral checkpoint files with modules split across multiple files', 'convert Mistral tokenizer from original format to HuggingFace format with optional chat template', 'convert Mistral params.json config to HuggingFace MistralConfig with proper key mapping', 'convert Mistral state dict weights with ROPE permutation and key remapping for HuggingFace model', 'build a MistralForCausalLM model for autoregressive text generation with past key value caching', 'create a MistralModel forward pass that encodes input tokens through stacked decoder layers with causal masking', 'test the MistralAttention module with grouped query attention and rotary position embeddings', 'refactor the MistralDecoderLayer to support gradient checkpointing with pre-norm residual connections', 'summarize the MistralRMSNorm layer that normalizes hidden states using root mean square statistics', 'review the MistralForQuestionAnswering class that combines GenericForQuestionAnswering with MistralPreTrainedModel']
```

Usage

```
{'convert_mistral_weights_to_hf': 'convert Mistral model weights from original format to HuggingFace Transformers format', 'run_convert_with_sharded_weights': 'run the converter on sharded Mistral checkpoint files with modules split across multiple files', 'convert_mistral_tokenizer': 'convert Mistral tokenizer from original format to HuggingFace format with optional chat template', 'convert_mistral_config': 'convert Mistral params.json config to HuggingFace MistralConfig with proper key mapping', 'convert_state_dict_weights': 'convert Mistral state dict weights with ROPE permutation and key remapping for HuggingFace model'}
```

## File: huggingface_transformers/src/transformers/models/mistral/modeling_mistral.py

Prompts

```
['convert Mistral model weights from original format to HuggingFace Transformers format', 'run the converter on sharded Mistral checkpoint files with modules split across multiple files', 'convert Mistral tokenizer from original format to HuggingFace format with optional chat template', 'convert Mistral params.json config to HuggingFace MistralConfig with proper key mapping', 'convert Mistral state dict weights with ROPE permutation and key remapping for HuggingFace model', 'build a MistralForCausalLM model for autoregressive text generation with past key value caching', 'create a MistralModel forward pass that encodes input tokens through stacked decoder layers with causal masking', 'test the MistralAttention module with grouped query attention and rotary position embeddings', 'refactor the MistralDecoderLayer to support gradient checkpointing with pre-norm residual connections', 'summarize the MistralRMSNorm layer that normalizes hidden states using root mean square statistics', 'review the MistralForQuestionAnswering class that combines GenericForQuestionAnswering with MistralPreTrainedModel']
```

Usage

```
{'build_mistral_causal_lm': 'build a MistralForCausalLM model for autoregressive text generation with past key value caching', 'create_mistral_model_forward': 'create a MistralModel forward pass that encodes input tokens through stacked decoder layers with causal masking', 'test_mistral_attention': 'test the MistralAttention module with grouped query attention and rotary position embeddings', 'refactor_mistral_decoder_layer': 'refactor the MistralDecoderLayer to support gradient checkpointing with pre-norm residual connections', 'summarize_mistral_rmsnorm': 'summarize the MistralRMSNorm layer that normalizes hidden states using root mean square statistics'}
```

## File: huggingface_transformers/src/transformers/models/mistral/modular_mistral.py

Prompts

```
['convert Mistral model weights from original format to HuggingFace Transformers format', 'run the converter on sharded Mistral checkpoint files with modules split across multiple files', 'convert Mistral tokenizer from original format to HuggingFace format with optional chat template', 'convert Mistral params.json config to HuggingFace MistralConfig with proper key mapping', 'convert Mistral state dict weights with ROPE permutation and key remapping for HuggingFace model', 'build a MistralForCausalLM model for autoregressive text generation with past key value caching', 'create a MistralModel forward pass that encodes input tokens through stacked decoder layers with causal masking', 'test the MistralAttention module with grouped query attention and rotary position embeddings', 'refactor the MistralDecoderLayer to support gradient checkpointing with pre-norm residual connections', 'summarize the MistralRMSNorm layer that normalizes hidden states using root mean square statistics', 'review the MistralForQuestionAnswering class that combines GenericForQuestionAnswering with MistralPreTrainedModel']
```

Usage

```
{'build_mistral_causal_lm': 'build a MistralForCausalLM model for autoregressive text generation with past key-value caching', 'create_mistral_model_forward': 'create a MistralModel forward pass that encodes input IDs and returns hidden states with causal masking', 'test_mistral_attention': 'test the MistralAttention class with sliding window attention and rotary position embeddings', 'refactor_mistral_decoder_layer': 'refactor the MistralDecoderLayer to use MistralAttention and MistralMLP components', 'review_mistral_for_question_answering': 'review the MistralForQuestionAnswering class that combines GenericForQuestionAnswering with MistralPreTrainedModel'}
```

