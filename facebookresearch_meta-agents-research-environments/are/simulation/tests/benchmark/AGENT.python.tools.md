# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/tests/benchmark/test_huggingface_loader.py

Prompts

```
['test that run_number is properly preserved from HuggingFace dataset rows to benchmark scenarios', 'test that run_number is preserved when oracle data is merged into HuggingFace scenarios', 'test that scenarios with different run_numbers are properly grouped in multi-scenario validation results', 'test backward compatibility for scenarios that do not have a run_number field set', 'test that run_number is correctly extracted from HuggingFace metadata rows and applied to scenarios']
```

Usage

```
{'test_run_number_preservation': 'test that run_number is properly preserved from HuggingFace dataset rows to benchmark scenarios', 'test_run_number_preservation_with_oracle_data': 'test that run_number is preserved when oracle data is merged into HuggingFace scenarios', 'test_scenario_grouping_in_validation_result': 'test that scenarios with different run_numbers are properly grouped in multi-scenario validation results', 'test_scenario_without_run_number': 'test backward compatibility for scenarios that do not have a run_number field set', 'test_run_number_from_hf_metadata': 'test that run_number is correctly extracted from HuggingFace metadata rows and applied to scenarios'}
```

