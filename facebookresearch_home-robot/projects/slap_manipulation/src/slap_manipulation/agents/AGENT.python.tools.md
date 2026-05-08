# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/slap_manipulation/src/slap_manipulation/agents/general_language_agent.py

Prompts

```
['build a GeneralLanguageAgent instance from config to execute LLM-generated task plans for robot manipulation', 'run get_task_plans_from_llm to parse LLM predictions from a JSON file into executable robot code lists', 'run get_task_plans_from_oracle to load ground truth task plans from a dataset JSON file', 'test get_taskplan_for_robot to parse LLM function call strings into verb noun adverb step dictionaries', 'review separate_into_codelist to split LLM-generated function call strings into individual callable steps', 'initialize a PeractAgent with config to set up PerceiverIO encoder and PerceiverActor agent', 'load pretrained weights into the PerAct model from the configured model path', 'create model input dictionary with proprioceptive state, language command, and time index for PerAct', 'predict the next 6D pose action from environment observations using the PerAct model', 'reset the PeractAgent to clear previous inputs and time step state', 'initialize a SLAPAgent with config, device, and task_id for robot manipulation skill prediction', 'load IPM and APM model weights into the SLAPAgent for interaction and action prediction', 'predict interaction point and action from environment observations using the SLAPAgent predict method', 'convert robot observations into voxelized point cloud input for the interaction prediction module', 'reset the SLAPAgent interaction point and keyframe state to prepare for a new prediction cycle']
```

Usage

```
{'build_GeneralLanguageAgent': 'build a GeneralLanguageAgent instance from config to execute LLM-generated task plans for robot manipulation', 'run_get_task_plans_from_llm': 'run get_task_plans_from_llm to parse LLM predictions from a JSON file into executable robot code lists', 'run_get_task_plans_from_oracle': 'run get_task_plans_from_oracle to load ground truth task plans from a dataset JSON file', 'test_get_taskplan_for_robot': 'test get_taskplan_for_robot to parse LLM function call strings into verb noun adverb step dictionaries', 'review_separate_into_codelist': 'review separate_into_codelist to split LLM-generated function call strings into individual callable steps'}
```

## File: facebookresearch_home-robot/projects/slap_manipulation/src/slap_manipulation/agents/peract_agent.py

Prompts

```
['build a GeneralLanguageAgent instance from config to execute LLM-generated task plans for robot manipulation', 'run get_task_plans_from_llm to parse LLM predictions from a JSON file into executable robot code lists', 'run get_task_plans_from_oracle to load ground truth task plans from a dataset JSON file', 'test get_taskplan_for_robot to parse LLM function call strings into verb noun adverb step dictionaries', 'review separate_into_codelist to split LLM-generated function call strings into individual callable steps', 'initialize a PeractAgent with config to set up PerceiverIO encoder and PerceiverActor agent', 'load pretrained weights into the PerAct model from the configured model path', 'create model input dictionary with proprioceptive state, language command, and time index for PerAct', 'predict the next 6D pose action from environment observations using the PerAct model', 'reset the PeractAgent to clear previous inputs and time step state', 'initialize a SLAPAgent with config, device, and task_id for robot manipulation skill prediction', 'load IPM and APM model weights into the SLAPAgent for interaction and action prediction', 'predict interaction point and action from environment observations using the SLAPAgent predict method', 'convert robot observations into voxelized point cloud input for the interaction prediction module', 'reset the SLAPAgent interaction point and keyframe state to prepare for a new prediction cycle']
```

Usage

```
{'init_PeractAgent': 'initialize a PeractAgent with config to set up PerceiverIO encoder and PerceiverActor agent', 'load_models_PeractAgent': 'load pretrained weights into the PerAct model from the configured model path', 'create_peract_input_PeractAgent': 'create model input dictionary with proprioceptive state, language command, and time index for PerAct', 'predict_PeractAgent': 'predict the next 6D pose action from environment observations using the PerAct model', 'reset_PeractAgent': 'reset the PeractAgent to clear previous inputs and time step state'}
```

## File: facebookresearch_home-robot/projects/slap_manipulation/src/slap_manipulation/agents/slap_agent.py

Prompts

```
['build a GeneralLanguageAgent instance from config to execute LLM-generated task plans for robot manipulation', 'run get_task_plans_from_llm to parse LLM predictions from a JSON file into executable robot code lists', 'run get_task_plans_from_oracle to load ground truth task plans from a dataset JSON file', 'test get_taskplan_for_robot to parse LLM function call strings into verb noun adverb step dictionaries', 'review separate_into_codelist to split LLM-generated function call strings into individual callable steps', 'initialize a PeractAgent with config to set up PerceiverIO encoder and PerceiverActor agent', 'load pretrained weights into the PerAct model from the configured model path', 'create model input dictionary with proprioceptive state, language command, and time index for PerAct', 'predict the next 6D pose action from environment observations using the PerAct model', 'reset the PeractAgent to clear previous inputs and time step state', 'initialize a SLAPAgent with config, device, and task_id for robot manipulation skill prediction', 'load IPM and APM model weights into the SLAPAgent for interaction and action prediction', 'predict interaction point and action from environment observations using the SLAPAgent predict method', 'convert robot observations into voxelized point cloud input for the interaction prediction module', 'reset the SLAPAgent interaction point and keyframe state to prepare for a new prediction cycle']
```

Usage

```
{'init_SLAPAgent': 'initialize a SLAPAgent with config, device, and task_id for robot manipulation skill prediction', 'load_models_SLAPAgent': 'load IPM and APM model weights into the SLAPAgent for interaction and action prediction', 'predict_SLAPAgent': 'predict interaction point and action from environment observations using the SLAPAgent predict method', 'create_interaction_prediction_input_from_obs': 'convert robot observations into voxelized point cloud input for the interaction prediction module', 'reset_SLAPAgent': 'reset the SLAPAgent interaction point and keyframe state to prepare for a new prediction cycle'}
```

