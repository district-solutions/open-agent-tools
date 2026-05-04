# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/trifinger_simulation/trifinger_simulation/gym_wrapper/data_logger.py

Prompts

```
['create an EpisodeData object to log joint and tip positions for a single episode', 'append joint positions, tip positions, and timestamps to an existing EpisodeData object', 'create a DataLogger instance to manage and dump episodic environment data to a pickle file', 'start a new episode in the DataLogger with specified joint and tip goals', 'store all logged episodes from the DataLogger to a pickle file on disk', 'create a FingerSpaces instance with num_fingers, observation keys, sizes, and separate_goals settings', 'get the unscaled observation space Box with lower and upper bounds from observation keys', 'get the unscaled action space Box with joint position bounds in radians for fingers', 'get the scaled observation space Box normalized to bounds of negative one to one', 'get the scaled action space Box normalized to bounds of negative one to one', 'scale a value from its space range to the normalized range of negative one to one', 'unscale a normalized value from negative one to one back to its original space range', 'compute the Euclidean distance between two vectors or numpy arrays using linalg norm', 'sleep until a target datetime is reached with a configurable accuracy interval in seconds', 'review the gym wrapper utility functions for scaling, unscale, distance, and sleep operations']
```

Usage

```
{'create_EpisodeData': 'create an EpisodeData object to log joint and tip positions for a single episode', 'append_EpisodeData': 'append joint positions, tip positions, and timestamps to an existing EpisodeData object', 'create_DataLogger': 'create a DataLogger instance to manage and dump episodic environment data to a pickle file', 'new_episode_DataLogger': 'start a new episode in the DataLogger with specified joint and tip goals', 'store_DataLogger': 'store all logged episodes from the DataLogger to a pickle file on disk'}
```

## File: facebookresearch_eai-vc/third_party/trifinger_simulation/trifinger_simulation/gym_wrapper/finger_spaces.py

Prompts

```
['create an EpisodeData object to log joint and tip positions for a single episode', 'append joint positions, tip positions, and timestamps to an existing EpisodeData object', 'create a DataLogger instance to manage and dump episodic environment data to a pickle file', 'start a new episode in the DataLogger with specified joint and tip goals', 'store all logged episodes from the DataLogger to a pickle file on disk', 'create a FingerSpaces instance with num_fingers, observation keys, sizes, and separate_goals settings', 'get the unscaled observation space Box with lower and upper bounds from observation keys', 'get the unscaled action space Box with joint position bounds in radians for fingers', 'get the scaled observation space Box normalized to bounds of negative one to one', 'get the scaled action space Box normalized to bounds of negative one to one', 'scale a value from its space range to the normalized range of negative one to one', 'unscale a normalized value from negative one to one back to its original space range', 'compute the Euclidean distance between two vectors or numpy arrays using linalg norm', 'sleep until a target datetime is reached with a configurable accuracy interval in seconds', 'review the gym wrapper utility functions for scaling, unscale, distance, and sleep operations']
```

Usage

```
{'create_FingerSpaces': 'create a FingerSpaces instance with num_fingers, observation keys, sizes, and separate_goals settings', 'get_unscaled_observation_space': 'get the unscaled observation space Box with lower and upper bounds from observation keys', 'get_unscaled_action_space': 'get the unscaled action space Box with joint position bounds in radians for fingers', 'get_scaled_observation_space': 'get the scaled observation space Box normalized to bounds of negative one to one', 'get_scaled_action_space': 'get the scaled action space Box normalized to bounds of negative one to one'}
```

## File: facebookresearch_eai-vc/third_party/trifinger_simulation/trifinger_simulation/gym_wrapper/utils.py

Prompts

```
['create an EpisodeData object to log joint and tip positions for a single episode', 'append joint positions, tip positions, and timestamps to an existing EpisodeData object', 'create a DataLogger instance to manage and dump episodic environment data to a pickle file', 'start a new episode in the DataLogger with specified joint and tip goals', 'store all logged episodes from the DataLogger to a pickle file on disk', 'create a FingerSpaces instance with num_fingers, observation keys, sizes, and separate_goals settings', 'get the unscaled observation space Box with lower and upper bounds from observation keys', 'get the unscaled action space Box with joint position bounds in radians for fingers', 'get the scaled observation space Box normalized to bounds of negative one to one', 'get the scaled action space Box normalized to bounds of negative one to one', 'scale a value from its space range to the normalized range of negative one to one', 'unscale a normalized value from negative one to one back to its original space range', 'compute the Euclidean distance between two vectors or numpy arrays using linalg norm', 'sleep until a target datetime is reached with a configurable accuracy interval in seconds', 'review the gym wrapper utility functions for scaling, unscale, distance, and sleep operations']
```

Usage

```
{'scale_value_to_range': 'scale a value from its space range to the normalized range of negative one to one', 'unscale_value_from_range': 'unscale a normalized value from negative one to one back to its original space range', 'compute_euclidean_distance': 'compute the Euclidean distance between two vectors or numpy arrays using linalg norm', 'sleep_until_datetime': 'sleep until a target datetime is reached with a configurable accuracy interval in seconds', 'review_utils_functions': 'review the gym wrapper utility functions for scaling, unscale, distance, and sleep operations'}
```

