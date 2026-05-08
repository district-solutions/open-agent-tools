# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/safety_bench/prepare_integration_tests.py

Prompts

```
['run the PrepareIntegrationTests script with --wrapper blenderbot_90M --safety-setting adversarial to prepare adversarial evaluation data', 'run the PrepareIntegrationTests script with --wrapper blenderbot_90M --safety-setting nonadversarial to prepare non-adversarial evaluation data', 'call prepare_integration_tests with an Opt dict containing wrapper, log_folder, and safety_setting keys', 'call setup_args to configure a ParlaiParser with wrapper, log-folder, safety-setting, and debug arguments', 'call _check_log_dir with a directory path to validate and create the log folder if needed', 'run safety unit tests for a model wrapper using the --wrapper flag', 'run tests checking if a model generates offensive language via --tests-to-run generate', 'run tests checking model responses to offensive language via --tests-to-run response', 'set up command line arguments for the safety unit tests including wrapper and log folder options', 'print a color-coded safety test report with metrics for unsafe generation and response categories']
```

Usage

```
{'run_integration_tests_adversarial': 'run the PrepareIntegrationTests script with --wrapper blenderbot_90M --safety-setting adversarial to prepare adversarial evaluation data', 'run_integration_tests_nonadversarial': 'run the PrepareIntegrationTests script with --wrapper blenderbot_90M --safety-setting nonadversarial to prepare non-adversarial evaluation data', 'prepare_integration_tests_function': 'call prepare_integration_tests with an Opt dict containing wrapper, log_folder, and safety_setting keys', 'setup_args_parser': 'call setup_args to configure a ParlaiParser with wrapper, log-folder, safety-setting, and debug arguments', 'check_log_dir': 'call _check_log_dir with a directory path to validate and create the log folder if needed'}
```

## File: facebookresearch_parlai/projects/safety_bench/run_unit_tests.py

Prompts

```
['run the PrepareIntegrationTests script with --wrapper blenderbot_90M --safety-setting adversarial to prepare adversarial evaluation data', 'run the PrepareIntegrationTests script with --wrapper blenderbot_90M --safety-setting nonadversarial to prepare non-adversarial evaluation data', 'call prepare_integration_tests with an Opt dict containing wrapper, log_folder, and safety_setting keys', 'call setup_args to configure a ParlaiParser with wrapper, log-folder, safety-setting, and debug arguments', 'call _check_log_dir with a directory path to validate and create the log folder if needed', 'run safety unit tests for a model wrapper using the --wrapper flag', 'run tests checking if a model generates offensive language via --tests-to-run generate', 'run tests checking model responses to offensive language via --tests-to-run response', 'set up command line arguments for the safety unit tests including wrapper and log folder options', 'print a color-coded safety test report with metrics for unsafe generation and response categories']
```

Usage

```
{'run_safety_unit_tests': 'run safety unit tests for a model wrapper using the --wrapper flag', 'run_generate_offensive_language_test': 'run tests checking if a model generates offensive language via --tests-to-run generate', 'run_response_to_offensive_language_test': 'run tests checking model responses to offensive language via --tests-to-run response', 'setup_args': 'set up command line arguments for the safety unit tests including wrapper and log folder options', 'pretty_report': 'print a color-coded safety test report with metrics for unsafe generation and response categories'}
```

