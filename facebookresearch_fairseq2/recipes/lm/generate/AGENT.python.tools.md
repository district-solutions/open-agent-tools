# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/recipes/lm/generate/dataset.py

Prompts

```
['create an LMGenerateDataset instance from a list of JSONL file paths for language model generation', 'create a DataPipelineReader from LMGenerateDataset using a tokenizer, gangs, and batch size for reading sequence batches', 'open an LMGenerateDataset from an LMGenerateDatasetConfig with file paths for language model generation tasks', 'review the LMGenerateDatasetConfig dataclass that holds a list of Path objects for dataset file paths', 'build a data pipeline that reads JSONL files, encodes prompts, buckets, collates, and wraps into SequenceBatch', 'run the LM generation recipe to generate text from prompts using a language model', 'create an LMGenerateUnit to process sequence batches and write outputs to text and JSON streams', 'review the LMGenerateRecipe create_task method to understand how it sets up the generation pipeline', 'test the LMGenerateUnit process_batch method to verify it generates responses and writes output correctly', 'refactor the LMGenerateUnit process_batch method to support custom output formats beyond text and JSON']
```

Usage

```
{'create_LMGenerateDataset': 'create an LMGenerateDataset instance from a list of JSONL file paths for language model generation', 'create_reader_LMGenerateDataset': 'create a DataPipelineReader from LMGenerateDataset using a tokenizer, gangs, and batch size for reading sequence batches', 'open_lm_generate_dataset': 'open an LMGenerateDataset from an LMGenerateDatasetConfig with file paths for language model generation tasks', 'review_LMGenerateDatasetConfig': 'review the LMGenerateDatasetConfig dataclass that holds a list of Path objects for dataset file paths', 'build_data_pipeline_LMGenerateDataset': 'build a data pipeline that reads JSONL files, encodes prompts, buckets, collates, and wraps into SequenceBatch'}
```

## File: facebookresearch_fairseq2/recipes/lm/generate/recipe.py

Prompts

```
['create an LMGenerateDataset instance from a list of JSONL file paths for language model generation', 'create a DataPipelineReader from LMGenerateDataset using a tokenizer, gangs, and batch size for reading sequence batches', 'open an LMGenerateDataset from an LMGenerateDatasetConfig with file paths for language model generation tasks', 'review the LMGenerateDatasetConfig dataclass that holds a list of Path objects for dataset file paths', 'build a data pipeline that reads JSONL files, encodes prompts, buckets, collates, and wraps into SequenceBatch', 'run the LM generation recipe to generate text from prompts using a language model', 'create an LMGenerateUnit to process sequence batches and write outputs to text and JSON streams', 'review the LMGenerateRecipe create_task method to understand how it sets up the generation pipeline', 'test the LMGenerateUnit process_batch method to verify it generates responses and writes output correctly', 'refactor the LMGenerateUnit process_batch method to support custom output formats beyond text and JSON']
```

Usage

```
{'run_LMGenerateRecipe': 'run the LM generation recipe to generate text from prompts using a language model', 'create_LMGenerateUnit': 'create an LMGenerateUnit to process sequence batches and write outputs to text and JSON streams', 'review_LMGenerateRecipe_create_task': 'review the LMGenerateRecipe create_task method to understand how it sets up the generation pipeline', 'test_LMGenerateUnit_process_batch': 'test the LMGenerateUnit process_batch method to verify it generates responses and writes output correctly', 'refactor_LMGenerateUnit_process_batch': 'refactor the LMGenerateUnit process_batch method to support custom output formats beyond text and JSON'}
```

