# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/crowdsourcing/projects/multisession_chat/human_eval/compile_results.py

Prompts

```
['run the ModelChatResultsCompiler to compile and save human plus model chat conversation results from result folders', 'call compile_results on ModelChatResultsCompiler to process conversation JSON files and return a pandas DataFrame of all conversations', 'call setup_args on ModelChatResultsCompiler to get an argument parser with hit-block-list, results-folders, model-nickname, and completed-run-stats-path options', 'use the AcceptabilityChecker inside ModelChatResultsCompiler to detect unacceptable messages in human utterances during conversation compilation', 'run compile_results to generate and save pairwise_ratings.json mapping initial data IDs to final ratings in the output folder', 'run the main crowdsourcing task using hydra config and mephisto blueprint', 'check that the bot model name in completed run stats matches the conversations needed string', 'configure the ScriptConfig dataclass with monitoring log rate and task directory defaults', 'register the ScriptConfig module with the mephisto hydra config system', 'run a model chat crowdsourcing task using the run_task function with hydra config', 'create a ModelChatWorld instance with an agent, bot, model name, and context info for persona-based chat', 'run the initial turn of a ModelChatWorld to start a conversation between a human agent and bot', 'get the final chat data dictionary with model name, personas, and context info from a completed session', 'prepare acceptability checking parameters for BST-style conversations with violation type filtering', 'make a ModelChatWorld by selecting a bot model based on remaining conversation counts and context generation']
```

Usage

```
{'run_compile_human_model_chat_results': 'run the ModelChatResultsCompiler to compile and save human plus model chat conversation results from result folders', 'compile_results_dataframe': 'call compile_results on ModelChatResultsCompiler to process conversation JSON files and return a pandas DataFrame of all conversations', 'setup_args_model_chat_compiler': 'call setup_args on ModelChatResultsCompiler to get an argument parser with hit-block-list, results-folders, model-nickname, and completed-run-stats-path options', 'check_acceptability_violations': 'use the AcceptabilityChecker inside ModelChatResultsCompiler to detect unacceptable messages in human utterances during conversation compilation', 'save_pairwise_ratings': 'run compile_results to generate and save pairwise_ratings.json mapping initial data IDs to final ratings in the output folder'}
```

## File: facebookresearch_parlai/parlai/crowdsourcing/projects/multisession_chat/human_eval/run.py

Prompts

```
['run the ModelChatResultsCompiler to compile and save human plus model chat conversation results from result folders', 'call compile_results on ModelChatResultsCompiler to process conversation JSON files and return a pandas DataFrame of all conversations', 'call setup_args on ModelChatResultsCompiler to get an argument parser with hit-block-list, results-folders, model-nickname, and completed-run-stats-path options', 'use the AcceptabilityChecker inside ModelChatResultsCompiler to detect unacceptable messages in human utterances during conversation compilation', 'run compile_results to generate and save pairwise_ratings.json mapping initial data IDs to final ratings in the output folder', 'run the main crowdsourcing task using hydra config and mephisto blueprint', 'check that the bot model name in completed run stats matches the conversations needed string', 'configure the ScriptConfig dataclass with monitoring log rate and task directory defaults', 'register the ScriptConfig module with the mephisto hydra config system', 'run a model chat crowdsourcing task using the run_task function with hydra config', 'create a ModelChatWorld instance with an agent, bot, model name, and context info for persona-based chat', 'run the initial turn of a ModelChatWorld to start a conversation between a human agent and bot', 'get the final chat data dictionary with model name, personas, and context info from a completed session', 'prepare acceptability checking parameters for BST-style conversations with violation type filtering', 'make a ModelChatWorld by selecting a bot model based on remaining conversation counts and context generation']
```

Usage

```
{'run_crowdsourcing_task': 'run the main crowdsourcing task using hydra config and mephisto blueprint', 'check_override_opt': 'check that the bot model name in completed run stats matches the conversations needed string', 'configure_scriptconfig': 'configure the ScriptConfig dataclass with monitoring log rate and task directory defaults', 'register_script_config': 'register the ScriptConfig module with the mephisto hydra config system', 'run_model_chat_task': 'run a model chat crowdsourcing task using the run_task function with hydra config'}
```

## File: facebookresearch_parlai/parlai/crowdsourcing/projects/multisession_chat/human_eval/worlds.py

Prompts

```
['run the ModelChatResultsCompiler to compile and save human plus model chat conversation results from result folders', 'call compile_results on ModelChatResultsCompiler to process conversation JSON files and return a pandas DataFrame of all conversations', 'call setup_args on ModelChatResultsCompiler to get an argument parser with hit-block-list, results-folders, model-nickname, and completed-run-stats-path options', 'use the AcceptabilityChecker inside ModelChatResultsCompiler to detect unacceptable messages in human utterances during conversation compilation', 'run compile_results to generate and save pairwise_ratings.json mapping initial data IDs to final ratings in the output folder', 'run the main crowdsourcing task using hydra config and mephisto blueprint', 'check that the bot model name in completed run stats matches the conversations needed string', 'configure the ScriptConfig dataclass with monitoring log rate and task directory defaults', 'register the ScriptConfig module with the mephisto hydra config system', 'run a model chat crowdsourcing task using the run_task function with hydra config', 'create a ModelChatWorld instance with an agent, bot, model name, and context info for persona-based chat', 'run the initial turn of a ModelChatWorld to start a conversation between a human agent and bot', 'get the final chat data dictionary with model name, personas, and context info from a completed session', 'prepare acceptability checking parameters for BST-style conversations with violation type filtering', 'make a ModelChatWorld by selecting a bot model based on remaining conversation counts and context generation']
```

Usage

```
{'create_modelchatworld': 'create a ModelChatWorld instance with an agent, bot, model name, and context info for persona-based chat', 'run_initial_turn': 'run the initial turn of a ModelChatWorld to start a conversation between a human agent and bot', 'get_final_chat_data': 'get the final chat data dictionary with model name, personas, and context info from a completed session', 'prepare_acceptability_checking': 'prepare acceptability checking parameters for BST-style conversations with violation type filtering', 'make_world': 'make a ModelChatWorld by selecting a bot model based on remaining conversation counts and context generation'}
```

