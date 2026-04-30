# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/reformer/convert_reformer_trax_checkpoint_to_pytorch.py

Prompts

```
['convert a Trax Reformer checkpoint pickle file to a PyTorch model state dict using a config json file', 'build a PyTorch ReformerModelWithLMHead from a ReformerConfig loaded from a JSON config file', 'set model weights from Trax checkpoint weights into a PyTorch Reformer model', 'set attention and feed-forward block weights from Trax format into a PyTorch Reformer encoder layer', 'set local-sparse hashing attention layer weights from Trax format into a PyTorch Reformer attention module', 'create a ReformerModel with ReformerConfig for bidirectional encoder tasks', 'run ReformerModelWithLMHead for causal language modeling and text generation', 'train ReformerForMaskedLM on masked language modeling with cross-entropy loss', 'classify sequences using ReformerForSequenceClassification with classification head', 'extract start and end positions using ReformerForQuestionAnswering for QA tasks']
```

Usage

```
{'convert_trax_checkpoint_to_pytorch': 'convert a Trax Reformer checkpoint pickle file to a PyTorch model state dict using a config json file', 'build_reformer_model_from_config': 'build a PyTorch ReformerModelWithLMHead from a ReformerConfig loaded from a JSON config file', 'set_model_weights_in_torch': 'set model weights from Trax checkpoint weights into a PyTorch Reformer model', 'set_block_weights_in_torch': 'set attention and feed-forward block weights from Trax format into a PyTorch Reformer encoder layer', 'set_layer_weights_in_torch_lsh': 'set local-sparse hashing attention layer weights from Trax format into a PyTorch Reformer attention module'}
```

## File: huggingface_transformers/src/transformers/models/reformer/modeling_reformer.py

Prompts

```
['convert a Trax Reformer checkpoint pickle file to a PyTorch model state dict using a config json file', 'build a PyTorch ReformerModelWithLMHead from a ReformerConfig loaded from a JSON config file', 'set model weights from Trax checkpoint weights into a PyTorch Reformer model', 'set attention and feed-forward block weights from Trax format into a PyTorch Reformer encoder layer', 'set local-sparse hashing attention layer weights from Trax format into a PyTorch Reformer attention module', 'create a ReformerModel with ReformerConfig for bidirectional encoder tasks', 'run ReformerModelWithLMHead for causal language modeling and text generation', 'train ReformerForMaskedLM on masked language modeling with cross-entropy loss', 'classify sequences using ReformerForSequenceClassification with classification head', 'extract start and end positions using ReformerForQuestionAnswering for QA tasks']
```

Usage

```
{'create_reformer_model': 'create a ReformerModel with ReformerConfig for bidirectional encoder tasks', 'run_reformer_lm_head': 'run ReformerModelWithLMHead for causal language modeling and text generation', 'train_reformer_masked_lm': 'train ReformerForMaskedLM on masked language modeling with cross-entropy loss', 'classify_with_reformer': 'classify sequences using ReformerForSequenceClassification with classification head', 'extract_answers_with_reformer': 'extract start and end positions using ReformerForQuestionAnswering for QA tasks'}
```

