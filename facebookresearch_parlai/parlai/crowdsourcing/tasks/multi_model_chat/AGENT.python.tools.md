# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/crowdsourcing/tasks/multi_model_chat/agents.py

Prompts

```
['create a MultipartyModelChatAgent with decision and speech agents for multi-party dialogue', 'use RandomSpeakerDecicionsAgent to randomly select the next speaker in a multi-party chat', 'flatten a list of persona dicts into a delimited string with flatten_personas', 'flatten a location dict into a delimited string with flatten_location', 'get the conversation context string from MultipartyModelChatAgent including personas, location, and history', 'run the MultiLIGHTModelChatResultsCompiler to compile and save human model chat conversation results as a DataFrame', 'build an argparse parser for the MultiLIGHTModelChatResultsCompiler with max convos per worker and min word count options', 'run the compile_and_save_results method to process task unit data and save conversation results to CSV files', 'review the compile_results method that iterates task units, filters bad conversations, and aggregates per model statistics', 'refactor the MultiLIGHTModelChatResultsCompiler subclass to override compile_results with MultiLIGHT-specific persona and turn rate logic', 'run a MultipartyChatWorld parley loop to conduct a multi-agent conversation with personas and save dialog data', 'create a ContextGenerator instance with an optional seed to generate random conversation contexts with personas and locations', 'get the list of conversation settings containing persona definitions and location descriptions for multi-party chat', 'make a MultipartyChatWorld instance by selecting a bot model and generating context from the context generator', 'review the MultipartyChatWorld parley method to understand turn-taking logic between human agents and bot workers']
```

Usage

```
{'create_multiparty_chat_agent': 'create a MultipartyModelChatAgent with decision and speech agents for multi-party dialogue', 'use_random_speaker_agent': 'use RandomSpeakerDecicionsAgent to randomly select the next speaker in a multi-party chat', 'flatten_personas_to_string': 'flatten a list of persona dicts into a delimited string with flatten_personas', 'flatten_location_to_string': 'flatten a location dict into a delimited string with flatten_location', 'get_chat_context': 'get the conversation context string from MultipartyModelChatAgent including personas, location, and history'}
```

## File: facebookresearch_parlai/parlai/crowdsourcing/tasks/multi_model_chat/compile_results.py

Prompts

```
['create a MultipartyModelChatAgent with decision and speech agents for multi-party dialogue', 'use RandomSpeakerDecicionsAgent to randomly select the next speaker in a multi-party chat', 'flatten a list of persona dicts into a delimited string with flatten_personas', 'flatten a location dict into a delimited string with flatten_location', 'get the conversation context string from MultipartyModelChatAgent including personas, location, and history', 'run the MultiLIGHTModelChatResultsCompiler to compile and save human model chat conversation results as a DataFrame', 'build an argparse parser for the MultiLIGHTModelChatResultsCompiler with max convos per worker and min word count options', 'run the compile_and_save_results method to process task unit data and save conversation results to CSV files', 'review the compile_results method that iterates task units, filters bad conversations, and aggregates per model statistics', 'refactor the MultiLIGHTModelChatResultsCompiler subclass to override compile_results with MultiLIGHT-specific persona and turn rate logic', 'run a MultipartyChatWorld parley loop to conduct a multi-agent conversation with personas and save dialog data', 'create a ContextGenerator instance with an optional seed to generate random conversation contexts with personas and locations', 'get the list of conversation settings containing persona definitions and location descriptions for multi-party chat', 'make a MultipartyChatWorld instance by selecting a bot model and generating context from the context generator', 'review the MultipartyChatWorld parley method to understand turn-taking logic between human agents and bot workers']
```

Usage

```
{'compile_multiLIGHT_chat_results': 'run the MultiLIGHTModelChatResultsCompiler to compile and save human model chat conversation results as a DataFrame', 'setup_args_multiLIGHT_compiler': 'build an argparse parser for the MultiLIGHTModelChatResultsCompiler with max convos per worker and min word count options', 'compile_and_save_results': 'run the compile_and_save_results method to process task unit data and save conversation results to CSV files', 'review_compile_results_method': 'review the compile_results method that iterates task units, filters bad conversations, and aggregates per model statistics', 'refactor_multiLIGHT_compiler_subclass': 'refactor the MultiLIGHTModelChatResultsCompiler subclass to override compile_results with MultiLIGHT-specific persona and turn rate logic'}
```

## File: facebookresearch_parlai/parlai/crowdsourcing/tasks/multi_model_chat/multiparty_worlds.py

Prompts

```
['create a MultipartyModelChatAgent with decision and speech agents for multi-party dialogue', 'use RandomSpeakerDecicionsAgent to randomly select the next speaker in a multi-party chat', 'flatten a list of persona dicts into a delimited string with flatten_personas', 'flatten a location dict into a delimited string with flatten_location', 'get the conversation context string from MultipartyModelChatAgent including personas, location, and history', 'run the MultiLIGHTModelChatResultsCompiler to compile and save human model chat conversation results as a DataFrame', 'build an argparse parser for the MultiLIGHTModelChatResultsCompiler with max convos per worker and min word count options', 'run the compile_and_save_results method to process task unit data and save conversation results to CSV files', 'review the compile_results method that iterates task units, filters bad conversations, and aggregates per model statistics', 'refactor the MultiLIGHTModelChatResultsCompiler subclass to override compile_results with MultiLIGHT-specific persona and turn rate logic', 'run a MultipartyChatWorld parley loop to conduct a multi-agent conversation with personas and save dialog data', 'create a ContextGenerator instance with an optional seed to generate random conversation contexts with personas and locations', 'get the list of conversation settings containing persona definitions and location descriptions for multi-party chat', 'make a MultipartyChatWorld instance by selecting a bot model and generating context from the context generator', 'review the MultipartyChatWorld parley method to understand turn-taking logic between human agents and bot workers']
```

Usage

```
{'run_multiparty_chat_world': 'run a MultipartyChatWorld parley loop to conduct a multi-agent conversation with personas and save dialog data', 'create_context_generator': 'create a ContextGenerator instance with an optional seed to generate random conversation contexts with personas and locations', 'get_settings': 'get the list of conversation settings containing persona definitions and location descriptions for multi-party chat', 'make_world': 'make a MultipartyChatWorld instance by selecting a bot model and generating context from the context generator', 'review_multiparty_chat_world_parley': 'review the MultipartyChatWorld parley method to understand turn-taking logic between human agents and bot workers'}
```

