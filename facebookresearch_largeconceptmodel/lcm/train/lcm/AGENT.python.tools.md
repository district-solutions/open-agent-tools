# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/lcm/train/lcm/criterion.py

Prompts

```
['compute MSE loss between flattened predictions and target tensors with optional scaling and normalization', 'create an LCMCriterionConfig dataclass to configure whether to compute RMSE instead of MSE', 'build an LCMCriterion instance with a config, model, and optional training style for loss computation', "review the LCMCriterion sonar_normalizer property to retrieve the model's SonarNormalizer from the model or frontend", 'test the LCMCriterion abstract call method to compute loss given an LCMInput batch', 'create an LCM trainer from an LCMTrainingConfig to start training a large concept model', 'build an LCM trainer by loading data, creating the model, and setting up FSDP or DDP wrapping', 'setup the reconstruction criterion for the LCM trainer using the CriterionsFactory', 'setup training and validation metric bags for tracking loss summands across datasets', 'create a model card from the last saved checkpoint with model architecture and config metadata']
```

Usage

```
{'compute_standard_mse': 'compute MSE loss between flattened predictions and target tensors with optional scaling and normalization', 'create_LCMCriterionConfig': 'create an LCMCriterionConfig dataclass to configure whether to compute RMSE instead of MSE', 'build_LCMCriterion': 'build an LCMCriterion instance with a config, model, and optional training style for loss computation', 'review_LCMCriterion_sonar_normalizer': "review the LCMCriterion sonar_normalizer property to retrieve the model's SonarNormalizer from the model or frontend", 'test_LCMCriterion_call': 'test the LCMCriterion abstract call method to compute loss given an LCMInput batch'}
```

## File: facebookresearch_largeconceptmodel/lcm/train/lcm/trainer.py

Prompts

```
['compute MSE loss between flattened predictions and target tensors with optional scaling and normalization', 'create an LCMCriterionConfig dataclass to configure whether to compute RMSE instead of MSE', 'build an LCMCriterion instance with a config, model, and optional training style for loss computation', "review the LCMCriterion sonar_normalizer property to retrieve the model's SonarNormalizer from the model or frontend", 'test the LCMCriterion abstract call method to compute loss given an LCMInput batch', 'create an LCM trainer from an LCMTrainingConfig to start training a large concept model', 'build an LCM trainer by loading data, creating the model, and setting up FSDP or DDP wrapping', 'setup the reconstruction criterion for the LCM trainer using the CriterionsFactory', 'setup training and validation metric bags for tracking loss summands across datasets', 'create a model card from the last saved checkpoint with model architecture and config metadata']
```

Usage

```
{'prepare_lcm_trainer': 'create an LCM trainer from an LCMTrainingConfig to start training a large concept model', 'LCMTrainerBuilder_build_trainer': 'build an LCM trainer by loading data, creating the model, and setting up FSDP or DDP wrapping', 'LCMTrainer_setup_criterion': 'setup the reconstruction criterion for the LCM trainer using the CriterionsFactory', 'LCMTrainer_setup_metric_bags': 'setup training and validation metric bags for tracking loss summands across datasets', 'LCMTrainer_create_model_card_for_last_checkpoint': 'create a model card from the last saved checkpoint with model architecture and config metadata'}
```

