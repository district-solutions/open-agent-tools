# Agent Python Tools

- repo: facebookresearch/code-prediction-transformer
- repo_uri: https://github.com/facebookresearch/code-prediction-transformer

## File: facebookresearch_code-prediction-transformer/models/trav_trans/dataset.py

Prompts

```
['create a Vocab instance and convert token sequences to index sequences using the vocab2idx mapping', 'collate a batch of sequences into padded input and target tensors for model training', 'create a Dataset instance from a file path and an IDs file path using Setup', 'create a Vocab instance from a vocab file path using the Setup class', 'review the Dataset collate method to understand how sequences are padded and shifted for teacher forcing', 'run generate_ast_ids.py to extract leaf and internal node ids from an AST file', 'run generate_ast_ids.py to extract attr, num, name, and param value ids from an AST file', 'run generate_ast_ids.py to extract call, assign, return, list, dict, and raise type ids from an AST file', 'run generate_ast_ids.py with all id types to extract leaf, value, and type ids from an AST file', 'review the get_leaf_ids function that separates AST nodes into leaf and internal node index lists']
```

Usage

```
{'create_vocab_convert': 'create a Vocab instance and convert token sequences to index sequences using the vocab2idx mapping', 'collate_dataset_sequences': 'collate a batch of sequences into padded input and target tensors for model training', 'setup_create_dataset': 'create a Dataset instance from a file path and an IDs file path using Setup', 'setup_create_vocab': 'create a Vocab instance from a vocab file path using the Setup class', 'review_collate_padding': 'review the Dataset collate method to understand how sequences are padded and shifted for teacher forcing'}
```

## File: facebookresearch_code-prediction-transformer/models/trav_trans/generate_ast_ids.py

Prompts

```
['create a Vocab instance and convert token sequences to index sequences using the vocab2idx mapping', 'collate a batch of sequences into padded input and target tensors for model training', 'create a Dataset instance from a file path and an IDs file path using Setup', 'create a Vocab instance from a vocab file path using the Setup class', 'review the Dataset collate method to understand how sequences are padded and shifted for teacher forcing', 'run generate_ast_ids.py to extract leaf and internal node ids from an AST file', 'run generate_ast_ids.py to extract attr, num, name, and param value ids from an AST file', 'run generate_ast_ids.py to extract call, assign, return, list, dict, and raise type ids from an AST file', 'run generate_ast_ids.py with all id types to extract leaf, value, and type ids from an AST file', 'review the get_leaf_ids function that separates AST nodes into leaf and internal node index lists']
```

Usage

```
{'run_generate_ast_leaf_ids': 'run generate_ast_ids.py to extract leaf and internal node ids from an AST file', 'run_generate_ast_value_ids': 'run generate_ast_ids.py to extract attr, num, name, and param value ids from an AST file', 'run_generate_ast_type_ids': 'run generate_ast_ids.py to extract call, assign, return, list, dict, and raise type ids from an AST file', 'run_generate_ast_all_ids': 'run generate_ast_ids.py with all id types to extract leaf, value, and type ids from an AST file', 'review_get_leaf_ids': 'review the get_leaf_ids function that separates AST nodes into leaf and internal node index lists'}
```

