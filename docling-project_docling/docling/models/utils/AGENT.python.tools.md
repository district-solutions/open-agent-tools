# Agent Python Tools

- repo: docling-project/docling
- repo_uri: https://github.com/docling-project/docling

## File: docling-project_docling/docling/models/utils/generation_utils.py

Prompts

```
['create a GenerationStopper subclass that implements should_stop to detect repetitive document tag patterns', 'build a DocTagsRepetitionStopper to detect consecutive identical tag blocks with regular coordinate progression', 'test the HFStoppingCriteriaWrapper adapter that wraps a GenerationStopper for HuggingFace Transformers generation', 'run a DocTagsRepetitionStopper on decoded text to detect repetitive layout output during generation', 'review the GenerationStopper base interface with should_stop and lookback_tokens methods for custom stopping logic', 'download a Hugging Face model snapshot by repo_id to a local directory with optional force and revision parameters', 'run download_hf_model to fetch a Hugging Face model repository and return the local download path', 'create an instance of HuggingFaceModelDownloadMixin and call download_models to download a Hugging Face model', 'refactor download_hf_model to add support for filtering specific files during Hugging Face model download', 'review HuggingFaceModelDownloadMixin.download_models and its wrapper around download_hf_model']
```

Usage

```
{'create_GenerationStopper': 'create a GenerationStopper subclass that implements should_stop to detect repetitive document tag patterns', 'build_DocTagsRepetitionStopper': 'build a DocTagsRepetitionStopper to detect consecutive identical tag blocks with regular coordinate progression', 'test_HFStoppingCriteriaWrapper': 'test the HFStoppingCriteriaWrapper adapter that wraps a GenerationStopper for HuggingFace Transformers generation', 'run_DocTagsRepetitionStopper': 'run a DocTagsRepetitionStopper on decoded text to detect repetitive layout output during generation', 'review_GenerationStopper': 'review the GenerationStopper base interface with should_stop and lookback_tokens methods for custom stopping logic'}
```

## File: docling-project_docling/docling/models/utils/hf_model_download.py

Prompts

```
['create a GenerationStopper subclass that implements should_stop to detect repetitive document tag patterns', 'build a DocTagsRepetitionStopper to detect consecutive identical tag blocks with regular coordinate progression', 'test the HFStoppingCriteriaWrapper adapter that wraps a GenerationStopper for HuggingFace Transformers generation', 'run a DocTagsRepetitionStopper on decoded text to detect repetitive layout output during generation', 'review the GenerationStopper base interface with should_stop and lookback_tokens methods for custom stopping logic', 'download a Hugging Face model snapshot by repo_id to a local directory with optional force and revision parameters', 'run download_hf_model to fetch a Hugging Face model repository and return the local download path', 'create an instance of HuggingFaceModelDownloadMixin and call download_models to download a Hugging Face model', 'refactor download_hf_model to add support for filtering specific files during Hugging Face model download', 'review HuggingFaceModelDownloadMixin.download_models and its wrapper around download_hf_model']
```

Usage

```
{'download_hf_model': 'download a Hugging Face model snapshot by repo_id to a local directory with optional force and revision parameters', 'run_download_hf_model': 'run download_hf_model to fetch a Hugging Face model repository and return the local download path', 'create_download_models_mixin': 'create an instance of HuggingFaceModelDownloadMixin and call download_models to download a Hugging Face model', 'refactor_download_hf_model': 'refactor download_hf_model to add support for filtering specific files during Hugging Face model download', 'review_HuggingFaceModelDownloadMixin': 'review HuggingFaceModelDownloadMixin.download_models and its wrapper around download_hf_model'}
```

