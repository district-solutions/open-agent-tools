# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/evaluation/feature_importance/feature_importance_base.py

Prompts

```
['review the FeatureImportanceBase dataclass and its compute_feature_importance abstract method', 'create a subclass of FeatureImportanceBase that implements compute_feature_importance to return a DataFrame', 'summarize the FeatureImportanceBase class which takes a model and sorted feature IDs', 'test that FeatureImportanceBase compute_feature_importance raises NotImplementedError as expected', 'refactor FeatureImportanceBase to add validation for the model and sorted_feature_ids fields', 'compute feature importance by perturbing each feature and measuring prediction changes across batches', 'create a default perturbation function that shuffles feature values within a batch using a given key', 'review the FeatureImportancePerturbation class and its compute_feature_importance method for perturbation-based analysis', 'build a feature importance analysis pipeline using FeatureImportancePerturbation with a custom prediction function', 'test the FeatureImportancePerturbation compute_feature_importance method with a mock data loader and model']
```

Usage

```
{'review_FeatureImportanceBase': 'review the FeatureImportanceBase dataclass and its compute_feature_importance abstract method', 'create_FeatureImportanceBase_subclass': 'create a subclass of FeatureImportanceBase that implements compute_feature_importance to return a DataFrame', 'summarize_FeatureImportanceBase': 'summarize the FeatureImportanceBase class which takes a model and sorted feature IDs', 'test_FeatureImportanceBase_compute': 'test that FeatureImportanceBase compute_feature_importance raises NotImplementedError as expected', 'refactor_FeatureImportanceBase': 'refactor FeatureImportanceBase to add validation for the model and sorted_feature_ids fields'}
```

## File: facebookresearch_reagent/reagent/evaluation/feature_importance/feature_importance_perturbation.py

Prompts

```
['review the FeatureImportanceBase dataclass and its compute_feature_importance abstract method', 'create a subclass of FeatureImportanceBase that implements compute_feature_importance to return a DataFrame', 'summarize the FeatureImportanceBase class which takes a model and sorted feature IDs', 'test that FeatureImportanceBase compute_feature_importance raises NotImplementedError as expected', 'refactor FeatureImportanceBase to add validation for the model and sorted_feature_ids fields', 'compute feature importance by perturbing each feature and measuring prediction changes across batches', 'create a default perturbation function that shuffles feature values within a batch using a given key', 'review the FeatureImportancePerturbation class and its compute_feature_importance method for perturbation-based analysis', 'build a feature importance analysis pipeline using FeatureImportancePerturbation with a custom prediction function', 'test the FeatureImportancePerturbation compute_feature_importance method with a mock data loader and model']
```

Usage

```
{'compute_feature_importance_perturbation': 'compute feature importance by perturbing each feature and measuring prediction changes across batches', 'create_default_perturb_fn': 'create a default perturbation function that shuffles feature values within a batch using a given key', 'review_FeatureImportancePerturbation_class': 'review the FeatureImportancePerturbation class and its compute_feature_importance method for perturbation-based analysis', 'build_feature_importance_analysis': 'build a feature importance analysis pipeline using FeatureImportancePerturbation with a custom prediction function', 'test_perturbation_feature_importance': 'test the FeatureImportancePerturbation compute_feature_importance method with a mock data loader and model'}
```

