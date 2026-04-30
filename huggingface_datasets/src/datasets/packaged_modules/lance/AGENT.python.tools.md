# Agent Python Tools

- repo: huggingface/datasets
- repo_uri: https://github.com/huggingface/datasets

## File: huggingface_datasets/src/datasets/packaged_modules/lance/lance.py

Prompts

```
['create a LanceConfig with custom features, columns, and batch_size for loading Lance datasets', 'resolve Lance dataset root URIs from a list of file paths inside _transactions or _versions directories', 'strip the revision tag from a Hugging Face hf:// URI so Lance can load it', 'replace a symlinked local _versions file with its real content to fix Lance loading', 'yield PyArrow tables keyed by fragment and batch index from Lance dataset fragments or LanceFileReaders']
```

Usage

```
{'build_lance_config': 'create a LanceConfig with custom features, columns, and batch_size for loading Lance datasets', 'resolve_dataset_uris': 'resolve Lance dataset root URIs from a list of file paths inside _transactions or _versions directories', 'fix_hf_uri': 'strip the revision tag from a Hugging Face hf:// URI so Lance can load it', 'fix_local_version_file': 'replace a symlinked local _versions file with its real content to fix Lance loading', 'generate_tables_from_lance_fragments': 'yield PyArrow tables keyed by fragment and batch index from Lance dataset fragments or LanceFileReaders'}
```

