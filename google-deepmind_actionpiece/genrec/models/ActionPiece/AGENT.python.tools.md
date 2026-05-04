# Agent Python Tools

- repo: google-deepmind/actionpiece
- repo_uri: https://github.com/google-deepmind/action_piece

## File: google-deepmind_actionpiece/genrec/models/ActionPiece/core.py

Prompts

```
['train an ActionPiece tokenizer on a state corpus to reach a target vocabulary size', 'encode a state sequence into tokens using the trained ActionPiece tokenizer with feature shuffle', 'decode a sequence of tokens back into the most basic features using the ActionPiece tokenizer', 'load a pretrained ActionPiece tokenizer from a saved metadata JSON file with optional vocab size', 'save the trained ActionPiece tokenizer vocabulary and priority data to a JSON metadata file', 'build a T5-based ActionPiece model with configurable layers, heads, and vocabulary size for recommendation tasks', 'run a forward pass through the ActionPiece model with a batch dictionary to get logits and loss', 'generate recommendation sequences using beam search with ensemble ranking and nDCG scoring across multiple beams', 'run beam search on input IDs with configurable max length, number of beams, and return sequences', 'review the beam search step logic that calculates next token scores and selects top tokens for each beam', 'encode sentence embeddings from a dataset using SentenceTransformer and optionally apply PCA dimensionality reduction', 'generate semantic IDs for dataset items using FAISS product quantization on sentence embeddings', 'tokenize item sequences into state sequences using the ActionPiece tokenizer for train, val, or test splits', 'collate a batch of tokenized examples into input_ids, attention_mask, and labels tensors for training', 'encode label sequences into token IDs using the ActionPiece core encoder with caching for faster inference', 'create a LinkedListState node with a state list, head_id, and context flag', 'append a new LinkedListState node to the end of an existing linked list', 'copy a LinkedListState node and all its following nodes into a new chain', 'traverse k steps forward from a LinkedListState node to get the k-th next node', 'convert a LinkedListState chain to a flat list with each node state shuffled']
```

Usage

```
{'train_actionpiece_tokenizer': 'train an ActionPiece tokenizer on a state corpus to reach a target vocabulary size', 'encode_state_sequence': 'encode a state sequence into tokens using the trained ActionPiece tokenizer with feature shuffle', 'decode_token_sequence': 'decode a sequence of tokens back into the most basic features using the ActionPiece tokenizer', 'load_pretrained_actionpiece': 'load a pretrained ActionPiece tokenizer from a saved metadata JSON file with optional vocab size', 'save_actionpiece_metadata': 'save the trained ActionPiece tokenizer vocabulary and priority data to a JSON metadata file'}
```

## File: google-deepmind_actionpiece/genrec/models/ActionPiece/model.py

Prompts

```
['train an ActionPiece tokenizer on a state corpus to reach a target vocabulary size', 'encode a state sequence into tokens using the trained ActionPiece tokenizer with feature shuffle', 'decode a sequence of tokens back into the most basic features using the ActionPiece tokenizer', 'load a pretrained ActionPiece tokenizer from a saved metadata JSON file with optional vocab size', 'save the trained ActionPiece tokenizer vocabulary and priority data to a JSON metadata file', 'build a T5-based ActionPiece model with configurable layers, heads, and vocabulary size for recommendation tasks', 'run a forward pass through the ActionPiece model with a batch dictionary to get logits and loss', 'generate recommendation sequences using beam search with ensemble ranking and nDCG scoring across multiple beams', 'run beam search on input IDs with configurable max length, number of beams, and return sequences', 'review the beam search step logic that calculates next token scores and selects top tokens for each beam', 'encode sentence embeddings from a dataset using SentenceTransformer and optionally apply PCA dimensionality reduction', 'generate semantic IDs for dataset items using FAISS product quantization on sentence embeddings', 'tokenize item sequences into state sequences using the ActionPiece tokenizer for train, val, or test splits', 'collate a batch of tokenized examples into input_ids, attention_mask, and labels tensors for training', 'encode label sequences into token IDs using the ActionPiece core encoder with caching for faster inference', 'create a LinkedListState node with a state list, head_id, and context flag', 'append a new LinkedListState node to the end of an existing linked list', 'copy a LinkedListState node and all its following nodes into a new chain', 'traverse k steps forward from a LinkedListState node to get the k-th next node', 'convert a LinkedListState chain to a flat list with each node state shuffled']
```

Usage

```
{'build_ActionPiece_model': 'build a T5-based ActionPiece model with configurable layers, heads, and vocabulary size for recommendation tasks', 'run_forward_pass': 'run a forward pass through the ActionPiece model with a batch dictionary to get logits and loss', 'generate_recommendations': 'generate recommendation sequences using beam search with ensemble ranking and nDCG scoring across multiple beams', 'run_beam_search': 'run beam search on input IDs with configurable max length, number of beams, and return sequences', 'review_beam_search_step': 'review the beam search step logic that calculates next token scores and selects top tokens for each beam'}
```

## File: google-deepmind_actionpiece/genrec/models/ActionPiece/tokenizer.py

Prompts

```
['train an ActionPiece tokenizer on a state corpus to reach a target vocabulary size', 'encode a state sequence into tokens using the trained ActionPiece tokenizer with feature shuffle', 'decode a sequence of tokens back into the most basic features using the ActionPiece tokenizer', 'load a pretrained ActionPiece tokenizer from a saved metadata JSON file with optional vocab size', 'save the trained ActionPiece tokenizer vocabulary and priority data to a JSON metadata file', 'build a T5-based ActionPiece model with configurable layers, heads, and vocabulary size for recommendation tasks', 'run a forward pass through the ActionPiece model with a batch dictionary to get logits and loss', 'generate recommendation sequences using beam search with ensemble ranking and nDCG scoring across multiple beams', 'run beam search on input IDs with configurable max length, number of beams, and return sequences', 'review the beam search step logic that calculates next token scores and selects top tokens for each beam', 'encode sentence embeddings from a dataset using SentenceTransformer and optionally apply PCA dimensionality reduction', 'generate semantic IDs for dataset items using FAISS product quantization on sentence embeddings', 'tokenize item sequences into state sequences using the ActionPiece tokenizer for train, val, or test splits', 'collate a batch of tokenized examples into input_ids, attention_mask, and labels tensors for training', 'encode label sequences into token IDs using the ActionPiece core encoder with caching for faster inference', 'create a LinkedListState node with a state list, head_id, and context flag', 'append a new LinkedListState node to the end of an existing linked list', 'copy a LinkedListState node and all its following nodes into a new chain', 'traverse k steps forward from a LinkedListState node to get the k-th next node', 'convert a LinkedListState chain to a flat list with each node state shuffled']
```

Usage

```
{'encode_sentence_embeddings': 'encode sentence embeddings from a dataset using SentenceTransformer and optionally apply PCA dimensionality reduction', 'generate_semantic_ids': 'generate semantic IDs for dataset items using FAISS product quantization on sentence embeddings', 'tokenize_item_sequences': 'tokenize item sequences into state sequences using the ActionPiece tokenizer for train, val, or test splits', 'collate_training_batch': 'collate a batch of tokenized examples into input_ids, attention_mask, and labels tensors for training', 'encode_labels': 'encode label sequences into token IDs using the ActionPiece core encoder with caching for faster inference'}
```

## File: google-deepmind_actionpiece/genrec/models/ActionPiece/utils.py

Prompts

```
['train an ActionPiece tokenizer on a state corpus to reach a target vocabulary size', 'encode a state sequence into tokens using the trained ActionPiece tokenizer with feature shuffle', 'decode a sequence of tokens back into the most basic features using the ActionPiece tokenizer', 'load a pretrained ActionPiece tokenizer from a saved metadata JSON file with optional vocab size', 'save the trained ActionPiece tokenizer vocabulary and priority data to a JSON metadata file', 'build a T5-based ActionPiece model with configurable layers, heads, and vocabulary size for recommendation tasks', 'run a forward pass through the ActionPiece model with a batch dictionary to get logits and loss', 'generate recommendation sequences using beam search with ensemble ranking and nDCG scoring across multiple beams', 'run beam search on input IDs with configurable max length, number of beams, and return sequences', 'review the beam search step logic that calculates next token scores and selects top tokens for each beam', 'encode sentence embeddings from a dataset using SentenceTransformer and optionally apply PCA dimensionality reduction', 'generate semantic IDs for dataset items using FAISS product quantization on sentence embeddings', 'tokenize item sequences into state sequences using the ActionPiece tokenizer for train, val, or test splits', 'collate a batch of tokenized examples into input_ids, attention_mask, and labels tensors for training', 'encode label sequences into token IDs using the ActionPiece core encoder with caching for faster inference', 'create a LinkedListState node with a state list, head_id, and context flag', 'append a new LinkedListState node to the end of an existing linked list', 'copy a LinkedListState node and all its following nodes into a new chain', 'traverse k steps forward from a LinkedListState node to get the k-th next node', 'convert a LinkedListState chain to a flat list with each node state shuffled']
```

Usage

```
{'create_linked_list_state_node': 'create a LinkedListState node with a state list, head_id, and context flag', 'append_linked_list_node': 'append a new LinkedListState node to the end of an existing linked list', 'copy_linked_list_chain': 'copy a LinkedListState node and all its following nodes into a new chain', 'traverse_linked_list_nextk': 'traverse k steps forward from a LinkedListState node to get the k-th next node', 'convert_linked_list_to_shuffled_list': 'convert a LinkedListState chain to a flat list with each node state shuffled'}
```

