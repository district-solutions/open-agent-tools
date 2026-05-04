# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/il/data/data.py

Prompts

```
['build a python module to create an EQADataset for embodied QA with VQA and PACMAN input types', 'create an EQADataset instance that caches episode frames to disk and builds a tar archive', 'test the EQADataset group_by_keys_ method to verify webdataset sample grouping and padding', 'refactor the EQADataset calc_max_length method to compute max question and action lengths for padding', 'review the EQADataset save_frame_queue method that renders simulator observations and saves frames as JPEGs', 'create an EQACNNPretrainDataset instance from a Habitat config for train or val mode', 'save rgb, depth, and semantic segmentation frames from shortest path positions to an LMDB database', 'load a new scene into the Habitat simulator by reconfiguring the simulator with the scene path', 'retrieve an indexed batch of rgb, depth, and segmentation tensors from the LMDB cache for training', 'check whether the EQA-CNN pretrain dataset LMDB cache directory exists and contains data', 'create a NavDataset instance with config, habitat environment, and device for PACMAN navigation training', 'convert flat navigation actions into hierarchical planner and controller actions with indices', 'extract CNN image features from a numpy array or torch tensor using the pretrained MultitaskCNN encoder', 'preprocess episode actions by remapping action codes and padding to max action length for batch processing', 'map a webdataset sample to preprocessed features including planner actions, controller actions, and image features']
```

Usage

```
{'build_EQADataset': 'build a python module to create an EQADataset for embodied QA with VQA and PACMAN input types', 'create_EQADataset_init': 'create an EQADataset instance that caches episode frames to disk and builds a tar archive', 'test_group_by_keys': 'test the EQADataset group_by_keys_ method to verify webdataset sample grouping and padding', 'refactor_calc_max_length': 'refactor the EQADataset calc_max_length method to compute max question and action lengths for padding', 'review_save_frame_queue': 'review the EQADataset save_frame_queue method that renders simulator observations and saves frames as JPEGs'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/il/data/eqa_cnn_pretrain_data.py

Prompts

```
['build a python module to create an EQADataset for embodied QA with VQA and PACMAN input types', 'create an EQADataset instance that caches episode frames to disk and builds a tar archive', 'test the EQADataset group_by_keys_ method to verify webdataset sample grouping and padding', 'refactor the EQADataset calc_max_length method to compute max question and action lengths for padding', 'review the EQADataset save_frame_queue method that renders simulator observations and saves frames as JPEGs', 'create an EQACNNPretrainDataset instance from a Habitat config for train or val mode', 'save rgb, depth, and semantic segmentation frames from shortest path positions to an LMDB database', 'load a new scene into the Habitat simulator by reconfiguring the simulator with the scene path', 'retrieve an indexed batch of rgb, depth, and segmentation tensors from the LMDB cache for training', 'check whether the EQA-CNN pretrain dataset LMDB cache directory exists and contains data', 'create a NavDataset instance with config, habitat environment, and device for PACMAN navigation training', 'convert flat navigation actions into hierarchical planner and controller actions with indices', 'extract CNN image features from a numpy array or torch tensor using the pretrained MultitaskCNN encoder', 'preprocess episode actions by remapping action codes and padding to max action length for batch processing', 'map a webdataset sample to preprocessed features including planner actions, controller actions, and image features']
```

Usage

```
{'create_EQACNNPretrainDataset': 'create an EQACNNPretrainDataset instance from a Habitat config for train or val mode', 'save_frames_to_lmdb': 'save rgb, depth, and semantic segmentation frames from shortest path positions to an LMDB database', 'load_scene_in_simulator': 'load a new scene into the Habitat simulator by reconfiguring the simulator with the scene path', 'getitem_rgb_depth_seg': 'retrieve an indexed batch of rgb, depth, and segmentation tensors from the LMDB cache for training', 'check_cache_exists': 'check whether the EQA-CNN pretrain dataset LMDB cache directory exists and contains data'}
```

## File: facebookresearch_eai-vc/third_party/habitat-lab/habitat_baselines/il/data/nav_data.py

Prompts

```
['build a python module to create an EQADataset for embodied QA with VQA and PACMAN input types', 'create an EQADataset instance that caches episode frames to disk and builds a tar archive', 'test the EQADataset group_by_keys_ method to verify webdataset sample grouping and padding', 'refactor the EQADataset calc_max_length method to compute max question and action lengths for padding', 'review the EQADataset save_frame_queue method that renders simulator observations and saves frames as JPEGs', 'create an EQACNNPretrainDataset instance from a Habitat config for train or val mode', 'save rgb, depth, and semantic segmentation frames from shortest path positions to an LMDB database', 'load a new scene into the Habitat simulator by reconfiguring the simulator with the scene path', 'retrieve an indexed batch of rgb, depth, and segmentation tensors from the LMDB cache for training', 'check whether the EQA-CNN pretrain dataset LMDB cache directory exists and contains data', 'create a NavDataset instance with config, habitat environment, and device for PACMAN navigation training', 'convert flat navigation actions into hierarchical planner and controller actions with indices', 'extract CNN image features from a numpy array or torch tensor using the pretrained MultitaskCNN encoder', 'preprocess episode actions by remapping action codes and padding to max action length for batch processing', 'map a webdataset sample to preprocessed features including planner actions, controller actions, and image features']
```

Usage

```
{'create_nav_dataset': 'create a NavDataset instance with config, habitat environment, and device for PACMAN navigation training', 'convert_flat_to_hierarchical_actions': 'convert flat navigation actions into hierarchical planner and controller actions with indices', 'extract_image_features': 'extract CNN image features from a numpy array or torch tensor using the pretrained MultitaskCNN encoder', 'preprocess_navigation_actions': 'preprocess episode actions by remapping action codes and padding to max action length for batch processing', 'map_dataset_sample': 'map a webdataset sample to preprocessed features including planner actions, controller actions, and image features'}
```

