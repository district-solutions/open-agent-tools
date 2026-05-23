# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-hitl/habitat_hitl/app_states/app_service.py

Prompts

```
['review the AppService class and its 20 dependency injection properties for the HITL sandbox driver', 'refactor the AppService property getters to add validation or lazy loading for injected dependencies', 'summarize the AppService constructor parameters including config, env, sim, controllers, and UI components', 'test the AppService dependency injection by verifying all 20 properties return their injected values', 'build a wrapper around AppService to provide typed access to env, sim, and agent controllers', 'implement a subclass of AppState to create a custom HITL app with sim_update logic', 'override the sim_update method to update simulation state and populate camera transform each frame', 'override on_environment_reset to reset internal members and record per-episode metrics on new episodes', 'override record_state to log step-level data using the app service step recorder', 'review the AppState abstract base class and its three lifecycle hooks for HITL app development', 'create an AppStateTutorial instance with an app_service to manage tutorial state and GUI agent control', 'build a tutorial scene by calling on_enter with final eye position and lookat position parameters', 'test the sim_update method to verify tutorial progression, camera transform updates, and help text rendering', 'refactor the _sim_update_tutorial method to handle SPACE and Q key inputs for skipping tutorial stages', 'review the _update_help_text method to verify it renders tutorial controls and display text on screen']
```

Usage

```
{'review_AppService_class': 'review the AppService class and its 20 dependency injection properties for the HITL sandbox driver', 'refactor_AppService_properties': 'refactor the AppService property getters to add validation or lazy loading for injected dependencies', 'summarize_AppService_init': 'summarize the AppService constructor parameters including config, env, sim, controllers, and UI components', 'test_AppService_injection': 'test the AppService dependency injection by verifying all 20 properties return their injected values', 'build_AppService_wrapper': 'build a wrapper around AppService to provide typed access to env, sim, and agent controllers'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-hitl/habitat_hitl/app_states/app_state_abc.py

Prompts

```
['review the AppService class and its 20 dependency injection properties for the HITL sandbox driver', 'refactor the AppService property getters to add validation or lazy loading for injected dependencies', 'summarize the AppService constructor parameters including config, env, sim, controllers, and UI components', 'test the AppService dependency injection by verifying all 20 properties return their injected values', 'build a wrapper around AppService to provide typed access to env, sim, and agent controllers', 'implement a subclass of AppState to create a custom HITL app with sim_update logic', 'override the sim_update method to update simulation state and populate camera transform each frame', 'override on_environment_reset to reset internal members and record per-episode metrics on new episodes', 'override record_state to log step-level data using the app service step recorder', 'review the AppState abstract base class and its three lifecycle hooks for HITL app development', 'create an AppStateTutorial instance with an app_service to manage tutorial state and GUI agent control', 'build a tutorial scene by calling on_enter with final eye position and lookat position parameters', 'test the sim_update method to verify tutorial progression, camera transform updates, and help text rendering', 'refactor the _sim_update_tutorial method to handle SPACE and Q key inputs for skipping tutorial stages', 'review the _update_help_text method to verify it renders tutorial controls and display text on screen']
```

Usage

```
{'implement_APPSTATE_SUBCLASS': 'implement a subclass of AppState to create a custom HITL app with sim_update logic', 'override_sim_update': 'override the sim_update method to update simulation state and populate camera transform each frame', 'override_on_environment_reset': 'override on_environment_reset to reset internal members and record per-episode metrics on new episodes', 'override_record_state': 'override record_state to log step-level data using the app service step recorder', 'review_APPSTATE_HOOKS': 'review the AppState abstract base class and its three lifecycle hooks for HITL app development'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-hitl/habitat_hitl/app_states/app_state_tutorial.py

Prompts

```
['review the AppService class and its 20 dependency injection properties for the HITL sandbox driver', 'refactor the AppService property getters to add validation or lazy loading for injected dependencies', 'summarize the AppService constructor parameters including config, env, sim, controllers, and UI components', 'test the AppService dependency injection by verifying all 20 properties return their injected values', 'build a wrapper around AppService to provide typed access to env, sim, and agent controllers', 'implement a subclass of AppState to create a custom HITL app with sim_update logic', 'override the sim_update method to update simulation state and populate camera transform each frame', 'override on_environment_reset to reset internal members and record per-episode metrics on new episodes', 'override record_state to log step-level data using the app service step recorder', 'review the AppState abstract base class and its three lifecycle hooks for HITL app development', 'create an AppStateTutorial instance with an app_service to manage tutorial state and GUI agent control', 'build a tutorial scene by calling on_enter with final eye position and lookat position parameters', 'test the sim_update method to verify tutorial progression, camera transform updates, and help text rendering', 'refactor the _sim_update_tutorial method to handle SPACE and Q key inputs for skipping tutorial stages', 'review the _update_help_text method to verify it renders tutorial controls and display text on screen']
```

Usage

```
{'create_AppStateTutorial': 'create an AppStateTutorial instance with an app_service to manage tutorial state and GUI agent control', 'build_on_enter_tutorial': 'build a tutorial scene by calling on_enter with final eye position and lookat position parameters', 'test_sim_update_tutorial': 'test the sim_update method to verify tutorial progression, camera transform updates, and help text rendering', 'refactor_skip_stage_logic': 'refactor the _sim_update_tutorial method to handle SPACE and Q key inputs for skipping tutorial stages', 'review_update_help_text': 'review the _update_help_text method to verify it renders tutorial controls and display text on screen'}
```

