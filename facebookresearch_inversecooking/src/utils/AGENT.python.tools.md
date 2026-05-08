# Agent Python Tools

- repo: facebookresearch/inversecooking
- repo_uri: https://github.com/facebookresearch/inversecooking

## File: facebookresearch_inversecooking/src/utils/ims2file.py

Prompts

```
['build LMDB databases from Recipe1M dataset images across train, val, and test splits using the CLI', 'create a function that loads an image, resizes and center crops it to a specified scale', 'test the LMDB pipeline by retrieving a stored image and verifying its shape', 'run the CLI to convert Recipe1M dataset images into LMDB format with configurable image scale', 'review the load_and_resize function that applies Resize and CenterCrop transforms to images', 'create a MaskedCrossEntropyCriterion loss function that ignores specified padding indices during forward pass', 'compute the soft IoU score between predicted outputs and target tensors with configurable sum axis', 'update error type counters tracking true positives, false positives, and false negatives from predictions', 'compute accuracy, jaccard, dice, and f1 metrics from accumulated error type counts', 'review the MaskedCrossEntropyCriterion forward method that applies log softmax and gathers NLL loss', 'prepare output from generated recipe token ids and ingredient ids using vocabularies and validate diversity', 'get recipe tokens by converting a list of token ids into words using a vocabulary', 'get ingredient names from a list of ingredient ids using an ingredient vocabulary list', 'prettify a list of recipe tokens into readable sentences with proper capitalization and spacing', 'colorize a list of generated ingredients green if in ground truth or red if not', 'create a Visualizer instance to log TensorBoard summaries to a checkpoints directory', 'log a grid of images to TensorBoard using the image_summary method', 'log ingredient or recipe text predictions and ground truth to TensorBoard', 'log scalar loss values and metrics to TensorBoard using scalar_summary', 'log a histogram of model parameters to TensorBoard using histo_summary']
```

Usage

```
{'build_lmdb_from_images': 'build LMDB databases from Recipe1M dataset images across train, val, and test splits using the CLI', 'create_image_resize_pipeline': 'create a function that loads an image, resizes and center crops it to a specified scale', 'test_lmdb_image_retrieval': 'test the LMDB pipeline by retrieving a stored image and verifying its shape', 'run_image_to_lmdb_conversion': 'run the CLI to convert Recipe1M dataset images into LMDB format with configurable image scale', 'review_load_and_resize': 'review the load_and_resize function that applies Resize and CenterCrop transforms to images'}
```

## File: facebookresearch_inversecooking/src/utils/metrics.py

Prompts

```
['build LMDB databases from Recipe1M dataset images across train, val, and test splits using the CLI', 'create a function that loads an image, resizes and center crops it to a specified scale', 'test the LMDB pipeline by retrieving a stored image and verifying its shape', 'run the CLI to convert Recipe1M dataset images into LMDB format with configurable image scale', 'review the load_and_resize function that applies Resize and CenterCrop transforms to images', 'create a MaskedCrossEntropyCriterion loss function that ignores specified padding indices during forward pass', 'compute the soft IoU score between predicted outputs and target tensors with configurable sum axis', 'update error type counters tracking true positives, false positives, and false negatives from predictions', 'compute accuracy, jaccard, dice, and f1 metrics from accumulated error type counts', 'review the MaskedCrossEntropyCriterion forward method that applies log softmax and gathers NLL loss', 'prepare output from generated recipe token ids and ingredient ids using vocabularies and validate diversity', 'get recipe tokens by converting a list of token ids into words using a vocabulary', 'get ingredient names from a list of ingredient ids using an ingredient vocabulary list', 'prettify a list of recipe tokens into readable sentences with proper capitalization and spacing', 'colorize a list of generated ingredients green if in ground truth or red if not', 'create a Visualizer instance to log TensorBoard summaries to a checkpoints directory', 'log a grid of images to TensorBoard using the image_summary method', 'log ingredient or recipe text predictions and ground truth to TensorBoard', 'log scalar loss values and metrics to TensorBoard using scalar_summary', 'log a histogram of model parameters to TensorBoard using histo_summary']
```

Usage

```
{'create_masked_cross_entropy_criterion': 'create a MaskedCrossEntropyCriterion loss function that ignores specified padding indices during forward pass', 'compute_soft_iou': 'compute the soft IoU score between predicted outputs and target tensors with configurable sum axis', 'update_error_types': 'update error type counters tracking true positives, false positives, and false negatives from predictions', 'compute_metrics': 'compute accuracy, jaccard, dice, and f1 metrics from accumulated error type counts', 'review_maskedcrossentropycriterion_forward': 'review the MaskedCrossEntropyCriterion forward method that applies log softmax and gathers NLL loss'}
```

## File: facebookresearch_inversecooking/src/utils/output_utils.py

Prompts

```
['build LMDB databases from Recipe1M dataset images across train, val, and test splits using the CLI', 'create a function that loads an image, resizes and center crops it to a specified scale', 'test the LMDB pipeline by retrieving a stored image and verifying its shape', 'run the CLI to convert Recipe1M dataset images into LMDB format with configurable image scale', 'review the load_and_resize function that applies Resize and CenterCrop transforms to images', 'create a MaskedCrossEntropyCriterion loss function that ignores specified padding indices during forward pass', 'compute the soft IoU score between predicted outputs and target tensors with configurable sum axis', 'update error type counters tracking true positives, false positives, and false negatives from predictions', 'compute accuracy, jaccard, dice, and f1 metrics from accumulated error type counts', 'review the MaskedCrossEntropyCriterion forward method that applies log softmax and gathers NLL loss', 'prepare output from generated recipe token ids and ingredient ids using vocabularies and validate diversity', 'get recipe tokens by converting a list of token ids into words using a vocabulary', 'get ingredient names from a list of ingredient ids using an ingredient vocabulary list', 'prettify a list of recipe tokens into readable sentences with proper capitalization and spacing', 'colorize a list of generated ingredients green if in ground truth or red if not', 'create a Visualizer instance to log TensorBoard summaries to a checkpoints directory', 'log a grid of images to TensorBoard using the image_summary method', 'log ingredient or recipe text predictions and ground truth to TensorBoard', 'log scalar loss values and metrics to TensorBoard using scalar_summary', 'log a histogram of model parameters to TensorBoard using histo_summary']
```

Usage

```
{'prepare_output_recipe': 'prepare output from generated recipe token ids and ingredient ids using vocabularies and validate diversity', 'get_recipe_tokens': 'get recipe tokens by converting a list of token ids into words using a vocabulary', 'get_ingredients': 'get ingredient names from a list of ingredient ids using an ingredient vocabulary list', 'prettify_recipe_text': 'prettify a list of recipe tokens into readable sentences with proper capitalization and spacing', 'colorize_ingredient_list': 'colorize a list of generated ingredients green if in ground truth or red if not'}
```

## File: facebookresearch_inversecooking/src/utils/tb_visualizer.py

Prompts

```
['build LMDB databases from Recipe1M dataset images across train, val, and test splits using the CLI', 'create a function that loads an image, resizes and center crops it to a specified scale', 'test the LMDB pipeline by retrieving a stored image and verifying its shape', 'run the CLI to convert Recipe1M dataset images into LMDB format with configurable image scale', 'review the load_and_resize function that applies Resize and CenterCrop transforms to images', 'create a MaskedCrossEntropyCriterion loss function that ignores specified padding indices during forward pass', 'compute the soft IoU score between predicted outputs and target tensors with configurable sum axis', 'update error type counters tracking true positives, false positives, and false negatives from predictions', 'compute accuracy, jaccard, dice, and f1 metrics from accumulated error type counts', 'review the MaskedCrossEntropyCriterion forward method that applies log softmax and gathers NLL loss', 'prepare output from generated recipe token ids and ingredient ids using vocabularies and validate diversity', 'get recipe tokens by converting a list of token ids into words using a vocabulary', 'get ingredient names from a list of ingredient ids using an ingredient vocabulary list', 'prettify a list of recipe tokens into readable sentences with proper capitalization and spacing', 'colorize a list of generated ingredients green if in ground truth or red if not', 'create a Visualizer instance to log TensorBoard summaries to a checkpoints directory', 'log a grid of images to TensorBoard using the image_summary method', 'log ingredient or recipe text predictions and ground truth to TensorBoard', 'log scalar loss values and metrics to TensorBoard using scalar_summary', 'log a histogram of model parameters to TensorBoard using histo_summary']
```

Usage

```
{'create_visualizer': 'create a Visualizer instance to log TensorBoard summaries to a checkpoints directory', 'log_image_summary': 'log a grid of images to TensorBoard using the image_summary method', 'log_text_summary': 'log ingredient or recipe text predictions and ground truth to TensorBoard', 'log_scalar_summary': 'log scalar loss values and metrics to TensorBoard using scalar_summary', 'log_histogram_summary': 'log a histogram of model parameters to TensorBoard using histo_summary'}
```

