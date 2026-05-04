# Agent Python Tools

- repo: facebookresearch/diht
- repo_uri: https://github.com/facebookresearch/diht

## File: facebookresearch_diht/example_imagenet_eval.py

Prompts

```
['run zero-shot ImageNet1K evaluation using a DIHT model and print top-1 accuracy', 'run the accuracy function to compute top-k classification accuracy from logits and labels', 'run model_zoo.load_model to load a DIHT model with its tokenizer and image transform', 'run zero-shot classifier extraction by encoding ImageNet class names with text templates', 'run image feature extraction by encoding ImageNet validation images and computing similarity to classifiers', 'run extract_features to get normalized image and text embeddings from a DIHT model and dataloader', 'run evaluate_retrieval to compute image-text similarity scores and recall metrics for a dataset', 'run compute_recall to calculate R@k retrieval recall for image-to-text and text-to-image directions', 'run the main evaluation script to evaluate a DIHT model on COCO and Flickr30K datasets', 'refactor extract_features to use a custom text prompt template instead of the default photo template']
```

Usage

```
{'run_zero_shot_imagenet_eval': 'run zero-shot ImageNet1K evaluation using a DIHT model and print top-1 accuracy', 'run_accuracy_function': 'run the accuracy function to compute top-k classification accuracy from logits and labels', 'run_load_diht_model': 'run model_zoo.load_model to load a DIHT model with its tokenizer and image transform', 'run_extract_zeroshot_classifiers': 'run zero-shot classifier extraction by encoding ImageNet class names with text templates', 'run_extract_image_features': 'run image feature extraction by encoding ImageNet validation images and computing similarity to classifiers'}
```

## File: facebookresearch_diht/example_retrieval_eval.py

Prompts

```
['run zero-shot ImageNet1K evaluation using a DIHT model and print top-1 accuracy', 'run the accuracy function to compute top-k classification accuracy from logits and labels', 'run model_zoo.load_model to load a DIHT model with its tokenizer and image transform', 'run zero-shot classifier extraction by encoding ImageNet class names with text templates', 'run image feature extraction by encoding ImageNet validation images and computing similarity to classifiers', 'run extract_features to get normalized image and text embeddings from a DIHT model and dataloader', 'run evaluate_retrieval to compute image-text similarity scores and recall metrics for a dataset', 'run compute_recall to calculate R@k retrieval recall for image-to-text and text-to-image directions', 'run the main evaluation script to evaluate a DIHT model on COCO and Flickr30K datasets', 'refactor extract_features to use a custom text prompt template instead of the default photo template']
```

Usage

```
{'run_extract_features': 'run extract_features to get normalized image and text embeddings from a DIHT model and dataloader', 'run_evaluate_retrieval': 'run evaluate_retrieval to compute image-text similarity scores and recall metrics for a dataset', 'run_compute_recall': 'run compute_recall to calculate R@k retrieval recall for image-to-text and text-to-image directions', 'run_main_evaluation': 'run the main evaluation script to evaluate a DIHT model on COCO and Flickr30K datasets', 'refactor_extract_features_template': 'refactor extract_features to use a custom text prompt template instead of the default photo template'}
```

