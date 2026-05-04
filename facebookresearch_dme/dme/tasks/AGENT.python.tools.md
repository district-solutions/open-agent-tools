# Agent Python Tools

- repo: facebookresearch/dme
- repo_uri: https://github.com/facebookresearch/dme

## File: facebookresearch_dme/dme/tasks/base.py

Prompts

```
['create an Adam or SGD optimizer with a ReduceLROnPlateau scheduler from args and model parameters', 'count the total number of trainable parameters in a PyTorch neural network module', "retrieve the current learning rate from a PyTorch optimizer's first parameter group", 'initialize all weights and biases of a PyTorch module using xavier, kaiming, or orthogonal methods', 'normalize a PyTorch tensor along a specified dimension using Lp norm with keepdim expansion', 'build a task that trains an image caption retrieval model using visual sentence embedding loss', 'run the visual sentence embedding loss computation between normalized image and caption feature tensors', 'create a PyTorch model with caption and image encoders for image caption retrieval', 'test the ranker to compute recall at 1, 5, 10 and mean reciprocal rank for image to caption retrieval', 'review the caption encoder that uses SentEncoder and applies L2 normalization to caption features', 'build a LanguageInferenceModel with a SentEncoder and multi-layer classifier for natural language inference', 'run the NaturalLanguageInferenceTask evaluate method to compute accuracy and loss on a data split', 'create a NaturalLanguageInferenceTask instance with args and logger to set up training for NLI', 'review the LanguageInferenceModel forward pass that concatenates premise and hypothesis encodings with difference and product features', 'test the NaturalLanguageInferenceTask batch_forward method to compute cross-entropy loss and track training accuracy', 'build a TextClassificationModel with a SentEncoder and multi-layer classifier for text classification', 'run a TextClassificationTask to train a model using cross entropy loss and batch forward passes', 'evaluate the TextClassificationTask model on a data iterator and report accuracy and loss stats', 'review the batch_forward method to compute loss and track correct predictions per batch', 'refactor the TextClassificationModel classifier head to adjust fc_dim or dropout for better performance']
```

Usage

```
{'get_optimizer_scheduler': 'create an Adam or SGD optimizer with a ReduceLROnPlateau scheduler from args and model parameters', 'count_param_num': 'count the total number of trainable parameters in a PyTorch neural network module', 'get_lr': "retrieve the current learning rate from a PyTorch optimizer's first parameter group", 'nn_init': 'initialize all weights and biases of a PyTorch module using xavier, kaiming, or orthogonal methods', 'normf': 'normalize a PyTorch tensor along a specified dimension using Lp norm with keepdim expansion'}
```

## File: facebookresearch_dme/dme/tasks/img_cap_retrieval.py

Prompts

```
['create an Adam or SGD optimizer with a ReduceLROnPlateau scheduler from args and model parameters', 'count the total number of trainable parameters in a PyTorch neural network module', "retrieve the current learning rate from a PyTorch optimizer's first parameter group", 'initialize all weights and biases of a PyTorch module using xavier, kaiming, or orthogonal methods', 'normalize a PyTorch tensor along a specified dimension using Lp norm with keepdim expansion', 'build a task that trains an image caption retrieval model using visual sentence embedding loss', 'run the visual sentence embedding loss computation between normalized image and caption feature tensors', 'create a PyTorch model with caption and image encoders for image caption retrieval', 'test the ranker to compute recall at 1, 5, 10 and mean reciprocal rank for image to caption retrieval', 'review the caption encoder that uses SentEncoder and applies L2 normalization to caption features', 'build a LanguageInferenceModel with a SentEncoder and multi-layer classifier for natural language inference', 'run the NaturalLanguageInferenceTask evaluate method to compute accuracy and loss on a data split', 'create a NaturalLanguageInferenceTask instance with args and logger to set up training for NLI', 'review the LanguageInferenceModel forward pass that concatenates premise and hypothesis encodings with difference and product features', 'test the NaturalLanguageInferenceTask batch_forward method to compute cross-entropy loss and track training accuracy', 'build a TextClassificationModel with a SentEncoder and multi-layer classifier for text classification', 'run a TextClassificationTask to train a model using cross entropy loss and batch forward passes', 'evaluate the TextClassificationTask model on a data iterator and report accuracy and loss stats', 'review the batch_forward method to compute loss and track correct predictions per batch', 'refactor the TextClassificationModel classifier head to adjust fc_dim or dropout for better performance']
```

Usage

```
{'build_ImageCaptionRetrievalTask': 'build a task that trains an image caption retrieval model using visual sentence embedding loss', 'run_VseLoss': 'run the visual sentence embedding loss computation between normalized image and caption feature tensors', 'create_ImageCaptionRetrievalModel': 'create a PyTorch model with caption and image encoders for image caption retrieval', 'test_ImageCaptionRetrievalRanker': 'test the ranker to compute recall at 1, 5, 10 and mean reciprocal rank for image to caption retrieval', 'review_CaptionEncoder': 'review the caption encoder that uses SentEncoder and applies L2 normalization to caption features'}
```

## File: facebookresearch_dme/dme/tasks/nli.py

Prompts

```
['create an Adam or SGD optimizer with a ReduceLROnPlateau scheduler from args and model parameters', 'count the total number of trainable parameters in a PyTorch neural network module', "retrieve the current learning rate from a PyTorch optimizer's first parameter group", 'initialize all weights and biases of a PyTorch module using xavier, kaiming, or orthogonal methods', 'normalize a PyTorch tensor along a specified dimension using Lp norm with keepdim expansion', 'build a task that trains an image caption retrieval model using visual sentence embedding loss', 'run the visual sentence embedding loss computation between normalized image and caption feature tensors', 'create a PyTorch model with caption and image encoders for image caption retrieval', 'test the ranker to compute recall at 1, 5, 10 and mean reciprocal rank for image to caption retrieval', 'review the caption encoder that uses SentEncoder and applies L2 normalization to caption features', 'build a LanguageInferenceModel with a SentEncoder and multi-layer classifier for natural language inference', 'run the NaturalLanguageInferenceTask evaluate method to compute accuracy and loss on a data split', 'create a NaturalLanguageInferenceTask instance with args and logger to set up training for NLI', 'review the LanguageInferenceModel forward pass that concatenates premise and hypothesis encodings with difference and product features', 'test the NaturalLanguageInferenceTask batch_forward method to compute cross-entropy loss and track training accuracy', 'build a TextClassificationModel with a SentEncoder and multi-layer classifier for text classification', 'run a TextClassificationTask to train a model using cross entropy loss and batch forward passes', 'evaluate the TextClassificationTask model on a data iterator and report accuracy and loss stats', 'review the batch_forward method to compute loss and track correct predictions per batch', 'refactor the TextClassificationModel classifier head to adjust fc_dim or dropout for better performance']
```

Usage

```
{'build_nli_model': 'build a LanguageInferenceModel with a SentEncoder and multi-layer classifier for natural language inference', 'run_nli_evaluation': 'run the NaturalLanguageInferenceTask evaluate method to compute accuracy and loss on a data split', 'create_nli_task': 'create a NaturalLanguageInferenceTask instance with args and logger to set up training for NLI', 'review_nli_forward': 'review the LanguageInferenceModel forward pass that concatenates premise and hypothesis encodings with difference and product features', 'test_nli_batch_forward': 'test the NaturalLanguageInferenceTask batch_forward method to compute cross-entropy loss and track training accuracy'}
```

## File: facebookresearch_dme/dme/tasks/text_classification.py

Prompts

```
['create an Adam or SGD optimizer with a ReduceLROnPlateau scheduler from args and model parameters', 'count the total number of trainable parameters in a PyTorch neural network module', "retrieve the current learning rate from a PyTorch optimizer's first parameter group", 'initialize all weights and biases of a PyTorch module using xavier, kaiming, or orthogonal methods', 'normalize a PyTorch tensor along a specified dimension using Lp norm with keepdim expansion', 'build a task that trains an image caption retrieval model using visual sentence embedding loss', 'run the visual sentence embedding loss computation between normalized image and caption feature tensors', 'create a PyTorch model with caption and image encoders for image caption retrieval', 'test the ranker to compute recall at 1, 5, 10 and mean reciprocal rank for image to caption retrieval', 'review the caption encoder that uses SentEncoder and applies L2 normalization to caption features', 'build a LanguageInferenceModel with a SentEncoder and multi-layer classifier for natural language inference', 'run the NaturalLanguageInferenceTask evaluate method to compute accuracy and loss on a data split', 'create a NaturalLanguageInferenceTask instance with args and logger to set up training for NLI', 'review the LanguageInferenceModel forward pass that concatenates premise and hypothesis encodings with difference and product features', 'test the NaturalLanguageInferenceTask batch_forward method to compute cross-entropy loss and track training accuracy', 'build a TextClassificationModel with a SentEncoder and multi-layer classifier for text classification', 'run a TextClassificationTask to train a model using cross entropy loss and batch forward passes', 'evaluate the TextClassificationTask model on a data iterator and report accuracy and loss stats', 'review the batch_forward method to compute loss and track correct predictions per batch', 'refactor the TextClassificationModel classifier head to adjust fc_dim or dropout for better performance']
```

Usage

```
{'build_text_classification_model': 'build a TextClassificationModel with a SentEncoder and multi-layer classifier for text classification', 'run_text_classification_task': 'run a TextClassificationTask to train a model using cross entropy loss and batch forward passes', 'evaluate_text_classification': 'evaluate the TextClassificationTask model on a data iterator and report accuracy and loss stats', 'review_batch_forward': 'review the batch_forward method to compute loss and track correct predictions per batch', 'refactor_classifier_head': 'refactor the TextClassificationModel classifier head to adjust fc_dim or dropout for better performance'}
```

