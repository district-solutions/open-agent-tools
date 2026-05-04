# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/pce/validator/message_templates/validator_step_names.py

Prompts

```
['get all validation step code names by calling ValidationStepNames.code_names()', 'look up a ValidationStepNames enum member from its code_name string using from_code_name()', 'access the human-readable formatted_name of a validation step like ValidationStepNames.VPC_CIDR.formatted_name', 'access the snake_case code_name of a validation step like ValidationStepNames.FIREWALL.code_name', "iterate over all ValidationStepNames enum members to access each step's attributes"]
```

Usage

```
{'list_validation_step_code_names': 'get all validation step code names by calling ValidationStepNames.code_names()', 'lookup_validation_step_by_code_name': 'look up a ValidationStepNames enum member from its code_name string using from_code_name()', 'access_validation_step_formatted_name': 'access the human-readable formatted_name of a validation step like ValidationStepNames.VPC_CIDR.formatted_name', 'access_validation_step_code_name': 'access the snake_case code_name of a validation step like ValidationStepNames.FIREWALL.code_name', 'iterate_validation_steps': "iterate over all ValidationStepNames enum members to access each step's attributes"}
```

