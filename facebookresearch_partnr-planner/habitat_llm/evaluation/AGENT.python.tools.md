# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/evaluation/centralized_evaluation_runner.py

Prompts

```
['run a centralized evaluation where a single planner coordinates actions across multiple agents in a simulation environment', 'get low level actions for all agents given an instruction, observations, and world graph states', 'reset the centralized planner to prepare for a new evaluation episode', 'initialize the centralized planner from Hydra config and assign agents with optional single-turn planning mode', 'review the CentralizedEvaluationRunner class that extends EvaluationRunner for multi-agent centralized control with planner coordination', 'initialize separate planners for each agent using the evaluation runner config and environment interface', 'reset all planner parameters after finishing one episode in the decentralized evaluation runner', 'review the DecentralizedEvaluationRunner class and its decentralized multi-agent evaluation strategy', 'summarize the DecentralizedEvaluationRunner class which extends EvaluationRunner for multi-agent decentralized control', 'run an instruction through the EvaluationRunner planner and collect metrics until the task is done', 'create an ActionHistoryElement to track an agent action with timestamp, response, and world graph state', 'create a StateHistoryElement to record an agent state with timestamp and agent UID', 'reset the EvaluationRunner to clear metrics, agent positions, and planner state for the next episode', 'log planner prompts, traces, and step-by-step info to JSON and text files for analysis']
```

Usage

```
{'run_centralized_evaluation': 'run a centralized evaluation where a single planner coordinates actions across multiple agents in a simulation environment', 'get_low_level_actions': 'get low level actions for all agents given an instruction, observations, and world graph states', 'reset_planners': 'reset the centralized planner to prepare for a new evaluation episode', 'initialize_planners': 'initialize the centralized planner from Hydra config and assign agents with optional single-turn planning mode', 'review_CentralizedEvaluationRunner': 'review the CentralizedEvaluationRunner class that extends EvaluationRunner for multi-agent centralized control with planner coordination'}
```

## File: facebookresearch_partnr-planner/habitat_llm/evaluation/decentralized_evaluation_runner.py

Prompts

```
['run a centralized evaluation where a single planner coordinates actions across multiple agents in a simulation environment', 'get low level actions for all agents given an instruction, observations, and world graph states', 'reset the centralized planner to prepare for a new evaluation episode', 'initialize the centralized planner from Hydra config and assign agents with optional single-turn planning mode', 'review the CentralizedEvaluationRunner class that extends EvaluationRunner for multi-agent centralized control with planner coordination', 'initialize separate planners for each agent using the evaluation runner config and environment interface', 'reset all planner parameters after finishing one episode in the decentralized evaluation runner', 'review the DecentralizedEvaluationRunner class and its decentralized multi-agent evaluation strategy', 'summarize the DecentralizedEvaluationRunner class which extends EvaluationRunner for multi-agent decentralized control', 'run an instruction through the EvaluationRunner planner and collect metrics until the task is done', 'create an ActionHistoryElement to track an agent action with timestamp, response, and world graph state', 'create a StateHistoryElement to record an agent state with timestamp and agent UID', 'reset the EvaluationRunner to clear metrics, agent positions, and planner state for the next episode', 'log planner prompts, traces, and step-by-step info to JSON and text files for analysis']
```

Usage

```
{'initialize_decentralized_planners': 'initialize separate planners for each agent using the evaluation runner config and environment interface', 'get_low_level_actions': 'get low level actions from all planners given an instruction, observations, and world graph', 'reset_planners_after_episode': 'reset all planner parameters after finishing one episode in the decentralized evaluation runner', 'review_DecentralizedEvaluationRunner': 'review the DecentralizedEvaluationRunner class and its decentralized multi-agent evaluation strategy', 'summarize_evaluation_runner': 'summarize the DecentralizedEvaluationRunner class which extends EvaluationRunner for multi-agent decentralized control'}
```

## File: facebookresearch_partnr-planner/habitat_llm/evaluation/evaluation_runner.py

Prompts

```
['run a centralized evaluation where a single planner coordinates actions across multiple agents in a simulation environment', 'get low level actions for all agents given an instruction, observations, and world graph states', 'reset the centralized planner to prepare for a new evaluation episode', 'initialize the centralized planner from Hydra config and assign agents with optional single-turn planning mode', 'review the CentralizedEvaluationRunner class that extends EvaluationRunner for multi-agent centralized control with planner coordination', 'initialize separate planners for each agent using the evaluation runner config and environment interface', 'reset all planner parameters after finishing one episode in the decentralized evaluation runner', 'review the DecentralizedEvaluationRunner class and its decentralized multi-agent evaluation strategy', 'summarize the DecentralizedEvaluationRunner class which extends EvaluationRunner for multi-agent decentralized control', 'run an instruction through the EvaluationRunner planner and collect metrics until the task is done', 'create an ActionHistoryElement to track an agent action with timestamp, response, and world graph state', 'create a StateHistoryElement to record an agent state with timestamp and agent UID', 'reset the EvaluationRunner to clear metrics, agent positions, and planner state for the next episode', 'log planner prompts, traces, and step-by-step info to JSON and text files for analysis']
```

Usage

```
{'run_instruction_with_evaluation_runner': 'run an instruction through the EvaluationRunner planner and collect metrics until the task is done', 'create_action_history_element': 'create an ActionHistoryElement to track an agent action with timestamp, response, and world graph state', 'create_state_history_element': 'create a StateHistoryElement to record an agent state with timestamp and agent UID', 'reset_evaluation_runner': 'reset the EvaluationRunner to clear metrics, agent positions, and planner state for the next episode', 'log_planner_data': 'log planner prompts, traces, and step-by-step info to JSON and text files for analysis'}
```

