# Agent Python Tools

- repo: google-deepmind/dmcontrol
- repo_uri: https://github.com/google-deepmind/dm_control

## File: google-deepmind_dmcontrol/dm_control/locomotion/examples/basic_cmu_2019.py

Prompts

```
['build a CMU humanoid environment that runs down a corridor obstructed by randomized walls', 'build a CMU humanoid environment that runs down a corridor with randomized gaps and platforms', 'build a CMU humanoid environment that navigates to a target on a standard floor arena', 'build a CMU humanoid environment that finds all target items in a randomly generated maze', 'build a CMU humanoid environment that collects correct targets while avoiding wrong ones in a fixed maze', 'build a dm_control environment where a rodent walker must climb out of a bowl-shaped terrain', 'build a dm_control environment where a rodent runs down a corridor with randomized gaps and platforms', 'build a dm_control environment where a rodent must find all target spheres in a random maze', 'build a dm_control environment where a rodent taps an orb, waits, and taps it again', 'summarize the four rodent task environment factory functions and their walker, arena, and task configurations', 'run the CMU humanoid tracking environment with motion capture reference data for RL training', 'create a MultiClipMocapTracking task that rewards an agent for tracking motion capture reference poses', 'build a composer Environment wrapping a CMU humanoid walker on a floor arena with a 30-second time limit', 'get the file path for CMU motion capture dataset version 2020 using cmu_mocap_data', 'review the cmu_humanoid_tracking function to understand how it configures the walker, arena, and mocap tracking task', 'test the cmu_humanoid_run_walls environment constructor runs and returns valid observations and rewards', 'test the cmu_humanoid_run_gaps environment constructor runs and returns valid observations and rewards', 'test the rodent_escape_bowl environment constructor runs and returns valid observations and rewards', 'test the rodent_maze_forage environment constructor runs and returns valid observations and rewards', 'test the rodent_two_touch environment constructor runs and returns valid observations and rewards']
```

Usage

```
{'build_cmu_humanoid_run_walls': 'build a CMU humanoid environment that runs down a corridor obstructed by randomized walls', 'build_cmu_humanoid_run_gaps': 'build a CMU humanoid environment that runs down a corridor with randomized gaps and platforms', 'build_cmu_humanoid_go_to_target': 'build a CMU humanoid environment that navigates to a target on a standard floor arena', 'build_cmu_humanoid_maze_forage': 'build a CMU humanoid environment that finds all target items in a randomly generated maze', 'build_cmu_humanoid_heterogeneous_forage': 'build a CMU humanoid environment that collects correct targets while avoiding wrong ones in a fixed maze'}
```

## File: google-deepmind_dmcontrol/dm_control/locomotion/examples/basic_rodent_2020.py

Prompts

```
['build a CMU humanoid environment that runs down a corridor obstructed by randomized walls', 'build a CMU humanoid environment that runs down a corridor with randomized gaps and platforms', 'build a CMU humanoid environment that navigates to a target on a standard floor arena', 'build a CMU humanoid environment that finds all target items in a randomly generated maze', 'build a CMU humanoid environment that collects correct targets while avoiding wrong ones in a fixed maze', 'build a dm_control environment where a rodent walker must climb out of a bowl-shaped terrain', 'build a dm_control environment where a rodent runs down a corridor with randomized gaps and platforms', 'build a dm_control environment where a rodent must find all target spheres in a random maze', 'build a dm_control environment where a rodent taps an orb, waits, and taps it again', 'summarize the four rodent task environment factory functions and their walker, arena, and task configurations', 'run the CMU humanoid tracking environment with motion capture reference data for RL training', 'create a MultiClipMocapTracking task that rewards an agent for tracking motion capture reference poses', 'build a composer Environment wrapping a CMU humanoid walker on a floor arena with a 30-second time limit', 'get the file path for CMU motion capture dataset version 2020 using cmu_mocap_data', 'review the cmu_humanoid_tracking function to understand how it configures the walker, arena, and mocap tracking task', 'test the cmu_humanoid_run_walls environment constructor runs and returns valid observations and rewards', 'test the cmu_humanoid_run_gaps environment constructor runs and returns valid observations and rewards', 'test the rodent_escape_bowl environment constructor runs and returns valid observations and rewards', 'test the rodent_maze_forage environment constructor runs and returns valid observations and rewards', 'test the rodent_two_touch environment constructor runs and returns valid observations and rewards']
```

Usage

```
{'build_rodent_escape_bowl': 'build a dm_control environment where a rodent walker must climb out of a bowl-shaped terrain', 'build_rodent_run_gaps': 'build a dm_control environment where a rodent runs down a corridor with randomized gaps and platforms', 'build_rodent_maze_forage': 'build a dm_control environment where a rodent must find all target spheres in a random maze', 'build_rodent_two_touch': 'build a dm_control environment where a rodent taps an orb, waits, and taps it again', 'summarize_rodent_environment_functions': 'summarize the four rodent task environment factory functions and their walker, arena, and task configurations'}
```

## File: google-deepmind_dmcontrol/dm_control/locomotion/examples/cmu_2020_tracking.py

Prompts

```
['build a CMU humanoid environment that runs down a corridor obstructed by randomized walls', 'build a CMU humanoid environment that runs down a corridor with randomized gaps and platforms', 'build a CMU humanoid environment that navigates to a target on a standard floor arena', 'build a CMU humanoid environment that finds all target items in a randomly generated maze', 'build a CMU humanoid environment that collects correct targets while avoiding wrong ones in a fixed maze', 'build a dm_control environment where a rodent walker must climb out of a bowl-shaped terrain', 'build a dm_control environment where a rodent runs down a corridor with randomized gaps and platforms', 'build a dm_control environment where a rodent must find all target spheres in a random maze', 'build a dm_control environment where a rodent taps an orb, waits, and taps it again', 'summarize the four rodent task environment factory functions and their walker, arena, and task configurations', 'run the CMU humanoid tracking environment with motion capture reference data for RL training', 'create a MultiClipMocapTracking task that rewards an agent for tracking motion capture reference poses', 'build a composer Environment wrapping a CMU humanoid walker on a floor arena with a 30-second time limit', 'get the file path for CMU motion capture dataset version 2020 using cmu_mocap_data', 'review the cmu_humanoid_tracking function to understand how it configures the walker, arena, and mocap tracking task', 'test the cmu_humanoid_run_walls environment constructor runs and returns valid observations and rewards', 'test the cmu_humanoid_run_gaps environment constructor runs and returns valid observations and rewards', 'test the rodent_escape_bowl environment constructor runs and returns valid observations and rewards', 'test the rodent_maze_forage environment constructor runs and returns valid observations and rewards', 'test the rodent_two_touch environment constructor runs and returns valid observations and rewards']
```

Usage

```
{'run_cmu_humanoid_tracking': 'run the CMU humanoid tracking environment with motion capture reference data for RL training', 'create_multi_clip_mocap_tracking_task': 'create a MultiClipMocapTracking task that rewards an agent for tracking motion capture reference poses', 'build_cmu_humanoid_environment': 'build a composer Environment wrapping a CMU humanoid walker on a floor arena with a 30-second time limit', 'get_cmu_mocap_data_path': 'get the file path for CMU motion capture dataset version 2020 using cmu_mocap_data', 'review_cmu_humanoid_tracking': 'review the cmu_humanoid_tracking function to understand how it configures the walker, arena, and mocap tracking task'}
```

## File: google-deepmind_dmcontrol/dm_control/locomotion/examples/examples_test.py

Prompts

```
['build a CMU humanoid environment that runs down a corridor obstructed by randomized walls', 'build a CMU humanoid environment that runs down a corridor with randomized gaps and platforms', 'build a CMU humanoid environment that navigates to a target on a standard floor arena', 'build a CMU humanoid environment that finds all target items in a randomly generated maze', 'build a CMU humanoid environment that collects correct targets while avoiding wrong ones in a fixed maze', 'build a dm_control environment where a rodent walker must climb out of a bowl-shaped terrain', 'build a dm_control environment where a rodent runs down a corridor with randomized gaps and platforms', 'build a dm_control environment where a rodent must find all target spheres in a random maze', 'build a dm_control environment where a rodent taps an orb, waits, and taps it again', 'summarize the four rodent task environment factory functions and their walker, arena, and task configurations', 'run the CMU humanoid tracking environment with motion capture reference data for RL training', 'create a MultiClipMocapTracking task that rewards an agent for tracking motion capture reference poses', 'build a composer Environment wrapping a CMU humanoid walker on a floor arena with a 30-second time limit', 'get the file path for CMU motion capture dataset version 2020 using cmu_mocap_data', 'review the cmu_humanoid_tracking function to understand how it configures the walker, arena, and mocap tracking task', 'test the cmu_humanoid_run_walls environment constructor runs and returns valid observations and rewards', 'test the cmu_humanoid_run_gaps environment constructor runs and returns valid observations and rewards', 'test the rodent_escape_bowl environment constructor runs and returns valid observations and rewards', 'test the rodent_maze_forage environment constructor runs and returns valid observations and rewards', 'test the rodent_two_touch environment constructor runs and returns valid observations and rewards']
```

Usage

```
{'test_cmu_humanoid_run_walls': 'test the cmu_humanoid_run_walls environment constructor runs and returns valid observations and rewards', 'test_cmu_humanoid_run_gaps': 'test the cmu_humanoid_run_gaps environment constructor runs and returns valid observations and rewards', 'test_rodent_escape_bowl': 'test the rodent_escape_bowl environment constructor runs and returns valid observations and rewards', 'test_rodent_maze_forage': 'test the rodent_maze_forage environment constructor runs and returns valid observations and rewards', 'test_rodent_two_touch': 'test the rodent_two_touch environment constructor runs and returns valid observations and rewards'}
```

