# Agent Python Tools

- repo: google-deepmind/concordia
- repo_uri: https://github.com/google-deepmind/concordia

## File: google-deepmind_concordia/examples/social_media/run.py

Prompts

```
['run a concordia social media simulation with a specified scenario number and language model', 'set up a language model and sentence transformer embedder for concordia simulations', 'run a specific concordia scenario by its number using a model and embedder', 'save simulation results to a timestamped JSON file in the output directory', 'list all available concordia social media scenarios with their names and descriptions', 'create a debug scenario config with four robot-alchemy enthusiasts on The Robotic Athanor forum', 'run the robot-alchemy forum simulation with a language model and embedder for eight steps', 'review the SCENARIO_INFO dict containing the scenario number, name, description, create, and run entries', 'summarize the create_debug_scenario function that builds entity configs and game masters for the alchemy forum', 'refactor the run_debug_simulation function to customize the max_steps parameter or callback behavior', 'create a simulation config for a robot alchemy forum scenario where agents generate images with every post', 'run the robot alchemy forum simulation with an image model so agents post memes alongside replies', 'configure entity prefab instances with image mode set to choice for image generation on each post', 'set player specific memories for forum users including Silas Petra Diego and Thaddeus with alchemical beliefs', 'run the robot alchemy simulation with a step callback to receive real time step updates', 'run a social media simulation scenario with a config, model, and embedder using the asynchronous engine', 'create a simulation config from a premise string and list of instance configs with optional extra prefabs', 'get a dictionary of entity and game master prefab classes for social media simulations', 'run a scenario with step callbacks and entity info callbacks to capture checkpoint history during execution', 'run a scenario that saves config, dynamic, and forum HTML visualizations plus a structured JSON log to an output directory']
```

Usage

```
{'run_social_media_simulation': 'run a concordia social media simulation with a specified scenario number and language model', 'setup_model_with_embedder': 'set up a language model and sentence transformer embedder for concordia simulations', 'run_scenario_by_number': 'run a specific concordia scenario by its number using a model and embedder', 'save_results_to_json': 'save simulation results to a timestamped JSON file in the output directory', 'list_available_scenarios': 'list all available concordia social media scenarios with their names and descriptions'}
```

## File: google-deepmind_concordia/examples/social_media/scenario_00_robo_alchemy.py

Prompts

```
['run a concordia social media simulation with a specified scenario number and language model', 'set up a language model and sentence transformer embedder for concordia simulations', 'run a specific concordia scenario by its number using a model and embedder', 'save simulation results to a timestamped JSON file in the output directory', 'list all available concordia social media scenarios with their names and descriptions', 'create a debug scenario config with four robot-alchemy enthusiasts on The Robotic Athanor forum', 'run the robot-alchemy forum simulation with a language model and embedder for eight steps', 'review the SCENARIO_INFO dict containing the scenario number, name, description, create, and run entries', 'summarize the create_debug_scenario function that builds entity configs and game masters for the alchemy forum', 'refactor the run_debug_simulation function to customize the max_steps parameter or callback behavior', 'create a simulation config for a robot alchemy forum scenario where agents generate images with every post', 'run the robot alchemy forum simulation with an image model so agents post memes alongside replies', 'configure entity prefab instances with image mode set to choice for image generation on each post', 'set player specific memories for forum users including Silas Petra Diego and Thaddeus with alchemical beliefs', 'run the robot alchemy simulation with a step callback to receive real time step updates', 'run a social media simulation scenario with a config, model, and embedder using the asynchronous engine', 'create a simulation config from a premise string and list of instance configs with optional extra prefabs', 'get a dictionary of entity and game master prefab classes for social media simulations', 'run a scenario with step callbacks and entity info callbacks to capture checkpoint history during execution', 'run a scenario that saves config, dynamic, and forum HTML visualizations plus a structured JSON log to an output directory']
```

Usage

```
{'create_debug_scenario': 'create a debug scenario config with four robot-alchemy enthusiasts on The Robotic Athanor forum', 'run_debug_simulation': 'run the robot-alchemy forum simulation with a language model and embedder for eight steps', 'review_SCENARIO_INFO': 'review the SCENARIO_INFO dict containing the scenario number, name, description, create, and run entries', 'summarize_create_debug_scenario': 'summarize the create_debug_scenario function that builds entity configs and game masters for the alchemy forum', 'refactor_run_debug_simulation': 'refactor the run_debug_simulation function to customize the max_steps parameter or callback behavior'}
```

## File: google-deepmind_concordia/examples/social_media/scenario_01_robo_alchemy_images.py

Prompts

```
['run a concordia social media simulation with a specified scenario number and language model', 'set up a language model and sentence transformer embedder for concordia simulations', 'run a specific concordia scenario by its number using a model and embedder', 'save simulation results to a timestamped JSON file in the output directory', 'list all available concordia social media scenarios with their names and descriptions', 'create a debug scenario config with four robot-alchemy enthusiasts on The Robotic Athanor forum', 'run the robot-alchemy forum simulation with a language model and embedder for eight steps', 'review the SCENARIO_INFO dict containing the scenario number, name, description, create, and run entries', 'summarize the create_debug_scenario function that builds entity configs and game masters for the alchemy forum', 'refactor the run_debug_simulation function to customize the max_steps parameter or callback behavior', 'create a simulation config for a robot alchemy forum scenario where agents generate images with every post', 'run the robot alchemy forum simulation with an image model so agents post memes alongside replies', 'configure entity prefab instances with image mode set to choice for image generation on each post', 'set player specific memories for forum users including Silas Petra Diego and Thaddeus with alchemical beliefs', 'run the robot alchemy simulation with a step callback to receive real time step updates', 'run a social media simulation scenario with a config, model, and embedder using the asynchronous engine', 'create a simulation config from a premise string and list of instance configs with optional extra prefabs', 'get a dictionary of entity and game master prefab classes for social media simulations', 'run a scenario with step callbacks and entity info callbacks to capture checkpoint history during execution', 'run a scenario that saves config, dynamic, and forum HTML visualizations plus a structured JSON log to an output directory']
```

Usage

```
{'create_scenario_with_images': 'create a simulation config for a robot alchemy forum scenario where agents generate images with every post', 'run_simulation_with_images': 'run the robot alchemy forum simulation with an image model so agents post memes alongside replies', 'configure_entity_prefabs_with_image_mode': 'configure entity prefab instances with image mode set to choice for image generation on each post', 'set_player_specific_memories': 'set player specific memories for forum users including Silas Petra Diego and Thaddeus with alchemical beliefs', 'run_simulation_with_step_callback': 'run the robot alchemy simulation with a step callback to receive real time step updates'}
```

## File: google-deepmind_concordia/examples/social_media/shared.py

Prompts

```
['run a concordia social media simulation with a specified scenario number and language model', 'set up a language model and sentence transformer embedder for concordia simulations', 'run a specific concordia scenario by its number using a model and embedder', 'save simulation results to a timestamped JSON file in the output directory', 'list all available concordia social media scenarios with their names and descriptions', 'create a debug scenario config with four robot-alchemy enthusiasts on The Robotic Athanor forum', 'run the robot-alchemy forum simulation with a language model and embedder for eight steps', 'review the SCENARIO_INFO dict containing the scenario number, name, description, create, and run entries', 'summarize the create_debug_scenario function that builds entity configs and game masters for the alchemy forum', 'refactor the run_debug_simulation function to customize the max_steps parameter or callback behavior', 'create a simulation config for a robot alchemy forum scenario where agents generate images with every post', 'run the robot alchemy forum simulation with an image model so agents post memes alongside replies', 'configure entity prefab instances with image mode set to choice for image generation on each post', 'set player specific memories for forum users including Silas Petra Diego and Thaddeus with alchemical beliefs', 'run the robot alchemy simulation with a step callback to receive real time step updates', 'run a social media simulation scenario with a config, model, and embedder using the asynchronous engine', 'create a simulation config from a premise string and list of instance configs with optional extra prefabs', 'get a dictionary of entity and game master prefab classes for social media simulations', 'run a scenario with step callbacks and entity info callbacks to capture checkpoint history during execution', 'run a scenario that saves config, dynamic, and forum HTML visualizations plus a structured JSON log to an output directory']
```

Usage

```
{'run_social_media_scenario': 'run a social media simulation scenario with a config, model, and embedder using the asynchronous engine', 'create_simulation_config': 'create a simulation config from a premise string and list of instance configs with optional extra prefabs', 'get_prefabs': 'get a dictionary of entity and game master prefab classes for social media simulations', 'run_scenario_with_callbacks': 'run a scenario with step callbacks and entity info callbacks to capture checkpoint history during execution', 'run_scenario_with_visualization': 'run a scenario that saves config, dynamic, and forum HTML visualizations plus a structured JSON log to an output directory'}
```

