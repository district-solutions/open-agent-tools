# Agent Python Tools

- repo: facebookresearch/pytorchvideo
- repo_uri: https://github.com/facebookresearch/pytorchvideo

## File: facebookresearch_pytorchvideo/pytorchvideo/data/ego4d/ego4d_dataset.py

Prompts

```
['create an Ego4dMomentsDataset instance to load Ego4D video, audio, and IMU data for the moments benchmark', 'load and normalize IMU sensor data from CSV files using the Ego4dImuData class for a given video UID', 'get a time-windowed IMU signal sample for a specific video clip start and end time', 'build a torchaudio signal transform for spectrogram, melspectrogram, or MFCC audio feature extraction', 'convert a list of Ego4D moment label strings into a one-hot encoded integer list', 'constrain a time window to a fixed length and video duration bounds', 'create a clip sampler that returns a fixed window around an Ego4d annotation', 'load a label ID mapping from a JSON file using iopath', 'review the abstract base class for Ego4d IMU data access with has_imu and get_imu_sample methods', 'refactor the MomentsClipSampler call method to adjust clip start and end times for video boundaries']
```

Usage

```
{'create_ego4d_moments_dataset': 'create an Ego4dMomentsDataset instance to load Ego4D video, audio, and IMU data for the moments benchmark', 'load_imu_data': 'load and normalize IMU sensor data from CSV files using the Ego4dImuData class for a given video UID', 'get_imu_sample': 'get a time-windowed IMU signal sample for a specific video clip start and end time', 'build_audio_transform': 'build a torchaudio signal transform for spectrogram, melspectrogram, or MFCC audio feature extraction', 'convert_labels_one_hot': 'convert a list of Ego4D moment label strings into a one-hot encoded integer list'}
```

## File: facebookresearch_pytorchvideo/pytorchvideo/data/ego4d/utils.py

Prompts

```
['create an Ego4dMomentsDataset instance to load Ego4D video, audio, and IMU data for the moments benchmark', 'load and normalize IMU sensor data from CSV files using the Ego4dImuData class for a given video UID', 'get a time-windowed IMU signal sample for a specific video clip start and end time', 'build a torchaudio signal transform for spectrogram, melspectrogram, or MFCC audio feature extraction', 'convert a list of Ego4D moment label strings into a one-hot encoded integer list', 'constrain a time window to a fixed length and video duration bounds', 'create a clip sampler that returns a fixed window around an Ego4d annotation', 'load a label ID mapping from a JSON file using iopath', 'review the abstract base class for Ego4d IMU data access with has_imu and get_imu_sample methods', 'refactor the MomentsClipSampler call method to adjust clip start and end times for video boundaries']
```

Usage

```
{'check_window_len': 'constrain a time window to a fixed length and video duration bounds', 'create_MomentsClipSampler': 'create a clip sampler that returns a fixed window around an Ego4d annotation', 'get_label_id_map': 'load a label ID mapping from a JSON file using iopath', 'review_Ego4dImuDataBase': 'review the abstract base class for Ego4d IMU data access with has_imu and get_imu_sample methods', 'refactor_MomentsClipSampler_call': 'refactor the MomentsClipSampler call method to adjust clip start and end times for video boundaries'}
```

