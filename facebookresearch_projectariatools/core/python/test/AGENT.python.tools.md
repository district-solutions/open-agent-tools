# Agent Python Tools

- repo: facebookresearch/projectariatools
- repo_uri: https://github.com/facebookresearch/projectaria_tools

## File: facebookresearch_projectariatools/core/python/test/corePyBindTest.py

Prompts

```
['test pickling and unpickling of device camera, IMU, magnetometer, barometer, and microphone calibration objects from VRS files', 'test converting raw IMU accelerometer and gyroscope data to rectified values using calibration models', 'test random access of sensor data from VRS files by index and by timestamp across multiple time domains', 'test rotating a camera calibration 90 degrees clockwise and verify pixel unprojection rays remain consistent', 'test reading VRS file metadata including device serial, recording profile, device ID, and time sync mode', 'read an open loop trajectory CSV file using mps.read_open_loop_trajectory', 'read a closed loop trajectory CSV file using mps.read_closed_loop_trajectory', 'read a global point cloud from a CSV or GZIP file using mps.read_global_point_cloud', 'read eye gaze data from a CSV file using mps.read_eyegaze and access vergence fields', 'read hand tracking results from a CSV file using mps.hand_tracking.read_hand_tracking_results', 'run the PFrameRandomAccessTest unittest to verify random access P-frame decoding parity', 'test the sample_indices function to generate boundary and interior frame sample indices', 'test the get_image_array function to retrieve a deep-copied numpy array from a VRS provider', 'review the test_random_access_parity method that compares sequential vs random-access image decoding', 'summarize the PIXEL_TOLERANCE constant used for per-component LSB drift tolerance in pixel comparison']
```

Usage

```
{'test_vrs_calibration_pickle': 'test pickling and unpickling of device camera, IMU, magnetometer, barometer, and microphone calibration objects from VRS files', 'test_imu_raw_to_rectified': 'test converting raw IMU accelerometer and gyroscope data to rectified values using calibration models', 'test_vrs_sensor_data_access': 'test random access of sensor data from VRS files by index and by timestamp across multiple time domains', 'test_camera_calibration_rotation': 'test rotating a camera calibration 90 degrees clockwise and verify pixel unprojection rays remain consistent', 'test_vrs_file_metadata': 'test reading VRS file metadata including device serial, recording profile, device ID, and time sync mode'}
```

## File: facebookresearch_projectariatools/core/python/test/mpsPyBindTest.py

Prompts

```
['test pickling and unpickling of device camera, IMU, magnetometer, barometer, and microphone calibration objects from VRS files', 'test converting raw IMU accelerometer and gyroscope data to rectified values using calibration models', 'test random access of sensor data from VRS files by index and by timestamp across multiple time domains', 'test rotating a camera calibration 90 degrees clockwise and verify pixel unprojection rays remain consistent', 'test reading VRS file metadata including device serial, recording profile, device ID, and time sync mode', 'read an open loop trajectory CSV file using mps.read_open_loop_trajectory', 'read a closed loop trajectory CSV file using mps.read_closed_loop_trajectory', 'read a global point cloud from a CSV or GZIP file using mps.read_global_point_cloud', 'read eye gaze data from a CSV file using mps.read_eyegaze and access vergence fields', 'read hand tracking results from a CSV file using mps.hand_tracking.read_hand_tracking_results', 'run the PFrameRandomAccessTest unittest to verify random access P-frame decoding parity', 'test the sample_indices function to generate boundary and interior frame sample indices', 'test the get_image_array function to retrieve a deep-copied numpy array from a VRS provider', 'review the test_random_access_parity method that compares sequential vs random-access image decoding', 'summarize the PIXEL_TOLERANCE constant used for per-component LSB drift tolerance in pixel comparison']
```

Usage

```
{'read_open_loop_trajectory': 'read an open loop trajectory CSV file using mps.read_open_loop_trajectory', 'read_closed_loop_trajectory': 'read a closed loop trajectory CSV file using mps.read_closed_loop_trajectory', 'read_global_point_cloud': 'read a global point cloud from a CSV or GZIP file using mps.read_global_point_cloud', 'read_eyegaze': 'read eye gaze data from a CSV file using mps.read_eyegaze and access vergence fields', 'read_hand_tracking_results': 'read hand tracking results from a CSV file using mps.hand_tracking.read_hand_tracking_results'}
```

## File: facebookresearch_projectariatools/core/python/test/test_pframe_random_access.py

Prompts

```
['test pickling and unpickling of device camera, IMU, magnetometer, barometer, and microphone calibration objects from VRS files', 'test converting raw IMU accelerometer and gyroscope data to rectified values using calibration models', 'test random access of sensor data from VRS files by index and by timestamp across multiple time domains', 'test rotating a camera calibration 90 degrees clockwise and verify pixel unprojection rays remain consistent', 'test reading VRS file metadata including device serial, recording profile, device ID, and time sync mode', 'read an open loop trajectory CSV file using mps.read_open_loop_trajectory', 'read a closed loop trajectory CSV file using mps.read_closed_loop_trajectory', 'read a global point cloud from a CSV or GZIP file using mps.read_global_point_cloud', 'read eye gaze data from a CSV file using mps.read_eyegaze and access vergence fields', 'read hand tracking results from a CSV file using mps.hand_tracking.read_hand_tracking_results', 'run the PFrameRandomAccessTest unittest to verify random access P-frame decoding parity', 'test the sample_indices function to generate boundary and interior frame sample indices', 'test the get_image_array function to retrieve a deep-copied numpy array from a VRS provider', 'review the test_random_access_parity method that compares sequential vs random-access image decoding', 'summarize the PIXEL_TOLERANCE constant used for per-component LSB drift tolerance in pixel comparison']
```

Usage

```
{'run_PFrameRandomAccessTest': 'run the PFrameRandomAccessTest unittest to verify random access P-frame decoding parity', 'test_sample_indices': 'test the sample_indices function to generate boundary and interior frame sample indices', 'test_get_image_array': 'test the get_image_array function to retrieve a deep-copied numpy array from a VRS provider', 'review_PFrameRandomAccessTest_test_random_access_parity': 'review the test_random_access_parity method that compares sequential vs random-access image decoding', 'summarize_PIXEL_TOLERANCE': 'summarize the PIXEL_TOLERANCE constant used for per-component LSB drift tolerance in pixel comparison'}
```

