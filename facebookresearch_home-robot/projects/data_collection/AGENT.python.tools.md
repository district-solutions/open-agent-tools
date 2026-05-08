# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/data_collection/collect_h5.py

Prompts

```
['run the h5 data collection script with a task name and directory path via click CLI', 'create an EpisodeManager instance to manage episodic data recording for a named task', 'toggle episode recording on or off using the EpisodeManager toggle_episode method', 'record a keyframe to the current episode using the EpisodeManager record_keyframe method', 'review the EpisodeManager class and its episode recording and keyframe management logic', 'create a SimpleDataset instance to load HomeRobot trial data from a directory path', 'run a PyTorch DataLoader with SimpleDataset to batch and iterate over training examples', 'get a single training example with temporal and image tensors from a trial by index', 'review the SimpleDataset get_datum method to understand how temporal and image keys are extracted', 'test the SimpleDataset main block to visualize RGB and depth images from sample data']
```

Usage

```
{'run_collect_h5': 'run the h5 data collection script with a task name and directory path via click CLI', 'create_EpisodeManager': 'create an EpisodeManager instance to manage episodic data recording for a named task', 'toggle_episode': 'toggle episode recording on or off using the EpisodeManager toggle_episode method', 'record_keyframe': 'record a keyframe to the current episode using the EpisodeManager record_keyframe method', 'review_EpisodeManager': 'review the EpisodeManager class and its episode recording and keyframe management logic'}
```

## File: facebookresearch_home-robot/projects/data_collection/tutorial_h5_dataloader.py

Prompts

```
['run the h5 data collection script with a task name and directory path via click CLI', 'create an EpisodeManager instance to manage episodic data recording for a named task', 'toggle episode recording on or off using the EpisodeManager toggle_episode method', 'record a keyframe to the current episode using the EpisodeManager record_keyframe method', 'review the EpisodeManager class and its episode recording and keyframe management logic', 'create a SimpleDataset instance to load HomeRobot trial data from a directory path', 'run a PyTorch DataLoader with SimpleDataset to batch and iterate over training examples', 'get a single training example with temporal and image tensors from a trial by index', 'review the SimpleDataset get_datum method to understand how temporal and image keys are extracted', 'test the SimpleDataset main block to visualize RGB and depth images from sample data']
```

Usage

```
{'create_SimpleDataset': 'create a SimpleDataset instance to load HomeRobot trial data from a directory path', 'run_SimpleDataset_dataloader': 'run a PyTorch DataLoader with SimpleDataset to batch and iterate over training examples', 'get_datum_SimpleDataset': 'get a single training example with temporal and image tensors from a trial by index', 'review_SimpleDataset_get_datum': 'review the SimpleDataset get_datum method to understand how temporal and image keys are extracted', 'test_SimpleDataset_main': 'test the SimpleDataset main block to visualize RGB and depth images from sample data'}
```

