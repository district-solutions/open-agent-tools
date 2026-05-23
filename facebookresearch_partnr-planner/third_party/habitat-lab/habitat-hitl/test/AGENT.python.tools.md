# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-hitl/test/test_example_apps.py

Prompts

```
['run a Python script as __main__ by setting sys.argv and calling runpy.run_path with the target file', 'spawn a subprocess to run a Python script and assert it exits with code 0', 'test the HITL basic_viewer example app using a smoke_test experiment config in a subprocess', 'test the HITL minimal example app using a smoke_test experiment config in a subprocess', 'test the HITL pick_throw_vr example app using a smoke_test experiment config in a subprocess', 'run the HITL main loop with a custom AppState subclass that steps the Habitat environment', 'test the hitl_main function using Hydra config composition with the smoke_test experiment override', 'create a subclass of AppState that implements sim_update to step the environment and set camera transforms', 'register Hydra plugins before composing configuration for the HITL simulation environment', 'compose a Hydra configuration with experiment overrides to initialize the HITL test environment', 'create a Users instance with a max user count and optionally activate all users on init', 'activate or deactivate a specific user by index in the Users set', 'create a Mask from a single index using Mask.from_index for bitwise user selection', 'create a Mask that includes all users except specified indices using Mask.all_except_index', 'get a list of active user indices filtered by a Mask using to_index_list']
```

Usage

```
{'run_main_script': 'run a Python script as __main__ by setting sys.argv and calling runpy.run_path with the target file', 'run_main_as_subprocess': 'spawn a subprocess to run a Python script and assert it exits with code 0', 'test_basic_viewer_example': 'test the HITL basic_viewer example app using a smoke_test experiment config in a subprocess', 'test_minimal_example': 'test the HITL minimal example app using a smoke_test experiment config in a subprocess', 'test_pick_throw_vr_example': 'test the HITL pick_throw_vr example app using a smoke_test experiment config in a subprocess'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-hitl/test/test_main.py

Prompts

```
['run a Python script as __main__ by setting sys.argv and calling runpy.run_path with the target file', 'spawn a subprocess to run a Python script and assert it exits with code 0', 'test the HITL basic_viewer example app using a smoke_test experiment config in a subprocess', 'test the HITL minimal example app using a smoke_test experiment config in a subprocess', 'test the HITL pick_throw_vr example app using a smoke_test experiment config in a subprocess', 'run the HITL main loop with a custom AppState subclass that steps the Habitat environment', 'test the hitl_main function using Hydra config composition with the smoke_test experiment override', 'create a subclass of AppState that implements sim_update to step the environment and set camera transforms', 'register Hydra plugins before composing configuration for the HITL simulation environment', 'compose a Hydra configuration with experiment overrides to initialize the HITL test environment', 'create a Users instance with a max user count and optionally activate all users on init', 'activate or deactivate a specific user by index in the Users set', 'create a Mask from a single index using Mask.from_index for bitwise user selection', 'create a Mask that includes all users except specified indices using Mask.all_except_index', 'get a list of active user indices filtered by a Mask using to_index_list']
```

Usage

```
{'run_HITL_test_app': 'run the HITL main loop with a custom AppState subclass that steps the Habitat environment', 'test_hitl_main_function': 'test the hitl_main function using Hydra config composition with the smoke_test experiment override', 'create_AppState_subclass': 'create a subclass of AppState that implements sim_update to step the environment and set camera transforms', 'register_hydra_plugins': 'register Hydra plugins before composing configuration for the HITL simulation environment', 'compose_Hydra_config': 'compose a Hydra configuration with experiment overrides to initialize the HITL test environment'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-hitl/test/test_user_mask.py

Prompts

```
['run a Python script as __main__ by setting sys.argv and calling runpy.run_path with the target file', 'spawn a subprocess to run a Python script and assert it exits with code 0', 'test the HITL basic_viewer example app using a smoke_test experiment config in a subprocess', 'test the HITL minimal example app using a smoke_test experiment config in a subprocess', 'test the HITL pick_throw_vr example app using a smoke_test experiment config in a subprocess', 'run the HITL main loop with a custom AppState subclass that steps the Habitat environment', 'test the hitl_main function using Hydra config composition with the smoke_test experiment override', 'create a subclass of AppState that implements sim_update to step the environment and set camera transforms', 'register Hydra plugins before composing configuration for the HITL simulation environment', 'compose a Hydra configuration with experiment overrides to initialize the HITL test environment', 'create a Users instance with a max user count and optionally activate all users on init', 'activate or deactivate a specific user by index in the Users set', 'create a Mask from a single index using Mask.from_index for bitwise user selection', 'create a Mask that includes all users except specified indices using Mask.all_except_index', 'get a list of active user indices filtered by a Mask using to_index_list']
```

Usage

```
{'create_users_with_max_count': 'create a Users instance with a max user count and optionally activate all users on init', 'activate_deactivate_user': 'activate or deactivate a specific user by index in the Users set', 'create_mask_from_index': 'create a Mask from a single index using Mask.from_index for bitwise user selection', 'create_mask_all_except': 'create a Mask that includes all users except specified indices using Mask.all_except_index', 'get_active_user_indices': 'get a list of active user indices filtered by a Mask using to_index_list'}
```

