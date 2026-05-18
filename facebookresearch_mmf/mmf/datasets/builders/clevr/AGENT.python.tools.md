# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/mmf/datasets/builders/clevr/builder.py

Prompts

```
['build the CLEVR dataset by downloading and extracting the zip archive to the MMF data folder', 'load a CLEVRDataset instance from the extracted data folder using config and dataset type', 'get the default YAML config path for the CLEVR dataset builder', 'register the CLEVR text vocab size and number of final outputs in the MMF registry', 'review the CLEVRBuilder class and its download, extraction, and dataset loading logic', 'create a CLEVRDataset instance with config and dataset_type to load CLEVR visual reasoning data', 'call the load method to load CLEVR questions from JSON and build vocabularies for training', 'build a vocabulary from CLEVR questions or answers using the _build_vocab method with tokenization', 'retrieve a CLEVR sample with tokenized text, answers, targets, and normalized image tensor by index', 'review the CLEVRDataset class and its methods for loading and processing CLEVR visual reasoning data']
```

Usage

```
{'build_clevr_dataset': 'build the CLEVR dataset by downloading and extracting the zip archive to the MMF data folder', 'load_clevr_dataset': 'load a CLEVRDataset instance from the extracted data folder using config and dataset type', 'get_clevr_config_path': 'get the default YAML config path for the CLEVR dataset builder', 'update_registry_for_model': 'register the CLEVR text vocab size and number of final outputs in the MMF registry', 'review_clevr_builder': 'review the CLEVRBuilder class and its download, extraction, and dataset loading logic'}
```

## File: facebookresearch_mmf/mmf/datasets/builders/clevr/dataset.py

Prompts

```
['build the CLEVR dataset by downloading and extracting the zip archive to the MMF data folder', 'load a CLEVRDataset instance from the extracted data folder using config and dataset type', 'get the default YAML config path for the CLEVR dataset builder', 'register the CLEVR text vocab size and number of final outputs in the MMF registry', 'review the CLEVRBuilder class and its download, extraction, and dataset loading logic', 'create a CLEVRDataset instance with config and dataset_type to load CLEVR visual reasoning data', 'call the load method to load CLEVR questions from JSON and build vocabularies for training', 'build a vocabulary from CLEVR questions or answers using the _build_vocab method with tokenization', 'retrieve a CLEVR sample with tokenized text, answers, targets, and normalized image tensor by index', 'review the CLEVRDataset class and its methods for loading and processing CLEVR visual reasoning data']
```

Usage

```
{'initialize_clevr_dataset': 'create a CLEVRDataset instance with config and dataset_type to load CLEVR visual reasoning data', 'load_clevr_questions': 'call the load method to load CLEVR questions from JSON and build vocabularies for training', 'build_clevr_vocab': 'build a vocabulary from CLEVR questions or answers using the _build_vocab method with tokenization', 'get_clevr_sample': 'retrieve a CLEVR sample with tokenized text, answers, targets, and normalized image tensor by index', 'review_clevr_dataset_class': 'review the CLEVRDataset class and its methods for loading and processing CLEVR visual reasoning data'}
```

