# Agent Python Tools

- repo: facebookresearch/rpgkdd2025
- repo_uri: https://github.com/facebookresearch/rpg_kdd2025

## File: facebookresearch_rpgkdd2025/genrec/models/RPG/model.py

Prompts

```
['create an RPG model instance with config, dataset, and tokenizer for recommendation tasks', 'run the RPG model forward pass on a batch to compute final states and loss', 'build an item-item similarity matrix using token embeddings and cosine similarity', 'generate top-k item recommendations from a batch using the RPG model', 'initialize the decoding graph by building adjacency list from item similarity matrix', 'build a python module that initializes an RPGTokenizer with a config dict and AbstractDataset to map items to semantic tokens', 'create a function that encodes sentence embeddings using SentenceTransformer or OpenAI and saves them to a binary file', 'test the RPGTokenizer tokenize_function method to convert item sequences into input_ids, attention_mask, labels, and seq_lens', 'refactor the _generate_semantic_id_opq method to train a FAISS OPQ index on sentence embeddings and produce semantic IDs', 'summarize the RPGTokenizer tokenize method that maps all dataset splits into tokenized HuggingFace datasets with torch format']
```

Usage

```
{'create_RPG_model': 'create an RPG model instance with config, dataset, and tokenizer for recommendation tasks', 'run_RPG_forward': 'run the RPG model forward pass on a batch to compute final states and loss', 'build_item_similarity_matrix': 'build an item-item similarity matrix using token embeddings and cosine similarity', 'generate_recommendations': 'generate top-k item recommendations from a batch using the RPG model', 'init_graph_decoding': 'initialize the decoding graph by building adjacency list from item similarity matrix'}
```

## File: facebookresearch_rpgkdd2025/genrec/models/RPG/tokenizer.py

Prompts

```
['create an RPG model instance with config, dataset, and tokenizer for recommendation tasks', 'run the RPG model forward pass on a batch to compute final states and loss', 'build an item-item similarity matrix using token embeddings and cosine similarity', 'generate top-k item recommendations from a batch using the RPG model', 'initialize the decoding graph by building adjacency list from item similarity matrix', 'build a python module that initializes an RPGTokenizer with a config dict and AbstractDataset to map items to semantic tokens', 'create a function that encodes sentence embeddings using SentenceTransformer or OpenAI and saves them to a binary file', 'test the RPGTokenizer tokenize_function method to convert item sequences into input_ids, attention_mask, labels, and seq_lens', 'refactor the _generate_semantic_id_opq method to train a FAISS OPQ index on sentence embeddings and produce semantic IDs', 'summarize the RPGTokenizer tokenize method that maps all dataset splits into tokenized HuggingFace datasets with torch format']
```

Usage

```
{'build_RPGTokenizer': 'build a python module that initializes an RPGTokenizer with a config dict and AbstractDataset to map items to semantic tokens', 'create_encode_sent_emb': 'create a function that encodes sentence embeddings using SentenceTransformer or OpenAI and saves them to a binary file', 'test_tokenize_function': 'test the RPGTokenizer tokenize_function method to convert item sequences into input_ids, attention_mask, labels, and seq_lens', 'refactor_generate_semantic_id_opq': 'refactor the _generate_semantic_id_opq method to train a FAISS OPQ index on sentence embeddings and produce semantic IDs', 'summarize_tokenize': 'summarize the RPGTokenizer tokenize method that maps all dataset splits into tokenized HuggingFace datasets with torch format'}
```

