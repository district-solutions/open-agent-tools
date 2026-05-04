# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-hitl/test/test_example_apps.py

Prompts

```
['run a Python script by setting sys.argv and executing it via runpy.run_path', 'spawn a subprocess to run a Python script and assert it exits with code 0', 'test the HITL basic viewer example app using the smoke_test experiment config', 'test the HITL minimal example app using the smoke_test experiment config', 'test the HITL pick and throw VR example app using the smoke_test experiment config', 'run the HITL main loop with a Hydra config and AppStateTest factory', 'test the HITL main function using pytest with a smoke test experiment config', 'create an AppStateTest subclass that steps the Habitat environment and sets a fixed overhead camera', 'review the AppStateTest sim_update method that computes actions and sets the 3D viewport camera transform', 'summarize the main function that initializes hitl_main with a config and AppStateTest lambda factory', 'test the Users class with zero max users to verify activate and deactivate are no-ops', 'test the Users class with four users to verify activation, deactivation, and mask-based index list filtering', 'test the Users class with 32 users to verify full mask capacity and all_except_indices filtering', 'test the Users constructor with activate_users=True to verify all users start active', 'test the Mask class bitwise operations including from_index, from_indices, all_except_index, and all_except_indices']
```

Usage

```
{'run_main': 'run a Python script by setting sys.argv and executing it via runpy.run_path', 'run_main_as_subprocess': 'spawn a subprocess to run a Python script and assert it exits with code 0', 'test_hitl_example_basic_viewer': 'test the HITL basic viewer example app using the smoke_test experiment config', 'test_hitl_example_minimal': 'test the HITL minimal example app using the smoke_test experiment config', 'test_hitl_example_pick_throw_vr': 'test the HITL pick and throw VR example app using the smoke_test experiment config'}
```

## File: facebookresearch_habitat-lab/habitat-hitl/test/test_main.py

Prompts

```
['run a Python script by setting sys.argv and executing it via runpy.run_path', 'spawn a subprocess to run a Python script and assert it exits with code 0', 'test the HITL basic viewer example app using the smoke_test experiment config', 'test the HITL minimal example app using the smoke_test experiment config', 'test the HITL pick and throw VR example app using the smoke_test experiment config', 'run the HITL main loop with a Hydra config and AppStateTest factory', 'test the HITL main function using pytest with a smoke test experiment config', 'create an AppStateTest subclass that steps the Habitat environment and sets a fixed overhead camera', 'review the AppStateTest sim_update method that computes actions and sets the 3D viewport camera transform', 'summarize the main function that initializes hitl_main with a config and AppStateTest lambda factory', 'test the Users class with zero max users to verify activate and deactivate are no-ops', 'test the Users class with four users to verify activation, deactivation, and mask-based index list filtering', 'test the Users class with 32 users to verify full mask capacity and all_except_indices filtering', 'test the Users constructor with activate_users=True to verify all users start active', 'test the Mask class bitwise operations including from_index, from_indices, all_except_index, and all_except_indices']
```

Usage

```
{'run_hitl_main': 'run the HITL main loop with a Hydra config and AppStateTest factory', 'test_hitl_main': 'test the HITL main function using pytest with a smoke test experiment config', 'create_APPSTATETEST': 'create an AppStateTest subclass that steps the Habitat environment and sets a fixed overhead camera', 'review_APPSTATETEST_sim_update': 'review the AppStateTest sim_update method that computes actions and sets the 3D viewport camera transform', 'summarize_main': 'summarize the main function that initializes hitl_main with a config and AppStateTest lambda factory'}
```

## File: facebookresearch_habitat-lab/habitat-hitl/test/test_user_mask.py

Prompts

```
['run a Python script by setting sys.argv and executing it via runpy.run_path', 'spawn a subprocess to run a Python script and assert it exits with code 0', 'test the HITL basic viewer example app using the smoke_test experiment config', 'test the HITL minimal example app using the smoke_test experiment config', 'test the HITL pick and throw VR example app using the smoke_test experiment config', 'run the HITL main loop with a Hydra config and AppStateTest factory', 'test the HITL main function using pytest with a smoke test experiment config', 'create an AppStateTest subclass that steps the Habitat environment and sets a fixed overhead camera', 'review the AppStateTest sim_update method that computes actions and sets the 3D viewport camera transform', 'summarize the main function that initializes hitl_main with a config and AppStateTest lambda factory', 'test the Users class with zero max users to verify activate and deactivate are no-ops', 'test the Users class with four users to verify activation, deactivation, and mask-based index list filtering', 'test the Users class with 32 users to verify full mask capacity and all_except_indices filtering', 'test the Users constructor with activate_users=True to verify all users start active', 'test the Mask class bitwise operations including from_index, from_indices, all_except_index, and all_except_indices']
```

Usage

```
{'test_users_class_with_zero_users': 'test the Users class with zero max users to verify activate and deactivate are no-ops', 'test_users_class_with_four_users': 'test the Users class with four users to verify activation, deactivation, and mask-based index list filtering', 'test_users_class_with_max_users': 'test the Users class with 32 users to verify full mask capacity and all_except_indices filtering', 'test_users_activate_users_constructor': 'test the Users constructor with activate_users=True to verify all users start active', 'test_mask_bitwise_operations': 'test the Mask class bitwise operations including from_index, from_indices, all_except_index, and all_except_indices'}
```

