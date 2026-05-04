# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/utils/obj_vec_dict.py

Prompts

```
['create an ObsVecDict instance and initialize it with an observation dictionary and ordered keys', 'convert an observation dictionary to a flattened observation vector using ObsVecDict', 'convert a flattened observation vector back to an observation dictionary using ObsVecDict', 'add, retrieve, or flush observation vectors in the ObsVecDict timestamped cache', 'squeeze singleton dimensions or expand observation dictionary values to 3D shape', 'convert euler angles to a quaternion using the euler2quat function', 'convert a quaternion to a 3x3 rotation matrix using the quat2mat function', 'convert a 3x3 rotation matrix to a quaternion using the mat2quat function', 'multiply two quaternions together using the mulQuat function', 'convert an axis and angle representation to a quaternion using axis_angle2quat', 'calculate the cosine similarity between two numpy vectors with optional batch dimensions', 'calculate the cosine angle between two batched numpy arrays using einsum', 'test the calculate_cosine function with two numpy arrays of the same shape', 'review the calculate_cosine function for handling zero-norm vectors safely', 'refactor the calculate_cosine function to use numpy broadcasting instead of einsum', 'run a MuJoCo environment policy visualization onscreen for a given number of episodes', 'run a MuJoCo environment policy visualization offscreen and save the rendered video to a file', 'run a random policy exploration on a MuJoCo environment with no policy file provided', 'run a pickled policy file in evaluation mode on a MuJoCo environment', 'review the rand_policy class that samples random actions from the environment action space', 'parse an XML file preserving comments using a version-aware ElementTree parser', 'serialize an ElementTree or Element node to a string with optional pretty formatting', 'merge a donor XML file into a receiver XML file at a specified node', 'merge two XML files and return the combined result as an ElementTree object', 'merge two XML files and return the combined result as a formatted string']
```

Usage

```
{'initialize_ObsVecDict': 'create an ObsVecDict instance and initialize it with an observation dictionary and ordered keys', 'obsdict2obsvec_convert': 'convert an observation dictionary to a flattened observation vector using ObsVecDict', 'obsvec2obsdict_convert': 'convert a flattened observation vector back to an observation dictionary using ObsVecDict', 'cache_obsvec_operations': 'add, retrieve, or flush observation vectors in the ObsVecDict timestamped cache', 'squeeze_and_expand_dims': 'squeeze singleton dimensions or expand observation dictionary values to 3D shape'}
```

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/utils/quatmath.py

Prompts

```
['create an ObsVecDict instance and initialize it with an observation dictionary and ordered keys', 'convert an observation dictionary to a flattened observation vector using ObsVecDict', 'convert a flattened observation vector back to an observation dictionary using ObsVecDict', 'add, retrieve, or flush observation vectors in the ObsVecDict timestamped cache', 'squeeze singleton dimensions or expand observation dictionary values to 3D shape', 'convert euler angles to a quaternion using the euler2quat function', 'convert a quaternion to a 3x3 rotation matrix using the quat2mat function', 'convert a 3x3 rotation matrix to a quaternion using the mat2quat function', 'multiply two quaternions together using the mulQuat function', 'convert an axis and angle representation to a quaternion using axis_angle2quat', 'calculate the cosine similarity between two numpy vectors with optional batch dimensions', 'calculate the cosine angle between two batched numpy arrays using einsum', 'test the calculate_cosine function with two numpy arrays of the same shape', 'review the calculate_cosine function for handling zero-norm vectors safely', 'refactor the calculate_cosine function to use numpy broadcasting instead of einsum', 'run a MuJoCo environment policy visualization onscreen for a given number of episodes', 'run a MuJoCo environment policy visualization offscreen and save the rendered video to a file', 'run a random policy exploration on a MuJoCo environment with no policy file provided', 'run a pickled policy file in evaluation mode on a MuJoCo environment', 'review the rand_policy class that samples random actions from the environment action space', 'parse an XML file preserving comments using a version-aware ElementTree parser', 'serialize an ElementTree or Element node to a string with optional pretty formatting', 'merge a donor XML file into a receiver XML file at a specified node', 'merge two XML files and return the combined result as an ElementTree object', 'merge two XML files and return the combined result as a formatted string']
```

Usage

```
{'convert_euler_to_quaternion': 'convert euler angles to a quaternion using the euler2quat function', 'convert_quaternion_to_rotation_matrix': 'convert a quaternion to a 3x3 rotation matrix using the quat2mat function', 'convert_rotation_matrix_to_quaternion': 'convert a 3x3 rotation matrix to a quaternion using the mat2quat function', 'multiply_two_quaternions': 'multiply two quaternions together using the mulQuat function', 'convert_axis_angle_to_quaternion': 'convert an axis and angle representation to a quaternion using axis_angle2quat'}
```

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/utils/vectormath.py

Prompts

```
['create an ObsVecDict instance and initialize it with an observation dictionary and ordered keys', 'convert an observation dictionary to a flattened observation vector using ObsVecDict', 'convert a flattened observation vector back to an observation dictionary using ObsVecDict', 'add, retrieve, or flush observation vectors in the ObsVecDict timestamped cache', 'squeeze singleton dimensions or expand observation dictionary values to 3D shape', 'convert euler angles to a quaternion using the euler2quat function', 'convert a quaternion to a 3x3 rotation matrix using the quat2mat function', 'convert a 3x3 rotation matrix to a quaternion using the mat2quat function', 'multiply two quaternions together using the mulQuat function', 'convert an axis and angle representation to a quaternion using axis_angle2quat', 'calculate the cosine similarity between two numpy vectors with optional batch dimensions', 'calculate the cosine angle between two batched numpy arrays using einsum', 'test the calculate_cosine function with two numpy arrays of the same shape', 'review the calculate_cosine function for handling zero-norm vectors safely', 'refactor the calculate_cosine function to use numpy broadcasting instead of einsum', 'run a MuJoCo environment policy visualization onscreen for a given number of episodes', 'run a MuJoCo environment policy visualization offscreen and save the rendered video to a file', 'run a random policy exploration on a MuJoCo environment with no policy file provided', 'run a pickled policy file in evaluation mode on a MuJoCo environment', 'review the rand_policy class that samples random actions from the environment action space', 'parse an XML file preserving comments using a version-aware ElementTree parser', 'serialize an ElementTree or Element node to a string with optional pretty formatting', 'merge a donor XML file into a receiver XML file at a specified node', 'merge two XML files and return the combined result as an ElementTree object', 'merge two XML files and return the combined result as a formatted string']
```

Usage

```
{'calculate_cosine_similarity': 'calculate the cosine similarity between two numpy vectors with optional batch dimensions', 'calculate_batched_cosine': 'calculate the cosine angle between two batched numpy arrays using einsum', 'test_calculate_cosine': 'test the calculate_cosine function with two numpy arrays of the same shape', 'review_calculate_cosine': 'review the calculate_cosine function for handling zero-norm vectors safely', 'refactor_calculate_cosine': 'refactor the calculate_cosine function to use numpy broadcasting instead of einsum'}
```

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/utils/visualize_env.py

Prompts

```
['create an ObsVecDict instance and initialize it with an observation dictionary and ordered keys', 'convert an observation dictionary to a flattened observation vector using ObsVecDict', 'convert a flattened observation vector back to an observation dictionary using ObsVecDict', 'add, retrieve, or flush observation vectors in the ObsVecDict timestamped cache', 'squeeze singleton dimensions or expand observation dictionary values to 3D shape', 'convert euler angles to a quaternion using the euler2quat function', 'convert a quaternion to a 3x3 rotation matrix using the quat2mat function', 'convert a 3x3 rotation matrix to a quaternion using the mat2quat function', 'multiply two quaternions together using the mulQuat function', 'convert an axis and angle representation to a quaternion using axis_angle2quat', 'calculate the cosine similarity between two numpy vectors with optional batch dimensions', 'calculate the cosine angle between two batched numpy arrays using einsum', 'test the calculate_cosine function with two numpy arrays of the same shape', 'review the calculate_cosine function for handling zero-norm vectors safely', 'refactor the calculate_cosine function to use numpy broadcasting instead of einsum', 'run a MuJoCo environment policy visualization onscreen for a given number of episodes', 'run a MuJoCo environment policy visualization offscreen and save the rendered video to a file', 'run a random policy exploration on a MuJoCo environment with no policy file provided', 'run a pickled policy file in evaluation mode on a MuJoCo environment', 'review the rand_policy class that samples random actions from the environment action space', 'parse an XML file preserving comments using a version-aware ElementTree parser', 'serialize an ElementTree or Element node to a string with optional pretty formatting', 'merge a donor XML file into a receiver XML file at a specified node', 'merge two XML files and return the combined result as an ElementTree object', 'merge two XML files and return the combined result as a formatted string']
```

Usage

```
{'run_visualize_policy_onscreen': 'run a MuJoCo environment policy visualization onscreen for a given number of episodes', 'run_visualize_policy_offscreen': 'run a MuJoCo environment policy visualization offscreen and save the rendered video to a file', 'run_random_policy_exploration': 'run a random policy exploration on a MuJoCo environment with no policy file provided', 'run_policy_evaluation_from_pickle': 'run a pickled policy file in evaluation mode on a MuJoCo environment', 'review_rand_policy_class': 'review the rand_policy class that samples random actions from the environment action space'}
```

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/utils/xml_utils.py

Prompts

```
['create an ObsVecDict instance and initialize it with an observation dictionary and ordered keys', 'convert an observation dictionary to a flattened observation vector using ObsVecDict', 'convert a flattened observation vector back to an observation dictionary using ObsVecDict', 'add, retrieve, or flush observation vectors in the ObsVecDict timestamped cache', 'squeeze singleton dimensions or expand observation dictionary values to 3D shape', 'convert euler angles to a quaternion using the euler2quat function', 'convert a quaternion to a 3x3 rotation matrix using the quat2mat function', 'convert a 3x3 rotation matrix to a quaternion using the mat2quat function', 'multiply two quaternions together using the mulQuat function', 'convert an axis and angle representation to a quaternion using axis_angle2quat', 'calculate the cosine similarity between two numpy vectors with optional batch dimensions', 'calculate the cosine angle between two batched numpy arrays using einsum', 'test the calculate_cosine function with two numpy arrays of the same shape', 'review the calculate_cosine function for handling zero-norm vectors safely', 'refactor the calculate_cosine function to use numpy broadcasting instead of einsum', 'run a MuJoCo environment policy visualization onscreen for a given number of episodes', 'run a MuJoCo environment policy visualization offscreen and save the rendered video to a file', 'run a random policy exploration on a MuJoCo environment with no policy file provided', 'run a pickled policy file in evaluation mode on a MuJoCo environment', 'review the rand_policy class that samples random actions from the environment action space', 'parse an XML file preserving comments using a version-aware ElementTree parser', 'serialize an ElementTree or Element node to a string with optional pretty formatting', 'merge a donor XML file into a receiver XML file at a specified node', 'merge two XML files and return the combined result as an ElementTree object', 'merge two XML files and return the combined result as a formatted string']
```

Usage

```
{'parse_xml_with_comments': 'parse an XML file preserving comments using a version-aware ElementTree parser', 'get_xml_str': 'serialize an ElementTree or Element node to a string with optional pretty formatting', 'merge_xmls': 'merge a donor XML file into a receiver XML file at a specified node', 'merge_xmls_to_tree': 'merge two XML files and return the combined result as an ElementTree object', 'merge_xmls_to_string': 'merge two XML files and return the combined result as a formatted string'}
```

