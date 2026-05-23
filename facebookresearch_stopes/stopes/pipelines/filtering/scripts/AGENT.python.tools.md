# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/pipelines/filtering/scripts/compute_length_factors.py

Prompts

```
['run the script with --flores-path and --data-conf-dir to compute language length scaling factors', 'run get_scaling_factors with a FLORES data path to compute length factors relative to English', 'create a length_factors.yaml config file from FLORES devset files using the CLI script', 'refactor get_scaling_factors to support additional normalization strategies beyond English-based rescaling', 'review the main function that writes length scaling factors to a YAML configuration file', 'run the script to populate train_primary.yaml config from primary training data directories', 'run the script to populate train_mined.yaml config from mined bitext data', 'run the script to populate train_bt.yaml config from backtranslated data', 'discover backtranslated datasets in direction directories and return Dataset objects with src and tgt paths', 'discover primary training datasets across multiple paths and return Dataset objects with src and tgt']
```

Usage

```
{'run_compute_length_factors': 'run the script with --flores-path and --data-conf-dir to compute language length scaling factors', 'run_get_scaling_factors': 'run get_scaling_factors with a FLORES data path to compute length factors relative to English', 'create_length_factors_yaml': 'create a length_factors.yaml config file from FLORES devset files using the CLI script', 'refactor_get_scaling_factors': 'refactor get_scaling_factors to support additional normalization strategies beyond English-based rescaling', 'review_main': 'review the main function that writes length scaling factors to a YAML configuration file'}
```

## File: facebookresearch_stopes/stopes/pipelines/filtering/scripts/populate_data_conf.py

Prompts

```
['run the script with --flores-path and --data-conf-dir to compute language length scaling factors', 'run get_scaling_factors with a FLORES data path to compute length factors relative to English', 'create a length_factors.yaml config file from FLORES devset files using the CLI script', 'refactor get_scaling_factors to support additional normalization strategies beyond English-based rescaling', 'review the main function that writes length scaling factors to a YAML configuration file', 'run the script to populate train_primary.yaml config from primary training data directories', 'run the script to populate train_mined.yaml config from mined bitext data', 'run the script to populate train_bt.yaml config from backtranslated data', 'discover backtranslated datasets in direction directories and return Dataset objects with src and tgt paths', 'discover primary training datasets across multiple paths and return Dataset objects with src and tgt']
```

Usage

```
{'run_populate_data_conf_primary': 'run the script to populate train_primary.yaml config from primary training data directories', 'run_populate_data_conf_mined': 'run the script to populate train_mined.yaml config from mined bitext data', 'run_populate_data_conf_bt': 'run the script to populate train_bt.yaml config from backtranslated data', 'get_bt_datasets': 'discover backtranslated datasets in direction directories and return Dataset objects with src and tgt paths', 'get_primary_datasets': 'discover primary training datasets across multiple paths and return Dataset objects with src and tgt'}
```

