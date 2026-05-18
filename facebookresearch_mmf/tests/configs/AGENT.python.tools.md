# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/tests/configs/test_configs_for_keys.py

Prompts

```
['run the unittest test_model_configs_for_keys to verify all registered model keys exist in their configuration', 'run the unittest test_dataset_configs_for_keys to verify all registered dataset builder keys exist in their configuration', 'run the TestConfigsForKeys unittest class to validate model and dataset configuration key existence', 'review the test_model_configs_for_keys method that iterates model_name_mapping and asserts each model key is present in config.model_config', 'review the test_dataset_configs_for_keys method that iterates builder_name_mapping and asserts each builder key is present in config.dataset_config', 'test all download URLs in the MMF zoo config YAML files for accessibility', 'test that all SHA256 checksums in the MMF zoo configs are valid 64-character hex strings', 'recursively traverse an OmegaConf DictConfig to find and process URL entries with a callback', 'check the HTTP header of a downloadable file URL up to 3 times with retry delays', 'validate that a DownloadableFile hashcode matches the expected 64-character hexadecimal SHA256 format']
```

Usage

```
{'run_test_model_configs_for_keys': 'run the unittest test_model_configs_for_keys to verify all registered model keys exist in their configuration', 'run_test_dataset_configs_for_keys': 'run the unittest test_dataset_configs_for_keys to verify all registered dataset builder keys exist in their configuration', 'run_TestConfigsForKeys': 'run the TestConfigsForKeys unittest class to validate model and dataset configuration key existence', 'review_test_model_configs_for_keys': 'review the test_model_configs_for_keys method that iterates model_name_mapping and asserts each model key is present in config.model_config', 'review_test_dataset_configs_for_keys': 'review the test_dataset_configs_for_keys method that iterates builder_name_mapping and asserts each builder key is present in config.dataset_config'}
```

## File: facebookresearch_mmf/tests/configs/test_zoo_urls.py

Prompts

```
['run the unittest test_model_configs_for_keys to verify all registered model keys exist in their configuration', 'run the unittest test_dataset_configs_for_keys to verify all registered dataset builder keys exist in their configuration', 'run the TestConfigsForKeys unittest class to validate model and dataset configuration key existence', 'review the test_model_configs_for_keys method that iterates model_name_mapping and asserts each model key is present in config.model_config', 'review the test_dataset_configs_for_keys method that iterates builder_name_mapping and asserts each builder key is present in config.dataset_config', 'test all download URLs in the MMF zoo config YAML files for accessibility', 'test that all SHA256 checksums in the MMF zoo configs are valid 64-character hex strings', 'recursively traverse an OmegaConf DictConfig to find and process URL entries with a callback', 'check the HTTP header of a downloadable file URL up to 3 times with retry delays', 'validate that a DownloadableFile hashcode matches the expected 64-character hexadecimal SHA256 format']
```

Usage

```
{'test_zoo_download_urls': 'test all download URLs in the MMF zoo config YAML files for accessibility', 'test_sha256_checksums': 'test that all SHA256 checksums in the MMF zoo configs are valid 64-character hex strings', 'recurse_on_config': 'recursively traverse an OmegaConf DictConfig to find and process URL entries with a callback', 'check_download_header': 'check the HTTP header of a downloadable file URL up to 3 times with retry delays', 'validate_sha256sum_format': 'validate that a DownloadableFile hashcode matches the expected 64-character hexadecimal SHA256 format'}
```

