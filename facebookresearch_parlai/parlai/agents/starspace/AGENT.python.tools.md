# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/starspace/modules.py

Prompts

```
['build a Starspace model with embedding layers and encoders for sentence pair classification', 'create a forward pass through Starspace encoding input and candidate tensors into embeddings', 'build an Encoder module that computes TF-IDF weighted or mean embeddings from token indices', 'review the Starspace class to understand shared versus separate embedding lookup tables', 'refactor the Encoder forward method to use vectorized TF-IDF weighting instead of a Python loop', 'build a StarspaceAgent for dialogue ranking using the Starspace algorithm with configurable embeddings and optimizers', 'create command-line arguments for StarspaceAgent including embedding type, size, learning rate, margin, and optimizer choices', 'train a StarspaceAgent model using negative sampling, cosine embedding loss, and configurable dropout on input features', 'predict the best response candidate from a list using cosine similarity scoring and ranking', 'save and load a StarspaceAgent model including model state dict, optimizer state, and configuration options']
```

Usage

```
{'build_starspace_model': 'build a Starspace model with embedding layers and encoders for sentence pair classification', 'create_starspace_forward': 'create a forward pass through Starspace encoding input and candidate tensors into embeddings', 'build_encoder_module': 'build an Encoder module that computes TF-IDF weighted or mean embeddings from token indices', 'review_starspace_embeddings': 'review the Starspace class to understand shared versus separate embedding lookup tables', 'refactor_encoder_tfidf': 'refactor the Encoder forward method to use vectorized TF-IDF weighting instead of a Python loop'}
```

## File: facebookresearch_parlai/parlai/agents/starspace/starspace.py

Prompts

```
['build a Starspace model with embedding layers and encoders for sentence pair classification', 'create a forward pass through Starspace encoding input and candidate tensors into embeddings', 'build an Encoder module that computes TF-IDF weighted or mean embeddings from token indices', 'review the Starspace class to understand shared versus separate embedding lookup tables', 'refactor the Encoder forward method to use vectorized TF-IDF weighting instead of a Python loop', 'build a StarspaceAgent for dialogue ranking using the Starspace algorithm with configurable embeddings and optimizers', 'create command-line arguments for StarspaceAgent including embedding type, size, learning rate, margin, and optimizer choices', 'train a StarspaceAgent model using negative sampling, cosine embedding loss, and configurable dropout on input features', 'predict the best response candidate from a list using cosine similarity scoring and ranking', 'save and load a StarspaceAgent model including model state dict, optimizer state, and configuration options']
```

Usage

```
{'build_starspace_agent': 'build a StarspaceAgent for dialogue ranking using the Starspace algorithm with configurable embeddings and optimizers', 'create_cmdline_args': 'create command-line arguments for StarspaceAgent including embedding type, size, learning rate, margin, and optimizer choices', 'train_starspace_model': 'train a StarspaceAgent model using negative sampling, cosine embedding loss, and configurable dropout on input features', 'predict_candidates': 'predict the best response candidate from a list using cosine similarity scoring and ranking', 'save_load_model': 'save and load a StarspaceAgent model including model state dict, optimizer state, and configuration options'}
```

