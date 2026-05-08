# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/image_chat/transresnet_multimodal/modules.py

Prompts

```
['build a TransresnetMultimodalModel with image, personality, and dialogue history encoders for multimodal response retrieval', 'run the forward pass on image features, personalities, dialogue histories, and labels to compute loss', 'choose the best k candidate responses given image features, personalities, and dialogue histories', 'run the MultimodalCombiner forward pass to combine multimodal encodings through transformer layers with positional embeddings', 'compute the contrastive loss between total encoded representations and label encodings using dot products', 'build a TransresnetMultimodalAgent to predict next utterance given an image, personality, and dialogue history', 'run a training step on the TransresnetMultimodalAgent with image features, personalities, and dialogue histories', 'run an evaluation step on the TransresnetMultimodalAgent to rank candidate responses and compute loss', 'review the TransresnetMultimodalAgent batch_act method to understand how it handles training and evaluation batches', 'summarize the extract_texts method that parses personalities and dialogue histories from observations']
```

Usage

```
{'build_TransresnetMultimodalModel': 'build a TransresnetMultimodalModel with image, personality, and dialogue history encoders for multimodal response retrieval', 'forward_TransresnetMultimodalModel': 'run the forward pass on image features, personalities, dialogue histories, and labels to compute loss', 'choose_best_response_TransresnetMultimodalModel': 'choose the best k candidate responses given image features, personalities, and dialogue histories', 'forward_MultimodalCombiner': 'run the MultimodalCombiner forward pass to combine multimodal encodings through transformer layers with positional embeddings', 'get_loss_TransresnetMultimodalModel': 'compute the contrastive loss between total encoded representations and label encodings using dot products'}
```

## File: facebookresearch_parlai/projects/image_chat/transresnet_multimodal/transresnet_multimodal.py

Prompts

```
['build a TransresnetMultimodalModel with image, personality, and dialogue history encoders for multimodal response retrieval', 'run the forward pass on image features, personalities, dialogue histories, and labels to compute loss', 'choose the best k candidate responses given image features, personalities, and dialogue histories', 'run the MultimodalCombiner forward pass to combine multimodal encodings through transformer layers with positional embeddings', 'compute the contrastive loss between total encoded representations and label encodings using dot products', 'build a TransresnetMultimodalAgent to predict next utterance given an image, personality, and dialogue history', 'run a training step on the TransresnetMultimodalAgent with image features, personalities, and dialogue histories', 'run an evaluation step on the TransresnetMultimodalAgent to rank candidate responses and compute loss', 'review the TransresnetMultimodalAgent batch_act method to understand how it handles training and evaluation batches', 'summarize the extract_texts method that parses personalities and dialogue histories from observations']
```

Usage

```
{'build_transresnet_multimodal_agent': 'build a TransresnetMultimodalAgent to predict next utterance given an image, personality, and dialogue history', 'run_train_step': 'run a training step on the TransresnetMultimodalAgent with image features, personalities, and dialogue histories', 'run_eval_step': 'run an evaluation step on the TransresnetMultimodalAgent to rank candidate responses and compute loss', 'review_batch_act': 'review the TransresnetMultimodalAgent batch_act method to understand how it handles training and evaluation batches', 'summarize_extract_texts': 'summarize the extract_texts method that parses personalities and dialogue histories from observations'}
```

