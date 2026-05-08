# Agent Python Tools

- repo: facebookresearch/openlth
- repo_uri: https://github.com/facebookresearch/open_lth

## File: facebookresearch_openlth/foundations/test/test_hparams.py

Prompts

```
['create a dataclass subclassing Hparams with typed fields, _name, and _description for hyperparameter management', 'add hyperparameter arguments from an Hparams dataclass to an argparse ArgumentParser with optional prefix and defaults', 'create an Hparams instance from parsed argparse Namespace arguments with optional prefix support', 'test nested Hparams dataclasses where inner hyperparameters are flattened with underscore-separated argument names', 'test the canonical string representation of Hparams showing only non-default field values sorted alphabetically', 'test the Step class constructor with iteration and iterations_per_epoch arguments', 'test the Step.from_iteration method to create a Step from an iteration number', 'test the Step.from_epoch method to create a Step from epoch and iteration values', 'test the Step.from_str method to parse strings like 5ep3it into Step objects', 'test the Step class comparison operators for equality and ordering checks']
```

Usage

```
{'create_hparams_dataclass': 'create a dataclass subclassing Hparams with typed fields, _name, and _description for hyperparameter management', 'add_args_to_parser': 'add hyperparameter arguments from an Hparams dataclass to an argparse ArgumentParser with optional prefix and defaults', 'create_from_args': 'create an Hparams instance from parsed argparse Namespace arguments with optional prefix support', 'test_nested_hparams': 'test nested Hparams dataclasses where inner hyperparameters are flattened with underscore-separated argument names', 'test_canonical_string_repr': 'test the canonical string representation of Hparams showing only non-default field values sorted alphabetically'}
```

## File: facebookresearch_openlth/foundations/test/test_step.py

Prompts

```
['create a dataclass subclassing Hparams with typed fields, _name, and _description for hyperparameter management', 'add hyperparameter arguments from an Hparams dataclass to an argparse ArgumentParser with optional prefix and defaults', 'create an Hparams instance from parsed argparse Namespace arguments with optional prefix support', 'test nested Hparams dataclasses where inner hyperparameters are flattened with underscore-separated argument names', 'test the canonical string representation of Hparams showing only non-default field values sorted alphabetically', 'test the Step class constructor with iteration and iterations_per_epoch arguments', 'test the Step.from_iteration method to create a Step from an iteration number', 'test the Step.from_epoch method to create a Step from epoch and iteration values', 'test the Step.from_str method to parse strings like 5ep3it into Step objects', 'test the Step class comparison operators for equality and ordering checks']
```

Usage

```
{'test_Step_constructor': 'test the Step class constructor with iteration and iterations_per_epoch arguments', 'test_Step_from_iteration': 'test the Step.from_iteration method to create a Step from an iteration number', 'test_Step_from_epoch': 'test the Step.from_epoch method to create a Step from epoch and iteration values', 'test_Step_from_str': 'test the Step.from_str method to parse strings like 5ep3it into Step objects', 'test_Step_comparisons': 'test the Step class comparison operators for equality and ordering checks'}
```

