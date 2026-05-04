# Agent Python Tools

- repo: google-deepmind/dmnevis
- repo_uri: https://github.com/google-deepmind/dm_nevis

## File: google-deepmind_dmnevis/experiments_torch/configs/cheap_finetuning_ind.py

Prompts

```
['get a ConfigDict for an independent finetuning experiment with ResNet18 and SGD optimizer', 'review the get_config function to understand the finetuning learner configuration structure', 'summarize the get_config function and its default hyperparameters for cheap finetuning', 'build a finetuning experiment config using get_config with ResNet18 and warmup cosine decay schedule', 'refactor the get_config function to use a different finetuning strategy or model architecture', 'get the learner config ConfigDict for the example bare-bones Nevis learner experiment', 'test the get_config function to verify it returns a valid ConfigDict with experiment keys', 'customize the train and eval augmentation chains in the finetuning config for image preprocessing', 'configure the SGD optimizer with momentum, Nesterov, and weight decay in the finetuning config', 'set the warmup cosine decay learning rate schedule with init rate and warmup epochs', 'adjust the finetuning strategy to INDEPENDENT mode for per-task train state initialization', 'get the finetuning learner config with ResNet34, SGD optimizer, and warmup cosine decay schedule', 'build a ConfigDict for a continual learning experiment using the PREVIOUS finetuning strategy with ResNet34', 'get the ConfigDict for pretraining a ResNet34 model on ImageNet with SGD and cosine decay', 'build a learner configuration with ResNet34, SGD optimizer, and warmup cosine decay schedule for ImageNet', 'create train and eval augmentation pipelines with random crop, flip, normalize, and central crop', 'configure the finetuning learner builder with an independent strategy for each task', 'set up an SGD optimizer with momentum 0.9 and a warmup cosine decay learning rate schedule']
```

Usage

```
{'get_finetuning_config': 'get a ConfigDict for an independent finetuning experiment with ResNet18 and SGD optimizer', 'review_get_config': 'review the get_config function to understand the finetuning learner configuration structure', 'summarize_get_config': 'summarize the get_config function and its default hyperparameters for cheap finetuning', 'build_finetuning_experiment': 'build a finetuning experiment config using get_config with ResNet18 and warmup cosine decay schedule', 'refactor_get_config': 'refactor the get_config function to use a different finetuning strategy or model architecture'}
```

## File: google-deepmind_dmnevis/experiments_torch/configs/example.py

Prompts

```
['get a ConfigDict for an independent finetuning experiment with ResNet18 and SGD optimizer', 'review the get_config function to understand the finetuning learner configuration structure', 'summarize the get_config function and its default hyperparameters for cheap finetuning', 'build a finetuning experiment config using get_config with ResNet18 and warmup cosine decay schedule', 'refactor the get_config function to use a different finetuning strategy or model architecture', 'get the learner config ConfigDict for the example bare-bones Nevis learner experiment', 'test the get_config function to verify it returns a valid ConfigDict with experiment keys', 'customize the train and eval augmentation chains in the finetuning config for image preprocessing', 'configure the SGD optimizer with momentum, Nesterov, and weight decay in the finetuning config', 'set the warmup cosine decay learning rate schedule with init rate and warmup epochs', 'adjust the finetuning strategy to INDEPENDENT mode for per-task train state initialization', 'get the finetuning learner config with ResNet34, SGD optimizer, and warmup cosine decay schedule', 'build a ConfigDict for a continual learning experiment using the PREVIOUS finetuning strategy with ResNet34', 'get the ConfigDict for pretraining a ResNet34 model on ImageNet with SGD and cosine decay', 'build a learner configuration with ResNet34, SGD optimizer, and warmup cosine decay schedule for ImageNet', 'create train and eval augmentation pipelines with random crop, flip, normalize, and central crop', 'configure the finetuning learner builder with an independent strategy for each task', 'set up an SGD optimizer with momentum 0.9 and a warmup cosine decay learning rate schedule']
```

Usage

```
{'get_config': 'get the learner config ConfigDict for the example bare-bones Nevis learner experiment', 'review_get_config': 'review the get_config function to understand the experiment stream and learner builder setup', 'summarize_get_config': 'summarize the get_config function and its use of NevisStream and example_learner builder', 'refactor_get_config': 'refactor the get_config function to use a different stream variant or learner builder', 'test_get_config': 'test the get_config function to verify it returns a valid ConfigDict with experiment keys'}
```

## File: google-deepmind_dmnevis/experiments_torch/configs/finetuning_ind.py

Prompts

```
['get a ConfigDict for an independent finetuning experiment with ResNet18 and SGD optimizer', 'review the get_config function to understand the finetuning learner configuration structure', 'summarize the get_config function and its default hyperparameters for cheap finetuning', 'build a finetuning experiment config using get_config with ResNet18 and warmup cosine decay schedule', 'refactor the get_config function to use a different finetuning strategy or model architecture', 'get the learner config ConfigDict for the example bare-bones Nevis learner experiment', 'test the get_config function to verify it returns a valid ConfigDict with experiment keys', 'customize the train and eval augmentation chains in the finetuning config for image preprocessing', 'configure the SGD optimizer with momentum, Nesterov, and weight decay in the finetuning config', 'set the warmup cosine decay learning rate schedule with init rate and warmup epochs', 'adjust the finetuning strategy to INDEPENDENT mode for per-task train state initialization', 'get the finetuning learner config with ResNet34, SGD optimizer, and warmup cosine decay schedule', 'build a ConfigDict for a continual learning experiment using the PREVIOUS finetuning strategy with ResNet34', 'get the ConfigDict for pretraining a ResNet34 model on ImageNet with SGD and cosine decay', 'build a learner configuration with ResNet34, SGD optimizer, and warmup cosine decay schedule for ImageNet', 'create train and eval augmentation pipelines with random crop, flip, normalize, and central crop', 'configure the finetuning learner builder with an independent strategy for each task', 'set up an SGD optimizer with momentum 0.9 and a warmup cosine decay learning rate schedule']
```

Usage

```
{'get_finetuning_config': 'get the finetuning learner ConfigDict with ResNet34, SGD optimizer, and warmup cosine decay schedule', 'customize_augmentations': 'customize the train and eval augmentation chains in the finetuning config for image preprocessing', 'configure_optimizer': 'configure the SGD optimizer with momentum, Nesterov, and weight decay in the finetuning config', 'set_learning_rate_schedule': 'set the warmup cosine decay learning rate schedule with init rate and warmup epochs', 'adjust_finetuning_strategy': 'adjust the finetuning strategy to INDEPENDENT mode for per-task train state initialization'}
```

## File: google-deepmind_dmnevis/experiments_torch/configs/finetuning_ind_pretrained.py

Prompts

```
['get a ConfigDict for an independent finetuning experiment with ResNet18 and SGD optimizer', 'review the get_config function to understand the finetuning learner configuration structure', 'summarize the get_config function and its default hyperparameters for cheap finetuning', 'build a finetuning experiment config using get_config with ResNet18 and warmup cosine decay schedule', 'refactor the get_config function to use a different finetuning strategy or model architecture', 'get the learner config ConfigDict for the example bare-bones Nevis learner experiment', 'test the get_config function to verify it returns a valid ConfigDict with experiment keys', 'customize the train and eval augmentation chains in the finetuning config for image preprocessing', 'configure the SGD optimizer with momentum, Nesterov, and weight decay in the finetuning config', 'set the warmup cosine decay learning rate schedule with init rate and warmup epochs', 'adjust the finetuning strategy to INDEPENDENT mode for per-task train state initialization', 'get the finetuning learner config with ResNet34, SGD optimizer, and warmup cosine decay schedule', 'build a ConfigDict for a continual learning experiment using the PREVIOUS finetuning strategy with ResNet34', 'get the ConfigDict for pretraining a ResNet34 model on ImageNet with SGD and cosine decay', 'build a learner configuration with ResNet34, SGD optimizer, and warmup cosine decay schedule for ImageNet', 'create train and eval augmentation pipelines with random crop, flip, normalize, and central crop', 'configure the finetuning learner builder with an independent strategy for each task', 'set up an SGD optimizer with momentum 0.9 and a warmup cosine decay learning rate schedule']
```

Usage

```
{'get_config_finetuning': 'get the finetuning learner config with ResNet34, SGD optimizer, and warmup cosine decay schedule', 'review_get_config': 'review the get_config function to understand the finetuning strategy and augmentation pipeline', 'summarize_get_config': 'summarize the get_config function and its ConfigDict structure for independent finetuning', 'refactor_get_config': 'refactor the get_config function to use a different pretrained backbone or optimizer', 'test_get_config': 'test the get_config function to verify it returns a valid ConfigDict with all required keys'}
```

## File: google-deepmind_dmnevis/experiments_torch/configs/finetuning_prev.py

Prompts

```
['get a ConfigDict for an independent finetuning experiment with ResNet18 and SGD optimizer', 'review the get_config function to understand the finetuning learner configuration structure', 'summarize the get_config function and its default hyperparameters for cheap finetuning', 'build a finetuning experiment config using get_config with ResNet18 and warmup cosine decay schedule', 'refactor the get_config function to use a different finetuning strategy or model architecture', 'get the learner config ConfigDict for the example bare-bones Nevis learner experiment', 'test the get_config function to verify it returns a valid ConfigDict with experiment keys', 'customize the train and eval augmentation chains in the finetuning config for image preprocessing', 'configure the SGD optimizer with momentum, Nesterov, and weight decay in the finetuning config', 'set the warmup cosine decay learning rate schedule with init rate and warmup epochs', 'adjust the finetuning strategy to INDEPENDENT mode for per-task train state initialization', 'get the finetuning learner config with ResNet34, SGD optimizer, and warmup cosine decay schedule', 'build a ConfigDict for a continual learning experiment using the PREVIOUS finetuning strategy with ResNet34', 'get the ConfigDict for pretraining a ResNet34 model on ImageNet with SGD and cosine decay', 'build a learner configuration with ResNet34, SGD optimizer, and warmup cosine decay schedule for ImageNet', 'create train and eval augmentation pipelines with random crop, flip, normalize, and central crop', 'configure the finetuning learner builder with an independent strategy for each task', 'set up an SGD optimizer with momentum 0.9 and a warmup cosine decay learning rate schedule']
```

Usage

```
{'get_config': 'get the finetuning learner ConfigDict with ResNet34, SGD optimizer, and PREVIOUS strategy for continual learning experiments', 'build_finetuning_config': 'build a ConfigDict for a continual learning experiment using the PREVIOUS finetuning strategy with ResNet34', 'customize_augmentations': 'customize the train and eval augmentation chains in the finetuning config for different image preprocessing', 'configure_optimizer': 'configure the SGD optimizer with momentum, Nesterov, and weight decay in the finetuning experiment config', 'set_learning_rate_schedule': 'set the warmup cosine decay learning rate schedule with configurable warmup epochs and final learning rate'}
```

## File: google-deepmind_dmnevis/experiments_torch/configs/pretrain_imagenet.py

Prompts

```
['get a ConfigDict for an independent finetuning experiment with ResNet18 and SGD optimizer', 'review the get_config function to understand the finetuning learner configuration structure', 'summarize the get_config function and its default hyperparameters for cheap finetuning', 'build a finetuning experiment config using get_config with ResNet18 and warmup cosine decay schedule', 'refactor the get_config function to use a different finetuning strategy or model architecture', 'get the learner config ConfigDict for the example bare-bones Nevis learner experiment', 'test the get_config function to verify it returns a valid ConfigDict with experiment keys', 'customize the train and eval augmentation chains in the finetuning config for image preprocessing', 'configure the SGD optimizer with momentum, Nesterov, and weight decay in the finetuning config', 'set the warmup cosine decay learning rate schedule with init rate and warmup epochs', 'adjust the finetuning strategy to INDEPENDENT mode for per-task train state initialization', 'get the finetuning learner config with ResNet34, SGD optimizer, and warmup cosine decay schedule', 'build a ConfigDict for a continual learning experiment using the PREVIOUS finetuning strategy with ResNet34', 'get the ConfigDict for pretraining a ResNet34 model on ImageNet with SGD and cosine decay', 'build a learner configuration with ResNet34, SGD optimizer, and warmup cosine decay schedule for ImageNet', 'create train and eval augmentation pipelines with random crop, flip, normalize, and central crop', 'configure the finetuning learner builder with an independent strategy for each task', 'set up an SGD optimizer with momentum 0.9 and a warmup cosine decay learning rate schedule']
```

Usage

```
{'get_config_pretrain_imagenet': 'get the ConfigDict for pretraining a ResNet34 model on ImageNet with SGD and cosine decay', 'build_pretrain_learner_config': 'build a learner configuration with ResNet34, SGD optimizer, and warmup cosine decay schedule for ImageNet', 'create_augmentation_pipeline': 'create train and eval augmentation pipelines with random crop, flip, normalize, and central crop', 'configure_finetuning_strategy': 'configure the finetuning learner builder with an independent strategy for each task', 'set_optimizer_and_schedule': 'set up an SGD optimizer with momentum 0.9 and a warmup cosine decay learning rate schedule'}
```

