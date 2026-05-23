# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/recipes/lm/sft/dataset.py

Prompts

```
['create an LMSFTDataset from a dictionary of sources mapped to LMSFTDataSource lists for each split', 'create a DataPipelineReader from LMSFTDataset with a tokenizer, gangs, and DataReadOptions for sequence batching', 'configure DataReadOptions with StaticBatching or LengthBatching, shuffle windows, and sync settings for dataset reading', 'open an LMSFTDataset from an LMSFTDatasetConfig containing sources for each split like train or validation', 'configure an LMSFTDataSource with a file path, optional split, and sampling weight for dataset mixing', 'run the LMSFTRecipe create_task method to build a trainer with data readers and validation units', 'create a LMSFTUnit instance to process a SequenceBatch and compute NLL loss for supervised fine-tuning', 'build a LMLossEvalUnit to evaluate model performance on validation batches using NLL loss metrics', 'review the LMSFTRecipe register method that registers the LMSFT dataset family in the dependency container', 'test the LMSFTUnit prepare_metric_bag method to verify NLL loss and sequence batch metrics are added']
```

Usage

```
{'create_LMSFTDataset': 'create an LMSFTDataset from a dictionary of sources mapped to LMSFTDataSource lists for each split', 'create_reader_LMSFTDataset': 'create a DataPipelineReader from LMSFTDataset with a tokenizer, gangs, and DataReadOptions for sequence batching', 'configure_DataReadOptions': 'configure DataReadOptions with StaticBatching or LengthBatching, shuffle windows, and sync settings for dataset reading', 'open_lm_sft_dataset': 'open an LMSFTDataset from an LMSFTDatasetConfig containing sources for each split like train or validation', 'configure_LMSFTDataSource': 'configure an LMSFTDataSource with a file path, optional split, and sampling weight for dataset mixing'}
```

## File: facebookresearch_fairseq2/recipes/lm/sft/recipe.py

Prompts

```
['create an LMSFTDataset from a dictionary of sources mapped to LMSFTDataSource lists for each split', 'create a DataPipelineReader from LMSFTDataset with a tokenizer, gangs, and DataReadOptions for sequence batching', 'configure DataReadOptions with StaticBatching or LengthBatching, shuffle windows, and sync settings for dataset reading', 'open an LMSFTDataset from an LMSFTDatasetConfig containing sources for each split like train or validation', 'configure an LMSFTDataSource with a file path, optional split, and sampling weight for dataset mixing', 'run the LMSFTRecipe create_task method to build a trainer with data readers and validation units', 'create a LMSFTUnit instance to process a SequenceBatch and compute NLL loss for supervised fine-tuning', 'build a LMLossEvalUnit to evaluate model performance on validation batches using NLL loss metrics', 'review the LMSFTRecipe register method that registers the LMSFT dataset family in the dependency container', 'test the LMSFTUnit prepare_metric_bag method to verify NLL loss and sequence batch metrics are added']
```

Usage

```
{'run_LMSFTRecipe_create_task': 'run the LMSFTRecipe create_task method to build a trainer with data readers and validation units', 'create_LMSFTUnit_process_batch': 'create a LMSFTUnit instance to process a SequenceBatch and compute NLL loss for supervised fine-tuning', 'build_LMLossEvalUnit_process_batch': 'build a LMLossEvalUnit to evaluate model performance on validation batches using NLL loss metrics', 'review_LMSFTRecipe_register': 'review the LMSFTRecipe register method that registers the LMSFT dataset family in the dependency container', 'test_LMSFTUnit_prepare_metric_bag': 'test the LMSFTUnit prepare_metric_bag method to verify NLL loss and sequence batch metrics are added'}
```

