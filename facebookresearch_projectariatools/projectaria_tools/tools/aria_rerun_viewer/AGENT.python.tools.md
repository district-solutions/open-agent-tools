# Agent Python Tools

- repo: facebookresearch/projectariatools
- repo_uri: https://github.com/facebookresearch/projectaria_tools

## File: facebookresearch_projectariatools/projectaria_tools/tools/aria_rerun_viewer/aria_data_plotter.py

Prompts

```
['create an AriaDataViewer instance with config and device calibration to visualize Project Aria sensor data in Rerun', 'plot camera image frames from RGB or SLAM sensors with JPEG compression and Gen1 rotation handling', 'plot IMU accelerometer and gyroscope data as time series using bulk vectorized logging for efficiency', 'plot eye gaze spatial points and combined gaze directions in 2D camera views and 3D world view', 'plot left and right hand landmark positions and skeleton in both 2D camera and 3D world views', 'run the aria rerun viewer CLI to visualize VRS sensor data from an Aria device recording', 'run log_vrs_to_rerun to convert a VRS file into a Rerun recording with optional stream filtering and subsampling', 'run parse_subsample_rates to parse CLI subsampling arguments like camera-rgb=2 into a stream-to-rate dictionary', 'run get_deliver_option to configure DeliverQueuedOptions for a VRS data provider with enabled streams and subsample rates', 'run plot_queued_sensor_data to iterate over queued VRS sensor data and plot images, IMU, GPS, audio, and more']
```

Usage

```
{'create_aria_data_viewer': 'create an AriaDataViewer instance with config and device calibration to visualize Project Aria sensor data in Rerun', 'plot_image_frames': 'plot camera image frames from RGB or SLAM sensors with JPEG compression and Gen1 rotation handling', 'plot_imu_sensor_data': 'plot IMU accelerometer and gyroscope data as time series using bulk vectorized logging for efficiency', 'plot_eye_gaze_data': 'plot eye gaze spatial points and combined gaze directions in 2D camera views and 3D world view', 'plot_hand_pose_data': 'plot left and right hand landmark positions and skeleton in both 2D camera and 3D world views'}
```

## File: facebookresearch_projectariatools/projectaria_tools/tools/aria_rerun_viewer/aria_rerun_viewer.py

Prompts

```
['create an AriaDataViewer instance with config and device calibration to visualize Project Aria sensor data in Rerun', 'plot camera image frames from RGB or SLAM sensors with JPEG compression and Gen1 rotation handling', 'plot IMU accelerometer and gyroscope data as time series using bulk vectorized logging for efficiency', 'plot eye gaze spatial points and combined gaze directions in 2D camera views and 3D world view', 'plot left and right hand landmark positions and skeleton in both 2D camera and 3D world views', 'run the aria rerun viewer CLI to visualize VRS sensor data from an Aria device recording', 'run log_vrs_to_rerun to convert a VRS file into a Rerun recording with optional stream filtering and subsampling', 'run parse_subsample_rates to parse CLI subsampling arguments like camera-rgb=2 into a stream-to-rate dictionary', 'run get_deliver_option to configure DeliverQueuedOptions for a VRS data provider with enabled streams and subsample rates', 'run plot_queued_sensor_data to iterate over queued VRS sensor data and plot images, IMU, GPS, audio, and more']
```

Usage

```
{'run_vrs_to_rerun_viewer': 'run the aria rerun viewer CLI to visualize VRS sensor data from an Aria device recording', 'run_log_vrs_to_rerun': 'run log_vrs_to_rerun to convert a VRS file into a Rerun recording with optional stream filtering and subsampling', 'run_parse_subsample_rates': 'run parse_subsample_rates to parse CLI subsampling arguments like camera-rgb=2 into a stream-to-rate dictionary', 'run_get_deliver_option': 'run get_deliver_option to configure DeliverQueuedOptions for a VRS data provider with enabled streams and subsample rates', 'run_plot_queued_sensor_data': 'run plot_queued_sensor_data to iterate over queued VRS sensor data and plot images, IMU, GPS, audio, and more'}
```

