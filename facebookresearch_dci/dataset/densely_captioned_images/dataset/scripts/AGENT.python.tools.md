# Agent Python Tools

- repo: facebookresearch/dci
- repo_uri: https://github.com/facebookresearch/dci

## File: facebookresearch_dci/dataset/densely_captioned_images/dataset/scripts/download.py

Prompts

```
['run the download script to fetch and extract all densely captioned images datasets and models', 'download a tar.gz file from a URL with retry logic, checksum verification, and automatic extraction', "verify a downloaded file's SHA256 checksum matches the expected target hash value", 'review the download_file function for retry logic, exponential backoff, and checksum validation', 'refactor run_downloads to support downloading additional datasets or models from the RESOURCES dictionary', 'run the CLIP dense caption evaluation on a model with all standard subtests', 'run the CLIP dense caption evaluation on a model with specific subtests like all_swaps or base_swaps', 'run the dense caption test on a CLIP model with a DenseCaptionedDataset and return accuracy metrics', 'run the CLIP dense caption evaluation on a model loaded from LoRA weight path', 'run the CLIP dense caption evaluation script directly with the default openai clip-vit-base-patch32 model']
```

Usage

```
{'run_downloads': 'run the download script to fetch and extract all densely captioned images datasets and models', 'download_file': 'download a tar.gz file from a URL with retry logic, checksum verification, and automatic extraction', 'check_checksum': "verify a downloaded file's SHA256 checksum matches the expected target hash value", 'review_download_file': 'review the download_file function for retry logic, exponential backoff, and checksum validation', 'refactor_run_downloads': 'refactor run_downloads to support downloading additional datasets or models from the RESOURCES dictionary'}
```

## File: facebookresearch_dci/dataset/densely_captioned_images/dataset/scripts/run_clip_dense_cap_eval.py

Prompts

```
['run the download script to fetch and extract all densely captioned images datasets and models', 'download a tar.gz file from a URL with retry logic, checksum verification, and automatic extraction', "verify a downloaded file's SHA256 checksum matches the expected target hash value", 'review the download_file function for retry logic, exponential backoff, and checksum validation', 'refactor run_downloads to support downloading additional datasets or models from the RESOURCES dictionary', 'run the CLIP dense caption evaluation on a model with all standard subtests', 'run the CLIP dense caption evaluation on a model with specific subtests like all_swaps or base_swaps', 'run the dense caption test on a CLIP model with a DenseCaptionedDataset and return accuracy metrics', 'run the CLIP dense caption evaluation on a model loaded from LoRA weight path', 'run the CLIP dense caption evaluation script directly with the default openai clip-vit-base-patch32 model']
```

Usage

```
{'run_dense_cap_on_model': 'run the CLIP dense caption evaluation on a model with all standard subtests', 'run_dense_cap_on_model_subtests': 'run the CLIP dense caption evaluation on a model with specific subtests like all_swaps or base_swaps', 'run_dense_cap_test_on_model': 'run the dense caption test on a CLIP model with a DenseCaptionedDataset and return accuracy metrics', 'run_dense_cap_on_lora': 'run the CLIP dense caption evaluation on a model loaded from LoRA weight path', 'run_dense_cap_eval_main': 'run the CLIP dense caption evaluation script directly with the default openai clip-vit-base-patch32 model'}
```

