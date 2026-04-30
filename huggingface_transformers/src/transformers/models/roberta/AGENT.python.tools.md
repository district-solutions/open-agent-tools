# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/roberta/convert_roberta_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert a fairseq RoBERTa checkpoint to a PyTorch HuggingFace model', 'create a RobertaForMaskedLM model from a fairseq RoBERTa checkpoint', 'create a RobertaForSequenceClassification model from a fairseq RoBERTa checkpoint with classification head', 'verify converted model outputs match the original fairseq RoBERTa outputs within tolerance', 'save the converted PyTorch RoBERTa model to a specified output directory', 'build a RoBERTa encoder model for bidirectional language understanding with positional and token-type embeddings', 'create a RoBERTa causal language model for autoregressive text generation with cross-attention support', 'test the RoBERTa masked language model for cloze-style token prediction with cross-entropy loss', 'run a RoBERTa sequence classifier for GLUE-style text classification with configurable loss functions', 'review the RoBERTa question answering model for extractive span prediction with start and end logits', 'create a RoBERTa model for sequence classification with a classification head on top of pooled output', 'build a RoBERTa model with a language modeling head for masked language modeling tasks', 'create a RoBERTa model for question answering that predicts start and end token positions', 'create a RoBERTa model for token classification tasks like NER with a linear classifier head', 'create a fast RoBERTa tokenizer from vocab and merges files with byte-level BPE encoding', 'build inputs with special tokens (bos, eos) for RoBERTa sequence pairs', 'encode text into RoBERTa input_ids using fast tokenizer with space-aware BPE', 'save RoBERTa tokenizer vocabulary files to a directory', 'create token type id masks (all zeros) for RoBERTa sequence-pair classification']
```

Usage

```
{'convert_roberta_checkpoint': 'convert a fairseq RoBERTa checkpoint to a PyTorch HuggingFace model', 'create_roberta_masked_lm': 'create a RobertaForMaskedLM model from a fairseq RoBERTa checkpoint', 'create_roberta_classification_model': 'create a RobertaForSequenceClassification model from a fairseq RoBERTa checkpoint with classification head', 'verify_conversion_accuracy': 'verify converted model outputs match the original fairseq RoBERTa outputs within tolerance', 'save_converted_model': 'save the converted PyTorch RoBERTa model to a specified output directory'}
```

## File: huggingface_transformers/src/transformers/models/roberta/modeling_roberta.py

Prompts

```
['convert a fairseq RoBERTa checkpoint to a PyTorch HuggingFace model', 'create a RobertaForMaskedLM model from a fairseq RoBERTa checkpoint', 'create a RobertaForSequenceClassification model from a fairseq RoBERTa checkpoint with classification head', 'verify converted model outputs match the original fairseq RoBERTa outputs within tolerance', 'save the converted PyTorch RoBERTa model to a specified output directory', 'build a RoBERTa encoder model for bidirectional language understanding with positional and token-type embeddings', 'create a RoBERTa causal language model for autoregressive text generation with cross-attention support', 'test the RoBERTa masked language model for cloze-style token prediction with cross-entropy loss', 'run a RoBERTa sequence classifier for GLUE-style text classification with configurable loss functions', 'review the RoBERTa question answering model for extractive span prediction with start and end logits', 'create a RoBERTa model for sequence classification with a classification head on top of pooled output', 'build a RoBERTa model with a language modeling head for masked language modeling tasks', 'create a RoBERTa model for question answering that predicts start and end token positions', 'create a RoBERTa model for token classification tasks like NER with a linear classifier head', 'create a fast RoBERTa tokenizer from vocab and merges files with byte-level BPE encoding', 'build inputs with special tokens (bos, eos) for RoBERTa sequence pairs', 'encode text into RoBERTa input_ids using fast tokenizer with space-aware BPE', 'save RoBERTa tokenizer vocabulary files to a directory', 'create token type id masks (all zeros) for RoBERTa sequence-pair classification']
```

Usage

```
{'build_roberta_encoder': 'build a RoBERTa encoder model for bidirectional language understanding with positional and token-type embeddings', 'create_roberta_causal_lm': 'create a RoBERTa causal language model for autoregressive text generation with cross-attention support', 'test_roberta_masked_lm': 'test the RoBERTa masked language model for cloze-style token prediction with cross-entropy loss', 'run_roberta_sequence_classifier': 'run a RoBERTa sequence classifier for GLUE-style text classification with configurable loss functions', 'review_roberta_question_answering': 'review the RoBERTa question answering model for extractive span prediction with start and end logits'}
```

## File: huggingface_transformers/src/transformers/models/roberta/modular_roberta.py

Prompts

```
['convert a fairseq RoBERTa checkpoint to a PyTorch HuggingFace model', 'create a RobertaForMaskedLM model from a fairseq RoBERTa checkpoint', 'create a RobertaForSequenceClassification model from a fairseq RoBERTa checkpoint with classification head', 'verify converted model outputs match the original fairseq RoBERTa outputs within tolerance', 'save the converted PyTorch RoBERTa model to a specified output directory', 'build a RoBERTa encoder model for bidirectional language understanding with positional and token-type embeddings', 'create a RoBERTa causal language model for autoregressive text generation with cross-attention support', 'test the RoBERTa masked language model for cloze-style token prediction with cross-entropy loss', 'run a RoBERTa sequence classifier for GLUE-style text classification with configurable loss functions', 'review the RoBERTa question answering model for extractive span prediction with start and end logits', 'create a RoBERTa model for sequence classification with a classification head on top of pooled output', 'build a RoBERTa model with a language modeling head for masked language modeling tasks', 'create a RoBERTa model for question answering that predicts start and end token positions', 'create a RoBERTa model for token classification tasks like NER with a linear classifier head', 'create a fast RoBERTa tokenizer from vocab and merges files with byte-level BPE encoding', 'build inputs with special tokens (bos, eos) for RoBERTa sequence pairs', 'encode text into RoBERTa input_ids using fast tokenizer with space-aware BPE', 'save RoBERTa tokenizer vocabulary files to a directory', 'create token type id masks (all zeros) for RoBERTa sequence-pair classification']
```

Usage

```
{'create_roberta_sequence_classifier': 'create a RoBERTa model for sequence classification with a classification head on top of pooled output', 'build_roberta_masked_lm': 'build a RoBERTa model with a language modeling head for masked language modeling tasks', 'create_roberta_question_answerer': 'create a RoBERTa model for question answering that predicts start and end token positions', 'create_roberta_token_classifier': 'create a RoBERTa model for token classification tasks like NER with a linear classifier head', 'create_roberta_causal_lm': 'create a RoBERTa model with a language modeling head for causal language modeling'}
```

## File: huggingface_transformers/src/transformers/models/roberta/tokenization_roberta_old.py

Prompts

```
['convert a fairseq RoBERTa checkpoint to a PyTorch HuggingFace model', 'create a RobertaForMaskedLM model from a fairseq RoBERTa checkpoint', 'create a RobertaForSequenceClassification model from a fairseq RoBERTa checkpoint with classification head', 'verify converted model outputs match the original fairseq RoBERTa outputs within tolerance', 'save the converted PyTorch RoBERTa model to a specified output directory', 'build a RoBERTa encoder model for bidirectional language understanding with positional and token-type embeddings', 'create a RoBERTa causal language model for autoregressive text generation with cross-attention support', 'test the RoBERTa masked language model for cloze-style token prediction with cross-entropy loss', 'run a RoBERTa sequence classifier for GLUE-style text classification with configurable loss functions', 'review the RoBERTa question answering model for extractive span prediction with start and end logits', 'create a RoBERTa model for sequence classification with a classification head on top of pooled output', 'build a RoBERTa model with a language modeling head for masked language modeling tasks', 'create a RoBERTa model for question answering that predicts start and end token positions', 'create a RoBERTa model for token classification tasks like NER with a linear classifier head', 'create a fast RoBERTa tokenizer from vocab and merges files with byte-level BPE encoding', 'build inputs with special tokens (bos, eos) for RoBERTa sequence pairs', 'encode text into RoBERTa input_ids using fast tokenizer with space-aware BPE', 'save RoBERTa tokenizer vocabulary files to a directory', 'create token type id masks (all zeros) for RoBERTa sequence-pair classification']
```

Usage

```
{'create_roberta_tokenizer_fast': 'create a fast RoBERTa tokenizer from vocab and merges files with byte-level BPE encoding', 'build_inputs_with_special_tokens': 'build inputs with special tokens (bos, eos) for RoBERTa sequence pairs', 'encode_roberta_text': 'encode text into RoBERTa input_ids using fast tokenizer with space-aware BPE', 'save_roberta_vocabulary': 'save RoBERTa tokenizer vocabulary files to a directory', 'create_token_type_ids_from_sequences': 'create token type id masks (all zeros) for RoBERTa sequence-pair classification'}
```

