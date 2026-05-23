# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/recipes/lm/train/dataset.py

Prompts

```
['create an LMTrainDataset from a list of LMTrainDataSource with file paths and sampling weights', 'create a DataReader that tokenizes, packs, and batches JSONL text data for language model training', 'open an LMTrainDataset by passing an LMTrainDatasetConfig with configured data sources', 'create a DataPipeline that reads and shards JSONL chunk files across distributed training ranks', 'configure an LMTrainDataSource dataclass with a file path and optional sampling weight for dataset mixing', 'create an LMTrainRecipe to register the LM training dataset family and configure the training task', 'create a training task from LMTrainRecipe by building a data reader and trainer from the recipe context', 'review the LMTrainUnit process_batch method that computes NLL loss for causal language model training', 'build a metric bag for LMTrainUnit that adds NLL loss and sequence batch metrics for tracking training', 'refactor the LMTrainUnit class to support a custom causal language model with modified batch processing']
```

Usage

```
{'create_lm_train_dataset': 'create an LMTrainDataset from a list of LMTrainDataSource with file paths and sampling weights', 'create_reader_for_lm_training': 'create a DataReader that tokenizes, packs, and batches JSONL text data for language model training', 'open_lm_train_dataset_from_config': 'open an LMTrainDataset by passing an LMTrainDatasetConfig with configured data sources', 'create_path_reader_pipeline': 'create a DataPipeline that reads and shards JSONL chunk files across distributed training ranks', 'configure_lm_train_data_source': 'configure an LMTrainDataSource dataclass with a file path and optional sampling weight for dataset mixing'}
```

## File: facebookresearch_fairseq2/recipes/lm/train/recipe.py

Prompts

```
['create an LMTrainDataset from a list of LMTrainDataSource with file paths and sampling weights', 'create a DataReader that tokenizes, packs, and batches JSONL text data for language model training', 'open an LMTrainDataset by passing an LMTrainDatasetConfig with configured data sources', 'create a DataPipeline that reads and shards JSONL chunk files across distributed training ranks', 'configure an LMTrainDataSource dataclass with a file path and optional sampling weight for dataset mixing', 'create an LMTrainRecipe to register the LM training dataset family and configure the training task', 'create a training task from LMTrainRecipe by building a data reader and trainer from the recipe context', 'review the LMTrainUnit process_batch method that computes NLL loss for causal language model training', 'build a metric bag for LMTrainUnit that adds NLL loss and sequence batch metrics for tracking training', 'refactor the LMTrainUnit class to support a custom causal language model with modified batch processing']
```

Usage

```
{'create_lm_train_recipe': 'create an LMTrainRecipe to register the LM training dataset family and configure the training task', 'create_task_from_recipe': 'create a training task from LMTrainRecipe by building a data reader and trainer from the recipe context', 'review_lmtrainunit_process_batch': 'review the LMTrainUnit process_batch method that computes NLL loss for causal language model training', 'build_lmtrainunit_metric_bag': 'build a metric bag for LMTrainUnit that adds NLL loss and sequence batch metrics for tracking training', 'refactor_lmtrainunit_for_custom_model': 'refactor the LMTrainUnit class to support a custom causal language model with modified batch processing'}
```

