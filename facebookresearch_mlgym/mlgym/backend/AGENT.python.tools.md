# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/mlgym/backend/base.py

Prompts

```
['create a ModelArguments dataclass to configure model name, cost limits, temperature, and top_p for MLGym', 'build an APIStats object to track total cost, task cost, tokens sent, tokens received, and api calls', 'add two APIStats objects together to aggregate cost and token usage across multiple model runs', 'update model statistics with input tokens, output tokens, and cost while enforcing cost limit thresholds', 'convert a conversation history list to API messages format with role and content fields', 'create a SubmitBaselineModel that runs baseline.py then submits results for testing', 'create a SubmitBaselineRLModel that runs src/train.py then submits results for testing', 'create a SubmitBaselineWrongModel that runs baseline.py and ls then submits wrong artefacts', 'create a ReplayModel that replays actions from a JSON file for testing', 'test the ReplayModel query method to verify it returns actions from a replay file', 'create a HumanModel instance with ModelArguments and a list of Command objects for interactive input', 'query the HumanModel to get user input with optional multi-line command support', 'create a HumanThoughtModel that captures both thought and action input from a human user', 'query the HumanThoughtModel to get thought and action input formatted with code fences', 'update the HumanModel stats with input tokens, output tokens, and cost values', 'query an LLM model using a list of history items and return the model response', 'update token counts and cost statistics for the LLM model and check cost limits', 'initialize the LiteLLM model client with model metadata from litellm model cost database', 'validate that input tokens do not exceed the model maximum input token limit', 'get a SubmitBaselineModel instance by passing ModelArguments with model_name set to submit_baseline', 'get a HumanModel instance by passing ModelArguments with model_name set to human and a list of commands', 'get a HumanThoughtModel instance by passing ModelArguments with model_name set to human_thought and commands', 'get a ReplayModel instance by passing ModelArguments with model_name set to replay and a replay_path', 'get a LiteLLMModel instance by passing ModelArguments with model_name starting with litellm prefix']
```

Usage

```
{'create_model_arguments': 'create a ModelArguments dataclass to configure model name, cost limits, temperature, and top_p for MLGym', 'build_api_stats': 'build an APIStats object to track total cost, task cost, tokens sent, tokens received, and api calls', 'add_api_stats': 'add two APIStats objects together to aggregate cost and token usage across multiple model runs', 'update_stats': 'update model statistics with input tokens, output tokens, and cost while enforcing cost limit thresholds', 'convert_history_to_messages': 'convert a conversation history list to API messages format with role and content fields'}
```

## File: facebookresearch_mlgym/mlgym/backend/debugging.py

Prompts

```
['create a ModelArguments dataclass to configure model name, cost limits, temperature, and top_p for MLGym', 'build an APIStats object to track total cost, task cost, tokens sent, tokens received, and api calls', 'add two APIStats objects together to aggregate cost and token usage across multiple model runs', 'update model statistics with input tokens, output tokens, and cost while enforcing cost limit thresholds', 'convert a conversation history list to API messages format with role and content fields', 'create a SubmitBaselineModel that runs baseline.py then submits results for testing', 'create a SubmitBaselineRLModel that runs src/train.py then submits results for testing', 'create a SubmitBaselineWrongModel that runs baseline.py and ls then submits wrong artefacts', 'create a ReplayModel that replays actions from a JSON file for testing', 'test the ReplayModel query method to verify it returns actions from a replay file', 'create a HumanModel instance with ModelArguments and a list of Command objects for interactive input', 'query the HumanModel to get user input with optional multi-line command support', 'create a HumanThoughtModel that captures both thought and action input from a human user', 'query the HumanThoughtModel to get thought and action input formatted with code fences', 'update the HumanModel stats with input tokens, output tokens, and cost values', 'query an LLM model using a list of history items and return the model response', 'update token counts and cost statistics for the LLM model and check cost limits', 'initialize the LiteLLM model client with model metadata from litellm model cost database', 'validate that input tokens do not exceed the model maximum input token limit', 'get a SubmitBaselineModel instance by passing ModelArguments with model_name set to submit_baseline', 'get a HumanModel instance by passing ModelArguments with model_name set to human and a list of commands', 'get a HumanThoughtModel instance by passing ModelArguments with model_name set to human_thought and commands', 'get a ReplayModel instance by passing ModelArguments with model_name set to replay and a replay_path', 'get a LiteLLMModel instance by passing ModelArguments with model_name starting with litellm prefix']
```

Usage

```
{'create_submit_baseline_model': 'create a SubmitBaselineModel that runs baseline.py then submits results for testing', 'create_submit_baseline_rl_model': 'create a SubmitBaselineRLModel that runs src/train.py then submits results for testing', 'create_submit_baseline_wrong_model': 'create a SubmitBaselineWrongModel that runs baseline.py and ls then submits wrong artefacts', 'create_replay_model': 'create a ReplayModel that replays actions from a JSON file for testing', 'test_replay_model_query': 'test the ReplayModel query method to verify it returns actions from a replay file'}
```

## File: facebookresearch_mlgym/mlgym/backend/human.py

Prompts

```
['create a ModelArguments dataclass to configure model name, cost limits, temperature, and top_p for MLGym', 'build an APIStats object to track total cost, task cost, tokens sent, tokens received, and api calls', 'add two APIStats objects together to aggregate cost and token usage across multiple model runs', 'update model statistics with input tokens, output tokens, and cost while enforcing cost limit thresholds', 'convert a conversation history list to API messages format with role and content fields', 'create a SubmitBaselineModel that runs baseline.py then submits results for testing', 'create a SubmitBaselineRLModel that runs src/train.py then submits results for testing', 'create a SubmitBaselineWrongModel that runs baseline.py and ls then submits wrong artefacts', 'create a ReplayModel that replays actions from a JSON file for testing', 'test the ReplayModel query method to verify it returns actions from a replay file', 'create a HumanModel instance with ModelArguments and a list of Command objects for interactive input', 'query the HumanModel to get user input with optional multi-line command support', 'create a HumanThoughtModel that captures both thought and action input from a human user', 'query the HumanThoughtModel to get thought and action input formatted with code fences', 'update the HumanModel stats with input tokens, output tokens, and cost values', 'query an LLM model using a list of history items and return the model response', 'update token counts and cost statistics for the LLM model and check cost limits', 'initialize the LiteLLM model client with model metadata from litellm model cost database', 'validate that input tokens do not exceed the model maximum input token limit', 'get a SubmitBaselineModel instance by passing ModelArguments with model_name set to submit_baseline', 'get a HumanModel instance by passing ModelArguments with model_name set to human and a list of commands', 'get a HumanThoughtModel instance by passing ModelArguments with model_name set to human_thought and commands', 'get a ReplayModel instance by passing ModelArguments with model_name set to replay and a replay_path', 'get a LiteLLMModel instance by passing ModelArguments with model_name starting with litellm prefix']
```

Usage

```
{'create_human_model': 'create a HumanModel instance with ModelArguments and a list of Command objects for interactive input', 'query_human_model': 'query the HumanModel to get user input with optional multi-line command support', 'create_human_thought_model': 'create a HumanThoughtModel that captures both thought and action input from a human user', 'query_human_thought_model': 'query the HumanThoughtModel to get thought and action input formatted with code fences', 'update_human_model_stats': 'update the HumanModel stats with input tokens, output tokens, and cost values'}
```

## File: facebookresearch_mlgym/mlgym/backend/litellm.py

Prompts

```
['create a ModelArguments dataclass to configure model name, cost limits, temperature, and top_p for MLGym', 'build an APIStats object to track total cost, task cost, tokens sent, tokens received, and api calls', 'add two APIStats objects together to aggregate cost and token usage across multiple model runs', 'update model statistics with input tokens, output tokens, and cost while enforcing cost limit thresholds', 'convert a conversation history list to API messages format with role and content fields', 'create a SubmitBaselineModel that runs baseline.py then submits results for testing', 'create a SubmitBaselineRLModel that runs src/train.py then submits results for testing', 'create a SubmitBaselineWrongModel that runs baseline.py and ls then submits wrong artefacts', 'create a ReplayModel that replays actions from a JSON file for testing', 'test the ReplayModel query method to verify it returns actions from a replay file', 'create a HumanModel instance with ModelArguments and a list of Command objects for interactive input', 'query the HumanModel to get user input with optional multi-line command support', 'create a HumanThoughtModel that captures both thought and action input from a human user', 'query the HumanThoughtModel to get thought and action input formatted with code fences', 'update the HumanModel stats with input tokens, output tokens, and cost values', 'query an LLM model using a list of history items and return the model response', 'update token counts and cost statistics for the LLM model and check cost limits', 'initialize the LiteLLM model client with model metadata from litellm model cost database', 'validate that input tokens do not exceed the model maximum input token limit', 'get a SubmitBaselineModel instance by passing ModelArguments with model_name set to submit_baseline', 'get a HumanModel instance by passing ModelArguments with model_name set to human and a list of commands', 'get a HumanThoughtModel instance by passing ModelArguments with model_name set to human_thought and commands', 'get a ReplayModel instance by passing ModelArguments with model_name set to replay and a replay_path', 'get a LiteLLMModel instance by passing ModelArguments with model_name starting with litellm prefix']
```

Usage

```
{'query_llm_with_history': 'query an LLM model using a list of history items and return the model response', 'update_llm_stats': 'update token counts and cost statistics for the LLM model and check cost limits', 'convert_history_to_messages': 'convert a list of history items into formatted messages for LLM API calls', 'setup_litellm_client': 'initialize the LiteLLM model client with model metadata from litellm model cost database', 'check_context_window': 'validate that input tokens do not exceed the model maximum input token limit'}
```

## File: facebookresearch_mlgym/mlgym/backend/utils.py

Prompts

```
['create a ModelArguments dataclass to configure model name, cost limits, temperature, and top_p for MLGym', 'build an APIStats object to track total cost, task cost, tokens sent, tokens received, and api calls', 'add two APIStats objects together to aggregate cost and token usage across multiple model runs', 'update model statistics with input tokens, output tokens, and cost while enforcing cost limit thresholds', 'convert a conversation history list to API messages format with role and content fields', 'create a SubmitBaselineModel that runs baseline.py then submits results for testing', 'create a SubmitBaselineRLModel that runs src/train.py then submits results for testing', 'create a SubmitBaselineWrongModel that runs baseline.py and ls then submits wrong artefacts', 'create a ReplayModel that replays actions from a JSON file for testing', 'test the ReplayModel query method to verify it returns actions from a replay file', 'create a HumanModel instance with ModelArguments and a list of Command objects for interactive input', 'query the HumanModel to get user input with optional multi-line command support', 'create a HumanThoughtModel that captures both thought and action input from a human user', 'query the HumanThoughtModel to get thought and action input formatted with code fences', 'update the HumanModel stats with input tokens, output tokens, and cost values', 'query an LLM model using a list of history items and return the model response', 'update token counts and cost statistics for the LLM model and check cost limits', 'initialize the LiteLLM model client with model metadata from litellm model cost database', 'validate that input tokens do not exceed the model maximum input token limit', 'get a SubmitBaselineModel instance by passing ModelArguments with model_name set to submit_baseline', 'get a HumanModel instance by passing ModelArguments with model_name set to human and a list of commands', 'get a HumanThoughtModel instance by passing ModelArguments with model_name set to human_thought and commands', 'get a ReplayModel instance by passing ModelArguments with model_name set to replay and a replay_path', 'get a LiteLLMModel instance by passing ModelArguments with model_name starting with litellm prefix']
```

Usage

```
{'get_model_submit_baseline': 'get a SubmitBaselineModel instance by passing ModelArguments with model_name set to submit_baseline', 'get_model_human': 'get a HumanModel instance by passing ModelArguments with model_name set to human and a list of commands', 'get_model_human_thought': 'get a HumanThoughtModel instance by passing ModelArguments with model_name set to human_thought and commands', 'get_model_replay': 'get a ReplayModel instance by passing ModelArguments with model_name set to replay and a replay_path', 'get_model_litellm': 'get a LiteLLMModel instance by passing ModelArguments with model_name starting with litellm prefix'}
```

