# Agent Python Tools

- repo: facebookresearch/blink
- repo_uri: https://github.com/facebookresearch/blink

## File: facebookresearch_blink/blink/common/optimizer.py

Prompts

```
['build a BERT optimizer with AdamW that groups parameters with and without weight decay', 'create an AdamW optimizer for BERT models with optional fp16 wrapper support', 'test the ellipse function that joins a list with an ellipsis for long lists', 'review the patterns_optimizer dictionary that defines which BERT layers to optimize', 'refactor get_bert_optimizer to support additional optimization patterns beyond the predefined set', 'create a BlinkParser instance with default common BLINK arguments like silent, debug, and top_k', 'create a BlinkParser instance with model arguments for loading BERT-based models and sequence length settings', 'add training arguments like learning rate, batch size, and num_train_epochs to a BlinkParser', 'add evaluation arguments like eval_batch_size, mode, and cand_pool_path to a BlinkParser', 'parse command line arguments using BlinkParser to configure BLINK entity linking model training or evaluation', 'create a BertEncoder PyTorch module wrapping a BERT model with optional linear projection layer', 'run the BertEncoder forward pass with token_ids, segment_ids, and attention_mask inputs', 'test the get_model_obj function to unwrap DataParallel models by extracting the inner module', 'review the BertEncoder constructor to configure dimensionality reduction via an optional add_linear parameter', 'refactor the BertEncoder forward method to use CLS token embeddings or pooler output based on configuration']
```

Usage

```
{'build_bert_optimizer': 'build a BERT optimizer with AdamW that groups parameters with and without weight decay', 'create_optimizer_with_fp16': 'create an AdamW optimizer for BERT models with optional fp16 wrapper support', 'test_ellipse_function': 'test the ellipse function that joins a list with an ellipsis for long lists', 'review_patterns_optimizer': 'review the patterns_optimizer dictionary that defines which BERT layers to optimize', 'refactor_get_bert_optimizer': 'refactor get_bert_optimizer to support additional optimization patterns beyond the predefined set'}
```

## File: facebookresearch_blink/blink/common/params.py

Prompts

```
['build a BERT optimizer with AdamW that groups parameters with and without weight decay', 'create an AdamW optimizer for BERT models with optional fp16 wrapper support', 'test the ellipse function that joins a list with an ellipsis for long lists', 'review the patterns_optimizer dictionary that defines which BERT layers to optimize', 'refactor get_bert_optimizer to support additional optimization patterns beyond the predefined set', 'create a BlinkParser instance with default common BLINK arguments like silent, debug, and top_k', 'create a BlinkParser instance with model arguments for loading BERT-based models and sequence length settings', 'add training arguments like learning rate, batch size, and num_train_epochs to a BlinkParser', 'add evaluation arguments like eval_batch_size, mode, and cand_pool_path to a BlinkParser', 'parse command line arguments using BlinkParser to configure BLINK entity linking model training or evaluation', 'create a BertEncoder PyTorch module wrapping a BERT model with optional linear projection layer', 'run the BertEncoder forward pass with token_ids, segment_ids, and attention_mask inputs', 'test the get_model_obj function to unwrap DataParallel models by extracting the inner module', 'review the BertEncoder constructor to configure dimensionality reduction via an optional add_linear parameter', 'refactor the BertEncoder forward method to use CLS token embeddings or pooler output based on configuration']
```

Usage

```
{'create_blink_parser_with_common_args': 'create a BlinkParser instance with default common BLINK arguments like silent, debug, and top_k', 'create_blink_parser_with_model_args': 'create a BlinkParser instance with model arguments for loading BERT-based models and sequence length settings', 'add_training_args_to_parser': 'add training arguments like learning rate, batch size, and num_train_epochs to a BlinkParser', 'add_eval_args_to_parser': 'add evaluation arguments like eval_batch_size, mode, and cand_pool_path to a BlinkParser', 'parse_blink_cli_arguments': 'parse command line arguments using BlinkParser to configure BLINK entity linking model training or evaluation'}
```

## File: facebookresearch_blink/blink/common/ranker_base.py

Prompts

```
['build a BERT optimizer with AdamW that groups parameters with and without weight decay', 'create an AdamW optimizer for BERT models with optional fp16 wrapper support', 'test the ellipse function that joins a list with an ellipsis for long lists', 'review the patterns_optimizer dictionary that defines which BERT layers to optimize', 'refactor get_bert_optimizer to support additional optimization patterns beyond the predefined set', 'create a BlinkParser instance with default common BLINK arguments like silent, debug, and top_k', 'create a BlinkParser instance with model arguments for loading BERT-based models and sequence length settings', 'add training arguments like learning rate, batch size, and num_train_epochs to a BlinkParser', 'add evaluation arguments like eval_batch_size, mode, and cand_pool_path to a BlinkParser', 'parse command line arguments using BlinkParser to configure BLINK entity linking model training or evaluation', 'create a BertEncoder PyTorch module wrapping a BERT model with optional linear projection layer', 'run the BertEncoder forward pass with token_ids, segment_ids, and attention_mask inputs', 'test the get_model_obj function to unwrap DataParallel models by extracting the inner module', 'review the BertEncoder constructor to configure dimensionality reduction via an optional add_linear parameter', 'refactor the BertEncoder forward method to use CLS token embeddings or pooler output based on configuration']
```

Usage

```
{'create_BertEncoder': 'create a BertEncoder PyTorch module wrapping a BERT model with optional linear projection layer', 'run_BertEncoder_forward': 'run the BertEncoder forward pass with token_ids, segment_ids, and attention_mask inputs', 'test_get_model_obj': 'test the get_model_obj function to unwrap DataParallel models by extracting the inner module', 'review_BertEncoder_init': 'review the BertEncoder constructor to configure dimensionality reduction via an optional add_linear parameter', 'refactor_BertEncoder_forward': 'refactor the BertEncoder forward method to use CLS token embeddings or pooler output based on configuration'}
```

