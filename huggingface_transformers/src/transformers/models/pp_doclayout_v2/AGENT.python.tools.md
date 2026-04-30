# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pp_doclayout_v2/image_processing_pp_doclayout_v2.py

Prompts

```
['create a PPDocLayoutV2ImageProcessor instance for preprocessing document layout images', 'preprocess a list of torch tensors with resize, center crop, rescale, normalize and pad options', 'run post_process_object_detection to convert raw model outputs into final bounding boxes with scores and labels', 'run _get_order_seqs to compute order sequences from stacked order logits using sigmoid and ranking', 'review the PPDocLayoutV2ImageProcessor class that extends TorchvisionBackend for document layout image processing', 'create a PPDocLayoutV2ForObjectDetection model from a PPDocLayoutV2Config for document layout detection with reading order', 'build a PPDocLayoutV2Config with custom encoder decoder and reading order settings for document layout analysis', 'run PPDocLayoutV2ForObjectDetection forward pass on pixel values to get bounding boxes and reading order logits', 'create a PPDocLayoutV2Model encoder-decoder backbone without detection heads for feature extraction', 'create a PPDocLayoutV2ReadingOrder model that predicts reading order from layout bounding boxes and labels', 'post-process PPDocLayoutV2ForObjectDetection output with image processor to get scored bounding boxes with reading order sequences']
```

Usage

```
{'create_PPDocLayoutV2ImageProcessor': 'create a PPDocLayoutV2ImageProcessor instance for preprocessing document layout images', 'preprocess_PPDocLayoutV2ImageProcessor': 'preprocess a list of torch tensors with resize, center crop, rescale, normalize and pad options', 'run_post_process_object_detection': 'run post_process_object_detection to convert raw model outputs into final bounding boxes with scores and labels', 'run_get_order_seqs': 'run _get_order_seqs to compute order sequences from stacked order logits using sigmoid and ranking', 'review_PPDocLayoutV2ImageProcessor': 'review the PPDocLayoutV2ImageProcessor class that extends TorchvisionBackend for document layout image processing'}
```

## File: huggingface_transformers/src/transformers/models/pp_doclayout_v2/modeling_pp_doclayout_v2.py

Prompts

```
['create a PPDocLayoutV2ImageProcessor instance for preprocessing document layout images', 'preprocess a list of torch tensors with resize, center crop, rescale, normalize and pad options', 'run post_process_object_detection to convert raw model outputs into final bounding boxes with scores and labels', 'run _get_order_seqs to compute order sequences from stacked order logits using sigmoid and ranking', 'review the PPDocLayoutV2ImageProcessor class that extends TorchvisionBackend for document layout image processing', 'create a PPDocLayoutV2ForObjectDetection model from a PPDocLayoutV2Config for document layout detection with reading order', 'build a PPDocLayoutV2Config with custom encoder decoder and reading order settings for document layout analysis', 'run PPDocLayoutV2ForObjectDetection forward pass on pixel values to get bounding boxes and reading order logits', 'create a PPDocLayoutV2Model encoder-decoder backbone without detection heads for feature extraction', 'create a PPDocLayoutV2ReadingOrder model that predicts reading order from layout bounding boxes and labels', 'post-process PPDocLayoutV2ForObjectDetection output with image processor to get scored bounding boxes with reading order sequences']
```

Usage

```
{'create_pp_doclayout_v2_model': 'create a PPDocLayoutV2ForObjectDetection model from a PPDocLayoutV2Config for document layout detection with reading order', 'build_pp_doclayout_v2_config': 'build a PPDocLayoutV2Config with custom encoder decoder and reading order settings for document layout analysis', 'run_pp_doclayout_v2_detection': 'run PPDocLayoutV2ForObjectDetection forward pass on pixel values to get bounding boxes and reading order logits', 'create_pp_doclayout_v2_base_model': 'create a PPDocLayoutV2Model encoder-decoder backbone without detection heads for feature extraction', 'create_pp_doclayout_v2_reading_order': 'create a PPDocLayoutV2ReadingOrder model that predicts reading order from layout bounding boxes and labels'}
```

## File: huggingface_transformers/src/transformers/models/pp_doclayout_v2/modular_pp_doclayout_v2.py

Prompts

```
['create a PPDocLayoutV2ImageProcessor instance for preprocessing document layout images', 'preprocess a list of torch tensors with resize, center crop, rescale, normalize and pad options', 'run post_process_object_detection to convert raw model outputs into final bounding boxes with scores and labels', 'run _get_order_seqs to compute order sequences from stacked order logits using sigmoid and ranking', 'review the PPDocLayoutV2ImageProcessor class that extends TorchvisionBackend for document layout image processing', 'create a PPDocLayoutV2ForObjectDetection model from a PPDocLayoutV2Config for document layout detection with reading order', 'build a PPDocLayoutV2Config with custom encoder decoder and reading order settings for document layout analysis', 'run PPDocLayoutV2ForObjectDetection forward pass on pixel values to get bounding boxes and reading order logits', 'create a PPDocLayoutV2Model encoder-decoder backbone without detection heads for feature extraction', 'create a PPDocLayoutV2ReadingOrder model that predicts reading order from layout bounding boxes and labels', 'post-process PPDocLayoutV2ForObjectDetection output with image processor to get scored bounding boxes with reading order sequences']
```

Usage

```
{'create_pp_doclayout_v2_model': 'create a PPDocLayoutV2ForObjectDetection model from a PPDocLayoutV2Config for document layout detection with reading order', 'build_pp_doclayout_v2_config': 'build a PPDocLayoutV2Config with custom encoder decoder and reading order settings for document layout analysis', 'run_pp_doclayout_v2_detection': 'run PPDocLayoutV2ForObjectDetection forward pass on pixel values to get bounding boxes and reading order logits', 'post_process_pp_doclayout_v2_output': 'post-process PPDocLayoutV2ForObjectDetection output with image processor to get scored bounding boxes with reading order sequences', 'create_pp_doclayout_v2_reading_order': 'create a PPDocLayoutV2ReadingOrder model that predicts reading order from layout bounding boxes and labels using GlobalPointer'}
```

