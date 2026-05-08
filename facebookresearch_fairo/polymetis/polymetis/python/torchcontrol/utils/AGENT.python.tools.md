# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/python/torchcontrol/utils/tensor_utils.py

Prompts

```
['convert any input into a PyTorch tensor of the default dtype using to_tensor', 'stack a list of tensors into a single tensor using stack_trajectory', 'convert a 1-D gain vector into a diagonal 2-D matrix using diagonalize_gain', 'pass through a 2-D gain matrix unchanged using diagonalize_gain', 'review the tensor_utils module for to_tensor, stack_trajectory, and diagonalize_gain functions', 'create a FakeRobotModel with a given number of joints for testing robot control algorithms', 'test the FakeRobotModel compute_jacobian method to return a 6xN identity matrix', 'test the FakeRobotModel forward_kinematics method to return position and quaternion outputs', 'test the FakeRobotModel inverse_dynamics method to return joint torque values', 'test the record_or_compare function to save or compare torch tensor dictionaries for regression testing', 'subtract two torch tensor timestamps each with seconds and nanoseconds elements', 'compute the time difference in seconds between two torch tensor timestamps', 'compute the time difference in milliseconds between two torch tensor timestamps', 'review the timestamp_subtract function that subtracts two shape (2,) torch tensor timestamps', 'summarize the time_utils module with functions for timestamp subtraction and diff calculations']
```

Usage

```
{'convert_to_tensor': 'convert any input into a PyTorch tensor of the default dtype using to_tensor', 'stack_trajectory_list': 'stack a list of tensors into a single tensor using stack_trajectory', 'diagonalize_gain_vector': 'convert a 1-D gain vector into a diagonal 2-D matrix using diagonalize_gain', 'diagonalize_gain_matrix': 'pass through a 2-D gain matrix unchanged using diagonalize_gain', 'review_tensor_utils': 'review the tensor_utils module for to_tensor, stack_trajectory, and diagonalize_gain functions'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/torchcontrol/utils/test_utils.py

Prompts

```
['convert any input into a PyTorch tensor of the default dtype using to_tensor', 'stack a list of tensors into a single tensor using stack_trajectory', 'convert a 1-D gain vector into a diagonal 2-D matrix using diagonalize_gain', 'pass through a 2-D gain matrix unchanged using diagonalize_gain', 'review the tensor_utils module for to_tensor, stack_trajectory, and diagonalize_gain functions', 'create a FakeRobotModel with a given number of joints for testing robot control algorithms', 'test the FakeRobotModel compute_jacobian method to return a 6xN identity matrix', 'test the FakeRobotModel forward_kinematics method to return position and quaternion outputs', 'test the FakeRobotModel inverse_dynamics method to return joint torque values', 'test the record_or_compare function to save or compare torch tensor dictionaries for regression testing', 'subtract two torch tensor timestamps each with seconds and nanoseconds elements', 'compute the time difference in seconds between two torch tensor timestamps', 'compute the time difference in milliseconds between two torch tensor timestamps', 'review the timestamp_subtract function that subtracts two shape (2,) torch tensor timestamps', 'summarize the time_utils module with functions for timestamp subtraction and diff calculations']
```

Usage

```
{'create_FakeRobotModel': 'create a FakeRobotModel with a given number of joints for testing robot control algorithms', 'test_FakeRobotModel_compute_jacobian': 'test the FakeRobotModel compute_jacobian method to return a 6xN identity matrix', 'test_FakeRobotModel_forward_kinematics': 'test the FakeRobotModel forward_kinematics method to return position and quaternion outputs', 'test_FakeRobotModel_inverse_dynamics': 'test the FakeRobotModel inverse_dynamics method to return joint torque values', 'test_record_or_compare': 'test the record_or_compare function to save or compare torch tensor dictionaries for regression testing'}
```

## File: facebookresearch_fairo/polymetis/polymetis/python/torchcontrol/utils/time_utils.py

Prompts

```
['convert any input into a PyTorch tensor of the default dtype using to_tensor', 'stack a list of tensors into a single tensor using stack_trajectory', 'convert a 1-D gain vector into a diagonal 2-D matrix using diagonalize_gain', 'pass through a 2-D gain matrix unchanged using diagonalize_gain', 'review the tensor_utils module for to_tensor, stack_trajectory, and diagonalize_gain functions', 'create a FakeRobotModel with a given number of joints for testing robot control algorithms', 'test the FakeRobotModel compute_jacobian method to return a 6xN identity matrix', 'test the FakeRobotModel forward_kinematics method to return position and quaternion outputs', 'test the FakeRobotModel inverse_dynamics method to return joint torque values', 'test the record_or_compare function to save or compare torch tensor dictionaries for regression testing', 'subtract two torch tensor timestamps each with seconds and nanoseconds elements', 'compute the time difference in seconds between two torch tensor timestamps', 'compute the time difference in milliseconds between two torch tensor timestamps', 'review the timestamp_subtract function that subtracts two shape (2,) torch tensor timestamps', 'summarize the time_utils module with functions for timestamp subtraction and diff calculations']
```

Usage

```
{'subtract_timestamps': 'subtract two torch tensor timestamps each with seconds and nanoseconds elements', 'compute_timestamp_diff_seconds': 'compute the time difference in seconds between two torch tensor timestamps', 'compute_timestamp_diff_ms': 'compute the time difference in milliseconds between two torch tensor timestamps', 'review_timestamp_subtract': 'review the timestamp_subtract function that subtracts two shape (2,) torch tensor timestamps', 'summarize_time_utils': 'summarize the time_utils module with functions for timestamp subtraction and diff calculations'}
```

