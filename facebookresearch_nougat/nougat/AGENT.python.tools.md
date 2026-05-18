# Agent Python Tools

- repo: facebookresearch/nougat
- repo_uri: https://github.com/facebookresearch/nougat.git

## File: facebookresearch_nougat/nougat/metrics.py

Prompts

```
['run the metrics CLI on a JSON results file to compute edit distance, BLEU, and METEOR scores', 'compute edit distance, BLEU, METEOR, precision, recall, and F-measure between predicted and ground truth text', 'split a list of pages into separate text, inline math, display math, and table blocks', 'get aggregated metrics across multiple prediction and ground truth pairs using multiprocessing', 'parse a JSON results file containing predictions and ground truths with optional sample limit', 'run inference on a document image using NougatModel to generate LaTeX token sequences', 'load a pretrained Nougat model from a HuggingFace model path or local directory', 'run a forward pass through NougatModel with image tensors and decoder input IDs for training', 'prepare a PIL image for the Swin encoder by cropping margins, resizing, and padding', 'add special tokens to the BART decoder tokenizer and resize token embeddings', 'postprocess generated text to fix markdown formatting and remove hallucinated references', 'postprocess a list of generated texts with optional multiprocessing support', 'truncate repeating segments at the end of a generated text string', 'convert raw text with latex equations and urls to markdown compatible format', 'remove hallucinated or missing references from generated academic text', 'create a custom albumentations Erosion transform that shrinks white regions using an elliptical kernel', 'create a custom albumentations Dilation transform that expands white regions using an elliptical kernel', 'create a Bitmap transform that replaces pixels below a threshold value with a specified replacement value', 'build a training image augmentation pipeline with erosion, dilation, affine, grid distortion, and noise transforms', 'build a test image normalization pipeline that normalizes with ImageNet stats and converts to PyTorch tensors']
```

Usage

```
{'run_metrics_cli': 'run the metrics CLI on a JSON results file to compute edit distance, BLEU, and METEOR scores', 'compute_metrics_function': 'compute edit distance, BLEU, METEOR, precision, recall, and F-measure between predicted and ground truth text', 'split_text_function': 'split a list of pages into separate text, inline math, display math, and table blocks', 'get_metrics_function': 'get aggregated metrics across multiple prediction and ground truth pairs using multiprocessing', 'get_parser_function': 'parse a JSON results file containing predictions and ground truths with optional sample limit'}
```

## File: facebookresearch_nougat/nougat/model.py

Prompts

```
['run the metrics CLI on a JSON results file to compute edit distance, BLEU, and METEOR scores', 'compute edit distance, BLEU, METEOR, precision, recall, and F-measure between predicted and ground truth text', 'split a list of pages into separate text, inline math, display math, and table blocks', 'get aggregated metrics across multiple prediction and ground truth pairs using multiprocessing', 'parse a JSON results file containing predictions and ground truths with optional sample limit', 'run inference on a document image using NougatModel to generate LaTeX token sequences', 'load a pretrained Nougat model from a HuggingFace model path or local directory', 'run a forward pass through NougatModel with image tensors and decoder input IDs for training', 'prepare a PIL image for the Swin encoder by cropping margins, resizing, and padding', 'add special tokens to the BART decoder tokenizer and resize token embeddings', 'postprocess generated text to fix markdown formatting and remove hallucinated references', 'postprocess a list of generated texts with optional multiprocessing support', 'truncate repeating segments at the end of a generated text string', 'convert raw text with latex equations and urls to markdown compatible format', 'remove hallucinated or missing references from generated academic text', 'create a custom albumentations Erosion transform that shrinks white regions using an elliptical kernel', 'create a custom albumentations Dilation transform that expands white regions using an elliptical kernel', 'create a Bitmap transform that replaces pixels below a threshold value with a specified replacement value', 'build a training image augmentation pipeline with erosion, dilation, affine, grid distortion, and noise transforms', 'build a test image normalization pipeline that normalizes with ImageNet stats and converts to PyTorch tensors']
```

Usage

```
{'run_NougatModel_inference': 'run inference on a document image using NougatModel to generate LaTeX token sequences', 'run_NougatModel_from_pretrained': 'load a pretrained Nougat model from a HuggingFace model path or local directory', 'run_NougatModel_forward': 'run a forward pass through NougatModel with image tensors and decoder input IDs for training', 'run_SwinEncoder_prepare_input': 'prepare a PIL image for the Swin encoder by cropping margins, resizing, and padding', 'run_BARTDecoder_add_special_tokens': 'add special tokens to the BART decoder tokenizer and resize token embeddings'}
```

## File: facebookresearch_nougat/nougat/postprocessing.py

Prompts

```
['run the metrics CLI on a JSON results file to compute edit distance, BLEU, and METEOR scores', 'compute edit distance, BLEU, METEOR, precision, recall, and F-measure between predicted and ground truth text', 'split a list of pages into separate text, inline math, display math, and table blocks', 'get aggregated metrics across multiple prediction and ground truth pairs using multiprocessing', 'parse a JSON results file containing predictions and ground truths with optional sample limit', 'run inference on a document image using NougatModel to generate LaTeX token sequences', 'load a pretrained Nougat model from a HuggingFace model path or local directory', 'run a forward pass through NougatModel with image tensors and decoder input IDs for training', 'prepare a PIL image for the Swin encoder by cropping margins, resizing, and padding', 'add special tokens to the BART decoder tokenizer and resize token embeddings', 'postprocess generated text to fix markdown formatting and remove hallucinated references', 'postprocess a list of generated texts with optional multiprocessing support', 'truncate repeating segments at the end of a generated text string', 'convert raw text with latex equations and urls to markdown compatible format', 'remove hallucinated or missing references from generated academic text', 'create a custom albumentations Erosion transform that shrinks white regions using an elliptical kernel', 'create a custom albumentations Dilation transform that expands white regions using an elliptical kernel', 'create a Bitmap transform that replaces pixels below a threshold value with a specified replacement value', 'build a training image augmentation pipeline with erosion, dilation, affine, grid distortion, and noise transforms', 'build a test image normalization pipeline that normalizes with ImageNet stats and converts to PyTorch tensors']
```

Usage

```
{'postprocess_text': 'postprocess generated text to fix markdown formatting and remove hallucinated references', 'postprocess_batch': 'postprocess a list of generated texts with optional multiprocessing support', 'truncate_repetitions': 'truncate repeating segments at the end of a generated text string', 'markdown_compatible': 'convert raw text with latex equations and urls to markdown compatible format', 'remove_hallucinated_references': 'remove hallucinated or missing references from generated academic text'}
```

## File: facebookresearch_nougat/nougat/transforms.py

Prompts

```
['run the metrics CLI on a JSON results file to compute edit distance, BLEU, and METEOR scores', 'compute edit distance, BLEU, METEOR, precision, recall, and F-measure between predicted and ground truth text', 'split a list of pages into separate text, inline math, display math, and table blocks', 'get aggregated metrics across multiple prediction and ground truth pairs using multiprocessing', 'parse a JSON results file containing predictions and ground truths with optional sample limit', 'run inference on a document image using NougatModel to generate LaTeX token sequences', 'load a pretrained Nougat model from a HuggingFace model path or local directory', 'run a forward pass through NougatModel with image tensors and decoder input IDs for training', 'prepare a PIL image for the Swin encoder by cropping margins, resizing, and padding', 'add special tokens to the BART decoder tokenizer and resize token embeddings', 'postprocess generated text to fix markdown formatting and remove hallucinated references', 'postprocess a list of generated texts with optional multiprocessing support', 'truncate repeating segments at the end of a generated text string', 'convert raw text with latex equations and urls to markdown compatible format', 'remove hallucinated or missing references from generated academic text', 'create a custom albumentations Erosion transform that shrinks white regions using an elliptical kernel', 'create a custom albumentations Dilation transform that expands white regions using an elliptical kernel', 'create a Bitmap transform that replaces pixels below a threshold value with a specified replacement value', 'build a training image augmentation pipeline with erosion, dilation, affine, grid distortion, and noise transforms', 'build a test image normalization pipeline that normalizes with ImageNet stats and converts to PyTorch tensors']
```

Usage

```
{'create_Erosion_transform': 'create a custom albumentations Erosion transform that shrinks white regions using an elliptical kernel', 'create_Dilation_transform': 'create a custom albumentations Dilation transform that expands white regions using an elliptical kernel', 'create_Bitmap_transform': 'create a Bitmap transform that replaces pixels below a threshold value with a specified replacement value', 'build_train_transform_pipeline': 'build a training image augmentation pipeline with erosion, dilation, affine, grid distortion, and noise transforms', 'build_test_transform_pipeline': 'build a test image normalization pipeline that normalizes with ImageNet stats and converts to PyTorch tensors'}
```

