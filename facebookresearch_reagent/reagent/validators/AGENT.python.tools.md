# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/validators/model_validator.py

Prompts

```
['create a subclass of ModelValidator that implements do_validate to check RL training output metrics', 'validate an RLTrainingOutput object using a ModelValidator subclass and return a ValidationResult', 'register a custom ModelValidator subclass in the workflow using the RegistryMeta metaclass', 'review the abstract do_validate method signature and required parameters for ModelValidator subclasses', 'summarize the ModelValidator base class structure and its validate and do_validate methods', 'create a NoValidation validator instance that performs no validation on RL training output', 'run do_validate on a NoValidation instance to get NoValidationResults with should_publish True', 'extend ModelValidator to create a custom validator with its own do_validate logic', 'review the NoValidation class to understand the validator pattern for RL training output', 'summarize the do_validate method which returns NoValidationResults with should_publish set to True']
```

Usage

```
{'create_model_validator_subclass': 'create a subclass of ModelValidator that implements do_validate to check RL training output metrics', 'validate_rl_training_output': 'validate an RLTrainingOutput object using a ModelValidator subclass and return a ValidationResult', 'register_model_validator_in_workflow': 'register a custom ModelValidator subclass in the workflow using the RegistryMeta metaclass', 'review_model_validator_do_validate': 'review the abstract do_validate method signature and required parameters for ModelValidator subclasses', 'summarize_model_validator_class': 'summarize the ModelValidator base class structure and its validate and do_validate methods'}
```

## File: facebookresearch_reagent/reagent/validators/no_validation.py

Prompts

```
['create a subclass of ModelValidator that implements do_validate to check RL training output metrics', 'validate an RLTrainingOutput object using a ModelValidator subclass and return a ValidationResult', 'register a custom ModelValidator subclass in the workflow using the RegistryMeta metaclass', 'review the abstract do_validate method signature and required parameters for ModelValidator subclasses', 'summarize the ModelValidator base class structure and its validate and do_validate methods', 'create a NoValidation validator instance that performs no validation on RL training output', 'run do_validate on a NoValidation instance to get NoValidationResults with should_publish True', 'extend ModelValidator to create a custom validator with its own do_validate logic', 'review the NoValidation class to understand the validator pattern for RL training output', 'summarize the do_validate method which returns NoValidationResults with should_publish set to True']
```

Usage

```
{'create_NoValidation_validator': 'create a NoValidation validator instance that performs no validation on RL training output', 'run_NoValidation_do_validate': 'run do_validate on a NoValidation instance to get NoValidationResults with should_publish True', 'extend_ModelValidator': 'extend ModelValidator to create a custom validator with its own do_validate logic', 'review_NoValidation_class': 'review the NoValidation class to understand the validator pattern for RL training output', 'summarize_NoValidation_do_validate': 'summarize the do_validate method which returns NoValidationResults with should_publish set to True'}
```

