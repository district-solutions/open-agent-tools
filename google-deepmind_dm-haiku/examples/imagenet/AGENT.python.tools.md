# Agent Python Tools

- repo: google-deepmind/dm-haiku
- repo_uri: https://github.com/google-deepmind/dm-haiku

## File: google-deepmind_dm-haiku/examples/imagenet/dataset.py

Prompts

```
['load an ImageNet dataset split with batching, sharding, and preprocessing for training or evaluation', 'double buffer dataset batches on accelerator devices to overlap host to device copies with computation', 'check that tensorflow and tensorflow_datasets meet the minimum required versions for the dataset pipeline', 'create a Split enum from a string like TRAIN, VALID, or TEST to select an ImageNet dataset partition', 'preprocess an ImageNet image with random crop, flip, bicubic resize, and RGB normalization', 'run ResNet50 training on ImageNet2012 using JAX, Haiku, and mixed precision with configurable epochs and batch size', 'run a single pmapped training step that computes gradients, applies optimizer updates, and returns updated TrainState', 'run model evaluation on a dataset split and return top-1 accuracy metrics', 'create a cosine learning rate schedule with warmup steps and linear scaling based on total batch size', 'create an SGD optimizer with Nesterov momentum, weight decay, and a custom learning rate schedule']
```

Usage

```
{'load_imagenet_split': 'load an ImageNet dataset split with batching, sharding, and preprocessing for training or evaluation', 'double_buffer_batches': 'double buffer dataset batches on accelerator devices to overlap host to device copies with computation', 'check_tf_versions': 'check that tensorflow and tensorflow_datasets meet the minimum required versions for the dataset pipeline', 'split_from_string': 'create a Split enum from a string like TRAIN, VALID, or TEST to select an ImageNet dataset partition', 'preprocess_imagenet_image': 'preprocess an ImageNet image with random crop, flip, bicubic resize, and RGB normalization'}
```

## File: google-deepmind_dm-haiku/examples/imagenet/train.py

Prompts

```
['load an ImageNet dataset split with batching, sharding, and preprocessing for training or evaluation', 'double buffer dataset batches on accelerator devices to overlap host to device copies with computation', 'check that tensorflow and tensorflow_datasets meet the minimum required versions for the dataset pipeline', 'create a Split enum from a string like TRAIN, VALID, or TEST to select an ImageNet dataset partition', 'preprocess an ImageNet image with random crop, flip, bicubic resize, and RGB normalization', 'run ResNet50 training on ImageNet2012 using JAX, Haiku, and mixed precision with configurable epochs and batch size', 'run a single pmapped training step that computes gradients, applies optimizer updates, and returns updated TrainState', 'run model evaluation on a dataset split and return top-1 accuracy metrics', 'create a cosine learning rate schedule with warmup steps and linear scaling based on total batch size', 'create an SGD optimizer with Nesterov momentum, weight decay, and a custom learning rate schedule']
```

Usage

```
{'run_resnet50_imagenet_training': 'run ResNet50 training on ImageNet2012 using JAX, Haiku, and mixed precision with configurable epochs and batch size', 'run_train_step': 'run a single pmapped training step that computes gradients, applies optimizer updates, and returns updated TrainState', 'run_evaluate_model': 'run model evaluation on a dataset split and return top-1 accuracy metrics', 'create_lr_schedule': 'create a cosine learning rate schedule with warmup steps and linear scaling based on total batch size', 'create_optimizer': 'create an SGD optimizer with Nesterov momentum, weight decay, and a custom learning rate schedule'}
```

