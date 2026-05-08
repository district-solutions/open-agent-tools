# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/personality_captions/transresnet/modules.py

Prompts

```
['build a TransresnetModel instance with opt, personalities list, and dictionary for image caption encoding', 'run train_batch on the TransresnetModel with image features, personalities, and captions to compute loss', 'run eval_batch on the TransresnetModel to evaluate hits at 1 metrics on a batch of examples', 'run choose_best_caption to select the top k matching captions for given image features and personalities', 'create a LinearWrapper module with input dim, output dim, and dropout for a linear layer with dropout', 'build a TransresnetAgent to generate personality-aware image captions using the ParlAI framework', 'train the TransresnetAgent model on personality captions data with image features and text labels', 'evaluate the TransresnetAgent model using eval_step to rank candidate captions by personality fit', 'save the TransresnetAgent model state dict and dictionary to disk for later loading', 'load a pretrained TransresnetAgent model from a saved checkpoint file path']
```

Usage

```
{'build_TransresnetModel': 'build a TransresnetModel instance with opt, personalities list, and dictionary for image caption encoding', 'run_train_batch': 'run train_batch on the TransresnetModel with image features, personalities, and captions to compute loss', 'run_eval_batch': 'run eval_batch on the TransresnetModel to evaluate hits at 1 metrics on a batch of examples', 'run_choose_best_caption': 'run choose_best_caption to select the top k matching captions for given image features and personalities', 'create_LinearWrapper': 'create a LinearWrapper module with input dim, output dim, and dropout for a linear layer with dropout'}
```

## File: facebookresearch_parlai/projects/personality_captions/transresnet/transresnet.py

Prompts

```
['build a TransresnetModel instance with opt, personalities list, and dictionary for image caption encoding', 'run train_batch on the TransresnetModel with image features, personalities, and captions to compute loss', 'run eval_batch on the TransresnetModel to evaluate hits at 1 metrics on a batch of examples', 'run choose_best_caption to select the top k matching captions for given image features and personalities', 'create a LinearWrapper module with input dim, output dim, and dropout for a linear layer with dropout', 'build a TransresnetAgent to generate personality-aware image captions using the ParlAI framework', 'train the TransresnetAgent model on personality captions data with image features and text labels', 'evaluate the TransresnetAgent model using eval_step to rank candidate captions by personality fit', 'save the TransresnetAgent model state dict and dictionary to disk for later loading', 'load a pretrained TransresnetAgent model from a saved checkpoint file path']
```

Usage

```
{'build_transresnet_agent': 'build a TransresnetAgent to generate personality-aware image captions using the ParlAI framework', 'train_transresnet_model': 'train the TransresnetAgent model on personality captions data with image features and text labels', 'evaluate_transresnet_model': 'evaluate the TransresnetAgent model using eval_step to rank candidate captions by personality fit', 'save_transresnet_model': 'save the TransresnetAgent model state dict and dictionary to disk for later loading', 'load_transresnet_model': 'load a pretrained TransresnetAgent model from a saved checkpoint file path'}
```

