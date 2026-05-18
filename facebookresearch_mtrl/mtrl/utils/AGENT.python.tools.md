# Agent Python Tools

- repo: facebookresearch/mtrl
- repo_uri: https://github.com/facebookresearch/mtrl

## File: facebookresearch_mtrl/mtrl/utils/checkpointable.py

Prompts

```
['review the Checkpointable abstract base class and its save and load abstract methods', 'build a subclass of Checkpointable that implements save and load for custom state', 'refactor the Checkpointable save method to support additional serialization formats', 'test a Checkpointable subclass to verify save and load round-trip correctness', 'summarize the Checkpointable interface and its abstract save and load methods', 'process an OmegaConf config by resolving setup fields, git info, and creating experiment directories', 'read an OmegaConf config from a YAML file on the filesystem and return it as an immutable struct', 'convert a Python dictionary into an OmegaConf config object for use with Hydra', 'convert an OmegaConf config object back into a plain Python dictionary with resolved values', 'extract environment builder parameters from a config by removing the hydra target key', 'flatten a list of lists into a single flat list using the flatten_list utility function', 'split a list into successive n-sized chunks using the chunks utility function', 'create a directory with parent directories using the make_dir utility function', 'set the random seed for python numpy and torch using the set_seed utility function', 'check if the git working directory has uncommitted changes using the has_uncommitted_changes utility function', 'create a VideoRecorder instance to record environment frames into a video file', 'initialize the VideoRecorder with enabled flag to start or stop recording', 'record a single frame or render from an environment using the VideoRecorder', 'save recorded frames as a video file with a specified filename using VideoRecorder', 'review the VideoRecorder class and its frame recording and video saving methods']
```

Usage

```
{'review_Checkpointable': 'review the Checkpointable abstract base class and its save and load abstract methods', 'build_Checkpointable_subclass': 'build a subclass of Checkpointable that implements save and load for custom state', 'refactor_Checkpointable_save': 'refactor the Checkpointable save method to support additional serialization formats', 'test_Checkpointable_subclass': 'test a Checkpointable subclass to verify save and load round-trip correctness', 'summarize_Checkpointable': 'summarize the Checkpointable interface and its abstract save and load methods'}
```

## File: facebookresearch_mtrl/mtrl/utils/config.py

Prompts

```
['review the Checkpointable abstract base class and its save and load abstract methods', 'build a subclass of Checkpointable that implements save and load for custom state', 'refactor the Checkpointable save method to support additional serialization formats', 'test a Checkpointable subclass to verify save and load round-trip correctness', 'summarize the Checkpointable interface and its abstract save and load methods', 'process an OmegaConf config by resolving setup fields, git info, and creating experiment directories', 'read an OmegaConf config from a YAML file on the filesystem and return it as an immutable struct', 'convert a Python dictionary into an OmegaConf config object for use with Hydra', 'convert an OmegaConf config object back into a plain Python dictionary with resolved values', 'extract environment builder parameters from a config by removing the hydra target key', 'flatten a list of lists into a single flat list using the flatten_list utility function', 'split a list into successive n-sized chunks using the chunks utility function', 'create a directory with parent directories using the make_dir utility function', 'set the random seed for python numpy and torch using the set_seed utility function', 'check if the git working directory has uncommitted changes using the has_uncommitted_changes utility function', 'create a VideoRecorder instance to record environment frames into a video file', 'initialize the VideoRecorder with enabled flag to start or stop recording', 'record a single frame or render from an environment using the VideoRecorder', 'save recorded frames as a video file with a specified filename using VideoRecorder', 'review the VideoRecorder class and its frame recording and video saving methods']
```

Usage

```
{'process_config': 'process an OmegaConf config by resolving setup fields, git info, and creating experiment directories', 'read_config_from_file': 'read an OmegaConf config from a YAML file on the filesystem and return it as an immutable struct', 'dict_to_config': 'convert a Python dictionary into an OmegaConf config object for use with Hydra', 'to_dict': 'convert an OmegaConf config object back into a plain Python dictionary with resolved values', 'get_env_params_from_config': 'extract environment builder parameters from a config by removing the hydra target key'}
```

## File: facebookresearch_mtrl/mtrl/utils/utils.py

Prompts

```
['review the Checkpointable abstract base class and its save and load abstract methods', 'build a subclass of Checkpointable that implements save and load for custom state', 'refactor the Checkpointable save method to support additional serialization formats', 'test a Checkpointable subclass to verify save and load round-trip correctness', 'summarize the Checkpointable interface and its abstract save and load methods', 'process an OmegaConf config by resolving setup fields, git info, and creating experiment directories', 'read an OmegaConf config from a YAML file on the filesystem and return it as an immutable struct', 'convert a Python dictionary into an OmegaConf config object for use with Hydra', 'convert an OmegaConf config object back into a plain Python dictionary with resolved values', 'extract environment builder parameters from a config by removing the hydra target key', 'flatten a list of lists into a single flat list using the flatten_list utility function', 'split a list into successive n-sized chunks using the chunks utility function', 'create a directory with parent directories using the make_dir utility function', 'set the random seed for python numpy and torch using the set_seed utility function', 'check if the git working directory has uncommitted changes using the has_uncommitted_changes utility function', 'create a VideoRecorder instance to record environment frames into a video file', 'initialize the VideoRecorder with enabled flag to start or stop recording', 'record a single frame or render from an environment using the VideoRecorder', 'save recorded frames as a video file with a specified filename using VideoRecorder', 'review the VideoRecorder class and its frame recording and video saving methods']
```

Usage

```
{'flatten_list': 'flatten a list of lists into a single flat list using the flatten_list utility function', 'chunk_list': 'split a list into successive n-sized chunks using the chunks utility function', 'create_directory': 'create a directory with parent directories using the make_dir utility function', 'set_random_seed': 'set the random seed for python numpy and torch using the set_seed utility function', 'check_git_status': 'check if the git working directory has uncommitted changes using the has_uncommitted_changes utility function'}
```

## File: facebookresearch_mtrl/mtrl/utils/video.py

Prompts

```
['review the Checkpointable abstract base class and its save and load abstract methods', 'build a subclass of Checkpointable that implements save and load for custom state', 'refactor the Checkpointable save method to support additional serialization formats', 'test a Checkpointable subclass to verify save and load round-trip correctness', 'summarize the Checkpointable interface and its abstract save and load methods', 'process an OmegaConf config by resolving setup fields, git info, and creating experiment directories', 'read an OmegaConf config from a YAML file on the filesystem and return it as an immutable struct', 'convert a Python dictionary into an OmegaConf config object for use with Hydra', 'convert an OmegaConf config object back into a plain Python dictionary with resolved values', 'extract environment builder parameters from a config by removing the hydra target key', 'flatten a list of lists into a single flat list using the flatten_list utility function', 'split a list into successive n-sized chunks using the chunks utility function', 'create a directory with parent directories using the make_dir utility function', 'set the random seed for python numpy and torch using the set_seed utility function', 'check if the git working directory has uncommitted changes using the has_uncommitted_changes utility function', 'create a VideoRecorder instance to record environment frames into a video file', 'initialize the VideoRecorder with enabled flag to start or stop recording', 'record a single frame or render from an environment using the VideoRecorder', 'save recorded frames as a video file with a specified filename using VideoRecorder', 'review the VideoRecorder class and its frame recording and video saving methods']
```

Usage

```
{'create_video_recorder': 'create a VideoRecorder instance to record environment frames into a video file', 'init_video_recorder': 'initialize the VideoRecorder with enabled flag to start or stop recording', 'record_frame': 'record a single frame or render from an environment using the VideoRecorder', 'save_video': 'save recorded frames as a video file with a specified filename using VideoRecorder', 'review_VideoRecorder_class': 'review the VideoRecorder class and its frame recording and video saving methods'}
```

