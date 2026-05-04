# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-hitl/habitat_hitl/app_states/app_service.py

Prompts

```
['review the AppService class to understand its dependency injection pattern and property-based accessors', 'build an AppService instance by injecting config, users, gui_input, env, sim, and controller dependencies', 'access the env property on AppService to retrieve the Habitat environment for simulation control', 'access the sim property on AppService to retrieve the RearrangeSim instance for rearrangement tasks', 'access the gui_agent_controllers or all_agent_controllers property to list available agent controllers', 'create a subclass of AppState to implement a custom HITL app with sim_update logic', 'implement the sim_update hook to update simulation state and populate camera transform each frame', 'implement the on_environment_reset hook to reset internal state when starting a new episode', 'implement the record_state hook to record step data using the app service step recorder', 'review the AppState abstract base class and its three lifecycle hooks for HITL app development', 'build a python module to instantiate AppStateTutorial with an app_service for Habitat HITL tutorial mode', 'create a tutorial scene by calling on_enter with final eye and lookat positions for the agent', 'run the sim_update method to advance tutorial animations and handle space or Q key input', 'review the _sim_update_tutorial method that saves keyframes, updates tutorial, and handles skip stage on key press', 'refactor the _update_help_text method to customize how tutorial controls and display text are drawn on screen']
```

Usage

```
{'review_AppService_class': 'review the AppService class to understand its dependency injection pattern and property-based accessors', 'build_AppService_instance': 'build an AppService instance by injecting config, users, gui_input, env, sim, and controller dependencies', 'access_AppService_env_property': 'access the env property on AppService to retrieve the Habitat environment for simulation control', 'access_AppService_sim_property': 'access the sim property on AppService to retrieve the RearrangeSim instance for rearrangement tasks', 'access_AppService_controllers_property': 'access the gui_agent_controllers or all_agent_controllers property to list available agent controllers'}
```

## File: facebookresearch_habitat-lab/habitat-hitl/habitat_hitl/app_states/app_state_abc.py

Prompts

```
['review the AppService class to understand its dependency injection pattern and property-based accessors', 'build an AppService instance by injecting config, users, gui_input, env, sim, and controller dependencies', 'access the env property on AppService to retrieve the Habitat environment for simulation control', 'access the sim property on AppService to retrieve the RearrangeSim instance for rearrangement tasks', 'access the gui_agent_controllers or all_agent_controllers property to list available agent controllers', 'create a subclass of AppState to implement a custom HITL app with sim_update logic', 'implement the sim_update hook to update simulation state and populate camera transform each frame', 'implement the on_environment_reset hook to reset internal state when starting a new episode', 'implement the record_state hook to record step data using the app service step recorder', 'review the AppState abstract base class and its three lifecycle hooks for HITL app development', 'build a python module to instantiate AppStateTutorial with an app_service for Habitat HITL tutorial mode', 'create a tutorial scene by calling on_enter with final eye and lookat positions for the agent', 'run the sim_update method to advance tutorial animations and handle space or Q key input', 'review the _sim_update_tutorial method that saves keyframes, updates tutorial, and handles skip stage on key press', 'refactor the _update_help_text method to customize how tutorial controls and display text are drawn on screen']
```

Usage

```
{'create_APPState_subclass': 'create a subclass of AppState to implement a custom HITL app with sim_update logic', 'implement_sim_update': 'implement the sim_update hook to update simulation state and populate camera transform each frame', 'implement_on_environment_reset': 'implement the on_environment_reset hook to reset internal state when starting a new episode', 'implement_record_state': 'implement the record_state hook to record step data using the app service step recorder', 'review_APPState_hooks': 'review the AppState abstract base class and its three lifecycle hooks for HITL app development'}
```

## File: facebookresearch_habitat-lab/habitat-hitl/habitat_hitl/app_states/app_state_tutorial.py

Prompts

```
['review the AppService class to understand its dependency injection pattern and property-based accessors', 'build an AppService instance by injecting config, users, gui_input, env, sim, and controller dependencies', 'access the env property on AppService to retrieve the Habitat environment for simulation control', 'access the sim property on AppService to retrieve the RearrangeSim instance for rearrangement tasks', 'access the gui_agent_controllers or all_agent_controllers property to list available agent controllers', 'create a subclass of AppState to implement a custom HITL app with sim_update logic', 'implement the sim_update hook to update simulation state and populate camera transform each frame', 'implement the on_environment_reset hook to reset internal state when starting a new episode', 'implement the record_state hook to record step data using the app service step recorder', 'review the AppState abstract base class and its three lifecycle hooks for HITL app development', 'build a python module to instantiate AppStateTutorial with an app_service for Habitat HITL tutorial mode', 'create a tutorial scene by calling on_enter with final eye and lookat positions for the agent', 'run the sim_update method to advance tutorial animations and handle space or Q key input', 'review the _sim_update_tutorial method that saves keyframes, updates tutorial, and handles skip stage on key press', 'refactor the _update_help_text method to customize how tutorial controls and display text are drawn on screen']
```

Usage

```
{'build_AppStateTutorial': 'build a python module to instantiate AppStateTutorial with an app_service for Habitat HITL tutorial mode', 'create_on_enter_tutorial': 'create a tutorial scene by calling on_enter with final eye and lookat positions for the agent', 'run_sim_update_tutorial': 'run the sim_update method to advance tutorial animations and handle space or Q key input', 'review_sim_update_tutorial_private': 'review the _sim_update_tutorial method that saves keyframes, updates tutorial, and handles skip stage on key press', 'refactor_update_help_text': 'refactor the _update_help_text method to customize how tutorial controls and display text are drawn on screen'}
```

