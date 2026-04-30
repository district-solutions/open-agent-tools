# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mbart/convert_mbart_original_checkpoint_to_pytorch.py

Prompts

```
['convert a fairseq MBart checkpoint from disk to a HuggingFace MBartForConditionalGeneration model', 'run the CLI to convert a fairseq MBart checkpoint to a PyTorch dump folder', 'remove ignore keys like encoder.version and decoder.version from a model state dict', 'create an nn.Linear layer from an embedding layer for fine-tuned MBart models', 'convert a fine-tuned MBart-50 fairseq checkpoint with relu activation to HuggingFace format', 'create an MBartModel instance for encoder-decoder sequence-to-sequence tasks', 'build an MBartForConditionalGeneration model for machine translation and summarization', 'test MBartForSequenceClassification for GLUE-style sequence classification tasks', 'run MBartForCausalLM for causal language modeling with decoder-only generation', 'review MBartForQuestionAnswering for extractive QA with start and end position logits', 'create an MBartTokenizer instance from a pretrained model with source and target language codes', 'build translation inputs by calling _build_translation_inputs with raw text, return_tensors, src_lang, and tgt_lang', 'set source language special tokens by calling set_src_lang_special_tokens with a language code string', 'set target language special tokens by calling set_tgt_lang_special_tokens with a language code string', 'switch the tokenizer to target mode by calling _switch_to_target_mode for translation generation']
```

Usage

```
{'convert_fairseq_mbart_checkpoint': 'convert a fairseq MBart checkpoint from disk to a HuggingFace MBartForConditionalGeneration model', 'run_cli_convert_mbart_checkpoint': 'run the CLI to convert a fairseq MBart checkpoint to a PyTorch dump folder', 'remove_ignore_keys_from_state_dict': 'remove ignore keys like encoder.version and decoder.version from a model state dict', 'create_linear_layer_from_embedding': 'create an nn.Linear layer from an embedding layer for fine-tuned MBart models', 'convert_mbart_50_finetuned_checkpoint': 'convert a fine-tuned MBart-50 fairseq checkpoint with relu activation to HuggingFace format'}
```

## File: huggingface_transformers/src/transformers/models/mbart/modeling_mbart.py

Prompts

```
['convert a fairseq MBart checkpoint from disk to a HuggingFace MBartForConditionalGeneration model', 'run the CLI to convert a fairseq MBart checkpoint to a PyTorch dump folder', 'remove ignore keys like encoder.version and decoder.version from a model state dict', 'create an nn.Linear layer from an embedding layer for fine-tuned MBart models', 'convert a fine-tuned MBart-50 fairseq checkpoint with relu activation to HuggingFace format', 'create an MBartModel instance for encoder-decoder sequence-to-sequence tasks', 'build an MBartForConditionalGeneration model for machine translation and summarization', 'test MBartForSequenceClassification for GLUE-style sequence classification tasks', 'run MBartForCausalLM for causal language modeling with decoder-only generation', 'review MBartForQuestionAnswering for extractive QA with start and end position logits', 'create an MBartTokenizer instance from a pretrained model with source and target language codes', 'build translation inputs by calling _build_translation_inputs with raw text, return_tensors, src_lang, and tgt_lang', 'set source language special tokens by calling set_src_lang_special_tokens with a language code string', 'set target language special tokens by calling set_tgt_lang_special_tokens with a language code string', 'switch the tokenizer to target mode by calling _switch_to_target_mode for translation generation']
```

Usage

```
{'create_mbart_model': 'create an MBartModel instance for encoder-decoder sequence-to-sequence tasks', 'build_mbart_translation': 'build an MBartForConditionalGeneration model for machine translation and summarization', 'test_mbart_classification': 'test MBartForSequenceClassification for GLUE-style sequence classification tasks', 'run_mbart_causal_lm': 'run MBartForCausalLM for causal language modeling with decoder-only generation', 'review_mbart_question_answering': 'review MBartForQuestionAnswering for extractive QA with start and end position logits'}
```

## File: huggingface_transformers/src/transformers/models/mbart/tokenization_mbart.py

Prompts

```
['convert a fairseq MBart checkpoint from disk to a HuggingFace MBartForConditionalGeneration model', 'run the CLI to convert a fairseq MBart checkpoint to a PyTorch dump folder', 'remove ignore keys like encoder.version and decoder.version from a model state dict', 'create an nn.Linear layer from an embedding layer for fine-tuned MBart models', 'convert a fine-tuned MBart-50 fairseq checkpoint with relu activation to HuggingFace format', 'create an MBartModel instance for encoder-decoder sequence-to-sequence tasks', 'build an MBartForConditionalGeneration model for machine translation and summarization', 'test MBartForSequenceClassification for GLUE-style sequence classification tasks', 'run MBartForCausalLM for causal language modeling with decoder-only generation', 'review MBartForQuestionAnswering for extractive QA with start and end position logits', 'create an MBartTokenizer instance from a pretrained model with source and target language codes', 'build translation inputs by calling _build_translation_inputs with raw text, return_tensors, src_lang, and tgt_lang', 'set source language special tokens by calling set_src_lang_special_tokens with a language code string', 'set target language special tokens by calling set_tgt_lang_special_tokens with a language code string', 'switch the tokenizer to target mode by calling _switch_to_target_mode for translation generation']
```

Usage

```
{'create_mbart_tokenizer': 'create an MBartTokenizer instance from a pretrained model with source and target language codes', 'build_translation_inputs': 'build translation inputs by calling _build_translation_inputs with raw text, return_tensors, src_lang, and tgt_lang', 'set_source_language_tokens': 'set source language special tokens by calling set_src_lang_special_tokens with a language code string', 'set_target_language_tokens': 'set target language special tokens by calling set_tgt_lang_special_tokens with a language code string', 'switch_to_target_mode': 'switch the tokenizer to target mode by calling _switch_to_target_mode for translation generation'}
```

