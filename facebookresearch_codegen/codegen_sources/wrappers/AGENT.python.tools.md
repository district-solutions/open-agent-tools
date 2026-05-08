# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/wrappers/models.py

Prompts

```
['create a ModelConfig from a pretrained checkpoint file path using ModelConfig.from_pretrained', 'build a Model encoder with a given config and language for code representation', 'load a pretrained ModelJava encoder from a model checkpoint path', 'load a pretrained ModelPython encoder from a model checkpoint path', 'run sequence classification on Python or Java code using ModelForSequenceClassification', 'tokenize Python or Java source code into subword tokens using BPE or RoBERTa models', 'convert a list of token strings to their corresponding integer IDs using the tokenizer vocabulary', 'decode a list of integer token IDs back into readable source code with optional detokenization', 'load a pretrained Java or Python tokenizer from a saved model checkpoint file', 'create a RoBERTa-based tokenizer for Python or Java code with special token handling']
```

Usage

```
{'create_modelconfig_from_pretrained': 'create a ModelConfig from a pretrained checkpoint file path using ModelConfig.from_pretrained', 'build_model_encoder': 'build a Model encoder with a given config and language for code representation', 'load_modeljava_from_pretrained': 'load a pretrained ModelJava encoder from a model checkpoint path', 'load_modelpython_from_pretrained': 'load a pretrained ModelPython encoder from a model checkpoint path', 'run_sequence_classification': 'run sequence classification on Python or Java code using ModelForSequenceClassification'}
```

## File: facebookresearch_codegen/codegen_sources/wrappers/tokenizer.py

Prompts

```
['create a ModelConfig from a pretrained checkpoint file path using ModelConfig.from_pretrained', 'build a Model encoder with a given config and language for code representation', 'load a pretrained ModelJava encoder from a model checkpoint path', 'load a pretrained ModelPython encoder from a model checkpoint path', 'run sequence classification on Python or Java code using ModelForSequenceClassification', 'tokenize Python or Java source code into subword tokens using BPE or RoBERTa models', 'convert a list of token strings to their corresponding integer IDs using the tokenizer vocabulary', 'decode a list of integer token IDs back into readable source code with optional detokenization', 'load a pretrained Java or Python tokenizer from a saved model checkpoint file', 'create a RoBERTa-based tokenizer for Python or Java code with special token handling']
```

Usage

```
{'tokenize_code_with_BPE': 'tokenize Python or Java source code into subword tokens using BPE or RoBERTa models', 'convert_tokens_to_ids': 'convert a list of token strings to their corresponding integer IDs using the tokenizer vocabulary', 'decode_token_ids': 'decode a list of integer token IDs back into readable source code with optional detokenization', 'load_pretrained_tokenizer': 'load a pretrained Java or Python tokenizer from a saved model checkpoint file', 'create_roberta_tokenizer': 'create a RoBERTa-based tokenizer for Python or Java code with special token handling'}
```

