# Agent Python Tools

- repo: facebookresearch/code-prediction-transformer
- repo_uri: https://github.com/facebookresearch/code-prediction-transformer

## File: facebookresearch_code-prediction-transformer/models/seq/astunparser.py

Prompts

```
['convert a Python AST tree back into source code using the Unparser class', 'unparse a Python AST into a string by passing a StringIO buffer to Unparser', 'unparse an AST while tracking __future__ imports for correct string literal handling', 'call a function on each item in a sequence with an interleaving function between items', 'dispatch AST node types to their corresponding unparsing methods via the dispatch method', 'create a Setup instance that builds a Vocab and Dataset from filepaths', 'convert a sequence of tokens to vocabulary indices using Vocab.convert', 'collate a batch of sequences into padded input and target tensors with Dataset.collate', 'create a Dataset instance from a file path and an IDs file path', 'create a Vocab instance from a vocabulary file path using Setup._create_vocab', 'run the CLI to generate JSON datapoints from a list of Python source code files', 'parse Python source code into AST tokens and split into fixed-length context windows', 'extract indices of non-None AST node types from a list of token types', 'extract indices of attr, Num, NameStore, NameLoad, and NameParam AST node types', 'transpose a list of SrcASTToken objects into chunked token and type lists']
```

Usage

```
{'unparse_ast_to_source': 'convert a Python AST tree back into source code using the Unparser class', 'unparse_ast_to_string': 'unparse a Python AST into a string by passing a StringIO buffer to Unparser', 'unparse_ast_with_future_imports': 'unparse an AST while tracking __future__ imports for correct string literal handling', 'interleave_helper': 'call a function on each item in a sequence with an interleaving function between items', 'dispatch_ast_nodes': 'dispatch AST node types to their corresponding unparsing methods via the dispatch method'}
```

## File: facebookresearch_code-prediction-transformer/models/seq/dataset.py

Prompts

```
['convert a Python AST tree back into source code using the Unparser class', 'unparse a Python AST into a string by passing a StringIO buffer to Unparser', 'unparse an AST while tracking __future__ imports for correct string literal handling', 'call a function on each item in a sequence with an interleaving function between items', 'dispatch AST node types to their corresponding unparsing methods via the dispatch method', 'create a Setup instance that builds a Vocab and Dataset from filepaths', 'convert a sequence of tokens to vocabulary indices using Vocab.convert', 'collate a batch of sequences into padded input and target tensors with Dataset.collate', 'create a Dataset instance from a file path and an IDs file path', 'create a Vocab instance from a vocabulary file path using Setup._create_vocab', 'run the CLI to generate JSON datapoints from a list of Python source code files', 'parse Python source code into AST tokens and split into fixed-length context windows', 'extract indices of non-None AST node types from a list of token types', 'extract indices of attr, Num, NameStore, NameLoad, and NameParam AST node types', 'transpose a list of SrcASTToken objects into chunked token and type lists']
```

Usage

```
{'create_setup_instance': 'create a Setup instance that builds a Vocab and Dataset from filepaths', 'convert_tokens_to_indices': 'convert a sequence of tokens to vocabulary indices using Vocab.convert', 'collate_batch_sequences': 'collate a batch of sequences into padded input and target tensors with Dataset.collate', 'create_dataset_from_files': 'create a Dataset instance from a file path and an IDs file path', 'create_vocab_from_file': 'create a Vocab instance from a vocabulary file path using Setup._create_vocab'}
```

## File: facebookresearch_code-prediction-transformer/models/seq/generate_data.py

Prompts

```
['convert a Python AST tree back into source code using the Unparser class', 'unparse a Python AST into a string by passing a StringIO buffer to Unparser', 'unparse an AST while tracking __future__ imports for correct string literal handling', 'call a function on each item in a sequence with an interleaving function between items', 'dispatch AST node types to their corresponding unparsing methods via the dispatch method', 'create a Setup instance that builds a Vocab and Dataset from filepaths', 'convert a sequence of tokens to vocabulary indices using Vocab.convert', 'collate a batch of sequences into padded input and target tensors with Dataset.collate', 'create a Dataset instance from a file path and an IDs file path', 'create a Vocab instance from a vocabulary file path using Setup._create_vocab', 'run the CLI to generate JSON datapoints from a list of Python source code files', 'parse Python source code into AST tokens and split into fixed-length context windows', 'extract indices of non-None AST node types from a list of token types', 'extract indices of attr, Num, NameStore, NameLoad, and NameParam AST node types', 'transpose a list of SrcASTToken objects into chunked token and type lists']
```

Usage

```
{'generate_datapoints_from_source': 'run the CLI to generate JSON datapoints from a list of Python source code files', 'tokenize_python_source': 'parse Python source code into AST tokens and split into fixed-length context windows', 'extract_leaf_ids': 'extract indices of non-None AST node types from a list of token types', 'extract_value_ids': 'extract indices of attr, Num, NameStore, NameLoad, and NameParam AST node types', 'transpose_tokens': 'transpose a list of SrcASTToken objects into chunked token and type lists'}
```

