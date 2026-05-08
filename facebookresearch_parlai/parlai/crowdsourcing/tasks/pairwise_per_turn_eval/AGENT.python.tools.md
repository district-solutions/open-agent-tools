# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/crowdsourcing/tasks/pairwise_per_turn_eval/bot_agent.py

Prompts

```
['create a PerTurnEvalTurkLikeAgent instance with opt, model_name, model_agent, and num_turns parameters', 'run the act method on PerTurnEvalTurkLikeAgent to generate a bot response using batch_act', 'review the PerTurnEvalTurkLikeAgent act method that uses batch_act instead of act for model inference', 'refactor the PerTurnEvalTurkLikeAgent act method to handle timeout or change normalization logic', 'summarize the PerTurnEvalTurkLikeAgent class that extends TurkLikeAgent for pairwise per-turn evaluation tasks', 'run a pairwise per turn evaluation task using a mephisto config and task directory', 'soft block MTurk workers using a task-specific qualification name to avoid collisions', 'load the database and process the mephisto configuration from a DictConfig object', 'initialize a SharedModelChatTaskState with a world module for pairwise evaluation tasks', 'validate and run a mephisto task configuration with shared state via the Operator class', 'create a PerTurnEvalBlueprint instance to run pairwise per-turn evaluation conversations between model pairs', 'validate task arguments and conversations needed string format before launching a per-turn eval task', 'parse a conversations needed string into a dict mapping model pairs to required conversation counts', 'load model options from a YAML config file and retrieve bot agents for active model pairs', 'format and inject the task question into the left pane HTML text for the frontend chat window', 'run a PerTurnEvalWorld parley loop to collect pairwise bot response ratings from a human agent', 'create a PerTurnEvalWorld instance with an agent, two bot workers, and optional context info', 'call make_world to build a PerTurnEvalWorld with two bot models selected by remaining conversation counts', 'call get_bot_worker to create a PerTurnEvalTurkLikeAgent wrapping a shared dialogue model agent', 'call validate_onboarding to check that onboarding data messages end with an ONBOARD_SUCCESS final status']
```

Usage

```
{'create_PerTurnEvalTurkLikeAgent': 'create a PerTurnEvalTurkLikeAgent instance with opt, model_name, model_agent, and num_turns parameters', 'run_PerTurnEvalTurkLikeAgent_act': 'run the act method on PerTurnEvalTurkLikeAgent to generate a bot response using batch_act', 'review_PerTurnEvalTurkLikeAgent_act': 'review the PerTurnEvalTurkLikeAgent act method that uses batch_act instead of act for model inference', 'refactor_PerTurnEvalTurkLikeAgent_act': 'refactor the PerTurnEvalTurkLikeAgent act method to handle timeout or change normalization logic', 'summarize_PerTurnEvalTurkLikeAgent': 'summarize the PerTurnEvalTurkLikeAgent class that extends TurkLikeAgent for pairwise per-turn evaluation tasks'}
```

## File: facebookresearch_parlai/parlai/crowdsourcing/tasks/pairwise_per_turn_eval/impl.py

Prompts

```
['create a PerTurnEvalTurkLikeAgent instance with opt, model_name, model_agent, and num_turns parameters', 'run the act method on PerTurnEvalTurkLikeAgent to generate a bot response using batch_act', 'review the PerTurnEvalTurkLikeAgent act method that uses batch_act instead of act for model inference', 'refactor the PerTurnEvalTurkLikeAgent act method to handle timeout or change normalization logic', 'summarize the PerTurnEvalTurkLikeAgent class that extends TurkLikeAgent for pairwise per-turn evaluation tasks', 'run a pairwise per turn evaluation task using a mephisto config and task directory', 'soft block MTurk workers using a task-specific qualification name to avoid collisions', 'load the database and process the mephisto configuration from a DictConfig object', 'initialize a SharedModelChatTaskState with a world module for pairwise evaluation tasks', 'validate and run a mephisto task configuration with shared state via the Operator class', 'create a PerTurnEvalBlueprint instance to run pairwise per-turn evaluation conversations between model pairs', 'validate task arguments and conversations needed string format before launching a per-turn eval task', 'parse a conversations needed string into a dict mapping model pairs to required conversation counts', 'load model options from a YAML config file and retrieve bot agents for active model pairs', 'format and inject the task question into the left pane HTML text for the frontend chat window', 'run a PerTurnEvalWorld parley loop to collect pairwise bot response ratings from a human agent', 'create a PerTurnEvalWorld instance with an agent, two bot workers, and optional context info', 'call make_world to build a PerTurnEvalWorld with two bot models selected by remaining conversation counts', 'call get_bot_worker to create a PerTurnEvalTurkLikeAgent wrapping a shared dialogue model agent', 'call validate_onboarding to check that onboarding data messages end with an ONBOARD_SUCCESS final status']
```

Usage

```
{'run_pairwise_per_turn_eval_task': 'run a pairwise per turn evaluation task using a mephisto config and task directory', 'soft_block_mturk_workers': 'soft block MTurk workers using a task-specific qualification name to avoid collisions', 'load_db_and_process_config': 'load the database and process the mephisto configuration from a DictConfig object', 'shared_model_chat_task_state': 'initialize a SharedModelChatTaskState with a world module for pairwise evaluation tasks', 'operator_validate_and_run_config': 'validate and run a mephisto task configuration with shared state via the Operator class'}
```

## File: facebookresearch_parlai/parlai/crowdsourcing/tasks/pairwise_per_turn_eval/per_turn_eval_blueprint.py

Prompts

```
['create a PerTurnEvalTurkLikeAgent instance with opt, model_name, model_agent, and num_turns parameters', 'run the act method on PerTurnEvalTurkLikeAgent to generate a bot response using batch_act', 'review the PerTurnEvalTurkLikeAgent act method that uses batch_act instead of act for model inference', 'refactor the PerTurnEvalTurkLikeAgent act method to handle timeout or change normalization logic', 'summarize the PerTurnEvalTurkLikeAgent class that extends TurkLikeAgent for pairwise per-turn evaluation tasks', 'run a pairwise per turn evaluation task using a mephisto config and task directory', 'soft block MTurk workers using a task-specific qualification name to avoid collisions', 'load the database and process the mephisto configuration from a DictConfig object', 'initialize a SharedModelChatTaskState with a world module for pairwise evaluation tasks', 'validate and run a mephisto task configuration with shared state via the Operator class', 'create a PerTurnEvalBlueprint instance to run pairwise per-turn evaluation conversations between model pairs', 'validate task arguments and conversations needed string format before launching a per-turn eval task', 'parse a conversations needed string into a dict mapping model pairs to required conversation counts', 'load model options from a YAML config file and retrieve bot agents for active model pairs', 'format and inject the task question into the left pane HTML text for the frontend chat window', 'run a PerTurnEvalWorld parley loop to collect pairwise bot response ratings from a human agent', 'create a PerTurnEvalWorld instance with an agent, two bot workers, and optional context info', 'call make_world to build a PerTurnEvalWorld with two bot models selected by remaining conversation counts', 'call get_bot_worker to create a PerTurnEvalTurkLikeAgent wrapping a shared dialogue model agent', 'call validate_onboarding to check that onboarding data messages end with an ONBOARD_SUCCESS final status']
```

Usage

```
{'create_per_turn_eval_blueprint': 'create a PerTurnEvalBlueprint instance to run pairwise per-turn evaluation conversations between model pairs', 'validate_assert_task_args': 'validate task arguments and conversations needed string format before launching a per-turn eval task', 'process_conversations_needed': 'parse a conversations needed string into a dict mapping model pairs to required conversation counts', 'load_shared_models': 'load model options from a YAML config file and retrieve bot agents for active model pairs', 'customize_left_pane_text': 'format and inject the task question into the left pane HTML text for the frontend chat window'}
```

## File: facebookresearch_parlai/parlai/crowdsourcing/tasks/pairwise_per_turn_eval/worlds.py

Prompts

```
['create a PerTurnEvalTurkLikeAgent instance with opt, model_name, model_agent, and num_turns parameters', 'run the act method on PerTurnEvalTurkLikeAgent to generate a bot response using batch_act', 'review the PerTurnEvalTurkLikeAgent act method that uses batch_act instead of act for model inference', 'refactor the PerTurnEvalTurkLikeAgent act method to handle timeout or change normalization logic', 'summarize the PerTurnEvalTurkLikeAgent class that extends TurkLikeAgent for pairwise per-turn evaluation tasks', 'run a pairwise per turn evaluation task using a mephisto config and task directory', 'soft block MTurk workers using a task-specific qualification name to avoid collisions', 'load the database and process the mephisto configuration from a DictConfig object', 'initialize a SharedModelChatTaskState with a world module for pairwise evaluation tasks', 'validate and run a mephisto task configuration with shared state via the Operator class', 'create a PerTurnEvalBlueprint instance to run pairwise per-turn evaluation conversations between model pairs', 'validate task arguments and conversations needed string format before launching a per-turn eval task', 'parse a conversations needed string into a dict mapping model pairs to required conversation counts', 'load model options from a YAML config file and retrieve bot agents for active model pairs', 'format and inject the task question into the left pane HTML text for the frontend chat window', 'run a PerTurnEvalWorld parley loop to collect pairwise bot response ratings from a human agent', 'create a PerTurnEvalWorld instance with an agent, two bot workers, and optional context info', 'call make_world to build a PerTurnEvalWorld with two bot models selected by remaining conversation counts', 'call get_bot_worker to create a PerTurnEvalTurkLikeAgent wrapping a shared dialogue model agent', 'call validate_onboarding to check that onboarding data messages end with an ONBOARD_SUCCESS final status']
```

Usage

```
{'run_per_turn_eval_world': 'run a PerTurnEvalWorld parley loop to collect pairwise bot response ratings from a human agent', 'create_per_turn_eval_world': 'create a PerTurnEvalWorld instance with an agent, two bot workers, and optional context info', 'make_world_pairwise_eval': 'call make_world to build a PerTurnEvalWorld with two bot models selected by remaining conversation counts', 'get_bot_worker': 'call get_bot_worker to create a PerTurnEvalTurkLikeAgent wrapping a shared dialogue model agent', 'validate_onboarding': 'call validate_onboarding to check that onboarding data messages end with an ONBOARD_SUCCESS final status'}
```

