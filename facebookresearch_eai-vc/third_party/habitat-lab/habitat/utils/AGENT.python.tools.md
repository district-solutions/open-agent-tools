# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat/utils/geometry_utils.py

Prompts

```
['compute the angle in radians between two numpy quaternions using angle_between_quaternions', 'create a quaternion representing the rotation from one 3D vector to another using quaternion_from_two_vectors', 'rotate a 3D vector by a given quaternion using quaternion_rotate_vector', 'transform a target agent state to the reference agent coordinate system using agent_state_target2ref', 'convert an x y z w coefficient array to a numpy quaternion using quaternion_from_coeff', 'create a ConnectionWrapper instance that proxies a multiprocessing Connection using ForkingPickler5 for serialization', 'send a Python object over a multiprocessing connection using ConnectionWrapper send method with pickle5 protocol', 'receive and deserialize a Python object from a multiprocessing connection using ConnectionWrapper recv method', 'serialize a Python object to a buffer using ForkingPickler5 dumps class method with pickle5 protocol', 'review the ConnectionWrapper class and its __getattr__ method that delegates attributes to the wrapped Connection', 'configure habitat_sim profiling to start capture at a specific step and capture a set number of steps', 'signal the start of a new step to the habitat_sim profiling system', 'push a named profiling range marker onto the NVTX stack for performance tracing', 'pop the most recent profiling range marker off the NVTX stack', 'annotate a code block with a profiling range using a context manager or decorator', 'sample a single non-stop action from a Habitat action space', 'sample multiple non-stop actions from a Habitat action space and return a list', 'test the sample_non_stop_action function to ensure it filters out StopAction', 'review the sample_non_stop_action function for correct StopAction filtering logic', 'refactor sample_non_stop_action to support custom exclusion criteria beyond StopAction']
```

Usage

```
{'compute_angle_between_quaternions': 'compute the angle in radians between two numpy quaternions using angle_between_quaternions', 'create_quaternion_from_two_vectors': 'create a quaternion representing the rotation from one 3D vector to another using quaternion_from_two_vectors', 'rotate_vector_by_quaternion': 'rotate a 3D vector by a given quaternion using quaternion_rotate_vector', 'transform_agent_state_to_reference': 'transform a target agent state to the reference agent coordinate system using agent_state_target2ref', 'convert_quaternion_coefficients': 'convert an x y z w coefficient array to a numpy quaternion using quaternion_from_coeff'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat/utils/pickle5_multiprocessing.py

Prompts

```
['compute the angle in radians between two numpy quaternions using angle_between_quaternions', 'create a quaternion representing the rotation from one 3D vector to another using quaternion_from_two_vectors', 'rotate a 3D vector by a given quaternion using quaternion_rotate_vector', 'transform a target agent state to the reference agent coordinate system using agent_state_target2ref', 'convert an x y z w coefficient array to a numpy quaternion using quaternion_from_coeff', 'create a ConnectionWrapper instance that proxies a multiprocessing Connection using ForkingPickler5 for serialization', 'send a Python object over a multiprocessing connection using ConnectionWrapper send method with pickle5 protocol', 'receive and deserialize a Python object from a multiprocessing connection using ConnectionWrapper recv method', 'serialize a Python object to a buffer using ForkingPickler5 dumps class method with pickle5 protocol', 'review the ConnectionWrapper class and its __getattr__ method that delegates attributes to the wrapped Connection', 'configure habitat_sim profiling to start capture at a specific step and capture a set number of steps', 'signal the start of a new step to the habitat_sim profiling system', 'push a named profiling range marker onto the NVTX stack for performance tracing', 'pop the most recent profiling range marker off the NVTX stack', 'annotate a code block with a profiling range using a context manager or decorator', 'sample a single non-stop action from a Habitat action space', 'sample multiple non-stop actions from a Habitat action space and return a list', 'test the sample_non_stop_action function to ensure it filters out StopAction', 'review the sample_non_stop_action function for correct StopAction filtering logic', 'refactor sample_non_stop_action to support custom exclusion criteria beyond StopAction']
```

Usage

```
{'create_ConnectionWrapper': 'create a ConnectionWrapper instance that proxies a multiprocessing Connection using ForkingPickler5 for serialization', 'send_object_via_wrapper': 'send a Python object over a multiprocessing connection using ConnectionWrapper send method with pickle5 protocol', 'recv_object_via_wrapper': 'receive and deserialize a Python object from a multiprocessing connection using ConnectionWrapper recv method', 'use_ForkingPickler5_dumps': 'serialize a Python object to a buffer using ForkingPickler5 dumps class method with pickle5 protocol', 'review_ConnectionWrapper_proxy': 'review the ConnectionWrapper class and its __getattr__ method that delegates attributes to the wrapped Connection'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat/utils/profiling_wrapper.py

Prompts

```
['compute the angle in radians between two numpy quaternions using angle_between_quaternions', 'create a quaternion representing the rotation from one 3D vector to another using quaternion_from_two_vectors', 'rotate a 3D vector by a given quaternion using quaternion_rotate_vector', 'transform a target agent state to the reference agent coordinate system using agent_state_target2ref', 'convert an x y z w coefficient array to a numpy quaternion using quaternion_from_coeff', 'create a ConnectionWrapper instance that proxies a multiprocessing Connection using ForkingPickler5 for serialization', 'send a Python object over a multiprocessing connection using ConnectionWrapper send method with pickle5 protocol', 'receive and deserialize a Python object from a multiprocessing connection using ConnectionWrapper recv method', 'serialize a Python object to a buffer using ForkingPickler5 dumps class method with pickle5 protocol', 'review the ConnectionWrapper class and its __getattr__ method that delegates attributes to the wrapped Connection', 'configure habitat_sim profiling to start capture at a specific step and capture a set number of steps', 'signal the start of a new step to the habitat_sim profiling system', 'push a named profiling range marker onto the NVTX stack for performance tracing', 'pop the most recent profiling range marker off the NVTX stack', 'annotate a code block with a profiling range using a context manager or decorator', 'sample a single non-stop action from a Habitat action space', 'sample multiple non-stop actions from a Habitat action space and return a list', 'test the sample_non_stop_action function to ensure it filters out StopAction', 'review the sample_non_stop_action function for correct StopAction filtering logic', 'refactor sample_non_stop_action to support custom exclusion criteria beyond StopAction']
```

Usage

```
{'configure_profiling': 'configure habitat_sim profiling to start capture at a specific step and capture a set number of steps', 'on_start_step': 'signal the start of a new step to the habitat_sim profiling system', 'range_push': 'push a named profiling range marker onto the NVTX stack for performance tracing', 'range_pop': 'pop the most recent profiling range marker off the NVTX stack', 'RangeContext': 'annotate a code block with a profiling range using a context manager or decorator'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat/utils/test_utils.py

Prompts

```
['compute the angle in radians between two numpy quaternions using angle_between_quaternions', 'create a quaternion representing the rotation from one 3D vector to another using quaternion_from_two_vectors', 'rotate a 3D vector by a given quaternion using quaternion_rotate_vector', 'transform a target agent state to the reference agent coordinate system using agent_state_target2ref', 'convert an x y z w coefficient array to a numpy quaternion using quaternion_from_coeff', 'create a ConnectionWrapper instance that proxies a multiprocessing Connection using ForkingPickler5 for serialization', 'send a Python object over a multiprocessing connection using ConnectionWrapper send method with pickle5 protocol', 'receive and deserialize a Python object from a multiprocessing connection using ConnectionWrapper recv method', 'serialize a Python object to a buffer using ForkingPickler5 dumps class method with pickle5 protocol', 'review the ConnectionWrapper class and its __getattr__ method that delegates attributes to the wrapped Connection', 'configure habitat_sim profiling to start capture at a specific step and capture a set number of steps', 'signal the start of a new step to the habitat_sim profiling system', 'push a named profiling range marker onto the NVTX stack for performance tracing', 'pop the most recent profiling range marker off the NVTX stack', 'annotate a code block with a profiling range using a context manager or decorator', 'sample a single non-stop action from a Habitat action space', 'sample multiple non-stop actions from a Habitat action space and return a list', 'test the sample_non_stop_action function to ensure it filters out StopAction', 'review the sample_non_stop_action function for correct StopAction filtering logic', 'refactor sample_non_stop_action to support custom exclusion criteria beyond StopAction']
```

Usage

```
{'sample_non_stop_action_single': 'sample a single non-stop action from a Habitat action space', 'sample_non_stop_action_multiple': 'sample multiple non-stop actions from a Habitat action space and return a list', 'test_sample_non_stop_action': 'test the sample_non_stop_action function to ensure it filters out StopAction', 'review_sample_non_stop_action': 'review the sample_non_stop_action function for correct StopAction filtering logic', 'refactor_sample_non_stop_action': 'refactor sample_non_stop_action to support custom exclusion criteria beyond StopAction'}
```

