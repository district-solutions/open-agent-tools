# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/CodeXGLUE/Text-Code/NL-code-search-Adv/code/model.py

Prompts

```
['build a Model instance with an encoder, config, tokenizer, and args for NL-code retrieval', 'run a forward pass on code and natural language inputs to compute contrastive loss', 'extract code and natural language embedding vectors by calling forward with return_vec=True', 'review the Model forward method that computes similarity scores and cross-entropy loss for code-NL pairs', 'test the Model class to verify contrastive loss computation between code and NL embeddings', 'run training for a natural language to code search model using BERT or RoBERTa', 'evaluate a trained NL-to-code search model and compute MRR scores', 'test a trained NL-to-code search model and write predictions to a JSONL file', 'convert raw JSON examples into tokenized InputFeatures for code and docstring pairs', 'create a PyTorch TextDataset from a JSONL file of code and docstring examples']
```

Usage

```
{'build_model_instance': 'build a Model instance with an encoder, config, tokenizer, and args for NL-code retrieval', 'run_forward_pass': 'run a forward pass on code and natural language inputs to compute contrastive loss', 'extract_code_nl_vectors': 'extract code and natural language embedding vectors by calling forward with return_vec=True', 'review_model_forward': 'review the Model forward method that computes similarity scores and cross-entropy loss for code-NL pairs', 'test_model_contrastive_loss': 'test the Model class to verify contrastive loss computation between code and NL embeddings'}
```

## File: facebookresearch_codegen/CodeXGLUE/Text-Code/NL-code-search-Adv/code/run.py

Prompts

```
['build a Model instance with an encoder, config, tokenizer, and args for NL-code retrieval', 'run a forward pass on code and natural language inputs to compute contrastive loss', 'extract code and natural language embedding vectors by calling forward with return_vec=True', 'review the Model forward method that computes similarity scores and cross-entropy loss for code-NL pairs', 'test the Model class to verify contrastive loss computation between code and NL embeddings', 'run training for a natural language to code search model using BERT or RoBERTa', 'evaluate a trained NL-to-code search model and compute MRR scores', 'test a trained NL-to-code search model and write predictions to a JSONL file', 'convert raw JSON examples into tokenized InputFeatures for code and docstring pairs', 'create a PyTorch TextDataset from a JSONL file of code and docstring examples']
```

Usage

```
{'run_train_nl_code_search': 'run training for a natural language to code search model using BERT or RoBERTa', 'run_evaluate_nl_code_search': 'evaluate a trained NL-to-code search model and compute MRR scores', 'run_test_nl_code_search': 'test a trained NL-to-code search model and write predictions to a JSONL file', 'convert_examples_to_features': 'convert raw JSON examples into tokenized InputFeatures for code and docstring pairs', 'create_text_dataset': 'create a PyTorch TextDataset from a JSONL file of code and docstring examples'}
```

