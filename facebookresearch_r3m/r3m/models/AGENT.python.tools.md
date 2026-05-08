# Agent Python Tools

- repo: facebookresearch/r3m
- repo_uri: https://github.com/facebookresearch/r3m

## File: facebookresearch_r3m/r3m/models/models_language.py

Prompts

```
['build a LangEncoder that loads distilbert-base-uncased and encodes language inputs into 768-dim embeddings', 'run the LangEncoder forward pass to tokenize and embed a list of language strings', 'build a LanguageReward network that predicts reward from concatenated start, goal, and language embeddings', 'run the LanguageReward forward pass with start embedding, goal embedding, and language embedding tensors', 'review the LangEncoder and LanguageReward classes for language embedding and reward prediction in R3M', 'create an R3M model with a ResNet34 visual encoder and language reward on a given device', 'run the R3M forward pass to encode image observations into feature representations', 'get the language-based reward from start and end state embeddings using sentence descriptions', 'compute the similarity between two embedding tensors using L2 distance or cosine similarity', 'review the R3M model initialization to understand ResNet size options and language weight configuration']
```

Usage

```
{'build_LangEncoder': 'build a LangEncoder that loads distilbert-base-uncased and encodes language inputs into 768-dim embeddings', 'run_LangEncoder_forward': 'run the LangEncoder forward pass to tokenize and embed a list of language strings', 'build_LanguageReward': 'build a LanguageReward network that predicts reward from concatenated start, goal, and language embeddings', 'run_LanguageReward_forward': 'run the LanguageReward forward pass with start embedding, goal embedding, and language embedding tensors', 'review_LangEncoder_LanguageReward': 'review the LangEncoder and LanguageReward classes for language embedding and reward prediction in R3M'}
```

## File: facebookresearch_r3m/r3m/models/models_r3m.py

Prompts

```
['build a LangEncoder that loads distilbert-base-uncased and encodes language inputs into 768-dim embeddings', 'run the LangEncoder forward pass to tokenize and embed a list of language strings', 'build a LanguageReward network that predicts reward from concatenated start, goal, and language embeddings', 'run the LanguageReward forward pass with start embedding, goal embedding, and language embedding tensors', 'review the LangEncoder and LanguageReward classes for language embedding and reward prediction in R3M', 'create an R3M model with a ResNet34 visual encoder and language reward on a given device', 'run the R3M forward pass to encode image observations into feature representations', 'get the language-based reward from start and end state embeddings using sentence descriptions', 'compute the similarity between two embedding tensors using L2 distance or cosine similarity', 'review the R3M model initialization to understand ResNet size options and language weight configuration']
```

Usage

```
{'create_R3M_model': 'create an R3M model with a ResNet34 visual encoder and language reward on a given device', 'run_R3M_forward': 'run the R3M forward pass to encode image observations into feature representations', 'get_R3M_reward': 'get the language-based reward from start and end state embeddings using sentence descriptions', 'compute_R3M_similarity': 'compute the similarity between two embedding tensors using L2 distance or cosine similarity', 'review_R3M_init': 'review the R3M model initialization to understand ResNet size options and language weight configuration'}
```

