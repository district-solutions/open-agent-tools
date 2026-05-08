# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/projects/safety_bench/utils/perspective_api.py

Prompts

```
['get the Perspective API key from credentials file or prompt the user to enter one', 'build a PerspectiveAPIClientManager instance using an opt dictionary with a perspective_api_key', 'get the toxicity score for a text string using the Perspective API client', 'check if a text string is classified as offensive using the in operator on the client manager', 'review the PerspectiveAPIClientManager class and its rate limiting retry logic for quota exceeded errors', 'collect model inputs and responses from a ParlAI task using a model wrapper agent', 'check a list of text responses for offensive content using classifier, string matcher, and Perspective API', 'collect model responses by passing a list of input strings through a model wrapper', 'write a text log of model inputs, outputs, and safety scores to a file', 'write a JSON report of safety evaluation results to a file', 'register a model wrapper class under a name so it is available via the CLI', 'load a registered model wrapper by its path from the MODEL_WRAPPER_REGISTRY', 'discover and import all model wrapper modules from the safety_bench.model_wrappers package', 'review the MODEL_WRAPPER_REGISTRY dictionary to see which model wrappers are currently registered', 'refactor the register_model_wrapper decorator to add validation or logging for registered wrapper names']
```

Usage

```
{'get_perspective_api_key': 'get the Perspective API key from credentials file or prompt the user to enter one', 'build_PerspectiveAPIClientManager': 'build a PerspectiveAPIClientManager instance using an opt dictionary with a perspective_api_key', 'get_perspective_api_toxicity_score': 'get the toxicity score for a text string using the Perspective API client', 'check_offensive_with_contains': 'check if a text string is classified as offensive using the in operator on the client manager', 'review_PerspectiveAPIClientManager': 'review the PerspectiveAPIClientManager class and its rate limiting retry logic for quota exceeded errors'}
```

## File: facebookresearch_parlai/projects/safety_bench/utils/safety_testing.py

Prompts

```
['get the Perspective API key from credentials file or prompt the user to enter one', 'build a PerspectiveAPIClientManager instance using an opt dictionary with a perspective_api_key', 'get the toxicity score for a text string using the Perspective API client', 'check if a text string is classified as offensive using the in operator on the client manager', 'review the PerspectiveAPIClientManager class and its rate limiting retry logic for quota exceeded errors', 'collect model inputs and responses from a ParlAI task using a model wrapper agent', 'check a list of text responses for offensive content using classifier, string matcher, and Perspective API', 'collect model responses by passing a list of input strings through a model wrapper', 'write a text log of model inputs, outputs, and safety scores to a file', 'write a JSON report of safety evaluation results to a file', 'register a model wrapper class under a name so it is available via the CLI', 'load a registered model wrapper by its path from the MODEL_WRAPPER_REGISTRY', 'discover and import all model wrapper modules from the safety_bench.model_wrappers package', 'review the MODEL_WRAPPER_REGISTRY dictionary to see which model wrappers are currently registered', 'refactor the register_model_wrapper decorator to add validation or logging for registered wrapper names']
```

Usage

```
{'collect_task_data_and_model_response': 'collect model inputs and responses from a ParlAI task using a model wrapper agent', 'check_texts_with_safety_tooling': 'check a list of text responses for offensive content using classifier, string matcher, and Perspective API', 'collect_model_responses': 'collect model responses by passing a list of input strings through a model wrapper', 'write_log': 'write a text log of model inputs, outputs, and safety scores to a file', 'write_report': 'write a JSON report of safety evaluation results to a file'}
```

## File: facebookresearch_parlai/projects/safety_bench/utils/wrapper_loading.py

Prompts

```
['get the Perspective API key from credentials file or prompt the user to enter one', 'build a PerspectiveAPIClientManager instance using an opt dictionary with a perspective_api_key', 'get the toxicity score for a text string using the Perspective API client', 'check if a text string is classified as offensive using the in operator on the client manager', 'review the PerspectiveAPIClientManager class and its rate limiting retry logic for quota exceeded errors', 'collect model inputs and responses from a ParlAI task using a model wrapper agent', 'check a list of text responses for offensive content using classifier, string matcher, and Perspective API', 'collect model responses by passing a list of input strings through a model wrapper', 'write a text log of model inputs, outputs, and safety scores to a file', 'write a JSON report of safety evaluation results to a file', 'register a model wrapper class under a name so it is available via the CLI', 'load a registered model wrapper by its path from the MODEL_WRAPPER_REGISTRY', 'discover and import all model wrapper modules from the safety_bench.model_wrappers package', 'review the MODEL_WRAPPER_REGISTRY dictionary to see which model wrappers are currently registered', 'refactor the register_model_wrapper decorator to add validation or logging for registered wrapper names']
```

Usage

```
{'register_model_wrapper': 'register a model wrapper class under a name so it is available via the CLI', 'load_wrapper_module': 'load a registered model wrapper by its path from the MODEL_WRAPPER_REGISTRY', 'setup_wrapper_registry': 'discover and import all model wrapper modules from the safety_bench.model_wrappers package', 'review_MODEL_WRAPPER_REGISTRY': 'review the MODEL_WRAPPER_REGISTRY dictionary to see which model wrappers are currently registered', 'refactor_register_model_wrapper': 'refactor the register_model_wrapper decorator to add validation or logging for registered wrapper names'}
```

