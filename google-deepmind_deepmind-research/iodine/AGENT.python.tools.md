# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/iodine/configurations.py

Prompts

```
['get the IODINE model configuration dictionary for the CLEVR-6 multi-object dataset', 'get the IODINE model configuration dictionary for the multi-dSprites colored-on-grayscale dataset', 'get the IODINE model configuration dictionary for the tetrominoes multi-object dataset', 'review the CLEVR-6 model architecture including decoder, refinement core, and factor evaluator settings', 'compare the latent dimensions, component counts, and learning rates across clevr6, multi_dsprites, and tetrominoes configs', 'run the iodine model training loop with sacred experiment configuration and tensorboard summaries', 'build a dataset model or optimizer component from a sacred config identifier using utils.build', 'get the tensorflow training step graph with gradient clipping and summary operations for a model', 'load a trained iodine model checkpoint and print all global and local variable values', 'get the checkpoint directory path for continuing an existing run or starting a new run']
```

Usage

```
{'get_clevr6_config': 'get the IODINE model configuration dictionary for the CLEVR-6 multi-object dataset', 'get_multi_dsprites_config': 'get the IODINE model configuration dictionary for the multi-dSprites colored-on-grayscale dataset', 'get_tetrominoes_config': 'get the IODINE model configuration dictionary for the tetrominoes multi-object dataset', 'review_clevr6_model_architecture': 'review the CLEVR-6 model architecture including decoder, refinement core, and factor evaluator settings', 'compare_dataset_configs': 'compare the latent dimensions, component counts, and learning rates across clevr6, multi_dsprites, and tetrominoes configs'}
```

## File: google-deepmind_deepmind-research/iodine/main.py

Prompts

```
['get the IODINE model configuration dictionary for the CLEVR-6 multi-object dataset', 'get the IODINE model configuration dictionary for the multi-dSprites colored-on-grayscale dataset', 'get the IODINE model configuration dictionary for the tetrominoes multi-object dataset', 'review the CLEVR-6 model architecture including decoder, refinement core, and factor evaluator settings', 'compare the latent dimensions, component counts, and learning rates across clevr6, multi_dsprites, and tetrominoes configs', 'run the iodine model training loop with sacred experiment configuration and tensorboard summaries', 'build a dataset model or optimizer component from a sacred config identifier using utils.build', 'get the tensorflow training step graph with gradient clipping and summary operations for a model', 'load a trained iodine model checkpoint and print all global and local variable values', 'get the checkpoint directory path for continuing an existing run or starting a new run']
```

Usage

```
{'run_iodine_training': 'run the iodine model training loop with sacred experiment configuration and tensorboard summaries', 'build_component_from_config': 'build a dataset model or optimizer component from a sacred config identifier using utils.build', 'get_train_step_graph': 'get the tensorflow training step graph with gradient clipping and summary operations for a model', 'load_checkpoint_variables': 'load a trained iodine model checkpoint and print all global and local variable values', 'get_checkpoint_directory': 'get the checkpoint directory path for continuing an existing run or starting a new run'}
```

