# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/perceiver/train/autoaugment.py

Prompts

```
['build a python module to apply the v0 AutoAugment policy to an image tensor', 'build a python module to apply RandAugment with N layers and magnitude M to an image', 'create a function that applies a sequence of image augmentation operations from a policy', 'create a function that applies cutout augmentation by masking a random region of the image', 'create a function that solarizes an image by inverting pixels above a threshold', 'load an ImageNet dataset split with preprocessing, augmentation, and batching for training or evaluation', "create a Split enum value from a string like 'TRAIN', 'VALID', or 'TEST'", 'generate a binary image mask for CutMix data augmentation with random patch placement', 'apply mixup augmentation to a batch of images by linearly interpolating pairs of images and labels', 'apply cutmix augmentation to a batch of images by replacing a random patch with another image', 'run the Perceiver training pipeline on ImageNet using jaxline platform with the Experiment class', 'build a training config with optimizer, model, and data settings using get_config for Perceiver IO', 'create an Experiment instance with mode, init_rng, and config to manage Perceiver training state', 'train the Perceiver model for one step using the step method with global_step and rng inputs', 'evaluate the Perceiver model on a test subset using the evaluate method and _eval_epoch', 'build a learning rate schedule with cosine decay warmup using get_learning_rate_schedule', 'calculate top-k accuracy metrics for classification logits and labels using topk_correct', 'compute softmax cross entropy loss from logits and one-hot labels using softmax_cross_entropy', 'create an adam or lamb optimizer with weight decay using make_optimizer and add_weight_decay', 'check if any prediction elements are in target arrays using the vmapped any_in function']
```

Usage

```
{'build_autoaugment_policy': 'build a python module to apply the v0 AutoAugment policy to an image tensor', 'build_randaugment_policy': 'build a python module to apply RandAugment with N layers and magnitude M to an image', 'create_image_augmentation_pipeline': 'create a function that applies a sequence of image augmentation operations from a policy', 'create_cutout_augmentation': 'create a function that applies cutout augmentation by masking a random region of the image', 'create_solarize_augmentation': 'create a function that solarizes an image by inverting pixels above a threshold'}
```

## File: google-deepmind_deepmind-research/perceiver/train/dataset.py

Prompts

```
['build a python module to apply the v0 AutoAugment policy to an image tensor', 'build a python module to apply RandAugment with N layers and magnitude M to an image', 'create a function that applies a sequence of image augmentation operations from a policy', 'create a function that applies cutout augmentation by masking a random region of the image', 'create a function that solarizes an image by inverting pixels above a threshold', 'load an ImageNet dataset split with preprocessing, augmentation, and batching for training or evaluation', "create a Split enum value from a string like 'TRAIN', 'VALID', or 'TEST'", 'generate a binary image mask for CutMix data augmentation with random patch placement', 'apply mixup augmentation to a batch of images by linearly interpolating pairs of images and labels', 'apply cutmix augmentation to a batch of images by replacing a random patch with another image', 'run the Perceiver training pipeline on ImageNet using jaxline platform with the Experiment class', 'build a training config with optimizer, model, and data settings using get_config for Perceiver IO', 'create an Experiment instance with mode, init_rng, and config to manage Perceiver training state', 'train the Perceiver model for one step using the step method with global_step and rng inputs', 'evaluate the Perceiver model on a test subset using the evaluate method and _eval_epoch', 'build a learning rate schedule with cosine decay warmup using get_learning_rate_schedule', 'calculate top-k accuracy metrics for classification logits and labels using topk_correct', 'compute softmax cross entropy loss from logits and one-hot labels using softmax_cross_entropy', 'create an adam or lamb optimizer with weight decay using make_optimizer and add_weight_decay', 'check if any prediction elements are in target arrays using the vmapped any_in function']
```

Usage

```
{'load_imagenet_dataset': 'load an ImageNet dataset split with preprocessing, augmentation, and batching for training or evaluation', 'create_split_from_string': "create a Split enum value from a string like 'TRAIN', 'VALID', or 'TEST'", 'generate_cutmix_mask': 'generate a binary image mask for CutMix data augmentation with random patch placement', 'apply_mixup_augmentation': 'apply mixup augmentation to a batch of images by linearly interpolating pairs of images and labels', 'apply_cutmix_augmentation': 'apply cutmix augmentation to a batch of images by replacing a random patch with another image'}
```

## File: google-deepmind_deepmind-research/perceiver/train/experiment.py

Prompts

```
['build a python module to apply the v0 AutoAugment policy to an image tensor', 'build a python module to apply RandAugment with N layers and magnitude M to an image', 'create a function that applies a sequence of image augmentation operations from a policy', 'create a function that applies cutout augmentation by masking a random region of the image', 'create a function that solarizes an image by inverting pixels above a threshold', 'load an ImageNet dataset split with preprocessing, augmentation, and batching for training or evaluation', "create a Split enum value from a string like 'TRAIN', 'VALID', or 'TEST'", 'generate a binary image mask for CutMix data augmentation with random patch placement', 'apply mixup augmentation to a batch of images by linearly interpolating pairs of images and labels', 'apply cutmix augmentation to a batch of images by replacing a random patch with another image', 'run the Perceiver training pipeline on ImageNet using jaxline platform with the Experiment class', 'build a training config with optimizer, model, and data settings using get_config for Perceiver IO', 'create an Experiment instance with mode, init_rng, and config to manage Perceiver training state', 'train the Perceiver model for one step using the step method with global_step and rng inputs', 'evaluate the Perceiver model on a test subset using the evaluate method and _eval_epoch', 'build a learning rate schedule with cosine decay warmup using get_learning_rate_schedule', 'calculate top-k accuracy metrics for classification logits and labels using topk_correct', 'compute softmax cross entropy loss from logits and one-hot labels using softmax_cross_entropy', 'create an adam or lamb optimizer with weight decay using make_optimizer and add_weight_decay', 'check if any prediction elements are in target arrays using the vmapped any_in function']
```

Usage

```
{'run_perceiver_imagenet_training': 'run the Perceiver training pipeline on ImageNet using jaxline platform with the Experiment class', 'build_training_config': 'build a training config with optimizer, model, and data settings using get_config for Perceiver IO', 'create_experiment_instance': 'create an Experiment instance with mode, init_rng, and config to manage Perceiver training state', 'train_model_step': 'train the Perceiver model for one step using the step method with global_step and rng inputs', 'evaluate_model': 'evaluate the Perceiver model on a test subset using the evaluate method and _eval_epoch'}
```

## File: google-deepmind_deepmind-research/perceiver/train/utils.py

Prompts

```
['build a python module to apply the v0 AutoAugment policy to an image tensor', 'build a python module to apply RandAugment with N layers and magnitude M to an image', 'create a function that applies a sequence of image augmentation operations from a policy', 'create a function that applies cutout augmentation by masking a random region of the image', 'create a function that solarizes an image by inverting pixels above a threshold', 'load an ImageNet dataset split with preprocessing, augmentation, and batching for training or evaluation', "create a Split enum value from a string like 'TRAIN', 'VALID', or 'TEST'", 'generate a binary image mask for CutMix data augmentation with random patch placement', 'apply mixup augmentation to a batch of images by linearly interpolating pairs of images and labels', 'apply cutmix augmentation to a batch of images by replacing a random patch with another image', 'run the Perceiver training pipeline on ImageNet using jaxline platform with the Experiment class', 'build a training config with optimizer, model, and data settings using get_config for Perceiver IO', 'create an Experiment instance with mode, init_rng, and config to manage Perceiver training state', 'train the Perceiver model for one step using the step method with global_step and rng inputs', 'evaluate the Perceiver model on a test subset using the evaluate method and _eval_epoch', 'build a learning rate schedule with cosine decay warmup using get_learning_rate_schedule', 'calculate top-k accuracy metrics for classification logits and labels using topk_correct', 'compute softmax cross entropy loss from logits and one-hot labels using softmax_cross_entropy', 'create an adam or lamb optimizer with weight decay using make_optimizer and add_weight_decay', 'check if any prediction elements are in target arrays using the vmapped any_in function']
```

Usage

```
{'build_lr_schedule': 'build a learning rate schedule with cosine decay warmup using get_learning_rate_schedule', 'calculate_topk_accuracy': 'calculate top-k accuracy metrics for classification logits and labels using topk_correct', 'compute_softmax_cross_entropy': 'compute softmax cross entropy loss from logits and one-hot labels using softmax_cross_entropy', 'create_weight_decay_optimizer': 'create an adam or lamb optimizer with weight decay using make_optimizer and add_weight_decay', 'check_element_membership': 'check if any prediction elements are in target arrays using the vmapped any_in function'}
```

