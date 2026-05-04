# Agent Python Tools

- repo: facebookresearch/denoisedmdp
- repo_uri: https://github.com/facebookresearch/denoised_mdp

## File: facebookresearch_denoisedmdp/denoised_mdp/io.py

Prompts

```
['write a list of torch tensor frames to an MP4 video file at a given path', 'make a grid of images from a batch of tensors with configurable rows and padding', 'normalize image tensors in a grid to a specified value range before display', 'create a grid from single-channel tensors by automatically converting to three channels', 'create an image grid whose dimensions are divisible by 16 for ffmpeg compatibility', 'create an ExperienceReplay buffer with an AutoResetEnvBase environment and a reset step action fill value tensor', 'sample a batch of sequence segments of given length from the ExperienceReplay buffer', 'append a reset step with an observation tensor to the ExperienceReplay buffer starting a new episode', 'append a step with action, reward, next observation, and done flag to the ExperienceReplay buffer', 'compute a checksum-like XOR digest of a PyTorch tensor using the checkxor function for data integrity verification']
```

Usage

```
{'write_video_from_frames': 'write a list of torch tensor frames to an MP4 video file at a given path', 'make_grid_of_images': 'make a grid of images from a batch of tensors with configurable rows and padding', 'normalize_tensor_grid': 'normalize image tensors in a grid to a specified value range before display', 'create_single_channel_grid': 'create a grid from single-channel tensors by automatically converting to three channels', 'ensure_grid_divisible_by_16': 'create an image grid whose dimensions are divisible by 16 for ffmpeg compatibility'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/memory.py

Prompts

```
['write a list of torch tensor frames to an MP4 video file at a given path', 'make a grid of images from a batch of tensors with configurable rows and padding', 'normalize image tensors in a grid to a specified value range before display', 'create a grid from single-channel tensors by automatically converting to three channels', 'create an image grid whose dimensions are divisible by 16 for ffmpeg compatibility', 'create an ExperienceReplay buffer with an AutoResetEnvBase environment and a reset step action fill value tensor', 'sample a batch of sequence segments of given length from the ExperienceReplay buffer', 'append a reset step with an observation tensor to the ExperienceReplay buffer starting a new episode', 'append a step with action, reward, next observation, and done flag to the ExperienceReplay buffer', 'compute a checksum-like XOR digest of a PyTorch tensor using the checkxor function for data integrity verification']
```

Usage

```
{'create_experience_replay_buffer': 'create an ExperienceReplay buffer with an AutoResetEnvBase environment and a reset step action fill value tensor', 'sample_replay_segments': 'sample a batch of sequence segments of given length from the ExperienceReplay buffer', 'append_reset_to_replay': 'append a reset step with an observation tensor to the ExperienceReplay buffer starting a new episode', 'append_step_to_replay': 'append a step with action, reward, next observation, and done flag to the ExperienceReplay buffer', 'compute_tensor_checksum': 'compute a checksum-like XOR digest of a PyTorch tensor using the checkxor function for data integrity verification'}
```

