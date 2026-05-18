# Agent Python Tools

- repo: facebookresearch/meta-agents-research-environments
- repo_uri: https://github.com/facebookresearch/meta-agents-research-environments

## File: facebookresearch_meta-agents-research-environments/are/simulation/scenarios/scenario_find_image_file/scenario.py

Prompts

```
["run the ScenarioFindImageFile scenario to test an agent's ability to find image files in a sandboxed file system", 'create a sandboxed file system with 10 text distractor files and one target image file for agent exploration', 'build oracle events defining the expected user request and agent response sequence for finding an image file', 'validate that the agent correctly identified llama.jpg as the image file in the sandboxed environment', 'register the ScenarioFindImageFile class with the scenario registry using the scenario_find_image_file identifier']
```

Usage

```
{'run_scenario_find_image_file': "run the ScenarioFindImageFile scenario to test an agent's ability to find image files in a sandboxed file system", 'init_and_populate_apps': 'create a sandboxed file system with 10 text distractor files and one target image file for agent exploration', 'build_events_flow': 'build oracle events defining the expected user request and agent response sequence for finding an image file', 'validate_scenario': 'validate that the agent correctly identified llama.jpg as the image file in the sandboxed environment', 'register_scenario': 'register the ScenarioFindImageFile class with the scenario registry using the scenario_find_image_file identifier'}
```

