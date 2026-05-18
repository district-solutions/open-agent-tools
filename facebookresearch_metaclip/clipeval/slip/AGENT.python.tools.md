# Agent Python Tools

- repo: facebookresearch/metaclip
- repo_uri: https://github.com/facebookresearch/metaclip

## File: facebookresearch_metaclip/clipeval/slip/datasets.py

Prompts

```
['create a FileListDataset from numpy image and label arrays with optional transforms', 'get a downstream ImageFolder dataset from a catalog entry with a given transform', 'get a downstream special dataset like CIFAR10 or MNIST from a catalog', 'get a downstream FileListDataset from a catalog entry with numpy image and label files', 'use pil_loader to open an image file path and convert it to RGB', 'run slip_evaluate to evaluate a CLIP model on 26 downstream datasets and write results to a JSON file', 'run main to evaluate a model with batch size 128 and save results to a JSON file', 'parse_results to read a JSONL results file and compute the average SLIP score across 26 datasets', 'review slip_evaluate to understand how it loads metadata, creates dataloaders, and runs zero-shot evaluation', 'refactor parse_results to support a variable number of datasets instead of asserting exactly 26', 'build text features by encoding label templates into normalized class embeddings using a CLIP model', 'run zero-shot evaluation on a dataset using a model, tokenizer, templates, and labels', 'validate a model on a dataloader using zero-shot image-text cosine similarity classification', 'load dataset catalog, templates, and labels JSON files from a metadata directory', 'compute top-k accuracy over predictions by comparing output logits against target labels']
```

Usage

```
{'create_FileListDataset': 'create a FileListDataset from numpy image and label arrays with optional transforms', 'get_downstream_dataset_imagefolder': 'get a downstream ImageFolder dataset from a catalog entry with a given transform', 'get_downstream_dataset_special': 'get a downstream special dataset like CIFAR10 or MNIST from a catalog', 'get_downstream_dataset_filelist': 'get a downstream FileListDataset from a catalog entry with numpy image and label files', 'use_pil_loader': 'use pil_loader to open an image file path and convert it to RGB'}
```

## File: facebookresearch_metaclip/clipeval/slip/eval_slip.py

Prompts

```
['create a FileListDataset from numpy image and label arrays with optional transforms', 'get a downstream ImageFolder dataset from a catalog entry with a given transform', 'get a downstream special dataset like CIFAR10 or MNIST from a catalog', 'get a downstream FileListDataset from a catalog entry with numpy image and label files', 'use pil_loader to open an image file path and convert it to RGB', 'run slip_evaluate to evaluate a CLIP model on 26 downstream datasets and write results to a JSON file', 'run main to evaluate a model with batch size 128 and save results to a JSON file', 'parse_results to read a JSONL results file and compute the average SLIP score across 26 datasets', 'review slip_evaluate to understand how it loads metadata, creates dataloaders, and runs zero-shot evaluation', 'refactor parse_results to support a variable number of datasets instead of asserting exactly 26', 'build text features by encoding label templates into normalized class embeddings using a CLIP model', 'run zero-shot evaluation on a dataset using a model, tokenizer, templates, and labels', 'validate a model on a dataloader using zero-shot image-text cosine similarity classification', 'load dataset catalog, templates, and labels JSON files from a metadata directory', 'compute top-k accuracy over predictions by comparing output logits against target labels']
```

Usage

```
{'run_slip_evaluation': 'run slip_evaluate to evaluate a CLIP model on 26 downstream datasets and write results to a JSON file', 'run_main_evaluation': 'run main to evaluate a model with batch size 128 and save results to a JSON file', 'parse_slip_results': 'parse_results to read a JSONL results file and compute the average SLIP score across 26 datasets', 'review_slip_evaluate': 'review slip_evaluate to understand how it loads metadata, creates dataloaders, and runs zero-shot evaluation', 'refactor_parse_results': 'refactor parse_results to support a variable number of datasets instead of asserting exactly 26'}
```

## File: facebookresearch_metaclip/clipeval/slip/eval_zeroshot.py

Prompts

```
['create a FileListDataset from numpy image and label arrays with optional transforms', 'get a downstream ImageFolder dataset from a catalog entry with a given transform', 'get a downstream special dataset like CIFAR10 or MNIST from a catalog', 'get a downstream FileListDataset from a catalog entry with numpy image and label files', 'use pil_loader to open an image file path and convert it to RGB', 'run slip_evaluate to evaluate a CLIP model on 26 downstream datasets and write results to a JSON file', 'run main to evaluate a model with batch size 128 and save results to a JSON file', 'parse_results to read a JSONL results file and compute the average SLIP score across 26 datasets', 'review slip_evaluate to understand how it loads metadata, creates dataloaders, and runs zero-shot evaluation', 'refactor parse_results to support a variable number of datasets instead of asserting exactly 26', 'build text features by encoding label templates into normalized class embeddings using a CLIP model', 'run zero-shot evaluation on a dataset using a model, tokenizer, templates, and labels', 'validate a model on a dataloader using zero-shot image-text cosine similarity classification', 'load dataset catalog, templates, and labels JSON files from a metadata directory', 'compute top-k accuracy over predictions by comparing output logits against target labels']
```

Usage

```
{'build_text_features': 'build text features by encoding label templates into normalized class embeddings using a CLIP model', 'run_evaluate': 'run zero-shot evaluation on a dataset using a model, tokenizer, templates, and labels', 'validate_zeroshot': 'validate a model on a dataloader using zero-shot image-text cosine similarity classification', 'load_metadata': 'load dataset catalog, templates, and labels JSON files from a metadata directory', 'compute_accuracy': 'compute top-k accuracy over predictions by comparing output logits against target labels'}
```

