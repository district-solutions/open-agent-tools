# Agent Python Tools

- repo: facebookresearch/clevr-iep
- repo_uri: https://github.com/facebookresearch/clevr-iep

## File: facebookresearch_clevr-iep/iep/data.py

Prompts

```
['create a ClevrDataset from HDF5 question and feature files with optional question family filtering', 'create a ClevrDataLoader that wraps ClevrDataset with automatic HDF5 file management and context support', 'use the clevr_collate function to batch question, image, feature, answer, and program data together', 'filter a ClevrDataset to include only specific question families from the HDF5 question file', 'convert an HDF5 dataset to a PyTorch LongTensor with optional boolean masking support', 'create a PyTorch Embedding layer from a vocab and pretrained word2vec vectors', 'expand an existing embedding layer vocabulary with new tokens and optional word2vec initialization', 'review the convert_pretrained_wordvecs function that maps vocab tokens to pretrained word vectors', 'review the expand_embedding_vocab function that grows an embedding layer with new tokens', 'summarize the embedding utilities module for converting and expanding PyTorch embedding layers', 'tokenize a string into a list of tokens with optional start and end tokens', 'build a vocabulary dictionary from a list of text sequences with minimum token count filtering', 'encode a list of string tokens into integer indices using a vocabulary mapping', 'decode a list of integer indices back into tokens or a delimited string', 'review the SPECIAL_TOKENS dictionary that defines NULL, START, END, and UNK token indices', 'convert a flat program list into a nested tree structure using list_to_tree', 'convert a program tree into prefix notation using tree_to_prefix', 'convert a program tree into postfix notation using tree_to_postfix', 'check if a program list forms a linear chain using is_chain', 'convert a function dict to a string representation using function_to_str', 'load a vocabulary JSON file from disk and build inverse index-to-token mappings for questions, programs, and answers', 'load a PyTorch checkpoint file from disk with all tensors remapped to CPU memory', 'load a Seq2Seq program generator model from a checkpoint file and return the model with its kwargs', 'load a ModuleNet execution engine model from a checkpoint file and return the model with its kwargs', 'invert a dictionary by swapping keys and values to create a reverse lookup mapping']
```

Usage

```
{'create_ClevrDataset': 'create a ClevrDataset from HDF5 question and feature files with optional question family filtering', 'create_ClevrDataLoader': 'create a ClevrDataLoader that wraps ClevrDataset with automatic HDF5 file management and context support', 'use_clevr_collate': 'use the clevr_collate function to batch question, image, feature, answer, and program data together', 'filter_ClevrDataset_by_families': 'filter a ClevrDataset to include only specific question families from the HDF5 question file', 'convert_dataset_to_tensor': 'convert an HDF5 dataset to a PyTorch LongTensor with optional boolean masking support'}
```

## File: facebookresearch_clevr-iep/iep/embedding.py

Prompts

```
['create a ClevrDataset from HDF5 question and feature files with optional question family filtering', 'create a ClevrDataLoader that wraps ClevrDataset with automatic HDF5 file management and context support', 'use the clevr_collate function to batch question, image, feature, answer, and program data together', 'filter a ClevrDataset to include only specific question families from the HDF5 question file', 'convert an HDF5 dataset to a PyTorch LongTensor with optional boolean masking support', 'create a PyTorch Embedding layer from a vocab and pretrained word2vec vectors', 'expand an existing embedding layer vocabulary with new tokens and optional word2vec initialization', 'review the convert_pretrained_wordvecs function that maps vocab tokens to pretrained word vectors', 'review the expand_embedding_vocab function that grows an embedding layer with new tokens', 'summarize the embedding utilities module for converting and expanding PyTorch embedding layers', 'tokenize a string into a list of tokens with optional start and end tokens', 'build a vocabulary dictionary from a list of text sequences with minimum token count filtering', 'encode a list of string tokens into integer indices using a vocabulary mapping', 'decode a list of integer indices back into tokens or a delimited string', 'review the SPECIAL_TOKENS dictionary that defines NULL, START, END, and UNK token indices', 'convert a flat program list into a nested tree structure using list_to_tree', 'convert a program tree into prefix notation using tree_to_prefix', 'convert a program tree into postfix notation using tree_to_postfix', 'check if a program list forms a linear chain using is_chain', 'convert a function dict to a string representation using function_to_str', 'load a vocabulary JSON file from disk and build inverse index-to-token mappings for questions, programs, and answers', 'load a PyTorch checkpoint file from disk with all tensors remapped to CPU memory', 'load a Seq2Seq program generator model from a checkpoint file and return the model with its kwargs', 'load a ModuleNet execution engine model from a checkpoint file and return the model with its kwargs', 'invert a dictionary by swapping keys and values to create a reverse lookup mapping']
```

Usage

```
{'convert_pretrained_wordvecs': 'create a PyTorch Embedding layer from a vocab and pretrained word2vec vectors', 'expand_embedding_vocab': 'expand an existing embedding layer vocabulary with new tokens and optional word2vec initialization', 'review_convert_pretrained_wordvecs': 'review the convert_pretrained_wordvecs function that maps vocab tokens to pretrained word vectors', 'review_expand_embedding_vocab': 'review the expand_embedding_vocab function that grows an embedding layer with new tokens', 'summarize_embedding_utils': 'summarize the embedding utilities module for converting and expanding PyTorch embedding layers'}
```

## File: facebookresearch_clevr-iep/iep/preprocess.py

Prompts

```
['create a ClevrDataset from HDF5 question and feature files with optional question family filtering', 'create a ClevrDataLoader that wraps ClevrDataset with automatic HDF5 file management and context support', 'use the clevr_collate function to batch question, image, feature, answer, and program data together', 'filter a ClevrDataset to include only specific question families from the HDF5 question file', 'convert an HDF5 dataset to a PyTorch LongTensor with optional boolean masking support', 'create a PyTorch Embedding layer from a vocab and pretrained word2vec vectors', 'expand an existing embedding layer vocabulary with new tokens and optional word2vec initialization', 'review the convert_pretrained_wordvecs function that maps vocab tokens to pretrained word vectors', 'review the expand_embedding_vocab function that grows an embedding layer with new tokens', 'summarize the embedding utilities module for converting and expanding PyTorch embedding layers', 'tokenize a string into a list of tokens with optional start and end tokens', 'build a vocabulary dictionary from a list of text sequences with minimum token count filtering', 'encode a list of string tokens into integer indices using a vocabulary mapping', 'decode a list of integer indices back into tokens or a delimited string', 'review the SPECIAL_TOKENS dictionary that defines NULL, START, END, and UNK token indices', 'convert a flat program list into a nested tree structure using list_to_tree', 'convert a program tree into prefix notation using tree_to_prefix', 'convert a program tree into postfix notation using tree_to_postfix', 'check if a program list forms a linear chain using is_chain', 'convert a function dict to a string representation using function_to_str', 'load a vocabulary JSON file from disk and build inverse index-to-token mappings for questions, programs, and answers', 'load a PyTorch checkpoint file from disk with all tensors remapped to CPU memory', 'load a Seq2Seq program generator model from a checkpoint file and return the model with its kwargs', 'load a ModuleNet execution engine model from a checkpoint file and return the model with its kwargs', 'invert a dictionary by swapping keys and values to create a reverse lookup mapping']
```

Usage

```
{'tokenize_string': 'tokenize a string into a list of tokens with optional start and end tokens', 'build_vocab_from_sequences': 'build a vocabulary dictionary from a list of text sequences with minimum token count filtering', 'encode_tokens_to_indices': 'encode a list of string tokens into integer indices using a vocabulary mapping', 'decode_indices_to_tokens': 'decode a list of integer indices back into tokens or a delimited string', 'review_special_tokens': 'review the SPECIAL_TOKENS dictionary that defines NULL, START, END, and UNK token indices'}
```

## File: facebookresearch_clevr-iep/iep/programs.py

Prompts

```
['create a ClevrDataset from HDF5 question and feature files with optional question family filtering', 'create a ClevrDataLoader that wraps ClevrDataset with automatic HDF5 file management and context support', 'use the clevr_collate function to batch question, image, feature, answer, and program data together', 'filter a ClevrDataset to include only specific question families from the HDF5 question file', 'convert an HDF5 dataset to a PyTorch LongTensor with optional boolean masking support', 'create a PyTorch Embedding layer from a vocab and pretrained word2vec vectors', 'expand an existing embedding layer vocabulary with new tokens and optional word2vec initialization', 'review the convert_pretrained_wordvecs function that maps vocab tokens to pretrained word vectors', 'review the expand_embedding_vocab function that grows an embedding layer with new tokens', 'summarize the embedding utilities module for converting and expanding PyTorch embedding layers', 'tokenize a string into a list of tokens with optional start and end tokens', 'build a vocabulary dictionary from a list of text sequences with minimum token count filtering', 'encode a list of string tokens into integer indices using a vocabulary mapping', 'decode a list of integer indices back into tokens or a delimited string', 'review the SPECIAL_TOKENS dictionary that defines NULL, START, END, and UNK token indices', 'convert a flat program list into a nested tree structure using list_to_tree', 'convert a program tree into prefix notation using tree_to_prefix', 'convert a program tree into postfix notation using tree_to_postfix', 'check if a program list forms a linear chain using is_chain', 'convert a function dict to a string representation using function_to_str', 'load a vocabulary JSON file from disk and build inverse index-to-token mappings for questions, programs, and answers', 'load a PyTorch checkpoint file from disk with all tensors remapped to CPU memory', 'load a Seq2Seq program generator model from a checkpoint file and return the model with its kwargs', 'load a ModuleNet execution engine model from a checkpoint file and return the model with its kwargs', 'invert a dictionary by swapping keys and values to create a reverse lookup mapping']
```

Usage

```
{'convert_program_list_to_tree': 'convert a flat program list into a nested tree structure using list_to_tree', 'convert_program_tree_to_prefix': 'convert a program tree into prefix notation using tree_to_prefix', 'convert_program_tree_to_postfix': 'convert a program tree into postfix notation using tree_to_postfix', 'check_if_program_is_chain': 'check if a program list forms a linear chain using is_chain', 'convert_function_to_string': 'convert a function dict to a string representation using function_to_str'}
```

## File: facebookresearch_clevr-iep/iep/utils.py

Prompts

```
['create a ClevrDataset from HDF5 question and feature files with optional question family filtering', 'create a ClevrDataLoader that wraps ClevrDataset with automatic HDF5 file management and context support', 'use the clevr_collate function to batch question, image, feature, answer, and program data together', 'filter a ClevrDataset to include only specific question families from the HDF5 question file', 'convert an HDF5 dataset to a PyTorch LongTensor with optional boolean masking support', 'create a PyTorch Embedding layer from a vocab and pretrained word2vec vectors', 'expand an existing embedding layer vocabulary with new tokens and optional word2vec initialization', 'review the convert_pretrained_wordvecs function that maps vocab tokens to pretrained word vectors', 'review the expand_embedding_vocab function that grows an embedding layer with new tokens', 'summarize the embedding utilities module for converting and expanding PyTorch embedding layers', 'tokenize a string into a list of tokens with optional start and end tokens', 'build a vocabulary dictionary from a list of text sequences with minimum token count filtering', 'encode a list of string tokens into integer indices using a vocabulary mapping', 'decode a list of integer indices back into tokens or a delimited string', 'review the SPECIAL_TOKENS dictionary that defines NULL, START, END, and UNK token indices', 'convert a flat program list into a nested tree structure using list_to_tree', 'convert a program tree into prefix notation using tree_to_prefix', 'convert a program tree into postfix notation using tree_to_postfix', 'check if a program list forms a linear chain using is_chain', 'convert a function dict to a string representation using function_to_str', 'load a vocabulary JSON file from disk and build inverse index-to-token mappings for questions, programs, and answers', 'load a PyTorch checkpoint file from disk with all tensors remapped to CPU memory', 'load a Seq2Seq program generator model from a checkpoint file and return the model with its kwargs', 'load a ModuleNet execution engine model from a checkpoint file and return the model with its kwargs', 'invert a dictionary by swapping keys and values to create a reverse lookup mapping']
```

Usage

```
{'load_vocab': 'load a vocabulary JSON file from disk and build inverse index-to-token mappings for questions, programs, and answers', 'load_cpu': 'load a PyTorch checkpoint file from disk with all tensors remapped to CPU memory', 'load_program_generator': 'load a Seq2Seq program generator model from a checkpoint file and return the model with its kwargs', 'load_execution_engine': 'load a ModuleNet execution engine model from a checkpoint file and return the model with its kwargs', 'invert_dict': 'invert a dictionary by swapping keys and values to create a reverse lookup mapping'}
```

