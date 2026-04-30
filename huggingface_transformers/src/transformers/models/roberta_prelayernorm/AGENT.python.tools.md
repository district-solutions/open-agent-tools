# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/roberta_prelayernorm/convert_roberta_prelayernorm_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert a RoBERTa-PreLayerNorm PyTorch checkpoint from a Hugging Face hub repo to a local PyTorch model folder', 'run the CLI script to convert a RoBERTa-PreLayerNorm checkpoint given a checkpoint repo and output folder path', 'create a RobertaPreLayerNormConfig from a pretrained checkpoint repo with specified architectures', 'convert original state dict keys by renaming roberta prefix to roberta_prelayernorm and removing unused LayerNorm weights', 'save the converted RobertaPreLayerNormForMaskedLM model and AutoTokenizer to a local output directory', 'build a RoBERTa-PreLayerNorm causal language model for next-token prediction with auto-regressive generation', 'create a RoBERTa-PreLayerNorm masked language model for bidirectional token prediction and fill-in-the-middle tasks', 'test the RoBERTa-PreLayerNorm sequence classification model for GLUE-style sentiment or text classification tasks', 'refactor the RoBERTa-PreLayerNorm question answering model to extract start and end token logits for span extraction', 'review the RoBERTa-PreLayerNorm token classification model for named entity recognition and sequence labeling tasks']
```

Usage

```
{'convert_roberta_prelayernorm_checkpoint': 'convert a RoBERTa-PreLayerNorm PyTorch checkpoint from a Hugging Face hub repo to a local PyTorch model folder', 'run_checkpoint_conversion_cli': 'run the CLI script to convert a RoBERTa-PreLayerNorm checkpoint given a checkpoint repo and output folder path', 'create_roberta_prelayernorm_config': 'create a RobertaPreLayerNormConfig from a pretrained checkpoint repo with specified architectures', 'convert_state_dict_keys': 'convert original state dict keys by renaming roberta prefix to roberta_prelayernorm and removing unused LayerNorm weights', 'save_converted_model_and_tokenizer': 'save the converted RobertaPreLayerNormForMaskedLM model and AutoTokenizer to a local output directory'}
```

## File: huggingface_transformers/src/transformers/models/roberta_prelayernorm/modeling_roberta_prelayernorm.py

Prompts

```
['convert a RoBERTa-PreLayerNorm PyTorch checkpoint from a Hugging Face hub repo to a local PyTorch model folder', 'run the CLI script to convert a RoBERTa-PreLayerNorm checkpoint given a checkpoint repo and output folder path', 'create a RobertaPreLayerNormConfig from a pretrained checkpoint repo with specified architectures', 'convert original state dict keys by renaming roberta prefix to roberta_prelayernorm and removing unused LayerNorm weights', 'save the converted RobertaPreLayerNormForMaskedLM model and AutoTokenizer to a local output directory', 'build a RoBERTa-PreLayerNorm causal language model for next-token prediction with auto-regressive generation', 'create a RoBERTa-PreLayerNorm masked language model for bidirectional token prediction and fill-in-the-middle tasks', 'test the RoBERTa-PreLayerNorm sequence classification model for GLUE-style sentiment or text classification tasks', 'refactor the RoBERTa-PreLayerNorm question answering model to extract start and end token logits for span extraction', 'review the RoBERTa-PreLayerNorm token classification model for named entity recognition and sequence labeling tasks']
```

Usage

```
{'build_causal_lm': 'build a RoBERTa-PreLayerNorm causal language model for next-token prediction with auto-regressive generation', 'create_masked_lm': 'create a RoBERTa-PreLayerNorm masked language model for bidirectional token prediction and fill-in-the-middle tasks', 'test_sequence_classification': 'test the RoBERTa-PreLayerNorm sequence classification model for GLUE-style sentiment or text classification tasks', 'refactor_question_answering': 'refactor the RoBERTa-PreLayerNorm question answering model to extract start and end token logits for span extraction', 'review_token_classification': 'review the RoBERTa-PreLayerNorm token classification model for named entity recognition and sequence labeling tasks'}
```

