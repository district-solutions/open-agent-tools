# Agent Python Tools

- repo: facebookresearch/pytorchvideo
- repo_uri: https://github.com/facebookresearch/pytorchvideo

## File: facebookresearch_pytorchvideo/pytorchvideo/data/epic_kitchen/epic_kitchen_dataset.py

Prompts

```
['create an EpicKitchenDataset instance with video info, actions CSV, clip sampler, and data manifest paths', 'sample a video clip by index from the EpicKitchenDataset returning video tensor, audio, and actions', 'define an ActionData dataclass with participant ID, video ID, verb, noun, timestamps, and frame ranges', 'get the start time in seconds from an ActionData instance using the start_time property', 'get the total number of video clips in the EpicKitchenDataset using the length method', 'build a frame manifest dictionary from a flat directory of video frames with optional multithreading', 'build a frame manifest dictionary from a nested participant directory structure with optional multithreading', 'build an encoded video manifest dictionary from a nested participant directory structure', 'review the build_frame_manifest_from_flat_directory function that parses frame files into VideoFrameInfo objects', 'review the build_frame_manifest_from_nested_directory function that parses participant-based frame files into VideoFrameInfo objects']
```

Usage

```
{'create_epic_kitchen_dataset': 'create an EpicKitchenDataset instance with video info, actions CSV, clip sampler, and data manifest paths', 'sample_video_clip': 'sample a video clip by index from the EpicKitchenDataset returning video tensor, audio, and actions', 'define_action_data': 'define an ActionData dataclass with participant ID, video ID, verb, noun, timestamps, and frame ranges', 'get_action_start_time': 'get the start time in seconds from an ActionData instance using the start_time property', 'get_dataset_length': 'get the total number of video clips in the EpicKitchenDataset using the length method'}
```

## File: facebookresearch_pytorchvideo/pytorchvideo/data/epic_kitchen/utils.py

Prompts

```
['create an EpicKitchenDataset instance with video info, actions CSV, clip sampler, and data manifest paths', 'sample a video clip by index from the EpicKitchenDataset returning video tensor, audio, and actions', 'define an ActionData dataclass with participant ID, video ID, verb, noun, timestamps, and frame ranges', 'get the start time in seconds from an ActionData instance using the start_time property', 'get the total number of video clips in the EpicKitchenDataset using the length method', 'build a frame manifest dictionary from a flat directory of video frames with optional multithreading', 'build a frame manifest dictionary from a nested participant directory structure with optional multithreading', 'build an encoded video manifest dictionary from a nested participant directory structure', 'review the build_frame_manifest_from_flat_directory function that parses frame files into VideoFrameInfo objects', 'review the build_frame_manifest_from_nested_directory function that parses participant-based frame files into VideoFrameInfo objects']
```

Usage

```
{'build_frame_manifest_flat': 'build a frame manifest dictionary from a flat directory of video frames with optional multithreading', 'build_frame_manifest_nested': 'build a frame manifest dictionary from a nested participant directory structure with optional multithreading', 'build_encoded_manifest_nested': 'build an encoded video manifest dictionary from a nested participant directory structure', 'review_build_frame_manifest_from_flat_directory': 'review the build_frame_manifest_from_flat_directory function that parses frame files into VideoFrameInfo objects', 'review_build_frame_manifest_from_nested_directory': 'review the build_frame_manifest_from_nested_directory function that parses participant-based frame files into VideoFrameInfo objects'}
```

