# Agent Python Tools

- repo: facebookresearch/emg2pose
- repo_uri: https://github.com/facebookresearch/emg2pose

## File: facebookresearch_emg2pose/emg2pose/tests/test_data.py

Prompts

```
['test the Emg2PoseSessionData class by loading an HDF5 file and validating metadata and timeseries', 'test the pytest fixture that returns the path to a test HDF5 data file', 'test that Emg2PoseSessionData metadata contains all expected keys like filename, session, and user', 'test that Emg2PoseSessionData metadata values match expected types like str, float, and np.int64', 'test that Emg2PoseSessionData timeseries arrays have correct shapes for time, emg, and joint_angles', 'test the forward_kinematics function with random joint angles and verify output tensor shape', 'run forward_kinematics on a batch of joint angle tensors to compute 3D landmark coordinates', 'create a test that generates random joint angles and asserts the output shape from forward_kinematics', 'review the forward_kinematics function to understand how joint angles are converted to 3D coordinates', 'summarize the forward_kinematics function that converts batched joint angles to 3D hand landmark positions', 'test the plot_hand_mesh function by rendering a hand mesh from joint angles and verifying the output figure', 'run the test suite to verify plot_hand_mesh returns a valid Plotly figure with expected vertex count', 'review the test_hand_mesh_plot function to understand how joint angles map to hand mesh visualization', 'refactor the test_hand_mesh_plot function to test additional edge cases like different flip or opacity values', 'summarize the test_visualization module which validates the plot_hand_mesh visualization function output']
```

Usage

```
{'test_Emg2PoseSessionData': 'test the Emg2PoseSessionData class by loading an HDF5 file and validating metadata and timeseries', 'test_hdf5_path_fixture': 'test the pytest fixture that returns the path to a test HDF5 data file', 'test_metadata_keys_validation': 'test that Emg2PoseSessionData metadata contains all expected keys like filename, session, and user', 'test_metadata_types_validation': 'test that Emg2PoseSessionData metadata values match expected types like str, float, and np.int64', 'test_timeseries_shapes_validation': 'test that Emg2PoseSessionData timeseries arrays have correct shapes for time, emg, and joint_angles'}
```

## File: facebookresearch_emg2pose/emg2pose/tests/test_kinematics.py

Prompts

```
['test the Emg2PoseSessionData class by loading an HDF5 file and validating metadata and timeseries', 'test the pytest fixture that returns the path to a test HDF5 data file', 'test that Emg2PoseSessionData metadata contains all expected keys like filename, session, and user', 'test that Emg2PoseSessionData metadata values match expected types like str, float, and np.int64', 'test that Emg2PoseSessionData timeseries arrays have correct shapes for time, emg, and joint_angles', 'test the forward_kinematics function with random joint angles and verify output tensor shape', 'run forward_kinematics on a batch of joint angle tensors to compute 3D landmark coordinates', 'create a test that generates random joint angles and asserts the output shape from forward_kinematics', 'review the forward_kinematics function to understand how joint angles are converted to 3D coordinates', 'summarize the forward_kinematics function that converts batched joint angles to 3D hand landmark positions', 'test the plot_hand_mesh function by rendering a hand mesh from joint angles and verifying the output figure', 'run the test suite to verify plot_hand_mesh returns a valid Plotly figure with expected vertex count', 'review the test_hand_mesh_plot function to understand how joint angles map to hand mesh visualization', 'refactor the test_hand_mesh_plot function to test additional edge cases like different flip or opacity values', 'summarize the test_visualization module which validates the plot_hand_mesh visualization function output']
```

Usage

```
{'test_forward_kinematics': 'test the forward_kinematics function with random joint angles and verify output tensor shape', 'run_forward_kinematics': 'run forward_kinematics on a batch of joint angle tensors to compute 3D landmark coordinates', 'create_forward_kinematics_test': 'create a test that generates random joint angles and asserts the output shape from forward_kinematics', 'review_forward_kinematics': 'review the forward_kinematics function to understand how joint angles are converted to 3D coordinates', 'summarize_forward_kinematics': 'summarize the forward_kinematics function that converts batched joint angles to 3D hand landmark positions'}
```

## File: facebookresearch_emg2pose/emg2pose/tests/test_visualization.py

Prompts

```
['test the Emg2PoseSessionData class by loading an HDF5 file and validating metadata and timeseries', 'test the pytest fixture that returns the path to a test HDF5 data file', 'test that Emg2PoseSessionData metadata contains all expected keys like filename, session, and user', 'test that Emg2PoseSessionData metadata values match expected types like str, float, and np.int64', 'test that Emg2PoseSessionData timeseries arrays have correct shapes for time, emg, and joint_angles', 'test the forward_kinematics function with random joint angles and verify output tensor shape', 'run forward_kinematics on a batch of joint angle tensors to compute 3D landmark coordinates', 'create a test that generates random joint angles and asserts the output shape from forward_kinematics', 'review the forward_kinematics function to understand how joint angles are converted to 3D coordinates', 'summarize the forward_kinematics function that converts batched joint angles to 3D hand landmark positions', 'test the plot_hand_mesh function by rendering a hand mesh from joint angles and verifying the output figure', 'run the test suite to verify plot_hand_mesh returns a valid Plotly figure with expected vertex count', 'review the test_hand_mesh_plot function to understand how joint angles map to hand mesh visualization', 'refactor the test_hand_mesh_plot function to test additional edge cases like different flip or opacity values', 'summarize the test_visualization module which validates the plot_hand_mesh visualization function output']
```

Usage

```
{'test_hand_mesh_plot': 'test the plot_hand_mesh function by rendering a hand mesh from joint angles and verifying the output figure', 'run_test_visualization': 'run the test suite to verify plot_hand_mesh returns a valid Plotly figure with expected vertex count', 'review_test_hand_mesh_plot': 'review the test_hand_mesh_plot function to understand how joint angles map to hand mesh visualization', 'refactor_test_hand_mesh_plot': 'refactor the test_hand_mesh_plot function to test additional edge cases like different flip or opacity values', 'summarize_test_visualization': 'summarize the test_visualization module which validates the plot_hand_mesh visualization function output'}
```

