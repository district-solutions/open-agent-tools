# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/rec/datamodules/tests/test_criteo_datamodule.py

Prompts

```
['test CriteoDataModule setup with no stage to verify train and test dataloaders return correct batch shapes', 'test CriteoDataModule setup with fit stage to verify only train dataloader is available and test raises AssertionError', 'test CriteoDataModule setup with test stage to verify only test dataloader is available and train raises AssertionError', 'test CriteoDataModule with dataset_name criteo_1t to verify valid names work and invalid names raise ValueError', 'test CriteoDataModule with dataset_name criteo_kaggle to verify Kaggle variant dataset loads and returns correct batch shapes', 'test that RandomRecDataModule produces identical batches when initialized with the same manual_seed value', 'test that RandomRecDataModule produces different batches when no manual_seed is provided', 'test that sparse feature offsets remain consistent across separate RandomRecDataModule instances', 'create a RandomRecDataModule with a manual_seed and min_ids_per_features for reproducible random data generation', 'review the TestRandomRecDataModule class and its test methods for validating batch equality assertions', 'create a Criteo-style TSV dataset with random integer and categorical features for testing', 'create Kaggle-format train and test TSV files with synthetic click-through rate data', 'create multi-day TSV dataset files for Criteo 1TB style train and validation splits', 'test the create_dataset_tsv context manager to verify it generates valid TSV files with correct row counts', 'review the create_dataset_tsv function to understand its Criteo dataset generation pattern and feature counts']
```

Usage

```
{'test_CriteoDataModule_none_stage': 'test CriteoDataModule setup with no stage to verify train and test dataloaders return correct batch shapes', 'test_CriteoDataModule_fit_stage': 'test CriteoDataModule setup with fit stage to verify only train dataloader is available and test raises AssertionError', 'test_CriteoDataModule_test_stage': 'test CriteoDataModule setup with test stage to verify only test dataloader is available and train raises AssertionError', 'test_CriteoDataModule_dataset_name': 'test CriteoDataModule with dataset_name criteo_1t to verify valid names work and invalid names raise ValueError', 'test_CriteoDataModule_kaggle_dataset': 'test CriteoDataModule with dataset_name criteo_kaggle to verify Kaggle variant dataset loads and returns correct batch shapes'}
```

## File: facebookresearch_recipes/torchrecipes/rec/datamodules/tests/test_random_rec_datamodule.py

Prompts

```
['test CriteoDataModule setup with no stage to verify train and test dataloaders return correct batch shapes', 'test CriteoDataModule setup with fit stage to verify only train dataloader is available and test raises AssertionError', 'test CriteoDataModule setup with test stage to verify only test dataloader is available and train raises AssertionError', 'test CriteoDataModule with dataset_name criteo_1t to verify valid names work and invalid names raise ValueError', 'test CriteoDataModule with dataset_name criteo_kaggle to verify Kaggle variant dataset loads and returns correct batch shapes', 'test that RandomRecDataModule produces identical batches when initialized with the same manual_seed value', 'test that RandomRecDataModule produces different batches when no manual_seed is provided', 'test that sparse feature offsets remain consistent across separate RandomRecDataModule instances', 'create a RandomRecDataModule with a manual_seed and min_ids_per_features for reproducible random data generation', 'review the TestRandomRecDataModule class and its test methods for validating batch equality assertions', 'create a Criteo-style TSV dataset with random integer and categorical features for testing', 'create Kaggle-format train and test TSV files with synthetic click-through rate data', 'create multi-day TSV dataset files for Criteo 1TB style train and validation splits', 'test the create_dataset_tsv context manager to verify it generates valid TSV files with correct row counts', 'review the create_dataset_tsv function to understand its Criteo dataset generation pattern and feature counts']
```

Usage

```
{'test_manual_seed_reproducibility': 'test that RandomRecDataModule produces identical batches when initialized with the same manual_seed value', 'test_non_deterministic_batches': 'test that RandomRecDataModule produces different batches when no manual_seed is provided', 'test_sparse_feature_offsets': 'test that sparse feature offsets remain consistent across separate RandomRecDataModule instances', 'create_random_rec_datamodule': 'create a RandomRecDataModule with a manual_seed and min_ids_per_features for reproducible random data generation', 'review_testclass_methods': 'review the TestRandomRecDataModule class and its test methods for validating batch equality assertions'}
```

## File: facebookresearch_recipes/torchrecipes/rec/datamodules/tests/utils.py

Prompts

```
['test CriteoDataModule setup with no stage to verify train and test dataloaders return correct batch shapes', 'test CriteoDataModule setup with fit stage to verify only train dataloader is available and test raises AssertionError', 'test CriteoDataModule setup with test stage to verify only test dataloader is available and train raises AssertionError', 'test CriteoDataModule with dataset_name criteo_1t to verify valid names work and invalid names raise ValueError', 'test CriteoDataModule with dataset_name criteo_kaggle to verify Kaggle variant dataset loads and returns correct batch shapes', 'test that RandomRecDataModule produces identical batches when initialized with the same manual_seed value', 'test that RandomRecDataModule produces different batches when no manual_seed is provided', 'test that sparse feature offsets remain consistent across separate RandomRecDataModule instances', 'create a RandomRecDataModule with a manual_seed and min_ids_per_features for reproducible random data generation', 'review the TestRandomRecDataModule class and its test methods for validating batch equality assertions', 'create a Criteo-style TSV dataset with random integer and categorical features for testing', 'create Kaggle-format train and test TSV files with synthetic click-through rate data', 'create multi-day TSV dataset files for Criteo 1TB style train and validation splits', 'test the create_dataset_tsv context manager to verify it generates valid TSV files with correct row counts', 'review the create_dataset_tsv function to understand its Criteo dataset generation pattern and feature counts']
```

Usage

```
{'create_dataset_tsv_criteo_style': 'create a Criteo-style TSV dataset with random integer and categorical features for testing', 'create_dataset_tsv_kaggle_format': 'create Kaggle-format train and test TSV files with synthetic click-through rate data', 'create_dataset_tsv_multi_day': 'create multi-day TSV dataset files for Criteo 1TB style train and validation splits', 'test_create_dataset_tsv': 'test the create_dataset_tsv context manager to verify it generates valid TSV files with correct row counts', 'review_create_dataset_tsv': 'review the create_dataset_tsv function to understand its Criteo dataset generation pattern and feature counts'}
```

