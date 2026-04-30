# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/ml_models/admin.py

Prompts

```
['delete the admin action method that removes predictions for selected ModelRun instances in bulk', 'delete all predictions and associated metadata from a ModelRun including annotations and stats', 'create a ModelInterface with title, description, skill_name, input_fields, and output_classes for a project', 'create a ThirdPartyModelVersion with provider, provider_model_id, and prompt for a parent ModelInterface', 'check if a user has permission to access a ModelInterface, ThirdPartyModelVersion, or ModelRun via organization match', 'validate that a value is a non-empty list of strings for model input_fields or output_classes']
```

Usage

```
{'delete_model_run_predictions': 'delete the admin action method that removes predictions for selected ModelRun instances in bulk'}
```

## File: HumanSignal_label-studio/label_studio/ml_models/models.py

Prompts

```
['delete the admin action method that removes predictions for selected ModelRun instances in bulk', 'delete all predictions and associated metadata from a ModelRun including annotations and stats', 'create a ModelInterface with title, description, skill_name, input_fields, and output_classes for a project', 'create a ThirdPartyModelVersion with provider, provider_model_id, and prompt for a parent ModelInterface', 'check if a user has permission to access a ModelInterface, ThirdPartyModelVersion, or ModelRun via organization match', 'validate that a value is a non-empty list of strings for model input_fields or output_classes']
```

Usage

```
{'delete_ModelRun_predictions': 'delete all predictions and associated metadata from a ModelRun including annotations and stats', 'create_ModelInterface': 'create a ModelInterface with title, description, skill_name, input_fields, and output_classes for a project', 'create_ThirdPartyModelVersion': 'create a ThirdPartyModelVersion with provider, provider_model_id, and prompt for a parent ModelInterface', 'check_permission': 'check if a user has permission to access a ModelInterface, ThirdPartyModelVersion, or ModelRun via organization match', 'validate_string_list': 'validate that a value is a non-empty list of strings for model input_fields or output_classes'}
```

