# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/nystromformer/convert_nystromformer_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert a Nystromformer original PyTorch checkpoint to HuggingFace PyTorch format using checkpoint, config, and output paths', 'rename Nystromformer checkpoint keys to match HuggingFace NystromformerForMaskedLM state dict naming conventions', 'transform an original Nystromformer state dict into HuggingFace-compatible format by renaming keys and filtering unsupported layers', 'run the Nystromformer checkpoint conversion CLI with --pytorch_model_path, --config_file, and --pytorch_dump_path arguments', 'review the convert_checkpoint_helper function that filters pooler, sen_class, and conv.bias keys while renaming state dict entries', 'build a NystromformerModel transformer with configurable embeddings and encoder layers', 'create a NystromformerForMaskedLM model for masked language modeling tasks', 'create a NystromformerForSequenceClassification model for GLUE-style classification tasks', 'create a NystromformerForQuestionAnswering model for extractive QA with start and end logits', 'create a NystromformerForTokenClassification model for NER and token-level classification']
```

Usage

```
{'convert_nystromformer_checkpoint': 'convert a Nystromformer original PyTorch checkpoint to HuggingFace PyTorch format using checkpoint, config, and output paths', 'rename_key': 'rename Nystromformer checkpoint keys to match HuggingFace NystromformerForMaskedLM state dict naming conventions', 'convert_checkpoint_helper': 'transform an original Nystromformer state dict into HuggingFace-compatible format by renaming keys and filtering unsupported layers', 'run_checkpoint_conversion_cli': 'run the Nystromformer checkpoint conversion CLI with --pytorch_model_path, --config_file, and --pytorch_dump_path arguments', 'review_convert_checkpoint_helper': 'review the convert_checkpoint_helper function that filters pooler, sen_class, and conv.bias keys while renaming state dict entries'}
```

## File: huggingface_transformers/src/transformers/models/nystromformer/modeling_nystromformer.py

Prompts

```
['convert a Nystromformer original PyTorch checkpoint to HuggingFace PyTorch format using checkpoint, config, and output paths', 'rename Nystromformer checkpoint keys to match HuggingFace NystromformerForMaskedLM state dict naming conventions', 'transform an original Nystromformer state dict into HuggingFace-compatible format by renaming keys and filtering unsupported layers', 'run the Nystromformer checkpoint conversion CLI with --pytorch_model_path, --config_file, and --pytorch_dump_path arguments', 'review the convert_checkpoint_helper function that filters pooler, sen_class, and conv.bias keys while renaming state dict entries', 'build a NystromformerModel transformer with configurable embeddings and encoder layers', 'create a NystromformerForMaskedLM model for masked language modeling tasks', 'create a NystromformerForSequenceClassification model for GLUE-style classification tasks', 'create a NystromformerForQuestionAnswering model for extractive QA with start and end logits', 'create a NystromformerForTokenClassification model for NER and token-level classification']
```

Usage

```
{'build_nystromformer_model': 'build a NystromformerModel transformer with configurable embeddings and encoder layers', 'create_masked_lm': 'create a NystromformerForMaskedLM model for masked language modeling tasks', 'create_sequence_classifier': 'create a NystromformerForSequenceClassification model for GLUE-style classification tasks', 'create_question_answerer': 'create a NystromformerForQuestionAnswering model for extractive QA with start and end logits', 'create_token_classifier': 'create a NystromformerForTokenClassification model for NER and token-level classification'}
```

