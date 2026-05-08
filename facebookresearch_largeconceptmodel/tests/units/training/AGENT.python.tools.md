# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/tests/units/training/conftest.py

Prompts

```
['create a toy PyArrow table with random source and target tensor columns for testing', 'use the pytest fixture to generate a temporary parquet train dataset config for unit tests', 'use the pytest fixture to generate a temporary parquet dev dataset config for unit tests', 'test ParquetDatasetConfig by writing partitioned parquet data and yielding a config object', 'review the simple_data function that creates random sonar embeddings as a PyArrow table', 'test the EmbeddingsBatch unbatch method by reconstructing a batch and verifying sequence and padding mask equality', 'test the EmbeddingsBatch get_last_element method by comparing extracted last elements against manually stacked expected values', 'run the test_unbatchon_embedding_batch test to verify EmbeddingsBatch unbatch roundtrip preserves sequences and padding masks', 'run the test_last_element_embedding_batch test to verify get_last_element returns correct terminal embeddings per sequence', 'review the test functions for EmbeddingsBatch unbatch and get_last_element to understand ragged sequence padding and batching behavior', 'test get_trainer using a builder function referenced via the _trainer_ config key', 'test get_trainer using a class constructor referenced via the _trainer_ config key', 'test that dataclass __post_init__ correctly computes derived field c from a and b', 'test that nested dataclass fields are populated from DictConfig sub-dictionaries', 'review how get_trainer resolves a dotted module path to instantiate a trainer from DictConfig', 'test the LCM trainer can be built, run training, and save the model correctly', 'compute the average evaluation loss across all validation datasets using the trainer', 'compare two PyTorch models by asserting all parameters match with torch.allclose', 'build an LCMTrainerBuilder from an LCMTrainingConfig to create a trainer for MSE training', 'load a trained LCM model from a model_card.yaml file using the card utils API']
```

Usage

```
{'create_simple_data_table': 'create a toy PyArrow table with random source and target tensor columns for testing', 'use_simple_train_dataset_fixture': 'use the pytest fixture to generate a temporary parquet train dataset config for unit tests', 'use_simple_validation_dataset_fixture': 'use the pytest fixture to generate a temporary parquet dev dataset config for unit tests', 'test_parquet_dataset_config': 'test ParquetDatasetConfig by writing partitioned parquet data and yielding a config object', 'review_simple_data_function': 'review the simple_data function that creates random sonar embeddings as a PyArrow table'}
```

## File: facebookresearch_largeconceptmodel/tests/units/training/test_batch.py

Prompts

```
['create a toy PyArrow table with random source and target tensor columns for testing', 'use the pytest fixture to generate a temporary parquet train dataset config for unit tests', 'use the pytest fixture to generate a temporary parquet dev dataset config for unit tests', 'test ParquetDatasetConfig by writing partitioned parquet data and yielding a config object', 'review the simple_data function that creates random sonar embeddings as a PyArrow table', 'test the EmbeddingsBatch unbatch method by reconstructing a batch and verifying sequence and padding mask equality', 'test the EmbeddingsBatch get_last_element method by comparing extracted last elements against manually stacked expected values', 'run the test_unbatchon_embedding_batch test to verify EmbeddingsBatch unbatch roundtrip preserves sequences and padding masks', 'run the test_last_element_embedding_batch test to verify get_last_element returns correct terminal embeddings per sequence', 'review the test functions for EmbeddingsBatch unbatch and get_last_element to understand ragged sequence padding and batching behavior', 'test get_trainer using a builder function referenced via the _trainer_ config key', 'test get_trainer using a class constructor referenced via the _trainer_ config key', 'test that dataclass __post_init__ correctly computes derived field c from a and b', 'test that nested dataclass fields are populated from DictConfig sub-dictionaries', 'review how get_trainer resolves a dotted module path to instantiate a trainer from DictConfig', 'test the LCM trainer can be built, run training, and save the model correctly', 'compute the average evaluation loss across all validation datasets using the trainer', 'compare two PyTorch models by asserting all parameters match with torch.allclose', 'build an LCMTrainerBuilder from an LCMTrainingConfig to create a trainer for MSE training', 'load a trained LCM model from a model_card.yaml file using the card utils API']
```

Usage

```
{'test_unbatch_embedding_batch': 'test the EmbeddingsBatch unbatch method by reconstructing a batch and verifying sequence and padding mask equality', 'test_get_last_element_embedding_batch': 'test the EmbeddingsBatch get_last_element method by comparing extracted last elements against manually stacked expected values', 'run_embedding_batch_unbatch_test': 'run the test_unbatchon_embedding_batch test to verify EmbeddingsBatch unbatch roundtrip preserves sequences and padding masks', 'run_embedding_batch_last_element_test': 'run the test_last_element_embedding_batch test to verify get_last_element returns correct terminal embeddings per sequence', 'review_embedding_batch_test_functions': 'review the test functions for EmbeddingsBatch unbatch and get_last_element to understand ragged sequence padding and batching behavior'}
```

## File: facebookresearch_largeconceptmodel/tests/units/training/test_get_trainer.py

Prompts

```
['create a toy PyArrow table with random source and target tensor columns for testing', 'use the pytest fixture to generate a temporary parquet train dataset config for unit tests', 'use the pytest fixture to generate a temporary parquet dev dataset config for unit tests', 'test ParquetDatasetConfig by writing partitioned parquet data and yielding a config object', 'review the simple_data function that creates random sonar embeddings as a PyArrow table', 'test the EmbeddingsBatch unbatch method by reconstructing a batch and verifying sequence and padding mask equality', 'test the EmbeddingsBatch get_last_element method by comparing extracted last elements against manually stacked expected values', 'run the test_unbatchon_embedding_batch test to verify EmbeddingsBatch unbatch roundtrip preserves sequences and padding masks', 'run the test_last_element_embedding_batch test to verify get_last_element returns correct terminal embeddings per sequence', 'review the test functions for EmbeddingsBatch unbatch and get_last_element to understand ragged sequence padding and batching behavior', 'test get_trainer using a builder function referenced via the _trainer_ config key', 'test get_trainer using a class constructor referenced via the _trainer_ config key', 'test that dataclass __post_init__ correctly computes derived field c from a and b', 'test that nested dataclass fields are populated from DictConfig sub-dictionaries', 'review how get_trainer resolves a dotted module path to instantiate a trainer from DictConfig', 'test the LCM trainer can be built, run training, and save the model correctly', 'compute the average evaluation loss across all validation datasets using the trainer', 'compare two PyTorch models by asserting all parameters match with torch.allclose', 'build an LCMTrainerBuilder from an LCMTrainingConfig to create a trainer for MSE training', 'load a trained LCM model from a model_card.yaml file using the card utils API']
```

Usage

```
{'test_get_trainer_with_builder_fn': 'test get_trainer using a builder function referenced via the _trainer_ config key', 'test_get_trainer_with_class': 'test get_trainer using a class constructor referenced via the _trainer_ config key', 'test_dataclass_post_init_computed_field': 'test that dataclass __post_init__ correctly computes derived field c from a and b', 'test_config_nested_dataclass_from_dictconfig': 'test that nested dataclass fields are populated from DictConfig sub-dictionaries', 'review_get_trainer_instantiation': 'review how get_trainer resolves a dotted module path to instantiate a trainer from DictConfig'}
```

## File: facebookresearch_largeconceptmodel/tests/units/training/test_toy_task_trainer.py

Prompts

```
['create a toy PyArrow table with random source and target tensor columns for testing', 'use the pytest fixture to generate a temporary parquet train dataset config for unit tests', 'use the pytest fixture to generate a temporary parquet dev dataset config for unit tests', 'test ParquetDatasetConfig by writing partitioned parquet data and yielding a config object', 'review the simple_data function that creates random sonar embeddings as a PyArrow table', 'test the EmbeddingsBatch unbatch method by reconstructing a batch and verifying sequence and padding mask equality', 'test the EmbeddingsBatch get_last_element method by comparing extracted last elements against manually stacked expected values', 'run the test_unbatchon_embedding_batch test to verify EmbeddingsBatch unbatch roundtrip preserves sequences and padding masks', 'run the test_last_element_embedding_batch test to verify get_last_element returns correct terminal embeddings per sequence', 'review the test functions for EmbeddingsBatch unbatch and get_last_element to understand ragged sequence padding and batching behavior', 'test get_trainer using a builder function referenced via the _trainer_ config key', 'test get_trainer using a class constructor referenced via the _trainer_ config key', 'test that dataclass __post_init__ correctly computes derived field c from a and b', 'test that nested dataclass fields are populated from DictConfig sub-dictionaries', 'review how get_trainer resolves a dotted module path to instantiate a trainer from DictConfig', 'test the LCM trainer can be built, run training, and save the model correctly', 'compute the average evaluation loss across all validation datasets using the trainer', 'compare two PyTorch models by asserting all parameters match with torch.allclose', 'build an LCMTrainerBuilder from an LCMTrainingConfig to create a trainer for MSE training', 'load a trained LCM model from a model_card.yaml file using the card utils API']
```

Usage

```
{'test_toy_mse_training': 'test the LCM trainer can be built, run training, and save the model correctly', 'get_eval_loss': 'compute the average evaluation loss across all validation datasets using the trainer', 'compare_models': 'compare two PyTorch models by asserting all parameters match with torch.allclose', 'build_LCMTrainerBuilder': 'build an LCMTrainerBuilder from an LCMTrainingConfig to create a trainer for MSE training', 'load_model_from_card': 'load a trained LCM model from a model_card.yaml file using the card utils API'}
```

