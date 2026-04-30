# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/t5gemma/configuration_t5gemma.py

Prompts

```
['create a T5GemmaModuleConfig instance with custom encoder layer settings like hidden_size and num_hidden_layers', 'create a T5GemmaConfig instance with separate encoder and decoder configurations for an encoder-decoder model', 'configure T5GemmaModuleConfig with custom query_pre_attn_scalar, sliding_window, and softcapping parameters', 'validate T5GemmaConfig architecture by checking hidden_size is a multiple of num_attention_heads', 'initialize T5GemmaConfig from pretrained checkpoint with encoder and decoder sub-configs automatically populated', 'build a T5GemmaForConditionalGeneration model for sequence-to-sequence text generation tasks', 'create a T5GemmaEncoderModel for encoder-only feature extraction and representation learning', 'test the T5GemmaForSequenceClassification model for text classification with configurable number of labels', 'refactor the T5GemmaForTokenClassification model for token-level NER tasks with encoder or encoder-decoder mode', 'run the T5GemmaModel forward pass for encoder-decoder sequence-to-sequence inference with past key values caching', 'create a T5GemmaConfig with encoder and decoder settings for the t5_gemma_module-7b model', 'build a T5GemmaModel encoder-decoder from a T5GemmaConfig for sequence-to-sequence tasks', 'run T5GemmaForConditionalGeneration to produce text outputs with masked language modeling loss', 'test T5GemmaForSequenceClassification for sentence-level classification with labeled data', 'review T5GemmaForTokenClassification for per-token classification tasks with encoder or encoder-decoder mode']
```

Usage

```
{'create_T5GemmaModuleConfig': 'create a T5GemmaModuleConfig instance with custom encoder layer settings like hidden_size and num_hidden_layers', 'create_T5GemmaConfig': 'create a T5GemmaConfig instance with separate encoder and decoder configurations for an encoder-decoder model', 'configure_T5GemmaModuleConfig': 'configure T5GemmaModuleConfig with custom query_pre_attn_scalar, sliding_window, and softcapping parameters', 'validate_T5GemmaConfig': 'validate T5GemmaConfig architecture by checking hidden_size is a multiple of num_attention_heads', 'initialize_T5GemmaConfig': 'initialize T5GemmaConfig from pretrained checkpoint with encoder and decoder sub-configs automatically populated'}
```

## File: huggingface_transformers/src/transformers/models/t5gemma/modeling_t5gemma.py

Prompts

```
['create a T5GemmaModuleConfig instance with custom encoder layer settings like hidden_size and num_hidden_layers', 'create a T5GemmaConfig instance with separate encoder and decoder configurations for an encoder-decoder model', 'configure T5GemmaModuleConfig with custom query_pre_attn_scalar, sliding_window, and softcapping parameters', 'validate T5GemmaConfig architecture by checking hidden_size is a multiple of num_attention_heads', 'initialize T5GemmaConfig from pretrained checkpoint with encoder and decoder sub-configs automatically populated', 'build a T5GemmaForConditionalGeneration model for sequence-to-sequence text generation tasks', 'create a T5GemmaEncoderModel for encoder-only feature extraction and representation learning', 'test the T5GemmaForSequenceClassification model for text classification with configurable number of labels', 'refactor the T5GemmaForTokenClassification model for token-level NER tasks with encoder or encoder-decoder mode', 'run the T5GemmaModel forward pass for encoder-decoder sequence-to-sequence inference with past key values caching', 'create a T5GemmaConfig with encoder and decoder settings for the t5_gemma_module-7b model', 'build a T5GemmaModel encoder-decoder from a T5GemmaConfig for sequence-to-sequence tasks', 'run T5GemmaForConditionalGeneration to produce text outputs with masked language modeling loss', 'test T5GemmaForSequenceClassification for sentence-level classification with labeled data', 'review T5GemmaForTokenClassification for per-token classification tasks with encoder or encoder-decoder mode']
```

Usage

```
{'build_t5gemma_conditional_generation': 'build a T5GemmaForConditionalGeneration model for sequence-to-sequence text generation tasks', 'create_t5gemma_encoder_model': 'create a T5GemmaEncoderModel for encoder-only feature extraction and representation learning', 'test_t5gemma_sequence_classification': 'test the T5GemmaForSequenceClassification model for text classification with configurable number of labels', 'refactor_t5gemma_token_classification': 'refactor the T5GemmaForTokenClassification model for token-level NER tasks with encoder or encoder-decoder mode', 'run_t5gemma_seq2seq_forward': 'run the T5GemmaModel forward pass for encoder-decoder sequence-to-sequence inference with past key values caching'}
```

## File: huggingface_transformers/src/transformers/models/t5gemma/modular_t5gemma.py

Prompts

```
['create a T5GemmaModuleConfig instance with custom encoder layer settings like hidden_size and num_hidden_layers', 'create a T5GemmaConfig instance with separate encoder and decoder configurations for an encoder-decoder model', 'configure T5GemmaModuleConfig with custom query_pre_attn_scalar, sliding_window, and softcapping parameters', 'validate T5GemmaConfig architecture by checking hidden_size is a multiple of num_attention_heads', 'initialize T5GemmaConfig from pretrained checkpoint with encoder and decoder sub-configs automatically populated', 'build a T5GemmaForConditionalGeneration model for sequence-to-sequence text generation tasks', 'create a T5GemmaEncoderModel for encoder-only feature extraction and representation learning', 'test the T5GemmaForSequenceClassification model for text classification with configurable number of labels', 'refactor the T5GemmaForTokenClassification model for token-level NER tasks with encoder or encoder-decoder mode', 'run the T5GemmaModel forward pass for encoder-decoder sequence-to-sequence inference with past key values caching', 'create a T5GemmaConfig with encoder and decoder settings for the t5_gemma_module-7b model', 'build a T5GemmaModel encoder-decoder from a T5GemmaConfig for sequence-to-sequence tasks', 'run T5GemmaForConditionalGeneration to produce text outputs with masked language modeling loss', 'test T5GemmaForSequenceClassification for sentence-level classification with labeled data', 'review T5GemmaForTokenClassification for per-token classification tasks with encoder or encoder-decoder mode']
```

Usage

```
{'create_t5gemma_config': 'create a T5GemmaConfig with encoder and decoder settings for the t5_gemma_module-7b model', 'build_t5gemma_model': 'build a T5GemmaModel encoder-decoder from a T5GemmaConfig for sequence-to-sequence tasks', 'run_t5gemma_generation': 'run T5GemmaForConditionalGeneration to produce text outputs with masked language modeling loss', 'test_t5gemma_classification': 'test T5GemmaForSequenceClassification for sentence-level classification with labeled data', 'review_t5gemma_token_classification': 'review T5GemmaForTokenClassification for per-token classification tasks with encoder or encoder-decoder mode'}
```

