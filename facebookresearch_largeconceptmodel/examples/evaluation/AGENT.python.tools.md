# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/examples/evaluation/prepare_evaluation_data.py

Prompts

```
['download a HuggingFace dataset and parse it into JSONL format for LCM and LLM evaluation', 'schedule a SONAR text embedding pipeline to process JSONL input into parquet output using Stopes', 'create an InstSonarEmbedder instance that splits text into sentences and embeds them with SONAR', 'split a pandas Series of text into sentences using the SaT-3l model and remove emojis', 'resplit a long sentence into shorter segments using probability-based peak detection with SaT']
```

Usage

```
{'prepare_data': 'download a HuggingFace dataset and parse it into JSONL format for LCM and LLM evaluation', 'embed': 'schedule a SONAR text embedding pipeline to process JSONL input into parquet output using Stopes', 'InstSonarEmbedder': 'create an InstSonarEmbedder instance that splits text into sentences and embeds them with SONAR', 'InstSonarEmbedder_split_one_single_column': 'split a pandas Series of text into sentences using the SaT-3l model and remove emojis', 'InstSonarEmbedder_resplit_sentence': 'resplit a long sentence into shorter segments using probability-based peak detection with SaT'}
```

