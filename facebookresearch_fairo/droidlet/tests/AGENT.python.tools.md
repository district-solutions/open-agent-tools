# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/tests/test_base_utils.py

Prompts

```
["test the number_from_span function that converts text like 'eighteen' or '20' to a float value", 'test the hash_user and check_username functions for salting and verifying a username with SHA-256', 'test the get_bounds function that computes min and max across x, y, z from a list of 3D locations', 'test the group_by function that groups items into a dictionary by a key function like even_num_detector', 'test the euclid_dist and manhat_dist functions that compute Euclidean and Manhattan distance between two 3D points', 'create a BackgroundTask with an init function, init args, and a process function for parallel work', 'start a BackgroundTask instance to begin processing tasks in a separate background thread', 'put items into a running BackgroundTask queue to be processed by the background process function', 'get results from a BackgroundTask with a timeout value to retrieve processed output', 'test the BackgroundTask class by creating a Foo instance and calling forward to verify parallel processing']
```

Usage

```
{'test_number_from_span': "test the number_from_span function that converts text like 'eighteen' or '20' to a float value", 'test_hash_username': 'test the hash_user and check_username functions for salting and verifying a username with SHA-256', 'test_get_bounds': 'test the get_bounds function that computes min and max across x, y, z from a list of 3D locations', 'test_group_by': 'test the group_by function that groups items into a dictionary by a key function like even_num_detector', 'test_distance_computation': 'test the euclid_dist and manhat_dist functions that compute Euclidean and Manhattan distance between two 3D points'}
```

## File: facebookresearch_fairo/droidlet/tests/test_parallel.py

Prompts

```
["test the number_from_span function that converts text like 'eighteen' or '20' to a float value", 'test the hash_user and check_username functions for salting and verifying a username with SHA-256', 'test the get_bounds function that computes min and max across x, y, z from a list of 3D locations', 'test the group_by function that groups items into a dictionary by a key function like even_num_detector', 'test the euclid_dist and manhat_dist functions that compute Euclidean and Manhattan distance between two 3D points', 'create a BackgroundTask with an init function, init args, and a process function for parallel work', 'start a BackgroundTask instance to begin processing tasks in a separate background thread', 'put items into a running BackgroundTask queue to be processed by the background process function', 'get results from a BackgroundTask with a timeout value to retrieve processed output', 'test the BackgroundTask class by creating a Foo instance and calling forward to verify parallel processing']
```

Usage

```
{'create_background_task': 'create a BackgroundTask with an init function, init args, and a process function for parallel work', 'start_background_task': 'start a BackgroundTask instance to begin processing tasks in a separate background thread', 'put_items_to_background_task': 'put items into a running BackgroundTask queue to be processed by the background process function', 'get_results_from_background_task': 'get results from a BackgroundTask with a timeout value to retrieve processed output', 'test_background_task': 'test the BackgroundTask class by creating a Foo instance and calling forward to verify parallel processing'}
```

