# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/parlai_chat/parlai_chat_agent_state.py

Prompts

```
['load stored ParlAI chat agent state data from a JSON file into the agent object', 'get parsed ParlAI chat data including agent name, messages, and world data from the agent state', 'update the ParlAI chat agent state by appending a new live message with a timestamp', 'save all ParlAI chat agent messages and metadata to a JSON state file on disk', 'get the task start and end timestamps from the first and last messages in the agent state', 'create a ParlAIChatBlueprintArgs dataclass to configure world file, task description, and conversation count for a ParlAI chat task', 'create a SharedParlAITaskState dataclass to hold frontend task options, world options, and the world module for shared state', 'review the ParlAIChatBlueprint constructor that loads context from CSV or JSONL files and dynamically imports the world module', 'test the ParlAIChatBlueprint assert_task_args method to validate world file existence, conversation count, and optional source paths', 'refactor the ParlAIChatBlueprint get_frontend_args method to customize task description, preview HTML, frame height, and mobile blocking options', 'rebuild the ParlAIChatTaskBuilder frontend by running npm install and webpack dev build', 'build a custom bundle from a source directory with main.js, style.css, and components', 'build the ParlAI frontend and copy bundle.js, index.html, and static files into a server directory', 'review the ParlAIChatTaskBuilder class and its frontend build methods for the Mephisto blueprint', 'refactor the ParlAIChatTaskBuilder rebuild_core method to use a different build tool instead of webpack', 'run onboarding for an OnboardingAgent using a ParlAI onboarding world and wait for submit', 'run a ParlAI task world assignment with multiple agents until the episode is done', 'run a single agent unit in a ParlAI world and collect world data on completion', 'create a MephistoAgentWrapper to use a Mephisto agent as a ParlAI agent in a world', 'cleanup and shutdown the onboarding world for a specific onboarding agent']
```

Usage

```
{'load_ParlAIChatAgentState_data': 'load stored ParlAI chat agent state data from a JSON file into the agent object', 'get_parsed_ParlAIChatAgentState_data': 'get parsed ParlAI chat data including agent name, messages, and world data from the agent state', 'update_ParlAIChatAgentState_live': 'update the ParlAI chat agent state by appending a new live message with a timestamp', 'save_ParlAIChatAgentState': 'save all ParlAI chat agent messages and metadata to a JSON state file on disk', 'get_ParlAIChatAgentState_task_times': 'get the task start and end timestamps from the first and last messages in the agent state'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/parlai_chat/parlai_chat_blueprint.py

Prompts

```
['load stored ParlAI chat agent state data from a JSON file into the agent object', 'get parsed ParlAI chat data including agent name, messages, and world data from the agent state', 'update the ParlAI chat agent state by appending a new live message with a timestamp', 'save all ParlAI chat agent messages and metadata to a JSON state file on disk', 'get the task start and end timestamps from the first and last messages in the agent state', 'create a ParlAIChatBlueprintArgs dataclass to configure world file, task description, and conversation count for a ParlAI chat task', 'create a SharedParlAITaskState dataclass to hold frontend task options, world options, and the world module for shared state', 'review the ParlAIChatBlueprint constructor that loads context from CSV or JSONL files and dynamically imports the world module', 'test the ParlAIChatBlueprint assert_task_args method to validate world file existence, conversation count, and optional source paths', 'refactor the ParlAIChatBlueprint get_frontend_args method to customize task description, preview HTML, frame height, and mobile blocking options', 'rebuild the ParlAIChatTaskBuilder frontend by running npm install and webpack dev build', 'build a custom bundle from a source directory with main.js, style.css, and components', 'build the ParlAI frontend and copy bundle.js, index.html, and static files into a server directory', 'review the ParlAIChatTaskBuilder class and its frontend build methods for the Mephisto blueprint', 'refactor the ParlAIChatTaskBuilder rebuild_core method to use a different build tool instead of webpack', 'run onboarding for an OnboardingAgent using a ParlAI onboarding world and wait for submit', 'run a ParlAI task world assignment with multiple agents until the episode is done', 'run a single agent unit in a ParlAI world and collect world data on completion', 'create a MephistoAgentWrapper to use a Mephisto agent as a ParlAI agent in a world', 'cleanup and shutdown the onboarding world for a specific onboarding agent']
```

Usage

```
{'create_ParlAIChatBlueprintArgs': 'create a ParlAIChatBlueprintArgs dataclass to configure world file, task description, and conversation count for a ParlAI chat task', 'create_SharedParlAITaskState': 'create a SharedParlAITaskState dataclass to hold frontend task options, world options, and the world module for shared state', 'review_ParlAIChatBlueprint_init': 'review the ParlAIChatBlueprint constructor that loads context from CSV or JSONL files and dynamically imports the world module', 'test_assert_task_args': 'test the ParlAIChatBlueprint assert_task_args method to validate world file existence, conversation count, and optional source paths', 'refactor_get_frontend_args': 'refactor the ParlAIChatBlueprint get_frontend_args method to customize task description, preview HTML, frame height, and mobile blocking options'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/parlai_chat/parlai_chat_task_builder.py

Prompts

```
['load stored ParlAI chat agent state data from a JSON file into the agent object', 'get parsed ParlAI chat data including agent name, messages, and world data from the agent state', 'update the ParlAI chat agent state by appending a new live message with a timestamp', 'save all ParlAI chat agent messages and metadata to a JSON state file on disk', 'get the task start and end timestamps from the first and last messages in the agent state', 'create a ParlAIChatBlueprintArgs dataclass to configure world file, task description, and conversation count for a ParlAI chat task', 'create a SharedParlAITaskState dataclass to hold frontend task options, world options, and the world module for shared state', 'review the ParlAIChatBlueprint constructor that loads context from CSV or JSONL files and dynamically imports the world module', 'test the ParlAIChatBlueprint assert_task_args method to validate world file existence, conversation count, and optional source paths', 'refactor the ParlAIChatBlueprint get_frontend_args method to customize task description, preview HTML, frame height, and mobile blocking options', 'rebuild the ParlAIChatTaskBuilder frontend by running npm install and webpack dev build', 'build a custom bundle from a source directory with main.js, style.css, and components', 'build the ParlAI frontend and copy bundle.js, index.html, and static files into a server directory', 'review the ParlAIChatTaskBuilder class and its frontend build methods for the Mephisto blueprint', 'refactor the ParlAIChatTaskBuilder rebuild_core method to use a different build tool instead of webpack', 'run onboarding for an OnboardingAgent using a ParlAI onboarding world and wait for submit', 'run a ParlAI task world assignment with multiple agents until the episode is done', 'run a single agent unit in a ParlAI world and collect world data on completion', 'create a MephistoAgentWrapper to use a Mephisto agent as a ParlAI agent in a world', 'cleanup and shutdown the onboarding world for a specific onboarding agent']
```

Usage

```
{'rebuild_ParlAIChatTaskBuilder_frontend': 'rebuild the ParlAIChatTaskBuilder frontend by running npm install and webpack dev build', 'build_ParlAIChatTaskBuilder_custom_bundle': 'build a custom bundle from a source directory with main.js, style.css, and components', 'build_ParlAIChatTaskBuilder_in_dir': 'build the ParlAI frontend and copy bundle.js, index.html, and static files into a server directory', 'review_ParlAIChatTaskBuilder_class': 'review the ParlAIChatTaskBuilder class and its frontend build methods for the Mephisto blueprint', 'refactor_ParlAIChatTaskBuilder_rebuild_core': 'refactor the ParlAIChatTaskBuilder rebuild_core method to use a different build tool instead of webpack'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/parlai_chat/parlai_chat_task_runner.py

Prompts

```
['load stored ParlAI chat agent state data from a JSON file into the agent object', 'get parsed ParlAI chat data including agent name, messages, and world data from the agent state', 'update the ParlAI chat agent state by appending a new live message with a timestamp', 'save all ParlAI chat agent messages and metadata to a JSON state file on disk', 'get the task start and end timestamps from the first and last messages in the agent state', 'create a ParlAIChatBlueprintArgs dataclass to configure world file, task description, and conversation count for a ParlAI chat task', 'create a SharedParlAITaskState dataclass to hold frontend task options, world options, and the world module for shared state', 'review the ParlAIChatBlueprint constructor that loads context from CSV or JSONL files and dynamically imports the world module', 'test the ParlAIChatBlueprint assert_task_args method to validate world file existence, conversation count, and optional source paths', 'refactor the ParlAIChatBlueprint get_frontend_args method to customize task description, preview HTML, frame height, and mobile blocking options', 'rebuild the ParlAIChatTaskBuilder frontend by running npm install and webpack dev build', 'build a custom bundle from a source directory with main.js, style.css, and components', 'build the ParlAI frontend and copy bundle.js, index.html, and static files into a server directory', 'review the ParlAIChatTaskBuilder class and its frontend build methods for the Mephisto blueprint', 'refactor the ParlAIChatTaskBuilder rebuild_core method to use a different build tool instead of webpack', 'run onboarding for an OnboardingAgent using a ParlAI onboarding world and wait for submit', 'run a ParlAI task world assignment with multiple agents until the episode is done', 'run a single agent unit in a ParlAI world and collect world data on completion', 'create a MephistoAgentWrapper to use a Mephisto agent as a ParlAI agent in a world', 'cleanup and shutdown the onboarding world for a specific onboarding agent']
```

Usage

```
{'run_onboarding_ParlAIChatTaskRunner': 'run onboarding for an OnboardingAgent using a ParlAI onboarding world and wait for submit', 'run_assignment_ParlAIChatTaskRunner': 'run a ParlAI task world assignment with multiple agents until the episode is done', 'run_unit_ParlAIChatTaskRunner': 'run a single agent unit in a ParlAI world and collect world data on completion', 'create_MephistoAgentWrapper': 'create a MephistoAgentWrapper to use a Mephisto agent as a ParlAI agent in a world', 'cleanup_onboarding_ParlAIChatTaskRunner': 'cleanup and shutdown the onboarding world for a specific onboarding agent'}
```

