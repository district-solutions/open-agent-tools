# Agent Python Tools

- repo: facebookresearch/geort
- repo_uri: https://github.com/facebookresearch/geort

## File: facebookresearch_geort/geort/utils/config_utils.py

Prompts

```
['create a python module that saves a dictionary to a JSON file with 4-space indentation', 'create a function that loads data from a JSON file and returns a Python dictionary', 'build a python module that loads a named configuration JSON file from the geort config directory', 'create a function that parses fingertip link keypoint info from a config into links, offsets, joints, and human IDs', 'build a python module that extracts lower and upper joint limit arrays from a config dictionary', 'check if two sets of actors are in contact in a physics scene above an impulse threshold', "get the indices of named joints from a SAPIEN articulation's active joints list", 'get active joint objects from an articulation filtered by a list of joint names', 'look up a SAPIEN entity by name from a list and optionally enforce uniqueness', 'review the hand utility functions for contact checking, joint lookup, and entity retrieval in SAPIEN', 'get the resolved root directory path of the GeoRT package', 'resolve a relative path against the GeoRT package root directory', 'get the resolved path to the GeoRT data directory', 'get the resolved path to the GeoRT checkpoint directory', 'get the resolved output path for a named human data subset']
```

Usage

```
{'save_json': 'create a python module that saves a dictionary to a JSON file with 4-space indentation', 'load_json': 'create a function that loads data from a JSON file and returns a Python dictionary', 'get_config': 'build a python module that loads a named configuration JSON file from the geort config directory', 'parse_config_keypoint_info': 'create a function that parses fingertip link keypoint info from a config into links, offsets, joints, and human IDs', 'parse_config_joint_limit': 'build a python module that extracts lower and upper joint limit arrays from a config dictionary'}
```

## File: facebookresearch_geort/geort/utils/hand_utils.py

Prompts

```
['create a python module that saves a dictionary to a JSON file with 4-space indentation', 'create a function that loads data from a JSON file and returns a Python dictionary', 'build a python module that loads a named configuration JSON file from the geort config directory', 'create a function that parses fingertip link keypoint info from a config into links, offsets, joints, and human IDs', 'build a python module that extracts lower and upper joint limit arrays from a config dictionary', 'check if two sets of actors are in contact in a physics scene above an impulse threshold', "get the indices of named joints from a SAPIEN articulation's active joints list", 'get active joint objects from an articulation filtered by a list of joint names', 'look up a SAPIEN entity by name from a list and optionally enforce uniqueness', 'review the hand utility functions for contact checking, joint lookup, and entity retrieval in SAPIEN', 'get the resolved root directory path of the GeoRT package', 'resolve a relative path against the GeoRT package root directory', 'get the resolved path to the GeoRT data directory', 'get the resolved path to the GeoRT checkpoint directory', 'get the resolved output path for a named human data subset']
```

Usage

```
{'check_contact_between_actors': 'check if two sets of actors are in contact in a physics scene above an impulse threshold', 'get_active_joint_indices': "get the indices of named joints from a SAPIEN articulation's active joints list", 'get_active_joints_by_name': 'get active joint objects from an articulation filtered by a list of joint names', 'get_entity_by_name_lookup': 'look up a SAPIEN entity by name from a list and optionally enforce uniqueness', 'review_hand_utils_helpers': 'review the hand utility functions for contact checking, joint lookup, and entity retrieval in SAPIEN'}
```

## File: facebookresearch_geort/geort/utils/path.py

Prompts

```
['create a python module that saves a dictionary to a JSON file with 4-space indentation', 'create a function that loads data from a JSON file and returns a Python dictionary', 'build a python module that loads a named configuration JSON file from the geort config directory', 'create a function that parses fingertip link keypoint info from a config into links, offsets, joints, and human IDs', 'build a python module that extracts lower and upper joint limit arrays from a config dictionary', 'check if two sets of actors are in contact in a physics scene above an impulse threshold', "get the indices of named joints from a SAPIEN articulation's active joints list", 'get active joint objects from an articulation filtered by a list of joint names', 'look up a SAPIEN entity by name from a list and optionally enforce uniqueness', 'review the hand utility functions for contact checking, joint lookup, and entity retrieval in SAPIEN', 'get the resolved root directory path of the GeoRT package', 'resolve a relative path against the GeoRT package root directory', 'get the resolved path to the GeoRT data directory', 'get the resolved path to the GeoRT checkpoint directory', 'get the resolved output path for a named human data subset']
```

Usage

```
{'get_package_root': 'get the resolved root directory path of the GeoRT package', 'to_package_root': 'resolve a relative path against the GeoRT package root directory', 'get_data_root': 'get the resolved path to the GeoRT data directory', 'get_checkpoint_root': 'get the resolved path to the GeoRT checkpoint directory', 'get_human_data_output_path': 'get the resolved output path for a named human data subset'}
```

