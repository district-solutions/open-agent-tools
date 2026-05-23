# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/pipelines/tests/test_configs.py

Prompts

```
['load a Hydra config from a YAML file with optional overrides and unnesting', 'validate a YAML config file against a Python dataclass type using promote_config', 'validate a nested YAML config file with a top-level config key against a dataclass', 'validate a line processor config file against a dataclass type', 'instantiate a StopesModule from a YAML config file mimicking CLI behavior', 'run the global mining pipeline with hydra config to mine bitext pairs from multilingual shards', 'create digit text and meta TSV files for a given language and number range', 'test the digits2vec function that converts digit words to binary bit vectors', 'build a ToyNumbersEncoder module that encodes digit text lines into numpy embedding matrices', 'review the text2number function that converts space-separated digit words into an integer']
```

Usage

```
{'load_conf': 'load a Hydra config from a YAML file with optional overrides and unnesting', 'validate_conf': 'validate a YAML config file against a Python dataclass type using promote_config', 'validate_nested_conf': 'validate a nested YAML config file with a top-level config key against a dataclass', 'validate_line_processor_conf': 'validate a line processor config file against a dataclass type', 'instantiate_module': 'instantiate a StopesModule from a YAML config file mimicking CLI behavior'}
```

## File: facebookresearch_stopes/stopes/pipelines/tests/test_global_mining.py

Prompts

```
['load a Hydra config from a YAML file with optional overrides and unnesting', 'validate a YAML config file against a Python dataclass type using promote_config', 'validate a nested YAML config file with a top-level config key against a dataclass', 'validate a line processor config file against a dataclass type', 'instantiate a StopesModule from a YAML config file mimicking CLI behavior', 'run the global mining pipeline with hydra config to mine bitext pairs from multilingual shards', 'create digit text and meta TSV files for a given language and number range', 'test the digits2vec function that converts digit words to binary bit vectors', 'build a ToyNumbersEncoder module that encodes digit text lines into numpy embedding matrices', 'review the text2number function that converts space-separated digit words into an integer']
```

Usage

```
{'run_global_mining_pipeline': 'run the global mining pipeline with hydra config to mine bitext pairs from multilingual shards', 'create_digits_test_data': 'create digit text and meta TSV files for a given language and number range', 'test_digits2vec_encoding': 'test the digits2vec function that converts digit words to binary bit vectors', 'build_toy_numbers_encoder': 'build a ToyNumbersEncoder module that encodes digit text lines into numpy embedding matrices', 'review_text2number_conversion': 'review the text2number function that converts space-separated digit words into an integer'}
```

