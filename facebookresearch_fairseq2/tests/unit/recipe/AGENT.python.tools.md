# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/unit/recipe/test_optim.py

Prompts

```
['test prepare_parameter_groups to split model parameters into optimizer groups by regex patterns', 'test prepare_parameter_groups returns all model parameters when no parameter group configs are specified', 'test prepare_parameter_groups when regex configs cover all model parameters exhaustively', 'test prepare_parameter_groups logs a warning when a parameter group config matches no parameters', 'review the FooParamGroupConfig dataclass that defines lr, betas, and weight_decay optimizer settings', 'test the _StandardSweepTagGenerator to generate a sweep tag from a recipe config dictionary', 'test that _StandardSweepTagGenerator produces the same tag regardless of config key ordering', 'test _StandardSweepTagGenerator with a custom sweep_format string containing config placeholders and hash', 'test that _StandardSweepTagGenerator raises ValidationError when sweep_format has mismatched braces', 'test that _StandardSweepTagGenerator raises ValidationError when sweep_format references config keys that do not exist']
```

Usage

```
{'test_prepare_parameter_groups': 'test prepare_parameter_groups to split model parameters into optimizer groups by regex patterns', 'test_parameter_groups_no_config': 'test prepare_parameter_groups returns all model parameters when no parameter group configs are specified', 'test_exhaustive_parameter_groups': 'test prepare_parameter_groups when regex configs cover all model parameters exhaustively', 'test_empty_parameter_group_warning': 'test prepare_parameter_groups logs a warning when a parameter group config matches no parameters', 'review_FooParamGroupConfig': 'review the FooParamGroupConfig dataclass that defines lr, betas, and weight_decay optimizer settings'}
```

## File: facebookresearch_fairseq2/tests/unit/recipe/test_sweep_tag.py

Prompts

```
['test prepare_parameter_groups to split model parameters into optimizer groups by regex patterns', 'test prepare_parameter_groups returns all model parameters when no parameter group configs are specified', 'test prepare_parameter_groups when regex configs cover all model parameters exhaustively', 'test prepare_parameter_groups logs a warning when a parameter group config matches no parameters', 'review the FooParamGroupConfig dataclass that defines lr, betas, and weight_decay optimizer settings', 'test the _StandardSweepTagGenerator to generate a sweep tag from a recipe config dictionary', 'test that _StandardSweepTagGenerator produces the same tag regardless of config key ordering', 'test _StandardSweepTagGenerator with a custom sweep_format string containing config placeholders and hash', 'test that _StandardSweepTagGenerator raises ValidationError when sweep_format has mismatched braces', 'test that _StandardSweepTagGenerator raises ValidationError when sweep_format references config keys that do not exist']
```

Usage

```
{'test_sweep_tag_generation': 'test the _StandardSweepTagGenerator to generate a sweep tag from a recipe config dictionary', 'test_sweep_tag_key_order_invariance': 'test that _StandardSweepTagGenerator produces the same tag regardless of config key ordering', 'test_sweep_tag_custom_format': 'test _StandardSweepTagGenerator with a custom sweep_format string containing config placeholders and hash', 'test_sweep_tag_invalid_format_validation': 'test that _StandardSweepTagGenerator raises ValidationError when sweep_format has mismatched braces', 'test_sweep_tag_unknown_key_validation': 'test that _StandardSweepTagGenerator raises ValidationError when sweep_format references config keys that do not exist'}
```

