# Agent Python Tools

- repo: facebookresearch/r-mae
- repo_uri: https://github.com/facebookresearch/r-mae

## File: facebookresearch_r-mae/pretrain/dataset/processor/functional.py

Prompts

```
['apply random resize and crop augmentation to an image sample and its bounding box targets', 'apply a center crop to an image sample and adjust its associated target annotations', 'resize an image sample to a target scale and proportionally scale its bounding box targets', 'crop an image region and adjust bounding boxes, masks, and keypoints in the target annotations', 'normalize an image tensor with mean and std values and convert bounding boxes to normalized center format', 'build a processor instance from a config dict with type and params keys using build_processor', 'register a new processor class in the PROCESSOR_REGISTRY using the register_processor decorator', 'compose multiple processor configs into a single Compose processor that applies them in sequence', 'create an AnswerProcessor that loads and normalizes answer strings from a class file into a word list', 'build a RandomSelect processor that randomly chooses between sub-processors based on weighted probabilities']
```

Usage

```
{'random_resize_crop_augmentation': 'apply random resize and crop augmentation to an image sample and its bounding box targets', 'center_crop_image': 'apply a center crop to an image sample and adjust its associated target annotations', 'resize_and_scale_image': 'resize an image sample to a target scale and proportionally scale its bounding box targets', 'crop_and_adjust_targets': 'crop an image region and adjust bounding boxes, masks, and keypoints in the target annotations', 'normalize_and_normalize_boxes': 'normalize an image tensor with mean and std values and convert bounding boxes to normalized center format'}
```

## File: facebookresearch_r-mae/pretrain/dataset/processor/processors.py

Prompts

```
['apply random resize and crop augmentation to an image sample and its bounding box targets', 'apply a center crop to an image sample and adjust its associated target annotations', 'resize an image sample to a target scale and proportionally scale its bounding box targets', 'crop an image region and adjust bounding boxes, masks, and keypoints in the target annotations', 'normalize an image tensor with mean and std values and convert bounding boxes to normalized center format', 'build a processor instance from a config dict with type and params keys using build_processor', 'register a new processor class in the PROCESSOR_REGISTRY using the register_processor decorator', 'compose multiple processor configs into a single Compose processor that applies them in sequence', 'create an AnswerProcessor that loads and normalizes answer strings from a class file into a word list', 'build a RandomSelect processor that randomly chooses between sub-processors based on weighted probabilities']
```

Usage

```
{'build_processor_from_config': 'build a processor instance from a config dict with type and params keys using build_processor', 'register_new_processor': 'register a new processor class in the PROCESSOR_REGISTRY using the register_processor decorator', 'compose_processors': 'compose multiple processor configs into a single Compose processor that applies them in sequence', 'create_answer_processor': 'create an AnswerProcessor that loads and normalizes answer strings from a class file into a word list', 'build_random_select_processor': 'build a RandomSelect processor that randomly chooses between sub-processors based on weighted probabilities'}
```

