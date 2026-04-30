# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/plbart/convert_plbart_original_checkpoint_to_torch.py

Prompts

```
['convert a Fairseq PLBart checkpoint from disk to a HuggingFace PLBart model', 'run the CLI to convert a Fairseq PLBart model.pt to a PyTorch dump folder', 'remove ignored keys like version and output_projection from a PLBart state dict', 'build a linear layer from an embedding layer for PLBart lm_head initialization', 'convert a Fairseq PLBart classification checkpoint to HuggingFace PLBartForSequenceClassification', 'build a PLBartForConditionalGeneration model for code-to-text and text-to-code tasks', 'create a PLBartForSequenceClassification model with a classification head for GLUE tasks', 'run a PLBartModel encoder-decoder forward pass with input_ids and attention_mask', 'test a PLBartForCausalLM model for autoregressive text generation with past_key_values caching', 'review the PLBartAttention multi-headed attention mechanism with cross-attention and caching support', 'create a PLBartModel seq2seq transformer with encoder and decoder for code-to-text and text-to-code tasks', 'build a PLBartForConditionalGeneration model with language modeling head for masked token filling and sequence generation', 'run PLBartForSequenceClassification for sequence classification using the BigBird Pegasus classification head', 'test PLBartForCausalLM as a decoder-only model for causal language modeling with token generation', 'review PLBartPreTrainedModel base class with gradient checkpointing, flash attention, SDPA, and flex attention support', 'create a PLBartTokenizer instance from a pretrained model with source and target language codes', 'build translation inputs for the generate function with source and target language tokens', 'prepare a seq2seq batch with source texts, target texts, and language codes for tokenization', 'convert a token string to its corresponding vocabulary integer ID', 'decode a list of token IDs back to a text string with optional special token skipping']
```

Usage

```
{'convert_fairseq_plbart_checkpoint': 'convert a Fairseq PLBart checkpoint from disk to a HuggingFace PLBart model', 'run_cli_convert_plbart': 'run the CLI to convert a Fairseq PLBart model.pt to a PyTorch dump folder', 'remove_ignore_keys_state_dict': 'remove ignored keys like version and output_projection from a PLBart state dict', 'make_linear_from_embedding': 'build a linear layer from an embedding layer for PLBart lm_head initialization', 'convert_classification_checkpoint': 'convert a Fairseq PLBart classification checkpoint to HuggingFace PLBartForSequenceClassification'}
```

## File: huggingface_transformers/src/transformers/models/plbart/modeling_plbart.py

Prompts

```
['convert a Fairseq PLBart checkpoint from disk to a HuggingFace PLBart model', 'run the CLI to convert a Fairseq PLBart model.pt to a PyTorch dump folder', 'remove ignored keys like version and output_projection from a PLBart state dict', 'build a linear layer from an embedding layer for PLBart lm_head initialization', 'convert a Fairseq PLBart classification checkpoint to HuggingFace PLBartForSequenceClassification', 'build a PLBartForConditionalGeneration model for code-to-text and text-to-code tasks', 'create a PLBartForSequenceClassification model with a classification head for GLUE tasks', 'run a PLBartModel encoder-decoder forward pass with input_ids and attention_mask', 'test a PLBartForCausalLM model for autoregressive text generation with past_key_values caching', 'review the PLBartAttention multi-headed attention mechanism with cross-attention and caching support', 'create a PLBartModel seq2seq transformer with encoder and decoder for code-to-text and text-to-code tasks', 'build a PLBartForConditionalGeneration model with language modeling head for masked token filling and sequence generation', 'run PLBartForSequenceClassification for sequence classification using the BigBird Pegasus classification head', 'test PLBartForCausalLM as a decoder-only model for causal language modeling with token generation', 'review PLBartPreTrainedModel base class with gradient checkpointing, flash attention, SDPA, and flex attention support', 'create a PLBartTokenizer instance from a pretrained model with source and target language codes', 'build translation inputs for the generate function with source and target language tokens', 'prepare a seq2seq batch with source texts, target texts, and language codes for tokenization', 'convert a token string to its corresponding vocabulary integer ID', 'decode a list of token IDs back to a text string with optional special token skipping']
```

Usage

```
{'build_plbart_conditional_generation_model': 'build a PLBartForConditionalGeneration model for code-to-text and text-to-code tasks', 'create_plbart_sequence_classification_model': 'create a PLBartForSequenceClassification model with a classification head for GLUE tasks', 'run_plbart_encoder_decoder_forward_pass': 'run a PLBartModel encoder-decoder forward pass with input_ids and attention_mask', 'test_plbart_causal_lm_generation': 'test a PLBartForCausalLM model for autoregressive text generation with past_key_values caching', 'review_plbart_attention_mechanism': 'review the PLBartAttention multi-headed attention mechanism with cross-attention and caching support'}
```

## File: huggingface_transformers/src/transformers/models/plbart/modular_plbart.py

Prompts

```
['convert a Fairseq PLBart checkpoint from disk to a HuggingFace PLBart model', 'run the CLI to convert a Fairseq PLBart model.pt to a PyTorch dump folder', 'remove ignored keys like version and output_projection from a PLBart state dict', 'build a linear layer from an embedding layer for PLBart lm_head initialization', 'convert a Fairseq PLBart classification checkpoint to HuggingFace PLBartForSequenceClassification', 'build a PLBartForConditionalGeneration model for code-to-text and text-to-code tasks', 'create a PLBartForSequenceClassification model with a classification head for GLUE tasks', 'run a PLBartModel encoder-decoder forward pass with input_ids and attention_mask', 'test a PLBartForCausalLM model for autoregressive text generation with past_key_values caching', 'review the PLBartAttention multi-headed attention mechanism with cross-attention and caching support', 'create a PLBartModel seq2seq transformer with encoder and decoder for code-to-text and text-to-code tasks', 'build a PLBartForConditionalGeneration model with language modeling head for masked token filling and sequence generation', 'run PLBartForSequenceClassification for sequence classification using the BigBird Pegasus classification head', 'test PLBartForCausalLM as a decoder-only model for causal language modeling with token generation', 'review PLBartPreTrainedModel base class with gradient checkpointing, flash attention, SDPA, and flex attention support', 'create a PLBartTokenizer instance from a pretrained model with source and target language codes', 'build translation inputs for the generate function with source and target language tokens', 'prepare a seq2seq batch with source texts, target texts, and language codes for tokenization', 'convert a token string to its corresponding vocabulary integer ID', 'decode a list of token IDs back to a text string with optional special token skipping']
```

Usage

```
{'create_plbart_model': 'create a PLBartModel seq2seq transformer with encoder and decoder for code-to-text and text-to-code tasks', 'build_plbart_conditional_generation': 'build a PLBartForConditionalGeneration model with language modeling head for masked token filling and sequence generation', 'run_plbart_sequence_classification': 'run PLBartForSequenceClassification for sequence classification using the BigBird Pegasus classification head', 'test_plbart_causal_lm': 'test PLBartForCausalLM as a decoder-only model for causal language modeling with token generation', 'review_plbart_pretrained_model': 'review PLBartPreTrainedModel base class with gradient checkpointing, flash attention, SDPA, and flex attention support'}
```

## File: huggingface_transformers/src/transformers/models/plbart/tokenization_plbart.py

Prompts

```
['convert a Fairseq PLBart checkpoint from disk to a HuggingFace PLBart model', 'run the CLI to convert a Fairseq PLBart model.pt to a PyTorch dump folder', 'remove ignored keys like version and output_projection from a PLBart state dict', 'build a linear layer from an embedding layer for PLBart lm_head initialization', 'convert a Fairseq PLBart classification checkpoint to HuggingFace PLBartForSequenceClassification', 'build a PLBartForConditionalGeneration model for code-to-text and text-to-code tasks', 'create a PLBartForSequenceClassification model with a classification head for GLUE tasks', 'run a PLBartModel encoder-decoder forward pass with input_ids and attention_mask', 'test a PLBartForCausalLM model for autoregressive text generation with past_key_values caching', 'review the PLBartAttention multi-headed attention mechanism with cross-attention and caching support', 'create a PLBartModel seq2seq transformer with encoder and decoder for code-to-text and text-to-code tasks', 'build a PLBartForConditionalGeneration model with language modeling head for masked token filling and sequence generation', 'run PLBartForSequenceClassification for sequence classification using the BigBird Pegasus classification head', 'test PLBartForCausalLM as a decoder-only model for causal language modeling with token generation', 'review PLBartPreTrainedModel base class with gradient checkpointing, flash attention, SDPA, and flex attention support', 'create a PLBartTokenizer instance from a pretrained model with source and target language codes', 'build translation inputs for the generate function with source and target language tokens', 'prepare a seq2seq batch with source texts, target texts, and language codes for tokenization', 'convert a token string to its corresponding vocabulary integer ID', 'decode a list of token IDs back to a text string with optional special token skipping']
```

Usage

```
{'create_PLBartTokenizer': 'create a PLBartTokenizer instance from a pretrained model with source and target language codes', 'build_translation_inputs': 'build translation inputs for the generate function with source and target language tokens', 'prepare_seq2seq_batch': 'prepare a seq2seq batch with source texts, target texts, and language codes for tokenization', 'convert_token_to_id': 'convert a token string to its corresponding vocabulary integer ID', 'decode_token_ids': 'decode a list of token IDs back to a text string with optional special token skipping'}
```

