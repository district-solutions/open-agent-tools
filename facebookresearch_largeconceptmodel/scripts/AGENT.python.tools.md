# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/scripts/fit_embedding_normalizer.py

Prompts

```
['run the script to fit a SonarNormalizer on a weighted mixture of parquet datasets and save it', 'run sample_sentences_from_mixed_sources to sample embedding vectors from a weighted list of parquet datasets', 'run main to sample embeddings from datasets, fit a SonarNormalizer, and save the model to a path', 'review the sample_sentences_from_mixed_sources function that builds a weighted data pipeline and samples embedding vectors', 'review the main function that fits a SonarNormalizer on sampled embeddings and saves the state dict', 'run the wikipedia preprocessing pipeline that splits text into sentences and embeds them with SONAR', 'run the sentence splitter using SAT model to split text columns into individual sentences', 'run the SONAR text embedder to generate embeddings for English text sentences on GPU', 'run the full pipeline combining sentence splitting and SONAR embedding on a HuggingFace dataset', 'run the HuggingFace input config to download and shard wikipedia data for processing']
```

Usage

```
{'run_fit_embedding_normalizer': 'run the script to fit a SonarNormalizer on a weighted mixture of parquet datasets and save it', 'run_sample_sentences_from_mixed_sources': 'run sample_sentences_from_mixed_sources to sample embedding vectors from a weighted list of parquet datasets', 'run_main_fit_normalizer': 'run main to sample embeddings from datasets, fit a SonarNormalizer, and save the model to a path', 'review_sample_sentences_from_mixed_sources': 'review the sample_sentences_from_mixed_sources function that builds a weighted data pipeline and samples embedding vectors', 'review_main_normalizer_workflow': 'review the main function that fits a SonarNormalizer on sampled embeddings and saves the state dict'}
```

## File: facebookresearch_largeconceptmodel/scripts/prepare_wikipedia.py

Prompts

```
['run the script to fit a SonarNormalizer on a weighted mixture of parquet datasets and save it', 'run sample_sentences_from_mixed_sources to sample embedding vectors from a weighted list of parquet datasets', 'run main to sample embeddings from datasets, fit a SonarNormalizer, and save the model to a path', 'review the sample_sentences_from_mixed_sources function that builds a weighted data pipeline and samples embedding vectors', 'review the main function that fits a SonarNormalizer on sampled embeddings and saves the state dict', 'run the wikipedia preprocessing pipeline that splits text into sentences and embeds them with SONAR', 'run the sentence splitter using SAT model to split text columns into individual sentences', 'run the SONAR text embedder to generate embeddings for English text sentences on GPU', 'run the full pipeline combining sentence splitting and SONAR embedding on a HuggingFace dataset', 'run the HuggingFace input config to download and shard wikipedia data for processing']
```

Usage

```
{'run_wikipedia_preprocessing_pipeline': 'run the wikipedia preprocessing pipeline that splits text into sentences and embeds them with SONAR', 'run_sentence_splitter_config': 'run the sentence splitter using SAT model to split text columns into individual sentences', 'run_sonar_text_embedder': 'run the SONAR text embedder to generate embeddings for English text sentences on GPU', 'run_full_pipeline_config': 'run the full pipeline combining sentence splitting and SONAR embedding on a HuggingFace dataset', 'run_hf_input_config': 'run the HuggingFace input config to download and shard wikipedia data for processing'}
```

